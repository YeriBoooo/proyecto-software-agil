# Arquitectura preliminar del proyecto

## 1. Estructura de carpetas

```text
proyecto-software-agil/
├── backend/              # API FastAPI (Python)
│   ├── app/
│   └── tests/
├── frontend/             # Interfaz Next.js
│   └── src/
├── docs/                 # Documentacion del proyecto
│   ├── arquitectura.md
│   ├── comparativa.md
│   └── manifiesto.md
├── .gitignore
└── README.md
```

Los archivos `.gitkeep` mantienen las carpetas preparadas en Git hasta que se incorporen los primeros modulos de codigo.

## 2. Flujo de arquitectura

```mermaid
flowchart LR
	Cliente[Cliente web Next.js] -->|HTTP/HTTPS| API[API FastAPI]
	API -->|SQL y migraciones| DB[(PostgreSQL)]
```

El frontend Next.js presenta la interfaz y consume la API. FastAPI concentra las reglas de negocio y expone endpoints HTTP. PostgreSQL persiste usuarios, productos, pedidos y el resto de la informacion del sistema.

## 3. Beneficios para un enfoque agil

### Separacion por capas

El frontend, la API y la base de datos tienen responsabilidades separadas. Se puede cambiar el diseno web sin reescribir la logica de negocio, siempre que se conserve el contrato de la API.

### Entregas incrementales

El equipo puede construir y probar una funcionalidad vertical completa en cada sprint: primero catalogo de productos, despues usuarios y luego ventas. Cada incremento demuestra valor real.

### Adaptacion rapida

Si cambia un requisito, se ajustan los endpoints y la interfaz en el siguiente sprint. La separacion reduce el impacto y evita rehacer toda la planificacion del sistema.

### Pruebas continuas

La API puede probarse con pruebas unitarias y de integracion, mientras el frontend valida sus componentes y flujos. La retroalimentacion llega durante el desarrollo, no solo al final.

### Menor riesgo

Si una funcionalidad se cancela o cambia, las demas capas y funcionalidades pueden seguir funcionando. Los incrementos pequenos hacen visibles antes los problemas tecnicos y de producto.

## 4. Relacion con la metodologia

Esta arquitectura se beneficia mas de un enfoque agil que de Cascada porque permite cambiar una parte del producto, entregar funcionalidades pequenas y obtener retroalimentacion temprana. Cascada sigue siendo util para requisitos estables o regulados, pero en este proyecto de comercio electronico la evolucion del mercado hace mas valioso aprender y ajustar en ciclos cortos.
