---
Fecha de creación: 2025-08-07 19:37
Fecha de Modificación: 2025-08-07 19:37
tags: [microservicios, arquitectura, diseño, distributed-systems, api]
Tema: Arquitectura y Diseño
---

## 📚 Idea/Concepto 
- Los **Microservicios** son un estilo arquitectónico que estructura una aplicación como una colección de servicios pequeños, autónomos y débilmente acoplados. Cada microservicio es responsable de una capacidad de negocio específica, se despliega independientemente, maneja su propia base de datos y se comunica con otros servicios a través de APIs bien definidas (típicamente REST o mensajería). Esta arquitectura permite escalabilidad independiente, desarrollo paralelo por equipos diferentes, uso de tecnologías heterogéneas y despliegues más frecuentes. Contrasta con la arquitectura monolítica donde toda la aplicación es una unidad única.

## 📌 Puntos Claves (Opcional)
- **Servicios independientes**: Cada microservicio es una unidad desplegable independientemente
- **Responsabilidad única**: Un servicio = una capacidad de negocio específica (bounded context)
- **Comunicación por API**: REST, GraphQL, gRPC o mensajería asíncrona (eventos)
- **Base de datos por servicio**: Cada servicio gestiona sus propios datos (no shared database)
- **Tolerancia a fallos**: Un servicio caído no debe tumbar todo el sistema
- **Tecnología heterogénea**: Cada servicio puede usar diferente stack tecnológico
- **Complejidad operacional**: Requiere orquestación, service discovery, monitoring distribuido
- **Patrones asociados**: API Gateway, Circuit Breaker, Service Mesh, Event Sourcing, CQRS

## 🔗 Connections
- [[Requerimientos No Funcionales]] - Microservicios abordan escalabilidad y disponibilidad
- [[Azure DevOps]] - Plataforma para CI/CD de microservicios
- [[Monitoreo de Aplicación]] - Crítico en arquitecturas distribuidas
- [[Definition of Done (DoD)]] - Incluye criterios específicos para microservicios
- [[User Story]] - Cada microservicio implementa capacidades de negocio específicas
- [[Sprint Backlog]] - Trabajo puede dividirse por microservicio
- [[Product Backlog]] - Features pueden mapearse a microservicios específicos
- [[Estándares de Programación]] - Cada microservicio debe seguir estándares consistentes

## 💡 Personal Insight (Opcional)
- Microservicios no son la solución para todo. Son excelentes para escalar equipos y sistemas grandes, pero añaden complejidad significativa. La regla de oro: empieza con un monolito bien estructurado y evoluciona a microservicios cuando el dolor lo justifique. El mayor desafío no es técnico sino organizacional: Conway's Law es real. Los anti-patterns más comunes son: microservicios demasiado pequeños (nanoservicios), compartir bases de datos, y no invertir en tooling/observabilidad. Sin DevOps maduro, microservicios es una receta para el desastre.

## 🧾 Recursos (Opcional)
- "Building Microservices" por Sam Newman
- "Microservices Patterns" por Chris Richardson
- Martin Fowler's Microservices Articles
- Netflix OSS Stack (Eureka, Hystrix, Zuul)
- Herramientas: Docker, Kubernetes, Istio, Kong API Gateway