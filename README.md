# Proyecto Software Ágil

Repositorio de la práctica de Ingeniería de Software II sobre metodologías ágiles, metodologías tradicionales y el Manifiesto Ágil.

## Objetivo

Comparar los enfoques tradicional y ágil, analizar su aplicación en distintos proyectos de software y relacionar los valores y principios del Manifiesto Ágil con una plataforma de comercio electrónico.

## Alcance de esta práctica

Esta entrega define la documentación y la arquitectura preliminar del proyecto. No incluye todavía la implementación de la API FastAPI ni de la interfaz Next.js; esas carpetas quedan preparadas para futuras guías.

## Estructura

- `backend/`: Estructura prevista para una API con FastAPI.
- `frontend/`: Estructura prevista para una interfaz con Next.js.
- `docs/`: Documentación y análisis de la práctica.

## Arquitectura preliminar

```text
Cliente Next.js
       |
       v
API FastAPI
       |
       v
Base de Datos PostgreSQL
```

La separación por capas permite entregar funcionalidades incrementales, probar cada componente y adaptar el producto a la retroalimentación del cliente. La explicación completa está en [docs/arquitectura.md](docs/arquitectura.md).

## Documentación

- [Comparativa de metodologías](docs/comparativa.md)
- [Manifiesto Ágil](docs/manifiesto.md)
- [Arquitectura del sistema](docs/arquitectura.md)

La documentación incluye el cuadro comparativo, el análisis de tres casos, la aplicación de tres principios ágiles, las respuestas de análisis y la actividad complementaria sobre Kanban, XP y Scrumban.

## Integrantes

- Geraldine Daniela Rojas Villegas
- David Adrian Lucano Nieves

## Repositorio

[github.com/YeriBoooo/proyecto-software-agil](https://github.com/YeriBoooo/proyecto-software-agil)