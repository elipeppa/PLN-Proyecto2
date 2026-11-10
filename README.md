# PLN-Proyecto2, diccionario inverso basado en normas de asociación y grafos

## Descripción del Proyecto
Se hizo la implementación de un sistema de diccionario inverso para recuperar palabras objetivo a partir de descripciones textuales en español. El sistema utiliza normas de asociación de palabras (NALC) modeladas como un grafo dirigido ponderado y representaciones vectoriales densas con `node2vec`.

## Estructura del Repositorio
- `Proyecto2_PLN_limpio.ipynb`: Notebook ejecutable de principio a fin con semillas fijas (`SEMILLA = 1950`).
- `nalc_asociaciones.csv`: Dataset de normas de asociación libre (estímulo, respuesta, FSG).
- `conjunto_evaluacion.csv`: Dataset con las descripciones, conceptos y partición.
- `requirements.txt`: Archivo de dependencias del entorno.

## Requisitos e Instalación
El proyecto requiere Python 3.10+ y las siguientes librerías principales:

- `spacy == 3.8.18`
- `networkx == 3.5`
- `scipy == 1.16.3`
- `gensim == 4.4.0`
- `pandas`
- `numpy`
- `scikit-learn`
- `tqdm`
  
(El colab las instala automáticamente)
