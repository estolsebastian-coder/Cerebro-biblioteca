---
type: libro
title: "VRAY"
author: "federico"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 91
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/3D MAX Y VRAY/MANUALES/VRAY.pdf"
convertido: 2026-10-16
---

# VRAY

> Texto extraído de `AYUDAS DE PROGRAMAS\3D MAX Y VRAY\MANUALES\VRAY.pdf` (91 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Tut orial 3d m ax

p or Feder i co Gon z ál ez Bosqu e

RENDER and LIGHTNING

Cómo configurar la iluminación global en VRay

Para crear una iluminación global rápida únicamente hay que seguir una serie
de sencillos pasos:

1.- Creamos una escena simple (o compleja, como queramos). En este caso he
hecho un plano con una tetera encima.

2.- Aplicamos los materiales que queramos. Yo he puesto el material por
defecto para el suelo y uno de un gris más claro y de dos caras para la tetera.

<!-- p. 2 -->

3.- Entramos a las opciones de Render (F10) y en "Current Renderers"
seleccionamos el VRay como motor de render para "Production".

4.- Nos desplazamos por las nuevas opciones del motor de render hasta los
"Global Switches", donde desactivaremos la iluminación por defecto del MAX.

5.- Más abajo encontramos el "Image Sampler (Antialiasing)" y allí
seleccionamos el "Adaptive Subdivision" como método de suavizado de
bordes. Marcamos también la casilla "Rand", lo que añade un poco de ruido en
las zonas suavizadas.

<!-- p. 3 -->

6.- Seguimos bajando hasta llegar a la pestaña de "Indirect Illumination (GI)".
Allí dejaremos las opciones tal y como están puestas en esta imagen.

7.- Ya sólo nos falta activar la luz global, y esto lo hacemos en la pestaña
"Environment". Después de activarlo subimos el multiplicador a 1,5 y...

8.- ... tiramos el render. Ya está. Con esta configuración no logramos la mejor
calidad, pero sí un tiempo buenísimo de render y una calidad, en relación con
el tiempo, muy acertada (en mi P4 a 1,7Ghz. tardó 8 segundos)

<!-- p. 4 -->

Cómo crear cáusticas en VRay

Unas buenas curvas cáusticas pueden dar mucha vida a una escena, ya que
es un efecto óptico con el que convivimos en todo momento. Para crearlas en
VRay hay que hacer lo siguiente:

1.- Creamos una escena simple, como por ejemplo la que he creado para este
tutorial.

2.- A continuación aplicamos los materiales. El suelo tiene el material estándar

<!-- p. 5 -->

del MAX, mientras que los otros tres objetos tienen un material más complejo
que explicaremos a continuación.

3.- Analizando el material de la esfera de cristal rojo, vemos cómo está creado:

\1. El color "Ambient" y "Diffuse" están cambiados al color rojo levemente
oscuro que queremos para la esfera.
\2. La opacidad la dejamos al 30, ya que si la bajásemos a 0 perderíamos
las sombras.
\3. El brillo especular ciertamente no tiene mayor misterio.
\4. El mapa de reflexión lo creamos con un "Falloff", añadiendo en el color
blanco del mismo el nodo de material VRayMap, y seleccionando en
éste último la casilla "Reflect", que por defecto ya viene seleccionada.
\5. La refracción la conseguimos añadiendo en la casilla del mapa de
refracción otro material VRayMap, pero esta vez marcando en él la
casilla "Refract" y añadiendo como color de filtrado el color difuso
añadido anteriormente, pero más claro

<!-- p. 6 -->

Material de la esfera roja

<!-- p. 7 -->

Map #2 (Falloff)

Map #3 (VRayMap)

Map #1 (VRayMap)

NOTA: para poder mostrar correctamente los materiales que tengan mapas de
VRay, debemos previamente seleccionar el motor de render VRay tal y como
se indicó en el tutorial "Cómo configurar la iluminación global en VRay" y
después, en las opciones de los materiales seleccionar como motor de render
de la ventana de los materiales el VRay.

4.- Procedemos a crear una luz en la escena que ilumine desde un lateral para
acentuar mucho más el efecto de las curvas cáusticas.

<!-- p. 8 -->

5.- La configuración de la luz la realizaremos siguiendo los datos marcados en
la siguiente imagen.

<!-- p. 9 -->

6.- Según la versión que poseamos de VRay puede que la luz tenga por
defecto la cualidad de generar cáusticas, pero siempre conviene cerciorarse.
Para ello, desde el menú de render, bajamos hasta la pestaña "System" y allí
entramos en las propiedades de las luces de la escena pulsando sobre el botón
"Light settings...".

<!-- p. 10 -->

7.- Una vez aquí marcamos, si no lo está, la casilla "Generate caustics".

8.- El paso previo a tirar el render es activar en el VRay la opción de calcular
las cáusticas que se encuentra en la pestaña "Caustics", dentro de las
opciones de render. Además de activarla, deberemos cambiar los parámetros
que trae por defecto, ya que queda mejor con los utilizados aquí. Podríamos
utilizar los valores que vienen por defecto, pero casi con toda seguridad que no
veríamos nada, ya que el multiplicador viene por defecto en "1", y con una luz
normal se necesita de 15.000 a 50.000 para que se comiencen a percibir.

<!-- p. 11 -->

9.- Una vez tirado el render podremos ver una imagen similar a ésta. En mi
equipo tardó 1 minuto y 48 segundos.

Aplicar un mapa de desplazamiento en VRay

Muchas veces, para añadir detalle extra a nuestra malla, un mapa de "bump"
no es suficiente para conseguir el efecto deseado, sobre todo en los bordes de
la geometría o con relieves muy acusados. Para ello la mejor solución es
utilizar un mapa de desplazamiento creado por nosotros. El VRay nos
proporciona un acabado muy acertado en estas acciones y un tiempo de render
no demasiado elevado.

Para aplicar un mapa de desplazamiento a una malla haremos lo siguiente:

<!-- p. 12 -->

1.- Creamos un plano y le aplicamos un material estándar, tal y como vienen
los propios del MAX. A la hora de crearlo las coordenadas de mapeado deben
estar activadas.

2.- A continuación colocamos una luz que incida desde un lateral para acentuar
después más el efecto mediante las sombras.

<!-- p. 13 -->

3.- La luz la configuraremos según estos parámetros.

<!-- p. 14 -->

4.- Preparamos el VRay para que utilice la iluminación global con un
"Environment" bastante azulado y de intensidad 0,8 (si hay dudas en este paso,
consultad el tutorial "Cómo configurar la iluminación global en VRay") y tiramos
un render. El resultado será un plano como este.

<!-- p. 15 -->

5.- Seleccionamos el plano y añadimos el modificador
"VRayDisplacementMod".

6.- Para poder utilizar este modificador necesitamos una imagen que podamos
usar como desplazamiento. El desplazamiento, sea cual sea el programa,
siempre sigue las mismas directrices: negro abajo y blanco arriba (parece el
lema del KKK ;-) (es una regla nemotécnica, nada más). Para este caso he
creado una imagen con el Photoshop simulando un laberinto.

<!-- p. 16 -->

7.- Una vez creada la imagen, vamos al editor de materiales y creamos un
"bitmap" pinchando en el botón "Get Material", marcando "Bitmap" y
seleccionando la imagen (laberinto) que hemos creado.

"Get Material"

"Bitmap" creado y su nombre "Map #1"

8.- Con el "Bitmap" creado, ya sólo tenemos que configurar el modificador
"VRayDisplacementMod". Para ello seleccionamos el "2D mapping" ya que es
un plano lo que vamos a desplazar, añadimos el mapa de desplazamiento
"Map #1" correspondiente al "Bitmap" de nuestra imagen, subimos el "Amount"

<!-- p. 17 -->

a 30 (la cantidad de elevación del modificador), aumentamos la resolución y la
precisión de la malla, y marcamos la casilla "Tight Bound" para una mayor
optimización de la malla.

9.- Si ahora tiramos el render notaremos una "leve" diferencia con el render
anterior :-). Las imperfecciones de las paredes son debidas a que, como se
puede ver en el punto 6, las líneas que hice en el Photoshop para crear el
laberinto no son rectas y además el antialiasing que tenían era muy malo. De
haberlo hecho con líneas horizontales y verticales perfectas esto no habría
ocurrido.

