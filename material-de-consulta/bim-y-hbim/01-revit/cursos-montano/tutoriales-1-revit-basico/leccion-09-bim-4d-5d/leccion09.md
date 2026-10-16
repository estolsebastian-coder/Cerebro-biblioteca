---
type: libro
title: "3ds Max Design 2012 – para usuarios de AutoCAD"
author: "Fernando Montaño La Cruz"
categoria: "BIM Y HBIM"
paginas: 22
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/CURSOS MONTAÑO/TUTORIALES 1 (REVIT BÁSICO)/Lección 09 BIM 4D & 5D/Leccion09.pdf"
convertido: 2026-10-16
---

# 3ds Max Design 2012 – para usuarios de AutoCAD

> Texto extraído de `BIM Y HBIM\01. Revit\CURSOS MONTAÑO\TUTORIALES 1 (REVIT BÁSICO)\Lección 09 BIM 4D & 5D\Leccion09.pdf` (22 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



<!-- p. 2 -->

Revit - BIM Fernando Montaño

Lección 1

Lección 9:

4ª y 5ª dimensión BIM

Contenido de esta lección:

 9 videos / duración: 1 hs. 22 min.

En esta lección aprenderá a:

 Cuantificar el volumen de hormigón necesario para construir la estructura del proyecto.
 Crear materiales para cuantificar el volumen de cada tipo de hormigón.
 Crear parámetros de familia globales
 Exportar tablas a Excel.
 Calcular dosificación y costes de los hormigones.
 Actualizar datos de Revit en Excel.
 Planificar la obra a lo largo del tiempo.
 Graficar la planificación de obra.
 Graficar los avances de obra.
 Comparar la planificación y los avances de obra.

Fernando Montaño La Cruz | fm@edu-cad.net 2

<!-- p. 3 -->

Revit - BIM Fernando Montaño
5D BIM – la dimensio n econo mica

Las cuantificaciones y presupuestos, al igual que los controles de avances de obras son aspectos de suma
importancia y fáciles de instrumentar en Revit. En esta lección profundizaremos en el cálculo de insumos, para
ello no solo cuantificaremos el volumen de hormigón necesario en la estructura del proyecto, también nos
basaremos en el uso de hormigones de distintas resistencias y dosificaciones, para obtener las cantidades y
costos exactos de cemento, arena y piedra. Además de ello reportaremos informes con los avances de dicha
estructura, a los efectos de saber y graficar con exactitud, el volumen de hormigón construido, el que está en
ejecución y el que aún resta por construir.

Asignar tipos de hormigones
Supondremos que en el proyecto se emplearán 5 tipos de hormigones de diferentes resistencias y
dosificaciones: H250, H220, H200, H180 y H140. La representación gráfica de los hormigones puede ser siempre
la misma, pero necesitaremos crear un material para cada uno de ellos; bastará con duplicar uno existente y
asignar los nombres que correspondan.

Facilitar la cuantificación de materiales relacionados a la estructura
Del mismo modo que en la primera lección definimos una propiedad para facilitar el cálculo de materiales de
acabado, es conveniente crear una propiedad que permita distinguir los materiales de un rubro en particular,
por ejemplo la estructura. Se trata de un parámetro de proyecto de Si/No, para definir si se trata de un material
de ese rubro.

Deberá ser del Tipo de parámetro “Si/No” y estar relacionado a la Categoría “Materiales”. El nombre y dónde lo
agrupamos, podrían ser cualquiera, pero corresponde que sean lógicos y comprensibles para cualquier usuario

Fernando Montaño La Cruz | fm@edu-cad.net 3

<!-- p. 4 -->

Revit - BIM Fernando Montaño

A continuación editamos los Parámetros personalizados… de los hormigones correspondientes y activamos la
opción recién creada, lo que equivaldrá a Sí.

Biblioteca de materiales personalizada
Debido a que muchas veces los materiales están asignados en familias, que estas dependen de otros archivos y
que los materiales creados NO están en otros archivos; será conveniente añadir los nuevos materiales en
bibliotecas personalizadas.

Para crear una nueva biblioteca, hacemos clic en el símbolo , seleccionamos Crear biblioteca nueva y le
asignamos un nombre y ubicación.

Fernando Montaño La Cruz | fm@edu-cad.net 4

<!-- p. 5 -->

Revit - BIM Fernando Montaño

Después y mediante un procedimiento similar, es posible crear categorías; por ejemplo “Hormigones”.

Los materiales se incluyen en la biblioteca, haciendo clic derecho y designando Añadir a>Biblioteca>Categoría

Fernando Montaño La Cruz | fm@edu-cad.net 5

<!-- p. 6 -->

Revit - BIM Fernando Montaño

Idea: La plantilla “Estructura” incluye hormigones de diferentes resistencias y podemos añadirlos a una
biblioteca personalizada.

Video 1: duración 10:18 minutos

Para metros de familia y globales

El procedimiento para asignar el material a los elementos estructurales puede cambiar, pero siempre se inicia
desde la paleta de propiedades. Algunos elementos admitirán cambios individualmente, pero otros deben ser
modificados editando las familias.

Por ejemplo, en las familias de pilares y vigas es posible asignar materiales individuales…

Editando la familia comprobaremos que no es posible asignar un material distinto, ya que éste depende de un
parámetro de familia.

Fernando Montaño La Cruz | fm@edu-cad.net 6

<!-- p. 7 -->

Revit - BIM Fernando Montaño

De igual modo que editamos las dimensiones de la familia, es posible editar el parámetro de familia y asignar
otro material…

NOTA: Cuando la familia se añade a un proyectos, dicho parámetro de familia es el que permitirá
modificar el material (ya sea desde la paleta de propiedades o editando el tipo). Por el contrario, los
componentes de las familias que tengan asignado materiales NO se podrán editar desde el proyecto; se deberá
editar la familia y ésta deberá cargarse nuevamente en el proyecto.

Parámetros globales
La estructura de un edificio incluye varias familias, por ejemplo pilares, vigas y cimientos. Si deseamos que todos
sean del mismo material, pero todavía no sabemos cuál; lo correspondiente será asignarle un parámetro global
de material. Esto permitirá modificar el material de todas las familias, con solo editar dicho parámetro.

Para asignar o crear un PG, hacer clic en el botón ubicado a la derecha, del campo correspondiente al material.

Fernando Montaño La Cruz | fm@edu-cad.net 7

<!-- p. 8 -->

Revit - BIM Fernando Montaño

El mismo parámetro global puede asignarse a tantas familias como sea necesario y se edita en

Gestionar>Configuración>Parámetros globales (GL)

Video 2/2a: duración 13:05 /6:19 minutos

Asignar y cuantificar hormigones
Como el objetivo siempre es conocer los procedimientos, asignaremos indistintamente los hormigones creados a
pilares, vigas, losas y cimentación.

Después cuantificamos los volúmenes de hormigón, utilizando el parámetro personalizado, para distinguir los
materiales estructurales de los otros.

La tabla de cómputo de materiales será del tipo Multicategoría, dado que incluirá materiales de diferentes
categorías, como suelos, cubiertas y elementos estructurales.

Incluirá, al menos, los parámetros del Nombre y Volumen del material, como así también el parámetro que
permite distinguir los hormigones usados en estructuras.

Fernando Montaño La Cruz | fm@edu-cad.net 8

<!-- p. 9 -->

Revit - BIM Fernando Montaño

Este último parámetro lo usaremos como filtro, pero estará oculto en la tabla.

Clasificaremos los materiales por su nombre, pero sin detallar todos los ejemplares.

Sí calcularemos totales, para los volúmenes.

Fernando Montaño La Cruz | fm@edu-cad.net 9

<!-- p. 10 -->

Revit - BIM Fernando Montaño

El resultado final será una tabla de contenido muy concreto, el volumen total de cada tipo de hormigos usado en
estructuras.

Video 3: duración 6:49 minutos

Exportar datos de la tabla
Si bien Revit ofrece muchas funcionalidades para cuantificar insumos y hacer presupuestos, también tiene
algunas limitaciones; ya sea por estas limitaciones o por costumbre, podemos preferir hacer un presupuesto en
una aplicación externa, como ser Excel o cualquiera más específica.

En este ejemplo importaremos los datos de la tabla anterior en Excel, donde disponemos de una planilla para
calcular todos los componentes de los hormigones, el coste de cada uno de ellos y el coste total. Los datos que
necesitamos ingresar son las cantidades de cada tipo y los costes unitarios de los insumos (cemento, arena,
piedra y agua).

Fernando Montaño La Cruz | fm@edu-cad.net 10

<!-- p. 11 -->

Revit - BIM Fernando Montaño

Aspectos previos
Tener presente que la presencia de la unidad junto al valor numérico, puede llevar a que la aplicación destino
interpreté un texto y no un número. Para evitarlo, es conveniente eliminar dichos textos.

Idea: Si fuese necesario es posible hacer una copia de la tabla, de forma de tener una con los textos de las
unidades y otra sin ellos.

Exportar datos a Excel (en formato TXT)
Casi todos los presupuestadores permiten importar datos en formato de texto. Para crear dicho archivo en

Revit, primero seleccionar la tabla y después >Exportar>Informes>Tabla de planificación

Fernando Montaño La Cruz | fm@edu-cad.net 11

<!-- p. 12 -->

Revit - BIM Fernando Montaño

A continuación designar el nombre y la ubicación del archivo.

Importar datos en Excel
\1. Posicionarse en una celda donde pegar todos los datos, sin afectar a los existentes.
\2. Ir a Datos y hacer clic en Desde texto

\3. Seleccionar el archivo y hacer clic en Importar.
\4. En el paso 1 mantener los valores predeterminados y hacer clic en Siguiente. (Usar Delimitados.)
\5. En el paso 2 mantener los valores predeterminados y hacer clic en Siguiente. (Usar Tabulación.)
\6. En el paso 3 hacer clic en Avanzadas… y designar que el Separador decimal usado es el punto “.” Después
Aceptar y por último Finalizar.

\7. Seguidamente hacer coincidir los volúmenes de hormigón extraídos en Revit, con las celdas correspondientes.
Basta con escribir = hacer clic en la celda donde está el dato de Revit y pulsar Enter.

Fernando Montaño La Cruz | fm@edu-cad.net 12

<!-- p. 13 -->

Revit - BIM Fernando Montaño

Cuando se modifique el proyecto en Revit, solo habrá que crear un nuevo TXT que remplace al anterior,
actualizar los datos en Excel y designar el nuevo archivo.

Video 4: duración 11:09 minutos

4D BIM – el tiempo

La cuarta dimensión BIM asocia al proyecto con el tiempo, en sus diversas formas; en los avances de obra
durante el período de construcción, la durabilidad de los componentes o el mantenimiento del edificio a lo largo
de su vida útil. Por ejemplo, graficar los avances de obra y compararlos con lo planificado, es una gran
herramienta que nos ofrecen las aplicaciones BIM.

Planificación de avances de la obra
Para graficar los avances de obra se requiere de un parámetro a tales efectos, por ejemplo un parámetro
numérico que indique la semana en la que se planifica construir el componente; por ejemplo un parámetro
llamado Semana de construcción, cuyo valor a asignar será 1, 2, 3, 4, 5…

Fernando Montaño La Cruz | fm@edu-cad.net 13

<!-- p. 14 -->

Revit - BIM Fernando Montaño

Dicha propiedad se aplicará a todas las categorías que vayamos a planificar y a cada elemento se asignará un
valor, por ejemplo a la cimentación, la semana 1.

Para graficar las semanas de construcción, primero duplicar una vista, por ejemplo una 3D. En las Modificaciones
de visibilidad se asignarán Filtros con las especificaciones deseadas, por ejemplo diferentes colores para cada
semana.

Fernando Montaño La Cruz | fm@edu-cad.net 14

<!-- p. 15 -->

Revit - BIM Fernando Montaño

Fernando Montaño La Cruz | fm@edu-cad.net 15

<!-- p. 16 -->

Revit - BIM Fernando Montaño

Video 5: duración 8:13 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 16

<!-- p. 17 -->

Revit - BIM Fernando Montaño

Construido/En construcción/Proyectado
Una forma de combinar la cuarta y quinta dimensión BIM es en reportes que nos permitan conocer los avances y
costes de obra en determinado momento; por ejemplo, para conocer lo que ya se ha construido (y gastado), lo
que se construirá en la semana en curso y el dinero necesario para afrontar esa etapa, como así también todo lo
que queda por delante.

Para graficar lo ya construido, lo que se construirá en la semana (o cualquier período de tiempo definido) y lo
que está proyectado a futuro, bastará crear filtros que grafiquen el proyecto en relación al valor de la semana de
referencia. Por ejemplo, si la semana de referencia es la 3ª, crearemos tres filtros:

 Uno que muestre todo lo planificado para las semanas anteriores a la 3ª, y por lo tanto abarcaremos los
valores menores a 3.
 Otro que muestre lo planificado para la tercer semana y por lo tanto que muestre los valores iguales a 3.
 Otro que muestre lo planificado para las siguientes semanas y por lo tanto que muestre los valores
mayores a 3.

Para obtener reportes semanales, bastará con cambiar ese número “3” en los tres filtros, por el valor de la
semana que corresponda.

Video 6: duración 6:04 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 17

<!-- p. 18 -->

Revit - BIM Fernando Montaño

Avances reales de obra
Los avances de obra no siempre se ajustarán a lo planificado y lo previsto para la semana 3 quizás no se ejecutó
o quizás se ejecutó antes de lo previsto. Esto lo podemos graficar mediante otra propiedad similar a la anterior,
aplicable también a todos los componentes de proyecto y que estable la semana en la que se ejecutaron las
obras.

O simplemente una propiedad de Si/No para establecer lo que se construyó y lo que no.

Combinando lo planificado y lo ejecutado, es posible graficar los avances reales, los atrasos e incluso las obras
realizadas antes de tiempo. Los atrasos en una semana, sería todo lo que estaba planificado construir hasta la
semana anterior, sin embargo no tiene el valor Sí en su propiedad Construido.

Fernando Montaño La Cruz | fm@edu-cad.net 18

<!-- p. 19 -->

Revit - BIM Fernando Montaño

Adelanto sería todo aquello a construir la semana actual o cualquiera posterior, pero que ya está construido.

Los filtros para graficar estos avances reales, además de incluir propiedades de representación para cada
semana, deberán representar lo que aún no se ha construido y que no tiene un valor asignado. Una graficación
podría mostrar en blanco lo construido en fecha, en rojo los retrasos y en verde lo que está adelantado.

Video 7: duración 13:32 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 19

<!-- p. 20 -->

Revit - BIM Fernando Montaño

Planificar la cuantificación de hormigón
Conocer el volumen de hormigón necesario para cubrir la demanda de cada semana o el volumen ya ejecutado y
el que aún resta por ejecutar, pueden ser algunos de nuestros objetivos de planificación. Esto lo lograremos
incorporando las nuevas propiedades (Construido Si/No y Semana de construcción) en la tabla de planificación
de hormigón.

Para conocer el volumen ya construido y el que falta por ejecutar…

…bastará con aplicar una primera Clasificación que agrupe los volúmenes de hormigón, por su propiedad de
Construido Sí/No.

Fernando Montaño La Cruz | fm@edu-cad.net 20

<!-- p. 21 -->

Revit - BIM Fernando Montaño

Para planificar el volumen necesario para cada semana…

…bastará con aplicar una primera Clasificación que agrupe los volúmenes de hormigón, por su propiedad de
Semana de construcción.

Fernando Montaño La Cruz | fm@edu-cad.net 21

<!-- p. 22 -->

Revit - BIM Fernando Montaño

Video 8: duración 6:28 minutos

Fernando Montaño La Cruz | fm@edu-cad.net 22
