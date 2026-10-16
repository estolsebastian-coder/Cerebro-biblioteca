---
type: libro
title: "3ds Max Design 2012 – para usuarios de AutoCAD"
author: "Fernando Montaño La Cruz"
categoria: "BIM Y HBIM"
paginas: 29
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/CURSOS MONTAÑO/TUTORIALES 1 (REVIT BÁSICO)/Leccion 08 Visualizacion 3d & Render/Leccion08.pdf"
convertido: 2026-10-16
---

# 3ds Max Design 2012 – para usuarios de AutoCAD

> Texto extraído de `BIM Y HBIM\01. Revit\CURSOS MONTAÑO\TUTORIALES 1 (REVIT BÁSICO)\Leccion 08 Visualizacion 3d & Render\Leccion08.pdf` (29 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



<!-- p. 2 -->

Revit - BIM Fernando Montaño

Lección 1

Lección 8:

Visualización 3D y Render

Contenido de esta lección:

 15 videos / duración: 2 hs. 6 min.

 descargar PDF lección 8

 descargar contenido para las prácticas.

En esta lección aprenderá a:

 Pintar superficies con materiales distintos.
 Dividir la superficie de los elementos.
 Añadir equipamiento al proyecto.
 Añadir cuadros y estampados.
 Añadir iluminación artificial.
 Crear terrenos de múltiples formas.
 Añadir cámaras.
 Crear renders interiores y exteriores; con luz natural y luz artificial.

Fernando Montaño La Cruz | fm@edu-cad.net 2

<!-- p. 3 -->

Revit - BIM Fernando Montaño

Introducción
El proceso de renderizado consiste en crear una imagen fotorrealista del modelo de construcción. Dicho proceso
puede darse de diversas formas, por ejemplo:

 Al designar el estilo visual Realista, que muestra materiales y texturas realistas en tiempo real.
 Al designar el estilo visual Trazado de rayos, damos inicio a un proceso de render que se dará en el visor de
pantalla y que podremos detener en el momento que el mismo alcance la calidad buscada.
 Render propiamente dicho.
 Renderizar en la nube de Autodesk 360º (sólo para clientes con subscripción).
 Exportar el modelo a otras aplicaciones más especializadas en render y animación, como ser 3ds Max o Lumion.
(Por su calidad y simpleza, se recomienda Lumion.)

Flujo de trabajo
Las etapas para crear render son las siguientes:

\1. Crear el modelo 3D
\2. Asignar materiales.
\3. Crear un entorno adecuado y decorado (terreno, equipamiento, personas, coches, vegetación,
estampados, etc.)
\4. Definir la iluminación del modelo de construcción.
\5. Definir las vistas interiores y exteriores.
\6. Definir la configuración del renderizado.
\7. Crear la imagen foto real.
Materiales

Asignar materiales
La designación del material a una categoría de elementos puede tener pequeñas variaciones; pero en todos los
casos lo hacemos desde la paleta de Propiedades y editando el Tipo. En algunos casos en material estará en el
primer cuadro que se abre (puertas y ventanas), en otros habrá que editar a la Estructura de los mismos (Muros,
Suelos, Barandas) y en otros habrá que editar los diferentes tipos de componentes de construcción (Escaleras).

Fernando Montaño La Cruz | fm@edu-cad.net 3

<!-- p. 4 -->

Revit - BIM Fernando Montaño

Material como Pintura

La herramienta Modificar>Geometría>Pintura (PT) permite pintar las superficies de componentes o familias,
sin afectar la estructura de los mismos. El procedimiento consiste en designar un material del proyecto en el
Explorador de materiales, y designar la superficie destino.

Añadir materiales al proyecto

En el Explorador de materiales (Gestionar>Configuración>Materiales ) es posible cargar materiales al
proyecto, desde las bibliotecas disponibles.

Fernando Montaño La Cruz | fm@edu-cad.net 4

<!-- p. 5 -->

Revit - BIM Fernando Montaño

Nota 1: Los Materiales como pintura se aplican sobre la superficie y NO sustituyen el material
existente. Su uso debe ser previsto desde la creación de componentes; por ejemplo, si mediante este
procedimiento aplicaremos el acabado final de los muros (pinturas de distintos colores, empapelado, etc.), esta
capa NO debe incluirse en la estructura del muro.

Nota 2: Los Materiales como pintura se retiran mediante la herramienta Modificar>Geometría>Eliminar Pintura

Video 1: duración 7:16 minutos

Dividir Caras

Mediante la herramienta Modificar>Geometría>Dividir cara (SF) es posible subdividir la superficie de una
cara en varias, con la forma que queramos otorgar. El procedimiento consiste en designar la cara y, mediante las
herramientas de dibujo, trazar la división que corresponda.

Esta herramienta es de suma utilidad para subdividir las áreas de revestimiento en baños y cocinas, a los efectos
de asignar el material que corresponda (mediante Pintar) a cada sector del muro.

Fernando Montaño La Cruz | fm@edu-cad.net 5

<!-- p. 6 -->

Revit - BIM Fernando Montaño

Idea: Para el cálculo de materiales, la propiedad Material: como pintura es una condición Si/No que nos
permite filtrar únicamente los materiales que cumplan con una de las 2 condiciones. Esto nos permite, por
ejemplo, hacer un cálculo rápido de todos los materiales de revestimiento.

Video 2: duración 15:24 minutos

Crear materiales
Como ya fue considerado en lecciones anteriores, los materiales de Revit son algo más complejos que lo
estrictamente relacionado al render. Los materiales también incluyen representaciones geométricas para planos
de planta, alzados, secciones, y distinguen su aspecto cuando se proyectan sobre una superficie o son
seccionados.

Los materiales se pueden crear de cero o a partir de otros existentes, esto está disponible al pie del Explorador
de materiales.

El nombre de los materiales es fundamental para realizar cálculos correctos y sencillos; por ejemplo, dos
hormigones de resistencias distintas, tendrán igual representación gráfica en planos y renders; pero es
importante distinguirlos por sus nombres en presupuestos. Esto conlleva a que podamos cargar al proyecto un
material de hormigón que se ajuste a nuestras necesidades, renombrarlo y asignarle el nombre “Hormigón 400”,
para los de 400 kg/cm². Ante la necesidad de un hormigón de 300 kg/cm² de resistencia, duplicamos el anterior y
le llamamos “Hormigón 300”. Su representación será la misma, pero serán materiales diferentes que se podrán
aplicar según corresponda y permitirán calcular su volumen exacto, de cada tipo de hormigón..

Crear un material cerámica
\1. Primero duplicar un material de similares características.
\2. Buscar un imagen del material que deseamos usar, casi seguro que una simple búsqueda en Google nos
permitirá encontrarla.

Fernando Montaño La Cruz | fm@edu-cad.net 6

<!-- p. 7 -->

Revit - BIM Fernando Montaño

\3. En la ficha Aspecto, remplazamos la imagen y las dimensiones de ella.

Fernando Montaño La Cruz | fm@edu-cad.net 7

<!-- p. 8 -->

Revit - BIM Fernando Montaño

Si el material es creado como Nuevo y no a partir de uno existente, remplazamos el aspecto por uno más acorde
al material que necesitamos.

Video 3: duración 11:16 minutos

Equipamiento

Equipamos el proyecto por medio de la herramienta Arquitectura>Construir>Componente y a continuación

cargamos la familia que corresponda Modificar|Colocar componente>Modo>Cargar familia , seguidamente
buscamos y seleccionamos la familia, en la carpeta que corresponda...

…por ejemplo Mobiliarios>Camas (en la biblioteca suministrada por Revit) o en cualquier carpeta en la que
hayamos copiado nuestras familias.

Fernando Montaño La Cruz | fm@edu-cad.net 8

<!-- p. 9 -->

Revit - BIM Fernando Montaño

Idea: Para girar los componentes o alinearlos a una dirección del proyecto, bastará con pulsar la barra
espaciadora, tantas veces como sea necesario.

Video 4: duración 4:49 minutos

An adir estampados

Los estampados son imágenes que se aplican sobre las superficies de muros y suelos (o cualquier otra), por

ejemplo cuadros o alfombras. La herramienta se encuentra en Insertar>Vincular>Estampado . En el cuadro

Tipo de estampado, creamos uno nuevo , le asignamos un nombre y después de hacer clic en , designamos
la imagen que deseamos usar.

Fernando Montaño La Cruz | fm@edu-cad.net 9

<!-- p. 10 -->

Revit - BIM Fernando Montaño

A continuación designamos la ubicación del estampado, sobre una superficie..

Video 5: duración 5:31 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 10

<!-- p. 11 -->

Revit - BIM Fernando Montaño
Iluminacio n

Revit nos ofrece múltiples elementos de iluminación, para insertar como cualquier Componente. Dichos
elementos se encuentran en la carpeta Iluminación…

Dependiendo del tipo de luminaria elegida, tendrá definido uno o varios anfitriones posibles (suelos, paredes,
techos…)

Las familias de luminarias suelen incluir tipos de diferentes potencias…

Entre las propiedades de la luminaria, es posible designar el tipo de lámpara, su intensidad y color.

Fernando Montaño La Cruz | fm@edu-cad.net 11

<!-- p. 12 -->

Revit - BIM Fernando Montaño

Video 6: duración 9:42 minutos

El terreno y su entorno

El proyecto no estará completo, si no se añade el terreno y quizás, su entorno. Son muchas las formas de
incorporar el terreno y de ellas, analizaremos 4:

\1. Dibujar el terreno manualmente.
\2. Importar un archivo con curvas de nivel en 2D y crear el terreno manualmente.
\3. Importar un archivo con curvas de nivel en 3D y crear el terreno automáticamente.
\4. Crear el terreno a partir de un archivo topográfico de puntos.

\1. Dibujar el terreno manualmente
Antes de crear el terreno es conveniente definir la parcela y todos los elementos de interés para definir los
niveles del mismo.

Después iremos a Masa y emplazamiento>Modelar emplazamiento>Superficie topográfica y utilizamos la

herramienta Colocar punto . Antes de marcar cada punto, debemos establecer su altura absoluta.

\2. Utilizar un archivo 2D
La opción anterior no ofrece mucha exactitud al m omento de establecer los niveles, por ello podemos basarnos
en una imagen con las curvas de nivel o en un archivo CAD, por ejemplo de AutoCAD. Primero que nada
debemos importar ese archivo.

Fernando Montaño La Cruz | fm@edu-cad.net 12

<!-- p. 13 -->

Revit - BIM Fernando Montaño

A continuación y mediante el primer procedimiento, creamos el terreno; pero esta vez con la guía de los
elementos del archivo externo.

Video 7: duración 8:31 minutos

Importar archivos con información 3D
Los contenidos creados en otras aplicaciones (por ejemplo AutoCAD) con elementos geométricos en 3D y que
permitan definir un terreno, pueden ser importados a Revit y después ser usados para definir el terreno.

\1. Importar el archivo desde Insertar>Vincular… o Insertar>Importar…

Fernando Montaño La Cruz | fm@edu-cad.net 13

<!-- p. 14 -->

Revit - BIM Fernando Montaño

\2. Crear una topografía, a partir del modelo importado; se realiza mediante Masa y emplazamiento>Modelar

emplazamiento>Superficie topográfica y a continuación Modificar|Editar

superficie>Herramientas>Crear desde importación> y designar el archivo importado o vinculado.

\3. Activar las capas cuya geometría se usará para crear el terreno.

Importar archivos con datos de puntos
Los archivos topográficos con relevamiento de los puntos de la superficie pueden ser usados para definir el
terrenos; dicha información debes estar en formato de texto .TXT (valores de coordenadas separados por
comas) o en formato .CSV. Después de seleccionar el archivo, se designa la unidad correspondiente de sus
coordenadas.

Video 8: duración 4:03 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 14

<!-- p. 15 -->

Revit - BIM Fernando Montaño
Acondicionamiento del Terreno

El primer paso para el acondicionamiento es su nivelación, para ello contamos con una herramienta que permite
crear Plataformas de construcción, ya sea planas o en pendiente.

Idea: Antes de definir cada plataforma, es conveniente planificar su ubicación, dibujando los elementos
geométricos.

Video 9: duración 11:00 minutos

Equipamiento del terreno
El terreno se puede equipar con familias de componentes que se pueden insertar desde Masa y

emplazamiento>Modelar emplazamiento>Componente de emplazamiento o al igual que el equipamiento

interior, mediante Arquitectura>Construir>Componente . Encontraremos familias en las carpetas
Emplazamiento, Entorno, Equipos especializados y Vegetación.

Familias de objetos RPC
En dichas carpetas encontraremos familias de objetos RPC de la empresa Archvision, por ejemplo personas y
árboles.

Estas familias incluyen múltiples tipos, que podremos designar, después de insertarlos.

Fernando Montaño La Cruz | fm@edu-cad.net 15

<!-- p. 16 -->

Revit - BIM Fernando Montaño

Video 10: duración 7:34 minutos

Vistas en Perspectiva real

Para visualizar la escena desde perspectiva real, debemos añadir una cámara; de preferencia, en una vista
superior. Dicha herramienta se encuentra junto a la de visualizar en 3D, en la barra de herramientas de acceso
rápido. Los pasos consisten en dar la ubicación de la cámara y el punto de mira, previamente es posible designar
un nivel y el desfase de los elementos, respecto del mismo.

Automáticamente cambiaremos a la nueva vista. Desde la paleta de propiedades se ajustarán algunos
parámetros de la vista, como ser el alcance de la misma (es posible definir una distancia y ocultar todo más allá
de ella), la configuración de render y las alturas de la cámara/ojo y el objetivo/destino.

Fernando Montaño La Cruz | fm@edu-cad.net 16

<!-- p. 17 -->

Revit - BIM Fernando Montaño

Para ajustar la cámara manualmente y desde otra vista, lo primero será verla; para ello hay que posicionarse en
la vista en la que se realizará el cambio (por ejemplo una vista superior), después hacer clic derecho en la vista
correspondiente a la cámara que deseamos visualizar y designar la opción Mostrar cámara.

Idea: Para visualizar las cámaras en otras vistas, bastará con seleccionar el marco correspondiente a vista
de la cámara.

Fernando Montaño La Cruz | fm@edu-cad.net 17

<!-- p. 18 -->

Revit - BIM Fernando Montaño

Con la cámara ya visible, es posible ajustar tanto el ojo como, como el destino.

Otra herramienta de suma utilidad para ajustes de cámara, es la Rueda de navegación, que nos permitirá las
siguientes funcionalidades.

 Orbita: Mantiene fijo el objetivo y gira la cámara a su alrededor, manteniendo fija la distancia.
 Centrar: Desplaza el Pivote u objetivo hasta una nueva ubicación (es necesario arrastrar el ratón).
 Zoom: Acerca y aleja la cámara del objetivo, nos permite entrar y salir de los ambientes.
 Mirar: Mantiene fijo el punto de ubicación de la cámara y gira el objetivo en todas direcciones.
 Encuadre: Desplaza simultáneamente la cámara y el objetivo, en cualquier dirección.
 Arriba abajo: Desplaza simultáneamente la cámara y el objetivo, en dirección vertical.

Ángulo de visual
La apertura del lente o ángulo de visual del ojo, se ajusta a través de la ventana correspondiente a la vista.

Video 11: duración 9:55 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 18

<!-- p. 19 -->

Revit - BIM Fernando Montaño
Render

Mediante el este procedimiento se obtiene una imagen fotorrialista, a partir del modelo 3D; en ella se reflejarán
los materiales y la iluminación creada.

Tamaño de imagen
La imagen que crearemos debe tener un tamaño asignado, para ello seleccionamos el marco de la vista,

hacemos clic en Tamaño de recorte y establecemos las dimensiones.

Iluminación del sol y cielo
Las sombras en el visor, nos ayudarán a definir la imagen que deseamos.

Desde el botón de sol, es posible configurar sus propiedades.

Fernando Montaño La Cruz | fm@edu-cad.net 19

<!-- p. 20 -->

Revit - BIM Fernando Montaño

Se puede establecer una ubicación en la tierra y la posición del sol para un día y una hora en particular.

Configuración de render
Para renderizar en la PC usamos la herramienta Vista>Gráficos>Renderizar (RR)

Se puede escoger entre varias configuraciones predeterminadas, cuya calidad ascendente (Borrador, Media, Alta
y Optima) coincidirá con tiempos de renderizado también ascendentes.

La duración de renderizado se puede establecer según 3 variables:

 Renderizar por nivel (1 a 40): A mayor nivel, mayor calidad y más demora. (Controlamos el tiempo en
función de más o menos calidad.)
 Renderizar por hora: Se establece el tiempo que destinaremos para el render. Por ejemplo, si el
almuerzo nos insume 45 minutos, podemos determinar este tiempo para que realice el mejor render
posible. (Controlamos el tiempo exacto, pero no la calidad que se obtiene.)
 Hasta que sea satisfactoria: Se establece una calidad mínima, sin importar el tiempo que demande
llegar a ella. (Exigimos calidad, pero sin importar el tiempo.)

Fernando Montaño La Cruz | fm@edu-cad.net 20

<!-- p. 21 -->

Revit - BIM Fernando Montaño

Resolución
El tiempo será proporcional al tamaño de la imagen y los píxeles que ella tenga. La densidad de puntos puede ser
de 75, 150, 300 o 600 por pulgada, lo que equivale a 30, 60, 120 y 240 puntos por centímetro.

Iluminación y fondo
La iluminación de la escena debe asignarse según se trate de una escena exterior o interior, y puede ser
aportada por el sol y/o las luces artificiales. De fondo de escena podemos elegir entre varios escenarios
predeterminados y que varían en la nubosidad, al igual que podemos escoger una imagen cualquiera.

Render
Ajustados los parámetros, damos inicio al proceso, haciendo clic en el botón Renderizar.

Después de obtener el Render es posible hacer algunos ajustes de exposición, para mejorar su calidad. Los
cambios se visualizan en tiempo real, como estando en un editor de imágenes.

Fernando Montaño La Cruz | fm@edu-cad.net 21

<!-- p. 22 -->

Revit - BIM Fernando Montaño

Una vez que disponemos de la imagen buscada, podemos exportarla a un archivo independiente (BMP, JPG, PNG
y TIF) o guardarla en el proyecto, para ser incluida en una lámina.

Video 12/13: duración 12:38 / 8:08 minutos

Renderizar en la nube de Autodesk 360
El procedimiento es simple y tiene como ventaja, que no insumimos tiempo para realizar los renders.

\1. Ejecutamos Vista>Gráficos>Renderizar en cloud .
\2. Si aún no lo hicimos, deberemos iniciar sesión como usuarios de Autodesk, para ello ingresamos el
usuario/mail y la contraseña.

Fernando Montaño La Cruz | fm@edu-cad.net 22

<!-- p. 23 -->

Revit - BIM Fernando Montaño

\3. Autodesk mostrará los 3 pasos del procedimiento.

\4. Designamos los parámetros de configuración del render e iniciamos la renderización. Autodesk nos
informará los minutos que tardará en estar lista la imagen.

Nota: es posible renderizar varias vistas de forma simultánea.

Las imágenes renderizadas se almacenan en nuestra galería de imágenes de la nube, accedemos a ella mediante

Vista>Gráficos>Renderizar en cloud .

Video 14: duración 5:27 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 23

<!-- p. 24 -->

Revit - BIM Fernando Montaño

Renders interiores
En escenas interiores es más frecuente el uso de las distintas configuraciones de luces:

Solo sol

Sol + Artificiales

Solo artificiales

Video 15: duración 4:51 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 24

<!-- p. 25 -->

Revit - BIM Fernando Montaño
Pra cticas recomendadas: renderizacio n

NOTA: Los textos que están a continuación, son extraídos del help de Revit y son un complemento, para quienes
desees profundizar en la técnica de renderizado.

Cuando se utiliza la herramienta de renderización, el motor de renderización utiliza algoritmos complejos para
producir una imagen fotorrealista de una vista 3D de un modelo de construcción.

La cantidad de tiempo necesaria para generar la imagen renderizada varía en función de múltiples factores,
como la cantidad de elementos de modelo y luces artificiales, la complejidad de los materiales y el tamaño o
resolución de la imagen. Además, la interacción de otros factores puede afectar al rendimiento de renderización.
Por ejemplo, los reflejos, refracciones y sombras suaves pueden aumentar el tiempo de renderización.

En última instancia, el rendimiento de renderización es un equilibrio entre la calidad de la imagen resultante y
los recursos (tiempo, recursos informáticos) dedicados a la operación. Las imágenes de baja calidad suelen
generarse rápidamente, mientras que las de alta calidad requieren mucho más tiempo.

Antes de renderizar una imagen, piense si necesita una imagen de gran calidad o una imagen con calidad de
diseño. Por lo general, empiece por renderizar una imagen con calidad de diseño para ver los resultados de la
configuración inicial. Luego podrá ajustar materiales, luces y otros efectos para mejorar la imagen. A medida que
se acerca al resultado deseado, puede utilizar la configuración de calidad media o baja para generar imágenes
más realistas. Utilice la configuración de alta calidad para generar una imagen final cuando esté seguro de que
los aspectos de renderización del material y la configuración de renderización producirán el resultado deseado.

En los temas siguientes se describen algunas características y configuraciones que afectan al rendimiento de
renderización.

Prácticas recomendadas: proceso de renderización
Nota: Estas prácticas recomendadas son específicas para el motor de renderización NVIDIA mental ray. No son
aplicables para Autodesk Raytracer.

En el Administrador de tareas de Windows, el proceso de la herramienta de renderización de Revit se denomina
fbxooprender.exe. Al renderizar una imagen, el proceso puede usar hasta cuatro procesadores. Si hay otros
procesos en ejecución, el de renderización libera parte de la capacidad disponible para asignarla a esos procesos.

Antes de renderizar una imagen, apague los protectores de pantalla que estén activos y cierre procesos no
esenciales para que no consuman recursos de procesamiento. Por ejemplo, algunas páginas Web que usan
gráficos Flash pueden ralentizar el proceso de renderización. Al cerrarlas habrá más capacidad de CPU disponible
para la renderización y puede que se agilice el proceso.

El Administrador de tareas de Windows puede resultar útil para supervisar la renderización de una imagen. Si
fbxooprender.exe no utiliza alrededor del 99% de la capacidad de procesamiento, puede que haya procesos
activos que interfieren en la renderización. Cierre tareas no esenciales para poner más capacidad de
procesamiento a disposición de la renderización.

Fernando Montaño La Cruz | fm@edu-cad.net 25

<!-- p. 26 -->

Revit - BIM Fernando Montaño

Prácticas recomendadas: rendimiento de renderización y modelo de construcción
Cuando se utiliza la herramienta de renderización de Revit, una de las formas más eficaces de reducir la
cantidad de tiempo necesaria para renderizar una imagen, es reducir la cantidad de elementos de modelo que
debe tener en cuenta el motor de renderización. Use una o más de las estrategias siguientes.

Oculte elementos de modelo innecesarios
Por ejemplo, si una imagen renderizada no va a mostrar mobiliario existente en la parte más lejana de un muro
interior, oculte el mobiliario en la vista antes de renderizar. Al hacerlo, reduce el número de elementos que el
motor debe tener en cuenta durante el proceso de renderización. Consulte Acerca de ocultar elementos en
una vista.

Cambie el nivel de detalle
Cambie el nivel de detalle de la vista de bajo a medio. Al reducir la cantidad de detalla en la vista 3D, reduce la
cantidad de objetos que se renderizan, reduciendo de este modo el tiempo de renderización.
Consulte Especificación del nivel de detalle para una vista.

Reduzca el área de vista que desea renderizar
Modelice solo la parte de la vista 3D que necesita mostrar en la imagen, omitiendo las áreas innecesarias. Para
ello, utilice una caja de sección, una región de recorte, el plano de recorte de cámara o una región de
renderización. Consulte Definir el área de vista para la renderización.

Prácticas recomendadas: rendimiento e iluminación de renderización
Para la herramienta de renderización de Revit, el proceso de renderización implica la simulación de
interacciones de luz con materiales. Como resultado, el rendimiento de renderización se ve notablemente
afectado por los cálculos de iluminación. Al prepararse para renderizar una imagen, tenga en cuenta lo siguiente.

Cantidad de luces
El tiempo de renderización es directamente proporcional a la cantidad de luces de la escena. Por lo general,
cuantas más luces se utilicen, más tiempo necesitará el motor de renderización para procesarlas. Puede ser
conveniente apagar luces que se necesiten en la imagen renderizada. Consulte Controlar las luces.

Normalmente, una vista interior tarda más en renderizarse que una exterior. Una vista exterior sin luz natural (es
decir, nocturna) que muestra muchas luces interiores encendidas tarda mucho tiempo en renderizarse.

Forma de origen de luz
Las luces más precisas requieren más tiempo de renderización. El parámetro Forma de emisión de un origen de
luz puede afectar al tiempo de renderización. Por ejemplo, los puntos de luz se renderizan más rápido que otras
formas. Las luces lineales son más lentas. Las luces circulares y rectangulares son las más lentas de renderizar.
Consulte Definir la geometría de un origen de luz.

Sombras suaves
Revit utiliza orígenes de luz de áreas para producir resultados más realistas. Sin embargo, las sombras de área
son costosas de calcular. Si incrementa la calidad de las sombras suaves, aumenta el tiempo de renderización.
(En el cuadro de diálogo Parámetros de calidad de renderización, utilice la opción Sombras suaves).
Consulte Referencia para la configuración de la calidad de renderización avanzada.

Iluminación indirecta
La iluminación indirecta simula la interacción de luces con el entorno al rebotar luz desde las superficies, incluso
con las que no están expuestas directamente a un origen de luz. Si aumenta la precisión de iluminación indirecta

Fernando Montaño La Cruz | fm@edu-cad.net 26

<!-- p. 27 -->

Revit - BIM Fernando Montaño

y la cantidad de rebotes, podrá mejorar los efectos más pequeños y sutiles de iluminación, así como la cantidad
de luz de una escena. Sin embargo, al incrementar la cantidad de iluminación indirecta, el tiempo necesario para
renderizar la imagen también aumenta. (En el cuadro de diálogo Parámetros de calidad de renderización, utilice
las opciones de iluminación indirecta). Consulte Referencia para la configuración de la calidad de
renderización avanzada.

Cajas de sección y grupos de luces
Al utilizar cajas de sección para limitar la geometría que se renderiza, puede reducir notablemente la cantidad de
tiempo necesaria para renderizar una imagen. (Consulte Definición el área de vista para la renderización).
También puede usar grupos de luces para desactivar luminarias, reduciendo así la cantidad de luces que
afectarán a la imagen renderizada. Consulte Acerca de los grupos de luces. No obstante, recuerde que las
luces que no se encuentran en la vista aún pueden afectar significativamente a la calidad de la imagen
renderizada). Las cajas de sección excluyen luces delimitadas. Si se planea concienzudamente, el uso combinado
de cajas de sección y grupos de luces puede reducir sensiblemente la cantidad de tiempo necesaria para
renderizar una imagen.

