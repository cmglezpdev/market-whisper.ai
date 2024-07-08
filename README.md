# Market Wisper AI

### Notebooks

- `Preprocessing.ipynb`: Contiene todo el preprocesamiento de los datos, usando los dos csv en donde están disponibles el historial de precios y el de las noticias. Al final creamos un nuevo csv que junta estos dos csv en uno solo listo para su uso en el entrenamiento del modelo.

- `Model_without_embeddings.ipynb`: Contiene el entrenamiento de un modelo usando la arquitectura LSTM de Redes Neuronales. Este modelo usa varias covariables en la entrada relacionadas al precio del stock.

- `Model_with_embeddings.ipynb`: Contiene el entrenamiento de un modelo usando la arquitectura LSTM de Redes Neuronales. Este modelo usa varias covariables en la entrada relacionadas al precio del stock más la representación en forma de embedding de las noticias.

- `Model_with_classification.ipynb`: Contiene el entrenamiento de un modelo usando la arquitectura LSTM de Redes Neuronales. Este modelo usa varias covariables en la entrada relacionadas al precio del stock más la clasificación de las noticias en positivas o negativas, añadiendo en vez de una simple clasificiación binaria, in índice de pertencencia a cada clasificación, o sea, que tan negativa y que tan positiva es la noticia.

### Integrantes

- Carlos Manuel González Peña C411
- Alex Sánchez Sáez C412
- Jorge Alberto Aspiolea C412

### Documentación

[Tabla de revisión bibliográfica](https://docs.google.com/spreadsheets/d/1uX74QC2q3J1TAglnB6ebzgcCtaV8xvYl1m9HpVLDthU/edit?gid=0#gid=0)
 
[Informe del proyecto](./Prediccion_de_mercado_basado_en_noticias.pdf)
