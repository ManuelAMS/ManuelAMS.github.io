---
layout: page
title: stsplus-update
categories: projects
---
![updater screenshot](/static/projects/stsplus/stsplus-updater.png)

Un script que me hice, primero para bash (Linux) y luego como BAT para DOS usando herramientas de FreeDOS como complemento, para poder actualizar este programa de seguimiento de satélites. Muy simple en realidad, porque los TLE's (Two-Line Element sets, ficheros con las coordenadas de satélites) son en texto plano, pero me sirvió para aprender a hacer mi primer script de bash con varias funciones y un menú.

Lo bueno es que la versión de DOS fue testeada en un 286, y no veo motivo para que no funcionara también en el 8086 original. No hay motivo real para eso en el fondo, ya que el STSPlus requiere un 486 rápido... pero bueno, tampoco me costaba nada y era un detalle un poco mas "nerd" si cabe.

No se si colgarlo, porque creo que han cambiado las normativas sobre el acceso a esos TLE's y ahora hace falta identificarse (por más que sean simples ficheros de texto y no contengan info alguna sobre satélites clasifiados, siguen siendo propiedad del NORAD)... en una mala puedo intentar incorporar login y password como variables al script. Tengo que revisarlo bien.

Pero tampoco hay mucha demanda. Hoy en día el usuario de este tipo de programas suele ser radioaficionado, y hay programas mejor diseñados para radioaficionados como GPredict. A mi el STSPlus me gusta por la estética "juegos de guerra" más que nada, sobre todo en un monitor CRT.