<!-- p. 18 -->

Configuración de una escena exterior con VRay

¿Quien no ha tenido que hacer una escena exterior en algún momento?. Ya
sea en una animación, en una infografía relacionada con infoarquitectura... casi
siempre se nos plantea el tener que hacer un entorno lumínico exterior válido
que nos de una sensación lo más real posible. El 3D Studio MAX nos permite
llegar a ello fácilmente junto con el fantástico motor de render VRay. Para ello
seguiremos los siguientes pasos:

1.- Para este tutorial he creado 4 edificios simples y un plano con multiplicador
a 500. También he colocado unas aceras para dar más gracia a la imagen.

<!-- p. 19 -->

2.- Creamos una luz "Target Direct", ya que es el tipo de luz idóneo para
simular la luz del sol, al ser sus rayos paralelos unos a otros, y la colocamos
como en la imagen.

<!-- p. 20 -->

3.- La mejor forma de colocar una luz es "viendo a través de ella". Esto lo
podemos hacer (teniéndola seleccionada) con el atajo de teclado "Shift+4", o
pulsando el botón derecho sobre el nombre de la vista y seleccionando la luz
dentro de "Views" como se ve en la imagen siguiente.

<!-- p. 21 -->

4.- Una vez hecho esto pasaremos a ver lo siguiente, o algo parecido.

5.- Con los iconos de "Light Hotspot", "Light Falloff" y "Orbit Light", a parte del
"Truck Light" hecho con el botón central del ratón, nos moveremos hasta que

<!-- p. 22 -->

posicionemos la luz como nos interese. Una buena manera es tal y como
aparece en la imagen.

6.- Si ahora tiramos un render conseguimos algo como esto.

<!-- p. 23 -->

7.- Configuramos la luz de la siguiente manera. Es importante tener en cuenta
varias cosas, como que tenga sombra, que ésta sea del tipo "VRayShadow",
que el color de la luz sea levemente amarillenta y tener marcada la casilla
"Overshoot" para que ilumine fuera del cilindro. Eso sí, aunque ilumine fuera,
las sombras sólo las calcula dentro del cilindro. En la pestaña de los
parámetros de la sombra "VRayShadow" marcamos la casilla "Area shadow" y
cambiamos el tamaño a un valor adecuado. Como ese valor depende del
tamaño de la escena, habrá que tirar varios render hasta que nos quede tal y
como queremos.

