# Patrones de Diseño — Diseño Orientado a Objetos (UCC)

Repositorio de la materia **Diseño Orientado a Objetos / Patrones de Diseño** (Universidad Cooperativa de Colombia). Reúne los ejercicios de clase de modelado UML con **Enterprise Architect** y **PowerDesigner**, generación de código, ingeniería inversa y la implementación de los patrones creacionales.

Autor: **Erick Collin Albornoz** ([@erickcolin2005](https://github.com/erickcolin2005))

---

## 📁 Estructura del repositorio

| Carpeta | Contenido |
|---|---|
| [`modelado-uml/`](modelado-uml) | Ejercicios de modelado UML (Enterprise Architect + PowerDesigner) |
| [`generacion-codigo-java/`](generacion-codigo-java) | Modelos con generación de código Java |
| [`ingenieria-inversa/`](ingenieria-inversa) | Proyectos analizados mediante ingeniería inversa |
| [`patrones-creacionales/`](patrones-creacionales) | Implementación de los 5 patrones creacionales |
| [`ejercicios/`](ejercicios) | Ejercicios varios |

> Las carpetas de ejercicios usan el formato de fecha `AAAA-MM-DD` para ordenarse cronológicamente.

---

## 🧩 Modelado UML

Ejercicios de diagramas de clases, objetos y secuencia.

| Fecha | Ejercicio | Herramienta |
|---|---|---|
| 2024-09-06 | [PowerDesigner — básico (modelo avión)](modelado-uml/2024-09-06-powerdesigner-basico) | PowerDesigner |
| 2024-09-13 | [Sistema de Apuestas](modelado-uml/2024-09-13-apuesta) | PowerDesigner |
| 2024-10-18 | [Sistema de Apuestas (Enterprise Architect)](modelado-uml/2024-10-18-apuesta-enterprise) | Enterprise Architect |
| 2024-10-25 | [LogicPremiar](modelado-uml/2024-10-25-logicpremiar) | Enterprise Architect |
| 2024-10-25 | [Transipiales — pasajes intermunicipales](modelado-uml/2024-10-25-transipiales) | EA + PowerDesigner |
| 2024-11-01 | [Apuesta — diagrama de secuencia](modelado-uml/2024-11-01-apuesta-secuencia) | Enterprise Architect |
| 2024-11-02 | [Sistema de Alquiler de Vehículos](modelado-uml/2024-11-02-sistema-alquiler-vehiculos) | EA + PowerDesigner |
| 2024-11-02 | [Sistema de Gestión Hospitalaria](modelado-uml/2024-11-02-sistema-gestion-hospital) | EA + PowerDesigner |
| 2024-11-07 | [Sistema E-commerce](modelado-uml/2024-11-07-sistema-ecommerce) | EA + PowerDesigner |
| 2024-11-07 | [Sistema de Gestión de Montaña Rusa](modelado-uml/2024-11-07-sistema-montana-rusa) | EA + PowerDesigner |
| 2024-11-07 | [Sistema de Reservas de Hoteles](modelado-uml/2024-11-07-sistema-reservas-hoteles) | EA + PowerDesigner |
| 2024-11-20 | [Bancario / Seguros / Vuelos](modelado-uml/2024-11-20-bancario-seguros-vuelos) | Enterprise Architect |

## ☕ Generación de código Java

Modelos UML con generación automática de código fuente Java.

| Fecha | Ejercicio |
|---|---|
| 2024-11-15 | [Sistema de Restaurante](generacion-codigo-java/2024-11-15-sistema-restaurante) |
| 2024-11-15 | [Sistema de Seguridad](generacion-codigo-java/2024-11-15-sistema-seguridad) |

## 🔄 Ingeniería inversa

Proyectos existentes analizados para reconstruir su modelo:

- [CalculatorDesktop](ingenieria-inversa/CalculatorDesktop)
- [fastapi_mongodb](ingenieria-inversa/fastapi_mongodb)
- [spring-framework-petclinic](ingenieria-inversa/spring-framework-petclinic)
- [springboot-postgresql-hibernate-crud-example](ingenieria-inversa/springboot-postgresql-hibernate-crud-example)

## 🏗️ Patrones creacionales

Proporcionan mecanismos de creación de objetos que aumentan la flexibilidad y reutilización del código. Cada patrón incluye su código de ejemplo y diagrama.

- [Factory Method](patrones-creacionales/Factory%20Method)
- [Abstract Factory](patrones-creacionales/Abstract%20Factory)
- [Builder](patrones-creacionales/Builder)
- [Prototype](patrones-creacionales/Prototype)
- [Singleton](patrones-creacionales/Singleton)

---

## 🛠️ Herramientas

- **Enterprise Architect** — archivos `.EAP` (diagramas de clases, objetos y secuencia)
- **PowerDesigner** — archivos `.pdm`, `.pdb`, `.oom`, `.oob`
- **Java** — código generado a partir de los modelos

## 📚 Referencias

- [Refactoring.Guru — Patrones de diseño](https://refactoring.guru/es/design-patterns)
- *Sumérgete en los Patrones de Diseño* — Alexander Shvets
