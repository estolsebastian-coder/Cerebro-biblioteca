---
type: libro
title: "3ds Max Design 2012 – para usuarios de AutoCAD"
author: "Fernando Montaño La Cruz"
categoria: "BIM Y HBIM"
paginas: 22
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/CURSOS MONTAÑO/TUTORIALES 1 (REVIT BÁSICO)/Leccion 03 Personalizar y decorar muros y cubiertas/Leccion03/Leccion03 Personalizar ydecorar Muros.pdf"
convertido: 2026-10-16
---

# 3ds Max Design 2012 – para usuarios de AutoCAD

> Texto extraído de `BIM Y HBIM\01. Revit\CURSOS MONTAÑO\TUTORIALES 1 (REVIT BÁSICO)\Leccion 03 Personalizar y decorar muros y cubiertas\Leccion03\Leccion03 Personalizar ydecorar Muros.pdf` (22 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Revit BIM

Autor:

Fernando Montaño

<!-- p. 2 -->

Revit - BIM Fernando Montaño

Lección 1 Curso online Revit BIM

Lección 3:

Personalizar muros y cubiertas

Contenido de esta lección:

 XX videos / duración: X hs. XX min.

 descargar PDF lección 3

 descargar contenido para las prácticas.

En esta lección aprenderá a:

 Crear muros básicos (simples y dobles).
 Asignar prioridades de unión a los muros.
 Resolver el remate de muros.
 Crear muros por barrido y telares.
 Añadir componentes de muros barridos.
 Crear familias de perfiles.
 Crear muros apilados.
 Crear muros superpuestos y adosados.
 Crear canalones y bordes de cubiertas.
 Crear cielo rasos de cubiertas.

Fernando Montaño La Cruz | fm@edu-cad.net 2

<!-- p. 3 -->

Revit - BIM Fernando Montaño

Introducción
El objetivo de esta lección será dar solución a gran parte de los muros que nos tocará construir, por ejemplo:

Aplicación de distintos materiales superficiales…

Muros apilados de diferentes tipos…

Muros caprichosos con 3 tipos de acabados diferentes y con una distribución frontal irregular...

Fernando Montaño La Cruz | fm@edu-cad.net 3

<!-- p. 4 -->

Revit - BIM Fernando Montaño

Uso de molduras horizontales y verticales…

Zócalos…

Pero por compleja que sea la solución a la que debamos recurrir, siempre comenzaremos con un muro básico y
simple.
Personalizar muros

Para fijar algunos conceptos básicos, comenzaremos creando y analizando dos tipos de muros sencillos, uno de
tipo simple, con un solo componente revocado en sus 2 caras; y otro doble, con un aislante térmico de
separación y también revocado en sus dos caras.

Crear un nuevo tipo de muro
Siempre lo crearemos como un duplicado de alguno existente, de preferencia el más parecido.

Fernando Montaño La Cruz | fm@edu-cad.net 4

<!-- p. 5 -->

Revit - BIM Fernando Montaño

Después editamos su Estructura, creamos capas, asignamos espesores, materiales y prioridades a las uniones de
las capas (Función).

Video 1: duración 9:49 minutos

Prioridades = Funcio n

Las capas de los muros se unirán de acuerdo a PRIORIDADES; ellas determinan la correcta forma en que debe
extenderse cada uno de los componentes.

Para que sea más sencillo recordarlo o asociarlo, Revit asigna nombres de funciones a dichas prioridades; pero es
importante tener presente que NO se trata de funciones, son PRIORIDADES que definen la unión de los
componentes.

 Prioridad 1 = Estructura
 Prioridad 2 = Substracto
 Prioridad 3 = Capa térmica de aire
 Prioridad 4 = Acabado 1
 Prioridad 5 = Acabado 2

Fernando Montaño La Cruz | fm@edu-cad.net 5

<!-- p. 6 -->

Revit - BIM Fernando Montaño

Si nos basamos en los nombres, sucederán situaciones como las siguientes…

Para evitar la interrupción del puente térmico es necesario que la cámara de aire se extienda hasta unirse
consigo misma y que el que se interrumpa sea el mampuesto; por lo tanto dicha cámara debe tener mayor
prioridad.

Video 2: duración 5:02 minutos

Remate en extremo de muros

Las capas intermedias del muro pueden rematar en los extremos del muro, como también pueden ser cubiertas
por alguno de los materiales superficiales.

Fernando Montaño La Cruz | fm@edu-cad.net 6

<!-- p. 7 -->

Revit - BIM Fernando Montaño

El remate de muro en aberturas se puede designar desde Envolvente de inserciones o individualmente desde las
propiedades de las aberturas mismas.

Video 3: duración 4:16 minutos

Barrido de muros

Todas las molduras de un muro, como ser dinteles, cornisas, zócalos, remates de muros, etc., se pueden crear
por medio de barridos de muros. El procedimiento se basa en la extrusión de un perfil a lo largo de los muros
designados (camino). Dicho perfil puede seleccionarse de los disponibles en la plantilla

ARQUITECTURA>CONSTRUIR>MURO: BARRIDO

Fernando Montaño La Cruz | fm@edu-cad.net 7

<!-- p. 8 -->

Revit - BIM Fernando Montaño

ARCHITECTURE>BUILD>WALL: SWEEP

ARQUITECTURA>CONSTRUIR>PAREDE: MOLDURA

Es posible elegir un perfil disponible en la plantilla, cargar familias de perfiles o crear uno nuevo.

Pueden ser colocados de forma horizontal y vertical.

Fernando Montaño La Cruz | fm@edu-cad.net 8

<!-- p. 9 -->

Revit - BIM Fernando Montaño

Es posible editar su longitud y aplicarlo únicamente en los sectores del muro deseados; para esto basta editar los
puntos extremos. En dicha edición podemos dividir y alinear barridos.

Telares

Procedimiento exactamente igual al del barrido, pero el volumen del barrido se sustrae del muro.

ARQUITECTURA>CONSTRUIR>MURO: TELAR

ARCHITECTURE>BUILD>WALL: REVEAL

ARQUITECTURA>CONSTRUIR>PAREDE: FRISO

Video 4: duración 8:53 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 9

<!-- p. 10 -->

Revit - BIM Fernando Montaño
Crear un perfil de barrido de muro

Iniciar un archivo nuevo, del tipo familia y basado en la plantilla Perfil métrico (Metric Profile).

El cruce de los ejes será el punto de inserción del perfil. Revisar las unidades del proyecto (UN).

Crear el perfil mediante las herramientas de Dibujar.

Guardar el perfil y Cargarlo al proyecto (se cargará con el mismo nombre que fue guardado previamente).

Si en el camino del barrido no hay huecos, la moldura será continua…

Fernando Montaño La Cruz | fm@edu-cad.net 10

<!-- p. 11 -->

Revit - BIM Fernando Montaño

Por esta razón puede ser importante el punto de referencia del perfil; al tomar el punto superior y éste
desplazarlo X distancia de la base, sí cortará las aberturas y se interrumpirá…

Video 5/6: duración 8:40 / 7:48 minutos

An adir barridos y telares a tipos de muros

Los componentes estándar de un muro son capas de espesor y altura constante, pero los muros reales no
siempre son así de simples; muchos incluyen diversas molduras, como basamentos o cornisas.

Fernando Montaño La Cruz | fm@edu-cad.net 11

<!-- p. 12 -->

Revit - BIM Fernando Montaño

Revit no es ajeno a esta realidad y permite añadir componentes creados a partir de perfiles de barrido o de
telares.

Antes de añadir estos componentes al muro, son necesarios los perfiles; por lo tanto, si no existen, se deberán
crear.

Procedimiento para añadir barridos a un muro
\1. Editar el tipo de muro al que se desean añadir los nuevos componentes, si fuera necesario duplicarlo,
para contar con las 2 opciones de muro.

\2. Editar la estructura del muro. Activar la Vista previa y designar Vista: Sección…
\3. Hacer clic en Barridos o Telares, según sea el componente a incorporar.

\4. Añadir un barrido y designar el Perfil, su Material, su ubicación a lo alto del muro, mediante una
Distancia relacionada a la base del muro o a la parte superior de éste.

Fernando Montaño La Cruz | fm@edu-cad.net 12

<!-- p. 13 -->

Revit - BIM Fernando Montaño

Video 7: duración 6:00 minutos

Muros apilados

Revit permite superponer muros básicos (unos sobre otros), para dar solución a muros más complejos; a estos
muros se les llama Apilados.

El procedimiento para crear un muro apilado comienza editando y duplicando uno existente.

Fernando Montaño La Cruz | fm@edu-cad.net 13

<!-- p. 14 -->

Revit - BIM Fernando Montaño

Continúa editando su estructura y asignando los muros básicos que correspondan. Estos deben ubicarse en
orden y con las alturas que correspondan. Debe tenerse presente que uno solo será de altura variable, los
restantes serán de altura fija.

Video 8: duración 6:08 minutos

Muros superpuestos/adosados y unidos
(pra ctica 1)

Cuando las franjas de un muro son horizontales, resulta fácil deducir que se pueden aplicar muros apilados o
añadir muros por barrido.

Fernando Montaño La Cruz | fm@edu-cad.net 14

<!-- p. 15 -->

Revit - BIM Fernando Montaño

Pero cuando no lo son y sus alturas son variables, no es posible aplicar dichas solución apilada y engorrosa la
aplicación de barridos.

A simple vista se reconocen 3 terminaciones en estos muros, que bien se podrían considerar como 3 tipos de
muros diferentes. Teniendo presente 2 aspectos de los muros…

a) Es posible unir muros para que trabajen juntos.
b) Es muy fácil editar el perfil de un muro y moldearlo con cualquier forma