<!-- p. 24 -->

8.- Entramos a las propiedades de render y en la pestaña de abajo, en "Assign
Renderer", seleccionamos el VRay como motor de render. Después, en sus
opciones, lo configuramos para que nos muestre un render rápido del resultado
final. De esta forma podremos cambiar varios parámetros y en poco tiempo ver
los resultados.

<!-- p. 25 -->



<!-- p. 26 -->

9.- Si ahora renderizamos la escena veremos algo similar a esto.

<!-- p. 27 -->

10.- La calidad deja mucho que desear, pero hemos conseguido el render en
pocos segundos, y en él sí que podemos apreciar suficientemente cómo va a
quedar la iluminación. También, para ver mejor cómo va a quedar el resultado
final podemos poner como fondo de la imagen el mismo color azulado que
hemos utilizado en el VRay para la iluminación global. Para ello entramos a las
opciones del "Environment" y arrastramos el color desde la ventana de
configuración de render a esta última.

<!-- p. 28 -->

11.- Después de esto, el render sería como el siguiente.

12.- La imagen ya sería creíble, pero siempre se puede mejorar. Si
conseguimos un cielo de 360º x 90º lograremos potenciar enormemente el
realismo de la imagen. Suele haber páginas por Internet que nos ofrecen
gratuitamente imágenes de este tipo. Además, es importante corregir la
perspectiva, ya que a no ser que nos asomemos desde la ventana de un 15º
piso no veríamos lo que vemos en la imagen previamente renderizada.

En la siguiente imagen he cambiado el cielo y la perspectiva. Se aprecia que
hay un cambio drástico, tanto a nivel de composición como de realismo. Según
sea la escena con la que trabajemos deberemos posicionar la cámara, y según
la sensación que queramos transmitir así será el bitmap que usaremos como
cielo de fondo.

<!-- p. 29 -->

Para la composición, sobre todo en trabajos de infoarquitectura, funciona muy
bien posicionar la cámara a 1,80m del suelo, ya que así se vería desde la
perspectiva de un transeunte.

13.- Ya sólo nos falta preparar los parámetros del VRay para renderizar la
imagen con una buena calidad, digna de cualquier presentación. Para ello sólo
tendremos que pones los valores como en la siguiente imagen.

<!-- p. 30 -->

14.- Tras unos minutos habremos renderizado una imagen de una calidad
similar a esta.

<!-- p. 31 -->

Cómo configurar la iluminación global en finalRender stage 1

Configurar una escena con iluminación global y buena calidad en finalRender
no es demasiado difícil, pero cierto es que tampoco es tan sencillo como en
otros motores de render. Para ello seguiremos los siguientes pasos:

1.- Creamos una escena (conviene que no sea demasiado compleja para que
se pueda hacer el tutorial en poco tiempo) y la aplicamos el material estándar
del MAX, aclarando levemente su color difuso.

<!-- p. 32 -->

2.- A continuación colocamos una luz cenital para que cree unas sombras
atractivas.

<!-- p. 33 -->

3.- La luz la configuraremos según estos parámetros.

4.- Nos vamos a la ventana de configuración del render y en la pestaña
"Current Renderers" seleccionamos el finalRender como motor de render para
producción.

<!-- p. 34 -->

5.- Cuando lo seleccionemos se nos desplegarán los nuevos menús del
finalRender. En la primera pestaña, "Global options", configuramos el antialiasing con los siguientes parámetros. Es importante recordar que la
configuración que estamos realizando es para tirar un render con bastante
calidad.

6.- Bajamos por las siguientes pestañas y nos paramos en "Global
Illumination", donde configuraremos los parámetros tal y como están en esta
imagen.

<!-- p. 35 -->

7.- Una vez configurados todos los parámetros ya podemos lanzar el render. El
resultado será algo similar a esto (al menos la iluminación ;-).

<!-- p. 36 -->

Análisis de la Integración de una figura 3D sobre otra imagen

Duración aproximada: 1-2 horas
Software: Softimage XSI 3.5, 3D Studio MAX 5.1 (motor de render VRay) y
Adobe Photoshop CS

Cuantas veces nos hemos quedado mirando una imagen en la que no
sabemos indicar qué objetos son 3D y cuales son reales, o cuantas veces nos
hemos preguntado cómo habrán conseguido el realismo de cierta escena. Pues
bien, esa magia es principalmente mérito de una buena integración de los
elementos 3D con la escena, pero no siempre se tiene claro el cómo
conseguirlo.

Para realizar cualquier integración hay unos pasos básicos que siempre hemos
de seguir:

<!-- p. 37 -->

\1. Modificar nuestro modelo 3D hasta llegar a la pose que deseemos que
tenga.
\2. Colocar al cámara con el ángulo y perspectiva lo más cercano posible al
fondo con el que lo vamos a componer.
\3. Configurar los posibles elementos matte si es que fuesen necesarios.
\4. Analizar la iluminación de la imagen sobre la que vamos a integrar
nuestro personaje e imitarla lo mejor posible en nuestro software 3D.
\5. Seleccionar nuestro motor de render, configurarlo y lanzar el render final.
\6. Hacer los retoques necesarios en Photoshop u otro programa de edición
de imagen.

