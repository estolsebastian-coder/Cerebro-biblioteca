---
type: libro
title: "Manual Catalogos"
author: "user"
categoria: "BIM Y HBIM"
paginas: 108
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/FAMILIAS/FAMILIAS GRUPO DEMA (ARGENTINA)/Manual Catalogos.pdf"
convertido: 2026-10-16
---

# Manual Catalogos

> Texto extraído de `BIM Y HBIM\01. Revit\FAMILIAS\FAMILIAS GRUPO DEMA (ARGENTINA)\Manual Catalogos.pdf` (108 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

®
Manual de Librerías Revit

Grupo DEMA, Vanguardia Tecnológica en Conducción de Fluidos,
presenta las primeras librerías BIM de la Argentina
para proyectos de instalaciones de agua, gas, desagües y calefacción
con sus sistemas ACQUA SYSTEM, SIGAS, DURATOP y TUBOTHERM.

<!-- p. 2 -->

Ferva S.A., empresa de Grupo Dema que provee gratuitamente estas librerías REVIT de sus productos Acqua System y Duratop, no será responsable de ningún costo directo o
indirecto, de cualquier naturaleza, que surjan o resulten del uso de los archivos.

<!-- p. 3 -->



<!-- p. 4 -->

INDICE

0.0 Consideraciones generales ................................................................................... Pág. 05

1.0 Librerías Grupo Dema Revit® - Información general ............................................ Pág. 07
1.1 Importe las librerías siguiendo las instrucciones de Grupo Dema
1.2 Recomendaciones iniciales:
1.3 Importar Vista de Veriﬁcación Grupo Dema
1.4 Importar Schedule / Tablas de cantidades

2.0 Librerías Grupo Dema Revit® - Información general ............................................ Pág. 14
2.1 Trabajar con tipos de tuberías en las Librerías Grupo Dema Revit®
2.2 Trabajar con Reducciones en las librerías Grupo Dema Revit®
2.3 Trabajar con Codos en las librerías Grupo Dema Revit®
2.4 Trabajar con Tees/Yees en las librerías Grupo Dema Revit®
2.5 Trabajar con Uniones en las librerías Grupo Dema Revit®
2.6 Trabajar con Pendientes

3.0 Línea de producto - Duratop ................................................................................. Pág. 26
3.1 Tipos de uniones
3.2 Codos
3.3 Ramales
3.4 Uniones y Caños cámara
3.5 Reducciones
3.6 Tapones
3.7 Accesorios
3.8 Kits

4.0 Línea de producto - Acqua System ....................................................................... Pág. 38
4.1 Tipos de tuberías
4.2 Bujes
4.3 Codos
4.4 Tees
4.5 Unión, niple, cupla.
4.6 Tapones
4.7 Llaves de paso/válvulas
4.8 Accesorios de sujeción e instalación
4.9 Kits - Productos especíﬁcos con parámetros de ajuste

03

<!-- p. 5 -->

INDICE

5.0 Accesorios .............................................................................................................. Pág. 50

6.0 Línea de producto - Sigas Thermofusión ............................................................... Pág. 51
6.1 Tipos de tuberías
6.2 Codos
6.3 Tee
6.4 Uniones
6.5 Reducciones
6.6 Tapones
6.7 Llaves de paso/Válvulas 6.8 Tablas y vista de veriﬁcación

7.0 Línea de producto - Tubotherm ............................................................................. Pág. 64
7.1 Características del sistema
7.2 Tipos de tuberías
7.3 Uniones - Sistema continuo
7.3.1. TUBOTHERM - Curva
7.3.2. TUBOTHERM - Unión en U
7.3.3. TUBOTHERM - Unión normal
7.4 Distribución del tendido Tubotherm
7.4.1 Tendidos y Grupo sistema
7.4.2 Tabla de tubería
7.4.3 Tabla de tubería ﬂexible
7.5 Accesorios
7.5.1 Kit Colector
7.5.2 Insertar Kit Colector
7.5.3 Tabla Kit Colector
7.6 Bloques de Diseño
7.7 Bloque Regular
7.7.1 Insertar Bloque Regular
7.7.2 Bloque Regular con borde periférico
7.7.3 Bloque Regular con borde periférico doble
7.7.4 Cuadro comparativo situaciones Bloque Regular

04

<!-- p. 6 -->

INDICE

7.8 Bloque Irregular
7.8.1 Insertar Bloque Irregular
7.8.2 Bloque Irregular con borde periférico
7.8.3 Cuadro comparativo situaciones Bloque Irregular
7.9 Suelo Tubotherm
7.9.1 Crear suelo y aplicar parámetros
7.9.2 Tabla
7.10 Recomendaciones
7.10.1 Pasaje de Curva a Unión en U
7.10.2 Avisos
7.10.3 Vista de Veriﬁcación

05

<!-- p. 7 -->

0.0 CONSIDERACIONES GENERALES

Por defecto Revit trae familias MEP que pueden ser utilizadas sin embargo las mismas son las genéricas
que no reﬂejan a ninguna empresa por lo tanto no poseen el rigor en sus dimensiones. Es aquí donde el
GRUPO DEMA entra en acción ejecutando las librerías Grupo Dema Revit® para así lograr tener una
Instalación de mayor precisión en BIM.

Para aprovechar al máximo las ventajas de utilizar nuestras librerías por favor siga estos pasos:
\1. Importe las librerías siguiendo las instrucciones de Grupo Dema
▪ Las librerías Grupo Dema Revit® contienen información adicional inteligente, cómo; una vista de
veriﬁcación y tablas especíﬁcas para el computo de cantidades de tuberías y accesorios (Tablas de
Planiﬁcación/Cantidades).
▪ Importe los archivos como se sugiere y podrá obtener todos los beneﬁcios de las librerías Grupo
Dema Revit®.
▪ Vista principal en la misma nos aparecerá el nombre de la línea del sistema, además de los
diferentes tipos de tubería, uniones y accesorios.

Ver Capítulo 1.1 para importar correctamente las librerías de Grupo Dema.

06

<!-- p. 8 -->

\2. Inserte tuberías y accesorios
▪Usando el panel de "Fontanería y tubería" (dentro de la pestaña de Instalaciones) y la ventana de
“Properties”
▪ Seleccione el tipo y diámetro de tubería deseada, luego empiece a dibujar la tubería - los
accesorios apropiados serán insertados automáticamente (en función de las preferencias de
enrutamiento).
▪ Seleccionando el accesorio predeterminado insertado, puede cambiarse usando la barra
desplegable en la ventana de propiedades.

En algunos accesorios, Grupo Dema ofrece la posibilidad de modiﬁcar sus características a través de
las secciones “Visilibity” (Visibilidad) o “Constraints” (Restricciones) en la ventana de propiedades.
A través de los botones “Pipe Fitting” (Unión de Tubería) y “Pipe Accessory” (Accesorio de Tubería)
ubicados en la pestaña de “System” (Instalaciones), puede insertar manualmente los accesorios
requeridos que no se encuentran incluidos de manera predeterminada en la ruta de preferencias.

\3. Varios tipos de tubería disponibles
▪ Grupo Dema posee varios tipos de tuberías según el sistema, además, trabaja con Diámetro
nominales

Ver capítulo 2.1 para un resumen completo de los tipos de tuberías que pueden ser
seleccionados para un proyecto.

\4. Cambiar orientación y tipo de accesorios
▪ Grupo Dema añadió esta característica en la ventana de propiedades para fácilmente:
a. Cambiar la orientación de un accesorio.
b. Cambiar características de un accesorio seleccionado.
▪ Al intentar crear accesorios que no existan en el portafolio de productos aparece un mensaje
indicando el error.

\5. Soluciones implementadas para Tee

Ver capítulos 2.2 y 2.4 para un resumen completo de como seleccionar la Tee y el buje correcto
para cada proyecto.

\6. Obtener el paquete más reciente
▪ Antes de empezar un nuevo proyecto debe asegurarse de haber descargado la versión más
reciente de las librerías Grupo Dema Revit® para obtener así una funcionalidad óptima y portafolio
actualizado.

07

<!-- p. 9 -->

1.0 Dema Librerías Revit® - Información general

1.1 Importe las librerías siguiendo las instrucciones de Grupo Dema

Con el ﬁn de hacer que el trabajo en Revit® sea más amigable para el usuario, Grupo Dema ha decidido,
no solo, crear familias ﬁeles a los productos, sino también añadirles inteligencia. Esto ayudará al usuario
a realizar conexiones y transiciones de manera correcta y con mayor ﬂuidez entre tuberías de diámetro
diferente.

Si son usadas correctamente las librerías Grupo Dema Revit® garantizarán no solo un diseño correcto,
sino también, acceso a la información, nombres y códigos de producto para cada parte usada en el
sistema.

A continuación, se encuentran los pasos a seguir para importar las familias, vista de veriﬁcación y tabla
de cantidades (Schedule).

IMPORTAR FAMILIAS:
\1. Abra la librería Revit® que será importada (por ejemplo “Línea Acqua System.rvt”), la misma será
entendida como "Proyecto de origen" y a la vez abra el archivo en el cual va a trabajar, este será el
"Proyecto de destino"

\2. En el proyecto de destino, haga click en la ﬁcha Gestionar y Diríjase al grupo de Conﬁguración. En el
mismo haga click en Transferir normas de proyecto.

08

<!-- p. 10 -->

\3. En el cuadro de diálogo Seleccionar en Copiar desde el "Proyecto de origen"

\4. Selección las normas de proyecto

Por defecto le aparecerá todo el listado seleccionado. En este caso Usted deberá hacer click en No
seleccionar ninguno y a continuación seleccionar de forma manual únicamente:

\- Conﬁguración de Tuberías
\- Tipo de tuberías
\- Plantillas de Vista
\- Materiales
\- Filtros

▪ Haga click en Aceptar

▪Si se abre el cuadro de diálogo Tipos duplicados le aparecerán 3 posibilidades de duplicado

\- Sobrescribir: transﬁere todas las normas de proyecto nuevas y sobrescribe los tipos duplicados.
\- Solo nuevo: transﬁere todas las normas de proyecto nuevas y omite los tipos duplicados.
\- Cancelar: cancela la operación.

▪ Seleccione la opción Solo nuevo en caso sea la primera vez que ejecuta esta acción de lo contrario
seleccione Sobrescribir en caso ya hubieran conﬁguraciones anteriores de las librerías Grupo Dema
Revit®

Ahora las familias se encuentran satisfactoriamente en el proyecto y se puede acceder a ellas mediante
la pestaña “Systems” (Instalaciones).

09

<!-- p. 11 -->

Otra posibilidad:

\1. Abra la librería Revit® que será importada.

▪ La vista de inicio es abierta de manera automática.
▪ Una vez abierta el Catalogo RVT del sistema deseado diríjase a la vista del nivel 1. Esta vista
contiene varios tipos de tuberías y algunas uniones/accesorios.
▪ Puede que algunas uniones de tubería que no se encuentran incluidos en la ruta de preferencias
predeterminada, estos también deben ser copiados para incluirlos en el proyecto en caso que sean
necesarios.
▪ Si el usuario no requiere trabajar con todos los tipos de tuberías no es necesario copiar todos los
tipos de tuberías visibles en la vista de inicio. Puede ser usado solo el tipo de tubería requerido para
el proyecto.

Para saber más acerca de los tipos de tubería disponibles diríjase a la sección 2.1.

▪ Solamente copiando una tubería, se transﬁeren sus accesorios y segmentos incluidos en su ruta
de preferencias.

\2. Escoja la opción “copiar al portapapeles” (Copy to Clipboard).
▪ Este modo de copia es necesario para transferir las propiedades de inteligencia correctamente.

\3. Diríjase al proyecto deseado.

\4. Abrir una vista 2D o 3D.

\5. Use la opción “Pegar desde el portapapeles”.
• En algunas versiones de Revit®, después de seleccionar la opción “pegar desde el portapapeles”
un aviso de información aparecerá mostrando que los tipos copiados ya existen en el proyecto y
serán mostrados. Seleccione “OK”.

\6. Ubique los elementos seleccionados en un espacio vacío sin usar en el proyecto.

\7. Haga Click en el botón de ﬁnalizar en la pestaña “Modify” (Modiﬁcar).

\8. Ahora las familias se encuentran satisfactoriamente en el proyecto y se puede acceder a ellas
mediante la pestaña “Systems” (Instalaciones).

10

<!-- p. 12 -->

1.2 Recomendaciones iniciales

Para tener una mejor visualización de las tuberías y accesorios se recomienda tener ajustado el nivel de
detalle en “Fine” (Alto) y el estilo visual en sombreado. Además, se recomienda manejar las unidades del
proyecto “Pipe Size” (Tamaño de tubería) milímetros como se muestra en las siguientes imágenes:

1.3 Importar Vista de Veriﬁcación Grupo Dema:

Las librerías Revit® de Grupo Dema permiten que el usuario veriﬁque si los ítems usados en el proyecto
se encuentran dibujados correctamente mediante un código de color.
Esta plantilla de vista se importará desde cada librería de Grupo Dema en caso se esté trabajando con
más de un sistema para así poder hacer la veriﬁcación de cada uno de ellos y sus restricciones

Si al inicio ya ejecuto la transferencia de normas de proyecto, la plantilla de se encuentra en su RVT de
trabajo (vea el punto 6 directamente), ahora sí solo necesita adquirir la plantilla de otro sistema:

11

<!-- p. 13 -->

a) Cree una nueva vista 3D en el Proyecto deseado o duplique una existente. Cambie el nombre de
la misma para saber que se trata de la vista de veriﬁcación, por ejemplo “VERIFICACION + NOMBRE
DEL SISTEMA”

