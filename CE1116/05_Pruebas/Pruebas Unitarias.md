---
Fecha de creación: 2025-08-07 19:37
Fecha de Modificación: 2025-08-07 19:37
tags: [pruebas-unitarias, unit-testing, tdd, testing, calidad]
Tema: Pruebas
---

## 📚 Idea/Concepto 
- Las **Pruebas Unitarias** son tests automatizados que verifican el comportamiento de unidades individuales de código (típicamente funciones, métodos o clases) de forma aislada. Prueban la lógica más pequeña y específica del código, usando mocks o stubs para aislar dependencias externas. Son rápidas de ejecutar, fáciles de escribir y proporcionan feedback inmediato sobre la correctitud del código. Forman la base de la pirámide de testing y son fundamentales para el desarrollo ágil, permitiendo refactoring seguro y desarrollo guiado por pruebas (TDD). Deben ser independientes, repetibles y determinísticas.

## 📌 Puntos Claves (Opcional)
- **Aislamiento**: Prueban una unidad de código sin dependencias externas
- **Rápidas**: Milisegundos de ejecución, permiten feedback inmediato
- **Principio FIRST**: Fast, Independent, Repeatable, Self-validating, Timely
- **AAA Pattern**: Arrange (preparar), Act (ejecutar), Assert (verificar)
- **Coverage**: Métrica de qué porcentaje del código está cubierto por tests
- **Mocking**: Simular dependencias externas (bases de datos, APIs, servicios)
- **TDD**: Test-Driven Development - escribir tests antes del código
- **Regresión**: Previenen que cambios rompan funcionalidad existente

## 🔗 Connections
- [[Pruebas Funcionales]] - Las pruebas unitarias son la base para pruebas de mayor nivel
- [[Definition of Done (DoD)]] - DoD incluye pruebas unitarias pasando
- [[Estándares de Programación]] - Tests siguen estándares de código
- [[Sprint Backlog]] - Escribir tests es parte del trabajo del Sprint
- [[User Story]] - Cada historia debe tener pruebas unitarias
- [[Velocity]] - Tests automatizados aceleran el desarrollo a largo plazo
- [[Azure DevOps]] - Ejecuta pruebas unitarias en CI/CD
- [[Requerimientos Funcionales]] - Cada requerimiento debe tener tests asociados

## 💡 Personal Insight (Opcional)
- Las pruebas unitarias son como un seguro: parecen un gasto innecesario hasta que las necesitas. El valor real no está en encontrar bugs (aunque lo hacen), sino en permitir cambios con confianza. TDD no es sobre testing, es sobre diseño: código testeable es código bien diseñado. El error más común es escribir tests después "si hay tiempo" - nunca lo hay. Mi filosofía: si no está testeado, no está terminado. El código legacy es simplemente código sin tests. La métrica de coverage es útil pero engañosa: 100% coverage no significa 0% bugs. Enfócate en testear comportamiento, no implementación.

## 🧾 Recursos (Opcional)
- "Test Driven Development" por Kent Beck
- "The Art of Unit Testing" por Roy Osherove
- "Working Effectively with Legacy Code" por Michael Feathers
- Frameworks: JUnit, NUnit, pytest, Jest, Mocha, RSpec
- Herramientas: Mockito, Sinon, Test doubles, Coverage tools