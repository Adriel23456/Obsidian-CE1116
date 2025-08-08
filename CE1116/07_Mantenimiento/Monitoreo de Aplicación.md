---
Fecha de creación: 2025-08-07 19:37
Fecha de Modificación: 2025-08-07 19:37
tags: [monitoreo, observabilidad, apm, mantenimiento, metricas]
Tema: Mantenimiento
---

## 📚 Idea/Concepto 
- El **Monitoreo de Aplicación** es la práctica de observar, medir y analizar continuamente el comportamiento, rendimiento y disponibilidad de aplicaciones en producción. Incluye la recolección de métricas (CPU, memoria, latencia), logs (eventos y errores), y traces (flujo de requests) para proporcionar visibilidad completa del sistema. El monitoreo moderno se basa en los tres pilares de la observabilidad: métricas, logs y trazas distribuidas. Permite detectar problemas proactivamente, diagnosticar incidentes rápidamente, optimizar el rendimiento y tomar decisiones basadas en datos sobre la salud y uso de la aplicación.

## 📌 Puntos Claves (Opcional)
- **Tres pilares de observabilidad**: Métricas (qué), Logs (por qué), Traces (cómo)
- **Métricas clave**: Response time, throughput, error rate, saturation (USE/RED methods)
- **APM (Application Performance Monitoring)**: Monitoreo especializado de aplicaciones
- **Alertas inteligentes**: Basadas en umbrales, anomalías o predicciones
- **Dashboards**: Visualización en tiempo real del estado del sistema
- **SLI/SLO/SLA**: Indicadores, objetivos y acuerdos de nivel de servicio
- **Monitoreo sintético**: Pruebas automatizadas simulando usuarios
- **Real User Monitoring (RUM)**: Datos de experiencia de usuarios reales

## 🔗 Connections
- [[Requerimientos No Funcionales]] - Monitoreo valida NFRs como performance y disponibilidad
- [[Azure DevOps]] - Integración con Application Insights y Azure Monitor
- [[Microservicios]] - Requieren monitoreo distribuido y correlación de traces
- [[Definition of Done (DoD)]] - Incluye configuración de monitoreo
- [[Pruebas Funcionales]] - Monitoreo detecta issues que escapan a las pruebas
- [[Velocity]] - Métricas de deployment frequency y lead time
- [[Stakeholder]] - Dashboards para visibilidad del negocio
- [[Product Owner]] - Usa métricas para decisiones de producto

## 💡 Personal Insight (Opcional)
- El monitoreo es como tener superpoderes en producción: puedes ver lo invisible. La diferencia entre un equipo que reacciona y uno que es proactivo está en su cultura de observabilidad. No se trata solo de saber cuándo algo falla, sino de entender el comportamiento normal para detectar anomalías sutiles. El error más común es sobre-alertar: alert fatigue mata la efectividad. Menos alertas críticas bien calibradas valen más que cientos de warnings ignorados. Mi filosofía: si no está monitoreado, no existe. Los logs son para debugging, las métricas para alerting, los traces para entender. Invierte en buenos dashboards; son la ventana a tu sistema.

## 🧾 Recursos (Opcional)
- "Site Reliability Engineering" por Google
- "Observability Engineering" por Charity Majors
- Herramientas: Prometheus + Grafana, ELK Stack, Application Insights, New Relic, Datadog
- Metodologías: USE Method, RED Method, Four Golden Signals
- OpenTelemetry - Estándar para observabilidad