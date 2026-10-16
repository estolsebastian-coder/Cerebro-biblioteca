---
type: libro
title: "Problem 1-006"
author: "Nancy"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 18
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/curso SAP 2000/Problem 1-006.pdf"
convertido: 2026-10-16
---

# Problem 1-006

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\curso SAP 2000\Problem 1-006.pdf` (18 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006
FRAME - NON-PRISMATIC SECTIONS AND AUTOMATIC FRAME SUBDIVISION

EXAMPLE DESCRIPTION
This example tests the SAP2000 non-prismatic frame section property. In
SAP2000 the axial (A), torsion (J), weight, and mass properties can vary linearly,
and the bending property (I) variation can be linear, parabolic or cubic. The
variation of the moment of inertia is defined in SAP2000 as follows:

L
where,
n n = 1 for linear variation,  1 / n x  1 / n  x   I1 I2 I ( x ) = ( I 1 ) − 1  + (I 2 )   n = 2 for parabolic variation, and   L   L  
n = 3 for cubic variation,
x

The example model consists of a complex, non-prismatic frame section that is
made up of four segments, assigned to a cantilever beam, and subjected to seven
load cases, each with a different type of loading. An applicable deformation
component at the free end of the cantilever is compared with independent hand
calculated results for each load case.

Important Note: Only bending and axial deformations are considered in the
analysis. Shear deformations are ignored. In SAP2000 this is achieved by setting
the property modification factor for shear area to 0.

This example also tests the frame automatic subdivide feature of SAP2000. The
automatic frame subdivide option internally divides the frame object into a user-
specified number of elements for the analysis. The analysis results are combined
and reported for the entire frame object, not the subdivided elements.

In this example two models are run. Model A has no automatic subdivision.
Model B has automatic subdivision that divides the frame object up into 10 equal
length elements. The results are compared for each model.

EXAMPLE 1-006 - 1

<!-- p. 2 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

GEOMETRY, PROPERTIES AND LOADING

144"
Material Properties 36" 36" 36" 36"
E = 3,600 k/in2
ν = 0.2
Seg. 1 Seg. 2 Seg. 3 Seg. 4 G= 1,500 k/in2
Unit weight = 0.15 k/ft3
Z 4 3 2 2 3 1 1 2

Y FSec FSec FSec FSec FSec FSec FSec FSec

X

Segment Definitions

Segment 1 Segment 2 Segment 3 Segment 4

Start Section FSec4 FSec2 FSec3 FSec1

End Section FSec3 FSec2 FSec1 FSec2

Length, in 36 36 36 36

Axial (A) Variation Linear Constant Linear Linear

Bending (I33) Variation Linear Constant Parabolic Cubic

Bending (I22) Variation Linear Constant Parabolic Cubic

Torsion (J) Variation Linear Constant Linear Linear

EXAMPLE 1-006 - 2

<!-- p. 3 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

Section Properties

FSec1 FSec2 FSec3 FSec4

Width b, in 12 12 12 12

Depth d, in 12 18 24 30

Area A, in2 144 216 288 360

Bending I33, in4 1728 5832 13824 27000

Bending I22, in4 1728 2592 3456 4320

Torsion J, in4 2,920.32 6,085.12 9,492.12 12,934.73

Loading

Load Case Load Type Value

1 Self weight Not Applicable

2 Fx at free end (axial) 500 k

3 Fy at free end 5 k

4 Fz at free end -5 k

5 Mx at free end (torsion) 5,000 k-in

6 My at free end 5,000 k-in

7 Mz at free end 5,000 k-in

EXAMPLE 1-006 - 3

<!-- p. 4 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

TECHNICAL FEATURES OF SAP2000 TESTED
¾ Structural behavior of a non-prismatic frame section
 Self weight calculations
 Linear variation of section area
 Linear, parabolic and cubic variation of moment of inertia
 Linear variation of section torsional constant
¾ Automatic frame subdivision

RESULTS COMPARISON
Independent results are hand calculated using the unit load method described on
page 244 in Cook and Young 1985.

Results for Model A (With No Automatic Subdivision)

Load Output Percent
Case Parameter SAP2000 Independent Difference

1 My (fixed end)k-in -184.950 -184.950 0%

2 Ux (free end) in 0.09087 0.09087 0%

3 Uy (free end) in 0.43120 0.43120 0%

4 Uz (free end) in -0.14335 -0.14335 0%

5 Rx (free end) rad 0.07987 0.07987 0%

6 Ry (free end) rad 0.03742 0.03742 0%

7 Rz (free end) rad 0.07634 0.07634 0%

EXAMPLE 1-006 - 4

<!-- p. 5 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

Results for Model B (With Automatic Subdivision into Ten Elements)

Load Output Percent
Case Parameter SAP2000 Independent Difference

1 My (fixed end)k-in -184.950 -184.950 0%

2 Ux (free end) in 0.09087 0.09087 0%

3 Uy (free end) in 0.43120 0.43120 0%

4 Uz (free end) in -0.14335 -0.14335 0%

5 Rx (free end) rad 0.07987 0.07987 0%

6 Ry (free end) rad 0.03742 0.03742 0%

7 Rz (free end) rad 0.07634 0.07634 0%

COMPUTER FILE: Example 1-006a, Example 1-006b

CONCLUSION
The SAP2000 results show an exact match with the independent results for both
models A and B.

EXAMPLE 1-006 - 5

<!-- p. 6 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

HAND CALCULATION

EXAMPLE 1-006 - 6

<!-- p. 7 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 7

<!-- p. 8 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 8

<!-- p. 9 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 9

<!-- p. 10 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 10

<!-- p. 11 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 11

<!-- p. 12 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 12

<!-- p. 13 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 13

<!-- p. 14 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 14

<!-- p. 15 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 15

<!-- p. 16 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 16

<!-- p. 17 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 17

<!-- p. 18 -->

COMPUTERS &
STRUCTURES
INC.

R Software Verification
PROGRAM NAME: SAP2000
REVISION NO.: 0

EXAMPLE 1-006 - 18
