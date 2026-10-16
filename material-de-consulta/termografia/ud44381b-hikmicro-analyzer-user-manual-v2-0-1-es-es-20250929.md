---
type: libro
title: "UD44381B_HIKMICRO Analyzer_User Manual_V2.0.1_es-ES_20250929"
author: ""
categoria: "TERMOGRAFÍA"
paginas: 116
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/TERMOGRAFÍA/UD44381B_HIKMICRO Analyzer_User Manual_V2.0.1_es-ES_20250929.pdf"
convertido: 2026-10-16
---

# UD44381B_HIKMICRO Analyzer_User Manual_V2.0.1_es-ES_20250929

> Texto extraído de `TERMOGRAFÍA\UD44381B_HIKMICRO Analyzer_User Manual_V2.0.1_es-ES_20250929.pdf` (116 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

HIKMICRO Analyzer

Manual de usuario V2.0.1

<!-- p. 2 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Información legal

© Hangzhou Microimage Software Co., Ltd. Todos los derechos reservados.
Sobre este manual
Este manual incluye las instrucciones de utilización y gestión del producto. Las figuras,
gráficos, imágenes y cualquier otra información que encontrará en lo sucesivo tienen
únicamente fines descriptivos y aclaratorios. La información incluida en el manual está
sujeta a cambios, sin aviso previo, debido a las actualizaciones de software u otros
motivos. Encuentre la última versión de este manual en la página web de HIKMICRO
(http://www.hikmicrotech.com).
Utilice este manual con la guía y asistencia de profesionales capacitados en el soporte del
producto.
Marcas registradas

y otras marcas comerciales y logotipos de HIKMICRO son
propiedad de HIKMICRO en diferentes jurisdicciones.
Las demás marcas comerciales y logotipos mencionados son propiedad de sus
respectivos dueños.
Descargo de responsabilidad
EN LA MEDIDA MÁ XIMA PERMITIDA POR LAS LEYES APLICABLES, ESTE MANUAL Y EL
PRODUCTO DESCRITO —INCLUIDOS SU HARDWARE, SOFTWARE Y FIRMWARE— SE
SUMINISTRAN «TAL CUAL» Y «CON TODOS SU FALLOS Y ERRORES». HIKMICRO NO
OFRECE GARANTÍAS, EXPLÍCITAS O IMPLÍCITAS, INCLUIDAS, A MODO MERAMENTE
ENUNCIATIVO MAS NO LIMITATIVO, AQUELLAS DE COMERCIABILIDAD, CALIDAD
SATISFACTORIA O IDONEIDAD PARA UN PROPÓ SITO EN PARTICULAR. EL USO QUE
HAGA DEL PRODUCTO CORRE BAJO SU Ú NICO RIESGO. EN NINGÚ N CASO, HIKMICRO
PODRÁ CONSIDERARSE RESPONSABLE ANTE USTED DE NINGÚ N DAÑ O ESPECIAL,
CONSECUENTE, INCIDENTAL O INDIRECTO, INCLUYENDO, ENTRE OTROS, DAÑ OS POR
PÉRDIDAS DE BENEFICIOS COMERCIALES, INTERRUPCIÓ N DE LA ACTIVIDAD
COMERCIAL, PÉRDIDA DE DATOS, CORRUPCIÓ N DE LOS SISTEMAS O PÉRDIDA DE
DOCUMENTACIÓ N, YA SEA POR INCUMPLIMIENTO DEL CONTRATO, AGRAVIO
(INCLUYENDO NEGLIGENCIA), RESPONSABILIDAD DEL PRODUCTO O EN RELACIÓ N CON
EL USO DEL PRODUCTO, INCLUSO CUANDO HIKMICRO HAYA RECIBIDO UNA
NOTIFICACIÓ N DE LA POSIBILIDAD DE DICHOS DAÑ OS O PÉRDIDAS.
USTED RECONOCE QUE LA NATURALEZA DE INTERNET IMPLICA RIESGOS DE
SEGURIDAD INHERENTES Y QUE HIKMICRO NO TENDRÁ NINGUNA RESPONSABILIDAD
POR NINGÚ N FUNCIONAMIENTO ANORMAL, FILTRACIONES DE PRIVACIDAD U OTROS

i

<!-- p. 3 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

DAÑ OS RESULTANTES DE ATAQUES CIBERNÉTICOS, ATAQUES DE PIRATAS
INFORMÁ TICOS, INFECCIONES DE VIRUS U OTROS RIESGOS DE SEGURIDAD PROPIOS DE
INTERNET; NO OBSTANTE, HIKMICRO PROPORCIONARÁ EL APOYO TÉCNICO OPORTUNO
DE SER NECESARIO.
USTED ACEPTA USAR ESTE PRODUCTO DE CONFORMIDAD CON TODAS LAS LEYES
APLICABLES Y SOLO USTED ES EL Ú NICO RESPONSABLE DE ASEGURAR QUE EL USO
CUMPLA CON DICHAS LEYES. EN ESPECIAL, USTED ES RESPONSABLE DE USAR ESTE
PRODUCTO DE FORMA QUE NO INFRINJA LOS DERECHOS DE TERCEROS, INCLUYENDO,
A MODO ENUNCIATIVO, DERECHOS DE PUBLICIDAD, DERECHOS DE PROPIEDAD
INTELECTUAL, DERECHOS RELATIVOS A LA PROTECCIÓ N DE DATOS Y OTROS
DERECHOS RELATIVOS A LA PRIVACIDAD. NO UTILIZARÁ ESTE PRODUCTO PARA
NINGÚ N USO FINAL PROHIBIDO, INCLUYENDO EL DESARROLLO O LA PRODUCCIÓ N DE
ARMAS DE DESTRUCCIÓ N MASIVA, EL DESARROLLO O PRODUCCIÓ N DE ARMAS
QUÍMICAS O BIOLÓ GICAS, NINGUNA ACTIVIDAD EN EL CONTEXTO RELACIONADO CON
ALGÚ N EXPLOSIVO NUCLEAR O EL CICLO DE COMBUSTIBLE NUCLEAR INSEGURO O EN
APOYO DE ABUSOS DE LOS DERECHOS HUMANOS.
RESPETE TODAS LAS PROHIBICIONES Y ADVERTENCIAS EXCEPCIONALES DE TODAS
LAS LEYES Y REGLAMENTOS APLICABLES, EN PARTICULAR, LAS LEYES Y
REGLAMENTOS LOCALES SOBRE ARMAS DE FUEGO Y/O CAZA. REVISE SIEMPRE TODAS
LAS DISPOSICIONES Y NORMATIVAS NACIONALES ANTES DE COMPRAR O UTILIZAR
ESTE PRODUCTO. TENGA EN CUENTA QUE USTED TIENE QUE SOLICITAR LOS PERMISOS,
CERTIFICADOS Y/O LICENCIAS CORRESPONDIENTES ANTES DE COMPRAR, VENDER,
PUBLICITAR Y/O UTILIZAR EL PRODUCTO. HIKMICRO NO SERÁ RESPONSABLE DE
CUALQUIER COMPRA, VENTA, COMERCIALIZACIÓ N Y USO ILEGALES O INADECUADOS, NI
DE NINGÚ N DAÑ O ESPECIAL, CONSECUENTE, INCIDENTAL O INDIRECTO DERIVADO DE
LOS MISMOS.
EN CASO DE HABER CONFLICTO ENTRE ESTE MANUAL Y LA LEGISLACIÓ N VIGENTE,
ESTA Ú LTIMA PREVALECERÁ .

ii

<!-- p. 4 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Convenciones de símbolos

Los símbolos que se pueden encontrar en este documento se definen del siguiente modo.

Símbolo Descripción

Peligro Indica una situación peligrosa que, de no evitarse, ocasionará o
podría ocasionar lesiones de importancia o incluso la muerte.

Indica una situación potencialmente peligrosa que, de no Precaución
evitarse, podría ocasionar daños de material, pérdida de datos,
deterioro del rendimiento u otros resultados imprevistos.

Nota Ofrece información adicional para destacar o complementar
puntos importantes del texto principal.

iii

<!-- p. 5 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Contenido

Capítulo 1 Vista general del producto ..................................................................................... 1
1.1 Introducción .................................................................................................................... 1
1.2 Flujos de trabajo ............................................................................................................. 2
1.3 Entorno de funcionamiento ........................................................................................... 3
1.4 Interfaz de la aplicación ................................................................................................. 3
Capítulo 2 Instalación, actualización y configuración básica del software ........................... 5
2.1 Instalación del software ................................................................................................ 5
2.2 Actualización del software ............................................................................................ 5
2.3 Desinstalar o modificar el software .............................................................................. 6
2.4 Configuración del software ........................................................................................... 6
2.4.1 Cambiar de idioma .............................................................................................. 6
2.4.2 Establecer las unidades ...................................................................................... 7
2.4.3 Cambiar el tema de apariencia .......................................................................... 7
2.4.4 Establecer el formato GPS ................................................................................. 7
2.4.5 Aceleración de hardware .................................................................................... 7
2.4.6 Ver y editar teclas de atajos ............................................................................... 7
2.5 Mantenimiento del software ......................................................................................... 8
2.6 Ayuda para los usuarios ................................................................................................ 9
2.6.1 Ver el manual de usuario .................................................................................... 9
2.6.2 Códigos de error y guía de solución de problemas .......................................... 9
2.6.3 Ver la información del cliente ........................................................................... 10
Capítulo 3 Administración de archivos ................................................................................ 11
3.1 Navegación por la página de administración de archivos ........................................ 11
3.2 Archivo local y Acceso rápido ..................................................................................... 12
3.3 Administración de Mis favoritos ................................................................................. 12
3.3.1 Crear Mis favoritos ............................................................................................ 13
3.3.2 Cambiar la ubicación de Mis favoritos ............................................................ 13

iv

<!-- p. 6 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

3.3.3 Ver los detalles de Mis favoritos ...................................................................... 13
3.4 Administración de favoritos ........................................................................................ 13
3.4.1 Crear favoritos ................................................................................................... 14
3.4.2 Cambiar de nombre los favoritos .................................................................... 14
3.4.3 Eliminar favoritos .............................................................................................. 14
3.5 Importar archivo ........................................................................................................... 14
3.6 Cambiar el nombre de archivo .................................................................................... 15
3.7 Eliminar archivo ............................................................................................................ 16
3.8 Añadir una etiqueta de color a un archivo ................................................................. 16
3.9 Ver y filtrar archivos ..................................................................................................... 16
3.9.1 Categorización y ordenación de archivos ....................................................... 17
3.9.2 Filtrar archivos ................................................................................................... 18
Capítulo 4 Análisis de imagen y vídeo .................................................................................. 20
4.1 Añadir vídeo/imagen a la lista de tareas .................................................................... 20
4.1.1 Añadir desde archivo local ............................................................................... 20
4.1.2 Añadir desde Mis favoritos ............................................................................... 21
4.1.3 Grupos de imágenes ......................................................................................... 22
4.2 Análisis de imágenes ................................................................................................... 23
4.2.1 Navegación para la pestaña Análisis (Imagen) .............................................. 26
4.3 Análisis de vídeo .......................................................................................................... 27
4.3.1 Navegación para la pestaña Análisis (vídeo).................................................. 28
4.3.2 Reproducción y configuración de vídeo radiométrico ................................... 29
4.4 Crear y analizar vídeos de tendencias ........................................................................ 30
4.4.1 Crear y reproducir vídeos de tendencias ......................................................... 30
4.5 Guardar y exportar archivos ........................................................................................ 31
4.5.1 Guardar imagen ................................................................................................. 32
4.5.2 Exportar imagen ................................................................................................ 33
4.5.3 Guardar/Exportar vídeo ..................................................................................... 34
Capítulo 5 Herramientas y operaciones de análisis ............................................................. 35

v

<!-- p. 7 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

5.1 Ajuste del diseño de la ventana .................................................................................. 35
5.1.1 Diseño rápido ..................................................................................................... 35
5.1.2 Diseño libre ........................................................................................................ 35
5.2 Zonas protegidas y su influencia ................................................................................ 37
5.3 Herramientas de edición de imagen ........................................................................... 38
5.3.1 Establecer el modo de visualización ............................................................... 40
5.3.2 Paletas y paletas invertidas .............................................................................. 42
5.3.3 Establecer isoterma .......................................................................................... 42
5.3.4 Aislamiento ........................................................................................................ 43
5.3.5 Detección de condensación ............................................................................. 44
5.3.6 Nivel y rango ...................................................................................................... 44
5.3.7 Distribución de color ......................................................................................... 46
5.3.8 Súperresolución ................................................................................................. 47
5.3.9 Rotar y cambiar el tamaño de una imagen ..................................................... 47
5.3.10 Edición avanzada de imagen ......................................................................... 48
5.3.11 Aplicar los parámetros de imagen a todas las imágenes de la lista de
tareas ................................................................................................................... 48
5.4 Herramientas de medición de temperatura ............................................................... 49
5.4.1 Añadir herramienta de medición ...................................................................... 49
5.4.2 Editar una herramienta de medición ................................................................ 52
5.4.3 Eliminar una herramienta de medición ............................................................ 52
5.4.4 Modificar parámetros de medición de la temperatura .................................. 53
5.4.5 Calcular el área .................................................................................................. 54
5.4.6 Establecer superposiciones de medición ....................................................... 55
5.4.7 Aplicar herramientas de medición a todas las imágenes de la lista de tareas
.............................................................................................................................. 57
5.5 Ver y exportar resultados de medición ....................................................................... 58
5.5.1 Ver resultados de medición de temperatura .................................................. 58
5.5.2 Ver el histograma de distribución de temperatura y el gráfico de líneas de
temperatura ......................................................................................................... 59

vi

<!-- p. 8 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

5.5.3 Ver y exportar vista térmica 3D ........................................................................ 60
5.5.4 Visualización de la curva de tiempo-temperatura para vídeo/transmisión en
vivo ....................................................................................................................... 61
5.5.5 Exportar la matriz de temperaturas de una imagen ....................................... 63
5.5.6 Exportar la matriz de temperaturas de un vídeo ............................................ 64
5.6 Ver y modificar anotaciones de imagen ..................................................................... 64
5.6.1 Crear y usar una plantilla de nota de etiqueta ................................................ 67
5.6.2 Establecer nota de etiqueta .............................................................................. 68
Capítulo 6 Generar un informe de imágenes ........................................................................ 70
6.1 Añadir y organizar imágenes térmicas ....................................................................... 71
6.2 Plantilla de informe ...................................................................................................... 72
6.2.1 Importar plantilla ............................................................................................... 74
6.2.2 Exportar plantilla ................................................................................................ 74
6.3 Editar informe ............................................................................................................... 74
6.3.1 Navegar por la interfaz de edición de informes .............................................. 75
6.3.2 Gestionar páginas ............................................................................................. 76
6.3.3 Editar objeto ....................................................................................................... 80
6.3.4 Eliminar objeto ................................................................................................... 97
6.3.5 Cambiar la plantilla de la página seleccionada .............................................. 97
6.4 Exportar archivo ........................................................................................................... 98
6.4.1 Exportar informe ................................................................................................ 98
6.4.2 Exportar objeto único ........................................................................................ 98
Capítulo 7 Análisis en vivo .................................................................................................... 99
7.1 Navegación por la pestaña En vivo ...........................................................................100
7.2 Conectar la cámara a través de USB ........................................................................101
7.3 Conectar la cámara a través de red ..........................................................................102
7.4 Establecer los parámetros del dispositivo ...............................................................105
7.5 Capturar imágenes .....................................................................................................106
7.6 Grabar vídeo ................................................................................................................107

vii

<!-- p. 9 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Capítulo 1 Vista general del producto

Este manual de usuario proporciona la guía de funcionamiento del Cliente. Para garantizar
un uso apropiado del Cliente y su estabilidad, consulte los siguientes contenidos y lea
detenidamente el manual antes de instalarlo y utilizarlo.

1.1 Introducción

El cliente de HIKMICRO Analyzer se usa para ver la información de temperatura incluida en
las imágenes térmicas y los vídeos radiométricos y para realizar análisis de datos de las
mediciones de temperatura.
Análisis de Archivos

Imágenes térmicas
Las imágenes térmicas realizadas por una cámara térmica se pueden importar al cliente
para la administración y el análisis de archivos.
El cliente proporciona funciones de administración de archivos, incluida la etiquetación
de archivos, la categorización, etc. Además, se pueden realizar análisis de archivos,
incluidas la edición de imágenes y el análisis de los datos de medición de temperatura.
Se pueden realizar múltiples operaciones para el análisis, como configurar las
herramientas de medición, ajustar los parámetros de medición, cambiar el modo de
visualización de las imágenes, establecer alarmas de color, etc. Tras el análisis, puede
ver los resultados de las mediciones y los gráficos, así como guardar las imágenes o
exportar el informe según sea necesario.
Vídeos radiométricos
Los vídeos radiométricos grabados con una cámara térmica también se pueden
importar al cliente para su análisis. Puede obtener los resultados de la medición
configurando las herramientas de medición, ajustando los parámetros de medición, etc.
Al mismo tiempo, las curvas tiempo-temperatura y los histogramas de distribución de
temperatura se mostrarán para que pueda comprobar los cambios y las distribuciones
de temperatura.
Vista y análisis en directo
Se puede conectar una cámara térmica al cliente para la vista en directo, y se puede
analizar la medición de temperatura en tiempo real para la imagen de la vista en directo.
Puede obtener los resultados de la medición configurando las herramientas de medición,
ajustando los parámetros de medición, etc.

1

<!-- p. 10 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

1.2 Flujos de trabajo

En esta sección se presentan los breves flujos de trabajo de análisis de archivos y de
análisis en directo.
Análisis de Archivos
\1. Use el dispositivo para obtener imágenes y vídeos térmicos.
\2. Importe los archivos en el cliente de HIKMICRO Analyzer para su análisis.
\3. Genere un informe de termografía en formato PDF, o en formato ODT para editarlo
posteriormente (no disponible para vídeos).
\4. Guarde el informe o compártalo con otras personas por correo electrónico.

Figura 1-1 Flujo de trabajo de análisis de archivos

Análisis en directo
\1. Conecte la cámara termográfica al cliente mediante USB o red, configure los
parámetros del dispositivo y compruebe la vista en directo.
\2. Establezca el modo de visualización de la imagen y configure las herramientas de
medición de la temperatura para ver los resultados de la medición en tiempo real.
\3. Capture imágenes y grabe vídeos durante la vista en directo y guarde los resultados de

2

<!-- p. 11 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

las mediciones, los gráficos y los registros de datos tras el análisis.

1.3 Entorno de funcionamiento

A continuación se indican los entornos de ejecución recomendados para instalar el
Cliente.
● Sistema operativo
○ Microsoft Windows 7/Windows 10/Windows 11 (sistema operativo de 64 bits)
○ Servidor Windows (sistema operativo de 64 bit)
● CPU: i5-4590 o superior
● RAM: 8G o superior
● Tarjeta gráfica: Serie RADEON X700 de 256 MB o más

1.4 Interfaz de la aplicación

Después de iniciar el cliente, se mostrará la interfaz de la biblioteca. En la parte superior
de la interfaz, haga clic en Biblioteca, Análisis, Informe o En vivo para cambiar a las
interfaces correspondientes.
Tabla 1-1 Introducción a las interfaces principales del cliente
Nombre Descripción general
Seleccione Biblioteca en la parte superior de la interfaz del cliente. La
biblioteca se utiliza para importar y administrar imágenes locales, vídeos
Material
radiométricos y otros materiales de análisis. Para la administración de la
biblioteca, consulte Administracióndearchivos.
Ventana principal para el análisis de imágenes y vídeos. Después de importar
archivos de la biblioteca a la Lista de tareas, puede cambiar a la pestaña
Análisis para comenzar el análisis. La pestaña de análisis ofrece herramientas
Análisis como edición de imágenes, configuración de parámetros de medición de
temperatura, etc. Para obtener más información, consulte Análisisdeimageny
vídeo.
Ventana para generar y editar informes. Los archivos de análisis de la Lista de
tareas se pueden convertir rápidamente en informes mediante plantillas de
informes. Los usuarios pueden editar aún más la vista previa del informe
Informe generado y exportar informes en diferentes formatos.
Para obtener información sobre operaciones específicas, consulte Generarun
informedeimágenes.

3

<!-- p. 12 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Nombre Descripción general

Nota
Los resultados del análisis de vídeo radiométrico no se pueden utilizar para
generar informes.

Pestaña para conectarse a cámaras térmicas o cámaras para análisis en
tiempo real. Durante el análisis, puede configurar la velocidad de fotogramas
En vivo del dispositivo, agregar herramientas de medición de temperatura, capturar
imágenes y grabar vídeos. Para operaciones específicas, consulte Análisisen
vivo.

4

<!-- p. 13 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Capítulo 2 Instalación, actualización y
configuración básica del software

2.1 Instalación del software

Abra el paquete de instalación del software y, a continuación, en la ventana emergente,
haga doble clic en para ejecutar la configuración y haga clic en Acepto los términos
del Acuerdo de licencia. Seleccione Instalación con un clic o Personalizar conforme sus
necesidades.
Instalación con un clic
El software está instalado en la ruta predeterminada: C:\Archivos de programa.
Instalación personalizada
Haga clic en y seleccione la ruta de instalación.
Instalar WinCap
El controlador WinCap se utiliza para buscar dispositivos en línea que estén en el mismo
segmento de red LAN que su dispositivo. Si necesita conectar su dispositivo al software
del cliente mediante una conexión de red para transmisión en vivo, asegúrese de que
WinCap esté instalado en el PC.
El asistente de instalación de software verifica automáticamente su sistema para ver si
se ha instalado el controlador. Marque Instalar WinCap como sugiere el software.
Después de la instalación, marque Crear icono en el escritorio, Abrir archivos RV y HRV
con HIKMICRO Analyzer de forma predeterminada, Abrir archivos JPEG con HIKMICRO
Analyzer de forma predeterminada según sea necesario.

2.2 Actualización del software

Antes de comenzar
Se ha instalado una versión anterior.
Antes de actualizar el software, asegúrese de que no lo está ejecutando.
Pasos
\1. Abra el paquete de instalación del software y haga doble clic en para ejecutar la
configuración.
\2. En la ventana emergente, haga clic en Actualizar.

5

<!-- p. 14 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Nota
● El software se actualizará en la misma ruta que la versión anterior.
● Si necesita conectar el dispositivo al software del cliente mediante una conexión de
red para transmisión en vivo, marque Instalar WinCap como sugiere el asistente de
actualización. El controlador WinCap se utiliza para buscar dispositivos en línea que
estén en el mismo segmento de red LAN que su dispositivo.
Después de la actualización, marque Crear icono en el escritorio, Abrir archivos RV y HRV
con HIKMICRO Analyzer de forma predeterminada, Abrir archivos JPEG con HIKMICRO
Analyzer de forma predeterminada según sea necesario.

2.3 Desinstalar o modificar el software

Antes de comenzar
Antes de desinstalar o modificar el software, asegúrese de que no lo está ejecutando.
Pasos
\1. Haga clic en > Panel de control > Procedimientos y funciones en el sistema
operativo Windows.
\2. Haga clic con el botón derecho sobre HIKMICRO Analyzer y, a continuación, seleccione
Desinstalar/Modificar o, simplemente, haga doble clic en HIKMICRO Analyzer.
\3. En la ventana emergente, seleccione:
– Desinstalar.
– Modificar.
Aparecerá un aviso emergente cuando la desinstalación o modificación se hayan
completado.

2.4 Configuración del software

En la ventana de ajustes, es posible cambiar el idioma de visualización, y las unidades de
temperatura y de distancia usadas en la visualización.
Nota
Algunos ajustes requieren reiniciar el HIKMICRO Analyzer para que surtan efecto.

2.4.1 Cambiar de idioma

En la esquina superior derecha, haga clic en > Preferencia para seleccionar un idioma
del sistema.

6

<!-- p. 15 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

2.4.2 Establecer las unidades

Pasos
\1. En la esquina superior derecha, haga clic en > Medición.
\2. Seleccione las unidades preferidas para temperatura, distancia y área.
\3. Guarde los cambios realizados.

2.4.3 Cambiar el tema de apariencia

Vaya a > Preferencias > Tema de apariencia para cambiar el tema entre Oscuro y
Brillante. El cambio tiene efecto después de hacer clic en Guardar.

2.4.4 Establecer el formato GPS

En el panel Información de la imagen, si una imagen contiene información GPS, esta se
mostrará como ajuste.
Pasos
\1. En la esquina superior derecha, haga clic en > Preferencia.
\2. Seleccione el formato de visualización.
\3. Haga clic en Guardar.

2.4.5 Aceleración de hardware

La aceleración de hardware utiliza la tarjeta gráfica del PC para acelerar el procesamiento
de imágenes térmicas y vídeos, a fin de mejorar la fluidez de la operación.
El software cliente verifica el hardware del PC para ver si la función es compatible. Si es
compatible, la función está activada de forma predeterminada.
Puede desactivar la función desde Configuración > Preferencias > Aceleración de
hardware cuando sea necesario.

Nota
Un botón de alternancia gris significa que el PC no admite la función.

2.4.6 Ver y editar teclas de atajos

Visualice y edite las teclas de atajos para la función en diferentes pestañas.
Pasos
\1. Acceda a la página de administración de las teclas de atajos: Configuración >

7

<!-- p. 16 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Preferencias > Teclas de atajos.
\2. En la lista, seleccione una para modificarla.
\3. Pulse las teclas en el teclado. Se admiten teclas únicas y combinaciones de teclas.

Figura 2-1 Reglas de las teclas de atajos
● Las teclas modificadoras como Ctrl, Alty Mayússon opcionales, mientras que la X es
obligatoria.
● La X podría ser una tecla de los siguientes tipos: teclas alfabéticas, teclas numéricas,
teclas de símbolos como !@#$%^&*(), teclas de función de F1 a F12 y teclas de
navegación como ↑↓←→.
\4. Compruebe si las teclas de atajos de la función están actualizadas en la lista.
\5. Guarde los cambios realizados.

Nota
Cuando ocurre un conflicto de teclas de atajos, el cliente lo maneja según las dos reglas
siguientes:
● Alcance del efecto. El alcance de una tecla de atajos se refiere al módulo funcional o
ventana donde surte efecto. Si los alcances de las teclas de atajos difieren, el cliente
responde a la tecla de atajos según el foco actual (ventana activa). Si los alcances
son los mismos, se aplica la regla de prioridad de la tecla de atajos.
● Prioridad. Una tecla de atajos configurada más tarde en el tiempo tiene mayor
prioridad. Si varios accesos directos comparten el mismo alcance, el cliente ejecuta el
que tenga mayor prioridad.

Resultado
Si desea restaurar las teclas de atajos predeterminadas, haga clic en Restablecer.

2.5 Mantenimiento del software

El cliente proporciona archivos de registro y volcado para solucionar problemas.
Archivos de registro
Los archivos de registro registran los datos de funcionamiento y ejecución del software
cliente.
Cuando necesite solucionar problemas, vaya a Configuración > Mantenimiento > Ruta del
registro para obtener la ruta donde guardar el registro. Descargue los registros y envíelos
al equipo de soporte técnico para analizar el problema.

8

<!-- p. 17 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Archivos de volcado
Un archivo de volcado es una instantánea de la memoria de un ordenador en un momento
específico, generalmente cuando un sistema, una aplicación o un proceso falla o
encuentra un error crítico. Captura el estado del sistema operativo, los procesos en
ejecución, los módulos cargados y el contenido de la memoria para proporcionar datos de
diagnóstico cruciales para la resolución de problemas.
Después de habilitar Guardar archivo de volcado, Windows crea un archivo de volcado
para solucionar problemas cuando el cliente se bloquea. Vaya a Configuración >
Mantenimiento > Ruta del archivo de volcado para obtener la ruta donde se guardará el
archivo de volcado. Descargue el archivo y envíelo al equipo de soporte técnico para
analizar el problema.

Nota
Se requiere la confirmación del Control de cuenta de usuario para habilitar o deshabilitar la
función de guardado de archivo de volcado.

2.6 Ayuda para los usuarios

Es posible ver el manual de usuario y la información de la versión del HIKMICRO Analyzer,
y enviarnos comentarios.

2.6.1 Ver el manual de usuario

En la esquina superior derecha, haga clic en para ver el manual y las nuevas
características.

2.6.2 Códigos de error y guía de solución de problemas

El cliente proporciona las causas y los métodos de gestión para los códigos de error
comunes. Los usuarios pueden hacer clic en el hipervínculo del código de error para saltar
a la sección correspondiente de la guía.

Nota
Si el código de error encontrado no está incluido en el documento, o si el problema
continúa sin resolverse después de seguir la guía, registre el código de error y
comuníquese con nuestro servicio de atención al cliente o soporte técnico para obtener
ayuda.

9

<!-- p. 18 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

2.6.3 Ver la información del cliente

En la esquina superior derecha, haga clic en > Acerca de para ver la versión del cliente,
el correo electrónico del soporte técnico, las licencias de código abierto, etc.

10

<!-- p. 19 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Capítulo 3 Administración de archivos

3.1 Navegación por la página de administración de archivos

Figura 3-1 Página de administración de archivos
\1. Acceso rápido a las carpetas. Capturas y Grabaciones son las dos carpetas
predeterminadas en Acceso rápido, y se utilizan para almacenar las imágenes y los
vídeos de los análisis de vídeo y los análisis en directo. También puede anclar otras
carpetas a Acceso rápido. Consulte ArchivolocalyAccesorápidopara obtener más
información.
\2. Carpeta de archivos locales. Puede ver los archivos almacenados en el ordenador local
e importarlos a Mis favoritos. Consulte Importararchivo.
\3. Mis carpetas favoritas. Puede administrar los archivos de imagen y vídeo importados
en las carpetas de Mis favoritos. El número en paréntesis representa el número de

11

<!-- p. 20 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

archivos importados y el número máximo de archivos que se pueden importar.
Consulte AdministracióndeMisfavoritosy Administracióndefavoritospara obtener
más detalles.
\4. Archivos. Vea los archivos en la carpeta seleccionada.
\5. Botones de operación de la lista de tareas. Las operaciones funcionan en todos los
archivos de la lista de tareas.
\6. Lista de tareas. Puede añadir archivos a la lista de tareas para analizarlos y generar un
informe posteriormente.
\7. Barra de herramientas de visualización de archivos, que incluye clasificación de
archivos, filtrado, actualización, cambio de modo de visualización (iconos grandes o
lista) y visualización de información de imágenes.
\8. Barra de herramientas de las carpetas favoritas, que incluye importación de archivos,
configuración de etiquetas de color, etc.
\9. Ruta de acceso rápido y carpetas de archivos locales en el PC local.

3.2 Archivo local y Acceso rápido

Archivo local y acceso rápido permite localizar, acceder y explorar carpetas rápidamente
en el ordenador local.
Archivo Local
Los archivos locales son carpetas en el ordenador local. Puede ver archivos en el archivo
local, añadir archivos a la Lista de tareas de HIKMICRO Analyzer o importar archivos en
Mis favoritos, etc.
Consulte Veryfiltrararchivospara obtener instrucciones sobre cómo ver y filtrar archivos.
Acceso rápido
Acceso rápido contiene las carpetas Capturas y Grabaciones de forma predeterminada.
Puede establecer manualmente las carpetas locales para el Acceso rápido.
● Capturas: almacena imágenes capturadas en análisis En directo y análisis de vídeos. La
ruta puede modificarse en > Ubicación > Imágenes capturadas en análisis y en
directo.
● Grabaciones: almacena vídeos grabados en análisis En directo. La ruta puede
modificarse en > Ubicación > Vídeo grabado en directo.
● Anclar/Desanclar una carpeta: Haga clic con el botón derecho en una carpeta y
seleccione Anclar a Acceso rápido/Desanclar de Acceso rápido.

3.3 Administración de Mis favoritos

12

<!-- p. 21 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

En Mis favoritos aparecen todos los archivos importados al Cliente y es posible navegar a
cualquiera de las carpetas específicas de Favoritos. Para los archivos importados desde
su ordenador local o desde cualquiera de la redes conectadas, podrá efectuar diferentes
operaciones, como ver los detalles, categorizar, editar, ordenar, añadir etiquetas, etc.

3.3.1 Crear Mis favoritos

Cuando abre el cliente por primera vez después de la instalación, tendrá que crear una ruta
para Mis favoritos.
En la ventana emergente, seleccione una carpeta para guardar los archivos.
Nota
● No se recomienda guardar los archivos directamente en la unidad C ni en el Escritorio.
● La carpeta para guardar los archivos debería ser una carpeta vacía.
● Es posible ver y editar la ruta de la carpeta para Mis favoritos. Consulte los detalles en
CambiarlaubicacióndeMisfavoritos.
Una vez configurada la ruta para Mis Favoritos, las imágenes de muestra se descargarán
automáticamente en Mis favoritos y podrán utilizarse para la posterior gestión de
materiales, el análisis de materiales y la generación de informes.

3.3.2 Cambiar la ubicación de Mis favoritos

Es posible ver o editar la ruta de guardado de la carpeta de Mis favoritos.
Pasos
\1. En la barra del menú, haga clic en .
\2. Haga clic en Ubicación.
\3. En Mis favoritos, haga clic en para seleccionar una ruta de carpeta o para editar
manualmente la ruta predeterminada.
\4. Haga clic en Guardar.

3.3.3 Ver los detalles de Mis favoritos

Haga clic con el botón derecho sobre Todos los archivos y seleccione Ver detalles para
ver la información básica, incluyendo la hora de creación, la última hora de edición, la
capacidad de la biblioteca y el número de archivos que hay en la biblioteca.

3.4 Administración de favoritos

Cree y nombre los favoritos según los distintos usos posibles. Puede importar archivos a
diferentes favoritos para categorizarlos en Mis favoritos.

13

<!-- p. 22 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Entre en Biblioteca > Mis favoritos > Todos los archivos para ver la lista completa de
favoritos.

3.4.1 Crear favoritos

Desde Mis favoritos, puede crear (carpetas de) favoritos para ordenar los archivos por
categorías.
En la página Biblioteca, haga clic en junto a Mis favoritos para crear una carpeta.

Nota
● Se puede crear un máximo de 32 carpetas de Favoritos diferentes e importar hasta 512
archivos en cada una de ellas. Se permite un máximo de 10 240 archivos en Mis
favoritos.
● El sistema crea la carpeta Ejemplo de favoritos por defecto y las imágenes de muestra
se importarán automáticamente a esta carpeta.

3.4.2 Cambiar de nombre los favoritos

Haga clic con el botón derecho sobre el nombre de la carpeta de Favoritos y seleccione
Cambiar el nombre para cambiarlo.

3.4.3 Eliminar favoritos

Haga clic con el botón derecho sobre el nombre de la carpeta de Favoritos y seleccione
Eliminar para eliminarla.

Nota
Puede encontrar los archivos en la carpeta de favoritos eliminados en la carpeta Todos
los archivos.

3.5 Importar archivo

Antes del análisis, puede importar archivos a Mis favoritos o a una o varias carpetas
específicas de Favoritos para categorizar y administrar los archivos.
Se pueden importar archivos en los siguientes formatos: *.jpeg, *.jpg, *.hrv y *.rv. Puede
importar al cliente un máximo de 10 240 archivos en total.

Antes de importar archivos, configure el Modo de importación según sea necesario.

14

<!-- p. 23 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Pasos
\1. (Opcional) Configure el Modo de importación. Copiar, Corte e Índice se pueden
seleccionar.
Haga clic en en la parte superior derecha del cliente y, a continuación, haga clic en
Modo de importación para configurar el modo de importación para las imágenes y los
vídeos por separado.

Modo de importación Descripciones

Copiar Copiar los archivos a Mis favoritos sin tocar los archivos
originales..

Corte Mover los archivos a Mis favoritos y eliminar los archivos
originales.

Índice Añadir los archivos indexados a Mis favoritos. Los cambios
se realizan directamente en el archivo de origen.

\2. En la página de la Biblioteca, importe los archivos mediante una de las siguientes
operaciones.
– Seleccione Todos los archivos o una de las carpetas específicas de Favoritos y haga
clic en Importar. Seleccione los archivos y haga clic en Abrir para importarlos al
cliente.
– Seleccione los archivos o carpetas en Archivo local. Haga clic con el botón derecho
en los archivos o carpetas, seleccione Importar a Favoritos y, a continuación,
seleccione los favoritos de destino para la importación.
– Abra una carpeta local en su PC con el explorador, seleccione y arrastre los archivos a
Todos los archivos o a una carpeta específica de Favoritos.
Nota
Cuando Mis favoritos o una carpeta de Favoritos específica estén vacíos, puede hacer
clic en la zona vacía de la derecha o arrastrar los archivos a esta área para importar
archivos.

3.6 Cambiar el nombre de archivo

Seleccione uno de los siguientes métodos para cambiar el nombre al archivo.
● Haga clic con el botón derecho en el archivo cuyo nombre desea cambiar y haga clic en
Cambiar el nombre.
● Marque el archivo al que le quiere cambiar el nombre. Haga clic en Más > Cambiar
nombre.

15

<!-- p. 24 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Nota
El nombre de archivo en el ordenador local no se modificará después de este cambio de
nombre.

3.7 Eliminar archivo

Es posible eliminar un único archivo o eliminar varios archivos simultáneamente.
Nota
Si elimina un archivo desde Todos los archivos también eliminará el archivo original; si
elimina un archivo de una de las carpetas específicas de Favoritos, solo eliminará el
archivo de dicha carpeta.

● Eliminar un único archivo:
○ Coloque el cursor sobre el archivo y haga clic en en la esquina inferior derecha del
archivo y, a continuación, haga clic en Aceptar en la ventana emergente.
○ Haga clic con el botón derecho sobre el archivo y seleccione Eliminar y, a
continuación, haga clic en Aceptar en la ventana emergente.
● Eliminar varios archivos simultáneamente:
Seleccione los archivos que quiera eliminar y haga clic en Eliminar en la barra de
herramientas y, a continuación, haga clic en Aceptar en la ventana emergente.

3.8 Añadir una etiqueta de color a un archivo

Si un archivo no tiene etiqueta de color, puede añadir una etiqueta al archivo; si un archivo
ya tiene una etiqueta de color, puede cambiar la etiqueta.
Puede añadir una etiqueta a un archivo para clasificarlo como sea necesario. Por ejemplo,
de acuerdo a la prioridad de gestión, puede añadir una etiqueta roja a un archivo que
necesite ser procesado inmediatamente.
Seleccione uno o varios archivos para etiquetar, coloque el cursor sobre la opción Etiqueta
en la barra de tareas y seleccione una etiqueta de color. La etiqueta agregada aparecerá
en la lista.
Haga clic con el botón derecho sobre el archivo con etiqueta y, a continuación, haga clic
en Restablecer etiqueta para restablecer la etiqueta añadida.

3.9 Ver y filtrar archivos

En las carpetas Favoritos, Acceso rápido y Archivo local, se admiten operaciones como
ordenar y filtrar según diferentes condiciones para ayudar a los usuarios a localizar

16

<!-- p. 25 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

rápidamente los archivos necesarios.
● Los archivos se pueden mostrar en forma de mosaico de iconos o en vista de lista.
Haga clic en para cambiar. En la vista de lista, puede arrastrar la columna de título
para ajustar el ancho de la columna.
● Para la categorización y ordenación de archivos, consulte Categorizaciónyordenación
dearchivos.
● Para filtrar archivos, consulte Filtrararchivos. Seleccione un archivo y haga clic en . A
continuación, la interfaz del lado derecho mostrará la información básica, incluido la
hora de captura, el nombre del archivo, la nota de texto adjunta o no, el ID del activo, etc.

3.9.1 Categorización y ordenación de archivos

Es posible categorizar y ordenar los archivos por hora de captura, etiqueta, etc.
Categorización de archivos
Los archivos de Mis favoritos se pueden categorizar por Hora de captura
(Anual/Mensual/Diaria), Etiqueta, ID de activo y Clasificación de fallo. En la esquina
superior derecha del cliente, haga clic en para establecer la condición de
categorización.
El nombre de la categoría de archivo, como el año/mes/día específico, se muestra a la
izquierda de la línea divisoria de categoría. Puede hacer clic en la casilla de verificación de
la izquierda para seleccionar todos los archivos de esta categoría, o hacer clic en en
la derecha para contraer esta categoría.
Hora de captura
Puede seleccionar Anual/Mensual/Diaria para categorizar los archivos.
Etiqueta
Categorice los archivos según sus etiquetas de color.
Consulte Añadirunaetiquetadecoloraunarchivopara establecer etiquetas de color.
ID de activo
El ID de activo es el ID o la información específica del objetivo observado. Se añade
manualmente o escaneando el código QR cuando el dispositivo captura la imagen
térmica. La categorización de archivos por ID de activo se utiliza para ver imágenes del
mismo activo u objetivo en diferentes momentos y estados para su análisis y
comparación.
Para una imagen con un ID de activo, puede ver el ID o el número en el área Información
de la imagen.
Clasificación de fallo
Clasificación de fallo es la etiqueta de nivel de fallo que se añade cuando el dispositivo

17

<!-- p. 26 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

captura imágenes durante un proceso de inspección.
Clasificación de fallo puede modificarse durante el análisis de imágenes térmicas.
Consulte Verymodificaranotacionesdeimagenpara obtener más información.

Nota
● La línea divisoria de categoría no mostrará ningún nombre o Desconocido para los
archivos sin la información de categoría específica.
● La categorización de archivos no está disponible en carpetas locales ni en carpetas de
acceso rápido.

Ordenación de archivos
Haga clic en para seleccionar una condición de clasificación. Los archivos se
clasificarán en orden ascendente/descendente por hora de captura, etiqueta o nombre.

Nota
Ordenar por tamaño solo está disponible en carpetas locales y de acceso rápido, mientras
que ordenar por etiqueta está disponible en las carpetas favoritas.

3.9.2 Filtrar archivos

Establezca condiciones para filtrar los archivos requeridos en carpetas locales, de acceso
rápido y favoritas, y mostrarlos.
Pasos
\1. Haga clic en para abrir el panel de filtros.
\2. Establezca las condiciones de filtro. Puede establecer una o varias condiciones de filtro.
Rango de tiempo
Filtre archivos cuya Hora de captura esté dentro del intervalo de horas establecido.
Nombre de archivo
Introduzca una palabra clave para filtrar los archivos cuyos nombres contengan la
palabra clave.
Etiqueta
Se refiere a las etiquetas de color.
Nota de texto
La nota de texto se refiere a los comentarios del usuario agregados a la imagen
cuando se realizó la captura. Puede seleccionar Con comentarios para filtrar

18

<!-- p. 27 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

imágenes con notas de texto; o seleccionar Sin comentarios para filtrar imágenes sin
notas de texto; o introducir una palabra clave de nota para filtrar imágenes cuyas
notas de texto contienen la palabra clave.
La nota de texto de una imagen se puede modificar durante el análisis. Consulte Very
modificaranotacionesdeimagenpara obtener más detalles.
Model dispstvo
Busque imágenes capturadas por dispositivos cuyo Modelo de dispositivo contenga
la palabra clave introducida.
El Modelo de dispositivo se puede ver en la información de la imagen.
ID de activo
Busque imágenes cuyo ID de activo contenga la palabra clave introducida.
El ID de activo es el ID o la información del objeto detectado agregado mediante el
escaneo del código QR o la entrada manual cuando se realizó la captura. El ID del
activo se puede ver en la página de información de la imagen.
\3. Haga clic en Filtrar para buscar los archivos objetivo.

Nota
● Al filtrar dentro de una carpeta de favoritos, se pueden filtrar simultáneamente los
archivos que cumplen los requisitos en sus subcarpetas. Al filtrar dentro de una
carpeta local o de acceso rápido, no se pueden filtrar los archivos en sus
subcarpetas.
● Las condiciones de filtrado permanecen sin cambios al cambiar entre carpetas del
mismo tipo (por ejemplo, entre carpetas locales) y el filtro se aplica automáticamente
al cambiar de carpeta.

\4. Opcional: Haga clic en > Restablecer para restablecer la condición del filtro.

19

<!-- p. 28 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Capítulo 4 Análisis de imagen y vídeo

Puede analizar imágenes radiométricas y vídeos, y generar informes para las imágenes.
El procedimiento principal es el siguiente.
\1. Añada a la lista de tareas las imágenes y vídeos que desee analizar. Consulte Añadir
vídeo/imagenalalistadetareaspara obtener más detalles.

Nota
Si un archivo está configurado para abrirse de forma predeterminada con este cliente,
puede iniciar directamente el cliente e introducir al análisis abriendo el archivo.

\2. Ajuste el diseño de la ventana cuando sea necesario. Consulte Ajustedeldiseñodela
ventanapara obtener instrucciones.
\3. Utilice herramientas para analizar las imágenes y los vídeos.
● Para analizar una imagen térmica, consulte Análisisdeimágenespara obtener
instrucciones.
● Para analizar un vídeo radiométrico, consulte Análisisdevídeopara obtener
instrucciones.
● Para crear y analizar vídeos de tendencias, consulte Crearyanalizarvídeosde
tendenciaspara obtener instrucciones.
\4. Guarde y exporte imágenes y vídeos modificados. Consulte Guardaryexportar
archivospara obtener instrucciones.
\5. Genere un informe de imágenes radiométricas. Consulte Generaruninformede
imágenespara obtener instrucciones.

Nota
Solo las imágenes y grupos radiométricos admiten la generación de informes.

4.1 Añadir vídeo/imagen a la lista de tareas

Antes de realizar el análisis, es posible añadir imágenes y vídeos a la lista de tareas.

4.1.1 Añadir desde archivo local

Añada uno o varios archivos de análisis (imágenes o vídeos) desde un archivo local a la
lista de tareas.
Seleccionar archivo
Seleccione uno o varios archivos. Se pueden seleccionar varios archivos de la siguiente

20

<!-- p. 29 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

manera:
● Marque la casilla de verificación del archivo.
● Haga clic con el botón izquierdo y arrastre para elegir varios archivos contiguos.
● Mantenga pulsada la tecla Ctrl y haga clic con el botón izquierdo para seleccionar varios
archivos no consecutivos; mantenga pulsada la tecla Mayús y haga clic con el botón
izquierdo en el primer y último archivo para seleccionar una serie de archivos.
Añadir a lista de tareas
● Añadir solo a la lista de tareas: Haga clic con el botón derecho y seleccione
Procesamiento de archivos > Añadir a la lista de tareas; o haga clic en Añadir a la lista
de tareas en la esquina superior derecha del cliente.
● Añadir a la lista de tareas y abrir el primer archivo en la ventana de análisis: Haga clic
con el botón derecho y seleccione Procesamiento de archivos > Analizar.
● Añadir todos los archivos de una carpeta a la lista de tareas: En la lista de archivos
locales, haga clic con el botón derecho en una carpeta y seleccione Añadir todo a la lista
de tareas o Analizar todo.

4.1.2 Añadir desde Mis favoritos

Añada uno o varios archivos de análisis (imágenes o vídeos) de Mis favoritos a la lista de
tareas.
Seleccionar archivo
Seleccione uno o varios archivos. Se pueden seleccionar varios archivos de la siguiente
manera:
● Marque la casilla de verificación del archivo.
● Mantenga pulsada la tecla Ctrl y haga clic con el botón izquierdo para seleccionar varios
archivos no consecutivos.
● Marque la casilla de verificación situada en el extremo izquierdo de la línea de categoría
y seleccione todos los archivos.
Añadir a lista de tareas

● Añadir solo a la lista de tareas: Haga clic con el botón derecho y seleccione
Procesamiento de archivos > Añadir a la lista de tareas; o haga clic en Añadir a la lista
de tareas.
● Añadir a la lista de tareas y abrir el primer archivo en la ventana de análisis: Haga clic
con el botón derecho y seleccione Procesamiento de archivos > Analizar.
● Añadir todos los archivos de una carpeta de Favoritos a la lista de tareas: Haga clic con
el botón derecho en una carpeta de Favoritos y seleccione Agregar todo a la lista de
tareas o Analizar todo.

21

<!-- p. 30 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

4.1.3 Grupos de imágenes

Las imágenes en la lista de tarea admiten la agrupación, y un grupo puede contener hasta
4 imágenes.
Influencia de los grupos de imágenes
● Influencia en la sincronización de parámetros de medición e imagen en la lista de
tareas:
○ Seleccione una imagen térmica y sincronice los parámetros o las mediciones. Se
sincronizan los parámetros y las mediciones de la primera imagen de los grupos de
imágenes y de las imágenes térmicas individuales de la lista de tareas.
○ Seleccione un grupo y sincronice los parámetros o las mediciones. Los parámetros y
mediciones de las imágenes térmicas no agrupadas en la lista de tareas se
sincronizan según la primera imagen del grupo seleccionado; los demás grupos de
imágenes térmicas en la lista de tareas sincronizan los parámetros y mediciones de
las imágenes correspondientes en el grupo seleccionado según el orden de las
imágenes.
● Al generar un informe, si la plantilla del informe contiene una página con el mismo
número de imagen térmica que en un grupo, puede importar rápidamente imágenes por
grupo.

Nota
Cuando hay grupos de imágenes en la lista de tareas, se utiliza una plantilla de informe
definida por el usuario. Basándose en la agrupación de archivos de la lista de tareas, el
cliente hace coincidir automáticamente los grupos de imágenes con las plantillas de
página con el número de imágenes correspondiente.
Si el número de imágenes de un grupo no se corresponde con la plantilla de página de la
plantilla de informe, el cliente selecciona la plantilla de página según el principio de
mostrar el mayor número posible de imágenes del grupo. Por ejemplo, si hay un grupo
de 3 imágenes en la lista de tareas y solo hay plantillas de página de 2 y 4 imágenes en
el informe, el cliente elegirá la plantilla de página de 4 imágenes para el grupo.

Agrupación automática
La lista de tareas ofrece la función de agrupación automática. Todas las imágenes
radiométricas en la lista de tareas se agrupan siguiendo el método establecido de arriba
hacia abajo.
● Haga clic en , establezca un método de agrupación y guarde para continuar.
● Haga clic en para desagruparlo todo.

Nota
Ajuste el orden de las imágenes antes de agruparlas automáticamente. Ahora ya no está

22

<!-- p. 31 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

permitido ajustar el orden de las imágenes dentro de un grupo.

Crear/Desagrupar manualmente un grupo de imágenes
\1. Seleccione los archivos que desee agrupar en la lista de tareas. Se permiten imágenes
o grupos. Se permiten hasta 4 imágenes en un grupo. Mantenga pulsada la tecla
Mayús y haga clic con el botón izquierdo para seleccionarlas de forma continua, y
mantenga pulsada la tecla Ctrl y haga clic con el botón izquierdo para seleccionarlas
de una en una.
\2. Seleccione Agrupar en el menú contextual. El número de imágenes del grupo se
muestra en la esquina superior izquierda de la miniatura del grupo.
\3. Vea las imágenes de un grupo. Seleccione un grupo y haga clic en Anterior, Siguiente
en la esquina inferior derecha de la ventana anterior.
\4. Desagrupe. Seleccione un grupo, haga clic con el botón derecho y seleccione
Desagrupar.

4.2 Análisis de imágenes

El análisis de imágenes incluye la visualización de información de imágenes, ajustes de
imágenes, parámetros de medición de temperatura y ajustes de herramientas, análisis de
gráficos y exportación de resultados de temperatura, visualización y modificación de
anotaciones de imágenes, y sincronización de parámetros de medición de
temperatura/herramientas en múltiples imágenes térmicas.
Tabla 4-1 Características del análisis de imágenes
Función Descripción
Incluye imagen visual (si está disponible), tipo de archivo,
resolución, rango de medición del dispositivo, modelo del
Ver información de
instrumento, hora de captura, etc. Consulte Navegaciónparala imágenes
pestañaAnálisis(Imagen)para conocer la ubicación de la
función.
Incluye cambio de modo de visualización, configuración de
Ajustar la imagen paleta, configuración de nivel y rango, isoterma, distribución de
para una mejor color, rotación de imagen, cambio de tamaño de imagen, edición
observación avanzada de imágenes, etc. Consulte Herramientasdeediciónde
imagenpara obtener más detalles.
Configurar los Los parámetros básicos de medición incluyen la temperatura
parámetros de atmosférica y la humedad.
medición de la Los parámetros de la ventana de IR se refieren a las ventanas de

23

<!-- p. 32 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Función Descripción
temperatura germanio u otros componentes ópticos agregados externamente
a la lente de la cámara/imagen térmica. La transmitancia óptica
y la temperatura se pueden modificar.
Consulte NavegaciónparalapestañaAnálisis(Imagen)para
conocer la ubicación de la función y los detalles de configuración
de Modificarparámetrosdemedicióndelatemperatura.
Las herramientas de medición se refieren a puntos, líneas,
polilíneas, rectángulos, elipses o polígonos dibujados en la
imagen para detectar temperaturas máximas, mínimas,
promedio y centrales dentro del área. La emisividad, la distancia
de medición y la temperatura reflejada se pueden establecer de
forma independiente para cada herramienta. Consulte Añadir
herramientademediciónpara añadir herramientas y Modificar
parámetrosdemedicióndelatemperaturapara la configuración
Establecer de parámetros.
herramientas de
medición y La herramienta delta se puede configurar para calcular
parámetros diferencias de temperatura entre herramientas de medición,
imágenes o constantes, con colores de fuente que indican los
niveles de rango delta. Consulte Añadirherramientademedición
para añadir una herramienta delta.
Cálculo del área de medición. Consulte Calcularelárea.
Se pueden agregar y ajustar libremente herramientas de
medición y superposiciones de información. Consulte Establecer
superposicionesdemediciónpara obtener más detalles.
En la ventana Temperatura medida puede consultar las
temperaturas máximas, mínimas, promedio y centrales de las
imágenes o herramientas de medición. Para abrir la ventana,
consulte Ajustedeldiseñodelaventanapara obtener más
detalles.Ver valores medidos y
gráficos y exportar Vea la vista 3D de herramientas de medición o imágenes y
los resultados exporte imágenes o datos CSV.
Vea histogramas de temperatura y gráficos de líneas de
herramientas de medición o imágenes y exporte imágenes de
gráficos o datos CSV.
Exporte la matriz de temperatura de toda la imagen en formato

24

<!-- p. 33 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Función Descripción
CSV.
Consulte Veryexportarresultadosdemediciónpara obtener
más detalles.
Las anotaciones de imágenes incluyen etiquetas de color,
clasificaciones de fallos, notas de etiquetas, notas de texto,
notas de imágenes, notas de voz, etc. Consulte Verymodificar
anotacionesdeimagenpara obtener instrucciones.
● Etiqueta de color: Se configura en las carpetas favoritas del
cliente. Se puede modificar durante el análisis.
● Clasificación de fallo: Se aplica a las imágenes capturadas en
modo de inspección con reglas preconfiguradas. Se puede
modificar durante el análisis.Gestionar
● Nota de texto: Texto añadido por el usuario durante la captura.anotaciones de
Se puede modificar durante el análisis.imágenes
● Nota de voz: Audio grabado por el usuario durante la captura.
No se admite la reproducción.
● Nota de etiqueta: Etiquetas de texto añadidas durante la
captura (requiere una plantilla de nota de etiqueta). Se puede
modificar durante el análisis.
● Nota de imagen: Imágenes visuales adicionales sobre el
objetivo. Solo ver.
● Notas de boceto: Gráficos dibujados por el usuario durante la
captura. Se puede mostrar/ocultar en el cliente.
Sincronice los parámetros de imagen y temperatura y las
herramientas de medición en las imágenes térmicas en una lista
Sincronización de la
de tareas para conseguir actualizaciones por lotes eficientes.
configuración de
Consulte Aplicarlosparámetrosdeimagenatodaslasimágenes
imagen y medición
delalistadetareasy Aplicarherramientasdemediciónatodas
lasimágenesdelalistadetareaspara obtener más detalles.

25

<!-- p. 34 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

4.2.1 Navegación para la pestaña Análisis (Imagen)

Figura 4-1 Pestaña Análisis (imagen)
\1. Lista de tareas. Se pueden añadir imágenes radiométricas, vídeos, grupos de imágenes,
vídeos de tendencias, etc., a la lista para su análisis o para generar informes. Consulte
Añadirvídeo/imagenalalistadetareaspara obtener instrucciones. El área de la
ventana principal muestra las imágenes y la información del archivo seleccionado en la
lista.
\2. Botones de operación de la lista de tareas. Las operaciones funcionan en todos los
archivos de la lista de tareas, por ejemplo, agrupación automática, operación por lotes
y borrado de la lista.
\3. Ventana de valor de la temperatura. Muestra las temperaturas medidas en la imagen y
herramientas de medición. Para abrir la ventana, consulte Ajustedeldiseñodela
ventanapara obtener más detalles.
\4. Herramientas de configuración de la paleta. Existen principalmente cuatro tipos de
paletas: las paletas comunes y sus versiones invertidas, la isoterma, la condensación y
el aislamiento. Consulte Paletasypaletasinvertidas, Establecerisoterma, Aislamiento,
Deteccióndecondensación, Nivelyrangoy Distribucióndecolorpara obtener más
detalles.
\5. Ventana del gráfico de temperatura. La distribución de temperatura y el gráfico de

26

<!-- p. 35 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

líneas están disponibles para toda la imagen o para las herramientas de medición
configuradas. Para abrir la ventana, consulte Ajustedeldiseñodelaventanapara
obtener más detalles.
\6. Imagen visual y ventana de vista 3D. Si la imagen radiométrica tiene una imagen visual
adjunta, puede añadir una ventana de imagen visual. Para abrir la ventana, consulte
Ajustedeldiseñodelaventanapara obtener más detalles. Para obtener más detalles
sobre la ventana de vista 3D, consulte Veryexportarvistatérmica3D.
\7. Panel de anotación. Vea y cambie las notas adjuntas a las imágenes radiométricas.
Consulte Verymodificaranotacionesdeimagenpara obtener más detalles.
\8. Panel de análisis de temperatura. Cambie los parámetros de medición, como la
temperatura y la humedad atmosféricas, la emisividad objetivo, la temperatura
reflejada y la distancia, en este panel. Consulte Modificarparámetrosdemediciónde
latemperaturapara obtener más detalles.
\9. Panel de información de archivo. Muestra la hora de captura, la resolución, el
dispositivo y otra información del archivo.
\10. Herramientas avanzadas de edición, rotación y cambio de tamaño de imágenes.
Consulte Ediciónavanzadadeimageny Rotarycambiareltamañodeunaimagenpara
obtener más detalles.
\11. Herramientas de análisis de medición. Utilice estas herramientas para añadir y editar
distintos tipos de mediciones, borrar todas las mediciones, etc. Consulte Añadir
herramientademediciónpara obtener más detalles.
\12. Modo de visualización. Si la imagen radiométrica tiene una imagen visual adjunta, se
pueden cambiar entre térmica, fusión, PIP, mezcla y visual. Consulte Establecerel
mododevisualizaciónpara obtener más detalles.
\13. Diseños y ventanas rápidos. Puede aplicar opciones de diseño rápido u organizar
libremente los diseños de las ventanas. Consulte Ajustedeldiseñodelaventanapara
obtener instrucciones.
\14. Guardado y exportación de archivos y datos.

Nota
Si la imagen térmica se captura cuando el dispositivo está en modo de prevención de
quemadura (el obturador del dispositivo está cerrado para evitar que el detector sufra
daños causados por objetivos inesperados a alta temperatura), aparecerá un aviso
recordando al usuario esta situación.

4.3 Análisis de vídeo

27

<!-- p. 36 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

4.3.1 Navegación para la pestaña Análisis (vídeo)

Figura 4-2 Análisis de vídeo radiométrico
\1. Lista de tareas. Se pueden añadir imágenes radiométricas, vídeos, grupos de imágenes,
vídeos de tendencias, etc., a la lista para su análisis o para generar informes. Consulte
Añadirvídeo/imagenalalistadetareaspara obtener instrucciones. El área de la
ventana principal muestra las imágenes y la información del archivo seleccionado en la
lista.
\2. Botones de operación de la lista de tareas. Las operaciones funcionan en todos los
archivos de la lista de tareas, por ejemplo, agrupación automática, operación por lotes
y borrado de la lista.
\3. Ventana de valor de la temperatura. Muestra las temperaturas medidas en la imagen y
herramientas de medición. Para abrir la ventana, consulte Ajustedeldiseñodela
ventanapara obtener más detalles.
\4. Controles de reproducción. Para la reproducción de un vídeo radiométrico, consulte
Reproducciónyconfiguracióndevídeoradiométricopara obtener más detalles. Para
reproducir un vídeo de tendencias, consulte Crearyreproducirvídeosdetendencias.

Nota
Si el vídeo se graba cuando el dispositivo está en modo de prevención de quemadura (el
obturador del dispositivo está cerrado para evitar que el detector sufra daños causados

28

<!-- p. 37 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

por objetivos inesperados a alta temperatura), aparecerá un aviso recordando al usuario
esta situación.

\5. Ventana del gráfico de temperatura. La curva de temperatura cambia con el progreso
de la reproducción. Las curvas de temperatura son configurables; consulte
Visualizacióndelacurvadetiempo-temperaturaparavídeo/transmisiónenvivoy Ver
elhistogramadedistribucióndetemperaturayelgráficodelíneasdetemperatura
para obtener instrucciones. La ventana del gráfico se puede abrir a través de la
herramienta de diseño en la barra de herramientas; consulte Ajustedeldiseñodela
ventanapara obtener más detalles.
\6. Herramientas de configuración de la paleta. Existen principalmente cuatro tipos de
paletas: las paletas comunes y sus versiones invertidas, la isoterma, la condensación y
el aislamiento. Consulte Paletasypaletasinvertidas, Establecerisoterma, Aislamiento,
Deteccióndecondensación, Nivelyrangoy Distribucióndecolorpara obtener más
detalles.
\7. Panel de análisis de temperatura. Cambie los parámetros de medición, como la
temperatura y la humedad atmosféricas, la emisividad objetivo, la temperatura
reflejada y la distancia, en este panel. Consulte Modificarparámetrosdemediciónde
latemperaturapara obtener más detalles.
\8. Panel de información de archivo. Muestra la hora de captura, la resolución, el
dispositivo y otra información del archivo.
\9. Herramientas avanzadas de edición, rotación y cambio de tamaño de imágenes.
Consulte Ediciónavanzadadeimageny Rotarycambiareltamañodeunaimagenpara
obtener más detalles.
\10. Herramientas de análisis de medición. Utilice estas herramientas para añadir y editar
distintos tipos de mediciones, borrar todas las mediciones, etc. Consulte Añadir
herramientademediciónpara obtener más detalles.
\11. Diseños y ventanas rápidos. Puede aplicar opciones de diseño rápido u organizar
libremente los diseños de las ventanas. Consulte Ajustedeldiseñodelaventanapara
obtener instrucciones.
\12. Guardado y exportación de archivos y datos.

4.3.2 Reproducción y configuración de vídeo radiométrico

El vídeo radiométrico admite múltiples controles de reproducción. Las instantáneas se
pueden guardar durante la reproducción.
Control de reproducción
● , botón de izquierda a derecha: Detener, Reproducir/Pausa, Fotograma
anterior, Fotograma siguiente.
● Fotograma específico: Introduzca el número de fotograma en el cuadro de texto y pulse

29

<!-- p. 38 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Entrar para saltar al cuadro.
● Velocidad de reproducción: Ajustar la velocidad de reproducción.
● Barra de progreso: Arrastre el punto azul para ajustar la posición de reproducción.
Guardar instantáneas
En el área de control de reproducción, haga clic en para capturar una instantánea.
Las imágenes capturadas se guardan en la carpeta Capturas en Acceso rápido en
Biblioteca.
Teclas de atajos para reproducción

Tecla de atajos Función
Espacio Reproducción/pausa
←(flecha hacia la izquierda) Fotograma anterior
→(flecha hacia la derecha) Fotograma siguiente
F4 Guardar instantánea (captura)

4.4 Crear y analizar vídeos de tendencias

Un vídeo de tendencias es una colección de imágenes térmicas compuesta por el usuario
y capturada por el mismo dispositivo. Puede reproducirse como un vídeo en función del
tiempo de grabación.
Para crear y reproducir vídeos de tendencias, consulte Crearyreproducirvídeosde
tendencias.
El análisis de un vídeo de tendencia es similar al análisis de vídeos radiométricos;
consulte Análisisdevídeo.

4.4.1 Crear y reproducir vídeos de tendencias

Pasos
\1. Crear vídeos de tendencias.
\1) Coloque las imágenes que deben generarse como vídeo de tendencias en la misma
carpeta en la Biblioteca (se admiten tanto Archivo local como Mis favoritos).
\2) En la Biblioteca, arrastre la carpeta hasta la Lista de tareas. A continuación, se
generará un vídeo de tendencias.
Nota
Si la carpeta contiene imágenes que no cumplen con los requisitos (deben haber sido

30

<!-- p. 39 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

tomadas con el mismo dispositivo, con el mismo objetivo y el mismo ratio de zoom),
se eliminarán del vídeo de tendencias generado. Se pueden incluir hasta 512
imágenes térmicas en un vídeo de tendencias.
El número que aparece en la esquina superior izquierda de la miniatura del vídeo de
tendencias en la lista de tareas representa el número de imágenes del vídeo.
La serie de imágenes del vídeo de tendencias sigue el orden de la hora de captura.
\2. Reproducir vídeos de tendencias.
\1) Cambie a la página Análisis y seleccione los vídeos de tendencias en la Lista de
tareas.
\2) Establezca la Velocidad de reproducción.
\3) Haga clic en para controlar la reproducción de los vídeos de tendencias;
también puede introducir un número en Ir a para ir a la imagen que le interese.