En el caso de la integración de nuestro personaje en el fotograma de la película
Shrek de PDI/DreamWorks utilizamos Softimage XSI 3.5 para el modelado,
texturizado y setup del personaje, 3D Studio MAX 5.1 con Vray para su
iluminación y renderizado, y Photoshop CS para la limpieza del fondo y
posteriores retoques de la imagen, aunque resultados parecidos se pueden
conseguir con cualquier otro software profesional.

Los primeros pasos

Lo primero es pensar qué queremos hacer. Si es un trabajo que nos han
encargado este paso ya lo habrán hecho otros en nuestro lugar, así que no nos
tendremos que complicar demasiado.
En el caso concreto de la integración que vamos a hacer, la idea principal es
reemplazar a Shrek de la imagen original por nuestro personaje Papo . La
labor no es fácil ya que Papo es bastante delgado y Shrek todo lo contrario,
así que utilizando la herramienta de clonar de Photoshop nos ponemos manos
a la obra.

<!-- p. 38 -->

Un buen rato después conseguimos un resultado como éste. Ahora debemos
buscar una pose similar de nuestro personaje, si es que queremos copiar la
postura original.

<!-- p. 39 -->

Buscando la mejor pose

Para llegar a una pose similar a la de Shrek modificamos el setup que ya
teníamos realizado sobre nuestro personaje.

<!-- p. 40 -->

Nos ayuda bastante el disponer de una imagen que poner de fondo para copiar
la pose, es este caso la imagen original de Shrek y Asno .

<!-- p. 41 -->

Una vez lograda la pose pasamos la malla ya deformada a MAX para poder
utilizar el motor Vray.

Posicionando la cámara

Una vez importada la malla y creados los materiales que vamos a utilizar
pasamos a configurar la cámara. Éste es uno de los pasos que conviene
realizar de la mejor forma posible ya que en ello reside el 50% de la credibilidad
de la escena, sobre todo si se trata de un trabajo de infoarquitectura donde
llegar a la perspectiva perfecta es una obligación.
La mejor forma de hacer esto en MAX es trabajar con la perspectiva en lugar
de la cámara, ya que con ella tenemos muchísima más libertad, y después
convertir ésta en una cámara (seleccionando una cámara y desde la
perspectiva pulsando Ctrl+C)
Pondremos como fondo a la hora de trabajar (Viewport Backgroung) la imagen
original de Shrek y Asno , para, únicamente orbitando, desplazándonos y
haciendo zoom colocar a nuestro personaje exactamente en el ángulo e
inclinación que nos interese.

<!-- p. 42 -->

Iluminación

La principal complicación de esta composición es la simulación de la luz, ya
que al atravesar unos árboles llega produciendo unas sombras características.
Para posicionar el emisor de luz principal no hay más que fijarse un poco en la
imagen original y ver cómo incide la luz sobre los objetos, y en especial sobre
Asno y Shrek .
Una vez situada la luz buscamos una imagen que sirva para filtrar ésta a modo
de proyector y crear un plano a modo de suelo con un material Matte/Shadow
que reciba sombras. La iluminación global hará el resto.

<!-- p. 43 -->

Motor de render

Una vez posicionada la cámara y la luz, no tenemos ya más que tirar el render
final. Para ello debemos elegir el motor de render que más se ajuste a nuestras
necesidades, ya que cada uno suele funcionar mejor en un campo concreto.
En esta integración hemos utilizado el Vray, ya que con él se pueden conseguir
composiciones de gran calidad en muy poco tiempo y empleando iluminación
global
Un dato importante, ya que yo cometí el error a la hora de tirar el render, es
lanzarlo con la imagen de fondo en la que ya hemos quitado a Shrek y no con
la original (que acabamos de usar para situar la cámara), puesto que así
ahorramos el tiempo que, de no cambiarla, deberíamos invertir en arreglar
ciertas partes del antialiasing de los bordes de Papo.
Una vez renderizada la imagen la guardamos en TGA o TIFF incluyendo el
canal alfa puesto que nos ayudará después a la hora de recortar al personaje
para la composición en Photoshop.

Retoques finales en Photoshop

<!-- p. 44 -->

Una vez abiertas las imágenes ya sólo nos queda hacer unos pequeños
retoques con el Photoshop. Para ello lo ideal es tener en la capa background
la imagen de la que hemos eliminado a Shrek y encima la imagen renderizada
con el canal alfa aplicado como una máscara. De esta forma podemos trabajar
con ambos elementos por separado.

Los retoques que realizamos con Photoshop son un ajuste Hue/Saturation para
desaturar levemente a Papo y para modificar el tono verde y cambiarlo por
uno más amarillento, la adición de una capa de ajuste por curvas para realzar
el color general de la composición, y el añadido de un poco de hierba en la
zona de los pies para hacer más creíble el efecto.

<!-- p. 45 -->

...

Después de un tiempo he echado un vistazo a la imagen de Papo para
recordar esos maravillosos ratos que pasé con mis compañeros de TRAZOS y
¡Oh! ¡Sorpresa! La imagen no es tan maravillosa como la recordaba. ¿Qué
ocurre? Pues básicamente que he descubierto un error en el fondo. Como
podéis apreciar en la imagen anterior el fondo medio roca, medio tierra de
detrás de Papo es distinto por su parte derecha e izquierda, así que... manos a
la obra.

15 minutos después he arreglado el fondo, dando una apariencia más
profesional a la imagen.

<!-- p. 46 -->

Materiales Avanzados