b) Diríjase a la pestaña “Manage” (Gestionar) y de clic en “Transfer Project Standards” (Transferir
normas de Proyecto).

c) Una lista de ítems a copiar aparecerá.

d) Escoja el nombre de la librería de la cual desea transferir propiedades en la parte superior de la
pestaña emergente.

e) Solamente debe ser seleccionado “View templates” (Plantilla de vista). Luego, “OK”.

f) Vaya a la barra Properties (Propiedades) de la nueva vista 3D. Encuentre Identity Data (Datos de
identidad) y de clic en “View Template” (Plantilla de vista).

g) La pestaña Apply View Template (Aplicar plantilla de vista) aparecerá.

h) Escoja de la lista “VERIFICACION + NOMBRE DEL SISTEMA” y seleccione “OK”. Por ejemplo
plantilla VERIFICACION ACQUA SYSTEM.

12

<!-- p. 14 -->

Esta vista de la librería de Grupo Dema permite al usuario veriﬁcar si las dimensiones de las tuberías son
válidas. Si una tubería es más larga de lo que se encuentra disponible en nuestro catálogo, será de color
rojo. Si un accesorio creado no es un producto de Grupo Dema, no será mostrado en la vista.

13

<!-- p. 15 -->

1.4 Importar Schedule / Tablas de cantidades

Siga los pasos a continuación para importar las tablas de cantidades:
a) Diríjase al Project Browser en la librería Grupo Dema Revit®.
Encuentre la pestaña Schedule/Quantities (Tablas de Planiﬁcación/Cantidades).

b) Seleccione los Schedule de Grupo Dema y con click derecho seleccione “Copiar al
portapapeles”. El número de Schedule puede variar entre librerías, de acuerdo a las
características especíﬁcas de la gama de productos.

c) Diríjase al Proyecto deseado.

d) Vaya a la pestaña “Modify” (Modiﬁcar) y seleccione “Paste from Clipboard” (Pegar desde
Portapapeles).

e) Las tablas se copiaran directamente y podrá utilizarlas inmediatamente

14

<!-- p. 16 -->

2.0 Librerías Grupo Dema Revit® - Información general

2.1 Trabajar con tipos de tuberías en las Librerías Grupo Dema Revit®

Revit® Estándar
Librería Grupo Dema Revit® Revit® estándar usa únicamente las
Usa diámetros y longitudes de tubería tuberías tipo americanas (US). Vs. disponibles en nuestro catálogo de De manera predeterminada y pueden
productos. ser de cualquier longitud.

El portafolio de productos siempre contendrá diámetros especíﬁcos, trabajándose con diámetros
nominales

• Grupo Dema ha creado tipos de tuberías especíﬁcos en sus librerías.

15

<!-- p. 17 -->

• Grupo Dema le brinda al usuario la posibilidad de dibujar tuberías seleccionando Diámetro
Nominal

División de tubería en longitudes disponibles.

• Revit® estándar no tiene restricciones de longitud de tuberías. Para mejorar el diseño con las librerías
Grupo Dema Revit®, se ofrece una solución para usar la longitud de las tuberías que se encuentran
disponibles en el portafolio de productos.

• Para veriﬁcar si la longitud de tuberías usada en el proyecto se encuentra disponible en el portafolio,
diríjase a la vista “Vista de Veriﬁcación” en la ventana de Project Browser (Navegador de Proyectos).
Si una tubería es de color rojo, es necesario que su longitud sea dividida en una dimensión disponible en
el portafolio o bien que se cambie por un tipo de tubería con esa medida disponible.

• Cambiar la longitud de la tubería:
a) Encuentre y seleccione la tubería de color rojo en la vista “Vista de Veriﬁcación”
b) Divida la tubería en secciones usando el comando Split Element (SL en el teclado), click en alguna
parte de la tubería y de forma automática y en función de las preferencias de enrutamiento se
unirán ambas tuberías con una unión perteneciente a las familias del Grupo Dema Revit®

16

<!-- p. 18 -->

c) Para asegurarse de usar la longitud máxima de la tubería cree una dimensión entre la unión y el
otro extremo de la tubería usando la función “Aligned Dimension (DI)”.

Asegúrese de alinear la dimensión a la unión, si ésta es alineada al ﬁnal de la tubería, esta solución no
funcionará.

d) Seleccione la unión que será movida y de clic en la dimensión para editar. La máxima longitud
disponible para tuberías sanitarias en Grupo Dema es de 4m. Ver catálogo de tuberías para tener
mayor precisión de las tuberías.

17

<!-- p. 19 -->