Prácticas recomendadas: rendimiento y materiales de renderización
Los materiales simulan diversos efectos, como los reflejos y texturas. Especifique el aspecto de renderización de
cada material mediante el cuadro de diálogo Materiales.

Cuando el motor de renderización renderiza materiales, el rendimiento depende de los efectos que se simulan.
De hecho, los aspectos de renderización complicados de materiales pueden ralentizar el proceso de
renderización más que la compleja geometría del modelo de construcción.

Cuando se prepare para renderizar una imagen utilizando la herramienta de renderización de Revit, tenga en
cuenta lo siguiente.

Cómo afectan los colores y patrones al rendimiento de renderización
La complejidad y el tamaño de un color o patrón afecta a la velocidad de renderización. Los patrones más
complejos requieren que el motor de renderización calcule más muestras, para que pueda captar los detalles. El
motor de renderización funciona mejor cuando puede identificar áreas de tratamiento de superficie similar y
estimar aspectos en grandes áreas homogéneas.

Por ejemplo, una superficie monocromática lisa se renderiza más rápidamente que una superficie con patrón
lisa. Un patrón de gran escala se renderiza con mayor rapidez que un denso patrón complejo. Una superficie
perforada detallada se renderiza más lentamente que superficie sencilla.

Los aspectos de renderización de material que precisan más tiempo para renderizarse son (de menor a mayor
lentitud): pintura metálica, metal moteado, metal forjado, agua, cristal esmerilado y metal perforado. Los
tiempo de renderización más lentos de esos materiales son proporcionales a la cantidad de la escena que
cubren.

