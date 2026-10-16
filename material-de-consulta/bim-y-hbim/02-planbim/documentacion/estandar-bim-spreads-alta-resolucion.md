---
type: libro
title: "Estándar BIM_spreads (alta resolución)"
author: ""
categoria: "BIM Y HBIM"
paginas: 77
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/02. Planbim/documentación/Estándar BIM_spreads (alta resolución).pdf"
convertido: 2026-10-16
---

# Estándar BIM_spreads (alta resolución)

> Texto extraído de `BIM Y HBIM\02. Planbim\documentación\Estándar BIM_spreads (alta resolución).pdf` (77 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->



<!-- p. 2 -->

ESTÁNDAR BIM
PARA PROYECTOS PÚBLICOS
Intercambio de Información entre Solicitante y Proveedores

Créditos:
Desarrollo de contenido:
Carolina Soto, Sebastián Manríquez, Paulina Godoy

Corrección de estilo y revisión de contenido:
Carolina Briones, Paola Valenzuela, Karen Gutiérrez,
Bárbara Morales, Raúl Salinas, Antonieta Frávega

Validación de contenido - Comité de Estándar BIM:
Diego Aburto, Felipe Acosta, Ignacio Acuña, Cesar
Ascencio, Dante Avendaño, Luis Bass, Yves Besançon, Rafael
Bombardiere, Reynaldo Cabezas, Esteban Campos, Rodrigo
Carrasco, Álvaro Castro, Cristián Delporte, Carlos Díaz,
Marcos Díaz, Nicolás Espinosa, Diego Fernández, Alberto
Fernández, Tania Godoy, Yasmila Herrera, Rodrigo Herrera,
Errol Holmberg, Yerko Jeria, Eduardo Jiménez, Rodrigo Lam,
Nicole Luppichini, Daniela Mardones, Moisés Martínez,
Gabriela Matta, Francisco Maureira, Esteban Montenegro,
Ignacio Morales, Benjamín Moya, Carlos Moya, Rafael
Novoa, Manuel Núñez, Manuel Ocampo, Felipe Opazo,
Esteban Pérez, Nicolás Posada, Jesús Pulido, Juan Luis
Ramírez, Rodrigo Ramírez, José Riesco, Carlos Riquelme,
Roberto Rojas, Ricardo Rojas, Manuel Saavedra, Felipe
Sabbagh, José Sepúlveda, Felipe Soffia, Mauricio Toledo, Javier
Vallejos, Hugo Vásquez, Patricio Zapata.

Diseño Gráfico:
Kathryn Gillmore, Geraldine Gillmore

Primera edición: junio de 2019
Santiago, Chile

Esta obra está licenciada bajo la Licencia Creative Commons
Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.
org/licenses/by-nc/4.0/.

<!-- p. 3 -->

Contenidos

Índice de tablas.............................................................................................. 8 • Componentes de la Solicitud de Información y del Plan de Ejecución BIM...• 38
Índice de figuras............................................................................................. 8 • 5.1 Objetivos de la utilización de BIM.....................................................• 40
• 5.1.1 Objetivo general....................................................................• 40 Listado de siglas.............................................................................................. 9 5
Prólogo....................................................................................................... 10 • 5.1.2 Objetivos específicos............................................................• 40
Equipo Planbim.............................................................................................. 10 • 5.1.3 Objetivo general y específicos de la utilización •
Comité de Estándar BIM................................................................................. 11 • de BIM en la SDI BIM.............................................................• 40
• 5.1.4 Objetivo general y específicos de la utilización •
• • de BIM en el PEB....................................................................• 41
• Introducción al Estándar...............................................................................• 12 • •
• 1.1 Industria de la construcción en Chile...................................• 14 • 5.2 Entregables BIM.................................................................................• 42
• • • 5.2.1 Entregables BIM en la SDI BIM..............................................• 42 1
• 1.2 ¿Qué es BIM?.........................................................................• 15 • 5.2.2 Entregables BIM en el PEB....................................................• 42
• • • •
• 1.3 ¿Qué es Planbim?..................................................................• 15 • 5.3 Modelos BIM......................................................................................• 43
• • • 5.3.1 Tipos de modelos.................................................................• 43
• 1.4 ¿Qué es un estándar?...........................................................• 16 • 5.3.2 Entidades de modelos BIM....................................................• 44
• • • 5.3.3 Modelos BIM en la SDI BIM....................................................• 46
• 1.5 ¿Por qué es necesario el Estándar BIM • • 5.3.4 Modelos BIM en el PEB..........................................................• 46
• para Proyectos Públicos?.......................................................• 16 • •
• • • 5.4 Documentos relacionados a los modelos BIM.................................• 47
• • • 5.4.1 Documentos relacionados a los modelos BIM en la SDI BIM....• 47
• Objetivo y alcance del Estándar....................................................................• 18 • 5.4.2 Documentos relacionados a los modelos BIM en el PEB.....• 47
• 2.1 Objetivo................................................................................• 20 • •
• • • 5.5 Estados de Avance de la Información de los Modelos (EAIM)............• 48 2
• 2.2 Alineación con estándares internacionales.........................• 21 • 5.5.1 EAIM en la SDI BIM................................................................• 49
• • • 5.5.2 EAIM en el PEB .....................................................................• 51
• 2.3 Alcance y ámbito de acción..................................................• 22 • •
• • • 5.6 Usos BIM............................................................................................• 52
• • • 5.6.1 Definiciones de Usos BIM......................................................• 53
• Términos y definiciones..................................................................................• 24 • 5.6.2 Usos BIM en la SDI BIM.........................................................• 55
• • 5.6.3 Usos BIM en el PEB...............................................................• 55
• • • 3
• Flujos de información BIM.............................................................................• 30 • 5.7 Tipos y Niveles de Información.........................................................• 56
• 4.1 Incorporación de BIM a proyectos públicos..........................• 32 • 5.7.1 Tipos de Información (TDI)...................................................• 56
• • • 5.7.2 Niveles de Información (NDI)...............................................• 60 4
• 4.2 Interoperabilidad..............................................................• 33 • 5.7.3 Tipos y Niveles de Información en la SDI BIM.........................• 66
• • • 5.7.4 Tipos y Niveles de Información en el PEB............................• 66
• 4.3 Trabajo colaborativo..............................................................• 34 • •
• • • 5.8 Estrategia de colaboración................................................................• 67
• 4.4 COBie y Manual Básico de Entrega de Información (MEI)• 34 • 5.8.1 Entorno de Datos Compartidos (CDE)...................................• 67
• 4.4.1 COBie.......................................................................• 34 • 5.8.2 Consolidación de modelos BIM..............................................• 68
• 4.4.2 Manual Básico de Entrega de Información (MEI).........• 34 • 5.8.3 Procedimiento de reuniones................................................• 68
• • • 5.8.4 Estrategia de colaboración en la SDI BIM............................• 68
• 4.5 Solicitud de Información BIM (SDI BIM)...................................• 35 • 5.8.5 Estrategia de colaboración en el PEB...................................• 68
• 4.5.1 Estructura de una Solicitud de Información BIM.....• 35 • •
• • • 5.9 Organización de los modelos BIM.......................................................• 69
• 4.6 Plan de Ejecución BIM (PEB).................................................• 35 • 5.9.1 Estructuración de los modelos BIM.....................................• 69
• 4.6.1 Plan de Ejecución BIM de Oferta...........................• 36 • 5.9.2 Nomenclaturas y codificación.............................................• 69
• 4.6.2 Plan de Ejecución BIM Definitivo.............................• 36 • 5.9.3 Sistemas de clasificación......................................................• 74
• 5.9.4 Organización de los modelos BIM en la SDI BIM................• 74
• 5.9.5 Organización de los modelos BIM en el PEB.......................• 74
•

4 5

<!-- p. 4 -->

Anexo I• Fichas• de1 Usos LevantamientoBIM...................................................................................de condiciones existentes.......................•• 7976 Anexo IV •• Plantilla para Plan de Ejecución BIM de Oferta ......................................• • 122
• 2 Estimación de cantidades y costos....................................• 80 • Introducción..........................................................................................• 126
• 3 Planificación de fases........................................................• 81 • •
• 4 Análisis del cumplimiento • • A Empresas participantes....................................................................• 126
• del programa espacial (zonificación)................................• 82 • •
• 5 Análisis de ubicación........................................................• 83 • B Objetivos y Usos BIM..........................................................................• 127
• 6 Coordinación 3D...............................................................• 84 • B.1 Objetivos de la utilización de BIM en el proyecto.................• 127
• 7 Diseño de especialidades.................................................• 85 • B.2 Usos BIM (PEB de Oferta)......................................................• 128
• 8 Revisión del diseño...........................................................• 86 • B.3 Recursos, capacidades y experiencia previa para cada •
• 9 Análisis estructural...........................................................• 87 Uso BIM requerido..............................................................• 128
• 10 Análisis lumínico...............................................................• 88 • •
• 11 Análisis energético............................................................• 89 • C Entregables BIM y sus formatos.........................................................• 129
• 12 Análisis mecánico.............................................................• 90 • C.1 Modelos BIM solicitados y sus formatos (PEB de Oferta)..........• 129
• 13 Otros análisis de ingeniería..............................................• 91 • C.2 Estado de Avance de la Información de los Modelos BIM•
• 14 Evaluación de sustentabilidad..........................................• 92 • para cada entrega...............................................................• 130
• 15 Validación normativa........................................................• 93 • C.3 Documentos solicitados y sus formatos (PEB de Oferta)....• 131
• 16 Planificación de obra.......................................................• 94 • •
• 17 Diseño de sistemas constructivos.....................................• 95 • D Estrategia de colaboración..............................................................• 132
• 18 Fabricación digital............................................................• 96 • D.1 Entorno de Datos Compartidos (CDE)................................• 132
• 19 Control de obra................................................................• 97 • D.2 Consolidación de modelos BIM...........................................• 132
• 20 Modelación as-built.........................................................• 98 • •
• 21 Gestión de activos............................................................• 99 • •
• 22 Análisis de sistemas..........................................................• 100 • Plantilla para Plan de Ejecución BIM Definitivo..........................................• 134 Anexo V • 23 Mantenimiento preventivo...............................................• 101 • •
• 24 Gestión y seguimiento de espacios..................................• 102 • Introducción..........................................................................................• 138
• 25 Planificación y gestión de emergencias............................• 103 • •
• • • A Empresas participantes ............................................................• 138
• • • •
Anexo II• Matriz• de1 RolesContextoBIM...................................................................................de la definición Roles y responsabilidades••BIM 104106 • B• ObjetivosB.1 Objetivosy Usos BIM........................................................................de la utilización de BIM en el proyecto.................•• 139139
• 2 ¿Qué es un Rol BIM?..........................................................• 107 • B.2 Usos BIM (PEB Definitivo).....................................................• 140
• 3 ¿Qué definen los Roles BIM?...........................................• 107 • B.3 Recursos, capacidades y experiencia previa para cada •
• 4 ¿Por qué necesitamos una definición • • Uso BIM requerido..............................................................• 140
• de Roles BIM para la industria?..........................................• 107 • •
• 5 ¿Cómo se utiliza la Matriz de Roles BIM?........................• 108 • C Entregables BIM y sus formatos.......................................................• 141
• 6 Acciones, responsabilidades y experiencia previa • • C.1 Modelos BIM solicitados y sus formatos (PEB Definitivo)......• 141
• para cada Rol BIM..............................................................• 109 • C.2 Estado de Avance de la Información de los Modelos•
• 7 Matriz de Roles BIM...........................................................• 110 • BIM para cada entrega.......................................................• 142
• • • C.3 Documentos solicitados y sus formatos (PEB Definitivo)......• 143
• • • •
Anexo III• Manual Básico de Entrega de Información (MEI)......................................• 118 • D• EstrategiaD.1 Entornode colaboración..............................................................de Datos Compartidos (CDE)..................................•• 144144
• D.2 Consolidación de modelos BIM............................................• 144
• D.3 Procedimiento de reuniones (solo PEB Definitivo)................• 145
• •
• E Organización de los modelos BIM.......................................................• 146
• E.1 Estructuración de los modelos BIM (solo PEB Definitivo)......• 146
• E.2 Nombres de archivos de los modelos BIM (solo PEB Definitivo)• 147
• E.3 Colores de disciplinas y sistemas (solo PEB Definitivo)..........• 148
• E.4 Sistema de clasificación (solo PEB Definitivo)......................• 149
• •
• •
• Bibliografía..........................................................................................• 150
6 7

<!-- p. 5 -->

Índice de tablas Listado de siglas

Tabla 01 Estándares internacionales relacionados ........................................................................ 21 AICE: Asociación de Ingenieros Civiles Estructurales
Tabla 02 Tipos de modelos BIM ...................................................................................................... 43 AB: As-Built
Tabla 03 Entidades mínimas para cada tipo de modelo BIM............................................................. 44 AOA: Asociación de Oficinas de Arquitectura
Tabla 04 Estados de Avance de la Información de los Modelos....................................................... 48 BAS: Building Automation System
Tabla 05 Modelos BIM que se pueden requerir según Estado de Avance de la Información............. 50 BCF: BIM Collaboration Format
Tabla 06 Usos BIM.......................................................................................................................... 52 BIM: Building Information Modeling
Tabla 07 Tipos de Información por cada Uso BIM........................................................................... 58 CAPJ: Corporación Administrativa del Poder Judicial
Tabla 08 Niveles de Información..................................................................................................... 61 CChC: Cámara Chilena de la Construcción
Tabla 09 Niveles de Información por Tipo de Información.............................................................. 62 CC: Coordinación de Construcción
Tabla 10 Niveles de Información por Estados de Avance de la Información de los Modelos............ 64 CDT: Corporación Desarrollo Tecnológico
Tabla 11 Nombres de archivos y carpetas....................................................................................... 70 CM: Construcción, Manufactura y Montaje
Tabla 12 Códigos de documentos................................................................................................... 71 CMMS: Computerized Maintenance Management System
Tabla 13 Códigos y colores por disciplina o sistema........................................................................ 73 COBie: Construction Operations Building information exchange
DA: Diseño de Anteproyecto
Tabla Roles 01 Acciones, responsabilidades y experiencia previa para cada Rol BIM...................... 109 DB: Diseño Básico
Tabla Roles 02 Matriz de Roles BIM................................................................................................ 110 DC: Diseño Conceptual
DD: Diseño de Detalle
Formulario 01 PEB de Oferta Empresas participantes................................................................... 126 DGAC: Dirección General de Aeronáutica Civil
Formulario 02 PEB de Oferta Objetivo general de la utilización de BIM en el proyecto............... 127 EAIM: Estado de Avance de la Información de los Modelos
Formulario 03 PEB de Oferta Objetivos específicos de la utilización de BIM en el proyecto........ 127 GIS: Geographic Information System (Sistema de Información Geográfica)
Formulario 04 PEB de Oferta Usos BIM......................................................................................... 128 GM: Gestión y Mantenimiento del Activo
Formulario 05 PEB de Oferta Modelos BIM solicitados y sus formatos......................................... 129 IDM: Information Delivery Manual
Formulario 06 PEB de Oferta EAIM para cada entrega.................................................................. 130 IFC: Industry Foundation Class
Formulario 07 PEB de Oferta Documentos solicitados y sus formatos......................................... 131 IFD: International Framework for Dictionaries
Formulario 08 PEB de Oferta Entorno de Datos Compartidos..................................................... 132 MDS: Ministerio de Desarrollo Social
Formulario 09 PEB de Oferta Generación de modelos BIM.......................................................... 132 MEI: Manual Básico de Entrega de Información (MEI)
MINEDUC: Ministerio de Educación
Formulario 01 PEB Definitivo Empresas participantes.................................................................. 138 MINSAL: Ministerio de Salud
Formulario 02 PEB Definitivo Objetivo general de la utilización de BIM en el proyecto................ 139 MINVU: Ministerio de Vivienda y Urbanismo
Formulario 03 PEB Definitivo Objetivos específicos de la utilización de BIM en el proyecto....... 139 MOP: Ministerio de Obras Públicas
Formulario 04 PEB Definitivo Usos BIM......................................................................................... 140 MVD: Model View Definition
Formulario 05 PEB Definitivo Modelos BIM solicitados y sus formatos.......................................... 141 MTT: Ministerio de Transportes y Telecomunicaciones
Formulario 06 PEB Definitivo EAIM para cada entrega.................................................................. 142 NDI: Nivel de Información
Formulario 07 PEB Definitivo Documentos solicitados y sus formatos.......................................... 143 PDI: Policía de Investigaciones de Chile
Formulario 08 PEB Definitivo Entorno de Datos Compartidos..................................................... 144 PEB: Plan de Ejecución BIM
Formulario 09 PEB Definitivo Generación de modelos BIM......................................................... 144 PM: Puesta en Marcha
Formulario 10 PEB Definitivo Procedimiento de reuniones.......................................................... 145 SDI: Solicitud de Información
Formulario 11 PEB Definitivo Estructuración de los modelos BIM................................................ 146 TDI: Tipo de Información
Formulario 12 PEB Definitivo Nombre de archivos de los modelos BIM....................................... 147 TI: Tecnologías de la Información
Formulario 13 PEB Definitivo Colores de disciplinas y sistemas .................................................... 148
Formulario 14 PEB Definitivo Sistema de clasificación................................................................. 149

Índice de figuras

Figura 1 Ámbito de acción del Estándar......................................................................................... 23
Figura 2 Plan de Ejecución BIM de los Proveedores Oferentes y del Proveedor Adjudicado............ 33
Figura 3 Documentos relacionados a los modelos BIM................................................................. 47
Figura 4 Ejemplo de entregas con modelos en distintos Estados de Avance de la Información...... 51
Figura 5 Simultaneidad de distintos NDI de las entidades en un modelo BIM.................................. 60
Figura 6 Ejemplo de definición de capacidad BIM según Rol ........................................................ 108

8 9

<!-- p. 6 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS

Prólogo Comité de Estándar BIM
El Estándar BIM para Proyectos Públicos fue desarrollado por Planbim de Corfo y su publicación se Las organizaciones que participaron en el desarrollo del presente estándar y sus respectivos
realizó en junio de 2019. representantes se listan a continuación.

El documento se construyó a partir del levantamiento y estudio de normativas, estándares y protocolos
BIM internacionales, y la recopilación de información sobre proyectos públicos nacionales, realizado
por el equipo de Planbim. Este trabajo se materializó en un primer borrador que fue puesto a disposición Listado de participantes de las mesas de discusión del presente Estándar
de un comité multisectorial, el Comité de Estándar BIM, que sesionó entre enero y diciembre de 2018
para el análisis y discusión de su contenido. Entre enero y marzo de 2019 el documento, validado por el SECTOR PÚBLICO SECTOR PRIVADO
comité, fue puesto a disposición de la industria para su discusión, a través de una consulta pública. Las
observaciones recogidas en ese período fueron analizadas y sancionadas por el mismo comité. CAPJ Manuel Ocampo AICE Cristián Delporte
Nicole Luppichini
El Estándar BIM para Proyectos Públicos fue desarrollado gracias al financiamiento del Ministerio DGAC Benjamín Moya
de Economía, Fomento y Turismo; Ministerio de Obras Públicas; Ministerio de Vivienda y Urbanismo MDS Carlos Riquelme AOA Felipe Sabbagh
y Corfo. Felipe Soffia Hugo Vásquez
Yves Besançon
MINEDUC Dante Avendaño
ARQZ-BIM Eduardo Jiménez Esteban Montenegro
Equipo Planbim Tania Go doy BIM Forum Manuel Saavedra
Carolina Soto, Directora Ejecutiva MINSAL Diego Aburto BIM Studio Nicolás Posada
Sebastián Manríquez, Coordinador de Instituciones Públicas Diego Fernández CC+RR José Riesco Carolina Briones, Coordinadora de Capital Humano y Sector Privado Ignacio Morales Moisés Martínez Paola Valenzuela, Planificación y Control de Gestión
MINVU Yasmila Herrera Raúl Salinas, Gestor de Procesos CChC Luis Bass
Yerko Je ria Bárbara Morales, Ejecutiva de Apoyo Estratégico Felipe Opazo
Paulina Godoy, Ejecutiva de Tecnologías MOP Carlos Díaz CDT Javier Vallejos
Antonieta Frávega, Ejecutiva de Procesos Rafael Novoa Roberto Rojas
Reynaldo Cabezas
Colegio de Marcos Díaz
MTT Carlos Moya Constructores
Daniela Mardones Civiles e Ing.
Esteban Pérez Constructores
PDI Rodrigo Carrasco Colegio de Juan Luis Ramírez
Planbim Nicolás Espinosa Arquitectos
Francisco Maureira Colegio de Álvaro Castro
Ingenieros Errol Holmberg
Manuel Núñez
SECTOR ACADEMIA Construsoft Ignacio Acuña
José Sepúlveda
PuntoLab Esteban Campos
COPSA Rodrigo Ramírez
Universidad Mauricio Toledo
Andrés Bello Geocom Rafael Bombardiere
Rodrigo Lam
Universidad Alberto Fernández
de Chile Gepro Gabriela Matta
Universidad Jesús Pulido Graphisoft Patricio Zapata
del Biobío IBIM Cesar Ascencio
Microgeo Rodrigo Herrera
SimiosLab Ricardo Rojas
VPA Ing. Felipe Acosta
Estructural

10 11

<!-- p. 7 -->

• •
• 1.1 Industria de la construcción en Chile.............................................• 14
• •
• 1.2 ¿Qué es BIM?...................................................................................• 15
• •
• 1.3 ¿Qué es Planbim?............................................................................• 15
• •
• 1.4 ¿Qué es un estándar?......................................................................• 16
• •
• 1.5 ¿Por qué es necesario el Estándar BIM para Proyectos Públicos?.........• 16
•

Introducción al Estándar1

12 13

<!-- p. 8 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS INTRODUCCIÓN AL ESTÁNDAR
1.1

Aporte de la Construcción en la economía chilena Empleos que aporta la Construcción en Chile

7.2% 10.6%

1.2 ¿Qué es BIM?
BIM (Building Information Modeling) es un conjunto de metodologías, tecnologías y estándares que
Industria de la construcción permiten diseñar, construir y operar una edificación o infraestructura de forma colaborativa en un espacio virtual4. Es decir, por una parte, las tecnologías permiten generar y gestionar información
en Chile mediante modelos a lo largo del ciclo de vida de un proyecto. Por otra parte, las metodologías,
basadas en estándares, permiten compartir esta información de manera estructurada entre todos los La industria de la construcción representa una
actores involucrados, fomentando el trabajo colaborativo e interdisciplinario, agregando así, valor a los parte importante de la economía chilena, ya que
procesos de la industria. BIM viene a replantear la forma tradicional de trabajo individual y fragmentado, aporta un 7,2 % del producto interno bruto1 y un
proponiendo una metodología de trabajo colaborativo. Esta metodología pone en el centro de interés 10,6 % de los empleos nacionales, es decir, más
la generación de información concisa de un proyecto y el intercambio fluido de ésta entre los diferentes 1 de 870 mil empleos2. Sin embargo, a pesar de actores involucrados a lo largo de todo el ciclo de vida de un proyecto. su relevancia, presenta una baja productividad.
Dos estudios de McKinsey3 que comparan la
productividad laboral de Chile con la de Estados 1.3 ¿Qué es Planbim? Introducción Unidos, medida en metros cuadrados construidos
por hora hombre, demuestran que ésta bajó de un Con la finalidad de incrementar la productividad y sustentabilidad de la industria de la construcción
55 % en 2007 a un 48 % en 2011. Las razones dadas mediante la incorporación de procesos, metodologías y tecnologías de información y comunicaciones
para esta baja productividad por dichos estudios que promuevan su modernización a lo largo de todo el ciclo de vida de las obras, el 2016 se creó Planbim. al Estándar
son, entre otras, la baja adopción de métodos Éste es un programa a 10 años impulsado por Corfo que surgió en el marco del Programa Estratégico
avanzados de gestión, la fragmentación de las etapas de Productividad y Construcción Sustentable, Construye 2025, y, desde 2017, está alojado en el Comité
y actores del proceso de diseño, construcción de Transformación Digital de Corfo. Planbim busca reducir los costos y plazos de los procesos de
y operación, la falta de estandarización, el bajo construcción de proyectos públicos y hacer más eficiente la operación de esta infraestructura. Para
uso de materiales prefabricados y la falta de lograr esto, Planbim tiene como una de sus metas la utilización de la metodología BIM para el desarrollo
capacitación de los trabajadores. y operación de proyectos de edificación e infraestructura pública al año 2020.

El proceso de implementación de BIM se está materializando a través de un trabajo coordinado y gradual
con distintas instituciones públicas. Este trabajo se inició a partir de un convenio de colaboración al cual
adhirieron las siguientes instituciones:

• Ministerio de Economía, Fomento y Turismo • Corfo
• Ministerio de Hacienda • Cámara Chilena de la Construcción
• Ministerio de Obras Públicas • Instituto de la Construcción
• Ministerio de Vivienda y Urbanismo • Corporación Administrativa del Poder Judicial
• Ministerio de Desarrollo Social • Codelco
• Ministerio de Salud • Servicio de Registro Civil e Identificación
• Ministerio de Educación • Carabineros de Chile
• Ministerio del Interior y Seguridad Pública • Policía de Investigaciones de Chile
• Ministeio de Transportes y Telecomunicaciones • Dirección General de Aeronáutica Civil
1  Banco Central, Memoria Anual, 2017
2  IALE Estudio de Identificación de Demanda de Capital Humano con
Capacidades BIM en la Industria de la Construcción. Estudio, Santiago,
2017
3  McKinsey&Company, Productividad Laboral en Chile ¿Cómo esta-
mos? Presentación IRADE, 28-11-2013 4  Basado en la definición de BIM Dictionary, https://bimdictionary.com/en/building-information-modelling/1/
14 15

<!-- p. 9 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS

El trabajo con estas instituciones se enfoca en la implementación de BIM en sus procesos, la capacitación de
sus equipos, la generación del presente estándar BIM y la construcción de requerimientos estandarizados
para los proyectos de edificación e infraestructura pública (Solicitud de Información BIM). Con esto se
busca, entre otras cosas, facilitar la participación de las empresas en las licitaciones y obtener información
precisa de los proyectos que entregue mejores herramientas para la toma de decisiones.

Adicionalmente al trabajo con las instituciones públicas, Planbim trabaja con el sector académico y
privado, incentivando, por una parte, la integración y actualización de contenidos BIM en los programas
de capacitación y mallas curriculares y, por otra, difundiendo los usos y beneficios de estas metodologías
de trabajo. Se espera que estos sectores respondan al requerimiento público, brindando servicios,
habilitando tecnologías y capacitando a la fuerza laboral.

1.4 ¿Qué es un estándar?
La International Organization for Standardization (ISO) indica que un estándar es un:

Documento, establecido por consenso y aprobado por un organismo reconocido, que entrega, para
usos comunes y repetidos, reglas y directrices o características para actividades o sus resultados,
ayudando a la obtención de un grado óptimo de ordenamiento en un contexto dado5.

1.5 ¿Por qué es necesario el Estándar BIM para proyectos públicos?
Se busca generar un requerimiento de BIM desde el Estado que sea consistente y transversal, es decir,
que todas las instituciones públicas que exijan BIM lo hagan de una manera estandarizada y conocida
por todos los actores involucrados en el proyecto. El objetivo de esto es facilitar la implementación
de BIM tanto para las empresas privadas como las instituciones públicas. Por una parte, las empresas
tendrán certeza de que la exigencia de BIM de las distintas instituciones públicas siempre será clara y
estandarizada, independiente de quien sea el Solicitante. Esto permitirá que la implementación de BIM
dentro de cada empresa sea más simple, y facilitará su participación en proyectos públicos. Por otra
parte, para las instituciones públicas que exigen BIM, o quieran hacerlo en el futuro, el estándar ayudará
a que cada organización inicie su requerimiento desde una base consensuada existente.

5  ISO/IEC Guide 2 - Standardization and related activities - General Vocabulary, 2004.
16 17

<!-- p. 10 -->

• 2.1 Objetivo....................................................................................• 20
• •
• 2.2 Alineación con estándares internacionales......................................• 21
• •
• 2.3 Alcance y ámbito de acción.............................................................• 22
2
Objetivo y alcance
del Estándar

18 19

<!-- p. 11 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS OBJETIVO Y ALCANCE DEL ESTÁNDAR
2.2

2.2 Alineación con estándares internacionales

El presente estándar se alinea con los requerimientos mínimos para el intercambio de información BIM
establecidos en los diferentes estándares internacionales. A su vez, incorpora mayor detalle respecto de
cómo debe ser entregada la información a través de la definición de, por ejemplo, Nivel de Información,
Tipo de Información, Usos de BIM, etc. Todas estas definiciones están basadas en estándares y
convenciones internacionales que se referencian en cada uno de los puntos correspondientes.

Tabla 01. Estándares internacionales relacionados
En la siguiente tabla se indican los estándares internacionales utilizados en el presente documento:

Tipo Nombre Estándar Descripción

IDM ISO 29481-1: 2016
Describe procesos
Information Delivery Manual ISO 29481-2: 2012
2.1 Objetivo IFC ISO 16739-1:2018 Transporta información / datos Industry Foundation Class
Este estándar ha sido elaborado para garantizar BCF
buildingSMART BCF Cambios para la Coordinación
que la información compartida en el marco BIM Collaboration Format
de los proyectos públicos de edificación e Base tecnológica IFD ISO 12006-3: 2007
infraestructura sea suficiente, consistente, de International Framework for buildingSMART Data Diccionario de términos
buena calidad e interoperable. Se busca, a través Dictionaries Dictionary
de esto, en conjunto con diversas acciones del 2 MVD Traduce procesos en requisitos
sector privado y público, lograr un aumento de la Model View Definition buildingSMART MVD técnicos
productividad y sustentabilidad de la industria de
COBie la construcción. Transporta información / datos Construction Operations Building BS 1192-4: 2014 Objetivos y para operación information exchange

ISO BIM 1
Organization of information about
Describe los conceptos y alcance del construction works. Information ISO19650-1: 2018
principios de BIM
management using building
information modelling
General Estándar ISO BIM 2
Organization of information about
Describe la fase de entrega de los
construction works. Information ISO19650-2: 2018
activos
management using building
information modelling

Project Building Information AIA Document G202- Define cinco Niveles de
Protocol Form 2013 Desarrollo (LOD)

Level of Development
Define seis Niveles de Desarrollo
Level of Development Specification Specification BIM
LOD
Forum USA

Project Execution Planning Guide BIM Planning at Penn
Define veinticinco Usos BIM
version 2.1 State

Matriz de Elementos/Objetos del US
Base de Veterans Affairs VA BIM Guide Define Tipos de Información para
Conceptos Define Tipos de Información para VA BIM Guide cada Entidad
cada Entidad

BIM Basic Information Define 12 pasos para
Manual Básico de Entrega de
Delivery Manual - intercambiar información de
Información (MEI)
version 1.0 manera estructurada

Collaborative production of
Define las convenciones de
architectural, engineering and
BS 1192:2007 nomenclaturas de archivos y
construction information - code of
carpetas
practice

Elaborada por Planbim20 21

<!-- p. 12 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS OBJETIVO Y ALCANCE DEL ESTÁNDAR
2.3

La tabla anterior muestra dos tipos de estándares que se describen a continuación.

Base tecnológica: Se tomaron como referencia siete documentos y/o formatos internacionales que
estandarizan los procesos, los datos y el diccionario de estos datos. Estos estándares dan a los software
BIM una estructura clara para el traspaso de la información con una visión global del diseño, ejecución
y operación de edificios e infraestructura. Esto permite flujos de trabajo de información abiertos,
llamados openBIM.

General: Las dos normas internacionales utilizadas incluyen recomendaciones generales de cómo administrar,
intercambiar, registrar, controlar y organizar la información que se aborda en el desarrollo de edificación e
infraestructura por parte de los todos los actores del proyecto. Esto genera un marco global que propicia la
internacionalización, tanto en la exportación como importación, de servicios relacionados.

Base de Conceptos: Se tomaron como referencia cinco documentos y/o protocolos internacionales que
establecen los conceptos claves que permiten al Estándar BIM definir los requerimientos mínimos para el
intercambio de información BIM, generando un lenguaje global común sobre los temas técnicos de BIM.

2.3 Alcance y ámbito de acción

El presente estándar aplica a proyectos públicos de diversa complejidad, independiente de su tipología
o envergadura, a lo largo de todo su ciclo de vida.

Su foco principal es el intercambio de información entre el Solicitante y los Proveedores, que pueden
ser Proveedores Oferentes - en la etapa de licitación - o Proveedor Adjudicado - durante el desarrollo
del proyecto. El estándar también aborda el flujo entre el Proveedor y las empresas que le prestan
servicios para el desarrollo del proyecto a través del Plan de Ejecución BIM (4.6), ya que en este Plan el
Proveedor debe entregar información acerca de los responsables de los proyectos, tanto dentro de su
empresa como de otras empresas participantes.

El Estándar BIM para Proyectos Públicos incluye convenciones respecto de la información geométrica y
no geométrica que debe ser intercambiada en un proyecto público entre el Solicitante y los Proveedores.
Además, se establece, como requerimiento mínimo, la incorporación de la información establecida en
los parámetros de COBie (4.4.1) y del Manual Básico de Entrega de Información, MEI (4.4.2.) en los
modelos BIM.

El público objetivo de este documento son tanto las instituciones públicas que regulan, licitan y/o
mandatan proyectos a otras instituciones, como las empresas privadas que prestan servicios en el
contexto de esos proyectos.

Si bien el presente estándar ha sido desarrollado para proyectos públicos, podría ser utilizado como
guía de referencia para proyectos privados, procurando analizar previamente si su contenido se ajusta
a las características y objetivos del proyecto.

Figura 1. Ámbito de acción del estándar

Elaborada por Planbim

22 23

<!-- p. 13 -->

3
Términos y definiciones

24 25

<!-- p. 14 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS TÉRMINOS Y DEFINICIONES
3

3.7 COBie (Construction Operations Building information exchange)
Estándar internacional que define las expectativas para el intercambio de información a lo largo del
ciclo de vida de una edificación o infraestructura¹⁰.

3.8 Estado de Avance de la Información de los Modelos (EAIM)
Distintos grados consecutivos de desarrollo de la información del proyecto.

3.9 Entidad2
Elemento virtual que representa un objeto físico o abstracto de construcción¹¹.

3.10 Entorno de Datos Compartidos (CDE, por sus siglas en inglés)
Fuente única de información para recopilar, gestionar y difundir documentos y modelos para equipos
multidisciplinarios, a través de un proceso estandarizado. Un CDE generalmente contiene un sistema
de gestión documental que facilita la transferencia de información entre los actores de un proyecto¹².

En el contexto del presente estándar, se aplican 3.11 Entregable BIM
los siguientes términos y definiciones: Documentos e información necesaria para la obtención de modelos BIM, así como todos los productos
resultantes del uso de herramientas y flujos de trabajo BIM.
3.1 Activo 1
Edificación o infraestructura una vez construida. 3.12 IFC (Industry Foundation Class)
Esquema de base de datos ampliable que representa información de la construcción para el intercambio
3.2 Actor entre distintos software para arquitectura, ingeniería y construcción¹³. 3 Organización, unidad organizacional o persona
involucrada en uno o más procesos del ciclo de 3.13 Interoperabilidad
vida del proyecto6. Capacidad de un producto o sistema para trabajar con otros productos o sistemas, [...] existentes o Términos y futuros, sin restricción de acceso o implementación¹⁴.
3.3 As-built
Registro del proyecto tal como se ha construido 3.14 Manual Básico de Entrega de Información (MEI)
realmente en el lugar, incluyendo los cambios de Guía de doce pasos a realizar en los modelos BIM, que permiten compartir e intercambiar información de definiciones
diseño ocurridos en el curso del trabajo. manera estructurada durante todo el ciclo de vida de la edificaciones e infraestructuras, considerando
la utilización de estándares openBIM¹⁵.
3.4 Building Information Modeling (BIM)
Conjunto de metodologías, tecnologías y 3.15 Modelo BIM federado
estándares que permiten diseñar, construir y Modelo creado a partir de información contenida en archivos separados. Esta información puede
operar una edificación o infraestructura de forma provenir de distintos actores¹⁶.
colaborativa en un espacio virtual7.
3.16 Modelo BIM integrado
3.5 Ciclo de vida Modelo compuesto por la información de las distintas disciplinas del proyecto, contenida en una única
Conjunto de etapas o fases por las que atraviesa base de datos.
una edificación o infraestructura desde la idea y
definición de sus requerimientos hasta el fin de 3.17 Nivel de Información (NDI)3
su uso⁸. Grados de profundidad que puede tener tanto la información geométrica como no geométrica
contenida en las entidades de los modelos BIM, según el Estado de Avance de la Información de los
3.6 Cliente Modelos en que se requiera.
Actor responsable de iniciar un proyecto y/o
aprobar las entregas9.

6 Basado en ISO19650-1:2018; 3.2.1, modificado. 10 BS 1192-4:2014.
7 Basado en la definición de Bilal Succar, https://bimdictionary.com/ 11 Basado en la definición de Bilal Succar, BIM Dictionary, modificado. https://bimdictionary.com/es/model-component/1/
en/building-information-modelling/1/ , modificado. 12 Bilal Succar, https://bimdictionary.com/en/common-data-environment/1/
8 Basado en ISO19650-1.2:2018; 3.2.10, modificado. 13 Chuck Eastman and others. BIM Handbook: A Guide to Building Information Modeling for Owners, Managers, Designers, Engineers and Contractors,
9 Basado en ISO19650-1:2018; 3.2.5, modificado. 2nd Edition.(2011), 114.
14 Asociación Francófona de Usuarios de Software Libre AFUL https://aful.org/gdt/interop
15 BIM Loket. https://www.bimloket.nl/BIMbasicIDM
16 Basado en ISO 19650-1:2018 3.3.11 y 3.3.12, modificado.
26 27

<!-- p. 15 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS TÉRMINOS Y DEFINICIONES
3

3.18 openBIM
Enfoque universal para el diseño, ejecución y operación de edificios basados en estándares y flujos
de trabajo abiertos. openBIM es una iniciativa de buildingSMART y de varios proveedores de software
líderes que utilizan el modelo de datos abierto de esa misma organización¹⁷.

3.19 Plan de Ejecución BIM (PEB)
Documento elaborado por el Proveedor que define cómo serán llevados a cabo los aspectos de
modelado y gestión de la información¹⁸.

3.20 Proveedor
Actor que entrega información referente a trabajos, bienes o servicios¹⁹.
Nota: El Proveedor puede ser Oferente, cuando presenta una propuesta técnica y/o económica en el
marco de una licitación, o Adjudicado, cuando ya es designado para realizar el desarrollo del proyecto.

3.21 Rol BIM
Función que se ejerce en alguna etapa del desarrollo y operación de un proyecto de edificación o
infraestructura, en base a capacidades BIM que se suman a las capacidades no referidas a BIM.

3.22 Solicitante
Actor que recibe la información de trabajos, bienes o servicios desde el Proveedor²⁰.
Nota: En algunos casos el Solicitante es a la vez el Cliente (3.6) del proyecto, mientras que en otros el
Solicitante actúa en representación del Cliente.

3.23 Solicitud de Información BIM (SDI BIM)
Documento que define por qué y para qué se utilizará BIM en un proyecto. Una Solicitud de Información
BIM puede ser denominada de diversas formas según la organización, por ejemplo, términos de
referencia BIM, bases administrativas, entre otras.

3.24 Tipo de Información BIM (TDI) 4
Grupo de datos que pueden estar contenidos en los modelos.

3.25 Uso BIM
Método de aplicación de BIM durante el ciclo de vida de una edificación o infraestructura para alcanzar
uno o más objetivos específicos²¹.

17  buildingSMART, https://www.buildingsmart.org/standards/technical-vision/
18 Basado en ISO19650-2:2018; 3.1.3.1, modificado.
19 ISO19650-1:2018; 3.2.3.
20 ISO19650-1:2018; 3.2.4.
21 Ralph G. Kreider and John I. Messner. The uses of BIM: Classifying and Selecting BIM Uses, Versión 0.9. (The Pennsylvania State University, 2013), 6.
28 2929

<!-- p. 16 -->

• 4.1 Incorporación de BIM a Proyectos Públicos...................................• 32
• •
• 4.2 Interoperabilidad..........................................................................• 33
• •
• 4.3 Trabajo colaborativo.........................................................................• 34
• •
• 4.4 COBie y Manual Básico de Entrega de Información (MEI)....................• 34
• 4.4.1 COBie...............................................................................• 34
• 4.4.2 Manual Básico de Entrega de Información (MEI)..................• 34
• •
• 4.5 Solicitud de Información BIM (SDI BIM)............................................• 35
• 4.5.1 Estructura de una Solicitud de Información BIM...............• 35
• •
• 4.6 Plan de Ejecución BIM (PEB).............................................................• 35
• 4.6.1 Plan de Ejecución BIM de Oferta........................................• 36 4 • 4.6.2 Plan de Ejecución BIM Definitivo o de Contrato................• 36
•
Flujos de información BIM

30 31

<!-- p. 17 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS FLUJOS DE INFORMACIÓN BIM
4.2

4.2 Interoperabilidad1
Interoperabilidad es la “capacidad de un producto o sistema para trabajar con otros productos o
sistemas, [...] existentes o futuros, sin restricción de acceso o implementación”²².

En el caso del presente estándar, la interoperabilidad es clave ya que permite al Estado:

• Mantener la transparencia y probidad. El Estado no debe solicitar el uso de una marca en
particular de software BIM.
• Fomentar la competencia y el aumento de proveedores de soluciones tecnológicas.
• Integrar la información proveniente de BIM con la información de otros software que pueden
ser o no desarrollos propios de las instituciones públicas.
• Asegurar la usabilidad de los datos en todo el ciclo de vida de los proyectos. El Estado
necesita información organizada que pueda ser usada en el futuro para la operación y
posibles remodelaciones, por lo que es clave que la disponibilidad de la información no esté
supeditada a la disponibilidad de una marca específica de software.
4.1 Incorporación de BIM a
proyectos públicos
BIM se incorpora en los requerimientos para
proyectos públicos con el fin de disminuir los
problemas en el ámbito de la construcción
mencionados en el punto 1.1. En este contexto,
BIM no modifica estructuralmente el flujo de 4
información dentro del proyecto, sino que se
utiliza para asegurar la suficiencia, consistencia,
calidad e interoperabilidad de la información Flujos de intercambiada durante el desarrollo de éste. Con
esto, se busca apoyar el proceso de cumplimiento
de la rentabilidad social de los proyectos y la información eficiencia en el uso de los recursos del Estado. PEB Oferta PEB Deﬁnitivo

Durante las diversas etapas de los proyectos
públicos se generan uno o más intercambios BIM de información entre el Solicitante y los
Proveedores. Para poder definir cómo se realizará
ese intercambio de información a través de
BIM, el Solicitante debe generar una Solicitud
de Información BIM y los Proveedores deben
responder a ésta a través de uno o más Planes de
Ejecución BIM, entre otros documentos (Figura 2). Licitación Contrato
El intercambio de modelos BIM entre el Solicitante
y los Proveedores se debe realizar a través de
formatos abiertos, en una lógica de openBIM.

Figura 2. Plan de Ejecución BIM de los Proveedores Oferentes y del Proveedor Adjudicado

Elaborada por Planbim

22 Asociación Francófona de Usuarios de Software Libre AFUL https://aful.org/gdt/interop
32 33

<!-- p. 18 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS FLUJOS DE INFORMACIÓN BIM
4.5

4.3 Trabajo colaborativo 4.5 Solicitud de Información BIM (SDI BIM)
El trabajo colaborativo es el proceso de desarrollo de un proyecto de edificación o infraestructura en En el marco del presente estándar, la Solicitud de Información BIM, o SDI BIM, se entiende como un
el cual todos los actores involucrados se enfocan en obtener beneficios compartidos de las tareas que documento que define por qué y para qué se utilizará BIM en un proyecto. El documento debe indicar
se realizan durante el ciclo de vida. Esto apunta a que la generación de información sea coordinada de manera formal y explícita los entregables BIM y la información que debe estar contenida en ellos.
independiente del proceso o la forma de contrato. Este documento es generado por el Solicitante y debe ser entregado a él o los Proveedores Oferentes
que pueden ser externos, por ejemplo, consultores y/o contratistas en el marco de una licitación, o
Para lograr el trabajo colaborativo es necesario que los distintos actores del proyecto generen equipos internos encargados de ciertas tareas del proyecto.
información utilizando procesos estandarizados y métodos de comunicación establecidos que
garanticen la calidad. La Solicitud de Información BIM puede actuar como complemento o anexo a una solicitud de información
mayor (bases de licitación, términos de referencia, documentos de llamados de subsidios, etc.) y debe
requerir la información siguiendo lo indicado en el presente estándar.
4.4 COBie y Manual Básico de Entrega de Información (MEI)1
4.5.1 Estructura de una Solicitud de Información BIM
4.4.1 COBie
Los aspectos mínimos que debe incorporar una Solicitud de Información BIM son:
COBie, por sus siglas en inglés Construction Operations Building information exchange, es un estándar
internacional desarrollado en 2007 por el Army Corps of Engineers de Estados Unidos. • Objetivo General y Objetivos Específicos (5.1)
• Usos, Tipos de Información y Niveles de Información BIM requeridos (5.6 y 5.7) Este estándar:
• Entregables (5.2)
define las expectativas para el intercambio de información a lo largo del ciclo de vida de
una edificación o infraestructura. El uso de COBie garantiza que la información se pueda • Estrategia de Colaboración (5.8)
preparar y utilizar sin la necesidad de conocer las aplicaciones o bases de datos de envío y • Organización de los modelos (5.9)
recepción. Asegura que el intercambio de información pueda ser revisado y validado para su
cumplimiento, continuidad e integridad.²³
4.6 Plan de Ejecución BIM (PEB) En el presente estándar, los parámetros COBie forman parte del conjunto mínimo de datos a requerir
por el Solicitante (ver Matriz de Información de Entidades²⁴). El esquema de intercambio de información El Plan de Ejecución BIM, o PEB, es un documento que debe generar cada Proveedor y que, a partir de
COBie, permitirá administrar los datos necesarios del edificio o infraestructura en sus distintas etapas los aspectos incorporados en la SDI BIM (4.5.1), se debe enfocar en:
durante el ciclo de vida. Estos datos pueden referirse a recintos y espacios, listas de equipos, hojas de
• Definir el proceso de ejecución del modelado y gestión de información del proyecto datos de productos, garantías, listados de repuestos y programas de mantenimiento, entre otros. El
uso de este esquema tiene como objetivo la mejora en la gestión de la operación y mantenimiento de • Especificar los procedimientos de intercambio de información, con sus responsables
las edificaciones e infraestructura pública. respectivos
• Establecer la infraestructura tecnológica y las competencias que tiene el Proveedor para el
4.4.2 Manual Básico de Entrega de Información (MEI)²⁵ desarrollo del modelado de información en el proyecto
Este manual es una guía de doce pasos a realizar en los modelos BIM, que permiten compartir e Con esto, se facilita la gestión de la entrega de información del proyecto
intercambiar información de manera estructurada durante todo el ciclo de vida de una edificación o En el caso de un proyecto que se inicia con una licitación deben existir dos PEB, un PEB de Oferta
infraestructura, considerando la utilización de estándares openBIM. Este documento fue desarrollado para la etapa de licitación, que debe ser presentado por todos los Proveedores Oferentes, y un PEB
por un grupo de empresas del sector de la construcción de los Países Bajos, en conjunto con BIM Loket Definitivo que realizará el Proveedor que se adjudique la licitación (Proveedor Adjudicado). En este
y buildingSMART Benelux²⁶, ambas instituciones sin fines de lucro. segundo PEB se debe actualizar y dar mayor detalle de la información presentada en el PEB de Oferta.
Este manual permite asegurar la disponibilidad y posible reutilización de la información de los modelos En el caso de un proyecto que inicia con un Proveedor Adjudicado ya definido, éste último solo debe
BIM de manera eficiente y es utilizado en el Estándar BIM para Proyectos Públicos como parte del conjunto generar el PEB Definitivo.
mínimo de datos a solicitar por las instituciones públicas, para garantizar entregables BIM de calidad.
Se adjuntan plantillas para el desarrollo de estos PEB en los anexos IV y V de este estándar.
Para más información del MEI, ver Anexo III y la Matriz de Información de Entidades²⁷.

23 BS 1192-4:2014. Collaborative production of information - Part 4: Fulfilling employer’s information exchange requirements using COBie - Code
of practice (The British Standard Institution, 2014), 1.
24 https://planbim.cl/biblioteca/documentos/
25 Con licencia de Creative Commons BY-SA 4.0, de BIM Loket. https://www.bimloket.nl/BIMbasicIDM
26 Bélgica, Holanda y Luxemburgo
27 https://planbim.cl/biblioteca/documentos/
34 35

<!-- p. 19 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS

4.6.1 Plan de Ejecución BIM de Oferta
El PEB de Oferta debe incorporar, entre otra información, los siguientes puntos:

• Información básica del proyecto

• Objetivos de la utilización de BIM en el proyecto

• Usos BIM en conjunto con la infraestructura tecnológica y competencias del equipo para
desarrollarlos

• Empresas participantes del proyecto con sus responsables

• Entregables generales y sus formatos en concordancia con el programa del proyecto

• Estrategia general de colaboración

4.6.2 Plan de Ejecución BIM Definitivo
El PEB Definitivo debe tomar como base el PEB de Oferta, en caso de que exista. El PEB Definitivo
debe ser complementado a medida que avanza el proyecto para reflejar el desarrollo y posibles
modificaciones de éste. Al finalizar el proyecto, este documento debe reflejar todos los cambios
implementados en su desarrollo.

El PEB Definitivo debe entregar información detallada en los siguientes aspectos:

• Información básica del proyecto
• Objetivos de la utilización de BIM en el proyecto
• Usos BIM en conjunto con la infraestructura tecnológica y competencias del equipo para
desarrollarlos
• Empresas y personas participantes del proyecto con sus Roles BIM
• Entregables específicos y sus formatos en concordancia con el programa del proyecto
• Estrategia y plataformas de colaboración
• Estándares y convenciones a utilizar respecto de nomenclatura, clasificación, unidades de
medidas, coordenadas, estructuración de los modelos (niveles definidos, volúmenes, etc.)
y otros

36 37

<!-- p. 20 -->

• Componentes de la Solicitud de Información y del Plan de Ejecución BIM....• 38
• 5.1 Objetivos de la utilización de BIM.....................................................• 40
• 5.1.1 Objetivo general....................................................................• 40
• 5.1.2 Objetivos específicos............................................................• 40
• 5.1.3 Objetivo general y específicos de la utilización de BIM en la SDI• BIM 40
• 5.1.4 Objetivo general y específicos de la utilización de BIM en el •PEB 41
• •
• 5.2 Entregables BIM.................................................................................• 42
• 5.2.1 Entregables BIM en la SDI BIM..............................................• 42
• 5.2.2 Entregables BIM en el PEB ....................................................• 42
• •
• 5.3 Modelos BIM.......................................................................................• 43
• 5.3.1 Tipos de modelos..................................................................• 43
• 5.3.2 Entidades de modelos BIM...................................................• 44
• 5.3.3 Modelos BIM en la SDI BIM....................................................• 46 5 • 5.3.4 Modelos BIM en el PEB..........................................................• 46
• •
• 5.4 Documentos relacionados a los modelos BIM...................................• 47
• 5.4.1 Documentos relacionados a los modelos BIM en la SDI BIM.....• 47
• 5.4.2 Documentos relacionados a los modelos BIM en el PEB..........• 47 Componentes de la • •
• 5.5 Estados de Avance de la Información de los Modelos (EAIM)...............• 48
• 5.5.1 EAIM en la SDI BIM................................................................• 49
• 5.5.2 EAIM en el PEB...........................................................................• 51 Solicitud de Información y
• •
• 5.6 Usos BIM.............................................................................................• 52
• 5.6.1 Definiciones de Usos BIM.....................................................• 53 del Plan de Ejecución BIM • 5.6.2 Usos BIM en la SDI BIM..........................................................• 55
• 5.6.3 Usos BIM en el PEB...............................................................• 55
• •
• 5.7 Tipos y Niveles de Información..........................................................• 56
• 5.7.1 Tipos de Información (TDI)....................................................• 56
• 5.7.2 Niveles de Información (NDI)................................................• 60
• 5.7.3 Tipos y Niveles de Información en la SDI BIM.......................• 66
• 5.7.4 Tipos y Niveles de Información en el PEB............................• 66
• •
• 5.8 Estrategia de colaboración...............................................................• 67
• 5.8.1 Entorno de Datos Compartidos (CDE)....................................• 67
• 5.8.2 Consolidación de modelos BIM.............................................• 68
• 5.8.3 Procedimiento de reuniones...............................................• 68
• 5.8.4 Estrategia de colaboración en la SDI BIM..............................• 68
• 5.8.5 Estrategia de colaboración en el PEB...................................• 68
• •
• 5.9 Organización de los modelos BIM......................................................• 69
• 5.9.1 Estructuración de los modelos BIM.....................................• 69
• 5.9.2 Nomenclaturas y codificación...............................................• 69
• 5.9.3 Sistemas de clasificación......................................................• 74
• 5.9.4 Organización de los modelos BIM en la SDI BIM....................• 74
• 5.9.5 Organización de los modelos BIM en el PEB.........................• 74
•

38 39

<!-- p. 21 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.1

La SDI BIM es un documento que define
por qué y para qué se utilizará BIM en
un proyecto. El PEB es un documento
elaborado por el Proveedor que define
cómo serán llevados a cabo los aspectos
de modelado y gestión de la información.

5.1 Objetivos de la utilización Ejemplo de objetivo general:
de BIM El objetivo general de la utilización de BIM es prevenir errores o modificaciones críticas sobre el
Para la correcta aplicación de la metodología BIM cronograma y presupuesto aprobado.
en el marco de un proyecto, es clave que existan
Ejemplo de objetivos específicos: previamente objetivos claros definidos para su
utilización. • Obtener las cantidades y costos de componentes del proyecto 5 • Asegurar el cumplimiento de los requerimientos programáticos
5.1.1 Objetivo general • Facilitar la colaboración y comunicación de los actores involucrados
Se entenderá por objetivo general de la utilización • Prevenir conflictos críticos entre las distintas especialidades Componentes de BIM la meta principal que se quiere alcanzar
a través del uso de esta metodología en un
proyecto determinado. Este objetivo no se refiere 5.1.4 Objetivo general y específicos de la utilización de BIM en el PEB de la a la meta de la institución sino del proyecto en
Tanto en el PEB de Oferta como en el PEB Definitivo, los Proveedores deben indicar los objetivos BIM particular, sin embargo, en algunos casos podrían
del proyecto, establecidos en la SDI BIM, correlacionándolos con los Usos BIM que se utilizarán para coincidir. El objetivo general debe ser claro,
cumplirlos. Para esto se incorporan los formularios de la sección B.1, en las plantillas de PEB de Oferta Solicitud de conciso, alcanzable en los plazos definidos con y PEB Definitivo. Estas plantillas se adjuntan en los anexos IV y V de este estándar. los recursos disponibles y debe estar orientado a
resultados concretos. Información
5.1.2 Objetivos específicos y del Plan de Los objetivos específicos de la utilización de
BIM en el proyecto son metas enfocadas a
tareas medibles que apuntan a responder a los
problemas concretos del mismo. Estas metas Ejecución BIM
pueden ser más de una y siempre deben estar
alineadas al objetivo general de la solicitud de BIM
en el proyecto.

5.1.3 Objetivo general y específicos de
la utilización de BIM en la SDI BIM
La Solicitud de Información BIM debe indicar
claramente y de manera diferenciada el objetivo
general y los objetivos específicos de la utilización
de BIM en el proyecto. Los Entregables (5.2) y
Usos BIM (5.6) solicitados en la SDI BIM deben
concordar con estos objetivos.
40 41

<!-- p. 22 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.3

5.2 Entregables BIM 5.3 Modelos BIM1
Se entenderá por Entregables BIM todos los documentos e información necesaria para la obtención de “Un modelo BIM es una representación digital tridimensional (3D) basada en entidades, rica en
modelos BIM, así como todos los productos resultantes del uso de herramientas y flujos de trabajo BIM. datos, creada por un actor del proyecto utilizando una herramienta de software BIM”²⁸. En el marco
del presente estándar, se entenderá que un modelo BIM puede generarse y/o gestionarse durante
cualquier etapa de ciclo de vida.
5.2.1 Entregables BIM en la SDI BIM
La Solicitud de Información BIM debe establecer claramente los entregables BIM, indicando, para cada 5.3.1 Tipos de modelos uno, sus formatos y soportes de entrega.
Existen diferentes tipos de modelos BIM, que pueden ser generados por distintos actores durante el
Estos entregables deben incluir como mínimo: ciclo de vida del proyecto.

• Plan de Ejecución BIM: PEB de Oferta y/o Definitivo dependiendo de la modalidad del
proyecto (4.6) Tabla 02. Tipos de modelos BIM
• Modelos BIM: Se debe definir específicamente cuáles modelos se solicitan (5.3) En la siguiente tabla se muestran nueve tipos de modelos BIM que se pueden generar para proyectos
• Documentos relacionados a los modelos (5.4) de edificación o infraestructura, según corresponda:
Dentro de la Solicitud de Información BIM se debe aclarar si se agregan entregables no especificados
Modelo BIM Edificación Infraestructura en otros términos de referencia del mismo proyecto.

Para especificar y delimitar la información que debe ser intercambiada a través de los entregables, a lo Sitio
largo del proyecto, se debe utilizar, dentro de la solicitud, cuatro conceptos:

• Usos BIM (5.6)
• Estados de Avance de la Información de los Modelos (5.5) Volumétrico
• Tipos de Información (TDI) (5.7.1.)
• Niveles de Información (NDI) (5.7.2.) Arquitectura
o Diseño de Infraestructura

5.2.2 Entregables BIM en el PEB
Tanto en el PEB de Oferta como en el Definitivo, los Proveedores deben señalar los Entregables Estructura
BIM, indicando, para cada uno, sus responsables y formatos, entre otra información. Para esto, se
incorporan los formularios de la sección C en las plantillas de PEB de Oferta y PEB Definitivo, además
de los formularios de la sección E en el PEB Definitivo. Estas plantillas se adjuntan en los anexos IV y V Mecánico Eléctrico Sanitario
de este estándar. (MEP por sus siglas en inglés)

Coordinación (**)

Construcción (***)

As-Built

Operación

(**): El modelo de coordinación debe ser realizado a través de la consolidación de, al menos, los modelos de arquitectura o diseño de infraes-
tructura, estructura y MEP. Esta consolidación debe realizarse por medio de modelos federados o integrados según lo indicado en el punto 5.8.2
(***): El modelo de construcción podrá considerar la utilización de otros de los nueve tipos de modelos. Esta consolidación debe realizarse por
medio de modelos federados o integrados según lo indicado en el punto 5.8.2
Elaborada por Planbim
28 Bilal Succar. BIM Dictonary, https://bimdictionary.com/es/bimmodel/1/
42 43

<!-- p. 23 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.3

5.3.2 Entidades de modelos BIM1
“Una entidad de modelo es un elemento virtual que representa un objeto físico o abstracto de
construcción, que puede ser o no paramétrico, tanto en 2D como 3D”²⁹.

Tabla 03. Entidades mínimas para cada tipo de modelo BIM : Elemento requerido, según el tipo de modelo. : Elemento sugerido, según el tipo de modelo.
(**): El modelo de coordinación debe ser realizado a través de la consolidación de al menos los modelos de arquitectura o diseño de infraestructura, estructura
En la siguiente tabla se indican algunas de las entidades mínimas requeridas en cada tipo de modelo de y MEP. Esta consolidación debe realizarse por medio de modelos federados o integrados según lo indicado en el punto 5.8.2.
información. La descripción de IFC de cada entidad se puede encontrar en la norma ISO 16739-1:2018 (***): El modelo de construcción podrá considerar la utilización de otros de los nueve tipos de modelos. Esta consolidación debe realizarse por medio de
y en el documento Matriz de Información de Entidades, disponible en repositorio digital de Planbim³⁰. modelos federados o integrados según lo indicado en el punto 5.8.2.

–
/ MEP - MEP ifcStair
–
Acabados y Tuberías
y Techumbre / CirculaciónRampas Especiales Tableros Civiles Geográficos / de/ Instalacionese Espacios Radier / / Cortina Falsos Ejes (IfcGrid) Terreno (IfcSite) Elementos (IfcCivilElement) Elementos (IfcGeographicElement) Fundaciones (IfcFooting) Zonas (IfcSpace-IfcZone) Columnas (IfcColumn) Vigas (IfcBeam) Losas (IfcSlab) Muros (IfcWall) Muros (IfcCurtainWall) Ventanas (IfcWindow) Puertas (IfcDoor) Cubiertas (IfcRoof) Cielos (IfcCovering) SistemasEscaleras (IfcTransportElement IfcRamp) Equipos (IfcSanitayTerminal- IfcMedicalDevice-IfcLamp) Muebles (IfcFurniture- IfcSystemFurnitureElement) Estructuras (IfcElementAssembly) Equipamiento (IfcEnergyConversionDevice IfcDistributionControlElement) Distribución (IfcDistributionFlowElement)
Entidades Modelos BIM

Sitio

Volumétrico

Arquitectura
o Diseño de
Infraestructura

Estructura

MEP

Coordinación
(**)

Construcción
(***)

As-Built

Operación

29 Bilal Succar. BIM Dictonary. https://bimdictionay.com/es/model-component/1/ Elaborada por Planbim, basada en la Matriz de elementos/objetos del US Veterans Affairs y en la norma ISO 16739-1:2018
30  https://planbim.cl/biblioteca/documentos/
44 45

<!-- p. 24 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.4

5.3.3 Modelos BIM en la SDI BIM1 5.4 Documentos relacionados a los modelos BIM
La SDI BIM debe indicar claramente cuáles, de los nueve modelos que se indican en el punto 5.3.1 se En el presente estándar se entenderá por Documentos relacionados a los modelos BIM tanto los
requieren para el desarrollo del proyecto. archivos que pueden ser extraídos directamente desde los modelos BIM en distintos formatos - por
ejemplo, planos, planillas, especificaciones técnicas, imágenes, videos, etc. - como los documentos de
Para garantizar la factibilidad de uso de la información de los modelos BIM en todo el ciclo de vida estos apoyo al desarrollo del proyecto y los modelos – por ejemplo, fichas técnicas, catálogos, nubes de punto,
deben ser entregados en un formato que permita la reutilización de la información incluso fuera del etc. (Figura 3).
software BIM utilizado para su creación. Por esto la SDI BIM debe requerir los modelos en:

• formato IFC 2x3 (mínimo) 5.4.1 Documentos relacionados a los modelos BIM en la SDI BIM
• formato LandXML³¹ en caso de que corresponda La Solicitud de Información BIM debe definir claramente los documentos requeridos.
• formato nativo de los software BIM de autoría
La SDI BIM debe solicitar que los archivos IFC sean exportados utilizando el o los Model View Definition 5.4.2 Documentos relacionados a los modelos BIM en el PEB
(MVD) correspondiente a la etapa de entrega del proyecto.
Tanto en el PEB de Oferta como en el Definitivo, los Proveedores deben indicar todos los documentos a
entregar, declarando el formato y versión a utilizar para cada uno. Para esto se incorporan los formularios
5.3.4 Modelos BIM en el PEB de la sección C.3 en las plantillas de PEB de Oferta y PEB Definitivo. Estas plantillas se adjuntan en los
anexos IV y V de este estándar.
Tanto en el PEB de Oferta como en el Definitivo, los Proveedores deben indicar todos los modelos a
entregar, declarando el formato y versión a utilizar para cada uno. Para esto se incorporan los formularios
de las secciones C.1 y C.2 en las plantillas de PEB de Oferta y PEB Definitivo. Estas plantillas se adjuntan
en los anexos IV y V de este estándar.

Los Proveedores deben asegurar que la información requerida en la SDI BIM ha sido exportada en los
archivos IFC utilizando el o los Model View Definition (MVD) correspondientes a la etapa de entrega
del proyecto.
Documentos de apoyo Documentos extraídos
al desarrollo de los modelos BIM de los modelos BIM

Figura 3. Documentos relacionados a los modelos BIM

Elaborada por Planbim
31 http://www.landxml.org/
46 47

<!-- p. 25 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.5

5.5 Estados de Avance de la Información de los Modelos (EAIM) 5.5.1 Estados de Avance de la Información de los Modelos en la SDI BIM
Los Estados de Avance de la Información son las distintas fases consecutivas de definición de los datos La Solicitud de Información BIM debe definir las entregas del proyecto, indicando, para cada una, en
contenidos en los modelos BIM, y están vinculados directamente al progreso en el tiempo del proyecto. cuál Estado de Avance de la Información se deben entregar los modelos. Un Estado puede tener una
En el marco del presente estándar se han definido nueve EAIM, uno en etapa de Planificación, tres en o más entregas.
Diseño, tres en Construcción y dos en Operación. Estos Estados delimitan los Niveles de Información Los Estados de Avance de la Información de los Modelos dependen del grado de desarrollo del
(NDI) que deben contener los entregables. Para más información sobre NDI, ver 5.7.2. proyecto. Por ejemplo, en la etapa de diseño, cuando se está desarrollando el Anteproyecto (DA) o el
Diseño de Detalle (DD), no se puede requerir el Modelo de Construcción o el Modelo de Operación, ya
Tabla 04. Estados de Avance de la Información de los Modelos que la información para su desarrollo aún no existe.
En la siguiente tabla se indican los diferentes Estados Avance de la Información de los Modelos:

de
DC Fase inicial del proceso de diseño, en la cual a partir de las especificaciones, requisitos
Diseño y necesidades del Solicitante, se establece el conjunto de tareas necesarias para
Conceptual obtener una solución al problema planteado. InformaciónPlanificación

DA Fase temprana del proceso de diseño, en la que se establecen los criterios generales
Diseño de de un proyecto, considerando los requerimientos y restricciones del Solicitante, tales
Anteproyecto como normativos y legales.
Diseño
de DB Fase en la que se preparan los criterios y especificaciones generales de los sistemas
que considera el proyecto.
Información Diseño Básico
Fase en la que se elabora la documentación específica de cada elemento del proyecto,
DD mediante una descripción completa de la información necesaria para la fabricación
Diseño de Detalle
y/o construcción de éstos.

CC Fase en la que se planifica el conjunto de actividades a ejecutar de un trabajo de
Coordinación de construcción, ordenándolo de la manera más eficiente posible y planificando todas
Construcción las acciones para su ejecución.

CM Construcción Construcción, Fase de ejecución de las actividades planificadas en el terreno o fuera de él (off-site),
de Manufactura y que da inicio a las tareas de fabricación, tanto manuales como industrializadas.
Información Montaje Fase en la que se registra el proyecto tal como se ha construido realmente en el lugar,
AB incluyendo los cambios de diseño ocurridos en el curso del trabajo. En esta fase se
As-Built
realiza la entrega de la información de la construcción, concluyendo el contrato de ésta.

Fase en la que se llevan a cabo las actividades de traspaso del activo al cliente,
incluyendo también la información para el uso de ésta como por ejemplo, las garantías
PM de los equipos instalados. Esta información sirve también para el desarrollo de
Puesta en Marcha Operación eventuales proyectos de remodelación o ampliación. Esta fase considera las pruebas
de de funcionamiento del activo.

GM Fase en la que se ejecutan las tareas de mantenimiento de acuerdo al programa
Gestión y de servicios del activo. Esto incluye las actividades enumeradas en la estrategia Información Mantenimiento del de traspaso, la evaluación posterior a la ocupación y la revisión de desempeño del
Activo proyecto.

Elaborada por Planbim
Nota: Los nombres de los EAIM podrán variar según las definiciones del Solicitante.48 4949

<!-- p. 26 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.5

Tabla 05. Modelos BIM que se pueden requerir según Estado de Avance de la Información Es importante aclarar que una entrega puede incorporar modelos en distintos Estados de Avance. Por
ejemplo, como se muestra en el siguiente cuadro, en una primera entrega la SDI BIM podría requerir En la siguiente tabla se indica cuáles son los tipos de modelos BIM que pueden ser requeridos en cada EAIM
sólo el modelo de arquitectura en Estado de Diseño de Anteproyecto. Luego, en la segunda entrega
ese modelo podría solicitarse en Estado de Diseño Básico, mientras que el modelo de Estructura, que
de comienza a desarrollarse posteriormente al de arquitectura, podría entregarse en Estado de Diseño
de Anteproyecto. En la tercera entrega los modelos de arquitectura y estructura podrían estar en un
Estado de Diseño Básico, y sin embargo los modelos MEP, al ser modelos que se inician después que los Diseño Sitio Volumétrico ArquitecturaoInfraestructura Estructura MEP Coordinación Construcción As-Built Operación anteriores, podrían estar recién en Estado de Diseño de Anteproyecto (Figura 4).
BIM

Modelos BIM Modelos EAIM
Modelo de Modelo de Modelo de
de Arquitectura Estructura MEP
DC
Diseño
Conceptual
01 DA Diseño de Anteproyecto InformaciónPlanificación

DA
Diseño de 02 DB Diseño Básico DA Diseño de Anteproyecto Anteproyecto
Diseño
de DB 03 DB Diseño Básico DB Diseño Básico DA Diseño de Anteproyecto
Diseño Básico Entregas
Información
04 DD Diseño de Detalle DB Diseño Básico DB Diseño Básico DD
Diseño de
Detalle
05 DD Diseño de Detalle DD Diseño de Detalle DD Diseño de Detalle
CC
Coordinación
de
Construcción Figura 4. Ejemplo de entregas con modelos en distintos Estados de Avance de la Información

CM Elaborada por Planbim Construcción Construcción,
de Manufactura y
Montaje

5.5.2 Estados de Avance de la Información de los Modelos en el PEB Información
AB
Tanto en el PEB de Oferta como en el Definitivo, los Proveedores deben incorporar información acerca As-Built
de, por ejemplo, los entregables y sus formatos, para cada Estado de Avance de la Información de los
Modelos. Para esto, se incorporan los formularios de las secciones C.2 y C.3 en las plantillas de PEB de
Oferta y PEB Definitivo. Estas plantillas se adjuntan en los anexos IV y V de este estándar. PM
Puesta en
Marcha Operación
de
GM
Gestión y
Mantenimiento Información
del Activo

Elaborada por Planbim
50 51

<!-- p. 27 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.6

5.6 Usos BIM1 5.6.1 Definiciones de Usos BIM
Los Usos BIM son “métodos de aplicación de BIM durante el ciclo de vida de una edificación o A continuación, se presentan las definiciones de los veinticinco Usos BIM. Para más información acerca
infraestructura para alcanzar uno o más objetivos específicos”³². Estos usos sirven para explicar las de los recursos sugeridos, las competencias necesarias y los Tipos de Información (TDI) aplicables a
diferentes formas en que las partes interesadas del proyecto pueden utilizar BIM. cada uno de éstos Usos, ver fichas en Anexo I.

En el ámbito internacional, existen distintos documentos de definición de Usos BIM. Las definiciones 1. Levantamiento de condiciones existentes: Proceso de desarrollo de uno o más modelos BIM
incorporadas en el presente estándar están basadas en el documento Building Information Modeling considerando las condiciones actuales de un sitio y/o sus instalaciones y/o un área específica dentro
Project Execution Planning Guide, de la Universidad del Penn State, en Estados Unidos, que determina de una edificación o infraestructura. Este modelo se puede desarrollar de múltiples maneras, por
veinticinco Usos BIM. ejemplo, a partir de escaneo láser o técnicas de topografía convencionales. Una vez que se construye
el modelo, éste se puede consultar para obtener información, ya sea para una nueva construcción o un
En la siguiente tabla se muestran los Usos BIM: proyecto de remodelación y/o ampliación.

\2. Estimación de cantidades y costos: Proceso de utilización de la información de uno o más modelos
BIM para extraer cantidades de componentes y materiales del proyecto y, en base a esta información, Tabla 06. Usos BIM el costo de un proyecto en sus distintas etapas, siendo más eficiente desarrollarlo desde las etapas
tempranas. Esto permite prevenir posibles costos y tiempos adicionales por errores y/o modificaciones
al proyecto.
PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN
\3. Planificación de fases: Proceso de utilización de uno o más modelos 4D (3D + tiempo) para planear la
\1. Levantamiento de condiciones existentes secuencia constructiva de un proyecto y/o las etapas de ocupación en una remodelación o ampliación
de una edificación o infraestructura.
\2. Estimación de cantidades y costos
\3. Planificación de fases 4. Análisis del cumplimiento del programa espacial (zonificación): Proceso de utilización de uno o
\4. Análisis del cumplimiento del programa espacial (zonificación) más modelos BIM para evaluar si el diseño cumple de manera eficiente y exacta con las áreas incluidas
\5. Análisis de ubicación en los requerimientos del proyecto, tomando en cuenta las regulaciones y normas establecidas.

\6. Coordinación 3D 5. Análisis de ubicación: Proceso de utilización de uno o más modelos BIM y/o GIS para evaluar las
\7. Diseño de especialidades propiedades de un área y determinar la mejor localización y orientación de un futuro proyecto.

\8. Revisión de diseño
\6. Coordinación 3D: Proceso de planificación entre las distintas disciplinas previo al diseño para evitar
\9. Análisis estructural posibles interferencias. Este Uso BIM incluye además la detección de interferencias una vez generados
\10. Análisis lumínico los diseños de las disciplinas a través de uno o más modelos BIM.
\11. Análisis energético
\7. Diseño de especialidades: Proceso de creación de uno o más modelos BIM de las distintas disciplinas
\12. Análisis mecánico
de un proyecto. El Diseño de especialidades es un paso clave para incorporar la información a una base
\13. Otros análisis de ingeniería de datos inteligente de la cual se pueden extraer propiedades, cantidades, costos, programación, etc.
\14. Evaluación de sustentabilidad
\15. Validación normativa 8. Revisión del diseño: Proceso de revisión de las posibles respuestas a los requerimientos del proyecto
respecto de áreas, diseño espacial, iluminación, seguridad, confort, acústica, materialidad, colores, etc.,
\16. Planificación de obra
mediante la creación de uno o más modelos BIM que pueden contener múltiples alternativas de diseño.
\17. Diseño sistemas constructivos
\18. Fabricación Digital 9. Análisis estructural: Proceso de análisis para determinar el comportamiento de un sistema
\19. Control de obra estructural a través de uno o más modelos BIM. En base a este análisis, se desarrolla y ajusta el diseño
para crear sistemas estructurales eficientes que cumplan con la normativa vigente. Esta información se 20. Modelación as-Built
utilizará en las fases de diseño y construcción.
\21. Gestión de activos
\22. Análisis de sistemas 10. Análisis lumínico: Proceso para determinar el comportamiento de un sistema de iluminación a
\23. Mantenimiento preventivo través de uno o más modelos BIM. Esto puede incluir iluminación artificial (interior y exterior) y natural
(iluminación solar y sombra). En base a este análisis, se desarrolla y ajusta el diseño para crear sistemas 24. Gest. y seguimiento de espacios
de iluminación eficientes. Este análisis permite simulaciones que pueden mejorar significativamente el
\25. Plan. y gestión de emergencias diseño y el rendimiento de la iluminación a lo largo de su ciclo de vida.
Basada en Project Execution Planning Guide version 2.1, mayo 2011
\11. Análisis energético: Proceso de evaluación de un proyecto a través de uno o más modelos BIM, en
base a criterios energéticos, que pueden incluir materiales, desempeños y/o procesos. Esta evaluación
energética puede ser realizada en todas las etapas del ciclo de vida, sin embargo, es más efectiva cuando
se realiza en la fase de diseño para luego ser aplicada en la etapa de construcción y operación del proyecto.

32  Ralph G. Kreider and John I. Messner. The uses of BIM: Classifying and Selecting BIM Uses, Versión 0.9. (The Pennsylvania State University, 2013), 6
52 53

<!-- p. 28 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.6

\12. Análisis mecánico: Proceso de análisis y evaluación de ingeniería de los sistemas mecánicos, basado 24. Gestión y seguimiento de espacios: Proceso de administración de los espacios y recursos
en las especificaciones de diseño para los sistemas del proyecto, a través de uno o más modelos BIM. relacionados a éstos dentro de una edificación o infraestructura, a través de uno o más modelos BIM
que permiten al equipo de administración analizar el uso del espacio y planificar posibles cambios. Esto
\13. Otros análisis de ingeniería: Proceso para determinar el método de ingeniería no tradicional es particularmente útil en la remodelación o ampliación de un proyecto durante la cual los espacios e
más pertinente basado en las especificaciones de diseño, a través de uno o más modelos BIM. Las instalaciones deben permanecer ocupados y en funcionamiento.
herramientas de análisis y simulaciones de rendimiento pueden mejorar significativamente el diseño de
las instalaciones y su consumo de energía durante todo el ciclo de vida. 25. Planificación y gestión de emergencias: Proceso en el cual se accede a la información crítica
de la edificación o infraestructura a través de uno o más modelos BIM, con el propósito de mejorar
\14. Evaluación de sustentabilidad: Proceso en el que un proyecto se evalúa en base a criterios de la eficiencia de respuesta ante una emergencia y minimizar los riesgos de seguridad. La información
sustentabilidad a través de uno o más modelos BIM. Este proceso debe ocurrir durante todas las dinámica del activo es proporcionada por un BAS (por sus siglas en inglés, Building Automation System),
etapas de la vida de un proyecto, incluida la planificación, el diseño, la construcción y la operación. mientras que la información de la edificación estática, como planos de planta y esquemas de equipos,
La aplicación de criterios sustentables a un proyecto en las fases de planificación y diseño temprano reside en el o los modelos BIM. El BIM junto con el BAS pueden mostrar claramente dónde se localiza la
mejoran la capacidad de impactar en la eficiencia del diseño y la planificación. emergencia dentro del edificio, las posibles rutas hacia el área y cualquier otro lugar en riesgo dentro
del activo. 15. Validación normativa. Proceso de revisión del cumplimiento de códigos y normas que aplican al
proyecto a través de uno o más modelos BIM.
5.6.2 Usos BIM en la SDI BIM 16. Planificación de obra: Proceso en el cual se utiliza uno o más modelos BIM para planificar, de manera
gráfica, las actividades vinculadas a los elementos existentes, temporales y propuestos de un proyecto La Solicitud de Información BIM debe definir claramente cuáles de los veinticinco Usos BIM se requieren.
durante su construcción. Esto puede incluir el costo de mano de obra y los materiales, entre otros puntos. Estos deben estar alineados a los objetivos definidos por el Solicitante.
\17. Diseño de sistemas constructivos: Proceso de diseño y análisis de la ejecución de sistemas de Existe una directa relación entre la cantidad de usos solicitados y la cantidad de recursos necesarios
construcción complementarios (por ejemplo, soportes temporales, acristalamientos, etc.) para para generar los modelos. Además, existen usos que demandan mayores recursos que otros. Por
optimizar su planificación a través de uno o más modelos BIM. esto, es importante acotar cuáles Usos BIM son necesarios y asegurarse de que, a través de éstos, el
Proveedor Adjudicado realmente pueda lograr los objetivos propuestos en la SDI BIM.
\18. Fabricación digital: Proceso que utiliza información de uno o más modelos BIM para facilitar la
fabricación de componentes de construcción o ensamblajes. Algunos usos de la fabricación digital se
pueden ver, por ejemplo, en la fabricación de chapas metálicas, fabricación de acero estructural, corte 5.6.3 Usos BIM en el PEB
de tuberías, creación de prototipos para revisiones de intención de diseño, etc. La información de los
modelos ayuda a asegurar la precisión, así como también la reducción de desperdicios en la fase de Tanto en el PEB de Oferta como en el Definitivo, los Proveedores deben indicar los Usos BIM que
fabricación. se utilizarán para cumplir los objetivos del proyecto. Adicionalmente debe indicar las competencias
y recursos con que cuentan para desarrollar esos Usos. Para esto, se incorporan los formularios de la
\19. Control de obra: Proceso de monitoreo, análisis, administración y optimización de la construcción, sección B, en las plantillas de PEB de Oferta y PEB Definitivo en las plantillas de PEB de Oferta y PEB
a través de uno o más modelos BIM. El objetivo es asegurar que la construcción se realice según las Definitivo. Estas plantillas se adjuntan en los anexos IV y V de este estándar.
especificaciones técnicas, de acuerdo con las regulaciones, seguridad y requerimientos del propietario,
así como para respaldar los estados de pago de los avances logrados en cada hito de entrega parcial.

\20. Modelación as-built: Proceso de modelación en el que se representa de manera exacta las
condiciones físicas de todos los elementos que son parte de una edificación o infraestructura. Los
elementos de estos modelos contienen toda la información solicitada para los modelos, tal como
códigos de barras, números de serie, garantías, historial de mantenimiento, entre otros.

\21. Gestión de activos: Proceso en el que un sistema de gestión organizado está vinculado
bidireccionalmente a un modelo BIM as-built, que puede estar conformado por uno o más modelos
BIM, para ayudar de manera eficiente en el mantenimiento y operación de un activo. Estos modelos BIM
contienen información de la construcción física, los sistemas, el entorno circundante y los equipos, que
se deben mantener, actualizar y operar de manera eficiente y sustentable.

\22. Análisis de sistemas: Proceso en el cual se utiliza uno o más modelos BIM para el análisis del
desempeño de un edificio o infraestructura de acuerdo con el planteamiento de las especialidades
en el diseño original. Esto incluye cómo funcionan los diferentes sistemas mecánicos y cuánta energía
utilizan. Otros análisis que se pueden hacer incluyen incidencia solar en las fachadas, análisis lumínico y
de radiación, cálculo de flujo de aire, entre otros.

\23. Mantenimiento preventivo: Proceso en el cual se utiliza uno o más modelos BIM para desarrollar
la mantención funcional de la estructura de una edificación o infraestructura (muros, columnas, pisos,
techo, etc.) y su equipamiento (mecánico, sanitario, eléctrico, etc.) durante su operación. Un programa
de mantenimiento exitoso puede mejorar de manera significativa el desempeño del activo, reduciendo
reparaciones y costos generales.
54 55

<!-- p. 29 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.7

5.7 Tipos y Niveles de Información1 TDI_G
Requerimientos energéticos En el presente estándar, se utilizan los conceptos de Tipos de Información (TDI) y Niveles de Información
Información de características energéticas de las entidades, como requerimientos de BIM (NDI) para explicitar los grupos de datos que deben estar contenidos en las entidades de los modelos
humedad, valor U, consumo de servicios, low E glazzing, entre otros. y el grado de profundidad de esa información. Estos conceptos se explican en las siguientes secciones.

TDI_H
5.7.1 Tipos de Información (TDI) Estándar sostenible
Información sobre condiciones de sustentabilidad, requerimientos de calidad de iluminación,
Los Tipos de Información, o TDI, son quince grupos de datos que pueden estar contenidos en las especificaciones de materiales sustentables y contenido reciclado, entre otros.
entidades de los modelos. Estos datos están organizados según la utilización que se le puede dar a la
información durante el ciclo de vida del proyecto. Estos TDI están basados en la Matriz de Elementos/ TDI_I
Objetos desarrollada por el US Veterans Affairs³³. Condiciones del sitio y medioambientales
Es información de las características generales del sitio y su entorno tales como, condiciones A continuación, se describen los Tipos de Información, identificados desde la letra “A” hasta la “O”
sísmicas, uso del terreno, de suelo y niveles de riesgo a las personas, entre otras.

TDI_J
Validación de cumplimiento de programa
TDI_A Información clave para realizar una validación del cumplimiento del programa funcional
Información general del proyecto del proyecto, como áreas planificadas, requisitos de áreas vidriadas, volumetría espacial
Información básica de identificación del proyecto como el tipo de edificio o infraestructura, y servicios requeridos, entre otros.
nombre del proyecto, dirección, requerimientos espaciales y programáticos, entre otros.
TDI_K
TDI_B Cumplimiento normativo
Propiedades físicas y geométricas Información que permita revisar el cumplimiento normativo y los requerimientos de
Información de las características y propiedades físicas de las entidades tales como seguridad de los ocupantes del proyecto, como requerimientos de control de fuego,
anchos, largos, altos, área, volumen, masa, etc. requerimientos de ventilación, anchos de accesos, carga de uso y carga de ocupación, así
como también aspectos seguridad vial, diseño geométrico de vías, entre otros.
TDI_C
Propiedades geográficas y de localización espacial TDI_L
Información de las propiedades de ubicación espacial y geográficas de las entidades, Requerimientos de fases, secuencia de tiempo y calendarización
tal como la latitud y longitud para la georreferencia del proyecto, el número y nombre Información que permita revisar fases, secuencias de tiempo y calendarización de áreas o
de piso, el número y nombre del espacio o zona y otra información necesaria para el partes de un proyecto, como, fases contempladas, orden de hitos del proyecto y orden
posicionamiento de las entidades. de construcción, entre otros.

TDI_D TDI_M
Requerimientos específicos de información para el fabricante y/o constructor Logística y secuencia de construcción
Información específica para la fabricación y/o construcción, como el tipo de elemento Información clave para revisar la logística de la construcción y su secuencia, como, por
(muro, pilar, puerta, etc.), su materialidad, nombre de sus componentes - en caso de ejemplo, ID del material e ID de instalación, número de serie del componente instalado,
existir-, identificación del producto, entre otros. entre otros.

TDI_E TDI_N
Especificaciones técnicas Entrega para la operación
Información de la especificación técnica de la entidad, como peso de transporte, nivel de Información clave para apoyar el funcionamiento de la entrega de la construcción como,
ruido, etc. En general, aplica para cualquier elemento que sea fabricado industrialmente por ejemplo, nombre de las empresas o compañías participantes del proyecto, sus
como, por ejemplo, equipos de aire, mobiliario, entre otros. contactos, nombre de la disciplina y áreas de trabajo, entre otras.

TDI_F TDI_O
Requerimientos y estimación de costos Gestión de activos
Información básica para la estimación del costo total del activo, como, por ejemplo, el Información para la gestión del activo como, tipos de productos, tipos de repuestos,
costo unitario referencial, costo base de ensamblaje, costo de transporte, entre otros. fechas de inicio y fin de garantías, entre otros.

33  U.S. Department of Veterans Affairs. The VA BIM Guide v1.0. Department of Veterans Affairs, 2010.
56 57

<!-- p. 30 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.7

Tabla 07. Tipos de Información por cada Uso BIM : Se considera TDI para el Uso BIM indicado
: TDI puede ser utilizado para proyectos que consideren rehabilitación
En la siguiente tabla, se presenta cada Uso BIM, identificando los Tipos de Información vinculados a éstos. Para
más información acerca de los recursos sugeridos, las competencias necesarias y los Tipos de Información
aplicables a cada uno de estos Usos, ver fichas en Anexo I.
ingeniería fases de de
y de espacial 3D de costos existentes diseño as-Built activos obra
y cumplimiento de de normativa obra sistemas digital seguimiento gestión del estructural lumínico energético mecánico de de de y de del de de análisis BIM programa espacios emergencias Análisis Análisis Análisis Análisis Otros Evaluaciónsustentabilidad Validación Planificación Diseñoconstructivos Fabricación Control Modelación Gestión Análisissistemas preventivo Gestiónde Planificaciónde Levantamientocondiciones Estimacióncantidades Planificación Análisisdel(zonificación) Análisisubicación Coordinación Diseñoespecialidades Revisión Usos 1. 2. 3. 4. 5. 6. 7. 8. 9. 10. 11. 12. 13. 14. 15. 16. 17. 18. 19. 20. 21. 22. 23.Mantenimiento 24. 25. Tipos de Información (TDI)

TDI_A
Información general del proyecto

TDI_B
Propiedades físicas y geométricas

TDI_C
Propiedades geográficas y de localización espacial

TDI_D
Requerimientos específicos de información para
el fabricante y/o constructor

TDI_E
Especificaciones técnicas

TDI_F
Requerimientos y estimación de costos

TDI_G
Requerimientos energéticos

TDI_H
Estándar sostenible

TDI_I
Condiciones del sitio y medioambientales

TDI_J
Validación de cumplimiento de programa

TDI_K
Cumplimiento normativo

TDI_L
Requerimientos de fases, secuencia de tiempo y
calendarización

TDI_M
Logística y secuencia de construcción

TDI_N
Entrega para la operación

TDI_O
Gestión de activos

Elaborada por Planbim, basada en la Matriz de elementos/objetos del US Veterans Affairs y en Project Execution Planning Guide versión
58 2.1, mayo 2011 59

<!-- p. 31 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.7

Los TDI son quince grupos de datos que Tabla 08. Niveles de Información
En la siguiente tabla se presenta una descripción de cada uno de los Niveles de Información (NDI):
pueden estar contenidos en las entidades
Concepto Descripción
de los modelos. Estos datos están

área, altura, volumen, localización y orientación de los organizados según la utilización que se NDI-1 Información inicial general Información inicial, que puede ser estimativa, acerca de
elementos generales.
le puede dar a la información durante el

Información básica del tamaño, forma, localización, cantidad ciclo de vida del proyecto. NDI-2 Información básica aproximada y orientación de los sistemas y elementos generales y su
ensamblaje.

5.7.2 Niveles de Información (NDI)1 Información detallada del tamaño, forma, localización,
Los Niveles de Información o NDI son los grados de profundidad que puede tener tanto la información NDI-3 Información detallada cantidad y orientación que sea relevante para el montaje de
los elementos. geométrica como no geométrica contenida en las entidades de los modelos BIM, según el Estado de
Avance de la Información de los Modelos en que se requiera. Esta información puede cambiar y/o
aumentar a medida que el proyecto avanza. Los NDI están directamente relacionados con los TDI. Información detallada y coordinada respecto del tamaño,
Información detallada y forma, localización, cantidad, orientación e interacción
A nivel internacional se utiliza comúnmente el término LOD, que tiene distintas acepciones y definiciones NDI-4 coordinada entre los sistemas de construcción y sus elementos de
en los diferentes países. Por ejemplo, en Reino Unido se utiliza para referirse a Level of Detail (Nivel montaje específico.
de Detalle) o Level of Definition (Nivel de Definición), mientras que, en Estados Unidos, se utiliza la
definición de LOD de la AIA, como Nivel de Desarrollo. En el presente estándar se utilizará el término Información detallada de la fabricación y montaje, Información detallada de la Nivel de Información (NDI) basado en el estándar desarrollado por The American Institute of Architects, NDI-5 considerando el tamaño, localización, cantidad, orientación
fabricación y montaje
(AIA)³⁴ y por BIMForum USA³⁵. e interacción entre los elementos.

En el presente estándar, se diferencian seis niveles por los cuales puede pasar la información de las
distintas entidades de los modelos. Es importante recalcar que es la información de las entidades la Información detallada del tamaño, forma, localización, Información detallada de lo
que pasa por distintos grados de información y por consecuencia la información de los modelos, y no NDI-6 cantidad, orientación y de la puesta en marcha de los construido y su puesta en marcha
viceversa. Es decir, no son los modelos los que se definen según un NDI, sino que los modelos albergan elementos construidos.
diferentes niveles de NDI, dependiendo del NDI de las entidades que contengan (Figura 5).
Elaborada por Planbim, basado en G202-2013 - Project Building Information Modeling Protocol Form de AIA y en el Level of
Development Specification de BIMForum USA

Algunos ejemplos de información geométrica de entidades BIM son:
Entidad
Cubiertas • Tamaño
NDI-2
• Volumen
Modelo BIM • Forma Arquitectura Entidad
NDI-3 Pilares • Altura NDI-1
• Orientación
Entidad
Puertas Algunos ejemplos de información no geométrica de entidades BIM son:
NDI-3
• Datos del sistema
Incorrecto Correcto • Datos de rendimiento
• Cumplimiento normativo
Figura 5. Simultaneidad de distintos NDI de las entidades en un modelo BIM • Especificaciones
Elaborada por Planbim • Costo
Para más detalle acerca de la información geométrica y no geométrica de las entidades BIM, ver
34  The American Institute of Architects. G202-2013 - Project Building Information Modeling Protocol Form. AIA, 2013. documento Matriz de Información de Entidades disponible en el repositorio digital de Planbim.
35  BIM Forum USA. Level of Development Specification. 2015.
60 36 https://planbim.cl/biblioteca/documentos/ 61

<!-- p. 32 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.7

5.7.2.1 Niveles de Información por Tipos de Información1
Dado que algunos Tipos de Información pueden ser requeridos en distintos Niveles de Información
dependiendo de los objetivos del proyecto o el Estado de Avance de la Información de éste, en la
siguiente tabla se especifican los distintos Niveles de Información que puede alcanzar cada uno de los
Tipos de Información.

Para más información acerca de cuáles parámetros se deben indicar para cada TDI en los distintos NDI,
ver documento Matriz de Información de Entidades, disponible en repositorio digital de Planbim³⁷.

Tabla 09. Niveles de Información por Tipos de Información : Es posible generar información del NDI indicado.
N/A : No Aplica generar información del NDI indicado.
: Se mantiene la información del NDI anterior.

de TiposInformación

Niveles de
Información TDI_A TDI_B TDI_C TDI_D TDI_E TDI-F TDI-G TDI_H TDI_I TDI_J TDI_K TDI_L TDI_M TDI_N TDI_O

NDI-1 N/A N/A N/A N/A

NDI-2 N/A N/A N/A

NDI-3 N/A

NDI-4 N/A

NDI-5

NDI-6

Elaborada por Planbim, basada en G202-2013 - Project Building Information Modeling Protocol Form de AIA, en el Level of
Development Specification de BIMForum USA, y la Matriz de Elementos/Objetos del US Veterans Affairs
37  https://planbim.cl/biblioteca/documentos/
62 63

<!-- p. 33 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.7

Tabla 10. Niveles de Información por Estados de Avance de la Información de los
Modelos
En la siguiente tabla se muestran los Niveles de Información mínimos que pueden tener las Entidades
BIM para cada Estado de Avance de la Información de los Modelos. - MEP
y Tuberías Especiales Circulación/ Rampas Civiles / Instalaciones de
e Cortina Falsos/ MEP y de Ejes (IfcGrid) Terreno (IfcSite) Elementos (IfcCivilElement) ElementosGeográficos (IfcGegraphicElement) Fundaciones (IfcFooting) Zonas/Espacios (IfcSpace-ifcZone) Columnas (IfcColumn) Vigas (IfcBeam) Losas/Radier (IfcSlab) Muros (IfcWall) Muros (IfcCurtainWall) Ventanas (IfcWindow) Puertas (IfcDoor) Cubiertas/Techumbres (IfcRoof) CielosAcabados (IfcCovering) SistemasEscaleras (IfcTransportElement– ifcStair–ifcRamp) Equipos (IfcSanitayTerminal- IfcMedicalDevice- IfcLamp) Muebles (IfcFurniture- IfcSystemFurniture Element) Estructuras (IfcElementAssembly) EquipamientoTableros (IfcEnergyConversionDevice IfcDistributionControlElement) Distribución (IfcDistributionFlowElement)
EntidadesModelos EAIM

de
DC
Diseño NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1
Conceptual InformaciónPlanificación

DA
Diseño NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1 NDI-1
Anteproyecto
diseño
de DB NDI-2 NDI-2 NDI-2 NDI-1 NDI-1 NDI-2 NDI-2 NDI-2 NDI-2 NDI-2 NDI-2 NDI-2 NDI-2 NDI-2 NDI-2 NDI-2 NDI-2 NDI-1 NDI-1 NDI-2 NDI-2
Diseño Básico
Información DD
Diseño de NDI-3 NDI-2 NDI-3 NDI-2 NDI-2 NDI-3 NDI-3 NDI-3 NDI-3 NDI-3 NDI-3 NDI-3 NDI-3 NDI-3 NDI-3 NDI-3 NDI-3 NDI-2 NDI-2 NDI-3 NDI-3
Detalle

CC
Coordinación
NDI-3 NDI-3 NDI-4 NDI-3 NDI-3 NDI-4 NDI-3 NDI-3 NDI-4 NDI-3 NDI-3 NDI-4 NDI-4 NDI-3 NDI-4 NDI-3 NDI-4 NDI-3 NDI-3 NDI-4 NDI-4
de
Construcción

CM construcción Construcción,
NDI-3 NDI-3 NDI-5 NDI-4 NDI-4 NDI-5 NDI-4 NDI-4 NDI-4 NDI-4 NDI-4 NDI-4 NDI-4 NDI-4 NDI-4 NDI-4 NDI-5 NDI-4 NDI-4 NDI-5 NDI-5
de Manufactura y
Información MontajeAB
NDI-3 NDI-3 NDI-5 NDI-4 NDI-4 NDI-5 NDI-4 NDI-4 NDI-5 NDI-4 NDI-5 NDI-5 NDI-5 NDI-4 NDI-5 NDI-4 NDI-5 NDI-5 NDI-5 NDI-5 NDI-5
As-Built

PM
Puesta en NDI-3 NDI-3 NDI-5 NDI-4 NDI-4 NDI-5 NDI-4 NDI-4 NDI-5 NDI-4 NDI-5 NDI-5 NDI-5 NDI-4 NDI-5 NDI-4 NDI-6 NDI-5 NDI-5 NDI-6 NDI-6 operación Marcha
de
GM
Gestión y
NDI-3 NDI-3 NDI-6 NDI-4 NDI-4 NDI-6 NDI-4 NDI-4 NDI-5 NDI-4 NDI-6 NDI-6 NDI-6 NDI-4 NDI-5 NDI-4 NDI-6 NDI-5 NDI-5 NDI-6 NDI-6
Mantenimiento Información del Activo

Elaborada por Planbim, basada en G202-2013 - Project Building Information Modeling Protocol Form de
64 AIA y en el Level of Development Specification de BIMForum USA 65

<!-- p. 34 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.8

5.7.3 Tipos y Niveles de Información en la SDI BIM 5.8 Estrategia de colaboración
La Solicitud de Información BIM debe definir cuáles Tipos de Información se requieren en el marco Para el correcto desarrollo del proyecto es clave que existan métodos establecidos y conocidos por
del proyecto, con sus correspondientes Niveles de Información. Dado que estos niveles dependen todos, tanto para la gestión de la información como para su intercambio. Estos métodos deben estar
del Estado de Avance de la Información de los Modelos, se debe velar por que los NDI requeridos apoyados por plataformas habilitantes que faciliten la comunicación y permitan tener trazabilidad de
sean siempre coherentes con el grado de avance del proyecto. Por ejemplo, en la etapa de diseño, la información y de la toma de decisiones del proyecto.
cuando se está desarrollando el anteproyecto (DA) o el diseño de detalle (DD), no se puede requerir
Para esto debe existir un ambiente de colaboración en las distintas etapas del ciclo de vida de los información sobre fechas de garantías o mantenciones (NDI 6), ya que esa información aún no existe.
activos. Éste debe permitir que los actores del proyecto accedan a la información para realizar sus
diferentes funciones y puede ser implementado de diferentes maneras según el nivel de madurez del
5.7.4 Tipos y Niveles de Información en el PEB Solicitante y el Proveedor Adjudicado. Este ambiente se conoce como Entorno de Datos Compartidos
(CDE, por sus siglas en inglés Common Data Environment).
Dado que los Niveles de Información están directamente relacionados a los EAIM (5.7.2.2), los Niveles
de Información quedan indicados de manera indirecta en el PEB, a través de la incorporación de los
EAIM de cada entrega. Para esto se incorpora el formulario de la sección C.2, en las plantillas de PEB de 5.8.1 Entorno de Datos Compartidos (CDE)1
Oferta y PEB Definitivo. Estas plantillas se adjuntan en los anexos IV y V de este estándar.
El CDE permite tener una fuente única de información para recopilar, gestionar y difundir documentos
y modelos entre los actores del proyecto, a través de un proceso estandarizado. Un CDE generalmente
contiene un sistema de gestión documental que facilita la transferencia de información entre los
actores de un proyecto³⁸. Además, debe considerar la seguridad y la calidad de la información.

La norma ISO 19650-1:2018 indica que la información de un proyecto puede estar localizada en
múltiples ubicaciones y el CDE permite que el flujo de trabajo esté distribuido en diferentes sistemas
informáticos o plataformas tecnológicas.

Esto quiere decir, que el CDE puede estar conformado por una plataforma o por la suma de distintos
sistemas que permitan colaborar, gestionar, registrar y dar trazabilidad a la información transferida
entre los actores. A continuación, se indican las condiciones que deben considerar estos sistemas:

• Plataforma de colaboración: Esta plataforma debe permitir trabajar con información unificada
y centralizada, siguiendo la estrategia de consolidación seleccionada (modelos federados o
integrados), administrando y respaldando los modelos BIM de manera segura.
• Plataforma de gestión documental: Esta plataforma debe permitir el control de los procesos
de intercambio de documentación y modelos BIM, gestionando los cambios y haciendo el
seguimiento de los costos y tiempos del proyecto.
• Formato de requerimientos de información y colaboración: Los comentarios, incidencias y
revisiones de los modelos BIM deben realizarse a través de formatos que permitan el registro y
trazabilidad de éstos. Para esto se puede utilizar BCF (BIM Collaboration Format), que permite,
en conjunto con los modelos BIM IFC, comunicar estos requerimientos de información del
proyecto a través de formatos abiertos, es decir openBIM.

5.8.1.1 Estatus del Entorno de Datos Compartidos (CDE)
A nivel internacional, las normas ISO 19650 parte 1 y 2 estandarizan la estructura del CDE, definiendo
cuatro estatus para los archivos alojados en el CDE:

• Trabajo en progreso
• Compartido
• Publicado
• Archivado

Los datos e información pueden existir en los cuatro estados anteriores, dependiendo de su desarrollo.
El estado de Archivado debe ser asignado a los documentos que han sido reemplazados o eliminados,
con el fin de mantener la trazabilidad del desarrollo de la información.

38  Basado en la definición de Bilal Succar, https://bimdictionary.com/en/common-data-environment/1/
66 67

<!-- p. 35 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.9

5.8.2 Consolidación de modelos BIM2 5.9 Organización de los modelos BIM
Existen distintas maneras de unir la información de los modelos generados por los diversos actores del Para lograr el correcto flujo de información en el desarrollo del proyecto es necesario compartir
proyecto. Por esto, se debe seleccionar una de las siguientes estrategias de consolidación, que debe información estructurada, sin ambigüedades, siendo los modelos BIM una parte muy importante de esa
ser conocida y utilizada a lo largo de todo el desarrollo del proyecto: información. Contar con modelos que cumplen requisitos mínimos de estandarización permite asegurar
la disponibilidad de información de manera más eficiente y eliminar pérdidas de tiempo en el proceso.
• Modelo BIM federado: Modelo creado a partir de información contenida en archivos
separados. Esta información puede provenir de distintos actores³⁹. En el presente estándar, los requisitos para la organización de los modelos se enfocan en:
• Modelo BIM integrado: Modelo compuesto por la información de las distintas disciplinas del • Estructuración de modelos
proyecto, contenida en una única base de datos.
• Nomenclaturas y codificación
5.8.3 Procedimiento de reuniones • Sistemas de clasificación
Al inicio del proyecto, el Proveedor Adjudicado debe realizar una reunión de inducción con el
Solicitante para: 5.9.1 Estructuración de los modelos BIM
Para el desarrollo de los modelos es clave que exista un acuerdo entre el Solicitante y el Proveedor • Confirmar su disponibilidad de recursos y capacidades en relación a los Usos BIM solicitados
Adjudicado acerca de:
• Consensuar y validar información para el desarrollo del PEB Definitivo
• Unidades que utilizará para el desarrollo de los modelos
Adicionalmente, para lograr un proceso colaborativo durante el desarrollo del proyecto se deben
programar reuniones para las actividades que lo requieran. • Coordenadas que se usarán para todos los modelos
• Sistema de subdivisión de los modelos, en caso de ser necesario Previo a estas reuniones se debe definir un objetivo claro, sus participantes y la frecuencia y modalidad
de éstas.
5.9.2 Nomenclaturas y codificación
5.8.4 Estrategia de colaboración en la SDI BIM 5.9.2.1 Estructura general de nomenclaturas
La Solicitud de Información BIM debe establecer las condiciones para el desarrollo del trabajo colaborativo Para lograr una correcta comunicación y traspaso de información entre los actores de un proyecto es
entre los distintos actores a lo largo del proyecto. Esto debe cubrir al menos los aspectos de: clave la utilización de nomenclaturas conocidas y compartidas por todos para elementos tales como
modelos, entidades y documentos relacionados.
• CDE
5.9.2.2 Nombres de archivos y carpetas
• Consolidación de modelos BIM
Los nombres de archivos deben estar construidos a partir de los códigos que se especifican más
• Procedimiento de reuniones adelante. Estos códigos se deben unir a través de guion medio (-).
En caso de que el Solicitante no tenga una preferencia respecto de uno o más de estas condiciones, la
La estructura de nombre para los archivos debe ser: SDI BIM debe requerir que los actores involucrados definan estos criterios de común acuerdo.
Proyecto-Organización-Disciplina-Zona-Nivel-Tipo de Documento-Número-Estatus(*)-Revisión(*)
5.8.5 Estrategia de colaboración en el PEB Ejemplo de nombre de archivo desglosado en Tabla 11: PR1-ABC-ARQ-Z1-01-MO-0001-C-A
En el PEB Definitivo, el Proveedor debe señalar cómo abordará la estrategia de colaboración. En La estructura de nombre para las carpetas debe ser:
caso de que la SDI BIM no defina específicamente alguno de estos aspectos, en el PEB se debe hacer
una propuesta al respecto, que deberá ser validada por el Solicitante. Para esto, se incorporan los Proyecto Estatus(*)-Revisión(*)
formularios de la sección D en las plantillas de PEB Inicial y PEB Definitivo que se adjuntan en los anexos
IV y V de este estándar.  Ejemplo de nombre de carpeta desglosado en Tabla 11: PR1-C-A

Los campos de nombre de archivos y carpetas, así como las descripciones incorporados en el presente
estándar, están basados en la norma BS 1192:2007.

Nota: (*) indica que el código es opcional.

39  Basado en ISO 19650-1:2018 3.3.11 y 3.3.12, modificado.
68 69

<!-- p. 36 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.9

5.9.2.3 Códigos de tipos de documentos Tabla 11. Nombres de archivos y carpetas
A continuación se indican códigos de dos letras mayúsculas para la identificación de documentos. En
caso de existir en el proyecto un tipo de documento que no está incluido en el siguiente listado, el
Campo Descripción Carpeta Archivo Solicitante debe proponer un código de dos letras.

Se debe definir un código único de proyecto al inicio de éste,
independiente y distinto del número de trabajo interno que
Proyecto tenga la organización. Se recomienda que éste coincida con PR1 PR1
algún código de contrato existente. El código para el proyecto y Tabla 12. Códigos de documentos
cualquier subproyecto debe ser de dos a seis caracteres. Sigla Documento

Se debe definir un código único para la organización solicitante. CO Corte Organización ABC Éste debe ser de tres a seis caracteres.
CV Circulaciones verticales con sus detalles
Disciplina o Se debe indicar un código para cada disciplina o sistema dentro
ARQ DE Detalles exteriores sistema del proyecto (Tabla 13). Este código debe ser de tres caracteres.
DH Detalles zonas húmedas Se debe indicar un código para la zona de la edificación o
infraestructura al cual pertenece el archivo. Éste debe ser de DI Detalles interiores
uno a dos caracteres.
Zona Z1 Nota: Cuando un archivo representa todas las zonas de una DP Detalles de planta generales
edificación o infraestructura debe indicarse como:
• ZZ: Todas las zonas EL Elevaciones (interiores y exteriores)
Se debe definir un código único para cada nivel si es una ES Escantillón
edificación y para cada localización si es una infraestructura.
ET Especificaciones técnicas Este código debe ser de dos caracteres.
• ZZ: Niveles múltiples GE Generalidades y notas generales respecto al proyecto
• XX: No hay nivel aplicable Nivel o • 01: Piso 1 01 ME Memoria (arquitectónica, de cálculo, entre otros)
ubicación • 02: Piso 2, etc.
• E1: Entrepiso por encima del nivel 01 MO Modelos
• E2: Entrepiso por encima del nivel 02, etc. PC Plantas de cielo
• S1: Subterráneo 1
• S2: Subterráneo 2, etc. PL Planta

Tipo de Se debe indicar un código único para cada tipo de documento PM Plan maestro MO
documento (Tabla 12). Este código debe ser de dos caracteres.
PO Programa oficial
Cuando un archivo pertenece a una serie que no se distingue PT Presupuesto Número por ninguno de los campos anteriores se debe indicar un 0001
(opcional) número secuencial. Este código debe ser de cuatro dígitos. TP Trabajos previos (demolición, trabajos de sitio, instalación de faenas, trabajos)

Elaborada por Planbim El texto descriptivo puede utilizarse para expresar distinciones Descripción que permitan el reconocimiento entre documentos. Este texto Puertas
(opcional) debe ser corto y preciso en su redacción.

Los códigos de identificación y gestión del estatus de las
carpetas y de los archivos pueden seguir lo indicado en la
sección de Estatus del Entorno de Datos Compartidos (5.8.1.1).
Estatus Este código debe ser de uno a tres caracteres. C C
(opcional) • T: Trabajo en progreso
• C: Compartido
• P: Publicado
• A: Archivado

Las carpetas y los archivos pueden indicar la versión de revisión Revisión de la información contenida. Este código debe ser de uno a dos A A
(opcional) caracteres y deben ser asignados de manera secuencial.

Resultado carpeta: PR1-C-A

Resultado archivo: PR1-ABC-ARQ-Z1-01-MO-0001-C-A

Elaborada por Planbim, basado en la norma ISO 19650-2: 2018
70 71

<!-- p. 37 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS COMPONENTES DE L A SOLICITUD DE INFORMACIÓN Y DEL PL AN DE EJECUCIÓN BIM
5.9

Tabla 13 - Códigos y colores por disciplina y/o sistema
5.9.2.4 Códigos y colores por disciplina y/o sistema Disciplina Sigla Color R G B
A continuación se presenta una tabla con códigos de tres letras mayúsculas para las especialidades y Arquitectura ARQ
sistemas que se encuentran más comúnmente en un proyecto, así como también colores asociados a
Audio y Acústica ACU
cada uno de éstos.
Audio AUD 190 120 10
En caso de existir en el proyecto una disciplina y/o sistema que no está incluido en el siguiente listado, el Acústica ACU 230 230 30
Solicitante debe proponer un código de tres letras mayúsculas y un color que no estén siendo utilizados Cálculo estructural EST 165 165 165
por otras disciplinas o sistemas.
Carga combustible CCB
Redes de combustible RCB 255 255 0
Escape de gases EDG 255 215 0

Circuito cerrado de TV CTV 230 160 0

Climatización CLI
Inyección de aire INY 230 30 100

Extración de aire EXT 135 15 80

Retorno de aire RET 155 40 175

Aire fresco FRE 215 0 250

Refrigerante REF 100 60 180

Equipos EQU 100 30 255
Evacuación condensación CON 80 110 255

Control centralizado CCT 30 150 240

Electricidad ELE
Fuerza FRZ 105 160 55
Corrientes débiles COD 120 255 0

Alumbrado ALU 205 220 55
Voz y datos VOD 200 255 0

Extracción de Basura BAS 110 210 75

Iluminación ILU 75 175 80

Obras civiles OCV 55 85 35

Protección contra incendio PCI
Detección de incendio DET 255 20 70

Extinción de incendio EXT 0 175 255

Red húmeda RHU 230 60 50
Red seca RSE 215 165 70

Radiocomunicación RAD 0 230 255

Redes de gases clínicos RGC
Gases clínicos GCL 100 255 220
Red de aire comprimido RAC 0 150 135

Residuos clínicos RCL 0 230 120

Sanitario SAN
Agua caliente ACA 255 60 0

Agua fría AFR 65 195 255
Aguas negras ANE 50 65 160
Aguas grises AGR 125 30 160

Aguas tratadas ATR 195 25 90

Aguas lluvias ALL 255 85 35
Riego RIE 120 85 70

Suministro de gas GAS 255 235 60

Tecno vigilancia TVG 115 115 115

Elaborada por Planbim 7372

<!-- p. 38 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS

5.9.3 Sistemas de clasificación
A nivel internacional, existen diversos sistemas de clasificación para la industria de la construcción,
por ejemplo: Uniformat, OmniClass (Norteamérica), Uniclass (Reino Unido), Building 90 (Finlandia) y Sfb Se busca que todas las
y BSAB (Suecia). Todos estos están basados en la norma ISO 12006-2:2015, que fija el marco para la
organización de información sobre trabajos de construcción.

Dentro del desarrollo de un proyecto se debe seleccionar un sistema de clasificación que debe ser instituciones públicas que utilizado por todas las partes involucradas durante todo el proceso.

5.9.4 Organización de los modelos BIM en la SDI BIM exijan BIM lo hagan de una
La Solicitud de Información BIM puede definir criterios a ser utilizados por todos los actores involucrados,
respecto de la organización de los modelos indicadas en 5.9.2, 5.2.2 y 5.9.3 referentes a:

• Estructuración de modelos: unidades, coordenadas y subdivisión de los modelos manera estandarizada y
• Nomenclaturas y codificación: nombres de archivos y carpetas, códigos y colores de las
disciplinas y/o sistemas
• Sistemas de clasificación: se debe definir un sistema para todo el proyecto conocida por todos los actores
En caso de que el Solicitante no tenga una preferencia respecto de uno o más de estos aspectos, la SDI
BIM debe requerir que los actores involucrados definan estos criterios de común acuerdo.
involucrados en el proyecto.
5.9.5 Organización de los modelos BIM en el PEB
En el PEB Definitivo, el Proveedor Adjudicado debe señalar cómo abordará la organización de
los modelos. El Proveedor debe seguir lo planteado en la SDI BIM acerca de la estructuración de
modelos, nomenclatura, codificación y sistema de clasificación. En caso de que la SDI BIM no defina
específicamente alguno de estos aspectos, en el PEB se debe hacer una propuesta al respecto, que
deberá ser validada por el Solicitante. Para esto, se incorporan los formularios de la sección E en la
plantilla de PEB Definitivo que se adjunta en el anexo V de este estándar.

74 7575

<!-- p. 39 -->

• 1 Levantamiento de condiciones existentes..........................................• 79
• 2 Estimación de cantidades y costo.........................................................• 80
• 3 Planificación de fases..............................................................................• 81
• 4 Análisis del cumplimiento del programa espacial (zonificación).......• 82
• 5 Análisis de ubicación...............................................................................• 83
• 6 Coordinación 3D......................................................................................• 84
• 7 Diseño de especialidades.......................................................................• 85 Anexo I • 8 Revisión del diseño..................................................................................• 86
• 9 Análisis estructural..................................................................................• 87
• 10 Análisis lumínico.......................................................................................• 88
• 11 Análisis energético...................................................................................• 89
• 12 Análisis mecánico.....................................................................................• 90
• 13 Otros análisis de ingeniería....................................................................• 91 Fichas de Usos BIM
• 14 Evaluación de sustentabilidad...............................................................• 92
• 15 Validación normativa...............................................................................• 93
• 16 Planificación de obra..............................................................................• 94
• 17 Diseño de sistemas constructivos.........................................................• 95
• 18 Fabricación digital...................................................................................• 96
• 19 Control de obra........................................................................................• 97
• 20 Modelación as-built................................................................................• 98
• 21 Gestión de activos...................................................................................• 99
• 22 Análisis de sistemas................................................................................• 100
• 23 Mantenimiento preventivo......................................................................• 101
• 24 Gestión y seguimiento de espacios......................................................• 102
• 25 Planificación y gestión de emergencias...............................................• 103

76 77

<!-- p. 40 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\1. Levantamiento de condiciones existentes
Es el proceso de desarrollo de uno o más modelos BIM considerando las condiciones actuales de un
sitio y/o sus instalaciones y/o un área específica dentro de una edificación o infraestructura. Este
modelo se puede desarrollar de múltiples maneras, por ejemplo, a partir de escaneo láser o técnicas de
topografía convencionales. Una vez que se construye el modelo, éste se puede consultar para obtener
información, ya sea para una nueva construcción o un proyecto de remodelación y/o ampliación.

Recursos sugeridos:
• Software de modelado BIM
• Software de manipulación de nubes de puntos, de exploración láser, o fotogramétrico
• Equipo LIDAR o fotogramétrico
• Equipo de topografía convencional
• Hardware apto para procesar modelos BIM
• Infraestructura TI necesaria
Equipo con capacidades BIM respecto de:
A continuación, se presenta una ficha de • Herramientas complementarias como escáner láser 3D, drones, equipos de topografía
descripción de cada Uso BIM, identificando los convencional, entre otros: N-42*
recursos sugeridos, las competencias requeridas • Generación de modelos a partir de información obtenida con las herramientas
por el equipo y los Tipos de Información BIM complementarias: F-18, F-19, F-20, F-21, G-22, G-23, G-24, J-29, I-27* Anexo I
vinculados a estos usos. • Información generada por herramientas complementarias: G-22, G-23, G-24, I-27*
• Niveles de Información (NDI) requeridos: G-22, G-23, G-24*
Para más información acerca de las capacidades Experiencia o conocimiento previo en:
que se referencian en cada uso, ver Anexo II • No aplica
Matriz de Roles BIM. Fichas de

Etapas de proyecto en las que aplica el Uso BIM: Usos BIM PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Levantamiento de condiciones existentes

TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas Propiedades Requerimientos específicos Especificaciones
del proyecto y geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación
calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II.

78 79

<!-- p. 41 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\2. Estimación de cantidades y costos 3. Planificación de fases
Proceso de utilización de uno o más modelos BIM para extraer cantidades de componentes y materiales Proceso de utilización de uno o más modelos 4D (3D + tiempo) para planear la secuencia constructiva
del proyecto y, en base a esta información, el costo de un proyecto en sus distintas etapas, siendo más de un proyecto y/o las etapas de ocupación en una remodelación o ampliación de una edificación o
eficiente desarrollarlo desde las etapas tempranas. Esto permite prevenir posibles costos y tiempos infraestructura.
adicionales por errores y/o modificaciones al proyecto.
Recursos sugeridos:
Recursos sugeridos: • Software de modelado BIM
• Software de estimación de costos basado en modelos BIM • Software de planificación
• Software de modelado BIM • Software BIM que incorpore tiempo (4D)
• Modelos BIM con los NDI correspondientes al EAIM indicado • Modelos BIM con los NDI correspondientes al EAIM indicado
• Datos de costos (incluidos los datos de algún sistema de clasificación) • Hardware apto para procesar modelos BIM
• Hardware apto para procesar modelos BIM • Infraestructura TI necesaria
• Infraestructura TI necesaria
Equipo con capacidades BIM respecto de: Equipo con capacidades BIM respecto de:
• Modelos para planificación: F-18, F-19, F-20, F-21, G-22, G-23, G-24, K-31, K-32, I-27* • Modelos para estimación de costos: F-18, F-19, F-20, F-21, G-22, G-23, G-24, K-31, K-33,
• Modelos que incorporan tiempo (4D): F-18, F-19, F-20, F-21, I-27, K-31, K-32* I-27*
• Programación de la construcción: F-19, K-31, K-32*
Experiencia o conocimiento previo en:
• Cuantificaciones y estimaciones de proyectos Experiencia o conocimiento previo en:
• Diseño y construcción • No aplica
• Estándares y normativas aplicables
• Sistemas y métodos constructivos

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Estimación de cantidades y costos Tipos de Información aplicables para Planificación de fases

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.

80 81

<!-- p. 42 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\4. Análisis del cumplimiento del programa espacial (zonificación) 5. Análisis de ubicación
Proceso de utilización de uno o más modelos BIM para analizar si el diseño cumple de manera eficiente Proceso de utilización de uno o más modelos BIM y/o GIS para evaluar las propiedades de un área y
y exacta con las áreas incluidas en los requerimientos del proyecto, tomando en cuenta las regulaciones determinar la mejor localización y orientación de un futuro proyecto.
y normas establecidas.
Recursos sugeridos:
Recursos sugeridos: • Software GIS
• Software de modelado BIM • Software de modelado BIM
• Modelos BIM con los NDI correspondientes al EAIM indicado • Modelos BIM con los NDI correspondientes al EAIM indicado
• Datos del programa espacial del proyecto • Datos de ubicación de sitio
• Normativa vigente según especialidad • Normativa vigente según especialidad
• Hardware apto para procesar modelos BIM • Hardware apto para procesar modelos BIM
• Infraestructura TI necesaria • Infraestructura TI necesaria
Equipo con capacidades BIM respecto de: Equipo con capacidades BIM respecto de:
• Modelos BIM para el análisis del cumplimiento del programa espacial del proyecto: F-18, • Modelos BIM y/o GIS para el análisis de ubicación: F-18, F-19, F-20, F-21, G-22, G-23,
F-19, F-20, F-21, G-22, G-23, G-24, I-27, I-28* G-24, I-27*
Experiencia o conocimiento previo en: Experiencia o conocimiento previo en:
• No aplica • No aplica

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Análisis del cumplimiento del programa espacial Tipos de Información aplicables para Análisis de ubicación

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.

82 83

<!-- p. 43 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\6. Coordinación 3D 7. Diseño de especialidades
Proceso de planificación entre las distintas disciplinas previo al diseño para evitar posibles interferencias. Proceso de creación de uno o más modelos BIM de las distintas disciplinas de un proyecto. El Diseño
El proceso incluye además la detección de interferencias una vez diseñadas las disciplinas a través de de Especialidades es un paso clave para incorporar la información a una base de datos inteligente de la
uno o más modelos BIM. cual se pueden extraer propiedades, cantidades, costos, programación, etc.

Recursos sugeridos: Recursos sugeridos:
• Software de modelado BIM • Software de modelado BIM
• Software de revisión de modelos BIM • Modelos BIM con los NDI correspondientes al EAIM indicado
• Modelos BIM con los NDI correspondientes al EAIM indicado • Estándares y normas según especialidad
• Normativa vigente según especialidad • Hardware apto para procesar modelos BIM
• Hardware apto para procesar modelos BIM • Infraestructura TI necesaria
• Infraestructura TI necesaria Equipo con capacidades BIM respecto de:
Equipo con capacidades BIM respecto de: • Modelos BIM de las disciplinas correspondientes: F-18, F-19, F-20, F-21, G-22, G-23, G-24,
• Modelos de las disciplinas correspondientes: F-18, F-19, F-20, F-21, G-22, G-23, G-24, H-25, H-26, I-27, I-28*
I-27, I-28* Experiencia o conocimiento previo en:
• Herramientas de revisión: E-15, J-29, J-30* • Diseño y construcción
Experiencia o conocimiento previo en: • Estándares y normativas aplicables
• Liderazgo de equipos de trabajo • Sistemas y métodos constructivos
• Coordinación de proyectos
• Diseño y construcción
• Estándares y normativas aplicables
• Sistemas y métodos constructivos

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Coordinación 3D Tipos de Información aplicables para Diseño de especialidades

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.

84 85

<!-- p. 44 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\8. Revisión del diseño 9. Análisis estructural
Proceso de revisión de las posibles respuestas a los requerimientos del proyecto respecto de áreas, Proceso de análisis para determinar el comportamiento de un sistema estructural a través de uno o más
diseño espacial, iluminación, seguridad, confort, acústica, materialidad, colores, etc., mediante la modelos BIM. En base a este análisis, se desarrolla y ajusta el diseño para crear sistemas estructurales
creación de uno o más modelos BIM que pueden contener múltiples alternativas de diseño. eficientes que cumplan con la normativa vigente. Esta información se utilizará en las fases de diseño y
construcción.
Recursos sugeridos:
• Software de revisión de modelos BIM Recursos sugeridos:
• Modelos BIM con los NDI correspondientes al EAIM indicado • Software de modelado BIM
• Espacio de revisión y validación colaborativa interdisciplinaria (virtual o físico) • Herramientas y software de análisis de Ingeniería Estructural
• Normativa vigente según especialidad • Modelos BIM con los NDI correspondientes al EAIM indicado
• Hardware apto para procesar modelos BIM • Estándares y normas según especialidad
• Infraestructura TI necesaria • Hardware apto para procesar modelos BIM
• Infraestructura TI necesaria
Equipo con capacidades BIM respecto de:
• Modelos BIM de las disciplinas: D-13, F-18, F-19, F-20, F-21, I-27, I-28* Equipo con capacidades BIM respecto de:
• Modelos BIM para análisis estructural: F-18, F-19, F-21, G-22, G-23, G-24, I-27, I-28*
Experiencia o conocimiento previo en:
• Diseño y construcción Experiencia o conocimiento previo en:
• Estándares y normativas aplicables • Técnicas de modelado analítico
• Sistemas y métodos constructivos • Diseño estructural
• Estándares y normativas aplicables
• Sistemas y métodos constructivos

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Revisión del diseño Tipos de Información aplicables para Análisis estructural

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.
: Opcional para proyectos de remodelación y/o ampliación

86 87

<!-- p. 45 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\10. Análisis lumínico 11. Análisis energético
Proceso para determinar el comportamiento de un sistema de iluminación a través de uno o más Proceso de evaluación de un proyecto a través de uno o más modelos BIM, en base a criterios
modelos BIM. Esto puede incluir iluminación artificial (interior y exterior) y natural (iluminación solar energéticos, que pueden incluir materiales, desempeños y/o procesos. Esta evaluación energética
y sombra). En base a este análisis, se desarrolla y ajusta el diseño para crear sistemas de iluminación puede ser realizada en todas las etapas del ciclo de vida, sin embargo, es más efectiva cuando se realiza
eficientes. Este análisis permite simulaciones que pueden mejorar significativamente el diseño y el en la fase de diseño para luego ser aplicada en la etapa de construcción y operación del proyecto.
rendimiento de la iluminación a lo largo de su ciclo de vida.
Recursos sugeridos:
Recursos sugeridos: • Software de simulación y análisis energético
• Software de modelado BIM • Modelo de diseño con los NDI según el EAIM indicado
• Herramientas y software de análisis de iluminación • Datos meteorológicos locales detallados
• Modelos BIM con los NDI correspondientes al EAIM indicados • Estándares y normas según especialidad
• Estándares y normas según especialidad • Estándares energéticos nacionales y/o locales (por ejemplo: Estándar ASHRAE 90.1)
• Hardware apto para procesar modelos BIM • Hardware apto para procesar modelos BIM
• Infraestructura TI necesaria • Infraestructura TI necesaria
Equipo con capacidades BIM respecto de: Equipo con capacidades BIM respecto de:
• Modelos para análisis lumínico: F-18, F-19, F-20, F-21, G-22, G-23, G-24, H-25, H-26, • Modelos BIM de las disciplinas: F-18, F-19, F-20, F-21, G-22, G-23, G-24, H-25, H-26, I-27,
I-27, I-28* I-28, M-40*
• Herramientas de análisis: I-27, I-28*, L-34
Experiencia o conocimiento previo en:
Experiencia o conocimiento previo en: • Análisis lumínico
• Estándares y normativas aplicables
• Diseño y construcción
• Sistemas y métodos constructivos

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Análisis lumínico Tipos de Información aplicables para Análisis energético

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.

88 89

<!-- p. 46 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\12. Análisis mecánico 13. Otros análisis de ingeniería
Proceso de análisis y evaluación de ingeniería de los sistemas mecánicos, basado en las especificaciones Proceso para determinar el método de ingeniería no tradicional más pertinente basado en las
de diseño para los sistemas del proyecto, a través de uno o más modelos BIM. especificaciones de diseño, a través de uno o más modelos BIM. Las herramientas de análisis y
simulaciones de rendimiento pueden mejorar significativamente el diseño de las instalaciones y su
Recursos sugeridos: consumo de energía durante su ciclo de vida.
• Software de modelado BIM
• Herramientas y software de análisis y cálculo de ingeniería Recursos sugeridos:
• Modelo de diseño con los NDI según el EAIM indicado • Software de modelado BIM
• Estándares y normas según especialidad • Herramientas y software de análisis de ingeniería
• Hardware apto para procesar modelos BIM • Modelo de diseño con los NDI según el EAIM indicado
• Infraestructura TI necesaria • Estándares y normas según especialidad
• Hardware apto para procesar modelos BIM
Equipo con capacidades BIM respecto de: • Infraestructura TI necesaria
• Modelos para análisis mecánico: F-18, F-19, F-20, F-21, G-22, G-23, G-24, H-25, H-26,
Equipo con capacidades BIM respecto de: I-27, I-28*
• Modelos para análisis de ingenierías: F-18, F-19, F-20, F-21, G-22, G-23, G-24, H-25, H-26,
I-27, I-28* Experiencia o conocimiento previo en:
• Diseño y construcción de sistemas mecánicos
Experiencia o conocimiento previo en: • Sistemas y métodos constructivos
• Ingeniería específica
• Diseño y construcción
• Sistemas y métodos constructivos

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Análisis mecánico Tipos de Información aplicables para Otros análisis de ingeniería

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.

90 91

<!-- p. 47 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\14. Evaluación de sustentabilidad 15. Validación normativa
Proceso en el que un proyecto se evalúa en base a criterios de sustentabilidad, a través de uno o más modelos Proceso de revisión del cumplimiento de códigos y normas que aplican al proyecto, a través de uno o
BIM. Este proceso debe ocurrir durante todas las etapas de la vida de una instalación, incluida la planificación, más modelos BIM.
el diseño, la construcción y la operación. La aplicación de características sustentables a un proyecto en las
Recursos sugeridos: fases de planificación y diseño temprano mejoran la capacidad de impactar en el diseño y la planificación.
• Software de revisión de modelos BIM a través de reglas
Recursos sugeridos: • Modelo de diseño con los NDI según el EAIM indicado
• Software de modelado BIM • Estándares y normas según especialidad
• Software de análisis de criterios de sustentabilidad • Hardware apto para procesar modelos BIM
• Modelo de diseño con los NDI según el EAIM indicado • Infraestructura TI necesaria
• Estándares y normas según especialidad Equipo con capacidades BIM respecto de:
• Hardware apto para procesar modelos BIM • Modelos BIM de las disciplinas: F-18, F-19, F-20, F-21, H-25, H-26, I-27, I-28, J-29, J-30*
• Infraestructura TI necesaria • Revisión de reglas normativas: E-15, E-17, J-29*
Equipo con capacidades BIM respecto de: Experiencia o conocimiento previo en:
• Modelos para evaluación de sustentabilidad: F-18, F-19, F-20, F-21, G-22, G-23, G-24, • Normativas aplicables
H-25, H-26, I-27, I-28, L-34*

Experiencia o conocimiento previo en:
• Estándares y normativas aplicables
• Diseño y construcción
• Sistemas y métodos constructivos

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Evaluación de sustentabilidad Tipos de Información aplicables para Validación normativa

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.
: Uso de BIM opcional para esta erapa.

92 93

<!-- p. 48 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\16. Planificación de obra 17. Diseño de sistemas constructivos
Proceso en el cual se utiliza uno o más modelos BIM para planificar, de manera gráfica, las actividades Proceso de diseño y análisis de la ejecución de sistemas de construcción complementarios (por
vinculadas a los elementos existentes, temporales y propuestos de un proyecto durante su construcción. ejemplo, soportes temporales, acristalamientos, etc.) para optimizar su planificación a través de uno o
Esto puede incluir el costo de mano de obra y los materiales, entre otros puntos. más modelos BIM.

Recursos sugeridos: Recursos sugeridos:
• Software de integración BIM que incorpore tiempo (4D) • Software de modelado BIM
• Software de planificación • Modelos BIM con los NDI correspondientes al EAIM indicado
• Modelos BIM con los NDI correspondientes al EAIM indicado • Estándares y normas según especialidad
• Hardware apto para procesar modelos BIM • Hardware apto para procesar modelos BIM
• Infraestructura TI necesaria • Infraestructura TI necesaria
Equipo con capacidades BIM respecto de: Equipo con capacidades BIM respecto de:
• Modelos de las disciplinas correspondientes: F-18, F-19, F-20, F-21, G-22, G-23, G-24, I-27, • Modelos para el diseño constructivo: F-18, F-19, F-20, F-21, G-22, G-23, G-24, H-25,
I-28* H-26, I-27, I-28*
• Herramientas de planificación y cronograma: K-31, K-32, K33*
Experiencia o conocimiento previo en:
Experiencia o conocimiento previo en: • Sistemas y métodos constructivos
• Coordinación de recursos de construcción • Prácticas de construcción apropiadas para cada sistema constructivo
• Diseño y construcción
• Sistemas y métodos constructivos

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Planificación de obra Tipos de Información aplicables para Diseño de sistemas constructivos

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.

94 95

<!-- p. 49 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\18. Fabricación digital 19. Control de obra
Proceso que utiliza información de uno o más modelos BIM para facilitar la fabricación de componentes Proceso de monitoreo, análisis, administración y optimización de la construcción, a través de uno o más
de construcción o ensamblajes. Algunos usos de la fabricación digital se pueden ver, por ejemplo, modelos BIM. El objetivo es asegurar que la construcción se realice según las especificaciones técnicas,
en la fabricación de chapa metálica, fabricación de acero estructural, corte de tuberías, creación de de acuerdo con las regulaciones, seguridad y requerimientos del propietario, así como para respaldar
prototipos para revisiones de intención de diseño, etc. La información de los modelos ayuda a asegurar los estados de pago de los avances logrados en cada hito de entrega parcial.
la precisión, así como también la reducción de desperdicios en la fase de fabricación.
Recursos sugeridos:
Recursos sugeridos: • Instrumentos de medición digital en obra
• Software de modelado BIM • Software BIM de Control de obra
• Modelos BIM con los NDI correspondientes al EAIM indicado • Modelos BIM con los NDI correspondientes al EAIM indicado
• Datos para máquina de fabricación • Estándares y normas según especialidad
• Equipos de fabricación • Hardware apto para procesar modelos BIM
• Estándares y normas según especialidad • Infraestructura TI necesaria
• Hardware apto para procesar modelos BIM Equipo con capacidades BIM respecto de:
• Infraestructura TI necesaria • Modelos de las disciplinas correspondientes: F-18, F-19, F-20, F-21, G-22, G-23, G-24,
Equipo con capacidades BIM respecto de: I-27, I-28*
• Modelos para fabricación digital: F-18, F-19, F-20, F-21, G-22, G-23, G-24, H-25, H-26, I-27, • Herramientas de planificación y control: K-31, K-32, K33, I-27*
I-28* Experiencia o conocimiento previo en:
• Diseño y construcción Experiencia o conocimiento previo en:
• Coordinación de recursos de construcción • Extraer información digital para fabricación
• Sistemas y métodos constructivos • Fabricar componentes de construcción utilizando información digital
• Matriz de riesgos • Sistemas y métodos constructivos
• Análisis de impactos (Tiempo/Costo)

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Fabricación digital Tipos de Información aplicables para Control de obra

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.

96 97

<!-- p. 50 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\20. Modelación as-built 21. Gestión de activos
Proceso de modelación en el que se representa de manera exacta las condiciones físicas de todos Proceso en el que un sistema de gestión organizado está vinculado bidireccionalmente a un modelo
los elementos que son parte de una edificación o infraestructura. Las entidades contienen toda la as-built, que puede estar conformado por uno o más modelos BIM, para ayudar de manera eficiente en el
información solicitada para los modelos, tal como códigos de barras, números de serie, garantías, mantenimiento y operación de un activo. Estos modelos BIM contienen información de la construcción
historial de mantenimiento, entre otros. física, los sistemas, el entorno circundante y los equipos, que se deben mantener, actualizar y operar
de manera eficiente y sustentable.
Recursos sugeridos:
• Software de modelado BIM Recursos sugeridos:
• Software o herramientas de manipulación de modelos BIM • Software de gestión de activos
• Software que permita el acceso a la información de lo construido • Sistema de registro de edificación e instalaciones de enlace bidireccional, entre el modelo
• Modelos BIM con los NDI correspondientes al EAIM indicado BIM y el software de gestión
• Base de datos del activo y/o equipos (según las capacidades del propietario) • Modelos BIM con los NDI correspondientes al EAIM indicado
• Hardware apto para procesar modelos BIM • Estándares y normas según especialidad
• Infraestructura TI necesaria • Hardware apto para procesar modelos BIM
• Infraestructura TI necesaria Equipo con capacidades BIM respecto de:
• Modelos de las disciplinas correspondientes: F-18, F-19, F-20, F-21, G-22, G-23, G-24, I-27, Equipo con capacidades BIM respecto de:
I-28* • Modelos BIM de las disciplinas: F-18, F-19, F-20, F-21, G-22, G-23, G-24, I-27*
• Herramientas de autoría: M-36, M-38* • Herramientas de gestión de activos: M-35, M-36, M-37, M-38, M-39, M-40*
Experiencia o conocimiento previo en: Experiencia o conocimiento previo en:
• Coordinación de los diferentes actores de diseño, construcción y administración del activo • Gestión financiera de activos
• Construcción y operación de una edificación o infraestructura (reemplazos, mejoras, etc.)
• Gestión de edificación o infraestructura
• Experiencia en eficiencia energética

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de información aplicables para Modelación as-built Tipos de Información aplicables para la Gestión de activos

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.

98 99

<!-- p. 51 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\22. Análisis de sistemas 23. Mantenimiento preventivo
Proceso en el cual se utiliza uno o más modelos BIM para el análisis del desempeño de un edificio Proceso en el cual se utiliza uno o más modelos BIM para desarrollar la mantención funcional de la
o infraestructura de acuerdo con el planteamiento de las especialidades en el diseño original. Esto estructura de una edificación o infraestructura (muros, columnas, pisos, techo, etc.) y su equipamiento
incluye cómo funcionan los diferentes sistemas mecánicos y cuanta energía utilizan. Otros análisis que (mecánico, sanitario, eléctrico, etc.) durante su operación. Un programa de mantenimiento exitoso puede
se pueden hacer incluyen incidencia solar en las fachadas, análisis lumínico y de radiación, cálculo de mejorar de manera significativa el desempeño del activo, reduciendo reparaciones y costos generales.
flujo de aire, entre otros.
Recursos sugeridos:
Recursos sugeridos: • Software o herramientas de manipulación de modelos BIM
• Software de análisis de sistemas • Modelos BIM con los NDI correspondientes al EAIM indicado
• Sistema de automatización de edificios vinculado al modelo as-built • Modelos BIM con los NDI correspondientes al EAIM indicado
• Sistema de administración de mantenimiento computarizado (CMMS por sus siglas en inglés) • Estándares y normas según especialidad vinculado al modelo as-built
• Hardware apto para procesar modelos BIM • Interfaz de panel de usuario vinculada al modelo as-built para proporcionar información de
• Infraestructura TI necesaria rendimiento del edificio o infraestructura
• Estándares y normas según especialidad
Equipo con capacidades BIM respecto de: • Hardware apto para procesar modelos BIM
• Modelos de las disciplinas correspondientes: F-18, F-19, F-20, F-21, I-27, I-28* • Infraestructura TI necesaria
• Herramientas operación y mantenimiento: M-35, M-36, M-37, M-38, M-39, M-40, M-41*
Equipo con capacidades BIM respecto de:
Experiencia o conocimiento previo en: • Modelos de las disciplinas correspondientes: F-18, F-19, F-20, F-21, G-22, G-23, G-24, I-27, I-28*
• Operación y mantenimiento de edificación o infraestructura • Herramientas operación y mantenimiento: M-35, M-36, M-37, M-38, M-39, M-40*
• Sistema de administración de mantenimiento computarizado (CMMS por sus siglas en inglés)
Experiencia o conocimiento previo en:
• Operación y mantenimiento de edificación o infraestructura
• Sistema de administración de mantenimiento computarizado (CMMS por sus siglas en inglés)

Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de Información aplicables para Análisis de sistema Tipos de Información aplicables para Mantenimiento preventivo

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.

100 101

<!-- p. 52 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO I FICHAS DE USOS BIM

\24. Gestión y seguimiento de espacios 25. Planificación y gestión de emergencias
Proceso de administración de los espacios y recursos relacionados a éstos dentro de una edificación o Proceso en el cual, a través de uno o más modelos BIM, se accede a la información crítica de la
infraestructura, a través de uno o más modelos BIM, que permiten al equipo de administración analizar edificación o infraestructura con el propósito de mejorar la eficiencia de respuesta ante una emergencia
el uso del espacio y planificar posibles cambios. Esto es particularmente útil en la remodelación o y minimizar los riesgos de seguridad. La información dinámica del activo sería proporcionada por un
ampliación de un proyecto durante la cual los espacios e instalaciones deben permanecer ocupados y BAS (por sus siglas en inglés, Building Automation System), mientras que la información de la edificación
en funcionamiento. estática, como planos de planta y esquemas de equipos, reside en el o los modelos BIM. El BIM junto
con el BAS pueden mostrar claramente dónde se localiza la emergencia dentro del edificio, las posibles
Recursos sugeridos: rutas hacia el área y cualquier otro lugar en riesgo dentro del activo.
• Sistema de registro del activo e instalaciones de enlace bidireccional, entre el modelo BIM y
el software de gestión Recursos sugeridos:
• Catastro de los recintos o zonas del activo • Software de revisión de modelos BIM as-built y sus entidades
• Software de gestión de activos empresariales (Enterprise Asset Management) • Sistema de automatización de edificios (BAS por sus siglas en inglés) vinculado al modelo BIM
• Modelos BIM con los NDI correspondientes al EAIM indicado as-built
• Estándares y normas según corresponda • Sistema de administración de mantenimiento computarizado (CMMS por sus siglas en inglés)
• Hardware apto para procesar modelos BIM vinculado al modelo as-built
• Infraestructura TI necesaria • Estándares y normas según corresponda
• Hardware apto para procesar modelos BIM Equipo con capacidades BIM respecto de:
• Infraestructura TI necesaria • Modelos BIM de las disciplinas: F-18, F-19, F-20, F-21, G-22, G-23, G-24, I-27, I-28*
• Herramientas de gestión y seguimiento de espacios: M-35, M-36, M-37, M-38, M-39, M-40* Equipo con capacidades BIM respecto de:
• Modelos BIM: F-18, F-19, F-20, F-21, G-22, G-23, G-24, I-27, I-28* Experiencia o conocimiento previo en:
• Herramientas de planificación y gestión de emergencias: L-34, M-35, M-36, M-37, M-38, • No aplica
M-39, M-40, M-41*
Experiencia o conocimiento previo en:
• No aplica
Etapas de proyecto en las que aplica el Uso BIM: Etapas de proyecto en las que aplica el Uso BIM:

PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN PLANIFICACIÓN DISEÑO CONSTRUCCIÓN OPERACIÓN

Tipos de Información aplicables para Gestión y seguimiento de espacios Tipos de Información aplicables para Planificación y gestión de emergencias

TDI_A TDI_B TDI_C TDI_D TDI_E TDI_A TDI_B TDI_C TDI_D TDI_E
Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones Información general Propiedades físicas y Propiedades Requerimientos específicos Especificaciones
del proyecto geométricas geográficas y de de información para el técnicas del proyecto geométricas geográficas y de de información para el técnicas
localización espacial fabricante y/o constructor localización espacial fabricante y/o constructor

TDI_F TDI_G TDI_H TDI_I TDI_J TDI_F TDI_G TDI_H TDI_I TDI_J
Requerimientos y Requerimientos Estándar Condiciones Validación de Requerimientos y Requerimientos Estándar Condiciones Validación de
estimación de costos energéticos sostenible del sitio y cumplimiento de estimación de costos energéticos sostenible del sitio y cumplimiento de
medioambientales programa medioambientales programa

TDI_K TDI_L TDI_M TDI_N TDI_O TDI_K TDI_L TDI_M TDI_N TDI_O
Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos Cumplimiento Requerimientos de fases, Logística y Entrega para la Gestión de activos
normativo secuencia de tiempo y secuencia de operación normativo secuencia de tiempo y secuencia de operación
calendarización construcción calendarización construcción

\*: Ver capacidades definidas para los Roles BIM en anexo II. *: Ver capacidades definidas para los Roles BIM en anexo II.

: Uso BIM opcional para esta etapa.

102 103

<!-- p. 53 -->

• 1 Contexto de la definición Roles y responsabilidades BIM .........................• 106
• 2 ¿Qué es un Rol BIM? ..................................................................................• 107
• 3 ¿Qué definen los Roles BIM? .....................................................................• 107
• 4 ¿Por qué necesitamos una definición de Roles BIM para la industria?• ..... 107
• 5 ¿Cómo se utiliza la Matriz de Roles BIM? ..................................................• 108
• 6 Acciones, responsabilidades y experiencia previa para cada Rol BIM• ...... 109
• 7 Matriz de Roles BIM ..................................................................................• 110 Anexo II
Matriz de Roles BIM

104 105

<!-- p. 54 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO II MATRIZ DE ROLES BIM

\2. ¿Qué es un Rol BIM?
Un Rol BIM es una función que se ejerce en alguna etapa de la planificación, diseño, construcción
y/u operación de una edificación o infraestructura, en base a capacidades BIM que se suman a las
capacidades no referidas a BIM.

• Un rol NO es un cargo
• Los roles BIM NO definen una nueva disciplina
• Los roles pueden ser desempeñados por personas existentes en un equipo si se capacitan
• Una persona SÍ puede ejercer más de un rol
• Un rol SÍ puede ser ejercido por varias personas
1 • Los roles definen capacidades BIM que se suman a las competencias de cada disciplina
\1. Contexto de la definición Roles y • Asumir un rol implica responsabilidades sobre determinadas acciones
responsabilidades BIM
Una de las brechas estructurales reconocidas por 3. ¿Qué definen los Roles BIM?
Planbim a través del Diagnóstico de la situación Al inicio de un proyecto que incorpora la metodología BIM, se deben seleccionar los Usos BIM Anexo II actual de formación de capital humano de BIM necesarios para cumplir los objetivos propuestos. Esos Usos BIM deben ser desarrollados por personas
en Chile⁴⁰, es que la industria de la construcción que cuentan con capacidades específicas para su ejecución y que tienen responsabilidades definidas
en Chile no contaba, en 2016, con una definición respecto de la información del proyecto. Esas capacidades y responsabilidades son definidas en los
de Roles BIM explícita y consensuada que Roles BIM, y están vinculadas a cada uno de los Usos a través de las Fichas de Usos BIM, incluidas en el
facilitara la adopción de esta metodología. Anexo I del presente estándar.
Esta definición es necesaria, ya que el uso de
metodología BIM obliga a incorporar nuevas
capacidades en las organizaciones. Por esto, el 4. ¿Por qué necesitamos una definición de Roles BIM para la industria? Matriz de año 2017 se desarrollaron cuatro mesas de trabajo La definición de Roles BIM permite, entre otros objetivos:
multisectoriales para generar una definición de
roles que luego fue plasmada, en noviembre del • Consensuar un lenguaje común entre los actores de la industria que permita y facilite el Roles BIM mismo año, en el documento Matriz de Roles BIM. trabajo colaborativo
En esta matriz, se definieron cinco roles, • Diferenciar las responsabilidades que asume cada actor participante de un proyecto y definir
nombrados de acuerdo con las responsabilidades explícitamente las capacidades BIM requeridas para ejercer un Rol BIM
BIM que asume cada uno de ellos, junto a cuarenta • Fomentar la enseñanza de la metodología BIM y de nuevas tecnologías para la gestión de la
y dos capacidades BIM requeridas por estos roles información de proyectos, promoviendo la capacitación tanto de la futura como de la actual
a lo largo del ciclo de vida de los proyectos. fuerza laboral
• Guiar a las instituciones de formación académica respecto de la actualización de sus mallas
curriculares, asegurando la pertinencia de los programas de estudios acorde a las necesidades
de la industria 4.0
• Guiar a las organizaciones y empresas en el diagnóstico de las capacidades BIM instaladas en
sus actuales equipos de trabajo y, por otra parte, facilitar la caracterización de brechas de
formación, que les permita desarrollar un plan de capacitación ajustado a sus requerimientos

40  PMG. Diagnóstico de la situación actual de formación de capital hu-
mano de BIM en Chile. Estudio de PMG para CORFO, 2016
106 107

<!-- p. 55 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO II MATRIZ DE ROLES BIM

\5. ¿Cómo se utiliza la Matriz de Roles BIM? 6. Acciones, responsabilidades y experiencia previa para cada Rol BIM
La Matriz presenta siete columnas y cuarenta y dos filas: En la siguiente tabla se define cada uno de los Roles BIM, de acuerdo a sus acciones y responsabilidades
relacionadas con BIM y experiencia previa sugerida.
• En la primera columna se describen catorce áreas temáticas sobre la metodología BIM, que
van a lo largo de todo el ciclo de vida de un proyecto y que sirven para agrupar las capacidades
• En la segunda columna se explican las 42 capacidades BIM Tabla Roles 01. Acciones, responsabilidades y experiencia previa para cada Rol BIM
• En cada celda de la tercera a la séptima columna se incorporan uno o más verbos que indican
la función que asume cada uno de los 5 Roles BIM, para cada una de las 42 capacidades BIM Rol BIM Acciones Experiencia o conocimiento
previo Para utilizar la Matriz de Roles BIM, se debe hacer un cruce entre Rol y capacidad BIM. Para esto
se debe: Conocimiento sobre los objetivos
técnicos y normativos del tipo de
A. Seleccionar la columna del Rol BIM a analizar proyecto, especialidad y etapa a
Visualizar y verificar la información (geometría y datos) de los revisar. Competencias en alguna de
B. Identificar la fila correspondiente a la capacidad y temática BIM modelos desarrollados en BIM, según la etapa del ciclo de vida las siguientes responsabilidades:
C. Desarrollar el cruce entre capacidad BIM y verbo definido para el Rol seleccionado, Revisión del proyecto (idea, diseño, construcción y operación). fiscalización, validación, auditoría,
anteponiendo el verbo específico que asume el Rol a la descripción de la capacidad BIM. Por en BIM control, desarrollo y/o ejecución
en base a la información obtenida
ejemplo, si tomamos el Rol de Revisión de Proyectos en BIM y la capacidad N°17 de la Matriz, de un proyecto.
la frase se construye así:
Desarrollar modelos BIM de proyectos según la especialidad,
Quien asuma el Rol de Revisión en BIM deberá ser capaz de Aplicar los estándares e utilizando diferentes tipos de representación y extracción de Conocimiento y competencias
instrumentos preestablecidos para la industria o desarrollados de forma interna, para el la documentación técnica de ellos. Dominar el intercambio de sobre los objetivos técnicos y
trabajo colaborativo y multidisciplinar. (Figura 6) la información en diferentes formatos. Modelar los elementos normativos del tipo de proyecto,
Modelación agregando o actualizando la información requerida. Usar y especialidad y etapa a modelar.
en BIM crear nuevas entidades.

Desarrollar el proceso de integración y flujo de información
entre los diferentes actores según la etapa de un proyecto.
Validar e integrar modelos de distintas especialidades,
Conocimiento y competencias
prever conflictos y conciliar soluciones. Comunicarse con los
sobre el desarrollo de proyectos,
especialistas para recopilar información y asegurar la correcta
Capacidades Dirección Revisión Modelación Coordinación Gestión los objetivos técnicos y normativos modelación del diseño. Organizar sesiones de coordinación
BIM en BIM en BIM en BIM en BIM en BIM del tipo de proyecto, especialidad
Coordinación entre las disciplinas. Configurar el entorno de modelación y etapa a coordinar. Liderazgo de
para desarrollar las entregas según lo especificado en el PEB. en BIM equipos.
Mantener el/los modelo(s) actualizado(s) y liviano(s). La(s)
persona(s) en este rol son el principal punto de contacto entre
los modeladores.
Aplicar los estándares Comprender Aplicar Aplicar Aplicar Desarrollar/
e instrumentos pre- Implementar Liderar la planificación, desarrollo y administración de los
establecidos para la E. RRHH y tecnológicos para la implementación y actualización industria o desarrollados
de forma interna, para de la metodología BIM en una organización, un proyecto Competencias en alguna de las 17 el trabajo colaborativo y o en la administración de un activo. Definir el entorno de siguientes responsabilidades:
multidisciplinar. modelación, los estándares que se usarán, los modelos que estandarización y optimización
se crearán, cómo se vincularán entre sí, cómo se ordenará y de procesos tecnológicos,
Gestión organizará la información en los modelos, la configuración planificación y administración
Figura 6. Ejemplo de definición de capacidad BIM según Rol en BIM de la infraestructura de TI y los protocolos de comunicación. de proyectos, operación y
Definir un cronograma para las entregas y organizar reuniones mantenimiento de activos.
del equipo BIM. La(s) persona(s) en este rol son el punto de Liderazgo de equipos.
contacto para el (los) gerente(s) del proyecto y para los diversos
coordinadores de un proyecto.

Liderar y fomentar la implementación de BIM en una
organización, de acuerdo a las necesidades, estrategias y toma Experiencia en gestión estratégica
de decisiones relativas a proyectos e inversiones, según la de proyectos y/o de organizaciones.
Dirección etapa del ciclo de vida del proyecto (idea, diseño, construcción Liderazgo.
en BIM y operación).

Elaborada por Planbim

108 109

<!-- p. 56 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO II MATRIZ DE ROLES BIM

\7. Matriz de Roles BIM
En la siguiente tabla se detallan las capacidades específicas de cada uno de los roles.

Tabla Roles 02. Matriz de Roles BIM Dirección Revisión Modelación Coordinación Gestión
Temáticas Capacidades BIM en BIM en BIM en BIM en BIM en BIM

Las características y déficit del modelo productivo tradicional de
Comprender / Comprender / 1 la industria de la construcción actual a nivel nacional e internacional Comprender Comprender Comprender Comunicar Comunicar
versus el modelo productivo BIM.
A
Pilares fundamentales del
Los pilares fundamentales de la metodología BIM relacionados con: Comprender / Comprender / Mandato Nacional BIM 2 Comprender Comprender Comprender estrategia, procesos y estándares, tecnologías y capital humano. Comunicar Comunicar
al 2020 en el contexto
internacional.
Comprender/ Comprender/ Las oportunidades en productividad, competitividad, sustentabilidad e 3 Comunicar / Comprender Comprender Comprender Comunicar / innovación que conlleva la implementación de la metodología BIM. Fomentar Fomentar

BIM como una metodología de trabajo colaborativo a lo largo de todo Comprender/ Comprender/
4 el ciclo de vida, considerando desde un inicio los requerimientos de Comunicar / Comprender Comprender Comprender Comunicar /
operación y mantenimiento de un proyecto. Fomentar Fomentar
B
Metodología BIM centrada Los beneficios que brinda BIM en términos de ahorro de costos, Comprender/ Comprender/
en el trabajo colaborativo a 5 tiempo y mayor productividad, considerando las limitantes y riesgos Planificar / Comprender Comprender Comprender Planificar /
lo largo de todo el ciclo de que implica su implementación. Comunicar Comunicar
vida de un proyecto.
Planificar / Los desafíos y cambios que implica Implementar una cultura de BIM y Comprender / 6 Comunicar / No aplica No aplica No aplica las responsabilidades para cada sector: público, privado y academia. Comunicar Fomentar

Comprender/ Los desafíos y cambios que implica Implementar BIM en una organización 7 Planificar / No aplica No aplica Comprender Comprender (trabajo colaborativo, flujo de información, etc.). Comunicar

Los Roles BIM y su caracterización de capacidades y responsabilidades, Planificar / 8 Comprender Comprender Comprender Comprender que deben ser integradas al capital humano de una organización. Implementar

Los requerimientos en cuanto a: rediseño de metodologías, procesos Validar / Planificar / 9 y estándares, habilitación de tecnologías e interoperabilidad y No aplica No aplica No aplica C Planificar Implementar capacitaciones, entre otros. Estrategias de
implementación de BIM
y la gestión del cambio Validar /
organizacional. 10 Las repercusiones legales y comerciales para la organización. Comunicar/ No aplica No aplica No aplica Comprender
Fomentar

Los desafíos para la adopción de BIM en una organización, tales como, Validar / Planificar / 11 crear condiciones para el éxito, mostrar logros a corto y mediano Comunicar / No aplica No aplica No aplica Implementar plazo, definir línea base y KPIs, entre otros. Fomentar

El cambio organizacional para la implementación de BIM, de acuerdo Validar / Planificar / 12 al nivel de madurez y rol de la organización dentro de la cadena de Comunicar / No aplica No aplica Comprender Implementar producción. Fomentar

110 111

<!-- p. 57 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO II MATRIZ DE ROLES BIM

Dirección Revisión Modelación Coordinación Gestión
Temáticas Capacidades BIM en BIM en BIM en BIM en BIM en BIM

Un sistema de trabajo colaborativo entre los actores de un proyecto, Validar / D Aplicar / Aplicar / Planificar /
Estrategia de comunicación 13 en base a protocolos de comunicación y seguridad, consulta, control, Comunicar / Validar Aplicar Validar Implementar revisión, validación y retroalimentación de la información. Fomentar de acuerdo a la Solicitud de
Información BIM (SDI BIM)
y el Plan de Ejecución BIM
El flujo de información definido por medio de la Solicitud de Información Desarrollar / (PEB), para coordinar el 14 Comprender Validar Aplicar Aplicar BIM (SDI BIM) y el Plan de Ejecución BIM (PEB). Implementar trabajo colaborativo.

Aplicar / Aplicar / 15 El marco normativo para el desarrollo de proyectos en BIM. Comprender Aplicar Validar Validar Validar
E
Marco normativo y El marco contractual entre los agentes participantes en el proyecto Comprender / 16 Comprender Aplicar No aplica Comprender estándares para el trabajo desarrollado en BIM, en relación a la fase del ciclo de vida. Aplicar
colaborativo y coordinado.

Los estándares e instrumentos preestablecidos para la industria
Desarrollar / 17 o desarrollados de forma interna, para el trabajo colaborativo y Comprender Aplicar Aplicar Aplicar Implementar
multidisciplinar.

La representación de la información geométrica de un proyecto en BIM Utilizar / 18 No aplica Desarrollar Desarrollar Validar mediante: planimetrías, visualizaciones 3D, renders, animaciones, etc. Validar

La representación de la información no geométrica de un proyecto en Utilizar / F 19 BIM mediante: reportes, planillas, tablas, etiquetas, cuadros de datos, No aplica Desarrollar Desarrollar Validar
Visualización y revisión de etc. Validar
la información estructurada
y actualizada de un
proyecto, según el flujo de Los diferentes formatos e interfaces de visualización de la información Planificar / 20 Utilizar Utilizar Utilizar Utilizar trabajo y entregables. de un proyecto por medio de dispositivos móviles. Implementar

La exportación e importación de plantillas y datos de proyectos en Utilizar / Planificar / 21 No aplica Comprender Desarrollar distintos formatos como: Excel, DWG, DWF, etc Desarrollar Implementar

La información geométrica de un modelo BIM, según Tipo de Información
(TDI), Nivel de Información (NDI) y Entregables BIM que se requieran en cada Utilizar / Planificar / 22 No aplica Desarrollar Desarrollar etapa y según cada especialidad (topografía, arquitectura, MEP, estructura, Validar Validar
etc.) G
Diseño y desarrollo de un La información no geométrica de un modelo BIM, según Tipo de
proyecto de edificación Información (TDI), Nivel de Información (NDI) y Entregables BIM que Utilizar / Planificar / 23 No aplica Desarrollar Desarrollar o infraestructura en base se requieran en cada etapa y según cada especialidad (topografía, Validar Validar
a modelos digitales y arquitectura, MEP, estructura, etc.)
paramétricos.
Las entidades pre-configuradas BIM que facilitan la estandarización e Desarrollar / Desarrollar / 24 No aplica Comprender Validar interoperabilidad de los proyectos. Aplicar Aplicar

112 113

<!-- p. 58 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO II MATRIZ DE ROLES BIM

Dirección Revisión Modelación Coordinación Gestión
Temáticas Capacidades BIM en BIM en BIM en BIM en BIM en BIM

Planificar / La personalización de la interfaz del software BIM, por medio de Utilizar / 25 No aplica Utilizar Utilizar Desarrollar / configuraciones predeterminadas y plantillas. Planificar H Implementar
Programación y
personalización de las
interfaces. Utilizar / Planificar / 26 La automatización de tareas y funciones en los software BIM utilizados. No aplica Utilizar Utilizar Desarrollar / Planificar Implementar

La exportación e importación de información entre sistemas BIM
Utilizar / Planificar / I 27 interoperables por medio de formato: IFC, LandXML, GIS, BCF, COBie, No aplica Utilizar Desarrollar Importación y exportación Desarrollar Implementar SQL, etc.
de modelos de proyectos
con datos paramétricos por
Los sistemas/plataformas de gestión de la comunicación e intercambio Planificar / medio de protocolos de
28 de información (Entorno de Datos Compartidos o CDE por sus siglas Comprender Utilizar Utilizar Utilizar Desarrollar / interoperabilidad.
en inglés). Implementar

La coordinación de los diferentes modelos BIM de un proyecto para Planificar / J 29 No aplica Validar No aplica Desarrollar Coordinación e integración evitar y/o detectar posibles incidencias, colisiones o conflictos. Validar
de información de
diferentes especialidades
de un proyecto, para prever Los informes sobre coordinación, interferencias y colisiones detectadas Validar / Planificar / 30 No aplica No aplica Desarrollar conflictos e interferencias. y/o posibles soluciones. Desarrollar Validar

La información del modelo ordenada de acuerdo a etapas (actividades
Planificar / 31 predecesoras y sucesoras) que permitan la coordinación según parti- No aplica No aplica Desarrollar Desarrollar Validar
das de obra y procesos productivos durante la construcción.
K
Planificación de la La estimación de los tiempos de un proyecto utilizando herramientas
Comunicar / Aplicar / Utilizar / Planificar / construcción de acuerdo 32 BIM de planificación, organización, programación y control de obras Comprender Fomentar Validar Desarrollar Validar
a costos, plazos y para la construcción.
programación de la obra.
La estimación de los costos de un proyecto utilizando herramientas
BIM para incrementar la precisión presupuestaria por medio de: cua- Comunicar / Aplicar / Utilizar / Planificar / 33 Comprender dro de precios, evaluación de costos, verificación de contratos, medi- Fomentar Validar Desarrollar Validar
ciones y cubicaciones para la construcción.
L
Optimización y simulación
anticipada de la operación El análisis sustentable y rendimiento energético para la optimización Comunicar / Utilizar / Planificar / 34 Validar Utilizar y mantenimiento de un del proyecto por medio de herramientas BIM. Fomentar Desarrollar Validar
proyecto durante su vida
útil.

114 115

<!-- p. 59 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO II MATRIZ DE ROLES BIM

Dirección Revisión Modelación Coordinación Gestión
Temáticas Capacidades BIM en BIM en BIM en BIM en BIM en BIM

La información necesaria para monitorear el comportamiento y man- Utilizar / Planificar / 35 No aplica Validar Desarrollar tenimiento de un activo. Desarrollar Validar

La información as-built necesaria para la gestión, mantenimiento y ex- Planificar / 36 No aplica Validar Desarrollar Planificar plotación de un activo. Validar

Los datos para calcular, seguir y reportar indicadores de uso, tiempo y
costos para la operación del activo. (ej: rendimiento del diseño, ajuste Utilizar / Planificar / 37 No aplica Validar Desarrollar a normativa y estándares, información de fabricantes y proveedores, Desarrollar Validar
M costos de reemplazo, períodos de cambio y mantenciones, etc.).
Operación y
mantenimiento de un La actualización de entidades, datos y procesos en los modelos BIM, ej: Utilizar / Planificar /
activo de infraestructura 38 piezas, equipamientos y sistemas, registrando su historial que permite No aplica Validar Desarrollar Desarrollar Validar
o edificación hasta su trazabilidad.
desmantelamiento.

El seguimiento y monitoreo de datos de manera planificada y periódica Comunicar / Utilizar / Planificar / 39 Validar Desarollar para una adecuada operación y control logístico del activo. Fomentar Desarrollar Implementar

La información para la estrategia de consumo y ahorros durante el ciclo Utilizar / Planificar / 40 No aplica Validar Desarollar de vida, plan de mantenimiento técnico y optimización. Desarrollar Validar

La información para la planificación de desastres y preparación ante la Utilizar / Planificar / 41 No aplica Validar Desarollar posibilidad de evacuación u otras emergencias. Desarrollar Validar

N
Alcances de la Era de la La actualización permanente del capital humano de la organización Comunicar / Planificar / Información y el valor de la 42 Comprender Comprender Comprender respecto de avances tecnológicos en la industria. Fomentar Implementar
actualización y formación
continua.

Elaborado por Planbim

116 117

<!-- p. 60 -->

Este manual⁴¹ es una guía de doce pasos a realizar
en los modelos BIM, que permiten compartir e
intercambiar información de manera estructurada
durante todo el ciclo de vida de una edificación
o infraestructura, considerando la utilización
de estándares openBIM. Este documento fue
desarrollado por un grupo de empresas del sector
de la construcción de los Países Bajos, en conjunto Anexo III
con BIM Loket y buildingSMART Benelux - Bélgica,
Holanda y Luxemburgo -, ambas instituciones sin
fines de lucro.

Este manual permite asegurar la disponibilidad Manual Básico de Entrega y posible reutilización de la información de
los modelos BIM de manera más eficiente, y
es utilizado en el Estándar BIM para Proyectos
Públicos como parte del conjunto mínimo de de Información (MEI) datos a solicitar por las instituciones públicas,
para garantizar entregables BIM de calidad.1

41 BIM Loket. https://www.bimloket.nl/BIMbasicIDM

118 119

<!-- p. 61 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO III MANUAL BÁSICO DE ENTREGA DE INFORMACIÓN BIM (MEI)

3.4 USO CORRECTO DE LAS ENTIDADES 3.5 ESTRUCTURA Y DENOMINACIÓN 3.6 SISTEMA DE CLASIFICACIÓN
Utilice el tipo más apropiado de entidad Estructure y nombre de manera Aplique el sistema de clasificación
BIM, tanto en la aplicación de origen como consistentemente los objetos. existente usado en el país.
en la entidad de IFC. Introduzca correctamente el tipo Asigne a cada objeto el código que
Ejemplo: losa = ifcSlab, muro = ifcWall, de objeto (ifcType, ifcObjectType o corresponda, del sistema de clasificación MANUAL BÁSICO DE ENTREGA DE INFORMACIÓN MEI viga = ifcBeam, columna = ifcColumn, ifcObjectTypeOverride). seleccionado.
escalera = ifcStair, puerta = ifcDoor, etc.
Cuando corresponda, introduzca también
correctamente el Nombre (ifcName o
NameOverride)
Ejemplo: aislamiento de techo, tipo: fibra de
vidrio.
ifcStair ifcObjectType 0 0 0 0
\1. ¿POR QUÉ ESTAMOS COMPARTIENDO ESTA INFORMACIÓN SIN AMBIGÜEDADES? CLASSIFICATION SYSTEM
Para asegurar y reutilizar la información de manera más eficiente y efectiva.

3.7 INDIQUE EL MATERIAL CORRECTO DE LOS 3.8 DUPLICADOS E INTERSECCIONES JUNTOS APRENDEMOS A
OBJETOS No se permiten duplicados o intersecciones. HABLAR EL MISMO IDIOMA
Asegúrese de comprobarlo en IFC. Asigne a los objetos una descripción del
material (ifcMaterial) Al denominar objetos, considere si el nombre Eliminar tareas ineficientes cumple con los siguientes criterios. Hablar el mismo lenguaje Ejemplo: Piedra caliza
Verifíquelo y sepa qué información está
compartiendo.

ifcMaterial
\2. ¿CÓMO VAMOS A COMPARTIR ESTA INFORMACIÓN SIN AMBIGÜEDADES? SignificativaComprensible ClaraCoherente
El conocimiento y las experiencias prácticas han demostrado que existe un importante denominador común. Lógica Reconocible
No estamos desarrollando algo nuevo, sino más bien utilizando estructuras existentes, basadas en openBIM IFC.

NUEVO NUEVO 4. CÓMO PODEMOS ASEGURAR LA DISPONIBILIDAD DE LA INFORMACIÓN
NUEVO SOBRE LOS OBJETOS PARA SU FUTURO USO? NUEVO NUEVO ifc La información sobre los objetos se asegura utilizando correctamente las propiedades y conjuntos de propiedades definidos en IFC.
NUEVO

4.1 ELEMENTO DE CARGA/NO DE CARGA
Asigne la propiedad LoadBearing a los objetos,
cuando corresponda [Verdadero/Falso].
\3. ¿QUÉ ESTRUCTURA UTILIZAREMOS? Ifc conjunto de propiedades
Los acuerdos enumerados a continuación ayudan a garantizar que cada parte involucrada siempre Pset_BeamCommon Pset##Common; LoadBearing
podrá encontrar y proporcionar la información correcta en el lugar correcto. LoadBearing
Pset##Common; IsExternal

Ejemplo: para vigas, las propiedades FireRating, Pset##Common; FireRating
Lista de control del manual de entrega de información básica LoadBearingPset_BeamCommon.y IsExternal forman parte de ....

3.1 NOMBRE DEL ARCHIVO 3.2 POSICIÓN Y ORIENTACIÓN LOCAL 3.3 NIVELES DEL PROYECTO Y SU DENOMINACIÓN 4.2 ELEMENTOS EXTERIORES 4.3 RESISTENCIA AL FUEGO 4.4 PROYECTO ESPECÍFICO
los pisos o niveles del Modelo BIM solo Asegúrese de utilizar una denominación La posición local del edificio o Nombre Asigne la propiedad IsExternal qué propiedades IFC está a los objetos, Asigne la propiedad FireRating a los Defina como: ifcBuildingStorey-Name. uniforme y coherente para los modelos infraestructura debe estar coordinada [Verdadero/Falso]. cuando corresponda utilizando para cada proyecto específico. objetos, cuando corresponda. Asigne todos los objetos o componentes al nivel (por disciplina) dentro del proyecto. y cercana al origen.
correcto. Consejo: las caras interiores y exteriores de la Consejo: aplicar el estándar existente utilizado Utilice un objeto físico como punto de Ejemplo: \<Edificio>_\<Disciplina>_\<Componente> Consejo: Dentro de un proyecto, asegúrese de que todas fachada tienen la propiedad IsExternalTrue. en el país correspondiente. origen, situado en 0.0.0, y expórtelo también a IFC.
las partes involucradas usen exactamente la
misma denominación, que esta se pueda clasificar
numéricamente y tenga una descripción textual.
Ejemplo 1: 00 nivel de acceso IsExternal FireRating Pset_##Common
Ejemplo 2: 01 primer nivel
xx min.

IfcProject
ifcBuildingStorey-Name

0.0.0 Con licencia de Creative Commons BY-SA 4.0, de BIM Loket.
Puede consultar el texto completo de la licencia en https://creativecommons.org/licenses/by-sa/4.0/

1/2 Manual básico de entrega de información MEI - versión 1.0
2/2 Manual básico de entrega de información MEI - versión 1.0

120 121

<!-- p. 62 -->

• Introducción................................................................................................................• 126
• •
• A Empresas participantes..............................................................................• 126
• •
• B Objetivos y Usos BIM..................................................................................• 127
• B.1 Objetivos de la utilización de BIM en el proyecto........................• 127
• B.2 Usos BIM (PEB de Oferta)...............................................................• 128 Anexo IV • B.3 Recursos, capacidades y experiencia previa para cada Uso •
BIM requerido.................................................................................• 128
• •
• C Entregables BIM y sus formatos................................................................• 129
• C.1 Modelos BIM solicitados y sus formatos (PEB de Oferta)................• 129
• C.2 EAIM para cada entrega.................................................................• 130 Plantilla para Plan de
• C.3 Documentos solicitados y sus formatos (PEB de Oferta)..............• 131
• •
• D Estrategia de colaboración.........................................................................• 132 Ejecución BIM de Oferta • D.1 Entorno de Datos Compartidos (CDE)..........................................• 132
• D.2 Consolidación de modelos BIM......................................................• 132
•

122 123

<!-- p. 63 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO IV PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DE OFERTA

Plan de Ejecución BIM de Oferta

Información del proyecto

Solicitante:
Nombre del proyecto:
Ubicación del proyecto:
Tipo de contrato:
Descripción del proyecto:
Número de contrato:
Número del proyecto:

A continuación, se incluye una plantilla para la
generación del Plan de Ejecución BIM de Oferta.
Ésta debe ser completada por los Proveedores Nº de documento:
Oferentes en el marco de las entregas Anexo IV
requeridas en la Solicitud de Información BIM. Fecha:
La versión digital de esta plantilla se encuentra
en el repositorio digital de Planbim⁴². Revisión:

Estado:
Plantilla
Hoja de control del documento

Revisión Estatus Página Enmienda Fecha Por para Plan de
Ejecución
BIM de
Oferta

42 https://planbim.cl/biblioteca/documentos/.
124 125

<!-- p. 64 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO IV PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DE OFERTA

Introducción B. Objetivos y Usos BIM
En el Plan de Ejecución BIM de Oferta (PEB de Oferta) los Proveedores Oferentes deben demostrar su
estrategia de utilización de BIM para el proyecto, así como las capacidades y competencias tanto de su B.1 Objetivos de la utilización de BIM en el proyecto
empresa como su cadena de suministro para cumplir con los requisitos de información del Solicitante
Indique el objetivo general y los objetivos específicos que se señalan en la Solicitud de Información BIM indicados en la Solicitud de Información BIM (SDI BIM).
e incorpore los Usos BIM que se relacionan a cada objetivo. Para más información, ver 5.1 del Estándar
La información entregada a través del PEB debe cumplir con lo indicado en el Estándar BIM para BIM para Proyectos Públicos.
Proyectos Públicos: Intercambio de Información entre Solicitante y Proveedores.
Formulario 02 PEB de Oferta. Objetivo general de la utilización de BIM en el proyecto
A. Empresas participantes
Objetivo general
Indique las empresas que participarán en el proyecto.

Formulario 01 PEB de Oferta. Empresas participantes Ej.: El objetivo de la utilización de BIM es prevenir errores o modificaciones críticas sobre el cronograma y presupuesto
aprobado.
Empresa Especialidad Código Nombre del responsable

Ej: Architop Ej: Proyecto de Arquitectura Ej: ARQ Ej: Juan Muñoz

Ej: Gerenciatop Ej: Gerenciamiento Ej: GER Ej: Alejandra Pérez

Formulario 03 PEB de Oferta. Objetivos específicos de la utilización de BIM en el proyecto

Objetivos específicos Usos BIM relacionados

Ej: Obtener las cantidades y costos de componentes del proyecto Ej: Estimación de cantidades y costos.

Declaración del Proveedor Oferente
La información entregada en el presente Plan de Ejecución BIM por parte del Proveedor Oferente ha
sido acordada por los representantes del equipo del proyecto mencionados anteriormente, quienes
cuentan con la autorización de sus empresas para validar este documento y su uso dentro del proyecto.

126 127

<!-- p. 65 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO IV PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DE OFERTA

B.2 Usos BIM (PEB de Oferta) C. Entregables BIM y sus formatos
Indique, para cada Uso BIM, la empresa y el Rol principal dentro de esa empresa de quien se hará cargo
de su desarrollo. Para más información, ver 5.6 del Estándar BIM para Proyectos Públicos. C.1 Modelos BIM solicitados y sus formatos (PEB de Oferta)

Indique, para cada modelo BIM, la especialidad a la que corresponde, los formatos que se usarán para su
desarrollo e intercambio entre proveedores, quién lo desarrollará y quién estará a cargo de su control
de calidad. Para más información, ver 5.3 del Estándar BIM para Proyectos Públicos.

Formulario 04 PEB de Oferta. Usos BIM Formulario 05 PEB de Oferta. Modelos BIM solicitados y sus formatos

Uso BIM Empresa Rol BIM Modelos BIM Especialidad Autor de modelo Responsable Formato nativo

Ej: Levantamiento de Condiciones Existentes Ej: MasterTop Ej: Gestión BIM Ej: Volumétrico Ej: Proyecto de Arquitectura Ej: ARQ Ej: ARQ Ej: PLN
Ej: Diseño de Especialidades Ej: Arquitop Ej: Gestión BIM

B.3 Recursos, capacidades y experiencia previa para cada Uso BIM requerido
Indique, para cada Uso BIM solicitado en la SDI BIM, los recursos que utilizará para el logro de los
Usos señalados anteriormente. Para esto, se deben utilizar los formularios de Recursos de los equipos,
creados para cada Uso BIM, que se encuentran en las plantillas de PEB disponibles en el repositorio
digital de Planbim⁴³. En estos formularios, se deben indicar cómo cumple el Proveedor con los recursos,
capacidades y experiencia previa para cada Uso BIM, referidos en las Fichas de Usos BIM en el Anexo I.

128 129
43 https://planbim.cl/biblioteca/documentos/

<!-- p. 66 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO IV PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DE OFERTA

C.2 Estado de Avance de la Información de los Modelos BIM para cada entrega C.3 Documentos solicitados y sus formatos (PEB de Oferta)
Indique para cada modelo el EAIM que corresponda para entrega según lo indicado en la SDI BIM. Para Indique para cada entrega su fecha y los Estados de Avance de la Información de los Modelos
más información, ver 5.5 del Estándar BIM para Proyectos Públicos. correspondientes para cada uno de los entregables solicitados. Para más información, ver 5.4 del
Estándar BIM para Proyectos Públicos.

Formulario 06 PEB de Oferta. EAIM para cada entrega Formulario 07 PEB de Oferta. Documentos solicitados y sus formatos

Proyecto:
Estado de Avance de la Información
(insertar nombre del proyecto) Entrega Entrega Entrega Entrega Entrega Entrega Entrega Entrega Fecha del Modelo (EAIM) Entregable
(insertar fecha) 01 02 03 04 05 06 “N”
Ej.: Etapa 01 Ej.: 02-03-2018 Ej.: Diseño Anteproyecto Ej.: Planimetría maestra
Modelos BIM EAIM EAIM EAIM EAIM EAIM EAIM EAIM

Ej: DA Ej: DA Ej: DA Ej: DA
Ej: DB Ej: DB
Diseño Diseño Diseño Diseño Sitio Diseño Diseño
Antepro- Antepro- Antepro- Antepro-
Básico Básico
yecto yecto yecto yecto

Ej: DC Ej: DA Ej: DA
Ej: DB Ej: DB Ej: DB
Diseño Diseño Diseño Volumétrico Diseño Diseño Diseño
Concep- Antepro- Antepro-
Básico Básico Básico
tual yecto yecto

Ej: DC Ej: DA
Ej: DB Ej: DB Ej: DD Ej: DD
Diseño Diseño Arquitectura Diseño Diseño Diseño de Diseño de
Concep- Antepro-
Básico Básico Detalle Detalle
tual yecto

Ej: DC Ej: DA
Ej: DB Ej: DB Ej: DD
Diseño Diseño Estructura Diseño Diseño Diseño de
Concep- Antepro-
Básico Básico Detalle
tual yecto
Mecánico, Eléctrico y Ej: DC Ej: DA Ej: DB Ej: DB
Diseño Diseño Sanitario (MEP por su Diseño Diseño
Concep- Antepro- siglas en inglés) Básico Básico
tual yecto

Ej: DC Ej: DA
Ej: DB
Diseño Diseño Coordinación Diseño
Concep- Antepro-
Básico
tual yecto

Construcción

As-built

Operación

130 131

<!-- p. 67 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS

D. Estrategia de colaboración

D.1 Entorno de Datos Compartidos (CDE)

Indique si el CDE está compuesto por una o múltiples plataformas tecnológicas, cuáles son y qué
formatos se utilizará para los requerimientos de información y colaboración. Para más información, ver
5.8.1 del Estándar BIM para Proyectos Públicos.

Formulario 08 PEB de Oferta. Entorno de Datos Compartidos

El CDE utilizado está conformado por una sola plataforma

Sí No

Plataformas y formatos del Entorno de Datos Compartidos

Entorno de Datos Compartidos (CDE): Ej.: CDE MASTER

Plataforma de colaboración: Ej.: BIMCollab

Plataforma de gestión documental: Ej.: G-Drive

Formato de requerimientos de información y
Ej.: Archivos BCF
colaboración:

D.2 Consolidación de modelos BIM

Indique la estrategia de consolidación de modelos que utilizará. Para más información, ver 5.8.2 del
Estándar BIM para Proyectos Públicos.

Formulario 09 PEB de oferta. Generación de modelos BIM

Estrategia SI NO

Modelo BIM federado Ej: X

Modelo BIM integrado

132 133

<!-- p. 68 -->

• Introducción..........................................................................................................• 138
• •
• A Empresas participantes.........................................................................• 138
• •
• B Objetivos y Usos BIM...............................................................................• 139
• B.1 Objetivos de la utilización de BIM en el proyecto.......................• 139
• B.2 Usos BIM (PEB definitivo).............................................................• 140 Anexo V • B.3 Recursos, capacidades y experiencia previa para cada Uso•
BIM requerido............................................................................• 140
• •
• C Entregables BIM y sus formatos...............................................................• 141
• C.1 Modelos BIM solicitados y sus formatos (PEB definitivo).....• 141
• C.2 EAIM para cada entrega.............................................................• 142 Plantilla para Plan de
• C.3 Documentos solicitados y sus formatos (PEB definitivo)............• 143
• •
• D Estrategia de colaboración ....................................................................• 144 Ejecución BIM Definitivo • D.1 Entorno de Datos Compartidos (CDE)........................................• 144
• D.2 Consolidación de modelos BIM...................................................• 144
• D.3 Procedimiento de reuniones (solo PEB definitivo) .....................• 145
• •
• E Organización de los modelos BIM.............................................................• 146
• E.1 Estructuración de los modelos BIM (solo PEB definitivo)............• 146
• E.2 Nombres de archivos de los modelos BIM (solo PEB Definitivo)..• 147
• E.3 Colores de disciplinas y sistemas (solo PEB definitivo)...............• 148
• E.4 Sistema de clasificación (solo PEB definitivo)...........................• 149
•

134 135

<!-- p. 69 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO V PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DEFINITIVO

Plan de Ejecución BIM Definitivo

Información del proyecto

Solicitante:
Nombre del proyecto:
Ubicación del proyecto:
Tipo de contrato:
Descripción del proyecto:
Número de contrato:
Número del proyecto:

A continuación, se incluye una plantilla para la
generación del Plan de Ejecución BIM Definitivo. Nº de documento:
Ésta debe ser completada por el Proveedor
Adjudicado en el marco de las entregas Fecha: Anexo V
requeridas en la Solicitud de Información BIM. La
Revisión: versión digital de esta plantilla se encuentra en el
repositorio digital de Planbim⁴⁴. Estado:

Hoja de control del documento Plantilla

Revisión Estatus Página Enmienda Fecha Por para Plan de
Ejecución
BIM Definitivo

44 https://planbim.cl/biblioteca/documentos/.

136 137

<!-- p. 70 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO V PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DEFINITIVO

Introducción B. Objetivos y Usos BIM
En el Plan de Ejecución BIM Definitivo (PEB Definitivo) el Proveedor Adjudicado debe demostrar su
estrategia de utilización de BIM para el proyecto, así como las capacidades y competencias tanto de su B.1 Objetivos de la utilización de BIM en el proyecto
empresa como su cadena de suministro para cumplir con los requisitos de información del Solicitante
Indique el objetivo general y los objetivos específicos que se señalan en la Solicitud de Información BIM indicados en la Solicitud de Información BIM (SDI BIM).
e incorpore los Usos BIM que se relacionan a cada objetivo. Para más información, ver 5.1 del Estándar
La información entregada a través del PEB Definitivo debe cumplir con lo indicado en el Estándar BIM BIM para Proyectos Públicos.
para Proyectos Públicos: Intercambio de Información entre Solicitante y Proveedores.
Formulario 02 PEB Definitivo. Objetivo general de la utilización de BIM en el proyecto
A. Empresas participantes
Objetivo general
Indique las empresas que participarán en el proyecto.

Formulario 01 PEB Definitivo. Empresas participantes Ej.: El objetivo de la utilización de BIM es prevenir errores o modificaciones críticas sobre el cronograma y presupuesto
aprobado.
Empresa Especialidad Código Nombre del responsable

Ej: Architop Ej: Proyecto de Arquitectura Ej: ARQ Ej: Juan Muñoz

Ej: Gerenciatop Ej: Gerenciamiento Ej: GER Ej: Alejandra Pérez

Formulario 03 PEB Definitivo. Objetivos específicos de la utilización de BIM en el proyecto

Objetivos específicos Usos BIM relacionados

Ej.: Prevenir conflictos críticos entre las distintas especialidades
Ej: Coordinación 3D
del proyecto

Declaración del Proveedor Adjudicado
La información entregada en el presente Plan de Ejecución BIM por parte del Proveedor Adjudicado ha
sido acordada por los representantes del equipo del proyecto mencionados anteriormente, quienes
cuentan con la autorización de sus empresas para validar este documento y su uso dentro del proyecto.

138 139

<!-- p. 71 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO V PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DEFINITIVO

B.2 Usos BIM (PEB Definitivo) C. Entregables BIM y sus formatos
Indique los principales contactos de cada organización que participa en el proyecto en relación con
cada Uso BIM. Agregue el correo electrónico de cada contacto, así como el rol que desempeña dentro C.1 Modelos BIM solicitados y sus formatos (PEB Definitivo)
de su empresa. Se pueden incluir personas adicionales más adelante en el documento. Para más
Indique, para cada modelo BIM, la especialidad a la que corresponde, los formatos que se usarán para su información, ver 5.6 del Estándar BIM para Proyectos Públicos.
desarrollo e intercambio entre proveedores, quién lo desarrollará y quién estará a cargo de su control
de calidad. Para más información, ver 5.3 del Estándar BIM para Proyectos Públicos.

Formulario 04 PEB Definitivo. Usos BIM Formulario 05 PEB Definitivo. Modelos BIM solicitados y sus formatos

Formato de Persona
intercambio Uso BIM Empresa Rol BIM responsable Disciplina Profesión Correo electrónico
Autor de Formato entre Resp. control
Modelo BIM Especialidad modelo Responsable nativo proveedores de calidad
Ej.: Levan-
tamiento de Ej.: Mas- Ej.: Ges- Ej.: Juan Ingeniero
TOP juanlopez@mail.com Ej.:.IFC / MVD Condiciones terTop tión BIM López Geomensor Ej.: Proyecto de
Ej.: Volumétrico Ej.: ARQ Ej.: ARQ Ej.:.PLN Coordination Ej.: GER Existentes Arquitectura
view 2.0
Ej.: Diseño de
Ej.: Arqui- Ej.: Direc- Ej.: Esteban estebantorres@
Especialida- ARQ Arquitecto
top ción BIM Torres correo.com
des

B.3 Recursos, capacidades y experiencia previa para cada Uso BIM requerido
Indique, para cada Uso BIM solicitado en la SDI BIM, los recursos que utilizará para el logro de los
Usos señalados anteriormente. Para esto, se deben utilizar los formularios de Recursos de los equipos,
creados para cada Uso BIM, que se encuentran en las plantillas de PEB que se encuentran en las plantillas
de PEB disponibles en el repositorio digital de Planbim⁴⁵. En estos formularios, se deben indicar cómo
cumple el Proveedor con los recursos, capacidades y experiencia previa para cada Uso BIM, referidos
en las Fichas de Usos BIM en el Anexo I.1

140 45 https://planbim.cl/biblioteca/documentos/ 141

<!-- p. 72 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO V PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DEFINITIVO

C.2 Estado de Avance de Información de Modelos BIM para cada Entrega C.3 Documentos solicitados y sus formatos (PEB Definitivo)
Indique para cada modelo el EAIM que corresponda para entrega según lo indicado en la SDI BIM. Para Indique para cada entrega su fecha, los Estados de Avance de la Información de los Modelos
más información, ver 5.5 del Estándar BIM para Proyectos Públicos. correspondiente para cada uno de los entregables solicitados con su formato, versión y si se extraerá
directamente de un modelo o no. Esto último no aplica a los entregables que son modelos. Para más
información, ver 5.4 del Estándar BIM para Proyectos Públicos.

Formulario 06 PEB Definitivo. EAIM para cada entrega Formulario 07 PEB Definitivo. Documentos solicitados y sus formatos

Proyecto: Estados de Avance de Formato
la Información de los Desde (insertar nombre del proyecto) Entrega Entrega Entrega Entrega Entrega Entrega Entrega
Entrega Fecha Modelos (EAIM) Entregable Nativo Versión Entrega modelo (insertar fecha) 01 02 03 04 05 06 “N”

Modelos BIM EAIM EAIM EAIM EAIM EAIM EAIM EAIM Ej.: Etapa Ej.: 02- Ej.: Diseño Anteproyecto Ej.: Planime- Ej.: Ej.: 2015 Ej.: PDF Ej.: Si
01 03-2018 tría maestra RVT

Ej: DA Ej: DA Ej: DA Ej: DA
Ej: DB Ej: DB
Diseño Diseño Diseño Diseño Sitio Diseño Diseño
Antepro- Antepro- Antepro- Antepro-
Básico Básico
yecto yecto yecto yecto

Ej: DC Ej: DA Ej: DA
Ej: DB Ej: DB Ej: DB
Diseño Diseño Diseño Volumétrico Diseño Diseño Diseño
Concep- Antepro- Antepro-
Básico Básico Básico
tual yecto yecto

Ej: DC Ej: DA
Ej: DB Ej: DB Ej: DD Ej: DD
Diseño Diseño Arquitectura Diseño Diseño Diseño de Diseño de
Concep- Antepro-
Básico Básico Detalle Detalle
tual yecto

Ej: DC Ej: DA
Ej: DB Ej: DB Ej: DD
Diseño Diseño Estructura Diseño Diseño Diseño de
Concep- Antepro-
Básico Básico Detalle
tual yecto
Mecánico, Eléctrico y Ej: DC Ej: DA Ej: DB Ej: DB
Diseño Diseño Sanitario (MEP por su Diseño Diseño
Concep- Antepro- siglas en inglés) Básico Básico
tual yecto

Ej: DC Ej: DA
Ej: DB
Diseño Diseño Coordinación Diseño
Concep- Antepro-
Básico
tual yecto

Construcción

As-built

Operación

142 143

<!-- p. 73 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO V PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DEFINITIVO

D. Estrategia de colaboración D.3 Procedimiento de reuniones (solo PEB Definitivo)
Indique las principales reuniones de trabajo y coordinación que se realizarán a lo largo del proyecto y
D.1 Entorno de Datos Compartidos (CDE) sus participantes. Para más información, ver 5.8.3 del Estándar BIM para Proyectos Públicos.

Indique si el CDE está compuesto por una o múltiples plataformas tecnológicas, cuáles son y qué
formatos se utilizarán para los requerimientos de información y colaboración. Para más información,
ver 5.8.1 del Estándar BIM para Proyectos Públicos.

Formulario 08 PEB Definitivo. Entorno de Datos Compartidos Formulario 10 PEB Definitivo. Procedimiento de reuniones

Especiali- Frecuencia El CDE utilizado está conformado por una sola plataforma
Tipo de Etapa del dades que de Cantidad de Tipo de
reunión proyecto participan reuniones * reuniones Ubicación Modalidad respaldo
Sí No
Ej.: Inicio de Ej.: Oficina
requerimien- Ej.: Diseño • ARQ 15 días 5 central Presencial Minuta
tos BIM • CAL cliente
Plataformas y formatos del Entorno de Datos Compartidos Ej.:
Oficina
• ARQ
Ej.: Revisión central
Ej.: Diseño • CAL 45 días indefinido Presencial Minuta
del PEB Coordinador
• ELE
Entorno de Datos Compartidos (CDE): Ej.: CDE MASTER de proyecto • CLI
Ej.:
Oficina
Ej.: Coordi- • ARQ Presencia
central Minuta y
nación del Ej.: Diseño • CAL 15 días 8 y video Plataforma de colaboración: Ej.: BIMCollab Coordinador video
Diseño • ELE conferencia
de proyecto
• CLI
Ej.: Cualquier
Plataforma de gestión documental: Ej.: G-Drive otra reunión Según video Minuta y Todas Todas 30 días indefinido
BIM con múl- disponibilidad conferencia video
tiples partes

Formato de requerimientos de información y
Ej.: Archivos BCF
colaboración: (*) La cantidad y frecuencia de las reuniones puede cambiar en virtud de la dinámica del proyecto.

D.2 Consolidación de modelos BIM
Indique la estrategia de consolidación de modelos que utilizará. Para más información, ver 5.8.2 del
Estándar BIM para Proyectos Públicos.

Formulario 09 PEB Definitivo. Generación de modelos BIM

Estrategia SI NO

Modelo BIM federado Ej: X

Modelo BIM integrado

144 145

<!-- p. 74 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO V PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DEFINITIVO

E. Organización de los modelos BIM E.2 Nombres de archivos de los modelos BIM (solo PEB Definitivo)
Indique la estructura a utilizar para los nombres de archivos de modelo. Para más información, ver 5.9.2
E.1 Estructuración de los modelos BIM (solo PEB Definitivo) del Estándar BIM para Proyectos Públicos.

Indique la estructura que tendrán los modelos BIM en el proyecto. Para más información, ver 5.9.1 del Proyecto-Organización-Disciplina-Zona-Nivel-Tipo de Documento-Número-Estatus(*)-Revisión(*).xyz
Estándar BIM para Proyectos Públicos.
Ejemplo: PR1-ABC-ARQ-Z1-01-MO-0001-C-A.xyz

Nota: xyz se refiere a la extensión de formato del archivo

Formulario 11 PEB Definitivo. Estructuración de los modelos BIM Formulario 12 PEB Definitivo. Nombre de archivos de los modelos BIM

Unidades que utilizará para el desarrollo Coordenadas que se utilizarán para todos los modelos BIM Modelo BIM Nombre
de los modelos BIM

Ej.: Sitio Ej.: PR1-ABC-TOP-ZZ-ZZ-MO-0001-C-A.xyz

Ej.: Se debe utilizar las coordenadas locales 0, 0, 0 del software.
Ej.: Las unidades serán metros con tres (3) Estas coordenadas deben estar vinculadas al punto de intersección Ej.: Arquitectura Ej.: PR1-ABC-ARQ-ZZ-ZZ-MO-0001-C-A.xyz
decimales de los ejes A y 1. Además, se debe incorporar a cada modelo una
entidad (IfcBuildingElementProxy) relacionada a esas coordenadas.

Sistema de subdivisión de los modelos, en caso de ser necesario

Modelo BIM Por Edificio Por Pisos Por Zonas Por Área Por Disciplina

Ej.: Sitio X

Ej.: Volumétrico X X

Ej.: Arquitectura X X

146 147

<!-- p. 75 -->

ESTÁNDAR BIM PARA PROYECTOS PÚBLICOS ANEXO V PL ANTILL A PARA PL AN DE EJECUCIÓN BIM DEFINITIVO

E.3 Códigos y colores por disciplinas y/o sistema (solo PEB Definitivo) E.4 Sistema de clasificación (solo PEB Definitivo)
Indique los colores a utilizar para las distintas disciplinas y/o entidades de modelo. Para más información, Indique el sistema de clasificación a utilizar en los modelos BIM en el proyecto. Para más información,
ver 5.9.2.4 del Estándar BIM para Proyectos Públicos. ver 5.9.3 del Estándar BIM para Proyectos Públicos.

Formulario 13 PEB Definitivo. Códigos y colores por disciplinas y/o sistema Formulario 14 PEB Definitivo. Sistema de clasificación

Sistema de clasificación a utilizar
Disciplina Sigla Color R G B

Ej: Arquitectura Ej:ARQ Ej:255 Ej:255 Ej:255 Ej.: El sistema de clasificación a utilizar es Omniclass

Ej: Audio y Acústica Ej:ACU Ej:255 Ej:255 Ej:255

Ej: Cálculo Estructural Ej:EST Ej:255 Ej:255 Ej:255

Ej: Carga Combustible Ej:CCB Ej:255 Ej:255 Ej:255

Ej: Redes de Combustibles Ej:RCB Ej:255 Ej:255 Ej:255

Ej: Escapes de gases Ej:EDG Ej:255 Ej:255 Ej:255

Ej: Circuito Cerrado de TV Ej:CTV Ej:255 Ej:255 Ej:255

Ej: Climatización Ej:CLI Ej:255 Ej:255 Ej:255

Ej: Inyección de Aire Ej:INY Ej:255 Ej:255 Ej:255

Ej: Extracción de Aire Ej:EXT Ej:255 Ej:255 Ej:255

Ej: Retorno de Aire Ej:RET Ej:255 Ej:255 Ej:255

Ej: Aire Fresco Ej:FRE Ej:255 Ej:255 Ej:255

Ej: Refrigerante Ej:REF Ej:255 Ej:255 Ej:255

Ej: Equipos Ej:EQU Ej:255 Ej:255 Ej:255

Ej: Evacuación Condensación Ej:CON Ej:255 Ej:255 Ej:255

Ej: Arquitectura Ej:ARQ Ej:255 Ej:255 Ej:255

148 149

<!-- p. 76 -->

• Banco Central, Memoria Anual, 2017. http://www.bcentral.cl/es/web/guest/-/memoria-anual-2017

• BIM Forum USA. Level of Development Specification, 2015. https://store.bimforum.org/BIMForum/Store/StoreLayouts/ Bibliografía Item_Detail.aspx?iProductCode=7803&CATEGORY=BIM_PRODS
• British Standards Institute. BS1192 Collaborative Produccion of architectural, engineering and construction information - Code
of Practice. London: BSI, 2007.

• -. BS1192-4 Fulfilling employer’s information exchange requirements using COBie - Code of Practice. London: BSI, 2014.

• BuildingSMART International. buildingSMART International home of openBIM. 2018. https://www.buildingsmart.org/about/
what-is-openbim/ifc-introduction/ (último acceso abril de 2018).

• Eastman, Chuck and others. BIM Handbook: A Guide to Building Information Modeling for Owners, Managers, Designers,
Engineers and Contractors, 2nd Edition. 2012, 2011.

• IALE. “Estudio de Identificación de Demanda de Capital Humano con Capacidades BIM en la Industria de la Construcción.”
Estudio, Santiago, 2017.

• Instituto Nacional de Normalización. NCh 1 Normas Chilenas NCh - Definiciones y procedimientos para su estudio y mantención.
Santiago: INN, 2011.

• —. NCh2 - Guía para la redacción de normas Chilenas. Santiago: INN, 2006.

• International Standardization Organization. ISO 16739 Industry Foundation Classes (IFC) for data sharing in the construction and
facility management industries. Suiza: ISO, 2013.

• —. ISO/IEC Guide 2 - Standardization and related activities - General Vocabulary. Suiza: ISO, 2004.

• —. ISO10241 International terminology standards - Preparation and layout. Suiza: ISO, 1992.

• —. ISO12006-2 Building construction - Organization of information about construction works - Part 2: Framework for
classification. Suiza: ISO, 2015.

• —. ISO12006-3 Building construction - Organization of information about construction works - Part 3: Framework for object
oriented information. Suiza: ISO, 2007.

• —. ISO 19650-1 Organization and digitization of information about buildings and civil engineering works, including building
information modelling (BIM) -- Information management using building information modelling -- Part 1: Concepts and
principles. Suiza: ISO, 2018.

• —. ISO 19650-2 Organization and digitization of information about buildings and civil engineering works, including building
information modelling (BIM) -- Information management using building information modelling -- Part 2: Delivery phase of
the assets. Suiza: ISO, 2018.

• —. ISO 29481-1 Building Information models - Information delivery manual - Part 1: Methodology and format. Suiza: ISO, 2016.

• —. ISO29481-2 Building Information Models - Information delivery manual - Part 2: Interaction framework. Suiza: ISO, 2012.

• Kreider, Ralph G, and Jhon I. Messner. The uses of BIM: Classifying and Selecting BIM Uses, Versión 0.9. The Pennsylvania State
University, 2013.

• McKinsey&Company, Productividad laboral en Chile ¿Cómo estamos? Presentación IRADE, 28-11-2013. https://irade.cl/wp-
content/uploads/2013/12/Rodrigo_Alcoholado.pdf.

• Proyect Management Institute. Guía de los fundamentos para la dirección de proyectos - Gúia PMBoK - Sexta Edición. PMI
Institute, 2017.

• Succar, Billal. BIM Dictonary. s.f. https://bimdictionary.com/es/bimmodel/1/ (último acceso: Mayo 2018).

• —. BIM Dictonary. n.d. https://bimdictionay.com/es/model-component/1/ (último acceso: 02 de Mayo de 2018).

• The American Institute of Architects. G202-2013 - Project Building Information. AIA, 2013.

• U.S. Department of Veterans Affairs. The VA BIM Guide v1.0. Department of Veterans Affairs, 2010.

150 151

<!-- p. 77 -->