e) Si la tubería es dividida correctamente y su longitud está disponible nuestro portafolio, la tubería
ya no será de color rojo en la vista “Vista de Veriﬁcación”.
El mismo procedimiento puede ser usado para poner una distancia entre dos uniones o una unión
y cualquier otro accesorio. Esto es útil para asegurarse de que en rectas largas la tubería sea usada
de manera completa si es posible.

• Además de forma complementaria una longitud incorrecta también puede ser fácilmente
encontrada en la Schedule (Tabla) de tuberías. Longitudes no disponibles estarán resaltadas con
color rojo.

De esta forma se logra una idea y vuelta entre el desarrollo del proyecto y la veriﬁcación del mismo
en el cómputo de elementos.

Haciendo click en “Resaltar en el modelo” el programa nos mostrara donde se encuentra la tubería
cuya medida está por fuera del catalogo.

18

<!-- p. 20 -->

2.2 Trabajar con Reducciones en las librerías Grupo Dema Revit®

Revit® Estándar Librería Grupo Dema Revit®
Las piezas de transición tienen la Frecuentemente es necesario más de
posibilidad de conectar a 2 diámetros un reductor, pero además nuestras
cualesquiera y siempre será librerías ofrecen monturas de
visualizado de la misma manera derivación en los casos necesarios o
usando un solo accesorio. El mismo bien diferentes tipos de reductores no
siempre será de reducción central simplemente los de reducción central.
Vs.

En la librería Grupo Dema Revit® se tuvieron en cuenta las siguientes situaciones:

\1. Usualmente es necesario más de una pieza para conectar dos diámetros distintos. Esto se puede
ejecutar utilizando los bujes de la librería de Grupo Dema Revit®

\2. Los sistemas de las librerías Grupo Dema Revit® proveen varios reductores que automáticamente
permiten la conexión entre tuberías de diferentes diámetros. Ente estos se encuentran el reductor
excéntrico y excéntrico anular.

19

<!-- p. 21 -->

2.3 Trabajar con Codos en las librerías Grupo Dema Revit®

Revit® Estándar Librería Grupo Dema Revit®
Es posible crear un codo con cualquier Solamente se pueden dibujar codos
ángulo y se visualiza siempre de la que se encuentran disponibles en
misma manera. Se encuentran nuestro portafolio de productos. Una
disponibles codos que vienen por gran variedad de codos es
defecto. suministrada; distintos ángulos según
el sistema. Vs.

\1. Gran variedad de codos disponibles en el portafolio de productos de Grupo Dema

• Dependiendo de la línea especíﬁca de productos, varios tipos de codos pueden ser insertados. Por
ejemplo El tipo predeterminado para la línea DURATOP/DURATOPXR es un codo MH
(macho-hembra) con cabezales que se pueden modiﬁcar en función del sentido del mismo, en
todos los tamaños. Es decir puede ser cambiado luego en un tipo especíﬁco de codo en el área de
Properties (Propiedades).

\2. Diámetros y ángulos especíﬁcos de codos disponibles

• De acuerdo al portafolio de nuestros productos pueden ser dibujados codos de; 45º, 90º y 87º30´.
Estos pueden ser insertados de manera automática dibujando dos tuberías y su ángulo apropiado.
Diríjase al capítulo de las líneas DURATOPX/DURATOP XR y ACQUA SYSTEM para aprender más
acerca de codos especíﬁco

20

<!-- p. 22 -->

2.4 Trabajar con Tees/Yees/Ramales en las librerías Grupo Dema Revit®

Librería Grupo Dema Revit® Revit® Estándar
Solo pueden ser dibujadas las Es posible conectar con cualquier
Tees/Yees que se encuentran diámetro y se visualiza siempre de la
disponibles en nuestro portafolio de misma manera. Solo se encuentran Vs. productos. De acuerdo a la línea de disponibles Tees/Yees simétricas con
productos especíﬁca se ofrece gran reductores céntricos.
variedad de Te´s y Ramales.

\1. Diámetros y ángulos especíﬁcos disponibles de Tees/Yees

• Si se desea dibujar una Tee/Yee puede hacerlo mediante un codo existente, presionando junto al
signo “+” que aparece cuando se selecciona el accesorio o conectando dos tuberías.

\2. Gran variedad en tipos de Tees/Yees y sus funcionalidades en el portafolio de Grupo Dema

• Dependiendo de la línea de producto, varios tipos de Tees/Yees pueden ser insertados.

• La línea sanitaria de las librerías Grupo Dema Revit® proveen Ramales con acceso reducido así
como Ramales con ventilación.

21

<!-- p. 23 -->

2.5 Trabajar con Uniones en las librerías Grupo Dema Revit®

Librería Grupo Dema Revit® Revit® Estándar
De acuerdo con la línea del producto Solo provee la visualización de una
se ofrece una gran variedad de unión. La longitud útil del accesorio no Vs. uniones especíﬁcas. La longitud útil de es correcta.
estas uniones es exacta.

• Trabajar con longitudes útiles permite conexiones correctas a las tuberías.

• Mientras se divide una tubería, los puntos de conexión representan la profundidad de inserción.

En la línea de agua fría y caliente las librerías Grupo Dema Revit® proveen una amplia variedad de
uniones estándar, adaptadores macho y hembra, uniones bridadas, niples, sobrepasos, etc.

22

<!-- p. 24 -->

2.6 Trabajar con Pendientes

Existen diferentes maneras de establecer pendientes en sistemas de tubería sanitaria. En esta sección
se hará un recorrido de esos métodos empezando desde los más fáciles de aplicar, hasta ﬁnalizar con
los más conﬁables.

1RA VARIANTE
Dibujar con las opciones encendidas “Slope Up” (Pendiente arriba) o “Slope Down” (Pendiente abajo)
aplica automáticamente la pendiente seleccionada a todas las tuberías dibujadas.
Cada vez que se va a dibujar una tubería se tienen estas opciones disponibles en la pestaña Modify
(Modiﬁcar).

23

<!-- p. 25 -->

2DA VARIANTE
Uso de la herramienta “slope” en un Sistema de tuberías que fue creado sin pendientes.

a) Use la Tecla TAB para seleccionar todos los componentes del Sistema, y de clic para conﬁrmar la
selección.

b) Vaya a la pestaña Modify (Modiﬁcar) y active la función Slope (Pendiente).

24

<!-- p. 26 -->

c) Determine el punto de control y elija el valor de la pendiente y seleccione “Finish” (Finalizar) para
aplicar la pendiente.

3RA VARIANTE
Usar la herramienta Angle Dimension.

a) Vaya a una vista de elevación o sección donde muestre la tubería horizontal.

b) Cree una dimensión angular entre la tubería vertical y la tubería objetivo horizontal.

25

<!-- p. 27 -->

c) Seleccione la tubería horizontal.

d) Click en el valor de la dimensión angular y coloque el valor deseado.

26

<!-- p. 28 -->

3.0 Línea de producto - DURATOP X / DURATOP XR

3.1 Tipos de tuberías

Dentro de la línea de DURATOP X contamos con diferentes tipos de tuberías cuya longitud máxima es lo
que las va diferenciando, estas longitudes irán desde los 0.25 mts. a 4 mts., todas disponibles en los
diámetros establecidos en nuestro porfolio de productos.

En la línea de DURATOP XR (sistema de superior resistencia e insonoridad) contamos con diferentes tipos
de tuberías cuya longitud máxima es lo que las va diferenciando, estas longitudes irán desde los 1 mts a
4 mts, todas disponibles en los diámetros establecidos en nuestro porfolio de productos.

3.2 Codos

• Insertar un tipo especíﬁco de codo

Al dibujar dos tuberías con un ángulo correcto un codo predeterminado será insertado.
Para cambiar a un codo especíﬁco siga los pasos a continuación:

a) Dibuje un codo estándar que conecte dos tuberías.
b) Seleccione el codo.

27

<!-- p. 29 -->

c) Diríjase a la ventana “Properties” (Propiedades) y despliegue la lista dando click en el recuadro
amarillo como se muestra a continuación.

d) Encienda la casilla “Constrain to routing preferences” (Restringir a preferencias de
enrutamiento) de esta forma el listado de codos se limitara, es decir, esta opción activará
solamente los codos de una línea especíﬁca de productos.

28

<!-- p. 30 -->

• Cambiar características y propiedades de los codos

Las librerías Grupo Dema Revit® provee funciones adicionales que permiten cambiar algunas
propiedades de los codos. Algunas de estas se encuentran disponibles solo para tipos especíﬁcos de
codos. Para cambiar las propiedades del accesorio diríjase a la ventana “Properties”. Al seleccionar las
casillas presentes en el grupo de restricciones las siguientes funciones pueden ser habilitadas o
deshabilitadas:

a) Rotación – cambiara la dirección de un codo
b) Conexión Tubería I / Conexión Tubería D - Nos permitirá colocar y elegir el extremo hembra
presente en la tubería de unión en función de la dirección del codo.

29

<!-- p. 31 -->

3.3 Ramales

• Existen diferentes tipos de conexión de Ramales

La Y se encuentra como opción predeterminada en ángulos de 45°. Si se desea dibujar una
Puede hacerlo mediante un codo existente (45º), presionando junto al signo “+” que aparece cuando se
selecciona el accesorio.

A B

A B

Según el signo que presiones el sentido de la Y variará

