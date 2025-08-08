---
Fecha de creación: 2025-08-07 19:37
Fecha de Modificación: 2025-08-07 19:37
tags: [pruebas-funcionales, testing, qa, calidad, pruebas]
Tema: Pruebas
---

## 📚 Idea/Concepto 
- Las **Pruebas Funcionales** son un tipo de testing que valida que el software funciona según los requerimientos funcionales especificados, verificando que cada función del sistema opera de acuerdo con los criterios de aceptación definidos. Se enfocan en el "qué" hace el sistema, no en "cómo" lo hace (caja negra), probando la aplicación desde la perspectiva del usuario final. Incluyen pruebas de unidad, integración, sistema y aceptación del usuario (UAT). Las pruebas funcionales aseguran que todas las funcionalidades entregan el valor esperado y son fundamentales para la calidad del producto.

## 📌 Puntos Claves (Opcional)
- **Caja negra**: Se prueban entradas y salidas sin conocer la implementación interna
- **Basadas en requerimientos**: Cada prueba valida uno o más requerimientos funcionales
- **Niveles de prueba**: Unit testing, Integration testing, System testing, UAT
- **Casos de prueba**: Escenarios específicos con datos de entrada y resultados esperados
- **Automatización**: Muchas pruebas funcionales pueden y deben automatizarse
- **Criterios de aceptación**: Base para diseñar pruebas funcionales
- **Regresión**: Aseguran que nuevas funcionalidades no rompen las existentes
- **Coverage**: Métricas de cuántos requerimientos están cubiertos por pruebas

## 🔗 Connections
- [[Requerimientos Funcionales]] - Lo que validan las pruebas funcionales
- [[User Story]] - Los criterios de aceptación definen las pruebas
- [[Definition of Done (DoD)]] - Incluye que las pruebas funcionales pasen
- [[Sprint Backlog]] - Pruebas como parte del trabajo del Sprint
- [[Requerimientos No Funcionales]] - Se complementan con pruebas no funcionales
- [[Product Owner]] - Valida pruebas de aceptación del usuario
- [[Velocity]] - Solo se cuenta trabajo con pruebas pasando
- [[Stakeholder]] - Participan en UAT

## 💡 Personal Insight (Opcional)
- Las pruebas funcionales son la red de seguridad del desarrollo. Sin ellas, cada cambio es un salto al vacío. La clave está en el balance: suficientes pruebas para tener confianza, pero no tantas que ralenticen el desarrollo. El test más valioso es el que encuentra un bug que hubiera llegado a producción. Mi filosofía: si un bug llega a producción, escribo una prueba para que nunca vuelva a ocurrir. Las pruebas automatizadas son una inversión que paga dividendos cada vez que se ejecutan. El mejor momento para escribir una prueba es antes de escribir el código (TDD).

## 🧾 Recursos (Opcional)
- "The Art of Software Testing" por Glenford Myers
- "Test Driven Development" por Kent Beck
- ISTQB Foundation Level Syllabus
- Herramientas: Selenium, Cypress, Jest, JUnit, Postman, TestRail