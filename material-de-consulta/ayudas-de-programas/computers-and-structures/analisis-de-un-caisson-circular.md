---
type: libro
title: "ANALISIS DE UN CAISSON CIRCULAR"
author: ""
categoria: "AYUDAS DE PROGRAMAS"
paginas: 11
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/ANALISIS DE UN CAISSON CIRCULAR.pdf"
convertido: 2026-10-16
---

# ANALISIS DE UN CAISSON CIRCULAR

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\ANALISIS DE UN CAISSON CIRCULAR.pdf` (11 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

ANALISIS DE UN CAISSON CIRCULAR APOYADO EN UN MEDIO ELASTICO

PD = 1520 Ton.
PL = 380 Ton.
H = 620 Ton.

El peso propio de la estructura está
incluido en la carga muerta
asignada.

La estructura está cimentada sobre
suelo homogéneo tipo GP, el cual
corresponde a un coeficiente de
Balasto vertical :
Kv = 11 Kg/cm3 (11000 Ton/m3)
El coeficiente de Balasto horizontal
se considera como el 50% del
vertical.

Solución
\1. El suelo se considerará como un medio elástico simulado como resortes, los cuales

serán las condiciones de borde que hace a la estructura estable.
\2. Click en la barra de unidades para poner unidades de Ton-m

\3. En el Menú principal ingresar a File y a New Model from Template, click en
Cylinder y llenar el cuadro de la siguiente forma para considerar el círculo dividido

en 10 secciones, 20 espacios en altura, 22.25 m de altura total medida a ejes del

cilindro y 2.8 m de radio a ejes de los muros, desactivar el cuadro restrains para que
no tenga restricciones en la base.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 2 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

\4. En el menu Draw, Edit Grid añadir grilla radial a 1 m y 2 m.

\5. Se han formado en el paso 3, elementos shell en el perímetro del cilindro. Hacer

click en el icono y picar en todas secciones de la capa superior e inferior del

cilindro.

\6. En el menú Define Materials, elegir concreto y picar Modify/show Material para
definir las propiedades del concreto y el acero, verificar que la resistencia del

concreto sea de 280 kg/cm2 (2800 Ton/m2).
\7. En el Menú Define Shell Section, Picar en Add New Section, en Name Section

escribir el nombre del elemento Shell que se está generando (PARED), el material

es concreto, en Membrane y Bending darle el espesor del shell (0.40 m), en Type
verificar que esté activado Shell, repetir el mismo procedimiento para generar el

elemento shell en la losa superior e inferior.
\8. Picar los elementos Shell de la losa superior y en el Menú Assign, asignarles el

elemento Shell que le corresponda, repetir para la losa superior y los elementos

laterales.
\9. Las condiciones de borde serán resortes colocados en todos los nudos de la losa

inferior menos el nudo central; en los nudos de muros que se encuentren enterrados.
\10. La Rigidez del resorte K se calcula multiplicando el Coeficiente de balasto por el

área de influencia del resorte como se muestra en el siguiente cuadro:

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 3 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

Rigidez de Resortes
Ubicación Kv Kh Area Rv Rh
(Ton/m3) (Ton/m3) (m2) (Ton/m) (Ton/m)
Paredes
Borde superior 11000 5500 0.71 7810 3905
Caras laterales 11000 5500 1.05 11550 5775
Borde inferior 11000 5500 0.52 5720 2860
Losa de Fondo
Radio = 2.80 11000 5500 1.57 17270 8635
Radio = 2.00 11000 5500 0.94 10340 5170
Radio = 1.00 11000 5500 0.31 3410 1705

\11. El borde superior corresponde al nivel 17.8 m, marcar los nudos de este nivel, en el

menú Assign Joints, Spring se ingresa en Translation 1 (Eje X) y Translation 2 (Eje
Y),la rigidez del resorte Rh=3905 Ton/m.

\12. Marcar los nudos en las caras laterales, en el menú Assign Joints, Spring se ingresa

en Translation 1 (Eje X) y Translation 2 (Eje Y), la rigidez del resorte Rh=5775
Ton/m.

\13. Marcar los nudos del borde de la losa inferior, en el menú Assign Joints, Spring se
ingresa en Translation 1 (Eje X) y Translation 2 (Eje Y), la rigidez del resorte

Rh=2860 Ton/m.y en Translation 3 (Eje Z), la rigidez del resorte Rv=17270 Ton/m.
\14. Marcar los nudos de radio 2 m y asignarle solamente la rigidez resorte vertical en

Translation 3 (Eje Z), repetir para el radio de 1m.

\15. En el Menú Define Static Load Cases, se define los tipos de carga estatica a los que
está sujeto la Estructura, estos son Carga Muerta, Viva y Sismo, se definirán como

CM, CV y SISMO respectivamente; en Load, ingresar CM, Tipe DEAD, en Self
Weight Multiplier (Multiplicador de Peso propio) pondremos 0, ya que de acuerdo

al problema la carga vertical está considerando el peso propio. Repetimos para los

otros 2 casos de carga.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 4 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

\16. En el Menú Define Load Combinations, para ingresarle la combinacion de carga

CM + CV + SISMO, Picar en Add New Combo, en Load Combination Name,

colocar COMB1, Load Combination type debe ser ADD para que el programa sume
las cargas mayoradas, en Title, se escribe una pequeña descripción de la

combinación (COMB1: CM + CV + SISMO), ingresar luego las cargas afectadas
por el coeficiente igual a 1, esta combinación se usará para el análisis a servicio.

\17. Marcar el nudo central de la losa superior y en el Menú Assign Joint Static Loads,

Forces, aplicar las cargas, Load Case Name = CM, Force Global Z = -1520 Ton,
OK; repetir para Load Case Name = CV, Force Global Z = -380 Ton.

\18. Marcar el nudo central de la losa superior y en el Menú Assign Joint Static Loads,
Forces, aplicar las cargas, Load Case Name = SISMO, Force Global X = 620 Ton,

en Moment Global YY = 620 Ton-m, correspondiente al momento producido al
trasladar la carga horizontal al nudo central de la losa superior, luego picar en OK.

\19. En el Menú Analize, Set Options picar en el icono de analisis espacial:

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 5 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

\20. Presionar el icono para efectuar el análisis.

\21. Con el análisis efectuado, pueden visualizarse las reacciones en los resortes picando

en , y marcando Spring Forces, OK.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 6 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

\22. Para enviar los resultados de estas reacciones en la base a un archivo de texto,

marcar los elementos y nodos de la base del caissón, luego ir al Menú File, Print

Output Tables; en este cuadro, marcar Spring Force (para que solo se visualicen los
resultados de reacciones en resortes), Selection Only (entrega valores para los nudos

y elementos señalizados) y Print to File (para grabar estos resultados en un archivo
con formato de texto); Presionar el botón Select Load y señalizar únicamente

COMB1, OK; Presionar el botón File Name, direccionar la ubicación del archivo,

dar nombre (Base Caisson.txt) y presionar Guardar, luego OK.

SAP2000 v6.11 File: EJEM CAISSON Ton-m Units PAGE 1
Enero 2, 2001 11:45

PARTICULAR

L O A D C O M B I N A T I O N M U L T I P L I E R S

COMBO TYPE CASE FACTOR TYPE TITLE

COMB1 ADD COMB1
CM 1.0000 STATIC(DEAD)
CV 1.0000 STATIC(LIVE)
SISMO 1.0000 STATIC(QUAKE)

SAP2000 v6.11 File: EJEM CAISSON Ton-m Units PAGE 2
Enero 2, 2001 11:45

PARTICULAR

J O I N T S P R I N G F O R C E S

JOINT LOAD F1 F2 F3 M1 M2 M3

1 COMB1 5.8414 0.0000 120.4101 0.0000 0.0000 0.0000

2 COMB1 5.8431 9.132E-03 117.8556 0.0000 0.0000 0.0000

5 COMB1 5.8390 0.0263 111.1677 0.0000 0.0000 0.0000

7 COMB1 5.8173 0.0405 102.9010 0.0000 0.0000 0.0000

9 COMB1 5.7862 0.0322 96.2131 0.0000 0.0000 0.0000

11 COMB1 5.7711 0.0000 93.6585 0.0000 0.0000 0.0000

13 COMB1 5.7862 -0.0322 96.2131 0.0000 0.0000 0.0000

15 COMB1 5.8173 -0.0405 102.9010 0.0000 0.0000 0.0000

17 COMB1 5.8390 -0.0263 111.1677 0.0000 0.0000 0.0000

19 COMB1 5.8431 -9.132E-03 117.8556 0.0000 0.0000 0.0000

247 COMB1 0.0000 0.0000 58.1690 0.0000 0.0000 0.0000

248 COMB1 0.0000 0.0000 57.0825 0.0000 0.0000 0.0000

249 COMB1 0.0000 0.0000 19.4409 0.0000 0.0000 0.0000

250 COMB1 0.0000 0.0000 19.2631 0.0000 0.0000 0.0000

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 7 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

252 COMB1 0.0000 0.0000 19.9064 0.0000 0.0000 0.0000

253 COMB1 0.0000 0.0000 61.0136 0.0000 0.0000 0.0000

254 COMB1 0.0000 0.0000 64.5296 0.0000 0.0000 0.0000

255 COMB1 0.0000 0.0000 20.4818 0.0000 0.0000 0.0000

256 COMB1 0.0000 0.0000 20.9473 0.0000 0.0000 0.0000

257 COMB1 0.0000 0.0000 67.3742 0.0000 0.0000 0.0000

258 COMB1 0.0000 0.0000 68.4607 0.0000 0.0000 0.0000

259 COMB1 0.0000 0.0000 21.1251 0.0000 0.0000 0.0000

260 COMB1 0.0000 0.0000 20.9473 0.0000 0.0000 0.0000

261 COMB1 0.0000 0.0000 67.3742 0.0000 0.0000 0.0000

262 COMB1 0.0000 0.0000 64.5296 0.0000 0.0000 0.0000

263 COMB1 0.0000 0.0000 20.4818 0.0000 0.0000 0.0000

264 COMB1 0.0000 0.0000 19.9064 0.0000 0.0000 0.0000

265 COMB1 0.0000 0.0000 61.0136 0.0000 0.0000 0.0000

266 COMB1 0.0000 0.0000 58.1690 0.0000 0.0000 0.0000

267 COMB1 0.0000 0.0000 19.4409 0.0000 0.0000 0.0000

\23. Los nudos en la base están dispuestos de la siguiente manera :

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 8 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

\24. Las presiones que calcularemos serán a lo largo del eje X, en los nudos 11, 248,

250, 251, 259, 258 y 1. Para calcular la presión se dividirá la reacción en el resorte

entre el area de influencia del resorte analizado :

Nudo Tipo de X F3 Area Presión Transm.
Carga (m.) (Ton.) (m2) (Ton/m2)
11 COMB1 -2.80 93.66 0.65 143.33
248 COMB1 -2.00 57.08 1.10 51.77
250 COMB1 -1.00 19.26 0.71 27.25
259 COMB1 1.00 21.13 0.71 29.89
258 COMB1 2.00 68.46 1.10 62.08
1 COMB1 2.80 120.41 0.65 184.27

PRESIONES TRANSMITIDAS EN LA BASE

DISTANCIA (m.)
\-2.80 0.00 2.80
0

50
TRANSMITIDA 100 (Ton/m2)

150 PRESION

\25. Para obtener por niveles las Fuerzas cortantes y momentos que se generan despues

del análisis en la estructura, es necesario definir los niveles en que queremos que
estos resultados se muestren.

\26. Picar , ir al Menú View, Set 3D View, en Aperture, reducir a un valor pequeño

(2); luego marcar los elementos y nudos del nivel inferior.
\27. Ir al Menú Assign, Group Name, en Groups tipear NIVEL0, picar en Add new

Group Name, OK.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 9 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

\28. Marcar los elementos y nudos del nivel superior al nivel marcado anteriormente,

con , marcar los elementos inferiores que llegan a este nivel. Ir al Menú Assign,

Group Name, en Groups tipear NIVEL1, picar en Add new Group Name, OK.
\29. Repetir el paso 26 para los niveles 2, 3, ..., 19, 20.

\30. Ir al Menú Display, Show Group Joint Force Sums, En el cuadro que aparece,
marcar los niveles del 1 al 20, y presionar OK; aparecerá el cuadro Group Joint

Force Summation. En este cuadro en el Menú File, Print Tables to File, grabar este

archivo como Cortantes.txt obteniendose el siguiente archivo:

SAP2000 v6.11 File: EJEM CAISSON Ton-m Units PAGE 1
Diciembre 29, 2000 17:57

PARTICULAR

G R O U P J O I N T F O R C E S U M M A T I O N

GROUP LOAD F-X F-Y F-Z M-X M-Y M-Z

NIVEL0 (Sum at X=1.92273E-09 Y=1.153638E-08 Z=0)
COMB1 -1.431E-06 -1.609E-06 5.126E-06 1.416E-05 -2.240E-06 0.000

NIVEL1 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=1.1125)
COMB1 -58.184 3.695E-06 -1900.000 -1.406E-04 313.537 6.124E-06

NIVEL2 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=2.225)
COMB1 -158.135 0.000 -1900.000 -1.102E-04 489.462 -2.878E-06

NIVEL3 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=3.3375)
COMB1 -241.053 -2.205E-06 -1900.000 -1.473E-04 757.633 1.941E-05

NIVEL4 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=4.45)
COMB1 -307.284 0.000 -1900.000 -4.840E-05 1099.487 0.000

NIVEL5 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=5.5625)
COMB1 -356.925 0.000 -1900.000 -3.073E-05 1496.566 4.565E-05

NIVEL6 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=6.675)
COMB1 -389.797 -2.824E-06 -1900.000 -8.874E-05 1930.215 -3.084E-05

NIVEL7 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=7.787499)
COMB1 -405.442 0.000 -1900.000 -4.055E-05 2381.268 1.320E-05

NIVEL8 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=8.900001)
COMB1 -403.108 1.898E-06 -1900.000 -7.126E-05 2829.726 6.048E-05

NIVEL9 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=10.0125)
COMB1 -381.736 0.000 -1900.000 -6.318E-05 3254.406 2.717E-06

NIVEL10 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=11.125)
COMB1 -339.957 1.421E-06 -1900.000 -9.312E-05 3632.609 1.100E-06

NIVEL11 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=12.2375)
COMB1 -276.092 -3.102E-06 -1900.000 -1.529E-04 3939.762 2.044E-05

NIVEL12 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=13.35)
COMB1 -188.163 1.283E-06 -1900.000 -1.221E-04 4149.093 9.334E-06

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 10 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

NIVEL13 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=14.4625)
COMB1 -73.912 0.000 -1900.000 5.175E-05 4231.319 3.758E-06

NIVEL14 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=15.575)
COMB1 69.176 0.000 -1900.000 4.365E-05 4154.361 0.000

NIVEL15 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=16.6875)
COMB1 243.857 0.000 -1900.000 1.028E-04 3883.070 -2.187E-05

NIVEL16 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=17.8)
COMB1 453.097 1.490E-06 -1900.000 -1.070E-04 3378.999 -2.714E-05

NIVEL17 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=18.9125)
COMB1 620.000 4.113E-06 -1900.000 -7.612E-05 2689.248 -1.964E-05

NIVEL18 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=20.025)
COMB1 620.000 -1.431E-06 -1900.000 -3.593E-05 1999.501 -2.057E-05

NIVEL19 (Sum at X=2.384186E-08 Y=-2.384186E-08 Z=21.1375)
COMB1 620.000 -2.825E-05 -1900.000 2.907E-05 1309.750 2.302E-06

NIVEL20 (Sum at X=2.167442E-08 Y=-2.167442E-08 Z=22.25)
COMB1 620.000 1.812E-05 -1900.000 -4.206E-05 620.000 -4.638E-06

\31. Si este archivo lo abrimos en una hoja de calculo y tabulamos los resultados

obtenidos para cada nivel obtendremos lo siguiente:

GROUP Z F-X F-Y F-Z M-X M-Y M-Z
(m.) Ton Ton Ton Ton-m. Ton-m. Ton-m.
NIVEL0 0.000 0.000 0.000 0.000 0.000 0.000 0.000
NIVEL1 1.113 -58.184 0.000 -1900.000 0.000 313.537 0.000
NIVEL2 2.225 -158.135 0.000 -1900.000 0.000 489.462 0.000
NIVEL3 3.338 -241.053 0.000 -1900.000 0.000 757.633 0.000
NIVEL4 4.450 -307.284 0.000 -1900.000 0.000 1099.487 0.000
NIVEL5 5.563 -356.925 0.000 -1900.000 0.000 1496.566 0.000
NIVEL6 6.675 -389.797 0.000 -1900.000 0.000 1930.215 0.000
NIVEL7 7.787 -405.442 0.000 -1900.000 0.000 2381.268 0.000
NIVEL8 8.900 -403.108 0.000 -1900.000 0.000 2829.726 0.000
NIVEL9 10.013 -381.736 0.000 -1900.000 0.000 3254.406 0.000
NIVEL10 11.125 -339.957 0.000 -1900.000 0.000 3632.609 0.000
NIVEL11 12.237 -276.092 0.000 -1900.000 0.000 3939.762 0.000
NIVEL12 13.350 -188.163 0.000 -1900.000 0.000 4149.093 0.000
NIVEL13 14.462 -73.912 0.000 -1900.000 0.000 4231.319 0.000
NIVEL14 15.575 69.176 0.000 -1900.000 0.000 4154.361 0.000
NIVEL15 16.687 243.857 0.000 -1900.000 0.000 3883.070 0.000

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 11 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

NIVEL16 17.800 453.097 0.000 -1900.000 0.000 3378.999 0.000
NIVEL17 18.912 620.000 0.000 -1900.000 0.000 2689.248 0.000
NIVEL18 20.025 620.000 0.000 -1900.000 0.000 1999.501 0.000
NIVEL19 21.137 620.000 0.000 -1900.000 0.000 1309.750 0.000
NIVEL20 22.250 620.000 0.000 -1900.000 0.000 620.000 0.000

\32. Obteniendose luego el Diagrama de Fuerzas cortantes y Momentos Flectores.

DIAGRAMA DE MOMENTOS DIAGRAMA DE FUERZAS
FLECTORES CORTANTES

20 20

15 15
(m.) (m.)

10 10 PROFUNDIDAD PROFUNDIDAD

5 5

0 0
\-600 -400 -200 0 200 400 600 800 -1000 0 1000 2000 3000 4000 5000

CORTANTE (Ton.) MOMENTO (Ton-m.)

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm
