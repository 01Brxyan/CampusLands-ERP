**Autores:**
- Brayan Snehyder Castro Velandia
- Andres Felipe Navas Alvear

Funciona en **Linux** y **Windows**, ejecutable desde **Visual Studio Code** o la **consola**.
Al iniciarse, muestra un menú numerado que permite gestionar inscripciones, rutas de entrenamiento, matrículas, trainers, coordinadores y evaluaciones. Este sistema facilita el control académico de los campers matriculados en el programa intensivo de programación de CampusLands.

**Características principales**

* Manejo de tres roles: **Camper**, **Trainer** y **Coordinador**.
* Registro de campers con datos personales, estado y riesgo académico.
* Inscripciones y asignación de rutas como **NodeJS**, **Java** y **NetCore**.
* Creación y administración de nuevas rutas con módulos como:

  * Fundamentos de Programación (Algoritmia, PSeInt, Python).
  * Programación Web (HTML, CSS, Bootstrap).
  * Programación Formal (Java, JavaScript, C#).
  * Bases de Datos (MySQL, MongoDB, PostgreSQL).
  * Backend (NetCore, Spring Boot, NodeJS, Express).
* Control de notas con cálculo ponderado: Teórica (30%), Práctica (60%) y Quices/Trabajos (10%).
* Estados de los campers: **Inscrito**, **Aprobado**, **Cursando**, **Graduado**, **Expulsado**, **Retirado**.
* Reportes completos:

  * Campers inscritos o aprobados.
  * Campers en riesgo académico.
  * Trainers activos.
  * Relación campers/trainers por ruta.
  * Resultados de módulos aprobados y reprobados.
* Almacenamiento de datos en **JSON** para mantener persistencia y organización.

**Estructura de Archivos**

* `main.py`: Punto de entrada del sistema.
* `modules/`: Contiene la lógica del programa (operaciones, validaciones, reportes).
* `data/`: Archivos JSON para almacenamiento persistente.

**Librerías Externas**
No se utilizaron librerías externas, únicamente funciones básicas incluidas en **Python**.

