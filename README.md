# YouTube Data Analysis

Este script de Python utiliza la API de YouTube para recopilar datos y realizar análisis sobre canales de YouTube y sus videos asociados.

## Requisitos

Asegúrate de cumplir con estos requisitos antes de comenzar:

- Python 3.x instalado.
- Las bibliotecas requeridas se pueden instalar mediante el siguiente comando:

``` bash
pip install google-api-python-client dateutil pandas IPython seaborn matplotlib nltk wordcloud
```
## Uso
## Configura tu API Key de YouTube:

Antes de usar este script, debes obtener una API Key de YouTube. Puedes obtener una siguiendo las instrucciones en la documentación de la API de YouTube. Luego, coloca tu API Key en el código en la variable api_key.

Configura los canales de YouTube que deseas analizar:

En la lista channel_ids, agrega los ID de los canales de YouTube que deseas analizar. Puedes agregar más canales a medida que sea necesario.

# Funcionalidades

El script incluye las siguientes funcionalidades:

- Recopilación de estadísticas de canales de YouTube, incluyendo suscriptores, vistas y videos totales.
- Recopilación de detalles de videos, incluyendo título, descripción, etiquetas y estadísticas como vistas, me gusta, comentarios, duración, entre otros.
- Análisis exploratorio de datos (EDA) que incluye gráficos de barras y gráficos de dispersión para visualizar datos de videos.
