---
type: libro
title: "Manual de VRay"
author: "tonneti"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 370
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/3D MAX Y VRAY/MANUALES/MANUAL VRAY 1.5.pdf"
convertido: 2026-10-16
---

# Manual de VRay

> Texto extraído de `AYUDAS DE PROGRAMAS\3D MAX Y VRAY\MANUALES\MANUAL VRAY 1.5.pdf` (370 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Manual de VRay

Guías y tutoriales

Manual:

\-Manual de VRay . (Traducción: Urrechu)

Guías:

\-Guía de VRay . (Autor: Endora)
\-Guía del Editor de materiales. ( Autor: Endora)

Tutoriales:

Autor: Federico González Bosque.
Ajustes.
Integración de una figura 3D en otra imagen.
Materiales avanzados.
Pantalla de alfileres.
Crear cáusticas.

Autor: José Florencio "Slimo".
Modelado, iluminación y materiales.
Composición.
Post-producción.

Autor: Evermotion. (Traducción: Urrechu)
Vaso con mistela.
Postal de un cafetería.
Trazado progresivo.
Cómo representar el cuero.
Múltiples vistas con un solo mapa de irradiación.
Crear un lámpara fluorescente encendida.

Autor: Aversis. (Traducción: Urrechu)
Configuración básica para VRay.
Ajustes básicos de materiales.
Refracciones.
Reflexiones.
Una iluminación estándar.
Copa de cristal +líquido.

Manual

<!-- p. 2 -->

Manual

Contenido

Características
Instalación
Render
Material
Luces
Sombras
Mapas
Renderización Distribuida
Terminología
Preguntas más frecuentes

Características

Características de VRay

El trazador de rayos VRAY está disponible en dos paquetes, el Básico y el Avanzado. El Paquete Básico, por
su juego equilibrado de características y bajo precio es ideal para estudiantes y artistas aficionados. El Paquete
Avanzado incluye varias características adicionales y está dirigido a artistas profesionales.

Paquete Básico

· Reflexiones y refracciones reales (Ver: VRayMap)

· Reflexiones y refracciones brillantes (Ver: VRayMap)
· Translucidez para crear cera, cristales minerales, ahumados… (Ver: VRayMap)

· Sombras zonales (sombras suaves). Incluye emisores esféricos y de caja. (Ver: VRayShadow)

· Iluminación indirecta (iluminación global). Se incluye el cómputo directo (a fuerza bruta), y mapas de irradiación.
(Ver: Iluminación indirecta)

· Desenfoque de movimiento. Incluye Quasi-Monte Carlo (Ver: Desenfoque de movimiento)

<!-- p. 3 -->

· Efecto de profundidad de campo. (Ver: DOF )

· Antialiasing. Incluye accesos fijos, simples de 2 niveles y adaptables. (Ver: Image Sampler)

· Cáusticas (Ver: Cáusticas)

· G-buffer (RGBA, ID material/objeto, buffer-Z, velocidad etc.) (Ver: G-buffer)

Paquete Avanzado

Incluye todas las características básicas más:

· Antialiasing basado en buffer-G. (Ver: Image Sampler)

· Mapas de irradiación reutilizables. Muestra incremental para vuelo en animaciones. (Ver: Iluminación Indirecta )

· Mapas globales de fotones reutilizables. (Ver: Cáusticas )

· Desenfoque de movimiento con muestra analítica (Ver: Desenfoque de movimiento)

· Soporte HDRI real. Incluye *.hdr, *.rad, el cargador de imagen con coordenadas de textura que se utiliza para
mapas cúbicos y angulares. Trace un mapa de sus imágenes directamente, sin distorsiones.

· Área natal para una iluminación físicamente correcta. (Ver: VRayLight)

· Material Natal para más cálculos de materiales físicamente exactos y más rápidos. (Ver: VRay material)

· Renderización Distribuida para utilizar todos sus ordenadores de los estudios. Basado en TCP/IP permite
conectarse por Internet. (Ver: Renderización Distribuida)

· Diferentes tipos de cámara: objetivo “ojo de pez”, cámaras esféricas, cilíndricas y cúbicas (Ver: Cámara)

· Licencia de red para usar VRay en toda su red con menos licencias.

Instalación

Instalación

Instalación automática
Para instalar VRay automáticamente, presione dos veces el ratón sobre el archivo setup.exe y siga las
instrucciones. Durante el proceso se le preguntará por el directorio donde instalar los archivos VRay. Escoja el
directorio Max (el directorio donde está el archivo 3dsmax.exe). Si algo falla, podría pensar en una instalación
manual.

Instalación manual

Para instalar VRay a mano necesitará estos archivos:

VRay40.dll
VRender40.dll
VRayNet40.dlu
VRSpawnServer.exe
vraydummy.max

Deben colocarse en los directorios siguientes:

[MAXROOT]\VRay40.dll
[MAXROOT]\plugins\VRender40.dll
[MAXROOT] \plugins\VRayNet40.dlu

<!-- p. 4 -->

[MAXROOT]\VRSpawnServer.exe
[MAXROOT]\vraydummy.max

Donde [MAXROOT] es el directorio de Max. El directorio 'plugins' puede ser cualquiera del directorio plugins.
(Incluir el archivo .ini en la carpeta de plugins estándar de 3ds Max).

Nota: la instalación del pack Básico no incluye VRSpawnServer.exe, vraydummy.max y VRAYNET40.DLU

Render

Render. Parámetros

Estos parámetros le permiten controlar diferentes aspectos del proceso de renderización. Los parámetros VRay
están subdivididos en las secciones siguientes:

Contenido

Image Sampler (Antialiasing)

Profundidad de campo/Filtro Antialiasing

Iluminación indirecta/Parámetros del mapa de irradiación avanzada

Cáusticas

Ambiente

Desenfoque de movimiento

Ejemplo de QMC

G-buffer

Cámara

Sistema

Image Sampler

Image Sampler (Anti-aliasing)

VRay utiliza distintos algoritmos para muestrear una imagen. Todos los ejemplos de imagen soportan el
antialiasing estándar de MAX, aunque a costa del tiempo de renderización. Usted puede escoger entre Fixed
rate, Simple two-level y Adaptive subdivisión.

Fixed rate

<!-- p. 5 -->

Es la nuestra de imagen más simple, y toma un número fijo de muestras para cada píxel

Subdivs - Ajusta el número de muestras por píxel.

Rand - Cuando está seleccionado, las muestras serán desplazadas cuasi-al azar dentro del píxel. Esto producirá
mejores resultados visuales.

Simple de dos niveles (Simple two-level)

Un nuestra sencilla adaptable. Los píxeles se prueban primero con un número bajo de muestras y luego algunos
son potenciados para mejorar la calidad de la imagen.

Base subdivs - Determina el número de muestras tomadas para cada píxel.

Fine subdivs - Determina el número de muestras para píxeles potenciados.

Threshold (Umbral) - Todos los píxeles vecinos con diferencia de intensidad mayor que el valor Threshold serán
potenciados. Valores inferiores producen mejor calidad de imagen.

Multipass - Con esta opción VRay el valor del píxel será comparado con los píxeles vecinos que no estaban
potenciados. Si la diferencia es mayor que el valor Threshold estos píxeles vecinos serán potenciados.

Nota: Esta opción es útil porque el píxel al que se ha potenciado la intensidad, a veces causa mayores
diferencias de intensidad con algunos píxeles vecinos.

Rand - Ver Sampler.

Subdivisión adaptativa. (Adaptive subdivision Sampler).

Es una muestra de imagen avanzada capaz de tomar menos de una muestra por píxel. Esta es la mejor nuestra
de imagen y la preferida en VRay. Por regla general toma menos muestras (y así tarda menos tiempo) para
alcanzar la misma calidad de imagen que otras nuestras.

Min. rate - Controla el número mínimo de muestras por píxel. Un valor cero significa una muestra por píxel.

Max. rate - Controla el número máximo de muestras (“sampler”) por píxel.

Threshold (Umbral)- Ver nuestra simple de dos niveles, arriba.

Multipass - Ver nuestra simple de dos niveles, arriba.

Rand - Ver nuestra de rate fijo, arriba.

Antialiasing basado en G-buffer . (G-buffer based antialiasing)

Object outline (Contorno de objeto) - Cuando esta activada VRay forzará el alisamiento de los bordes que forman
el contorno del objeto.

Nota: si quiere alisar los bordes de todo el objeto, debería usar también Normals Antialiasing.

Normals - Cuando esta opción está activada VRay lleva al antialias aquellas muestras vecinas donde el ángulo
entre su normal es mayor que el valor de umbral (el valor de umbral normal puede seleccionarse en la caja
Normals). Un valor de 0.0 corresponde a 0 grados, mientras que un valor de 1.0 corresponde a 180 grados.

Z-value - Cuando esta opción está seleccionada lleva la imagen al antialias cuando la diferencia en el valor Z de
las muestras de imagen vecinas es mayor que el valor de umbral (el valor de umbral puede especificarse en la
caja con la opción Z-value).

Material ID (Identificación del material)- Cuando esta opción está activada VRay lleva al antialias la imagen
donde las muestras de imagen vecinas tienen diferentes ID de material.

Nota: La selección de nuestras para sus imágenes puede tener efectos drásticos en la calidad/velocidad. En
general, si no tiene efectos desenfocados (Direct GI, glossy reflections / refractions, area lights / shadows,
translucency), el nuestreo será más rápido y producirá los mejores resultados. Si su escena incluye muchos
efectos desenfocados (sobre todo combinaciones entre ellos, y más aún con Direct GI y DOF), utilice Fixed or
the Two-level sampler . Si sólo hay unas zonas que necesitan antialiasing, usará Two-level sampler, pero si tiene

<!-- p. 6 -->

muchos detalles (por ejemplo mapas de textura finos), Fixed rate sampler podría funcionar considerablemente
mejor que los otros dos.

Nota: pueden ser mezcladas libremente las diferentes opciones de G-buffer antialiasing.

Nota: G-.buffer antialiasing no depende de los canales seleccionados en los parámetros de canales de
salida(Output channels) .

Nota: VRay siempre alisa según el esquema seleccionado (Fixed rate / Simple two-level / Adaptive
subdivision). Por lo tanto las opciones que controlan G-buffer antialiasing no tienen ningún efecto cuando el
esquema Fixed rate antialiasing está seleccionado.

Nota: VRay siempre considera los colores de las muestras de imagen. Si quiere el antialias sólo según
alguna propiedad G-buffer, debe escoger Simple two-level o Adaptive subdivision antialiasing y el valor
Threshold bastante alto para deshabilitar el antialiasing en el color.

Ejemplo de Image Sampler

Ejemplo de Image sampler

Cuando la opción Rand está activada el sampler es desplazado cuasi al azar dentro del píxel.

Rand = off, Subdiv = 2 (zoom x2)

Rand = on, Subdiv = 2 (zoom x2)
Las imágenes siguientes contrastan la diferencia entre las escenas renderizadas con y sin antialiasing.

Nota: Sampler con Subdivs a 1 no es equivalente a ningún antialiasing.

<!-- p. 7 -->

Fixed rate Sampler, subdivs=1

Fixed rate Sampler, subdivs = 4
Las imágenes siguientes muestran el efecto de la opción Multipass en la muestra Simple 2 -level. Ambas
imágenes han sido hechas con Sampler Simple 2-level, el valor Base subdivs está en 1, Fine subdivs = 4, rand
\= off..

Multipass = off

<!-- p. 8 -->

Multipass = on
Las imágenes siguientes muestran la diferencia en Simple 2-level y Adaptive samplers. Multipass para ambos
sampler está en on y Rand en off. Si observa con detalle las áreas marcadas, notará que hay ciertas diferencias
en la primera imagen (Simple 2-level Sampler).

Simple 2-level Sampler, Base subdivs = 2, Fine subdivs=4

Adaptive Sampler, Min rate = -2, Max rate = 4

Profundidad de campo

<!-- p. 9 -->

Profundidad de campo (Filtro Depth of field/Antialiasing)

Este es un efecto que permite la renderización de la imagen como si fuera tomada por una cámara enfocada en
algún punto de la escena.

On - Habilita (o no) la profundidad de campo

Focal dist - Distancia focal del punto que se enfocó (sharp).

Get from camera - Con esta opción, la distancia focal de la cámara se tomará automáticamente. Para cámaras
fijas es la distancia entre la cámara y su objetivo, y para cámaras libres es el juego de ajustes de la cámara.

Shutter size - Tamaño del obturador en unidades reales. Valores más altos producen más desenfoque.

Subdivs - Determina el número de muestras para el efecto de profundidad de campo (Depth of field). Mayores
valores producirán mayor calidad.

Filtrado (Filtering)

On – Activar/desactivar. Cuando la filtración está seleccionada, puede escoger un filtro apropiado para la escena.
VRay trabaja con los filtros estándar de Max antialiasing (excepto el "Plate Match").

Size - Tamaño del filtro.

Nota: Cuando filtración está desactivada, VRay usará una caja de filtro interna de 1x1 píxel.

Ejemplo de Profundidad de campo

Ejemplo de Profundidad de campo (Depth of field)

Modificando el valor de distancia focal se determinan qué partes de la escena aparecerán enfocadas (sharp).

Focal dist =150 (El cono está enfocado)

<!-- p. 10 -->

Focal dist=220 (La esfera está enfocada)
Cambiando el valor Shutter size se determina cuánto son desenfocadas las diferentes partes de la escena
según la distancia del foco al espectador.

Shutter size = 4, Focal dist = 200

Shutter size = 12, Focal dist = 200
Modificando lo valores Subdivs value se determina cuánto de liso es el efecto DOF renderizado.

<!-- p. 11 -->

Subdivs = 3, Filtering = on

Subdivs = 5, Filtering = on

GI (Iluminación Indirecta)

Iluminación indirecta (GI)/ Mapa de Irradiación Avanzado

VRay utiliza dos métodos para calcular la iluminación global -el cómputo Directo y el mapa de Irradiación.
Aunque el cómputo directo es un algoritmo simple que utiliza todos los rayos para calcular el GI, produce la mejor
exactitud en los resultados, sin embargo a costa de renderizaciones más largas. El mapa de irradiación es un
algoritmo que usa técnicas sofisticadas de caching y produce resultados menos exactos con menor tiempo de
renderización.

On – Activa/desactiva GI.

<!-- p. 12 -->

First diffuse bounce. (Primer salto difuso)

Multiplier - Este valor determina cuánto se difunden los rebotes en la iluminación final de la imagen.

Direct computation parámeters. (Cómputo directo de parámetros)

Direct computation (Computación directa)- GI es calculado usando el trazado de rayo directo. (Ray tracing)

Subdivs (Subdivisiones) - Este valor determina el número del hemisferio para calcular la luz indirecta. Los valores
inferiores producen más ruido.

Mapa de irradiación. Parámetros

Irradiance map - GI es calculado y almacenado en un mapa especial antes de la renderización real. (Por lo
general es más rápido que Direct computation)

Show adaptive - La conexión de esta opción le deja ver cuántas muestras GI fueron tomadas de las diferentes
partes de la escena.

Min rate - Este valor determina el número mínimo de muestras de GI por píxel. Usted por lo general querrá
guardar este negativo, para que el GI sea calculado rápidamente en zonas grandes y planas de la imagen. Nota:
si el valor Min rate es mayor que, o igual a cero, el cómputo del mapa de irradiación será más lento que la
renderización GI con Direct computations. VRay también consumirá mucha más memoria.

Max rate - Este valor determina el número máximo de muestras GI por píxel.

Clr thresh - Cuando la diferencia de intensidad entre las muestras GI vecinas excede el valor Clr thres, VRay
tomará más muestras GI.

Nrm thresh - Cuando el coseno del ángulo entre vectores junto a las muestras excede el valor Nrm thresh VRay
tomará más muestras.

HSph. subdivs - El número de hemisferio tomado para calcular GI.

Interp. samples - El número GI por punto, almacenado en el mapa de irradiación.

Secondary bounces (Rebotes secundarios)

Multiplier - Multiplicador para la irradiación de rebotes secundarios. (Ver First diffuse bounce Multiplier)

None - Cuando está seleccionado, VRay no utiliza rebotes secundarios de rayos.

Subdivs - Este valor determina qué número de hemisferio toma para calcular los rebotes secundarios de GI.

Depth - Este valor determina el número de rebotes indirectos.

Advanced irradiance map parameters (Parámetros de mapa de Irradiación Avanzada) (Únicamente
disponible con Irradiance map activada)

Interpolation type – Este cuadro le deja escoger la ruta donde VRay interpola las muestras de GI almacenadas
en el mapa de irradiación para calcular la muestra GI para un píxel dado. Los ajustes disponibles son Weighted
average, Least squares fit, Delone triangulation. (Promedio ponderado, la menor parte, triangulación Delone)

<!-- p. 13 -->

Don't delete on render end – (No suprimir en el render final) -Si está activado, VRay mantendrá el mapa de
irradiación en la memoria después de terminar la renderización de la escena. Si no, el mapa será suprimido y la
memoria que ocupa será liberada.

Nota: esta opción puede ser muy útil si se quiere calcular el mapa de irradiación para una escena particular sólo
una vez y luego reutilizarla para la posterior renderización. Para crear un mapa nuevo elija Don't delete on render
end (no eliminar en el render final) y Single frame. Después de que el mapa de irradiación esté calculado, puede
cancelar la renderización y guardar el mapa en un archivo.

Single frame – (Solo un frame) En este caso VRay calcula el mapa de irradiación para cada frame por separado.
Cualquier mapa de irradiación anterior es borrado.

Multiframe incremental - En este caso VRay calcula el mapa de irradiación del frame actual basado en el mapa
del frame anterior. VRay calcula dónde tienen que ser tomadas nuevas muestras de GI y luego las agrega al
mapa de irradiación anterior. El mapa de irradiación para el primer frame es calculado por separado; cualquier
mapa de irradiación anterior es suprimido.

From file (de archivo) - El mapa de irradiación para cada frame es el mismo. Se carga el archivo especificado y
cualquier mapa de irradiación anterior es borrado.

Add to current map (Agregar al mapa actual) - En este caso VRay calcula el mapa de irradiación del frame actual
por separado y suma éste al mapa del frame anterior (para el primer frame, el mapa de irradiación anterior podría
ser el mapa guardado al terminar la última renderización.

Incremental add to current frame (Agregar al frame actual) - En este caso VRay calcula el mapa de irradiación del
frame actual basado en el mapa del frame anterior. VRay calcula dónde tienen que ser tomadas muestras de GI
nuevas y luego las agrega al mapa de irradiación anterior (para el primer frame, el mapa de irradiación anterior
podría ser el mapa dejado terminado de la última renderización).

Nota: VRay no tiene una skylight (luz solar) separada. El efecto “claraboya” puede lograrse poniendo color de
fondo o el mapa de ambiente en el diálogo de ambiente de MAX, o en el propio diálogo de Ambiente del VRAY'.

Ejemplo de GI (Iluminación Indirecta)

Ejemplo de Iluminación Indirecta

Las dos imágenes siguientes han sido hechas sin GI.

GI – of. Ninguna fuente de iluminación

<!-- p. 14 -->

GI - off. Escena con una fuente de iluminación Omni.

Las imágenes siguientes están hechas con GI usando Direct Computation. No hay ninguna fuente de iluminación
en la escena, solamente el juego de color de "claraboya" para iluminar el color gris (195,195,195). La carencia de
suficientes muestras de GI (valor Subdivs demasiado bajo) producirá más ruido.

Direct Computation, Subdivs-5. Secondary-off. 58 seg.

Direct Computation, Subdivs-11. Secondary-off. 2 min. 9 seg.
Las imágenes siguientes muestran la renderización GI con el mapa de irradiación. Los ajustes comunes para
ambas imágenes son: Secondary bounces = off, Clr thresh = 0.8, Nrm thresh = 0.5, HSph. subdivs = 15, Interp.
samples = 30.

Min rate = -4, Max rate = -4,5sec.

<!-- p. 15 -->

Min rate = -2, Max rate = -1,27sec.
Las imágenes siguientes muestran el efecto Secondary bounces. La configuración es: Irradiance map, Clr thresh
\= 0.8, Nrm thresh = 0.5, HSph. subdivs = 15, Interp. samples = 30, Min rate= -2, Max rate = -1.

Secondary bounces = off

Secondary bounces, Multiplier = 0.4, Depth= 3, Subdivs =1

Cáusticas

Cáusticas (Caustics)

<!-- p. 16 -->

Como sistema de renderización avanzado VRay soporta la renderización de efectos cáusticos. Para producir
este efecto debe tener generadores y receptores de cáusticas apropiados en la escena. (Para información sobre
cómo hacer de un objeto un generador/receptor de cáusticas, lea las secciones Object settings y Lights
settings en Render parameters > System > Object/Light settings. Los ajustes desde esta sección controlan la
generación del mapa de fotones. (Una explicación del mapa de fotones puede verse en la sección
Terminología).

On – Habilita/deshabilita las cáusticas.

Multiplier - Este multiplicador controla la fuerza de las cáusticas. Es global y se aplica a todas las fuentes de
iluminación que generan cáusticas. Si quiere multiplicadores diferentes para fuentes de iluminación diferentes,
debería usar los ajustes locales de luz.

Nota: este multiplicador es acumulativo con los de los ajustes locales de luz.

Search dist - Cuando VRay utiliza un fotón que golpea un objeto en algún punto, el trazador de rayos busca otros
fotones en el mismo plano en el área circundante (el área de búsqueda). El área de búsqueda, de hecho es un
círculo con el fotón original en el centro, y su radio es igual al valor Search dist.

Max photons - Cuando VRay utiliza un fotón que golpea a un objeto en algún punto y cuenta los fotones del área
circundante, hace un promedio de la iluminación de aquella área, basada en el número de fotones que tiene. Si
los fotones son más que Max photons, VRay sólo usará el primero de ellos.

Don't delete on render end - Cuando esté comprobado, VRay mantendrá el mapa de fotones en la memoria
después de terminar la renderización de la escena. Si no, el mapa será suprimido y la memoria que ocupa será
liberada. Nota: esta opción puede ser útil sobre todo si se quiere calcular el mapa de fotones para una escena
particular sólo una vez, y luego reutilizarlo para la posterior renderización.
Modo

New map - Cuando esta opción está seleccionada, se generará un nuevo mapa de fotones. Éste se superpondrá
a cualquier mapa de fotones dejado de la renderización previa.

Save to file - Pulse este botón si quiere guardar un mapa de fotones ya generado.

From file – Con esta opción VRay no calculará el mapa de fotones, pero lo cargará de un archivo. Pulse el botón
Browse de la derecha para especificar el nombre del archivo.

Ejemplo de Cáusticas

Ejemplo de Cáusticas

Ajustes comunes de las imágenes: Sph. subdivs = 50, Multiplier = 17000, Max photons = 60. El número de
fotones (Sph. subdivs) se ha seleccionado bajo adrede para que los fotones separados sean más diferentes.

<!-- p. 17 -->

Search dist = 1

Search dist = 10
Los ajustes comunes para las imágenes son: Sph. subdivs = 300, Multiplier = 1700, Max photons = 60. El número
de fotones es mayor que en las renderizaciones anteriores, pero es todavía más bajo que los ajustes por defecto
de VRAY.

Search dist = 1

<!-- p. 18 -->

Search dist = 5
Ajustes: Sph. subdivs = 4000, Multiplier = 17000, Search distance = 0.5. El número de fotones se ha aumentado
bastante, y la distancia de búsqueda se ha bajado para que el efecto Max photons sea más evidente.

Max photons = 1

Max photons = 60
Las imágenes siguientes muestran las cáusticas producidas con Glossy y sin Glossy (materiales de refracción
brillantes). Ajustes: Multiplier = 17000, Search dist = 5, Max photons = 60.

<!-- p. 19 -->

Glossiness = 1.0

Glossiness = 0.9, Max photons = 200, Search dist = 15

Ambiente

Ambiente (Enviroment)

En la sección de parámetros de ambiente es donde se puede especificar un color y un mapa para usar durante
los cálculos de reflexión/refracción y GI. Si no se especifica un color/mapa, serán usados en su lugar el color de
fondo y el mapa de Max.

Override MAX's - Con esta opción VRay usará el color y la textura especificados durante el GI y los cálculos de
reflexión/refracción.

Color - Le permite especificar el color de fondo (skylight).

Multiplier - Un multiplicador para el valor Color.

<!-- p. 20 -->

Texture - Le deja escoger una textura de fondo.

Desenfoque de movimiento

Desenfoque de movimiento (Motion blur)

En esta sección puede escoger el método para desenfocar la escena según sus propiedades. En los controles
puede escoger el método de desenfocar la escena, y según las propiedades. Los dos algoritmos disponibles de
VRay son Monte Carlo motion blur y Analytic motion blur.

On – Conmutador de desenfoque.

Duration (frames) - Este valor determina el número de frames que VRay tiene en cuenta cuando el desenfoque
de movimiento se calcule para el frame actual. (El tiempo que el obturador de la cámara virtual estará abierto).

Low samples - Este valor controla el número de las muestras de tiempo que serán usadas por VRay para
calcular el desenfoque de movimiento durante los cálculos de GI.

Geometry samples - Este valor determina qué número de geometría tendrá en cuenta al desenfocar el frame.
Una muestra de geometría es una red con una posición particular en un tiempo dado. Para calcular el
desenfoque de movimiento VRay asume el movimiento linear entre varias posiciones. (Muestras de geometría).
Cuando una red cambia de posición, las muestras de geometría se ponen directamente según el valor Duration
(frames).
Nota: VRay asume el movimiento linear de vértices de red de una muestra de geometría al siguiente.

Probando Monte Carlo

Min samples - El tiempo mínimo de prueba por muestra de imagen. El aumento de este valor produce resultados
más alisados a costa de aumentar el tiempo de renderización.

Max samples - Este valor determina las muestras de tiempo máximas por muestra.

Threshold (Umbral) - Cuando la diferencia de color entre las muestras de imagen próximas es mayor que el
valor Threshold, VRay tomará muestras durante más tiempo. Si está seleccionado el valor más alto de Threshold
tendrá una gran diferencia en el color por hacer que VRay tome muestras durante más tiempo. Esto producirá
menos tiempo en las tomas de muestra y más ruido, y tiempos de renderización más cortos.

Probando Analytic

Material min samples - Este valor determina el número mínimo de muestras por cara. Valores inferiores
producirán más ruido sobre texturas detalladas.

Material max samples - Este valor determina el número máximo de muestras.

Material threshold - Ver Threshold en la susodicha sección

Ejemplo de Desenfoque de movimiento

<!-- p. 21 -->

Ejemplo de Motion blur (Desenfoque de movimiento).

Efecto motion blur necesitará al menos de 2 frames para que VRay asuma el movimiento de red. (Un cambio de
la posición/orientación) y en consecuencia el desenfoque de aquella red.

Motion blur – off.

Motion blur - on.
La siguiente escena consiste en la animación de tres frames de un cono que se mueve. En el primer frame el
cono está a la izquierda. En el segundo está en la caja, y en el tercero a la derecha.

Escena

<!-- p. 22 -->

Frame 3 con motion blur
Las imágenes siguientes muestran el efecto de los valores de parámetro Duration (frames). Esta es la frame #3
renderizada con Analytic sampling: Min samples = 4, Max samples = 8, Geometry samples = 5.

Duration(frame) = 0.5

Duration (frames) = 2

Las imágenes siguientes manifiestan el parámetro Geometría. Duration (frames) está seleccionado en 2. Los
demás parámetros son los mismos que en las imágenes anteriores. El mayor valor se ha seleccionado para
Geometry samples para un cálculo más exacto del movimiento del objeto. Sin embargo, el aumento excesivo de
este valor aumentará el tiempo de renderización.

<!-- p. 23 -->

Geometry simples = 2

Geometry simples = 8

Las imágenes siguientes muestran la diferencia entre la prueba de Monte Carlo y la prueba de Analític. Con la
prueba de Monte Carlo, en la imagen final hay una cierta cantidad de ruido. Sin embargo para escenas de redes
de alta densidad es mucho más rápido. Prueba de Monte Carlo: Min samples = 10, Max samples = 40,
Threshold = 0.01. Controle con estos comandos la cantidad de ruido. Los ajustes para la prueba analítica son no
pertinentes para esta escena debido a la ausencia de materiales.

Prueba con Quasi Monte Carlo

<!-- p. 24 -->

Prueba con Analytic

Ejemplo de QMC

QMC samplers

Lock to píxels. (Bloqueo de píxeles)

\-Esta caja de controles dirige el motor de generación cuasi-arbitrario del VRAY'. En la renderización VRay usa
pequeños valores cuasi-arbitrarios para producir los mejores resultados visuales. Si la opción está On, VRay
generará valores dependiendo de los píxeles que se han dado. En este caso dos renderizaciones de un mismo
frame producirán el mismo resultado y así, en una animación será evitado cierto efecto de parpadeo. Sin
embargo, si desactiva la opción Lock to píxels, dos renderizaciones del la misma frame serán ligeramente
diferentes. En aquel caso una animación con un valor no suficientemente alto de subdivs aparecerá
parpadeando, porque los valores QMC generados para una frame son completamente diferentes de los
generados para la otra.

Adaptation -
Los ajustes en esta sección se refieren a cómo VRay adapta el motor Cuasi Monte Carlo al valor actual
calculado.

To result multiplier - Este valor es el nivel de optimización que VRay toma basado en el multiplicador del
resultado de una muestra. Por ejemplo, la iluminación indirecta tendrá menos efecto sobre un objeto con un color
oscuro difuso comparado con otro brillante. Esto puede acelerar considerablemente la renderización sin sacrificar
demasiado la calidad de la imagen final. Un valor 1.0 significa la adaptación completa (esta es la opción más
rápida), y un valor 0.0 deshabilitará esta clase de optimización.

To sample difference - Este valor es el nivel de optimización que VRay toma, basado en la diferencia entre la
prueba tomada para calcular un valor. Por ejemplo, si la diferencia entre muestras es suficientemente baja VRay
decide que no hay ninguna razón para tomar más muestras. Esto puede acelerar considerablemente la
renderización sin sacrificar demasiado la calidad de la imagen final. Un valor promedio de 1.0 es la adaptación
completa (esta es la opción más rápida), y un valor de 0.0 inutilizará este tipo de optimización.

Difference threshold - Este valor le permite especificar el umbral de diferencia para las muestras. Si permite a
Adaptación probar la diferencia, VRay comparará la diferencia de las muestras con este valor para decidir si hay
que tomar más.

Nota: este ajuste no tiene ningún efecto cuando To sample difference está seleccionado en 0.0.

<!-- p. 25 -->

G-buffer

G-buffer

VRay soporta el G-buffer con los canales opcionales siguientes: Z-value, Unclamped color, Normal, Material ID,
Material color, Material transparency, Object velocity, Node ID, Render ID. Los canales disponibles se muestran
en la lista Output channels y cada uno puede ser seleccionado/deseleccionado con un clic del botón izquierdo
del ratón.

Z-value - Este canal proporciona un buffer de profundidad.

Unclamped color - Este canal proporciona un buffer para almacenar colores “insujetados con abrazaderas”. Esto
puede resultar útil sobre todo cuando quiera producir una imagen HDRI.

Normal - Este canal proporciona un buffer para almacenar vectores normales.

Material ID - Este canal proporciona un buffer para almacenar el material ID.

Material color - Este canal está lleno del color material. El color es calculado como si no hubiera ningún material
transparente en la escena. (No se hace caso a la transparencia de ningún material).

Material transparency - Este canal proporciona un buffer alfa. Allí VRay almacena la transparencia del material
para cada píxel de la imagen.

Object velocity - En este canal VRay almacena la velocidad de los objetos por píxel. Esto permite una variedad
de efectos post-render, incluyendo el desenfoque.

Node ID (Identificación del nodo) - Este canal proporciona un buffer Node ID. El Node ID puede ponerse por
objeto (no son necesarias IDs diferentes para objetos distintos) por las propiedades del objeto de Max. Hágalo
así pulsando con el botón derecho sobre el objeto deseado y las propiedades escogidas. En la etiqueta General
vaya a G-buffer y varíe el valor de Object Channel. (Este es el Node ID del objeto).

Render ID - Este canal proporciona el buffer Render ID. El Render ID es un número entero que VRay asigna a
cada objeto de la escena. Usted no puede cambiar las Render IDs de los objetos porque se generan
internamente. VRay garantiza que todas las Render ID son únicas y constantes. (Una vez asignada, la ID de un
objeto no se cambia hasta que termine la renderización).

Nota: como todos los valores de Buffer-G son almacenados por píxeles, y debido al hecho de que VRay por lo
general toma varias muestras de imagen por píxel, es importante tener una cierta regla para decidir cuál de los
valores de las muestras escribir en el Buffer-G. Actualmente, para cada píxel VRay recoge el valor de la muestra
que está más cerca del centro de un píxel.

Cámara

Cámara

<!-- p. 26 -->

Las cámaras en VRay definen los rayos que se proyectan en la escena, que básicamente es cómo se proyecta la
escena es en la pantalla. VRay soporta varios tipos de cámara: Standard, Spherical, Cylindrical (point),
Cylindrical (ortho), Box y Fish eye. Las vistas orto también se soportan.

Override FOV (Anular FOV) - Con este ajuste se puede anular el ángulo FOV de Max (solamente si conviene).

FOV - Aquí se especifica el ángulo FOV (sólo cuando Override FOV está conectado y el tipo de cámara actual
soporta el ángulo FOV).

Height - Aquí usted puede especificar la altura de la cámara Cylindrical (ortho). Nota: este ajuste está disponible
sólo cuando Type está seleccionado como Cylindrical (Ortho).

Auto-fit - Este ajuste controla la opción de la cámara de Objetivo de ojo de pez. Cuando Auto-fit está
seleccionado VRay calculará el valor Dist automáticamente para que la imagen quepa horizontalmente.

Dist - Este ajuste se aplica sólo con la cámara Fish-eye. La cámara Fish-eye simula una cámara Estándar con
una esfera absolutamente reflexiva (con un radio de 1.0) que refleja la escena en el obturador. El valor Dist
decide cómo de alejada está la cámara del centro de la esfera (qué parte de la esfera será capturada por la
cámara). Nota: este ajuste no tiene efecto cuando la opción Auto-fit está seleccionada.

Curve - Este ajuste se aplica sólo con la cámara de objetivo ojo de pez. Este ajuste resuelve el modo en que la
imagen será curvada. Un valor 1.0 corresponde a la imagen verdadera de objetivo de un ojo de pez. Cuando el
valor se acerca a 0.0 se aumenta la acción de curvatura. Cuando el valor se acerca a 2.0 se reduce la acción de
combar. Nota: de hecho este valor controla el ángulo en el que los rayos son reflejados por la esfera de la
cámara virtual.

Type

En esta lista se puede seleccionar el tipo de cámara. Los tipos disponibles son Standard, Spherical, Cylindrical

(point), Cylindrical (ortho), Box, Fish eye.

Standard - Esta es una cámara estándar. El arco rojo en el diagrama corresponde al ángulo FOV.

Spherical - Esta es una cámara esférica, lo que significa que sus objetivos tienen forma esférica. El arco rojo en
el diagrama corresponde al ángulo FOV.

<!-- p. 27 -->

Cylindrical (point) - Con este tipo de cámara todos los rayos tienen un origen común. El arco rojo en el diagrama
corresponde al ángulo FOV. Nota: en la dirección vertical la cámara se comporta como una cámara estándar, y
en dirección horizontal actúa como cámara esférica.

Cylindrical (ortho) - Con este tipo de cámara todos los rayos son paralelos. Nota: en la dirección vertical la
cámara se comporta como en vista orto, y en dirección horizontal actúa como una cámara esférica.

<!-- p. 28 -->

Box (Caja)- La cámara de caja es simplemente 6 cámaras estándar colocadas a los lados de una caja. Este tipo
de cámara es excelente para la generación de mapas de ambiente para trazar un mapa cúbico. También puede
ser muy útil para la GI. Calcule el mapa de irradiación con una cámara Box, guárdelo en un archivo y podrá
reutilizarlo con una cámara estándar que puede señalar en cualquier dirección.

Fish eye (Ojo de pez) - Este tipo especial de cámara captura la escena como si fuera la cámara normal
apuntando a una esfera absolutamente reflexiva que refleja la escena en el obturador. Se pueden usar los
ajustes Dist/FOV para controlar la parte de la esfera qué será captada por la cámara. El arco rojo en el diagrama
corresponde al ángulo FOV. Nota: la esfera tiene siempre un radio de 1.0.

<!-- p. 29 -->

Sistema

System

Desde esta sección puede controlar los distintos parámetros de VRay. Estos están divididos en las secciones
siguientes:

Raycaster params

Aquí puede controlar varios parámetros del VRAY –BSP (División de Espacio Binario Árbol)

Max tree depth - La profundidad máxima del árbol.

Min leaf size - El tamaño mínimo de una hoja. Más allá de este punto no habrá ninguna subdivisión posterior.

Face/level coef - Controla la cantidad máxima de triángulos en una hoja.

<!-- p. 30 -->

Render region division

Aquí puede controlar varios parámetros de la renderización de zonas (cubos) de VRAY. El cubo es una parte
esencial del sistema de renderización de VRAY. Un cubo es una parte rectangular de un frame dado, que es
dado por separado desde otros cubos. Los cubos pueden ser enviados para funcionar en LAN para su
procesamiento y\o pueden ser distribuidos entre varias CPUs. Como un cubo puede ser procesado solamente
por un procesador, la división del frame en demasiado número de pequeños cubos puede lograr una utilización
óptima de los recursos de PCs. Sin embargo la división del frame en demasiados cubos puede reducir la
velocidad de renderización porque hay un tiempo relacionado con cada cubo (el sistema cúbico, la transferencia
en el LAN, etc.).

X - determina la anchura máxima de región en píxeles (Region W/H seleccionada), o el número de zonas en la
dirección horizontal. (Cuando Region Count está seleccionada).

Y - determina la altura máxima de la región en píxeles (W/H de Región está seleccionada), o el número de zonas
en la dirección vertical. (Cuando Region Count está seleccionada).

Region sequence - Determina el orden de las zonas.

Reverse sequence – Retrocede a Region sequence.

Nota: Cuando Image Sampler está seleccionada como Adaptive Sampler el tamaño de los cubos cambiará
hasta un número próximo a 2.

Render compartido

Render compartido (Distributed rendering)

Distributed rendering - Este checkbox especifica si VRay usará la Renderización Distribuida.

Ajustes - este botón abre la caja de diálogo VRay Networking settings.

VRay Networking settings (Ajustes de conexión a red)

Networking settings está organizado en dos subdivisiones: Manager Settings y System Settings.

Manager Settings. (Configuración de ajustes)

Search - Pulsando este botón hace que VRAY busque a servidores sobre la red que están listos a hacer la
renderización distribuida. Esto toma aproximadamente 2 segundos para explorar la red. Todos los servidores que
fueron encontrados serán agregados en la lista debajo del botón. Un clic con el de botón derecho del ratón sobre
el nombre de un servidor despliega un menú que le permite habilitarlo o no, y marcar la prioridad del servidor
correspondiente.

System Settings (Configuración de sistema)

Server bc port - Este es un ajuste específico de servidor . Se recomiendan dejar el campo en su valor por
defecto. Si hay cualquier problema, póngase en contacto con su administrador de red.

<!-- p. 31 -->

Server port - Es un ajuste específico de servidor . Se recomienda dejar el campo en su valor por defecto. Si
hubiere problemas, contacte con el administrador de red.

Client BC port - Es un ajuste específico de servidor. Se recomienda dejar el campo en su valor por defecto. Si
hay problemas contacte con el administrador de red.

Project directory - Es el directorio para los archivos temporales para el RENDER CLIENT. (Por defecto, es el
directorio temp del la PC local).

Network directory - Esta es la ruta del directorio para los archivos temporales de los SERVIDORES. Nota: debe
haber este directorio en cada máquina del SERVIDOR.

Previous renderer

Aquí puede elegir el modo en el que se muestra la imagen anterior, dando el frame actual.

Unchanged – Deshace los cambios.

Cross - Pone a negro cada píxel diferente . Fields - Pone a negro cada línea distinta . Darken -Oscurece la
imagen entera.

Object Settings /Light Settings - Estos botones abren los cuadros de diálogo del objeto local y los ajustes de
iluminación.

(Configuración global) Global settings - (Configuración objeto) Object settings

VRay soporta Desenfoque de Movimiento, Iluminación Indirecta y Cáusticas. En el diálogo de propiedades de
objeto de VRAY (a la izquierda) hay una lista de los objetos de la escena, y a la derecha están sus propiedades.
Usted puede seleccionar múltiples objetos. Hay también una lista de juegos de selección de Max para configurar
la interfaz a conveniencia. Las propiedades son estas:

Object settings (Configuración de objeto)

Use default moblur simples (Usar Motion Blur por defecto - Con este checkbox seleccionado, el valor de
Geometry Samples será tomado de los parámetros de Motion blur.
Para una explicación sobre Geometry Simples, vea la sección de parámetros de Motion blur de Render
parameters.

Motion blur samples – Desde aquí puede ponerse el valor de Geometry Samples para los objetos seleccionados.
Esto anulará el valor de los parámetros de desenfoque Motion. Nota: este ajuste no tiene ningún efecto con el
ajuste Use default moblur simples seleccionado. Para una explicación sobre Geometry Simples, leer Motion
blur, sección Render parameters.

Generate GI (Generar GI) - Este ajuste controla si VRay enviará rebotes secundarios a los objetos
seleccionados.

Receive GI (Recibir GI) - Este ajuste controla el comportamiento de VRAY raytracing. Apagar esta opción impide
a VRay evaluar la GI cuando un rayo golpea los objetos seleccionados. (No hay ninguna Iluminación Indirecta
para los objetos seleccionados).

<!-- p. 32 -->

GI multiplier - Este es un multiplicador adicional para el GI. Este valor no anula los multiplicadores de Indirect
Illumination (Iluminación indirecta).

Generate caustics (Generar cáusticas) - Cuando este ajuste está seleccionado, los objetos seleccionados
refractarán la luz que viene de las fuentes de iluminación generadoras de cáusticas, para que se produzca el
efecto. Nota: para generar cáusticas, un objeto debe tener un material reflexivo o refractivo.

Receive caustics (Recibir cáusticas) - Cuando este ajuste está seleccionado los objetos seleccionados se harán
receptores de cáusticas. Cuando la luz es refractada por los objetos que generan cáusticas, sólo serán visibles si
se proyectan sobre receptores de cáusticas.

Caustics multiplier - Este valor es un multiplicador para las cáusticas generadas por el objeto seleccionado. Nota:
este valor no tiene ningún efecto a no ser que Generate caustics esté seleccionado.

Ajustes de luz (Light settings)

VRay soporta fuentes de iluminación de cáusticas. En el diálogo de propiedades de luz de VRay -a la izquierdahay una lista de fuentes de iluminación en las escenas, y a la derecha están los ajustes de luz. Se pueden
seleccionar múltiples fuentes de iluminación. Hay también una lista de opciones de Max para configurar la
interfaz. Las propiedades son:

Generate caustics (Generar cáusticas)- Cuando este ajuste está seleccionado las fuentes seleccionadas emitirán
una luz que será reflejada o refractada por los objetos de la escena produciendo el efecto de cáusticas. Nota:
para obtener el efecto de cáusticas debe poner el valor apropiado para el Caustics multiplier, y también algunos
objetos que generen cáusticas en la escena.

Caustic subdivs - Esta opción controla la cantidad de fotones que VRay enviará para calcular las cáusticas. Un
número mayor reduce la velocidad de cálculo del mapa de fotones.

Caustics multiplier - Este valor es un multiplicador para cáusticas generado por el objeto seleccionado. Nota:
este multiplicador es acumulativo -no anula el multiplicador en la sección parámetros de Caustics. El
multiplicador no tiene ningún efecto a no ser que Generate caustics esté seleccionado.

Material

VRayMtl parameters

Un material especial - el VRAYMTL - es suministrado con VRAY renderer. Éste tiene en cuenta físicamente una
mejor y correcta iluminación (distribución de energía) en la escena, es más rápido en la renderización, utiliza la
reflexión más conveniente. Dentro de VRAYMTL se pueden aplicar diferentes mapas de textura, controlar los
reflejos y refracciones, agregar rebotes y mapas de desplazamiento, obligar a cálculos de GI directos, y escoger
el BRDF para el material.
Los parámetros materiales están agrupados en las secciones siguientes:

Basic parameters (Parámetros básicos)

<!-- p. 33 -->

Diffuse - Es el color difuso del material. Puede anular este multiplicador con un mapa en la ranura de mapas de
refracción en la sección Texture maps.

Reflect - Un multiplicador de reflexión. Usted puede anular este multiplicador con un mapa en la ranura de mapas
de reflexión en la sección Texture maps.

Glossiness - Este valor muestra el lustre del material. Un valor de 0.0 produce reflexiones sumamente borrosas.
Un valor 1.0 apagará el lustre (VRay producirá reflexiones absolutamente agudas). Observe los aumentos de
lustre.

Subdivs - Controla el número de rayos enviados para evaluar el brillo de la reflexión. Cuando el lustre está
seleccionado a 1.0, el valor de subdivisiones no tiene ningún efecto (VRay no envía ningún rayo para evaluar el
lustre).

Fresnel reflection - Con esta opción de reflejos se actuará como auténticas reflexiones de cristal. Esto significa
que los reflejos desaparecerán cuando el ángulo entre el rayo y los accesos superficiales normales 0 grados (los
reflejos serán más visibles cuando los rayos sean casi paralelos a la superficie, y allí no habrá casi ningún reflejo
cuando los rayos sean perpendiculares a la superficie).

<!-- p. 34 -->

Max depth - Profundidad máxima de rayo. El mapa devolverá en negro los rayos de mayor profundidad.

Refract - Un multiplicador para la refracción. Se puede anular este multiplicador con un mapa en la ranura de
mapas de refracción en la sección Texture maps.

Glossiness - Este valor determina el lustre del material. Un valor de 0.0 produce refracciones sumamente
borrosas. Un valor de 1.0 apagará el lustre (VRay producirá refracciones absolutamente agudas).

Subdivs - Controla el número de rayos enviados para evaluar la refracción brillante. Cuando Glossiness está
seleccionado en 1.0 el valor Subdivs no tiene ningún efecto (VRay no envía ningún rayo para evaluar el lustre).

IOR - Este valor determina el índice de refracción para el material. Si usted recoge el valor apropiado puede
producir refracciones como si estuvieran causadas por el agua, el diamante, el cristal, etc. Una útil tabla de
valores de IOR se encuentra en la sección “Terminología” de este manual.

Max depth – Máxima profundidad del rayo. El mapa devolverá un color negro para los rayos de mayor
profundidad.

Translucent - Translucidez. Observe que sus luces deben tener sombras VRay para trabajar con translucidez.
Glossy debe estar también seleccionado. VRay usará Fog color para determinar la cantidad de luz que pasa por
el material bajo la superficie.

Thickness (Espesor)- Este valor determina el grosor de la capa translúcida. Cuando una profundidad de rayo
alcanza este valor VRay no envía el rayo por debajo de la superficie.

Light multiplier - Multiplicador de luz. Describe la cantidad de luz reflejada por el material por debajo de la
superficie.

Scatter coeff - Este valor controla la dirección de los rayos que se dispersan bajo la superficie del objeto
translúcido. Con un valor 0.0 los rayos se dispersarán por debajo de la superficie en todas las direcciones, y con
un valor 1.0 los rayos tendrán la misma dirección que el rayo inicial que atraviesa el objeto.

Fwd/bck coeff - Este valor controla cuántos de los rayos que se dispersan bajo la superficie del objeto translúcido
se propagarán adelante y hacia atrás en relación con el rayo inicial que atraviesa este objeto. Un valor medio de
1.0 hará que todos los rayos se propaguen adelante; un valor medio de 0.0 hará que todos los rayos se
propaguen hacia atrás, y un valor de 0.5, distribuirá igualmente los rayos en las direcciones delante y detrás.

Fog color - VRay le permite llenar los objetos de niebla de refractada. Esto es, el color de la niebla.

Fog multiplier –Multiplicador para Fog color. Los valores más bajos producen una niebla más transparente.

Options

Trace reflections - Conmuta los reflejos.

Trace refractions - Conmuta las refracciones.

Use irradiance map if On - Cuando use el mapa de irradiación para el GI, todavía puede querer usar al GI a
fuerza bruta para aplicar este material. Para lograrlo simplemente desactive la opción Use irradiance map if . Si
no el GI para los objetos con este material usará el mapa de irradiación. Nota: esta opción no tiene ningún efecto
a no ser que el GI esté conectado y ponga el mapa de Irradiación.

Trace diffuse & glossy together (Difuso y brillante juntos) - Cuando el lustre de reflexión/refracción está
conectado, VRay usa un número de rayos para componer el lustre y otro grupo de rayos para calcular el color
difuso. Cambie la opción Trace diffuse & glossy together, para obligar a VRAY a componer sólo un grupo de
rayos para el lustre como para difundir el componente del material. En este caso VRay realiza ciertas
valoraciones y recoge algunos rayos para componer el componente difuso y el resto para componer el lustre.

Double-sided (Doble cara) - Esta opción especifica si VRay asume toda la geometría como de doble cara.

Reflect on back side - Este checkbox fuerza a VRAY a componer reflexiones siempre (hasta sobre los lados
traseros de las caras). Nota: esta opción no tiene ningún efecto a no ser que Reflect on back side esté
seleccionado.

<!-- p. 35 -->

Cutoff - Esto es el valor de umbral para reflexiones/refracciones. Cuando los reflejos/refracciones contribuyen
poco al valor final de una muestra de imagen no serán compuestos. El umbral cutof pone la mínima contribución
para una reflexión/refracción.

Texture maps (Mapas de textura)

En esta sección del material VRay se pueden poner mapas de textura diferentes. Las ranuras de mapas de
textura disponibles son Diffuse, Reflect, Refract, Glossiness, Bump y Displace. En cada ranura de mapa de
textura hay un multiplicador, un checkbox y un botón. El multiplicador controla la fuerza del mapa de textura. El
checkbox cambia el mapa a off y on. El botón le permite escoger y\o cambiar el mapa de textura actualmente
seleccionado.

Diffuse - El mapa de textura en esta ranura controla el color difuso del material. Si necesita solamente un color
simple entonces deshabilite esta ranura y use el ajuste Difuso en la sección Parámetros Básicos.

Reflect - El mapa de textura en esta ranura controla el multiplicador de color de reflexión del material. Si necesita
solamente un multiplicador simple en color, deshabilite esta ranura y use el ajuste Reflejar en la sección
Parámetros Básicos.

Glossiness (Lustre)- El mapa de textura en esta ranura actúa como un multiplicador para la reflexión brillante.

Refract - El mapa de textura en esta ranura controla el multiplicador de color de refracción del material. Si
necesita solamente un multiplicador simple en color, incapacite esta ranura y use el ajuste Refractar en la
sección Parámetros Básicos en su lugar.

Glossiness - El mapa de textura de esta ranura actúa como un multiplicador para las refracciones brillantes.

Bump - Esta es la ranura donde va el golpe. Un mapa de golpe se usa para simular una superficie desigual sin
que en realidad se agregue más geometría a la escena.

Displace (Desplazamiento) - Es la ranura donde va el mapa de desplazamiento. Un mapa de desplazamiento se
usa para modelar la superficie para que aparezca áspera. A diferencia del golpe trazan un mapa del mapa de
desplazamiento, de hecho realiza la subdivisión de la superficie y el desplazamiento de vértices (geometría de
cambios). Es también generalmente más lento que un mapa de golpe.

Ejemplos de VRayMtl

Las imágenes siguientes muestran las reflexiones brillantes creadas con el material VRay. Diffuse está
seleccionado a RGB(0,0,255), Reflection está como RGB(230,230,230). Refractions en off. El BRDF está puesto
en Phong. El valor Subdivs para el lustre es 5. Antialiasing está puesto en Adaptive subdivision con Min rate =
1, Max rate = 2.

Fixed rate (Subdivs = 1), Glossiness = 1.0

<!-- p. 36 -->

Glossiness = 1.0

Glossiness = 0.8

Glossiness = 0.6

<!-- p. 37 -->

Glossiness = 0.6, Subdivs = 8

Glossiness = 0.4, Subdivs = 8

Las imágenes siguientes muestran el efecto de reflexiones Fresnel. Cuando los reflejos son puestos en Fresnel,
su fuerza depende del ángulo entre el rayo y la superficie reflexiva. Una reflexión no-fresnel no depende del
ángulo entre el rayo y la superficie reflexiva. Las dos imágenes fueron tomadas de una escena que consiste en
una fila de cajas rojas y dos cajas grises con la reflexión actuando como espejos.

Fresnel = off

<!-- p. 38 -->

Fresnel = on
Las imágenes siguientes muestran diferentes shaders soportados en el material VRay. El material aplicado a la
esfera está seleccionado a reflexión brillante para que la diferencia de shader sea más prominente. Ajustes:
Diffuse = RGB (128,128,128), Reflect = RGB(200,200,200), Glossiness = 0.4, Subdivs = 6.

BRDF = Phong

BRDF = Blinn

<!-- p. 39 -->

BRDF = Ward

Las imágenes siguientes muestran algunos ajustes de materiales VRay en cuanto a la translucidez. Para
producir translucidez tiene que conectar el GI, aplicar VRayShadow a la fuente de iluminación, hacer el material
del objeto deseado de refracción. La escena consiste en un hemisferio de refracción y una caja simple que cruza
la esfera. Estos son los ajustes comunes para las imágenes: Translucent = on, Thickness = 100, Light multiplier
\= RGB (255, 255, 255), Scatter coeff = 0.0, Fwd/bck coeff = 0.25, Fog color = RGB(185, 205, 198), Fog multiplier
\= 0.1.

Translucent = off

Fog multiplier = 0.3, Fwd/bck coeff = 0.0

<!-- p. 40 -->

Scatter coef = 0.0

Scatter coef = 1.0

Scatter coef = 1.0, Fwd/bck coef = 0.0

<!-- p. 41 -->

Scatter coef = 1.0, Fwd/bck = 1.0

Reflexión bidireccional

BRDF (Reflexión bidireccional)

Una de las características de las propiedades de los reflejos de una superficie es el uso de la función de
distribución de reflexión bidireccional (BRDF); una función que define la característica de reflexión espectral y
espacial de una superficie. VRay soporta los siguientes tipos de BRDF: Phong, BLinn y Ward.

Opciones

Options

Trace reflections - Conmuta los reflejos.

Trace refractions - Conmuta las refracciones.

Use irradiance map if On - Cuando use el mapa de irradiación para el GI, todavía puede querer usar al GI a
fuerza bruta para aplicar este material. Para lograrlo, simplemente desactive la opción Use irradiance map if . Si
no el GI para los objetos con este material usará el mapa de irradiación. Nota: esta opción no tiene ningún efecto
a no ser que el GI esté conectado y ponga el mapa de Irradiación.

Trace diffuse & glossy together (Difuso y brillante juntos) - Cuando el lustre de reflexión/refracción está
conectado, VRay usa un número de rayos para componer el lustre y otro grupo para calcular el color difuso.
Cambie la opción Trace diffuse & glossy together, para obligar a VRAY a componer sólo un grupo de rayos para
el lustre como para difundir el componente del material. En este caso VRay realiza ciertas valoraciones y recoge
algunos rayos para componer el componente difuso, y el resto para componer el lustre.

Double-sided (Doble cara) - Esta opción especifica si VRay asume toda la geometría como de doble cara.

Reflect on back side - Este checkbox fuerza a VRAY a componer reflexiones siempre (hasta sobre los lados
traseros de las caras). Nota: esta opción no tiene ningún efecto a no ser que Reflect on back side esté
seleccionado.

Cutoff - Este es el valor de umbral para reflexiones/refracciones. Cuando los reflejos/refracciones contribuyen
poco al valor final de una muestra de imagen, no serán compuestos. El umbral cutof pone la mínima contribución
para una reflexión/refracción.
Mapa de textura

Texture maps (Mapas de textura)

En esta sección del material VRay se pueden poner diferentes mapas de textura. Las ranuras de mapas de
textura disponibles son Diffuse, Reflect, Refract, Glossiness, Bump y Displace. En cada ranura de mapa de
textura hay un multiplicador, un checkbox y un botón. El multiplicador controla la fuerza del mapa de textura. El

<!-- p. 42 -->

checkbox cambia el mapa a off y on. El botón le permite escoger y\o cambiar el mapa de textura actualmente
seleccionado.

Diffuse - El mapa de textura en esta ranura controla el color difuso del material. Si necesita solamente un color
simple deshabilite esta ranura y use el ajuste Difuso de la sección Parámetros Básicos.

Reflect - El mapa de textura en esta ranura controla el multiplicador de color de reflexión de material. Si necesita
solamente un multiplicador simple en color, deshabilite esta ranura y use el ajuste Reflejar en la sección
Parámetros Básicos.

Glossiness (Lustre)- El mapa de textura en esta ranura actúa como un multiplicador para la reflexión brillante.

Refract - El mapa de textura en esta ranura controla el multiplicador de color de refracción del material. Si
necesita solamente un multiplicador simple en color, incapacite esta ranura y use el ajuste Refractar en la
sección Parámetros Básicos en su lugar.

Glossiness - El mapa de textura de esta ranura actúa como un multiplicador para las refracciones brillantes.

Bump - Esta es la ranura donde va el golpe. Un mapa de golpe se usa para simular una superficie desigual sin
que en realidad se agregue más geometría a la escena.

Displace (Desplazamiento) - Es la ranura donde va el mapa de desplazamiento. Un mapa de desplazamiento se
usa para modelar la superficie para que aparezca áspera. A diferencia del golpe traza un mapa de
desplazamiento; de hecho realiza la subdivisión de la superficie y el desplazamiento de vértices (geometría de
cambios). Es también más lento que un mapa de golpe.

Ejemplos de Material

Ejemplo de VRayMtl

Las imágenes siguientes muestran las reflexiones brillantes creadas con el material VRay. Diffuse está
seleccionado a RGB(0, 0,255), Reflection está como RGB(230, 230, 230). Refractions en off. BRDF está puesto
en Phong. El valor Subdivs para el lustre es 5. Antialiasing está puesto en Adaptive subdivision con Min rate =
1, Max rate = 2.

Fixed rate (Subdivs = 1), Glossiness = 1.0

<!-- p. 43 -->

Glossiness = 1.0

Glossiness = 0.8

Iluminación

VRayLight parameters

Esta sección describe los parámetros que controlan la fuente de iluminación VRayLight.

<!-- p. 44 -->

On - Cambia entre on y off

Double-sided (De doble cara)- Cuando VRayLight es la fuente de iluminación estos mandos nos ofrecen
opciones si la luz se emite desde ambos lados del plano. (Este campo no tiene efecto cuando la fuente de
iluminación Esfera está seleccionada).

Transparent - Este ajuste controla si la forma de la fuente VRayLight será visible en el render. Cuando esta
opción está apagada, a la fuente se le asigna el color actual de luz.

Ignore light normals (Ignorar luz normal) - Este checkbox le deja controlar el cómputo de luz cuando un rayo
golpea la fuente de iluminación. Para una luz físicamente real, debería quitarse; sin embargo cuando esta opción
está seleccionada los resultados pueden ser más lisos.

Normalize intensity (Intensidad normalizada)- Cuando está seleccionada el tamaño de la fuente de iluminación
no afectará a su intensidad. La intensidad será la misma como si el tamaño de la fuente de iluminación fuese 1.
Nota: antes de marcar la normalización de intensidad es útil poner el tamaño y el valor Mul a 1 para que
alcance la intensidad deseada. Entonces active Normalize intensity y cambie el tamaño de la fuente de
iluminación como desee. La intensidad quedará igual.

No decay (No descomponer) - Cuando esta opción está marcada VRayLight no se descompondrá con la
distancia. Sino que la luz se descompondrá con el cuadrado inverso de la distancia (funciona como la
descomposición de la luz en la vida real).

Store with irradiance map (Almacenar con mapa de irradiación) - Cuando esta opción está conectada y el cálculo
de GI seleccionado en Irradiance Map, VRAY calculará de nuevo los efectos del VRAYLIGHT y los almacenará
en el mapa de irradiación. El resultado es que el mapa de irradiación se calculará más despacio, pero la
renderización tardará menos tiempo. También puede guardar el mapa de irradiación y reutilizarlo más tarde.

Color - Color de la luz emitida por la fuente VRayLight.

Mult.- Un multiplicador de color de VRAYLIGHT.

No decay = on (Iluminación verdadera)

Tipo

Type

Plane - Cuando este tipo de fuente de iluminación está seleccionado VRayLight tiene la forma de un plano.

Sphere - Cuando este tipo de fuente de iluminación está seleccionado VRayLight tiene la forma de una esfera.
Size

U size - El tamaño U de la fuente de iluminación (si la fuente de iluminación de Esfera es el tamaño de U
seleccionado corresponde al radio de la esfera).

V size - El tamaño V de la fuente de iluminación (este campo no tiene ningún efecto cuando la fuente de
iluminación de Esfera está seleccionada).

W size - El tamaño W de la fuente de iluminación (este campo no tiene efectos cuando la fuente de iluminación
Esfera está seleccionada).

Sampling

Subdivs - Este valor controla el número de muestras que VRay toma para calcular la iluminación.

Low subdivs - Este valor controla el número de muestras que VRay toma para calcular la iluminación cuando low
accuracy computation esté considerado.

Degrade depth - Este valor denota la profundidad del rayo a la que VRay cambia low accuracy computations

Ejemplo de luces

<!-- p. 45 -->

VRayLight. Ejemplo

Las imágenes siguientes muestran cómo el radio de la fuente de iluminación de esfera afecta a las sombras del
objeto.

Normalize intensity está conectado para conservar la intensidad de luz en la escena, independientemente del
tamaño de la fuente de iluminación.

Transparent = off, Ignore light normals = off, Normalize intensity = on, No decay = off, Color (255,255,255),
Subdivs
\= 10, Low subdivs = 1, Degrade depth = 2, Sphere.

U size = 10 (En este caso, el radio de la esfera)

U size = 60 (En este caso, el radio de la esfera)
Las imágenes siguientes muestran la fuente de iluminación plane. Parámetros comunes:
Transparent = off, Ignore light normals = off, Normalize intensity = on, No decay = off, Color (255, 255, 255),
Subdivs = 10, Low subdivs = 1, Degrade depth = 2, Sphere.

<!-- p. 46 -->

U size = 10, V size = 1

U size = 1, V size = 40

Las imágenes siguientes se manifiestan el parámetro No decay. En el mundo verdadero las fuentes de
iluminación atenúan con el cuadrado inverso de la distancia. Sin embargo se puede desactivar la
descomposición de la luz para producir ciertos efectos en VRay. Los ajustes para la fuente de iluminación a la
izquierda son los mismos para ambas imágenes.

No decay = off (Iluminación falsa)

<!-- p. 47 -->

No decay = on (Iluminación verdadera)

Sombras

VRayShadow params (Parámetros de sombras)

VRayShadow soporta sombra de zona y se usa para la renderización correcta de translucidez en los mapas de
refracción VRayMap. También las sombras difuminadas realizadas con VRAYSHADOW son más rápidas de
calcular que las causados por luces de zona (Ver VRayLight).

Transparent shadows (Sombras transparentes) – Es útil cuando una sombra se produce por un objeto
transparente. Con esta opción VRay calculará las sombras independientemente de los parámetros de sombras
de Objeto de Max (Color, Mapa, etc.). Cuando necesite ajustar las Sombras de Objeto de Max, deshabilite
Transparent shadows.

Area shadow – Interruptor de Sombras de Zona.

Box - VRay calcula las sombras como si fueran producidas por una fuente de iluminación con la forma de una
caja.

Sphere - VRay calcula las sombras como si provinieran de una fuente de iluminación con la forma de una esfera.

U size (Tamaño de U) - El tamaño U de la fuente de iluminación que VRay tiene en cuenta cuando calcula las
sombras de área (si la fuente de iluminación Sphere es el U size seleccionado corresponde al radio de la esfera).

V size - El tamaño V de la fuente de iluminación que VRay tendrá en cuenta cuando calcule sombras de área
(este campo no tienen ningún efecto cuando la fuente de iluminación Esfera está seleccionada).

<!-- p. 48 -->

W size - El tamaño W de la fuente de iluminación VRay. (este campo no tienen efectos cuando la fuente de
iluminación Esfera está seleccionada).

Subdivs (Subdivisiones) - Este valor controla el número de muestras que VRay tomará para calcular las sombras
en un punto dado.

Low subdivs (Subdivisiones bajas) - Este valor controla el número de muestras que VRay tomará para calcular
las sombras en un punto dar cuando se considera el cómputo de exactitud bajo.

Degrade depth (Grado de profundidad)- Este valor muestra la profundidad del rayo en la que VRay cambia a
cómputos bajos de exactitud .

Bias (Tendencia) - La tendencia del rayo para calcular la sombra en un punto dado.

Ejemplo de Sombras

Ejemplo de sombras (VRayShadow)

Transparent shadows - off.

Transparent shadows - on.

<!-- p. 49 -->

Area shadow - on, Box (1, 1, 1), subdivs - 3, 9 s

Area shadow-on, Box(1, 70, 1), subdivs - 3, 10 s

Area shadow - on, Box (1, 70, 1), subdivs - 7, 28 s

<!-- p. 50 -->

Area shadow - on, Sphere (40), subdivs - 7, 29 s

Mapas

VRayMap parameters

Reflect - Cuando esta opción está seleccionada VRayMap actuará como mapa de reflexión. Entonces la sección
de Reflection params se usa para controlar los ajustes del mapa. (Cambiar los ajustes en Refraction params
no tendrá ningún efecto sobre el mapa).

Refract - Cuando se selecciona esta opción VRayMap actuará como un mapa de refracción. Entonces puede
usarse la sección Refraction params para controlar los ajustes del mapa (Cambiar los ajustes en Refraction
params no tendrá ningún efecto sobre el mapa).

Parámetros de reflexión

<!-- p. 51 -->

Reflection params (Parametros de reflexión)

Filter color - Multiplicador para los reflejos. No lo use en el material para poner fuerza de reflexiones. En su lugar
use este color con filtro. (De lo contrario el mapa de fotones no será correcto).

Reflect on back side - Este checkbox obliga a VRAY a componer siempre reflexiones. La utilización de esta
opción en conjunción con una refracción traza un mapa de aumentos.

Glossy – Conmuta las reflexiones brillantes/borrosas.

Glossiness - El lustre del material. Un valor de cero significa reflexiones sumamente borrosas. Valores más altos
hacen las reflexiones más agudas.

Subdivs - Controla el número de rayos enviados para evaluar la reflexión brillante.

Low subdivs - Número de rayos usados para evaluar reflexiones cuando VRay asume cómputos de exactitud
bajos (durante la prueba GI y cuando la profundidad del rayo alcanza el valor de Degrade depth).

Max depth - Profundidad máxima del rayo para el mapa. El mapa volverá a Exit color para los rayos de mayor
profundidad.

Degrade depth - Cuando la profundidad del rayo alcanza este valor VRay cambiará a cómputos de exactitud
bajos (Low subdivs el valor será usado como Subdivs).

Cutoff thresh - Los reflejos que contribuyen poco al valor final de una muestra de imagen no serán tenidos en
cuenta. El umbral pone la contribución mínima para componer una reflexión.

Exit color - Salir cuando la profundidad máxima del rayo haya sido alcanzada, pero la reflexión no haya sido
calculada aún.

Parámetros de refracción

Refraction params

Filter color - Multiplicador para la refracción. (Ver Filter color en la sección Reflection params)

Glossy – Interruptor de refracciones brillantes/borrosas.

Glossiness - (ver Glossiness en la sección Reflection params)

Subdivs - (ver Subdivs en la sección Reflection params)

Low subdivs - (ver Low subdivs en la sección Reflection params)

Translucent - Translucidez. (Las luces deben tener VRay shadows para ser traslúcidas).

Glossy -Debe estar conectado también. VRay usará Fog color para determinar la cantidad de luz que pasa por
debajo de la superficie del material.

Thickness - Este valor determina el contador de la capa translúcida. Cuando una profundidad de rayo alcanza
este valor VRays no atravesará más allá de esta distancia.

Light multiplier - Multiplicador para contribución de luz. Describe la cantidad de luz reflejada por el material
debajo de la superficie.

Scatter coeff - Este valor controla la dirección de los rayos que se dispersarán bajo la superficie del objeto
translúcido. Un valor medio de 0.0 hace que los rayos sub-superficiales se dispersen en todas las direcciones, y
un valor medio de 1.0 hace que tengan la misma dirección que el rayo inicial que atraviesa el objeto.

Fwd/bck coeff - Este valor controla cuántos de los rayos que se dispersan bajo la superficie del objeto translúcido
se van a propaga hacia delante y atrás en relación con el rayo inicial que atraviesa este objeto. Un valor medio
de 1.0 hace que todos los rayos se propaguen adelante, un valor medio de 0.0 hará que todos los rayos se
propaguen hacia atrás, y un valor 0.5 significa una distribución equitativa de rayos en las dos direcciones.

<!-- p. 52 -->

Fog color - VRay le permite llenar de niebla objetos de refracción. Esto es, pintar con niebla.

Fog multiplier - Multiplicador para Fog color. Los valores más bajos producen niebla más transparente.

Max Depth - Profundidad máxima del rayo para las refracciones. (Ver Max depth en la sección Reflection
params)
Degrade depth - (ver Degrade depth en la sección params)
Cutoff thresh - (ver Cutoff thresh en la sección Reflection params)
Exit color - (ver Exit color en la sección Reflection params)

Ejemplo mapa

VRayMap ejemplo

Ejemplo de reflexión. En las escenas siguientes hay un cono truncado colocado entre dos cajas paralelas. El
material de las cajas es un mapa de reflexión VRay.

Glossiness -10000, Subdivs - 2

Glossiness - 10000, Subdivs - 6

<!-- p. 53 -->

Glossiness - 1000, Subdivs - 5

Glossiness - 100, Subdivs – 5

Glossy-off, Max depth - 1

<!-- p. 54 -->

Glossy - off, Max depth - 5
Para ejemplos sobre la translucidez ver ejemplos de VRayMtl.

Tabla de Índices de refracción de materiales

MATERIAL ÍNDICE DE REFRACCIÓN (IOR)
\-----------------------------------------------------------------

Vacío 1.00000
Aire a STP 1.00029
Hielo 1.31
Agua a 20º C 1.33
Acetona 1.36
Alcohol etílico 1.36
Solución azucarada (30%) 1.38
Fluorita 1.433
Cuarzo fundido 1.46
Glicerina 1.473
Solución azucarada (80%) 1.49
Típica corona de cristal 1.52
Cristales de corona 1.52-1.62
Corona de espectáculo, C-1 1.523
Cloruro sódico (sal) 1.54
Poliestireno 1.55-1.59
Bisulfito Carbónico 1.63
Cristales de sílex 1.57-1.75
Cristal de sílex pesado 1.65
Sílex Extra denso, EDF-3 1.7200
Metileno yodado 1.74
Zafiro 1.77
Cristal de sílex más pesado 1.89
Diamante 2.417

De Reynolds
\--------------
Aluminio pulido 65 - 75 % Aire 1,0002926
Aluminio mate 55 - 75 % Alcohol 1,329
Acero 25 - 30 % Ambar 1,546
Acero inoxidable 80 - 90 % Aguamarina 1,577
Cobre muy pulido 60 - 70 % Diamante 2,417
Latón muy pulido 70 - 75 % Esmeralda 1,56
Roble claro pulido 25 - 35 % Cristal 1,51

<!-- p. 55 -->

Roble oscuro pulido 10 - 15 % Hidrógeno (gas) 1,000140
Papel blanco 70 - 80 % Hielo 1,309
Granito 20 - 25 % Metanol 1,329
Mármol pulido 30 - 70 % Nailon 1,53
Estuco claro 40 - 45 % Oxígeno (gas) 1,000276
Estuco oscuro 15 - 25 % Oxígeno (líquido) 1,221
Hormigón 20 - 30 % Plástico 1,460
Ladrillos 10 - 15 % Cuarzo 1,544
Cristal 5 - 10 % Rubí 1,760
Espejo de plata 80 - 88 % Ojo de tigre 1,544
Espero pulido 92 - 95 % Topacio 1,620
Azulejos blancos 75 - 80 % Agua (vapor) 1,000261
Blanco esmaltado 65 - 75 % Agua (20º C.) 1, 33335
Blanco lacado 80 - 85 % Circonita 1,800 - 1,960

Preguntas frecuentes

Preguntas frecuentes

Pregunta: Tengo un sistema de CPU dual, pero la renderización parece que no se realiza. ¿Qué pasa?

Respuesta: Compruebe la opción Multi en las preferencias de Max - Customize > Preferences > Rendering >
Multi- threading. Asegúrese de que está activada.
___________________________________________________________

Pregunta: Cuando doy un objeto particular con el VRay renderer aparecen rectángulos oscuros sobre el objeto.
Cuando doy el mismo objeto con las características por defecto de Max scanline renderer, los rectángulos
oscuros desaparecen.

Respuesta: Esto podría pasar si su objeto es una caja delgada con unsolapamiento de caras. Aumente la altura
o quite las caras de traslapo y los cuadrados deberían desaparecer.
___________________________________________________________

Pregunta: ¿Por qué no puedo afectar a la transparencia de un objeto? Por ejemplo una luz directa con
VRAYSHADOW y un objeto con material VRayMtl.

Respuesta: El material del VRAY no soporta la transparencias en el sentido de los materiales estándar de Max.
El único modo de hacer una sombra transparente con VRAYMTL es usando cáusticas.
___________________________________________________________

Pregunta: ¿Por qué cuándo uso un mapa de partículas trazadas con VRay las partículas no afrontan la cámara?

Respuesta: Los materiales con el juego de Mapa de Cara no funcionarán correctamente con VRay.
___________________________________________________________

Pregunta: ¿Por qué no puedo dar partículas cuando uso el desenfoque de movimiento del VRay?

Respuesta: Probablemente porque las partículas cambian su topología entre los frames. VRay no puede aplicar
el desenfoque de movimiento a los objetos que cambian el número de vértices/caras por la duración de los
frames de desenfoque de movimiento. En tales casos puede usar un desenfoque de movimiento post-render.
_______________________________________ ____________________

Pregunta: ¿VRay es compatible con VIZ 4?

Respuesta: VRay 1.0 no está garantizado para trabajar correctamente con VIZ Discret 4.
_______________________________________ ____________________

Pregunta: ¿Cómo puedo dar wireframe con VRay?

Respuesta: Puede usar la textura VRayEdges para hacerse algo similar (aunque no es exactamente lo mismo).

<!-- p. 56 -->

_______________________________________ ____________________

Pregunta: ¿Por qué la renderización de la misma escena que usa tamaños diferentes termina con tiempos de
renderización considerablemente diferentes?. Sin embargo no hay ninguna diferencia en la calidad.

Respuesta: No debería haber ninguna diferencia en la imagen final, cueste lo que cueste. Sin embargo, cada
zona requiere de algún tiempo. También, cuando usted usa filtros antialiasing, hay una frontera alrededor de
cada región que además tiene que ser dada para que los bordes se mezclen suavemente. Con el aumento de
tamaño de la región, este trabajo adicional lleva menos tiempo. Las zonas más pequeñas tienen más rápida la
actualización de pantalla -usted puede ver su imagen en progreso; las zonas ahorran memoria; las zonas
permiten el fácil “multiensartamiento” (y lo más importante) la Renderización Distribuida. La opción de
retardo/actualización es la mejor para el usuario. Se recomiendan los valores 16 a 64.
_________________________________________

Pregunta: ¿Por qué el mapa HDRI no tiene ningún efecto sobre el nivel especular de los objetos?

Respuesta: Con los materiales estándar de Max, el nivel especular es solamente un modo de simular la vista de
brillo de los objetos. Para un objeto verdadero el brillo tiene que ser reflexivo. El mismo solicita objetos dados en
VRay. Si quiere lograr una vista con una brillante iluminación con VRay, iluminación de objetos y mapas de
ambiente, tendrá que hacer objetos reflexivos.
_______________________________________ ____________________

Pregunta: ¿Por qué tengo las sombras producidas por el mapa de HDRI tan débiles?

Respuesta: Para sombras más agudas, consiga un mapa HDRI con una gama dinámica bastante alta.
_______________________________________ ____________________

Pregunta: ¿Por qué pierdo detalles cuándo doy un objeto con la parte de detalle que usa VRay el GI?

Respuesta: Aumente el valor de Max -por ejemplo a 0. También puede intentar reducir los umbrales normales y
de color. Además para hacer la GI más detallada puede: (a) reducir las muestras de interpolación, o (b) usar otro
método de interpolación - Delone triangulation no desenfocará la GI, solamente lo interpolará; sin embargo el
valor Mín/Máx todavía debe ser suficiente para capturar todos los detalles.
_______________________________________ ________________________________________

Pregunta: ¿Cómo uso el mapa HDRI con VRay para iluminar la escena?

Respuesta: Cárguelo en su mapa de ambiente si quiere mostrarlo de fondo, o en el panel render puede cargarlo
en la sección para anular el ambiente de Max para la Skyline.
_______________________________________ ____________________

Pregunta: ¿Cómo puedo poner el IOR cuando uso un material estándar con VRAYMAP para las refracciones?

Respuesta: Cambie el IOR del material (en el el parámetro Extended el material Standard).
___________________________________________________________

Pregunta: ¿Cómo hago para crear una sombra transparente en VRay? Uso un punto con la sombra VRay y
compruebo la sombra transparente, pero es negra.

Respuesta: En los parámetros de render de VRay, cambie a Cáusticas, y ponga el Multiplicador de cáusticas
(todavía en los parámetros de VRay) a algo así como 10000-100000.
_______________________________________ ____________________

Pregunta: ¿Cómo logro en VRay una subsuperficie que se disperse?

Respuesta: Hay dos modos. Use VRayMtl o un material estándar con VRAYMAP en la ranura de refracción. Si
usa VRAYMAP, en las opciones tendrá que cambiarlo a Refract y activar Translucency y Glossiness.
__________________________________________________________

Pregunta: ¿El filtro antialiasing afecta al mapa de irradiación? ¿Puedo calcular un mapa de irradiación con un
filtro y luego usarlo con otro?

Respuesta: No, el mapa de irradiación no se afecta por el filtro de antialiasing. De hecho si sólo tiene que
calcular un mapa de irradiación, puede renderizar sin filtro antialiasing. Usted puede agregar estos más tarde
para su renderización final.
_______________________________________ ____________________

<!-- p. 57 -->

Pregunta: ¿Puedo renderizar el mapa de irradiación en 400 x 400 y luego usarlo para un 800 x 800? ¿Cuál será
el efecto?

Respuesta: Sí, se puede hacer esto. El efecto final será como si usted hubiera calculado el mapa de irradiación
en un valor de prueba inferior.

Renderización compartida

Distributed rendering (Renderización Compartida)

Introducción

La Renderización Distribuida es una técnica para extender un trabajo dentro de un frame único a través de
muchos ordenadores en red. Hay diferentes maneras de hacer esto pero el concepto principal debe reducir las
veces dará dividiendo las diferentes partes de renderización y dar cada partes participantes diferentes del
trabajo. El camino más común para hacer esto es dividir el frame para entregarse en pequeñas zonas (cubos) y
asignar a cada máquina un número de ellos. Luego se combinan los resultados en la imagen final.

VRay organización

VRay soporta a doctor Esto divide el frame en cubos y los reparte entre los participantes de la Renderización
Distribuida. Esto se hace con el protocolo TCP/IP que es el protocolo estándar de Internet, y el protocolo más
común soportado por el hardware. VRay no necesita el archivo adicional o el directorio compartido. La dirección
de la distribución está dividida en Render Clients y Render Servers.

Render Clients

Render client es el ordenador que el usuario usa actualmente. Esto divide el frame sobre la renderización de
zonas y lo distribuye a través del Render Servers. Entonces dirige el proceso de renderización supervisando que
los servidores obtengan la información para seguir trabajando, y recupera los resultados procesados. En el
Render Cliente hay una interfaz para manejar los Servidores -para incluirlos o excluirlos de la renderización- así
como para controlar su estado. Cuando un cubo está renderizado Render Client recoge el resultado, lo muestra y
le envía otro cubo al Servidor (si hay más para ser procesadas).

Render Servers

Render server es el ordenador que recibe una parte del frame -el cubo- lo distribuye y envía al cliente. Su estado
es supervisado y controlado por el Render Client.

Instalación. Notas

El paquete de Renderización Distribuida consiste en:

\- VRayNet40.dlu - una utilidad que combina al Render Servidor y el Render Client y agrega la interfaz en la
pestaña UTILIDADES del panel de Comandos de Max para el control de los servidores. (Ver: VRaySystem-
\>Distributed rendering )

\- VRMaxSpawn.exe - Un programa que comienza 3DS Max en el modo " SERVIDOR" (más notas sobre este
modo pueden leerse en la documentación original de 3DS Max). Hay que tener cuidado por si Max se bloquea
para reiniciarlo inmediatamente otra vez. Si prefiere cerrar Max en la máquina del servidor, no cierre el proceso
de Max, solamente cierra el programa VRMaxSpawn.exe.

\- VRayDummy.max - un archivo de Max (vacío) que se carga al comienzo de todo Server Render.

Directorios

VRayNet40.dlu, como cualquier otro plugin debería colocarse en algún sitio de su directorio estándar de plugins
para que Max pueda encontrarlo y cargarlo. VRMaxSpawn.exe debería estar colocado en el directorio raíz de
Max. Este es el directorio donde se encuentra el archivo 3dsmax.exe. VRayDummy.max actualmente debe ser
también colocado en el directorio raíz de Max. Hay 2 directorios adicionales que se usan para archivos
temporales de la Renderización Distribuida: PROYECTOS y los directorios de RED.

<!-- p. 58 -->

Aquéllos se usan para el almacenaje temporal de archivos. Pueden ser seleccionados desde la interfaz de
VRayNet, (ambos en Render rollup) así como en la utilidad rollup de VRAYNET.DLU. Es muy importante que
estos directorios estén asignados correctamente ya que la mayor parte de las acciones realizadas por DOCTOR
VRay se registran en archivos locales localizados en el directorio C:\
Usted debe tener permiso para escribir y crear allí archivos (C:\).

Cómo probar

Primero principio con las pruebas del RENDER SERVER. Ejecute el programa VRMaxSpawn.exe. Este intentará
encontrar automáticamente el archivo 3dsmax.exe y lo iniciará en modo de servidor. Usted debería ocultar 3DS
Max minimizándolo en la barra de tareas. Debería tener el título "$0_SRV_MAXSCENE.MAX". Si Max se queda
allí sin cerrar, usted tiene el funcionamiento de parte del Servidor.

Ahora prueba el RENDER CLIENT. Abra a su Max normalmente. Abra una escena que gustaría renderizar.
Escoja VRay como motor de render y asegúrese de que ha comprobado la activación de Renderización
Distribuida, en la sección SISTEM VRAY. Presione el botón de ajustes en la sección de Renderización
Distribuida. Después de que se asegure de que tiene al menos un RENDER SERVER funcionando en algún sitio
de la red LOCAL - presione el botón BÚSQUEDA en la sección de Servidores VRay. Después de un tiempo de
aproximadamente 2 segundos debería ver la lista de VRAY puesta al día con todos los servidores encontrados
en la red.

Si quiere agregar a un servidor que no ha podido ser encontrado, simplemente pulse "agregar al servidor" e
introduzca la dirección IP con la que el servidor VRay puede encontrarlo. Ahora pulse derecho en la lista y
autorice. Puede inhabilitarlo más tarde. Actualmente VRay soporta la prioridad de proceso. Esta es realmente
práctica cuando la misma caja es usada por otros objetivos y no sería cortés asignar todo el tiempo de la CPU.
Evite el caso extremo- REALTIME. Usted puede terminar por reanudar su caja como esto no será capaz de
hacer algo, incluyendo el interfaz de usuario, el disco, etc.

Ahora que tiene la ventana de ajustes le abrieron podría querer mantenerla abierta cuando muestra la
información útil sobre el estado de servidores. El icono a la izquierda muestra los estados OFF, IDLE, BUSY y
FAILED. Más información sobre lo que hace actualmente el servidor está disponible en la sección de estado de
la lista de servidores VRay. Ahora está listo para rodar. Pulse el botón RENDER y el interruptor de la ventana de
ajustes para ver qué pasa. La interfaz de Max no está bloqueada. Esto es -usted será capaz de cambiar
ventanas y diálogos. Evite deshabilitar o permitir servidores durante el proceso de renderización. Primero cancele
el actual render, espere a que todos los servidores cambien al estado IDLE (el icono verde).

Para autorizar a su máquina local como un servidor de renderización -también debe iniciar VRMaxSPawn en la
zona. Esto puede ser un problema con escenas realmente grandes y prometemos arreglarlo en la próxima
versión (1.1).

Si algo falla...

Prácticamente cada acción tomada por DOCTOR VRay está registrada. Usted puede encontrar todos los
archivos en el directorio de C:\ y averiguar qué ha fallado. Si no entiende el problema puede comprimir y
enviarnos los archivos para analizarlos y eventualmente intentar ayudarle a: VRay @ chaoticdimension.com

Si falla cualquiera de sus MAX SERVERS debería conseguir un informe de qué ha fallado y
MAXCLIENTSHOULD local intenta recuperarse. Si falla - debería iniciar de nuevo su MAX CLIENT. Sin embargo,
no tiene que comenzar de nuevo con todos los Servidores. A veces si un Render Server falla - 3dsmax.exe
todavía funciona aunque no se vea su interfaz. Este puede ser un gran problema cuando prácticamente no
funciona mientras VRMaxSpawner todavía piensa que está en activo. En este caso debería ejecutar el
ADMINISTRADOR DE TAREAS y apagar 3dsmax.exe.

Nota: Cada MAX SERVER debe tener todos los plugins y mapas de textura cargados en sus directorios
apropiados para que la escena que usted envía no haga que se aborten. Por ejemplo teniendo un plugin
PHOENIX usado en la escena causará un fracaso del servidor en cualquiera de los Servidores de Max que no
tengan el plugin PHOENIX instalado. Si ha trazado un mapa de su objeto con un archivo llamado
JUNGLEMAP.JPG y no tiene el mapa en los directorios BITMAPS de la instalación del Servidor de Max - logrará
el cubo entregado a aquella máquina como si el mapa estuviera apagado.

Nota: la renderización de una secuencia de animación entera en Renderización Distribuida es actualmente
bastante ineficaz.

Nota: la renderización de escenas con mapas de irradiación no puede ser muy productiva como cuando los
cálculos de mapa de irradiación no han sido distribuidos. Cada uno de los render del servidor calcula su propio
mapa de irradiación, y no puede ser muy eficiente cuando el tiempo de renderización en sí mismo puede llevar

<!-- p. 59 -->

mucho menos tiempo que la preparación del mapa de irradiación. Intentaremos mejorar este comportamiento en
el futuro.

Nota: Evite pulsar ABORT inmediatamente después de que haya comenzado la Renderización Distribuida. A
veces Max se cuelga.

Nota: No se debe pulsar PAUSA en absoluto. Este es un problema de Max y no pensamos que seamos
capaces de poner en práctica la opción PAUSA en la Renderización Distribuida.

Terminología

Terminología:

Analytic sampling. (Prueba analítica)

Esta es una de las técnicas del VRay para el desenfoque de movimiento. En vez de tomar un número de muestras de tiempo,
el método analítico desenfoca los triángulos móviles perfectamente. Considerará todos los triángulos que cruza un rayo dado
durante un intervalo de tiempo dado. Tenga presente que debido a su "perfección" este método será sumamente lento, sobre
todo con escenas con movimiento rápido. (Ver también: Motion blur parameters, Motion blur, Quasi Monte Carlo sampling)

Antialiasing (Prueba de imagen)

Antialiasing es una técnica especial para producir imágenes de bordes lisos, altos de contraste y pequeños detalles en
materiales y objetos. VRay logra el antialiasing tomando muestras de imagen adicionales donde sea necesario. Para
determinar si son necesarias más muestras, VRay compara las diferencias en los colores (y\o en otras propiedades) de las
muestras de imagen vecinas. Esta comparación puede realizarse de varios modos. VRay soporta antialiasing fixed, simple 2
level y adaptive (Ver también: Image samplers parameters, G-Buffer, G-Buffer Antialiasing)

Area lights (Luz de zona)

La luz de área es un término que describe una fuente de iluminación de no-punto. Estos tipos de fuentes de iluminación
producen sombras de zona. La renderización VRay lo hace con VRayLight. (Ver también: VRay Light parameters, Sombras de
área)

Area shadows (Soft shadows -Sombras suaves)

Las sombras de área son sombras veladas (o sombras con bordes velados) causadas por fuentes de iluminación de no-punto
(luces de Área). VRay es capaz de producir el efecto de sombras de área con VRayShadow o con luces de área. (Ver
también: VRayShadow parameters, Area lights)

BRDF (Función de distribución de reflactancia bidireccional)

Una de las propiedades características de la reflexión de una superficie es el uso de distribución de reflexión bidireccional
(BRDF), una función que define la característica de reflexión espectral y espacial de una superficie. VRay soporta los tipos
BRDF siguientes: Phong, Blinn, Ward. (Ver también: VRayMtl)

BSP (Árbol, Espacio Binario divisor)

BSP es una estructura de datos especial para organizar la geometría de la escena para los cruces de rayos. (Cruzar un rayo
con los triángulos en la escena es la tarea más frecuente realizada por un trazador). Actualmente VRay implementa dos tipos
de Árbol BSP. Son static BSP Tree para escenas sin motion blur y BSP Tree para motion blur. (Ver también: Motion Blur -
Desenfoque de movimiento)

Bucket Region, (Zona de cubo)- (Rendering region)

Un cubo es una parte rectangular del frame que se muestra separada de otros cubos. La división de un frame en la
renderización de zonas tiene en cuenta la utilización óptima de recursos (CPUs, PCs, memoria…). También tiene en cuenta
la Renderización Distribuida. (Ver: Distributed rendering)

Caustics (Radiosidad)

Es el efecto de la luz refractada por un objeto no-opaco que golpea sobre una superficie (difusa). (Ver también: Caustics
parameters)

Degrade depth (Profundidad)

En la renderización VRay arroja muchos rayos. La profundidad del rayo denota el número de golpes que un rayo particular ha
producido mientras se propaga en la escena. Por lo general cuanto mayor es la profundidad de un rayo, más pequeño es su
efecto sobre la imagen final. Cuando la profundidad de un rayo alcanza el valor Degrade depth VRay asume que no afectará

<!-- p. 60 -->

mucho a la imagen final y usa cómputos de exactitud bajos. Vea que VRay por lo general puede determinar bastante
satisfactoriamente cuántos rayos se necesitan para calcular un cierto valor; por tanto normalmente usted no tendrá que
ajustar la profundidad. (Ver también: cómputos de exactitud bajos)

Depth of field (Profundidad de campo) - (DOF)

La profundidad de campo es el efecto de tener un punto particular en la escena para que aparezca enfocado (agudo) y el
resto desenfocado (borroso), según las propiedades del obturador de la cámara y la distancia. Es similar al funcionamiento
real de las cámaras; este efecto es sobre todo útil para producir imágenes fotorrealistas. (Ver también: DOF parameters,
Camera parameters)

Distributed rendering - (Renderización Distribuida) - (DR)

La Renderización Distribuida es una técnica para la utilización de todos los recursos computacionales disponibles (todas las
CPUs, todas las máquinas en un LAN, etc.). DOCTOR divide el frame actualmente procesado a la renderización por zonas y
mantiene todas las CPUs en red LAN ocupadas en la renderización. Sin embargo para secuencias de animación, debería
usar la red estándar de Max

G-Buffer

Este término describe la colección de los distintos datos generados durante la renderización de la imagen. Estos podrían ser
valores Z, IDs de material, de objetos, colores, etc. Es muy útil para realizar el procesamiento de imágenes de post-render
(Ver también: G-Buffer parameters, Antialiasing, Image samplers parameters)

G-Buffer Antialiasing

VRay es capaz de hacer un antialiasing de una imagen dada basada en las diferencias de uno o de varios canales G-buffer.
(Ver también: Antialiasing, Image sampler parameters, G-Buffer)

HDRI (Imagen de Alta Gama Dinámica)

Una Imagen de Gama Alta Dinámica es una imagen que contiene colores dinámicos de alta gama (con componentes que
exceden la gama de 0.0-1.0, o 0-255). Este tipo de imágenes, a menudo se usa como mapa de ambiente para iluminar la
escena con luz natural.

Índice de Refracción (IOR)
El índice de refracción se define como la velocidad de la luz en el vacío, dividido por la velocidad de la luz en un medio dado.
IOR = C/V, donde V es la velocidad específica de la luz para los diferentes medios. Para realizar un material con un IOR
específico tiene que poner el valor Index of refraction en los materiales estándar de Max, en la sección Extended parameters.

Indirect Illumination (Global lighting, Global Illumination) - Iluminación Indirecta (Iluminación Global)

En el mundo verdadero, cuando la partícula de un rayo de luz golpea un objeto se divide en múltiples rayos reflejados en
todas las direcciones con diferente intensidad. Estos rayos pueden rebotar con otros objetos y producir más rayos, etcétera.
Este proceso, repetido muchas veces, genera la “Iluminación Global”. (Ver también: Indirect Illumination parameters,

Irradiance map (Mapa de irradiación)

La iluminación Indirecta en VRay generalmente se logra con muestras de GI. El mapa de irradiación es un escondrijo especial
donde VRay guarda las muestras GI precalculadas. Durante la renderización se tratan cuando VRay necesita una muestra de
GI particular la calcula interpolando las muestras de GI precalculadas próximas almacenadas en el mapa de irradiación. Una
vez calculado, el mapa de Irradiación puede ser guardado en un archivo y reutilizado en renderizaciones posteriores. Esto
puede ser útil sobre todo para la cámara volante -para animaciones. Las muestras para VRayLight también pueden estar
almacenadas en el mapa de irradiación. (Ver también: Parámetros de iluminación indirecta, Iluminación indirecta, Área de
luces, Área de sombras)

Low accuracy computations (Cómputos de exactitud bajos)

En ciertos casos VRay no tendrá que calcular con absoluta precisión la contribución de un rayo a la imagen final. VRay
entonces trabajará más rápido, pero será menos exacto en el cómputo y tomará menos muestras. Esto produce resultados
ligeramente más ruidosos, pero disminuirá el tiempo de renderización. Los usuarios pueden controlar el grado de
optimización cuando VRay cambia a cómputos bajos de exactitud cambiando los valores de Degrade depth. (Ver también:
Degrade depth, Low subdivs)

(Quasi) Monte Carlo sampling

La prueba de Monte Carlo es un método para el cómputo numérico de integrales de funciones evaluando estas funciones en
un número de puntos arbitrarios. La prueba de Cuasi Monte Carlo es una modificación de este método, que en vez de puntos
generados al azar usa puntos que forman una secuencia de discrepancia baja, que son distribuidos más uniformemente que
los puramente arbitrarios. Este es el método usado por VRay para evaluar cosas complejas como la iluminación global,
reflexiones desenfocadas, profundidad de campo, desenfoque de movimiento y antialiasing.

Motion Blur (Desenfoque de movimiento)

<!-- p. 61 -->

Este efecto se observa cuando se mira algún objeto en rápido movimiento. El movimiento es tan rápido que uno no puede
enfocar el objeto, y su imagen aparece velada ante el espectador. (Ver también: Parámetros de MotionBlur, Muestra analítica,
Muestra de Monte Carlo)

Photon, Photon map (Mapa de fotones)

Esta es una simulación de los auténticos fotones (un fotón es una partícula de luz). Para producir efectos de cáustica VRay
utiliza cierta cantidad de fotones que provienen de las fuentes de iluminación. Los resultados son almacenados en un mapa
de fotones y usados durante el proceso de renderización para que los efectos cáusticos, sumamente realistas, se
reproduzcan.

Reflections (Reflejos)

Como trazador de rayos avanzado VRay soporta reflexiones exactas. También las reflexiones brillantes . (Ver también:
VRayMap parameters, VRayMtl parameters, Glossiness, Reflections, VRayMtl)

Refractions (Refracciones)

La refracción es el doblamiento de una onda de luz cuando entra en un medio donde la velocidad es diferente. La refracción
cuando pasa de un medio rápido a un medio lento, fuerza al rayo hacia el límite entre los dos medios. Como trazador
avanzado VRay soporta refracciones físicamente exactas. VRay también maneja refracciones brillantes (Ver también:
VRayMap parameters, VRayMtl parameters, IOR, Translucency, Glossiness, Reflections, VRayMtl)

Subdivs

En VRay subdivs es una medida de cuántos rayos (muestras) calculará VRay para un cierto valor. El número de muestras es
el valor square de las subdivisiones.

Translucency (Transparencia)

La translucidez es un término que describe la interacción de la luz con un medio no opaco (la cera, el mármol, la piel etc.).
VRay soporta un modelo de translucidez simple, que sin embargo puede producir resultados bastante naturales. (Ver
también: VRayMap parametros, VRayMtl parametros, Refracciones)

<!-- p. 62 -->

Tutorial de Endora

Guía de Endora

<!-- p. 63 -->

Contenido

Image sampler (Antialisanig)

Indirect ilumination (GI)

Irradiance map

Global photon map

Cuasi-Monte Carlo GI

Lightmap

Caustics

Enviroment

QMC sampler

G-buffer/color mapping

Camera

Default displacement

System

VRayShadowsParams

Galería de imágenes
Image sampler (Antialiasing

Image Sampler (Antialiasing)

Fixed rate: Test simple de imagen que nos da un numero fijo de muestras para cada píxel. Funciona mejor en
escenas con texturas muy detalladas.

<!-- p. 64 -->

Subdivs: Nos determina el número de muestras por píxel.

Adaptive QMC: Nos da muy buena calidad y rebaja los tiempos de fix rate.
Min subdivs: Controla el número mínimo de muestras por pixel.
Max subdivs: Controla el número máximo de muestras por pixel.

Adaptive subdivisión: Realiza menos de una muestra por pixel, lo que nos permitirá igualar la calidad de
alisado en comparación con adaptive QMC pero tardando menos tiempo en realizarlo.
Min rate: Controla el número mínimo de muestras por pixel, tomando como valor cero una muestra por pixel.
Min rate: Controla el número máximo de muestras por pixel.
Threshold: Nos define el umbral usado para realizar el muestreo. Cuanto menor sea el valor de éste, mayor será
la calidad del alisado.Rand: Nos permite un mejor alisado, acercando las muestras que rodean a cada pixel,

<!-- p. 65 -->

definiéndolo en mayor medida.

Antialiasing filter: Nos permite controlar el alisado de los objetos en la escena.
Entre todos los filtros disponibles el Catmull-rom nos servirá para la mayor parte de las escenas, realzando mejor
las lineas.

Indirect ilumination

Gi caustics: Reflective-refractive, activa o desactiva las reflexiones y refracciones cáusticas en la escena.
Primary bounces: Multiplier: Nos determina el valor para el motor de iluminación que seleccionemos (GI engine)
en el primer rebote de la luz.
(Estos motores serán detallados mas adelante).
GI engine:

.

Secondary bounces: Multiplier: Nos determina el valor para el motor de iluminación que seleccionemos (GI
engine) en el segundo rebote de la luz.
GI engine:

Post-processing: Saturation: Regula la cantidad de saturación en la escena.
Contrast: Regula la cantidad de contraste en la escena.
Contrast base: Aumentando su valor reduciremos la exposición del blanco.

Irradiance map

<!-- p. 66 -->

Built-in presets: Nos permite seleccionar 7 valores preestablecidos y uno personalizable en current preset,lo que
nos servirá para poder regular la calidad del render.

Basic parameters:
Min rate: Cantidad mínima de muestras por pixel.
El valor cero significaría una muestra por cada pixel, mucha calidad pero tiempos de render largos.
Los valores positivos casi nunca suelen usarse, ya que sería igual que utilizar "computación directa", lo que
prolongaría en exceso el tiempo de cálculo del render.
Los valores negativos son los apropiados, pero cuanto menores sean estos mayor perdida tendremos en calidad
y menor será el tiempo de calculo del render. Estos datos también son aplicables a Max rate.

Max rate: Cantidad máxima de muestras por pixel. (Cuanto mas próximos estén los valores a cero mas calidad
obtendremos en el render)

Tomamos como ejemplo el cálculo del mapa de irradiancia a -3, 0 para una resolución de 800x600 pixels.

Prepass1: (800/2/2/2=100 y 600/2/2/2=75) GI calculada para una resolución de 100x75 pixels.
Prepass2: (800/2/2=200 y 600/2/2=150) GI calculada para una resolución de 200x150 pixels.
Prepass3: (800/2=400 y 600/2=300) GI calculada para una resolución de 400x300 pixels.
Prepass4: GI calculada para una resolución de 800x600 pixels.

Si queremos obtener el mismo mapa de irradiancia, pero para una resolución de 1600x1200, usaremos los
valores -4, -1
Prepass1: (1600/2/2/2/2=100 y 1200/2/2/2/2=75) GI calculada para una resolución de 100x75 pixels.
Prepass2: (1600/2/2/2=200 y 1200/2/2/2=150) GI calculada para una resolución de 200x150 pixels
Prepass3: (1600/2/2=400 y 1200/2/2=300) GI calculada para una resolución de 400x300 pixels.
Prepass4: (1600/2=800 y 1200/2=600) GI calculada para una resolución de 800x600 pixels.

Hsph subdivs: Cantidad de muestras que van a ser computadas por la iluminación global. Determina el número
de rayos que serán lanzados en un punto dado.

HSphere subdivs: 1 = 1 ray
HSphere subdivs: 2 = 4 rays
HSphere subdivs: 3 = 9 rays
HSphere subdivs: 4 = 16 rays
HSphere subdivs: 5 = 25 rays
HSphere subdivs: 6 = 36 rays
HSphere subdivs: 7 = 49 rays

<!-- p. 67 -->

HSphere subdivs: 8 = 64 rays
HSphere subdivs: 9 = (9x9=81) 81 rays, etc....

A mayor cantidad de muestras más calidad general para el render.
Tened en cuenta que las hsph subdivs e interp samples deben de estar equilibrados.
Incrementado el hpsh reduciremos un poco las interp ya que no serán necesarias tantas muestras para el
calculo;
así evitaremos artefactos (manchas) en el render.
Ocurriría a la inversa si aumentamos las interpolaciones. En este caso no serian necesarias tantas hpsh subdiv.
Un ejemplo que podamos usar por norma general y que nos da suficiente calidad seria hpsh subdivs: 50 e interp.
samples: 20.

Interp samples: Cantidad de muestras que son almacenadas por el mapa de irradiación

Clr thresh: Añade más muestras en zonas de cambio de iluminación más acusadas, según la diferencia de color
de dos muestras cercanas o el ángulo que formen entre ellas. Cuanto menor sea el valor de éste, más calidad
nos dará en el render. Un valor intermedio que nos dé una calidad aceptable puede ser 0,3.

Nrm thresh: Añade mas muestras en zonas de cambio de iluminación menos acusadas, según la diferencia de
color de dos muestras cercanas o el ángulo que formen entre ellas.Cuanto menor sea el valor de éste, más
calidad nos dará en el render. Un valor intermedio que nos de una calidad aceptable puede ser 0,3.

Dist thresh: Es muy útil para zonas de contacto entre objetos, aumentando o disminuyendo la cantidad de
muestras entre esas partes más próximas y que necesitan ser mas definidas. El ejemplo mas claro son las
esquinas. Este valor funciona al contrario que Nrm y Clr thresh. Cuanto mayor sea, mejor será la definición de
éste y más muestras tomará
en esas zonas.

Show calc. phase: Nos va mostrando las fases previas del cálculo del mapa de irradiancia con respecto a los
valores dados en min-max rate.

Show direct light: Visiona un previo de las muestras que serán tomadas para el cálculo del mapa en las luces
directas.

Show samples: Visiona las muestras que serán tomadas para el cálculo del mapa de irradiación.

<!-- p. 68 -->

Advance options:
Interpolation type: Controla las diferentes formas de interpolación de las muestras que se calculan en el mapa de
irradiancia. Podemos dejar por defecto least squares fit.

Sample lookup: Proceso por el que van a ser tratadas las muestras en la interpolación. Por defecto densitybased. (Es el que mas calidad nos dará).

Calc. pass interpolation samples:
Multipass:
Randomize samples:
Check sample visibility:

Mode:
Bucket mode: Divide la imagen en regiones o cubos, que serán visibles en el proceso de renderizado.

Single frame: El mapa de irradiación será calculado por cada frame independientemente.

Miltiframe incremental: Reconoce si existen nuevas muestras con respecto al mapa anterior calculado,
añadiendo las que sean necesarias. (Muy útil en animaciones).

From file: Guarda el mapa de irradiación de cada muestra.

Add to current map: Similar a multiframe incremental, calcula los frames nuevos y los añade al mapa anterior.

Incremental add to current map: Añade las nuevas muestras calculadas en add to current map.

On render end: Nos da la posibilidad de guardar el mapa de irradiancia en un archivo para poder utilizarlo
posteriormente sin tener que volver a calcularlo. Es muy importante saber que el mapa guardado solo sirve para
una única resolución del render. Si variamos ésta, el mapa ya no nos servirá y habrá que volver a calcularlo.

En la pestaña auto save pondremos la ruta de nuestro disco duro en donde queramos guardar el mapa.
Si activamos switch to save map la pestaña auto save será desactivada tras finalizar el render, impidiendo que el
mapa guardado sea borrado al efectuar un nuevo render.
Global photon map

<!-- p. 69 -->

(Esta pestaña únicamente es visible si activamos photon map en primary o secondary bounces).
Bounces: Número de rebotes que será usado por el mapa de photons.

Auto search dist: Calcula automáticamente el radio de uso de los photons en base a la precisión que tengamos
asignada en max density.

Search dist: Con este parámetro asignamos manualmente el radio de actuación de los fotones en un punto.

Max photons: Cantidad máxima de photons que serán usados con respecto al valor dado en search dist.(A mayor
valor, mejor precisión en la iluminación).

Multiplier: Intensidad lumínica de los photons. Este parámetro actúa similar al multiplicador normal de las luces.

Max density: Nos permite especificar la exactitud del mapa de photons en un punto.
Este parámetro varía en función de la escala de la escena; una unidad equivaldría a 1cm, 1 mm, 1m, etc. Este
dato junto con search dist son importantísimos, ya que no es igual la precisión de la iluminación con radio de 1
metro,
que con radio de 1 milímetro.

En este esquema podemos apreciar cómo funcionan los photons.
La linea azul nos marca el radio (search dist) que nos delimita la zona de acción de los fotones.
Los círculos verdes son los photons (max photons).
El circulo rojo nos indica la precisión con la cual será calculada la iluminación en ese punto especifico dado por el
valor de max density.

La información lumínica almacenada por los photons que se encuentran dentro del radio especificado por la zona

azul es absorbida por la zona roja permitiendo hacer el cálculo de la cantidad de luz en ese punto especifico.

<!-- p. 70 -->

(Estas pruebas están realizadas con un radio de 150, 100 y 50 milímetros. Si la escala fuese en metros las
manchas mostradas tendrían un radio de 150, 100 y 50 metros respectivamente, obteniendo muy poca precisión
en el mapa de photons).

El uso de max density y search dist se basa en una proporción fundamental; 1 es a 5. Si ponemos por ejemplo
un valor de 10 en max density, tendremos que situar el search dist a 50. Si el valor es de 30, el search dist será
de 150, y así consecutivamente.

Covert to irradiance map:
Interp. samples:
Convex hull area estimate:

Store direct light: Activando esta opción el mapa de fotones nos permitirá calcular tanto la iluminación directa
como indirecta (luces de area), bajando los tiempos de render en escenas con varias luces. Si la desactivamos,
la luz directa será calculada a fuerza bruta.

Retrace thresold:
Retrace bounces:
Mode: New map:
From file:
On render end: Don´t delete:
Auto save:
Switch to saved map:

Cuaso-Monte Carlo GI

<!-- p. 71 -->

(Esta pestaña únicamente es visible si activamos Quasi-Monte Carlo en primary y secondary bounces).
Subdivs: Cantidad de muestras que serán computadas por la iluminación global.

Secondary bounces: Número de rebotes secundarios que efectúa la luz.

Lightmap

Calculation parameters: Subdivs: Cantidad de muestras que serán computadas por los mapas de luz.

Sample size:
Scale:

<!-- p. 72 -->

Store direct light:
Show calc. phase:
Reconstruction parameters: Pre-filter:
Filter:
Interp. samples:

Caustics

Multiplier: Cantidad de luz que es reflejada y refractada. Este valor nos permite aumentar el efecto cáustico de la
luz sin necesidad de tener que incrementar la intensidad de las luces.

(También tenemos la posibilidad de controlar la intensidad cáustica dentro del panel Vray light properties,
aumentando el valor de caustic multiplier).

<!-- p. 73 -->

Caustic subdivs.: Cantidad de muestras que van a ser computadas para la iluminación cáustica.

Search dist: Funciona de igual manera que en global photon map.

Max photons: Funciona de igual manera que global en photon map.

Mode:
On render end:

<!-- p. 74 -->

Enviroment

Gi enviroment (skylight): Override Max´s: Activa la iluminación global del entorno, pudiendo ser aplicado un color
especifico o una imagen. Si utilizamos esta casilla anularemos el efecto del entorno del Max sobre la iluminación.

El multiplier nos permitirá regular la intensidad de esta iluminación.(Por defecto 1).

Reflection/refraction etc enviroment: Similar a GI enviroment pero aplicable solo a las reflexiones y refracciones
de los materiales.

QMC sampler

Adaptive amount: Controla el grado de muestras que serán aplicadas.
Valor 0 significa el maximo de muestras a computar, al contrario que el valor 1 del cual solo computamos las
mínimas.

Noise threshold: Umbral que regula la cantidad de granulado en la escena.
Valor 0 significa cantidad nula de grano.

<!-- p. 75 -->

Valores aceptables para dar calidad: 0,01 a 0,04

Min samples: Determina el mínimo número de rayos a tomar en cuenta para el cálculo. Valores recomendados
para obtener calidad son 15 o superiores.

Global subdivs multiplier: Multiplica el valor de las subdivisiones globales asignadas a la escena.

G-buffer/color maping

G-Buffer output channels:

Color mapping:

Type:

Linear multiply:
Exponential:
Hsv exponential:

<!-- p. 76 -->

Dark multiplier:
Bright multiplier:
Clamp output:

Affect background:

Camera

Camera type: Type:

Override fov:

Depth of field (DOF): Llamado técnicamente en fotografía, profundidad de campo.

Aperture: Apertura del diafragma de la cámara; nos indica el grado de desenfoque que deseamos usar en la
escena.

<!-- p. 77 -->

Center bias: Nos indica el grado de distorsión focal.

Focal dist.: O distancia focal, nos permite controlar la distancia en la que los objetos se encontrarán enfocados.
(Este valor depende de la escala de la escena).

Get from camera:
Sides:
Rotation:
Subdivs: A mayor valor de éste, mejor será la definición del desenfoque.(Los tiempos de render aumentan
considerablemente).

Motion blur: Desenfoque provocado por el movimiento de los objetos.(Efecto simulando a las cámaras reales al
obtener una baja velocidad de obturación).

<!-- p. 78 -->

Duration (frames): Tiempo calculado en frames que será tomado para realizar el desenfoque.

Interval center: Nos permite mantener más enfocadas las zonas situadas entre áreas de desenfoque.

Bias: Cantidad de desenfoque que será aplicado en cada frame.(A mayor valor, menos desenfoque).

<!-- p. 79 -->

Subdivs: Define la calidad que será usada en cada una de las muestras. (Los tiempos de render aumentan en
consideración).

Deafult Displacement

Override Max´s:
Edje lenght:
View-dependent:
Max subdivs:
Amount:
Relative to bbox:
Tight bounds:
(Este panel lo podemos encontrar dentro de la pestaña modificadores de objeto VRay displacement mod).

<!-- p. 80 -->

Type:

Common params: Texture chan:
Filter texmap:
Amount: Distancia que será afectada por el desplazamiento.

Shift:
Water level:

Relative to bbox:

2D mapping:
Resolution: Con este parámetro podemos concretar la resolución que será aplicada en la imagen que tomemos

para el desplazamiento.

(Aqui os dejo un ejemplo de cómo realizar un enrejado perfecto, rápida y facilmente usando una simple imagen).

System

<!-- p. 81 -->

Raycaster params: Max. tree depth:
Min. leaf size:
Face/level coef:

Distributed rendering:

Render region division: X: Anchura relativa a la región de renderizado. Y: Altura relativa a la region de
renderizado.
Region W/H:
Region count:
Region secuence: Tipo de secuencia con la cual va a ser renderizada la escena. Disponemos de 6 tipos:

Reverse secuence: Invertimos la secuencia de renderizado.

Previous render: Unchanged: Superposicion de la nueva imagen sobre la anterior.

Cross: La anterior imagen será ligeramente oscurecida dando paso al nuevo render.

Fields: Similar a cross pero oscureciendo levemente la imagen.

Darken: El anterior render será borrado, dando comienzo la nueva imagen con fondo de pantalla en negro.

Blue: Similar a darken pero superponiendo el fondo de color azul sin llegar a borrar el antiguo render.

Frame stamp: Nos permite colocar una franja de texto en la zona inferior de las imagenes. Podemos plasmar el
texto a nuestro gusto, o usar los siguientes codigos de informacion del VRay:

%vrayversion: Version de VRay.
%filename: Nombre del archivo.
%frame: Cuadro de la animación en el que estemos renderizando.
%rendertime: Tiempo de render.
%computername: Host o nombre de nuestro equipo.
%date: Fecha actual.
%time: Hora actual.
%camera: Nombre asignado a la cámara que está siendo renderizada.
%w: Anchura de la imagen.
%h: Altura de la imagen.

<!-- p. 82 -->

%ram: Memoria RAM disponible.
%vmem: Memoria virtual disponible.
%mhz: Velocidad del procesador.
%cpu: Tipo de procesador.
%os: Sistema operativo actual.

Full width: Si lo activamos, el fondo del texto ocupará el 100% del ancho de la imagen.

Justify: Nos permite alinear el texto a izquierda, derecha o centrarlo.

Object properties:Use default moblur samples: Mantiene por defecto la cantidad de muestras que serán aplicadas
por el motion blur.

Motion blur samples: Permite definir el número de muestras que serán usadas por el motion blur. Nos dará más
calidad, pero los tiempos de render aumentarán bastante.

Generate GI: Aumenta o disminuye la intensidad de luz que es generada por el objeto.

Receive GI: Aumenta o disminuye la intensidad de luz que es recibida por objeto.

<!-- p. 83 -->

Visible to GI: Si desactivamos esta opción, el objeto no será afectado por la iluminación global.

Generate caustics: Activamos o no la posibilidad de generar efectos cáusticos en el objeto.

Receive caustics: Activamos o no la posibilidad de recibir efectos cáusticos en el objeto.

Caustics multiplier: Intesidad del efecto cáustico sobre el objeto.

Matte properties: Matte object: Convierte los objetos a fondo blanco para poder ser usados como canal alfa.

Alpha contribution:

Direct light: Shadows: Permite que las sombras sean proyectadas sobre el objeto.

<!-- p. 84 -->

Affect alpha:

Color: Con este parámetro podemos controlar el color de las sombras proyectadas sobre el objeto.

Brightness: Aumenta o disminuye la intensidad de las sombras sobre los objetos matte.

Reflection/Refraction/GI: Reflection amount: Cantidad de reflexión que es afectada por el objeto matte.

Refraction amount: Cantidad de refracción que es afectada por el objeto matte.

GI amount: Intesidad de iluminación global que afecta al objeto matte.

No GI on other mattes: Impide que la iluminación global que afecta al objeto repercuta sobre el resto de objetos
matte.

<!-- p. 85 -->

VRayShadowsParams

<!-- p. 86 -->

(Lo podemos encontrar en la pestaña modificadores de cada luz).
Transparent shadows: Activando esta opción las sombras proyectadas de objetos transparentes adoptan el color
de éstos.
Por el contrario, si la desactivamos las sombras tomarán por defecto un tono grisaceo.

Smooth surface shadows: Suaviza las sombras sobre los contornos de los objetos, permitiendo un degradado
más uniforme.
(Es un efecto poco apreciable a primera vista).

Bias: Nos marca la tendencia de las sombras a alejarse o acercarse de los objetos que las proyectan.

Area shadow: Nos permite controlar la cantidad de difusión que efectúan las sombras sobre los objetos.

Box: Las sombras son pronunciadas imitando la trayectoria que sería producida por el efecto de ellas sobre un
cubo.

Sphere: Las sombras son pronunciadas imitando la trayectoria que sería producida por el efecto de ellas sobre
una esfera.

<!-- p. 87 -->

U,V,W size: Delimita el tamaño del difuminado producido por las sombras de área.

Subdivs: Al igual que en el resto de los parametros del VRay, nos controla la cantidad de muestras que serán
tomadas para definir la calidad de las sombras.

<!-- p. 88 -->

On: Activa o desactiva el uso de la luz.

Double-sided: Permite activar la iluminación en ambas caras de cada Vraylight.

Invisible: Hace invisible el objeto emisor de luz (Vraylight) para la escena.

Ignore light normals:

Normalize intensity: Por defecto activada, permite que la intensidad de luz sea trabajada en watios por metro
cuadrado.
Desactivando esta opción el multiplicador de luz define la intensidad total en watios de la fuente luminosa.

No decay: Al tener activada esta opción las luces no trabajan en medidas físicas reales de potencia.

Color: Selecciona el color que será proyectado por la luz.

Mult.: Multiplicador o intensidad proporcionada por la luz.

Skylight portal: Esta opción desactivará el multiplicador manual de las luces, siendo sustituido por la intensidad
de la luz que asignemos al entorno, o Gi enviroment.

Store with irradiance map: El cálculo de las luces será realizado junto con el mapa de irradiación.

Smooth surface shadows: Suaviza las sombras sobre los contornos de los objetos, permitiendo un degradado
más uniforme.

Type: Plane: Objeto emisor de luz con forma plana.

Dome: Objeto emisor de luz con forma de domo.

<!-- p. 89 -->

Sphere: Objeto emisor de luz con forma esférica.

Size: Tamaño del objeto emisor de luz (Vraylight) con respecto a los ejes x, y, z trabajando en función de la
escala en la escena.

Sampling: Subdivs: Controla la cantidad de muestras que serán tomadas para definir la calidad en las sombras.

On: Activa o desactiva el uso de la luz.

Double-sided: Permite activar la iluminación en ambas caras de cada Vraylight.

Invisible: Hace invisible el objeto emisor de luz (Vraylight) para la escena.

Ignore light normals:

Normalize intensity: Por defecto activada, permite que la intensidad de luz sea trabajada en watios por metro
cuadrado. Desactivando esta opción el multiplicador de luz define la intensidad total en watios de la fuente
luminosa.

No decay: Al tener activada esta opción las luces no trabajan en medidas físicas reales de potencia.

Color: Selecciona el color que será proyectado por la luz.

Mult.: Multiplicador o intensidad proporcionada por la luz.

Skylight portal: Esta opción desactivará el multiplicador manual de las luces, siendo sustituido por la intensidad
de la luz que asignemos al entorno, o Gi enviroment.

Store with irradiance map: El cálculo de las luces será realizado junto con el mapa de irradiación.

Smooth surface shadows: Suaviza las sombras sobre los contornos de los objetos, permitiendo un degradado
más uniforme.

Type: Plane: Objeto emisor de luz con forma plana.

Dome: Objeto emisor de luz con forma de domo.

Sphere: Objeto emisor de luz con forma esférica.

Size: Tamaño del objeto emisor de luz (Vraylight) con respecto a los ejes x, y, z trabajando en función de la
escala en la escena.

Sampling: Subdivs: Controla la cantidad de muestras que serán tomadas para definir la calidad en las sombras.

Galería de imágenes

<!-- p. 90 -->

Guía del Editor de materiales

<!-- p. 91 -->

Contenido

Basic parameters
BRDF
Options
Maps
Reflect interpolation
Refract interpolation

Parámetros básicos

Diffuse: Define el color asignado al material.

También nos permite la posibilidad de asignar un mapa al canal diffuse activando la pestaña situada a la derecha
del color.

<!-- p. 92 -->

Reflect: Establece la intensidad que podemos aplicar a la reflexión.

Al igual que en diffuse, nos permite asignar un mapa al material.

<!-- p. 93 -->

Hilight. glossiness: Controla el difuminado de la reflexión que producen los puntos de luz.

Refl. glossiness: Controla el difuminado de la reflexión. Con valor 1,0 obtendríamos un reflejo perfecto.

<!-- p. 94 -->

Subdivs: Ajusta la calidad de la reflexión producida por el glossiness. A mayor valor, más definición.

Use interpolation: Activando esta pestaña podremos controlar la calidad de las reflexiones usando el menú
desplegable.

<!-- p. 95 -->

Fresnel reflections:

Parámetro mediante el cual obligaremos a las caras más paralelas de los objetos a efectuar un mayor grado de
reflexión que las dispuestas en un ángulo diferente.

Fresnel IOR: Valor que controla la intensidad de las reflexiones fresnel. Para poder modificar este valor debemos
desactivar la pestaña "L" situada a la derecha de fresnel reflections. Cuanto mayor sea este valor, menos
apreciado será el efecto fresnel.

Max depht: Profundidad máxima que nos determina el número de veces que los rayos son reflejados en los
objetos. A mayor número de rayos, mejor será la definición de las reflexiones.

<!-- p. 96 -->

Exit color: Nos indica mediante el color que asignemos, el limite máximo que puede alcanzar la reflexión de los
rayos en el objeto. Las zonas rojas de la imagen corresponderían a los puntos donde más veces han sido
reflejados los objetos entre sí.

Refract: Establece la intensidad que podemos aplicar a la refracción.

<!-- p. 97 -->

Glossiness: Controla el difuminado de la refracción.

Subdivs: Ajusta la calidad de la refracción producida por el glossiness. A mayor valor, más definición.

Use interpolation: Activando esta pestaña podremos controlar la calidad de las refracciones usando el menú
desplegable.

Translucent: Propiedad por la cual podemos distribuir la luz dentro de un objeto asignándole un color.

Thickness: Cantidad de rayos que serán trazados en el interior de los objetos.

<!-- p. 98 -->

Light multiplier: Multiplicador que aumenta o disminuye la intensidad de la luz en el objeto translúcido.

Scatter coeff: Controla la dispersión de los rayos. Valores cercanos a 0 nos proporcionarán una dispersión hacia
todos los lados del objeto. Valores cercanos a 1 nos mantendrán la dirección original de los rayos en el objeto.

Fwd/bck coeff: Controla la dirección en la que serán dispersados los rayos. Valores cercanos a 0 nos
proporcionarán una dispersión hacia el interior del objeto. Valores cercanos a 1 nos proporcionarán una
dispersión hacia el exterior del objeto.

<!-- p. 99 -->

IOR: Indice de refracción por el cual será definida la forma en que los rayos de luz atraviesan los objetos. A
mayor valor más distorsión en el reflejo.

Max depth: Profundidad máxima que nos determina el número de veces que los rayos son refractados en los
objetos.
A efectos prácticos, si en la realidad colocamos un espejo enfrente de otro, estos se reflejarían infinitas veces;
en este caso el valor depht nos indica la cantidad de veces que queremos que esto ocurra.

Exit color: Nos indica, mediante el color que asignemos, el limite máximo que puede alcanzar la refracción de los
rayos en el objeto.

<!-- p. 100 -->

Fog color: Nos indica la degradación que sufre la luz al atravesar el objeto, de forma visible mediante el color que
asignemos. A mayor valor, menor transparencia.

Fog multiplier: Valor a través del cual controlaremos la cantidad de degradación efectuada por fog color.

Affect shadows: Permite que las sombras se adapten a la transparencia del objeto.

<!-- p. 101 -->

Affect alfa: Activando esta pestaña el canal alpha se verá afectado por las reflexiones.

BRDF

<!-- p. 102 -->

Phong: Proporciona brillos muy marcados.

Blinn: Suaviza ligeramente el brillo Phong.

Ward: Difumina completamente el brillo.

Anisotropy (-1..1): Propiedad por la cual podemos modificar la escala del brillo de los materiales en relación al eje
seleccionado.

<!-- p. 103 -->

Rotation: Con esta opción rotaremos el brillo en el eje seleccionado.

UV vectors derivation:

Local axis: Eje por el cual vendrá definida la derivación de la anisotropía.

Map channel: La derivación vendrá definida por el canal del mapa seleccionado.

Opciones

<!-- p. 104 -->

Trace reflections: Activa o desactiva el trazado de las reflexiones.

Trace refractions: Activa o desactiva el trazado de las refracciones.

Cutoff: Límite por debajo del cual las reflexiones y refracciones no serán trazadas.

Double-side: Permite que el material sea computado en las caras internas de los objetos.

Reflect on back side: Permite la reflexión entre las caras internas de los objetos.

Use irradiance map: Activando esta pestaña el cálculo de las reflexiones será efectuado por el mapa de
irradiancia.
En caso contrario, será sustituido por QMC, permitiendo mayor detalle pero alargando los tiempos de
renderizado.

<!-- p. 105 -->

Treat glossy rays as GI rays: Nos especifica cuándo los rayos glossy serán sustituidos por iluminación global.

Energy preservation mode: Permite controlar de qué manera son afectados entre sí los canales diffuse, reflection
y refraction. Como ejemplo, si tomamos un material con aspecto de mármol y le vamos aumentando
progresivamente la cantidad de reflexión, llegará un momento en que ésta tapará completamente al mármol y
solo veremos reflejo.

RGB: Los colores rojo, verde y azul son tratados de forma separada.

Monocrome: Los canales diffuse, reflection y refraction son tratados en base a la intensidad de cada uno.

<!-- p. 106 -->

Mapas

Diffuse:

Reflect:

<!-- p. 107 -->

HGlossiness:

RGlossiness:

Fresnel IOR:

<!-- p. 108 -->

Refract:

Glossiness:
IOR:

Translucent:

<!-- p. 109 -->

Bump:

Displace:

Opacity:

<!-- p. 110 -->

Enviroment:

Reflect Interpolation

Min rate:

Max rate:

Clr thresh:

Interp. samples:

Nrm thresh:

Refract Interpolation

<!-- p. 111 -->

Min rate:

Max rate:

Clr thresh:

Interp. samples:

Nrm thresh:

Tutoriales

<!-- p. 112 -->

Relación de tutoriales de Vray

Autor: Federico González Bosque.
Ajustes.
Integración de una figura 3D en otra imagen.
Materiales avanzados.
Pantalla de alfileres.
Crear cáusticas.

Autor: José Florencio "Slimo".
Modelado, iluminación y materiales.
Composición.
Post-producción.

Autor: Dideje
Iluminación de interiores.

Evermotion. (Traducción: Urrechu)
Vaso con mistela.
Postal de un cafetería.
Trazado progresivo.
Cómo representar el cuero.
Múltiples vistas con un solo mapa de irradiación.
Crear un lámpara fluorescente encendida.

Aversis. (Traducción: Urrechu)
Configuración básica para VRay.
Ajustes básicos de materiales.
Refracciones.
Reflexiones.
Una iluminación estándar.
Copa de cristal +líquido.

Spot3D. (Traducción: Urrechu)
Técnicas básicas VRay Advanced.
Trazar un mapa de fotones.
Ejemplos de funciones

<!-- p. 113 -->

Tutorial

FEDERICO GONZÁLEZ BOSQUE
federicogonzalezbosque@yahoo.com.ar

<!-- p. 114 -->

Temas abordados en este tutorial

\- Cómo configurar la iluminación global en VRay.
\- Aplicar un mapa de desplazamiento.
\- Aplicar configuración de una escena exterior.
\- Cómo configurar la iluminación global en FinalRender.

\- Integración de una figura 3D en otra imagen.
\- Iluminación.
\- Motor de render.
\- Retoques finales en Photoshop.

\- Materiales avanzados.
.Plástico mate.
.Plástico pulido.
.Madera.
.Metal cromado.
.Cristal.
.Pintura metalizada.
.Agua.
.Terciopelo.

\- Cómo crear una pantalla de alfileres.

\- Cómo crear cáusticas.

Cómo configurar la iluminación global

Cómo configurar la iluminación global. (En VRay)

Para crear una iluminación global rápida únicamente hay que seguir una serie de sencillos pasos:

1.- Creamos una escena simple (o compleja, como queramos). En este caso he hecho un plano con una tetera
encima.

2.- Aplicamos los materiales que queramos. Yo he puesto el mateial por defecto para el suelo y uno de un gris
más claro y de dos caras para la tetera.

<!-- p. 115 -->

3.- Entramos a las opciones de Render (F10) y en "Current Renderers" seleccionamos el VRay como motor de
render para "Production".

4.- Nos desplazamos por las nuevas opciones del motor de render hasta los "Global Switches", donde
desactivaremos la iluminación por defecto del Max.

5.- Más abajo encontramos el "Image Sampler (Antialiasing)" y allí seleccionamos "Adaptive Subdivision" como
método de suavizado de bordes. Marcamos también la casilla "Rand", lo que añade un poco de ruido en las
zonas suavizadas.

6.- Seguimos bajando hasta llegar a la pestaña de "Indirect Illumination (GI)". Allí dejaremos las opciones tal y
como están puestas en esta imagen.

7.- Ya sólo nos falta activar la luz global, y esto lo hacemos en la pestaña "Environment". Después de activarlo
subimos el multiplicador a 1,5 y...

<!-- p. 116 -->

8.- ... tiramos el render. ¡Ya está!. Con esta configuración no logramos la mejor calidad, pero sí un tiempo
buenísimo de render y una calidad, en relación con el tiempo, muy acertada (en mi P4 a 1,7Ghz. tardó 8
segundos)

Aplicar un mapa de desplazamiento

Aplicar un mapa de desplazamiento en VRay

Muchas veces, para añadir detalle extra a nuestra malla, un mapa de "bump" no es suficiente para conseguir el
efecto deseado, sobre todo en los bordes de la geometría o con relieves muy acusados.Para ello la mejor
solución es utilizar un mapa de desplazamiento creado por nosotros. VRay nos proporciona un acabado muy
acertado en estas acciones y un tiempo de render no demasiado elevado.

Para aplicar un mapa de desplazamiento a una malla haremos lo siguiente:

1.- Creamos un plano y le aplicamos un material estándar, tal y como vienen los propios del Max. A la hora de
crearlo las coordenadas de mapeado deben estar activadas.

2.- A continuación colocamos una luz que incida desde un lateral para acentuar después más el efecto mediante
las sombras.

<!-- p. 117 -->

3.- La luz la configuraremos según estos parámetros.

<!-- p. 118 -->

4.- Preparamos el VRay para que utilice la iluminación global con un "Environment" bastante azulado y de
intensidad 0,8 (si hay dudas en este paso, consultad el tutorial Cómo configurar la iluminación global en VRay y
tiramos un render. El resultado será un plano como este.

<!-- p. 119 -->

5.- Seleccionamos el plano y añadimos el modificador "VRayDisplacementMod".

6.- Para poder utilizar este modificador necesitamos una imagen que podamos usar como desplazamiento. El
desplazamiento, sea cual sea el programa, siempre sigue las mismas directrices: negro abajo y blanco arriba (es
una regla nemotécnica, nada más). Para este caso he creado una imagen con el Photoshop simulando un
laberinto.

<!-- p. 120 -->

7.- Una vez creada la imagen, vamos al editor de materiales y creamos un "bitmap" pinchando en el botón "Get
Material", marcando "Bitmap" y seleccionando la imagen (laberinto) que hemos creado.

"Get Material"

"Bitmap" creado y su nombre "Map #1"

8.- Con el "Bitmap" creado, ya sólo tenemos que configurar el modificador "VRayDisplacementMod". Para ello
seleccionamos el "2D mapping" ya que es un plano lo que vamos a desplazar, añadimos el mapa de
desplazamiento "Map #1" correspondiente al "Bitmap" de nuestra imagen, subimos el "Amount" a 30 (la cantidad
de elevación del modificador), aumentamos la resolución y la precisión de la malla, y marcamos la casilla "Tight
Bound" para una mayor optimización de la malla.

9.- Si ahora tiramos el render notaremos una "leve" diferencia con el render anterior. Las imperfecciones de las
paredes son debidas a que, como se puede ver en el punto 6, las líneas que hice en el Photoshop para crear el
laberinto no son rectas y además el antialiasing que tenían era muy malo. De haberlo hecho con líneas
horizontales y verticales perfectas esto no habría ocurrido.

<!-- p. 121 -->



<!-- p. 122 -->

Aplicar Configuración de una escena exterior

Configuración de una escena exterior con VRay

¿Quien no ha tenido que hacer una escena exterior en algún momento?. Ya sea en una animación, en una
infografía relacionada con infoarquitectura... casi siempre se nos plantea el tener que hacer un entorno lumínico
exterior válido que nos de una sensación lo más real posible. El 3D Studio Max nos permite llegar a ello
fácilmente junto con el fantástico motor de render VRay. Para ello seguiremos los siguientes pasos:

1.- Para este tutorial he creado 4 edificios simples y un plano con multiplicador a 500. También he colocado unas
aceras para dar más gracia a la imagen.

2.- Creamos una luz "Target Direct", ya que es el tipo de luz idóneo para simular la luz del sol, al ser sus rayos
paralelos unos a otros, y la colocamos como en la imagen.

<!-- p. 123 -->

3.- La mejor forma de colocar una luz es "viendo a través de ella". Esto lo podemos hacer (teniéndola
seleccionada) con el atajo de teclado "Shift+4", o pulsando el botón derecho sobre el nombre de la vista y
seleccionando la luz dentro de "Views", como se ve en la imagen siguiente.

4.- Una vez hecho esto pasaremos a ver lo siguiente, o algo parecido.

<!-- p. 124 -->

5.- Con los iconos de "Light Hotspot", "Light Falloff" y "Orbit Light", a parte del "Truck Light" hecho con el botón
central del ratón, nos moveremos hasta queposicionemos la luz como nos interese. Una buena manera es tal y
como aparece en la imagen.

6.- Si ahora tiramos un render conseguimos algo como esto.

<!-- p. 125 -->

7.- Configuramos la luz de la siguiente manera. Es importante tener en cuenta varias cosas, como que tenga
sombra, que ésta sea del tipo "VRayShadow", que el color de la luz sea levemente amarillenta y tener marcada la
casilla "Overshoot" para que ilumine fuera del cilindro. Eso sí, aunque ilumine fuera, las sombras sólo las calcula
dentro del cilindro. En la pestaña de los parámetros de la sombra "VRayShadow" marcamos la casilla "Area
shadow" y cambiamos el tamaño a un valor adecuado. Como ese valor depende del tamaño de la escena, habrá
que tirar varios render hasta que nos quede tal y como queremos.

8.- Entramos a las propiedades de render y en la pestaña de abajo, en "Assign Renderer", seleccionamos VRay
como motor de render. Después, en sus opciones, lo configuramos para que nos muestre un render rápido del
resultado final. De esta forma podremos cambiar varios parámetros y en poco tiempo ver los resultados.

<!-- p. 126 -->

9.- Si ahora renderizamos la escena veremos algo similar a esto.

10.- La calidad deja mucho que desear, pero hemos conseguido el render en pocos segundos, y en él sí que
podemos apreciar suficientemente cómo va a quedar la iluminación. También, para ver mejor cómo va a quedar
el resultado final podemos poner como fondo de la imagen el mismo color azulado que hemos utilizado en el
VRay para la iluminación global. Para ello entramos a las opciones del "Environment" y arrastramos el color
desde la ventana de configuración de render a esta última.

11.- Después de esto, el render sería como el siguiente.

<!-- p. 127 -->

12.- La imagen ya sería creíble, pero siempre se puede mejorar. Si conseguimos un cielo de 360º x 90º
lograremos potenciar enormemente el realismo de la imagen. Suele haber páginas por Internet que nos ofrecen
gratuitamente imágenes de este tipo. Además, es importante corregir la perspectiva, ya que a no ser que nos
asomemos desde la ventana de un 15º piso no veríamos lo que vemos en la imagen previamente renderizada.

En la siguiente imagen he cambiado el cielo y la perspectiva. Se aprecia que hay un cambio drástico, tanto a
nivel de composición como de realismo. Según sea la escena con la que trabajemos deberemos posicionar la
cámara, y según la sensación que queramos transmitir así será el bitmap que usaremos como cielo de fondo.

Para la composición, sobre todo en trabajos de infoarquitectura, funciona muy bien posicionar la cámara a 1,80
m del suelo, ya que así se vería desde la perspectiva de un transeunte.

<!-- p. 128 -->

13.- Ya sólo nos falta preparar los parámetros del VRay para renderizar la imagen con una buena calidad, digna
de cualquier presentación. Para ello sólo tendremos que pones los valores como en la siguiente imagen.

<!-- p. 129 -->

14.- Tras unos minutos habremos renderizado una imagen de una calidad similar a esta.

<!-- p. 130 -->

Aplicar ConfigurCómo configurar la iluminación global

Cómo configurar la iluminación global.

Configurar una escena con iluminación global y buena calidad en finalRender no es demasiado difícil, pero cierto
es que tampoco es tan sencillo como en otros motores de render. Para ello seguiremos los siguientes pasos:

1.- Creamos una escena (conviene que no sea demasiado compleja para que se pueda hacer el tutorial en poco
tiempo) y la aplicamos el material estándar del Max, aclarando levemente su color difuso.

2.- A continuación colocamos una luz cenital para que cree unas sombras atractivas.

3.- La luz la configuraremos según estos parámetros.

<!-- p. 131 -->

4.- Nos vamos a la ventana de configuración del render y en la pestaña "Current Renderers" seleccionamos el
finalRender como motor de render para producción.

5.- Cuando lo seleccionemos se nos desplegarán los nuevos menús del finalRender. En la primera pestaña,
"Global options", configuramos el anti aliasing con los siguientes parámetros. Es importante recordar que la
configuración que estamos realizando es para tirar un render con bastante calidad.

6.- Bajamos por las siguientes pestañas y nos paramos en "Global Illumination", donde configuraremos los
parámetros tal y como están en esta imagen.

<!-- p. 132 -->

7.- Una vez configurados todos los parámetros ya podemos lanzar el render. El resultado será algo similar a esto
(Al menos la iluminación).

<!-- p. 133 -->

Análisis de la Integración de una figura 3D sobre otra imagen

<!-- p. 134 -->

Duración aproximada: 1-2 horas
Software: Softimage XSI 3.5, 3D Studio MAX. (Motor de render VRay) y Photoshop CS

Temas abordados en este tutorial

Iluminación.
Motor de render.
Retoques finales en Photoshop.

¿Cuántas veces nos hemos quedado mirando una imagen en la que no sabemos indicar qué objetos son 3D y
cuales son reales?, o ¿cuántas veces noshemos preguntado cómo habrán conseguido el realismo de cierta
escena?. Pues bien, esa magia es principalmente mérito de una buena integración de los elementos 3D con la
escena, pero no siempre se tiene claro cómo conseguirlo.

Para realizar cualquier integración hay unos pasos básicos que siempre hemos de seguir:

\1. Modificar nuestro modelo 3D hasta llegar a la pose que deseemos que tenga.
\2. Colocar al cámara con el ángulo y perspectiva lo más cercano posible al fondo con el que lo vamos a
componer.
\3. Configurar los posibles elementos matte si es que fuesen necesarios.
\4. Analizar la iluminación de la imagen sobre la que vamos a integrar nuestro personaje e imitarla lo mejor
posible en nuestro software 3D.
\5. Seleccionar nuestro motor de render, configurarlo y lanzar el render final.
\6. Hacer los retoques necesarios en Photoshop u otro programa de edición de imagen.

En el caso de la integración de nuestro personaje en el fotograma de la película Shrek de PDI/DreamWorks
utilizamos Softimage XSI 3.5 para el modelado, texturizado y setup del personaje, 3D Studio Max 5.1 con Vray
para su iluminación y renderizado, y Photosp CS para la limpieza del fondo y posteriores retoques de la imagen,
aunque resultados parecidos se pueden conseguir con cualquier otro software profesional.

Los primeros pasos

Lo primero es pensar qué queremos hacer. Si es un trabajo que nos han encargado este paso ya lo habrán
hecho otros en nuestro lugar, así que no nos tendremos que complicar demasiado.
En el caso concreto de la integración que vamos a hacer, la idea principal es reemplazar a Shrek de la imagen
original por nuestro personaje Papo. La labor no es fácil ya que Papo es bastante delgado y Shrek todo lo
contrario, así que utilizando la herramienta de clonar de Photoshop nos ponemos manos a la obra.

<!-- p. 135 -->

Un buen rato después conseguimos un resultado como éste. Ahora debemos buscar una pose similar de nuestro
personaje, si es que queremos copiar la postura original.

Buscando la mejor pose

Para llegar a una pose similar a la de Shrek modificamos el setup que ya teníamos realizado sobre nuestro
personaje.

<!-- p. 136 -->

Nos ayuda bastante el disponer de una imagen que poner de fondo para copiar la pose, es este caso la imagen
original de Shrek y Asno.

Una vez lograda la pose pasamos la malla ya deformada a MAX para poder utilizar el motor Vray.

Posicionando la cámara

<!-- p. 137 -->

Una vez importada la malla y creados los materiales que vamos a utilizar pasamos a configurar la cámara. Éste
es uno de los pasos que conviene realizar de la mejor forma posible ya que en ello reside el 50% de la
credibilidad de la escena, sobre todo si se trata de un trabajo de infoarquitectura donde llegar a la perspectiva
perfecta es una obligación.

La mejor forma de hacer esto en MAX es trabajar con la perspectiva en lugar de la cámara, ya que con ella
tenemos muchísima más libertad, y después convertir ésta en una cámara (seleccionando una cámara y desde
la perspectiva pulsando Ctrl+C).
Pondremos como fondo a la hora de trabajar (Viewport Backgroung) la imagen original de Shrek y Asno , para,
únicamente orbitando, desplazándonos y haciendo zoom colocar a nuestro personaje exactamente en el ángulo
e inclinación que nos interese.

Iluminación

Iluminación

La principal complicación de esta composición es la simulación de la luz, ya que al atravesar unos árboles llega
produciendo unas sombras características. Para posicionar el emisor de luz principal no hay más que fijarse un
poco en la imagen original y ver cómo incide la luz sobre los objetos, y en especial sobre Asno y Shrek .
Una vez situada la luz buscamos una imagen que sirva para filtrar ésta a modo de proyector y crear un plano a
modo de suelo con un material Matte/Shadow que reciba sombras. La iluminación global hará el resto.

Motor de render

<!-- p. 138 -->

Motor de render

Una vez posicionada la cámara y la luz, no tenemos ya más que tirar el render final. Para ello debemos elegir el
motor de render que más se ajuste a nuestras necesidades, ya que cada uno suele funcionar mejor en un campo
concreto.

En esta integración hemos utilizado el Vray, ya que con él se pueden conseguir composiciones de gran calidad
en muy poco tiempo y empleando iluminación global.

Un dato importante, ya que yo cometí el error a la hora de tirar el render, es lanzarlo con la imagen de fondo en
la que ya hemos quitado a Shrek y no con la original (que acabamos de usar para situar la cámara), puesto que
así ahorramos el tiempo que, de no cambiarla, deberíamos invertir en arreglar ciertas partes del antialiasing de
los bordes de Papo.

Una vez renderizada la imagen la guardamos en TGA o TIFF incluyendo el canal alfa puesto que nos ayudará
después a la hora de recortar al personaje para la composición en Photoshop.

Retoques finales en Photoshop

Retoques finales en Photoshop

Una vez abiertas las imágenes ya sólo nos queda hacer unos pequeños retoques con el Photoshop. Para ello lo
ideal es tener en la capa background la imagen de la que hemos eliminado a Shrek y encima la imagen
renderizada con el canal alfa aplicado como una máscara. De esta forma podemos trabajar con ambos
elementos por separado.

Los retoques que realizamos con Photoshop son un ajuste Hue/Saturation para desaturar levemente a Papo y
para modificar el tono verde y cambiarlo por uno más amarillento, la adición de una capa de ajuste por curvas
para realzar el color general de la composición, y el añadido de un poco de hierba en la zona de los pies para
hacer más creíble el efecto.

<!-- p. 139 -->

Después de un tiempo he echado un vistazo a la imagen de Papo para recordar esos maravillosos ratos que
pasé con mis compañeros de TRAZOS y... ¡Oh! ¡Sorpresa! La imagen no es tan maravillosa como la recordaba.
¿Qué ocurre? Pues básicamente que he descubierto un error en el fondo. Como podéis apreciar en la imagen
anterior el fondo medio roca, medio tierra de detrás de Papo es distinto por su parte derecha e izquierda, así
que... manos a la obra.15 minutos después he arreglado el fondo, dando una apariencia más profesional a la
imagen.

Materiales avanzados

<!-- p. 140 -->

Temas abordados en este tutorial

Plástico mate
Plástico pulido
Madera
Metal cromado
Cristal
Pintura metalizada
Agua
Terciopelo

¡Trabajo terminado.! Pero , ¿qué es lo que falla? Hemos trabajado el modelado de nuestra escena, la
iluminación , pero hay algo que sigue diciendo que es una imagen de síntesis. En muchos casos el problema
es de unos materiales creados demasiado deprisa, o sin habernos parado a pensar cómo deberían ser. Siempre
todo va demasiado rápido cuando queremos ver nuestro primer render y pocas veces retrocedemos para hacer
un buen ajuste del color, brillo especular, etc.

En este tutorial crearemos varios materiales básicos muy utilizados en la configuración de una escena Standard ,
enumerando y explicando paso a paso cada parte del proceso. Estos materiales son plástico, madera, metal
cromado, cristal, pintura metalizada, agua, y terciopelo. Emplearemos VRay a la hora de renderizar así como
de configurar ciertos parámetros de los materiales, pero esto no indica que no se pueda seguir este tutorial con
los parámetros propios de otros motores de render como finalRender, Brazil o MentalRay.

Para que este tutorial se pueda entender, vamos a explicar brevemente unos conceptos básicos en la
creación de cualquier material:

Color: tono cromático propio de un objeto. Se puede usar un color único o una imagen como mapa de colores.

Brillo especular: rebote de la luz sobre la superficie del objeto proveniente del emisor lumínico. Cuando
más rugosa sea la superficie del mismo, más se refractará (esparcirá) la luz. Se puede controlar tanto la
intensidad, como el color o el nivel de refracción. Los más utilizados son el Blinn (plásticos, madera y casi
cualquier material), Anisotrópicos (CDs u otra superficie con microsurcos), Multi-Layer (combinación de dos
brillos especulares para conseguir un efecto más atractivo en muchos casos ).

Opacidad: grado de transparencia de un objeto. Se puede delimitar con un porcentaje o utilizando un
mapa de opacidad, donde los tonos más claros indicarían opacidad y los más oscuros transparencia.

Reflexión: propiedad de ciertos materiales de reflejar la luz (la imagen). Se puede especificar el porcentaje
de reflexión así como lo difuminado que esté.

Refracción: cualidad de los materiales transparentes o translúcidos de variar la trayectoria de los fotones (luz)
que los atraviesa distorsionando así lo que se ve a través de ellos. La cantidad de variación de la trayectoria la
da el Indice de Refracción (IOR en inglés).

Una vez explicados estos conceptos, y antes de comenzar con la parte bonita de este tutorial, vamos a ver
cómo hacer un efecto que emplearemos en casi todos los materiales: la reflexión Fresnel. Es
necesario exponerlo aquí para tener después ya la base necesaria con la que poder seguir todos los pasos de la
creación de un material más o menos avanzado.

La reflexión Fresnel no es más que una reflexión que afecta más a las zonas más paralelas a la orientación
de la cámara desde la que vemos y menos a las perpendiculares. Es idónea para plástico, lacados, porcelana,
etc. Ya que da un aspecto mucho más realista a los objetos.

Hacer esta reflexión es bastante sencillo:

\1. Desplegamos la pestañaMAPS del material con el que trabajamos y hacemos clic en el botón NONE de
Reflection. Escogemos como reflejo el Falloff atenuación).

<!-- p. 141 -->

\2. Seleccionamos como tipo de Falloff el Fresnel.

\3. Hacemos clic en el botón NONE del color blanco del Falloff y ahí seleccionamos nuestro material raytrace,
en el caso del VRay llamado VRayMap. Si usásemos otro motor de render escogeríamos el pertinente.

<!-- p. 142 -->

\4. El reflejo Fresnel ya estaría creado: si deseásemos desenfocar el reflejo únicamente deberíamos
marcar la casilla Glossy dentro de las opciones del VRayMap y cambiar el valor del Glossiness por el que
busquemos.

Una vez visto esto estamos preparados para comenzar con nuestros materiales.

<!-- p. 143 -->

Plástico mate

Plástico mate.
(Material Standard)

\1. Asignamos un color, ya sea sencillo (Diffuse) o un bitmap (imagen). Éste será el color de nuestro objeto.

\2. Utilizamos un brillo especular de color blanco, de poca intensidad Specular Level = 20 -30) y bastante difuso
(Glossiness = 10 - 20).

\3. Si se quiere rizar el rizo, podemos utilizar un reflejo Fresnel muy desenfocado.

Plástico pulido

<!-- p. 144 -->

Plástico pulido.
(Material Standard)

\1. Asignamos un color, ya sea sencillo (Diffuse) o un bitmap (imagen). Este será el color de nuestro objeto, al
igual que en el plástico mate.

\2. Utilizamos un brillo especular de color blanco,de gran intensidad Specular Level = 200 - 500) y muy nítido
(Glossiness = 85 95).

\3. Aplicamos un reflejo Fresnel nítido.

Madera

<!-- p. 145 -->

Madera.
(Material Standard)

\1. Para el color utilizamos un bitmap (imagen) de madera o el material procedural Wood del MAX. Se
aconseja el bitmap por el gran realismo que ofrece. Es interesante desaturar un poco la imagen que tengamos ya
que habitualmente los bitmap de madera que podemos encontrar en cualquier paquete de texturas tienen una
saturación de color por encima de lo habitual. También podemos conseguir esta desaturación si utilizamos un
color Diffuse gris neutro (128,128,128) y el bitmap lo aplicamos no al 100% sino al 80 90%.

\2. Empleamos un brillo especular de color ámbar o similar, no blanco, de poca intensidad (Specular Level =
20 - 30) y muy difuso (Glossiness = 10 - 20). También se puede mejorar con un especular Multi-Layer , como
en el ejemplo.

\3. Como lo más probable es que no dispongamos del bump correspondiente, podemos emplear el mismo
bitmap o el procedural que hayamos utilizado como tal. La intensidad del mismo dependerá de la claridad
y del contraste de la fuente, así que iremos haciendo pruebas hasta que logremos un relieve no demasiado
exagerado pero apreciable.

\4. Si la madera está recién barnizada, o lacada, utilizaremos un reflejo Fresnel nítido al 70 - 90 % de intensidad.
Si el barniz empleado es mate o el objeto ya tiene muchas horas de uso usaremos el reflejo Fresnel
desenfocado al 50 - 70 % de intensidad.

Metal cromado

Metal cromado.

<!-- p. 146 -->

(Material Standard)

\1. Para que el reflejo no aparezca demasiado claro utilizamos un color Diffuse gris oscuro o negro.

\2. El brillo especular lo configuramos de color blanco, muy nítido (Glossiness = 85 - 95) y de gran intensidad
(Specular Level = 200 - 500). También se puede mejorar con el especular Multi-Layer , tal y como aparece en el
ejemplo.

\3. Aplicamos reflexión normal (no Fresnel) al 100%.

NOTA: la calidad del cromado depende enteramente del entorno que rodee al objeto. Cuanto más rico sea
(una imagen 360º, una escena completa terminada, etc.) mejor quedará.

Cristal

Cristal.

<!-- p. 147 -->

(Material VRayMtl)

Este material lo vamos a crear, no con el material Standard de MAX, sino con el material que nos trae el
VRay: el VRayMtl. De este modo podremos aprovechar su facilidad de uso y así emplearla posteriormente.

\1. En la casilla del color Diffuse pinchamos y seleccionamos un color muy oscuro, preferiblemente negro (para
no aclarar los reflejos).

\2. En el cuadro de Reflect cambiamos el negro existente por blanco. En este material la cantidad de reflexión
no se especifica por un número sino por un color. Negro = no reflejo, y Blanco = reflejo máximo. También
activamos las reflexiones Fresnel (Fresnel reflections), mucho más sencilla de hacer que con los materiales
Standard .

\3. La refracción funciona igual que la reflexión. Cambiamos el color negro (no refracción) por blanco (refracción
máxima).

MUY IMPORTANTE: para que lo que estemos creando sea cristal y no otro material transparente deberemos
ser fieles al Indice de Refracción, que en el cristal es 1,52 más o menos. Si ponemos otro la refracción
cambiará y el resultado no será el correcto.

También podemos hacer variaciones del cristal como las siguientes:

Cristal tintado: se puede teñir el cristal del color que se quiera. Tan sólo hay que hacer alguna prueba
antes de tirar el render definitivo ya que depende del grosor del objeto. Para ello cambiamos el color blanco del
Fog color (color de niebla) por el que queramos y modificamos el Fog multiplier (multiplicador de niebla)
hasta lograr la cantidad de teñido.

<!-- p. 148 -->

Cristal no liso (rugoso): este es otro efecto interesante, y podría ser usado en mamparas de baño o similar.
Únicamente deberíamos trabajarnos el relieve que emplearíamos. Crearlo es tan fácil como añadir un mapa
específico al Bump (el ejemplo está hecho con Noise).

<!-- p. 149 -->

Cristal al ácido: se podría considerar una variante del anterior, con la salvedad de que el relieve que
distorsiona lo que se ve a través de él es muy pequeño. Para crear este efecto no hace falta utilizar el Bump,
ya que el material del VRay tiene una opción que simula este efecto. Para utilizarlo, bajamos el valor del
Glossiness de 1 (brillante, sin defectos ni distorsión) a lo que nos interese (0,8 en el ejemplo). La suavidad de
este efecto la da el valor de Subdivs (subdivisiones): cuando mayor sea, más nítido y más tiempo de render).

<!-- p. 150 -->

Pintura metalizada

Pintura metalizada.
(Material Standard)

\1. Como color aplicamos un mapa Falloff en lugar de un color plano, ya que parte del efecto de la pintura
metalizada lo da el que las partes más paralelas a la orientación de la cámara sean más oscuras. Como
primer color usamos el que queramos que tenga nuestro objeto, y de segundo el color negro, o el primero color
pero mucho más oscuro.

\2. Para enriquecer el brillo especular utilizamos el de tipo Multi-Layer que no es más que dos brillos especulares
superpuestos. Como primero brillo especular empleamos uno de color blanco, muy intenso (Specular Level =
300 - 500) y muy nítido (Glossiness = 90 - 95). El especular secundario será del color del objeto pero más claro,
bastante difuso (Glossiness = 15 - 30) y su intensidad estará regulada por un mapa Celullar, Noise o
cualquiera que configurado a un tamaño muy pequeño de un aspecto de granulado. Así se logrará la
sensación de purpurina. Según el caso, nos podría interesar que el color del especular secundario no fuese
una versión más clara del color Diffuse (por ejemplo muchas pinturas azul metalizado tienen un especular
secundario morado).

\3. Aplicamos un reflejo Fresnel nítido, aunque en el caso de la pintura metalizada también podemos usar un
reflejo normal al 20%.

<!-- p. 151 -->

Agua

Agua

Tenemos que pensar antes de nada qué agua necesitamos, si agua transparente (si se va a ver qué hay
debajo), o agua opaca (si queremos que sólo refleje). Si necesitamos agua transparente, utilizaremos un
material VRayMtl debido a los posibles problemas que nos podrían generar las sombras si lo hacemos con un
Standard .

Agua transparente (Material VRayMtl)

\1. Con el fin de no clarar los reflejos Fresnel pondremos un color Diffuse negro completamente.

\2. Cambiamos el color negro de la refleción (Reflect) a blanco y activamos la casilla Fresnel reflection .

\3. También modificamos la casilla de color negro de la refracción (Refract) y la ponemos de color blanco
(refracción total). El Indice de Refracción (IOR) lo ponemos a 1,33.

\4. El relieve lo conseguimos con un mapa Noise ya sea Regular o Fractal según más nos interese.

NOTA: hay que activar la casilla Affect Shadows del material VRayMtl para que procese bien el color.

<!-- p. 152 -->

(con cambio de tamaño del "Noise")

Agua opaca (Material Standard)

\1. El color Diffuse deberá ser azul un poco desaturado (hacia gris) y bastante oscuro (el del ejemplo es RGB:
28, 48, 58).

\2. Como brillo especular queda muy bien también el Multi- Layer . De brillo especular primario usamos un
color blanco, de gran intensidad (Specular Level = 200 - 500) y muy nítido (Glossiness = 85 95). El
especular secundario sería de color azul claro, poca intensidad(Specular Level = 20 -35) y muy difuso
(Glossiness = 20 30).

\3. Utilizamos un reflejo Fresnel en la casilla Reflect.

<!-- p. 153 -->

MUY IMPORTANTE: al igual que con los cromados, la calidad del agua depende en gran parte de aquello que
refleje. Si nuestra escena no aporta demasiado que reflejar, siempre podemos utilizar la posibilidad de utilizar un
reflejo de entorno distinto al del render. Esto se consigue con la opción del VRay "Reflection/refraction etc
environment" - "Override MAX's".

Terciopelo

<!-- p. 154 -->

Terciopelo.
(Material Standard)

\1. La clave de este material es su color, ya que no tiene ningún brillo especular, reflejo o similar. El efecto
adecuado lo produce el material Falloff aplicado al color Diffuse. De los dos colores que tiene, el superior
(color de lo perpendicular a la orientación de la cámara) será granate y el inferior (paralelo a la orientación de
la cámara) rosa no pastel.

\2. Aunque el efecto ya esté casi conseguido podemos mejorarlo si añadimos un poco de Noise al
relieve Bump. Este tiene que ser muy pequeño y fractal, para que quede como una muy levemente rugosa.

Ver tabla de índices de refracción en el manual de VRay

<!-- p. 155 -->

Cómo crear una pantalla de alfileres

Tutorial

<!-- p. 156 -->

Cómo crear un "PinScreen" o "Pantalla de alfileres"
(Ya sé que este script hace justo esto. De todas formas si queréis aprender cómo hacerlo sin el script seguid
este tutorial. Aprenderéis más)

¿Cuántas veces hemos entrado en una tienda de regalos y hemos visto esa especie de "caja" vertical con una
matriz de "clavos" que, al presionarlos con la mano, crea por la otra cara la misma figura 3D de la mano con los
clavos desplazados?. Este efecto se puede lograr de múltiples maneras, pero el que más se acerca a la realidad
es el de crear la matriz de clavos con un mapa de desplazamiento.

Para lograr este efecto tendremos que trabajar un poco ya que necesitamos crear la imagen que utilizaremos
para el desplazamiento y modificarla con Photoshop para que además simule los clavos.

1.- Buscamos el modelo 3D que queramos utilizar. Está bien que sean cosas más o menos contundentes, ya que
si el modelo posee partes finas no quedará bien al perder gran parte del detalle. Siempre se puede probar con
una mano, un objeto sin mucho detalle, o como en este caso una cara.

(Esta cara ha sido descargada de la zona de material gratuito en 3D Cafe)

2.- Creamos una cámara frontal a la cabeza de manera que ésta quede bien encuadrada y ocupando casi todo el
encuadre.

3.- Utilizando la herramienta de medición "Tape" medimos las distancias: 1, de la cámara a la parte más cercana
del objeto con respecto a la cámara (la punta de la nariz); y 2, de la cámara a la parte más lejana del objeto con
respecto a la cámara (el supuesto nacimiento de las orejas).

<!-- p. 157 -->

4.- Con estas medidas nos vamos a la ventana de configuración del render y entramos en la pestaña "Render
Elements".

5.- Ahí añadimos (botón "Add...") como elemento de render el "Z Depth" para que nos calcule la profundidad del
objeto en el eje "Z" y lo configuramos con las dos distancias calculadas anteriormente con la herramienta "Tape".

<!-- p. 158 -->

6.- Renderizamos y tendremos como resultado algo parecido a esto. La imagen final que vamos a utilizar como
desplazamiento la deberemos sacar a una resolución grande (de 2000 x 2000 en este caso), para poder hacer
después bien el desplazamiento.

Sólo guardaremos la imagen "Z Depth" en formato TIF sin compresión, para evitar pérdidas de calidad.

7.- Abrimos la imagen en Photoshop y la aplicamos el filtro "Mosaic..." que se encuentra dentro del grupo
"Pixelate".

8.- Aplicamos un tamaño de celdilla de 19 pixels (el tamaño de la celdilla depende del tamaño de la matriz de
clavos que queramos usar. Para este caso concreto 19 está bien).

<!-- p. 159 -->

9.- Creamos un nuevo documento del tamaño de cada celdilla (19 x 19).

10.- Con la herramienta de selección circular creamos un círculo dejando siempre un pixel de margen por cada
lado y rellenamos la selección de color negro.

11.- Seleccionamos la imagen completa y pinchamos en "Define Pattern...", dentro del menú "Edit". De esta
forma crearemos un nuevo patrón que después repetiremos en la imagen "Z Depth" importada del MAX.

12.- Ponemos un nombre identificativo al patrón creado.

<!-- p. 160 -->

13.- Volvemos a la imagen "Z Depth" y creamos una nueva capa sobre el fondo (background) original.

14.- Rellenamos la nueva capa con el patrón creado.

<!-- p. 161 -->

Conseguiremos algo como esto.

15.- Invertimos los colores de la nueva capa.

<!-- p. 162 -->

16.- El resultado será una imagen como esta.

17.- Ahora, cambiaremos el modo de combinación de la capa nueva con el fondo a "Multiply". Este modo hace
que las zonas más claras se transparenten y las zonas más oscuras permanezcan tal cual. Así lograremos ver
por los círculos blancos la imagen del fondo.

<!-- p. 163 -->

18.- Este ya podría ser un mapa de desplazamiento válido. El problema es que la zona negra sería
completamente plana en lugar de mostrarnos varios"clavos" con un mínimo desplazamiento. Esto lo
solucionamos aclarando los tonos oscuros de la imagen del fondo mediante la modificación de las curvas del
Photoshop. Para lograr esto seleccionamos la capa del fondo (background) y seleccionamos como nueva capa
de ajuste las curvas ("Curves..."). Ahí modificamos sólo la zona oscura para no estropear las partes más claras.

<!-- p. 164 -->

19.- El resultado sería el siguiente.

Guardamos la imagen como TIF o GIF (sin optimización ninguna y a 256 colores)

20.- De nuevo en el 3D Studio MAX, creamos un plano, marcamos la casilla "Generate Mapping Coords" y le
aplicamos un modificador
"VRayDisplacementMod" para aplicar el mapa de desplazamiento que acabamos de crear.

21.- Vamos al editor de materiales y con la casilla de un material seleccionado pinchamos sobre el icono "Get
Material". Seleccionamos "Bitmap" y cuando nos pregunte por la imagen que deseamos seleccionamos la
imagen que hemos creado en Photoshop.

<!-- p. 165 -->

22.- Arrastramos el nuevo material al "Texmap", dentro del "Common params" del "RayDisplacementMod".
Seleccionamos "Instance" para que si modificamos posteriormente algún parámetro del material se aplique
también en el mapa de desplazamiento, y configuramos los parámetros del modificador como viene abajo:

\* 2D mapping (landscape): mapeado apropiado para un plano, como es éste nuestro caso.
\* Amount: cantidad de desplazamiento. Cuando más tenga, más elevado será.
\* Resolution: resolución de la malla. En este caso debería ser alto para representar todos losdetalles de la
imagen original.
\* Tigh bounds: suaviza los bordes para evitar posibles problemas.

NOTA: si este método da problemas se puede utilizar el "3D mapping", y añadir en "Face subdivs" un número
alto de subdivisiones como 512 o 1024.

23.- Seleccionamos el VRay como motor de render, "Adaptive subdivision" como método de antialiasing en la
pestaña "VRay:: Image sampler
(Antialiasing)" y si queremos algún efecto de iluminación global (ver Tutorial 1).

<!-- p. 166 -->

24.- Una vez seguidos todos los pasos, y tras un buen rato renderizando, deberíamos lograr una imagen como
ésta:

<!-- p. 167 -->

Cómo crear cáusticas

<!-- p. 168 -->

Tutorial

Cómo crear cáusticas en VRay

Unas buenas curvas cáusticas pueden dar mucha vida a una escena, ya que es un efecto óptico con el que
convivimos en todo momento. Para crearlas en VRay hay que hacer lo siguiente:

1.- Creamos una escena simple, como por ejemplo la que he creado para este tutorial.

2.- A continuación aplicamos los materiales. El suelo tiene el material estándar del Max, mientras que los otros
tres objetos tienen un material más complejo, que explicaremos a continuación..

3.- Analizando el material de la esfera de cristal rojo, vemos cómo está creado:

\1. El color "Ambient" y "Diffuse" están cambiados al color rojo levemente oscuro que queremos para la
esfera.

\2. La opacidad la dejamos al 30, ya que si la bajásemos a 0 perderíamos las sombras.

\3. El brillo especular ciertamente no tiene mayor misterio.

\4. El mapa de reflexión lo creamos con un "Falloff", añadiendo en el color blanco del mismo el nodo de
material/VRayMap, y seleccionando en éste último la casilla "Reflect", que por defecto ya viene seleccionada.

<!-- p. 169 -->

\5. La refracción la conseguimos añadiendo en la casilla del mapa de refracción otro material VRayMap,
pero esta vez marcando en él la casilla "Refract" y añadiendo como color de filtrado el color difuso
añadido anteriormente, pero más claro

Material de la esfera roja

<!-- p. 170 -->

Map #2 (Falloff)

Map #3 (VRayMap)

Map #1 (VRayMap)

NOTA: para poder mostrar correctamente los materiales que tengan mapas de VRay, debemos previamente
seleccionar el motor de render VRay tal y como se indicó en el tutorial Cómo configurar la iluminación global
en VRay y después, en las opciones de los materiales seleccionar como motor de render de la ventana de los
materiales el VRay.

4.- Procedemos a crear una luz en la escena que ilumine desde un lateral para acentuar mucho más el efecto de
las curvas cáusticas.

<!-- p. 171 -->

5.- La configuración de la luz la realizaremos siguiendo los datos marcados en la siguiente imagen.

6.- Según la versión que poseamos de VRay puede que la luz tenga por defecto la cualidad de generar
cáusticas, pero siempre conviene cerciorarse. Para ello, desde el menú de render, bajamos hasta la pestaña
"System" y allí entramos en las propiedades de las luces de la escena pulsando sobre el botón "Light settings...".

<!-- p. 172 -->

7.- Una vez aquí marcamos, si no lo está, la casilla "Generate caustics".

8.- El paso previo a tirar el render es activar en el VRay la opción de calcular las cáusticas que se encuentra en
la pestaña "Caustics", dentro de las opciones de render. Además de activarla, deberemos cambiar los
parámetros que trae por defecto, ya que queda mejor con los utilizados aquí. Podríamos utilizar los valores que
vienen por defecto, pero casi con toda seguridad que no veríamos nada, ya que el multiplicador viene por defecto
en "1", y con una luz normal se necesita de 15.000 a 50.000 para que se comiencen a percibir.

9.- Una vez tirado el render podremos ver una imagen similar a ésta. En mi equipo tardó 1 minuto y 48 segundos.

<!-- p. 173 -->

Tutorial de José Florencio "Slimo"

<!-- p. 174 -->

Tutorial

INTRODUCCIÓN:

En este tutorial pretendo detallar las técnicas aprendidas para crear imágenes de estudio fotorrealistas. No
pretendo que el lector tome al pie de la letra todo lo aquí explicado, sino que le ayude a encontrar sus propias
técnicas para generar imágenes fotorrealistas. Doy por sentado que el lector tiene un conocimiento medio del
software 3dstudioMAX, Vray 1.46 y Photoshop CS.

Inicialmente he dividido el tutorial en tres secciones, pero dejo abierta la posibilidad de ampliarlo en un futuro con
técnicas de texturizado.

José Florencio Güell
slimo@lausseq.com

Temas abordados en este tutorial

Modelado, Iluminación y Materiales.

<!-- p. 175 -->

Composición.
Postproducción.

Modelado,Iluminación y Materiales

PARTE1 Modelado, Iluminación y Materiales:

A diferencia de la mayoría de interiores generados por ordenador donde lo que se intenta es mostrar el conjunto
de la escena con una o varias imágenes, en cambio el tipo de imágenes a la que hace referencia este tutorial lo
que intenta mostrar es un producto ya sea una mesa, silla, nevera, etc etc, con un entorno que adorne el
producto sin perder el objetivo principal, por ello las técnicas aquí descritas su único objetivo es realzar al
máximo el producto que se intenta mostrar.

\- Empezaremos por crear dos cubos de 10x10 metros y 10 cm. de espesor, con una separación entre ellos de 3
metros ese será el suelo y el techo de la escena respectivamente.

<!-- p. 176 -->

\- Partiendo de lo que he explicado, en vez de modelar la habitación completa modelaremos paredes sueltas,
esquinas, paredes con ventanas, con puertas, etc. etc. En el ejemplo he creado un rincón con dos ventanales y
una pared principal con rodapié.
\-

\- Creamos una luz Vray y la ajustamos a una de las ventanas. La clonamos, y la ajustamos a la otra ventana.
Ahora tenemos dos opciones: o emparentamos las luces a las ventanas, o creamos un composite con el conjunto
rincón-luces. Yo personalmente prefiero la primera opción. A este conjunto, a partir de ahora, le llamare "Set". La

<!-- p. 177 -->

razón de hacerlo así es por que a la hora de componer la escena resulta mucho mas sencillo mover esas
porciones de escenario que crear uno cerrado e intentar colocar la cámara.

\- Una vez creado un Set (o varios), los posicionamos para crear una habitación estándar donde empezaremos a
preparar los materiales.
\-

<!-- p. 178 -->

\- creamos una target camera con centro en el escenario y lentes de 42 mm., que usaremos de apoyo para
preparar los materiales.

\- Cargamos el mueble que previamente habremos modelado en otra escena de MAX.

\- Dios dijo ¡hágase la luz!. Nosotros creamos una direct target a la que llamaremos "Sol". Ajustamos. A la escena
le damos intensidad, color y activamos las Vray Shadows. Tambien ajustamos las Vraylights que tenemos en el
Set.
\-

\- Ahora nos iremos a los settings del Vray y activaremos lo descrito a continuación. Buscaremos una
configuración baja para que los tiempos en las pruebas de render no se disparen.

Selecionamos Antialiasing Fixed rated.
Activamos filtro Catmull-Rom.
Activamos Indirect illumination.
La combinacion Irradiance map - Lightcache -después de muchas pruebas- es la combinacion que mas
velocidad-calidad ofrece para este tipo de escenas.
En Color mapping escogeremos el modo Exponential.
Para el Irradiance map seleccionamos Medium.

<!-- p. 179 -->

En Light cache, por ahora dejaremos las Subdivs a 100 y activamos el Pre-filter.

Activamos GI enviroment y dejamos el multiplier a 1.

<!-- p. 180 -->

Activamos Reflection/refraction y lo subimos a 6. La razón es que necesitaremos mucha intensidad en los reflejos
que llegan del exterior.

Subimos el Noise threshold a 0,05.

\- Ajustada la iluminación del entorno empezamos a editar materiales. En este punto no voy a entrar en detalles;
creo que hay muchos tutoriales en la red explicando lo mismo, y en cualquier caso podéis echarle un ojo a la
escena de ejemplo.

<!-- p. 181 -->

\- Una vez ajustados los materiales de la escena la utilizaremos para aplicar y ajustar los materiales de todos los
objetos que vayamos a utilizar en la composición.
\-

<!-- p. 182 -->



<!-- p. 183 -->



<!-- p. 184 -->

Composición

PARTE-2 Composición.

\- El primer paso es cargar el objeto principal en el centro de la escena y ajustar la cámara buscando la posición
que más nos agrade para la composición final.

<!-- p. 185 -->

\- A continuación movemos y posicionamos las paredes alrededor del objeto buscando la estética que más nos
convenga.

\- Cerraremos el resto del escenario con unos cubos para que la luz exterior no afecte a la escena.

<!-- p. 186 -->

\- Cargamos los objetos más relevantes, que ayudarán a dar fuerza a la composición final, y los colocamos en el
lugar que más nos guste.

\-Llegado a este punto, cuando la composición general de la imagen ya esta creada, nos dedicaremos a realzar el
objeto principal con luces. Empezaremos con una luz Spot y una sombra dura, seguido de una o dos luces Vray
con sombra blanda. Es una técnica básica de iluminación con tres luces cuya explicación encontraréis
fácilmente.

<!-- p. 187 -->



<!-- p. 188 -->



<!-- p. 189 -->

\- Una vez iluminado el mueble añadiremos el resto de objetos preparados con antelación. Solo nos queda ajustar
los parámetros de Vray para generar el render final. Yo recomiendo el formato PNG de 16 bits por canal y canal
alfa activado.

<!-- p. 190 -->



<!-- p. 191 -->

Postproducción

PARTE-3 Postproducción

Una vez finalizado el Render pasamos a la fase de postproducción, en la cual usaremos Photoshop CS.
Antes de dejar por concluido el trabajo con el 3dsMax renderizaremos unas capas que nos harán falta para la
postproducción.

Primero de todo cambiaremos el motor de render Vray por el Scanline. Nos vamos a la pestaña de Render
Elements y activamos el canal Difuse y el canal Specular. También activaremos dos Z-buffer. El primero con la
distancia de la cámara al objeto principal, y el segundo del objeto principal al fondo de la escena.

En el editor de materiales creamos un material Estándar con un color gris neutro y un Specular 100-30 y lo
aplicamos solo al objeto principal -en este caso la mesa y sus complementos directos: "Televisor, Video, etc". La

<!-- p. 192 -->

razón de hacer esto es crear unas capas con el Difuse y el Specular solo del objeto principal, para luego
componer y realzarlo en Photoshop.

Ahora desactivaremos todas las luces que tengamos en la escena exceptuando la Spot; no es necesario
desactivar las Vray light ya que estas no generan luz en el Render Scanline. El resultado de las capas debe ser
similar a esto:

Abrimos Photoshop CS y cargamos la imagen renderizada; ahora buscamos una imagen para poner de fondo
que quede coherente en la composición; si es necesario tocaremos un poco la exposición de dicha imagen.

Cargamos ahora las dos capas de Z-buffer y las incluimos como dos canales alfa.

<!-- p. 193 -->



<!-- p. 194 -->

Cargamos el canal Diffuse y Specular y los incluimos como capas. Un truco, ya que en formato PNG ya lleva
incluido el canal alfa para posicionarlas en la imagen lo mas rápido posible. Antes de traspasarla seleccionamos
toda la imagen y le hacemos un borde negro de 1px. Con esta acción, al copiar-pegar ella misma se posiciona en
el lugar correcto.

\-Primero editaremos la capa Diffuse. Para ello ocultamos la capa Specular que editaremos mas adelante.
Seleccionamos la capa Diffuse y la cambiamos de Normal a Color Dodge. En este momento veremos cómo solo
el mueble y los complementos principales se resaltan del fondo con mucho brillo, con lo cual habrá que tocar la
intensidad de la capa para este proceso. Yo prefiero usar el comando Curves ya que permite un mayor control
sobre
las zonas claras y oscuras.

<!-- p. 195 -->

\- Para la capa Specular seguiremos el mismo proceso que para la capa diffuse. Si algunos objetos no queremos
que tengan tanto brillo solo tendremos que seleccionarlo y oscurecer un poco.

\- Este proceso lo podemos repetir tantas veces como brillos queramos en el objeto. Solo tenemos que volver al
MAX, mover la Spot y sacar los brillos allá donde más los necesitemos.

\- Explicación: este método lo ideé debido a que necesitaba realzar el objeto del entorno, pero hacerlo desde el
MAX directamente, ajustando luces y materiales era demasiado laborioso; en cambio de esta forma es un
proceso bastante sencillo, técnicamente incorrecto pero estéticamente aceptable.

\- Una vez ajustadas todas las capas, lo fusionamos todo, y le daremos el toque final a la imagen:
¡enguarrémosla!.
La generación de imágenes sintéticas, o como queráis llamarlas, tienen el inconveniente de que son demasiado
limpias; en cambio la realidad es muy diferente -suciedad, imperfecciones, rozaduras, etc. Pero el tipo de imagen
que estamos generando no es recomendable ensuciarla, ya que en las fotos de estudio reales se intenta
mantenerla limpia y libre de imperfecciones al máximo. Otra diferencia entre una foto y una imagen de síntesis se
encuentra en la cámara. En la realidad genera una serie de imperfecciones -distorsión de lente, aberración
cromática, profundidad de campo- y por
buena que sea la cámara digital o tradicional, estas imperfecciones siempre estarán presentes en mayor o menor
medida, y es lo que vamos a simular a continuación.

\- Empecemos con la profundidad de campo. No voy a extenderme en el tema, podéis encontrar la teoría en libros
de fotografía o en la red. Básicamente se podría explicar como un efecto de desenfoque que se crea a partir del
punto donde hemos enfocado el objetivo, en este caso el mueble. Cuanto mas distancia hay de ese punto, tanto
hacia el infinito como hacia la cámara, el desenfoque es mayor. Para simular este efecto usaremos el Lens Blur.

<!-- p. 196 -->

\- Ha llegado el momento de usar los dos Z-buffer que generemos con anterioridad. Habitualmente se usa solo uno,
pero como sé de antemano cuál es el objeto enfocado, prefiero usar dos Z-buffer ya que me da más control a la
hora de desenfocar el primer y segundo plano.

Seleccionamos Alpha 1.
Ponemos Focal distance a 0.
Ajustamos el Radius.
Añadimos un poco de Noise.

<!-- p. 197 -->

Ajustamos el Brightness. Este parametro es muy importante junto con Blur Focal distance. Con él daremos
intensidad al exterior de la escena.

Añadimos un poco de Noise.

Moviendo estos dos deslizadores conseguiremos que los tres canales RGB se distorsionen en el borde de la
imagen.

Moviendo el Amount aclararemos u oscureceremos las esquinas de la imagen.

\- Una vez simulada la profundidad de campo solo nos queda añadir un poco de aberración cromática. Para ello
usaremos el Lens corrección. Photoshop CS lleva este filtro para disimular y quitar la aberración cromática en las
imágenes reales; yo lo uso para añadírselo a las imágenes 3D y darles así un pequeño toque personal.

<!-- p. 198 -->

Mi único deseo al crear este minitutorial es poder aportar mi granito de arena a toda la comunidad 3D de habla
hispana, espero que con el aporte algunas ideas a otros que como yo, intentan superarse día a día.
La inclusión de la escena de ejemplo lo he visto necesario para que el lector pueda practicar con ella. Todos los
objetos, materiales y texturas incluidos han sido creados por mi. Espero que el lector haga un buen uso de ellos,
y si los va a usar para sus propias creaciones desearía que no los incluyera tal cual, si no que le diera su propio
toque personal.

slimo@lausseq.com

Dideje

<!-- p. 199 -->

Tutorial

Iluminación de Interiores
Autor: Dideje. (Compilado del foro 3Dpoder)

Vamos a iluminar un espacio con luz artificial.
Esta escena es buena porque es sencilla y tiene muchos rincones y zonas dificiles.En las explicaciones no
pondré captura de parametros, sino que los iré diciendo, y poniendo su resultado con el render correspondiente.
Iremos despacio e intentando que quede todo claro.

Contenido

Apertura de la escena y primeros ajustes
Primer resultado con fotones
Luces fotométricas
Pruebas extremas
Resumen sobre luces fotométricas
Algunas características
En cuanto a los fotones...
Iluminación natural
Dudas con Hsp, Dubdivs e Intrp. Samples
Respuestas y otros.

Apertura de la escena y primeros ajustes

Apertura de la escena y primeros ajustes

<!-- p. 200 -->

Abrimos la escena "escena_pruebas" de la carpeta donde la hayamos guardado.

Le damos a render y esto es lo que tenemos:

Las pruebas las vamos a hacer sin AA de momento, para que vaya más rápido.

Ahora activamos la GI y ponemos los siguientes parámetros (buenos para hacer pruebas) en el irradiance.

Min max rate -4 -2
Hsph 20
Inter 40

Ya empieza a verse mejor. Vamos a encaminar nuestros esfuerzos en conseguir más iluminación en general, y
en las zonas oscuras, en particular.

Para aumentar la iluminación lo que hemos hecho es subir el multiplicador de los rebotes secundarios a 0,65, el
deph del direct (número de rebotes) a 6 y el dark del color mapping a 3,5 en modo hsv (probad los otros, que a
mí me ha convencido más este).

<!-- p. 201 -->

Es conveniente siempre subir el dark antes que el multiplicador de los rebotes, ya que si subimos mucho éste,
tendremos un color bled, o fuga de color de un material a otro excesivo.

En general con direct en los rebotes secundarios tenemos muy poco control sobre la iluminación, y a partir de 10
en deph más o menos no notamos incidencia alguna. Yo lo he dejado en 6, pero de 3 a 6 se notaba muy poca
diferencia. Lo ideal será hacerlo con fotones como veremos más adelante.
La iluminación en cuanto a intensidad y equilibrio, zonas oscuras, zonas claras, me ha gustado. No hay reglas
generales para todas las escenas; cada escena es un mundo y requiere sus valores que tendremos que ir viendo
a base de pruebas.

Una vez que tenemos nuestra escena en cuanto a luminosidad convenientemente iluminada (al menos con direct
en los rebotes secundarios) vamos a darle calidad procurando no subir los tiempos excesivamente.

Aquí va la escene renderizada con los siguientes parámetros:

He bajado el max rate a -1, con lo que tendremos más muestras. También he bajado el control thersh a 0,3 (más
precisión en las zonas de cambio de iluminación) y el nrm thersh a 0,4 (un poco más de precisión en los cambios
de normales).
Como veis tiene bastante más calidad.

Hay que tener en cuenta que tiene que existir en equilibrio entre los hsph y las interpolaciones.
Si ponemos un número de hsph bajo (pocas muestras) necesitamos unas interpolaciones más o menos altas
para que suavicen bien los espacios entre muestra y muestra.
Si usamos un número alto de hsph las interpolaciones deben bajar, ya que no son tan necesarias; hay suficientes
muestras y se necesita interpolar menos; además evitamos que se produzcan artefactos por exceso de
interpolaciones (zonas iluminadas en esquinas y cosas así). Evidentemente los tiempos suben con esta segunda
opción.

<!-- p. 202 -->

Aquí está la escena con la calidad final, al menos una calidad decente y con AA adaptative subdivision -1 2.
He subido el min max rate a -3 -1.
Hsph 35.
Interp 45.
El nrm lo he bajado a 0,3.

Aviso que los interiores son jodidos en cuanto a que salgan tiempos espectaculares conservando calidad. En
general yo no suelo subir mucho los hsph, y juego con los nrm, control y dist para meter muestras allí donde
quiero, dependiendo de la escena. Si tiene muchas esquinitas conviene bajar el nrm para que meta más
muestras ahí. En fin, es tener un poco de sentido común y no esperarse tiempos absurdamente bajos con
calidad, porque no se puede.
He editado el post, que no doy con la tecla para escalar esto bien, así que las unidades se quedan en pulgadas
para escenas que hagamos nosotros trabajar en centímetros o milímetros.
Abrimos la escena del principio, activamos GI y ponemos en los rebotes primarios y secundarios global photon
map y representamos (“renderizamos”).

Como hicimos con direct, subimos el multiplicador de los rebotes secundarios a 0,65 y el dark en hsv a 3,5 y
representamos.
Como vemos, la representación es rapidísima y tenemos una idea bastante aproximada de la luminosidad de la
escena.

<!-- p. 203 -->

Voy a explicar ahora los parámetros del global photon map.
La iluminación mediante fotones funciona de la siguiente manera:

Las luces de la escena emiten fotones que chocan con la geometría.
Cada vez que se produce un choque, el mapa de fotones guarda la información. Va creando una especie de
malla de iluminación (un estilo a la malla que te crea la radiosidad del Max) y los parámetros que definen esta
malla son:

Max density: nos dice la precisión de esa malla en un punteo.
Search diste: nos dice la distancia máxima a la que se mira para coger información de luz.
Y max fotones nos dice el número máximo de fotones que se tienen en cuenta para definir la iluminación en un
punteo.

Un ejemplo visual:
Si ponemos max density 1, search diste 5, y max photons 30 y unidades en cm., la luz emite un fotón, ese fotón
choca con la geometría y con precisión de 1 cm. respecto a ese punteo hace una especie de esfera con radio 5
cm., coge 30 fotones que se encuentren dentro de esa esfera y calcula la iluminación en ese punteo.
De ahí la importancia de las unidades, si la escena es en metros, 1.0 en max density significa que la precisión es
de un metro, que evidentemente es demasiado grande para tener calidad de iluminación.
Lo ideal sería poner el max density en 0.0, con lo que la precisión sería perfecta -pero claro- los tiempos suben
mucho. En general hay una relación "mágica" para el valor de max density y search dist, y es 1/5. O sea,
Max density 1.0 Search dist 5.0
Max density 2.0 Search dist 10.0

Si se activa lo de autosearch, Vray lo hace mejor, pero los tiempos también suben.
Los bounces son el número de rebotes. A más rebotes, mejor iluminación, pero más tiempo de render.
El multiplicador es el "brillo" de los fotones; un multiplicador normal.
La pestaña "convert to irradiance map" sirve para que ahora se cojan solo el número de fotones equivalentes al
número de interpolaciones para el cálculo del mapa de fotones. Además la solución es más suave.
Si tenemos max photons 30 y activamos convert to irradiance map con 10 interpolaciones, solo se tendrán en
cuenta 10 fotones, y no 30 (los tiempos bajan) y esto no es lo mismo teóricamente que poner 10 en max photons
y no activar esa casilla. También la solución es más suave (distintos métodos de cálculo).

<!-- p. 204 -->

Si no está activada la pestaña "convex hull área estimate" Vray usa un algoritmo simplificado que puede causar
esquinas oscuras. Si se activa, se soluciona esto. Los tiempos suben, pero ayuda a corregir ese posible defecto.
La pestaña "store direct light" indica el método de cálculo de la luz directa.
Si no lo activamos, la iluminación de las luces de área de nuestra escena serán calculadas mediante fuerza bruta
y los tiempos subirán.
Si lo activamos, el método de cálculo cambia y pasa a calcularse como la luz indirecta, y los tiempos bajan
\-sobre todo si tenemos varias luces. Es parecido a la pestaña "store with irradiance map" de las luces de área. Si
la activas, las luces de área no son computadas mediante fuerza bruta, y se calculan en el irradiance map, con lo
que la representación irá más rápida aunque el cálculo del irradiance map será más lento.
El parámetro Raytrace threshold hace que superficies cercanas (esquinas por ejemplo) sean calculadas
mediante Monte Carlo (calidad). Su valor indica lo que Vray entiende por cercano. Si ponemos 0 no habrá
retrace, y si subimos el valor indicamos que a partir de esa distancia se calcula mediante Monte carlo.
El valor de retrace bounces nos dice cuántos rebotes son calculados mediante Monte Carlo en las zonas
cercanas (definidas mediante el retrace threshold). En general tiene que ser igual a los bounces que tengamos
en la escena. Valores más pequeños pueden causar esquinas oscuras.

Primer resultado con fotones

Primer resultado con fotones

Primer resultado con fotones, sin complicarnos mucho la vida.
Como veis el tiempo ha bajado una bestialidad.
He usado en el primer rebote cálculo con irradiance con los parámetros de la imagen de calidad, que tardó 7
minutos, y en los secundarios, fotones con los siguientes parámetros:

10 Bounces.
Max density 1 y Search dist 5. (O sea, calidad)
Convert to irradiance map activado y store direct light activado.
0.0 en retrace threshold (si hubiese visto que en las esquinas salen artefactos lo hubiese subido, pero ha ido bien
y los tiempos bajan).
Por último el número de subdivs para cada luz es de 200 (400.000 fotones).

Habría que ir probando a ver como afecta el retrace y aumentando el número de fotones o disminuyendo y
aumentando radios de búsqueda...en fin, lo que se os ocurra.

Aquí va la representación con fotones y vemos cómo han bajado los tiempos conservando la misma calidad que
con direc.

<!-- p. 205 -->

Un truquillo que puede venir bien según la escena, y sobre todo se puede usar en animaciones, es calcular las
vralights mediante irradiance. Esto se consigue activando la casilla "store with irradiance map" en el panel de las
Vraylights.

Como veis las sombras son mucho más suaves (también menos reales) pero da el pego para una animación, por
ejemplo. Realmente lo que habría que hacer es no marcar esa casilla y subir las subdivs en el panel para que
suavice más las sombras, pero claro, los tiempos suben que da gusto
Fijaos en el tiempo de está prueba.

<!-- p. 206 -->

Luces fotométricas

<!-- p. 207 -->

Luces fotométricas

Otra escena sacada del foro de Vray. Esta vez es un interior con luces artificiales fotométricas.
Si miráis la ayuda del Max.
Cita:
“3ds max ofrece la simulación de la propagación de luz por un entorno con una base física. Los resultados
obtenidos no son sólo renderizaciones muy reales, también medidas exactas de la distribución de la luz en la
escena.
Las luces fotométricas utilizan valores fotométricos (energía de luz) que permiten definir las luces con más
precisión, igual que si fuesen reales. Puede crear luces con distintas distribuciones y características de color, o
bien importar archivos fotométricos de fabricantes de luces”.
Esto último es lo que hemos usado, archivos fotométricos de un fabricante de luces: Erco

Creamos una luz fotométrica puntual, por ejemplo, y en la distribución elegimos web y seleccionamos el archivo
.ies. Es muy sencillo.

Este tipo de luces dan mucho juego puesto que no son la típica Vraylight, y en interiores -donde son importantes
las luminarias- es más que aconsejable utilizarlas. Además hay muy buenas bibliotecas por la red.

Cogéis la escena de luces fotométricas, hacéis un buen cálculo de fotones y guardáis el mapa. Lo cargáis y
cambiáis el primer rebote a DIRECT COMPUTATION con subdivs = 3

Y aquí la tenéis: tiene mucho ruido, pero el tiempo es más que aceptable. (Ya se sabe: direct computation =
calidad). Si probáis a representar con direct computation, y direct en los rebotes secundarios, no se acaba nunca
la representación.

El cálculo del primer rebote con global photon map sirve para hacer una aproximación a la luminosidad de la
escena muy, muy rápida (ideal para los ajustes previos y para ver el mapa de fotones propiamente dicho). Esto
es muy importante, porque en escenas en las que tengamos distintas luces, con distintos multiplicadores.... lo
que hay que conseguir es una apariencia del mapa similar, es decir, que esté igual de "suavizado".
En la escena de ejemplo esto no ha sido relevante, puesto que las Vraylights son iguales y tienen el mismo
multiplicador, así que la distribución de fotones será igual de suave para cada una de ellas.

Aquí veis un ejemplo de lo que hay que conseguir y lo que hay que evitar.
En el primero veis el mapa de fotones proveniente de cada 4 luces de la escena por separado. Como veis, la
"suavidad" es igual. La luminosidad no es lo que hay que mirar, sino que la proporción claro-oscuro de los
fotones sea igual.
En el segundo veis distintas apariencias del mapa de fotones, y eso es lo que hay que evitar

<!-- p. 208 -->

Aquí está el wire.
He intentado hacer una animación de la escena usando photons en los rebotes secundarios.¡Estos fotones son
una maravilla! Solo hay que guardar el mapa de fotones de cualquier frame. Sirve para toda la escena.
Haced la prueba. Representáis un cuadro con photons en primary y secundary bounces y guardáis el mapa. Lo
cargáis y os vais a otro cuadro, el que queráis, y representáis.
Después de calcular el primer cuadro, guardé el mapa de fotones, lo cargué y puse en el irradiance map
"incremental add to current map".

<!-- p. 209 -->

Como el mapa de fotones sólo hay que calcularlo una vez, subí las subdivs de las luces a 600, y también tuve
que usar retrace. Ahora se ve perfectamente su incidencia. Sin retrace eran bastante más rápidos los cuadros,
pero en las esquinas se notaba la perdida de calidad. Subí el retrace a 3 y listo. También usé "store with
irradiance map" para más velocidad, y la verdad es que las sombras son de bastante calidad. Debe ser por la
cantidad de fotones tan alta y por el retrace.

Aquí tenéis unos cuadros.
La verdad es que ha tardado bastante; primero todo el cálculo de irradiance map tardó 15 minutos, y después,
aquí veis los tiempos por cuadro.
Sobretodo la zona de los aros le ha costado trabajo al Vray, aunque tampoco iba buscando tiempos
espectaculares sino buena calidad, y la verdad que es un gustazo ver 5 segunditos con GI de la buena. on GI de
la buena.

Pruebas extremas

<!-- p. 210 -->

Pruebas en situación extrema

Aquí unas pruebas en situación extrema. Luces blancas blanquísimas, paredes blancas blanquísimas y sofás
rojos rojísimos.
Consiguiendo la misma luminosidad con photons y con direct, el color bleding es muy parecido; incluso con direct
puede que sea más. De hecho, en el foro de Vray han llegado a decir que los fotones en los rebotes secundarios
proporcionan un correcto color bleding.
Está claro que si una escena es mejor representarla con fotones, no voy a representarla con direct por el color
bleding, un problema fácilmente solucionable y que en la mayoría de los casos se debe a malas configuraciones
de iluminación en escenas en las que hay que tener cuidado. Descartar los photons por el color bleding es una
solemne tontería; seguro que se debe a todo menos a los fotones.
Como muestra un botón: lo fácil que es eliminar cuanto se quiera el color bleding en una escena dramática como
esta.

<!-- p. 211 -->

El valor hsph del firs bounce nos indica el número de rayos que se lanzan para calcular la iluminación en un
punto.

De esta manera:

HSphere subdivs: 1 = 1 ray
HSphere subdivs: 2 = 4 rays
HSphere subdivs: 3 = 9 rays
HSphere subdivs: 4 = 16 rays
HSphere subdivs: 5 = 25 rays
HSphere subdivs: 6 = 36 rays
HSphere subdivs: 7 = 49 rays
HSphere subdivs: 8 = 64 rays
HSphere subdivs: 9 = 81 rays
HSphere subdivs: 10 = 100 rays
HSphere subdivs: 15 = 225 rays
HSphere subdivs: 20 = 400 rays
HSphere subdivs: 25 = 625 rays
HSphere subdivs: 50 = 2500 rays
HSphere subdivs: 100 = 10000 rays

Resumen sobre las luces fotométricas

Resumen sobre las luces fotométricas

Deduzco que la iluminación de un interior con luces fotométricas no ha quedado del todo clara, así que va una
explicación breve y concisa.
Empezamos cargando la escena.
Es un pasillo iluminado solo con luminarias fotométricas. Cargáis la escena desde la carpeta donde la tengáis,
seleccionáis un grupo luminaria, lo abrís, seleccionáis la luz fotométrica y seleccionáis en distribución "web" el
archivo "ERCO-83471-TC-9.ies" bajado de Erco, que corresponde a un tipo de luminaria de techo.

<!-- p. 212 -->

Ahora vamos a ajustar la luminosidad de la escena.
Seleccionamos el first y secondary bounces photon map y ponemos una malla pequeña (1,5 puse yo). Ajustamos
el multiplicador de los rebotes secundarios y el valor dark del color mapping.
Mis valores después de hacer algunas pruebas fueron: 0.7 en multiplicador del secondary bounces (bajo, así
evitamos excesivo color bled), y 8 en hsv color mapping.

Render y resultado:

No vemos fotones. Con las luces fotométricas hay que aumentar mucho el valor difuse, en el panel system de las
luces.
Lo aumento a 1000 y este es el resultado: ya vemos los fotones, y hemos dado con un multiplicador adecuado.

<!-- p. 213 -->

Una vez que hemos ajustado la luminosidad de la escena, subimos el número de fotones por cada luz (subdivs =
\400) cambiamos el first bounce a irradiance map, y con valores pequeños (20,40--4,-2) tiramos una prueba para
ver que todo sigue bien.

<!-- p. 214 -->

Ya tenemos la escena iluminada. Solo queda texturizar y meter calidad, tanto en fotones (disminuyendo la malla
\-yo he puesto 0.5, 2.5 -la escena está en centímetros) poniendo algo de retrace threshold (yo he puesto 1,
aunque viendo el resultado, igual tenía que haberlo dejado en 0), y aumentado el número de fotones subdivs =
\750) como en irradiance (un -3 -1,40 -30 con dist 0.3 va bien).

En fin, que tampoco tiene más; con las luces fotométricas solo hay que tener cuidado en aumentar mucho el
valor difuse de las luces.

Aquí tenéis el resultado con texturas y algo de postproducción.

Miniatura de Adjuntos.

Solo decir que para el material de las esferas que hay simulando las luces he usado un Vraylight egz.
Los materiales egz son materiales genéricos que una vez instalados se pueden escoger desde el editor de
materiales.

Son:

Luz.
Cristal.
Material metálico de coche.
Cera.

Ajusté la luz con rgb level 1 y generat GI 2, con un color anaranjado, sin los materiales egz, que os adjunto.
Para instalarlos, descomprimimos y nos vamos a run script dentro del Max. Se puede hacer cogiendo un Vraymtl
y poniendo en el canal difuse un mapa output, ajustando su rgb level, poniendo encima de este Vraymtl un
Vraymtlwrapper y subiendo el valor de generar GI.

Fijaos cómo la creación de shaders wapos es muy sencilla una vez que estamos dentro de una escena. El
material de las teteras en simplemente un gris con un poco de reflexión; lo que pasa que al haber luces y un
entorno realista queda muy bien.
A veces nos desesperamos en conseguir un shader determinado en una escena sin entorno real, y vemos que
no sale. Aun cuando la teoría está bien, simplemente falta ese entorno que da una escena buenamente creada.
(Un hdri, a veces no es tan eficaz).

\-Archivos adjuntosPara cargar los materiales egz, ir a maxcript-run script y seleccionad el archivo .mzp. Tras hacer esto tienen que
aparecer 4 nuevos materiales dentro del editor.

First diffuse bounce.
Multiplier: Multiplicador de los rebotes primarios.

Algunas características

<!-- p. 215 -->

Irradiance map:
Min rat: controla el número de muestras (pasadas) junto con el Max rat. A mayor número de muestras, mejor
calidad de render.
Max rat: a menor valor (-2) mejores tiempos pero peor calidad.
Control thresh: a menor valor, más definición en zonas de cambio de iluminación.
Nrm thresh: a menor valor, más definición en los cambios de normales.
Dist thresh:
HSph. Subdivs: Con un número alto de HSph Subdivs, las Intrp. Samples deben ser bajas para evitar que
aparezcan artefactos (iluminación en esquinas). Un valor alto proporciona mayor calidad en la representación,
pero peores tiempos. (No sé exactamente que hace)
Intrp. Samples:
Secondary bounces:
Multiplier: Controla la iluminación de los rebotes secundarios. Un multiplicador muy alto provoca un color bled o
fuga de color de un material a otro excesivo.

Direct computación:
Subdivs: Nos dice los rayos que serán lanzados en el segundo rebote. Si el número es igual o menor que el
HSph. Subdivs. se lanzan los mismos rayos que HSph; si es mayor se lanza el valor de subvids.
Se recomienda dejarlo en 1, porque así no aumentan los tiempos y no suele ser necesario lanzar más rayos.
Depth: número de rebotes de cada rayo. A mayor número mejor iluminación.

Fotones:
Bounces: es el número de rebotes, a más rebotes mejor iluminación pero más tiempo de render.

Auto Search dist: Vray calcula la distancia. Este proceso consigue buenos resultados pero empeora los tiempos
de render.

Search dist: Radio de acción de los fotones. Hay que tener en cuenta la escala del archivo (metros, cm.)

Max photons: Número de fotones generados en ese radio.

Multiplier: El multiplicador es el "brillo" de los fotones; un multiplicador normal.

Max density: Controla la precisión del choque del fotón con la geometría. La luz emite un fotón, ese fotón choca
con la geometría y con precisión de 1 cm. (el valor que tengamos en Max density respecto a ese punto) hace una
especie de esfera con radio 5 cm. (el valor que tengamos en Search dist), y coge 30 fotones (el valor que
tengamos en Max photons) que se encuentren dentro de esa esfera, y calcula la iluminación en ese punto.
De ahí la importancia de las unidades. Si la escena está en metros, 1.0 en max density significa que la precisión
es de un metro, que evidentemente es demasiado grande para tener calidad de iluminación.
Evidentemente, lo ideal sería poner el max density en 0.0, con lo que la precisión sería perfecta, pero los tiempos
suben mucho.
En general hay una relación "mágica" para el valor de max density y search dist y es 1/5
O sea Max density 1.0 Search dist 5.0 / Max density 2.0 Search dist 10.0

Convert to irradiance map: Coge solo el número de fotones equivalentes al número de interpolaciones. La
solución es más suave.

Intrp. Samples: si tenemos max photons 30 y activamos convert to irradiance map con 10 interpolaciones, solo se
tendrán en cuenta 10 fotones y no 30. Los tiempos bajan.

Convex hull área estimate: si no está activada, Vray usa un algoritmo simplificado que puede causar esquinas
oscuras; si se activa se soluciona esto. Los tiempos suben pero ayuda a corregir ese posible defecto.

Store direct light: Si no lo activamos, la iluminación de las luces de área de nuestra escena serán calculadas
mediante fuerza bruta, y los tiempos subirán.
Si lo activamos, el método de cálculo cambia y pasa a calcularse como la luz indirecta, y los tiempos bajan
(sobre todo si tenemos varias luces).

Retrace threshold: Hace que las superficies cercanas (esquinas, por ejemplo) sean calculadas mediante Monte
Carlo (calidad). Su valor indica lo que Vray entiende por cercano. Si ponemos 0 no habrá retrace, y si subimos el
valor indicamos que a partir de esa distancia se calcula mediante Monte Carlo. Un valor 0,0 mejora los tiempos
de render.

Retrace bounces: nos dice cuántos rebotes son calculados mediante Monte Carlo en las zonas cercanas
(definidas mediante el retrace threshold). En general, tiene que ser igual a los Bounces que tengamos en la
escena. Valores más pequeños pueden causar esquinas oscuras.

<!-- p. 216 -->

Color Mapping
Hay 3 tipos de color mapping y a rasgos generales:

Linear: quema las zonas de luces y cercanías.

Exponencial: corrige esa sobrexposición, pero satura los colores.

HSV exponencial: corrige la sobrexposición y mantiene la correcta saturación.

Dark multiplier: aumenta la iluminación general de la escena en las zonas de sombras.

Bright multiplier:

\- "Direct Computation" del Vray: más o menos, lo que significa es: no hagas un submuestreo --> Calcula TODOS
los píxeles de la representación. Por lo tanto, no se produce interpolación para calcular los píxeles intermedios.
Viene a ser (a efectos de colocación de muestras) como colocar un 0/0 en el Irradiance Map.
\- Mapa de Irradiación: viene a significar algo así: calcúlame SÓLO las muestras que yo considere necesarias.
Especificando el mínimo de muestras al que puedo llegar -el máximo- qué criterios debo seguir para disponerlas,
y una vez que las tenga colocadas, utilizar un cierto número de rayos para calcular su iluminación.
Al NO haber muestras en todos los píxeles de la representación, es necesario interpolar para asignar la
iluminación a los píxeles que quedan.

Min/Max Rat: especifican la cantidad de muestras MINIMA/MAXIMA que puede haber por píxel. Si te fijas en los
renders de abajo (están sacados de Brazil, pero es lo mismo). En el primero el número de puntos rosa
(MUESTRAS) es muy poco denso, mientras que en el otro es más denso. Esto es porque en la imagen con más
muestras he puesto un min. rat más alto, es decir "Como MINIMO tienes que colocar tantas muestras cada
tantos píxeles".

¿Ves los tres cuadrados rosas en el primer render? Es una zona (render a medias sobre otro render) a 0/0, es
decir, TODOS los píxeles son muestras, y por tanto todos son tenidos en consideración para el cálculo.

El asunto está en utilizar el mínimo número de muestras posibles (menos cálculo, menos tiempo de render), y
aún así sacar buenos resultados. Un MÁXIMO de 0 significa en los motores: si la zona LO NECESITA, coloca
una muestra en cada píxel. Un máximo por encima de 0 (1, 2, etc.) supone entrar a nivel subpixel, cosa que muy
pocas veces está justificado.

ClrThreshold y Normal Threshold son números que especifican la posibilidad de añadir más muestras según la
diferencia de color de dos muestras cercanas o el ángulo que formen. Según la representación, a veces es útil
utilizar uno u otro criterio para añadir muestras en las zonas difíciles.

El valor del Dist threshold ayuda a añadir muestras cuando tienes dos objetos cercanos, por ejemplo una caja
pequeña sobre otra caja. Aumentando el valor del dist. threshold se añadirán más muestras en esa zona cercana
a la "unión" de ambos objetos. El valor dist añade muestras en todas las esquinas de nuestra escena, por lo que
su importancia es FUNDAMENTAL. Recordad que ya dijimos que este valor funciona al contrario que los otros.
Más alto, más precisión. Los otros, más bajo más precisión.

\- Mapa de Irradiación: sería algo así como una textura que le indica al programa la iluminación de los distintos
objetos. De todas formas ten esto en cuenta: el cálculo se realiza sólo en unos píxeles determinados. Estos
píxeles se corresponden con un objeto, pero hay muchos puntos que por no aparecer en la representación (si un
objeto está detrás de la cámara, por ejemplo) no habrán sido calculados. En estos puntos el mapa de irradiación
tendrá grandes carencias; intentará suplirlas con interpolación, pero el resultado será malo.

<!-- p. 217 -->

Y ahora explico un poco lo de first bounce difuse, lo de los hemisferios, qué son los rayos, etc., etc.
He dibujado unos esquemas. Los he visto en más de una ocasión por ahí, pero como no he podido localizarlos
he acabado dibujándolos "grosso modo".

El primer esquema representa la iluminación directa sobre una muestra. Nada que señalar, es una línea recta
que une el punto de luz con la muestra.

<!-- p. 218 -->

El segundo esquema representa la iluminación difusa. Partiendo de una muestra (situada evidentemente en un
determinado plano), se genera un hemisferio a su alrededor, y prolongando las líneas que van desde la muestra
hacia los distintos puntos del hemisferio, se realiza una "búsqueda de iluminación". Estas líneas son los tan
mencionados RAYOS (Hsph Subdivs). Su distribución a lo largo del hemisferio no tiene por qué ser uniforme.

En el tercer esquema tenemos una muestra de una escena. Partiendo de esa muestra se genera el hemisferio y
se lanzan los rayos. Si te fijas, sólo he dibujado el PRIMER REBOTE DIFUSO, pero el motor de render es
configurable para generar más rebotes y así poder calcular la iluminación de esa muestra de una manera más
realista.
La luz va perdiendo energía a medida que rebota en los objetos; por eso, para conseguir realismo no es
necesario configurar un número muy elevado de rebotes, ya que a partir de cierto número apenas tienen
incidencia en la escena.

Y aquí viene la gran diferencia con respecto al mapa de fotones. El mapa de Irradiación se calcula en sentido
inverso a la iluminación. Es decir, empezamos a trazar rayos a partir de la muestra. El mapa de fotones parte de
los puntos de luz (necesita generadores de fotones). En el proceso del mapa de fotones NO se tienen en cuenta
los píxeles de la representación. Es una simulación más intuitiva del comportamiento de la luz, pero el número de
fotones que debe generar una fuente de luz para lograr la misma calidad que el mapa de Irradiación es brutal.

Hay que darse cuenta de que con el Mapa de Irradiación, los píxeles de la representación recibían rayos y rayos.
Mediante el mapa de fotones todo depende del número de rayos que mediante rebote hayan llegado a esos
puntos.
Por el mismo motivo, el guardado del mapa de fotones es independiente de la representación en sí.

<!-- p. 219 -->

En cuanto a las interpolaciones, digamos que después de calcular muestras, rayos, etc., etc. y tener por fin los
valores de cada muestra, hay que averiguar qué valores van a tener el resto de los píxeles de la representación
que no tenían una muestra asignada. Para eso, se produce una interpolación entre los valores de las muestras.

Imagínate que en un extremo tienes una muestra de color negro y en el otro una de color blanco. El PC haría un
gradiente que iría de negro a blanco para rellenar la zona que no ha sido calculada.

El problema del Interpolate samples es que si lo aumentas demasiado alcanzará a más muestras a la hora de
interpolar, y generará una especie de desenfoque buscando una representación continua. Esto influye
negativamente en la calidad de la representación y puede producir (p. ej.) artefactos luminosos en zonas donde
no deberían existir. Si el valor es muy bajo, se respetará más el valor inicial de las muestras, y dará la sensación
de que hay un montón de pequeñas manchas oscuras y claras en la escena. Aunque aumentes el número de
rayos y de cálculo en general, siempre va a haber una diferencia de color entre muestras cercanas, y eso se
nota. No puedes pasarte ni quedarte corto.

¿Pocos rayos, o pocas muestras, o poca interpolación?.

Partiendo del hecho de que cada escena es un mundo, creo que, lo mejor es optar por un término medio. Un
exceso o una falta de cualquiera de esos tres ingredientes suele dar lugar a problemas. Más rayos y más
muestras aumentan los tiempos de render. Sin embargo la interpolación apenas supone cálculo, por lo que en
principio, y sobre todo gracias al guardado de los mapas, siempre podremos realizar más pruebas con este
último aspecto.

El valor de las interpolaciones NO ES GUARDADO NI CALCULADO en el irradiance map, por lo que podemos
guardar nuestro irradiance map y jugar con el número que queramos, pues se computan durante la
representación.

En cuanto a los fotones...

Cosas que tenéis que tener en cuenta: el valor de retrace threshold (ya sabéis que con él las esquinas se
calculan con direct computation y ganamos calidad en detrimento del tiempo) y el valor de retrace bounces son
computados durante el cálculo del irradiance map.Por lo tanto, podéis hacer un cálculo de fotones, guardar el
mapa y poner el primer rebote en irradiance map y variar estos valores, pues se computan ahí y no en el cálculo
de fotones.
Max photons y search dist tampoco se computan en el cálculo de fotones.
Si tenéis ambos rebotes en global photon map, guardáis el mapa y podéis variar estos valores pues se computan
en el proceso de render. Esto es buenísimo para hacer nuestras pruebas.

Lanzamos muchísimos fotones y guardamos el mapa; entonces variamos esos valores, y nos ahorramos todo el
cálculo del lanzamiento de fotones.
Si tenéis el primer rebote en irradiance map, estos valores se computan ahí, así que también podéis guardar el

<!-- p. 220 -->

mapa de fotones e ir variándolos. Abajo tienes dónde está la casilla "check sample visibility" que previene los
artefactos en algunos casos.

En cuanto a qué significa el bright multiplier del color mapping, pues es un multiplicador para las zonas
iluminadas de la escena.

El mapa de fotones es totalmente independiente de la resolución del render (los píxeles, vamos). Es igual
calcularlo a 10 x 10 que a 1000000 x 1000000, además de que tarda lo mismo, claro. Tampoco hace falta un
mejor mapa de fotones para una resolución más alta. Lo mejor es calcular el mapa de fotones con un max
density pequeño y muchos fotones, guardarlo y después variar el search dist a nuestro gusto y usar retrace si
vemos que salen artefactos en las esquinas. (También podemos aumentar el número de fotones, depende lo que
consuma más tiempo).
En definitiva, el mapa de fotones depende de las unidades de la escena, no como el irradiance map, que sí tiene
una relación directa con los píxeles de salida.

Iluminación natural

Vamos allá con la iluminación natural.
La escena es "Luz_natural_inicio.max". La cargáis y escogéis Vray como renderer.

Ya está más o menos texturizada. Es mejor iluminar con texturas, porque si lo hacemos todo en blanco después
pueden salir problemas, aunque depende mucho de la experiencia, claro.
He puesto un suelo de madera con glossy (desenfoque en el reflejo), aunque ahora de momento no lo tiene, para
que las pruebas vayan más rápido -solo reflexión. Al final se lo añadiremos.
Y después, a las primitivas les he puesto un material gris con reflexión -como aluminio o algo así- que queda
bien. Lo demás blanco.

Como veis, hay dos luces en la escena. Una direccional a modo de sol, y una Vraylight en el hueco con la opción
skylight portal, que lo que hará es meter más y mejor luz indirecta en nuestro interior.
La Vraylight cogerá los valores del enviroment de GI. Estas luces tienen como multiplicador 1.
He dejado el enviroment de Max con un tono azulado.
En general, vamos a dejar todos los multiplicadores de las luces en 1, y también el enviroment .

Ahora vamos a ver los fotones de cada luz por separado.

Empezamos con la Vraylight, así que apagamos el sol.
Activamos GI y ponemos global photon map en el first bounce y secondary bounce, ya que vamos a usar
fotones. (Os dejo a vosotros que hagáis pruebas con direct.) El multiplicador de los rebotes secundarios depende
de la escena, pero no lo subiremos mucho por el color bled. Aquí, como tenemos paredes blancas y el suelo de
madera que puede producirlo, lo he puesto a 0.65.

Para iluminar la escena, lo que vamos a hacer es usar el color mapping hsv. Por norma general hay que subir el
dark entre 10 y 15. Yo lo he puesto a 12.

La configuración del global photon map ya sabéis:
Max density bajo (lo he puesto en 1).
Searchi dist 5.
10 bounces.
Retrace 0.

Las opciones de la derecha, las 3 activadas.

Representamos:

<!-- p. 221 -->

Como veis el mapa de fotones es muy malo.
Hemos dejado el número de fotones por defecto (subdivs en el panel system) en 150 (150 x 150 = 22500)
Por lo general no bajaremos de 1000 subdivs en ninguna luz para tener algo de calidad; lo suyo sería subirlo
más.
Subimos a un millón de fotones lanzados. Ya veis que el resultado es mucho mejor.

Ya hemos acabado con la Vraylight. La apagamos, encendemos el sol, y vamos a ver el mapa de fotones que
produce. Subimos las subdivs a 1000 como la Vraylight y lanzamos render.

El mapa de fotones sigue siendo muy malo, porque las luces standar (omnis, direct, spot) necesitan bastantes
más subdivs que las Vraylight para alcanzar la misma suavidad.
Recordemos que lo que hay que conseguir con el mapa de fotones cuando hay más de una luz, es que la
contribución de cada luz sea similar (esté igual de suavizada la solución del mapa).
Subimos las subdivs a 3000 y lanzamos render.

<!-- p. 222 -->

Miniatura de Adjuntos

Como vemos el mapa de fotones de la Vraylight y del sol están más o menos igual de suavizados (mismo
contraste, zonas oscuras y claras). Fijaos sobre todo en la pared de la derecha, que es donde mejor se aprecia.
Por cierto, han salido un par de manchas blancas en el mapa del sol, espero que no den problemas.
Ahora vamos a activar las dos luces y calcular el mapa de fotones conjunto, para guardarlo y poner el primer
rebote en irradiance map y darle calidad al asunto.

Lanzamos render y guardamos el mapa (o bien activamos el autosave, o después del render le damos a save to
file). Cargamos el mapa de fotones con la opción from file y lo dejamos cargado.
Miniatura de Adjuntos

Con el mapa de fotones cargado, cambiamos el primer rebote a irradiance map y ponemos unos valores bajos.
Yo he puesto hsph 20 intrp 40 con un -4 -2.
Lanzamos render

Miniatura de Adjuntos
No está mal, así que vamos a subir un poco el irradiance, y yo lo dejo aquí.

Tal vez habría que haber usado algo de retrace porque el mapa de fotones no está muy allá.
Yo aumentaría las subdivs de la Vraylight a 2000 y el sol a 5000 por lo menos, y tal vez subiría más el color
mapping, que el cuartillo ese ha salido un pelín oscuro.

He puesto el glossy de la madera a 0.75, y AA adaptative 0 2 y los valores del irradiance:
control y nrm 0.4
dist 0.25 -3 -1
hsph 35 intr 35

Aquí tenéis la escena con direct en los rebotes secundarios y los mismos valores que en mi escena anterior.
Mismos rebotes, mismo color mapping, mismo multiplicador en los rebotes y mismo Irradiance map, claro. Ya dije
que era bajo para que veáis lo que puede hacer el mapa de fotones.

Me he entretenido un rato en mejorar la iluminación, sobre todo en conseguir iluminar el cuartillo ese bastante, y
no producir quemazón en la entrada de luz, además de ajustar una calidad media-alta en la representación.

<!-- p. 223 -->

Dudas con Hsph. Subdivs e Intrp. Samples

Intentaré explicar lo mejor que pueda en qué consisten los parámetros Hsph. Subdivs e Intrp. samples.

Empezamos con las Hsph. Subdivs.

Básicamente, un raytracer lo que hace es lanzar rayos (primary rays) desde el punto de vista del observador (la
cámara). Entonces se va viendo cada rayo en qué punto colisiona. En un raytracer sin soporte para GI, una vez
que el rayo intersecta en un punto de una superficie, se calculan los componentes de la iluminación para dicho
punto (diffuse, specular...), y listo. En situaciones en las que se tenga que calcular una reflexión o una refracción,
se vuelve a lanzar otro rayo (secondary rays) para llevar a cabo dicho cálculo (en realidad se lanzan tantos rayos
como máxima profundidad le demos a la reflexión). Vale, esto es en un raytracer donde no se soporta GI. Ahora
veamos el caso de la GI.

Al igual que antes, se lanza un rayo desde la cámara y éste intrsecta en algún punto de una superficie. Llegados
a este punto es donde se encuentra la gran diferencia entre calcular o no la GI. Sin GI, dije que se calculaba la
iluminación para ese punto y listo. Pues bien, con GI, lo que hay que hacer es ver la contribución de toda la
escena en la iluminación de dicho punto. ¿Cómo se hace esto? Pues básicamente lanzando más rayos
(secondary rays) desde el punto en cuestión.

La pregunta ahora es: ¿cuántos rayos y en qué dirección lanzamos dichos rayos? Aquí es donde entra en juego
el parámetro Hsph. Subdivs. Lo que se hace es que se construye un hemisferio (semiesfera) imaginario sobre el
punto actual con una dirección igual a la normal de dicho punto. Esta semiesfera tendrá tantas subdivisiones
como le indiquemos en el parámetro Hsph. Subdivs (es como cuando construimos una esfera y le asignamos el
número de segmentos). Evidentemente, a más subdivisiones, más rayos secundarios se lanzarán, por lo que la
GI será de mayor calidad, y por supuesto, el tiempo de cálculo será mayor. Cabe aclarar que si pones un número
de 50 subdivisiones, en realidad no estás lanzando 50 rayos sino 2500, es decir, el número de rayos lanzados
será igual a Hsph. Subdivs al cuadrado.

Otra pregunta que uno se puede hacer es en qué dirección salen estos rayos. ¿Se distribuyen uniformemente
sobre el hemisferio? Lo cierto es que no. Lo que se hace es lanzar rayos aleatoriamente utilizando el algoritmo
QMC (Quasi Monte Carlo). Para ilustrar todo esto, os adjunto la Imagen 1 (abajo) donde podéis ver el punto que
se está calculando actualmente (la esfera roja), el hemisferio que utilizaremos para lanzar los rayos secundarios,

<!-- p. 224 -->

y los propios rayos secundarios.

Como veis en la imagen, algunos rayos impactarán en el muro de la izquierda, otros impactarán en el suelo,
otros en la esfera y otros lo harán con el environment (en este caso es de color azul). Así, si un rayo impacta en
el environment (color azul), ese azul contribuirá en una determinada cantidad al color del punto que estamos
tratando actualmente (el punto representado por la esfera roja).

Ahora voy a intentar explicar el significado de Intrp. samples.
Vray almacena un determinado número de muestras (samples) en el irradiance map. El número de estas
muestras y su disposición espacial va a depender de forma directa (aunque no es lo único que determina esto)
de los parámetros Min. rat y Max. rat. Evidentemente, cuantas más muestras se almacenen en el irradiance map,
mayor será su calidad, pero más tiempo tardará en calcularse. Si os fijáis, cuando le damos a render, Vray
empieza a calcular el irradiance map. El número de pasadas que se utilizarán para calcularlo dependerán, como
he dicho, de los parámetros Min. rat y Max. rat. Así, si ponemos unos valores de (-3, 0), Vray calculará el
irradiance map en 4 pasos. Esto lo podéis ver cuando Vray empieza a representar, cuando pone Current task:
prepass 1 de 4, etc. Pues bien, imaginemos que Vray ya ha terminado de calcular el irradiance map. Ahora llega
la hora de utilizar este irradiance map para generar la escena final. Aquí es donde entra en juego el parámetro
Interp. samples.
Lo que Vray hace es interpolar los samples del irradiance map. Cuanto mayor sea la interpolación, más suave
será la imagen final. Una interpolación demasiado baja, da como resultado los típicos manchurrones. Esto es
porque al realizar una interpolación pobre, la diferencia de intensidad entre samples es demasiado acusada.

Para entender mejor esto, mirad la Imagen 2. En ella podéis observar dos samples sacados del irradiance map
(estos son los colores de los extremos, es decir, el negro y el gris claro). En la fila de arriba, hemos especificado
una interpolación de 4, por lo que se generan 4 samples intermedios, resultantes de la interpolación de los
samples originales (los 2 de los extremos). En la fila de abajo, tenemos los mismos samples originales, pero en
esta ocasión hemos especificado una interpolación de 2, por lo que Vray genera 2 samples intermedios.

Ahora, aplicamos un gaussian blur (todo esto lo he hecho en Photoshop, por lo que no quiere decir que Vray
haga esto) a la fila superior y a la inferior (ver Imagen 3). Como podéis observar, en la fila en la que hemos
utilizado un mayor número de interpolaciones, la transición entre un sample y otro es suave, mientras que en la
fila inferior, donde utilizamos únicamente 2 samples de interpolación, se nota la transición de un sample a otro lo
cual genera los típicos manchurrones que mencioné anteriormente.

La verdad es que explicar esto de forma que se entienda bien es bastante complicado; y si encima uno no llega a
entender el Vray al 100% (para eso tendría que haber programado un renderer con soporte GI, y lo máximo a lo
que llegué fue a un raytracer bastante simple). Esto quiere decir que ciertas cosas que he dicho no pueden ser
del todo exactas.

Imagen 1

<!-- p. 225 -->

Imagen 2

Imagen 3

Y aquí, los parámetros y la diferencia entre las dos imágenes finales. Ambas tienen AA -1 2.

<!-- p. 226 -->

Y aquí, los parámetros y la diferencia entre las dos imágenes finales. Ambas tienen AA -1 2.
Miniatura de Adjuntos.

<!-- p. 227 -->

Respuestas y otros

... En cuanto al truco mágico de sumar hsph y inter., yo también estuve un tiempo intentando buscar una
correspondencia, pero no existe, depende mucho de la escena, y he visto interiores muy bien configurados que
no siguen ningún tipo de reglas. Lo de que a partir de 40 hshp la representación se vuelve infinita, pues bien, los
tiempos suben pero a veces es necesario subir mucho para conseguir calidad. He visto interiores hasta con 80
hsph.

... En cuanto a lo de poner el search dist tan grande (que abarque toda la escena), habría que hacer pruebas y
comprobar si merece la pena. Las pruebas que he hecho han aumentando un poco el tiempo de render y no se
consigue más calidad.

... Lo de que sólo te salga el color mapping lineal y exponencial, ya se ha comentado muchas veces. El color
mapping hsv se añadió en la versión 1.09.03i.

... Con Photoshop no tengo una mecánica definida. Depende de la imagen y lo que quiera conseguir. Os pongo
aquí cosas que suelo tocar aleatoriamente:

Máscara de enfoque, por supuesto.
Niveles.
Saturación.
Balance de color.
Brillo, contraste.
Algo de glow, y algo de ruido.

... Con Photoshop CS suelo usar también lo de shadow-highlith y photo filter. Voy probando hasta que veo que
me gusta más el resultado, y la verdad es que suele mejorar siempre con respecto al render original.

... Aquí os pongo una imagen de un interior que me gustó mucho, y el retoque que yo le hice. Es cuestión de ir
probando y darle el toque que queramos. Muchas cosas se hacen mucho más rápido en Photoshop.

... Han preguntado por ahí sobre el color bled, y como tiene mucha relación con iluminación de interiores lo
pongo aquí para que siga contribuyendo a este manual. Son unas cuantas estrategias para controlar el color
bled. No os fijéis en la calidad de las imágenes, que han sido pruebas muy rápidas.

<!-- p. 228 -->

La escena está en en directorio de Max. Puedes cargarla desde aquí. (Es Max 6) ¿De qué? Cambiar todo a sólo
directorio, por las distinats versiones de max)

<!-- p. 229 -->

... Es un poco complicado de explicar:
Los 2 son métodos para escoger las muestras que servirán de base a la interpolación. El precalc overlapping es
posterior al quad-balanced, y arregla algunos problemas que tenía éste, además de que en velocidad son
parecidos e incluso más rápido. Así que a priori es la mejor opción.

... Para luces fotométricas, fotones, y demás métodos que tengan que ver con geometría (irradiance no -por
ejemplo- aunque siempre es aconsejable), lo importante es que la escena esté construida en unidades reales.
Una habitación de alto 3 metros, no 30 y cosas así.
Es importante también que esas unidades sean unidades pequeñas (centímetros o milímetros) ya que con
metros la precisión no es la misma.1 milímetro es 0.001 metro, que es un valor muy próximo a 0 y Vray se hace
un lío al ser un valor tan pequeño. No te digo nada si es 0.1 milímetro. De todas formas, en principio no tendría
que haber muchos problemas al usar metros, pero es mejor no usarlos; al menos con escenas en las que
necesitemos unidades pequeñas. (Si estoy modelando e iluminando una lámpara que mide 30 cm. por ejemplo,
lo suyo es usar cm. o mm.)

... Suavidad en las sombras: luz más grande, sombras más suave. Luz más pequeña, sombra más dura.
Lo normal es colocar una Vraylight por hueco, porque así es como sucede en la realidad, y las sombras dentro
del espacio serán más correctas. Con una sola luz será también más difícil conseguir la misma calidad. De todas
formas, si hay demasiados huecos siempre es una solución a considerar el poner menos luces que una por
hueco.

... Lo del parpadeo en animaciones pues es por:
1.versión pirata
2.antialiasing
3.poca calidad

... Optimizar una animación para que haya calidad y no suban mucho los tiempos es complicado, y hay que
conocer muy bien qué tocar para que la calidad no se resienta.

... Lo del min max rat es muy sencillo y fácil de entender. A ver si lo pilláis
Empezamos con:
MIN RAT 0
MAX RAT 0
Esta es una solución sin interpolaciones, o sea, le estamos diciendo a Vray que meta una muestra por cada píxel
SIEMPRE.

MIN RAT -1
MAX RAT- 0
Aquí estamos diciéndole que meta como mínimo una muestra por cada 2 píxeles (-1) en las zonas donde vea
oportuno, y como máximo una muestra por píxel (0). O sea, que en una escena con zonas planas -paredes por
ejemplo- con esta configuración Vray en esa pared meterá una muestra cada 2 píxeles (ahorrándose tiempo),
porque en esas zonas no necesitará más. Aquí es donde Vray va a interpolar, porque le falta la información de
un píxel intermedio (se inventará más o menos ese píxel teniendo en cuenta el valor de interpolaciones que
tengamos).Y como mucho, en detalles pequeños meterá una muestra por píxel. Está claro que esta solución es
más rápida que la anterior.

MIN RAT -2
MAX RAT -1
Pues ya es fácil de seguir. Aquí como mínimo meterá una muestra por cada 3 píxeles (-2). O sea, en toda la
escena, como mínimo, hay una muestra por cada 3 píxeles. Y como máximo, le decimos que meta una muestra
cada 2 píxeles. Así que en detalles pequeños por ejemplo, no se tendrá que inventar el píxel que le falta. Si se
cuentan las muestras que mete Vray, son menos que los dos casos anteriores, así que esta configuración es
más rápida aún.

MIN RAT -5
MAX RAT 0
Esta es una configuración para escenas en las que haya de todo. Grandes zonas planas y detallitos pequeños.
Con -5 le estamos diciendo que meta una muestra cada 6 píxeles en esas zonas grandes y planas; así que
ahorramos tiempo porque en esas zonas no se necesitarán más, y las que se invente Vray serán más o menos
correctas. Si ponemos -3 por ejemplo, ya estamos metiendo más muestras a la fuerza, y estamos obligando a
Vray a que meta como mínimo una muestra cada 4 píxeles; así que aunque no lo necesitara, él meterá siempre
como mínimo eso. Y con el 0, pues decimos que en las zonas donde lo necesite llegue a meter muestra por
píxel, con lo que los pequeños detalles saldrán bien.

MAX RAT 1

<!-- p. 230 -->

Aquí entramos a nivel subpixel y muy raramente es necesario. Aquí decimos que llegue a meter como máximo 2
muestras por píxel, y es muy difícil que necesitemos esa cantidad, porque en un solo píxel los cambios de
iluminación son muy, muy pequeños.

En general, siempre es bueno hacer un recorrido amplio de max rat a min rat, porque así le damos a Vray la
oportunidad de que ahorre tiempo. Es mejor un -4 -1 que un -2 -1. Será bastante más rápido y posiblemente la
calidad sea muy parecida (siempre dependiendo de la escena, claro).

Todo esto tiene que ver también con la resolución. No es igual un píxel a 640 x 480 (hay más partes de la escena
dentro) que un píxel a 3000 x 2000, donde coge menos. Por tanto, siempre hay que pensar en la resolución de la
representación. Un -1 en max rat puede ser excesivo a una resolución de 3000 e insuficiente a una resolución de
\500. En general, partiendo de la resolución de 640 x 480, cada vez que doblemos esa resolución podremos subir
un valor al min max rat. Por ejemplo, a 640 x 480 usamos MIN RAT -3 MAX RAT 0.

Si queremos tirar la representación a 1200 x 1000 más o menos, con MIN RAT -4 MAX RAT -1 tendríamos
calidad parecida. Esto es igual que representar a 640, guardar el irradiance, y cargarlo y representar a 1200.
Por esta regla de tres, a una resolución de 5000, a lo mejor llegamos a un MAX RAT -5 o -6 y claro, tendríamos
poca calidad. Es una orientación para que veamos que el irradiance depende de la resolución de la
representación. Yo rara vez subo de -2 en el max rat, tire a la resolución que tire.

Para el cálculo de fotones da igual la resolución. Es igual tirarlo a 320 que ha 5000 (tardará más tiempo en
representar, pero no el cálculo).
Tengo este problemita con esta escena, aclaro que es irradiance (nada de fotones). Tiene una direct target como
sol, y una Vraylight en la ventana con el skylight activado.
La opacidad la controlas con el color de refracción. Blanco es totalmente transparente y negro es totalmente
opaco.
Igual con la reflexión, si no quieres que refleje nada, pon el color de reflexión en negro.
Para los estores podrías usar las opciones de traslucidez del material Vray (lo he tocado poquísimo), o usar
refracción gris o glossy en la refracción. Sería un material similar a las cortinas.
Para el material cromado tienes que ponerle reflexión y nada de refracción.

... La experiencia me dice que es más fácil obtener calidad con más luces en la escena. Si en una habitación con
un hueco ponemos una direct a modo de sol exclusivamente, es más difícil obtener resultados buenos que si
además de esa luz ponemos una Vraylight en el hueco. En general, colocar Vraylight en nuestra escena nos dará
más calidad. (Y se come los artefactos que da gusto). Una práctica habitual en escenas con una sola entrada de
luz es colocar tres luces:

Una luz direccional a modo de sol.
Una luz Vray en el hueco.
Una luz Vray tras la cámara simulando la luz que viene de otras habitaciones, por ejemplo.
Aquí te pongo el archivo ies que tiene las cáusticas.

La explicación:
Primero pon luces fotométricas puntuales (las que trae el Max) y las colocas en tus luminarias (cuidado con
meterlas dentro de algo, que entonces no iluminan) y haces instancias de esas luces para seguir colocándolas
donde toque.
Después te vas al panel de la fotométrica puntual y eliges en distribución WEB. En el apartado web/web file,
metes el archivo .ies de aquí.
Pon el color que quieras. Después bajas el multiplicador, como ves abajo (es ir probando). Tira renders sin GI y
ajusta ese multiplicador para que no queme la luz (a mí un 15% me vino bien).
Después activas GI y pones en el primer y secondary bounces, global photon map.
En el panel system/lights settings de Vray, sube el difuse multiplier hasta que veas que la luminosidad es la que
buscas. Yo puse 200 y tenía un color mapping de 5 hsv, así que eso depende de tu escena.

Cuando tengas ajustada la luminosidad cambia el primer rebote a irradiance y listo.

<!-- p. 231 -->

RENDER

<!-- p. 232 -->

Aquí pongo dos render. El primero con Vray y el segundo con Mental Ray. Los tiempos se asemejan.

<!-- p. 233 -->

Aquí dejo tres render (El primero es con tu archivo .ies josem). Así es como me quedó. Los dos últimos son de
Mental ray y Vray. Decía anteriormente que en Vray se puede iluminar un interior (etc.) con luces que funcionen
parecido a un foco de mano; como si fuesen focos comunes de 100 watt por ejemplo, que no sucede en la
realidad ni con Mental ray. Por eso decía que habrá que tener cuidado con los controles de Vray.

<!-- p. 234 -->

... Las fotométricas, es cierto que se comportan diferente a las Vray, porque tienen sus propias características de
apertura, rango, potencia, etc. En el caso de las Vray, lo desconozco. Supongo que donde den, allí iluminan, y
luego se van atenuando. Pero tampoco sé cómo controlar esa atenuación; es simplemente tocando parámetros
de rebotes primarios y secundarios, me imagino.

Aquí hay una librería de materiales que está bien, échale un ojo por si te sirve alguno.

<!-- p. 235 -->



<!-- p. 236 -->

Evermotion

<!-- p. 237 -->

Tutoriales:

Cómo representar el cuero
Múltiples vistas con un solo mapa de irradiación
Cristal + líquido
Creación de un vaso con mistela
Creación de una escena de cafetería

Cómo representar el cuero

Bienvenido. Muchos quieren saber cómo hacer una buena representación del cuero. ¡Vamos allá!

<!-- p. 238 -->

Mostraré la escena del Vol. 5's de Archmodels. Al principio, debemos ajustar nuestro material.

Ahora poner correctamente la textura de cuero en el modelo.

<!-- p. 239 -->

Después se debe aplicar el material para modelar. Para ver el material seleccione "Show Material in Viewport",
para ayudarle en la correcta creación del mapa.

<!-- p. 240 -->

Ahora seleccionamos nuestro modelo y agregamos un modificador de mapa UVW con mapeado de caja -esto es
todo.

<!-- p. 241 -->

Después de la representación el material debería ser parecido al de abajo.

<!-- p. 242 -->

Múltiples vistas con un solo mapa de irradiación.

En este tutorial examinaremos cómo renderizar una escena estática desde múltiples vistas.
Esta es la escena que usaremos:

Queremos representar de manera eficiente varias vistas de esta escena, usando el mapa de irradiación.
Los diferentes modos de mapa de irradiación nos ayudarán en esta tarea.

Primero abra el archivo "Arrancando la escena.max".
Por defecto, el modo de mapa de irradiación es Single frame. Esto nos permite representar la escena desde
cualquier vista, pero el mapa de irradiación será calculado siempre desde el principio.

Hay dos cámaras en la escena. Represente cada una de ellas: Seleccione la opción Don't delete en el grupo On
render end todo que tenemos que hacer está abierto la persiana Advanced irradiance map parameters y
pulsar Save to file (Guardar a archivo). Asigne un nombre al archivo, por ejemplo "prueba", y guarde el mapa
de irradiación.
Ahora que tenemos el mapa guardado en el disco, tenemos que decir al VRay que use este mapa.
Cambie el modo de mapa de irradiación From file (Desde archivo), pulse Browse y seleccione el archivo que
habíamos guardado.
Renderice la imagen. Vea que ahora VRay no calcula de nuevo un mapa de irradiación, sino que pasa
directamente a la interpretación.

<!-- p. 243 -->

Ya que no tiene que calcular ningún mapa de irradiación, la interpretación es muy rápida. ¿Qué pasaría si
queremos representar la primera vista en este momento?. Vamos a verlo:

Seleccione la opción Show samples desde la persiana Indirect illumination y represente la escena. Ahora se
puede ver dónde están realmente las muestras:
Incremental add to current map. Recuerde que el mapa de irradiación está todavía en la memoria. Renderice
la vista (Muestras verdes) y el mapa nuevo (muestras rojas): From file, apagar Show samples y representar:

De hecho, no es necesario ir siempre a través de todo el procedimiento. Ponga otra vez el modo Incremental
add to current map. Cambie la vista a perspectiva y represente otras vistas de forma arbitraria - simplemente
cambie la vista y hágalo. Repítalo varias veces.
Abajo se muestran los resultados:

<!-- p. 244 -->



<!-- p. 245 -->



<!-- p. 246 -->

Después de que represente algunas vistas guarde el mapa de irradiación en un archivo pulsando el botón Save
to file (Guardar aarchivo). Guárdelo en el mismo sitio que antes. Enseguida vamos a necesitarlo.
Como comparación, aquí está la última de estas imágenes, renderizada de nuevo con el modo de mapa de
irradiación Single frame (que significa que ha sido generado un nuevo mapa de irradiación completamente
nuevo).

Fíjese que el tiempo de representación aumenta - la generación de un mapa nuevo cuesta más que la utilización
del que ya tenemos en la memoria como base.
Vamos a volver al mapa guardado. Ahora contiene información bastante grande de nuestra escena. Podemos
usar ésta para renderizar otras vistas sin añadir más muestras de irradiación. Selecciones From file. Escoja una
vista que sea similar a la que ha renderizado antes y represente:

<!-- p. 247 -->

¡Observe que para esta imagen no hemos hecho ningún cálculo de irradiación! Solamente usamos el mapa que
ya teníamos calculado. Esto es así porque el mapa de irradiación ya tiene suficiente información para dar esta
vista, aunque nosotros no la hayamos renderizado antes.
Si el mapa no tuviera suficiente información, nos aparecerían artefactos, como antes, y tendríamos que usar el
modo Incremental add to current map para completar la información que necesita.
Como conclusión: este es un proceso básico de trabajo que puede usarse para renderizar una escena estática
desde múltiples vistas.

\-Primero prepare la escena (la geometría, materiales, iluminación, etc.).

\-Ajuste el mapa de irradiación al nivel de detalle que prefiera (por ejemplo uno predeterminado) y ajuste los
parámetros del render.

\-Limpie de la memoria cualquier mapa de irradiación anterior para evitar resultados no deseados.

\-Ponga el modo de mapa de irradiación en Incremental add to current map

Represente tantas vistas como necesite. La primera será lenta, ya que hay que calcular completamente un
mapa. Cada una de las siguientes será más rápida dependiendo del tamaño que ocupe en la memoria el mapa.

Puede guardar el mapa acumulado en un archivo. Posteriormente se puede usar para representar desde otras
vistas de la escena rápidamente. Para cargar el mapa guardado tiene que seleccionar el modo "desde archivo"
(From file), y elegir correctamente el nombre del archivo. Entonces puede retrasar el modo Incremental add to
current map y seguir representando otras vistas si está seguro de que el mapa ya tiene suficiente información.

Nota: si modifica la escena (por ejemplo agregando o suprimiendo objetos, materiales, luces, etc.) el mapa de
irradiación que está en la memoria será distinto y tendrá que recomponerlo desde el principio.

Crear un vaso con mistela

<!-- p. 248 -->

(Renderización de dos superficies que se tocan exactamente)

Temas abordados en este tutorial

Temas abordados en este tutorial

General
Render inicial
Render del líquido
Render final

General

En este tutorial hablaremos de la representación de interfaces superficiales de refracción con VRay. Un ejemplo
típico es la representación de un líquido en un contenedor de cristal. El problema es que tenemos dos objetos
distintos, que comparten exactamente el mismo límite superficial.
Desde un punto de vista del modelaje, es muy difícil asegurar que los dos objetos tengan exactamente la misma
geometría divisoria. Aunque esto se puede hacer (con dificultad) para las escenas estáticas, las cosas se
complican si queremos animarlo.
Desde un punto de vista de la representación, si dos superficies están físicamente juntas, el renderer no puede
distinguir entre ellas con exactitud, y puede llevar a errores en la representación.
Considerando estas dos cuestiones, es obvio que tendremos que separar las superficies, o modelar la interfaz
superficial separadamente. Tenemos estas tres opciones:

1- El líquido y el contenedor no se tocan y hay un hueco entre ellos. Esta solución es fácil de hacer y no requiere
de un apoyo especial al motor de render. Sin embargo, no puede producir un resultado realista, porque el hueco
entre las dos superficies modifica drásticamente la representación y hace que el líquido más se parezca a un
bloque sólido.

2- El líquido traslapa el contenedor. Esta solución produce resultados potencialmente mucho más realistas, pero
requiere un apoyo especial del renderer. El renderer debe guardar la pista cuyas superficies han sido cruzadas
por el rayo, para que pueda calcular el índice correcto de refracción. Sin esto, este método no se puede usar. Por
suerte, VRay proporciona el marco necesario, que hace de esta solución la preferida.

3- La tercera solución es modelar la interfaz separadamente. En general, esto es difícil de poner en práctica -
sobre todo en animaciones. Además, con esta alternativa hay un tercer objeto en la escena con un material
separado, que complica más las cosas. Tampoco trabajará muy bien con cosas como niebla en el cristal - ya que
en aquel caso, VRay no puede hacer la conexión entre el material de cristal/líquido, y el material de interfaz
superficial, y no puede aplicar correctamente el valor de la niebla.

<!-- p. 249 -->

Hablaremos únicamente de los dos primeros métodos; el tercero es más difícil y no lo recomendamos con el
VRay.

Render inicial

\-Abrir la escena de partida.

\-Asignar VRay como motor de render.
\- Para hacer más rápidas las vistas anticipadas de la escena, vaya a Image sampler y ponga el Image sampler
type en Fixed.

Después, queremos conseguir un GI rápido:
\-En Indirect illumination, active GI and set both the Primary y Secondary GI engines to Light cache.

\-Desactive Refractive GI caustics. Añadiremos trazado de mapa de fotones más tarde, para el render final.

\-En el Light cache, ponga Sample size en 0.04 para conseguir muestras con menos ruido.

\-Ponga en el panel de luz el modo Filter Fixed y Filter size en 0.08 Ya que mostraremos el escondrijo de luz
directamente.

\-Apagar el Store direct light opción para el escondrijo de luz, ya que queremos calcular la iluminación directa
separadamente.

\-Poner Subdivs en 500.

<!-- p. 250 -->

\-Opcionalmente, seleccione sello de frame de la persiana System .

\-Represente:

Así se muestra el vaso que llenaremos de líquido inmediatamente.

Render del líquido

Ahora que tenemos el vaso, tenemos que echarle el líquido.

\-Ponemos el objeto "liquid inside". Si mira el visor front, verá que el objeto está ligeramente dentro del
contenedor de cristal, sin tocarlo:

<!-- p. 251 -->

Aunque la distancia entre el contenedor y el líquido sea realmente pequeña, la representación no parece realista
\-parece que tenemos un cristal con un bloque sólido dentro. Para evitarlo, haremos solaparse un poquito el
líquido con el contenedor.
\-Ponga el objeto "líquido” e inoculte el objeto "líquido" traslapado. Desde el visor Front verá que este objeto
traslapa ligeramente el contenedor:

Ahora se ve mucho mejor; el líquido parece tocar realmente el cristal.

<!-- p. 252 -->

Render final

Para finalizar, nos gustaría mejorar el antialiasing, y agregar algunas cáusticas.
\-Seleccione Caustics desde la persiana Caustics .

\-Ponga Max. density en 0.2 - Queremos limitar la densidad de los fotones, ya que esto nos permite disparar más
fotones para un efecto de cáusticas más alisado.

\-Ponga el parámetro Search distance a 2.0. Normalmente los valores de 5 a 10 veces el parámetro Max. density
son como mejor trabaja.

\-Ponga el parámetro Max. photons a 0 -Esto hará que VRay considere todos los fotones dentro de la distancia de
búsqueda del punto.

Ahora la renderización se toma un poco más de tiempo, ya que VRay tiene que calcular también las cáusticas.
Ya tenemos cáusticas, pero con bastante ruido. Podemos reducirlo aumentando las subdivisiones (subdivs) de
las cáústicas, desde light.

\-Seleccione el objeto de VRAYLIGHT.

\-Pulse con el botón derecho en el objeto de luz del visor y seleccione "V-Ray properties. Se abre la caja de
diálogo de las propiedades de la luz, el cuadro de diálogo de configuración de luces de VRay.

\-Ponga Caustics subdivs en 4000.

<!-- p. 253 -->

Las cáusticas se ven mejor ahora y estos serán los ajustes que usemos para la representación final. Si quiere
cáusticas aún más alisadas, aumente el valor de Caustics subdivs y\o aumente el parámetro Search distance.

\-Para evitar calcular de nuevo las cáusticas para las siguientes interpretaciones, guarde el mapa de fotones de
cáusticas en un archivo, ponga el Caustics mode en From file, y seleccione saved caustics map con el botón
Browse.

Ahora tenemos que mejorar el antialiasing y reducir el ruido de la luz de área.
\-En el cuadro de ajustes Image sampler, ponga Image sampler type en Adaptive QMC.

\-En QMC Sampler, ponga Noise threshold en 0.002.

\-Ponga Global subdivs multiplier a 8.0 - Esto reducirá el ruido de la luz de área.

<!-- p. 254 -->

\-Representación final:

<!-- p. 255 -->

Creación de una postal de cafetería

Introducción.

Cuando fui a Francia en abril de 2005 en un viaje del instituto, compré diferentes postales para enviar a mi familia
y amigos. Por casualidad me olvidé de enviársela a uno de ellos, así que me la traje a casa.

Representaba la Cafetería Flore de París, famoso café francés de existencialistas y artistas. Me gustó mucho y
decidí realizarla con técnicas gráficas de ordenador.

Para su realización usé 3ds Max7 y Vray Advanced 1.46. El largo proceso de post-producción fue posible con
una tarjeta gráfica Wacom.

Tiziano Fioriti

Temas abordados en este tutorial:

Modelado
Texturación
Iluminación
Interpretación
Profundidad de campo y post-producción

Modelado

Cuando uno decide realizar una imagen como esta, tiene que saber que la parte del modelado es la más
sencilla.

<!-- p. 256 -->

Todos los objetos de la escena están modelados en Max con el instrumento poligonal. La taza de café, los
platillos, los cristales y los líquidos se hicieron con el instrumento torno, y luego convertidos a editables. Los
huevos son simples esferas con muchas subdivisiones.

El dibujo de la mujer es una simple spline editable convertida a polieditable, y luego deformada con el
modificador FFD 4x4x4. La mesa es una primitiva "cilindro" convertido y modificado como editable.

Texturación

La escena está compuesta por varios materiales complejos de Vray. Comenzaremos por el más simple. Mi dibujo
está como difuso y una textura creada en el Photoshop como bump (con un valor de 80). La taza de café tiene
una textura creada con el Photoshop (simulando la porcelana) como difusa, un color gris claro (R211, G211,
B211) con Reflect, y la reflexión fresnel activada.

Las píldoras son un material Multi/Sub-Object con dos materiales Vray encajados; ambos tienen activada la
opción Reflect con un color gris próximo al blanco (R228, G228, B228) y la reflexión fresnel activada.

El material del huevo tiene una textura creada con el Photoshop en canal difuso, un color gris oscuro (R59, G59,
B59) en la ranura reflect (FR activado) y refl.glossiness en 0,7.

<!-- p. 257 -->

El agua y el cristal tienen materiales muy similares excepto el valor IOR (vea la imagen debajo, también para el
material leche); el agua tiene 1,335, mientras que el cristal tiene 1,606.

La tetera tiene un material cromado; difuso en negro, la ranura reflect en R228, G228, B228, la reflexión fresnel
activada y la profundidad máxima de reflexión en 10.

Ahora vienen los materiales complejos. La mesa tiene dos materiales. Uno con una textura realizada en

<!-- p. 258 -->

Photoshop en difuso y ranura de golpe (30 como valor de golpe); el canal reflexión tiene un mapa procesal
(ruido, con valores estándar) en su propia ranura.

Otro tiene difuso en negro, reflexión en R176, G124, B74 con 0,85 como refl.glossiness y 3 como valor de
subdivisión. Además el canal refracción es negro, pero su número de subdivisiones es de 50. Por fin, el Índice de
Refracción es aproximadamente de 0,47.

Iluminación

Creo que el proceso de iluminación es el más importante de un proyecto.

Observe la imagen de arriba para ver las luces. Hay tres luces Vray con el multiplicador en 3, 3,5 y 4. Todas
tienen activado el "Store Irradiance map". Para un buen resultado coloqué también una imagen HDR llamada
"Cocina" y descargable desde el sitio web de Paul Debevec con multiplicador 0,5

<!-- p. 259 -->

Interpretación

La resolución final (3.048 x 2.287) llevó aproximadamente 5 horas. Debajo puede ver la configuración de los
ajustes de Irradiación y Antialiasing.

Puede ver los ajustes del render en las imágenes de abajo. La ranura de ambiente tiene la imagen HDR de
Debevec.

<!-- p. 260 -->

Profundidad de campo y postproducción

Este proceso es realmente importante. Un resultado mediocre podría mejorarse mucho con un buen software de
post-procesamiento. En este caso usé el Photoshop de Adobe. El cálculo de la profundidad de campo de la
imagen (o la animación) es realmente problemático. Es aconsejable hacerlo con un plugin de 3ds Max. Yo usé el
ZDepth.

En mi caso usé valores como: Mín. Z 155 y Máx. Z 230. Una vez hecho el mapa de profundidad (debajo), tiene
que exportarlo a un software adecuado (por ejemplo Photoshop) y ponerlo como canal alfa. Después puede
cargar el mapa alfa en Filter > Blur> Lens blur , y modificar algunos parámetros hasta lograr unos buenos
resultados.

<!-- p. 261 -->

El fondo es simplemente una imagen de mapa de bits saturada y luego velada.

Con pequeñas y simples modificaciones, creé algunos detalles como los rasguños sobre la taza de café y sobre
la mesa.
Consejo importante: es muy útil realzar o reducir los ajustes de brillo/contraste y Matiz/Saturación. Yo probé con
varios hasta alcanzar unos resultados interesantes.

<!-- p. 262 -->

Trazado progresivo

<!-- p. 263 -->

Tutorial
Trazado progresivo

En este tutorial hablaremos de un método alternativo para calcular la imagen final con VRay llamado Trazado
Progresivo.

Típicamente la computación de la imagen realiza separadamente varias tareas -por ejemplo, los cálculos de las
cáusticas, de la luz, de la irradiación...etc. Mientras el usuario puede ver el proceso de algunas de estas etapas,
la imagen final sólo se completa al final de la última etapa -los resultados intermedios no se pueden utilizar.
Por otra parte, el trazado progresivo, es un método para el cómputo incremental de toda la imagen inmediato. El
usuario puede detener el cálculo en cualquier momento y usar los resultados intermedios, si se consideran lo
suficientemente buenos. Además, de esta manera, sólo tiene que ocuparse de unos pocos controles, y es muy
fácil.
VRay se basa en el Algoritmo light cache para realizar el trazado progresivo. Esto tiene la ventaja de usar el
ajuste de luz para reducir el ruido durante el proceso de trazado para resultados de limpieza y la propagación
más rápida de la luz. La utilización del ajuste de luz asegura que el número de saltos de luz no estará limitado y
que el resultado sea una correcta iluminación para la escena. Además, la imagen puede ser guardada y
reutilizada más tarde para una interpretación normal.

Temas abordados en este tutorial

Interpretación inicial
Representación con materiales
Notas

Interpretación inicial

Paso 1: sistema inicial.
La realización del trazado progresivo es muy fácil:
1.1. Abrir la escena de partida desde el directorio de Max, donde la hayan guardado.
1.2. Seleccione VRay como motor de representación (render).
1.3. Comprobar la opción Override mtl en el cuadro Global switches. pulse el botón derecho en next y
seleccione el material por defecto de VRayMtl.

1.4. Seleccione Indirect illumination y seleccione primary y secondary GI desde el caché Light.

1.5. Seleccione en la persiana light el modo Progressive path tracing.

1.6. Opcionalmente, puede marcar Frame stamp para imprimir el tiempo del proceso en la imagen.

<!-- p. 264 -->

1.7. Marque la opción Enable built-in frame buffer en el cuadro V-Ray virtual frame buffer. Esto no es
necesario, pero le permite usar el zoom de forma segura durante el proceso. La utilización del 3dsmax VFB
puede bloquear el programa si usa el zoom durante la interpretación.

1.8. Representación de la escena. Debería ver gradualmente la imagen que está siendo muestreada; con más
ruido al principio, pero mejorando a medida que se van añadiendo más muestras:

Paso 2: Ajuste del nivel de ruido
La imagen de encima es claramente ruidosa, aunque esté calculada muy rápidamente, y puede usarse para
vistas previas. Sin embargo, para las interpretaciones finales, nos gustaría reducir el ruido. Esto se hace
ajustando el parámetro de luz Subdivs.

3.1. Pónga Subdivs en 2000.

3.2. Represente. La interpretación ahora se toma más tiempo, porque VRay está calculando más muestras.
Desde que aumentamos el valor Subdivs, el tiempo de representación se multiplicará por cuatro:

3.3. Si quiere reducir el ruido más tarde, aumente el valor de Subdivs. Para representar, todavía puede ponerlo
a un valor muy alto y esperar hasta que le guste antes de cancelar la representación, y utilizar el resultado. Aquí
se ve con 20000 subdivisiones, que se cancelaron después de una hora:

<!-- p. 265 -->

Paso 4: Ajuste de la tendencia de la solución GI
Para las imágenes de arriba, usamos los ajustes por defecto para la luz (excepto el parámetro Subdivs). Los
ajustes por defecto ayudan durante los cálculos de la GI. Esto ayuda reducir el ruido en la imagen final, a costa
de la tendencia a la solución de GI. Esta tendencia puede manifestarse como escapes de luz por debajo de las
paredes delgadas o como que aparezca manchada la GI secundaria. Sin embargo en la mayoría de los casos, la
diferencia es mínima.
Puede usar parámetro de luz Sample size para controlar la tendencia. Los valores más grandes usarán mayores
muestras de luz y aumentarán la tendencia. Los más bajos disminuirán la tendencia, pero pueden utilizar más
memoria. Un valor de 0.0 no usará ningún caching en absoluto y producirá una solución imparcial.
Abajo hay tres interpretaciones con valores diferentes para el Sample size y con el valor Subdivs en (1000). No
hay gran diferencia en esta escena simple, pero en situaciones más complicadas, la reducción del ruido puede
ser significativa.

Sample size = 0.04 Sample size = 0.02 Sample size = 0.0 (Solución
imparcial)

Siguiente:

Mejorar la calidad con materiales

<!-- p. 266 -->

Representación con materiales

Paso 1: Interpretación con materiales
\-Apagar la opción Override mtl del cuadro Global siwtches.
\-Para la vista previa, ponga Subdivs del cahé light a 1000.
\-Represente:

En este punto, puede ajustar los materiales etc., lográndose una regeneración relativamente rápida.

Paso 2: mejorar la calidad con materiales.
Ya que el nivel de ruido está determinado por el parámetro Subdivs, sólo tenemos que aumentarlo. Las
subdivisiones individuales para los materiales (reflexiones/refracciones) no importan.
\-Aumente el parámetro Subdivs hasta 2000 y represente. La interpretación ahora lleva más tiempo, pero
reduce el ruido:
Seleccione Reflective GI caustics en Indirect illumination.

\-Represente la imagen. Se pueden ver las reflexiones cáusticas sobre el suelo verde y sobre la esfera, así
como una mejora general de la escena. Note que la imagen tiene también más ruido en los sitios donde hay
cáusticas:

<!-- p. 267 -->

\-Para reducir el ruido en la imagen, necesitaremos más Subdivis para la luz, por ejemplo, 4000. Ya que
aumentamos el valor dos veces, el tiempo se cuadruplicará:

Vea que no puede obtener GI-cáusticas de las superficies perfectamente especulares con fuentes de iluminación
de punto. La fuente de iluminación debe ser de zona, o el material debe ser brillante, o ambas cosas. También
puede trazar un mapa de fotones para generar cáusticas mediante los ajustes en Caustics.
Este método no es tan exacto como la GI de cáusticas, pero puede manejar fuentes de iluminación de punto con
superficies especulares perfectas.

Aumento del tamaño de la imagen

La única cosa a recordar al cambiar el tamaño de imagen consiste en que las imágenes más grandes tienen más
ruido que las más pequeñas para un mismo ajuste del Valor Subdivs. Es porque las muestras están repartidas
sobre más píxeles, y por lo tando, cada píxel consigue menos muestras. Para compensarlo, tendrá que aumentar
el valor de las subdivisiones. El aumento de la resolución por dos, significa que también tendrá que aumentar el
valor Subdivs dos veces para conseguir la misma calidad (y esto significa que el tiempo de render se
cuadruplicará otra vez).

Aquí está la imagen final en 800 x 600 píxeles, con 8000 Subdivisiones:

<!-- p. 268 -->

Notas

El tipo Image Sampler (QMC, fixed, Adaptative subdivision) no se tiene en cuenta en este modo, ya que el
algoritmo hace una superprueba automáticamente. Después de que se ha completado la imagen, VRay imprimirá
los trazados mínimos y máximos que fueron configurados para los pixeles.

El filtro antialiasing sin embargo, sí se tiene en cuenta. Vea que los filtros perfilado (Mitchell-Netravali, CatmullRom) pueden presentar ruido y necesitarán más muestras para darnos una imagen alisada. Los filtros como
Blend también tardan más. La vuelta al antialiasing filtra la menor parte del ruido.

Los parámetros de las subdivisiones en los materiales, texturas, luces, ajustes de cámara etc. no se tienen en
cuenta en este modo. El ruido y la calidad se controlan enteramente por el ajuste de la luz, con el parámetro
Subdivs.

Los únicos parámetros de QMC sampler que se tienen en cuenta son Adaptative amount y Tim-independent.
Nunca ponga el parámetro Adaptative amount a 0.0.

Actualmente, sólo se genera el canal RGBA por el algoritmo. Cualquier canal G-BUFFER adicional no se tiene en
cuenta.

El ajuste de luz no tiene limitación sobre el número de rebotes de luz difusa en la escena. El número de saltos
especulares (por reflexiones/refracciones) está controlado por el material, o a escala global en el cuadro Global
switches.

Actualmente, el trazado progresivo no funciona correctamente para representar los campos, ni con
objetos/materiales matte.

Actualmente, VRay sólo puede generar internamente 2^32 trazados únicos de luz. El parámetro de ajuste
Subdivs está limitado a 60.000, que da 60.000^2 = 3.600.000.000 trazados únicos. Ya que éstos están
distribuidos por toda la imagen, para las muy grandes puede ser imposible conseguir suficientes por píxel para
un resultado alisado. Por ejemplo, una imagen de 2.000 x 2.000 puede calcularse casi siempre con 900 trazados
por píxel -que puede no ser adecuado para un resultado perfectamente liso. En este caso, usar un método
tradicional (QMC-IG) puede resultar una solución mejor.

<!-- p. 269 -->

Ajustes básicos

Tutoriales:

Configuración básica para VRay.
Ajustes básicos de materiales.
Refracciones.
Reflexiones.
Una iluminación estándar.
Copa de cristal + líquido

Configuración básica para el render Vray

Tutorial

Configuración básica para el Vrender

Asignar Vray

Seleccionar como render a Vray

Abra el diálogo de ajustes de render, vaya a la persiana Current Renderers y pulse el botón asignar renderer
para la producción. Marque Vray.

¡Persianas extras!

<!-- p. 270 -->

Después de designar a Vray como renderer principal, verá muchas nuevas persianas. Cada una con "Vray:… "
seguido del nombre del ajuste.

En el resto del tutorial vamos a dar una explicación general de cada una.

VRay frame buffer

Vray frame buffer

Cuando está abierto, el buffer de Vray sustituye al de Max. El buffer de frame de Vray tiene muchas más
opciones y muchos otros ajustes muy interesantes.
En esta persiana puede controlar su tamaño deshabilitando 'get resolution from max'.
La interpretación del archivo de imagen de Vray le permite renderizar imágenes de muy alta resolución, sin que
se coma por completo toda la memoria RAM disponible.

El uso del frame buffer Vray es sólo para usuarios avanzados. No se moleste en usarlo mientras sea un
principiante con Vray.

<!-- p. 271 -->

Vray global switches

Vray global switches

Aquí puede controlar muchos ajustes de Vray, principalmente los que suelen acelerar la interpretación de la
prueba.

¡Puede activar-desactivar el desplazamiento, la iluminación, las luces por defecto de Max, las luces ocultas y las
sombras solamente pinchando el cuadrito apropiado!

El botón "don't render final image" se usa para dejar que Vray calcule solo la iluminación indirecta -el GI- (por
ejemplo el mapa de irradiación) sin que renderice la imagen. Olvídese de esto por ahora.

Habilite todas las reflexiones y refracciones en la escena haciendo clic en el cuadrito. Es muy práctico para
probar los objetivos. La Max depth controla la profundidad de la reflexión/refracción (el número de veces que un
rayo puede reflexionar/refractar antes de ser ignorado en el proceso de trazado).

También puede apagar los mapas, sus filtros... etc. Los efectos de brillo (Glossy effects) son reflexiones o
refracciones borrosas. Apagarlos mejora enormemente el tiempo del proceso, algo muy adecuado mientras se
están haciendo pruebas de render.

Anular material (Override mtl) puede usarse para asignar a cada objeto de la escena el mismo material.

Tendencia de rayo secundaria (Secondary rays bias): por favor lea el manual.

<!-- p. 272 -->

Image sampler (Antialiasing)

Image sampler (Antialiasing)

En Vray, puede decidir entre 3 tipos de alternativas para calcular el alisado de la imagen. ¡controla cómo de
aguda y lisa será la imagen, y tiene un efecto enorme sobre la duración del proceso!

La fija (Fixed rate) es muy práctica, pero es lenta en muchos casos. Úsela si hay muchos materiales brillantes,
sombras de área, desenfoque de movimiento… etc. Las subdivisiones más altas suponen mejor calidad, pero
más lentitud.

QMC adaptable (Adaptative QMC) es mi favorito. Como su nombre ya indica, es adaptable, adaptará sus
cálculos a la situación. Comparará la calidad del pixel calculado, y decidirá si es lo bastante bueno o si hay que
calcular más.
Esta calidad se controla por la persiana QMC. (Más abajo del tutorial, en "persianas"). Use QMC adaptable si
tiene en la escena muchas glossies, sombras de zona, desenfoque de movimiento etc., y si quiere priorizar la
velocidad a costa de la calidad de la imagen. Lleva algún tiempo dominarlo, pero una vez que se logra, se tiene
el control total del Vray con solo hacer unos pocos clics.

La subdivisión adaptable (Adaptative subdivision) es también un método adaptable. Aunque es muy rápido es
muchos casos, puede hacerse muy lento si hay muchos glossies en la escena. También usa más memoria RAM.
Úselo si tiene grandes áreas lisas en su escena (por ejemplo un interior con grandes paredes blancas). Las
posiciones min./máx. controlan la calidad. De 0-2 son buenos valores, -2 a -1 es bueno para una representación
muy rápida.

Serán necesarias algunas pruebas para entender las diferencias entre los 3 modos. La documentación en línea
tiene muy buenas explicaciones sobre este asunto, con muchos ejemplos mostrando las diferencias.

El filtro anti aliasing (Antialiasing filter) puede cambiarse si tiene problemas con las texturas finas o para depurar
detalles en la escena. Cada opción tiene sus propias características, pero no es objetivo de este tutorial
explicarlas todas. ¡En muchos casos puede simplemente apagar el filtro!

Unos filtros que yo uso a menudo:
\- Ninguno.
\- Mitchell Netravali: Resultado liso, mandos buenos.
\- Catmull rom: Muy agudo (un poco como el resultado 'unsharp mask' -Máscara de desenfoque- en Photoshop).
\- Soften con el radio alrededor de 2.5 (Liso y rápido).

<!-- p. 273 -->

Indirect illumination (GI)

Este persiana controla las opciones principales para el GI (= la luz echada). Como la mayor parte de renderers,
GI Vray diferencia entre los rebotes primarios y los secundarios.

Un proyector simple arrojará luz directa. Esta luz golpea un objeto y será absorbida un poco, pero el resto
rebotará (saltará) por la escena. Este es el salto o rebote primario. Este primer rebote probablemente golpeará
en otro objeto y rebotará otra vez (el salto secundario) etc. antes de perder su energía.

El salto de luz primario directo tendrá el mayor impacto sobre la iluminación, porque esta luz todavía tiene mucha
energía. necesita ser calculada con mucha exactitud para crear una iluminación realista. Los rebotes secundarios
son generalmente menos importantes (como mucha energía lumínica ya ha sido absorbida, tiene menos impacto
en el resultado visual -las Escenas de interiores son una excepción, allí los saltos secundarios también son
importantes).

Puede escoger entre los diferentes modos de calcular los rebotes primarios y secundarios, y ajustar su fuerza
(con los multiplicadores). Con un post procesado puede cambiar la saturación o el contraste de la GI.

Las Cáusticas son el modelo formado por las luces refractadas/reflejadas. El GI caustics es el creado por la luz
GI refractada/reflejada (los saltos, rebotes de la luz). Los saltos estándar primarios y secundarios no tienen en
cuenta las propiedades reflexivas/de refracción de los materiales, sólo sus propiedades difusas. Tiene que
habilitarlos -o no- en los dos cuadritos apropiados.
Un ejemplo muy visible de cáusticas reflexivas es el modelo de luz que vería si pusiese un proyector sobre un
anillo de cromo encima de una mesa. La refracción cáustica es generada por ejemplo por una esfera de cristal,
que recoge toda la luz que pasa por ella, creando una zona de brillo por debajo.
¡Note que cuándo quiere que la luz GI atraviese objetos transparentes, debe marcar "GI caustics refractive"!
Recuerde que "cáusticas" es sólo un nombre para la luz refractada/reflejada. En iluminación, las luces que son
reflejadas o refractadas se llaman 'causticas'. Por ejemplo la luz que atraviesa una ventana también es cáustica.

Un caso especial es la que proviene de un proyector de Max por ejemplo (o cualquier otra luz de Max). Esta es
una luz directa y no luz GI; Vray le ofrece la posibilidad de representar también estas 'caustics' de luz directa.
Estas opciones tienen su propia persiana (vea más adelante). Observará que la luz de un proyector no penetra
en los objetos transparentes en Vray. Esto es porque por defecto, no se permite la luz directa de caustics. Si
quiere que la luz atraviese los materiales transparentes, tiene que permitir caustics (llevará más tiempo), o usar
la opción de falsas cáusticas en las opciones del material Vray transparant. (La opción = 'affect shadows'
\-afectar sombras- en las propiedades de refracción del material).

<!-- p. 274 -->

Irradiance map / Quasi monte carlo / photon mapping / light cache

Irradiance map / Quasi monte carlo / photon mapping / light cache

Según el método que haya seleccionado para los rebotes primarios y secundarios, aparecerán las susodichas
persianas. Todas ellas tienen los modos de rebotes de GI interesados. Cada uno tiene sus características y sus
aplicaciones. Esto es complicado de explicar en este tutorial básico.

Por ahora, recuerde que todos estos métodos son modos de aproximarse a la iluminación GI (Iluminación
indirecta). Los cálculos reales de GI llevan mucho tiempo, es por eso que estos métodos se crearon para
acelerar las cosas utilizando unos valores aproximados.

Caustics

¿Recuerda la luz caustica directa del vista anteriormente en este tutorial? Bien, desde aquí puede habilitarlas o
no, y controlar algunos parámetros. Para conseguir que una luz cáustica directa se vea agradable, también
tendrá que adaptarla en los ajustes de Vraylight.

¡Un truco sencillo para eliminar la necesidad de luce cáusticas directas, es sencillamente no es usar luces
directas. sólo con la luz GI, haga clic en 'refractive/reflective GI caustics' en la persiana de Iluminación Indirecta y
todas las cáusticas se calcularán según sus ajustes de GI! Desde luego, no siempre es posible usar sólo la
iluminación GI... pero si sólo usa Skylight "la claraboya" y los tipos de luz de Vray, puede eliminar la necesidad
de usar cáusticas directas.

<!-- p. 275 -->

Enviroment

Environment (Ambiente)

Vray le permite anular el ambiente de Max con estos mandos.

Use la "claraboya" para iluminar la escena 'skylight'. Si pone un mapa en la ranura detrás de ella, la muestra en
color es abandonada y en cambio, se usa el mapa para iluminar la escena. Tiene que marcar el GI para que la
claraboya se haga visible. La claraboya no es una luz directa; en realidad se trata como de un rebote primario, es
por eso que el GI es necesario para hacerla visible. ¡Note que si habilita el GI, la claraboya se apaga y si hubiera
puesto un color de fondo de Max, este color sería usado como "claraboya"!

Otra muestra controla el ambiente de reflexión y refracción. Esté como esté el enviroment de Max, sus objetos
siempre reflexionarán/refractarán. También puede poner un mapa, como con la opción de claraboya.

¡Note que estos ajustes no se resaltarán en el fondo!. Para esto use el ambiente (enviroment) de Max.

QMC sampler

QMC puede verse como un centro de control de la calidad global. Controla todos los parámetros que tienen algo
que ver con los cálculos de Cuasi Monte Carlo como QMC adaptative AA, QMC-GI, mapa de Irradiación, efectos
brillantes, sombras de área, desenfoque de Movimiento y profundidad de campo.

El parámetro más importante es el umbral de ruido (Noise thresold), que controla la exactitud de los cálculos. El
ajuste de la calidad más alta es 0.001, pero requiere de tiempos más largos. El multiplicador global de
subdivisiones puede usarse para disminuir o aumentar todos los parámetros de las subdivisión en la escena. Es
muy útil para pruebas rápidas.

<!-- p. 276 -->

Color mapping

Color mapping

El mapa de color puede ser usado para el post-procesamiento de una imagen de Vray. Por favor vaya al manual
para más información sobre sus diferentes tipos.

Camera

Se pueden escoger distintos tipos de cámara en vez de la cámara estándar por defecto de Max; por ejemplo el
objetivo "Ojo de pez", la cámara esférica, cilíndrica… etc. Por favor, vea el manual para más información sobre
los diferentes tipos de cámara.

La profundidad de campo es el efecto causado por el diámetro de la apertura del diafragma de la cámara. Los
objetos que están desenfocados aparecerán borrosos. Cuanto más lejos del foco y más grande sea el diafragma,
más desenfocado estará.

El desenfoque de movimiento es el aspecto borroso que se aprecia cuando los objetos se mueven muy rápido, o
cuando se mueve la cámara. En la vida real esto se controla por la velocidad del obturador de la cámara.

Ambos efectos son raytraced, no falsificados con trucos, de manera que tienen un gran impacto sobre el tiempo
de procesamiento.

<!-- p. 277 -->

Default displacement

Estos parámetros controlan los ajustes por defecto del Vraydisplacement. Más sobre el desplazamiento puede
verse en el manual en línea, con muchas ilustraciones.

System

Otra persiana que controla toda clase de parámetros generales.

Los parámetros Raycaster se utilizan para controlar la cantidad de memoria que VRay usará en una escena
específica. ¡En el 99 % de los casos no tendría por qué tocarlos!

Render region división. X y Y controlan la anchura y la altura de un cubo a representar. Para pequeñas las
resoluciones, puede bajarlos; para las altas aumentarlos. Unos buenos valores son entre 32 y 128 píxeles.
Región secuence cambia la orden en el que se representarán los cubos.

Distribute rendering (interpretación compartida) es el proceso de representar una imagen con un PC diferente.
"Previous render". Como el anterior la representación del frame en el buffer es superpuesta por los nuevos
cubos.

Default geometry (Geometría por defecto) estática/dinámica: Vea el manual.

Frame stamp es muy útil para imprimir el tiempo del proceso sobre la imagen representada.

Objects settings y Lights settings son las propiedades específicas para las luces y objetos Vray de la escena.
Puede marcar-desmarcar todas las opciones para cada objeto de la escena.

Presets (Predeterminar) puede guardar todos o algunos ajustes de render para el cambio fácil y rápido entre

<!-- p. 278 -->

ajustes, por ejemplo de prueba o de alta calidad.

Vray log es la pequeña ventana que aparece, dándole alguna información sobre el proceso de interpretación.

<!-- p. 279 -->

Ajustes básicos de materiales

Crear una escena de prueba.

Una tetera es un buen objeto para probar el render, por su forma.
Cree dos teteras sobre un plano más grande si quiere seguir este tutorial tan de cerca como sea posible.

Abrir el editor de materiales

Ábralo presionando la tecla "m" del teclado.

Cargar un Vraymaterial

<!-- p. 280 -->

Presione el botón "estandard" en el editor de materiales y seleccione VRayMtl de la lista. Pulse dos veces o
arrastre a una de las ranuras de materiales.

Renombre y coloree

Renombre el material como "teapot1". El primer parámetro en el material es la ranura difusa. Este es el color
principal del material. El cuadrado a su lado es una ranura de mapa; Aquí se pueden cargar bitmaps u otra clase
de mapas en la textura del material. Por el momento, ponga un color anaranjado claro.

Segundo material

Repita los pasos anteriores para crear un material de color gris claro. Renombre este material como
"groundplane" y asígnelo a la pequeña tetera. Debería tener algo parecido a la imagen siguiente.

Primer render

Represente. La imagen debería ser similar a la mía, si se han puesto todos los ajustes del paso 1. ¡¡Asegúrese
de que la iluminación por defecto está desactivada!!!

<!-- p. 281 -->

Use interpolation

Hay un checkbox en los parámetros de reflexión que no he explicadio. El 'use interpolation'. Se puede usar para
acelerar el cálculo de los reflejos brillantes. Trabaja más o menos como el mapa de Irradiación para el GI.

Cuando marque esta caja, podrá ajustar la interpolación de Vraymaterial.

No explicaré estos ajustes, porque no recomiendo usar la interpolación para reflexiones brillantes. Raras veces
son buenos, y cuando quiere calidad, ellos toman casi mientras los reflejos están represente brillantes.

Si quiere conocer más sobre la interpolación, remítase al manual.

Refracción

Refracciones Temas abordados en este tutorial:

Crear la escena de prueba
Crear los materiales
Parámetros de refracción
Color de refracción
Color difuso
Ajustar los reflejos
Crear un ambiente
VrayLightMtl
Ajustar "la claraboya"
GI-Cáusticas
Max depth
Opciones: reflexiones sobre la parte posterior
Glossiness
IOR
Color de salida
Fog color
Refraction color
Glossiness+IOR=1+fog
VrayLight
Affect shadows
Material final
Sistema de imágen final
Comparación con GI QMC

<!-- p. 282 -->

Para empezar este tutorial:

Abra el cuadro de diálogo de configuración del render y haga lo siguiente:

\- Seleccione a Vray como motor de render.
\- Marque Output size en 480 x 360píxeles.
\- Global switches: apague las luces por defecto.
\- Image sampler a adaptive QMC.
\- Antialising filter "mitchell-netravali".
\- Indirect illumination en ON.
\- Secondary bounces bounces multiplier a 0,85.
\- Ajustes de Irradiance map:
\- "low" preset.
\- hsph subdivs = 20.
\- environment:
\- skylight color blanco puro.
\- reflection/refraction negro puro, 1.0 multiplier.
\- system:
\- render region division 50 x 50 píxeles
\- frame stamp: Suprima todo excepto el rendertime.

Fog color

El color de niebla es usado para teñir las refracciones de un cierto color. Las zonas más gruesas estarán más
oscuras (más coloreadas) que las áreas más finas. Pruebe con un color rojo claro para la niebla y represente.

El material es muy oscuro, pero las partes más delgadas ya muestran alguna transparencia.

El color de niebla y el multiplicador de niebla son en realidad un control de absorción. La luz suelta su energía
viajando por el material. Cuanto mayor es la distancia, más energía será absorbida por el objeto. Es por eso que
las partes más delgadas retendrán más luz que las partes más gruesas.

<!-- p. 283 -->

Refraction color

Probablemente esté preguntándose, ¿entonces cuál es el uso del color de Refraction?

Bien, vuelva a las opciones por defecto de la niebla, y elija un color rojo.
Represente.

El cristal también está coloreado, pero sin el efecto de absorción. ¡Están coloreadas igualmente las zonas
delgadas y gruesas (las áreas oscuras son las refracciones del ambiente negro!).
Por lo general yo uso un blanco puro blanco para refractan el color y juego sólo con las opciones de niebla. Pero
experimento con diferentes ajustes de color/niebla para ver lo que hacen. Recuerde, el color oscuro significa
menos transparencia. La saturación del color tiene un impacto enorme sobre el aspecto de la refracción. Un color
saturado muy oscuro parecerá muy similar a un color muy oscuro insaturado en la muestra en color, pero será
totalmente distinto cuando se use para refractar el color de niebla o el color. ¡Pruébelo solamente!

<!-- p. 284 -->

Glossiness + IOR=1.0 + fog

Ponga el glossiness a 0.75 y las subdivisiones a 16 y represente otra vez. El material parece cera un poco
reflexiva.

Ponga Glussiness a 1.0 otra vez y IOR a 1.6 antes de continuar.

VRayLight

Pulse y arrastre a un visor para crear una luz Vray rectangular. Haga el tamaño el mismo como nuestra caja, y
posiciónela de la misma manera. Después, pomga la caja. Ponga los ajustes Vraylight como en la imagen de
abajo. El multiplicador debería ser igual al multiplicador del Vraylightmaterial que ya usó anteriormente cuando
vimos la caja de luz.

Ahora creamos una fuente de iluminación exactamente igual que cuando creamos la caja de luz, pero ésta
proyectará sombras de área raytraced.

<!-- p. 285 -->

Affect shadows

Una opción importante que no hemos tocado aún, son las sombras afectará checkbox. Esto no tendrá ningún
efecto en nuestra escena de prueba porque no hay ninguna luz directa, sólo la luz GI. Las opciones de sombras
afectarán sólo si se usan con rayos de luz directos.

Por lo tanto, sustituiremos la caja de luz por Vray Arealight. Vaya al panel crear y escoja luces, y del menú
dropdown escoja Vray.

En el material de cristal, marque Affect shadows y pulse render.

La imagen debería parecerse a la mía. Como se puede ver, proyecta sombras verdes. Esto es así porque han
sido usadas las opciones de Affect shadows y el color de niebla.

El tiempo de renderización aumenta porque las sombras son raytraced.

<!-- p. 286 -->

Material final

Use los ajustes de material como en la imagen inferior. Bajé el multiplicador de niebla un poco, y aumenté la
profundidad máxima ambos a 8.

Sistema de imagen final

En los ajustes de mapa de irradiación, cambie todo como en la imagen de abajo. Vaya también a la persiana
QMC y cambie el umbral de ruido a 0.001 para una calidad máxima.

<!-- p. 287 -->

Represente la imagen, debería verse algo parecida a la de abajo.

Observe las cáusticas agradables y las sombras de área, controladas por los ajustes de mapa de IR. No
permitieron ninguna cáustica en con fuerza encontrar sitios, ningún tiempo consumiendo raytraced sombras fue
necesario.

Comparación con GI QMC

Como prueba, rendericé la imagen con el GI QMC en vez de con el mapa de irradiación para el primer salto. El
GI QMC no es un método aproximado como el mapa de IR con su algoritmo de prueba. GI QMC calcula al GI sin
compromiso, cada muestra de luz consigue igual atención. Esta es una buena prueba para comparar cómo de
bien es calculado el GI con el mapa de IR.

Como puede ver, en las zonas con mucho detalle de iluminación, la imagen de GI QMC se ve mejor (= more
físicamente corrigen) que el IR. Pero se lleva 10 minutos comparados a 1m 24s para la versión del mapa de IR...
Si quiere un GI más detallado con el mapa de IR, tiene que corregir algunos ajustes de mapa de IR.

<!-- p. 288 -->

La imagen anterior está representada con ajustes de mapa IR optimizados. Como se puede ver, viene muy cerca
del ejemplo de GI QMC, pero sin ruido en el suelo. Explicaré cómo optimizar los ajustes de mapa de IR en un
próximo tutorial.

Translucidez

Como los mandos de translucidez son un poco extraños en su comportamiento, no intentaré explicarlos...
Explicaciones más técnicas pueden encontrarse en los documentos en línea, y creo que equipo de Vray trabaja
en un tutorial sobre la translucidez...

Se pueden conseguir resultados muy similares con combinaciones de ajustes sumamente diferentes, pero
cuando se cambien las condiciones de iluminación, reaccionarán de manera muy diferente.

<!-- p. 289 -->

Los controles de translucidez también dependen del lustre de refracción y de los ajustes de niebla. Ellos trabajan
juntos, y sobre todo el color de niebla es un ajuste muy sensible que tendrá un efecto muy drástico sobre el
material. ¡¡Una cosa que nunca debería hacer, es usar colores que tengan uno de sus componentes a
255!!!

Por lo general me marcho la translucidez colorea blanco puro, la refracción colorea un valor de escala de grises y
luego controla el color material con el difuso y el color de niebla. Con el multiplicador de niebla y el multiplicador
de luz de translucidez se crean varios efectos de luz.

piel

Aquí tiene los ajustes para material de la piel. Juegue con los ajustes e intente entender lo que cada parámetro
afecta al resultado final. Note que debido al empleo tanto de la reflexión como del lustre de refracción, este
material irá muy lento, sobre todo con estos valores de subdivisiones tan altos.

<!-- p. 290 -->

Recomponga todos los ajustes de antes

Anteriormente, se cambiaron todos los ajustes para la imagen final. Tenemos que volver atrás para probar ahora
los valores de render.

Abra el diálogo de ajustes de render y ponga lo siguiente:

\- output size en 480 x 360 píxeles.
\- global switches: desactive las luces por defecto.
\- image sampler en adaptive QMC.
\- antialising filter "mitchell-netravali".
\- Active indirect illumination.
\- Seconrepresentey bounces multiplier en 0,85.
\- Configuración de Irradiance map:
\- "low" preset.
\- hsph subdivs = 20
\- environment:
\- skylight color blanco puro.
\- reflection/refraction negro puro, 1.0 multiplier.
\- system:
\- render region division 50 x 50 píxeles.
\- frame stamp: Suprima todo menos la parte del rendertime.

Crear un material de cromo

Cree un Vraymaterial nuevo y ajuste como en la imagen de abajo. Este es un material básico de cromo. Asigne
este material al nudo toroide y haga una prueba rápida de representación. Debería parecerse a mi testimage.
Ahora cambie el lustre de reflexión a 0.7 antes de seguir.

BRDF

<!-- p. 291 -->

En esta persiana puede escoger entre blinn, phong o ward shader. El efecto de estos tres tipos es notable, y más
usando reflexiones brillantes. Represente la escena con tres shaders diferentes. Los ajustes afectan a cómo
parecerán los toques de luz.

Ward shader se utiliza normalmente para los materiales metálicos.

Anisotropía

Las reflexiones anisotrópicas son reflexiones estiradas en alguna dirección. Se ve esto a menudo sobre metales
lijados, por ejemplo el interior de las cazuelas de cocina. Los controles de anisotropía determinan la forma del
toque de luz.

El nudo toroide no es el mejor ejemplo, pero usted conseguirá el punto.

Cambie la anisotropía a -0.6 y represente la imagen. Hay aquí también una diferencia enorme entre pong, blinn y
ward. Pruebe también con algunos otros valores (como por ejemplo +0.6).

El eje de coordenadas XYZ le permite cambiar la dirección de los reflejos, o puede usar un canal de trazar un
mapa en su lugar. El parámetro de rotación gira los reflejos...

Opciones

<!-- p. 292 -->

Primero ponga anisotropy a 0.0 otra vez, y también refl glossiness a 1.0.

El trazado de los reflejos y de las refracciones es bastante simple, simplemente cambiando el cálculo entre
losdos.

El parámetro cutoff es un valor de treshold para Vray para remontar reflexiones cualquier remoto o no. Pruebe
con un valor de 0,7 sobre la imagen. El aumento del umbral puede acelerar la interpretación cuando se usan
muchas reflexiones en la escena.

Double sided: Por favor remítase al manual.

Reflect on backside. Usamos esta opción ya al principio de este tutorial. Si está seleccionado, también se
calcularán los reflejos para las superficies traseras.

Use irradiance map: Si lo apaga, el mapa de irradiación no se usará con este material. En cambio, el GI del
material será calculado con el GI QMC. Esto puede ser muy útil si la irradiación traza un mapa de aspecto
borroso en algunos pequeños detalles de la sombra sobre ciertos objetos.

Treat glossy rays as GI rays: Por favor vaya al manual.

Energy preservation mode: Por favor vea el manual.

Mapas

Los mapas rollout resumen todos los mapas de textura diferentes. Casi todos los mapas son accesibles desde
los parámetros básicos del rollout (los pequeños cuadrados al lado de los parámetros), pero unos aparecerán
sólo aquí.

Estos son los cuatro mapas: bump, displace, opacity y environment.

Bump allows: puede representar irregularidades en la superficie usando un mapa. Las áreas oscuras en el mapa
son áreas 'bajas', las brillantes son áreas 'altas'.

Displacement: parecido al golpe, pero en vez de la falsificación que lo da, se deforma la malla real para crear las
irregularidades. Vea el manual para tutoriales extensos y ejemplos sobre desplazamiento.

Opacity: es lo mismo que ya está acostumbrado a en el estánrepresente materiales de Max.

Environment: le permite usar diferentes reflexiones/refracciones el ambiente para cada material.

Reflect/refract interpolation

<!-- p. 293 -->

Estos cuadros contienen parámetros para controlar la interpolación de los reflejos/rebotes. Solo se necesitan si
hubiera seleccionado el 'use interpolation' en los parámetros básicos. No recomiendo usar la interpolación para
efectos brillantes. Si realmente quiere usarlos, por favor vea el manual para una información más detallada.

Reflexiones

Seleccione el material “orange” en el editor de materiales. Debajo de la ranura difusa están las opciones de
reflexión del material. La muestra en color al lado reflect es el control principal de reflexión. Un valor negro no
proporcionará ninguna reflexión en absoluto, el blanco significa que el material será reflexivo al 100 %. Si lo pone
rojo por ejemplo, los reflejos estarán teñidas de rojo.

Primero pruebe con un color gris medio.

Render

Represente. Vea que la tetera se ha vuelto muy reflexiva.

Pruebe con un gris muy oscuro, y también con otro muy claro para ver la diferencia.

Max depth

<!-- p. 294 -->

Aumente el parámetro de profundidad en el material de cristal a 10, tanto para los reflejos como para las
refracciones. Notará un poco más de variación en la reflexión/refracción. En algunos casos aumentar la
maxdepth ayuda a hacer el cristal más realista. Esto no nos importa mucho ahora, porque nuestro ambiente es
también negro, como el color de salida cuando la profundidad máxima (maxdepth) es alcanzada. En ambientes
coloreados el efecto de maxdepth será más apreciable.
Sigamos, ponga maxdepth en 5.

Reflexiones Fresnel

La reflexión Fresnel es un fenómeno que se da en casi todas las superficies reflexivas. Las partes de la
superficie que señalan directamente hacia usted reflexionarán menos que las que llegan con un ángulo mayor.

La cantidad del efecto es controlada por el IOR del material. Puede encontrarlo en los parámetros de refracción.
En la vida real, el efecto fresnel siempre están vinculados. Sin embargo en Vray puede desvincularlo, poniendo
un IOR diferente para la reflexión y la refracción. Para hacerlo, pulse la pequeña L al lado del cuadro del fresnel.
Se mostrará la caja IOR fresnel.

Ponga el fresnel IOR en 1.6 y pulse render. Note que en medio de la tetera hay reflexiones más débiles que en
los costados. Este es el efecto fresnel.

Baje el valor fresnel IOR para aumentar el efecto. Cuanto más abajo, menos reflexionará en el medio. Si va muy
alto, será lo mismo que antes fresnel (> 25).

<!-- p. 295 -->

Tetera 2 material

Duplique el material orange, asígnelo a la tetera pequeña y renómbrela como “tetera 2”. Cambie el color difuso a
rojo oscuro.

Lustre de reflexión

<!-- p. 296 -->

Seleccione el material naranja (orange). Cambie el color de la reflexión a un gris medio. Apague los reflejos
fresnel.

Cambie reflection glossiness de 1.0 a 0.8.

Represente.

Ahora los reflejos son muy borrosas. Para crear este efecto en 3D, también podría poner un bumpmap muy fino
en la ranura bumpmap; pero usando el parámetro de lustre, la interpretación será mucho más rápida.

Juegue con el valor de glossiness para ver lo que sucede.

Medio de lustre 'shinyness', Tan glossiness = 1.0 es 100% Valores brillantes, inferiores no son reflexiones
brillantes o borrosas. Hay mucha confusión sobre esto; muchas personas mezclará bien la revista ilustrada de
término con borroso.

Reflexiones borrosas más lisas

<!-- p. 297 -->

El valor de las subdivisiones bajo el lustre refl controla la suavidad de los reflejos borrosas. Cámbielo a 20 y
represente. El resultado es mucho más liso.

Sepa que 8 subdivisiones significan 8 x 8 = 64 muestras, 20 subdivisiones 20 x 20 = 400 muestras. Duplicar las
subdivisiones significará aproximadamente 4 veces más de tiempo para la representación.

¡¡Asegúrese de que tiene seleccionado AA en QMC adaptable cuando use valores altos de subdivisión!! Si quiere
usar la subdivisión adaptable AA, puede escaparse con valores inferiores (de 3 a 10). AA adaptable alisa mucho
el ruido producido por las subdivisiones bajas. Si tiene muchas reflexiones borrosas en la escena, QMC
adaptable siempre será más rápido.

QMC ajustes: alise más los reflejos borrosos

Si quiere que el ruido sea aún más liso, aumentar las subdivisiones no siempre ayuda. No vaya más alto de 40
para mallaucir el ruido. Una solución mejor suele ser ajustando el QMC.

Abra el cuadro de diálogo de ajustes de render y vaya a QMC. Cambie el umbral de ruido a 0.001 y represente
otra vez. Ahora el ruido habrá desaparecido completamente, pero a costa de alargar el tiempo del proceso.

Los ajustes de QMC proporcionan un modo fácil de acelerar la prueba de render, simplemente aumentando el
umbral de ruido a por ejemplo 0.05. Observe que los ajustes en el QMC también afectarán al cálculo del mapa de
irradiación y DOF, MB, sombras de Área, etc. Por tanto, mallauciendo el ruido th no sólo mejorará los efectos de
brillo, sino también la calidad del GI, etc.

Por ahora, cambie el umbral de ruido a 0.005. Mientras estamos aquí, vaya a la ventana system y abra el post de
Vray (suprima todo el texto excepto la parte del rendertime). Así verá mejor las diferencias de velocidad.

Highlight glossiness

Probablemente ya sabe que 'highlights' está configurado por defecto en los materiales de Max. Bien, estos
toques de luz no son nada más que falsas reflexiones borrosas. Un toque de luz es en realidad una reflexión de

<!-- p. 298 -->

una fuente de iluminación muy brillante.

En las versiones anteriores de Vray, no había ningún modo de representar estos falsos toques de luz con los
materiales VRay (Vraymaterials). Ante la demanda popular, los desarrolladores aportaron falsos toques de luz a
los Vraymaterial.

Observe que estos toques de luz sólo aparecerán si se usan luces en la escena. La luz (skylight) (de claraboya,
luz solar) no genera toques de luz.

Crear un proyector

Para ver el efecto de lustre del toque de luz, cree un proyector de Max dirigido hacia las dos teteras.

Baje el multiplicador de "claraboya" a 0.0 para esta prueba. No queremos que venga ninguna luz del cielo.

En los ajustes de spotlight, seleccione shadows (sombras) y marque las sombras de Vray en la lista tipo de
sombra.

Representación

Represente la escena.

<!-- p. 299 -->

La parte blanca en la parte superior de la tetera es el lustre del toque de luz, la falsa reflexión borrosa. Un
proyector de Max es invisible a la cámara y a los reflejos, pero con este parámetro de lustre de toque de luz,
puede hacerlo visible en los reflejos.

Highlight glossiness unido

Por defecto, el ajuste del highlight glossiness está vinculado al parámetro de lustre refl. Esto significa que cuando
se usa el lustre refl y hay luces en la escena, aparecerá también el lustre de toque de luz.

Apagar los reflejos

Tan ser capaz para represente sólo el toque de luz glosan, tiene que apagar los reflejos para el material. Esto es
posible en Vray, pero el ajuste está oculto en las opciones de la persiana Vraymaterial.

<!-- p. 300 -->

No marque 'trace reflections' y represente otra vez.

Vea que ahora el material tiene sólo las falsas reflexiones brillantes. Este material se parece a un material de
Max con algunas hightlights.

Es un material poco realista, porque refleja la fuente de iluminación, pero no el resto del ambiente.

Ranuras de mapa

Al lado de todos los parámetros de reflexión hay una ranura de mapa. Esto significa que se puede controlar el
color de reflexión, el lustre refl, el lustre de toque de luz y el valor fresnel.

Por ejemplo la ranura de reflexión. El Pulse sobre ella y seleccione "checker" de la lista. Hágalo visible en el visor
para ver si traza correctamente un mapa del objeto.

Reajuste los demás ajustes de reflexión a su valor por defecto (gris medio, ningún fresnel, all glossy = 1.0, trace
reflections en posición on). Suprima el proyector y ponga skylight back a 1.0.

Pulse render.

Verá algo parecido a mi ejemplo. Todas las partes negras del mapa serán no reflexivas, todas las partes blancas
lo son al 100 %.

Pruebe también con el mismo mapa en otras ranuras. Pero tenga cuidado: blanco para el lustre significa un valor
de 1.0, no borroso, y negro significa muy borroso (valor 0.0 para el glossy).

<!-- p. 301 -->

Color de salida

Como con la reflexión, para las refracciones hay también un color de salida. Después de que un rayo haya
refractado el número de veces de maxdepth, entrará en juego este color de salida . Haga clic en la caja de
diálogo y asígnele un color verde llamativo. Represente.
Puede ver claramente lo que las partes de la imagen se acercan el número (5) de Max depth.

Ponga el color de salida en negro otra vez.

Índice de refracción (IOR)

Ponga el IOR (Índice de Refracción de materiales) a 1.0 y represente. ¡El toroide se ha esfumado! Esto ha
ocurrido porque no ha rebotado ningún rayo con este valor de IOR. Como fresnell IOR está vinculado a la
refracción IOR, éste también tiene el valor 1.0, lo que significa que el objeto también se convierte en no reflexivo.
El color de refracción es blanco puro, de modo que los rayos tampoco están teñidos. ¡Todo esto hizo que el
toroide desapareciera!

<!-- p. 302 -->

Lustre (Glossiness)

El parámetro glossiness es similar al de reflexiones. Esto es el empleado debe enturbiar las refracciones. Esto es
uno de la mayor parte de tiempo consumiendo ajustes, tiempos de render irán realmente altos si ponemos
muchas subdivisiones.

Pruebe con un valor de 0.8 con 8 subdivisiones. Verá que las refracciones borrosas tienen mucho ruido debido a
que tiene pocas subdivisiones. Pero vale para hacerse una idea.

Cambie el lustre a 1.0

Opciones: reflexiones sobre la parte posterior

Vaya a las opciones del material de cristal, y seleccione la opción 'reflect on backside'. Esto permitirá al interior
de la superficie reflejar también el ambiente. Para renderizar el cristal, debería dejar esta opción marcada;
genera reflexiones muy agradables y realistas de los interiores. También aumenta el tiempo de elaboración,
desde luego.

<!-- p. 303 -->

Para seguir el tutorial, deselecciónelo otra vez.

Max depth (Profundidad máxima)

Ponga el color de salida a negro y juegue con el parámetro de profundidad máxima hasta que desaparezca la
mayor parte de las zonas negras.

Por lo general no debería ser mayor que 10. Los números mayores solo van a ralentizar el proceso sin aportar
ninguna mejoría.

Refracción GI de cáusticas

La luz que viene de la caja no es una luz directa como la de un proyector de Max. En realidad es tratado como
rebote primario de GI (como el Vray skylight). Si apagara el GI y representase, no habría ninguna luz en
absoluto.

Por esto, es importante que active la refracción de cáusticas GI en la persiana de iluminación indirecta. Intente

<!-- p. 304 -->

representar esta escena sin el GI de refracción de cáusticas.

Verá que las sombras son mucho más oscuras. La luz del GI es incapaz ahora de traspasar el objeto
transparente (no hay ninguna GI cáustica). Las cáusticas son más notables que la luz refractada/ reflejada.

Para continuar, marque otra vez las refracciones cáusticas GI. Vaya también a la persiana de mapa de
irradiación y ponga el predeterminado de costumbre. Cambie el min/max rate a -4 / -2 para acelerar la
interpretación. Note que el GI estará más enturbiado ahora, pero como solo estamos probando, no importa.

Hablaremos más sobre las cáusticas más adelante del tutorial. Por ahora recuerde que tiene que marcar las GI
cáusticas si quiere que el GI atraviese a los objetos transparentes.

Ajustar la "claraboya"

Pulse render. Es demasiado brillante, porque nuestra claraboya está todavía activa. Ponga el skylight multiplier a
0.0 y represente otra vez. Si está demasiado brillante o demasiado oscuro, tiene que jugar con el multiplicador
Vraylightmaterial hasta que se vea bien.

Ahora ya se puede ver claramente la luz que viene de nuestra caja grande, y la fuente de iluminación también

<!-- p. 305 -->

reflexiona en el nudo toroide. El contraste entre el ambiente de luz muy brillante y el negro es muy bueno para
representar el cristal o el metal.

VrayLightMtl

VrayLightMtl

El objetivo es convertir esta caja en una fuente de iluminación. Un modo fácil de hacerlo, es usando un material
especial VrayLightMaterial. Pulse el botón asignar material y escoja VrayLightMtl de la lista. Asigne el material a
la caja y ponga el multiplicador a 8.0

<!-- p. 306 -->

Crear un ambiente

La interpretación se ve muy sosa, porque la única cosa que reflejar o refractar es el groundplane y el color de
ambiente negro.

Cree una caja grande, delgada y posiciónela más o menos como se muestra abajo.

Ajustar los reflejos

El paso anterior se veía extraño, porque por lo general los materiales con tales propiedades de refracción son
también reflexivos. Si pone la reflexión a blanco puro, y marca las reflexiones fresnel, el material se verá mucho
mejor. El material que usted creó es ahora el básico para el cristal.

<!-- p. 307 -->

Color difuso

Cambie el difuso a negro y represente otra vez. El resultado es bastante diferente.

Color de refracción

Represente la imagen. Verá que el objeto parece transparente. El color de refracción gris significa que tendrá
aproximadamente el 50 % de transparencia.

<!-- p. 308 -->

Parámetros de refracción

Vaya al material blanco y mire los parámetros de refracción. La refracción manda rayos muy brillantes que se
desvían cuando van de un medio a otro. Por ejemplo viaja por el aire, luego golpea un objeto de cristal y el rayo
se dobla con un cierto ángulo. Este rayo irá más lejos por el cristal, y eventualmente lo traspasará en un punto,
desviándose otra vez.

Cuánto viaja, un rayo depende del IOR (índice de refracción) del material. Un IOR alto significa muchos rebotes,
IOR = 1.0 significa que los rayos no rebotarán.

El material Vray tiene todas las opciones disponibles para crear cualquier clase de material de refracción. Como
puede ver, muchas opciones son similares a las de los parámetros de reflexión.

Primero, cambie el color refract a un gris medio.

Crear los materiales

Cree un Vraymaterial azul medio para el groundplane, y otro gris muy claro para el nudo toroide y asígnelos a los
objetos correspondientes.

Represente. Debería aparecer algo como la imagen de abajo.

<!-- p. 309 -->

Crear la escena de prueba

Ahora el objeto tetera de Max no es buena porque la malla tiene agujeros, no es "hermética" y no es deseable
para los objetos de refracción. Hice este modelo modificando el nudo toroide de Max porque esta será una forma
interesante para probar, debido a la cantidad de curvas y de zonas delgadas y gruesas que tiene.

Si quiere, use los mismos ajustes que yo.

Estudio de una iluminación estándar

Arranque el Max y seleccione Vray como renderer.

Vaya a 'personalizar -sistema de unidades' y ponga tanto la escala de unidad de demostración como la escala de
unidad de sistema a métrico: milímetros.

Cree 3 esferas con un radio de 35 mm y colóquelas como aparecen abajo.

<!-- p. 310 -->

\2. El groundplane

Intentaremos construir un fondo de un modo sencillo. Por lo general los fotógrafos ponen un paño grande de
color blanco o negro detrás de la escena, doblado por abajo, para que no se vea el borde entre la pared trasera y
el suelo.

Hay muchos de modos de hacerlo. Comenzaré de un cilindro, lo doblaré y lo acabaré con un modificador
meshsmooth. De esta manera, el plano de fondo será muy liso en todas las direcciones, asegurando que no nos
dará reflejos extraños (como cuando se usa -por ejemplo- una caja como escenario).
Vea abajo los ajustes del cilindro, y del modificador meshsmooth.

<!-- p. 311 -->



<!-- p. 312 -->

\3. Crear una cámara

Ahora cree una cámara y colóquela como en la imagen de abajo. Asígnela una lente de 50 mm. Ponga el visor
perspectiva
usar esta cámara, permita 'show safe frame' para ver el proceso.

\4. Crear los materiales

Necesitamos tres materiales: 1 casi blanco, 1 cromo y 1 rojo reflexivo.

Vea los ajustes que yo he usado para los materiales cromo y rojo. (Esto debería serle ya familiar si completó el
Tutorial básico de materiales.

Asigne los materiales a las esferas. El groundplane también usa un material casi blanco.

. Ajuste el Render

<!-- p. 313 -->

Abra el cuadro de diálogo de ajustes del render y haga lo siguiente:
\- Designe Vray como motor de render si no lo había hecho.
\- Tamaño de salida a 480 x 360 píxeles.
\- Interruptores globales: apague las luces por defecto.
\- image sampler en adaptive QMC.
\- antialising filter "mitchell-netravali".
\- indirect illumination: ON.
\- Secondary bounces multiplier en 0.8.
\- Configuración de Irradiance map:
\- "low" preset.
\- hsph subdivs = 20.
\- environment:
\- skylight pure white color, 1.0 multiplier.
\- reflection/refraction pure black, 1.0 multiplier.
\- system:
\- render region division 50 x 50 píxeles.
\- frame stamp: borre todo excepto la parte del rendertime.

Represente la escena, que será similar a esta.

\6. Plano de reflexión/luces

En vez e el skylight, usaremos un luz grande rectangular de VRay (Vraylights) para iluminar la escena. También
la utilizaremos para crear reflexiones agradables. (Como hicimos en el tutorial de ajustes de materiales.

Cree dos Vraylights y colóquelas más o menos como aparecen abajo.

La luz de la izquierda es 400 x 350 mm con un multiplicador 3.5 y la de la derecha 360 x 500 mm con
multiplicador 5.5.

Vaya a la ventana ambiente (Enviroment) Vray y cambie el skylight multiplier a 0.1.

<!-- p. 314 -->

\7. Lo que tenemos hasta ahora

Si pone todas las luces y multiplicadores de cielo como yo hice, la iluminación debería estar más o menos bien.
Hice la luz más brillante con toda la intención, así se crean sombras en una dirección. Si los pusiera en fuerzas
iguales, la imagen sería poco interesante como iluminación, plana, entrando con igual fuerza de todas las
direcciones. Cuanto más grande sea la diferencia entre las dos luces, la iluminación será más dramática.

Primer pic muestra izquierda = 3.5 y derecha =5.5

La segunda izquierda = 2 y derecha =7

Seguiremos con los ajustes 2/7.

Continuemos…

\9. Subdivisión contra QMC

<!-- p. 315 -->

Subdivisión contra QMC

A primera vista, se podría pensar que la imagen de subdivisión adaptable es mejor (tiene menos ruido), pero si
observa detenidamente, el ruido es diferente, no "mejor". En el área de sombra hay una clase de ruido
'enturbiada', comparado al QMC Sampler, que es un ruido nítido constante.

La imagen superior es subdivisión adaptativa AA, la inferior es QMC adaptative AA.

\10. Reducir el ruido

<!-- p. 316 -->

Ahora intentaremos reducir el ruido en ambas imágenes para ver cuál es más rápido para imágenes de alta
calidad.

Cambie Image sampler a Adaptive subdivision AA, min/max=0/2.
Ponga a 30 las subdivisiones para ambas luces y represente.
La imagen no está libre de ruido. (Si hace zoom, puede ver un diminuto bit de turbiedad).

Ahora ponga Adaptive QMC AA, min/max = 1/4
Ajuste las subdivisiones a 36.
En la persiana QMC sampler, cambie el umbral de ruido ruido (threshold) a 0.002. La adpative QMC AA es muy
sensible a los ajustes del QMC. El umbral de ruido es el más importante. (QMC sampler controla la calidad de
todos los cálculos relacionados con 'Quasi monte carlo'. En breve todos los ajustes de las subdivisiones son
QMC, excepto las subdivisiones del caché de luz)
Si hace zoom aquí, también puede ver un poco de ruido, pero más agudo y más liso que el enturbiado de la
subdivisión adaptativa.

Pero en este caso, la subfivisión adaptativa se adapta a QMC AA. Cuando añada materiales más complejos
como glossiness, más luces de área, texturas, mapas de desplazamiento, etc., los tiempos de render para QMC
adaptative no aumentarán tanto como con la subdivis adaptative AA. Por lo general cuando tiene muchos efectos
de brillo (también con DOF, Motion blur,...) es mejor usar QMC adaptative AA.

\11. La opción Store with irradiance map

<!-- p. 317 -->

Como dije, la razón del ruido son las sombras de área. Sobre todo para la interpretación de prueba, podemos
inutilizarlos fácilmente.

Llaman la luz que viene de un Vraylight (o también de la estándar de Max luz 'directa'. Esto significa que no es la
luz GI (el rebote primario o secundario). Una vez que esta luz directa golpea en una superficie, rebota un poco
(según cómo sea de oscura y reflexiva la superficie). Se ha dado en llamar a este rebote "el primer' rebote", y es
calculado por el mapa de irradiación (porque hemos puesto como primario el motor del GI de rebote en el mapa
de irradiación).

Pero el Vraylight tiene una opción "Store with irradiance map" (con mapa de irradiación). Esta opción en realidad
significa 'primero la luz GI del rebote'. En vez de proyectar luz directa, ahora la luz de Vray emitirá primero la luz
de GI y así será calculada por el mapa de irradiación. También significa que cuando golpea en una superficie, y
rebota, se hará luz GI secundaria, y será calculada por el motor GI secundario, QMC GI en este caso.

Poniendo el Vraylight en 'store with IR map', el resultado será que no hay ninguna luz directa más, sólo la luz GI.
Esto significa que todas las sombras también serán creadas por la luz GI. La consecuencia de esto es, que la
calidad de la sombra ya no depende de las subdivisiones Vraylight, sino que es controlada por los ajustes de GI,
a saber el mapa de irradiación (y el GI QMC para los rebotes secundarios). Es importante tener muy claro que
las subdivisiones Vraylight no hacen absolutamente nada si está seleccionado 'store with IR map' !

(Nota: esta opción sólo funciona si el mapa de IR está puesto como primer motor de GI de rebote. ¡Si tiene por
ejemplo QMC GI para el primer y segundo rebote, y luces con "Store with IR map" seleccionados, estas luces no
proyectarán luz!)

Con Store with IR map, representé dos imágenes con la opción 'show GI only' (de la persiana global switches).
Esta opción representa la imagen sólo con la luz GI, sin ninguna luz directa que pudiera haber en la escena.
La primera es con Vraylight normal (sin la opción "store with IR map").
La segunda con ella.

Se ve claramente que en el primer ejemplo, con la luz directa extraída, no hay mucho GI para calcular. Y en el
segundo ejemplo, toda la luz es luz GI.

Este paso es muy importante, debe comprender la diferencia entre "Store with IR map" apagado o encendido, y
la diferencia entre rebote directo-primario y los rebotes secundarios.

<!-- p. 318 -->

La desventaja de esta opción es que habrá más luz de GI de rebote primario, pero, también más luz GI
secundaria proyectada (el cálculo de la luz GI, sobre todo el segundo rebote, es muy costoso). Esto significa que
tiene que confiar en el mapa de IR y los cálculos GI QMC para crear sombras agradables. En el resultado no es
un problema tan grande, porque de todos modos no habrá muchos rebotes secundarios. La Luz que golpea la
parte superior de las esferas por ejemplo (= first bounce), rebotará (second bounce) directamente hacia el cielo.
Por tanto, este segundo rebote no tendrá ningún efecto en la representación. Sólo un poco en medio del piso y
los objetos, o de un objeto al otro. Pero los rebotes secundarios no tendrán una influencia tan grande en la
iluminación ni en la creación de las sombras.

Esto provocará más de un problema en la iluminación de una escena de interior. Allí, el segundo rebote no irá al
cielo, sino que probablemente golpeará en un techo o en la pared, rebotando una y otra vez... Así es que en
estas escenas, los rebotes secundarios tienen un gran impacto sobre la iluminación final y las sombras. En estos
casos, sería una idea buena reducir la cantidad de luz GI, sustituyendo el primer rebote por luz directa. ('store
with IR map' apagado).

Piense en ello, en vez de confiar en comenzar con la luz GI de rebote primario, ahora comience con la luz directa
que ya iluminará mucho la escena (la calidad es perfecta, es una luz directa), entonces hay un primer rebote y
luego un segundo.

Resumiendo: para que la representación no se alargue enormemente puede beneficiarse de Store with IR map,
porque no hay muchos rebotes secundarios. Tendrá que mejorar los ajustes de mapa de IR, acabando en un
cálculo GI más largo, pero la interpretación real de la imagen será mucho más rápida, porque no hay ninguna
sombra difícil que representar. El tiempo total (el cálculo GI + raytracing) será mucho menor que cuando se usan
verdaderas raytraced de sombras de área (aquí el cálculo GI irá más rápido, pero mucho más largo, entonces el
resultado total combinado es mucho mayor).

Vea la imagen con los ajustes siguientes:
\- Adaptive QMC AA 1/4
\- Noise threshold = 0.002 in QMC sampler rollout
\- IR map: Vea los ajustes debajo.
Como puede ver... ¡el tiempo del proceso se ha acortado a la mitad, y comparado a los ejemplos de sombras de
área raytraced, no hay ningún ruido en absoluto! Pero las sombras son un poco menos exactas.

Vaya a los ajustes de mapa de IR y cambie el minimo/máximo a -4 / -3 y el hsph subdivs a 20. En la persiana
QMC sampler ponga el threshold a 0.005. Estos son valores de prueba muy rápidos. Represente la imagen otra
vez. Observe que las sombras están ahora menos detalladas (las esferas parece que flotan un poco). Pero...
¡eh!, 11,3 segundos no están nada mal.

<!-- p. 319 -->

1Final

Final

Ahora, ya debería entender mejor la diferencia entre subdivs adaptative AA y QMC adaptative AA, el efecto de la
opción 'store with IR map', y cómo crear un estudio de iluminación sencillo.

GUARDE ESTA ESCENA para reutilizarla en tutoriales posteriores.

Cristal + líquido

<!-- p. 320 -->

continuar con el resultado de Estudio de una iluminación estándar

\1. Continuemos con el resultado final (la escena que guardó) del tutorial "Estudio de una iluminación
estándar".

Abra el archivo que guardó en el ejercicio anterior. Suprima u oculte las 3 esferas; no las necesitaremos más.

Ponga la persiana render properties con esta configuración:

\- Output size en 400 x 480 píxeles.
\- Global switches: Cierre las luces por defecto.
\- Image sampler en adaptive QMC.
\- Antialising filter "mitchell-netravali".
\- Indirect illumination: ON.
\- Secondary bounces: QMC GI y el multiplier en 0.8
\- Active refractive GI caustics.
\- Configuración de Irradiance map:
\- Min/max=-4 / -3
\- Hsph subdivs = 20 = interp samples.
\- Clr=nrm=0.4
\- Dist=0.1
\- Environment:
\- Skylight pure white color, 0.1 multiplier.
\- Reflection/refraction pure black, 1.0 multiplier.

<!-- p. 321 -->

\- QMC sampler: noise threshold = 0.005
\- System:
\- Render region division 50 x 50 píxeles.
\- Frame stamp: Suprima todo excepto la parte de rendertime.

Vray lights debería tener activada la opción 'store with IR map' para comenzar. La luz de la izquierda tiene un
valor de 3, la derecha de 5. Colóquelos como en la captura de pantalla de abajo.
También cambie la posición de la cámara como yo lo hice, poniendo un objetivo de 85mm.

La escena debería tener las unidades en el sistema métrico (mm).

Continuar con el Importar el modelo de cristal

El cristal es un material que cada uno intenta representar probando de distintas maneras. Vray es capaz de
representar el cristal de forma muy realista en muy poco tiempo.

Ya se explicó bastante sobre la creación del cristal en el tutorial Ajustes básicos de materiales. Muchas cosas
se repetirán aquí, pero esta vez representaremos un objeto verdadero.

Abra o cargue el fichero "glass01.3ds" (está en la carpeta "Downloads" del directorio del 3ds max). Use la función
"importar" para llevarlo a la escena (para apagar 'convert units' en las opciones de importación). El cristal debería
ponerse como en la imagen de abajo. Si no, simplemente redimensiónelo. Probablemente sus unidades estén
mal puestas si la copa es demasiado grande o pequeña.

<!-- p. 322 -->

Subirlo un poquito

Cualquier renderer siempre tendrá problemas con el traslapo de caras. Sobre todo con materiales transparentes
puede causar problemas. El cristal profundiza la mentira de caras exactamente sobre las caras del plano de
fondo, ellos están en la misma posición exacta. ¡Aunque no sea muy visible aquí, es bueno recordarlo, para
evitar caras coincidentes! Una subida de la copa de 0.2 mm es ya más que suficiente.

<!-- p. 323 -->

Crear el mat. básico de cristal

Crear el material básico de cristal

Cree un material nuevo Vray. Primero aclararemos el cristal altamente reflexivo. Para hacerlo, primero ponga el
color difuso a nego puro . Entonces la refracción de juego colorea a blancopuro. Blanco puro significa el 100 %
de refracción, terminando en el componente difuso que no tiene ningún efecto en absoluto.

Haga la reflexión colorear casi blanco puro y compruebe las reflexiones fresnel.

Esta es la base de nuestro material cristal. Es un cristal claro, reflexivo al 100 %.

Asigne el objeto de cristal y represente. Debería parecerse a esta imagen:

<!-- p. 324 -->

Reflexión sobre la parte posterior

¿Note la frontera oscura sobre la superficie interior de la copa? Para deshacernos de esto, conectaremos la
opción 'reflect on backside' en las opciones del material.

Represente otra vez para ver la diferencia.

Esta opción crea reflexiones internas, un efecto que también ocurre en la realidad.

<!-- p. 325 -->

Profundidad de Refl. / Refr.

Estas opciones controlan el número de veces que un rayo puede reflexionar o refractar antes de que sea quitado
de remotos cálculos. Los números más bajos serán más rápidos, pero irán demasiado bajo y el objeto o algunas
zonas se verán en negro.

Auménte ambas a 10 y represente otra vez. La diferencia es enorme en el pie y en la parte media de la copa
(porque en estas partes, las reflexiones internas pasarán mucho, excediendo rápidamente la profundidad
máxima).

El valor 10 están bien. ¡No lo ponga demasiado alto porque el tiempo de procesamiento aumentará mucho!

Ajustar el sistema

Nuestro estudio es un poco 'too much' para esta escena. Lo ajustaremos apagando la luz izquierda. Para
compensar la disminución de luz, ponga el multiplicador de claraboya de ambiente a 0.4.

Represente la escena. Debería parecer más o menos a esta:

<!-- p. 326 -->

Relleno con agua

Para llenar una copa con agua, debería modelar el agua. Pero no es tan sencillo como parece.
Ante todo, la superficie del agua se doblará por encima de donde toca el cristal, debido a las fuerzas de
adherencia. Este efecto tiene que ser modelado, o el agua no parecerá muy realista.

Ahora hay un problema con las superficies que coinciden. Si modelamos el líquido exactamente como la
superficie interior de la copa, la interpretación parecerá extraña debido a que estas caras son coincidentes (el
vaso de la derecha). El mejor sistema es modelar el agua un poco más grande que la superficie del interior de la
copa. Si la modelamos ligeramente más pequeña, no sería realista ni lo uno ni lo otro (el vaso de la izquierda).

Modelé la copa en el Rhinoceros, y es una curva torcida. Más adelante le mostraré estas curvas también, para
ver cómo se modeló el agua contra el cristal.

Importar el agua

Abra el modelo en Max (apague 'convert units'). El agua debería estar perfectamente colocada en la copa.

Cree un Vraymaterial nuevo, llámelo "agua" y dele un color difuso blanco puro.

Represente la escena.

<!-- p. 327 -->

Material agua

Vaya a su material de agua y cambie los ajustes según la imagen de abajo. De hecho, son los mismos ajustes
que el cristal, sólo que el IOR es diferente.

Vaya también a la persiana opciones y conecte reflect on backside like (reflexionar en la parte posterior), como
hicimos con el material cristal.

<!-- p. 328 -->

Representar otra vez

Ahora tenemos una bonita copa de vino llena de agua.

Como se puede ver, es bastante fácil conseguir un resultado decente para el cristal y el agua en Vray. Ya
nuestro primera representación se ve bastante bien. Pero para depurarla, tiene que conocer algunos trucos. Las
preguntas sobre el cristal aparecen mucho en los foros de Vray, así que espero que este tutorial aclare un poco
algunas cosas.

Vino tinto

Copie el material agua y renómbrelo como 'vino tinto'. Cambie el color de niebla a un rojo saturado, y baje el
multiplicador a 0.05. Nos dará refracciones rojas. Aplique el material del vino al agua. Represente para ver el
efecto.

Experimente con diferentes colores y multiplicadores para crear también otros líquidos.

Naturalmente, puede hacer lo mismo con el material de la copa, para crear cristales coloreados.

<!-- p. 329 -->

Ampliar la escena

Para dar a la escena un aspecto más interesante, copiaremos la copa y la pondremos en el suelo, como si se
hubiera cáido caído.

Seleccione el modelo de copa y cópielo, gírela y colóquela en la posición de abajo.

Cambie el tamaño de salida de render a 430 x 480 píxeles.

<!-- p. 330 -->

Girar la cámara

Con la herramienta “rotar”, gire la cámara -8 grados. Muévala también para crear una composición mejor.
Represente la escena. Debería parecerse a ésta.

\15. Smaller Vraylight

Las sombras son muy débiles porque nuestra luz de área es muy grande. Ajustaremos el Vraylight, lo haremos
más pequeño y la nueva posición. Puede ver en la imágen de abajo como lo coloqué yo. No sólo es más
pequeño, sino que también la alejé.

U-size = 250 mm y V-size = 300
Light multiplier está en 22. Es mucho más alto porque la luz de área es más pequeña.

Cambie también el multiplicador del cielo (ajustes de ambiente Vray enviroment) a 0.15 en vez de 0.4. De esta
forma, la iluminación del ambiente no se verá tanto como antes sobre las zonas de sombra .

Nice caustics

<!-- p. 331 -->

Esta luz más pequeña también producirá cáusticas.

Recuerda la confusión que hay con GI caustics, que ya vimos en el tutorial de ajustes básicos de
materialesBien, aquí los usaremos otra vez.

Primero represente la escena con los nuevos ajustes de luz. Debería parecerse a la imagen inferior. Observe
que las sombras son mucho más visibles ahora. Cuanto más pequeña la fuente de iluminación, más
pronunciadas serán las sombras.

Ninguna GI caustics

En los ajustes de GI, ponga GI de refracción de cáusticas. Verá claramente que las sombras se oscurecen.
Ninguna luz es capaz de atravesar los materiales transparentes.

Esto es solamente un recordatorio para mostrarle el efecto de GI caustics.

Cambie el GI de refracción de cáusticas como estaba antes.

Por lo general no uso GI de reflexión de causticas, porque en la mayoría de los casos perjudican en vez de
beneficiar. El modo de refracción suele ser el más importante, como puede en este ejemplo.

Cáusticas más agudas

<!-- p. 332 -->

Como la la calidad de la sombra y de las cáusticas se controlan totalmente por los ajustes del mapa de IR, los
depuraremos.

Note que las sombras se crean por el mapa de IR porque tenemos seleccionada la opción 'store with IR map' en
Vraylight. Entonces nuestro Vraylight no proyecta luz directa, sino la luz de GI.
Abra la persiana del mapa de irradiación y cámbie la configuración a:

Min/max = -4 / -1
Hsph subdivs= 35

La calidad de las muestras aumentará debido a que hay más subdivisiones hsph.

Conecte 'show calc fase' para ver el progreso del cálculo del mapa de IR.

Como puede ver, las cáusticas ya son más perceptibles.

GI en alta calidad

<!-- p. 333 -->

Si quiere las mejores soluciones de GI de aumentar caustics y la calidad de la sombra, tiene unas opciones.

Primero debe aumentar los ajustes min./máx., a por ejemplo -2 / 1. Para resoluciones bajas,-2 / 1 es realmente
de alta calidad, no vaya más alto o perderá la ventaja.

También puede aumentar las hsph subdivs. Esto calculará mejor cada muestra que tome.

El thresolt también es importante, yendo de 0.4 a 0.3 tendrá un efecto enorme, pero también sobre el tiempo de
procesado... El dist thresolt puede estar también aquí (más muestras donde los objetos están próximos,
importantes para la zona bajo el pie de la copa)

¿Qué ajustes son los mejores? Todos un poco.

El ajuste Min/Máx. tiene el impacto más grande. Para esta interpretación usé los siguientes ajustes de mapa de
IR :

\- Min/max = -3 / 1
\- Hsph subdivs = 40
\- Clr = 0.35
\- Nrm = 0.4
\- Dist = 0.25

El caustics (sobre todo estos bajo el cristal que estáabajo, mira la zona del pie) están mucho mejor ahora. Pero el
tiempo aumentó mucho... Por lo general no necesitará estos ajustes tan altos, porque ningún cliente notará la
diferencia.

Observe que el ajuste máximo de + 1 sólo es utilizado para la resolución 430 x 480.

Para resoluciones de 640 a 800 píxeles, use -3 / 0 como los más altos (-4 / -1 para 1280 a 1600 etc.). Explicaré
el comportamiento del mapa de irradiación en otro tutorial.

\20.

<!-- p. 334 -->

Como puede ver, necesitamos ajustes de mapa de IR muy altos para asegurarnos de que las sombras y las
cáusticas serán calculadas correctamente.

Como dije antes, la calidad de la sombra depende de los ajustes del mapa de IR debido a la opción en el ajuste
de iluminación de Vray Store with IR map , tratando la luz como luz GI en vez de directa.

Apagando esta opción, las sombras serán raytraced, que termina muy de alta calidad. ¡Los tiempos seráb
mayores, pero ya que la calidad depende ahora casi completamente de las subdivisiones de la luz, podemos
usar ajustes más bajos del mapa de IR! Tan IR el cálculo de mapa se acelerará, y el pase de interpretación real
reducirá la velocidad, siendo más o menos el mismo tiempo total, pero con mejores detalles en las sombras.

Cuando use sombras de área raytraced, note que el GI caustics todavía será calculado por los ajustes de mapa
de IR (Vraylight es la única luz capaz de producir luz directa y GI caustics al mismo tiempo, y es una luz ideal
para interpretaciones). Por tanto, no podemos ir demasiado bajos con estos ajustes o las cáusticas perderán
demasiada calidad.

Apague la opción Store with IR map en los ajustes de luces Vraylight, y pónga las subdivisioness a 30.

Vaya a los ajustes de mapa de IR y el cambie min/max a -4 / -1, y las subdivisiones hsph a 35.

Represente la imagen y observe el proceso. Vea que durante el cálculo del mapa IR, todo se oscurece, porque
Vraylight no proyecta ya la luz GI. Este pase irá bastante rápido, pero el pase de interpretación real irá lento
porque la luz directa (y las sombras de área) también tienen que calcularse ahora.

El resultado es muy agradable. Las cáusticas están un poco menos detalladas, pero se compensa por las
sombras.

Imagen final

<!-- p. 335 -->

Ahora representaremos la imagen en una resolución más alta.

Ponga la salida a 717 x 800 píxeles.

Queremos la misma calidad de GI que en la imagen anterior, pero como los ajustes del mapa de IR dependen de
la resolución, tendremos que tirar una moneda al aire. Kinda dobló la resolución, para tener la misma calidad de
GI, sólo tenemos que bajar los valores mínimos y los máximos a 1. Tan ponen estos en -5 / -
\2. El tresholds y hsph subdivs no afectan a la resolución; déjelos con sus valores actuales.

Para deshacerse del ruido último en las sombras y anti aliasing, vaya a la persiana QMC y cambie el umbral de
ruido a 0.002.

¡Represente! ¿Qué le parece?

Spot3D

<!-- p. 336 -->

Tutoriales

Trazar un mapa de fotones
Técnicas básicas para el VRay Advanced
Ejemplos de las funciones del programa con diferectes ajustes. (actualizado)

Trazar un mapa de fotones

En este tutorial examinaremos el trazado un mapa de fotones en el VRay y los modos de usarlo.

¿Cómo trazamos un mapa de fotones?

El trazado de un mapa de fotones es una técnica para calcular la iluminación global. Sin embargo, a diferencia
del mapa de irradiación, que comienza a remontar rayos de la cámara, el mapa de fotones traza un mapa de
rayos de las luces en la escena. Los dos modos no son mutuamente exclusivos, y para tener los mejores
resultados, el mapa de fotones y el de irradiación deberían usarse conjuntamente.
El mapa de fotones tiene muchos parámetros que tienen producen resultados muy interesantes; aquí no
hablaremos de todas sus posibilidades, solamente indicaremos los ajustes que están comprobados y que
funcionan bien la mayoría de las veces.

Temas tratados en este tutorial

Configuración inicial
La caja Cornell
Más difícil: el atrio Scorza

Configuración inicial

Configuración inicial

Para todos nuestros ejercicios, comenzaremos con los ajustes siguientes para el mapa de fotones (observe que
pueden ser diferentes de los que viene por defecto.

Convert to irradiance map - off
Auto search distance - off
Max photons - cero
Convex hull area estimate - off
Store direct light - on
Retrace threshold - cero

Los únicos parámetros que usaremos realmente son:

Max density - Define la resolución (el detalle espacial) del mapa de fotones. La información de la iluminación del
mapa de fotones se obtiene en un número de puntos sobre las superficies de los objetos de la escena. Este

<!-- p. 337 -->

parámetro define la distancia entre aquellos puntos. Con los valores más bajos los puntos estarán más próximos
el uno del otro y serán más numerosos. En los valores más grandes las muestras de luz estarán más alejadas la
una de la otra y habrá menos. Obviamente, este parámetro depende de la escala de la escena. El cambio de
este parámetro supondrá un nuevo cálculo del mapa.
Search distance - Define cómo será reconstruida la iluminación de los puntos descritos arriba. Puede pensar en
ello como enturbiar el mapa de fotones. Debería ser más grande que la densidad máxima, pero el valor exacto
dependerá de cómo de borroso quiere que sea el resultado del mapa de fotones. Los valores de 2-5 veces el
valor de la densidad máxima funcionan bien. El cambio de este parámetro no requiere de un nuevo cálculo del
mapa, ya que solo se usa durante la interpretación.
Los otros parámetros los mantendremos en sus valores por defecto, pero se pueden cambiar cuando se
necesite:

Bounces - Esto controla el número de rebotes de luz; puede ponerlo a cualquier valor; más rebotes significan un
cálculo más lento del mapa de fotones. Lo mantendremos en 10, pero puede ajustarlo como quiera.

Multiplier - Es un multiplicador para el mapa de fotones; lo mantendremos en 1.0, pero puede cambiarlo si lo
necesita.

Aquí hemos limitado los parámetros del mapa de fotón que usaremos a dos solamente -Max density, y Search
distance. Estos son suficientes para controlar el mapa de fotones. Además de estos ajustes, la calidad del mapa
depende del número de fotones emitidos por las luces de la escena. Más fotones emitidos significan un mapa
más alisado y más exacto. El número de fotones es controlable para cada luz desde el cuadro de diálogo Light
settings, accesible desde la persiana VRay System.

La caja Cornell

Un ejemplo simple – la caja Cornell

Veremos el efecto de estos dos parámetros sobre una escena sencilla Cornell parecida a una caja.
Puede abrir la escena "cornell_box.max" guardada en el directorio de Max. Es una escena muy simple de un
espacio cerrado con paredes coloreadas de manera diferente y una luz de punto. Las paredes tienen materiales
VRay porque actualmente los fotones funcionan solamente con materiales VRay.
Note que la luz de punto tiene el cuadrado inverso falloff y un multiplicador bastante alto. Esto es porque las
luces verdaderas tienen el cuadrado inverso falloff, y el fotón traza por defecto un mapa del cuadrado inverso del
falloff.
Esto es lo que se ve si se representa el archivo.

Ahora conecte el GI y ponga el método de mapa de fotones, tanto para rebotes primarios como para
secundarios. Apague Auto search dist, ponga Max photons a 0, Retrace threshold a 0.0, y Max density a
10.0:

<!-- p. 338 -->

Si representa, debería tener este resultado:

Un poco oscuro, pero esto puede corregirse aumentando Secondary bounces multiplier ( persiana Indirect
illumination) a 1.0. Si representa otra vez, debería verse esto:

<!-- p. 339 -->

Representa bastante rápido, y es una aproximación bastante buena de la iluminación de la escena. Obviamente,
está lejos de ser una imagen de buena calidad, pero luego nos pondremos a ello.
Ahora vaya al diálogo Render, y en la persiana System, haga clic en el botón Light settings. En el cuadro de
diálogo que se abre, seleccione la luz de punto y ponga su parámetro Diffuse subdivs a 500. Esto controla el
número de fotones difusos emitidos por la luz (no directamente, aunque el número real de fotones sea el
cuadrado de este número, en este caso -250,000). Cierre el cuadro de diálogo de ajustes de luz) y represente
otra vez:

Tarda más, pero puede advertir que se ha reducido el ruido de las muestras individuales de luz, aunque la
imagen esté todavía sucia. Podemos reducir la suciedad aumentando el parámetro Search distance. Póngalo a
40 y represente otra vez:

<!-- p. 340 -->

El resultado es mucho mejor, aunque sigue siendo muy borroso. También vea que las esquinas están oscuras.
Las esquinas oscuras no son fáciles para evitar con el mapa de fotones, pero se puede reducir el efecto. Ahora
ponga Max density a 5.0 y Search distance a 10.0:

El efecto de las esquinas oscuras se ha reducido mucho, pero la imagen está todavía muy manchada. Para
disminuir el ruido, aumente las Diffuse subdivs para la luz a 1500:

El ruido de las muestras se reduce otra vez. Ahora podríamos aumentar otra vez el parámetro Search distance
para alisar el resultado, sin embargo haremos algo más -usaremos el mapa de irradiación para hacer el
alisamiento. En la persiana Indirect illumination, marque el método First diffuse bounce Irradiance map
cambie a High el mapa de irradiación predeterminado. Si representa, se verá así:

<!-- p. 341 -->

La caja Cornell de la escena es muy fácil para un algoritmo de iluminación global, desde ella es muy pequeña la
oclusión (objetos que proyectan sombras y paran la luz). Después veremos un ejemplo más difícil: la escena del
Atrio Sponza.

Más difícil:el atrio Sponza

Ahora veremos cómo usar el mapa de fotones en una escena más compleja, el Atrio Sponza, que ha sido
modelada por Marko Dabrovic. Cargue la escena inicial contenida en la carpeta Sponza. Si representa
enseguida, la escena se verá así:

Observe que mapa de fotones no trabaja con "la claraboya". Esto es así porque los fotones necesitan de una
superficie verdadera para emitirse. Por lo tanto, el mapa de fotones no es conveniente para escenas exteriores.
Sin embargo, en escenas donde "la claraboya" entra por pequeñas aperturas (como las ventanas), se puede
"invitar" a la luz poniendo luces de VRay en estas aperturas. En el caso de la escena Sponza, hemos puesto una
luz de VRay en lo alto del edificio, que es la única claraboya del lugar.
Ahora seleccione Iluminación Global y escoja el mapa de fotones tanto para los rebotes primarios como
secundarios difuso. Ponga los Multiplier de los rebotes secundarios a 1.0. Vaya a la persiana Global photon
map y ponga en off Auto search distance; Retrace threshold a 0.0 y Max photons a 0:

Después, debemos determinar un valor bueno para Max density. Escogeremos un valor para Search distance.

Un buen valor para Max density depende de la escala de la escena y del detalle deseado del mapa de fotones.
Hay un ayudante en la escena, para medir la distancia entre dos columnas. Su longitud es casi de 6 unidades.
Un valor bueno podría ser, digamos, una décima de esta distancia. Pónga Max density a 0.6 y Search distance
al doble de este valor, 1.2 y represente. Debería tener un resultado parecido a este:

<!-- p. 342 -->

El resultado es bastante borroso, de modo que está claro que necesitaremos valores inferiores para Max density
y Search distance. Después de algunas pruebas, hemos encontrado que con 0.05 para Max density y 0.1 para
Search distance se produce el siguiente resultado:

Es obvio que tiene mucho ruido, pero el detalle (el tamaño de las manchas) parece ser bastante bueno.
Oscureceremos áreas porque no tenemos suficientes fotones emitidos por las luces. Para corregir esto, vaya a la
persiana Sistema y haga clic en Light settings. Seleccione ambas luces de la escena y pónga las Diffuse
subdivs a 500 (lo que significa 500 x 500 = 250.000 fotones por cada luz). Cierre el cuadro de diálogo Light
settings y represente. Ahora lleva más tiempo, pero el resultado es mejor:

<!-- p. 343 -->

De todos modos, necesitaremos más fotones para un buen mapa, entonces se pone el Diffuse subdivs para el
sol (el objetivo dirige la luz) hasta 2.000 (lo que significan 4.000.000 de fotones) y el Diffuse subdivs ya que
VRay alumbra a 2.500 (lo que suponen 6.250.000 fotones). Cierre el cuadro de diálogo Light settings y
represente. Ahora lleva bastante más tiempo (varios minutos), pero el resultado es mucho mejor:

Para ahorrar tiempo en las siguientes interpretaciones, puede guardar el mapa de fotones en el disco: vaya a la
persiana Global photon map y pulse en botón Save to file. Escoja cualquier nombre para el mapa de fotones y
guardelo. Entonces ponga el mapa de fotones Mode a From file y usando el botón Browse elija el mapa que
guardó. Ahora podemos jugar un poco con Search distance para revolver el mapa de fotones un poco más.
Pónga Search distance a 0.4 y represente:

<!-- p. 344 -->

El mapa es más liso, pero se puede ver claramente el efecto de los bordes oscuros. En vez de usar el mapa de
fotones solo para la GI, usaremos el mapa de irradiación para alisar la GI. Ponga el valor Search distance a 0.1
y el primer método de rebote difuso Irradiance map. Active la opción Show calc. phase, escoja High como
mapa de irradiación predeterminado y represente:

Nota: el mapa de fotones es independiente de la vista. Podemos representar una vista diferente sin calcular de
nuevo el mapa de fotones (aunque el mapa de irradiación todavía tiene que ser calculado):

<!-- p. 345 -->

En esta imagen se pueden ver algunos "artefactos" (manchas) en las esquinas donde se encuentran dos
superficies. Esto pasa porque el mapa de fotones tiene demasiado ruido en esas zonas, que también se reflejan
en el mapa de irradiación. Así es como aparece el mapa de fotones en esta vista:

El ruido es porque la luz tiene más difícil entrar en las zonas cerradas de una escena. Un modo de reducir el
ruido es disparar aún más fotones. Aquí está el mapa de fotones con 6.000 subdivisiones (36.000.000 de
fotones) para el sol, y 5.000 subdivisiones (25.000.000 de fotones) para la luz de zona:

Esta es la misma imagen, pero con el mapa de irradiación como primer método difuso de rebotes:

<!-- p. 346 -->

Otro modo de reducir los artefactos es aumentar el valor de la distancia de búsqueda, que enturbiará el mapa un
poco más; sin embargo también hará más pronunciado el efecto de los bordes oscuros. Esta imagen fue
renderizada con una distancia de búsqueda de 0.2; se usó el mapa de fotones de baja resolución original:

Aún hay otra forma de tratar con los artefactos, que es aumentar el valor Retrace threshold a su valor por
defecto de 2.0. Esto hará que VRay calcule la GI directamente para los rebotes secundarios cerca de las
esquinas, en vez de usar el mapa de fotones. Esto significa que el mapa de irradiación será lento de calcular,
pero las esquinas serán algo mejores. La imagen siguiente fue representada con Search distance a 0.1 y
Retrace threshold a 2.0:

Técnicas básicas para VRay Advanced

<!-- p. 347 -->

Temas abordados en este tutorial:

Nota: sólo funciona con 3Ds max 8 o posterior.

Iluminación exterior
Ajustes ambientales
Escena nocturna
Material de Luz de VRay
Sangría de Color
VRay Toon
Iluminación de Interior
HDRI
Ajustes Básicos de Materiales
Desplazamiento de VRay

Abra o descargue el archivo Basic_V-Ray_Tut_Start.max

Iluminación exterior

<!-- p. 348 -->

Antes de comenzar pongamos la configuración siguiente:

\- Global Switches: apagar Default Lights.
\- V-Ray Image Sampler: Use Adaptive Subdivisión. (Por ahora)

<!-- p. 349 -->

\- V-Ray Indirect Illumination (GI): Asegúrese de que GI está conectado.
\- V-Ray Indirect Illumination (GI): Use Irradiance Map (IR Map) para los rebotes primarios.
\- V-Ray Indirect Illumination (GI): QMC para los rebotes Secundarios.
\- V-Ray Environment: en el GI Environment Check Override de Max, cambie el color ambiental al de su elección
(dependiendo de la escena)
\- V-Ray Environment: Reflection/Refraction: Compruebe que está anulado.
Max's ( Esto no es importante ahora. pero lo será para HDRI)
\- V-Ray QMC Sampler: estos ajustes pueden estar un poco altos por ahora, pero entraremos en esto más
adelante.
\- V-Ray Irradiance Map: ponga la predeterminada.
\- Colocar los parámetros del Mapa de Irradiación básicos como los de la imagen (están optimizados para una
representación rápida)
\- Dejar los demás ajustes por defecto, por el momento momento.

Environment Adjustmnets

Aquí se ve un ejemplo de lo que puede pasar en una escena si el ambiente está demasiado alto. Como puede
ver, la imagen se ve apagada y sobresaturada.

El ajuste del ambiente de GI a .6 fue el que produjo este resultado.

Nota: el efecto "Apagado" también se debe al Objetivo la Luz directa en la escena. En combinación con las luces,
un GI alto de los multiplicadores de Ambiente pueden causar resultados no deseados. Por contra, es posible
iluminar una escena usando solamente el GI enviroment.

<!-- p. 350 -->

\-Aumente el GI Environment Multiplier a 1.0 y apague Target Direct Light (Direct01)

\-Represente la escena.

Como puede ver, esta prueba produce sombras muy suaves e indefinidas. Este método puede utilizarse para
después. Se puede añadir un mapa de bits al GI Environment pulsando "None" Y buscando un bitmap de su
elección. (Añadir un bitmap al GI environment es parecido, lo mismo que con la iluminación HDRI que veremos
más abajo)

Escena nocturna

\-Ponga GI Environment a 0.4 y un color parecido al de debajo.
Incluso en las noches más oscuras, en medio de en ninguna parte, siempre habrá algún tipo de "luz ambiental"
(en diferentes grados, desde luego). La Luz de las estrellas, la luna, o como en muchas escenas nocturnas, la luz
de los edificios circundantes y en general la "civilización" puede crear la suficiente luz ambiental para ver un
objeto... incluso si éste no tiene ninguna fuente de iluminación propia. (Todo esto depende de la escena) Un
buen modo de tener esta luz ambiental es usando el GI environment.

<!-- p. 351 -->

\-Asegúrese de que la luz Direct01 esté desconectada y luego seleccione y encienda la luz "Inside Omni". Esta luz
simplemente proporciona alguna iluminación interior no tan oscura.

\-Represente la escena. Debería ser algo parecida a la imagen de arriba.

Material luz VRay

El material de luz de VRay le permite crear una fuente de luz con cualquier geometría. Yo apliqué una luz VRay a
la cúpula de la estructura.

<!-- p. 352 -->

\-Abra al Editor de Materiales (M), pulse sobre una ranura vacía de material y en el botón superior derecho que
pone "Estándar". (Si el botón es V-RayMtl, no se ha seleccionado una ranura apropiada)

\-Cuando abra el buscador de Material/Mapa seleccione la V-RayLightMtl resaltada en la parte de abajo de la
lista, como se ve arriba.

En el Editor de Materiales puede hacer los ajustes de la Luz de VRay. Juegue con el color y el multiplicador
hasta conseguir los resultados deseados.

<!-- p. 353 -->

También puede usar un material estándar de MAX para producir luces geométricas. El curving tube tiene un
bitmap de arco iris en la ranura del mapa de self illumination. El material es un estándar de MAX.

Sangría de color

\-Apague la luz "Inside Omni" y encienda la luz "Direct01".

<!-- p. 354 -->

\-Debajo de V-Ray Environment, ajuste el GI Environment como lo teníamos antes, cuando hicimos la luz solar
directa. Dé al multiplicador un valor de 0.3 y ponga un color amarillo claro.

\-Seleccione la esfera de encima de la estructura y asígnela el material "Yellow1".

\-Represente la escena. ¿Es parecida a la de arriba?

Vea los efectos de sangría en color. La Luz salta de la esfera a los objetos circundantes. Aunque este efecto
sucede realmente en la realidad, yo a menudo lo veo muy exagerado en las interpretaciones. Puede desaturar
sus materiales (o su correspondencia bitmaps) para disminuir este efecto.

VRay toon

VRay Toon

\-Pulse enviroment (o pulse "8"). Esto despliega los cuadros de diálogo Environment y Effects Dialog.

\-En la persiana Atmósfera pulse el botón "Add". Seleccione VRay Toon de la lista que aparece.

\-Abra la pestaña que hay debajo de Enviroment y Effects para ver los ajustes de VRay Toon y cambie la línea de
pixeles a world pulsando sobre el botón de radio "World". Escriba un valor World de 0.6, como se muestra arriba.

<!-- p. 355 -->

\-Represente la escena. Debería tener un resultado similar a la de arriba.

Nota: puede modificar el color y el grosor de la línea para lograr los resultados que desee. También puede usar
un bitmap en la ranura line color si lo prefiere.

Iluminación interior

<!-- p. 356 -->

\-Ponga la Camera02 y asegúrese de que la luz "Inside Omni" esté apagada.

\- Presione "8" para abrir la caja de diálogo Environment y Effects. Debajo de la persiana Atmósfera seleccione
VRay Toon de la lista Effects. Con VRay Toon seleccionado pulse el botón suprimir. Para este interior se
requiere del VRay Toon el efecto apagado.

\-Escoja Pane01, pulse derecho en el visor y ponga las propiedades de VRay como se aprecia abajo.

\-Con las Propiedades de VRay abiertas marque "Matte object", arriba a la derecha. Marque shadows en Direct
light.

\-El objeto de Matte crea el plano invisible pero todavía nos dará sombras y reflejos. (Útil para el estudio de
iluminación). Hemos hecho esto para que el plano del suelo se resalte en el interior. (También para explicar las
propiedades de los objetos VRay). Hay muchos ajustes útiles en las propiedades de objeto VRay.

<!-- p. 357 -->

\-Represente la escena.

Evidentemente, está muy oscura. Tan chulo como es el VRay, la mayoría de las veces necesita de alguna ayuda
para iluminar las escenas de interiores. En otras palabras, solo un rayo directo de luz no es suficiente. Aquí es
donde entran las Luces de VRay en las ventanas. Aviso: están colocadas fuera de la ventana (ajuste la posición
a sus necesidades) y es de la misma forma que la ventana.

\-Seleccione la V-RayLight01 y pulse la etiqueta modificar del panel de control.

\-Conecte la V-RayLight01 pulsando el checkbox que está debajo de la persiana parámetros. Otras cinco luces
VRay en la escena son los casos de Light01 y debería encenderla también. Asegúrese de que esté marcado
"Invisible" . Si no lo está, la luz de Direct01 no podrá atravesar las luces de VRay.

\-Con las luces marcadas, represente la escena. Debería aparecer una imagen parecida a la de arriba.

La imagen se vealgo granulosa con los ajustes de Luz por defecto de VRay. Para corregirlo podemos cambiar
algunos ajustes en la persiana VRay QMC Sampler.

<!-- p. 358 -->

\-Abra la caja de diálogo Render Scene si no está ya abierta. (Presione F10)

\- Pulse la etiqueta Renderer y la casilla debajo de la persiana "V-Ray QMC Sampler" y ábrala si está cerrada.

\-Haga los ajustes necesarios para que se parezca a la imagen de abajo:

\-Represente la escena.
Note como los ajustes que hemos hecho han reducido el grano a un nivel más tolerable. Sin embargo, el tiempo
del proceso se ha duplicado. Tendrá que probar con los ajustes del QMC Sampler hasta que tenga un nivel
óptimo de calidad y velocidad. Esto es más fácil de decir que de hacer, y desde luego, varía de escena a escena.

<!-- p. 359 -->

Comparación de ajustes. Las flechas amarillas muestran la línea divisoria de la misma escena con dos ajustes
diferentes.

Iluminación HDRI

El archivo HDRI usado en este tutorial ha sido creado por Aversis. Visite su sitio para ver más tutoriales (en
inglés) sobre iluminación HDRI y muchos otros temas de VRay.
\-Cambie a Camera03 y ponga los siguientes objetos de 3DS max: Bowl, Glass, Teapot, Torus Knot y Water.

\-Represente la escena. Debería ser similar a la imagen de arriba.
La imagen está iluminada solamente por la luz Direct01 y los rebotes de la GI.

<!-- p. 360 -->

\-Presione "M" para abrir al Editor de Materiales. Pulse sobre el material V-ray HDRI, arriba a la derecha.

<!-- p. 361 -->

Nota: cargue un archivo VRay HDRI seleccionando una ranura vacía y pulse el botón azul "Get Material" que
está destacado en amarillo debajo. Cuando el buscador de Material/Map se abra, seleccione la opción VRayHDRI (resaltada en amarillo, arriba).

\-Arrastre el material HDRI del editor de materiales a ambas ranuras de ambiente localizadas en la persianaVRay
Environment. Escoja y pulse OK.

<!-- p. 362 -->

\-Antes de representar la escena tenemos que apagar la luz Direct01 y asegurarnos de que el multiplicador de GI
Environment esté puesto a 1 (resaltado en amarillo arriba). Como lo único que ilumina la escena es la luz HDRI,
el multiplicador de ambiente GI tiene que estar más alto.

Nota: se puede, por ejemplo, usar una luz directa (la luz del sol) conjuntamente con la iluminación HDRI. Pero,
sería buena idea tener una más poderosa que la otra para evitar "quemar" las imágenes (vea la sección 2).
Asegúrese de que los parámetros HDRI están como en la imagen de más arriba. (Juegue con los ajustes más
adelante)

\-Represente la escena. Sus resultados deberían ser similares a la imagen que está encima.

Las sombras son mucho más suaves e indefinidas. La apariencia es similar al ambiente directo descrito al
principio de este tutorial. Sin embargo, hay diferencias sutiles. No crea que la iluminación HDRI sólo produce
sombras suaves. Si en la mayoría de los casos lo hace así, es porque la mayoría de las sombras en el mundo
real tienen bordes suaves, y la HDRI tiene el propósito de recrear con exactitud las condiciones de iluminación
reales.

Ajustes de materiales

\-Asigne a los materiales Green, Red y Yellow1 un color gris claro en la ranura de reflexión. También puede
copiar el color pulsando con el derecho sobre el color y pegandolo en las ranuras de reflexión de otros
materiales. Mire la imagen de arriba.

<!-- p. 363 -->

\-Represente la escena. Sus resultados deberían ser parecidos a los mios.

Configuración del cristal:

<!-- p. 364 -->

Configuración del agua

<!-- p. 365 -->

Nota: usé el ruido predeterminado, porque creo que es el mejor para nuestra situación. Se puede animar la
cantidad de golpes para crear un efecto de ondulación en las animaciones.

Glossy Reflections

Cambie los ajustes de los materiales rojo, verde y amarillo. (Deje solo los colores difusos). Coloque Refl.
glossiness a 0.85.

Represente.

<!-- p. 366 -->

Cristal empañado

Ajustes para el cristal empañado, o esmerilado:

Bajé la refracción glossiness

<!-- p. 367 -->

Las he bajado a 0.95. He hecho esto de manera un poco intuitiva, pero al aumentar los glossieness hay que
bajar el spinner.
Observe el aumento del tiempo. Para las animaciones podría querer otra manera de conseguir este efecto.
Recuerde que todavía estamos en los ajustes básicos. Nuestro Mapa de Irradiación (el Mapa IR) es un sistema
para una rápida representación. La calidad más alta de IR y de la resolución de salida aumenta
considerablemente el tiempo del proceso. Dicho esto, yo he logrado representar animaciones con movimiento de
objetos que usan estos IR "bajos" sin notarse "parpadeo".

Displacement

Ningún paso a seguir aquí, solamente algunos ejemplos y ajustes.

El de arriba es un plano sin mapa de Desplazamiento de VRay.

El mismo plano, pero con desplazamiento (Arriba).

<!-- p. 368 -->

El mapa difuso... (Arriba)

...y el de desplazamiento.

Recuerde que las zonas blancas sobresalen más, y las negras menos. No se olvide de esto, si no quiere tener
resultados no deseados. Entreténgase un rato con Photoshop poniendo puntos blancos puros o negros en la
geometría de desplazamiento.

<!-- p. 369 -->

Crear un mapa de desplazamiento.

\1. Seleccione el objeto al que se quiere aplicar el Desplazamiento de VRay.

\2. Aplique el modificador Mesh Smooth al objeto y ponga las iteraciones a cero.

\3. Aplique un modificador de desplazamiento de VRay.

<!-- p. 370 -->

\-Ajuste como aparece en la imagen superior:

En parámetros comunes, resaltado en amarillo, hay un botón para agregar un bitmap para el desplazamiento. Así
es como añadí la imagen en blanco y negro de piedra que hemos visto arriba.