4.5 Guardar y exportar archivos

Guardar se refiere a preservar las modificaciones realizadas durante el análisis en la
ubicación original o especificada. Exportar se refiere a guardar archivos en otros formatos
compatibles o guardar únicamente datos especificados por el usuario. Los distintos tipos
de archivos admiten distintas operaciones de guardado y exportación.
Tabla 4-2 Operaciones de guardado y exportación para diferentes tipos de archivos
Tipo de archivo Operaciones
Admite el guardado. Al guardar imágenes agrupadas, las
modificaciones se guardan en cada imagen individual.
Admite Guardar como por lotes. Cada imagen del grupo se
Imágenes guardará como un archivo individual.
radiométricas,
Durante la exportación por lotes desde la lista de tareas, cada grupos de imágenes
imagen del grupo se guardará en el formato requerido.
Consulte Guardarimageny Exportarimagenpara obtener
información sobre las operaciones.
Admite guardar en la ruta original o guardar en otras ubicaciones
de almacenamiento.
Admite la exportación a vídeos en formato MP4 y HRV, con
Vídeos radiométricos configuraciones de rango de fotogramas (fotograma inicial y
fotograma final).
No admite la exportación por lotes.
Consulte Guardar/Exportarvídeopara obtener información sobre

31

<!-- p. 40 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Tipo de archivo Operaciones
las operaciones.
Admite guardar mediante el icono en la barra de
herramientas. Al guardar un vídeo de tendencias, las
modificaciones se guardan en cada imagen individual y no se
genera ningún archivo de vídeo durante este proceso. Vídeos de tendencias
Los vídeos de tendencias NO admiten el guardado por lotes
desde la lista de tareas.
NO admite la exportación por lotes.
Otras imágenes NO se admiten análisis, guardado ni exportación.

