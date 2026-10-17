---
type: libro
title: "Inf Interna del Programa"
author: "Ing. Eliud"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 18
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/COMPUTERS AND STRUCTURES/Inf Interna del Programa.pdf"
convertido: 2026-10-16
---

# Inf Interna del Programa

> Texto extraído de `AYUDAS DE PROGRAMAS\COMPUTERS AND STRUCTURES\Inf Interna del Programa.pdf` (18 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Frame/Cable Section

Form: Frame Properties

Defining a frame/cable section makes the section available for assignment to selected frame/cable
elements.

The Define menu > Frame/Cable Sections command allows you to (a) import sections from predefined
databases, (b) define frame section properties on the basis of their dimensions, (c) review and modify
section properties, and (d) delete section properties.

To define frame sections:

\1. Click the Define menu > Frame Sections command to bring up the Define Frame Properties form.
\2. On the Define Frame Properties form, the "Properties" area of this form lists the names of all the
currently defined frame section properties; SAP2000 automatically creates this list, which you can
use or add to, modify, or delete as necessary using the two drop-down lists and two buttons in the
"Click to" area of the form:

b. Import {Property}

Initially displaying "Import I/Wide Flange," use this drop-down list to import frame
section properties from one of several section databases included with SAP2000.

To import a section from a database,

\1. Click on one of the section types in the Import {Property Name} drop-
down list.
\2. Specify a database file from which to choose the section, if SAP2000
displays the Section Property File form. See Frame Section Databases
for a list of the section databases included with SAP2000.
\3. SAP2000 then displays a list of all of the sections of the type specified
in the database. Click on one section to select it, or click here to learn
about methods for selecting multiple sections .

See Frame Section Types for a listing of the types of section properties that can be
imported and for access to further help that explains the various areas on the form. Note
that when you use the import feature, you do not make changes to the {Section Type}
form. Use the Import {Section Type} option to import the section type, then use the
Modify/Show Property button to make any desired changes.

c. Add {Property}

Initially displaying "Add I/Wide Flange," use this drop-down list to add section properties
that you specify on the basis of their section dimensions.

\1. Click on one of the section types in the Add {Section Type} drop-down list.
\2. SAP2000 then displays a form specific to the type of section selected. See
Frame Section Types to access further help that explains the various areas on the
{Section Type} form.
a. Modify/Show Property

<!-- p. 2 -->

• Highlight the section property to be reviewed/modified in the list of names in
the "Properties" area of the form.
• Click the Modify/Show Property button.
• SAP2000 displays a form specific to the type of section selected. Use this form
to modify the desired parameter. See Frame Section Types to access further help that
explains the various areas of a particular section form.

a. Delete Property

• Highlight the section property to be deleted in the list of names in the
"Properties" area of the form.
• Click the Delete Property button.

Note: Frame sections that are currently assigned to any line objects in the model or
that are used to define other frame section properties, such as nonprismatic
sections and auto select section lists, cannot be deleted.

<!-- p. 3 -->

Add SD Section

Form: SD Section Data

Use the Section Designer utility to graphically define unusual sections. SAP2000 then calculates the section
properties for that section.

Add frame section properties using Section Designer as follows:

\1. Click the Define menu > Frame/Cable Sections command to access the Frame Properties form.
\2. In the "Click to" area of the Frame Properties form, use the drop-down list that initially reads
"Add I/Wide Flange" to locate and highlight Add SD Section to access the SD Section Data form.
\3. Use the SD Section Data form to provide parameters for the following:

o Section name: Specify or modify the name of the frame section.
o Base Material: Specify or modify a defined material property. The options available
depend on the design type of the material property selected.
 If the design type of the specified material property is Steel, the No
Design/Check option and the General Steel Section option are available.
 If the design type of the specified material property is Concrete, the No
Design/Check option and the Concrete Column option are available.
 If the design type of the specified material property is Other, only the No
Design/Check option is available.
o Design Type: Specify the section type.
 If the section type is a General Steel Section, any frame section assigned this
property is designed by the Steel Frame Design postprocessor as a general
section.
 If the section type is Concrete Column, any frame section assigned this property
is designed by the Concrete Frame Design postprocessor.
 If the section type is Other (not designed), any frame section assigned this
property is not designed by any postprocessor.
o Concrete Column Check/Design: This area is active only if the Concrete Column option
has been selected in the Design Type area. Use this option to specify whether the
concrete column is to have its specified reinforcing checked or new longitudinal
reinforcing designed when it is run through the Concrete Frame Design postprocessor.

o Define/Edit/Show Section and the Section Designer button: After you have
appropriately specified items in the rest of the form, click the Section Designer button in
this area to go to the Section Designer utility and draw the section. When you exit the
Section Designer utility, you return to the SD Section Data form. Click the OK button to
complete the definition of the frame section property.
o Display Color. The display color box identifies the color that will be used to display the
section. Click on the box to access the Color form where you can change to a different
coloring by clicking on it and then clicking the OK button to close that form.
\4. After you had defined the frame properties using the Section Designer utility, click the OK button.

<!-- p. 4 -->

Frame Loads - Distributed

Form: Frame Distributed Loads

Distributed (Uniform and Trapezoidal) forces and moments can be assigned along the length of frame/cable
objects. The loads may be as simple or as complicated as required.

Loads are specified in force-per-length or moment-per-length units.

\1. Select one or more frame/cable objects to be assigned loads.
\2. Use the Assign menu > Frame Loads > Distributed command to access the Frame Distributed
Loads form.
 Load Case Name. Choose the load case to which the load(s) is being assigned
 Units. Choose the units to be used.
 Load Type and Direction. Specify the load type (Forces or Moments) and coordinate
system and the load direction.

Note: The Gravity direction is taken to be in the negative Global Z direction. To enter a
load in the gravity direction, enter a positive number if the direction is set to Gravity and a
negative number if the direction is set to Global Z.

 Options Specify how the load will be applied.
o Add to Existing Loads: Adds the specified distributed load to the frame object.
If one or more distributed load assignments have already been made, this option
increases the existing load, assuming a positive load is being specified.
o Replace Existing Loads: Replaces the currently specified distributed load, if
any, with the new load. If no assignment exists, the new assignment is still
made. This is the default option.
o Delete Existing Loads: Deletes any and all distributed load assignments made
to the selected object(s). When this option is selected, the items in the Load
Type and Direction, Trapezoidal Loads, and Uniform Loads areas of the form
are ignored when the OK button is clicked.

Note that the default option is Replace and that the program defaults to this every time the
form is opened.

 Trapezoidal Loads. For trapezoidal loads, enter up to four locations and the
corresponding load values in the proper units. The load will change abruptly at the first
and fourth locations, and vary smoothly at the second and third locations. If more than
four locations are needed, perform more assignment operations, using the Add to Existing
Loads option.
 Relative Distance from End-I or Absolute Distance from End-I. Specify if
the distance from End I is relative or absolute for the location(s) specified in the
Trapezoidal Loads area of the form.
 Uniform Loads. For uniform loads (i.e., constant over the full length of the selected
object), enter the load value in the Uniform Load field.

If uniform and trapezoidal loads are specified at the same time, they are additive.

<!-- p. 5 -->

Frame Loads - Points

Form: Frame Point Loads

Concentrated forces and moments can be assigned along the length of frame/cable objects. The loads may
be as simple or as complicated as required.

\1. Select one or more frame/cable objects to be assigned loads
\2. Use the Assign menu > Frame Loads > Point command to access the Frame Point Loads form.
 Load Case Name. Choose the load case to which the loads are being assigned
 Units. Choose the units to be used.
 Load Type and Direction. Specify the type of load (Force or Moment), the coordinate
system, and the load direction.

Note: The Gravity direction is taken to be in the negative Global Z direction. To enter a
load in the gravity direction, enter a positive number if the direction is set to Gravity and a
negative number if the direction is set to Global Z.

 Options. Specify how the load will be applied.
o Add to Existing Loads: Adds the specified point load to the frame object. If
one or more point load assignments have already been made, this option
increases the existing load, assuming a positive load is being specified.
o Replace Existing Loads: Replaces the currently specified point load, if any,
with the new load. If no assignment exists, the new assignment is still made.
This is the default option.
o Delete Existing Loads: Deletes any and all point load assignments made to the
selected object(s). When this option is selected, the items in the Load type and
Direction and Point Loads areas of the form are ignored when the OK button is
clicked.

Note that the default option is Replace and that the program defaults to this every time the
form is opened.

 Point Loads. Enter up to four locations and the corresponding load values in the proper
units. If you need more than four locations, perform more assignment operations, using
the Add to Existing Loads option.
 Relative Distance from End-I or Absolute Distance from End-I. Specify if
the distance from End I is relative or absolute for the location(s) specified in the
Point Loads area of the form.

<!-- p. 6 -->

Define Area Sections

Form: Area Sections, Area Section Data

Use the Define menu > Area Sections command to access the Area Sections form and add, modify, or
delete an area property definition. The area project definition consists of geometrical and material
properties.

 Sections. This area of the form lists any section property definitions. When the Add New Section
button is used, the property definition name appears in this list. When a property needs to be
modified or deleted, select it from this list before using the Modify/Show Section button or the
Delete Section button.
 Add New Section button. Click the Add New Section button to access the Area Section Data form
and define a new area section definition. The Area Section Data form has the following areas.
o Section Name edit box. Use the suggested default or type a name in the edit box.
o Material Name drop-down list. Select the Material name (type) from the drop-down list.
o Material Angle edit box. Use this edit box to specify an angle to modify the local axis of
the area objects to which this area section definition is assigned.
o Area Type. Choose to specify the area object as a Shell, Plane or Axisysmmetric Solid
(Asolid) by selecting the appropriate option.
o Membrane Thickness edit box. Type a value for the membrane thickness in this edit
box, if appropriate.
o Bending Thickness edit box. Type a value for the bending thickness in this edit box, if
appropriate.
o Type. Specify Shell, Membrane, or Plate type by selecting the appropriate option.
o Thick Plate check box. Check this check box to include a thick plate.
o Set Modifiers button. Click the Set Modifiers button to access the Property Stiffness
Modification Factors form.
o Display Color box. The Display Color box shows the color that will be used to display
the area sections defined. Click the Display Color box to display the Color form; click a
new color to change the display color.
 Modify/Show Section button.
\1. Select the property definition to be modified from the list of property definitions in the Sections
area of the Area Sections form.
\2. Click the Modify/Show Section button to access the Area Section Data form and modify the
selected section definition.
 Delete Section button
\1. Select the property definition to be deleted from the list of property definitions in the Sections area
of the Area Sections form.
\2. Click the Delete Section button to delete the definition

<!-- p. 7 -->

Sign Convention

Normal Axis 3

Local axis 3 is always normal to the plane of the shell element. This axis is directed towards you
when the path j1-j2-j3 appears counter-clockwise. For quadrilateral elements, the element plane is
defined by the vectors that connect the mid-points of the two pairs of opposite sides.

Default Orientation

The default orientation of the local 1 and 2 axes is determined by the relationship between the
local 3 axis and the global Z axis:

 The local 3-2 plane is taken to be vertical, i.e., parallel to the Z axis
 The local 2 axis is taken to have an upward (+Z) sense unless the element is horizontal, in
which case the local 2 axis is taken along the global +Y direction.
 The local 1 axis is horizontal, i.e., it lies in the X-Y plane

The element is considered to be horizontal if the sine of the angle between the local 3 axis and the
Z axis is less than 10-3.

The local 2 axis makes the same angle with the vertical axis as the local 3 axis makes with the
horizontal plane. This means that the local 2 axis points vertically upward for vertical elements.

Element Coordinate Angle

The shell element coordinate angle, ang, is used to define element orientations that are different
from the default orientation. It is the angle through which the local 1 and 2 axes are rotated about
the positive local 3 axis from the default orientation. The rotation for a positive angle value of ang
appears counter-clockwise when the local +3 axis is pointing toward you.

For horizontal elements, ang is the angle between the local 2 axis and the horizontal +Y axis.
Otherwise, ang is the angle between the local 2 axis and the vertical plane containing the local 3
axis. The following figures provide examples.

<!-- p. 8 -->



<!-- p. 9 -->



<!-- p. 10 -->

Frame Element Internal Forces Output Conventions

The frame element internal forces are:

 P, the axial force
 V2, the shear force in the 1-2 plane
 V3, the shear force in the 1-3 plane
 T, the axial torque (about the 1-axis)
 M2, the bending moment in the 1-3 plane (about the 2-axis)
 M3, the bending moment in the 1-2 plane (about the 3-axis)

These internal forces and moments are present at every cross section along the length of the frame element.

For each load case and load combination the frame element internal forces and moments
are computed and reported at each frame element output station.

In frame element output displayed in a tabular form, either on the computer screen, printed to a printer or
printed to a file, the locations of the output stations are identified by the absolute distance to the station
measured from the i-end of the element.

The sign convention for frame element internal forces is illustrated in the figure below. This sign
convention can be described by defining the concept of positive and negative faces of an element. Consider
a section cut through the element in the 2-3 plane. At this section the positive 1 face is the face whose
outward normal (arrow that is perpendicular to the section and pointing away from the section) is in the
positive local 1 direction. At this same section the negative one face is one whose outward normal is in the
negative local 1 direction. The positive 2 and 3 faces are those faces with outward normals in the positive
local 2 and 3 directions, respectively, from the neutral axis. Note the following about the frame element
internal forces:

<!-- p. 11 -->

 Positive internal forces (P, V2 and V3) and positive axial torque (T) acting on a positive 1 face are
oriented in the positive direction of the corresponding element local coordinate axis. For example,
when V2 acting on a positive 1 face is positive it is oriented in the direction of the positive local 2-
axis.

 Positive internal forces (P, V2 and V3) and positive axial torque (T) acting on a negative 1 face
are oriented in the negative direction of the corresponding element local coordinate axis. For
example, when V2 acting on a negative 1 face is positive it is oriented in the direction of the
negative local 2-axis.

 Positive M2 bending moments cause compression on the positive 3 face and tension on the
negative 3 face.

 Positive M3 bending moments cause compression on the positive 2 face and tension on the
negative 2 face.

 When end offsets along the length of the frame element are present, the internal forces and
moments are output at the faces of the supports rather than the ends of the element. No output is
produced within the end offset length.

 The right-hand rule applies in the figure for determining the sense of the moments shown by the
double arrows.

<!-- p. 12 -->

Forces/Stresses – Shells.

Form: Element Forces/Stress Contours for Shells

\1. Click the Display menu > Forces/Stresses > Shells command to display the Element Forces/Stress
Contours for Shells form and display internal area object element forces and stresses directly on
the model.

Important note: The internal shell element forces are forces per unit length acting along the
midsurface of the shell element (area object). The internal shell element stresses are stresses
acting on the edges (not positive 3-axis face and negative 3-axis face) of the shell element (area
object). See Sign Conventions for more information about the faces of shell objects.

 Case/Combo Name: Choose the analysis case or combination whose shell element
forces or stresses are to be displayed.
 Multivalued Options. For multi-mode cases, choose the mode number for which results
are to be shown. For multi-step cases, choose the step number, time step, or frequency
step; or choose Envelope to view the maximum or minimum results over all steps.
 Component Type: Specify display of shell element internal forces or the internal
stresses.
 Component: Specify which component of force or stress is to be displayed.

Shell element internal forces.

o F11: Direct force per unit length acting at the midsurface of the element on the
positive and negative 1 faces in the 1-axis direction.
o F22: Direct force per unit length acting at the midsurface of the element on the
positive and negative 2 faces in the 2-axis direction.
o F12: Shearing force per unit length acting at the midsurface of the element on
the positive and negative 1 faces in the 2-axis direction, and acting on the
positive and negative 2 faces in the 1-axis direction.
o FMAX: Maximum principal force per unit length acting at the midsurface of the
element. Note that by definition, principal forces are oriented such that the
associated shearing force per unit length is zero.
o FMIN: Minimum principal force per unit length acting at the midsurface of the
element. Note that by definition, principal forces are oriented such that the
associated shearing force per unit length is zero.
o FVM: See Von Mises Stress
o M11: Direct moment per unit length acting at the midsurface of the element on
the positive and negative 1 faces about the 2-axis.
o M22: Direct moment per unit length acting at the midsurface of the element on
the positive and negative 2 faces about the 1-axis.
o M12: Twisting moment per unit length acting at the midsurface of the element
on the positive and negative 1 faces about the 1-axis, and acting on the positive
and negative 2 faces about the 2-axis.
o MMAX: Maximum principal moment per unit length acting at the midsurface
of the element. Note that by definition, principal moments are oriented such that
the associated twisting moment per unit length is zero.
o MMIN: Minimum principal moment per unit length acting at the midsurface of
the element. Note that by definition, principal moments are oriented such that
the associated twisting moment per unit length is zero.

<!-- p. 13 -->

o V13: Out-of-plane shear per unit length acting at the midsurface of the element
on the positive and negative 1 faces in the 3-axis direction.
o V23: Out-of-plane shear per unit length acting at the midsurface of the element
on the positive and negative 2 faces in the 3-axis direction.
o VMAX: Maximum principal shear per unit length acting at the midsurface of
the element. Note that by definition, principal shears are oriented on faces of the
element such that the associated shears per unit length on perpendicular faces
are zero.

Shell element internal stresses.

o S11: Direct stress (force per unit area) acting on the positive and negative 1
faces in the 1-axis direction.
o S22: Direct stress (force per unit area) acting on the positive and negative 2
faces in the 2-axis direction.
o S12: Shearing stress (force per unit area) acting on the positive and negative 1
faces in the 2-axis direction and acting on the positive and negative 2 faces in
the 1-axis direction.
o SMAX: Maximum principal stress (force per unit area). Note that by definition,
principal stresses are oriented such that the associated shearing stress is zero.
o SMIN: Minimum principal stress (force per unit area). Note that by definition,
principal stresses are oriented such that the associated shearing stress is zero.
o SVM: Von Mises stress (force per unit area).
o S13: Out-of-plane shearing stress (force per unit area) acting on the positive and
negative 1 faces in the 3-axis direction.
o S23: Out-of-plane shearing stress (force per unit area) acting on the positive and
negative 2 faces in the 3-axis direction.
o SMAXV: Maximum principal shearing stress (force per unit area). Note that by
definition, principal shearing stresses are oriented on faces of the element such
that the associated shears per unit length on perpendicular faces are zero.

 Contour Range: The shell element internal forces and stresses are displayed as colored
contours. Specify two values:

o Min: Any element with a force or stress less than the value shown here is
displayed in the color associated with Min in the Contours area of the Assign
Output Colors form. Note that the color associated with Min is the top color in
the form.
o Max: Any element with a force or stress greater than or equal to the value
shown here is displayed in the color associated with Max in the Contours area of
the Assign Output Colors form. Note that the color associated with Max is the
top color in the form.

The program spaces the intermediate range values equally between the
specified Min and Max values. If the Min and Max values are set to zero,
SAP2000 will automatically create a contour range that includes all values.
This is the default.

<!-- p. 14 -->

Von Mises Stress

The Von Mises Stress provides a measure of the shear, or distortional, stress in the material. This type of
stress tends to cause yielding in metals. It is independent of the amount of hydrostatic stress (σ1= σ2= σ3)
action on the material.

The Von Mises Stress is identified in terms of the principal stresses as
σvm=√1/2[(σ1- σ2)2+( σ1- σ3)2+( σ2- σ3)2].

In a state of pure tension, say σ11=σ and all other stresses are zero, then σvm=σ. In a state of pure shear, say
σ12=τ and all other stresses are zero, then σvm=√3 τ.

For materials, initial yielding can be expected when σvm=σy, where σy is the tensile yield stress, or when
σvm=√3 τy, where τy is the yield stress in shear. For other materials, particularly frictional materials such as
soil and concrete, the Von Mises Stress may have no value in predicting yield or failure.

<!-- p. 15 -->

Mesh Areas

Form: Mesh Selected Areas

To Mesh

\1. Select the area objects to be meshed.
\2. Click the Edit menu > Mesh Areas command to access the Mesh Selected Areas form.
\3. Select the Mesh into option.
\4. Type in the number of objects (in both directions) into which the area objects should be meshed.
\5. Click the OK button.

To Mesh using selected Joints on edges

\1. Select the area objects to be meshed into multiple objects and also select the joints on the edges of
the area objects.
\2. Click the Edit menu > Mesh Areas command to access the Mesh Selected Areas form.
\3. Select the Mesh using selected Joints on edges option.
\4. Click the OK button.

To Mesh using grid intersections

\5. Select the area objects to be meshed into multiple objects.
\6. Click the Edit menu > Mesh Areas command to access the Mesh Selected Areas form.
\7. Select the Mesh at intersection with grids option.
\8. Click the OK button.

Note: For the mesh using selected joints on edges option to work, an equal number of joints must be present on the opposite edges.
Also, if both sides are not divided, this option will not work.

Area - Automatic Area Mesh

Form: Assign Automatic Area Mesh

Use the Assign menu > Area > Automatic Area Mesh command to activate the Assign Automatic Area
Mesh form. The options on the form specify how SAP2000 internally subdivides the selected area objects:

 No Auto Meshing – Tags the area object to not be automatically meshed by SAP2000 into the
analysis model, thereby treating the object as a structural element.
 Auto Mesh Area – When this option is selected, use the edit boxes to specify how the selected
object is to be subdivided.
 Add restraints along edge if corners have restraints – When the Auto Mesh Area
option is selected, check this check box to add restraints along the edges of the meshed
objects when the corners of the selected object were assigned restraints.

Note: Unlike the Edit menu > Mesh Areas command, the Assign menu > Area > Automatic Area Mesh
command does not change the size or number of the objects; the meshing performed is internal and is
handled similar to any other assignment. This allows for the meshing to be changed or removed without
any effect on the area object geometry. Use the Display menu > Miscellaneous Assigns > Area command to
display the Automatic Area Object Meshing and the Automatic Area Edge Constraints.

<!-- p. 16 -->

Area Loads - Uniform (Shell)

Form: Area Uniform Loads

\1. Select one or more area objects to which to assign the uniform load.
\2. Click on the Assign menu > Area Loads > Uniform (Shell) command to access the Area Uniform
Loads form.
 Load Case Name. Select the load case for which the uniform load is being specified.
 Units. Verify that the units are appropriate for specifying the load. Use the drop-down list
to change them, if necessary.
 Uniform Load. Specify the load value. Use the drop-down lists to specify the coordinate
system and the load direction.

Note: The Gravity direction is taken to be in the negative Global Z direction. To enter a
load in the gravity direction, enter a positive number if the direction is set to Gravity and a
negative number if the direction is set to Global Z.

 Options. Specify how the load is to be applied.
o Add to Existing Loads: Adds the specified uniform load to the area object. If
one or more uniform load assignments have already been made, this option
increases the uniform load, assuming, of course, that a positive stiffness is being
specified.
o Replace Existing Loads: Replaces the currently specified uniform load if any,
with the new load. If no assignment has been made, the new assignment is still
made. This is the default option.
o Delete Existing Loads: Deletes any and all uniform load assignments made to
the selected area object(s). When this option is selected, the items in the
Uniform Load area of the form are ignored when the OK button is clicked.
 Click the OK button.

<!-- p. 17 -->

Diaphragm Constraints Form

Access the Diaphragm Constraints form by clicking the Add New Constraint or Modify/Show Constraint
button on the Define Constraints form or the Define/Assign Constraints form after selecting "Diaphragm"
from the Choose Constraint to Add drop-down list on those forms, which are accessed using the Define
menu > Joint Constraints command or the Define menu > Assign Joint Constraints command, respectively.

A Diaphragm Constraint causes all of its constrained joints to move together as a planar diaphragm that is
rigid against membrane (in-plane) deformation. This constraint can be used to:

 Model concrete floors (or concrete-filled decks) in building structures, which typically have very
high in-plane stiffness
 Model diaphragms in bridge superstructures

The constraint must have at least two joints to have any effect on the model. It is intended to be used on a
set of joints that lie in a flat plane. If the joints are not co-planar, the constraint will effectively restrain the
joints against out-of-plane (plate) bending, which unrealistically stiffens the structure.

An option is available to automatically create multiple, independent constraints at different elevations from
the single set of joints assigned this constraint.

Use the following areas on the Diaphragm Constraints form to make the appropriate entries:

 Constraint Name Use the default or enter a unique name for the constraint being defined. If the
multiple-constraint option is used (see below), the independent, automatic diaphragm constraints
still share the same name.
 Coordinate System Choose the coordinate system in which the constraint axis (below) is being
defined. If the constraint axis is automatic, the choice of coordinate system has no effect on the
constraint.
 Constraint Axis The constraint equations will be written for a diaphragm in a plane
perpendicular to the selected axis. If the joints lie in a unique plane, it is usually best to choose the
Add button and let the program automatically determine the axis. This axis does not necessarily
need to be parallel to a coordinate-system direction. If the joints are not coplanar, or you want to
force a particular direction, choose the axis in the chosen coordinate system that is perpendicular
to the diaphragm. For example, if you choose the Z axis, this constraint is equivalent to a body
constraint in the same coordinate system with translations X and Y and rotation Z chosen. You
must choose direction Z if you want to use the automatic, multiple-constraint option (see below.)

 Automatic Multiple Constraints If you choose the constraint axis to be Z, you have the option
to check the Assign a different diaphragm constraint to each different selected Z level check box If
you check this option, the program will automatically create a separate diaphragm constraint for
each subset of joints assigned this constraint that have the same Z coordinate. For example, in a
simple structure you could assign one diaphragm to the entire model, and separate diaphragm
constraints would be created at each floor level. This assumes that there are no intermediate joints
on the columns or walls, and all joints at each floor are at the same elevation. Use with caution!

After a constraint has been defined, it must be assigned to the joints to be constrained.

<!-- p. 18 -->

Mass Source

Form: Define Mass Source

Use the Define menu > Mass Source command to access the Define Mass Source form and specify how
SAP2000 should calculate mass for the model. In SAP2000 mass and weight serve different functions.
Mass is used for the inertia in dynamic analyses, and for calculating the built-in acceleration loads. Weight
is a load that you define and assign in one or more load cases, which can then be applied in one or more
analysis cases.

 Mass Definition. Choose how to define the mass of the structure
\2. From Element and Additional Masses. By default, the program uses mass
specifications:
 Mass density specified for materials
 Additional line mass assigned to frame/cable objects
 Additional area mass assigned to area objects
 Mass specified for link properties
 Mass assigned directly to the joints.

\1. From Loads. Mass may be calculated from a scaled combination of load cases. The
absolute value of the net load acting in the global Z direction is divided by the
acceleration due to gravity, in the current units, and is used for the mass in the three
translational direction.
\2. From Element and Additional Masses and Loads. A combination of the methods (1)
and (2) above.

 Define Mass Multiplier for loads. If option 2 or 3 was selected for Mass Definition, enter a
combination of one or more load cases in the table using the Add, Modify, and Delete buttons.
These load cases will be scaled by the factors you specify and added together to determine the
mass. Do not include the acceleration due to gravity in the scale factors; the program will do that
automatically.
