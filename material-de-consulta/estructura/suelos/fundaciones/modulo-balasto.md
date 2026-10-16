---
type: libro
title: "modulo_balasto"
author: "NACHO"
categoria: "ESTRUCTURA"
paginas: 6
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/SUELOS/FUNDACIONES/modulo_balasto.pdf"
convertido: 2026-10-16
---

# modulo_balasto

> Texto extraído de `ESTRUCTURA\SUELOS\FUNDACIONES\modulo_balasto.pdf` (6 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

DETERMINACIÓN DEL COEFICIENTE DE
BALASTO EN CIMENTACIONES

Introducción
Actualmente en el campo de las cimentaciones, uno de los métodos más
empleados para calcular los esfuerzos es la modelización como viga flexible,
en el cual se supone el terreno como un conjunto infinito de muelles
situados bajo una viga deformable, la cimentación. La constante de
deformación de cada muelle es Ks (módulo de balasto), valor obtenido del
cociente entre la presión de contacto (q) y el desplazamiento, en nuestro
caso (δ).

Ks= q / δ

Fuente: CALAVERA RUIZ, JOSÉ 1

El método se creó inicialmente para el análisis de las traviesas del
ferrocarril, donde el balasto es la capa de grava que se tiende sobre la
explanación de los ferrocarriles para asentar y sujetar las traviesas. El
creador de este modelo de interacción estructura-terreno fue Winkler, y
tiene múltiples aplicaciones, no sólo en el campo de las cimentaciones, sino
en cualquiera problema que pudiese adaptarse a este modelo.
La aplicación de la teoría del módulo de balasto ha ganado aceptación en los
últimos tiempos, ya que permite una fácil asimilación del modelo de la
interacción estructura-terreno utilizando los métodos matriciales de cálculo.
Bastará con incluir muelles en los nudos con la rigidez correspondiente al
balasto, en elementos lineales mediante su discretización en varias barras
cuyos nudos incluyen bielas, en elementos superficiales mediante un
emparrillado de barras con las bielas en los nudos. Esto ha supuesto que el
método de Winkler sea el que usa la mayor del software de cálculo de
estructuras, principalmente para vigas y losas de cimentación.

<!-- p. 2 -->

Por el contrario, existen varias objeciones al modelo que lo hacen poco
fiable:
• En el caso de cimentaciones superficiales, el modelo supone que cada
punto del suelo se comporta independientemente de las cargas
existentes en sus alrededores, lo cual no ocurre en la realidad porque
la distribución de las cargas varía debido a la deformación de la viga.
• La deformación del cimiento hace que los pilares desciendan con él,
por tanto “la viga no puede ser concebida en absoluto como una
pieza con carga igual a la reacción del terreno y apoyada en los
pilares, sino apoyada en el terreno y cargada por los pilares”1.
• El valor del módulo de balasto no es función exclusiva del terreno,
también depende de las características geométricas de la cimentación
y de la estructura que ésta sostiene, se hace compleja la
extrapolación de los resultados de los estudios geotécnicos a un
modelo de cálculo fiable.

Recomendaciones
A grandes rasgos el modelo de interacción cimiento-terreno se ha de ajustar
a la forma de distribuirse las presiones sobre el terreno. Si éstas se
distribuyen de una manera lineal, como por ejemplo en cimentaciones
rígidas, el cálculo debe llevarse a cabo mediante los métodos clásicos de
cimentaciones con leyes de tensiones lineales. Si la distribución de
tensiones es irregular, debe usar un modelo de elementos flexibles, como
por ejemplo el método de Winkler o los elementos finitos.
Debido al desconocimiento real de los valores del módulo de balasto para
unos determinados cimentación, estructura y terreno, es necesario que
calcular con órdenes de magnitud. Para ello se hace un estudio de
sensibilidad de la variable, es decir, analizamos los resultados del cálculo
con tres valores de K distintos, por ejemplo un diez veces mayor y otro diez
veces menor que el que tenemos estimado, para así ver cuanto influye esta
variable. En caso de ser de gran influencia es recomendable hacer una
comprobación inversa a partir del asiento, calculando el módulo K
correspondiente al valor del asiento de la cimentación, estimados por los
métodos clásicos de la geotécnia.
Para obtener un primer orden de magnitud del módulo de balasto no debe
tomarse el valor del ensayo de placa de carga, es necesario hacerle unas
correcciones debidas a los diferentes aspectos que intervienen en el valor
de K, tal como se explicará a continuación.

Obtención del módulo de balasto
Método 1:
A partir de ensayo de placa de carga realizado sobre el terreno, con
unas dimensiones habituales de placa cuadrada de 30x30cm, o bien
circular de diámetros 30, 60 y 76,2cm. En el estudio geotécnico este
módulo viene generalmente representado por una K, mientras que el

<!-- p. 3 -->

correspondiente subíndice identifica a la placa con que se realizó el
ensayo (K30, K60, etc.)
El tamaño de la placa influye en la profundidad afectada, por tanto a
menor tamaño de placa menor bulbo de presiones y con ello menor
profundidad de los estratos estudiados. En el caso de losas la
profundidad de influencia de la placa es mucho menor que la de la losa
real, cuyo bulbo de presiones está en función de su ancho total, con lo
que se puede inducir a errores graves debidos a bajadas de rigidez de
estratos inferiores pero activos. En el caso de terrenos rocosos las
pruebas realizadas con una placa grande estarán más afectadas por la
fisuración que las hechas con placa pequeña.
A partir del ensayo de placa de carga, mediante formulación planteada
por Terzaghi que contempla las dimensiones del cimiento se puede
obtener el módulo de balasto. En general, este método es para zapatas
porque en el caso de losas es más complejo y se debe estudiar la
rigidez del conjunto de estructura-cimentación, aunque como se verá es
posible adaptarlo para obtener un primer orden de magnitud.
Dada una losa rectangular y un coeficiente de balasto obtenido
mediante ensayo de placa de carga de 30x30cm definimos:
• b: ancho equivalente de la zapata (m): parámetro que depende
de la rigidez de la estructura y de la cimentación. En el caso de
losas, un valor aproximado para b puede ser la luz media entre
pilares, si es una luz pequeña, o el ancho total de la losa en caso
de luces medias o grandes, a pesar de que esto conduce a
módulos de balasto excesivamente bajos. Se recomienda
consultar bibliografía específica en caso de necesitar un valor de
precisión.
• l: lado mayor o longitud de la losa (m)
• Ks,30: módulo obtenido en placa de 30x30cm (kN/m3).
• Ks,cuadrada: módulo de la zapata cuadrada (kN/m3).
• Ks,rectangular: módulo de la zapata rectangular (kN/m3).

Para el cálculo del módulo de balasto de la zapata rectangular será
necesario primero calcular el de la cuadrada.
El módulo de balasto de la zapata rectangular en función del de la placa
cuadrada se define por (Terzaghi 1955):

Ks, rectangular= (2/3) Ks, cuadrada [ 1+ b/(2l) ]
donde Ks, cuadrada se determina en función del tipo de suelo y del
ensayo de placa de carga de 30x30:
Suelos cohesivos (arcillas):
Ks, cuadrado cohesivo= Ks,30 [0,30/b]
Suelos arenosos o granulares:
Ks, cuadrado arenoso= Ks,30 [(b+0,30)/(2b)]2

<!-- p. 4 -->

Nota 1:
En el caso de tener una mezcla de suelos es posible interpolar a partir
de los valores anteriores en la proporción existente de dichos suelos,
aunque esto no deja de ser una aproximación.
Nota 2:
En el caso de trabajar en cm, basta con cambiar el coeficiente 0,30 por
30 para que sean válidas las fórmulas.
Nota 3:
Aunque lo correcto es obtener los datos del módulo de balasto del
terreno, podemos dar unos valores orientativos para ensayos de placa
de carga2.

<!-- p. 5 -->

Método 2:
Mediante la determinación de los parámetros característicos del terreno
(módulo de deformación, tensión admisible, etc.) que se relacionan con
el módulo de balasto por fórmulas de diversos autores.
Fórmula de Vesic: en función del módulo de deformación o elasticidad
(Es) y del coeficiente de Poisson (νs) el terreno, que en su forma
reducida tiene la siguiente expresión:
Ks = Es / [ B (1-νs2) ]
donde B es el ancho de la cimentación.

<!-- p. 6 -->

Fórmula de Klepikov3:
Ks = Es/[ωA(1/2) (1-νs2)]
con (A) el área de la base de la cimentación y (ω) un coeficiente de
forma de la cimentación que para zapatas o losas se puede obtener de
la tabla en función del largo (L) y del ancho (b) de la cimentación:

L/b 1,0 1,5 2,0 3,0 4,0 5,0 6,0 7,0 8,0 9,0 10,0
ω 0,88 0,87 0,86 0,83 0,80 0,77 0,74 0,73 0,71 0,69 0,67

Fórmula de Bowles4: basada en la tensión admisible de la cimentación:
Ks (kN/m3) = 40*(Factor de Seguridad)*σa (kPa)
donde el factor de seguridad es el empleado para minorar la tensión
admisible (FS = 3).

Elaboración y recopilación: Nacho Requena (arquitecto)
Septiembre de 2007

REFERENCIAS
1 CALAVERA RUIZ, JOSÉ: “Cálculo de estructuras de cimentación”, Ed. Instituto técnico
de materiales y construcciones (Intemac), Madrid, 2000.
2 CALAVERA RUIZ, JOSÉ: “Proyecto y cálculo de estructuras de hormigón. Tomo 2”, Ed.
Ed. Instituto técnico de materiales y construcciones (Intemac), Madrid, 1999.
3 TSUDIK, EDWARD: “Analysis of Beams and Frames on Elastic Foundation”, Ed. Trafford
Publishing.
4 BOWLES, JOSEPH: "Foundation Analisis and Design", Ed. Mc Graw-Hill, 1997.

BIBLIOGRAFÍA

RODRÍGUEZ ORTÍZ, J.M., SERRA GESTA, J. y OTEO MAZO, C.: “Curso aplicado de
cimentaciones”, Ed. COAM, Madrid.

CALAVERA RUIZ, JOSÉ: “Cálculo de estructuras de cimentación”, Ed. Instituto técnico de
materiales y construcciones (Intemac), Madrid, 2000.

MUZAS LABAD, FERNANDO. \<\<Consideraciones sobre la elección de los coeficientes de
balasto>>. Revista de Obras Públicas Noviembre 2002. Nº 3427.

DE MECÁNICA: “Módulo de balasto”, http://www.demecanica.com
