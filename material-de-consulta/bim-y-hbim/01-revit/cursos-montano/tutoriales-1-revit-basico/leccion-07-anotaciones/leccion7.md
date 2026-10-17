---
type: libro
title: "3ds Max Design 2012 – para usuarios de AutoCAD"
author: "Fernando Montaño La Cruz"
categoria: "BIM Y HBIM"
paginas: 19
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/CURSOS MONTAÑO/TUTORIALES 1 (REVIT BÁSICO)/Leccion 07 Anotaciones/Leccion7.pdf"
convertido: 2026-10-16
---

# 3ds Max Design 2012 – para usuarios de AutoCAD

> Texto extraído de `BIM Y HBIM\01. Revit\CURSOS MONTAÑO\TUTORIALES 1 (REVIT BÁSICO)\Leccion 07 Anotaciones\Leccion7.pdf` (19 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Revit BIM

Autor:

Fernando Montaño

<!-- p. 2 -->

Revit - BIM Fernando Montaño

Lección 1 Curso online Revit BIM

Lección 7:

Anotaciones

Contenido de esta lección:

 11 videos / duración: 1 hs. 52 min.

 descargar PDF lección N

 descargar contenido para las prácticas.

En esta lección aprenderá a:

 Acotar planos.
 Ajustar las características de las cotas.
 Definir los orígenes de coordenadas del proyecto.
 Distinguir entre Punto de reconocimiento y Punto base del proyecto.
 Añadir etiquetas para todos los componentes.
 Personalizar las etiquetas.
 Relacionar etiquetas y tablas de planificación.
 Graficar planos de colores.
 Definir etapas de proyecto y crear los planos correspondientes a cada una.

Fernando Montaño La Cruz | fm@edu-cad.net 2

<!-- p. 3 -->

Revit - BIM Fernando Montaño

Introducción
La documentación de un proyecto incluirá elementos geométricos, pero también muchos componentes de
anotación, como ser textos, textos de etiquetas, cotas, áreas, etiquetas de los componentes (muros, puertas,
ventanas, espacios, etc.) y un sinfín de elementos de anotación más. Esta lección estará dedicada a la creación
de todos estos tipos de elementos. Todos estos elementos de anotación serán independientes de la escala y los
tamaños que asignemos, serán los que tendrán en el papel impreso o en la publicación digital.
Cotas

Las cotas de Revit debemos analizarlas desde dos aspectos:

\1. Las herramientas para añadir cotas.
\2. Las características del objeto de cota.

Herramientas para añadir cotas
A ellas accedemos desde las barra de herramientas de acceso rápido o desde la ficha Anotar.

Generalmente comenzaremos acotando los muros y usaremos la herramienta llamada Alineada . Será
necesario designar si queremos colocar cotas manualmente (Referencias individuales) o si deseamos acotar
muros de forma automática (Muros enteros). En caso de seleccionar esta última, se pueden incluir o no los
huecos (dependerá de las Opciones del comando) y si los acotaremos hasta sus extremos o sus ejes. Los muros
se podrán acotar hasta sus ejes o sus extremos o caras.

Fernando Montaño La Cruz | fm@edu-cad.net 3

<!-- p. 4 -->

Revit - BIM Fernando Montaño

Nota: Si desde el extremo del muro acotado, nace uno que no es perpendicular a él, Revit nos
permitirá designar otros puntos a acotar y que se proyectarán sobre la misma línea.

Idea: Después de seleccionar una línea de cotas, podremos añadir o eliminar nuevos puntos de
referencia. Al designar un punto nuevo se crea una referencia, pero al designar uno existente, se elimina la
referencia correspondiente. Siempre terminamos este procedimiento haciendo clic en un espacio vacío.

Modificando el tipo de cota, pero usando la misma herramienta y los mismos procedimientos, podremos añadir
cotas de línea base…

O cotas por coordenadas…

Fernando Montaño La Cruz | fm@edu-cad.net 4

<!-- p. 5 -->

Revit - BIM Fernando Montaño

Video 1: duración 11:01 minutos

Cotas lineales
Esta herramienta proyecta las cotas sobre una línea horizontal o vertical, pero a diferencia de las anteriores
proyecta la distancia entre puntos y no entre elementos, por lo tanto es necesario designar cada punto a acotar.

Cotas angulares
Designar las dos caras que definen un ángulo y después la ubicación de dicha cota.

Fernando Montaño La Cruz | fm@edu-cad.net 5

<!-- p. 6 -->

Revit - BIM Fernando Montaño

Cota Radial/Diámetro
Designar el arco y después la ubicación de la cota.

Longitud de arco
Primero se designa el arco a acotar, después 2 elementos que definan desde donde hasta donde se acotará y por
último, la ubicación de la cota.

Video 2: duración 3:39 minutos

Cota de elevación
Esta herramienta permite acotar la altura (Z) de un elemento, en general la usamos en alzados y secciones, pero
también la podemos usar en planos para acotar elementos desfasados de los muros, por ejemplo el umbral de
puertas o el antepecho de ventanas. Designar el elemento y la ubicación de la cota, mediante 2 puntos.

Fernando Montaño La Cruz | fm@edu-cad.net 6

<!-- p. 7 -->

Revit - BIM Fernando Montaño

Sistemas de coordenadas
Revit ofrece 2 orígenes de coordenadas a los que podremos hacer referencia, uno para uso interno del proyecto

(Punto base del proyecto ) y otro más amplio, en general vinculado al terreno (Punto de reconocimiento

).

Para designar el Punto base del proyecto es necesario cambiar el estado de delimitación del punto , en caso

de NO hacerlo ( ), junto con el origen se desplazará todo el proyecto.

Cota de coordenadas de punto
Las cotas de coordenadas de punto pueden estar referidas a cualquiera de los orígenes, designándose esto en el
tipo de Cota de coordenada.

Fernando Montaño La Cruz | fm@edu-cad.net 7

<!-- p. 8 -->

Revit - BIM Fernando Montaño

Norte del proyecto y norte real
Habitualmente y si es posible, será más cómodo trabajar el proyecto en modo ortogonal (suponiendo el Norte
en dirección vertical); pero difícilmente el norte real coincida con esta dirección, por lo tanto habrá que designar
dicha dirección. En las propiedades de la vista es posible designar cual de ambos nortes será la referencia, para
modificar el real, será necesario designarlo.

Designado el norte real, lo rotamos desde Gestionar>Ubicación de proyecto>Rotar norte real

Video 3: duración 11:13 minutos

Características de los tipos de cotas
Las características de las cotas se pueden configurar modificando el Tipo, desde la paleta de propiedades o
accediendo por la cinta de herramientas Anotar>Cota, expandiendo el grupo y designando el tipo de cota a
editar; por ejemplo Tipos de cota lineal.

Fernando Montaño La Cruz | fm@edu-cad.net 8

<!-- p. 9 -->

Revit - BIM Fernando Montaño

Será necesario designar el Tipo de cota a editar, las propiedades, según correspondan, estarán organizadas en
las persianas Gráficos y Texto. La mayor parte de las propiedades son muy intuitivas y bastará con editarlas y
aplicarlas, para visualizar los cambios en el proyecto; si los cambios no son de acuerdo a lo esperado, volvemos
los valores a su estado anterior.

Video 4: duración 14:25 minutos

Etiquetas

Las etiquetas son elementos de anotación, que muestran información sobre cualquier elemento del modelo;
como ser muros, puertas, ventanas, habitaciones, etc.

Dichas etiquetas puede incluirse mediante tres procedimientos:

\1. Al insertar el elemento en el modelo, para esto es necesario activar la opción Etiquetar al colocar, antes
de añadir el elemento correspondiente, por ejemplo al añadir puertas…

Fernando Montaño La Cruz | fm@edu-cad.net 9

<!-- p. 10 -->

Revit - BIM Fernando Montaño

\2. Etiquetar elementos uno a uno usando la herramienta Anotar>Etiqueta>Etiquetar por categoría y
designando cada elemento a etiquetar.

\3. Etiquetar todos los elementos de una categoría usando la herramienta Anotar>Etiqueta>Etiquetar
todo. Se abre un cuadro en el que designamos la categoría a etiquetar (por ejemplo Puertas) y la
etiqueta que deseamos usar.

Idea: Algunas categorías no están disponibles para Etiquetar todo, esto se debe a que no está cargada
una etiqueta para tal categoría. Ante una situación como esta, etiquetamos un elemento solo, entonces Revit
nos pedirá cargar la familia correspondiente a esa categoría; una vez cargada, quedará disponible para su uso
masivo.

Fernando Montaño La Cruz | fm@edu-cad.net 10

<!-- p. 11 -->

Revit - BIM Fernando Montaño

Video 5: duración 7:00 minutos

Modificar etiquetas y/o añadir nuevas
Si bien siempre es posible crear familias a partir de la plantilla correspondiente, será más fácil si se edita una
familia, se realizan las modificaciones pertinentes (de geometría y etiquetas de texto), se guarda con un nombre
diferente y se carga en el proyecto actual.

Tablas de planificación
Las tablas de planificación, al igual que las etiquetas, permiten documentar los datos de los componentes del
proyecto; se pueden usar tanto para incluir en planos, como para controlar los datos de las etiquetas. Por
ejemplo, una tabla de planificación de puertas permite saber la cantidad de puertas de cada tipo hay en el
proyecto; pero también permite establecer las propiedades de éstas. La tabla permite extraer únicamente la
información de puertas y será más simple detectar errores, realizar algunos tipos de cambios o calcular insumos
y hacer presupuestos.

Video 6: duración 12:30 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 11

<!-- p. 12 -->

Revit - BIM Fernando Montaño
Habitaciones

Las habitaciones son elementos del modelo (como lo son muros, aberturas, suelo, etc.), aunque están muy
relacionados a las etiquetas, por la información que permiten aportan a la documentación del proyecto
(nombres, áreas, volúmenes, etc.)

La herramienta se ejecuta con las teclas RM y encuentra en Arquitectura>Habitación y área>Habitación .
Bastará designar un punto dentro del área, para crear la habitación delimitada por los elementos que la rodean.

Todos los componentes capaces de delimitar una habitación, incluyen una propiedad que establece si son o no,
límites. Los muros de un placar, por ejemplo, en muchos casos no deben delimitar las habitaciones, sino que
deben estar incluidos en ellas; por lo tanto, en estos muros no se debe activar dicha propiedad.

Del mismo modo que algunos elementos físicos no deben ser límites, también se suele dar la necesidad de crear
dos o más habitaciones, dentro de un mismo espacio; por ejemplo para delimitar el área que corresponde a un
estar y al comedor. Para tales situaciones disponemos de la herramienta Arquitectura>Habitación y

área>Separador de habitación

Fernando Montaño La Cruz | fm@edu-cad.net 12

<!-- p. 13 -->

Revit - BIM Fernando Montaño

Idea: Es posible crear todas las habitaciones de una vez, con la herramienta Colocar habitaciones

automáticamente . El problema de hacerlo radica en que su numeración será automática y no el orden que
deseamos.

Siguiendo procedimientos ya estudiados, es posible personalizar las etiquetas de las habitaciones.

Fernando Montaño La Cruz | fm@edu-cad.net 13

<!-- p. 14 -->

Revit - BIM Fernando Montaño

Video 7/8: duración 8:23/9:48 minutos

Esquemas de color
Los esquemas de color (plantas y secciones) son útiles para ilustrar gráficamente las categorías de espacio, ya
sea por habitaciones, por áreas, por alguna clasificación (Departamento), etc.

Dicho esquema de color se activa desde Propiedades>Gráficos>Esquema de color

Se abre un cuadro en el que designamos la Categoría y la propiedad a clasificar.

Fernando Montaño La Cruz | fm@edu-cad.net 14

<!-- p. 15 -->

Revit - BIM Fernando Montaño

Pueden ser por superficie y establecer franjas, por ejemplos las habitaciones de menos de 10m² y las de superior
área.

Es posible establecer la característica que queramos, mediante Departamento y aplicar el correspondiente
esquema de color.

Esta planta de colores no significaría nada, si no es acompañada de una leyenda que explique el significado de
cada uno de los colores. Dicha leyenda se añade desde Anotar>Relleno de color>Leyenda de relleno de color

Fernando Montaño La Cruz | fm@edu-cad.net 15

<!-- p. 16 -->

Revit - BIM Fernando Montaño

Video 9: duración 11:47 minutos

Etapas del proyecto

En los conceptos BIM se incluyen, además de las 3 dimensiones por todos conocidos, varias dimensiones más,
relacionadas con el tiempo y la economía. La 4ª dimensión se relaciona con el paso del tiempo y abarcar desde
las etapas de un proyecto, hasta detalladas simulaciones del proceso de construcción de un proyecto (en general
realizadas con la aplicación Navisworks). Muchos proyectos a construir se planifican en una sola etapa; pero en
las reformas y ampliaciones a proyectos, existen al menos 2 etapas, que involucran a lo existente y a las
intervenciones nuevas.

Supondremos que tenemos un proyecto y poco dinero, por lo tanto haremos una pequeña reforma interna, que
afectará parte de lo existente. En una segunda etapa haremos una pequeña ampliación y en un futuro una
segunda ampliación. Planificar las intervenciones a lo largo del tiempo es tener presente esa 4ª dimensión BIM y

el primer paso consiste en definir las Fases del proyecto (Gestionar>Proceso por fases>Fases ).

Fernando Montaño La Cruz | fm@edu-cad.net 16

<!-- p. 17 -->

Revit - BIM Fernando Montaño

Como se trata de modificaciones a un edificio Existente, mantendremos la etapa con dicho nombre. A las
restantes etapas les llamaremos Reforma, Ampliación y A futuro. Es importante respetar el orden en el tiempo
de las etapas.

En la etapa final de un proyecto ejecutivo, debemos preparar los gráficos que serán presentados a los
organismos de control, para su autorización. Estos dibujos se deben llevar a cabo teniendo en cuenta una
codificación específica y obligatoria. Si bien los criterios pueden cambiar en cada país, uno muy usado es NO
incluir sombreados en muros existentes que van a quedar, el muro pintado de negro para las nuevas
edificaciones y el muro rayado a 45º, para indicar su demolición.

En Revit dichos gráficos están predefinidos, pero es posible modificarlos, estableciendo Filtros de fases o
Modificaciones de gráficos. Por ejemplo, si queremos que el relleno de los muros a construir sea en color rojo,
es necesario designarlo en Modificaciones de gráficos

Y designar que los gráficos de lo Nuevo, serán acordes a lo Modificado (en Modificaciones de gráficos)

Fernando Montaño La Cruz | fm@edu-cad.net 17

<!-- p. 18 -->

Revit - BIM Fernando Montaño

Antes de añadir las modificaciones a una etapa, es necesario crear una vista nueva y asignar la etapa
correspondiente, en Propiedades>Proceso por fases>Fase

Todo lo que haya que derribar, se asigna mediante la herramienta Modificar>Geometría>Derribar

Fernando Montaño La Cruz | fm@edu-cad.net 18

<!-- p. 19 -->

Revit - BIM Fernando Montaño

Todas las acciones de derribo y construcción que se realicen, tendrán su correspondiente expresión gráfica.
Cuando se derriba una abertura, automáticamente se construye el muro para cubrir el hueco.

A cada componente del proyecto es posible designar su fase de creación y derribo…

Video 10/11: duración 9:56/11:55 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 19
