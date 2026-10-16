---
type: libro
title: "Manual VraySun & VraySky"
author: "neo"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 18
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/3D MAX Y VRAY/MANUALES/VRAYSUN AND VRAYSKY.pdf"
convertido: 2026-10-16
---

# Manual VraySun & VraySky

> Texto extraído de `AYUDAS DE PROGRAMAS\3D MAX Y VRAY\MANUALES\VRAYSUN AND VRAYSKY.pdf` (18 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Manual VraySun & VraySky

Neozenit®2006. No utilizar este documento si el permiso escrito de su autor.
neozenit@gmail.com / http://neozenit.cgsociety.org

Hola a todos, este manual es una pequeña explicación de lo que he aprendido de esta poderosa y poco difundida
herramienta que incorpora las últimas versiones Beta de Vray, espero que os sirva de algo. Doy por entendido que
la gente que lee esta referencia tiene un mínimo conocimiento de 3dsMax así como de motor de render Vray.

VraySky

Como llegamos a el:
Pinchamos en Enviroment Map:

<!-- p. 2 -->

Seleccionamos VraySky

Una vez tengamos el VraySky seleccionado como Enviroment Map, lo arrastramos a una de las
celdas de material del Material Editor, aquí es donde empezamos a trabajar con el VraySky, este es
mas o menos un Hdri variable, es decir que podemos modificar los parámetros de color e intensidad y
además recoge la información del punto de luz de la escena que le asignemos como Nodo
(sun_node)

<!-- p. 3 -->

Parámetros de los que se compone:

specify_sun_node:
Lo podemos dejar apagado, con lo cual no
actúa, o verificado o encendido, en este caso se
activan los siguientes parámetros.

sun_node:
Aquí le decimos que punto de luz va a
interactuar, con nuestro VraySky, es decir el
punto de luz que le va ha dar luminancia a este
mapa.

Puede ser cualquier tipo de luz, aunque como
mejor funciona es con las direccionales, Direct,
Spot y sobre todo VraySun.

Para activarla, solo tenemos que pulsar sobre el
botón “None” y seleccionar un punto de luz de
nuestra escena, para ello con pinchar en la
escena muestra luz, es suficiente.

Sun_turbidity:
Pequeña explicación sobre que es la turbiedad atmosférica, la turbiedad atmosférica es el fenómeno
natural o inducido, que hace que la luz cambie de espectro cromático (color) dependiendo de la
composición de la masa de aire que atraviese, por ejemplo en una mañana de verano, en el campo la
turbiedad será mínima, sin embargo en una gran ciudad y debido a la polución atmosférica esta será
alta. Este factor puede ser natural, por ejemplo en un desierto el polvo y arena en suspensión debido
a una tormenta de arena, hará que la turbiedad sea alta.
Los parámetros de la casilla sun_turbidity, pueden variar desde el 2 hasta el 20, siendo la
atmósfera pura el 2 y la mas turbia el 20, en condiciones normales trabajaremos siempre en
los rangos comprendidos entre el valor 2 y el 3, usando sus decimales para afinar mas en
nuestros propósitos.

<!-- p. 4 -->

Ejemplo:

Creamos un suelo y una tetera, creamos un VraySun (en su apartado
explicare, cada una de sus opciones) con los parámetros por defecto,
bueno tendremos que cambiar el intensity_multiplier (por defecto viene
en 1).

Este punto luminoso, lo
colocaremos a las
18:00 horas (cuando
indico la posición en
horas del punto
luminosos, me refiero
a la altura sobre el
horizonte que tiene el
sol a esa hora,
obviamente esto
cambiara
dependiendo de la
zona geográfica en la
que nos
encontremos)

<!-- p. 5 -->

Creamos un VraySky como he explicado anteriormente y con el vray como motor de render activado
y con esta configuración (mas adelante veremos que configuración es preferible utilizar).
A continuación tiramos unos renders, cambiando solamente el valor del campo sun_turbidity

<!-- p. 6 -->

sun_turbidity =20

sun_turbidity =15

<!-- p. 7 -->

sun_turbidity =10

sun_turbidity =5

<!-- p. 8 -->

sun_turbidity =2

<!-- p. 9 -->

Ahora bien si dejamos el valor sun_turbidity en 2 y movemos el sol (VraySun) a distintos horarios
(ángulo de incidencia sobre el horizonte) obtendremos los siguientes resultados:

7 horas (mas o menos 20º de inclinación sobre el horizonte) amaneciendo

10 horas (más o menos 45º de inclinación sobre el horizonte) media mañana

<!-- p. 10 -->

12 horas (mas o menos 90º de inclinación sobre el horizonte) medio día

18 horas (más o menos 135º de inclinación sobre el horizonte) media tarde

<!-- p. 11 -->

21horas (mas o menos 165º de inclinación sobre el horizonte) anocheciendo

Sun_ozone:
Este campo representa la acumulación de ozono atmosférico o de vapor de agua en suspensión, el
valor mínimo es 0 lo que equivaldría a un día seco y el valor máximo es 1, lo que equivaldría a un
día con altos valores de ozono atmosférico o a un día con alta concentración de humedad ambiente.

Los valores cercanos al 0 no tendrán mostraran en los renders menos tinte azulado, que los valores
cercanos al 1, siendo valores óptimos los comprendidos entre el 0,15 y el 0,45

En este parámetro nos limitaremos a poner el mismo valor que el campo “ozone” del VraySun
que tengamos asignado en el campo (sun_node), ya que es este realmente el que genera o muestra
cambios en nuestros renders y trabajan mejor si el valor es el mismo.

Sun_intensity_multiplier:
Este campo es muy simple, controla la intensidad de la luz que irradia el cielo.
Sus valores están comprendidos entre el valor mínimo 0 y valor máximo 100000000, siendo
valores por encima de 1 casi inútiles, siendo el valor optimo y el mas usado 0,001.

Sun_size_multiplier:
Este campo es muy simple, controla el tamaño del emisor de luz que irradia el cielo.
Sus valores están comprendidos entre el valor mínimo 0 y valor máximo 100000000, siendo
valores por encima de 10 casi inútiles, siendo el valor medio y optimo, mas usado el 5.

Neozenit®2006
No utilizar este documento si el permiso escrito de su autor.
neozenit@gmail.com / http://neozenit.cgsociety.org

<!-- p. 12 -->

Manual VraySun & VraySky

Neozenit®2006. No utilizar este documento si el permiso escrito de su autor.
neozenit@gmail.com / http://neozenit.cgsociety.org

Hola a todos, este manual es una pequeña explicación de lo que he aprendido de esta poderosa y poco difundida
herramienta que incorpora las últimas versiones de Vray, espero que os sirva de algo. Doy por entendido que la
gente que lee esta referencia tiene un mínimo conocimiento de 3dsMax así como de motor de render Vray.

VraySun

Como llegamos a el:
Pinchamos en Lights.
Seleccionamos Vray.
Seleccionamos VraySun y dibujamos en el viewport elegido la
trayectoria de la luz, como hacemos normalmente con
cualquier luz direccional, con la diferencia que en este tipo de
luz, según el horario (inclinación) que coloquemos la luz
tendremos un resultado distinto.

Vraysun, colocado a las 7:00 (de 15 a 20 grados) obtendremos una imagen con la típica iluminación
del amanecer. El VraySky se adapta automáticamente a este tipo de iluminación.

<!-- p. 13 -->

Vraysun, colocado a las 16:00 (de 110 a 125 grados) obtendremos una imagen con la típica
iluminación de media tarde, con luces fuertes y sombras cortas. El VraySky se adapta
automáticamente a este tipo de iluminación.

Vraysun, colocado a las 21:00 (de 155 a 170 grados) obtendremos una imagen con la típica
iluminación de últimas horas de la tarde, con luces suaves y sombras largas. El VraySky se adapta
automáticamente a este tipo de iluminación.

<!-- p. 14 -->

Parámetros de los que se compone:
enabled:
Lo podemos dejar apagado, con lo cual no actúa, o verificado o
encendido, en este caso se activan los siguientes parámetros. En este
caso solo iluminara el VraySky si lo tuviésemos activado (se consiguen
iluminaciones interesantes practicando esta opción)

Turbidity:
En este campo, podremos tener en cuenta lo explicado para el VraySky,
pero teniendo en cuenta que lo que se modifica aquí, es la cantidad y
tonalidad de la luz emitida por el VraySun (es una simulación, de
filtrado de luz, por causas ambientales).
Los parámetros de la casilla turbidity, pueden variar desde el 2 hasta el 20, siendo la luz pura
el 2 y la mas turbia el 20, en condiciones normales trabajaremos siempre en los rangos
comprendidos entre el valor 2 y el 3, usando sus decimales para afinar mas en nuestros
propósitos.

Turbidity = 2,0

Turbidity = 5,0

<!-- p. 15 -->

Turbidity = 10,0

Turbidity = 15,0

Turbidity = 20,0

<!-- p. 16 -->

Ozone:
Este campo representa la acumulación de ozono atmosférico o de vapor de agua en suspensión, el
valor mínimo es 0 lo que equivaldría a un día seco y el valor máximo es 1, lo que equivaldría a un
día con altos valores de ozono atmosférico o a un día con alta concentración de humedad ambiente.

Los valores cercanos al 0 no tendrán mostraran en los renders menos tinte azulado, que los valores
cercanos al 1, siendo valores óptimos los comprendidos entre el 0,15 y el 0,45

Debemos recordar poner el mismo valor en el campo “ozone” del VraySky.

Ozone = 0

<!-- p. 17 -->

Ozone = 0,50

Ozone = 1

<!-- p. 18 -->

intensity_multiplier:
Este campo es muy simple, controla la intensidad de la luz que irradia el emisor o VraySun.
Sus valores están comprendidos entre el valor mínimo 0 y valor máximo 100000000, siendo
valores por encima de 1 casi inútiles y los valores mas usados los números comprendidos
entre el 0,001 y el 0,01

size_multiplier:
Este campo es muy simple, controla el tamaño del emisor de luz.
Sus valores están comprendidos entre el valor mínimo 0 y valor máximo 100000000, siendo
valores por encima de 10 casi inútiles y el valor medio y optimo, mas usado el 5.

shadow_subdivs:
Este campo es muy simple, controla la calidad de las sombras.
Sus valores están comprendidos entre el valor mínimo 0 y valor máximo 1000, siendo los valores
mas usados los números comprendidos entre el 8 y el 16.
La mejora de calidad en las sombras aumenta de forma proporcional los tiempos de render.

shadow_bias:
Este campo es muy simple, permite el desfase de las sombras.
Sus valores están comprendidos entre el valor mínimo 0 y valor máximo 100000000, siendo los
valores mas usados y óptimos los números comprendidos entre el 0 y el 1(y sus decimales).

Neozenit®2006
No utilizar este documento si el permiso escrito de su autor.
neozenit@gmail.com / http://neozenit.cgsociety.org
