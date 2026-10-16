---
type: libro
title: "LinkConstraintUtility"
author: "Andrew Ostler"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 3
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/3D MAX Y VRAY/MODELOS/Nueva carpeta/Scripts/LinkConstraintUtility/LinkConstraintUtility.pdf"
convertido: 2026-10-16
---

# LinkConstraintUtility

> Texto extraído de `AYUDAS DE PROGRAMAS\3D MAX Y VRAY\MODELOS\Nueva carpeta\Scripts\LinkConstraintUtility\LinkConstraintUtility.pdf` (3 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Link Constraint Utility

Preamble
The Link Constraint Utility (LCU) is intended to make it easier to peruse and manipulate all the
various Link Constraints in a scene in a single view at once.

Opening the Utility
The LCU can be used in two ways: as a scripted utility panel, or as a rollout floater. Functionality is
identical in both cases, and the two can be used concurrently.

Use as a scripted utility panel
Follow the usual procedure for a MAXScripted utlity: in the 3ds Max
Utilities panel, select the MAXScript utility. If the utility has not yet
been installed, click the Run Script button, which will bring up a file
browser in which you should locate the script file. Then choose “LM
Link Constraint Utility” from the drop-down menu as shown in the
image.

Use as a rollout floater

<!-- p. 2 -->

Open the Customize User Interface dialog and
locate the LCU item in the “LinkConstraintUtility”
category.

In Use

The image above shows the LCU in a simple scene containing three spheres. Sphere01 uses Sphere02
and Sphere03 as parents (the usual link constraint view in the motion panel is shown for comparison).

In the LCU window there is a rollout for each object in the scene that uses a link constraint.

The “Select” button selects the object that is the subject of the rollout (Sphere01 in the example).

The “Trajectory” checkbox shows or hides the display of the object’s trajectory (as is displayed by
clicking the Trajectories button in the motion panel).

The listbox shows the object’s parents and the key times at which the links are active (this is the same
information that is shown in the link constraint rollout in the motion panel).

Clicking an item in the listbox selects the object in the scene. Double-clicking an item shows or hides
the trajectory for that object. (An object in the list with a visible trajectory is noted by the prefix “(T)”
in front of its name.)

<!-- p. 3 -->

Selecting objects in the scene (e.g. by clicking on them in the viewport) highlights any entries those
objects may have in the LCU listboxes.
