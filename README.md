# Análisis de la detección de armas de fuego en videos utilizando arquitecturas de Transformers de detección de objetos


## Base de datos
El trabajo utilizará el conjunto de datos Mock attack dataset [Salazar et al., 2020], el cual ha sido modificado para darle el formato de cocodataset.
* [Link](https://drive.google.com/drive/folders/1H2DdpzPDr4Q8e0ljEt2naUcAgbhm2Tav?usp=sharing)

<div align="center">
  <img src="https://github.com/JoseArmandoChavezQuijahuaman/Proyectos/assets/100543415/3c475a2e-4228-4649-b547-a5b4bd899c15" alt="Captura desde 2023-06-08 11-39-23" style="width: 50%;">
</div>

## Modelo a evaluar
El análisis se hará sobre una de las arquitecturas más populares: DEtection TRansformer (DETR).

## DETR
Es una de las primeras arquitecturas Transformer end-to-end diseñada para la detección de objetos. A diferencia de enfoques tradicionales que requieren etapas o módulos adicionales, DETR realiza todo el proceso de detección de objetos en una sola etapa. Esto incluye la detección, clasificación y asignación de ubicaciones a los objetos en la imagen.

![DeformableDERT](https://github.com/JoseArmandoChavezQuijahuaman/Proyectos/assets/100543415/d8017cad-a9c3-4bb5-889e-10cef46e9ce2)
