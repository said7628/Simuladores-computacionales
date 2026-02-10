# Simulador Computacional (Reto de Formación)

En esta unidad de formación enfrentarás un reto que te permitirá desarrollar las subcompetencias asignadas a este bloque y alcanzar los niveles de dominio esperados.

## Contexto: Simuladores Computacionales

Un **simulador computacional** es una herramienta de software que permite reproducir el comportamiento de un sistema real. Su aplicación abarca la gran mayoría de dominios de conocimiento: **económico, social, financiero, empresarial**, entre otros.

La reproducción del comportamiento se realiza mediante la creación de **eventos, acciones y respuestas** que imitan, con cierto nivel de fidelidad, la conducta de un sistema.

### Objetivos de un simulador
Los simuladores son creados con varios objetivos, por ejemplo:

- Mejorar el entendimiento de un problema complejo.
- Entrenar a las personas involucradas en el diseño, operación o mantenimiento de un sistema.
- Prospectar patrones de comportamientos futuros.
- Analizar el comportamiento del sistema en situaciones extremas, sin poner en riesgo el sistema real.

### Componentes principales
Los simuladores computacionales son sistemas complejos compuestos por varios módulos, entre los que destacan:

- **Módulo de base de datos:** almacena la información referente al sistema que emula.
- **Módulo de interfaz gráfica:** permite la interacción con el usuario. (Existe una categoría de videojuegos considerada como simuladores por la precisión con la que recrean sistemas complejos).
- **Módulo del motor de ejecución:** sistema central donde se ejecuta la lógica que reproduce el comportamiento del sistema emulado.

---

## Reto

Construir un **simulador computacional** que reproduzca el comportamiento **parcial** de un sistema:

- empresarial
- económico
- social
- político
- educativo

Este simulador permitirá el **análisis de escenarios actuales o futuros** para apoyar la **toma de decisiones** orientada a la mejora de procesos o componentes del sistema.

El simulador contará con una **interfaz gráfica equiparable a un videojuego 2D o 3D**.

---

## Características mínimas del sistema

El sistema debe cumplir como mínimo con:

- Arquitectura **cliente-servidor**.
- Implementación **web**.
- Capacidad de conexión a una **base de datos relacional**.
- Visualización de **indicadores de control** usando técnicas de videojuegos:
  - tableros **2D**
  - tableros **3D**
  - **múltiples cámaras**
- Enfoque en el apoyo a la toma de decisiones para solucionar un **problema específico** de una empresa (**socio formador**).

La especificación del problema a abordar se define **en conjunto con el socio formador**.

---

## Etapas del Proyecto (Ciclos)

### Ciclo 0 — Prototipo
**Preguntas guía:**
- ¿Cómo capturar y representar los requerimientos funcionales y no funcionales del reto?
- ¿Cómo crear una maqueta inicial que transmita cómo el sistema resuelve los requerimientos?

### Ciclo 1 — Integración de Base de Datos
**Preguntas guía:**
- ¿Cómo representar la estructura de información necesaria para la solución del reto?
- ¿Cómo crear un prototipo funcional inicial que cumpla con los requerimientos del reto?

### Ciclo 2 — Refinamiento del Prototipo
**Preguntas guía:**
- ¿Cómo realizar la mejora continua en el desarrollo del proyecto que soluciona el reto?

### Ciclo 3 — Entrega Final
**Preguntas guía:**
- ¿Cómo comprobar la efectividad del producto final al ser usado por el socio formador en un entorno real?

---

## Entregables

- **Ciclo 0:** Prototipo (**MockUp**) que presente las funcionalidades básicas.
- **Ciclo 1:** Integración del prototipo a la estructura de la base de datos. Conversión del MockUp a un prototipo desarrollado con capacidad de navegación por los diferentes caminos de ejecución de casos de uso.
- **Ciclo 2:** Mejora continua del prototipo para satisfacer al menos **75%** de los caminos de ejecución (**flujos de información**).
- **Ciclo 3:** Entrega final. El producto final contiene la **totalidad** de los flujos de información requeridos.

---

## Estructura sugerida del repositorio

> Ajusta esta estructura según tu stack y forma de trabajo.

```txt
/
├─ docs/               # documentación (requerimientos, mockups, diagramas, etc.)
├─ client/             # frontend web (UI estilo videojuego 2D/3D)
├─ server/             # backend (API, lógica de negocio)
├─ database/           # scripts SQL, migraciones, seeds
├─ assets/             # recursos gráficos (sprites, modelos, texturas, etc.)
├─ tests/              # pruebas (unitarias/integración)
└─ README.md
