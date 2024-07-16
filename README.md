# Predicción del Precio de una Vivienda

Este proyecto fue desarrollado como parte del Bootcamp de Data Science en la IT Academy. El objetivo principal es desarrollar un modelo predictivo capaz de estimar el precio de viviendas en el estado de California, utilizando técnicas de machine learning y análisis de imágenes.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Datos](#datos)
- [Metodología](#metodología)
- [Modelos](#modelos)
- [Resultados](#resultados)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Descripción

En el competitivo mercado inmobiliario, las herramientas de valoración precisas son esenciales. Este proyecto utiliza datos históricos y características visuales de las propiedades para predecir su precio, superando las limitaciones de los métodos tradicionales.

## Datos

El conjunto de datos utilizado en este proyecto proviene de múltiples fuentes:

- **Zillow**: Datos históricos de ventas de viviendas mediante web scraping.
- **Realtor.com**: Datos de mercado inmobiliario complementarios.
- **Open Data California**: Información geográfica y demográfica.

## Metodología

La metodología del proyecto se divide en varias fases:

1. **Recopilación de Datos**: Uso de técnicas de web scraping y extracción de datos de diversas fuentes.
2. **Procesamiento de Imágenes**: Análisis de las imágenes de las propiedades utilizando redes neuronales convolucionales (CNN).
3. **Modelado Predictivo**: Integración de datos estructurados y características visuales para desarrollar un modelo híbrido.
4. **Evaluación del Modelo**: Uso de métricas como MSE y R² para validar la precisión del modelo.

## Modelos

Los modelos utilizados en el proyecto incluyen:

- **Regresión Lineal**
- **Árboles de Decisión**
- **Random Forest**
- **Gradient Boosting Machines (GBM)**

## Resultados

Los resultados del proyecto muestran que el modelo de Gradient Boosting Machines (GBM) proporciona la mejor precisión predictiva, con un R² de 0.90 y un MSE de 1,500,000.

## Requisitos

- Python 3.x
- Bibliotecas: pandas, numpy, scikit-learn, tensorflow, keras, matplotlib, seaborn, beautifulsoup4, selenium

## Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/vsm-data-science/prediccion-precio-vivienda.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd prediccion-precio-vivienda
    ```
3. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

Para ejecutar el proyecto, sigue estos pasos:

1. **Recopilación de Datos**:
    - Ejecuta los scripts de web scraping para obtener datos de Zillow y Realtor.com.
2. **Procesamiento de Imágenes**:
    - Preprocesa las imágenes y extrae características utilizando la CNN.
3. **Entrenamiento del Modelo**:
    - Entrena el modelo híbrido utilizando los datos recopilados.
4. **Evaluación del Modelo**:
    - Evalúa la precisión del modelo utilizando los conjuntos de datos de validación y prueba.

```bash
python train_model.py

