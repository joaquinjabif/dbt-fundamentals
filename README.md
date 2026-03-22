# ⚡ dbt Fundamentals: Analytics Engineering Project

![dbt Badge](https://img.shields.io/badge/dbt-Certified_Fundamentals-orange?style=for-the-badge&logo=dbt)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

Este repositorio contiene el proyecto desarrollado durante la certificación **dbt Fundamentals** de dbt Labs. El objetivo fue transformar datos crudos en un modelo analítico profesional aplicando buenas prácticas de ingeniería de software al mundo de los datos.

## 🎯 Objetivos del Proyecto
* Implementar un flujo de **Analytics Engineering** utilizando dbt Cloud.
* Transformar datos relacionales en un **Esquema Estrella (Star Schema)** optimizado para BI.
* Asegurar la calidad de los datos mediante **Tests Automatizados** y documentación técnica integrada.

## 🏗️ Arquitectura y Stack Técnico
* **Data Warehouse:** Snowflake (Carga de datos crudos).
* **Transformación:** dbt (Data Build Tool).
* **Lenguajes:** SQL (CTEs, Joins complejos) y Jinja (Lógica dinámica).
* **Control de Versiones:** Git & GitHub.

## 🛠️ Características Implementadas
* **Modelado por Capas:** Creación de tablas de staging y modelos finales (Marts) siguiendo la arquitectura modular de dbt.
* **Testing:** Implementación de tests de unicidad, no nulidad y relaciones para garantizar integridad referencial.
* **Documentación:** Generación de linaje de datos y descripciones de columnas mediante archivos YAML.
* **Materialización:** Configuración de tablas y vistas eficientes en el Data Warehouse.

## 📈 Impacto
Con este enfoque, logré reducir la deuda técnica que suelen generar los scripts de SQL sueltos, permitiendo que la lógica de negocio sea auditable, testeable y fácil de escalar para herramientas de visualización como Power BI.

---
*Proyecto realizado por Joaquín Jabif | Estudiante de Ingeniería en Sistemas (UTN)*
