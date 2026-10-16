---
type: libro
title: "BIMbasisInfra_infographicA4_1_0.Traducido_v20"
author: "Florkiewicz Martínez, José Ignacio"
categoria: "BIM Y HBIM"
paginas: 2
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/03. BuildingSmart Spain/BIM Basico Infra 1_0.pdf"
convertido: 2026-10-16
---

# BIMbasisInfra_infographicA4_1_0.Traducido_v20

> Texto extraído de `BIM Y HBIM\03. BuildingSmart Spain\BIM Basico Infra 1_0.pdf` (2 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

BIM INFRA BÁSICO

\1. ¿POR QUÉ NECESITAMOS INTERCAMBIAR INFORMACIÓN SIN AMBIGÜEDADES?
Para asegurar y reuƟlizar la información de manera más eﬁciente y efecƟva

HABLAR EL MISMO LENGUAJE ELIMINAR TAREAS INEFICIENTES

\2. ¿CÓMO VAMOS A COMPARTIR ESTA INFORMACIÓN SIN AMBIGÜEDADES?
El conocimiento y las experiencias prácƟcas han demostrado que existe un importante denominador común.
No estamos desarrollando algo nuevo, sino más bien uƟlizando estructuras existentes basadas en estándares abiertos, como IFC, siempre que sea posible

nuevo

nuevo
nuevo
nuevo nuevo
nuevo LandXML IFC

x y z
x

y

z

Consejo: uƟlizar IFC en la medida que sea posible

\3. ¿QUÉ ESTRUCTURA UTILIZAREMOS?
Los acuerdos enumerados a conƟnuación ayudan a garanƟzar que cada parte involucrada siempre podrá
encontrar y proporcionar la información correcta en el lugar correcto.

3.1 NOMBRE DE LOS ARCHIVOS

Asegúrese de uƟlizar un El nombre del archivo estará Entre los campos que Los elementos que
nombre uniforme y compuesto por una serie de componen el nombre del componen el nombre
coherente que permita campos deﬁnidos con una archivo se deben incluir el deben de estar
reconocer el contenido. abreviatura. nombre del proyecto, la fase correctamente separados.
y la disciplina. Consejo: UƟliza guión medio
o bajo como separador.

Ejemplos: Puertos del Estado 2020_SC0010B0001_MOEST01_DiquesVerticales .ifc
Infraestructuras cat XG10021-OE-CO-INS-TramoG-ServiciosAfectados .ifc
Euskal Trenbide Sarea ETS190506-T03-ETS-BIM-TRA-F02-002_V06_A .ifc
Categorías de los campos:

• Identificación y autoría localización y/o zonificación clasificación, descripción y/o autonumérico

1/2 BIM basis Infra - versión 1.0

<!-- p. 2 -->

3.2 UNIDADES DEL PROYECTO 3.3 SISTEMA DE COORDENADAS
UƟlice siempre las mismas unidades. Los Elección del Sistema de Coordenadas:
milímetros y/o metros se acuerdan en el
proyecto. 1. RD Triangulación Nacional 2. Altura (z) relaƟva al 3. En caso de no tener NMMA
Coordenadas NMMA en España deﬁna otro sistema de referencia
29 30 31

30
T 2010 z
m y/o mm 0 (NMMA)
10
S 3020
40 z
R 28 50
60
Ejemplo: nivel inferior
ETRS 89 Husos Consejo: veriﬁca que no hay un sistema local.

3.4 PUNTOS DE REFERENCIA 3.5 DENOMINACIÓN 3.6 CLASIFICACIÓN DE LA INFORMACIÓN
Al inicio del proyecto se debe acordar un Los objetos estarán adecuadamente Los objetos se codiﬁcan mediante el
punto de refencia en la zona del mismo . estructurados y nombrados con lógica. sistema de clasiﬁcación requerido.
El punto de refencia debe ser Consejo: UƟlice signos para la separación del Esta codiﬁcación se registra en
preferiblemente en metros redondeado nombre Ejemplo: (subrayado) _ medatados/propiedades.
a metros.
Nota: UƟliza el siguiente símbolo

clasificación
pilar_as2

Consejo: Asignar los clasiﬁcadores mediante el uso de las
Consejo: No uƟlices sistemas locales enƟdades estándar del esquema IFC adecuadas a tal efecto.

3.7 ESTADO DE LOS OBJETOS 3.8 ASIGNACIÓN DE MATERIALES A
Los objetos reciben automáƟcamente un estado resgistrado en los metadatos/propiedades. LOS OBJETOS
Es decir: nuevo, existente, temporal, descartado y construido (= as built) A los objetos se les asigna un material

Nuevo Asfalto

Construido
Temporal Ejecutado
Existente
Acero

Descartado

3.9 ELEMENTOS EMBEBIDOS 3.10 DUPLICADOS E INTERSECCIONES JUNTOS APRENDEMOS A HABLAR EL
Los objetos deben indicar si corresponden No se permiten elementos duplicados o MISMO IDIOMA
a un elemento embebido a ejecutar intersecciones. Asegúrese de realizar las
"in situ" comprobaciones. Al denominar objetos, considere si el nombre
Nota: El objeƟvo es realizarlo mediante una Consejo: Para evitar duplicación de la información cumple con los siguientes criterios.
clasiﬁcación, si no es posible se hará mediante solo asigne la información de su disciplina Veriİquelo y sepa qué información está
metadatos/propiedades comparƟendo.

Significativa Clara
Comprensible Consistente
Lógica Reconocible

Embebido

2/2 Adaptado por BIM basis Infra - versión 1.0