…se avizoran dos caminos, NO convencionales, por los que buscar una solución:

\1. Tres muros superpuestos y de perfil editado.
\2. Tres muros adosados y de perfil editado.

A continuación se exponen sus características.
Muros superpuestos

Utilizaremos 3 muros similares, pero con distinta terminación exterior. Los 3 tendrán una capa de
revoque/estucado (2.5 cm) y una de ladrillo hueco (15 cm). La terminación exterior será para cada caso: Madera
(2 cm), Ladrillo (5.5 cm) y Piedra (10 cm).

Fernando Montaño La Cruz | fm@edu-cad.net 15

<!-- p. 16 -->

Revit - BIM Fernando Montaño

A los muros de planta baja se les reducirá su altura...

… después se los copiará y se insertarán nuevos en el espacio hueco.

En cada nivel se aplicarán muros de terminación diferente.

Fernando Montaño La Cruz | fm@edu-cad.net 16

<!-- p. 17 -->

Revit - BIM Fernando Montaño

Corroboramos que los planos interiores están a plomo.

Después todo consiste en editar los perfiles de cada muro, de forma coordinada y coherente…

Video 9/10: duración 9:21/7:55 minutos

Muros adosados

Esta solución consiste en crear un tipo de muro que se corresponda con la sección más fina del muro, o sea la
que tiene el revestimiento exterior más fino...

