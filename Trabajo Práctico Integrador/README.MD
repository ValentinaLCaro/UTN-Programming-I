# 🌍 World Country Management System (Python)

## 📘 Project Overview
This project is the final integrated assignment for the Programming I course at the Universidad Tecnológica Nacional (UTN). It implements a comprehensive data management system for global country information using CSV persistence and full CRUD operations.

### Core Features

A functional Python application capable of:

- **Data Lifecycle:** Add, query, update, and persist country information.

- **Algorithms:** Implementation of custom sorting and filtering algorithms.

- **Data Science Basics:** Calculation of descriptive statistics and population trends.

- **Validation:** Robust input handling, including verification against the 193 UN-recognized sovereign states.

---

## 🏛️ Academic Context
**University:** Universidad Tecnológica Nacional (UTN)

**Program:** University Technician in Programming

**Course:** Programming I

**Teaching Staff:**

- **Head Professor:** Alberto Cortez

- **Assistant Professors:** Brian Lara, Miguel Barrera

---

## 👥 Contributors
- **Valentina Caro** – Section 3  
- **Leonardo Stamile** – Section 13  

**Completion Date:** November 11, 2025

---

## 🧱 Project Structure
```
tpi_paises.py           # Main script containing application logic
paises.csv              # CSV database (automatically generated/updated)
README.md               # Project documentation
```

The application follows a modular architecture with specialized functions:
- Validations: `texto_no_vacio()`, `es_entero_positivo()`, `pais_esta_permitido()`
- CRUD operations: `agregar_pais()`, `actualizar_pais()`, `buscar_por_nombre()`
- Data Filtering: `filtrar_por_continente()`, `filtrar_por_rango_poblacion()`, `filtrar_por_rango_superficie()`
- Sorting Engines: `ordenar_por_nombre()`, `ordenar_por_poblacion()`, `ordenar_por_superficie()`
- Persistence: `cargar_desde_csv()`, `guardar_a_csv()`
- Analytics: `estadisticas()`

---

## ⚙️ Execution Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/usuario/tpi_paises.git
   cd tpi_paises
   ```

2. **Run the application:**
   ```bash
   python tpi_paises.py
   ```

3. **Interactive Menu:**
   The system features a CLI (Command Line Interface) with 12 specialized options for data manipulation and reporting:
   ```
   1) Cargar países desde CSV
   2) Guardar países a CSV
   3) Agregar país
   4) Actualizar población y superficie
   5) Buscar país por nombre
   6) Filtrar por continente
   7) Filtrar por rango de población
   8) Filtrar por rango de superficie
   9) Ordenar por nombre
   10) Ordenar por población
   11) Ordenar por superficie
   12) Mostrar estadísticas
   0) Salir
   ```

---

## 🎥 Media & Resources
- **Explainer Video:** [🔗 Enlace al video](https://youtu.be/CKHOuVgVxBQ?si=P1lqfzrKfjqCsUiD)
- **Source Code:** [🔗 Enlace al repositorio](https://github.com/ValentinaLCaro/UTN-Programming-I/tree/54a8e7e26e38fbfcf5db22ab492f5882a31460df/Trabajo%20Pr%C3%A1ctico%20Integrador)


---

## 🧩 🧩 Technologies Used
- **Language:** Python 3.10+
- **Storage:** Flat-file CSV
- **Paradigm:** Structured & Modular Programming
- **Standard Library:** `os`,`csv` 

---

## 🧾 License
This project was developed for academic purposes at UTN. All rights reserved by the authors for the original implementation.
