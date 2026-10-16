---
type: libro
title: "4.- SAFE Tutorial v. 12 Ingles"
author: ""
categoria: "AYUDAS DE PROGRAMAS"
paginas: 112
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/SAFE/4.- SAFE Tutorial v. 12 Ingles.pdf"
convertido: 2026-10-16
---

# 4.- SAFE Tutorial v. 12 Ingles

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\SAFE\4.- SAFE Tutorial v. 12 Ingles.pdf` (112 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

™
SAFE
DESIGN OF SLABS, BEAMS AND FOUNDATIONS
REINFORCED AND POST-TENSIONED CONCRETE

Tutorial

ISO SAF120108M3 Version 12.0.0
Berkeley, California, USA December 2008

<!-- p. 2 -->

Copyright

Copyright © Computers & Structures, Inc., 1978-2008
All rights reserved.

The CSI Logo® is a registered trademark of Computers & Structures, Inc. SAFE TM and
Watch & Learn TM are trademarks of Computers & Structures, Inc. Adobe and Acrobat are
registered trademarks of Adobe Systems Incorported. AutoCAD is a registered trademark
of Autodesk, Inc.

The computer program SAFE TM and all associated documentation are proprietary and
copyrighted products. Worldwide rights of ownership rest with Computers & Structures,
Inc. Unlicensed use of this program or reproduction of documentation in any form,
without prior written authorization from Computers & Structures, Inc., is explicitly
prohibited.

No part of this publication may be reproduced or distributed in any form or by any
means, or stored in a database or retrieval system, without the prior explicit written
permission of the publisher.

Further information and copies of this documentation may be obtained from:

Computers & Structures, Inc.
1995 University Avenue
Berkeley, California 94704 USA

Phone: (510) 649-2200
FAX: (510) 649-2299
e-mail: info@csiberkeley.com (for general questions)
e-mail: support@csiberkeley.com (for technical support questions)
web: www.csiberkeley.com

<!-- p. 3 -->

DISCLAIMER

CONSIDERABLE TIME, EFFORT AND EXPENSE HAVE GONE INTO THE
DEVELOPMENT AND TESTING OF THIS SOFTWARE. HOWEVER, THE USER
ACCEPTS AND UNDERSTANDS THAT NO WARRANTY IS EXPRESSED OR
IMPLIED BY THE DEVELOPERS OR THE DISTRIBUTORS ON THE ACCURACY
OR THE RELIABILITY OF THIS PRODUCT.

THIS PRODUCT IS A PRACTICAL AND POWERFUL TOOL FOR STRUCTURAL
DESIGN. HOWEVER, THE USER MUST EXPLICITLY UNDERSTAND THE BASIC
ASSUMPTIONS OF THE SOFTWARE MODELING, ANALYSIS, AND DESIGN
ALGORITHMS AND COMPENSATE FOR THE ASPECTS THAT ARE NOT
ADDRESSED.

THE INFORMATION PRODUCED BY THE SOFTWARE MUST BE CHECKED BY
A QUALIFIED AND EXPERIENCED ENGINEER. THE ENGINEER MUST
INDEPENDENTLY VERIFY THE RESULTS AND TAKE PROFESSIONAL
RESPONSIBILITY FOR THE INFORMATION THAT IS USED.

<!-- p. 4 -->



<!-- p. 5 -->

Contents

Introduction

Introduction v

Reinforced Concrete Example

The Project 1

Navigating Through SAFE 2

Step 1 Begin a New Model 3
Set the Units 4
Define the Grid 4
Save the Model 8

Step 2 Define Properties 8
Define Material Properties 8
Define Slab and Drop Properties 10
Define Beam Properties 13
Define Column Properties 14
Define Wall Properties 16

Step 3 Define Static Load Patterns 18

Step 4 Define Load Cases 18

i

<!-- p. 6 -->

SAFE - Tutorial

Step 5 Draw Objects 20
Draw Slabs 20
Draw Columns 23
Draw Walls 25
Draw Beams 29
Draw Openings (Area Objects) 30

Step 6 Add Design Strips 30

Step 7 Set Display Options 34

Step 8 Assign Loads 36

Step 9 Run the Analysis and Design 38

Step 10 Graphically Review the Analysis
Results 39

Step 11 Design Display 41

Step 12 Run Detailing 46

Step 13 Create Report 49

Post-Tensioned Concrete Example

The Project 53

Navigating Through SAFE 54

Step 1 Begin a New Model 55
Set the Units 56
Define the Grid 56
Save the Model 61

Step 2 Define Properties 61
Define Material Properties 62
Define Slab Properties 63
Define Tendon Properties 65
Define Column Properties 66
Define Wall Properties 68

Step 3 Define Static Load Patterns 69

Step 4 Define Load Cases 70

ii

<!-- p. 7 -->

Contents

Step 5 Draw Objects 72
Draw Slabs 72
Draw Columns 75
Draw Walls 77
Draw Openings (Area Objects) 79
Draw Design Strips 81

Step 6 Add Tendons 83

Step 7 Set Display Options 88

Step 8 Assign Loads 89

Step 9 Run the Analysis and Design 92

Step 10 Graphically Review the Analysis
Results 92

Step 11 Design Display 95

Step 12 Run Detailing 97

Step 13 Create Report 101

iii

<!-- p. 8 -->



<!-- p. 9 -->

Introduction

The two examples in this tutorial provide step-by-step illustrations of
how SAFE can be used to create, analyze, design and detail concrete slab
systems. The first example is for a mild-reinforced concrete slab (R/C),
and the second example deals with a post-tensioned structure (P/T).
Although the general procedure is similar for both examples, the structures and specific details differ.

v

<!-- p. 10 -->

Reinforced Concrete

R/C Example

The intent of this tutorial is to give you hands-on experience via step-by-
step instructions on how to use SAFE to model, analyze, design and
detail mild reinforced concrete slabs. Fundamentals of the model creation
process are identified and various model construction techniques are
introduced. As you complete the tutorial, you will build the model shown
in Figure 1.

The Project

The tutorial project is an irregularly shaped suspended concrete slab,
with overall dimensions of 113 feet by 120 feet. A large opening exists in
the interior for stair access. The 10-inch thick slab is supported by 12-
inch-thick walls, 16-inch-thick drop panels on columns, and 18-inch by
24-inch beams on two perimeter sides. Columns are 18 inches square,
drop panels are typically 6 feet square, and the story height below the
slab is 12 feet. The model will be analyzed for a uniform dead load of 30
pounds per square foot (psf) plus the self weight of the structure and a
live load of 50 psf.

1

<!-- p. 11 -->

SAFE Tutorial – R/C

Concrete Materials:
A. Concrete strength, f’c = 4000 psi
B. Unit weight of concrete = 150 pcf
Mild-steel reinforcing:
C. fy = 60 ksi

Figure 1 The Project Model

Navigating Through SAFE
The SAFE program provides the user with two principal ways to navi-
gate through program commands: menu commands or toolbar buttons.
All commands are available through the main menu bar (e.g., Draw
menu > Draw Columns), and a majority of the menu commands are
also available as buttons on toolbars (e.g., Draw Columns, ). The
availability of a button on the toolbar is indicated in the menus by the
existence of an icon to the left of the command, as shown in Figure 2.

2 Navigating Through SAFE

<!-- p. 12 -->

Step 1 Begin a New Model

Figure 2 Draw Menu

In this tutorial, the reference to various commands will be given using
the narrative description, i.e., Draw menu > Draw Column command,
in lieu of the associated button.

Step 1 Begin a New Model

In this Step, the dimensions and basic grid will be defined, which will
serve as a guide for developing the model. This model will be built with-
out using the automated template tools provided in SAFE to demonstrate
how to construct a model from scratch. However, as a general rule, we
highly recommend using templates to start models whenever possible
because they provide a quick, easy way of generating a model. Consult
the SAFE Help topics for information about templates.

Step 1 Begin a New Model 3

<!-- p. 13 -->

SAFE Tutorial – R/C

Set the Units

If the units shown in the drop-down list in the lower right-hand corner of
the SAFE window are not lb-ft, scroll through the drop-down list to set
the units to lb-ft.

Define the Grid

A. Click the File menu > New Model command to access the New
Model Initialization form shown in Figure 3. This form is used to
specify the starting point of the model creation: a Blank screen, a
screen with a Grid Only, or one of eight templates. Default units also
may be selected here, along with the design code and preferences.

Figure 3 New Model Initialization form

B. In the Design Data area, select ACI 318-08 from the Design Code
drop-down list.

C. In the Initial Model area, click the Grid Only button to display the
Coordinate System Definition form shown in Figure 4. This form is
used to specify the number of grids and spacing in each direction. It
is important that the grid be defined such as to accurately represent

4 Step 1 Begin a New Model

<!-- p. 14 -->

Step 1 Begin a New Model

the geometry of the structure; so it is advisable to spend time care-
fully planning the number and spacing of the grid lines.

D. Select the Cartesian option.

E. As shown in Figure 4, set the Number of Grid Lines in the X Direc-
tion to 6 and in the Y Direction to 7. Set the Spacing in the X Direc-
tion to 20 feet and in the Y Direction to 18 feet.

Figure 4 Coordinate System Definition form

F. Click the Edit Grid button to display the form shown in Figure 5.
The Coordinate System form is used to modify and edit the grid
definitions, as well as set the top of model datum. It also allows the
user to set the display options associated with the grids.

\1. In the Display Grid Data as area, select the Spacing option.

\2. In the X Grid Data table, change the X spacing as follows:

Step 1 Begin a New Model 5

<!-- p. 15 -->

SAFE Tutorial – R/C

Figure 5 Coordinate System form

Grid ID Change X Spacing to

A 26
D 27

\3. In the Y Grid Data table, change the Y spacing as follows:

Grid ID Change Y Spacing to

3 24
4 24

\4. Click the OK button to accept your changes.

6 Step 1 Begin a New Model

<!-- p. 16 -->

Step 1 Begin a New Model

Upon closing the Coordinate System form, by default, the grid sys-
tem displays in the main SAFE window, with two windows tiled ver-
tically: a Model Explorer window on the left and a Plan View on the
right. The number of view windows can be changed using the Op-
tions menu > Windows command.

G. Click the View menu > Set Display Options command to display
the Set Display Options form. Uncheck the Horizon option and click
the OK button to exit that form. The Horizon option displays a plane
that resembles an engineering calculation grid to illustrate the datum
plane location; we are turning this option off to display our coordi-
nate system grid better.

You should now have a display similar to that shown in Figure 6.

Display Title Bar (active)

Global Axes

Units

Figure 6 SAFE Main Window

Note that the Plan View window is active. When a window is
active, the display title bar is highlighted. Set a window active by
clicking anywhere in the window.

Note that the Global Axes are displayed and that the Z positive is in
the “up” direction. When SAFE refers to the direction of gravity, this
is in the negative Z direction, or “down.”

Step 1 Begin a New Model 7

<!-- p. 17 -->

SAFE Tutorial – R/C

Save the Model

Save your model often! Click the File menu > Save command. Specify
the directory in which to save the model. For this tutorial, specify the file
name as Slab.

Typically a model would be saved with the same name. However to
record work at various stages of development or as a backup, the File
menu > Save As command can be used to save the file using another
name.

Step 2 Define Properties

In this Step, material and
section properties for the
slab (area object) and
beams (line objects), col-
umns, and walls are de-
fined. Note that previously
defined materials and
properties may be re-
viewed and modified us-
ing the Model Explorer
window (see Figure 7). To
do this, expand any of the
property items on the tree
by clicking the + node,
and then double click on
the desired item to display
the associated form.

Figure 7 Model Explorer
window

Define Material Properties

A. Click the Define menu > Materials command to access the Materi-
als form shown in Figure 8.

8 Step 2 Define Properties

<!-- p. 18 -->

Step 2 Define Properties

Figure 8 Materials form

B. Highlight 4000Psi in the Materials area, and click the Modify/Show
Material button to display the Material Property Data form shown in
Figure 9. That form lists the properties associated with 4000psi con-
crete; this is the concrete property that will be used in our model.

Figure 9 Material Property Data form

Step 2 Define Properties 9

<!-- p. 19 -->

SAFE Tutorial – R/C

C. Click the OK button to accept this material as defined.

D. In the Materials area, highlight A615Gr60.

E. Click the Modify/Show Material button to display the Material
Property Data form shown in Figure 10. This form lists the proper-
ties associated with Grade 60 reinforcing; this is the rebar property
that will be used in our model.

F. Click the OK button to accept this material as defined.

G. Click the OK button on the Materials form to accept all of the de-
fined materials.

H. Click the File menu > Save command to save your model.

Figure 10 Material Property Data form

Define Slab and Drop Properties

A. Click the Define menu > Slab Properties command to access the
Slab Properties form shown in Figure 11.

10 Step 2 Define Properties

<!-- p. 20 -->

Step 2 Define Properties

Figure 11 Slab Properties form

B. In the Slab Property area, highlight SLAB1.

C. Recall that for this tutorial project, the slab thickness is 10 inches. To
adjust the default dimensions of SLAB1, click the Modify/Show
Property button to access the Slab Property Data form shown in
Figure 12.

\1. Select Slab from the Type drop-down list in the Analysis Prop-
erty Data area; this ensures that any area object with this prop-
erty assignment will be identified as a slab member.

\2. Type 10in in the Thickness edit box in the Analysis Property
Data area.

Note: When the units are explicitly stated, in this case inches
(in), the program automatically converts the number input to be
consistent with the database units (recall that the units have
been set to lb-ft). The value also may have been input as 10/12,
without the inch identifier.

\3. Click the OK button to accept the changes and return to the Slab
Properties form.

Step 2 Define Properties 11

<!-- p. 21 -->

SAFE Tutorial – R/C

Figure 12 Slab Property Data form

D. Recall that the project has 16-inch-thick drop panels on columns. To
specify a property for the drop panel, click the Add New Property
button on the Slab Properties form and complete the following.

\1. Type DROP in the Property Name edit box on the Slab Property
Data form.

\2. Select Drop from the Type drop-down list in the Analysis Prop-
erty Data area.

Note: When multiple area objects occupy the same location in
plan, SAFE determines which property value to use in the stiff-
ness formula based on the following hierarchy: the Drop type
has priority over a Slab type.

\3. Type 16in in the Thickness edit box.

\4. Click the OK button to accept the changes and return to the Slab
Properties form.

12 Step 2 Define Properties

<!-- p. 22 -->

Step 2 Define Properties

E. Click the OK button to end the slab property definitions. Click the
File menu > Save command to save the model.

Define Beam Properties

A. Click the Define menu > Beam Properties command to access the
Beam Properties form shown in Figure 13.

Figure 13 Beam Properties form

B. In the Beam Property area, highlight BEAM1.

C. Click the Modify/Show Property button to access the Beam Prop-
erty Data form shown in Figure 14. Recall that the beams for the pro-
ject are 18 inches by 24 inches (or 1.5 by 2 feet in the currently
specified lb-ft units).

\1. In the Analysis Property Data area, select L Beam from the Beam
Shape Type drop-down list.

\2. In the Analysis Property Data area, type 1.5 into the Web Width
at Top edit box, type 1.5 into the Web Width at Bottom edit box,
type 2 into the Depth edit box, type 5 into the Flange Width edit
box, and 10/12 into the Slab Depth edit box.

Step 2 Define Properties 13

<!-- p. 23 -->

SAFE Tutorial – R/C

Figure 14 Beam Property Data form

\3. In the Design Property Data area, type 1.5 into the Web Width at
Top edit box, type 1.5 into the Web Width at Bottom edit box,
type 2 into the Depth edit box, select the Auto option, and type
10in into the Slab Depth edit box.

\4. Click the OK button to end the beam property definition.

D. Click the OK button to leave the Beam Properties form. Click the
File menu > Save command to save your model.

Define Column Properties

A. Click the Define menu > Column Properties command to access
the Column Properties form.

B. In the Column Property area, highlight COL1.

C. Click the Modify/Show Property button to access the Column
Property Data form shown in Figure 15. Recall that the columns for
the project are 18 inches square and that the drop panels are 6 feet
square.

14 Step 2 Define Properties

<!-- p. 24 -->

Step 2 Define Properties

Figure 15 Column Property Data form

\1. In the Column Section Dimensions area, select Rectangular from
the Column Shape drop-down list.

\2. In the Column Section Dimensions area, type 1.5 (or 18in) into
the Parallel to 2-Axis edit box and type 1.5 (or 18in) into the
Parallel to 3-Axis edit box.

\3. Make sure that the Include Automatic Rigid Zone Area Over
Column option is checked. This option restricts deformation of
the slab at the column location, which prevents unrealistic peaks
in moment distribution from occurring.

\4. In the Automatic Drop Panel Dimensions area, check the Include
Automatic Drop Panel Over Column option. This option auto-
matically adds a drop panel when a column with this property is
drawn.

Step 2 Define Properties 15

<!-- p. 25 -->

SAFE Tutorial – R/C

\5. In the Automatic Drop Panel Dimensions area, type 6 into the
Parallel to 2-Axis edit box and type 6 into the Parallel to 3-Axis
edit box.

\6. In the Automatic Drop Panel Dimensions area, select DROP
from the Slab Property drop-down list.

\7. Click the OK button to leave the Column Property Data form.

D. Click the Add New Property button to access the Column Property
Data form.

\1. In the General Data area, type COL-PER in the Property Name
edit box.

\2. In the Column Section Dimensions area, select Rectangular from
the Column Shape drop-down list.

\3. In the Column Section Dimensions area, type 1.5 into the Paral-
lel to 2-Axis edit box and type 1.5 into the Parallel to 3-Axis edit
box.

\4. Make sure that the Include Automatic Rigid Zone Area Over
Column option is checked.

\5. In the Automatic Drop Panel Dimensions area, make sure that
the Include Automatic Drop Panel Over Column option is un-
checked.

\6. Click the OK button to leave the Column Property Data form.

E. Click the OK button to accept the Column Property definitions.

Define Wall Properties

A. Click the Define menu > Wall Properties command to access the
Wall Properties form.

B. In the Wall Property area, highlight Wall1.

16 Step 2 Define Properties

<!-- p. 26 -->

Step 2 Define Properties

C. Click the Modify/Show Property button to access the Wall Property
Data form shown in Figure 16. Recall that the walls for the project
are 12 inches thick.

Figure 16 Wall Property Data form

\1. In the Wall Dimensions area, type 1 into the Thickness edit box.

\2. Make sure that the Include Automatic Rigid Zone Area Over
Wall option is checked. This option restricts deformation of the
slab at the wall location, which prevents unrealistic peaks in
moment distribution from occurring.

\3. Click the OK button to leave the Wall Property Data form.

D. Click the OK button to accept the Wall Property definition.

This completes the material and section property definition phase of the
model creation. The slab and beam properties will be assigned in the
model datum plane, while the columns and walls will be assigned as
supports. Supports also can be assigned as point restraints, point springs
or line springs. Support stiffnesses are calculated by SAFE based on the
cross-sectional properties, material properties, and lengths specified
when the columns and walls are drawn.

Step 2 Define Properties 17

<!-- p. 27 -->

SAFE Tutorial – R/C

Step 3 Define Static Load Patterns

In this Step, the dead and live static load patterns are defined. That is, we
will name the various types of loads and specify the self-weight multipli-
ers. The loads will be assigned to objects, and the values for the loads
specified (uniform dead load of 30 psf and live load of 50 psf), in Step 8.

A. Click the Define menu > Load Patterns command to access the
Static Load Case Names form shown in Figure 17.

Figure 17 Load Patterns form

B. Note that load patterns DEAD and LIVE are defined by default.

C. Recall that the project will be analyzed for the dead load plus the self
weight of the structure. Thus, the Self Weight Multiplier should be
set equal to 1 (this will include 1.0 times the self weight of all mem-
bers) for the DEAD load. Only the DEAD load pattern should have a
non-zero Self Weight Multiplier.

D. Click the OK button to accept the defined static load patterns.

E. Click the File menu > Save command.

Step 4 Define Load Cases

In this Step, the Load Cases are defined. This is where the type of analy-
sis is specified.

18 Step 3 Define Static Load Patterns

<!-- p. 28 -->

Step 4 Define Load Cases

A. Click the Define menu > Load Cases command to access the Load
Cases form shown in Figure 18.

Figure 18 Load Cases form

B. With the DEAD Load Case Name highlighted, click the Mod-
ify/Show Case button to display the Load Case Data form shown in
Figure 19. This data form changes based on the type of load case
specified.

\1. In the Load Case Type area, select Static from the drop-down
list. Modal and Hyperstatic also are available as load case types.

\2. In the Analysis Type area, select the Linear option. When work-
ing with a Static Load Case Type, the program offers the option
to do Linear, Nonlinear (Allow Uplift), Nonlinear (Cracked), or
Nonlinear (Long Term Cracked) analysis. For our tutorial exam-
ple, a Static, Linear analysis will be performed for DEAD and
LIVE.

\3. In the Loads Applied area, verify that the load pattern is DEAD
with a scale factor of 1.

\4. Click the OK button to close the Load Case Data form.

Step 4 Define Load Cases 19

<!-- p. 29 -->

SAFE Tutorial – R/C

Figure 19 Load Cases Data form

C. Review the LIVE load case, if so desired, by selecting it and using
the Modify/Show Case button as described for the DEAD load case.

D. Click the OK button to close the Load Cases form.

E. Click the File menu > Save command.

Step 5 Draw Objects

In this Step, slabs, columns with drops, beams, walls, and openings will
be drawn.

Draw Slabs

Ensure that the Plan View is active (click anywhere in the display win-
dow; a window is active when the Display Title Bar, just below the hori-

20 Step 5 Draw Objects

<!-- p. 30 -->

Step 5 Draw Objects

zontal toolbar, is highlighted). Now draw area objects to model the slab
using the following Action Items.

A. Click the Draw menu > Snap Options command to display the
Snap Options form shown in Figure 20.

Figure 20 Snap Options form

B. In the Snap to area, make sure that the Points and Grid Intersections
options are checked. These snap options will assist in accurately po-
sitioning objects when drawing.

C. In the Snap Increments area, make sure that the (Imperial in Inches)
Snap at length increments of option is checked. When drawing slab
edges, beams and walls, a dimension line will appear and the object
will snap to the values specified in this edit box.

D. Click the OK button to close the Snap Options form.

E. Click the Draw menu > Draw Slabs/Areas command to access the
Draw Slabs/Areas form shown in Figure 21. If the Draw Slabs/Areas
form covers part of the model, click on the blue title bar, hold down
the mouse button, and drag it out of the way.

Step 5 Draw Objects 21

<!-- p. 31 -->

SAFE Tutorial – R/C

Figure 21 Draw Slabs/Areas form

F. Make sure that the Type of Object is set to Slab. If it is not, click
once in the drop-down list opposite the Type of Object item and
select Slab.

G. Click in the Property drop-down list and select SLAB1. This is the
slab property defined in Step 2.

H. Click in the Edge Drawing Type drop-down list and select Straight
Line. Although not used in this project, slab edges also may be
drawn with arcs and curves.

I. To draw the first corner of the slab, click once in the Plan View at
the intersection of grid lines A and 7 (the cursor should display Grid
Point A 7 at the correct location). Then moving clockwise around the
grid (note how the slab edge is dimensioned as you draw), click once
at these grid intersections in this order to draw the outline of the slab:
F7, F1, D1, D3, and A3. After clicking at grid A3, press the Enter
key on the keyboard. The shaded slab object should now appear.

If you have made a mistake while drawing this object, click the Se-
lect menu > Select > Pointer/Window command to leave the Draw
mode and go to the Select mode. Then click the Edit menu > Undo
Area Add command, and repeat Items E through I.

J. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Slabs/Areas
command.

K. Select the slab by clicking on it anywhere. The status bar in the
lower left-hand corner should show “1 Areas, 6 Edges selected.” If

22 Step 5 Draw Objects

<!-- p. 32 -->

Step 5 Draw Objects

you make a mistake in selecting, press the Select menu > Clear Se-
lection command and try again.

L. Click the Edit menu > Edit Areas > Expand/Shrink Areas com-
mand to display the Expand/Shrink Areas form shown in Figure 22.

M. Type 9in into the Offset Value edit box. We will use this form to ex-
pand (a positive value expands) the slab by 9 inches at each corner to
create the perimeter overhang that is needed to accommodate the
width of the columns (1/2 of 18 inches).

Figure 22 Expand/Shrink Areas form

N. Click the OK button to finish the slab.

O. Click the File menu > Save command to save your model.

Draw Columns

With the active window set as described in the preceding Draw Slabs
section (i.e., Plan View window active and the snap to points and grid intersections enabled), use the following Action Items to draw columns.

A. Click the Draw menu > Draw Columns command to access the
Draw Columns form shown in Figure 23.

B. Click in the Property Below drop-down list and select COL1. This is
the property for the 18-inch by 18-inch column with a drop panel de-
fined in Step 2.

C. Click in the Property Above drop-down list and select NONE. There
are no columns above the slab.

Step 5 Draw Objects 23

<!-- p. 33 -->

SAFE Tutorial – R/C

Figure 23 Draw Columns form

D. Click in the Height Below edit box and type 12. Note that the units
are feet.

E. Click in the Cardinal Point drop-down list and select 10 (Centroid).

F. Locate the mouse cursor just above and to the left of grid intersection
A6, hold down the left mouse button, and drag diagonally to just be-
low and to the right of E3 and release the mouse button. Columns
and drop panels should be placed at every grid intersection enclosed
by the window just drawn. Note how the drop panels are trimmed at
the slab edges.

G. Locate the mouse cursor just above and to the left of grid intersection
D2, hold down the left mouse button, and drag diagonally to just be-
low and to the right of E1 and then release. Again, columns and drop
panels should be added to the grid intersections enclosed by the win-
dow.

H. Click in the Property Below drop-down list and select COL-PER.
This is the property for the 18-inch by 18-inch column without a
drop panel for use on the perimeter.

I. Left click once at each of the following grid locations to draw the pe-
rimeter columns: A7, B7, C7, D7, E7, F7, F6, F5, F4, F3, F2, and F1.

24 Step 5 Draw Objects

<!-- p. 34 -->

Step 5 Draw Objects

J. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Columns com-
mand.

K. Locate the mouse cursor just above and to the left of grid intersection
C6, hold down the left mouse button, and drag diagonally to just be-
low and to the right of D5 and release the mouse button. The status
bar in the lower left-hand corner should show “24 Points, 4 Lines, 4
Areas, 16 Edges selected.” If the selection is not correct, simply click
the Select menu > Clear Selection command and try again.

L. Click the Edit menu > Delete command or press the Delete key on
the keyboard to remove the columns enclosed in the window.

M. Click the File menu > Save command to save your model.

N. Click the View menu > Set Default 3D View command to display
the model in 3D. Note how the columns extend below the slab.

O. Click the View menu > Set Plan View command to return to the
Plan View before continuing the project.

Draw Walls

Similar to the preceding two sections, ensure that the Plan View is active
and that the snap to points, grid intersections and the snap increments options are enabled. Now use the following Action Items to draw walls.

A. Click the Draw menu > Draw Walls command to access the Draw
Walls form shown in Figure 24.

B. Click in the drop-down list opposite the Wall Property Below item
and select WALL1. This is the wall property for the 12-inch-thick
wall defined in Step 2.

C. Click in the Wall Property Above drop-down list and select NONE.
There are no walls above the slab

D. Click in the Wall Height Below edit box and type 12. Note that the
units are feet.

Step 5 Draw Objects 25

<!-- p. 35 -->

SAFE Tutorial – R/C

Figure 24 Draw Walls form

E. Click in the drop-down list opposite the Line Drawing Type item and
select Straight Line. Although not used in this project, walls may
also be drawn with arcs and curves.

F. Left click at grid intersection C6 to begin drawing the first wall.
Draw the wall along grid line C (the wall is on grid line C if no angle
measure is shown) past grid line 5 until the snap increments dimen-
sion line shows 30 and then click again. Hit the Enter key on the
keyboard to complete the wall. This places a wall 30 feet long along
grid line C.

If you have made a mistake while drawing this object, click the Se-
lect menu > Select > Pointer/Window command to leave the Draw
mode and go to the Select mode. Then click the Edit menu > Undo
Area Object Add command, and repeat Items A through F.

G. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Walls command.

H. Hold down the Shift key on your keyboard and right click once at
the end point of the wall just drawn. A selection list similar to the
one shown in Figure 25 appears because multiple objects exist at that
location. In this example, two point objects and two area objects ex-
ist at the same location. Note that the selection list will appear only
when the Shift key is used with the click.

26 Step 5 Draw Objects

<!-- p. 36 -->

Step 5 Draw Objects

Figure 25 Selection List form

I. Highlight the first point object and click the OK button. Because a
right click action initiated the selection process, a Point Object In-
formation form similar to the one shown in Figure 26, will display.

491491

Figure 26 Point Object Information form

Step 5 Draw Objects 27

<!-- p. 37 -->

SAFE Tutorial – R/C

\1. Click on the Geometry tab. Verify that the Point Global X and Y
Coordinates are 46 and 72, respectively. If the coordinates are
not correct, re-draw the wall following the instructions described
in Item F above.

\2. Click the OK button to leave the Point Object Information form.

J. Click the Draw menu > Draw Walls command to access the Draw
Walls form.

K. For the next wall, located along grid line 6, left click at grid intersec-
tion C6 to begin drawing the wall and at intersection D6 (the snap
increment dimension line should show 20) to designate the end of the
wall.

L. With the draw mode still active, draw the last wall along grid line D
past grid line 5 until the snap increments dimension line shows 30
and then click again. Hit the Enter key on the keyboard to complete
the wall. This wall should be parallel to the first wall drawn.

M. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Walls command.
Your model should look similar to Figure 27.

Figure 27 The model after drawing columns and walls

28 Step 5 Draw Objects

<!-- p. 38 -->

Step 5 Draw Objects

Draw Beams

Similar to the previous sections, ensure that the Plan View is active and
the snap to points and grid intersections features are enabled. Draw the
beams as follows.

A. Click the Draw menu > Draw Beams/Lines command to access the
Draw Beams/Lines form shown in Figure 28.

Figure 28 Draw Beams/Lines form

B. Click in the drop-down list opposite the Property item and select
BEAM1. Recall that BEAM1 is the 18-inch by 24-inch beam defined
in Step 2.

C. Click in the Line Drawing Type drop-down list and select Straight
Line.

D. Left click once at the grid intersection A7. Click again at grid inter-
sections F7, followed by F1. Although only one beam per side was
drawn, the program will automatically mesh this single object inter-
nally into multiple beam elements to provide the correct connectivity
to the supporting columns and slab elements.

E. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Beams command.

F. Click the File menu > Save command to save your model.

Step 5 Draw Objects 29

<!-- p. 39 -->

SAFE Tutorial – R/C

Draw Openings (Area Objects)

Similar to the previous sections, ensure that the Plan View is active and
the snap to points and grid intersections features are enabled. Draw an
area object to model the opening as follows:

A. Click the Draw menu > Draw Rectangular Slabs/Areas command
to display the Draw Rectangular Slabs/Areas form shown in Figure
\29.

B. Click once in the drop-down list opposite the Type of Object item
and select Opening.

Figure 29 Draw Rectangular Slabs/Areas form

C. Left click at the intersection of grid lines C and 6, and while holding
the left mouse button down, move diagonally down to the wall end
point located along grid line D between grids 4 and 5 and release the
button. An area object with different shading should appear, indicat-
ing that an opening for the stairs has been drawn. An opening takes
priority over an object with assigned slab properties when the pro-
gram determines the stiffness formulation.

D. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Rectangular
Slabs/Areas command.

E. Click the File menu > Save command to save your model.

Step 6 Add Design Strips

In this step, design strips will be added to the model. Design strips de-
termine how reinforcing will be calculated and positioned in the slab.
Forces are integrated across the design strips and used to calculate the

30 Step 6 Add Design Strips

<!-- p. 40 -->

Step 6 Add Design Strips

required reinforcing for the selected design code. Typically design strips
are positioned in two principal directions: Layer A and Layer B.

Similar to the previous sections, ensure that the Plan View is active and
the snap to points and grid intersections features are enabled. Add design
strips to the model as follows:

A. Click the Edit menu > Add/Edit Design Strips > Add Design
Strips command to display the Add Design Strips form shown in
Figure 30.

B. In the Options area, select the Add Design Strips Along Cartesian
Grid Lines option.

C. In the Parameters area, click in the Grid Direction drop-down list and
select X.

Figure 30 Add Design Strips form

D. Select A from the Strip Layer drop-down list.

E. Select the Auto option. The added design strips will automatically
adjust their width to align with adjacent strips.

Step 6 Add Design Strips 31

<!-- p. 41 -->

SAFE Tutorial – R/C

F. Click the OK button to leave the Add Design Strips form. Design
strips along the X-axis grids should now appear as solid lines.

G. Left click on the design strips that lie on grid lines 1 and 2 to select
them; the status bar in the lower left-hand corner should show “2 De-
sign Strips selected.” If the selection is not correct, simply click the
Select menu > Clear Selection command and try again.

H. Left click on the slab (anywhere except at a column, drop panel,
beam or design strip location) to select it; the status bar in the lower
left-hand corner should now show “1 Areas, 6 Edges, 2 Design Strips
selected.”

I. Left click at grid intersection A1 and at grid intersection A2; the
status bar in the lower left-hand corner should now show “2 Points, 1
Areas, 6 Edges, 2 Design Strips selected.”

J. Click the Edit menu > Align Points/Lines/Edges command to dis-
play the Align Points/Lines/Edges form shown in Figure 31.

K. Select the Trim Line/Tendon/Strip Objects option.

Figure 31 Align Points/Lines/Edges form

L. Click the OK button to leave the Align Points/Lines/Edges form.
The design strips along grid lines 1 and 2 should now be trimmed to
the edge of the slab.

M. Left click on the design strip that lies on grid line 5 to select it; the
status bar in the lower left-hand corner should show “1 Design Strips
selected.”

32 Step 6 Add Design Strips

<!-- p. 42 -->

Step 6 Add Design Strips

N. Press the Delete key on the keyboard to remove the selected design
strip from the model.

O. Click the Draw menu > Draw Design Strips command to display
the Draw Design Strips form shown in Figure 32.

Figure 32 Draw Design Strips form

P. Select A from the Strip Layer drop-down list.

Q. Type 9 into the Start Width Left edit box.

R. Type 12 into the Start Width Right edit box.

S. Type 9 into the End Width Left edit box.

T. Type 12 into the End Width Right edit box.

U. Left click at grid intersection A5 and at C5, and then click the right
mouse button to stop drawing.

V. Left click at grid intersection D5 and at F5.

W. Press the Esc key on the keyboard to leave the Draw Design Strips
command.

X. Click the Edit menu > Add/Edit Design Strips > Add Design
Strips command to display the Add Design Strips form.

Y. Select Y from the Grid Direction drop-down list.

Z. Click in the Strip Layer edit box and select B from the drop-down
list.

Step 6 Add Design Strips 33

<!-- p. 43 -->

SAFE Tutorial – R/C

AA. Click the OK button to leave the Add Design Strips form. Design
strips along the Y-axis grids should now appear as solid lines.

BB. Left click on the design strips that lie on grid lines A, B and C to se-
lect them; the status bar in the lower left-hand corner should show “3
Design Strips selected.”

CC. Left click on the slab (anywhere except at a column, drop panel,
beam or design strip location) to select it; the status bar in the lower
left-hand corner should now show “1 Areas, 6 Edges, 3 Design Strips
selected.”

DD. Left click at grid intersections A1, B1 and C1; the status bar in the
lower left-hand corner should now show “3 Points, 1 Areas, 6 Edges,
3 Design Strips selected.”

EE. Click the Edit menu > Align Points/Lines/Edges command to dis-
play the Align Points/Lines/Edges form.

FF. Select the Trim Line/Tendon/Strip Objects option.

GG. Click the OK button to leave the Align Points/Lines/Edges form.
The design strips along grid lines A, B, and C should now be
trimmed to the edge of the slab.

HH. Click the File menu > Save command to save your model.

Step 7 Set Display Options

In this Step, the set display options will be used to alter the objects dis-
played.

A. Click the View menu > Set Display Options command. When the
Set Display Options form displays, uncheck the Design Strip Layer A
and Design Strip Layer B check boxes in the Items Present in View
area, as shown in Figure 33. This action will turn off the display of
the design strips.

34 Step 7 Set Display Options

<!-- p. 44 -->

Step 7 Set Display Options

Figure 33 Set Display Options form

B. Click the OK button to accept the changes, and the model now ap-
pears as shown in Figure 34.

Figure 34 Model after all objects have been drawn

Step 7 Set Display Options 35

<!-- p. 45 -->

SAFE Tutorial – R/C

Step 8 Assign Loads

In this Step, the dead and live loads will be assigned to the slab. Ensure
that the Plan View is still active, and that the program is in the select
mode (Draw menu > Select > Pointer/Window command).

A. Select the slab by clicking on it anywhere that is not a beam, wall,
column, drop panel or opening. The status bar in the lower left-hand
corner should show “1 Areas, 6 Edges selected.” If you make a mis-
take in selecting, click the Select menu > Clear Selection command,
and try again.

B. Click the Assign menu > Load Data > Surface Loads command to
access the Surface Loads form shown in Figure 35.

C. If it is not selected already, select DEAD from the Load Pattern
Name drop-down list.

D. Make sure lb-ft is displayed in the Units area.

Figure 35 Surface Loads form

E. In the Uniform Loads (Gravity Direction), type 30 in the Uniform
Load edit box.

36 Step 8 Assign Loads

<!-- p. 46 -->

Step 8 Assign Loads

Note: Additional load cases may be defined by clicking on the “…”
button next to the load pattern name. A “…” button returns you to the
form used to define the item in the adjacent drop-down list or edit
box, which in this case is the Load Patterns form.

F. Click the OK button to accept the dead load assignment. SAFE will
display the loads on the model. Use the Assign menu > Clear Dis-
play of Assigns command to remove the assignments from the dis-
play, if desired.

G. Click anywhere on the main slab to reselect the slab, or click the Se-
lect menu > Get Previous Selection command to select the slab.

H. Click the Assign menu > Load Data > Surface Loads command to
again access the Surface Loads form.

I. Select LIVE from the Load Pattern Name drop-down list.

J. Type 50 in the Uniform Load edit box in the Uniform Loads area.

K. Click the OK button to accept the live load assignment. Again, use
the Assign menu > Clear Display of Assigns command to remove
the assignments from the display.

L. To review the assignments to the slab, right click on the slab any-
where that is not a beam, wall, column, drop-panel or opening to ac-
cess the Slab-Type Area Object Information form shown in Figure
\36.

M. Select the Loads tab and note that the DEAD Load Pattern has a
Force per Unit Area of 30, and that the LIVE Load Pattern has a
Force per Unit Area of 50.

N. Click the OK button to close the Slab-Type Area Object Information
form.

O. Click the File menu > Save command to save your model.

Step 8 Assign Loads 37

<!-- p. 47 -->

SAFE Tutorial – R/C

Figure 36 Slab-Type Area Object Information form

Step 9 Run the Analysis and Design

In this Step, the analysis and design will be run.

A. Click the Run menu > Run Analysis & Design command to start
the analysis. The program will create the analysis model from your
object-based SAFE model and will display information in the status
bar in the lower left-hand corner as the analysis and design proceeds.
Additional information about the run may be accessed at a later time
using the File menu > Show Input/Output Text Files command
and selecting the filename with a .LOG extension.

B. When the analysis and design are finished, the program automati-
cally displays a deformed shape view of the model, and the model is
locked. The model is locked when the Options menu >
Lock/Unlock Model icon appears depressed. Locking the model
prevents any changes to the model that would invalidate the analysis
results.

38 Step 9 Run the Analysis and Design

<!-- p. 48 -->

Step 10 Graphically Review the Analysis Results

Step 10 Graphically Review the Analysis Results

In this Step, the analysis will be reviewed using graphical displays of the
results.

A. Click the View menu > Set Default 3D View command to display
the deformed shape for the DEAD load case in 3D.

B. Click the Start Animation button in the lower right-hand corner of
the display to animate the deformed shape. Speed of the animation
may be adjusted by using the slider control adjacent to the button.
Click the Stop Animation button to end the animation.

C. Click the Display menu > Show Deformed Shape command to ac-
cess the Deformed Shape form shown in Figure 37.

Figure 37 Deformed Shape form

Step 10 Graphically Review the Analysis Results 39

<!-- p. 49 -->

SAFE Tutorial – R/C

D. In the Load Case/Load Combination area, select the Load Case op-
tion.

E. Select LIVE from the Load Case drop-down list.

F. Select the Automatic option in the Scaling area.

G. Check the Draw Contours checkbox in the Contour Range area.

H. Click the OK button to generate a 3-D deformed shape with contours
for the LIVE load case.

I. Click the Display menu > Show Slab Forces/Stresses command to
bring up the Slab Forces/Stresses form shown in Figure 38.

Figure 38 Slab Forces/Stresses form

J. Select LIVE from the Load Case drop-down list.

K. Select the Resultant Forces option in the Component Type area.

L. Select the M22 option in the Component area.

M. Select the Display Contours on Deformed Shape option in the Dis-
play Options area.

40 Step 10 Graphically Review the Analysis Results

<!-- p. 50 -->

Step 11 Design Display

N. Click the OK button to generate the moment diagram shown in Fig-
ure 39.

Figure 39 M22 Moment Diagram

Note that as you move the cursor over the moment diagram, the val-
ues are displayed at the cursor and in the lower left-hand corner of
the window.

O. Click the Display menu > Show Undeformed Shape command to
clear the display of the moment diagram.

P. Click the View menu > Set Plan View command to return to the
Plan View.

Step 11 Design Display

In this Step, design results for the slab and beams will be displayed. Note
that the design was run along with the analysis in Step 9. Design results
are for the ACI 318-08 code, which was selected in Step 1. Design pref-
erences may be reviewed or changed by going to the Design menu > De-

Step 11 Design Display 41

<!-- p. 51 -->

SAFE Tutorial – R/C

sign Preferences command (some design preferences are also set on the
property data forms); be sure to re-run the analysis and design (Step 9) if
changes to the preferences are made.

A. Click the Display menu > Show Slab Design command to access
the Slab Design form shown in Figure 40.

Figure 40 Slab Design form

B. In the Choose Display Type area, select Strip Based from the Design
Basis drop-down list and Enveloping Reinforcement from the Dis-
play Type drop-down list.

C. In the Choose Strip Direction area, check the Layer A checkbox and
uncheck the Layer B checkbox. This will display the design results in
the Layer A (X) direction only.

42 Step 11 Design Display

<!-- p. 52 -->

Step 11 Design Display

D. In the Rebar Location Shown area, check the Show Top Rebar
checkbox and uncheck the Show Bottom Rebar checkbox.

E. In the Reinforcing Display Type area, select the Show Total Rebar
Area for Strip option.

F. Click the OK button to leave the Slab Design form and display the
slab design results. The top reinforcing required in the Layer A di-
rection is displayed.

Positioning the cursor at any location on a Layer A design strip
causes the required top and bottom reinforcing values to be displayed
in the lower left corner of the window and at the cursor.

G. To view the required reinforcing in the Layer B direction, click the
Display menu > Show Slab Design command to display the Slab
Design form.

H. In the Choose Strip Direction area, uncheck the Layer A checkbox
and check the Layer B checkbox.

I. Check the Show Bottom Rebar checkbox in the Rebar Location
Shown area.

J. In the Reinforcing Display Type area, select the Show Number of
Bars of Size: option and select #5 from the Top drop-down list and
\#5 from the Bottom drop-down list.

K. Click the OK button to leave the Slab Design form and display the
slab design results for the Layer B direction. The view will be up-
dated to that shown in Figure 41. Again, positioning the cursor any-
where on the strips will result in the display of the reinforcing values
in the lower left-hand corner of the SAFE window.

Step 11 Design Display 43

<!-- p. 53 -->

SAFE Tutorial – R/C

Figure 41 Layer B reinforcing

L. To view the required reinforcing in the beams, click the Display
menu > Show Beam Design command. The Beam Design form
shown in Figure 42 displays.

M. In the Choose Display Type area, select Longitudinal Rebar from the
Display Type drop-down list and Flexure from the Rebar Type drop-
down list.

N. Review the other selected options and then click the OK button to
close the Beam Design form.

The view will be updated to show the flexural reinforcing required in
the beams along the two perimeter sides. Positioning the cursor on
the beams will result in the display of the reinforcing values in the
lower left-hand corner and at the cursor.

44 Step 11 Design Display

<!-- p. 54 -->

Step 11 Design Display

Figure 42 Beam Design form

O. Right click on a beam to display the Design Details form shown in
Figure 43.

Figure 43 Design Details form

Step 11 Design Display 45

<!-- p. 55 -->

SAFE Tutorial – R/C

Scroll through the form to see all of the design information associ-
ated with the selected beam. Click the X button in the top-right cor-
ner of the form to close the form.

Step 12 Run Detailing

In this Step, detailing will be run and displayed. Detailing may be
run only after analysis and design are complete.

A. Click the Detailing menu > Detailing Preferences command to
display the Detailing Preferences form shown in Figure 44. Use
this form to set the regional standards, to control how dimension-
ing is displayed, to manage reinforcing bar notation, and to select
the units for material quantity takeoffs.

Figure 44 Detailing Preferences form

B. Review the settings on this form (we will accept the default se-
lections), and then click the OK button to close the form.

C. Click the Detailing menu > Slab/Mat Reinforcing Preferences
to display the Slab/Mat Detailing Preferences form shown in
Figure 45.

46 Step 12 Run Detailing

<!-- p. 56 -->

Step 12 Run Detailing

Figure 45 Slab/Mat Detailing Preferences form

D. Click the General and Display tab. On this tab review or alter
the rebar curtailment, detailing and callout options, as well as set
how sections should be cut. We will accept the default settings.

E. Click the Rebar Selection tab and review or change the rebar se-
lection rules, preferred sizes, minimums and reinforcing around
openings. We will accept the default settings.

F. Click the OK button to accept the selections and close the form.

G. Click the Detailing menu > Drawing Sheet Setup command to
display the Drawing Sheet Setup form. The sheet size, scales, ti-
tle block and text sizes can be reviewed and changed using this
form. We will accept the default settings.

H. Click the OK button to close the form.

Step 12 Run Detailing 47

<!-- p. 57 -->

SAFE Tutorial – R/C

I. Review the line thicknesses and styles by clicking the Detailing
menu > Drawing Format Properties command.

J. Click the OK button to accept the selections and close the form.

K. Now that the detailing preferences and drawing setup options
have been reviewed, click the Run menu > Run Detailing com-
mand to generate the detailing drawings. A framing plan is dis-
played when detailing is complete.

L. Click the Detailing menu > Show Detailing command to access
the Display Detailing Item form shown in Figure 46.

Figure 46 Display Detailing Item form

M. Select the Drawing option.

N. Select Slab Rebar Plan – Bottom Bars from the Drawing drop-
down list.

48 Step 12 Run Detailing

<!-- p. 58 -->

Step 13 Create Report

O. Click the OK button to leave the Display Detailing Item form
and display the selected drawing shown in Figure 47.

P. Clicking on the Detailing tab in the Model Explorer and expand-
ing the Views and Drawing Sheets trees also provides access to
detailing drawings and views.

Q. Click the Display menu > Show Undeformed Shape command
to return to the model.

Figure 47 Slab Rebar Plan

Step 13 Create Report

In this Step, a report describing model input and output results will
be created.

A. Click the File menu > Report Setup command to display the
Report Setup Data form.

B. In the Report Output Type area, be sure that the RTF File option
is selected.

Step 13 Create Report 49

<!-- p. 59 -->

SAFE Tutorial – R/C

C. In the Report Items area, uncheck the Include Hyperlinked Con-
tents checkbox.

D. Click the OK button to leave the Report Setup Data form.

E. Click the File menu > Create Report command to display the
Microsoft Word Rich Text File Report form.

F. Type SLAB in the File name edit box and click the Save button.
A report, with a cover similar to that shown in Figure 48 should
be displayed in your word processor, and will be saved to your
hard disk.

Figure 48 Cover Page for Report

50 Step 13 Create Report

<!-- p. 60 -->

Step 13 Create Report

G. Scroll through the report to find tables that list geometry and
properties, analysis results and design information, such as that
shown if Figure 49.

H. Close your word processor and return to the SAFE program.

I. Click the File menu > Save command to save your model one
last time.

Figure 49 Typical Report information

Congratulations! You’ve successfully created, analyzed, designed,
detailed, and reviewed a SAFE reinforced concrete model.

Step 13 Create Report 51

<!-- p. 61 -->



<!-- p. 62 -->

Post-Tensioned Concrete

P/T Example

The intent of this tutorial is to give you hands-on experience via step-by-
step instructions on how to use SAFE to model, analyze, design and
detail post-tensioned concrete slabs. Fundamentals of the model creation
process are identified and various model construction techniques are
introduced. As you complete the tutorial, you will build the model shown
in Figure 50.

The Project

The tutorial project is an irregularly shaped post-tensioned concrete slab
as might be used for residential construction, with overall dimensions of
108 feet by 92 feet. Several openings exist in the interior for stair access.
The 8-inch thick slab is supported by a combination of 8-inch-thick walls
and 12-inch-square columns. The floor-to-floor height is 10 feet. The
model will be analyzed for a uniform dead load (partitions + mechanical)
of 35 pounds per square foot (psf) plus the self weight of the structure,
and a live load of 50 psf.

53

<!-- p. 63 -->

SAFE Tutorial – P/T

Concrete Materials:
A. Concrete strength, f’c = 5000 psi
B. Unit weight of concrete = 150 pcf
Prestressing Tendons:
C. Unbonded mono-strand
D. ½” diameter strand; 0.153 square-inch area
E. fse = 175.5 ksi (216 ksi @ stressing – 40.5 ksi losses)
Reinforced Concrete:
F. fy = 60ksi

Figure 50 The Project Model

Navigating Through SAFE

The SAFE program provides the user with two principal ways to navi-
gate through program commands: menu commands or toolbar buttons.
All commands are available through the main menu bar (e.g., Draw
menu > Draw Columns), and a majority of the menu commands are

also available as buttons on toolbars (e.g., Draw Columns, ). The

54 Navigating Through SAFE

<!-- p. 64 -->

Step 1 Begin a New Model

availability of a button on the toolbar is indicated in the menus by the ex-
istence of an icon to the left of the command, as shown in Figure 51.

Figure 51 Draw Menu

In this tutorial the reference to various commands will be given using the
narrative description, i.e., Draw menu > Draw Column in lieu of the as-
sociated button.

Step 1 Begin a New Model

In this Step, the dimensions and basic grid will be defined, which will
serve as a guide for developing the model. This model will be built with-
out using the automated template tools provided in SAFE to demonstrate
how to construct a model from scratch. However, as a general rule, we
highly recommend using templates to start models whenever possible

Step 1 Begin a New Model 55

<!-- p. 65 -->

SAFE Tutorial – P/T

because they provide a quick, easy way of generating a model. Consult
the SAFE Help topics for information about templates.

Set the Units

If the units shown in the drop-down list in the lower right-hand corner of
the SAFE window are not kip-in, scroll through the drop-down list to set
the units to kip-in.

Define the Grid

A. Click the File menu > New Model command to access the New
Model Initialization form shown in Figure 52. This form is used to
specify the starting point of the model creation: a Blank screen, a
screen with a Grid Only, or one of eight templates. Default units may
also be selected here, along with the design code and preferences.

Figure 52 New Model Initialization form

B. In the Design Data area, select ACI 318-08 from the Design Code
drop-down list.

C. In the Initial Model area, click the Grid Only button to display the
Coordinate System Definition form shown in Figure 53. This form is
used to specify the number of grids and spacing in each direction. It

56 Step 1 Begin a New Model

<!-- p. 66 -->

Step 1 Begin a New Model

is important that the grid be defined such as to accurately represent
the geometry of the structure, so it is advisable to spend time carefully planning the number and spacing of the grid lines.

Figure 53 Coordinate System Definition form

\1. Select the Cartesian option.

\2. As shown in Figure 53, set the Number of Grid Lines in the X
Direction to 8 and in the Y Direction to 6.

\3. In the Grid Spacing area, type 16ft in the X Direction edit box.

Note: When the units are explicitly stated, in this case feet (ft),
the program automatically converts the number input to be con-
sistent with the database units (recall that the units have been
set to kip-in). The value also may have been input as 16*12,
without the ft identifier.

\4. Type 16ft in the Y Direction edit box in the Grid Spacing area.

\5. Click the Grid Labels button to display the Grid Labeling Op-
tions form shown in Figure 54.

Step 1 Begin a New Model 57

<!-- p. 67 -->

SAFE Tutorial – P/T

Figure 54 Grid Labeling Options form

a. In the X Grid area, type 1 in the Beginning X ID edit box.
This will number the grids along the X-axis starting with 1.

b. In the Y Grid area, type A in the Beginning Y ID edit box.
This will label the grids along the Y-axis starting with A.

c. In the Y Grid area, select the Label Top to Bottom option –
grid A will start at the top of the model.

d. Click the OK button to accept the changes and leave the Grid
Labeling Options form.

\6. Click the Edit Grid button on the Coordinate System Definition
form to display the form shown in Figure 55. The Coordinate
System form is used to modify and edit the grid definitions, as
well as set the top of model datum. It also allows the user to set
the display options associated with the grids.

58 Step 1 Begin a New Model

<!-- p. 68 -->

Step 1 Begin a New Model

Figure 55 Coordinate System form

a. In the Display Grid Data as area, select the Spacing option.

b. In the X Grid Data table, change the X spacing as follows
(make sure to type ft in the edit box):

Grid ID Change X Spacing to

2 28ft
4 12ft
5 8ft
6 8ft
7 20ft

c. In the Y Grid Data table, change the Y spacing as follows
(make sure to type ft in the edit box):

Step 1 Begin a New Model 59

<!-- p. 69 -->

SAFE Tutorial – P/T

Grid ID Change Y Spacing to

F 20ft
E 12ft
C 28ft

d. Click the OK button to accept your changes.

When you leave the Coordinate System form, by default, the
grid displays on screen in the main SAFE window with two
windows tiled vertically: a Model Explorer window on the left
and a Plan View on the right. The number of view windows
can be changed using the Options menu > Windows com-
mand.

D. Click the View menu > Set Display Options command to display
the Set Display Options form. Uncheck the Horizon option in the
Items Present In View area and click the OK button to exit this form.
The Horizon option displays a plane that resembles an engineering
calculation grid to illustrate the datum plane location; we are turning
this option off to display our coordinate system grid better.

You should now have a display similar to that shown in Figure 56.

Display Title Bar (active)

Global Axes

Units

Figure 56 SAFE Main Window

60 Step 1 Begin a New Model

<!-- p. 70 -->

Step 2 Define Properties

Note that the Plan View window is active. When the window is ac-
tive, the display title bar is highlighted. Set a window active by click-
ing anywhere in the window.

Note that the Global Axes are displayed as well, and that the Z posi-
tive is in the “up” direction. When SAFE refers to the direction of
gravity, this is in the negative Z direction, or “down.”

Save the Model

Save your model often! Click the File menu > Save command. Specify
the directory in which you want to save the model. For this tutorial, spec-
ify the file name as PTSlab.

Typically you will save the model with the same name. However to re-
cord your work at various stages of development or as a backup, the File
menu > Save As command can be used to save the file using another
name.

Step 2 Define Properties

In this Step, material and section
properties for the slab, tendons,
columns, and walls are defined.

Although we are going to define
our materials and sections using
menu commands, previously
defined materials and properties
also may be reviewed and
modified using the Model Explorer
window (see Figure 57). To do
this, expand any of the property
items on the tree by clicking the +
node, and then double click on the
desired item to display the
associated form.

Figure 57 Model Explorer window

Step 2 Define Properties 61

<!-- p. 71 -->

SAFE Tutorial – P/T

Define Material Properties

A. Click the Define menu > Materials command to access the Materi-
als form shown in Figure 58.

Figure 58 Materials form

B. Click the Add New Material Quick button to display the Quick Ma-
terial Definition form shown in Figure 59. This form will be used to
define the 5000psi concrete material for the model.

\1. Select Concrete from the Material Type drop-down list.

\2. Select f’c 5000 psi from the Specification drop-down list.

\3. Click the OK button to exit the Quick Material Definition form.

Figure 59 Quick Material Definition form

C. In the Materials area of the Materials form, highlight A416Gr270.

62 Step 2 Define Properties

<!-- p. 72 -->

Step 2 Define Properties

D. Click the Modify/Show Material button to display the Material
Property Data form shown in Figure 60. This form lists the proper-
ties associated with Grade 270 prestressing strands; this is the tendon
material property that will be used in our model.

\1. Click the OK button to accept this material as defined.

Figure 60 Material Property Data form

E. Click the OK button on the Materials form to accept all of the de-
fined materials.

F. Click the File menu > Save command to save your model.

Define Slab Properties

A. Click the Define menu > Slab Properties command to access the
Slab Properties form shown in Figure 61.

Step 2 Define Properties 63

<!-- p. 73 -->

SAFE Tutorial – P/T

Figure 61 Slab Properties form

B. In the Slab Property area, highlight SLAB1.

C. Recall that for this tutorial project, the slab thickness is 8 inches. To
adjust the default dimensions of SLAB1, click the Modify/Show
Property button to access the Slab Property Data form shown in
Figure 62.

\1. In the General Data area, select 5000Psi from the Slab Material
drop-down list.

Note: Additional material properties may be defined by clicking
on the “…” button next to the load pattern name. A “…” button re-
turns you to the form used to define the item in the adjacent
drop-down list, which in this case is the Materials form.

\2. Select Slab from the Type drop-down list in the Analysis Prop-
erty Data area; this ensures that any area object with this prop-
erty assignment will be identified as a slab member.

\3. If not already displayed, type 8 in the Thickness edit box in the
Analysis Property Data area.

\4. Click the OK button to accept the changes and return to the Slab
Properties form.

64 Step 2 Define Properties

<!-- p. 74 -->

Step 2 Define Properties

Figure 62 Slab Property Data form

D. Click the OK button to end the slab property definition.

E. Click the File menu > Save command to save the model.

Define Tendon Properties

A. Click the Define menu > Tendon Properties command to access
the Tendon Properties form.

B. Click the Add New Property button to access the Tendon Property
Data form shown in Figure 63. Recall that the strands for the tendons
have an area of 0.153 square inches.

\1. Verify that TENDON1 is showing in the Property Name edit box
in the General Data area.

Step 2 Define Properties 65

<!-- p. 75 -->

SAFE Tutorial – P/T

Figure 63 Tendon Property Data form

\2. In the General Data area, make sure that A416Gr270 is displayed
in the Material Type drop-down list.

\3. If not already entered, type 0.153 in the Strand Area edit box in
the Property Data area.

\4. Click the OK button to end the tendon property definition.

C. Click the OK button to leave the Tendon Properties form.

D. Click the File menu > Save command to save your model.

Define Column Properties

A. Click the Define menu > Column Properties command to access
the Column Properties form.

B. In the Column Property area, highlight COL1.

C. Click the Modify/Show Property button to access the Column
Property Data form shown in Figure 64. Recall that the columns for
the project are 12-inch square.

\1. In the General Data area, select 5000Psi from the Material drop-
down list.

66 Step 2 Define Properties

<!-- p. 76 -->

Step 2 Define Properties

Figure 64 Column Property Data form

\2. In the Column Section Dimensions area, select Rectangular from
the Column Shape drop-down list.

\3. In the Column Section Dimensions area, type 12 into the Parallel
to 2-Axis edit box and type 12 into the Parallel to 3-Axis edit
box.

\4. Make sure that the Include Automatic Rigid Zone Area Over
Column option is checked. This option restricts deformation of
the slab at the column location, which prevents unrealistic peaks
in moment distribution from occurring.

\5. Click the OK button to leave the Column Property Data form.

D. Click the OK button to accept the Column Property definition.

Step 2 Define Properties 67

<!-- p. 77 -->

SAFE Tutorial – P/T

Define Wall Properties

A. Click the Define menu > Wall Properties command to access the
Wall Properties form.

B. In the Wall Property area, highlight Wall1.

C. Click the Modify/Show Property button to access the Wall Property
Data form shown in Figure 65. Recall that the walls for the project
are 8-inch thick.

Figure 65 Wall Property Data form

\1. In the General Data area, select 5000Psi from the Wall Material
drop-down list.

\2. In the Wall Dimensions area, type 8 into the Thickness edit box.

\3. Check the Include Automatic Rigid Zone Area Over Wall check-
box. This option restricts deformation of the slab at the wall
location, which prevents unrealistic peaks in moment distribution
from occurring.

\4. Click the OK button to leave the Wall Property Data form.

68 Step 2 Define Properties

<!-- p. 78 -->

Step 3 Define Static Load Patterns

D. Click the OK button to accept the Wall Property definition.

This completes the material and section property definition phase of the
model creation. The slab and tendon properties will be assigned in the
model datum plane, while the columns and walls will be assigned as
supports. Supports also can be assigned as point restraints, point springs
or line springs. Support stiffnesses are calculated by SAFE based on the
cross-sectional properties, material properties and lengths specified when
the columns and walls are drawn.

Step 3 Define Static Load Patterns

In this Step, the dead, live, and post-tensioning static load patterns are
defined. That is, we will name the various types of loads (dead, live,
prestress-final, and so on), and specify the self-weight multipliers. The
loads will be assigned to objects, and the values for the loads specified
(uniform dead load of 35 psf and live load of 50 psf), in Step 8.

A. Click the Define menu > Load Patterns command to access the
Static Load Case Names form shown in Figure 66.

Figure 66 Load Patterns form

B. Note that load patterns DEAD and LIVE are defined by default.

C. Recall that the project will be analyzed for the dead load plus the self
weight of the structure. Thus, the Self Weight Multiplier should be
set equal to 1 (this will include 1.0 times the self weight of all mem-

Step 3 Define Static Load Patterns 69

<!-- p. 79 -->

SAFE Tutorial – P/T

bers) for the DEAD load. Only the DEAD load pattern should have a
non-zero Self Weight Multiplier.

D. Click the Add Load Pattern button.

E. Highlight LPAT1 in the Load column and type PT-FINAL.

F. Select PRESTRESS-FINAL from the drop-down list under Type for
the PT-FINAL load pattern.

G. Click the Add Load Pattern button.

H. Highlight LPAT1 in the Load column and type PT-TRANSFER.

I. Select PRESTRESS-TRANSFER from the drop-down list under Type
for the PT-TRANSFER load pattern. The Load Patterns form should
appear as shown in Figure 67.

Figure 67 Load Patterns form after all load patterns are entered

J. Click the OK button to accept all of the defined static load patterns.

K. Click the File menu > Save command.

Step 4 Define Load Cases

In this Step, the Load Cases are defined. This is where the type of analy-
sis is specified.

70 Step 4 Define Load Cases

<!-- p. 80 -->

Step 4 Define Load Cases

A. Click the Define menu > Load Cases command to access the Load
Cases form shown in Figure 68.

Figure 68 Load Cases form

B. With the DEAD Load Case Name highlighted, click the Mod-
ify/Show Case button to display the Load Case Data form shown in
Figure 69. This data form changes based on the type of load case
specified.

\1. In the Load Case Type area, select Static from the drop-down
list. Modal and Hyperstatic are also available as load case types.

\2. In the Analysis Type area, select the Linear option. When work-
ing with a Static Load Case Type, the program offers the option
to do Linear, Nonlinear (Allow Uplift), Nonlinear (Cracked), or
Nonlinear (Long Term Cracked) analysis. For our tutorial exam-
ple a Static, Linear analysis will be performed for DEAD, LIVE,
PT-FINAL and PT-TRANSFER.

\3. In the Loads Applied area, verify that the load pattern is DEAD
with a scale factor of 1.

\4. Click the OK button to close the Load Case Data form.

Step 4 Define Load Cases 71

<!-- p. 81 -->

SAFE Tutorial – P/T

Figure 69 Load Case Data form

C. Review the other load cases, if so desired, by selecting a case and us-
ing the Modify/Show Case button as described for the DEAD load
case.

D. Click the OK button to close the Load Cases form.

E. Click the File menu > Save command.

Step 5 Draw Objects

In this Step, slabs, columns, walls, openings, and design strips will be
drawn.

Draw Slabs

Ensure that the Plan View is active (click anywhere in the display win-
dow; a window is active when the Display Title Bar, just below the hori-

72 Step 5 Draw Objects

<!-- p. 82 -->

Step 5 Draw Objects

zontal toolbar, is highlighted). Now draw area objects to model the slab
using the following Action Items.

A. Click the Draw menu > Snap Options command to display the
Snap Options form shown in Figure 70.

Figure 70 Snap Options form

B. In the Snap to area, make sure that the Points and Grid Intersections
options are checked. These snap options will assist in accurately po-
sitioning objects when drawing.

C. In the Snap Increments area, make sure that the (Imperial in Inches)
Snap at length increments of option is checked. When drawing slab
edges, beams and walls, a dimension line will appear and the object
will snap to the values specified in this edit box.

D. Click the OK button to close the Snap Options form.

E. Click the Draw menu > Draw Slabs/Areas command to access the
Draw Slabs/Areas form shown in Figure 71. If the Draw Slabs/Areas
form covers part of the model, click on the blue title bar, hold down
the mouse button, and drag it out of the way.

Step 5 Draw Objects 73

<!-- p. 83 -->

SAFE Tutorial – P/T

Figure 71 Draw Slabs/Areas form

F. Make sure that the Type of Object is set to Slab. If it is not, click
once in the drop-down list opposite the Type of Object item and se-
lect Slab.

G. Click in the Property edit box and select SLAB1 from the drop-down
list. This is the slab property defined in Step 2.

H. Click in the Edge Drawing Type drop-down list and select Straight
Line. Although not used in this project, slab edges also may be
drawn with arcs and curves.

I. To draw the first corner of the slab, click once in the Plan View at
the intersection of grid lines 1 and A (the cursor should display Grid
Point 1 A at the correct location). Then moving clockwise around the
grid (note how the slab edge is dimensioned as you draw), click once
at these grid intersections in this order to draw the outline of the slab:
8A, 8D, 4D, 4F, and 1F. If you mistakenly click at the wrong point,
use the •Backspace key on the keyboard to “undo” the point and try
again. After clicking at grid 1F, press the Enter key on the keyboard.
The shaded slab object should now display.

If you made a mistake and wish to try re-drawing the entire object,
click the Select menu > Select > Pointer/Window command to
leave the Draw mode and go to the Select mode. Then click the Edit
menu > Undo Area Add command, and repeat Items E through I.

J. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Slabs/Areas
command.

K. Select the slab by clicking on it anywhere. The status bar in the
lower left-hand corner should show “1 Areas, 6 Edges selected.” If

74 Step 5 Draw Objects

<!-- p. 84 -->

Step 5 Draw Objects

you make a mistake in selecting, press the Select menu > Clear Se-
lection command and try again.

L. Click the Edit menu > Edit Areas > Expand/Shrink Areas com-
mand to display the Expand/Shrink Areas form shown in Figure 72.

Figure 72 Expand/Shrink Areas form

M. Type 6 into the Offset Value edit box. We will use this form to ex-
pand (a positive value expands) the slab by 6-inches at each corner to
create the perimeter overhang that is needed to accommodate the
width of the columns (1/2 of 12 inches).

N. Click the OK button to finish the slab.

O. Click the File menu > Save command to save your model.

Draw Columns

With the active window set as described in the preceding Draw Slabs
section (i.e., Plan View window active and the snap to points and grid intersections enabled), use the following Action Items to draw columns.

A. Click the Draw menu > Draw Columns command to access the
Draw Columns form shown in Figure 73.

B. Click in the Property Below edit box and select COL1 from the drop-
down list. This is the property for the 12-inch by 12-inch column de-
fined in Step 2.

C. Click in the Property Above edit box and select COL1 from the drop-
down list.

Step 5 Draw Objects 75

<!-- p. 85 -->

SAFE Tutorial – P/T

Figure 73 Draw Columns form

D. Click in the Height Below edit box and type 10ft. Note that the units
are inches, so this value will be converted to 120.

E. Click in the Height Above edit box and type 10ft.

F. Click in the Cardinal Point edit box and select 10 (Centroid) from
the drop-down list.

G. Left click once at each of the following grid intersections to draw the
columns: 1A, 1B, 1F, 2A, 2B, 2F, 3F, 4F, 5A, 5B, 5D, 8A, 8B, 8C,
and 8D.

If you have made a mistake while drawing the columns, click the Se-
lect menu > Select > Pointer/Window command to leave the Draw
mode and go to the Select mode. Then click the Edit menu > Undo
Column Object Add command as many times as needed to remove
the incorrectly drawn columns, and repeat Items A through G.

H. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Columns com-
mand.

I. Click the File menu > Save command to save your model.

J. Click the View menu > Set Default 3D View command to display
the model in 3D. Note how the columns extend above and below the
slab.

76 Step 5 Draw Objects

<!-- p. 86 -->

Step 5 Draw Objects

K. Click the View menu > Set Plan View command to return to the
Plan View before continuing with the project.

Draw Walls

Similar to the preceding two sections, ensure that the Plan View is active
and that the snap to points, grid intersections and the snap increments options are enabled. Now use the following Action Items to draw walls.

A. Click the Draw menu > Snap Options command to access the Snap
Options form.

B. Check the Line Ends and Midpoints checkbox in the Snap to area.

C. Click the OK button to close the Snap Options form.

D. Click the Draw menu > Draw Walls command to access the Draw
Walls form shown in Figure 74.

Figure 74 Draw Walls form

E. Click in the drop-down list opposite the Wall Property Below item
and select WALL1. This is the wall property for the 8-inch-thick wall
defined in Step 2.

F. Click in the Wall Property Above drop-down list and select WALL1.

G. Click in the Wall Height Below edit box and type 10ft. Note that the
units are inches, so the value will be converted to 120.

Step 5 Draw Objects 77

<!-- p. 87 -->

SAFE Tutorial – P/T

H. Click in the Wall Height Above edit box and type 10ft.

I. Click in the drop-down list opposite the Line Drawing Type item and
select Straight Line. Although not used in this project, walls may
also be drawn with arcs and curves.

J. Left click at grid intersection 1C to begin drawing the first wall.
Draw the wall along grid line C to grid intersection 2C and then click
again. The snap increments dimension line should show 16 ft. Hit the
Enter key on the keyboard to complete the wall. This places a wall
16 feet long along grid line C.

If you have made a mistake while drawing this object, click the Se-
lect menu > Select > Pointer/Window command to leave the Draw
mode and go to the Select mode. Then click the Edit menu > Undo
Area Object Add command, and repeat Items A through G.

K. For the next wall, also located along grid line C, left click at grid in-
tersection 3C to begin drawing the wall and at intersection 4C (the
snap increment dimension line should show 16 ft) to designate the
end of the wall. Hit the Enter key on the keyboard to complete the
wall.

L. Click at grid intersection 1E and then at intersection 2E to draw the
next wall along grid E. Hit the Enter key on the keyboard to com-
plete the wall.

M. Click at grid intersection 3E and then at intersection 4E to draw the
last x-direction wall along grid E. Hit the Enter key on the keyboard
to complete the wall.

N. Click at grid intersection 3A and then at intersection 3B to draw the
first y-direction wall along grid 3. Hit the Enter key on the keyboard
to complete the wall.

O. Snap the mouse to the Mid Point of the wall (a triangular cursor
should display) along grid line C between grids 3 and 4, and left
click. Move the mouse to the Mid Point of the wall along grid line E
between grids 3 and 4 and click again – the snap increment dimen-

78 Step 5 Draw Objects

<!-- p. 88 -->

Step 5 Draw Objects

sion line should show 28 ft. Hit the Enter key on the keyboard to
complete the wall.

P. Click at grid intersection 6C and then at intersection 6D to draw the
next y-direction wall along grid 6. Hit the Enter key on the keyboard
to complete the wall.

Q. Click at grid intersection 7A and then at intersection 7B to draw the
last y-direction wall. Hit the Enter key on the keyboard to complete
the wall.

R. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Walls command.
Your model should look similar to Figure 75.

Figure 75 The model after drawing columns and walls

Draw Openings (Area Objects)

Similar to the previous sections, ensure that the Plan View is active.
Draw an area object to model the opening as follows:

Step 5 Draw Objects 79

<!-- p. 89 -->

SAFE Tutorial – P/T

A. Click the Draw menu > Draw Rectangular Slabs/Areas command
to display the Draw Rectangular Slabs/Areas form shown in Figure
\76.

Figure 76 Draw Rectangular Slabs/Areas form

B. Click once in the drop-down list opposite the Type of Object item
and select Opening.

C. Left click at the intersection of grid lines 3 and C, and while holding
the left mouse button down, move diagonally down and to the right
to the point where grid line D intersects the adjacent y-direction wall,
and release the button. An area object (8 ft x 28 ft) with different
shading should appear, indicating that an opening for the stairs has
been drawn. An opening takes priority over an object with assigned
slab properties when the program determines the stiffness formula-
tion.

D. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Rectangular
Slabs/Areas command.

S. Click the Draw menu > Snap Options command to access the Snap
Options form.

T. Check the Intersections checkbox in the Snap to area.

E. Click the OK button to close the Snap Options form.

F. Click the View menu > Rubber Band Zoom command. Left click
just above and to the left of grid intersection 6A, and while holding
the mouse button down, drag a window down and to the left of grid
intersection 7B.

80 Step 5 Draw Objects

<!-- p. 90 -->

Step 5 Draw Objects

G. Click the Draw menu > Draw Rectangular Slabs/Areas command
to display the Draw Rectangular Slabs/Areas form.

H. To draw the second opening, snap the mouse to the intersection of
grid line 6 and the edge of the slab (the cursor should say Intersec-
tion), and while holding the left mouse button down, move diago-
nally down and to the right to the Mid Point of the wall that lies
along grid line 7, and release the button.

I. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Rectangular
Slabs/Areas command.

J. Click the View menu > Restore Full View command.

K. Click the File menu > Save command to save your model.

Draw Design Strips

Similar to the previous sections, ensure that the Plan View is active. Design strips determine how tendons and reinforcing will be calculated and
positioned in the slab. Typically design strips are positioned in two principal directions: Layer A and Layer B. Use the following Action Items
to draw design strips:

A. Click the Draw menu > Draw Design Strips command to display
the Draw Design Strips form shown in Figure 77.

Figure 77 Draw Design Strips form

Step 5 Draw Objects 81

<!-- p. 91 -->

SAFE Tutorial – P/T

B. Select A from the Strip Layer drop-down list. Design strips subse-
quently drawn will be assigned to Layer A.

C. The values showing in the width edit boxes may be ignored, as we
will edit the design strips in a later step to automatically adjust their
width based on the location of adjacent strips.

D. Left click at grid intersection 1A to begin drawing the first design
strip. Click again at grid intersection 6A and hit the Enter key on the
keyboard to complete the design strip.

E. Repeat Item D for the following pairs of grid intersections: 7A to
8A; 1B to 8B; 1C to 8C; 1E to 4E; and 1F to 4F.

F. Snap the mouse to the Point at the approximate intersection of grids
D and 3.5 (between 3 and 4) along the wall and left click to begin the
design strip, and then click again at grid intersection 8D. Hit the En-
ter key to complete the design strip. This completes the Layer A de-
sign strips.

Note that although the majority of the design strips were drawn using
grid intersections rather than the edge of the slab, the program as-
sumes that they should go to the slab edge and will automatically ex-
tend the design strips when the tolerance is small.

G. On the Draw Design Strips form, select B from the Strip Layer drop-
down list. Design strips subsequently drawn will be assigned to
Layer B.

H. Left click at grid intersection 1A to begin drawing the first Layer B
design strip. Click again at grid intersection 1F and hit the Enter key
on the keyboard to complete the design strip.

I. Repeat Item H for the following pairs of grid intersections: 2A to 2F;
3A to 3F; 4A to 4F; 5A to 5D; 6A to 6D; 7A to 7D; and 8A to 8D.

J. Click on the Select menu > Select > Pointer/Window command or
press the Esc key on the keyboard to exit the Draw Design Strips
command and return to the select mode.

82 Step 5 Draw Objects

<!-- p. 92 -->

Step 5 Draw Objects

K. Click the Select menu > Select > Properties > Design Strip Layers
command to display the Select Design Strip Layers form shown in
Figure 78.

Figure 78 Select Design Strip Layers form

L. Highlight Layer A and Layer B in the Select area by holding down
the Shift key on the keyboard while clicking on the items.

M. Click the OK button to leave the form. The status bar in the lower
left-hand corner should now show “15 Design Strips selected.”

N. Click the Edit menu > Add/Edit Design Strips > Edit Strip
Widths command to display the Edit Strip Widths form.

O. In the Strip Width Options area, select the Auto Widen Entire Strip
option. Selecting this option allows the program to automatically set
the width of each design each strip based on the location of adjacent
strips.

P. Click the OK button to accept the selections and leave the Edit Strip
Widths form.

Q. Click the File menu > Save command to save your model.

Step 5 Draw Objects 83

<!-- p. 93 -->

SAFE Tutorial – P/T

Step 6 Add Tendons

In this step, tendons will be added to the model. Although tendons may
be drawn in the model using the Draw menu > Draw Tendons com-
mand, it is often more efficient to add them to the design strips, which is
how tendons will be added to this project. The number of tendons (and
strands) will be determined by the program based on the following de-
faults: tendon jacking stress = 216 ksi; stressing losses = 27 ksi; long-
term losses = 13.5 ksi; tendons are jacked from the J-end (ending point)
of the tendon.

Similar to the previous sections, ensure that the Plan View is active. Add
tendons to the design strips as follows:

A. Click the Select menu > Select > Properties > Design Strip Layers
command to display the Select Design Strip Layers form.

B. Highlight Layer A in the Select area.

C. Click the OK button to accept the selection. The status bar in the
lower left-hand corner should now show “7 Design Strips selected.”

D. Click the Edit menu > Add/Edit Tendons > Add Tendons in
Strips command to display the Quick Tendon Layout form shown in
Figure 79.

Figure 79 Quick Tendon Layout form

84 Step 6 Add Tendons

<!-- p. 94 -->

Step 6 Add Tendons

E. Select Banded from the Layout Type drop-down list. Tendons will
be banded in the Layer A direction, and distributed in the Layer B di-
rection.

F. Type 0 into the Band Width edit box. By using a value of 0, the pro-
gram will calculate how many total strands are needed.

G. Select TENDON1 from the Tendon Property drop-down list. This is
the tendon property defined in Step 2.

H. Select Reverse Parabola from the Vertical Profile drop-down list.

I. Verify that the Self Load Balancing Ratios are set to 0.8 for Maxi-
mum and 0.6 for Minimum. This controls how much of the struc-
ture’s self weight the program will try to balance with the post-
tensioning.

J. Click the OK button to leave the Quick Tendon Layout form. A sin-
gle tendon in each Layer A design strip should now appear.

K. Click the Select menu > Select > Properties > Design Strip Layers
command to display the Select Design Strip Layers form.

L. Highlight Layer B in the Select area.

M. Click the OK button to accept the selection. The status bar in the
lower left-hand corner should now show “8 Design Strips selected.”

N. Click the Edit menu > Add/Edit Tendons > Add Tendons in
Strips command to display the Quick Tendon Layout form.

O. Select Distributed from the Layout Type drop-down list.

P. Type 38 into the Tendon Spacing edit box. The program will deter-
mine how many strands are needed in each tendon for this spacing.

Q. Select Parabola from the Vertical Profile drop-down list.

R. Verify that the Self Load Balancing Ratios are set to 0.8 for Maxi-
mum and 0.6 for Minimum.

Step 6 Add Tendons 85

<!-- p. 95 -->

SAFE Tutorial – P/T

S. Click the OK button to leave the Quick Tendon Layout form. Ten-
dons in the Layer B design strips should now display.

T. Hold down the Shift key on your keyboard and right click once on
any of the tendons just drawn. A selection list similar to the one
shown in Figure 80 displays because multiple objects exist at that lo-
cation. In this case, one tendon and one area object exist at the same
location. Note that the selection list will display only when the Shift
key is used with the right click.

Figure 80 Selection List form

U. Highlight the tendon object and click the OK button. Because a right
click action initiated the selection process, a Tendon Object Informa-
tion form similar to the one shown in Figure 81 will display.

\1. Click on the Loads tab. Note that the Tendon Jacking Stress is
216 ksi, and that the losses are 27 ksi for Stressing and 13.5 ksi
for Long Term.

\2. Click on the Geometry tab. This tab describes the geometry of
the tendon in both plan and elevation.

86 Step 6 Add Tendons

<!-- p. 96 -->

Step 6 Add Tendons

Figure 81 Tendon Object Information form

\3. Left click in any of the edit boxes associated with a vertical span,
and the Tendon Vertical Profile form appears, similar to that
shown in Figure 82. This form displays the vertical profile of the
tendon in elevation, and allows the tendon profile to be altered
either graphically, by grabbing a control point on the tendon and
moving it to a new position, or numerically, by selecting the de-
sired span and entering new values into the table. Click the OK
button, to accept the default profiles.

Step 6 Add Tendons 87

<!-- p. 97 -->

SAFE Tutorial – P/T

Figure 82 Tendon Vertical Profile form

\4. Click the Assignments tab. This tab lists the number of strands
associated with the selected tendon.

\5. Click the OK button to exit the Tendon Object Information
form.

V. Click the File menu > Save command to save your model.

Step 7 Set Display Options

In this Step, the set display options will be used to alter the objects dis-
played.

A. Click the View menu > Set Display Options command. When the
Set Display Options form displays, uncheck the Tendon, Design
Strip Layer A and Design Strip Layer B check boxes in the Items
Present in View area as shown in Figure 83. This action will turn off
the display of the tendons and design strips.

88 Step 7 Set Display Options

<!-- p. 98 -->

Step 7 Set Display Options

Figure 83 Set Display Options form

B. Click the OK button to accept the changes, and the model now ap-
pears as shown in Figure 84.

Figure 84 Model after all objects have been drawn

Step 7 Set Display Options 89

<!-- p. 99 -->

SAFE Tutorial – P/T

Step 8 Assign Loads

In this Step, the dead and live loads will be assigned to the slab. Ensure
that the Plan View is still active, and that the program is in the select
mode (Draw menu > Select > Pointer/Window command).

A. Select the slab by clicking on it anywhere that is not a wall, column
or opening. The status bar in the lower left-hand corner should show
“1 Areas, 6 Edges selected.” If you make a mistake in selecting, click
the Select menu > Clear Selection command, and try again.

B. Click the Assign menu > Load Data > Surface Loads command to
access the Surface Loads form shown in Figure 85.

C. If it is not already displayed, select DEAD from the Load Pattern
Name drop-down list.

D. Select lb-ft from the Units area drop-down list.

E. In the Uniform Loads (Gravity Direction), type 35 in the Uniform
Load edit box.

Figure 85 Surface Loads form

90 Step 8 Assign Loads

<!-- p. 100 -->

Step 8 Assign Loads

Note: Additional load cases may be defined by clicking on the “…”
button next to the load pattern name. A “…” button returns you to the
form used to define the item in the adjacent drop-down list, which in
this case is the Load Patterns form.

F. Click the OK button to accept the dead load assignment. SAFE will
display the loads on the model. Use the Assign menu > Clear Dis-
play of Assigns command to remove the assignments from the dis-
play, if desired.

G. Click anywhere on the main slab to reselect the slab, or click the Se-
lect menu > Get Previous Selection command to select the slab.

H. Click the Assign menu > Load Data > Surface Loads command to
again access the Surface Loads form.

I. Select LIVE from the Load Pattern Name drop-down list.

J. Type 50psf in the Uniform Load edit box in the Uniform Loads area.

K. Click the OK button to accept the live load assignment. Again, use
the Assign menu > Clear Display of Assigns command to remove
the assignments from the display.

To review the assignments to the slab, right click on the slab anywhere
that is not a wall, column or opening to access the Slab-Type Area Object Information form shown in Figure 86.

Select the Loads tab and then lb-ft from the Units drop-down list and
note that the DEAD Load Pattern has a Force per Unit Area of 35, and
that the LIVE Load Pattern has a Force per Unit Area of 50. Click the
OK button to close the Slab-Type Area Object Information form. Click
the File menu > Save command to save your model.

Step 8 Assign Loads 91

<!-- p. 101 -->

SAFE Tutorial – P/T

Figure 86 Slab-Type Area Object Information form

Step 9 Run the Analysis and Design

In this Step, the analysis and design will be run.

A. Click the Run menu > Run Analysis & Design command to start
the analysis. The program will create the analysis model from your
object-based SAFE model, and will display information in the status
bar in the lower left-hand corner as the analysis and design proceeds.
Additional information about the run may be accessed at a later time
using the File menu > Show Input/Output Text Files command
and selecting the filename with a .LOG extension.

92 Step 9 Run the Analysis and Design

<!-- p. 102 -->

Step 10 Graphically Review the Analysis Results

B. When the analysis and design are finished, the program automati-
cally displays a deformed shape view of the model, and the model is
locked. The model is locked when the Options menu >
Lock/Unlock Model icon appears depressed. Locking the model
prevents any changes to the model that would invalidate the analysis
results.

Step 10 Graphically Review the Analysis Results

In this Step, the analysis will be reviewed using graphical displays of the
results.

A. Click the View menu > Set Default 3D View command to display
the deformed shape for the DEAD load case in 3D.

B. Click the Start Animation button in the lower right-hand corner of
the display to animate the deformed shape. Speed of the animation
may be adjusted by using the slider control adjacent to the button.
Click the Stop Animation button to end the animation.

C. Click the Display menu > Show Deformed Shape command to ac-
cess the Deformed Shape form shown in Figure 87.

Figure 87 Deformed Shape form

Step 10 Graphically Review the Analysis Results 93

<!-- p. 103 -->

SAFE Tutorial – P/T

D. In the Load Case/Load Combination area, select the Load Case op-
tion.

E. Select PT-FINAL from the Load Case drop-down list. Note that in
addition to the DEAD, LIVE, PT-FINAL and PT-TRANSFER load
cases that were previously defined, the program has automatically
created a PT-FINAL-HP load case for hyperstatic analysis.

F. Select the Automatic option in the Scaling area.

G. Check the Draw Contours checkbox in the Contour Range area.

H. Click the OK button to generate a 3-D deformed shape with contours
for the PT-FINAL load case.

I. Click the Display menu > Show Slab Forces/Stresses command to
bring up the Slab Forces/Stresses form shown in Figure 88.

J. Select PT-TRANSFER from the Load Case drop-down list.

K. Select the Stresses Top Face option in the Component Type area.

L. Select the S11 option in the Component area.

Figure 88 Slab Forces/Stresses form

94 Step 10 Graphically Review the Analysis Results

<!-- p. 104 -->

Step 11 Design Display

M. Select the Display Contours on Deformed Shape option in the
Display Options area.

N. Click the OK button to generate the moment diagram shown in
Figure 89.

Figure 89 S11 Stress Diagram

Note that as you move the cursor over the diagram, the values are
displayed at the cursor and in the lower left-hand corner of the win-
dow.

O. Click the Display menu > Show Undeformed Shape command to
clear the display of the stress diagram.

P. Click the View menu > Set Plan View command to return to the
Plan View.

Step 11 Design Display

In this Step, design results for the slab will be displayed. Note that the
design was run along with the analysis in Step 9. Design results are for
the ACI 318-08 code, which was selected in Step 1. Design preferences
may be reviewed or changed by going to the Design menu > Design
Preferences command (some design preferences are also set on the

Step 11 Design Display 95

<!-- p. 105 -->

SAFE Tutorial – P/T

property data forms); be sure to re-run the analysis and design (Step 9) if
changes to the preferences are made.

A. Click the Display menu > Show Slab Design command to access
the Slab Design form shown in Figure 90.

Figure 90 Slab Design form

B. In the Choose Display Type area, select Strip Based from the Design
Basis drop-down list and Stress Check - Transfer from the Display
Type drop-down list.

C. In the Choose Strip Direction area, check the Layer A checkbox and
uncheck the Layer B checkbox. This will display the stress check re-
sults in the Layer A (X) direction only.

D. In the Stress Type Shown area, select the Tensile option.

E. Click the OK button to leave the Slab Design form and display the
stress check results. The tensile stresses at transfer are displayed; if
failed is displayed, the stress at that location exceeds the allowable
P/T Stress Check ratio specified on the Design Preferences form ac-
cessed using the Design menu > Design Preferences command.

96 Step 11 Design Display

<!-- p. 106 -->

Step 11 Design Display

Positioning the cursor at any location on a Layer A design strip
causes the top and bottom stress values to be displayed in the lower
left corner of the window and at the cursor.

G. To view the stress check results in the Layer B direction, click the
Display menu > Show Slab Design command to display the Slab
Design form.

H. In the Choose Display Type area, select Stress Check – Long Term
from the Display Type drop-down list.

I. In the Choose Strip Direction area, uncheck the Layer A checkbox
and check the Layer B checkbox.

J. In the Stress Type Shown area, select the Compressive option.

K. Click the OK button to leave the Slab Design form and display the
long-term compressive stress check results for the Layer B direction.
The view will be updated to that shown in Figure 91. Again, posi-
tioning the cursor anywhere on the strips will result in the display of
the stress check values in the lower left-hand corner of the SAFE
window.

Figure 91 Layer B Long-Term Compressive Stresses

Step 11 Design Display 97

<!-- p. 107 -->

SAFE Tutorial – P/T

Step 12 Run Detailing

In this Step, detailing will be run and displayed. Detailing may be
run only after analysis and design are complete.

A. Click the Detailing menu > Detailing Preferences command to
display the Detailing Preferences form shown in Figure 92.

Figure 92 Detailing Preferences form

Use this form to set the regional standards, to control how di-
mensioning is displayed, to manage reinforcing bar notation, and
to select the units for material quantity takeoffs.

B. Review the settings on this form (we will accept the default se-
lections), and then click the OK button to close the form.

C. Click the Detailing menu > Slab/Mat Reinforcing Preferences
to display the Slab/Mat Detailing Preferences form shown in
Figure 93.

98 Step 12 Run Detailing

<!-- p. 108 -->

Step 12 Run Detailing

Figure 93 Slab/Mat Detailing Preferences form

D. Click the General and Display tab. On this tab review or alter
the rebar curtailment, detailing and callout options, as well as set
how sections should be cut. We will accept the default settings.

E. Click the Rebar Selection tab and review or change the rebar se-
lection rules, preferred sizes, minimums and reinforcing around
openings. We will accept the default settings.

F. Click the OK button to accept the selections and close the form.

G. Click the Detailing menu > Drawing Sheet Setup command to
display the Drawing Sheet Setup form. The sheet size, scales, ti-
tle block and text sizes can be reviewed and changed using this
form. We will accept the default settings.

H. Click the OK button to close the form.

Step 12 Run Detailing 99

<!-- p. 109 -->

SAFE Tutorial – P/T

I. Review the line thicknesses and styles by clicking the Detailing
menu > Drawing Format Properties command.

J. Click the OK button to accept the selections and close the form.

K. Now that the detailing preferences and drawing setup options
have been reviewed, click the Run menu > Run Detailing com-
mand to generate the detailing drawings. A framing plan is dis-
played when detailing is complete.

L. Click the Detailing menu > Show Detailing command to access
the Display Detailing Item form shown in Figure 94.

Figure 94 Display Detailing Item form

M. Select the Drawing option.

N. Select Tendon Layout Plan from the Drawing drop-down list.

O. Click the OK button to leave the Display Detailing Item form
and display the selected drawing shown in Figure 95.

100 Step 12 Run Detailing

<!-- p. 110 -->

Step 13 Create Report

Figure 95 Tendon Layout Plan

P. Clicking on the Detailing tab in the Model Explorer and expand-
ing the Views and Drawing Sheets trees also provides access to
detailing drawings and views.

Q. Click the Display menu > Show Undeformed Shape command
to return to the model.

Step 13 Create Report

In this Step, a report describing model input and output results will
be created.

A. Click the File menu > Report Setup command to display the
Report Setup Data form.

B. In the Report Output Type area, make sure that the RTF File op-
tion is selected.

C. In the Report Items area, uncheck the Include Hyperlinked Con-
tents checkbox.

Step 13 Create Report 101

<!-- p. 111 -->

SAFE Tutorial – P/T

D. Click the OK button to leave the Report Setup Data form.

E. Click the File menu > Create Report command to display the
Microsoft Word Rich Text File Report form.

F. Type PTSLAB in the File name edit box and click the Save but-
ton. A report, with a cover similar to that shown in Figure 96
should be displayed in your word processor, and will be saved to
your hard disk.

G. Scroll through the report to find tables that list geometry and
properties, analysis results and design information, such as that
shown if Figure 97.

Figure 96 Cover Page for Report

102 Step 13 Create Report

<!-- p. 112 -->

Step 13 Create Report

H. Close your word processor and return to the SAFE program.

I. Click the File menu > Save command to save your model one
last time.

Figure 97 Typical Report information

Congratulations! You’ve successfully created, analyzed, designed,
detailed, and reviewed a SAFE post-tensioned concrete model.

Step 13 Create Report 103
