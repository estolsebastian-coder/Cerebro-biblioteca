---
type: libro
title: "adsk_aqr"
author: "mfisher"
categoria: "AYUDAS DE PROGRAMAS"
paginas: 6
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/AYUDAS DE PROGRAMAS/AUTOCAD/adsk_aqr.pdf"
convertido: 2026-10-16
---

# adsk_aqr

> Texto extraído de `AYUDAS DE PROGRAMAS\AUTOCAD\adsk_aqr.pdf` (6 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

AutoCAD ® 2007
AutoCAD LT ® 2007
Quick Reference

Use the Help System

locate entries in the index enter a question or phrase for the natural language version or
enter exact words and phrases for the Microsoft version

navigate to
topics using
the table of
contents

understand how display a list of
to use a feature commands and
system variables
display procedures related to related to the
the selected topic selected topic

Autodesk, the Autodesk logo, AutoCAD, AutoCAD LT and DesignCenter are registered trademarks of Autodesk, Inc. All
other brand names, product names, or trademarks belong to their respective holders.

<!-- p. 2 -->

Command Aliases

Command Alias Command Alias

ADCENTER dc LINE l

ARC a MOVE m

BLOCK b MTEXT t

CIRCLE c OFFSET o

COPY co OPTIONS op

DIMSTYLE d PAN p

DIST di PLINE pl

DSETTINGS ds PROPERTIES pr

ERASE e ROTATE ro

EXPLODE x TABLE tb

EXTEND ex TOOLPALETTES tp

FILLET f TRIM tr

HATCH h UNDO u

INSERT i XREF xr

LAYER la ZOOM z

You can define your own command aliases; see “Create Command Aliases” in the Help system. For a complete
list of command aliases, click Tools ➤ Customize ➤ Edit Program Parameters.

Shortcut Keys

Shortcut Description Command or
Keys System Variable

F1 Opens the Help system HELP

F2 Switches between text window and drawing area GRAPHSCR, TEXTSCR

F3 Turns running object snaps on and off OSNAP

F7 Turns the grid on and off GRID

F8 Turns Ortho mode on and off ORTHO

F9 Turns Snap on and off SNAP

F10 Turns polar tracking on and off DSETTINGS

F11 Turns object snap tracking on and off DSETTINGS

F12 Turns off Dynamic Input temporarily DYNMODE

CTRL+9 Turns the command window on and off COMMANDLINE/HIDE

CTRL+0 Turns user interface elements on and off CLEANSCREENON/OFF

CTRL+R Cycles through viewports CVPORT

<!-- p. 3 -->

Coordinate Entry

Method Format Description

Absolute Cartesian #X,Y Specifies a location measured by distances
coordinates from 0,0 in the current UCS

Relative Cartesian @X,Y Specifies a location measured by distances
coordinates from the last point

Absolute polar coordinates #distance\<angle Specifies a location measured by distance and
angle from 0,0 in the current UCS

Relative polar coordinates @distance\<angle Specifies a location measured by distance and
angle from the last point

Coordinate filters .x or .y or .z or Specifies a location by extracting and
.xy or .yz or .xz combining coordinate values from two or
three locations

Direct distance entry distance Specifies a location from the direction that you
move the pointing device and the distance
you enter

Lock an angle for a point \<angle Specifies an angle override that locks the
cursor for the next point entered

Enter coordinates, filters, and distances at any point prompt on the command line.

System Variables

System Variable Description

DRAGMODE Controls the way dragged objects are displayed

GRIPOBJLIMIT Suppresses the display of grips when the initial selection set includes more than the
specified number of objects

LTSCALE Sets the global linetype scale factor

PICKADD Controls whether new selections replace the current selection set or add to it

PICKDRAG Controls the method of drawing a selection window

PICKSTYLE Controls the use of group selection and associative hatch selection

PSLTSCALE Controls linetype scaling in a layout

UCSICON Controls the display of the UCS icon in the current viewport

VISRETAIN Controls the visibility, color, linetype, lineweight, and plot styles of xref-dependent
layers (if PSTYLEPOLICY is set to 0)

XLOADCTL Turns xref demand-loading on and off and controls whether the original drawing or
a copy is opened

For a complete list of system variables, see the Command Reference in the Help system.

<!-- p. 4 -->

Object Selection

To select Use this method at the
Select Objects prompt

Individual objects Click the object you want to
select

Most recently created visible object Last (enter L)

Most recent selection set Previous (enter p)

Add or remove objects from selection Hold down SHIFT and select
objects

Objects touching or enclosed by the crossing Crossing (drag cursor from
1
selection; selected objects are gray in the right to left, or enter c)
illustration

2

Objects completely within the window selection; Window (drag cursor from
2
selected objects are gray in the illustration left to right, or enter w)

1

Objects touched by a fence (a crossing polyline); Fence (enter f)
selected objects are gray in the illustration

Objects crossing or completely within a polygon; CPolygon (enter cp)
selected objects are gray in the illustration

Objects completely within a polygon; selected WPolygon (enter wp)
objects are gray in the illustration

<!-- p. 5 -->

The Interface

Current Tab

Tool Palettes

■Place frequently used blocks,
hatches, and commands on a tool
palette.
■Create custom tools and text. Non-current Tabs
■Drag blocks and hatches from the
tool palette into your drawing.

■Right-click the indicated areas in
the illustration to display relevant
shortcut menus.

DesignCenter

■Organize access to drawings, blocks,
hatches, and other drawing content.

■Drag content from any source
drawing to your current drawing.

■Drag drawings, blocks, and hatches
to a tool palette.

■Right-click the indicated areas in the
illustration to display relevant
shortcut menus.

<!-- p. 6 -->

In-Place Text Editor (MTEXT command)

Create one or more paragraphs of multiline text (mtext) in the In-Place Text Editor.

save changes and close

display ruler display menu options

first line indent ruler

set width of multiline text objects

tab stops

paragraph indent

Layer Settings, Property Override Controls, Status Bar Buttons, and Tray Settings

Set the current layer and control layer display. Override the default color, linetype, and lineweight properties.
Control the display of status bar buttons from the shortcut menu. When tray settings are turned on, icons and
notifications are displayed in the tray at the right end of the status bar.

Styles Toolbar: Text, Dimensions, Tables
Layer Control Color Control Linetype Control

Right click any toolbar to Lineweight Control
display shortcut menu

status bar

Communication Toolbar/Window
Center: Positions Unlocked:
cursor status bar buttons: use get information lock or unlock
coordinates precision tools when drawing from Autodesk and toolbars and
submit feedback windows
