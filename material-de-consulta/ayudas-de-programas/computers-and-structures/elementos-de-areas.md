---
type: libro
title: "Elementos de Areas"
author: "Eliud"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 4
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/Elementos de Areas.pdf"
convertido: 2026-10-16
---

# Elementos de Areas

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\Elementos de Areas.pdf` (4 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Curso: Análisis y Diseño Estructural Utilizando el Programa SAP2000 Versión 1.0
Ing. Eliud Hernández C.I.V: 134.353

ELEMENTOS DE AREAS

Los elementos de áreas son analizados a través del método de Elementos Finitos
(medio continuo). Para ello el programa establece tres tipos o modelos matemáticos de
características diferentes, aplicables a determinados casos prácticos.

Estos modelos difieren básicamente en su matriz de rigidez, la cual condiciona sus
grados de libertad y su posible deformación dentro del sistema estructural.

Tipo Shell:

• Elemento que se deforma en su plano y fuera del plano.
• Permite modelar y obtener la deformada espacial de losas, muros o placas
macizas resistentes a momentos, corte y fuerza axial.
• Se vincula de manera rígida (Monolítica) a las vigas de apoyos, es decir, induce
fuerzas de corte, axial y momentos a sus apoyos.

<!-- p. 2 -->

Curso: Análisis y Diseño Estructural Utilizando el Programa SAP2000 Versión 1.0
Ing. Eliud Hernández C.I.V: 134.353

Tipo Membrana:

• Elemento que solo se deforma en su plano.
• Elemento que no permite deformaciones fuera de su plano.
• Permite modelar techos simplemente apoyados, debido a que transmite su carga
a las vigas y/o correas por ancho tributario, de manera rígida. (Losacero, losa de
tabelones, Machihembrado. En general techos simplemente apoyados )

<!-- p. 3 -->

Curso: Análisis y Diseño Estructural Utilizando el Programa SAP2000 Versión 1.0
Ing. Eliud Hernández C.I.V: 134.353

Tipo Plate:

• Elemento que no se deforma en su plano.
• Elemento que solo permite deformaciones fuera de su plano.
• Cualquier carga en su plano genera su inestabilidad
• Es equivalente al Shell, pero no permite cargas en su plano.
• Es aplicable a losas cuya flexión se produzca básicamente en una sola dirección.

Aspectos Resaltantes

Es importante destacar diversos aspectos, conociendo lo descrito anteriormente, para
realizar el análisis de losas y muros, se hace necesario discretizar en múltiples
diferenciales de áreas que permitan obtener deformadas mas aproximadas y con ello un
equilibrio de esfuerzos y fuerzas coherente., las cuales deberán ser interpretadas con
criterio a fines de diseño. Así pues, en cada nodo generado producto de la
discretización, podrá evaluarse su desplazamiento final para cualquier régimen de
cargas.

En estos modelos, las vigas y columnas y en general cualquier elemento lineal,
debidamente conectado, establecen las condiciones de contorno o frontera, las cuales
condicionan directamente los niveles de deformación y transmisión de fuerzas entre los
elementos de áreas discretizados.

La transmisión de las cargas de las áreas (Losas, muros) a los elementos lineales
(Vigas, columnas) se realiza a través de los nodos. Esto quiere decir que si al discretizar
un área determinada sus nodos no coinciden con la directriz del elemento lineal de
apoyo, este elemento queda totalmente desvinculado y sencillamente la losa o muro que
se este analizando obtiene un borde libre.

En el caso de los elementos de área tipo Membrana, como ya se dijo antes, su
deformación sólo ocurre en su plano. Esto trae como consecuencia que su estabilidad
fuera del plano deba venir condicionada por la utilización de elementos de apoyos
(Vigas, correas, etc). Bajo cargas perpendiculares al plano de la membrana, los
elementos de apoyos son los que se encargan de resistir y definir la deformada del
sistema. Las cargas transmitidas de las membranas a estos elementos se realizan por
ancho tributario de nodos.

<!-- p. 4 -->

Curso: Análisis y Diseño Estructural Utilizando el Programa SAP2000 Versión 1.0
Ing. Eliud Hernández C.I.V: 134.353
