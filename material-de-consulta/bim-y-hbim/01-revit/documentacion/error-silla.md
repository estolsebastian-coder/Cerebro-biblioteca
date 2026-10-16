---
type: libro
title: "error silla"
author: ""
categoria: "BIM Y HBIM"
paginas: 1
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/DOCUMENTACIÓN/error silla.pdf"
convertido: 2026-10-16
---

# error silla

> Texto extraído de `BIM Y HBIM\01. Revit\DOCUMENTACIÓN\error silla.pdf` (1 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Manual de Revit

_problema visualización de silla sobre mesa

01_ Situación inicial, en vista de plantas la silla
se superpone por sobre la mesa, error en las
regiones de máscara y planos de trabajo.

Como sabemos, ambas familias poseen dife-
rente cota, donde por un lado la mesa tiene
una referencia altimétrica final más elevada
que el asiento de la silla.

regiones de máscara y planos de referencia
02_ Evaluar la posición de las regiones de
máscara de ambos elementos. Por un lado, la
mesa debe contar con una región de máscara
asociada a un plano de referencia en su tapa.
Por el otro, en la silla se debe verificar que su
región de máscara este realizada en la parte
del asiento.

( la verificación se hace dentro de cada familia )

03_Una vez corroborado la existencia de estas
máscaras de recorte y su posición debemos
corregir su posición de anotación.

Lo que suele ocurrir es que la región de más-
cara de la silla, estando dibujada en el plano
correspondiente posee la restricción de
DIBUJAR EN PRIMER PLANO.

Para corregir este error debemos hacer que no
se dibuje dicha región en primer plano, sino
que en el plano que fue dibujada.

\- seleccionar la región de máscara y líneas de deta-
lle de la familia silla. (filtrar selección con la herra-
mienta “filtro”)

\- hacer clic en el símbolo de “=” a la derecha de
“dibujar en primer plano” en la paleta de propieda-
des.

\- una vez dentro de los parámetros, seleccionar la
opción “ninguno”en la ventana emergente.

\- habiendo seleccionado dicha condición, al cerrar la
ventana emergente se nos habilitará la opción de
desmarcar DIBUJAR EN PRIMER PLANO solucionan-
do el error.

\- cerrar y guardar los cambios dentro de la familia
de la silla. ¡ problema resuelto !
