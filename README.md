TUIA - Procesamiento del Lenguaje Natural 

En este proyecto se lograron desarrollar estos 5 ejercicios:

1) Construir un dataset haciendo web scraping de páginas web de su elección.
   
* Definir 4 categorías de noticias/artículos.
* Para cada categoría, extraer los siguientes datos de 10 noticias diferentes:

 -url (sitio web donde se publicó el artículo)
 -título (título del artículo)
-texto (contenido del artículo)

2) Utilizando los datos de título y categoría del dataset del ejercicio anterior, entrenar un
modelo de clasificación de noticias en categorías específicas.

3) Para cada categoría, realizar las siguientes tareas:
   
* Procesar el texto mediante recursos de normalización y limpieza.
* Con el resultado anterior, realizar conteo de palabras y mostrar la importancia de las
mismas mediante una nube de palabras.

4) Usar modelos de embeddings para evaluar la similitud entre los títulos de las noticias de una de las categorías.

5) Escribir un programa interactivo que, según la categoría seleccionada por el usuario,
devuelva un resumen de las noticias incluidas en ella.


# Instrucciones para correr el proyecto

1. Descargar el proyecto desde <> Code -> Download ZIP
2. Extraerlo en su PC (la carpeta se llamará nlp-main, dentro de ella tp1_nlp) 
3. Abrir VS Code -> File -> Open Folder... (tp1_nlp)
4. Abrimos una nueva terminal 
5. Creamos un venv: python -m venv venv
6. Lo activamos: .\venv\Scripts\activate
7. Y dentro de él instalamos los requerimientos: pip install -r .\requirements.txt
8. Nos movemos a la carpeta src: cd sr
9. Corremos python: python
10. Y por último abrimos el práctivo tp1_nlp.ipynb
