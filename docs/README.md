# OctoAcme – Documentación de Gestión de Proyectos

Este README centraliza la documentación de gestión de proyectos de OctoAcme y funciona como punto de entrada para navegar los procesos, roles y prácticas operativas del equipo.

## Resumen de procesos

OctoAcme opera con un ciclo de vida de proyecto claro y repetible: **Initiation**, **Planning**, **Execution**, **Release** y **Close/Retrospective**. En Initiation se valida la necesidad, stakeholders, métricas de éxito y decisión go/no-go; en Planning se consolida un backlog priorizado con estimaciones, Definition of Done, dependencias y plan de releases; en Execution se construye, revisa, prueba y da seguimiento; en Release se despliega de forma controlada con verificación y comunicación; y en Close/Retrospective se capturan aprendizajes para mejoras accionables.

Los artefactos típicos que sostienen este flujo incluyen el **Project One-pager/Charter**, backlog con criterios de aceptación, plan de releases, **Risk Register** y notas de retrospectiva. Este marco permite que la entrega sea iterativa y con ownership explícito de responsabilidades.

En cuanto a roles, el **Project Manager** coordina cronograma, riesgos y comunicaciones; el **Product Manager/PdM** define resultados, prioriza y mide impacto; **Developers** diseñan e implementan con pruebas y revisiones; **QA/Testing** valida calidad y criterios de aceptación; y **Stakeholders** aportan inputs y aprobaciones.

La comunicación se organiza con standups (diarios o acordados), weekly delivery sync y demos/reviews por sprint o hito, apoyada por un tablero de estado tipo **Backlog → Ready → In Progress → In Review → QA → Done**. El reporte semanal cubre progreso, próximos pasos, riesgos/bloqueos y decisiones requeridas, con escalamiento de bloqueos **equipo → PM → Product Lead → Sponsor**. En calidad, se privilegian PRs pequeños enlazados a issues con criterios de aceptación, CI con tests/lint y al menos una aprobación antes de merge, pruebas unitarias/integración, smoke tests para flujos críticos, security scanning y QA manual cuando aplica; para releases, se exige criterios cumplidos, CI OK, release notes y plan de rollback/mitigación, cerrando con retrospectivas con acciones, dueño y fecha.

## Índice de documentos

- [Visión general de gestión de proyectos](./octoacme-project-management-overview.md)
- [Initiation](./octoacme-project-initiation.md)
- [Planning](./octoacme-project-planning.md)
- [Execution and Tracking](./octoacme-execution-and-tracking.md)
- [Risks and Communication](./octoacme-risks-and-communication.md)
- [Release and Deployment](./octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
