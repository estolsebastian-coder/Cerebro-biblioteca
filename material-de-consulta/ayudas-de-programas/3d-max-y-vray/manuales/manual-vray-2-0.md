---
type: libro
title: "Manual V-Ray 2.0"
author: "Jose Vicente Sanz March"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 60
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/3D MAX Y VRAY/MANUALES/MANUAL VRAY 2.0.pdf"
convertido: 2026-10-16
---

# Manual V-Ray 2.0

> Texto extraído de `AYUDAS DE PROGRAMAS\3D MAX Y VRAY\MANUALES\MANUAL VRAY 2.0.pdf` (60 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



<!-- p. 2 -->

Manual de V-Ray 2.0

Autor: Jose Vicente Sanz March

INDICE

\- VRAY FRAME BUFFER Pag. 2

\- GLOBAL SWITCHES Pag. 6

\- INDIRECT ILUMINATION (GI) Pag. 9

\- CAUSTICS Pag. 13

\- ENVIRONMENT Pag. 15

\- IMAGE SAMPLER (Antialiasing ) Pag. 17

\- COLOR MAPPING Pag. 23

\- CAMERA Pag. 25

\- DEFAULT DISPLACEMENT Pag. 29

\- SYSTEM Pag. 31

\- MATERIALES Pag. 35

\- VRAYLIGHT Pag. 39

\- VRAYSUN Y VRAYSKY Pag. 43

\- VRAYPHYSICALCAMERA Pag. 46

\- V-Ray RT Pag. 49

Manual de Vray 2.0 1

<!-- p. 3 -->

VRAY FRAME BUFFER

General:

Además de la ventana de render de 3ds
Max (RFW o VFB), V-Ray le permite
usar un buffer de V-Ray específico, que
tiene algunas funciones adicionales:

\-Le permite ver todos los elementos de
render en una sola ventana y cambiar
entre ellos fácilmente;

\-Mantiene la imagen en formato
completo de punto flotante de 32 bits;

\- Permite realizar correcciones simples
de color en la imagen renderizada;

\- Le permite elegir el orden en que los
buckets se representan.

El VfB V-Ray también tiene algunas
limitaciones, que se enumeran en la
sección Notas de abajo.

Parámetros:

Show last VFB - Si usted ha renderizado
desde la V-Ray VfB, pero lo han cerrado,
este botón le permite volver a abrirla.

Enable built-in frame buffer - Permite el
uso del Vray frame buffer. Debido a razones
técnicas, el original 3ds Max frame buffer
todavía existe pero no se utilizará cuando el
de Vray este activado con el fin de preservar
el consumo de memoria.

Render to memory frame buffer - esto
abrirá un frame buffer V- Ray y lo usará
para almacenar los datos de color que se
pueden observar mientras se hace el render. Si desea hacer una imagen de alta resolución que
realmente no cabría en la memoria o que puede consumir una gran cantidad de memoria RAM usted
puede desactivar esta función y activar Render to V-Ray raw image file.

Get resolution from 3ds Max - esto hará que el V-Ray VfB tome su resolución del 3ds Max, de la
pestaña common, del output size.

Manual de Vray 2.0 2

<!-- p. 4 -->

Output resolution - esto es la resolución que desea utilizar con el V-Ray frame buffer. Se activa
cuando desactivamos el botón Get resolution from 3ds Max

Pixel aspect - especifica la relación de aspecto de los píxeles de la imagen.

Render to V-Ray raw image file - cuando se activa esta opción, V-Ray escribe directamente en el
disco los datos de imagen RAW, de la vista que se está representando. No almacena los datos en la
RAM, por lo que esta característica es muy útil cuando la resolución es enorme y ayuda a preservar la
memoria. Si desea ver lo que se está representando, puede activar la opción de Generate preview.
Puede especificar un archivo de salida Vrimg o Exr:

Si se especifica un archivo de extensión .Vrimg, el archivo resultante puede ser visto a través del
Archivo> Ver imagen... del menú de 3ds Max, o convertirse en un archivo OpenEXR con la ayuda de la
herramienta vrimg2exr .

Si se especifica una extensión exr., V-Ray escribirá un archivo OpenEXR que se puede utilizar
directamente en 3ds Max o en otras aplicaciones de composición. El archivo contiene todos los
elementos para crear la imagen. Al hacer clic en el botón Examinar, puede especificar el nombre de
archivo si desea guardar la imagen en 16 bits o 32 bits en un archivo .Exr.

Generate preview - esto creará un pequeño previo de lo que se está representando. Si no está
utilizando V-Ray memory frame buffer para así conservar el uso de la memoria (es decir, si Render
to memory frame buffer está apagado), puede utilizar esta función para ver una pequeña imagen de
lo que se está renderizando y detener el proceso, si hay algo que se ve mal.

Save separate render channels - esta opción le permite guardar los canales del VfB en archivos
separados. Utilice el botón Browse ... para especificar la ruta del archivo. Esta opción sólo está
disponible cuando se representa a un frame buffer de memoria. Si la representación se realiza sólo en
un archivo de imagen en bruto, los canales de render se pueden extraer de ese archivo después de
finalizado el procesamiento.

Save RGB y Save Alpha - estas opciones le permiten desactivar los canales RGB y alfa
respectivamente. Esto puede ser útil si sólo desea generar otros canales de representación por ejemplo
el z-buffer u otra cosa. Tenga en cuenta que V-Ray seguirá generando el RGB y canales alfa, sin
embargo, no se guardará.

VfB barra de herramientas:

Esta parte de la barra de herramientas establece el canal
seleccionado, así como el modo de vista previa. Elija los canales
RGB que desea ver con la ayuda de los botones. También puede ver
la imagen renderizada en modo monocromático.

Manual de Vray 2.0 3

<!-- p. 5 -->

Cuando se comparan dos imágenes A / B característica del Historial VFB estos
botones le permiten elegir la dirección de la línea de separación.

Esto guardará la imagen del render actual a un archivo, puede usar esta función mientras se
hace el render.

Abre un archivo .Vrimg para visualizarlo en el VfB V-Ray.

Borra el contenido del frame buffer. Es útil cuando se inicia un render nuevo para evitar
confusión con la imagen anterior.

Esto creará una copia virtual en el frame buffer de 3ds Max del actual de V-Ray, puede
habilitar esta función sobre la marcha, mientras se hace el render.

Esto obligará a V-Ray a comenzar a renderizar desde el bucket que se encuentra más cercano
al puntero del ratón. Arrastre el ratón sobre el frame buffer de V-Ray, mientras que se hace el
render para ver qué Buckers se representan primero. Puede habilitar esta función mientras se
hace el render.

Región de Render: Esta opción le permite hacer un render de una region en el VfB V-Ray.

Enlaza la imagen del VfB V-Ray a Pdplayer.

Render: Inicia la representación.

Esto abrirá el cuadro de diálogo de las correcciones de color que le permitirá definir las
correcciones de color de los distintos canales de color. También mostrará el histograma y las curvas
para modificar la imagen.

Fuerza el color clamping en el VfB V-Ray. Muestra mediante colores ficticios las zonas sobre-

expuestas. Por defecto esta desactivado y muestra el render original.

Muestra el color clamping en el VfB V-Ray. Muestra en blanco sobre gris las zonas sobreexpuestas.

Abrirá de manera permanente el cuadro de diálogo que le dará información sobre el píxel en el
que haga clic con el puntero del ratón (botón derecho del ratón).

Permite a las correcciones de color con niveles. Si no activa este botón no se mostraran.

Permite las correcciones con curva de color, Si no activa este botón no se mostraran.

Activa la corrección de exposición.

Muestra la imagen en el espacio de color sRGB.

Activa la corrección LUT.

Manual de Vray 2.0 4

<!-- p. 6 -->

Muestra el historial de V-Ray VfB.

Permite Conmutar la relación de pixel a 1, si no estuviera renderizado en ese valor.

Activa la visión estereoscópica en rojo / cyan .

Activa la visión estereoscópica en verde / magenta.

VfB Historia:

En V-Ray 2.0, el VfB V-Ray permite al usuario mantener un
historial de imágenes previamente renderizados. Las imágenes se
almacenan como archivos. Vrimg en un lugar especificado por el
usuario. Además de mantener la historia de esta función permite
al usuario establecer una imagen A y B y compararlas en el visor
del VfB.

Enable VFB history – Activa el Historial de Vray.

Options – Abre las opciones que permiten al usuario especificar
la ubicación donde se guarda la historia y la cantidad de espacio
disponible en disco.

Save - Guarda la imagen actual del VfB en el historial.

Load - Carga la imagen seleccionada en el historial.

Remover - Elimina la imagen seleccionada del historial.

Clear - Borra el historial por completo.

Set A - Establece la imagen seleccionada actualmente como la imagen de A/ B en el VfB.

Set B - Establece la imagen seleccionada actualmente como B en la comparación B / A.

Manual de Vray 2.0 5

<!-- p. 7 -->

GLOBAL SWITCHES

General

Los Global Switches le permiten controlar varios aspectos del render de la escena de forma global.

Parámetros

Geometry

Displacement - ativado (por defecto)
o desactivar el mapeo de
desplazamiento propio de V-Ray.
Tenga en cuenta que esto no tiene
ningún efecto sobre la asignación de
desplazamiento estándar de Max, que
puede ser controlado a través del
parámetro correspondiente en el
cuadro de diálogo Renderizar escena.

Force back face culling - activa o
desactiva (por defecto) la cara
posterior de los polígonos en el render
desde la cámara y para las sombras
raytrace. Cuando esta opción está
activada, las superficies de los objetos
con las normales dando la espalda a la cámara (o la fuente de luz, las sombras raytrace) aparecerán
totalmente transparentes. Esto permite observar el interior de objetos cerrados cuando la cámara está
fuera.

Lighting

Lights - activa o desactiva las luces de toda la escena. Tenga en cuenta que si se desactiva esta, VRay utilizará las luces por defecto. Si usted no desea la iluminación directa de la escena, se debe
desmarcar tanto esto como los parámetros por defecto las luces.

Default lights - le permite controlar las luces por defecto en la escena.
\-Off- las luces por defecto en la escena estarán siempre desconectadas

\- On - las luces por defecto estarán siempre encendidas cuando no hay luces en la escena o
cuando se ha desactivado la iluminación global (ver el parámetro de luz).

\- Off con GI - las luces por defecto se apagan sólo cuando la iluminación global está habilitada
o si hay luces en la escena.

Hidden lights - activa o desactiva el uso de luces ocultas. Cuando esta opción está activada, las luces
se renderizan independientemente de si están ocultas o no. Cuando esta opción está apagada, las
luces que están ocultas por cualquier motivo (ya sea a propósito o no) no se incluirá en el render.

Shadows - activa o desactiva las sombras a nivel global.

Manual de Vray 2.0 6

<!-- p. 8 -->

Show GI only - cuando esta opción está activada, la iluminación directa no se incluirá en el
renderizado final. Tenga en cuenta que las luces todavía se tendrán en cuenta para el cálculo de GI, sin
embargo al final, sólo se mostrará la iluminación indirecta.

Materials

Reflection/refraction desactiva las reflexiones y las refracciones de todos los materiales de la
escena.
Max depth - permite al usuario limitar globalmente la profundidad en la reflexión / refracción. Cuando
está desmarcada, la profundidad es controlada a nivel local por los materiales / mapas. Cuando se
activa esta opción, todos los materiales y mapas usan la profundidad especificada aquí.

Maps - activa o desactiva los mapas de textura.
Filter maps - activa o desactiva el filtrado de los mapas de textura. Cuando se activa, la profundidad
es controlada a nivel local por la configuración de los mapas de textura. Cuando está desactivado, no
se realiza el filtrado.
Filter maps for GI - activar o desactivar el filtrado de texturas en los cálculos de GI y reflexiones
brillantes / refracciones. Cuando está apagado (por defecto), los mapas de texturas no son filtrados
por GI y reflexiones brillantes / refracciones con el fin de acelerar los cálculos. Si esta opción está
activada, las texturas serán filtradas en estos casos.
Max. trans levels - Controla a qué profundidad los objetos transparentes se renderizan.
Transp. cutoff - Controla hasta que umbral el seguimiento de los objetos transparentes se detendrá.
Si la transparencia acumulada de un rayo se encuentra por debajo de este umbral, dejará de seguirse
este rayo.

Override mtl - esta opción permite al usuario reemplazar todos los materiales de la escena en el
momento de renderizarla. Todos los objetos se representan con el material elegido, si se selecciona
una, o con sus materiales con vista de alambre, si no se especifica el material.
Override Exclude -al hacer clic en este botón aparece el cuadro de dialogo de 3ds Max inclusión /
exclusión que le permite seleccionar exactamente los objetos en los que se les remplazará los
materiales.

Glossy effects - esta opción permite al usuario reemplazar todas las reflexiones brillantes en la
escena por efectos no-brillantes, útil para versiones de prueba.

Indirect ilumination

Don’t render final image - cuando esta opción está activada, V-Ray sólo calcula los mapas
pertinentes de iluminación global (mapas de fotones, light cache, los mapas de irradiación). Esta es
una opción útil si se está calculando los mapas para una animación ya que solo hará los cálculos
guardándolos y no nos renderizará los fotogramas.

Raytracing

Secondary rays bias - un pequeño desplazamiento positivo que se aplicarán a todos los rayos
secundarios del cálculo de iluminación, lo que puede ser utilizado si se superponen las caras en la
escena para evitar las manchas negras que pueden aparecer. Este parámetro también es útil cuando
se utiliza el 3ds Max render to texture para evitar manchas.

Compatibility

Legacy sun / sky / camera models - las versiones anteriores de V-Ray utiliza modelos de cálculo
un poco diferentes para la VRaySun , VRaySky y VRayPhysicalCamera que no tenían tanta precisión
física. Cuando esta opción está desactivada (opción predeterminada), V-Ray utiliza modelos mejorados

Manual de Vray 2.0 7

<!-- p. 9 -->

y más precisos. Cuando está activado, V-Ray cambiará a los viejos modelos para ser compatible con
escenas antiguas. Cuando una vieja escena se abre, V-Ray le mostrará automáticamente un cuadro de
diálogo y le preguntará si desea cambiar esta configuración.
Use 3ds Max photometric scale- cuando está activado (por defecto), esta opción adapta el
VRayLight , VRaySun , VRaySky y VRayPhysicalCamera a las unidades fotométricas utilizadas por 3ds
Max y sus luces fotométricas. Cuando está desactivado, estos plugins funcionan dentro de los valores
que usa V-Ray en sus luces fotométricas, al igual que en versiones anteriores de V-Ray. Mantener esta
opción asegura que un VRayLight con una potencia dada coincidirá con una luz fotométrica 3ds Max
con la misma potencia.

Manual de Vray 2.0 8

<!-- p. 10 -->

INDIRECT ILUMINATION (GI)

General

Aproximaciones para la iluminación indirecta
V-Ray implementa varios métodos para el cálculo de la iluminación indirecta con diferentes soluciones
con una excelente relación entre la calidad y la velocidad:

 Brute force- es el método más simple, la iluminación indirecta se calcula de forma
independiente para cada punto y se calcula lanzando una serie de rayos en diferentes
direcciones desde una semiesfera por encima de ese punto.

Ventajas:
o este método, se conservan todos los detalles (por ejemplo, sombras pequeñas y
afiladas) en la iluminación indirecta;
o está libre de defectos, como el parpadeo en las animaciones;
o no requiere memoria adicional;
o iluminación indirecta en el caso de motion blur de objetos en movimiento se calcula
correctamente.

Desventajas:

o el cálculo es muy lento para imágenes complejas (por ejemplo, la iluminación de
interiores);
o tiende a producir ruido en las imágenes, que sólo puede evitarse aumentando el número
de rayos lanzados, por lo que podría ralentizar aún más el render.

 Irradiance map- este método se basa en el almacenamiento en archivos de la irradiación, la
idea básica consiste en calcular la iluminación indirecta sólo en algunos puntos de la escena, e
interpolar para el resto de los puntos.

Ventajas:
o el irradiance map es muy rápido en comparación con el cálculo directo, especialmente
para las escenas con grandes áreas planas;
o el ruido inherente al cálculo directo es muy reducido;
o el mapa de irradiación se puede guardar y re-utilizado para acelerar los cálculos desde
puntos de vista diferentes para la misma escena y también en animaciones de cámara;
o el mapa de irradiación también se puede utilizar para acelerar la iluminación directa
desde fuentes de luz en la escena, reduciendo considerablemente los tiempos de render.

Desventajas:

o algunos detalles en la iluminación indirecta se puede perder o volverse borrosos debido a
la interpolación;
o si la configuración utilizada es de baja calidad, puede aparecer parpadeo al procesar las
animaciones;
o el irradiance map requiere de memoria adicional;
o la iluminación indirecta con motion blur de objetos en movimiento no es del todo
correcta y puede generar ruido (aunque en la mayoría de los casos esto no se nota).

Manual de Vray 2.0 9

<!-- p. 11 -->

 Photon map - este metodo se basa en el rastreo de partículas emitidas des de las fuentes de
luz y rebotando por el escenario. Esto es útil para las escenas de interiores o semi-interiores
con un montón de luces o ventanas pequeñas. El mapa de fotones por lo general no produce
tan buenos resultados como para ser utilizados directamente, sin embargo, puede ser utilizado
como una aproximación a la iluminación de la escena para acelerar el cálculo de GI a través de
un cálculo directo o un irradiance map.

Ventajas:
o el mapa de fotones puede producir una aproximación a la iluminación de la escena con
gran rapidez;
o el mapa de fotones se pueden guardar y ser re-utilizado para acelerar el cálculo desde
otros puntos de vista diferentes para la misma escena y también en animaciones de
cámara;
o el mapa de fotones es independiente de la vista.

Desventajas:

o el mapa de fotones por lo general no es adecuado para la visualización directa;
o requiere de memoria adicional;
o en la aplicación de V-Ray, la iluminación participación borrosa de movimiento de objetos
en movimiento no es del todo correcto (aunque esto no es un problema en la mayoría de
los casos).
o el mapa de fotones necesidades reales de las luces para poder trabajar, no puede ser
utilizada para producir la iluminación indirecta causada por las luces de medio ambiente
(claro).
o
 Light cache - es una técnica de aproximación de la iluminación global de una escena. Es muy
similar a los mapas de fotones, pero sin muchas de sus limitaciones. El light cache se construye
lanzando muchos fotones desde la cámara. Cada fotón rebota en los objetos de la escena en
una estructura en 3D, muy similar al mapa de fotones. El light cache es una solución universal
GI que se puede utilizar tanto para interiores o escenas exteriores, ya sea directamente o como
una aproximación en el rebote secundario cuando se utiliza junto con el irradiance map o el
método de brute force GI.

Ventajas:
o El light cache es fácil de configurar.
o el decaimiento funciona de manera eficiente con las luces - incluyendo claro, luz propia
los objetos, las luces no-físico, las luces fotométricas, etc Por el contrario, el mapa de
fotones está limitado en los efectos de iluminación que puede reproducir - por ejemplo,
el mapa de fotones no puede reproducir la iluminación de claraboya o de luces omni
estándar sin la atenuación inversa al cuadrado.
o El light cache produce resultados correctos en las esquinas y alrededor de objetos
pequeños. El mapa de fotones, por el contrario, se basa en sistemas de difícil estimación
de densidad, que a menudo producen resultados erróneos en estos casos, ya sea
oscureciendo o aclarando esas áreas.
o en muchos casos, el light cache puede ser visualizado directamente para las vistas
previas muy rápido y de forma suave dándonos una idea de la iluminación de la escena.

Desventajas:

o como el irradiance map, el light cache es dependiente de la vista y se genera para una
determinada posición de la cámara. Sin embargo, genera una aproximación de las partes
visibles directamente de la escena y también - por ejemplo, una caché de luz se puede
aproximar por completo el GI en un cuarto cerrado;
o Actualmente, el light cache sólo funciona con materiales V-Ray;
o como el mapa de fotones, el light cache no es adaptativo. La irradiación se calcula en
una resolución fija, la cual es determinada por el usuario;

Manual de Vray 2.0 10

<!-- p. 12 -->

o el light cache no funciona muy bien con los mapas de relieve, debe combinarlo con el
uso del irradiance map en la GI o brute force si quieres conseguir mejores resultados
con los mapas de relieve.
o La iluminación de la participación borrosa de movimiento de objetos en movimiento no
es del todo correcto, pero es muy suave ya que el caché de la luz difumina GI en el
tiempo y (en comparación con el mapa de irradiación, donde se calcula cada muestra en
un momento determinado de tiempo).

¿Qué método utilizar? Eso depende de la tarea en cuestión.

Rebotes primarios y secundarios
Los controles de iluminación indirecta en V-Ray se dividen en dos grandes apartados: los controles
relativos a rebotes primarios de la difusa y los controles de los rebotes secundarios de la difusa. Un
rebote primario es el primero de los rebotes que efectúa la luz que sale de las fuentes de luz de
nuestra escena. Los secundarios son el resto de rebotes, hasta 3, que realiza la luz en los objetos de
nuestra escena.

Parámetros

On - Activa la iluminación indirecta.

GI caustics
Cáusticas GI representan la luz que
ha pasado por un material difuso y
una o varias reflexiones especulares
(o refracciones). Cáusticas GI puede
ser generada por VraySky, o fuentes
de luz como una luz spot. Sin
embargo, las causticas causadas por
las luces directas, no se puede
simular de esta manera. Debe utilizar
la sección de causticas para la luz
directa. Tenga en cuenta que
cáusticas GI suelen ser difíciles de
muestrear y puede introducir ruido en la solución de GI.

GI caustics Refractive - esto permite que la iluminación indirecta pueda pasar a través de objetos
transparentes (vidrio, etc) . Tenga en cuenta que esto no es lo mismo que las cáusticas, que
representan la luz directa pasando por los objetos transparentes.
GI caustics Reflective- esto permite que la luz indirecta se refleje en los objetos especulares
(espejos, etc). Tenga en cuenta que esto no es lo mismo que las cáusticas, que representan la luz
directa reflejándose en superficies especulares. Esta opción está desactivada por defecto, ya que
suelen contribuir muy poco a la iluminación final, mientras que a menudo producen ruido no deseado.

Post-procesamiento
Estos controles permiten la modificación adicional de la iluminación indirecta, antes de que se agregue
a la representación final. Los valores por defecto aseguran un resultado físicamente correcto, sin
embargo si el usuario lo desea, puede modificar el aspecto de la GI con fines artísticos.
Saturation - Control de la saturación de la GI, un valor de 0,0 significa que todos los colores se
eliminan de la solución GI y tendrá tonos de gris solamente. El valor predeterminado de 1,0 significa
que la solución de GI no se habá modificado. Valores por encima de 1,0 realzan los colores en la
solución de GI.
Contrast - Este parámetro trabaja en conjunto con la base de contraste para aumentar el contraste de
la solución de GI. Cuando el contraste es de 0.0, la solución de GI se vuelve completamente uniforme

Manual de Vray 2.0 11

<!-- p. 13 -->

con el valor definido por la base de contraste. Un valor de 1.0 significa que la solución no se ha
modificado. Los valores superiores a 1,0 aumentar el contraste.
Contrast base - Este parámetro determina la base para el aumento del contraste. En él se definen los
valores de GI que se mantendran durante los cálculos de contraste.

Ambient occlusion
Estos controles le permiten añadir un canal de oclusión ambiental a la solución de iluminación global.
On - activar o desactivar la oclusión ambiental.
Cantidad - la cantidad de oclusión ambiental. Un valor de 0.0 no producirá ninguna oclusión
ambiental.
Radius - Radio de la oclusión ambiental.
Subdivs - determina el número de muestras utilizadas para el cálculo de oclusión ambiental. Los
valores más bajos se calculan más rápido, pero podrían producir ruido.

Primary bounces
Multiplier - este valor determina la potencia de los rebotes primarios y cuanto contribuyen a la
iluminación de la imagen final. Tenga en cuenta que el valor predeterminado de 1,0 produce una
imagen físicamente correcta. Otros valores son posibles, pero no son plausibles físicamente.
GI engine – lista que especifica el método que se utilizará para calcular los rebotes primarios.
Irradiance map - esto hará que V-Ray use un mapa de radiación en los rebotes primarios. Ver
irradiance map para obtener más información.
Photon map - si selecciona esta opción, V-Ray usará un mapa de fotones para calcular los rebotes
primarios. Por lo general, no produce buenos resultados insuficientes para un render a calidad final
cuando se utiliza como motor principal de GI. Ver photon map para obtener más información.
Brute force - la selección de este método hará que V-Ray use el cálculo directo de los rebotes
primarios. Ver brute force para más información.
Light cache - esto selecciona el light cache como el principal motor de GI. Ver light cache para
obtener más información.

Secondary bounces
Multiplier – este valor determina la potencia de los rebotes secundarios en la iluminación de la
escena. Los valores cercanos a 1.0 pueden tender a lavar la escena, mientras que los valores alrededor
de 0.0 pueden producir una imagen oscura. Tenga en cuenta que el valor predeterminado de 1,0
produce resultados físicamente correctos. Mientras que otros valores son posibles, no son físicamente
posibles.
GI engine - Este parámetro determina la forma en que V-Ray calculará los rebotes secundarios.
None - no se calcularán rebotes secundarios. Utilice esta opción para producir imágenes de luz
natural, sin alteración del color por las luces indirectas.
Photon map - selecciona esta opción, V-Ray usará un mapa de fotones para calcular los rebotes
secundarios. Por lo general, no produce buenos resultados dando poca calidad cuando se utiliza como
principal motor de GI. Ver photon map para obtener más información.
Brute force - seleccionando este método hará que V-Ray use el cálculo directo en los rebotes
secundarios. Ver brute forcé para más información.
Light cache - selecciona el light cache como principal motor de GI. Ver light cache para obtener más
información.

Notas

 Usted calculará la iluminación con precisión física si establece tanto en los multiplicadores de GI
primaria y secundaria un valor predeterminado de 1,0. Mientras que otros valores son posibles,
no producen un resultado preciso y real.

Manual de Vray 2.0 12

<!-- p. 14 -->

CAUSTICS

General

V-Ray es compatible con la representación de los efectos cáusticos de la luz. Con el fin de producir este
efecto debe tener generadores y receptores de las cáusticas en la escena (para información sobre
cómo hacer que un objeto sea un generador/ receptor de cáusticas lee la configuración de objetos y
secciones ajustes Luces en los parámetros de Render> Sistema> Configuración del objeto / luz . La
configuración de esta sección controlan los parámetros de la generación del mapa de fotones.
Para el cálculo de los efectos cáusticos, V-Ray utiliza una técnica conocida como mapeo de fotones. Es
una técnica de dos pasos. El primer paso consiste en disparar partículas (fotones) a partir de las
fuentes de luz en la escena, su rastreo a medida que rebotan dentro de la escena, y el registro de los
lugares donde los fotones chocan con las superficies de los objetos. El segundo paso es la presentación
final, cuando las cáusticas se calculan mediante el uso de técnicas de estimación de densidad en los
fotones almacenados durante el primer paso.

Parámetros

On – activa la representación de
cáusticas.

Multiplier - este multiplicador
controla la fuerza de las cáusticas. Es
global y se aplica a todas las fuentes
de luz que generan cáusticas. Si
desea multiplicadores diferentes para
las fuentes de luz diferentes se debe
usar la configuración de luz local.
Nota: este multiplicador es
acumulativo con los multiplicadores
en los ajustes de luz local.

Search dist. - cuando V-Ray tiene
que hacer el efecto cáustico en un
punto de la superficie determinada,
la búsqueda de un número de
fotones en esa superficie en los alrededores del punto de sombra (área de búsqueda). El área de
búsqueda, de hecho, es un círculo con centro en el fotón original y su radio es igual al valor de la
distancia de búsqueda. Los valores más bajos producen más nítidez, pero tal vez más ruido en las
cáusticas, los valores más grandes producen un efecto suave, pero cáusticas borrosas.
Max photons - Este es el número máximo de fotones que se tendrán en cuenta cuando se representa
el efecto cáustico sobre una superficie. Los valores más bajos producen menos fotones que se
utilizarán y la caustica será más nítida, pero tal vez con más ruido. Los valores más grandes producen
más suavidad, pero cáusticas borrosas. El valor especial de 0 significa que V-Ray utilizará todos los
fotones que se encuentre dentro del área de búsqueda.
Max density- este parámetro le permite limitar la resolución (y por lo tanto la memoria) del mapa de
fotones cáusticos. Cada vez que V-Ray necesita almacenar un nuevo fotón en el mapa de fotones
cáusticos, por primera vez se verá si hay otros fotones a una distancia determinada por la densidad
máxima. Si ya existe un fotón adecuado en el mapa, V-Ray acaba de añadir la energía del fotón nueva
a la que en el mapa. De lo contrario, V-Ray va a almacenar el nuevo fotón en el mapa de fotones.
Usando esta opción le permite disparar fotones (y por lo tanto obtener resultados más suaves),
manteniendo el tamaño del mapa de fotones cáusticos manejable.

Manual de Vray 2.0 13

<!-- p. 15 -->

Mode - controla el modo de cálculo del mapa de fotones:

New map - cuando se selecciona esta opción un nuevo mapa de fotones se generan. Que se
sobreponen a cualquier mapa de fotones previos sobrantes de la representación anterior.

Save to file - Active este botón si desea guardar un mapa ya generado de fotones en un archivo.

From file - cuando se habilita esta opción V-Ray no calculará el mapa de fotones, sino que lo cargará
desde un archivo. Pulse el botón browse a la derecha para especificar el nombre del archivo.
File - el nombre del archivo con el mapa de fotones cáusticos que se carga cuando el modo se ajusta a
“from file”.
Don’t delete- cuando está activado, V-Ray mantendrá el mapa de fotones en la memoria después de
que haya terminado la representación de la escena. De lo contrario el mapa será eliminado de la
memoria. Esta opción puede ser especialmente útil si se desea calcular el mapa de fotones para una
escena en particular sólo una vez y volver a utilizarla para el resto de renders.
Auto save - cuando está activada, V-Ray guarda automáticamente el mapa de fotones cáusticos para
el archivo asignado cuando finaliza el render.
Switch to saved map - esta opción sólo está disponible si está en modo “auto save”. Hará que V-Ray
se ajuste automáticamente al modo “from file” con el nombre del archivo del mapa que acaba de
guardar.

Notas

 Las causticas también dependen de la configuración de la fuente de luz individual.

Manual de Vray 2.0 14

<!-- p. 16 -->

ENVIRONMENT

General

La sección de Environment en V-Ray ofrece opciones para especificar un color o un mapa de textura
para ser utilizado durante el cálculo de la GI y los cálculos de reflexión / refracción. Si no se especifica
un color / mapa entonces es usado el color de fondo y el mapa que se especifica en el cuadro de
diálogo de environment que 3ds Max utiliza por defecto.
Si en esta sección no modificamos nada se utilizaran los parámetros que están establecidos en el
environment de MAX, para conseguir acabados foto-realistas no es recomendable activar esta parte, lo
aconsejable es utilizar las opciones del environment de MAX.

Parámetros

GI Environment (skylight)
Este botón le permite reemplazar la configuración de 3ds Max para el environment para el cálculo de la
iluminación indirecta. El efecto de cambiar el entorno de la GI es similar a utilizar un VraySkylight.
On - enciende y apaga el GI Environment override.
Color - permite especificar un color en el environment. Tenga en cuenta que esto se ignora si hay una
textura aplicada.
Multiplier - un multiplicador para el valor del color. Tenga en cuenta que el multiplicador no afecta a
la textura del environment (si existe). Utilice un Output map para controlar el brillo si el mapa en sí
no tiene controles de brillo.
Textura - le permite elegir un mapa para aplicarlo como entorno. Tenga en cuenta que si está
presente, la textura reemplaza el color especificado.

Reflection / refraction environment override
Este grupo le permite reemplazar la configuración de 3ds Max para los cálculos de las reflexiones y
refracciones del entorno. Tenga en cuenta que también puede cambiar la reflexión / refracción del
entorno sobre el propio material o también en el mapa. Si no habilita Refraction environment
override, este grupo de control afecta tanto a las reflexiones como a las refracciones. Si se habilita la
Refraction environment override, entonces este grupo sólo afecta a los reflejos.

On - con esta opción activada V-Ray utiliza el color especificado y textura durante los cálculos de
reflexión / refracción.
Color - le permite especificar el color del environment para las reflexiones / refracciones. Esto es
ignorado, si hay una textura aplicada.
Multiplier - un multiplicador para el valor del color. Tenga en cuenta que el multiplicador no afecta a
la textura del environment (si existe). Utilice un Output map para controlar el brillo si el mapa en sí
no tiene controles de brillo.
Textura - le permite elegir una textura para el environment. Tenga en cuenta que si se especifica,
este anula la textura de color.

Manual de Vray 2.0 15

<!-- p. 17 -->

Refraction environment override
Este grupo permite anular el environment para los rayos de refracción solamente. Cuando esta
anulación se desactiva, V-Ray utiliza el entorno especificado en el grupo de reflexión / refracción en el
cálculo de las refracciones.

On – Activa el Refraction environment override.
Color - especifica el color del Refraction environment override. Este color se ignora si hay una
textura aplicada.
Multiplier – es un multiplicador para el valor del color. Tenga en cuenta que el multiplicador no afecta
a la textura del environment (si existe). Utilice un Output map para controlar el brillo si el mapa en sí
no tiene controles de brillo.
Textura - especifica la textura para el Refraction environment override. Tenga en cuenta que si
está presente, esta textura reemplaza el color especificado.

Manual de Vray 2.0 16

<!-- p. 18 -->

IMAGE SAMPLER (Antialiasing )

El aliasing es el artefacto gráfico
característico que hace que en una
pantalla ciertas curvas y líneas
inclinadas presenten un efecto visual
tipo "sierra" o "escalón". El aliasing
ocurre cuando se intenta representar
una imagen con curvas y líneas
inclinadas en una pantalla,
framebuffer o imagen, pero que
debido a la resolución finita del
sustrato resulta que éste sea incapaz de representar la curva como tal, y por tanto dichas curvas se
muestran en pantalla dentadas al estar compuestas por pequeños cuadrados (los píxeles).

El antialiasing es un algoritmo que permite evitar estos artefactos asociados al aliasing gráfico, como
por ejemplo los patrones de Moiré. V-Ray implementa tres algoritmos para el muestreo de una imagen,
podemos verlos en la imagen de arriba.
El siguiente ejemplo muestra la diferencia básica entre una imagen sin antialiasing, y otra con él:

Antialiasing Fixed a 1 Antialiasing Adaptative subdivision a -1,2

Tipos:

IMAGE SAMPLER FIXED:

Es la muestra de imagen más simple, toma
un número fijo de muestras por pixel que le
indicamos en la única ventana que tiene
llamada Subdivs. Cuando está establecido en
1, se toma una muestra en el centro de cada píxel. Si esta es superior a 1, las muestras se distribuyen
dentro del píxel. El número real de píxeles es el cuadrado de este parámetro (por ejemplo, 4
subdivisiones producen 16 muestras por píxel).

Manual de Vray 2.0 17

<!-- p. 19 -->

Esta solución no es la más rápida ya que no utiliza ningún tipo de optimización en los cálculos, aunque
por eso también es la más exacta si los valores de subdivisión son suficientemente altos. Es la menos
utilizada.

IMAGE SAMPLER ADAPTIVE DMC:

Es la muestra de imagen de dos niveles,
toma un número variable de muestras por
píxel en función de la diferencia en la
intensidad de los píxeles.

Este es el preferido de toma de muestras para las imágenes con un montón de pequeños detalles
(como VRayFur, por ejemplo) y / o efectos de desenfoque (DOF, el desenfoque de movimiento,
reflexiones glossy, etc.) También consume menos memoria que la toma de muestras de adaptive
subdivision.

Min subdivs - determina la cantidad inicial (como mínimo) de muestras tomadas para cada píxel.
Rara vez es necesario aumentar a más de 1, excepto si necesitas renderizar líneas u objetos muy
delgados, u objetos en movimiento si se utiliza el desenfoque de movimiento. El número real de
píxeles es el cuadrado de este número (por ejemplo, 4 subdivs producen 16 muestras por píxel).
Max subdivs - determina el número máximo de muestras para cada pixel. El número máximo real
de toma de muestras es el cuadrado de este número (por ejemplo, 4 subdivs produce un máximo de
16 muestras). Tenga en cuenta que V-Ray puede tomar menos que el máximo número de muestras,
si la diferencia en la intensidad de los píxeles vecinos es lo suficientemente pequeña.
Use DMC sampler thresh - cuando este se encuentra activado (por defecto), V-Ray va a utilizar el
umbral indicado en la DMC de toma de muestras para determinar si las muestras son más necesarios
para un pixel. Cuando está desactivado, el parámetro Clr thresh se utilizará en su lugar.
Clr thresh - el umbral que se utilizará para determinar si un pixel necesita un mayor número de
muestras. Esto se ignora si el Use DMC sampler thresh está activado.
Show samples - si este está activado, V-Ray mostrará una imagen donde el brillo de los píxeles es
directamente proporcional al número de muestras tomadas en este píxel. Esto es útil para afinar el
antialiasing de la imagen.

DMC SAMPLER:

V-Ray utiliza una variante del algoritmo de
muestreo Monte Carlo llamado
Deterministic Monte Carlo (DMC).

Adaptive amount - Controla el grado en que el número de muestras depende de la cantidad de
glossy del material que se renderiza. También controla el número mínimo de muestras que se
tomarán. Digamos que se adapta a los requerimientos de la zona que está renderizando.
Un valor de 1,0 significa la plena adaptación; un valor de 0,0 significa que no hay adaptación, no es
recomendable bajar de 0,5 ya que los tiempos de render se eternizan.

Min samples - Determina el número mínimo de muestras que deben tomarse antes de la terminación
anticipada en la que se utiliza el algoritmo. Los valores más altos harán los cálculos del algoritmo más
fiable.

Manual de Vray 2.0 18

<!-- p. 20 -->

Noise threshold – Es el umbral que utiliza Vray para determinar cuando un valor es "suficientemente
bueno" para ser utilizado. Esto se traduce directamente a ruido en el render final. Los pequeños
valores significa menos ruido, más muestras y de mayor calidad. Un valor de 0,0 significa que la
adaptación no se van a realizar, en este caso Vray no admite nada de ruido.

Global subdivs multiplier - este valor multiplica todos los valores en todas partes durante el render;
se utiliza para rápidamente aumentar o disminuir la toma de muestras de calidad en toda la escena.
Esto afecta a todo, excepto para el lightmap, mapa de fotones y cáusticas. Todo lo demás (DOF,
motion blur, irradiance map, brute force GI, zona de luces, zona de sombra, brillo reflexiones y
refracciones) se ve afectada por este parámetro.

Time independent - Cuando esta opción está activada, el patrón de muestreo utilizará el mismo
marco para encuadrar toda una animación. Dado que esto puede ser indeseable en algunos casos,
puede desactivar esta opción para que cambie el patrón con el tiempo.

DMC SAMPLER, CALIDAD CONTRA VELOCIDAD:

Puede utilizar el DMC SAMPLER para el control de la calidad del render, por ejemplo:
Para la más baja calidad:
aumentar el Adaptive amount
aumentar el Noise threshold
reducir Min samples
Para mayor calidad:
disminuir el Adaptive amount
disminuir el Noise threshold
aumentar Min samples

Ejemplos, comenzamos con mayor calidad y mas tiempo de render y bajamos a menos:

Adaptive amount: 0.7 Noise threshold: 0.001 Min samples: 40

Manual de Vray 2.0 19

<!-- p. 21 -->

Adaptive amount: 0.8 Noise threshold: 0.01 Min samples: 30

Adaptive amount: 0.9 Noise threshold: 0.05 Min samples: 15

Manual de Vray 2.0 20

<!-- p. 22 -->

Adaptive amount: 1 Noise threshold: 0.1 Min samples: 5

ADAPTIVE SUBDIVISION:

Esta es una toma de muestras avanzada de
imagen capaz de undersampling (tomando
menos de una muestra por cada pixel). En
ausencia de efectos borrosos (GI directa,
DOF, brillante reflexión / refraction etc), este
es el mejor image sampler en V-Ray. En promedio se necesita un menor número de muestras (y, por
tanto, menos tiempo) para lograr la misma calidad de imagen que con otros image samplers. Sin
embargo, con texturas detalladas y / o efectos borrosos, puede ser más lenta y produce peores
resultados que los otros dos métodos. Este método consume más memoria que los otros dos
muestreadores.

Min. rate - Controla el número mínimo de muestras por píxel. Un valor de cero significa una
muestra por cada pixel; -1 significa una muestra cada dos píxeles; -2 significa una muestra cada
cuatro pixeles, etc
Max. rate - Controla el número máximo de muestras por píxel; cero significa una muestra por cada
píxel, 1 significa cuatro muestras, 2 significa ocho muestras, etc
Clr thresh - Determina la sensibilidad del sistema de muestreo a los cambios en la intensidad de luz y
color de los píxeles. Valores más bajos producen mejores resultados, mientras que los valores más
altos aumentaran la velocidad.
Randomize samples - Desplaza las muestras de forma aleatoria para mejorar el antialiasing de
zonas horizontales o verticales.
Object outline – Adapta la toma de muestras con supersamples en los bordes de los objetos(con
independencia de que realmente necesitan ser supersampleados). Esta opción no tiene efecto si DOF o
motion blur está habilitado.
Nrm thresh - Esto supersamplea zonas marcadamente diferentes por las normales. Esta opción no
tiene efecto si DOF o motion blur está habilitado.
Show samples - Si está activado, V-Ray mostrará una imagen donde el brillo de los píxeles es
directamente proporcional al número de muestras tomadas en este píxel. Esto es útil para ajustar el
antialiasing de la imagen.

Manual de Vray 2.0 21

<!-- p. 23 -->

Antialiasing filter:

Los filtros se aplican a nivel de sub-pixel, a lo
largo de los distintos sub-pixel de muestras. Por
lo tanto, aplicando el filtro en el render el
resultado es más preciso que si lo aplicamos
como un efecto posterior. V-Ray puede utilizar
todos los filtros estándares de 3ds Max (con la
excepción de Plate match filter) y produce
resultados similares a los del render scanline.

Hay dos tipos, los que sirven para prevenir y
solucionar efectos indeseables de moiré y los
que aumentan la nitidez de la imagen.

En el primer grupo cabe destacar el filtro de Area, el recomendado para animaciones, ya que es rápido
y soluciona en la mayoria de casos el efecto moiré. Del segundo grupo destacaré los clásicos MitchelNetravali y Catmull-Rom que acentúan notablemente la nitidez de las imágenes, son filtros que no son
recomendados para animación ya que nos obligarían a aumentar la calidad del image sampler que
estemos utilizando y los tiempos podrían aumentar considerablemente. Otro filtro desarrollado por
Vray es el LanczosFilter, más rápido que los anteriores y que también aumenta la nitidez del render.

Manual de Vray 2.0 22

<!-- p. 24 -->

COLOR MAPPING

General

Color mapping (también llamado tone mapping) se puede utilizar para aplicar transformaciones de
color en los tonos de la imagen final. A veces una imagen puede contener un rango más alto de colores
de los que se pueden visualizar en una pantalla de ordenador. Color mapping tiene la tarea de reasignar los valores de la imagen para que se visualice correctamente.

Parámetros

Type - Este es el tipo de
transformación utilizado. Estos son
los tipos posibles:

Linear multiply – con este modo,
simplemente se multiplican los
colores de la imagen final en base a
su brillo de forma lineal.
Componentes de color que son
demasiado brillantes (por encima de 1,0 o 255) se recortarán y no se mostraran. Esto puede dar lugar
a manchas de quemado cerca de fuentes de luz brillante, se utiliza principalmente en exteriores.

Exponential - este modo, se saturan los colores en función de su brillo. Esto puede ser útil para
prevenir que se queme la imagen en las zonas muy brillantes (por ejemplo alrededor de fuentes de luz,
etc). Este modo no limita los colores brillantes, sino que se los satura. Indicado para interiores.

Exponential VHS - este modo es muy similar al modo exponencial, pero conservará el tono del color
y la saturación, en vez de lavar el color hacia el blanco.

Intensity exponential - Este modo es similar al exponencial, pero hace que se conserve la relación
de los componentes de color RGB y sólo afectará a la intensidad de los colores.

Gamma correction - Este modo aplica una curva de gamma a los colores. En este caso, el
multiplicador de Dark es un multiplicador general de los colores antes de que se corrija la gamma. El
multiplicador de Bright es la inversa del valor de gamma (por ejemplo para una gamma de 2.2, el
multiplicador Bright debe ser 0,4545).
Intensity gamma - de este modo se aplica una curva de gamma a la intensidad de los colores, en
lugar de a cada canal (r / g / b) de forma independiente.
Reinhard - este modo es una mezcla entre la asignación de colores exponencial y el modo lineal. Si el
Burn value es de 1,0, el resultado del color mapping es lineal y si el Burn value es 0.0, el resultado
es exponencial.
Dark multiplier - este es el multiplicador de los colores oscuros.
Bright multiplier - esto es el multiplicador de colores brillantes.
Gamma - Este parámetro permite al usuario controlar la corrección de gamma de salida de la imagen,
independientemente del modo de asignación de colores. Tenga en cuenta que el valor es la inversa de
la que se utiliza para el tipo Gamma correction. Por ejemplo, para corregir la imagen de una pantalla
de gamma 2,2, se debe establecer el parámetro Gamma sólo a 2,2.
Sub-pixel mapping - esta opción controla si la asignación de colores se aplicarán a los píxeles de la
imagen final, o también a las muestras sub-pixel. En versiones anteriores de V-Ray, esta opción estaba

Manual de Vray 2.0 23

<!-- p. 25 -->

activa siempre, sin embargo su valor por defecto es ahora de cómo esta produce representaciones más
correctas, especialmente si se utiliza la configuración universal de acercamiento.
Clamp output - si está activada, los colores se ajustaran después de aplicar el color mapping. En
algunas situaciones, esto puede ser indeseable (por ejemplo, si usa una imagen HDR de fondo) - en
este caso, desactive clamp output.
Clamp level - esta opción especifica el nivel en el que los componentes de color se ajustarán, si la
opción de clamp output está encendida.
Affect background - si está desactivado, el color mapping no afecta a los colores que pertenecen a
un segundo plano.
Don’t affect colors (adaptation only) - cuando este parámetro está activo, el color mapping no se
aplicará a la imagen final, sin embargo V-Ray procederá con todos sus cálculos como si el color
mapping se aplicase (por ejemplo, los niveles de ruido se corregirán en consecuencia). Esto puede ser
útil, por ejemplo, si usted sabe que va a aplicar un poco de corrección de color a la imagen más
adelante, pero desea mantener la misma representación en el espacio lineal para aplicar despues
efectos de composición. Tenga en cuenta que la opción de clamp output si esta activada, afectará al
Don’t affect colors .
Lineal work flow - cuando se selecciona esta opción V-Ray aplicará automáticamente la inversa de la
corrección gamma que ha configurado en el campo de gamma para todos los VRayMtl materiales en la
escena Tenga en cuenta que esta opción está destinada a ser utilizada sólo para la conversión rápida
de escenas viejas, escenas que no se crearon con el lineal work flow. Esta opción no es un reemplazo
para el lineal work flow correcto.

Manual de Vray 2.0 24

<!-- p. 26 -->

CAMERA

General

La pestaña cámara controla la forma en que se proyecta la geometría de la escena sobre la imagen.
Tenga en cuenta que si utiliza el VRayPhysicalCamera en la escena, la mayoría de los parámetros de
esta sección seran ignorados, con la excepción de algunos de los parámetros de desenfoque de
movimiento (los de la parte derecha del cuadro de diálogo),

Parámetros

muestras de la geometría. Para objetos en rotación que lo hacen rápidamente (como la hélice de un avión), es
necesario aumentar esto para conseguir que el desenfoque de movimiento se vea correcto. Tenga en cuenta
que a más muestras de la geometría aumentará el consumo de memoria, ya que las copias de la geometría se
guardan en la memoria. También puede controlar el número de muestras de la geometría en función de cada
objeto en el cuadro de diálogo Object properties.

Tipo de cámara
Las cámaras de V-Ray en general recogen los rayos que se han lanzado en la escena, que básicamente
es como la escena se proyecta en la pantalla. V-Ray soporta varios tipos de cámara: Default, esférica,
cilíndrica (punto), cilíndricos (orto), Caja y ojo de pez. Las vistas ortográficas son compatibles también.
Esta sección la usaremos cuando no estemos usando una cámara V-Ray, sino una standard de MAX.

Override FOV - con esta opción se puede anular el ángulo del campo de visión de 3ds Max. Esto es
debido a que algunos tipos de cámara V-Ray pueden llegar a rangos FOV de 0 a 360 grados, mientras
que las cámaras en 3ds Max se limitan a 180 grados.

FOV - aquí se especifica el ángulo de campo de visión (FOV anulación sólo cuando está encendido y el
tipo de cámara actual es compatible con el ángulo del campo de visión).

Manual de Vray 2.0 25

<!-- p. 27 -->

Height - aquí se puede especificar la altura de la parte cilíndrica (orto) de la cámara. Este ajuste sólo
está disponible cuando el tipo de cámara está ajustado a cilíndrica (orto).
Auto-fit - esta opción controla la opción de ajuste automático de la cámara de ojo de pez. Cuando
Auto-fit se activa V-Ray calculará el valor Dist automáticamente de modo que la imagen generada se
ajusta horizontalmente con las dimensiones de la imagen.

Dist - este ajuste se aplica sólo a las cámaras ojo de pez. La cámara de ojo de pez se simula como
una cámara estándar mirando a una esfera que refleja como un espejo (con un radio de 1.0) que
refleja la escena en el obturador de la cámara. El valor Dist determina la distancia desde la cámara
hasta el centro de la esfera (de esta manera gran parte de la esfera será capturada por la cámara).
Nota: esta opción no tiene efecto cuando la opción Ajuste automático está activado.

Curve - este ajuste sólo se aplica a la cámara de ojo de pez. Este ajuste curva la imagen renderizada
deformándola. Un valor de 1,0 corresponde al valor real de un objetivo ojo de pez. A medida que el
valor se aproxima a 0,0 la deformación es mayor. Cuando el valor se aproxima a 2,0 la deformación se
reduce.
Nota: de hecho, este valor controla el ángulo de los rayos que se reflejan en la esfera virtual de la
cámara.

Type - en esta lista puede seleccionar el tipo de la cámara.

Default - se trata de una cámara estenopeica estándar (una cámara fotográfica sin lente, que consiste
en una caja a prueba de luz con un pequeño agujero donde entra luz).

Spherical - esta es una cámara esférica que significa que las lentes de cámara tienen forma esférica.

Cylindrical (point) - con este tipo de cámara todos los rayos tienen un origen común - son arrojados
desde el centro del cilindro. En la dirección vertical de la cámara actúa como una cámara default y en
la dirección horizontal actúa como una cámara esférica.

Cylindrical (orto) - en la dirección vertical de la cámara actúa como un punto de vista ortográfico y en
la dirección horizontal actúa como una cámara esférica.

Box – Caja, no es más que 6 cámaras estándar colocados en cada uno de los lados de una caja. Este
tipo de cámara es excelente para la generación de mapas de entorno para el mapeo de un cubo. Puede
ser muy útil para GI también - se puede calcular el iradiance map con una cámara box, guardarlo en
un archivo y puede reutilizarlo con una cámara standard que puede apuntar en cualquier dirección.

Fish eye - este tipo especial de cámara capta la escena como si fuera una cámara estenopeica normal
apuntando a una esfera totalmente reflectante que refleja la escena en el obturador de la cámara.
Corresponde a un objetivo tipo gran angular. Puede utilizar la configuración Dist / FOV para controlar
qué parte de la esfera será capturada por la cámara. El arco rojo en el diagrama se corresponde con el
ángulo del campo visual. Tenga en cuenta que la esfera tiene siempre un radio de 1,0.

Warped spherical - otra cámara esférica con un aspecto un poco diferente.

Depth of field
Estos parámetros controlan la profundidad de campo cuando se representa con una cámara estándar
de 3ds Max o con una vista en perspectiva. Los parámetros no se tienen en cuenta si se hace el render
desde una VRayPhysicalCamera.

On - activa el efecto de profundidad de campo.

Aperture - este es el tamaño de la abertura de la cámara virtual, en las unidades reales de la escena.
Los pequeños tamaños de apertura reducen el efecto DOF, los tamaños más grandes producen el
efecto más borroso.

Manual de Vray 2.0 26

<!-- p. 28 -->

Center bias - determina la uniformidad del efecto DOF. Un valor de 0.0 significa que la luz pasa de
manera uniforme a través de la abertura. Los valores positivos significan que la luz se concentra hacia
el borde de la abertura, mientras que valores negativos concentrar la luz en el centro.

Focal Dist. - determina la distancia de la cámara en la que los objetos estarán en foco perfecto. Los
objetos que estén más cerca o más lejos que esta distancia se veran borrosos.

Get from camera - cuando esta opción está activada, la distancia focal se determina a partir del
target de la cámara.

Sides - esta opción le permite simular la forma poligonal del diafragma de las cámaras en el mundo
real. Cuando esta opción está desactivada, la forma se supone que es perfectamente circular.

Rotation - especifica la orientación de la forma del diafragma.

Anisotropy - esta opción permite el estiramiento del efecto bokeh en horizontal o en vertical. Los
valores positivos deforman en la dirección vertical. Los valores negativos deforman en la dirección
horizontal.

Subdivs - controla la calidad del efecto DOF. Los valores más bajos se calculan más rápido, pero
producen más ruido en la imagen. Los valores más altos suavizar el ruido, pero tardan más tiempo en
procesarse. Tenga en cuenta que la calidad del muestreo también depende de los ajustes en el DMC
Sampler , así como en los valores del image sampler .

Motion blur
On – activa el desenfoque de movimiento.

Duration - especifica la duración, en fotogramas, durante el cual el obturador de la cámara está
abierta.

Interval centre - específica el centro del intervalo de desenfoque de movimiento con respecto al
fotograma de 3ds Max. Un valor de 0.5 significa que la mitad del intervalo de desenfoque de
movimiento está a medio camino entre el fotograma que se renderiza y el fotograma siguiente. Un
valor de 0.0 significa que la mitad del intervalo coincide con el fotograma exacto.

Bias - este controla distorsion del efecto de desenfoque de movimiento. Un valor de 0.0 significa que
la luz pasa de manera uniforme durante el intervalo de desenfoque de movimiento completo. Los
valores positivos significan que la luz se concentra hacia el final del intervalo, mientras que valores
negativos concentrar la luz hacia el principio.

Parametros generales del motion blur
Estos parámetros se utilizan si se está usando una cámara estándar o una VRayPhysicalCamera con el
desenfoque de movimiento activado.

Prepass samples - Controla la cantidad de muestras en el tiempo que serán calculadas por el
iradiance map.

Blur particles as mesh - esta opción controla la renderizacion de los sistemas de partículas. Cuando
está activado, las partículas se volverán borrosa y serán tratadas como geometria. Sin embargo,
muchos sistemas de partículas cambiar el número de partículas entre los fotogramas. Puede desactivar
esta opción para calcular el desenfoque de movimiento de la velocidad de las partículas en su lugar.

Geometry samples - determina el número de segmentos de la geometría utilizada para calcular el
desenfoque de movimiento de las particulas. Se supone que los objetos se mueven de forma lineal
entre las
Subdivs - determina la calidad del desenfoque de movimiento. Los valores más bajos se calculan más
rápido, pero producen más ruido en la imagen. Los valores más altos suavizan el ruido, pero tardan

Manual de Vray 2.0 27

<!-- p. 29 -->

más tiempo en renderizarse. Tenga en cuenta que la calidad del muestreo también depende de los
ajustes en el DMC Sampler , así como en los valores del image sampler .

Notas

 Profundidad de campo sólo es compatible con el tipo de cámara estándar. Otros tipos de
cámara no producen el efecto de profundidad de campo en esta pestaña.

 Cuando DOF y desenfoque de movimiento están habilitados, se renderizan con el mayor de los
dos parámetros de Subdivs.

Manual de Vray 2.0 28

<!-- p. 30 -->

DEFAULT DISPLACEMENT

General

Esta sección le permite controlar el desplazamiento en los objetos con mapas de desplazamiento, que
no tienen un modificador VRayDisplacementMod aplicado.

Parámetros

Override Max - cuando esta opción
está activada, V-Ray renderiza los
materiales con mapa de
desplazamiento utilizando su propio
sistema de desplazamiento interno
con microtriangulos. Cuando esta
opción está desactivada, los objetos
se calculan con el estándar de
desplazamiento de 3ds Max.

Edge length - lo que determina la calidad de los desplazamientos. Cada triángulo de la malla original
se subdivide en una serie de sub-triángulos. Más sub-triángulos significa más detalle en los
desplazamientos, tiempos de render más lentos y más uso de la RAM. Menos sub-triángulos significa
menos detalles, una representación más rápida y menos RAM. La calidad del desplazamiento depende
de los siguientes parámetros que veremos a continuación.

View-dependent - cuando está activado, el edge lenght se calcula en función de aquello que se ve
desde la cámara. Cuando está apagado, se calcula para toda la escena, aunque el objeto no se vea o
este lejos de la cámara.

Max. subdivs - Controla la cantidad de sub-triángulos máxima generada a partir de cualquier
triángulo de la malla original. El valor es en realidad la raíz cuadrada del número máximo de subtriángulos. Por ejemplo, un valor de 256 significa que en la mayoría de los polígonos de la maya
original se generaran 256 x 256 = 65.536 sub-triángulos. No es una buena idea mantener este valor
muy alto. Si es necesario utilizar los valores más altos, será mejor subdividir la malla original en
triángulos más pequeños en su lugar.

Tight bounds - cuando está activado, V-Ray intentará calcular el volumen exacto que delimita los
triángulos desplazados de la malla original. Para ello es necesario un pre-muestreo de la textura de
desplazamiento, pero el render será más rápido, si la textura tiene grandes áreas de color negro o
blanco. Sin embargo, si la textura de desplazamiento varía mucho entre el negro y el blanco total, si
puede ser más rápido desactivar esta opción. Cuando está apagado, V-Ray no pre-sampleará la
textura.

Amount - éste es un parámetro por defecto de escala para el desplazamiento. Los valores mayores
que 1,0 aumentan la cantidad de desplazamiento, mientras que los valores inferiores a 1,0 lo reducen.

Relative to Bbox - si este parámetro está activado, la cantidad de desplazamiento actual se basa en
el recuadro que delimita los objetos, digamos que la cantidad es relativa al tamaño del objeto. Si esta
opción está desactivada, el desplazamiento se expresa en unidades genéricas de la escena, donde las
áreas blancas en el mapa de desplazamiento corresponden al desplazamiento de una unidad genérica.
Usted puede utilizar el parámetro de cantidad para aumentar o disminuir la cantidad de

Manual de Vray 2.0 29

<!-- p. 31 -->

desplazamiento, si la escena esta en centímetros y el Amount es de 1, significaría que las zonas
blancas del mapa de desplazamiento subirían 1 cm.

Notas

 La cantidad de desplazamiento por defecto se basa en el recuadro de delimitación de un objeto.
Por lo tanto, no es una buena opción cuando se tiene modificadores de deformación de objetos.
En ese caso, puede desactivar la opción relativa a Bbox, o se puede aplicar un modificador
VRayDisplacementMod, que aplica la cantidad de desplazamiento constante.

Manual de Vray 2.0 30

<!-- p. 32 -->

SYSTEM

General

En esta sección se puede adaptar una serie de parámetros relacionados con el funcionamiento global
del renderizador.

Parámetros

Dynamic memory limit - el límite de memoria RAM total del raycaster dinámico que almacena la
geometría dinámica así como el desplazamiento, los objetos VRayProxy, VRayFur, etc,. Por lo tanto, si
la geometría tiene que ser descargada y cargada con demasiada frecuencia, los hilos que esperar a los
demás y el rendimiento de la representación se verá afectada. En V-Ray 2.0 y posteriores, se puede
establecer a 0 para eliminar cualquier límite en ese caso, V-Ray consumirá tanta memoria como sea
necesario.

Render región division
Aquí puede controlar diversos parámetros de las regiones del render de V-Ray (buckets). El bucket es
una parte esencial del sistema de renderizado distribuido de V-Ray. Un bucket es una parte rectangular
de la imagen renderizada, que se representa de forma independiente con otros buckets. Estos buckets
se pueden enviar a otras máquinas de la LAN para el procesamiento y / o se pueden distribuir entre
varias CPUs. Debido a que un bucket solo puede ser procesado por un único procesador y la división de
la estructura en un número demasiado pequeño de buckets puede evitar la utilización óptima de los
recursos computacionales (algunas CPU permanecer paradas todo el tiempo). Sin embargo, dividir el
render en muchos buckets pueden retrasar el render debido a que hay una sobrecarga de tiempo de

Manual de Vray 2.0 31

<!-- p. 33 -->

algunos de ellos relacionados con cada balde (cubo de configuración, transferencia inalámbrica a
internet, etc).
X - determina la anchura máxima de la región en píxeles (Región W / H está seleccionado) o el número
de regiones en la dirección horizontal (cuando Conde región se ha seleccionado)
Y - determina la altura máxima de la región en píxeles (Región W / H está seleccionado) o el número
de regiones en la dirección vertical (cuando Conde región se ha seleccionado)
Secuencia de la región - que determina el orden en que las regiones son prestados. Tenga en cuenta
que la secuencia de triangulación por defecto que es mejor si se utiliza un lof de geometría dinámica
(desplazamiento de mapa de los objetos, VRayProxy o VRayFur objetos), ya que camina a través de la
imagen de una manera muy consistente, de manera que la geometría que se ha generado para los
cubos anteriores se pueden utilizados para los cucharones del siguiente. Las secuencias de otros
tienden a saltar de un extremo de la imagen a otro que no es bueno con la geometría dinámica.
Secuencia inversa - invierte el orden de secuencia de la región.

Anterior hacer - este parámetro determina qué se debe hacer con la imagen anterior en el buffer
virtual cuando se inicia la prestación. Tenga en cuenta que este parámetro no tiene efecto en el
resultado final de la prestación, sino que se lleva a cabo simplemente como una forma práctica de
distinguir entre las partes desde el marco actual que se queden, y la parte sobrante de la prestación
anterior. Los valores posibles son:
Sin cambios - no se harán cambios - el buffer virtual sigue siendo la misma;

Cruz - cada segundo píxel de la imagen se establece en negro;

Campos - cada línea de la imagen se establece en negro;

Oscurecer - los colores de la imagen se oscurecerán.

Azul - la imagen anterior se tiñe de azul.

Distributed rendering
El renderizado distribuido es el proceso de cálculo de una sola imagen en varias máquinas diferentes.
Tenga en cuenta que esto es diferente de la distribución de la estructura sobre varios hilos en la CPU
en una sola máquina, que se llama multithreading. V-Ray soporta multithreading, así como renderizado
distribuido.
Antes de poder utilizar la opción de renderizado distribuido, debe determinar los equipos que tomarán
parte en los cálculos. Ambos 3ds Max y V-Ray deben ser adecuadamente instalados en las máquinas,
aunque no es necesario que tengan licencia. Usted debe asegurarse de que la aplicación de V-Ray
spawner se está ejecutando en las máquinas - ya sea como un servicio, o como una aplicación
independiente.

Distributed rendering esta casilla especifica si V-Ray utilizará el renderizado distribuido.

Settings... - este botón se abre el cuadro de dialogo del V-Ray Distributed rendering.

Frame stamp
Esta es una manera de poner un texto breve sobre las imágenes renderizadas. Puede ser útil en
muchos aspectos - por ejemplo, en el render en red, para determinar rápidamente qué cuadros fueron
renderizados por tal o cual máquina. El frame stamp es una línea de texto, que aparece en la parte
inferior de la imagen.
Casilla de verificación – Enciende o apaga el frame stamp.
Cuadro de edición - Aquí se escribe el texto que desea que aparezca en las imágenes. También
puede utilizar algunas palabras especiales, todas las que comienzan con el símbolo de porcentaje (%).
Las palabras clave V-Ray las sustituirá por el valor correspondiente:
Palabra clave Significado

Manual de Vray 2.0 32

<!-- p. 34 -->

%vrayversion la versión actual de V-Ray

%filename el nombre del archivo de la escena actual

%frame el número de la imagen actual

el número de primitivas intersectables únicas generadas para el
%primitives
fotograma actual

%rendertime el tiempo de render para el fotograma actual

%computername el nombre de red del equipo

%date la fecha actual del sistema

%time la hora actual del sistema

%w el ancho de la imagen en píxeles

%h la altura de la imagen en píxeles

el nombre de la cámara de este fotograma (si la representación
%camera
corresponde a la de una cámara, permanecera vacía de lo contrario)

el valor de cualquier parámetro de V-Ray, por su nombre MaxScript .
%"\<maxscript parameter Tenga en cuenta que debe incluir el nombre del parámetro entre
name>" comillas ("). Tenga en cuenta también que esta opción sólo funciona
cuando se representa en el búfer de 3ds Max.

%ram la cantidad de memoria física (en KBytes) instalado en el sistema

%vmem la cantidad de memoria virtual (en KBytes) disponibles en el sistema

%mhz la velocidad de reloj de la CPU del sistema (s)

%os el sistema operativo

Font - este botón le permite elegir una fuente y los atributos de fuente para el texto en el marco de
sello.
Full witch - cuando se selecciona esta opción, el frame stamp llenará todo el ancho de la imagen, de
lo contrario el frame stamp será tan ancho como el texto.
Justify - especifica la posición del frame stamp:
Left - el frame stamp se coloca a la izquierda de la imagen.
Center - el frame stamp está centrado.
Right - el frame stamp se coloca en la parte derecha de la imagen.

Objects settings / Lights settings
Estos botones abren los cuadros de diálogo para el object settings y para el lights settings .

Manual de Vray 2.0 33

<!-- p. 35 -->

Presets
Este botón abre el diálogo de presets .

V-Ray log
Estos parámetros controlan la ventana de mensajes
de V-Ray. Durante la representación, V-Ray escribe
varios tipos de información en el archivo C: \
VRayLog.txt. La ventana de mensajes muestra parte
de esa información para que pueda verlo sin tener
que abrir manualmente el archivo.
Cada mensaje puede ser de una de las cuatro
categorías, que son coloreados de una manera
diferente en la ventana de mensajes. Esas categorías
son errores (en color rojo), advertencias (color
verde), los mensajes informativos (en color
blanco) y los mensajes de depuración (en color
negro).

Show window - cuando está activada, V-Ray
mostrará la ventana de mensajes al inicio de cada representación.
Level - esto determina qué tipo de mensajes serán mostrados en la ventana:
1 - sólo los mensajes de error
2 - mensajes de error y advertencias
3 - errores, advertencias y mensajes informativos
4 - todos los mensajes
Log file - este parámetro determina la ubicación y el nombre del archivo de registro. El archivo de
registro predeterminado es C: \ VRayLog.txt

Otros parámetros
MAX-compatible ShadeContext - V-Ray hace todos los cálculos en un espacio mundial (toda la
escena). Sin embargo, algunos plugins 3ds Max (sobre todo atmosféricos) procesan la escena en un
espacio desde cámara, porque esto es lo que el renderizador por defecto scanline hace. Para mantener
la compatibilidad con plugins, V-Ray emula el trabajo en espacio de cámara mediante la conversión de
los diferentes puntos y vectores al trabajar con otros plugins. Además de la desaceleración de V-Ray al
estar obligado a convertir los valores de toda la escena en cada render, y trabajando con modificadores
de la cámara. Es por esto que usted tiene la opción de desactivar la emulación de espacio de cámara.

Check for missing files - cuando está activada, V-Ray trata de encontrar los archivos que faltan en la
escena y abre una lista si falta algún archivo. Los archivos que faltan también se guardaran en el
archivo C: \ VRayLog.txt. Si esta opción está activada, y hacer la escena con la representación
distribuida, y si los servidores hacen detecta los archivos que faltan, que se niegan a hacer la escena.
Optimized atmospheric evaluation - normalmente en 3ds Max, los efectos atmosféricos son
calculados después del render. Al activar esta opción hará que V-Ray calcule primero los efectos
atmosféricos, y la sombra de la superficie detrás de ellos sólo si los atmosféricos son lo
suficientemente transparentes.
Low thread priority - activando esto bajará la prioridad de los procesos de render de V-Ray,
haciendo que el sistema operativo reserve recursos para otras aplicaciones y no los invierta todos en
V-Ray.

Manual de Vray 2.0 34

<!-- p. 36 -->

MATERIALES

VRayMtl

General

Un material especial - el VRayMtl – es el que se recomienda usar con V-Ray. Esto permite una mejor
iluminación físicamente correcta y una mejor distribución de luz en la escena, una representación más
rápida, la reflexión es más correcta así como los calculos de refracción. Dentro del VRayMtl puede
aplicar diferentes mapas de textura, controlar los reflejos y las refracciones, añadir mapas de relieve y
de desplazamiento, la fuerza de los cálculos directos de la GI, y elegir el BRDF del material.

Parámetros

Basic parameters

Diffuse
Difusa - este es el color difuso del material. Tenga en
cuenta que el color difuso real de la superficie
depende también de la reflexión y la refracción de los
colores.
Roughness - este parámetro puede ser utilizado
para simular superficies rugosas o superficies
cubiertas de polvo (por ejemplo, la piel o la superficie
de la Luna).

Reflection
Reflexión - color de la reflexión.

Fresnel reflections - marcando esta opción hace
que la fuerza de reflexión varie con el ángulo de
visión de la superficie. Algunos de los materiales en
la naturaleza (vidrio, etc) reflejan la luz de esta
manera. Tenga en cuenta que el efecto Fresnel
también depende del índice de refracción.

Fresnel IOR - el IOR a utilizar en el cálculo de las
reflexiones de Fresnel. Normalmente, esta se bloquea
en el parámetro de refracción IOR, pero se puede
desbloquear un control más preciso.

Hilight glossiness - lo que determina la forma del
brillo en el material. Normalmente este parámetro se
bloquea en el valor Refl. glossiness con el fin de
producir resultados con precisión física.

Refl. glossiness - Controla la nitidez de los reflejos.
Un valor de 1.0 significa una reflexión perfecta como

Manual de Vray 2.0 35

<!-- p. 37 -->

un espejo, los más bajos producen reflejos borrosos o brillantes. Utilice el parámetro Subdivs abajo
para controlar la calidad de reflexiones brillantes.

Subdivs - controla la calidad del glossiness. Los valores más bajos se renderizan más rápido, pero el
resultado tendrá más ruido. Los valores más altos tardan más tiempo, pero que producen resultados
más suaves.
Use interpolation - V-Ray puede utilizar un sistema de cálculo similar al irradiance map en el
renderizado de reflexiones glossy. Marque esta opción para activar este tipo de cálculo. Vea la
interpolación de reflexión para obtener más detalles.
Dim distance - específica la distancia después de la cual los rayos de reflexión no se trazarán
Dim fall off - una radio de atenuación para la dim distance.
Max depth - el número de veces que un rayo puede reflejarse. Escenas con una gran cantidad de
superficies reflectantes y de refracción pueden requerir valores más altos para parecer reales.
Exit color - si un rayo ha alcanzado su máxima profundidad de reflexión, este será el color que
devolverá el material.

Refraction
Refract - color refracción. Tenga en cuenta que el color de refracción real depende del color de
reflexión también.
IOR - índice de refracción del material, que describe la forma en que la luz se curva al atravesar la
superficie del material. Un valor de 1.0 significa que la luz no va a cambiar de dirección.
Glossiness - Controla la nitidez de las refracciones. Un valor de 1.0 significa perfecta como el cristal,
los más bajos producen refracciones borrosas o glossy. Utilice el parámetro Subdivs abajo para
controlar la calidad de las refracciones glossy.
Subdivs - controla la calidad de las refracciones glossy. Los valores más bajos se renderizan más
rápido, pero el resultado tendrá más ruido. Los valores más altos tardan más tiempo, pero producen
resultados más suaves. Este parámetro también controla la calidad del efecto translúcido.
Use interpolation - V-Ray puede utilizar un sistema de cálculo similar al irradiance map en el
renderizado de refracciones glossy y translúcidas. Marque esta opción para activar este tipo de cálculo.
Vea la interpolación de refracción para obtener más detalles.
Max depth - el número de veces que un rayo puede ser refractado. Escenas con una gran cantidad de
superficies de refracción y de reflexión pueden requerir valores más altos para parecer reales
Exit color - si está activado, cuando un rayo ha alcanzado la profundidad máxima de refracción, el
rayo devolverá el color de salida. Cuando está desactivado, el rayo no se refracta, pero se mantendrá
sin cambios.
Fog color – determina la atenuación de la luz cuando pasa a través del material. Esta opción permite
simular el hecho de que objetos gruesos parecen menos transparentes que los objetos finos. Tenga en
cuenta que el efecto del color de la niebla depende del tamaño absoluto de los objetos y por lo tanto
dependientes de la escala de la escena. El color de la niebla también determina el aspecto del objeto
cuando se utiliza transparencia.
Fog multiplier - la fuerza del efecto de niebla. Los valores más bajos reducen el efecto de la niebla,
por lo que el material será más transparente. Los valores más altos aumentan el efecto de niebla, lo
que hace el material más opaco.
Fog bias - Este parámetro permite cambiar la forma en que se aplicó el color de la niebla, mediante el
ajuste de este parámetro puede hacer que las partes delgadas del objeto aparezcan más transparentes
de lo normal, o menos transparentes de lo normal.
Affect shadows - esto hará que el material proyecte sombras transparentes, dependiendo del color
de la refracción y el color del fog. Esto sólo funciona con luces y sombras V-Ray.
Affect chanels - Permite especifícar qué canales van a ver afectadas por la transparencia del material
\-Color Only – La transparencia sólo afectará a los canales RGB del render final

\- Color + alfa - esto hará que el material transmita la refracción al canal alfa de los objetos que
refractan, en lugar de mostrar un alfa opaco. Tenga en cuenta que en la actualidad esto sólo funciona
con refracciones claras (sin glossyness).

\- All channels - todos los canales y elementos de render se verán afectados por la transparencia del
material

Manual de Vray 2.0 36

<!-- p. 38 -->

Dispersion - esta opción permite el cálculo de la dispersión de la luz con la verdadera longitud de
onda
Abbe - esta opción le permite aumentar o disminuir el efecto de dispersión. Valores bajos amplía la
dispersión y viceversa.

Translucency
Type - selecciona el algoritmo para calcular la translucidez (también llamada sub-surface
scattering). Tenga en cuenta que la refracción debe estar habilitada para que este efecto sea visible.
En la actualidad sólo es compatible la dispersión de un solo rebote. Los valores posibles son:
None - No se calcula para el material;

Hard (wax) model - Este modelo es especialmente adecuado para materiales duros como el mármol;

Soft (water) model - este modelo está recomendado para compatibilidad con las versiones de V-Ray
(1.09.x);

Hybrid model - este es el modelo más realista de SSS (sub-surface scattering ) y es adecuado
para simular la piel, leche, zumos de frutas y otros materiales translúcidos.
Back-side color - normalmente el color del efecto de SSS depende del color del fog, este parámetro
le permite, además, tintar el SSS.
Thickness –Grosor, lo que limita los rayos que se trazará por debajo de la superficie. Esto es útil si
usted no quiere o no necesita rastrear toda la sub-superficie de volumen.
Light multiplier - un multiplicador para el efecto translúcido.
Scatter coefficient - la cantidad de dispersión dentro del objeto, 0.0 significa que los rayos medios
se dispersan en todas direcciones;. 1,0 significa que un rayo no puede cambiar su dirección en el
interior del volumen, bajo la superficie.
Forward/backward coefficient - controla la dirección de la dispersión de los rayos, 0.0 significa que
un rayo no puede ir hacia dentro (lejos de la superficie, dentro del objeto); 0,5 significa que un rayo
tiene la misma posibilidad de ir hacia adelante que hacia atrás; 1,0 significa. Que un rayo se dispersa
hacia fuera (hacia la superficie, hacia el exterior del
objeto).

BRDF
Los parámetros BRDF determinan de qué manera
reaccionarán las reflexiones y los brillos en el
material. Son los tipos de shaders (sombreadores)
de V-Ray.
Tipo - esto determina el tipo de BRDF
Phong - Phong seleccionado / reflexiones

Blinn - Blinn seleccionado / reflexiones

Ward - ward seleccionado / reflexiones

Soften- este parámetro permite al usuario suavizar la transición desde la oscuridad a las áreas
brillantes en los reflejos especulares.
Fix dark glossy edges - esta opción permite eliminar los bordes oscuros que a veces aparecen en los
objetos con materiales brillantes.
Anisotropy - determina la forma del hilight. Un valor de 0.0 significa Hilights isotrópicos. Valores
negativos y positivos simular el "cepillado" de la superficie.
Rotation - determina la orientación del efecto anisotrópico en grados (rotación en grados). Diferentes
superficies de cepillado se pueden simular mediante el uso de un mapa de textura para el parámetro
de rotación de la anisotropía.
Local axis - controla la dirección para el efecto anisotrópico se elige:
X,Y,Z- la dirección se basa en el eje del objeto seleccionado.

Map channel - la dirección se basa en el canal de mapa seleccionado.

Manual de Vray 2.0 37

<!-- p. 39 -->

Mapas
Estos determinan los distintos mapas de texturas utilizados por el material.

Notas

 Utilice el VRayMtl siempre que sea posible en sus escenas. Este material está especialmente
optimizado para V-Ray y, a menudo la GI y la iluminación se calcula mucho más rápido por V-
Ray que con el material standard de 3ds Max. Muchos Ray V-características (por ejemplo, la
caché de luz , mapeo de fotones , elementos de render ) se garantiza que funcione
correctamente sólo con materiales que cumplen VRayMtl y otros V-Ray.

 VRayMtl pueden producir reflexiones / refracciones de los objetos mate - ver VRayMtlWrapper .

Manual de Vray 2.0 38

<!-- p. 40 -->

VRAYLIGHT

General

El VRayLight es un plugin específico que genera una fuente de luz que se
puede utilizar para crear luces de área físicamente precisas.

Parámetros

General
On - Activa la VRayLight
Exclude - permite excluir objetos de ser iluminados o de producir sombras
por la luz.
Type - especifica la forma de la luz:

Plane - la VRayLight tiene la forma de un rectángulo plano.

Sphere - la VRayLight tiene la forma de una esfera.

Dome - la VRayLight ilumina con una luz ambiental. La luz proviene de una
cúpula semi-esférica por encima del eje z y que despide luz hacia el centro
de la escena desde todas las direcciones.

Mesh - permite el uso de una malla u objeto poligonal como forma del
emisor de la luz. Si la luz está cerca de otras superficies de la escena, lo
mejor es utilizar este modo con GI habilitado. Esto permitirá que V-Ray use
el muestreo de la luz directa y de la GI para obtener mejores resultados. En
la actualidad hay algunas restricciones en el uso de luces de malla, más
información en a la sección de Notas.

Intensity
Units: - permite elegir las unidades de potencia de la luz. Utilizar las
unidades correctas es esencial cuando se trabaja con la VRayPhysicalCamera
. La luz tomará la escala de la escena en consideración y usará las unidades
para obtener el resultado correcto en la escala que se está trabajando. Los
valores posibles son:

Default (image) - el color y el multiplicador directamente determinan el
color de la luz visible sin ningún tipo de conversión. La superficie de la luz
aparecerá con el color dado en la imagen final cuando se vea directamente
en la cámara (suponiendo que no hay asignación de colores).

Luminous power (lm) – la potencia total emitida por la luz visible medida
en lúmenes. Cuando se utiliza este valor, la intensidad de la luz no depende
de su tamaño. Una típica bombilla de 100W emite alrededor de 1.500
lúmenes de luz.

Luminance (lm / m ^ 2/sr) – la potencia de la luz sobre una superficie
medida en lúmenes por metro cuadrado por estereorradián. Cuando se
utiliza este valor, la intensidad de la luz depende de su tamaño.
Radiant power (W) - potencia total emitida por la luz visible medida en
vatios. Cuando se utiliza esta configuración, la intensidad de la luz no
depende de su tamaño. Tenga en cuenta que esto no es lo mismo que la

Manual de Vray 2.0 39

<!-- p. 41 -->

energía eléctrica consumida por una bombilla, por ejemplo. Una bombilla típica de luz de 100 W sólo
emite entre 2 y 3 vatios de luz visible.

Radiance (W / m² / sr) – la potencia visible de la superficie de la luz medida en vatios por metro
cuadrado por estereorradián. Cuando se utiliza este valor, la intensidad de la luz depende de su
tamaño.

Multiplier - multiplicador para el color de la luz, ésta es también la intensidad de la luz en las
unidades seleccionadas por el parámetro de Intensity units.

Mode - le permite seleccionar el modo en el que se determina el color de la luz:
Color - el color de la luz está directamente determinado por el parámetro color.

Temperature - la temperatura de color de la luz (en grados Kelvin) es especificado por el parámetro
de temperature.

Size
Half-length - la mitad de la longitud de la fuente de luz, medida en unidades de escena. Si la fuente
de esfera de luz se selecciona este valor corresponde al radio de la esfera. Este parámetro es ignorado
por las luces Dome.
Half-width - la mitad de la anchura de la fuente de luz, medida en unidades de la escena. Este campo
no tiene efecto cuando la fuente es de tipo Sphere o Dome.
W size - actualmente este parámetro no hace nada. Esta reservado para (un día) el VRayLight apoya
en forma de caja fuentes de luz.

Options
Cast shadows - cuando está encendido (por defecto), la luz proyecta sombras. Desactive esta opción
para desactivar la proyección de sombras de la luz.
Double-sided - cuando la luz es una fuente de luz plana esta opción controla si la luz es emitida
desde ambos lados del emisor. Este campo no tiene efecto sobre las fuentes de luz sphere o dome.
Invisible - este ajuste controla si la forma de la fuente VRayLight es visible en el resultado de render.
Cuando esta opción está desactivada la fuente se representa en el color de la luz actual. De lo
contrario no es visible en la escena. Tenga en cuenta que esta opción sólo afecta a la visibilidad de la
luz cuando se ve directamente a la cámara no a través de refracciones. La visibilidad de la luz con
respecto a las reflexiones está controlada por la opción Afectar especular.
Ignore light normals - normalmente, la superficie de la fuente emite luz en todas direcciones.
Cuando esta opción está desactivada, se emite más luz en la dirección de la normal de la superficie de
la fuente.
No decay - normalmente la intensidad de la luz es inversamente proporcional al cuadrado de la
distancia de la luz (las superficies que están más lejos de la luz son más oscuras que las superficies
que están más cerca de la luz). Cuando esta opción está activada la intensidad no decae con la
distancia.
Skylight portal - cuando esta opción está activada, el color y los parámetros del multiplicador se
ignoran, y la luz tomara los valores de intensidad y color del ambiente en el parámetro “environment”.
Portal simple - esta opción sólo está disponible si la opción está en modo “skylight portal”. La
VRayLight cuenta con que no hay nada de interés detrás de la luz en sí misma, por lo que el color del
medio ambiente puede ser utilizado directamente. Normalmente, el skylight portal toma su color de
cualquier objeto que está detrás de ella. Al activar esta opción hace que el renderizado de las luces del
skylight portal sea más rápido.
Store with irradiance map - cuando esta opción está activada y el cálculo de GI se ajusta en modo
irradiance map V-Ray calculará los efectos de la VRayLight y los almacenará en el irradiance map. El
resultado es que el irradiance map se calcula más lentamente, pero el render tarda menos tiempo.
También puede guardar el irradiance map y volverlo a usar más tarde.
Affect difuse - esto determina si la luz está afectando a las propiedades de difusa de los materiales.
Affect specular - esto determina si la luz está afectando al canal especular de los materiales.
Affect reflexion - esto determina si la luz aparecerá en las reflexiones de los materiales.

Manual de Vray 2.0 40

<!-- p. 42 -->

Sampling
Subdivs - este valor controla el número de muestras que V-Ray toma para calcular la iluminación. Los
valores más bajos consiguen resultados con más ruido, pero se hacen más rápido. Los valores más
altos producen resultados más suaves, pero llevarán más tiempo. Tenga en cuenta que el número real
de muestras también depende de la configuración del DMC Sampler .
Shadow bias - sesgo que mueve la sombra hacia o desde el objeto de sombras (u objetos). Si el valor
de bias es demasiado bajo, las sombras pueden "filtrarse" a través de lugares que no deberían,
produciendo patrones de moiré o lo que fuera en los lugares y áreas oscuras de las mallas. Si el bias es
demasiado alto, las sombras pueden "separarse" de un objeto. Si el valor de bias es demasiado
extremo en cualquier dirección, las sombras pueden no ser representadas.
Cutoff - este parámetro especifica un umbral para la intensidad de la luz, por debajo del cual la luz no
se calculará. Esto puede ser útil en escenas con muchas luces, en la que se desea limitar el efecto de
las luces a cierta distancia a su alrededor. Los valores más altos acortar más la luz, los valores más
bajos hacen que el umbral sea mayor. Si se especifica 0.0, la luz se calcula para todas las superficies.

Texture
Use texture - cuando el tipo de luz es Plane, Dome o mesh se utiliza esta opcion, esto aplica una
textura en la superficie de la luz. Si hay superficies que están cerca de la luz con mapa de textura, lo
mejor es tener GI habilitado. Esto permite que V-Ray use la combinación de muestreo directo e
indirecto a la luz, lo que reduce el ruido de las superficies cerca de la luz.
Texture - específica el uso de la textura. La intensidad de la textura también se ve afectada por el
multiplicador de la luz.
Resolution - especifica la resolución en la que se vuelve a muestrear la textura para que ilumine con
esa textura.
Adaptiveness - controla la cantidad mediante la que se ajusta el brillo de la luz a la toma de muestras
de la textura. Si es 0.0, no hay adaptación basada en la intensidad de la textura. Cuando se establece
en 1,0 (por defecto), se aplica la cantidad máxima de adaptación. El cambio de este parámetro puede
ser necesario si hay partes muy brillantes en la imagen, que sin embargo oscurece la escena en
particular. Esto evitará que la luz concentre una gran cantidad de muestras en esta área y por
consiguiente muy pocas muestras en otras partes de la textura. Este parámetro se omite si el tipo de
luz es mesh.

Dome light options
Spherical (full dome) - Cuando está activada, esta opción hace que la luz dome cubra toda la esfera
alrededor de la escena. Cuando está apagado (por defecto), la luz cubre solo un hemisferio.
Dist Ray - le permite especificar la distancia máxima a la que los rayos de sombra van a ser
rastreados.
From GI settings - el valor de Ray Dist está determinado por el parámetro Ray Dist en la
configuración de GI
Explicit - el valor Ray Dist se determina por el parámetro de Distance
Target radius – desde la luz dome, se define una esfera alrededor del icono de la luz hasta donde los
fotones serán disparados cuando se usen mapa de fotones.
Emit radius - desde la luz dome, se define una esfera alrededor del icono de la luz a partir de la cual
los fotones serán disparados hacia la zona central con un radio de emisión.

Mesh light options

Pick mesh - haga clic en el botón para seleccionar un objeto malla de la
escena como la forma de la luz. Si no se especifica ninguna malla, la luz
asume una forma de caja.
Flip normals - si está activada, las normales de la fuente de la malla serán
invertidas lo que produce que la luz se emita en el lado opuesto.

Manual de Vray 2.0 41

<!-- p. 43 -->

Replace mesh with light - si esta opción está activada en el momento de seleccionar la malla esta
será eliminada y la luz de malla de V-Ray se creará en su lugar reemplazando el objeto malla.

Extract mesh as node - utilice este botón para restaurar a objeto malla cuando ha creado una luz
tipo mesh sustituyendo la geometría real de la luz, se puede obtener la geometría original de nuevo
haciendo clic en este botón

Notas

 Cuando usee luces mesh o luces con un mapa de textura, lo mejor es tener la GI habilitada.
Esto permite que V-Ray use el modo combinado de muestreo directo e indirecto de la luz, lo
que reduce el ruido de las superficies cerca de la luz.

 En la actualidad las luces mesh no funcionan correctamente si el objeto de origen de malla tiene
aplicado desenfoque de movimiento. Esto se solucionará en una versión futura. El desenfoque
de movimiento funciona correctamente para los otros tipos de luz (plane y sphere).

Manual de Vray 2.0 42

<!-- p. 44 -->

VRAYSUN Y VRAYSKY

General

El VRaySun y VRaySky son herramientas especiales que son proporcionadas por el renderizador V-Ray.
Desarrollados para trabajar en conjunto, el VRaySun y VRaySky reproducen el Sol de la vida real y el
medio ambiente del cielo en la Tierra. Ambos están programados para que cambien su apariencia
dependiendo de la dirección de la VRaySun.
El Sol de V-Ray y el cielo se basan en modelos físicos reales.

VRaySun parámetros

El VRaySun se encuentra en el menú (Create / Lights / VRay ). También se
puede especificar el VRaySun como el tipo de sol dentro de un sistema
Daylight de 3ds Max.
Enabled - enciende y apaga la luz del sol.
Invisible - Cuando está activada, esta opción hace invisible el sol, tanto a
la cámara como a las reflexiones. Esto es útil para evitar manchas brillantes
en las superficies brillantes.
Affect diffuse -, determina si el VRaySun está afectando a las propiedades
de difusión de los materiales.
Affect specular - esto determina si el VRaySun está afectando a los brillos
especulares de los materiales.
Cast atmospherics shadows - Cuando se activa las sombras de los
efectos atmosféricos en la escena.
Turbidity- Este parámetro determina la cantidad de polvo en el aire y
afecta al color del sol y del cielo. Los valores más bajos producen un cielo
claro y azul, mientras que los grandes valores hacen que sean de color
amarillo y naranja, por ejemplo, en una gran ciudad.
Ozone - este parámetro afecta el color de la luz solar. Disponible en el
rango de entre 0,0 y 1,0. Los valores más pequeños hacen que la luz del
sol sea más amarilla, valores mayores la tintan de azul.
Intensity multiplier - se trata de un multiplicador de la intensidad de la
VRaySun. Ya que el sol es muy brillante por defecto, puede utilizar este
parámetro para reducir su efecto.
Size multiplier - este parámetro controla el tamaño visible del sol. Esto afecta a la apariencia del
disco solar visto por la cámara y las reflexiones, así como a la nitidez de las sombras.
Shadow subdivs - Controla el número de muestras para el área de la sombra del sol. Más subdivs
producir sombras zona con mejor calidad, pero hacen el render más lento.
Shadow bias - desplaza la sombra hacia o desde el objeto (u objetos) que la produce. Si el valor de
bias es demasiado bajo, las sombras pueden "filtrarse" a través de lugares que no deberían, producen
patrones de moiré o defectos de render en las áreas oscuras de las mallas. Si el bias es demasiado
alto, las sombras pueden "separarse" de un objeto. Si el valor de bias es demasiado extremo en
cualquier dirección, las sombras pueden no ser renderizadas en ningún caso.
Photon emit radius - determina el radio de la zona, donde los fotones serían disparados. Esta zona
está representada por el cilindro de color verde alrededor de vector de los rayos del sol. Este

Manual de Vray 2.0 43

<!-- p. 45 -->

parámetro tiene efecto cuando los fotones se utilizan en las soluciones de GI o cáusticos.

Sky model - Le permite especificar el modelo que se utilizará para generar la textura VRaySky.
\- Preetham et al. - Cuando se selecciona este modo la textura de VRaySky se genera en base al
metodo Preetham et al.

\- CIE clear - cuando se selecciona este modo la textura de VRaySky se genera en función del método
de CIE para el cielo despejado.

\- CIE overcast - cuando se selecciona este modo la textura de VRaySky se genera en función del
método de CIE para el cielo nublado
Indirect horiz ilum -. Especifica la intensidad (en lux) de la iluminación en las superficies horizontales
que viene del cielo
Exclude - este botón le permite excluir objetos de la iluminación / sombra proyectada por la luz solar.

VRaySky parámetros

El mapa de textura VRaySky se suele utilizar como
un mapa de entorno, ya sea en el diálogo de
environment de 3dsmax, o en una de las ranuras
del environment de V-Ray y se comporta muy
parecido a un mapa de entorno HDRI. El VRaySky
cambia de aspecto según la posición de la
VRaySun.
Manual sun node – activa los parámetros del
VRaySky:
Off - el VRaySky tomará automáticamente los
parámetros de la VRaySun habilitada en la escena.
En este caso, ninguno de los otros parámetros de
VRaySky son accesibles.
On - usted puede elegir una fuente de luz
diferente. Se recomienda que elija sólo las luces
directas, como el vector de la dirección se toma en cuenta al calcular el aspecto del cielo. En este caso,
el VRaySun ya no tiene el control de la VRaySky y los parámetros en el despliegue del mapa de textura
determinan el aspecto final del cielo.
Sun node - especifica que la fuente de luz que elige acturará como Sol.
Sun turbidity – igual que los parámetros VRaySun
Sun ozone - igual que los parámetros VRaySun
Sun intensity multiplier - igual que los parámetros VRaySun
Sun size multiplier - igual que los parámetros VRaySun
Sun invisible - cuando esta opción está activada, el disco del sol no será visible en la textura del
cielo.

Sky model - Le permite especificar el modelo de procedimiento que se utilizará para generar la textura
VRaySky. - igual que los parámetros VRaySun

Manual de Vray 2.0 44

<!-- p. 46 -->

Notas

 Por defecto, el VRaySun y VRaySky son muy brillantes. En el mundo real, la radiación solar
promedio es de 1000 W por metro cuadrado. Por defecto en V-Ray están en esos valores, la
equivalencia con una luz standard de max sin decaimiento es de entre 200 y 300 veces
superior. Esto es absolutamente correcto desde el punto de vista físico, pero no es excesivo
para tener una imagen agradable. Para solucionar esto puede utilizar el color mapping para
ajustar estos valores en un rango más pequeño (que es la manera ideal) o puede usar el
multiplicador de la intensidad del sol para que el sol y el cielo tengan menos brillo. Pero lo que
produce resultados más reales es usar la VRayPhysicalCamera con los valores adecuados para
así no tener la necesidad de cambiar el sol y los parámetros de cielo.

Manual de Vray 2.0 45

<!-- p. 47 -->

VRAYPHYSICALCAMERA

General

El VRayPhysicalCamera le permite utilizar en la escena los parámetros del mundo real para configurar
la cámara virtual (por ejemplo, f-stop, distancia focal del objetivo, etc).
También hace que sea más fácil de usar fuentes de luz con iluminación real
(por ejemplo, VRayLight con unidades físicas, o VRaySun y VRaySky ).

Parámetros

Basic parameters
Type - determina el tipo de cámara. Esta opcion tiene un efecto sobre el
efecto de desenfoque de movimiento producido por la cámara:
Still cam - simula una cámara de fotos con una velocidad de obturación
normal.

Movie cam - simula una cámara de cine con un obturador circular.

Video cam - simula una cámara de vídeo con obturación y con un sensor
CCD.
Targeted - especifica si la cámara tiene un objetivo en la escena de 3ds
Max o no.
Film gate - especifica el tamaño horizontal de la película en milímetros.
Tenga en cuenta que este ajuste tiene en cuenta las unidades de la
configuración del sistema para producir el resultado correcto. El tamaño
vertical de la película se calcula con la relación de aspecto del fotograma
(tamaño de película vertical = tamaño de película horizontal / relación de
aspecto).
Focal length - especifica la longitud focal equivalente de la lente de la
cámara. Este ajuste tiene en cuenta las unidades de la configuración del
sistema para producir el resultado correcto.
FOV - cuando está activado, podemos establecer el campo de visión
directa, sin tener que configurar el film gate de la película ni la distancia
focal
Zoom factor - especifica un factor de zoom. Los valores superiores a 1,0
zoom en la imagen, valores inferiores a 1,0 nos alejan la imagen.
Horizontal offset – En horizontal compensa el campo de visión de la

Manual de Vray 2.0 46

<!-- p. 48 -->

cámara desplazándolo una fracción de la vista actual. Por ejemplo, un valor de 0,5 compensará la
cámara la mitad de la anchura actual de la imagen hacia la izquierda.
Vertical offset – En vertical compensa el campo de visión de la cámara desplazándolo una fracción de
la vista actual. Por ejemplo, un valor de 0,5 compensará la cámara la mitad de la altura actual de la
imagen hacia arriba.
Target distance - la distancia al objetivo de la cámara para una cámara específica.
F-number- determina el tamaño de la apertura de la cámara e, indirectamente, de la exposición. Si la
opción de la exposición está marcada, cambiando el f-number afectará a la exposicion de la imagen.
Distortion - especifica el coeficiente de distorsión de la lente de la cámara. Un valor de 0.0 significa
que no hay distorsión y los valores positivos producen una distorsion con efecto "barril", mientras que
los valores negativos producen una distorsión tipo "almohada".
Distortion Type - determina qué fórmula se utiliza para el calculo de la distorsión cuando el valor de
la distorsión no es cero:
Quadratic este es el tipo de distorsión por defecto. Se utiliza una fórmula simplifica, que es más fácil
de calcular que el método cubic.

Cubic este es el tipo de distorsión utilizado por las cámaras de algunos programas de tracking como
syntheyes, Boujou, etc… Si va a utilizar uno de estos programas, debe utilizar el tipo de distorsión
cubic.
Vertical shift y horizontal shift- permiten la simulación de lentes de cambio de la perspectiva de 2
puntos. La modificación de estos parámetros es similar a aplicar un modificador en la corrección de la
perspectiva de la cámara. Recomiendo utilizar los botones Guess vert y Guess horiz a fin de lograr la
perspectiva de 2 puntos.
Specify focus - lo que le permite especificar una distancia de enfoque diferente de la distancia al
target de la cámara.
Exposure - cuando esta opción está activada, el f-number, velocidad de obturación y ajustes de ISO
afectarán el brillo de la imagen.
Vigneting - cuando esta opción está activada, el efecto de viñeteado óptico de las cámaras del mundo
real se simula. También se puede especificar la cantidad del efecto viñeta, donde hay 0,0 no se
produce el efecto y con el valor 1.0 es la cantidad normal.
White balance - permite la modificación adicional de la salida de la imagen. Permite ajustar el
balance de blancos en los tonos de la imagen. Hay varios presets que se pueden utilizar, sobre todo el
de luz de día preestablecido para las escenas de exterior.
Shutter speed - la velocidad de obturación, medida en segundos a la inversa, para la cámara
fotográfica. Por ejemplo, si queremos una velocidad de obturación de 1 / 30 s corresponde a un valor
de 30 para este parámetro.
Shuter angle - ángulo de disparo (en grados) de la cámara cinematográfica.
Shutter offset – desplazamiento del obturador (en grados) de la cámara cinematográfica.
Latency – en un sensor CCD determina la latencia, en segundos, de la cámara de vídeo.
Film speed (ISO) - determina la sensibilidad de la pelicula (es decir, el ISO). Los valores más bajos
hacen que la imagen sea más oscura, mientras que los grandes valores hacen que sea más brillante.

Bokeh efectos
Estos parámetros controlan los efectos bokeh cuando la opción de la
profundidad de campo está activa.
Blades - define la forma de la apertura de la cámara. Cuando esta opción
está desactivada, la apertura es simulada perfectamente circular. Cuando
está encendido, se simula con una abertura poligonal, con un número
determinado de lados.
Rotation - define el giro del obturador.
Center bias - define un valor de bias para los efectos bokeh. Los valores positivos hacen que el borde
exterior sea más brillante, los valores negativos que el centro sea brillante.
Anisotropy - permite el estiramiento de los efectos bokeh en horizontal o verticalmente para simular
lentes anamórficas.

Manual de Vray 2.0 47

<!-- p. 49 -->

Sampling
Hay parámetros de control de la toma de muestras para la cámara virtual.
Depth-of-field – activa la toma de muestras de la profundidad de campo.
Motion blur – activa el muestreo de desenfoque de movimiento.
Subdivs - determina el número de muestras (rayos) para el cálculo de la
profundidad de campo y / o el desenfoque de movimiento.

Varios parámetros

Estos parámetros controlan otros aspectos de la cámara.
Horizon line - enciende y apaga en la pantalla la línea del horizonte de la
cámara en la vista perspectiva.
Clipping - enciende y se apaga el recorte de la cámara.
near / far clipping range - el rango de cerca / lejos del recorte, cuando
está encendido.
near / far env plane - (utilizado por algunos de los efectos atmosféricos en
3ds Max).

Notas

 El modificador de corrección de cámara no funciona con la VRayPhysicalCamera. En su lugar,
utilice el parámetro de desplazamiento vertical de la cámara con el mismo propósito.

 Hay tres tipos de FOV (campo visual): horizontal, vertical y diagonal. BiA horizontal depende del
tamaño de la puerta película, distancia focal, distancia de enfoque y zoom. Además de estos
cuatro parámetros, el vertical y diagonal BiA dependen de la relación de aspecto de la imagen.

 La configuración de Aperture width en el cuadro de diálogo Render setup no tienen ningún
efecto cuando el VRayPhysicalCamera se utiliza. En su lugar, debe utilizar la configuración del
DOF de la propia cámara.

 Algunos valores de desenfoque de movimiento (duración, etc) no tienen ningún efecto sobre la
VRayPhysicalCamera. En cambio, el desenfoque de movimiento es controlado por la propia
cámara (a través de los parámetros de velocidad de obturación, etc.)

Manual de Vray 2.0 48

<!-- p. 50 -->

V-Ray RT

General

V-Ray RT es un plugin de renderizado ActiveShade para 3ds Max. Para comenzar a usarlo, primero
debe seleccionar en Assign Renderer en el cuadro de diálogo render setup:

Seleccione V-Ray RT en el cuadro de diálogo que aparece:

Tenga en cuenta que V-Ray RT debe ser seleccionado como un renderizador de ActiveShade, no va a
funcionar como un renderizador de producción.

V-Ray RT, opciones

Shading
Trace depth - Representa el número máximo de rebotes que se
calcula para las reflexiones y refracciones. El individuo material de
reflexión / refracción de los ajustes de profundidad todavía se
consideran, siempre y cuando no exceda el valor especificado aquí.
GI depth- el número de rebotes de la iluminación indirecta. Otros
ajustes de GI (por ejemplo, si está activado o desactivado la GI) se
toman del renderizador de producción V-Ray.

Material override
Override mtl - Esta opción permite al usuario reemplazar los materiales de la escena en la
representación. Todos los objetos se representan con el material elegido, si se selecciona una, o con
los materiales asignados, si no se especifica el material.
Override exclude - Al hacer clic en este botón aparece el cuadro de diálogo 3ds Max de inclusión /
exclusión que le permite seleccionar exactamente los objetos a los que se les reemplaza los materiales.

Performance
Los parámetros en esta sección afectan al rendimiento de V-Ray RT. Tenga en cuenta que los valores
óptimos para una configuración dada de la máquina y la red pueden ser diferentes de los valores por
defecto. El usuario puede experimentar con estos valores para encontrar los óptimos.
Ray bundle size - Controla el número de rayos que se envían a los servidores de V-Ray RT para su
procesamiento. Cuando se utiliza la representación distribuida, los tamaños más pequeños causan que
sea más frecuente la comunicación cliente / servidor con los paquetes de red más pequeños lo que
disminuye la velocidad del procesador, pero el aumento de la interactividad, y viceversa. Tenga en
cuenta que este número no es la cantidad exacta de los rayos, pero es proporcional a la misma. No es
recomendable aumentar este valor más allá de 512.

Manual de Vray 2.0 49

<!-- p. 51 -->

Rays per píxel - El número de rayos que se trazan para cada píxel en cada imagen. Cuanto mayor
sea este valor, más suave será la imagen desde el principio de la representación con GI, pero la
interactividad puede disminuir considerablemente. El aumento de este valor también reduce la
cantidad de datos transferidos desde los servidores a la máquina cliente.
Show statistics - Cuando se activa esta opción, algunos valores útiles se muestran en la esquina
superior derecha de la ventana ActiveShade:

 V-Ray versión RT;
 Número de rayos a cámara calculados (es decir, muestras de imágenes) por segundo, en miles
(Kpaths / s);
 Tiempo transcurrido desde que la imagen actual se empezó a renderizar. Este valor se reajusta
cada vez que se realiza un cambio en la escena que requiere un nuevo cálculo de la imagen.

Rendering
Render Servers - Este botón abre el cuadro de dialogo del render interactivo de V-Ray.
Max render time especifica la cantidad de tiempor que se estará renderizando la imagen, después de
este tiempo el render ya no se refinará más.
Max path per pixel finaliza el render cuando llega a cierto número de rayos trazados por pixel,
podemos controlar que el render finalice cuando la imagen llegue a cierta calidad.

Engine
Type: CPU Renderiza usando la potencia del procesador, es el más compatible con la mayoría de
herramientas y materiales de V-Ray
Open Cl Usa los procesadores de la tarjeta gráfica para acelerar el render, tiene multitud de
incompatibilidades.

Locks
Lock render buffer - Bloquea el buffer por lo que al hacer más cambios en la escena de 3ds Max
estos no se reflejan en la ventana de ActiveShade (sin embargo V-Ray RT continúa perfeccionando la
imagen). Cabe señalar que antes de iniciar V-Ray render interactivo, esta casilla está desactivada.
Durante la representación, está desactivado de nuevo por lo que es imposible recuperar una vez que el
buffer de la interactividad está bloqueado. La única manera de hacerlo es mediante el cierre y la
reapertura de la ventana ActiveShade.

Adaptive sampling
Añade más muestras en las zonas con más ruido para que en el render salgan más suaves y
detalladas.
Show mask nos muestra en color rojo las zonas donde se añadirán más muestras para refinar ese
ruido.
Max noise. Controla la cantidad de refinamiento en el ruido, cuanto mayor es este número, más ruido
aparecerá en la imagen, cuanto menor es este valor más se refinará la imagen y llegará a menores
cantidades de ruido, si el valor lo ponemos en 0 no realizará ninguna adaptación y refinará el ruido por
igual en toda la imagen, llegando a refinar y perder tiempo de cálculo en zonas que no lo necesitan, no
es recomendable poner este valor.

. Vrscene exportación
El formato de archivo. Vrscene es el formato de descripción de escena utilizado por la versión Stand
alone de V-Ray. V-Ray RT le permite exportar sus escenas 3ds Max a este formato para la
representación posterior con V-Ray stand alone fuera de 3ds Max.
Export vrscene file-. Esta es la ruta seleccionada y completa del archivo, el nombre y la extensión se
fijan, la escena de 3ds Max se exporta al archivo especificado vrscene cuando V-Ray RT se inicia..
Don’t render (just export) - Permite a la escena ser exportada sin que se renderice. La sesión
ActiveShade será cerrada tan pronto como el archivo. Vrscene se crea. Tenga en cuenta que en la
actualidad la escena se exporta únicamente para el marco actual, sin animación.

Manual de Vray 2.0 50

<!-- p. 52 -->

3ds Max controles

ActiveShade en las ventanas (solo versiones de MAX
anteriores a la 2012)
El botón ActiveShade en el cuadro de diálogo Configuración de
Render inicia el V-Ray RT render en una ventana separada y el
tamaño de la ventana está determinada por la anchura y la altura
valores en la pestaña Común del diálogo mismo. Sin embargo, el
representador ActiveShade también se puede iniciar en una
ventana gráfica de 3ds Max, eligiendo ver ActiveShade en la
organización y de la vista. En este caso el tamaño de la imagen
representada es la misma que el tamaño de la ventana gráfica. Si
la opción Mostrar cuadro de seguridad está activada, la prestación
se limita dentro de ese marco. Cambiar el tamaño de la ventana
después de que el render V-Ray RT se ha iniciado, no se
recomienda debido a que el comportamiento no es estable.
Para devolver un visor ActiveShade a su estado normal, haga clic en cualquier parte, y elija Cerrar en
el menú cuad.
Tenga en cuenta que la ventana debe ser la perspectiva o la cámara de la vista cuando se convierta en
una ventana ActiveShade. Visores en modo usuario y ortogonal actualmente no son compatibles.
El estado ActiveShade de una ventana se guarda con la escena de 3ds Max. Si guarda la escena en un
estado donde una de las vistas es una ventana ActiveShade, cuando se carga la escena más tarde, 3ds
Max se iniciará automáticamente V-Ray RT para la misma ventana.

Como Renderizar una Animacion con Vray RT

Para renderizar con Vray RT una animación lo primero que debemos hacer es asignar como motor de
render el Vray RT. Antes de seguir creo que es obligatorio insistir que vray RT no es un motor para el
render de producción, es solo para hacer pre-visualizaciones y luego usar Vray para renderizar.

Si por el motivo que sea necesitamos generar una animación con Vray RT, en la siguiente imagen del
Render Setup veréis como he asignado el Vray RT como renderizador principal, en producción, también
está en las otras pestañas pero esto no influye para nada.

Manual de Vray 2.0 51

<!-- p. 53 -->

Nos aseguramos del rango de fotogramas que vamos a renderizar es el que queremos.

Una vez esta esta parte correctamente configurada nos vamos a la pestaña Vray RT y ponemos los
parámetros tal como veis en la imagen de la izquierda.
Importante los rayos por pixel, 40 es un valor alto, ya que queremos no limitar el motor por eso lo
subimos.
El tipo de Engine es el CPU, ya que por GPU no soporta ni los Proxy de la escena ni algunos materiales.
El Max render time lo he puesto a 6 minutos, el renderizador renderizará durante este tiempo y
guardará la imagen y continuará con el fotograma siguiente.
Max Path per pixel lo he subido a 200 para que no limite al tiempo de render, si lanzásemos a una
granja en la la diferencia de potencia entre los ordenadores fuera muy grande, podríamos poner una
número de pases de 20 o 100 o lo que quisiéramos y cuando llegase a ese valor o pasase una cantidad
de tiempo, lo que antes llegase, pasaría al fotograma siguiente. En este caso lo que busco es que
llegue antes esos 6 minutos que no esos 200 pases.

Manual de Vray 2.0 52

<!-- p. 54 -->

Recordar que bajar el valor del Adaptive sampling a 0 (el valor que se muestra en la imagen es el
incorrecto) nos desactivaría esta optimización, debemos dejarlo en 0,01.
Por ultimo he activado los Proxy para que los renderice.

El último paso es asignar un render output, una ruta donde guardar las imágenes del render. He usado
como formato de archivo el jpg, suficiente para la calidad que me ofrece Vray RT.

Manual de Vray 2.0 53

<!-- p. 55 -->

V-Ray RT usado como motor de render comparado con V-Ray Advance

He metido en un ordenador dos tarjetas Nvidia, una Geforce 295 y otra GeForce 240, en “Inicio/todos
los programas/chaos group/ V-Ray RT/Select Open Cl devices for Vray RT” me reconoce todos los
núcleos Cuda, 720 en total, sin SLI por que las tarjetas son diferentes. He puesto a renderizar el Vray
RT en modo OpenCL para ver cómo funcionaba.
Os adjunto los renders para que veáis los tiempos, en ningún momento me da los resultados tan
fantásticos que podemos ver en la web de ChaosGroup, también destacar que muchas cosas no las
reconoce, como algunos materiales con opacidad y efectos de cámara.
He dejado renderizando durante 6 minutos las imágenes GPU y CPU, luego la llamada CPU V2 la he
dejado 20 minutos en total.

Vray RT CPU

Vray RT CPU

Manual de Vray 2.0 54

<!-- p. 56 -->

Vray RT OpenCl

También he renderizado con Vray 2.0 para comparar, en modo Irradiance Map y Light Cache ha
tardado 10 minutos pero con peor calidad de iluminación y luego lo he puesto en Quasi Montecarlo
(Brute Force para los iniciados) y ha tardado solo 17 minutos, lo cual confirma que tal como prometen
los chicos de Chaos Group han mejorado los algoritmos de este método de cálculo.

Vray Irradiance Map + Light Cache

Manual de Vray 2.0 55

<!-- p. 57 -->

Vray Brute Force + Brute Force

Vray Brute Force (subdivs 20) + Light Cache

Vray Brute Force + Light Cache

Manual de Vray 2.0 56

<!-- p. 58 -->

Vray Irradiance Map + Brute Force

Vray Brute Force (subdivs 20) + Light Cache

Vray Brute Force + Light Cache

Manual de Vray 2.0 57

<!-- p. 59 -->

En conclusión, El VrayRT consigue sus mejores tiempos cuando queremos hacer pre-visualizaciones,
cuando queremos refinar el resultado, más allá de los 4-10 minutos, funciona mejor el motor de
render.
Cabe destacar que el método de cálculo para el RT está basado en Quasi Montecarlo, lo que me hace
pensar que la mejora del algoritmo se logró para poder desarrollar el RT y también se aprovechó para
el Renderizador. El QMC o Brute Force es el método más parecido que tiene Vray al cálculo unbiased,
en mi opinión mejor que el LightCache en modo "progressive path tracing"

Recomiendo usar Vray RT para lo que sirve, previsualización, olvidaros del render por GPU con Vray, al
menos hasta dentro de uno o dos años o es posible que más.
El render por GPU es el futuro, no me cabe ninguna duda, pero deberemos esperar unos años para que
sea una tecnología estable y fácil de usar con Vray.

Manual de Vray 2.0 58

<!-- p. 60 -->

3DValue, Consultoría Profesional para la Creación de Contenidos Digitales 3D
www.3dvalue.com
info@3dvalue.com
\+34 96 341 15 36
Síguenos en Twitter: twitter.com/3DValue
Síguenos en LinkedIn – Grupo V-Ray España

Actualidad 3D, Toda la actualidad del mundo del 3D. Programas técnicas y novedades.
www.actualidad3d.com

Tutoriales 3D.
www.tutoriales3d.es

ChaosGroup proporciona las soluciones más avanzadas de representación para la
arquitectura, efectos visuales para el cine, los medios de comunicación y el
entretenimiento, el diseño de automóviles, la televisión y otras industrias.
www.chaosgroup.com