30

<!-- p. 32 -->

Los ramales se encuentra como opción predeterminada en ángulos de 90° además pueden cambiarse,
por ejemplo cambiar de Ramal simple a Ramal con ventilación

a) Diríjase a la ventana “Properties” (Propiedades)
b) Encienda la casilla “Constrain to routing preferences” (Restringir a preferencias de
enrutamiento) de esta forma el listado de codos se limitara, es decir, esta opción activará
solamente los ramales de una línea especíﬁca de productos.
c) Seleccione el ramal con el que desea trabajar.

En ambos casos la tipo de unión deberá estar primera en la preferencia de enrutamiento para que la
pieza se adapte automáticamente, de lo contrario Revit nos anunciará Error.

31

<!-- p. 33 -->

Otra posibilidad es realizar el cruce de tuberías:

32

<!-- p. 34 -->

3.4 Uniones y Caños cámara

• Insertar una unión

En sistemas sanitarios una unión es insertada cuando una tubería es dividida en dos elementos. Para
insertar una unión siga las instrucciones:

a) Active la herramienta Split Element (cortar) en la pestaña Modify (Modiﬁcar) o use el comando
“SL” en el teclado.
b) De click en el punto donde quiere dividir la tubería y una unión será insertada

Para cambiar la unión por otros accesorios seleccione la unión y en la ventana de “properties”
(Propiedades) seleccione el accesorio deseado.

33

<!-- p. 35 -->

La librería Grupo Dema Revit® con el objetivo de establecer las correcta conexiones entre las tuberías
no solo ofrece la cupla de unión sino un Conector Hembra, que reﬂeja la unión real entre dos tuberías
macho - hembra y no solo macho - macho.

3.5 Reducciones

• Dentro del catálogo de nuestro productos contamos con piezas como:
\- Reductor Anular
\- Reductor Excéntrico anular
\- Reductor Excéntrico
\- Cupla de Reducción

• Los reductores se encuentran predeterminados. Estos permiten conectar a cualquier diámetro.
Para insertar uno, siga los pasos que se muestran:

a) Dibuje una tubería de cualquier diámetro.
b) Desde el extremo de esa tubería dibuje otra tubería de distinto diámetro.
c) En el punto donde cambia el diámetro se crea una cupla de reducción automáticamente, siempre
que la variación de diámetros entre las tuberías se encuentre dentro de las establecidas en nuestro
portfolio.

34

<!-- p. 36 -->

35

<!-- p. 37 -->

En caso querer una Reducción Excéntrica, bastara con tildar la casilla de Excentricidad dentro de las
propiedades de la familia y la misma cambiara a reducción excéntrica siempre y cuando estemos dentro
de los diámetros establecidos en nuestro porfolio

36

<!-- p. 38 -->

3.6 Tapones

• Grupo Dema ha suministrado tapones para los remates de los accesorios o al ﬁnal de una tubería.
Para insertar estos accesorios siga estos pasos:

a) Seleccione una tubería o un accesorio, que tenga al menos una conexión sin uso.
b) Diríjase a la pestaña Modify(Modiﬁcar) y de clic en el grupo Editar y click en “Cap Open Ends”
(Taponar extremos abiertos)
c) El tapón es insertado automáticamente en la cabeza o extremo libre.

Otra posibilidad a la hora de insertar tanto uniones u otro tipo de accesorios es; usando el comando
“CM” y en la barra de “Properties” (Propiedades) seleccionar el tipo de unión que quiero incorporar al
sistema, acerco la unión a la tubería hasta que la identiﬁque (el eje de la tubería se tornara azul) y hago
click donde deseo que la misma este ubicada.

37

<!-- p. 39 -->

3.7 Accesorios

La librería Grupo Dema Revit® con el objetivo de brindar no solo soluciones de instalación sino además
de montaje de las distintas instalaciones ofrece un sistema integral de grampas como los es la línea
DEMA FIX dirigida tanto al sistema de Acqua como al de Duratop (ver sección de accesorios).

3.8 Kits

La librería Grupo Dema Revit® no solo brindara las familias individuales de las diferentes uniones y
accesorios que se requieren en una instalación, si no también ofrecerá familias, que se entenderán
como kits de instalación, las mismas contendrán todos aquellos elementos necesarios según la
situación.

38

<!-- p. 40 -->

4.0 Línea de producto - Acqua System

4.1 Tipos de tuberías

Dentro de la línea Acqua System contamos con 5 tipos de tuberías, cuya longitud máxima es 4mts cada
tipo con un destino particular en función de sus cualidades:
PN25 Agua Fría - Agua Caliente (Alta exigencia)
PN20 Agua Fría - Agua Caliente
PN12 Agua Fría
Acqua Luminum X-Treme P+Q Cañerías a la vista en conducción de agua frica-caliente y sistemas
de calefacción
Lilac Recuperación de Agua de lluvia y grises

No es necesario copiar todas en su proyecto, seleccione las tuberías deseadas y cópielas

39

<!-- p. 41 -->

4.2 Bujes

• Insertar Bujes

Los bujes se encuentran predeterminados. Estos permiten conectar a cualquier diámetro (dentro de las
variables determinadas en nuestro catálogo). Para insertar uno, siga los pasos que se muestran:
a) Dibuje una tubería de cualquier diámetro (Esta deberá ser la que va a sufrir la reducción).
b) Desde el extremo de esa tubería dibuje otra tubería de distinto diámetro (tubería de menor
diámetro).
c) En el punto donde cambia el diámetro se crea un buje automáticamente, siempre que la
variación de diámetros entre las tuberías se encuentre dentro de las establecidas en nuestro
portfolio.

Ahora bien esta variación se utiliza para unir accesorios con tuberías no tuberías con tuberías como se
ve en las imagenes:

En la línea Acqua System así sean las tuberías de agua (fría o caliente) y las de recupero usan los mismos
accesorios.

40

<!-- p. 42 -->

4.3 Codos

Al dibujar dos tuberías con un ángulo de 45º o 90º un codo será insertado. En la librería Acqua System
no hay opciones para cambiar las características de los codos (como en los de Duratop).

• Insertar Codo con extremo Roscado

Para cambiar a un codo con un extremo roscado o de entrada macho hembra siga los pasos a
continuación:

a) Dibuje un codo de 90 grados (puede colocar el que le aparece por defecto cuando aplica el
comando CM).
b) Seleccione el codo.
c) Diríjase a la ventana “Properties” y despliegue la lista de codos.
d) Escoja el codo que desee.

41

<!-- p. 43 -->

CODOS CON ROSCA

Los codos con extremo roscado que proporciona Acqua System pueden ser:

\- Codo 90º con rosca hembra
\- Codo 45º con rosca macho

Estos permitirán conectar al sistema de termofusión de unión con uno de roscado determinado en
pulgadas (unión dada por lo general con accesorios terminales):

a) Seleccione el codo sin tuberías conectadas o bien con el comando CM, seleccione un codo de
extremo roscado, dentro de los disponibles en nuestro catálogo de productos.

b) Haciendo click en el extremo de unión común (medidas propias del catálogo de Acqua System).
Dibuje la línea de tubería que desee

c) Ahora escoja extremo roscado. Y haciendo click derecho dibuje la tubería (Veriﬁque que la
tubería a utilizar contenga las medidas de unión en pulgadas) o la unión roscada.

42

<!-- p. 44 -->

UNIDADES:

Para mejorar la correspondencia de unidades entre las diferentes uniones con extremo roscado, las
dimensiones de la unión en el extremo con roca (macho o hembra) se determinaran escribiendo la
dimensión en PULGADAS y el programa hará la conversión automática.

Por ejemplo escriba ½ pulgadas o bien 0.5 pulgadas y automáticamente el programa convertirá esta
medida a 12.7 milímetros.

De esta forma se evitan errores de conversión.

43

<!-- p. 45 -->

4.4 Tees

A diferencia de la librería Duratop X/ Duratop XR, Acqua System no tiene Yee. Pero si contiene Tee
normal, con reducciones y con extremos roscados.

La Tee normal se encuentra como opción predeterminada. Ahora bien si unimos tuberías de diferentes
diámetros se creara Te de reducción central o excéntrica según sea el caso.

Para cambiar a otras opciones siga los pasos que se muestran a continuación:

• Insertar Tee Roscada

Para cambiar a una Tee con un extremo roscado siga los pasos a continuación:

a) Dibuje una Tee y seleccione la Tee y escriba el comando CS.
b) Diríjase a la ventana “Properties” y despliegue la lista de Tees.
d) Escoja la Tee roscada

44

<!-- p. 46 -->

Se puede dibujar la Tee escribiendo el comando CM y despliegue la lista en la barra de propiedades de
Tees. Escoja la Tee roscada necesaria.

45

<!-- p. 47 -->

4.5 Unión, niple, cupla.

• Insertar una unión

En el sistema de Acqua System una unión es insertada cuando una tubería es dividida en dos elementos.
Para insertar una unión siga las instrucciones de la sección 3.4.

Para cambiar la unión por otros accesorios seleccione la unión y en la ventana de “Properties”
seleccione el accesorio deseado. Por ejemplo una Cupla eléctrica.

46

<!-- p. 48 -->

4.6 Tapones

