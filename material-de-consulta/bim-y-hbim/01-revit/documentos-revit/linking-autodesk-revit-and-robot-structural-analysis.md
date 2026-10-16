---
type: libro
title: "Linking Autodesk Revit Revit Structure and Robot Structural Analysis Professional - Final"
author: "fudalat"
categoria: "BIM Y HBIM"
paginas: 29
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/DOCUMENTOS REVIT/Linking Autodesk Revit and Robot Structural Analysis.pdf"
convertido: 2026-10-16
---

# Linking Autodesk Revit Revit Structure and Robot Structural Analysis Professional - Final

> Texto extraído de `BIM Y HBIM\01. Revit\DOCUMENTOS REVIT\Linking Autodesk Revit and Robot Structural Analysis.pdf` (29 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Autodesk® Revit®
Autodesk® Revit® Structure
Autodesk® Robot™ Structural Analysis Professional

Integrating Autodesk Revit,
Revit Structure, and Robot
Structural Analysis
Professional

This paper explores the interoperability between Autodesk®
Revit®, Autodesk® Revit® Structure, and Autodesk® Robot™
Structural Analysis Professional software—including
recommended workflows, analytical modeling best practices, and
the details of data exchange between the solutions.

Structural engineers typically start the design process by interpreting architectural
drawings, creating design documentation, and creating various analytical models. These
analytical models must be consistently coordinated with respect to general framing layout,
material and section properties, and loading. Once analysis and design is complete the
design documentation is modified to reflect the most current design. This workflow is
repeated for each iteration of the design process.

The link between Autodesk Revit 2015 or Autodesk Revit Structure 2015 software and
Autodesk Robot Structural Analysis Professional 2015 software helps make this workflow
smoother by facilitating the coordination of design documentation with structural analytical
design information.
Revit1 software supports the Building Information Modeling (BIM) process for structural
engineers by providing a physical model of the structure to use for documentation and an
associated analytical model, as well as other structural attributes and properties to use for
structural analysis and design. Robot Structural Analysis Professional supports BIM with
its advanced analysis and multimaterial design functionality. The bidirectional
interoperability of Revit and Robot Structural Analysis Professional software helps reduce
the time needed to create and update multiple analysis models and helps to avoid
potential errors resulting from manual coordination between analysis results and
construction documentation.

1 Autodesk Revit 2015 contains the functionality of Autodesk® Revit® Architecture 2015, Autodesk®
Revit® MEP 2015, and Autodesk Revit Structure 2015 software, and is available in the Autodesk®
Building Design Suite Premium and Ultimate editions. To limit product name repetition, the use of the
name “Revit” throughout the rest of this paper refers to both Autodesk Revit and Autodesk Revit
Structure software.

www.autodesk.com/revit and www.autodesk.com/robot

<!-- p. 2 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Contents
More streamlined information exchange........................................................................ 3
Design/analysis interoperability ..................................................................................... 5
Interoperability command in Revit .................................................................................. 7
Sending a model to Robot ............................................................................................ 7
Send options ............................................................................................................ 8

Updating a Revit model ................................................................................................ 9
Interoperability command in Robot Structural Analysis Professional ...................... 10
Sending a model to Revit ............................................................................................ 10
Send options .......................................................................................................... 11

Updating a Robot model ............................................................................................. 11
Best practices ................................................................................................................. 13
Analytical modeling ..................................................................................................... 13
Structural content........................................................................................................ 13
Automatic physical/analytical relations ....................................................................... 14
Alignment and constraints ...................................................................................... 14

Analytical model projections ................................................................................... 14

Bracing ................................................................................................................... 14

Sloped Framing ...................................................................................................... 15

Phases and design options .................................................................................... 16

Analytical model adjustment ....................................................................................... 17
Analytical alignment ............................................................................................... 17

Manual adjustment of the analytical model............................................................. 17

Analytical model consistency checks .......................................................................... 20
Warnings ................................................................................................................ 20

Analytical check tools ............................................................................................. 20

Analytical attributes ..................................................................................................... 21
Member end releases ............................................................................................. 21

Best practices for updates and collaboration .............................................................. 22
Scope of transferred model elements .......................................................................... 23
Supports ..................................................................................................................... 23
Linear elements .......................................................................................................... 24
Loads .......................................................................................................................... 27
Concrete reinforcement .............................................................................................. 27
Other elements and element parameters ................................................................... 28
Summary ......................................................................................................................... 29

2

<!-- p. 3 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

More streamlined information
exchange

Some structural engineering firms begin the design process by creating documentation.
Others start by creating an analytical model. The link between Autodesk Revit software
products and Robot Structural Analysis Professional supports both of these workflows.
However, there are some advantages to starting the design process with a model in Revit
software instead of with Robot Structural Analysis Professional.

For instance, in addition to creating construction documents, many firms use the Revit
Structure model to help coordinate their designs with other disciplines. Therefore,
structural drafters can begin modeling, documenting using company standards, and
coordinating the structure. By starting the design in Revit, you create both a physical
model, for coordination and early documentation, and a simplified analytical model. Each
model is independently editable, but also maintains a consistent relationship to the other.

Figure 1: The bidirectional link
between Revit software and
Robot Structural Analysis
Professional enables firms to
add analysis-related
information to the Revit model,
use that model directly for
analysis in Robot Structural
Analysis Professional, and then
update the Revit model based
on the analysis results.

Moreover, Revit software capabilities enable structural designers to enrich the physical
model with information such as physical properties, proposed analytical model definition,
and expected loads conditions. This makes the physical model more complete and also
enhances collaboration with structural engineers.

For example, in a traditional workflow the CAD technician or designer creates a physical
model defining expected relations with its analytical representation, which is a
simplification of more detailed, real geometry. The CAD technician must then wait until the
engineer has completed the structural analysis and design before starting coordination
and documentation tasks.

The bidirectional link between Revit and Robot helps make the exchange of structural
analytical information much smoother. The link enables firms to add analysis-related
information to the Revit model, use that model (and information) directly for analysis in
Robot Structural Analysis Professional, and then update the Revit model based on the
analysis results. This iterative data exchange respects and preserves the information
defined in both software solutions.

3

<!-- p. 4 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

In Revit software, the physical model and the associated analytical model (which contains
the boundary conditions and load definitions used for analysis) are created concurrently.
Thus, the structural designer creates both the physical and analytical model using Revit
and then sends the analytical model to a structural engineer who uses Robot for structural
analysis.

Once the model has been linked to Robot Structural Analysis Professional, the engineer
begins the analysis and code design process. After an initial analysis, the engineer may
want to make some changes to the analytical model based on calculated results.

In some cases the engineer may also decide to make changes to the model prior to initial
analysis based on experience and knowledge. Additionally, the engineer may define more
load cases and loads using Robot.

After the analysis has been performed, the engineer explores the results and starts to
design the structural elements. Using Robot Structural Analysis Professional, the engineer
can also run code checking to design concrete, steel, and timber elements based on a
wide variety of national and international codes.

When the engineer has completed design changes and the analysis, the information is
transferred back to Revit, enabling the designer to review the design changes from the
analysis and code-checking phase and update the physical model accordingly.

Below is a recommended workflow for concurrent structural documentation, design, and
analysis:

• The CAD technician creates a structural model based on an existing
architectural model or existing architectural 2D layouts.
• The structural designer adjusts material and profile definitions, and adjusts the
analytical model proposed by Revit. Autodesk recommends the use of the
Content Generator Extension2 to help create appropriate material definitions
and sections based on regional catalogues that contain necessary structural
properties for further analysis and code checking.
• The designer creates loads and load combinations that can be used for
analysis in Robot, as well as preliminary or load takedown analysis available
with Revit Extensions.3 This information can also be used within design and
code checking applications such as the Composite Design Extension for
composite steel framing.
• The designer then sends the Revit model to Robot Structural Analysis
Professional. In this fashion, the engineer exploits the interoperability between
the software solutions—using the Revit analytical model and the Robot
software to perform structural analyses.
• Based on analysis outcomes, the engineer may make decisions that need
coordination with the designer (and perhaps ultimately the architect as well).
Within Robot, the engineer updates the analytical model with recommended
changes and alerts the designer.

2 The Content Generator Extension is part of the Autodesk® Revit® Extensions for Autodesk Revit
2015 software products, which deliver a full range of benefits to enhance Revit software. Revit
Extensions include tools for structural analysis, modeling, concrete reinforcement, interoperability,
and construction documentation. All Revit Extensions are available through the Autodesk®
Subscription Program.
3 All Revit Extensions are available through the Autodesk Subscription Program for Autodesk Revit
2015 software products.

4

<!-- p. 5 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

• The designer uses Revit to review the engineer’s recommended changes to the
analytical model. In collaboration with the engineer, the designer accepts or
rejects the proposed changes to the analytical model and Revit automatically
adjusts the physical model accordingly.
• This iterative collaboration between the designer and engineer repeats as
necessary.
• The designer may also adjust section sizes and properties, based on
information received from Robot Structural Analysis Professional or other code-
checking applications linked with Revit.

Design/analysis interoperability

The link between Revit and Robot enables engineers to send selected portions of a Revit
model to Robot, and vice versa. This flexibility enables the engineer to work with the
structure in separate analysis models.

Figure 2: Filtered views in
Gravity Autodesk Revit and Revit Structure
software are used to create
separate analysis models in Robot
Structural Analysis Professional.

Lateral

Revit Revit Robot Structural Analysis
Complete Model Selection Professional Models

For example, the engineer can create separate analysis and design for:

• Gravity and lateral systems
• Structural steel and reinforced concrete systems
• Logical separations in structure
• Evaluations of specific elements
• Phased construction and design options

Modeling a structure in Revit helps the user visualize the relationship between a real
physical structure and its analytical simplification, which is needed for analysis.
Furthermore, this physical structural model is the basis for documentation and code
checking (which focuses on physical elements and attributes such as section sizes,
materials, rebar, and so on).

5

<!-- p. 6 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

However, certain elements or parameters may be easier to model and adjust in Robot,
such as member end releases, loads, and boundary conditions. As an advanced analysis
software solution, Robot Structural Analysis Professional has more robust capabilities in
this area. For example, the creation of load combinations is more automated in Robot,
which can auto-generate numerous combinations at once. Additionally, the software has
more options for creating loads. Then again, there are instances where it may be
necessary or preferable to model loads using Revit, primarily for use in other Revit
Extensions or other applications for analysis and code checking.

A suggested approach for analysis and design is as follows:

• Model these elements in Revit software:
o Grids and levels
o Structural columns and framing
o Structural floors and foundations
o Structural materials definition
o Preliminary design load cases and loads
o Boundary conditions and member end releases
• Perform preliminary analysis and design with available Revit Extensions
• Send to Robot Structural Analysis Professional
• Enrich the analytical model in Robot by adding:
o Final design load cases, loads, and load combinations
o Advanced boundary conditions and member end releases
o Meshing and advanced analysis parameters
• Perform final analysis and design in Robot
• Update these Revit elements from Robot:
o Spatial analytical model
o Member sizes
o Designed concrete reinforcement
• Use Revit to check and approve the proposed changes by:
o Adjusting the location of physical elements
o Helping to coordinate the physical changes with other disciplines
• Repeat for each design iteration as needed

There is no correct or incorrect workflow for analysis interoperability. The optimal workflow
for one firm or a particular project may be different for another. Factors to consider
include:

• Division of modeling, design, analysis, and documentation tasks by CAD
technicians, designers, and engineers
• Work-sharing and collaboration standards
• Number and types of licenses for Revit software and Robot Structural Analysis
Professional software

6

<!-- p. 7 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

• Use of multiple analysis tools on one project
• Use of multiple code-checking tools

Interoperability command in Revit

When Robot Structural Analysis Professional or Structural Analysis Toolkit for Autodesk
Revit is installed on the same computer as Revit software, new commands are added to
the Revit user interface that provide a link between the two products. This link enables the
Revit user to send a Revit model to Robot for analysis and design, and to update the Revit
model based on the results of the analyses. All analyses and design is performed in
Robot, except for composite steel framing. The Composite Design feature for Autodesk
Revit Extension is used to analyze and design composite steel framing directly in Revit.

Figure 3: The Revit user interface
provides a link between the two
software applications.

This link also enables the Revit user to send the Revit model to an intermediate file
(.smxx), and update the Revit model from an intermediate file (.smxx). Note that in this
type of data transfer, some options like “Use plan views as backgrounds,” “Reinforcement
projects,” and “Steel connections” are not available. Also, the results cannot be
transferred using the .smxx file. This option can be useful when Robot and Revit are not
installed on the same machine.

Sending a model to Robot
After selecting the Robot Structural Analysis link, the user has the option to send a model
to—or update a model from—Robot Structural Analysis Professional.

Figure 4: This dialog box enables
users to send or update a Revit
model to or from Robot Structural
Analysis Professional.

The software can also transfer static analysis results calculated in Robot Structural
Analysis Professional to Revit. These results can then be used in the Revit
documentation.

7

<!-- p. 8 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

If there are two users (for example, a designer using Revit on one computer and an
engineer using Robot on another computer), the Revit user should select the Send to the
intermediate file (.smxx) option. In this case, the Revit model data is transferred to the
Robot user via an .smxx4 file, enabling a designer to continue to work in Revit while an
engineer uses the .smxx file in Robot on a separate computer.

If both applications are installed on the same computer, the Direct integration option
should be selected. The model is automatically transferred from Revit to Robot and the
Robot software is launched. This workflow may be beneficial for a quick analysis check or
small design update.

Send options
There are a few options to consider when sending a model to Robot. The designer can
send the entire model or a specific portion of the model. Sending only a selection of the
model is useful when performing analysis and design for certain elements or structural
systems, or when making small modifications in layout or design.

Self-weight of the structure can be ignored or placed on the Load Case of the engineer’s
choosing. The Load Cases must be created in Revit prior to executing the command.

Figure 5: Dialog box showing
options for sending a Revit model
to Robot Structural Analysis
Professional.

By selecting the “Use plan views as backgrounds” option, existing views with structural
content are sent to Robot as background objects.

By selecting the “Reinforcement projects” option, modeled concrete reinforcing bars are
sent to Robot.

By selecting the “Steel connections” option, modeled steel connections are sent to Robot.

4 SMXX is the binary file format that contains information about the structural model.

8

<!-- p. 9 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Updating a Revit model

The options for updating a Revit model from Robot Structural Analysis Professional are
similar to the options for sending a model. Note that in addition to updating the entire
model, selected elements in Revit software can be updated.

If the “Select modified elements in Revit Structure” option is checked, Revit will highlight
all the new or revised elements that were updated from Robot, enabling the user to more
easily review the model.

Within the analytical model, the software can:

• Update section definitions

• Update analytical line locations

• Add or remove structural elements

Figure 6: Options for
updating a Revit model from
Robot Structural Analysis
Professional.

9

<!-- p. 10 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Interoperability command in Robot
Structural Analysis Professional

A new command has been added to Robot that provides a link between Robot and Revit
software. This link enables the Robot user to update or create a Robot model from a Revit
model for analysis and design and then send the Robot model to Revit, making changes
based on the results of the analyses.

Figure 7: The Robot Structural
Analysis Professional user interface
provides a link between the two
software applications.

This link also enables the Robot user to send the Robot model to an intermediate file
(.smxx), and update the Robot Structural Analysis Professional model from an
intermediate file (.smxx). Note that in this type of data transfer some options like “Use plan
views as backgrounds,” “Reinforcement projects,” and “Steel connections” are not
available. Also, the results cannot be transferred using the .smxx file. This option can be
useful when Robot and Revit are not installed on the same machine.

Sending a model to Revit
After selecting the Add-Ins Integration Autodesk Revit Structure option, the user
can send a model to—or update a model from—Revit software.

Figure 8: This dialog box enables
users to send or update a Revit
model to or from Robot Structural
Analysis Professional.

The software can also transfer static analysis results calculated in Robot Structural
Analysis Professional to Revit. These results can then be used in the Revit
documentation.

10

<!-- p. 11 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

If there are two users (for example, a designer using Revit on one computer and an
engineer using Robot on another computer), the Robot user should select the “Send to
the intermediate file (.smxx)” option. In this case, the Robot model data is transferred to
the Revit user via an .smxx5 file, enabling an engineer to continue to work in Robot
Structural Analysis Professional while a designer uses the .smxx file in Revit on a
separate computer.

If both applications are installed on the same computer, the ”Direct integration” option
should be selected. The model is automatically transferred from Robot to Revit (note that
Revit must be launched).

Send options
There are a few options to consider when sending a model to Revit. The engineer can
send the entire model or select a specific portion of the model to be sent. Sending only a
selection of the model is useful when performing analysis and design for certain elements
or structural systems, or when making small modifications in layout or design.

Figure 9: Dialog box showing
options for sending a Robot
Structural Analysis Professional
model to Revit.

By selecting the “Reinforcement projects” option, modeled concrete reinforcing bars are
sent to Revit.

By selecting the “Steel connections” option, modeled steel connections are sent to Revit.

Updating a Robot model
The options for updating a Robot model from Revit are similar to the options for sending a
model. Note that in addition to updating the entire model, selected elements in Robot can
be updated.

Self-weight of the structure can be ignored or placed on the Load Case of the engineer’s
choosing. The Load Cases must be created in Revit software prior to executing the
command.

5 The .smxx binary file format contains the information about the structural model.

11

<!-- p. 12 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Figure 10: Options for
updating a Robot Structural
Analysis Professional model
from Revit.

By selecting the “Use plan views as backgrounds” option, existing views with structural
content are sent to Robot as background objects.

By selecting the “Reinforcement projects” option, modeled concrete reinforcing bars are
sent to Robot.

By selecting the “Steel connections” option, modeled steel connections are sent to Robot.

12

<!-- p. 13 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Best practices

The following recommendations are provided to facilitate the transfer of elements between
Revit and Robot.

Analytical modeling
There are two ways a Revit user creates an analytical model:

\1. As the user defines the physical model, the software will automatically create an
analytical model and keep that analytical model consistent with the physical
model.

\2. The user can also adjust this analytical model manually by manipulating
analytical nodes positions.

The software’s automatic relation settings should reflect how the user intends to manage
the relationship between the physical and analytical models over time as changes occur.

The automatic relation settings are predefined rules that the software uses to
automatically create a more accurate, analytical simplification of the physical model. But
that analytical simplification is subjective and engineers may want an analysis model
defined in a way that suits their individual expectations and requirements. Therefore, the
user can manually adjust the analytical model. When editing the analytical model, a
customized relation between the physical and analytical model is created, keeping the
analytical and physical model synchronized as changes occur.

Autodesk recommends that the Revit user take advantage of the automatic relation
settings when first creating a physical model and adjust them later as needed.

Structural content
The Content Generator Extension (part of Revit Extensions) should be used to create
families for structural framings and columns. The sections created with the Content
Generator are based on widely used steel profile data—the same data used by Robot. In
addition, the newly created content mimics the appropriate physical characteristics, which
is necessary when using the Revit physical model in code-checking applications.

Figure 11: The Content
Generator Extension is used
to create families for
structural framings and
columns.

13

<!-- p. 14 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Automatic physical/analytical relations

Alignment and constraints
Creation of duplicate nodes at intersections is a common issue engineers encounter when
linking a Revit model to analysis software. This often occurs when framing elements are
not properly joined. One way to help reduce duplicate nodes is to align or constrain
structural elements to grids, levels, and named reference planes in Revit software. This is
particularly relevant for braced frames and where structural elements are offset from the
primary grids.

Figure 12: Explicitly constraining a
beam to a grid using the Align tool.

Analytical model projections
By default, Revit assigns Auto-detect parameters for the horizontal and vertical
projections. When using Auto-detect, the software will try to determine the best logical
location for the analytical model line(s). In most cases, the software correctly determines
the best analytical line location. Therefore, using the default Auto-detect is suggested.
Override this parameter only if needed.

Figure 13: The effect of the
analytical project parameter
on an analytical model.

Interior Face Auto-detect or Center Line

Bracing
The use of the guidelines mentioned in the sections above can help prevent the creation
of duplicate nodes at bracing intersections. In particular, use grids, levels, and named
reference planes for braced frames offset from the primary grid lines.

When defining the brace, it is recommended that the user attach the brace start and end
nodes to beams instead of columns. Notice the parameter distinctions in the Element
Properties window. This affects where the cutback distance is located (cut by column or
by beam) and the behavior of how the bracing node moves when other analytical
elements are adjusted.

14

<!-- p. 15 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Figure 14: The difference in
the element property
parameters for braces based
on attachment type.

Figure 15: Notice the location of
element end points and physical
member setbacks for each
attachment at the lower level.

Carefully inspect bracing intersections at sloped roofs or floors by zooming in and
enabling Thin Lines to check that the brace node intersects the other elements. If it does
not, use the Analytical Adjust tool to manually adjust the location to the beam-end node,
using Tab to iterate through each element.

Sloped Framing
The link between Revit and Robot supports the exchange of sloped framing. Multiple
levels (for example, levels at low and high sides) may be used in Revit for construction
documents, but they are not needed to link with Robot. Instead, a single level or even no
level and element offsets are sufficient for interoperability with Robot.

Revit software Robot Structural Analysis Professional

Figure 16: Sloped framing in Revit software and Robot Structural Analysis Professional.

15

<!-- p. 16 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Coplanar framing of a sloped floor having the projection parameter(s) set to Auto-detect
will automatically align the analytical framing line to the analytical plane of the floor where
the floor is set to Top of Slab or Bottom of Slab.

Bottom of
Slab

Center of
Slab

Figure 17: The relationship
Top of Slab
of beam (shown in orange)
and slab (shown in brown)
analytical lines for various
projections of the slab.

Phases and design options
The link between Revit software and Robot Structural Analysis Professional does not
support the Revit Phase parameters. Therefore it is recommended that users send
selected elements filtered by Phase to Robot, resulting in multiple analytical models.
Sending the entire model will send all elements—regardless of Phase, such as created or
demolished.

A similar approach is recommended for Design Options.

Figure 18: Multiple analytical
models created from Phase-
Existing filtered view selections.

Phase 1

Phase 2

Robot Structural Revit software: Revit software:
Analysis Professional: complete model Phased views
analysis models

16

<!-- p. 17 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Analytical model adjustment
Structural engineers often create analytical models that may seem illogical or hard to
describe by an algorithm when compared to the physical model, as the engineer’s
decisions are often subjective and based on experience. As such, Revit software includes
functionality to more easily create and edit the analytical model. The following features
help users create an analytical representation of a physical model according to their
individual expectations:

• Analytical alignment

o Auto-detect adjustment

o Projection adjustment

• Manual adjustment of the analytical model

Analytical alignment
Analytical alignment encompasses a number of different options for positioning the
analytical model in relationship to itself and other analytical elements. There are two
methods of analytical alignment: auto-detection and projection. Analytical alignment is
determined by structural element instance properties.

Automatic adjustment is performed on a structural element in relation to a neighboring
structural element. Revit can automatically adjust the analytical model for beams, braces,
structural columns, structural walls, structural floors, and foundation slabs to align these
elements more accurately. This behavior is based on the instance parameters of the
elements and tolerance settings.

For auto-detection to occur, the analytical Adjustment Methods instance properties must
be set to Auto-detect for an element and its individual ends. This is the default justification
method for all analytical structural elements. Automatic adjustment is then performed, as
long as the analytical model of the adjacent element is within tolerance.

Each structural member has optional locations for its analytical projection plane. These
projection plane locations are relative either to the levels of the structure or to the
structural element itself. Each projection plane for each element has a default location, but
the user may change the location by adjusting the Vertical parameter on the Analytical
Model section of the Properties palette.

Manual adjustment of the analytical model
Revit software includes a special analytical edit mode that enables direct manipulation of
the analytical model, providing greater control.

In this edit mode, the user can directly modify the analytical model elements of beams,
braces, columns, floors, and walls. To activate the analytical edit mode, select the
Analytical Adjust icon on the Analyze tab. Additional access is provided on the contextual
tabs of all the analytical elements.

When the edit mode is activated, node elements appear at the ends of all analytical
beams, braces, and columns. In addition, analytical floors, foundation slabs, and walls
have corner analytical nodes. All non-analytical elements are set to half-tone and are not
selectable.

17

<!-- p. 18 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

When the linear analytical element is selected, the widgets display at the ends of the
element with its local coordinate system. You can toggle between the global and the local
coordinate system simply by hitting the spacebar.

Figure 19: Revit software
includes a special analytical
edit mode that enables direct
manipulation of the analytical
model.

When floors or foundation slabs in the analytical model are selected, the user sees
controls posted at all corners and edges, which enable direct manipulation of the
analytical model. You may select individual edges by using the Tab key while hovering
over an edge. Pressing the spacebar will cycle through edge local and global drag widget
arrow orientations.

You can also select the analytical node itself, resulting in the display of a widget for the
node. Moving the node will move the ends of all elements that join the node. To remove a
single element from the analytical node, first select the element and then use the widgets
that appear at its end to move only the end of that element. The same behavior works for
multiselection. If you want to remove two elements from an analytical node, select each
element and move the widget. Only those elements will be moved and be disconnected
from the analytical node.
Figure 20: To simplify theThe presence of openings in a surface analytical
analytical model, Revit usersmodel can make it overly complicated for
can identify openings in floors,analysis. Engineers may want to simplify the
foundation slabs, and wallsanalytical model by specifying which openings
that will be ignored duringshould not be included in the model. The
analysis.openings editor enables you to identify openings
that will be ignored in analytical floors,
foundation slabs, and walls.

In the analytical edit mode, selecting the Openings button launches the openings editor. In
this editor, each opening in an analytical model has a checkbox. To ignore the opening
during analysis, simply uncheck the checkbox and the opening will be removed from the
analytical model, yet remain in the physical model.

18

<!-- p. 19 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

You can also adjust analytical walls in relation to nodes of analytical floors and analytical
foundation slabs. The Analytical Wall Adjustment tool enables the selection of nodes that
are associated to analytical floors or analytical foundation slabs as the target position of
the wall adjustment.

An analytical link is an element connecting two separate analytical nodes. Analytical links
may be used in situations such as connecting offset columns or beams, or modeling rigid
floor diaphragms. Manually creating analytical links helps to simplify and accelerate
structural analysis of the model.

Thanks to ability to create filters based on the Connection Status parameter, you have
greater control over the analytical model. For example, analytical nodes with
“unconnected” status can be displayed in a different color than “connected” nodes.

You can use Analytical Model Categories visibility settings to display local coordinate
system (LCS) widgets along structural analytical elements in a view.

Figure 21: Local Coordinate
System widgets along
structural analytical elements
in a view.

Hosted loads and boundary conditions can be oriented to the host LCS. They also respect
host LCS direction and rotate when the LCS is changed.

19

<!-- p. 20 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Analytical model consistency checks

Warnings
Be sure to inspect and correct all elements that trigger a warning, such as “Beam or Brace
is slightly off axis and may cause inaccuracies.” Typically, the corrective action is to align
and constrain the element to a grid or reference plane.

Figure 22: Review warnings and make appropriate corrections.

Analytical check tools
Before sending a Revit model to Robot Structural Analysis Professional, it is important to
check member supports and perform analytical/physical model consistency checks. These
checks will also help prevent the creation of duplicate nodes and the generation of other
errors or warnings when linking to Robot.

Figure 23: Revit analytical model tools.

Tools for analytical consistency provide warnings in the early design stages about the
stability of the structure. This gives a user greater insight into a design prior to submitting
it for complete analysis.

During a member support check, the software will inspect each structural element to help
see if it is correctly supported. For example, a typical beam should be supported by
another beam, a column, or a wall. For each element that is identified as not supported,
the software will generate a warning message. This member support check will also help
identify circular support conditions.

20

<!-- p. 21 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

An analytical/physical model consistency check inspects the relationship between an
element’s physical location and its analytical line. Tolerances can be configured in the
Structural Settings dialog box. For example, a warning will be generated if the analytical
model line is more than 12 inches from the physical model per the settings shown in the
figure below.

Figure 24: Analytical
model settings in Revit
software.

This analytical/ physical model consistency check is particularly important for elements
that have overridden horizontal or vertical projections. During the design process, an
element may be significantly moved or adjusted. If the overridden Projection parameter is
not updated, the analytical model will be significantly different from the physical model.

Both of these checks can be performed manually or automatically. Automatic checking is
not recommended during the initial creation of a Revit model or during significant revision
to a structure. Use automatic checking once the design process has stabilized and only
minor changes occur.

Analytical attributes

Member end releases
Member end releases may be adjusted in both Revit and Robot. It is recommended that
those adjustments be made in Revit and that the adjustments should reflect the structure’s
expected behavior. Those adjustments can also be made in Robot if a more robust toolset
and settings are needed.

By default, Revit creates pinned connections between member ends. Sending a model
created in this fashion to Robot will invariably reveal numerous instabilities and result in

21

<!-- p. 22 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

calculation errors. Therefore, when the model is initially sent to Robot, make all
adjustments to member end releases before running calculations in Robot. All the end
release adjustments will be transferred back to Revit during the next update of the Revit
model from Robot.

Best practices for updates and
collaboration
The Revit structural model combines a physical representation of the structure with an
analytical representation. The bidirectional link between Revit and Robot enables this
common model to be used for structural analysis and design, drawing production, and
project coordination.

During the design process, the engineer uses the Revit model in Robot for analysis and
design. In parallel, the designer uses Revit to review, accept, or reject the engineer’s
proposals represented in the analytical model—or even suggest another solution based
on the engineer’s suggestions.

All changes made by the engineer to cross-sections and materials using Robot can be
viewed in the physical model as well by the designer using Revit.

A diverse range of results and structural parameters—including reinforcement for concrete
structural element—are transferred from Robot to Revit. This information provides the
designer with valuable design intent regarding the reinforcement of the concrete elements.

Since the structural design process is iterative, there may be a need to send the structural
model back to Robot for further analyses after making design changes. When the
designer transfers the Revit model back to Robot, all changes made in Robot are
maintained in Revit and analysis-centric information such as meshing parameters,
additional loads, and so forth are preserved. This helps support the integration and
preservation of data between Revit and Robot throughout the iterative design process and
also helps to enhance collaboration.

Note that after the initial transfer (either way—from Revit to Robot or vice versa) both
models are equally important for subsequent data transfers.

For example, if a designer sends a Revit model to Robot, a Robot model based on the
Revit model is created. Then the user can work on both models and synchronize changes
(by transferring data between products).

Not all data pieces entered in one product (Revit or Robot) are synchronized with the
other product and they persist in the native model only. Discarding one of these models
and recreating it from scratch based on another model may result in the loss of data.

22

<!-- p. 23 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Scope of transferred model elements
The following sections describe how model elements in Revit and Robot are transferred
between the applications. The tables use these symbols to describe the transfer:

\< > elements are transferred in both directions
\> or \< elements are transferred in that direction only
NA elements are not transferred
P elements are transferred one way with data preserved but not accessible

Any limitations related to the transfer of an element are noted as well.

Supports
Isolated foundations and point boundary conditions modeled in Revit software are
transferred to Robot as nodal supports. The relationship between nodal supports in Robot
created from isolated foundations in Revit is preserved on subsequent exchanges
between the software applications. However, nodal supports initially modeled in Robot are
transferred to Revit as point boundary conditions regardless of their release settings or
location (for example, base of column). Nodal supports created from isolated foundations
in Revit are initially transferred to Robot as fully fixed, thus the engineer may need to
adjust the nodal support releases in Robot for more accurate analysis.

Figure 25: Table of Nodal Elements
Revit software Robot Structural Analysis Professional

Isolated Foundation > Nodal Support

Point Boundary Condition \<> Nodal Support

When sending selected portions of a model (for instance, the top level of a building), new
boundary conditions will need to be defined in Robot. When updating the selected portion,
consider deselecting the new Robot nodal supports prior to updating the Revit model.
Otherwise, the nodal supports will be transferred to Revit software. These same practices
generally apply when linking a Revit model with other structural analysis software.

The inactive status of nodes in Robot is transferred to/from and preserved in the Revit
model; however, this information is not visible or readily accessible to the user.

23

<!-- p. 24 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Linear elements
Structural columns, framing elements, and braces modeled in Revit software are
transferred to Robot as bar elements—Columns, Beams, and Simple Bars, respectively.
Revit parameters such as Analyze As (for instance, lateral, gravity) and Framing Type
(girder, joist) have no bearing on the Robot element.

Revit elements such as structural columns spanning multiple levels are transferred intact
to Robot as physical members. During analysis these physical members are split into
finite elements at intersecting framing nodes.

Wall foundations and line boundary conditions modeled in Revit are transferred to Robot
as linear supports. The mode of transfer between Revit and Robot is the same as that of
nodal supports.

Curved beams modeled in Revit are transferred to Robot as discretized linear beams. By
default, Robot will provide a fine discretization unless the discretization parameters
(approximate curve) are defined for the element in Revit software. When updating the
Revit model from Robot, Robot will preserve the discretized beam segment information in
Revit as new hidden data rather than creating a new—or updating an existing—single
curved beam.

Beam systems and trusses are container objects in Revit software. The individual framing
elements contained in beam systems and trusses are transferred to Robot as beams or
bars while the beam systems and trusses container objects are not. The individual framing
members hosted by beam system and trusses are editable in Robot and updated
accordingly in Revit. However, it is recommended that any modification of the member
layout be performed in Revit instead of Robot. Also, note that the beam system tag will not
update since this is a function of the Beam Type parameter of the beam system in Revit
software.

Figure 26: Table of Bar and Linear Elements
Revit software Robot Structural Analysis Professional

Line Boundary Condition > Linear Support

Wall Foundation > Linear Support

Structural Column \<> Column

Beam \<> Beam

Brace \<> Bar

Curved Beam P> Discretized Beams

Beam System NA

Truss NA

24

<!-- p. 25 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Several of the Element parameters in Revit are transferred to and from Robot. Other
Robot design parameters, such as slenderness and buckling coefficients, are preserved in
the Robot model and are neither visible nor accessible to the Revit user.

Figure 27: Table of Bar and Linear Element Parameters

Revit software Robot Structural Analysis Professional

Analytical Link > Rigid Link

Cross-Section Rotation \<> Gamma Angle

P Cable

P Elastic Ground

P Geometric Imperfection

P Non-linear Hinge

End Release \<> End Release

P Member Type

P Inactive Status

P Shear force respect in deformation

P Tension / Compression Member

P Axial Forces Only

Planar elements
Area boundary conditions modeled in Revit are transferred to Robot as planar supports.
Both pinned and user-defined supports are transferred. Planar supports in Robot are not
transferred to or preserved in Revit.

Structural floors and structural walls modeled in Revit are transferred to Robot as floor
and wall panel elements, respectively, which can be meshed into finite elements for
analysis and design. Roofs modeled in Revit software are considered nonstructural and
are not transferred to Robot. If steel roof decking is needed in Robot for analysis and
design, it should be modeled in Revit as a structural floor.

25

<!-- p. 26 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Foundation slabs are transferred to Robot as floors and returned to Revit software as a
structural floor rather than a foundation slab. Concrete floors in Robot have the same
cross-sectional and material properties as those in Revit. Floors with corrugated steel
decking are transferred to Robot with transformed section and material properties.

Curved structural walls modeled in Revit are transferred to Robot as curved walls. Similar
to curved beams, curved walls in Robot are transferred to Revit and preserved there as
hidden data.

Figure 28: Table of Planar Elements

Revit software Robot Structural Analysis Professional

Area Boundary Condition > Planar Support

Foundation Slab > Floor

Structural Floor \<> Floor

Structural Wall \<> Wall

Curved Structural Wall P> Wall

Wall Opening & Window P> Opening

Door P> Opening

Vertical or Shaft Opening P> Opening

Slab Edge NA

Wall, vertical, and shaft openings, windows, and openings created by Editing Profile
modeled in Revit are transferred to Robot as openings. The perimeter shape of a floor,
wall, and slab, including arcs, are transferred as the contour shape of the panel in Robot.
Doors modeled in Revit are transferred to Robot as part of the parameter panel definition
rather than openings. No relationship is maintained between the Revit openings and the
Robot openings. Therefore, any new openings created in Robot (or modifications made to
existing openings) are not updated in Revit software.

Finite element auto-meshing of the transferred floor and wall panels is not done
automatically during the transfer, and must be completed by the engineer in Robot. The
auto-meshing and other planar parameters are preserved in Robot during subsequent
transfers. However, the auto-mesh should be reviewed after significant revision to the
floor layout.

26

<!-- p. 27 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Figure 29: Table of Planar Element Parameters

Revit software Robot Structural Analysis Professional

P Load Distribution

P Reinforcement Design Parameters

P Calculation Model

P Meshing Parameters

NA Emitters

Loads
Loads, load natures, load cases, and load combinations are transferred between Revit
and. Load elements created in Revit and transferred to Robot are editable. However,
changes made in Robot are not propagated back to Revit software. Loads created in
Robot are transferred to and preserved in the Revit model; however, they are hidden and
are not accessible to the Revit user.

Figure 30: Table of Load Elements
Revit software Robot Structural Analysis Professional

Load Nature \<> Load Nature

Load Case \<> Load Case

Load Combination \<> Load Combination

(Hosted) Point Load \<> Nodal Load

(Hosted) Line Load \<> Linear Load

(Hosted) Area Load \<> Planar Load

Concrete reinforcement
Structural rebar modeled in Revit software is transferred to Robot only for structural
columns, beams, and spread footings. Area and path reinforcement and structural rebar
modeled in other elements or modeled manually in Revit software are not transferred to
Robot. Rebar designed in Robot for columns, beams, and spread footings are transferred
to Revit.

Reinforcement patterns created with the use of Revit Extensions (reinforcement of
columns, reinforcement of beams, and reinforcement of spread footings) are transferred to
Robot based on the parametric definition of patterns. Therefore, the use of these Revit
Extensions is recommended for reinforcement definition and Revit can be used to create
rebar using direct manipulation rules if needed.

27

<!-- p. 28 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Figure 31: Table of Rebar Elements
Revit software Robot Structural Analysis Professional

Area Reinforcement NA

Path Reinforcement NA

Structural Rebar \<> Rebar

Revit Extensions Patterns \< Revit Extensions Patterns

Revit Extensions Required Reinforcement \< Required Reinforcement

Other elements and element parameters
Materials, grids, and levels modeled in Revit are created as materials, structural axes, and
stories in Robot. The bidirectional transfer of these elements is limited. Therefore, it is
recommended that the user create and adjust these elements in Revit software. Many of
the other project wide and structural analysis parameters in Robot are sent to and
preserved in Revit software.

Figure 32: Table of Other Elements and Element Parameters
Revit software Robot Structural Analysis Professional

Material > Material

Grid > Structural Axis

Level \<> Story

P Global Mesh Parameters

P Active Section Databases

P Units

P Analysis Parameters

P Model Generation Parameters

28

<!-- p. 29 -->

INTEGRATING REVIT AND ROBOT STRUCTURAL ANALYSIS PROFESSIONAL

Summary

The integration between Revit software and Robot Structural Analysis Professional
facilitates the coordination of design information and construction documentation. The
integration supports multiple workflows stemming from choices regarding initial modeling
software and the use of multiple analytical models to split the workload. Additionally, Revit
offers many tools and modeling practices to prepare a model for a smoother
interoperability with Robot Structural Analysis Professional and other widely used
structural analysis software applications.

The result of better interoperability is a more streamlined and productive design process,
the opportunity to perform more analysis to help find the best structural design option, and
a better understanding of design intent yielding less errors and omissions.

Autodesk, the Autodesk logo, Revit, and Robot are registered trademarks or trademarks of Autodesk, Inc., and/or its
subsidiaries and/or affiliates in the USA and/or other countries. All other brand names, product names, or
trademarks belong to their respective holders. Autodesk reserves the right to alter product and services offerings,
and specifications and pricing at any time without notice, and is not responsible for typographical or graphical errors
that may appear in this document.

© 2014 Autodesk, Inc. All rights reserved.

29
