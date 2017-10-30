# Lyft

**Este es un proyecto de maquetado web con HTML & CSS.**

***

#### Trabajo realizado por:
 "María Paz Thompson" <m.paz.thompson@gmail.com>

*29 de Octubre 2017*

***

### Pseudo-Código.

 - Head está compuesto por el título del proyecto y enlaces a: *google fonts, icomoon y stylesheet*.

 -  Body, cuenta con etiquetas *div* (que contienen las imágenes de fondo), *section y footer*, que anidan el contenido de cada sección:

	1. **Div class="backgroundimg":** Comienza con este *div* *backgroundimg*, el cual por medio de css contiene la primera imagen de fondo y también anida *nav* y a la primera *section* llamada *"signup"*.

       	  a. **Nav:** tiene todos sus elementos englobados en un *div* llamado *"containernav"*, el cual contiene tres div que son los siguientes: *logolyft* (contiene el logo que está situado en la esquina superior izquierda), *containbuttons* (contenedor de los botones situados en la esquina superior derecha: Drive, Explore y Help) y el botón de *Log In*.
	  
	  	b. **Section class= "signup":** contiene un *div containersu* que anida todos los elementos de esta sección (*div que contienen texto, form, input, hr, button y etiquetas ancore*).

	2. **Section class="gradient":** esta sección, contiene en su background el fondo de gradiente de la página, además de dos *div* principales: el primero *descriptionimg*, el cual contiene todos los títulos y párrafos que van situados a la derecha de la imagen. El segundo *div class="cellimg"* contiene la imagen del celular con la app en uso.

   3. **Section class="videos":** anida 3 *div* principales: *textvideo1, textvideo2, textvideo3*. todas contienen un título pequeño, un título grande, un párrafo y un video incorporado con un *iframe* desde youtube, cada *div* con un orden diferente.

    4. **Footer:** tiene bastante información, por lo que lo designé en dos secciones para poder organizar los elementos.

		a. **Section class="columns":** dispone de 3 *div* (que contienen 5 *etiquetas ancore* cada uno) y un *div* que tiene los logos de AppStore, Google Play y Microsoft (cada uno con su correspondiente enlace de descarga).
		
		b.**Section class="rscr":** esta sección contiene las redes sociales (con íconos de *icomoon* y un div para el círculo), un *hr* y texto de *copyrights*.

Cabe mencionar que cada etiqueta HTML, tiene una clase que está modificada mediante una hoja de estilo CSS.
***

La página original de esta maqueta está en la siguiente imagen.

![Alt text](https://image.ibb.co/kHdq6R/fullpage.png)
