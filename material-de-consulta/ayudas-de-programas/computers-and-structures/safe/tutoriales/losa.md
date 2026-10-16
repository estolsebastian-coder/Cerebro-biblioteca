---
type: libro
title: "Losa"
author: "your name"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 16
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/SAFE/Tutoriales/Losa.pdf"
convertido: 2026-10-16
---

# Losa

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\SAFE\Tutoriales\Losa.pdf` (16 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Problema 3
Sistema de Viga-tabla de uno-manera Con Abrir

Diseñe Información
E = 3600 ksi, Proporción de Poissons = 0.2, Peso de la Unidad = 150 pcf
f'c = 4 ksi, fy = 60 ksi
Los X dirección cima rebar cubren = 2.5” (al centroide del rebar)
Los Y dirección cima rebar cubren = 1.5” (al centroide del rebar)
Los X dirección fondo rebar cubren = 1.5” (al centroide del rebar)
Los Y dirección fondo rebar cubren = 2.5” (al centroide del rebar)
Todas las columnas son 12” a través de 12.”
Altura de la columna debajo de es 10 pies.
Todas las vigas son 12” ancho a través de 18” profundo (12” profundo debajo de la tabla).
Vigas del plan como vigas del rectanglar (no los T-viga).
La tabla es 6” espeso.
La carga muerta además del mismo-peso es 35 psf.
La carga viva es 100 psf.

Para Hacer
Use el ACI 318-95 código. Repase los momentos de la viga factorizados. Repase el viga flexural
reforzando calculado.

<!-- p. 2 -->

Problema 3 Solución

\1. Pulse el botón la gota abajo la caja en la barra de estado cambiar las unidades al kip-ft.

\2. Del menú File seleccione New Model From Template….Esto despliega la Tabla Las
plantillas dialogan caja.

\3. En esta caja del diálogo:

• Pulse el botón Ribbed Slab para desplegar la caja de diálogo de
Losa de Rebordes.

• En esta caja del diálogo:

En el Along X Direction área verifica que se entran en 0.5 en la Left
Edge Distance y la Right Edge Distance revisa cajas.

En el Along X Direction área tipo 1 en el Number of Spans revisa caja.

En el Along X Direction áreas verifique que se entran en 24 en el
Spacing revise caja.

En el Along Y Direction área verifica que se entran en 0.5 en la Left
Edge Distance y la Right Edge Distance revisa cajas.

En el Along Y Direction área tipo 1 en el Number of Spans revisa caja.

En el Along Y Direction áreas verifique que se entran en 24 en el
Spacing revise caja.

Digite 0.5 en el Slab Thickness revise caja.

Verifique que en 1 se entra en el Column Size (square) revise caja.

Digite 10 en la Column Height Below revise caja.

En el área de Load tipo .035 en la Dead Load (Additional) revise caja.
Puesto que las unidades son kips y pies, .035 son equivalentes a 35 psf.

<!-- p. 3 -->

En el área de Load tipo .1 en la Live Load revisa caja. Puesto que las
unidades son kips y pies, .1 son equivalentes a 100 psf.

Salga Create Live Load Patterns verifican caja desenfrenado.

Nota: Verificando Create Live Load Patterns verifican causas de la caja el programa
para crear todas las clases de salto automáticamente generado los modelos cargantes para
la carga viva. Estos modelos se agregan automáticamente a los casos de carga estáticos
definidos y se identifican con un Tipo de Carga llamó Modelo Viva. Además, estos
modelos de carga viva son automáticamente incluidos en las combinaciones de carga
creadas para el Diseño.

En el área de la Joist (viga) tipo 6 en el Spacing revisa caja.

En el área de la Joist verifique que la Y Dirección opción este seleccionada que
esto significa que las vigas se definirán paralelo al el

Nota: Nosotros definiremos y asignaremos beam/ joist sizes después.

Pulse el botón de OK.

\4. Del menú Edit seleccione Edit Grid... para desplegar el Defina X Reja diálogo caja.

\5. En esta caja del diálogo:

• En el área del Display seleccione la Y Grid opcion.

• En el Display Grid Como áreas verifica que la opción de las Ordenadas se
selecciona.

• Pulse el botón en la fila 3 de la hoja de cálculo.

• En la Grid Line #3 área selecciona la opción de la Línea Secundaria.

Nota: las líneas de la reja Secundarias no tienen Reja las burbujas de ID. Nosotros no
especificaremos una Reja ID para estas líneas secundarias.

• Digite 4 en la columna de la Coordenada de la fila 3 de la hoja de cálculo.

• Digite 20 en la columna de la Coordenada de la fila 4 de la hoja de cálculo.

• Pulse el botón de OK. El modelo aparece ahora como mostrado en Figura 3-1.

<!-- p. 4 -->

\6. Anule la viga del centro (viga) pulsando el botón en él para seleccionarlo y entonces
apretando el Anule llave en el teclado.

\7. Verifique que el botón Snap to Points en la barra de herramientas lateral está
deprimido. Alternativamente, usted podría pulsar el botón adelante del menú Draw, el
Snap To selecto y verifica hay una marca del cheque al lado de los Puntos en el submenú.

\8. Pulse el botón Snap to Intersections en la barra de herramientas lateral.
Después de que usted pulsa el botón en el botón que seguirá siendo indicando deprimidos
que esta opción del chasquido es activa. Alternativamente, usted podría pulsar el botón
adelante del menú Draw, el Snap To y pulsa el botón en Intersecciones en el sub-menú
activar esta opción del Snap.

Nota: El acto de botones de opciones instantáneo como los interruptores de la barra
traviesa. Usted puede acostumbrarlos a encender opciones instantáneas o fuera de. Si un
botón de la opción instantáneo parece deprimido entonces que esa opción del chasquido
es activa. Pulsando el botón cualquier Snap opción botón barra traviesa él entre activo
(deprimido) y inactivo (no deprimido). Semejantemente, los artículos de la opción
instantáneos en el Draw acto del menú como los interruptores de la barra traviesa. Si una
opción instantánea en el Chasquido Al sub-menú tiene una marca del cheque entonces al
lado de él que esa opción del chasquido es activa. Pulsando el botón una opción
instantánea en el Snap To las barras traviesas del sub-menú el estado de esa opción.

<!-- p. 5 -->

Figura 3-1: Modelo después del Paso 5

\9. Pulse el botón Draw Line Object en la barra de herramientas lateral (o
seleccione Draw Line Object del menú Draw).

\10. Dibuje un objeto de la línea pulsando el botón en el punto etiquetó J en Figura 3-1 y
entonces los pulsando el botón dobles en el punto etiquetaron K para completar el objeto
de la línea.

Nota: con la opción de chasquido de Intersección activada el cursor del ratón sacará una
foto a la intersección de la viga y línea de la reja a los puntos J y K.

Nota: Nosotros también podríamos singularizar pulse el botón en el punto etiquetó K y
entonces aprieta el Entre en llave en el teclado completar el objeto de la línea.

\11. Dibuje un objeto de la línea pulsando el botón en el punto etiquetó L en Figura 3-1 y
entonces los pulsando el botón dobles en el punto etiquetaron M para completar el objeto
de la línea. El modelo aparece ahora como mostrado en Figura 3-2.

<!-- p. 6 -->

Figura 3-2: Modelo Después del Paso 11

\12. Pulse el botón Snap to Intersections en la barra de herramientas lateral para
dejar fuera de funcionamiento esta opción del chasquido.

\13. Pulse el botón Snap to Middle and Ends en la barra de herramientas lateral
activar esta opción del chasquido.

\14. Ejecute el cursor del ratón a lo largo de la viga cerca del punto etiquetó O en Figura
3-2 hasta los chasquidos del cursor al punto medio de la viga y una caja del texto que
dicen Medio Punto aparece. La izquierda pulsa el botón el ratón para empezar
deduciendo una nueva viga de esta situación del punto medio.

\15. Suba el ratón al punto etiquetó P en Figura 3-2. De nuevo el cursor del ratón sacará
una foto al punto medio de la viga. Doble pulse el botón al punto P para terminar
dibujando esta viga.

\16. Semejantemente, pulse el botón en el punto etiquetó Q en Figura 3-2 y entonces doble
pulse el botón en el punto etiquetó R para dibujar otra viga. Note que ambos apunta que
Q y R están en los puntos medios de vigas. El modelo aparece ahora como mostrado en
Figura 3-3.

<!-- p. 7 -->

\17. Ahora nosotros dibujaremos el objeto del área que definirá la apertura de la tabla.

Pulse el botón Draw Rectangular Area Object en la barra de herramientas lateral
(o seleccione Draw Rectangular Object del menú Draw).

Figure 3-3: Modelo Paso 16 más a popa

\18. Solo pulse el botón en el punto etiquetó S en Figura 3-3 y entonces doble pulse el
botón en el punto etiquetó T para dibujar el objeto del área.

\19. Pulse el botón Pointer/Select para cambiar de Dibuja modo para seleccionar
modo.

\20. El derecho pulsa el botón cerca del punto etiquetó U en Figura 3-3 desplegar la Tabla
Rectangular
Caja de diálogo de información para el objeto del área arrastrado justo.

\21. En esta caja del diálogo:

• En el Locate Slab area seleccione la opción By Center.

• En la Identificación y las áreas de la Situación verifican ese Centro X y Centro Y
son ambos 12. Éstos son los X y Y coordina del centro del objeto del área.

<!-- p. 8 -->

• En la Identification and Location área de la Situación tipo 11 en la Dimensión
de X y digite 15 en la Dimensión de Y revise cajas.

• Pulse el botón el botón de OK.

\22. La izquierda pulsa el botón cerca del punto etiquetó U en Figura 3-3 seleccionar el
objeto de área de dimensiones justo.

\23. Del menú Assign seleccione Opening. Esta área se designa ahora como una apertura.

\24. Pulse el botón la gota abajo la caja en la barra de estado cambiar las unidades a kip-

in.

\25. Del menú Define seleccione Slab Properties… desplegar las Propiedades de la Tabla
dialogan caja.

\26. En esta caja del diálogo:

• En el Tabla Propiedad área momento culminante la propiedad nombró SLAB y
entonces pulsa el botón Modify/Show Property para desplegar los Datos de
Propiedad de Tabla dialogo caja.

• En esta caja del diálogo:

En el Análisis Propiedad Datos área:

Verifique que el Modulus of Elasticity es 3600.

Verifique que la Poisson’s ratio es 0.2.

Nota: Nosotros verificaremos el peso de la unidad después.

Verifique que el Espesor del Torcimiento (X), Doblando Espesor (Y) y Torciendo
Espesor son todos los 6.

Nota: Estos valores legan todos es 6 porque nosotros entramos en el espesor del
fundamento en la caja de diálogo de Ribbed Slab en Paso 3.

Verifique que la opción de Tipo de Tabla se selecciona.

Verifique que la caja de cheque de Thick Plate se verifica.

<!-- p. 9 -->

Nota: Verificando la caja de cheque de Thick Plate dice al programa considerar
deformaciones de esquila de tabla en el análisis. Si esta caja no se verifica entonces que
las deformaciones de esquila de tabla no son incluidas en el análisis.

En el Plan Propiedad Datos área:

Verifique que el Thickness es 6.

Teclee 2.5 en la X Cover Top (a Centroide) revise caja.

Teclee 1.5 en la Y Cover Top (a Centroide) revise caja.

Teclee 1.5 en el X Cover Bottom (a Centroide) revise caja.

Teclee 2.5 en el Y Cover Bottom (a Centroide) revise caja.

Verifique Concrete Strength, fc es 4.

Verifique Reinforcing Yield Stress, fy es 60.

Verifique que el No Design no se verifica.

Pulse el botón de OK dos veces.

\27. Del menú Define seleccione Beam Properties… desplegar las Propiedades de la
Viga dialogan caja.

\28. En esta caja del diálogo:

• Pulse el botón el gota-baje caja en el Pulse el botón Al área y pulse el botón
adelante Add Rectangular Beam para desplegar los Datos de Propiedad Para la
caja de diálogo de Viga Rectangular.

• En esta caja del diálogo:

Digite XBEAM en Beam Property name.

En el Análisis Propiedad Datos área:

Verifique Modulus of Elasticity es 3600.

Verifique que Poisson’s ratio es 0.2.

Nota: Nosotros verificaremos el peso de la unidad después.

<!-- p. 10 -->

Verifique que la Width (anchura) es 12.

Digite 18 en la Depth (Profundidad).

En Design Property Data área:

Verifique que Width es 12.

Digite 18 en Depth.

Digite 2.5 en Cover Top (a Centroide) revise caja.

Digite 1.5 en Cover Bottom (a Centroide) revise caja.

Verifique Concrete Strength, fc es 4.

Verifique Reinforcing Yield Stress, fy es 60.

Verifique Shear Steel Yield Stress, fys es 60.

Verifique Concrete Shear Strength, fcs es 4.

Verifique que el No Design no se verifica.

Pulse el botón de OK.

• Pulse el botón el gota-baje caja en el Pulse el botón Al área y pulse el botón adelante
Add Rectangular Beam Para desplegar los Datos de Propiedad Para la caja de diálogo
de Viga Rectangular.

• En esta caja del diálogo:

Digite YBEAM en el nombre de Propiedad de Viga revise caja.

En el Análisis Propiedad Datos área:

Verifique que Modulus of Elasticity es 3600.

Verifique que Poisson’s ratio es 0.2.

Nota: Nosotros verificaremos el peso de la unidad después.

Verifique Width es 12.

Digite 18 en Depth.

En el Design Property Data área:

<!-- p. 11 -->

Verifique Width es 12.

Digite 18 en Depth.

Digite 1.5 en Cover Top (a Centroide).

Digite 2.5 en Cover Bottom (a Centroide).

Verifique Concrete Strength, fc es 4.

Verifique Reinforcing Yield Stress, fy es 60.

Verifique Shear Steel Yield Stress, fys es 60.

Verifique Concrete Shear Strength, fcs es 4.

Verifique que No Design no se verifica.

Pulse el botón de OK dos veces.

\29. Pulse el botón la gota abajo la caja en la barra de estado cambiar las unidades al kip-

ft.

\30. Del menú Define seleccione Slab Properties…desplegar las Propiedades de la Tabla
dialogan caja.

\31. En esta caja del diálogo:

• En el Tabla Propiedad área momento culminante la propiedad nombró SLAB y
entonces pulsa el botón Modify/Show Property para desplegar los Datos de
Propiedad de Tabla dialogo caja.

• En esta caja del diálogo:

Verifique que unit weight es 0.15.

Pulse el botón OK dos veces para terminar todas las cajas del diálogo.

\32. Del menú Define seleccione Beam Properties... desplegar las Propiedades de la Viga
dialogan caja.

\33. En esta caja del diálogo:

<!-- p. 12 -->

• En el Viga Propiedad área momento culminante la propiedad nombró XBEAM y
entonces pulsa el botón Modify/Show Property para desplegar los de Propiedad
la Para la caja del diálogo de Viga Rectangular.

• En esta caja del diálogo:

Verifique que unit weight es 0.15.

Pulse el botón de OK.

• En el Viga Propiedad área momento culminante la propiedad nombró YBEAM y
entonces pulsa el botón Modify/Show Property para desplegar los de Propiedad
la Para la caja del diálogo de Viga Rectangular.

• En esta caja del diálogo:

Verifique que unit weight es 0.15.

Pulse el botón de OK dos veces para terminar todas las cajas del diálogo.

\34. Pulse el botón View en la ventana de vista de plan las Propiedades de la Tabla
titulado para asegurarse que es activo. Cuando la ventana es activa que su barra del título
se resalta.

\35. Pulse el botón Select All en la barra de herramientas principal para seleccionar
todos los elementos.

\36. Del menú Assign seleccione Beam Properties... desplegar las Propiedades de la
Viga dialogan caja.

\37. en esta caja del diálogo:

• En la Viga Propiedad lista caja pulse el botón en YBEAM para resaltarlo.

• Pulse el botón OK. El modelo aparece ahora como mostrado en Figura 3-4.

<!-- p. 13 -->

Figure 3-4: Modelo Paso 37 más a popa

\38. Seleccione las cuatro vigas del X-dirección que se rodean en Figura 3-4 pulsando el
botón en ellos.
\39. Del menú Assign seleccione Beam Properties... desplegar las Propiedades de la Viga
dialogan caja.

\40. En esta caja del diálogo:

• En la Viga Propiedad lista caja pulse el botón en XBEAM para resaltarlo.

• Pulse el botón de OK.

\41. El derecho pulsa el botón en alguna parte no en el objeto de área de tabla en la
apertura, por ejemplo al punto etiquetó V en Figura 3-4 desplegar la Tabla Información
diálogo caja Rectangular.

\42. En esta caja del diálogo:

• Nota que la Propiedad de la Tabla es SLAB y llamada que nosotros ya hemos
definido estas propiedades.

<!-- p. 14 -->

• Nota que el Caso de Carga gota-abajo la caja dice DEAD que los w/area
asociados revisan que la caja dice 0.035. Ésta es la carga muerta nosotros
inicialmente la entrada (vea paso 3).

• Seleccione LIVE del Caso de Carga gota-abajo la caja y nota que los w/área
asociados revisan caja dice 0.1. Ésta es la carga viva nosotros inicialmente la
entrada (vea paso 3).

• Pulse el botón de OK.

\43. Del menú Options seleccione Preferences…y entonces selecciona la Concrete Tab.

\44. En esta caja del diálogo:

• Verifique que ese ACI 318-95 se selecciona en el Código de Diseño Concreto
gota-abajo la caja.

• Verifique eso en el Refuerzo Resulta área de las Unidades el Sq-in y la opción de
Sq-in/ft se selecciona.

• Pulse el botón de OK.

\45. En el menú Design seleccione Select Design Combos para desplegar la Carga del
Plan Combinaciones Selección diálogo caja.

\46. En esta caja del diálogo:

• En Design Combos listan caja pulse el botón DCON2 para resaltarlo y entonces
pulse el botón Show.

• Note que esta combinación de carga se define como 1.4DL + 1.7LL. También
nota que el Uso Para la caja de Design Check se verifica.

Nota: SAFE automáticamente crea combinaciones de carga de plan basadas en el código
del plan seleccionado y en los tipos de carga estáticos. En este caso donde los tipos de
carga estáticos definidos están MUERTOS y VIVOS (vea Static Load Cases adelante el
menú Define) y el código del plan es ACI 318-95, el programa crea dos casos de carga
automáticamente. Ellos tienen 1.4DL años (DCON1) y 1.4DL + 1.7LL (DCON2).

Si nosotros quisiéramos agregar una combinación de carga de plan adicional que nosotros
podríamos definirlo seleccionando Load Combinations... del menú Define y entonces
pulsando el botón Add New Combo, desplegar los datos de Combinación de Carga
dialogan caja. En esta caja del diálogo nosotros podemos definir la combinación de carga
y nosotros podemos verificar el Uso Para la caja de cheque de Plan si nosotros queremos
usar la combinación de carga en plan.

<!-- p. 15 -->

• Pulse el botón de OK dos veces para terminar todas las cajas del diálogo.

\47. Del menú Analyze seleccione Set Options para desplegar las Opciones del Análisis
dialogo caja.

\48. En esta caja del diálogo:

• En el área de Tipo de Análisis verifica que la opción Normal se selecciona.

• Acepte la dimensión de malla de máximo predefinida de 4 pies.

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

En este ejemplo nosotros estamos aceptando la malla del máximo predefinida de cuatro
pies. Esto significa que la tabla que mide por palmos entre las vigas que usa dos
elementos que están menos de los cuatro elementos recomendados en el párrafo anterior
se modelará. Si la exactitud de la tabla resulta (momentos, etc.) era entonces importante a
nosotros que nosotros podríamos querer reducir el tamaño de malla de máximo a 1.5 pies.

Nota: La malla automáticamente generada por el programa puede ser vista pulsando el

botón Set Objects en la barra de herramientas principal (o seleccionando Set Object
Options... del menú View) desplegar la caja de diálogo de Objetos Fija, verificando la
Show Mesh cheque caja en el área de las Opciones, y pulsando el botón de OK. Usted
puede apagar el despliegue de la malla un-verificando esta caja.

• Pulse el botón de OK.

\49. Pulse el botón Run Analysis en la barra de herramientas principal (o Run
Analysis selecto del menú Analyze).

\50. Cuando el análisis inicial es cheque completo los mensajes en la ventana del Análisis
(debe haber ninguna advertencia o errores) y entonces pulsa el botón de OK para cerrar
la ventana del Análisis.

<!-- p. 16 -->

\51. Pulse el botón Show Beam Forces en la barra de herramientas principal (o
seleccione Show Beam Forces…del menú Display) desplegar la Viga Fuerza caja del
diálogo.

\52. En esta caja del diálogo:

• Seleccione DCON2 Combo de la Carga gota-abajo la caja.

• En el área del Componente seleccione la opción del Momento.

• En el Despliegue opciones área cheque la Muestra Valora caja del cheque. Note la
de si de que Hartura el Diagrama cheque caja se verifica que usted tendrá al un-
cheque él antes del que usted pueda verificar que la Muestra la caja de Valora.

• Pulse el botón de OK para desplegar los diagramas del momento.

\53. Ejecute el cursor del ratón encima de las vigas y lea el momento valora del lado de la
izquierdo-mano de la barra de estado al fondo de la ventana SAFE.

\54. Si usted quiere ver resultados de fuerza de viga entonces para otros componentes de
fuerza repita pasos 51 a través de 53.

\55. En el menú Design seleccione Start Design. Cuando el Diseño está completo que el
refuerzo de la X-tira calculado se despliega en pulgadas del cuadrado.

\56. Del menú Design seleccione Display Beam Design Info…para desplegar la Viga que
Refuerza caja del diálogo.

\57. En esta caja del diálogo:

• En el Tipo de Reforzar áreas verifica que la opción de Flexura es escogida.

• En el área de Valores Reforzando verifique que la Muestra se verifican Valores de
Rebar a Controlar caja de cheque de Estación.

• En el área de Valores Reforzando verifique que la Muestra no se verifican
Valores de Rebar en Cada caja de cheque de Estación.

• Acepte los otros valores predefinidos en esta caja del diálogo.

• Pulse el botón el botón de OK.

\58. Ejecute el cursor del ratón encima de las vigas y lea los flexura aceran valores del
lado de la izquierdo-mano de la barra de estado al fondo de la ventana SAFE.
