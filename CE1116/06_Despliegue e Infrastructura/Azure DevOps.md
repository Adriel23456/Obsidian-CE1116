---
Fecha de creación: 2025-08-07 19:37
Fecha de Modificación: 2025-08-07 19:37
tags: [azure-devops, cicd, devops, deployment, infrastructure]
Tema: Despliegue e Infraestructura
---

## 📚 Idea/Concepto 
- **Azure DevOps** es una plataforma integral de Microsoft que proporciona servicios para planificación, desarrollo colaborativo, entrega y operación de software. Combina Azure Boards (gestión de trabajo ágil), Azure Repos (control de versiones Git), Azure Pipelines (CI/CD), Azure Test Plans (testing) y Azure Artifacts (gestión de paquetes). Permite implementar prácticas DevOps end-to-end, automatizando el ciclo de vida completo del desarrollo desde la planificación hasta el monitoreo en producción. Soporta cualquier lenguaje, plataforma y nube, integrándose con herramientas populares del ecosistema DevOps.

## 📌 Puntos Claves (Opcional)
- **Azure Boards**: Kanban boards, backlogs, sprints, dashboards para gestión ágil
- **Azure Repos**: Repositorios Git privados ilimitados con pull requests y políticas de branch
- **Azure Pipelines**: CI/CD con YAML o diseñador visual, agentes hosted o self-hosted
- **Azure Test Plans**: Gestión de pruebas manuales y exploratorias
- **Azure Artifacts**: Feed de paquetes para NuGet, npm, Maven, Python
- **Integración**: Con VS Code, Visual Studio, Jenkins, Slack, Teams
- **Infrastructure as Code**: Soporte para ARM templates, Terraform, Ansible
- **Seguridad**: Políticas de branch, code scanning, gestión de secretos

## 🔗 Connections
- [[Sprint Backlog]] - Azure Boards gestiona el backlog del Sprint
- [[Taskboard]] - Implementado en Azure Boards
- [[Product Backlog]] - Gestionado en Azure Boards
- [[Velocity]] - Métricas y reportes en Azure Boards
- [[Pruebas Unitarias]] - Ejecutadas automáticamente en Azure Pipelines
- [[Microservicios]] - Despliegue independiente via Azure Pipelines
- [[Definition of Done (DoD)]] - Pipelines validan automáticamente DoD
- [[Estándares de Programación]] - Enforced por políticas y pipelines
- [[Monitoreo de Aplicación]] - Integración con Azure Monitor y Application Insights

## 💡 Personal Insight (Opcional)
- Azure DevOps es como un Swiss Army knife para equipos de desarrollo. Su mayor fortaleza es la integración: todo en un lugar, desde el backlog hasta el deployment. El desafío es no perderse en la cantidad de features. Mi consejo: empieza simple con Boards y Repos, luego añade Pipelines gradualmente. Los YAML pipelines son más poderosos que el diseñador visual pero tienen curva de aprendizaje. La magia real está en los gates y approvals automáticos que previenen deployments problemáticos. No subestimes Azure Artifacts; un feed de paquetes privado bien gestionado ahorra muchísimos dolores de cabeza.

## 🧾 Recursos (Opcional)
- Azure DevOps Documentation (docs.microsoft.com/azure/devops)
- "The DevOps Handbook" por Kim, Humble, Debois y Willis
- Azure DevOps Labs (azuredevopslabs.com)
- Certificación: Azure DevOps Engineer Expert (AZ-400)
- Templates: Azure Pipeline YAML templates repository