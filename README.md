# Análisis de la detección de armas de fuego en videos utilizando arquitecturas de Transformers de detección de objetos


## Base de datos
El trabajo utilizará el conjunto de datos Mock attack dataset [Salazar et al., 2020], el cual ha sido recopilado y anotado manualmente durante un simulacro de ataque. El conjunto de datos incluye tres cámaras de vigilancia ubicadas en diferentes áreas, cada una representando escenarios distintos. Las secuencias de video tienen diferentes duraciones y se han seleccionado segmentos con movimiento para su anotación. En total, se anotaron 607 fotogramas para Cam1, 3,511 fotogramas para Cam7 y 1,031 fotogramas para Cam5. Estos fotogramas anotados manualmente proporcionan información valiosa para tareas de detección de objetos y otras aplicaciones de visión por computadora.

## Modelo a evaluar
El análisis se hará sobre una de las arquitecturas más populares: DEtection TRansformer (DETR).

## DETR
Es una de las primeras arquitecturas Transformer end-to-end diseñada para la detección de objetos. A diferencia de enfoques tradicionales que requieren etapas o módulos adicionales, DETR realiza todo el proceso de detección de objetos en una sola etapa. Esto incluye la detección, clasificación y asignación de ubicaciones a los objetos en la imagen.

![DeformableDERT](https://github.com/JoseArmandoChavezQuijahuaman/Proyectos/assets/100543415/d8017cad-a9c3-4bb5-889e-10cef46e9ce2)