Nota
Debido a las actualizaciones del protocolo del cliente, las imágenes radiométricas o los
vídeos radiométricos guardados o exportados utilizando la versión del cliente V1.7.2 y
posteriores no se pueden ver ni analizar con versiones anteriores del cliente.

4.5.1 Guardar imagen

Después del análisis de la imagen, puede guardar la información de la imagen modificada
(herramientas de mediciones, información de la temperatura, nota de texto, análisis de
condensación, etc.) para referencias futuras.
Las operaciones para guardar una imagen y para guardar todas las imágenes son las
siguientes.
Guardar una imagen
En la Lista de tareas, seleccione una imagen y haga clic en en la barra de tareas para
guardar la modificación.
En la Lista de tareas, seleccione una imagen y haga clic en en la barra de tareas y
seleccione Guardar como. A continuación, puede introducir el nombre de la imagen,
seleccionar la ruta y el formato con el que guardar el archivo.

Nota
Al guardar un grupo de imágenes, todas las imágenes del grupo se guardan de forma
independiente.

Guardado por lotes

32

<!-- p. 41 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Haga clic en en la parte inferior de la Lista de tareas y seleccione Guardar por lotes
para guardar toda la información de la imagen modificada.
Haga clic en en la parte inferior de la Lista de tareas y seleccione Guardar por lotes
como para guardar todas las imágenes modificadas en la ruta de acceso designada.

Nota
Las funciones Guardar por lotes y Guardar como se aplican exclusivamente a imágenes
radiométricas individuales en la lista de tareas. Los grupos de imágenes, los vídeos
radiométricos/de tendencias y las imágenes normales se excluyen de las operaciones por
lotes

4.5.2 Exportar imagen

Después de editar y analizar la imagen, es posible exportar la imagen para hacer una copia
de seguridad en su ordenador o compartirla con terceros.
Pasos

Nota
● La imagen exportada no puede utilizarse para el análisis de imágenes.
● Haga clic en > Exportación por lotes en la Lista de tareas para exportar todas las
imágenes radiométricas.
● Al exportar un grupo de imágenes, cada imagen del grupo se exportará según la
configuración.
\1. En la pestaña de Análisis, seleccione la imagen a exportar en la Lista de tareas.
\2. Haga clic en > Exportar imagen en la Lista de tareas para abrir la ventana de
configuración.

Figura 4-3 Exportar imagen
\3. Establezca la parámetros relevantes.

33