• Insertar un tapón

Grupo Dema ha suministrado la librería Acqua System con tapones para los extremos de las tuberías.
Para insertar estos accesorios siga los pasos de la sección 3.6.

47

<!-- p. 49 -->

4.7 Llaves de paso/válvulas

• Insertar Llaves de paso/Válvulas

a) Escriba el comando CM, por defecto el programa le ofrecerá insertar el ultimo accesorio utilizado
(haga click para insertarlo si es el que desea).
b) Diríjase a la ventana “Properties” y despliegue la lista en la barra de propiedades.
d) Escoja la llave o válvula que desea
e) Acerque la Llave o válvula que eligió a la tubería en la cual la requiere, la misma se tornara azul.
Haciendo click en la misma la llave o válvula se insertara automáticamente con las medidas
necesarias (siempre que las mismas se encuentren deﬁnidas en nuestro catálogo).

48

<!-- p. 50 -->

4.8 Accesorios de montaje de montaje

La librería Grupo Dema Revit® con el objetivo de brindar no solo soluciones de instalación sino además
de montaje de las distintas instalaciones ofrece un sistema integral de grampas como los es la línea
DEMA FIX dirigida tanto al sistema de Acqua como al de Duratop (ver sección de accesorios 5.0).

49

<!-- p. 51 -->

4.9 Kits - Productos especíﬁcos con parámetros de ajuste

Para una mayor agilidad a la hora de ejecutar el tendido de las instalaciones además de las piezas de
nuestros productos ejecutamos Kits en donde cada elemento que los conforma se puede regular de
forma independiente pero siempre con la lógica del conjunto. Por ejemplo regular:

\- ORIENTACION REJILLA
\- ORIENTACION PILETA
\- LARGO DEL PROLOONGADOR

50

<!-- p. 52 -->

5.0 Accesorios montaje

Grupo DEMA, diseño y elaboro un sistema integral de grampas de superior calidad, con una gran
resistencia mecánica y prolongada vida útil.

GRAMPA PLASTICA GRAMPA PLASTICA GRAMPA PLASTICA A
AJUSTABLE A CREMALLERA CREMALLERA CON GOMA

KITS DE FIJACION PERFILES DE MONTAJE

Las mismas están destinadas a las líneas Acqua System y Duratop x/xr ya que más allá de que podrían
sujetar las tuberías de SIGAS THERMOFUSION la norma NAG 200 indica utilizar únicamente grampas
metálicas.

51

<!-- p. 53 -->

6.0 Línea de producto - Sigas Thermofusión

6.1 Tipos de tuberías

La línea de Sigas Thermofusión es el primer sistema para instalaciones internas de gas, en
acero-polietileno, con unión por Thermofusión lo que brinda una triple seguridad para la conducción de
gas que además aportar un signiﬁcativo ahorro de tiempos y costos de instalación.

Las tuberías de Sigas vienen con un largo comercial de 4mts y cuyos diámetros van desde Ø20mm a
Ø110mm

52

<!-- p. 54 -->

6.2 Codos

Al dibujar dos tuberías con un ángulo correcto un codo predeterminado será insertado.Para cambiar a
un codo especíﬁco siga los pasos a continuación:

a) Dibuje un codo estándar que conecte dos tuberías.

b) Seleccione el codo.
c) Diríjase a la ventana “Properties” (Propiedades) y despliegue la lista.

53

<!-- p. 55 -->

d) Encienda la casilla “Constrain to routing preferences” (Restringir a preferencias de
enrutamiento) de esta forma el listado de codos se limitara, es decir, esta opción activará solamente los
codos de una línea especíﬁca de productos.

54

<!-- p. 56 -->

6.3 Tee

La línea de Sigas contiene Tee normal y Tee con reducción central. La Tee normal se encuentra como
opción predeterminada. Ahora bien si unimos tuberías de diferentes diámetros se creara Te de
reducción central o bien a partir de un codo tildando el signo + que aparece

55

<!-- p. 57 -->

Desde una Tee normal se puede crear una te de reducción central simplemente seleccionando la
tubería del centro y eligiendo un diámetro menor, la pieza se creara sin problemas si la reducción se
encuentra dentro de las medidas de nuestro porfolio de productos. En caso la medida no se encuentre
deberá colocar posterior a la reducción la cupla de reducción pertinente

A

B

56

<!-- p. 58 -->

C

57

<!-- p. 59 -->

6.4 Uniones

• Insertar una unión
En el sistema de Sigas una unión es insertada cuando una tubería es dividida en dos elementos.
Para insertar una unión siga las instrucciones de la sección 3.4.
Para cambiar la unión por otros accesorios seleccione la unión y en la ventana de “Properties”
seleccione el accesorio deseado. Por ejemplo una Cupla eléctrica.

A

B

58

<!-- p. 60 -->

6.5 Reducciones

Dentro de la línea de Sigas podemos encontrar:
\- Cupla de Reducción
\- Bujes de Reducción
\- Reductor Anular

De forma predeterminada en las preferencias de enrutamiento cuando colocamos una tubería y
continua a esta colocamos una de menor diámetro se creara una Cupla de reducción, seleccionando la
misma podemos cambiarla por otro tipo de reducción sin problemas.

Para insertar una, siga los pasos que se muestran:

a) Dibuje una tubería de cualquier diámetro (Esta deberá ser la que va a sufrir la reducción).

b) Desde el extremo de esa tubería dibuje otra tubería de distinto diámetro (tubería de menor
diámetro).

c) En el punto donde cambia el diámetro se crea una reducción automáticamente, siempre que la
variación de diámetros entre las tuberías se encuentre dentro de las establecidas en nuestro
portfolio.

A

B

59

<!-- p. 61 -->

d) Elección de otro tipo de reductor, bastara con seleccionar el reductor y dirigirse a la Barra de
propiedades para cambiarlo por el que necesitemos.

Siempre es ideal tener tildado “Restringir a preferencias de enrutamiento” ya que esto permite que la
visualización de piezas a elegir sea aquella que está ligada a lo que buscamos hacer

En el caso del Reductor anular, para la correcta inserción del mismo durante el cambio de diámetros lo
ideal es colocarlo primero en los tipos de transiciones. (Dentro del orden de las preferencias de
enrutamiento)
Hacer esto en caso de usar el reductor anular de lo contrario mantener las preferencias de
enrutamiento como vienen por defecto

60

<!-- p. 62 -->

6.6 Tapones

• Insertar un tapón

Grupo Dema ha suministrado la librería Sigas Thermofusión con tapones para los extremos de las
tuberías. Para insertar estos accesorios siga los pasos de la sección 3.6.

61

<!-- p. 63 -->

6.7 Llaves de paso/Válvulas

• Insertar Llaves de paso/Válvulas

a) Escriba el comando CM, por defecto el programa.

b) le ofrecerá insertar el ultimo accesorio utilizado
(Haga click para insertarlo si es el que desea).

c) Diríjase a la ventana “Properties” y despliegue la
lista en la barra de propiedades.

d) Escoja la llave o válvula que desea.

e) Acerque la Llave o válvula que eligió a la tubería en la cual la requiere, la misma se tornara azul.
Haciendo click en la misma la llave o válvula se insertara automáticamente con las medidas
necesarias (siempre que las mismas se encuentren deﬁnidas en nuestro catálogo).

A B

Haciendo click sobre la pieza le aparecerán dos signos y

Le permitirá rotar la pieza Le permitirá cambiar el sentido de la pieza

62

<!-- p. 64 -->

En el caso de la Válvula esférica de Bronce la misma no debe ser colocada directamente en la tubería ya
que la conexión es por roscado, se requiere una pieza de transición

A B

Armamos un kit de Válvula + transición macho para que la salida sea directamente en milímetros que es
como trabajamos el sistema.

63

<!-- p. 65 -->

6.8 Tablas y vista de veriﬁcación

Como en todas nuestras líneas, Sigas Thermofusión cuenta con tablas de accesorios, uniones y tuberías
así como una vista de veriﬁcación que permite veriﬁcar las longitudes máximas o bien si hay alguna
pieza que este por fuera de las medidas de nuestro porfolio.

En la vista de veriﬁcación se visualizara en rojo aquellas tuberías que superen el largo máximo (largo de
comercialización), al igual que las uniones o accesorios que no pertenezcan al portfolio de nuestros
productos.

64

<!-- p. 66 -->

7.0 Línea de producto - Tubotherm

7.1 Características del sistema

Tubotherm es el primer piso térmico argentino desarrollado en Polietileno de Alta Resistencia Térmica
PERT.

Sus ventajas frente al polietileno reticulado son:
\-Máxima seguridad en las uniones
\-Mayor ﬂexibilidad y facilidad de trabajo
\-Material reciclable, apto para construcción sustentable
\-Menor pérdida de carga
\-Alta resistencia al calor y presión
\-Gran estabilidad y resistencia al envejecimiento

65

<!-- p. 67 -->

Como su nombre lo indica en Tubotherm la unión en el sistema se da por Thermofusión lo que permite
una instalación altamente segura con la posibilidad de reparar cualquier rotura o pinchadura accidental
dejando la instalación con el mismo valor agregado de origen.

7.2 Tipos de tuberías