¡Trabajo terminado! Pero ¿qué es lo que falla? Hemos trabajado el modelado
de nuestra escena, la iluminación pero hay algo que sigue diciendo que es
una imagen de síntesis. En muchos casos el problema es de unos materiales
creados demasiado deprisa, o sin habernos parado a pensar cómo deberían
ser. Siempre todo va demasiado rápido cuando queremos ver nuestro primer
render y pocas veces retrocedemos para hacer un buen ajuste del color, brillo
especular, etc.

En este tutorial crearemos varios materiales básicos muy utilizados en la
configuración de una escena Standard , enumerando y explicando paso a
paso cada parte del proceso. Estos materiales son plástico, madera, metal
cromado, cristal, pintura metalizada, agua, y terciopelo. Emplearemos
VRay a la hora de renderizar así como de configurar ciertos parámetros de los
materiales, pero esto no indica que no se pueda seguir este tutorial con los
parámetros propios de otros motores de render como finalRender, Brazil o
MentalRay.

<!-- p. 47 -->

Para que este tutorial se pueda entender, vamos a explicar brevemente unos
conceptos básicos en la creación de cualquier material:

Color: tono cromático propio de un objeto. Se puede usar un color único
o una imagen como mapa de colores.
Brillo especular: rebote de la luz sobre la superficie del objeto
proveniente del emisor lumínico. Cuando más rugosa sea la superficie
del mismo, más se refractará (esparcirá) la luz. Se puede controlar tanto
la intensidad, como el color o el nivel de refracción. Los más utilizados
son el Blinn (plásticos, madera y casi cualquier material), Anisotrópico
(CDs u otra superficie con microsurcos), Multi-Layer (combinación de
dos brillos especulares para conseguir un efecto más atractivo en
muchos casos ).
Opacidad: grado de transparencia de un objeto. Se puede delimitar con
un porcentaje o utilizando un mapa de opacidad, donde los tonos más
claros indicarían opacidad y los más oscuros transparencia.
Reflexión: propiedad de ciertos materiales de reflejar la luz (la imagen).
Se puede especificar el porcentaje de reflexión así como lo difuminado
que esté.
Refracción: cualidad de los materiales transparentes o translúcidos de
variar la trayectoria de los fotones (luz) que los atraviesan distorsionando
así lo que se ve a través de ellos. La cantidad de variación de la
trayectoria la da el Indice de Refracción (IOR en inglés).

Una vez explicados estos conceptos, y antes de comenzar con la parte bonita
de este tutorial, vamos a ver cómo hacer un efecto que emplearemos en casi
todos los materiales: la reflexión Fresnel . Es necesario exponerlo aquí para
tener después ya la base necesaria con la que poder seguir todos los pasos de
la creación de un material más o menos avanzado.

La reflexión Fresnel no es más que una reflexión que afecta más a las zonas
más paralelas a la orientación de la cámara desde la que vemos y menos a las
perpendiculares. Es idónea para plástico, lacados, porcelana, etc. Ya que da un
aspecto mucho más realista a los objetos.

Hacer esta reflexión es bastante sencillo:

\1. Desplegamos la pestaña MAPS del material con el que trabajamos y
hacemos clic en el botón NONE de Reflection . Escogemos como
reflejo el Falloff (atenuación).

<!-- p. 48 -->

\2. Seleccionamos como tipo de Falloff el Fresnel .

\3. Hacemos clic en el botón NONE del color blanco del Falloff y ahí
seleccionamos nuestro material raytrace, en el caso del VRay llamado
VRayMap . Si usasemos otro motor de render escogeríamos el
pertinente.

<!-- p. 49 -->

\4. El reflejo Fresnel ya estaría creado: Si deseásemos desenfocar el
reflejo únicamente deberíamos marcar la casilla Glossy dentro de las
opciones del VRayMap y cambiar el valor del Glossiness por el que
busquemos.

<!-- p. 50 -->

Una vez visto esto estamos preparados para comenzar con nuestros
materiales.

Plástico mate (Material Standard)

\1. Asignamos un color, ya sea sencillo (Diffuse) o un bitmap
(imagen). Éste será el color de nuestro objeto.

\2. Utilizamos un brillo especular de color blanco, de poca
intensidad (Specular Level = 20 - 30) y bastante difuso
(Glossiness = 10 - 20).

<!-- p. 51 -->

\3. Si se quiere rizar el rizo, podemos utilizar un reflejo Fresnel
muy desenfocado.

<!-- p. 52 -->

Plástico pulido (Material Standard)

\1. Asignamos un color, ya sea sencillo (Diffuse) o un bitmap
(imagen). Éste será el color de nuestro objeto, al igual que en
el plástico mate.

\2. Utilizamos un brillo especular de color blanco, de gran
intensidad (Specular Level = 200 - 500) y muy nítido
(Glossiness = 85 95).

\3. Aplicamos un reflejo Fresnel nítido.

<!-- p. 53 -->

Madera (Material Standard)

\1. Para el color utilizamos un bitmap (imagen) de madera o el
material procedural Wood del MAX. Se aconseja el bitmap
por el gran realismo que ofrece. Es interesante desaturar un
poco la imagen que tengamos ya que habitualmente los
bitmap de madera que podemos encontrar en cualquier
paquete de texturas tienen una saturación de color por encima
de lo habitual. También podemos conseguir esta desaturación
si utilizamos un color Diffuse gris neutro (128,128,128) y el
bitmap lo aplicamos no al 100% sino al 80 90%.