<!-- p. 42 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Tipo de imagen
Es posible exportar tanto imágenes térmicas como imágenes visuales, o puede
seleccionar un tipo de ellas para exportar.
Nota
Los tipos de imagen que se pueden exportar dependerán del dispositivo.
Nombre de archivo
Es posible personalizar el nombre del archivo simultáneamente para las imágenes
térmicas y visuales.
Guardando ruta
La imagen se guarda en el directorio predeterminado, o puede seleccionar otra ruta
de guardado.
\4. Haga clic en Aceptar para exportar la imagen.

4.5.3 Guardar/Exportar vídeo

Tras el análisis del vídeo, puede guardar la información del vídeo (herramienta de
medición, resultados de la medición, etc.) para su uso posterior.
Nota
● Las funciones Guardar y Guardar como están disponibles para los vídeos .hrv, pero no
para los vídeos .rv.
● Tras la operación, haga clic en Abrir archivo en la ventana emergente para ver los vídeos
guardados y exportados.
● Debido a la actualización del protocolo, los vídeos guardados/exportados por la versión
del cliente V1.7.2 o posterior no se pueden reproducir ni analizar en versiones anteriores
del cliente.
Guardar vídeo
Seleccione un vídeo en la lista de tareas y, en la barra de herramientas, haga clic en
para guardar el vídeo.
Guardar como vídeo
Seleccione un vídeo en la lista de tareas y, en la barra de herramientas, haga clic en >
Guardar como. Establezca el nombre y la ubicación del archivo y haga clic en Aceptar.
Exportar vídeo
Seleccione un vídeo en la lista de tareas. En la barra de herramientas, haga clic en >
Exportar vídeo. Establezca el tipo de exportación y los fotogramas de vídeo que desea
exportar y haga clic en Aceptar. Establezca el nombre y la ubicación del archivo y haga clic
en Aceptar.

34

<!-- p. 43 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Capítulo 5 Herramientas y operaciones de
análisis

5.1 Ajuste del diseño de la ventana

El diseño de Análisis y En vivo se puede ajustar para satisfacer diferentes requisitos de
visualización de imágenes y datos.
● El cliente tiene varios diseños integrados de uso común, que los usuarios pueden
aplicar rápidamente. El análisis de imágenes, el análisis de vídeo y el análisis en vivo
pueden aplicar de forma independiente diferentes Diseños rápidos. Para obtener más
información, consulte Diseñorápido.
● El cliente admite el diseño libre para la mayoría de las ventanas. Los usuarios pueden
agregar o quitar ventanas, ajustar el tamaño y la posición de las ventanas. Para obtener
más información, consulte Diseñolibre.

Nota
Los diseños de ventana se guardan automáticamente por sesión (por separado para
imágenes/vídeo térmico/análisis en vivo) y se restauran al volver a abrir.

5.1.1 Diseño rápido

Diseño rápido se refiere a varios diseños de ventanas de uso común integrados en el
software del cliente que los usuarios pueden aplicar directamente.
En las pestañas Análisis y En vivo, haga clic en en la barra de herramientas para
mostrar las opciones de diseño rápido. Haga clic para seleccionar y aplicar.

Nota
Los modos de diseño rápido admitidos difieren para el análisis de imágenes, el análisis de
vídeo y el análisis en vivo. Consulte la interfaz del cliente para conocer los detalles.

5.1.2 Diseño libre

Los usuarios pueden agregar libremente diferentes tipos de ventanas de información y
ajustar sus posiciones y tamaños.
Añadir y quitar ventanas de información

35

<!-- p. 44 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

\1. En la pestaña de análisis, haga clic en el icono de la barra de herramientas para
abrir la lista de ventanas compatibles que se pueden añadir.
\2. Haga clic para seleccionar la ventana de información obligatoria.
\3. Las ventanas de imágenes recién añadidas se añaden de manera predeterminada al
lado derecho de la ventana principal (la ventana de imagen térmica); las ventanas de
gráficos y tablas se añaden debajo de la ventana principal de manera predeterminada.
Las ventanas adicionales del mismo tipo se apilarán como pestañas.
\4. Las ventanas innecesarias se pueden cerrar haciendo clic en en la esquina superior
derecha.
Ajustar posición de ventanas
Haga clic en el encabezado de la ventana que desea reposicionar y arrástrelo para ajustar
su posición. El indicador de diseño le ayuda a localizar dónde colocarlo.

Figura 5-1 Indicador de diseño
● Para separar una ventana de la interfaz del software: Arrastre el encabezado de la
ventana a cualquier lugar donde no aparezca ningún indicador de diseño y luego suelte
el ratón.
● Para ajustar la posición de la ventana dentro de la interfaz principal del software:
Arrastre su encabezado a la ventana adyacente del área de destino hasta que aparezca
el indicador de diseño. Alinee el cursor con la posición del indicador y luego suéltelo
para bloquear la ventana en la zona de vista previa sombreada.

36

<!-- p. 45 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Figura 5-2 Ajuste de la posición de la ventana

Cambiar tamaño de ventana
Mueva el ratón hasta el borde de la ventana. Cuando el borde se vuelva azul y el cursor
cambie a , arrastre para ajustar la posición de ese borde.

Figura 5-3 Selección y arrastre de bordes de ventana

5.2 Zonas protegidas y su influencia

Una zona protegida se refiere a un área donde la recopilación de información de
temperatura está deshabilitada durante la captura de imágenes o vídeos por parte del
dispositivo. El cliente admite la identificación y el marcado de zonas protegidas en
imágenes, vídeos y análisis en vivo.

37

<!-- p. 46 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Identificación de zona protegida
En el cliente, las zonas protegidas se muestran como áreas poligonales (con hasta 10
lados) con el contorno rojo y rellenas con sombreado gris transparente. Pueden existir
múltiples zonas protegidas dentro de un mismo fotograma.

Figura 5-4 Ejemplo de zona protegida (3 zonas)

Zonas protegidas
La información de temperatura dentro de las zonas protegidas se excluye durante el
análisis. Por lo tanto, al añadir herramientas de medición, asegúrese de que no se
superpongan con las zonas protegidas.
Las zonas protegidas son solo de visualización en el cliente y no se pueden modificar.

5.3 Herramientas de edición de imagen

En la pestaña Análisis, la edición de imágenes se realiza principalmente a través del área
de la barra de paleta en el lado derecho de la imagen térmica. Desde la barra de
herramientas superior también puede configurar el modo de imagen, ajustar parámetros
avanzados como la nitidez y el contraste de la imagen, y modificar el tamaño y la
orientación de la imagen. A través de la edición de imágenes, puede ver la imagen con
más detalles y una distribución de temperatura más clara.

38

<!-- p. 47 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Nota
Las herramientas para editar imágenes, vídeos y transmisiones en vivo son diferentes.
Consulte la interfaz real para conocer los detalles.

Figura 5-5 Herramientas de edición de imágenes - Barra de herramientas superior

Figura 5-6 Herramientas de edición de imágenes - Configuración de la paleta
\1. Modo de visualización. Cuando la imagen térmica tiene una imagen visual adjunta,
puede elegir ver la imagen en modo puramente térmico, visual o mixto. Consulte
Establecerelmododevisualizaciónpara obtener más instrucciones.
\2. Edición avanzada de imágenes. Proporciona parámetros como brillo, contraste y
nitidez. Consulte Ediciónavanzadadeimagenpara obtener más instrucciones.
\3. Rotar la imagen.
\4. Cambiar el tamaño de la imagen. Consulte Rotarycambiareltamañodeunaimagen
para obtener más instrucciones.
\5. Configuración de paleta. Muestra el tipo de paleta de la imagen/vídeo/transmisión en
vivo actual. Haga clic en ella para abrir el panel de configuración de la paleta.
\6. Modo de nivel y rango. Se puede seleccionar entre automático y manual. Consulte
Nivelyrangopara obtener más instrucciones.
\7. Parte superior de la escala de temperatura. Cuando se utiliza el modo de nivel y rango
manual, el usuario puede ajustar valor de escala superior.
\8. Paletas invertidas. Marque la casilla para invertir la relación temperatura-color del tipo
de paleta seleccionado. Consulte Paletasypaletasinvertidaspara obtener más
instrucciones.
\9. Parte inferior de la escala de temperatura. Cuando se utiliza el modo de nivel y rango
manual, el valor de la escala inferior es ajustable por el usuario.

39

<!-- p. 48 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

\10. Tipos de paleta. Hay 4 tipos principales: paletas personalizadas e integradas, isoterma,
condensación y aislamiento. Consulte Paletasypaletasinvertidas, Establecerisoterma,
Aislamientoy Deteccióndecondensaciónpara obtener más instrucciones.
\11. Distribución de color. Representa las relaciones de colores y temperaturas. Se puede
seleccionar entre lineal e histograma. Consulte Distribucióndecolorpara obtener más
información.
\12. Importar otras paletas. El formato de archivo aceptable es *gpl. Consulte Paletasy
paletasinvertidaspara obtener más instrucciones.
\13. Paletas no integradas. Si la imagen térmica en análisis tiene un tipo de paleta no
integrada, la paleta se puede leer y mostrar normalmente. Su nombre será Desde
imagen en la parte superior de la lista.
\14. Tipos de paleta integrados.

Nota
Para las imágenes, vídeos y transmisiones en directo con baja resolución térmica, hay
disponible una función de superresolución que mejora la calidad de la imagen y ofrece
más detalles. Consulte Súperresoluciónpara obtener más instrucciones.

5.3.1 Establecer el modo de visualización

Las imágenes tomadas por una cámara que tenga tanto un canal térmico como visual
pueden mostrarse en modo térmico, fusión, PIP, mezcla o visual.
En la barra de herramientas de la pestaña Análisis, haga clic en para seleccionar un
modo de visualización.

Nota
Los vídeos radiométricos, los vídeos de tendencias y la transmisión en vivo solo tienen
disponible el modo térmico

Modo Muestra Descripción

Térmica Solo imagen térmica.

En el modo Fusión, la imagen térmica y la imagen óptica se
combinan para crear unos contornos de imagen claros, de Fusión
modo que no solo se puede detectar la temperatura del
entorno del objeto continuamente, sino también distinguir la

40

<!-- p. 49 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Modo Muestra Descripción
forma del objeto dentro del entorno.

Nota
Si fuese necesario, haga clic en Ajustar la Alineación de
Fusión para alinear la imagen visual con la imagen
radiométrica.
● Haga clic en / para acercar/alejar la imagen visual.
También puede usar la tecla MÁ S/MENOS para
acercar/alejar la imagen.
● Haga clic en / / / para ajustar la posición de la
imagen visual. También puede pulsar las teclas de dirección
del teclado para ajustar la posición.
● Haga clic en Restablecer para restaurar la posición de la
imagen visual al momento en el que se capturó la imagen
visual.

En el modo de mezcla, puede ajustar la proporción de luz
visible. Si la imagen del modo térmico no se ve clara, es
posible aumentar la proporción de luz visible para obtener
más detalles y así tomar decisiones precisas.

Mezcla Nota
Seleccione Mezcla y arrastre el control deslizante hacia la
izquierda o hacia la derecha para ajustar el nivel
térmico/visual.

En el modo PIP (imagen en imagen), la imagen visual aparece
en segundo plano y la imagen térmica se muestra en el centro
de la imagen.
PIP Seleccione PIP en la lista desplegable. Si es necesario, puede
hacer clic en Ajustar vista térmica para redimensionar y mover
la imagen radiométrica siguiendo las instrucciones en la
interfaz.

41

<!-- p. 50 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Modo Muestra Descripción

Visual Solo imagen visual.

5.3.2 Paletas y paletas invertidas

Las paletas contienen la correspondencia entre la temperatura y el color de la imagen. El
cliente muestra diferentes colores según la paleta seleccionada y la temperatura de la
imagen. La selección de una paleta adecuada puede proporcionar más detalles de la
imagen.
Establecer una paleta
En la herramienta Paleta a la derecha de la imagen térmica, haga clic en el campo Paletas
en la parte superior para mostrar el panel Configuración de paleta. Pase el ratón por
encima de un tipo de paleta de la lista para obtener una vista previa del efecto. Haga clic
en un tipo de paleta para guardar el cambio.
El cliente admite varias paletas incorporadas y una paleta personalizada. Para la paleta
personalizada, el cliente puede leerla desde una imagen térmica o desde un archivo de
paleta independiente (*.gpl).
● Importe un archivo de paleta independiente (*.gpl) a través de + en la parte superior
derecha de la lista de paletas. La nueva paleta se muestra en la parte superior de la lista
con el nombre Desde archivo. Las imágenes térmicas en la lista de tareas pueden
utilizar la paleta.
● Si la imagen/vídeo térmico original tiene un tipo de paleta no incorporado, el software
puede leer el tipo y mostrarlo en la parte superior de la lista con el nombre Desde
imagen. La paleta de imágenes no está disponible para otras imágenes y vídeos en la
lista de tareas.
Paletas invertidas
Invertir una paleta consiste en invertir los colores correspondientes a las temperaturas
altas y bajas en las paletas. Por ejemplo, el área de alta temperatura se muestra en blanco
y el área de baja temperatura se muestra en negro después de seleccionar la paleta
Blanco viv. Cuando se establece la escala de temperatura inversa, el área de alta
temperatura se muestra en negro vivo y el área de baja temperatura, en blanco vivo.
Marque Invertir en la parte superior izquierda de la lista de la paleta para utilizar la función.

5.3.3 Establecer isoterma

42

<!-- p. 51 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Isoterma es un modo de paleta que asigna colores diferenciados a rangos de temperatura
específicos para identificar rápidamente áreas de temperatura anormales o especiales en
la imagen. Se pueden configurar hasta tres segmentos de temperatura isoterma, cada uno
con un color sólido o con relleno de paleta.

Figura 5-7 Configuración de isoterma
En el lado derecho de la imagen térmica, abra la página Configuración de paleta y
seleccione Isoterma en la lista desplegable Paleta. Aparecerán tres segmentos de
isotermas en la página de configuración.
Verifique la cantidad requerida de isotermas y configure Color, Máx. y Mín. para cada
segmento de isoterma.
Nota
● El color de cada segmento de isoterma se puede configurar como un color sólido o un
relleno de paleta.
● Los rangos de temperatura de las isotermas pueden superponerse. Cuando se produce
superposición, el orden de prioridad para los segmentos de isoterma efectivos es:
Isoterma 3 > Isoterma 2 > Isoterma 1

5.3.4 Aislamiento

El aislamiento se utiliza comúnmente para detectar el rendimiento del aislamiento térmico
de los edificios. Se recomienda utilizar imágenes térmicas de interiores para el análisis del
rendimiento del aislamiento.
Pasos
\1. En el área de la barra de paleta en el lado derecho de la imagen térmica, abra

43

<!-- p. 52 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Configuración de paleta y seleccione Aislamiento en la lista desplegable Paleta.
\2. Después de configurar la Temperatura interior y la Temperatura exterior, el cliente
analizará el rendimiento del aislamiento de las superficies en la imagen.
\3. Si hay un área cuyo rendimiento de aislamiento es inferior al Nivel de aislamiento
establecido, el área con anomalías de aislamiento se mostrará en cian en la imagen.

Nota
Un valor de índice de aislamiento más alto indica mayores demandas de rendimiento de
aislamiento. Se recomienda establecer el nivel de aislamiento entre 60 y 80.

5.3.5 Detección de condensación

La función es detectar la humedad relativa (RH) de la superficie de los objetos. Las áreas
que superen el umbral configurado se resaltarán en verde en la imagen térmica.
Pasos
\1. En el área de la barra de paleta en el lado derecho de la imagen térmica, abra
Configuración de paleta, luego seleccione Condensación en la lista desplegable Paleta.
\2. Establezca el umbral de la alarma de HR en Umbral de alarma. Las superficies que
superen el umbral se representarán con una paleta verde.
\3. Opcional: Ajuste los parámetros de temperatura ambiente y HR según sea necesario.
● Cuando la opción Usar parámetros locales está deshabilitada, el sistema calcula los
resultados utilizando la Temperatura ambiental y la Humedad relativa del Análisis de
temperatura (parámetros del entorno del dispositivo al tomar imágenes térmicas,
solo lectura).
Cuando se habilita Usar parámetros locales, el sistema utiliza la siguiente Temperatura
ambiental y Humedad relativa (parámetros del entorno del objeto de destino configurados
por el usuario) para el cálculo.

5.3.6 Nivel y rango

Cambiar los niveles de temperatura facilita el análisis de las anomalías de temperatura.
Existen tres modos para ajustar los niveles y el alcance, incluyendo el Automático y el
Manual. Los capítulos siguientes describen cómo usar estos modos.

Nivel y rango Automático

En este modo, el Cliente calculará automáticamente la escala de temperatura para
obtener un mejor contraste y brillo de la imagen.
En la parte superior de la escala de temperatura, seleccione Automático en la lista

44

<!-- p. 53 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

desplegable.
Nota
● Si el efecto de imagen en este modo no cumple sus expectativas, puede seleccionar
Manual para ajustar manualmente la escala de temperatura. Para ver los detalles,
consulte ManualdeNivelyrango.
● En el modo Automático, haga clic con el botón derecho sobre una herramienta de
medición de zona (incluyendo rectángulo, círculo, elipse y polígono) y seleccione Mejora
de la imagen regional. El Cliente calculará automáticamente la escala de temperatura
de la zona y cambiará a modo Manual, en el que podrá seguir ajustando la escala de
temperatura manualmente. Para ver los detalles, consulte ManualdeNivelyrango.
Además, en el modo Manual, si mueve o redimensiona esta herramienta de medición de
zona, el efecto de imagen cambiará al mismo tiempo.

Figura 5-8 Ejemplo de imagen (Automático)

Manual de Nivel y rango

Puede ajustar manualmente el valor superior e inferior de la paleta seleccionada, y
también el rango de la escala de temperatura.

45

<!-- p. 54 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Pasos
\1. Seleccione Manual en la lista desplegable.

Figura 5-9 Ajuste manual
\2. Ajustar el rango de temperatura de la paleta.
– Arrastre los controles deslizantes en los extremos de las paletas hacia arriba y hacia
abajo o introduzca los valores deseados en los campos correspondientes.
– Coloque el cursor sobre la barra de la paleta (4) y arrastre toda la barra hacia arriba y
hacia abajo para ajustar el rango de la paleta en la escala.
– Para los vídeos térmicos y transmisiones en vivo (2), se admite el modo
semiautomático. El cliente controla automáticamente el final del rango cuando está
en modo y el otro es ajustable manualmente cuando está en modo . Haga clic
en los iconos para cambiar de modo.
\3. Opcional: Ajuste el rango de la escala de temperatura. Haga clic en los campos (3 y 5) e
introduzca los valores deseados.

5.3.7 Distribución de color

Es posible cambiar la distribución de colores en una imagen. Una distribución de color
diferente le permitirá analizar la imagen con mayor facilidad y más concienzudamente.
En el panel Configuración de paleta, seleccione un modo de la lista desplegable
Distribución de color.
Tabla 5-1 Distribución de color
Distribución de color Descripción
Lineal Aplicable cuando el intervalo de temperatura de una imagen es

46

<!-- p. 55 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Distribución de color Descripción
grande.
Aplicable cuando el intervalo de temperatura de una imagen es Histograma
pequeño.

5.3.8 Súperresolución

El cliente admite la tecnología de superresolución SuperIR para ofrecer imágenes y vídeos
más nítidos y con más detalles.
● Para las imágenes térmicas importadas al cliente, este las procesa automáticamente
con la tecnología SuperIR. Como resultado, las imágenes tienden a verse mejor en el
cliente que en el dispositivo.
● Para los vídeos radiométricos y los vídeos de tendencias en el cliente, si la resolución IR
es inferior a 256×192, el conmutador SuperIR aparece en la barra de herramientas.
Nota
Cuando un vídeo radiométrico se exporta a un archivo MP4, el efecto de SuperIR se
conserva. El efecto no se conserva al exportar el archivo a otros formatos.
● Para un dispositivo que se conecta al cliente para el análisis en directo, si su resolución
IR es inferior a 256×192, el conmutador de SuperIR aparece en la barra de herramientas.
Nota
El efecto de SuperIR no se conserva en las imágenes térmicas o vídeos capturados
durante el análisis en directo.

5.3.9 Rotar y cambiar el tamaño de una imagen

Puede rotar o cambiar el tamaño de la imagen según sus necesidades.
Rotar la imagen
En la barra de herramientas, haga clic en Rotar una vez. La imagen rotará 90 grados.

Nota
Las herramientas de medición establecidas se borrarán después de la rotación.

Cambiar el tamaño de la imagen
● Ajustar a la ventana: El tamaño de la imagen se ajustará automáticamente al tamaño de
la ventana.
● Tamaño fijo: Deslice el cursor para ajustar el tamaño. El tamaño de la imagen no
cambiará en consonancia con el tamaño de la ventana.

47

<!-- p. 56 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

5.3.10 Edición avanzada de imagen

Puede ajustar diversos parámetros de la imagen, como el brillo, el contraste, la nitidez, etc.
para un mejor análisis.
\1. En la barra de herramientas, haga clic en .
\2. Seleccionar el modo de ajuste de imagen.
\3. En el modo Manual, ajuste los siguientes parámetros según sea necesario.

Parámetro Descripción
Arrastre o introduzca un número entero a la derecha para
Brillo ajustar el brillo de la imagen.
El contraste es la diferencia de nivel de brillo entre la zona más
brillante y la más oscura de una imagen. Cuanto más alto sea
Contraste el contraste, mayor será la diferencia.
Arrastre o introduzca un número entero a la derecha para
ajustar el contraste de la imagen.
La nitidez describe la claridad de los detalles de la imagen.
Cuanto más alta sea la nitidez, más clara se verá la imagen.
Nitidez
Arrastre o introduzca un número entero a la derecha para
ajustar la nitidez de la imagen.

Después de configurar los parámetros anteriores, lleve a cabo las acciones siguiente
según sea necesario.
● Haga clic en Aceptar para guardar la configuración actual.
● Haga clic en Vista previa para ver una vista previa del efecto de los parámetros
editados.
● Haga clic en Restablecer para restaurar los ajustes predeterminados.

5.3.11 Aplicar los parámetros de imagen a todas las imágenes de
la lista de tareas

Cuando se analizan varias imágenes al mismo tiempo, es posible aplicar los parámetros
de la imagen seleccionada al resto de las imágenes de la lista de tareas (excepto Otra
imagen) para mejorar la eficacia del análisis de imágenes.
Seleccione una imagen o un grupo en la Lista de tareas y haga clic con el botón derecho
para seleccionar Aplicar los ajustes de la imagen a todo para configurar por lotes los
parámetros de imagen en la Lista de tareas.
● Seleccione una imagen térmica y sincronice los parámetros. Se sincronizan los
parámetros de la primera imagen térmica para todas las imágenes térmicas no

48

<!-- p. 57 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

agrupadas y agrupadas de la Lista de tareas.
● Seleccione un grupo y sincronice los parámetros. Cuando seleccione un grupo de
imágenes para iniciar la aplicación, se aplicarán todas las imágenes térmicas
individuales con los ajustes de parámetros de la primera imagen del grupo, y los ajustes
de las imágenes de otros grupos se sincronizarán según el orden de las imágenes del
grupo seleccionado.

5.4 Herramientas de medición de temperatura

