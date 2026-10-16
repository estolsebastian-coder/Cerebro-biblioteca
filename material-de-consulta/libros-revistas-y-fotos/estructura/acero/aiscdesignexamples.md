---
type: libro
title: "AISC Design Examples v13.0"
author: "Christopher Hewitt"
categoria: "LIBROS, REVISTAS Y FOTOS"
paginas: 525
extraccion: "texto (OCR pendiente)"
fuente: "local:E:/MATERIAL DE CONSULTA/LIBROS, REVISTAS Y FOTOS/ESTRUCTURA/ACERO/AISCDesignExamples.pdf"
convertido: 2026-10-16
---

# AISC Design Examples v13.0

> Texto extraído de `LIBROS, REVISTAS Y FOTOS\ESTRUCTURA\ACERO\AISCDesignExamples.pdf` (525 páginas, texto (OCR pendiente)). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

DESIGN EXAMPLES
Version 13.0

AMERICAN INSTITUTE
OF
STEEL CONSTRUCTION
INC.

<!-- p. 2 -->

Copyright © 2005

by

American Institute of Steel Construction, Inc.

All rights reserved. This CD-ROM or any part thereof
must not be reproduced in any form without the
written permission of the publisher.

The information presented in this publication has been prepared in accordance with recognized engineering
principles and is for general information only. While it is believed to be accurate, this information should
not be used or relied upon for any speciﬁc application without competent professional examination and
veriﬁcation of its accuracy, suitability, and applicability by a licensed professional engineer, designer, or
architect. The publication of the material contained herein is not intended as a representation or warranty
on the part of the American Institute of Steel Construction or of any other person named herein, that this
information is suitable for any general or particular use or of freedom from infringement of any patent or
patents. Anyone making use of this information assumes all liability arising from such use.

Caution must be exercised when relying upon other speciﬁcations and codes developed by other bodies
and incorporated by reference herein since such material may be modiﬁed or amended from time to time
subsequent to the printing of this edition. The Institute bears no responsibility for such material other than
to refer to it and incorporate it by reference at the time of the initial publication of this edition.

Printed in the United States of America

<!-- p. 3 -->

i.-1.

PREFACE

The AISC Design Examples CD provides examples on the application of the 2005 AISC Specification for Structural
Steel Buildings (ANSI/AISC 360-05) and the AISC Steel Construction Manual, 13 th Edition. The examples found
herein illustrate how the Specification and Manual can be used to determine solutions to common engineering
problems efficiently, and outline the background to many of the tabulated values found in the Manual.

The design examples on this CD do not represent a stand-alone document. They are intended to be used in
conjunction with the Specification, its Commentary, and the Manual.

Part I of these examples is organized to correspond with the organization of the Specification and the Chapters are
referred to by their corresponding letter reference from the Specification.

Part II is devoted primarily to connection examples that draw on the tables from the Manual, recommended design
procedures, and the breadth of the Specification. The chapters of Part II are labeled II-A, II-B, II-C, etc.

Part III addresses aspects of design that are linked to the performance of a building as a whole. This includes
coverage of lateral stability and second order analysis, illustrated through a four-story braced-frame and momentframe building.

The Design Examples are arranged with LRFD and ASD designs presented side by side, for consistency with the
Manual. Design with ASD and LRFD are based on the same nominal strength for each element so that the only
difference between the approaches is which set of load combinations from ASCE 7 are used for design and whether
the resistance factor for LRFD or the safety factor for ASD should be used.

CONVENTIONS

The following conventions are used throughout these examples:

\1. The 2005 AISC Specification for Structural Steel Buildings is referred to as the Specification and the AISC
Steel Construction Manual, 13th Edition, is referred to as the Manual.

\2. The source of equations or tabulated values taken from the Specification or Manual is noted along the right-
hand edge of the page.

\3. When the design process differs between LRFD and ASD, the designs equations are presented side-by-side.
This rarely occurs, except when the resistance factor, φ, and the safety factor, Ω, are applied.

\4. The results of design equations are presented to 3 significant figures throughout these calculations.

ACKNOWLEDGEMENTS

The AISC Committee on Manuals and Textbooks gratefully acknowledges the contributions of the primary author,
Charles R. Page, P.E., and the following individuals who assisted in the development of this document:

George Batcha Steve Herlache
J. Brown Richard C. Kaehler
Jon Dean Stanley Lawson
Douglas Ferrell Kregan Liang
James Fisher Larry S. Muir
Louis F. Geschwindner, Jr. Erin Mulcahy
Tom Getschman Carie Randle
Andrew Gilmore John Rolfes
Jesse Hamilton David Rutledge
David Hawes Lee Svanda
Darren Hayward Eric Yanovich

<!-- p. 4 -->

i.-2.

The Committee also gratefully acknowledges the contributions of the following individuals who provided technical
reviews of this document.

Carlos Aguirre Jerome F. Hajjar
Duane Becker Johanna Hingle
Hans-Erik Blomgren Roberto Leon
Reidar Bjorhovde William Liddy
Wai-Fah Chen Owen Kohashi
Gregory Deierlein Darin Riggleman
Ryan D. Dick David Samuelson
Cynthia J. Duncan William Segui
Carol Drucker W. Lee Shoemaker
Michael Kemfert Raymond Tide
Kevin LeSmith Cenk Tort
Stanley Lindsey Thomas J. Schlafly
Steven Fenves Chia-Ming Uang
Theodore Galambos Donald White
Thomas Getschman

<!-- p. 5 -->

ii-1
TABLE OF CONTENTS

PART I. EXAMPLES BASED ON THE AISC SPECIFICATION

CHAPTER A GENERAL PROVISIONS

CHAPTER B DESIGN REQUIREMENTS

CHAPTER C STABILITY ANALYSIS AND DESIGN

CHAPTER D DESIGN OF MEMBERS FOR TENSION

Example D.1 W-Shape Tension Member ..........................................................................................................D-2
Example D.2 Single-Angle Tension Member ....................................................................................................D-4
Example D.3 WT-Shape Tension Member ........................................................................................................D-6
Example D.4 Rectangular HSS Tension Member .............................................................................................D-8
Example D.5 Round HSS Tension Member ...................................................................................................D-10
Example D.6 Double-Angle Tension Member ................................................................................................D-12
Example D.7 Pin-Connected Tension Member ................................................................................................D-14
Example D.8 Eyebar Tension Member ............................................................................................................D-16
Example D.9 Find Ae of a Plate with Staggered Bolts ......................................................................................D-18

CHAPTER E DESIGN OF MEMBERS FOR COMPRESSION

Example E.1a W-Shape Column Design with Pinned Ends ................................................................................E-4
Example E.1b W-Shape Column Design with Intermediate Bracing.................................................................. E-6
Example E.1c W-Shape Available Strength Calculation ....................................................................................E-8
Example E.1d W-Shape Available Strength Calculation ....................................................................................E-9
Example E.2 Built-up Column with a Slender Web........................................................................................ E-10
Example E.3 Built-up Column with Slender Flanges ......................................................................................E-14
Example E.4a W-Shape Compression Member (Moment Frame) ....................................................................E-18
Example E.4b W-Shape Compression Member (Moment Frame) ....................................................................E-21
Example E.5 Double Angle Compression Member without Slender Elements ...............................................E-22
Example E.6 Double Angle Compression Member with Slender Elements ....................................................E-26
Example E.7 Design of a WT Compression Member without Slender Elements ............................................E-31
Example E.8 Design of a WT Compression Member with Slender Elements .................................................E-34
Example E.9 Design of a Rectangular HSS Compression Member without Slender Elements .....................E-37
Example E.10 Design of a Rectangular HSS Compression Member with Slender Elements ..........................E-39
Example E.11 Design of a Pipe Compression Member .....................................................................................E-42
Example E.12 Built-up I-Shaped Member with Different Flange Sizes ............................................................E-44

CHAPTER F DESIGN OF MEMBERS FOR FLEXURE

Example F.1-1a W-Shape Flexural Member Design in Strong-Axis Bending, Continuously Braced ................... F-6
Example F.1-1b W-Shape Flexural Member Design in Strong-Axis Bending, Continuously Braced ................... F-7
Example F.1-2a W-Shape Flexural Member Design in Strong-Axis Bending, Braced at Third Points ................. F-8
Example F.1-2b W-Shape Flexural Member Design in Strong-Axis Bending, Braced at Third Points................. F-9
Example F.1-3a W-Shape Flexural Member design in Strong-Axis Bending, Braced at Midspan...................... F-11
Example F.1-3b W-Shape Flexural Member Design in Strong-Axis Bending, Braced at Midspan..................... F-13
Example F.2-1a Compact Channel Flexural Member, Continuously Braced....................................................... F-15
Example F.2-1b Compact Channel Flexural Member, Continuously Braced ....................................................... F-16
Example F.2-2a Compact Channel Flexural Member with Bracing at Ends and Fifth Points ............................. F-17
Example F.2-2b Compact Channel Flexural Member with Bracing at End and Fifth Points ............................... F-18
Example F.3a W-Shape Flexural Member with Noncompact Flanges in Strong-Axis Bending ...................... F-20
Example F.3b W-Shape Flexural Member with Noncompact Flanges in Strong-Axis Bending ...................... F-22
Example F.4 W-shape Flexural Member, Selection by Moment of Inertia for Strong-Axis Bending ............ F-23
Example F.5 I-shaped Flexural Member in Minor-Axis Bending ................................................................... F-25
Example F.6 HSS Flexural Member with Compact Flange ........................................................................... F-27
Example F.7a HSS Flexural Member with Noncompact Flange ..................................................................... F-28
Example F.7b HSS Flexural Member with Noncompact Flanges .................................................................... F-30
Example F.8a HSS Flexural Member with Slender Flanges ............................................................................ F-32

<!-- p. 6 -->

ii-2

Example F.8b HSS Flexural Member with Slender Flanges ............................................................................ F-33
Example F.9a Pipe Flexural Member ................................................................................................................ F-35
Example F.9b Pipe Flexural Member ................................................................................................................ F-36
Example F.10 WT Shape Flexural Member ...................................................................................................... F-37
Example F.11 Single Angle Flexural Member .................................................................................................. F-39
Example F.12 Rectangular Bar in Strong-Axis Bending ................................................................................... F-41
Example F.13 Round Bar in Bending ................................................................................................................ F-43
Example F.14 Non-Symmetrical Z-shape in Strong-Axis Bending .................................................................. F-45

CHAPTER G DESIGN OF MEMBERS FOR SHEAR

Example G.1a W-Shape in Strong-Axis Shear ....................................................................................................G-3
Example G.1b W-Shape in Strong-Axis Shear ....................................................................................................G-4
Example G.2a C-Shape in Strong-Axis Shear .....................................................................................................G-5
Example G.2b C-Shape in Strong-Axis Shear .....................................................................................................G-6
Example G.3 Angle in Shear ..............................................................................................................................G-7
Example G.4 Rectangular HSS in Shear ...........................................................................................................G-8
Example G.5 Round HSS in Shear ....................................................................................................................G-9
Example G.6 Doubly-Symmetric Shape in Weak-Axis Shear .........................................................................G-11
Example G.7 Singly-Symmetric Shape in Weak-Axis Shear ..........................................................................G-12
Example G.8a Built-up Plate Girder with Transverse Stiffeners .......................................................................G-13
Example G.8b Built-up Plate Girder with Transverse Stiffeners .......................................................................G-17

CHAPTER H DESIGN OF MEMBERS FOR COMBINED FORCES AND TORSION

Example H.1a W-shape Subjected to Combined Compression and Bending
About Both Axes (braced frame) .................................................................................................H-2
Example H.1b W-shape Column Subjected to Combined Compression and Bending Moment
About Both Axes (braced frame) ..................................................................................................H-3
Example H.2 W-Shape Column Subjected to Combined Compression and Bending Moment
About Both Axes (by Specification Section H2) .........................................................................H-4
Example H.3 W-Shape Subject to Combined Axial Tension and Flexure......................................................... H-6
Example H.4 W-Shape Subject to Combined Axial Compression and Flexure .................................................H-9
Example H.5a Rectangular HSS Torsional Strength ........................................................................................H-12
Example H.5b Round HSS Torsional Strength .................................................................................................H-13
Example H.5c HSS Combined Torsional and Flexural Strength ......................................................................H-14
Example H.6 W-Shape Torsional Strength ......................................................................................................H-17

CHAPTER I DESIGN OF COMPOSITE MEMBERS
Example I.1 Composite Beam Design ............................................................................................................... I-6
Example I.2 Filled Composite Column in Axial Compression ....................................................................... I-10
Example I.3 Encased Composite Column in Axial Compression ................................................................... I-13
Example I.4 Encased Composite Column in Axial Tension ............................................................................ I-17
Example I.5 Filled Composite Column in Axial Tension ............................................................................... I-19
Example I.6 Filled Composite Member Design for Shear ............................................................................... I-20
Example I.7 Combined Axial and Flexural Strength ....................................................................................... I-22

CHAPTER J DESIGN OF CONNECTIONS

Example J.1 Fillet Weld in Longitudinal Shear .................................................................................................J-2
Example J.2 Fillet Weld Loaded at an Angle ....................................................................................................J-4
Example J.3 Combined Tension and Shear in Bearing Type Connections........................................................ J-6
Example J.4 Slip-Critical Connection with Short Slotted Holes .......................................................................J-7
Example J.5 Combined Tension and Shear in a Slip-Critical Connection .......................................................J-10
Example J.6 Bearing Strength of a Pin in a Drilled Hole ................................................................................ J-12
Example J.7 Base Plate Bearing on Concrete...................................................................................................J-13

<!-- p. 7 -->

ii-3

CHAPTER K DESIGN OF HSS AND BOX MEMBER CONNECTIONS

Example K.1 Welded/bolted Wide Tee Connection to an HSS Column ..........................................................K-2
Example K.2 Welded/bolted Narrow Tee Connection to an HSS Column .......................................................K-7
Example K.3 Double Angle Connection to an HSS Column ..........................................................................K-10
Example K.4 Unstiffened Seated Connection to an HSS Column ..................................................................K-12
Example K.5 Stiffened Seated Connection to an HSS Column ......................................................................K-14
Example K.6 Single-Plate Connection to Rectangular HSS Column .............................................................K-18
Example K.7 Through-Plate Connection .........................................................................................................K-21
Example K.8 Transverse Plate Loaded Perpendicular to the HSS Axis on a Rectangular HSS................... K-24
Example K.9 Longitudinal Plate Loaded Perpendicular to the HSS Axis on a Round HSS ........................K-26
Example K.10 HSS Brace Connection to a W-shaped Column..........................................................................K-28
Example K.11 Rectangular HSS Column with a Cap Plate, Supporting a Continuous Beam ..........................K-31
Example K.12 Rectangular HSS Column Base Plate ........................................................................................K-33
Example K.13 Rectangular HSS Strut End Plate ..............................................................................................K-35

PART II. EXAMPLES BASED ON THE AISC STEEL CONSTRUCTION MANUAL

CHAPTER IIA SIMPLE SHEAR CONNECTIONS

Example II.A-1 All-Bolted Double-Angle Connection ......................................................................................IIA-2
Example II.A-2 Bolted/Welded Double-Angle Connection ...............................................................................IIA-4
Example II.A-3 All-Welded Double-Angle Connection .................................................................................... IIA-6
Example II.A-4 All-Bolted Double-Angle Connection ......................................................................................IIA-8
Example II.A-5 Bolted/Welded Double-Angle Connection (beam-to-girder web). .........................................IIA-12
Example II.A-6 Beam End Coped at the Top Flange Only ..............................................................................IIA-14
Example II.A-7 Beam End Coped at the Top and Bottom Flanges.................................................................. IIA-20
Example II.A-8 All-Bolted Double-Angle Connections (beams-to-girder web) ..............................................IIA-23
Example II.A-9 Offset All-Bolted Double-Angle Connections (beams-to-girder web) ...................................IIA-29
Example II.A-10 Skewed Double Bent-Plate Connection (beam-to-girder web)............................................... IIA-31
Example II.A-11 Shear End-Plate Connection (beam to girder web)................................................................. IIA-36
Example II.A-12 All-Bolted Unstiffened Seated Connection (beam-to-column web) .......................................IIA-38
Example II.A-13 Bolted/Welded Unstiffened Seated Connection (beam-to-column flange) .............................IIA-41
Example II.A-14 Stiffened Seated Connection (beam-to-column flange) ..........................................................IIA-44
Example II.A-15 Stiffened Seated Connection (beam-to-column web) .............................................................IIA-47
Example II.A-16 Offset Unstiffened Seated Connection (beam-to-column flange)........................................... IIA-49
Example II.A-17 Single-Plate Connection (conventional – beam-to-column flange) ........................................IIA-52
Example II.A-18 Single-Plate Connection (beam-to-girder web) .......................................................................IIA-54
Example II.A-19 Offset Extended Single-Plate Connection (beam-to-column web) .........................................IIA-56
Example II.A-20 All-Bolted Single-Plate Shear Splice ......................................................................................IIA-61
Example II.A-21 Bolted/Welded Single-Plate Shear Splice ...............................................................................IIA-65
Example II.A-22 Bolted Bracket Plate Design ...................................................................................................IIA-69
Example II.A-23 Welded Bracket Plate Design.................................................................................................. IIA-73
Example II.A-24 Eccentrically-Loaded Bolt Group (IC method) .......................................................................IIA-76
Example II.A-25 Eccentrically Loaded Bolt Group (elastic method)................................................................. IIA-78
Example II.A-26 Eccentrically-Loaded Weld Group (IC method)..................................................................... IIA-80
Example II.A-27 Eccentrically-Loaded Weld Group (elastic method) ...............................................................IIA-82
Example II.A-28 All-Bolted Single-Angle Connection (beam-to-girder web)................................................... IIA-84
Example II.A-29 Bolted/Welded Single-Angle Connection (beam-to-column flange). ..................................... IIA-88
Example II.A-30 All-Bolted Tee Connection (beam-to-column flange) ............................................................IIA-90
Example II.A-31 Bolted/Welded Tee Connection (beam-to-column flange) .....................................................IIA-96

<!-- p. 8 -->

ii-4

CHAPTER IIB FULLY RESTRAINED (FR) MOMENT CONNECTIONS

Example II.B-1 Bolted Flange-Plate FR Moment Connection (beam-to-column flange) ................................. IIB-2
Example II.B-2 Welded Flange-Plated FR Moment Connection (beam-to-column flange) ............................ IIB-10
Example II.B-3 Directly-Welded Flange FR Moment Connection (beam-to-column flange). ....................... IIB-17
Example II.B-4 Four-Bolt Unstiffened Extended End-Plate
FR Moment Connection (beam-to-column flange) ................................................................ IIB-21

CHAPTER IIC BRACING AND TRUSS CONNECTIONS

Example II.C-1 Truss Support Connection Design ........................................................................................... IIC-2
Example II.C-2 Bracing Connection ............................................................................................................... IIC-11
Example II.C-3 Bracing Connection ............................................................................................................... IIC-34
Example II.C-4 Truss Support Connection Design ......................................................................................... IIC-41
Example II.C-5 HSS Chevron Brace Connection ........................................................................................... IIC-46
Example II.C-6 Heavy Wide Flange Compression Connection (flanges on the outside) ................................ IIC-51

CHAPTER IID MISCELLANEOUS CONNECTIONS

Example II.D-1 Prying Action in Tees and in Single Angles ............................................................................IID-2
Example II.D-2 Beam Bearing Plate .................................................................................................................IID-7
Example II.D-3 Slip-Critical Connection with Oversized Holes
(Designed for Slip as a Serviceability Limit State) ................................................................IID-12

PART III. SYSTEM DESIGN EXAMPLES

DESIGN OF SELECTED MEMBERS AND LATERAL ANALYSIS OF A 4 STORY BUILDING

General description of the building including geometry, gravity loads, and lateral loads .......................................III-3
Roof member design and selection ..........................................................................................................................III-6
Floor member design and selection .......................................................................................................................III-13
Column design and selection for gravity loads...................................................................................................... III-29
Wind load determination .......................................................................................................................................III-38
Seismic load determination ....................................................................................................................................III-41
Determination of Required Strength including Second-Order Effects ..................................................................III-53

APPENDIX A. CROSS-REFERENCE LIST FOR THE 2005 AISC SPECIFICATION

<!-- p. 9 -->

A-1

CHAPTER A
GENERAL PROVISIONS

GENERAL PROVISIONS

A1. SCOPE

All of the examples on this CD are intended to illustrate the application of the 2005 AISC Specification for
Structural Steel Buildings (ANSI/AISC 360-05) and the AISC Steel Construction Manual, 13th Edition in low-and
moderate-seismic applications, (i.e. with R equal to or less than 3). For information on design applications
involving R greater than 3, the AISC Seismic Design Manual, available at www.aisc.org, should be consulted.

A2. REFERENCED SPECIFCATIONS, CODES AND STANDARDS

Section A2 includes a detailed list of the specifications, codes and standards referenced throughout the
Specification.

A3. MATERIAL

Section A3 includes a list of the steel materials that are acceptable for use in accordance with the Specification.
The complete ASTM standards for the most commonly used steel materials can be found in Selected ASTM
Standards for Structural Steel Fabrication, available at www.aisc.org.

<!-- p. 10 -->

B-1

CHAPTER B
DESIGN REQUIREMENTS

B1. GENERAL PROVISIONS

B2. LOADS AND LOAD COMBINATIONS

In the absence of a building code to provide otherwise, the default load combinations to be used with this
Specification are taken from ASCE7-02.

B3. DESIGN BASIS

Chapter B of the Specification and Part 2 of the Manual, describe the basis of design, for both LRFD and ASD.

This Section describes three basic types of connections: Simple Connections, Fully Restrained (FR) Moment
Connections, and Partially Restrained (PR) Moment Connections. Several examples of the design of each of these
types of connection are given in Part II of these design examples.

Information on the application of serviceability and ponding criteria may be found in Specification Chapter L, and its
associated commentary. Design examples and other useful information on this topic are given in AISC Design
Guide 3, Serviceability Design Consideration for Steel Buildings, Second Edition.

Information on the application of fire design criteria may be found in Specification Appendix 4, and its associated
commentary. Design examples and other useful information on this topic are presented AISC Design Guide19, Fire
Resistance of Structural Steel Framing.

Corrosion protection and fastener compatibility are discussed in Chapter 2 of the Manual.

B4. CLASSIFICATION OF SECTIONS FOR LOCAL BUCKLING

Specification Table B4.1 gives the complete list of limiting width-thickness ratios for all compression and flexural
members defined by the Specification.

Except for one section, the W-shapes presented in the compression member selection tables as column sections meet
the criteria as non-slender element sections. The W-shapes presented in the flexural member selection tables as beam
sections meet the criteria for compact sections, except for 10 specific shapes. When non-compact or slender element
members are tabulated in the design aids, local buckling criteria are accounted for in the tabulated design values.

The shapes listing and other member-design tables in the Manual also include footnoting to highlight sections that
exceed local buckling limits in their most commonly available material grades. These footnotes include the
following notations:

c
Shape is slender in compression
f
Shape exceeds compact limit for flexure
g
The actual size, combination, and orientation of fastener components should be compared with the geometry of
the cross-section to ensure compatibility
h
Flange thickness greater than 2 in. Special requirements may apply per AISC Specification Section A3.1c.
v
Shape does not meet the h/tw limit for shear in Specification Section G2.1

<!-- p. 11 -->

C-1

CHAPTER C
STABILITY ANALYSIS AND DESIGN

C1. STABILITY DESIGN REQUIREMENTS

The Specification has, for some time, required that design account for both the stability of the structural system as a
whole, and the stability of individual elements. Thus, the lateral analysis used to assess stability should include
consideration of the combined effect of gravity and lateral loads, including the resulting second-order effects, P-
∆ and P-δ . The effects of “leaning columns” should also be considered, as illustrated in the four-story building
design example in Part III of AISC Design Examples.

P-∆and P-δeffects are illustrated in Commentary Figure C-C1.1. Several methods for addressing stability, including
P-∆ and P-δeffects are discussed in Section C2.

C2. CALCULATION OF REQUIRED STRENGTHS

The calculation of required strengths is illustrated in the four-story building design example in Part III of AISC
Design Examples.

<!-- p. 12 -->

D-1

CHAPTER D
DESIGN OF MEMBERS FOR TENSION

INTRODUCTION

D1. SLENDERNESS LIMITATIONS

Section D1 does not establish a slenderness limit for tension members, but recommends limiting L/r to a
maximum of 300. This is not an absolute requirement, and rods and hangers are specifically excluded from this
recommendation.

D2. TENSILE STRENGTH

Both tensile yield strength and tensile rupture strengths must be considered for the design of tension members. It
is not unusual for tensile rupture strength to govern the design of a tension member, particularly for small
members with holes or heavier sections with multiple rows of holes.

For preliminary design, tables are provided in Part 5 of the Manual for W-shapes, L-shapes, WT shapes,
Rectangular HSS, Square HSS, Round HSS, Pipe and 2L-shapes. The calculations in these tables for available
tensile rupture strength assume an effective area, Ae, of 0.75Ag. If the actual effective area is greater than 0.75Ag,
the tabulated values will be conservative and manual calculations can be performed to obtain higher available
strengths. If the actual effective area is less than 0.75Ag, the tabulated values will be unconservative and manual
calculations are necessary to determine the available strength.

D3. AREA DETERMINATION

The gross area, Ag, is the total cross-sectional area of the member.

In computing net area, An, an extra z in. is added to the bolt hole diameter and an allowance of z in. is added to
the width of slots in HSS gusset connections.

A computation of the effective area for a chain of holes is presented in Example D.9.

Unless all elements of the cross-section are connected, Ae=AnU, where U is a reduction factor to account for shear
lag. The appropriate values of U can be obtained from Table D3.1 of the Specification.

D4. BUILT-UP MEMBERS

The limitations for connections of built-up members are discussed in Section D4 of the Specification.

D5. PIN-CONNECTION MEMBERS

An example of a pin-connected member is given in Example D.7.

D6. EYEBARS

An example of an eyebar connection is given in Example D.8.

<!-- p. 13 -->

D-2

Example D.1 W-Shape Tension Member

Given:

Select an 8 in. W-shape, ASTM A992, to carry a dead load of 30 kips and a live load of 90 kips in tension. The
member is 25 ft long. Verify the member strength by both LRFD and ASD with the bolted end connection shown.
Verify that the member satisfies the recommended slenderness limit.

Solution:

Calculate the required tensile strength

LRFD ASD
Pu = 1.2(30 kips) + 1.6(90 kips) Pa = 30 kips + 90 kips
\= 180 kips = 120 kips

Try a W8×21

Material Properties:
W8×21 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3
Geometric Properties:
W8×21 Ag = 6.16 in.2 bf = 5.27 in. tf = 0.400 in. d = 8.28 in. Manual
ry = 1.26 in. Table 1-1
y = 0.831 in. (for WT4×10.5) Table 1-8

Check tensile yield limit state using tabulated values

LRFD ASD
277 kips > 180 kips o.k. 184 kips > 120 kips o.k. Manual
Table 5-1

Check the available tensile rupture strength at the end connection

Verify the table assumption that Ae / Ag ≥ 0.75 for this connection

<!-- p. 14 -->

D-3

Calculate U as the larger of the values from Table D3.1 case 2 or case 7

Case 2 – Check as 2 WT-shapes Commentary
Fig. C-D3.1
x in. U = 1 − = 1 −0.831 = 0.908
l 9.00 in.
Table D3.1 Case 7
Case 2
bf = 5.27 in. d = 8.28 in. bf \< 2/3d

U = 0.85
Table D3.1
Case 7 Use U = 0.908

Calculate An

Section D3.2 An = Ag – 4(dh + z in.)tf
\= 6.16 in.2 – 4(m in. + z in.)(0.400 in.) = 4.76 in.2

Calculate Ae

Section D3.3
Ae = AnU
\= 4.76 in.2(0.908) = 4.32 in.2
Eqn. D3-1
Ae /Ag = 4.32 in.2 / 6.16 in.2 = 0.701 \< 0.75 tabulated values for rupture n.a.

Pn = FuAe = (65 ksi)(4.32 in.2) = 281 kips

Eqn. D2-2

LRFD ASD
φt = 0.75 Ωt = 2.00 Section D2
φtPn = 0.75(281 kips) = 211 kips Pn/Ωt = (281 kips)/2.00 = 141 kips

211 kips > 180 kips o.k. 141 kips > 120 kips o.k.

Check the non-mandatory slenderness limit Section D1

⎛ 25.0ft ⎞⎛ 12.0in. ⎞
L / r = ⎜ ⎟⎜ ⎟ = 238 \< 300 o.k.
⎝ 1.26in. ⎠⎝ ft ⎠

LRFD ASD
225 kips > 180 kips o.k. 150 kips > 120 kips o.k. Manual
Table 5-1

The W8×21 available tensile strength is governed by the tensile rupture limit state at the end
connection.

<!-- p. 15 -->

D-4

Example D.2 Single-Angle Tension Member

Given:

Verify, by both ASD and LRFD, the strength of an L4×4×½, ASTM A36, with one line of (4) ¾ in. diameter
bolts in standard holes. The member carries a dead load of 20 kips and a live load of 60 kips in tension. Calculate
at what length this tension member would cease to satisfy the recommended slenderness limit.

Solution:

Material Properties:
L4×4×½ ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-3
Geometric Properties:
L4×4×½ Ag = 3.75 in.2 rz = 0.776 in. y = 1.18 in. = x Manual
Table 1-7
Calculate the required tensile strength
LRFD ASD
Pu = 1.2(20 kips) + 1.6(60 kips) Pa = 20 kips + 60 kips
\= 120 kips = 80.0 kips

Calculate the available tensile yield strength

Pn = FyAg = (36ksi)(3.75in.2) = 135 kips Eqn. D2-1

LRFD ASD
φt = 0.90 Ωt = 1.67 Section D2
φtPn = 0.90(135 kips) = 122 kips Pn /Ωt = (135 kips)/1.67 = 80.8 kips

Calculate the available tensile rupture strength

Calculate U as the larger of the values from Table D3.1 case 2 or case 8

Case 2
x U = 1 − = 1 −1.18in. = 0.869 Table D3.1 l 9.00in.
Case 2 Case 8 with 4 or more fasteners per line in the direction of loading

U = 0.80
Table D3.1
Case 8Use U = 0.869

<!-- p. 16 -->

D-5

Calculate An Section D3.2
An = Ag – (dh + z)t
\= 3.75 in.2 – (m in. + z in.)(2 in.) = 3.31 in.2

Calculate Ae Section D3.3

Ae = AnU = 3.31 in.2(0.869) = 2.88 in.2 Eqn. D3-1

Pn = FuAe = (58 ksi)(2.88 in.2) = 167 kips Eqn. D2-2

LRFD ASD
φt = 0.75 Ωt = 2.00 Section D2
φtPn = 0.75(167 kips) = 125 kips Pn/Ωt = (167 kips)/2.00 = 83.5 kips

The L4×4×2 available tensile strength is governed by the tensile yielding limit state.

LRFD ASD
φtPn = 125 kips Pn/Ωt = 83.5kips
125 kips > 120 kips o.k. 83.5 kips > 80.0 kips o.k.

Calculate recommended Lmax
⎛ ft ⎞
Lmax = 300rz = (300)(0.776in.) ⎜ ⎟ = 19.4 ft Section D1 ⎝ 12.0in. ⎠

Note: The L/r limit is a recommendation, not a requirement.

<!-- p. 17 -->

D-6

Example D.3 WT-Shape Tension Member

Given:

A WT6×20, ASTM A992, member has a length of 30 ft and carries a dead load of 40 kips and a live load of 120
kips in tension. Assume the end connection is fillet welded and has a length of 16 in. Verify the member strength
by both LRFD and ASD. Assume that the gusset plate and the weld have been checked and are satisfactory.

Solution:

Material Properties:
WT6×20 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3
Geometric Properties:
WT6×20 Ag = 5.84 in.2 rx = 1.57 in. y = 1.09 in. = x (in equation for U) Manual
Table 1-8

Calculate the required tensile strength

LRFD ASD
Pu = 1.2(40.0 kips) + 1.6(120 kips) Pa = 40.0 kips + 120 kips
\= 240 kips = 160 kips

Check tensile yielding limit state using tabulated values

LRFD ASD
φtPn = 263 kips > 240 kips o.k. Pn/Ωt = 175 kips > 160 kips o.k. Manual
Table 5-3

Check tensile rupture limit state using tabulated values

LRFD ASD
214 kips \< 240 kips n.g. 142 kips \< 160 kips n.g. Manual
Table 5-3

The tabulated available rupture strengths may be conservative for this case, therefore calculate
the exact solution.

Calculate U
x Table D3.1 U = 1 − = 1 −1.09in. = 0.932 Case 2 l 16.0in.

<!-- p. 18 -->

D-7

Calculate An Section D3.2

An = Ag = 5.84 in.2 (because there are no holes)

Calculate Ae Section D3.3

Ae = AnU Eqn. D3-1
\= 5.84 in.2(0.932) = 5.44 in.2

Calculate Pn

Pn = Fu Ae
\= 65 ksi(5.44 in2) = 354 kips

LRFD ASD
φt = 0.75 Ωt = 2.00 Section D2
φtPn = 0.75(354 kips) = 266 kips Pn/Ωt = (354 kips)/2.00 = 177 kips

266 kips > 240 kips o.k. 177 kips > 160 kips o.k.

Alternately, the available tensile rupture strengths can be determined by modifying the
tabulated values. The available tensile rupture strengths published in the tension member
selection tables are based on the assumption that Ae = 0.75Ag. The actual available strengths
can be determined by adjusting the table values as follows:

LRFD ASD
⎛ Ae ⎞ ⎛ Ae ⎞ φtPn = 214 kips ⎜ ⎟ Pn/Ωt = 142 kips ⎜ ⎟ Manual ⎜ ⎟ ⎜ ⎟ ⎝ 0.75 Ag ⎠ ⎝ 0.75 Ag ⎠ Table 5-3
⎛ 2 ⎞ ⎛ 2 ⎞ 5.44in. 5.44in. = 214 kips ⎜ ⎟ = 266 kips = 142 kips ⎜ ⎟ = 176 kips
2 2 ⎜ ⎟ ⎜ ⎟ 0.75 ( 5.84in. ) 0.75 ( 5.84in. ) ⎝ ⎠ ⎝ ⎠

The WT6×20 available tensile strength is governed by the tensile yielding limit state.

LRFD ASD
φtPn = 263 kips Pn/Ωt = 175 kips
263 kips > 240 kips o.k. 175 kips > 160 kips o.k.

Check the non-mandatory slenderness limit Section D1

⎛ 30.0ft ⎞⎛ 12.0in. ⎞
L / r = ⎜ ⎟⎜ ⎟ = 229 \< 300 o.k.
⎝ 1.57in. ⎠⎝ ft ⎠

<!-- p. 19 -->

D-8

Example D.4 Rectangular HSS Tension Member

Given:

Verify, by LRFD and ASD, the strength of an HSS6×4×a, ASTM A500 grade B, with a length of 30 ft. The
member is carrying a dead load of 35 kips and a live load of 105 kips in tension. Assume the end connection is
fillet welded to a 2 in. thick single concentric gusset plate and has a length of 16 in.

Solution:

Material Properties:
HSS6×4×a ASTM A500 grade B Fy = 46 ksi Fu = 58 ksi Manual
Table 2-3
Member Geometric Properties:
HSS6×4×a Ag = 6.18 in.2 ry = 1.55 in. t = 0.349 in. Manual
Table 1-11
Calculate the required tensile strength

LRFD ASD
Pu = 1.2(35.0 kips) + 1.6(105 kips) Pa = 35.0 kips + 105 kips
\= 210 kips = 140 kips

Check available tensile yield strength

LRFD ASD
φtPn = 256 kips > 210 kips o.k. Pn/Ωt = 170 kips > 140 kips o.k. Manual
Table 5-4

Check available tensile rupture strength

LRFD ASD
201 kips \< 210 kips n.g. 134 kips \< 140 kips n.g. Manual
Table 5-4

The tabulated available rupture strengths may be conservative in this case, therefore calculate
the exact solution.

Calculate U
B 2 + 2 BH (4.00in.) 2 + 2(4.00in.)(6.00in.) Table D3.1
x = = = 1.60 in. Case 6 4( B + H ) 4(4.00in. + 6.00in.)

x U = 1 − = 1 −1.60in. = 0.900
l 16.0in.

<!-- p. 20 -->

D-9

Allowing for a z in. gap in fit-up between the HSS and the gusset plate,
An = Ag – 2(tp + z in.)t
\= 6.18 in.2 – 2(2 in. + z in.)(0.349 in.) = 5.79 in.2

Calculate Ae Section D3.2

Ae = AnU
\= 5.79 in.2(0.900) = 5.21 in.2 Section D3.3

Calculate Pn Eqn. D3-1

Pn = Fu Ae
\= 58 ksi(5.21 in2) = 302 kips

LRFD ASD
φt = 0.75 Ωt = 2.00 Section D2
φtPn = 0.75(302 kips) = 227 kips Pn /Ωt = (302 kips)/2.00 = 151 kips

227 kips > 210 kips o.k. 151 kips > 140 kips o.k.

The HSS available tensile strength is governed by the tensile rupture limit state.

Check the non-mandatory slenderness limit Section D1

⎛ 30.0ft ⎞⎛ 12.0in. ⎞
L / r = ⎜ ⎟⎜ ⎟ = 232 \< 300 o.k.
⎝ 1.55in. ⎠⎝ ft ⎠

<!-- p. 21 -->

D-10

Example D.5 Round HSS Tension Member

Given:

See Figure D-5 below. An HSS6.000×0.500, ASTM A500 grade B, has a length of 30 ft. The member carries a
dead load of 40 kips and a live load of 120 kips in tension. Assume the end connection is a fillet welded 2 in.
thick single concentric gusset plate that has a length of 16 in. Verify the strength by both LRFD and ASD.

Solution:

Material Properties:
HSS6.000×0.500 ASTM A500 grade B Fy = 42 ksi Fu = 58 ksi Manual
Table 2-3
Member Geometric Properties:
HSS6.000×0.500 Ag = 8.09 in.2 r = 1.96 in. t = 0.465 in. Manual
Table 1-13
Calculate the required tensile strength

LRFD ASD
Pu = 1.2(40.0 kips) + 1.6(120 kips) Pa = 40.0 kips + 120 kips
\= 240 kips = 160 kips

Check available tensile yield strength

LRFD ASD
φtPn = 306 kips > 240 o.k. Pn/Ωt = 203 kips > 160 kips o.k. Manual
Table 5-6

Check available tensile rupture strength

LRFD ASD
φtPn = 264 kips > 240 kips o.k. Pn/Ωt = 176 kips > 160 kips o.k. Manual
Table 5-6

Check that Ae ≥0.75 Ag as assumed in table

L = 16.0 in. D = 6.00 in. L/D = 16.0 in./(6.00 in.) = 2.67 > 1.3 Manual
Table D3.1
U = 1.0 Case 5

Allowing for a z in. gap in fit-up between the HSS and the gusset plate,

An = Ag – 2(tp + z in.)t Section D3.2
\= 8.09 in.2 – 2(0.500 in. + z in.)(0.465 in.) = 7.57 in.2

<!-- p. 22 -->

D-11

Calculate Ae Section D3.3

Ae = AnU Eqn. D3-1
\= 7.57 in.2 (1.0) = 7.57 in.2

Ae /Ag = 7.57 in.2 /(8.09 in.2) = 0.936 in.2 > 0.75 Ag o.k.

Check the non-mandatory slenderness limit Section D1

⎛ 30.0ft ⎞⎛ 12.0in. ⎞
L / r = ⎜ ⎟⎜ ⎟ = 184 \< 300 o.k.
⎝ 1.96in. ⎠⎝ ft ⎠

<!-- p. 23 -->

D-12

Example D.6 Double-Angle Tension Member

Given:

A 2L4×4×2 (a-in. separation), ASTM A36, has one line of (8) ¾-in. diameter bolts in standard holes and is 25 ft
in length. The double angle is carrying a dead load of 40 kips and a live load of 120 kips in tension. Verify the
strength by both LRFD and ASD.

Solution:

Material Properties:
2L4×4×2 ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-3
Geometric Properties:
For a single L4×4×2 Ag = 3.75 in.2 rx = 1.21 in. Manual
ry = 1.83 in. x = 1.18 in. Table 1-7

Calculate the required tensile strength

LRFD ASD
Pn= 1.2(40.0 kips) + 1.6(120 kips) Pn= 40.0 kips + 120 kips
\= 240 kips = 160 kips

Calculate the available tensile yield strength

Pn = FyAg = (36ksi)(2)(3.75in.2) = 270 kips Eqn. D2-1

LRFD ASD
φt = 0.90 Ωt = 1.67 Section D2
φtPn = 0.90(270 kips) = 243 kips Pn /Ωt = (270 kips)/1.67 = 162 kips

Calculate the available tensile rupture strength

Calculate U
x Table D3-1U = 1 − = 1 −1.18in. = 0.944 Case 2 l 21.0in.

<!-- p. 24 -->

D-13

Calculate An Section D3.2

An = Ag – 2(dh + z in.)t
\= 2(3.75in.2) – 2(m in. + z in.)(2 in.) = 6.63 in.2

Calculate Ae

Ae = AnU = 6.63in.2(0.944) = 6.26 in.2 Eqn. D3-1

Pn = FuAe = (58ksi)(6.26 in.2) = 363 kips Eqn. D2-2

LRFD ASD
φt = 0.75 Ωt = 2.00 Section D2
φtPn = 0.75(363 kips) = 272 kips Pn/Ωt = (363 kips)/2.00 = 182 kips

The available strength is governed by the tensile yielding limit state.

LRFD ASD
243 kips > 240 kips o.k. 162 kips > 160 kips o.k.

Check the non-mandatory slenderness limit Section D1
⎛ 25.0ft ⎞⎛ 12.0in. ⎞
L / r = ⎜ ⎟⎜ ⎟ = 248 \< 300 o.k.
⎝ 1.21in. ⎠⎝ ft ⎠

<!-- p. 25 -->

D-14

Example D.7 Pin-Connected Tension Member

Given:

An ASTM A36 pin connected tension member with the dimensions shown below carries a dead load of 12 kips
and a live load of 4 kips in tension. The diameter of the pin is 1 inch, in a Q-in. oversized hole. Assume that the
pin itself is adequate. Verify the strength by both LRFD and ASD.

Solution:

Material Properties:
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-4
Geometric Properties:
w = 4.25 in. t = 0.500 in. d = 1.00 in. a = 2.25 in. c = 2.50 in.

Check dimensional requirements: Section D5.2

\1) beff = 2t + 0.63 in. = 2(0.500 in.) + 0.63 in. = 1.63 in.

\2) a > 1.33beff 2.25 in. > (1.33)(1.63 in.) = 2.17 in. o.k.

\3) w > 2beff + d 4.25 in. > 2(1.63 in.) + 1.00 in. = 4.26in. ≅ 4.25in. o.k.

\4) c > a 2.50 in. > 2.25 in. o.k.

Calculate the required tensile strength

LRFD ASD
Pu = 1.2(12.0 kips) + 1.6(4.00 kips) Pa = 12.0 kips + 4.00 kips
\= 20.8 kips = 16.0 kips

<!-- p. 26 -->

D-15

Calculate the available tensile rupture strength on the net effective area

Pn = 2tbeffFu = (2)(0.500 in.)(1.63 in.)(58 ksi) = 94.5 kips Eqn. D5-1

LRFD ASD
φt = 0.75 Ωt = 2.00 Section D5.1
φtPn = 0.75(94.5 kips) = 70.9 kips Pn/Ωt = (94.5 kips) / 2.00 = 47.3 kips

Calculate the available shear rupture strength

Asf = 2t(a + d/2) = 2(0.500 in.)[2.25 in. + (1.00 in. /2)] = 2.75 in.2 Section D5.1

Pn = 0.6FuAsf = (0.6)(58 ksi)(2.75 in.2) = 95.7 kips Eqn. D5-2

LRFD ASD
φsf = 0.75 Ωsf = 2.00 Section D5.1
φsfPn = 0.75(95.7 kips) = 71.8 kips Pn/Ωsf = (95.7 kips) / 2.00 = 47.9 kips

Calculate the available bearing strength

Apb = 0.500 in.(1.00 in.) = 0.500 in.2

Rn = 1.8FyApb = 1.8(36 ksi)(0.500 in.2) = 32.4 kips Eqn. J7.1

LRFD ASD
φt = 0.75 Ωt = 2.00 Section J7
φtPn = 0.75(32.4 kips) = 24.3 kips Pn/Ωt = (32.4 kips) / 2.00 = 16.2 kips

Calculate the available tensile yielding strength

Ag = 4.25 in. (0.500 in.) = 2.13 in.2 Section D2

Pn = FyAg = 36 ksi (2.13 in.2) = 76.5 kips Eqn. D2.1

LRFD ASD
φt = 0.90 Ωt = 1.67 Section D2
φtPn = 0.90(76.5 kips) = 68.9 kips Pn/Ωt = (76.5 kips) / 1.67 = 45.8 kips

The available tensile strength is governed by the bearing strength limit state

LRFD ASD
φtPn = 24.3 kips Pn/Ωt = 16.2 kips
24.3 kips > 20.8 kips o.k. 16.2 kips > 16.0 kips o.k.

<!-- p. 27 -->

D-16

Example D.8 Eyebar Tension Member

Given:

See Figure D-8 below. A s in. thick eyebar member, ASTM A36, carries a dead load of 25 kips and a live load of
15 kips in tension. The pin diameter d is 3 in. Verify the strength by both LRFD and ASD.

Solution:

Material Properties:
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-4
Geometric Properties:
w = 3 in. b = 2.23 in. t = 0.625 in.
db = 3 in. dh = 3.03 in. R = 8.00 in.

Check dimensional requirements Section D4.2

\1) t > ½ in. 0.625 in. > 0.500 in. o.k.

\2) w \< 8t 3.00 in. \< 8(0.625 in.) = 5 in. o.k.

\3) d > 7/8w 3.00 in. > 7/8 (3.00 in.) = 2.63 in. o.k.

\4) dh \< d + 1/32 in. 3.03 in. \< 3.00 in. + (1/32 in.) = 3.03 in. o.k.

\5) R > dh + 2b 8.00 in. > 3.03 in. + 2(2.23 in.) = 7.50 in. o.k.

\6) 2/3w \< b \< 3/4w 2/3(3.00 in.) \< 2.23 in. \< 3/4(3.00 in.)
2.00 in. \< 2.23 in. \< 2.25 in. o.k.

<!-- p. 28 -->

D-17

Calculate the required tensile strength

LRFD ASD
Pu = 1.2(25.0 kips) + 1.6(15.0 kips) Pa = 25.0 kips + 15.0 kips
\= 54.0 kips = 40.0 kips

Calculate the available tensile yield strength at the eyebar body (at w)

Ag = 3.00 in.(0.625 in.) = 1.88 in.2
Pn= FyAg = (36 ksi)(1.88 in.2) = 67.7 kips Eqn. D2-1

LRFD ASD
φt = 0.90 Ωt = 1.67 Section D2
φtPn = 0.90(67.7 kips) = 60.9 kips Pn/Ωt = (67.7 kips)/1.67 = 40.5 kips

60.9 kips > 54.0 kips o.k. 40.3 kips > 40.0 kips o.k.

The eyebar tension member available strength is governed by the tension yield limit state.

Note: The eyebar detailing limitations ensure that the tensile yielding limit state at the eyebar
body will control the strength of the eyebar itself. The pin should also be checked for shear
yielding, and if the material strength is lower than that of the eyebar, bearing.

<!-- p. 29 -->

D-18

Example D.9 Find Ae of a Plate with Staggered Bolts

Given:

See Fig. D-9 below. A 14 in. wide and 2 in. thick plate subject to tensile loading has staggered holes as shown.
Compute An and Ae

Solution:

Calculate net hole diameter Section D3.2

dnet = dh + z in. = 0.875 in.

Compute the net width for all possible paths across the plate
Because of symmetry, many of the net widths are identical and need not be calculated
s 2
w =14.0- d
net ∑ + ∑ Section D3.2 4 g
Line A-B-E-F: w = 14.0in.-2(0.875in.) = 12.3in.
( 2.50in.) 2 ( 2.50in.) 2 Line A-B-C-D-E-F: w = 14.0in.- 4(0.875in.) + + = 11.5in. (controls)
4(3.00in.) 4(3.00in.)
( 2.50in.) 2 Line A-B-C-D-G: w = 14.0in.-3(0.875in.) + = 11.9in.
4(3.00in.)
( 2.50in.) 2 ( 2.50in.) 2 Line A-B-D-E-F: w = 14.0in.-3(0.875in.) + + = 12.1in.
4(7.00in.) 4(3.00in.)
Therefore, An = (11.5 in.)(0.500 in.) = 5.75 in.2

Calculate U

Since tension load is transmitted to all elements by the fasteners
Table D3.1
U= 1.0 Case 1

Ae = An(1.0) = 5.75 in.2 Eqn. D3-1

<!-- p. 30 -->

E-1

CHAPTER E
DESIGN OF MEMBERS FOR COMPRESSION

This chapter covers the design of compression members, the most common of which are columns. The Manual
includes design tables for the following compression member types in their most commonly available grades:

• wide-flange column shapes
• HSS
• double angles
• single angles

LRFD and ASD information is presented side by side for quick selection, design or verification. All of the tables
account for the reduced strength of sections with slender elements.

The design and selection method for both LRFD and ASD designs is similar to that of previous specifications, and
will provide similar designs. In the new Specification, ASD and LRFD will provide identical designs when the
live load is approximately three times the dead load.

The design of built-up shapes with slender elements can be tedious and time consuming, and it is recommended
that standard rolled shapes be used, when possible.

E1. GENERAL PROVISIONS

The design compressive strength, φcPn, and the allowable compressive strength, Pn/Ωc, are determined as follows:

Pn = nominal compressive strength based on the controlling buckling mode

φc = 0.90 (LRFD) Ωc = 1.67 (ASD).

Because Fcr is used extensively in calculations for compression members, it has been tabulated in Table 4-22 for
all of the common steel yield strengths.

E2. SLENDERNESS LIMITATIONS AND EFFECTIVE LENGTH

In this edition of the Specification, there is no limit on slenderness, KL/r. Per the Commentary, it is recommended
that KL/r not exceed 200, as a practical limit based on professional judgment and construction economics.

Although there is no restriction on the unbraced length of columns, the tables of the Manual are stopped at
common or practical lengths for ordinary usage. For example, a double 3×3×¼ angle, with a a-in. separation has
an ry of 1.25 in. At a KL/r of 200, this strut would be 20’-10” long. This is thought to be a reasonable limit based
on fabrication and handling requirements.

Throughout the Manual, shapes that contain slender elements when supplied in their most common material grade
are footnoted with the letter “c”. For example, see a W14×22c.

E3. COMPRESSIVE STRENGTH FOR FLEXURAL BUCKLING OF MEMBERS WITHOUT
SLENDER ELEMENTS

Non-slender (compact and non-compact) sections, including non-slender built-up I-shaped columns and nonslender HSS columns, are governed by these provisions. The general design curve for critical stress versus KL/r is
shown in Figure E-1.

<!-- p. 31 -->

E-2

E3.2
Inelastic
buckling
E3.3
Elastic
Critical buckling
stress,
ksi

Transition between
KL/r equations (location
varies by Fy)
Figure E-1 Standard Column Curve

TRANSITION POINT LIMITING VALUES OF KL/r
Fy ksi (MPa) Limiting KL/r 0.44Fy ksi (MPa)
36 (248) 134 15.8 (109)
50 (345) 113 22.0 (152)
60 (414) 104 264. (182)
70 (483) 96 30.8 (212)

BRACING AND BRACE POINTS

The term L is used throughout this chapter to describe the length between points that are braced against lateral
and/or rotational displacement.

E4. COMPRESSIVE STRENGTH FOR TORSIONAL AND FLEXURAL-TORSIONAL BUCKLING
OF MEMBERS WITHOUT SLENDER ELEMENTS

This section is most commonly applicable to double angles and Tee sections, which are singly symmetric shapes
subject to torsional and flexural-torsional buckling. The available strength in axial compression of these shapes is
tabulated in Part 4 of the Manual and examples on the use of these tables have been included in this chapter, for
the shapes with KLz = KLy.

E5. SINGLE ANGLE COMPRESSION MEMBERS

The available strength of single-angle compression members is tabulated in Part 4 of the Manual.

E6. BUILT-UP MEMBERS

There are no tables for built-up shapes in the Manual, due to the number of possible geometries. This section
makes suggestions as to how select built-up members to avoid slender elements, thereby making the analysis
relatively straightforward.

<!-- p. 32 -->

E-3

E7. MEMBERS WITH SLENDER ELEMENTS

The design of these members is similar to members without slender elements except that the formulas are
modified by a reduction factor for slender elements, Q. Note the similarity of Equation E7-2 with Equation E3-2,
and the similarity of Equation E7-3 with Equation E3-3.

The Tables of Part 4, incorporate the appropriate reductions in available strength to account for slender elements.

Design examples have been included in this Chapter for built-up I-shaped members with slender webs and slender
flanges. Examples have also been included for a double angle, WT, and an HSS shape with slender elements.

<!-- p. 33 -->

E-4

Example E.1a W-Shape Column Design with Pinned Ends

Given:
Select an ASTM A992 (Fy = 50 ksi) W-shape column to carry an
axial dead load of 140 kips and live load of 420 kips. The column is
30 feet long, and is pinned top and bottom in both axes. Limit the
column size to a nominal 14 in. shape.

Solution:

Calculate the required strength

LRFD ASD
Pu = 1.2(140 kips) + 1.6(420 kips) = 840 kips Pa = 140 kips + 420 kips = 560 kips

Select a column using Manual Table 4-1
Commentary
For a pinned-pinned condition, K = 1.0 Table
C-C2.2
Because the unbraced length is the same in both the x-x and y-y directions and rx exceeds ry for
all W-shapes, y-y axis bucking will govern.

Enter the table with an effective length, KLy, of 30 ft, and proceed across the table until
reaching the least weight shape with an available strength that equals or exceeds the required
strength. Select a W14×132.

<!-- p. 34 -->

E-5

The available strengths in axial compression for a y-y axis effective length of 30 ft are:
LRFD ASD
φcPn = 892 kips > 840 kips o.k. Pn/Ωc = 594 kips > 560 kips o.k. Manual
Table 4-1

<!-- p. 35 -->

E-6

Example E.1b W-Shape Column Design with Intermediate Bracing

Given:

Redesign the column from Example E.1a assuming the
column is laterally braced about the y-y axis and torsionally
braced at the midpoint.

Solution:

Calculate the required strength

LRFD ASD
Pu = 1.2(140 kips) + 1.6(420 kips) = 840 kips Pa = 140 kips + 420 kips = 560 kips

Select a column using Manual Table 4-1.
Commentary
For a pinned-pinned condition, K = 1.0 Table
C-C2.2
Since the unbraced lengths differ in the two axes, select the member using the y-y axis then
verify the strength in the x-x axis.

Enter Table 4-1 with a y-y axis effective length, KLy, of 15 ft and proceed across the table until
reaching a shape with an available strength that equals or exceeds the required strength. Try a
W14×90. A 15 ft long W14×90 provides an available strength in the y-y direction of

LRFD ASD
φPn = 1000 kips Pn/Ω = 667 kips

The rx /ry ratio for this column, shown at the bottom of Manual Table 4-1, is 1.66. The
equivalent y-y axis effective length for strong axis buckling is computed as

30.0ft
KL = = 18ft
1.66

<!-- p. 36 -->

E-7

From the table, the available strength of a W14×90 with an effective length of 18 ft is
LRFD ASD
φcPn = 928 kips > 840 kips o.k. Pn/Ωc = 618 kips > 560 kips o.k. Manual
Table 4-1

The available compression strength is governed by the x-x axis flexural buckling limit state.

<!-- p. 37 -->

E-8

The available strengths of the columns described in Examples E.1a and E.1b are easily
selected directly from the Manual Tables. The available strengths can also be verified by hand
calculations, as shown in the following Examples E.1c and E.1d.

Example E.1c W-Shape Available Strength Calculation
Calculate the available strength of a W14×132 column with unbraced lengths of 30 ft in both
axes. The material properties and loads are as given in Example E.1a.

Material properties: Manual
ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3

Geometric Properties:
W14×132 Ag = 38.8 in.2 rx = 6.28 in. ry = 3.76 in. Manual
Table 1-1
Calculate the available strength
Commentary
For a pinned-pinned condition, K = 1.0 Table
C-C2.2
Since the unbraced length is the same for both axes, the y-y axis will govern.

K y L y 1.0 ( 30.0 ft ) 12.0in = = 95.7
ry 3.76 in. ft

For Fy = 50 ksi, the available critical stresses, φcFcr and Fcr/Ωc for KL/r = 95.7 are interpolated
from Manual Table 4-22 as

LRFD ASD
φcFcr = 23.0 ksi Fcr/Ωc = 15.3 ksi Manual
Table 4-22
2 (15.3 ksi ) φc nP = 38.8 in. 2 ( 23.0 ksi ) Pn / Ω=c 38.8 in.
\= 892 kips > 840 kips o.k. = 594 kips > 560 kips o.k.

Note that the calculated values match the tabulated values.

<!-- p. 38 -->

E-9

Example E.1d W-Shape Available Strength Calculation
Calculate the available strength of a W14×90 with a strong axis unbraced length of 30 ft and
weak axis and torsional unbraced lengths of 15 ft. The material properties and loads are as
given in Example E.1b.

Geometric Properties:
W14x90 Ag = 26.5 in.2 rx = 6.14 in. ry = 3.70 in. Manual
Table 1-1
Check both slenderness ratios
Commentary
K = 1.0 Table
C-C2.2
KLx 1.0 ( 30.0 ft ) = 12in.= 58.6 governs
rx 6.14 in. ft
KL y 1.0 (15.0 ft ) 12 in. = = 48.6
ry 3.70 in. ft

The available critical stresses may be interpolated from Manual Table 4-22 or calculated
directly as follows.

Calculate the elastic critical buckling stress, Fe

π2 E π2 29,000 ksi
Fe = 2 = 2 = 83.3ksi Eqn. E3-4
⎛ KL ⎞ ( 58.6 )
⎜ ⎟
⎝ r ⎠

Calculate flexural buckling stress, Fcr

Check limit
E 29,000 ksi
4.71 = 4.71 = 113 > 58.6
Fy 50 ksi

KL E
Because \< 4.71
r Fy

F y 50.0 ⎡ ⎤ ⎡ ksi ⎤ Fe 83.3 ksi ⎢ 0.658Fcr = ⎥ Fy = ⎢ 0.658 ⎥ 50.0 ksi = 38.9ksi Eqn. E3-2
⎢ ⎥ ⎣ ⎦ ⎣ ⎦

2 Pn = FcrAg = 38.9ksi ( 26.5in ) = 1030 kips Eqn. E3-1

LRFD ASD
φc = 0.90 Ωc = 1.67
φcPn = 0.90(1030 kips) Pn/Ωc = (1030 kips) / 1.67
\= 928 kips > 840 kips o.k. = 618 kips > 560 kips o.k.

<!-- p. 39 -->

E-10

Example E.2 Built-up Column with a Slender Web

Given:
Verify that a built-up, ASTM A572 grade 50, column with PL1in.×8in. flanges and a
PL4in.×15in. web is sufficient to carry a dead load of 70 kips and live load of 210 kips in
axial compression. The column length is 15 ft and the ends are pinned in both axes.

Solution:

Material Properties:
ASTM A572 Grade 50 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3
Geometric Properties:
Built-up Column d = 17.0 in. bf = 8.00 in. tf = 1.00 in. h = 15.0 in. tw = 0.250 in.

Calculate the required strength

LRFD ASD
Pu = 1.2(70.0 kips) + 1.6(210 kips) = 420 kips Pa = 70.0 kips + 210 kips = 280 kips

Calculate built-up section properties (ignoring fillet welds)

A = 2(8.00 in.)(1.00 in.) + (15.0 in.)(0.250 in.) = 19.8 in.2

2 (1.00 in. )( 8.00 in. ) 3 (15.0 in. )( 0.250 in. ) 3 4
yI = + = 85.4 in.
12 12

I y 85.4 in. 4
ry = = 2 = 2.08 in. A 19.8 in.

I x Ix = ∑ Ad 2 + ∑
2 2 ( 0.250 in. )(15.00 in. ) 3 2 ( 8.0 in. )(1.0 in. ) 3 = 2 ( 8.00 in. )( 8.00 in. ) + + = 1100 in.4 12 12

<!-- p. 40 -->

E-11

Calculate the elastic flexural buckling stress Section E7

For a pinned-pinned condition, K = 1.0 Commentary
Table
Since the unbraced length is the same for both axes, the y-y axis will govern by inspection. C-C2.2

KL y 1.0 (15.0 ft ) 12.0in. = = 86.6
ry 2.08 in. ft

π 2 E π2 (29,000 ksi)
Fe = 2 = 2 = 38.2 ksi Eqn. E3-4 ⎛ KL ⎞ ( 86.6 )
⎜ ⎟
⎝ r ⎠

Calculate the elastic critical torsional buckling stress

Note: Torsional buckling will not govern if KLy > KLz, however, the check is included here to
illustrate the calculation.
Design
I y ho 2 85.4 in. 4 (16.0 in.) 2 Guide No. 9
Cw = = = 5470 in.6 Eqn. 3-5 4 4

Design 3 3 3 bt 2 ( 8.00 in. )(1.00 in. ) + (15.0 in. )( 0.250 in. ) Guide No. 9 J = = = 5.41 in4 ∑ 3 3 Eqn. 3-4
⎡ 2 ⎤ π EC w 1 Eqn. E4-4 Fe = ⎢ 2 + GJ ⎥ ⎢ I x +I y ⎣ ( K z L ) ⎥⎦

6 ⎤ 1 ⎡ π 2 ( 29,000 ksi)( 5470in. ) 4 ⎥ = ⎢ 2 + (11,200 ksi)( 5.41in. ) ⎢ 4 4 ⎣ ( 180in.) ⎥⎦ 1100in. + 85.4in.
\= 92.2 ksi > 38.2 ksi

Therefore, the flexural buckling limit state controls.

Use Fe = 38.2 ksi

Check for slender elements using Specification Section E7

Determine Qs, the unstiffened element (flange) reduction factor

Calculate kc

4 4 Table B4.1
kc = = = 0.516 which is between 0.35 and 0.76 Note [a]
ht w 15.00.250

b 4.00in. k c E 0.516(29,000 ksi) Table B4.1 = = 4.0 \< 0.64 = 0.64 = 11.1
t 1.00in. Fy 50 ksi Case 4

<!-- p. 41 -->

E-12

Therefore, the flange is not slender.

Qs = 1.0

Determine Qa, the stiffened element (web) reduction factor

h 15.0 in. E 29,000 ksi
\= = 60.0 > 1.49 = 1.49 = 35.9 , therefore the web is slender.
t 0.250 in. Fy 50 ksi
Aeff
Qa = where Aeff is effective area based on the reduced effective width of the web, be. Section E7.2 A

Eqn. E7-16 For equation E7-17, take f as Fcr with Q = 1.0

KL /r = 86.6 from above

E 29,000 ksi
4.71 = 4.71 = 113 > 86.6
QFy 1.0 ( 50 ksi )

KL E
When M 4.71
r QFy

y ( 50 ⎡ QF ⎤ ⎡ 1.0 ksi ) ⎤
Fe 38.2 ksi Fcr = Q ⎢ 0.658 ⎥ Fy = 1.0 ⎢ 0.658 ⎥ ( 50 ksi ) = 28.9 ksi
⎢ ⎥ ⎢⎣ ⎥⎦ Eqn. E7-2 ⎣ ⎦
E ⎡ 0.34 E ⎤
be = 1.92t ⎢1 − ⎥ ≤ b, where b = h
f ⎢⎣ ( b t ) f ⎥⎦ Eqn. E7-17
29,000 ksi ⎡ 0.34 29,000 ksi ⎤ = 1.92 ( 0.250 in. ) ⎢1 − ⎥ ≤ 15.0 in.
28.9 ksi ⎢⎣ ( 15.0 in. 0.250 in. ) 28.9 ksi ⎥⎦
\= 12.5 in. \< 15.0 in., therefore compute Aeff with reduced effective web width.

2 Aeff = be t w + 2b f t f = (12.5 in. )( 0.250 in. ) + 2 ( 8.00 in. )(1.00 in. ) = 19.1 in.

Aeff 19.1 in. 2
Qa = = 2 = 0.966 A 19.8 in. Eqn. E7-16

Q = QsQa = (1.00)(0.966) = 0.966
Section E7
Determine whether Specification Equation E7-2 or E7-3 applies

KL/r = 86.6 from above

E 29,000 ksi
4.71 = 4.71 = 115.4 > 86.6
QFy 0.966(50 ksi)

Therefore, Specification Equation E7-2 applies.

<!-- p. 42 -->

E-13

y ( 50 ⎡ QF ⎤ ⎡ 0.966 ksi ) ⎤
Fe 38.2 ksiFcr = Q ⎢ 0.658 ⎥ Fy = 0.966 ⎢ 0.658 ⎥ ( 50 ksi ) = 28.5 ksi
⎢ ⎥ ⎢⎣ ⎥⎦ Eqn. E7-2 ⎣ ⎦

Calculate the nominal compressive strength

2Pn = Fcr Ag = 28.5 ksi (19.8 in ) = 562 kips Eqn. E7-1

LRFD ASD
φc = 0.90 Ωc = 1.67 Section E1
φc nP = 0.90 ( 562 kips ) Pn / Ω=c 562 kips/1.67
\= 505 kips > 420 kips o.k. = 336 kips > 280 kips o.k.

<!-- p. 43 -->

E-14

Example E.3 Built-up Column with Slender Flanges

Given:
Determine if a built-up, ASTM A572 grade 50 column with PLa in.×102 in. flanges and a
PL4 in.×74 in. web has sufficient available strength to carry a dead load of 40 kips and a live
load of 120 kips in axial compression. The column unbraced length is 15 ft in both axes and
the ends are pinned.

Solution:

Material Properties: Manual
ASTM A572 Gr. 50 Fy = 50 ksi Fu = 65 ksi Table 2-3

Geometric Properties:
Built-up Column d = 8.00 in. bf = 10.5 in. tf = 0.375 in. h = 7.25 in.
tw = 0.250 in.

Calculate the required strength
LRFD ASD
Pu = 1.2(40.0 kips) + 1.6(120 kips) = 240 kips Pa = 40.0 kips + 120 kips = 160 kips

Calculate built-up section properties (ignoring fillet welds)

A = 2(10.5 in.)(0.375 in.) + (7.25 in.)(0.250 in.) = 9.69 in.2

Since the unbraced length is the same for both axes, the weak axis will govern.
⎡ ( 0.375 in. )(10.5 in. ) 3 ⎤ ( 7.25 in. )( 0.250 in. ) 3 4
yI = 2 ⎢ ⎥ + = 72.4 in.
⎢ 12 ⎥ 12 ⎣ ⎦
I y 72.4 in. 4
ry = = 2 = 2.73 in. A 9.69 in.
2 ( 0.25 in. )( 7.25 in. ) 3 2 (10.5 in. )( 0.375 in. ) 3 Ix = 2 (10.5 in. )( 0.375in. )( 3.81 in. ) + +
12 12
\= 122 in.4

<!-- p. 44 -->

E-15

Check web slenderness

For a stiffened element (web) in a doubly symmetric I-shaped section, under uniform
compression,

E 29,000 ksi
λr = 1.49 = 1.49 = 35.9 Table B4.1
Fy 50 ksi Case 10
h 7.25 in.
\= = 29.0 \< 35.9 Therefore, the web is not slender.
t w 0.250 in.

Note that the fillet welds are ignored in the calculation of h for built up sections.

Check flange slenderness

Calculate kc

4 4
k c = = = 0.743 where 0.35 M kc M 0.76 o.k.
h 7.25 in. Table B4.1
t w 0.250 in. Note [a]
Use kc = 0.743

For flanges of a built-up I-shaped section under uniform compression;

k c E 0.743 ( 29,000 ksi )
λr = 0.64 = 0.64 = 13.3 Table B4.1 Fy 50 ksi
Case 4
b 5.25 in.
\= = 14.0 > 13.3 Therefore, the flanges are slender.
t 0.375 in.

For compression members with slender elements, Section E7 of the Specification applies. The
nominal compressive strength, Pn, shall be determined based on the limit states of flexural, Section E7
torsional, and flexural-torsional buckling. Depending on the slenderness of the column,
Specification Equation E7-2 or E7-3 applies. Fe is used in both equations and is calculated as
the lesser of Specification Equations E3-4 and E4-4.

For a pinned-pinned condition, K = 1.0
Commentary
Since the unbraced length is the same for both axes, the weak axis will govern. Table
C-C2.2
K y L y 1.0 (15.0 ft ) 12 in. = = 65.9
ry 2.73 in. ft

Calculate the elastic critical stress, Fe, for flexural buckling

π 2 E π 2 29,000 ksi
Fe = 2 = 2 = 65.9 ksi
⎛ KL ⎞ ( 65.9 ) ⎜ ⎟ Eqn. E3-4
⎝ r ⎠

<!-- p. 45 -->

E-16

Calculate the elastic critical stress, Fe, for torsional buckling

Not likely to govern, but check for completeness

I y ho 2 72.4 in. 4 (7.63 in.) 2
Cw = = = 1050 in.6 Design
4 4 Guide No. 3
Eqn 3-5
bt 3 2 (10.5 in. )( 0.375 in. ) 3 + 7.25 in. ( 0.25 in. ) 3
J = = = 0.407 in.4 ∑ Design 3 3
Guide No. 3
Eqn 3-4 ⎡ 2 ⎤ π EC w 1 Fe = ⎢ 2 + GJ ⎥
⎢ x +I y ⎣ ( K z L ) ⎥⎦ I

6 ⎤ 1 Eqn. E4-4 ⎡ π 2 ( 29,000 ksi)(1050in. ) 4 ⎥ = ⎢ 2 + (11,200 ksi)( 0.407in. ) ⎢ 4 4 ⎣ ( 180in.) ⎥⎦ 122in. + 72.4in.
\= 71.2 ksi > 65.9 ksi

Therefore, use Fe = 65.9 ksi

Determine Q, the slenderness reduction factor

Q = QsQa, where Qa = 1.0 because the web is not slender

Calculate Qs, the unstiffened element (flange) reduction factor
Section E7-1
Determine the proper equation for Qs by checking limits for Equations E7-7 to E7-9

b
\= 14.0 from above
t
Section
Ek c 29,000 ksi(0.743)0.64 = 0.64 = 13.3 E7-1(b)
F 50 ksi

Ek c 29,000 ksi(0.743)1.17 = 1.17 = 24.3
Fy 50 ksi

b Ek c Ek c0.64 M 1.17 \< therefore, Equation E7-8 applies.
Fy t Fy
⎛ b ⎞ Fy
Qs = 1.415 − 0.65 ⎜ ⎟
⎝ t ⎠ Ek c

50 ksi = 1.415 − 0.65 (14.0 ) = 0.977 Eqn. E7-8 ( 29,000 ksi )( 0.743 )

Q =QsQa = (0.977)(1.0) = 0.977

<!-- p. 46 -->

E-17

Calculate nominal compressive strength

E 29,000 ksi
4.71 = 4.71 = 115 > 65.9 therefore, Specification Eqn. E7-2 applies.
QFy 0.977 ( 50 ksi )

y ⎡ QF ⎤ ⎡ 0.977 ( 50 ksi ) ⎤
eFcr = Q ⎢ 0.658 F ⎥ Fy = 0.977 ⎢ 0.658 65.9 ksi ⎥ ( 50 ksi ) = 35.8 ksi Eqn. E7-2
⎢ ⎥ ⎢⎣ ⎥⎦ ⎣ ⎦

2Pn = Fcr Ag = ( 35.8 ksi )( 9.69 in ) = 347 kips Eqn. E7-1

LRFD ASD
φc = 0.90 Ωc = 1.67 Section E1
φc nP = 0.90 ( 347 kips ) Pn / Ω=c (347 kips)/1.67
\= 312 kips > 240 kips o.k. = 208 kips > 160 kips o.k.

Note: Built-up sections are generally more expensive than standard rolled shapes; therefore,
a standard compact shape, such as a W8×35 might be a better choice even if the weight is
somewhat higher. This selection could be taken directly from Manual Table 4-1.

<!-- p. 47 -->

E-18

Example E.4a W-Shape Compression Member (Moment Frame)

This example is primarily intended to
illustrate the use of the alignment chart for
sidesway uninhibited columns.

Given:

The member sizes shown for the moment
frame illustrated here (sidesway
uninhibited in the plane of the frame) have
been determined to be adequate for lateral
loads. The material for both the column
and the girders is ASTM A992 grade 50.
The loads shown at each level are the
accumulated dead loads and live loads at
that story. The column is fixed at the base
about the x-x axis of the column.

Determine if the column is adequate to
support the gravity loads shown. Assume
the column is continuously supported in
the transverse direction (the y-y axis of the
column).

Material Properties:
ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-1
Geometric Properties:
W18×50 Ix = 800 in.4 Manual
W24×55 Ix = 1350 in.4 Table 1-1
W14×82 Ag = 24.0 in.2 Ix = 881 in.4

Calculate the required strength for the column between the roof and floor

LRFD ASD
uP = 1.2 ( 41.5 kips ) + 1.6 (125 kips ) = 250 kips aP = 41.5 + 125 = 167 kips

Calculate the effective length factor, K

LRFD ASD
Pu 250 kips Pa 167 kips
\= 2 = 10.4 ksi \< 18 ksi = 2 = 6.96 ksi \<12 ksi
Ag 24.0 in. Ag 24.0 in.

Manual
τ = 1.00 τ = 1.00 Table 4-21

Therefore, no reduction in stiffness for inelastic buckling will be used.

<!-- p. 48 -->

E-19

Determine Gtop and Gbottom
⎛ 881 in. 4 ⎞
( I c / Lc ) ⎝ 14.0 ft ⎠ ∑ ⎜ ⎟ Commentary Gtop = τ = (1.00) 4 = 1.38 C2.2 ( I g / Lg ) ⎛ 800 in. ⎞ ∑ 2 ⎜ ⎟
⎝ 35.0 ft ⎠
⎛ 881 in. 4 ⎞
2 ⎜ ⎟
( I c / Lc ) ⎝ 14.0 ft ⎠ Commentary ∑ Gbottom = τ = (1.00) 4 = 1.63 ( I g / Lg ) ⎛ 1,350 in. ⎞ C2.2 & ∑
2 ⎜ ⎟ Fig. C-C2.4 ⎝ 35.0 ft ⎠

From the alignment chart, K is slightly less than 1.5. Because the column available strength
tables are based on the KL about the y-y axis, the equivalent effective column length of the
upper segment for use in the table is:

( KL ) x 1.5 (14.0 ft ) KL = = = 8.61 ft
⎛ rx ⎞ 2.44
⎜ ⎟
⎝ ry ⎠

Take the available strength of the W14x82 from Manual Table 4.1

At KL = 9 ft, the available strength in axial compression is:
LRFD ASD Manual
φc nP = 942 kips > 250 kips o.k. Pn / Ω=c 627 kips > 167 kips o.k. Table 4-1

Calculate the required strength for the column segment between the floor and the foundation

LRFD ASD
Pu = 1.2(100 kips) + 1.6 (300 kips) Pa = 100 kips + 300 kips
\= 600 kips = 400 kips

Calculate the effective length factor, K

LRFD ASD
Pu 600 kips Pa 400 kips = 2 = 25.0 ksi = 2 = 16.7 ksi
Ag 24.0 in. Ag 24.0 in.

Manual
τ = 0.890 τ = 0.890 Table 4-21

⎛ I ⎞ ⎛ 881 in. 4 ⎞ ⎛ I ⎞ ⎛ 881 in. 4 ⎞ 2 ⎜ ⎟ Σ ⎜ ⎟ Σ⎜ ⎟ 2 ⎜ ⎟ ⎝ 14.0 ft ⎠ ⎝ L ⎝ L ⎠ c ⎝ 14.0 ft ⎠ ⎠ c = 1.45 Gtop = τ = ( 0.890 ) 4 = 1.45 Gtop = τ = ( 0.890 ) 4 ⎛ I ⎞ ⎛ 1350 in. ⎞ ⎛ I ⎞ ⎛ 1350 in. ⎞ Σ⎜ ⎟ 2 ⎜ ⎟ Σ⎜ ⎟ 2 ⎜ ⎟ ⎝ L ⎝ L ⎠ g ⎝ 35.0 ft ⎠ ⎠ g ⎝ 35.0 ft ⎠
Commentary
Section
C2.2b

<!-- p. 49 -->

E-20

Gbottom = 1 ( fixed )

From the alignment chart, K is approximately 1.42. Because the column available strengths
are based on the KL about the y-y axis, the effective column length of the lower segment for
use in the table is:

( KL ) x 1.42 (14.0 ft )KL = = = 8.15 ft
⎛ rx ⎞ 2.44 ⎜ ⎟ ⎜ ⎟ ⎝ ry ⎠
Take the available strength of the W14x82 from Manual Table 4-1

at L = 9 ft, (conservative) the available strength in axial compression is:
LRFD ASD
φc nP = 942 kips > 600 kips o.k. Pn / Ω=c 627 kips > 400 kips o.k. Manual
Table 4-1

A more accurate strength could be determined by interpolation from Manual Table 4-1

<!-- p. 50 -->

E-21

Example E.4b W-Shape Compression Member (Moment Frame)

Determine the available strength of the
column shown subject to the same gravity
loads shown in Example E.4a with the
column pinned at the base about the x-x
axis. All other assumptions remain the
same.

As determined in Example E.4a, for the column segment between the roof and the floor, the
column strength is adequate.

As determined in Example E.4a, for the column segment between the floor and the foundation,
Gtop = 1.45

CommentaryAt the base,
Section Gbot = 10 (pinned)
C2.2b
Note: this is the only change in the analysis.

CommentaryFrom the alignment chart, K is approximately equal to 2.0. Because the column available
Figure C-C2.4strength Tables are based on the effective length, KL, about the y-y axis, the effective column
length of the lower segment for use in the table is:

( KL ) x 2.0 (14.0 ft )KL = = = 11.5 ft
⎛ rx ⎞ 2.44 ⎜ ⎟ ⎜ ⎟ ⎝ ry ⎠

Interpolate the available strength of the W14×82 from Manual Table 4-1

LRFD ASD
φc nP = 863 kips > 600 kips o.k. Pn / Ω=c 574 kips > 400 kips o.k. Manual
Table 4-1

<!-- p. 51 -->

E-22

Example E.5 Double Angle Compression Member without Slender Elements

Given:
Verify the strength of a 2L4×32×a LLBB (w-in. separation) strut
with a length of 8 ft and pinned ends carrying an axial dead load of 20
kips and live load of 60 kips. Also, calculate the required number of
fully tightened or welded intermediate connectors required.

Material Properties: Manual
ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-3

Geometric Properties:
2L4×32×a LLBB rz = 0.719 in. (single angle) rx = 1.25 in. Manual
ry = 1.55 in. for a inch separation Table 1-15
ry = 1.69 in. for w inch separation Table 1-7

Calculate the required strength

LRFD ASD
Pu = 1.2(20 kips) + 1.6(60 kips) = 120 kips Pa = 20 kips + 60 kips = 80.0 kips

Select a column using Manual Table 4-9

K = 1.0 Commentary
Table C-C2.2
For (KL)x = 8 ft, the available strength in axial compression is taken from the upper (x-x)
portion of the table as
LRFD ASD
φc Pn= 127 kips > 120 kips o.k. Pn/ Ωc = 84.2 kips > 80.0 kips o.k. Manual
Table 4-9

For buckling about the y-y axis, the values are tabulated for a separation of a in.

To adjust to a spacing of w in., (KL)y is multiplied by the ratio of the ry for a a-in. separation
to the ry for a w-in. separation. Thus,
⎛ 1.55 in. ⎞ 1.0 ( 8.00 ft ) ⎜ ⎟ = 7.34 ft ( KL ) y = ⎝ 1.69 in. ⎠

The calculation of the equivalent (KL)y above is a simplified approximation of Specification
Section E6.1. To ensure a conservative adjustment for a ¾ in. separation, take (KL)y = 8 ft.

<!-- p. 52 -->

E-23

The available strength in axial compression is taken from the lower (y-y) portion of the table
as
LRFD ASD
φc Pn= 130 kips > 120 kips o.k. Pn/ Ωc = 86.5 kips > 80.0 kips o.k. Manual
Table 4-9

Therefore, x-x axis flexural buckling governs.

Determine the number of intermediate connectors required

Per Table 4-12, at least two welded or pretensioned bolted intermediate connectors are
required. This can be verified as follows:

(8.00 ft) 12 in. ( ft ) Section E6.2 a = distance between connectors = = 32.0 in.
3 spaces

The effective slenderness ratio of the individual components of the built-up member based
upon the distance between intermediate connectors, a, must not exceed three quarters of the
controlling slenderness ratio of the overall built-up member.
Ka 3 ⎛ Kl ⎞
Therefore: ≤ ⎜ ⎟ ri 4 ⎝ r ⎠ max
⎛ KL ⎞
3ri ⎜ ⎟
⎝ r ⎠ maxSolving for a gives, a ≤
4 K
KL 1.0(8.00 ft)(12 in./ft)
\= = 76.8 controls
rx 1.25 in.
KL 1.0(8.00 ft)(12 in./ft)
\= = 56.8
ry 1.69 in.

⎛ KL ⎞
3 rz ⎜ ⎟
⎝ r ⎠ max 3(0.719in.)(76.8)Thus, a ≤ = = 41.4 in. > 32.0 in. o.k.
4 K 4(1.0)

The available strength can be easily determined by using the tables of the Manual. Available
strength values can be verified by hand calculations, as shown below.

Calculation Solution:

Geometric Properties:
2L4×32×a LLBB Ag = 5.34 in.2 ry = 1.69 in. r0 = 2.33 in. H = 0.813 Manual
Table 1-15 J = 0.132 in.4 (single angle) ry = 1.05 in. (single angle)
Table 1-7 x = 0.947 in. (single angle)

Check for slender elements

b 4.0 in.
\= = 10.7
t 0.375 in.
λr = 0.45 E = 0.45 29,000 ksi = 12.8 >10.7
Fy 36 ksi
Therefore, there are no slender elements.

<!-- p. 53 -->

E-24

For compression members without slender elements, Specification Sections E3 and E4 apply.
The nominal compressive strength, Pn, shall be determined based on the limit states of flexural,
torsional, and flexural-torsional buckling.

Check flexural buckling about the x-x axis Section E3

KL 1.0(8.00ft)(12 in./ft)
\= = 76.8
rx 1.25 in.

π 2 E π 2 ( 29,000 ksi ) Eqn. E3-4
Fe = 2 = 2 = 48.5 ksi
⎛ KL ⎞ (76.8)
⎜ ⎟
⎝ r ⎠
E 29,000 ksi
4.71 = 4.71 = 134 > 76.8, therefore
Fy 36 ksi

y 36 ksi ⎡ F ⎤ ⎡ ⎤ Fe 48.5 ksiFcr = ⎢ 0.658 ⎥ Fy = ⎢ 0.658 ⎥ ( 36 ksi ) = 26.4 ksi controls Eqn. E3-2
⎢ ⎥ ⎣ ⎦ ⎣ ⎦

Check torsional and flexural-torsional buckling
Section E4
For non-slender double angle compression members, Specification Equation E4-2 applies.

Fcry is taken as Fcr, for flexural buckling about the y-y axis from Specification Equation E3-2 or
E3-3 as applicable.

KL
Compute the modified for built up members with fully tightened or welded connectors Section E6
ry

a = 96.0 in. / 3 = 32.0 in.

rib = ry (single angle) = 1.05 in.

h 2 x + 0.750in. 2 ( 0.947in. ) + 0.750in.α = = = = 1.26
2 rib 2ry 2 (1.05 in. )
⎛ KL ⎞ ⎛ KL ⎞ 2 α 2 ⎛ a ⎞ 2
⎜ ⎟ = ⎜ ⎟ + 0.82 2 ⎜ ⎟ Eqn. E6-2
⎝ r ⎠ m ⎝ r ⎠ o (1 + α ) ⎝ rib ⎠
2 (1.26 ) 2 ⎛ 32.0in. ⎞ 2 = ( 56.8 ) + 0.82 2 ⎜ ⎟ = 60.7 \< 134
1 + (1.26 ) ⎝ 1.05in. ⎠
π 2 E π 2 ( 29,000 ksi )
Fe = 2 = 2 = 77.7 ksi
⎛ KL ⎞ (60.7) Eqn. E3-4
⎜ ⎟
⎝ r ⎠

y 36 ksi ⎡ F ⎤ ⎡ ⎤ Fe 77.7 ksiFcry = ⎢ 0.658 ⎥ Fy = ⎢ 0.658 ⎥ ( 36 ksi ) = 29.7 ksi Eqn. E3-2
⎢ ⎥ ⎣ ⎦ ⎣ ⎦

<!-- p. 54 -->

E-25

4 GJ (11,200 ksi ) (2 angles) ( 0.132 in. )
Fcrz = 2 = 2 = 102 ksi Eqn. E4-3
Ag r0 ( 5.34 in. )( 2.33 in. )
⎡ ⎤
⎛ Fcry + Fcrz ⎞⎢ 4 Fcry Fcrz H ⎥ Eqn. E4-2 1 − 1 −Fcr = ⎜ ⎝ 2 H ⎟⎢⎠
⎢⎣ ( Fcry + Fcrz ) 2 ⎥⎥⎦

⎛ 29.7ksi + 102 ksi ⎞ ⎡ 4 ( 29.7ksi )(102 ksi )( 0.813 ) ⎤ ⎥ ⎢1 − 1 − = ⎜ ⎟ ⎜ = 27.8 ksi ⎟⎢ ⎥ 0.813 ) ( 29.7ksi + 102 ksi ) 2 ⎝ 2 ( ⎠⎣ ⎦

does not control

Pn = Fcr Ag = ( 26.4 ksi ) 5.34 in 2 = 141 kips Eqn. E4-1

LRFD ASD
φc = 0.90 Ωc = 1.67 Section E1
φ c nP = 0.90 (141 kips ) = 127 kips 141 kips Pn / Ω=c = 84.4 kips
\> 120 kips o.k. 1.67
\> 80.0 kips o.k.

<!-- p. 55 -->

E-26

Example E.6 Double Angle Compression Member with Slender Elements

Given:
Determine if a 2L5×3×4 LLBB (w-in. separation) strut with a length
of 8 ft and pinned ends has sufficient available strength to support a
dead load of 10 kips and live load of 30 kips in axial compression.
Also, calculate the required number of fully tightened or welded
intermediate connectors.

Material Properties:
ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-3
Geometric Properties:
2L5×3×4 LLBB rz = 0.652 in. (single angle) rx = 1.62 in. Manual
ry = 1.19 in. for a inch separation Table 1-15
ry = 1.33 in. for w inch separation Table 1-7

Calculate the required strength

LRFD ASD
uP = 1.2 (10.0 kips ) + 1.6 ( 30.0 kips ) = 60.0 kips aP = 10.0 kips + 30.0 kips = 40.0 kips

Table Solution:
Commentary
K = 1.0 Table C-C2.2

From the upper portion of Manual Table 4-9, the available strength for buckling about the x-x
axis, with (KL)x = 8 ft is

LRFD ASD Manual
φc Pnx = 87.2 kips > 60.0 kips o.k. Pnx / Ω=c 58.0 kips > 40.0 kips o.k. Table 4-9

For buckling about the y-y axis, the tabulated values are based on a separation of a in. To
adjust for a spacing of w in., (KL)y is multiplied by the ratio of ry for a a-in. separation to ry
for a w-in. separation.

⎛ 1.19 in. ⎞ 1.0 ( 8.0 ft ) ⎜ ⎟ = 7.16 ft ( KL ) y = ⎝ 1.33 in. ⎠

This calculation of the equivalent (KL)y does not completely take into account the effect of
section E6.1 and is slightly unconservative.

From the tabulated values in the lower portion of Manual Table 4-9, interpolate for a value at
(KL)y = 7.16 ft,

<!-- p. 56 -->

E-27

The available strength in compression is:
LRFD ASD Manual
φc Pny = 65.1 kips > 60.0 kips o.k. Pny / Ω=c 43.3 kips > 40.0 kips o.k. Table 4-9

These strengths are approximate due to the linear interpolation from the Table and the
approximate value of the equivalent (KL)y noted above. These can be compared to the more
accurate values calculated in detail below.

Determine the number of intermediate connectors required.

From the tabulated values, it is determined that at least two welded or pretensioned bolted Manual
intermediate connectors are required. This can be confirmed by calculation, as follows: Table 4-9

(8.00 ft) 12 in. ( ft ) a = distance between connectors = = 32.0 in.
3 spaces

The effective slenderness ratio of the individual components of the built-up member based Section E6.2
upon the distance between intermediate connectors, a, must not exceed three quarters of the
controlling slenderness ratio of the overall built-up member.
Ka 3 ⎛ Kl ⎞
Therefore, ≤ ⎜ ⎟ ri 4 ⎝ r ⎠ max
⎛ KL ⎞
3 ri ⎜ ⎟
⎝ r ⎠ maxSolving for a gives, a ≤
4 K

ri = rz = 0.652 in.

KLx 1.0 ( 8.0 ft )(12.0 in./ft ) = = 59.3
rx 1.62 in.
KL y 1.0 ( 8.0 ft )(12.0 in./ft ) = = 72.2 controls
ry 1.33 in.
⎛ KL ⎞
3 rz ⎜ ⎟ ⎝ r ⎠ max 3 ( 0.652 in. )( 72.2 )Thus, a ≤ = = 35.3 in. > 32.0 in. o.k.
4 K 4 (1.0 )

The governing slenderness ratio used in the calculations of the Manual Table include the
effects of the provisions of Section E6.1 and is slightly higher as a result. See below for these
calculations. As a result, the maximum connector spacing calculated here is slightly
conservative.

Available strength values can be verified by hand calculations, as shown below.

Calculation Solution:

Geometric Properties:
2L5×3×4 LLBB Ag = 3.88 in.2 ry = 1.33 in. or = 2.59 in. H = 0.657 Manual
Tables 1-15, J = 0.0438 in.4 (single angle) ry = 0.853 in. (single angle)
1-7 and 4-9 x = 0.648 in. (single angle)

<!-- p. 57 -->

E-28

Determine if the section is noncompact or slender

b 5.00 in. Table B4.1
\= = 20.0 Case 5 t 0.250 in.

Calculate the limiting width-thickness ratios

E 29,000 ksi
λ r = 0.45 = 0.45 = 12.8 \< 20.0 Therefore the angle has a slender element.
Fy 36 ksi
For a double angle compression member with slender elements, Specification Section E7
applies. The nominal compressive strength, Pn, shall be determined based on the limit states
of flexural, torsional, and flexural-torsional buckling. Depending on the elastic critical
buckling stress, Fe, of the member, Fcr will be determined by Specification E7-2 or E7-3.

Determine Q, the slender element reduction factor
Section E7
Q = Qs(Qa=1.0) for members composed of unstiffened slender elements.

Calculate Qs for the angles individually using Specification Section E7.1c
Section
E7.1c
E 29,000 ksi
0.45 = 0.45 = 12.8 \< 20.0
Fy 36 ksi

E 29,000 ksi
0.91 = 0.91 = 25.8 > 20.0
Fy 36 ksi

Therefore, Specification Equation E7-11 applies.

⎛ b ⎞ Fy
Qs = 1.34 − 0.76 ⎜ ⎟
⎝ t ⎠ E Eqn. E7-11
36 ksi = 1.34 − 0.76 ( 20.0 ) = 0.804
29,000 ksi
Qa = 1.0 (no stiffened elements)

Therefore, Q = Qs Qa = 0.804 (1.0 ) = 0.804

Determine the applicable equation for the critical stress, Fcr

From above, K = 1.0

Specification Equation E7-2 requires the computation of Fe. For singly symmetric members,
Specification Equations E3-4 and E4-5 apply.

<!-- p. 58 -->

E-29

Check x-x axis flexural buckling

K x L 1.0 ( 8.0 ft )(12.0 in./ft ) = = 59.3
rx 1.62 in.
π 2 E π 2 ( 29,000 ksi )
Fe = 2 = 2 =81.4 ksi does not govern Eqn. E3-4
⎛ K x L ⎞ (59.3)
⎜ ⎟
⎝ rx ⎠

Check torsional and flexural-torsional buckling

K y L 1.0 ( 8.0 ft )(12.0 in./ft ) = = 72.2
ry 1.33 in.
KL
Compute the modified for built up members with fully tightened or welded connectors Section E6 ry

a = 96.0 in. / 3 = 32.0 in.

rib = ry (single angle) = 0.853 in.

h 2 x + 0.750in. 2 ( 0.648in. ) + 0.750in.α = = = = 1.20
2 rib 2ry 2 ( 0.853 in. )
⎛ KL ⎞ ⎛ KL ⎞ 2 α 2 ⎛ a ⎞ 2
⎜ ⎟ = ⎜ ⎟ + 0.82 2 ⎜ ⎟ Eqn. E6-2
⎝ r ⎠ m ⎝ r ⎠ o (1 + α ) ⎝ rib ⎠
2 (1.20 ) 2 ⎛ 32.0in. ⎞ 2 = ( 72.2 ) + 0.82 2 ⎜ ⎟ = 76.8
1 + (1.20 ) ⎝ 0.853in. ⎠

π 2 E π 2 ( 29,000 ksi )
Fey = 2 = 2 =48.6 ksi
⎛ K y L ⎞ (76.8) Eqn. E4-10
⎜ ⎟ ⎜ ⎟ ⎝ ry ⎠ m
⎛ 2 ⎞ π EC w 1Fez = ⎜ 2 + GJ ⎟ 2 ⎜ g ro Eqn. E4-11 ⎝ ( K z L ) ⎟⎠ A

For double angles, omit term with Cw per User Note at end of Section E4.

4 GJ (11,200 ksi )( 2angles )( 0.0438in. )
Fez = 2 = 2 = 37.7ksi
Ag ro 3.88in. ( 2.59in. )

⎡ ⎤
⎛ Fey + Fez ⎞⎢ 4 Fey Fez H ⎥ 1 − 1 −Fe = ⎜ ⎟⎢ ⎝ 2 H ⎠ Eqn. E4-5 ⎢⎣ ( Fey + Fez ) 2 ⎥⎦⎥

<!-- p. 59 -->

E-30

⎛ 48.6 ksi + 37.7ksi ⎞ ⎡ 4 ( 48.6 ksi )( 37.7ksi )( 0.657 ) ⎤ ⎥ = ⎢1 − 1 − ⎜ ⎟ ⎟⎢ ⎥ ⎜ 2 ( 0.657 ) ( 48.6 ksi + 37.7ksi ) 2 ⎝ ⎠⎣ ⎦

\= 26.6 ksi governs

0.44QFy = 0.44(0.804)(36 ksi) = 12.7 ksi \< 26.6 ksi, therefore Equation E7-2 applies.

y )( 36 ⎡ QF ⎤ ⎡ ( 0.804 ksi ) ⎤ Eqn. E7-2
Fe 26.6 ksiFcr = Q ⎢ 0.658 ⎥ Fy = 0.804 ⎢ 0.658 ⎥ ( 36 ksi ) = 18.4 ksi
⎢ ⎥ ⎢⎣ ⎥⎦ ⎣ ⎦
2 = 71.3 kips Eqn. E7-1Pn = Fcr Ag = (18.4 ksi ) 3.88 in.

LRFD ASD
φc = 0.90 Ωc = 1.67
71.3 kips Section E1 φ c nP = 0.90 ( 71.3 kips ) Pn / Ω=c
1.67
\= 64.1 kips > 60.0 kips o.k. = 42.7 kips > 40.0 kips o.k.

<!-- p. 60 -->

E-31

Example E.7 Design of a WT Compression Member without Slender Elements

Given:
Select a WT-shape compression member with a length of 20 ft to
support a dead load of 20 kips and live load of 60 kips in axial
compression. The ends are pinned.

Because WT sections are cut from ASTM A992 W-shape beams, the material properties are:

Material Properties:
ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3

Calculate the required strength

LRFD ASD
uP = 1.2 ( 20.0 kips ) + 1.6 ( 60.0 kips ) = 120 kips aP = 20.0 kips + 60.0 kips = 80.0 kips

Table Solution:

K = 1.0 Therefore (KL)x = (KL)y = 20.0 ft Commentary
Table C-C2.2
Select the lightest member from Table 4-7 with sufficient available strength about the both the
x-x (upper portion of the table) and the y-y axis (lower portion of the table) to support the
required strength.

Try a WT7×34

The available strength in compression is:
LRFD ASD
φ c Pnx = 128 kips > 120 kips Controls o.k. Pnx / Ω=c 85.2 kips > 80.0 kips Controls o.k. Manual
Table 4-7 φ c Pny = 221 kips > 120 kips o.k. Pny / Ω=c 147 kips > 80.0 kips o.k.

The available strength can be easily determined by using the tables of the Manual. Available
strength values can be verified by hand calculations, as shown below.

Calculation Solution:

Geometric Properties:
WT7×34 Ag = 9.99 in. 2 xr = 1.81 in. yr = 2.46 in. or = 3.19 in. J = 1.50 in. 4
Manual H = 0.916 d = 7.02 in. tw = 0.415 in. bf = 10.0 in. tf = 0.720 in. Table 1-8

<!-- p. 61 -->

E-32

Check for slender elements
d 7.02in. E 29,000ksi
\= = 16.9 \< 0.75 = 0.75 = 18.1 therefore, the web is not slender. Table B4.1
t w 0.415in. Fy 50ksi Case 8

b f 10 in. E 29,000 ksi
\= = 6.94 \< 0.56 = 0.56 = 13.5 therefore, the flange is not Table B4.1
2t f 2(0.720 in.) Fy 50 ksi Case 3
slender.

There are no slender elements.

For compression members without slender elements, Specification Sections E3 and E4 apply.
The nominal compressive strength, Pn, shall be determined based on the limit states of flexural,
torsional, and flexural-torsional buckling.

Check flexural buckling about the x-x axis
Section E3
KL 1.0(20.0 ft)(12 in./ft)
\= = 133
rx 1.81 in.

E 29, 000 ksi
\4. 71 = 4 .71 = 113 \< 133 therefore, Specification Equation E3-3 applies.
Fy 50 ksi
π 2 E π 2 ( 29,000 ksi ) Eqn. E3-4 Fe = 2 = 2 =16.3 ksi
⎛ KL ⎞ (133)
⎜ ⎟
⎝ r ⎠
Fcr = 0.877 Fe = 0.877(16.3 ksi) = 14.3 ksi controls Eqn. E3-3

Because the WT7×34 section does not have any slender elements, Specification Section E4
will be applicable for torsional and flexural-torsional buckling. Fcr will be calculated using
Specification Equation E4-2

Calculate Fcry

KL KL
Fcry is taken as Fcr From Specification Section E3, where =
r ry

KL 1.0 ( 20.0 ft )(12 in./ft ) = = 97.6 \< 113 therefore, Eqn. E3-2 applies
ry 2.46 in.

π 2 E π 2 ( 29,000 ksi )
Fe = 2 = 2 =30.1 ksi
⎛ KL ⎞ (97.6) Eqn. E3-4
⎜ ⎟
⎝ r ⎠

y ⎡ F ⎤ ⎡ 50.0ksi ⎤ 30.1ksi FeFcry = Fcr = ⎢ 0.658 ⎥ Fy = ⎢ 0.658 ⎥ 50.0 ksi = 24.9 ksi Eqn. E3-2
⎢ ⎥ ⎢⎣ ⎥⎦ ⎣ ⎦

<!-- p. 62 -->

E-33

4 GJ (11,200 ksi )(1.50 in. )
Fcrz = 2 = 2 2 = 165 ksi Eqn. E4-3 Ag ro ( 9.99 in. )( 3.19 in. )
⎡ ⎤ 4 F H + ⎛ Fcry Fcry crz Fcrz ⎞⎢ ⎥Fcr = ⎜ Eqn. E4-2 ⎟⎢1 − 1 − ⎥ 2 H F ⎝ + Fcry crz ( ) 2 ⎠⎣ ⎦

⎛ 24.9 ksi + 165 ksi ⎞ ⎡ 4 ( 24.9 ksi )(165 ksi )( 0.916 ) ⎤ ⎥ = ⎢1 − 1 − ⎜ ⎟ ⎟⎢ ⎥ ⎜ 2 ( 0.916 ) ( 24.9 ksi + 165 ksi ) 2 ⎝ ⎠⎣ ⎦

\= 24.5 ksi does not control

x-x axis flexural buckling governs, therefore

2 = 143 kipsPn = Fcr Ag = (14.3 ksi ) 9.99 in. Eqn. E3-1

LRFD ASD
φc nP = 0.90 (143kips ) 143kips Section E1 Pn / Ω=c
1.67
\= 128 kips > 120 kips o.k. = 85.4 kips > 80.0 kips o.k.

<!-- p. 63 -->

E-34

Example E.8 Design of a WT Compression Member with Slender Elements

Given:
Select a WT-shape compression member with a length of 20 ft to
support a dead load of 5 kips and live load of 15 kips in axial
compression. The ends are pinned.

Because WT sections are cut from ASTM A992 W-shape beams, the material properties are:

Material Properties:
ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3
Calculate the required strength
LRFD ASD
uP = 1.2 ( 5.00 kips ) + 1.6 (15.0 kips ) = 30.0 kips aP = 5. 00 kips + 15 .0 kips = 20.0 kips

Table Solution:

K = 1.0, therefore (KL)x = (KL)y = 20 ft. Commentary
Table C-C2.2
Select the lightest member from Table 4-7 with sufficient available strength about the both the
x-x (upper portion of the table) and the y-y axis (lower portion of the table) to support the
required strength.

Try a WT7×15

Determine the available strength in axial compression from Manual Table 4-7

LRFD ASD
φ c Pnx = 66.6 kips > 30.0 kips o.k. Pnx / Ω=c 44.3 kips > 20.0 kips o.k. Manual
Table 4-7 φ c Pnx = 36.5 kips > 30.0 kips controls o.k. Pny / Ω=c 24.3 kips > 20.0 kips controls o.k.

The available strength can be easily determined by using the tables of the Manual. Available
strength values can be verified by hand calculations, as shown below.

Calculation Solution:

Geometric Properties:
WT7×15 Ag = 4.42 in. 2 xr = .2 07 in. yr = .1 49 in. or = .2 90 in. J = 0 .190 in. 4 Manual
Table 1-8 H = .0772 Qs = 0.609 d = 6.92 in. tw = 0.270 in. bf = 6.73 in.
tf = 0.385 in.

<!-- p. 64 -->

E-35

Check for slender elements

d 6.92 in. E 29,000 ksi
\= = 25.6 > 0.75 = 0.75 = 18.1 therefore, the web is slender. Table B4.1
t w 0.270 in. Fy 50 ksi Case 8

b f 6.73 in. Table B4.1
\= Case 3
2t f 2(0.385 in.)
therefore, the flange is not slender.
E 29,000 ksi
\= 8.74 \< 0.56 = 0.56 = 13.4
Fy 50 ksi

Because this WT7×15 has a slender web, Specification Section E7 is applicable. The nominal
compressive strength, Pn, shall be determined based on the limit states of flexural, torsional,
and flexural-torsional buckling.

Calculate the x-x axis critical elastic flexural buckling stress

K x L 1.0 ( 20.0 ft )(12 in./ft ) = = 116
rx 2.07 in.
π 2 E π 2 (29,000 ksi) Eqn. E3-4
Fe = 2 = 2 = 21.3 ksi does not control
⎛ KL ⎞ (116 )
⎜ ⎟
⎝ r ⎠

Calculate the critical elastic torsional and flexural-torsional buckling stress

K y L 1.0 ( 20.0 ft )(12 in./ft ) = = 161
ry 1.49 in.

π 2 E π 2 (29,000 ksi)
Fey = 2 = 2 = 11.0 ksi Eqn. E4-10
⎛ K y L ⎞ (161)
⎜ ⎟ ⎜ ⎟ ⎝ ry ⎠

⎛ π ⎞ 1 2 EC wFez = ⎜ 2 + GJ ⎟ 2 Omit term with Cw per User Note at end of Section E4 Eqn. E4-11 ⎜ g ro ⎝ ( K z L ) ⎟⎠ A

GJ 11, 200ksi ( 0. 190in. 4 )
Fez = 2 = 2 2 = 57. 2 ksi
Ag ro 4. 42in. ( 2 .90in.)

⎛ Fey + Fez ⎞ ⎡ 4 Fey Fez H ⎤
Fe = ⎜ ⎟ ⎢1 − 1 − ⎥
⎝ 2 H ⎠⎣⎢ ( Fey + Fez )2 ⎥⎦ Eqn. E4-5

<!-- p. 65 -->

E-36

⎛ 11 . 0ksi + 57. 2ksi ⎞ ⎡ 4 (11 .0ksi )( 57 .2ksi )( 0 .772 ) ⎤
eF = ⎜ ⎟ ⎢1 − 1 − ⎥ = 10 .5 ksi controls
⎝ 2 ( 0 . 772 ) ⎠⎣ (11 .0ksi + 57 .2ksi )2 ⎦

The cross section is composed of only unstiffened compression elements.
Therefore, Qa = 1.0

Q = Qs (Qa = 1.0) = 0.609

Check limit for the applicable equation

0.44QFy = 0.44(0.609)(50 ksi) = 13.4 ksi > 10.5 ksi therefore Eqn. E7-3 applies

Eqn. E7-3Fcr = 0.877 Fe = 0.877 (10.5 ksi ) = 9.21 ksi
2 = 40.7 kips Eqn. E7-1Pn = Fcr Ag = ( 9.21 ksi ) 4.42 in.

LRFD ASD
φc = 0.90 Ωc = 1.67
φc nP = 0.90 ( 40.7kips ) Pn / Ω=c 40.7kips/1.67 Section E1
\= 36.5 kips > 30.0 kips o.k. = 24.3 kips > 20.0 kips o.k.

<!-- p. 66 -->

E-37

Example E.9 Design of a Rectangular HSS Compression Member without
Slender Elements

Given:
Select a rectangular HSS compression member, with a length of 20 ft,
to support a dead load of 85 kips and live load of 255 kips in axial
compression. The base is fixed and the top is pinned.

Material Properties:
ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Manual
Table 2-3
Calculate the required strength

LRFD ASD
uP = 1.2 ( 85.0 kips ) + 1.6 ( 255 kips ) = 510 kips aP = 85.0 kips + 255 kips = 340 kips

Table Solution:

K = 0.8 Commentary
Table C-C2.2
(KL)x = (KL)y = 0.8(20.0 ft) = 16.0 ft

Enter Manual Table 4-3 for rectangular sections or Table 4-4 for square sections.
Try an HSS12×10×2

Determine the available strength in axial compression

LRFD ASD
φ c nP = 673 kips > 510 kips o.k. Pn / Ω=c 448 kips > 340 kips o.k. Manual
Table 4-3

The available strength can be easily determined by using the tables of the Manual. Available
strength values can be verified by hand calculations, as shown below.

Calculation Solution:

Geometric Properties: Manual
HSS12×10×2 Ag = 19.0 in. 2 xr = 4.56 in. yr = 3.96 in. tdes = 0.465 in. Table 1-11

<!-- p. 67 -->

E-38

Check for slender elements

Note: if the corner radius is not known, b and h shall be taken as the outside dimension less Section B4
three times the design wall thickness. This is generally a conservative assumption.

Calculate b/t of the most slender wall

Table B4.1 h 12.0 in.-3(0.465in.) E 29,000 ksi
\= = 22.8 \< 1.40 = 1.40 = 35.2 Case 12
t 0.465in. Fy 46 ksi
Therefore, the section does not contain slender elements.

Since ry \< rx and (KL)x = (KL)y, ry will govern the available strength.

Determine the applicable equation

K y L 0. 8 ( 20 .0 ft )(12 in./ft ) = = 48 .5
ry 3.96 in.

E 29, 000 ksi
\4. 71 = 4. 71 = 118 > 48.5, therefore, use Specification Equation E3-2. Section E3 Fy 46 ksi
π 2 E π 2 ( 29, 000 )
Fe = 2 = 2 = 122 ksi
⎛ KL ⎞ ( 48. 5 )
⎜ ⎟ Eqn. E3-4
⎝ r ⎠

y 46 ksi ⎛ F ⎞ ⎛ ⎞ Fe 122 ksi 0 .658 ⎟Fcr = ⎜ Fy = ⎜ 0. 658 ⎟ ( 46 ksi ) = 39.3 ksi Eqn. E3-2 ⎜ ⎟ ⎝ ⎠ ⎝ ⎠
Pn = Fcr Ag = ( 39 .3 ksi ) 19 . 0 in. 2 = 746 kips Eqn. E3-1

LRFD ASD
φc = 0.90 Ωc = 1.67
746 kips Specification φc nP = 0.90 ( 746 kips ) Pn / Ω=c Section E1 1.67
\= 673 kips > 510 kips o.k. = 448 kips > 340 kips o.k.

<!-- p. 68 -->

E-39

Example E.10 Design of a Rectangular HSS Compression Member with
Slender Elements

Given:
Select a rectangular HSS12×8 compression member with a length of
30 ft, to support an axial dead load of 26 kips and live load of 77 kips.
The base is fixed, the top is pinned.

A column with slender elements has been selected to demonstrate the
design of such member.

Material Properties: Manual
ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Table 2-3

Calculate the required strength

LRFD ASD
uP = 1.2 ( 26.0 kips ) + 1.6 ( 77.0 kips ) = 154 kips aP = 26. 0 kips + 77 .0 kips = 103 kips

Table Solution:

K = 0.8 Therefore (KL)x = (KL)y = 0.8(30.0 ft) = 24.0 ft Commentary
Table C-C2.2
Enter Manual Table 4-3, in the HSS12×8 section and proceed across the page until the lightest
section is found with an available strength that is equal to or greater than the required strength,
in this case a HSS 12×8×x.

Determine the available strength in axial compression
LRFD ASD
φ c nP = 155 kips > 154 kips o.k. Pn / Ω=c 103 kips ? 103 kips o.k. Manual
Table 4-3

The available strength can be easily determined by using the tables of the Manual. Available
strength values can be verified by hand calculations, as shown below, including adjustments
for slender elements.

Calculation Solution:

Geometric Properties:
2 b
HSS12×8×x Ag = 6.76 in. xr = 4.56 in. yr = .3 35 in. = 43.0 Manual t
Table 1-11 h
\= 66.0 tdes = 0.174 in.
t

<!-- p. 69 -->

E-40

Determine for slender elements

Calculate the limiting width-thickness ratios

E 29,000 ksi
λ r = 1.40 = 1.40 = 35.2 \< 43.0 therefore both the 10-in. and 12-in. walls are Table B4.1
Fy 46 ksi Case 12
slender elements.

Note that for determining the width-thickness ratio, b is taken as the outside dimension minus
three times the design wall thickness.

For the selected shape

b = 8.00 in. – 3(0.174 in.) = 7.48 in. Specification
h = 12.0 in. – 3(0.174 in.) = 11.5 in. Section
B4.2d
For an HSS member with slender elements, the nominal compressive strength, Pn, shall be
determined based upon the limit states of flexural buckling. Torsional buckling will not
govern unless the torsional unbraced length greatly exceeds the controlling flexural unbraced
length.

Compute effective area, Aeff Section E7
Aeff
Qa = Eqn. E7-16 A

where

Aeff = summation of the effective areas of the cross section based on the reduced effective
widths be.

For flanges of square and rectangular slender element section of uniform thickness,

E ⎡ 0.38 E ⎤
be = 1.92 t ⎢1 − ⎥ M b
Eqn. E7-18 f ⎢⎣ ( b t ) f ⎥⎦
where f = Pn /Aeff, but can conservatively be taken as Fy

For the 8-in. walls,

E ⎡ 0.38 E ⎤ Eqn. E7-18be = 1.92 t ⎢1 − ⎥
Fy ⎢⎣ ( b t ) Fy ⎥⎦
29,000 ksi ⎡ 0.38 29,000 ksi ⎤
\= 1.92(0.174in.) ⎢1 − ⎥ = 6.53 in. M 7.48 in.
46 ksi ⎢⎣ ( 43.0 ) 46ksi ⎥⎦

Length that can not be used = b – be = 7.48 in. – 6.53 in. = 0.950 in.

For the 12 inch walls.

<!-- p. 70 -->

E-41

E ⎡ 0.38 E ⎤
be = 1.92 t ⎢1 − ⎥
Fy ⎢⎣ ( b t ) Fy ⎥⎦
29,000ksi ⎡ 0.38 29,000ksi ⎤
\= 1.92(0.174in.) ⎢1 − ⎥ = 7.18 in. M 11.5 in. Eqn. E-16
46ksi ⎢⎣ ( 66.0 ) 46ksi ⎥⎦

Length that can not be used = 11.5 in. – 7.18 in. = 4.32 in.

Therefore Aeff = 6.76 in.2 – 2(0.174 in.)(0.950 in.) – 2(0.174 in.)(4.32 in.) = 4.93 in.2

Aeff 4.93 in. 2
Therefore Q = Qa = = 2 = 0.729 A 6.76 in.

Determine the appropriate equation for Fcr

K y L 0.8(30.0 ft)(12 in./ ft) E 29,000 ksi
\= = 86.0 \< 4.71 = 4.71 = 139
ry 3.35in. QFy 0.729(46 ksi)

y ⎡ QF ⎤ Eqn. E7-2
eTherefore Fcr = Q ⎢ 0.658 F ⎥ Fy
⎢ ⎥ ⎣ ⎦

π 2 E π 2 (29,000 ksi) Eqn. E3-4
Fe = 2 = 2 = 38.7 ksi
⎛ KL ⎞ 86.0
⎜ ⎟
⎝ r ⎠

QF y 0.729(46 ⎡ ⎤ ⎡ ksi) ⎤ Fe 38.7 ksi ⎢ 0.658Fcr = Q ⎥ Fy = 0.729 ⎢ 0.658 ⎥ 46 ksi = 23.3 ksi. Eqn. E7-2
⎢ ⎥ ⎣ ⎦ ⎣ ⎦
Eqn. 7-1Pn = FcrAg = 23.3 ksi(6.76 in.2) = 158 kips

LRFD ASD
φc = 0.90 Ωc = 1.67
Section E1 158 kips φc nP = 0.90 (158 kips ) = 142 kips \< 154 kips Pn / Ω=c = 94.7 kips \< 103 kips
1.67
See note below See note below

Note: A conservative initial assumption (f = Fy) was made in applying Specification Equation
E7-18. A more exact solution is obtained by iterating from the Compute effective area, Aeff
step using f = Pn/Aeff until the value of f converges. The HSS column strength tables in the
Manual were calculated using this iterative procedure.

<!-- p. 71 -->

E-42

Example E.11 Design of a Pipe Compression Member

Given:
Select a Pipe compression member with a length 30 ft to
support a dead load of 35 kips and live load of 105 kips in
axial compression. The column is pin-connected at the ends
in both axes and braced at the midpoint in the y-y direction.

Material Properties: Manual
ASTM A53 Gr. B Fy = 35 ksi Fu = 60 ksi Table 2-3

Calculate the required strength

LRFD ASD
uP = 1.2 ( 35.0 kips ) + 1.6 (105 kips ) = 210 kips aP = 35.0 kips + 105 kips = 140 kips

Table Solution:
K = 1.0 Therefore, (KL)x = 30.0 ft and (KL)y = 15.0 ft Buckling about the x-x axis controls. Commentary
Table C-C2.2
Enter Manual Table 4-6 with a KL of 30 ft and proceed across the table until reaching the
lightest section with sufficient available strength to support the required strength.

Try a 10 inch Standard Pipe. The available strength in axial compression is:

LRFD ASD
φ c nP = 215 kips > 210 kips o.k. Pn / Ω=c 143 kips > 140 kips o.k. Manual
Table 4-10

The available strength can be easily determined by using the tables of the Manual. Available
strength values can be verified by hand calculations, as shown below.

Calculation Solution:

Geometric Properties: Manual
Pipe 10 Std. A = 11.1 in. 2 r = 3.68 in. Table 4-10

All Steel Pipes shown in Manual Table 4-10 are compact at 35 ksi, so no local buckling check is
required.

KL ( 30. 0 ft )(12 in./ft ) Section E3 = = 97 .8
r 3.68 in.

<!-- p. 72 -->

E-43

E 29,000 ksi
4.71 = 4.71 = 136 > 97.8
Fy 35 ksi
π 2 E π 2 ( 29, 000 ksi) Eqn. E3-4
Fe = 2 = 2 = 29. 9 ksi
⎛ KL ⎞ ( 97 .8 )
⎜ ⎟
⎝ r ⎠

y 35 ksi ⎛ F ⎞ ⎛ ⎞ Fe 29.9 ksiFcr = ⎜ 0 .658 ⎟ Fy = ⎜ 0. 658 ⎟ ( 35 ksi ) = 21. 4 ksi Eqn. E3-2 ⎜ ⎟ ⎝ ⎠ ⎝ ⎠
Pn = Fcr Ag = ( 21 .4 ksi ) 11. 1 in.2 = 238 kips Eqn. E3-1

LRFD ASD
φc = 0.90 Ωc = 1.67 Section E1
238 kips φ c nP = 0.90 ( 238 kips ) Pn / Ω=c
1.67
\= 215 kips > 210 kips o.k. = 143 kips > 140 kips o.k.

Note that the design procedure would be similar for a round HSS column, except that local
buckling should also be checked.

<!-- p. 73 -->

E-44

Example E.12 Built-up I-Shaped Member with Different Flange Sizes

Given:
Compute the available strength of a built-up compression member with a length of 14 ft. The
ends are pinned. The outside flange is PLw×5, the inside flange is PLw×8, and the web is
PLa×102. Material is ASTM A572 Grade 50.

Material Properties: Manual
ASTM A572 Fy = 50 ksi Fu = 65 ksi Table 2-4

Solution:

User note: There are no tables for special built-up shapes.

Determine if the shape has any slender elements

Check outside flange slenderness

Calculate kc
4 4 Table B4.1
k c = = = 0.756 0.35 ≤ k c ≤ 0.76. o.k. Note [a] h 10.5 in.
t w 0.375 in.

b 2.50 in.
\= = 3.33
t 0.75 in.
k c E 0.756 ( 29,000 ksi )λ r = 0.64 = 0.64 = 13.4
Fy 50 ksi Table B4.1
Case 4
b
≤λ r therefore, the outside flange is not slender.
t

Check inside flange slenderness
b 4.0 in.
\= = 5.33
t 0.750 in. Table B4.1
Case 4b
≤λ r therefore, the inside flange is not slender.
t

<!-- p. 74 -->

E-45

Check web slenderness

h 10.5 in.
\= = 28.0 Table B4.1 t 0.375 in.
Case 14
E 29,000 ksi
λ r = 1.49 = 1.49 = 35.9
Fy 50 ksi
h
\< λ r therefore, the web is not slender.
t

Calculate section properties (ignoring welds)

Ag = b f 1t f 1 + ht w + b f 2 t f 2 = ( 8.00 in. )( 0.750 in. ) + (10.5 in. )( 0.375 in. ) + ( 5.00 in. )( 0.75 in. )
\= 13.7 in. 2

2 2 6.00 in.2 )(11.6 in. ) + ( 3.94 in. )( 6.00 in. ) + ( 3.75 in. )( 0.375 in. ) Σ Ai yi ( y = = = 6.92 in.
2 2 2 Σ Ai ( 6.00 in. ) + ( 3.94 in. ) + ( 3.75 in. )

Note that the neutral axis location is measured from the bottom of the outside flange.

⎡ ( 8.0 in. )( 0.75 in. ) 3 2 ⎤ xI = ⎢ + ( 8.0 in. )( 0.75 in. )( 4.71 in. ) ⎥ +
⎢ 12 ⎥ ⎣ ⎦
⎡ ( 0.375 in. )(10.5 in. ) 3 2 ⎤ ⎢ + ( 0.375 in. )(10.5 in. )( 0.92 in. ) ⎥ +
⎢ 12 ⎥ ⎣ ⎦
⎡ ( 5.0 in. )( 0.750 in. ) 3 2 ⎤ 4 ⎢ + ( 5.0 in. )( 0.750 in. )( 6.55 in. ) ⎥ = 334 in.
⎢ 12 ⎥ ⎣ ⎦

I x 334 in. 4
rx = = 2 = 4.94 in. A 13.7 in.

⎡ ( 0.75 in. )( 8.0 in. ) 3 ⎤ ⎡ (10.5 in. )( 0.375 in. ) 3 ⎤ ⎡ ( 0.750 in. )( 5.0 in. ) 3 ⎤ 4
yI = ⎢ ⎥ + ⎢ ⎥ + ⎢ ⎥ = 39.9 in.
⎢ 12 ⎥ ⎢ 12 ⎥ ⎢ 12 ⎥ ⎣ ⎦ ⎣ ⎦ ⎣ ⎦

I y 39.9 in. 4
ry = = 2 = 1.71 in. A 13.7 in.

Calculate x-x axis flexural elastic critical buckling stress, Fe

K x L 1.0 (14.0 ft )(12 in./ft ) = = 34.0 Section E3
rx 4.94 in.

<!-- p. 75 -->

E-46

π 2 E π 2 (29,000 ksi)
Fe = 2 = 2 = 247 ksi does not control Eqn. E3-4
⎛ KL ⎞ ( 34.0 )
⎜ ⎟
⎝ r ⎠

Calculate the flexural- torsional critical elastic buckling stress

⎛ bt 3 ⎞ ( 8.00 in. )( 0.750 in. ) 3 (10.5 in. )( 0.375 in. ) 3 ( 5.00 in. )( 0.750 in. ) 3 4
J = Σ ⎜ ⎟ = + + = 2.01 in.
⎝ 3 ⎠ 3 3 3

t f t f 0.750 in. 0.750 in.
ho = d − − = 12.0 in. − − = 11.3 in.
2 2 2 2
t f ho 2 ⎛ b13 b2 3 ⎞ ( 0.750 in. )(11.25 in. ) 2 ⎛ ( 8.00in. ) 3 ( 5.00in. ) 3 ⎞ 6C w = ⎜ 3 3 ⎟ = ⎜ 3 3 ⎟ = 795 in.
12 ⎝ b1 + b2 ⎠ 12 ⎜⎝ ( 8.00in. ) + ( 5.00in. ) ⎟⎠

Locate the shear center
Due to symmetry, both the centroid and the shear center lie on the y-axis. Therefore ox = 0

⎛ b13 ⎞ ⎛ (8.00 in.) 3 ⎞e = ho ⎜ 3 3 ⎟ = 11.3in. ⎜ 3 3 ⎟ = 9.04 in.
⎝ b1 + b2 ⎠ ⎝ (8.00 in.) + (5.00 in.) ⎠

Note that this shear center location is taken from the center of the outside flange. Therefore,
add one-half the flange thickness to determine the shear center location measured from the
bottom of the outside flange.
ft 0.75 in.
e + = 9.04 in. + = 9.42 in.
2 2
⎛ t f ⎞
Therefore y o = ⎜ e + ⎟ − y = 9.42 in. − 6.92 in. = 2.50 in.
⎝ 2 ⎠
2 2 2 I x + I y 2 334 in. 4 + 39.9 in. 4 2
r0 = x0 + y 0 + = 0 + (2.50 in.) + 2 = 33.5 in.
Ag 13.7 in. Eqn. E4-7
x02 + y02 0 + (2.50 in.) 2
H = 1 − 2 = 1 − 2 = 0.813 Eqn. E4-8
r0 33.5 in.

Since the ends are pinned, K = 1.0 Commentary
Table
C.C-2.2KL 1.0 (14.0 ft )(12.0 in./ft ) = = 98.2
ry 1.71 in.
π 2 E π 2 ( 29,000 ksi )
Fey = 2 = 2 = 29.7 ksi Eqn. E4-10
⎛ K y L ⎞ ( 98.2 )
⎜ ⎟ ⎜ ⎟ ⎝ ry ⎠

<!-- p. 76 -->

E-47

⎡ ⎤⎛ 1 ⎞ π 2 EC wFez = ⎢ 2 + GJ ⎥ ⎜ 2 ⎟ Eqn. E4-11 ⎟ ⎢ Ag ro ⎠ ⎣ ( K z L ) ⎥⎝⎦ ⎜

6 ⎞ ⎡ π 2 ( 29,000 ksi )( 795 in. ) 4 ⎤⎛ 1 ⎟ = 66.6 ksi = ⎢ 2 + (11,200 ksi )( 2.01 in. ) ⎥⎜ 2 2 ⎟ ⎢ ⎡ (13.7 in. )( 33.5 in. ) ⎠ ⎣ ( ⎣ 1.0 )(14.0 ft )(12 in./ft ) ⎤⎦ ⎥⎦ ⎜⎝

⎡ ⎤
4 Fey Fez H ⎛ Fey + Fez ⎞⎢ ⎥ Eqn. E4-5 1 − 1 −Fe = ⎜ 2 ⎟⎢ ⎝ 2 H ⎠ ⎢⎣ ( Fey + Fez ) ⎥⎥⎦
⎛ 29.7 ksi + 66.6 ksi ⎞ ⎡ 4 ( 29.7 ksi )( 66.6 ksi )( 0.813 ) ⎤ ⎥ ⎢1 − 1 − = ⎜ ⎟ ⎜ ⎟⎢ ⎥ 0.813 ) ( 29.7 ksi + 66.6 ksi ) 2 ⎝ 2 ( ⎠⎣ ⎦
\= 26.4 ksi controls

Torsional and flexural-torsional buckling governs

0.44Fy = 0.44(50 ksi) = 22.0 ksi \< 26.4 ksi therefore Equation E3-2 applies

y ⎡ F ⎤ ⎡ 50 ksi ⎤ Eqn. E3-2 Fe 26.4ksiFcr = ⎢ 0.658 ⎥ Fy = ⎢ 0.658 ⎥ ( 50 ksi ) = 22.6 ksi
⎢ ⎥ ⎣ ⎦ ⎣ ⎦
2 = 310 kips Eqn. E3-1Pn = Fcr Ag = ( 22.6 ksi ) 13.7 in.

LRFD ASD
φc = 0.90 Ωc = 1.67
310 kips Section E1 φ c nP = 0.90 ( 310 kips ) = 279 kips Pn / Ω=c = 186 kips
1.67

<!-- p. 77 -->

F-1

CHAPTER F
DESIGN OF MEMBERS FOR FLEXURE

INTRODUCTION

This Specification chapter contains provisions for calculating the flexural strength of members subject to simple
bending about one principal axis. Included are specific provisions for I-shaped members, channels, HSS, tees,
double angles, single angles, rectangular bars, rounds and unsymmetrical shapes. Also included is a section with
proportioning requirements for beams and girders.

There are selection tables in the Manual for standard beams in the commonly available yield strengths. The
section property tables for most cross sections provide information that can be used to conveniently identify
noncompact and slender sections. LRFD and ASD information is presented side by side.

Most of the formulas from this chapter are illustrated by example below. The design and selection techniques
illustrated in the examples for both LRFD and ASD designs are similar to past practices and will result in similar
designs.

F1. GENERAL PROVISIONS

Selection and evaluation of all members is based on deflection requirements, and strength, which is determined
based on the design flexural strength, φbMn, or the allowable flexural strength, Mn/Ωb, where:

Mn = the lowest nominal flexural strength based on the limit states of yielding, lateral torsional-buckling and
local buckling, where applicable

φb = 0.90 (LRFD) Ωb = 1.67 (ASD).

This design approach is followed in all examples.

The term Lb is used throughout this chapter to describe the length between points which are either braced against
lateral displacement of the compression flange or braced against twist of the cross section. Requirements for
bracing systems and the required strength and stiffness at brace points are given in Specification Appendix 6.

The use of Cb is illustrated in several examples below. Manual Table 3-1 provides tabulated Cb values for many
common situations.

F2. DOUBLY-SYMMETRIC COMPACT I-SHAPED MEMBERS AND CHANNELS BENT ABOUT
THEIR MAJOR AXIS

Section F2 applies to the design of compact beams and channels. As indicated in the User Note in Section F2 of
the Specification, the vast majority of rolled I-shaped beams and channels fall into this category. The curve
presented as a solid line in Figure F-1 below is a generic plot of the moment capacity, Mn, as a function of the
unbraced length, Lb. The horizontal segment of the curve at the far left, between Lb = 0 ft and Lp, is the area where
the strength is limited by flexural yielding. In this region, the nominal strength is taken as the full plastic moment
strength of the section as given by Specification Equation F2-1. In the area of the curve at the far right, starting at
Lr, the strength is limited by elastic buckling. The strength in this region is given by Specification Equation F2-3.
Between these regions, within the linear region of the curve between Mn = Mp at Lp on the left, and Mn = 0.7My =
0.7FySx at Lr on the right, the strength is limited by inelastic buckling. The strength in this region is provided in
Specification Equation F2-2.

The curve plotted as a heavy solid line represents the case where Cb = 1.0, while the heavy dashed line represents
the case where Cb exceeds 1.0. The nominal strengths calculated in both equations F2-2 and F2-3 are linearly
proportional to Cb, but are limited to not more than Mp as shown in the figure.

<!-- p. 78 -->

F-2

Mn = Mp = FyZx Eqn. F2-1

⎡ ⎛ Lb − L p ⎞ ⎤
Mn = Cb ⎢ M p − ( M p − 0.70 Fy S x ) ⎜ ⎟ ⎥ ≤ M p Eqn. F2-2 ⎜ ⎢⎣ ⎝ Lr − L p ⎟⎠ ⎥⎦

Mn = FcrSx ≤ Mp: where Fcr is evaluated as shown below
Eqn. F2-3
Cb π 2 E Jc ⎛ Lb ⎞ 2Fcr = 2 1 + 0.078 ⎜ ⎟
⎛ Lb ⎞ S x ho ⎝ rts ⎠ Eqn. F2-4
⎜ ⎟
⎝ rts ⎠

The provisions of this section are illustrated in Example F.1(W-shape beam) and Example F.2 (channel).

Plastic design provisions are given in Appendix 1. Lpd, the maximum unbraced length for plastic design is less
than Lp.

<!-- p. 79 -->

F-3

F3. DOUBLY-SYMMETRIC I-SHAPED MEMBERS WITH COMPACT WEBS AND
NONCOMPACT OR SLENDER FLANGES, BENT ABOUT THEIR MAJOR AXIS

The strength of shapes designed according to this section is limited by local buckling of the compression flange.
Only a few standard wide flange shapes have noncompact flanges. For these sections, the strength reduction in
with Fy = 50 ksi steel varies. The approximate percentages of Mp about the strong axis that can be developed by
noncompact members when braced such that Lb ≤ Lp are shown below:

W21×48 = 99% W14×99 = 99% W14×90 = 96% W12×65 = 98%
W10×12 = 99% W8×31 = 99% W8×10 = 99% W6×15 = 94%
W6×8.5 = 97% M4×6 = 85%

The strength curve for the flange local buckling limit state, shown in Figure F-2, is similar in nature to that of the
b f
lateral-torsional buckling curve. The horizontal axis parameter is λ= . The flat portion of the curve to the left
2 t f
of λpf is the plastic yielding strength, Mp. The curved portion to the right of λrf is the strength limited by elastic
buckling of the flange. The linear transition between these two regions is the strength limited by inelastic flange
buckling.

Mn = Mp = FyZx Eqn. F2-1

⎡ ⎛ λ −λ pf ⎞ ⎤
Mn = ⎢ M p − ( M p − 0.7 Fy S x ) ⎜ ⎟ ⎥ Eqn. F3-1 ⎜
⎝ ⎢⎣ λ rf −λ pf ⎟⎠ ⎥⎦

0.9 Ek c S x
Mn = 2 Eqn. F3-2 λ

The strength reductions due to local flange buckling of the few standard rolled shapes with noncompact flanges
are incorporated into the design tables in Chapter 3 of the Manual.

There are no standard I-shaped members with slender flanges. The noncompact flange provisions of this section
are illustrated in Example F.3.

<!-- p. 80 -->

F-4

F4. OTHER I-SHAPED MEMBERS WITH COMPACT OR NONCOMPACT WEBS, BENT ABOUT
THEIR MAJOR AXIS

This section of the Specification applies to doubly symmetric I-shaped members with noncompact webs and
singly symmetric I-shaped members (those having different flanges) with compact or noncompact webs.

F5. DOUBLY-SYMMETRIC AND SINGLY-SYMMETRIC I-SHAPED MEMBERS WITH
SLENDER WEBS BENT ABOUT THEIR MAJOR AXIS

This section applies to I-shaped members with slender webs, formerly designated as “plate girders”.

F6. I-SHAPED MEMBERS AND CHANNELS BENT ABOUT THEIR MINOR AXIS

I-shaped members and channels bent about their minor axis are not subject to lateral-torsional buckling. Rolled or
built up shapes with noncompact or slender flanges, as determined by Specification Table B4.1, must be checked
for local flange buckling using Equations F6-2 or F6-3 as applicable.

The vast majority of W-, M-, C-, and MC-shapes have compact flanges, and can therefore develop the full plastic
moment, Mp about the minor axis. The provisions of this section are illustrated in Example F.5.

F7. SQUARE AND RECTANGULAR HSS AND BOX-SHAPED MEMBERS

Square and rectangular HSS need only be checked for the limit states of yielding and local buckling. Although
lateral-torsional buckling is theoretically possible for very long rectangular HSS bent about the strong axis,
deflection will control the design as a practical matter.

The design and section property tables in the Manual were calculated using a design wall thickness of 93% of the
nominal wall thickness. Strength reductions due to local buckling have been accounted for in the Manual design
tables. The selection of rectangular or square HSS with compact flanges is illustrated in Example F.6. The
provisions for rectangular or square HSS with noncompact flanges are illustrated in Example F.7. The
provisions for HSS with slender flanges are illustrated in Example F.8.

F8. ROUND HSS AND PIPES

The definition of HSS encompasses both tube and pipe products. The lateral-torsion buckling limit state does
not apply, but round HSS are subject to strength reductions from local buckling. Available strengths of round
HSS and Pipe are listed in Manual Table 3-14 and 3-15. The tabulated properties and strengths of these shapes in
the Manual are calculated using a design wall thickness of 93% of the nominal wall thickness. The design of a
round HSS is illustrated in Example F.9.

F9. TEES AND DOUBLE ANGLES LOADED IN THE PLANE OF SYMMETRY

The specification provides a check for flange local buckling, which applies only when the flange is in
compression due to flexure. This limit state will seldom govern. No explicit check for local buckling of the web
is provided, but the lateral-torsional limit state equation converges to the local buckling limit state strength as the
length approaches zero. Thus, this limit state must still be checked for members with very short or zero unbraced
length when the tip of the stem is in flexural compression. As noted in the commentary, when the unbraced
EJ
length is zero, the equation converges to M n = 0.424 . When the tip of the tee is in flexural tension and the
d
beam is continuously braced, this limit state need not be checked. Attention should be given to end conditions of
tees to avoid inadvertent fixed end moments which induce compression in the web unless this limit state is
checked. The design of a WT-shape in bending is illustrated in Example F.10.

F10. SINGLE ANGLES

Section F10 permits the flexural design of single angles using either the principal axes or geometric axes (x-x and
y-y axes). When designing single angles without continuous bracing using the geometric axis design provisions,
My must be multiplied by 0.80 for use in Equations F10-1, F10-2 and F10-3. The design of a single angle in
bending is illustrated in Example F.11.

<!-- p. 81 -->

F-5

F11. RECTANGULAR BARS AND ROUNDS

There are no design tables in the Manual for these shapes. The local buckling limit state does not apply to any
bars. With the exception of rectangular bars bent about the strong axis, solid square, rectangular and round bars
are not subject to lateral-torsional buckling and are governed by the yielding limit state only. Rectangular bars
bent about the strong axis are subject to lateral torsional buckling and are checked for this limit state with
Equations F11-2 and F11-3 where applicable.

These provisions can be used to check plates and webs of tees in connections. A design example of a rectangular
bar in bending is illustrated in Example F.12. A design example of a round bar in bending is illustrated in
Example F.13.

F12. UNSYMMETRICAL SHAPES

Due to the wide range of possible unsymmetrical cross sections, specific lateral-torsional and local buckling
provisions are not provided in this Specification section. A general template is provided, but appropriate literature
investigation and engineering judgment are required for the application of this section. A Z-shaped section is
designed in Example F.14.

F13. PROPORTIONS FOR BEAMS AND GIRDERS

This section of the Specification includes a limit state check for tensile rupture due to holes in the tension flange
of beams, proportioning limits for I-shaped members, detail requirements for cover plates and connection
requirements for beams connected side to side.

<!-- p. 82 -->

F-6

Example F.1-1a W-Shape Flexural Member Design in Strong-
Axis Bending, Continuously Braced.

Given:

Select an ASTM A992 W-shape beam with a simple span of 35 feet. Limit the member to a
maximum nominal depth of 18 in. Limit the live load deflection to L/360. The nominal loads
are a uniform dead load of 0.45 kip/ft and a uniform live load of 0.75 kip/ft. Assume the beam
is continuously braced.

Solution:

Material Properties:
ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3
Calculate the required flexural strength
LRFD ASD
wu = 1.2(0.450 kip/ft) +1.6 (0.750 kip/ft) wa = 0.450 kip/ft + 0.750 kip/ft
\= 1.74 kip/ft = 1.20 kip/ft
1.74 kip/ft ( 35.0 ft ) 2 1.20 kip/ft ( 35.0 ft ) 2
Mu = = 266 kip-ft Ma = = 184 kip-ft
8 8

Calculate the required moment of inertia for live-load deflection criterion of L/360

L 35.0ft(12 in./ft)
∆ max = = = 1.17 in.
360 360
Manual
4 4 3 Table 3-23 5 wl 5(0.750 kip/ft)(35.0 ft) (12 in./ft)
Ix(reqd) = = = 748 in.4 Diagram 1
384 E ∆ max 384 (29,000 ksi)(1.17in.)

Select a W18×50 from Table 3-2

Per the User Note in Section F2, the section is compact. Since the beam is continuously
braced and compact, only the yielding limit state applies.

LRFD ASD
M n M px Manual φ b M n = φ b M px = 379kip-ft > 266 kip-ft o.k. = = 252 kip-ft > 184 kip-ft o.k. Table 3-2 Ω b Ω b
Ix = 800 in.4 > 748 in.4 o.k. Manual
Table 3-2

<!-- p. 83 -->

F-7

Example F.1-1b W-Shape Flexural Member Design in Strong-
Axis Bending, Continuously Braced.

Given:

Example F.1-1a can be easily solved by utilizing the tables of the AISC Steel Construction
Manual. Alternatively, this problem can be solved by applying the requirements of the AISC
Specification directly.

Solution:

Material Properties: Manual
ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3

Geometric Properties: Manual
W18×50 Zx = 101 in.3 Table 1-1

Required strength from Example F.1-1a

LRFD ASD
Mu = 266 kip-ft Ma = 184 kip-ft

Calculate the nominal flexural strength, Mn

Per the User Note in Section F2, the section is compact. Since the beam is continuously
braced and compact, only the yielding limit state applies.

Mn = Mp = Fy Zx = 50 ksi(101 in.3) = 5050 kip-in. or 421 kip-ft Eqn. F2-1

Calculate the available flexural strength

LRFD ASD
φb = 0.90 Ωb = 1.67 Section F1
φb Mn = 0.90(421 kip-ft) M n / Ωb = (421 kip-ft) /1.67
\= 379 kip-ft > 266 kip-ft o.k. = 252 kip-ft > 184 kip-ft o.k.

<!-- p. 84 -->

F-8

Example F.1-2a W-Shape Flexural Member Design in Strong-Axis Bending,
Braced at Third Points

Given:
Verify the strength of the W18×50 beam selected in Example F.1-1a if the beam is braced at the ends and third
points rather than continuously braced.

Solution:

Required flexural strength at midspan from Example F.1-1a

LRFD ASD
Mu = 266 kip-ft Ma = 184 kip-ft

35.0ft
bL = = 11.7ft
3

By inspection, the middle segment will govern. For a uniformly loaded beam braced at the
Manual ends and third points, Cb = 1.01 in the middle segment. Conservatively neglect this small
Table 3-1 adjustment in this case.

Obtain the available strength from Table 3-10

Enter Table 3-10 and find the intersection of the curve for the W18×50 with an unbraced
length of 11.7 ft. Obtain the available strength from the appropriate vertical scale to the left.

LRFD ASD
M n Manual
φbMn ≈ 302 kip-ft > 266 kip-ft o.k. ≈ 201kip-ft > 184 kip-ft o.k. Table 3-10 Ω b

<!-- p. 85 -->

F-9

Example F.1-2b W-Shape Flexural Member Design in Strong-
Axis Bending, Braced at Third Points
Given:

Example F.1-2a was solved by utilizing the tables of the AISC Steel Construction Manual.
Alternatively, this problem can be solved by applying the requirements of the AISC
Specification directly.

Solution:

Material Properties: Manual
ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3

Geometric Properties: Manual
W18×50 Sx = 88.9 in.3 Table 1-1

Required strength from Example F.1-2a

LRFD ASD
Mu = 266 kip-ft Ma = 184 kip-ft

Calculate the nominal flexural strength, Mn

Calculate Cb

For the lateral-torsional buckling limit state, the nonuniform moment modification factor can
be calculated using Specification Equation F1.1.

12.5 M max Eqn. F1-1 Cb = Rm ≤ 3.0
2.5 M max + 3 M A + 4 M B + 3 M C

For the center segment of the beam, the required moments for Equation F1-1 can be calculated
as a percentage of the maximum midspan moment as: Mmax = 1.00, MA = 0.972, MB = 1.00, MC
\= 0.972.

Rm = 1.0 for doubly-symmetric members
12.5 (1.00 ) Cb = 1.0 ) = 1.01 2.5 (1.00 ) + 3 ( 0.972 ) + 4 (1.00 ) + 3 ( 0.972 )(

For the end-span beam segments, the required moments for Equation F1-1 can be calculated as
a percentage of the maximum midspan moment as: Mmax = 0.889, MA = 0.306, MB = 0.556, and
MC = 0.750.
12.5 ( 0.889 ) Cb = 1.0 ) = 1.46 2.5 ( 0.889 ) + 3 ( 0.306 ) + 4 ( 0.556 ) + 3 ( 0.750 )(

<!-- p. 86 -->

F-10

Thus, the center span, with the higher required strength and lower Cb, will govern.

Lp = 5.83 ft Manual
Lr = 17.0 ft Table 3-2

Note: The more conservative formula for Lr given in the User Note in Specification Section F2
can yield very conservative results.

For a compact beam with an unbraced length of Lp \< Lb ≤ Lr, the lesser of either the flexural
yielding limit-state or the inelastic lateral-torsional buckling limit-state controls the nominal
strength.

Mp = 5050 kip-in. (from Example F.1-2a)

⎡ ⎛ Lb − L p ⎞ ⎤
Mn = Cb ⎢ M p − ( M p − 0.7 Fy S x ) ⎜ ⎟ ⎥ ≤ M p Eqn. F2-2 ⎜ ⎢⎣ ⎝ Lr − L p ⎟⎠ ⎥⎦

⎡ 3 ⎛ 11.7ft − 5.83ft ⎞ ⎤ Mn = 1.01 ⎢ 5050 kip-in. − ( 5050 kip-in. − 0.7 ( 50 ksi )( 88.9in. ) ) ⎜ ⎟ ⎥ ⎣ ⎝ 17.0ft − 5.83ft ⎠ ⎦

≤ 5050kip-in.
\= 4070 kip-in. or 339 kip-ft

Calculate the available flexural strength

LRFD ASD
φb = 0.90 Ωb = 1.67 Section F1
φb Mn = 0.90(339 kip-ft) M n / Ωb = (339 kip-ft) /1.67
\= 305 kip-ft > 266 kip-ft o.k. = 203 kip-ft > 184 kip-ft o.k.

<!-- p. 87 -->

F-11

Example F.1-3a. W-Shape Flexural Member design in Strong-
Axis Bending, Braced at Midspan

Given:
Verify the strength of the W18×50 beam selected in Example F.1-1a if the beam is braced at
the ends and center point rather than continuously braced.

Solution:

Required flexural strength at midspan from Example F.1-1a

LRFD ASD
Mu = 266 kip-ft Ma = 184 kip-ft

35.0ft
bL = = 17.5ft
2

Manual For a uniformly loaded beam braced at the ends and at the center point, Cb = 1.30. There are
Table 3-1 several ways to make adjustments to Table 3-10 to account for Cb greater than 1.0.

Procedure A.

Available moments from the sloped and curved portions of the plots in from Manual Table 3-
10 may be multiplied by Cb, but may not exceed the value of the horizontal portion (φMn for
LRFD, Mn/Ω for ASD).

Obtain the available strength of a W18×50 with an unbraced length of 17.5 ft from Manual
Table 3-10

Enter Table 3-10 and find the intersection of the curve for the W18×50 with an unbraced
length of 11.7 ft. Obtain the available strength from the appropriate vertical scale to the left.

LRFD ASD
φbMn ≈ 222 kip-ft Mn / Ωb ≈ 147 kip-ft Manual
Table 3-10 φbMp ≈ 379 kip-ft (upper limit on CbMn) Mp / Ωb ≈ 252 kip-ft (upper limit on CbMn)

Adjust for Cb Adjust for Cb

(1.30)(222 kip-ft) = 288 kip-ft (1.30)(147 kip-ft) = 191 kip-ft

<!-- p. 88 -->

F-12

Check Limit Check Limit

288 kip-ft ≤ φbMp = 379 kip-ft o.k. 191 kip-ft ≤ Mp / Ωb = 252 kip-ft o.k.

Check available versus required strength Check available versus required strength

288 kip-ft > 266 kip-ft o.k. 191 kip-ft > 184 kip-ft o.k.

Procedure B.

For preliminary selection, the required strength can be divided by Cb and directly compared to
the strengths in Table 3-10. Members selected in this way must be checked to ensure that the
required strength does not exceed the available plastic moment strength of the section.

Calculate the adjusted required strength

LRFD ASD
Mu’ = 266 kip-ft / 1.3 = 205 kip-ft Ma’ = 184 kip-ft / 1.3 = 142 kip-ft

Obtain the available strength for a W18×50 with an unbraced length of 17.5 ft from Manual
Table 3-10

LRFD ASD Manual
φbMn ≈ 222 kip-ft > 205 kip-ft o.k. Mn / Ωb ≈ 147 kip-ft > 142 kip-ft o.k. Table 3-10

φbMp ≈ 379 kip-ft > 266 kips o.k. Mp / Ωb ≈ 252 kip-ft > 184 kips o.k.

<!-- p. 89 -->

F-13

Example F.1-3b. W-Shape Flexural Member Design in Strong-
Axis Bending, Braced at Midspan
Given:

Example F.1-3a was solved by utilizing the tables of the AISC Steel Construction Manual.
Alternatively, this problem can be solved by applying the requirements of the AISC
Specification directly.

Solution:

Geometric Properties:
W18×50 rts = 1.98 in. Sx = 88.9 in.3 J = 1.24 in.4 ho = 17.4 in.

Required strength from Example F.1-3a

LRFD ASD
Mu = 266 kip-ft Ma = 184 kip-ft

Calculate the nominal flexural strength, Mn

Calculate Cb

12.5 M max Cb = Rm ≤ 3.0
2.5 M max + 3 M A + 4 M B + 3 M C Eqn. F1-1

The required moments for Equation F1-1 can be calculated as a percentage of the maximum
midspan moment as: Mmax= 1.00, MA = 0.438, MB = 0.750, and MC = 0.938.

Rm = 1.0 for doubly-symmetric members
12.5 (1.00 ) Cb = 1.0 ) = 1.30 2.5 (1.00 ) + 3 ( 0.438 ) + 4 ( 0.750 ) + 3 ( 0.938 )(

Lp = 5.83 ft Manual
Lr = 17.0 ft Table 3-6

For a compact beam with an unbraced length Lb > Lr, the limit state of elastic lateral-torsional
buckling applies.

Calculate Fcr with Lb = 17.5 ft

⎞ 2 Jc Cb π 2 E ⎛ Lb where c = 1.0 for doubly symmetric I-shapes Eqn. F2-4Fcr = ⎜ ⎟ 2 1 + 0.078
⎛ Lb ⎞ S x ho ⎝ rts ⎠
⎜ ⎟
⎝ rts ⎠

4 2 1.30 π 2 (29,000 ksi) (1.24in. ) 1.0 ⎛ 17.5ft(12 in./ft) ⎞
Fcr = 2 1 + 0.078 3 ⎜ ⎟ = 43.2 ksi
1.98in. ⎠ ⎛ 17.5ft(12 in./ft) ⎞ ( 88.9in. )(17.4in. ) ⎝
⎜ ⎟
⎝ 1.98 in. ⎠

<!-- p. 90 -->

F-14

Mn = FcrSx ≤ Mp Eqn. F2-3

Mn = 43.2 ksi(88.9 in.3) = 3840 kip-in. \< 5050 kip-in.
Mn = 3840 kip-in or 320 kip-ft

Calculate the available flexural strength

LRFD ASD
φb = 0.90 Ωb = 1.67 Section F1
M n 320 kip-ft
φb Mn = 0.90(320 kip-ft) = 288 kip-ft Ω=b 1.67 = 192 kip-ft
288 kip-ft > 266 kip-ft o.k. 192 kip-ft > 184 kip-ft o.k.

<!-- p. 91 -->

F-15

Example F.2-1a Compact Channel Flexural Member,
Continuously Braced

Given:

Select an ASTM A36 channel to serve as a roof edge beam with a simple span of 25 ft. Limit
the live load deflection to L/360. The nominal loads are a uniform dead load of 0.23 kip/ft and
a uniform live load of 0.69 kip/ft. The beam is continuously braced.

Solution:

Material Properties:
Manual ASTM A36 Fy = 36 ksi Fu = 58 ksi
Table 2-3
Calculate the required flexural strength

LRFD ASD
wu = 1.2(0.230 kip/ft) + 1.6(0.690 kip/ft) wa = 0.230 kip/ft + 0.690 kip/ft
\= 1.38 kip/ft = 0.920 kip/ft

1.38 kip/ft ( 25.0 ft ) 2 0.920 kip/ft ( 25.0 ft ) 2
Mu = = 108 kip-ft Ma = = 71.9 kip-ft
8 8

Select a trial section

Per the User Note in Section F2, all ASTM A36 channels are compact. Because the beam is
compact and continuously braced, the yielding limit state governs. Select C15×33.9 from
Manual Table 3-8.

LRFD ASD
φbMn = φbMp = 137 kip-ft > 108 kip-ft o.k. Mn/Ωb = Mp/Ωb = 91.2 kip-ft > 71.9 kip-ft o.k.

Check live load deflection
L 25.0 ft (12 in./ft )
∆ max = = = 0.833 in.
360 360 Manual
For C15×33.9, Ix = 315 in.4 Table 1-5

5 wl 4 5 ( 0.690 kip/ft )( 25.0 ft ) 4 (12 in./ft ) 3 Manual
∆max = = 4 = 0.664 in. \< 0.833 in. o.k. Table 3-23 384 EI 384 ( 29,000 ksi )( 315 in. )

<!-- p. 92 -->

F-16

Diagram 1

Example F.2-1b Compact Channel Flexural Member,
Continuously Braced
Given:

Example F.2-1a can be easily solved by utilizing the tables of the AISC Steel Construction
Manual. Alternatively, this problem can be solved by applying the requirements of the AISC
Specification directly.

Solution:

Material Properties: Manual
ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-3

Geometric Properties: Manual
C15×33.9 Zx = 50.8 in.3 Table 1-5

Required strength from Example F.2-1a

LRFD ASD
Ma = 71.9 kip-ft Mu = 108 kip-ft

Calculate the nominal flexural strength, Mn

Per the User Note in Section F2, all ASTM A36 C- and MC-shapes are compact.

A channel that is continuously braced and compact is governed by the yielding limit state.

Mn= Mp = FyZx = 36 ksi(50.8 in.3) = 1830 kip-in. or 152 kip-ft Eqn. F2-1

LRFD ASD
φb = 0.90 Ωb = 1.67 Section F1
φb Mn = 0.90(152 kip-ft) Mn/Ωb = 152 kip-ft / 1.67
\= 137 kip-ft > 108 kip-ft o.k. = 91.3 kip-ft > 71.9 kip-ft o.k.

<!-- p. 93 -->

F-17

Example F.2-2a Compact Channel Flexural Member
with Bracing at Ends and Fifth Points

Given:
Check the C15×33.9 beam selected in Example F.2-1a, assuming it is braced at the ends and
the fifth points rather than continuously braced.

Solution:

Material Properties:
ASTM A36 Fy = 36 ksi Fu = 58 ksi

The center segment will govern by inspection.

Required strength at midspan from Example F.2-1a

LRFD ASD
Mu = 108 kip-ft Ma = 71.9 kip-ft

With an almost uniform moment across the center segment, Cb = 1.0, so no adjustment is Manual
required. Table 3-1

25.0ft
bL = = 5.00ft
5

Obtain the strength of the C15×33.9 with an unbraced length of 5.00 ft from Manual Table 311

Enter Table 3-11 and find the intersection of the curve for the C15×33.9 with an unbraced
length of 5.00 ft. Obtain the available strength from the appropriate vertical scale to the left.

LRFD ASD Manual
φbMn ≈ 130 kip-ft > 108 kip-ft o.k. Mn/Ωb ≈ 87.0 kip-ft > 71.9 kip-ft o.k. Table 3-11

<!-- p. 94 -->

F-18

Example F.2-2b Compact Channel Flexural Member with
Bracing at End and Fifth Points

Given:

Verify the results from Example F.2-2a by calculation using the provisions of the
Specification.

Solution:

Material Properties: Manual
ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-3

Geometric Properties: Manual
C15×33.9 Sx = 42.0 in.3 Table 3-8

Required strength from Example F.2-2a

LRFD ASD
Mu = 108 kip-ft Ma = 71.9 kip-ft

Calculate the nominal flexural strength, Mn

Per the User Note in Section F2, all ASTM A36 C- and MC-shapes are compact.

For the center segment of a uniformly loaded beam braced at the ends and the fifth points, Manual Table
Cb = 1.0 3-1

Lp = 3.75 ft Manual
Lr = 14.5 ft Table 3-8

For a compact channel with Lp \< Lb ≤ Lr, the lesser of the flexural yielding limit state or the
inelastic lateral-torsional buckling limit-state controls the available flexural strength.

Lateral-torsional buckling limit state

From Example F.2-2a, Mp = 1830 kip-in.

⎡ ⎛ Lb − L p ⎞ ⎤
Mn = Cb ⎢ M p − ( M p − 0.7 Fy S x ) ⎜ ⎟ ⎥ ≤ M p Eqn. F2-2
⎢⎣ ⎝ ⎜ Lr − L p ⎟⎠ ⎥⎦
⎡ 3 ⎛ 5.00ft − 3.75ft ⎞ ⎤ ≤ 1830 kip-in.Mn = 1.0 ⎢1830 kip-in. − ( 1830 kip-in. − 0.7 ( 36 ksi )( 42.0in. ) ) ⎜ ⎟ ⎥ ⎣ ⎝ 14.5ft − 3.75ft ⎠ ⎦

\= 1740 kip-in. \< 1830 kip-in. o.k.

Mn = 1740 kip-in. or 145 kip-ft

<!-- p. 95 -->

F-19

Calculate the available flexural strength

LRFD ASD
φb = 0.90 Ωb = 1.67
M n 145 kip-ft
φb Mn = 0.90(145 kip-ft) = 131 kip-ft Ω=b 1.67 = 86.8 kip-ft
131 kip-ft > 108 kip-ft o.k. 86.8 kip-ft > 71.9 kip-ft o.k.

<!-- p. 96 -->

F-20

Example F.3a W-Shape Flexural Member with Noncompact
Flanges in Strong-Axis Bending

Given:

Select an ASTM A992 W-shape beam with a simple span of 40 feet. The nominal loads are a
uniform dead load of 0.05 kip/ft and two equal 18 kip concentrated live loads acting at the
third points of the beam. The beam is continuously braced. Also calculate the deflection.

Note: A beam with noncompact flanges will be selected to demonstrate that the tabulated
values of the Steel Construction Manual account for flange compactness.

Solution:

Material Properties:

ASTM A992 Fy = 50 ksi Fu = 65 ksi

Calculate the required flexural strength at midspan

LRFD ASD
wu = 1.2(0.0500 kip/ft) = 0.0600 kip/ft wa = 0.0500 kip/ft
Pu = 1.6(18.0 kips) = 28.8 kips Pa = 18.0 kips
( 0.0600 kip/ft )( 40.0 ft ) 2 ( 0.0500 kip/ft )( 40.0 ft ) 2
Mu = Ma =
8 8
40.0 ft 40.0 ft + ( 28.8kips ) +(18.0 kips )
3 3
\= 396 kip-ft = 250 kip-ft

Select the lightest section with the required strength from the bold entries in Manual Table 3-2
Manual
Select W21×48. Table 3-2

ManualThis beam has a noncompact compression flange at Fy = 50 ksi as indicated by footnote “f” in
Table 1-1Manual Table 3-2. This is also footnoted in Manual Table 1-1.

<!-- p. 97 -->

F-21

Check the available strength

LRFD ASD
M n M px Manual
φbMn = φbMpx = 398 kip-ft > 396 kip-ft o.k. = = 265 kip-ft > 250 kip-ft o.k. Table 3-2 Ω b Ω b
Note: the value Mpx in Table 3-2 include strength reductions due the noncompact nature of the
shape

Calculate deflection
Manual
Ix = 959 in.4 Table 1-1

5 wl 4 Pl 3 Manual
∆max = + Table 3-23 384 EI 28 EI
4 3 3 3 Diagrams 1
5 ( 0.0500 kip/ft )( 40.0 ft ) (12 in./ft ) 18.0 kips ( 40.0 ft ) (12 in./ft ) and 9 = +
4 4 ) 384 ( 29,000 ksi )( 959 in. ) 28 ( 29,000 ksi )( 959in
\= 2.66 in.

This deflection can be compared with the appropriate deflection limit for the application.
Deflection will often be more critical than strength in beam design.

<!-- p. 98 -->

F-22

Example F.3b W-Shape Flexural Member with Noncompact
Flanges in Strong-Axis Bending
Given:

Verify the results from Example F.3a by calculation using the provisions of the Specification.

Solution:

Material Properties:
ASTM A992 Fy = 50 ksi Fu = 65 ksi

Geometric Properties: Manual
W21×48 Sx = 93.0 in.3 Zx = 107 in.3 Table 2-3

Check flange slenderness
b f Manual λ = = 9.47
2 t f Table 1-1
The limiting width-thickness ratios for the compression flange are:
29,000 ksi E = 9.15 Manual λpf = 0.38 = 0.38
Fy 50 ksi Table 1-1

E 29,000 ksi λrf = 1.0 = 1.0 = 24.1 Table B4.1
Fy 50 ksi Case 1

λrf > λ > λpf; therefore, the compression flange is noncompact. This could also be determined
from the footnote “f” in Manual Table 1-1.

Calculate the nominal flexural strength, Mn

Since the beam is continuously braced, and therefore not subject to lateral-torsional buckling,
the available strength is governed by Section F3

Mp = FyZx = 50 ksi(107 in.3) = 5350 kip-in. or 446 kip-ft.

⎡ ⎛ λ −λ pf ⎞ ⎤
⎥ ⎟Mn = Eqn. F3-1 ⎢ M p − ( M p − 0.7 Fy S x ) ⎜⎜ ⎟ λ rf −λ pf ⎝ ⎠ ⎢⎣ ⎥⎦

⎡ 3 ⎛ 9.47 − 9.15 ⎞ ⎤Mn = ⎢ 5350 kip-in. − ( 5350 kip-in − 0.7 ( 50 ksi )( 93.0in. ) ) ⎜ ⎟ ⎥ ⎣ ⎝ 24.1 − 9.15 ⎠ ⎦
\= 5310 kip-in. or 442 kip-ft.

Calculate the available flexural strength

LRFD ASD
φb = 0.90 Ωb = 1.67 Section F1
φbMn = 0.90(442 kip-ft) Mn/Ωb = 442 kip-ft / 1.67
\= 398 kip-ft > 396 kip-ft o.k. = 265 kip-ft > 250 kip-ft o.k.
Note that these available strength values are identical to the tabulated values in Manual Table
3-2, which account for the non-compact flange.

<!-- p. 99 -->

F-23

Example F.4 W-shape Flexural Member, Selection by
Moment of Inertia for Strong-Axis Bending

Given:

Select an ASTM A992 W-shape flexural member by the moment of inertia, to limit the live
load deflection to 1 in. The span length is 30 ft. The nominal loads are a uniform dead load of
0.80 kip/ft and a uniform live load of 2 kip/ft. Assume the beam is continuously braced.

Solution:

Material Properties:
ASTM A992 Fy = 50 ksi Fu = 65 ksi

Calculate the required flexural strength

LRFD ASD
wu = 1.2(0.800 kip/ft) + 1.6(2.00 kip/ft) wa = 0.800 kip/ft + 2.00 kip/ft
\= 4.16 kip/ft = 2.80 kip/ft
4.16 kip/ft ( 30.0 ft ) 2 2.80 kip/ft ( 30.0 ft ) 2
Mu = = 468 kip-ft Ma = = 315 kip-ft
8 8

Calculate the minimum required moment of inertia

The maximum deflection, ∆max, occurs at mid-span and is calculated as
4 Manual 5 wl
∆max = Table 3-23
384 EI
Diagram 1
Rearranging and substituting ∆max = 1.00 in.

5 ( 2.00 kips/ft )( 30.0 ft ) 4 (12in./ft ) 3
Imin = = 1,260 in.4
384 ( 29,000 ksi )(1.00 in. )

Select the lightest section with the required moment of inertia from the bold entries in Manual
Table 3-3

Select a W24×55
Manual
Ix = 1,350 in.4 > 1,260. in.4 o.k. Table 1-1

Because the W24×55 is continuously braced and compact, its strength is governed by the
yielding limit state and Section F2.1

<!-- p. 100 -->

F-24

Obtain the available strength from Manual Table 3-2

LRFD ASD
φbMn = φbMpx = 503 kip-ft Mn/Ωb = Mpx/Ωb = 334 kip-ft Manual
Table 3-2
503 kip-ft > 468 kip-ft o.k. 334 kip-ft > 315 kip-ft o.k.

<!-- p. 101 -->

F-25

Example F.5 I-shaped Flexural Member in Minor-Axis
Bending

Given:

Select an ASTM A992 W-shape beam loaded in its minor axis with a simple span of 15 ft.
The nominal loads are a total uniform dead load of 0.667 kip/ft and a uniform live load of 2
kip/ft. Limit the live load deflection to L/240. Assume the beam is braced at the ends only.

Note: Although not a common design case, this example is being used to illustrate
Specification Section F6 (I-shaped members and channels bent about their minor axis).

Solution:

Material Properties:
Manual ASTM A992 Fy = 50 ksi Fu = 65 ksi
Table 2-3
Calculate the required flexural strength

LRFD ASD
wu = 1.2(0.667 kip/ft) + 1.6(2.00 kip/ft) wa = 0.667 kip/ft + 2.00 kip/ft
\= 4.00 kip/ft = 2.67 kip/ft
4.00kip/ft(15.0 ft) 2 2.67kip/ft(15.0 ft) 2
Mu = = 113 kip-ft Ma = = 75.0 kip-ft
8 8

Calculate the minimum required moment of inertia

L 15.0 ft(12 in./ft)
∆max = = = 0.750 in.
240 240

Manual
4 4 3 5 wl 5 ( 2.00 kip/ft )(15.0 ft ) (12 in./ft ) Table 3-23 Ιreq = = = 105 in.4
384 E ∆ max 384 ( 29,000 ksi )( 0.750 in. ) Diagram 1

Select the lightest section from the bold entries in Manual Table 3-3, due to the likelihood that
deflection will govern this design.

<!-- p. 102 -->

F-26

Try a W12×58

Geometric Properties:
W12×58 Sy = 21.4 in.3 Zy = 32.5 in.3 Iy = 107 in.4 Manual
Table 3-3
Manual Iy = 107 in.4 > 105 in.4 o.k.
Table 1-1
Specification Section F6 applies. Since the W12×58 has compact flanges per the User Note in
this Section, the yielding limit state governs the design.

Mn = Mp = FyZy ≤ 1.6FySy Eqn. F6-1

\= 50 ksi(32.5 in3) ≤ 1.6(50 ksi)(21.4 in3)

\= 1630 kip-in. ≤ 1710 kip-in. o.k.

\= 1630 kip-in. or 135 kip-ft

Calculate the available flexural strength

LRFD ASD
φb = 0.90 Ωb = 1.67 Section F1
135kip-ft
φbMn = 0.90(135 kip-ft) = 122 kip-ft Mn/Ωb = = 81.1 kip-ft
1.67
122 kip-ft > 113 kip-ft o.k. 81.1 kip-ft > 75.0 kip-ft o.k.

<!-- p. 103 -->

F-27

Example F.6 HSS Flexural Member with Compact Flange

Given:

Select a square ASTM A500 Gr. B HSS beam to span 7.5 feet. The nominal loads are a
uniform dead load of 0.145 kip/ft and a uniform live load of 0.435 kip/ft. Limit the live load
deflection to L 240 . Assume the beam is continuously braced.

Solution:

Material Properties:
ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi

Calculate the required strength

LRFD ASD
wu = 1.2(0.145 kip/ft) + 1.6(0.435 kip/ft) wa = 0.145 kip/ft + 0.435 kip/ft
\= 0.870 kip/ft = 0.580 kip/ft
( 0.870 kip/ft )( 7.50 ft ) 2 ( 0.580 kip/ft )( 7.50 ft ) 2
Mu = = 6.12 kip-ft Ma = = 4.08 kip-ft
8 8

Calculate the minimum required moment of inertia

L 7.50 ft(12 in./ft)
∆max = = = 0.375 in.
240 240
4 Manual 5 wl
Ιreq = Table 3-23
384 E ∆ max Diagram 1
5 ( 0.435 kip/ft )( 7.50 ft ) 4 (12 in./ft ) 3 = = 2.85 in.4
384 ( 29,000 ksi )( 0.375 in. )

Select an HSS with a minimum Ix of 2.85 in.4, using Manual Table 1-12, having adequate
available strength, using Manual Table 3-13.

Select HSS3×3×4

Manual Ix = 3.02 in.4 > 2.85 in.4 o.k. Table 1-12

Obtain the required strength from Table 3-13
LRFD ASD Manual
φ b M n = 8.55 kip-ft > 6.12 kip-ft o.k. M n / Ω=b 5.69 kip-ft > 4.08 kip-ft o.k. Table 3-13

<!-- p. 104 -->

F-28

Example F.7a HSS Flexural Member with Noncompact Flange

Given:

Select a rectangular ASTM A500 Gr. B HSS beam with a span of 21 ft. The nominal loads
include a uniform dead load of 0.15 kip/ft and a uniform live load of 0.40 kip/ft. Limit the live
load deflection to L/240. Assume the beam is braced at the end points only. A noncompact
member was selected here to illustrate the relative ease of selecting noncompact shapes from
the Manual, as compared to designing a similar shape by applying the Specification
requirements directly, as shown in Example F.7b.

Solution:

Material Properties:
ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi

Calculate the required strength
LRFD ASD
wu = 1.2(0.150 kip/ft) + 1.6(0.400 kip/ft) wa = 0.150 kip/ft + 0.400 kip/ft
\= 0.820 kip/ft = 0.550 kip/ft
0.820 kip/ft ( 21.0 ft ) 2 0.550 kip/ft ( 21.0 ft ) 2
Mu = = 45.2 kip-ft Ma = = 30.3 kip-ft
8 8

Calculate the minimum moment of inertia
L 21.0 ft (12 in./ft )
∆max = = = 1.05 in.
240 240
5 wl 4 Manual ∆max =
384 EI Table 3-18
Diagram 1
Rearranging and substituting ∆max = 1.05 in.

5 ( 0.400 kip/ft )( 21.0 ft ) 4 (12 in./ft ) 3 4Imin = = 57.5 in.
384 ( 29,000 ksi )(1.05 in. )

Select a HSS with a minimum Ix of 57.5 in.4, using Manual Table 1-11, having adequate
available strength, using Manual Table 3-12.

Select a HSS10×6×x oriented in the strong direction. This rectangular HSS section was
purposely selected for illustration purposes because it has a noncompact flange as noted by
footnote “f” in Manual Table 3-12.

Ix = 74.6 in.4 > 57.5 in.4 o.k. Manual

<!-- p. 105 -->

F-29

Obtain the required strength from Table 3-12 Table 1-11

LRFD ASD Manual
φ b M n = 57.0 kip-ft > 45.2 kip-ft o.k. M n / Ω=b 37.9 kip-ft > 30.3 kip-ft o.k. Table 3-12

<!-- p. 106 -->

F-30

Example F.7b HSS Flexural Member with Noncompact
Flanges

Given:

Notice that in Example F.8b the required information was easily determined by consulting the
tables of the Steel Construction Manual. The purpose of the following calculation is to
demonstrate the use of the Specification equations to calculate the flexural strength of a HSS
member with a noncompact compression flange.

Solution:

Material Properties:
ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Manual
Table 2-3
Geometric Properties:
HSS10×6×x Zx = 18.0 in.3 Sx = 14.9 in.3 Manual
Table 1-11
Check for flange compactness

b Manual
λ = = 31.5
t Table 1-11

The limiting ratio for a compact HSS flange in flexure is

E 29,000 ksi
λp = 1.12 = 1.12 = 28.1 Table B4.1,
Fy 46 ksi Case 12

Check flange slenderness

The limiting ratio for a slender HSS flange in flexure is

E 29,000 ksi Table B4.1,λr = 1.40 = 1.40 = 35.2
Fy 46 ksi Case 12

λp \< λ \< λr therefore the flange is noncompact. For this situation, Specification Eqn. F7-2
Section F7applies

Check web slenderness

h
λ = = 54.5 Manual
t
Table 1-11
The limiting ratio for a compact HSS web in bending is

E 29,000 ksi
λp = 2.42 = 2.42 = 60.8 > 54.5, therefore the web is compact. Table B4.1
Fy 46 ksi Case 13

For HSS with non-compact flanges and compact webs, Specification Section F7.2(b) applies.

<!-- p. 107 -->

F-31

⎛ b Fy ⎞Mn = M p − ( M p − Fy S ) ⎜ 3.57 − 4.0 ⎟ ≤ M p ⎜ t E ⎟ ⎝ ⎠
Eqn. F7-2
Mp = FyZ = 46 ksi(18.0 in.3) = 828 kip-in.

3 ⎛ 46 ksi ⎞ ⎤ − 4.0 ⎟Mn = ( 828 kip-in. ) − ⎡ ⎜ 3.57 ( 31.5 ) ( 828 kip-in. ) − ( 46 ksi )(14.9 in. ) ⎣ ⎦⎜ ⎟ 29,000 ksi ⎝ ⎠

\= 760 kip-in. or 63.3 kip-ft

Calculate the available flexural strength

LRFD ASD
φb = 0.90 Ωb = 1.67 Section F1
63.3 kip-ft φ b M n = 0.90 ( 63.3 kip-ft ) = 57.0 kip-ft M n / Ω=b = 37.9 kip-ft
1.67

<!-- p. 108 -->

F-32

Example F.8a HSS Flexural Member with Slender Flanges

Given:
Verify the strength of an ASTM A500 Gr. B HSS8×8×x with a span of 21 ft. The nominal
loads are a dead load of 0.125 kip/ft and a live load of 0.375 kip/ft. Limit the live load
deflection to L 240 .

Solution:

Material Properties:

ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi

Calculate the required flexural strength

LRFD ASD
wu = 1.2(0.125 kip/ft) + 1.6(0.375 kip/ft) wa = 0.125 kip/ft + 0.375 kip/ft
\= 0.750 kip/ft = 0.500 kip/ft
( 0.750 kip / ft )( 21.0 ft ) 2 ( 0.500 kip / ft )( 21.0 ft ) 2
Mu = = 41.3 kip-ft Ma = = 27.6 kip-ft
8 8

Obtain the flexural strength of the HSS8×8×x from Manual Table 3-13

LRFD ASD
Manual φ b M n = 45.3 kip-ft > 41.3 kip-ft o.k. M n / Ω=b 30.1 kip-ft > 27.6 kip-ft o.k. Table 3-12

Check deflection

l ( 21.0 ft )(12 in./ft )
∆ max = = = 1.05 in.
240 240

Manual
Ix = 54.4 in.4 Table 1-12
5 wl 4 5 ( 0.375 kip/ft ) 3 ( 21.0ft ) 4 (12in./ft ) 3 Manual = = 1.04 in. \< 1.05 in. o.k.∆ max = 4 Table 3-23 384 EI 384 ( 29,000 ksi )( 54.4 in. ) Case 1

<!-- p. 109 -->

F-33

Example F.8b HSS Flexural Member with Slender Flanges

Given:

In Example F.8a the available strengths were easily determined from the tables of the Steel
Construction Manual. The purpose of the following calculation is to demonstrate the use of
the Specification equations to calculate the flexural strength of a HSS member with slender
flanges.

Solution:

Material Properties: Manual
Table 2-3
ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi

Geometric Properties: Manual
Table 1-12
HSS8×8×x Ix = 54.4 in.4 Zx = 15.7 in.3 Sx = 13.6 in.3
bf = 8.0 in. tf = 0.174 in. b/t = 43.0 h/t = 43.0

Check flange slenderness

The assumed outside radius of the corners of HSS shapes is 1.5t. The design thickness is used
to check compactness. The limiting ratio for HSS flanges in bending is as follows:

The limiting ratio for a slender HSS flange in bending is:

E 29,000 ksi
λ r = 1.40 = 1.40 = 35.2 Table B4.1
Fy 46 ksi Case 12

b
λ = = 43.0 > λr, therefore flange is slender.
t

Check for web compactness

The limiting ratio for a compact web in bending is:

E 29,000 ksi
λ p = 2.42 = 2.42 = 60.8 Table B4.1
Fy 46 ksi Case 13

h
λ = = 43.0 > λp, therefore the web is compact.
t

For HSS sections with slender flanges and compact webs, Specification F7-2(c) applies.

Mn = FySeff Eqn. F7-3

Where Seff is the effective section modulus determined with the effective width of the
compression flange taken as:

<!-- p. 110 -->

F-34

E ⎡ 0.38 E ⎤
be = 1.92 t ⎢1 − ⎥ ≤ b
Fy ⎢⎣ b / t Fy ⎥⎦ Eqn. F7-4
b = 8.00 in. − 3 ( 0.174 in. ) = 7.48 in.

29,000 ksi ⎡ 0.38 29,000 ksi ⎤be = 1.92 ( 0.174 in. ) ⎢1 − ⎥ = 6.53 in.
46 ksi ⎢⎣ 43.0 46 ksi ⎥⎦

The ineffective width of the compression flange is:

7.48 in. – 6.53 in. = 0.950 in.

An exact calculation of the effective moment of inertia and section modulus could be
performed taking into account the ineffective width of the compression flange and the resulting
neutral axis shift. Alternatively, a simpler but slightly conservative calculation can be
performed by removing the ineffective width symmetrically from both the top and bottom
flanges.

3 ⎤ 4 ⎡ 2 ( 0.950 in. ) (0.174 in.)Ieff ≈ 54.4 in. − 2 ⎢ ( 0.950 in. )( 0.174 in. )( 3.91) + ⎥ = 49.3 in.4
⎢⎣ 12 ⎥⎦

The effective section modulus can now be calculated as follows:

I eff 49.3 in. 4 3
S eff = = = 12.3 in. d / 2 ( 8.00 in. ) / 2

Calculate the nominal flexural strength, Mn

Mn = Fy Seff = 46 ksi(12.3 in.3) = 567 kip-in. or 47.3 kip-ft
Eqn. F7-3

Calculate the available flexural strength

LRFD ASD
φ b = 0.90 Ω=b 1.67 Section F1
47.3 kip-ft φ b M n = 0.90 ( 47.3 kip-ft ) M n / Ω=b
1.67
\= 42.5 kip-ft > 41.3 kip-ft o.k. = 28.3 kip-ft > 27.6 kip-ft o.k.

Note that the calculated available strengths are somewhat lower than those in Manual Table 313 due to the use of the conservative calculation of the approximate effective section modulus
above.

<!-- p. 111 -->

F-35

Example F.9a Pipe Flexural Member

Given:

Select an ASTM A53 grade B Pipe shape with a simple span of 16 ft. The nominal loads are a
total uniform dead load of 0.32 kip/ft and a uniform live load of 0.96 kip/ft. Assume there is
no deflection limit for this beam. The beam is braced only at the ends.

Solution:

Material Properties:

ASTM A500 Gr. B Fy = 35 ksi Fu = 60 ksi

Calculate the required flexural strength

LRFD ASD
wu = 1.2(0.320 kip/ft) + 1.6(0.960 kip/ft) wa = 0.320 kip/ft + 0.960 kip/ft
\= 1.92 kip/ft = 1.28 kip/ft
1.92 kip/ft (16.0 ft ) 2 1.28 kip/ft (16.0 ft ) 2
Mu = = 61.4 kip-ft Ma = = 41.0 kip-ft
8 8

Select a member from Manual Table 3-15 having the required strength

Select Pipe 8 X-Strong.

LRFD ASD
φ b M n = 81.4 kip-ft > 61.4 kip-ft o.k. M n / Ω=b 54.1 kip-ft > 41.0 kip-ft o.k. Manual
Table 3-15

<!-- p. 112 -->

F-36

Example F.9b Pipe Flexural Member

Given:

The available strength in Example F.9a was easily determined using Manual Table 3-15. The
following calculation demonstrates the calculation of the available strength by directly
applying the requirements of the Specification.

Solution:

Material Properties:

ASTM A53 Gr. B Fy = 35 ksi Fu = 60 ksi Manual
Table 2-3
Geometric Properties:
Manual
Pipe 8 X-Strong Z = 31.0 in.3 D = 8.63 in. t = 0.465 in. D/t = 18.5 Table 1-14

Required flexural strength from Example F.9a

LRFD ASD
Mu = 61.4 kip-ft Ma = 41.0 kip-ft

Check compactness

For circular HSS in flexure, the limiting diameter to thickness ratio for a compact section is:

0.07 E 0.07 ( 29,000 ksi ) Table B4.1
λ p = = = 58.0 Case 15
Fy 35 ksi

D
λ = = 18.5 \< λ p , therefore the section is compact and the limit state of flange local
t
buckling does not apply.

D 0.45 E
By inspection, \< , therefore Specification Section F8 applies. Section F8
t Fy
Calculate the nominal flexural strength based on the flexural yielding limit state

3M n = M p = Fy Z = ( 35 ksi )( 31.0 in. ) = 1080 kip-in. or 90.4 kip-ft
Eqn. F8-1

Calculate the available flexural strength

LRFD ASD
φ b = 0.90 Ω=b 1.67 Section F1
90.4 kip-ft φ b M n = 0.90 ( 90.4 kip-ft ) M n / Ω=b
1.67
\= 81.4 kip-ft > 61.4 kip-ft o.k. = 54.1 kip-ft > 41.0 kip-ft o.k.

<!-- p. 113 -->

F-37

Example F.10 WT Shape Flexural Member

Given:

Select an ASTM A992 WT beam with a simple span of 6 ft. The toe of the stem of the WT is
in tension. The nominal loads are a uniform dead load of 0.08 kip/ft and a uniform live load of
0.24 kip/ft. There is no deflection limit for this member. Assume full lateral support.

Solution:

Material properties:
Manual
ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3

Calculate the required flexural strength

LRFD ASD
wu = 1.2(0.0800 kip/ft) + 1.6(0.240 kip/ft) wa = 0.0800 kip/ft + 0.240 kip/ft
\= 0.480 kip/ft = 0.320 kip/ft
0.480 kip/ft ( 6.00 ft ) 2 0.320 kip/ft ( 6.00 ft ) 2
Mu = = 2.16 kip-ft Ma = = 1.44 kip-ft
8 8

Try WT 5×6

Geometric Properties:

WT 5×6 Ix = 4.35 in.4 Zx = 2.20 in.3 Sx = 1.22 in.3 bf = 3.96 in. Manual
4 Table 1-8 I x 4.35 in. 3 tf = 0.210 in. y = 1.36 in. S xc = = = 3.20 in.
yc 1.36 in.

Calculate the nominal flexural strength, Mn

Flexural yielding limit state

M p = Fy Z x ≤ 1.6 M y for stems in tension Eqn. F9-2

31.6 M y = 1.6 Fy S x = 1.6 ( 50 ksi )(1.22 in. ) = 97.6 kip-in.

<!-- p. 114 -->

F-38

3M p = Fy Z x = ( 50 ksi )( 2.20 in. ) = 110 kip-in. > 97.6 kip-in. , therefore use

Mp = 97.6 kip-in. or 8.13 kip-ft

M n = M p = 8.13 kip-ft controls Eqn. F9-1

Lateral-torsional buckling limit state Section F9.2

Because the WT is fully braced and the stem is in tension, no check of the lateral-torsional
buckling limit state is required. Note that if the stem is in compression, Equation F9-4 must be
checked even for fully braced members, since the equation converges to the web local
buckling limit state check at an unbraced length of zero. See Commentary Section F9.

Flange local buckling limit state

Check flange compactness

fb 3.96 in.λ = = = 9.43
2 t 2(0.210 in.)

E 29,000 ksi Table B4.1,
λp = 0.38 = 0.38 = 9.15 \< 9.43; therefore the flange is not compact.
Fy 50 ksi Case 7
Check flange slenderness

E 29,000 ksi Table B4.1,λr = 1.0 = 1.0 = 24.1 > 9.43, therefore the flange in not slender.
Fy 50 ksi Case 7
Calculate critical flange local buckling stress

For a Tee with a noncompact flange, the critical stress is:

⎛ ⎛ b f ⎞ Fy ⎞ ⎛ 50 ksi ⎞Fcr = Fy ⎜ 1.19-0.50 ⎜ ⎟ ⎟ = ( 50 ksi ) ⎜ 1.19-0.50 ( 9.43 ) ⎟ = 49.7 ksi Eqn. F9-7 ⎜ ⎟ ⎜ 29,000 ksi ⎟ ⎠ ⎝ 2t f ⎝ ⎠ E ⎟⎠ ⎜⎝

Calculate the nominal flexural strength

Eqn. F9-6Mn = FcrSxc = 49.7 ksi(3.20 in.3) = 159 kip-in. or 13.3 kip-ft does not control

Calculate the available flexural strength

LRFD ASD
φ b = 0.90 Ω=b 1.67 Section F1
8.13 kip-ft φ b M n = 0.90 ( 8.13 kip-ft ) M n / Ω=b
1.67
\= 7.32 kip-ft > 2.16 kip-ft o.k. = 4.87 kip-ft > 1.44 kip-ft o.k.

<!-- p. 115 -->

F-39

Example F.11 Single Angle Flexural Member

Given:

Select an ASTM A36 single angle with a simple span of 6 ft. The vertical leg of the single
angle is down and the toe is in tension. The nominal loads are a uniform dead load of 0.05
kip/ft and a uniform live load of 0.15 kip/ft. There is no deflection limit for this angle.
Conservatively assume Cb = 1.0. Assume bending about the geometric x-x axis and that there
is no lateral-torsional restraint.

Solution:

Material Properties: Manual
ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-3

Calculate the required flexural strength

LRFD ASD
wu = 1.2(0.05 kip/ft) + 1.6(0.15 kip/ft) wa = 0.05 kip/ft + 0.15 kip/ft
\= 0.300 kip/ft = 0.200 kip/ft
( 0.300 kip/ft )(6 ft )2 ( 0.200 kip/ft )(6 ft )2
Mu = = 1.35 kip-ft Ma = = 0.900 kip-ft
8 8

Try L4×4×4

Geometric Properties: Manual
L4×4×4 Sx = 1.03 in3 Sz = 0.419 in.3 Table 1-7

Calculate the nominal flexural strength, Mn

For all calculations, My is taken as 0.80 times the yield moment calculated using the geometric
section modulus

3M y = 0.80 S x Fy = 0.80 (1.03in. )( 36 ksi ) = 29.7kip-in. Section
F10-2

Flexural yielding limit state

M n = 1.5 M y = 1.5 ( 29.7kip-in. ) Eqn. F10-1
\= 44.5 kip-in. or 3.71 kip-ft controls

<!-- p. 116 -->

F-40

Lateral-torsional buckling limit state

Determine Me

For bending about one of the geometric axes of an equal-leg angle without continuous lateraltorsional restraint and with maximum tension at the toe, use Equation F10-4b.

4 ⎛ 2 ⎞ Eqn. F10-4b 0.66 Eb tCb ⎛ Lt ⎞M e = 2 ⎜ 1 + 0.78 ⎜ 2 ⎟ + 1 ⎟ L ⎜ ⎝ b ⎠ ⎟ ⎝ ⎠
4 ⎛ 2 ⎞
0.66 ( 29,000 ksi )( 4.00 in. ) ( 0.250 in. )(1.0 ) ⎜ ⎛ ( 72.0 in. )( 0.250 in. ) ⎞ ⎟
\= 2 ⎜ 1 + 0.78 ⎜ 2 ⎟ + 1 ⎟
( 72.0 in. ) ⎜ ⎜⎝ ( 4.00 in. ) ⎟⎠ ⎟ ⎝ ⎠
\= 569 kip-in. > 29.7 kip-in. therefore, Equation F10-3 is applicable.

⎛ M y ⎞
M n = ⎜ 1.92 − 1.17 ⎟ M y ≤ 1.5 M y Eqn. F10-3 ⎜ M e ⎟ ⎝ ⎠
⎛ 29.7 kip-in. ⎞ = ⎜ 1.92 − 1.17 ⎟ 29.7 kip-in. ≤ 1.5 ( 29.7kip-in. ) ⎜ 569 kip-in. ⎟ ⎝ ⎠
\=49.1 kip-in. ≤ 44.5kip-in. , therefore

Mn = 44.5 kip-in. or 3.71 kip-ft.

LRFD ASD
φ b = 0.90 Ω=b 1.67 Section F1
φ b M n = 0.90 ( 3.71 kip-ft ) 3.71kip-ft M n / Ω=b
1.67
\= 3.34 kip-ft > 1.35 kip-ft o.k. = 2.22 kip-ft > 0.900 kip-ft o.k.

Note: In this example it is assumed that the toe of the vertical leg of the single angle is in
tension. If the toe of the outstanding leg is in compression, as in this example, the leg local
buckling limit state must also be checked. The designer should also consider the possibility
that restrained end conditions of a single angle member could unintentionally cause the
outstanding leg to be in compression.

<!-- p. 117 -->

F-41

Example F.12 Rectangular Bar in Strong-Axis Bending

Given:

Select an ASTM A36 rectangular bar with a span of 12 ft. The bar is braced at the ends and at
the midpoint. Conservatively use Cb = 1.0. Limit the depth of the member to 5 in. The
nominal loads are a total uniform dead load of 0.44 kip/ft and a uniform live load of 1.32
kip/ft.

Solution:

Material Properties: Manual
ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-3

LRFD ASD
wu = 1.2(0.440 kip/ft) + 1.6(1.32 kip/ft) wa = 0.440 kip/ft + 1.32 kip/ft
\= 2.64 kip/ft = 1.76 kip/ft
2.64 kip/ft (12.0 ft ) 2 1.76kip/ft (12.0 ft ) 2
Mu = = 47.5 kip-ft Ma = = 31.7 kip-ft
8 8

Try a 5 in.×3 in. bar.

Geometric Properties:
bd 2 ( 3.00 in. )( 5.00 in. ) 2 3
Rectangular bar 5×3 S x = = = 12.5 in.
6 6
bd 2 ( 3.00 in. )( 5.00 in. ) 2 3
Z x = = = 18.8 in.
4 4

Solution:

Calculate nominal flexural strength, Mn Section
F11.1
Flexural yielding limit state

Check limit

Lb d 0.08 E
2 ≤
t Fy

<!-- p. 118 -->

F-42

( 72.0 in.)( 5.00 in.) 0.08 ( 29,000 ksi )
2 ≤ 36 ksi ) ( 3.00 in.) (
40.0 \< 64.4, therefore the yielding limit state applies.

M n = M p = Fy Z ≤ 1.6 M y
Eqn. F11-1

3 1.6 M y = 1.6 Fy S x = 1.6 ( 36 ksi )(12.5 in. ) = 720 kip-in.

3 M p = Fy Z x = ( 36 ksi )(18.8 in. ) = 675 kip-in. \< 720 kip-in.

Use M n = M p = 675 kip-in. or 56.3 kip-ft

Lateral-torsional buckling limit state Section
F11.1
Lb d 0.08 E
As calculated above, 2 \< , therefore the lateral-torsional buckling limit state does not
t Fy
apply.

LRFD ASD
φb = 0.90 Ωb = 1.67 Section F1
φ b M n = 0.90 ( 56.3 kip-ft ) 56.3 kip-ft M n / Ω=b
1.67
\= 50.6 kip-ft > 47.5 kip-ft o.k. = 33.7 kip-ft > 31.7 kip-ft o.k.

<!-- p. 119 -->

F-43

Example F.13 Round Bar in Bending

Given:

Select an ASTM A36 round bar with a span of 2.50 feet. The bar is unbraced. The material is
ASTM A36. Assume Cb = 1.0. Limit the diameter to 2 in. The nominal loads are a
concentrated dead load of 0.10 kips and a concentrated live load of 0.25 kips at the center. The
weight of the bar is negligible.

Solution:

Material Properties: Manual
ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-3

Calculate the required flexural strength

LRFD ASD
Pu = 1.2(0.100 kip) + 1.6(0.250 kip) Pa = 0.100 kip + 0.250 kip
\= 0.520 kip = 0.350 kip
( 0.520 kip )( 2.50 ft ) ( 0.350 kip )( 2.50 ft )
Mu = = 0.325 kip-ft Ma = = 0.219 kip-ft
4 4

Try 1 in. diameter rod.

Geometric Properties:
πd 3 π (1.00 in. ) 2 3
Round bar S x = = = 0.0982 in.
32 32
d 3 (1.00 in. ) 3 3
Z x = = = 0.167 in.
6 6

Calculate the nominal flexural strength, Mn

Flexural yielding limit state

Mn = Mp = FyZx M 1.6 My Eqn. F11-1

1.6My = 1.6(36 ksi)(0.0982 in3) = 5.66 kip-in

FyZx = 36 ksi(0.167 in3) = 6.00 kip-in > 5.66 kip-in.

Therefore, Mn = 5.66 kip-in. or 0.471 kip-ft

<!-- p. 120 -->

F-44

Lateral-torsional buckling limit state Sec. F11.2

This limit state need not be considered for rounds.

Calculate the available flexural strength

φb = 0.90 Ωb = 1.67 Section F1
0.471 kip-ft
φbMn = 0.90(0.471 kip-ft) M n / Ω=b
1.67
\= 0.424 kip-ft > 0.325 kip-ft o.k. = 0.282 kip-ft > 0.219 kip-ft o.k.

<!-- p. 121 -->

F-45

Example F.14 Non-Symmetrical Z-shape in Strong-Axis
Bending

Given:

Determine the available strength of the ASTM A36 Z-shape shown for a simple span of 18 ft.
The Z-shape is braced at 6 ft on center. Assume a Cb = 1.0. The nominal loads are a uniform
dead load of 0.025 kip/ft and a uniform live load of 0.10 kip/ft. The profile of the purlin is
shown below.

<!-- p. 122 -->

F-46

Solution:

Material properties: Manual
Table 2-3
Z Purlin Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

tw = tf = 0.250 in.

2A = ( 2.50 in.)( 0.25 in.)( 2 ) + ( 0.25 in.)( 0.25 in.)( 2 ) + (11.5 in.)( 0.25 in.) = 4.25 in.

⎡ ( 0.25 in.)( 0.25 in.) 3 2 2 ⎤ xI = ⎢ + ( 0.25 in.) ( 5.62 in.) ⎥ ( 2 )
⎢ 12 ⎥ ⎣ ⎦
⎡ ( 2.50 in.)( 0.25 in.) 3 2 ⎤ + ⎢ + ( 2.50 in.)( 0.25 in.)( 5.87 in.) ⎥ ( 2 )
⎢ 12 ⎥ ⎣ ⎦
( 0.25 in.)(11.5 in.) 3
\+
12
\= 78.8 in. 4

y = 6.00 in.
I x 78.8 in. 4 3S x = = = 13.1 in.
y 6.00 in.
⎡ ( 0.25 in.)( 0.25 in.) 3 2 2 ⎤ yI = ⎢ + ( 0.25 in.) ( 2.25 in.) ⎥ ( 2 )
⎢ 12 ⎥ ⎣ ⎦
⎡ ( 0.25 in.)( 2.50 in.) 3 2 ⎤ + ⎢ + ( 2.50 in.)( 0.25 in.)(1.12 in.) ⎥ ( 2 )
⎢ 12 ⎥ ⎣ ⎦
(11.5 in.)( 0.25 in.) 3
\+
12
\= 2.88 in. 4
I y 2.87 in. 4
ry = = 2 = 0.823 in. A 4.25 in.
b f 2.50 in.
rts ≈ = = 0.543 in.
⎛ ht w ⎞ ⎛ (11.5 in. )( 0.250 in. ) ⎞ 12 ⎜ 1 + ⎟ 12 ⎜ 1 + ⎟ ⎜ ⎜ ⎟ ⎝ 6 ( 2.50 in. )( 0.250 in. ) ⎟⎠ ⎝ 6b f t f ⎠

Calculate the required flexural strength
LRFD ASD
wu = 1.2(0.025 kip/ft) + 1.6(0.10 kip/ft) wa = 0.025 kip/ft + 0.10 kip/ft
\= 0.190 kip/ft = 0.125 kip/ft

( 0.190 kip/ft )(18.0 ft ) 2 ( 0.125 kip/ft )(18.0 ft ) 2
Mu = = 7.70 kip-ft Ma = = 5.06 kip-ft
8 8

<!-- p. 123 -->

F-47

Flexural yielding limit state

Fn = Fy = 36 ksi Eqn. F12-2

Mn = FnS = 36 ksi(13.1 in.3) = 473 kip-in. or 39.4 kip-ft Eqn. F12-1.

Local buckling limit state

There are no specific local buckling provisions for Z-shapes in the Specification. Use
provisions for rolled channels from Specification Table B4.1.

Check for flange slenderness

Conservatively neglecting the end return:

b 2.50in.
λ = = = 10.0
t f 0.250in.

E 29,000 ksi Table B4.1
λ p = 0.38 = 0.38 = 10.8 > 10.0, therefore the flange is compact
Fy 36 ksi Case 1

Check for web slenderness

h 11.5 in.
λ = = = 46.0
t w 0.250 in.

E 29,000 ksi
λ p = 3.76 = 3.76 = 107 > 46.0, therefore the web is compact. Table B4.1
Fy 36 ksi Case 9
Therefore, no limit state for local buckling applies

Lateral-torsional buckling limit state

Per the User Note in Section F12, take the critical lateral-torsional buckling stress as half that
of the equivalent channel.

Calculate limiting unbraced lengths

For bracing at 6 ft on center, bL = ( 6.00 ft )(12 in./ft ) = 72.0 in.

E 29,000 ksiL p = 1.76 ry = 1.76 ( 0.823 in. ) = 41.1 in. \< 72.0 in.
Fy 36 ksi Eqn. F2-5

⎛ E ⎞ Jc ⎛ 0.7 Fy S x h0 ⎞ 2
Lr = 1.95rts ⎜ ⎟ 1 + 1 + 6.76 ⎜ ⎟ Eqn. F2-6 ⎝ 0.7 Fy ⎠ S x h0 ⎝ EJc ⎠

Per the user note in Specification Section F2, the square root term in Specification Equation

<!-- p. 124 -->

F-48

F2-4 can conservatively be taken equal to one, therefore,

E 29000 ksiLr = πrts = π ( 0.543 in. ) = 57.9 in. \< 72.0 in. 0.7 Fy 0.7 ( 36 ksi )

Calculate one half of the critical lateral-torsional buckling stress of the equivalent channel

Lb > Lr, therefore,
Eqn. F2-4
Cb π 2 E ⎛ Jc ⎞⎛ Lb ⎞ 2Fcr = ( 0.5 ) 2 1 + 0.078 ⎜ ⎟⎜ ⎟
⎛ Lb ⎞ ⎝ S x h0 ⎠⎝ rts ⎠
⎜ ⎟
⎝ rts ⎠

Conservatively taking the square root term as 1.0,

Cb π 2 E 1.0 π 2 ( 29,000 ksi )Fcr = ( 0.5 ) 2 = ( 0.5 ) 2 = 8.14 ksi
⎛ Lb ⎞ ⎛ 72.0 in. ⎞
⎜ ⎟ ⎜ ⎟
⎝ rts ⎠ ⎝ 0.543 in. ⎠

Fn = Fcr M Fy Eqn. F12-3
\= 8.14 ksi \< 36 ksi o.k.

M n = Fn S Eqn. F12-1

3 = ( 8.14 ksi )(13.1 in. ) = 107 kip-in. or 8.89 k-ft controls

Calculate the available strength

LRFD ASD
φb = 0.90 Ωb = 1.67 Section F1
8.89 kip-ft φ b M n = 0.90 ( 8.89 kip-ft ) M n / Ω=b
1.67
\= 8.00 kip-ft > 7.70 kip-ft o.k. = 5.32 kip-ft > 5.06 kip-ft o.k.

<!-- p. 125 -->

G-1

CHAPTER G
DESIGN OF MEMBERS FOR SHEAR

INTRODUCTION

This chapter covers webs of singly or doubly symmetric members subject to shear in the plane of the web, single
angles, HSS sections, and shear in the weak direction of singly or doubly symmetric shapes.

Most of the formulas from this chapter are illustrated by example. Tables for all standard ASTM A992 W-shapes
and ASTM A36 channels are included in the Manual. In the tables, where applicable, LRFD and ASD shear
information is presented side-by-side for quick selection, design and verification.

LRFD shear strengths have been increased slightly over those in the previous LRFD Specification for members
not subject to shear buckling. ASD strengths are essentially identical to those in the previous ASD Specification.
LRFD and ASD will produce identical designs for the case where the live load effect is approximately three times
the dead load effect.

G1. GENERAL PROVISIONS
The design shear strength, φvVn, and the allowable shear strength, Vn /Ωv are determined as follows:

Vn = nominal shear strength based on shear yielding or shear buckling

φv = 0.90 (LRFD) Ωv = 1.67 (ASD).

Exception: For all current ASTM A6, W, S, and HP shapes except W44×230, W40×149, W36×135, W33×118,
W30×90, W24×55, W16×26, and W12×14 for Fy = 50 ksi:

φv = 1.00 (LRFD) Ωv = 1.50 (ASD).

Section G2 does not utilize tension field action. Section G3 specifically addresses the use tension field action.

Strong axis shear values are tabulated for W-shapes in Manual Tables 3-2 and 3-6, for S-shapes in Manual Table
3-7, for C-shapes in Manual Table 3-8 and for MC-shapes in Manual Table 3-9. Weak axis shear values for Wshapes, S-shapes, C-shapes and MC-shapes and shear values for angles, rectangular HSS and box members, and
round HSS are not tabulated.

G2. MEMBERS WITH UNSTIFFENED OR STIFFENED WEBS

As indicated in the User Note of this section, virtually all W, S and HP shapes are not subject to shear buckling
and are also eligible for the more liberal safety and resistance factors, φv = 1.00 (LRFD) and Ωv = 1.50 (ASD).
This is presented in Example G.1 for a W-shape. A channel shear strength design is presented in Example G.2.

G3. TENSION FIELD ACTION

A built-up girder with a thin web and vertical stiffeners is presented in Example G.8.

G4. SINGLE ANGLES

Rolled angles are typically made from ASTM A36 steel. All single angles listed in the Manual have a Cv =1.0. A
single angle example is illustrated in Example G.3.

<!-- p. 126 -->

G-2

G5. RECTANGULAR HSS AND BOX MEMBERS

The shear height, h, is taken as the clear distance between the radii. If the corner radii are unknown, the outside
radius is taken as 3 times the design thickness. An HSS example is provide in Example G.4.

G6. ROUND HSS

For all Round HSS and Pipes of ordinary length listed in the Manual, Fcr can be taken as 0.6Fy in Specification
Equation G6-1. A round HSS example is illustrated in Example G.5.

G7. WEAK AXIS SHEAR IS SINGLE AND DOUBLY SYMMETRIC SHAPES

For a weak axis shear example see Example G.6 and Example G.7.

G8. BEAMS AND GIRDERS WITH WEB OPENINGS

For a beam and girder with web openings example see AISC Design Guide 2.

<!-- p. 127 -->

G-3

Example G.1a W-Shape in Strong-Axis Shear.

Given:

Verify the shear strength of a W24×62 ASTM A992 beam with end shears of 48 kips from dead load and 145 kips
from live load.

Solution:

Material Properties:
W24×62 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3
Geometric Properties:
W24×62 d = 23.7 in. tw = 0.430 in. Manual
Table 1-1

Calculate the required shear strength

LRFD ASD
Vu = 1.2(48.0 kips) + 1.6(145 kips) = 290 kips Va = 48.0 kips + 145 kips = 193 kips

Take the available shear strength from Manual Table 3-2

LRFD ASD
φvVn = 306 kips Vn/Ωv = 204 kips Manual
306 kips > 290 kips o.k. 204 kips > 193 kips o.k. Table 3-2

<!-- p. 128 -->

G-4

Example G.1b W-Shape in Strong-Axis Shear.

The available shear strength, which can be easily determined by the tabulated values of the
Steel Construction Manual, can be verified by directly applying the provisions of the
Specification.

Except for very few sections, which are listed in the User Note, Specification Section G2.1(a)
is applicable to the I-shaped beams published in the Manual when Fy ≤ 50 ksi.

Cv = 1.0 Eqn. G2-2

Calculate Aw

Aw = dtw = 23.7 in. (0.430 in.) = 10.2 in.2

Calculate Vn

Vn = 0.6FyAwCv = 0.6(50 ksi)(10.2 in. 2)(1.0) = 306 kips Eqn. G2-1

Calculate the available shear strength

LRFD ASD
φv = 1.00 Ωv = 1.50 Section G2.1a
φvVn = 1.00(306 kips) = 306 kips Vn/Ωv = 306 kips / 1.50 = 204 kips

<!-- p. 129 -->

G-5

Example G.2a C-Shape in Strong-Axis Shear.

Given:
Verify the shear strength of a C15×33.9 channel with end shears of 17.5 kips from dead load
and 52.5 kips from live load.

Solution:

Material Properties:
C15×33.9 ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-3
Geometric Properties:
C15×33.9 d = 15.0 in. tw = 0.400 in. Manual
Table 1-5
Calculate the required strength

LRFD ASD
Vu = 1.2(17.5 kips) + 1.6(52.5 kips) Va = 17.5 kips + 52.5 kips
\= 105 kips = 70.0 kips

Take the available shear strength from Manual Table 3-8

LRFD ASD
φvVn =117 kips Vn/Ωv = 77.6 kips Manual Table
117 kips > 105 kips o.k. 77.6 kips > 70.0 kips o.k. 3-8

<!-- p. 130 -->

G-6

Example G.2b C-Shape in Strong-Axis Shear.

The available shear strength, which can be easily determined by the tabulated values of the
Steel Construction Manual, can be verified by directly applying the provisions of the
Specification. Cv is 1.0 for all rolled channels when Fy ≤ 36 ksi, and Specification Equation
G2-1 is applicable.

Cv = 1.0 Eqn. G2-2

Calculate Aw

Aw = 15.0 in.(0.400 in.) = 6.00 in.2

Calculate Vn

Vn = 0.6FyAwCv = 0.6(36 ksi)(6.00 in.2)(1.0) = 130 kips Eqn. G2-1

Calculate the available shear strength

The values of φv = 1.00 (LRFD) and Ωv = 1.50 (ASD) do not apply to channels. The general
values φv = 0.90 (LRFD) and Ωv = 1.67 (ASD) must be used.

LRFD ASD
φvVn = 0.90(130 kips) = 117 kips Vn/Ωv =130 kips / 1.67 = 77.6 kips

<!-- p. 131 -->

G-7

Example G.3 Angle in Shear.

Given:
Verify the shear strength of a 5×3×4 (LLV) ASTM A36 angle with end shears of 3.5 kips
from dead load and 10.5 kips from live load.

Solution:

Material Properties:
L5×3×4 angle ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-3
Geometric Properties:
L5×3×4 angle d = 5.00 in. tw = 0.250 in. Manual
Table 1-7

Calculate the required shear strength

LRFD ASD
Vu = 1.2(3.50 kips) + 1.6(10.5 kips) Va = 3.50 kips + 10.5 kips
\= 21.0 kips = 14.0 kips

Note: There are no tables for angles in shear, but the shear strength can be calculated as
follows:

For angles in shear, use Specification Equation G2-1 with Cv = 1.0. Section G4

Calculate Aw

Aw = dtw = (5.00 in.)(0.250 in.) = 1.25 in.2

Calculate Vn

Vn = 0.6FyAwCv = 0.6(36 ksi)(1.25 in.2)(1.0) = 27.0 kips Eqn. G2-1

Calculate the available shear strength

LRFD ASD
φ v = 0.90 Ωv = 1.67 Section G1
φvVn = 0.90(27.0 kips) = 24.3 kips Vn/Ωv = 27.0 kips / 1.67 = 16.2 kips
24.3 kips > 21.0 kips o.k. 16.2 kips > 14.0 kips o.k.

<!-- p. 132 -->

G-8

Example G.4 Rectangular HSS in Shear.

Given:

Verify the shear strength of a HSS6×4×a ASTM A500 grade B member with end shears of 11 kips from dead
load and 33 kips from live load. The beam is oriented with the shear parallel to the 6 in. dimension.

Solution:

Material Properties:
HSS6×4×a ASTM A500B Fy = 46 ksi Fu = 58 ksi Manual
Table 2-3
Geometric Properties:
HSS6×4×a h = 6.00 in. w = 4.00 in. t = 0.349 in. Manual
Table 1-11
Calculate the required shear strength

LRFD ASD
Vu = 1.2(11.0 kips) + 1.6(33.0 kips) Va = 11.0 kips + 33.0 kips
\= 66.0 kips = 44.0 kips

User note: There are no Manual Tables for shear in HSS shapes, but the shear strength can be
calculated as follows:

Calculate the nominal strength Section G5

For rectangular HSS in shear, use Section G2.1 with Aw = 2ht and kv = 5.

If the exact radius is unknown, the radius is taken as 3 times the design thickness.

h = d – 2(3tw) = 6.00 in. – 2(3)(0.349 in.) = 3.91 in.

h/tw = 3.91 in. / 0.349 in. = 11.2

1.10 k v E F y =1.10 5(29,000 ksi 46 ksi) = 61.8

11.2 \< 61.8 Therefore Cv = 1.0 Eqn. G2-3

Note: most standard HSS sections listed in the manual have Cv = 1.0 at Fy ≤ 46 ksi.Calculate
Aw

Aw = 2ht = 2(3.91 in.)(0.349 in.) = 2.73 in.2

Calculate Vn

Vn = 0.6FyAwCv = 0.6(46 ksi)(2.73 in.2)(1.0) = 75.2 kips
Eqn. G2-1
Calculate the available shear strength

LRFD ASD
φv = 0.90 Ωv = 1.67 Section G1
φvVn = 0.90(75.2 kips) = 67.7 kips Vn /Ωv = 75.2 kips / 1.67 = 45.0 kips
67.7 kips > 66.0 kips o.k. 45.0 kips > 44.0 kips o.k.

<!-- p. 133 -->

G-9

Example G.5 Round HSS in Shear.

Given:

Verify the shear strength of a round HSS16.000×0.375 ASTM A500 grade B member
spanning 32 feet with end shears of 30 kips from dead load and 90 kips from live load.

Solution:

Material Properties:
HSS16.000×0.375 ASTM A500 Gr.B Fy = 42 ksi Fu = 58 ksi Manual
Table 2-3
Geometric Properties:
HSS16.000×0.375 D = 16.0 in. t = 0.349 in. Ag =17.2 in.2 Manual
Table 1-13

Note: There are no Manual tables for Round HSS in shear, but the strength can be calculated
as follows:

Calculate the required shear strength

LRFD ASD
Vu = 1.2(30.0 kips) + 1.6(90.0 kips) Va = 30.0 kips + 90.0 kips
\= 180 kips = 120 kips

Calculate Fcr as the smallest of: Section G6

1.60 E
Fcr = 5 take Lv as half the span = 192 in. Eqn. G6-2a
Lv ⎛ D ⎞ 4
⎜ ⎟
D ⎝ t ⎠
1.60(29,000ksi)
\= 5 = 112 ksi
192 in. ⎛ 16.0 in. ⎞ 4 Eqn. G6-2b
⎜ ⎟
16.0 in. ⎝ 0.349 in. ⎠

or

0.78 E 0.78(29,000ksi)
Fcr = 3 = 3 = 73 ksi
2 ( D / t ) 2 ⎛ 16.0 in. ⎞ ⎜ ⎟
⎝ 0.349 in. ⎠
or

Fcr = 0.6Fy = 0.6(42ksi) = 25.2ksi controls

Note: Equations G6-2a and G6-2b will not normally control for the sections published in the
Manual except when high strength steel is used or the span is unusually long.

Calculate Vn Section G6

2 Fcr Ag ( 25.2 ksi )(17.2in. )
Vn = = = 217 kips
2 2

<!-- p. 134 -->

G-10

Calculate the available shear strength Eqn. G6-1

LRFD ASD
φv = 0.90 Ωv = 1.67 Section G1
φvVn = 0.90(217 kips) = 195 kips Vn/Ωv = 217 kips / 1.67 = 130 kips
195 kips > 190 kips o.k. 130 kips > 120 kips o.k.

<!-- p. 135 -->

G-11

Example G.6 Doubly-Symmetric Shape in Weak-Axis Shear.

Given:

Verify the strength of a W21×48 ASTM A992 beam with end shears of 20 kips from dead load
and 60 kips from live load in the weak direction.

Solution:

Material Properties:
W21×48 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3
Geometric Properties:
W21×48 bf = 8.14 in. tf = 0.430 in. Manual
Table 1-1

Calculate the required shear strength

LRFD ASD
Vu = 1.2(20.0 kips) + 1.6(60.0 kips) Va = 20.0 kips + 60.0 kips = 80.0 kips
\= 120 kips

For weak axis shear, use Equation G2-1 and Section G2.1(b) with Aw = bftf for each flange and Section G7
kv = 1.2.

Calculate Aw (multiply by 2 for both shear resisting elements)

Aw =2bf tf = 2(8.14 in.)(0.430 in.) = 7.00 in2

Calculate Cv Section G2.1b

bf /tf = 8.14 in. / 0.430 in. = 18.9

1.10 k v E F y =1.10 1.2(29,000 ksi 50 ksi) = 29.0 > 18.9 therefore, Cv = 1.0 Eqn. G2-3

Note: For all ASTM A6 W, S, M, and HP shapes, when Fy \< 50 ksi, Cv = 1.0.

Calculate Vn

Vn = 0.6FyAwCv = 0.6(50 ksi)(7.00 in.2)(1.0) = 210 kips
Eqn. G2-1
Calculate the available shear strength

LRFD ASD
φ v = 0.90 Ωv = 1.67 Section G1
φvVn = 0.90(210 kips) = 189 kips Vn/Ωv = 210 kips / 1.67 = 126 kips
189 kips > 120 kips o.k. 126 kips > 80.0 kips o.k.

<!-- p. 136 -->

G-12

Example G.7 Singly-Symmetric Shape in Weak-Axis Shear.

Given:

Verify the strength of a C9×20 ASTM A36 channel with end shears of 5 kips from dead load and 15 kips from
live load in the weak direction.

Solution:

Material Properties:
C9×20 ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-3
Geometric Properties:
C9×20 bf = 2.65 in. tf = 0.413 in. Manual
Table 1-5

Note: There are no Manual tables for this, but the strength can be calculated as follows:

Calculate the required shear strength

LRFD ASD
Vu = 1.2(5.00 kips) + 1.6(15.0 kips) Va = 5.00 kips + 15.0 kips
\= 30.0 kips = 20.0 kips

For weak axis shear, use Equation G2-1 and Section G2.1(b) with Aw = bftf for each flange and Section G7
kv = 1.2.

Calculate Aw (multiply by 2 for both shear resisting elements)

Aw =2bf tf = 2(2.65 in.)(0.413in.) = 2.19 in.2 Section G7

Calculate Cv
Section G2.1b
bf /tf = 2.65 in. / 0.413 in. = 6.42

1.10 k v E Fy =1.10 1.2(29,000 ksi 36 ksi) = 34.2 > 6.42 Therefore, Cv = 1.0 Eqn. G2-3

Calculate Vn

Vn = 0.6FyAwCv = 0.6(36 ksi)(2.19 in.2)(1.0) = 47.3 kips
Eqn. G2-1
Calculate the available shear strength

LRFD ASD
φ v = 0.90 Ωv = 1.67 Section G1
φvVn = 0.90(47.3 kips) = 42.6 kips Vn/Ωv = 47.3 kips / 1.67 = 28.3 kips
42.5 kips > 30.0 kips o.k. 28.3 kips > 20.0 kips o.k.

<!-- p. 137 -->

G-13

Example G.8a Built-up Plate Girder with Transverse Stiffeners

Given:

A built up ASTM A36 I-shaped girder spanning 56 ft. has a uniformly distributed dead load of
0.92 klf and a live load of 2.74 klf in the strong direction. The girder is 36 in. tall with 12 in. ×
1½ in. flanges and a c in. web. Determine if the member has sufficient available shear
strength to support the end shear, without and with tension field action. Use transverse
stiffeners, as required.

User note: This built-up girder was purposely selected with a thin web in order to illustrate the
design of transverse stiffeners. A more conventionally proportioned plate girder would have at
least a ½ in. web and slightly smaller flanges.

Solution:

Material Properties:
Built-up girder ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-3
Geometric Properties:
Built-up girder tw= 0.313 in. d = 36.0 in. bft = bfc = 12.0 in.
tf = 1.50 in. h = 33.0 in.

Calculate the required shear strength at the support

LRFD ASD
Ru =[1.2(0.92 klf) + 1.6(2.74 klf)](28.0 ft) Ra = (0.92 klf + 2.74 klf)(28.0 ft)
\= 154 kips = 102 kips

Determine if stiffeners are required

Aw = dtw = (36.0 in.)(0.313 in.) = 11.3 in.2

h/tw = 33.0 in. / 0.313 in. = 105

105 \< 260 Therefore, kv = 5 Section G2.1b

1.37 vk E / Fy = 1.37 5(29,000 ksi) /(36 ksi) = 86.9

105 > 86.9 therefore, use Specification Eqn. G2-5 to calculate Cv

<!-- p. 138 -->

G-14

1.51Ek v 1.51(29,000 ksi)(5) Eqn. G2-5
Cv = 2 = 2 = 0.547
( h / t w ) Fy (105) (36 ksi)

Calculate Vn
Eqn. G2-1
Vn = 0.6FyAwCv = 0.6(36 ksi)(11.3 in.2)(0.547) = 134 kips

Check the available shear strength without stiffeners

LRFD ASD
φv = 0.90 Ωv = 1.67 Section G1
φvVn = 0.90(134 kips) = 120 kips Vn /Ωv = 134 kips / 1.67 = 80.0 kips
120 kips \< 154 kips not o.k. 80.0 kips \< 102 kips not o.k.

Therefore, stiffeners are required. Therefore, stiffeners are required.

Manual Tables 3-16a and 3-16b can be used to select stiffener spacings needed to develop the
required stress in the web.

Limits on the Use of Tension Field Action: Section G3.1

Consideration of tension field action is not permitted if any of the following are true:

a) end panels in all members with transverse stiffeners
b) members when a/h exceeds 3.0 or [260/(h/tw)]2
c) 2Aw /(Afc+Aft) > 2.5
d) h/bfc or h/bft > 6.0

Select stiffener spacing for end panel

Tension field action is not permitted for end panels, therefore use Table 3-16a.

LRFD ASD
Use Vu =φvVn to determine the required Use Va = Vn/Ωv to determine the required
stress in the web by dividing by the web area stress in the web by dividing by the web area

φ vVn Vu 154 kips Vn Va 102 kips
\= = 2 = 13.6 ksi = = 2 = 9.03 ksi
Aw Aw 11.3in. Ω v Aw Aw 11.3 in.

Use Table 3-16a from the Manual to select the required stiffener ratio a/h based on the h/t ratio Manual
φ vVn Table 3-16aof the girder and the required stress. Interpolate and follow an available stress curve, =
Aw
Vn13.6 ksi for LRFD, = 9.03 ksi for ASD, until it intersects the horizontal line for a h/tw
Ω v Aw
value of 105. Project down from this intersection and take the maximum a/h value of 1.80
from the axis across the bottom. Since h = 33.0 in., stiffeners are required at (1.80)(33.0 in.) =
59.4 in. maximum. Therefore, use 59.0 in.

Select stiffener spacing for the second panel

Tension field action is allowed, but not required, since the second panel is not an end panel. Section G3.1

<!-- p. 139 -->

G-15

Calculate the required shear strength at the start of the second panel, 59 in. from end

LRFD ASD
59.0in. ⎞ ⎛ 59.0 in . ⎞
Va = 102k - (0.92klf + 2.74klf) ⎜ ⎟ Vu = 154k − [1.2(0.92klf)+1.6(2.74klf) ]⎛⎜ ⎟ ⎝ 12in./ft ⎠ ⎝ 12 in./ft ⎠
\= 127 kips = 84.0 kips

Check the available shear strength without stiffeners

LRFD ASD
φv = 0.90 Ωv = 1.67 Section G1

From previous calculation From previous calculation
φvVn = 0.90(134 kips) = 120 kips Vn/Ωv = 134 kips / 1.67 = 80.0 kips
120 kips \< 127 kips not o.k. 80.0 kips \< 84.0 kips not o.k.

Therefore additional stiffeners are Therefore additional stiffeners are
required. required.

Use Vu =φvVn to determine the required Use Va = Vn/Ωv to determine the required
stress in the web by dividing by the web area stress in the web by dividing by the web area

φ vVn Vu 127 kips Vn Va 84.0 kips
\= = 2 = 11.2 ksi = = 2 = 7.43 ksi
Aw Aw 11.3in. Ω v Aw Aw 11.3 in.

Use Table 3-16b from the Manual to select the required stiffener a/h ratio based on the h/t ratio Manual
of the girder and the required stress. Interpolate and follow an available stress curve, Table 3-16b
φ vVn Vn = 11.2 ksi for LRFD, = 7.43 ksi for ASD, until it intersects the horizontal line for
Aw Ω v Aw
a h/tw value of 105. Because the available stress does not intersect the h/tw value of 105, the
maximum value of 3.0 for a/h may be used. Since h = 33.0 in., an additional stiffener is
required at (3.0)(33.0 in.) = 99.0 in. maximum from the previous one.

Select stiffener spacing for the second panel

Tension field action is allowed, but not required, since the next panel is not an end panel. Section G3.1

Calculate the required shear strength at the start of the third pane, 158 in. from end

LRFD ASD
Vu = 154 kips Va = 102 kips
⎛ 158.0in. ⎞ ⎛ 158.0in. ⎞
\- [1.2(0.920 klf) + 1.6(2.74 klf)] ⎜ ⎟ - (0.920 klf + 2.74 klf) ⎜ ⎟
⎝ 12 in./ft ⎠ ⎝ 12 in./ft ⎠
\= 81.7 kips = 53.8 kips

<!-- p. 140 -->

G-16

Check the available shear strength without stiffeners

LRFD ASD
φv = 0.90 Ωv = 1.67 Section G1

From previous calculation From previous calculation
φvVn = 0.90(134 kips) = 120 kips Vn/Ωv = 134 kips / 1.67 = 80.0 kips
120 kips > 81.7 kips o.k. 80.0 kips > 53.8 kips o.k.

Therefore additional stiffeners are not Therefore additional stiffeners are not
required. required.

The four Available Shear Stress tables, Manual Tables 3-16a, 3-16b, 3-17a and 3-17b, are Manual
useful because they permit a direct solution for the required stiffener spacing. Alternatively, Table 3-16
you can select a stiffener spacing and check the resulting strength, although this process is
likely to be iterative. In the proof below, the stiffener spacings that were selected from the
charts in the example above are used.

<!-- p. 141 -->

G-17

Example G.8b Built-up Plate Girder with Transverse Stiffeners

The stiffener spacings from Example G.8a, which were easily determined from the tabulated
values of the Steel Construction Manual, are verified below by directly applying the provisions
of the Specification.

Verify the shear strength of end panel Section G2.1b
5 5
kv = 5 + 2 = 5 + 2 = 6.54
( a / h ) (1.80 )

h/tw = 33.0 in. / 0.313 in. = 105

Check a/h limits

59 in.a/h = = 1.80 ≤ 3.0
33 in.
⎡ 260 ⎤ 2 ⎡ 260 ⎤ 2
a/h = 1.80 \< ⎢ ⎥ = ⎢ ⎥ = 6.13 ⎣ ( h / t w ) ⎦ ⎣ 105 ⎦
Therefore, use kv = 6.54.

Tension field action is not allowed since the panel is an end panel.

Since h / t w > 1.37 k v E / Fy = 1.37 ( 6.54 )( 29,000 ksi ) / ( 36ksi ) = 99.5 ,
1.51Ek v 1.51 ( 29,000 ksi )( 6.54 )
Cv = 2 = 2 = 0.721 Eqn. G2-5
( h / t w ) Fy (105) 36 ksi

Vn = 0.6FyAwCv = 0.6(36ksi)(11.3 in.2)(0.721) = 176 kips Eqn. G2-1

Calculate the available shear strength

LRFD ASD
φv = 0.90 Ωv = 1.67 Section G1
φvVn = 0.90(176 kips) =159 kips Vn/Ωv = (176 kips) / 1.67 = 106 kips
159 kips > 154 kips o.k. 106 kips > 102 kips o.k.

Verify the shear strength of the second panel

a/h for the second panel was 3.0
5 5
kv = 5 + 2 = 5 + 2 = 5.56
( a / h ) ( 3.0 )

Check a/h limits
99 in.a/h = = 3.00 ≤ 3.0
33 in. Section G2.1
⎡ 260 ⎤ 2 ⎡ 260 ⎤ 2
a/h = 3.00 \< ⎢ ⎥ = ⎢ ⎥ = 6.13 ⎣ ( h / t w ) ⎦ ⎣ 105 ⎦
Therefore use kv = 5.56

<!-- p. 142 -->

G-18

Since h / t w > 1.37 k v E / Fy = 1.37 ( 5.56 )( 29,000 ksi ) / ( 36ksi ) = 91.7 ,
1.51Ek v 1.51(29,000 ksi)(5.56) Eqn. G2-5
Cv = 2 = 2 = 0.613
( h / t w ) Fy (105) (36 ksi)

Section G3.2
Since h / t w > 1.10 k v E / Fy =1.10 5.56(29,000ksi) /(36ksi) = 73.6, use Eqn. G3-2
⎡ 1 − C v ⎤
Vn = 0.6 Fy Aw ⎢C v + 2 ⎥ Eqn. G3-2
⎢⎣ 1.15 1 + ( a / h ) ⎥⎦
2 ⎡ 1 − 0.613 ⎤
\= 0.6(36 ksi)(11.3 in. ) ⎢ 0.613 + 2 ⎥
⎣ 1.15 1 + (3.0) ⎦
Vn = 176 kips

Calculate the available shear strength

LRFD ASD
φv= 0.90 Ωv = 1.67 Section G1
φvVn = 0.90(176 kips) =158 kips Vn/Ωv = (176 kips) / 1.67 = 105 kips
156 kips > 127 kips o.k. 105 kips > 84.0 kips o.k.

<!-- p. 143 -->

H-1

CHAPTER H
DESIGN OF MEMBERS FOR COMBINED FORCES AND TORSION

For all interaction equations in Specification Section H, the required forces and moments must include the results
of a second-order analysis, as required by Section C of the Specification. This represents a significant change for
ASD users, who are accustomed to using an interaction equation that includes a partial second-order
amplification.

<!-- p. 144 -->

H-2

Example H.1a W-shape Subjected to Combined Compression and Bending
About Both Axes (braced frame).

Given:
Verify if an ASTM A992 W14×99 has sufficient available strength to support the axial forces and moments
listed below, obtained from a second order analysis that includes P-δ effects. The unbraced length is 14 ft and
the member has pinned ends. KLx = KLy = Lb = 14.0 ft

LRFD ASD
Pu = 400 kips Pa = 267 kips
Mux = 250 kip-ft Max = 167 kip-ft
Muy = 80.0 kip-ft May = 53.3 kip-ft

Solution:

Material Properties: Manual
ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3

Try a W14×99

Take combined strength parameters from Manual Table 6-1
LRFD ASD

0.886 1.33 Manual
p = 3 at 14.0 ft p = 3 at 14.0 ft 10 kips 10 kips Table 6-1

1.38 2.08
bx = 3 at 14.0 ft bx = 3 at 14.0 ft 10 kip-ft 10 kip-ft
2.85 4.29
by = 103 kip-ft by = 3 10 kip-ft

Check limit for Equation H1-1a Check limit for Equation H1-1a
Pu 400 kips Pa 267 kips Manual = = 0.354 = = 0.356 Table 4-1 φ c Pn 1,130 kips Pn / Ω c 751 kips
Pu Pa Section H1.1 Since > 0.2, Since > 0.2,
φ c Pn Pn / Ω c
pPu + bxMux + byMuy M 1.0 pPa + bxMax + byMay M 1.0

⎛ 0.866 ⎞ ⎛ 1.33 ⎞
\= 267kips ) 400 kips ) = ⎜ 3 ⎟ ( ⎜ 3 ⎟ ( ⎝ 10 kips ⎠ ⎝ 10 kips ⎠
⎛ 1.38 ⎞ ⎛ 2.08 ⎞ 167kip-ft ) 250 kip-ft ) +⎜ 3 ⎟ ( +⎜ 3 ⎟ ( ⎝ 10 kip-ft ⎠ ⎝ 10 kip-ft ⎠
⎛ 2.85 ⎞ ⎛ 4.29 ⎞ 53.3kip-ft ) 80.0 kip-ft ) +⎜ 3 ⎟ ( +⎜ 3 ⎟ ( ⎝ 10 kip-ft ⎠ ⎝ 10 kip-ft ⎠

\= 0.346 + 0.345 + 0.228 = 0.927 M 1.0 o.k. = 0.356 + 0.347 + 0.229 = 0.931 M 1.0 o.k.
Manual Table 6-1 simplifies the calculation of Specification Equations H1-1a and H1-1b. A
direct application of these equations is shown in Example H.2.

<!-- p. 145 -->

H-3

Example H.1b W-shape Column Subjected to Combined Compression and
Bending Moment About Both Axes (braced frame)

Verify if an ASTM A992 W14×99 has sufficient available strength to support the axial forces and moments
listed below, obtained from a second order analysis that includes second-order effects. The unbraced length is
14 ft and the member has pinned ends. KLx = KLy = Lb = 14.0 ft

LRFD ASD
Pu = 400 kips Pa = 267 kips
Mux = 250 kip-ft Max = 167 kip-ft
Muy = 80.0 kip-ft May = 53.3 kip-ft

Solution:

Material Properties: Manual
ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3

Take the available axial and flexural strengths from the Manual Tables

LRFD ASD
at KLy = 14.0 ft, at KLy = 14.0 ft, Manual
Pc = φcPn = 1130 kips Pc = Pn/Ωc= 751 kips Table 4-1

at Lb = 14.0 ft, at Lb = 14.0 ft, Manual
Mcx = φMnx = 642 kip-ft Mcx = Mnx /Ω = 428 kip-ft Table 3-10

Mcy = φMny = 311 kip-ft Mcy = Mny /Ω = 207 kip-ft Manual
Table 3-2
Pu 400 kips Pa 267 kips = = 0.354 = = 0.356
φ c Pn 1,130 kips Pn / Ω c 751 kips
Pu Pa Since > 0.2, use Eqn. H1.1a Since > 0.2, use Eqn. H1.1a
φ c Pn Pn / Ω c

8 ⎛ 8 ⎛ M ry ⎞ M ry ⎞ M rx M rx Pr Pr + + + + ⎜ ⎟ M 1.0 ⎜ ⎟ M 1.0 ⎜ ⎟ ⎜ ⎟ Eq. H1.1a Pc 9 ⎝ M cx M cy ⎠ Pc 9 ⎝ M cx M cy ⎠

400 kips 8 ⎛ 250 kip-ft 80.0 kip-ft ⎞ 267 kips 8 ⎛ 167 kip-ft 53.3 kip-ft ⎞
\+ ⎜ + ⎟ + ⎜ + ⎟
1130 kips 9 ⎝ 642 kip-ft 311 kip-ft ⎠ 751 kips 9 ⎝ 428 kip-ft 207 kip-ft ⎠
8 8
\< 1.0 = 0.354 + ( 0.389 + 0.257 ) = 0.929 \< 1.0 = 0.356 + ( 0.390 + 0.257 ) = 0.931
9 9
o.k. o.k.

<!-- p. 146 -->

H-4

Example H.2 W-Shape Column Subjected to Combined Compression and
Bending Moment About Both Axes
(by Specification Section H2)

Given:
Verify if an ASTM A992 W14×99 shown in Example H.1 has sufficient available strength, using
Specification Section H2.1. This example is included primarily to illustrate the use of Specification Section
H2. KLx = KLy = Lb = 14.0 ft

LRFD ASD
Pu = 400 kips Pa = 267 kips
Mux = 250 kip-ft Max = 167 kip-ft
Muy = 80.0 kip-ft May = 53.3 kip-ft

Solution:

Material Properties: Manual
ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3

Geometric Properties: Manual
W14×99 A = 29.1 in.2 Sx = 157 in.3 Sy = 55.2 in.3 Table 1-1

Calculate the required flexural and axial stresses

LRFD ASD
Pu 400 kips Pa 267kips
f a = = 2 = 13.7ksi f a = = 2 = 9.18ksi A 29.1in. A 29.1in.
M ux 250 kip-ft ⎛ 12in. ⎞ M ax 167kip-ft ⎛ 12in. ⎞
f bw = = 3 ⎜ ⎟ = 19.1ksi f bw = = 3 ⎜ ⎟ = 12.8ksi
S x 157in. ⎝ ft ⎠ S x 157in. ⎝ ft ⎠
M uy 80.0 kip-ft ⎛ 12in. ⎞ M ay 53.3kip-ft ⎛ 12in. ⎞
f bz = = 3 ⎜ ⎟ = 17.4 ksi f bz = = 3 ⎜ ⎟ = 11.6 ksi
S y 55.2in. ⎝ ft ⎠ S y 55.2in. ⎝ ft ⎠

Calculate the available flexural and axial stresses from the available strengths in Example H.1b

LRFD ASD
φ c Pn 1,130 kips Fcr Pn 751kips
Fa = φ c Fcr = = 2 = 38.8ksi Fa = = = 2 = 25.8ksi
A 29.1in. Ω c Ω c A 29.1in.
φ b M nx 645kip-ft ⎛ 12in. ⎞ M nx 431kip-ft ⎛ 12in. ⎞
Fbw = = 3 ⎜ ⎟ = 49.3ksi Fbw = = 3 ⎜ ⎟ = 32.9ksi S x 157in. ⎝ ft ⎠ Ω b S x 157in. ⎝ ft ⎠
φ b M ny 311kip-ft ⎛ 12in. ⎞ M ny 207kip-ft ⎛ 12in. ⎞
Fbz = = 3 ⎜ ⎟ = 67.6 ksi Fbz = = 3 ⎜ ⎟ = 45.0 ksi S y 55.2in. ⎝ ft ⎠ Ω b S y 55.2in. ⎝ ft ⎠

As shown in the LRFD calculation of Fbz above, the available flexural stresses can exceed the
yield stress in cases where the available strength is governed by yielding and the yielding strength
is calculated using the plastic section modulus.

<!-- p. 147 -->

H-5

Calculate the combined stress ratio

LRFD ASD
f a f bw f bw + + a + + f bz M 1.0 f f bz M 1.0 Eqn. H2-1
Fa Fbw Fbz Fa Fbw Fbz

13.7 ksi 19.1 ksi 17.4 ksi 9.18 ksi 12.8 ksi 11.6 ksi
\+ + = 0.998 \< 1.0 + + = 1.00 o.k.
38.8 ksi 49.3 ksi 67.6 ksi 25.8 ksi 32.9 ksi 45.0 ksi
o.k.

A comparison of these results with those from Example H.1 shows that Equation H1-1a will
produce less conservative results than Equation H2-1 when its use is permitted.

Note: this check is made at a point. The designer must therefore select which point along the
length is critical, or check multiple points if the critical point can not be readily determined.

<!-- p. 148 -->

H-6

Example H.3 W-Shape Subject to Combined Axial Tension and Flexure.

Given:
Select an ASTM A992 W-shape with a 14-in. nominal depth to carry nominal forces of 29 kips from dead
load and 87 kips from live load in axial tension, as well as the following nominal moments:

MxD = 32.0 kip-ft MxL = 96.0 kip-ft
MyD = 11.3 kip-ft MyL = 33.8 kip-ft

The unbraced length is 30 ft and the ends are pinned. Assume the connections are made with no holes.

Solution:

Material Properties: Manual
ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3

Calculate the required strength

LRFD ASD
Pu = 1.2(29.0 kips) + 1.6(87.0 kips) Pa = 29.0 kips + 87.0 kips
\= 174 kips = 116 kips
Mux = 1.2(32.0 kip-ft) + 1.6(96.0 kip-ft) May = 32.0 kip-ft + 96 kip-ft
\= 192 kip-ft = 128 kip-ft
Muy = 1.2(11.3 kip-ft) + 1.6(33.8 kip-ft) May = 11.3 kip-ft + 33.8 kip-ft
\= 67.6 kip-ft = 45.1 kip-ft

Verify that a W14×82 has sufficient available strength

Geometric Properties: Manual
W14×82 A = 24.0 in.2 Sx = 123 in.3 Zx = 139 in.3 Sy = 29.3 in.3 Table 1-1
Zy = 44.8 in.3 Iy = 148 in.4 Lp = 8.76 ft Lr = 33.1 ft Table 3-2

Calculate the nominal gross tensile strength

Pn = FyAg = (50 ksi)(24.0 in.2) = 1200 kips Eqn. D2-1

Note that for a member with holes, the rupture strength of the member would also have to be
computed using Specification Equation D2-2.

Calculate the nominal flexural strength for bending about the x-x axis

Yielding limit state

Mnx = Mp = FyZx = 50 ksi(139 in.3) = 6950 kip-in = 579 kip-ft Eqn. F2-1

Lateral-torsional buckling limit state

Lb = 30.0 ft

Since Lp \< Lb M Lr, Equation F2-2 applies

<!-- p. 149 -->

H-7

Calculate lateral-torsion buckling modification factor

From Manual Table 3-1, Cb = 1.14, without considering the beneficial effects of the tension Section H1.2
force. However, Cb may be increased because the column is in axial tension.

4 π 2 EI y π 2 ( 29,000 ksi )(148 in. )
Pey = 2 = 2 = 327 kips
Lb ( ( 30.0 ft )(12.0 in./ft ) )

LRFD ASD
Pu 174 kips 1.5 Pa 1.5 (116 kips ) 1 + = 1 + = 1.24 1 + = 1 + = 1.24
Pey 327kips Pey 327kips

C b = 1.24 (1.14 ) = 1.41
⎡ ⎛ Lb - L p ⎞ ⎤
⎥ M Mp Eqn. F2-2 ⎟Mn = Cb ⎢ M p - ( M p -0.7 Fy S x ) ⎜⎜ ⎟ ⎝ Lr - L p ⎠ ⎢⎣ ⎥⎦
⎡ 3 ⎛ 30.0ft - 8.76ft ⎞ ⎤Mn = 1.41 ⎢ 6950 kip-in. - ( 6950 kip-in. - 0.7 ( 50 ksi )(123 in. ) ) ⎜ ⎟ ⎥
⎣ ⎝ 33.1ft - 8.76ft ⎠ ⎦
\= 6550 kip \< Mp therefore use:

Mn = 6550 kip-in. or 545 kip-ft controls

Local buckling limit state

Per Manual Table 1-1, the cross section is compact at Fy = 50 ksi; therefore, the local buckling Manual
limit state does not apply. Table 1-1

Calculate the nominal flexural strength for bending about the y-y axis

Yielding limit state

Since W14×82 has compact flanges, only the limit state of yielding applies.

Mny = Mp = FyZy M 1.6FySy Eqn. F6-1

\= 50 ksi(44.8 in.3) M 1.6(50 ksi)(29.3 in.3)

\= 2240 kip-in \< 2344 kip-in., therefore use:

Mny = 2240 kip-in. or 187 kip-ft

<!-- p. 150 -->

H-8

LRFD ASD
Sections D2
φb = φt = 0.90 Ωb = Ωt = 1.67 and F1
1200 kips
Pc = φtPn = 0.90(1200 kips) = 1080 kips Pc = Pn /Ω=t = 719 kips
1.67
545 kip-ft
Mcx = φbMnx = 0.90(545 kip-ft) = 491 kip-ft Mcx = M nx / Ω b = = 327 kip-ft
1.67
187 kip-ft
Mcy = φbMny = 0.90(187 kip-ft) = 168 kip-ft Mcy = M ny / Ω=b = 112 kip-ft
1.67

Check limit for Equation H1-1a

LRFD ASD
Pr Pu 174 kips Pr Pa 116 kips = = = 0.161 \< 0.2 = = = 0.161 \< 0.2
φ t Pn φ t Pn 1080 kips Pn / Ω t Pn / Ω t 719 kips

Therefore, Equation H1-1b applies

Pr ⎛ M rx M ry ⎞
\+ ⎜ + ⎟ ≤ 1.0 Eqn. H1-1b
2 Pc ⎝ M cx M cy ⎠

LRFD ASD
174 kips ⎛ 192 kip-ft 67.6 kip-ft ⎞ 116 kips ⎛ 128 kip-ft 45.1 kip-ft ⎞
\+ ⎜ + ⎟ ≤ 1.0 + ⎜ + ⎟ ≤ 1.0 2 (1080 kips ) ⎝ 491 kip-ft 168 kip-ft ⎠ 2 ( 719 kips ) ⎝ 327 kip-ft 112 kip-ft ⎠

0.874 \< 1.0 o.k. 0.875 \< 1.0 o.k.

<!-- p. 151 -->

H-9

Example H.4 W-Shape Subject to Combined Axial Compression and
Flexure

Given: Select an ASTM A992 W-shape with a 10 in. nominal depth to carry nominal axial compression
forces of 5 kips from dead load and 15 kips from live load. The unbraced length is 14 ft and the ends are
pinned. The member also has the following nominal required moment strengths, not including second-order
effects:

MxD = 15 kip-ft MxL = 45 kip-ft
MyD = 2 kip-ft MyL = 6 kip-ft

The member is not subject to sidesway.

Solution:

Material Properties:
ASTM A992 Fy = 50 ksi Fu = 65 ksi

Calculate the required strength, not considering second-order effects

LRFD ASD
Pu = 1.2(5.00 kips) + 1.6(15.0 kips) Pa = 5.00 kips + 15.0 kips
\= 30.0 kips = 20.0 kips
Mux = 1.2(15.0 kip-ft) + 1.6(45.0 kip-ft) Max = 15.0 kip-ft + 45.0 kip-ft
\= 90.0 kip-ft = 60.0 kip-ft
Muy = 1.2(2.00 kip-ft) + 1.6(6.00 kip-ft) May = 2.00 kip-ft + 6.00 kip-ft
\= 12.0 kip-ft = 8.00 kip-ft

Try a W10×33

Geometric Properties:
W10×33 A = 9.71 in.2 Sx= 35.0 in.3 Zx = 38.8 in.3 Ix = 171 in.4 Manual
Sy= 9.20 in.3 Zy = 14.0 in.3 Iy = 36.6 in.4 Table 1-1
Lp = 6.85 ft Lr = 12.8 ft Table 3-1

Calculate the available axial strength
Commentary
For a pinned-pinned condition, K = 1.0. Table
C-C2.2
Since KLx = KLy = 14.0 ft and rx > ry, the y-y axis will govern.

LRFD ASD Manual
Pc = φcPn = 253 kips Pc = Pn/Ωc = 168 kips Table 4-1

<!-- p. 152 -->

H-10

Calculate the required flexural strengths including second order amplification

Use “Amplified First-Order Elastic Analysis” procedure from Section C2.1b. Since the
member is not subject to sidesway, only P-δ amplifiers need to be added.

C m
B1 = Eqn. C2-2 1 −α Pr / Pe1

Cm = 1.0

X-X axis flexural magnifier

4 29,000 ksi )(171in. ) Eqn. C2-5 π 2 EI x π 2 (
Pe1 = 2 = 2 = 1730 kips
( K1 Lx ) ( (1.0 )(14.0ft )(12in./ft ) )

LRFD ASD
α = 1.0 α = 1.6
1.0 1.0
B1 = = 1.02 B1 = = 1.02 Eqn. C2-2 1 − 1.0 ( 30.0 kips /1730 kips ) 1 − 1.6 ( 20.0 kips /1730 kips )

Mux = 1.02(90.0 kip-ft) = 91.8 kip-ft Max = 1.02(60.0 kip-ft) = 61.2 kip-ft

Y-Y axis flexural magnifier

4 π 2 EI y π 2 ( 29,000 ksi )( 36.6in. )
Pe1 = 2 = 2 = 371 kips Eqn. C2-5
( K1 L y ) ( (1.0 )(14.0ft )(12in./ft ) )

LRFD ASD
α = 1.0 α = 1.6
1.0 1.0
B1 = = 1.09 B1 = = 1.09 Eqn. C2-2 1 − 1.0 ( 30.0 kips /371kips ) 1 − 1.6 ( 20.0 kips /371kips )

Muy = 1.09(12.0 kip-ft) = 13.1 kip-ft May = 1.09 (8.00 kip-ft) = 8.76 kip-ft

Calculate the nominal bending strength about the x-x axis

Yielding limit state

Mnx = Mp = FyZx = 50 ksi(38.8 in.3) = 1940 kip-in or 162 kip-ft Eqn. F2-1

Lateral-torsional buckling limit state

Since Lp \< Lb \< Lr, Equation F2-2 applies

From Manual Table 3-1, Cb = 1.14 Manual
Table 3-1

<!-- p. 153 -->

H-11

⎡ ⎛ Lb - L p ⎞ ⎤
⎥ ⎟ M Mp Eqn. F2-2Mnx = Cb ⎢ M p - ( M p -0.7 Fy S x ) ⎜⎜ ⎟ ⎝ Lr - L p ⎠ ⎢⎣ ⎥⎦
⎡ 3 ⎛ 14.0ft - 6.85ft ⎞ ⎤Mnx = 1.14 ⎢1940 kip-in. - ( 1940 kip-in. - 0.7 ( 50 ksi )( 35.0 in. ) ) ⎜ ⎟ ⎥
⎣ ⎝ 21.8 ft - 6.85ft ⎠ ⎦
\= 1820 kip-in. M 1940 kip-in., therefore use:

Mnx = 1820 kip-in. or 152 kip-ft controls

Local buckling limit state

Per Manual Table 1-1, the member is compact for Fy = 50 ksi, so the local buckling limit state Manual
does not apply Table 1-1

Calculate the nominal bending strength about the y-y axis Section F6.2

Since a W10×33 has compact flanges, only the yielding limit state applies.

Mny = Mp = FyZy M 1.6FySy Eqn. F6-1
\= 50 ksi(14.0 in.3) M 1.6(50 ksi)(9.20 in.3)
\= 700 kip-in \< 736 kip-in., therefore

Use Mny = 700 kip-in. or 58.3 kip-ft

LRFD ASD
φb = 0.90 Ωb = 1.67 Section F2
Mcx = φbMnx = 0.90(152 kip-ft) = 137 kip-ft Mcx = Mnx/Ωb = 152 kip-ft/1.67 = 91.0 kip-ft
Mcy = φbMny = 0.90(58.3 kip-ft) = 52.5 kip-ft Mcy = Mny/Ωb = 58.3 kip-ft/1.67 = 34.9 kip-ft

Check limit for Equation H1-1a

LRFD ASD
Pr Pu 30.0 kips Pr Pa 20.0 kips = = = 0.119, therefore, = = = 0.119, therefore Section H1.1 Pc φ c Pn 253 kips Pc Pn / Ω c 168 kips
use Specification Equation H1.1b use Specification Equation H1.1b
⎛ ⎛ Eqn. H1.1b M ry ⎞ M ry ⎞ M rx M rx Pr Pr + + + + ⎜ ⎟ M 1.0 ⎜ ⎟ M 1.0 ⎜ ⎟ ⎜ ⎟ 2 Pc ⎝ M cx M cy ⎠ 2 Pc ⎝ M cx M cy ⎠
30.0 kips ⎛ 91.8 kip-ft 13.1 kip-ft ⎞ 20.0 kips ⎛ 61.2 kip-ft 8.76 kip-ft ⎞
\+ ⎜ + ⎟ + ⎜ + ⎟
2(253 kips) ⎝ 137 kip-ft 52.5 kip-ft ⎠ 2(168 kips) ⎝ 91.0 kip-ft 34.9 kip-ft ⎠

0.0593 + 0.920 = 0.979 M 1.0 o.k. 0.0595 + 0.924 = 0.983 M 1.0 o.k.

<!-- p. 154 -->

H-12

Example H.5a Rectangular HSS Torsional Strength
Given:
Determine the available torsional strength of an ASTM A500 Gr. B HSS6×4×4.

Solution:

Material Properties:
ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Manual
Table 2-3
Geometric properties:
h b Manual
HSS6×4×4 = 22.8 = 14.2 t = 0.233 in. Table 1-11 t t

Evaluate wall slenderness to determine the appropriate critical stress equation

h b h
\> , therefore, governs.
t t t
h E
≤ 2.45
t Fy

29,000 ksi
22.8 ≤ 2.45 = 61.5 therefore, use Eqn. H3-3
46 ksi

Fcr = 0.6 Fy = 0.6(46 ksi) = 27.6 ksi Eqn. H3-3

Calculate the nominal torsional strength

Tn = FcrC = 27.6 ksi (10.1 in.3) = 278 kip-in. Eqn. H3-1

C = 10.1 Manual
Table 1-11
Calculate the available torsional strength

LRFD ASD
φT = 0.90 ΩT = 1.67 Section H3.1
φTTn = 0.90(278 kip-in.) = 250 kip-in. Tn/ΩΤ = 278 kip-in./1.67 = 166 kip-in.

Note: For more complete guidance on design for torsion, see AISC Design Guide 9, Torsional
Analysis of Structural Steel Members.

<!-- p. 155 -->

H-13

Example H.5b Round HSS Torsional Strength

Given:
Determine the available torsional strength of an ASTM A500 Gr. B HSS5.000×0.250 that is
14 ft long.

Solution:

Material Properties: Manual
ASTM A500 Gr. B Fy = 42 ksi Fu = 58 ksi Table 2-3

Geometric properties:
D Manual
HSS5.000×0.250 = 21.5 t = 0.233 in. D = 5.00 in.
t Table 1-13

Calculate the critical stress as the larger of

1.23E 1.23 ( 29,000 ksi )
Fcr = 5 = 5 = 133 ksi Eqn. H3-2a
4 L ⎛ D ⎞ 4 14.0 ft (12 in./ft) ( 21.5 ) ⎜ ⎟ 5.00 in. D ⎝ t ⎠
and
0.60 E 0.60 ( 29,000 ksi ) Eqn. H3-2b Fcr = 3 = 3 = 175 ksi
2 ⎛ D ⎞ 2 ( 21.5 )
⎜ ⎟
⎝ t ⎠

However, Fcr shall not exceed 0.60 Fy = 0.60(42 ksi) = 25.2 ksi, therefore, Section H3.1

Fcr = 25.2 ksi

Calculate the torsional shear constant
Manual
C = 7.95 in.3 Table 1-13

Calculate the nominal torsional strength

Tn = FcrC = 25.2 ksi (7.95 in.3) = 200 kip-in. Eqn. H3-1

Calculate the available torsional strength

LRFD ASD
φT = 0.90 ΩT = 1.67 Section H3.1
φTTn = 0.90(200 kip-in.) = 180 kip-in. Tn/ΩT = 200 kip-in./1.67 = 120 kip-in.

Note: For more complete guidance on design for torsion, see AISC Design Guide 9, Torsional
Analysis of Structural Steel Members.

<!-- p. 156 -->

H-14

Example H.5c HSS Combined Torsional and Flexural Strength

Given:
Verify the strength of an ASTM A500 Gr. B HSS6×4×1/4 loaded as shown. The beam is
simply supported with torsionally fixed ends.

wD = 0.460 kip/ft applied 6 in. off centerline
wL = 1.38 kip/ft applied 6 in. off centerline

8.00 ft

Solution:

Material Properties: Manual
ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Table 2-3

Geometric properties:
h b
HSS 6×4×4 = 22.8 = 14.2 t = 0.233 in. Zx = 8.53 in.3 Manual
t t Table 1-11

Calculate the required strengths

LRFD ASD
wu = 1.2(0.460 kip/ft) + 1.6(1.38 kip/ft) wa = 0.460 kip/ft + 1.38 kip/ft
\= 2.76 kip/ft = 1.84 kip/ft

wu l wa l Vr = Vu = Vr = Va =
2 2
2.76 kip/ft ( 8.00 ft ) 1.84 kip/ft ( 8.00 ft ) = = 11.0 kips = = 7.36 kips
2 2

wu l 2 wa l 2 Mr = Mu = Mr = Ma =
8 8
2.76 kip/ft ( 8.00 ft ) 2 (12 in./ft ) 1.84 kip/ft ( 8.00 ft ) 2 (12 in./ft ) = =
8 8
\= 265 kip-in. = 177 kip-in.

wu le wa le Tr = Tu = Tr = Ta =
2 2
2.76 kip/ft ( 8.00 ft )( 6.00in. ) 1.84 kip/ft ( 8.00 ft ) (6.00 in.) = =
2 2
\= 66.2 kip-in. = 44.2 kip-in.

<!-- p. 157 -->

H-15

Calculate the nominal shear strength

h = 6.00 in.2 - 3(0.233 in.) = 5.30 in.
Section G5
Aw = 2ht = 2(5.30 in.)(0.233 in.) = 2.47 in.2

kv= 5

Calculate the web shear coefficient

h k v E 5(29,000ksi) = 22.8 ≤ 1.10 = 1.10 = 61.7 therefore, Cv = 1.0 Eqn. G2-3
t w Fy 46 ksi

Vn = 0.6FyAwCv = 0.6(46 ksi)(2.47 in.2)(1.0) = 68.2 kips Eqn. G2-1

Calculate the available shear strength

LRFD ASD
φv = 0.90 Ω v = 1.67 Section G1
Vc = φ vVn = 0.90(68.2 kips) = 61.4 kips Vc = Vn/Ω v = 68.2 kips/1.67 = 40.8 kips

Calculate the nominal flexural strength Section F7

Flexural yielding limit state

Mn = Mp = FyZx = 46 ksi(8.53 in.3) = 392 kip-in. Eqn. F7-1

Flange local buckling limit state
b E
\= 14.2 \< 1.12 = 28.1 therefore the flange is compact and the flange local buckling Table B4.1
t Fy Case 12
limit state does not apply.

Web local buckling limit state
h E
\= 22.8 \< 2.42 = 60.8 therefore the the web is compact and the web local buckling Table B4.1
t Fy Case 13
limit state does not apply.

Therefore Mn = 392 kip-in., controlled by the flexural yielding limit state.

Calculate the available flexural strength

LRFD ASD
φb = 0.90 Ω b = 1.67 Section F1
Mc = φ bMn = 0.90(392 kip-in.) = 353 kip-in. Mc = M n /Ω b = 392 kip-in./1.67 =235 kip-in.

Take the available torsional strength from Example H.5a

Tc = φTTn = 0.90(278 kip-in.) = 250 kip-in. Tc = Tn/ΩΤ = 278 kip-in./1.67 = 166 kip-in. Ex. H.5a

<!-- p. 158 -->

H-16

Check combined strength

LRFD ASD
⎛ Pr M r ⎞ ⎛ Vr Tr ⎞ 2 ⎛ Pr M r ⎞ ⎛ Vr Tr ⎞ 2 ⎜ + ⎟ + ⎜ + ⎟ ≤ 1.0 ⎜ + ⎟ + ⎜ + ⎟ ≤ 1.0 Eqn. H3-6
⎝ Pc M c ⎠ ⎝ Vc Tc ⎠ ⎝ Pc M c ⎠ ⎝ Vc Tc ⎠

⎛ 265kip-in. ⎞ ⎛ 177 kip-in. ⎞
⎜ 0 + ⎟ ⎜ 0 + ⎟
⎝ 353 kip-in. ⎠ ⎝ 235 kip-in. ⎠
⎛ 11.0 kips 66.2 kip-in. ⎞ 2 ⎛ 7.36 kips 44.2 kip-in. ⎞ 2
\+ ⎜ + ⎟ + ⎜ + ⎟
⎝ 61.4 kips 250 kip-in. ⎠ ⎝ 40.8 kips 166 kip-in. ⎠

\=0.948 \< 1.0 o.k. = 0.953 \< 1.0 o.k.

<!-- p. 159 -->

H-17

Example H.6 W-Shape Torsional Strength.

This design example is taken from AISC Design Guide 9 – Torsion Analysis of Structural Steel
Members. As shown below, a W10×49 spans 15 ft (180 in.) and supports concentrated loads
at midspan that act at a 6 in. eccentricity with respect to the shear center. Determine the
stresses on the cross section and the adequacy of the section to support the loads.

Given:

PD = 2.50 kips applied 6 in. off centerline
PL = 7.50 kips applied 6 in. off centerline

7.5 ft

15 ft

Beam Loading Diagram

The end conditions are assumed to be flexurally and torsionally pinned. The eccentric load
can be resolved into a torsional moment and a load applied through the shear center.

Solution:

Material Properties:
Manual ASTM A992 Fy = 50 ksi Fu = 65 ksi
Table 2-3
Geometric Properties:
Manual W10×49 Ix = 272 in.4 Sx= 54.6 in.3 tf = 0.560 in. tw = 0.340 in.
Table 1-1 J = 1.39 in.4 Cw = 2070 in.6

Additional Torsional Properties:
Design W10×49 Sw1= 33.0 in.4 a = 62.1 in. Wno = 23.6 in.2 Guide 9 Qf = 13.0 in.3 Qw = 30.2 in.3 Appendix A

Calculate the required strength

LRFD ASD
Pu = 1.2(2.50 kips) + 1.6(7.50 kips) Pa = 2.50 kips + 7.50 kips
\= 15.0 kips = 10.0 kips
uP 15.0 kips aP 10.0 kips Vu = = = 7.50 kips Va = = = 5.00 kips
2 2 2 2
uP l 15.0 kips(15.0 ft)(12 in./ft) aP l 10.0 kips(15.0 ft)(12 in./ft) Mu = = Ma = =
4 4 4 4
\= 675 kip-in. = 450 kip-in.
Tu = Pue = 15.0 kips(6.00 in.) = 90.0 kip-in. Ta = Pae = 10.0 kips(6.00 in.) = 60.0 kip-in.

<!-- p. 160 -->

H-18

Calculate the normal and shear stresses from flexure

LRFD ASD
M u 675 kip-in. M a 450 kip-in. Design
σ bxu = = 3 = 12.4 ksi σ bxa = = 3 = 8.24 ksi Guide 9 S x 54.6 in. S x 54.6 in. Eqn.4.5
(compression at top, tension at bottom) (compression at top, tension at bottom)

3 Design 5.00 kips ( 30.2 in. ) Vu Qw 7.5 kips ( 30.2 in.3 ) Va Qw
τ bwu = = 4 = 2.45 ksi τ bwa = = 4 = 1.63 ksi Guide 9 I x t w 272 in. ( 0.340 in. ) I x t w 272 in. ( 0.340 in. ) Eqn. 4.6
3 3 Vu Q f 7.5 kips (13.0 in. ) Va Q f 5.00 kips (13.0 in. )
τ bf u = = 4 = 0.640 ksi τ bfa = = 4 = 0.427 ksi Design I x t f 272 in. ( 0.560 in. ) I x t f 272 in. ( 0.560 in. ) Guide 9
Eqn. 4.6

Calculate torsional stresses

The following functions are taken from AISC’s Design Guide 9 – Torsion Analysis of
Structural Steel Members Appendix B, Case 3, with α = 0.5. Design
Guide 9
l 180 in. Appendix B
\= = 2.90 Case 3, a 62.1 in.
α = 0.5

At midspan (z/l = 0.5)

Using the graphs for θ, θ", θ' and θ"', select values Design
Guide 9
⎛ GJ ⎞⎛⎞1 Tr l For θ; θ × ⎜ ⎝ Tr ⎟⎝⎠⎠ ⎜⎟l = +0.09 Solve for θ = +0.09 GJ AppendixCase 3, B
⎛ GJ ⎞ Tr l α = 0.5 For θ"; θ '' × a = -0.44 Solve for θ" = -0.44 ⎜ ⎟ ⎝ Tr ⎠ GJa
⎛ GJ ⎞
For θ' ; θ ' × = 0 Therefore θ ' = 0 ⎜ ⎟ ⎝ Tr ⎠
⎛ GJ ⎞ 2 Tr l For θ"'; θ ''' × ⎜ ⎟ a = -0.50 Solve for θ ''' = -0.50 2 ⎝ Tr ⎠ GJa

At the support (z/l = 0)

⎛ GJ ⎞⎛⎞1 Design For θ; θ × ⎜ ⎝ Tr ⎟⎝⎠⎠ ⎜⎟l = 0 Therefore θ = 0 Guide 9 Appendix B
⎛ GJ ⎞ Case 3,
For θ"; θ '' × a = 0 Therefore θ ''= 0 ⎜ ⎟ α = 0.5 ⎝ Tr ⎠
⎛ GJ ⎞ Tr For θ'; θ ' × = +0.28 Solve for θ ' = +0.28 ⎜ ⎟ ⎝ Tr ⎠ GJ
⎛ GJ ⎞ 2 Tr l For θ"'; θ ''' × ⎜ ⎟ a = -0.22 Solve for θ '''= -0.22 2 ⎝ Tr ⎠ GJa
In the above calculations note that the applied torque is negative with the sign convention
used.

<!-- p. 161 -->

H-19

rTCalculate for use below
GJ

LRFD ASD
uT -90.0 kip-in. aT -60.0 kip-in. = =
4 4 GJ (11,200 ksi )(1.39 in. ) GJ (11,200 ksi )(1.39 in. )
\= -5.78 x 10 -3 rad/in. = -3.85 x 10 -3 rad/in.

Calculate the shear stresses due to pure torsion
Design
τ t = Gt θ ' Guide 9
Eqn. 4.1

LRFD ASD
At midspan At midspan
θ ' = 0; τ ut = 0 θ ' = 0; τ at = 0

At the support, for the web; At the support, for the web;
Design ⎛ −5.78rad ⎞ ⎛ −3.85 rad ⎞ Guide 9 τut = 11,200 ksi ( 0.340 in. )( 0.28 ) ⎜ 3 ⎟ τ at = 11,200 ksi(0.340 in.)(0.28) ⎜ 3 ⎟
⎝ 10 in. ⎠ ⎝ 10 in. ⎠ Eqn. 4.1
\= -6.16 ksi = -4.11 ksi

At the support, for the flange; At the support, for the flange;
⎛ −5.78rad ⎞ ⎛ −3.85rad ⎞ Design
τ ut = 11,200 ksi(0.560 in.)(0.28) ⎜ 3 ⎟ τ at = 11,200 ksi(0.560 in.)(0.28) ⎜ 3 ⎟ Guide 9 ⎝ 10 in. ⎠ ⎝ 10 in. ⎠ Eqn. 4.1
\= -10.2 ksi = -6.76 ksi

Calculate the shear stresses due to warping

− ES wl θ"' Design
τ t = Guide 9
t f Eqn. 4.2a

LRFD ASD
At midspan At midspan
4 4 −29,000ksi ( 33.0in. ) ⎡ −0.50 ( −5.78rad ) ⎤ −29,000ksi ( 33.0in. ) ⎡ −0.50 ( −3.85rad ) ⎤
τuw = ⎢ 2 3 ⎥ τaw = ⎢ 2 3 ⎥ Design 0.560in. ⎢ Guide 9 ⎣ ( 62.1in. ) 10 ⎥⎦ 0.560in. ⎢⎣ ( 62.1in. ) 10 ⎥⎦
Eqn. 4.2a
\= -1.28 ksi = -0.853 ksi

At the support At the support
4 4 −29,000ksi ( 33.0in. ) ⎡ −0.22 ( −5.78rad ) ⎤ −29,000ksi ( 33.0in. ) ⎡ −0.22 ( −3.85rad ) ⎤ Design ⎢ ⎥ ⎢ ⎥ τuw = τaw = Guide 9 3 3 0.560in. ⎢ ⎥ 0.560in. ⎢ ⎥ 62.1in. ) 2 10 62.1in. ) 2 10 ⎣ ( ⎦ Eqn. 4.2a ⎣ ( ⎦
\= -0.564ksi = -0.375 ksi

<!-- p. 162 -->

H-20

Calculate the normal stresses due to warping
Design
σ w = EWno θ" Guide 9
Eqn. 4.3a

LRFD ASD
At midspan At midspan
2 ⎡ −0.44 ( −5.78rad ) ⎤ 2 ⎡ −0.44 ( −3.85rad ) ⎤ Design σuw = 29,000 ksi ( 23.6 in. ) ⎢ 3 ⎥ σ aw = 29,000 ksi ( 23.6in. ) ⎢ 3 ⎥ Guide 9 ⎢⎣ ( 62.1 in. ) 10 ⎥⎦ ⎢⎣ ( 62.1 in. ) 10 ⎥⎦ Eqn. 4.3a
\= 28.0 ksi = 18.7 ksi

At the support At the support
Since θ" = 0, σ uw = 0 Since θ" = 0, σ aw = 0

Calculate the combined stresses

The summarized stresses are as follows:

Summary of Stresses (ksi)
LFRD ASD
Location Normal Stresses Shear Stresses Normal Stresses Shear Stresses
σ uw σ ub f un τ ut τ uw τ ub f uv σ aw σ ab f an τ at τ aw τ ab f av
Midspan
Flange |28.1 |12.4 |40.4 0 -1.28 |0.640 -1.92 |18.7 |8.24 |26.9 0 -0.853 |0.427 -1.28
Web ---- ---- ---- 0 ---- |2.45 -2.45 ---- ---- ---- 0 ---- |1.63 |1.63
Support
Flange 0 0 0 -10.2 -0.564 |0.640 -11.4 0 0 0 -6.76 -0.375 |0.427 -7.56
Web ---- ---- ---- -6.16 ---- |2.45 -8.61 ---- ---- ---- -4.11 ---- |1.63 -5.74
Maximum |40.4 -11.4 |26.9 -7.56

LRFD ASD
The maximum normal stress due to flexure The maximum normal stress due to flexure
and torsion occurs at the edge of the flange at and torsion occurs at the edge of the flange at
midspan and is equal to 40.4 ksi. midspan and is equal to 26.9 ksi.

The maximum shear stress due to flexure and The maximum shear stress due to flexure and
torsion occurs in the middle of the flange at torsion occurs in the middle of the flange at
the support and is equal to 11.4 ksi. the support and is equal to 7.56 ksi.

Calculate the available strength

LRFD ASD
φT = 0.90 ΩT = 1.67 Section H3.3

Normal Stresses Normal Stresses

Yielding limit state Yielding limit state

Fn = Fy = 50 ksi controls Fn = Fy = 50 ksi controls Eqn. H3-7

Lateral-torsional buckling limit state Lateral-torsional buckling limit state Manual
Table 3-1
Cb = 1.32 Cb = 1.32 Case 1

<!-- p. 163 -->

H-21

Compute Fn using values from Table 3-10. Compute Fn using values from Table 3-10. Manual
with Lb = 15.0 ft and Cb = 1.0 with Lb = 15.0 ft and Cb = 1.0 Table 3-10

φbMn = 206 kip-ft Mn /Ωb = 138 kip-ft

Fn = Fcr Fn = Fcr Eqn. H3-9
φ b M n M n / Ω b = Cb = Cb Ω b
φ b S x S x
206 kip-ft ⎛ 12in. ⎞ 138kip-ft ⎛ 12in. ⎞
1.67 = 1.32 3 ⎜ ⎟ = 1.32 ( 3 ⎜ ⎟ ft ⎠ 0.90 ( 54.6in. ) ⎝ ft ⎠ )( 54.6in. ) ⎝
\= 66.4 ksi > 50 ksi does not control = 66.9 ksi > 50 ksi does not control

φTFn = 0.9(50 ksi) = 45.0 ksi > 40.4 ksi o.k. Fn /ΩT = 50 ksi/1.67 = 30.0 ksi > 26.9 ksi o.k.

Shear yielding limit state Shear yielding limit state
Eqn. H3-8
Fn = 0.6Fy Fn = 0.6Fy

Design shear strength Allowable shear strength

φTFn = 0.90(0.6)(50 ksi) Fn /ΩT = (0.6)(50 ksi)/1.67
\= 27.0 ksi > 11.4 ksi o.k. = 18.0 ksi > 7.56 ksi o.k.

Calculate the maximum rotation at service load

The maximum rotation occurs at midspan. The service-load torque is:
Design
T = Pe = − ( 2.50 kips+7.50 kips )( 6.00 in. ) = -60.0 kip-in. Guide 9
Eqn. 4.1

The maximum rotation is:

Tl 0.09 ( −60.0 kip-in. )(180 in. )θ = + 0.9 = = −0.624 rads = − 3.58 degrees
4 GJ 11,200 ksi (1.39 in. )

<!-- p. 164 -->

I-1

CHAPTER I
DESIGN OF COMPOSITE MEMBERS

I1. GENERAL PROVISIONS

The available strength of composite sections may be calculated by one of two methods - the plastic stress distribution
method or the strain-compatibility method. The composite design tables in the Steel Construction Manual are based
on the plastic stress distribution method.

I2. AXIAL MEMBERS

Generally, the available compressive strength of a composite member is based on a summation of the strengths of all
of the components of the column. The Specification contains several requirements to ensure that the steel and
concrete components work together.

For tension members, the concrete tensile strength is ignored and only the strength of the steel member and properly
connected reinforcing is permitted to be used in the calculation of available tensile strength.

Because of concerns about the deformation compatibility of steel and concrete in resisting shear, either the steel or
the reinforced concrete, but not both, are permitted to be used in the calculation of available shear strength. Whether
the composite column is an encased column or a filled column, it is important to consider the load path within the
composite member, and to provide shear transfer mechanisms and appropriate top and bottom details.

The design of encased composite compression and tension members is presented in Examples I-3 and I-4. There are
no tables in the Manual for the design of these members.

The design of filled composite compression and tension members is presented in Examples I-2 and I-5. The Manual
includes tables for the design of filled composite members in compression.

I3. FLEXURAL MEMBERS

Because a plastic stress distribution is used for both LRFD and ASD designs, the flexural strength of composite
beams is generally greater than that of former ASD designs. Shear connectors, in many cases, have lower horizontal
shear strength than was permitted in past LRFD specifications. Designers are encouraged to read the discussion on
this subject in Commentary Chapter I. The design of a typical composite beam member is illustrated in
Example I-1.

I4. COMBINED AXIAL FORCE AND FLEXURE

Design for combined axial force and flexure may be accomplished in any of the three methods outlined in the
Commentary. Example I-7 illustrates the plastic-distribution method.

To assist in developing this curve, a series of equations is provided in Figure I-1. These equations define selected
points on the interaction curve, without consideration of slenderness effects. Figures I-1a through I-1d outline
specific cases, and the applicability of the equations to a cross-section that differs should be carefully considered. As
an example, the equations in Figure I-1a are appropriate for the case of side bars located at the centerline, but not for
other side bar locations. In contrast, these equations are appropriate for any amount of reinforcing at the extreme
reinforcing bar location. In Figure I-1b, the equations are appropriate only for the case of 4 reinforcing bars at the
corners of the encased section. When design cases deviate from those presented the appropriate interaction equations
can be derived from first principles.

<!-- p. 165 -->

PLASTIC CAPACITIES FOR RECTANGULAR,
tt
ENCASED W-SHAPES BENT ABOUT THE X-X AXIS

Section Stress Distribution Point Defining Equations

P = A F + A F + 0.85 f , A
A s y sr yr c c
M = 0
A
A As = area of steel shape
A = area of all continuous reinforcing bars
sr
A = h h − A − A
c 1 2 s sr

P = 0.85 f , A
C c c
C M C = M B

0.85 fc , Ac
D = 2 (A) P
M D = Zs Fy + Zr Fyr + 1 2 Zc ( 0.85 fc , )
Zs = full x-axis plastic section modulus of steel shape
D Asrs = area of continuous reinforcing bars at the centerline
⎛ h ⎞
2 − c ⎟ Zr = ( Asr − Asrs ) ⎜ ⎝ 2 ⎠
h h2
Zc = 142 − Z s − Zr

P = 0 B
, M F 0.85 f = M − Z D sn y c B − 1 2 Zcn ( )
(C) Z = h h 2 − Z
cn 1 n sn

For h below the flange ⎛ n ⎝ hn ≤ d2 − t f ⎞⎠

, A 0.85 f + A − 2 F c ( Ac srs ) yr srs
h = n ⎤ h t 2 ⎡ − t + 2 F w ) y w 1 ⎢⎣ 0.85 fc , ( ⎥⎦
Z = t h2 sn w n

d For h within the flange 2 n ( − t f \< hn ≤ d 2 )
B
, (D) 0.85 f A A A + A − 2 F − 2 F
c c s s yr srs ( − db f + Asrs ) y ( − db f )
h =
n ⎤ h 2 ⎡ + 2 F b f y 1 − b f ) ⎢⎣ 0.85 fc , ( ⎥⎦
d d Z = Z − h + h − b f ( sn s n )( n ) 2 2

For h > d 2 ) n above the flange ( hn

, 0.85 f A A + A + A − 2 F − 2 F c ( Ac s srs ) y s yr srs
h =
n , 2 0.85 f h ( c 1 )
Z = Z = full x-axis plastic section modulus of steel shape sn sx
(B)

Figure I-1a. W-Shapes, Strong-Axis Anchor Points.

<!-- p. 166 -->

PLASTIC CAPACITIES FOR RECTANGULAR,
ENCASED W-SHAPES BENT ABOUT THE Y-Y AXIS

Section Stress Distribution Point Defining Equations

P = A F + A F + 0.85 f , A
A s y sr yr c c
M = 0
A
A As = area of steel shape
A = area of continuous reinforcing bars sr
A = h h − A − A
c 1 2 s sr

, ⎡ h1 Asr ⎤ ⎢ ⎥ P F 0.85 f A h = A + − +
2 E s y c ( c ) − b f ) 2 ( 2 ⎢⎣ ⎥⎦
M = M − Z F − 1 Z 0.85 f , E D sE y 2 cE ( c )
E Z = Z = full y-axis plastic section modulus of steel shape
sE sy
h b2
1 f
(A) ZcE = 4 − Z sE

P = 0.85 f , A
C MC = M c c
C B

0.85 f , A
P = c c
D 2
M = Z F + Z F + 1 Z 0.85 f , D s y r sr 2 c ( c )
Z = full y-axis plastic section modulus of steel shape
(E) s
D ⎛ h2 ⎞
Z = A
r sr ⎜⎜⎝ 2 − c ⎟⎟⎠
h h2
Z = 1 2 − Z − Z
c 4 s r

P = 0
B
M = M − Z F − 1 Z 0.85 f , B D sn y 2 cn ( c )

h h 2 − Z
1 (C) Zcn = n sn

⎛ b f ⎞
For h below the flange ⎜ h ≤ ⎟
n ⎜⎝ n 2 ⎟⎠

, 0.85 f A A + A − 2 F
c c s s ( − 2 t f b f ) y ( − 2 t f b f )
h =
n , ⎤ 2 ⎡ h 0.85 f
1 c − 2 t f ) ⎢⎣ 4 t f Fy + ( ⎥⎦
b B ⎛ b f ⎞⎛ f ⎞
⎜ ⎟⎜ ⎟ Z − 2 t + h − h
f (D) Z sn = s n n ⎜⎝ 2 ⎟⎜⎠⎝ 2 ⎟⎠

⎛ b f ⎞
For h above the flange ⎜ h > ⎟
n ⎜⎝ n 2 ⎟⎠
, 0.85 f A + A − 2 F
c ( Ac s ) y s
h =
n 2 ⎡ 0.85 f , h ⎤ ⎢⎣ c 1 ⎥⎦
(B) Z sn = Z sy = full y-axis plastic section modulus of steel shape

Figure I-1b. W-Shapes, Weak-Axis Anchor Points

<!-- p. 167 -->

PLASTIC CAPACITIES FOR COMPOSITE,
FILLED HSS BENT ABOUT THE X-X OR Y-Y AXIS

Section Stress Distribution Point Defining Equations

P = A F + A 0.85 f , A s y c ( c )
M = 0
A
A = area of steel shape
A s
A = h h − 0.858 r 2
c 1 2 i

(A)

P = A 0.85 f , C c ( c )
C M C = M B

(C)

0.85 f , A
P = c c
D 2
M = Z F + 1 Z 0.85 f , D s y 2 c ( c )
D Z = full y-axis plastic section modulus of steel shape
s
h h2
Z = 1 2 − 0.192 r 3
c 4 i
(D)

P = 0
B
M = M − Z F − 1 Z 0.85 f , B D sn y 2 cn ( c )
Z = 2 t h2 sn w n
Z = h h2
B cn 1 n
0.85 f , A h
h = c c ≤ 2
n 2 ⎡ 0.85 f , h + 4 t F ⎤ 2 ⎢⎣ c 1 w y ⎥⎦

(B)

Figure I-1c. Filled Rectangular or Square HSS, Strong- or Weak Axis Anchor Points

<!-- p. 168 -->

PLASTIC CAPACITIES FOR COMPOSITE,
FILLED ROUND HSS BENT ABOUT ANY AXIS

Section Stress Distribution Point Defining Equations

P = A F + 0.85 f , A *
A s y c c
M = 0
A
A = π( dt − t 2 ) A s
πh2 A =
c 4

(A)
P = 0.85 f , A
C MC = M c c
C B

0.85 f , A
(C) P = c c
D 2
M = Z F + 1 Z 0.85 f , D s y 2 c ( c )
D d 3 Z = plastic section modulus of steel shape = − Z
s 6 c
h3 Z =
c 6

P = 0
B
M = Z F − 1 Z 0.85 f , B sB y 2 cB ( c )
θ d 3 sin3 ( 2 )
(D) Z sB = 6 − ZcB
θ h3 sin3 ( 2 )
Z =
cB 6
0.0260 K − 2 K
θ = c s +
c B 0.0848 K
K f A + 2 K + 0.857 K ( 0.0260 Kc 2 , s ) c s c c
(in rads)
0.0848 K
c
K = f , h2
c c
d ⎛ − t ⎞ K = F
s y ⎜⎝ ⎟⎠ t ("thin" HSS wall assumed) 2
h ⎛ π − θ⎞ h h =
n 2 sin ⎜⎝ 2 ⎟⎠ ≤ 2 (not used, for reference only) (B)

\* PA = As Fy +0.95 f c' Ac is permitted to be used when the composite column is loaded only in axial compression.

Figure I-1d. Filled Round HSS Anchor Points

<!-- p. 169 -->

I-6

Example I-1 Composite Beam Design

Given:

A series of 45-ft. span composite beams at 10 ft. o/c are carrying the loads shown below. The beams are ASTM
A992 and are unshored. The concrete has f′c = 4 ksi. Design a typical floor beam with 3 in. 18 gage composite deck,
and 4½ in. normal weight concrete above the deck, for fire protection and mass. Select an appropriate beam and
determine the required number of shear studs.

Solution:

Material Properties:
Concrete f′c = 4 ksi

ManualBeam Fy = 50 ksi Fu = 65 ksi
Table 2-3

Loads:
Dead load:
Slab = 0.075 kip/ft2
Beam weight = 0.008 kip/ft2 (assumed)
Miscellaneous = 0.010 kip/ft2 (ceiling etc.)

Live load:
Non-reduced = 0.10 kips/ft2

Since each beam is spaced at 10 ft. o.c.

Total dead load = 0.093 kip/ft2(10 ft.) = 0.93 kips/ft.
Total live load = 0.10 kip/ft2(10ft.) = 1.00 kips/ft.

Construction dead load (unshored) = 0.083 kip/ft2(10 ft) = 0.83 kips/ft
Construction live load (unshored) = 0.020 kip/ft2(10 ft) = 0.20 kips/ft

<!-- p. 170 -->

I-7

Determine the required flexural strength
LRFD ASD
wu = 1.2(0.93 kip/ft) + 1.6(1.0 kip/ft) wa = 0.93 kip/ft + 1.0 kip/ft
\= 2.72 kip/ft = 1.93 kip/ft
2.72 kip/ft(45 ft) 2 1.93 kip/ft(45 ft) 2
Mu = = 687 kip-ft. Ma = = 489 kip-ft.
8 8

Use Tables 3-19, 3-20 and 3-21 from the Manual to select an appropriate member

Determine beff Section
I.3.1.1a
The effective width of the concrete slab is the sum of the effective widths for each side of the
beam centerline, which shall not exceed:

(1) one-eighth of the beam span, center to center of supports
45 ft. ( 2 ) = 11.3 ft.
8

(2) one-half the distance to center-line of the adjacent beam
10 ft. ( 2 ) = 10.0 ft. Controls
2

(3) the distance to the edge of the slab
Not applicable

Calculate the moment arm for the concrete force measured from the top of the steel shape, Y2.

Assume a = 1.0 in. (Some assumption must be made to start the design process. An assumption
of 1.0 in. has proven to be a reasonable starting point in many design problems.)

Y2 = tslab – a/2 = 7.5 – ½ = 7.0 in.

Enter Manual Table 3-19 with the required strength and Y2=7.0 in. Select a beam and neutral Manual Table
axis location that indicates sufficient available strength. 3-19

Select a W21×50 as a trial beam.

When PNA location 5 (BFL), this composite shape has an available strength of:
LRFD ASD
φbMn= 770 kip-ft > 687 kip-ft o.k. Mn/Ωb = 512 kip-ft > 489 kip-ft o.k. Manual
Table 3-19
Note that the required PNA location for ASD and LRFD differ. This is because the live to dead
load ratio in this example is not equal to 3. Thus, the PNA location requiring the most shear
transfer is selected to be acceptable for ASD. It will be conservative for LRFD.

<!-- p. 171 -->

I-8

Check the beam deflections and available strength
Check the deflection of the beam under construction, considering only the weight of concrete as
contributing to the construction dead load.

Limit deflection to a maximum of 2.5 in. to facilitate concrete placement.

0.83 kip/ft )( 45 ft ) 4 (1728 in. 3 /ft 3 ) 4 5 wDL l 4 5 ( I req = = = 1,060 in. 384 E ∆ 384 ( 29,000 ksi )( 2.5 in. )

From Manual Table 3-20, a W21×50 has Ix = 984 in.4, therefore this member does not satisfy the
deflection criteria under construction.

Using Manual Table 3-20, revise the trial member selection to a W21×55,
which has Ix = 1140 in.4, as noted in parenthesis below the shape designation.

Check selected member strength as an un-shored beam under construction loads assuming
adequate lateral bracing through the deck attachment to the beam flange.
LRFD ASD
Calculate the required strength Calculate the required strength

1.4 DL = 1.4 (0.83 kips/ft) = 1.16 kips/ft DL+LL = 0.83 + 0.20 = 1.03 kips.ft

1.2DL+1.6LL = 1.2 (0.83) + 1.6(0.20)
\= 1.32 klf

1.31 kip/ft(45 ft) 2 1.03 kips/ft(45 ft) 2
Mu (unshored) = Ma (unshored) =
8 8
\=331 kip-ft = 260 kip-ft

The design strength for a The allowable strength for a
W21×55 is 473 kip-ft > 331 kip-ft o.k. W21× 55 is 314 kip-ft > 260 kip-ft o.k.

For a W21×55 with Y2=7.0 in, the member has sufficient available strength when the PNA is at Manual
location 6 and ∑ Qn = 292 kips. Table 3-19

LRFD ASD
φbMn=767 kip-ft > 687 kip-ft o.k. Mn/Ωb = 510 kip-ft > 489 kip-ft o.k. Manual
Table 3-19

Check a
∑ Qn 292 kipsa = = = 0.716 in.
0.85 f c' b 0.85(4 ksi)(10 ft.)(12 in./ft.)
0.716 in. \< 1.0 in. assumed o.k.

Check live load deflection
∆LL \< l/360 = ((45 ft.)(12 in./ft))/360 = 1.5 in.

A lower bound moment of inertia for composite beams is tabulated in
Manual Table 3-20.

<!-- p. 172 -->

I-9

For a W21×55 with Y2=7.0 and the PNA at location 6, ILB = 2440 in.4 Manual Table
3-20
1.0 kip/ft )( 45 ft ) 4 (1728 in. 3 /ft 3 ) 5 wLL l 4 5 (
∆ LL = = 4 = 1.30 in. 384 EI LB 384 ( 29,000 ksi )( 2440 in. )
1.30 in. \< 1.5 in. o.k.

Determine if the beam has sufficient available shear strength
LRFD ASD
45ft 45ft Manual
Vu= ( 2.72kip/ft ) = 61.2 kips Va = (1.93kip/ft ) = 43.4 kips Table 3-3 2 2
φVn= 234 kips > 61.2 kips o.k. Vn/Ω = 156 kips > 43.4 kips o.k.

Determine the required number of shear stud connectors

Using perpendicular deck with one ¾-in. diameter weak stud per rib in normal weight 4 ksi Manual Table
concrete. Qn = 17.2 kips/stud 3-21

∑ Qn 292 kips = = 17, on each side of the beam. Section 3.2d(5) Qn 17.2 kips

Total number of shear connectors; use 2(17) = 34 shear connectors. Section 3.2d(6)

Check the spacing of shear connectors

Since each flute is 12 in., use one stud every flute, starting at each support, and proceed for 17
studs on each end of the span.
Section
6dstud \< 12 in. \< 8tslab , therefore, the shear stud spacing requirements are met. I3.2c (b)

The studs are to be 5 in. long, so that they will extend a minimum of 12 in. into slab.

<!-- p. 173 -->

I-10

Example I-2 Filled Composite Column in Axial Compression

Given:

Determine if a 14-ft long HSS10×6×a ASTM A500 grade B column filled with f′c = 5 ksi normal weight concrete
can support a dead load of 56 kips and a live load of 168 kips in axial compression. The column is pinned at both
ends and the concrete at the base bears directly on the base plate. At the top, the load is transferred to the concrete in
direct bearing.

Solution:

Calculate the required compressive strength
LRFD ASD
Pu = 1.2(56 kips) + 1.6(168 kips) Pa = 56 kips + 168 kips
\= 336 kips = 224 kips

The available strength in axial compression can be determined directly from the Manual at KL = 14
ft as:
LRFD ASD
φcPn = 353 kips Pn /Ωc = 236 kips Manual
Table 4-14
353 kips > 336 kips o.k. 236 kips > 224 kips o.k.

Supporting Calculations
The available strength of this filled composite section can be most easily determined by using
Table 4-14 of the Manual. Alternatively, the available strength can be determined by direct
application of the Specification requirements, as illustrated below.

Material Properties:
HSS10×6×3/8 Fy= 46 ksi Fu = 58 ksi Manual
Table 2-3
Concrete f′c = 5 ksi Ec = w1.5 f c' = (145)1.5 5 = 3,900 ksi

<!-- p. 174 -->

I-11

Geometric Properties:
HSS10×6×3/8 t = 0.375 in. b = 10.0 in. h = 6.0 in. Manual Table
1-11
Concrete:
The concrete area is calculated as follows

r = 2t = 2(0.375 in. ) = 0.75 in. (outside radius)
bf = b-2r = 10 – 2(0.75) = 8.50 in.
hf = h-2r = 6 – 2(0.75) = 4.50 in.

Ac = bfhf+ π(r-t)2 + 2bf(r-t) + 2hf(r-t)
\= (8.50 in.)(4.50 in.) + π(0.375 in.)2 + 2(8.50 in.)(0.375 in.) + 2(4.50 in.)(0.375 in.)
\= 48.4 in.2
b1 h13 2(b2 )( h2 ) 3 ⎛ π 8 ⎞ ⎛ π ( r − t ) 2 ⎞⎛ h2 4 ( r − t ) ⎞ 2 + I c = + + 2 ( r − t ) ⎜ − ⎟ + 2 ⎜ ⎟ ⎜ ⎟ 12 12 ⎝ 8 9 π ⎠ ⎜ ⎝ 2 ⎟⎠ ⎝ 2 3π ⎠
For this shape, buckling will take place about the weak axis, thus
h1 = 6 − 2 ( 0.375 ) = 5.25 in.
b1 = 10 − 4 ( 0.375 ) = 8.5 in.
h2 = 6 − 4 ( 0.375 ) = 4.5 in.
b2 = 0.375 in.
( r − t ) = 0.75 − 0.375 = 0.375 in.
(8.5)(5.25) 3 2(0.375)(4.50) 3 4 ⎛ π 8 ⎞ cI = + + 2 ( 0.375 ) ⎜ − ⎟ 12 12 ⎝ 8 9 π ⎠
⎛ π ( 0.375 ) 2 ⎞⎛ 4.5 4 ( 0.375 ) ⎞ 2
\+ 2 ⎜ ⎟⎜ + ⎟ ⎜ ⎝ 2 ⎟⎠ ⎝ 2 3π ⎠
\= 111 in.4
Manual Table
HSS10×6×a: 1-11
As = 10.4 in.2 Is = 61.8 in.4 h/t = 25.7

Limitations: Section I1.2
\1) Normal weight concrete 10 ksi > f′c > 3 ksi f′c = 5 ksi o.k.

\2) Not Applicable.

Section I2.2a 3) The cross-sectional area of the steel HSS shall comprise at least one percent of the total
composite cross section.

10.4 in.2 > (0.01)(48.6 in.2+ 10.4 in.2) = 0.590 in.2 o.k.

\4) The maximum b/t ratio for a rectangular HSS used as a composite column
shall be equal to 2.26 E Fy .

b/t = 25.7\< 2.26 E Fy =2.26 29,000ksi 46ksi = 56.7 o.k.

User note: For all rectangular HSS sections found in the Manual the b/t ratios do not
exceed 2.26 E Fy .
\5) Not Applicable.

<!-- p. 175 -->

I-12

Calculate the available compressive strength

C2 = 0.85 for rectangular sections Sec. I2.2b

Po = AsFy + AsrFyr + C2Ac f′c Eqn. I2-13
\= (10.4 in.2)(46 ksi) + 0.85(48.4 in.2)(5 ksi) = 684 kips

⎛ As ⎞ ⎛ 10.4in.2 ⎞
C3 = 0.6 + 2 ⎜ ⎟ = 0.6 + 2 ⎜ 2 2 ⎟ 0.954 > 0.90 Eqn. I2-15 ⎝ Ac + As ⎠ ⎝ 48.4in. + 10.4in. ⎠=
Therefore use 0.90

EIeff = EsIs + EsIsr + C3EcIc Eqn. I2-14
\= (29,000 ksi)(61.8 in.4) + (0.90)(3,900 ksi)( 111 in.4)
\= 2,180,000 kip-in.2

User note: K value is from Chapter C and for this case K = 1.0.

Pe = π2(EIeff)/(KL)2 = π2(2,180,000 kip-in.2) / ((1.0)(14ft)(12in./ft))2 = 762 kips
Eqn. I2-4
Po 684 kips = = 0.898
Pe 762 kips

0.898 \< 2.25 Therefore use Eqn. I2-2 to solve Pn
Section
⎡ ⎛ Po ⎞ ⎤ I2.1b
⎜ ⎟ ⎝ Pe ⎢ ⎠ ⎥ 0.658 = (684 kips) ⎡ 0.658( 0.898 ) ⎤ 470 kipsPn = Po ⎢ ⎥ ⎣ ⎦= Eqn. I2-6
⎢⎣ ⎥⎦

LRFD ASD
φc = 0.75 Ωc = 2.00
Section I2.1b
φcPn = 0.75(470kips) = 353 kips Pn/Ωc = 470 kips / 2.00 = 235 kips

353 kips > 336 kips o.k. 235 kips > 224 kips o.k.

<!-- p. 176 -->

I-13

Example I-3 Encased Composite Column in Axial Compression

Given:

Determine if a 14 ft tall W10×45 steel section encased in a 24 in.×24in. concrete column with f′c = 5 ksi, is adequate
to support a dead load of 350 kips and a live load of 1050 kips in axial compression. The concrete section has 8-#8
longitudinal reinforcing bars and #4 transverse ties @ 12in. o/c., The column is pinned at both ends and the load is
applied directly to the concrete encasement.

Solution:

Material Properties:
Column W10×45 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3
Concrete f′c = 5 ksi Ec = 3,900 ksi (145 pcf concrete)

Reinforcement Fyst = 60 ksi

Geometric Properties:
W10×45: Manual
As = 13.3 in.2 Table 1-1
Iy = 53.4 in.4

Reinforcing steel:
Asr = 6.32 in.2 (the area of 1-#8 bar is 0.79 in.2, per ACI)
π r 4 2 π (0.50) 4 2 4Isr = + Ad = 8 + 6(0.79)(9.5) = 428 in.
4 4

Concrete:
Ac = Acg - As - Asr = 576 in.2- 13.3 in.2 - 6.32 in.2 = 556 in.2
Ic = Icg - Is - Isr = 27,200 in.4

Note: The weak axis moment of inertia is used as part of a slenderness check.

<!-- p. 177 -->

I-14

Limitations:
\1) Normal weight concrete 10 ksi > f′c > 3 ksi f′c = 5 ksi o.k. Section I1.2

\2) Fyst \< 75 ksi Fyst = 60 ksi o.k.

\3) The cross-sectional area of the steel core shall comprise at least one percent of the total
Section I2.1a composite cross section.

13.3 in.2 > (0.01)(576 in.2) = 5.76in.2 o.k.

\4) Concrete encasement of the steel core shall be reinforced with continuous
longitudinal bars and lateral ties or spirals. The minimum transverse
reinforcement shall be at least 0.009 in.2 of tie spacing.

0.20 in.2/12 in. = 0.0167 in.2/in. > 0.009 in.2/in. o.k.

\5) The minimum reinforcement ratio for continuous longitudinal reinforcing, ρsr,
shall be 0.004.

Asr 6.32in. 2 ρsr = = 2 = 0.011 > 0.004 o.k. Eqn. I2-1
Ag 576in.

Calculate the total required compressive strength

LRFD ASD
Pu = 1.2(350 kips) + 1.6(1050 kips) Pa = 350 kips + 1050 kips
\= 2100 kips = 1400 kips

Calculate the available compressive strength
Po = AsFy + AsrFyr + 0.85Ac f′c
Eqn. I2-2 = (13.3 in.2)(50 ksi) + (6.32 in.2)(60 ksi) +0.85(556 in.2)(5 ksi) = 3410 kips

⎛ As ⎞ ⎛ 13.3 in.2 ⎞
C1 = 0.1 + 2 ⎜ ⎟ = 0.1 + 2 ⎜ 2 2 ⎟ = 0.15 ⎝ Ac + As ⎠ ⎝ 556 in. + 13.3 in. ⎠ Eqn. I2-5

EIeff = EsIs + 0.5EsIsr + C1EcIc
Eqn. I2-4 = (29,000 ksi)(53.4 in.4) + 0.5(29,000 ksi)(428 in.4) + (0.15)(3,900 in.4)(27,200)
\=23,700,000 kip-in.2

User note: K value is from Chapter C and for this case K = 1.0.

Pe = π2(EIeff)/(KL)2 = π2(23,700,000 kip-in.2) / ((1.0)(14in.)(12in./ft))2 = 8,290 kips
Eqn. I2-3
Po 3,410 kips = =0.411
Pe 8,290 kips

0.411 \< 2.25 Therefore use Eqn. I2-2 to solve Pn Section I2.1b

<!-- p. 178 -->

I-15

⎡ ⎛ Po ⎞ ⎤ Eqn. I2-6
⎜ ⎟ ⎝ Pe ⎢ ⎠ ⎥ 0.658 = (3,410 kips) ⎡ 0.658( 0.411) ⎤ 2870 kipsPn = Po ⎢ ⎥ ⎣ ⎦=
⎢⎣ ⎥⎦
LRFD ASD
φc = 0.75 Ωc = 2.00 Section I2.1b

φcPn = 0.75(2870kips) = 2150 kips Pn/Ωc = 2870 kips / 2.00 =1440 kips

2150 kips > 2100 kips o.k. 1440 kips > 1400 kips o.k.

Because the entire load in the column was applied directly to the concrete, accommodations must
be made to transfer an appropriate portion of the axial force to the steel column. This force is
transferred as a shear force at the interface between the two materials.

Determine the number and spacing of 2-in. diameter headed shear studs to transfer the axial
force.

Solution:

Material Properties:
Conc. f′c = 5 ksi Ec = 4070 ksi

Manual TableShear Studs Fu = 65 ksi
3-21

Geometric Properties:
W10×45 Ast = 13.3 in.2 Aflange = 4.97 in.2 Aweb = 3.36 in.2 dst = 10.1 in. Manual
Table 1-1Shear Studs Asc = 0.196 in.2
Conc. dc = 24 in.

Calculate the shear force to be transferred
LRFD ASD
Pu 2,100 V = Pa Ω=c 1,400 ( 2 ) = 2,800 kips V = = = 2,800 kips
φ c 0.75

V′= V(AsFy /Po) = 2800 kips ((13.3 in.2)(50 ksi) / (3410 kips)) = 546 kips Eqn. I2-10
Calculate the nominal strength of one 2 in. diameter shear stud connector

<!-- p. 179 -->

I-16

Qn = 0.5Asc f c' Ec \< AscFu
0.5Asc f c' Ec = 0.5(0.196 in.2) (5ksi)(3900ksi) = 13.7 kips
Eqn. I2-12
AscFu = (0.196 in.2)(65 ksi) = 12.7 kips

Therefore use 12.7 kips.

Calculate the number of shear studs required to transfer the total force, V’

V′ / Qn = 546 kips / 12.7 kips = 43

An even number of studs are required to be placed symmetrically on two faces. Therefore use 22
studs minimum per flange

Determine the spacing for the shear studs Section
I2.1f
The maximum stud spacing is 16 in.

The available column length is 14ft (12 in./ft) = 168 in. and the maximum spacing is
\= 168 in./(22+1) = 7.3 in.

Therefore, on the flanges, use single studs @ 7 in.

Stud placement is to start 10.5 in. from one end.

Determine the length of the studs for the flanges;

⎛ d c − d st ⎞ ⎛ 24 in. − 10.1 in. ⎞
⎜ ⎟ - 3 in. = ⎜ ⎟ 3 in. = 3.95 in.⎝ 2 ⎠ ⎝ 2 ⎠-
Therefore use 3 ½ in. in length for the flanges.

Note: The subtraction of 3 in. is to ensure sufficient cover.

Summary: use 2-in. diameter shear stud connectors as shown on each flange, spaced @ 7 in.

<!-- p. 180 -->

I-17

Example I-4 Encased Composite Column in Axial Tension

Given:

Determine if the composite column in Example I-3 can support a dead load compression of 150 kips and a wind load
tension of 645 kips. The column is pinned at both ends. The steel W-shape and the reinforcing are attached at each
end in order to transfer any tensile force.

Solution:

Material Properties:
Column W10×45 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3Concrete f′c = 5 ksi Ec = 3,900 ksi
Reinforcement Fyst = 60 ksi
ACI-318

Geometric Properties:
W10×45: Manual
As = 13.3 in.2 Iy = 53.4 in.4 Table 1-1

Reinforcing steel:
Asr = 6.32 in.2 Isr = 428 in.4

Concrete:
Ac= 556 in.2 Ic = 27,200 in.4

<!-- p. 181 -->

I-18

Limitations:
\1) Normal weight concrete 10 ksi > f′c > 3 ksi; f′c = 5 ksi o.k. Section I1.2

\2) Fyst \< 75 ksi; Fyst = 60 ksi o.k.

\3) The cross-sectional area of the steel core shall comprise at least one percent of the total
Section I2.1a composite cross section.

13.3 in.2 > (0.01)(576 in.2) = 5.76in.2 o.k.

\4) Concrete encasement of steel core shall be reinforced with continuous
longitudinal bars and lateral ties or spirals. The minimum transverse
reinforcement shall be at least 0.009 in.2 of tie spacing.

0.20 in.2/12 in. = 0.0167 in.2/in. > 0.009 in.2/in. o.k.

\5) The minimum reinforcement ratio for continuous longitudinal reinforcing, ρsr,
shall be 0.004.

Asr 6.32in. 2
ρsr = = 2 = 0.011 > 0.004 o.k. Eqn. I2-1
Ag 576in.

Calculate the required tensile strength
LRFD ASD
Pu =0.9(-150 kips) + 1.6(645 kips) Pa = 0.6(-150 kips) + 645 kips
\= 897 kips = 555 kips

Calculate the available tensile strength
Pn = Pt = AsFy + AsrFyr Eqn. I2-8
\= (13.3 in.2)(50 ksi) + (6.32 in.2)(60ksi) = 1040 kips

LRFD ASD
φt = 0.90 Ωt = 1.67 Section I2.1c

φtPn = 0.90(1040 kips) = 940 kips Pn/Ωt = 1040 kips / 1.67 = 625 kips

940 kips > 897 kips o.k. 625 kips > 555 kips o.k.

<!-- p. 182 -->

I-19

Example I-5 Filled Composite Column in Axial Tension

Given:

Determine if the filled composite column in Example I-2 is adequate to support a dead load compression of 70 kips
and a wind load tension of 300 kips. The column is pinned at both ends and all of the load is transferred by the base
and cap plates.

Solution:

Material Properties:
HSS10×6×a Fy= 46 ksi Fu = 58 ksi Manual
Table 2-3
Concrete f′c = 5 ksi Ec = 4,070 ksi

Geometric Properties:
HSS10×6×a: Manual
A = 10.4 in.2 Table 1-11

Calculate the required tensile strength
LRFD ASD
Pu = 0.9(-70 kips) + 1.6(300 kips) Pa = 0.6(-70 kips) + 300 kips
\= 417 kips = 258 kips

Determine the available tensile strength
Pn = Po = AsFy Eqn. I2-16
\= (10.4 in.2)(46 ksi) = 478 kips

LRFD ASD
φt = 0.90 Ωt = 1.67
Section
φtPn =0.90(478 kips) = 430 kips Pn/Ωt = 478 kips / 1.67 = 286 kips I2.1b

430 kips > 417 kips o.k. 286 kips >258 kips o.k.

User note: The concrete is not considered to contribute to the available tensile strength, therefore
no shear transfer between the encasing steel and the concrete fill is required for this load case.

<!-- p. 183 -->

I-20

Example I-6 Filled Composite Member Design for Shear.

Given:

This composite member ASTM A500 grade B with 5ksi normal weight concrete has a dead load end shear of 20 kips
and a live load end shear of 60 kips. Verify that this end shear can be safely carried by both LRFD and ASD analysis.

User note: Shear strength shall be calculated based on either the shear strength of the steel section
alone as specified in Specification Chapter G or the shear strength of the reinforced concrete Section
portion alone. I2.2d

Solution:

Material Properties:
ASTM A500 Gr. B Fy = 46ksi Fu = 58 ksi Manual
Table 2.3

Geometric Properties:
HSS 10×6×a d = 10 in. tw = 0.349 in. Manual Table
1-11

Calculate the required shear strength
LRFD ASD
Vu = 1.2(20 kips) + 1.6(60 kips) Va = 20 kips + 60 kips
\= 120 kips = 80 kips

Calculate the available shear strength
The available shear area for rectangular HSS and box members is 2ht, where h is the outside
dimension minus the top and bottom radii. If the exact corner radius is not known, h shall be Section G5
taken as the outside dimension minus three times the design wall thickness.

User note: kV = 5.0 for all sizes of HSS rectangular or box members listed in the Manual. Also
all HSS listed in the manual have a Cv = 1.0. Section G5

Calculate h

h = d – (3tw) = 10 in. – (3)(0.349 in.) = 8.95 in. Section G5

Calculate Aw

Aw = 2htw = 2(8.95 in.)(0.349 in.) = 6.25 in2 Section G5

Calculate Vn

Vn = 0.6FyAwCv = 0.6(46 ksi)(6.25 in.2)(1.0) = 173 kips Eqn. G2-1

<!-- p. 184 -->

I-21

LRFD ASD
φv = 0.90 Ωv = 1.67
Section G1
Vu = φvVn = 0.90(173 kips) = 156 kips Va = Vn/Ωv = 173 kips / 1.67 = 104 kips

156 kips ? 120 kips o.k. 104 kips ? 80 kips o.k.

User note: For illustration of Cv = 1.0 refer to Chapter G, Example G.4.

<!-- p. 185 -->

I-22

Example I-7 Combined Axial and Flexural Strength

Given:

A 14 ft long composite column consists of a W10×45 steel section encased in a 24 in.×24in. concrete section. The
concrete is reinforced with 8-#8 longitudinal bars and #4 transverse ties @ 12 in. o.c., as illustrated below.
Determine if the member has sufficient available strength to support an axial dead load of 260 kips and an axial live
load of 780 kips in compression, as well as a dead load moment of 80 k-ft and a live load moment of 240 k-ft. The
load is applied directly to the concrete encasement.

Solution:

Material Properties:
W10×45:
ASTM A992 Fy = 50 ksi Fu = 65 ksi
Manual
Table 2-3Concrete
f′c = 5 ksi Ec = 3,900 ksi ACI-318

Reinforcement
Fyst = 60 ksi

Geometric Properties:
W10×45:
As = 13.3 in.2 Iy = 53.4 in.4 Z =54.9 in3 d = 10.1 in. bf = 8.02 in. tw = 0.35 in. Manual
tf = 0.62 in. Table 1-1

Reinforcing steel:
Asr = 6.32 in.2 Asrs = 1.59 in.2 Isr = 428 in.4

Concrete:
Ac = 556 in.2 Ic = 27,200 in.4

<!-- p. 186 -->

I-23

Limitations:
\1) Normal weight concrete 10 ksi > f′c > 3 ksi f′c = 5 ksi OK Section I1.2

\2) Fyst \< 75 ksi Fyst = 60 ksi o.k.

\3) The cross-sectional area of the steel core shall comprise at least one percent of the total
Section I2.1a composite cross section.

13.3 in.2 > (0.01)(576 in.2) = 5.76in.2 o.k.

\4) Concrete encasement of steel core shall be reinforced with continuous
longitudinal bars and lateral ties or spirals. The minimum transverse
reinforcement shall be at least 0.009 in.2 per inch of tie spacing.

0.20 in.2/12 in. = 0.0167 in.2/in. > 0.009 in.2/in. o.k.

\5) The minimum reinforcement ratio for continuous longitudinal reinforcing, ρsr,
shall be 0.004.

Asr 6.32in. 2 ρsr = = 2 = 0.011 > 0.004 o.k. Eqn. I2-1
Ag 576in.
Calculate the required strengths
LRFD ASD
Pu = 1.2(260 kips) + 1.6(780 kips) Pa = 260 kips + 780 kips
\= 1560 kips = 1040 kips

Mu= 1.2(80 k-ft) + 1.6 (240 k-ft) Ma = 80 k-ft + 240 k-ft
\= 480 k-ft = 320 k-ft

The available strength of the composite section subjected to combined axial and flexural loads is
determined by constructing an interaction curve. The curve is generated by calculating the
available strength of the section at a series of points on the interaction curve and reducing the
strength for slenderness effects and multiplying by the resistance factor for LRFD or dividing by
the safety factor for ASD. The defining equations of the interaction curve were given earlier in
Figure I-1a, and will be used to construct the curve illustrated in Commentary Figure C4-3, and
repeated here.

<!-- p. 187 -->

I-24

Point A (M = 0)

Determine the available compressive strength and moment strength
Po = AsFy + AsrFyr + 0.85Ac f′c
Eqn. I2-4 = (13.3 in.2)(50 ksi) + (6.32 in.2)(60ksi) +0.85(556 in.2)(5ksi) = 3,410 kips

⎛ As ⎞ ⎛ 13.3in.2 ⎞
C1 = 0.1 + 2 ⎜ ⎟ = 0.1 + 2 ⎜ 2 2 ⎟ = 0.15 Eqn. I2-7 ⎝ Ac + As ⎠ ⎝ 556in. + 13.3in. ⎠

EIeff = EsIs + 0.5EsIsr + C1EcIc
\= (29,000 ksi)(53.4 in.4) + 0.5(29,000 ksi)(428 in.4) + (0.15)(3,900 in.4)(27,200) Eqn. I2-6
\= 23,700,000 kip-in.2

User note: K value is from Chapter C and for this case K = 1.0.

Pe = π2(EIeff)/(KL)2 = π2(23,700,000 kip-in.2) / ((1.0)(14 ft)(12in./ft))2 = 8,290 kips Eqn. I2-5

Po 3,410 kips = = 0.411
Pe 8,290 kips

0.411 \< 2.25 Therefore use Eqn. I2-2 to determine Pn

⎡ ⎛ Po ⎞ ⎤
⎜ ⎟ ⎝ Pe ⎢ ⎠ ⎥ 0.658 = (3410 kips) ⎡ 0.658( 0.411) ⎤ 2870 kips Eqn. I2-2PnA = Po ⎢ ⎥ ⎣ ⎦=
⎢⎣ ⎥⎦

<!-- p. 188 -->

I-25

⎛ Ac (0.85 f c' ) ⎞
Point D ⎜ PD = ⎟
⎝ 2 ⎠
Ac ( 0.85 f c' )
PD = Commentary
2 Figure C-I4.1
556 in 2 0.85)( 5.0 ksi ) ( )(
PD =
2
PD = 1180 kips
Z s = full x-axis plastic modulus of steel shape
Z s = 54.9 in 3
⎛ h2 ⎞ 2 2 ⎛ 24 in. ⎞ 3 − c = 6.32 in. − 1.59 in. = 44.9 in -2 12 in.⎟ Z r = ( Asr − Asrs ) ⎜ ⎟ ( ⎠ ⎠ ⎝ 2 ) ⎜⎝ 2
2 2 h1h2 ( 24 in )( 24 in ) 3 3 3 Z c = − Z s − Z r = − 54.9 in − 44.9 in = 3360 in
4 4
1 ' M D = Z s Fy + Z r Fyr + Z c ( 0.85 f c ) 2
3 3 1 3 54.9 in 44.9 in 3360 in 0.85 )( 5.0 ksi ) M D = ( )( 50 ksi ) + ( )( 60.0 ksi ) + ( )( 2
\= 12,600 k-in
12,600 k-in
M nD = in = 1050 k-ft 12 ft

⎡ ⎛ Po ⎞ ⎤ Eqn. I2-2
⎜ ⎟ ⎝ Pe ⎢ ⎠ ⎥ 0.658 = (1,180 kips) ⎡ 0.658( 0.411) ⎤ 994 kips andPnD = Po ⎢ ⎥ ⎣ ⎦= Commentary
⎢⎣ ⎥⎦ I4

<!-- p. 189 -->

I-26

Point B (PB = 0)

⎛ ⎛ d ⎞ d ⎞
For hn in the flange ⎜ ⎜ − t f ⎟ \< hn ≤ ⎟ Commentary ⎝ ⎝ 2 ⎠ 2 ⎠ Figure C-I4.1
− 2 Fyr Asrs 0.85 f c' ( − 2 F y ( Ac + As − db f + Asrs ) As − db f )
hn =
2 ⎡ + 2 F y b f ⎤ 0.85 f c ' ( h1 − b f ) ⎣ ⎦
556 in. 2 + 13.3 in. 2 − 10.1(8.02) + 1.59 13.3 in. 2 − 10.1(8.02) − 2(60)(1.59) 0.85 ( 5.0 ksi )( − 2 ( 50 ksi )( ) )
hn = 2 [ ( 0 .85 )( 5.0 ksi )( 24 in.-8.02 ) + 2(50)(8.02) ]
hn = 4.98 in.
⎛ d ⎞⎛ d ⎞
Z sn = Z s − b f ⎜ − hn ⎟⎜ + hn ⎟ ⎝ 2 ⎠⎝ 2 ⎠
3 ⎛ 10.1 ⎞⎛ 10.1 ⎞ 3
Z sn = 54.9 in − 8.02 ⎜ − 4.98⎟⎜ + 4.98⎟ = 49.3 in. ⎝ 2 ⎠⎝ 2 ⎠
2 2 3Z cn = h1 hn − Z sn = ( 24 in.)( 4.98 in.) − 49.3 in
Z cn = 546 in.3
1 'M B = M D − Z sn F y − Z c n ( 0.85 f c ) 2
49.3 in.3 50.0 ksi )M B = (12,600 k-in.) − ( )(
1 3 546 in.− 0.85 )( 5.0 ksi ) = 8,970 k-in. ( )( 2
8,970 k-in.
M nB = = 748 k-ft
12 in.ft

Point C (MC = MB; PC = 0.85 f′c Ac)
PC = Ac ( 0.85 f c' ) Commentary
556 in 2 0.85 )( 5.0 ksi ) = 2360 kips Figure C-I4.1 PC = ( )(
M nC = M nB = 748 k-ft

⎡ ⎛ Po ⎞ ⎤
⎜ ⎟ Eqn. I2-2 and ⎝ Pe ⎢ ⎠ ⎥ 0.658 0.6580.411 ⎤ = 2360 ⎡ = 1990 kips PnC = PC ⎣ ⎦ ⎢ ⎥ Commentary
⎢⎣ ⎥⎦ Section I4

<!-- p. 190 -->

I-27

Summary of nominal strength including length effects

PnA = 2870 kips
M nA = 0
PnB = 0
M nB = 748 k-ft
PnC = 1990 kips
M nC = 748 k-ft
PnD = 994 kips
M nD = 1050 k-ft

LRFD ASD
φc = 0.75 φb = 0.90 Ωc = 2.00 Ωb = 1.67 Section I4

φ c PnA = 2150 kips PnA / Ω=c 1440 kips
φ b M nA = 0 M nA / Ω=b 0
φ c PnB = 0 PnB / Ω=c 0
φ b M nB = 673 k-ft M nB / Ω=b 448 k-ft
φ c PnC = 1490 kips PnC / Ω=c 995 kips
φ b M nC = 673 k-ft M nC / Ω=b 448 k-ft
φ c PnD = 746 kips PnD / Ω=c 497 kips
φ b M nD = 945 k-ft M nD / Ω=b 629 k-ft

Interaction Interaction

Pu > Pc Pu > Pc Commentary
1560 kips > 1490 kips 1040 kips > 995 kips Section I4

thus thus

Pu − PC M uy Pu − PC M uy + ≤ 1.0 + ≤ 1.0
PA − PC M Cy PA − PC M Cy

1560 − 1490 480 1040 − 995 320
\+ = 0.82 > 1.0 + = 0.82 > 1.0
2150 − 1490 673 1440 − 995 448

Therefore, this column is adequate Therefore, this column is adequate
for the specified loading for the specified loading

The shear connector requirements for this encased composite column are similar
to that of Example I-2

<!-- p. 191 -->

J-1

CHAPTER J
DESIGN OF CONNECTIONS

INTRODUCTION

Chapter J of the Specification addresses the design and checking of connections. The chapter’s primary focus is
the design of welded and bolted connections. Design requirements for fillers, splices, column bases, concentrated
forces, anchors rods, and other threaded parts are also covered. Special requirements for connections subject to
fatigue are not covered in this chapter.

<!-- p. 192 -->

J-2

Example J.1 Fillet Weld in Longitudinal Shear

Given:

An ¼ in.×18-in. wide plate is fillet welded to a a-in. plate. Assume that the plates are ASTM
A572 grade 50 and have been properly sized. Assume FEXX = 70 ksi. Note that plates would
normally be specified as ASTM A36, but Fy = 50 ksi plate has been used here to demonstrate
requirements for long welds.

Size the welds for the loads shown.

Solution:

Determine the maximum weld size

Because the overlapping plate is ¼ in., the maximum fillet weld size that can be used without
special notation (built out to obtain full-throat thickness as required in AISC Specification
Section J2.2b) is a x-in. fillet weld. A x-in. fillet weld can be deposited in the flat or
horizontal position in a single pass (true up to c-in).

Determine the required strength
LRFD ASD
Pu = 1.2(33 kips) + 1.6(100 kips) = 200 kips Pa = 33 kips + 100 kips = 133 kips

Determine the length of weld required
LRFD ASD
The design strength per inch of a x-in. The allowable strength per inch of a x-in.
fillet weld is fillet weld is

φRn = 1.392 (3) = 4.17 kips/ in. Rn/Ω= 0.928 (3) = 2.78 kips/ in. Manual
Part 8
Pu 200 kips Pa Ω 133 kips = = 48 in. = = 48 in.
φRn 4.17 kips/in. Rn 2.78 kips/in.
or 24 in. of weld on each side or 24 in. of weld on each side.

<!-- p. 193 -->

J-3

Check the weld for length to weld size ratio

l 24 in.
\= = 128 > 100,
w 0.188 in.

Therefore Specification Equation J2-1 must be applied, and the length of weld increased, since
the resulting β will reduce the available strength below the required strength.

SpecificationTry a weld length of 27 in.
Eqn. J2-1
The new length to weld size ratio is 27 in. /0.188 in. = 144

For this ratio

β = 1.2-0.002(l/w) M 1.0; 1.2- 0.002(144) = 0.912

Recheck the weld at its reduced strength

LRFD ASD
Rn =(0.912) ( 2.78 kips/in.)( 54 in.) φRn = (0.912) ( 4.17 kips/in.)( 54 in.) Ω
\= 205 kips > Pu = 200 kips o.k. = 137 kips > Pa = 133 kips o.k.

Therefore, use 27 in. of weld on each side Therefore, use 27 in. of weld on each side

<!-- p. 194 -->

J-4

Example J.2 Fillet Weld Loaded at an Angle

Given:

Design a fillet weld at the edge of a gusset plate to carry a force of 50 kips due to dead load
and a force of 150 kips due to live load, at an angle of 60 degrees relative to the weld. Assume
the beam and the gusset plate thickness and length have been properly sized.

Solution:

Calculate the required strength

LRFD ASD
Pu = 1.2(50 kips) + 1.6(150 kips) = 300 kips Pa = 50 kips + 150 kips = 200 kips

Assume a c-in. fillet weld is used on each side.

The shear strength of a c-in. fillet weld is

LRFD ASD
5(1.392) = 6.96 kip/in. 5(0.928) = 4.64 kip/in.

And for two sides And for two sides
2(6.96 kip/in.) = 13.9 kip/in. 2(4.64 kip/in.) = 9.28 kip/in.

Because the angle of the force relative to the axis of the weld is 60 degrees, the strength of the
weld can be increased as follows:
kw = 0.60 FEXX (1.0 + 0.50 sin 1.5 θ )

1.5 = 0.60(70) (1.0 + 0.50 (0.866) )
\= 1.40

<!-- p. 195 -->

J-5

Find the increased strength and the required length of weld
LRFD ASD
Calculate the increased strength. Calculate the increased capacity.
13.9 kip/in.(1.40) = 19.5 kip/in. 9.280 kip/in.(1.40) = 13.0 kip/in.

Determine the required length of weld. Determine the required length of weld.
300 kips/19.5 kip/in. = 15.4 in. 200 kips/13.0 kip/in. = 15.4 in.

Use 16 in. o.k. Use 16 in. o.k.

<!-- p. 196 -->

J-6

Example J.3 Combined Tension and Shear in Bearing Type Connections

Given:

A ¾-in. diameter, ASTM A325-N bolt is subjected to a tension force of 3.5 kips due to dead
load and 12 kips due to live load, and a shear force of 1.33 kips due to dead load and 4 kips
due to live load.

Check the combined stresses according to the Equations J3-3a and J3-3b.

Solution:

Calculate the required tensile and shear strength

LRFD ASD
Tension = 1.2(3.5) +1.6(12.0) = 23.4 kips Tension = 3.5 + 12.0 = 15.5 kips
Shear = 1.2(1.33) + 1.6(4.00) = 8.00 kips Shear = 1.33 + 4.00 = 5.33 kips

Calculate fv Calculate fv

8.00/0.442 = 18.1 ksi ≤ φFnv 5.33/0.442 = 12.1 ksi ≤ Fnv /Ω

Check combined tension and shear. Check combined tension and shear. Eq. J3-3a
Fnt Ω Fnt and J3-3b Fnt′ = 1.3 Fnt − f v ≤ Fnt Fnt′ = 1.3 Fnt − f v ≤ Fnt
φFnv Fnv
Fnt = 90 ksi, Fnv = 48 ksi Fnt = 90 ksi, Fnv = 48 ksi
90 Fnt′ = 1.3(90) − (18.1) Fnt′ = 1.3(90) −2.00(90) (12.1)
0.75(48) 48
\= 71.7 \< 90 = 71.6 \< 90 Table J3.2

Section J3.6 Rn = Fnt′Ab = 71.7(0.442) = 31.7 kips Rn = Fnt′Ab = 71.6(0.442) = 31.6 kips

For combined tension and shear For combined tension and shear
φ = 0.75 Ω = 2.00

Design tensile strength Allowable tensile strength

φRn = 0.75(31.7) = 23.8 kips > 23.4 kips o.k. Rn/Ω=31.6/2.00 = 15.8 kips > 15.5 kips o.k.

<!-- p. 197 -->

J-7

Example J.4 Slip-Critical Connection with Short Slotted Holes
High-strength bolts in slip-critical connections are permitted to be designed to prevent slip either as a
serviceability limit state or as a strength limit state. The most common design case is design for slip as a
serviceability limit state. The design of slip as a strength limit state should only be applied when bolt slip can
result in a connection geometry that will increase the required strength beyond that of a strength limit state, such
as bearing or bolt shear. Such considerations occur only when oversized holes or slots parallel to the load are
used, and when the slipped geometry increases the demand on the connection. Examples include the case of
ponding in flat-roofed long span trusses, or the case of shallow, short lateral bracing.

Given:
Select the number of ¾-in. ASTM A325 slip-critical bolts with a Class A faying surface that
are required to support the loads shown when the connection plates have short slots transverse
to the load. Select the number of bolts required for slip resistance only.

Assume that the connected pieces have short slots transverse to the load. Use a mean slip
coefficient of 0.35, which corresponds to a Class A surface.

Solution:

Calculate the required strength
LRFD ASD
Pu = 1.2(17 kips) + 1.6(51 kips) = 102 kips Pa = 17 kips + 51 kips = 68 kips

For standard holes or slots transverse to the direction of the load, a connection can be
designed on the basis of the serviceability limit state. For the serviceability limit state:

φ = 1.00 Ω = 1.50 Specification
Find Rn, where: Section J3.8

µ = 0.35 for Class A surface
Du = 1.13
hsc = 0.85 (short slotted holes)
Table J3.1Tb = 28 kips
Ns = 2, number of slip planes

Rn = µDuhscTbN
Eqn.J3-4
Rn = 0.35(1.13)(0.85)(28)(2) = 18.8 kips/bolt

<!-- p. 198 -->

J-8

Determine the required number of bolts.
LRFD ASD
18.8 kips/bolt Manual
68 kips / = 5.42 bolts
102 kips/1.00(18.8 kips/bolt) = 5.42 bolts 1.50 Table 7-3

Use 6 bolts o.k. Use 6 bolts o.k.

Given:

Repeat the problem with the same loads, but assuming that the connected pieces have long
slotted holes in the direction of the load and that the deformed geometry of the connection
would result in a critical load increase.

Solution:

Pu= 102 kips and Pa = 68 kips per the first solution

For this connection, the designer has determined that oversized holes or slots parallel to the
direction of the load will result in a deformed geometry of the connection that creates a critical
load case. Therefore, the connection is designed to prevent slip at the required strength level.

φ = 0.85 Ω = 1.76 Specification
Section J3.8
In addition, hsc will change because we now have long slotted holes.

Find Rn

µ = 0.35 for Class A surface
Du = 1.13
hsc = 0.70 (long slotted holes)
Tb = 28 kips
Ns = 2, number of slip planes Table J3.1

Rn = µDuhscTbNs

SpecificationRn = 0.35(1.13)(0.70)(28)(2) = 15.5 kips/bolt
Eqn. J3-4

<!-- p. 199 -->

J-9

Determine the required number of bolts
LRFD ASD
102 kips 68 kips (1.76) Manual
\= 7.73 bolts = 7.63 bolts Table 7-4 0.85(15.5 kips/bolt) 15.5 kips/bolt
Use 8 bolts o.k. Use 8 bolts o.k.

<!-- p. 200 -->

J-10

Example J.5 Combined Tension and Shear in a Slip-Critical Connection.
Because the pretension of a bolt in a slip-critical connection is used to create the clamping force that produces the
shear strength of the connection, the available shear strength must be reduced for any load that produces tension in
the connection.

Given:

The slip-critical bolt group shown below is subjected to tension and shear. This connection is designed for slip as
a serviceability limit state. Use ¾-in. diameter ASTM A325 slip-critical class A bolts in standard holes. This
example shows the design for bolt slip resistance only, and assumes that the beams and plates are adequate to
transmit loads in a rigid fashion.

Solution:

The fastener pretension for a ¾-in. diameter ASTM A325 bolt is 28 kips Specification
Table J3.1
Du = 1.13 per Specification Section J3.8.
Nb = number of bolts carrying the applied tension.

Determine the tension on bolts, check tension on the bolts and find ks
LRFD ASD
Pu = 1.2(10 kips)+1.6(30kips) = 60 kips Pa = 10 kips + 30kips = 40 kips

By geometry, By geometry,

4 ⎛ 60 kips ⎞ 4 ⎛ 40 kips ⎞
Tu = ⎜ ⎟ 6 kips/bolt Ta = ⎜ ⎟ 4 kips/bolt 5 ⎝ 8 bolts ⎠= 5 ⎝ 8 bolts ⎠=
3 ⎛ 60 kips ⎞ 3 ⎛ 40 kips ⎞
Vu = ⎜ ⎟ 4.5 kips/bolt Va = ⎜ ⎟ 3 kips/bolt 5 ⎝ 8 bolts ⎠= 5 ⎝ 8 bolts ⎠=

Check bolt tension Check bolt tension

φRn= 29.8 kips/bolt > 6 kips/bolt o.k. Rn /Ω= 19.9 kips/bolt > 4 kips/bolt o.k. Manual
Table 7-2

<!-- p. 201 -->

J-11

Combined tension and shear factor Combined tension and shear factor
Tu 6 kips Ta 1.5 × 4 kips Eqn. J3-5a ks = 1 − = 1 − ks = 1 −1.5 = 1 − and J3-5b Du Tb N b 1.13(28 kips)(1) Du Tb N b 1.13(28 kips)(1)
\= 0.810 = 0.810

Multiply the available shear strength of the bolts by the reduction factor ks
LRFD ASD
φRn = 11.1 kips/bolt Rn /Ω = 7.38 kips/bolt Manual
Table 7-3

Modify the slip resistance by ks and check bolt shear
LRFD ASD
ksφRn= (0.810)(11.1 kips/bolt) k s Rn = (0.810)(7.38 kips/bolt)
Ω
\= 8.99 kips/bolt > 4.50 kips/bolt o.k. = 5.98 kips/bolt > 3.00 kips/bolt o.k.

<!-- p. 202 -->

J-12

Example J.6 Bearing Strength of a Pin in a Drilled Hole

Given:

A 1-in. diameter pin is placed in a drilled hole in a 12-in. thick steel plate.

Determine the available bearing strength of the pinned connection.

Material Properties:
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi

Solution:

Calculate the projected bearing area

1 1 2 in.2 2 in.) = 1Apb = dt p = (1 in.)(1

Calculate nominal bearing strength

Rn = 1.8 Fy Apb = 1.8 ( 36 ksi )(1 12 in.) = 97.2 kips Specification
Eqn. J7-1

Calculate the available bearing strength
LRFD ASD
φ = 0.75 Ω = 2.00 Specification
97.2 kips Section J7 φRn = 0.75 ( 97.2 kips ) = 72.9 kips Rn / Ω= = 48.6 kips
2.00

<!-- p. 203 -->

J-13

Example J.7 Base Plate Bearing on Concrete

Given:

A W12×96 column bears on a 24 in. × 24 in. concrete pedestal. The space between the base
plate and the concrete pedestal is grouted. Design the base plate to support the following loads
in axial compression:
PD = 115 kips
PL = 345 kips

Material Properties:

Column W12×96 ASTM A992 Fy = 50 ksi Fu = 65 ksi
Base Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi
Concrete Pedestal f’c = 3 ksi
Grout f’c = 4 ksi

Geometric Properties:

Column W12×96 d = 12.7 in. bf = 12.2 in. tf = 0.900 in. tw = 0.550 in. Manual
Table 1-1

Solution:

Calculate the required strength
LRFD ASD
uP = 1.2 (115 kips ) + 1.6 ( 345 kips ) = 690 kips aP = 115 kips + 345 kips = 460 kips

Aped = (24 in.)(24 in.) = 576 in.2
Acol = (12.7 in.)(12.2 in.) = 155 in.2

Since the pedestal area is larger than the column footprint area, but less than less than 4 times
column footprint area, the concrete bearing area will be the geometrically similar area of the
pedestal to the base plate.

<!-- p. 204 -->

J-14

Calculate the base plate area

LRFD ASD
φc = 0.60 Ωc = 2.50 Specification
Pu Pa Ω c Section J8
A1( req ) = A1( req ) = φ c 0.85 f ' c 0.85 f ' c

690 kips 2 ( 460 kips )( 2.50 ) 2 = = 451 in. = = 451 in. 0.6 ( 0.85)( 3 ksi ) ( 0.85)( 3 ksi )

Note: The strength of the grout has conservatively been neglected, as its strength is greater
than that of the concrete pedestal.

Try a 22 in.×22 in. base plate

Check base plate dimensions

Table 14-2Verify N ≥ d + 2 ( 3 in.) and B ≥ b f + 2 ( 3 in.)

d + 2 ( 3 in.) = 12.7 in. + 2 ( 3 in.) = 18.7 in. \< 22 in. o.k.

fb + 2 ( 3 in.) = 12.2 in. + 2 ( 3 in.) = 18.2 in. \< 22 in. o.k.

2 > 451 in.2 o.k.Base plate area, A1 = NB = ( 22 in.)( 22 in.) = 484 in.

Note: A square base plate with a square anchor rod pattern will be used to minimize the chance
for field and shop problems.

Calculate the geometrically similar concrete bearing area

Since the pedestal is square and the base plate is a concentrically located square, the full
pedestal area is also the geometrically similar area. Therefore,

2A2 = ( 24 in.)( 24 in.) = 576 in.

Verify the concrete bearing strength

LRFD ASD
φc = 0.60 Ωc = 2.50 Specification
Section J8
Specification A2 0.85 f ' c A1 A2 φ c Pp = φ c 0.85 f ' c A1 Pp / Ω=c Eqn. J8-2
A1 Ω c A1

2 2 2 576 in. 2 ( 0.85)( 3 ksi )( 484 in. ) 576 in. = 0.6 ( 0.85)( 3 ksi )( 484 in. ) 2 = 2 484 in. 2.5 484 in.

\= 808 kips > 690 kips o.k. = 539 kips > 460 kips o.k.

<!-- p. 205 -->

J-15

Note: It is permitted to take φc = 0.65 per ACI 318-02
Also note that as the area of the base plate approaches the area of concrete, the modifying
A2ratio, , approaches unity and Specification Eqn. J8-2 converges to Specification Eqn. J8-1.
A1

Calculate required base plate thickness Manual
Part 14
N − 0.95d 22 in. − 0.95 (12.7 in.)m = = = 4.97 in.
2 2

B − 0.8b f 22 in. − 0.8 (12.2 in.)n = = = 6.12 in.
2 2

db f (12.7 in.)(12.2 in.)
n ' = = = 3.11 in.
4 4

LRFD ASD
Calculate required base plate thickness Calculate required base plate thickness

4 db f Pu 4 db f Pa Ω c
X = 2 X = 2
Pp ( φ c Pp ( d + b f ) d + b f )

4 (12.7 in.)(12.2 in.)( 690 kips ) 4 (12.7 in.)(12.2 in. )( 460 kips )
\= 2 = 2
(12.7 in. + 12.2 in.) ( 808 kips ) (12.7 in. + 12.2 in.) ( 539 kips )

\= 0.854 = 0.853

2 X 2 X
λ = ≤ 1 λ = ≤ 1
1 + 1 − X 1 + 1 − X

2 0.854 2 0.853
\= =
1 + 1 − 0.854 1 + 1 − 0.853

\= 1.34 > 1, use λ = 1. = 1.34 > 1, use λ = 1.

Note: λ can always be conservatively taken as being equal to 1

λn ' = (1)( 3.11 in.) = 3.11 in.

l = max ( m, n, λn ') = max ( 4.97 in.,6.12 in.,3.11 in.) = 6.12 in.

<!-- p. 206 -->

J-16

LRFD ASD
Pu 690 kips Pa 460 kips f pu = = = 1.43 ksi f pa = = = 0.95 ksi BN ( 22 in.)( 22 in.) BN ( 22 in.)( 22 in.)

2 f pu 3.33 f pa
t p ( req ) = l t p ( req ) = l 0.9 Fy Fy

2 (1.43 ksi ) 3.33 ( 0.950 ksi ) = ( 6.12 in.) = ( 6.12 in.) 0.9 ( 36 ksi ) ( 36 ksi )

\= 1.82 in. = 1.82 in.

Use a 2 in. thick base plate.

<!-- p. 207 -->

K-1

CHAPTER K
Design of HSS and Box Member Connections

Examples K.1 through K.6 illustrate common beam to column shear connections that have been adapted for use
with HSS columns. Example K.7 illustrates a through plate shear connection, which is unique to HSS columns.
Calculations for transverse and longitudinal forces applied to HSS are illustrated in Examples K.8 and K.9. An
example of an HSS truss connection is given in Example K.10. Examples on HSS cap plate and base plate
connections are given in Examples K.11 through K.13.

<!-- p. 208 -->

K-2

Example K.1 Welded/bolted Wide Tee Connection to an HSS Column

Given:
Design a connection between a W16×50 beam and a HSS8×8×4 column using a WT5×24.5.
Use w-in. diameter ASTM A325-N bolts in standard holes with a bolt spacing, s, of 3 in.,
vertical edge distance Lev of 14 in. and 3 in. from the weld line to the bolt line. Design as a
flexible connection.

PD = 6.2 kips
PL = 18.5 kips

Note: A tee with a flange width wider than 8 in. was selected to provide sufficient surface for
flare bevel groove welds on both sides of the column, since the tee will be slightly offset from
the column centerline.

Solution:

Material Properties:
Beam ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Tee ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Column ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi

Geometric Properties:
Beam W16×50 tw = 0.380 in. d = 16.3 in. tf = 0.630 in. Manual
T = 13 s in. Tables
Tee WT5×24.5 ts = tw = 0.340 in. d = 4.99 in. tf = 0.560 in. 1-1, 1-8, and
bf = 10.0 in. k1 = m in. 1-12
Column HSS8×8×4 t = 0.233 in. B = 8.00 in.

Calculate the required strength

LRFD ASD
Pu = 1.2(6.20 kips) + 1.6(18.5 kips) Pa = 6.20 kips + 18.5 kips
\= 37.0 kips = 24.7 kips

<!-- p. 209 -->

K-3

Calculate the available strength assuming the connection is flexible

LRFD ASD
Determine the number of bolts Determine the number of bolts

Determine the single bolt shear strength Determine the single bolt shear strength Manual
φrn = 15.9 kips rn /Ω = 10.6 kips Table 7-1

Determine single bolt bearing strength based Determine single bolt bearing strength based
on edge distance on edge distance

Table J3.4 Lev = 14-in. ≥ 1.25 in. o.k. Lev = 14-in. ≥ 1.25 in. o.k.

Manual φrn = 49.4 kips/in.(0.340 in.) = 16.8 kips rn /Ω = 32.9 kips/in.(0.340 in.) = 11.2 kips
Table 7-6
Determine single bolt bearing capacity Determine single bolt bearing capacity
based on spacing based on spacing

s = 3.00 in. > 3(w) = 2.25 in. s = 3.00 in. > 3(w) = 2.25 in.

Manual φrn = 87.8 kips/in.(0.340 in.) = 29.8 kips rn /Ω = 58.5 kips/in.(0.340 in.) = 19.9 kips Table 7-5

Therefore bolt shear controls, Therefore bolt shear controls,
Pu 37.0 kips Pa 24.7 kips C min = = = 2.33 C min = = = 2.33
φrn 15.9 kips rn / Ω 10.6 kips

Using e = 3 in. and s = 3 in., determine C. Using e = 3 in. and s = 3 in., determine C.

Try 4 bolts, Try 4 bolts, Manual
C = 2.81 > 2.33 o.k. C = 2.81 > 2.33 o.k. Table 7-7

Check WT stem thickness limit
d b 1 ( 34 in.) 1 Manual t max = + 16 in. = + 16 in. = 0.438 in. > 0.340 in. o.k. Section 9
2 2
Note: beam web thickness is greater than WT stem thickness. If the beam web were thinner
than the WT stem, this check could be satisfied by checking the thickness of the beam web

Determine WT length required Manual
Section 10
A W16×50 has a T-dimension of 13s in.

Lmin = T/2 = (13s in.)/2 = 6.81 in.

Determine WT length required for bolt spacing and edge distances

L = 3(3.00 in.) + 2 (1.25 in.) = 11.5 in. \< T = 13s in. o.k.

Try L = 11.5 in.

<!-- p. 210 -->

K-4

Calculate the stem shear yielding strength

Rn = 0.6 Fy Ag = 0.6(50 ksi)(11.5in.)(0.340in.) = 117 kips Eqn. J4-3

LRFD ASD
117 kips
φRn = 1.00(117 kips) = 117 kips Rn / Ω= = 78.0 kips
1.5
117 kips > 37.0 kips o.k. 78.0 kips > 24.7 kips o.k.

Calculate the stem shear rupture strength
Section J4.2
Rn = [ L − n( d h + 1/16) ]( t )( 0.6 Fu )
\= [11.5 in. – 4(0.875 in.)](0.340 in.)(0.6)(65 ksi)
\= 106 kips

LRFD ASD
106 kips
φRn = 0.75(106 kips) = 79.6 kips Rn / Ω= = 53.0 kips
2.00
79.6 kips > 37.0 kips o.k. 53.0 kips > 24.7 kips o.k.

Calculate the stem available block shear rupture strength Section J4.3

For this case Ubs = 1.0

LRFD ASD
φFu Ant Fu Ant Manual = 76.2 kips/in. = 50.8 kips/in. Table 9-3a t t Ω
φ 0.6 Fy Agv 0.6 Fy Agv = 231 kips/in. = 154 kips/in. Manual
t t Ω Table 9-3b
φ 0.6 Fu Anv 0.6 Fu Anv = 210 kips/in. = 140 kips/in. Manual t t Ω
Table 9-3c
φRn = φ0.6FuAnv+φUbsFuAnt Rn 0.6Fu Anv U bs Fu Ant = + Eqn. J4-5
Ω Ω Ω
≤φ0.6FyAgv+φUbsFuAnt 0.6Fy Agv U bs Fu Ant ≤ +
Ω Ω

Rn / Ω= 0.340 in.(140 kips/in. +50.8 kips/in.) φRn=0.340 in.(210 kips/in + 76.2 kips/in)
≤0.340 in.(231kips/in.+76.2 kips/in.) ≤0.340 in.(154 kips/in.+50.8 kips/in.)
\=97.3 kips ≤104 kips = 64.9 kips ≤69.6 kips

97.3 kips > 37.0 kips o.k. 64.9 kips > 24.7 kips o.k.

Check stem bending

Calculate the required flexural strength

LRFD ASD
Mu = Pue = 37.0 kips(3.00 in.) = 111 kip-in. Ma = Pae = 24.7 kips(3.00 in.) = 74.1 kip-in.

<!-- p. 211 -->

K-5

Calculate the stem nominal flexural yielding strength

td 2 0.340in. (11.5in. ) 2 3Z = = = 11.2in.
4 4
td 2 0.340in. (11.5in. ) 2 3S = = = 7.49in.
6 6
M n = M p = Fy Z ≤ 1.6 M y Eqn F11-1
3 3 = 50 ksi (11.2in. ) ≤ 1.6 ( 50 ksi )( 7.49in. )
\= 560 kip-in. \< 599 kip-in. o.k.

Note: the 1.6 limit will never control, because the shape factor for a plate is 1.5

Calculate the stem available flexural yielding strength

LRFD ASD
560 kip-in.
φMn=0.90(560 kip-in.) M n / Ω=
1.67
\= 504 kip-in. > 111 kip-in. o.k. = 335 kip-in. > 74.1 kip-in. o.k.

Calculate the stem flexural rupture strength

td 2Z net = − 2 t ( d h + z in. )(1.5in. + 4.5in. ) Manual 4
2 Part 9
0.340in. (11.5in. ) 3 = − 2 ( 0.340in. )( m in. + z in. )(1.5in. + 4.5in. ) = 7.67in.
4

3M n = Fu Z net = 65ksi ( 7.67in. ) = 499kip-in.

LRFD ASD
499 kip-in.
φMn=0.75(499 kip-in.) M n / Ω=
2.00
\= 374 kip-in. > 111 kip-in. o.k. = 250 kip-in. > 74.1 kip-in. o.k.

Check beam web bearing

t w > t s → 0.380 in. > 0.340 in.

Beam web is satisfactory for bearing by comparison with WT.

Calculate weld size Table J2.2

Since the flange width of the WT is larger than the width of the HSS, a flare bevel groove
weld is required. Taking the outside radius as 2(4 in.) = 2 in. and using AISC Specification
Table J2.2, the effective throat thickness of the flare bevel weld is E = c(2 in.) = 0.156 in.

<!-- p. 212 -->

K-6

The equivalent fillet weld that provides the same throat dimension is

⎛ D ⎞ ⎛ 1 ⎞ 0.156 ) = 3.53 sixteenths of an inch⎜ ⎟⎜ ⎟ = 0.156 → D = 16 2 (⎝ 16 ⎠⎝ 2 ⎠

The equivalent fillet weld size is used in the following calculations

Check weld ductility Manual
Section 9
fb − 2 k1 8.00 in. − 2 ( m in. ) b = = = 3.19 in.
2 2
Fyc t f 2 ⎛ b 2 ⎞
\+ 2 ≤ 16 ( 0.625t s ) wmin = ( 0.0158 ) ⎜ 2 ⎟ b ⎝ L ⎠
( 50 ksi )( 0.560 in. ) 2 ⎡ ( 3.19 in.) 2 ⎤ = ( 0.0158 ) ⎢ 2 + 2 ⎥ ≤ ( 0.625)( 0.340 in.)
3.19 in. ⎢ ⎣ ( 11.5 in.) ⎥⎦
\= 0.161 in. \< 0.213 in.

0161 in. = 2.58 sixteenths of an in.

Dmin = 2.58 \< 3.53 sixteenths of an in. o.k.

Calculate the nominal weld shear strength

The load is assumed to act concentrically with the weld group.

a = 0, therefore, C = 3.71
Manual
Rn=CC1Dl=3.71(1.00)(3.53 sixteenths of an in.)(11.5 in.) = 151 kips Table 8-4

Check shear rupture in HSS at weld Manual
Section 9
3.09 D 3.09 ( 3.53 sixteenths )
t min = = = 0.188 in.
Fu 58 ksi
Therefore the weld controls

Calculate the available weld strength

LRFD ASD
φ = 0.75 Ω= 2.00
φRn = 0.75(151 kips) Rn / Ω= 151kips / 2.00
\= 113 kips > 37.0 kips o.k. = 75.3 kips > 24.7 kips o.k.

<!-- p. 213 -->

K-7

Example K.2 Welded/bolted Narrow Tee Connection to an HSS Column

Given:
Design a connection for a W16×50 beam to an HSS8×8×4 column using a tee with fillet welds against the flat
width of the HSS. Use w-in. diameter A325-N bolts in standard holes with a bolt spacing, s, of 3.00 in., vertical
edge distance Lev of 14-in. and 3.00 in. from the weld line to the center of the bolt line. Design this as a
connection to a flexible support. Assume that, for architectural purposes, the flanges of the WT from the previous
example have been stripped down to a width of 6.5 in.

PD = 6.2 kips
PL = 18.5 kips

Note: This is the same problem as Example K.1 with the exception that a narrow tee will be selected which will
permit fillet welds on the flat of the column. The beam will still be centered; therefore the tee will be slightly
offset.

Solution:

Material Properties:
Beam ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Tee ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Column ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi

Geometric Properties:
Beam W16×50 tw = 0.380 in. d = 16.3 in. tf = 0.630 in. Manual
Column HSS8×8×4 t = 0.233 in. B = 8.00 in. Tables 1-1
Tee WT5×24.5 ts = tw = 0.340 in. d = 4.99 in. tf = 0.560 in. and 1-12
k1 = m in.

Calculate the required strength

LRFD ASD
Pu = 1.2(6.20 kips) + 1.6(18.5 kips) Pa = 6.20 kips + 18.5 kips
\= 37.0 kips = 24.7 kips

<!-- p. 214 -->

K-8

Verify the strength of the WT

Maximum flange width assuming 4-in. welds and HSS corner radius equal to 1.5 times the
nominal thickness (1.5)(4 in.) = a in.

1 4 in. ) = 6.75 in.fb ≤ 8.00in. − 2( 3 8 in.) − 2 (

The strength of the stem thickness was verified in Example K.1.

Determine the number of bolts

LRFD ASD
Determine the bolt shear strength Determine the bolt shear strength Manual
φrn = 15.9 kips rn /Ω = 10.6 kips Table 7-1

Determine bolt bearing strength based on Determine bolt bearing strength based on
edge distance edge distance
Lev = 14-in. ≥ 1.25 in. Lev = 14-in. ≥ 1. 25 in. Table J3.4

Manual φrn = 49.4 kips/in.(0.340 in.) = 16.8 kips rn /Ω = 32.9 kips/in.(0.340 in.) = 11.2 kips
Table 7-6
Bolt shear strength controls Bolt shear strength controls

Determine the coefficient for the eccentrically loaded bolt group

LRFD ASD
φrn = 15.9 kips rn /Ω = 10.6 kips Manual
Table 7-7
Pu 37.0 kips Pa 24.7 kips C min = = = 2.33 C min = = = 2.33
φrn 15.9 kips rn / Ω 10.6 kips

Using e = 3.00 in. and s = 3.00 in., enter Using e = 3.00 in. and s = 3.00 in., enter
Manual Table 7-7 Manual Table 7-7

Try 4 bolts, Try 4 bolts,

C = 2.81 > 2.33 o.k. C = 2.81 > 2.33 o.k.

Determine the minimum fillet weld size based on the thinner part

Minimum size = 8 in. (D = 2) for welding to 4 in. material Table J2.4

Check weld ductility

5 5 3 4 in. − 2 ( ( fb − 2 k1 ) ⎡⎣ 8 in.) ⎤⎦ Manualb = = = 2 14 in. Part 9
2 2
Fyc t f 2 ⎛ b 2 ⎞
\+ 2 ≤ ( 0.625t s )wmin = ( 0.0158 ) ⎜ 2 ⎟ b ⎝ L ⎠

<!-- p. 215 -->

K-9

( 50 ksi )( 0.360in.) 2 ⎡ ( 2 14 in.) 2 ⎤ ⎢ + 2 ⎥ = ( 0.0158 ) ≤ ( 0.625)( 0.240 in.)
2 1 4 in. ⎢ ⎥ 11 1 2 in.) 2 ⎣ ( ⎦

\= 0.093 in. ≤ 0.150 in.

Dmin = 0.093(0.625) = 0.058 sixteenths of an in. \< 2 o.k.

Calculate minimum wall thickness in HSS to match weld strength Manual
Section 9
3.09 D 3.09 ( 2 )
t min = = = 0.107 in. \< 0.233 in.
Fu 58 ksi

Therefore weld controls

Calculate the weld nominal shear strength

The load is assumed to act concentrically with the weld group.

a = 0; therefore C = 3.71

Rn=CC1Dl=3.71(1.00)(2 sixteenths of an in.)(11.5 in.) = 85.3 kips Manual
Table 8-4
Calculate the available weld shear strength

LRFD ASD
φ = 0.75 Ω= 2.00
85.3 kips
φRn = 0.75(85.3 kips) = 64.0 kips Rn / Ω= = 42.7 kips
2.00
64.0 kips > 37.0 kips o.k. 42.7 kips > 24.7 kips o.k.

Note: Use a x-in. fillet weld as a practical minimum.

<!-- p. 216 -->

K-10

Example K.3 Double Angle Connection to an HSS Column

Given:
Use Tables 10-1 and 10-2 to design a double-angle connection for a W36×231 beam to an
HSS14×14×2 column. Use w-in. diameter ASTM A325-N bolts in standard holes.

PD = 37.5 kips
PL = 113 kips

Solution:

Material Properties:
Beam ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column ASTM A500 Gr. Fy = 46 ksi Fu = 58 ksi Table 2-3
Angles ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:
Beam W36×231 tw = 0.760 in. Manual
Column HSS14×14×2 t = 0.465 in. B = 14.0 in. Tables 1-1
and 1-12

Compute the required strength

LRFD ASD
Ru = 1.2(37.5 kips) + 1.6(113 kips) Ra = 37.5 kips + 113 kips
\= 225 kips = 151 kips

<!-- p. 217 -->

K-11

Design bolts and welds

Try 8 rows of bolts and c-in. welds B

Obtain the bolt group and angle available strengths from Table 10-1

LRFD ASD
φRn = 254 kips > 225 kips o.k. Rn /Ω = 170 kips > 151 kips o.k. Manual
Table 10-1

Obtain the available weld strength from Table 10-2

LRFD ASD
φRn = 279 kips > 225 kips o.k. Rn /Ω= 186 kips > 151 kips o.k. Manual
Table 10-2

Check the minimum support thickness
Manual
Minimum support thickness = 0.238 in. \< 0.465 in. o.k. Table 10-2

Calculate the minimum angle thickness

t min = w + z = c + z = a in. Section
J2.2b
Use a-in. angle thickness to accommodate the welded legs of the double angle connection.

Use 2L4×32 ×a×1’-112”.

L = 23.5 in. > T/2 o.k.

B of the HSS is greater than 12 in., the minimum acceptable width for 4-in. OSL angles.

Calculate the available beam web strength

LRFD ASD
φRn = (702 kips/in.)(0.760 in.) = 534 kips Rn /Ω = (468 kips/in.)(0.760 in.) = 356 kips Manual
534 kips > 225 kips o.k. 356 kips > 151 kips o.k. Table 10-1

<!-- p. 218 -->

K-12

Example K.4 Unstiffened Seated Connection to an HSS Column

Given:
Use Table 10-6 to design an unstiffened seated connection for a W21×62 beam to an
HSS12×12×2 column.

PD = 9 kips
PL = 27 kips

Solution:

Material Properties:
Beam ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Table 2-3
Angles ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:
Beam W21×62 tw = 0.400 in. d = 21.0 in. k = 1.12 in. Manual
Column HSS12×12×2 t = 0.465 in. B = 12.0 in. Tables 1-1
and 1-12

Calculate the required strength

LRFD ASD
Ru = 1.2(9.00 kips) + 1.6(27.0 kips) Ra = 9.00 kips + 27.0 kips
\= 54.0 kips = 36.0 kips

<!-- p. 219 -->

K-13

Design the seat angle and weld
LRFD ASD
Check local web yielding Check local web yielding Manual
Table 9-4
Ru −φR1 Ra − R1 / Ω Manual
N min = ≥ k N min = ≥ k Section 10 φR2 R2 / Ω
54.0 kips − 55.8 kips 36.0 kips − 37.2 kips
\= ≥ 1.12 in. = ≥ 1.12 in.
20.0 kips/in. 13.3 kips/in.

Use Nmin = 1.12 in. Use Nmin = 1.12 in.

Check web crippling when N / d M 0.2, Check web crippling when N / d M 0.2,

Ru −φR3 54.0 kips − 71.7 kips Ra − R3 / Ω 36.0 kips − 47.8 kips N min = = N min = =
φR4 5.37 kips/in. R4 / Ω 3.58 kips/in.
which results in a negative quantity. which results in a negative quantity.

Check web crippling when N / d > 0.2, Check web crippling when N / d > 0.2,
Ru −φR5 54.0 kips − 64.2 kips Ra − R5 / Ω 36.0 kips − 42.8 kips N min = = N min = =
φR6 7.16 kips/in. R6 / Ω 4.78 kips/in.
which results in a negative quantity. which results in a negative quantity.

Note: Generally, the value of N/d is not initially known and the larger value determined from
the web crippling equations above can be used conservatively to determine the bearing length
required for web crippling.

For this beam and end reaction, the beam web strength exceeds the required strength (hence
the negative bearing lengths) and the lower-bound bearing length controls (Nreq = k = 1.12 in.).
Thus, Nmin = 1.12 in.

Try a L8×4×s with c in. fillet welds.

Determine outstanding angle leg available strength

LRFD ASD
φRn = 81.0 kips Rn / Ω= 53.9 kips Manual
Table 10-6 81.0 kips > 54.0 kips o.k. 53.9 kips > 36.0 kips o.k.

Determine weld available strength

LRFD ASD
φRn = 66.7 kips > 54.0 kips o.k. Rn / Ω= 44.5 kips > 36.0 kips o.k. Manual
Table 10-6

Since the t of the HSS is greater than the tmin for the c-in. weld, no reduction in the weld
strength is required to account for the shear in the HSS.

Connection to beam and top angle

Use a L4×4×4 in. top angle. Use x-in. fillet weld across the toe of the angle for attachment to Manual
the HSS. Attach both the seat and top angles to the beam flanges with two w-in. diameter Part 10
ASTM A325-N bolts.

<!-- p. 220 -->

K-14

Example K.5 Stiffened Seated Connection to an HSS Column

Given:
Use Manual Tables 10-8 and 10-14 to design a stiffened seated connection for a W21×68 beam
to a HSS12×12×2 column.

PD = 20 kips
PL = 60 kips

Use w-in. diameter ASTM A325-N bolts in standard holes to connect the beam to the seat
plate.
Use 70 ksi electrode welds to connect the stiffener, seat plate and top angle to the HSS.

Solution:

Material Properties:
Beam ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Table 2-3
Angles and Plates ASTM A36 Fy = 36 ksi Fu = 58 ksi

<!-- p. 221 -->

K-15

Geometric Properties: Manual
Beam W21×68 tw = 0.430 in. d = 21.1 in. k = 1.19 in. Tables 1-1
Column HSS12×12×2 t = 0.465 in. B = 12.0 in. and 1-12

Check limits of applicability for Specification Section K1

Strength: Fy = 46 ksi \< 52 ksi o.k. Section K1.2
Fy 46 ksi
Ductility: = = 0.79 \< 0.80 o.k.
Fu 58 ksi

Calculate the required strength

LRFD ASD
uP = 1.2 ( 20.0 kips ) + 1.6 ( 60.0 kips ) aP = 20.0 kips + 60.0 kips
\= 120 kips = 80.0 kips

Determine stiffener width W required for web crippling and local web yielding

For web crippling, assume N/d > 0.2 and use constants R5 and R6 from Manual Table 9-4. Manual
Assume a w-in. setback. Section 10

LRFD ASD
Ru −φR5 Ra − R5 / Ω Manual
Wmin = + setback ≥ k + setback Wmin = + setback ≥ k + setback Table 9-4 φR6 R6 / Ω
120 kips − 75.9 kips 3 80.0 kips − 50.6 kips 3 = + 4 in. = + 4 in.
7.94 kips/in. 5.29 kips/in.
\= 6.31 in. = 6.34 in.

For local web yielding, use constants R1 and R2 from Manual Table 9-4. Assume a w-in.
setback.

LRFD ASD
Ru −φR1 Ra − R1 / Ω Manual
Wmin = + setback Wmin = + setback Table 9-4 φR2 R2 / Ω
126 kips − 63.7 kips 3 84.0 kips − 42.5 kips 3 = + 4 in. = + 4 in.
21.5 kips/in. 14.3 kips/in.
\= 3.65 in. = 3.65 in.

The minimum stiffener width, W, for web crippling controls. Use W = 7.00 in.

Check bearing width assumption

N = 7.00 in. − 3 4 in. = 6 1 4 in.
6 14 in.N / d = = 0.30 > 0.2, as assumed.
21.1 in.

Determine the weld strength requirements for the seat plate

Try L = 24 in. with c in. fillet welds. Enter Manual Table 10-8 using W = 7 in. as
determined above.

<!-- p. 222 -->

K-16

LRFD ASD Manual
φRn = 293 kips > 126 kips o.k. Rn / Ω= 195 kips > 84.0 kips o.k. Table 10-8

Since t of the HSS is greater than tmin for the c-in. weld, no reduction in the weld strength to
account for shear in the HSS is required.

The minimum length of the seat-plate-to-HSS weld on each side of the stiffener is 0.2L = 4.8 Manual
in. This establishes the minimum weld between the seat plate and stiffener; use 5 in. of c-in. Section 10
weld on each side of the stiffener.

Determine the stiffener plate thickness

To develop the stiffener-to-seat plate welds, the minimum stiffener thickness is

5 5 8 in. 16 in.) =pt min = 2 w = 2 (

For a stiffener with Fy = 36 ksi and a beam with Fy = 50 ksi, the minimum stiffener thickness,
⎛ Fybeam ⎞ ⎛ 50 ksi ⎞ t p min = ⎜ ⎟ t w = ⎜ ⎟ ( 0.430 in. ) = 0.597 in. ⎜ ⎟ ⎝ Fy stiffener ⎠ ⎝ 36 ksi ⎠

For a stiffener with Fy = 36 ksi and a column with Fu = 58 ksi, the maximum stiffener
thickness is
Fu t 58 ksi ( 0.465 in.) t p max = = = 0.749 in.
Fyp 36 ksi Eqn. K1-10

Use stiffener thickness of s in.

Determine the stiffener length using Manual Table 10-14

LRFD ASD
⎛ Ru W ⎞ 120 kips ( 7.00in.) ⎛ Ra W ⎞ 80.0 kips ( 7.00in.)
⎜ 2 ⎟ = 2 ⎜ 2 ⎟ = 2 ⎝ t ⎠ req ( 0.465in.) ⎝ t ⎠ req ( 0.465in.)
\= 4100 kips/in. = 2720 kips/in.

To satisfy the minimum above, select a To satisfy the minimum above, select a
stiffener L = 24 in. from Table 10-14 stiffener L = 24 in. from Table 10-14
Manual
RuW RaW Table 10-14
2 = 4310 kips/in. > 4100 kips/in. o.k. 2 = 2870 kips/in. > 2720 kips/in. o.k. t t

Use PLs×7×2’-0 for the stiffener.

Check the HSS width

The minimum width is 0.4L + tp + 3t

B = 12.0 in. > 0.4 ( 24.0 in. ) + 58 in. + 3 ( 0.465 in. ) = 11.6 in.

<!-- p. 223 -->

K-17

Determine the seat plate dimensions

To accommodate two w-in. diameter ASTM A325-N bolts on a 52 in. gage connecting the
beam flange to the seat plate, a width of 8 in. is required. To accommodate the seat-plate-toHSS weld, the required width is:
Manual
0.4 ( 24 in.) + 0.625 in. = 10.2 in. Part 10

Note: To allow room to start and stop welds, an 11.5 in. width is used.

Use PLa×7×0’-112 for the seat plate.

Select the top angle, bolts and welds

The minimum weld size for the HSS thickness according to Specification Table J2.4 is x in.
The angle thickness should be z in. larger.

Use L4×4×4 with x-in. fillet welds along the toes of the angle to the beam flange and HSS.
Alternatively two w-in. diameter ASTM A325-N bolts may be used to connect the beam leg of
the angle to the beam flange.

<!-- p. 224 -->

K-18

Example K.6 Single-Plate Connection to Rectangular HSS Column

Given:
Use Manual Table 10-9 to design a single-plate connection for between a W18×35 beam and a
HSS6×6×a column.

PD = 6.5 kips
PL = 19.5 kips

Use w-in. diameter ASTM A325-N bolts in standard holes and 70 ksi weld electrode.

Solution:

Material Properties:
Beam ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Tables 2-3
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties: Manual
Beam W18×35 d = 17.7 in. tw = 0.300 in. T = 152 in. Tables 1-1
Column HSS6×6×a B = H = 6.00 in. t = 0.349 in. b/t = 14.2 and 1-12

Determine applicability of Specification Section K1

Strength: Fy = 46 ksi \< 52 ksi o.k.
Section K1.2
Fy 46 ksi
Ductility: = = 0.79 \< 0.80 o.k.
Fu 58 ksi

Determine if a single plate connection is suitable (the HSS wall is not slender)
E 29,000 ksi
Slenderness: λ = 1.40 = 1.40 = 35.2 > 14.2 o.k. Table B4.1
Fy 46 ksi Case 12

<!-- p. 225 -->

K-19

Calculate the required strength

LRFD ASD
Ru = 1.2 ( 6.50 kips ) + 1.6 (19.5 kips ) Ra = 6.50 kips + 19.5 kips
\= 39.0 kips = 26.0 kips

Calculate maximum single-plate thickness

Fu t 58 ksi(0.349 in.)
t p max = = = 0.562 in. Eqn. K1-10 Fyp 36 ksi
Note: Limiting the single-plate thickness precludes a shear yielding failure of the HSS wall. Section K1.5

Design the single-plate connection

Try 3 bolts and a c-in. plate thickness with 4-in. fillet welds.

pt = 516 in. \< 0.562 in. o.k.

Obtain the available single plate connection strength from Manual Table 10-9

LRFD ASD Manual
φRn = 47.7 kips > 39.0 kips o.k. Rn / Ω= 31.8 kips > 26.0 kips o.k. Table 10-9

Use a PLc×42×0’-9”

Check HSS shear rupture strength at welds
Manual
6.19 D 6.19 ( 4 ) Section 9
t min = = = 0.427 in. > t = 0.349 in. n.g.
Fu 58 ksi

Since t \< t min, the shear rupture strength of the HSS is less than the weld strength. Consider
reducing the weld size to x in.

6.19 D 6.19 ( 3 )
t min = = = 0.320 in. \< t = 0.349 in. o.k.
Fu 58 ksi

<!-- p. 226 -->

K-20

Determine the weld shear strength

This is the special case where the load is not in the plane of the weld group. Use k = 0. Manual
Table 8-4
e 3.00 in.
a = = = 0.333 Therefore C = 2.95 (interpolated)
l 9.00 in.

Rn=CC1Dl=2.95(1.00)(3 sixteenths of an in.)(9.00 in.) = 79.6 kips

Calculate the available weld shear strength

LRFD ASD
φ = 0.75 Ω= 2.00
79.6 kips
φRn = 0.75(79.6 kips) = 59.7 kips Rn / Ω= = 39.8 kips
2.00
59.7 kips > 39.0 kips o.k. 39.8 kips > 26.0 kips o.k.

Calculate the available beam web bearing strength from Manual Table 10-1

For three w-in. diameter bolts

LRFD ASD
φRn = ( 263 kips/in.)( 0.300 in.) Rn / Ω= (175 kips/in.)( 0.300 in.) Manual
Table 10-1 = 78.9 kips > 39.0 kips o.k. = 52.5 kips > 26.0 kips o.k.

<!-- p. 227 -->

K-21

Example K.7 Through-Plate Connection

Given:
Use Table 10-9 to design a through-plate connection between a W18×35 beam and a
HSS6×4×8 with the connection to one of the 6 in. faces. A thin-walled column is used to
illustrate the design of a through-plate connection.

PD = 6.5 kips
PL = 19.5 kips

Use w-in. diameter ASTM A325-N bolts in standard holes and 70 ksi weld electrode.

Solution:

Material Properties:
Beam ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Tables 2-3
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties: Manual
Beam W18×35 d = 17.7 in. tw = 0.300 in. T = 152 in. Tables 1-1
Column HSS6×4×8 B = 4.00 in. H = 6.00 in. t = 0.116 in. and 1-11
h/t = 48.7

Determine applicability of Specification Section K1

Strength: Fy = 46 ksi \< 52 ksi o.k. Section K1.2
Fy 46 ksi
Ductility: = = 0.79 \< 0.80 o.k.
Fu 58 ksi

Determine if a single-plate connection is suitable (HSS wall is not slender)
E 29,000 ksi
Slenderness: λ = 1.40 = 1.40 = 35.2 \< 48.7 n.g. Table B4.1
Fy 46 ksi Case 12
Since the HSS6×4×8 is slender, a through-plate connection should be used instead of a
single-plate connection. Through plate connections are typically very expensive. When a
single-plate connection is not adequate, another type of connection, such as a double-angle

<!-- p. 228 -->

K-22

connection may be preferable to a through-plate connection.

Calculate the required strength

LRFD ASD
Ru = 1.2 ( 3.30 kips ) + 1.6 ( 9.90 kips ) Ra = 3.30 kips + 9.90 kips
\= 19.8 kips = 13.2 kips

Design the portion of the through-plate connection that resembles a single-plate

Try 3 rows of bolts (L=82) and a 4 in. plate thickness with x-in. fillet welds.

Obtain the available single plate connection strength from Manual Table 10-9

LRFD ASD Manual
φRn = 38.3 kips > 19.8 kips o.k. Rn / Ω= 25.6 kips > 13.2 kips o.k. Table 10-9a

Check weld size for through-plate connection

e = 3.00 in.
6.19 D 6.19 ( 3 )
t min = = = 0.320 in. > 0.116 in. (proration required)
Fu 58ksi

Calculate the required weld strength

LRFD ASD
Ru ( B + e ) Ra ( B + e )
V fu = V fa =
B B
(19.8 kips )( 4.00 in. + 3.00 in. ) (13.2 kips )( 4.00 in. + 3.00 in. ) = =
4.00 in. 4.00 in.
\= 34.7 kips = 23.1 kips

V fu 34.7 kips V fa 23.1 kips
v fu = = = 4.08 kips/in. v fa = = = 2.72 kips/in.
L 8.50 in. L 8.50 in.

Calculate the available weld strength

LRFD ASD
⎛ t ⎞ ⎛ t ⎞ Manual
φrn = 1.392 Dnw ⎜ ⎟ φrn = 0.928 Dnw ⎜ ⎟ Part 9 ⎝ t min ⎠ ⎝ t min ⎠
⎛ 0.116 in. ⎞ ⎛ 0.116 in. ⎞ = 1.392 ( 3)( 2 welds ) ⎜ ⎟ = 0.928 ( 3)( 2 welds ) ⎜ ⎟ ⎝ 0.320 in. ⎠ ⎝ 0.320 in. ⎠
\= 3.03 kips/in. \< 4.08 kips/in. n.g. = 2.02 kips/in. \< 2.72 kips/in. n.g.

A deeper plate is required. A deeper plate is required.

V fu 34.7 kips V fa 23.1 kips
Lreq = = = 11.5 in. Lreq = = = 11.5 in.
φrn 3.03 kips/in. rn / Ω 2.02 kips/in.

<!-- p. 229 -->

K-23

Use an 112 in. long plate and increase the vertical edge distance to 2w in.

Recheck the plate length

L = 112 in. \< T = 152 in. o.k.

Calculate the available beam web bearing strength

For three w in. diameter bolts

LRFD ASD
φRn = ( 263 kips/in. )( 0.300 in. ) Rn / Ω= (175 kips/in. )( 0.300 in. ) Manual
Table 10-1 = 78.9 kips > 19.8 kips o.k. = 52.5 kips > 13.2 kips o.k.

<!-- p. 230 -->

K-24

Example K.8 Transverse Plate Loaded Perpendicular to the HSS Axis on a
Rectangular HSS.

Given:
Verify the local strength of the HSS column subject to the transverse loadings given below,
applied through a 5 in. wide plate. The HSS 8×8×2 is in compression with nominal axial
loads of PD column = 54 kips and PL column = 162 kips. The HSS has negligible flexural required
strength and the connecting member is 4 in. wide.

Solution:

Material Properties:
Column ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Manual
Plate ASTM A36 Fyp = 36 ksi Fu = 58 ksi Table 2-3
Table 2-4
Geometric Properties:
Column HSS8×8×2 B = 8.00 in. t = 0.465 in. Manual
Plate Bp = 5.50 in. tp = 0.500 in. Table 1-12

Check the limits of applicability of Specification Section K1

\1) Strength: Fy less than or equal to 52 ksi for HSS Fy = 46 ksi o.k. Section K1.2
\2) Ductility: Fy/Fu ≤0.8 for HSS Fy/Fu= 0.79 o.k.
\3) 0.25 \< Bp/B \< 1.0 Bp/B = 0.69 o.k. Section
\4) B/t ≤ 35 B/t=17 o.k. K1.3b

Calculate the required strength

LRFD ASD
Transverse force from the plate Transverse force from the plate
Pu = 1.2(10.0 kips) + 1.6(30.0 kips) Pa = 10.0 kips + 30.0 kips
\= 60.0 kips = 40.0 kips

Column axial force Column axial force
Pr = Pu column Pr = Pa column
\= 1.2(54.0 kips) + 1.6(162 kips) = 54.0 kips + 162 kips
\= 324 kips = 216 kips

<!-- p. 231 -->

K-25

Calculate available local yielding strength for uneven load distribution in the loaded plate

⎡ ⎤
⎢ 10 Fy t ⎥
Rn = ⎢ ⎥ B p ≤ Fyp t p B p Eqn. K1-2
⎢ ⎛ B ⎞ ⎥
⎢ ⎜ ⎟ ⎥ ⎣ ⎝ t ⎠ ⎦
⎡ ⎤
⎢ ⎥ 10(46 ksi)(0.465 in.)
Rn = ⎢ ⎥ 5.50 in. ≤ 36 ksi(0.500 in.)(5.50 in.)
⎢ ⎛ 8.00 in. ⎞ ⎥
⎢ ⎜ ⎟ ⎥ ⎣ ⎝ 0.465 in. ⎠ ⎦
\= 68.4 kips ≤ 99.0 kips o.k.

LRFD ASD
φ = 0.95 Ω= 1.58 Section
68.4 kips K1.3b
φRn = 0.95(68.4 kips) = 65.0 kips Rn / Ω= = 43.3 kips
1.58
65.0 kips > 60.0 kips o.k. 43.3 kips > 40.0 kips o.k.

Check shear yielding (punching)

This limit state does not control when Bp > B-2t, nor when Bp \< 0.85B. Section
K1.3b(b)
B-2t= 8.00 in. – 2(0.500 in.)= 7.00 in.

0.85B= 0.85(8.00 in.) = 6.80 in.

Therefore, since Bp\<6.80 in. this limit state does not control.

Check sidewall strength

This limit state does not control unless the chord member and branch member (connecting Section
element) have the same width. K1.3b(c)

Therefore, since Bp\<6.80 in. this limit state does not control.

<!-- p. 232 -->

K-26

Example K.9 Longitudinal Plate Loaded Perpendicular to the HSS Axis on
a Round HSS.

Given:
Verify the local strength of the HSS tension member subject to the transverse loadings given
below, applied through a 4 in. wide plate. The HSS6.000×0.375 is in tension with PD = 4 kips
and PL = 12 kips.

Solution:

Material Properties:
Column ASTM A500 Gr. B Fy = 42 ksi Fu = 58 ksi Manual
Plate ASTM A36 Fyp = 36 ksi Fu = 58 ksi Table 2-3
Table 2-4
Geometric Properties:
Column HSS6.000×0.375 D = 6.00 in. t = 0.349 in. Manual
Plate N = 4.00 in. Table 1-13

Check the limits of applicability of Specification Section K1

\1) Strength: Fy less than or equal to 52 ksi for HSS Fy = 42 ksi o.k. Section K1.2
\2) Ductility: Fy/Fu ≤ 0.8 for HSS Fy/Fu= 0.72 o.k. Section
\3) D/t ≤ 50 for T-connections D/t=17.2 o.k. K1.4a

Calculate the required strength

LRFD ASD
Pu = 1.2(4.00 kips) + 1.6(12.0 kips) Pa = 4.00 kips + 12.0 kips
\= 24.0 kips = 16.0 kips

Check the limit state of chord plastification

2 ⎛ 0.25 N ⎞
Rn = 5.5 Fy t ⎜ 1 + ⎟ Q f Eqn. K1-8 ⎝ D ⎠

Since the column is in tension, Qf = 1.0

2 ⎛ 0.25(4.00 in.) ⎞
Rn = 5.5(42 ksi)(0.349 in.) ⎜ 1 + ⎟ 1.0 = 32.8 kips Eqn. K1-8
⎝ 6.00 in. ⎠

<!-- p. 233 -->

K-27

LRFD ASD

32.8 kips
φRn = 0.90(32.8 kips) = 29.5 kips Rn / Ω= =19.6 kips Section
1.67 K1.4a
29.5 kips > 24.0 kips o.k. 19.6 kips > 16.0 kips o.k.

<!-- p. 234 -->

K-28

Example K.10 HSS Brace Connection to a W-shape Column.

Given:
Design the connection shown below. The required axial strength in the brace is 80 kips
(LRFD) and 52 kips (ASD). The axial force may be either tension or compression. The length
of the brace is 6 ft.

Solution:

Material Properties:
Brace ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Manual
Plate ASTM A36 Fyp = 36 ksi Fu = 58 ksi Table 2-3

Geometric Properties:
Brace HSS32×32×4 Ag = 2.91 in.2 r = 1.32 in. t = 0.233 in. Manual
Plate t = 0.375 in. Table 1-12

<!-- p. 235 -->

K-29

Obtain the available axial compression strength of the brace from Manual Table 4-4

K = 1.0
Lb = 6.00 ft

LRFD ASD
φcPn = 98.4 kips Pn/Ωc = 65.4 kips Manual
98.4 kips > 80.0 kips o.k. 65.4 kips > 52.0 kips o.k. Table 4-4

Obtain the available tension yielding strength of the brace from Manual Table 5-5

LRFD ASD
φtPn = 120 kips Pn/Ωt = 80.2 kips Manual
120 kips > 80.0 kips o.k. 80.2 kips > 52.0 kips o.k. Table 5-5

Calculate the tensile rupture strength of the brace

3 8 + 116 ) = 2.71 in.4An= Ag – 2 ( wt )( slot ) = 2.91 - 2 ( 0.233)(

1 1 1 B 2 + 2 BH ( 3 2 in. ) 2 + 2 ( 3 2 in. )( 3 2 in. ) Table D3.1
x = = = 1.31 in.
1 4( B + H ) 4 ( 3 2 in. + 3 1 2 in. )

8w in. of overlap occurs. Try four x-in. fillet welds, each 7-in. long

x 1.31 in.
U = 1- = 1- = 0.813
l 7.00 in.

Ae = UAn = 0.813(2.71 in.2) = 2.20 in.2

Eqn. D2-2Pn = FuAe = 58 ksi(2.20 in.2) = 128 kips

Calculate the available tension rupture strength

LRFD ASD
φt = 0.75 Ωt = 2.00
φtPn = 0.75(128 kips) = 95.8 kips Pn/Ωt = (128 kips)/2.00 = 63.9 kips
95.8 kips > 80.0 kips o.k. 63.9 kips > 52.0 kips o.k.

Calculate available strength of x-in. weld of HSS to plate

LRFD ASD

kips/in. φRn =4(7 in.)(3 sixteenths)(1.392 kips/in. sixteenth ) Rn =4(7in.)(3 sixteenths)(0.928 sixteenth ) Ω
\= 117 kips > 80.0 kips o.k. = 78.0 kips > 52.0 kips o.k.

<!-- p. 236 -->

K-30

Calculate the available strength of the weld of gusset plate to column

The slope of the member relative to the longitudinal weld along the column is 50 degrees.
Therefore the standard values for longitudinal fillet welds can be increased by:
(1.0 + 0.50 sin 1.5 θ ) = 1.34
or 34-percent.

Minimum weld is x-in. fillet each side. Therefore:

LRFD ASD
φRn = 2(16.0 in.)(3)(1.392)(1.34) Rn/Ω = 2(16.0 in.)(3)(0.928)(1.34)
\= 179 kips > 80.0 kips o.k. = 119 kips > 52.0 kips o.k.

<!-- p. 237 -->

K-31

Example K.11 Rectangular HSS Column with a Cap Plate, Supporting a
Continuous Beam.

Given:
Verify the strength of the HSS column subject to the given gravity beam reactions through the cap plate. Out of
plane stability of the column top is provided by the stiffeners shown. The column axial forces are RDL = 24 kips
and RLL = 30 kips.

Solution:

Material Properties:
Beam ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Table 2-3
Cap Plate ASTM A36 Fyp = 36 ksi Fu = 58 ksi

Geometric Properties:
Beam W18×35 d = 17.7 in. bf = 6.00 in. tw = 0.300 in. Manual
tf = 0.425 in. k1 = 0.750 in. Table 1-1
Column HSS8×8×4 t = 0.233 in. Manual
Cap Plate t = 0.500 in. Table 1-12

Calculate the required strength

LRFD ASD
Ru = 1.2(24.0 kips) + 1.6(30.0 kips) Ra = 24.0 kips + 30.0 kips
\= 76.8 kips = 54.0 kips

Assume the vertical beam reaction is transmitted to the HSS through bearing of the cap plate at
the two column faces perpendicular to the beam.

Calculate bearing length, N, at bottom of W18×35 Section K1.6

N = 2k1 + 5tf = 2(0.750 in.) + 5(0.425 in.) = 3.63 in.

Check limit for number of HSS faces contributing

5pt + N = 5 ( 0.500in. ) + 3.63in.=6.13in. \< 8.00 in. therefore, only 2 walls contribute

<!-- p. 238 -->

K-32

Calculate the nominal local wall yielding strength of the HSS

For each of the two walls:
Rn = Fy t ( 5t p + N ) ≤ BFy t
Eqn. K1-11
\= 46 ksi ( 0.233in. ) ( 5 ( 0.500in. ) + 3.63in. ) ≤ 8.00in. ( 46 ksi )( 0.233in. )
65.7kips ≤ 85.7kips

Use Rn = 65.7 kips per wall

Calculate the available local wall yielding strength of the HSS

LRFD ASD
φ= 1.00 Ω = 1.50 Section K1.6
φRn = 1.00(65.7 kips)(2 walls) Rn/Ω = (65.7 kips/1.50)(2 walls)
\= 131 kips > 76.8 kips o.k. = 87.6 kips > 54.0 kips o.k.

Calculate the nominal wall local crippling strength of the HSS Section K1.6

For each of the two walls:

⎡Rn = 0.8t 2 EFy t p / t ⎤⎦ 0.5 Eqn. K1-12 ⎢⎣ 1 + ( 6 N / B )( t / t p )1.5 ⎤⎡⎥⎦ ⎣
2 ⎡ ⎛ 6 ( 3.63in. ) ⎞ ⎛ 0.233in. ⎞1.5 ⎤ ⎡ 29,000 ksi ( 46 ksi )( 0.500in. ) ⎤ 0.5 ⎢1 + ⎥ ⎜Rn = 0.8 ( 0.233in. ) ⎢ ⎥ ⎟ ⎜ ⎟ ⎜ 8.00in. ⎟ ⎢ ⎝ 0.500in. ⎝ ⎠ ⎣ 0.233in. ⎦ ⎣ ⎠ ⎥⎦

\= 137 kips per wall

Calculate the available local wall local crippling strength of the HSS

LRFD ASD
φ = 0.75 Ω = 2.00 Section K1.6
φRn = 0.75(137 kips)(2 walls) Rn/Ω = (137 kips/2.00)(2 walls)
\= 207 kips > 76.8 kips o.k. = 137 kips > 54.0 kips o.k.

The presence of the stiffeners eliminates the need to check the beam web for local web yielding
and local web crippling.

<!-- p. 239 -->

K-33

Example K.12 Rectangular HSS Column Base Plate.

Given:
A HSS 6×6×2 column is supporting nominal loads of 40 kips from dead load and 120 kips from live load. The
column is supported by a 7’-6” × 7’-6” concrete spread footing with a f ′c = 3000 psi. Size a base plate for this
column.

Solution:

Material Properties:
Column ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Manual
Base Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-3

Geometric Properties:
HSS 6×6×2 B = H = 6.00 in.

Calculate the required strength

LRFD ASD
Pu = 1.2(40.0 kips) + 1.6(120 kips) Pa = 40.0 kips + 120 kips
\= 240 kips = 160 kips

Note: The procedure illustrated here is similar to that presented in AISC Design Guide 1Column Base Plates.

Try a base plate which extends 32 in. from each face of the HSS column, or 13 in. by 13 in.

Calculate the available strength for the limit state of concrete crushing

Pp = 0.85 cf' A1 A2 A1 where A2 A1 ≤ 4
Eqn. J8-2
A1 = (13.0.in.)(13.0 in.) = 169 in.2

A2 = (90.0.in.)(90.0 in.) = 8100 in.2

<!-- p. 240 -->

K-34

2 8100in. 2 2Pp = 0.85 ( 3 ksi )(169 in. ) 2 ≤ 1.7 ( 3ksi )(169in. ) 169in.
20,700 kips ≤ 862 kips

Use Pp = 862 kips

Note: The limit on the right side of Equation J8-2 will control when A2/A1 exceeds 4.0

LRFD ASD
φc = 0.60 Ωc = 2.50 Section J8
φcPp = 0.60(862 kips) Pp/Ωc = 862 kips/2.50
\= 517 kips > 240 kips o.k. = 345 kips > 160 kips o.k.

Calculate the pressure under the bearing plate and determine the required thickness

For a rectangular HSS, the distance m or n is determined using 0.95 times the depth and width
of the HSS.

Note: When the HSS is large compared to the edge extension, a quick and conservative
approach is to include in the bearing area only the surface within the distance m or n of the
HSS wall within the shape.

N - 0.95(outside dimension)
m = n =
2
⎡ ⎤ 13.0 in. - 0.95(6.00 in.) ⎣ 6 − 2 ( 12 ) = = 3.65 in. > ⎦= 2.50 in. , therefore, the full area of
2 2
the baseplate inside the HSS is effective in bearing.

The critical bending moment is the cantilever moment outside the HSS perimeter.

LRFD ASD
Pu 240 kips Pa 160 kips
f pu = = 2 = 1.42 ksi f pa = = 2 = 0.947 ksi
Aeff 169in. Aeff 169in.
f pu l 2 f pa l 2
M u = M a =
2 2
pt 2 pt 2
Z = Z =
4 4
φb = 0.90 Ωb = 1.67

Mn = Mp = FyZ Mn = Mp = FyZ Eqn. F11-1

Equating: Equating:

Mu = φb Mn and solving for tp gives: Ma = Mn/Ωb and solving for tp gives:
2 f pu l 2 2 f pa l 2
t p ( req ) = t p ( req ) =
φ b Fy Fy / Ω b
2 (1.42 ksi )( 3.65in.) 2 2 ( 0.947ksi )( 3.65in.) 2 = = 1.08 in. = = 1.08 in.
0.90 ( 36 ksi ) ( 36 ksi ) /1.67
Therefore, use a 14 in. thick plate.

<!-- p. 241 -->

K-35

Example K.13 Rectangular HSS Strut End Plate.

Given:
Determine weld leg size, end plate thickness, and the size of ASTM A325 bolts required to resist nominal forces
of 16 kips from dead load and 50 kips from live load on an ASTM A500 Gr. B HSS4×4×4 section. The end
plate is ASTM A36.

Solution:

Material Properties:
Strut ASTM A500 Gr. B Fy = 46 ksi Fu = 58 ksi Manual
End Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-3

Geometric Properties:
Strut HSS 4×4×4 t = 0.233 in. A = 3.37 in.2 Manual
End Plate b = a = 1.50 in. Table 1-12

Calculate the required tensile strength

LRFD ASD
Pu = 1.2(16.0 kips) + 1.6(50.0 kips) Pa = 16.0 kips + 50.0 kips
\= 99.2 kips = 66.0 kips

Preliminary size of the (4) ASTM A325 bolts
LRFD ASD
Pu 99.2kips Pa 66.0kips rut = = = 24.8 kips rat = = = 16.5 kips
n 4 n 4
Manual
Try 34 -in. diameter ASTM A325 bolts Try 34 -in. diameter ASTM A325 bolts Table 7-2
φnr = 29.8 kips nr / Ω = 19.9 kips

<!-- p. 242 -->

K-36

Calculate required end-plate thickness with consideration of prying action
d b d ba ' = a + ≤ 1.25b + Manual 2 2
3 3 Section 9
\= 1.50 in. + 4 ≤ 1.25(1.50 in.)+ 4
2 2
\= 1.88 in. ≤2.25 in. o.k.
d b 34b ' = b − = 1.5 in. − = 1.12 in.
2 2
b ' 1.12
ρ = = = 0.596
a ' 1.88
3 d ' ( 4 + 1 8 )δ = 1 − = 1 − = 0.781
p 4.0
LRFD ASD
1 ⎛ φrn ⎞ 1 ⎛ 29.8 ⎞ 1 ⎛ rn / Ω ⎞ 1 ⎛ 19.9 ⎞ Manual = β = − 1 − 1 ⎜ ⎜ ⎜ ⎟ ⎜ ⎟ = − 1⎟⎠= 0.346 Section 9 ρ 0.596 ⎝ 24.8 0.596 ⎝ 16.5 ⎠ − 1⎟⎠= 0.338 β = ρ ⎝ ⎠ ⎝ rut rat
1 ⎛ β ⎞ 1 ⎛ β ⎞
α ' = α ' = ⎜ ⎟ ⎜ ⎟ δ ⎝−β⎠1 δ ⎝−β⎠1
1 ⎛ 0.338 1 ⎛ 0.346 ⎞ = ⎜ ⎞=⎟ 0.654 ≤ 1.0 = ⎜ ⎟ = 0.677 ≤ 1.0 0.781 ⎝ 1 − 0.338 ⎠ 0.781 ⎝ 1 − 0.346 ⎠

LRFD ASD
Manual 4.44 rut b ' 6.66 rat b ' t req = t req = Section 9
pFu (1 + δα ') pFu (1 + δα ')
4.44 ( 24.8 kips )(1.12 in. ) 6.66 (16.5 kips )(1.12 in. ) = =
4.00 in. ( 58 ksi ) (1 + 0.781 ( 0.654 ) ) 4.00in. ( 58 ksi ) (1 + 0.781 ( 0.677 ) )
\= 0.593 in. = 0.589 in.

Use 58 in. end plate, 1t > 0.593, further bolt Use 58 in. end plate, 1t > 0.589, further bolt
check for prying not required. check for prying not required.

Use (4) 3 4 in. diameter A325 bolts Use (4) 3 4 in. diameter A325 bolts

Calculate the weld size required

Fw = 0.60Fexx(1.0 + 0.5 sin1.5(θ)) = 0.60(70 ksi)(1.0 + 0.5sin1.5(90) = 63.0 ksi Eqn. J2-5

l = 4(4.00 in.) = 16.0 in.

LRFD ASD
For shear and fillet welds φ = 0.75 For shear and fillet welds Ω = 2.00
Pu ΩPa w ≥ w ≥
φFw (0.707)l Fw (0.707)l
99.2 kips 2.00 ( 66.0 kips ) Manual ≥ ≥ Section 8 0.75 ( 63.0 ksi )( 0.707 )(16.0 in. ) ( 63.0 ksi )( 0.707 )(16.0 in. )
\= 0.186 in. = 0.185 in.

<!-- p. 243 -->

K-37

Check minimum weld size requirements
For t = 58 in. minimum weld = 14 in. Table J2.4

LRFD ASD
0.250 in. > 0.186 in. 0.250 in. > 0.185 in.
Use 14 in. weld leg size Use 14 in. weld leg size

Results
Use 14 in. weld with 58 in. end plate and (4) ¾-in. diameter ASTM A325 bolts.

<!-- p. 244 -->

IIA-1

Chapter IIA
Simple Shear Connections

The design of simple shear connections is covered in Part 10 of the
AISC Steel Construction Manual.

<!-- p. 245 -->

IIA-2

Example II.A-1 All-Bolted Double-Angle Connection

Given:

Select an all-bolted double-angle connection between a W36×231 beam and a W14×90 column
flange to support the following beam end reactions:

RD = 37.5 kips
RL = 112.5 kips

Use w-in. diameter ASTM A325-N bolts in standard holes.

Material Properties:

Beam W36×231 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Angles 2L5×32 ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Beam W36×231 tw = 0.760 in. Manual
Column W14×90 tf = 0.710 in. Table 1-1
Angles 2L5×32 SLBB

<!-- p. 246 -->

IIA-3

Solution:

LRFD ASD
Ru = 1.2(37.5 kips) + 1.6(112.5 kips) Ra = 37.5 kips + 112.5 kips

\= 225 kips = 150 kips

Manual Table 10-1 includes checks for the Manual Table 10-1 includes checks for the
limit states of bearing, shear yielding, shear limit states of bearing, shear yielding, shear
rupture, and block shear rupture on the rupture, and block shear rupture on the
angles, and shear on the bolts. angles, and shear on the bolts.

Try 8 rows of bolts and c-in. angle Try 8 rows of bolts and c-in. angle
thickness. thickness.

φRn = 247 kips > 225 kips o.k. Rn / Ω= 165 kips > 150 kips o.k. Manual Table
10-1
Check the beam web for bolt bearing. Check the beam web for bolt bearing.
Block shear rupture, shear yielding and Block shear rupture, shear yielding and
shear rupture will not control, since the shear rupture will not control, since the
beam is uncoped. beam is uncoped.

Uncoped, Leh = 1w in. Uncoped, Leh = 1w in.

φRn = (702 kips/in.)(0.760 in.) Rn / Ω= (468 kips/in.)(0.760 in.) Manual Table
10-1
\= 534 kips > 225 kips o.k. = 356 kips > 150 kips o.k.

Check supporting member flange for bolt Check supporting member flange for bolt
bearing bearing

φRn = (1400 kips/in.)(0.710 in.) Rn / Ω= (936 kips/in.)(0.710 in.) Manual Table
10-1
\= 994 kips > 225 kips o.k. = 665 kips > 150 kips o.k.

See Example II.A-2 for a bolted/welded double angle connection.

<!-- p. 247 -->

IIA-4

Example II.A-2 Bolted/Welded Double-Angle Connection

Given:

Use Manual Table 10-2 to substitute welds for bolts in the support legs of the double-angle
connection (welds B). Use 70 ksi electrodes.

Material Properties:

Beam W36×231 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Angles 2L4×32 ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Beam W36×231 tw = 0.760 in. Manual
Column W14×90 tf = 0.710 in. Table 1-1
Angles 2L4×32 SLBB

<!-- p. 248 -->

IIA-5

Solution:

LRFD ASD
Ru = 1.2(37.5 kips) + 1.6(112.5 kips) Ra = 37.5 kips + 112.5 kips

\= 225 kips = 150 kips
Manual
Design welds (welds B) Design welds (welds B) Table 10-2

Try c-in. weld size, L = 232 in. Try c-in. weld size, L = 232 in.

tf min = 0.238 in. \< 0.710 in. tf min = 0.238 in. \< 0.710 in.
o.k. o.k.

φRn = 279 kips > 225 kips o.k. Rn / Ω= 186 kips > 150 kips o.k.

Check minimum angle thickness Check minimum angle thickness

tmin = w + z-in. ≥ c in. tmin = w + z-in. ≥ c in. Section J2.2b

\= c in. + z in. = c in. + z in.

\= a in. > c in o.k. = a in. > c in. o.k.

Use 2L4×32×a Use 2L4×32×a

Check bolt shear. Check angles for bolt Check bolt shear. Check angles for bolt
bearing, shear yielding, shear rupture, and bearing, shear yielding, shear rupture, and
block shear rupture block shear rupture

Check 8 rows of bolts and a in. angle Check 8 rows of bolts and a in. angle Manual
thickness. thickness. Table 10-1

φRn = 254 kips > 225 kips o.k. Rn / Ω= 170 kips > 150 kips o.k.
Check beam web for bolt bearing. Check beam web for bolt bearing.

Uncoped, Leh = 1w in. Uncoped, Leh = 1w in.

φRn = (702 kips/in.)(0.760 in.) Rn / Ω= (468 kips/in.)(0.760 in.) Manual
Table 10-1
\= 534 kips > 225 kips o.k. = 356 kips > 150 kips o.k.
Check supporting member flange for bolt Check supporting member flange for bolt
bearing bearing

φRn = (1400 kips/in.)(0.710 in.) Rn / Ω= (936 kips/in.)(0.710 in.) Manual Table
10-1
\= 994 kips > 225 kips o.k. = 665 kips > 150 kips o.k.
Note: In this example, because of the relative size of the cope to the overall beam size, the
coped section does not control. When this can not be determined by inspection, see Manual
Part 9 for the design of the coped section.

See Example II.A-1 for an all-bolted double-angle connection (beam-to-column flange).

<!-- p. 249 -->

IIA-6

Example II.A-3 All-Welded Double-Angle Connection

Given:

Use Manual Table 10-3 to design an all-welded double-angle connection between a W36×231
beam and a W14×90 column flange.
Use 70 ksi electrodes.

Material Properties:

Beam W36×231 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Angles 2L4×32 ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Beam W36×231 tw = 0.760 in. Manual
Column W14×90 tf = 0.710 in. Tables 1-1
Angles 2L4×32 SLBB and 1-15

<!-- p. 250 -->

IIA-7

Solution:

LRFD ASD
Ru = 1.2(37.5 kips) + 1.6(112.5 kips) Ra = 37.5 kips + 112.5 kips

\= 225 kips = 150 kips

Design the weld between the beam-web and Design the weld between the beam-web and Manual
the angle leg (welds A) the angle leg (welds A) Table 10-3

Try 4 in. weld size, L = 24 in. Try 4 in. weld size, L = 24 in.

tw min = 0.381 in. \< 0.760 in. tw min = 0.381 in. \< 0.760 in.
o.k. o.k.

φRn = 343 kips > 225 kips o.k. Rn / Ω= 229 kips > 150 kips o.k.
Design the welds between support and the Design the welds between support and the
angle leg (welds B) angle leg (welds B)

Try 4 in. weld size Try 4 in. weld size

tf min = 0.190 in. \< 0.710 in. tf min = 0.190 in. \< 0.710 in.
o.k. o.k. Manual
Table 10-3
φRn = 229 kips > 225 kips o.k. Rn / Ω= 153 kips > 150 kips o.k.
Check the minimum angle thickness Check the minimum angle thickness

tmin = w + z in. ≥ 8 in. tmin = w + z in. ≥ 8 in. Section J2.2b

\= 4 in. + z in. = 4 in. + z in.

\= c in. ≥ 8 in. o.k. = c in. ≥ 8 in. o.k.

Use 2L4×3×c Use 2L4×3×c

Comment:

See Example II.A-1 for an all-bolted double-angle connection and Example II.A-2 for a
bolted/welded double-angle connection.

<!-- p. 251 -->

IIA-8

Example II.A-4 All-Bolted Double-Angle Connection

Given:

Use Manual Table 10-1 to select an all-bolted double-angle connection between a W18×50
beam and a W21×62 girder web to support the following beam end reactions:

RD = 10 kips
RL = 30 kips

The beam top flange is coped 2-in. deep by 4-in. long, Lev = 14 in., Leh = 1w in. (assumed to
be 12 in. for calculation purposes to account for possible underrun in beam length)

Use w-in. diameter ASTM A325-N bolts in standard holes.

Material Properties:

Beam W18×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Girder W21×62 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Angles 2L4×32 ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Beam W18×50 d = 18.0 in. tw = 0.355 in. Snet = 23.4 in.3 Manual
Cope c = 4 in. dc = 2 in. e = 4 in. + 2 in. = 42-in. Tables 1-1
h0 = 16.0 in. and 9-2
Girder W21×62 tw = 0.400 in.
Angles 2L4×3 ½ SLBB

<!-- p. 252 -->

IIA-9

Solution:

LRFD ASD
Ru = 1.2(10 kips) + 1.6(30 kips) = 60 kips Ra = 10 kips + 30 kips = 40 kips

Check bolt shear. Check angles for bolt Check bolt shear. Check angles for bolt
bearing, shear yielding, shear rupture and bearing, shear yielding, shear rupture and
block shear rupture block shear rupture

Try 3 rows of bolts and 4 in. angle thickness Try 3 rows of bolts and 4 in. angle thickness
Manual
φRn = 76.4 kips > 60 kips o.k. Rn / Ω= 50.9 kips > 40 kips o.k. Table 10-1
Check beam web for bolt bearing, block Check beam web for bolt bearing, block
shear rupture, shear yielding and shear shear rupture, shear yielding and shear
rupture rupture

Check beam web for bolt bearing Check beam web for bolt bearing
Manual
Top flange coped, Lev = 14 in , Leh = 1w in Top flange coped, Lev = 14 in, Leh = 1w in Table 10-1

φRn = (200 kips/in.)(0.355 in.) Rn / Ω= (133 kips/in.)(0.355 in.)

\= 71.0 kips > 60 kips o.k. = 47.2 kips > 40 kips o.k.
Check supporting member web for bolt Check supporting member web for bolt
bearing bearing

φRn = (526 kips/in.)(0.400) Rn / Ω= (351 kips/in.)(0.400 in.) Manual
Table 10-1
\= 210 kips > 60 kips o.k. = 140 kips > 40 kips o.k.
Check block shear rupture Check block shear rupture Commentary
Section J4.3
Since one vertical row of bolts is used, the Since one vertical row of bolts is used, the
tension stress can be taken as uniform, tension stress can be taken as uniform,
therefore therefore

Ubs = 1.0 Ubs = 1.0 Eqn. J4-5

⎛ 0.6 Fy Agv Rn Fu Ant U bs Fu Anv ⎞ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) , = + min ⎜ ⎟ Ω Ω ⎝ Ω Ω ⎠ Manual
Tables 9-3a
Tension Component Tension Component

φ Fu Ant = 51.8 kips/in. (0.355 in.) Fu Ant /Ω = 34.5 kips/in. (0.355 in.)
Manual
Shear Yielding Component Shear Yielding Component Table 9-3b

φ0.6FyAgv = 163 kips/in. (0.355 in.) 0.6FyAgv /Ω = 109 kips/in. (0.355 in.)
Manual
Shear Rupture Component Shear Rupture Component Table 9-3c

φ0.6FuAnv = 148 kips/in. (0.355 in.) 0.6FuAnv / Ω = 98.7 kips/in. (0.355 in.)

<!-- p. 253 -->

IIA-10

Rn = (98.7 kips/in. + 34.5 kips/in.)(0.355 in.)
φRn = (148 kips/in. + 51.8 kips/in.)(0.355 in.) Ω

\= 70.9 kips \< 76.3 kips = 47.3 kips \< 50.9 kips

70.9 kips > 60 kips o.k. 47.3 kips > 40 kips o.k.

Note: The middle portion of Manual Table 10-1 includes checks of the limit-state of bolt
bearing on the beam web and the limit-state of block shear rupture on coped beams. Manual Manual
Tables 9-3a, 9-3b and 9-3c are required for values of Lev and Leh beyond the limits of Table 10- Table 10-1
\1. For coped members, the limit states of flexural rupture and local buckling must be checked
independently, per Part 9.

Check flexural rupture on the coped section
Manual
Snet = 23.4 in3 Table 9-2

Fu S net (65 ksi)(23.4 in.3 ) Manual
Rn = = = 338 kips Part 9 e 4 12 in.

LRFD ASD
φ = 0.75 Ω= 2.00

φRn = 0.75(338 kips) (338 kips) Rn / Ω=
2.00

\= 254 kips > 60 kips o.k. = 169 kips > 40 kips o.k.

Check local web buckling at the coped section
d Manual
Verify c ≤ 2 d and d c ≤ Part 9 2

c = 4.0 in. \< 2 (18.0 in. ) = 36.0 in. o.k.

18.0 in.
cd = 2.0 in. \< = 9.0 in. o.k.
2

c 4 in. c 4 in.
\= = 0.222; = = 0.250
d 18.0 in. h0 16.0 in.

c
Since ≤ 1.0,
d

⎛ c ⎞ f = 2 ⎜ ⎟ = 2 ( 0.222 ) = 0.444 ⎝ d ⎠

<!-- p. 254 -->

IIA-11

c
Since ≤ 1.0,
h0

⎛ h0 ⎞ 1.65 ⎛ 16.0 ⎞ 1.65 k = 2.2 = 2.2 ⎜ ⎟ = 21.7 ⎜ ⎟ ⎝ c ⎠ ⎝ 4.00 ⎠

⎛ t w ⎞ 2 ⎛ 0.355 in. ⎞ 2 Manual (0.444)(21.7) = 124 ksi ≤ Fy fk = 26,210 ⎜ ⎟ Fcr = 26,210 ⎜ ⎟ Part 9 ⎠ ⎝ 16.0 in. ⎠ ⎝ h0

Fcr S net (50 ksi)(23.4 in.3 ) Rn = = = 260 kips
e 4 12 in.

LRFD ASD
φ = 0.90 Ω= 1.67
Section F1
φRn = 0.90(260 kips) 260 kips Rn / Ω=
1.67

\= 234 kips > 60 kips o.k. = 156 kips > 40 kips o.k.

Check shear yielding on beam web

Rn = 0.6 Fy Ag = 0.6(50 ksi)(0.355 in)(16.0 in) = 170 kips Eqn J4-3

LRFD ASD
φ = 1.00 Ω= 1.50
Section J4.2
φRn = 1.00(170 kips) 170 kips Rn / Ω=
1.50

\= 170 kips > 60 kips o.k. = 113 kips > 40 kips o.k.

Check shear rupture on beam web

Anv = tw [ho-3(0.875 in.)] = (0.355 in.)(16.0 in. - 2.63 in.) = 4.75 in2 Equation
J4-4
Rn = 0.6 Fu Anv = 0.6(65 ksi)(4.75 in2) = 185 kips

LRFD ASD
φ = 0.75 Ω= 2.00
Section J4.2 185 kips
φRn = 0.75(185 kips) Rn / Ω=
2.00
\= 139 kips > 60 kips o.k. = 92.6 kips > 40 kips o.k.

Note: see Example II.A-5 for a bolted/welded double-angle connection.

<!-- p. 255 -->

IIA-12

Example II.A-5 Bolted/Welded Double-Angle Connection (beam-to-girder web).

Given:

Use Manual Table 10-2 to substitute welds for bolts in the supported-beam-web legs of the
double-angle connection (welds A).

Use 70 ksi electrodes.
Use w-in. diameter ASTM A325-N bolts in standard holes.

Material Properties:

Beam W18×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Girder W21×62 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Angles 2L4×32 ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Beam W18×50 d = 18.0 in. tw = 0.355 in. Snet = 23.4 in.3 Manual
Cope c = 4 in. dc = 2 in. e = 4 in. + 2 in. = 42 in. Tables 1-1,
h0 = 16.0 in. 1-15, and
Girder W21×62 tw = 0.400 in. 9-2
Angles 2L4×32 SLBB

<!-- p. 256 -->

IIA-13

Solution:

LRFD ASD
Ru = 1.2(10 kips) + 1.6(30 kips) = 60.0 kips Ra = 10 kips + 30 kips = 40.0 kips

Design welds (welds A) Design welds (welds A) Manual
Table 10-2
Try x-in. weld size, L = 82 in. Try x-in. weld size, L = 82 in.

tw min = 0.286 in. \< 0.355 in. tw min = 0.286 in. \< 0.355 in.
o.k. o.k.

φRn = 110 kips > 60 kips o.k. Rn / Ω= 73.4 kips > 40 kips o.k.
Check minimum angle thickness Check minimum angle thickness

w = weld size w = weld size

tmin = w + z-in. ≥ 4 in. tmin = w + z-in. 4 in. Section J2.2b

\= x in. + z in. = x in. + z in.
Manual
\= 4 in. ≥ 4 in. o.k. = 4 in. ≥ 4 in. o.k. Table 10-1

Note: see Example II.A-4 for an all-bolted double-angle connection (beam-to-girder web).

<!-- p. 257 -->

IIA-14

Example II.A-6 Beam End Coped at the Top Flange Only

Given:

For a W21×62 coped 8-in. deep by 9-in. long at the top flange only:

A. calculate the available strength of the beam end, considering the limit states of flexural
rupture and local buckling. Assume e = 9½ in.

B. choose an alternate W21 shape to eliminate the need for stiffening for an end reaction of
RD = 16.5 kips and RL = 47 kips.

C. determine the size of doubler plate needed to stiffen the W21×62 for the given end
reaction.

D. determine the size of longitudinal stiffeners needed to stiffen the W21×62 for the given
end reaction.

Material Properties:

Beam W21×62 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi Tables 2-3
and 2-4

Geometric Properties:

Beam W21×62 d = 21.0 in. tw = 0.400 in. Snet = 17.8 in.3 Manual
Cope c = 9 in. dc = 8 in. e = 9 in. + 2 in. = 92 in. Tables 1-1
h0 = 13.0 in. and 9-2

<!-- p. 258 -->

IIA-15

Solution A:

Check flexural rupture strength of the coped section

Snet = 17.8 in3 Manual
Table 9-2
Fu S net (65 ksi)(17.8 in.3 )
Rn = = = 122 kips Manual e 9 12 in.
Part 9
LRFD ASD
φ = 0.75 Ω= 2.00 Section F1
122 kips
φRn = 0.75(122kips) = 91.3 kips Rn / Ω= = 61 kips
2.00

Check local buckling
Manual
Verify parameters Part 9

c ≤ 2d

c = 9.0 in. \< 2 ( 21.0 in. ) = 42.0 in. o.k.

dc \< d / 2
21.0 in.
cd = 8.0 in. \< = 10.5 in. o.k.
2

c 9 in. c 9 in.
\= = 0.429; = = 0.693
d 21.0 in. h0 13.0 in.

c
Since ≤ 1.0,
d

⎛ c ⎞ f = 2 ⎜ ⎟ = 2 ( 0.429 ) = 0.858 ⎝ d ⎠

c
Since ≤ 1.0,
h0

⎛ h0 ⎞ 1.65 ⎛ 13.0 in. ⎞ 1.65 k = 2.2 = 2.2 ⎜ ⎟ = 4.03 ⎜ ⎟ ⎝ c ⎠ ⎝ 9.0 in. ⎠

For a top cope only, the critical buckling stress is

⎛ t w ⎞ 2
Fcr = 26,210 ⎜ ⎟ fk ≤ Fy ⎝ h0 ⎠ Manual
2 Part 9 ⎛ 0.400 in. ⎞
\= 26,210 ⎜ ⎟ (0.858)(4.03) ≤ 50 ksi ⎝ 13.0 in. ⎠
\= 85.8 ksi ≤ 50 ksi

<!-- p. 259 -->

IIA-16

Use Fcr = 50 ksi

Fcr Snet (50 ksi)(17.8 in.3 ) Rn = = = 93.7 kips
e 9 12 in.

LRFD ASD
φ = 0.90 Ω= 1.67 Section F1
93.7 kips
Rn / Ω= = 56.1 kips φRn = 0.90(93.7 kips) = 84.3 kips 1.67

Check shear yielding on beam web

Rn = 0.6 Fy Ag = 0.6(50 ksi)(0.400 in)(13.0 in) = 156 kips

Eqn J4-3

LRFD ASD
φ = 1.00 Ω= 1.50

φRn = 1.00(156 kips) = 156 kips 156 kips Rn / Ω= = 104 kips Sect J4.2 1.50

Check shear rupture on beam web

Rn = 0.6 Fu Anv = 0.6(65 ksi)(0.400 in)(13.0 in) = 203 kips Eqn J4-4

LRFD ASD
φ = 0.75 Ω= 2.00 Section J4.2

φRn = 0.75(203 kips) = 203 kips 203 kips Rn / Ω= = 101 kips
2.00

Thus, the available strength is controlled by local bucking, with
LRFD ASD
φRn = 84.3 kips. Rn /Ω = 56.1 kips.

<!-- p. 260 -->

IIA-17

Solution B:

LRFD ASD
Ru = 1.2(16.5 kips) + 1.6 ( 47 kips ) = 95 kips Ra = 16.5 kips + 47 kips = 63.5 kips

LRFD ASD
Calculate required section modulus based on Calculate required section modulus based on
flexural rupture flexural rupture

Ru e (95 kips)(9 12 in.) Ra e Ω 63.5 kips(9 12 in.)(2.00) S req = = S req = =
φFy 0.75(65 ksi) Fu 65 ksi

\= 18.6 in.3 = 18.6 in.3

Try W21×73 with an 8-in. deep cope
Manual
S net = 21.0 in.3 > 18.6 in.3 o.k. Table 9-2

Check local buckling
Similarly as determined in Solution A for the W21×62, the available critical stress due to local
buckling for a W21×73 with an 8-in. deep cope is limited to the yield stress.

Therefore,

Fcr S net (50 ksi)(21.0 in. 3 )Rn = = = 111 kips
e 9 12 in.

LRFD ASD
φ = 0.90 Ω= 1.67 Section F1
φRn = 0.90(111 kips) = 100 kips 111 kips
Rn / Ω= = 66.5 kips
1.67
\> 95.0 kips o.k. > 63.5 kips o.k.

<!-- p. 261 -->

IIA-18

Solution C:

LRFD ASD
Design doubler plate Design doubler plate Manual
Part 9
Doubler plate must provide a required Doubler plate must provide a required
strength of strength of

95 kips – 84.3 kips = 10.7 kips. 63.5 kips – 56.1 kips = 7.40 kips.

( Ru −φRn beam ) e ( Ra − Rn beam / Ω ) e Ω S req = S req =
φFy Fy

(95 kips - 84.3 kips)(9 12 in.) (63.5 kips-56.1 kips)(9 12 in.)(1.67) = =
0.90(50 ksi) 50 ksi

\= 2.26 in.3 = 2.35 in.3

For an 8-in. deep plate, For an 8-in. deep plate,

6 S req 6(2.26 in.3 ) 6 S req 6(2.35 in.3 )
t req = 2 = 2 = 0.212 in. t req = 2 = 2 = 0.220 in. d ( 8 in.) d ( 8 in.)
Note: ASTM A572 grade 50 plate is recommended in order to match the beam yield strength

Thus, since the doubler plate must extend at least dc beyond the cope,
use a PL c in.×8 in. ×1’-5” with ¼ in welds.

<!-- p. 262 -->

IIA-19

Solution D:

Design longitudinal stiffeners

Try PL 4 in.×4 in. slotted to fit over the beam web with Fy = 50 ksi. From section property
calculations for the neutral axis and moment of inertia, the neutral axis is located 4.40 in. from
the bottom flange (8.84 in. from the top of the stiffener) and the elastic section modulus of the
reinforced section is as follows:

I0 (in.4) Ad 2 (in.4) I0 + Ad 2 (in.4)

Stiffener 0.00521 76.0 76.0
W21×62 web 63.2 28.6 91.8
W21×62 bottom flange 0.160 84.9 85.1
Σ= Ix = 253 in.4

I x 253 in.4 3 S net = = = 28.6 in.
c 8.84 in.

and the nominal strength of the reinforced section is

Fy S net (50 ksi)(28.6 in 3 )
Rn = = = 151 kips
e 9 12 in.

LRFD ASD
Calculate design strength Calculate allowable strength

φ = 0.90 Ω= 1.67
Section F1
151 kips
Rn / Ω= φRn = 0.90(151 kips) 1.67

\= 136 kips > 95 kips o.k. = 90.4 kips > 63.5 kips o.k.

Plate dimensions

Since the longitudinal stiffening must extend at least dc beyond cope,

Use PL 4 in.×4 in.×1’-5” with ¼ in. welds

<!-- p. 263 -->

IIA-20

Example II.A-7 Beam End Coped at the Top and Bottom Flanges.

Given:

A W21×62 is coped 3-in. deep by 7-in. long at the top flange and 4-in. deep by 7-in. long at the
bottom flange. Calculate the available strength of the beam end considering the limit states of
flexural rupture, local buckling, shear yielding, and shear rupture. Assume e = 72 in.

Material Properties:

Beam W21×62 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Table 2-3

Geometric Properties:

Beam W21×62 d = 21.0 in. tw = 0.400 in. Manual
Cope c = 7 in. dc = 4 in. e = 72 in. h0 = 14.0 in. Tables 1-1
and 9-2a

Solution:

Check flexural rupture on the coped section

t w h0 2 (0.400 in.)(14.0 in.) 2 3 Manual
S net = = = 13.1 in. Part 9 6 6

Fu S net (65 ksi)(13.1 in.3 ) Rn = = = 114 kips
e 7 12 in.

LRFD ASD
φ = 0.75 Ω= 2.00 Section F1

φRn = 0.75(114 kips) = 85.1 kips 114 kips Rn / Ω= = 57.0 kips
2.00

<!-- p. 264 -->

IIA-21

Check local buckling
Manual
Verify parameters Part 9

c ≤ 2d

c = 7.0 in. \< 2 ( 21.0 in. ) = 42.0 in. o.k.

dc ≤ 0.2d

cd = 3.0 in. \< 0.2(21.0) = 4.20 in. o.k.

⎛ d c ⎞ ⎛ 3.0 in. ⎞
f d = 3.5 − 7.5 ⎜ ⎟ = 3.5 − 7.5 ⎜ ⎟ = 2.43 ⎝ d ⎠ ⎝ 21.0 in. ⎠

For the doubly-coped beam when c ≤ 2 d and d c ≤ 0.2 d , the critical buckling stress is Manual
Part 9
⎛ t w 2 ⎞
Fcr = 0.62πE ⎜ ⎟ f d ≤ Fy ⎝ ch0 ⎠
⎡ ( 0.400 in.) 2 ⎤ = 0.62π(29,000) ⎢ ⎥ (2.43) = 224 ksi ≤ 50 ksi
⎢ (7 in.)(14.0 in.) ⎥ ⎣ ⎦

Use Fcr = 50 ksi

Fcr Snet (50 ksi)(13.1 in.3 ) Rn = = = 87.3 kips (same as yielding)
e 7 12 in.

LRFD ASD
φ = 0.90 Ω= 1.67

φRn = 0.90(87.3 kips) = 78.6 kips (87.3 kips) Rn / Ω= = 52.3 kips
1.67

Check shear yielding on beam web

Rn = 0.6 Fy Ag = 0.6(50 ksi)(0.400 in)(14.0 in) = 168 kips Eqn J4-3

LRFD ASD
φ = 1.00 Ω= 1.50 Section J4.2

φRn = 1.00(168 kips) = 168 kips 168 kips Rn / Ω= = 112 kips
1.50

Check shear rupture on beam web

Rn = 0.6 Fu Anv = 0.6(65 ksi)(0.400 in)(14.0 in) = 218 kips Eqn J4-4

<!-- p. 265 -->

IIA-22

LRFD ASD
φ = 0.75 Ω= 2.00 Specification
Sect J4.2
φRn = 0.75(218 kips) = 164 kips 218 kips Rn / Ω= = 109 kips
2.00

Thus, the available strength is controlled by local bucking, with
LRFD ASD
φRn = 78.6 kips Rn /Ω = 52.3 kips

<!-- p. 266 -->

IIA-23

Example II.A-8 All-Bolted Double-Angle Connections (beams-to-girder web).

Given:

Design the all-bolted double-angle connections between the W12×40 beam (A) and W21×50
beam (B) and the W30×99 girder-web to support the following beam end reactions:

Beam A Beam B
RDA = 4.17 kips RDB = 18.3 kips
RLA = 12.5 kips RLB = 55.0 kips

Use ¾-in. diameter ASTM A325-N bolts in standard holes.

Material Properties:

W12×40 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
W21×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
W30×99 ASTM A992 Fy = 50 ksi Fu = 65 ksi
Angle ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Beam W12×40 tw = 0.295 in. d = 11.9 in. h0 = 9.9 in. Snet = 8.03 in.3 Manual
top flange cope dc = 2 in. c = 5 in. Table 1-1
and Manual
Beam W21×50 tw = 0.380 in. d = 20.8 in. h0 = 18.8 in. Snet = 32.5 in.3 Table 9-2
top flange cope dc = 2 in. c = 5 in.

Girder W30×99 tw = 0.520 in. d = 29.7 in.

<!-- p. 267 -->

IIA-24

Solution:

Beam A:
LRFD ASD
RAu = (1.2)(4.17 kips) + (1.6)(12.5 kips) RAa = 4.17 kips + 12.5 kips

\= 25 kips = 16.7 kips

Check bolt shear, check angles for bolt Check bolt shear, check angles for bolt
bearing, shear yielding, shear rupture, bearing, shear yielding, shear rupture,
and block shear rupture for the W12×40 and block shear rupture for the W12×40
(beam A) (beam A)

Try two rows of bolts and 4-in. angle Try two rows of bolts and 4-in. angle
thickness thickness Manual
Table 10-1
φRn = 48.9 kips > 25 kips o.k. Rn /Ω = 32.6 kips > 16.7 kips o.k.

Check beam web for bolt bearing, block Check beam web for bolt bearing, block
shear rupture, shear yielding, and shear shear rupture, shear yielding, and shear
rupture (beam A) rupture (beam A)

From Table 10-1, for two rows of bolts and From Table 10-1, for two rows of bolts and
Lev = 14 in. and Leh = 12 in. Lev = 14 in. and Leh = 12 in. Manual
Table 10-1
φRn = (126 kips/in.)(0.295 in.) Rn /Ω = (83.7 kips/in.)(0.295 in.)

\= 37.2 kips > 25 kips o.k. = 24.7 kips > 16.7 kips o.k.

Check flexural rupture of the coped section Check flexural rupture of the coped section
(beam A) (beam A)
Manual
Snet = 8.03 in3 Snet = 8.03 in3 Table 9-2

φ = 0.75 Ω= 2.00 Section F1

3 3 Manual ( 65 ksi )( 8.03 in. ) Fu S net 0.75 ( 65 ksi )( 8.03 in. ) φFu Snet Part 9 = Rn / Ω= = φRn = 5 in. + 12 in.)( 2.00 ) e ( 5 in. + 12 in.) eΩ (

\= 71.2 kips > 25 kips o.k. = 47.5 kips > 16.7 kips o.k.

Check coped section

Snet = 8.03 in.3 Manual
Table 9-2
Verify parameters

c M 2d Manual
Part 9
5 in. M 2(11.9 in.) = 23.8 in. o.k.

dc M d/2

2 in. M 11.9 in. / 2 = 5.95 in. o.k.

<!-- p. 268 -->

IIA-25

c 5 in. c 5 in.
\= = 0.420 ≤ 1.0 ; = = 0.505 ≤ 1.0
d 11.9 in. h0 9.9 in.

Calculate plate buckling model adjustment factor

⎛ c ⎞
f = 2 ⎜ ⎟ = 2(0.420) = 0.840 ⎝ d ⎠

Calculate plate buckling coefficient

⎛ h0 ⎞ 1.65 ⎛ 9.90 ⎞ 1.65
k = 2.2 ⎜ ⎟ = 2.2 ⎜ ⎟ = 6.79 ⎝ c ⎠ ⎝ 5.00 ⎠

⎛ t w ⎞ 2
Fcr = 26,210 ⎜ ⎟ fk ≤ Fy ⎝ h0 ⎠
⎛ 0.250 in. ⎞ 2 = 26,210 ⎜ ⎟ ( 0.840 )( 6.79 ) = 95.3 ksi ≤ 50 ksi ⎝ 9.9 in. ⎠

Use Fcr = 50 ksi

LRFD ASD
φ = 0.90 Ω= 1.67

3 3 ( 50 ksi )( 8.03 in. ( Fcr / Ω ) S net ) 0.90 ( 50 ksi )( 8.03 in. ) φFcr S net Manual = Rn / Ω= = φRn = 5 12 in.) Part 9 e ( 5 12 in.) e 1.67 (

\= 65.7 kips > 25 kips o.k. = 43.7 kips > 16.7 kips o.k.

Check shear yielding on beam web

Rn = 0.6 Fy Ag = 0.6(50 ksi)(0.295 in)(9.90 in) = 87.6 kips Eqn J4-3

LRFD ASD
φ = 1.00 Ω= 1.50 Section J4.2
φRn = 1.00(87.6 kips) Rn / Ω= 87.6 kips
1.50
\= 87.6 kips > 25 kips. o.k. = 58.4kips > 16.7 kips o.k.

Check shear rupture on beam web

Anv = tw [(ho – 2(0.875 in.)] = 0.295 in. (9.9 in. – 1.75 in.) = 2.40 in2

Rn = 0.6 Fu Anv = 0.6(65 ksi)(2.40 in2) = 93.8 kips Eqn J4-4

LRFD ASD
φ = 0.75 Ω= 2.00 Section J4.2
φRn = 0.75(93.8 kips) = 70.3kips 93.8 kips Rn / Ω= = 46.9 kips
2.00
70.3 kips > 25 kips o.k. 46.9 kips > 16.7 kips o.k.

<!-- p. 269 -->

IIA-26

Beam B:
LRFD ASD
RBu = (1.2)(18.3kips) + (1.6)(55.0 kips) RBa = 18.3 kips + 55.0 kips

\= 110 kips = 73.3 kips

Check bolt shear, check angles for bolt Check bolt shear, check angles for bolt
bearing, shear yielding, shear rupture, and bearing, shear yielding, shear rupture, and
block shear rupture for beam B (W21×50) block shear rupture for beam B (W21×50)

Try five rows of bolts and 4 in. angle Try five rows of bolts and 4 in. angle
thickness. thickness.

Manual φRn = 125 kips > 110 kips o.k. Rn/Ω = 83.3 kips > 73.3 kips o.k.
Table 10-1
Check beam web for bolt bearing, block Check beam web for bolt bearing, block
shear rupture, shear yielding, and shear shear rupture, shear yielding, and shear
rupture (beam B) rupture (beam B)

From tables, for five rows of bolts and Lev = From tables, for five rows of bolts and Lev =
14 in. and Leh = 12 in. 14 in. and Leh = 12 in.

φRn = (312 kips/in.)(0.380 in.) Rn/Ω = (208 kips/in.)(0.380 in.)

Manual = 119 kips > 110 kips o.k. = 79.0 kips > 73.3 kips o.k.
Table 10-1
Check flexural rupture of the coped section Check flexural rupture of the coped section
(beam B) (beam B)

Snet = 32.5 in3 Snet = 32.5 in3 Manual
Table 9-2
φ = 0.75 Ω= 2.00
3 3 Section F1 ( 65 ksi )( 32.5 in ) Fu S net 0.75 ( 65 ksi )( 32.5 in ) φFu S net Manual = Rn / Ω= = φRn = 5 12 in.)( 2.00 ) Part 9 e ( 5 12 in.) e Ω (

\= 288 kips > 110 kips o.k. = 192 kips > 73.3 kips o.k.

Check coped section Manual Table
Snet = 32.5 in.3 9-2

Verify parameters Manual
Part 9
c M 2d

5 in. M 2(20.8 in.) = 41.6 in. o.k.

dc M d/2

2 in. M 20.8 in. / 2 = 10.4 in. o.k.

c 5 in. c 5 in.
\= = 0.240 ≤ 1.0 ; = = 0.266 ≤ 1.0
d 20.8 in. h0 18.8 in.

<!-- p. 270 -->

IIA-27

Calculate plate buckling model adjustment factor

⎛ c ⎞
f = 2 ⎜ ⎟ = 2(0.240) = 0.480 ⎝ d ⎠

Calculate plate buckling coefficient

⎛ h0 ⎞ 1.65 ⎛ 18.8 ⎞ 1.65
k = 2.2 ⎜ ⎟ = 2.2 ⎜ ⎟ = 19.6 ⎝ c ⎠ ⎝ 5.00 ⎠

⎛ t w ⎞ 2
Fcr = 26,210 ⎜ ⎟ fk ≤ Fy ⎝ h0 ⎠
⎛ 0.380 in. ⎞ 2= 26,210 ⎜ ⎟ ( 0.480 )(19.6 ) = 101 ksi ≤ 50 ksi ⎝ 18.8 in. ⎠

Use Fcr = 50 ksi

LRFD ASD
φ = 0.90 Ω= 1.67

3 3 Fcr / Ω ) S net ( 50 ksi )( 32.5 in. ) 50 ksi )( 32.5 in. ) ( φFcr S net 0.90 ( φRn = = Rn / Ω= = 5 12 in.) e ( 5 12 in.) e 1.67 (

\= 266 kips > 110 kips o.k. = 117 kips > 73.3 kips o.k.

Check shear yielding on beam web

Rn = 0.6 Fy Ag = 0.6(50 ksi)(0.380 in)(18.8 in) = 214 kips Eqn J4-3

LRFD ASD
φ = 1.00 Ω= 1.50 Section J4.2
214 kips
φRn = 1.00(214 kips) Rn / Ω=
1.50
\= 214 kips > 110 kips o.k. = 143kips > 73.3 kips o.k.

Check shear rupture on beam web

Anv = tw [ho – (5)(0.875 in.)] = 0.380 in. (18.8 in. – 4.38 in.) = 5.48 in2

Rn = 0.6 Fu Anv = 0.6(65 ksi)(5.48 in2) = 213 kips Eqn J4-4

LRFD ASD
φ = 0.75 Ω= 2.00 Section J4.2
213 kips
φRn = 0.75(213 kips) = 160kips Rn / Ω= = 107 kips
2.00
107 kips > 73.3 kips o.k.
160 kips > 110 kips o.k.

<!-- p. 271 -->

IIA-28

Supporting Girder

Check the supporting girder web

The required bearing strength per bolt is greatest for the bolts that are loaded by both
connections. Thus, for the design of these 4 critical bolts, the required strength is determined as
LRFD ASD
From Beam A, each bolt must support one- From Beam A, each bolt must support one-
fourth of 25 kips or 6.25 kips/bolt. fourth of 16.7 kips or 4.18 kips/bolt.

From Beam B, each bolt must support one- From Beam B, each bolt must support one-
tenth of 110 kips or 11.0 kips/bolt. tenth of 73.3 kips or 7.33 kips/bolt.

Thus, Thus,

Ru = 6.25 kips/bolt + 11.0 kips/bolt Ra = 4.18 kips/bolt + 7.33 kips/bolt

\= 17.3 kips/bolt = 11.5 kips/bolt

The design bearing strength per bolt is The allowable bearing strength per bolt is

φru = (87.8 kips/in)(0.520 in.) ra / Ω = (58.5 kips/in.)(0.520 in.) Manual
Table 7-5
\= 45.7 kips/bolt > 17.3 kips/bolt o.k. = 30.4 kips/bolt > 11.5 kips/bolt o.k.

Although not required for design, the tabulated values may be verified by hand calculations,
as follows
φrn = φ(1.2LctFu) M φ(2.4dtFu) rn/Ω = (1.2LctFu)/Ω M (2.4dtFu)/Ω Eqn. J3-6a

φ1.2LctFu = 1.2LctFu/Ω =

(0.75)(1.2)(3 in. – d in.)(0.520 in.)(65 ksi) (1.2)(3 in. – d in.)(0.520 in.)(65 ksi)/(2.00)

\= 64.7 kips = 43.1 kips

φ(2.4dtFu) = (2.4dtFu)/Ω =

(0.75)(2.4)(w in.)(0.520 in.)(65 ksi) (2.4)(w in.)(0.520 in.)(65 ksi)/(2.00)

\= 45.6 kips \< 64.6 kips = 30.4 kips \< 43.1 kips

φrn = 45.6 kips/bolt > 17.3 kips/bolt o.k. rn/Ω = 30.4 kips/bolt > 11.5 kips/bolt o.k.

<!-- p. 272 -->

IIA-29

Example II.A-9 Offset All-Bolted Double-Angle Connections
(beams-to-girder web)

Given:

Two all-bolted double-angle connections are made back-to-back with offset beams. Design the
connections to accommodate an offset of 6 in.

Material Properties:

W18×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
W16×45 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Angle ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Girder W18×50 tw = 0.355 in. d = 18.0 in. Manual
Beam W16×45 tw = 0.345 in. d = 16.1 in. Table 1-1

Solution:

Modify the 2L4×32×4 connection designed in Example II.A-4 to work in the configuration
shown above. The offset dimension (6 in.) is approximately equal to the gage on the support
from the previous example (6 ¼ in.) and, therefore, is not recalculated below.

Thus, the bearing strength of the middle vertical row of bolts (through both connections),
which now carry a portion of the reaction for both connections, must be verified for this new
configuration.

For each beam,

RD = 10 kips
RL = 30 kips

<!-- p. 273 -->

IIA-30

LRFD ASD
Ru = (1.2)(10 kips) + (1.6)(30 kips) = 60 kips Ra = 10 kips + 30 kips = 40 kips

The required bearing strength per bolt is The required bearing strength per bolt is

( 2 connections )( 60 kips/connection ) ( 2 connections )( 40 kips/connection )
ur = ar =
6 bolts 6 bolts

\= 20.0 kips/bolt = 13.3 kips/bolt

Check supporting girder web Check supporting girder web

The design strength per bolt is The allowable strength per bolt is
Manual
Table 7-5
φru = (87.8 kips/in)(0.355 in.) ra / Ω = (58.5 kips/in.)(0.355 in.)

\= 31.2 kips/bolt > 20.0 kips/bolt o.k. = 20.8 kips/bolt > 13.3 kips/bolt o.k.

Note: If the bolts are not spaced equally from the supported beam web, the force in each
column of bolts should be determined by using a simple beam analogy between the bolts, and
applying the laws of statics.

<!-- p. 274 -->

IIA-31

Example II.A-10 Skewed Double Bent-Plate Connection (beam-to-girder web).

Given:

Design the skewed double bent-plate connection between the W16×77 beam to W27×94 girderweb to support the following beam end reactions:

RD = 13.3 kips
RL = 40.0 kips

Use d-in. diameter ASTM A325-N bolts in standard holes through the support.
Use 70 ksi electrode welds to the supported beam.

<!-- p. 275 -->

IIA-32

Material Properties:

W16×77 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
W27×94 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Plate Material ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

W16×77 tw = 0.455 in. d = 16.5 in. Manual
W27×94 tw = 0.490 in. Table 1-1

Solution:

LRFD ASD
Ru = 1.2 (13.3 kips) + 1.6 (40.0 kips) Ra = 13.3 kips + 40.0 kips

\= 80.0 kips = 53.3 kips

See the scaled layout (c) of the connection. Assign load to each vertical row of bolts
by assuming a simple beam analogy between bolts and applying the laws of statics.

LRFD ASD
Required strength of bent plate A Required strength for bent plate A

80.0 kips (2.25 in.) 53.3 kips (2.25 in.)
Ru = = 30.0 kips Ra = = 20.0 kips
6.0 in. 6.0 in.

Required strength for bent plate B Required strength for bent plate B

Ru = 80.0 kips - 30.0 kips = 50.0 kips Ra = 53.3 kips - 20.0 kips = 33.3 kips

Assume that the welds across the top and bottom of the plates will be 22 in. long, and that the
load acts at the intersection of the beam centerline and the support face.

While the welds do not coincide on opposite faces of the beam web and the weld groups are
offset, the locations of the weld groups will be averaged and considered identical see Figure
(d).

Design welds

Assume plate length of 82 in.

kl 2 12 in. k = = = 0.294 in.
l 8 12 in.

Manual
From tables, with θ = 0° and k = 0.294 Table 8-8

2.5(1.25)(2)
xl = = 0.463 in.
2.5(2) + 8.5
0.463
x = = 0.054
8.5

<!-- p. 276 -->

IIA-33

Thus,

( al + xl ) − xl 3 58 in − 0.463 in. a = = = 0.372
l 8 12 in.

Interpolating from tables, with θ = 0°, a = 0.372, and k = 0.294,
Manual
C = 2.52 Table 8-8

The required weld size for two such welds is
LRFD ASD
φ = 0.75 Ω= 2.00 Manual
Table 8-9 Ru Ω Ra Dreq = Dreq =
φCC1l CC1l
( 50 kips ) 2.0 ( 33.3 kips ) = =
0.75 ( 2.52 )(1.0 )( 8 12 in.) ( 2.52 )(1.0 )( 8 12 in.)
\= 3.11 → 4 sixteenths = 3.11 → 4 sixteenths

Use 4-in. fillet welds.

Check beam web thickness

According to Part 9 of the Manual, with FEXX = 70 ksi on both sides of the connection, the Manual
minimum thickness required to match the available shear rupture strength of the connection Part 9
element to the available shear rupture strength of the base metal is

6.19 D ( 6.19 )( 4 sixteenths )
t min = = = 0.381 in. \< 0.455 in. o.k.
Fu 65 ksi
LRFD ASD
Design bolts Design bolts

Maximum shear to bent plate = 50 kips Maximum shear to bent plate = 33.3 kips

Use 3 rows of 7/8 in. diameter ASTM A325- Use 3 rows of 7/8 in. diameter ASTM A325N bolts. N bolts.

Check shear on bolts Check shear on bolts

φRn = n ( φrn ) Rn / Ω= n ( rn / Ω ) Manual
Table 7-1

\= (3 bolts)(21.6 kips/bolt) = (3 bolts)(14.4 kips/bolt)

\= 64.8 kips > 50 kips o.k. = 43.2 kips > 33.3 kips o.k.

Check bearing on support Check bearing on support

φrn = 102 kips/in. Rn / Ω = 68.3 kips/in. Manual
Table 7-6
\= (102 kips/in)(0.490 in.)(3 bolts) = (68.3 kips/in)(0.490 in.)(3 bolts)

\= 150 kips > 50 kips o.k. = 100 kips > 33.3 kips o.k.

<!-- p. 277 -->

IIA-34

Design bent plates Design bent plates

Try a PL c in. Try a PL c in.

Check bearing on plates Check bearing on plates

φvrni = 91.4 kips/in. rni /Ωv = 60.9 kips/in.

φvrno= 40.8 kips/in. rno /Ωv = 27.2 kips/in.

φRn = [(91.4 kips/in) (2 bolts) = [(60.9 kips/in) (2 bolts)
\+(40.8 kips/in)(1 bolt)](c in.) +(27.2 kips/in)(1 bolt)](c in.)

\= 70 kips > 50 kips o.k. = 46 kips > 33.3 kips o.k.

Check shear yielding of plates Check gross shear yielding of plates

φ = 1.00 Ω = 1.50

φRn = φ (0.6Fy) Ag Rn / Ω = (0.6Fy) Ag / Ω

Eqn. J4-5 = (1.00)(0.6)(36 ksi)(82 in.)(c in.) = (0.6)(36 ksi)(82 in.)(c in.)/1.50

\= 57.4 kips > 50 kips o.k. = 38.3 kips > 33.3 kips o.k.

Check shear rupture of the plates Check shear rupture of the plates

φ = 0.75 Ω = 2.00

5 5 16 in.) 16 in.) An = ⎡⎣ (8 12 in.)- ( 3)(1.0 in.) ⎤⎦ ( An = ⎡⎣ (8 12 in.)- ( 3)(1.0 in.) ⎤⎦ (
\= 1.72 in.2 = 1.72 in.2

φRn = φ (0.6Fu) An Rn / Ω = (0.6Fu) An / Ω

\= (0.75)(0.6)(58 ksi)(1.72 in.2) = (0.6)(58 ksi)(1.72 in.2)/2.00

\= 44.9 kips \< 50 kips n.g. = 29.9 kips \< 33.3 kips n.g.

Increase the plate thickness to a in. Increase the plate thickness to a in.

3 3 8 in.) 8 in.) An = ⎡⎣ (8 12 in.)- ( 3)(1.0 in.) ⎤⎦ ( An = ⎡⎣ (8 12 in.)- ( 3)(1.0 in.) ⎤⎦ (
\= 2.06 in.2 = 2.06 in.2

φRn = (0.75)(0.6)(58 ksi)(2.06 in.2) Rn / Ω = (0.6)(58 ksi)(2.06 in.2)/2.00

\= 53.8 kips > 50 kips o.k. = 35.8 kips > 33.3 kips o.k.

Check block shear rupture of the plate Check block shear rupture of the plate

with n = 3, Lev = Leh = 14 in., with n = 3, Lev = Leh = 14 in.,

⎛ 0.6 Fy Agv Rn Fu Ant U bs Fu Anv ⎞φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) , = + min ⎜ ⎟ Ω Ω ⎝ Ω Ω ⎠

<!-- p. 278 -->

IIA-35

Tension rupture component Tension rupture component Manual
Table 9-3a
φFu Ant = 21.8 kips/in.(a in.) Fu Ant = 14.5 kips/in.(a in.)

Manual Shear yielding component Shear yielding component
Table 9-3b
φ 0.6 Fy Agv = 117 kips/in.(a in.) 0.6 Fy Agv = 78.3 kips/in.(a in.)

Manual
Shear rupture component Shear rupture component Table 9-3c

φ 0.6 Fu Anv = 124 kips/in.(a in.) 0.6 Fu Anv = 82.6 kips/in.(a in.)

φRn = (117 kips/in. + 21.8 kips/in.)(a in.) Rn/Ω = (78.3 kips/in.+14.5 kips/in.)(a in.)

\= 52.1 kips > 50 kips o.k. = 34.8 kips > 33.3 kips o.k.

Thus, the configuration shown in Figure II.A-10 can be supported using a-in. bent plates, and
4-in. fillet welds.

<!-- p. 279 -->

IIA-36

Example II.A-11 Shear End-Plate Connection (beam to girder web).

Given:

Design a shear end-plate connection to connect a W18×50 beam to W21×62 girder web, to
support the following beam end reactions:

RD = 10 kips
RL = 30 kips

Use w-in. diameter ASTM A325-N bolts in standard holes and 70 ksi electrodes.

Material Properties:

Beam W18×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Girder W21×62 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

Beam W18×50 d = 18.0 in. tw = 0.355 in. Snet = 23.4 in.3 Manual
Cope c = 4 4 in. dc = 2 in. e = 42 in. h0 = 16.0 in. Tables 1-1
Girder W21×62 tw = 0.400 in. and 9-2

Solution:
LRFD ASD
Ru = 1.2(10 kips) + 1.6(30 kips) = 60 kips Ra = 10 kips + 30 kips = 40 kips

Check bolt shear. Check end plate for bolt Check bolt shear. Check end plate for bolt Manual
bearing, shear yielding, shear rupture and bearing, shear yielding, shear rupture and Table 10-4
block shear rupture. block shear rupture.

Try 3 rows of bolts and 4 in. plate thickness Try 3 rows of bolts and 4 in. plate thickness

φRn = 76.4 kips > 60 kips o.k. Rn / Ω= 50.9 kips > 40 kips o.k.

<!-- p. 280 -->

IIA-37

Check weld shear, check beam web shear Check weld shear, check beam web shear
rupture rupture Manual
Table 10-4
Try 4-in. weld. Try 4-in. weld.

twmin = 0.381 in. > 0.355 in. Proration req’d twmin = 0.381 in. > 0.355 in. Proration req’d

(0.355 in.) (0.355 in.)
φRn = 89.1 kips Rn / Ω= 59.4 kips
(0.381 in.) (0.381 in.)

\= 83.0 kips > 60 kips o.k. = 55.3 kips > 40 kips o.k.

Check supporting member web or flange for Check supporting member web or flange for Manual
bolt bearing bolt bearing Table 10-4

φRn = (526 kips/in.)(0.400 in.) Rn / Ω= (351 kips/in.)(0.400 in.)

\= 210 kips > 60 kips o.k. = 140 kips > 40 kips o.k.

Check coped section

As was shown in Example II.A-4, coped section does not control design. o.k.

Check web shear

As was shown in Example II.A-4, web shear does not control design. o.k.

Note: See Example II.A-4 for an all-bolted double-angle connection and Example II.A-5 for
a bolted/welded double-angle connection.

<!-- p. 281 -->

IIA-38

Example II.A-12 All-Bolted Unstiffened Seated Connection
(beam-to-column web).

Given:

Design an all-bolted unstiffened seated connection between a W16×50 beam and W14×90
column web to support the following end reactions:

RD = 9 kips
RL = 27.5 kips

Use d-in. diameter ASTM A325-N bolts in standard holes.

Material Properties:

Beam W16×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3,
Angles ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-4

Geometric Properties:

Beam W16×50 tw = 0.380 in. d = 16.3 in. tf = 0.630 in. k = 1.03 in. Manual
Column W14×90 tw = 0.440 in. Table 1-1

<!-- p. 282 -->

IIA-39

Solution:

LRFD ASD
Ru = 1.2(9 kips) + 1.6(27.5 kips) = 55 kips Ra = 9 kips + 27.5 kips = 36.5 kips

Check beam web Check beam web Section J10

For local web yielding, For local web yielding,

Ru −φR1 Ra − R1 / Ω Manual
N min = ≥ k N min = ≥ k Table 9-4 φR2 R2 / Ω

55 kips − 49.0 kips 36.5 kips − 32.7 kips
\= ≥ 1.03 = ≥ 1.03
19.0 kips 12.7 kips

\= 0.316 in. \< 1.03 in. = 0.299 in. \< 1.03 in.

\= 1.03 in. = 1.03 in.

For web crippling, For web crippling,

N N
When ≤ 0.2 When ≤ 0.2
d d

Ru −φR3 Ra − R3 / Ω N min = N min =
φR4 R4 / Ω

55 kips − 67.2 kips 36.5 kips − 44.8 kips
\= =
5.81 kips 3.87 kips

which results in a negative quantity. which results in a negative quantity.

N N
When > 0.2 When > 0.2
d d

Ru −φR5 Ra − R5 / Ω N min = N min =
φR6 R6 / Ω

55 kips − 60.9 kips 36.5 kips − 40.6 kips
\= =
7.74 kips/in. 5.16 kips/in.

which results in a negative quantity. which results in a negative quantity.

Thus, N min = 1.03 in. Thus, N min = 1.03 in.

<!-- p. 283 -->

IIA-40

Check shear yielding and flexural yielding Check shear yielding and flexural yielding of
of angle. Check local yielding and angle. Check local yielding and crippling
crippling of beam web of beam web

Try an 8 in. angle length with a w in. Try an 8 in. angle length with a w in. Manual
thickness and a 32 in. minimum outstanding thickness and a 32 in. minimum outstanding Table 10-5
leg. leg.

φRn = 117 kips > 55 kips o.k. Rn /Ω = 77.6 kips > 36.5 kips o.k.

Try L6×4×w (4-in. OSL), 8-in. long with Try L6×4×w (4-in. OSL), 8-in. long with
52-in. bolt gage, connection type B (four 52-in. bolt gage, connection type B four
bolts). bolts).

For d-in. diameter ASTM A325-N bolts, For d-in. diameter ASTM A325-N bolts,
Manual φRn = φ v rn n = 86.6 kips > 55 kips o.k. Rn / Ω= ( rn / Ω ) n = 57.7 kips > 36.5 kips o.k. Table 10-5

Check bolt bearing on the angle Check bolt bearing on the angle
Manual
Bolt single shear strength = 21.6 kips Bolt single shear strength = 14.4 kips Table 7-1
and
(2.4 dtFu ) Section J3.10 Rn / Ω= φRn = φ (2.4 dtFu ) Ω Eqn (J3-6a)

\= 0.75(2.4)(7 8 in.)(3 4 in.)(58 ksi) (2.4)(7 8 in.)(3 4 in.)(58 ksi)
\=
2.00

\= 68.5 kips > 21.6 kips o.k. = 45.7 kips > 14.4 kips o.k.

Check supporting column Check supporting column
Manual
Bolt single shear strength = 21.6 kips Bolt single shear strength = 14.4 kips Table 7-1
and
(2.4 dtFu ) Section J3.10 Rn / Ω= φRn = φ (2.4 dtFu ) Ω Eqn (J3-6a)
(2.4)(7 8 in.)(0.440 in.)(65 ksi)
\= = 0.75(2.4)(7 8 in.)(0.440 in.)(65 ksi) 2.00

\= 45.0 kips > 27.1 kips o.k. = 30.0 kips > 14.4 kips o.k.

Select top angle and bolts
Use an L4×4×4 with two d-in. diameter ASTM A325-N through each leg.

<!-- p. 284 -->

IIA-41

Example II.A-13 Bolted/Welded Unstiffened Seated Connection
(beam-to-column flange)

Given:

Design an unstiffened seated connection between a W21×62 beam and a W14×61 column
flange, to support the following beam end reactions:

RD = 9 kips
RL = 27.5 kips

Use w-in. diameter ASTM A325-N bolts in standard holes to connect the supported beam to
the seat and top angles. Use 70 ksi electrode welds to connect the seat and top angles to the
column flange.

Note: For calculation purposes, assume setback is equal to ¾ in. to account for possible
beam underrun.

Material Properties:

Beam W21×62 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×61 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Angles ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Beam W21×62 tw = 0.400 in. d = 21.0 in. tf = 0.615 in. k = 1.12 in. Manual
Column W14×61 tf = 0.645 in. Table 1-1

<!-- p. 285 -->

IIA-42

Solution:

LRFD ASD
Ru = 1.2(9 kips) + 1.6(27.5 kips) = 55 kips Ra = 9 kips + 27.5 kips = 36.5 kips

Check the strength of the beam web Check the strength of the beam web

For local web yielding For local web yielding

Ru −φR1 Ra − R1 / Ω Manual
N min = ≥ k N min = ≥ k Table 9-4 φR2 R2 / Ω
55 kips − 55.8 kips 36.5 kips − 37.2 kips
\= ≥ 1.12 in. = ≥ 1.12 in.
20 kips 13.3 kips

N min = 1.12 in. N min = 1.12 in.

For web crippling, For web crippling,

⎛ N ⎞ 3.25 ⎛ N ⎞ 3.25
⎜ ⎟ = ⎜ ⎟ = ⎝ d ⎠ max 21 ⎝ d ⎠ max 21
\= 0.16 \< 0.2 = 0.16 \< 0.2

N N
When ≤ 0.2 When ≤ 0.2
d d
Ru −φR3 Ra − R3 / Ω N min = N min =
φR4 R4 / Ω
55 kips − 71.7 kips 36.5 kips − 47.8 kips
\= =
5.37 kips 3.58 kips

which results in a negative quantity. which results in a negative quantity.

Therefore, N min = 1.12 in. Therefore, N min = 1.12 in.

Check shear yielding and flexural yielding of Check shear yielding and flexural yielding of
angle. Check local yielding and crippling angle. Check local yielding and crippling
of beam web of beam web

Try an 8 in. angle length with a s-in. Try an 8 in. angle length with a s-in.
thickness and a 32 in. minimum outstanding thickness and a 32 in. minimum outstanding
leg. leg.

Nreq > 18 in. Nreq > 18 in.

For N = 18 in. For N = 18 in.

φRn =81.0 kips > 55 kips o.k. Rn /Ω = 53.9 kips > 36.5 kips o.k. Manual
Table 10-6

<!-- p. 286 -->

IIA-43

Try an L8×4×s (4 in. OSL), 8 in. long with Try an L8×4×s (4 in. OSL), 8 in. long with
c in. fillet welds. c in. fillet welds.

φRn = 66.7 kips > 55 kips o.k. Rn /Ω = 44.5 kips > 36.5 kips o.k. Manual
Table 10-6
Use two w-in. diameter ASTM A325-N Use two w-in. diameter ASTM A325-N
bolts to connect the beam to the seat angle. bolts to connect the beam to the seat angle.

The strength of the bolts must be verified if horizontal forces are added to the connection.

Select top angle, bolts, and welds
Use L4×4×4 with two w in. diameter ASTM A325-N bolts through the supported-beam leg of Specification
the angle. Use a x-in. fillet weld along the toe of the angle to the column flange. See the Sec. J2.2b
discussion in Manual Part 10.

Note: See Example II.A-12 for an all-bolted unstiffened seat connection.

<!-- p. 287 -->

IIA-44

Example II.A-14 Stiffened Seated Connection (beam-to-column flange).

Given:

Design a stiffened seated connection between a W21×68 beam and a W14×90 column flange,
to support the following end reactions:

RD = 21 kips
RL = 62.5 kips

Use w in. diameter ASTM A325-N bolts in standard holes to connect the supported beam to
the seat plate and top angle. Use 70 ksi electrode welds to connect the stiffener and top angle
to the column flange.

Note: For calculation purposes, assume setback is equal to ¾ in. to account for possible
beam underrun.

Material Properties:

Beam W21×68 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Angles and plates ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

Beam W21×68 tw = 0.430 in. d = 21.1 in. tf = 0.685 in. Manual
Column W14×90 tf = 0.710 in. Table 1-1

<!-- p. 288 -->

IIA-45

Solution:

LRFD ASD
Ru = 1.2(21 kips) + 1.6(62.5 kips) = 125 kips Ra = 21 kips + 62.5 kips = 83.5 kips

Determine stiffener width W required Determine stiffener width W required

For web crippling, assume N/d > 0.2 For web crippling, assume N/d > 0.2

Ru −φR5 Ra − R5 / Ω Manual
Wmin = + setback Wmin = + setback Table 9-4 φR6 R6 / Ω

125 kips − 75.9 kips 83.5 kips − 50.6 kips 3 = + 34 in. = + 4 in.
7.94 kips/in. 5.29 kips/in.

\= 6.93 in. = 6.97 in.

For local web yielding, For local web yielding,

Ru −φR1 Ra − R1 / Ω
Wmin = + setback Wmin = + setback Manual
φR2 R2 / Ω Table 9-4

125 kips − 63.7 kips 3 83.5 kips − 42.5 kips 3 = + 4 in. = + 4 in.
21.5 kips/in. 14.3 kips/in.

\= 3.60 in. \< 6.93 in. = 3.62 in. \< 6.97 in.

Use W = 7 in. Use W = 7 in.

Check assumption Check assumption

N 6.93 in. − 0.75 in. N 6.97 in. − 0.75 in.
\= =
d 21.1 in. d 21.1 in.

\= 0.293 > 0.20 o.k. = 0.295 > 0.20 o.k.
Determine stiffener length L and stiffener to Determine stiffener length L and stiffener to
column flange weld size column flange weld size

Try a stiffener with L = 15 in. and c in. Try a stiffener with L = 15 in. and c in. Manual
weld weld Table 10-8

φRn = 139 kips > 125 kips o.k. Rn /Ω = 93.0 kips > 83.5 kips o.k.

Determine weld requirements for seat plate

Use c-in. fillet welds on each side of the stiffener. Minimum length of seat-plate-to-column Manual
flange weld is 0.2(L) = 3 in. If the weld between the seat plate and stiffener plate is required to Part 10
be stronger than the weld between the seat plate and the column flange, use c-in. fillet welds
on each side of the stiffener to the seat plate, length of weld = 7 in. > 3 in. o.k.

<!-- p. 289 -->

IIA-46

Determine the seat plate dimensions

A width of 8 in. is adequate to accommodate two w-in. diameter ASTM A325-N bolts on a Manual
52 in. gage connecting the beam flange to the seat plate. Part 10

Use a PLa in.×7 in.×8 in. for the seat plate.

LRFD ASD
Determine the stiffener plate thickness Determine the stiffener plate thickness

Determine minimum plate thickness to Determine minimum plate thickness to Manual
develop the stiffener-to-seat-plate weld. develop the stiffener-to-seat-plate weld. Section 10

t min = 2w = 2(c in.) = s in. t min = 2w = 2(c in.) = s in.

Determine minimum plate thickness for a Determine minimum plate thickness for a
stiffener with Fy = 36 ksi and beam with Fy = stiffener with Fy = 36 ksi and beam with Fy =
50 ksi. 50 ksi.

50 50 50 50
t min = t w = (0.430 in.) t min = t w = (0.430 in.)
36 36 36 36

\= 0.597 in. \< s in. = 0.597 in. \< s in.

Use a PL s in.×7 in.×15 in. Use a PL s in.×7 in.×15 in.

Check column web thickness

3.09 D 3.09(5)(2)
t w min = = = 0.475 in.
Fu 65

tw for W14×90 = 0.44 in.

LRFD ASD
⎛ 0.440 in. ⎞ Rn ⎛ 0.440 in. ⎞
φRn = 139 kips ⎜ ⎟ = 93.0 kips ⎜ ⎟ ⎝ 0.475 in. ⎠ Ω ⎝ 0.475 in. ⎠
\= 129 kips > 125 kips o.k. = 86.1 kips > 83.5 kips o.k.

Select top angle, bolts, and welds

Use a L4×4×4 with two w in. diameter ASTM A325-N bolts through the supported-beam leg Section
of the angle. Use a x in. fillet weld along the toe of the supported leg of the angle. J2.2b

<!-- p. 290 -->

IIA-47

Example II.A-15 Stiffened Seated Connection (beam-to-column web).

Given:

Design a stiffened seated connection between a W21×68 beam and a W14×90 column web to
support the following beam end reactions:

RD = 21 kips
RD = 62.5 kips

Use w in. diameter ASTM A325-N bolts in standard holes to connect the supported beam to
the seat plate and top angle. Use 70 ksi electrode welds to connect the stiffener and top angle
to the column web.

Material Properties:

Beam W21×68 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Angles and plates ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

Beam W21×68 tw = 0.430 in. d = 21.1 in. tf = 0.685 in. Manual
Column W14×90 tw = 0.440 in. Table 1-1

<!-- p. 291 -->

IIA-48

Solution:

LRFD ASD
Ru = 1.2(21 kips) + 1.6(62.5 kips) = 125 kips Ra = 21 kips + 62.5 kips = 83.5 kips

Determine stiffener width W required Determine stiffener width W required

As previously calculated in As previously calculated in
Example II.A-14, use W = 7 in. Example II.A-14, use W = 7 in.

Determine stiffener length L and stiffener to Determine stiffener length L and stiffener to
column web weld size column web weld size

As previously calculated in As previously calculated in
Example II.A-14, use L = 15 in. and c in. Example II.A-14, use L = 15 in. and c in.
weld size. weld size.

Determine weld requirements for seat plate

As previously calculated in Example II.A-14, use 3 in. of c in. weld on both sides of the seat
plate for the seat-plate-to-column-web welds and for the seat-plate-to-stiffener welds.

Determine seat plate dimensions

For a column-web support, the maximum distance from the face of the support to the line of Manual
the bolts between the beam flange and seat plate is 32 in. The PL a in.×7 in.×8 in. previously Table 10-8
selected in Example II.A-14 will accommodate these bolts.

Determine stiffener plate thickness

As previously calculated in Example II.A-14, use a PL s in.×7 in.×15 in.

Select top angle, bolts, and welds

Use L4×4×4 with two w in. diameter ASTM A325-N bolts through the supported-beam leg of Section
the angle. Use a x in. fillet weld along the toe of the supported leg of the angle. J2.2b

Check the strength of the column web

If only one side of the column web has a stiffened seated connection, then Manual
Table 10-8
3.09 D 3.09 ( 5 )
t w min = = = 0.24 in.
Fu 65

If both sides of the column web have a stiffened seated connection, then

6.19 D 6.18 ( 5 )
t w min = = = 0.48 in.
Fu 65

Column tw = 0.44 in., which is sufficient for the one-sided stiffened seated connection shown.

Note: Additional detailing considerations for stiffened-seated connections are given on page
10-94 of the Manual.

<!-- p. 292 -->

IIA-49

Example II.A-16 Offset Unstiffened Seated Connection
(beam-to-column flange).

Given:

Determine the seat angle and weld size required for the unstiffened seated connection between
a W14×48 beam and a W12×65 column-flange connection with an offset of 5½ in, to support
the following beam end reactions:

RD = 5 kips
RL = 15 kips

Use 70 ksi electrode welds to connect the seat angle to the column flange.

Material Properties:

W14×48 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
W12×65 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Angle ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

W14×48 tw = 0.340 in. d = 13.8 in. tf = 0.595 in. k = 1.19 in. Manual
W12×65 tf = 0.605 in. Table 1-1

<!-- p. 293 -->

IIA-50

Solution:

LRFD ASD
Ru = (1.2)(5 kips)+(1.6)(15 kips) = 30 kips Ra = 5 kips + 15 kips = 20 kips

Design the seat angle and welds Design the seat angle and welds

The required strength for the right-hand weld The required strength for the right-hand weld
can be determined by summing moments can be determined by summing moments
about the left-hand weld. about the left-hand weld.

( 30 kips )( 3 in.) ( 20 kips )( 3 in.)
RuR = = 25.7 kips RaR = = 17.1 kips
3 12 in. 3 12 in.

Selecting the welds on both sides of the seat Selecting the welds on both sides of the seat
to resist this force, the total required strength to resist this force, the total required strength
would be Ru = 51.4 kips would be Ra = 34.2 kips

For local web yielding, For local web yielding,

Ru −φR1 Ra − ( R1 / Ω ) Manual N min = ≥ k N min = ≥ k φR2 ( R2 / Ω ) Table 9-4

( 51.4 kips ) − ( 50.4 kips ) ( 34.2 kips ) − ( 33.6 kips ) = > 1.19 in. > 1.19 in. =
17.0 kips/in. 11.3 kips/in.

\= 0.06 in. > 1.19 in. = 0.05 in. > 1.19 in.

Nmin = 1.19 in. Nmin = 1.19 in.

For web crippling, For web crippling,

N N When ≤ 0.2 When ≤ 0.2 d d
Ru −φR3 Ra − ( R3 / Ω ) N min = φR4 N min = ( R4 / Ω ) Manual
( 51.4 kips ) − ( 55.2 kips ) Table 9-4 = ( 34.2 kips ) − ( 36.8 kips )
5.19 kips/in. =
3.46 kips/in.

which results in a negative quantity which results in a negative quantity.
Thus, Nreq = 1x in. Thus, Nreq = 1x in.

A 6 in. angle length with a s-in. thickness A 6 in. angle length with a s-in. thickness
provides provides
Rn /Ω= 36.7 kips > 34.2 kips o.k. Manual φRn = 55.2 kips > 51.4 kips o.k. Table 10-6

<!-- p. 294 -->

IIA-51

With a L7×4 (OSL) angle and c-in. fillet With a L7×4 (OSL) angle and c-in. fillet
welds, the weld strength from the tables is welds, the weld strength from the tables is

φRn = 66.7 kips > 51.4 kips o.k. Rn /Ω= 44.5 kips > 34.2 kips o.k.

Use L7×4× s×6 in. for the seat angle. Use Use L7×4×s×6 in. for the seat angle. Use
two w in. diameter ASTM A325-N bolts to two w in. diameter ASTM A325-N bolts to
connect the beam to the seat angle and weld connect the beam to the seat angle and weld
the angle to the column with c-in. fillet the angle to the column with c-in. fillet
welds. welds.

Select top angle, bolts, and welds Select top angle, bolts, and welds

Use L4×4×4 with two w-in. diameter Use L4×4×4 with two w-in. diameter
ASTM A325-N bolts through the ASTM A325-N bolts through the
outstanding leg of the angle. outstanding leg of the angle.

Use a x-in. fillet weld along the toe of the Use a x-in. fillet weld along the toe of the Section J2.2b
angle to the column flange (maximum size angle to the column flange (maximum size
permitted by the Specification). permitted by the Specification).

<!-- p. 295 -->

IIA-52

Example II.A-17 Single-Plate Connection
(conventional – beam-to-column flange)

Given:

Design a single-plate connection between a W16×50 beam and a W14×90 column flange to
support the following beam end reactions:

RD = 8 kips
RL = 25 kips

Use w-in. diameter ASTM A325-N bolts in standard holes and 70 ksi electrode welds.

Material Properties:

Beam W16×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

Beam W16×50 tw = 0.380 in. d = 16.3 in. tf = 0.630 in. Manual
Column W14×90 tf = 0.710 in. Table 1-1

<!-- p. 296 -->

IIA-53

Solution:
LRFD ASD
Ru = 1.2(8 kips) + 1.6(25 kips) = 50 kips Ra = 8 kips + 25 kips = 33 kips

Check bolt shear. Check plate for shear Check bolt shear. Check plate for shear
yielding, shear rupture, and block shear yielding, shear rupture, and block shear
rupture rupture

Try four rows of bolts, 4 in. single plate Try four rows of bolts, 4 in. single plate Manual
thickness, and x in. fillet weld size. thickness, and x in. fillet weld size. Table 10-9

φRn = 52.2 kips > 50 kips o.k. Rn / Ω= 34.8 kips > 33 kips o.k.

Check minimum fillet weld size Check minimum fillet weld size
Weld size = 316 in. o.k. Weld size = 316 in. o.k. Section J2.2b
Check beam web for bolt bearing. Block Check beam web for bolt bearing. Block
shear rupture, shear yielding and shear shear rupture, shear yielding and shear
rupture will not control for an uncoped rupture will not control for an uncoped
section. section.

For an uncoped section, For an uncoped section,
Manual
φRn = (351 kips/in.)(0.380 in.) Rn / Ω= ( 234 kips/in. )( 0.380 in. ) Table 10-1

\= 133 kips > 50 kips o.k. = 88.9 kips > 33 kips o.k.

<!-- p. 297 -->

IIA-54

Example II.A-18 Single-Plate Connection (beam-to-girder web)

Given:

Design a single-plate connection between a W18×35 beam to a W21×62 girder web to support
the following beam end reactions:

RD = 6.5 kips
RL = 20 kips

Top flange coped 2-in. deep by 4 -in. long, Lev = 1½ in., Leh = 1½ in. (assumed to be 1¼ in. for
calculation purposes to account for possible underrun in beam length),

Use w-in. diameter ASTM A325-N bolts in standard holes and 70 ksi electrode welds.

Material Properties:

Beam W18×35 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Girder W21×62 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

Beam W18×35 tw = 0.300 in. d = 17.7 in. tf = 0.425 in. Manual
Cope c = 4 in. dc = 2 in. e = 4 ½ in. h0 = 15.7 in. Table 1-1
Girder W21×62 tw = 0.400 in.

<!-- p. 298 -->

IIA-55

Solution:

Note: The connection plate dimensions for a w in. diameter bolt in Manual Table 10-9 are Manual
based on Leh = 12 in. min. and Lev (top & bottom) = 14 in. min. Part 10

LRFD ASD
Ru = 1.2(6.5 kips) + 1.6(20 kips) = 40 kips Ra = 6.5 kips + 20 kips = 26.5 kips

Check bolt shear. Check plate for bolt Check bolt shear. Check plate for bolt
bearing, shear yielding, shear rupture, and bearing, shear yielding, shear rupture, and
block shear rupture block shear rupture

Try four rows of bolts, 4 in. single plate Try four rows of bolts, 4 in. single plate Manual
thickness, and x in. fillet weld size. thickness, and x in. fillet weld size. Table 10-9

φRn = 52.2 kips > 40 kips o.k. Rn / Ω= 34.8 kips > 26.5 kips o.k.

Check minimum fillet weld size Check minimum fillet weld size
Weld size = 316 in. o.k. Weld size = 316 in. o.k. Section J2.2b
Check beam web for bolt bearing, block Check beam web for bolt bearing, block
shear rupture, shear yielding and shear shear rupture, shear yielding and shear
rupture rupture

For coped section, n= 4, Lev = Leh = 12 in. For coped section, n= 4, Lev = Leh = 12 in. Manual
Table 10-1
φRn = (257 kips/in.)(0.300 in.) Rn / Ω= (171 kips/in. )( 0.300 in. )

\= 77.1 kips > 40 kips o.k. = 51.3 kips > 26.5 kips o.k.

Note: For coped beam sections, the limit states of flexural rupture and local buckling should be
checked independently per Part 9. However, for the shallow cope in this example, flexural
yielding and local buckling do not govern. For a illustration of these checks, see Example
II.A-4.

<!-- p. 299 -->

IIA-56

Example II.A-19 Extended Single-Plate Connection
(beam-to-column web)

Given:

Design the connection between a W16×36 beam and the web of a W14×90 column, to support
the following beam end reactions:

RD = 6 kips
RL = 18 kips

Use d-in. diameter ASTM A325-N bolts in standard holes. The beam is braced by the floor
diaphragm.

Material Properties:

W16×36 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Plate Material ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

W16×36 tw = 0.295 in. d = 16.0 in. Manual
W14×90 tw = 0.440 in. bf = 14.5 in. Table 1-1

Solution:

Determine the required strength
LRFD ASD
Ru = 1.2(6 kips) + 1.6(18 kips) = 36 kips Ra = 6 kips + 18 kips = 24 kips

<!-- p. 300 -->

IIA-57

Determine the distance from the support to the first line of bolts

a = 9 in.

LRFD ASD
Determine the bearing strength of one bolt Determine the bearing strength of one bolt
on the beam web on the beam web

φnr = 2.4Futwdb rn 2.4Fu t w db =
Ω Ω

\= 0.75(2.4)(65)(0.295)(0.875)(2.33) = 2.4(65)(0.295)(0.875)(2.33)/2.00
Manual
Table 7-5 = 30.2 kips = 20.1 kips
Determine the shear strength of one bolt Determine the shear strength of one bolt

φnr = 21.6 kips nr = 14.4 kips
Ω

Therefore, shear controls over bearing Therefore, shear controls over bearing

Determine the strength of the bolt group Determine the strength of the bolt group

Manual For e = 10.5 in., C = 2.33 For e = 10.5 in., C = 2.33
Table 7-8

φRn = C φrn = 2.33(21.6 kips) Rn Crn = = 2.33(14.4 kips)
Ω Ω
\= 50.3 kips > 36 kips o.k. = 33.6 kips > 24 kips o.k

Determine the maximum plate thickness such that the plate will yield before the bolts shear.

Mmax = 1.25FnvAbC′

1.25Fnv = 1.25(48 ksi) = 60 ksi

Ab = 0.601 in.2

C′= 26 in.

Mmax = (60 ksi)(0.601 in.2)(26 in.)

\= 938 kip-in. Manual
Table 7-8 6M max 6(938 kip-in.)
t max = 2 = 2 = 1.09 in.
Fy d 36 ksi(12 in.)

<!-- p. 301 -->

IIA-58

Try a plate thickness of ½ in.

LRFD ASD
Check flexural strength of the plate Check flexural strength of the plate

The required strength is The required strength is

Mu = Ru e = (36 kips)(9 in.) Ma = Ra e = (24 kips)(9 in.)

\= 324 in.-kips = 216 in.-kips

Check shear yielding of the plate Check shear yielding of the plate

φRn = φ0.6Fy Ag Rn / Ω = 0.6Fy Ag / Ω Eqn. J4-3

φ =1.00 Ω =1.50

\= (1.00)(0.6)(36 ksi)(12 in.)(2 in.) = (0.6)(36 ksi)(12 in.)(2 in.)/1.50

\= 130 kips > 36 kips o.k. = 86.4 kips > 24 kips o.k.

Determine critical flexural stress in presence Determine critical flexural stress in presence
of shear stress, fv of shear stress, fv

36 kips 24 kips
fv = = 6 ksi fv = = 4 ksi
( 12 in.)(12 in.) ( 12 in.)(12 in.)

2 2 ⎛ Fy ⎞ − 3 f v 2 Fcr φFcr = ( φFy ) = − 3 f v 2 ⎜ ⎟ Ω ⎝ Ω ⎠

\= (0.9 × 36 ksi) 2 − 3(6 ksi) 2 ⎛ 36 ksi ⎞ 2 2
\= ⎜ ⎟ − 3(4 ksi) ⎝ 1.67 ⎠
\= 30.7 ksi = 20.4 ksi

( 12 in.)(12 in.) 2 M n Fcr ( 12 in.)(12 in.) 2 φM n = φFcr Z = ( 30.7 ksi ) = Z = ( 20.4 ksi ) 4 Ω Ω 4

\= 503 kip-in. > 324 kip-in. o.k. = 367 kip-in. > 216 kip-in. o.k.

t p d 2 ⎡ d b + 0.125 ⎤ 0.5(12) 2 ⎡ 0.875 + 0.125 ⎤ 3
Z net = ⎢1 − ⎥ = ⎢1 − ⎥ = 12.0 in. 4 ⎣ 3 ⎦ 4 ⎣ 3 ⎦

<!-- p. 302 -->

IIA-59

LRFD ASD
For flexural rupture, For flexural rupture,

φM n = φFu Z net M n / Ω= Fu Z net / Ω

φ = 0.75 Ω = 2.00
3 ( 58 ksi )(12.0 in. ) 3 Fu Z net / Ω= φFu Z net = 0.75 ( 58 ksi )(12.0 in. ) 2.00

\= 522 in.-kips > 324 in.-kips o.k. = 348 in.-kips > 216 in.-kips o.k.

Check shear rupture of the plate

⎡An = ( t p ) ⎣ d - n ( d b + 0.125 in.) ⎤⎦
4 in.2 = ( 12 in.) ⎡⎣ (12 in.) - ( 4 )( 0.875 in.+0.125 in ) ⎤=⎦
LRFD ASD
φ = 0.75 Ω = 2.00

φRn = 0.6 Fu An 0.6 Fu An Eqn. J4-4 Rn / Ω= Ω
2 2 = 0.75(0.6) ( 58 ksi )( 4 in. ) 0.6 ( 58 ksi )( 4 in. ) =
2.00
\= 104 kips > 24 kips o.k.
\= 69.6 kips > 24 kips o.k.

Check block shear rupture of the plate Check block shear rupture of the plate

n = 4, Lev = 12 in. Leh = 14 in., n = 4, Lev = 12 in. Leh = 14 in.,

Rn Fu Ant U bs ⎛ 0.6 Fy Agv Fu Anv ⎞ Eqn. J4-5 = + min , ⎜ ⎟ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) Ω Ω ⎝ Ω Ω ⎠

Tension rupture component Tension rupture component
Manual
Table 9-3a φFu Ant = 35.4 kips/in.( 12 in.) Fu Ant / Ω= 23.6 kips/in.( 12 in.)

Shear yielding component Shear yielding component

Manual
φ 0.6 Fy Agv = 170 kips/in.( 12 in.) 0.6 Fy Agv / Ω= 113 kips/in.( 12 in.) Table 9-3b

Shear component Shear component
φ 0.6 Fu Anv = 194 kips/in.( 12 in.) 0.6 Fu Anv / Ω= 129 kips/in.( 12 in.) Manual
Table 9-3c
φRn = (170 kips/in. + 35.4 kips/in.) ( 12 in.) Rn / Ω= (113 kips/in. + 23.6 kips/in.)( 12 in.)

\= 103 kips > 36 kips o.k. = 68.3 kips > 24 kips o.k.

<!-- p. 303 -->

IIA-60

Check local buckling of the plate Manual
Part 9
This check is analogous to the local buckling check for doubly coped beams as illustrated
previously in the Manual Part 9 where c = 6 in. and dc = 12 in. at both the top and bottom
flanges

Fcr = Fy Q
ho Fy
λ =
⎛ ho ⎞ 2
10t w 475 + 280 ⎜ ⎟ ⎝ c ⎠
(12 in.) 36 ksiλ = = 0.462
⎛ 12.0 in. ⎞ 2 1 10 475 + 280 ⎜ ⎟ ( 2 ) ⎠ ⎝ 9 in.

λ \< 0.7, therefore, Q = 1

Fcr = Fy

Therefore, plate buckling does not control.

<!-- p. 304 -->

IIA-61

Example II.A-20 All-Bolted Single-Plate Shear Splice

Given:

Design an all-bolted single-plate shear splice between a W24×55 beam and a W24×68 beam.

RD = 10 kips
RL = 30 kips

Use d-in. diameter ASTM A325-N bolts with 5 in. between vertical bolt rows.

Material Properties:

W24×55 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
W24×68 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Splice Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

Beam W24×55 tw = 0.395 in. Manual
Beam W24×68 tw = 0.415 in. Table 1-1

<!-- p. 305 -->

IIA-62

Solution:

Design the bolt groups

Note: When the splice is symmetrical, the eccentricity of the shear to the center of gravity of
either bolt group is equal to half the distance between the centroids of the bolt groups.
Therefore, each bolt group can be designed for the shear, Ru or Ra, and one-half the eccentric
moment, Rue or Rae.

Using a symmetrical splice, each bolt group will carry one-half the eccentric moment.
Thus, the eccentricity on each bolt group e/2 = 22 in.

LRFD ASD
Ru = 1.2(10 kips) + 1.6(30 kips) Ra = 10 kips + 30 kips
\= 60 kips = 40 kips

For bolt shear, For bolt shear,

φrn = 21.6 kips/bolt. rn/Ω = 14.4 kips/bolt. Manual
Table 7-1
For bearing on the web of the W24×55, For bearing on the web of the W24×55,

φrn = (102 kips/in.)(0.395 in.) rn/Ω = (68.3 kips/in.)(0.395 in.) Manual
Table 7-6
\= 40.3 kips/bolt = 27.0 kips/bolt

Since bolt shear is more critical, Since bolt shear is more critical,

Ru 60 kips Ra 40 kips C min = = = 2.78 C min = = = 2.78
φrn 21.6 kips/bolt rn / Ω 14.4 kips/bolt

with θ = 00 and ex = 22 in., a four-bolt with θ = 00 and ex = 22 in., a four-bolt
connection provides connection provides
Manual
C = 3.07 > 2.78 o.k. C = 3.07 > 2.78 o.k. Table 7-7

Design splice plate Design splice plate

Try PL a in. ×8 in. ×1’-0”. Try PL a in. ×8 in. ×1’-0”.

Check flexure of the plate Check flexure of the plate

Ru e ( 60 kips )( 5 in.) Ra e ( 40 kips )( 5 in.) M u = = = 150 in.-kips M a = = = 100 in.-kips
2 2 2 2
For flexural yielding, For flexural yielding,

Manual
φMn = φFyZx Mn/Ω = FyZx/Ω Part. 15

φ = 0.90 Ω = 1.67
⎡ ( 38 in.)(12 in.) 2 ⎤ ⎡ ( 38 in. )(12 in. ) 2 ⎤ = ( 0.90 )( 36 ksi ) ⎢ ⎥ = ( 36 ksi ) ⎢ ⎥ /1.67
⎢⎣ 4 ⎥⎦ ⎢⎣ 4 ⎥⎦

\= 437 in.-kips > 150 in.-kips = 291 in.-kips > 100 in.-kips

<!-- p. 306 -->

IIA-63

For flexure rupture,

⎡ ⎤ t s 2 n ( n 2 − 1)( d h + 116 in.) 2
Z net ≈ ⎢ d − ⎥
4 ⎢ d ⎥ ⎣ ⎦

15 ⎡ 3 2 ( 3 in.) 2 ( 4 )( 4 2 − 1)( 8 in. 16 in. + 116 in.) ⎤ 3 ≈ ⎢(12 in.) − ⎥ = 9.28 in.
4 ⎢ 12 in. ⎥ ⎣ ⎦

LRFD ASD
φ = 0.75 Ω = 2.00

φMn = φFuZnet Mn/Ω = FuZnet/Ω

\= (0.75)(58 ksi)(9.28 in3) = (58 ksi)(9.28 in3) / 2.00

\= 404 in.-kips > 150 in.-kips o.k. = 269 in.-kips > 100 in.-kips o.k.

Check shear yielding of the plate Check shear yielding of the plate

/ Ω φRn = φ ( 0.6 Fy Ag ) Rn / Ω= ( 0.6 Fy Ag ) Eqn. J4-3

φ = 1.00 Ω = 1.50
\= 1.00 ( 0.6 ( 36 ksi )(12 in.)( 38 in.) ) = ( 0.6 ( 36 ksi )(12 in.)( 38 in.) ) /1.50

\= 97.2 kips > 60 kips o.k. = 64.8 kips > 40 kips o.k.

Check shear rupture of the plate Check shear rupture of the plate
φRn = φ ( 0.6 Fu An ) Rn / Ω= ( 0.6 Fu An ) / Ω Eqn. J4-4

φ = 0.75 Ω = 2.00

in.) / 2.00 = 0.75 ( 0.6 )( 58 ksi ) ⎡⎣ 12 in. − 4 (1 in.) ⎤⎦ ( 38 in.) = 0.6 ( 58 ksi ) ⎡⎣ 12 in. − 4 (1 in.) ⎤⎦ ( 38

\= 78.3 kips > 60 kips o.k. = 52.2 kips > 40 kips o.k.

Check block shear rupture of the plate Check block shear rupture of the plate

Leh = Lev = 12 in., Leh = Lev = 12 in.,

Rn Fu Ant U bs ⎛ 0.6 Fy Agv Fu Anv ⎞ Eqn. J4-5 = + min , ⎜ ⎟ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) Ω Ω ⎝ Ω Ω ⎠

Because maximum shear stress occurs at one Because maximum shear stress occurs at one
row of bolts row of bolts Commentary
Section J4.3
Ubs = 1.00 Ubs = 1.00

<!-- p. 307 -->

IIA-64

Tension rupture component Tension rupture component
Manual
φFu Ant = 43.5 kips/in.(a in.) Fu Ant / Ω= 29.0 kips/in.(a in.) Table 9-3a

Shear yielding component Shear yielding component

Manualφ 0.6 Fy Agv = 170 kips/in.(a in.) 0.6 Fy Agv / Ω= 113 kips/in.(a in.) Table 9-3b

Shear rupture component Shear rupture component
Manual
φ 0.6 Fu Anv = 183 kips/in.(a in.) 0.6 Fu Anv / Ω= 122 kips/in.(a in.) Table 9-3c

φRn = (170 kips/in. + 43.5 kips/in.)(a in.) Rn/Ω = (113 kips/in. + 29.0 kips/in.)(a in.)

\= 80.1 kips > 60 kips o.k. = 53.3 kips > 40 kips o.k.
Use PL a in. ×8 in. ×1’-0
Use PL a in. ×8 in. ×1’-0

<!-- p. 308 -->

IIA-65

Example II.A-21 Bolted/Welded Single-Plate Shear Splice

Given:

Design a single-plate shear splice between a W16×31 beam and W16×50 beam (not illustrated)
to support the following beam end reactions:

RD = 8.0 kips
RL = 24.0 kips

Use ¾-in. diameter ASTM A325-N bolts through the web of the W16×50 and 70 ksi electrode
welds to the web of the W16×31.

Material Properties:

W16×31 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
W16×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Splice Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

W16×31 tw = 0.275 in. Manual
W16×50 tw = 0.380 in. Table 1-1

Solution:

LRFD ASD
Ru = 1.2(8 kips) + 1.6(24 kips) = 48 kips Ra = 8 kips + 24 kips = 32 kips

Design the weld group

Since the splice is unsymmetrical and the weld group is more rigid, it will be designed for the
full moment from the eccentric shear.

Assume PL a in.×8 in.×1’-0

<!-- p. 309 -->

IIA-66

kl 3 12 in.k = = = 0.292
l 12 in.

By interpolation, with θ = 00, x = 0.0538 and xl = 0.646 in.

al 5.85 in.
al = 62 in. – 0.646 in. = 5.85 in., a = = = 0.488
l 12 in.
Manual
By interpolation, C = 2.14 and the required weld size is Table 8-8

LRFD ASD
Pu ( 48 kips ) Pa Ω ( 32 kips )( 2.0 ) Dreq = = Dreq = = φCC1l 0.75 ( 2.14 )(1.0 )(12 in.) CC1l ( 2.14 )(1.0 )(12 in. )

\= 2.49 → 3 sixteenths = 2.49 → 3 sixteenths

The minimum weld size is x in. The minimum weld size is x in. Table J2.4

Use a x-in. weld size. Use a x-in. weld size.

Check shear rupture of beam web at the weld (W16×31)

For fillet welds with Fexx = 70 ksi on one side of the connection, the minimum thickness
required to match the available shear rupture strength of the connection element to the
available shear rupture strength of the base metal is:
Manual
3.09 D ( 3.09 )( 3 sixteenths ) Part 9
t min = = = 0.143 \< 0.275 in. o.k.
Fu 65 ksi

Design the bolt group

Since the weld group was designed for the full eccentric moment, the bolt group will be
designed for shear only.

LRFD ASD
For bolt shear For bolt shear

φrn = 15.9 kips/bolt rn/Ω = 10.6 kips/bolt Manual
Table 7-1
For bearing on the a-in. thick single plate, For bearing on the a-in. thick single plate,
conservatively use the design values conservatively use the design values
provided for Le = 1 ½ in. provided for Le = 1 ½ in. Manual
Table 7-6
φnr = ( 44.0 kips/in./bolt )( 38 in.) nr / Ω= ( 29.4 kips/in./bolt )( 38 in.)

φrn = 16.5 kips/bolt rn/Ω = 11.0 kips/bolt

<!-- p. 310 -->

IIA-67

Since bolt shear is more critical than bearing, Since bolt shear is more critical than bearing,

Ru Ru nmin = nmin =
φrn rn / Ω
48 kips 32 kips
\= =
15.9 kips/bolt 10.6 kips/bolt
\= 3.02 → 4 bolts = 3.02 → 4 bolts

Design the single plate

As before, try a PL a in.×8 in.×1’-0

LRFD ASD
Check flexure of the plate Check flexure of the plate
Manual
Mu = Rue = (48 kips)(5.85 in.) = 281 in.-kips Ma = Rae = (32 kips)(5.85 in.) = 187 in.-kips Part 15

For flexural yielding For flexural yielding

φ = 0.90 Ω = 1.67

φMn = φFyZx Mn/Ω = FyZx/Ω
⎡ ( 38 in.)(12 in.) 2 ⎤ ⎡ ( 38 in.)(12 in.) 2 ⎤
\= (0.9)(36 ksi) ⎢ ⎥ = (36 ksi) ⎢ ⎥ /1.67
⎣ 4 ⎦ ⎣ 4 ⎦

\= 437 in.-kips > 281 in.-kips o.k. = 291 in.-kips > 187 in.-kips o.k.

Check flexural rupture Check flexural rupture Manual
Part 9
t p d 2 t p d 2
Z net = Z x = Z net = Z x =
4 4
( 38 in.)(12 in.) 2 3 ( 38 in.)(12 in.) 2 3 = = 13.5 in = = 13.5 in
4 4

φMn = φFuZnet Fu S net M n / Ω= Ω

φ = 0.75 Ω = 2.00

3 58 ksi )(13.5 in. ) 3 ( = 0.75 ( 58 ksi )(13.5 in. ) = 2.00

\= 587 in.-kips > 281 in.-kips o.k. = 392 in.-kips > 187 in.-kips o.k.

<!-- p. 311 -->

IIA-68

Check shear yielding of the plate Check shear yielding of the plate

/ Ω Rn / Ω= ( 0.6 Fy Ag )φRn = φ ( 0.6 Fy Ag ) Eqn. J4-3

φ = 1.00 Ω = 1.50

/1.50 = 1.00 ⎡ ⎣ 0.6 ( 36 ksi )(12 in.)( 38 in.) ⎤⎦ = ⎡⎣ 0.6 ( 36 ksi )(12 in.)( 38 in.) ⎤⎦

\= 97.2 kips > 48 kips o.k. = 64.8 kips > 32 kips o.k.

Check shear rupture of the plate
Check shear rupture of the plate
Eqn. J4-4 Rn / Ω= ( 0.6 Fu An ) / Ω
φRn = φ ( 0.6 Fu An )
Ω = 2.00
φ = 0.75

7 3 12 in. − 4 ( 8 in. ) / 2.0 = 0.6 ( 58 ksi ) ⎡⎣ 8 in. ) ⎤⎦ (
7 3 12 in. − 4 ( 8 in.)= 0.75 ( 0.6 )( 58 ksi ) ⎡⎣ 8 in.) ⎤⎦ (
\= 55.5 kips > 32 kips o.k.
\= 83.2 kips > 48 kips o.k.
Check block shear rupture of the plate
Check block shear rupture of the plate
Leh = Lev = 12 in.,
Leh = Lev = 12 in.,
Thus,
Thus,

Rn Fu Ant U bs ⎛ 0.6 Fy Agv Fu Anv ⎞ Eqn. J4-5 = + min , ⎜ ⎟φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φFu Anv ) Ω Ω ⎝ Ω Ω ⎠
Ubs = 1.0
Ubs = 1.0
Tension rupture component
ManualTension rupture component
Table 9-3a
Fu Ant / Ω= 30.8 kips/in.(a in.)
φFu Ant = 46.2 kips/in.(a in.)
Shear yielding component Manual
Shear yielding component Table 9-3b
0.6 Fy Agv / Ω= 113 kips/in.(a in.)
φ 0.6 Fy Agv = 170 kips/in.(a in.)
Shear rupture component Manual
Shear rupture component Table 9-3c
0.6 Fu Anv / Ω= 129 kips/in.(a in.)
φ 0.6 Fu Anv = 194 kips/in.(a in.)
Rn/Ω = (113 kips/in. + 30.8 kips/in.)( 38 in.)
φRn = (170 kips/in. + 46.2 kips/in.)( 38 in.)
\= 53.9 kips > 32 kips o.k.
\= 81.1 kips > 48 kips o.k.
Use PL a in.×8 in.×1’-0
Use PL a in.×8 in.×1’-0

<!-- p. 312 -->

IIA-69

Example II.A-22 Bolted Bracket Plate Design

Given:

Design a bracket plate to support the following loads:

PD = 9 kips
PL = 27 kips

Use d-in. diameter ASTM A325-N bolts in standard holes

Material Properties:

Plate Material ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-4

Solution:

LRFD ASD
Ru = 1.2(9 kips) + 1.6(27 kips) = 54 kips Ra = 9 kips + 27 kips = 36 kips

Design bolts Design bolts
Ru Ra C min = C min =
φrn rn / Ω

54 kips 36 kips
\= =
21.6 kips/bolt 14.4 kips/bolt

\= 2.50 = 2.50

For θ = 00, a 52 in. gage with s = 3 in., For θ = 00, a 52 in. gage with s = 3 in.,
ex = 12 in., and n = 6 ex = 12 in., and n = 6
Manual
C = 4.53 > 2.50 o.k. C = 4.53 > 2.50 o.k. Table 7-9

<!-- p. 313 -->

IIA-70

Check bolt bearing Check bolt bearing Manual
Table 7-6
Try PLa in. × 20 in., Le ≥ 2 ¼ in. Try PLa in. × 20 in., Le ≥ 2 ¼ in.

φrn = (91.4 kips/bolt)(a in.) rn /Ω = (60.9 kips/bolt)(a in.)

\= 34.3 kips/bolt = 22.8 kips/bolt

Since this is greater than the single-shear Since this is greater than the single-shear
strength of one bolt, bolt bearing is not strength of one bolt, bolt bearing is not
critical. critical.
Check flexure in the bracket plate Check flexure in the bracket plate

On line K, the required strength Mu is On line K, the required strength Ma is

M u = Pu eb = (54 kips)(12 in. – 2w in.) M a = Pa eb = (36 kips)(12 in. – 2w in.)

\= 500 in.-kips = 333 in.-kips

For flexural yielding on line K, For flexural yielding on line K,

φ = 0.90 Ω= 1.67

φM n = φFy Z x M n / Ω= Fy Z x / Ω
⎛ ( 38 in.)( 20 in.) 2 ⎞ ( 36 ksi ) ⎜ ⎟ ⎛ ( 38 in.)( 20 in.) 2 ⎞ ⎝ 4 ⎠ = 0.90 ( 36 ksi ) ⎜ ⎟ =
⎝ 4 ⎠ 1.67

\= 1220 in.-kips > 500 in.-kips o.k. = 808 in.-kips > 333 in.-kips o.k.

For flexural rupture on line K,

⎡ ( 20 in.) 2 ⎤Z net = 38 in. ⎢ − 2 (1.5 + 4.5 + 7.5)(1 in.) ⎥
⎢ 4 ⎥ ⎣ ⎦
\= 27.4 in.3

LRFD ASD
φ = 0.75 Ω= 2.00 Section J4

3 3 ( 58 ksi )( 27.4 in. ) Fu Z net φM n = φFu Z net = 0.75 ( 58 ksi )( 27.4 in. ) Manual = M n / Ω=
Ω 2.00 Part 15

\= 1190 in.-kips > 500 in.-kips o.k. = 795 in.-kips > 333 in.-kips o.k.

<!-- p. 314 -->

IIA-71

For flexural yielding on the free edge of the triangular plate,
⎛ b ⎞ ⎛ b ⎞ 2 ⎛ b ⎞ 3
z = 1.39 − 2.2 ⎜ ⎟ + 1.27 ⎜ ⎟ − 0.25 ⎜ ⎟ Manual ⎝ a ⎠ ⎝ a ⎠ ⎝ a ⎠ Part 15
1 ⎛ 15 2 3 4 in. ⎞ ⎛ 15 1 4 in. ⎞ ⎛ 15 1 4 in. ⎞
\= 1.39 − 2.2 ⎜ ⎟ + 1.27 ⎜ ⎟ − 0.25 ⎜ ⎟ = 0.340 ⎝ 20 in. ⎠ ⎝ 20 in. ⎠ ⎝ 20 in. ⎠

LRFD ASD
φ = 0.90 Ω= 1.67

φPn = φFy zbt Fy zbt Pn / Ω= Ω

( 36 ksi )( 0.286 )(15.25 in.)( 0.375 in.) = 0.90 ( 36 ksi )( 0.340 )(15.25 in.)( 0.375 in.) =
1.67
\= 41.9 kips > 36.0 kips o.k. = 63 kips > 54.0 kips o.k.

Check local buckling of the bracket plate

b 15 14 in. = = 0.763 \< 1.0
a 20 in.

b
Since 0.5 ≤ \< 1.0,
a

⎛ Fy ⎞ ⎛ 36 ksi ⎞
\= 0.366 in. \< a in. o.k. t min = b ⎜ ⎟ = (15 14 in.) ⎜ ⎟ ⎜ ⎝ 250 ⎟⎠ ⎝ 250 ⎠

LRFD ASD
Check shear yielding of the bracket plate Check shear yielding of the bracket plate Eqn. J4-3

φ = 1.00 Ω = 1.50

Ag Ag ( 0.6 Fy ) φRn = φ ( 0.6 Fy ) Rn / Ω= Ω
\= 1.0 ( 0.6 )( 36 ksi )( 20 in.)( 38 in.) 0.6 ( 36 ksi )( 20 in.)( 38 in.) =
1.50

\= 162 kips > 54.0 kips o.k. = 108 kips > 36.0 kips o.k.

Check shear rupture of the bracket plate Check shear rupture of the bracket plate
0.6 Fu Anv Rn / Ω= φRn = φ ( 0.6 Fu ) Anv Ω
Eqn. J4-4
φ = 0.75 Ω = 2.00
in.) 0.6 ( 58 ksi ) ⎡⎣ 20 in. − 6 (1 in.) ⎤⎦ ( 38 in.) = 0.75 ( 0.6 )( 58 ksi ) ⎡⎣ 20 in. − 6 (1 in.) ⎤⎦ ( 38 =
\= 137 kips > 54.0 kips o.k. 2.00
\= 91.4 kips > 36.0 kips o.k.

<!-- p. 315 -->

IIA-72

Check block shear rupture of the bracket plate (shear plane on line K, tension plane across
bottom two bolts)

Since the eccentricity reduces the 12 bolts to 4.53 effective, the equivalent block shear rupture Manual
force applied concentric to the bolt group is Table 7-9

LRFD ASD
Ru = (54.0 kips)(12/4.53) = 143 kips. Ra = (36.0 kips)(12/4.53) = 95.4 kips

2 3 8 in.) = 2.34 in.Ant = ⎡⎣ 5 1 2 in. + 2 1 4 in − 1 1 2 ( 1 in.) ⎤⎦ (

2 3 8 in.) = 6.56 in.Agv = ( 20 in. − 2 12 in.)(

2Anv = 6.56 in.2 − 5.5 ( 1 in.)( 38 in.) = 4.50 in.

Compare

0.6FuAnv = 0.6(58 ksi)(4.50 in.2) = 157 kips

0.6FyAgv = 0.6(36 ksi)(6.56 in.2) = 142 kips

Shear on the gross area controls, thus;
Commentary
The connection has two vertical rows of bolts, therefore Ubs = 0.5 Section J4.3

2Rn = 0.6 Fy Agv + U bs Fu Ant = 142 kips + 0.5 ( 58 ksi )( 2.34 in. ) = 210 kips Eqn. J4-5

LRFD ASD
( 210 kips ) = 105 kips n / Ω= φRn = 0.75 ( 210 kips ) = 157 kips R 2.00

157 kips > 143 kips o.k. 105 kips > 95.4 kips o.k.

<!-- p. 316 -->

IIA-73

Example II.A-23 Welded Bracket Plate Design.

Given:

Design a welded bracket plate, using 70 ksi electrodes, to support the following loads:

PD = 9 kips
PL = 27 kips

Material Properties:

Plate Material ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Table 2-4

Solution:

LRFD ASD
Ru = 1.2(9 kips) + 1.6(27 kips) = 54 kips Ra = 9 kips + 27 kips = 36 kips

Assume PL2 in.×18 in.

Try a C-shaped weld with kl = 3 in. and l = 18 in. Manual
Table 8-8
k = kl/l = 3 in / 18 in = 0.167

x = 0.0221

and

al + xl = 114 in.

a(18 in.) + (0.0221)(18 in.) = 114 in.

<!-- p. 317 -->

IIA-74

a = 0.603

Interpolate using θ = 00, k = 0.167, and a = 0.603

C = 1.47

C1 = 1.0 for E70XX electrode.

LRFD ASD
Pu 54 kips Pa Ω ( 36 kips )( 2.00 ) Dreq = = Dreq = = φCC1l 0.75 (1.47 )(1.0 )(18 in.) CC1 l (1.47 )(1.0 )(18 in.)

\= 2.72 → 3 sixteenths = 2.72 → 3 sixteenths
\< ½ in. – z in. = v o.k. \< ½ in. – z in. = v o.k

Use a x-in. fillet weld. Use a x-in. fillet weld.
Table J2.4
Dmin = 3 o.k. Dmin = 3 o.k.

Check the flexural strength of the bracket Check the flexural strength of the bracket
plate plate

Conservatively taking the required moment Conservatively taking the required moment
strength of the plate as equal to the moment strength of the plate as equal to the moment
strength of the weld group, strength of the weld group,

Mu = Pu(al) = (54 kips)(0.603)(18 in.) Ma = Pa(al) = (36 kips)(0.603)(18 in.)

\= 586 in-kips = 391 in-kips

For flexural yielding of the plate,

( 12 in.)(18 in.) 2M n = Fy Z x = ( 36 ksi ) = 1,458 in.-kips
4

LRFD ASD
φ = 0.90 Ω= 1.67

(1,458 in.-kips )
M n / Ω= = 873 in.-kips Manual φM n = 0.90 (1,458 in.-kips ) = 1,312 in.-kips 1.67 Part 15

1,312 in.-kips > 586 in.-kips o.k. 873 in.-kips > 391 in.-kips o.k.

For yielding on the free edge of the triangular plate,

b 14 34 in. = = 0.820 Manual a 18 in.
2 3 Part 15
⎛ b ⎞ ⎛ b ⎞ ⎛ b ⎞ 2 3 z = 1.39 − 2.2 ⎜ ⎟ + 1.27 ⎜ ⎟ − 0.25 ⎜ ⎟ = 1.39 − 2.2 ( 0.820 ) + 1.27 ( 0.820 ) − 0.25 ( 0.820 ) ⎝ a ⎠ ⎝ a ⎠ ⎝ a ⎠
\= 0.302

3 1 4 in.)( 2 in.) = 80.2 kipsPn = Fy zbt = ( 36 ksi )( 0.302 )(14

<!-- p. 318 -->

IIA-75

LRFD ASD
φ = 0.90 Ω= 1.67

( 80.2 kips )
nP / Ω= = 48.0 kips φnP = 0.90 ( 80.2 kips ) = 72.2 kips 1.67

72.2 kips > 54.0 kips o.k. 48.0 kips > 36.0 kips o.k.

Check local buckling of the bracket plate Manual
Part 15
b
Since 0.5 ≤ \< 1.0
a

⎞ ⎛ ⎛ Fy 36 ksi ⎞ 3 = 0.354 in. \< 2 in. o.k. ⎟ = (14 4 in.) t min = b ⎜ ⎜ ⎟ ⎜ ⎝ 250 ⎟⎠ ⎝ 250 ⎠

Check shear yielding of the bracket plate

Rn = 0.6 Fy Ag = 0.6 ( 36 ksi )(18 in.)( 12 in.) = 194 kips Eqn. J4-3

LRFD ASD
φ = 1.00 Ω= 1.50

(194 kips )
nP / Ω= = 130 kips > 36.0 kips φRn = 1.00 (194 kips ) = 194 kips 1.50

194 kips > 54.0 kips o.k. 130 kips > 36.0 kips o.k.

<!-- p. 319 -->

IIA-76

Example II.A-24 Eccentrically-Loaded Bolt Group (IC method)

Given:

Determine the largest eccentric force that can be supported by the available shear strength of
the bolts using the instantaneous center of rotation method. Use d-in. diameter ASTM A325N bolts in standard holes. Assume that bolt shear controls over bearing.

Solution A:

Assume the load is vertical (θ = 00) as illustrated below

With θ = 00, with s = 3 in., e = 16 in., and n = 6: Manual
Table 7-9
C = 3.55

LRFD ASD
φrn = 21.6 kips rn / Ω = 14.4 kips Manual
Table 7-1
φRn = Cφrn Rn / Ω= C ( rn / Ω )

\= 3.55(21.6 kips) = 3.55(14.4 kips)

\= 76.7 kips = 51.1 kips

Thus, Pu must be less than or equal to 76.7 Thus, Pa must be less than or equal to 51.1
kips. kips.

Note: The eccentricity of the load significantly reduces the shear strength of the bolt group.

<!-- p. 320 -->

IIA-77

Solution B:
Assume the load acts at an angle of 750 with respect to vertical (θ = 750) as illustrated below

With θ = 750, s = 3 in., e = 16 in., and n = 6:
Manual
C = 7.90 Table 7-9

LRFD ASD
φRn = Cφrn = 7.90(21.6 kips) = 171 kips Rn / Ω= Crn / Ω = 7.90(14.4 kips)= 114 kips

Thus, Pu must be less than or equal to 171 Thus, Pa must be less than or equal to 114
kips. kips.

<!-- p. 321 -->

IIA-78

Example II.A-25 Eccentrically Loaded Bolt Group (elastic method)

Given:

Determine the largest eccentric force that can be supported by the available shear strength of
the bolts using the elastic method for θ = 0°. Compare the result with that of the previous
example. Use d in. diameter ASTM A325-N bolts in standard holes. Assume that bolt shear
controls over bearing. Ip = 406 in.4 per in.2

Solution:

LRFD ASD
Direct shear force per bolt Direct shear force per bolt Manual
Part 7
Pu Pu Pa Pa rpx = 0, rpy = = rpx = 0, rpy = =
n 12 n 12

Additional shear force due to eccentricity Additional shear force due to eccentricity

Pu ec y Pu (16 in.)(7 12 -in.) Pa ec y Pa (16 in.)(7 12 -in.)
rmx = = 4 2 rmx = = 4 2
I p 406 in. per in. I p 406 in. per in.

\= 0.296 Pu = 0.296 Pa
⎛ 5 12 -in. ⎞ ⎛ 5 12 -in. ⎞
Pu (16 in.) ⎜ ⎟ Pa (16 in.) ⎜ ⎟ Pu ec x ⎝ 2 ⎠ Pa ec x ⎝ 2 ⎠
rmy = = 4 2 rmy = = 4 2
I p 406 in. per in. I p 406 in. per in.

\= 0.108 Pu = 0.108 Pa

<!-- p. 322 -->

IIA-79

Resultant shear force Resultant shear force

ru = ( rpx + rmx ) 2 + ( rpy + rmy ) 2 ra = ( rpx + rmx ) 2 + ( rpy + rmy ) 2

2 ⎛ Pu ⎞ 2 2 ⎛ Pa ⎞ 2
\= (0 + 0.296 Pu ) + ⎜ + 0.108 Pu ⎟ = (0 + 0.296 Pa ) + ⎜ + 0.108 Pa ⎟ ⎝ 12 ⎠ ⎝ 12 ⎠

\= 0.352 Pu = 0.352 Pa

Since ru must be less than or equal to the Since ra must be less than or equal to the
available strength, available strength,

φrn 21.6 kips rn / Ω 14.4 kips Pu ≤ = = 61.3 kips Pa ≤ = = 40.9 kips
0.352 0.352 0.352 0.352

Note: the elastic method, shown here, is more conservative than the instantaneous center of
rotation method, shown in Example II.A-24a.

<!-- p. 323 -->

IIA-80

Example II.A-26 Eccentrically-Loaded Weld Group (IC method)

Given:

Determine the largest eccentric force that can be supported by the available shear strength of
the weld group, using the instantaneous center of rotation method. Use a a-in. fillet weld and
70 ksi electrode.

Solution A. Assume that the load is vertical (θ = 0°) as illustrated below

l = 10 in., kl = 5 in., therefore k = 0.5

With θ = 0 o, x = 0.125

xl + al = 10 in.

0.125(10 in.) + a (10 in.) = 10 in.

a = 0.875

ManualBy interpolation,
Table 8-8
C = 1.88

LRFD ASD
CC1 Dl Rn / Ω= φRn = φCC1 Dl Ω

\= 0.75(1.88)(1.0)(6 sixteenths)(10 in.) 1.88(1.0)(6 sixteenths)(10 in.)
\=
2.00

\= 84.6 kips = 56.4 kips

Thus, Pu must be less than or equal to 84.6 Thus, Pa must be less than or equal to 56.4
kips. kips.

Note: The eccentricity of the load significantly reduces the shear strength of this weld group as
compared to the concentrically loaded case.

<!-- p. 324 -->

IIA-81

Solution B. Assume that the load acts at an angle of 75° with respect to vertical (θ = 75°) as illustrated below

As determined in solution a,

k = 0.5 and a = 0.875, Manual
Table 8-8
By interpolation, with θ = 75o

C = 3.45

LRFD ASD
CC1 Dl Rn / Ω= φRn = φCC1 Dl Ω

3.45(1.0)(6 sixteenths)(10 in.)
\= = 0.75(3.45)(1.0)(6 sixteenths)(10 in.) 2.00

\= 155 kips = 103 kips

Thus, Pu must be less than or equal to 155 Thus, Pa must be less than or equal to 103
kips. kips.

<!-- p. 325 -->

IIA-82

Example II.A-27 Eccentrically-Loaded Weld Group (elastic method)

Given:

Determine the largest eccentric force that can be supported by the available shear strength of
the welds in the connection, using the elastic method. Compare the result with that of the
previous example. Use a in. fillet welds made with E70 electrodes.
Ip = 385 in.4 per in.2

Solution:

LRFD ASD
Direct shear force per inch of weld Direct shear force per inch of weld
Manual
Pu Pu Pa Pa Part 8 rpx = 0, rpy = = rpx = 0, rpy = =
l 20 l 20

Additional shear force due to eccentricity Additional shear force due to eccentricity

Pu ec y Pu (8.75 in.)(5 in.) Pa ec y Pa (8.75 in.)(5 in.)
rmx = = 4 2 = 0.114 Pu rmx = = 4 2 = 0.114 Pa
I p 385 in. per in. I p 385 in. per in.

Pu ec x Pu (8.75 in.) ( 3.75 in.) Pa ec x Pa (8.75 in.) ( 3.75 in.)
rmy = = 4 2 rmy = = 4 2
I p 385 in. per in. I p 385 in. per in.

\= 0.0852 Pu = 0.0852 Pa

Resultant shear force Resultant shear force

ru = ( rpx + rmx ) 2 + ( rpy + rmy ) 2 ra = ( rpx + rmx ) 2 + ( rpy + rmy ) 2

2 ⎛ Pu ⎞ 2 2 ⎛ Pa ⎞ 2
\= (0 + 0.114 Pu ) + ⎜ + 0.0852 Pu ⎟ = (0 + 0.114 Pa ) + ⎜ + 0.0852 Pa ⎟ ⎝ 20 ⎠ ⎝ 20 ⎠

\= 0.177 Pu = 0.177 Pa

<!-- p. 326 -->

IIA-83

Since ru must be less than or equal to the Since ra must be less than or equal to the
available strength, available strength,

φrn 1.392(6 sixteenths) rn / Ω 0.928(6 sixteenths)
Pu ≤ = = 47.2 kips Pa ≤ = = 31.5 kips Manual 0.177 0.177 0.177 0.177
Part 8

Note: The strength of the weld group predicted by the elastic method, as shown here, is
significantly less than the predicted by the instantaneous center of rotation method in Example
II.A-26a.

<!-- p. 327 -->

IIA-84

Example II.A-28 All-Bolted Single-Angle Connection (beam-to-girder web)

Given:

Design an all-bolted single-angle connection (case I in Table 10-10) between a W18×35 beam
and a W21×62 girder-web, to support the following beam end reactions:

RD = 6.5 kips
RL = 20 kips

Top flange coped 2 in. deep by 4 in. long, Lev = 1½ in., Leh = 1½ in. (assumed to be 1¼ in. for
calculation purposes to account for possible underrun in beam length),

Use ¾-in. diameter A325-N bolts in standard holes.

Material Properties:

Beam W18×35 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Girder W21×62 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Angle ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Beam W18×35 tw = 0.300 in. d = 17.7 in. tf = 0.425 in. Manual
Cope c = 4 in. dc = 2 in. e = 42-in. h0 = 15.7 in. Table 1-1
Girder W21×62 tw = 0.400 in.

<!-- p. 328 -->

IIA-85

Solution:

LRFD ASD
Ru = 1.2(6.5 kips) + 1.6(20 kips) = 40 kips Ra = 6.5 kips + 20 kips = 26.5 kips

Design the bolts and angle Design the bolts and angle
Since half-web dimension of W18×35 is less Since half-web dimension of W18×35 is less
than 4 in., the tabular values may than 4 in., the tabular values may Manual
conservatively be used. Bolt shear is more conservatively be used. Bolt shear is more Table 7-1
critical than bolt bearing in this example; critical than bolt bearing in this example;
thus, φvrn = 15.9 kips. thus, rn /Ωv = 10.6 kips.

Ru 40 kips Ra 26.5 kips Cmin = = = 2.52 C min = = = 2.52
φrn 15.9 kips/bolt rn / Ω 10.6 kips/bolt

Try a four-bolt connection with a a-in. thick Try a four-bolt connection with a a-in. thick
angle. angle. Manual
Table 10-10
C = 3.07 > 2.52 o.k. C = 3.07 > 2.52 o.k.

The 3-in. leg will be shop bolted to the girder The 3-in. leg will be shop bolted to the girder
web and the 4-in. leg will be field bolted to web and the 4-in. leg will be field bolted to
the beam web. the beam web.
Check shear yielding of the angle Check shear yielding of the angle
Section J4.2
φRn = φ(0.6FyAg) Rn / Ω = 0.6FyAg / Ω Eqn J4-3

\= 1.0(0.6)(36 ksi)(112 in.)(a-in.) = 0.6(36 ksi)(112 in.)(a-in.) / 1.50

\= 93.2 kips > 40 kips o.k. = 62.1 kips > 26.5 kips o.k.

Check shear rupture of the angle Check shear rupture of the angle
Section J4.2
φRn = φ(0.6FuAn) Rn / Ω = (0.6FuAn)/ Ω Eqn J4-4

\= 0.75{0.6(58 ksi)[(112 in.)(a-in.) – = 0.6(58 ksi)[(112 in.)(a-in.) –

4(d-in.)(a-in.)]} 4(d-in.)(a-in.)] / 2.00

\= 78.3 kips > 40 kips o.k. = 52.2 kips > 26.5 kips o.k.

Check block shear rupture of the angle Check block shear rupture of the angle
From the tables, with n = 4, Lev = 12 in. From the tables, with n = 4, Lev = 12 in.
Leh = 14 in., Leh = 14 in.,

Rn Fu Ant U bs ⎛ 0.6 Fy Agv Fu Anv ⎞ = + min , ⎜ ⎟ ⎝ Ω Ω ⎠ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) Ω Ω

Tension rupture component Tension rupture component
Manual
φFu Ant = 35.3 kips/in.(a in.) Fu Ant / Ω= 23.6 kips/in.(a in.) Table 9-3a

<!-- p. 329 -->

IIA-86

Shear yielding component Shear yielding component Manual
Table 9-3b
φ 0.6 Fy Agv = 170 kips/in.(a in.) 0.6 Fy Agv / Ω= 113 kips/in.(a in.)

Shear rupture component Shear rupture component
Manual
Table 9-3c
φ 0.6 Fu Anv = 194 kips/in.(a in.) 0.6 Fu Anv = 129 kips/in.(a in.)

Tension stress is uniform, therefore Tension stress is uniform, therefore
Eqn. J4-5
Ubs = 1.0 Ubs = 1.0

φRn = (170 kips/in. + 35.3 kips/in.)(a in.) Rn/Ω = (113 kips/in. + 23.6 kips/in.)(a in.) Commentary
Section J4.3
\= 77.0 kips > 40 kips o.k. = 51.4 kips > 26.5 kips o.k.
Check flexure of the support-leg of the angle Check flexure of the support-leg of the angle

The required strength is The required strength is

Mu = Ru e = (40 kips)(1w-in. + 0.300 in./2) Ma = Ra e = (26.5 kips)(1w-in. + 0.300 in./2)

\= 76.0 in.-kips = 50.4 in.-kips

For flexural yielding For flexural yielding

φ = 0.90 Ω= 1.67

φM n = φFy Z x Mn / Ω = FyZx / Ω Manual
Part 15
2 3 1 ⎡ ( 8 in.)(11 2 in.) ⎤ 3 1 8 in.)(11 2 in.) 2 ⎤ ⎢ ⎥ ( 36 ksi ) ⎡ ( = 0.90 ( 36 ksi ) = ⎢ ⎥ ⎢⎣ 4 ⎥⎦ 1.67 ⎢⎣ 4 ⎥⎦

\= 402 in.-kips > 76.0 in.-kips o.k.
\= 267 in.-kips > 50.4 in.-kips o.k.

For flexural rupture,

⎡ ⎤ t s 2 n ( n 2 − 1)( d h + 116 in.) 2
Z net ≈ ⎢ d − ⎥
4 ⎢ d ⎥ ⎣ ⎦

13 ⎡ 3 2 ( 3 in.) 2 ( 4 )( 4 2 − 1)( 8 in. 16 in. + 116 in.) ⎤ 3 ≈ ⎢(11 12 in.) − ⎥ = 8.55 in.
4 ⎢ 11 12 in. ⎥ ⎣ ⎦
LRFD ASD

3 58 ksi )( 8.55 in. ) Fu Z net ( φMn = φFuZnet = 0.75(58ksi)(8.55 in.3) M n / Ω= = Ω 2.00

\= 248 in.-kips > 53.4 in.-kips o.k. = 372 in.-kips > 76.0 in.-kips o.k.

<!-- p. 330 -->

IIA-87

Check beam web for bolt bearing and block Check beam web for bolt bearing and block
shear rupture. shear rupture.

n = 4, Lev =12 in., and Leh = 12 in. n = 4, Lev =12 in., and Leh = 12 in.
(Assumed to be 14 in. for calculation (Assumed to be 14 in. for calculation Manual
purposes to provide for possible underrun in purposes to provide for possible underrun in Table 10-1
beam length), beam length),

φRn = (257 kips/in.)(0.300 in.) Rn / Ω = (171 kips/in.)(0.300 in.)

\= 77.1 kips > 40 kips o.k. = 51.3 kips > 26.5 kips o.k.

<!-- p. 331 -->

IIA-88

Example II.A-29 Bolted/Welded Single-Angle Connection
(beam-to-column flange).

Given:

Design a single-angle connection between a W16×50 beam and a W14×90 column flange to
support the following beam end reactions:

RD = 9 kips
RL = 27 kips

Use ¾ in. diameter ASTM A325-N bolts to connect the supported beam to the single angle.
Use 70 ksi electrode welds to connect the single angle to the column flange.

Material Properties:

W16×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Angle ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties:

Beam W16×50 tw = 0.380 in. d = 16.3in. tf = 0.630 in. Manual
Column W14×90 tf = 0.710 Table 1-1

Solution:

LRFD ASD
Ru = 1.2 (9 kips) + 1.6 (27 kips) = 54 kips Ra = 9 kips + 27 kips = 36 kips

Design single angle, bolts, and welds Design single angle, bolts, and welds

Since the half-web dimension of a W16×50 Since the half-web dimension of a W16×50
is less than 4 in., the tabulated values may is less than 4 in., the tabulated values may
conservatively be used. conservatively be used.

Try a four bolt single angle (L4×3×a). Try a four bolt single angle (L4×3×a).
Manual
φRn = 63.6 kips > 54 kips o.k. Rn /Ω = 42.4 kips > 36 kips o.k. Table 10-11

<!-- p. 332 -->

IIA-89

Also with a x-in fillet weld size Also with a x-in. fillet weld size

φRn = 56.6 kips > 54 kips o.k. Rn /Ω = 37.7 kips > 36 kips o.k. Manual
Table 10-11
Use four-bolt single angle L4×3×a. The 3- Use four-bolt single angle L4×3×a. The 3in. leg will be shop welded to the column in. leg will be shop welded to the column
flange and the 4 in. leg will be field bolted to flange and the 4 in. leg will be field bolted to
the beam web. the beam web.

Check supported beam web Check supported beam web

The bearing strength of the beam web per The bearing strength of the beam web per
bolt is bolt is

s = 3 in., w in. diameter bolts, standard holes s = 3 in., w in. diameter bolts, standard holes
rn t w n Rn / Ω=φRn = φrn t w n Ω

\= (87.8 kips/in.)(0.380 in.)(4 bolts) = (58.5 kips/in.)(0.380 in.)(4 bolts)

Manual
\= 133 kips > 54 kips o.k. = 88.9 kips > 36 kips o.k.
Table 7-5

Check support Check support

Minimum support thickness for the x-in. Minimum support thickness for the x-in. Manual
welds is 0.286 in. welds is 0.286 in. Table 10-11
tw = 0.710 in > 0.286 in o.k. tw = 0.710 in > 0.286 in o.k.

<!-- p. 333 -->

IIA-90

Example II.A-30 All-Bolted Tee Connection (beam-to-column flange)

Given:

Design an all-bolted tee connection between a W16×50 beam and a W14×90 column flange to
support the following beam end reactions:

RD = 9 kips
RL = 27 kips

Use ¾ in. diameter ASTM A325-N bolts in standard holes. Try a WT5×22.5 with a four-bolt
connection.

Material Properties:

W16×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
WT5×22.5 ASTM A992 Fy = 50 ksi Fu = 65 ksi

Geometric Properties:

Beam W16×50 tw = 0.380 in. d = 16.3 in. tf = 0.630 in. Manual
Column W14×90 tf = 0.710 in. Tables 1-1
Tee WT5×22.5 d = 5.05 in. bf = 8.02 in. tf = 0.620 in. and 1-8
ts = 0.350 in. k1 = m in.
(see W10×45 Manual Table 1-1)

<!-- p. 334 -->

IIA-91

Solution:

Ru = 1.2 (9 kips) + 1.6 (27 kips) = 54 kips Ra = 9 kips + 27 kips = 36 kips

Check limitation on tee stem thickness

See Rotational Ductility discussion at the beginning of the Manual Part 9

d b 34 in.ts max = + 116 in. = + 116 in. = 0.438 in. > 0.350 in. o.k.
2 2

Check limitation on bolt diameter for bolts through tee flange
Manual
Part 10Assuming a 52 in. gage,

b = flexible width in connection element

13 16 in.) g − 2 k1 5 12 in. − 2 (b = = = 1.94 in.
2 2

Fy ⎛ b 2 ⎞
db min = 0.163t f ⎜ 2 + 2⎟ ≤ 0.69 t s b ⎝ L ⎠

50 ksi ⎡ (1.94 in.) 2 ⎤ = 0.163 ( 0.620 in.) ⎢ 2 + 2 ⎥ ≤ 0.69 0.350 in.
1.94 in. ⎢⎣ ( 11 12 in ) ⎥⎦

\= 0.731 in. ≤ 0.408 in.

\= 0.408 in.

Since db = w in. > db min = 0.408 in. o.k.

Check bolt group through beam web for shear and bearing

a = d - Leh = 5.05 in. – 14 in. = 3.80 in.

LRFD ASD
Since bolt shear is more critical than bolt Since bolt shear is more critical than bolt
bearing in this example, φrn = 15.9 kips, bearing in this example, rn/Ω = 10.6 kips, Manual
Table 7-1
Thus, Thus,

φRn = nφrn = (4 bolts)(15.9 kips) Rn/Ω = nrn/Ω = (4 bolts)(10.6 kips)

\= 63.6 kips > 54 kips o.k. = 42.4 kips > 36 kips o.k.

<!-- p. 335 -->

IIA-92

Check shear yielding of the tee stem Check shear yielding of the tee stem

φRn = φ 0.6 Fy Ag Rn/Ω = 0.6 Fy Ag / Ω Eqn. J4-3

φ = 1.00 Ω = 1.50

/1.5 = 1.00 ⎡ = ⎡ ⎣ 0.6 ( 50 ksi )(11 12 in.)(0.350 in.) ⎤⎦ ⎣ 0.6 ( 50 ksi )(11 12 in.)( 0.350 in.) ⎤⎦

\= 121 kips > 54 kips o.k. = 80.5 kips > 36 kips o.k.

Check shear rupture of the tee stem Check shear rupture of the tee stem

φRn = φ 0.6 Fu Anv Rn/Ω = 0.6 Fu Anv / Ω Eqn. J4-4

Where φ = 0.75 Where Ω = 2.00

0.350 in.)= 0.75 ( 0.6 )( 65 ksi ) ⎡⎣ 11 12 in. − 4 ( 0.875 in.) ⎤⎦ = 0.6 ( 65 ksi ) ⎡⎣ 11 12 − 4 ( 0.875 in.) ⎤⎦ (
( 0.350 in.) / 2.00

\= 54.6 kips > 36 kips o.k.= 81.9 kips > 54 kips o.k.

Check block shear rupture of the tee stemCheck block shear rupture of the tee stem

Leh = Lev = 14 in.,Leh = Lev = 14 in.,

Thus,Thus,

⎛ 0.6 Fy Agv Fu Ant U bs Fu Anv ⎞ , n = + minφRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) R ⎜ ⎟ Eqn. J4-5 Ω Ω ⎝ Ω Ω ⎠

Tension rupture component Tension rupture component
Manual
u Ant / Ω= 26.4 kips/in. (0.350 in.) Table 9-3a φFu Ant = 39.6 kips/in. (0.350 in.) F

Shear yielding component Shear yielding component
Manual y Agv / Ω= 154 kips/in. (0.350 in.) φ 0.6 Fy Agv = 231 kips/in. (0.350 in.) 0.6 F Table 9-3b

Shear rupture component Shear rupture component
Manual
u Anv / Ω= 140 kips/in. (0.350 in.) Table 9-3c φ 0.6 Fu Anv = 210 kips/in. (0.350 in.) 0.6 F

φRn= (210 kips/in. + 39.6 kips/in.)(0.350 Rn = (140 kips/in. + 26.4 kips/in.)(0.350 in.)
in.) Ω

\= 58.2 kips > 36 kips o.k.
\= 87.4 kips > 54 kips o.k.

<!-- p. 336 -->

IIA-93

Check bolt group through support for shear Check bolt group through support for shear
and bearing combined with tension due to and bearing combined with tension due to
eccentricity eccentricity

The following calculation follows the Case II The following calculation follows the Case II
approach in the Section “Eccentricity approach in the Section “Eccentricity Normal
Normal to the Plane of the Faying Surface” to the Plane of the Faying Surface” in the
in the introduction of Part 7 of the Manual introduction of Part 7 of the Manual

Calculate tensile force per bolt rut. Calculate tensile force per bolt rat.

Ru e Ra erut = rat =
n ' d m n ' d m

54 kips ( 5.05 in. − 1 14 in.) 36 kips ( 5.05 in. − 1 14 in.)
utr = atr = 4 bolts ( 6 in.) 4 bolts ( 6 in.)

\= 8.55 kips/bolts = 5.70 kips/bolts

Check design strength of bolts for tension- Check allowable strength of bolts for
shear interaction tension-shear interaction

When threads are not excluded from the When threads are not excluded from the
shear planes of ASTM A325 bolts shear planes of ASTM A325 bolts

54 kips 36 kips
ruv = rav =
8 bolts 8 bolts
Manual
\= 6.75 kips/bolt \< 15.9 kips/bolt o.k. = 4.50 kips/bolt \< 10.6 kips/bolt o.k. Table 7-1

Fnt = 90 ksi, Fnv = 48 ksi Fnt = 90 ksi, Fnv = 48 ksi Table J3.2

Fnt ΩFnt Eqn. J3-3aFnt ' = 1.3 Fnt − f v ≤ Fnt Fnt ' = 1.3 Fnt − f v ≤ Fnt
φFnv Fnv and J3-3b

φ = 0.75 Ω = 2.00

⎧⎡⎪ 90 ksi ⎤ ⎧⎡⎪ ( 2.00 )( 90 ksi ) ⎤
\= 1.3(90 ksi) −⎨⎢ ⎥ = 1.3(90 ksi) −⎨⎢ ⎥ 48 ksi ) ⎦ ⎪⎣⎩ ( 0.75)( 48 ksi ) ⎦ ⎪⎣⎩ (

⎛ 6.75 kips/bolt ⎞ ⎫ ⎛ 4.50 kips/bolt ⎞ ⎫
⎜ 2 ⎟ ⎬ ≤ 90 ksi ⎜ 2 ⎟ ⎬ ≤ 90 ksi ⎝ 0.442 in ⎠⎭ ⎝ 0.442 in ⎠⎭

\= 78.8 ksi \< 90 ksi = 78.8 ksi \< 90 ksi

φRn = Fnt′Ab Rn /Ω = Fnt′Ab /Ω
Eqn. J3-2
\= 0.75(78.8 ksi)(0.442 in2) = (78.8 ksi)(0.442 in2)/2.00

\= 26.1 kips/bolt > 8.55 kips/bolt o.k. = 17.4 kips/bolt > 5.7 kips/bolt o.k.

<!-- p. 337 -->

IIA-94

Check bearing strength at bolt holes

With Le = 14 in. and s = 3 in., the bearing strength of the tee flange exceeds the single shear
strength of the bolts. Therefore, bearing strength is o.k.

Check prying action Manual
Part 9
( g − t s ) ( 5 12 in. − 0.350 in.)b = = = 2.58 in.
2 2
( fb − g ) ( 8.02 in. − 5 12 in.)a = = = 1.26 in.
2 2

Since a = 1.26 in. is less than 1.25b = 3.23 in., use a = 1.26 in. for calculation purposes

d ⎛ 34 in. ⎞
b ' = b − = 2.58 in. −⎜ ⎟ 2.21 in. 2 ⎝ 2 ⎠=

⎛ d ⎞ ⎛ 34 in. ⎞
a ' = a + ⎜ ⎟ = 1.26 in. + ⎜ ⎟ 1.64 in. ⎝ 2 ⎠ ⎝ 2 ⎠=

b ' 2.21 in.
ρ = = = 1.35
a ' 1.64 in.

LRFD ASD
T = rut = 8.55 kips/bolt T = rat = 5.70 kips/bolt Manual
Part 9
B = φrn = 26.1 kips/bolt B = rn / Ω= 17.4 kips/bolt

1 ⎛ B ⎞ 1 ⎛ B ⎞
β = ⎜ − 1⎟ β = ⎜ − 1⎟ ρ ⎝ T ⎠ ρ ⎝ T ⎠

1 ⎛ 26.1 kips/bolts ⎞ 1 ⎛ 17.4 kips/bolts ⎞
\= − 1 ⎜ ⎟ 1.52 = ⎜ − 1⎟ 1.52 1.35 ⎝ 8.55 kips/bolts ⎠= 1.35 ⎝ 5.70 kips/bolts ⎠=

Since β ≥ 1 , set α′= 1.0 Manual
Part 9

11 12 in. p = = 2.88 in./bolt
4 bolts

d ' 1316 in.δ = 1 − = 1 − = 0.718
p 2.88 in.

<!-- p. 338 -->

IIA-95

LRFD ASD
Manual 4.44 rut b ' 6.66 rat b ' t req = t req = Part 9 pFu (1 + δα ') pFu (1 + δα ')

4.44 ( 8.55 kips/bolt )( 2.21 in.) 6.66 ( 5.70 kips/bolt )( 2.21 in.) = =
( 2.88 in./bolt )( 65 ksi ) ⎡+⎣ 1 ( 0.718)(1.0 ) ⎤⎦ ( 2.88 in./bolt )( 65 ksi ) ⎡+⎣ 1 ( 0.718)(1.0 ) ⎤⎦

\= 0.511 in. \< 0.620 in. o.k. = 0.511 in. \< 0.620 in. o.k.

Similarly, checks of the tee flange for shear yielding, shear rupture, and block shear rupture
will show that the tee flange is o.k.

LRFD ASD
Check beam web for bolt bearing, block Check beam web for bolt bearing, block
shear rupture, shear yielding and shear shear rupture, shear yielding and shear
rupture rupture

For single shear, four rows of w in. diameter For single shear, four rows of w in. diameter Manual
bolts and an uncoped beam with Fy = 50 ksi bolts and an uncoped beam with Fy = 50 ksi Table 10-1
and Fu = 65 ksi, and Fu = 65 ksi,

φRn = (702 kips/in.)(0.380 in.)/2 Rn /Ω= (468 kips/in.)(0.380 in.)/2

\= 133 kips > 54 kips o.k. = 88.9 kips > 36 kips o.k.

Check supporting member web or flange for Check supporting member web or flange for
bolt bearing bolt bearing

For, double shear, four rows of w in. For, double shear, for four rows of w in. Manual
diameter bolts with Fy = 50 ksi and Fu = 65 diameter bolts with Fy = 50 ksi and Fu = 65 Table 10-1
ksi, ksi,

φRn = (702 kips/in.)(0.710 in.) Rn /Ω = (468 kips/in.)(0.710 in.)

\= 498 kips > 54 kips o.k. = 332 kips > 36 kips o.k.

<!-- p. 339 -->

IIA-96

Example II.A-31 Bolted/Welded Tee Connection (beam-to-column flange)

Given:

Design a tee connection bolted to a W16×50 supported beam and welded to a W14×90
supporting column flange, to support the following beam end reactions:

RD = 6 kips
RL = 18 kips

Use w in. diameter ASTM A325-N bolts in standard holes and E70 electrode welds. Try a
WT5×22.5 with four-bolts.

Material Properties:

W16×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
W14×90 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
WT5×22.5 ASTM A992 Fy = 50 ksi Fu = 65 ksi

Geometric Properties:

Beam W16×50 tw = 0.380 in. d = 16.3 in. tf = 0.630 in. Manual
Column W14×90 tf = 0.710 in. Tables 1-1
Tee WT5×22.5 d = 5.05 in. bf = 8.02 in. tf = 0.620 in. and 1-8
ts = 0.350 in. k1 = m in.
(see W10×45 Manual Table 1-1)

<!-- p. 340 -->

IIA-97

Solution:

LRFD ASD
Ru = 1.2 (6 kips) + 1.6 (18 kips) = 36 kips Ra = 6 kips + 18 kips = 24 kips

Check limitation on tee stem thickness Manual
Part 9
See Rotational Ductility discussion at the beginning of the Manual Part 9

d b 34 in.ts max = + 116 in. = + 116 in. = 0.438 in. > 0.350 in. o.k.
2 2

Design the welds connecting the tee flange to the column flange

b = flexible width in connection element

fb − 2 k1 8.02 in. − 2 ( 1316 in.)b = = = 3.20 in.
2 2

Fy t f 2 ⎛ b 2 ⎞
wmin = 0.0158 ⎜ 2 + 2 ⎟ ≤ 58 t s
b ⎝ L ⎠

⎡ ( 50 ksi )( 0.620 in. ) 2 ⎤⎛⎡ ( 3.20 in. ) 2 ⎞ ⎤ ⎢ ⎜ ⎟ + 2 ⎥ = 0.0158 ⎢ ≤ ( 58 )( 0.350 in. ) ⎟ ⎢ ⎥ ⎢ ( 3.20 in. ) ⎥⎜⎥ ⎣ ⎦⎝ (11 12 in. ) 2 ⎠ ⎣ ⎦
Manual
\= 0.197 in. ≤ 0.212 in. Part 9

Design welds for direct load only with no eccentricity

LRFD ASD
Try 4-in. fillet welds. Try 4-in. fillet welds.

φRn = 1.392Dl Rn/Ω = 0.928Dl Manual
Part 8
\= 1.392 (4 sixteenths)(2 sides)(112 in.) = 0.928 (4 sixteenths)(2 sides)(112 in.)

\= 128 kips > 36 kips o.k. = 85.4 kips > 24 kips o.k.

Use 4-in. fillet welds. Use 4-in. fillet welds.

Check the stem side of the connection

Since the connection is flexible at the support, the tee stem and bolts must be designed for
eccentric shear, where the eccentricity, eb, is

a = d - Leh = 5.05 in. – 14 in. = 3.80 in.

eb = a = 3.80 in.

<!-- p. 341 -->

IIA-98

LRFD ASD
Thus the tee stem and bolts must be designed Thus the tee stem and bolts must be designed
for Ru = 36 kips and Rueb = 137 in.-kips. for Ra = 24 kips and Raeb = 91.2 in.-kips.

Check bolt group through beam web for Check bolt group through beam web for
shear and bearing shear and bearing

For θ = 00 , with s = 3 in., For θ = 00 , with s = 3 in.,
ex = eb = 3.80 in., and n = 4 bolts, ex = eb = 3.80 in., and n = 4 bolts, Manual
Table 7-7
C = 2.45 C = 2.45

and, since bolt shear is more critical than bolt and, since bolt shear is more critical than bolt
bearing in this example, bearing in this example,

φRn = Cφrn = 2.45 (15.9 kips/bolt) Rn /Ω = Crn /Ω = 2.45 (10.6 kips/bolt) Manual
Table 7-1
\= 39.0 kips > 36.0 kips o.k. = 26.0 kips > 24.0 kips o.k.

Check flexure on the tee stem Check flexure on the tee stem
Manual
For flexural yielding For flexural yielding Part 15

φ = 0.90 Ω = 1.67

φMn = φFyZx Mn/Ω = FyZx/Ω

⎡ ( 0.350 in. )(11 12 in. ) 2 ⎤ ⎡ ( 0.350 in. )(11 12 in. ) 2 ⎤ = ( 0.9 )( 50 ksi ) ⎢ ⎥ = ( 50 ksi ) ⎢ ⎥ /1.67
⎢ 4 ⎥ ⎢ 4 ⎥ ⎣ ⎦ ⎣ ⎦

\= 520 in.-kips > 137 in.-kips o.k. = 346 in-kips > 91.2 in.-kips o.k.

For flexural rupture,

⎡ ⎤ t s 2 n ( n 2 − 1)( d h + 116 in.) 2
Z net ≈ ⎢ d − ⎥
4 ⎢ d ⎥ ⎣ ⎦

13 ⎡ 0.350 in. 2 ( 3 in.) 2 ( 4 )( 4 2 − 1)( 16 in. + 116 in.) ⎤ 3 ≈ ⎢(11 12 in.) − ⎥ = 7.98 in.
4 ⎢ 11 12 in. ⎥ ⎣ ⎦

LRFD ASD
φMn = φFuZnet Mn/Ω = FuZnet/Ω

φ = 0.75 Ω = 2.00

\= (0.75)(65 ksi)(7.98 in3) = (65 ksi)(7.98 in3)/2.00

\= 389 in.-kips > 137 in.-kips o.k. = 259 in.-kips > 91.2 in.-kips o.k.

<!-- p. 342 -->

IIA-99

Check shear yielding of the tee stem Check shear yielding of the tee stem

φRn = φ 0.60 Fy Ag Rn/Ω = 0.60 Fy Ag / Ω Eqn. J4-3

φ = 1.00 Ω = 1.50

\= 1.00 ( 0.6 )( 50 ksi )(11 12 in.)( 0.350 in.) = 0.6 ( 50 ksi )(11 12 in.)( 0.350 in.) /1.50

\= 121 kips > 36 kips o.k. = 80.5 kips > 24 kips o.k.

Check shear rupture of the tee stem Check shear rupture of the tee stem

φ = 0.75 Ω = 2.00

φRn = φ 0.6 Fu Anv Rn/Ω = 0.6 Fu Anv / Ω Eqn. J4-4
0.6 ( 65 ksi ) =φRn = 0.75 ( 0.6 )( 65 ksi ) 2.00
× ⎡ 0.350 in.) × ⎡ 0.350 in.) ⎣11 12 − 4 ( 0.875 in.) ⎤⎦ ( ⎣11 12 − 4 ( 0.875 in.) ⎤⎦ (

\= 81.9 kips > 36 kips o.k. = 54.6 kips > 24 kips o.k.

Check block shear rupture of the tee stem Check block shear rupture of the tee stem

Leh = Lev = 14 in., Leh = Lev = 14 in.,

Thus. Thus.
Rn Fu Ant U bs ⎛ 0.6 Fy Agv Fu Anv ⎞ Eqn. J4-5 = + min , ⎜ ⎟φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) Ω Ω ⎝ Ω Ω ⎠

Tension rupture component Tension rupture component
Manual
φFu Ant = 39.6 kips/in. (0.350 in.) Fu Ant / Ω= 26.4 kips/in. (0.350 in.) Table 9-3a

Shear yielding component Shear yielding component
Manual
φ 0.6 Fy Agv = 231 kips/in. (0.350 in.) 0.6 Fy Agv / Ω= 154 kips/in. (0.350 in.) Table 9-3b

Shear rupture component Shear rupture component
Manual
φ 0.6 Fu Anv = 210 kips/in. (0.350 in.) 0.6 Fu Anv / Ω= 140 kips/in. (0.350 in.) Table 9-3c

Rn
φRn = (210 kips/in. + 39.6 kips/in.)(0.350 = (140 kips/in. + 26.4 kips/in.)(0.350 in.) Ω
in.)
\= 58.2 kips > 24 kips o.k.

\= 87.4 kips > 36 kips o.k.

<!-- p. 343 -->

IIA-100

Check beam web for bolt bearing, block Check beam web for bolt bearing, block
shear rupture, shear yielding and shear shear rupture, shear yielding and shear
rupture rupture

From the table, single shear, four rows of w- From the table, single shear, four rows of w- Manual
in. diameter bolts and an uncoped beam with in. diameter bolts and an uncoped beam with Table 10-1
Fy = 50 ksi and Fu = 65 ksi, Fy = 50 ksi and Fu = 65 ksi,

φRn = (702 kips/in.)(0.380 in.)/2 Rn/Ω = (468 kips/in.)(0.380 in.)/2

\= 133 kips > 36 kips o.k. = 88.9 kips > 24 kips o.k.

Check the supporting column flange Check the supporting column flange

From the table, for column flange material From the table, for column flange material Manual
with Fy = 50 ksi, n = 4, L = 112, Welds B, with Fy = 50 ksi, n = 4, L = 112, Welds B, Table 10-2
Weld size = 4-in. the minimum support Weld size = 4-in. the minimum support
thickness is 0.190 in. thickness is 0.190 in.

tf = 0.710 in. > 0.190 in. o.k. tf = 0.710 in. > 0.190 in. o.k.

<!-- p. 344 -->

IIB-1

Chapter IIB
Fully-Restrained (FR) Moment Connections

The design of fully restrained (FR) moment connections is covered in Part 11 of the
AISC Steel Construction Manual.

<!-- p. 345 -->

IIB-2

Example II.B-1 Bolted Flange-Plate FR Moment Connection
(beam-to-column flange)

Given:

Design a bolted flange-plated FR moment connection between a W18×50 beam and a W14×99
column flange to transfer the following forces:

RD = 7 kips MD = 42 kip-ft
RL = 21 kips ML = 126 kip-ft

Use d-in. diameter ASTM A325-N bolts in standard holes and E70 electrodes.

Material Properties:

Beam W18×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×99 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-2
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-3

Geometric Properties:

Beam W18×50 d = 18.0 in. bf = 7.50 in. tf = 0.570 in. tw = 0.355 in. Sx = 88.9 Manual
in.3 Table 1-1
Column W14×99 d = 14.2 in. bf = 14.6 in. tf = 0.780 in.

<!-- p. 346 -->

IIB-3

Solution:

LRFD ASD
Ru = 1.2 ( 7 kips ) + 1.6 ( 21 kips ) Ra = 7 kips + 21 kips
\= 42 kips = 28 kips
M u = 1.2 ( 42 kip-ft ) + 1.6 (126 kip-ft ) M a = 42 kip-ft + 126 kip-ft
\= 168 kip-ft = 252 kip-ft

Check the beam available flexural strength

Assume two rows of bolts in standard holes.

2 SectionA fg = b f t f = ( 7.50 in.)( 0.570 in.) = 4.28 in.
F13.1

2 7 1 2 − 2 ( 8 in. + 1 8 in.)( 0.570 in.) = 3.14 in.A fn = A fg − 2 ( d b + 8 in.) t f = 4.28 in.

Fy 50 ksi
\= = 0.769 \< 0.8 , therefore Yt = 1.0.
Fu 65 ksi

2Fu A fn = ( 65 ksi )( 3.14 in. ) = 204 kips

2Yt Fy A fg = (1.0 )( 50 ksi )( 4.28 in. ) = 214 kips > 204 kips

Therefore the nominal flexural strength, Mn, at the location of the holes in the tension flange is
as follows:

2 3 Fu A fn S x ( 65 ksi )( 3.14 in. )( 88.9 in. ) Specification
M n = = 2 = 4240 kip-in. or 353 kip-ft A fg 4.28 in. Eqn. F13-1

LRFD ASD
φ = 0.90 Ω = 1.67

353 kip-ft
M n / Ω=b = 211 kip-ft φ b M n = 0.90 ( 353 kip-ft ) = 318 kip-ft 1.67

318 kip-ft > 252 kip-ft o.k. 211 kip-ft > 168 kip-ft o.k.

Design single-plate web connection

Try a PL a×4×0’-9, with three d-in. diameter ASTM A325-N bolts and 4-in. fillet welds.

<!-- p. 347 -->

IIB-4

LRFD ASD
Design shear strength of the bolts Allowable shear strength of bolts Manual
Table 7-1
Single shear; Single shear;

φrn = 21.6 kips/bolt rn/Ω = 14.4 kips/bolt

\= 42 kips/(21.6 kips/bolt) = 1.94 bolts = 28 kips/(14.4 kips/bolt) = 1.94 bolts

Bearing strength of bolts Bearing strength of bolts Manual
Table 7-5
Bolt spacing = 3 in. Bolt spacing = 3 in.

φrn = (91.4 kips/in./bolt)(a in.) rn/Ω = (60.9 kips/in./bolt)(a in.)

\= 34.3 kips/bolt = 22.8 kips/bolt

\= 42 kips/(34.3 kips/bolt) = 1.23 bolts = 28 kips/(22.8 kips/bolt) = 1.23 bolts

Plate shear yielding Plate shear yielding

φ = 1.00 Ω = 1.50

φRn = 0.60 φFy Ag rn/Ω = 0.60 Fy Ag /Ω = Eqn J4-3

\= 0.60(1.00)(36 ksi)(9 in.)(a in.) = 0.60(36 ksi)(9 in.)(a in.)/(1.50)

\= 72.9 kips > 42 kips o.k. = 48.6 kips > 28 kips o.k.

Plate shear rupture Plate shear rupture

Where φ = 0.75 Ω = 2.00

Eqn J4-4 φRn = 0.60 φFu Anv rn/Ω = 0.60 Fu Anv /Ω =

(3 bolts)(d in.+ z in.+ z in.) = 3 in. (3 bolts)(d in.+ z in.+ z in.) = 3 in.

Anv = (9 in. – 3 in.)(a in.) = 2.25 in2 Anv = (9 in. – 3 in.)(a in.) = 2.25 in2

\= 0.60(0.75)(58 ksi)(2.25 in2) = 0.60(58 ksi)(2.25 in2)/(2.00)

\= 58.7 kips > 42 kips o.k. = 39.2 kips > 28 kips o.k.

Block shear rupture strength of the plate
Leh = 14 in.; Lev = 12 in.; Ubs = 1.0; n = 3

LRFD ASD
⎛ 0.6 Fy Agv Rn Fu Ant U bs Fu Anv ⎞ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) , = + min ⎜ ⎟ Ω Ω ⎝ Ω Ω ⎠

Tension rupture component Tension rupture component Manual
Table 9-3a
φFuAnt = 32.6 kips/in(a in) FuAnt/ Ω = 21.8 kips/in(a in)

<!-- p. 348 -->

IIB-5

Shear yielding component Shear yielding component Manual
Table 9-3b
φ0.60FyAgv = 121 kips/in(a in) 0.60FyAgv / Ω = 81.0 kips/in(a in)

Shear rupture component Shear rupture component Manual
Table 9-3c
φ0.60FuAnv = 131 kips/in(a in) 0.60FuAnv / Ω = 87.0 kips/in(a in)

Rn/Ω = (81.0 kips/in + 21.6 kips/in)(a in)
φRn = (121 kips/in + 32.6 kips/in)(a in)
\= 38.5 kips > 24 kips o.k.
\= 57.6 kips > 42 kips o.k.

Weld Strength Weld Strength Manual
Part 8
φRn = 1.392D l (2) Rn / Ω = 0.928Dl (2)

\= 1.392(4 sixteenths)(9 in.)(2) = 0.928(4 sixteenths)(9 in.)(2)

\= 100 kips > 42 kips o.k. = 66.8 kips > 28 kips o.k.

Connecting Elements Rupture Strength at Welds

Shear rupture strength of base metal

⎛ 2 ⎞⎛ D ⎞
Section J4.2 0.6 FEXX ⎜ ⎟⎜ ⎟ ⎜ 16 ⎠ 3.09 D ⎝ 2 ⎟⎝⎠ t min = =
0.6 Fu Fu

Column flange; tf = 0.780 in.

3.09 D ( 3.09 )( 4 sixteenths )
t min = = = 0.190 in.
Fu 65 ksi

Plate; t = a in.

3.09 ( 2 ) D ( 6.19 )( 4 sixteenths )
t min = = = 0.427 in. > a in. proration required.
Fu 58 ksi

LRFD ASD
38 in. 38 in. φRn = ( 50.1 kips ) = 44 kips Rn / Ω= ( 33.4 kips ) = 29.3 kips
0.427 in. 0.427 in.

44 kips > 42 kips o.k. 29.3 kips > 28 kips o.k.

<!-- p. 349 -->

IIB-6

Design tension flange plate and connection

Design of bolts

LRFD ASD
M u ( 252 kip-ft )(12 in./ft ) M a (168 kip-ft )(12 in./ft ) Manual Puf = = = 168 kips Paf = = = 112 kips Part 12
d 18.0 in. d 18.0 in.

Try a PL w× 7 Try a PL w×7

Determine critical bolt strength Determine critical bolt strength
Manual
For shear, φnr = 21.6 kips/bolt For shear, nr / Ω= 14.4 kips/bolt Table 7-1

For bearing on flange; For bearing on flange;

φrn = (102 kips/bolt ) t f rn / Ω= ( 68.3 kips/bolt ) t f

\= (102 kips/bolt )( 0.570 in.) = ( 68.3 kips/bolt )( 0.570 in.)

\= 58.1 kips/bolt = 38.9 kips/bolt Manual
Table 7-6
For bearing in plate; For bearing in plate;

φrn = ( 91.4 kips/bolt ) t f rn / Ω= ( 60.9 kips/bolt ) t f

\= ( 91.4 kips/bolt )( 0.570 in. ) = ( 60.9 kips/bolt )( 0.570 in. )

\= 52.1 kips/bolt = 34.7 kips/bolt

Shear controls, therefore the number of bolts Shear controls, therefore the number of bolts
required is as follows: required is as follows:

Puf 168 kips Paf 112 kips
nmin = = = 7.78 bolts nmin = = = 7.78 bolts
φrn 21.6 kips/bolt rn / Ω 14.4 kips/bolt

Use eight bolts. Use eight bolts.

Check flange plate tension yielding

3 4 in. ) = 189 kips Eqn. D2-1Pn = Fy Ag = ( 36 ksi )( 7 in. )(

LRFD ASD
M u ( 252 kip-ft )(12 in./ft ) M u (168 kip-ft )(12 in./ft ) Puf = = Puf = = d + t p (18.0 in. + 34 in.) d + t p (18.0 in. + 34 in.)
\= 161 kips = 108 kips

φ = 0.90 Ω = 1.67

<!-- p. 350 -->

IIB-7

φnP = 0.90 (189 kips ) = 170 kips 189 kips nP / Ω= = 113 kips
1.67

170 kips > 161 kips o.k. 113 kips > 108 kips o.k.

Check flange plate tension rupture

An M 0.85 Ag = 0.85(7 in.)(0.75 in.) = 4.46 in2
Eqn. J4-1
2 7 3 7 in.) − 2 ( 4 in.) = 3.75 in. t p = ⎡⎣( 8 in. + 1 8 in.) ⎤⎦ (An = ⎡⎣ B − 2 ( d b + 1 8 in.) ⎤⎦
Ae = 3.75 in.2

2Pn = Fu Ae = ( 58 ksi )( 3.75 in. ) = 217 kips Eqn. D2-2

LRFD ASD
φ = 0.75 Ω = 2.00

φnP = 0.75 ( 217 kips ) = 163 kips 217 kips nP / Ω= = 109 kips
2.0
163 kips > 161 kips o.k.
109 kips > 108 kips o.k.

Check flange plate block shear rupture

There are two cases for which block shear rupture must be checked. The first case involves the
tearout of the two blocks outside the two rows of bolt holes in the flange plate; for this case Leh
\= 12 in. and Lev = 12 in. The second case involves the tearout of the block between the two
rows of the holes in the flange plate. Manual Tables 9-3a, 9-3b, and 9-3c may be adapted for
this calculation by considering the 4 in. width to be comprised of two, 2-in. wide blocks where
Leh = 2 in. and Lev = 12 in. Thus, the former case is the more critical.

LRFD ASD
Manual
⎛ 0.6 Fy Agv Rn Fu Ant U bs Fu Anv ⎞ Table 9-3a φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) , = + min ⎜ ⎟ Ω Ω ⎝ Ω Ω ⎠ Manual
Table 9-3b
Tension component Tension component
3 3 φU bs Fu Ant = 43.5 kips ( 4 in.)( 2 ) 4 in.)( 2 ) Fu Ant / Ω= 29.0 kips (
Manual
Table 9-3c Shear yielding component Shear yielding component
3 3 φ 0.6 Fy Agv = 170 kips ( 4 in.)( 2 ) 4 in.)( 2 ) 0.6 Fy Agv / Ω= 113 kips (

Shear rupture component Shear rupture component
3 3 φ 0.6 Fu Anv = 183 kips ( 4 in.)( 2 ) 4 in.)( 2 ) 0.6 Fu Anv / Ω= 122 kips (

Shear yielding controls, thus Shear yielding controls, thus

3 3 φRn = (170 kips + 43.5 kips )( 4 in.)( 2 ) 4 in.)( 2 ) Rn / Ω= (113 kips + 29.0 kips )(

\= 320 kips > 161 kips o.k. = 213 kips > 108 kips o.k.

<!-- p. 351 -->

IIB-8

Determine the required size of the fillet weld to supporting column flange

The applied tension load is perpendicular to the weld, Eqns. J2-4,
therefore θ = 90° and 1.0 + 0.5sin 1.5 θ = 1.5. and J2-5

LRFD ASD
Puf Paf
Dmin = Dmin = 2 (1.5 )(1.392 ) l 2 (1.5 )( 0.928 ) l

161 kips 108 kips
\= =
2 (1.5 )(1.392 )( 7 in. ) 2 (1.5 )( 0.928 )( 7 in. )

\= 5.51 sixteenths = 5.54 sixteenths

Use a-in. fillet welds, 6 > 5.51 o.k. Use a-in. fillet welds, 6 > 5.54 o.k.

Connecting Elements Rupture Strength at Welds

Tension rupture strength of base metal
⎛ 2 ⎞⎛ D ⎞
0.6 FEXX ⎜ ⎟⎜ ⎟ ⎜ 16 ⎠ 1.86 D ⎝ 2 ⎟⎝⎠ t min = =
Fu Fu

Column flange; tf = 0.780 in.

1.86 D (1.86 )( 6 sixteenths )
t min = = = 0.171 in.
Fu 65 ksi

Flange plate; tf = 0.75 in.

3.71D (1.86 )( 2 )( 6 sixteenths )
t min = = = 0.384 in.
Fu 58 ksi

Design compression flange plate and connection

Try PL w×7

Assume K = 0.65 and l = 2.0 in. (12 in. edge distance and 2 in. setback).

Kl 0.65 ( 2.0 in.) = = 6.00 \< 25
r ⎛ 34 in. ⎞
⎜ ⎟ ⎝ 12 ⎠

Therefore, Fcr = Fy Section J4.3

2 3A = ( 7 in. )( 4 in. ) = 5.25 in.

<!-- p. 352 -->

IIB-9

LRFD ASD
φ = 0.90 Ω = 1.67
2 Fy Ag ( 36 ksi )( 5.25 in. ) 2 = Pn / Ω= φPn = φFy Ag = 0.90 ( 36 ksi )( 5.25 in. ) Ω 1.67 Eqn. J4-6

\= 170 kips > 161 kips o.k. = 113 kips > 108 kips o.k.

The compression flange plate will be identical to the tension flange plate; a w in.×7 in. plate
with eight bolts in two rows of four bolts on a 4 in. gage and a in. fillet welds to the
supporting column flange.

Note: Tension due to load reversal must also be considered in the design of
the fillet weld to the supporting column flange.

The column must be checked for stiffening requirements. For further information, see AISC
Design Guide No. 13 Wide-Flange Column Stiffening at Moment Connections – Wind and
Seismic Applications (Carter, 1999).

<!-- p. 353 -->

IIB-10

Example II.B-2 Welded Flange-Plated FR Moment Connection
(beam-to-column flange)

Given:

Design a welded flange-plated FR moment connection between a W18×50 beam and a
W14×99 column flange to transfer the following forces:

RD = 7 kips MD = 42 kip-ft
RL = 21 kips ML = 126 kip-ft

Use d-in. diameter ASTM A325-N bolts in standard holes and E70 electrodes.

Material Properties:

Beam W18×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×99 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-4

Geometric Properties:

Beam W18×50 d = 18.0 in. bf = 7.50 in. tf = 0.570 in. tw = 0.355 in. Zx = 101 Manual
in.3 Table 1-1
Column W14×99 d = 14.2 in. bf = 14.6 in. tf = 0.780 in.

<!-- p. 354 -->

IIB-11

Solution:

LRFD ASD
Ru = 1.2(7 kips) + 1.6(21 kips) = 42 kips Ra = 7 kips + 21 kips = 28 kips

Mu = 1.2(42 kip-ft) + 1.6(126 kip-ft) Ma = 42 kip-ft + 126 kip-ft

\= 252 kip-ft = 168 kip-ft

Check the beam flexural strength
LRFD ASD
For a W18×50 For a W18×50
Manual
φbMn = 379 kip-ft > 252 kip-ft o.k. Mn/Ωb = 252 kip-ft > 168 kip-ft o.k. Table 3-3

Design the single-plate web connection

Try a PL a×4×0’-9, with three d-in. diameter ASTM A325-N bolts and 4 in. fillet welds.

LRFD ASD
Shear strength of bolts Shear strength of bolts Manual
Table 7-1
Single shear; Single shear;

φrn = 21.6 kips/bolt rn/Ω = 14.4 kips/bolt

\= 42 kips/(21.6 kips/bolt) = 1.94 bolts = 28 kips/(21.6 kips/bolt) = 1.94 bolts

Bearing Strength of bolts Bearing Strength of bolts Manual
Table 7-5
Bolt spacing = 3 in. Bolt spacing = 3 in.

φrn = (91.4 kips/in./bolt)(a in.) rn/Ω = (60.9 kips/in./bolt)(a in.)

\= 34.3 kips/bolt = 22.8 kips/bolt

\= 42 kips/(34.3 kips/bolt) = 1.22 bolts = 28 kips/(22.8 kips/bolt) = 1.22 bolts

Plate shear yielding Plate shear yielding

φ = 1.00 Ω = 1.50

φRn = 0.60 φFy Ag rn/Ω = 0.60Fy Ag /Ω

\= 0.60(1.00)(36 ksi)(9 in.)(a in.) = 0.60(36 ksi)(9 in.)(a in.)/(1.50)
Eqn J4-3
\= 72.9 kips > 42 kips o.k. = 48.6 kips > 28 kips o.k.

<!-- p. 355 -->

IIB-12

Plate shear rupture Plate shear rupture

φ = 0.75 Ω = 2.00

φRn = 0.60 φFu Anv rn/Ω = 0.60Fu Anv /Ω
Eqn J4-4
(3 bolts)(d in.+ z in.+ z in.) = 3 in. (3 bolts)(d in.+ z in.+ z in.) = 3 in.

Anv = (9 in. – 3 in.)(a in.) = 2.25 in2 Anv = (9 in. – 3 in.)(a in.) = 2.25 in2

\= 0.60(0.75)(58 ksi)(2.25 in2) = 0.60(58 ksi)(2.25 in2)/(2.00)

\= 58.7 kips > 42 kips o.k. = 39.2 kips > 28 kips o.k.

Block shear rupture strength for plate
Leh = 14 in.; Lev = 12 in.; Ubs = 1.0; n = 3

LRFD ASD
⎛ 0.6 Fy Agv Rn Fu Ant U bs Fu Anv ⎞ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) , = + min ⎜ ⎟ Ω Ω ⎝ Ω Ω ⎠

Tension component Tension component

φUbsFuAnt = 32.6 kips/in(a in) UbsFuAnt / Ω = 21.8 kips/in(a in) Manual
Table 9-3a
Shear yielding Shear yielding

φ0.60FyAgv = 121 kips/in(a in) 0.60FyAgv / Ω t = 81.0 kips/in(a in) Manual
Table 9-3b
Shear rupture Shear rupture

φ0.60FuAnv = 131 kips/in(a in) 0.60FuAnv / Ω = 87.0 kips/in(a in) Manual
Table 9-3c
φRn = (121 kips/in + 32.6 kips/in)(a in) Rn/Ω = (81.0 kips/in + 21.6 kips/in)(a in)

\= 57.6 kips > 42 kips o.k. = 38.5 kips > 24 kips o.k.

Weld Strength

φRn = 1.392Dl(2) Rn / Ω = 0.928Dl(2) Manual
Part 8
\= 1.392(4 sixteenths)(9 in.)(2) = 0.928(4 sixteenths)(9 in.)(2)

\= 100 kips > 42 kips o.k. = 66.8 kips > 28 kips o.k.

Connecting Elements Rupture Strength at Welds

Shear rupture strength of base metal
⎛ 2 ⎞⎛ D ⎞
0.6 FEXX ⎜ ⎝ 2 ⎟⎝⎠ ⎜ 16 ⎟⎠ 3.09 D
t min = =
0.6 Fu Fu

<!-- p. 356 -->

IIB-13

Column flange; tf = 0.780 in.

3.09 D ( 3.09 )( 4 sixteenths )
t min = = = 0.190 in.
Fu 65 ksi

Plate; t = a in.

3.09 ( 2 ) D ( 6.19 )( 4 sixteenths )
t min = = = 0.427 in. > a in. proration required
Fu 58 ksi

LRFD ASD
38 in. Rn 38 in. φRn = ( 50.1 kips ) = 44 kips = ( 33.4 kips ) = 29.3 kips 0.427 in. Ω 0.427 in.

44 kips > 42 kips o.k. 29.3 kips > 28 kips o.k.

Design tension flange plate and connection

Determine the flange force
LRFD ASD
M u M a Manual
Puf = Paf = Part 12 d + t p d + t p
( 252 kip-ft )(12 in./ft ) (168 kip-ft )(12 in./ft ) = = 161 kips = = 108 kips
(18.0 in.+ 34 in. ) (18.0 in. + 34 in. )

The top flange width bf = 72 in. Assume a shelf dimension of s in. on both sides of the plate.
The plate width, then, is 72 in. – 2(s in.) = 64 in. Try a 1 in.×64 in. flange plate.

Check top flange plate tension yielding

Eqn. D2-1Rn = Fy Ag = ( 36 ksi )( 6 14 in.)(1 in.) = 225 kips

LRFD ASD
φ = 0.90 Ω = 1.67

φRn = 0.90 ( 225 kips ) = 203 kips 225 kips Rn / Ω= = 135 kips
1.67

203 kips > 161 kips o.k. 135 kips > 108 kips o.k.

Determine the force in the welds
LRFD ASD
M u M a Manual
Puf = Paf = Part 12 d d
( 252 kip-ft )(12 in./ft ) (168 kip-ft )(12 in./ft ) = = 168 kips = = 112 kips
(18.0 in. ) (18.0 in. )

<!-- p. 357 -->

IIB-14

Determine the required weld size and length for fillet welds to beam flange. Try a c-in. fillet
weld. The minimum length of weld lmin is as follows:

For weld compatibility, disregard the increased capacity due to perpendicular loading of the
end weld.

LRFD ASD
Puf 168 kips Paf 112 kips
lmin = = = 24.1 in. lmin = = = 24.1 in. Manual 1.392 D 1.392 ( 5 ) 0.928 D 0.928 ( 5) Part 8

Use 9 in. of weld along each side and 64 in. Use 9 in. of weld along each side and 64 in.
of weld along the end of the flange plate. of weld along the end of the flange plate.

l = 2 ( 9 in. ) + 6 14 in. l = 2 ( 9 in. ) + 6 14 in.

\= 24.2 in. > 24.1 in. o.k. = 24.2 in. > 24.1 in. o.k.

Connecting Elements Rupture Strength at Welds

Shear rupture strength of base metal

⎛ 2 ⎞⎛ D ⎞
0.6 Fexx ⎜ ⎟⎜ ⎟ ⎜ 16 ⎠ 3.09 D ⎝ 2 ⎟⎝⎠ t min = =
0.6 Fu Fu

Beam flange; tf = 0.570 in.

3.09 D ( 3.09 )( 5 sixteenths )
t min = = = 0.238 in.
Fu 65 ksi

Flange plate; tp = 1.00 in.

3.09 D ( 3.09 )( 5 sixteenths )
t min = = = 0.266 in.
Fu 58 ksi

Tension rupture strength of base metal

⎛ 2 ⎞⎛ D ⎞
0.6 Fexx ⎜ ⎟⎜ ⎟ ⎜ 16 ⎠ 1.86 D ⎝ 2 ⎟⎝⎠ t min = =
Fu Fu

Beam flange; tf = 0.570 in.

1.86 D (1.86 )( 5 sixteenths )
t min = = = 0.143 in.
Fu 65 ksi

<!-- p. 358 -->

IIB-15

Flange plate; tf = 1.00 in.

1.86 D (1.86 )( 5 sixteenths )
t min = = = 0.160 in.
Fu 58 ksi

Determine the required fillet weld size to supporting column flange Section J2.4
Eqn. J2-5
The applied tension load is perpendicular to the weld, therefore θ = 90 ° and 1.0 + sin1.5 θ = 1.5.

LRFD ASD
Puf Paf
Dmin = Dmin = 2 (1.5)(1.392 ) l 2 (1.5)( 0.928 ) l

168 kips 112 kips
\= =
2 (1.5)(1.392 )( 6 14 in.) 2 (1.5)( 0.928 )( 6 14 in.)

\= 6.44 sixteenths = 6.44 sixteenths

Use v-in. fillet welds, 7 > 6.44 o.k. Use v-in. fillet welds, 7 > 6.44 o.k.
Note: Tension due to load reversal must also be considered in the design of the fillet weld to the
supporting column flange.

Connecting Elements Rupture Strength at Welds

Tension rupture strength of base metal

⎛ 2 ⎞⎛ D ⎞
0.6 Fexx ⎜ ⎟⎜ ⎟ ⎜ 16 ⎠ 1.86 D ⎝ 2 ⎟⎝⎠ t min = =
Fu Fu

Column flange; tf = 0.780 in.

1.86 D (1.86 )( 7 sixteenths )
t min = = = 0.200 in.
Fu 65 ksi

flange plate; tp = 1.00 in.

1.86 ( 2 ) D ( 3.71)( 7 sixteenths )
t min = = = 0.448 in.
Fu 58 ksi

Design compression flange plate and connection

The compression flange plate should have approximately the same area as the tension flange
plate ( A = 6 14 in. × 1 in. = 6.25 in. 2 ). Assume a shelf dimension of s in. The plate width, then,
is 72 in. + 2(s in.) = 8w in. To approximately balance the flange plate areas, try a w in. × 8w
in. compression flange plate.

<!-- p. 359 -->

IIB-16

Assume K = 0.65 and l = 2.0 in. (12 in. edge distance and 2-in. setback).

Kl 0.65 ( 2.0 in.) = = 6.00 \< 25
r ⎛ 34 in. ⎞
⎜ ⎟ ⎝ 12 ⎠

2 3 3A = ( 8 4 in.)( 4 in. ) = 6.56 in.

LRFD ASD
φ = 0.90 Ω = 1.67

2 2 φRn = φFy Ag = 0.90 ( 36 ksi )( 6.56 in. ) Fy Ag ( 36 ksi )( 6.56 in. )
Rn / Ω= = Eqn. E3-1 Ω 1.67

\= 212 kips > 161 kips o.k. = 141 kips > 108 kips o.k.

Determine the required weld size and length for fillet welds to beam flange

Based upon the weld length required for the tension flange plate, use c in. fillet weld and
122 in. of weld along each side of the beam flange.

Connecting Elements Rupture Strength at Welds

Shear rupture strength of base metal

⎛ 2 ⎞⎛ D ⎞
0.6 Fexx ⎜ ⎟⎜ ⎟ ⎜ 16 ⎠ 3.09 D ⎝ 2 ⎟⎝⎠ t min = =
0.6 Fu Fu

Beam flange; tf = 0.570 in.

3.09 D ( 3.09 )( 5 sixteenths )
t min = = = 0.238 in.
Fu 65 ksi

Bottom flange plate; tp = 0.750 in.

3.09 D ( 3.09 )( 5 sixteenths )
t min = = = 0.266 in.
Fu 58 ksi

The column must be checked for stiffening requirements. For further information, see AISC
Design Guide No. 13 Wide-Flange Column Stiffening at Moment Connections – Wind and
Seismic Applications. (Carter, 1999).

<!-- p. 360 -->

IIB-17

Example II.B-3 Directly-Welded Flange FR Moment Connection
(beam-to-column flange).

Given:

Design a directly welded flange FR moment connection between a W18×50 beam and a
W14×99 column flange to transfer the following forces:

RD = 7 kips MD = 42 kip-ft
RL = 21 kips ML = 126 kip-ft

Use d-in. diameter ASTM A325-N bolts in standard holes and E70 electrodes.

Material Properties:

Beam W18×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×99 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-4

Geometric Properties:

Beam W18×50 d = 18.0 in. bf = 7.50 in. tf = 0.570 in. tw = 0.355 in. Zx = 101 in.3 Manual
Column W14×99 d = 14.2 in. bf = 14.6 in. tf = 0.780 in. Table 1-1

<!-- p. 361 -->

IIB-18

Solution:

LRFD ASD
Ru = 1.2(7 kips) + 1.6(21 kips) = 42 kips Ra = 7 kips + 21 kips = 28 kips

Mu = 1.2(42 kip-ft) + 1.6(126 kip-ft) Ma = 42 kip-ft + 126 kip-ft

\= 252 kip-ft = 168 kip-ft

Check beam flexural strength
LRFD ASD
For a W18×50 For a W18×50
Manual
φbMn = 379 kip-ft > 252 kip-ft o.k. Mn /Ωb = 252 kip-ft > 168 kip-ft o.k. Table 3-2

Design single-plate web connection

Try a PL a×4×0’-9, with three d-in. diameter ASTM A325-N bolts and 4 in. fillet welds.

LRFD ASD
Shear strength of bolts Shear strength of bolts Manual
Table 7-1
Single shear; Single shear;

φrn = 21.6 kips/bolt rn/Ω = 14.4 kips/bolt

\= 42 kips/(21.6 kips/bolt) = 1.94 bolts = 28 kips/(14.4 kips/bolt) = 1.94 bolts

Bearing Strength of bolts Bearing Strength of bolts Manual
Table 7-5
Bolt spacing = 3 in. Bolt spacing = 3 in.

φrn = (91.4 kips/in./bolt)(a in.) rn/Ω = (60.9 kips/in./bolt)(a in.)

\= 34.3 kips/bolt = 22.8 kips/bolt

\= 42 kips/(34.3 kips/bolt) = 1.47 bolts = 28 kips/(22.8 kips/bolt) = 1.22 bolts

Plate shear yielding Plate shear yielding

φ = 1.00 Ω = 1.50

φRn = 0.60φFy Ag rn/Ω = 0.60Fy Ag /Ω =
Eqn. J4-3
\= 0.60(1.00)(36 ksi)(9 in.)(a in.) = = 0.60(36 ksi)(9 in.)(a in.)/(1.50)

\= 72.9 kips > 42 kips o.k. = 48.6 kips > 28 kips o.k.

Plate shear rupture Plate shear rupture

φ = 0.75 Ω = 2.00

Eqn. J4-4 φRn = 0.60φFu Anv rn/Ω = 0.60Fu Anv /Ω

(3 bolts)(d in.+ z in.+ z in.) = 3 in. (3 bolts)(d in.+ z in.+ z in.) = 3 in.

<!-- p. 362 -->

IIB-19

Anv = (9 in. – 3 in.)(a in.) = 2.25 in2 Anv = (9 in. – 3 in.)(a in.) = 2.25 in2

\= 0.60(0.75)(58 ksi)(2.25 in2) = 0.60(58 ksi)(2.25 in2)/(2.00)

\= 58.7 kips > 42 kips o.k. = 39.2 kips > 28 kips o.k.

Block shear rupture strength for plate

Leh = 14 in.; Lev = 12 in.; Ubs = 1.0; n = 3

LRFD ASD
Rn Fu Ant U bs ⎛ 0.6 Fy Agv Fu Anv ⎞ Manual , Table 9-3a ⎜ ⎟ Ω ⎝ Ω ⎠ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) Ω = Ω + min

Tension component Tension component Manual
Table 9-3b
φFuAnt = 32.6 kips/in(a in) FuAnt / Ω = 21.8 kips/in(a in)

Shear yielding component Shear yielding component Manual
Table 9-3c
φ0.60FyAgv = 121 kips/in(a in) 0.60FyAgv / Ω = 81.0 kips/in(a in)

Shear rupture component Shear rupture component

φ0.60FuAnv = 131 kips/in(a in) 0.60FuAnv / Ω = 87.0 kips/in(a in)

φRn = (121 kips/in + 32.6 kips/in)(a in) Rn/Ω = (81.0 kips/in + 21.6 kips/in)(a in)

\= 57.6 kips > 42 kips = 38.5 kips > 24 kips

Weld Strength Weld Strength Manual
Part 8
φRn = 1.392Dl(2) Rn / Ω = 0.928Dl(2)

\= 1.392(4 sixteenths)(9 in.) = 0.928(4 sixteenths)(9 in.)

\= 50.1 kips > 42 kips = 33.4 kips > 28 kips

Connecting Elements Rupture Strength at Welds

Shear rupture strength of base metal

⎛ 2 ⎞⎛ D ⎞
0.6 Fexx ⎜ ⎟⎜ ⎟ ⎜ 16 ⎠ 3.09 D ⎝ 2 ⎟⎝⎠ t min = =
0.6 Fu Fu

Column flange tf = 0.780 in.

3.09 D ( 3.09 )( 4 sixteenths )
t min = = = 0.190 in.
Fu 65 ksi

<!-- p. 363 -->

IIB-20

Plate tp = a in.

3.09 ( 2 ) D ( 6.19 )( 4 sixteenths )
t min = = = 0.427 in.
Fu 58 ksi

LRFD ASD
38 in. Rn 38 in. φRn = ( 50.1 kips ) = 44 kips = ( 33.4 kips ) = 29.3 kips 0.427 in. Ω 0.427 in.

44 kips > 42 kips o.k. 29.3 kips > 28 kips o.k.

A complete-joint penetration groove weld will transfer the entire flange force in tension and Table J2.5
compression.

Note: The column must be checked for stiffening requirements. For further information, see
AISC Design Guide No. 13 Wide-Flange Column Stiffening at Moment Connections – Wind
and Seismic Applications. (Carter, 1999).

<!-- p. 364 -->

IIB-21

Example II.B-4 Four-Bolt Unstiffened Extended End-Plate FR Moment
Connection (beam-to-column flange).
Given:
Design a four-bolt unstiffened extended end-plate FR moment connection between a W18×50
beam and a W14×99 column-flange to transfer the following forces:

RD = 7 kips MD = 42 kip-ft
RL = 21 kips ML = 126 kip-ft

Use ASTM A325-N snug-tight bolts in standard holes and E70 electrodes.

a. Use design procedure 1 (thick end-plate and smaller diameter bolts) from AISC Steel
Design Guide 16 Flush and Extended Multiple-Row Moment End-Plate Connections.
b. Use design procedure 2 (thin end-plate and larger diameter bolts) from AISC Steel
Design Guide 16 Flush and Extended Multiple-Row Moment End-Plate Connections.

Material Properties:

Beam W18×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Column W14×99 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-4

Geometric Properties:

Beam W18×50 d = 18.0 in. bf = 7.50 in. tf = 0.570 in. tw = 0.355 in. Sx = 88.9 in.3 Manual
Column W14×99 d = 14.2 in. bf = 14.6 in. tf = 0.780 in. Table 1-1

<!-- p. 365 -->

IIB-22

Solution A:

LRFD ASD
Ru = 1.2(7 kips) + 1.6(21 kips) = 42 kips Ra = 7 kips + 21 kips = 28 kips

Mu = 1.2(42 kip-ft) + 1.6(126 kip-ft) Ma = 42 kip-ft + 126 kip-ft

\= 252 kip-ft = 168 kip-ft

Check beam flexural strength
LRFD ASD
For a W18×50 For a W18×50
Manual
φbMn = 379 kip-ft > 252 kip-ft o.k. Mn /Ωb = 252 kip-ft > 168 kip-ft o.k. Table 3-3

Extended end-plate geometric properties:

bp = 72 in. g = 52 in. pf,i = 12 in. pf,o = 12 in. pext = 3 in.

Calculate secondary dimensions

h0 = d + p f , o = 18.0 in. + 1 1 2 in. = 19 1 2 in.

t f 0.570 in.
d o = h0 − = 19 12 in. − = 19.22 in.
2 2

h1 = d − p f , i − t f = 18.0 in. − 1 12 in. − 0.570 in. = 15.9 in.

ft 0.570 in.
d1 = h1 − = 15.93 in. − = 15.6 in.
2 2

rγ = 1.0 for extended end-plates

Determine the required bolt diameter assuming no prying action

For ASTM A325-N bolts, Fnt = 90 ksi Table J3.2

LRFD ASD
2 M u 2 M a Ω d breq = d breq = d n ) d n ) πφFnt ( ∑ π Fnt ( ∑

2 ( 252 kip-ft )(12 in./ft ) 2 (168 kip-ft )(12 in./ft )( 2.00 ) = =
π ( 0.75 )( 90 ksi )(19.2 in. + 15.6 in. ) π ( 90 ksi )(19.2 in. + 15.6 in.)

\= 0.905 in. = 0.905 in.
Use 1-in. diameter ASTM A325-N snug- Use 1-in. diameter ASTM A325-N snug-
tightened bolts. tightened bolts.

Determine the required end-plate thickness

<!-- p. 366 -->

IIB-23

1 1 b p g ( 7 2 in.)( 5 2 in.)
s = = = 3.21 in.
2 2

Verify interior bolt pitch, p f , i = 1 12 in. ≤ s = 3.21 in. o.k.

b p ⎡ ⎛ 1 1 ⎞ ⎛ 1 ⎞ ⎤ 2 ⎡ ⎤ Y = + + ⎢ − 12 ⎥ h1 ⎜ ⎟ + h0 ⎜ ⎟ h1 ( p f , i + s ) ⎣ ⎦ 2 s g ⎠ ⎠ ⎝ p f , i ⎝ p f , o ⎢⎣ ⎥⎦

7 12 in. ⎡ ⎛ 1 1 ⎞ 1 ⎛ 1 ⎞ 1 ⎤ + − 2 ⎥ ⎟ = ⎢ (15.93 in.) ⎜ 1 + (19 2 in.) ⎜ 1 ⎟ 2 ⎣ ⎝ 1 2 in. 3.21 in. ⎠ ⎝ 1 2 in. ⎠ ⎦

2
\+ ⎡ ⎣( 15.93 in.)(1 12 in. + 3.21 in.) ⎤⎦ 5 12 in.

\= 133

πd b 2 Fnt π (1 in.) 2 ( 90 ksi ) Pt = = = 70.7 kips
4 4
d n ) = 2 ( 70.7 kips )(19.2 in. + 15.6 in. ) = 4930 kip-in.M n = 2 Pt ( ∑

LRFD ASD
φ = 0.75 Ω = 2.00

4930 kip-in.
M n / Ω= = 2460 kip-in. φM n = 0.75 ( 4930 kip-in. ) = 3700 kip-in. 2.00

φ = 0.90 Ω = 1.67

1.11γ r φM np 1.11γ r ⎛ M np ⎞
t p req ' d = t p req ' d = ⎜ ⎟ φ b Fpy Y ⎛ Fpy ⎞ ⎝ Ω ⎠
⎜ ⎟ Y ⎝ Ω b ⎠
1.11 (1.0 )( 3700 kip-in. ) 1.11 (1.0 )( 2460 kip-in. )(1.67 ) = =
( 0.90 )( 36 ksi )(133 in. ) ( 36 ksi )(133 in. )

\= 0.977 in. = 0.978 in.

Use a 1-in. thick end-plate. Use a 1-in. thick end-plate.

<!-- p. 367 -->

IIB-24

LRFD ASD
Calculate end-plate design strength Calculate end-plate allowable strength

From above, φM n = 3700 kip-in. From above, M n / Ω= 2464 kip-in.

φ = 0.90 Ω = 1.67

φ b M pl φ b Fpy t p 2 Y M pl Fpy t p 2 Y
\= =
γ r γ r Ωγb r Ωγb r

0.90 ( 36 ksi )(1 in.) 2 (133 in.) ( 36 ksi )(1 in. ) 2 (133 in. ) = =
1.0 1.67 (1.0 )

\= 4310 kip-in. = 2860 kip-in.

M ⎛ φ b pl ⎞ M ⎛ ⎞ pl φM n = min φM np , ⎜ ⎟ M n / Ω=b min M np / Ω b , γ ⎜ ⎟ ⎝ ⎠ r Ωγ ⎝ b r ⎠

\= 3700 kip-in. or 308 kip-ft = 2460 kip-in. or 205 kip-ft

308 kip-ft > 252 kip-ft o.k. 205 kip-ft > 168 kip-ft o.k.

Check bolt shear

Try the minimum of four bolts at tension flange and two bolts at compression flange.

LRFD ASD
φRn = nφrn = ( 2 bolts )( 28.3 kips/bolt ) Rn / Ω= nrn / Ω= ( 2 bolts )(18.8 kips/bolt ) Manual
Table 7-1
\= 56.6 kips > 42 kips o.k. = 37.6 kips > 28 kips o.k.

Determine the required size of the beam Determine the required size of the beam web- Manual
web-to end-plate fillet weld to end-plate fillet weld Part 8

φFy t w 0.90 ( 50 ksi )( 0.355 in. ) Fy t w ( 50 ksi )( 0.355 in. )
Dmin = = Dmin = = 2 (1.39 ) 2 (1.39 ) 2 Ω ( 0.928 ) 2 (1.67 )( 0.928 )

\= 5.75 sixteenths = 5.73 sixteenths

Use a in. fillet welds on both sides of the beam web from the inside face of the beam flange to
the centerline of the inside bolt holes plus two bolt diameters.

Determine weld size required for the end reaction

The end reaction , Ru or Ra, is resisted by weld between the mid-depth of the beam and the
inside face of the compression flange or between the inner row of tension bolts plus two bolt
diameters, which ever is smaller. By inspection the former governs for this example.

<!-- p. 368 -->

IIB-25

d 18.0 in.
l = − t f = − 0.570 in. = 8.43 in.
2 2

LRFD ASD
Ru 42 kips Ra 28 kips Dmin = = Dmin = = 2 (1.39 ) l 2 (1.39 )( 8.43 in.) 2 ( 0.928 ) l 2 ( 0.928)( 8.43 in.)

\= 1.79 → 3 sixteenths (minimum size) = 1.79 → 3 sixteenths (minimum size)
Table J2.4
Use x-in. fillet weld on both sides of the Use x-in. fillet weld on both sides of the
beam web below the tension-bolt region. beam web below the tension-bolt region.

Connecting Elements Rupture Strength at Welds

Shear rupture strength of base metal

⎛ 2 ⎞⎛ D ⎞
0.6 Fexx ⎜ ⎟⎜ ⎟ ⎜ 16 ⎠ 3.09 D ⎝ 2 ⎟⎝⎠ t min = =
0.6 Fu Fu

Beam web tw = 0.355 in.

3.09 ( 2 ) D ( 6.19 )( 3 sixteenths )
t min = = = 0.285 in.
Fu 65 ksi

End plate tp = 1 in.

3.09 D ( 3.09 )( 3 sixteenths )
t min = = = 0.160 in.
Fu 58 ksi

LRFD ASD
⎛ 0.355 in. ⎞ ⎛ 0.355 in. ⎞
Ru = 1.392 Dl ⎜ ⎟ Ra = 0.928 Dl ⎜ ⎟ ⎝ 0.285 in. ⎠ ⎝ 0.476 in. ⎠

⎛ 0.355 in. ⎞ ⎛ 0.355 in. ⎞ = 1.392 ( 3 sixteenths )( 2 )( 8.43 in.) ⎜ ⎟ = 0.928 ( 3 sixteenths )( 2 )( 8.43 in.) ⎜ ⎟ ⎝ 0.285 in. ⎠ ⎝ 0.285 in. ⎠
\= 87.7 kips > 42 kips = 58.5 kips > 28 kips

Determine required fillet weld size for the beam flange to end-plate connection

l = 2 − t w = 2 ( 7.50 in. + 0.570 in.) − 0.355 in. = 15.8 in. ( b f + t f )

<!-- p. 369 -->

IIB-26

LRFD ASD
2 M u 2 ( 252 kip-ft )(12 in./ft ) 2 M a 2 (168 kip-ft )(12 in./ft ) Puf = = Paf = =
d n 19.2 in. + 15.6 in. ∑ d n 19.2 in. + 15.6 in. ∑

\= 173 kips = 116 kips
Puf 173 kips Paf 116 kips
Dmin = = Dmin = = 1.5 (1.39 ) l 1.5 (1.39 )(15.8 in. ) 1.5 ( 0.928 ) l 1.5 ( 0.928 )(15.8 in.)

\= 5.27 → 6 sixteenths (minimum size) = 5.27 → 6 sixteenths (minimum size)

Note that the 1.5 factor is from Specification J2.4.

Use a-in. fillet welds at beam tension flange. Welds at compression flange may be 4-in. fillet
welds (minimum size per Specification Table J2.4).

Connecting Elements Rupture Strength at Welds

Tension rupture strength of base metal

Rn = Fu Ae Section J4.1
⎛ 2 ⎞⎛ D ⎞
0.6 Fexx ⎜ ⎟⎜ ⎟ ⎜ 16 ⎠ 1.86 D ⎝ 2 ⎟⎝⎠ t min = =
Fu Fu

Beam flange; tf = 0.570in.

1.86 ( 2 ) D ( 3.71)( 6 sixteenths )
t min = = = 0.343 in.
Fu 65 ksi

End plate; tp = 1.00 in.

1.86 D (1.86 )( 6 sixteenths )
t min = = = 0.192 in.
Fu 58 ksi

<!-- p. 370 -->

IIB-27

Solution B:

Only those portions of the design that vary from the solution “A” calculations are presented
here.

LRFD ASD
Determine required end-plate thickness Determine required end-plate thickness

φ = 0.90 Ω = 1.67

γ r M u γ r M a Ω b t preq = t preq =
φ b Fy Y Fy Y

1.0 ( 252 kip-ft )(12 in./ft ) 1.0 (168 kip-ft )(12 in./ft )(1.67 ) = =
0.90 ( 36 ksi )(133 in.) ( 36 ksi )(133 in.)

\= 0.84 in. = 0.84 in.

Use tp = d in. Use tp = d in.

Select a trial bolt diameter and calculate the maximum prying forces

Try 1-in. diameter bolts.

b p 1 7.50 in. 1w ' = − ( d b + 16 in.) = − (1 16 in.) = 2.69 in.
2 2

⎛ t p ⎞ 3 ⎛ 78 in. ⎞ 3
ai = 3.682 ⎜ ⎟ − 0.085 = 3.682 ⎜ ⎟ − 0.085 = 2.38 ⎝ d b ⎠ ⎝ 1 in. ⎠
2 ⎡ ⎛ b p ⎞ ⎤ πd b 3 Fnt
t p Fyp ⎢ 0.85 ⎜ ⎟ + 0.80 w ' ⎥ + ⎝ 2 ⎠ 8 ⎣ ⎦Fi ' =
4 p f , i

2 ⎡ ⎛ 7 1 2 ⎤ ( 78 ) ( 36 ) ⎢ 0.85 ⎜ ⎞+⎟ 0.80 ( 2.69 ) ⎥ ⎣ ⎝ 2 ⎠ ⎦ =
4 (1 12 )

π (1) 3 ( 90 )
8 +
4 (1 12 )

\= 30.4 kips

<!-- p. 371 -->

IIB-28

w ' t p 2 2 ⎛ Fi ' ⎞ 2Qmax i = Fyp −⎜3 ⎟ ⎜ ⎟ 4 ai ⎝ w ' t p ⎠

( 2.69 )( 78 ) 2 2 ⎛ 30.4 ⎞ 2 = 36 −⎜3 ⎟
4 ( 2.38 ) ⎜⎝ 2.69 ( 78 ) ⎟⎠

\= 6.10 kips

1 2 in. 2.38 in., 1 1 2 in. ] = 1ao = min ⎡⎣ ai , pext − p f , o ⎤⎦ = min [
⎛ p f i ⎞ ⎛ 1 12 in. ⎞Fo ' = Fi ' ⎜ ⎟ = ( 30.4 kips ) ⎜ ⎟ ⎝ p fo ⎠ ⎝ 1 12 in. ⎠

\= 30.4 kips

w ' t p 2 2 ⎛ Fo ' ⎞ 2Qmax o = Fyp −⎜3 ⎟ ⎜ ⎟ 4 ao ⎝ w ' t p ⎠

( 2.69 )( 78 ) 2 2 ⎛ 30.4 ⎞ 2 = 36 −⎜3 ⎟ 7 2.69 ( 4 (1 12 ) ⎜⎝ 8 ) ⎟⎠

\= 9.68 kips

Calculate the connection available strength for the limit state of bolt rupture with prying
action
πd b 2 Fnt π (1 in.) 2 ( 90 ksi )Pt = = = 70.7 kips
4 4
Unmodified Bolt Pretension, bT 0 = 51 kips

Modify bolt pretension for the snug-tight condition. Table J3.1

Tb 0 51 kips
Tb = = = 12.8 kips AISC Design 4 4
Guide 16
Table 2-1,
Table 4-2

<!-- p. 372 -->

IIB-29

LRFD ASD
M q
\= φM q = Ω
⎧ 1 ⎫ ⎡ ⎣( ⎪ Pt − Qmax o ) d 0 + 2 ( Pt − Qmax i ) d1 ⎤⎦ ⎪ ⎧ φ ⎡ ⎣ 2 ( Pt − Qmax o ) d 0 + 2 ( Pt − Qmax i ) d1 ⎤⎦ ⎫ ⎪ Ω ⎪ ⎪ ⎪ ⎪ 1 ⎪ ⎡ ⎪ ⎪ ⎤ ⎣ 2 ( ⎪⎣ φ ⎡ 2 ( Pt − Qmax o ) d 0 + 2 ( Tb ) d1 ⎦ ⎪ Pt − Qmax o ) d 0 + 2 ( Tb ) d1 ⎤⎦ ⎪ ⎪ Ω max ⎨ ⎬ max ⎨ ⎬
1 φ ⎡ ⎪ ⎣ 2 ( Pt − Qmax i ) d1 + 2 ( Tb ) d 0 ⎤⎦ ⎪ ⎪ ⎡ ⎣ 2 ( Pt − Qmax i ) d1 + 2 ( Tb ) d 0 ⎤⎦ ⎪ ⎪ ⎪ ⎪ ⎪ Ω ⎪⎩ φ ⎡⎣ 2 ( Tb )( d 0 + d1 ) ⎤⎦ ⎪⎭ ⎪ ⎪ 1 ⎪ ⎡ ⎣ 2 ( Tb )( d 0 + d1 ) ⎤⎦ ⎪ ⎩Ω ⎭

⎧ ⎫ 2 ( 70.7 − 9.68 )(19.2 ) ⎤ 1 ⎡ ⎧ ⎡ 2 ( 70.7 − 9.68 )(19.2 ) ⎤ ⎫ ⎪ ⎪ ⎢ ⎥ ⎪ ⎪ 0.75 ⎢ ⎥ ⎪ 2.00 ⎢⎣ +2 ( 70.7 − 6.10 )(15.6 ) ⎥⎦ ⎪ ⎪ ⎪ 70.7 − 6.10 )(15.6 ) ⎢⎣ + 2 ( ⎥⎦ ⎪ ⎪ ⎪ ⎪ ⎪ 1 ⎡ 2 ( 70.7 − 9.68 )(19.2 ) ⎤ ⎪ ⎡ 2 9.68 − ⎪ ⎪ ( 70.7 )( 19.2 ) ⎤ ⎢ ⎥ ⎪ ⎪ 0.75 ⎢ ⎥ ⎪ ⎪ 2.00 ⎪ ⎪ 12.8 )(15.6 ) ⎢⎣ +2 ( ⎥⎦ = max 15.6 + 2 = max ⎨ ⎬ (12.8 )( ) ⎨ ⎬ ⎢⎣ ⎥⎦
⎪ ⎪ ⎪ 1 ⎡ 2 ( 70.7 − 6.10 )(15.6 ) ⎤ ⎪ ⎪ ⎡ 2 ( 70.7 − 6.10 )(15.6 ) ⎤ ⎪ ⎪ ⎢ ⎥ ⎪
⎪ 0.75 ⎢ ⎥ ⎪ ⎪ 2.00 ⎢⎣ +2 ( 12.8 )(19.2 ) ⎥⎦ ⎪ ⎪ ⎢⎣ + 2 ( 12.8 )(19.2 ) ⎥⎦ ⎪ ⎪ ⎪
⎪ ⎡ 0.75 ⎡ ⎣ 2 ( ⎣ 2 ( ⎩ 12.8 )(19.215 + 15.6 ) ⎤⎦ ⎪⎭ ⎩⎪⎪ 2.001 12.8 )(19.215 + 15.6 ) ⎤⎦ ⎪⎪⎭

⎧3275 kip-in. ⎫ ⎧ 2183 kip-in. ⎫
⎪ ⎪ ⎪ ⎪ ⎪ 2059 kip-in. ⎪ ⎪1373 kip-in. ⎪ = max ⎨ ⎬ = 3275 kip-in. = max ⎨ ⎬ = 2138 kip-in.
⎪1885 kip-in. ⎪ ⎪1257 kip-in. ⎪
⎪ ⎪ ⎩669 kip-in. ⎭ ⎪⎩ 446 kip-in. ⎪⎭

3275
φM q = 3275 kip-in. M q / Ω= 1.5 = 2183 kip-in.
\= 273 kip-ft > 252 kip-ft o.k. = 182 kip-ft > 168 kip-ft o.k.

For Example IIB-4, design procedure 1 produced a design with a 1-in. thick end-plate and 1in. diameter bolts. Design procedure 2 produced a design with a d-in. thick end-plate and 1-in.
diameter bolts. Either design is acceptable. Design procedure 1 did not produce a smaller bolt
diameter for this example, although in general it should result in a thicker plate and smaller
diameter bolt than design procedure 2. It will be noted that the bolt stress is lower in design
procedure 1 than in design procedure 2.

<!-- p. 373 -->

IIC-1

Chapter IIC
Bracing and Truss Connections

The design of bracing and truss connections is covered in
Part 13 of the AISC Steel Construction Manual.

<!-- p. 374 -->

IIC-2

Example II.C-1 Truss Support Connection

Given:

Determine:

a. the connection requirements between gusset and column,
b. the required gusset size and the weld requirements for member U0L1 at the gusset.

RD = 18.5 kips
RL = 55.5 kips

Use d-in. diameter ASTM A325-N bolts in standard holes and E70 electrodes.

<!-- p. 375 -->

IIC-3

Material Properties: Manual
Top Chord WT8×38.5 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Column W12×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi and 2-4
Brace 2L4×32×a ASTM A36 Fy = 36 ksi Fu = 58 ksi
Gusset Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi
Clip Angles 2L4×4 ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:
Top Chord WT8×38.5 tw = 0.455 in. Manual
Brace 2L4×32×a t = 0.375 in. Table 1-8

Solution:

LRFD ASD
Brace axial load Brace axial load

Ru = 174 kips Ra = 116 kips

Truss end reaction Truss end reaction

Ru = 1.2 (18.5) + 1.6 ( 55.5) = 111 kips Ra = 18.5 + 55.5 = 74 kips

Top chord axial load Top chord axial load

Ru = 140 kips Ra = 93 kips

Design the weld connecting the diagonal to the gusset

Note: Specification Section J1.7 requiring that the center of gravity of the weld group coincide
with the center of gravity of the member does not apply to end connections of statically loaded Section J1.7
single angle, double angle and similar members.

For a-in. angles, Dmin = 3, try 4-in. fillet welds, D = 4. Table J2.4
LRFD ASD
Ru 174 kips Ra 116 kips Lreq = = = 7.81 in. Lreq = = = 7.81 in. 4 D (1.392 ) 4 ( 4 )(1.392 ) 4 D (1.392 ) 4 ( 4 )( 0.928 )

Use 8 in. at the heel and 8 in. at the toe of Use 8 in. at the heel and 8 in. at the toe of
each angle. each angle.

Determine minimum gusset thickness based on weld size

Note: This check is required only when the stress in the plate is unknown. Since, in this case,
the stress is known and gusset block shear rupture will be checked, this is not required. It is
included here to illustrate the method.

For two 4-in. fillet welds,

6.19 D 6.19 ( 4 )
t min = = = 0.427 in. Fu ( 58 ksi )

<!-- p. 376 -->

IIC-4

Use a 2 in. gusset plate. With the diagonal to gusset welds determined, a gusset plate layout as
shown in Figure (c) can be made.

LRFD ASD
Design bolts connecting clip angles to Design bolts connecting clip angles to
column (shear and tension) column (shear and tension)

The number of d-in. diameter ASTM A325- The number of d-in. diameter ASTM A325-
N bolts required for shear only is as follows: N bolts required for shear only is as follows:

Ru 111 kips Ru 74 kips Manual
nmin = = = 5.14 nmin = = = 5.14 Table 7-1 φrn 21.6 kips/bolt φrn 14.4 kips/bolt

Try a clip angle thickness of s in. For a trial calculation, the number of bolts was increased to
10 in pairs at 3-in. spacing; this is done to “square off” the connection as shown

LRFD ASD
With 10 bolts, With 10 bolts,

Ru 111 kips Ra 74 kips
f v = = 2 = 18.5 ksi f v = = 2 = 12.3 ksi nAb (10 bolts )( 0.601 in. ) nAb (10 bolts )( 0.601 in. )

LRFD ASD
The eccentric moment at the faying surface The eccentric moment at the faying surface is
is as follows: as follows:

M u = Ru e = (111 kips )( 6.1 in.) = 677 kip-in. M a = Ra e = ( 74 kips )( 6.1 in.) = 451 kip-in.

For the bolt group, the Case II approach of Manual Part 7 can be used. Thus, the maximum
tensile force per bolt, T, is given by:

n’ = number of bolts above the neutral axis = 4 bolts
dm = moment arm between resultant tensile force and resultant compressive force = 9 in.

LRFD ASD
M u 677 kip-in. M a 451 kip-in. Tu = = = 18.8 kips/bolt Ta = = = 12.5 kips/bolt n ' d m ( 4 bolts )( 9 in.) n ' d m ( 4 bolts )( 9 in.)

LRFD ASD
Check design tensile strength of bolts Check design tensile strength of bolts

Fnt ΩFnt Fnt ' = 1.3 Fnt − f v ≤ Fnt Fnt ' = 1.3 Fnt − f v ≤ Fnt
φFnv Fnv
Eqn. J3-3a
(LRFD) and
90 ksi ( 2.00 )( 90 ksi ) J3-3b (ASD) = 1.3 ( 90 ksi ) − (18.5 ksi ) = 1.3 ( 90 ksi ) − (12.3 ksi ) 0.75 ( 48 ksi ) 48 ksi
Table J3.2
\= 70.8 ksi \< 90 ksi o.k. = 70.1 ksi \< 90 ksi o.k.

<!-- p. 377 -->

IIC-5

2
2 Fnt ' B = φFnt ' Ab = 0.75 ( 70.8 ksi )( 0.601 in. ) B = Ab = 70.1 ksi ( 0.601 in. ) Ω 2.00
\= 31.9 kips > 18.8 kips o.k.
\= 21.1 kips > 12.5 kips o.k.

Check the clip angles

Check prying action.

p = 3 in.

58 in.b = 2 in. − = 1.69 in.
2

Note: 14 in. entering and tightening clearance accommodated, o.k.

a = 4 in. − 2 in. ≤ 1.25b (for calculation purposes)

\= 2 in. \< 1.25 (1.69 in.) = 2.11 in. o.k.

d ( 78 in.)b ' = b − = 1.69 in. − = 1.25 in.
2 2

d ( 78 in.)a ' = a + = 2 in. + = 2.44 in.
2 2

b ' 1.25 in.
ρ = = = 0.512
a ' 2.44 in.

d ' 1516 in.δ = 1 − = 1 − = 0.688
p 3 in.

LRFD ASD
4.44 Bb ' 4.44 ( 31.9 kips )(1.25 in.) 6.66 Bb ' 6.66 ( 21.1 kips )(1.25 in.)
tc = = tc = = pFu ( 3 in.)( 58 ksi ) pFu ( 3 in.)( 58 ksi )

\= 1.01 in. = 1.01 in.

1 ⎡ ⎛ ct ⎞ 2 ⎤
α ' = ⎢ ⎜ ⎟ − 1⎥ δ (1 + ρ) ⎢⎣ ⎝ t ⎠ ⎥⎦
1 ⎡ ⎛ 1.01 in. ⎞ 2 ⎤
\= ⎢ ⎜ ⎟ − 1⎥ 0.688 (1 + 0.512 ) ⎢⎣ ⎝ 0.625 in. ⎠ ⎥⎦

\= 1.55

<!-- p. 378 -->

IIC-6

Since α ' > 1, use α ' = 1.0

LRFD ASD
⎛ t ⎞ 2 ⎛ t ⎞ 2 1 + δα ') Ta = B ⎜ ⎟ ( 1 + δα ') Ta = B ⎜ ⎟ ( ⎝ t c ⎠ ⎝ t c ⎠

⎤ = ( 21.1 kips ) ⎜⎛ 0.625 in. ⎟⎣⎞⎡2 1 + 0.688 (1) ⎤⎦ = ( 31.9 kips ) ⎜⎛ 0.625 in. ⎟⎣⎞⎡2 1 + 0.688 ( 1) ⎦ ⎝ 1.01 in. ⎠ ⎝ 1.01 in. ⎠

\= 20.6 kips > 18.8 kips o.k. = 13.6 kips > 12.5 kips o.k.

Check shear yielding of the clip angles Check shear yielding of the clip angles

Ag φRn = φ ( 0.6 Fy ) Ag ( 0.6 Fy )
Rn / Ω= Ω
\= 1.0 ( 0.6 )( 36 ksi ) ⎡⎣ 2 (15.0 in.)( 58 in.) ⎤⎦
( 0.6 )( 36 ksi ) ⎡⎣ 2 (15.0 in.)( 58 in.) ⎤⎦ =
1.50

\= 405 kips > 111 kips o.k. = 270 kips > 74 kips o.k.

Check shear rupture of the angles Check shear rupture of the angles

2 in.) = 12.5 in. in.) = 12.5 in. 2 An = 2 ⎡⎣15.0 in. − 5 ( 1 in.) ⎤⎦ ( 58 An = 2 ⎡⎣15.0 in. − 5 ( 1 in.) ⎤⎦ ( 58

( 0.6 Fu ) An
n / Ω= φRn = φ ( 0.6 Fu ) An R Ω

2 2 = 0.75 ( 0.6 )( 58 ksi )(12.5 in. ) ( 0.6 )( 58 ksi )(12.5 in. ) =
2.00

\= 326 kips > 111 kips o.k. = 218 kips > 74 kips o.k.

Check block shear rupture of the clip angles
Section J4.3
Assume uniform tension stress, use Ubs = 1.0.

2 5 8 in.) = 16.9 in.Gross area subject to shear, Agv = 2 (15.0 in. − 1 12 in.)(

5 = 11.3 in.2 1 in.)(Net area subject to shear, Anv = 16.9 in.2 − 2 ⎡⎣ 4 12 ( 8 in.) ⎤⎦

5 5 = 1.88 in.2 2 in.)( 8 in.) − 0.5 (1 in.)(Net area subject to tension, Anv = 2 ⎡⎣( 8 in.) ⎤⎦

<!-- p. 379 -->

IIC-7

LRFD ASD
⎤ ⎡ ⎤ 0.6 Fy Agv ,0.6 Fu Anv } Fu Ant + min { 0.6 Fy Agv ,0.6 Fu Anv } φRn = φ ⎡⎣ Fu Ant + min { ⎦ ⎣ ⎦ Rn / Ω=
Ω Eqn. J4-5
2 ⎤ ⎡( 58 ksi )(1.88 in. ) +
2 ⎢ ⎤ ⎥ ⎡ ( 58 ksi )(1.88 in. ) + 2 ⎢ ⎥ ⎧ ⎫ ⎢ ⎥ = 0.75 0.6 36 ksi 16.9 in. ( )( ) , ⎪ ⎪ 2 ⎢ ⎥ ⎢ ⎥ min ⎧ ⎫ ⎨ ⎬ 0.6 36 16.9 in. ( 2 ksi )( ) , ⎪ ⎪ ⎢ ⎥ ⎢ ⎥ 0.6 58 ksi 11.3 in. ( ⎪ min )( ) ⎨ ⎬ ⎪⎩ ⎭ ⎣ ⎦ 2 ⎢ ⎥ 0.6 58 ksi 11.3 in. ( ⎪ )( ) ⎪⎩ ⎭ ⎣ ⎦ =
2.00

\= 356 kips > 111 kips o.k. = 237 kips > 74 kips o.k.

Use 2L4×4×s.

Check bearing and tearout

dThe clear edge distance, Lc, for the top bolts is Lc = Le − ', where Le is the distance to the
2
center of the hole. Thus,

15 16 in.) = 1.03 in. cL = 1 1 2 in. − 1 2 (

The bearing/ tearout capacity of the top bolt is as follows:

LRFD ASD
φrn = φ1.2 Lc tFu \< 2.4 dtFu 1.2 Lc tF 2.4 dtFu rn / Ω= ≤ Ω Ω
\= 0.75(1.2) (1.03 in.)( 58 in.)( 58 ksi ) 1.2 (1.03 in.)( 58 in.)( 58 ksi ) =
2.00

7 5 7 5 8 in.)( 8 in.)( 58 ksi ) ≤ 0.75 ( 2.4 )( 8 in.)( 8 in.)( 58 ksi ) 2.4 ( ≤
2.00
\= 33.6 kips \< 57.1 kips = 22.4 kips \< 38.1 kips

\= 33.6 kips/bolt = 22.4 kips/bolt

<!-- p. 380 -->

IIC-8

The bearing/ tearout capacity of each of the remaining bolts is cL = 3 in. − 1 ( 1516 in.) = 2.06 in.

LRFD ASD
φrn = φ1.2 Lc tFu \< 2.4 dtFu 1.2 Lc tF 2.4 dtFu rn / Ω= ≤ Ω Ω
\= 0.75(1.2) ( 2.06 in.)( 58 in.)( 58 ksi ) 1.2 ( 2.06 in.)( 58 in.)( 58 ksi ) =
2.00

7 5 7 5 8 in.)( 8 in.)( 58 ksi ) ≤ 0.75 ( 2.4 )( 8 in.)( 8 in.)( 58 ksi ) 2.4 ( ≤
2.00
\= 67.2 kips \< 57.1 kips = 44.8 kips \< 38.0 kips

\= 57.1 kips/bolt = 38.1 kips/bolt

Therefore the bearing/ tearout capacity of the Therefore the bearing/ tearout capacity of the
bolt group is bolt group is
22.4 kips )( 2 bolts ) + φRn = ( 33.6 kips )( 2 bolts ) + Rn / Ω= (
38.1 kips )( 8 bolts ) ( 57.1 kips)( 8 bolts) (

\= 524 kips > 111 kips o.k. = 350 kips > 74 kips o.k.

Design clip angle-to-gusset connection

The minimum weld size is x in. with top chord slope being 2 on 12, the horizontal welds are
as shown due to the square cut end. Use the average length. Then, Table J2.4

l = 15.0 in. Manual
Table 8-9

3 3 8 in. + 2 3 4 in. kl = = 3.06 in.
2

kl 3.06 in.
k = = = 0.204
l 15.0 in.

With θ = 0°, by interpolation x = 0.030 and

al + xl = 10.1 in.

⎡ ⎣10.1 in. − 0.030 ( 15.0 in.) ⎤⎦a = = 0.643
15.0 in.

By interpolation, C = 1.50

<!-- p. 381 -->

IIC-9

LRFD ASD
Ru Ω Ra Dreq = Dreq = 2 ( φCC1l ) 2 ( CC1l )

111 kips ( 2.0 )( 74 kips ) = = 2 ( 0.75)(1.50 )( 1.0 )( 15.0 in.) 2 (1.50 )(1.0 )(15.0 in.)
\= 3.29 → 4 sixteenths = 3.29 → 4 sixteenths

Use 4-in. fillet welds. Use 4-in. fillet welds.

Design chord extension plate

The chord stem extension plate thickness should match or slightly exceed that of the tee stem;
use 2-in. plate.

Check tension yielding on the Whitmore section

Lw = 4 in. + 2 ( 8 in.) tan30 ° = 13.2 in.

LRFD ASD
Fy Ag ( 36 ksi )(13.2 in.)( 12 in.) = n / Ω= φRn = φFy Ag = 0.9 ( 36 ksi )(13.2 in.)( 12 in.) R 1.67 Ω

\= 214 kips > 174 kips o.k. = 142 kips > 116 kips o.k.

Check block shear rupture of the clip angles

Assume uniform tension stress, use Ubs = 1.0
Section J4.3
2Gross area subject to shear, Agv = 2 ( 8.0 in.)( 12 in.) = 8.0 in.

Net area subject to shear, Anv = Agv = 8.0 in.2

2Net area subject to tension, Anv = ( 4 in.)( 12 in.) = 2.0 in.

LRFD ASD
Rn Fu Ant U bs ⎛ 0.6 Fy Agv Fu Anv ⎞ , Eqn. J4-5 ⎜ ⎟ Ω ⎝ Ω ⎠ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) Ω = Ω + min

2 ( 58 ksi )( 2.0 in. ) 2 = 0.75 ( 58 ksi )( 2.0 in. ) = 2.00
2 2 ⎧ ⎫ ⎫ 0.6 )( 36 ksi )( 8.0 in. ) , ⎪ 0.75 ( ⎪ ⎧ 0.6 ( 36 ksi )( 8.0 in. ) , ⎪ + min ⎨ 2 ⎪ ⎪ 2.00 ( 0.6 )( 58 ksi )( 8.0 in. ⎪⎩ 0.75 ) ⎬⎪⎭ + min ⎪ ⎨ ⎬ 2 ⎪ 0.6 ( 58 ksi )( 8.0 in. ) ⎪
⎪ ⎪ ⎩ 2.00 ⎭
\= 217 kips > 174 kips o.k. = 144 kips > 116 kips o.k.

<!-- p. 382 -->

IIC-10

The gusset width must be such that the groove weld connecting it to the stem of the tee can
transfer the tee axial force between the gusset and the top chord (note that the slight slope of
the top chord has been ignored). The required length is

LRFD ASD
Ru ΩRa Lreq = Lreq = φ ( 0.6 Fu ) t ( 0.6 Fu ) t
140 kips ( 2.00 )( 93 kips ) = = 11.8 in. = = 11.8 in. 0.75 ( 0.6 )( 58 ksi )( 0.455 in.) ( 0.6 )( 58 ksi )( 0.455 in.)

Use L = 15 in. Use L = 15 in.

The gusset depth depends upon the connection angles. From a scaled layout, the gusset must
extend 1’-0” below the tee stem.

Use PL2×12×1’-3.

<!-- p. 383 -->

IIC-11

Example II.C-2 Bracing Connection

Given:

Design the diagonal bracing connection between the W12×87 brace and the W18×106 beam
and the W14×605 column.

Brace Axial Load Tu = 675 kips Ta = 450 kips
Beam End Reaction Ru = 15 kips Ra = 10 kips
Column Axial Load Pu = 422 kips Pa = 281 kips

Use d-in. diameter ASTM A325-N bolts in standard holes and E70 electrodes.

<!-- p. 384 -->

IIC-12

Material Properties:

Brace W12×87 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Beam W18×106 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Column W14×605 ASTM A992 Fy = 50 ksi Fu = 65 ksi and 2-4
Gusset Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Brace W12×87 A=25.6 in.2 d =12.5 in. tw=0.515 in. bf=12.1 in. tf=0.810 in. Manual
Beam W18×106 d=18.7 in. tw=0.590 in. bf=11.2 in. tf=0.940 in. k=1.34 Table 1-1
Column W14×605 d=20.9 in. tw=2.60 in. bf=17.4 in. tf=4.16 in.

<!-- p. 385 -->

IIC-13

Solution:

Brace-to-gusset connection

Distribute brace force in proportion to web and flange areas.

LRFD ASD
Force in flange Force in flange

Pu b f t f ( 675 kips )(12.1 in.)( 0.810 in.) Pa b f t f ( 450 kips )(12.1 in.)( 0.810 in.)
Puf = = 2 Paf = = 2 A 25.6 in. A 25.6 in.
\= 259 kips
\= 172 kips
Force in web
Force in web
Puw = Pu − 2 Puf = 675 kips − 2 ( 259 kips )
Paw = Pa − 2 Paf = 450 kips − 2 (172 kips )
\= 157 kips
\= 106 kips

Design brace-flange-to-gusset connection.

Determine number of d-in. diameter ASTM A325-N bolts required on the brace side for single
shear.

LRFD ASD
Puf 259 kips Paf 172 kips
nmin = = = 11.9 → 12 bolts nmin = = = 11.9 → 12 bolts
φrn 21.6 kips/bolt rn / Ω 14.4 kips/bolt

On the gusset side, since these bolts are in double shear, half as many bolts will be required.
Try six rows of two bolts each through the flange, six bolts through the gusset, and 2L4x4xw
angles (A = 10.9 in.2 x = 1.27 in. ).

LRFD ASD
Check tension yielding of the angles Check tension yielding of the angles
2
F ( 36 ksi y Ag )(10.9 in. ) 2 = Rn / Ω= φRn = φFy Ag = 0.90 ( 36 ksi )(10.9 in. ) 1.67 1.67

\= 353 kips > 259 kips o.k. = 235 kips > 172 kips o.k.

Check tension rupture of the angles
x 1.27 in.
U = 1 − = 1 − = 0.92 Table D3.1
l 15 in.
8.65 in.2Ae = UAn = 0.92 ⎡⎣10.9 in.2 − 2 ( 34 in.)(1 in.) ⎤⎦ =

LRFD ASD
( 58 ksi )( 8.65 in.2 ) Fu Ae 2 = Rn / Ω= φRn = φFu Ae = 0.75 ( 58 ksi )( 8.65 in. ) 2.00 Ω

\= 376 kips > 259 kips o.k. = 251 kips > 172 kips o.k.

<!-- p. 386 -->

IIC-14

Check block shear rupture of the angles.

Use n = 6, Lev = 12 in., and Leh = 12 in.

LRFD ASD
⎛ 0.6 Fy Agv Rn Fu Ant U bs Fu Anv ⎞ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) , = + min ⎜ ⎟ Ω Ω ⎝ Ω Ω ⎠

Tension Rupture Component Tension Rupture Component Manual
Table 9-3a
3 3 φ Fu Ant = ( 43.5 kips/in.)( 4 in.)( 2 ) 4 in.)( 2 ) Fu Ant / Ω= ( 29.0 kips/in.)(

Manual Shear Yielding Component Shear Yielding Component
Table 9-3b

3 3 φ 0.6 Fy Agv = ( 267 kips/in.)( 4 in.)( 2 ) 4 in.)( 2 ) 0.6 Fy Agv / Ω= (178 kips/in.)(

Shear Rupture Component Shear Rupture Component Manual
Table 9-3c
3 3 φ 0.6 Fu Anv = ( 287 kips/in.)( 4 in.)( 2 ) 4 in.)( 2 ) 0.6 Fu Anv / Ω= (191 kips/in.)(

φ Rn = ( 43.5 kips + 267 kips )( 34 in.)( 2 ) Rn / Ω= ( 29.0 kips + 178 kips )( 34 in.)( 2 ) Eqn. J4-5

\= 465 kips > 259 kips o.k. = 310 kips > 172 kips o.k.

Similarly, the block shear rupture strength of the brace flange is o.k.

Design brace-web-to-gusset connection

Determine number of d-in. diameter ASTM A325-N bolts required on the brace side (double
shear) for shear.

LRFD ASD
Puw 157 kips Paw 106 kips Manual Table
nmin = = = 3.63 → 4 bolts nmin = = = 3.67 → 4 bolts 7-1 φrn 43.3 kips/bolt rn /Ω 28.9 kips/bolt

On the gusset side, the same number of bolts are required. Try two rows of two bolts and two
PLa×9.

LRFD ASD
Check tension yielding of the plates Check tension yielding of the plates

( 36 ksi )( 2 )( 38 in.)( 9 in.)
n / Ω= Fy Ag / Ω= φ Rn = φ Fy Ag = 0.90 ( 36 ksi )( 2 )( 38 in.)( 9 in.) R 1.67
Eqn. D2-1
\= 219 kips > 157 kips o.k. = 146 kips > 106 kips o.k.

<!-- p. 387 -->

IIC-15

Check tension rupture of the plates

Take Ae as the lesser of An and 0.85Ag,
Section D3.2
3 3 2 User Note = min = 5.25 in.Ae = min ( An ,0.85 Ag ) { ( 8 ,0.85 ( 2 )( 8 in.)( 9 in.) } in.) ⎡⎣ 2 ( 9 in.) − 4 (1 in.) ⎤⎦

LRFD ASD
( 58 ksi )( 5.25 in.2 ) 2 Eqn. D2-2 Rn / Ω= Fu Ae / Ω= φRn = φFu Ae = 0.75 ( 58 ksi )( 5.25 in. ) 2.00

\= 228 kips > 157 kips o.k. =152 kips > 106 kips o.k.

Check block shear rupture of the plates (outer blocks).

Use n = 2, Lev = 12 in., and Leh = 12 in. The calculations here are done in the same manner
as those for the angles. Thus,

LRFD ASD
⎛ 0.6 Fy Agv Rn Fu Ant U bs Fu Anv ⎞ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φFu Anv ) , = + min ⎜ ⎟ Ω Ω ⎝ Ω Ω ⎠

Tension Rupture Component Tension Rupture Component Manual
Table 9-3a
3 3 φFu Ant = ( 43.5 kips/in.)( 4 in.)( 2 ) 4 in.)( 2 ) Fu Ant / Ω= ( 29.0 kips/in.)(

Manual Shear Yielding Component Shear Yielding Component
Table 9-3b

3 3 φ 0.6 Fy Agv = ( 72.9 kips/in.)( 4 in.)( 2 ) 4 in.)( 2 ) 0.6 Fy Agv / Ω= ( 48.6 kips/in.)(
Manual
Shear Rupture Component Shear Rupture Component Table 9-3c

3 φ 0.6 Fu Anv = ( 78.3 kips/in.)( 4 in.)( 2 ) 0.6 Fu Anv / Ω= ( 52.2 kips/in.)( 34 in.)( 2 )

3 Eqn. J4-5 φ Rn = ( 43.5 kips + 72.9 kips )( 4 in.)( 2 ) Rn / Ω= ( 29.0 kips + 48.6 kips )( 34 in.)( 2 )

\= 175 kips > 157 kips o.k. = 116 kips > 106 kips o.k.

Similarly, the block shear rupture strength of the interior blocks of the brace-web plates and
the brace web are o.k.

Check block shear rupture of the brace web.

Use n = 2, Lev = 12 in., and Leh = 3 in.

<!-- p. 388 -->

IIC-16

LRFD ASD
Rn Fu Ant U bs ⎛ 0.6 Fy Agv Fu Anv ⎞ = + min , ⎜ ⎟ ⎝ Ω Ω ⎠ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φFu Anv ) Ω Ω

Tension Rupture Component Tension Rupture Component Manual
Table 9-3a
φ Fu Ant = (122 kips/in.)( 0.515 in.)( 2 ) Fu Ant / Ω= ( 81.3 kips/in.)( 0.515 in.)( 2 )

Shear Yielding Component Shear Yielding Component
Manual
Table 9-3b φ 0.6 Fy Agv = (101 kips/in.)( 0.515 in.)( 2 ) 0.6 Fy Agv / Ω= ( 67.5 kips/in.)( 0.515 in.)( 2 )

Shear Rupture Component Shear Rupture Component
Manual
φ 0.6 Fu Anv = ( 87.8 kips/in.)( 0.515 in.)( 2 ) 0.6 Fu Anv / Ω= ( 58.5 kips/in.)( 0.515 in.)( 2 ) Table 9-3c

Eqn. J4-5 φ Rn = (122 kips + 101 kips )( 0.515 in.)( 2 ) Rn / Ω= ( 81.3 kips + 58.5 kips )( 0.515 in.)( 2 )
\= 216 kips > 157 kips o.k. = 144 kips > 106 kips o.k.

LRFD ASD
Check tension yielding of the brace Check tension yielding of the brace

2 ( 50 ksi )( 25.6 in. ) 2 Eqn. D2-1 Rn / Ω= Fy Ag / Ω= φRn = φFy Ag = 0.90 ( 50 ksi )( 25.6 in. ) 1.67

\= 1150 kips > 675 kips o.k. = 766 kips > 450 kips o.k.

Check tension rupture of the brace

Take Ae as An,

2 1 in.) = 21.3 in.Ae = An = 25.6 in.2 −⎡⎣ 4 ( 0.810 in.) + 2 ( 0.515 in.) ⎤⎦ (

LRFD ASD
( 65 ksi )( 21.3 in.2 ) 2 Eqn. D2-2 Rn / Ω= Fu Ae / Ω= φRn = φFu Ae = 0.75 ( 65 ksi )( 21.3 in. ) 2.00

\= 1040 kips > 675 kips o.k. = 692 kips > 450 kips o.k.

Design the gusset

From edge distance, spacing, and thickness requirements of the angles and web plates, try
PL w.

Check block shear rupture for the force transmitted through web. Use n = 2, Lev = 12 in. and
Leh = 3 in.

LRFD ASD
⎛ 0.6 Fy Agv Rn Fu Ant U bs Fu Anv ⎞ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φFu Anv ) , = + min ⎜ ⎟ Ω Ω ⎝ Ω Ω ⎠

<!-- p. 389 -->

IIC-17

Tension Rupture Component Tension Rupture Component
Manual

3 4 in.)( 2 ) Table 9-3a φFu Ant = (109 kips/in.)( 34 in.)( 2 ) Fu Ant / Ω= ( 72.5 kips/in.)(

Shear Yielding Component Shear Yielding Component
Manual
Table 9-3b
3 φ 0.6 Fy Agv = ( 72.9 kips/in.)( 4 in.)( 2 ) 0.6 Fy Agv / Ω= ( 48.6 kips/in.)( 34 in.)( 2 )

Shear Rupture Component Shear Rupture Component
Manual
3 3 4 in.)( 2 ) Table 9-4 φ 0.6 Fu Anv = ( 78.3 kips/in.)( 4 in.)( 2 ) 0.6 Fu Anv / Ω= ( 52.2 kips/in.)(

3 3 4 in.)( 2 ) φ Rn = (109 kips + 72.9 kips )( 4 in.)( 2 ) Rn / Ω= ( 72.5 kips + 48.6 kips ) (

\= 273 kips > 157 kips o.k. = 182 kips > 106 kips o.k. Eqn. J4-5

Check block shear rupture for total brace force

With Agv = 24.8 in.2, Anv = 16.5 in.2, and Ant = 12.4 in.2. Thus,

LRFD ASD
Rn Fu Ant U bs ⎛ 0.6 Fy Agv Fu Anv ⎞ , Section J4.3 ⎜ ⎟ Ω ⎝ Ω ⎠ φRn = φFu Ant U bs + min ( φ 0.6 Fy Agv , φFu Anv ) Ω = Ω + min

Tension Rupture Component Tension Rupture Component
2 58 ksi )(12.4 in. ) Fu Ant ( 2 =
2.00 φFu Ant = 0.75 ( 58 ksi )(12.4 in. ) Ω
\= 539 kips = 360 kips

Shear Yielding Component Shear Yielding Component
2 0.6 Fy Agv ( 0.6 )( 36 ksi )( 24.8 in. ) 2 = φ 0.6 Fy Agv = 0.75 ( 0.6 )( 36 ksi )( 24.8 in. ) Ω 2.00
\= 402 kips = 268 kips

Shear Rupture Component Shear Rupture Component
2 0.6 )( 58 ksi )(16.5 in. ) 2 0.6 Fu Anv ( = φ 0.6 Fu Anv = 0.75 ( 0.6 )( 58 ksi )(16.5 in. ) Ω 2.00
\= 431 kips = 287 kips
φ Rn = 539 kips + min ( 402 kips,431 kips ) Rn / Ω= 360 kips + min ( 268 kips,287 kips )

\= 941 kips > 675 kips o.k. = 628 kips > 450 kips o.k.

<!-- p. 390 -->

IIC-18

Check tension yielding on the Whitmore section of the gusset.

The Whitmore section, as illustrated with dashed lines in Figure (b), is 34.8 in. long; 30.9 in.
occurs in the gusset and 3.90 in. occurs in the beam web. Thus,

LRFD ASD
φRn = φFy Aw Rn / Ω= Fy Aw / Ω
Eqn. J4-1
⎡ ( 36 ksi )( 30.9 in.)( 34 in.) + ⎤ ⎡ ( 36 ksi )( 30.9 in.)( 34 in.) + ⎤
\= 0.90 ⎢ ⎥ ⎢ ⎥
50 ksi )( 3.90 in.)( 0.590 in.) ⎥⎦ ⎢⎣ ( 50 ksi )( 3.90 in.)( 0.590 in.) ⎥⎦ ⎢⎣ ( =
1.67

\= 854 kips > 675 kips o.k. = 568 kips > 450 kips o.k.

Note: The beam web thickness is used, conservatively ignoring the larger thickness in the
beam-flange and the flange-to-web fillet area.

Check bearing strength of the angles, brace flange and gusset

The bearing strength per bolt is given by Specification Section J3.10 as:

rn = 1.2 Lc tFu ≤ 2.4 dtFu
Eqn. J3-6a
Because of the edge distance requirement, the angles, brace flange, and gusset, must be
considered simultaneously. The angles have edge bolts and interior bolts. For an edge bolt,

15 1 2 )( 16 in.) = 1.03 in. cL = 1 1 2 in. − (

LRFD ASD
1.2 Lc tF 2.4 dtFu ≤ rn / Ω= φrn = φ1.2 Lc tFu \< 2.4 dtFu Ω Ω Eqn. J3-6a
1.2 (1.03 in.)( 34 in.)( 58 ksi ) 3 = = 0.75(1.2) ( 1.03 in.)( 4 in.)( 58 ksi ) 2.00
7 3 7 3 ≤ 2.4(0.75) ( 8 in.)( 4 in.)( 58 ksi ) 2.4 ( 8 in.)( 4 in.)( 58 ksi ) ≤
2.00
\= 40.4 kips \< 68.6 kips = 26.9 kips \< 45.7 kips

\= 40.4 kips/bolt = 26.9 kips/bolt

For an interior bolt,

cL = 3 in. − (1)( 1516 in.) = 2.06 in.

<!-- p. 391 -->

IIC-19

LRFD ASD
φrn = φ1.2 Lc tFu \< 2.4 dtFu 1.2 Lc tF 2.4 dtFu
rn / Ω= ≤ Eqn. J3-6a Ω Ω

3 = 0.75(1.2) ( 2.06 in.)( 4 in.)( 58 ksi ) 1.2 ( 2.06 in.)( 34 in.)( 58 ksi ) =
7 3 ≤ 0.75(2.4) ( 8 in.)( 4 in.)( 58 ksi ) 2.00
7 3 2.4 ( 8 in.)( 4 in.)( 58 ksi ) ≤
2.00
\= 81.0 kips \< 68.6 kips = 54 kips \< 45.7 kips
\= 68.6 kips/bolt = 45.7 kips/bolt

Note: The above strengths are per angle.

The gusset plate bolt strengths are the same as the angle bolt strengths since the gusset plate is
the same thickness and material, and has the same edge distance. Thus,

LRFD ASD
For an edge bolt, φnr = 40.4 kips/bolt For an edge bolt, nr / Ω= 26.9 kips/bolt

For an interior bolt, φrn = 68.6 kips/bolt For an interior bolt, rn/Ω = 45.7 kips/bolt

For the brace, edge bolt Lc = 1.03 in. and interior bolt Lc = 2.06 in.

LRFD ASD
Brace edge bolt, Brace edge bolt,

1.2 Lc tF 2.4 dtFu ≤ rn / Ω= φrn = φ1.2 Lc tFu \< 2.4 dtFu Ω Ω Eqn. J3-6a
1.2 (1.03 in.)( 0.810 in.)( 65 ksi ) = = 0.75(1.2) (1.03 in.)( 0.810 in.)( 65 ksi ) 2.00
≤ 0.75(2.4) ( 78 in.)( 0.810 in.)( 65 ksi ) 2.4 ( 78 in.)( 0.810 in.)( 65 ksi ) ≤
2.00
\= 48.9 kips \< 83.3 kips = 32.6 kips \< 55.5 kips

\= 48.9 kips/bolt = 32.6 kips/bolt

LRFD ASD
Brace interior bolt, Brace interior bolt,
1.2 Lc tF 2.4 dtFu ≤ rn / Ω= φrn = φ1.2 Lc tFu \< 2.4 dtFu Ω Ω Eqn. J3-6a
1.2 ( 2.06 in.)( 0.810 in.)( 65 ksi ) = = 0.75(1.2) ( 2.06 in.)( 0.810 in.)( 65 ksi ) 2.00
≤ 0.75(2.4) ( 78 in.)( 0.810 in.)( 65 ksi ) 2.4 ( 78 in.)( 0.810 in.)( 65 ksi ) ≤
2.00
\= 97.8 kips \< 83.2 kips = 65.2 kips \< 55.5 kips

\= 83.2 kips/bolt = 55.5 kips/bolt

<!-- p. 392 -->

IIC-20

The bearing strength of the flange connection can now be calculated. Summarizing the various
strengths:

LRFD ASD

Member Edge Interior Member Edge Interior
Angle (2) 80.8 kips 137 kips Angle (2) 53.8 kips 91.4 kips
Gusset 40.4 kips 68.6 kips Gusset 26.9 kips 45.7 kips
Brace 48.9 kips 83.2 kips Brace 32.6 kips 55.5 kips

From the above table, From the above table,

φRn = (1 bolt )( 40.4 kips/bolt ) Rn / Ω= (1 bolt )( 26.9 kips/bolt )
\+ ( 5 bolts )( 68.6 kips/bolt ) + ( 5 bolts )( 45.7 kips/bolt )

\= 383 kips > 259 kips o.k. = 255 kips > 172 kips o.k.

Note: The gusset edge bolt bearing strength is less than the bolt double shear strength; the bolt
shear strength must be re-checked. Thus, the revised bolt shear strength is

LRFD ASD
φRn = (1 bolt )( 40.4 kips/bolt ) Rn / Ω= (1 bolt )( 26.9 kips/bolt )
\+ ( 5 bolts )( 43.3 kips/bolt ) + ( 5 bolts )( 28.9 kips/bolt )

\= 257 kips \< 259 kips o.k. = 171 kips \< 172 kips o.k.

Note: When the brace force is compression gusset buckling would have to be checked; refer to
the comments at the end of this example.

Distribution of the brace force to beam and column

From the members and frame geometry

d beam 18.7 in. Manual
eb = = = 9.35 in. Part 13 2 2

d column 20.9 in.ec = = = 10.5 in.
2 2

12
tan θ = = 1.25
9 916

and eb tan θ − ec = ( 9.35 in.)(1.25) − (10.5 in.) = 1.19 in.

Try gusset PL w × 42 in. horizontally × 33 in. vertically (several intermediate gusset
dimensions were inadequate). With connection centroids at the midpoint of the gusset edges

42 in. 1 1α = + 2 in. = 21 2 in.
2

where 2 in. is allowed for the setback between the gusset and the column, and

<!-- p. 393 -->

IIC-21

33 in.
β = = 16 12 in.
2

Choosing β = β , the α required for the uniform forces is

α = eb tan θ − ec + β tan θ = 1.19 + (16.5 in.)(1.25) = 21.8 in.

The resulting eccentricity is α −α , where

α −α = 21.8 in. − 21.5 in. = 0.3 in.

Since slight eccentricity is negligible. Use α = 21.8 in. and β = 16.5 in.

Calculate gusset interface forces

r = ( α + ec ) 2 + ( β + eb ) 2 = ( 21.8 in. + 10.5) 2 + (16.5 in. + 9.35 in.) 2 = 41.4 in.

On the gusset-to-column connection

LRFD ASD
ec Pu (10 12 in.)( 675 kips ) ec Pa (10 12 in.)( 450 kips ) H uc = = = 171 kips H ac = = = 114 kips
r 41.4 in. r 41.4 in.

βPu (16 12 in.)( 675 kips ) βPa (16 12 in.)( 450 kips ) Vuc = = = 269 kips Vac = = = 179 kips
r 41.4 in. r 41.4 in.

On the gusset-to-beam connection

LRFD ASD
αPu ( 21.8 in.)( 675 kips ) αPa ( 21.8 in.)( 450 kips ) H ub = = = 355 kips H ab = = = 237 kips
r 41.4 in. r 41.4 in.

eb Pa ( 9.35 in.)( 675 kips ) eb Pa ( 9.35 in.)( 450 kips ) Vub = = = 153 kips Vab = = = 102 kips
r 41.4 in. r 41.4 in.

Design gusset-to-column connection

The forces involved are Vuc = 269 kips (Vac = 179 kips ASD) shear and Huc = 171 kips (Hac =
114 kips ASD) tension.

Try 2L4×4×2×2’-6 welded to the gusset and bolted with 10 rows of d in. diameter A325-N
bolts in standard holes to the column flange.

Calculate the required tensile strength per bolt

LRFD ASD
H uc 171 kips H ac 114 kips Tu = = = 8.55 kips/bolt Ta = = = 5.70 kips/bolt
n 20 bolts n 20 bolts

<!-- p. 394 -->

IIC-22

Check design strength of bolts for tension- Check allowable strength of bolts for
shear interaction. tension-shear interaction.

Vuc 269 kips Vac 179 kips Manual
ruv = = = 13.5 kips/bolt rav = = = 8.95 kips/bolt Table 7-1 n 20 bolts n 20 bolts

13.5 kips/bolt \< 21.6 kips/bolt o.k. 8.95 kips/bolt \< 14.4 kips/bolt o.k.

ruv 13.5 kips rav 8.95 kips
f uv = = 2 = 22.5 ksi f av = = 2 = 14.9 ksi
Ab 0.6013 in. Ab 0.6013 in.

Fnt Fnt Ω
Fnt ' = 1.3 Fnt − f uv ≤ Fnt Fnt ' = 1.3 Fnt − f av ≤ Fnt Eqn. J3-3a/b φFnv Fnv
and
( 2.00 ) = 1.3 ( 90 ksi ) − 90 ksi ( 22.5 ksi ) = 1.3 ( 90 ksi ) − 90 ksi (14.9 ksi ) Table J3.2 0.75 ( 48 ksi ) 48 ksi

\= 60.8 ksi \< 90 ksi = 61.1 ksi \< 90 ksi

Use Fnt’ = 60.8 ksi Use Fnt’ = 61.1 ksi

2 61.1 ksi )( 0.6013 in. ) Fnt ' Ab (
2 = a = Bu = φFnt ' Ab = 0.75 ( 60.8 ksi )( 0.6013 in. ) B 2.00 Ω

\= 27.4 kips/bolt > 8.55 kips/bolt o.k. = 18.4 kips/bolt > 5.70 kips/bolt o.k.

Check bearing strength at bolt holes

The bearing strength per bolt is

LRFD ASD
1.2 Lc tF 2.4 dtFu ≤ rn / Ω= φrn = φ1.2 Lc tFu \< 2.4 dtFu Ω Ω Eqn. J3-6a
1.2 (1.03 in.)( 12 in.)( 58 ksi ) = = 0.75(1.2) (1.03 in.)( 12 in.)( 58 ksi ) 2.00
7 1 7 1 ≤ 0.75(2.4) ( 8 in.)( 2 in.)( 58 ksi ) 2.4 ( 8 in.)( 2 in.)( 58 ksi ) ≤
2.00
\= 26.9 kips \< 45.7 kips = 17.9 kips \< 30.5 kips

\= 26.9 kips/bolt = 17.9 kips/bolt

Since this edge bolt value exceeds the single- Since this edge bolt value exceeds the single-
shear strength of the bolts 21.6 kips, and the shear strength of the bolts 14.4 kips, and the
actual shear per bolt of 13.5 kips, bearing actual shear per bolt of 8.95 kips, bearing
strength is o.k. strength is o.k

<!-- p. 395 -->

IIC-23

Check prying action
t 1 12 in. 1 Manualb = g − = 2 2 in. − = 2 4 in. Part 9 2 2

Note: 14 in. entering and tightening clearance is accommodated, o.k.

a = 4 in. − g = 4 in. − 2 1 2 in. = 1 1 2 in.

Since a =12 in. is less than 1.25b = 2.81 in., use a = 12 in.

d 78 in.b ' = b − = 2 14 in. − = 1.81 in.
2 2

d 78 in.a ' = a + = 1 12 in. + = 1.94 in.
2 2

b ' 1.81 in.
ρ = = = 0.935
a ' 1.94 in.

LRFD ASD
1 ⎛ Bu ⎞ 1 ⎛ 27.4 kips/bolt ⎞ 1 ⎛ Ba ⎞ 1 ⎛ 18.4 kips/bolt ⎞ β = − 1 = − 1 β = − 1 = − 1 ⎜ ⎟ ⎜ ⎟ ⎜ ⎟ ⎜ ⎟ ρ ⎝ Tu ⎠ 0.935 ⎝ 8.55 kips/bolt ⎠ ρ ⎝ Ta ⎠ 0.935 ⎝ 5.70 kips/bolt ⎠

\= 2.36 = 2.38

Since β > 1, set α’ = 1.0

d ' 1516 in.δ = 1 − = 1 − = 0.688
p 3 in.
LRFD ASD
4.44Tu b ' 6.66Ta b ' t req = t req = pFu (1 + δα ') pFu (1 + δα ')

4.44 ( 8.55 kips/bolt )(1.81 in.) 6.66 ( 5.70 kips/bolt )(1.81 in.) = =
( 3 in.)( 58 ksi ) ⎡+⎣ 1 0.688 (1.0 ) ⎤⎦ ( 3 in.)( 58 ksi ) ⎡+⎣ 1 0.688 (1.0 ) ⎤⎦

\= 0.484 in. = 0.484 in.

Since t = 2 in. > 0.484 in., angles are o.k. Since t = 2 in. > 0.484 in., angles are o.k.

<!-- p. 396 -->

IIC-24

Design welds

Try fillet welds around the perimeter (three sides) of both angles.

LRFD ASD
Puc = H uc 2 + Vuc 2 Pac = H ac 2 + Vac 2

\= (171 kips ) 2 + ( 269 kips ) 2 = 319 kips = (114 kips ) 2 + (179 kips ) 2 = 212 kips

\-1 ⎛ H uc ⎞ -1 ⎛ 171 kips ⎞ -1 ⎛ H ac ⎞ -1 ⎛ 114 kips ⎞ θ = tan = tan = 32.4° θ = tan = tan = 32.5° ⎜ ⎟ ⎜ ⎟ ⎜ ⎟ ⎜ ⎟ ⎝ Vuc ⎠ ⎝ 269 kips ⎠ ⎝ Vac ⎠ ⎝ 179 kips ⎠

From Manual Table 8-8 with θ = 300,

l = 30 in., kl = 32 in., therefore k = 0.117

By interpolation

x = 0.011, xl = 0.011(30 in.) = 0.33 in.

al = 4 in. − xl = 4 in. − 0.33 in. = 3.67 in.
a = 0.122

By interpolation

C = 2.60

LRFD ASD
Puc Pac Ω Dreq = Dreq =
φCC1l CC1l
319 kips ( 212 kips )( 2.00 ) = =
0.75 ( 2.60 )(1.0 )( 2 welds )( 30 in.) ( 2.60)(1.0 )( 2 welds )( 30 in.)
\= 2.73 → 3 sixteenths = 2.72 → 3 sixteenths

From Specification Table J2.4, minimum weld size is 4 in. Use 4-in. fillet welds.

Check gusset thickness against weld size required for strength
6.19 D 6.19 ( 2.73 sixteenths )
For two fillet welds, t min = = = 0.291 in. \< 34 in. o.k.
Fu 58 ksi

<!-- p. 397 -->

IIC-25

Check strength of angles

Check shear yielding (due to Vuc or Vac)

LRFD ASD
0.60 Fy Ag φRn = φ ( 0.60 Fy Ag ) Rn / Ω= Eqn. J4-3 Ω
0.60 ( 36 ksi )( 2 )( 30 in.)( 12 in.) = 1.00 ⎡ ⎣ 0.60 ( 36 ksi )( 2 )( 30 in.)( 12 in.) ⎤⎦ =
1.50
\= 648 kips > 269 kips o.k.
\= 432 kips > 179 kips o.k.

Similarly, shear yielding of the angles due to Huc is not critical.

Check shear rupture
LRFD ASD
φ Rn = φ ( 0.60 Fu Anv ) 0.60 Fu Anv
Rn / Ω= Eqn. J4-4 Ω
\= 0.75(0.60) ( 58 ksi )( 12 in.) 0.60 ( 58 ksi )( 12 in.) ⎡⎣ ( 2 )( 30 in.) − 20 (1 in.) ⎤⎦ =
× ⎡ ⎣ ( 2 )( 30 in.) − 20 (1 in.) ⎤⎦ 2.00

\= 348 kips > 179 kips o.k.
\= 522 kips > 269 kips
o.k.

Block shear rupture

Use n = 10, Lev = 12 in. and Leh = 12 in. Thus,

LRFD ASD
⎛ 0.6 Fy Agv Rn Fu Ant U bs Fu Anv ⎞ φRn = φ Fu Ant U bs + min ( φ 0.6 Fy Agv , φ Fu Anv ) , = + min ⎜ ⎟ Ω Ω ⎝ Ω Ω ⎠

Tension Rupture Component Tension Rupture Component Manual
Table 9-3a
φ Fu Ant = ( 43.5 kips/in.)( 12 in.)( 2 ) Fu Ant / Ω= ( 29.0 kips/in.)( 12 in.)( 2 )

Manual Shear Yielding Component Shear Yielding Component
Table 9-3b
φ 0.6 Fy Agv = ( 462 kips/in.)( 12 in.)( 2 ) 0.6 Fy Agv / Ω= ( 308 kips/in.)( 12 in.)( 2 )
Manual
Shear Rupture Component Shear Rupture Component Table 9-3c
φ 0.6 Fu Anv = ( 496 kips/in.)( 12 in.)( 2 ) 0.6 Fu Anv / Ω= ( 331 kips/in.)( 12 in.)( 2 )

Eqn. J4-5 φ Rn = ( 43.5 kips + 462 kips )( 12 in.)( 2 ) Rn / Ω= ( 29.0 kips + 308 kips )( 12 in.)( 2)

\= 506 kips > 269 kips o.k. = 337 kips > 179 kips o.k.

<!-- p. 398 -->

IIC-26

Check column flange

By inspection, the 4.16 in. thick column flange has adequate flexural strength, stiffness, and
bearing strength.

Design the gusset-to-beam connection

The forces involved are

LRFD ASD
Hub = 355 kips Hab = 237 kips
Vub = 153 kips Vab = 102 kips

Because one edge of the gusset is welded and the other is bolted, the distribution of force on
the welded edge is uneven. To account for this, the required strength of the gusset edge is
amplified by a factor of 1.25 to allow for the redistribution of forces on the weld.

The stresses on the gusset plate at the welded edge are as follows:

LRFD ASD
Vub Vab Fy Eqn. J4-6 f ua = ≤φFy f aa = tl tl ≤Ω

153 kips 102 kips 36 ksi = ≤ 0.90 ( 36 ksi ) = ≤ ( 34 in.)( 42 in.) ( 34 in.)( 42 in.) 1.67

\= 4.86 ksi \< 32.4 ksi o.k. = 3.24 ksi \< 21.6 ksi o.k.

H ub H ab 0.60 Fy f uv = ≤φ ( 0.60 Fy ) f av = ≤ Eqn. J4-3 tl tl Ω

355 kips ( 36 ksi ) = ≤ 1.00 ( 0.60 )( 36 ksi ) = 237 kips ≤ 0.60 ( 34 in.)( 42 in.) ( 34 in.)( 42 in.) 1.50

\= 11.3 ksi \< 21.6 ksi o.k. = 7.52 ksi \< 14.4 ksi o.k.

LRFD ASD
\-1 ⎛ Vub ⎞ -1 ⎛ 153 kips ⎞ -1 ⎛ Vab ⎞ -1 ⎛ 102 kips ⎞ Section J2.4 θ = tan = tan = 23.3° θ = tan = tan = 23.3 ° ⎜ ⎟ ⎜ ⎟ ⎜ ⎟ ⎜ ⎟ ⎝ H ub ⎠ ⎝ 355 kips ⎠ ⎝ H ab ⎠ ⎝ 237 kips ⎠

µ = 1.0 + 0.5sin 1.5 θ = 1.0 + 0.5sin 1.5 ( 23.3° ) = 1.12 Eqn. J2-5

The weld strength per z in. is as follows:

LRFD ASD
φ wr = (1.392 kips/in.)(1.12 ) = 1.56 kips/in. wr / Ω= ( 0.928 kips/in.)(1.12 ) = 1.04 kips/in.

The peak weld stress is given by The peak weld stress is given by

⎛⎞t 2 2 ⎛⎞t 2 2 f u peak = ⎜⎟ ( f ua + f ub ) + f uv f a peak = ⎜⎟ ( f aa + f ab ) + f av ⎝⎠2 ⎝⎠2

<!-- p. 399 -->

IIC-27

⎛ 3 4 in. ⎞ 2 2 ⎛ 3 4 in. ⎞ 2 2 = ⎜ ⎟ ( 4.86 ksi + 0 ksi ) + (11.3 ksi ) = ⎜ ⎟ ( 3.24 ksi + 0 ksi ) + ( 7.52 ksi ) ⎝ 2 ⎠ ⎝ 2 ⎠

\= 4.61 kips/in. = 3.07 kips/in.

The average stress is The average stress is

⎡ ( f ua − f ub ) 2 + f uv 2 ⎤ ⎡ ( f aa − f ab ) 2 + f av 2 ⎤ ⎢ ⎥ ⎢ ⎥ t t
⎢ 2 2 ⎥ ⎢ 2 2 ⎥ + ( f aa + f ab ) + f av ⎥⎦ ⎢⎣ + ( f ua + f ub ) + f uv ⎥⎦ ⎢⎣ f u ave = f a ave =
4 4

Since fub = 0 ksi (there is no moment on the Since fab = 0 ksi (there is no moment on the
edge) fu ave = fu peak = 4.61 kips/in. edge) fa ave = fa peak = 4.61 kips/in.
The design weld stress is The design weld stress is
f u weld = max { f u peak , 1.25 f u ave } f a weld = max { f a peak , 1.25 f a ave }

\= max { 4.61 kips/in., 1.25 ( 4.61 kips/in.) } = max { 3.07 kips/in., 1.25 ( 3.07 kips/in.) }

\= 5.76 kips/in. = 3.84 kips/in.

The required weld size is The required weld size is

f u weld Ωf a weldDreq = Dreq =
φrw rw

5.76 kips/in. 3.84 kips/in.
\= = 3.69 → 4 sixteenths = = 3.69 → 4 sixteenths
1.56 kips/in. 1.04 kips/in.

Minimum weld size is c in. Use a c-in. Minimum weld size is c in. Use a c-in.
fillet weld. fillet weld.

LRFD ASD
Check local web yielding of the beam Check local web yielding of the beam

φRn = φ ( N + 2.5 k ) Fyw t w ( N + 2.5k ) Fyw t w
Rn / Ω= Ω Eqn. J10-3
\= 1.0 ⎡ 50 ksi )( 0.590 in.) ⎣ 42 in. + 2.5 ( 1.34 in.) ⎤⎦ (
⎡ 50 ksi )( 0.590 in.) ⎣ 42 in. + 2.5 ( 1.34 in.) ⎤⎦ ( =
\= 1340 kips > 153 kips o.k. 1.50

\= 892 kips > 102 kips o.k.

<!-- p. 400 -->

IIC-28

Design beam-to-column connection

Since the brace may be in tension or compression, the required strength the beam-to-column
connection is as follows. The required shear strength is

LRFD ASD
Rub ± Vub = 15 kips + 153 kips = 168 kips Rab ± Vab = 10 kips + 102 kips = 112 kips

and the required axial strength is and the required axial strength is

Aub ± ( H u − H ub ) = 0 ± 171 kips = 171 kips Aab ± ( H a − H ab ) = 0 ± 114 kips = 114 kips

Try 2L8×6×w×1’-22 (leg gage = 2w in.) welded to the beam web, bolted with five rows of d
in. diameter A325-N bolts in standard holes to the column flange.

Calculate tensile force per bolt
LRFD ASD
Aub ± ( H u − H ub ) 171 kips Aab ± ( H a − H ab ) 114 kips
Tu = = Ta = =
n 10 bolts n 10 bolts

\= 17.1 kips/bolt = 11.4 kips/bolt

Check available strength of bolts for tension-shear interaction
LRFD ASD
Rub ± Vub 168 kips Rab ± Vab 112 kips Vu = = Va = =
n 10 bolts n 10 bolts

\= 16.8 kips/bolt = 11.2 kips/bolt

Vu 16.8 kips/bolt Va 11.2 kips/bolt
f uv = = 2 = 27.4 ksi f av = = 2 = 18.6 ksi
Ab 0.6013 in. Ab 0.6013 in.

Fnt Ω Fnt Table J3.2,
Fnt ' = 1.3 Fnt − f uv ≤ Fnt Fnt ' = 1.3 Fnt − f av ≤ Fnt Eqns. J3-3a φFnv Fnv
and J3-3b
90 ksi 2.00 ( 90 ksi ) = 1.3 ( 90 ksi ) − ( 27.4 ksi ) \< 90 ksi = 1.3 ( 90 ksi ) − (18.6 ksi ) \< 90 ksi 0.75 ( 48 ksi ) 48 ksi
\= 48.5 ksi \< 90 ksi o.k. = 47.2 ksi \< 90 ksi o.k.

Use Fnt’ = 48.5 ksi. Use Fnt’ = 47.2 ksi.

2 ( 48.5 ksi )( 0.6013 in. ) 2 Fnt ' Ab Ba = = Bu = φFnt ' Ab = 0.75 ( 48.5 ksi )( 0.6013 in. ) Ω 2.00

\= 21.9 kips/bolt > 17.1 kips/bolt o.k. = 14.2 kips/bolt > 11.4 kips/bolt o.k.

<!-- p. 401 -->

IIC-29

LRFD ASD
Check bearing strength Check bearing strength
1.2 Lc tF 2.4 dtFu ≤ rn / Ω= φrn = φ1.2 Lc tFu \< 2.4 dtFu Ω Ω Eqn. J3-6a
1.2 (1.03 in.)( 34 in.)( 58 ksi ) 3 = = 0.75(1.2) (1.03 in.)( 4 in.)( 58 ksi ) 2.00
7 3 7 3 ≤ 0.75(2.4) ( 8 in.)( 4 in.)( 58 ksi ) 2.4 ( 8 in.)( 4 in.)( 58 ksi ) ≤
2.00
\= 26.9 kips \< 45.7 kips
\= 40.4 kips \< 68.6 kips
\= 40.4 kips/bolt = 26.9 kips/bolt

Since this edge bolt value exceeds the single- Since this edge bolt value exceeds the single-
shear strength of the bolts 21.6 kips, bearing shear strength of the bolts 14.4 kips, bearing
does not control. o.k. does not control. o.k.

Check prying action

t 3 0.75 in. 3b = g − = 2 4 in. − = 2 8 in.
2 2

Note: 14 in. entering and tightening clearance is accommodated, o.k.

a = 6 in. − g = 6 in. − 2 3 4 = 3 1 4 in.

Since a = 34 in. exceeds 1.25b = 2.97 in., use a = 2.97 in. for calculation purposes.

d 78 in.
b ' = b − = 2 38 in. − = 1.94 in.
2 2

d 78 in.a ' = a + = 2.97 in. + = 3.41 in.
2 2

b ' 1.94 in.
ρ = = = 0.569
a ' 3.41 in.

14 12 in. p = = 2.90 in./bolt
5 bolts

d ' 1516 in.δ = 1 − = 1 − = 0.677
p 2.90 in.

LRFD ASD
1 ⎛ Bu ⎞ 1 ⎛ 21.9 kips ⎞ 1 ⎛ Ba ⎞ 1 ⎛ 14.2 kips ⎞ β = − 1 = − 1 β = − 1 = − 1 ⎜ ⎟ ⎜ ⎟ ⎜ ⎟ ⎜ ⎟ ρ ⎝ Tu ⎠ 0.569 ⎝ 17.1 kips ⎠ ρ ⎝ Ta ⎠ 0.569 ⎝ 11.4 kips ⎠

\= 0.493 = 0.432

<!-- p. 402 -->

IIC-30

1 ⎛ β ⎞ 1 ⎛ β ⎞
α ' = ≤ 1.0 α ' = ≤ 1.0 ⎜ ⎟ ⎜ ⎟ δ ⎝−β⎠1 δ ⎝−β⎠1

1 ⎛ 0.493 ⎞ 1 ⎛ 0.432 ⎞
\= ⎜ ⎟ ≤ 1.0 = ⎜ ⎟ ≤ 1.0 0.677 ⎝ 1 − 0.493 ⎠ 0.677 ⎝ 1 − 0.432 ⎠

\= 1.44 > 1.0, use α ' = 1.0 . = 1.12 > 1.0, use α ' = 1.0 .

4.44Tu b ' 6.66Ta b ' t req = t req = pFu (1 + δα ') pFu (1 + δα ')

4.44 (17.1 kips/bolt )(1.94 in.) 6.66 (11.4 kips/bolt )(1.94 in.) = =
( 2.90 in.)( 58 ksi ) ⎡+⎣ 1 ( 0.677 )(1.0 ) ⎤⎦ ( 2.90 in.)( 58 ksi ) ⎡+⎣ 1 ( 0.677 )(1.0 ) ⎤⎦

\= 0.723 in. \< w in. o.k. = 0.723 in. \< w in. o.k

Design welds

Try fillet welds around perimeter (three sides) of both angles.

LRFD ASD
Puc = (171 kips ) 2 + (168 kips ) 2 = 240 kips Pac = (114 kips ) 2 + (112 kips ) 2 = 160 kips

\-1 ⎛ 171 kips ⎞ -1 ⎛ 114 kips ⎞ θ = tan = 45.5° θ = tan = 45.5° ⎜ ⎟ ⎜ ⎟ ⎝ 168 kips ⎠ ⎝ 112 kips ⎠

For θ = 450, l = 142 in., kl = 72 in., and k = 0.517 Manual
By interpolation Table 8-8

x = 0.132,
xl = 0.132(142 in.) = 1.91 in.
al = 8 in. − xl = 8 in. − 1.91 in. = 6.09 in.
a = 0.420

By interpolation

C = 3.55

LRFD ASD
Puc Ω Pac Dreq = Dreq =
φCC1l CC1l

240 kips 2.00 (160 kips ) = =
0.75 ( 3.55)(1.0 )( 2 welds )(14 12 in.) ( 3.55)(1.0 )( 2 welds )(14 12 in.)

\= 3.11 → 4 sixteenths = 3.11 → 4 sixteenths

Table J2.4 Minimum weld size is 4 in. Use 4-in. fillet Minimum weld size is 4 in. Use 4-in. fillet
welds. welds.

<!-- p. 403 -->

IIC-31

Check beam web thickness (against weld size required for strength)

For two fillet welds

6.19 D 6.19 ( 3.11 sixteenths )
t min = = = 0.296 in. \< 0.590 in. o.k.
Fu 65 ksi

Check the strength of the angles

Shear yielding
LRFD ASD
0.60 Fy Ag Eqn. J4-3 φRn = φ ( 0.60 Fy Ag ) Rn / Ω= Ω

3
3 ( 36 ksi )( 2 )(14 12 in.)( 4 in.) = 1.0 ( 0.60 )( 36 ksi )( 2 )(14 12 in.)( 4 in.) = 0.60
1.50
\= 470 kips > 168 kips o.k.
\= 313 kips > 112 kips o.k.

Similarly, shear yielding of the angles due to Huc is not critical.

Shear rupture

3 1 14.3 in.2 2 (14Anv = ( 4 in.) ⎡⎣ 2 in.) − 10 (1in.) ⎤=⎦

LRFD ASD
φRn = φ ( 0.60 Fu Anv ) 0.60 Fu Anv Eqn. J4-4 Rn / Ω= Ω
2 0.60 ( 58 ksi )(14.3 in. ) 2 = = 0.75 ( 0.60 )( 58 ksi )(14.3 in. ) 2.00

\= 372 kips > 168 kips o.k. = 248 kips > 11 kips o.k.

Block shear rupture

With n = 5, Lev = 14 in., Leh = 34 in. Section J4.3

2 3 1 3 1 4 in.) − ( 4 in.)( 2 ) = 4.12 in.Ant = ⎡⎣ ( 2 )(1.0 in.) ⎤⎦ (

2 3 4 in.)( 2 ) = 19.8 in.Agv = (13 14 in.)(

2 3 1 13 1 4 in.) − ( 4 4 in.)( 2 ) = 13.1 in.Anv = ⎡⎣ ( 2 )(1 in.) ⎤⎦ (

2Fu Ant = ( 58 ksi )( 4.12 in. ) = 239 kips

20.60 Fy Agv = 0.60 ( 36 ksi )(19.9 in. ) = 430 kips controls

20.60 Fu Anv = 0.6 ( 58 ksi )(13.1 in. ) = 457 kips

<!-- p. 404 -->

IIC-32

LRFD ASD
( 239 kips + 430 kips )
n / Ω= Eqn. J4-5 φRn = 0.75 ( 239 kips + 430 kips ) R 2.00

\= 502 kips > 168 kips o.k. = 334 kips > 112 kips o.k.

Check column flange

By inspection, the 4.16 in. thick column flange has adequate flexural strength, stiffness, and
bearing strength.

Note: When the brace is in compression, the buckling strength of the gusset would have to be
checked, where
LRFD ASD
φRn = φ c Fcr Aw Rn / Ω= Fcr Aw / Ω c

Kl1In the above equation, φcFcr or Fcr/Ωc may be determined from with Specification Section
r
E3 or J4.4, where l1 is the perpendicular distance from the Whitmore section to the interior
l1 + l 2 + l3edge of the gusset. Alternatively, the average value of l = may be substituted, where
3
these quantities are illustrated in the figure. Note that, for this example l2 is negative since part
of the Whitmore section is in the beam web.

The effective length factor K has been established as 0.5 by full scale tests on bracing
connections (Gross, 1990). It assumes that the gusset is supported on both edges. In cases
where the gusset is supported on one edge only, such as illustrated in Example 3, Figure (d),
the brace can more readily move out-of-plane and a sidesway mode of buckling can occur in
the gusset. For this case, K should be taken as 1.2.

Check gusset buckling

The area of the Whitmore section is

⎛ 50 ksi ⎞ 2Aw = ( 30.9 in.)( 34 in.) + ( 3.90 in.)( 0.590 in.) ⎜ ⎟ = 26.4 in. ⎝ 36 ksi ⎠

In the above equation, the area in the beam web is multiplied by the ratio 50/36 to convert the
area to an equivalent area of A36 plate.

17.0 in. 12 )( ) Kl1 0.5 (The slenderness ratio is = = 39.3
r 34 in.

From Specification Section E3

π 2 E π 2 ( 29000 ksi )
Fe = 2 = 2 = 185
⎛ Kl ⎞ 39.3
⎜ ⎟ ⎝ r ⎠

<!-- p. 405 -->

IIC-33

E 29000 ksi
Check 4.71 = 4.71 = 134
Fy 36 ksi

y 36 ksi ⎡ F ⎤ ⎡ ⎤ Fe 185 ksiThe buckling stress is given by Fcr = ⎢ 0.658 ⎥ Fy = ⎢ 0.658 ⎥ ( 36 ksi ) = 33.2 ksi
⎢ ⎥ ⎣ ⎦ ⎣ ⎦

The required stress is

LRFD ASD
675 kips 450 kips
f ua = 2 = 25.6 ksi f aa = 2 = 17.0 ksi 26.4 in. 26.4 in.

The available stress is The available stress is

33.2 ksi
Fcr / Ω= φFcr = 0.90 ( 33.2 ksi ) 1.67

\= 29.9 ksi > 25.6 ksi o.k. = 19.9 ksi > 17.0 ksi o.k.

<!-- p. 406 -->

IIC-34

Example II.C-3 Bracing Connection

Given:

Each of the four designs shown for the diagonal bracing connection between the W14×68
brace, W24×55 beam, and W14×211 column web have been developed using the Uniform
Force Method (the General Case and Special Cases 1, 2, and 3) for the load case of 1.2D +
1.3W for LRFD and D + W for ASD.

For the given values of α and β, determine the interface forces on the gusset-to-column and
gusset-to-beam connections for

a. General Case of Figure (a)
b. Special Case 1 of Figure (b)
c. Special Case 2 of Figure (c)
d. Special Case 3 of Figure (d)

Brace Axial Load Pu = |195 kips Pa = |130 kips
Beam End Reaction Ru = 44 kips Ra = 29 kips
Beam Axial Load Au = 26 kips Aa = 17 kips

<!-- p. 407 -->

IIC-35

Material Properties:

Brace W14×68 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Beam W24×55 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Column W14×211 ASTM A992 Fy = 50 ksi Fu = 65 ksi and 2-4
Gusset Plate ASTM A36 Fy = 36 ksi Fu = 58 ksi

<!-- p. 408 -->

IIC-36

Geometric Properties:

Brace W14×68 A=20.0 in.2 d=14.0 in. tw=0.415 in. bf=10.0 in. tf=0.720 in. Manual
Beam W24×55 d=23.6 in. tw=0.395 in. bf=7.01 in. tf=0.505 in. k=1.11 Table 1-1
Column W14×211 d=15.7 in. tw=0.980 in. bf=15.8 in. tf=1.56 in.

Solution A (General Case):

Assume β = β = 3 in.
⎛ 12 ⎞ ⎛ 12 ⎞
16.1 in.α = eb tan θ − ec + β tan θ = (11.8 in.) ⎜ 1 ⎟ − 0 + ( 3 in.) ⎜ 1 ⎟ = ⎝ 11 16 ⎠ ⎝ 11 16 ⎠

Since α ≠α , an eccentricity exists on the gusset-to-beam connection.

Calculate the interface forces

r = ( α + ec ) 2 + ( β + eb ) 2 = (16.1 in. + 0 in.) 2 + ( 3 in. + 11.8 in.) 2 = 21.9 in.

On the gusset-to-column connection

LRFD ASD
β 3 in. β 3 in. Vuc = Pu = (195 kips ) = 26.7 kips Vac = Pa = (130 kips ) = 17.8 kips
r 21.9 in. r 21.9 in.

ec ec H uc = Pu = 0 kips H ac = Pa = 0 kips
r r

On the gusset-to-beam connection

LRFD ASD
α 16.1 in. α 16.1 in. H ub = Pu = (195 kips ) = 143 kips H ab = Pa = (130 kips ) = 95.6 kips
r 21.9 in. r 21.9 in.

eb 11.8 in. eb 11.8 in. Vub = Pu = (195 kips ) = 105 kips Vab = Pa = (130 kips ) = 70.0 kips
r 21.9 in. r 21.9 in.

α −α α −α M ub = Vub ( M ab = Vab ( ) )

(105 kips )(15 34 in. − 16.1 in.) ( 70.0 kips )(15 34 in. − 16.1 in.) = =
12 in./ft 12 in./ft

\= -3.06 kip-ft = -2.04 kip-ft

In this case, this small moment is negligible.

On the beam-to-column connection, the shear is
LRFD ASD
Rub + Vub = 44 kips + 105 kips = 149 kips Rab + Vab = 29 kips + 70 kips = 99 kips

<!-- p. 409 -->

IIC-37

and the axial force is
LRFD ASD
Aub + Huc = 26 kips | 0 kips = 26 kips Aab + Hac = 17 kips | 0 kips = 17 kips

For a discussion of the sign use between Aub and Huc (Aab an Hac for ASD), refer to AISC
(1992).

Solution B (Special Case 1):

In this case, the centroidal positions of the gusset-edge connections are irrelevant; α and β are
given to define the geometry of the connection, but are not needed to determine the gusset edge
forces.

The angle of the brace from the vertical is

\-1 ⎛ 12 ⎞θ = tan = 49.8° ⎜ ⎟ ⎝ 10 18 ⎠
The horizontal and vertical components of the brace force are
LRFD ASD
H u = Pu sin θ = (195 kips ) sin 49.8° = 149 kips H a = Pa sin θ = (130 kips ) sin 49.8 ° = 99.3 kips
Vu = Pu cos θ = (195 kips ) cos49.8° = 126 kips Va = Pa cos θ = (130 kips ) cos49.8 ° = 83.9 kips

On the gusset-to-column connection
LRFD ASD
Vuc = Vu = 126 kips Vac = Va = 83.9 kips

H uc = 0 kips H ac = 0 kips

On the gusset-to-beam connection
LRFD ASD
Vub = 0 kips Vab = 0 kips

H ub = H u = 149 kips H ab = H a = 99.3 kips

On the beam-to-column connection
LRFD ASD
Rub = 44 kips (shear) Rab = 29 kips (shear)

Aub = 26 kips (axial transfer force) Aab = 17 kips (axial transfer force)

In addition to the forces on the connection interfaces, the beam is subjected to a moment Mub
or or Mab, where
LRFD ASD
(149 kips )(11.8 in.) ( 99.3 kips )(11.8 in.)
M ub = H ub eb = M ab = H ab eb =
12 in./ft 12 in./ft

\= 147 kip-ft = 97.6 kip-ft

<!-- p. 410 -->

IIC-38

This moment, as well as the beam axial load Hub = 149 kips or Hab = 99.3 kips and the
moment and shear in the beam associated with the end reaction Rub or Rab, must be considered
in the design of the beam.

Solution C (Special Case 2):

Assume β = β = 10 12 in.

⎛ 12 ⎞ ⎛ 12 ⎞
24.2 in.α = eb tan θ − ec + β tan θ = (11.8 in.) ⎜ 1 ⎟ − 0 + (10 12 in.) ⎜ 1 ⎟ = ⎝ 11 16 ⎠ ⎝ 11 16 ⎠

Calculate the interface forces for the general case before applying Special Case 2.

r = ( α + ec ) 2 + ( β + eb ) 2 = ( 24.2 in. + 0 in.) 2 + (10 12 in. + 11.8 in.) 2 = 32.9 in.

On the gusset-to-column connection

LRFD ASD
β 10 12 in. β 10 12 in. Vuc = Pu = (195 kips ) = 62.2 kips Vac = Pa = (130 kips ) = 41.5 kips
r 32.9 in. r 32.9 in.

ec ec H uc = Pu = 0 kips H ac = Pa = 0 kips
r r

On the gusset-to-beam connection

LRFD ASD
α 24.2 in. α 24.2 in. H ub = Pu = (195 kips ) = 143 kips H ab = Pa = (130 kips ) = 95.6 kips
r 32.9 in. r 32.9 in.

eb 11.8 in. eb 11.8 in. Vub = Pu = (195 kips ) = 69.9 kips Vab = Pa = (130 kips ) = 46.6 kips
r 32.9 in. r 32.9 in.

On the beam-to-column connection, the shear is
LRFD ASD
Rub + Vub = 44 kips + 69.9 kips = 114 kips Rab + Vab = 29 kips + 46.6 kips = 75.6 kips

and the axial force is
LRFD ASD
Aub + Huc = 26 kips | 0 kips = 26 kips Aab + Hac = 17 kips | 0 kips = 17 kips

Next, applying Special Case 2 with ∆Vub = Vub = 69.9 kips (∆Vab = Vab = 46.6 kips for ASD),
calculate the interface forces.

<!-- p. 411 -->

IIC-39

On the gusset-to-column connection (where Vuc is replaced by Vuc + ∆Vub) or (where Vac is
replaced by Vac + ∆Vab for ASD)

LRFD ASD
Vuc = 62.2 kips + 69.9 kips = 132 kips Vac = 41.5 kips + 46.6 kips = 88.1 kips

H uc = 0 kips (unchanged) H ac = 0 kips (unchanged)

On the gusset-to-beam connection (where Vub is replaced by Vub - ∆Vub) or (where Vab is
replaced by Vab - ∆Vab)
LRFD ASD
H ub = 143 kips (unchanged) H ab = 95.6 kips (unchanged)

Vub = 69.9 kips − 69.9 kips = 0 kips Vab = 46.6 kips − 46.6 kips = 0 kips

( 69.9 kips )( 24.2 in.) ( 46.6 kips )( 24.2 in.) M ub = ( ∆ Vub ) α = M ab = ( ∆Vab ) α =
12in./ft 12in./ft

\= 141 kip-ft = 94.0 kip-ft

On the beam-to-column connection, the shear is
LRFD ASD
Rub + ∆Vub - ∆Vub Rab + ∆Vab - ∆Vab

\= 44 kips + 69.9 kips - 69.9 kips = 29 kips + 46.6 kips – 46.6 kips

\= 44 kips = 29 kips

and the axial force is

LRFD ASD
Aub + Huc = 26 kips | 0 kips = 26 kips Aab + Hac = 17 kips | 0 kips = 17 kips

<!-- p. 412 -->

IIC-40

Solution D (Special Case 3):

Set β = β = 0 in.

⎛ 12 ⎞
12.8 in.α = be tan θ = (11.8 in.) ⎜ ⎟ = ⎝ 11 116 ⎠

Since, α ≠α , an eccentricity exists on the gusset-to-beam connection.

Calculate the interface forces

r = α 2 + eb 2 = (12.8 in.) 2 + (11.8 in.) 2 = 17.4 in.

On the gusset-to-beam connection

LRFD ASD
α 12.8 in. α 12.8 in. H ub = Pu = (195 kips ) = 143 kips H ab = Pa = (130 kips ) = 95.6 kips
r 17.4 in. r 17.4 in.

eb 11.8 in. eb 11.8 in. Vub = Pu = (195 kips ) = 132 kips Vab = Pa = (130 kips ) = 88.2 kips
r 17.4 in. r 17.4 in.

α −α α −α M ub = Vub ( M ab = Vab ( ) )

(132 kips )(12.8 in. − 13 12 in.) ( 88.2 kips )(12.8 in. − 13 12 in.) = =
12 in./ft 12 in./ft

\= -7.70 kip-ft = -5.15 kip-ft

In this case, this small moment is negligible.

On the beam-to-column connection, the shear is

LRFD ASD
Rub + Vub = 44 kips + 132 kips = 176 kips Rab + Vab = 29 kips + 88.2 kips = 117 kips

And the axial force is

LRFD ASD
Aub + Huc = 26 kips | 0 kips = 26 kips Aab + Hac = 17 kips | 0 kips = 17 kips

Note: From the foregoing results, designs by Special Case 3 and the General Case of the
Uniform Force Method provide the more economical designs. Additionally, note that designs
by Special Case 1 and Special Case 2 result in moments on the beam and/ or column that must
be considered.

<!-- p. 413 -->

IIC-41

Example II.C-4 Truss Support Connection

Given:

Determine the requirements for the following cases:

a. Joint L1
b. Joint U1

RD = 18.5 kips
RL = 55.5 kips

Use E70 electrodes.

Material Properties:

Top Chord WT8×38.5 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Bottom Chord WT8×28.5 ASTM A992 Fy = 50 ksi Fu = 65 ksi Tables 2-3
Diagonal U0L1 2L4×32×a ASTM A36 Fy = 36 ksi Fu = 58 ksi and 2-4
Web U1L1 2L32×3×c ASTM A36 Fy = 36 ksi Fu = 58 ksi
Diagonal U1L2 2L32×22×c ASTM A36 Fy = 36 ksi Fu = 58 ksi

<!-- p. 414 -->

IIC-42

Geometric Properties:

Top Chord WT8×38.5 tw = 0.455 in.
Bottom Chord WT8×28.5 tw = 0.430 in. d = 8.22 in. Manual
Tables 1-8Diagonal U0L1 2L4×32×a A = 5.35 in.2 y = 1.20 in.
and 1-15
Web U1L1 2L32×3×c A = 3.91 in.2
Diagonal U1L2 2L32×22×c A = 3.58 in.2

LRFD ASD
Web U1L1 load Web U1L1 load

Ru = -108 kips Ra = -72 kips

Diagonal U0L1 load Diagonal U0L1 load

Ru = +165 kips Ra = +110 kips

Diagonal U1L2 load Diagonal U1L2 load

Ru = +114 kips Ra = +76 kips

Solution a:

Check shear yielding of bottom chord tee stem (on Section A-A)

Rn = 0.6 Fy Aw = 0.6 ( 50 ksi )( 8.22 in.)( 0.430 in.) = 106 kips Eqn. J4-3

LRFD ASD
106 kips
Rn / Ω= = 70.7 kips φRn = 1.00 (106 kips ) = 106 kips 1.50

106 kips \< 108 kips n.g. 70.7 kips \< 72 kips n.g.

Additional shear area must be provided.

Try PLv in.×4 in. complete-joint-penetration groove welded to the stem of the WT.

Rn = 0.6 ( 36 ksi )( 4 in.)( 716 in.) = 37.8 kips

LRFD ASD
37.8 kips
Rn / Ω= 70.7 kips + = 95.9 kips φRn = 106 kips + 1.00 ( 37.8 kips ) = 144 kips 1.50

144 kips > 108 kips o.k. 95.9 kips > 72 kips o.k.

Design welds for member U1L1

User Note: Specification Section J1.7 requiring that the center of gravity of the weld group
coincide with the center of gravity of the member does not apply to end connections of Section J1.7
statically loaded single angle, double angle and similar members.

<!-- p. 415 -->

IIC-43

The minimum weld size is wmin = 316 in.
Table J2.4
The maximum weld size is wmax = thickness - 116 in. = 1 4 in.

Calculate the minimum length of x-in. fillet weld.

LRFD ASD
Ru 108 kips Ra 72 kips Lmin = = Lmin = = 1.392 D 1.392 ( 3 sixteenths ) 0.928 D 0.928 ( 3 sixteenths )

\= 25.9 in. = 25.9 in.

Use 62 in. of x-in. weld at the heel and toe of both angles for a total of 26 in.

Design welds for member U0L1
Table J2.4
The minimum weld size is wmin = 316 in.

The maximum weld size is wmax = thickness - 116 in. = 5 16 in.

Calculate the minimum length of x in. fillet weld.

LRFD ASD
Ru 165 kips Ra 110 kips Lmin = = Lmin = = 1.392 D 1.392 ( 3 sixteenths ) 0.928 D 0.928 ( 3 sixteenths )

\= 39.5 in. = 39.5 in.

Use 10 in. of x in. weld at the heel and toe of both angles for a total of 40 in.

Check tension yielding of diagonal U0L1

2 Eqn. J4-1Rn = Fy Ag = ( 36 ksi )( 5.35 in. ) = 193 kips

LRFD ASD
193 kips
Rn / Ω= = 115 kips φ Rn = 0.90 (193 kips ) = 173 kips 1.67

173 kips > 165 kips o.k. 115 kips > 110 kips o.k.

Check tension rupture of diagonal U0L1

Table D3.1 x 1.20 in.
U = 1 − = 1 − = 0.880 Case 2
l 10 in.

2Rn = Fu Ae = ( 58 ksi )( 0.880 )( 5.35 in. ) = 273 kips Eqn. J4-2
LRFD ASD
φRn = 0.75 ( 273 kips ) = 205 kips 273 kips Rn / Ω= = 137 kips
2.00
205 kips > 165 kips o.k. 137 kips > 110 kips o.k.

<!-- p. 416 -->

IIC-44

Solution b:

Check shear yielding of top chord tee stem (on Section B-B)

Rn = 0.6 Fy Aw = 0.6 ( 50 ksi )( 8.26 in.)( 0.455 in.) = 113 kips Eqn. J4-3

LRFD ASD
φ Rn = 1.00 (113 kips ) = 113 kips 113 kips Rn / Ω= = 75.3 kips
1.50
113 kips > 78 kips o.k.
75.3 kips > 52 kips o.k.

Design welds for member U1L1

As calculated previously in Solution a, use 62 in. of x-in. weld at the heel and toe of both
angles for a total of 26 in.

Design welds for member U1L2

The minimum weld size is wmin = 316 in.
Table J2.4
The maximum weld size is wmax = 14 in.

Calculate the minimum length of 4 in. fillet weld.

LRFD ASD
Ru 114 kips Ra 76 kips Lmin = = Lmin = = 1.392 D 1.392 ( 4 sixteenths ) 0.928 D 0.928 ( 4 sixteenths )

\= 20.5 in. = 20.5 in.

Use 72 in. of 4-in. fillet weld at the heel and 4 in. of fillet weld at the toe of each angle for a
total of 23 in.

Check tension yielding of diagonal U1L2

2 Eqn. J4-1Rn = Fy Ag = ( 36 ksi )( 3.58 in. ) = 129 kips

LRFD ASD
129 kips
Rn / Ω= = 77.2 kips φRn = 0.90 (129 kips ) = 116 kips 1.67

116 kips > 114 kips o.k. 77.2 kips > 76 kips o.k.

Check tension rupture of diagonal U1L2

x 1.13 in.
U = 1 − = 1 − = 0.803 Table D3.1 l ⎛ 7 12 in. + 4 in. ⎞
⎜ ⎟ Case 2 ⎝ 2 ⎠

2 Eqn. J4-2Rn = Fu Ae = ( 58 ksi )( 0.803)( 3.58 in. ) = 167 kips

<!-- p. 417 -->

IIC-45

LRFD ASD
167 kips
Rn / Ω= = 83.4 kips φRn = 0.75 (167 kips ) = 125 kips 2.00

125 kips > 114 kips o.k. 83.4 kips > 76 kips o.k.

Check block shear rupture

Because the cut end of the angle, the block shear rupture model presented in Part 9 does not
directly apply. Conservatively, the block shear rupture strength will be based on the shear
rupture strength of the WT stem along the length of the welds.

Rn = 0.6 Fu Aw = 0.6 ( 65 ksi )( 7 12 in. + 4 in.)( 0.455 in.) = 204 kips Eqn. J4-4

LRFD ASD
φRn = 0.75 ( 204 kips ) = 153 kips 204 kips Rn / Ω= = 102 kips
2.00

153 kips > 114 kips o.k. 102 kips > 76 kips o.k.

<!-- p. 418 -->

IIC-46

Example II.C-5 HSS Chevron Brace Connection

Given:

The loads shown are actual loads from the bottom chevron from the example problem at the
back of the book. The beam above has been design to carry its load with out the chevron, and
the end connections have been design to all vertical and horizontal loads required. Check the
HSS braces for tension and compression and design the connection including welding, shear
lag requirements and check to see if stiffening is required.

Use E70 electrodes.

Material Properties:
Beam W18×35 Fy = 50 ksi Fu = 65 ksi Manual
Brace HSS6×6×2 Fy = 46 ksi Fu = 58 ksi Tables 2-3
Gusset Plate Fy = 36 ksi Fu = 58 ksi and 2-4

Geometric Properties: Manual
Beam W18×35 d = 17.7 in. tw = 0.300 in. kdes. = 0.827 in. Tables 1-1
Brace HSS6×6×2 H = 6 in. B = 6 in. A = 9.74 in. t = 0.465 in. and 1-12

Solution:

Determine required brace-to-gusset weld size

Since the brace loads are axial, the angle between the longitudinal brace axis and line of force
is θ w = 0 ° .
FW = 0.60 FEXX (1 + 0.5sin 1.5 θ w ) = 0.60 ( 70 ksi )(1 + 0.5sin 1.5 0 ° ) = 42 ksi

<!-- p. 419 -->

IIC-47

LRFD ASD
Pu Pa Ω Wwreq ' d = + 116 in. Wwreq ' d = + 116 in. φ 4 Fw ( 0.707 ) Lw 4 Fw ( 0.707 ) Lw

158 kips (105 kips )( 2.00 ) = + 116 in. = + 116 in. 0.75 ( 4 )( 42 ksi )( 0.707 )( 6 in.) ( 4 )( 42 ksi )( 0.707 )( 6 in.)

\= 0.296 in.+ z-in. = 0.358 in. = 0.295 in.

Use a-in. fillet weld Use a-in. fillet weld

Note: the z-in. added to the weld size is to account for the slot in HSS

The minimum weld size for this connection is x in. The required weld size is larger therefore,
use a-in. fillet welds. Table J2.4

Determine required gusset plate thickness

We = Ww − 3 8 in.- 116 in. = 5 16 in.

LRFD ASD
φ ( 0.60 FEXX We )( 0.707 )( 2 ) Ω ( 0.60 FEXX We )( 0.707 )( 2 )
t1req ' d = t1req ' d = φ ( 0.60 Fy 1 ) Ω ( 0.60 Fy 1 )

0.75 ( 0.60 )( 70 ksi )( 14 in.)( 0.707 )( 2 ) (1.50 )( 0.60 )( 70 ksi )( 14 in.)( 0.707 )( 2 ) = =
1.00 ( 0.60 )( 36 ksi ) ( 2.00 )( 0.60 )( 36 ksi )

\= 0.644 in. = 0.644 in.

Use a w-in. gusset plate.

Check gusset plate buckling (compression brace)

t1 3 4 in.r = = = 0.217 in.
12 12

From the figure, the distance l1 = 62 in.

Since the gusset is attached by one edge only, the buckling mode could be a sidesway type as
shown in Commentary Table C-C2.2. In this case use K = 1.2.

Kl1 1.2 ( 6 12 in.) = = 36.0
r 0.217 in.

E 29000 ksi
Limiting slenderness ratio 4.71 = 4.71 = 134 > 36.0
Fy 36 ksi

<!-- p. 420 -->

IIC-48

π 2 E π 2 ( 29000 ksi )
Fe = 2 = 2 = 221 ksi Eqn. E3-4
⎛ Kl1 ⎞ ( 36.0 )
⎜ ⎟ ⎝ r ⎠

y 36 ksi ⎡ F ⎤ ⎡ ⎤ Fe 221 ksiFcr = ⎢ 0.658 ⎥ Fy = ⎢ 0.658 ⎥ ( 36 ksi ) = 33.6 ksi
⎢ ⎥ ⎣ ⎦ ⎣ ⎦ Eqn. E3-2

wl = B + 2 [ (connection length) tan30° ] = 6 in. + 2 ( 6 in.) tan30 ° = 12.9 in.

Note: Here, the Whitmore section is assumed to be entirely in the gusset. The Whitmore
section can spread across the joint into adjacent connected material of equal or greater
thickness or adjacent connected material of lesser thickness provided that a rational analysis is
performed. Eqn. E3-1

2 3 4 in.) = 9.675 in.Aw = l w t1 = (12.9 in.)(

2Pn = Fcr Aw = ( 33.6 ksi )( 9.675 in. ) = 325 kips

LRFD ASD
325 kips
nP / Ω= = 195 kips φ nP = 0.90 ( 325 kips ) = 293 kips 1.67

293 kips > 158 kips o.k. 204 kips > 105 kips o.k.

Check tension yielding of gusset plate (tension brace)

From above, Aw = 8.06 in.2

2 Eqn. J4-1Rn = Fy 1 Aw = ( 36 ksi )( 9.675 in. ) = 348 kips

LRFD ASD
348 kips
Rn / Ω= = 208 kips φ Rn = 0.90 ( 348 kips ) = 313 kips 1.67

313 kips > 158 kips o.k. 208 kips > 105 kips o.k.

Check shear strength at brace-to-gusset welds
Table D3.1
Try minimum weld length, Lw = 6 in. Case 6

2Effective Area, Ae = 4 Lw t = 4 ( 6 in.)( 0.465 in.) = 11.2 in.

2Nominal Shear Strength, Vn = 0.6 Fy Ae = 0.6 ( 46 ksi )(11.2 in. ) = 309 kips Eqn. J4-3

LRFD ASD
309 kips
Rn / Ω= = 206 kips φ Rn = 1.00 ( 309 kips ) = 309 kips 1.50
309 kips > 158 kips o.k. 206 kips > 105 kips o.k.

<!-- p. 421 -->

IIC-49

Check shear lag fracture in HSS brace

B 2 + 2 BH ( 6 in.) 2 + 2 ( 6 in.)( 6 in.) x = = = 2.25 in.
4 ( B + H ) 4 ( 6 in.+6 in.)
Table D3.1
x 2.25 in. Case 6
U = 1 − = 1 − = 0.625 in.
Lw 6 in.

2 3 4 in.+ 1 8 in. gap ) = 9.01 in.An = Ag − 2tt1 = 9.74 − 2 ( 0.9)(0.465 in.)(

2 2Ae = UAn = 0.625 ( 9.16 in. ) = 5.72 in.

Rn = Fu Ae = ( 58 ksi )( 5.63 in.) = 327 kips Eqn. J4-4

LRFD ASD
327 kips
Rn / Ω= = 164 kips φ Rn = 0.75 ( 327 kips ) = 245 kips 2.00

245 kips > 158 kips o.k. 164 kips > 105 kips o.k.

Calculate interface forces

Design the gusset-to-beam connection as if each brace were the only brace and locate each
brace’s connection centroid at the ideal centroid locations to avoid inducing a moment on the
gusset-beam interface, similarly to uniform force method special case 3.

d 17.7 in.
eb = = = 8.85 in.
2 2

−⎛1 12 ⎞θ = tan = 48° ⎜ ⎟ ⎝ 10 1316 ⎠

Let α = α = be tan θ = ( 8.85 in.) tan 48° = 9.83 in. → Use 10 in.

β = ce = 0

r = ( α + ec ) 2 + ( β + eb ) 2 = (10 in. + 0 ) 2 + ( 0 + 8.85 in.) 2 = 13.4 in.

LRFD ASD
αPu (10 in.)(158 kips ) αPa (10 in.)(105 kips ) H ub = = = 118 kips H ab = = = 78.6 kips
r 13.4 in. r 13.4 in.

eb Pu ( 8.85 in.)(158 kips ) eb Pa ( 8.85 in.)(105 kips ) Vub = = = 105 kips Vab = = = 69.6 kips
r 13.4 in. r 13.4 in.

<!-- p. 422 -->

IIC-50

Determine required gusset-to-beam weld size

The weld length is twice the horizontal distance from the work point to the centroid of the
gusset-to-beam connection, α, for each brace. Therefore, l = 2α = 2 (10 in.) = 20 in.

Since the gusset straddles the work line of each brace, the weld is uniformly loaded. Therefore,
the available strength is the average required strength and the fillet weld should be designed
for 1.25 times the average strength.

LRFD ASD
1.25 Pu 1.25 (158 kips ) 1.25 Pa 1.25 (105 kips ) Dreq ' d = = = 3.55 Dreq ' d = = = 3.54 1.392l 1.392 ( 20 in.)( 2 ) 0.928l 0.928 ( 20 in.)( 2 )

The minimum fillet weld size is 4 in. The required weld size is also 4 in., use a 4 in. fillet
weld 40-in. long total. Table J2.4

Check gusset thickness (against weld size required for strength)

6.19 D 6.19 ( 3.55)
t min = = = 0.379 in. \< s in. o.k.
Fu 58 ksi

Check local web yielding of the beam

50 ksi )( 0.300 in.) = 362 kips Eqn. J10-2Rn = ( N + 5 k ) Fy t w = ⎡⎣ 20 in. + 5 ( 0.827 in.) ⎤⎦ (

LRFD ASD
φ Rn = 1.00 ( 662 kips ) = 662 kips 662 kips Rn / Ω= = 441 kips
1.50
158 kips(cos 48°) = 105 kips 105 kips(cos 48°) = 70.2 kips

662 kips > 105 kips o.k. 441 kips > 70.2 kips o.k.

<!-- p. 423 -->

IIC-51

Example II.C-6 Heavy Wide Flange Compression Connection
(flanges on the outside)

Given:

This truss has been designed with nominal 14 in. W-shapes, with the flanges to the outside of
the truss. Beams framing into the top chord and lateral bracing are not shown but can be
assumed to be adequate.

Based on multiple load cases, the critical dead and live load forces for this connection were
determined. A typical top chord connection and the dead load and live load forces are shown
below in detail A. Design this typical connection using 1-in. diameter ASTM A325 slipcritical bolts in oversized holes with a class-A faying surface.

Note: slip critical bolts in oversized holes were selected for this truss to facilitate field erection.

<!-- p. 424 -->

IIC-52

Material Properties:

Beam W-shapes ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Gusset Plates ASTM A36 Fy = 36 ksi Fu = 58 ksi Tables 2-3
and 2-4

Geometric Properties:

W14×109 d = 14. 3 in. bf = 14.6 in. tf = 0.860 in. Manual
W14×61 d = 13.9 in. bf = 9.99 in. tf = 0.645 in. Table 1-1

Solution:

Determine the required strength of the member
LRFD ASD
Left top chord: Left top chord:
1.2(262 kips) + 1.6(262 kips) = 734 kips 262 kips + 262 kips = 524 kips

Right top chord: Right top chord:
1.2(345 kips) + 1.6(345 kips) = 966 kips 345 kips + 345 kips = 690 kips

Vertical: Vertical:
1.2(102 kips) + 1.6(102 kips) = 286 kips 102 kips + 102 kips = 204 kips

Diagonal: Diagonal:
1.2(113 kips) + 1.6(113 kips) = 316 kips 113 kips + 113 kips = 226 kips

Determine the single shear strength

dbolt = 1 in. Section J3.8
ASTM A325-SC bolts
Class A faying surface
µ = 0.35 (class A)
dhg = 1.25 in. (diameter of holes at gusset plates)
hsc = 0.85 (oversized and short-slotted holes)
Tb = 51.0 kips Table J3.1
Du = 1.13

Slip prevention up to the required strength level is selected in this case to prevent truss Eqn. J3-4
deflections that could permit a significant ponding condition for which the truss was not
designed.

Rn = µDuhscTb Ns = 0.35(1.13)(0.85)(51.0 kips)(1) = 17.1 kips

LRFD ASD
For connections designed to prevent slip at For connections designed to prevent slip at Section J3.8
the required strength level; the required strength level;

φ = 0.85 Ω = 1.76

φRn = 0.85(17.1 kips) = 14.6 kips/bolt Rn/Ω = 17.1 kips / 1.76 = 9.74 kips/bolt

<!-- p. 425 -->

IIC-53

Diagonal connection
LRFD ASD
Axial force = 316 kips Axial force = 226 kips

316 kips / 14.6 kips/bolt = 21.7 bolts 226 kips / 9.74 kips/bolt = 23.2 bolts

2 rows both sides = 21.7 bolts / 4 = 5.42 2 rows both sides = 23.2 bolts / 4 = 5.80

Therefore use 6 rows @ min. 3 in. spacing Therefore use 6 rows @ min. 3 in. spacing

Check the Whitmore section in the gusset plate (tension only)

Whitmore section = gage of the bolts + tan 300 (length of bolt group) × 2 Manual
Part 9

1 0 ⎡ × 2 = ( 5 2 in.) + tan30 ⎣( 5 spaces)( 3 in.) ⎤⎦
\= 22.8 in.

Try a in. thick plate

Ag = (0.375 in.)(22.8 in.) = 8.56 in2

LRFD ASD
Check tension yielding Check shear yielding

φ = 0.90 Ω= 1.67
φRn = φ FyAg Rn / Ω = FyAg / Ω Eqn. J4-1

\= 0.90(36 ksi)(8.56 in2)(2) = (36 ksi)(8.56 in2)(2) / 1.67

\= 555 kips > 316 kips o.k. = 369 kips > 226 kips o.k.

Check block shear rupture in plate Check block shear rupture in plate Section J4.3

φ = 0.75 Ω= 2.00

Tension stress is uniform, Tension stress is uniform,

Therefore; Ubs = 1.0 Therefore; Ubs = 1.0

tp = 0.375 in. Try Plate with, tp = 0.375 in.

Agv / in. = (2 rows)[(6 bolts-1)(3 in.) + 2 in.] Agv / in. = (2 rows)[(6 bolts-1)(3 in.) + 2 in.]
\= 34.0 in. = 34.0 in.

Anv / in. = 34.0 in. – (2 rows)(6 bolts –0.5) Anv / in. = 34.0 in. – (2 rows)(6 bolts –0.5)
× (1.25 in.+ 0.0625 in.) = 19.6 in × (1.25 in.+ 0.0625 in.) = 19.6 in

Ant / in. = 5.50 in. – (1.25 in. + 0.625 in.) Ant / in. = 5.50 in. – (1.25 in. + 0.625 in.)
\= 4.19 in. = 4.19 in.

<!-- p. 426 -->

IIC-54

φRn = φ(0.6FuAnv + UbsFuAnt) M Rn / Ω = (0.6FuAnv + UbsFuAnt) / Ω M
Eqn. J4-5
φ(0.6FyAgv + UbsFuAnt) (0.6FyAgv + UbsFuAnt) / Ω

Tension Rupture Component Tension Rupture Component

φUbs(Fu Ant) / t = 182 kips/in. Ubs(Fu Ant) / (tΩ) = 121 kips/in.

Shear Yielding Component Shear Yielding Component

φ(0.6FyAgv) / t = 551 kips/in. (0.6FyAgv) / (tΩ) = 367 kips/in.

Shear Rupture Component Shear Rupture Component

φ(0.6FuAnv) / t = 511 kips/in. (0.6FuAnv) / (tΩ) = 340 kips/in.

φRn = (511 kips/in. + 182 kips/in.)(0.375 in.) Rn /Ω = (340 kips/in.+121 kips/in.)(0.355 in.)
\= 260 kips = 173 kips
M (551 kips/in. + 182 kips/in.)(0.355 in.) M (367 kips/in.+121 kips/in.)(0.355 in.)
\= 275 kips = 183 kips

\= 260 kips \< 275 kips = 173 kips \< 183 kips

260 kips > 316 kips / 2 = 158 kips o.k. 173 kips > 226 kips / 2 = 113 kips o.k.

Check block shear rupture on beam flange Check block shear rupture on beam flange
By inspection, block shear rupture on the By inspection, block shear rupture on the
beam flange will not control. beam flange will not control.

Bolt bearing on plate Bolt bearing on plate

Based on Bolt Spacing = 3 in.; oversized Based on Bolt Spacing = 3 in.; oversized
holes, Fu = 58 ksi holes, Fu = 58 ksi

φnr = ( 91.4 kips/in. )( 0.375 in. ) nr / Ω= ( 60.9 kips/in. )( 0.375 in. ) Manual
\= 34.3 kips > 14.6 kips =22.8 kips > 9.74 kips Table 7-5

Based on Edge Distance = 2 in.; oversized Based on Edge Distance = 2 in.; oversized
holes, Fu = 58 ksi holes, Fu = 58 ksi

φnr = ( 71.8 kips/in. )( 0.375 in. ) nr / Ω= ( 47.9 kips/in. )( 0.375 in. ) Manual
Table 7-6
\= 26.9 kips > 14.6 kips = 18.0 kips > 9.74 kips

Bolt bearing on flange Bolt bearing on flange

Based on Bolt Spacing = 3 in.; standard Based on Bolt Spacing = 3 in.; standard
holes, Fu = 65 ksi holes, Fu = 65 ksi

φnr = (113 kips/in. )( 0.645 in. ) nr / Ω= ( 75.6 kips/in. )( 0.645 ) Manual
\= 72.9 kips > 14.6 kips = 48.8 kips > 9.74 kips Table 7-5

Based on Edge Distance = 2 in.; standard Based on Edge Distance = 2 in.; standard
holes, Fu = 65 ksi holes, Fu = 65 ksi

<!-- p. 427 -->

IIC-55

φnr = ( 85.9 kips/in. )( 0.645 in. ) nr / Ω= ( 57.3 kips/in. )( 0.645 in. ) Manual
Table 7-6 = 55.4 kips > 14.6 kips = 37.0 kips > 9.74 kips

Horizontal connection
LRFD ASD
Axial force = 966 kips – 734 kips = 232 kips Axial force = 690 kips – 524 kips = 166 kips

232 kips / 14.6 kips/bolt = 15.9 bolts 166 kips / 9.74 kips/bolt = 17.0 bolts Section J3.5

2 rows both sides = 15.9 bolts / 4 = 3.98 2 rows both sides = 17.0 bolts / 4 = 4.26

Use 6 bolts per row Use 6 bolts per row

Check shear in plate Check shear in plate
Section J4.3
φ = 0.75 Ω= 2.00

Try Plate with, tp = 0.375 in. Try Plate with, tp = 0.375 in.

Agv / tp = (1 row)(6 bolts -1)(6 in.) + 4 in. Agv / tp = (1 row)(6 bolts -1)(6 in.) + 4 in.

\= 34.0 in. = 34.0 in.

Anv / tp = 34.0 in. – (1 row)(6 bolts) Anv / tp = 34.0 in. – (1 row (6 bolts – 0.5)
× (1.25 in.+ 0.0625 in.) = 26.1 in × (1.25 in.+ 0.0625 in.) = 26.8 in

Check shear yielding Check shear yielding
Eqn. J4-3
φ = 1.00 Ω= 1.50

Rn / Ω = (0.6FyAg) / Ω = 184 kipsφRn = φ(0.6FyAg) = 275 kips

Check shear rupture
Check shear rupture
φ = 0.75
Ω= 2.00

Eqn. J4-4φRn = φ(0.6FuAnv) = 256 kips Rn / Ω = (0.6FuAnv) / Ω = 170 kips

\= 256 kips \< 275 kips = 170 kips \< 184 kips

256 kips > 232 kips / 2 = 116 kips o.k. 170 kips > 166 kips / 2 = 83.0 kips o.k.

Bolt bearing on plate Bolt bearing on plate

<!-- p. 428 -->

IIC-56

Based on Bolt Spacing = 6 in.; oversized Based on Bolt Spacing = 6 in.; oversized
holes, Fu = 58 ksi holes, Fu = 58 ksi
Manual
φnr = (104 kips/in. )( 0.375 in. ) nr / Ω= ( 69.9 kips/in. )( 0.375 in. ) Table 7-5
\= 39.0 kips > 14.6 kips =26.1 kips > 9.74 kips

Based on Edge Distance = 2 in.; oversized Based on Edge Distance = 2 in.; oversized
holes, Fu = 58 ksi holes, Fu = 58 ksi
Manual
φnr = ( 71.8 kips/in. )( 0.375 in. ) nr / Ω= ( 47.9 kips/in. )( 0.375 in. ) Table 7-6
\= 26.9 kips > 14.6 kips = 18.0 kips > 9.74 kips

Bolt bearing on flange Bolt bearing on flange

Based on Bolt Spacing = 6 in.; standard Based on Bolt Spacing = 6 in.; standard
holes, Fu = 65 ksi holes, Fu = 65 ksi

Manualφnr = (117 kips/in. )( 0.860 in. ) nr / Ω= ( 78.0 kips/in. )( 0.860 ) Table 7-5
\= 101 kips > 14.6 kips = 67.0 kips > 9.74 kips

Based on edge distance = 2 in.; standard Based on edge distance = 2 in.; standard
holes, Fu = 65 ksi holes, Fu = 65 ksi

φnr = ( 85.9 kips/in.)( 0.860 in.) nr / Ω= ( 57.3 kips/in.)( 0.860 in.) Manual
Table 7-6
\= 73.9 kips > 14.6 kips = 49.3 kips > 9.74 kips

Vertical connection
LRFD ASD
Axial force = 286 kips Axial force = 204 kips

286 kips / 14.6 kips/bolt = 19.6 bolts 204 kips / 9.74 kips/bolt = 20.9 bolts

2 rows both sides = 19.6 bolts / 4 = 4.91 2 rows both sides = 20.9 bolts / 4 = 5.24
Therefore use 5 rows Therefore use 6 rows

Check shear in plate Check shear in plate Specification
Section J4.3
Try Plate with, tp = 0.375 in. Try Plate with, tp = 0.375 in.

Agv / tp = 33 w in. (from sketch) Agv / tp = 33 w in. (from sketch)

Anv / tp = 33 w in. – (1 row)(7 bolts) Anv / tp = 33 w in. – (1 row)(7 bolts)
× (1.25 in. + 0.0625 in.) = 24.6 in × (1.25 in. + 0.0625 in.) = 24.6 in

Check shear yielding Check shear yielding

φ = 1.00 Ω= 1.50

φRn = φ(0.6FyAg) = 273 kips Eqn. J4-3 Rn / Ω = (0.6FyAg) / Ω = 182 kips

<!-- p. 429 -->

IIC-57

Check shear rupture Check shear rupture

Where φ = 0.75 Where Ω= 2.00

φRn = φ(0.6FuAnv) = 240 kips Rn / Ω = (0.6FuAnv) / Ω = 160 kips
Eqn. J4-4
\= 240 kips \< 273 kips = 160 kips \< 182 kips

240 kips > 286 kips / 2 = 143 kips o.k. 160 kips > 204 kips / 2 = 102 kips o.k.

Bolt bearing on plate Bolt bearing on plate

Conservatively based on Conservatively based on
Bolt Spacing = 3 in.; oversized holes, Bolt Spacing = 3 in.; oversized holes,
60.9 kips/in.)( 0.375 in.) Manualφnr = ( 91.4 kips/in. )( 0.375 in. ) nr / Ω= ( Table 7-5
\= 34.3 kips > 14.6 kips = 22.8 kips > 9.74 kips

Based on Edge Distance = 2 in.; oversized Based on Edge Distance = 2 in.; oversized
holes, holes,
47.9 kips/in. )( 0.375 in. ) Manualφnr = ( 71.8 kips/in. )( 0.375 in. ) nr / Ω= (
Table 7-6 = 26.9 kips > 14.6 kips = 18.0 kips > 9.74 kips

Bolt bearing on flange Bolt bearing on flange

Conservatively based on Conservatively based on
Bolt Spacing = 3 in.; standard holes, Bolt Spacing = 3 in.; standard holes,
Manual
75.6 kips/in. )( 0.645 ) Table 7-5φnr = (104 kips/in.)( 0.645 in.) nr / Ω= (
\= 67.0 kips > 14.6 kips = 48.8 kips > 9.74 kips

Based on edge distance = 2 in.; standard Based on edge distance = 2 in.; standard
holes, holes,

Manual 57.3 kips/in. )( 0.645 in. )φnr = ( 85.9 kips/in. )( 0.645 in. ) nr / Ω= ( Table 7-6
\= 55.4 kips > 14.6 kips = 37.0 kips > 9.74 kips

Bolt Shear Strength Bolt Shear Strength

Based on ASTM A325-N; single shear Based on ASTM A325-N; single shear
Manual
φnr = 28.3 kips > 14.6 kips nr / Ω= 18.8 kips > 9.74 kips Table 7-1

<!-- p. 430 -->

IIC-58

Note: The final layout for the connection is as follows:

Note that because the difference in depths between the top chord and the vertical and diagonal
members, x in. loose shims are required on each side of the shallower members.

<!-- p. 431 -->

IID-1

Chapter IID
Miscellaneous Connections

This section contains design examples on connections in the AISC Steel Construction Manual.
that are not covered in other sections of AISC Design Examples.

<!-- p. 432 -->

IID-2

Example II.D-1 Prying Action in Tees and in Single Angles

Given:

Design a WT tension-hanger connection between a 2L3×3×c tension member and a W24×94
beam connection to support the following loads:

PD = 13.5 kips
PL = 40 kips

Use w-in. diameter ASTM A325-N bolts and 70 ksi electrodes.

Material Properties:

Hanger ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Beam W24×94 ASTM A992 Fy = 50 ksi Fu = 65 ksi Table 2-3
Angles 2L3×3×c ASTM A36 Fy = 36 ksi Fu = 58 ksi

Geometric Properties:

Beam W24×94 d = 24.3 in. tw = 0.515 in. bf = 9.07 in. tf = 0.875 in. Manual
Angles 2L3×3×c A = 3.55 in.2 x = 0.860 in. Tables 1-1,
1-7, and
1-15

Solution:

LRFD ASD
uP = 1.2(13.5 kips) + 1.6(40 kips) = 80.2 kips aP = 13.5 kips + 40 kips = 53.5 kips

<!-- p. 433 -->

IID-3

Check tension yielding of angles Eqn. D2-1

Rn = Fy Ag = (36 ksi)(3.55 in.2 ) = 128 kips

LRFD ASD
128 kips
Rn / Ω= φRn = 0.90(128 kips) 1.67

\= 115 kips > 80.2 kips = 76.6 kips > 53.5 kips
Try 4-in. fillet welds Try 4-in. fillet welds

uP 80.2 kips aP 53.5 kips Lmin = = Lmin = =
1.392 D 1.392(4 sixteenths) 0.928 D 0.928(4 sixteenths)

\= 14.4 in. = 14.4 in.

Use four 4-in. welds (16 in. total), one at Use four 4-in. welds (16 in. total), one at
each toe and heel of each angle. each toe and heel of each angle.

Check tension rupture of angles

Calculate the effective net area

x 0.860 in. Table D3.1
U = 1 − = 1 − = 0.785 Case 2 L 4 in.

2Ae = AnU = (3.55 in.2 ) ( 0.785) = 2.80 in. Eqn. D2-2
LRFD ASD
φ = 0.75 Ω= 2.00
Rn = Fu Ae = (58 ksi)(2.80 in.2 ) = 163 kips Rn = Fu Ae = (58 ksi)(2.80 in.2 ) = 163 kips
163
φ t Rn = 0.75(163) Rn / Ω=t
2.00 .
\= 122 kips > 80 kips o.k. = 81.5 kips > 53.5 kips o.k.
Select a preliminary WT using beam gage Select a preliminary WT using beam gage

g = 4 in. g = 4 in.

With four w-in. diameter ASTM A325-N With four w-in. diameter ASTM A325-N
bolts, bolts,

Pu 80 kips Pa 53.5 kips Manual
Tu = rut = = = 20 kips/bolt Ta = rat = = = 13.4 kips/bolt Table 7-2 n 4 n 4

B = φrn = 29.8 kips > 20 kips o.k. B = rn / Ω= 19.9 kips > 13.4 kips o.k.

<!-- p. 434 -->

IID-4

With four bolts, the maximum effective length is 2g = 8 in. Thus, there are 4 in. of tee length
tributary to each pair of bolts and

LRFD ASD
2 bolts(20 kips/bolt) 2 bolts(13.4 kips/bolt)
\= 10.0 kips/in. = 6.7 kips/in.
4 in. 4 in.

The minimum depth WT that can be used is equal to the sum of the weld length plus the weld
size plus the k-dimension for the selected section. From Manual Table 1-8 with an assumed
b = 4 in./2 = 2 in., t 0 ≈ 1116 in., and d min = 4 in. + 14 in. + k ≈ 6 in., appropriate selections
include:

WT6×39.5 WT8×28.5
WT7×34 WT9×30

Manual
Try WT8×28.5; bf = 7.12 in., tf = 0.715 in., tw = 0.430 in. Table 1-8

Check prying action
Manual
Part 9
g − t w (4 in. − 0.430 in.)b = = = 1.79 in. > 1 14 -in. entering and tightening clearance, o.k.
2 2

fb − g (7.12 in. − 4 in.)
a = = = 1.56 in.
2 2

Since a = 1.56 in. \< 1.25b = 2.24 in., use a = 1.56 in.

d ⎛ 34 in. ⎞
b ' = b − = 1.79 in. − ⎜ ⎟ = 1.42 in. 2 ⎝ 2 ⎠

d ⎛ 34 in. ⎞
a ' = a + = 1.56 in. + ⎜ ⎟ = 1.94 in. 2 ⎝ 2 ⎠

b ' 1.42 in.
ρ= = = 0.732
a ' 1.94 in.

LRFD ASD
1 ⎛ B ⎞ 1 ⎛ 29.8 kips/bolt ⎞ 1 ⎛ B ⎞ 1 ⎛ 19.9 kips/bolt ⎞
β= ⎜ − 1⎟ = ⎜ − 1⎟ β= ⎜ − 1⎟ = ⎜ − 1⎟ ρ⎝ T ⎠ 0.732 ⎝ 20 kips ⎠ ρ⎝ T ⎠ 0.732 ⎝ 13.4 kips ⎠

\= 0.669 = 0.663

d ' ⎛ 1316 in. ⎞
δ = 1 − = 1 − ⎜ ⎟ = 0.797 p ⎝ 4 in. ⎠

<!-- p. 435 -->

IID-5

Since β\< 1.0,
LRFD ASD
1 ⎛ β ⎞ 1 ⎛ β ⎞
α' = ⎜ ⎟ ≤ 1.0 α' = ⎜ ⎟ ≤ 1.0
δ⎝ 1 − β⎠ δ⎝ 1 − β⎠

1 ⎛ 0.669 ⎞ 1 ⎛ 0.663 ⎞
\= ⎜ ⎟ = ⎜ ⎟ 0.797 ⎝ 1 − 0.669 ⎠ 0.797 ⎝ 1 − 0.663 ⎠

\= 2.54 ∴ α' = 1.0 = 2.47 ∴ α' = 1.0

4.44Tb ' 6.66Tb '
t min = t min =
pFu (1 +δα') pFu (1 +δα')

4.44(20 kips/bolt)(1.42 in.) 6.66(13.4 kips/bolt)(1.42 in.)
\= =
(4 in.)(65 ksi)[1 + (0.797)(1.0)] (4 in.)(65 ksi)[1 + (0.797)(1.0)]

\= 0.521 in. \< ft = 0.715 in. o.k. = 0.521 in. \< ft = 0.715 in. o.k.

Check tension yielding of the tee stem on the Whitmore section Manual
Part 9
The effective width of the tee stem (which cannot exceed the actual width of 8 in.) is

Lw = 3 in. + 2(4 in.)(tan 30 D ) ≤ 8 in.

\= 7.62 in.

and the nominal strength is determined as

LRFD ASD
φ = 0.90 Ω= 1.67
Rn = Fy Ageff = (50 ksi)(7.62 in.)(0.430 in.) = 164 kips Rn = Fy Ageff = (50 ksi)(7.62 in.)(0.430 in.) = 164 kips Eqn. D2-1

Manual
164
φRn = 0.90(164) = 147 kips > 80 kips o.k. Rn / Ω= = 98.2 kips > 53.5 kips o.k. Part 9
1.67
Check shear rupture of the base metal along the toe and heel of each weld line

6.19 D
t min =
Fu
⎛ 4 ⎞
\= 6.19 ⎜ ⎟ ⎝ 65 ksi ⎠
\= 0.381 in.\< 0.430 in. o.k.

Check block shear rupture of the tee stem

Since the angles are welded to the WT-hanger the gross area shear yielding will control.

2Agv = ( 2 welds )( 4 in.)( 0.430 in.) = 3.44 in.

<!-- p. 436 -->

IID-6

Tension stress is uniform, therefore Ubs = 1.0.
Table D3.1
2Ant = Ag = 1.0 ( 3 in.)( 0.430 in.) = 1.29 in.

Rn = 0.6FuAnv+UbsFuAnt ≤ 0.6FyAgv+UbsFuAnt

2 2Rn = 0.6 Fy Agv + U bs Fu Ant = 0.6 ( 50 ksi )( 3.44 in. ) + 1.0 ( 65 ksi )(1.29 in. ) = 187 kips Eqn. J4-5

LRFD ASD
φ = 0.75 Ω= 2.00
187
φRn = 0.75(187) = 140 kips > 80 kips o.k. Rn / Ω = = 93.5 kips > 53.5 kips o.k.
2.00

Note: Alternately, a WT tension hanger could be selected with a flange thickness to reduce the
effect of prying action to an insignificant amount, i.e., uq ≈ 0. Assumsing b ' = 1.42 in.

LRFD ASD
4.44Tb ' 6.66Tb '
t min = t min =
pFu pFu

4.44(20 kips/bolt)(1.42 in.) 6.66(13.4 kips/bolt)(1.42 in.)
\= =
(4 in./bolt)(65 ksi) (4 in./bolt)(65 ksi)

\= 0.696 in. = 0.698 in. Manual
Table 1-8
Try WT9×35.5 Try WT9×35.5

tf = 0.810 in. > 0.696 in. o.k. tf = 0.810 in. > 0.698 in. o.k.

tw = 0.495 in. > 0.430 in. o.k. tw = 0.495 in. > 0.430 in. o.k.

bf = 7.64 in. > 7.12 in. o.k. bf = 7.64 in. > 7.12 in. o.k.

<!-- p. 437 -->

IID-7

Example II.D-2 Beam Bearing Plate

Given:

A W18×50 beam with a dead load end reaction of 15 kips and a live load end reaction of 45
kips is supported by a 10-in. thick concrete wall.

If the beam has Fy = 50 ksi, the concrete has f ‘c = 3 ksi, and the bearing plate has Fy = 36 ksi,
determine:

a. if a bearing plate is required if the beam is supported by the full wall thickness,
b. the bearing plate required if N = 10 in. (the full wall thickness),
c. the bearing plate required if N = 6 in. and the bearing plate is centered on the thickness of
the wall.

Material Properties:

Beam W18×50 ASTM A992 Fy = 50 ksi Fu = 65 ksi Manual
Bearing Plate (if required) ASTM A36 Fy = 36 ksi Fu = 58 ksi Tables 2-3
Concrete Wall f’c = 3 ksi and 2-4

Geometric Properties:

Beam W18×50 d = 18.0 in. tw = 0.355 in. bf = 7.50 in. tf = 0.570 in. Manual
k = 0.972 in. k1 = 13/16 in. Table 1-1
Concrete Wall h = 10 in.

<!-- p. 438 -->

IID-8

Solution A:

LRFD ASD
Ru = 1.2(15 kips) + 1.6(45 kips) = 90 kips Ra = 15 kips + 45 kips = 60 kips

Check local web yielding Check local web yielding

Ru − φR1 Ra − R1 / Ω Manual Nreq = ≥ k Nreq = ≥ k Table 9-4 φR2 R2 / Ω

90 kips - 43.1 kips 60 kips - 28.8 kips = ≥ 0.972 in. = ≥ 0.972 in.
17.8 kips/in. 11.8 kips/in.

\= 2.63 in. \< 10 in. o.k. = 2.64 in. \< 10 in. o.k.

Check web crippling Check web crippling

N 10 in. N 10 in.
\= =
d 18.0 in. d 18.0 in.

\= 0.556 = 0.556

N N
Since > 0.2, Since > 0.2,
d d

Ru - φR5 Ra - R5 / Ω Nreq = Nreq =
φR6 R6 / Ω
Manual
Table 9-4
90 kips-52.0 kips 60 kips - 34.7 kips
\= =
6.30 kips/in. 4.20 kips/in.

\= 6.03 in. \< 10 in. o.k. = 6.03 in. \< 10 in. o.k.

N N
Verify > 0.2, Verify > 0.2,
d d

N N
\= 0.335 > 0.2 o.k. = 0.335 > 0.2 o.k.
d d

Check the bearing strength of concrete Check the bearing strength of concrete

cφ = 0.60 Ω=c 2.50

φcPp = φc(0.85f’c)A1 Pp/Ωc = ( 0.85f’c) A1/Ωc
Eqn. J8-1
\= 0.60 (0.85)(3 ksi)(7.50 in.×10 in.) = (0.85)(3 ksi)(7.50 in.×10 in.)/2.50

\= 115 kips > 90 kips o.k. = 76.5 kips > 60 kips o.k.

<!-- p. 439 -->

IID-9

Check beam flange thickness

LRFD ASD
Determine cantilever length Determine cantilever length Manual
Part 14
fb 7.50 fb 7.50
n = - k = - 0.972 in. = 2.78 in., n = - k = - 0.972 in. = 2.78 in.,
2 2 2 2

Determine bearing pressure Determine bearing pressure

Ru Ra fp = fp =
A1 A1

Determine cantilever moment Determine cantilever moment

Ru n 2 Ra n 2 M u = M a =
2 A1 2 A1

Z = 14 t 2 Z = 14 t 2
⎛ t 2 ⎞ ⎛ t 2 ⎞
M ≤ FyZ ≤ Fy ⎜ ⎟ M ≤ FyZ ≤ Fy ⎜ ⎟ ⎝ 4 ⎠ ⎝ 4 ⎠
4 M u 2 Ru n 2 Ω 4 M a Ω 2 Ra n 2 treq = = treq = =
φFy φA1 Fy Fy A1 Fy

φ = 0.90 Ω = 1.67

2.22 Ru n 2 3.33 Ra n 2 tmin = tmin =
A1 Fy A1 Fy

2.22(90 kips)(2.78 in.) 2 3.33(60 kips)(2.78 in.) 2
\= =
(7.50 in. × 10 in.)(50 ksi) (7.50 in. × 10 in.)(50 ksi)

\= 0.643 in. > 0.570 in. n.g. = 0.643 in. > 0.570 in. n.g.

A bearing plate is required. A bearing plate is required.

<!-- p. 440 -->

IID-10

Solution B:

N = 10 in.

From Solution A, local web yielding and web crippling are not critical.
LRFD ASD
Calculate the required bearing-plate width. Calculate the required bearing-plate width.

cφ = 0.60 Ω=c 2.50

Ru Ra Ω c
A1 req = ' A1 req = ' Eqn. J8-1
φc (0.85 f c ) (0.85 f c )

90 kips 60 kips(2.50)
\= =
0.60(0.85 x 3 ksi) (0.85 x 3 ksi)

\= 58.8 in2 = 58.8 in2

A1 req A1 req
B req = B req =
N N

58.8 in.2 58.8 in. 2
\= =
10 in. 10 in.

\= 5.88 in. = 5.88 in.

Use B = 8 in. (least whole-inch dimension Use B = 8 in. (least whole-inch dimension
that exceeds bf) that exceeds bf)

Calculate required bearing-plate thickness. Calculate required bearing-plate thickness. Manual
Part 14
B B
n = - k n = - k
2 2

8 in. 8 in.
\= - 0.972 in. = - 0.972 in.
2 2

\= 3.03 in. = 3.03 in.

2.22 Ru n 2 3.33 Ra n 2 tmin = tmin =
A1 Fy A1 Fy

2.22(90 kips)(3.03 in.) 2 3.33(60 kips)(3.03 in.) 2
\= =
(10 in. × 8 in.)(36 ksi) (10 in. × 8 in.)(36 ksi)

\= 0.799 in. = 0.799 in.

Use PL1×10×0’-8 Use PL1×10×0’-8

<!-- p. 441 -->

IID-11

Solution C:

N = 6 in.

From Solution A, local web yielding and web crippling are not critical.

Try B = 8 in.

A1 = B × N = (8 in.)(6 in.) = 48 in.2

To determine the dimensions of the area A2, the load is spread into the concrete at a slope of 2:1 until an edge or
the maximum condition A2 / A1 ≤ 2 is met. There is also a requirement that the area A2 be geometrically
similar to A1. The 6-in. dimension spreads 2 in. to each side to meet the concrete edge. Thus, the 8-in.
dimension can also be spread 2 in. to each side. Therefore,

N1 = 6 in. + 2(2 in.) = 10 in.

B1 = 8 in. + 2(2 in.) = 12 in.

A2 = B1 × N1 = 12 in. (10 in.) = 120 in.2

Check A2 / A1 = 1.58 ≤2 o.k.
LRFD ASD
cφ = 0.60 Ω=c 2.50
1 ⎛ Ru ⎞ 2 1 ⎛ Ra Ω c ⎞ 2
A1 req = ⎜ ' ⎟ A1 req = ⎜ ' ⎟
A2 ⎝ φc (0.85 f c ) ⎠ A2 ⎝ (0.85 f c ) ⎠ Eqn. J8-2

1 ⎛ 90 kips ⎞ 2 1 ⎛ 60 kips(2.50) ⎞ 2
\= 2 ⎜ ⎟ = 2 ⎜ ⎟ 120 in. ⎝ 0.60(0.85 × 3 ksi) ⎠ 120 in. ⎝ (0.85 × 3 ksi) ⎠

\= 28.8 in.2 \< 48 in.2 o.k. = 28.8 in.2 \< 48 in.2 o.k.

Calculate the required bearing-plate Calculate the required bearing-plate
thickness. thickness.

Manual
B B
n = - k n = - k Part 14
2 2
8 in. 8 in.
\= - 0.972 in. = - 0.972 in.
2 2

\= 3.03 in. = 3.03 in.

2.22 Ru n 2 3.33 Ra n 2 tmin = tmin =
A1 Fy A1 Fy
2.22(90 kips)(3.03 in.) 2 3.33(60 kips)(3.03 in.) 2
\= =
( 6 in. )( 8 in. ) (36 ksi) ( 6 in.)( 8 in.) (36 ksi)
\= 1.03 in. = 1.03 in.

Use PL14×6×0’-8 Use PL14×6×0’-8

<!-- p. 442 -->

IID-12

Example II.D-3 Slip-Critical Connection with Oversized Holes
(Designed for Slip as a Serviceability Limit State)

Given:

Determine the number of bolts required to connect, 2L3×3×4 tension member to a plate under
a beam as shown. The angles have standard holes and the plate has oversized holes per
Manual Table J3.3.

RD = 15 kips
RL = 45 kips

Use w-in. diameter ASTM A325-SC class A bolts.
Assume that the strength of the beam, angles, and plate have been checked.

Material Properties:

L3×3×4 ASTM A36 Fy = 36 ksi Fu = 58 ksi Manual
Plate Material ASTM A36 Fy = 36 ksi Fu = 58 ksi Table 2-3
and 2-4

<!-- p. 443 -->

IID-13

Solution:

LRFD ASD
Ru = (1.2)(15 kips) + (1.6)(45 kips) = 90 kips Ra = 15 kips + 45 kips = 60 kips

Design of bolts Design of bolts

Because of oversized holes the slip is a Because of oversized holes the slip is a
serviceability limit state, Class A faying serviceability limit state, Class A faying
surface, w in. diameter ASTM A325-SC surface, w in. diameter ASTM A325-SC
bolts in double shear bolts in double shear

φrn = 18.8 kips/bolt rn/ Ω = 12.6 kips/bolt Manual
Table 7-4
φRn 90 kips ( Rn / Ω ) 60 kips n = = n = =
φrn 18.8 kips/bolt ( rn / Ω ) 12.6 kips/bolt

\= 4.78 → 5 bolts = 4.76 → 5 bolts

Try (5) w-in. dia. ASTM A325-SC bolts Use (5) w-in. dia. ASTM A325-SC bolts

Check bolt shear strength Check bolt shear strength

Fv Ab Manual
φrn = φFv Ab = 31.8 kips/bolt rn / Ω= = 21.2 kips/bolt Table 7-1 Ω

rn
φRn = φrn n Rn / Ω= n = (21.2 kips/bolt)(5 bolts) = (31.8 kips/bolt)(5 bolts) Ω

\= 106 kips > 60 kips o.k.
\= 159 kips > 90 kips o.k.

Try, PL a in. Try, PL a in.

Check bolt bearing strength on plate Check bolt bearing strength on plate
Eqn J3-6a
φrn = φ(1.2LctFu) M φ(2.4dtFu) rn / Ω = (1.2LctFu)/ Ω M (2.4dtFu)/ Ω

φ = 0.75 Ω = 2.00

Oversized holes, bolt spacing = 3 in. Oversized holes, bolt spacing = 3 in.

φrn = (78.3 kips/in.)(a in.) rn / Ω = (52.2 kips/in.)(a in.) Manual
Table 7-5
\= 29.4 kips/bolt = 19.6 kips/bolt

Oversized holes, edge distance = 14 in. Oversized holes, edge distance = 14 in.

φrn = (40.8 kips/in.)(a in.) rn / Ω = (27.2 kips/in.)(a in.) Manual
Table 7-6
\= 15.3 kips/bolt = 10.2 kips/bolt

15.3 kips/bolt \< 29.4 kips/bolt 10.2 kips/bolt \< 19.6 kips/bolt

<!-- p. 444 -->

IID-14

φRn = φrn n Rn / Ω= rn n / Ω

\= (15.3 kips/bolt)(5 bolts) = (10.2 kips/bolt)(5 bolts)

\= 76.5 kips \< 80 kips n.g. = 51.0 kips \< 80 kips n.g.

Try 6 bolts Try 6 bolts

φRn = φrn n Rn / Ω= rn n / Ω

\= (15.3 kips/bolt)(6 bolts) = (10.2 kips/bolt)(6 bolts)

\= 91.8 kips > 80 kips o.k. = 61.2 kips > 60 kips o.k.

Use 6 bolts Use 6 bolts

<!-- p. 445 -->

III-1

III. SYSTEM DESIGN EXAMPLES

DESIGN OF SELECTED MEMBERS
AND LATERAL ANALYSIS
OF A 4 STORY BUILDING

INTRODUCTION

This section illustrates the load determination and selection of members that are part of the gravity and lateral
frame of a typical 4-story building. The design is completed in accordance with the 2005 AISC Specification for
Structural Steel Buildings and the 13th Edition AISC Steel Construction Manual. Building code requirements are
taken from International Building Code 2003 as the Design Code and loading criteria are based on SEI/ASCE 702.

This section includes:
• Analysis and design of a typical steel frame for gravity loads
• Analysis and design of a typical steel frame for lateral loads
• Examples illustrating each of the three methods for satisfying the stability provisions of AISC
Specification Chapter C.

The building being analyzed in this design example is located in a Midwestern city with moderate wind and
seismic loads. The criteria for these minimum loads are given in the description of the design example

CONVENTIONS

The following conventions are used throughout this example:

\1. Beams or columns that have similar, but not necessarily identical, loads are grouped together. This is
done to simplify the selection process, because such grouping is generally a more economical practice for
design, fabrication, and erection.

\2. Certain calculations, such as design loads for snow drift, which might typically be determined using a
spreadsheet or structural analysis program, are summarized and then incorporated into the analysis. This
simplifying feature allows the design example to illustrate concepts relevant to the member selection
process.

\3. Two commonly used deflection calculations, for uniform loads, have been rearranged so that the
conventional units in the problem can be directly inserted into the equation for steel design. They are as
follows:

5 w kip/in.(l in.) 4 w kip/ft(l ft) 4
Simple Beam: ∆ = 4 = 4 384(29,000 ksi)(I in.) 1290(I in.)
w kip/in.(l in.) 4 w kip/ft(l ft) 4
Beam Fixed at both Ends: ∆ = 4 = 4 384(29,000 ksi)(I in.) 6450(I in.)

<!-- p. 446 -->

III-2

DESIGN SEQUENCE

The design sequence is presented as follows:

\1. General description of the building including geometry, gravity loads, and lateral loads.

\2. Roof member design and selection.

\3. Floor member design and selection.

\4. Column design and selection for gravity loads.

\5. Wind load determination.

\6. Seismic load determination.

\7. Horizontal force distribution to the lateral frames.

\8. Preliminary column selection for the moment frames and braced frames.

\9. Seismic load application to lateral systems.

\10. Second order effects (P-delta) analysis

<!-- p. 447 -->

III-3

GENERAL DESCRIPTION OF THE BUILDING

Geometry

The design example is a 4-story building, comprised of 7 bays at 30 ft in the East-West (Numbered Grids)
direction and bays of 45 ft, 30 ft and 45 ft in the North-South (Lettered Grids) direction. The floor-to-floor height
for the 4 floors is 13’-6” and the height from the fourth floor to the roof (at the edge of the building) is 14’-6”.
Based on discussions with Fabricators, the same column size will be used for the whole height of the building.

Basic Building Layout

The plans of these floors and the roof are shown on sheets S2.1 thru S2.3, found at the end of this Chapter. The
exterior of the building is a ribbon window system with brick spandrels supported and back-braced with steel and
in-filled with metal studs. The spandrel wall extends 2 ft above the elevation of the edge of the roof. The window
and spandrel system is shown on design drawing Sheet S4.1.

The roof system is 1½-in. metal deck on bar joists. These bar joists are supported on steel beams as shown on
Design Drawing Sheet S2.3. The roof slopes to interior drains. The middle 3 bays have a 6-ft-tall screen wall
around them and house the mechanical equipment and the elevator over run. This area has steel beams, in place
of steel bar joists, to help carry the mechanical equipment.

The three elevated floors have 3 in. of normal weight concrete over 3-in. composite deck for a total slab thickness
of 6 in. The supporting beams are spaced at 10 ft on center. These beams are carried by composite girders in the
East-West direction to the columns. There is a 30 ft by 45 ft opening in the second floor, to create a 2-story
atrium at the entrance. These floor layouts are shown on Drawings S2.1 and S2.2. The first floor is a slab on
grade and the foundation consists of conventional spread footings.

The building includes both moment frames and braced frames for lateral resistance. The lateral system in the
North-South direction consists of Chevron braces at the end of the building, located adjacent to the stairways. In
the East-West direction there are no locations in which Chevron braces can be concealed. Consequently, the
lateral system in the East-West direction is composed of moment frames at the North and South faces of the
building.

This building is sprinklered and has large open spaces around it, and consequently does not require fire proofing
for the floors.

<!-- p. 448 -->

III-4

Wind Forces

The Basic Wind Speed is 90 miles per hour (3 second gust). Because it is located in an Office Park with
substantial parking areas around it, it will be analyzed as Wind Exposure Category C. Because it is an ordinary
(Category II) office occupancy, the wind importance factor is 1.0.

Seismic Forces

This building is located in an area where the sub-soil has been evaluated and the site class has been determined to
be Category D. The area has a short period Ss = 0.121 and a one-second period S1 = 0.060. The seismic
importance factor is 1.0, that of an ordinary office occupancy (Category II).

Roof and Floor Loads

Roof loads:

The ground snow load (pg) for this building is 20 psf. The slope of the roof is ¼ in./ft or more at all locations, but
not exceeding ½ in./ft. Consequently, 5 psf rain-on-snow surcharge is to be considered, but no ponding instability
design calculations are not required. This roof can be designed as a fully exposed roof, but, per ASCE 7 Section
7.3, cannot be designed for less than pf = (I)pg = 0.020 kip/ft2 snow live load. Snow drift will be applied at the
edges of the roof and at the screen wall around the mechanical area.

Floor Loads:

The basic live load for the floor is 50 psf. An additional partition live load of 20 psf will be applied. However,
because the locations of partitions and, consequently, corridors are not known, and will be subject to change, the
entire floor will be designed for a live load of 80 psf. This live load will be reduced, based on type of member
and area per the IBC provisions for live-load reduction.

ROOF MEMBER DESIGN AND SELECTION

Calculate dead load and live load

Dead Load
Roofing = 0.005 kip/ft2
Insulation = 0.002 kip/ft2
Deck = 0.002 kip/ft2
Beams = 0.003 kip/ft2
Joists = 0.003 kip/ft2
Misc. = 0.005 kip/ft2
Total = 0.020 kip/ft2

Live Load
Snow = 0.020 kip/ft2 ASCE 7
Rain on Snow = 0.005 kip/ft2 Section 7.3
Total = 0.025 kip/ft2 and 7.10
Note: In this design, the Rain and Snow Load is greater than the Roof Live Load

The deck for this design example is 1½ in., wide rib, 22 gage, painted roof deck, placed in a pattern of 3
continuous spans minimum. The general joist layout is 6 ft on center. At 6 ft on center, this deck has an
allowable total load capacity of 0.071 kip/ft2. This will require changing 2 spaces at 6 ft to a 5 ft, 4 ft, 3 ft pattern
at the ends of the Mechanical area. The roof diaphragm and roof loads extend 6 in. past the centerline of grid as
shown on Drawing S4.1

<!-- p. 449 -->

III-5

Flat roof snow load = 0.020 kip/ft2, Density γ = 0.0166 kip/ft2, hb = 1.20 ft ASCE 7
Section 7.8
Summary of Drifts

Upwind Roof Proj. Max. Drift Max Drift ASCE 7
Length (lu) Height Load Width (W) Figure 7-8

Side Parapet 121 ft 2 ft 0.0132 kip/ft2 6.36 ft Summary
End Parapet 211 ft 2 ft 0.0132 kip/ft2 6.36 ft from Spread
Screen Wall 60.5 ft 6 ft 0.0305 kip/ft2 7.35 ft Sheet

SELECT ROOF JOISTS

Layout loads and size joists

User Note: Joists are normally designed by ASD and are designed and selected in this manner here.

The 45-ft side joist with the heaviest loads is shown below along with its end reactions and maximum moment:

Because the load is not uniform, select a 24KCS4 JOIST AT 16.5 plf, which has an allowable moment of 92.3
kip-ft and an allowable shear of 8.40 kips.

The standard 30 ft joist in the middle bay will have a uniform load of

w = (0.020 kip/ft2 + 0.025 kip/ft2)(6 ft) = 0.270 kip/ft.

Per joist catalog, select an 18K5 joist at 7.7 plf.

Note: the first joist away from the screen wall and the first joist away from the end of the building must account
for snow drift. An 18K7 joist will be used in these locations.

<!-- p. 450 -->

III-6

SELECT ROOF BEAMS

Calculate loads and select beams in the mechanical area

For the beams in the mechanical area, the mechanical units could weigh as much as 0.060
kip/ft2. Use 0.040 kip/ft2 for additional live load, which will account for the mechanical units
and any snow drift which could occur in the mechanical area. The beams in the mechanical area
are at 6 ft on center.

Calculate minimum Ix to limit deflection to 1/360 = 1 in., because plaster ceiling will be used IBC Table
in the lobby area. Use 0.040 kip/ft2 as an estimate of the snow load, including some drifting 1604.3
that could occur in this area, for deflection calculations.

0.240kip/ft(30 ft) 4
Ireq (Live Load)= = 151 in.4
1290(1 in.)

Calculate the required strengths and select the beams in the mechanical area

LRFD ASD
Wu = 6 ft[1.2 (0.020 kip/ft2) Wa = 6 ft(0.020 kip/ft2
\+1.6(0.025 kip/ft2 + 0.040 kip/ft2)] +0.025 kip/ft2 + 0.040 kip/ft2)
\= 0.768 kip/ft = 0.510 kip/ft

0.768 kip/ft(30 ft) 2 0.510 kip/ft(30 ft) 2
Mu = = 86.4 kip-ft Ma = = 57.4 kip-ft
8 8
Select a W14×22, which has an available Select a W14×22, which has an available
Manual moment strength of 125 kip-ft and moment strength of 82.8 kip-ft and
Table 3-2 an Ix of 199 in.4 an Ix of 199 in.4

30 ft 30 ft Ru = ( 0.768 kip/ft) ) = 11.5 kips Ra = ( 0.510 kip/ft) ) = 7.65 kips
2 2

φbVn = 94.8 kips > 11.5 kips o.k. Vn/Ωb = 63.2 kips > 7.65 kips o.k.

Note: a W12×22 beam would also meet all criteria, but a 14 in. beam was selected so that
consistent beam sizes could be used throughout the building.

<!-- p. 451 -->

III-7

SELECT BEAMS AT THE END OF THE BUILDING

The beams at the ends of the building carry the brick spandrel panel and a small portion of roof
load. Because there is continuous glass underneath this window, limit live load deflection to ¼in. total movement. In addition, per AISC Design Guide 3, Second Edition, limit deflection due
to spandrel weight to the L/480 or a-in. maximum. In calculating the wall loads, the brick
weight is taken as 55 lb/ft, and the glass weight is taken as 90 lb/ft. The spandrel panel weight is
approximately

w = 7.50 ft (0.055 kip/ft2) = 0.413 kip/ft.

the dead load from the roof is equal to

w = 3.5 ft (0.020 kip/ft2) = 0.070 kip/ft

and the live load from the roof can be conservatively taken as

w = 3.5 ft (0.025 kip/ft2 + 0.0132 kip/ft2) = 0.134 kip/ft.

to account for the maximum snow drift as a uniform load

Assume the beams are simple spans of 22.5 ft.

Calculate minimum Ix to limit live load deflection to ¼ in.
0.134 kip/ft(22.5 ft) 4
Ireq = =106 in.4
1290(0.25 in.)

Calculate minimum Ix to limit spandrel weight deflection to a in.
0.413 kip/ft(22.5 ft) 4
Ireq = = 218 in.4
1290(0.375 in.)

The loading diagram is as follows

Calculate the required strengths and select the beams for the roof ends

LRFD ASD
Wu =1.2 ( 0.070 kip/ft2 + 0.413 kip/ft) Wa = (0.070 kip/ft2 + 0.413 kip/ft)
\+1.6(0.134 kip/ft2) + 0.134 kip/ft2
\= 0.794 kip/ft = 0.617 kip/ft

<!-- p. 452 -->

III-8

0.794 kip/ft(22.5 ft) 2 0.617 kip/ft(22.5 ft) 2
Mu = = 50.2 kip-ft Ma = = 39.0 kip-ft
8 8
Select W16×26, which has an available Select W16×26, which has an available Manual
moment strength of 166 kip-ft and an Ix of moment strength of 110 kip-ft and an Ix of Table 3-2
301 in.4 301 in.4

SELECT THE BEAM ALONG THE SIDE OF THE BUILDING

The beams along the side of the building carry the spandrel panel and a substantial roof dead load and live load.
The spandrel beam is over glass, therefore, limit the live load deflection to ¼ in. In addition, per AISC Design
Guide 3, Second Edition, limit deflection due to spandrel weight to the L/480 or a in. maximum. These beams
will be part of the moment frames on the side of the building and therefore will be designed as fixed at both ends.
The roof dead load and live load to this edge beam is equal to the joist end dead load and live load reaction.
Treating this as a uniform load, divide this by the joist spacing.

wD = 2.76 kips/6 ft = 0.460 kip/ft. wL = 3.73 kips/6 ft = 0.622 kip/ft.

Calculate minimum Ix to limit the live load deflection to ¼ in.

4 ( 0.622 kip/ft ) (30 ft)
Ireq = = 312 in.4
6450(0.25 in.)

Calculate minimum Ix to limit the spandrel weight deflection to a in.

4 ( 0.413 kip/ft ) (30 ft)
Ireq = = 138 in.4
6450(0.375 in.)

<!-- p. 453 -->

III-9

Calculate the required strengths and select the beams for the roof sides

LRFD ASD
Wu =1.2 (0.460 kip/ft2 + 0.413 kip/ft) Wa = (0.460 kip/ft2 + 0.413 kip/ft)
\+1.6(0.622 kip/ft2) + 0.622 kip/ft2
\= 2.04 kip/ft = 1.50 kip/ft

2.04 kip/ft(30 ft) 2 1.50 kip/ft(30 ft) 2
Mu = = 153 kip-ft Ma = = 113 kip-ft
12 12
For Lb = 6 ft and Cb = 1.0, select W16×31, For Lb = 6 ft and Cb = 1.0, select W16×31, Manual
which has an available moment strength of which has an available moment strength of
Table 3-10 183 kip-ft and an Ix of 375 in.4 122 kip-ft and an Ix of 375 in.4

Note: This roof beam may need to be upsized during the lateral load analysis to increase the
stiffness and strength of the member and improve lateral frame drift performance.

<!-- p. 454 -->

III-10

SELECT THE BEAMS ALONG THE INTERIOR LINES OF THE BUILDING

There are 3 individual beam loadings that occur along grids C and D. The beams from 1 to 2
and 7 to 8 have a uniform snow load except for the snow drift at the end at the parapet. The
snow drift from the far ends of the 45 foot joists is negligible. The beams from 2 to 3 and 6 to
7 are the same as the first group, except they have snow drift at the screen wall. The loading
diagrams are shown below. A summary of the moments, left and right reactions, and required
Ix to keep the live load deflection to equal or less than the span divided by 240 (or 1.50 in.) is IBC Table
given below. 1604.3

Note: by footnote G, for steel structural members, the dead load shall be taken as zero for D +
L deflection calculation combination.

<!-- p. 455 -->

III-11

Summary of required strengths and required moment of inertia

LRFD ASD
Grids 1 to 2 and 7 to 8(opposite hand) Grids 1 to 2 and 7 to 8(opposite hand)

Ru (left) = 1.2(11.6 kips) + 1.6(16.1 kips) Ra (left) = 11.6 kips + 15.6 kips
\= 38.8 kips = 27.2 kips

Ru (right) = 1.2(11.3 kips) + 1.6(14.2 kips) Ra (right) = 11.3 kips + 14.2 kips
\= 36.1 kips = 25.5 kips

Mu = 1.2(84.3 kip-ft) + 1.6(107 kip-ft) Ma = 84.3 kip-ft + 107 kip-ft Manual
\= 272 kip-ft = 191 kip-ft Table 3-10

(0.938 klf)(30 ft) 4 (0.938 klf)(30 ft) 4
I x req'd = I x req'd =
1290 (1.5 in.) 1290 (1.5 in.)
\= 393 in. 4 = 393 in. 4

For Lb = 6 ft and Cb = 1.0, select W21×44 For Lb = 6 ft and Cb = 1.0, select W21×44 Manual
which has an available moment of 333 kip-ft which has an available moment of 222 kip-ft Table 3-10
and Ix = 843 in.4 and Ix = 843 in.4

Grids 2 to 3 and 6 to 7(opposite hand) Grids 2 to 3 and 6 to 7(opposite hand)

Ru (left) = 1.2(11..3 kips) + 1.6(14.3 kips) Ra (left) = 11.3 kips + 14.3 kips
\= 36.6 kips = 25.6 kips

Ru (right) = 1.2(11.3 kips) + 1.6(17.9) kips) Ra (right) = 11.3 kips + 17.9 kips
\= 42.1 kips = 29.2 kips

Mu = 1.2(84.4 kip-ft) + 1.6(109 kip-ft) Ma = 84.4 kip-ft + 109 kip-ft
\= 278 kip-ft = 195 kip-ft

(0.938 klf)(30 ft) 4 (0.938 klf)(30 ft) 4
I x req'd = I x req'd =
1290 (1.5 in.) 1290 (1.5 in.)
\= 393 in. 4 = 393 in. 4

For Lb = 6 ft and Cb = 1.0, select W21×44 For Lb = 6 ft and Cb = 1.0, select W21×44
which has an available moment of 333 kip-ft which has an available moment of 222 kip-ft
and Ix = 843 in.4 and Ix = 843 in.4

The third individual beam loading occurs at the beams from 3 to 4, 4 to 5, and 5 to 6. This is the
heaviest load.

<!-- p. 456 -->

III-12

SELECT THE BEAMS ALONG THE SIDES OF THE MECHANICAL AREA

The beams from 3 to 4, 4 to 5, and 5 to 6 have a uniform snow load outside the screen walled
area, except for the snow drift at the parapet ends and the screen wall ends of the 45 foot joists.
Inside the screen walled area the beams support the mechanical equipment. A summary of the
moments, left and right reactions, and required Ix to keep the live load deflection to equal or IBC Table
less than the span divided by 240 (or 1.50 in.) is given below. 1604.3

Note: by footnote g, for steel structural members, the dead load shall be taken as zero for D + IBC Table
L deflection calculation load combination. 1604.3

LRFD ASD
Wu =1.2 (0.750 kip/ft2) +1.6(1.57 kip/ft2) Wa = 0.750 kip/ft + 1.57 kip/ft2
\= 3.41 kip/ft = 2.32 kip/ft

3.41 kip/ft(30 ft) 2 2.32 kip/ft(30 ft) 2
Mu = = 384 kip-ft Ma = = 261 kip-ft
8 8

30 ft 30 ft Ru = ( 3.41 kip/ft) ) = 51.2 kips Ru = ( 2.32 kip/ft) ) = 34.8 kips
2 2

1.57 kip/ft(30.0 ft) 4 1.57 kip/ft(30.0 ft) 4
Ix req’d = = 393 in.4 Ix req’d = = 393 in.4
1290(1.50 in.) 1290(1.50 in.)

For Lb = 6 ft and Cb = 1.0, select W21×48, For Lb = 6 ft and Cb = 1.0, select W21×48, Manual which has an available moment strength of which has an available moment strength of
Table 3-10 398 kip-ft, an available end shear of 217 kips 265 kip-ft, an available end shear of 144 kips
and an Ix of 959 in.4 and an Ix of 959 in.4

<!-- p. 457 -->

III-13

FLOOR MEMBER DESIGN AND SELECTION

Calculate dead load and live load

Dead Load
Slab and Deck = 0.057 kip/ft2 Steel Deck
Beams (est.) = 0.008 kip/ft2 Institute
Misc. ( ceiling, mechanical, etc.) = 0.010 kip/ft2 Diaphragm
Total = 0.075 kip/ft2 Design
Manual
Live Load
Total (can be reduced for area per IBC 2003) = 0.080 kip/ft2 IBC Section
1607.9

The floor and deck will be 3 in. of normal weight concrete, cf ' = 4 ksi, on 3 in. 20 gage, galvanized, composite
deck, laid in a pattern of 3 or more continuous spans. The total depth of the slab is 6 in. The general layout for
the floor beams is 10 ft on center. At 10 ft on center, this deck has an allowable superimposed live load capacity
of 0.143 kip/ft2. In addition, it can be shown that this deck can carry a 2,000 pound load over an area of 2.5 ft by
2.5 ft (per IBC Section 1607.4). The floor diaphragm and the floor loads extend 6 in. past the centerline of grid as
shown on Drawing S4.1.

<!-- p. 458 -->

III-14

SELECT FLOOR BEAMS (composite and non-composite)

Note: There are two early and important checks in the design of composite beams. First, select a beam that either
does not require camber, or establish a target camber and moment of inertia at the start of the design process. A
reasonable approximation of the camber is between L/300 minimum and L/180 maximum (or a maximum of 1½
to 2 in.).

Second, check that the beam is strong enough to safely carry the wet concrete and a 0.020 kip/ft2 construction live
load (per ASCE 37-02), when designed by the ASCE 7 load combinations and the provisions of Chapter F of the
Specification.

SELECT TYPICAL 45 FT COMPOSITE BEAM (10 FT ON CENTER)

Find a target moment of inertia for an un-shored beam

Hold deflection to around 2 in. maximum to facilitate pouring.
0.65 kip/ft(45 ft) 4
I req ≈ = 1030 in.4
1290(2.0 in.)

Determine minimum strength to carry wet concrete and construction live load

wDL = 0.065 kip/ft2(10 ft) = 0.65 kip/ft
wLL = 0.020 kip/ft2(10 ft) = 0.20 kip/ft

Determine the required moment strength due to wet concrete only

LRFD ASD
Wu = 1.4(0.65 kip/ft) = 0.91 kip/ft Wa = 0.65 kip/ft
0.91 kip/ft(45 ft) 2 0.65 kip/ft(45 ft) 2
Mu = = 230 kip-ft Ma = = 165 kip-ft
8 8

Determine the required moment strength due to wet concrete and construction live load

LRFD ASD
Wu = 1.2(0.65 kip/ft) + 1.6(0.20 kip/ft) Wa = 0.65 kip/ft + 0.20 kip/ft
\= 1.10 kip/ft = 0.85 kip/ft
1.10 kip/ft(45 ft) 2 0.85 kip/ft(45 ft) 2
Mu = = 278 kip-ft Ma = = 215 kip-ft
8 8
controls Controls

Use Manual Table 3-2 to select a beam with Ix ≥ 1030 in.4. Select W21×50, which has Manual
Ix = 984 in.4, close to our target value, and has an available moment strength of Table 3-2
413 kip-ft (LRFD) and 274 kip-ft (ASD).

Check for possible live load reduction due to area

For interior beams KLL = 2 IBC Table
1607.9.1
The beams are at 10 ft on center, therefore the area AT = 45 ft × 10 ft = 450 ft2.
⎛ 15 ⎞
L = Lo ⎜ 0.25 + ⎟ = 0.060 kip/ft2 ≥ 0.50Lo = 0.040 kip/ft2 IBC Eqn ⎜ ⎟ ⎝ K LL AT ⎠ 16-21

<!-- p. 459 -->

III-15

Therefore use 0.060 kip/ft2.
The beam is continuously braced by the deck.

The beams are at 10 ft on center, therefore the loading diagram is as shown below.

Calculate the required moment strength
LRFD ASD
Wu = 1.2(0.75 kip/ft) = 1.6 (0.60 kip/ft) Wa = 0.75 kip/ft + 0.60 kip/ft
\= 1.86 kip/ft = 1.35 kip/ft

1.86 kip/ft(45 ft) 2 1.35 kip/ft(45 ft) 2
Mu = = 471 kip-ft Ma = = 342 kip-ft
8 8

Y2 = 6 in. – 2 in = 5.5 in.

Use Manual Table 3-19 to check W21×50 selected above. Using values of 471kip-ft (LRFD) Manual
or 342 kip-ft (ASD) and a Y2 value of 5.5 in Table 3-19
LRFD ASD
Select W21×50 beam, where Select W21×50 beam, where Manual Table
PNA = 7, Qn = 184 kips PNA = 7, Qn = 184 kips 3-19
φbMp = 599 kip-ft > 471 kip-ft o.k. Mp/Ωb = 399 kip-ft > 342 kip-ft o.k.

Determine beff
The effective width of the concrete slab is the sum of the effective widths for each side of the Specification
beam centerline which shall not exceed: Sec. I.3.1.1a

(1) one-eighth of the span of the beam, center to center of supports
45 ft
( 2 sides) = 11.3 ft.
8

(2) one-half the distance to the center line of the adjacent beam
10 ft
( 2 sides) = 10.0 ft. controls
2

(3) the distance to the edge of the slab
Not applicable

<!-- p. 460 -->

III-16

Check a

LRFD ASD
∑ Qn ∑ Qn a = ' a = '
0.85 f c b 0.85 f c b
184 kips 184 kips
\= =
0.85(4 ksi)(10 ft)(12 in./ft) 0.85(4 ksi)(10 ft)(12 in./ft)
\= 0.451 in. \< 1.0 in. o.k. = 0.451 in. \< 1.0 in. o.k.

Check end shear strength

LRFD ASD
45 ft 45 ft Manual
Ru = (1.86 kip/ft) ) = 41.9 kips Ra = (1.35 kip/ft) ) = 30.4 kips Table 3-2 2 2
φbVn = 217 kips > 41.9 kips o.k. Vn/Ωb = 145 kips > 30.4 kips o.k.

Check live load deflection

∆ LL = l 360 = ((45 ft)(12 in./ft))/360 = 1.5 in. IBC Table
1604.3

LRFD ASD
W21×50: Y2 = 5.5 in., PNA = 7 W21×50: Y2 = 5.5 in., PNA = 7
ILB = 1640 in.4 ILB = 1640 in.4 Manual
wLL l 4 0.60 kip/ft(45 ft) 4 wLL l 4 0.60 kip/ft(45 ft) 4 Table 3-20 ∆ LL = = 4 ∆ LL = = 4
1290 I LB 1290(1730 in. ) 1290 I LB 1290(1730 in. )
\= 1.10 in. \<1.5 in. o.k. = 1.16 in. \< 1.5 in. o.k.

Determine the required shear stud connectors

Using perpendicular deck with one w-in. diameter stud per rib in normal weight, 4 ksi Manual
concrete, in weak position; Qn = 17.2 kips/stud Table 3-21

LRFD ASD
∑ Qn 184 kips ∑ Qn 184 kips = = 10.7 studs / side = = 10.7 studs / side
Qn 17.2 kips/stud Qn 17.2 kips/stud

Therefore use 22 studs.

SELECT TYPICAL 30 FT COMPOSITE (OR NON-COMPOSITE) BEAM
(10 FT ON CENTER)

Find a target moment of inertia for an un-shored beam

Hold deflection to around 1.5 in. maximum to facilitate concrete placement.
0.65 kip/ft(30 ft) 4
I req ≈ = 272 in.4
1290(1.50 in.)

<!-- p. 461 -->

III-17

Determine minimum strength to carry wet concrete and construction live load

wDL = 0.065 kip/ft2(10 ft) = 0.65 kip/ft
wLL = 0.020 kip/ft2(10 ft) = 0.20 kip/ft

Determine the required moment strength due to wet concrete only

LRFD ASD
Wu = 1.4(0.65 kip/ft) = 0.91 kip/ft Wa = 0.65 kip/ft
0.91 kip/ft(30 ft) 2 0.65 kip/ft(30 ft) 2
Mu = = 102 kip-ft Ma = = 73.1 kip-ft
8 8

Determine the required moment strength due to wet concrete and construction live load

LRFD ASD
Wu = 1.2(0.65 kip/ft) + 1.6(0.20 kip/ft) Wa = 0.65 kip/ft + 0.20 kip/ft
\= 1.10 kip/ft = 0.85 kip/ft
1.10 kip/ft(30 ft) 2 0.85 kip/ft(30 ft) 2
Mu = = 124 kip-ft Ma = = 95.6 kip-ft
8 8
Controls controls

Use Manual Table 3-2 to find a beam with an Ix ≥ 272 in.4. Select W16×26, which has an Manual
Ix = 301 in.4 which exceeds our target value, and has an available moment of Table 3-2
166 kip-ft (LRFD) and 110 kip-ft (ASD).

Check for possible live load reduction due to area IBC Table
1607.9.1
For interior beams KLL = 2

The beams are at 10 ft on center, therefore the area AT = 30 ft × 10 ft = 300 ft2. IBC Eqn
⎛ 15 ⎞ 16-21
L = Lo ⎜ 0.25 + ⎟ = 0.069 kip/ft2 ≥ 0.50 Lo = 0.040 kip/ft2 ⎜ ⎟ ⎝ K LL AT ⎠

Therefore, use 0.069 kip/ft2

The beams are at 10 ft on center, therefore the loading diagram is as shown below.

<!-- p. 462 -->

III-18

Calculate the required strength

LRFD ASD
Wu = 1.2(0.75 kip/ft) = 1.6 (0.69 kip/ft) Wa = 0.750 kip/ft + 0.690 kip/ft
\= 2.00 kip/ft = 1.44 kip/ft

2.00 kip/ft(30 ft) 2 1.44 kip/ft(30 ft) 2
Mu = = 225 kip-ft Ma = = 162 kip-ft
8 8

From previous calculation, Y2 = 5.5 in.

Use Manual Table 3-19 to check the W16×26 selected above. Using required strengths of 225 Manual
kip-ft (LRFD) or 162 kip-ft (ASD) and a Y2 value of 4.5 in Table 3-19

LRFD ASD
Select W16×26 beam, where Select W16×26 beam, where Manual
Table 3-19
PNA = 7 and PNA = 7 and
∑ Qn = 96.0 kips ∑ Qn = 96.0 kips

φbMp = 248 kip-ft > 225 kip-ft o.k. Mp/Ωb = 165 kip-ft > 162 kip-ft o.k.

Determine beff

The effective width of the concrete slab is the sum of the effective widths for each side of the Specification
beam centerline, which shall not exceed: Sec. I.3.1.1a

(1) one-eighth of the span of the beam, center to center of supports
30 ft
( 2 sides) = 7.50 ft. Controls
8

(2) one-half the distance to the center line of the adjacent beam
10 ft
( 2 sides) = 10.0 ft.
2

(3) the distance to the edge of the slab
Not applicable

Check a

LRFD ASD
∑ Qn ∑ Qn a = ' a = '
0.85 f c b 0.85 f c b
96.0 kips 145 kips
\= =
0.85(4 ksi)(7.50 ft)(12 in./ft) 0.85(4 ksi)(7.50 ft)(12 in./ft)
\= 0.313 in. \< 1.0 in. o.k. = 0.473 in. \< 1.0 in. o.k.

<!-- p. 463 -->

III-19

Check end shear strength

LRFD ASD
30 ft 30 ft Manual
Ru = ( 2.00 kip/ft) ) = 30.0 kips Ra = (1.44 kip/ft) ) = 21.6 kips Table 3-2 2 2
φbVn = 106 kips > 30.0 kips o.k. Vn/Ωb = 70.5 kips > 21.6 kips o.k.

Check live load deflection

∆ LL = l 360 = ((30 ft)(12 in./ft))/360 = 1.0 in. IBC Table
1604.3

LRFD ASD
W16×26 W16×26 Manual
Table 3-20
Y2 = 5.5 in. Y2 = 5.5 in.
PNA = 7 PNA = 6
ILB = 535 in.4 ILB = 622 in.4

wLL l 4 0.69 kip/ft(30 ft) 4 wLL l 4 0.69 kip/ft(30 ft) 4 ∆ LL = = 4 ∆ LL = = 4
1290 I LB 1290(575 in. ) 1290 I LB 1290(575 in. )
\= 0.753 in. \< 1.0 in. o.k. = 0.753 in. \< 1.0 in. o.k.

Determine the required shear stud connectors

Using perpendicular deck with one w-in. diameter stud per rib in normal weight, 4 ksi Manual
concrete, in weak position; Qn = 17.2 kips/stud Table 3-21

LRFD ASD
∑ Qn 96.0 kips ∑ Qn 96.0 kips = = 5.58 studs / side = = 5.58 studs / side
Qn 17.2 kips/stud Qn 17.2 kips/stud
Use 12 studs at about 3’-0” o.c. Use 17 studs

Note: There is a maximum spacing of 8(6 in.) = 4’- 0” or 3’-0” between studs. Specification
Sec. I3.2d(6)
Therefore use 12 studs, at no more than 3’-0” on center.

Note: this beam could also be designed as a non-composite beam. Use Manual Table 3-2 with previous moments
and shears:

LRFD ASD
Select W18×35 Select W18×35
φbMp = 249 kip-ft > 225 kip-ft o.k. Mp/Ωb = 166 kip-ft > 162 kip-ft o.k.
φvVn = 159 > 30.0 kips o.k. Vn/Ωv = 106 kips > 21.6 kips o.k.

<!-- p. 464 -->

III-20

Check beam deflections

Check W18×35 with an Ix = 510 in.4, with only wet concrete on beams. Manual
Table 3-1

Note: Because this beam is stronger than the W16×26 composite beam, no wet concrete strength checks are
required.
0.65 kip/ft(30 ft) 4
∆ DL (wet concrete) = 4 =0.80 in. o.k. 1290(510 in. )
Note: A good break point to eliminate camber is w in. If a W18×40 (Ix = 612 in.4),
∆ DL ( wet concrete) = 0.615 in. ) was selected, no camber is required.

Per previous smaller beam calculation, the live load deflection is o.k.

Therefore selecting a W18×40 would eliminate both shear studs and cambering. The cost of the extra steel weight
may be offset by the elimination of studs and cambering. Local labor and material costs should be checked in
making this determination.

SELECT TYPICAL END BEAM
The influence area for these beams is less than 400 ft2, therefore no live load reduction can be taken.

These beams carry 5.5 ft of dead load and live load as well as a wall load.

The dead load is

w = 5.5 ft(0.075 kips/ft) = 0.413 kip/ft.

The dead load of the wall system at the floor is

w = 7.5 ft(0.055 kip/ft + 6.0 ft( 0.015 kip/ft)
\= 0.413 kip/ft + 0.090 kip/ft
\= 0.503 kip/ft.

The total dead load is w = 0.916 kip/ft.

The live load is w = 5.5 ft(0.080 kip/ft) = 0.440 kip/ft.

<!-- p. 465 -->

III-21

The loading diagram is as follows

Calculate the required strengths

LRFD ASD
Wu = 1.2(0.916 kip/ft) + 1.6 (0.440 kip/ft) Wa = 0.916 kip/ft + 0.440 kip/ft
\= 1.80 kip/ft = 1.36 kip/ft

1.80 kip/ft(22.5 ft) 2 1.36 kip/ft(22.5 ft) 2
Mu = = 114 kip-ft Ma = = 85.8 kip-ft
8 8
22.5 ft 22.5 ft Ru = (1.80 kip/ft) ) = 20.3 kips Ra = (1.36 kip/ft) ) = 15.3 kips
2 2

Because these beams are less than 25-ft long, they will be most efficient as non-composite
beams. The beams at the ends of the building carry a brick spandrel panel. Because there is
continuous glass underneath this spandrel, limit live load deflection to ¼ in. total movement. In
addition, per AISC Design Guide 3, Second Edition, limit deflection due to spandrel weight to
L/480 or a-in. maximum.

Calculate minimum Ix to limit live load deflection to ¼ in.
0.440 kip/ft(22.5 ft) 4
Ireq = = 350 in.4 controls
1290(0.25 in.)

Calculate minimum Ix to limit spandrel weight deflection to a in.
0.413 kip/ft(22.5 ft) 4
Ireq = = 218 in.4
1290(0.375 in.)

Select Beam from Manual Table 3-2

LRFD ASD
Select W16×31 with an Ix = 375 in.4 Select W16×31 with an Ix = 375 in.4 Manual
φbMp = 203 kip-ft > 114 kip-ft o.k. Mp/Ωb = 135 kip-ft > 85.8 kip-ft o.k. Table 3-2
φvVn = 131 > 20.3 kips o.k. Vn/Ωv = 87.3 kips > 15.3 kips o.k.

<!-- p. 466 -->

III-22

SELECT TYPICAL SIDE BEAM

The beams along the side of the building carry the spandrel panel and glass, and dead load and live load from the
intermediate floor beams. The spandrel beam is over glass below, therefore, limit the live load deflection to ¼ in.
In addition, per Steel Design Guide 3, Second Edition, limit deflection due to spandrel weight to the L/480 or ain. maximum. These beams will be part of the moment frames on the side of the building and therefore will be
designed as fixed at both ends.

Establish loads

The dead load reaction from the floor beams is

P = 0.75 kip/ft (45 ft / 2) = 16.9 kips

The uniform dead load along the beam is

w = 0.50 ft (0.075 kip/ft2) + 0.503 kip/ft = 0.541 kip/ft.

Select typical 30 foot composite(or non-composite) girders

Check for possible live load reduction

For edge beams with cantilevered slabs, KLL = 1, per ASCE Table 4-2. However, it is also IBC Table
permissible to calculate the value of KLL based upon influence area. Because the cantilever 1607.9.1
dimension is small, KLL will be closer to 2 than 1. The calculated value of KLL based upon the
influence area is
IBC Eqn
KLL = 1.98. 16-21

The AT = 30 ft × (22.5 ft + 0.5 ft) = 690 ft2.
⎛ 15 ⎞
L = Lo ⎜ 0.25 + ⎟ = 0.0523 kip/ft2 ≥ 0.50 Lo = 0.040 kip/ft2 ⎜ ⎟ ⎝ K LL AT ⎠

Therefore, use 0.0523 kip/ft2.

The live load from the floor beams is P = 0.523 kip/ft(45 ft / 2) = 11.8 kips

The uniform live load along the beam is w = 0.50 ft (0.0523 kip/ft2) = 0.025 kip/ft.

The loading diagram is shown below.

<!-- p. 467 -->

III-23

A summary of the moments, reactions and required moments of inertia, determined from a
structural analysis of a fixed-end beam, is as follows:

Calculate the required strengths and select the beams for the floor side beams

LRFD ASD
Typical side beam Typical side beam
Ru = 49.5 kips Ra = 37.2 kips
Mu at ends =313 kip-ft Ma at ends = 234 kip-ft
Mu at ctr. =156 kip-ft Ma at ctr. = 117 kip-ft
∆ LL = 0.177 in. \< 1.0 in. o.k. ∆ LL = 0.177 in. \< 1.0 in. o.k.

Calculate minimum Ix to limit the spandrel weight deflection to a in.

4 ( 0.503 kip/ft ) (30 ft)
Ireq = = 168 in.4
6450(0.375 in.)

LRFD ASD
Typical side beam Typical side beam
Select W21×44 which has an available Select W21×44 which has an available Manual
moment of 358 kip-ft and an Ix of 843 in.4 moment of 238 kip-ft and an Ix of 843 in.4 Table 3-2

Note: During concrete placement, because the deck is parallel to the beam, the beam will not
have continuous lateral support. It will be braced at 10 ft on center by the intermediate beams.
Also, during concrete placement, a construction live load of 0.020 kip/ft2 will be present. This
load pattern and a summary of the moments and reactions is shown below.

<!-- p. 468 -->

III-24

LRFD ASD
Typical side beam with wet concrete only Typical side beam with wet concrete only
Ru = 21.1 kips Ra = 15.1 kips
Mu at ends = 140 kip-ft Ma at ends = 99.9 kip-ft
Mu at ctr. = 70.0 kip-ft Ma at ctr. = 50.0 kip-ft

∆ LL = 0.220 in. \< 1.0 in. o.k.

LRFD ASD
Typical side beam with wet concrete and Typical side beam wet concrete and
construction load construction load
Ru = 25.6 kips Ra = 19.8 kips
Mu at ends = 169 kip-ft controls Ma at ends = 131 kip-ft controls
Mu at ctr. = 84.5 kip-ft Ma at ctr. = 65.3 kip-ft

∆ LL = 0.288 in. \< 1.0 in. o.k.

LRFD ASD
The available strength of a W21×44 with an The available strength of a W21×44 with an Manual
unbraced length of 10 ft, and a conservative unbraced length of 10 ft, and a conservative Table 3-10
value of Cb = 1.0 is 262 kip-ft. value of Cb = 1.0 is 175 kip-ft.

262 kip-ft > 169 kip-ft o.k. 175 kip-ft > 131 kip-ft o.k.

Note: The W21×44 is adequate for strength and deflection, but may be increased in size to help
with moment frame strength or drift control.

<!-- p. 469 -->

III-25

SELECT TYPICAL INTERIOR BEAM

Establish loads

The dead load reaction from the floor beams is P = 0.75 kip/ft(37.5 ft) = 28.1 kips

Check for live load reduction due to area

For interior beams, KLL = 2 IBC Table
1607.9.1
The AT = 30 ft × 37.5 ft = 1125 ft2.
⎛ 15 ⎞
L = Lo ⎜ 0.25 + ⎟ = 0.0453 kip/ft2 ≥ 0.50 Lo = 0.040 kip/ft2 IBC Eqn. ⎜ ⎟ ⎝ K LL AT ⎠ 16-21
Therefore, use 0.0453 kip/ft2

The live load from the floor beams is P = 0.0453 kip/ft2(10 ft)(37.5 ft) = 17.0 kips

Note: The dead load for this beam is included in the assumed overall dead load.

A summary of the simple moments and reactions is shown below:

Calculate the total loads, moments and shears, and select the beams for the interior beams

LRFD ASD
Typical interior beam Typical interior beam
Ru = 60.9 kips Ra = 45.1 kips
Mu = 609 kip-ft Ma = 451 kip-ft

Check for beam requirements when carrying wet concrete

Note: During concrete placement, because the deck is parallel to the beam, the beam will not
have continuous lateral support. It will be braced, at 10 ft on center by the intermediate beams.
Also, during concrete placement, a construction live load of 0.020 kip/ft2 will be present. This
load pattern and a summary of the moments and reactions, and deflection requirements is
shown below. Limit wet concrete deflection to 1.5 in.

<!-- p. 470 -->

III-26

LRFD ASD
Typical Interior Beam with wet concrete only Typical interior Beam with wet concrete only
Ru = 34.1 kips Ra = 24.4 kips
Mu = 341 kip-ft Ma = 207 kip-ft

Target Ix ≥ 658 in.4

LRFD ASD
Typical Interior Beam with wet concrete and Typical Interior Beam with wet concrete and
construction load construction load
Manual
Ru = 41.3 kips Ra = 31.9 kips Table 3-10
Mu (midspan) =413 kip-ft Ma (midspan) = 319 kip-ft

Select beam with an unbraced length of 10 ft Select beam with an unbraced length of 10 ft
and a conservative Cb = 1.0 and a conservative Cb = 1.0

Select W21×68, which has an available Select W21×68, which has an available
moment strength of 532 kip-ft moment strength of 354 kip-ft

φbMp = 532 kip-ft > 413 kip-ft o.k. Mp/Ωb = 354 kip-ft ≈319 kip-ft o.k.

Check W21×68 as a composite beam

From previous calculations:

LRFD ASD
Typical Interior Beam Typical Interior beam
Ru = 60.9 kips Ra = 45.1 kips
Mu (midspan) =609 kip-ft Ma (midspan) = 451 kip-ft

Y2 (from previous calculations) = 5.5 in.

Use Manual Table 3-19, check W21×68, using required strengths of 609 kip-ft (LRFD) and 451
kip-ft (ASD) and Y2 value of 5.5 in.

LRFD ASD
Select a W21×68 Select a W21×68 Manual
Where PNA = 7, ∑ Qn = 251 kips Where PNA = 7, ∑ Qn = 251 kips Table 3-19
φbMn = 847 kip-ft > 609 kip-ft o.k. Mn/Ωb = 564 kip-ft > 461 kip-ft o.k.

<!-- p. 471 -->

III-27

This beam has an Ix = 1480 in.4 > 658 in.4
Therefore, do not camber.

Determine beff

The effective width of the concrete slab is the sum of the effective widths for each side of the Specification
beam centerline which shall not exceed: Sec. I.3.1.1a

(1) one-eighth of the span of the beam, center to center of supports
30 ft
( 2 sides) = 7.50 ft. Controls
8

(2) one-half the distance to the center line of the adjacent beam
⎛ 45 ft 30 ft ⎞
⎜ + ⎟ = 37.5 ft.
⎝ 2 2 ⎠

(3) the distance to the edge of the slab
Not applicable.

LRFD ASD
Check a Check a
∑ Qn ∑ Qn a = ' a = '
0.85 f c b 0.85 f c b
251 kips 251 kips
\= =
0.85(4 ksi)(7.50 ft)(12 in./ft) 0.85(4 ksi)(7.50 ft)(12 in./ft)
\= 0.820 in. \< 1.0 in. o.k. = 0.820 in. \< 1.0 in. o.k.

Determine the required shear stud connectors

Using parallel deck with one w-in. diameter stud in normal weight, 4 ksi concrete, in weak Manual
position; Qn = 21.5 kips/stud Table 3-21

LRFD ASD
∑ Qn 251 kips ∑ Qn 251 kips = = 11.7 studs / side = = 11.7 studs / side
Qn 21.5 kips/stud Qn 21.5 kips/stud

Therefore, use a minimum 24 studs for Therefore, use a minimum 24 studs for
horizontal shear. horizontal shear.

The maximum stud spacing is 3’-0”. The maximum stud spacing is 3’-0”.

Since the load is concentrated at 3 points, Since the load is concentrated at 3 points,
the studs are to be arranged as follows: the studs are to be arranged as follows:

Use 12 studs between supports and Use 12 studs between supports and
supported beams at 3 points. Between supported beams at 3 points. Between
supported beams middle 3 of span, use 4 supported beams middle 3 of span, use 4
studs to satisfy minimum spacing studs to satisfy minimum spacing
requirements. requirements.

Thus, 28 studs are required in a 12:4:12 Thus, 28 studs are required in a 12:4:12
arrangement. arrangement.

<!-- p. 472 -->

III-28

Note: This W21×68 beam, with full lateral support, is very close to having sufficient available
strength to support the imposed loads without composite action. Since design was completed
using the available Manual tables, a PNA location 7 was selected. A more economical solution
would result if a PNA lower in the beam web could have been selected. In that case, very few
studs would have been required and a larger non-composite beam might be a better solution. It
is important to note the significant impact of properly designing for construction

<!-- p. 473 -->

III-29

COLUMNS MEMBER DESIGN SELECTION FOR GRAVITY COLUMNS

Estimate column loads

Roof (from previous calculations)
Dead Load 0.020 kips/ft2
Live (Snow) 0.025 kips/ft2
Total 0.045 kips/ft2

Snow drifting loads at the perimeter of the roof and at the mechanical screen wall from previous calculations

Reaction to column (side parapet)

w = (3.73 kips / 6 ft) - (0.025 ksf)(23.0 ft) = 0.047 kips/ft

Reaction to column (end parapet)

w = (0.43 klf) - (0.025 ksf)(15.5 ft) = 0.043 kips/ft

Reaction to column (screen wall)

w = (0.48 klf) – (0.025 ksf)(15.5 ft) = 0.105 kips/ft

Mechanical equipment (average)

w = 0.040 kips/ft

<!-- p. 474 -->

III-30

Col Loading Area DL PD LL PL
Width Length
ft ft ft2 kips/ft2 kips kips/ft2 kips

2A, 2F, 3A, 3F, 4A, 4F 23.0 30.0 690 0.020 13.8 0.025 17.3
5A, 5F, 6A, 6F, 7A, 7F
snow drifting side 30.0 0.047 klf 1.41
exterior wall 30.0 0.413 klf 12.4
26.2 18.7

1B, 1E, 8B, 8E 3.50 22.5 79 0.020 1.58 0.025 1.97
snow drifting end 22.5 0.043 klf 0.97
exterior wall 22.5 0.413 klf 9.29
10.9 2.94

1A, 1F, 8A, 8F 23.0 15.5 345 0.020 6.34 0.025 7.93
\-(79 ft 2 )
2
\= 317
snow drifting end 11.8 0.043 klf 0.51
snow drifting side 15.5 0.047 klf 0.73
exterior wall 26.3 0.413 klf 10.8
17.2 9.16

1C, 1D, 8C, 8D 37.5 15.5 581 0.020 10.8 0.025 13.5
\-(79 ft 2 )
2
\= 542
snow-drifting end 26.3 0.043 klf 1.13
exterior wall 26.3 0.413 klf 10.8
21.7 14.7

2C, 2D, 7C, 7D 37.5 30.0 1,125 0.020 22.5 0.025 28.1

3C, 3D, 4C, 4D 22.5 30.0 675 0.020 13.5 0.025 16.9
5C, 5D, 6C, 6D
snow-drifting 30.0 0.105 klf 3.15
mechanical area 15.0 30.0 0.060 27.0 0.025 11.3
40.5 31.3

<!-- p. 475 -->

III-31

Floor Loads (from previous calculations)
Dead load 0.075 kips/ft2
Live load 0.080 kips/ft2
Total load 0.155 kips/ft2

Reduction in live loads, analyzed at the base of 3 floors

Columns: 2A, 2F, 3A, 3F, 4A, 4F, 5A, 5F, 6A, 6F, 7A, 7F
Exterior column without cantilever slabs
IBC Sect
KLL = 4 Lo = 0.080 ksf n = 3 1607.9

AT = (23 ft)(30ft) = 690 ft2

⎛ 15 ⎞
L = Lo ⎜ 0.25 + ⎟ IBC Eqn ⎜ ⎟ ⎝ K LL nAT ⎠ 16-21

⎛ ⎞
⎜ 15 ⎟ = 0.080 ksf 0.25+ ⎜ 2 ⎟ ⎜ ⎟ ( 4 )( 3 )( 690 ft ) ⎝ ⎠

\= 0.033 ksf ≥ 0.4 Lo = 0.032 ksf

use L = 0.033 ksf

Columns: 1B, 1E, 8B, 8E
Exterior column without cantilever slabs

KLL = 4 Lo = 0.080 ksf n = 3 IBC Section
1607.9
AT = (5.5 ft)(22.5 ft) = 124 ft2

⎛ 15 ⎞
L = Lo ⎜ 0.25 + ⎟ ⎜ ⎟ ⎝ K LL nAT ⎠ IBC Eqn
16-21

⎛ ⎞
⎜ 15 ⎟ = 0.080 ksf 0.25+ ⎜ 2 ⎟ ⎜ ⎟ ( 4 )( 3 )(124 ft ) ⎝ ⎠

\= 0.051 ksf ≥ 0.4 Lo = 0.032 ksf

use L = 0.051 ksf

<!-- p. 476 -->

III-32

Columns: 1A, 1F, 8A, 8F
Corner column without cantilever slabs
IBC Section
Conservatively assume KLL = 1 Lo = 0.080 ksf n = 3 1607.9

AT = (15.5 ft)(23 ft) – (124 ft2 / 2) = 295 ft2
⎛ 15 ⎞ IBC Eqn
L = Lo ⎜ 0.25 + ⎟ ≥ 0.4 Lo 16-21
⎝ K LL nAT ⎠

⎛ ⎞
15 = 0.080 ksf ⎜ 0.25+ ⎟ ≥ 0.4(0.08 ksf )
2 ⎜ 1)( 3)( 295 ft ⎝ ( ) ⎟⎠

\= 0.060 ksf ≥ 0.032 ksf

use L = 0.060 ksf

Columns: 1C, 1D, 8C, 8D
Exterior column without cantilever slabs

KLL = 4 Lo = 0.080 ksf n = 3 IBC Section
1607.9
AT = (15.5 ft)(37.5 ft) – (124 ft2 / 2) = 519 ft2

⎛ 15 ⎞ IBC Eqn
L = Lo ⎜ 0.25 + ⎟ ≥ 0.4 Lo 16-21
⎝ K LL nAT ⎠

⎛ ⎞
15 = 0.080 ksf ⎜ 0.25+ ⎟ ≥ 0.4(0.08 ksf )
2 ⎜ 4 )( 3)( 519 ft ⎝ ( ) ⎟⎠

\= 0.035 ksf ≥ 0.032 ksf

use L = 0.035 ksf

<!-- p. 477 -->

III-33

Columns: 2C, 2D, 3C, 3D, 4C, 4D, 5C, 5D, 6C, 6D, 7C, 7D
Interior column

KLL = 4 Lo = 0.080 ksf n = 3 IBC Section
1607.9
AT = 1,125 ft2

⎛ 15 ⎞ IBC Eqn
L = Lo ⎜ 0.25 + ⎟ ≥ 0.4 Lo 16-21
⎝ K LL nAT ⎠

⎛ ⎞
15 = 0.080 ksf ⎜ 0.25+ ⎟ ≥ 0.4(0.08 ksf)
2 ⎜ 4 )( 3)(1,125 ft ⎝ ( ) ⎟⎠

\= 0.030 ksf ≥ 0.032 ksf

use L = 0.032 ksf

<!-- p. 478 -->

III-34

Column Loading DL PD LL PL
Width Length Area
ft ft ft2 kips/ft2 kips kips/ft2 kips

2A, 2F, 3A, 3F, 4A, 4F 23.0 30.0 690 0.075 51.8 0.033 22.9
5A, 5F, 6A, 6F, 7A, 7F
exterior wall 30.0 0.503 klf 15.1
66.8 22.9

1B, 1E, 8B, 8E 5.50 22.5 124 0.075 9.28 0.051 6.33
exterior wall 22.5 0.503 klf 11.3
20.6 6.33

1A, 1F, 8A, 8F 23.9 15.5 370 0.075 22.1 0.060 17.8
\-(124 ft 2 )
2
\= 295
exterior wall 27.3 0.503 klf 13.7
35.8 17.8

1C, 1D, 8C, 8D 37.5 15.5 581 0.075 39.0 0.035 18.3
\-(124 ft 2 )
2
\= 519
exterior wall 22.5 0.503 klf 11.3
50.3 18.3

2C, 2D, 3C, 3D, 4C, 4D 37.5 30.0 1,125 0.075 84.4 0.032 36.0
5C, 5D, 6C, 6D, 7C, 7D

<!-- p. 479 -->

III-35

Column load summary

Col Floor PD PL

kips kips

2A, 2F, 3A, 3F, 4A, 4F Roof 26.2 18.7
5A, 5F, 6A, 6F, 7A, 7F 4th 66.8 22.9
3rd 66.8 22.9
2nd 66.8 22.9
Total 227 87.4

1B, 1E, 8B, 8E Roof 10.9 2.94
4th 20.6 6.33
3rd 20.6 6.33
2nd 20.6 6.33
Total 72.7 21.9

1A, 1F, 8A, 8F Roof 17.2 9.16
4th 35.8 17.8
3rd 35.8 17.8
2nd 35.8 17.8
Total 125 62.5

1C, 1D, 8C, 8D Roof 21.7 14.7
4th 50.3 18.3
3rd 50.3 18.3
2nd 50.3 18.3
Total 173 69.5

2C, 2D, 7C, 7D Roof 22.5 28.1
4th 84.4 36.0
3rd 84.4 36.0
2nd 84.4 36.0
Total 276 136

3C, 3D, 4C, 4D Roof 40.5 31.3
5C, 5D, 6C, 6D 4th 84.4 36.0
3rd 84.4 36.0
2nd 84.4 36.0
Total 294 139

<!-- p. 480 -->

III-36

Selection of interior column

Columns: 3C, 3D, 4C, 4D, 5C, 5D, 6C, 6D

Elevation of second floor slab: 113.5 ft
Elevation of first floor slab: 100 ft
Column unbraced length: 13.5 ft

LRFD ASD
Pu = 1.2(294 kips) + 1.6(139 kips) = 575 kips Pa = 294 kips + 139 kips = 433 kips

From the tables, enter with the effective length of 13.5 ft, and proceed across the table until Manual
reaching the lightest size that has sufficient available strength at the required unbraced Table 4-1
length.
LRFD ASD
W12×65 W12×65 Manual
Table 4-1
φcPn = 696 kips > 575 kips o.k. Pn/Ωc = 463 kips > 433 kips o.k.

W14×68 W14×68

φcPn = 655 kips > 575 kips o.k. Pn/Ωc =436 kips > 433 kips o.k.

Selection of interior column

Columns: 2C, 2D, 7C, 7D

Elevation of second floor slab: 113.5 ft
Elevation of first floor slab: 100.0 ft
Column unbraced length: 13.5 ft

LRFD ASD
Pu = 1.2(276 kips) + 1.6(136 kips) = 549 kips Pa = 276 kips + 136 kips = 412 kips

From the tables, enter with the effective length of 13.5 ft, and proceed until reaching the Manual
lightest size that has sufficient available strength at the required unbraced length. Table 4-1
LRFD ASD
W12×65 W12×65 Manual
Table 4-1
φcPn = 696 kips > 549 kips o.k. Pn/Ωc = 463 kips > 412 kips o.k.

W14×68 W14×68

φcPn = 655 kips > 549 kips o.k. Pn/Ωc = 436 kips > 412 kips o.k.

<!-- p. 481 -->

III-37

Selection of exterior column

Columns: 1B, 1E, 8B, 8E

Elevation of second floor slab: 113.5 ft
Elevation of first floor slab: 100.0 ft
Column unbraced length: 13.5 ft

LRFD ASD
Pu = 1.2(72.7 kips) + 1.6(21.9 kips) Pa = 72.7 kips + 21.9 kips

\= 122 kips = 95 kips

From the tables, enter with the effective length of 13.5 ft, and proceed down the sizes (across Manual
the page) until a size is found that satisfies the total load at the unbraced length. Table 4-1

LRFD ASD
W12×40 W12×40 Manual
Table 4-1
φcPn = 316 kips > 139 kips o.k. Pn/Ωc = 210 kips > 105 kips o.k.

Note: A 12 in. column was selected above for ease of erection.

<!-- p. 482 -->

III-38

WIND LOAD DETERMINATION

Simplified wind load method (mean roof height less than 60 ft) IBC Sect
1609.6
To qualify for the simplified wind load method, the following must be true.

\1. simple diaphragm building o.k. IBC Sect
\2. not a flexible building o.k. 1609.6.1.1
\3. does not have response characteristics requiring special considerations o.k.
\4. regular shape and symmetrical cross section o.k.

Define input parameters
IBC Table
\1. Occupancy category: II 1604.5

\2. Basic wind speed V, 90 mph IBC Sect
1609.3

\3. Importance factor Iw 1.0 IBC Table
1604.5

\4. Exposure category: C IBC Sect
1609.4

\5. Height and exposure adjustment λ: 1.59 IBC Table
1609.6.2.1(4)

ps = λ Iw ps30 = (1.59)(1.0)(12.8 psf) = 20.4 psf Horizontal pressure zone A IBC Table
(1.59)(1.0)(10.2 psf) = 13.5 psf Horizontal pressure zone C 1609.6.2.1(1)
(1.59)(1.0)(-15.4 psf) = -24.5 psf Vertical pressure zone E and
(1.59)(1.0)(-8.8 psf) = -14.0 psf Vertical pressure zone F Eqn. 16-35
(1.59)(1.0)(-10.7 psf) = -17.0 psf Vertical pressure zone G
(1.59)(1.0)(-6.8 psf) = -10.8 psf Vertical pressure zone H

a = 10% of least horizontal dimension or 0.4h, whichever is smaller, but not less than either IBC Fig
4% of least dimension or 3 ft. 1609.6.2.1

10% of least dimension: 12.0 ft
40% of eave height: 22.0 ft
4% of least dimension or 3 ft 4.8 ft
a = 12.0 ft
2a = 24.0 ft

Zone A - End zone of wall (width = 2a)
Zone C – Interior zone of wall
Zone E – End zone of windward roof (width = 2a)
Zone F – End zone of leeward roof (width = 2a)
Zone G – Interior zone of windward roof
Zone H – Interior zone of leeward roof

<!-- p. 483 -->

III-39

Calculate load to roof diaphragm

Assume mechanical screen wall height: 6 ft

Wall height: 2 (55.0 ft – 40.5 ft) = 7.25 ft

Parapet wall height: 2 ft.

Total wall height at roof at screen wall: 6 ft + 7.25 ft = 13.3 ft

Total wall height at roof at parapet: 2 ft + 7.25 ft = 9.25 ft

Calculate load to 4th floor diaphragm

Wall height: 2 (55.0 ft – 40.5 ft) = 7.25 ft

2 (40.5 ft – 27.0 ft) = 6.75 ft

Total wall height at floor: 6.75 ft + 7.25 ft = 14.0 ft

Calculate load to third floor diaphragm

Wall height: 2 (40.5 ft – 27.0 ft) = 6.75 ft

2 (27.0 ft – 13.5 ft) = 6.75 ft

Total wall height at floor: 6.75 ft + 6.75 ft = 13.5 ft

Calculate load to second floor diaphragm

Wall height: 2 (27.0 ft – 13.5 ft) = 6.75 ft

2 (13.5 ft – 0.0 ft) = 6.75 ft

Total wall height at floor: 6.75 ft + 6.75 ft = 13.5 ft

<!-- p. 484 -->

III-40

Total load to diaphragm:

Load to diaphragm: ws(A) = (20.4 psf)(9.25 ft) = 189 plf

ws(C) = (13.5 psf)(9.25 ft) = 125 plf

ws(C) = (13.5 psf)(13.3 ft) = 179 plf

Load to diaphragm: ws(A) = (20.4 psf)(14.0 ft) = 286 plf

ws(C) = (13.5 psf)(14.0 ft) = 189 plf

Load to diaphragm: ws(A) = (20.4 psf)(13.5 ft) = 275 plf

ws(C) = (13.5 psf)(13.5 ft) = 182 plf

l = length of structure, ft

b = width of structure, ft

h = height of wall at building element, ft

Wind from a north – south direction

Total load to diaphragm: PW(n-s) = 2 a ws(A) + ws(C) ( l – 2 a)

Wind from a east – west direction

Total load to diaphragm: PW(e-w) = 2 a ws(A) + ws(C) (b – 2 a)

l b 2a h ps(A) ps(C) ws(A) ws(C) PW(n-s) PW(e-w)

ft ft ft ft psf psf plf plf kips kips

Roof 213 123 24 9.25 20.4 189 9.06 9.06
9.25 13.5 125 9.37 5.62
13.3 13.5 179 16.1 5.37
Fourth 213 123 24 14.0 20.4 13.5 286 189 42.6 25.6
Third 213 123 24 13.5 20.4 13.5 275 182 41.1 24.7
Second 213 123 24 13.5 20.4 13.5 275 182 41.1 24.7
Base 159 95.0

<!-- p. 485 -->

III-41

SEISMIC LOAD DETERMINATION

The floor plan area: 120 ft, column center line to column center line, by 210 ft, column center line to column
center line, with the edge of floor slab or roof deck 6 in. beyond the column center line.

Area = (121 ft)(211 ft) = 25,531 ft2

The perimeter cladding system length:

Length = (2)(122 ft) + (2)(212 ft) = 668 ft

The perimeter cladding weight at floors:

Brick spandrel panel with metal stud backup (7.5 ft)(0.055 ksf) = 0.413 klf
Window wall system (6.0 ft)(0.015 ksf) = 0.090 klf
Total 0.503 klf

Typical roof dead load (from previous calculations):

Roof Area = (25,531 ft2)(0.020 ksf) = 511 kips
Wall perimeter = (668 ft)(0.413 klf) = 276 kips
Mechanical equipment = 32 kips
Total 818 kips

Typical third and fourth floor dead load:

Floor Area = (25,531 ft2)(0.085 ksf) = 2,170 kips
Wall perimeter = (668 ft)(0.503 klf) = 336 kips
Total 2,506 kips

Second floor dead load: the floor area is reduced because of the open atrium

Floor Area = (24,226 ft2)(0.085 ksf) = 2,059 kips
Wall perimeter = (668 ft)(0.503 klf) = 336 kips
Total 2,395 kips

Total dead load of the building:
Roof 818 kips
Fourth floor 2,506 kips
Third floor 2,506 kips
Second floor 2,395 kips
Total 8,225 kips

<!-- p. 486 -->

III-42

Calculate the seismic forces

Office Building Category II IBC Table
1604.5

Seismic Use Group I IBC Sect.
1616.2

Importance Factor IE = 1.00 IBC Table
1604.5

SS = 0.121 IBC Fig
1615(1)
S1 = 0.06 IBC Fig
1615(2)
Soil, site class D IBC Table
1615.1.1
Fa @ SS M 0.25 = 1.6 IBC Table
1615.1.2(1)
Fv @ S1 M 0.1 = 2.4 IBC Table
1615.1.2(2)
SMS = Fa SS = (1.6)(0.121) = 0.194 IBC Eqn
16-38
SM1 = Fv S1 = (2.4)(0.06) = 0.144 IBC Eqn
16-39
SDS = q SMS = 0.129 IBC Eqn
16-40
SD1 = q SM1 = 0.096 IBC Eqn
16-41
SDS M 0.167g, Seismic Use Group I: Seismic Design Category: A IBC Table
1616.3(1)
0.067g M SD1 M 0.133g, Seismic Use Group I: Seismic Design Category: B IBC Table
1616.3(2)
Building Height, hn = 55 ft
ASCE 7
Ct = 0.02: x = 0.75 Table
9.5.5.3.2

Ta = Ct (hn)x = (0.02)(55 ft)0.75 = 0.404 ASCE 7 Eqn
9.5.5.3.2-1
0.8 Ts = 0.8 (SD1/SDS ) = 0.8(0.129 / 0.096) = 0.595 IBC Sec.
1615.1.4
Since Ta \< 0.8 Ts; Seismic Design Category A may be used and it is therefore IBC Sect
permissible to select a structural steel system not specifically detailed for seismic 1616.3
resistance, for which the Seismic Response Modification Coefficient R = 3

Overstrength Factor: Ωo = 3 ASCE 7
Table 9.5.2.2
Seismic Base Shear: V = Cs W ASCE 7 Eqn
9.5.5.2-1
S DS 0.129 C s = = = 0.043 Controls ASCE 7 Eqn R I E 31 9.5.5.2.1-1

<!-- p. 487 -->

III-43

S D1 0.096 Cs need not exceed, C s = = = 0.079
3 ⎛ ⎞ R 0.404 ) ⎜ ⎟ T ( ASCE 7 Eqn 1 )( I E ⎝ ⎠
9.5.5.2.1-2

Min Cs = 0.44 SDSIE = 0.44(0.129)(1.0) = 0.006
ASCE 7 Eqn
V = 0.043(8225 kips) = 354 kips 9.5.5.2.1-3

Calculate vertical distribution of seismic forces
ASCE 7 Sect
Fx = CvxV = Cvx(0.043)W 9.5.5.4
ASCE 7 Eqn
wx hx k 9.5.5.4-1 Cvx = n
wi hi k ∑ ASCE 7 Eqn i =1
9.5.5.4-2
for structures having a period of 0.5 sec or less, k = 1

Calculate horizontal shear distribution and torsion

n ASCE 7 Sect
Fi 9.5.5.4 Vx = ∑
i = x
ASCE 7 Eqn
Calculate Overturning Moment 9.5.5.5

n ASCE 7 Sect
Fi ( hi − hx ) M x = ∑ 9.5.5.6
i = x
ASCE 7 Eqn
k k 9.5.5.6 wx hx wxhx Cvx Fx Vx Mx

kips ft kip-ft kips kips kips k-ft

Roof 818 55.0 45,000 0.18 64.6 64.6
Fourth 2,506 40.5 101,500 0.41 146 210 936
Third 2,506 27.0 67,700 0.27 97.1 307 3,774
Second 2,395 13.5 32,300 0.13 46.4 354 7,922
Base 8,225 246,500 354 12,696

Determine rigidity of diaphragms

Roof

Roof deck: 12 in. deep, 22 gage, Type B,
support fasteners; s in. puddle welds and sidelap fasteners; #10 TEK screws
Joist spacing = 6 ft
Diaphragm length = 210 ft
Diaphragm width = 120 ft

Load to diaphragm = (64.6 kips) / (210 ft) = 0.308 klf

( 308 plf )( 210 ft )Diaphragm shear load = = 269 plf
2 (120 ft )

<!-- p. 488 -->

III-44

Fastener layout = 36 / 5; sidelap = 3 #10 TEK Steel Deck
Institute
DB = 758 K1 = 0.287 K2 = 870 Shear strength = 298 plf Diaphragm
Design
K 2 870 Manual
G ' = = = 18.6 k/in
0.3 DB 0.3 ( 758 ) 3.78 + + 3 K 1 span 3.78 + + 3 ( 0.287 )( 6 ) span 6

wL2 ( 0.308 klf )( 210 ft ) 2 ∆= = = 0.761 in
8 BG ' 8 (120 ft )(18.6 k/in )

Allowable story drift: 0.025 hsx = 0.025(14.5 ft) = 0.363 in. IBC Table
1617.3.1

Diaphragm, rigid. Lateral deformation M 2 (story drift) IBC Sect
1602
∆ = 0.761 in. > 2(0.363 in.) = 0.725 in.

Therefore, the roof diaphragm is flexible, but using at rigid diaphragm distribution is more
conservative.

Fourth floor

Floor deck: 3 in. deep, 22 gage, Composite deck with normal weight concrete,
support fasteners; s in. puddle welds and button punched sidelap fasteners
Beam spacing = 10 ft
Diaphragm length = 210 ft
Diaphragm width = 120 ft

Load to diaphragm = (146 kips) / (210 ft) = 0.695 klf

( 695 plf )( 210 ft )Diaphragm shear load = = 608 plf
2 (120 ft )
Fastener layout = 36 / 4; 1 button punched sidelap fastener Steel Deck
Institute
K1 = 0.178 K2 = 870 K3 = 2,380 Shear strength = 1,588 plf Diaphragm
Design
⎛ K 2 ⎞ ⎛ 870 ⎞ Manual
\+ 2,380 = 2,533 k/in + K 3 = ⎜ ⎟ G ' = ⎜ ⎟ ⎜ ⎟ 0.729 )( 6 ) ⎝ 3.590 + 3 K 1 span ⎠ ⎝ 3.50 + 3 ( ⎠

wL2 ( 0.695 klf )( 210 ft ) 2 ∆= = = 0.0126 in
8 BG ' 8 (120 ft )( 2,533 k/in )

<!-- p. 489 -->

III-45

Allowable story drift; 0.025 hsx = 0.025(13.5 ft) = 0.338 in. IBC Table
1617.3.1

Diaphragm, rigid. Lateral deformation M 2 (story drift) IBC Sect
1602
∆ = 0.0126 in. M 2(0.338 in.) = 0.675 in.

Therefore, the floor diaphragm is rigid

Second floor

Floor deck: 3 in. deep, 22 gage, Composite deck with normal weight concrete,
support fasteners: s in. puddle welds and button punched sidelap fasteners
Beam spacing = 10 ft
Diaphragm length = 210 ft
Diaphragm width = 120 ft
Because of the open atrium in the floor diaphragm, an effective diaphragm depth of 75 ft, will be used for the
deflection calculations

Load to diaphragm = (46 kips) / (210 ft) = 0.221 klf

( 221 plf )( 210 ft )Diaphragm shear load = = 193 plf
2 (120 ft )
Fastener layout = 36 / 4; 1 button punched sidelap fastener Steel Deck
K1 = 0.729 K2 = 870 K3 = 2,380 Shear strength = 1,588 plf Institute
Diaphragm
⎛ K 2 ⎞ ⎛ 870 ⎞ Design
\+ 2,380 = 2,533 k/in Manual + K 3 = ⎜ ⎟ G ' = ⎜ ⎟ ⎜ ⎟ 0.729 )( 6 ) ⎝ 3.590 + 3 K 1 span ⎠ ⎝ 3.50 + 3 ( ⎠

wL2 ( 0.221 klf )( 210 ft ) 2 ∆= = = 0.00641 in
8 BG ' 8 ( 75 ft )( 2,533 k/in )

Allowable story drift; 0.025 hsx = 0.025(13.5 ft) = 0.338 in. IBC Table
1617.3.1

Diaphragm, rigid. Lateral deformation M 2 (story drift) IBC Sect
1602
∆ = 0.00641 in. M 2(0.338 in.) = 0.675 in.

Therefore, the floor diaphragm is rigid

<!-- p. 490 -->

III-46

Horizontal shear distribution and torsion: ASCE 7 Sect
9.5.5.5
Load to Grids 1 and 8
Fy Load to Frame Accidental Torsion Total

kips % kips % kips kips

Roof 64.6 50 32.3 5 3.23 35.5
Fourth 146 50 73.0 5 7.30 80.3
Third 97.1 50 48.6 5 4.86 53.4
Second 46.4 50 23.2 5 2.32 25.5
Base 195

Load to Grids A and F
Fx Load to Frame Accidental Torsion Total

kips % kips % kips kips

Roof 64.6 50 32.3 5 3.23 35.5
Fourth 146 50 73.0 5 7.30 80.3
Third 97.1 50 48.6 5 4.86 53.4
Second 46.4 51.8(1) 24.0 5 2.32 26.4
Base 196

Note: In this example, Grids A and F have both been conservatively designed for the slightly
higher load on Grid A due to the atrium opening.

(1) At the Second Floor slab, because of the atrium opening, the center of mass is not at the center of rigidity.

Area Mass x-dist Mx y-dist My
ft2 kips ft k-ft ft k-ft

I 10,950 931 45.25 42,118 60.5 56,313
II 2,265 193 105.5 20,311 37.75 7,268
III 10,950 931 165.8 154,279 60.5 56,313
2,054 216,709 119,894

x = 216,709 k-ft / 2,054 kips = 105.5 ft

105.5 ft / 211 ft = 50%

y = 119,894 k-ft / 2,054 kips = 58.37 ft

(121 ft - 58.37 ft) / 121 ft = 51.8%

<!-- p. 491 -->

III-47

MOMENT FRAME MODEL

Grids 1 and 8 were modeled in conventional structural analysis software as two-dimensional models. The secondorder option in the structural analysis program was not used. Rather, for illustration purposes, second-order effects
are calculated separately, using the B1-B2 approximation method given in Specification Section C2.1b.

The column and beam layouts for the moment frames follow. Although the frames on Grids A and F are the
same, slightly heavier seismic loads accumulate on grid F, after accounting for the atrium area on Grid A and
accidental torsion. The models are half-building models. The frame was originally modeled with W14×82
interior columns and W21×44 non-composite beams. This model had a drift that substantially exceeded the
0.025hsx story drift allowed per IBC Table 1617.3.1, Seismic Use Group I. The column size was incremented up
to a W14×99 and the W21×44 beams were upsized to W24×55 (with minimum composite studs) and the beams
were modeled with a stiffness of Ieq = Is. Alternatively, the beams could be modeled
as I eq = 0.6 I LB + 0.4 I n (Formula 24), s. This equation is given in AISC Design Guide 8. These changes resulted in
a drift that satisfied the L / 400 limit. This layout is shown in the Grid A and F, Frame (½ building) layout that
follows.

All of the vertical loads on the frame were modeled as point loads on the frame. As noted in the description of the
dead load, W, in IBC Section 1617.5, 0.010 kip/ft2 is included in the dead load combinations. The remainder of
the half-building model gravity loads were accumulated in the leaning column, which was connected to the frame
portion of the model with pinned ended links. See Geschwindner, AISC Engineering Journal, Fourth Quarter
1994, A Practical Approach to the “Leaning” Column. The dead load and live load are shown in the load cases
that follow. The wind and the seismic loads are modeled and distributed 1/14 to exterior columns and 1/7 to the
interior columns. This approach minimizes the tendency to accumulate too much load in the lateral system
nearest an externally applied load.

There are four horizontal load cases. Two are the wind load and seismic load, per the previous discussion. In
addition, notional loads of Ni = 0.002Yi were established. These load cases are shown in the load cases that
follow.

The same modeling procedures were used in the braced frame analysis. If column bases are not fixed in
construction, they should not be fixed in the analysis.

<!-- p. 492 -->

III-48

The model layout, dead loads, live loads, wind loads, seismic loads, dead load notional loads, and live load
notional loads for the moment frame are given as follows:

<!-- p. 493 -->

III-49

<!-- p. 494 -->

III-50

<!-- p. 495 -->

III-51

<!-- p. 496 -->

III-52

<!-- p. 497 -->

III-53

CALCULATION OF REQUIRED STRENGTH - THREE METHODS

Three methods of determining the required strength including second-order effects are included
below. A fourth method – second-order analysis by amplified first-order analysis – is found in
Section C2.2b or the Specification. The method requires the inclusion of notional loads in the
analysis, but all required strengths can be determined from a first-order analysis. For guidance
on applying these methods, see the discussion in Manual Part 2 titled Required Strength,
Effective Length, and Second-Order Effects.

GENERAL INFORMATION FOR ALL THREE METHODS

Seismic load dominates over winds loads in the moment frame direction of this example
building. Although the frame analysis that follows was run for all LRFD and ASD load
combinations, the column unity design check is highly dependent on the moment portion, and
therefore, the controlling equations are those with the load combinations shown below. A
typical column near the middle of the frame is analyzed, but the first interior columns and the
end columns were also checked. Beam analysis is covered after the three different methods are
shown for the typical interior column.

Note: The second-order analysis and the unity checks are based on the moments and column
loads for the particular load combination being checked, and not on the envelope of maximum
values.

METHOD 1. EFFECTIVE LENGTH METHOD
This method accounts for second-order effects in frames by amplifying the axial forces and Specification
moments in members and connections from a first-order analysis. C2.2a

A first-order frame analysis is run using the load combinations for LRFD or ASD. A minimum
lateral load (notional load) equal to 0.2% of the gravity loads is included for any load case for
which the lateral load is not already greater. The general load combinations are in ASCE 7 and
are summarized in Part 2 of the Manual.

A summary of the axial loads, moments and 1st floor drifts from the first-order computer
analysis is shown below:

LRFD ASD
1.2D ± 1.0E + 0.5L + 0.2S D ± (W or 0.7 E) (Controls for columns)
(Controls for columns and beams) D + 0.75(W or 0.7E) + 0.75L
\+ 0.75(Lr or S or R) (Controls for beams)

For Interior Column Design: For Interior Column Design:
Pu = 335 kips Pa = 247 kips
M1u = 157 kip-ft (from first-order analysis) M1a = 110 kip-ft (from first-order analysis)
M2u = 229 kip-ft (from first-order analysis) M2a = 161 kip-ft (from first-order analysis)

First-order first floor drift = 0.562 in. First-order first floor drift = 0.394 in.

The required second-order flexural strength, Mr, and axial strength, Pr, are as follows:
For typical interior columns the gravity-load moments are approximately balanced, therefore,
Mnt = 0.0 kip-ft

<!-- p. 498 -->

III-54

LRFD ASD
Mr = B1Mnt + B2Mlt Mr = B1Mnt + B2Mlt Specification
Eqn C2-1a
Determine B1 Determine B1

Pr = required second-order axial strength Pr = required second-order axial strength Specification
using LRFD or ASD load combinations, using LRFD or ASD load combinations, Section C2.1b
kips. kips.

Note that for members in axial compression Note that for members in axial compression
Pr may be taken as Pr = Pnt + Plt. For a long Pr may be taken as Pr = Pnt + Plt. For a long
frame, such as this one, the change in load to frame, such as this one, the change in load to
the interior columns, associated with lateral the interior columns, associated with lateral
load is negligible. load is negligible.

Therefore, Pr = 335 kips Therefore, Pr = 247 kips
(from previous calculations) and (from previous calculations) and

I = 1,110 in.4 (W14×99) I = 1,110 in.4 (W14×99)

π 2 EI π 2 EI
Pel = 2 Pel = 2 Specification
( K1 L ) ( K1 L ) Eqn C2-5

4 4 π ( 29,000 ksi )(1,110 in ) π ( 29,000 ksi )(1,110 in )
\= 2 = 2
(1.0 ) ( (13.5 ft )(12 in/ft ) ) (1.0 ) ( (13.5 ft )(12 in/ft ) )

\= 12,100 kips = 12,100 kips
Specification
Cm = 0.6 – 0.4(M1 / M2) Cm = 0.6 – 0.4(M1 / M2) Eqn C2-4

\= 0.6 – 0.4 (157 kip-ft / 229 kip-ft) = 0.6 – 0.4 (110 kip-ft / 161 kip-ft)

\= 0.326 = 0.326

α = 1.0, α = 1.6,

C m C m B1 = B1 =
⎛ αPr ⎞ ⎛ αPr ⎞ Specification
1 −⎜ ⎟ 1 −⎜ ⎟ Eqn C2-2 ⎝ Pe1 ⎠ ⎝ Pe1 ⎠

0.326 0.326
\= =
⎛ (1.0 )( 335 kips ) ⎞ ⎛ (1.6 )( 247 kips ) ⎞
1 −⎜ ⎟ 1 −⎜ ⎟ ⎝ 12,100 kips ⎠ ⎝ 12,100 kips ⎠

\= 0.335 ≥ 1; Use 1.0 = 0.337 ≥ 1; Use 1.0

<!-- p. 499 -->

III-55

Calculate B2 Calculate B2

1 1
B2 = B2 =
Pnt ⎞ ⎛ α ∑ Pnt ⎞ ⎛ α ∑ 1 −⎜ ⎟ 1 −⎜ ⎟ ⎜ ⎟ ⎜ ⎟ Pe 2 Pe 2 ⎝ ∑ ⎠ ⎝ ∑ ⎠
where: where:

α = 1.0, α= 1.6,

Pnt = 3,750 kips (from computer output)∑ Pnt = 5,250 kips (from computer output) ∑
and and Specification
HL HL Section C2.1b ∑ ∑ Pe 2 may be taken as = RM∑ Pe 2 may be taken as = RM ∑ ∆ H ∆ H
where RM is taken as 0.85 for moment frames where RM is taken as 0.85 for moment frames

H = D + 0.7 E H = 1.2 D + 1.0 E + 0.5 L + 0.2 S ∑∑
\= 195 kips (Horizontal) = 137 kips (Horizontal)
(from previous seismic force (from previous seismic force
distribution calculations) distribution calculations)

∆ H = 0.562 in. (from computer output) ∆ H = 0.394 in. (from computer output)

(195 kips )(13.5 ft )(12 in/ft ) (137 kips )(13.5 ft )(12 in/ft ) Specification
0.85 0.85 Eqn C2-6b ∑ eP 2 =∑ eP 2 = 0.562 in. 0.394 in.

\= 47,800 kips = 47,900 kips
1 1
B2 = B2 = Specification
Pnt ⎞ Pnt ⎞ ⎛ α ∑ ⎛ α ∑ 1 −⎜ ⎟ 1 −⎜ ⎟ Eqn C2-3 ⎜ ⎟ ⎜ ⎟ Pe 2 Pe 2 ⎝ ∑ ⎠ ⎝ ∑ ⎠
1 1
\= =
⎛ (1.0 )( 5,250 kips ) ⎞ ⎛ (1.6 )( 3,750 kips ) ⎞
1 −⎜ ⎟ 1 −⎜ ⎟
⎝ 47,800 kips ⎠ ⎝ 47,900 kips ⎠

\= 1.12 ≥ 1 = 1.14 ≥ 1

Calculate amplified moment Calculate amplified moment

\= (1.0)(0.0 kip-ft) + (1.12)(229 kip-ft) = (1.0)(0.0 kip-ft) + (1.14)(161 kip-ft)

\= 256 kip-ft = 184 kip-ft

Calculate amplified axial load Calculate amplified axial load

Pr = 335 kips Pr = 247 kips
(from computer analysis) (from computer analysis)

<!-- p. 500 -->

III-56

Pr = Pnt + B2Plt Pr = Pnt + B2Plt

\= 335 kips + (1.12)(0.0 kips) = 247 kips + (1.14)(0.0 kips)

\= 335 kips = 247 kips

Determine the controlling effective length Determine the controlling effective length

For out-of-plane buckling in the braced For out-of-plane buckling in the braced
frame frame

Ky=1.0 Ky=1.0
Commentary
For in-plane buckling in the moment frame, For in-plane buckling in the moment frame, Section C2.2b
use the nomograph use the nomograph

Kx=1.43 Kx=1.43

To account for leaning columns in the To account for leaning columns in the
controlling load case controlling load case

For leaning columns, For leaning columns,
Q = 2140 kips∑ Q = 3010 kips ∑
P = 1740 kips∑ P = 2490 kips ∑

Q Q ∑ ∑ K = K o 1 + K = K o 1 +
P P ∑ ∑
3010 2140
\= 1.43 1 + = 2.13 = 1.43 1 + = 2.14
2490 1740
KL x 2.13(13.5) KL x 2.14(13.5) = = 17.3 = = 17.4
rx / ry 1.66 rx / ry 1.66

<!-- p. 501 -->

III-57

Pc = 1,041 kips (W14 × 99 @ KL = 17.3 ft) Pc = 692 kips (W14 × 99 @ KL = 17.4 ft) Specification
Sect H1.1
Manual
Pr 335 kips Pr 247 kips Table 4-1 = = 0.321 ≥ 0.2 = = 0.357 ≥ 0.2
Pc 1,041 kips Pc 692 kips

Manual
M cx = 646 kip-ft (W14 × 99) M cx = 430 kip-ft (W14 × 99) Table 3-2

Pr ⎛⎞8 ⎛ M rx M ry ⎞ Pr ⎛⎞8 ⎛ M rx M ry ⎞ + ⎜⎟⎜ + ⎟ + ⎜⎟⎜ + ⎟ SpecificationPc ⎝⎠⎝9 M cx M cy ⎠ Pc ⎝⎠⎝9 M cx M cy ⎠ Eqn H1-1a

⎛⎞8 ⎛ 256 kip-ft ⎞ ⎛⎞8 ⎛ 184 kip-ft ⎞
\= 0.321 + ⎜⎟⎜ ⎟ = 0.357 + ⎜⎟⎜ ⎟ ⎝⎠⎝9 646 kip-ft ⎠ ⎝⎠⎝9 430 kip-ft ⎠

\= 0.673 ≤ 1.0 o.k. = 0.737 ≤ 1.0 o.k.

<!-- p. 502 -->

III-58

METHOD 2. SIMPLIFIED DETERMINATION OF REQUIRED STRENGTH
A method of second-order analysis based upon drift limits and other assumptions is described in
Chapter 2 of the Manual. A first-order frame analysis is run using the load combinations for
LRFD or ASD. A minimum lateral load (notional load) equal to 0.2% of the gravity loads is
included for any load case for which the lateral load is not already greater.

LRFD ASD
1.2D ± 1.0E + 0.5L + 0.2S (Controls D ± (W or 0.7 E) (Controls columns)
columns and beams)
D + 0.75(W or 0.7E) + 0.75L
\+ 0.75(Lr or S or R) (Controls beams)

For a first-order analysis For a first-order analysis

For Interior Column Design: For Interior Column Design:
Pu = 335 kips Pa = 247 kips
M1u = 157 kip-ft (from first-order analysis) M1a = 110 kip-ft (from first-order analysis)
M2u = 229 kip-ft (from first-order analysis) M2a = 161 kip-ft (from first-order analysis)

First-floor first-order drift = 0.562 in. First-floor first-order drift = 0.394 in.

Then the following steps are executed.

LRFD ASD
Step 1: Step 1:

Lateral load = 195 kips Lateral load = 140 kips

Deflection due to first-order elastic analysis Deflection due to first-order elastic analysis

∆ = 0.562 in. between first and second floor ∆ = 0.394 in. between first and second floor

Floor height = 13.5 ft Floor height = 13.5 ft

Drift ratio = (13.5 ft)(12 in/ft) / 0.562 in Drift ratio = (13.5 ft)(12 in/ft) / 0.394 in

\= 288 = 411

Step 2: Step 2:

Design story drift limit = 0.025 hxs Design story drift limit = 0.025 hxs IBC Table
1617.3.1
\= h/400 = h/400

Adjusted Lateral load = (288/ 400)(195 kips) Adjusted Lateral load = (411 / 400)(137 kips)

\= 141 kips = 141 kips

<!-- p. 503 -->

III-59

Step 3: Step 3: (for an ASD design the ratio must be
factored by 1.6)
total story load total story load Load ratio = (1.0 ) Load ratio = (1.6 )
lateral load lateral load

5,250 kips 3,750 kips = (1.0 ) = (1.6 )
141 kips 141 kips

\= 37.2 = 42.6
Manual
Interpolating from the table: B2 = 1.1 Interpolating from the table: B2 = 1.1 Page 2-12

Which matches the value obtained in the first Which matches the value obtained in the first
method to the 2 significant figures of the method to the 2 significant figures of the
table table
Note: Because the table is intentionally based on two significant figures, this value is taken as
1.1 rather than an interpolated value > 1.1. This convenient selection is within the accuracy of
the method. Since the selection is in the shaded area of the chart, K=1.0.

Step 4. Multiply all the forces and moment from the first-order analysis by the value obtained
from the table.

LRFD ASD
Mr = B2(Mnt + Mlt) Mr = B2(Mnt + Mlt)

\= 1.1(0 kip-ft + 229 kip-ft) = 252 kip-ft = 1.1(0 kip-ft + 161 kip-ft) = 177 kip-ft

Pr = 1.1(Pnt + Plt) Pr = 1.1(Pnt + Plt)

\= 1.1(335 kips +0.0 kips) = 368 kips = 1.1(247 kips +0.0 kips) = 272 kips

Pr 368 kips Pr 272 kips Specification For = = 0.323 ≥ 0.2 For = = 0.358 ≥ 0.2 Sect H1.1 Pc 1,140 kips Pc 759 kips
where
Pc = 1,140 kips (W14 × 99 @ KL =13.5 ft) Pc = 759 kips (W14 × 99 @ KL = 13.5 ft) Manual
Table 4-1
Manual
M cx = 646 kip-ft (W14 × 99) M cx = 430 kip-ft (W14 × 99) Table 3-2

Specification 8 ⎛ 8 ⎛ M ry ⎞ M ry ⎞ ⎛⎞ ⎛⎞ M rx M rx Pr Pr Eqn H1-1a + + + + ⎜ ⎟ ⎜ ⎟ ⎜⎟ ⎜⎟ Pc ⎝⎠⎝9 M cx M cy ⎠ Pc ⎝⎠⎝9 M cx M cy ⎠

⎛⎞8 ⎛ 252 kip-ft ⎞ ⎛⎞8 ⎛ 177 kip-ft ⎞
\= 0.323 + ⎜⎟⎜ ⎟ = 0.358 + ⎜⎟⎜ ⎟ ⎝⎠⎝9 646 kip-ft ⎠ ⎝⎠⎝9 430 kip-ft ⎠

\= 0.670 ≤ 1.0 o.k. = 0.724 ≤ 1.0 o.k.

<!-- p. 504 -->

III-60

METHOD 3. DIRECT ANALYSIS METHOD
Second-order analysis by the direct analysis method is found in Appendix 7 of the Specification.
This method requires that both the flexural stiffness and axial stiffness be reduced and that 0.2%
notional lateral loads be applied in the analysis. The combination of these two modifications
account for the second-order effects and the results for design can be taken directly from the
analysis. A summary of the axial loads, moments and 1st floor drifts from first-order analysis is
shown below:

LRFD ASD
1.2D ± 1.0E + 0.5L + 0.2S (Controls D ± (W or 0.7 E) (Controls columns)
columns and beams) D + 0.75(W or 0.7E) + 0.75L
\+ 0.75(Lr or S or R) (Controls beams)
For a 1st order analysis with notional loads For a 1st order analysis with notional loads
and reduced stiffness: and with reduced stiffness:

For Interior Column Design: For Interior Column Design:
Pu = 335 kips Pa = 247 kips
M1u = 157 kip-ft (from first-order analysis) M1a = 110 kip-ft
M2u = 229 kip-ft (from first-order analysis) M2a = 161 kip-ft

First-floor drift due First-floor drift due
to reduced stiffnesses = 0.703 in. to reduced stiffnesses = 0.493 in.

Note: For ASD, this method requires multiplying the ASD load combinations by a factor of 1.6
in analyzing the drift of the structure, and then dividing the results by 1.6 to obtain the required
strengths. The ASD forces shown above include the multiplier of 1.6.

LRFD ASD
For this method, K =1.0. For this method, K =1.0

Manual
Pc = 1,140 kips (W14 × 99 @ KL = 13.5 ft) Pc = 759 kips (W14 × 99 @ KL = 13.5 ft) Table 4-1

Specification Pr 335 kips Pr 247 kips = = 0.294 ≥ 0.2 = = 0.325 ≥ 0.2 Sect H1.1
Pc 1,140 kips Pc 759 kips
Manual
M cx = 646 kip-ft (W14 × 99) M cx = 430 kip-ft (W14 × 99) Table 3-2

Mr = B1Mnt + B2Mlt Mr = B1Mnt + B2Mlt

Determine B1 Determine B1

Pr = required second-order axial strength Pr = required second-order axial strength
using LRFD or ASD load combinations, using LRFD or ASD load combinations,
kips. kips.

Note that for members in axial compression Note that for members in axial compression
Pr may be taken as Pr = Pnt + Plt. For a long Pr may be taken as Pr = Pnt + Plt. For a long
frame, such as this one, the change in load to frame, such as this one, the change in load to
the interior columns, associated with lateral the interior columns, associated with lateral
load is negligible. load is negligible.

Therefore, Pr = 335 kips Therefore, Pr = 247 kips
(from previous calculations) and (from previous calculations) and

<!-- p. 505 -->

III-61

I = 1,110 in.4 (W14×99) I = 1,110 in.4 (W14×99)

π 2 EI π 2 EI
Pel = 2 Pel = 2
( K1 L ) ( K1 L )

4 4 π ( 29,000 ksi )(1,110 in ) π ( 29,000 ksi )(1,110 in )
\= 2 = 2
(1.0 ) ( (13.5 ft )(12 in/ft ) ) (1.0 ) ( (13.5 ft )(12 in/ft ) )

\= 12,106 kips = 12,100 kips

Cm = 0.6 – 0.4(M1 / M2) Cm = 0.6 – 0.4(M1 / M2)

\= 0.6 – 0.4 (157 kip-ft / 229 kip-ft) = 0.6 – 0.4 (110 kip-ft / 161 kip-ft)

\= 0.326 = 0.327

α = 1.0, α = 1.6,

C m C m B1 = B1 =
⎛ αPr ⎞ ⎛ αPr ⎞
1 −⎜ ⎟ 1 −⎜ ⎟ ⎝ Pe1 ⎠ ⎝ Pe1 ⎠

0.326 0.327
\= =
⎛ (1.0 )( 335 kips ) ⎞ ⎛ (1.6 )( 247 kips ) ⎞
1 −⎜ ⎟ 1 −⎜ ⎟ ⎝ 12,100 kips ⎠ ⎝ 12,100 kips ⎠

\= 0.335 ≥ 1; Use 1.0 = 0.338 ≥ 1; Use 1.0

Calculate B2 Calculate B2
1 1
B2 = B2 =
Pnt ⎞ ⎛ α ∑ Pnt ⎞ ⎛ α ∑ 1 −⎜ ⎟ 1 −⎜ ⎟ ⎜ ⎟ ⎜ ⎟ Pe 2 Pe 2 ⎝ ∑ ⎠ ⎝ ∑ ⎠
where: where:

α = 1.0, α= 1.6,

Pnt = 3,750 kips (from computer output)∑ Pnt = 5,250 kips (from computer output) ∑
HL HL ∑ ∑ Pe 2 may be taken as = RM Pe 2 may be taken as = RM ∑∑ ∆ H ∆ H
where RM is taken as 0.85 for moment frames where RM is taken as 0.85 for moment frames

H = D + 0.7 E H = 1.2 D + 1.0 E + 0.5 L + 0.2 S ∑∑
\= 195 kips (Horizontal) = 137 kips (Horizontal)
(from previous seismic force (from previous seismic force
distribution calculations) distribution calculations)

<!-- p. 506 -->

III-62

∆ H = 0.703 in. ∆ H = 0.493 in. (from computer output)

(195 kips )(13.5 ft )(12 in/ft ) (137 kips )(13.5 ft )(12 in/ft )
0.85 0.85∑ eP 2 = ∑ eP 2 = 0.703 in. 0.493 in.

\= 38,200 kips = 38,300 kips
1 1
B2 = B2 =
Pnt ⎞ ⎛ α ∑ Pnt ⎞ ⎛ α ∑ 1 −⎜ ⎟ 1 −⎜ ⎟
Pe 2 ⎠ ⎝ ∑ Pe 2 ⎠ ⎝ ∑
1 1
\= =
⎛ (1.0 )( 5,250 kips ) ⎞ ⎛ (1.6 )( 3,750 kips ) ⎞
1 −⎜ ⎟ 1 −⎜ ⎟ ⎝ 38,200 kips ⎠ ⎝ 38,300 kips ⎠

\= 1.16 ≥ 1 = 1.19 ≥ 1

Calculate amplified moment Calculate amplified moment

\= (1.0)(0.0 kip-ft) + (1.16)(229 kip-ft) = (1.0)(0.0 kip-ft) + (1.19)(161 kip-ft)

\= 266 kip-ft = 192 kip-ft

Calculate amplified axial load Calculate amplified axial load

Pr = 335 kips Pr = 247 kips
(from computer analysis) (from computer analysis)

Pr = Pnt + B2Plt Pr = Pnt + B2Plt

\= 335 kips + (1.16)(0.0 kips) = 247 kips + (1.19)(0.0 kips)

\= 335 kips = 247 kips

Pr ⎛⎞8 ⎛ M rx M ry ⎞ Pr ⎛⎞8 ⎛ M rx M ry ⎞
\+ ⎜⎟⎜ + ⎟ + ⎜⎟⎜ + ⎟ SpecificationPc ⎝⎠⎝9 M cx M cy ⎠ Pc ⎝⎠⎝9 M cx M cy ⎠ Eqn H1-1b

⎛⎞8 ⎛ 266 kip-ft ⎞ ⎛⎞8 ⎛ 192 kip-ft ⎞
\= 0.294 + ⎜⎟⎜ ⎟ = 0.325 + ⎜⎟⎜ ⎟ ⎝⎠⎝9 646 kip-ft ⎠ ⎝⎠⎝9 430 kip-ft ⎠

\= 0.660 ≤ 1.0 = 0.722 ≤ 1.0

<!-- p. 507 -->

III-63

BEAM ANALYSIS IN THE MOMENT FRAME

The controlling load combinations for the beams in the frames are shown below and evaluated
for the second floor beam. The dead load, live load and seismic moments were taken from
computer analysis.

LRFD ASD
1.2D + 1.0E +0.5L D + 0.7E

\=1.2(153 kip-ft) +1.0(117 kip-ft) =153 kip-ft + 0.7(112 kip-ft)
\+ 0.5(80.5 kip-ft) =153 kip-ft + 78.4 kip-ft
\=184 kip-ft + 117 kip-ft + 40.3 kip-ft =231 kip-ft
\=341 kip-ft controls
D + 0.75(0.7E) + 0.75L
\=153 kip-ft + 0.75(0.7)(112 kip-ft)
\+ 0.75(80.5 kip-ft)
\= 153 kip-ft + 58.8 kip-ft + 60.4 kip-ft
\= 272 kip-ft controls

The available moment is 503 kip-ft The available moment is 334 kip-ft Manual
503 kip-ft > 341 kip-ft o.k. 334 kip-ft > 272 kip-ft o.k. Table 3-2

Note: because the typical exterior beam was increased to a W24×55 to help with drift, all load
combinations resulted in less demand than the available moment strength of the beam.

The ends of these beams can be designed by one of the techniques illustrated in the Chapter IIB
of the design examples.

<!-- p. 508 -->

III-64

BRACED FRAME ANALYSIS

The braced frames at Grids 1 and 8 were analyzed for their lateral loads. The same stability
design requirements from Chapter C were applied to this system.

Second-order analysis by amplified first-order analysis Specification
C2.1b
The following is a method to account for second-order effects in frames by amplifying the
axial forces and moments in members and connections from a first-order analysis.

First a first-order frame analysis is run using the load combinations for LRFD and ASD. From
this analysis the critical axial loads, moments, and deflections are obtained.

The required second-order flexural strength, Mr, and axial strength, Pr, are as follows:

LRFD ASD
π 2 EI π 2 EI Specification
Pel = 2 Pel = 2 Eqn C2-5
( K1 L ) ( K1 L )

4 4 π ( 29,000 ksi )( 425 in ) π ( 29,000 ksi )( 425 in )
\= 2 = 2
(1.0 ) ( (13.5 ft )(12 in/ft ) ) (1.0 ) ( (13.5 ft )(12 in/ft ) )

\= 4,635 kips = 4,635 kips

I = 425 in 4 (W12 × 58) I = 425 in 4 (W12 × 58)

1 1
B2 = B2 =
Pnt ⎞ Specification ⎛ α ∑ Pnt ⎞ ⎛ α ∑ 1 −⎜ ⎟ 1 −⎜ ⎟ Eqn C2-3 ⎜ ⎟ ⎜ ⎟ Pe 2 Pe 2 ⎝ ∑ ⎠ ⎝ ∑ ⎠

1 1
\= =
⎛ (1.0 )( 5,452 kips ) ⎞ ⎛ (1.6 )( 3,894 kips ) ⎞
1 −⎜ ⎟ 1 −⎜ ⎟
⎝ 150,722 kips ⎠ ⎝ 150,722 kips ⎠

\= 1.04 ≥ 1 = 1.04 ≥ 1

Pnt = 3,894 kips (from computer output) ∑ Pnt = 5,452 kips (from computer output) ∑

HL HL ∑ ∑ Pe 2 = RM Pe 2 = RM ∑ ∑ ∆ H ∆ H Specification
Eqn C2-6b
(195 kips )(13.5 ft )(12 in/ft ) (137 kips )(13.5 ft )(12 in/ft ) = 1.0 = 1.0
0..210 in. 0.147 in.

\= 150,722 kips = 150,722 kips

<!-- p. 509 -->

III-65

H = D + 0.7 E ∑ H = 1.2 D + 1.0 E + L + 0.2 S ∑

\= 195 kips = 137 kips
(from previous calculations) (from previous calculations)

∆ H = 0.210 in. (from computer output) ∆ H = 0.147 in. (from computer output)

Pr = Pnt + B2Plt Pr = Pnt + B2Plt Specification
Eqn C2-1b
\= 242 kips + (1.04)(220 kips) = 173 kips + (1.04)(179 kips)

\= 470 kips = 360 kips

Pc = 553 kips (W12 × 58) Pc = 368 kips (W12 × 58) Manual
Table 4-1

Pr 470 kips Pr 360 kips For = = 0.850 ≤ 1.0 For = = 0.977 ≤ 1.0
Pc 553 kips Pc 368 kips

Note: Notice that the lower displacements of the braced frame produce much lower values for
B2. Similar values could be expected for the other two methods of analysis.

<!-- p. 510 -->

III-66

ANALYSIS OF DRAG STRUTS

The fourth floor has the highest force to the ends of the building at E = 80.3 kips (from previous calculations).
The beams at the end of the building which span 22.5 ft are W16×31

The loads for these edge beams with a DL of 0.75 ksf (5.5 ft) and exterior wall at 0.503 kip/ft and a LL of 0.80 ksf
(5.5 ft) are DLtot = 0.916 kip/ft, LLtot = 0.440 kip/ft.

The controlling load combinations are LRFD (1.2D+1.0E+0.50L) and ASD (1.0D+0.75(0.7E)+0.75L) or
(D+0.7E)

LRFD ASD
Mu = 1.2(58.0 kip-ft) + 0.50(27.8 kip-ft) Ma = 1.0(58.0 kip-ft) + 0.75(27.8 kip-ft)

\= 83.5 kip-ft = 78.9 kip-ft
or

Ma = 58.0 kip-ft

Load from the diaphragm shear Load from the diaphragm shear

Fp = 80.3 kips Fp = 0.75(0.70)(80.3 kips) = 42.2 kips

or

Fp = 0.70(80.3 kips) = 56.2 kips

Load to the drag struts Load to the drag struts

Only the two 45 ft long segments on either side of the brace can transfer load into the brace,
because the stair opening is in front of the brace.

LRFD ASD

V= 80.3 kips /2(45 ft) = 0.892 kip/ft V= 42.2 kips /2(45 ft) = 0.469 kip/ft
or
V= 56.2 kips /2(45 ft) = 0.624 kip/ft

The top flange stress due to bending The top flange stress due to bending

\= 83.5 kip-ft(12 in/ft) / 47.2 in3 = 78.9 kip-ft(12 in/ft) / 47.2 in3

\= 21.2 ksi = 20.1 ksi
or

\= 58.0 kip-ft(12 in/ft) / 47.2 in3

\= 14.7 ksi

Note: It is often possible to resist the drag strut force using the slab directly. For illustration
purposes, this solution will instead use the beam to resist the force independently of the slab.
The full cross-section can be used to resist the force if the member is designed as a column
braced at one flange only (plus any other intermediate bracing present, such as from filler
beams). Alternatively, a reduced cross-section consisting of the top flange plus a portion of the
web can be used. Arbitrarily use the top flange and 8 times the web thickness as an area to
carry the drag strut component.

<!-- p. 511 -->

III-67

Area = 5.53 in.(0.440 in.) + 8(0.275 in.2) = 2.43 in.2 + 0.605 in.2 = 3.04 in.2

Ignoring the small segment of the beam between Grid C and D, the stress due to the drag strut
force is:

LRFD ASD
⎛ 80.3 ft ⎞ ⎛ 80.3 ft ⎞
\= ⎜ ⎟ (0.892 kip/ft)/3.04 in.2 = 13.2 ksi = ⎜ ⎟ (0.469 kip/ft)/3.04 in.2 = 6.94 ksi ⎝ 2 ⎠ ⎝ 2 ⎠

or

\= 45 ft(0.624 kip/ft)/3.04 in.2 = 9.23 ksi

Total top flange stress Total top flange stress

\= 21.2 ksi + 13.2 ksi = 20.1 ksi + 6.49 ksi

\= 34.4 ksi. = 26.6 ksi controls

or

\= 14.7 ksi + 9.23 ksi

\= 23.9 ksi

For bending or compression φ = 0.90 For bending or compression Ω = 1.67

φFy = 45 ksi >34.4 ksi o.k. Fy / Ω = 29.9 ksi > 26.6 ksi o.k.

Note: Because the drag strut load is a horizontal load, notations indicating the method of transfer into the strut,
and the extra horizontal load which must be accommodated by the beam end connections should be indicated on
the drawings.

<!-- p. 512 -->



<!-- p. 513 -->



<!-- p. 514 -->



<!-- p. 515 -->



<!-- p. 516 -->



<!-- p. 517 -->

APPENDIX A-1

APPENDIX A

CROSS-REFERENCE LIST FOR THE
2005 AISC SPECIFICATION FOR STRUCTURAL STEEL
BUILDINGS TO PAST AISC SPECIFICATIONS

The following cross-reference list relates the new 2005 Specification for Structural Steel Buildings table of
contents to the corresponding sections, where applicable, of past AISC specifications. Cross references are
given to the five standards that the new 2005 AISC Specification replaces:
• 1989 Specification for Structural Steel Buildings-Allowable Stress Design and Plastic Design
(1989 ASD)
• 1989 Specification for Allowable Stress Design of Single Angle Members (1989 ASD Single
Angle)
• 1999 Load and Resistance Factor Design Specification for Structural Steel Buildings (1999
LRFD)
• 2000 Load and Resistance Factor Design Specification for Steel Hollow Structural Sections (2000
LRFD HSS)
• 2000 Load and Resistance Design Specification for Single-Angle Members (2000 LRFD Single
Angle)

<!-- p. 518 -->

APPENDIX A-2

CROSS-REFERENCE LIST FOR THE 2005 AISC SPECIFICATION

AISC SPECIFICATION REFERENCES
2000 LRFD SINGLE ANGLE
2005 SPECIFICATION 1989 ASD 1999 LRFD
HSS 1989 ASD 2000 LRFD

A. GENERAL PROVISIONS
A1. Scope A1 A1 1.1 1 1
\1. Low-Seismic Applications NEW NEW NEW NEW NEW
\2. High-Seismic Applications
\3. Nuclear Applications A1
A2. Referenced Specifications, Codes and Standards A6 A6 NEW NEW NEW
A3. Material
\1. Structural Steel Materials A3.1 A3.1 1.2.1 NEW NEW
1a. ASTM Designations A3.1.a A3.1a 1.2.1
1b. Unidentified Steel A3.1b A3.1b NEW
1c. Rolled Heavy Shapes A3.1c A3.1c
1d. Built-Up Heavy Shapes A3.1c A3.1c
\2. Steel Castings and Forgings A3.2 A3.2
\3. Bolts, Washers and Nuts A3.4 A3.3
\4. Anchor Rods and Threaded Rods A3.5 A3.4
\5. Filler Metal and Flux for Welding A3.6 A3.5
\6. Stud Shear Connectors A3.7 A3.6
A4. Structural Design Drawings and Specifications A7 A7 NEW NEW NEW

B. DESIGN REQUIREMENTS
B1. General Provisions B NEW NEW NEW NEW
B2. Loads and Load Combinations A4 A4 1.3 NEW NEW
B3. Design Basis
\1. Required Strength NEW A5.1 NEW NEW NEW
\2. Limit States A5.1 A5.2
\3. Design for Strength Using Load and
NEW A5.3
Resistance Factor Design (LRFD)
\4. Design for Strength Using Allowable
A5.1 NEW
Strength Design (ASD)
\5. Design for Stability B4 B4
\6. Design of Connections J J1.1 9
6a. Simple Connections J1.2 J1.2 NEW
6b. Moment Connections J1.3 A2
\7. Design for Serviceability A5.4 A5.4
\8. Design for Ponding K2 K2
\9. Design for Fatigue K4 K3
\10. Design for Fire Conditions NEW NEW
\11. Design for Corrosion Effects L5 L5
\12. Design Wall Thickness for HSS NEW NEW 1.2.2
\13. Gross and Net Area Determination
a. Gross Area B1 B1 NEW
b. Net Area B2 B2 NEW
B4. Classification of Sections for Local Buckling B5.1 B5.1, APP. B5.1 2.2 NEW NEW
\1. Unstiffened Elements B5.1 NEW
\2. Stiffened Elements B5.1 NEW
B5. Fabrication, Erection and Quality Control M M NEW NEW NEW
B6. Evaluation of Existing Structures NEW N NEW NEW NEW

C. STABILITY ANALYSIS AND DESIGN
C1. Stability Design Requirements
\1. General Requirements B4, C1 B4 NEW NEW NEW
\2. Members Stability Design Requirements C3
\3. System Stability Design Requirements NEW
3a. Braced-Frame and Shear-Wall
C2.1 C2.1
Systems
3b. Moment-Frame Systems C2.2 C2.2
3c. Gravity Framing Systems NEW NEW
3d. Combined Systems NEW NEW

<!-- p. 519 -->

APPENDIX A-3

CROSS-REFERENCE LIST FOR THE 2005 AISC SPECIFICATION

AISC SPECIFICATION REFERENCES
2000 LRFD SINGLE ANGLE
2005 SPECIFICATION 1989 ASD 1999 LRFD
HSS 1989 ASD 2000 LRFD

C2. Calculation of Required Strengths
\1. Methods of Second-Order Analysis NEW NEW NEW NEW NEW
1a. General Second-Order Elastic
NEW
Analysis
1b. Second-Order Analysis by Amplified
First-Order Elastic Analysis C2.2

\2. Design Requirements NEW NEW NEW NEW
2a. Design by Second-Order Analysis
2b. Design by First-Order Analysis

D. DESIGN OF MEMBERS FOR TENSION
D1. Slenderness Limitations B7 B7 2.3 NEW NEW
D2. Tensile Strength D1 D1 3.1 2 2
D3. Area Determination
\1. Gross Area B1 B1 NEW NEW NEW
\2. Net Area B2 B2 NEW 2 2
\3. Effective Net Area B3 B3 2.1 2 2
D4. Built-Up Members D2 D2 NEW NEW NEW
D5. Pin-Connected Members
\1. Tensile Strength D3.1 D3.1, E5 NEW NEW NEW
\2. Dimensional Requirements NEW D3.1, E5 NEW NEW NEW
D6. Eyebars D3.3 D3.2 NEW NEW NEW

E. DESIGN OF MEMBERS FOR
COMPRESSION

E1. General Provisions E E NEW NEW NEW
E2. Slenderness Limitations and Effective Length E1 B7, E1.1 4.1.1 NEW NEW
E3. Compressive Strength for Flexural Buckling of
E2 E2 4.2 4 4
Members Without Slender Elements
E4. Compressive Strength for Torsional and Flexural-
Torsional Buckling of Members Without Slender E3 E3 4.2 NEW NEW
Elements
E5. Single Angle Compression Members NEW NEW N.A. 4 4
E6. Built-Up Members
\1. Compressive Strength E4 E4.1 NEW NEW NEW
\2. Dimensional Requirements E4 E4.2 NEW NEW NEW
E7. Members with Slender Elements App. B5 App.B5, App. E3 4.2 4 4
\1. Slender Unstiffened Elements, Qs App. B5 App. E3 N.A. 4 4
\2. Slender Stiffened Elements, Qa App. B5 App. E3 4.2 N.A. N.A.

F. DESIGN OF MEMBERS FOR FLEXURE
F1. General Provisions F F 5.1 5 5
F2. Doubly Symmetric Compact I-Shaped Members and
F1.1, F1.3 F1 N.A. N.A. N.A.
Channels Bent About Their Major Axis
\1. Yielding F1.1
\2. Lateral-Torsional Buckling F1.2
F3. Doubly Symmetric I-Shaped Members with Compact
Webs and Noncompact or Slender Flanges Bent F1.2, F1.3 App. F1 N.A. N.A. N.A.
About Their Major Axis
\1. Lateral-Torsional Buckling
\2. Compression Flange Local Buckling
F4. Other I-Shaped Members with Compact or
Noncompact Webs, Bent About Their Major Axis F1 App. F1 N.A. N.A. N.A.

\1. Compression Flange Yielding
\2. Lateral-Torsional Buckling
\3. Compression Flange Local Buckling
\4. Tension Flange Yielding

<!-- p. 520 -->

APPENDIX A-4

CROSS-REFERENCE LIST FOR THE 2005 AISC SPECIFICATION

AISC SPECIFICATION REFERENCES
2000 LRFD SINGLE ANGLE
2005 SPECIFICATION 1989 ASD 1999 LRFD
HSS 1989 ASD 2000 LRFD

F5. Doubly Symmetric and Singly Symmetric I-Shaped
Members with Slender Webs Bent About Their G2 App. F1 N.A. N.A. N.A.
Major Axis
\1. Compression Flange Yielding
\2. Lateral-Torsional Buckling
\3. Compression Flange Yielding
\4. Tension Flange Yielding NEW NEW
F6. I-Shaped Members and Channels Bent About Their
F2 App. F1 N.A. N.A. N.A.
Minor Axis
\1. Yielding
\2. Flange Local Buckling
F7. Square and Rectangular HSS and Box-Shaped
F3 App. F1 5.1 N.A. N.A.
Members
\1. Yielding
\2. Flange Local Buckling
\3. Web Local Buckling
F8. Round HSS F3 App. F1 5.1 N.A. N.A.
\1. Yielding
\2. Local Buckling
F9. Tees and Double Angles Loaded in the Plane of
NEW F1.2c NEW N.A. N.A.
Symmetry
\1. Yielding
\2. Lateral-Torsional Buckling
\3. Flange Local Buckling of Tees NEW
F10. Single Angles NEW NEW N.A. 5 5
\1. Yielding 5.1.2 5.1.2
\2. Lateral-Torsional Buckling 5.1.3 5.1.3
\3. Leg Local Buckling 5.2.2 5.2.2
F11. Rectangular Bars and Rounds F2 App. F1 5 N.A. N.A.
\1. Yielding 5.1
\2. Lateral-Torsional Buckling NEW
F12. Unsymmetrical Shapes NEW NEW N.A. N.A. N.A.
\1. Yielding
\2. Lateral-Torsional Buckling
\3. Local Buckling
F13. Proportions of Beams and Girders
\1. Hole Reductions B10 B10 NEW NEW NEW
\2. Proportioning Limits for I-Shaped Members
G1 App. G1

\3. Cover Plates B10 B10
\4. Built-Up Beams F6 NEW

G. DESIGN OF MEMBERS FOR SHEAR
G1. General Provisions F4 F2 NEW NEW NEW
G2. Members with Unstiffened or Stiffened Webs
\1. Nominal Shear Strength F4 F2, App. F2, App. G3 5.2 NEW NEW
\2. Transverse Stiffeners F5 App. F2.3 N.A. NEW NEW
G3. Tension Field Action
\1. Limits on the Use of Tension Field Action
G3 App. G3 N.A. NEW NEW

\2. Nominal Shear Strength with Tension Field
G3 App. G3 N.A. NEW NEW Action
\3. Transverse Stiffeners G4 App. G4 N.A. NEW NEW
G4. Single Angles NEW NEW N.A. 3 3
G5. Rectangular HSS and Box Members NEW F2 5.2 N.A. N.A.
G6. Round HSS NEW NEW 5.2 N.A. N.A.
G7. Weak Axis Shear in Singly and Doubly Symmetric
NEW H2 NEW N.A. N.A.
Shapes
G8. Beams and Girders with Web Openings NEW F4 NEW NEW NEW

<!-- p. 521 -->

APPENDIX A-5

CROSS-REFERENCE LIST FOR THE 2005 AISC SPECIFICATION

AISC SPECIFICATION REFERENCES
2000 LRFD SINGLE ANGLE
2005 SPECIFICATION 1989 ASD 1999 LRFD
HSS 1989 ASD 2000 LRFD

H. DESIGN OF MEMBERS FOR COMBINED
FORCES AND TORSION

H1. Doubly and Singly Symmetic Members Subject to
Flexural and Axial Force

\1. Doubly and Singly Symmetric Members in
H1 H1.2 7.1 6.1 6.1 Flexure and Compression
\2. Doubly and Singly Symmetric Members in
H2 H1.1 7.1 6.2 6.2
Flexure and Tension
\3. Doubly Symmetric Members in Single Axis
NEW NEW 7.2 N.A. N.A.
Flexure and Compression
H2. Unsymmetric and Other Members Subject to Flexura
H1 H2 N.A. N.A. N.A.
and Axial Force
H3. Members Under Torsion and Combined Torsion,
Flexure, Shear and/or Axial Force
\1. Torsional Strength of Round and Rectangular
NEW H2 6.1 N.A. N.A.
HSS
\2. HSS Subject to Combined Torsion, Shear,
H2 7.2 N.A. N.A.
Flexure and Axial Force
\3. Strength of Non-HSS Members under
H2 N.A. NEW NEW
Torsion and Combined Stress

I. DESIGN OF COMPOSITE MEMBERS
I1. General Provisions I NEW NEW NEW NEW
\1. Nominal Strength of Composite Sections
NEW NEW

1a. Plastic Stress Distribution Method

1b. Strain-Compatibilty Method
\2. Material Limitations I2.1
\3. Shear Connectors I4 I5.1
I2. Axial Members
\1. Encased Composite Columns
1a. Limitations NEW I2.1 NEW NEW NEW
1b. Compressive Strength E2 I2.2
1c. Tensile Strength D1 NEW
1d. Shear Strength F4 NEW
1e. Load Transfer NEW I2.4
1f. Detailing Requirements NEW I2.1, I5.6
1g. Strength of Stud Shear Connectors
A 3. 7 I5.3

\2. Filled Composite Columnns
2a. Limitations NEW I2.1 NEW N.A. N.A.
2b. Compressive Strength I2.2
2c. Tensile Strength NEW
2d. Shear Strength NEW
2e. Load Transfer I2.4
2f. Detailing Requirements I5.6
I3. Flexural Members
\1. General
1a. Effective Width I1 I3.1 NEW NEW NEW
1b. Shear Strength NEW NEW
1c. Strength During Construction I2 I3.4
\2. Strength of Composite Beams with Shear
Connectors
2a. Positive Flexural Strength I2 I3.2
2b. Negative Flexural Strength NEW I3.2
2c. Strength of Composite Beams with
I5 I3.5
Formed Steel Deck
2d. Shear Connectors I4 I5
\3. Flexural Strength of Concrete-Encased and
NEW, I2 I3.3
Filled Members
I4. Combined Axial Force and Flexure NEW I4 7.1 NEW NEW
I5. Special Cases I6 I6 NEW N.A. N.A.

<!-- p. 522 -->

APPENDIX A-6

CROSS-REFERENCE LIST FOR THE 2005 AISC SPECIFICATION

AISC SPECIFICATION REFERENCES
2000 LRFD SINGLE ANGLE
2005 SPECIFICATION 1989 ASD 1999 LRFD
HSS 1989 ASD 2000 LRFD

J. DESIGN OF CONNECTIONS
J1. General Provisions
\1. Design Basis J1.1 J1.1 NEW NEW NEW
\2. Simple Connections J1.2 J1.2, B9
\3. Moment Connections J1.3 J1.3
\4. Compression Members with Bearing Joints
J1.4 J1.4

\5. Splices in Heavy Sections J1.7 J1.5
\6. Beam Copes and Weld Access Holes J1.8 J1.6
\7. Placement of Welds and Bolts J1.9 J1.8
\8. Bolts in Combination with Welds J1.10 J1.9
\9. High-Strength Bolts in Combination with
J1.11 J1.10
Rivets
\10. Limitations on Bolted and Welded
J1.12 J1.11
Connections
J2. Welds J2 J2 9.2 NEW NEW
\1. Groove Welds J2.1 J2.1 9.2
\2. Fillet Welds J2.2 J2.2 9.2
\3. Plug and Slot Welds J2.3 J2.3 NEW
\4. Strength J2.4 J2.4, App. J2.4
\5. Combination of Welds J2.5 J2.5
\6. Filler Metal Requirements NEW J2.6
\7. Mixed Weld Metal J2.6 J2.7
J3. Bolts and Threaded Parts
\1. High-Strength Bolts J3.1 J3.1 NEW NEW NEW
\2. Size and Use of Holes J3.2 J3.2
\3. Minimum Spacing J3.8 J3.3
\4. Minimum Edge Distance J3.9 J3.4
\5. Maximum Spacing and Edge Distance J3.10 J3.5
\6. Tension and Shear Strength of Bolts and
J3.4 J3.6
Threaded Parts
\7. Combined Tension and Shear in Bearing-
J3.5 J3.7, App. J3.7
Type Connections
\8. High-Strength Bolts in Slip-Critical
NEW J3.8, App. J3.8
Connections
\9. Combined Tension and Shear in Slip-Critical
J3.6 J3.9, App. J3.9
Connections
\10. Bearing Strength at Bolt Holes J3.7 J3.10 9.1.1 NEW NEW
\11. Speical Fasteners NEW NEW 9.1.2
\12. Tension Fasteners NEW NEW 9.1.3
J4. Affected Elements of Members and Connecting
Elements
\1. Strength of Elements in Tension NEW J4.2, J5.2 9.3.2 NEW NEW
\2. Strength of Elements in Shear NEW J4.1, J5.3 9.3.1
\3. Block Shear Strength J4, J5.2 J4.3 NEW
\4. Strength of Elements in Compression NEW NEW NEW
J5. Fillers J6 J6 NEW NEW NEW
J6. Splices J7 J7 NEW NEW NEW
J7. Bearing Strength J8 J8 9.1.1 NEW NEW
J8. Column Bases and Bearing on Concrete J9 J9 NEW NEW NEW
J9. Anchor Rods and Embedments NEW J10 NEW NEW NEW

<!-- p. 523 -->

APPENDIX A-7

CROSS-REFERENCE LIST FOR THE 2005 AISC SPECIFICATION

AISC SPECIFICATION REFERENCES
2000 LRFD SINGLE ANGLE
2005 SPECIFICATION 1989 ASD 1999 LRFD
HSS 1989 ASD 2000 LRFD

J10. Flanges and Webs with Concentrated Forces K1 K1 NEW NEW NEW
\1. Flange Local Bending K1.2 K1.2
\2. Web Local Yielding K1.3 K1.3
\3. Web Crippling K1.4 K1.4
\4. Web Sidesway Buckling K1.5 K1.5
\5. Web Compression Buckling K1.6 K1.6
\6. Web Panel Zone Shear K1.7 K1.7
\7. Unframed Ends of Beams and Girders NEW K1.8
\8. Additional Stiffener Requirements for
K1.8 K1.9
Concentrated Forces
\9. Additional Doubler Plate Requirements for
NEW K1.10
Concentrated Forces

K. DESIGN OF HSS AND BOX MEMBER
CONNECTIONS

K1. Concentrated Forces on HSS
\1. Definitions of Parameters NEW NEW NEW N.A. N.A.
\2. Limits of Applicability NEW
\3. Concentrated Force Distribution Transversely

3a. Criterion for Round HSS 8.1a
3b. Criteria for Rectangular HSS 8.1b, 9.2
\4. Concentrated Force Distributed
Longitudinally at the Center of the HSS
Diameter or Width, and Acting Perpendicular 8.2
to the HSS Axis
4a. Criterion for Round HSS 8.2a
4b. Criterion for Rectangular HSS 8.2b
\5. Concentrated Force Distributed
Longitudinally at the Center of the HSS
Width, and Acting Parallel to the HSS Axis NEW

\6. Concentrated Axial Force on the End of a
8.3
Rectangular HSS with a Cap Plate
K2. HSS-to-HSS Truss Connections NEW NEW 9.4, 9.3.4 N.A. N.A.
\1. Definitions of Parameters 9.4.1
\2. Criteria for Round HSS 9.4.2
2a. Limits of Applicability 9.4.2a
2b. Branches with Axial Loads in T-, Y-
9.4.2b
and Cross-Connections
2c. Branches with Axial Loads in K-
9.4.2b
Connections
\3. Criteria for Rectangular HSS 9.4.3
3a. Limits of Applicability 9.4.3a
3b. Branches with Axial Loads in T-,Y-
NEW NEW 9.4.3b NEW NEW
and Cross-Connections
3c. Branches with Axial Loads in
9.4.3c
Gapped K-Connections
3d. Branches with Axial Loads in
NEW
Overlapped K-Connections
3e. Welds to Branches 9.2
K3. HSS-to-HSS Moment Connections NEW NEW 9.4 N.A. N.A.
\1. Definitions of Parameters 9.4.1
\2. Criteria for Round HSS 9.4.2
2a. Limits of Applicability 9.4.2a
2b. Branches with Axial Loads in T-, Y-
9.4.2b
and Cross-Connections
2c. Branches with Out-of-Plane Bending
Moments in T-, Y- and Cross- NEW
Connections
2d. Branches with in-Plane Bending
Moments in T-,Y- and Cross- NEW
Connections

<!-- p. 524 -->

APPENDIX A-8

CROSS-REFERENCE LIST FOR THE 2005 AISC SPECIFICATION

AISC SPECIFICATION REFERENCES
2000 LRFD SINGLE ANGLE
2005 SPECIFICATION 1989 ASD 1999 LRFD
HSS 1989 ASD 2000 LRFD

\3. Criteria for Rectangular HSS NEW NEW 9.4.3 N.A. NEW
3a. Limits of Applicability 9.4.3a
3b. Branches with In-Plane Bending
Moments in T- and Cross- NEW
Connections
3c. Branches with Out-of-Plane Bending
Moments in T- and Cross-
Connections
3d. Branches with Combined Bending
Moment and Axial Force in T- and
Cross-Connections

L. DESIGN FOR SERVICEABILITY
L1. General Provisions L L NEW NEW NEW
L2. Camber L1 L1 NEW NEW NEW
L3. Deflections L3.1 L3.1 NEW NEW NEW
L4. Drift L3 L3.3 NEW NEW NEW
L5. Vibration L3.2 L3.2 NEW NEW NEW
L6. Wind-Induced Motion NEW NEW NEW NEW NEW
L7. Expansion and Contraction L2 L2 NEW NEW NEW
L8. Connection Slip L4 L4 NEW NEW NEW

M. FABRICATION, ERECTION AND
QUALITY CONTROL

M1. Shop and Erection Drawings M1 M1 NEW NEW NEW
M2. Fabrication
\1. Cambering, Curving and Straightening M2.1 M2.1 NEW NEW NEW
\2. Thermal Cutting M2.2 M2.2
\3. Planing of Edges M2.3 M2.3
\4. Welded Construction M2.4 M2.4
\5. Bolted Construction M2.5 M2.5
\6. Compression Joints M2.6 M2.6
\7. Dimensional Tolerances M2.7 M2.7
\8. Finish of Column Bases M2.8 M2.8
\9. Holes for Anchor Rods NEW NEW
\10. Drain Holes 10 N.A. N.A.
\11. Requirements for Galvanized Members NEW NEW NEW
M3. Shop Painting
\1. General Requirements M3.1 M3.1 NEW NEW NEW
\2. Inaccessible Surfaces M3.2 M3.2 NEW
\3. Contact Surfaces M3.3 M3.3 NEW
\4. Finished Surfaces M3.4 M3.4 NEW
\5. Surfaces Adjacent to Field Welds M3.5 M3.5 10
M4. Erection
\1. Alignment of Column Bases M4.1 M4.1 NEW NEW NEW
\2. Bracing M4.2 M4.2
\3. Alignment M4.3 M4.3
\4. Fit of Column Compression Joints and Base
M4.4 M4.4
Plates
\5. Field Welding M4.5 M4.5 10
\6. Field Painting M4.6 M4.6 NEW
\7. Field Connections M4.7 M4.7 NEW
M5. Quality Control M5 M5 NEW NEW NEW
\1. Cooperation M5.1 M5.1
\2. Rejections M5.2 M5.2
\3. Inspection of Welding M5.3 M5.3
\4. Inspection of Slip-Critical High-Strength
M5.4 M5.4 Bolted Connections
\5. Identification of Steel M5.5 M5.5

<!-- p. 525 -->

APPENDIX A-9

CROSS-REFERENCE LIST FOR THE 2005 AISC SPECIFICATION

AISC SPECIFICATION REFERENCES
2000 LRFD SINGLE ANGLE
2005 SPECIFICATION 1989 ASD 1999 LRFD
HSS 1989 ASD 2000 LRFD

Appendix 1. INELASTIC ANALYSIS AND
DESIGN

1.1 General Provisions NEW NEW NEW NEW NEW
1.2 Materials NEW NEW NEW NEW NEW
1.3 Moment Redistribution NEW NEW NEW NEW NEW
1.4 Local Buckling NEW B5.2 2.2.2 NEW NEW
1.5 Stability and Second-Order Effects NEW C1.1 NEW NEW NEW
\1. Braced Frames NEW
\2. Moment Frames
1.6 Columns and Other Compression Members NEW NEW NEW NEW NEW
1.7 Beams and Others Flexural Members NEW F1.3 5.3 NEW NEW
1.8 Members Under Combined Forces NEW NEW NEW NEW NEW
1.9 Connections NEW NEW NEW NEW NEW

Appendix 2. DESIGN FOR PONDING
2.1 Simplified Design for Ponding K2 K2 NEW NEW NEW
2.2 Improved Design for Ponding NEW App. K2 NEW NEW NEW

Appendix 3. DESIGN FOR FATIGUE
3.1 General K4, App. K4 K3, App. K3.1 NEW NEW NEW
3.2 Calculation of Maximum Stresses and Stress Ranges
App. K4.2 App. K3.2 NEW NEW NEW

3.3 Design Stress Range App.K4.2 App. K3.3 NEW NEW NEW
3.4 Bolts and Threaded Parts App. K4.3 App. K3.4 NEW NEW NEW
3.5 Special Fabrication and Erection Requirements NEW App. K3.5 NEW NEW NEW

Appendix 4. STRUCTURAL DESIGN FOR
FIRE CONDITIONS NEW NEW NEW NEW NEW

Appendix 5. EVALUATION OF EXISTING
STRUCTURES

5.1 General Provisions NEW N1 NEW NEW NEW
5.2 Material Properties
\1. Determination of Required Tests NEW N2.1 NEW NEW NEW
\2. Tensile Properties N2.2
\3. Chemical Composition N2.3
\4. Base Metal Notch Toughness N2.4
\5. Weld Metal N2.5
\6. Bolts and Rivets N2.6
5.3 Evaluation by Structural Analysis
\1. Dimensional Data NEW N3.1 NEW NEW NEW
\2. Strength Evaluation N3.2
\3. Serviceabiltity Evaluation N3.3
5.4 Evaluation by Load Tests
\1. Determination of Load Rating by Testing
NEW N4.1 NEW NEW NEW

\2. Serviceabiltity Evaluation N4.2
5.5 Evaluation Report N5

Appendix 6. STABILITY BRACING FOR
COLUMNS AND BEAMS NEW C3 NEW NEW NEW

Appendix 7. DIRECT ANALYSIS METHOD
NEW NEW NEW NEW NEW
