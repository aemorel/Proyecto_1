# Proyecto 1
# Retail Sales Analysis and Prediction

Este proyecto tiene como objetivo realizar un análisis integral de las ventas en una tienda de retail utilizando datos proporcionados. El análisis incluirá la manipulación básica de datos con NumPy, visualización y análisis con Pandas, y predicciones de ventas futuras utilizando técnicas de Machine Learning.

## Descripción del Proyecto

El proyecto se divide en las siguientes partes:

1. **Análisis de Ventas**: Exploración del dataset para entender los patrones de ventas por categoría, identificar productos con mayores y menores ventas, y calcular estadísticas básicas.
2. **Visualización de Datos**: Uso de visualizaciones gráficas para identificar tendencias en las ventas de la tienda.
3. **Predicción de Ventas**: Uso de modelos de Machine Learning para predecir futuras ventas basadas en los datos históricos.

## Dataset

El dataset utilizado en este proyecto es el **Retail Sales Dataset** (2023-2024), que contiene información detallada sobre las ventas diarias de diferentes productos en una tienda de retail.

Puedes descargar el dataset desde [Kaggle](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset).

## Estructura del Proyecto

- `data/`: Contiene los archivos de datos del proyecto.
- `notebooks/`: Contiene los notebooks de Jupyter donde se realiza el análisis y las predicciones.
- `src/`: Contiene el código fuente del proyecto, incluyendo las funciones de carga, preprocesamiento y modelos.
- `README.md`: Este archivo que explica la estructura y el propósito del proyecto.

## Instalación

1. Clona este repositorio en tu máquina local:

    ```bash
    git clone https://github.com/tu_usuario/retail-sales-analysis.git
    cd retail-sales-analysis
    ```

2. Crea un entorno virtual para el proyecto:

    ```bash
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```

3. Instala las dependencias necesarias:

    ```bash
    pip install -r requirements.txt
    ```

## Uso

1. Carga y analiza los datos:
    - Dirígete a la carpeta `notebooks` y abre los notebooks de Jupyter para realizar el análisis de ventas.
    
    ```bash
    cd notebooks
    jupyter notebook
    ```

2. Ejecuta el análisis básico y preprocesamiento de datos utilizando el archivo `data_loader.ipynb` en el directorio `notebooks`.

3. Para predicciones, puedes usar el archivo `sales_prediction.ipynb` que contiene los modelos de Machine Learning utilizados para predecir ventas futuras.

