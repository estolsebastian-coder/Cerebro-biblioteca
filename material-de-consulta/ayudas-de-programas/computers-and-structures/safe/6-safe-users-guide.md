---
type: libro
title: "6.- SAFE_Users_Guide"
author: "Nancy"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 62
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/SAFE/6.- SAFE_Users_Guide.pdf"
convertido: 2026-10-16
---

# 6.- SAFE_Users_Guide

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\SAFE\6.- SAFE_Users_Guide.pdf` (62 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

SAFE

Integrated Analysis and Design of Slab Systems

Introductory User’s Guide

Computers and Structures, Inc. Version 8.0.0
Berkeley, California, USA August 2004

<!-- p. 2 -->

Copyright

The computer program SAFE and all associated documentation are proprietary and
copyrighted products. Worldwide rights of ownership rest with Computers and
Structures, Inc. Unlicensed use of the program or reproduction of the documentation in
any form, without prior written authorization from Computers and Structures, Inc., is
explicitly prohibited.

Further information and copies of this documentation may be obtained from:

Computers and Structures, Inc.
1995 University Avenue
Berkeley, California 94704 USA

Phone: (510) 845-2177
FAX: (510) 845-4096
e-mail: info@csiberkeley.com (for general questions)
e-mail: support@csiberkeley.com (for technical support questions)
web: www.csiberkeley.com

 Copyright Computers and Structures, Inc., 1978-2004.
The CSI Logo is a registered trademark of Computers and Structures, Inc.
SAFE and CSiDETAILER are trademarks of Computers and Structures, Inc.
Windows is a registered trademark of Microsoft Corporation.
Adobe and Acrobat are registered trademarks of Adobe Systems Incorporated.
AutoCAD is a registered trademark of Autodesk, Inc.

<!-- p. 3 -->

DISCLAIMER

CONSIDERABLE TIME, EFFORT AND EXPENSE HAVE GONE INTO THE
DEVELOPMENT AND DOCUMENTATION OF SAFE. THE PROGRAM HAS BEEN
THOROUGHLY TESTED AND USED. IN USING THE PROGRAM, HOWEVER,
THE USER ACCEPTS AND UNDERSTANDS THAT NO WARRANTY IS
EXPRESSED OR IMPLIED BY THE DEVELOPERS OR THE DISTRIBUTORS ON
THE ACCURACY OR THE RELIABILITY OF THE PROGRAM.

THE USER MUST EXPLICITLY UNDERSTAND THE ASSUMPTIONS OF THE
PROGRAM AND MUST INDEPENDENTLY VERIFY THE RESULTS.

<!-- p. 4 -->

SAFE™SAFE™ Contents

Introductory User’s Guide

1 Program Description

This is SAFE 1-1

Time Saving Options 1-2

Templates and Defaults 1-3

Basic Process 1-3

2 The SAFE “Screen”

Objective 2-1

The Graphical User Interface 2-1

Units 2-3

File Operations 2-3

Viewing Options 2-4

Aerial View 2-5

Refreshing the Display Window 2-5

Draw 2-6

i

<!-- p. 5 -->

Introductory User's Guide

Select 2-6

Edit 2-7

Assign 2-8

Define 2-9

Analyze 2-9

Display 2-10

Design 2-11

Detailing 2-11

Preferences 2-12

More Information 2-12

3 Basic Modes, Drawing Tools, Mouse
Pointers, Coordinate Systems and Grids

Objective 3-1

Select or Draw 3-1

Coordinate Systems and Grids 3-3

4 Begin a Model

Objective 4-1

Create a Basic Grid System 4-2

Begin a Model Using Templates 4-4

Save the Model 4-6

5 Add Structural Objects and Define Proper-
ties

Objective 5-1

Define Properties and Supports 5-1

Draw Point Objects 5-3

Draw Line Objects 5-3

Draw Area Objects 5-4

6 Select Structural Objects

Objective 6-1

ii

<!-- p. 6 -->

Contents

Selection Methods 6-1

Selection Commands 6-3

Deselect Command 6-4

Get Previous Selection Command 6-4

Clear Selection 6-4

7 Load the Structural Model

Objective 7-1

Define Static Load Case Names 7-1

Self-Weight Multiplier 7-2

Long-Term Deflection Multiplier 7-3

Assign Structural Loads 7-3

8 Assign Properties to the Model

Objective 8-1

Assign/Change Properties 8-1

Overlapping Area Objects 8-3

9 Edit the Model Geometry

Objective 9-1

Editing Tools 9-1

10 Analyze the Structural Model

Objective 10-1

Set the Analysis Options 10-1

Run the Analysis 10-2

Locking and Unlocking the Model 10-3

11 Design the Structure

Objective 11-1

Design Process 11-1

iii

<!-- p. 7 -->

Introductory User's Guide

12 CSiDETAILER

Objective 12-1

SAFE to CSiDETAILER 12-1

13 Obtain Basic Graphical Displays

Objective 13-1

Display Analysis Results 13-1

14 Generate Analysis and Design Results

Objective 14-1

Output Options 14-1

iv

<!-- p. 8 -->

1

SAFE™SAFE™ Chapter 1

Program Description

This chapter briefly describes the program and some of the concepts in-
volved in its use.

This is SAFE

SAFE is a powerful tool for the analysis and design of concrete slabs and
basemats. For the first time, modeling, analysis, and design are all inte-
grated in an easy-to-use object-based program that can handle simple or
complex slabs and foundations. Seamless integration with CSiDE-
TAILER provides for the automated generation of detail drawings. SAFE
may be used as a stand-alone application, or may be used in conjunction
with ETABS to complete detailed analysis and design of floor plates cre-
ated in ETABS.

The basic approach for using SAFE is very straightforward. The user es-
tablishes grid lines, places structural objects relative to the grid lines us-
ing points, lines and areas, and assigns loads and structural properties to
those structural objects. Analysis and design are then performed based on

This is SAFE 1 - 1

<!-- p. 9 -->

Introductory User’s Guide

1 the structural elements and their assignments. Results are generated in
graphical or tabular form that can be printed to a printer or to a file for
use in other programs.

In using the program, you manage the File, Edit the SAFE Menu
model, change the View, Define properties or load Commands:
cases, Draw something new in the model, Select that  File
something, Assign properties or loads, Analyze the  Edit
model, Display analysis results for checking, Design  View
the structure, and apply various Options to achieve the  Define
desired outcome with optimum effort. Those actions  Draw
are the basis for the program menu structure. Thus,  Select
familiarity with the menu commands and their func-  Assign
tion is key to expanding your ability to use SAFE.  Analyze
 Display
The subsequent chapters of this manual describe each
 Design
of the menu commands in greater detail. Familiarity
 Options
with the submenus will enable the user to create mod-
els for complex Flat Slabs with Openings, Slabs with
Beams, Footings and Mats.

Additional Technical Notes are available to explain how the program
performs concrete beam and slab design in accordance with applicable
building codes. Information regarding the creation of detail drawings
may be found in the CSiDETAILER manual.

Time Saving Options

The program also includes options that reduce the time spent creating
models. Those options include the following:

 Single Click Drawing - Allows the user to draw line and area objects
with a single mouse click, including drop panels.

 Snap To - Allows the user to place structural objects with accuracy.

 Properties of Object Form - Allows the user to assign structural
properties to the object concurrent with drawing the object.

1 - 2 Time Saving Options

<!-- p. 10 -->

Chapter 1 - Templates and Defaults

Templates and Defaults 1

SAFE provides a number of templates that allow for the rapid generation
of models for a wide range of slab and foundation systems. Those tem-
plates serve as a good starting point because they can be modified easily
or appended to as needed.

The program includes defaults parameters, some of which are building
code specific. Those defaults are accessed using "Preferences." The pos-
sible options available for the default values for preferences are identi-
fied in the design Technical Notes.

By using the built-in templates and defaults, the user can create a model
in a matter of minutes. Consult the SAFE Help topics for more informa-
tion.

Basic Process

The following provides a broad overview of the basic modeling process:

\1. Set the units.

\2. Start a new model.

\3. Set up grid lines.

\4. Define slab and beam properties.

\5. Draw structural objects.

\6. Define supports.

\7. Assign supports.

\8. Define load cases.

\9. Assign loads.

\10. View and edit the model.

\11. Analyze the model.

\12. Display results for checking.

\13. Design the model.

\14. Generate output.

\15. Save the model.

Templates and Defaults 1 - 3

<!-- p. 11 -->

2

SAFE™SAFE™ Chapter 2

The SAFE “Screen”

Objective

This chapter briefly describes the graphical user interface.

The Graphical User Interface

The graphical user interface shown in Figure 2-1 includes the main win-
dow, main title bar, display title bar, menu bar, toolbars, display win-
dows, status bar, mouse pointer position coordinates and the current
units. Each of those items is described in the bulleted list that follows.

 Main Window - This window may be moved, resized, maximized,
minimized, or closed using standard Windows operations. Refer to
Windows help, available on the Start menu, for additional information
on those items.

 Main Title Bar - The main title bar includes the program and model
names. The main title bar is highlighted when the program is in use.

Objective 2 - 1

<!-- p. 12 -->

Introductory User’s Guide

Toolbars
Menu Bar
2 Main Title Bar

Display Title Bar Display Title Bar
(Active Window) (Inactive Window)

Window
Separator
Current
Units

Mouse Pointer
Position Coordinates
Status Bar

Figure 2-1 The SAFE graphical user interface

Move the main window by left clicking in the main title bar and hold-
ing down the mouse button to drag the window.

 Menu Bar - The menu bar contains all of the program's menus.

 Toolbars and Buttons - Toolbars are made up of buttons. Buttons
provide "one-click" access to commonly used commands. Holding the
mouse pointer over a toolbar button for a few seconds without clicking
or holding down any mouse buttons will display a short description of
the button's function in a small text box.

 Display Windows. A display window shows the geometry of the
model and may also include displays of properties, loading and analy-
sis, or design results. Up to four windows may display at any one time.

 Display Title Bar. The display title bar is located at the top of the dis-
play window. The display title bar is highlighted when the associated

2 - 2 The Graphical User Interface

<!-- p. 13 -->

Chapter 2 - Units

display window is active. The text in the display title bar typically in-
cludes the type of the view in the associated display window. 2
 Status Bar - The status bar is located at the bottom of the main win-
dow. Text describing the current status of the program is displayed on
the left side of the status bar.

 Mouse Pointer Position Coordinates - The mouse pointer position
coordinates are displayed on the right-hand side of the status bar. A
window does not need to be active for the mouse pointer position co-
ordinates to be displayed. It is only necessary that the mouse pointer
be over the window. The mouse pointer position coordinates are only
displayed for two-dimensional plan views.

Units

SAFE works with two basic units: force and length. The program offers
many different compatible sets of force and length units to choose from,
such as “Kip-in” or “N-mm.” Angular geometry is measured in degrees.

Upon starting a new model, a set of units should be specified. Those be-
come the “base units” for the model. Although data may be input or re-
ported using any set of units, those values are always converted to and
from the base units of the model.

The current units are displayed in a drop-down box located on the far
right-hand side of the status bar. The units can be changed at any time
during the model creation process.

File Operations

File operations are used to start a new model, to bring in an existing
model for display or modification, to save or export the current model for
use in SAFE or another application, and to produce output. File opera-
tions are selected from the File menu.

New models can be started from scratch or from predefined templates
supplied with the program.

Units 2 - 3

<!-- p. 14 -->

Introductory User’s Guide

In addition to opening files in the standard SAFE database format (.FDB
2 extension), the program also allows files to be imported in the following formats: V6/V7 text file (.F2K extension), V5 text file, or .DXF/.DWG
files (geometry only) created by AutoCAD.

Models created by the program may be saved in the .FDB format, or ex-
ported in the following formats: SAFE text (.F2K), SAP2000 text (.S2K),
AutoCAD (.DXF/.DWG – geometry only) and Access Database file.

CSiDETAILER, which can be started from within SAFE, is an applica-
tion for generating detail drawings for slabs and beams analyzed and de-
signed using SAFE.

Viewing Options

View options, which affect how the structure displays, may be set for
each display window and the options may differ from window to win-
dow. Those options are available on the View menu and from the tool-
bar.

 Set Layers of the Slab – The definition of the slab for analysis and
design purposes is accomplished using layers. The three layers in the
SAFE model of a slab are Structural Layer, X-Design Strip Layer, and
Y-Design Strip Layer. The Structural Layer is used to define slab ge-
ometry, load, and boundary conditions, which are related to analysis
only. The Design Strip Layers are used to define the design strips. The
Design Strip Layers hide all information related to analysis.

 Set 2-D View - A 2-D view consists of a single plane parallel to the X-
Y coordinate plane.

 Set 3-D View - A 3-D view shows the whole model from a vantage
point of your choice. The view direction is defined by an angle in the
horizontal plane and an angle above the horizontal plane.

 Set Object Options – Various options are available to control how
objects appear in a display window. The options primarily affect views
of the undeformed shape. They include controls for visibility and la-
beling for the various types of objects, as well as the “shrunken-object

2 - 4 Viewing Options

<!-- p. 15 -->

Chapter 2 - Aerial View

view.” This option shrinks objects away from the joints allowing better
review of the model’s connectivity. 2
 Zoom Features – Zoom in to a view to see more detail, or zoom out
to see more of the structure. Zooming in and out may be completed in
predefined increments. You may also zoom in to a part of the structure
by dragging a selection window around the portion of interest.

 Pan – Panning allows dynamic movement of the structure around the
display window by clicking and moving the mouse.

 Other Options – Grid lines and the global axes can be turned on and
off. Automatically generated mesh can be viewed. After these and
other settings have been set, the view parameters can be saved as a
Named View and subsequently recalled and applied to any display
window.

Aerial View

The Aerial View displays a full view of the active window’s drawing in a
separate window. Use the Aerial View to help move around the active
window of a larger model, and with the zoom features, to view smaller
areas more easily. Also use the aerial view to track which part of the
model is displayed in the active window. Each time the model is edited,
the aerial view is updated. The Aerial View window can be made visible
using the Options menu > Show Aerial View Window command.

Refreshing the Display Window

After performing certain options, the Display Window may need to be
redrawn. The display window is not automatically refreshed after every
change to save time. To refresh a display, click the Refresh Window

button .

Aerial View 2 - 5

<!-- p. 16 -->

Introductory User’s Guide

Draw
2 Drawing is used to add new objects to the model or to modify one object
at a time. Objects include beams, slabs, slab design strips, and other
point, line and area objects. To draw, the program must be in Draw
Mode, which is activated by clicking one of the draw buttons on the
toolbar or using a Draw menu command.

In Draw Mode, the left mouse button is used to draw and edit objects,
and the right mouse button is used to query the properties of objects.
Drawing may be performed in the XY plane only.

Depending on the type of object to be drawn, a “Properties of Object”
form appears that can be used to specify various structural and support
properties for the object. As point objects are drawn, column support
properties can be assigned simultaneously. Line objects may be assigned
beam structural properties or wall support properties when being drawn,
and area objects can be assigned slab properties or defined as openings.
After an object has been drawn, the object may be selected and loads
may be assigned to it, or existing assignments can be modified.

Draw operations are also affected by the view layer of the slab. For
structural objects and loading, usually the view is set to the Structural
Layer. To define design slab strips, set the view to Strip Layers.

Draw Mode and Select Mode are mutually exclusive. No other opera-
tions can be performed when the program is in Draw Mode.

Select

Selection is used to identify those objects to which the next operation
will apply.

SAFE uses a “noun-verb” concept; that is, a selection is made and then
an operation is performed. Certain editing, assigning, printing and dis-
playing operations require prior selection of an object.

2 - 6 Draw

<!-- p. 17 -->

Chapter 2 - Edit

To select, the program must be in Select Mode, which is activated by
clicking one of the select buttons on the toolbar. Alternatively, selecting 2 any action from the Select menu puts the program into Select Mode.

Many different types of selection are available, including:

 Selecting individual objects.

 Drawing a window around objects.

 Drawing a line that intersects objects.

 Selecting beam or slab objects having the same property type.

 Selecting beams or slabs by groups.

 Selecting all objects.

 Selecting previously selected objects again.

In Select Mode, the left mouse button is used to select objects, and the
right mouse button is used to query the properties of objects.

Draw Mode and Select Mode are mutually exclusive.

Edit

Editing is used to make changes to the model. Most editing operations
work with one or more objects that were selected immediately before
using the Edit command. Editing operations on the Edit menu include the
following:

 Cutting and Copying the geometry of selected objects to the Windows
clipboard. Geometry information put on the clipboard can be accessed
by other programs, such as spreadsheets.

 Pasting object geometry from the Windows clipboard into the model.
The geometry could be edited in a spreadsheet program before being
copied and Pasted into SAFE.

 Deleting objects.

Edit 2 - 7

<!-- p. 18 -->

Introductory User’s Guide

 Moving points, which also modifies connected objects.
2  Replicating objects in a linear or radial array or mirroring them.

 Aligning points and their connected objects to be exactly vertical or
horizontal.

Assign

Certain assignments may be made when drawing an object, such as as-
signing the beam structural property when drawing a line object. How-
ever, additional assignments, or changes to assignments, may be made to
one or more objects that were selected immediately before using the As-
sign menu command. Assignment operations are selected from the As-
sign menu, including:

 Assigning slab properties to area objects.

 Assigning openings to area objects.

 Assigning rib/joist locations for ribbed/waffle type slabs.

 Assigning beam properties to line objects.

 Assigning elevation offsets to area and line objects.

 Assigning column support properties to point objects.

 Assigning wall support properties to line objects.

 Assigning soil support properties to area objects.

 Assigning slab discontinuities to line objects.

 Assigning point, line, and surface loads.

 Assigning objects to named groups.

2 - 8 Assign

<!-- p. 19 -->

Chapter 2 - Define

Define
Define is used to create named entities that are not part of the geometry 2
of the model. Those entities, accessed from the Define menu, include the
following:

 Slab material and section properties and design parameters.

 Beam material and section properties and design parameters.

 Column support properties.

 Wall support properties.

 Soil support properties.

 Static load cases.

 Load combinations.

 Group names.

Definition of those entities does not require prior selection of an object.

Analyze

After a complete structural model has been created using the preceding
commands, the model can be analyzed to determine the resulting dis-
placements, stresses and reactions.

Before running an analysis, Set Options for the analysis using the Ana-
lyze menu, including:

 Type of analysis and any control parameters.

 Maximum mesh dimension.

After setting the options, especially the “Maximum Mesh Dimension,” it
may be advantageous to view the generated finite element mesh. To view
the mesh and verify that it is satisfactory, click the Set Object Options
button on the toolbar and check the Show Mesh box on the resulting

Define 2 - 9

<!-- p. 20 -->

Introductory User’s Guide

form; click the button again and uncheck the box to turn off the display
2 of the mesh, if desired.
To run the analysis, select Run Analysis from the Analyze menu, or click
the Run Analysis button on the toolbar. The program saves the model in
a SAFE database file, then checks and analyzes the model. During the
checking and analysis phases, messages from the analysis engine appear
in a monitor window. When the analysis is complete, the scroll bar on
the monitor window can be used to scroll through and review the analy-
sis messages.

Display

The Display menu commands are used to view the model and the results
of the analysis. Graphical and tabular displays are available in SAFE.
Most display types may be chosen from the Display menu. Several of
them may also be accessed using toolbar buttons.

 Graphical Displays – Different types of graphical display may be
selected for each display window. Each window may also have its own
view orientation and display options. Available displays of the model
input include the undeformed geometry and loads. Analysis results
that can be graphically displayed include deformed shapes; beam force
and moment diagrams; slab moment and shear contour plots;
integrated force and moment diagrams for design slab strips; and
reactive forces, including bearing pressures. Additionally, deformed
shape plots may be animated.

 Tabular Displays – Tabular information can be displayed for selected
objects by choosing Show Input Tables or Show Output Tables from
the Display menu. Tabular information can be printed or saved to a file
for selected objects by choosing the File menu > Print Input Tables
or File menu > Print Output Tables command. If no objects are
selected, the tables produced are for the entire model.

2 - 10 Display

<!-- p. 21 -->

Chapter 2 - Design

Design
After an analysis has been completed, concrete slabs and beams can be 2
designed with respect to design code requirements. Design may be per-
formed for the given load combinations by choosing the Design menu >
Start Design command. Before designing, verify the selected design
code using the Options menu > Preferences command and the Design
tab.

Graphical displays of reinforcing steel and other design parameters are
available. Tabular design information can also be displayed using com-
mands from the Design menu. Tabular design information can be printed
for selected objects using the File menu > Print Design Tables com-
mand.

Detailing

After analysis and design are complete, use the optional CSiDETAILER
program to create a detail model and generate plans, sections and tables
showing the placement and size of the reinforcing based on the user-
selected code. The detailing model created by CSiDETAILER is an in-
ternal model, with input consisting of data from the analysis and design
of the user’s model in SAFE and detailing options and preferences set
by the user.

Use the commands on the Detailing menu to set preferences for the ap-
pearance of the drawings and to start the CSiDETAILER program. Use
the commands within the CSiDETAILER program to specify additional
preference settings that include, among other items, code, smallest and
largest rebar, minimum and maximum number of rebar, shortest and
longest rebar, rebar cutoff (curtailment) rules, rebar shapes, and rebar
marks.

Output from the detailing model consists of detailed area objects that
represent slab, footing and mat members and detailed line objects that
represent beam members. Detailing information that can be viewed in
plans, sections, elevations, tables and schedules includes the number, the
size, the shape and the location of reinforcing bars as calculated by

Design 2 - 11

<!-- p. 22 -->

Introductory User’s Guide

CSiDETAILER based on the preferences. Output from CSiDETAILER
2 can be exported to .dwg or .dxf format for further refinement using AutoCAD.

Preferences

SAFE allows custom setting of some parameters using the Options
menu > Preferences command, including the design code, the cross-
sectional areas of nominal bars, tolerances, and fonts.

More Information

More information about SAFE features and commands is available from
the SAFE Help topics contained within the program. Pressing the F1 key
on the keyboard while a form is displayed in the program will access
context-sensitive help for that form. Information about code-specific de-
sign is available in the SAFE Design Manual and information about de-
tailing using the optional CSiDETAILER program is available in the
CSiDETAILER User's Manual.

2 - 12 Preferences

<!-- p. 23 -->

3

SAFE™SAFE™ Chapter 3

Basic Modes, Drawing Tools, Mouse Pointers,
Coordinate Systems and Grids

Objective

This chapter briefly describes the two modes of user operation for SAFE,
the drawing tools, the mouse pointers, the coordinate systems and grid
lines, and the system-generated mesh.

Select or Draw

The two distinct modes in this program are the select mode and the draw
mode. The select mode allows you to select objects and is used for edit-
ing operations, making assignments to objects, and viewing or printing
results. The draw mode allows you to draw objects. By default, the pro-
gram is in select mode. Chapter 6 describes the various methods for se-
lecting points, lines, and areas in your model.

Objective 3 - 1

<!-- p. 24 -->

Introductory User’s Guide

The draw mode automatically enables when you select one of the fol-
lowing commands from the Draw menu or click on the corresponding
button(s) on the toolbar:
3
 Draw Point Objects

 Draw Line Objects or

 Draw Area Objects , , ,

The draw mode remains enabled until you do one of the following to re-
turn to the select mode:

 Click the Pointer button on the toolbar .

 Press the Esc key on the keyboard.

 Select a command from the Select menu.

The mouse pointer indicates which mode is enabled. The mouse
pointer is defined by the mouse pointer properties identified in the Win-
dows Control Panel for the Normal Select Pointer and the Alternate Se-
lect pointer.

 In select mode, the pointer is the Normal Select Pointer, and
if the default settings are being used, the mouse pointer will
look like this .

 In draw mode, the mouse pointer is the Alternate Select
pointer, and if the default settings are being used, the mouse
pointer will look like this .

Note that while in draw mode if the mouse pointer “hovers” over the
toolbar buttons or the menus, the pointer temporarily changes to the se-
lection pointer. If you do not click on one of the menus or toolbar but-
tons, the mouse pointer reverts to the draw mode pointer when you move
back into the display window.

3 - 2 Select or Draw

<!-- p. 25 -->

Chapter 3 - Coordinate Systems and Grids

Typically, set the properties for the mouse by clicking on the Windows 3
Start menu, then Control panel and clicking on Mouse to bring up your
mouse properties form.

Other mouse properties used at various special times in the program in-
clude Help Select, Busy, Text Select, Vertical Resize, Horizontal Resize,
and Precision Select. The appearance of each of those mouse pointers
also will change depending on the mouse pointer properties specified.

Coordinate Systems and Grids

All locations in the model are ultimately defined with respect to a single
global coordinate system. This is a three-dimensional, right-handed,
Cartesian (rectangular) coordinate system. The three axes, X, Y, and Z,
are mutually perpendicular and satisfy the right-hand rule. All area, line
and point objects lie on the XY (horizontal) plane, and although vertical
offsets may be assigned in SAFE to slabs and beams for later use in
CSiDETAILER, those offsets do not affect the analysis or design.

SAFE always considers the +Z direction as upward. By default, a posi-
tive load acts in the –Z (downward) direction.

In addition to the coordinate system, a two-dimensional grid system con-
sisting of “construction” lines used for locating objects in the model is
also defined. The grid system is also of Cartesian (rectangular) defini-
tion, and is positioned relative to the global system.

Drawing operations tend to “snap” to grid line intersections (default) un-
less this feature is turned off. Numerous other snaps also are available on
the Draw menu, including snap to line ends and midpoints and snap to
intersections. Those powerful tools should be used whenever possible to
ensure accurate model construction. Not using the snaps may result in
“gaps” between objects, causing errors in the model’s connectivity.

Any number of grid lines in the X or Y directions with arbitrary spacing
can be defined. When starting a new model, grid spacing must be uni-
form. Thereafter, grid lines can be added, moved, and deleted.

Coordinate Systems and Grids 3 - 3

<!-- p. 26 -->

4

SAFE™SAFE™ Chapter 4

Begin a Model

Objective

This chapter describes how to create a basic grid system, begin a model
using templates, and save the model. The grid system is the basis for cre-
ating the model. Structural objects are placed relative to the grid system,
and typically the model grids should be defined to match the grids shown
on the design documents.

The built-in SAFE templates are very convenient tools for the immediate
generation of models of slabs and basemats that have regular geometries.
The templates require simple control information to define the basic pa-
rameters for the structural geometry and loading from which the com-
plete slab model, including the slab design strips, is created. In many
cases, templates can be used as starting points for the definition of more
complex slab systems.

Objective 4 - 1

<!-- p. 27 -->

Introductory User’s Guide

Create a Basic Grid System

Begin creating a grid system by clicking the File menu > New Model
command or the New Model button . The form shown in Figure 4-1
will display.4

Figure 4-1
The Grid
Definition
form

The Grid Definition form is used to specify the number of horizontal grid
lines and spacing. To obtain a uniform grid, simply specify the number
of grid lines in the X and Y directions and the grid spacing for those
lines. Note that the uniform spacing in the X and Y directions may be
different. This option defines a grid system for the global coordinate
system only. Click the OK button to accept the changes made to the
form, or click Cancel to cancel the changes.

To specify non-uniform spacing and to label the grid lines, click the Edit
menu > Edit Grid command. This will display a Define Grid form (see
Figure 4-2), which has options for changing grid labels and spacing for
each grid line in the X or Y directions. The form also has options related
to how the grid lines display, including an option to make the grid lines
invisible. Note that the global coordinate/grid system is a Cartesian (rec-
tangular) coordinate system. A reference “datum” elevation may also be

4 - 2 Create a Basic Grid System

<!-- p. 28 -->

Chapter 4 - Create a Basic Grid System

specified, which is useful when analyzing multiple floors from the same
building.

4

Figure 4-2
The Define Grid form

Definition of the grid system is important because of the following:

 Objects snap to grid lines when drawn in the model; thus, grid lines
must be defined accurately so that the placement of objects can be
completed efficiently.

 Objects mesh at their intersections with grid lines.

 The grid lines in the model can be defined with the same names as are
used on the building plans, allowing for easier identification of specific
locations in the model.

Create a Basic Grid System 4 - 3

<!-- p. 29 -->

Introductory User’s Guide

Begin a Model Using Templates

SAFE also has an option to begin a model using templates. Begin a
model using templates by clicking the File menu > New Model from
Template command. The Slab Templates form shown in Figure 4-3 will4
display.

Figure 4-3
The Slab
Templates
form

Note that there are five slab templates, one base mat template, and two
templates for footings. Template models provide a quick, easy way of
starting a model. They automatically add structural objects with appro-
priate properties to a model. We highly recommend that you start your
models using templates whenever possible.

Choose any of the templates by left clicking its associated button. When
a template button is clicked, a form for that template will appear. Use the
form to specify various data for the template, such as grid dimensions
and spacing, slab or mat thicknesses, loads, drop panels or footings.

Important Note: When using the templates, beams, joists and ribs are
modeled with depths equal to the dimension from the top of the slab to

4 - 4 Begin a Model Using Templates

<!-- p. 30 -->

Chapter 4 - Begin a Model Using Templates

the bottom of the beam, joist or rib. Beams are modeled as line objects,
and joists and ribs are modeled with equivalent slab properties.

After specifying data for a template, the model will appear in the display
window. The default display will show two views tiled vertically, a 4
Structural Layer Plan View on the left and a Structural Layer 3-D View
on the right, as shown in Figure 4-4. Use the Options menu > Windows
command to change the number of windows displayed.

Figure 4-4
The SAFE main window

Note that the Structural Layer Plan View is active in Figure 4-4. When
the window is active, the display title bar is highlighted. Set a view ac-
tive by clicking anywhere in the view window.

Begin a Model Using Templates 4 - 5

<!-- p. 31 -->

Introductory User’s Guide

Save the Model

It is a good idea to save your model often. To save the model, click on the
File menu > Save command or the Save button. The first time
the model is saved, SAFE will prompt you to specify a file name in the4
Save Model File As form.

4 - 6 Save the Model

<!-- p. 32 -->

5

SAFE™SAFE™ Chapter 5

Add Structural Objects and Define Properties

Objective

Point, line, and area objects are used in SAFE to represent columns sup-
ports, beams and slabs. Properties are defined to reflect their structural
behavior in the model. This chapter touches briefly on defining proper-
ties and supports and describes how to add objects to the structural
model. Point, line, and area objects can be added to a model that was
started using only a grid system or to a model started using a template
(see the previous chapter).

Define Properties and Supports

Some properties, such as slab and beam properties that contain both ma-
terial and section definitions, are named entities that must be specified
using the commands on the Define menu before assigning them to ob-
jects as described later in this chapter and in Chapter 8. If you assign a
property to an object, for example a beam property to a line object, any

Objective 5 - 1

<!-- p. 33 -->

Introductory User’s Guide

changes to the definition of the property will automatically apply to the
object. A named property has no effect on the model unless it is assigned
to an object.

Supports may be assigned to point, line and area objects, and similar to
properties, they are named entities that must be specified before they are
5 assigned. Column and wall supports may be defined as “Below,”
“Above” or “Above & Below” the slab. Based on the object type and the
associated support properties, the program generates spring elements at
each mesh location.

Table 5-1 identifies the subcommands on the Define menu, the type of
object to which the definition can be applied, and the form used to com-
plete the definition. Context sensitive help is available by pressing the F1
key when the form is displayed on-screen.

TABLE 5-1 Property Definitions

Property Object Type Name of Input Form

Slab Properties (Drop, Column, Openings) Area Slab Property Data
Beam Properties Line Property Data for Beam
Column Supports Point Column Support Property Data

Wall Supports Line Wall Support Property Data
Soil Supports Area Soil Support Property Data

The input forms have options to add new definitions, modify or review
existing definitions, and delete existing definitions. Each property defi-
nition should have a unique name that the user can specify, or use the
program-suggested name. It is important that the definition names make
it easy to assign them to the various objects correctly!

Depending on the type of property, the definitions can include user-
specified analysis parameters such as thicknesses, heights, weights,
Modulus of elasticity, Poisson’s ratio, and design parameters such as top
and bottom cover, material strengths and many other parameters. In ad-
dition to those items, the Slab Property Data form also has a parameter
for specifying the type of slab (e.g., flat slab, waffle, drop), which con-
trols not only the analysis formulation, but also the design and detailing.

5 - 2 Define Properties and Supports

<!-- p. 34 -->

Chapter 5 - Draw Point Objects

Draw Point Objects

Point objects are most commonly used to create column supports. To
draw a point object, make sure that the Structural Layer Plan View is ac-
tive. Click the Draw Point Object button or use the Draw menu >
Draw Point Objects command. The Properties of Object pop-up form 5
for points shown in Figure 5-1 will appear.

Figure 5-1
Properties of
Object form
for Points

The Properties of Object form provides a Property drop-down list of the
previously defined properties that can be assigned to the Type of Point.
Review the definitions and drawing controls (Plan Offset X, Plan Offset
Y) shown in the form before drawing the point. Change any entry in the
form by clicking on it and making a new selection from the drop-down
list or typing in new information into the edit box, as appropriate.

With the parameters in the Properties of Object form set, left click any-
where in the Structural Layer Plan View to locate the point object. A
“plus” mark should appear at that point in the views. Continue to place
other points/columns by left clicking.

Draw Line Objects

Line objects are most commonly used to create beams or wall supports.
To draw a line object, activate the Structural Layer Plan View. Click the
Quick Draw Line Objects button, or the Draw menu > Quick
Draw Line Objects command. The Properties of Object pop-up form for
line objects shown in Figure 5-2 will appear.

Figure 5-2
Properties of
Object form
for Lines

Draw Point Objects 5 - 3

<!-- p. 35 -->

Introductory User’s Guide

Similar to points, the Properties of Object form provides a Property drop-
down list of the previously defined properties that can be assigned to the
Type of Line. Change any entry in the form by clicking on it and making
a new selection from the drop-down list or typing in new information
into the edit box, as appropriate.
5 With the parameters in the Properties of Object form set, left click once
in the Structural Layer Plan View on a grid line to place a line object.
With the parameters set as shown in Figure 5-2, a beam will appear along
the selected grid line in the display window. Continue to place other
beams, or change the Type of Line to Wall to place wall supports.

Alternatively, click once in the center of the grid lines outlining a bay to
draw beams or wall supports around the entire bay simultaneously.

Draw Area Objects

Area objects are most commonly used to create slabs (including footings
and mats) or openings in slabs. To draw an area object, activate the
Structural Layer Plan View. Click the Draw Area Objects button or
select the Draw menu > Draw Area Objects command. The Properties
of Object pop-up form for area objects shown in Figure 5-3 will appear.

Figure 5-3
Properties of
Object form
for Areas

Similar to points and lines, this Properties of Object form provides a
Property drop-down list of the previously defined properties that can be
assigned to the Type of Area. Change any entry in the form by clicking
on it and making a new selection from the drop-down list or typing in
new information into the edit box, as appropriate.

With the parameters in the Properties of Object form set, ensure that the
Snap to Grid Intersections and Points command is active to assist in
accurately drawing the area object. This command is active when its as-

5 - 4 Draw Area Objects

<!-- p. 36 -->

Chapter 5 - Draw Area Objects

sociated button appears depressed. Alternatively, use the Draw menu
\> Snap To > Points command to ensure that this command is active.
The Snap to Grid Intersections and Points command is active by de-
fault.

Left click once at a grid intersection (or any other position in the Struc-
tural Layer Plan View) to begin the area object at that location. Then, 5
moving around the perimeter of the area object, click once at other grid
intersections to draw the outline of the object. Press the Enter key on the
keyboard to complete the object.

If you have made a mistake while drawing this object, click the Select
Object button to change the program from Draw mode to Select
mode. Then click the Edit menu > Undo Area Object Add command.

To better view the area addition, click the Set Object Options button
. When the Set Objects form appears, check the Fill Elements check
box as shown in Figure 5-4. Click the OK button to update the view.

Figure 5-4
Set Objects
form

Draw Area Objects 5 - 5

<!-- p. 37 -->

6

SAFE™SAFE™ Chapter 6

Select Structural Objects

Objective

This chapter describes the options available for selecting objects in
SAFE.

Selection Methods

To enable the select mode, click the Pointer button on the toolbar .

The program has three basic methods of selecting objects:

 Left click: Left click on an object to select it. If there are multiple
objects, one on top of the other, hold down the Ctrl key on the key-
board and left click on the objects. A Selection List form similar to
that shown in Figure 6-1will appear and identify the objects that exist
at that location. Select the desired object by moving the mouse
pointer over it in the form and left clicking on it.

Objective 6 - 1

<!-- p. 38 -->

Introductory User’s Guide

Figure 6-1
Selection
List form

6

 Window or "Windowing": To draw a window around an object(s) to
select it, position the mouse pointer beyond the limits of the object; for
example, above and to the left of the object(s). Then depress and hold
down the left mouse button. While keeping the left button depressed,
drag the mouse to a position below and to the right of the object(s).
Release the left mouse button to complete the selection. Note the fol-
lowing about window selection.

As the mouse is dragged, a "rubber band window" will appear. The
rubber band window is a dashed rectangle that changes shape as the
mouse is moved. Any visible object that is completely inside the rub-
ber band window when the left mouse button is released is selected.

The window can be started at any point as long as the starting point is
beyond the limits of the object(s) to be selected. For example, the
starting point can be above and to the right, below and to the left or
below and to the right of the object(s). In all cases, drag the mouse di-
agonally across the object(s) to be selected.

An entire object must lie within the rubber band window for the object
to be selected.

 Intersecting Line: To select one or more objects by drawing a line
through it or them, click the Select menu > Select > Intersecting Line
command or the Select using Intersecting Line button . Then po-
sition the mouse pointer to one side of the object(s) to be selected. De-

6 - 2 Selection Methods

<!-- p. 39 -->

Chapter 6 - Selection Commands

press and hold down the left button on the mouse. While keeping the
left button depressed, drag the mouse across the object(s). Release the
left mouse button to complete the selection. Note the following about
the intersecting line selection method:

As the mouse is dragged, a "rubber band line" appears. The rubber
band line is a dashed line that changes length and orientation as the
mouse is moved. The rubber band line extends from the point where 6
the left mouse button is first depressed to the current mouse pointer po-
sition. Any visible object that is intersected (crossed) by the rubber
band line when the left mouse button is released is selected.

After using this method to make a selection, the program defaults to
the window selection mode. Thus, the menu command or button
must be used each time to access the Select Using Intersecting Line
method.

Selection Commands

Table 6-1 identifies the submenu commands and related actions accessed
using the Select menu command.

Table 6-1 Submenus of the Select Menu Command

Command Action

Select menu > Select Select the name of any collection of objects that has
by groups been defined as a group from the Select Group box

and that group will be selected.

Select menu > Select Select a beam property name from the Select Beam

by beam properties Properties form and all line objects that have been

assigned that beam property will be selected.

Select menu > Select Select a slab property name from the Select Slab

by slab properties Properties form and all area objects that have been

assigned that slab property will be selected.

Selection Commands 6 - 3

<!-- p. 40 -->

Introductory User’s Guide

Table 6-1 Submenus of the Select Menu Command

Command Action

Select menu > Select Selects all objects in the model, both visible and
all invisible objects. Be careful using this command.
6 You can also use the Select All button to exe- cute this command.

Deselect Command

Objects can be deselected one at a time by left clicking on the selected
objects. Alternatively, use the Select menu > Deselect command and its
submenus for quicker and more specific deselection actions. This com-
mand accesses submenu items similar to those described in the previous
section, except that executing the Select menu > Deselect command and
an associated submenu item deselects rather than selects an object(s). As
an example of the advantage of this option, assume that all objects in a
model need to be selected except for those with a particular beam prop-
erty. Do this quickly and easily by first using the Select menu > Select
\> All command and then using the Select menu > Deselect > Beam
Properties command.

Get Previous Selection Command

The Select menu > Get Previous Selection command reselects the pre-
viously selected object(s). For example, assume that some area objects
were selected by clicking on them and slab properties were assigned to
them. Use the Get Previous Selection command or the Get Previous
Selection button to select the area objects again and assign some-

thing else to them, such as surface loads.

Clear Selection

The Select menu > Clear Selection command and its associated Clear
Selection button will clear all currently selected objects. It is an all
or nothing command and cannot be used to selectively clear a portion of
a selection.

6 - 4 Selection Commands

<!-- p. 41 -->

7
SAFE™SAFE™ Chapter 7

Load the Structural Model

Objective

This chapter describes defining and assigning structural loads for the
Note: model. Loads, including dead, live, earthquake, snow and the like, are
An unlimited defined as static load cases that are assigned to various structural objects
number of in the model.
load cases
can be Note that the program automatically assembles the static load cases into
defined in design load combinations in accordance with the specified building code.
SAFE.
Design codes can be selected using the Options menu > Preferences
command.

Define Static Load Case Names

Click the Define menu > Static Load Cases command to access the
Static Load Case Names form. Use the form to specify the following in-
formation:

Objective 7 - 1

<!-- p. 42 -->

Introductory User’s Guide

 The name of the load case. The program does not allow use of dupli-
cate names.

 A load type, which can be selected from the Type drop-down list.

 A self-weight multiplier (see the explanation about the self-weight
multiplier that follows).

 A long-term deflection multiplier (see the explanation about the
7 long-term deflection multiplier that follows).

Click the Add New Load button to add a new load case name. Select a
previously defined load case and click the Modify Load button to mod-
ify that load case, or click the Delete Load button to delete it. Consult
the SAFE Help for more specific information about defining loads.

Self-Weight Multiplier

The self-weight of the structure is determined by multiplying the unit
weight (weight per unit volume) of each object that has structural prop-
erties times the volume of the object. The unit weight is specified in the
slab or beam properties, which are accessed using the Define menu >
Slab Properties or Define menu > Beam Properties commands, re-
spectively.

Specify that a portion of the self-weight be applied to any static load
case. The self-weight multiplier controls what portion of the self-weight
is included in a load case. A self-weight multiplier of 1 means to include
the full self-weight of the structure in the load case. A self-weight multi-
plier of 0.5 means to include half of the self-weight of the structure in the
load case.

Normally you should specify a self-weight multiplier of 1 in one
static load case only, usually the dead load case. All other static load
cases then have self-weight multipliers of zero. Note that if you include a
self-weight multiplier of 1 in two different load cases, and then combine
those two load cases in a load combination, the results for the load com-
bination are based on an analysis where double the self-weight of the
structure has been applied as a load.

7 - 2 Define Static Load Case Names

<!-- p. 43 -->

Chapter 7 - Assign Structural Loads

Long-Term Deflection Multiplier

SAFE allows for an elastic (linear) analysis or a cracked deflection (non-
linear) analysis. In a cracked deflection analysis, SAFE takes into ac-
count the reduction of the gross section properties resulting from the
cracking of the concrete, which results in an increase in the deflections.

When performing a cracked deflection analysis, the user has the option to
assign a long-term deflection multiplier to each load case to account for
behavior such as shrinkage and creep. Normally, a long-term deflection 7
multiplier with a value greater than 1 should be applied only to per-
manent load cases, such as the dead load case. All other temporary
load cases (for example, live, wind, earthquake or snow) should use a
factor of 1. The long-term deflection multiplier works only with the
cracked deflection analysis.

Assign Structural Loads

Static loads can be assigned to point, line, and area objects. The object(s)
must first be selected before a load can be assigned. Chapter 6 of this
guide describes the options for selecting structural objects.

After the object has been selected, click the Assign menu command to
access the applicable submenu and assignment options. Note that the
type of object selected determines which assignment can be made. For
example, if an area object is selected, the Surface Loads command will
be available, while a point selection will allow the user to specify either
Point Loads or Point Deflections. If only point objects (e.g., column
supports) and line objects (e.g., beams) are selected before clicking the
Assign menu command, the Surface Loads command will not be avail-
able.

After clicking the Assign menu command and the submenu applicable to
the type of object, a form will appear. Table 7-1 identifies the forms gen-
erated when the various commands are used. Consult the SAFE Help for
more specific information about assigning loads.

Assign Structural Loads 7 - 3

<!-- p. 44 -->

Introductory User’s Guide

TABLE 7-1 Input Forms for Load Commands on the Assign Menu

Command Name of Input Form

Assign menu > Point Loads Point Loads

Assign menu > Point Displacements Point Displacement Loads

Assign menu > Line Loads Line Loads

Assign menu > Surface Loads Surface Loads7

Although the forms vary depending on the command used, each form has
a drop-down list that allows the user to select the load case to be as-
signed. The forms also include other object/assignment-specific input
fields that enable the user to refine the load assignment. Context-
sensitive help is available for each form by pressing the F1 key on the
keyboard when the form is displayed on screen.

It is important to remember that SAFE does not allow any deformation in
the plane of the slab, so loads that would cause only displacements in the
slab plane are not available within the loading forms.

7 - 4 Assign Structural Loads

<!-- p. 45 -->

SAFE™SAFE™ Chapter 8 8

Assign Properties to the Model

Objective

This chapter describes how to assign or change the properties of struc-
tural objects in the model. Note that properties and supports can be as-
signed when the object is being drawn as described in Chapter 5.

Assign/Change Properties

In creating the model, the user draws point, line, and area objects. To en-
able analysis and design, those objects must be assigned properties, such
as slab properties, beam properties, column supports, wall supports, and
loads, among others. Note that the definition of properties and assign-
ment of loads were explained in Chapters 5 and 7, respectively.

The types of assignments that can be made to an object depend on the
type of object. Table 8-1 identifies the types of assignments that can be
made using the Assign menu commands, depending on the type of ob-
ject.

Objective 8 - 1

<!-- p. 46 -->

Introductory User’s Guide

TABLE 8-1 Possible Assignments to Objects by Object Type

Object Assignment Option Name of Input Form*

Points Point Restraints Point Restraints
Column Supports Support Properties

Lines Beam Properties Beam Properties
Beam Offset Beam Offset

Wall Supports Support Properties
Releases Slab Releases
8 Shell/Areas SlabSlab PropertiesOffset SlabSlab PropertiesOffset
Slab Rib Locations Slab Rib Location

Opening **
Soil Supports Support Properties

\* With a form displayed on-screen, press the F1key to access context-sensitive help.

\**No form; command converts area to an opening

Releases, point restraints, offsets and rib/joist locations are assigned di-
rectly to objects. Those properties can only be changed by making an-
other assignment of that same property to the object; they are not named
entities and they do not exist independent of the objects.

View the assignment made to point, line, and area objects by right
clicking on the object. The appropriate Point Information, Line Informa-
tion, or Area Information form will display.

In each case, the user must select an object before executing the desired
assignment command (for example, a line object must be selected before
using the Assign menu > Beam Properties command). As explained in
Chapter 6 of this guide, using the Ctrl key and left clicking on a location
in the model can simplify the process of selecting objects when multiple
objects may be present at the same location or if selecting objects is new
to the user and seems challenging.

As shown in Table 8-1, the availability of commands depends on the
type of object selected. The input forms include object/assignment-
specific input fields that enable the user to refine the assignment. Modifi-
cations to the assignments can be made by accessing the input forms us-
ing the appropriate Assign menu command. Context-sensitive help ex-

8 - 2 Assign/Change Properties

<!-- p. 47 -->

Chapter 8 - Overlapping Area Objects

plaining the various forms is available by pressing the F1 key on the
keyboard while a form is displayed on-screen.

Overlapping Area Objects

Overlapping area objects often occur at support locations, where it is not
uncommon to draw a slab, a drop, and a column member at the same
plan position. When multiple objects overlap, the program determines
which property to use based on the following hierarchy:
An area object designated as a column type will replace an area 8
object designated as a drop, which in turn will replace an area
object designated as a slab.

Thus, for a model containing both slab and column type area objects, the
program will use only the column type properties in the column locations
when generating the internal finite element mesh, and will ignore the
overlapping slab properties. Type identifiers for area objects are speci-
fied on the Slab Property Data form.

Occasionally an area object may be drawn within the boundary of a lar-
ger area object, and both objects have the same type assignment (e.g.,
they are both slab types). In that case, SAFE will use the properties asso-
ciated with the smaller object that lies completely within the larger ob-
ject. In the case where the objects overlap and one is not completely em-
bedded within the other (and assuming they are of similar type), the pro-
gram will use the properties from the object that was last drawn in the
overlapping area.

Important Note: Only the properties of the overlapping area objects are
ignored; any surface loads applied to those redundant objects are not
omitted and will be applied in an additive manner. Therefore, although
the areas of overlap typically are small in comparison to the total area of
the slab, it is generally recommended that load assignments be made to
only one object at any given location. Typically the load would be as-
signed to the primary slab area objects, and surface loads would not be
assigned to drops or column area objects.

It should also be noted that any area object assigned as an opening using
the Assign menu > Opening command will take precedence over an

Overlapping Area Objects 8 - 3

<!-- p. 48 -->

Introductory User’s Guide

area object with a slab property assignment in the same location. In ad-
dition, area objects assigned as openings lose all surface loads that may
have been applied to the objects (i.e., they are unloaded openings).

Finally, when it comes to design, area objects designated as column
types should not be designed as it is generally not appropriate to use slab
design rules for a column. An option is available on the forms to specify
No Design.

Note: As a general rule, area objects that are designated as column
8 types should have a thickness approximately equal to five times that of
the surrounding slab, which results in an element that will be at least an
order of magnitude two times stiffer in bending than the slab.

8 - 4 Overlapping Area Objects

<!-- p. 49 -->

SAFE™SAFE™ Chapter 9
9

Edit the Model Geometry

Objective

This chapter describes how to edit the model quickly and easily while
maintaining model integrity.

Editing Tools

During the course of creating the model, the user may need to edit the
model. Table 9-1 identifies the various edit command available in SAFE.
Some are familiar Windows commands.

In most cases, the user should first select the point, line, or area object
and then click the appropriate menu or button. In some cases, the action
will be immediate (for example, the Undo or Redo commands). In other
cases, a form will appear that allows the user to specify how the object is
to be edited (for example, the Edit menu > Replicate command accesses
the Replicate form, which allows the user to replicate point, line or area
objects in one of three ways). In other cases, the command is a toggle

Objective 9 - 1

<!-- p. 50 -->

Introductory User’s Guide

that, when enabled, will affect subsequent actions. Note that the type of
commands and options available depends on the type of object being ed-
ited.

TABLE 9-1 Edit Commands in SAFE

Immediate/

Command Action Form Used/

Toggle

Edit menu > Undo and The Undo command or button deletes the Immediate
Redo last performed action. The Redo command or

button restores the last step that was un-9
done.

Edit menu > Cut, Copy Generally similar to the standard cut, copy and Immediate

and Paste paste Windows commands.

Edit menu > Delete The Delete command deletes the selected ob- Immediate

ject(s) and all of its assignments (loads, proper-

ties, supports and the like).

Edit menu > Edit Grid Edits the coordinate/grid system in either the X Define (X or Y)

or Y direction. Grid Form

Edit menu > Add Grid Inserts new grid lines parallel to either the X or Y Add Grid Lines

at Selected Points direction at the selected points. at Selected

Points Form

Edit menu > Move Moves point objects in the model. When a point Move Selected

object is moved, all line and area objects at- Points Form

tached to the point are reoriented or resized to

account for the movement. Move works only

with selected points; thus, to move a line or area

object using this command, you must select the

points that define the line or area object, not the

line or area object itself.

Edit menu > Replicate Copies and pastes duplicates of the selected line Replicate Form

or area objects to specified locations using linear

replication, radial replication, or replication about

a mirror plane. Note that this command differs

from the Copy command because it also copies

any assignments made to the line or area object.

9 - 2 Editing Tools

<!-- p. 51 -->

Chapter 9 - Editing Tools

TABLE 9-1 Edit Commands in SAFE

Immediate/

Command Action Form Used/

Toggle

Edit menu > Align Ver- Aligns selected points and the line and area ob- Align Selected

tical/Horizontal jects defined by selected points. A maximum Lines/Edges/

distance that the points can move is specified Points Form

and if the selected points are within that toler-

ance distance, they will align on a grid line or

with each other if a grid line is not within the tol-

erance distance. When a point object is re- 9
aligned, all line and area objects attached to the

point are reoriented or resized to account for the

movement. NOTE: This is a sophisticated and

complex command, and it is strongly suggested

that the user verify its behavior before using it on

a large model.

Edit menu > Convert Converts selected rectangular area objects into Immediate

Rect to Area polynomial area objects.

With a form displayed on-screen, press the F1 key on the keyboard to ac-
cess context-sensitive help about that form.

Editing Tools 9 - 3

<!-- p. 52 -->

SAFE™SAFE™ Chapter 10

10

Analyze the Structural Model

Objective

This chapter describes how to analyze the model.

Set the Analysis Options

Before running the analysis, set the analysis options using the Analyze
menu > Set Options command. The Analysis Options form shown in
Figure 10-1 will appear.

Use the Analysis Options form to specify the type of analysis to be per-
formed, as well as to define other parameters specific to the type of
analysis selected. During analysis, SAFE automatically meshes the
model, creating a set of lines parallel to the coordinate axes that define
the finite element model. Generation of the mesh is influenced by the lo-
cations of point and slab objects, openings, beams and their orientations,
loads, soil support, and gridlines. The user can influence the size of the

Objective 10 - 1

<!-- p. 53 -->

Introductory User’s Guide

mesh by setting the maximum mesh dimension using the Analyze menu
\> Set Options command.

Figure 10-1
Analysis Options
form

10

To view the element mesh generated by the program, click the Set Ob-
ject Options button . When the Set Objects form appears, check the
Show Mesh check box.

Run the Analysis

Run the analysis by clicking the Analyze menu > Run Analysis com-
mand or the Run Analysis button .

The program will display an "Analyzing, Please Wait" window. Data
will scroll in this window as the program runs the analysis. After the
analysis has been completed, it is possible to use the window to scroll
through the data before closing the window.

When the entire analysis process has been completed, the model auto-
matically displays a deformed shape view of the model, and the model is
locked. The model is locked when the Lock/Unlock Model button
appears depressed. Locking the model prevents any changes to the model
that would invalidate the analysis results.

Consult the SAFE Help topics for more information about analyzing
your model.

10 - 2 Run the Analysis

<!-- p. 54 -->

Chapter 10 - Locking and Unlocking the Model

Locking and Unlocking the Model 10

After an analysis has been performed, SAFE automatically locks the
model to prevent any changes that would invalidate the analysis results
and subsequent design results. The user also can lock the model at any
time to prevent changes, or unlock it to permit changes using the
Lock/Unlock button . SAFE will display a warning message that
analysis results will be deleted if a model is unlocked following an
analysis.

Locking and Unlocking the Model 10 - 3

<!-- p. 55 -->

SAFE™SAFE™ Chapter 11

11

Design the Structure

Objective

This chapter describes design using the SAFE design option.

Design Process

SAFE designs both concrete slabs and beams. Slabs are those area ob-
jects that have been assigned slab properties, and beams are line objects
with beam property assignments. Specific material properties and design
data are input using the Define menu > Slab Properties or Beam Prop-
erties commands, and design code preferences are selected using the
Options menu > Preferences command and the Design tab.

To perform the design, first run the analysis (described in the previous
chapter), then click the Design menu > Start Design command. The
type of design depends on the type of members used in the model (e.g., a
beam design will be performed only if line objects with beam property
assignments are included in the model).

Objective 11 - 1

<!-- p. 56 -->

Introductory User’s Guide

After the design is complete, the plan view display will update to show
the slab reinforcing required in the X-Strips (design strips in the X direc-
tion). Strips can be viewed using the View menu > Set X-Strip Layer or
Set Y-Strip Layer commands.

The other commands available on the Design menu are somewhat se-
quential. That is, some commands must be used before other commands
become available. This is intended to help the user step through the de-
sign process. Table 11-1 summarizes the commands used in the design
process. With a form displayed on-screen, press the F1 key on the key-
board to access context-sensitive help about that form.

TABLE 11-1 Design Commands
11 Command Action Form

Design menu > Initiates the design process. An analysis must Immediate, no

Start Design precede use of this command. form used

Design menu > Allows review of the default design load combina- Design Load

Select Design tions determined by the program, or designation Combinations

Combo of user-specified design load combinations. Fa- Selection Form

cilitates review or modification of load combina-

tions during design.

Design menu > Allows the required slab reinforcing to be dis- Slab Reinforcing

Display Slab played directly on the model as an area or number Form

Design Info of bars in the X or Y direction strips.

Design menu > Allows for the display on the model of the required Beam Reinforcing

Display Beam beam reinforcing (flexural or shear). Form

Design Info

Design menu > Allows for the display on the model of calculated No form; results

Display Punching punching shear ratios. are displayed

Shear Ratios onscreen.

Design menu > Allows the user to select the type of information to Design Tables

Show Design include in the design tables to be viewed on- Form

Tables screen, including design output and design forces.

Design menu > Displays the slab area, concrete volume, and de- SAFE – Approxi-

Show Total signed steel weight calculated by the program. mate Quantities

Quantities Form

11 - 2 Design Process

<!-- p. 57 -->

SAFE™SAFE™ Chapter 12

12
CSiDETAILER

Objective

This chapter describes how to use the CSiDETAILER program in con-
junction with SAFE to generate reinforcing detail drawings.

SAFE to CSiDETAILER

The CSiDETAILER program will detail both slabs and beams after an
analysis and design has been completed in SAFE. The program uses the
required reinforcing obtained from the SAFE design along with code
mandated minimums (as determined from the Detailing Options in
CSiDETAILER) to produce drawings and schedules of reinforcing lay-
outs. Within CSiDETAILER, the user has control over the drawing
setup, including the sheet size and scale, the units and how each view
should be displayed on the drawing.

To produce the reinforcing details (assuming that you have a licensed
copy of CSiDETAILER in addition to a copy of SAFE), first run the

Objective 12 - 1

<!-- p. 58 -->

Introductory User’s Guide

analysis followed by the design (described in Chapters 10 and 11, re-
spectively), then set the preferences using the appropriate commands on
the Detailing menu in SAFE. After the preferences have been set, click
the Detailing menu > Start Detailer command to launch CSiDE-
TAILER. The CSiDETAILER program will automatically generate all
possible drawings. Consult the CSiDETAILER manuals and on-line
Help for more information about using CSiDETAILER.

12

12 - 2 SAFE to CSiDETAILER

<!-- p. 59 -->

SAFE™SAFE™ Chapter 13

13
Obtain Basic Graphical Displays

Objective

This chapter describes how to display analysis results graphically.

Display Analysis Results

Analysis results can be displayed graphically after the analysis has been
run. To display results, click the Display menu and select the type of dis-
play desired. Table 13-1 identifies the display options.

TABLE 13-1 Display Menu Options

Command Action Form

Display menu > Show The Show Undeformed Shape command or No form; results
Undeformed Shape button plots the undeformed shape are displayed.

onscreen.

Objective 13 - 1

<!-- p. 60 -->

Introductory User’s Guide

TABLE 13-1 Display Menu Options

Command Action Form

Display menu > Show The Show Loads command or button dis- Show Loads Form
Loads plays loads assigned to point, line and area

objects.

Display menu > Show Provides the user with the opportunity to com- Input Tables Form

Input Tables plete an on-screen review of the input parame-

ters used in building the model.

Display menu > Show The Show Deformed Shape command or but- Deformed Shape
Deformed Shape ton plots a deformed shape on-screen Form

based on user-specified loads. This plot can be

animated for 3-D views.
13 Display menu > Show The Show Slab Forces command or button Slab Forces Form
Slab Forces displays slab forces on-screen based on

user-specified loads.

Display menu > Show The Show Beam Forces command or button Beam Forces
Beam Forces displays beam forces on-screen based on Form

user-specified loads.

Display menu > Show Displays moments or shears in the X direction Strip Forces Form

Strip Forces or Y direction strips based on user-specified

loads.

Display menu > Show Displays reaction forces (or soil pressures) on- Joint Forces Form

Reaction Forces screen based on user-specified loads.

Display menu > Show Allows the user to select and show on-screen Output Tables
Output Tables various tables of analysis results. Some of the Form

output data is located via I and J grids, which

may be displayed by checking the Show Mesh

box on the View menu > Set Object Options

command.

With a form displayed on-screen, press the F1 key on the keyboard to ac-
cess context-sensitive help about that form.

13 - 2 Display Analysis Results

<!-- p. 61 -->

SAFE™SAFE™ Chapter 14

14
Generate Analysis and Design Results

Objective

This chapter identifies the commands for generating analysis and design
results.

Output Options

Analysis and design results can be printed to a printer or a file using the
File menu commands. Table 14-1 identifies the print commands.

TABLE 14-1 File Menu Print Options

Command Action Form

File menu > Print Allows the user to specify page breaks and ti- Print Setup Form
Setup tles as well as the paper size and orientation of

the page.

Objective 14 - 1

<!-- p. 62 -->

Introductory User’s Guide

TABLE 14-1 File Menu Print Options

Command Action Form

File menu > Print Provides a snapshot of how the file will print in No forms; results

Preview for Graph- graphical format. are displayed

ics

File menu > Print Prints whatever graphics are displayed in the Immediate, no
Graphics active window to the printer that is currently form used

specified as active.

File menu > Print Prints tables of analysis input data to a printer Input Tables Form
Input Tables or to a text file.

File menu > Print Prints tables of analysis output data to a printer Output Tables

Output Tables or to a text file. Form
14 FileDesignmenuTables> Print Printsor to atablestext file.of design output data to a printer DesignFormTables

With a form displayed on-screen, press the F1 key on the keyboard to ac-
cess context-sensitive help about that form.

14 - 2 Output Options