\2. Empleamos un brillo especular de color ambar o similar, no
blanco, de poca intensidad (Specular Level = 20 - 30) y muy
difuso (Glossiness = 10 - 20). También se puede mejorar con
un especular Multi-Layer , como en el ejemplo.

\3. Como lo más probable es que no dispongamos del bump
correspondiente, podemos emplear el mismo bitmap o
procedural que hayamos utilizado como tal. La intensidad del
mismo dependerá de la claridad y del contraste de la fuente,
así que iremos haciendo pruebas hasta que logremos un
relieve no demasiado exagerado pero apreciable.

\4. Si la madera está recién barnizada, o lacada, utilizaremos
un reflejo Fresnel nítido al 70 - 90 % de intensidad. Si el

<!-- p. 54 -->

barniz empleado es mate o el objeto ya tiene muchas horas de
uso usaremos el reflejo Fresnel desenfocado al 50 - 70 % de
intensidad.

<!-- p. 55 -->

Metal cromado (Material Standard)

\1. Para que el reflejo no aparezca demasiado claro utilizamos
un color Diffuse gris oscuro o negro.

\2. El brillo especular lo configuramos de color blanco, muy
nítido (Glossiness = 85 - 95) y de gran intensidad (Specular
Level = 200 - 500). También se puede mejorar con el
especular Multi-Layer , tal y como aparece en el ejemplo.

\3. Aplicamos reflexión normal (no Fresnel ) al 100%.

NOTA: la calidad del cromado depende enteramente del entorno
que rodee al objeto. Cuanto más rico sea (una imagen 360º, una
escena completa terminada, etc.) mejor quedará.

<!-- p. 56 -->



<!-- p. 57 -->

Cristal (Material VRayMtl)

Este material lo vamos a crear, no con el material Standard de
MAX sino con el material que nos trae el VRay: el VRayMtl. De

<!-- p. 58 -->

este modo podremos aprovechar su facilidad de uso y así
emplearla posteriormente.

\1. En la casilla del color Diffuse pinchamos y seleccionamos
un color muy oscuro, preferiblemente negro (para no aclarar
los reflejos).

\2. En el cuadro de Reflect cambiamos el negro existente por
blanco. En este material la cantidad de reflexión no se
especifica por un número sino por un color. Negro = no reflejo,
y Blanco = reflejo máximo. También activamos las reflexiones
Fresnel ( Fresnel reflections ), mucho más sencilla de hacer
que con los materiales Standard .

\3. La refracción funciona igual que la reflexión. Cambiamos el
color negro (no refracción) por blanco (refracción máxima).

MUY IMPORTANTE: para que lo que estemos creando sea cristal
y no otro material transparente deberemos ser fieles al Indice de
Refracción, que en el cristal es 1,52 más o menos. Si ponemos
otro la refracción cambiará y el resultado no será el correcto.

También podemos hacer variaciones del cristal como las
siguientes:

<!-- p. 59 -->

o Cristal tintado: se puede teñir el cristal del color que se quiera.
Tan sólo hay que hacer alguna prueba antes de tirar el render
definitivo ya que depende del grosor del objeto. Para ello
cambiamos el color blanco del Fog color (color de niebla) por el
que queramos y modificamos el Fog multiplier (multiplicador de
niebla) hasta lograr la cantidad de teñido.

o Cristal no liso (rugoso): este es otro efecto interesante, y podría
ser usado en mamparas de baño o similar. Únicamente
deberíamos trabajarnos el relieve que emplearíamos. Crearlo es
tan fácil como añadir un mapa específico al Bump (el ejemplo
está hecho con Noise ).

<!-- p. 60 -->

o Cristal al ácido: se podría considerar una variante del anterior,
con la salvedad de que el relieve que distorsiona lo que se ve a
través de él es muy pequeño. Para crear este efecto no hace falta
utilizar el Bump, ya que el material del VRay tiene una opción que
simula este efecto. Para utilizarlo, bajamos el valor del
Glossiness de 1 (brillante, sin defectos ni distorsión) a lo que
nos interese (0,8 en el ejemplo). La suavidad de este efecto la da
el valor de Subdivs (subdivisiones): cuando mayor sea, más
nítido y más tiempo de render).

<!-- p. 61 -->



<!-- p. 62 -->



<!-- p. 63 -->

Pintura metalizada (Material Standard)

\1. Como color Diffuse aplicamos un mapa Falloff en lugar
de un color plano, ya que parte del efecto de la pintura
metalizada lo da el que las partes más paralelas a la
orientación de la cámara sean más oscuras. Como primer
color usamos el que queramos que tenga nuestro objeto, y de
segundo el color negro, o el primero color pero mucho más
oscuro.

\2. Para enriquecer el brillo especular utilizamos el de tipo
Multi-Layer que no es más que dos brillos especulares
superpuestos. Como primero brillo especular empleamos uno
de color blanco, muy intenso (Specular Level = 300 - 500) y
muy nítido (Glossiness = 90 - 95). El especular secundario
será del color del objeto pero más claro, bastante difuso
(Glossiness = 15 - 30) y su intensidad estará regulada por un
mapa Celullar , Noise o cualquiera que configurado a un
tamaño muy pequeño de un aspecto de granulado. Así se
logrará la sensación de purpurina . Según el caso, nos podría
interesar que el color del especular secundario no fuese una
versión más clara del color Diffuse (por ejemplo muchas
pinturas azul metalizado tienen un especular secundario
morado).