Con configuraciones de calidad entre borrador y media, los materiales complejos muestran muchos defectos
(pequeñas imprecisiones e imperfecciones en la imagen renderizada). Los materiales no perfectamente
reflectantes (como los suelos de madera o los montantes de metal) aparecen moteados. Es posible mejorar
estos problemas ajustando el valor Precisión de reflejos borrosos.

Para mejorar el aspecto de siluetas y superficies con patrones sin aumentar considerablemente el tiempo de
renderización, ajuste el valor Precisión de imagen (anti-aliasing). Para producir imágenes con poca profundidad

Fernando Montaño La Cruz | fm@edu-cad.net 27

<!-- p. 28 -->

Revit - BIM Fernando Montaño

de iluminación pero con geometría rígida, utilice el parámetro de calidad de diseño con un alto valor de Precisión
de imagen (anti-aliasing).

Cómo afectan los tipos de reflejo al rendimiento de renderización
El aspecto de renderización de un material especifica su reflectividad. Revit puede renderizar rápidamente
reflejos mate. Pero cualquier característica de material que cause distorsiones visuales (como transparencias o
reflejos borrosos) requiere más trabajo para renderizarse y, por lo tanto, más tiempo de renderización.

Los reflejos brillantes son ligeramente más difíciles de renderizar que los mate. Una superficie vítrea es más
difícil de renderizar que una lisa y brillante. El agua es más difícil de renderizar que el cristal. El metal con una
pátina o una superficie forjada es más difícil de renderizar que el pulido.

