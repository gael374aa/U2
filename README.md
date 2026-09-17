# Práctica de Manipulación de Bases de Datos con SQLite3 y Pandas

Este repositorio contiene el desarrollo y reporte de la Unidad I para la materia Taller de Bases de Datos de la carrera de Ingeniería en Sistemas Computacionales en el Instituto Tecnológico Superior de Misantla.

---

## Acerca del Proyecto

El objetivo de esta práctica es implementar y manipular bases de datos relacionales en memoria mediante un entorno Python (Jupyter Notebook / Google Colab).

A lo largo del proyecto se abordan las operaciones fundamentales del ciclo de vida de las bases de datos relacionales (CRUD) a través de tres escenarios prácticos:
1. **Restaurante (`comida`):** Gestión de menú, precios y disponibilidad.
2. **Escuela (`alumnos`):** Control académico, notas y promedios.
3. **Tienda Escolar (`productos`):** Inventario de productos, aplicabilidad de descuentos y categorización.

---

## Tecnologías y Herramientas

* **Lenguaje:** Python 3
* **Base de Datos:** SQLite3 (en memoria `:memory:`)
* **Librerías:**
  * `sqlite3`: Para la ejecución de sentencias DDL, DML y DQL.
  * `pandas`: Para el procesamiento y visualización estructurada de consultas (`SELECT`) en DataFrames.
* **Entorno:** Google Colab / Jupyter Notebook

---

## Conceptos Aplicados

- **DDL (Data Definition Language):** Creación y depuración de tablas (`CREATE TABLE`, `DROP TABLE`) con restricciones (`PRIMARY KEY`, `AUTOINCREMENT`, `NOT NULL`, etc.).
- **DML (Data Manipulation Language):** Inserción, actualización y borrado de registros (`INSERT INTO`, `UPDATE`, `DELETE`) con filtros condicionales (`WHERE`).
- **DQL (Data Query Language):** Consultas e inspección de datos (`SELECT`) integradas con `pandas`.

---

## Estructura del Repositorio

* `ejercicio_create_table.py` / `.ipynb`: Código fuente en Python/Notebook con las consultas SQL ejecutadas.
* `Reporte_Practica.pdf`: Documento con el reporte detallado (Introducción, Desarrollo de secciones y Conclusiones).

---

## Enlace al Notebook

Puedes acceder directamente al entorno ejecutable en Google Colab desde aquí:  
[Abrir Notebook en Google Colab](https://colab.research.google.com/drive/13iOl8hI6o_g7FjyWtilAORThRUfyB5ci?usp=sharing)

---

## Autor

* **Alumno:** Agustin Gael Grijalva Martínez
* **Materia:** Taller de Base de Datos
* **Docente:** Irahan Otoniel José Guzmán
* **Institución:** Instituto Tecnológico Superior de Misantla