---
type: libro
title: "Sap2000-Manualalbañileria"
author: ""
categoria: "AYUDAS DE PROGRAMAS"
paginas: 7
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/Sap2000-Manualalbañileria.pdf"
convertido: 2026-10-16
---

# Sap2000-Manualalbañileria

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\Sap2000-Manualalbañileria.pdf` (7 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

ANALISIS DE ESTRUCTURA EN ALBAÑILERIA (ELEMENTO PORTANTE "MUROS")

Para modelar una estructura de albañilería en el programa de computo SAP2000 se procede ha
generar los elementos portantes como elementos FRAME estando empotrados en la base y libres en
el otro extremo

Muros de ladrillos combinados con muros de concreto armado

Parámetros Dinámicos
Z = 0.40 (Lima)
U= 1.00 (Categoría C)
S = 1.20 (Tipo 2) Tp = 0.60

Solución.-

1.- Dibujar planta de edificación de los centros de gravedad de los elementos portantes de la
estructura en AUTOCAD, incluyéndole su elevación.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 2 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

2.- Grabar en capa requerida por SAP 2000
LAYER – SAP_FRAMES

3.- Exportar con formato de extensión DXF. del AUTOCAD
FILE – EXPORT – (nombre de archivo).DXF

4.- Importar con extensión DXF. al SAP2000.
En el menú principal FILE – IMPORT - (nombre de archivo) con extensión DXF

5.- Asignar coordenadas en X,Y,Z, a la estructura a importar, verificar unidades en cuadro inferior,
que estén en Ton-m.

6.- Ingreso de propiedades de los materiales a usarse como: MASA (Si se quiere considerar la
masa del elemento para el análisis y diseño) DENSIDAD, MODULO DE ELASTICIDAD,
RADIO DE POISSON, en el menú principal se hará en menú principal
Define – Materials - Add New Material

Mass = 0.00 Ton/m2
Weight = 1.8 Ton/m2
Modulo de elasticidad = 500000 Ton/m2
Modulo poisson = 0.3

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 3 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

7.- Definir secciones de cada elemento estructural, dándole sus propiedades respectivas a cada
elemento. (Largo, Espesor de Sección) En el menú principal DEFINE – FRAME SECTIONS

8.- Definir los casos de cargas propias, muertas y vivas, que se tendrán en la estructura. En el menú
principal DEFINE y en el submenú STATIC LOAD
CASES (1) se tipea la clase de carga que va ha definir,
(2) se define en el cuadro extendible la clase de carga
que se aplicará, (3) se tipea en Self Weight Multiplier
1 para considerar las cargas por peso propio en ésta
selección, ó 0 para no tomar en cuenta en la carga
definida el peso cuando se define en el peso propio.

9.- Ingreso de Espectro de diseño de estructura con el Periodo Vs. Magnitud FUNC1.En el menú
principal se escoge Define – Response Spectrum Functions – Add New Function. En el
casillero de Time se tipea el periodo de la estructura, seguido de su magnitud.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 4 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

10.- Definir casos de respuesta de espectro. Para escoger los casos de respuesta se selecciona del
menú principal Define – Response Spectrum Cases – Add New Spectra. Se introduce en
Damping para estructuras de concreto Armado es de 0.09 en la ventana de respuesta de
espectro se selecciona en la ventana de respuesta de espectro FUNC1 para la dirección U1 y se
repite para la dirección U2.

11.- Asignar restricción de empotramiento en la base de toda la estructura. Seleccionar toda la base
colocarse en el plano XZ mostrar la perspectiva click , luego en el menú principal
View - Set 3D View cerrar la apertura 5 Casillero de APERTURE.
Seleccionar toda la base en el menú principal Assign - Joint - Restraints o mediante el
icono en la barra de herramientas marcar todos los casilleros.

12.- Asignar la masa de cada piso al nudo maestro de la estructura, ingresando en el sentido donde
va ha actuar (X (Direction 1) e Y (Direction 2) ) y el momento de inercia rotacional de las
masas en la dirección Z (Rotation about 3). En el Menú principal Assign - Joint - Masses

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 5 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

13.- Asignar secciones a los elementos estructurales, seleccionar los muros representados por
elementos frame. En el Menú principal ASSIGN – FRAME - SECTIONS, click name
seleccionar muro definido, repetir procedimiento para seleccionar todos los muros.

14.- Seleccionar los nudos de los elementos por piso para que se desplacen juntos con la opción
en el menú principal Assign - Joint - Constraints – Diaphragm para cada piso se asigna un
diafragma diferente. Nos ubicamos en el último piso Add Diaphragm, en el casillero en
blanco se tipea DIAPH1 y se hace click 2 veces O.K. y repite para cada piso.

15.- Visualizar estructura con las propiedades de la secciones
VIEW – SET ELEMENTS
– CHECK SHOW EXTRUSIONS

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 6 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

16.- Analizar Estructura Modelada Con Sus Respectivas Secciones (Analyze)
Ingresar opciones de análisis, estructura en el espacio o en el plano, número de modos de
vibración
ANALYZE – SET OPTIONS – SET DYNAMIC PARAMETERS

17.- Analizar la estructura. En el menú principal ANALIZE – RUN o con la opción grafica de

18.- Revisar los resultados obtenidos del análisis, desplazamientos
de la estructura.
DISPLAY – DEFORMED SHAPE
Para visualizar la estructura sin deformar se accede mediante
el icono de

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm

<!-- p. 7 -->

ING. EDUARDO RIVERA REYES
CONSULTOR DE PUENTES Página Web: www.puentesrivera.es.fm

19.- Visualisar las formas de modo de vibración.
En el menú principal DISPLAY – SHOW MODE SHAPE o con la opción grafica de

20.- Visualizar fuerzas y esfuerzos en los elementos
En el menú principal DISPLAY –
SHOW ELEMENT FORCES/STRESSES

21.- Ver las fuerzas cortantes en la base de la estructura por grupo
En el menu principal ASSIGN – GROUP NAME –
Add new Group Name seleccionar los nudos en la
base de la estructura y las columnas que llegan.

22.- Los desplazamientos Máximos
∆ / hentrepiso > desplazamiento permitido. Para obtener
los desplazamientos reales de la estructura se hace
Click derecho en cada nudo de cada piso y se
compara con los desplazamientos máximos.

E-mail: erivera@terra.com.pe Telefax: 226-1435 - Lima Perú
www.puentesrivera.es.fm