Al añadir/editar/eliminar herramientas de medición y ajustar los parámetros de medición
de la temperatura, puede analizar los resultados de medición de las imágenes, los vídeos,
la transmisión en vivo y áreas específicas de los materiales. Con la herramienta de cálculo
de área, puede calcular el área de una herramienta específica. Además, el cliente admite la
aplicación por lotes de herramientas de medición a todas las imágenes térmicas en la
Lista de tareas, lo que mejora enormemente la eficiencia del análisis.
Para establecer una herramienta de medición, consulte Añadirherramientademedición.
Para editar una herramienta de medición, consulte Editarunaherramientademedición.
Para eliminar una herramienta de medición, consulte Eliminarunaherramientade
medición.
Para ajustar los parámetros de medición de temperatura, consulte Modificarparámetros
demedicióndelatemperatura.
Para calcular el área de la regla, consulte Calcularelárea.
Al obtener una vista previa o exportar materiales, puede agregar y modificar el contenido y
la posición de la información superpuesta en la imagen. Para la configuración, consulte
Establecersuperposicionesdemedición.
Para aplicar herramientas de medición a todas las imágenes de la lista de tareas, consulte
Aplicarherramientasdemediciónatodaslasimágenesdelalistadetareas.

5.4.1 Añadir herramienta de medición

Las herramientas de medición incluyen puntos, líneas, polilíneas, rectángulos, elipses,
polígonos y herramientas delta. Añada una o más herramientas de medición en la imagen
para el análisis de temperatura. Los resultados de la medición se muestran en una
ventana de tabla de resultados de medición independiente o superpuestos en la imagen.

Figura 5-10 Barra de herramientas de medición

49

<!-- p. 58 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Nota
Se pueden añadir hasta 32 herramientas de medición en total.

Añadir herramienta de medición
Haga clic en una herramienta de la barra de herramientas para comenzar a dibujar en la
imagen. Puede seguir dibujando las mismas herramientas de tipo hasta que pulse la tecla
ESC o haga clic nuevamente en el icono de la herramienta.
Tabla 5-2 Métodos de dibujo de las herramientas de medición
Tipo de herramienta Método de trazado
Haga clic en y, a continuación, haga clic en cualquier lugar de
Punto
la imagen para añadir un punto de medición.
Haga clic en y, a continuación, arrastre el ratón a cualquier
Línea
parte de la imagen para dibujar una línea recta.
Haga clic en para expandir la lista y seleccione para entrar
en el modo de dibujo. Haga clic con el botón izquierdo en la
imagen para añadir los nodos de polilínea y haga clic con el botón
derecho para finalizar el dibujo. Línea poligonal

Nota
Se permiten hasta 10 nodos.

Haga clic en , haga clic con el botón izquierdo en la imagen y
Rectángulo
arrastre el ratón para dibujar un rectángulo.
Haga clic en para expandir la lista, seleccione y, a
continuación, haga clic con el botón izquierdo en la imagen y
arrastre el ratón para dibujar una elipse.
Elipse/Círculo
Nota
Mantenga pulsada la tecla Mayús mientras dibuja para crear un
círculo.

Haga clic en para expandir la lista, seleccione y, a
continuación, haga clic con el botón izquierdo en la imagen para
Polygon
añadir nodos del polígono. Haga clic en el botón derecho para
finalizar el dibujo.

50

<!-- p. 59 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Tipo de herramienta Método de trazado

Nota
Es posible añadir hasta 10 nodos.

Nota
El cliente admite entrar en diferentes estados de dibujo de herramientas mediante teclas
de acceso rápido. Vaya a la página de teclas de atajos para ver y modificar. Consulte Very
editarteclasdeatajospara obtener instrucciones.

Añadir herramienta delta
Las herramientas delta se utilizan para calcular las diferencias de temperatura. Por
ejemplo, la diferencia entre la temperatura más alta medida por una herramienta de
medición de puntos y la temperatura más baja medida por una herramienta de medición
de líneas.
Haga clic en en la barra de herramientas y configure los parámetros relevantes en
Configuración de la herramienta delta.
Seleccionar medición
Establecer la fórmula de cálculo. Seleccione la herramienta de medición y el tipo de
temperatura.

Nota
● Constante se refiere a un valor de temperatura personalizado que se debe introducir
manualmente.
● Imagen se refiere a la temperatura de la imagen (temperatura más alta, más baja,
promedio y central).

Resultado
Muestra la diferencia de temperatura calculada.
Nota
● Se pueden configurar hasta 4 herramientas delta.
● Los resultados de la diferencia de temperatura entre las herramientas de medición
también se muestran en la imagen como líneas de conexión discontinuas. Sin embargo,
cuando se selecciona Constante o Temperatura promedio, no se mostrarán líneas
discontinuas.
● Haga clic con el botón derecho en la línea de conexión discontinua para editar o

51

<!-- p. 60 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

eliminar la herramienta delta.

5.4.2 Editar una herramienta de medición

Moverunaherramientademedición
Redimensionarunaherramientademedición
EditarelcálculodelDelta
Modificarelcontenidoyelestilodelasuperposicióndelaherramientademedición
Mover una herramienta de medición
● En la barra de herramientas, haga clic en , seleccione una herramienta de medición en
la imagen y arrástrela a una nueva posición.
● Pulse las teclas de flecha del teclado para ajustar la ubicación de una herramienta.

Redimensionar una herramienta de medición
\1. En la barra de herramientas, haga clic en .
\2. Seleccione una herramienta de medición en la imagen.
\3. Arrastre el nodo de la herramienta de medición para remidensionar la herramienta.

Figura 5-11 Cambiar el tamaño de una herramienta de medición

Editar el cálculo del Delta
En la ventana Valor de medición, puede hacer clic con el botón derecho en un delta y
seleccionar Editar para editar el delta.
Vaya a > Agregar temperatura medida para abrir la ventana Valor de medición.
Modificar el contenido y el estilo de la superposición de la herramienta de
medición
El cliente permite ajustar el color de la herramienta, la posición y el tamaño de los textos
superpuestos, lo que facilita resaltar el contenido clave. Consulte Establecer
superposicionesdemediciónpara obtener más información.

5.4.3 Eliminar una herramienta de medición

52

<!-- p. 61 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Es posible eliminar una a una las herramientas de medición, hasta eliminarlas todas.
Nota
Después de eliminar una herramienta de medición, si algún Delta calculado está
relacionado con la herramienta eliminada, dicho Delta también se eliminará.
Eliminar una herramienta de medición
● Haga clic con el botón derecho en una herramienta de medición y seleccione Eliminar
medición.
● Seleccione una herramienta de medición y pulse la tecla Supr del teclado.

Borrar todas las herramientas de medición
● Haga clic con el botón derecho en cualquier posición de la imagen (excepto en los
lugares donde no haya ninguna herramienta de medición) y seleccione Eliminar todas
las mediciones.
● En la barra de herramientas, haga clic en para eliminar todas las herramientas de
medición.
Eliminar Delta
La forma de eliminar una herramienta de medición también se aplica a la eliminación de
un delta.
Otra forma es hacer clic con el botón derecho del ratón en un delta en la ventana Valor de
medición y seleccionar Eliminar.
Vaya a > Agregar temperatura medida para abrir la ventana Valor de medición.

5.4.4 Modificar parámetros de medición de la temperatura

En el panel Análisis de temperatura en el lado derecho de las pestañas Análisis y En vivo,
ajuste parámetros como Temperatura atmosférica, Humedad, Emisividad y Distancia para
afinar la precisión de la medición.
Parámetros de medición de la temperatura

Temperatura atmosférica
Temperatura del aire del entorno donde se encuentra el objetivo.
Humedad
Humedad relativa del ambiente donde se encuentra el objetivo.
Ventana IR externa - Transmitancia
Es necesario cuando se conectan componentes ópticos externos (por ejemplo,
ventanas de germanio) al dispositivo de imagen.

53

<!-- p. 62 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Ventana IR externa - Temperatura
Es necesario cuando se conectan componentes ópticos externos (por ejemplo,
ventanas de germanio) al dispositivo de imagen.
Emisividad
Ajustar según el tipo de objetivo observado.
Distancia
Distancia entre el dispositivo de imagen y el objetivo observado.
Temperatura reflejada.
Es necesario cuando existen objetos de alta temperatura en la escena y los objetivos de
baja emisividad reflejan su radiación. Establezca el valor de temperatura del objeto de
alta temperatura.
Configuración de los parámetro de temperatura
El cliente permite a los usuarios configurar los parámetros para la
imagen/vídeo/transmisión en vivo en su totalidad, o configurar los parámetros para una
herramienta de medición específica.
● Establecer parámetros para una herramienta
○ Después de configurar una herramienta de medición, haga clic con el botón derecho
en el área de la herramienta en la imagen y seleccione Parámetros de la herramienta
para establecer su distancia, emisividad y temperatura reflejada.
○ En el panel Análisis de temperatura, en el lado derecho de las pestañas Análisis y En
vivo, seleccione una herramienta de la lista desplegable Medición y configure su
distancia, emisividad y temperatura reflejada.
● Establecer parámetros para la imagen
○ Haga clic con el botón derecho en la imagen (excepto en el área de las herramientas
de medición) y seleccione Parámetros de medición para configurar los parámetros de
imagen.
○ En el panel Análisis de temperatura, en el lado derecho de las pestañas Análisis y En
vivo, seleccione Imagenen la lista desplegable Medición y configure su distancia,
emisividad y temperatura reflejada.
La Temperatura atmosférica y la Humedad también son parámetros de la imagen.

Nota
○ Haga clic en para Restablecer los parámetros a los valores predeterminados.
○ La Temperatura atmosférica y la Humedad no se pueden cambiar para los vídeos.

5.4.5 Calcular el área

54

<!-- p. 63 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

El cliente permite calcular el área de la superficie delimitada por las herramientas de
medición de área (rectángulo, polígono, círculo y elipse). El cálculo es una estimación del
área de la superficie en base a la distancia al objetivo.
Antes de comenzar
Asegúrese de haber añadido una herramienta de medición de zona a la imagen. Para
obtener información sobre cómo una herramienta de medición, consulte
Pasos
\1. Seleccione una herramienta de medición de zona en la imagen.
\2. Abra el panel Análisis de temperatura de la derecha.
\3. En Cálculo de Á rea, haga clic en el valor archivado para establecer la distancia a la
herramienta de área establecida.
Compruebe el resultado en la ventana Valor de medición. Vaya a > Agregar
temperatura medida para abrir la ventana Valor de medición.

5.4.6 Establecer superposiciones de medición

La superposición de mediciones se refiere a las herramientas de medición, parámetros,
resultados de medición, flechas y otra información que se muestra en imágenes térmicas,
vídeos y transmisiones en vivo. En circunstancias específicas, puede ajustar la posición, el
tamaño, el color, la visibilidad de la flecha de la superposición, etc.
Ajuste de la superposición en las pestañas Análisis y En vivo
La información superpuesta en la ventana de análisis y en vivo se divide principalmente en
dos tipos: Mostrar en la esquina superior izquierda y Mostrar con medidas. Puede alternar
entre ellos a través de Configuración > Superposición de imágenes > Ubicación.

Nota
● Las configuraciones de ubicación de superposición se aplican a las imágenes (incluidas
las instantáneas en vivo) y al análisis de transmisión en vivo, pero no a los vídeos
radiométricos (incluidos los vídeos grabados durante el análisis de transmisión en vivo).
● Para los vídeos radiométricos, los resultados de la medición solo se muestran en la
esquina superior izquierda. Los nombres y colores de las herramientas de medición se
pueden modificar a través de Configuración de superposición en el menú del botón
derecho.

Mostrar en la parte superior izquierda
Los parámetros de medición y los resultados se muestran en una lista vertical que
comienza desde la esquina superior izquierda de la imagen.

55

<!-- p. 64 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

● Seleccione un área sin herramientas. Utilice Configuración de superposición en el
menú del botón derecho o haga doble clic en el cuadro de información superior
izquierdo para configurar elementos de superposición, como los parámetros de
medición.
Seleccione un área sin herramientas. Utilice Configuración de superposición superior
izquierda en el menú del botón derecho para ajustar el tamaño (escala), el color de
fuente y el color de fondo.
● Seleccione un área de herramientas. Utilice Superposición de herramientas en el
menú del botón derecho para configurar elementos específicos de la superposición
de herramientas, como modificar nombres y colores de herramientas y configurar
temperaturas y parámetros mostrados.
● Haga clic en Restablecer para restaurar la configuración predeterminada.

Nota
Los parámetros y resultados relacionados con toda la imagen se muestran en el cuadro
de información superior izquierdo de forma predeterminada y no se pueden mover.

Mostrar con mediciones
Los parámetros de medición y los resultados se muestran alrededor de la herramienta
de medición. El tamaño, el fondo, el color y la posición del cuadro de información son
ajustables.
Ajuste de los elementos de visualización y el color
● Haga doble clic en el cuadro de información de superposición o seleccione un área
de herramientas y use Superposición de herramientas en el menú del botón
derecho para abrir la configuración.
● En la configuración, configure el nombre y el color de la herramienta, los elementos
de contenido superpuestos, el tamaño (escala), el color del texto y el fondo, la
visibilidad de la flecha (generada automáticamente cuando un cuadro de
información está lejos de la herramienta relacionada) y el color de la flecha.
● Haga clic en Recordar para aplicar las configuraciones modificadas a las
herramientas futuras.
● Haga clic en Restablecer para restaurar los ajustes predeterminados.

56

<!-- p. 65 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Ajuste de la posición del cuadro de información
● Haga clic y arrastre el cuadro de información para ajustar su posición. Si Mostrar
flecha está habilitado, se genera automáticamente una flecha indicadora cuando el
cuadro de información está lejos de la herramienta.
● El cliente admite la restauración de las superposiciones a sus posiciones
predeterminadas.
En las áreas que no son de herramientas, utilice Restaurar todo a la posición de
superposición predeterminada en el menú del botón derecho. Para una herramienta
específica, utilice Restaurar a la posición de superposición predeterminada.
Ajuste de la superposición para imágenes y vídeos exportados
Las imágenes y los materiales exportados generalmente conservan el contenido y los
efectos de superposición de vista previa (a excepción de algunos efectos). Además,
puede superponer información de hora, escala de temperatura, brújula y GPS, etc.
Configure a través de Configuración > Superposición de imagen > Superposición en
imagen/vídeo exportado.

Nota
Las flechas no se muestran al abrir imágenes guardadas/exportadas con visores de
fotografías o reproductores de vídeo estándar. Las flechas solo son visibles al abrir
imágenes radiométricas en este cliente.

5.4.7 Aplicar herramientas de medición a todas las imágenes de la
lista de tareas

Cuando se analizan varias imágenes al mismo tiempo, es posible aplicar las herramientas

57

<!-- p. 66 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

de medición, los parámetros y los rango delta en una imagen al resto de las imágenes de
la Lista de tareas para mejorar la eficacia del análisis de imagen.
En la pestaña Lista de tareas, haga clic con el botón derecho sobre una imagen o un grupo
y seleccione Aplicar mediciones a todo.
● Cuando seleccione una imagen térmica para iniciar la aplicación, se sincronizarán todas
las imágenes térmicas individuales y la primera imagen de cada grupo.
● Cuando seleccione un grupo de imágenes para iniciar la aplicación, se aplicarán todas
las imágenes térmicas individuales con los ajustes de medición de la primera imagen
del grupo, y los ajustes de las imágenes de otros grupos se sincronizan según el orden
de las imágenes del grupo seleccionado.

5.5 Ver y exportar resultados de medición

Los resultados de la medición se muestran como datos o gráficos en ventanas
independientes. El sistema también admite la exportación de imágenes y datos de
temperatura para su posterior análisis.

5.5.1 Ver resultados de medición de temperatura

Abra la ventana Valor de medición para ver los datos de resultados medidos de las
imágenes y las herramientas de medición en la imagen, el vídeo y la transmisión en vivo.
La ventana Valor de medición se puede abrir mediante > Agregar temperatura
medida en la barra de herramientas.
La columna Nombre muestra imágenes o herramientas de temperatura específicas
configuradas en las imágenes.

Figura 5-12 Resultado de la medición de distancia
Cuando se configuran las herramientas delta, la sección Delta muestra el nombre delta, la
fórmula y el resultado.
Los rangos delta se pueden configurar a través de en la esquina superior derecha. La
fórmula y el resultado se muestran en el color correspondiente a los rangos establecidos.

Nota
Durante el análisis de vídeo (incluido el análisis de transmisión en vivo), los resultados de

58

<!-- p. 67 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

la medición se actualizan dinámicamente.

5.5.2 Ver el histograma de distribución de temperatura y el gráfico
de líneas de temperatura

El histograma de distribución de temperatura muestra el porcentaje de píxeles de
diferentes temperaturas en toda la imagen o dentro de las herramientas de medición
establecidas. El gráfico de líneas de temperatura muestra valores de temperatura en
diferentes puntos a lo largo de una herramienta recta o polilínea. Los gráficos se
actualizan dinámicamente durante la reproducción de vídeo y transmisión en vivo.
Abrir ventanas de gráficos
\1. En la pestaña de análisis, haga clic en el icono de la barra de herramientas para
abrir la lista de ventanas compatibles que se pueden añadir.
\2. En la lista desplegable, seleccione Añadir gráfico de barras de distribución de
temperatura o Añadir gráfico de líneas de temperatura. Aparecerá una ventana de
gráfico debajo de la imagen térmica. De forma predeterminada, varios gráficos se
muestran como pestañas. Para realizar ajustes de diseño, consulte Ajustedeldiseño
delaventana.
\3. Seleccione la regla de medición o área correspondiente para el gráfico de
histograma/línea en el menú desplegable en la esquina superior derecha de la ventana
del gráfico.
Histograma de distribución de temperatura
El eje X representa los valores de temperatura, mientras que el eje Y indica el porcentaje
de distribución dentro de toda la imagen o la herramienta de medición seleccionada. Al
pasar el cursor por encima se muestra el valor porcentual actual.

Figura 5-13 Histograma de distribución de temperatura

Gráfico de líneas de temperatura

59

<!-- p. 68 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

El eje X indica la distancia relativa a lo largo de la ruta de medición (donde 0 denota el
punto de inicio), mientras que el eje Y muestra los valores de temperatura; al pasar el
cursor por encima se revela la lectura exacta de la temperatura.

Figura 5-14 Gráfico de líneas de temperatura

Exportar gráficos
Haga clic con el botón derecho en el área del gráfico y seleccione Exportar imagen o
Exportar archivo CSV.
● Imagen del gráfico: Formato JPEG (no editable)
● Archivo CSV: Datos de temperatura para cada punto indexado.

5.5.3 Ver y exportar vista térmica 3D

El cliente admite la generación, visualización y exportación de imágenes o datos de vista
3D para imágenes y sus áreas de herramientas de medición. Estos gráficos permiten a los
usuarios observar patrones de distribución de temperatura y cambios dinámicos en los
objetivos con mayor claridad y visualización intuitiva.
Generación de imágenes de vista 3D
En una visualización de vista 3D, el eje X corresponde al recuento de píxeles horizontales
de la imagen o del área de la herramienta seleccionada, el eje Y al recuento de píxeles
verticales y el eje Z al valor de temperatura en cada píxel.

Nota
Para configurar la representación de la Vista 3D, vaya a > Vista 3D.

Siga estos pasos para generar una imagen de vista 3D:
\1. En la pestaña de análisis, haga clic en el icono de la barra de herramientas para
abrir la lista de ventanas compatibles que se pueden añadir.
\2. Seleccione Añadir vista 3D de la lista desplegable para abrir la ventana. La ventana se
muestra de forma predeterminada a la derecha de la imagen térmica.

60

<!-- p. 69 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

\3. Haga clic en el cuadro desplegable en la esquina superior izquierda del panel Vista 3D
y seleccione el área (Imagen/Herramienta) para la cual desea generar la Vista 3D.
\4. Pase el ratón sobre la imagen de vista 3D generada y arrástrelo para rotar la imagen 3D
para una mejor observación general de la distribución de la temperatura.

Nota
La vista 3D generada se actualiza dinámicamente durante la reproducción de vídeo y
transmisión en vivo.

Exportar vista 3D
El cliente admite la copia, la exportación de imágenes de vista 3D y la exportación de
tablas de vista 3D (en formato CSV).
Haga clic con el botón derecho en la imagen de la Vista 3D y luego seleccione Exportar
imagen, Exportar archivo CSV o Copiar imagen para continuar.

5.5.4 Visualización de la curva de tiempo-temperatura para
vídeo/transmisión en vivo

El cliente admite la visualización de curvas de tiempo y temperatura para vídeos
radiométricos, vídeos de tendencias y análisis en vivo. La curva de tiempo-temperatura
representa el cambio de temperatura en un vídeo o transmisión o en cierta herramienta de
medición a lo largo del tiempo.
Apertura de la ventana de curva de tiempo-temperatura
\1. En la lista de tareas de la pestaña Análisis, seleccione un vídeo radiométrico o un vídeo
de tendencias, o conecte la cámara/imagen termográfica al análisis en vivo.
\2. En la pestaña de análisis, haga clic en el icono de la barra de herramientas para
abrir la lista de ventanas compatibles que se pueden añadir.
\3. En la lista desplegable, seleccione Agregar curva de tiempo-temperatura. La nueva
ventana se muestra debajo de la imagen térmica de forma predeterminada.
\4. Configure la curva de temperatura que se muestra en el gráfico.
Configuración y visualización de la curva de tiempo-temperatura
\1. Haga clic en el icono en la esquina superior derecha de la curva de temperatura
para abrir la ventana de configuración.
\2. Marque las curvas de temperatura que desee mostrar (temperatura máxima,
temperatura mínima, temperatura promedio y delta). Se permiten hasta 32 curvas.

61

<!-- p. 70 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Figura 5-15 Configuración de la curva de temperatura
\3. Ajuste el rango de tiempo que se muestra en el gráfico. Utilice la rueda del ratón o
haga clic en el icono para hacer zoom. Coloque el cursor en el borde
izquierdo/derecho de la ventana debajo de la curva y arrástrelo hacia la
izquierda/derecha para ver las tendencias de cambio de temperatura en diferentes
períodos de tiempo.
\4. Pase el ratón sobre la curva de temperatura y muévalo para ver la temperatura en
diferentes puntos de tiempo en la curva.

Figura 5-16 Curva de tiempo-temperatura

Exportar imagen y datos
La curva de tiempo-temperatura se puede exportar como imagen o como datos en

62

<!-- p. 71 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

formato CSV para guardar.
● Exportar imagen: Haga clic con el botón derecho en cualquier parte del gráfico y
seleccione Exportar imagen para guardarlo como una imagen en formato JPG. La
edición de imágenes no es compatible.
● Exportar datos: Haga clic en el icono en la esquina superior derecha del gráfico para
abrir la ventana Exportar máx./mín./promedio. Establezca los parámetros y haga clic en
Aceptar para exportar.
Orientación de los datos
La disposición de los datos en la tabla CSV.
Vertical: Los datos exportados para cada fotograma se organizan de arriba a abajo en
orden cronológico.
Horizontal: Los datos de cada fotograma están organizados de izquierda a derecha
en orden cronológico.
Seleccionar mediciones/delta
Marque los resultados de la imagen o de la herramienta de medición que desea
exportar.
Seleccionar fotogramas
Establezca los fotogramas de vídeo cubiertos por los datos exportados.
Todo: Exporta los datos de verificación de todos los fotogramas del vídeo.
Personalizado: Exporte los datos de verificación de los fotogramas seleccionados
(desde el Fotograma inicial hasta el Fotograma final).

