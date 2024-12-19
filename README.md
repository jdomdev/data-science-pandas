# Prácticas de Ciencia de Datos con Pandas

Este repositorio contiene **notebooks en Jupyter (`.ipynb`)** desarrollados durante un curso especializado en Ciencia de Datos, utilizando la biblioteca **Pandas**. Las prácticas se realizaron en **entornos virtuales gestionados con Anaconda**, lo que garantiza un entorno controlado y reproducible para el aprendizaje y experimentación.

---

## 📚 Temario del Curso

### **Módulo 7: Preprocesamiento y Limpieza de Datos con Numpy y Pandas**

#### **Parte I: Fundamentos y Técnicas Básicas**
1. **Fundamentos de Numpy**
   - Introducción y operaciones básicas.
2. **Introducción al Data Wrangling y Preprocesamiento de Datos**
   - Herramientas y entorno de trabajo en Python.
3. **Manipulación de Datos con Pandas**
   - **Estructuras de datos**: Series y DataFrame.
   - **Lectura y escritura de datos**: Archivos CSV, Excel, JSON, entre otros.
   - **Filtrado y selección**: Operaciones para trabajar con DataFrames.
   - **Limpieza de datos básica**:
     - Identificación y manejo de valores atípicos.
     - Estrategias para tratar valores faltantes.
4. **Procesamiento de Datos Avanzado con Pandas**
   - Agrupación y agregación.
   - Combinación y unión de DataFrames.
   - Manejo de datos categóricos y extracción de texto.
   - Técnicas avanzadas para valores atípicos y faltantes.

#### **Parte II: Procesamiento Avanzado y Rendimiento**
1. **Procesamiento de Datos Temporales y Geoespaciales**
   - Análisis de series temporales con Pandas.
   - Introducción a GeoPandas para análisis geoespacial.
2. **Optimización y Rendimiento**
   - Técnicas de optimización en el wrangling de datos.
   - Uso de concurrencia y paralelismo.

---

## 📂 Estructura del Repositorio

- **notebooks/**: Contiene los notebooks clasificados por tema.
  - `fundamentos_numpy.ipynb`: Operaciones básicas y fundamentos de Numpy.
  - `wrangling_basico.ipynb`: Introducción al preprocesamiento y limpieza de datos.
  - `pandas_avanzado.ipynb`: Técnicas avanzadas de Pandas, como agrupación, unión y manejo de datos categóricos.
  - `series_temporales.ipynb`: Análisis y manejo de datos temporales.
  - `geopandas_intro.ipynb`: Prácticas con GeoPandas para datos geoespaciales.
- **datasets/**: Archivos utilizados durante las prácticas (CSV, Excel, JSON, etc.).
- **env/**: Archivos para la gestión del entorno virtual con Anaconda.

---

## 🚀 Configuración del Entorno

### 1. Clona el repositorio:
```bash
git clone https://github.com/jdomdev/data-science-pandas.git
cd data-science-pandas
```

### 2. Crea el entorno con Anaconda:
```bash
conda env create -f environment.yml
conda activate pandas-env
```

### 3. Inicia Jupyter Notebook:
```bash
jupyter notebook
```

## 📋 Dependencias Principales
- Python: >=3.9
- Numpy: >=1.21
- Pandas: >=1.3
- GeoPandas: >=0.10
- Matplotlib: >=3.4
- Jupyter: >=1.0
