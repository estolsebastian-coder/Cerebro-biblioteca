---
type: libro
title: "Indicecompleto"
author: "lauri"
categoria: "ESTRUCTURA"
paginas: 6
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/ESTRUCTURA/BIELAS Y TIRANTES/Indicecompleto.pdf"
convertido: 2026-10-16
---

# Indicecompleto

> Texto extraído de `ESTRUCTURA\BIELAS Y TIRANTES\Indicecompleto.pdf` (6 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Ejemplos para el Diseño de
Hormigón Estructural usando
Modelos de Bielas y Tirantes

Preparado por Miembros del Subcomité 445-1, Modelos de Bielas y Tirantes,
para las reuniones de la Convención realizada en Phoenix, entre el 27 de
octubre y el 1 de noviembre, 2002, y auspiciado por el Comité Conjunto ACI-
ASCE 445, Corte y Torsión, y el Comité ACI 318-F, Corte y Torsión

Editor
Kart-Heinz Reineck

<!-- p. 2 -->

ii

Se pueden presentar comentarios sobre los trabajos de este simposio de acuerdo con los
requisitos generales de las Políticas de Publicación de ACI, enviándolos a las oficinas
centrales de ACI ubicadas en la dirección que se indica a continuación. La fecha de cierre
para la recepción de comentarios es Junio de 2003. Todos los comentarios aprobados por el
Comité de Actividades Técnicas, junto con los comentarios finales de los autores, serán
publicados en la edición de setiembre/octubre ya sea del ACI Structural Journal o el ACI
Materials Journal, dependiendo del tema central de cada trabajo.

El Instituto no se responsabiliza por las declaraciones u opiniones expresadas en sus
publicaciones. Las publicaciones del Instituto no pueden ni deben ser sustituto de la
capacitación individual, la responsabilidad profesional ni el buen criterio del usuario, ni del
proveedor, de la información presentada.

Los trabajos incluidos en este volumen han sido revisados de acuerdo con los
procedimientos de publicación del Instituto por personas expertas en los temas cubiertos
por cada trabajo.

Copyright  2002
AMERICAN CONCRETE INSTITUTE
P.O. Box 9094
Farmington hills, Michigan 48333-9094

Todos los derechos reservados, incluyendo los derechos de reproducción y utilización en
cualquier forma y por cualquier medio, incluyendo cualquier proceso fotográfico o
dispositivo de copiado electrónico o mecánico, impreso o escrito u oral, o el registro
sonoro o reproducción visual para su utilización en cualquier sistema o dispositivo de
reproducción o conocimiento, sin el consentimiento escrito de los propietarios del
copyright.

ISBN: 0-87031-086-0

<!-- p. 3 -->

iii

Prefacio

El nuevo Apéndice A de ACI 318-2002 sobre modelos de bielas y tirantes proporciona
una excelente herramienta para diseñar hormigón estructural cuando no se pueden aplicar
procedimientos de diseño seccional para flexión y corte. Este es el caso de las regiones de
discontinuidad (regiones D), las cuales, si no están detalladas correctamente, pueden sufrir
daño estructural y aún fallas de tipo frágil. Esta publicación especial presenta ejemplos del
uso de modelos de bielas y tirantes siguiendo el Apéndice A de ACI 318-2002 para diseñar
regiones D tales como ménsulas, vigas de gran altura con y sin aberturas, vigas con
extremos entallados, vigas con apoyos indirectos, zonas de anclajes de miembros
pretensados, muros de cortante con aberturas, tableros en pilas de un puente y cabezales de
pilotes.
Las contribuciones y ejemplos fueron preparados por miembros del Subcomité ACI 445A Corte y Torsión: Modelos de Bielas y Tirantes y presentados en la Convención realizada
en Phoenix, entre el 27 de octubre y el 1 de noviembre, 2002, auspiciada por el Comité
Conjunto ACI-ASCE 445: Corte y Torsión y el Subcomité ACI 318-E: Corte y Torsión. Los
trabajos contenidos en esta publicación especial han sido revisados de acuerdo con las
políticas del American Concrete Institute. Se agradece la cooperación de los autores en la
preparación de los manuscritos y su revisión.
También se agradece el esfuerzo de los encargados de las revisiones y del personal de
las oficinas centrales de ACI, especialmente el Sr. Todd Watson, Gerente de Documentos
Técnicos.
Finalmente, el editor desea agradecer a Cathy French, Presidente del Comité ACI-ASCE
445, y Jim Wight, anteriormente Presidente del Subcomité ACI 318E, por su apoyo
constante al trabajo realizado por el Subcomité ACI 445-A y esta publicación especial.

Kart-Heinz Reineck
Editor y Presidente del Subcomité ACI 445-A Corte y Torsión: Modelos de Bielas y
Tirantes
ILEK, Univesidad de Stuttgart, Alemania

Subcomité ACI 445-A Corte y Torsión: Modelos de Bielas y Tirantes

Miembros: Sergio M. Alcocer, Robert B. Anderson, Robert W. Barnes, Jay Holombo,
Gary J. Klein, Daniel Kuchma, Denis Mitchell, Kart H. Reineck (Presidente), Julio A.
Ramírez, Mario Rodríguez, David Sanders, Sri S. Sritharan, Claudia M. Uribe, Fernando
Yanez.

Miembros Asociados: Dat Duthinh, Mary Beth D. Hueste, Laura Lowes, Adolfo B.
Matamoros, Khaled A. Nahlawi, Lawrence C. Novak, Philip K. H. Tan, Neil Wexler.

<!-- p. 4 -->

iv

Miembros Correspondientes: John E. Breen, James G. MacGregor, James O. Jirsa, James
Lefter, James K. Wight.

<!-- p. 5 -->

v

Ejemplos para el diseño de hormigón estructural usando
modelos de bielas y tirantes

Contenidos

Prefacio iii

Parte 1: Introducción 1
Kart – Heinz Reineck

Parte 2: Derivación de modelos de bielas y tirantes
para el Código ACI 2002 7
James G. MacGregor

Parte 3:Verificación experimental de modelos de bielas y tirantes 41
Denis Mitchell, William D. Cook, Claudia M. Uribe, y Sergio Alcocer

Parte 4: Ejemplos 63

Ejemplo 1a: Diseño de una viga de gran altura de acuerdo con ACI 318-02 65
Claudia M. Uribe y Sergio Alcocer

Ejemplo 1b: Diseño alternativo para la viga no esbelta (viga de gran altura) 81
Tjen N. Tjhin y Daniel A. Kuchma

Ejemplo 2: Viga T con extremos entallados soportada por una viga T invertida 91
David Sanders

Ejemplo 3.1: Ménsula en una columna 105
Tjen N. Tjhin y Daniel A. Kuchma

Ejemplo 3.2: Ménsula doble 117
Tjen N. Tjhin y Daniel A. Kuchma

Ejemplo 4: Viga de gran altura con una abertura 129
Lawrence C. Novak y Heiko Sprenger

Ejemplo 5: Viga con cargas y apoyos indirectos 143
Wiryanto Dewobroto y Karl-Heinz Reineck

Ejemplo 6: Viga pretensada 165
Adolfo Matamoros y Julio A. Ramirez

<!-- p. 6 -->

vi

Ejemplo 7: Modelo de bielas y tirantes para el tablero de un puente atirantado 185
Bob Anderson

Ejemplo 8: Muro de gran altura con dos aberturas 195
Robert W. Barnes

Ejemplo 9: Cabezal de pilotes 213
Gary J. Klein

Parte 5:

Kart-Heinz Reineck 225