\3. Aplicamos un reflejo Fresnel nítido, aunque en el caso de
la pintura metalizada también podemos usar un reflejo normal
al 20%.

<!-- p. 64 -->



<!-- p. 65 -->

Agua

Tenemos que pensar antes de nada qué agua necesitamos, si
agua transparente (si se va a ver qué hay debajo), o agua opaca
(si queremos que sólo refleje). Si necesitamos agua transparente,
utilizaremos un material VRayMtl debido a los posibles problemas
que nos podrían generar las sombras si lo hacemos con un
Standard .

o Agua transparente (Material VRayMtl)

\1. Con el fin de no clarar los reflejos Fresnel pondremos un
color Diffuse negro completamente.

\2. Cambiamos el color negro de la refleción ( Reflect ) a blanco
y activamos la casilla Fresnel reflection .

\3. También modificamos la casilla de color negro de la
refracción ( Refract ) y la ponemos de color blanco (refracción
total). El Indice de Refracción ( IOR ) lo ponemos a 1,33.

\4. El relieve lo conseguimos con un mapa Noise ya sea
Regular o Fractal según más nos interese.

NOTA: hay que activar la casilla Affect Shadows del material
VRayMtl para que procese bien el color.

<!-- p. 66 -->



<!-- p. 67 -->

(con cambio de tamaño del "Noise")

o Agua opaca (Material Standard)

<!-- p. 68 -->

\1. El color Diffuse deberá ser azul un poco desaturado (hacia
gris) y bastante oscuro (el del ejemplo es RGB: 28, 48, 58).

\2. Como brillo especular queda muy bien también el Multi-
Layer . De brillo especular primario usamos un color blanco,
de gran intensidad (Specular Level = 200 - 500) y muy nítido
(Glossiness = 85 95). El especular secundario sería de color
azul claro, poca intensidad (Specular Level = 20 - 35) y muy
difuso (Glossiness = 20 30).

\3. Utilizamos un reflejo Fresnel en la casilla Reflect .

<!-- p. 69 -->

MUY IMPORTANTE: al igual que con los cromados, la calidad del
agua depende en gran parte de aquello que refleje. Si nuestra
escena no aporta demasiado que reflejar, siempre podemos
utilizar la posibilidad de utilizar un reflejo de entorno distinto al del
render. Esto se consigue con la opción del VRay
"Reflection/refraction etc environment" - "Override MAX's".

Terciopelo (Material Standard)

\1. La clave de este material es su color, ya que no tiene ningún
brillo especular, reflejo o similar. El efecto adecuado lo
produce el material Falloff aplicado al color Diffuse . De los
dos colores que tiene, el superior (color de lo perpendicular a
la orientación de la cámara) será granate y el inferior (paralelo
a la orientación de la cámara) rosa no pastel.

\2. Aunque el efecto ya esté casi conseguido podemos
mejorarlo si añadimos un poco de Noise al relieve Bump .
Éste tiene que ser muy pequeño y fractal, para que quede
como una superficie muy levemente rugosa.

<!-- p. 70 -->



<!-- p. 71 -->

Selección de la tabla de Valores Reflectantes e Indices de Refracción de los
materiales de Jon Reynolds

Valores Indice de Refracción Material Material reflectantes (IOR)
Aluminio pulido 65 - 75 % Aire 1,0002926
Aluminio mate 55 - 75 % Alcohol 1,329
Acero 25 - 30 % Ambar 1,546
Acero inoxidable 80 - 90 % Aguamarina 1,577
Cobre muy pulido 60 - 70 % Diamante 2,417
Latón muy pulido 70 - 75 % Esmeralda 1,56
Roble claro pulido 25 - 35 % Cristal 1,51
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
Blanco lacado 80 - 85 % Circonita 1,800 1,960

<!-- p. 72 -->

Cómo crear un "PinScreen" o "Pantalla de alfileres"
(Ya sé que este script hace justo esto. De todas formas si queréis aprender cómo hacerlo sin el
script seguid este tutorial. Aprenderéis más)

Cuantas veces hemos entrado en una tienda de regalos y hemos visto esa
especie de "caja" vertical con una matriz de "clavos" que, al presionarlos con la
mano, crea por la otra cara la misma figura 3D de la mano con los clavos
desplazados. Este efecto se puede lograr de múltiples maneras, pero el que
más se acerca a la realidad es el de crear la matriz de clavos con un mapa de
desplazamiento.

Para lograr este efecto tendremos que trabajar un poco ya que necesitamos
crear la imagen que utilizaremos para el desplazamiento y modificarla con
Photoshop para que además simule los clavos.

1.- Buscamos el modelo 3D que queramos utilizar. Está bien que sean cosas
más o menos contundentes, ya que si el modelo posee partes finas no quedará
bien al perder gran parte del detalle. Siempre se puede probar con una mano,
un objeto sin mucho detalle, o como en este caso una cara.

Esta cara ha sido descargada de la zona de material gratuito en 3D Cafe (www.3dcafe.com)

2.- Creamos una cámara frontal a la cabeza de manera que ésta quede bien
encuadrada y ocupando casi todo el encuadre.

<!-- p. 73 -->

3.- Utilizando la herramienta de medición "Tape" medimos las distancias: 1, de
la cámara a la parte más cercana del objeto con respecto a la cámara (la punta
de la nariz); y 2, de la cámara a la parte más lejana del objeto con respecto a la
cámara (el supuesto nacimiento de las orejas).

