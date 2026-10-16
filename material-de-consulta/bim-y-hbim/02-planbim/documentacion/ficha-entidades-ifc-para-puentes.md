---
type: libro
title: "Ficha Entidades IFC para Puentes"
author: "Sebastián Manríquez"
categoria: "BIM Y HBIM"
paginas: 11
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/02. Planbim/documentación/Ficha Entidades IFC para Puentes.pdf"
convertido: 2026-10-16
---

# Ficha Entidades IFC para Puentes

> Texto extraído de `BIM Y HBIM\02. Planbim\documentación\Ficha Entidades IFC para Puentes.pdf` (11 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

FICHA DE
ENTIDADES IFC
PARA PUENTES

Según ISO 16739-1:2018
VERSIÓN 2.0

Mayo 2020

<!-- p. 2 -->

Esta obra está licenciada bajo la Licencia Creative Commons
Atribución-NoComercial 4.0 Internacional.
Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/.

1

<!-- p. 3 -->

1 ÍNDICE

1 ÍNDICE ............................................................................................................................................................................ 2

2 INTRODUCCIÓN ............................................................................................................................................................ 3

3 ESTRUCTURA DE UN PUENTE .......................................................................................................................................... 5

Estribo ...................................................................................................................................................................... 6

Cepa ....................................................................................................................................................................... 7

Tablero .................................................................................................................................................................... 8

2

<!-- p. 4 -->

2 INTRODUCCIÓN

El esquema de información Industry Foundation Classes (IFC, por sus siglas en inglés), es un estándar abierto
para la especificación e intercambio de información de la industria de la construcción. Su utilización ha crecido
de forma exponencial en los últimos años, y un gran número de software BIM han incorporado en sus flujos de
trabajo la importación y exportación de información en este formato. El esquema está en un constante
desarrollo, actualizando sus contenidos e incorporando elementos y parámetros de tipologías no incluidas en un
comienzo. En específico, la actualización que suma toda la información particular de puentes se encuentra
publicado para revisión, y se espera que sea oficializada en los próximos meses.

En sus esfuerzos por impulsar la implementación de la metodología BIM por parte de las instituciones
públicas, Planbim ha creado un Estándar que toma los principales elementos de los documentos y normas más
relevantes de la industria a nivel internacional, adaptándolos al contexto nacional.

Para asegurar que la información intercambiada por los distintos participantes de un proyecto sea
interoperable y estandarizada, el Estándar BIM para Proyectos Públicos adopta el esquema IFC, utilizándolo
como base para especificar los elementos que componen los distintos modelos BIM, el Tipo de Información (TDI)
que estos deben contener según los objetivos a cumplir, y el Nivel de Información (NDI) aplicable para cada
etapa de un proyecto.

Para facilitar la aplicación del esquema Ifc en tipologías que utilizan elementos constructivos particulares,
como es el caso del Departamento de Puentes de la Dirección de Vialidad del Ministerio de Obras Públicas, se
elabora la presente Ficha de Entidades para Puentes. Este documento muestra en una tabla los elementos
específicos de la tipología con su entidad IFC equivalente, y el tipo predefinido que mejor representa su función
(si corresponde). Además, para mayor claridad, se incluye un esquema conceptual de cada parte de la
estructura con la misma información de la tabla.

Para esta versión del presente documento, se hará alusión a las entidades incluidas en la versión IFC 4.0.2.1
(IFC 4 ADD2 TC1), que corresponde a la publicada en la ISO 16739-1:2018. A su vez, para precisar la función que
cumple cada elemento en una estructura de puente, se utilizó el tipo predefinido (Type Enum) USERDEFINED
(definido por usuario). Esto nos permite ingresar en este campo el nombre del tipo predefinido que será
especificado en la versión Ifc Bridge, próxima a publicarse. Por ejemplo, en la versión oficial de Ifc 4, la entidad
Muro (IfcWall) no tiene un tipo predefinido para Muro de Contención (RETAININGWALL), por lo que se deja este
parámetro como USERDEFINED (definido por usuario), y se utiliza el atributo Tipo de Objeto (Object Type) para
especificar esta información. Una vez que se oficialice la actualización del esquema que incorpora este tipo
predefinido, se puede actualizar la información de los modelos sin que esto implique un gran esfuerzo. Esto
muestra en las siguientes imágenes:

ESQUEMA GENERAL

ENTIDAD
ENTITY

TIPO PREDEFINIDO
TYPE ENUM

TIPO DE OBJETO
OBJECT TYPE

Fig.1- Una entidad representa una categoría de elementos, definidas por propiedades comunes. El tipo predefinido es un listado de tipos
de elementos derivados de una entidad, y que usualmente corresponden a los más utilizados. El tipo de objeto es el parámetro que nos permite
definir manualmente el nombre del elemento derivado de una entidad que necesitamos.

3

<!-- p. 5 -->

ESQUEMA IFC 4 (OFICIAL)

MURO

 MOVIBLE
 PARAPETO
 PARTICIÓN
 SÓLIDO

 DEFINIDO POR USUARIO TIPO DE OBJETO: CONTENCIÓN
USERDEFINED
 NO DEFINIDO
NOTDEFINED

Fig. 2 – En el esquema IFC 4 Oficial, una entidad general como un muro puede especificarse según un listado de los tipos más utilizados
(TypeEnum). En este listado también encontraremos la opción de que el usuario ingrese el tipo específico (USERDEFINED), o podemos dejarlo sin
definición (NOTDEFINED). De seleccionar la opción USERDEFINED, se utiliza el atributo Object Type para ingresar la información correspondiente.
Para el caso del muro de contención, debemos utilizar esta última opción, ya que el esquema actual no incluye este tipo predefinido.

ESQUEMA IFC BRIDGE (CANDIDATO)

MURO

 MOVIBLE
 PARAPETO
 PARTICIÓN
 SÓLIDO
 CONTENCIÓN
 DEFINIDO POR USUARIO
 NO DEFINIDO

Fig. 3 – En el esquema IFC BRIDGE, actualmente en proceso de revisión, la entidad general muro puede especificarse directamente según
el listado de los tipos más utilizados (TypeEnum), pues en esta versión se incorpora el tipo de muro de CONTENCIÓN.

Para comprender cómo se ordena la información en el esquema Ifc, revisar las distintas versiones, y las
definiciones básicas de sus miembros y características, se recomienda revisar la página oficial de buildingSmart
https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/ .

4

<!-- p. 6 -->

3 ESTRUCTURA DE UN PUENTE

Podemos subdividir un puente en tres grandes estructuras. Cada una de ellas tiene su propia entidad Ifc, y a su
vez se descomponen en elementos constructivos:

\1. Estribo
\2. Cepa
\3. Tablero

3

1

2

5

<!-- p. 7 -->

Estribo

Español Inglés IFC 4 Oficial TypeEnum
Estructura Estribo Abutment IfcElementAssembly USERDEFINED / ABUTMENT

Espaldar Back-wall IfcWall USERDEFINED / RETAININGWALL

Elementos Alas Wing-wall IfcWall USERDEFINED / RETAININGWALL
constructivos
Muro frontal Stem-wall IfcWall USERDEFINED / RETAININGWALL

Espaldar (Back-wall)
Entidad: IfcWall
Tipo Predef: USERDEFINED
/ RETAININGWALL
Alas (Wing-wall)
Entidad: IfcWall
Tipo Predef: USERDEFINED
/ RETAININGWALL
Muro Frontal (Stem Wall)
Entidad: IfcWall
Tipo Predef: USERDEFINED
/ RETAININGWALL
Fundación (Pile Cap)
Entidad: IfcFooting
Tipo Predef: USERDEFINED
/ PILE_CAP Pilotes (Pile)
Entidad: IfcPile
Tipo Predef: BORED

6

<!-- p. 8 -->

Cepa

Español Inglés Ifc 4 Oficial TypeEnum
Estructura Cepa Pier IfcElementAssembly USERDEFINED / PIER

Cabezal Pier Cap IfcBeam USERDEFINED / PIERCAP

Elevación Pier IfcColumn USERDEFINED / PIERSTEM
Elementos Dado de fundación Pile Cap IfcFooting PILE_CAP
constructivos
Pilotes Pile IfcPile BORED

Cabezal (Pier Cap)
Entidad: IfcBeam
Tipo Predef: USERDEFINED / PIERCAP

Elevación (Pier Stem)
Entidad: IfcColumn
Tipo Predef: USERDEFINED /
PIERSTEM

Pilotes (Pile)
Entidad: IfcPile
Dado de fundación (Pile Cap) Tipo Predef: BORED
Entidad: IfcFooting
Tipo Predef: USERDEFINED / PILE_CAP

7

<!-- p. 9 -->

Tablero

Español Ingles Ifc 4 Oficial TypeEnum
Estructura Tablero Bridge Deck IfcElementAssembly USERDEFINED / DECK

Pavimento Pavement IfcSlab USERDEFINED / PAVING

Losa puente Deck Slab IfcSlab
USERDEFINED / GIRDER
Viga Girder IfcBeam
SEGMENT
Travesaño Diaphragm IfcBeam USERDEFINED / DIAPHRAGM

Dispositivo de apoyo Bearing IfcMechanicalFastener USERDEFINED / BEARING

Barra de anclaje Anchor bar IfcReinforcingBar ANCHORING

Tope sísmico externo External shear key IfcWall USERDEFINED / RETAININGWALL

Tope sísmico interno Internal shear key IfcWall USERDEFINED / RETAININGWALL Elementos
constructivos Junta dilatación Expansion Joint IfcDiscreteAccesory USERDEFINED /
EXPANSION_JOINT_DEVICE
USERDEFINED /
Losa de acceso Approach slab IfcSlab
APPROACH_SLAB
Barrera de contención Bridge rail IfcWall PARAPET

Baranda Guardrail IfcRailing GUARDRAIL

Pavimento (Pavement) Tope sísmico interno (Internal Shear Key)
Entidad: IfcSlab Entidad: IfcWall
Tipo Predef: USERDEFINED / PAVING Tipo Predef: USERDEFINED / RETAININGWALL

Dispositivos de apoyo (Bearing) Barras de anclaje (Anchor Bar) Tope sísmico external (External shear key)
Entidad: IfcMechanicalFastener Entidad: IfcReinforcingBar Entidad: IfcWall
Tipo Predef: USERDEFINED / BEARING Tipo Predef: ANCHORING Tipo Predef: USERDEFINED / RETAININGWALL

8

<!-- p. 10 -->

Junta de dilatación/expansión (Expansion Joint)
Entidad: IfcDiscreteAccesory
Tipo Predef: USERDEFINED / EXPANSION_JOINT_DEVICE
Losa de acceso (Aproach Slab)
Entidad: IfcSlab
Tipo Predef: USERDEFINED / APROACH_SLAB Baranda (Guardrail/Railing)
Entidad: IfcRailing
Tipo Predef: GUARDRAIL

Travesaño (Diaphragm)
Entidad: IfcBeam
Tipo Predef: USERDEFINED / DIAPHRAGM

Barrera de contención (Bridge Rail)
Entidad: IfcWall
Tipo Predef: PARAPET

9

<!-- p. 11 -->

www.planbim.cl

in

10
