---
type: libro
title: "Losa1"
author: "your name"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 21
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/SAFE/Tutoriales/Losa1.pdf"
convertido: 2026-10-16
---

# Losa1

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\SAFE\Tutoriales\Losa1.pdf` (21 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

SAFE Problema 1
Tabla Llana irregular

Propiedades de la Losa de concreto
E = 4000 ksi, Proporción de Poissons = 0.2, Peso de la Unidad = 150 pcf
F'c = 4 Ksi, Fy = 60 Ksi
Asuma tapa predefinida por reforzar acero

Columnas de concreto y Propiedades de la Pared
E = 4000 ksi, Proporción de Poissons = 0.2, Altura = 12’

Tabla la Carga Uniforme
Carga muerta: la Tabla el mismo peso más 50 los psf sobrepusieron DL
Carga viva: 100 psf típico, 250 psf entre la columna línea 3, 5, E y F

Para Hacer
Repase la tabla elástica los y resquebrajada los desplazamientos verticales bajo el unfactorizaron DL + la carga del la de LL. Repase los MXX tabla momentos factorizados (1.4DL+
1.7LL). Repase la X-tira calculada que refuerza para ACI 318-95.

<!-- p. 2 -->

Problema 1 Solución

\1. Pulse el botón drop down la caja en la barra de estado cambiar las unidades al kip-ft.

\2. Del menú File seleccione New Model…. Esto despliega la Reja Definición diálogo
caja.

\3. En esta caja del diálogo:

• Los pulso el botón Edit Grid desplegar el Defina X la Reja diálogo caja.

• En esta caja del diálogo:

En el área del Despliegue verifica que la Grid X opción se selecciona.

En la Reja del Despliegue Como área verifica que la opción de las Ordenadas se
selecciona.

Llene en la Grid ID y columnas de hoja de cálculo de Coordenada mostrada en
la Figura 1-1.

Figura 1-1: la X Grid Definición

En el Despliegue seleccione la Grid Y opción. Nota que el título de los cambios
de caja de diálogo para Definir Reja de Y.

<!-- p. 3 -->

Llene en la Grid ID y columnas de hoja de cálculo de Coordenada mostrada en la
Figura 1-2.

Pulse el botón el botón de OK para completar la definición de la reja. La pantalla
se refrescará y desplegará dos vistas del modelo (la reja línea a estas alturas) en
ventanas inmediatas verticalmente azulejadas. La ventana de la izquierdo-mano es
una vista de plan de capa estructural en el avión de X-Y y la ventana diestra es
una capa estructural 3-D vista.

Figura 1-2: la Grid Y Definición

Nota: En información SAFE puede verse en tres capas diferentes. Ellos son el
Capa estructural, Capa de Tira de X-plan y Capa de Tira de Y-plan. El Estructural
La capa incluye información sobre la geometría de la tabla, cargas y condiciones del
límite. La Capa de Tira de X-plan se usa para definir la magnitud de las tiras de plan de
X-dirección. La Capa de Tira de Y-plan se usa para definir la magnitud de las tiras de
plan de Y-dirección. Usted pueda seleccionar la capa a ser mostrada del menú de Vista.

\4. Pulse el botón en la ventana tituló Vista de Plan de Capa Estructural para asegurarse es
activo. El la ventana es activa cuando su barra del título se resalta.

\5. Verifique que botón Snap To Points en la barra de herramientas lateral está así
deprimido habilitando esto que saca una foto opción.

Nota: Usted también podría verificar que el Chasquido A la opción de los Puntos es
activo pulsando el botón el Draw menú, seleccionando Snap To y verificando eso hay
una marca del cheque al lado de los Points adelante el sub-menú. Si la marca del
cheque existe entonces que la opción es activa. Si la marca del cheque no es allí,

<!-- p. 4 -->

entonces pulse el botón puntos y entonces la marca del cheque aparecerá indicando que
la opción es ahora activo. Este artículo del menú está como un interruptor de la barra
traviesa. Usted puede pulsar el botón en él para encenderlo y fuera de. La marca del
cheque le dice si es adelante (verificó) o fuera de (no verificó).

\6. Pulse el botón Draw Quadrilateral Area Object en la barras de herramientas
lateral (o selecciona Draw Quadrilateral Area Object del Draw menú). Nota en la que
usted es ahora Dibuja modo y que la forma del indicador del ratón ha cambiado.

Nota: hay dos modos distintos en SAFE: el modo Selecto y Dibuja Modo. El modo
selecto, el modo predefinido, se usa por asignar propiedades y cargas y para el
despliegue de asignaciones y resultados. Dibuje que el modo se usa para dibujar
geometría. El indicador del ratón es dependiendo diferente en que modo en el que usted

es. En modo Selecto las miradas de indicador de ratón as í . En Dibuje modo las

miradas de indicador de ratón as í . Usted siempre puede decir qué modo que usted
es en mirando la apariencia del indicador del ratón. Usted entra dibuja modo siempre
que usted o seleccione uno de las herramientas del dibujo en el barra de herramientas

lateral o en el Dibuje menú. Pulsando el botón del Indicador en el barra de
herramientas lateral lo cambiarán del Retire modo atrás para Seleccionar modo.

Fondo: los modelos SAFE se componen de objetos del área, objetos de la línea y objetos
del punto. Se usan objetos del área para definir tablas, uniformemente las cargas
distribuidas y tierra (uniformemente distribuido) los apoyos. Se usan objetos de la línea
para definir vigas, cargas de la línea y apoyos de la pared. Se usan objetos del punto
para definir cargas del punto y columna (punto) los apoyos. Para crear a un modelo
SAFE usted dibuja estos tres tipos de objetos (área, línea y punto) y les asigna
definiciones apropiadas.

\7. Nosotros definiremos la tabla (no incluso las aperturas que se dirigirán después)
usando tres objetos del área. Dibuje el primer objeto del área solo pulsando el botón en
reja intersecciones B-5, F-5 y E-3 y entonces el pulsando el botón doble en el cuarto y la
intersección de la reja final a las A-3.

Nota: Cuando usted pone el indicador cerca de uno de las intersecciones de la reja que
un punto aparecerá en la intersección de la reja con una caja del título que dice “la
Intersección de la Reja.” Esto indica que usted está dentro de la tolerancia del
Chasquido Apuntar rasgo y que si usted pulsa el botón el ratón que usted sacará una foto
a la intersección de la reja. Usted puede controlar la tolerancia por sacar una foto
seleccionando el menú de Options, pulsando el botón Preferences..., seleccionando la
Etiqueta de las Dimensiones y poniendo el Chasquido de la Pantalla a la Tolerancia.

<!-- p. 5 -->

Nota: el pulsando el botón Doble en la última intersección de la reja completa el objeto
del área. O pueden tres-estarse al lado de objetos del área (triángulo) o cuatro-estaba al
lado de (cuadrilátero). Si usted dobla pulse el botón en el tercer punto que usted hará a
un objeto del área tres-estado al lado de. El pulsando el botón doble en el cuarto punto
da un objeto del área cuatro-estado al lado de. En lugar del pulsar el botón doble en el
último punto usted puede singularizar pulse el botón en el último punto y entonces
apriete el Entre en llave en el teclado completar el objeto del área. Este método trabaja
en los dos tres- al lado de y cuatro-estaba al lado de objetos del área.

\8. Dibuje un segundo objeto del área solo pulsando el botón en reja intersecciones A-3,
C-3 y C-1 y entonces apretando el Entre en llave en el teclado.

\9. Dibuje un tercer objeto del área solo pulsando el botón en intersecciones de la reja C-3
y D-3 y entonces el pulsando el botón doble en el tercio y la intersección de la reja final a
las C-2.

\10. Pulse el botón Draw Line Object en la barra de herramientas lateral (o
selecciona Draw Line Object del Draw menú).

\11. Dibuje un objeto de la línea pulsando el botón en reja intersección C-3 y entonces el
pulsando el botón doble en reja intersección D-4 para completar el objeto de la línea. Este
objeto de la línea se usará para definir el apoyo de la pared.

Nota: Nosotros también podríamos singularizar pulse el botón en reja intersección D-4 y
entonces apriete el Entre en llave en el teclado completar el objeto de la línea.

\12. Pulse el botón Draw Point Object en la barra de herramientas lateral (o
selecciona Draw Point Object del Draw menú).

\13. Dibuje un objeto del punto pulsando el botón doble en reja intersección D-5. Este
objeto del punto se usará para definir un apoyo de la columna. El modelo aparece como
mostrado en Figura 1-3.

Nota: Nosotros también podríamos singularizar pulse el botón en reja intersección D-5 y
entonces apriete el Entre en llave en el teclado completar el objeto del punto.

Nota: no es necesario dibujar objetos del punto para las otras cinco columnas porque
aquéllos ya apuntan que los objetos existen. Ellos fueron creados que cuando el área
objeta definiendo la tabla era arrastrado. Cuando los objetos del área son arrastrado, se
crean objetos del punto automáticamente a las esquinas del objeto del área.
Semejantemente, cuando los objetos de la línea son se crean objetos del punto arrastrado
automáticamente a los extremos del objeto de la línea.

<!-- p. 6 -->

Si usted no define un objeto del punto entonces como un apoyo o una carga que el
programa ignorará ese objeto cuando el análisis se corre. Así usted no necesita cuidado
sobre cualquier objeto del punto extraño que puede haber sido creado por el programa a
las esquinas de objetos del área o extremos de objetos de la línea.

Figura 1-3: Modelo Después de Paso 13

\14. Ahora nosotros dibujaremos que la tabla que abre entre la columna línea C y D. Pulse

el botón Quick Draw Rectangular Area Object en la barra de herramientas lateral
(o selecciona Quick Draw Rectangular Object del menú Draw).

\15. Pulse el botón una vez en el área entre la columna línea C, D 4 y 5 eso se etiqueta
“Pulse el botón Aquí” en Figura 1-3. Un objeto del área rectangular que cubre el área
limitada por columna se crea línea C, D, 4 y 5.

\16. Pulse el botón Pointer/Select para cambiar de Dibuja modo para seleccionar
modo. El modelo aparece ahora como mostrado en Figura 1-4.

<!-- p. 7 -->

Figura 1-4: Modelo Después de Paso 16

\17. El derecho pulsa el botón una vez en el objeto del área sólo usando arrastrado el
Rápido Dibuje rasgo para desplegar la Tabla Información diálogo caja Rectangular.

\18. En esta caja del diálogo:

• En el Localice área de la Tabla verifique que el Por opción de los Bordes se
selecciona.

• En la Identificación y área de la Situación tipo 17 en el Xmin revisa caja.

• En la Identificación y área de la Situación tipo 23 en el Xmax revisa caja.

• En la Identificación y área de la Situación tipo 28 en el Ymin revisa caja.

• En la Identificación y área de la Situación tipo 32 en el Ymax revisa caja.

• Pulse el botón el botón de OK. Los El objeto del área es re-clasificaron según
tamaño.

Nota: Alternativamente nosotros podríamos crear la reja adicional línea y usó éstos la
reja línea para definir este objeto del área

<!-- p. 8 -->

\19. La izquierda pulsa el botón el objeto del área del seleccionarlo del para re-clasificado
según tamaño.

\20. Del Asigne Apertura selecta al menú. Esta área se designa ahora como una apertura y
el modelo aparece como mostrado en Figura 1-5.

Figura 1-5: Modelo Después del Paso 20

\21. Ahora nosotros dibujaremos que la tabla que abre entre la columna línea B y C.
Nosotros usaremos que la reja secundaria línea para ayudarnos dibujar la apertura.

\22. Del menú Edit seleccione Edit Grid... para desplegar el Defina X Reja diálogo caja.

\23. En esta caja del diálogo:

• En el área del Despliegue verifica que la X Reja opción se selecciona.

• En la Reja del Despliegue Como área verifica que la opción de las Ordenadas se
selecciona.

• Pulse el botón en la fila 7 de la hoja de cálculo.

<!-- p. 9 -->

• En la Línea de la Reja #7 área selecciona la opción de la Línea Secundaria.

Nota: las líneas de la reja Secundarias no tienen Reja las burbujas de ID. Nosotros no
especificaremos una Reja ID para estas líneas secundarias.

• Teclee 9 en la columna de la Coordenada de la fila 7 de la hoja de cálculo.

• En el área del Despliegue seleccione la Y Reja opción.

• Pulse el botón en la fila 6 de la hoja de cálculo.

• Verifique que la opción de la línea Secundaria se selecciona en la Línea de la Reja
\#6 área.

• Teclee 24 en la columna de la Coordenada de la fila 6 de la hoja de cálculo.

• Pulse el botón el botón de OK. El modelo aparece ahora como mostrado en
Figura 1-6.

Figura 1-6: Modelo Después de Paso 23

<!-- p. 10 -->

\24. Pulse el botón Quick Draw Rectangular Area Object en la barra de
herramientas lateral (o selecciona Quick Draw Rectangular Area Object del menú
Draw).

\25. Pulse el botón en el área designada “X” en Figura 1-6 para dibujar el objeto del área.

\26. Pulse el botón Pointer/Select abrochan para cambiar el modo de Dibujo para
Seleccionar modo.

\27. Pulse el botón el nuevo objeto del área para seleccionarlo.

\28. Del Asigne Apertura selecta al menú. Esta área se designa ahora como una apertura.

\29. Pulse el botón la gota abajo la caja en la barra de estado cambiar las unidades a

kip-in.

\30. Pulse el botón en los objetos del punto a B-5, D-5, F-5, E-3, C-1 y A-3 seleccionarlos.
Cuando usted ha seleccionado que todos los seis objetos del punto miran el lado de la
izquierdo-mano de la barra de estado al fondo de la ventana SEGURA y verifica que dice
“6 Junturas seleccionaron.”

\31. Del menú Assign seleccione Column Supports... desplegar las Propiedades de
Apoyo dialogan caja.

\32. En esta caja del diálogo:

• Resalte COL1 en el área de Sostenes de Apoyo.

• Pulse el botón Modify/Show para desplegar las Columna Apoyo Propiedad Datos
caja del diálogo.

• En esta caja del diálogo:

En el Defina Columna Por área verifica que la opción de Propiedades Rectangular
se selecciona.

En las Propiedades Debajo del área de la Tabla tipo 4000 en el Módulo de
Elasticidad revisa caja.

En las Propiedades Debajo de la Tabla verifique ese la Proporción de Poisson es
0.2.

En las Propiedades Debajo del área de la Tabla tipo 18 en la Dimensión de X
revisa caja.

<!-- p. 11 -->

En las Propiedades Debajo del área de la Tabla tipo 18 en la Dimensión de Y
revisa caja.

En las Propiedades Debajo del área de la Tabla tipo 144 en la Altura de la
Columna revisa caja.

Pulse el botón el botón de OK dos veces para terminar todas las cajas del diálogo.

\33. Seleccione el objeto de la línea entre las intersecciones de la reja C-3 y D-4 pulsando
el botón en él.

\34. Del menú Assign seleccione Wall Supports...desplegar las Propiedades de Apoyo
dialogan caja.

\35. En esta caja del diálogo:

• Resalte WALL1 en el área de Sostenes de Apoyo.

• Pulse el botón Modify/Show Property para desplegar los Cortaron Apoyo
Propiedad Datos

• caja del diálogo.

• En esta caja del diálogo:

En el Defina Pared Por área verifica que la opción de las Dimensiones se
selecciona.

En las Propiedades Debajo del área de la Tabla tipo 4000 en el Módulo de
Elasticidad revisa caja.

En las Propiedades Debajo de la Tabla verifique ese la Proporción de Poisson es
0.2.

En las Propiedades Debajo de la Tabla verifica que el Espesor es 12.

En las Propiedades Debajo del área de la Tabla tipo 144 en la Altura de la
Columna revisa caja.

Pulse el botón el botón de OK dos veces para terminar todas las cajas del diálogo.

<!-- p. 12 -->

\36. Seleccione los tres objetos del área que definen la tabla pulsando el botón en cada uno
de ellos. No seleccione los objetos del área que definen las aperturas de la tabla.

\37. Del menú Assign seleccionar Wall Supports...desplegar las Propiedades de la Tabla
dialogan caja.

\38. En esta caja del diálogo:

• En el Tabla Propiedad área momento culminante la propiedad nombró SLAB1 y
el pulse el botón Modify/Show Propierty para desplegar los Datos de Propiedad
de Tabla dialoga caja.

• En esta caja del diálogo:

Acepte el Nombre de Propiedad predefinido, SLAB1.

En el Análisis Propiedad Datos área:

Teclee 4000 en el Módulo de Elasticidad revise caja.

Verifique que la proporción de Poisson es 0.2.

Nota: Nosotros verificaremos el peso de la unidad después.

Teclee 10 en el Espesor del Torcimiento (X) revise caja.

Teclee 10 en el Espesor del Torcimiento (Y) revise caja.

Teclee 10 en el Espesor Torciendo revise caja.

Verifique que la opción de Tipo de Tabla se selecciona.

Verifique que la caja de cheque de Plato Espesa se verifica.

Nota: Verificando la caja de cheque de Plato Espesa dice al programa considerar
esquila de la tabla deformaciones en el análisis. Si esta caja no se verifica entonces que
las deformaciones de esquila de tabla no son incluidas en el análisis.

En el Plan Propiedad Datos área:

Teclee 10 en el Espesor revise caja.

<!-- p. 13 -->

Admita valores predefinidos a la X Tapa Cima, Y Tapa Cima, X Tapa
Fondo y Y Tapa Fondo.

Verifique la Fuerza Concreta, el f'c es 4.

Verifique la Tensión del Rendimiento Reforzando, el fy es 60.

Verifique que el No la caja de cheque de Plan no se verifica.

Pulse el botón de OK dos veces para asignar esta propiedad de la tabla.

\39. Pulse el botón la gota abajo la caja en la barra de estado cambiar las unidades al kip-

ft.

\40. Del menú Define seleccionar Slab Properties...desplegar las Propiedades de la Tabla
dialogan caja.

\41. En esta caja del diálogo:

• En el Tabla Propiedad área momento culminante la propiedad nombró SLAB1 y
el pulse el botón Modify/Show Propierty para desplegar los Datos de Propiedad
de Tabla dialoga caja.

• En esta caja del diálogo:

Verifique que el peso de la unidad es 0.15.

Pulse el botón de OK dos veces para terminar todas las cajas del diálogo.

\42. Del menú Define seleccione Static Load Cases...para desplegar la Carga Caso
Nombres diálogo caja Estática.

\43. En esta caja del diálogo:

• Teclee DL en la Carga revise caja.

• Teclee 3 en el Multiplicador de Desviación de Término Largo que revisa caja, si
en él no se entra ya.

Nota: El multiplicador en término desviaciones largas es sólo activo para el análisis
resquebrajado, no es activo para el análisis normal. El multiplicador de desviación de
longterm se piensa toaccount para los efectos de arrástrese y encogimiento. Un
multiplicador de desviación de longterm de 1 esencialmente los medios que la desviación
del longterm es igual a la desviación inmediata, eso es, no hay ninguna desviación
adicional debido arrastrarse y encogimiento para ese caso de carga. Un multiplicador

<!-- p. 14 -->

del longterm de tres medios que la desviación del longterm es igual a tres veces la
desviación inmediata, eso es, la desviación adicional debido arrastrarse y el
encogimiento es igual a dos veces la desviación inmediata para ese caso de carga.

• Pulso el botón Modify Load.

• Teclee LL en la Carga revisan caja.

• Seleccione el del de Viva la Tipo gota-abajo la caja.

• Teclee 0 el del en Mismo Multiplicador del Peso revisan caja.

• Teclee 1 el del en Multiplicador de Desviación del Largo de Término revisan caja.

• Pulso el botón Add New Load

• Pulso el botón de OK.

\44. Pulse el botón el Restaure botón de la Selección Anterior en la barra de
herramientas principal seleccionar los tres objetos del área que definen la tabla de nuevo
(no incluyen los objetos del área que definen las aperturas de la tabla).

\45. Del menú Assign seleccione Surface Loads...desplegar la Superficie Carga caja del
diálogo.

\46. En esta caja del diálogo:

• Verifique que DL cargan que el caso se selecciona en el Nombre de Caso de
Carga gota-abajo la caja.

• Teclee .05 en la Carga por el Área revise caja.

Nota: Desde las unidades actuales los kips y pies están, 0.05 son equivalentes a 50 psf.

Nota: En SAFE, las cargas verticales positivas actúan que se extiende hacia abajo.

• Pulse el botón el botón de OK para asignar la carga de la tabla uniforme.

\47. Pulse el botón el Restaure botón de la Selección Anterior en la barra de
herramientas principal seleccionar los tres objetos del área que definen la tabla de nuevo
(no incluso los objetos del área que definen las aperturas de la tabla).

<!-- p. 15 -->

\48. Del menú Assign seleccione Surface Loads... desplegar la Superficie Carga caja del
diálogo.

\49. En esta caja del diálogo:

• Seleccione que los LL cargan caso del Nombre de Caso de Carga gota-abajo la
caja.

• Teclee .1 (equivalente a 100 psf) en la Carga por el Área revise caja.

• Pulse el botón de OK para asignar la carga de la tabla uniforme.

\50. Pulso el botón Show Undeformed Shape para quitar las cargas desplegadas de
la superficie.

\51. Pulse el botón Draw Quadrilateral Area Object en la barra de herramientas
lateral (o selecciona Draw Quadrilateral Area Object del menú Draw).

\52. Dibuje un objeto del área solo pulsando el botón en intersecciones de la reja E-5 y F-5
y entonces el pulsando el botón doble en reja intersección E-3.

\53. Pulse el botón Pointer/Select abrochan para cambiar de Dibujo modo para
Seleccionar.

\54. Pulse el botón en el objeto del área arrastrado justo para seleccionarlo.

\55. Del menú Assign seleccione Surface Loads...desplegar la Superficie Carga caja del
diálogo.

\56. En esta caja del diálogo:

• Seleccione que los LL cargan caso del Nombre de Caso de Carga gota-abajo la
caja.

• Teclee .15 (equivalente a 150 psf) en la Carga por el Área revise caja.

Nota: Esta carga del área ya se agregará a la carga del área de 0.1 ksf asignó para dar
una carga total de 0.25 ksf (250 psf).

• Pulse el botón de OK para asignar la carga de la tabla uniforme.

\57. Pulso el botón Show Undeformed Shape para quitar las cargas desplegadas de
la superficie.

<!-- p. 16 -->

\58. Pulse el botón en los dos puntos a las esquinas de la apertura entre la columna línea C
y D donde las cargas del punto serán asignadas (esquinas la línea de la columna más
cercana D) para seleccionarlos.

\59. Del menú Assign seleccione Point Loads... desplegar el Punto Carga caja del
diálogo.

\60. En esta caja del diálogo:

• Verifique que DL cargan que el caso se selecciona en el Nombre de Caso de
Carga gota-abajo la caja.

• En el área de Cargas tipo 4 en la Carga Vertical revisa caja.

• Pulse el botón el botón de OK para asignar las cargas del punto.

\61. Pulse el botón 3D View en la barra de herramientas principal conseguir una
vista mejor de las cargas del punto aplicadas.

\62. Pulse el botón 2D View en la barra de herramientas principal devolver a una
vista del plan.

\63. Pulse el botón el Restaure botón de la Selección Anterior en la barra de herramientas
principal seleccionar de nuevo de nuevo las dos junturas.

\64. Del menú Assign seleccione Point Loads...desplegar el Punto Carga caja del diálogo.

\65. En esta caja del diálogo:

• Seleccione que los LL cargan caso del Nombre de Caso de Carga gota-abajo la
caja.

• En el área de Cargas tipo 3 en la Carga Vertical revisa caja.

• Pulse el botón el botón de OK para asignar las cargas del punto.

\66. Pulse el botón Perspective Toggle en la barra de herramientas principal
conseguir una vista mejor de las cargas del punto aplicadas.

\67. Pulse el botón Perspective Toggle en la barra de herramientas principal
devolver a una vista del plan.

<!-- p. 17 -->

\68. Pulso el botón Show Undeformed Shape para quitar las cargas del punto
desplegadas.

\69. Del menú Define seleccione Load Combinations... desplegar las Combinaciones de
Carga dialogan caja.

\70. En esta caja del diálogo:

• Pulse el botón Add New Combo abrochan para desplegar los Datos de
Combinación de Carga dialogo caja.

• En esta caja del diálogo:

Teclee DISPL (corto para el desplazamiento) en el Nombre de Combinación de
Carga revise caja.

Teclee DL + LL Para los Desplazamientos en el Título revisan caja.

En el Nombre del Caso gota-abajo la caja verifique el DL Carga Caso se
selecciona.

Verifique que en 1 se entra en el Factor de la Balanza revise caja.

Pulse el botón Add.

Seleccione LL Caso de Carga del Nombre del Caso drop-down caja.

Pulse el botón Add.

Pulse el botón de OK dos veces para terminar todas las cajas del diálogo.

\71. Del menú Analyze seleccione Set Options para desplegar las Opciones del Análisis
dialogo caja.

\72. En esta caja del diálogo:

• En el área de Tipo de Análisis seleccione la opción de las Desviaciones Normal y
Resquebrajada.

• Acepte la dimensión de malla de máximo predefinida de 4 pies.

Nota: para enredar automáticamente primero al modelo el programa desarrolla una
malla que está roto en cada línea de la reja, al borde de cualquier área objeta, a los
extremos de cada línea objete y a cada objeto del punto. Si la dimensión de cualquier
elemento enredara de esta manera excede la dimensión de malla de máximo especificada

<!-- p. 18 -->

entonces esos elementos se subdividen tal que la dimensión de malla de máximo ya no se
excede.

Nota: en general, el tamaño de malla de máximo debe ser basado en la longitud del
palmo. Es práctica buena para tener cuatro elementos por lo menos en un palmo, y
generalmente no es necesario tener más de ocho elementos en un palmo.
Así si la longitud del palmo típica está menos de dieciséis pies, puede ser aconsejable
reducir el tamaño de malla de máximo predefinido a algo menos de 4 pies.

Nota: La malla automáticamente generada por el programa puede ser vista pulsando el

botón Set Objects la barra de herramientas principal (o seleccionando Set Object
Options...del menú de View) desplegar la caja de diálogo de Objetos Fija, verificando la
Muestra Malla cheque caja en el área de las Opciones, y pulsando el botón el botón de
OK. Usted puede apagar el despliegue de por de malla de la que un-verifica caja del
esta.

• Pulse el botón de OK.

\73. Pulse el botón Run Analysis en la barra de herramientas principal (o seleccione
Run Analysis del menú Analysis).

\74. Cuando el análisis es cheque completo los mensajes en la ventana del Análisis (debe
haber ninguna advertencia o errores) y entonces pulsa el botón de OK para cerrar la
ventana del Análisis.

\75. Pulse el botón en la ventana de vista de plan para asegurarse que es activo.

\76. Pulse el botón Show Static Deformed Shape en la barra de herramientas
principal (o seleccione Show Static Deformed Shape del menú Display) para desplegar
la caja de diálogo de Forma Deformada.

\77. En esta caja del diálogo:

• DISPL Combo selecto de la Carga gota-abajo la caja.

• En el área de Opciones de Despliegue verifique que el Desplazamiento Contornea
que la caja del cheque se verifica.

• En el área de Opciones de Despliegue seleccione la opción Elástica.

• Pulse el botón de OK para desplegar la forma deformada.

<!-- p. 19 -->

\78. Mueva el cursor del ratón encima del elementos del los de la tabla del la el y prado el
desplazamiento valora en el izquierdo-mano esté al lado de de la barra del la del fondo de
al de estado de la ventana del l SAFE.

\79. Pulse el botón Show Static Deformed Shape en la barra de herramientas
principal (o seleccionar Show Static Deformed Shape del menú Display) para desplegar
la caja de diálogo de Forma Deformada.

\80. En esta caja del diálogo:

• DISPL Combo selecto de la Carga gota-abajo la caja si ya no se selecciona.

• En el área de Opciones de Despliegue verifique que el Desplazamiento Contornea
que la caja del cheque se verifica.

• En el área de Opciones de Despliegue seleccione el Término Largo la opción
Resquebrajada.

• Pulse el botón de OK para desplegar la forma deformada.

\81. Mueva el cursor del ratón encima del elementos del los de la tabla del la el y prado el
desplazamiento valora en el izquierdo-mano esté al lado de de la barra del la del fondo de
al de estado de la ventana del la SAFE.

Nota: el podrían compararse término desviaciones largas Resquebrajadas contra el
desviaciones elásticas en ventanas del por laterales lateral.

\82. Del menú Options seleccione Preferentes… y entonces selecciona la Etiqueta
Concreta.

\83. En esta caja del diálogo:

• Verifique que ese ACI 318-95 se selecciona en el Código del Plan Concreto gota-
abajo la caja.

• Verifique eso en el de Refuerzo Resultado el Unidades área el Sq-en la y la
opción del Sq-in/ft se selecciona.

• Pulse el botón el botón de OK.

\84. En el menú Design escoge Select Design Combos para desplegar la Carga del Plan
Combinaciones Selección diálogo caja.

\85. En esta caja del diálogo:

<!-- p. 20 -->

• En el Plan Combos listan caja pulse el botón en DCON2 para resaltarlo y
entonces pulse el botón de Show.

• Note que esta combinación de carga se define como 1.4DL + 1.7LL.

Nota: SAFE automáticamente crea combinaciones de carga de plan basadas en el código
del plan seleccionado y en los tipos de carga estáticos. En este caso donde los tipos de
carga estáticos definidos están MUERTOS y VIVEN (vea Static Load Cases adelante del
menú Define) y el código del plan es ACI 318-95, el programa crea dos casos de carga
automáticamente.

Ellos tienen 1.4DL años (DCON1) y 1.4DL + 1.7LL (DCON2).

• Pulse el botón de OK dos veces para terminar todas las cajas del diálogo.

\86. En el menú Design seleccione Start Design.

\87. Cuando el plan está completo que el refuerzo de la X-tira calculado se despliega en
pulgadas del cuadrado para cada uno de las tiras del plan. Nota que usted puede ejecutar
su cursor encima de este refuerzo y el refuerzo requerido se despliega en el lado de la
izquierdo-mano de la barra de estado al fondo de la ventana SEGURA.

Nota: el usted de Si ninguna especifica por lo menos entonces una tira del plan de la
tabla que el programa creará una tira del plan del tabla automáticamente para cada
rema / la columna de la malla del la. Puesto que nosotros no creamos ninguna tira de
plan de tabla en este ejemplo, el programa creó automáticamente el plan despoja
mostrado ahora y ellos corresponden a la malla.

\88. Del menú Design seleccione Display Slab Design Info... para desplegar la Tabla que
Refuerza caja del diálogo.

\89. En esta caja del diálogo:

• En el Escoge área de Dirección de Tira verifica que la X Dirección Tira opción es
escogida.

• En el Tipo del Despliegue Reforzando seleccione el Número de Muestra de
opción de las Barras y entonces seleccione #6 del asociado gota-abajo la caja.

• Pulse el botón de OK.

\90. El refuerzo de la X-tira calculado que muestra el número requerido de #6 barras para
cada uno de las tiras del plan se despliega ahora. Nota que usted puede ejecutar su cursor
encima de este refuerzo y el refuerzo requerido en pulgadas del cuadrado se despliega en
el lado de la izquierdo-mano de la barra de estado al fondo de la ventana SEGURA.

<!-- p. 21 -->

\91. Pulse el botón Show Slab Forces en la barra de herramientas principal (o
seleccione Show Slab Forces...del menú Display) desplegar la Tabla Fuerza caja del
diálogo.

\92. En esta caja del diálogo:

• DISPL Combo selecto de la Carga gota-abajo la caja.

• Verifique que la opción de Mxx se selecciona en el área del componente.

• Pulse el botón de OK.

\93. Los momentos del X-dirección se despliegan ahora. Nota que usted puede ejecutar su
cursor encima del momento contornea y el momento a la situación del cursor se despliega
en el lado de la izquierdo-mano de la barra de estado al fondo de la ventana SEGURA.