Dentro de la librería de Tubotherm contamos con Tuberías de Polietileno PERT cuya longitud máxima
dependerá del rollo que se compre, la presentación general o más usada son rollos de 100 mts.

\- Polietileno PERT 100m Ø16 Ø20
(Presentación comercial Rollo de 100 mts)

\- Polietileno PERT 120m Ø16 Ø20
(Presentación comercial Rollo de 120 mts)

\- Polietileno PERT 240m Ø16 Ø20
(Presentación comercial Rollo de 240 mts)

Si bien este tipo de tuberías viene en diámetros de Ø16 - Ø20 - Ø25 - Ø32.
En el sistema de Piso térmico Tubotherm se trabaja con los diámetros de Ø16 - Ø20
Más allá que los rollos vengan de hasta 240mts el largo máximo para cualquier circuito es de 100mts

7.3 Uniones - Sistema continuo

La longitud de presentación de los rollos de Tubotherm en conjunto con la unión por Thermofusión
permite el aprovechamiento del tubo otorgándonos libertad en el diseño de los circuitos sin limitarnos
al largo del rollo.
Para la confección de la tubería Polietileno PERT 100 m y que se pueda trabajar con la ﬂexibilidad real en
el software, Grupo DEMA® confecciono 3 tipos de uniones dos de ellas no son piezas reales sino que
sirven de soporte para ejecutar el tendido de este sistema.

Curva Unión en U Unión normal

66

<!-- p. 68 -->

7.3.1. TUBOTHERM - Curva

Curva que se utilizara en los cambios de sentido.

67

<!-- p. 69 -->

Este tipo de unión TUBOTHERM – Curva nos permitirá realizar un tendido completamente ﬂexible
(ángulos adaptativos). Con las limitaciones pertinentes en función del diámetro de la tubería.

68

<!-- p. 70 -->

Si bien el sistema es completamente ﬂexible no se debe estrangular la tubería para esto se tiene que
tener en cuenta que el Radio de curvatura no tiene que ser menor a 5 veces el diámetro de la tubería.
Es por eso que Grupo DEMA® confecciono las familias (TUBOTHERM - Curva TUBOTHERM - Unión en U)
teniendo en cuenta estos parámetros.

D: diámetro de tubería en función de la tubería que
estemos usando en el sistema

Radio de curva: Este parámetro es editable para poder
regular la curva sin embargo está condicionado por R

R: Determina el radio mínimo de curvatura que puede
tener la unión con lo cual, si por error colocáramos un
Radio de curva no admisible en función del diámetro de la
tubería, la familia adoptara este valor de curvatura.

En caso el Radio de curva sea un valor admisible, la familia tomara este valor como referencia y Radio de
curva=R como se muestra en el siguiente ejemplo:

69

<!-- p. 71 -->

Ahora bien en caso el Radio de curvatura \< R (mínimo), la curvatura adoptada será R evitando así que
generemos un tendido que a la hora de ejecutar la obra genere problemas en la instalación.

En el siguiente cuadro podemos ver el comportamiento de la familia

7.3.2. TUBOTHERM – Unión en U

Esta Unión en U o curva anti estrangulamiento permitirá generar el diseño del tendido de la tubería
cuando por un tema de cálculo la separación entre la tuberías resulta menor al diámetro mínimo
admisible para la curvatura de la tubería.

70

<!-- p. 72 -->

La curva tomara la forma adecuada en función del diámetro y espaciado de la tubería, este espaciado lo
podemos regular:

A) Seleccionamos la Curva U

B) Nos dirigimos a la barra de propiedades “Properties”

C) Dentro de Cotas modiﬁcamos el Parámetro “Ancho Tubería”

71

<!-- p. 73 -->

D) Una vez modiﬁcado, el espaciado de las tuberías cambiará y con este, la Curva U adoptará la forma
adecuada.

Espaciado original

72

<!-- p. 74 -->

Espaciado ﬁnal

De esta forma la Librería Grupo DEMA® asegura que durante el diseño del tendido se eviten
estrangulamientos indebidos así como un cálculo más exacto del tendido diseñado.

A continuación se puede ver el comportamiento de la familia:

Cuando el espaciado supera el mínimo requerido de curvatura por defecto la familia no se podrá usar ya
que en este caso lo que se debe usar es la familia TUBOTHERM - Curva y no la familia TUBOTHERM -
Unión en U.

73

<!-- p. 75 -->

7.3.3. TUBOTHERM – Unión normal

• Insertar una unión
En el sistema de Tubotherm la unión se insertara cuando una tubería es dividida en dos segmentos. Para
insertar una unión siga las instrucciones de la sección 3.4

7.4 Distribución del tendido Tubotherm

Como lo ilustran los dibujos, la distribución de tubos puede tomar distintas formas: Serpentina, Espiral,
Combinado (serpentina + espiral), según la geometría de cada habitación, la separación de las cañerías
y el criterio profesional a la hora de diseñar el mismo.

74

<!-- p. 76 -->

7.4.1 Tendidos y Grupo sistema

Al tendido que diseñemos podemos aplicarle un parámetro de grupo.
Grupo DEMA® creo un parámetro llamado “Grupo Sistema” el cual está también incluido en todos
nuestros catálogos, el mismo lo que nos permite es agrupar una instalación que estemos ejecutando
(sea cual sea el sistema). La ventaja principal que nos otorga este parámetro es que en las tablas de
cómputo este parámetro permitirá hacer un cómputo agrupando los diferentes sistemas o grupos que
deﬁnimos por medio del parámetro “Grupo Sistema”.

A) Selección del tendido/instalación:
Acercándose a alguno de los elementos de la instalación con el mouse el elemento se tornara azul,
posterior a esto y sin mover el curso apretamos TAB y el programa tornara azul todos aquellos
elementos que se encuentren vinculados.

B) Damos clic al mismo para ﬁjar la selección. La barra de Propiedades “Properties” cambiara porque
habremos seleccionado elementos de diferentes categorías.

C) Dentro de la barra de propiedades “Properties” nos aparecerán aquellos parámetros que podemos
trabajaren este conjunto.

D) Nos dirigimos a la categoría “Texto” y Dentro del parámetro “Grupo Sistema” Escribimos el
nombre que quedemos dar a este tendido o instalación

75

<!-- p. 77 -->

E) Hacemos clic fuera de la barra de propiedades y ya este tendido estará agrupado.
Si vamos a la tabla de computo de Tuberías (Schedule) veremos que las tuberías estarán agrupadas
además del diámetro y tipo de tubería por el “Grupo sistema” al que pertenecen.

76

<!-- p. 78 -->

7.4.2 Tabla de tubería

\- Art-Numero: Código de la pieza/tubería para realizar el pedido a nuestros distribuidores
\- Diámetro: La tabla agrupara tuberías con el mismo diámetro
\- Serie/Tipo: La tabla agrupara tuberías del mismo tipo en caso el sistema tuviera más de un tipo de
tuberías
\- Comentario de Tipo: Nos recuerda la longitud máxima de este tipo de tubería
\- Longitud
\- Grupo Sistema: Parámetro asignado por el instalador proyectista

7.4.3 Tabla de tubería ﬂexible

En esta Tabla se realizara el cómputo de:
• TUBOTHERM – Curva
• TUBOTHERM – Unión en U

Estas son las familias que permitirán la ejecución de un sistema ﬂexible y de las cuales se podrá obtener
la longitud de trabajo para obtener un cómputo de mayor precisión.

77

<!-- p. 79 -->

\- Art-Numero: En este caso el código será el mismo que las tuberías en función del diámetro usado
\- Diámetro: La tabla agrupara tuberías con el mismo diámetro
\- Nombre en catalogo: Nos diferenciara una familia de otra
\- Total: Número de ejemplares usados en el sistema
\- Longitud: Longitud del tendido de la familia
\- Grupo Sistema: Parámetro asignado por el instalador proyectista.

7.5 Accesorios

Los diferentes tendidos que generemos dentro del sistema los podremos manejar desde nuestro Kit de
Colectores. La cantidad de circuitos podrá ir desde 2 a 7 en función de los espacios que necesitemos
acondicionar.

Para una más rápida y práctica ejecución del sistema, así como en la realidad tenemos a disposición
dentro del catálogo BIM Grupo DEMA®:

\- Kit Colector Plástico (Izq/Der)
\- Kit Colector con Caudalímetro (Izq/Der)
\- Kit Colector con Bypass y Caudalímetro (Izq/Der)

Podrá utilizar el que crea pertinente según la instalación.
El kit está compuesto de todos aquellos accesorios necesarios para su uso, por lo cual además del
cómputo de cantidad y tipos de Kits Colectores se podrá obtener el listado de accesorios interno del
mismo.

Si bien la comercialización de cada Kit Colector ya viene armado y con todos los elementos necesarios.
Ofrecemos la posibilidad de saber la composición del Kit para etapas posteriores de gestión y
mantenimiento.

78

<!-- p. 80 -->

Kit Colector Kit Colector con Kit Colector con Bypass
Plástico Caudalímetro y Caudalímetro

7.5.1 Kit Colector

79

<!-- p. 81 -->

Cada Kit Colector vendrá con una serie de parámetros que se podrán editar:

