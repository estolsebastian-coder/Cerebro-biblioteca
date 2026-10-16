---
type: libro
title: "método de control"
author: "ebrenner"
categoria: "MATERIAL O.R.T"
paginas: 8
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/MATERIAL O.R.T/gestion de obras/Metodo de Control.pdf"
convertido: 2026-10-16
---

# método de control

> Texto extraído de `MATERIAL O.R.T\gestion de obras\Metodo de Control.pdf` (8 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Técnicas Informáticas para la Gestión de Obra

Ing. Ernesto Brenner

Método de Control de Obras

Introducción
Cualquier Método de Control se basa en la comparación de Previstos contra Reales. Si no existen
Previstos o no existen Reales, no es posible el Control. Por otro lado hay que notar que no es
suficiente controlar solamente porcentajes de Obra (Previstos contra Reales) En este caso
podríamos llegar al 100% de la Obra pero podría haber costado un 120% del costo previsto.
Tampoco es posible controlar solamente dinero. En este caso podríamos llegar a gastar el 100%
del dinero que pensábamos gastar pero haber ejecutado solamente un 80% de la obra.
La única forma de controlar un proyecto es llevar simultáneamente el avance de tres variables.
• Porcentajes
• Pesos
• Cantidades.

De esta forma se definen tres curvas en las cuales para un momento determinado del tiempo
quedan determinados tres puntos. Si hasta ese momento se ejecutó el 80% de la obra, se utilizó el
80% del dinero y se utilizaron el 80% de los materiales, podríamos decir que es una obra sana.
Pero si por ejemplo, hasta el momento se ejecutó el 80% de la obra, se gastó el 90% del dinero y
se utilizaron el 70% de las cantidades, es una obra con problemas. Para este último caso, se puede
concluir que fueron sobrestimados los rendimientos y se compró mucho más caro de lo que se
pensaba.
Este es un concepto muy fácil de entender pero no es del todo práctico en el momento de la
implementación. Solo pusimos el ejemplo a los efectos de mostrar que se necesitan controlar varias
variables simultáneamente. Más adelante se explicará el método a ser implementado.
Ya vimos la necesidad de generar dos Presupuestos por cada Proyecto. Uno Costo y Uno Venta. Si
bien este Presupuesto Venta se hace partiendo del Presupuesto Costo, generalmente en la etapa
de la generación de la Oferta se lo deforma tanto que muchas veces sería difícil encontrar una
relación entre ambos.
Posiblemente se hayan subido precios de Materiales, seguramente la Mano de Obra estará 100%
en blanco, se habrán cambiado rendimientos de Mano de Obra y Equipos, se habrá incrementado
la incidencia porcentual de los primeros ítems de obra para poder tener un desahogo financiero en
los primeros meses de Obra, se habrá tomado un valor de amortización de equipos no del todo
real, se habrán cargado Costos Financieros, Beneficios. etc. O sea..., se ha generado “Una Gran
Mentira”.
Es por ello que a los efectos de controlar no lo vamos a hacer contra este Presupuesto Venta. De
nada serviría obtener los Costos Reales, “Una Gran Verdad”, y compararlos contra esta “Gran
Mentira”. La diferencia (resta) entre una Verdad y una Mentira es inevitablemente otra “Mentira” que
obviamente solo serviría para engañarnos.
Cuando controlamos debemos comparar los Costos Previstos contra los Costos Reales para
encontrar los desvíos. O sea, lo que nosotros pensábamos que deberíamos haber gastado contra
lo que realmente se gastó (en porcentajes, pesos y cantidades).
Es necesario entender que es imperioso implementar una metodología de control muy pensada.
Como hemos visto, son tantos los conceptos, y están tan lejos de cualquier acercamiento intuitivo
que hagamos que es imposible que se logre un control aceptable sin querer.

Página 1 de 8 Agosto 2008

<!-- p. 2 -->

Técnicas Informáticas para la Gestión de Obra

Ing. Ernesto Brenner

Desvíos y Análisis de Desvíos
En un proyecto cualquiera, los desvíos pueden provenir solamente de tres lugares diferentes.
• Desvíos debidos a Precios:
Los precios reales de compra pueden ser más caros o más baratos que los presupuestados.
• Desvíos debidos a Rendimientos:
Es posible que las cantidades de Materiales, Mano de Obra o Equipos que se estén utilizando
realmente sean mayores o menores que las estimadas en el presupuesto.
• Desvíos debidos a variaciones de Volúmenes:
Es posible que en un mes determinado se construya más o menos de lo previsto
Antes de comenzar un mes determinado se tiene una estimación de lo que debería suceder ese
mes. A dicha estimación la llamaremos Presupuesto Previsto. Sus hipótesis son Precios,
Rendimientos y Volúmenes Previstos.
Al finalizar el mes las cosas pueden no haber sido como se previeron en su momento. Se tienen los
Precios, Rendimientos y Volúmenes Reales.
Desvios\Presupuesto Previsto Real
Precios Previsto Real
Rendimientos Previsto Real
Volúmenes Previsto Real

Generalmente se cree que si se obtiene la diferencia en pesos entre el Presupuesto Previsto y el
Real el problema del Control y los desvíos queda solucionado. (recordemos que estamos hablando
de Presupuestos Costo).
Pero no es así. Supongamos que el volumen previsto era originalmente de un 10% y que para ese
volumen, el Presupuesto Previsto era de $100.-. Al terminar el mes, la medición de obra muestra
que se ejecutó solo un 8% en lugar del 10% previsto. Según esto se deberían haber gastado $80.-
correspondientes a la parte proporcional de los $100.- previstos. Supongamos, además, que
durante ese mes se compro caro y que esto hizo que en lugar de $80.- se hayan gastado $90.-. Y
supongamos por último que los rendimientos de materiales y mano de obra previstos no se hayan
cumplido a rajatablas por lo que en lugar de $90.- se hayan terminado gastando $100.-
La información que le llegaría a un gerente sería que se deberían haber gastado $100.- y en la
realidad se han gastado $100.-. Sin embargo todo anduvo mal. Se ejecutó menos de lo que se
pensaba, se compró caro y se utilizaron más recursos de los previstos.
Esto se debe a que dentro de estas tres variables que producen desvíos (Precios, Rendimientos y
Volúmenes) hay algunas más importantes que otras.
Supongamos que entre el Presupuesto Previsto y el Real insertamos un presupuesto llamado
Presupuesto Flexible con Precios y Rendimientos Previstos pero con Volumen Real.
Desvios\Presupuesto Previsto Flexible Real
Precios Previsto Previsto Real
Rendimientos Previsto Previsto Real
Volúmenes Previsto Real Real

Es fácil notar que la diferencia en $ (pesos) entre el Previsto y el Flexible sería la desviación debida
únicamente a los Volúmenes y que la diferencia en $ (pesos) entre el Flexible y el Real sería la
desviación debida a Precios más Rendimientos. Obviamente estas dos desviaciones podrían tener
igual signo o signos contrarios.

Página 2 de 8 Agosto 2008

<!-- p. 3 -->

Técnicas Informáticas para la Gestión de Obra

Ing. Ernesto Brenner

El tema es que un atraso en los volúmenes no siempre es una pérdida, o mejor dicho, un atraso en
los volúmenes previstos podría implicar multas o costos financieros pero no una pérdida igual al
100% de dicho atraso. Quizás se puedan justificar los atrasos con el comitente por problemas
climáticos o lograr la devolución de las multas cuando se vuelva a recuperar el ritmo de Obra. En
cambio, si se compra mas caro o si los rendimientos son más bajos, esa diferencia se pierde en un
100% y definitivamente.
En el análisis que hacía el gerente entre los $100.- previstos y los $100.- reales, la variable
Volumen (que no es tan importante), estaba nublando u ocultando la parte realmente interesante
del problema.
Pero es posible avanzar aún más en el tema. Supongamos ahora que entre el presupuesto Flexible
y el Real insertamos otro llamado Presupuesto Revisado con Precios y Volúmenes Reales y
solamente Rendimientos Previstos.
Desvios\Presupuesto Previsto Flexible Revisado Real
Precios Previsto Previsto Real Real
Rendimientos Previsto Previsto Previsto Real
Volúmenes Previsto Real Real Real

El Flexible difiere del Revisado solamente en los Precios por lo que el desvío en $ (pesos) sería el
dinero ganado o perdido en dicho mes gracias o por culpa de quien sea el responsable de las
Compras. Por otro lado, el Revisado difiere del Real solamente en los Rendimientos por lo que la
diferencia en $ (pesos) sería el dinero ganado o perdido gracias o por culpa de quien sea
responsable del tema, generalmente la Dirección de Obras.
Aparecen entonces dos actores muy importantes, Compras y la Dirección de Obra como centros de
responsabilidad. Cuán distintas serían ahora las cosas si se le entrega al gerente la información de
la siguiente forma.
Sr. Gerente:
Este mes nos hemos atrasado un 10% respecto a los volúmenes previstos.
Independientemente de ello, se han perdido $5.- por desviaciones en los rendimientos por
responsabilidad de la Dirección de Obra, y $5.- por culpa de oficina de compras que no logró
los precios presupuestados.
Estaba previsto un gasto de (-$100) que más los $10 que no se debieron haber por la merma
en el volumen daría (-$90). A esto habría que restarle los $5 que se perdieron por
rendimientos y los $5 que se perdieron por precios con lo que volvería a dar (-$100)
Total Previsto (-$100)
Volúmenes $10
Precios (-$5)
Rendimientos (-$5)
Total Real (-$100)

(*) Negativo Gasto, Positivo Beneficio
Si se hubieran analizado solamente los totales se hubiera llegado a la conclusión de que la obra
andaba a la perfección pero en realidad se han perdido $10
Es importante que, además de una análisis detallado de lo sucedido se definan las
responsabilidades. No solamente no es posible que no sepamos si ganamos o perdimos, sino que
tampoco es posible que no sepamos gracias o por culpa de quien o por lo menos de que Proceso.
Los resultados deben ser medibles y deben haber responsables. Estas son dos reglas básicas de la
“Calidad” como concepto genérico. Es la única forma de generar un feedback para que los

Página 3 de 8 Agosto 2008

<!-- p. 4 -->

Técnicas Informáticas para la Gestión de Obra

Ing. Ernesto Brenner

procesos se vayan puliendo y mejorando. Sin esta información un gerente está disparando en la
oscuridad o rezando que nada suceda.

Implementación
Ahora veremos como pueden llevarse a la práctica estos conceptos.
En el cuadro se quiere esquematizar un diagrama de GANTT en el cuan están especificados para
cada mes los porcentajes de avance previstos y reales para cada tarea. Se supone que para el
ejemplo estamos a principios del Mes 3 por lo cual solo existen mediciones de los valores Reales
de ejecución para los Meses 1 y 2.
TAREA Mes 1 Mes 2 Mes 3 Mes 4
Hormigón P5% P10% P5% P5%
R5% R8%
Mampostería
Pintura

P Porcentaje de Avance Previsto de la Tarea
R Porcentaje de Avance Real de la Tarea

La idea es tratar de hacer un control y un seguimiento de lo ocurrido en el mes que acaba de
terminar. Solucionado este tema y extendiéndolo a toda la Obra, tendríamos el problema
solucionado.
Porcentaje de Avance Cantidad de Bolsas de Cemento Listado
Previsto 10% 10 para el Avance Previsto Listado 10
Real 8% 8 para el Avance Real Listado 8
11 Suma de Remitos del Mes Listado 11
7 Bolsas realmente utilizadas en el Mes Listado 7

Este podría ser un cuadro con información sobre la Obra para el Mes 2 y se leería de la siguiente
forma:
• Renglón 1: En el momento que se hizo el Plan de Trabajos se suponía que se iba a hacer un
10% de Obra lo que según los rendimientos estimados en aquel momento se hubieran
necesitado 10 bolsas de cemento.
• Renglón 2: Terminado el Mes 2 se verificó que en realidad se había ejecutado solo un 8% de
Obra en lugar del 10% previsto, lo que según los rendimientos previstos originalmente se
hubieran necesitado 8 bolsas de cemento
• Renglón 3: La suma de los remitos de las bolsas de cemento llegadas a obra en dicho mes dio
11 bolsas de cemento
• Renglón 4: La cantidad de bolsas utilizadas realmente durante el Mes 2 para ejecutar el
porcentaje de obra real (8%) fue 7 bolsas de cemento.
Cada uno de los números que están en la columna de la derecha y que simplificamos en el ejemplo
diciendo que son bolsas de cemento, en realidad no son solo un número sino que cada uno de ellos
es un listado. De ahora en más nos referiremos a ellos como Listado 10, Listado 8, Listado 11,
Listado 7, respectivamente.
Por ejemplo: El número 7, o mejor dicho el Listado 7, es un listado con todos los insumos que se
consumieron realmente durante el Mes 2 para poder ejecutar el porcentaje de obra Real (8%).
Con estos datos se deberán sacar por un lado, conclusiones a nivel gerencial sobre el estado y el
avance de la obra, y por el otro, se deberá extraer la información técnica para el control en Obra.
Como se puede ver no queda demasiado claro a simple vista si fue un buen mes o no, pero es
importante que nos pongamos de acuerdo acerca de la interpretación de estos números para llegar

Página 4 de 8 Agosto 2008

<!-- p. 5 -->

Técnicas Informáticas para la Gestión de Obra

Ing. Ernesto Brenner

a un diagnóstico común. Si nos ponemos en el lugar del contratista que está ejecutando la Obra,
una posible lectura de dicha información sería la siguiente:
El Comitente de esta obra no debe estar demasiado contento debido a que hubo un atraso en el
ritmo de obra. Se pensaba ejecutar un 10% y solo se ejecutó un 8%. Sin embargo en el momento
de la Presupuestación se pensaba que para ese construir ese 8% se iban a necesitar 8 bolsas de
cemento y en la realidad se están utilizando solamente 7. Esto quiere decir, que de seguir así las
cosas, además del Beneficio que nuestra Empresa pensaba obtener, estamos ahorrando una bolsa
de cemento por cada 8% de obra que construimos.
El problema del atraso no es un problema tan grave porque generalmente no implica una pérdida.
El atraso podría haber sido por con problemas climáticos y en el peor de los casos quizás nos
apliquen una multa y podremos negociar la devolución de dicha multa si volvemos a ritmo.
Las Empresas generalmente Controlan mal porque comparan el Listado 10 contra el Listado 11. El
Listado 10 lo utilizan porque es el único que pueden obtener debido a que generalmente disponen
de un único Gantt, el de Contrato. Y el Listado 11 porque es fácil de obtener debido a que se lo
piden a Area Administrativa. Pero esta comparación sería incorrecta. Si se compara el 10 contra
11 se llegaría a la conclusión de que se está perdiendo una bolsa de cemento sin embargo
comparando el 8 contra el 7 se concluye que se está ganando una bolsa de cemento y esto es lo
real.
Hacer un Control de Costos es comparar un Previsto contra un Real, pero no cualquier Previsto
contra cualquier Real, sino un muy cierto y determinado Previsto contra un muy cierto y
determinado Real. El problema es que obtener en una Obra el Listado 8 y el Listado 7 es mucho
más laborioso que obtener el Listado 10 y el 11, pero no se pueden sustituir. No es posible que
lleguemos a distintas conclusiones dependiendo de que set de listados comparemos. Obviamente
hay algo que no está bien.
La idea es tratar de llegar a una conclusión sobre qué se debe comparar con qué, debatir hasta
llegar a una conclusión y de ahí en más implementar la metodología diseñada sin tener que volver a
replantear el tema en cada Obra. Todas las Industrias tienen la misma problemática y todas llegan
a la conclusión de que la única forma de Controlar es encontrar los Listados 8 y 7 y que de no ser
posible encontrarlos es preferible no controlar antes que tomar los listados 10 y 11. Controlar los
listados 10 y 11 es como estar midiendo la otra Obra.
Inclusive en esta Obra el problema no es tan grave porque de haber controlado mal hubiéramos
pensado que las cosas no funcionaban y luego la realidad nos hubiera dado una grata sorpresa,
pero miremos el siguiente ejemplo.
TAREA Mes 1 Mes 2 Mes 3 Mes 4
Hormigón P5% P8% P5% P5%
R5% R10%
Mampostería
Pintura

Porcentaje de Avance Cantidad de Bolsas de Cemento
Previsto 8% 8 para el Avance Previsto
Real 10% 10 para el Avance Real
7 Suma de Remitos del Mes
11 Bolsas realmente utilizadas en el Mes

En este ejemplo se invirtieron todos los problemas. Se pensaba originalmente que se iba a ejecutar
un 8% pero la obra se aceleró y se terminó haciendo un 10% con lo que nuestro Comitente está

Página 5 de 8 Agosto 2008

<!-- p. 6 -->

Técnicas Informáticas para la Gestión de Obra

Ing. Ernesto Brenner

realmente contento. Si controláramos mal (en este caso el 8 contra el 7) pensaríamos que la Obra
anda sobre ruedas y nos iríamos a festejar con el Comitente pues para ambos la Obra avanza
rápidamente y además estamos gastando menos de lo previsto.
Sin embargo tarde o temprano la cruel realidad se hará presente indefectiblemente pues la obra
nunca anduvo bien. Comparando el 10 contra el 11 nos hubiéramos dado cuenta que se estaba
perdiendo dinero.
SI ya estamos convencidos de que tenemos que hacer, solo queda encontrar los listados 7 y 8
con lo cual el problema del Control queda absolutamente solucionado. Y es realmente así.

Obtención del Previsto (Listado 8 del primer ejemplo)
Para obtener el listado 8, una vez terminado el mes en cuestión, es necesario ingresar en el Gantt
el porcentaje realmente ejecutado de cada tarea y obtener la Explosión de Insumos para dicho
mes. Recordemos que una Explosión de Insumos Mensual es la desagregación en sus insumos
más simples de las cantidades o porcentajes que figuran en dicho Gantt según los Rendimientos y
Precios previstos en el momento de la presupuestación.
Esta no es una tarea que implique un trabajo adicional demasiado grande. La medición del avance
de obra hay que hacerla para poder hacer la Certificación. Es decir que el único trabajo adicional es
ingresar en el Programa dicha medición y el software se encargará de obtener en función de dichos
volúmenes los insumos teóricos necesarios.

Obtención del Consumido (Listado 7 del primer ejemplo)
Para encontrar los desvíos es necesario comparar el listado anterior con los Consumidos Reales
correspondientes al volumen real ejecutado en el período.
Obtener este listado es el trabajo más complicado de todo el Control. Es importante estar
convencido haber entendido y asimilado la metodología y la justificación del método para no
claudicar en el intento. Controlar bien es en realidad un gran negocio. Es mucho más barato
Controlar que no Controlar. La ineficiencia en la Construcción es enorme y por ende cuando se
implementa una metodología seria se obtiene de inmediato un gran resultado. En una industria muy
eficiente que ya haya pasado por esta etapa podría pasar que sea mas caro el Control que el
beneficio que dicho Control implica. Pero no hay que preocuparse puesto que estamos realmente
muy lejos de este punto.
Imaginemos que en la obra existe un Pañol (Depósito de Materiales) con dos puestas, una puerta A
por la que entran insumos desde la calle y salen hacia la calle y una puerta B por la que salen
insumos hacia la Obra

Ingresos

A Pañol B
Utilizados Egresos Obra

La sumatoria de los Ingresos y Egresos se corresponde con el Listado 11 de nuestro primer
ejemplo y se controla con los Remitos firmados a los Proveedores. Recordemos que a los efectos
del Control de la Obra como lo venimos planteando, este Listado de Remitos o Listado 11 no lo
utilizamos para nada.

Página 6 de 8 Agosto 2008

<!-- p. 7 -->

Técnicas Informáticas para la Gestión de Obra

Ing. Ernesto Brenner

Por la puerta B, salen los insumos que van a ser consumidos en la obra y se corresponden con el
Listado 7 del primero de los dos ejemplos tratados. Este listado es precisamente la información que
debemos capturar en obra para compararla con los previstos (Listado 8)
Existen dos formas de obtenerlo:

1- Calculando lo Realmente Utilizado. ( esta es la forma menos habitual)
Para ello es necesario que plantear la ecuación que gobierna a este pañol:

Sant. + l - E - Sact = U

Donde.
Sant. = Corte de Stock anterior
l = Ingresos durante el período
E = Egresos durante el período
Sact. = Corte de Stock actual
U = Insumos Utilizados durante el período.
Por ejemplo: Supongamos que a principios del mes se midió el Stock de inodoros y se contaron 10
(Sant.), que durante este mes ingresaron 10 (l) inodoros más y que dicho ingreso fue debidamente
documentado con los Remitos correspondientes, que en ese mismo período se devolvieron 2 (E)
inodoros por no estar en condiciones y que hoy, un mes después del anterior recuento de Stock, se
contaron 8 (Sact.)
Sant.+ l - E - Sact = U
10 + 10 - 2 - 8 = 10
Reemplazando en la fórmula se determina que se utilizaron 8 inodoros durante dicho período.
Esto habría que hacerlo para los “N” primeros insumos de la curva ABC. Se debe agregar a este
listado los consumidos de Mano de Obra que se obtienen de Area Administrativa en Sueldos y
Jornales.

2- Haciendo una Medición Directa en Obra. (esta es la forma más
habitual)
Si se trata de implementar una medición directa de los consumidos en Obra en un período, muchas
veces el problema está al menos parcialmente solucionado. Este es el caso de los Subcontratos de
Mano de Obra a los cuales se les la propia empresa les provee los materiales. Cada vez que dicho
Subcontratista hace un pedido de Materiales, éste pedido se consigna mediante una Orden de
Requisición de Materiales. Este documento no es más que un Remito Interno que el Subcontratista
firma dejando constancia de los Materiales que está utilizando. Con todos estos documentos se
genera el listado correspondiente.
Si extendiéramos esta metodología al personal propio, es decir, si logramos que nuestros propios
Capataces deban firmar también Ordenes de Requisición de Materiales, el problema quedaría
solucionado en su totalidad.
Como se puede ver, esto implicaría disponer de un pañolero que de alguna forma anote todo lo que
sale del pañol por la puerta B. Este trabajo solo le requeriría medio día de trabajo y en obras
pequeñas menos aún (se supone que durante las mañanas se entregan todos los materiales

Página 7 de 8 Agosto 2008

<!-- p. 8 -->

Técnicas Informáticas para la Gestión de Obra

Ing. Ernesto Brenner

necesarios para todo el día). Por las tardes quedaría libre como para ejecutar alguna otra tarea lo
que significa que en el peor de los casos estaríamos asignando medio sueldo mensual como costo
de control. En obras pequeñas es directamente el propio Capataz quien consignaría en una planilla
diaria los materiales utilizados.
Recordemos que este Control no se lleva a cabo sobre el total de los insumos sino sobre los más
importantes de la Obra que ya habían sido determinados mediante la curva ABC en la etapa de
Presupuestación. Generalmente existen alrededor de 15 insumos que representan más del 80% del
costo y dentro de estos 15 Insumos están sin ninguna duda las distintas categorías de Mano de
Obra. Esto simplifica el trabajo enormemente no solo debido a que finalmente el trabajo se reduce
a controlar 10 o 12 Materiales sino que entre estos materiales no figuran los Materiales a granel.
(esto es lógico debido a que si fueran realmente importantes serían provistos de otra forma)

Este Listado 7 debe necesariamente incluir la Mano de Obra en sus distintas categorías por
encontrarse dentro de los Insumos Calientes (los “N” más importantes de la Curva ABC). Los
consumidos reales de un mes determinado puede obtenerse del Area Administrativa.

En el capítulo de Desvíos y Análisis de Desvíos está la justificación teórica de lo que estamos
exponiendo. El listado 8 se corresponde con el Presupuesto Flexible en tanto tiene como hipótesis
de Volúmenes Reales y Precios y Rendimientos Previstos

Página 8 de 8 Agosto 2008
