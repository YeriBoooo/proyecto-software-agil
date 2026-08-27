# Comparativa de Metodologias y Estudio de Casos

## 1. Cuadro comparativo

| Criterio | Metodologias tradicionales (Cascada) | Metodologias agiles (Scrum) |
| --- | --- | --- |
| Enfoque | Predictivo y secuencial; el alcance se define al inicio. | Iterativo e incremental; se prioriza la entrega de valor. |
| Manejo de requisitos | Se especifican antes de desarrollar y los cambios se controlan formalmente. | Se aceptan cambios y se reordena el backlog segun el valor para el cliente. |
| Ciclo de vida | Analisis -> diseno -> codificacion -> pruebas -> implantacion. | Sprints de 1 a 4 semanas con planificacion, desarrollo, pruebas y revision en cada ciclo. |
| Entrega | Normalmente una entrega al final del proyecto. | Entregas frecuentes de incrementos de software funcionando. |
| Documentacion | Exhaustiva y elaborada principalmente al inicio. | Suficiente, util y actualizada; acompana al producto sin sustituirlo. |
| Rol del cliente | Participa sobre todo al inicio y en la aceptacion final. | Colabora continuamente, valida incrementos y aporta retroalimentacion. |
| Ventajas | Alta previsibilidad, fases claras y facilidad para presupuestar un alcance estable. | Adaptacion rapida, valor temprano, aprendizaje continuo y deteccion temprana de riesgos. |
| Desventajas | Responde mal a cambios; los errores pueden descubrirse tarde y el valor llega al final. | Exige disciplina, disponibilidad del cliente y ofrece menor precision sobre el alcance lejano. |

## 2. Estudio de casos y metodologia recomendada

### Caso 1: Sistema de inventarios estable

**Descripcion:** Los requisitos, usuarios y funcionalidades son conocidos y no se esperan cambios importantes.

**Recomendacion:** Cascada (metodologia tradicional).

**Justificacion:** Es posible planificar el alcance completo y avanzar por fases secuenciales. En este escenario la previsibilidad, la documentacion del alcance y el control del plan aportan mas valor que la adaptacion frecuente.

**Por que no Scrum:** Las iteraciones y la reordenacion continua del backlog aportarian poca ventaja cuando el producto ya esta bien definido.

### Caso 2: Plataforma de comercio electronico en evolucion

**Descripcion:** El mercado, la competencia y la retroalimentacion de los clientes generan nuevos requisitos de manera continua.

**Recomendacion:** Scrum (metodologia agil).

**Justificacion:** El equipo puede entregar valor cada una o dos semanas, validar productos con usuarios y priorizar funciones como nuevos medios de pago, reportes o integraciones. El aprendizaje de cada sprint reduce el riesgo de construir un producto obsoleto.

**Por que no Cascada:** Al terminar todas las fases, las necesidades del mercado podrian haber cambiado y el producto podria no ser competitivo.

### Caso 3: Software medico regulado

**Descripcion:** Existen normas sanitarias, certificaciones, validaciones y requisitos de trazabilidad obligatorios.

**Recomendacion:** Enfoque hibrido: planificacion y controles tipo Cascada, con practicas agiles dentro de los modulos.

**Justificacion:** La regulacion exige requisitos controlados, evidencias, documentacion y revisiones formales. A la vez, el desarrollo incremental, las pruebas continuas y las revisiones frecuentes pueden mejorar la calidad sin incumplir las obligaciones normativas.

**Por que no un enfoque puramente agil:** La documentacion y la trazabilidad no son opcionales ni pueden dejarse para el final.

## 3. Tres principios aplicados al comercio electronico

### Principio: Entregar software con frecuencia

Se entrega un incremento funcional al final de cada sprint de dos semanas. El primer sprint puede incluir registro y listado de productos; el segundo, carrito de compras; y el tercero, procesamiento de pedidos. El cliente valida cada incremento antes de priorizar el siguiente.

### Principio: Aceptar cambios, incluso en fases avanzadas

Si el cliente solicita una pasarela de pagos a mitad del desarrollo, el Product Owner incorpora la necesidad al backlog, la prioriza y la planifica para el siguiente sprint. El equipo adapta el plan sin desechar el catalogo ni el carrito ya construidos.

### Principio: El software funcionando es la medida principal de progreso

Una funcionalidad solo se considera terminada cuando es ejecutable, probada y demostrable. En la revision del sprint se muestra la aplicacion funcionando; una tarea documentada pero no utilizable no cuenta como incremento terminado.

## 4. Actividad complementaria: marcos agiles

### Kanban

Visualiza el trabajo en un tablero y limita el trabajo en curso. Conviene para equipos de soporte, mantenimiento o productos con flujo continuo de solicitudes y prioridades variables.

### Extreme Programming (XP)

Prioriza la calidad tecnica mediante practicas como pruebas automatizadas, integracion continua, programacion en pareja y entregas pequenas. Conviene cuando los requisitos cambian mucho y el software requiere alta confiabilidad tecnica.

### Scrumban

Combina la planificacion y las revisiones de Scrum con el flujo y los limites de trabajo en curso de Kanban. Conviene para equipos que necesitan conservar cierta cadencia, pero reciben incidencias o prioridades urgentes con frecuencia.
