---
layout: page
title: MC-to-MT (Minecraft-to-Minetest)
categories: projects
---
Un script enorme para bash (Linux) que me hice para convertir resource packs de Minecraft a Minetest. Algunos de los sprites no son fáciles porque son compuestos.

Lo colgaría, pero es bastante espagueti el código y está algo atrasado (lo hice antes de la update que añadió bastantes biomas, con lo que las texturas de bloques que Minecraft no tenía y minetest sí las tomaba prestadas del mod Biomes'o'plenty si estaba disponible). Además, nunca logré tomar el tono exacto de verde de la hierba (la textura de Minecraft es en escala de grises porque se adapta al bioma).

Además, casi todo lo que me proponía con este script lo ha hecho Sofar algo mejor en su [mcresconvert](https://github.com/minetest-tools/mcresconvert). Creo que aún si lo abandona sería mejor continuar con un fork del suyo que con el mío.

Aunque el mío era bastante fácil de portar a .bat de windows si se le incluyen algunas herramientas como infozip e imagemagick, y el suyo no... en fin, ya veré si lo limpio un poco.