5.5.5 Exportar la matriz de temperaturas de una imagen

Es posible exportar la Matriz de temperaturas de una imagen o de una medición en un
archivo CSV para futuros análisis.
Pasos
\1. Haga clic con el botón derecho en una imagen y seleccione Exportar matriz de temp..
Nota
Tenga en cuenta que hacer clic en un área de herramientas y en un área que no es de
herramientas es diferente.
● Á rea de herramientas: Exporta la matriz de temperaturas de la herramienta
seleccionada. El nombre de la herramienta se añadirá al nombre de archivo
predeterminado para identificar el archivo.
● Á rea sin herramientas: Exporta la matriz de temperaturas de toda una imagen.
\2. Edite el nombre de archivo y seleccione la ubicación del archivo. Haga clic en Aceptar
para exportar el archivo en formato CSV.
\3. Haga clic en Abrir archivo para ver la matriz de temperaturas.

63

<!-- p. 72 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

5.5.6 Exportar la matriz de temperaturas de un vídeo

Es posible exportar la matriz de temperaturas de todos los fotogramas o de fotogramas
específicos del vídeo o de una medición en un archivo CSV para futuros análisis.
Pasos
\1. Haga clic con el botón derecho en la imagen y seleccione Exportar valor de
temperatura.
Nota
Tenga en cuenta que hacer clic en un área de herramientas y en un área que no es de
herramientas es diferente.
● Á rea de herramientas: Exporta la matriz de temperaturas de la herramienta
seleccionada (excepto los polígonos y elipses).
● Á rea sin herramientas: Exporta la matriz de temperaturas de los fotogramas de una
imagen.
\2. Seleccione el tipo de exportación como Matriz de temperatura.
\3. Seleccione los fotogramas del vídeo.
\4. Haga clic en Aceptar.
\5. Cree un nombre para el archivo, y seleccione la ubicación del archivo. Haga clic en
Aceptar para exportar el archivo en formato CSV.
Qué hacer a continuación
Haga clic en Abrir archivo en la ventana emergente para ver la matriz de temperatura.

5.6 Ver y modificar anotaciones de imagen

Las anotaciones de imagen son diferentes textos, etiquetas, voz y otra información
adicional adjunta a la imagen térmica en la imagen térmica. En la pestaña Análisis, puede
ver y modificar parte de la información.
En la pestaña Análisis, seleccione un archivo en la lista de tareas y abra las anotaciones a
través de en la parte derecha de la ventana.

64

<!-- p. 73 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Figura 5-17 Anotación

Tabla 5-3 Anotaciones de imágenes
Tipo de anotación Descripciones
La etiqueta es la anotación de color añadida cuando el archivo se
administra en Mis favoritos. Durante el análisis de archivos, se
Etiqueta de color admiten las modificaciones a través de .
Para obtener información sobre cómo añadir etiquetas, consulte
Añadirunaetiquetadecoloraunarchivo.
Durante la captura de imágenes, los gráficos anotados en el
dispositivo mediante bocetos a mano alzada se denominan notas
Nota de boceto de boceto. Marque la opción Mostrar notas de boceto para mostrar
la capa de boceto. Si una imagen térmica no tiene ningún boceto
adjunto, la opción aparece desactivada.
La nota de texto es el texto que el usuario añade a la imagen. Puede
Nota de texto
verla y editarla en el cuadro de texto bajo Nota de texto.

65

<!-- p. 74 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Tipo de anotación Descripciones

Nota
Las notas de texto guardadas son leídas automáticamente por el
objeto nota de texto del informe.

La nota de voz es el contenido de voz que el usuario añade a la
imagen. Si una imagen tiene una nota de voz que se muestra en la
Nota de texto, haga clic en para reproducir el contenido de
voz.
Nota de voz
Nota
Si una imagen no contiene este contenido, no se muestra el botón
correspondiente.

Cuando necesite añadir rápidamente contenido de texto
estandarizado a varias imágenes, puede utilizar la nota de etiqueta.
El informe del análisis puede enlazar notas de etiqueta de
imágenes.
Antes de utilizar la nota de etiqueta, debe crear una plantilla de nota
de etiqueta.
Si una imagen tiene información de nota de etiqueta, puede
modificarla durante el análisis. Puede guardar notas de etiqueta en
Nota de etiqueta una imagen como plantilla.
El cliente admite la aplicación por lotes de plantillas de notas de
etiqueta a todas las imágenes térmicas de la lista de tareas.
Las notas de etiqueta de las imágenes de la lista de tareas pueden
modificarse por lotes.
Para obtener información sobre cómo crear y administrar notas de
etiqueta, consulte Crearyusarunaplantilladenotadeetiqueta.
Para obtener información sobre cómo añadir y modificar una nota
de etiqueta de una imagen, consulte Establecernotadeetiqueta.
La clasificación de fallo es el contenido que se añade cuando el
dispositivo toma imágenes de los objetos inspeccionados durante
Clasificación de
la inspección. Se puede modificar durante el análisis. Cuando sefallo
genera un informe de análisis, la clasificación de fallo se muestra
en la página de resumen.

66

<!-- p. 75 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Tipo de anotación Descripciones
La nota de imagen son imágenes tomadas con la lente visual del
dispositivo durante la captura de imágenes térmicas.
Nota de imagen Si una imagen térmica tiene estas notas de imagen, se pueden ver
en Nota de imagen. Haga clic en Imagen más grande en la esquina
inferior derecha para ampliar la imagen.

5.6.1 Crear y usar una plantilla de nota de etiqueta

Cuando el informe requiere una gran cantidad de información adicional, puede añadir y
configurar una nota de etiqueta. En estos momentos, esta función solo es compatible con
imágenes.
Gestión de plantillas de notas de etiqueta
\1. En la esquina superior derecha del cliente, haga clic en para abrir la ventana
Configuración de plantilla de nota de etiqueta.

Nota
Habrá un archivo de plantilla por defecto con el nombre General.json.

\2. En la esquina superior derecha de la ventana, haga clic en Nuevo para crear una
plantilla nueva. Introduzca el nombre de la plantilla y haga clic en Confirmar.
La plantilla creada aparecerá en la lista de plantillas.
\3. Seleccione la plantilla creada y haga clic en Editar a la derecha.

Icono Función
Añadir nueva Categoría.
/ /
Establezca el tipo de categoría como opción única, opción múltiple o txt.

Después de establecer el tipo de categoría, añada opciones o texto para la
categoría correspondiente.
Para la categoría de elección única o múltiple, puede seleccionar una
opción y hacer clic en / para moverse hacia arriba/abajo.
Seleccione una categoría, selección o texto y luego haga clic en para
editar el contenido o haga doble clic en la categoría, la opción o el texto
para editar el contenido.

Haga clic en para añadir la clasificación de fallos. La categoría de

67

<!-- p. 76 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Icono Función
clasificación de fallos no se puede editar.

\4. Una vez configurada la plantilla, haga clic en Guardar. La plantilla guardada puede
utilizarse para el análisis de imágenes.

Nota
En el caso de las plantillas añadidas y predeterminadas, puede eliminarlas o cambiarles
el nombre.
Las plantillas de notas de etiquetas pueden importarse o exportarse según sea
necesario.

Gestión local de plantillas de notas de etiqueta
La plantilla predeterminada y la plantilla recién añadida se guardarán en la ruta
(Public\HIKMICRO Analyzer\TextRemarkTemplate). También puede añadir y configurar
plantillas a través de cualquier editor de texto en el ordenador local.
El cliente leerá automáticamente los archivos de plantilla que estén en formato JSON y
cumplan con los protocolos pertinentes y la lista de plantillas se actualizará después de
volver a abrir la ventana Configuración de plantillas de notas de etiquetas o de
añadir/eliminar/importar cualquier plantilla.
Configuración de nota de etiqueta de imagen
En la página Análisis, puede seleccionar una plantilla añadida para la imagen actual o
configurar directamente una nota de etiqueta para la imagen en concreto. Con la nota de
etiqueta configurada específicamente para la imagen, si desea sustituirla por otra plantilla
existente, la información de la nota de etiqueta configurada se sobrescribirá y se perderá.
Consulte los detalles en Establecernotadeetiquetaparaunasolaimagen.
En la parte derecha de la página Análisis, haga clic en . Para saber cómo configurar la
nota de etiqueta, consulte Gestióndeplantillasdenotasdeetiqueta.

5.6.2 Establecer nota de etiqueta

Establecer nota de etiqueta para una sola imagen
Establezca el contenido de la nota de etiqueta y la plantilla para una imagen en el panel
Anotaciones. Haga clic en para guardar la configuración de esta imagen.
● : Edite el contenido de la nota de la etiqueta. Después de editarla, haga clic en
Guardar.
● : Cambiar la plantilla de la nota de la etiqueta. Para obtener detalles sobre cómo
gestionar notas de etiqueta, consulte Crearyusarunaplantilladenotadeetiqueta.

68

<!-- p. 77 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Establecer plantilla de nota de etiqueta para todas las imágenes
En la Lista de tareas, haga clic en y seleccione Aplicar plantilla de nota de etiqueta
para seleccionar una plantilla y haga clic en Sí. Todas las imágenes de la lista de tareas
utilizarán la misma plantilla de nota de etiqueta.
Modificar notas de etiqueta para varias imágenes
Use la función de importación/exportación de > Editar nota de etiqueta por lotes para
modificar las notas de etiqueta de todas las imágenes en la lista de tareas con un plantilla
de nota de etiqueta.
\1. Vaya a > Editar nota de etiqueta por lotes > Exportar a archivo CSV.
\2. Seleccione una plantilla de nota de etiqueta, establezca la Ubicación de exportación y
confirme la exportación.
\3. Abra el archivo exportado, edite el contenido y guarde el cambio.

Nota
● Se permite añadir y eliminar columnas de etiquetas.
● NO cambie el contenido o el nombre de la columna Ruta(Ruta). De lo contrario, la
importación del archivo podría fallar.
● NO cambie el formato del archivo al guardarlo después de editarlo.

\4. Vaya a > Editar nota de etiqueta por lotes > Importar desde archivo CSV para
seleccionar el archivo editado y confirme la importación.

Nota
Tras la importación, las etiquetas de opción múltiple y de opción única se convierten en
texto.

69

<!-- p. 78 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Capítulo 6 Generar un informe de imágenes

Puede generar un archivo de informe de una o varias imágenes térmicas, con contenido
como información de la imagen, parámetros de medición y resultados, y guardarlo en el
ordenador local para su posterior comparación y análisis.
El procedimiento para generar un informe es el siguiente.
\1. Seleccione las imágenes térmicas que se incluirán en el informe y ajuste el orden y la
agrupación de las imágenes en la lista de tareas. Consulte Añadiryorganizar
imágenestérmicaspara obtener más detalles.
Nota
● Si necesita comparar imágenes térmicas en una página de informe, se recomienda
crear grupos de imágenes en la Lista de tareas y, a continuación, seleccionar una
plantilla (plantilla de página o plantilla de informe) con páginas que incluyan el mismo
número de imágenes térmicas que en los grupos. Consulte Gruposdeimágenespara
obtener instrucciones.
Por ejemplo, si desea generar rápidamente una página de 2 imágenes térmicas, cree
un grupo de 2 imágenes y use la plantilla del sistema Comparación térmica x2 para
generar el informe.
● No se permiten vídeos para generar un informe.
\2. Seleccione una plantilla para las imágenes y los grupos.
● Seleccione la plantilla desde la página de inicio del informe .
○ Seleccione Nuevo informe para comenzar desde cero.
○ Haga clic en Biblioteca de plantillas para abrir la biblioteca de plantillas de páginas
e informes. Seleccione una plantilla para comenzar.
Para ver más funciones sobre las plantillas, consulte Plantilladeinformepara
obtener más detalles.
○ Haga clic en Usar última plantilla para comenzar con la última plantilla utilizada.

70

<!-- p. 79 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Figura 6-1 Página de inicio de informe
● En la página de edición de informes, haga clic en para seleccionar una plantilla a
fin de crear un nuevo informe. O haga clic en para volver a la página de inicio del
informe y crear un informe de otras maneras.
\3. Previsualice y edite su informe. Existen múltiples herramientas de edición.
● Herramientas de estilo: añadir y editar portada, página de resumen, encabezado y pie
de página, propiedades del documento y ajustar la alineación del contenido.
● Herramientas de organización de contenido: organizar todo el contenido con títulos
de diferentes encabezados y tablas. Los textos, las imágenes y los objetos de
contenido predefinidos (por ejemplo, una tabla de resultados de medición) pueden
insertarse en las celdas de la tabla.
● Objetos de contenido predefinidos: hay múltiples objetos de contenido predefinidos
para añadir imágenes y vincular datos rápidamente. Las categorías de objetos de
contenido disponible son Imagen, Información, Medición de temperatura y Gráficos
de distribución de temperatura.
Nota
Para los objetos de contenido predefinidos organizados en una tabla, es posible
añadir filas y columnas. Puede introducir texto o enlazar propiedades del documento
u otros elementos relacionados con la imagen.
Para más funciones de edición de un informe, consulte Editarinforme.
\4. Guarde y exporte su informe. Se admiten los formatos PDF y OTD. Consulte Exportar
archivopara obtener instrucciones.

6.1 Añadir y organizar imágenes térmicas

Antes de generar un informe, generalmente es necesario añadir las imágenes térmicas

71

<!-- p. 80 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

necesarias a la lista de tareas. Si necesita generar directamente un archivo de informe
utilizando imágenes de acuerdo con la plantilla de informe, ajuste el orden y los grupos de
imágenes con anticipación.
Pasos
\1. Añadir imágenes a la lista de tareas. Los siguientes dos métodos están disponibles.
– En la pestaña Biblioteca, seleccione una o más imágenes de las carpetas Archivo
local, Acceso rápido o Favoritos, haga clic con el botón derecho y seleccione
Procesamiento de archivos > Generar informe para ingresar directamente a la página
Informe.
– Si hay imágenes en la lista de tareas, haga clic en la pestaña Informe en la parte
superior para entrar en la página del informe.
\2. Ajuste el orden de las imágenes y los grupos en la lista de tareas. Haga clic con el botón
derecho para seleccionar una imagen o un grupo y luego arrástrelo hacia arriba o hacia
abajo para ajustar el orden.
Si necesita utilizar una plantilla de informe para generar por lotes páginas de análisis de
imágenes, el orden de las imágenes o grupos en la lista de tareas determina la
secuencia de las páginas de análisis de imágenes en el informe.
\3. Opcional: Agrupe imágenes. Se admiten la agrupación manual y la agrupación
automática. Consulte Gruposdeimágenespara obtener detalles.
Si una página de la plantilla de informe requiere agregar varias imágenes térmicas para
un análisis comparativo, las imágenes deben agruparse para una generación rápida y
adecuada.

6.2 Plantilla de informe

Puede seleccionar entre las plantillas existentes en el sistema, importar o crear más
plantillas para los informes.
Todas las plantillas, incluidas las del sistema y las personalizadas, se almacenan en la
Biblioteca de plantillas.
Plantillas de páginas del sistema
Existen 4 plantillas de páginas del sistema en el software. Puede verlas en la página de
selección de plantilla: Lote térmico x2, Comparación térmica x2, Imagen ampliada y
Térmico y visual.
● Las dos primeras plantillas de página (Lote térmico x2 y Comparación térmica x2), cada
una de las cuales contiene 2 imágenes térmicas, funcionan mejor con grupos de 2
imágenes.
● Térmico y visual tiene una imagen térmica. Funciona mejor con una única imagen.

72

<!-- p. 81 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

● Imagen ampliada no tiene imágenes térmicas. Una imagen térmica vinculada a esta
plantilla de página se convertirá en una imagen no radiométrica.

Figura 6-2 Seleccionar plantilla

Importar plantillas
El software permite la importación de plantillas. Consulte Importarplantillapara obtener
instrucciones.
Las plantillas que no son del sistema en la Biblioteca de plantillas se pueden exportar y
enviar a otros usuarios. Consulte Exportarplantillapara obtener instrucciones.
Guardar plantillas de página y plantillas de informe
Después de terminar de editar un informe (consulte Editarinformepara obtener
instrucciones), puede exportar el archivo completo como una plantilla de informe, o
seleccionar guardar páginas típicas como plantillas de página.
● Para guardar una plantilla de informe: seleccione en la barra de herramientas,
introduzca un nombre de plantilla y guarde el archivo.
Para guardar una plantilla de página: haga clic con el botón derecho en una miniatura de
página de la vista previa de páginas, seleccione Guardar como plantilla e introduzca un
nombre de plantilla para guardar el archivo.
Nota
● No está permitido que los nombres de las nuevas plantillas dupliquen los del sistema. Si

73

<!-- p. 82 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

establece un nombre que es el mismo que uno existente en una plantilla que no es del
sistema, se sobrescribirá el anterior.
● Al guardar una plantilla de informe, solo contiene 1) páginas sin imágenes térmicas (por
ejemplo, portada, página de resumen), y 2) páginas con diferente número de imágenes
térmicas, una página por cada número. Si en el informe hay varias páginas que
contienen la misma cantidad de imágenes térmicas, la primera página se guardará en la
plantilla de informe.
Gestionar plantillas
Vaya a Biblioteca de plantillas desde la página de inicio del informe para cambiar el
nombre y eliminar plantillas que no sean del sistema mediante el menú del botón derecho.

6.2.1 Importar plantilla

Pasos
\1. En la Biblioteca de plantillas de la página de inicio del informe, haga clic en Importar.
\2. Seleccione un archivo de plantilla (*.odt y *.art) del PC local.
\3. Haga clic en Abrir para importar la plantilla.

Nota
Se permiten hasta 64 plantillas (entre las que se incluye la plantilla predeterminada).
Para los informes generados con una plantilla *.odt, no se admite la vista previa ni la
edición en el software.

6.2.2 Exportar plantilla

\1. Seleccione Biblioteca de plantillas en la página de inicio del informe.
\2. Seleccione una plantilla personalizada (se admiten tanto plantillas de informe como de
página) y, a continuación, haga clic con el botón derecho en la plantilla. Las plantillas
incorporadas no se pueden exportar.
\3. Seleccione Exportar plantilla, establezca el nombre del archivo y haga clic en Guardar.

6.3 Editar informe

El informe se genera desde la plantilla y las imágenes seleccionadas. Es posible editar
objetos, añadir o eliminar páginas en el informe, personalizar la propiedad del texto,
cambiar plantilla, etc.

74

<!-- p. 83 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

6.3.1 Navegar por la interfaz de edición de informes

Aquí puede ver las miniaturas, configurar los objetos, cambiar la plantilla, etc.

Figura 6-3 Página de edición de informes
\1. Lista de tareas. El contenido de la Lista de tareas (excepto vídeos) se sincronizará en
la Biblioteca, el Análisis y la página del Informe. Las imágenes de la lista de tareas se
pueden añadir a la vista previa del informe arrastrándolas y soltándolas con el ratón.
\2. Botones de operación de la lista de tareas. Las operaciones funcionan en todos los
archivos de la lista de tareas, por ejemplo, agrupación automática, operación por lotes
y borrado de la lista.
\3. Vista general del informe. Puede ver las miniaturas de las páginas del informe y
arrastrarlas para ajustar el orden. Se puede añadir y eliminar páginas, así como
cambiar y exportar plantillas de página, mediante el menú contextual o los botones de
operación que se encuentran debajo.
\4. Vista previa de la página del informe. En la vista previa de la página, puede agregar
objetos de contenido, como imágenes, tablas de información, encabezados, etc., y
vincularlos a imágenes y parámetros térmicos. Puede arrastrar los objetos para
moverlos. Consulte Editarobjetopara obtener más detalles.
\5. Configuración de propiedad vinculada. Después de seleccionar una imagen térmica,
sus propiedades y parámetros relacionados se pueden sincronizar con las celdas

75

<!-- p. 84 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

correspondientes en las tablas.
\6. Configuración de detalles del objeto. Establezca el tamaño del objeto, los elementos a
mostrar, el estilo de la tabla, el número de columnas y filas, la imagen térmica
vinculada, etc.
\7. Herramientas de alineación de contenido y de acercamiento/alejamiento de página.
\8. Herramientas de encabezado, pie de página y propiedades de documento de informe.
La configuración funciona en todo el informe.
\9. Herramientas de objetos de contenido que incluyen imágenes e información de
imágenes, parámetros de medición, resultados y gráficos. Consulte Editarobjetopara
obtener más detalles.
\10. Nuevo informe.
\11. Página de inicio del informe.
\12. Exportar archivo de informe y guardar plantilla de informe. Consulte Exportarinformey
Plantilladeinformepara obtener más detalles.
Teclas de atajos
Vaya a Configuración > Teclas de atajos para ver y editar las teclas de atajos para la
edición de informes. Consulte Veryeditarteclasdeatajospara obtener más detalles.

6.3.2 Gestionar páginas

Puede añadir o eliminar páginas del informe, cambiar el orden de las páginas, editar la
propiedad del documento, añadir encabezados y pies de página al informe.

Añadir nueva página

Realice una de las siguientes operaciones para agregar una nueva página.

Nota
Se pueden añadir hasta 512 páginas de contenido, 1 portada y una página de resumen.

● Haga clic en en la esquina inferior izquierda, o haga clic con el botón derecho en
una miniatura de página a la izquierda y seleccione Página nueva para añadir diferentes
tipos de páginas. Están disponibles portada, página de contenido, página en blanco y
página de resumen.
○ Los tipos de página portada y página de resumen tienen objetos de contenido
editable predefinidos. Consulte Editarportaday Editarpáginaderesumenpara
obtener instrucciones.
○ Al añadir una página de contenido, seleccione una plantilla de página de la biblioteca.
Consulte Plantilladeinformepara obtener más información.

76

<!-- p. 85 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

○ Al añadir una página en blanco, puede añadir y editar objetos de contenido libremente.
Consulte Editarobjetopara obtener más información.
● También puede generar nuevas páginas de contenido arrastrando imágenes y grupos
de imágenes de la lista de tareas al área de resumen de informes o al área de objetos de
imágenes no térmicas.

Cambio del orden de las páginas

En la lista de miniaturas de páginas de la izquierda, puede arrastrar las páginas para
cambiar del orden de las mismas.

Eliminar página

Pasos
\1. Seleccione a la izquierda la página en miniatura que desea eliminar y realice las
siguientes operaciones para eliminar la página actual.
– Haga clic con el botón derecho del ratón en la miniatura y seleccione Eliminar página.
– Haga clic en en la parte inferior para eliminar la página seleccionada.
– Pulse la tecla Suprimir.
– Haga clic en en la parte de abajo para eliminar todas las páginas.

Editar portada

La portada tiene 3 objetos por defecto: logotipo, título y tabla de información del informe.
La tabla vincula automáticamente 4 propiedades del documento. Todos los contenidos se
pueden ajustar.
Pasos

Nota
La tabla de propiedades se incluye por defecto en la portada y no se puede
redimensionar, cambiar de posición ni eliminar.
\1. Haga clic para seleccionar el logotipo de la portada. Cambie la imagen del logotipo y
cambie su tamaño desde Detalles del objeto en el panel de la derecha.
\2. Edite el título.
\1) Haga doble clic en el título para cambiar el texto del título.
\2) Cambie el tamaño de fuente del título desde Detalles del objeto en el panel de la
derecha.
\3. Edite la tabla de información del informe de la portada.
\1) En la barra de herramientas, haga clic en para abrir la página Propiedad del
documento. Introduzca un valor para cada clave.

