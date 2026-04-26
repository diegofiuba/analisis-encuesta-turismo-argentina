# Análisis de Gasto Turístico mediante Modelos de Clasificación

## Descripción:

Este proyecto tiene como objetivo predecir el nivel de gasto de los turistas en función de las características de su viaje, utilizando técnicas de clasificación supervisada. El dataset proviene de la "Encuesta de Viajes y Turismo de los Hogares (EVyTH)", distribuida por el Ministerio de Turismo y Deportes de la República Argentina.

## Estructura del Proyecto:
- **01_comprension_limpieza_y_preparacion.ipynb**:  
  Contiene la introducción al proyecto, los objetivos y el análisis preliminar de los datos. 
  Además, se realiza la limpieza y preparación de los datos para su posterior análisis y modelado.
- **02_modelo_de_clasificación.ipynb**:  
  Contiene el preprocesado de los datos, el análisis de la importancia de las variables, y la implementación del modelo de clasificación **Hoeffding Tree** para predecir el gasto turístico 
## Requisitos:
- Python 3.x
- Bibliotecas:
- `pandas`
- `numpy`
- `matplotlib`
- `sklearn`
- `river`
- `tqdm`

Podés instalar las dependencias ejecutando:
```bash
pip install -r requirements.txt
```

	## Uso:
1. Clona este repositorio.
2. Ejecuta los notebooks en el orden establecido.
3. Podés ejecutar los notebooks en Google Colab o en tu entorno local.

**Pasos:**
1. **Configuración del entorno:** El primer paso es configurar las rutas y cargar el dataset.
2. **Análisis exploratorio de los datos:** Se analizan los atributos del dataset, detectando valores faltantes y valores erróneos.
3. **Preprocesado de los datos:** Se realizan transformaciones en los atributos y se prepara el conjunto de entrenamiento y prueba.
4. **Modelado:** Se implementa el modelo **Hoeffding Tree** para la predicción del gasto turístico.
5. **Evaluación:** Se evalúan los resultados utilizando matrices de confusión y métricas de clasificación.

## Limitaciones del Trabajo:
- Los datos provienen de encuestas telefónicas, lo que puede generar sesgos, valores faltantes o imprecisiones.
- La variable objetivo fue discretizada, lo que puede simplificar el problema pero también conlleva una pérdida de información.
- Los resultados obtenidos corresponden al dataset utilizado y no necesariamente son aplicables a otros contextos.