Los reflejos borrosos son más difíciles de calcular. Sin embargo, no es posible controlar la calidad de los reflejos
borrosos para reducir el efecto del rendimiento de renderización. (Use las opciones de reflejos y transparencia).

Cómo afectan las refracciones y reflejos al rendimiento de renderización
Los materiales refractivos, como el cristal, también suelen proyectar reflejos. Por lo tanto, estos materiales son
más costosos (en tiempo y recursos) de renderizar que otros. Además, el panel medio de cristal tiene dos capas
o lados, que requieren varias capas de refracción. Al renderizar una imagen, todas las capas deben calcularse de
manera que pueda ver a través del cristal. Por ejemplo, se necesitan al menos seis refracciones para ver a través
de tres paneles de cristal sólido.

Al renderizar una imagen, puede especificar el número de rebotes desde superficies reflectantes (Número
máximo de reflejos) y el número de paneles de cristal para refracciones (Número máximo de refracciones). Los
parámetros más altos suelen producir tiempos de renderización más largos. Las refracciones borrosas
incrementan el tiempo de renderización. (En el cuadro de diálogo Parámetros de calidad de renderización, use
las opciones de reflejos y transparencia).

Prácticas recomendadas: rendimiento de renderización y Calidad/tamaño de
imagen
Cuando se utiliza la herramienta de renderización de Revit, el tamaño o la resolución de una imagen
renderizada tiene un efecto predecible en el tiempo de renderización. El parámetro Precisión de imagen (antialiasing) afecta al tiempo de renderización del mismo modo. Los valores más altos de estos parámetros
requieren más tiempo para generar la imagen renderizada.