77

<!-- p. 86 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

El contenido de las celdas de la tabla de información que enlaza con la propiedad del
documento se actualizará de forma sincrónica.
\2) Haga clic en una celda de la tabla, establezca el número de fila, el número de
columna y muestre u oculte el borde/encabezado de la tabla desde Detalles del
objeto en el panel de la derecha.
\3) Haga doble clic en una celda añadida para introducir texto. O vincúlela con otras
propiedades del documento arrastrando el elemento deseado desde el panel
Propiedad vinculada (a la derecha) hasta la celda.
Nota
Solo se puede introducir texto en un celda antes de enlazarla con una propiedad. Para
eliminar una propiedad vinculada de una celda, haga clic con el botón derecho en la
celda y seleccione Eliminar propiedad vinculada.
\4. Otras operaciones: Haga clic en un objeto o una celda y seleccione , o para
ajustar la alineación.

Editar página de resumen

La página de resumen tiene un título por defecto y una tabla resumen. Para la tabla
resumen, puede establecer el número de columnas, establecer la alineación del texto y
vincular las celdas de la tabla con diferentes propiedades.
Pasos

Nota
El objeto de tabla resumen se incluye por defecto en la página de vista general y no se
puede redimensionar, cambiar de posición ni eliminar.
\1. Edite el título.
\1) Haga doble clic en el título para cambiar el texto del título.
\2) Cambie el tamaño de fuente del título desde Detalles del objeto en el panel de la
derecha.
\2. Seleccione el objeto de tabla resumen.
Aparecerá el panel de configuración del objeto a la derecha.
\3. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Establecer el Introduzca el número de columnas. Se permiten hasta 9
número de columnas.
columnas

78

<!-- p. 87 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Establecer la Seleccione , o para alinear el contenido a la izquierda,
alineación del texto centrado o a la derecha.

Propiedad del Para vincular una celda con una propiedad, seleccione el objeto
enlace o una celda de la tabla y, a continuación, arrastre una propiedad
del panel de configuración a la celda específica.
Para eliminar la propiedad vinculada, seleccione la celda, haga
clic con el botón derecho del ratón en la celda y seleccione
Eliminar propiedad vinculada.
Nota
● Una vez vinculada la celda con una propiedad, el contenido
vinculado no puede editarse.
● Para actualizar la información vinculada, haga clic en
Actualizar contenido vinculado.

\4. Opcional: Actualice la página de vista general.
\1) Haga clic con el botón derecho en la miniatura de la página de resumen de la
izquierda.
\2) Haga clic en Actualizar.

Configurar el encabezado

Puede configurar uno o varios encabezados con distintos formatos y contenidos.
\1. Haga clic en en la barra de herramientas o haga doble clic en el área del
encabezado en la página del informe para abrir la ventana de configuración del
encabezado.
\2. Compruebe el encabezado izquierdo, central o derecho según sea necesario.
\3. Seleccione imagen o texto como formato de encabezado y seleccione una imagen
específica o introduzca el texto, según sea necesario.
Nota
● Los encabezados en formato de texto no pueden superar los 200 caracteres.
● Cuando seleccione el formato de imagen, puede hacer clic en Añadir nueva para
importar imágenes desde el ordenador local.
● Puede obtener la vista previa de los encabezados en tiempo real.
\4. Haga clic en Aceptar para guardar la configuración del encabezado. Los encabezados
configurados se visualizarán en el informe.
Nota
Los encabezados no se aplicarán a la portada en el cliente ni en el ordenador local.

79

<!-- p. 88 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Cuando edite el informe en el cliente, la posición del encabezado mostrado solo será a
modo de referencia. El encabezado real del informe exportado se mostrará en la
posición de salto de página.

Configurar pie de página

Puede configurar uno o varios pies de página de diferentes contenidos.
\1. Haga clic en en la barra de herramientas o haga doble clic en el área del pie de
página en la página del informe para abrir la ventana de configuración del pie de
página.
\2. Compruebe el pie de página izquierdo, central o derecho según sea necesario.
\3. Seleccione texto o página como formato de pie de página e introduzca textos
específicos o seleccione el estilo de número de página según corresponda.
Nota
● Los pies de página en formato de texto no pueden superar los 200 caracteres.
● Puede obtener la vista previa de los pies de página en tiempo real.
\4. Haga clic en Aceptar para guardar la configuración del pie de página. Los pies de
página configurados se mostrarán en el informe.
Nota
Los pies de página no se aplicarán a la portada en el cliente ni en el ordenador local.
Cuando edite el informe en el cliente, la posición o el número de página del pie de
página mostrado solo será a modo de referencia. En el caso de los pies de texto, el pie
real del informe exportado se mostrará en la posición del salto de página; para el pie de
número de página, el número real de página del informe exportado se mostrará con el
total de páginas a la derecha de los saltos de página.

Establecer el tamaño de página del informe

En la esquina superior derecha del cliente, haga clic en > Preferencia. En Tamaño de la
página del informe, seleccione un tamaño de página en el menú desplegable.
El ajuste del tamaño de página se aplicará a la página Informe en el cliente y al informe
exportado en el ordenador local.

6.3.3 Editar objeto

Los objetos incluidos en el informe variarán dependiendo de la plantilla seleccionada. La
información relativa a la imagen o imágenes seleccionadas se introducirá
automáticamente en los objetos correspondientes. Es posible editar los objetos existentes,
incluyendo el cambio de la imágenes térmica vinculada, configurar el tipo de imagen,

80

<!-- p. 89 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

personalizar textos, etc.
Nota
Para los objetos que pueden vincularse con imágenes térmicas, es posible ver el nº de
imagen térmica en la lista desplegable Vincular imagen térmica.

Añadir objeto

Haga clic en el icono del objeto específico en la barra de herramientas.
Nota
No se pueden añadir objetos a la portada ni a la página de resumen.
Admite la visualización de la superposición de información de temperatura en el objeto de
imagen térmica y el objeto de mediciones (establecido en Configuración > Superposición
de informe).
Se pueden introducir textos directamente sin añadir objetos.

Icono Objeto
Tabla personalizada
Para la presentación de informes, solo se permite un objeto en cada fila de texto;
si se necesitan varios objetos en una fila, puede añadir un objeto de tabla
personalizado para anidarlos.
Para la edición específica de objetos de tabla personalizados, consulte Tabla
personalizada.
Título. Hay niveles de fuente ajustables en Detalles del objeto en el panel de la
derecha.
Térmica
Para editar un objeto de imagen térmica específico, consulte Imagentérmica.
Visual
Para editar un objeto de imagen visual específico, consulte Imagenvisual.
Logotipo
Para editar un objeto de logotipo específico, consulte Logotipo.
Información
● Información de la Imagen
Para editar un objeto de información de imagen, consulte Informacióndela
Imagen.
● Información del dispositivo

81

<!-- p. 90 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Icono Objeto
Para editar un objeto de información del dispositivo específico, consulte
Informacióndeldispositivo.
● Nota de texto
Para editar un objeto de nota textual específico, consulte Notadetexto.
● Nota de etiqueta
Para editar un objeto de nota de etiqueta específico, consulte Notadeetiqueta.

Medición de la temperatura
● Mediciones
Para editar un objeto de medición específico, consulte Mediciones.
● Parámetros de imagen
Para editar un objeto de parámetros de imagen, consulte Parámetrosde
imagen.
● Parámetros de medición
Para editar un objeto de parámetros de medición, consulte Parámetrosde
medición.
● Delta
Para editar un objeto delta específico, consulte Delta.

Nota
Se permite un máximo de un Delta en cada página.

Gráficos de distribución de temp.
● Gráfico de barras de distribución de temp.
Para editar un objeto de gráfico de barras de distribución de temperaturas
específico, consulte Gráficodebarrasdedistribucióndetemp..
● Gráfico de líneas de distribución de temp.
Para editar un objeto de gráfico de líneas de distribución de temperaturas
específico, consulte Gráficodelíneasdedistribucióndetemp..

Mover/Ajustar objeto

Puede mover y ajustar el objeto en el informe.
Seleccione un objeto en el informe. Podrá efectuar las operaciones siguientes:
● Arrastrar el objeto a la posición que necesite.

82

<!-- p. 91 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

● Arrastrar las cuatro esquinas de un objeto de imagen para ajustar su tamaño; arrastrar
los dos lados de un objeto de tabla para ajustar su anchura.
Nota
También puede introducir el valor específico del tamaño en el panel de configuración de
objetos de la derecha.
El sistema controla automáticamente el tamaño de las imágenes, logotipos y tablas
insertados en las celdas.

Copiar/Cortar el objeto informe

Los objetos de informe se pueden copiar o cortar a otros lugares del informe o a otro
software (como un documento de Word).
Haga clic con el botón derecho en el objeto del informe y seleccione Cortar/Copiar, o pulse
los atajos de teclado Ctrl + C o Ctrl + X para cortar o copiar el objeto seleccionado.
Nota
Cuando corte o copie un objeto, también incluirá el formato del objeto. Por ejemplo, el
tamaño de letra y la alineación se incluirían al copiar o cortar un texto, el nombre de la
imagen se incluirá al copiar o cortar una imagen.

Tabla personalizada

Puede insertar un objeto de tabla personalizado, del que podrá editar el número de líneas y
columnas, configurar el contenido, vincular celdas con propiedades, etc.
Pasos

Nota
Para las celdas que no tienen una propiedad vinculada, se pueden insertar objetos de
tipo imagen (por ejemplo, Imagentérmicae Imagenvisual) y objetos de tipo tabla (por
ejemplo, Informacióndeldispositivoy Mediciones).
\1. Seleccione el objeto de tabla general en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Ocultar los bordes Marque o desmarque la opción Ocultar los bordes de la tabla
de la tabla para ocultar o mostrar los bordes de la tabla. Cuando está
marcada, el borde se representará mediante líneas de puntos en

83

<!-- p. 92 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

el cliente.

Establecer la Seleccione , o para alinear el objeto a la izquierda,
alineación de centrado o a la derecha.
texto/objetos

Establecer filas y Introduzca el número concreto de filas y columnas que
columnas necesite.
Nota
● Se pueden introducir hasta 20 filas y 10 columnas.
● Puede seleccionar una celda y hacer clic con el botón
derecho para insertar o eliminar una fila o columna.

Exibir itens Marque la opción Encabezado de tabla para que se muestre en
el objeto según sea necesario.
Una vez marcada, puede hacer doble clic en el encabezado de la
tabla para introducir los textos que necesite. Pulse Alt + Intro
para saltar de línea.

Introducir texto en Seleccione una celda que no se haya vinculado con ninguna
la celda propiedad y haga doble clic en la celda para introducir textos.
Pulse Alt + Intro para saltar de la línea dentro de la celda.

Vincular la celda Para vincular una celda con una propiedad, seleccione el objeto
con una propiedad o una celda de la tabla y, a continuación, arrastre una propiedad
del panel de configuración a la celda específica.
Para eliminar la propiedad vinculada, seleccione la celda, haga
clic con el botón derecho del ratón en la celda y seleccione
Eliminar propiedad vinculada.
Nota
Una vez vinculada la celda con una propiedad, el contenido
vinculado no puede editarse.

Insertar un objeto Seleccione una celda que no se haya vinculado con la
en la celda propiedad, haga clic con el botón derecho del ratón en la celda y
seleccione Insertar imagen / Insertar tabla.

Imagen térmica

84

<!-- p. 93 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Las imágenes térmicas añadidas a la lista de tareas de análisis se mostrarán
automáticamente en el objeto Imagen térmica.
Pasos
\1. Seleccione una imagen térmica en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Establecer tamaño ● Introduzca el valor específico para la anchura y la altura, para
ajustar el tamaño de la imagen. La anchura y la altura solo
pueden modificarse uniformemente.
● Seleccione el objeto y arrastre una de las 4 esquinas para
escalar uniformemente la imagen.

Eliminar imagen Para eliminar la imagen, desplace el ratón por encima de la
térmica miniatura de la imagen y haga clic en Eliminar.
Nota
Si un objeto ya está vinculado con una imagen térmica, al
eliminar la imagen térmica vinculada o el objeto vinculado con
la imagen térmica, también se eliminará la vinculación, y esta
acción no se puede deshacer.

Cambiar imagen Para cambiar la imagen, pase el ratón por encima de la
térmica miniatura de la imagen y haga clic en Seleccionar para
seleccionar una imagen diferente, o arrastre una imagen de la
lista de tareas al objeto de destino.
Nota
● Si arrastra la imagen a otras posiciones, por ejemplo, al área
de vista general del informe o a un área del informe que no
sea objeto de imagen térmica, se generará una nueva página
de contenido para la imagen. Consulte los detalles en Añadir
nuevapágina. No es posible arrastrar imágenes por lotes
para cambiar imágenes térmicas por lotes. Cuando arrastre
varias imágenes, se generarán varias páginas de contenido

85

<!-- p. 94 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

de forma correspondiente, con independencia de la posición
a la que arrastre las imágenes.

Establecer la Seleccione , o para alinear el objeto a la izquierda,
alineación del centrado o a la derecha.
objeto

Exibir itens Marque Escala de temperatura para visualizar la barra de escala
a la derecha de la imagen térmica.
Marque Nombre de la imagen para mostrar el nombre de la
imagen debajo de la imagen térmica.

Establecer como Haga clic con el botón derecho en el objeto de la imagen
imagen principal térmica y seleccione Establecer como imagen principal. Una vez
establecida como imagen principal, la imagen térmica se
mostrará como miniatura de la página actual a la izquierda para
su previsualización.

Editar imagen Haga doble clic en una imagen térmica o clic con el botón
térmica derecho y seleccione Editar para empezar a editar. Consulte
Análisisdeimágenespara obtener instrucciones.
Haga clic en Guardar cuando haya terminado de editar.

Imagen visual

Las imágenes visuales y las imágenes normales vinculadas a imágenes térmicas se
mostrarán en el objeto Imagen visual.
Pasos
\1. Seleccione el objeto de imagen visual en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Establecer tamaño ● Introduzca el valor específico para la anchura y la altura, para
ajustar el tamaño de la imagen. La anchura y la altura solo
pueden modificarse uniformemente.
● Seleccione el objeto y arrastre una de las 4 esquinas para

86

<!-- p. 95 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

escalar uniformemente la imagen.

Seleccionar tipo Seleccione el tipo de imagen en la lista desplegable.
● Selección automática: El objeto se rellenará automáticamente
con la imagen vinculada a la imagen térmica.
● Otra imagen: Puedes añadir imágenes convencionales desde
el ordenador local. Haga clic en para agregar una imagen.
Pase el ratón por encima de la imagen añadida y haga clic en
para eliminarla.
● Imagen visual alineada: Al seleccionar este tipo, el objeto se
rellenará automáticamente con la imagen visual alineada
correspondiente a la imagen térmica vinculada.

Figura 6-4 Imagen visual alineada
● Imagen visual a tamaño completo: Al seleccionar este tipo, el
objeto se rellenará automáticamente con la imagen visual a
tamaño completo correspondiente a la imagen térmica
vinculada.

Figura 6-5 Imagen visual a tamaño completo
● Nota de imagen: Imágenes visuales asociadas a una imagen
térmica. El contenido de las imágenes puede ser diferente de
la imagen térmica. Las notas de imagen se toman cuando el
dispositivo captura una imagen térmica, y no se permite
cambiarlas en el software. Si una imagen térmica no tiene
ninguna nota de imagen asociada, el área de imagen
permanece en blanco.

Vincular imagem Cuando selecciona Selección automática, Imagen visual
termográfica alineada, Imagen visual a tamaño completo o Nota de imagen,
puede vincular una imagen térmica con el objeto. Seleccione

87

<!-- p. 96 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

una imagen térmica de la lista desplegable y el objeto se
rellenará automáticamente con la imagen visual vinculada a la
imagen térmica.

Cargar imagen Cuando seleccione Otra imagen como tipo de imagen, puede
hacer clic en Añadir o doble clic en el objeto para cargar un
archivo de imagen local.

Establecer la Seleccione , o para alinear el objeto a la izquierda,
alineación del centrado o a la derecha.
objeto

Exibir itens Marque Nombre de la imagen para mostrar el nombre de la
imagen debajo de la misma.

Logotipo

Pasos
\1. Seleccione un objeto de logotipo en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Operación Descripción

Establecer tamaño Introduzca el valor específico de anchura y altura del logotipo
según sea necesario. La anchura y la altura solo pueden
modificarse uniformemente.

Establecer la Seleccione , o para alinear el objeto a la izquierda,
alineación del centrado o a la derecha.
objeto

Añadir logotipo Haga clic en Añadir para cargar una imagen como el logotipo
desde el ordenador local.
Nota
● Una vez añadido el logotipo, puede pasar el ratón por encima
de la imagen añadida y hacer clic en Eliminar o Seleccionar
para eliminar o cambiar el logo.
● Si ha eliminado o modificado el logotipo, puede hacer clic en
Restablecer para restaurar el logotipo predeterminado.

88

<!-- p. 97 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

El efecto de la configuración puede previsualizarse sincronizadamente en el informe.

Información de la Imagen

En este objeto se mostrará el nombre de la imagen, la resolución IR, el tamaño de la
imagen y la hora de captura.
Pasos
\1. Seleccione la información de la imagen en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Establecer tamaño ● Introduzca el valor específico de la anchura.
● Seleccione el objeto y arrastre uno de los 2 lados para ajustar
la anchura.

Establecer la Seleccione , o para alinear el contenido a la izquierda,
alineación de centrado o a la derecha.
texto/objetos

Vincular imagem Seleccione una imagen térmica de la lista desplegable para
termográfica vincularla con este objeto. El objeto se rellenará
automáticamente con la información de la imagen térmica
vinculada.
Nota
La información de la imagen térmica no se puede editar.

Exibir itens Marque los elementos que se mostrarán en el objeto según sea
necesario.

Información del dispositivo

En este objeto se mostrará la información del dispositivo de captura, incluido el modelo de
dispositivo, el número de serie del dispositivo, etc.
Pasos
\1. Seleccione la información del dispositivo en el informe.

89

<!-- p. 98 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Establecer tamaño ● Introduzca el valor específico de la anchura.
● Seleccione el objeto y arrastre uno de los 2 lados para ajustar
la anchura.

Establecer la Seleccione , o para alinear el contenido a la izquierda,
alineación de centrado o a la derecha.
objeto/texto

Vincular imagem Seleccione una imagen térmica de la lista desplegable para
termográfica vincularla con este objeto. El objeto se rellenará
automáticamente con la información del dispositivo de la
imagen térmica vinculada.
Nota
La información vinculada no se puede editar.

Exibir itens Marque los elementos que se mostrarán en el objeto según sea
necesario.

Nota de texto

La información de la nota de texto se mostrará en este objeto.
Antes de comenzar
Para añadir una nota de texto a la imagen térmica, consulte los detalles en .
Pasos
\1. Seleccione el objeto de la Nota de texto en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.

Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.

90

<!-- p. 99 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Operación Descripción

Editar título del Puede editar el título del objeto (Nota de texto predeterminada).
objeto

Establecer tamaño ● Introduzca el valor específico de la anchura.
● Seleccione el objeto y arrastre uno de los 2 lados para ajustar
la anchura.

Establecer la Seleccione , o para alinear el contenido a la izquierda,
alineación de centrado o a la derecha.
texto/objeto

Vincular imagem Seleccione una imagen térmica de la lista desplegable para
termográfica vincularla a este objeto. El objeto se rellenará automáticamente
con notas de texto de la imagen térmica vinculada.
Nota
La información vinculada no se puede editar.

Nota de etiqueta

Los objetos de nota de etiqueta se utilizan para reponer la información correspondiente
sobre imágenes térmicas.
Pasos
\1. Seleccione el objeto de la nota de etiqueta en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Cambiar el estilo de Para cambiar el estilo de la tabla, marque las casillas Ocultar
la tabla borde de tabla y Título de tabla.

Establecer la Seleccione , o para alinear el contenido a la izquierda,
alineación de centrado o a la derecha.
texto/objetos

91

<!-- p. 100 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Editar título de Haga doble clic en el encabezado de la tabla para entrar en el
tabla modo de edición.

Vincular imagem Seleccione una imagen térmica de la lista desplegable para
termográfica vincularla con este objeto. La tabla se rellenará
automáticamente con la información de la nota de etiqueta de
la imagen térmica vinculada.
Nota
La nota de etiqueta vinculada en la tabla no se puede editar. La
tabla se rellena automáticamente a medida que cambia la
imagen vinculada.

Mediciones

En este objeto se mostrarán las mediciones de los parámetros de la imagen global y los
parámetros de las herramientas de medición, incluyendo la gravedad, la temperatura
máxima, la temperatura mínima, la temperatura central, etc.
Pasos
\1. Seleccione un objeto de medición en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Cambiar el estilo de Para cambiar el estilo de la tabla, marque las casillas Ocultar
la tabla borde de tabla y Título de tabla.

Establecer la Seleccione , o para alinear el contenido a la izquierda,
alineación del texto centrado o a la derecha.

Editar título de Haga doble clic en el encabezado de la tabla para entrar en el
tabla modo de edición.

Vincular imagem Seleccione una imagen térmica de la lista desplegable para
termográfica vincularla a este objeto. La tabla se rellenará automáticamente
con resultados de medición de la imagen térmica vinculada.

92

<!-- p. 101 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Nota
El resultado de la medición vinculada no se puede editar. La
tabla se rellena automáticamente a medida que cambia la
imagen vinculada.

Parámetros de imagen

En este objeto se mostrarán los parámetros de la imagen global, como la distancia, la
humedad, la temperatura atmosférica, etc.
Pasos
\1. Seleccione el objeto de parámetros de imagen en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Establecer tamaño ● Introduzca el valor específico de la anchura.
● Seleccione el objeto y arrastre uno de los 2 lados para ajustar
la anchura.

Establecer la Seleccione , o para alinear el contenido a la izquierda,
alineación de centrado o a la derecha.
texto/objetos

Vincular imagem Seleccione una imagen térmica de la lista desplegable para
termográfica vincularla a este objeto. El objeto se rellenará automáticamente
con los parámetros de la imagen global de la imagen térmica
vinculada.
Nota
La información vinculada no se puede editar.

Exibir itens Marque los elementos que se mostrarán en el objeto según sea
necesario.

93

<!-- p. 102 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Parámetros de medición

En este objeto se mostrarán los parámetros de las herramientas de medición, como la
emisividad, la distancia, etc.
Pasos
\1. Haga clic en el objeto Parámetros de medición del informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Cambiar el estilo de Para cambiar el estilo de la tabla, marque las casillas Ocultar
la tabla borde de tabla y Título de tabla.

Establecer la Seleccione , o para alinear el contenido a la izquierda,
alineación de centrado o a la derecha.
texto/objetos

Editar título de Haga doble clic en el encabezado de la tabla para entrar en el
tabla modo de edición.

Vincular imagem Seleccione una imagen térmica de la lista desplegable para
termográfica vincularla a este objeto. El objeto se rellenará automáticamente
con los parámetros de las herramientas de medición de la
imagen térmica vinculada.
Nota
La información vinculada no se puede editar. La tabla se rellena
automáticamente cuando cambia la imagen vinculada.

Exibir itens Marque los elementos que se mostrarán en el objeto según sea
necesario.

Delta

