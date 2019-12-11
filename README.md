# Pytorch Yolo V3 - Batteries Detection

Modelo creado como proyecto final para DemoDay de Saturdays Ai Santiago 2019.

## [Project Information]

La idea principal del proyecto se basa en la detección y reconocimiento de basura con potencial de reciclado, como por ejemplo: vidrio, carton, plastico,
etc. Una vez este material era identificado dentro de los desechos es posible idear un plan de automatización para el reciclado automatico usando
el presente modelo para la separación inteligente de estos residuos y evitando así la separación manual que es el actual metodo utilizado.

Para simplificar la elaboración del proyecto y de modo investigativo, se ha simplificado el problema solo enfocandose en la identificación de material critico reciclable
de manera separada, por lo cual, hemos optado por la identificación unica de Pilas o celdas de energia para abarcar el presente proyecto.

## [Model About]
- Dataset personalizado: Se recpilaron 1000 imagenes aproximadamente para el entrenamiento del modelo.
- El entrenamiento fue realizado por los weights originales de yolov3 tiny.
- Se modificaron los hiperparametros de convoluciones y para 1 sola clase, además de especificarse los epochs sugeridos por el autor original.


## [Project Status]
- Modelo funcionando de manera optima.
- Capaz de detectar pilas en imagenes/videos en la cual el objeto este quieto o en movimiento.


## [Details]
- Posibilidad de expandir la cantidad de clases a detectar tal como es mencionada en la idea original del proyecto.
- Se detectaron problema de sesgos asociadas a las imgenes usadas, principalmente en aquellas pilas que se encuentran con enfoque alejado de la imagen.
- Es posible aumentar la precisión amplificando el número de dataset.

## [TODO]
- Agregar ruido al dataset a modo de ampliar la cantidad de imagenes en el entrenamiento
- Utilizar configuraciones y weights originales de yolov3 para comparar resultados ya obtenidos por yolov3 tiny
- Agregar una segunda y tercera categoría para prueba directa de detección.

## [CITATION]
- BASED ON: https://github.com/ultralytics/yolov3#citation
- [![DOI](https://zenodo.org/badge/146165888.svg)](https://zenodo.org/badge/latestdoi/146165888)
