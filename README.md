# Adobe-Scripts / ExtendScript para Photoshop
Un conjunto de funciones en Javascript para Photoshop. Realizan tareas sencillas para facilicitar el flujo de trabajo del fotógrafo.

Un ejemplo:
a_anchoXalto_comoCopia.jsx
==========================
guarda una copia en JPG de la foto que estamos trabajando añadiéndole dos cosas al nombre del archivo, que indican instrucciones al laboratorio:
1) un prefijo que indica la calidad en que se ha guardado: un dígito en hexadecimal que va desde calidad 1 a calidad c (12)
2) un sufijo de la forma ancho x alto (en cm) y el texto _cpy001
Así, si tenemos una foto de 10x15 cm llamada foto.jpg y la guardamos en calidad 10 se guardará como a_foto-10x15_cpy001.jpg
