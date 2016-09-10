---
layout: post
title: Como traducir y adecentar el System Shock 2, edición GOG
date:   2016-06-09 05:09:39
categories: mods juegos
---
![logo](/static/posts/ss2header.jpg)
Esto es una nota personal, para por si tengo que volver a meterlo y no me acuerdo, pero en fin... que tampoco duele dejarlo al público.

Importante: instalar el juego en una ruta corta. Los mods tienen un límite de 80 caracteres para la ruta, así que si lo tienes como yo en F:\juegos\GOG\System Shock 2\ igual te toca renombrar alguna carpeta de mods. El nombre de la carpeta de cada mod da igual realmente.


Descargar la magnífica [traducción de ClanDLAN](http://academia.clandlan.net/?page=academia/view&id=1).

Para instalarla, hay un paso de la página y de su readme que ya no es necesario. Donde dice de instalar el NewDark... si el juego se instala via GOG Galaxy, ya te integra una versión más reciente de la que se incluye con la traducción, así que lo único que hay que hacer para instalar la traducción es:

- Copiar las carpetas DMM y subtitles de la traducción en la raiz del juego System Shock 2.
- Copiar la carpeta cutscenes a la System Shock 2\Data, sobreescribiendo las originales. Esto añade los videos subtitualdos.
- Copiar el Blue Mod Manager\ss2bmm.exe en la carpeta raiz del System Shock 2
- Ejecutar el ss2bmm.exe y desde él activar "SS2_traduDLAN".

Y ya está, el juego subtitulado en castellano. Podemos tener el siguiente problema: ¡la interfaz y los textos no se leen porque salen muy pequeños! Esto es porque el juego originalmente se diseñó para 640x480 y similares. Se puede solucionar con una pequeña edición:

- editar el fichero cam_ext.cfg, y buscar la siguiente línea: 

;d3d_disp_scaled_2d_overlay 640 480

- cambiarla por lo siguiente (así lo tengo yo para jugar en 1080p):

d3d_disp_scaled_2d_overlay 960 540

Podemos probar otros ratios hasta encontrar el que mas nos convenza.

Aquí se pueden ver dos capturas, una con el scale por defecto y otra con el que he puesto de ejemplo:

![logo](/static/posts/ss2-01.jpg)
![logo](/static/posts/ss2-02.jpg)


### MODS RECOMENDADOS

Aquí pongo los mods que yo estoy usando y que recomiendan para newbies en los foros de System Shock 2. Menciono las versiones actuales a Junio de 2016, pero obviamente si hay versiones más nuevas, instalad las más nuevas. Los mods se instalan extrayéndolos en la carpeta DMM y se activan en el mismo s2bmm.exe.

- [Vurt's Flora Overhaul](https://www.systemshock.org/index.php?topic=3181.0): mejora las plantas. Descargar el Vurt's SS2 Flora Overhaul 1.0k.7.
- [Tacticool Complete](https://www.systemshock.org/index.php?topic=691): armas en alta resolución. Descargar el Tacticool_complete_v1.05.7z, incluye todos los archivos mencionados después. 
- [Four Hundred](https://www.systemshock.org/index.php?topic=4240): texturas mejoradas. Descargar el AccFam_19.rar pero NO el "removed content", porque da problemas. 
- [Rebirth](https://www.systemshock.org/index.php?topic=8): mejores modelos para enemigos. Descargar el SS2_rebirth_v04a.7z. El otro fichero (que mejora las escopetas de los enemigos) pone que da problemas con otros mods así que lo ignoraremos. 
- [Vintage Song Remake](https://www.systemshock.org/index.php?topic=6849.0): Músicas mas cercanas a como se oían las originales, en volumen y tal. Este mod las añade en wav así que son 300 megazos. Descargamos el SS2_Vaxquis_VintageSongRemake.7z.
- [Vurt's Organics](https://www.systemshock.org/index.php?topic=4139): huevos alienígenas y demás. Descargamos todos los .7z excepto Biomatter y Grub Pod Smiley.
- [SHTUP-ND y SCP](https://www.systemshock.org/index.php?topic=8175): texturas de objetos mejoradas, y el SCP corrige bugs del juego. Descargamos el SHTUP-ND_beta1.7z y el SCP_beta2.7z.
- [Olfred's Fixed Objects](https://www.systemshock.org/index.php?topic=5982): modelos de objetos mejorados. Descargamos el obj_fixes_v11.7z.
 
Y aquí yo añadiría otros, que no entiendo que no los incluyan en la lista:

- [Vurt's Hi-Res Space Textures](https://www.systemshock.org/index.php?topic=4135.0): mejora las texturas del espacio que se ven por las ventanas. Descargamos el Vurt's Hi-Res Space v1.1.7z.
- [Vurt's Water](https://www.systemshock.org/index.php?topic=4167.0). Mejora la animación del agua. Descargamos el Vurt's SS2 Water v5.1.7z. 

Y ya pondré mas mods, que realmente acabo de conocer el juego y aún no lo he catado demasiado :).