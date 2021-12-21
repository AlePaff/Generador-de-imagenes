# Generador-de-imagenes


Bitácora de cada día en el desarrollo del tp

| Fecha | Comentario |
| ------------- | ------------- |
| 6/12  | - cargar los datos y subir todo a drive, comprobar que anden y se puedan visualizar. <br> - ver si se pueden leer csv sin subirlos a colab (no resultó en nada funcional)  |
| 7/12  | lograr visualizar una imagen en colab de la base de datos, y convertidor de numpy a texto (y viceversa)  |
|9/12 | - hice un analisis exploratorio de datos. <br> - averigué como funciona VQGAN+CLIP. \\- entrené un modelo """simple""" de CLIP para después darme cuenta que no era un generador de imagen, sinó mas bien un buscador/relacionador de texto-imagen<br> - investigar MUCHAS otras formas de crear imagenes falsas a partir de frases. "15 pastillas de metafetamina"<br> - llego a la conclusión que hacer esto puede llevar demasiado tiempo, porque hay que armarlo todo ya que no hay notebooks o codigo python programable (liberado al publico). Y decido cambiar a simplemente generar texto dada una palabra "droga", "alcohol", etc<br> 
|16/12| - continuar investigando métodos de crear imagenes en base a una palabra <br> - encontré un metodo que genera números en base a una imagen, ver como pasarlo para que genere en base a un texto <br> - seguí investigando otras alternativas, encontré artículos buenos de CGANs, debo leer más teoría <br><br> Idea: puedo llegar a crear una palabra y que me la encodee en una categoría "cocaina" -> 32.  "libro" -> 11. etc
|19/12|- añadidas mas lineas a la exploración de datos<br>- visualizar imagenes, a color, escala de grises, todo a numpy<br>- preprocesamiento (verificación de imagenes correctas, tamaños, repetidas, etc)<br>- adaptación de mi dataset al modelo copiado, aún sin funcionar<br>- arreglo de detalles menores <br><br>  Ir pensando ideas para como presentar el tp en el video
|20/12|- enterarme que la entrega no es el 23 sinó el 20 <br> - separé train y test, de forma que queden categorías uniformemente distribuidas<br> - volví a unzipear todas las imagenes porque había faltantes <br> - añadidas más partes de preprocesamiento (imagenes existentes, filtros, etc) <br>- mejoré las funciones conversoras a grayscale, rgb, y imagen a numpy<br> - reescalar imágenes<br> - baseline terminado y funcionando <br> - limpieza del notebook <br> - creación del ppt, grabación del video y pdf de entrega con links 

