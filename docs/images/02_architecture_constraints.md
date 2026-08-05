# 2. Restricciones de la Arquitectura

## 2.1 Restricciones Técnicas
| Decisión | Justificación |
|---|---|
| Backend: Java con Spring Boot | Robustez, ecosistema maduro, equipo con experiencia previa |
| Base de datos: PostgreSQL | Open source, soporte transaccional ACID, buen manejo relacional |
| Frontend: SPA con React | Experiencia de usuario fluida, amplio soporte de componentes |
| Arquitectura: Monolito modular | Alcance del proyecto no justifica la complejidad operativa de microservicios |
| Comunicación: REST/JSON | Estándar, simple de consumir desde el frontend |

## 2.2 Restricciones Organizacionales
- Equipo de 3-4 desarrolladores con tiempo limitado (proyecto académico).
- Entrega por sprints, siguiendo metodología Scrum.
- Repositorio único en GitHub para código y documentación.

## 2.3 Convenciones
- Código versionado en GitHub siguiendo Gitflow simplificado (main/develop/feature).
- Documentación de arquitectura en formato arc42 + diagramas C4 con PlantUML.
