# Comparativa de Metodologías y Estudio de Casos

## 1. Cuadro comparativo

| Criterio | Metodologías tradicionales (Cascada) | Metodologías ágiles (Scrum) |
| --- | --- | --- |
| Enfoque | Predictivo y secuencial; el alcance se define al inicio. | Iterativo e incremental; se prioriza la entrega de valor. |
| Manejo de requisitos | Se especifican antes de desarrollar y los cambios se controlan formalmente. | Se aceptan cambios y se reordena el backlog según el valor para el cliente. |
| Ciclo de vida | Análisis -> diseño -> codificación -> pruebas -> implantación. | Sprints de 1 a 4 semanas con planificación, desarrollo, pruebas y revisión en cada ciclo. |
| Entrega | Normalmente una entrega al final del proyecto. | Entregas frecuentes de incrementos de software funcionando. |
| Documentación | Exhaustiva y elaborada principalmente al inicio. | Suficiente, útil y actualizada; acompaña al producto sin sustituirlo. |
| Rol del cliente | Participa sobre todo al inicio y en la aceptación final. | Colabora continuamente, valida incrementos y aporta retroalimentación. |
| Ventajas | Alta previsibilidad, fases claras y facilidad para presupuestar un alcance estable. | Adaptación rápida, valor temprano, aprendizaje continuo y detección temprana de riesgos. |
| Desventajas | Responde mal a cambios; los errores pueden descubrirse tarde y el valor llega al final. | Exige disciplina, disponibilidad del cliente y ofrece menor precisión sobre el alcance lejano. |

## 2. Estudio de casos y metodología recomendada

### Caso 1: Sistema de inventarios estable

**Descripción:** Los requisitos, usuarios y funcionalidades son conocidos y no se esperan cambios importantes.

**Recomendación:** Cascada (metodología tradicional).

**Justificación:** Es posible planificar el alcance completo y avanzar por fases secuenciales. En este escenario la previsibilidad, la documentación del alcance y el control del plan aportan más valor que la adaptación frecuente.

**Por qué no Scrum:** Las iteraciones y la reordenación continua del backlog aportarían poca ventaja cuando el producto ya está bien definido.

### Caso 2: Plataforma de comercio electronico en evolucion

**Descripción:** El mercado, la competencia y la retroalimentación de los clientes generan nuevos requisitos de manera continua.

**Recomendación:** Scrum (metodología ágil).

**Justificación:** El equipo puede entregar valor cada una o dos semanas, validar productos con usuarios y priorizar funciones como nuevos medios de pago, reportes o integraciones. El aprendizaje de cada sprint reduce el riesgo de construir un producto obsoleto.

**Por qué no Cascada:** Al terminar todas las fases, las necesidades del mercado podrían haber cambiado y el producto podría no ser competitivo.

### Caso 3: Software medico regulado

**Descripción:** Existen normas sanitarias, certificaciones, validaciones y requisitos de trazabilidad obligatorios.

**Recomendación:** Enfoque híbrido: planificación y controles tipo Cascada, con prácticas ágiles dentro de los módulos.

**Justificación:** La regulación exige requisitos controlados, evidencias, documentación y revisiones formales. A la vez, el desarrollo incremental, las pruebas continuas y las revisiones frecuentes pueden mejorar la calidad sin incumplir las obligaciones normativas.

**Por qué no un enfoque puramente ágil:** La documentación y la trazabilidad no son opcionales ni pueden dejarse para el final.

## 3. Tres principios aplicados al comercio electrónico

### Principio: Entregar software con frecuencia

Se entrega un incremento funcional al final de cada sprint de dos semanas. El primer sprint puede incluir registro y listado de productos; el segundo, carrito de compras; y el tercero, procesamiento de pedidos. El cliente valida cada incremento antes de priorizar el siguiente.

### Principio: Aceptar cambios, incluso en fases avanzadas

Si el cliente solicita una pasarela de pagos a mitad del desarrollo, el Product Owner incorpora la necesidad al backlog, la prioriza y la planifica para el siguiente sprint. El equipo adapta el plan sin desechar el catálogo ni el carrito ya construidos.

### Principio: El software funcionando es la medida principal de progreso

Una funcionalidad solo se considera terminada cuando es ejecutable, probada y demostrable. En la revisión del sprint se muestra la aplicación funcionando; una tarea documentada pero no utilizable no cuenta como incremento terminado.

## 4. Actividad complementaria: marcos ágiles

### Kanban

Visualiza el trabajo en un tablero y limita el trabajo en curso. Conviene para equipos de soporte, mantenimiento o productos con flujo continuo de solicitudes y prioridades variables.

### Extreme Programming (XP)

Prioriza la calidad técnica mediante prácticas como pruebas automatizadas, integración continua, programación en pareja y entregas pequeñas. Conviene cuando los requisitos cambian mucho y el software requiere alta confiabilidad técnica.

### Scrumban

Combina la planificación y las revisiones de Scrum con el flujo y los límites de trabajo en curso de Kanban. Conviene para equipos que necesitan conservar cierta cadencia, pero reciben incidencias o prioridades urgentes con frecuencia.
