# Labo1_Web

Preguntas: ejercicio 1 : 
1. Actualice la página en su navegador y pregúntese ¿Hay cambios en la visualización del sitio web? Si la
respuesta es negativa, piense un momento ¿Para qué sirven las etiquetas meta? Busque esa respuesta en la
introducción teórica de la guía o consulte con una búsqueda de su duda en google.

Respuesta: Las etiquetas meta sirven para proporcionar informacion sobre el contenido de una pagina web, tanto a los navegadores
como a los motores de busqueda, sin que estos sean visibles para los usuarios.

ejercicio 2: 
2. Asegúrese de entender el valor del atributo src de la etiqueta img. ¿Qué pasaría si la imagen esta guardada
en la misma carpeta de la página web? ¿Y si está en una carpeta superior?

Respuesta: Investigando un poco, vi que el atributo src indica la ruta hacia el archivo de imagen, y dependiendo de 
donde esta ubicada la imagen, asi cambia tambien el valor. 
Entonces, si la imagen esta en la misma carpeta que la pagina web: el atributo src solo necesita el nombre del archivo.
y si la imagen está en una carpeta superior:
Debo usar ../ para subir un nivel en la estructura de carpetas. Es decir, si la imagen está una carpeta arriba, la estructura seria la siguiente: 
--<img src="../imagen.jpg" alt="Imagen">--