Altura desde NPT: Por defecto la familia
vendrá con un desfase de 40cm que es la
altura mínima a la que debe estar el gabinete
sobre el NPT

Numero de Circuitos: Podremos elegir el
número de circuitos del Kit (2 a 7 circuitos)
dependiendo del kit

Ver gabinete: Tildando o no esta casilla
podremos ver o no el gabinete del Kit

Desfase: Podremos regular la altura del Kit
teniendo en cuenta ya el desfase mínimo de
40cm

d: Deﬁniremos en que diámetro trabajara el
sistema Ø16 o Ø20

Ver o no gabinete:

80

<!-- p. 82 -->

7.5.2 Insertar Kit Colector

A) Para insertar el mismo bastara con escribir CM y seleccionar en la barra de propiedades
“Properties” el Kit pertinente. Además dependiendo del diseño y proyecto, la entrada de los Kits puede
ser izquierda o derecha.

B) Elegir Colocar en Plano de Trabajo

C) Ir al muro que funcionará de anﬁtrión del mismo

81

<!-- p. 83 -->

D) Previo a hacer clic para insertar el Kit deﬁnir el desfase y diámetro de trabajo

E) Transición: Rosca a Thermofusión
En el caso de la conexión del mando y colector previo a la conexión con la tubería se deberá colocar una
transición
Como ser Tubo macho o un Codo 90° con roca macho por ejemplo, se usara el accesorio de pertinente
según la situación.

Para colocar el mismo primero se debe deﬁnir el tamaño de la pieza y después con simplemente acercar
la misma al punto de unión la misma se unirá automáticamente

82

<!-- p. 84 -->

A B

A B

Una vez la transición de rosca a Thermofusión este establecida se puede seguir ejecutando el tendido
del sistema de la forma habitual.

F)

83

<!-- p. 85 -->

7.5.3 Tabla Kit Colector

En la tabla de Kits Colectores nos dará un total de los Kits que estemos usando en nuestro proyecto de
diseño ya que según la envergadura del mismo se usara uno o más Kits. Como sugerencia cada nivel
deberá tener su propio Colector de circuitos.

En la misma los datos de muestra serán:

\- Grupo sistema: Nombre del colector o del sistema que le asignemos
\- Art-Numero: Código del Kit para realizar el pedido a nuestros distribuidores
\- Nombre en catalogo: Nombre del kit elegido
\- Total: Recuento de Kits usados en el proyecto

7.6 Bloques de Diseño

En nuestro sistema la distribución del tendido puede tomar distintas formas (serpentín, espiral o
combinado) La elección del diseño dependerá de dos factores. Un factor es la geometría del local y el
otro la separación entre tubos. Por ejemplo la forma espiral permite aplicar separaciones de hasta 0,10
mts entre tubos, sin riesgos de que se presenten estrangulamientos.
Pero además otro punto clave a la hora de determinar el diseño del tendido es si el local a acondicionar
tiene perímetros con grandes vanos. En este caso en el área más cercana al vano debería ejecutar un
tendido con menor espaciado entre las tuberías.
En la instalación del sistema de Tubotherm tenemos diferentes elementos constructivos que se tiene
que tener en cuenta. Entre ellos:
• Aislación térmica: Aislación Horizontal - Aislación Vertical ( junta de dilatación)
• Manta Aislante
• Film de Polietileno
• Precintos

84

<!-- p. 86 -->

Para los ﬁnes prácticos del sistema y para tener en cuenta todos estos factores y elementos Grupo
DEMA® desarrollo Bloques de Diseño.

El Bloque de Diseño será Regular o Irregular y la geometría en cada uno se podrá acomodar en función
de la geometría del local pero además se podrá establecer si el tendido de la instalación será simple o
bien combinado en lo que reﬁere al espaciado del mismo para así poder contrarrestar perdidas por
vanos de gran envergadura.
Cada uno de estos bloques tendrá parámetros que tendremos que manipular para obtener toda la
información necesaria.

85

<!-- p. 87 -->

7.7 Bloque Regular

Entenderemos como Bloque regular a aquel bloque que no tenga más de 4 lados

En este Bloque se deberán manejar ciertos parámetros para obtener la información necesaria y
correcta.

7.7.1 Insertar Bloque Regular

A) Colocar Bloque:
Escriba en comando CM, ir a la barra de propiedades y buscar el Bloque de Diseño, una vez seleccionado
y antes colocarlo veriﬁcar el nivel de trabajo así como el desfase si fuera pertinente.

86

<!-- p. 88 -->

B) Determinar medidas del Bloque

Seleccionando el bloque de diseño y dentro de la barra de propiedades en el área de Cotas
modiﬁcaremos según nuestras necesidades Lh-Lx-Ly

Lh: Altura del Contrapiso
Ly: Largo eje Y (Vertical)
Lx: Largo eje X (Horizontal)

C) Determinar Ø y espaciado del tendido

Seleccionando el bloque de diseño y dentro de la barra de propiedades en el área de Cotas
modiﬁcaremos según los criterios de diseño y necesidad Conexión a Colector - Espaciado tuberías -
Inicio del tendido.

87

<!-- p. 89 -->

Conexión a Colector: Diámetro de la tubería que
usaremos en el sistema
Espaciado tuberías: El espaciado que habrá entre
las tuberías del tendido
Inicio del tendido: Para regular el punto de inicio
del tendido

E) Datos en Tabla (Schedule)

• Tipo de Bloque de Diseño: Regular o Irregular
• Área: Área del Bloque de Diseño (Ly x Ly)
• Junta de dilatación: En caso el Área supere los 40m2 o los 8m de largo se recomienda la
realización de una junta de dilatación
• Art-Numero: El código será en función del Ø de la tubería del tendido el código puesto por
defecto en cualquier caso reﬁere a la línea Polietileno PERT - 100mts (Rollo de 100 mts)
• Borde Periférico: Se encontrara tildado si se tuvo en cuenta algún lado con vano de gran
importancia
• Borde Periférico Doble: Se encontrara tildado si se tuvo en cuenta dos lados con vanos de gran
importancia
• Longitud tubería: Área/Espaciado tubería
• Precintos: Sujetadores necesarios para ﬁjar el tendido. Longitud de tuberíax2
• Malla Cima: Para ﬁjación de tubos x m²
• Manta Aislante: Se toma la superﬁcie a calefaccionar y se le aplica un coeﬁciente de seguridad
• Rollo: La presentación comercial de la manta aislante se presenta en un rollo de 20m de largo
por 1 m de ancho. Esta columna determinara la cantidad de rollos necesario en función del área a
calefaccionar.

88

<!-- p. 90 -->

7.7.2 Bloque Regular con borde periférico

En caso tener un local que tenga vanos de gran importancia a la hora de considerarlos para el
acondicionamiento del espacio. Se deberá tildar la casilla Borde Periférico.

89

<!-- p. 91 -->

Una vez tildada esta restricción, El área del Bloque de Diseño se dividirá en dos.

Esta área se podrá regular en profundidad con el parámetro Borde Periférico que se encuentra dentro
del grupo de Cotas.

90

<!-- p. 92 -->

Parámetros

Bloque con Borde periférico

91

<!-- p. 93 -->

Bloque sin Borde periférico

A misma área del local (Área: 4m2), la longitud de Tubería y la cantidad de sujetadores varia ya que en
el Bloque de Diseño con Borde periférico no trabaja con un espaciado de tubería único.

92

<!-- p. 94 -->

7.7.3 Bloque Regular con Borde Periférico Doble

En caso tener un local que tenga vanos de gran importancia a la hora de considerarlos para el
acondicionamiento del espacio. Y que estos vanos además estuvieran sobre dos caras del espacio a
acondicionar

Una vez tildada esta restricción, el área del Bloque de Diseño se dividirá en dos.

93

<!-- p. 95 -->

Esta área se podrá regular en profundidad con el parámetro Borde Periférico Y (Eje vertical) - Borde
Periférico X (Eje horizontal) que se encuentra dentro del grupo de Cotas.

7.7.4 Cuadro comparativo situaciones Bloque Regular

En el cuadro se puede ver como en un mismo espacio geométrico con diferentes variables se obtiene
una longitud de tendido diferente.

94

<!-- p. 96 -->

7.8 Bloque irregular

Entenderemos como Bloque Irregular a aquel bloque que tenga dentro de su composición algún recorte
ya sea porque el espacio es así o bien porque dentro del mismo hay vacíos de gran importancia.

Al igual que en el Bloque Regular en este bloque se deberán manejar ciertos parámetros para obtener
la información necesaria y correcta.

7.8.1 Insertar Bloque Irregular

A) Colocar Bloque:
Escriba en comando CM, ir a la barra de propiedades “Properties” y buscar el Bloque de Diseño, una vez
seleccionado y antes colocarlo veriﬁcar el nivel de trabajo así como el desfase si fuera pertinente.

95

<!-- p. 97 -->

B) Determinar medidas del Bloque
Seleccionando el bloque de diseño y dentro de la barra de propiedades “Properties” en el área de Cotas
modiﬁcaremos según nuestras necesidades Lh-Lx-Ly

Lh: Altura del Contrapiso
Ly: Largo eje Y (Vertical)
Lx: Largo eje X (Horizontal)