<!-- p. 74 -->

4.- Con estas medidas nos vamos a la ventana de configuración del render y
entramos en la pestaña "Render Elements".

5.- Ahí añadimos (botón "Add...") como elemento de render el "Z Depth" para
que nos calcule la profundidad del objeto en el eje "Z" y lo configuramos con las
dos distancias calculadas anteriormente con la herramienta "Tape".

<!-- p. 75 -->

6.- Renderizamos y tendremos como resultado algo parecido a esto. La imagen
final que vamos a utilizar como desplazamiento la deberemos sacar a una
resolución grande (de 2000 x 2000 en este caso), para poder hacer después
bien el desplazamiento.

Sólo guardaremos la imagen "Z Depth" en formato TIF sin compresión, para
evitar pérdidas de calidad.

<!-- p. 76 -->

7.- Abrimos la imagen en Photoshop y la aplicamos el filtro "Mosaic..." que se
encuentra dentro del grupo "Pixelate".

<!-- p. 77 -->

8.- Aplicamos un tamaño de celdilla de 19 pixels (el tamaño de la celdilla
depende del tamaño de la matriz de clavos que queramos usar. Para este caso
concreto 19 está bien).

<!-- p. 78 -->

9.- Creamos un nuevo documento del tamaño de cada celdilla (19 x 19).

10.- Con la herramienta de selección circular creamos un círculo dejando
siempre un pixel de margen por cada lado y rellenamos la selección de color
negro.

<!-- p. 79 -->

11.- Seleccionamos la imagen completa y pinchamos en "Define Pattern...",
dentro del menú "Edit". De esta forma crearemos un nuevo patrón que después
repetiremos en la imagen "Z Depth" importada del MAX.

<!-- p. 80 -->

12.- Ponemos un nombre identificativo al patrón creado.

13.- Volvemos a la imagen "Z Depth" y creamos una nueva capa sobre el fondo
(background) original.

14.- Rellenamos la nueva capa con el patrón creado.

<!-- p. 81 -->



<!-- p. 82 -->

Conseguiremos algo como esto.

15.- Invertimos los colores de la nueva capa.

16.- El resultado será una imagen como ésta.

<!-- p. 83 -->

17.- Ahora, cambiaremos el modo de combinación de la capa nueva con el
fondo a "Multiply". Este modo hace que las zonas más claras se transparenten
y las zonas más oscuras permanezcan tal cual. Así lograremos ver por los
círculos blancos la imagen del fondo.

<!-- p. 84 -->

18.- Este ya podría ser un mapa de desplazamiento válido. El problema es que
la zona negra sería completamente plana en lugar de mostrarnos varios
"clavos" con un mínimo desplazamiento. Esto lo solucionamos aclarando los
tonos oscuros de la imagen del fondo mediante la modificación de las curvas
del Photoshop. Para lograr esto seleccionamos la capa del fondo (background)
y seleccionamos como nueva capa de ajuste las curvas ("Curves..."). Ahí
modificamos sólo la zona oscura para no estropear las partes más claras.

<!-- p. 85 -->

19.- El resultado sería el siguiente.

<!-- p. 86 -->

Guardamos la imagen como TIF o GIF (sin optimización ninguna y a 256
colores)

20.- De nuevo en el 3D Studio MAX, creamos un plano, marcamos la casilla
"Generate Mapping Coords." y le aplicamos un modificador
"VRayDisplacementMod" para aplicar el mapa de desplazamiento que
acabamos de crear.

<!-- p. 87 -->

21.- Vamos al editor de materiales y con la casilla de un material seleccionado
pinchamos sobre el icono "Get Material". Seleccionamos "Bitmap" y cuando
nos pregunte por la imagen que deseamos seleccionamos la imagen que
hemos creado en Photoshop.

22.- Arrastramos el nuevo material al "Texmap", dentro del "Common params"
del "RayDisplacementMod". Seleccionamos "Instance" para que si modificamos
posteriormente algún parámetro del material se aplique también en el mapa de
desplazamiento, y configuramos los parámetros del modificador como viene
abajo:

\* 2D mapping (landscape): mapeado apropiado para un plano, como es éste nuestro caso.
\* Amount: cantidad de desplazamiento. Cuando más tenga, más elevado será.
\* Resolution: resolución de la malla. En este caso debería ser alto para representar todos los

<!-- p. 88 -->

detalles de la imagen original.
\* Tigh bounds: suaviza los bordes para evitar posibles problemas.

NOTA: si este método da problemas se puede utilizar el "3D mapping", y añadir
en "Face subdivs" un número alto de subdivisiones como 512 o 1024.

<!-- p. 89 -->

23.- Seleccionamos el VRay como motor de render, "Adaptive subdivision"
como método de antialiasing en la pestaña "VRay:: Image sampler
(Antialiasing)" y si queremos algún efecto de iluminación global (ver Tutorial 1).

24.- Una vez seguidos todos los pasos, y tras un buen rato renderizando,
deberíamos lograr una imagen como ésta.

<!-- p. 90 -->

DI. federico gonzález bosque
federicogonzalezbosque@yahoo.com.ar
copy® 2005

<!-- p. 91 -->

This document was created with Win2PDF available at http://www.daneprairie.com.
The unregistered version of Win2PDF is for evaluation or non-commercial use only.
