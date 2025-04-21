# CursoIA_Proyecto_Final
Proyecto final del curso de IA

Este proyecto consiste en la detección de elementos en sistemas de transporte : vease cintas transportadoras de banda, rodillos, empujadores, transferencias.... a través de un modelo entrenado y con detección de código de barras.

Primeramente se genera un DATASET de ROBOFLOW con mezcla de 4 datasets y la API KEY de Roboflow insertada en los secretos de Google Colab (Gracias Anabel).

Segundo se realiza un modelo de entrenmaiento con (Train, val y set) de un número más o menos igual por cada uno de los 4 grupos.

Tercero se integra en la interfaz de Gradio para la predicción de códigos de barras y el tipo de contenedor que detecta con el modelo de predicción.