Fernando Montaño La Cruz | fm@edu-cad.net 17

<!-- p. 18 -->

Revit - BIM Fernando Montaño

…y otros dos muros con únicamente el revestimiento exterior…

Debido a que en estos últimos muros el revestimiento exterior estará dentro del núcleo, en el primero el
revestimiento también deberá estarlo.

Los muros deberán superponerse de forma tal, que el plano interior de los 3 revestimientos coincida
exactamente; posteriormente se deben unir, designando primero el revestimiento de mayor grosor.

Video 11: duración 12:00 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 18

<!-- p. 19 -->

Revit - BIM Fernando Montaño

Cubierta y ajuste a muros

Las cubiertas están en 2 niveles diferentes y por ello las crearemos independientes.

Después creamos el encuentro entre ambas con la herramienta…

MODIFICAR>GEOMETRÍA>UNIR/SEPARAR CUBIERTA

MODIFY> GEOMETRY >JOIN/UNJOIN ROOF

MODIFICAR>GEOMETRÍA>UNIR/DESUNIR TELHADO

Designar el borde a modificar y después el plano hasta el que se extenderá.

Video 12: duración 10:41 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 19

<!-- p. 20 -->

Revit - BIM Fernando Montaño
Superposicio n de cubiertas

La superposición entre ambas cubiertas…

Se soluciona editando el perfil de la principal…

Video 13: duración 12:00 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 20

<!-- p. 21 -->

Revit - BIM Fernando Montaño
Imposta y canalo n

Las opciones que nos ofrecen las cubiertas para su remate son limitadas, apenas si un corte a plomo o escuadra.

Pero la realidad puede demandar de otras terminaciones y el uso de canalones. Mediante un procedimiento
similar al de muros barridos, podremos añadir impostas y canalones a las cubiertas.

En ambos casos es necesario contar con un perfil que defina la forma del elemento.

Video 14: duración 9:26 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 21

<!-- p. 22 -->

Revit - BIM Fernando Montaño

Cielorrasos en cubiertas

El componente "Cubierta: cielo raso" se utiliza, en general, para dar terminación al espacio exterior
comprendido entre la cubierta y el muro.

El procedimiento para crearlo es similar al de una cubierta, también lo es la forma de crear tipos y son
elementos que se pueden Unir, tanto a muros como a cubiertas, para solucionar los conflictos existentes.

Video 15: duración 5:38 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 22
