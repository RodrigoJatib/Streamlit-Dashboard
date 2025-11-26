# Product Analytics Dashboard (Streamlit) / Dashboard de Analítica de Productos

This repository contains a **product analytics dashboard** built with Python and Streamlit.  
It loads a product dataset (e.g. categories, prices, stock levels, and sales) and lets the user explore the data through interactive filters, summary KPIs, and visualizations.

Este repositorio contiene un **dashboard de analisis de productos** desarrollado con Python y Streamlit.  
Carga un conjunto de datos de productos (por ejemplo: categorías, precios, niveles de stock y ventas) y permite explorar la información mediante filtros interactivos, KPIs de resumen y visualizaciones.

---

## Features / Funcionalidades

**EN**

- Load a CSV dataset with product information.
- Filter data by:
  - Product category
  - Date range (if available in the dataset)
  - Price range / stock range
- Summary KPIs, for example:
  - Total number of products
  - Total sales / revenue
  - Average price
  - Average stock
- Visualizations:
  - Bar chart: sales or quantity by category
  - Line chart: sales over time
  - Tables with sortable and filterable data

**ES**

- Carga de un dataset en formato CSV con información de productos.
- Filtros sobre los datos:
  - Categoría de producto
  - Rango de fechas (si el dataset lo incluye)
  - Rango de precio / stock
- KPIs de resumen, por ejemplo:
  - Cantidad total de productos
  - Ventas / ingresos totales
  - Precio promedio
  - Stock promedio
- Visualizaciones:
  - Gráfico de barras: ventas o cantidad por categoría
  # Product Analytics Dashboard (Streamlit) / Dashboard de Analítica de Productos

  This repository contains a **product analytics dashboard** built with Python and Streamlit. It loads a product dataset (for example: categories, prices, stock levels, and sales) and lets the user explore the data through interactive filters, summary KPIs, and visualizations.

  Este repositorio contiene un **dashboard de análisis de productos** desarrollado con Python y Streamlit. Carga un conjunto de datos de productos (por ejemplo: categorías, precios, niveles de stock y ventas) y permite explorar la información mediante filtros interactivos, KPIs de resumen y visualizaciones.

  ---

  ## Features / Funcionalidades

  **EN**

  - Load a CSV dataset with product information.
  - Filter data by:
    - Product category
    - Date range (if available in the dataset)
    - Price range / stock range
  - Summary KPIs, for example:
    - Total number of products
    - Total sales / revenue
    - Average price
    - Average stock
  - Visualizations:
    - Bar chart: sales or quantity by category
    - Line chart: sales over time
    - Tables with sortable and filterable data

  **ES**

  - Carga de un dataset en formato CSV con información de productos.
  - Filtros sobre los datos:
    - Categoría de producto
    - Rango de fechas (si el dataset lo incluye)
    - Rango de precio / stock
  - KPIs de resumen, por ejemplo:
    - Cantidad total de productos
    - Ventas / ingresos totales
    - Precio promedio
    - Stock promedio
  - Visualizaciones:
    - Gráfico de barras: ventas o cantidad por categoría
    - Gráfico de líneas: ventas a lo largo del tiempo
    - Tablas con datos filtrados y ordenables

  ---

  ## Tech Stack / Tecnologías Utilizadas

  **EN**

  - **Language:** Python 3.x
  - **Framework:** Streamlit
  - **Data processing:** pandas
  - **Visualization:** Streamlit charts (and/or matplotlib / plotly, depending on the implementation)

  **ES**

  - **Lenguaje:** Python 3.x
  - **Framework:** Streamlit
  - **Procesamiento de datos:** pandas
  - **Visualización:** componentes de gráficos de Streamlit (y/o matplotlib / plotly, según la implementación)

  ---

  ## Getting Started / Puesta en Marcha

  ### 1. Clone the repository / Clonar el repositorio

  ```bash
  git clone https://github.com/RodrigoJatib/Streamlit-Dashboard.git
  cd Streamlit-Dashboard
  ```

  ### 2. Crear y activar un entorno virtual (opcional)

  Windows (PowerShell):

  ```pwsh
  python -m venv .venv
  .\.venv\Scripts\Activate.ps1
  ```

  Windows (CMD):

  ```cmd
  python -m venv .venv
  .venv\Scripts\activate
  ```

  Linux / macOS:

  ```bash
  python -m venv .venv
  source .venv/bin/activate
  ```

  ### 3. Install dependencies / Instalar dependencias

  If you use `requirements.txt` / Si usás `requirements.txt`:

  ```bash
  pip install -r requirements.txt
  ```

  Basic example / Ejemplo básico:

  ```bash
  pip install streamlit pandas
  ```

  ### 4. Run the app / Ejecutar la aplicación

  ```bash
  streamlit run dashboard.py
  ```

  Open the URL shown in the terminal (usually http://localhost:8501).

  Usage / Uso

  Run `streamlit run dashboard.py`.

  Upload your own CSV file or use the sample datasets in the repository (e.g. `gaseosas.csv`, `vinos.csv`).

  Use the sidebar filters (category, date, price, etc.) to slice the data.

  Explore KPIs, charts, and tables to analyze product behavior.

  Future Improvements / Mejoras Futuras

  - Add authentication (login) to separate user workspaces.
  - Export filtered data and charts to PDF or Excel.
  - Add more advanced KPIs (margins, profitability, stock turnover).
  - Connect to a real database instead of using CSV files.

  Credits / Créditos

  Developed by Rodrigo Gabriel Jatib as part of a university project and refined as a portfolio project.
