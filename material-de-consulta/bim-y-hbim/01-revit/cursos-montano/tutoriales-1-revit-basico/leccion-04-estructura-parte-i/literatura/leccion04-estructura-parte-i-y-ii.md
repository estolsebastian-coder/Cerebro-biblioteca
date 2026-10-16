---
type: libro
title: "3ds Max Design 2012 – para usuarios de AutoCAD"
author: "Fernando Montaño La Cruz"
categoria: "BIM Y HBIM"
paginas: 16
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/CURSOS MONTAÑO/TUTORIALES 1 (REVIT BÁSICO)/Leccion 04 Estructura Parte I/Literatura/Leccion04 Estructura Parte I y II.pdf"
convertido: 2026-10-16
---

# 3ds Max Design 2012 – para usuarios de AutoCAD

> Texto extraído de `BIM Y HBIM\01. Revit\CURSOS MONTAÑO\TUTORIALES 1 (REVIT BÁSICO)\Leccion 04 Estructura Parte I\Literatura\Leccion04 Estructura Parte I y II.pdf` (16 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Revit BIM

Autor:

Fernando Montaño

<!-- p. 2 -->

Revit - BIM Fernando Montaño

Lección 1 Curso online Revit BIM

Lección 4:

Estructura

Contenido de esta lección:

 12 videos / duración: 1 hs. 35 min.

 descargar PDF lección 04

 descargar contenido para las prácticas.

En esta lección aprenderá a:

 Crear vigas y pilares.
 Crear cimentaciones y suelos estructurales.
 Resolver uniones entre componentes estructurales.
 Crear sistemas de vigas.
 Añadir tornapuntas y conexiones.
 Crear cubiertas de chapas.
 Crear muros entre componentes de la estructura..

Fernando Montaño La Cruz | fm@edu-cad.net 2

<!-- p. 3 -->

Revit - BIM Fernando Montaño

Introducción
En esta lección abordaremos el tema Estructura. Comenzaremos con un nuevo proyecto (Práctica 4) consistente
en una sencilla nave industrial y posteriormente trabajaremos la estructura de los proyectos que venimos
realizando.

El objetivo de la primera parte es conocer las herramientas básicas de estructura y su aplicación en un proyecto
que se inicia por su estructura. El objetivo de la segunda práctica es conocer los procedimientos para añadir la
estructura en un proyecto iniciado previamente, o sea cómo coordinar la estructura con todo lo que ya tenemos
realizado.

Videos 1: duración 2:56 minutos

Iniciar un proyecto de estructura
El primer paso consiste en iniciar un proyecto a partir de la Plantilla Estructural suministrada por Revit, o de la
que tengamos personalizada para dicha función.

El siguiente paso será definir los Niveles/Level (LL) del proyecto y una Rejilla/Grid/Eixo (GR) coincidente con los
ejes de los componentes estructurales.

Fernando Montaño La Cruz | fm@edu-cad.net 3

<!-- p. 4 -->

Revit - BIM Fernando Montaño

Añadir pilares verticales

ESTRUCTURA>ESTRUCTURA>PILAR (CL)

STRUCTURE>STRUCTRE>COLUMN (CL)

ESTRUTURA>ESTRUTURA>COLUNA (CL)

Debemos posicionarnos en el plano donde nacerá el pilar y definir su dirección, hacia abajo
(Profundidad/Depth) o hacia arriba (Altura/Height); también debemos asignar el nivel al que se conectará o su
altura, en caso de no conectarse a ninguno.

El procedimiento para seleccionar un pilar es similar a cualquier otro, seleccionamos uno de la plantilla o
cargamos una familia de Pilares estructurales, de las suministradas por Revit. Si los elementos estándar no se
ajustan a nuestra necesidad, hacemos un duplicado y editamos sus dimensiones.

Idea: Al momento de insertar el pilar o después de haberlo insertado, podemos rotarlo con solo
pulsar la barra espaciadora.

Idea: La herramienta En rejilla inserta Pilares (Cimentación o Vigas) en los cruces de todas las
rejillas seleccionadas; con lo cual se acelera mucho el procedimiento de insertarlos.

Fernando Montaño La Cruz | fm@edu-cad.net 4

<!-- p. 5 -->

Revit - BIM Fernando Montaño

Videos 2/3: duración 14:24/3:35 minutos

Cimentacio n de hormigo n

Mediante el procedimiento de añadir pilares, vigas y zapatas a las intersecciones de las rejillas, creamos la
cimentación del proyecto. Mediante el procedimiento de duplicar elementos existentes y editar sus
dimensiones, creamos los siguientes componentes estructurales:

 Pilar de Ho de 0.30x0.30
 Zapata de Ho de 1.60x1.60x0.80
 Viga de Ho de 0.30x0.30

Los componentes estructurales se unen de forma automática y con la misma herramienta usada en muros y
suelos, es posible cambiar el tipo de unión.

Fernando Montaño La Cruz | fm@edu-cad.net 5

<!-- p. 6 -->

Revit - BIM Fernando Montaño

Después añadimos un suelo estructural de 15 cm de hormigón, usando el mismo procedimiento para crear
suelos arquitectónicos y cubiertas.

Videos 4: duración 10:17 minutos

Estructura de acero

El resto de la estructura se crea mediante los mismos procedimientos, pero designando los pilares y vigas
necesarios.

Idea: Muchas veces conviene crear pilares y vigas en la rejilla, aunque después sea necesario borrar
algunas o incluso dividirlas.

Fernando Montaño La Cruz | fm@edu-cad.net 6

<!-- p. 7 -->

Revit - BIM Fernando Montaño

Videos 5: duración 10:17 minutos

Uniones entre vigas y pilares

Las vigas y pilares inclinados tienen un punto redondo que determina su extremo analítico, y un par de flechitas
que determinan su extensión física; la misma se usa para determinar el distanciamiento entre ambos.

En estructuras metálicas las vigas se extenderán hasta el plano exterior de un rectángulo imaginario que
envuelve el pilar; algunas veces es lo correcto, pero otras no lo es.

En dichos casos seleccionar la viga (o pilar inclinado), hacer clic en la herramienta Cambiar referencia y designar
el plano hasta el que se debe prolongar.

Fernando Montaño La Cruz | fm@edu-cad.net 7

<!-- p. 8 -->

Revit - BIM Fernando Montaño

Para recortar los componentes de un modo más apropiado, usar la herramienta Aplicar recorte (CP)

La distancia de recorte se determina en las propiedades del componente.

Nota: Si viga y pilar NO son perpendiculares, el pilar deberá tener propiedad de inclinado, para crear
un recorte.

Fernando Montaño La Cruz | fm@edu-cad.net 8

<!-- p. 9 -->

Revit - BIM Fernando Montaño

Las uniones de vigas y pilares se conmutan con la herramienta Uniones de viga/pilar y haciendo clic en las
flechitas que se muestran.

Si se modifica la altura de los elementos, la unión permanecerá.

Algunas uniones podrían NO resolverse mediante los procedimientos automatizados, en dichos casos se puede
recurrir a la herramienta de crear huecos en los componentes; en general lo opción más fácil de usar es la que
permite crear los agujeros a partir de sus caras. El procedimiento para definir el perfil del recorte es similar a
cualquiera de los vistos hasta el momento.

Videos 6: duración 10:16 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 9

<!-- p. 10 -->

Revit - BIM Fernando Montaño
Sistema de vigas

El sistema de vigas rellena un área con un conjunto de vigas paralelas y en una cantidad fija y a distancias
iguales, o a una distancia específica entre ellas. El área a rellenar se detecta automáticamente entre los
elementos estructurales o es posible dibujar su borde, mediante un procedimiento igual al de los suelos.

Videos 7: duración 8:18 minutos

Tornapuntas y conexiones

Los tornapuntas son refuerzos estructurales de similar características que las vigas; en general los usamos para
triangular estructuras y evitar su deformación.

Fernando Montaño La Cruz | fm@edu-cad.net 10

<!-- p. 11 -->

Revit - BIM Fernando Montaño

Las conexiones entre elementos estructurales se añaden como Componentes prediseñados (familias
suministradas por Revit, creadas por el usuario o descargadas de Internet) o se pueden crear in situ.

Algunos ejemplos suministrados por Revit…

Videos 8: duración 4:45 minutos

Cerramientos verticales

Los muros de Revit no son compatibles con estructuras de acero, esto significa que no se pueden unir entre
ellos; por lo tanto los muros se deben colocar entre pilares y debemos editar su perfil, para adaptarlos a vigas
inclinadas.

Fernando Montaño La Cruz | fm@edu-cad.net 11

<!-- p. 12 -->

Revit - BIM Fernando Montaño

Videos 10: duración 5:37 minutos

Cubierta de la nave

Se trata de una cubierta simple, formado por 2 caras con pendiente y por lo tanto es posible crearla con la
herramienta Cubierta por perímetro. También es muy sencillo crearla a partir de una vista conveniente, como
una Cubierta por extrusión. Para esta opción solo se necesita dibujar las 2 líneas de la cara superior de la
cubierta….

Videos 11: duración 3:03 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 12

<!-- p. 13 -->

Revit - BIM Fernando Montaño
Cubierta de chapa

Debido a que no se trata de una cubierta sólida y que a nivel de estructura se crearon cada uno de los
componentes de la misma, sería interesante dotar a la cubierta de una chapa con su forma real, por ejemplo…

Revit nos proporciona una familia de cubiertas (y muros) llamada Cristalera inclinada

Se trata de una cubierta que estará formada por paneles que se repiten de forma matricial (filas y columnas) y
con elementos intermedios y en los bordes (que pueden o NO ser incluidos). Esta familia servirá para crear
cubiertas de chapa, de teja, vidriadas, etc.

Fernando Montaño La Cruz | fm@edu-cad.net 13

<!-- p. 14 -->

Revit - BIM Fernando Montaño

Crear una Cristalera inclinada o un Muro cortina es exactamente igual, en ambos casos debemos designar los
paneles y los tipos de montantes, verticales y horizontales, intermedios y para los extremos.

Tanto los paneles como los montantes, se deben crear y cargar previamente.

Chapa / Panel del muro cortina
Los pasos para crearla son:

\1. Iniciar una Familia nueva, partiendo de la plantilla Panel de muro cortina métrico / Metric Curtain Wall
Panel / Painel de parede cortina métrico.

\2. Verificar la unidad y ajustar la distancia entre los planos (eje a exterior de área útil).

Fernando Montaño La Cruz | fm@edu-cad.net 14

<!-- p. 15 -->

Revit - BIM Fernando Montaño

\3. Añadir los Planos de referencia (RP) necesarios para definir el perfil.

\4. Designar Extrusión, como tipo de volumen a crear, y dibujar el perfil de la chapa, encerrando un área.

\5. En una vista en alzado ajustar la altura del volumen al nivel superior de referencia.

Fernando Montaño La Cruz | fm@edu-cad.net 15

<!-- p. 16 -->

Revit - BIM Fernando Montaño

\6. Guardar la familia y cargarla en el proyecto.
\7. Editar cubierta y asignar el panel y sus correspondientes dimensiones.

Videos 12: duración 14:48 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 16
