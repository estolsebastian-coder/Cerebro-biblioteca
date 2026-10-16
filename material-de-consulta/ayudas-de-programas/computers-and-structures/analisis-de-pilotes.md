---
type: libro
title: "ANALISIS DE PILOTES"
author: ""
categoria: "AYUDAS DE PROGRAMAS"
paginas: 8
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/ANALISIS DE PILOTES.pdf"
convertido: 2026-10-16
---

# ANALISIS DE PILOTES

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\ANALISIS DE PILOTES.pdf` (8 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

ANALISIS DE PILOTES APOYADOS EN UN MEDIO ELASTICO

El pilote mostrado se encuentra hincado sobre

suelo tipo GW, este suelo es No Cohesivo, entonces
la rigidez de los resortes que simulan el suelo se

distribuirán triangularmente, el Coeficiente de

Balasto vertical Kv=17 kg/cm3 (17000 Ton/m3).
El coeficiente horizontal será el 50% del vertical.

Las cargas son las siguientes :
Vu = 88.10 Ton

Hu = 7.40 Ton

Solución
\1. Click en la barra de unidades para poner unidades de Ton-m

\2. En el Menú File, New Model, y llenar como sigue:

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 2 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

\3. Picar en el icono para generar los elementos frame en las grillas creadas.

\4. En el menú Define Materials, elegir concreto y picar Modify/show Material para definir
las propiedades del concreto y el acero, verificar que la resistencia del concreto sea de

280 kg/cm2 (2800 Ton/m2).

\5. Ir al Menú Define, Frame Sections, Add Circle, en Section Name tipear PILOTE, en
Material es Concreto, Diameter es 0.35 m.

\6. Marcar los dos elementos generados, ir al Menú Assign, Fame, Section, señalar
PILOTE, picar OK, los elementos señalados se les ha asignado la sección PILOTE

creada anteriormente.

\7. Menu Draw, Edit Grid, en Direction Z, mover la grilla de 37.10 a 21.15 m, y marcar en
la casilla Glue Joints to Grid Lines. Marcando esta opción, los nudos que se encuentren

en el nivel 37.10, se moverán conjuntamente con la grilla al nivel 21.15.

\8. Picar el icono Marcar el recuadro Frames Labels para visualizar la numeración de

los elementos Frame.

\9. Picar en el elemento 3 (elemento inferior), ir al Menu Edit, Divide Frames, en 10
elementos:

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 3 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

\10. Para obtener los nudos donde se apoyarán los resortes, marcamos los elementos

generados, y los volvemos a dividir, esta vez en 2, ir a Menú Edit, Divide Frames, en
Divide into 2 Frames, Last/First ratio 1, la relación entre longitudes del ultimo entre el

primer elemento generado es 1.

\11. Marcar el nudo central del tramo inferior de 1.855 m (creados en el paso 9), sobre este
nudo se aplicará el resorte, el cual tendrá una rigidez como se muestra en el Item 10 del

siguiente cuadro.

Rigidez de Resortes
Nivel Profundidad (zi) Kv Kh Area Rv Rh
(m) (Ton/m3) (Ton/m3) (m2) (Ton/m) (Ton/m)

1 1.855 17000 8500 1.02 1733.7 866.9
2 3.71 17000 8500 1.02 3467.5 1733.7
3 5.565 17000 8500 1.02 5201.2 2600.6
4 7.42 17000 8500 1.02 6934.9 3467.5
5 9.275 17000 8500 1.02 8668.6 4334.3
6 11.13 17000 8500 1.02 10402.4 5201.2
7 12.985 17000 8500 1.02 12136.1 6068.0
8 14.84 17000 8500 1.02 13869.8 6934.9
9 16.695 17000 8500 1.02 15603.5 7801.8
10 18.55 17000 8500 1.02 17337.3 8668.6

\12. Menú Assign, Joint, Spring, en el cuadro Translation 1 (Eje X), colocar 8668.60 Ton/m,

correspondiente a la rigidez horizontal del resorte en el nivel 10.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 4 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

\13. Repetir el paso 11 y 12 para los niveles siguientes, asignandole el resorte en el nudo
central de cada tramo.

\14. Se le asignará en el nudo del extremo inferior un resorte vertical para que tome la
reacción vertical, se marca el nudo mencionado, Menú Assign, Joint, Spring, en el

cuadro Translation 3 (Eje Z), colocar 17337.3 Ton/m, para la rigidez vertical.

\15. Las cargas dadas son últimas, entonces pueden agruparse en un solo caso de carga
estática que por defecto es LOAD1. Marcar el nudo del extremo superior que es donde

se aplica la carga, Menú Assign, Joint Static Loads, Forces, en Force Global X ingresar
7.40 Ton, en Force Global Z ingresar -88.10 Ton.

\16. En el Menú Analize, Set Options picar en el icono de análisis plano, a continuación OK.

\17. Grabar el archivo con algún nombre, ejemplo Análisis de pilotes.SDB, luego ejecutar el

programa picando en .

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 5 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

\18. Para enviar los resultados de las reacciones laterales a un archivo de texto, ir al Menú

File, Print Output Tables; en este cuadro, marcar únicamente Spring Force (para que
solo se visualicen los resultados de reacciones en resortes) y Print to File (para grabar

estos resultados en un archivo con formato de texto); Presionar el botón Select Load y

señalizar únicamente LOAD1, OK; Presionar el botón File Name, direccionar la
ubicación del archivo, dar nombre (Reaccion pilote.txt) y presionar Guardar, luego OK.

SAP2000 v6.11 File: ANALISIS DE PILOTES Ton-m Units PAGE 1
Enero 2, 2001 14:16

PARTICULAR

F R A M E E L E M E N T F O R C E S

FRAME LOAD LOC P V2 V3 T M2 M3

4 LOAD1
0.00 -88.70 7.40 0.00 0.00 0.00 19.24
1.30 -88.40 7.40 0.00 0.00 0.00 9.62
2.60 -88.10 7.40 0.00 0.00 0.00 0.00
15 LOAD1
0.00 -92.99 0.00 0.00 0.00 0.00 0.00
4.6E-01 -92.88 0.00 0.00 0.00 0.00 0.00
9.3E-01 -92.77 0.00 0.00 0.00 0.00 0.00
16 LOAD1
0.00 -92.77 2.119E-04 0.00 0.00 0.00 0.00
4.6E-01 -92.67 2.119E-04 0.00 0.00 0.00 -9.825E-05
9.3E-01 -92.56 2.119E-04 0.00 0.00 0.00 -1.965E-04
17 LOAD1
0.00 -92.56 2.119E-04 0.00 0.00 0.00 -1.965E-04
4.6E-01 -92.45 2.119E-04 0.00 0.00 0.00 -2.947E-04
9.3E-01 -92.35 2.119E-04 0.00 0.00 0.00 -3.930E-04
18 LOAD1
0.00 -92.35 1.395E-03 0.00 0.00 0.00 -3.930E-04
4.6E-01 -92.24 1.395E-03 0.00 0.00 0.00 -1.040E-03
9.3E-01 -92.13 1.395E-03 0.00 0.00 0.00 -1.687E-03
19 LOAD1

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 6 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

0.00 -92.13 1.395E-03 0.00 0.00 0.00 -1.687E-03
4.6E-01 -92.02 1.395E-03 0.00 0.00 0.00 -2.333E-03
9.3E-01 -91.92 1.395E-03 0.00 0.00 0.00 -2.980E-03
20 LOAD1
0.00 -91.92 -6.216E-03 0.00 0.00 0.00 -2.980E-03
4.6E-01 -91.81 -6.216E-03 0.00 0.00 0.00 -9.739E-05
9.3E-01 -91.70 -6.216E-03 0.00 0.00 0.00 2.785E-03
21 LOAD1
0.00 -91.70 -6.216E-03 0.00 0.00 0.00 2.785E-03
4.6E-01 -91.60 -6.216E-03 0.00 0.00 0.00 5.668E-03
9.3E-01 -91.49 -6.216E-03 0.00 0.00 0.00 8.550E-03
22 LOAD1
0.00 -91.49 -2.842E-02 0.00 0.00 0.00 8.550E-03
4.6E-01 -91.38 -2.842E-02 0.00 0.00 0.00 2.173E-02
9.3E-01 -91.27 -2.842E-02 0.00 0.00 0.00 3.491E-02
23 LOAD1
0.00 -91.27 -2.842E-02 0.00 0.00 0.00 3.491E-02
4.6E-01 -91.17 -2.842E-02 0.00 0.00 0.00 4.808E-02
9.3E-01 -91.06 -2.842E-02 0.00 0.00 0.00 6.126E-02
24 LOAD1
0.00 -91.06 8.486E-02 0.00 0.00 0.00 6.126E-02
4.6E-01 -90.95 8.486E-02 0.00 0.00 0.00 2.191E-02
9.3E-01 -90.85 8.486E-02 0.00 0.00 0.00 -1.744E-02
25 LOAD1
0.00 -90.85 8.486E-02 0.00 0.00 0.00 -1.744E-02
4.6E-01 -90.74 8.486E-02 0.00 0.00 0.00 -5.679E-02
9.3E-01 -90.63 8.486E-02 0.00 0.00 0.00 -9.615E-02
26 LOAD1
0.00 -90.63 5.094E-01 0.00 0.00 0.00 -9.615E-02
4.6E-01 -90.52 5.094E-01 0.00 0.00 0.00 -3.324E-01
9.3E-01 -90.42 5.094E-01 0.00 0.00 0.00 -5.686E-01
27 LOAD1
0.00 -90.42 5.094E-01 0.00 0.00 0.00 -5.686E-01
4.6E-01 -90.31 5.094E-01 0.00 0.00 0.00 -8.048E-01
9.3E-01 -90.20 5.094E-01 0.00 0.00 0.00 -1.04
28 LOAD1
0.00 -90.20 -3.122E-01 0.00 0.00 0.00 -1.04
4.6E-01 -90.09 -3.122E-01 0.00 0.00 0.00 -8.963E-01
9.3E-01 -89.99 -3.122E-01 0.00 0.00 0.00 -7.515E-01
29 LOAD1
0.00 -89.99 -3.122E-01 0.00 0.00 0.00 -7.515E-01
4.6E-01 -89.88 -3.122E-01 0.00 0.00 0.00 -6.067E-01
9.3E-01 -89.77 -3.122E-01 0.00 0.00 0.00 -4.619E-01
30 LOAD1
0.00 -89.77 -5.62 0.00 0.00 0.00 -4.619E-01
4.6E-01 -89.67 -5.62 0.00 0.00 0.00 2.14
9.3E-01 -89.56 -5.62 0.00 0.00 0.00 4.75
31 LOAD1
0.00 -89.56 -5.62 0.00 0.00 0.00 4.75
4.6E-01 -89.45 -5.62 0.00 0.00 0.00 7.36
9.3E-01 -89.34 -5.62 0.00 0.00 0.00 9.96
32 LOAD1
0.00 -89.34 -8.70 0.00 0.00 0.00 9.96
4.6E-01 -89.24 -8.70 0.00 0.00 0.00 14.00
9.3E-01 -89.13 -8.70 0.00 0.00 0.00 18.03
33 LOAD1
0.00 -89.13 -8.70 0.00 0.00 0.00 18.03
4.6E-01 -89.02 -8.70 0.00 0.00 0.00 22.07
9.3E-01 -88.92 -8.70 0.00 0.00 0.00 26.10
34 LOAD1
0.00 -88.92 7.40 0.00 0.00 0.00 26.10
4.6E-01 -88.81 7.40 0.00 0.00 0.00 22.67
9.3E-01 -88.70 7.40 0.00 0.00 0.00 19.24
\19. Los resultados así obtenidos, pueden ser “jalados” a una hoja de cálculo, donde se
puede visualizar y ordenar mejor los resultados:

FRAME Profundidad P V2 V3 T M2 M3
z (m.) (Ton.) (Ton.) (Ton.) (Ton.) (Ton-m) (Ton-m)
0.000 -92.99 0.00 0.00 0.00 0.00 0.00
15 0.464 -92.88 0.00 0.00 0.00 0.00 0.00
0.928 -92.77 0.00 0.00 0.00 0.00 0.00

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 7 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

0.928 -92.77 0.00 0.00 0.00 0.00 0.00
16 1.391 -92.67 0.00 0.00 0.00 0.00 0.00
1.855 -92.56 0.00 0.00 0.00 0.00 0.00
1.855 -92.56 0.00 0.00 0.00 0.00 0.00
17 2.319 -92.45 0.00 0.00 0.00 0.00 0.00
2.783 -92.35 0.00 0.00 0.00 0.00 0.00
2.783 -92.35 0.00 0.00 0.00 0.00 0.00
18 3.246 -92.24 0.00 0.00 0.00 0.00 0.00
3.710 -92.13 0.00 0.00 0.00 0.00 0.00
3.710 -92.13 0.00 0.00 0.00 0.00 0.00
19 4.174 -92.02 0.00 0.00 0.00 0.00 0.00
4.638 -91.92 0.00 0.00 0.00 0.00 0.00
4.638 -91.92 -0.01 0.00 0.00 0.00 0.00
20 5.101 -91.81 -0.01 0.00 0.00 0.00 0.00
5.565 -91.70 -0.01 0.00 0.00 0.00 0.00
5.565 -91.70 -0.01 0.00 0.00 0.00 0.00
21 6.029 -91.60 -0.01 0.00 0.00 0.00 0.01
6.493 -91.49 -0.01 0.00 0.00 0.00 0.01
6.493 -91.49 -0.03 0.00 0.00 0.00 0.01
22 6.956 -91.38 -0.03 0.00 0.00 0.00 0.02
7.420 -91.27 -0.03 0.00 0.00 0.00 0.03
7.420 -91.27 -0.03 0.00 0.00 0.00 0.03
23 7.884 -91.17 -0.03 0.00 0.00 0.00 0.05
8.348 -91.06 -0.03 0.00 0.00 0.00 0.06
8.3418 -91.06 0.08 0.00 0.00 0.00 0.06
24 8.811 -90.95 0.08 0.00 0.00 0.00 0.02
9.275 -90.85 0.08 0.00 0.00 0.00 -0.02
9.275 -90.85 0.08 0.00 0.00 0.00 -0.02
25 9.739 -90.74 0.08 0.00 0.00 0.00 -0.06
10.203 -90.63 0.08 0.00 0.00 0.00 -0.10
10.203 -90.63 0.51 0.00 0.00 0.00 -0.10
26 10.666 -90.52 0.51 0.00 0.00 0.00 -0.33
11.130 -90.42 0.51 0.00 0.00 0.00 -0.57
11.130 -90.42 0.51 0.00 0.00 0.00 -0.57
27 11.594 -90.31 0.51 0.00 0.00 0.00 -0.80
12.058 -90.20 0.51 0.00 0.00 0.00 -1.04
12.058 -90.20 -0.31 0.00 0.00 0.00 -1.04
28 12.521 -90.09 -0.31 0.00 0.00 0.00 -0.90
12.985 -89.99 -0.31 0.00 0.00 0.00 -0.75
12.985 -89.99 -0.31 0.00 0.00 0.00 -0.75
29 13.449 -89.88 -0.31 0.00 0.00 0.00 -0.61
13.913 -89.77 -0.31 0.00 0.00 0.00 -0.46
13.913 -89.77 -5.62 0.00 0.00 0.00 -0.46
30 14.376 -89.67 -5.62 0.00 0.00 0.00 2.14
14.840 -89.56 -5.62 0.00 0.00 0.00 4.75
14.840 -89.56 -5.62 0.00 0.00 0.00 4.75
31 15.304 -89.45 -5.62 0.00 0.00 0.00 7.36

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 8 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

15.768 -89.34 -5.62 0.00 0.00 0.00 9.96
15.768 -89.34 -8.70 0.00 0.00 0.00 9.96
32 16.231 -89.24 -8.70 0.00 0.00 0.00 14.00
16.695 -89.13 -8.70 0.00 0.00 0.00 18.03
16.695 -89.13 -8.70 0.00 0.00 0.00 18.03
33 17.159 -89.02 -8.70 0.00 0.00 0.00 22.07
17.623 -88.92 -8.70 0.00 0.00 0.00 26.10
17.623 -88.92 7.40 0.00 0.00 0.00 26.10
34 18.086 -88.81 7.40 0.00 0.00 0.00 22.67
18.550 -88.70 7.40 0.00 0.00 0.00 19.24
18.550 -88.70 7.40 0.00 0.00 0.00 19.24
4 18.673 -88.40 7.40 0.00 0.00 0.00 9.62
21.150 -88.10 7.40 0.00 0.00 0.00 0.00

DIAGRAMA DE FUERZAS CORTANTES DIAGRAMA DE MOMENTOS

20 20

15 15
(m) (m)

10 10 PROFUNDIDAD PROFUNDIDAD

5 5

0 0
\-10 -5 0 5 10 -10 0 10 20 30
CORTANTE (Ton) MOMENTO (Ton-m)

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm
