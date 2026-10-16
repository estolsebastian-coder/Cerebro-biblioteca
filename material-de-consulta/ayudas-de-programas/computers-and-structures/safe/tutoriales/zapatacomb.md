---
type: libro
title: "Zapatacomb"
author: "your name"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 15
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/SAFE/Tutoriales/Zapatacomb.pdf"
convertido: 2026-10-16
---

# Zapatacomb

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\SAFE\Tutoriales\Zapatacomb.pdf` (15 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

SAFE Problema 2
Combinado Pagando

Propiedades de Fundamento de hormigón
E = 3600 ksi, Proporción de Poissons = 0.2, Peso de la Unidad = 150 pcf
f'c = 4 ksi, fy = 60 ksi
Los X dirección cima rebar cubren = 3” (al centroide del rebar)
Los Y dirección cima rebar cubren = 2” (al centroide del rebar)
Los X dirección fondo rebar cubren = 3.5” (al centroide del rebar)
Los Y dirección fondo rebar cubren = 4.5” (al centroide del rebar)
Las columnas concretas son 18” a través de 18.”

Ensucie Propiedades
Módulo del Subalterno-calidad = 200 kcf

Para Hacer
Use el código ACI 318-95. Ejecute el análisis que usa la opción de iteración de levantamiento.
Repase la distribución de presión de tierra. Repase los desplazamientos del fundamento
verticales elásticos bajo DL un-factorizado + LL + la carga de EQ. Repase el pagando factorizado
los momentos. Repase el pagando calculado reforzando.

PLANTA

ELEVACION

<!-- p. 2 -->

Problema 2 Solución

\1. Pulse el botón la gota abajo la caja en la barra de estado cambiar las unidades al kip-ft.

\2. Del menú File seleccione New Model From Template….Esto despliega la Tabla
Las plantillas dialogan caja.

\3. En esta caja del diálogo:

Pulse el botón Combined Footing para desplegar el Pagando Combinado
la caja del diálogo.

• En esta caja del diálogo:

Teclee 3 la del en el del de Distancia Borde Izquierda, la Distancia de Borde de
Derecho, Distancia de Borde de Cima y Distancia del de Borde el Fondo revisan
cajas (4 revisan del diferente el del cajas del las total).

En las áreas del Espacio verifica que la opción de X se selecciona.

Teclee 20 en el Espacio revise caja.

Para Load 1 150 en el PDEAD revisa caja y teclea 75 en el PLIVE revise caja.

Nota: Cuando el pagando combinado se define en el X-dirección (i.e., la opción de X se
selecciona en el área del Espacio) entonces Carga 1 es la columna izquierda que carga y
Carga 2 es la carga de la columna correcta. Los Cuando el pagando combinado se
definen el de en de entonces el Y dirección que Carga 1 es la columna del fondo que
carga y Carga 2 cargas de la de es de la columna de la cima.

Para Carga 2 tipo 150 en el PDEAD revisa caja y teclea 75 en el PLIVE revise
caja.

Teclee 3 en el Footing Thickness revise caja.

Teclee 200 en el Soil Modulus revise caja.

<!-- p. 3 -->

Teclee 1.5 en el Load Size (Cuadrado) revise caja. Puesto que las unidades son
kips y pies los 1.5 es equivalente a 18 pulgadas. La caja del diálogo aparece ahora
como mostrado en Figura 2.1.

Pulse el botón de OK.

Figura 2-1: Combined Footing Caja del Diálogo

\4. Del menú Define seleccione Static Load Cases…para desplegar la Carga Caso
Nombres diálogo caja Estática.

\5. En esta caja del diálogo:

• Digite EQ en la caja Load Edit.

• Seleccione QUAKE del Tipo drop-down la caja.

• Digite 0 en el Self Weight Multiplier.

• Digite 1 en el Long Term Deflection Multiplier.

• Pulse el botón Add New Load.

• Pulse el botón de OK.

\6. Del menú Define seleccione Load Combinations... desplegar las Combinaciones de
Carga dialogan caja.

<!-- p. 4 -->

\7. En esta caja del diálogo:

• Pulse el botón Add New Combo abrochan para desplegar los Datos de
Combinación de Carga dialogo caja.

• En esta caja del diálogo:

Escriba DISPL (corto para el desplazamiento) en el Load Combination
Name revise caja.

Digite DL + LL + EQ Para los Displasements en el Título revisan caja.

En el Nombre del Caso drop-down la caja verifique DL Carga Caso se
selecciona.
Verifique que en 1 se entra en el Scale Factor revise caja.

Pulse el botón Add.

Seleccione LL Load Caso del Nombre del Caso gota-abajo la caja.

Pulse el botón Add.

Seleccione EQ Load Caso del Nombre del Caso gota-abajo la caja.

Pulse el botón Add.

Pulse el botón de OK dos veces para terminar todas las cajas del diálogo.

\8. Pulse el botón en el objeto del punto (elemento de la juntura) a la reja intersección A-1
para seleccionarlo. Cuando la juntura se selecciona mirada al lado de la izquierdo-mano
de la barra de estado al fondo de la ventana SAFE y verifica que dice “1 Junturas
seleccionaron.”

\9. Del menú Assign seleccione Point Load desplegar el Punto Carga caja del diálogo.

\10. En esta caja del diálogo:

• Seleccione EQ Load en Load Case Name gota-abajo la caja.

• En el área de Cargas tipo Carga Vertical 100 en la revisa caja.

Nota: En SAFE, las cargas verticales positivas actúan que se extiende hacia abajo.

• En el Size Load área de tipo 1.5 en la Dimensión de X y la Dimensión de Y
revisa cajas.

<!-- p. 5 -->

• Pulse el botón de OK para asignar esta carga del punto.

\11. Pulse el botón en el objeto del punto (elemento de la juntura) a la reja intersección
B-1 para seleccionarlo.

\12. Del menú Assign seleccione Point Loads…desplegar el Punto Carga caja del
diálogo.

\13. En esta caja del diálogo:

• Verifique EQ Load en Load Case Name gota-abajo la caja.

• En el área de Cargas tipo Carga Vertical -100 en la revisa caja. El signo menos se
usa porque esta carga del terremoto está actuando a.

• En el Tamaño de área de Carga verifica que la Dimensión de X y Dimensión de Y
son 1.5.

• Pulse el botón de OK para asignar esta carga del punto.

\14. Pulse el botón 3D View en la barra de herramientas principal conseguir una
vista mejor de las cargas del punto aplicadas.

\15. Pulse el botón 2D View en la barra de herramientas principal devolver a una
vista del plan.

\16. Pulse el botón Show Undeformed Shape para quitar las cargas del punto
desplegadas.

\17. Pulsa el botón derecho en la fundación para desplegar la Tabla Información diálogo
caja Rectangular.

\18. En esta caja del diálogo:

• En la nota de áreas de Característica técnicas que la Propiedad de la Tabla que se
llama FOOTING. Esta propiedad de la tabla fue creada y fue aplicada por la
plantilla del footing combinada.

• En la nota de área de Característica técnicas que el Apoyo es TIERRA. Esta
propiedad de apoyo fue creada y fue aplicada por la plantilla del footing
combinada.

• Nosotros verificaremos estas propiedades y si el requisito los modifica reunir
nuestros propios requisitos en los pasos siguientes.

<!-- p. 6 -->

• Pulse el botón de Cancel para cerrar la caja del diálogo.

\19. Pulse el botón la gota abajo la caja en la barra de estado cambiar las unidades a

Kip-in.

\20. Del menú Define seleccione Slab Properties... desplegar las Propiedades de la Tabla
dialogan caja.

\21. En esta caja del diálogo:

• En el Tabla Propiedad área momento culminante la propiedad nombró FOOTING
y entonces pulsa el botón Modify/Show Property para desplegar los Datos de
Propiedad de Tabla dialogo caja.

• En esta caja del diálogo:

En el Análisis Propiedad Datos área:

Verifique que el Modulus of Elasticity es 3600.

Verifique que la Poisson’s ratio es 0.2.

Nota: Nosotros verificaremos el peso de la unidad después.

Verifique que el Bending Thickness (X), Bending Thickness (Y) y Twisting
Thickness son todos los 36.

Nota: Estos valores legan todos es 36 porque nosotros entramos en el espesor del
fundamento el Pagando Combinado la caja del diálogo en Paso 3.

Verifique que la opción de Slab Type sea selecciona.

Verifique que la caja de Thick Plate check se verifica.

Nota: Verificando la caja de chequo Espesor de Plato dice al programa considerar
deformaciones de esquila de tabla en el análisis. Si esta caja no se verifica entonces que
las deformaciones de esquila de tabla no son incluidas en el análisis.

En el Plan Propiedad Datos área:

Verifique que el Thickness es 36.

Teclee 3 en la X Cover Top (a Centroide) revise caja.

<!-- p. 7 -->

Teclee 2 en la Y Cover Top (a Centroide) revise caja.

Teclee 3.5 en el X Cover Bottom (a Centroide) revise caja.

Teclee 4.5 en el Y Cover Bottom (a Centroide) revise caja.

Verifique la Concrete Strength, f'c es 4.

Verifique la Reinforcing Yield Stress, fy es 60.

Verifique que el No Design check no se verifica.

Pulse el botón de OK dos veces.

\22. Pulse el botón la gota abajo la caja en la barra de estado cambiar las unidades al kip-

ft.

\23. Del menú Define seleccione Slab Properties... desplegar las Propiedades de la Tabla
dialogan caja.

\24. En esta caja del diálogo:

• En el Tabla Propiedad área momento culminante la propiedad nombro
FOOTING y entonces pulsa el botón Modify/Show Property para desplegar los
Datos de Propiedad de Tabla dialogo caja.

• En esta caja del diálogo:
Verifique que el unit weight es 0.15.

Pulse el botón de OK dos veces para terminar todas las cajas del diálogo.

\25. Del menú Define seleccione Soil Supports... desplegar las Propiedades de Apoyo
dialogan caja.

\26. En esta caja del diálogo:

En el Apoyo Sostenes área momento culminante la propiedad nombró SOIL y entonces
pulsa el botón Modify/Show Property para desplegar los Tierra Apoyo Propiedad Datos
dialogo caja.
En esta caja del diálogo:

Verifique que el subgrade modulus es 200.

<!-- p. 8 -->

Nota: Este valor será 200 porque nosotros entramos en el módulo de subalterno-calidad
de tierra en el Combinado Pagando caja del diálogo en Paso 3.

Pulse el botón de OK dos veces para terminar todas las cajas del diálogo.

\27. Del menú Options seleccione Preferences... y entonces selecciona Desing, Concrete
Tab.

\28. En esta caja del diálogo:

• Verifique que ese ACI 318-95 se selecciona en el Código del Plan Concreto gota-
abajo la caja.

• Verifique Reinforcement Results Units area the Sq-in y Sq-in/ft opción
seleccionaron.

• Pulse el botón de OK.

\29. En el menú Desing elija Select Design Combos para desplegar la Carga del Plan
Combinaciones Selección diálogo caja.

\30. En esta caja del diálogo:

• En el Plan Combos listan caja pulse el botón en DCON2 para resaltarlo y
entonces pulse el botón de Show.

• Note que esta combinación de carga se define como 1.4DL + 1.7LL. También
nota que el Uso para la caja de cheque de Plan se verifica.

Nota: SAFE automáticamente crea combinaciones de carga de plan basadas en el código
del plan seleccionado y en los tipos de carga estáticos. En este caso donde los tipos de
carga estáticos definidos están MUERTOS y VIVO y TERREMOTO (vea Static Load
Cases del menú Define) y el código del plan es ACI 318-95, el programa crea seis casos
de carga automáticamente. Ellos tienen 1.4DL años (DCON1) y 1.4DL + 1.7LL
(DCON2), 1.05DL + 1.275LL + 1.4025EQ (DCON3), 1.05DL + 1.275LL - 1.4025EQ
(DCON4), 0.9DL + 1.43 EQ (DCON5), y 0.9DL - 1.43 EQ (DCON6).

Si nosotros quisiéramos agregar una combinación de carga de plan adicional que
nosotros podríamos definirlo seleccionando Load Combinations... del menú Define y
entonces pulsando el botón Add New Combo, desplegar los datos de Combinación de
Carga dialogan caja. En esta caja del diálogo nosotros podemos definir la combinación
de carga y nosotros podemos verificar el Uso Para la caja de cheque de Plan si nosotros
queremos usar la combinación de carga en plan.

<!-- p. 9 -->

• Pulse el botón de OK dos veces para terminar todas las cajas del diálogo.

\31. Del menú Analyze seleccione Set Options para desplegar las Opciones del Análisis
dialogo caja.

\32. en esta caja del diálogo:

• En el área de Tipo de Análisis seleccione la opción Iterative For Uplift.

• Acepte los valores predefinidos en el Levantamiento Iteración Parámetros área.

Nota: La Tolerancia de la Convergencia predefinida, 0.001, debe mantener exactitud
suficiente la mayoría de los problemas. El Número del Máximo predefinido de
Iteraciones, 10, no puede mantener exactitud suficiente muchos problemas. Pueden
requerirse iteraciones adicionales. Estos términos se definen en Paso 35.

• Acepte la dimensión de malla de máximo predefinida (maximum mesh
dimension) de 4 pies.

Nota: para enredar automáticamente primero al modelo el programa desarrolla una malla
que está roto en cada línea de la reja, al borde de cualquier área objeta, a los extremos de
cada línea objete y a cada objeto del punto. Si la dimensión de cualquier elemento
enredara de esta manera excede la dimensión de malla de máximo especificada entonces
esos elementos se subdividen tal que la dimensión de malla de máximo ya no se excede.

Nota: en general, el tamaño de malla de máximo debe ser basado en la longitud del
palmo. Es práctica buena para tener cuatro elementos por lo menos en un palmo, y
generalmente no es necesario tener más de ocho elementos en un palmo. Así si la
longitud del palmo típica está menos de dieciséis pies, puede ser aconsejable reducir el
tamaño de malla de máximo predefinido a algo menos de 4 pies.

Nota: La malla automáticamente generada por el programa puede ser vista pulsando el

botón Set Objects en la barra de herramientas principal (o seleccionando Set
Objects Options… del menú View) desplegar la caja de diálogo de Objetos Fija,
verificando el Show Mesh cheque caja en el área de las Opciones, y pulsando el botón el
botón de OK. Usted puede apagar el despliegue de la malla un-verificando esta caja.

• Pulse el botón de OK.

\33. Pulse el botón Run Analyze en la barra de herramientas principal (o el Run
Analyze selecto del menú Analyze).

<!-- p. 10 -->

\34. Cuando el análisis inicial es cheque completo los mensajes en la ventana del Análisis
(debe haber ninguna advertencia o errores) y entonces pulsa el botón de OK para cerrar
la ventana del Análisis. El programa procederá hacer las iteraciones para el levantamiento
entonces.

\35. Cuando las iteraciones para el levantamiento están completas una Levantamiento
Análisis Estado ventana similar a eso mostrado en Figura 2-2 aparecerá dando
información sobre qué bien las iteraciones del levantamiento convergió.

Figura 2-2: Estado de Análisis de Levantamiento que Usa un Máximo de 10 Iteraciones

Nota: hay cinco columnas en la Levantamiento Análisis Estado ventana etiquetó Combo,
ConErr, ConTol, Iteraciones y MaxIters respectivamente. Los datos en esta ventana
serán leídos en filas. La columna de Combo identifica la combinación de carga. La
columna de ConErr es el error de la convergencia al final de las iteraciones del
levantamiento. El error de la convergencia se define como el máximo tensión tensor
dividida por la media tensión donde la media tensión es PTOTAL / ATOTAL. La
columna de ConTol es la tolerancia de la convergencia usuario-definida, en otras
palabras, el error de la convergencia aceptable o aceptable. Este valor es definido por la
Convergencia Tolerancia artículo entrada en el Levantamiento Iteración Parámetros área
en las Opciones del Análisis dialoge caja (menú Analyze > Set Options). La columna de
MaxIters es que el número del máximo usuario-definido de iteraciones realizado antes
de la iteración del levantamiento se detiene, aunque no ha convergido. Este valor es
definido por el Número del Máximo de entrada de artículo de Iteraciones en el
Levantamiento Iteración Parámetros área en las Opciones del Análisis dialoge caja menú
(Analyze > Set Options). La columna de las Iteraciones dice que cuántas iteraciones
realmente se realizaron para la combinación de carga especificada. Se realizan iteraciones
de análisis de levantamiento hasta o la tolerancia de la convergencia está satisfecho, o el
número del máximo especificado de iteraciones se alcanza.

\36. La Levantamiento Análisis Estado ventana indica que la tolerancia de la convergencia
no ha estado satisfecha para combinaciones de carga DCON5 y DCON6. Para ver el
efecto de esto no la convergencia nosotros veremos las presiones de la tierra.

<!-- p. 11 -->

\37. Pulse el botón el “X” en la esquina diestra superior de la Levantamiento Análisis
Estado ventana para cerrarlo.

\38. Pulse el botón Show Joint Reactions abrochan en la barra de herramientas
principal (o seleccione Show Reaction Forces… del menú Display) desplegar la Juntura
Fuerza caja del diálogo.

\39. En esta caja del diálogo:

• Seleccione DCON5 Combo de la Carga gota-abajo la caja.

• En el Type of Load seleccione la opción de Soil Pressure.

• Pulse el botón de OK para desplegar el diagrama de presión de tierra.

\40. Ejecute el cursor del ratón encima de la tierra presión diagrama contorno parcela y lea
los valores del lado de la izquierdo-mano de la barra de estado al fondo de la ventana
SAFE. Nota que el valor mínimo es aproximadamente -0.145 ksf (tensión). Si las
iteraciones hubieran convergido totalmente, eso es el error de la convergencia había
alcanzado cero, entonces este valor del mínimo sería 0 ksf, es decir, ninguna tensión.
Nosotros ejecutaremos el análisis que de nuevo usa más iteración para mejorar esta
convergencia.

\41. Pulse el botón Lock/Unlock Model en la barra de herramientas principal abrir
al modelo.

\42. Del menú Analyze seleccione Set Options para desplegar las Opciones del Análisis
dialogo caja.

\43. En esta caja del diálogo:

• En el Uplift Iteration Parámetros área tipo 100 en el Número del Máximo de
Iteraciones revisa caja.

• Pulse el botón de OK.

\44. Pulse el botón Run Analyze en la barra de herramientas principal (o el Run
Analyze selecto del menú Analyze).

\45. Cuando el análisis inicial es cheque completo los mensajes en la ventana del Análisis
(debe haber ninguna advertencia o errores) y entonces pulsa el botón de OK para cerrar
la ventana del Análisis. El programa procederá hacer las iteraciones para el levantamiento
entonces.

<!-- p. 12 -->

\46. Cuando las iteraciones para el levantamiento están completas una Levantamiento
Análisis Estado ventana similar a eso mostrado en Figura 2-3 aparecerá dando
información sobre qué bien las iteraciones del levantamiento convergió.

Figura 2-2: Estado de Levantamiento Análisis que Usa un Máximo de 100 Iteraciones

\47. Aviso que todas las combinaciones de carga se convergen, y que tomó 63 iteraciones
para combinaciones de carga DCON5 y DCON6 converger.

\48. Pulse el botón el “X” en la esquina diestra superior de la Levantamiento Análisis
Estado ventana para cerrarlo.

\49. Pulse el botón Show Joint Reactions abrochan en la barra de herramientas
principal (o seleccione Show Reaction Forces… del menú de Display) desplegar la
Juntura Fuerza caja del diálogo.

\50. En esta caja del diálogo:

• Seleccione DCON5 Combo de la Carga gota-abajo la caja.

• En el Type of Load seleccione la opción de Soil Pressure.

• Pulse el botón de OK para desplegar el diagrama de presión de tierra.

\51. Ejecute el cursor del ratón encima de la tierra presión diagrama contorno parcela y lea
los valores del lado de la izquierdo-mano de la barra de estado al fondo de la ventana
SAFE. Nota que el valor mínimo es aproximadamente -0.002 ksf (tensión). Ésta es una
aproximación muy buena para poner a cero tensión.

\52. Pulse el botón en la ventana de vista de plan para asegurarse que es activo.

\53. Pulse el botón Show Static Deformed Shape en la barra de herramientas
principal (o Show Deformed Shape...del menú Display) para desplegar la caja de
diálogo de Forma Deformada.

<!-- p. 13 -->

\54. En esta caja del diálogo:

• DISPL Combo selecto de la Carga gota-abajo la caja.

• En el área de Opciones de Display verifique que el Displacement Contours que
la caja del chequeo se verifica.

• Pulse el botón de OK para desplegar la forma deformada.

\55. Mueva el cursor del ratón encima de los elementos de la tabla y lea el desplazamiento
valora en el lado de la izquierdo-mano de la barra de estado al fondo de la ventana SAFE.
Note que estos desplazamientos están en pies.

\56. Pulse el botón la gota abajo la caja en la barra de estado cambiar las unidades a

Kip-in.

\57. Mueva el cursor del ratón encima de los elementos de la tabla y lea el desplazamiento
valora en el lado de la izquierdo-mano de la barra de estado al fondo de la ventana SAFE.
Note que estos desplazamientos están en pulgadas.

\58. Pulse el botón la gota abajo la caja en la barra de estado cambiar las unidades al

Kip-ft.

\59. Pulse el botón Show Slab Forces en la barra de herramientas principal (o
seleccione Show Slab Forces...del menú del Display) desplegar la Tabla Fuerza caja del
diálogo.

\60. En esta caja del diálogo:

• Seleccione DCON3 Combo de la Carga gota-abajo la caja.

• En el área del Componente seleccione la opción de Mxx.

• Pulse el botón de OK.

\61. Los momentos del X-dirección se despliegan ahora. Nota que usted puede ejecutar su
cursor encima del momento contornea y el momento a la situación del cursor se despliega
en el lado de la izquierdo-mano de la barra de estado al fondo de la ventana SAFE.

\62. Si usted quiere ver resultados de fuerza de tabla para otros componentes de fuerza o
para otras combinaciones de carga entonces repita pasos 55 a través de 57.

<!-- p. 14 -->

\63. En el menú Design seleccione Start Design.

\64. Cuando el Diseño está completo que el refuerzo de la X-tira calculado se despliega en
pulgadas del cuadrado. Nota que usted puede ejecutar su cursor encima de este refuerzo y
el refuerzo requerido se despliega en el lado de la izquierdo-mano de la barra de estado al
fondo de la ventana SAFE.

Nota: el usted de Si ninguna especifica por lo menos entonces una tira del plan de la tabla
que el programa creará una tira del diseño de la Losa automáticamente para cada
row/column of the mesh. Puesto que nosotros no creamos ninguna tira de plan de Losa
en este ejemplo, el programa creó automáticamente el plan despoja mostrado ahora y
ellos corresponden a la malla.

\65. Del menú Design seleccione Display Slab Design Info...para desplegar la Tabla que
Refuerza caja del diálogo.

\66. En esta caja del diálogo:

• En el Escoge la Dirección de Tira a verificar que la X Directions Strip opción es
escogida.

• En el Tipo del Despliegue Reforzando seleccione la opción Show Number of
Bars y entonces seleccione #6 del asociado gota-abajo la caja.

• Pulse el botón de OK.

\67. El refuerzo de la X-tira calculado que muestra el número requerido de #6 barras se
despliega ahora. Nota que usted puede ejecutar su cursor encima de este refuerzo y el
refuerzo requerido en pulgadas del cuadrado se despliega en el lado de la izquierdo-mano
de la barra de estado al fondo de la ventana SAFE.

\68. Del menú Design seleccione Display Slab Design Info... para desplegar la Tabla que
Refuerza caja del diálogo.

\69. En esta caja del diálogo:

• En el Escoge Dirección de la Tira seleccione la Y Directions Strip opción.

• En el Tipo del Despliegue Reforzando seleccione el Número de Muestra de
opción de las Barras y entonces seleccione #4 del asociado gota-abajo la caja.

• Pulso el botón de OK.

<!-- p. 15 -->

\70. Refuerzo de la tira-Y calculado que muestra el número requerido de #4 barras para
cada uno del de tiras de las planean ahora de despliega de se. Nota que usted puede
ejecutar su cursor encima del refuerzo del este el y el refuerzo requerido en pulgadas
cuadradas se despliega en el lado del izquierdo-mano del la de la barra del la del fondo de
al de estado de la ventana del la SAFE.
