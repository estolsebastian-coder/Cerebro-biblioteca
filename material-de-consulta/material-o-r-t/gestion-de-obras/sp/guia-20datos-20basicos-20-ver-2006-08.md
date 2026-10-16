---
type: libro
title: "GUIA%20DATOS%20BASICOS%20_ver%2006-08"
author: "Ana Laura"
categoria: "MATERIAL O.R.T"
paginas: 7
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/MATERIAL O.R.T/gestion de obras/sp/GUIA%20DATOS%20BASICOS%20_ver%2006-08.pdf"
convertido: 2026-10-16
---

# GUIA%20DATOS%20BASICOS%20_ver%2006-08

> Texto extraído de `MATERIAL O.R.T\gestion de obras\sp\GUIA%20DATOS%20BASICOS%20_ver%2006-08.pdf` (7 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



Datos
SP 3.0
Básicos

Versión3.14.001
06/2008

<!-- p. 2 -->

Contenido
\1. CREAR, MODIFICAR Y ELIMINAR DATOS BÁSICOS I: .................................................................. 3
1.1. Crear un nuevo Dato Básico ................................................................................................... 3
1.2. Eliminar un Dato Básico ......................................................................................................... 3
1.3. Editar un Dato Básico ........................................................................................................... 3
\2. DATOS BÁSICOS I:................................................................................................................... 3
2.1. MONEDAS ............................................................................................................................ 3
2.2. INDICES............................................................................................................................... 4
2.3. PORCENTAJES E IMPUESTOS................................................................................................. 4
2.4. TIPOS DE INSUMOS .............................................................................................................. 4
2.5. TIPOS DE OBRA.................................................................................................................... 4
2.6. UNIDADES – DEFINICIÓN/EQUIVALENCIA .............................................................................. 4
\3. DATOS BÁSICOS II: INSUMOS................................................................................................... 5
3.1. Crear insumos partiendo de un registro vacío ......................................................................... 5
3.2. Crear insumos partiendo de la copia uno existente................................................................... 5
3.3. Crear nueva carpeta en la jerarquía de Insumos ...................................................................... 5
3.4. PRECIOS DE REFERENCIA...................................................................................................... 6
\4. DATOS BÁSICOS II – COMPOSICIONES...................................................................................... 6
4.1. Crear composiciones partiendo de un registro vacío ................................................................. 6
4.2. Crear composiciones partiendo de la copia una existente.......................................................... 7
4.3. Crear nueva carpeta en la jerarquía de Composiciones ............................................................. 7

Guía de Datos Básicos de SP 3.0 G2 -Pág. 2 de 7

<!-- p. 3 -->

\1. CREAR, MODIFICAR Y ELIMINAR DATOS BÁSICOS I:

MONEDAS /INDICES /PORCENTAJES E IMPUESTOS /TIPOS DE INSUMO /TIPOS DE OBRA /UNIDADES

Agregar
1.1. Crear un nuevo Dato Básico
Eliminar
1.1.1. Navegar a datos básicos/xx.

1.1.2. Agregar un registro vacío (ins).
1.1.3. Completar los datos

1.2. Eliminar un Dato Básico
1.2.1. Navegar a datosbásicos/xx
1.2.2. Seleccionar de la lista el registro a eliminar.
1.2.3. Presionar el botón borrar (del). Menú contextual
(botón derecho mouse)

1.3. Editar un Dato Básico
1.3.1. Navegar a datosbásicos/xx
1.3.2. Editar los datos que pueden ser editados (los que tiene fondo blanco)
posicionándose en la celda correspondiente y modificando el valor

Enelcasoqueunregistrodelosdatosbásicosestésiendoutilizadoenalgunapartedel
sistema, no será posible su eliminación para preservar la integridad de la base de
datos.

\2. DATOS BÁSICOS I:

2.1. MONEDAS
2.1.1. Navegar a datosbásicos/monedas

Aquísedefinenlasmonedasautilizarenelsistema.

Las cotizaciones son globales y sólo a manera de referencia. Las cotizaciones que se
consideraránparacadaobrasetomarándelatablademonedasdecadaobra(verG2-
MóduloPresupuesto/Cotizaciones).

Guía de Datos Básicos de SP 3.0 G2 -Pág. 3 de 7

<!-- p. 4 -->

2.2. INDICES
2.2.1. Navegar a datosbásicos/índices

Se pueden crear “índices” para poder agregar como un parámetro más cuando se
definen fórmulas para establecer: precios de insumos, cantidad de un insumo en una
composición(rendimiento),cantidaddeunacomposiciónenunaobra(metraje).Estos
índices se utilizan para tomar como referencia en un sólo parámetro valores que
utilizaremosfrecuentemente.Estosíndicestienenunvalorúnicoporobra.

Losvaloressonglobalesysóloamaneradereferencia.Losvaloresqueseconsiderarán
paracadaobrasetomarándelatabladecadaobra.

2.3. PORCENTAJES E IMPUESTOS
2.3.1. Navegar a datosbásicos/porcentajeseimpuestos

Impuestosy/oporcentajesqueseutilizaránenlospresupuestosy/ocertificadosde
obra.

Los % son globales y sólo a manera de referencia. Las % que se considerarán para
cadaobrasetomarándeladefinicióndeimpuestosdecadaobra.(verguíaG2-Módulo
Presupuesto/Impuestos).

2.4. TIPOS DE INSUMOS
2.4.1. Navegar a datosbásicos/tiposdeinsumos

Es la clasificación primaria y obligatoria de todos los insumos del sistema. Esta
clasificación permite clasificar la información que brinda el sistema en los distintos
módulosenestosgrupos.Laclasificacióntradicionalnormalmenteutilizadaes: Mano
deObra/Materiales/Subcontratos/Servicios/Equipos.

2.5. TIPOS DE OBRA
2.5.1. Navegar a datosbásicos/tiposdeobra

Tipodeobra:eltipodeobraesunfiltroparaclasificarlascomposicionesdelsistema.
Se aconseja definir más de un tipo de obra cuando la empresa maneje diferentes
rubroseintencionalmentesequieramantenerinformaciónreservadaparacadatipo.

2.6. UNIDADES – DEFINICIÓN/EQUIVALENCIA
2.6.1. Navegar a datosbásicos/unidades.

Unidadesqueutilizaelsistemaparainsumosycomposiciones.

Elcampo“esdetiempo?”sirveparaidentificarlasunidadesdetiempoparaprocesos
posterioresdelsistemacomolaplanificación.

Sedefinenequivalenciasentredistintasunidadesparapoderexpresarelpreciodeun
insumo en una unidad distinta al que se definió en el sistema. Ejemplo: se puede
expresarelpreciodelcementoporbolsaaúncuandoelinsumosedefinióenelsistema
porkg. Sedebeenestecasodefinirlaequivalencia:1bolsadecemento =50kg.

Guía de Datos Básicos de SP 3.0 G2 -Pág. 4 de 7

<!-- p. 5 -->

Lasequivalenciaspuedensergenéricaso“universales”,esdecirunarelaciónválida
paratodoslosinsumos(porej:1000kg=1ton)oparticularporinsumo(aplicaejemplo
cemento).

\3. DATOS BÁSICOS II: INSUMOS

Losinsumossonloselementosbásicosdelsistemadepresupuestación.Parapoderser
consideradasenelrubradodeunaobradeberánestarnecesariamenteasociadosauna
composición.

3.1. Crear insumos partiendo de un registro vacío
3.1.1. Navegar a datos básicos/insumos (Ctrl+M).
3.1.2. Agregar un registro vacío (Insert).
3.1.3. Completar los datos del cabezal: insumos (código) / nombre / tipo de insumo /
notas /carpeta.
3.1.4. Cargar los datos de definición del precio del insumo. Se agregará un registro por
cada forma de pago que se quiera considerar, definiendo: forma de pago, unidad,
moneda y precio.

Los precios ingresados en esta interfase se guardarán en la lista global de precios
(preciosdereferencia).

3.2. Crear insumos partiendo de la copia de uno existente
3.2.1. Navegar a datosbásicos/insumos(Ctrl+M).
3.2.2. Seleccionar de la lista desplegada el insumo que se tomará como base de copia.
3.2.3. Copiar el insumo y su definición:
3.2.4. Pegar el insumo y su definición:
3.2.5. Actualizar los datos del cabezal; insumos(código)/nombre/tipodeinsumo/
notas/carpeta.

Código(nombrecortodelinsumo):recordarqueloscódigossonúnicos.Entantonose
modifiqueelquesetomócomocopiaelsistemaadvierte:“elinsumoyaexiste”.

3.2.6. Actualizar los datos de definición del precio del insumo. Se agregará un registro
por cada forma de pago que se quiera considerar, definiendo: forma de pago,
unidad, moneda y precio.

3.3. Crear nueva carpeta en la jerarquía de Insumos

LasJerarquíadeInsumos(o“Carpetas)esunaestructuradeclasificacióntipo“árbol”
delosmismos.Estotalmenteconfigurableporelusuarioypermitebúsquedasmás
ordenadas.

Guía de Datos Básicos de SP 3.0 G2 -Pág. 5 de 7

<!-- p. 6 -->

3.3.1. Navegar a datosbásicos/insumos(Ctrl+M)

3.3.2. Ingresar a la definición de jerarquías
3.3.3. Ubicarse en el lugar donde queremos ingresar la nueva carpeta de clasificación.
3.3.4. Agregar una nueva carpeta , ingresando el nombre que corresponda.

En el caso que la carpeta quede mal ubicada dentro del “árbol” de clasificación, se
puedecortarypegarenlanuevaubicación(funcionesasociadasalbotónderechodel
mouse).Estemovimientoarrastratodoelcontenidodelacarpetaalanuevaubicación.
Elnombretambiénsepuedeeditar(dobleclick)ymodificarencualquiermomento.

3.4. PRECIOS DE REFERENCIA
3.4.1. Navegar a datosbásicos/preciosdereferencia

Lospreciosdereferenciassonlosprecios“globales”delsistema.Registralosvalores
dadosalosinsumosdelsistemacuandoseledioelaltaypermiteeditarymodificarlos.

Estos precios son considerados para una obra particular cuando al crearla se toma la
opción: origen de precios / global (ver G2 Guía de Presupuesto / Crear obra). El
sistema copia por única vez los precios al crear la obra, a partir de allí el ajuste de
preciosserealizadentrodelMóduloPresupuestoydentrodelaobra.

\4. DATOS BÁSICOS II – COMPOSICIONES

Las composiciones son la unidad mínima de costo dentro del rubrado de
presupuestacióndeunaobra(análisisdecostounitario).Estádefinidaporinsumosy/o
sub-composiciones (composiciones dentro de otra composición). Debe contener al
menos uno de estos elementos en su definición. Cada elemento se agrega a la
definiciónconunacantidad(consumoorendimiento)asociada.

Las cantidades (metrajes) de cada composición se definen asociadas a una obra en
particulary enelrubradodepresupuesto(VERG2:MóduloPresupuesto).

LadefinicióndecomposicionesenDatosBásicosesladefinición“global” oestándarde
la misma. La definición se puede modificar y/o ajustar dentro de cada obra en
particular(VERG2:MóduloPresupuesto)sinmodificaresteestándar.

4.1. Crear composiciones partiendo de un registro vacío
4.1.1. Navegar a datosbásicos/composiciones(Ctrl+t)
4.1.2. Agregar un registro vacío (Insert)
4.1.3. Completar los datos del cabezal: composición (código) / nombre / descripción /
tipo de obra / unidad /carpeta.

Tipo de obra: el tipo de obra es un filtro que asocia lasdistintas composiciones a los
distintostiposdeobrasdefinidos.Sisedefinecomogenérica(Gen)sepodrácompartir
desdetodoslostiposdeobras.
Guía de Datos Básicos de SP 3.0 G2 -Pág. 6 de 7

<!-- p. 7 -->

4.1.4. Cargar los datos de definición de la composición. Se agregarán insumos o
subcomposiciones con sus respectivos datos: tipo (insumo/composición) / tipo /
código /cantidad (rendimiento).

Paraseleccionaruninsumoacomposición(insumo/composición)utilizarlaayudade
búsqueda: F3.Estaayudanospermitirábuscartantoporcódigo(nombrecorto)porel
nombrelargo,oporlajerarquíadeclasificación(carpetas).

4.2. Crear composiciones partiendo de la copia de una existente
4.2.1. Navegar a datosbásicos/composiciones(Ctrl+t)
4.2.2. Seleccionar de la lista desplegada la composición que se tomará como base de
copia.
4.2.3. Copiar la composición y sus insumos:
4.2.4. Pegar la composición y sus insumos
4.2.5. Actualizar los datos del cabezal: composición (código) / nombre / descripción /
tipo de obra / unidad /carpeta

Código (nombre corto de la composición): recordar que los códigos son únicos. En
tantonosemodifiqueelquesetomocomocopiaelsistemaadvierte:“lacomposición
yaexiste”.

4.2.6. Actualizar los datos de definición de la composición. Se agregarán los insumos o
sub-composiciones que estén faltando, se eliminarán los insumos o sub-
composiciones que no se utilicen, se ajustarán los rendimientos de aquellos que
correspondan.

4.3. Crear nueva carpeta en la jerarquía de Composiciones

LasJerarquíadeComposiciones(o“Carpetas)esunaestructuradeclasificacióntipo
“árbol”delasmismas.Estotalmenteconfigurableporelusuarioypermitebúsquedas
másordenadas.

4.3.1. Navegar a datosbásicos/composiciones(Ctrl+t)

4.3.2. Ingresar a la definición de jerarquías
4.3.3. Ubicarse en el lugar donde queremos ingresar la nueva carpeta de clasificación.
4.3.4. Agregar una nueva carpeta , ingresando el nombre que corresponda.

En el caso que la carpeta quede mal ubicada dentro del “árbol” de clasificación, se
puedecortarypegarenlanuevaubicación(funcionesasociadasalbotónderechodel
mouse).Estemovimientoarrastratodoelcontenidodelacarpetaalanuevaubicación.
Elnombretambiénsepuedeeditar(dobleclick)ymodificarencualquiermomento.

Guía de Datos Básicos de SP 3.0 G2 -Pág. 7 de 7