La tabla de rangos delta y valores estándar (basada en los resultados de gravedad) se
mostrará en este objeto. El resultado del delta de medición configurado en una imagen
térmica en la página de informe cambiará al color correspondiente según el rango y los
estándares establecidos.

94

<!-- p. 103 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Antes de comenzar
Las imágenes térmicas de la página deben contener herramientas delta, y el resultado de
la medición delta debe mostrarse en forma de tabla.
Pasos
\1. Seleccione un objeto Delta en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Establecer tamaño ● Introduzca el valor específico de la anchura.
● Seleccione el objeto y arrastre uno de los 2 lados para ajustar
la anchura.

Establecer la Seleccione , o para alinear el contenido a la izquierda,
alineación de centrado o a la derecha.
texto/objetos

Vincular imagem Seleccione una imagen térmica de la lista desplegable para
termográfica vincularla a este objeto. El objeto se rellenará automáticamente
con los resultados de la gravedad de la imagen térmica
vinculada.
Nota
La información vinculada no se puede editar.

Configurar el rango Puede editar los nombres de los rangos delta y los valores
Delta estándar.

Gráfico de barras de distribución de temp.

El gráfico de barras de distribución de temperaturas de la imagen térmica vinculada se
mostrará en este objeto para su posterior análisis.
Pasos
\1. Seleccione el objeto del Gráfico de barras de distribución de temp. en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.

95

<!-- p. 104 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Establecer tamaño ● Introduzca el valor específico para la anchura y la altura para
ajustar el tamaño del objeto.
● Seleccione el objeto y arrastre una de las 4 esquinas para
escalar uniformemente el objeto.

Vincular imagem Seleccione una imagen térmica de la lista desplegable para
termográfica vincularla a este objeto. El objeto se rellenará automáticamente
con el gráfico de barras de distribución de temperaturas de la
imagen térmica vinculada.

Vincular medições Seleccione la medición que desea aplicar y el objeto se rellenará
automáticamente con la información correspondiente a la
medición.

Establecer la Seleccione , o para alinear el objeto a la izquierda,
alineación del centrado o a la derecha.
objeto

Número de barras Introduzca un número específico para las barras o haga clic en
o para aumentar o disminuir el número de barras.

Gráfico de líneas de distribución de temp.

El gráfico de líneas de distribución de temperaturas de la imagen térmica vinculada se
mostrará en este objeto para su posterior análisis.
Pasos
\1. Seleccione el objeto del Gráfico de líneas de distribución de temp. en el informe.
Aparecerá el panel de configuración del objeto a la derecha.
\2. Podrá efectuar las operaciones siguientes.
Nota
El efecto de la configuración puede previsualizarse sincronizadamente en el informe.
Operación Descripción

Establecer tamaño ● Introduzca el valor específico para la anchura y la altura para
ajustar el tamaño del objeto.

96

<!-- p. 105 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

● Seleccione el objeto y arrastre una de las 4 esquinas para
escalar uniformemente el objeto.

Vincular imagem Seleccione una imagen térmica de la lista desplegable para
termográfica vincularla a este objeto. El objeto se rellenará automáticamente
con el gráfico de líneas de distribución de temperaturas de la
imagen térmica vinculada.

Vincular medições Seleccione la medición que desea aplicar y el objeto se rellenará
automáticamente con la información correspondiente a la
medición.
Nota
● Si modifica o elimina la imagen térmica vinculada, también se
modificará la medición vinculada.
● Solo puede vincular la medición de líneas y la medición de
polilíneas.

Establecer la Seleccione , o para alinear el objeto a la izquierda,
alineación del centrado o a la derecha.
objeto

6.3.4 Eliminar objeto

Pasos
\1. Realice una de las siguientes operaciones para eliminar el objeto seleccionado.
– Seleccione un objeto, haga clic con el botón derecho del ratón en el objeto y
seleccione Eliminar objeto.
– Seleccione un objeto y haga clic en Contenido > Eliminar objeto.

6.3.5 Cambiar la plantilla de la página seleccionada

Pasos
\1. Haga clic con el botón derecho del ratón en una página.
\2. Seleccione Cambiar plantilla.
\3. Seleccione una plantilla adecuada para sustituir a la actual.
\4. Haga clic en Guardar.

97

<!-- p. 106 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

6.4 Exportar archivo

6.4.1 Exportar informe

Tras editar y previsualizar el informe en el cliente, puede exportarlo al ordenador local para
comparar, analizar y resumir las estadísticas de medición de la temperatura. Puede
realizar operaciones como editar el nombre del archivo del informe, establecer la ruta de
guardado, exportar el informe como PDF o archivo ODT editable y abrir la carpeta del
archivo exportado.
\1. En la barra de herramientas de la página del informe, haga clic en .
\2. Seleccione ODT o PDF como formato de archivo, edite el nombre del archivo y
configure la ruta de guardado.
\3. Haga clic en Aceptar para exportar el informe.
Nota
● Por defecto, para el nombre del informe se usará la fecha de exportación, el mes y el
año. Para los informes exportados el mismo día, puede optar por sustituir el archivo
anterior o volver atrás para cambiar manualmente el nombre del informe.
● En el aviso de exportación correcta, puede hacer clic en Abrir carpeta para ver el
informe exportado en el ordenador local o hacer clic en Aceptar para permanecer en
la página de edición del informe.
● Puede editar el archivo ODT exportado en Microsoft Word.

6.4.2 Exportar objeto único

Puede exportar de forma independiente como archivos CSV los objetos de tipo tabla del
informe (Información del informe, Tabla resumen, Tabla general, Información de la imagen,
Información del dispositivo, Nota de texto, Nota de etiqueta, Mediciones, etc.).
\1. Seleccione un objeto de tipo tabla en el informe, haga clic con el botón derecho del
ratón en el objeto y seleccione Exportar archivo CSV.
\2. Edite el nombre del archivo y la ruta de guardado según sea necesario.
\3. Haga clic en Aceptar para exportar el archivo CSV.
Nota
● Por defecto, para el nombre del archivo se usará la fecha de exportación, el mes y el
año. Para los archivos exportados el mismo día, puede optar por sustituir el archivo
anterior o volver atrás para cambiar manualmente el nombre del archivo.
● En el aviso de exportación correcta, puede hacer clic en Abrir archivo para ver el
archivo exportado en el ordenador local.

98

<!-- p. 107 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Capítulo 7 Análisis en vivo

Tras conectar el dispositivo al cliente, podrá ver imágenes en directo, realizar mediciones
en tiempo real, capturar instantáneas y grabar vídeos para su posterior análisis.

Nota
El análisis en directo requiere que su dispositivo sea compatible. Si se conecta con un
cable USB, el dispositivo debe ser compatible con el protocolo de transmisión en tiempo
real UVC. Al conectar el dispositivo al cliente por red, el dispositivo debe admitir conexión
de red por cable o inalámbrica.

Los pasos principales del análisis en directo son los siguientes:
\1. Conecte su dispositivo al cliente mediante un cable USB o red.
Para la conexión USB, consulte ConectarlacámaraatravésdeUSB.
Para una conexión de red, consulte Conectarlacámaraatravésdered.
\2. Tras la conexión, configure los parámetros del dispositivo para obtener una imagen
nítida y una transmisión fluida. Consulte Establecerlosparámetrosdeldispositivo.
\3. Ajuste la configuración de la imagen y la medición, y compruebe los resultados de la
medición en tiempo real. Las operaciones son similares a las del análisis de vídeo.
Consulte Análisisdevídeopara obtener instrucciones.

Nota
● Si necesita que el software cliente guarde las configuraciones de medición de imagen
y temperatura para la futura conexión del mismo dispositivo, habilite Recordar
configuraciones en vivo en Configuración > Preferencias.
● Haga clic en Restaurar a valores predeterminados en la esquina superior derecha de
la ventana para recuperar la configuración de imagen y medición a los valores
predeterminados del cliente.

\4. Guarde las instantáneas, los vídeos, los diagramas, etc. para su posterior análisis.
● Para capturar instantáneas, consulte Capturarimágenes
● Para grabar vídeos, consulte Grabarvídeo.
● Para exportar imágenes y datos de diagramas, consulte Visualizacióndelacurvade
tiempo-temperaturaparavídeo/transmisiónenvivoy Exportarlamatrizde
temperaturasdeunvídeo.

99

<!-- p. 108 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

7.1 Navegación por la pestaña En vivo

Figura 7-1 Pestaña En vivo
\1. Controles de conexión del dispositivo. Consulte ConectarlacámaraatravésdeUSBo
Conectarlacámaraatravésderedpara obtener instrucciones.
\2. Estado del dispositivo. Tras conectarse a un dispositivo, muestra la velocidad de
fotogramas en tiempo real del dispositivo, la tasa de renderizado, la resolución IR, etc.
\3. Ajustes de dispositivo. Se permite ajustar funciones del dispositivo como la velocidad
de fotogramas, el rango de temperatura o la calibración manual de la imagen. Consulte
Establecerlosparámetrosdeldispositivopara obtener instrucciones.
\4. Capturas y grabaciones Se permite capturar instantáneas de forma manual o
programada y grabar vídeos. Consulte Capturarimágenesy Grabarvídeopara obtener
instrucciones.
\5. Ventana de valor de la temperatura. Muestra las temperaturas medidas en la imagen y
herramientas de medición. Para abrir la ventana, consulte Ajustedeldiseñodela
ventanapara obtener más detalles.
\6. Ventana de curva de temperatura en tiempo real. Muestra las temperaturas en tiempo
real de los puntos destacados en la imagen o herramientas de medición en gráficos.
Para la configuración de la curva, consulte Visualizacióndelacurvade
tiempo-temperaturaparavídeo/transmisiónenvivoy Verelhistogramadedistribución
detemperaturayelgráficodelíneasdetemperatura. La ventana se puede abrir con las

100

<!-- p. 109 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

herramientas de diseño de ventanas en la barra de herramientas; consulte Ajustedel
diseñodelaventanapara obtener instrucciones.
\7. Herramientas de configuración de la paleta. Existen principalmente cuatro tipos de
paletas: las paletas comunes y sus versiones invertidas, la isoterma, la condensación y
el aislamiento. Consulte Paletasypaletasinvertidas, Establecerisoterma, Aislamiento,
Deteccióndecondensación, Nivelyrangoy Distribucióndecolorpara obtener más
detalles.
\8. Herramientas avanzadas de edición, rotación y cambio de tamaño de imágenes.
Consulte Ediciónavanzadadeimageny Rotarycambiareltamañodeunaimagenpara
obtener más detalles.
\9. Herramientas de análisis de medición. Utilice estas herramientas para añadir y editar
distintos tipos de mediciones, borrar todas las mediciones, etc. Consulte Añadir
herramientademediciónpara obtener más detalles.
\10. Diseños y ventanas rápidos. Puede aplicar opciones de diseño rápido u organizar
libremente los diseños de las ventanas. Consulte Ajustedeldiseñodelaventanapara
obtener instrucciones.

Nota
● Si el dispositivo entra en modo de prevención de quemadura (el obturador del
dispositivo está cerrado para evitar que el detector sufra daños causados por objetivos
inesperados a alta temperatura) durante la transmisión en directo, aparecerá un aviso
recordando al usuario esta situación.
● Cuando la resolución IR de un dispositivo es inferior a 256×192, el cliente ofrece la
opción de activar SuperIR. La función adopta la tecnología de superresolución para
mejorar la visualización; consulte Súperresoluciónpara obtener más información.

Teclas de atajos en el análisis en vivo
Vaya a Configuración > Teclas de atajos para ver y editar las teclas de atajos. Para
obtener más información, consulte Veryeditarteclasdeatajos.

7.2 Conectar la cámara a través de USB

Puede conectar una cámara térmica que admita la transmisión de vídeo infrarrojo
radiométrico al ordenador a través de USB. Tras conectar la cámara, puede realizar
operaciones como la visualización en directo, la captura de imágenes y la medición de la
temperatura.
Prepararse para la transmisión
\1. Conecte la cámara a un puerto USB de su ordenador con el cable USB suministrado.

101

<!-- p. 110 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Mantenga la cámara encendida.
\2. Seleccione Proy. pantalla USB en el menú emergente de la cámara.
Nota
● Para cámaras con versiones de firmware anteriores, active Proy. pantalla USB en el
menú de configuración (consulte el manual de usuario de su cámara). De lo contrario,
la transmisión puede fallar.
● Se recomienda conectar con un puerto y un cable USB 3.0 si su ordenador y
dispositivo admiten la función. En comparación con USB 2.0, USB 3.0 permite una
configuración de velocidad de fotogramas más alta para garantizar una transmisión
más fluida para determinados modelos de alta resolución IR. Si su cámara admite
USB 3.0, siga las instrucciones del cliente para cambiar el puerto USB.
Iniciar la transmisión en el cliente
\1. En la esquina superior izquierda, haga clic en > Conexión USB.
\2. Haga clic en Seleccionar dispositivo para ver la lista de dispositivos detectados. Haga
clic en Actualizar y espere si no se ha detectado ningún dispositivo.
\3. Seleccione un dispositivo y haga clic en Conectar para iniciar la vista en directo.
Nota
Durante la vista en directo, si desea cambiar a otras pestañas, elija Fondo para
mantener la transmisión en segundo plano.
\4. Haga clic en Desconectar para detener la vista en directo.

Nota
● El cliente es capaz de detectar varios dispositivos USB, pero solo transmite desde un
dispositivo a la vez.
● Si un dispositivo está transmitiendo, evita enchufar/desenchufar otros terminales USB
en el ordenador.
● Evite actualizar la lista de dispositivos con frecuencia.

7.3 Conectar la cámara a través de red

Puede conectar una cámara térmica por red cableada o inalámbrica para iniciar la vista en
directo, grabar vídeos, etc.
Nota
Solo se puede conectar una cámara térmica a la vez de esta forma.
Prepararse para la transmisión
● Conecte la cámara y el PC al mismo segmento red LAN de forma inalámbrica o por

102

<!-- p. 111 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

cable.
Nota
En el caso de una cámara/generador de imágenes portátil, el protocolo DHCP está
habilitado de manera predeterminada, y la dirección IP de la cámara se asigna
automáticamente mediante enrutadores o conmutadores. Vea la dirección IP de la
cámara desde su menú Configuración > Ajustes de dispositivo > Información del
dispositivo.
Para ver y editar la dirección IP de su PC, tomemos Windows10 como ejemplo, vaya a
Configuración > Red e Internet > Estado > Internet conectado > Propiedades.
● Para la cámara activada que se haya conectado al Cliente o a la aplicación móvil a
través de la red, se debe obtener con antelación la contraseña de inicio de sesión
configurada durante la activación de la cámara.
● El controlador WinCap se ha instalado en el PC. Para obtener más información, consulte
Instalacióndelsoftwarey Actualizacióndelsoftware.
Primera conexión de red (cámara no activada)

Figura 7-2 Barra de conexión de red
\1. Haga clic en (1) en la esquina superior izquierda del panel en vivo y seleccione
Conexión de red.
\2. Haga clic en (6) para abrir la lista de cámaras en línea y ver las cámaras
detectadas.
Nota
Si no puede encontrar su cámara en la lista, haga clic en Actualizar (3).
\3. Seleccione la cámara según el modelo y el número de serie y luego haga clic en
Activación.
\4. Introduzca y confirme la contraseña de inicio de sesión según sea necesario.
\5. Haga clic en Configuración avanzada para modificar la Dirección IP, la Máscara de
subred y la Puerta de enlace, o marque Protocolo DHCP para que el enrutador asigne
dinámicamente estos parámetros.
Nota
● Si la activación tiene éxito pero la configuración de Configuración avanzada falla, el
Cliente cambiará automáticamente al modo DHCP para garantizar el acceso a la red.
● Si se requiere una dirección IP fija, puede intentar restablecer el dispositivo y
reactivarlo para configurar parámetros avanzados.

103

<!-- p. 112 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

\6. Haga clic en Activar.
\7. Opcional: Habilite Acceso de red en el dispositivo.

Nota
Para los dispositivos nuevos cuya función de acceso a la red está deshabilitada de
manera predeterminada, cuando el cliente detecta su estado deshabilitado, enviará un
mensaje en pantalla para que habilite la función rápidamente.

\8. Haga clic en Conectar para iniciar la vista en directo.
Conexión rápida a la última cámara conectada
El nombre del modelo (5) de la última cámara conectada se muestra en la barra de
nombre de la cámara. El color del punto (4) indica el estado de la conexión.
● Los puntos verdes significan que la cámara está en línea y se ha conectado
automáticamente. Puede hacer clic en Conectar para iniciar la vista en directo.
● Para ver puntos de otros colores, puede pasar el ratón sobre el nombre del modelo (5)
para ver la dirección IP de la cámara, el nombre del modelo, el número de serie y el
estado de la conexión.
Conectarse a otras cámaras en línea
\1. Abra la lista de cámaras en línea (6).
\2. Seleccione la cámara a la que necesita conectarse y haga clic en Conectar.
\3. Ingrese la contraseña de inicio de sesión y haga clic en Sí para iniciar la vista en
directo.
Nota
● El cliente guarda automáticamente la contraseña de inicio de sesión de la cámara en
función del número de serie. Si la cámara se ha conectado correctamente al cliente
con anterioridad, inicie la vista en directo sin volver a introducir la contraseña.
● El inicio de sesión automático en la cámara no es compatible después de cambiar de
cuenta de ordenador.
● Si olvida su contraseña, haga clic en Olvidé mi contraseña en la ventana emergente
para ver la guía.
Parámetros de red de entrada manual para iniciar sesión en una cámara
activada
\1. Haga clic en (2) para abrir la ventana de conexión manual.
\2. Introduzca la dirección IP, el puerto, el nombre de usuario y la contraseña de la cámara
y haga clic en Sí para iniciar sesión y conectarse a la cámara para la vista en directo.
Nota
Si olvida su contraseña, haga clic en Olvidé mi contraseña en la ventana emergente para

104

<!-- p. 113 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

ver la guía.

7.4 Establecer los parámetros del dispositivo

El cliente puede configurar algunos de los parámetros de la cámara. Los parámetros
disponibles varían según el método de conexión y los modelos de cámara.
Establezca los parámetros de la cámara a la izquierda de la pestaña Directo.
Rango de temperatura
Establezca un Rango de temperatura adecuado para la medición en la izquierda según sus
objetivos. Los rangos admitidos son diferentes en los distintos modelos.
Seleccione Automático si la opción está disponible.
Velocidad de fotogramas del dispositivo
La velocidad de la cámara en tiempo real y la velocidad de renderizado del cliente se
muestran en el área de estado de la cámara a la izquierda.
Puede cambiar la velocidad de fotogramas de la cámara introduciendo un valor en el
campo de texto bajo Velocidad del dispositivo y haciendo clic en Aplicar. Las velocidades
en tiempo real se convierten en números alrededor del valor establecido gradualmente
después de la aplicación correcta.
Nota
● Asegúrese de que la función de configuración de velocidad de fotogramas esté activada
en la cámara. De lo contrario, no se permite cambiar la velocidad de fotogramas del
cliente. Consulte el manual de usuario de su cámara para saber cómo activar la función.
● Evite aplicar la velocidad de fotogramas con frecuencia.
● La velocidad en tiempo real de la cámara mostrada puede ser ligeramente diferente de
la velocidad establecida debido a factores como el estado de la red.
● Se recomienda conectar con un puerto y un cable USB 3.0 si su ordenador y dispositivo
admiten la función. En comparación con USB 2.0, USB 3.0 permite una configuración de
velocidad de fotogramas más alta para garantizar una transmisión más fluida para
determinados modelos de alta resolución IR. Si su cámara admite USB 3.0, siga las
instrucciones del cliente para cambiar el puerto USB.
Calibración manual de la imagen
Debido a sus propias limitaciones, una cámara térmica necesita calibrar la imagen de vez
en cuando para garantizar el efecto de la imagen y la precisión de la medición de la
temperatura. Normalmente, la cámara calibra la imagen automáticamente. También
puede hacer clic en a la izquierda para calibrar la imagen una vez.
Cuando la cámara está en este proceso, aparece en pantalla el mensaje "Calibrando
imagen...".

105

<!-- p. 114 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

Enfoque
La función solo está disponible en las cámaras compatibles con el enfoque automático. El
modo de enfoque disponible varía según los modelos de cámara.
Seleccione un Modo de enfoque en la izquierda y opere siguiendo las instrucciones a
continuación.
Enfoque automático
Enfoque el área central o un área seleccionada por el usuario.
● En este modo, haga clic en Enfoque a la derecha. La cámara enfocará el área central
una vez.
● Haga clic con el botón derecho en cualquier lugar de la imagen y seleccione Enfoque
en el menú contextual. La cámara enfocará el área seleccionada una vez.
● Haga clic con el botón derecho en una herramienta de medición (círculo, elipse,
rectángulo o polígono) en la imagen y seleccione Enfoque en herramienta en el menú
contextual. La cámara enfocará el área de la herramienta una vez.
Enfoque automático continuo
En este modo, la cámara decide el área de enfoque en función de la escena de
observación. Se vuelve a enfocar cuando cambia la escena de observación.
Los usuarios no pueden cambiar el área de enfoque en este modo.
Enfoque asistido por láser
En este modo, haga clic en Enfoque a la derecha. La cámara emitirá un rayo láser para
medir la distancia al área central de la escena. La cámara enfoca con precisión en
función de la distancia.

Precaución
Cuando utilice el enfoque asistido por láser, asegúrese de que no haya ninguna persona
en el área de enfoque para evitar posibles lesiones causadas por la exposición al rayo
láser.

7.5 Capturar imágenes

Durante la visualización en directo, puede capturar imágenes y guardarlas en el ordenador
local.
Nota
● La resolución de la imagen capturada viene determinada por la resolución IR del
dispositivo, por ejemplo, 256×192.
● Debido a la actualización del protocolo, las imágenes capturadas por la versión del
cliente (V1.7.2) o posteriores no se pueden ver ni analizar en versiones anteriores del

106

<!-- p. 115 -->

Manual de usuario de HIKMICRO Analyzer V2.0.1

cliente.
Capturar una instantánea
En la izquierda, haga clic en para capturar imágenes.
Captura programada
\1. Establezca Intervalo entre capturas y Número en Capturas y grabaciones en la
izquierda.
\2. Haga clic en Horario para iniciar la captura.
En el área de estado del dispositivo, a la izquierda, se muestra el estado de captura, el
número de capturas y la cuenta atrás de capturas.
Se detiene cuando se captura el número determinado de imágenes. O haga clic en
Detener para finalizar la programación.
Ver las imágenes capturadas
Vea las imágenes guardadas en la carpeta Capturas en Acceso rápido en Biblioteca.

7.6 Grabar vídeo

Durante la visualización en directo, puede grabar vídeos en formato .hrv y guardarlos en el
ordenador local.
En la izquierda, haga clic en , establezca la velocidad de fotogramas de grabación de
vídeo en la ventana emergente y haga clic en Aceptar para empezar a grabar.
Haga clic en para detener la grabación.
Vea los vídeos guardados en la carpeta Grabaciones en Acceso rápido en Biblioteca.
Nota
● La resolución del vídeo grabado depende de la resolución IR de la cámara.
● Si la función SuperIR está activada en la grabación, el efecto no se guardará en el vídeo
grabado.
● Debido a la actualización del protocolo, los vídeos grabados por la versión del cliente
(V1.7.2 ) o posterior no se pueden reproducir ni analizar en versiones anteriores del
cliente.

107

<!-- p. 116 -->

UD44381B