Efecto del incremento de resolución de imagen
Si duplica el valor de resolución de la imagen (por ejemplo, de 75 dpi a 150 dpi) sin cambiar otros parámetros, el
tiempo de renderización puede ser entre dos y cuatro veces superior al normal. Dependiendo de la complejidad
de la imagen renderizada, la duración del proceso puede ser de entre 1,9 y 3,9 veces superior; el incremento de
tiempo promedio es 2,7 veces más que la imagen de 75 dpi original.

Si vuelve a duplicar el valor de resolución (es decir, de 75 dpi a 150 dpi y luego a 300 dpi) cada incremento de
resolución incrementa la duración del proceso 2,7 veces. Así pues, si incrementa la resolución de 75 dpi a 300
dpi, el tiempo de renderización se incrementará 2,7 x 2,7 veces, o aproximadamente 7,3 veces el tiempo de
renderización a 75 dpi original. Si incrementa la resolución de 75 dpi a 600 dpi, el tiempo de renderización se
incrementará 2,7 x 2,7 x 2,7 veces, o aproximadamente 19,7 veces el tiempo de renderización a 75 dpi original.

Fernando Montaño La Cruz | fm@edu-cad.net 28

<!-- p. 29 -->

Revit - BIM Fernando Montaño

Comprobación del tamaño de imagen
Al definir el área que va a renderizar, compruebe que el tamaño de la imagen es adecuado y razonable. Si
especifica un tamaño de imagen muy grande, es posible que la velocidad de renderización sea muy lenta.

Región de recorte: Al usar una región de recorte para definir el área de vista para renderizar, puede
especificar la altura y anchura de dicha región. El tamaño de la región de recorte define el tamaño del papel de la
imagen renderizada.

Región de renderización: Al usar una región de renderización para definir el área de vista que va a
renderizar en una vista ortográfica, puede arrastrar el límite de dicha región. La altura y anchura resultantes se
muestran en el cuadro de diálogo Renderización, en Salida.

Fernando Montaño La Cruz | fm@edu-cad.net 29