Bloque que viene por defecto

C) Determinar medidas del vacío y ubicación dentro del área
Seleccionando el bloque de diseño y dentro de la barra de propiedades “Properties” en el área de Cotas
modiﬁcaremos según nuestras necesidades:

\1. Lx vacío: Largo eje X (Horizontal) para el vacío
\2. Ly vacío: Largo eje Y (Vertical) para el vacío
\3. Distancia a vacío X: Desde el eje de inicio al eje ﬁnal del vacío. Es importante que Distancia a
vacío X ≤ Lx pero nunca mayor porque nos daría un cálculo erróneo
\4. Distancia a vacío Y: Desde el eje de inicio al eje ﬁnal del vacío. Es importante que Distancia a
vacío Y ≤ Ly pero nunca mayor porque nos daría un cálculo erróneo.

96

<!-- p. 98 -->

• Distancia a vacío X \< Lx Distancia a vacío Y \< Ly

• Distancia a vacío X = Lx Distancia a vacío Y = Ly

97

<!-- p. 99 -->

D) Determinar Ø y espaciado del tendido

Seleccionando el bloque de diseño y dentro de la barra de propiedades “Properties” en el área de Cotas
modiﬁcaremos según los criterios de diseño y necesidad Conexión a Colector - Espaciado tuberías -
Inicio del tendido.

Conexión a Colector: Diámetro de la tubería que
usaremos en el sistema
Espaciado tuberías: El espaciado que habrá
entre las tuberías del tendido
Inicio del tendido: Para regular el punto de inicio
del tendido

98

<!-- p. 100 -->

E) Datos en Tabla (Schedule)

• Tipo de Bloque de Diseño: Regular o Irregular
• Área: Área del Bloque de Diseño (Ly x Ly)
• Junta de dilatación: En caso el Área supere los 40m2 o los 8m de largo se recomienda la
realización de una junta de dilatación
• Art-Numero: El código será en función del Ø de la tubería del tendido el código puesto por
defecto en cualquier caso reﬁere a la línea Polietileno PERT - 100mts (Rollo de 100 mts)
• Borde Periférico: Se encontrara tildado si se tuvo en cuenta algún lado con vano de gran
importancia
• Borde Periférico Doble: Se encontrara tildado si se tuvo en cuenta dos lados con vanos de gran
importancia
• Longitud tubería: Área/Espaciado tubería
• Precintos: Sujetadores necesarios para ﬁjar el tendido. Longitud de tuberíax2
• Malla Cima: Para ﬁjación de tubos x m²
• Manta Aislante: Se toma la superﬁcie a calefaccionar y se le aplica un coeﬁciente de seguridad
• Rollo: La presentación comercial de la manta aislante se presenta en un rollo de 20m de largo
por 1 m de ancho. Esta columna determinara la cantidad de rollos necesario en función del área a
calefaccionar.

7.8.2 Bloque Irregular con borde periférico

Deﬁniremos al bloque con borde periférico tildando dentro del cuadro de Propiedades “Properties”, en
el Grupo de Restricciones “Borde Periférico”

99

<!-- p. 101 -->

Una vez tildado el parámetro de Borde Periférico, dentro del grupo de Cotas deﬁnimos la profundidad
que debe tener este.

7.8.3 Cuadro comparativo situaciones Bloque Irregular

En el cuadro se puede ver como en un mismo espacio geométrico con diferentes variables se obtiene
una longitud de tendido diferente o bien como a una misma área según la geometría y condicionantes
la longitud puede cambiar.

100

<!-- p. 102 -->

7.9 Suelo Tubotherm

Grupo DEMA® deﬁnió dentro de su catálogo un tipo de suelo que no tiene un ﬁn constructivo
meramente sino que el objetivo es que se pueda usar este “Suelo Tubotherm” en conjunto con su tabla
correspondiente para poder deﬁnir y calcular los diferentes elementos que componen el sistema. Así
como la cantidad de circuitos que puede haber dentro de un mismo espacio, cuando por diseño el
proyecto exige mayor ﬂexibilidad en el formato y división de los circuitos.

7.9.1 Crear suelo y aplicar parámetros

La forma de trabajar con el Suelo Tubotherm será la misma forma con la que se trabaja cualquier suelo

A) Nos dirigimos a la solapa Arquitectura y dentro del grupo Construir elegimos suelo arquitectónico

B) Ejecutamos el suelo deﬁniendo el nivel en el que se va a trabajar

101

<!-- p. 103 -->

C) Una vez ejecutado el mismo tendremos que determinar la separación de tuberías del circuito

7.9.2 Tabla

102

<!-- p. 104 -->

Consideraciones: Para poder tener los datos calculados se debe usar el Suelo Tubotherm, además la
separación de tubería en cada suelo/circuito se podrá modiﬁcar tanto en la tabla como en la barra de
propiedades seleccionando el suelo.
El cálculo será automático y nos dará los valores totales de los elementos necesarios del sistema
separado por “Grupo Sistema” (nombre del circuito).

• Longitud de tubería
• Precintos
• Malla Cima
• Manta Aislante

7.10 Recomendaciones

7.10.1 Pasaje de Curva a Unión en U

Como preferencia de enrutamiento la unión por defecto para las tuberías será TUBOTHERM - curva
para cambiar el tipo de unión a TUBOTHERM - Unión en U, realizaremos los siguientes pasos:

A) Una vez dibujada la curva seleccione el segmento secundario (Entenderemos como segmento
secundario el que se creó al general la curva).

B) Una vez seleccionado el mismo procederemos a eliminarlo y seleccionar posteriormente la curva
de unión

103

<!-- p. 105 -->

C) Una vez seleccionando la curva nos dirigimos a la barra de propiedades, desplegamos la barra de
selección y buscamos la Unión en U. Automáticamente la familia cambiara.

D) Una vez ejecutado el cambio podemos continuar con el tendido inmediatamente o bien modiﬁcar
la longitud de separación entre las tuberías

Para tener en cuenta el sentido de la curva que vamos a cambiar tiene que ser izquierdo ya que en el
otro sentido el programa nos arrojara Error.

7.10.2 Avisos

El catalogo Tubotherm Grupo DEMA® contiene avisos de advertencia tanto en las tablas de computo
como en nuestra vista de veriﬁcación. Pero también algunas familias como los Bloques de diseño nos
mostraran un aviso en caso el área o lados de un espacio sea superior a la recomendada.

Ejemplo A:

Si bien el Área obtenida es menor a la recomendada (40m2) Uno de los lados es superior al máximo
aconsejable (8m). En este caso nos aparecerá esta advertencia a modo de consejo para dividir el área
en dos colocando una junta de dilatación pertinente.
A niveles prácticos esta sugerencia nos está diciendo que el circuito es muy grande por lo cual se debe
dividir en dos (usar dos bloques de diseño para completar el área a calefaccionar).

104

<!-- p. 106 -->

Ejemplo B:

En este caso ninguno de los lados del bloque es mayor a 8m pero el área obtenida del mismo es
superior a los 40m2. En este caso nos aparecerá esta advertencia a modo de consejo para dividir el área
en dos colocando una junta de dilatación pertinente.
Nuevamente a niveles prácticos esta sugerencia nos está diciendo que el circuito es muy grande por lo
cual se debe dividir en dos (usar dos bloques de diseño para completar el área a calefaccionar)

105

<!-- p. 107 -->

7.10.3 Vista de Veriﬁcación

Como en todos nuestros Catálogos, tenemos una vista de veriﬁcación. La única variante en esta línea es
que al ser Tubotherm una línea de color rojo, el color de alerta o error será verde ﬂuo.

Esta vista de veriﬁcación Tubotherm nos resaltara en Verde Fluo todos aquellos componentes del
sistema que estén por fuera de sus máximos establecidos como:

\- Largos de longitud de tuberías
\- Largo de lados de los bloques de diseño
\- Áreas mayores a las recomendadas tanto en bloques de diseño como en Suelos Tubotherm
\- Elementos que no sean propios del sistema

Esta vista nos ayudara a veriﬁcar situaciones que deberemos revisar para evitar trasladar errores a obra
o bien a un buen funcionamiento del sistema.

106

<!-- p. 108 -->

Prohibida la reproducción y difusión total o parcial del
contenido de este manual, por cualquier tipo de medio, sin
la previa autorización escrita por parte de la empresa Ferva
S.A.

Queda hecho el depósito que establece la Ley 11.723.
Derechos reservados.

La responsabilidad de Ferva S.A. en cuanto al contenido del
presente Manual Técnico se limita a informar a los usuarios
sobre las características de los productos y su mejor
utilización. En ningún caso pretende enseñar el oﬁcio de
instalador sanitario, como así tampoco el diseño y cálculo de
las intalaciones.

Ferva S.A. se reserva el derecho a modiﬁcar parcial o
totalmente el presente manual y los productos que
presenta sin previo aviso.

En caso de dudas, por favor contactar a:
soportebim@grupodema.com.ar

Av. Pte. Perón 3750
(B1754BAP) San Justo
Proviencia de Buenos Aires
República Argentina
Tel.: (54-11) 4480-7000
Fax: (54-11) 4441-1274
E-mail: tecnica@grupodema.com.ar
www.grupodema.com.ar
