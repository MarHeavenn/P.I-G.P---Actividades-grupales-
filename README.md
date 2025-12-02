# reporte del sprint — control de valor ganado (evm)

## 1. contexto del proyecto
- equipo: Gisee
- sprint #: 3   período: 2025-01-12 / 2025-01-12
- meta del sprint: El objetivo de este sprint es completar las actividades finales del proyecto, enfocándose en mejorar el rendimiento del asistente conversacional, implementar medidas de seguridad básicas para la protección de datos de los usuarios, avanzar en las primeras pruebas de integración con el hardware de entrada y salida de audio y preparar la documentación final requerida para la entrega del proyecto.
Durante este sprint se optimizará la fluidez del flujo conversacional y el acceso a la memoria contextual, se aplicará cifrado a la información sensible almacenada, se validará el funcionamiento inicial del módulo de voz a texto y texto a voz con el hardware disponible y se realizarán pruebas finales del sistema, junto a la generación del documento final del proyecto.

## 2. resumen ejecutivo (al corte)
- estado general: ☑ verde — criterio: se cumplieron todas las historias planificadas dentro del presupuesto.
- principales riesgos/bloqueos:  rendimiento del asistente, seguridad, integración con hardware de audio y cierre/documentación


## 3. métricas clave
- BAC total: 8,202  |  PV: 6,102 |  EV: 6,680.29  |  AC: 6,990
- SV = EV - PV: 578.29  |  CV = EV - AC: -309.71
- SPI = EV/PV: 1.0948  |  CPI = EV/AC: 0.9557
- EAC = BAC/CPI: 7,491.99  |  ETC = EAC - AC: -6,989.04

> Fuente: archivo **Plantilla-EVM-Sprint-3-Project-GISEE.xlxs** (hojas *WBS*, *Costos*, *Métricas*).

## 4. WBS y definición de hecho (DoD)
- regla de ganancia por entregable: ☑ 50/50
- evidencia mínima de DoD por tipo:
    - feature: código funcional integrado en rama principal + pruebas unitarias pasando + validación de la funcionalidad en entorno staging contra criterios de aceptación.​
    - bug: issue documentado con pasos de reproducción + test que demuestra el fallo y la corrección + commit del fix integrado en rama principal + verificación del QA marcada como                 aprobada.​
    - tech: configuración Docker versionada en repositorio + entorno levantado correctamente con esa configuración y despliegue exitoso del servicio + evidencia (logs/capturas) de que el servicio arranca y responde de forma estable

## 5. gráficos sugeridos (opcional)
- curva S (PV/EV/AC) al corte
- burnup/burndown de historias o puntos

## 6. enlaces de evidencia
- repositorio: (https://github.com/MarHeavenn/P.I-G.P---Actividades-grupales-)
- ambiente staging/producción: ______________________
- tablero (jira/linear/openproject): (https://gisee.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog)

## 7. acuerdos para el siguiente sprint
- mejoras de proceso: incluir revisión técnica cruzada antes de mergear PRs.
- cambios de alcance/prioridad: incorporar pipeline de conversación completo y conexión con memoria contextual.
---
