---
type: libro
title: "losas_macizas_en_dos_direcciones"
author: "webmaster"
categoria: "ESTRUCTURA"
paginas: 6
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/ESTABILIDADES FADU/ESTABILIDAD 1/losas/losas_macizas_en_dos_direcciones.pdf"
convertido: 2026-10-16
---

# losas_macizas_en_dos_direcciones

> Texto extraído de `ESTRUCTURA\ESTABILIDADES FADU\ESTABILIDAD 1\losas\losas_macizas_en_dos_direcciones.pdf` (6 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Losas macizas en dos direcciones

El método de rotura que utilizaremos en este curso está condicionado a los siguientes
supuestos:

• Son losas rectangulares
λ x
• Tienen una relación de lados 5,0 ≤ ≤ 2
λ y
• Están apoyadas en sus cuatro bordes

• Están subarmadas, lo que se cumple si el acero supera el 5‰ de deformación
específica durante la rotura.

Bajo estos condicionantes podemos suponer que en una losa simplemente apoyada en la que
se aumenta la carga hasta producir su rotura se formarán líneas que parten de los vértices
pudiendo unirse en la parte central con otra paralela a uno de los bordes de apoyo.

En la foto observamos un modelo
ensayado a rotura con carga uniforme
brindada por presión neumática.
Las armaduras se han cortado luego de
superar su alargamiento específico de
rotura (unas 50 veces superior al de
fluencia).
La losa quedó dividida en trozos, y
supondremos que cada uno apoya sobre
el borde al que pertenece.
La carga uniforme equivalente sobre el
apoyo se obtiene distribuyendo el peso del
trozo en el largo del borde.

Si consideramos la continuidad estructural
de las losas entre sí o con tabiques de
HºAº podemos dividir a los bordes de
apoyo en dos tipos: continuos y
simplemente apoyados. Cuando la línea de rotura se forma entre bordes de un mismo tipo
(ambos continuos o ambos simplemente apoyados) sigue la bisectriz del ángulo que forman,
por lo que estará a 45º si forman un ángulo recto. Si son de distinto tipo formará un ángulo
menor, que podemos suponer de 30º, con el que no tiene continuidad y mayor (60º) con el
continuo. Sobre los bordes continuos se forma también una línea de rotura en la cara superior
de la losa, es por la rotación de la losa alrededor del mismo y contribuye a aumentar la carga
de rotura si hemos colocado la armadura necesaria en esa cara superior.
Veamos algunos ejemplos donde al borde continuo lo simbolizamos con un rayado.

1

<!-- p. 2 -->

ℓy

60º 45º
30º

ℓx

ℓy
y

45º 45º 30º

x
ℓx

Para determinar las armaduras de tramo y apoyos y fijar definitivamente el espesor utilizaremos
un procedimiento automatizado en su mayor parte. Se comienza trabajando con el plano de
estructura una vez que están definidos los elementos que brindan apoyo a las losas macizas y
la configuración de estas. Se decide como están armadas (una o dos direcciones) y se las
designa con un número a cada una. Se realiza el análisis de carga suponiendo que tendrán el
espesor que surge del predimensionado.
Disponiendo un sistema de ejes x, y, con el primero en horizontal, tendremos los siguientes
datos:
• La resistencia del hormigón, f’c, en MPa
• La designación de cada losa
• Luz en dirección x, en metros
• Luz en dirección y, en metros
Kg
• Carga permanente por metro cuadrado, qD, en 2
m
Kg
• Sobrecarga de uso por metro cuadrado, qL, en 2
m
• Condición de continuidad de cada uno de los cuatro bordes de apoyo
En todas las losas la luz x será la paralela al eje x adoptado, la perpendicular será la luz en y.
Para comunicar al programa la continuidad de cada borde hay que situarse en cada losa
numerando los bordes conforme al siguiente esquema:

2

<!-- p. 3 -->

2

1 3
ℓy

4

ℓx

Introducimos los datos anteriores en la planilla de losas macizas por rotura, poniendo una “s”
en los bordes con continuidad.

estructuras 2 a

Losas por método de rotura (dx = dy = h - 2cm) f'c = 15

DATOS Mom. de Empotram.
Losa qD qL ℓx ℓy Borde contínuo? "s" / "n" Mx1 My2 Mx3 My4

Kg/m² Kg/m² m m B1 B2 B3 B4 tm/m tm/m tm/m tm/m

L1 500 200 4 3,5 s 0 0 -0,762 0

L2 500 200 4 3,5 s s -0,633 0 -0,633 0

Obtenemos los Mom. de Empotram., que equivalen, sin serlo, a los momentos de
empotramiento perfecto de cada borde de losa en que indicamos que había continuidad.
En la planta de estructura anotamos esos valores dentro de la losa respectiva y sobre el lado
que corresponde.
En general tendremos dos valores distintos sobre un mismo borde y a cada lado del mismo
según la losa que consideremos, y sabemos que el valor del momento de apoyo, por equilibrio,
tiene que ser el mismo. Procedemos entonces a adoptar un valor único para cada borde. Si los
valores a ambos lados difieren poco lo más apropiado es tomar el promedio multiplicado por
0,85. Si hubiera una marcada diferencia habrá que ver que es lo más apropiado desde el punto
de vista de la seguridad.
Un caso particular lo constituyen los voladizos, allí el momento a adoptar es el del voladizo por
una cuestión de equilibrio del mismo.

Veamos un ejemplo:

3

<!-- p. 4 -->

Consideraremos la terraza del salón de usos múltiples de la casa Koshino, de Ando Tadao. En
la volumetría se indica con un óvalo.

.

qD = 500 Kg/m² qL = 200 Kg/m²

3,50 1 2 1
m

4,00 m 4,00 m 4,00 m

Losa 1 Losa 2

4

<!-- p. 5 -->

(,0 762 + ,0 63 )
− ,059 = − ,085
MOMENTOS 2
DATOS APOYOS

V1 V2 V1

\- -
0,762 0,63
tm/m tm/m

Momentos obtenidos

(,0762 + ,063 )
− ,059 = − ,085 ( ,0762 + ,063)
− ,059 = − ,085 2
2 Momentos adoptados

\-
0,59
tm/m

5

<!-- p. 6 -->

Completados los datos de momentos de borde y espesor adoptados, se obtienen las
armaduras en tramo y apoyo.

db 8 c/25
db

6
1,42 1,36
c/18
db 6 c/19

0,60 t/m 0,48 t/m

1,71

0,55 0,88 0,85
0,748 t/m t/m t/m

1,71
1,376 48º 34,8º 34,5º

1,54 2,46 2,00

6
