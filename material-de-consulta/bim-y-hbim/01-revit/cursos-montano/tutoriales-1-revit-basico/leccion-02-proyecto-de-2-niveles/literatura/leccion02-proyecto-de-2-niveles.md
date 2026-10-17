---
type: libro
title: "3ds Max Design 2012 – para usuarios de AutoCAD"
author: "Fernando Montaño La Cruz"
categoria: "BIM Y HBIM"
paginas: 22
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/CURSOS MONTAÑO/TUTORIALES 1 (REVIT BÁSICO)/Leccion 02 Proyecto de 2 niveles/Literatura/Leccion02 Proyecto de 2 niveles.pdf"
convertido: 2026-10-16
---

# 3ds Max Design 2012 – para usuarios de AutoCAD

> Texto extraído de `BIM Y HBIM\01. Revit\CURSOS MONTAÑO\TUTORIALES 1 (REVIT BÁSICO)\Leccion 02 Proyecto de 2 niveles\Literatura\Leccion02 Proyecto de 2 niveles.pdf` (22 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Revit BIM

Autor:

Fernando Montaño

<!-- p. 2 -->

Revit - BIM Fernando Montaño

Lección 1 Curso online Revit BIM

Lección 02:

Vivienda en 2 niveles

Contenido de esta lección:

 14 videos / duración: 1 hs. 40 min.

 descargar PDF lección 2

En esta lección aprenderá a:

 Crear proyectos de dos niveles.
 Copiar componentes a otros niveles.
 Crear desniveles.
 Realizar ajustes a muros dependientes del nivel.
 Añadir escaleras por tramo y por boceto.
 Editar escaleras.
 Ajustar las losas a las escaleras.
 Crear secciones y cortes 3D.

Fernando Montaño La Cruz | fm@edu-cad.net 2

<!-- p. 3 -->

Revit - BIM Fernando Montaño
Objetivos de esta leccio n

La presencia de desniveles en un proyecto añade nuevos problemas y desafíos a resolver, por ejemplo:

 la ubicación en el espacio de los componentes.
 El encuentro entre componentes ubicados en diferentes niveles.
 Las aberturas compartidas por muros pertenecientes a distintos niveles.
 Asegurar la circulación por todos los niveles.

Muchos de estos problemas no se apreciarán en vistas de planta y alzado, por lo tanto será necesario recurrir a
nuevas herramientas de visualización, como secciones y cortes 3D.

Es objetivo de esta lección detectar y resolver todos los problemas ocasionados por la existencia de desniveles.

Fernando Montaño La Cruz | fm@edu-cad.net 3

<!-- p. 4 -->

Revit - BIM Fernando Montaño
Premisas previas del proyecto

Si bien esta lección tratará sobre un proyecto que intentaremos reproducir, cada uno siéntase libre de trabajar
con el proyecto que desee e incluso, darle la forma que desee. Dado que proyectar tiene mucho de resolver
problemas, en realidad de esta práctica lo que nos importan son los desafíos a resolver, más que el proyecto en
sí mismo. El principal desafío de esta lección es resolver los problemas que suponen los desniveles en un
proyecto.

Como ejemplo trabajaremos en el primer proyecto y definiremos los siguientes niveles…

Video 2.01: duración 4:44 minutos

Definir los niveles del proyecto

Iniciamos un proyecto nuevo utilizando la Plantilla arquitectónica.

En una vista de Alzado redefinimos la ubicación de los niveles de planta baja y planta alta.

Añadimos los niveles secundarios (NO asociados a Vistas de plano, desactivar la casilla correspondiente).

ARQUITECTURA>REFERENCIAS>NIVEL (LL)

ARCHITECTURE>> (LL)

ARQUITECTURA> (LL)

Fernando Montaño La Cruz | fm@edu-cad.net 4

<!-- p. 5 -->

Revit - BIM Fernando Montaño

En la lista de planos final, debemos tener 3 en Planos de planta y 1 en Planos de techo.

Cuando se superponen los nombres de los niveles, podremos hacer clic en el icono de recodo y crear un quiebre
en la línea de nivel.

Video 2.02: duración 8:08 minutos

Intercambio y ajuste de contenido

Dado que en la primera práctica del curso dibujamos la planta baja del proyecto 1, podremos copiar de ese
archivos los componentes que nos interesan, como muros y carpintería (los suelos y cubiertas serán diferentes y
los crearemos nuevos).

No perdemos tiempo en seleccionar los objetos individualmente, seleccionamos todo y aplicamos el filtro,
activando los componentes que deseamos seleccionar.

Fernando Montaño La Cruz | fm@edu-cad.net 5

<!-- p. 6 -->

Revit - BIM Fernando Montaño

Después lo de siempre, Ctrl+C (para copiar) y Ctrl+V (para pegar); previamente cambiamos al archivo
correspondiente y designamos la planta baja.

Seguidamente hacemos los ajustes de muros, a los niveles que corresponden; por ejemplo, los muros exteriores
y el interior correspondiente a la cochera, deben nacer a nivel de suelo exterior y no de la planta baja
propiamente dicha.

Fernando Montaño La Cruz | fm@edu-cad.net 6

<!-- p. 7 -->

Revit - BIM Fernando Montaño

En proyectos donde existan muchos desniveles, aquellos que sean de menor importancia podemos obviarlos y
simplemente hacer referencia a otros niveles y establecer una distancia de desfase.

Muros que inicialmente eran uno solo, quizás haya que dividirlos para ajustarlos mejor a sus niveles.

Obviamente, los ajustes de muros a sus niveles, deberán ser acompañados de ajustes en la carpintería también.

Video 2.03: duración 7:43 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 7

<!-- p. 8 -->

Revit - BIM Fernando Montaño
Editar perfil de muro

Dividir los muros crea mayor cantidad de ellos y puede volverlos más engorrosos, los proyectos grande. Ante
tales situaciones podemos mantener los muros como un solo componente y editar su perfil, para ajustarlo a los
desniveles.

Las recomendaciones para hacerlo son:

\1. Seleccionar únicamente el muro a editar y aquellos que necesitemos de referencia.
\2. Aislar estos muros.
\3. Visualizarlo de frente al plano de edición.

\4. Cambiamos a modo de edición.

\5. Mediante las herramientas que ya conocemos, hacemos los ajustes necesarios.

Video 2.04: duración 3:20 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 8

<!-- p. 9 -->

Revit - BIM Fernando Montaño

Crear 2º nivel

En el nivel de Planta Alta, por el momento, visualizaremos la proyección de lo que sucede en la Planta Baja…

Algunos muros van desde Planta Baja hasta el nivel de las cubiertas y es posible cambiar su Restricción superior.

Otro procedimiento se relaciona con copiar los muros de planta baja a planta alta, incluyendo aquellos interiores
que sean similares y ayuden a reducir el trabajo. Este procedimiento consiste en seleccionar y copiar lo útil de la
Planta baja, para después pegarlo, pero Alineando con los niveles seleccionados.

Fernando Montaño La Cruz | fm@edu-cad.net 9

<!-- p. 10 -->

Revit - BIM Fernando Montaño

Los muros de PB no responden a la misma realidad de los de PA, por lo tanto después haremos los ajustes que
correspondan en las restricciones de los muros y Restablecer algún perfil.

Fernando Montaño La Cruz | fm@edu-cad.net 10

<!-- p. 11 -->

Revit - BIM Fernando Montaño

Video 2.05: duración 5:51 minutos

Muros planta Alta

Ya sabemos hacerlos y no requieren de un video. No es necesario ajustarse estrictamente a los planos,
diseñarlos a gusto.

Fernando Montaño La Cruz | fm@edu-cad.net 11

<!-- p. 12 -->

Revit - BIM Fernando Montaño

Se proyectarán elementos de la planta baja, debido a que las plantas son cortes del proyecto a una determinada
altura (por defecto 1.20 sobre el nivel del plano), pero se proyectan los elementos que están por encima y por
debajo de dicho plano. Hasta no realizar los pisos, se proyectarán los elementos visibles de la planta baja.
Suelos

En la primera planta tendremos 3 suelos asociados a los niveles correspondientes: cochera, entrepiso y planta
baja.

Fernando Montaño La Cruz | fm@edu-cad.net 12

<!-- p. 13 -->

Revit - BIM Fernando Montaño

En planta alta también serán 3 los suelos. Por el momento obviamos la presencia de escaleras, debido a que no
están diseñadas y desconocemos el área que ocuparán.

Dada la similitud entre suelos, es posible copiarlos y después ajustarlos a sus niveles correspondientes.

Muros que comparten abertura
Cuando hay desniveles puede ser engorroso ajustar cada muro a sus alturas correspondientes, pero de no
hacerlo, el problema se evidenciará en algunas aberturas. En recurso rápido para solucionar este problema es
unirlos, de esta forma la abertura será compartida por ambos muros.

Video 2.06: duración 12:02 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 13

<!-- p. 14 -->

Revit - BIM Fernando Montaño
Secciones y secciones 3D

Para diseñar correctamente los entrepisos y las escaleras, necesitaremos recurrir a otros tipos de vistas, como
ser secciones y secciones en 3D.

Crear una sección 2D

VISTA>CREAR>SECCIÓN

VIEW>CREATE>SECTION

VISTA>CRIAR>CORTE

En una vista de planta designar por donde pasa el corte y después hacer los ajustes necesarios, mediante los
pinzamientos del marco del corte (alcance, invertir, .

Mediante el Navegador de proyectos podremos acceder a la vista.

Fernando Montaño La Cruz | fm@edu-cad.net 14

<!-- p. 15 -->

Revit - BIM Fernando Montaño

Sección segmentada
Si un corte lineal no muestra todo lo que necesitamos, podemos añadir divisiones al segmento, en los puntos
que sean necesarios.

Cortes 3D
Para crear un corte 3D basta con activar la Caja de sección (Section Box/Caixa de corte), correspondiente a una
vista 3D y ajustar el alcance del mismo. Dicha caja se activa desde la paleta de Propiedades.

Idea: Crear una copia de la vista 3D, para cada corte que queramos conservar.

Video 2.07: duración 7:07 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 15

<!-- p. 16 -->

Revit - BIM Fernando Montaño
Escaleras

ARQUITECTURA>CIRCULACIÓN>ESCALERA

ARCHITECTURE>CIRCULATION>STAIR

ARQUITECTURA>CIRCULAÇAO>ESCADA

Tenemos la posibilidad de utilizar modelos de escaleras predeterminados ( ) o hacerla con la

forma exacta que nosotros queramos ( )

Escalera por componentes rectos
Podrás ser una escalera formada por un solo tramo recto o por la sucesión de varios, unidos por descansillos. Al
ejecutar la orden y realizar el primer clic, Revit nos permitirá previsualizar la longitud de desarrollo que
demandará la escalera; si el clic lo realizamos antes del final requerido, ahí finalizará el primer tramo y en el
siguiente clic comenzará un nuevo tramo. En medio de ese 2º y 3er clic, de ser posible, se creará
automáticamente un descansillo; si o fuese posible, habrá que crearlo manualmente, con la herramienta
correspondiente (disponible después de ejecutar la orden escalera).

En la vista previa, tendremos la posibilidad de analizar el espacio que demandará y tomar decisiones, asignar
mayor o menor longitud a huellas o contrahuellas. Variaciones importantes a estos valores podrían violentar las
normas de diseño de la escalera y no ser admitidos por Revit; en caso de querer continuar, será necesario
modificar dichas reglas de diseño. En tal caso el procedimiento recomendado a seguir es editar el tipo de
escalera, crear una copia y asignar nuevas reglas de juego.

Fernando Montaño La Cruz | fm@edu-cad.net 16

<!-- p. 17 -->

Revit - BIM Fernando Montaño

Después de crear la escalera y como todo en Revit, podemos hacer los cambios y revisiones necesarias, como
cambiar dimensiones, tipos de escaleras o tipos de barandillas.

Video 2.08: duración 13:29 minutos

Escalera por boceto

ARQUITECTURA>CIRCULACIÓN>ESCALERA POR BOCETO

ARCHITECTURE>CIRCULATION>STAIR BY SKETCH

ARQUITECTURA>CIRCULAÇAO>ESCADA POR CROQUI
Este procedimiento para crear escaleras será uno de los que más usaremos, dado que no permite crear todo tipo
de soluciones que el proyecto demande. El procedimiento consiste en diseñar el contorno y las contrahuellas de
la escalera…

Video 2.09: duración 3:57 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 17

<!-- p. 18 -->

Revit - BIM Fernando Montaño
Desniveles pequen os

La comunicación entre el garaje y la vivienda, y el pasaje a planta baja, a pesar de ser desniveles muy pequeños,
pueden ser fácilmente resueltos con escaleras de un tramo.

Video 2.10: duración 9:34 minutos

Escalera del acceso

El acceso a la vivienda es un caso de escalera compleja y una solución correcta nos demandará de un sistema
mixto, comenzar con una escalera de tramo y convertirla en boceto, para su edición.

Esta escalera es compleja, debido a la presencia de la columna en su interior. Si no existiera dicha columna, la
resolveríamos con una escalera por boceto.

Fernando Montaño La Cruz | fm@edu-cad.net 18

<!-- p. 19 -->

Revit - BIM Fernando Montaño

Pero la columna nos obligará a rodear la columna con una única escalera; los procedimientos pueden ser varios,
por ejemplo partir de una escalera de 2 tramos rectos y después editarla.

Video 2.11: duración 3:57 minutos

Barandillas

ARQUITECTURA>CIRCULACIÓN>BARANDILLA

ARCHITECTURE>CIRCULATION>RAILING

ARQUITECTURA>CIRCULAÇAO>GUADA-CORPO

Las barandillas pueden colocarse en Anfitriones (escaleras o rampas) o pueden dibujarse por medio de un boceto.

Fernando Montaño La Cruz | fm@edu-cad.net 19

<!-- p. 20 -->

Revit - BIM Fernando Montaño

Video 2.12: duración 2:08 minutos

Ajustes entre suelos y muros

Los suelos que se extienden por muchas habitaciones, seguramente, se superpongan con algunos muros; esto es
un grave error constructivo, que como consecuencia provocará errores de visualización. Para solucionar estos
problemas debemos Unir los componentes.

MODIFICAR>GEOMETRÍA>UNIR

MODIFY>GEOMETRY>JOIN

MODIFICAR>GEOMETRÍA>UNIR

Fernando Montaño La Cruz | fm@edu-cad.net 20

<!-- p. 21 -->

Revit - BIM Fernando Montaño

El procedimiento consiste en designar los 2 objetos. Uno de ellos tendrá prioridad sobre el otro (el suelo) y por lo
tanto será el que permanecerá; eliminándose el tramo compartido de quien no tiene la prioridad. En caso de que
dicha prioridad no se corresponda con nuestro deseo, debemos cambiar dicho orden de unión.

MODIFICAR>GEOMETRÍA>CAMBIAR ORDEN DE UNION

MODIFY>GEOMETRY>SWITCH JOIN ORDER

MODIFICAR>GEOMETRÍA>ALTERNAR ORDEM DA UNIAO

Visualmente se soluciona el problema, pero constructivamente quizás NO, ya que probablemente el muro apoye
sobre el suelo y exteriormente veamos el acabado continuo del muro, que también cubre el borde del suelo. En
dicho caso necesitamos ajustar el alcance del suelo, para que coincida con la cama del muro que corresponda.

De esta forma el ajuste será el correcto…

Video 2.13: duración 8:09 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 21

<!-- p. 22 -->

Revit - BIM Fernando Montaño
Alineacio n de planos 3D

Debido a la representación de los componentes en 2D (elementos ocultos) algunos detalles se nos pueden
escapar, pero sí se visualizarán claramente en vistas 3D y secciones. De igual forma que alineamos los
componentes las vistas de planta, también podemos hacerlo en las vistas 3D, designando sus planos
correspondientes.

Idea: Después de alinear bloquear ubicación, para que escalera y suelo siempre permanezcan
unidos.

Video 2.14: duración 9:54 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 22
