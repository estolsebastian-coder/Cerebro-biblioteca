---
type: libro
title: "etabs-autocad-tutorial"
author: "Propietario"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 11
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/curso SAP 2000/etabs-autocad-tutorial.pdf"
convertido: 2026-10-16
---

# etabs-autocad-tutorial

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\curso SAP 2000\etabs-autocad-tutorial.pdf` (11 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Import DXF

Etabs nos permite de una forma rápida y precisa la estructuración de modelos
complejos, importando desde Auto CAD archivos DXF existentes, acomtinuacion
veremos los pasos a seguir para dibujar un modelos de un edificio de muros de
mampostería, del cual tenemos la planta en formato DWG de Auto CAD del mismo nos
interesa las líneas de los Muros y Gris. Para su diseño en ETABS.

A. Primera Parte, Trabajando con AutoCad, Cargar el programa.

1.- Abrimos el Archivo Existentes en Auto CAD, Ejemplo File-Open y buscamos la
carpeta donde esta contenido el Archivo (Edificio Apartamentos Calculo). Figura A.

Figura A

2.- la figura B, Muestra la Vista en Planta del dibujo. Si no disponemos del archivo
procedemos a dibujar la planta de conjunto en Auto CAD.

<!-- p. 2 -->

Figura B

3.- Procedemos Crear un layer para Dibujar las líneas de los ejes de los muros Ejemplo
L-Muro y otro leyer para los Gris, (podemos Elegir cualquier nombre para designar los
Leyers), En la barra de herramientas Object Properties, pulsar sobre layer, Ver Figura C,
en el cuadro de dialogo Layer Properties manager, Pulsar sobre New, escribir el
Nombre del layer Ejemplo, Lmuro, definir un color para el Layer (White). Lo Mismo
hacemos para el Layer Gris, luego Pulsamos OK.
Tenemos dos Layer nuevo, seleccionamos el Layer Lmuro en la barra desplegable layer.

<!-- p. 3 -->

Figura C.

4.- Continuación procedemos a dibujar las líneas de los ejes de los muros en el Layer
Lmuro, utilizando el comando Line, en el centro del muro, o con en comando Offset a
una distancia igual a la mitad del espesor del muro, en este caso luego deberemos de
cambiar la propiedad de la línea a la del Layer Lmuro. Al finar tendremos dibujadas
todas las líneas correspondientes a los ejes de los muros ver Figura D.

Figura D.
5.- Seleccionamos el Layer Gris de la barra desplegable layer y procedemos a dibujar
una línea por cada Eje de muro, procurando que la línea sea continúa de un extremo del
dibujo al otro y todas del mismo largo, para que los Gris en ETABS se visualicen todos
iguales. Ver figura E.

<!-- p. 4 -->

Figura E.

6.- Para hacer coincidir los Ejes de referencia de Auto CAD con los de ETABS,
debemos mover el dibujo al origen de Coordenadas 0,0,0 en el punto donde deseamos
ubicar el Origen. Para ello seleccionamos todo el dibujo, pulsamos sobre el icono
Mover, luego damos un clip en el punto de origen, escribimos 0,0,0 en la línea de
comando y pulsamos Entre, El dibujo se moverá al punto señalado.

7.- Continuación Procedemos a Salvar el dibujo en formato DXF de Auto CAD,
pulsamos sobre el menú Files, seleccionamos Save As, en el cuadro de dialogo Save
Drawing As, pulsamos sobre Files Of Type y seleccionamos AutoCad 2000 DXF.
Seleccionamos la Carpeta donde deseamos ubicar el Archivo y listo. (Figura F)

Figura F.

Ya podemos finalizar AutoCad y proceder a Importar desde ETABS. El archivo DXF
correspondiente.

<!-- p. 5 -->

B. Segunda Parte, Trabajando con ETABS v8, Cargar el programa.

1.- Seleccionar una unidad de medida en metro (Ton-m), Luego en la barra de menú
pulsar en file, en el menú desplegable Seleccionar Import. Y luego seleccionar la opción
DXF Floor plan (Figura G).

El programa nos pide el tipo de inicialización para el nuevo modelo, usar Defaulf.edb

Figura G.

2.- Pasamos al cuadro de dialogo Import DXF File de la figura H.
Buscamos la ruta de absceso donde se encuentra el archivo DXF, Salvado en Autocad
Ejemplo Edificio apartamentos Cálculo y pulsamos sobre Abrir.

<!-- p. 6 -->

Figura H.

3.- En el cuadro de dialogo siguiente (Figura I), seleccione el leyer que primero desea
importar, en Beams seleccione el leyer Lmuro, en Plan Location seleccione el nivel
donde se desee ubicar las líneas de los muros Ejemplo Base. Usar la dirección por
defecto del eje Z. presione OK.

<!-- p. 7 -->

Figura I.

\4. ETABS genera las líneas de los muros dibujados en AutoCad, en el nivel señalado y
con los ejes de referencia en la coordenada indicada. (Figura J)
Continuación Procedemos a configurar la altura de los niveles así como la cantidad
deseada.

Figura J.

Figura K.

<!-- p. 8 -->

En el menú Edit seleccionamos Edit Store Data a continuación de Edit Store, en el
cuadro de dialogo de la figura K, se define las alturas de los piso Ejemplo 2,8 MT.,
además de el piso master, ejemplo Story1. Aquí podemos cambiar el nombre de los
pisos.
De igual forma en Edy Store data seleccionamos Delete Store, Marcamos el Story4 y
presionamos sobre OK. Para borrar el nivel 4. Y tener solo 3 niveles.

4.- Ahora vamos a proceder a generar los muros del edificio para los tres niveles.
En la ventana izquierda de la vista en planta de la figura J con el Mause marcamos todas
las líneas de muro, continuación en el menú Edit seleccionamos Extrude lines To
Áreas. En el cuadro de dialogo de la figura L, Seleccionamos Linear. Usamos los
siguientes valores

Dx = 0
Dy = 0
Dz = 2.8

Numero de Piso = 3

Marcamos la casilla delete Source Objects para eliminar las líneas de muros en el
modelo.

Figura L.

<!-- p. 9 -->

5.- ETABS nos genera un modelo con las áreas de los muros Figura M.

Figura M.

\6. A continuación procedemos a importar los Gris para poder obtener las distintas
elevaciones de los muros.

Figura N
En el Menú File de la figura N, seleccionamos Import, y luego DXF File Of
Architectural Gris buscamos el archivo dxf hecho en Auto Cad y presionamos Abrir.
.

<!-- p. 10 -->

Figura O.

En el cuadro de dialogo de la figura O, seleccionamos el layer Grid y Presionamos OK.
Etabs generas los Gris para los diferentes ejes de los muros. (Figura P)

Figura P.

<!-- p. 11 -->

Los pasos siguientes serian definir las secciones de los Muros, losas etc., así como los
materiales, dibujar las losas, aplicar las cargas y demás funciones de ETABS.
La figura Q muestra el trabajo terminado.

Como podemos ver es sumamente rápido la generación de estructuras usando archivos
existentes de AutoCad.

Figura Q.

Preparado por:
Ing. Federico Rojas
Inrroca@hotmail.com
