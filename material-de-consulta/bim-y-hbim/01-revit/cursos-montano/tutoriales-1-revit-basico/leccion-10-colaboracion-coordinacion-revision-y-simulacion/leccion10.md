---
type: libro
title: "3ds Max Design 2012 – para usuarios de AutoCAD"
author: "Fernando Montaño La Cruz"
categoria: "BIM Y HBIM"
paginas: 19
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/CURSOS MONTAÑO/TUTORIALES 1 (REVIT BÁSICO)/Lección 10 Colaboración, coordinación, revisión y simulación BIM/Leccion10.pdf"
convertido: 2026-10-16
---

# 3ds Max Design 2012 – para usuarios de AutoCAD

> Texto extraído de `BIM Y HBIM\01. Revit\CURSOS MONTAÑO\TUTORIALES 1 (REVIT BÁSICO)\Lección 10 Colaboración, coordinación, revisión y simulación BIM\Leccion10.pdf` (19 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



<!-- p. 2 -->

Revit - BIM Fernando Montaño

Lección 1

Lección 10:

Colaboración, coordinación, revisión y
simulación BIM

Contenido de esta lección:

13 videos / duración: 2 hs. 12 min.

En esta lección aprenderá a:

 Trabajar en equipo mediante sub-proyectos de Revit.
 Revisar interferencias y colisiones en Revit.
 Definir las etapas del Proyecto, mediante parámetro.
 Asignar las atapas a los componentes del proyecto.
 Coordinar las etapas y definir tiempos en Excel.
 Coordinar un proyecto en Navisworks.
 Crear una animación 4D.
 Crear un proyecto en AutoCAD, para su integración BIM.
 Definir y coordinar las etapas del sub-proyecto de AutoCAD.
 Gestionar el proyecto completo en Navisworks.
 Integración con Navisworks Freedom.

Fernando Montaño La Cruz | fm@edu-cad.net 2

<!-- p. 3 -->

Revit - BIM Fernando Montaño

Trabajo en equipo y coordinacio n de proyectos

Revit ofrece una forma ordenada de trabajar en equipo, para que varios colaboradores interactúen en el mismo
proyecto y de forma simultánea. La misma consiste en crear un archivo central en el que concentrará toda la
información del proyecto y archivos locales para uso de cada colaborador del proyecto.

El primer paso consistirá en crear el archivo central, puede ser a partir de un proyecto ya iniciado (por ejemplo
en anteproyecto desarrollado por el arquitecto) o puede ser a partir de un archivo vacío o casi vacío. (En nuestro
caso partiremos de la vivienda creada en las primeras lecciones).

Guardar como archivo central en una ubicación de red
Lo primero es habilitar la colaboración, para que los integrantes del equipo puedan acceder simultáneamente, al

mismo modelo; para ello activamos el botón Colaborar>Gestionar colaboración>Colaborar

Guardamos el proyecto en una ubicación a la que puedan acceder todos los colaboradores y le asignamos un
nombre. Seguidamente aparecerá un cuadro en el que designaremos si deseamos colaborar a través de nuestra
red o de Autodesk 360 (servicio de pago para Revit).

Fernando Montaño La Cruz | fm@edu-cad.net 3

<!-- p. 4 -->

Revit - BIM Fernando Montaño

Se habilitará el botón Subproyectos , lo seleccionamos y cambiamos el nombre al proyecto, para asignar
uno más acorde.

Aceptamos y cerramos el archivo. Al cerrar Revit notificará que este será el modelo central.

Todos los colaboradores que deseen trabajar en el proyecto, deberán usar el comando Abrir y localizarlo en la
red de uso común a todos.

Fernando Montaño La Cruz | fm@edu-cad.net 4

<!-- p. 5 -->

Revit - BIM Fernando Montaño

Cada colaborador deberá abrir el archivo o modelo central, pero aceptando el ofrecimiento predeterminado de
Crear un nuevo archivo local, o sea en la estación de trabajo del usuario. Esto implica que si son 4 los
colaboradores, existirá un archivo central y 4 archivos locales.

Cada usuario podrá determinar sub proyectos y toda intervención estará vinculada a uno de dichos subproyectos.

El colaborador dispondrá de 2 herramientas para actualizar el proyecto:

 Sincronizar: Guarda el archivo local y actualiza los cambios en el archivo central; al mismo tiempo que
cargar nuevamente el archivo central, con todas las actualizaciones realizadas por los colaboradores.

Fernando Montaño La Cruz | fm@edu-cad.net 5

<!-- p. 6 -->

Revit - BIM Fernando Montaño

 Volver a cargar lo más reciente (RL): Carga nuevamente el archivo central, actualizando las
modificaciones realizadas por otros colaboradores.

Un aspecto fundamental para comprobar errores en la etapa de diseño es coordinando los sub-proyectos
realizados por los todos los colaboradores; por ejemplo: albañilería, estructura, instalaciones, etc. Detectar
interferencias en la etapa de construcción supondrá más costos y mayor pérdida de tiempo. Si los sub-proyectos
están realizados en Revit, la coordinación y verificación se realizará en Revit mismo; pero si los proyectos están
realizados en otras aplicaciones, entonces la coordinación se realizará en Naviswork.

Como ejemplo usaremos los proyectos de albañilería y estructura realizados en lecciones anteriores…

Para coordinar estos proyectos primero se debe vincular uno al otro; insertaremos la estructura en el pryecto de
albañilería.

Fernando Montaño La Cruz | fm@edu-cad.net 6

<!-- p. 7 -->

Revit - BIM Fernando Montaño

Obviamente estructura y muros o suelos tendrán muchas interferencias, pero estas se solucionan como fue
analizado también en lecciones anteriores. Las interferencias también podrían darse entre la estructura y la
carpintería, y esto sí vale la pena revisar.

Video 1/2: duración 11:13 / 8:01 minutos

Analizar y solucionar interferencias en el proyecto
Al integrar todos los sub-proyectos en un único proyecto, seguro existirán colisiones entre ellos, algunas lógicas y
cuyo ajuste no será urgente (como la estructura con muros, suelos y cubiertas) y otras más conflictivas y que
demandarán de soluciones inmediatas, como por ejemplo la estructura con las aberturas o con las restantes
instalaciones.

Para conocer estas colisiones, debemos Ejecutar comprobación de interferencias, herramienta que
encontraremos en Colaborar>Coordinar>Comprobación de interferencias>

Fernando Montaño La Cruz | fm@edu-cad.net 7

<!-- p. 8 -->

Revit - BIM Fernando Montaño

Seguidamente debemos establecer los 2 grupos de objetos a comparar, por ejemplo, por un lado puertas y
ventanas y por el otro todos los componentes de la estructura.

A continuación Revit nos dará un reporte detallado de todas las colisiones

Bastará seleccionar alguno de los componentes y hacer clic en Mostrar, para visualizar el problema de forma
destacada.

Fernando Montaño La Cruz | fm@edu-cad.net 8

<!-- p. 9 -->

Revit - BIM Fernando Montaño

En conocimiento del problema, el responsable del sub-proyecto deberá tomar las medidas que correspondan y
después repetir la verificación, bastará con actualizar el informe.

Video 3: duración 8:36 minutos

Simulacio n 4D

Un procedimiento de mucho impacto y ayuda consiste en crear simulaciones que muestren la secuencia
constructiva del edificio, a lo largo del tiempo. La secuencia de actividades que antes solo podíamos representar
en un diagrama GANTT, ahora y por procedimientos sencillos, también podemos mostrar mediante una
simulación 4D. Para hacerlo necesitaremos de Revit, pero también de Excel y Navisworks.

Navisworks es otra aplicación de Autodesk y que también podemos usar de forma gratuita en nuestro
aprendizaje. Navisworks permite hacer coordinación, revisión y análisis de proyectos; como así también es una
excelente herramienta para comunicación del diseño y procesos constructivos, a través de simulaciones
animadas y 4D. Permite integrar en un único modelo, modelos creados en diferentes aplicaciones, como ser

Fernando Montaño La Cruz | fm@edu-cad.net 9

<!-- p. 10 -->

Revit - BIM Fernando Montaño

Revit, AutoCAD, 3ds Max, Inventor, SolidWorks, Rhino, SketchUp, etc. Navisworks es la aplicación por
excelencia, para gestionar un proyecto completo.

Para una simulación 4D, al igual que para crear un GANTT, se requiere de ciertos datos básicos, como ser la
definición de tareas, el inicio de cada una de ellas y la duración de la misma. A diferencia del GANTT, donde solo
realizamos definiciones, en una simulación 4D será necesario asociar las tareas a los objetos del modelo 3D.

Nota: En lugar de Excel, sería mejor el empleo de aplicaciones más orientadas a la gestión de proyectos, como
ser Project; pero la demostración será en Excel por ser una aplicación de uso más generalizado y porque se
ajusta perfectamente a nuestras necesidades. Además de ello, Project no es una aplicación de uso libre para
estudiantes, como lo son las aplicaciones de Autodesk.

Paso 1: preparar el proyecto en Revit
Dos son las formas en que podemos definir los diferentes procesos o etapas de construcción del edificio:

\1. Creando Montajes…

\2. Mediante la creación de parámetros de proyecto.

Luego de asignar todas las tareas y/o crear los montajes, creamos una tabla de planificación que nos permita
obtener un listado de todas las tareas que asignamos y luego la exportamos en formato de texto.

NOTA: Dado que la propiedad relacionada a la etapa se aplicará a múltiples categorías de objetos, la
tabla de planificación será de Multi categoría; pero estas tablas NO incluyen datos de las familias de sistema (las
familias que no se cargan ni se guardan en archivos externos, como ser muros, suelos y cubiertas). Por esta razón

Fernando Montaño La Cruz | fm@edu-cad.net 10

<!-- p. 11 -->

Revit - BIM Fernando Montaño

faltarán datos en la tabla de planificación y sería conveniente crear una tabla externa en simultáneo con la
asignación de dichas tareas; con ello nos ahorraremos crear la tabla de planificación y exportarla a Excel.

A continuación exportamos el proyecto a Navisworks, a través de las Herramientas externas…

Video 4/5: duración 12:39 / 5:48 minutos

Paso 2: asignar tiempos a las etapas en Excel
La tabla que necesitamos deberá incluir, además de la Terea, al menos las siguientes columnas:

 Tipo de tarea: debemos indicar si la tarea involucra la Construcción o el Demoler componentes, o si se
trata de un elemento Temporal. (En nuestro ejemplo se trata de todos componentes a construir y por lo
tanto serán del tipo Construcción.)
 Fecha de inicio programado para la tarea.
 Duración de la tarea.
 Fecha de finalización programa para la tarea.

Fernando Montaño La Cruz | fm@edu-cad.net 11

<!-- p. 12 -->

Revit - BIM Fernando Montaño

También podría incluir datos como la fecha real de inicio y duración de las tareas, coste de los materiales, de la
mano de obra o de los equipos, como así también todos aquellos datos que considere necesarios para la
organización del proyecto.

Esta tabla deberá guardarse con la extensión CSV (del inglés comma-separated values).

NOTA: En versiones de Windows en español los archivos CSV pueden incluir “;” como separador, pero
Navisworks solo aceptará la “,” como separador, por lo tanto habrá que editar el archivo y remplazar unos por
los otros.

Video 6: duración 12:52 minutos

Paso 3: Navisworks: crear simulación 4D
El procedimiento en Navisworks consistirá de tres pasos:

\1. Abrir el proyecto proveniente de Revit.
\2. Cargar los datos de Excel, correspondientes a la secuencia de tareas.
\3. Asociar las tareas a los componentes del modelo 3D.

Para realizar las tareas 2 y 3, visualizaremos la línea de tiempo (TimerLiner)…

Fernando Montaño La Cruz | fm@edu-cad.net 12

<!-- p. 13 -->

Revit - BIM Fernando Montaño

Desde la ficha Origenes de datos, añadiremos el archivo de Excel, con las etapas del proyecto.

Acto seguido se deben asociar los contenidos de la tabla de Excel, a las columnas de datos de Navisworks…

Una vez cargada la tabla, sus datos debe ser añadidos a la ficha Tareas; esto se realiza mediante un clic derecho
en la referencia al archivo y designando la opción Regenerar jerarquía de tareas

Si bien ya contaremos con la lista de tareas, será necesario vincular dichas tareas a los componentes del modelo
3D. Para hacerlo recurrimos a una regla que permita enlazar automáticamente dichas tareas, a los componentes
que tengan idéntico valor en alguna de sus propiedades; esto demandará de crear una Nueva regla.

Fernando Montaño La Cruz | fm@edu-cad.net 13

<!-- p. 14 -->

Revit - BIM Fernando Montaño

La misma asociará las tareas de la columna Nombre a los Componentes cuya coincidencia sea textual, con la
propiedad llamada Etapa.

Creados los vínculos será posible desplazarnos hasta la ficha Simular y desplazar la barra de tiempo, para
conocer los avances de obra, en la fecha deseada.

Video 7/8: duración 8:50 / 9:19 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 14

<!-- p. 15 -->

Revit - BIM Fernando Montaño

Integrar AutoCAD al equipo de trabajo

La metodología BIM se basa en la suma de un modelo 3d e información asociada a los componentes del mismo.
Si bien AutoCAD es una aplicación CAD, permite crear modelos tridimensionales y asociarles información,
mediante la creación de bloques e inclusión de atributos de bloques. Un atributo de bloque puede determinar su
coste, características, momento en que se ejecuta en la obra, etc.

Una extracción de datos nos permitirá exportar a Excel los datos exactos del diseño; los que compartiremos por
medio de una tabla CSV…

Video 9: duración 20:17 minutos

Planificación en Excel
El responsable de gestionar las etapas de la obra podrá manipular los datos y definir el inicio y duración de cada
etapa, y coordinar con todos los restantes sub-proyectos…

Fernando Montaño La Cruz | fm@edu-cad.net 15

<!-- p. 16 -->

Revit - BIM Fernando Montaño

Video 10: duración 12:39 minutos

Navisworks: unión de sub-proyectos y animación 4D
En Navisworks se deben realizar las siguientes etapas:

\1. Añadir el sub-proyecto realizado en AutoCAD (o cualquier otra aplicación).

\2. Cargar la lista de tareas relacionada al sub-proyecto de AutoCAD o cargar la lista general y después
eliminar las tareas repetidas.

Fernando Montaño La Cruz | fm@edu-cad.net 16

<!-- p. 17 -->

Revit - BIM Fernando Montaño

\3. Asociar las tareas de la línea de tiempo, con sus respectivos objetos de AutoCAD; esto se realiza creando
una regla que asocie automáticamente…

…los elementos de columna Nombre (de tarea) y a los objetos que tengan el mismo valor asignado al
Atributo correspondiente (en este ejemplo el atributo ETAPA)

Video 11: duración 8:53 minutos

Navisworks: Análisis de colisiones
El proceso para realizar un análisis de colisiones es:

\1. Abrir la paleta Clash detective.
\2. Anadir una prueba.
\3. Asignar nombre a la prueba.
\4. Seleccionar el primer conjunto de objetos a comparar.
\5. Designar el segundo conjunto.
\6. E36..jecutar la prueba.

Fernando Montaño La Cruz | fm@edu-cad.net 17

<!-- p. 18 -->

Revit - BIM Fernando Montaño

Después de ejecutar la prueba se mostrarán cada una de las colisiones entre los conjuntos de objetos y para
cada una de ellas se podrán tomar las acciones que correspondan.

Video 12: duración 8:55

Integración con Navisworks
Navisworks permite integrar todos los sub-proyectos en un solo modelo tridimensional, independientemente de
la aplicación en la que fueron concebidos; permitiendo así que cada colaborador trabaje con los programas que
conoce y en los que se siente cómodo. Pero en el equipo de trabajo intervienen personas que no trabajan
directamente en esos sub-proyectos, que desconocen el uso de muchas o todas las aplicaciones de diseño
empleadas, pero que necesitan acceder a la información para la toma de decisiones; por ejemplo los inversores,
clientes, asesores, promotores, etc.

Navisworks permite compartir la información con estas personas, por medio de un visualizador gratuito, que
todos pueden descargar e instalar en sus ordenadores: Navisworks Freedom

Este visor 3d se puede descargar de la página: http://www.autodesk.com/products/navisworks/autodesk-
navisworks-freedom

…o mediante los siguientes enlaces:

 2017: Navisworks_Freedom_2017_dlm.sfx.exe
 2016: Navisworks_Freedom_2016_dlm.sfx.exe
 2015: Navisworks_Freedom_2015_dlm.sfx.exe
 2014: Navisworks_Freedom_2014_dlm.sfx.exe
 2013: 64 bits Navisworks_Freedom_2013_dlm.sfx.exe / 32 bits Navisworks_Freedom_2013_dlm.sfx.exe

El archivo a compartir será del tipo Niavisworks (*.NWD)

Fernando Montaño La Cruz | fm@edu-cad.net 18

<!-- p. 19 -->

Revit - BIM Fernando Montaño

En esta aplicación gratuita el proyecto se podrá visualizar desde cualquier punto de vista y en cualquier
momento de su construcción.

Video 13: duración 4:14

Fernando Montaño La Cruz | fm@edu-cad.net 19
