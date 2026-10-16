---
type: libro
title: "GUIA%20PRESUPUESTO%20_ver%2006-08_"
author: "Ana Laura"
categoria: "MATERIAL O.R.T"
paginas: 13
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/MATERIAL O.R.T/gestion de obras/sp/GUIA%20PRESUPUESTO%20_ver%2006-08_.pdf"
convertido: 2026-10-16
---

# GUIA%20PRESUPUESTO%20_ver%2006-08_

> Texto extraído de `MATERIAL O.R.T\gestion de obras\sp\GUIA%20PRESUPUESTO%20_ver%2006-08_.pdf` (13 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



Módulo
SP 3.0
Presupuesto

Versión3.14.001
06/2008

<!-- p. 2 -->

Contenido
\1. GESTION DE COMPOSICIONES (desde Datos Básicos)................................................................. 3
1.1. Crear composiciones (tarjetas) partiendo de un registro vacío................................................... 3
1.2. Crear composiciones partiendo de la copia una existente.......................................................... 3
1.3. Crear nueva carpeta en la jerarquía de Composiciones ............................................................. 3
\2. GESTION DE OBRAS................................................................................................................. 4
2.1. Crear obra............................................................................................................................ 4
2.2. Dar permisos al usuario ......................................................................................................... 4
2.3. Seleccionar la obra ................................................................................................................ 4
2.4. Cambiar el estado de una obra............................................................................................... 5
2.5. Editar datos de una obra........................................................................................................ 5
\3. GENERACIÓN DE RUBRADO DE PRESUPUESTACION ................................................................... 5
3.1. Crear el rubrado de presupuestación....................................................................................... 5
3.2. Ajustar (particularizar) la definición de algunas composiciones .................................................. 6
3.3. Crear composiciones globales desde el rubrado de presupuesto ................................................ 7
3.4. Ver la distintas inserciones de una composición dentro de una obra........................................... 7
3.5. Ingresar volúmenes............................................................................................................... 7
3.6. Ingresar repetidores.............................................................................................................. 7
\4. HERRAMIENTAS DE APOYO (rubrado de presupuesto)................................................................. 8

4.1. Vistas (zoom) ................................................................................................. 8

4.2. Visualizar composiciones incompletas ............................................................................... 8

4.3. Revisar el presupuesto ............................................................................................... 9

4.4. Edición rápida ................................................................................................................ 9
\5. PRECIOS Y MONEDAS............................................................................................................... 9
5.1. Precios por lista de precios..................................................................................................... 9
5.2. Precios en grilla definición de rubrado de presupuesto.............................................................10
5.3. Cotizaciones ........................................................................................................................10

\6. COSTOS INDIRECTOS ......................................................................................................10
6.1. Definición (cálculo) de costos indirectos .................................................................................10
6.2. Distribución (prorrateo) de costos indirectos...........................................................................10

\7. UTILIDADES ...................................................................................................................11
7.1. Definición (cálculo) y prorrateo de leyes sociales.....................................................................11

\8. IMPUESTOS ....................................................................................................................11
8.1. Selección de impuestos.........................................................................................................11
8.2. Forma de aplicación y forma de cálculo..................................................................................11

\9. LEYES SOCIALES .............................................................................................................12
9.1. Selección de definición para una obra ....................................................................................12
9.2. Forma de aplicación y forma de cálculo..................................................................................12

\10. PORCENTAJES VARIOS ....................................................................................................12

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 2 de 13

<!-- p. 3 -->

\1. GESTION DE COMPOSICIONES (desde Datos Básicos)

1.1. Crear composiciones partiendo de un registro vacío
1.1.1. Navegar a DatosBásicos/Composiciones(Ctrl+t)
1.1.2. Agregar un registro vacío (Insert)
1.1.3. Completar los datos del cabezal: Composición (código) / Nombre /
Descripción/Tipodeobra/Unidad/Carpeta.

Tipo de obra: el tipo de obra es un filtro que asocia las distintas composiciones a los distintos
tipos de obras definidos. Si se define como genérica (Gen) se podrá compartir desde todos los
tipos de obras.

1.1.4. Cargar los datos de definición de la composición. Se agregarán insumos o sub-
composiciones con sus respectivos datos: Tipo (insumo/composición) / Tipo /
Código/Cantidad(rendimiento).

Para seleccionar un insumo a composición (insumo/ composición) utilizar la ayuda de
búsqueda: F3. Esta ayuda nos permitirá buscar tanto por código (nombre corto), por el nombre
largo, o por la jerarquía de clasificación (carpetas).

1.2. Crear composiciones partiendo de la copia de una existente
1.2.1. Navegar a Datosbásicos/Composiciones(Ctrl+t)
1.2.2. Seleccionar de la lista desplegada la composición que se tomará como base de
copia.
1.2.3. Copiar la composición y sus insumos
1.2.4. Pegar la composición y sus insumos
1.2.5. Actualizar los datos del cabezal: Composición (código) / Nombre /
Descripción/Tipodeobra/Unidad/Carpeta.

Código (nombre corto de la composición): recordar que los códigos son únicos. En tanto no se
modifique el que se tomó como copia el sistema advierte: “la composición ya existe”.

1.2.6. Actualizar los datos de definición de la composición (tarjeta). Se agregarán los
insumos o sub-composiciones que estén faltando, se eliminarán los insumos o sub-
composiciones que no se utilicen, se ajustarán los rendimientos de aquellos que
corresponda.

1.3. Crear nueva carpeta en la jerarquía de Composiciones
1.3.1. Navegar a DatosBásicos/Composiciones(Ctrl+t)

1.3.2. Ingresar a la definición de jerarquías
1.3.3. Ubicarse en el lugar donde queremos ingresar la nueva carpeta de clasificación.
1.3.4. Agregar una nueva carpeta , ingresando el nombre que corresponda.

En el caso que la carpeta quede mal ubicada dentro del “árbol” de clasificación, se puede cortar
y pegar en la nueva ubicación (funciones asociadas al botón derecho del mouse). Este
movimiento arrastra todo el contenido de la carpeta a la nueva ubicación. El nombre también se
puede editar (doble click) y modificar en cualquier momento.

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 3 de 13

<!-- p. 4 -->

\2. GESTION DE OBRAS

2.1. Crear obra
2.1.1. Navegar a Obra/Ver-Crear obras...

2.1.2. Agregar un registro vacío (Insert)
2.1.3. Completar los datos generales de la obra (General): Obra(código)/Nombre/
Dirección/Cliente/TipodeObra/SituacióndelaObra

Tipo de obra: Tener presente que sólo se podrán copiar datos de una obra a otra cuando son del
mismo tipo.

Situación de la obra: Para presupuestar, seleccionar “Presupuestación” o “Presupuestación y
Gestión” en el caso de trabajar integrado con el módulo de gestión de obras (SGL).

2.1.4. Completar los datos de presupuesto de la obra (Presupuesto):
 Moneda base: moneda con la cual se va a trabajar en el armado del
presupuesto
 Fecha de inicio obra/ Duración de la obra / Comienzo de cobro:
Sólo a los efectos de la programación y el estudio de flujo de caja
 Volumen (de obra) / Unidad: Sólo a los efectos de un registro
estadístico
2.1.5. Completar los datos de Origen Presupuesto:
 Origendelrubrado: origen de copia del rubrado

Al tomar la opción ninguno no se podrán copiar otros datos desde otras obras, como por
ejemplo: precios, metrajes, etc.

 Origendeprecios: origen de copia de lista de precios. Puede ser de una
obra distinta a la seleccionada para copiar el rubrado.

En los dos casos para desplegar la lista de obras apretar F3

2.1.6. Seguridad

No es necesario completar los datos de seguridad, estos son datos de auditoría y los completa el
sistema.

2.2. Dar permisos al usuario
Las obras se crean con todos los permisos deshabilitados, el administrador del sistema
deberá generar los permisos correspondientes al usuario para la obra creada (ver
manual).

En la versión “Empresarial” los permisos son siempre globales, es decir, para todas las obras.

2.3. Seleccionar la obra
2.3.1. Navegar a Obra/Abrir(Ctrl+A)
2.3.2. Seleccionar de la lista la obra creada.

Se muestran dos listas una de existentes y otra de recientes que muestra los últimos accesos.

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 4 de 13

<!-- p. 5 -->

También se discrimina el presupuesto base y las versiones de precios: .. Las “versiones” son
distintos estudios de presupuestos de una misma obra.

No se pueden crear versiones de obra si el presupuesto está cerrado o estuviera en etapa de
control.

2.4. Cambiar el estado de una obra
2.4.1. Navegar a Obras/Ver-Crearobras...
2.4.2. Seleccionar

para cerrar (congelar) los datos del presupuesto

para pasar la obra a control
para cerrar (congelar) los datos de control y presupuesto

Las consultas y reportes del sistema están siempre disponibles independientemente del estado de
la obra

2.5. Editar datos de una obra
2.5.1. Navegar a Obras/Ver-Crearobras...
2.5.2. Modificar posicionándose en la celda que contiene el dato que se quiere
modificar

Los datos que se pueden modificar (editables) se diferencian de los que no por el color de fondo
de la celda; los de fondo gris no se pueden modificar, los de fondo blanco si.

\3. GENERACIÓN DE RUBRADO DE PRESUPUESTACION

3.1. Crear el rubrado de presupuestación

3.1.1. Seleccionar módulo de PRESUPUESTO:
3.1.2. Navegar a Presupuesto/RubradodePresupuestoo seleccionar

3.1.3. Edición: Seleccionar para poder poner en modo modif. (edición) el
presupuesto
3.1.4. Operar sobre el árbol del presupuesto y con la opción Nuevo(Insert) del menú
contextual para crear los rubros y sub-rubros (capítulos) y cargar las composiciones
del presupuesto.

Para cargar una composición -opción “es composición”- utilizar la ayuda de búsqueda: F3.
Esta ayuda nos permitirá buscar tanto por código (nombre corto) por el nombre largo, o por la
jerarquía de clasificación (carpetas).

3.1.5. Operar sobre el árbol del presupuesto y con las opciones Cortar (Ctrl+X),
Copiar (Ctrl+C) Eliminar (DEL) del menú contextual para ir ajustando la
estructura del presupuesto (Rubrado).

También se puede operar con el DRAG and DROP (arrastrar y pegar) para modificar la
estructura del Rubrado.

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 5 de 13

<!-- p. 6 -->

3.1.6. Copiar de otra obra: Seleccionar (herramientas) y luego la opción
CopiarRubrosdeotraobra, para facilitar el armado del Rubrado copiando desde
otra obra rubros, sub-rubros y composiciones.

3.2. Ajustar (particularizar) la definición de algunas composiciones
3.2.1. Para ajustar el nombre en el árbol de presupuesto posicionarse sobre la
composición y seleccionar la opción cambiar nombre del menú contextual (botón
derecho del mouse).

El sistema permite darle un nuevo nombre a la composición manteniendo el mismo código. Esto
permite que puedan convivir en un mismo Rubrado de presupuesto la misma composición con
varias inserciones y un nombre particular para cada una. Lo que si siempre es único por
composición y por obra es la definición, o sea que si se altera la definición de una de las
inserciones el cambio se actualiza en las demás.

3.2.2. Trabajando sobre la grilla definición modificar los rendimientos de los distintos
insumos (columna Cantidad). Debe estar habilitada la edición de rendimientos:
3.2.3. Insertar nuevos insumos o sub-composiciones (*), eliminar insumos o sub-
composiciones existentes utilizando las opciones (Insert) y (Del)

Estas funcionalidades operan exclusivamente sobre la grilla definición (no operan sobre la
estructura de árbol del presupuesto).

(*) Se nombran como sub-composiciones aquellas composiciones que forman parte de la
definición de otra composición. Recordar que el sistema permite “n” niveles de anidación
(inserciones múltiples libres).

La ubicación del cursor dentro de la grilla determina el nivel de inserción del elemento
seleccionado (insumo o composición). Las tabulaciones grafican los distintos niveles de
inserción.

3.2.4. Posicionándose sobre la composición en el árbol del presupuesto seleccionar de
(herramientas) la opción Comparar Composición para comparar la nueva
definición con la definición global.
Es en esta instancia cuando se resuelve si:
 se mantienen las diferencias: una definición particular para la obra y otra
global (como un estándar de referencia)
 se actualiza la definición global con la nueva definición particular.
 se restituye la definición global de la composición a la definición particular

Esta funcionalidad permite trabajar con un número más limitado de composiciones (tarjetas) ya
que se puede “particularizar” en cada obra de forma diferente una misma composición (tarjeta).
Es conveniente mantener como definición global aquella que se aproxime mas a un estándar, ya
que será siempre la referencia en la comparación.

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 6 de 13

<!-- p. 7 -->

3.3. Crear composiciones globales desde el Rubrado de presupuesto
3.3.1. Seleccionar la composición que se utilizará como base de copia
3.3.2. Posicionándose sobre la composición en el árbol del presupuesto seleccionar de
(herramientas) la opción Generar Composición Global para crear una nueva
composición.

Al generarse la copia es obligatorio definir un nuevo código y también un nuevo nombre. Se
puede cambiar la unidad. El tipo de obra y el resto de los datos de la composición se toman de la
composición copiada. Para encarpetar (clasificar) es necesario hacerlo desde Datos Básicos
editando la composición ya creada y seleccionando la ubicación elegida.

3.3.3. Sobre la grilla definición ajustar la definición para que se corresponda con la
composición que se quiere crear utilizando los procedimientos ya ejercitados en el
item 3.2.
3.3.4. Posicionándose sobre la composición en el árbol del presupuesto seleccionar de
(herramientas) la opción Comparar Composición para Comparar la nueva
definición con la definición global (que en este caso es la definición de la composición
copiada).
3.3.5. Seleccionar la opción: Redefinirenformagloballadefiniciónactualdela
Composición.

De esta forma se actualiza la base global de composiciones con la nueva definición

3.4. Ver la distintas inserciones de una composición dentro de una obra
3.4.1. Posicionándose sobre la composición en el árbol del presupuesto seleccionar de
(herramientas) la opción Dependencias de una Composición para ver las
distintas inserciones de la composición.

3.5. Ingresar volúmenes

3.5.1. Opción 1. Seleccionar de (herramientas) la opción Ingresar Cantidades
para ingresar los volúmenes de la obra.
3.5.2. Opción 2. Desde la grilla definición se puede ingresar volúmenes en la columna
Cantidad y en la fila correspondiente al cabezal de la composición. Debe estar
habilitada la edición de metrajes:

3.6. Ingresar repetidores
3.6.1. Opción 1. Parado sobre el capítulo que corresponda seleccionamos la opción
Propiedades del menú contextual (click botón derecho). En la opción Repetidor se
carga el valor de repetición.
3.6.2. Opción 2. Desde la grilla definición se puede ingresar volúmenes en la columna
Cantidad de los capítulos. Debe estar habilitada la edición de capítulos:

IMPORTANTE: Los repetidores se pueden aplicar en cualquier nivel de clasificación, la única
restricción es que se permite un sólo repetidor por rama del Rubrado. Los repetidores
multiplican los valores de los capítulos contenidos.

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 7 de 13

<!-- p. 8 -->

\4. HERRAMIENTAS DE APOYO (Rubrado de presupuesto)

4.1. Vistas (Zoom)
Dependiendo del nodo del árbol de presupuesto desde donde se esta ubicado en la grilla
definición se pueden obtener distintos niveles de visualización de la información:

 se visualizan solo los rubros hijos

 se visualizan hasta el nivel composición

 se visualizan hasta el primer nivel de definición de composiciones (sin detalle
de sub-composiciones (básicos)).

 se visualizan hasta el último nivel de definición de composiciones (con detalle
de sub-composiciones o básicos).

La vista en la grilla definición se genera automáticamente cuando en el nivel inmediato inferior
al menos hay una composición. En caso contrario la vista se genera “a demanda” cuando se

selecciona un nivel económico:

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 8 de 13

<!-- p. 9 -->

4.2. Visualizar composiciones incompletas
4.2.1. Seleccionar la opción para revisar que no falten; metrajes (volúmenes), precios
de insumos y rendimientos (cantidad del insumo dentro de una composición).

4.2.2. Se marcarán con las composiciones que estén incompletas.
4.2.3. En el caso que el proceso de revisión detecte omisiones desplazarse con el
navegador para realizar las correcciones.

4.3. Revisar el presupuesto

4.3.1. Seleccionar la opción para ir registrando las revisiones del presupuesto.
4.3.2. La revisión puede incluir un comentario (por ej: revisadoporTC13-05-06.)

4.3.3. Seleccionar la opción para visualizar los sectores del presupuesto que ya
tienen un registro de revisión.
4.3.4. En el caso que el proceso detecte sectores no revisados desplazarse con el
navegador para recorrer los sectores no revisados.

4.4. Edición rápida
4.4.1. Seleccionar la opción para ingresar valores en la grilla definición de forma rápida
(sin cálculo automático de valores)

4.4.2. Seleccionar la opción para liberar la edición rápida. Automáticamente se
ajustan los valores.

\5. PRECIOS Y MONEDAS

5.1. Precios por lista de precios

5.1.1. Navegar a Presupuestos/Listadeprecios... o seleccionar

5.1.2. Seleccionar para visualizar solo los insumos que están siendo utilizados en la
obra.
5.1.3. Ingresar la forma de pago, unidad, moneda y precio para cada insumo.

En caso de cotizar el precio en una unidad distinta a la manejada en las composiciones debe
existir una relación de equivalencia entre ambas para poder realizar la conversión.

Los precios ingresados actualizan exclusivamente los de la obra seleccionada.

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 9 de 13

<!-- p. 10 -->

5.2. Precios en grilla definición de rubrado de presupuesto

5.2.1. Navegar a Presupuesto/RubradodePresupuestoo seleccionar
5.2.2. Trabajando sobre la grilla definición modificar los precios de los distintos insumos
(columna unitarios $). Debe estar habilitada la edición de precios:

5.3. Cotizaciones

5.3.1. Navegar a Presupuestos/Monedas... o seleccionar
5.3.2. Ingresar las cotizaciones correspondientes.

Estas cotizaciones afectan sólo la obra seleccionada

\6. COSTOS INDIRECTOS

6.1. Definición (cálculo) de costos indirectos

6.1.1. Navegar a Presupuestos / Costos indirectos... o seleccionar , opción
“Definición”.
6.1.2. Seleccionar el criterio para la definición de los costos indirectos:
 Monto fijo (definido por el usuario)
 Por tipo de insumo
 Por presupuesto; valor rama “costos indirectos” del rubrado de presupuesto

Cuando se definen por tipo de insumo se pueden definir como un % o monto asociado a cada
tipo, o uno general para toda la obra.

La rama “costos indirectos” del rubrado de presupuesto solo va a ser considerada en nivel XY
(costos) y nivel XYZ (precio) cuando se tome la última opción.

6.2. Distribución (prorrateo) de costos indirectos

6.2.1. Navegar a Presupuestos / Costos indirectos... o seleccionar , opción
“Distribución”.
6.2.2. Seleccionar el criterio para la distribución de los costos indirectos:
 Por tipo de insumo
 Por rubros

6.2.3. Marcar ( ) en la casilla “Cálculoautomático”cuales van a ser los rubros que
se calcularán de forma automática y cuales no. Para marcar todos juntos seleccionar

6.2.4. Una vez modificados los valores (% o $) en la grilla (celdas fondo amarillo)
seleccionar para realizar el cálculo

La distribución es independiente de la forma en que se calcularon los costos indirectos

Se pueden modificar libremente todos los % o montos asignados a cada rubro o tarea, en tanto
no se supere el monto total de costos indirectos. De todas formas y en cualquiera de los dos
Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 10 de 13

<!-- p. 11 -->

opciones de distribución siempre debe haber por lo menos una tarea que se calcule de forma
automática.

\7. UTILIDADES

7.1. Definición (cálculo) y prorrateo de utilidades

7.1.1. Navegar a Presupuestos/Utilidades... o seleccionar

7.1.2. Marcar ( ) en la casilla “Incluirenprorrateo” los rubros que se incluirán en
el prorrateo de los beneficios.
7.1.3. Modificar los valores en la grilla (celdas fondo amarillo), el sistema prorrateará
automáticamente en los rubros “hijos” marcados con los valores (% o $) ingresados.

En el caso de las utilidades la definición y distribución se realizan simultáneamente.

El nivel de aplicación depende del lugar donde se modifiquen los valores. Si me posiciono sobre
la línea “presupuesto” se estarán modificando todo los rubros contenidos (en este caso todo el
presupuesto) que tengan la marca .

\8. IMPUESTOS

8.1. Selección de impuestos

8.1.1. Navegar a Presupuestos/Impuestos... o seleccionar

8.1.2. Seleccionar para seleccionar un nuevo impuesto, editar o eliminar
uno existente respectivamente.
8.1.3. Seleccionar de los impuestos disponibles los que se van a aplicar y el % aplicado

El % no necesariamente debe coincidir con el definido globalmente para el insumo. Se puede
aplicar más de un impuesto, pero no se pueden definir acumulativos, es decir impuesto aplicado
sobre impuesto, siempre se calculan sobre la base.

8.2. Forma de aplicación y forma de cálculo
8.2.1. Definir si integra o no costos.
 En el caso que no se integre se aplicara globalmente al final del presupuesto.
 En el caso que si se integre se incluirán dentro del costo de la tarea y se habilita
opciones de cálculo
8.2.2. Definir forma de cálculo (opción integra costos)
 Globalmente
 Por tipo de insumo u insumo

Para seleccionar por insumo en la opción “aplica” seleccionar: (por insumo). Esto permitirá
discriminar insumo por insumo los % e impuestos aplicados.

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 11 de 13

<!-- p. 12 -->

\9. LEYES SOCIALES

9.1. Selección de definición para una obra

9.1.1. Navegar a Presupuestos/LeyesSociales... o seleccionar

9.1.2. Seleccionar para seleccionar una nueva definición de leyes sociales,
editar o eliminar una existente respectivamente.
9.1.3. Seleccionar la obra

9.2. Forma de aplicación y forma de cálculo
9.2.1. Definir si las leyes sociales se van a integrar o no al presupuesto.

En los dos casos (si integra o no el costo) el sistema calculará el valor de las leyes sociales, la
diferencia es que cuando estas se integran se suman al costo de los distintos rubros
presupuestados, en caso contrario sólo se informa el valor.

9.2.2. Seleccionar la opción de cálculo:
 Discriminado por rubro: % asociado a cada rubro
 Discriminado por tipo insumo: % asociado a cada insumo
9.2.3. Opción “Discriminado por insumo”: Seleccionar con los tipos de insumos que
involucran insumos con cálculo de leyes sociales. Definir luego para los insumos que
correspondan los % a aplicar en cada caso.

¿MONTO IMPONIBLE u APORTE? : Al definir los % el usuario le estará “diciendo”
indirectamente al sistema qué es lo que va calcular; si el “Monto Imponible” o el “Aporte” (o
sea, valores aportados a BPS). Está claro que en el caso de integrar a costo estos % deberían
corresponder al Aporte, ya que no es correcto integrar Monto Imponible en el precio.

LEYES SOCIALES DE COSTOS INDIRECTOS: Tanto en el caso que los Costo Indirectos se
calculen por tipo de insumo o por presupuesto de Costos Indirectos (ver 6.1) el sistema calculará
e informará por separado las Leyes Sociales de Costos Directos y las de Costos Indirectos, no
obstante cuando se integran a Costo estas últimas (leyes sociales de Costos Indirectos) no se
considerarán dentro del mismo.

\10. PORCENTAJES VARIOS

Los porcentajes varios se suman al final de cálculo, luego de la utilidades y antes de los
impuestos (cuando no están integrados al costo).. Se aplican globalmente para todo el
presupuesto.

10.1.1. Navegar a Presupuestos/Porcentajesvarios... o seleccionar .

10.1.2. Seleccionar para agregar un nuevo porcentaje o eliminar uno existente
respectivamente. La edición se realiza sobre la grilla.
10.1.3. Completar los datos requeridos:concepto;%;¿incluyeanterior?

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 12 de 13

<!-- p. 13 -->

El concepto ¿incluye anterior? condiciona el cálculo. Se calculará sobre el subtotal inmediato
anterior en la opción “si”, o sobre la base (subtotal antes de aplicar ningún %) en la opción
“no”.

10.1.4. Seleccionar para modificar el orden de aplicación.

Guía Módulo de Presupuestos SP 3.0 G2 -Pág. 13 de 13
