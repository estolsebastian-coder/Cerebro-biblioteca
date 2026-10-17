---
type: libro
title: "HIKMICRO Analyzer Client_Release Notes_V2.0.1_en-US_202509"
author: ""
categoria: "TERMOGRAFÍA"
paginas: 25
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TERMOGRAFÍA/HIKMICRO Analyzer V2.0.1_250910_multiplelanguage/HIKMICRO Analyzer Client_Release Notes_V2.0.1_en-US_202509.pdf"
convertido: 2026-10-16
---

# HIKMICRO Analyzer Client_Release Notes_V2.0.1_en-US_202509

> Texto extraído de `TERMOGRAFÍA\HIKMICRO Analyzer V2.0.1_250910_multiplelanguage\HIKMICRO Analyzer Client_Release Notes_V2.0.1_en-US_202509.pdf` (25 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

HIKMICRO Analyzer Client V2.0.1
Release Notes

<!-- p. 2 -->

HIKMICRO Analyzer Client • Release Notes

TABLE OF CONTENTS

1 Introduction ............................................................................................................ 4
1.1 Version information .................................................................................................................................. 4
1.2 Multilanguage type ................................................................................................................................... 4
1.3 Running environment ............................................................................................................................... 5
2 New features .......................................................................................................... 6
2.1 Window layout adjustment available ...................................................................................................... 6
2.1.1 3 types of quick layout......................................................................................................................... 6
2.1.2 Arrange layout freely ............................................................................................................................ 6
2.1.3 Window layouts are automatically saved ........................................................................................... 8
2.2 Analysis toolbar and task list function rearranged ................................................................................ 8
2.2.1 Top toolbar ........................................................................................................................................... 8
2.2.2 Task list ................................................................................................................................................ 9
2.2.3 Auto grouping all image files in task list ............................................................................................ 9
2.3 Palette settings reorganized .................................................................................................................... 9
2.3.1 4 main palette types: palettes, isotherm, insulation and condensation ........................................... 9
2.3.2 Isotherm provides 3 temperature ranges with distinguished color or palette filling ..................... 10
2.3.3 Range of temperature scale is user adjustable ............................................................................... 11
2.3.4 New system palette: Blue Yellow ...................................................................................................... 11
2.3.5 Supported palette file format is changed to *gpl ............................................................................. 12
2.4 New overlay options and styles ............................................................................................................. 12
2.4.1 Emissivity, ambient temperature, distance and reflected temperature can be overlaid ............... 12
2.4.2 Top-left overlay style changeable ..................................................................................................... 12
2.4.3 Adjustable style of overlay displayed with measurement tools...................................................... 13
2.5 Settings path changed for overlay on exported images/videos .......................................................... 14
2.6 New features of exporting image temperature matrix ......................................................................... 14
2.7 Library mangement ................................................................................................................................ 14
2.7.1 File sorting and filtering are supported in local file and quick access folders ............................... 14
2.7.2 Files can be displayed in list in local and favorite folders ............................................................... 15
2.8 Report ...................................................................................................................................................... 15
2.8.1 New report home page offers creation guide .................................................................................. 15
2.8.2 ODT format templates supported ..................................................................................................... 16
2.8.3 HIKMICRO logo is added to thermal images in reports................................................................... 17
2.9 Live anaysis: player frame rate auto control ......................................................................................... 17
2.10 Compatibility ........................................................................................................................................... 17
2.10.1 New device function supported (by network connection) .......................................................... 17
2.10.2 Shield regions and sketch notes displayable in client ................................................................ 17
2.10.3 Connecting to devices that comply with EN 18031 supported .................................................. 18
2.11 Client settings and maintenance ........................................................................................................... 19
2.11.1 Client shortcut keys editable ........................................................................................................ 19
2.11.2 Bright appearance theme available .............................................................................................. 20
2.11.3 Opening files with HIKMICRO Viewer ........................................................................................... 20
2.11.4 Saving dumping file for trouble shouting ..................................................................................... 20
2.12 User support ........................................................................................................................................... 21
2.12.1 New feature introduction .............................................................................................................. 21
2.12.2 Error codes and troubleshooting guide........................................................................................ 21
3 Optimization and bug fixing ................................................................................... 22

<!-- p. 3 -->

HIKMICRO Analyzer Client • Release Notes

3.1 Optimization ........................................................................................................................................... 22
3.2 Bug fixing ................................................................................................................................................ 22

<!-- p. 4 -->

HIKMICRO Analyzer Client • Release Notes

1 Introduction

The HIKMICRO Analyzer client is used to view the temperature information
contained in thermal images and radiometric videos, and perform
temperature measurement data analysis.

Thermal images taken by a thermal camera can be imported to the client
for file management and analysis.

The client provides file management functions including file tagging,
categorization, etc. In addition, file analysis can be performed, including
image editing and temperature measurement data analysis. Multiple
operations can be performed for the analysis, including configuring
measurement tools, adjusting measurement parameters, switching image
display mode, setting color alarms, etc. After the analysis, you can view the
measurement results and charts, and save the images or export the report
as required.

Radiometric videos recorded by a thermal camera can also be imported to
the client for analysis. You can obtain the measurement results by
configuring measurement tools, adjusting measurement parameters, etc. At
the same time, the time-temperature curves and temperature distribution
histograms will be displayed for you to check the temperature changes and
distributions.

A thermal camera can be connected to the client for live view, and the real-
time temperature measurement analysis can be performed for the live view
image. You can obtain the measurement results by configuring
measurement tools, adjusting measurement parameters, etc.

1.1 Version information

Version Date

HIKMICRO Analyzer V2.0.1 2025-09

1.2 Multilanguage type

Type Chinese, Czech, Danish, Dutch, English, Finnish, French,
Germany, Hungarian, Italian, Japanese, Korean,
Norwegian, Polish, Portuguese, Russian, Romanian,

4

<!-- p. 5 -->

HIKMICRO Analyzer Client • Release Notes

Slovak, Spanish, Swedish, Turkish, Traditional Chinese

1.3 Running environment

Operating Microsoft® Windows 7 (64-bit operating system)
System Microsoft® Windows 10 (64-bit operating system)
Microsoft® Windows 11 (64-bit operating system)

CPU i5-4590 or above

RAM 8G or above

Graphics Card RADEON X700 series 256M or above

5

<!-- p. 6 -->

HIKMICRO Analyzer Client • Release Notes

2 New features

This chapter introduces the new features of HIKMICRO Analyzer Client
V2.0.1

2.1 Window layout adjustment available

2.1.1 3 types of quick layout

Quick Layout refers to several commonly used window layouts built into the
client software, which users can apply directly.

In the Analysis and Live tabs, click in the toolbar to show the quick
layout options. Click to select and apply.

The supported quick layout modes differ for image analysis, video analysis,
and live analysis.

2.1.2 Arrange layout freely

Users can freely add different types of information windows and adjust
their positions and sizes.

AddingandRemovingWindows

\1. Click the toolbar icon to open the list of supported windows for
addition.
\2. Click to select the required information window.
\3. Newly image windows are added by default to the right side of the main
window (the thermal image window); chart and table windows are added
below the main window by default. Additional windows of the same type
will be stacked as tabs.

AdjustingWindowPosition

6

<!-- p. 7 -->

HIKMICRO Analyzer Client • Release Notes

Left-click on the window header you want to reposition and drag it to adjust
its position. The layout indicator helps you locate where to place it.

 To detach a window from the software interface: Drag the window
header to any place where no layout indicator appears, then
release the mouse.
 To adjust window position within the main software interface:
Drag its header to the adjacent window of the target area until the
layout indicator appears. Align your cursor with the indicator's
position, then release to lock the window in the shaded preview
zone.

Resizingwindows

Move the cursor to the edge of the window. When the edge turns blue and
the cursor changes to , drag to adjust that edge's position.

7

<!-- p. 8 -->

HIKMICRO Analyzer Client • Release Notes

2.1.3 Window layouts are automatically saved

Window layouts for image, thermal video, and Live analysis are
automatically saved per session and restored upon reopening.

2.2 Analysis toolbar and task list function rearranged

2.2.1 Top toolbar

The top toolbar retains five function modules: window and layout
adjustment, image mode switching, measurement tools adding and editing,
image rotation, resizing and advanced settings, and file saving and
exporting.

 The palette and level and span settings are adjusted to palette
settings. See 2.3
 The access to overlay settings are moved to the right-click menu.
See 2.4

8

<!-- p. 9 -->

HIKMICRO Analyzer Client • Release Notes

2.2.2 Task list

Functionbuttonsrearranged

Batch operation for image files in the task list are integrated into three
action buttons located at the bottom.

 auto grouping
 batch operations
 remove all files

DeltarangeisincludedduringApplyMeasurementstoAll

Delta range settings is also synchronized when Applying Measurements to
All via the right-click menu in the task list.

2.2.3 Auto grouping all image files in task list

By setting a grouping rule, for example every two/three/four images a
group, all thermal images in the task list are grouped automatically top
down.

Click to start auto grouping. Note that the image order should be
arranged in advance as in-group order change is not allowed.

2.3 Palette settings reorganized

2.3.1 4 main palette types: palettes, isotherm, insulation and

condensation

Access to all palette-related settings is consolidated within the palette bar
area for easy use and navigation.

9

<!-- p. 10 -->

HIKMICRO Analyzer Client • Release Notes

2.3.2 Isotherm provides 3 temperature ranges with distinguished

color or palette filling

Isotherm is a palette mode which assigns differentiated colors to specific
temperature ranges for quick identifying abnormal or special temperature
areas in the image.

Up to three isotherm temperature segments can be set, each with either
solid color or palette filling.

Check the required isotherms and set the temperature range and color or
palette filling.

10

<!-- p. 11 -->

HIKMICRO Analyzer Client • Release Notes

Temperature ranges of isotherms can overlap. When overlapping occurs,
the priority order for effective isotherm segments is: Isotherm 3 > Isotherm
2 > Isotherm 1

2.3.3 Range of temperature scale is user adjustable

In manual level and span mode, the top and bottom of the temperature
scale is adjustable.

2.3.4 New system palette: Blue Yellow

11

<!-- p. 12 -->

HIKMICRO Analyzer Client • Release Notes

2.3.5 Supported palette file format is changed to *gpl

When importing a custom palette file into the client software, the file should
be a *gpl instead of a *pal (*.pal is supported in earlier client versions).

2.4 New overlay options and styles

2.4.1 Emissivity, ambient temperature, distance and reflected

temperature can be overlaid

Right-click on the image and select Overlay Settings/Tool Overlay to view
addible items.

Double click on the top-left info box can also open the overlay settings
window.

2.4.2 Top-left overlay style changeable

Right-click on the non-tool area of the image, and select Top-Left Overlay to
change the font color, size, and the background.

12

<!-- p. 13 -->

HIKMICRO Analyzer Client • Release Notes

2.4.3 Adjustable style of overlay displayed with measurement

tools

Adjustinginfoboxposition
 Click and drag the info box to adjust its position. If Show Arrow is
enabled, an indicator arrow is auto-generated when the info box is
far from the tool.
 The client supports restoring overlays to default positions.

13

<!-- p. 14 -->

HIKMICRO Analyzer Client • Release Notes

 In non-tool areas, use Restore All to Default Overlay Position in
the right-click menu. For a specific tool, use Restore to Default
Overlay Position.

 Overlay location settings apply to images (including live snapshots)
and live stream analysis, but not to radiometric videos (including
videos recorded during live stream analysis).
 Arrows are not displayed when opening saved/exported images
with standard photo viewers or video players. Arrows are only
visible when opening radiometric images in this client.

Adjustingdisplayitemsandcolor

 Double-click the overlay info box or select a tool area and use Tool
Overlay in the right-click menu to open settings.
 In settings, configure tool name/color, overlay content items, size
(scaling), text/background color, arrow visibility (auto-generated
when a info box is far from the related tool), and arrow color.
 Click Remember to apply modified settings to future tools.
 Click Reset to restore to the default settings.

2.5 Settings path changed for overlay on exported
images/videos
The new setting path is Settings > Image Overlay > Overlay on Exported
Images/Videos.

2.6 New features of exporting image temperature
matrix

 The matrix of the ellipse, circle, and polygon measurement is
supported for exporting.
 The pixel axes are added in the CSV file.

2.7 Library mangement

2.7.1 File sorting and filtering are supported in local file and

14

<!-- p. 15 -->

HIKMICRO Analyzer Client • Release Notes

quick access folders

When filtering files in local and quick access folders, as long as the filtering
conditions remain unchanged when switching between folders of the same
type, and the filter is applied automatically upon folder change.

2.7.2 Files can be displayed in list in local and favorite folders

In favorite folders, display in list is also supported. The width of column is
adjustable by dragging the header separator.

2.8 Report

2.8.1 New report home page offers creation guide

A report home page is added to offer creation guide and access to report
template and tag note template libraries.

15

<!-- p. 16 -->

HIKMICRO Analyzer Client • Release Notes

In report editing page, click to enter the home page.

2.8.2 ODT format templates supported

This version supports generating reports based on imported *odt template.
 Import the *odt template from the template library from report
home page.
 When generating reports with *odt templates, in-software report
editing is not supported.

16

<!-- p. 17 -->

HIKMICRO Analyzer Client • Release Notes

2.8.3 HIKMICRO logo is added to thermal images in reports

2.9 Live anaysis: player frame rate auto control
When the live image experiences severe stuttering during live analysis, the
client automatically adjusts the player frame rate to ensure a relatively
smooth preview.

Frame drop may occur during the auto adjustment.

2.10 Compatibility

2.10.1 New device function supported (by network connection)

R&D box camera, HM-TD2C68E-25/Q, firmware V5.5.110 and newer
versions: supports temperature measurement templates auto switch
(reboot free) when switching between normal lens and macro lens.

2.10.2 Shield regions and sketch notes displayable in client

The shielded regions and attached sketch notes can be viewed in client
analysis.

Shieldregion

In the client, shield regions are displayed as polygonal areas (with up to 10
sides) outlined in red and filled with gray transparent shading. Multiple
shield regions may exist within a single frame.

Temperature information within shield regions is excluded during analysis.
Therefore, when adding measurement tools, ensure they do not overlap
with shield regions.

Shield regions are view-only in the client and cannot be modified.

17

<!-- p. 18 -->

HIKMICRO Analyzer Client • Release Notes

Sketchnotes

During image capture, graphics annotated on the device via freehand
sketching are termed Sketch Notes. Check the Show Sketch Notes in
Annotation panel to display the sketch layer.

2.10.3 Connecting to devices that comply with EN 18031

supported

The version is compatible with new device firmware that complies with EN
\18031.

When the client is connecting to a device by network, if the device’s
Network Access function is disabled, the client will prompt a window to

18

<!-- p. 19 -->

HIKMICRO Analyzer Client • Release Notes

notify users and ask a permission to turn on the function on device and
proceed the connection.

2.11 Client settings and maintenance

2.11.1 Client shortcut keys editable

In this version, the all editable shortcut keys can be viewed by Settings >
Shortcut Keys

To change a function shortcut key, select one to be modified, and press the
keys.

Rulesofshortcutkeys

 Modifier keys as Ctrl, Alt, and Shiftare optional, while the X is
compulsory.
 The X could be one key of the following types: alphabet keys,
numeric keys, symbol keys such as !@#$%^&*(), function keys
from F1 to F12, and navigation keys as ↑↓←→.

When a shortcut key conflict occurs, the client handles it according to the
following two rules:

19

<!-- p. 20 -->

HIKMICRO Analyzer Client • Release Notes

 Scope of Effect. The scope of a shortcut key refers to the functional
module or window where it takes effect. If the scopes of the shortcut
keys differ, the client responds to the shortcut key according to the
current focus (active window). If the scopes are the same, the shortcut
key priority rule is applied.
 Priority. A shortcut key set later in time has higher priority. If multiple
shortcuts share the same scope, the client executes the one with the
highest priority.

2.11.2 Bright appearance theme available

Go to Settngs > Preference > Appearance Theme to change the theme
between Dark and Bright.

2.11.3 Opening files with HIKMICRO Viewer

When installing or upgrading the client, check Open RV and HRV Files with
HIKMICRO Analyzer by Default, Open JPEG Files with HIKMICRO Analyzer
by Default.

2.11.4 Saving dumping file for trouble shouting

A dump file is a snapshot of a computer's memory at a specific moment—
typically when a system, application, or process crashes or encounters a
critical error. It captures the state of the operating system, running
processes, loaded modules, and memory contents, providing crucial
diagnostic data for troubleshooting.

20

<!-- p. 21 -->

HIKMICRO Analyzer Client • Release Notes

After enabling Save Dump File, Windows creates a dump file for
troubleshooting when the client crashes. Go to Settings > Maintenance >
Dump File Path to get the dump file saving path. Download the file and
send it to the technical support team for problem analysis.

User Account Control confirmation is required to enable/disable the saving
dump file function.

2.12 User support

2.12.1 New feature introduction

When you open this version for the first time, a new feature introduction
page pops-up to give a quick idea about the main new features.

Click in the upper right corner of the client and select New Features to
read the page again.

2.12.2 Error codes and troubleshooting guide

For the frequently encountered error codes, this version provides an in-
software error code and troubleshooting guide. Click on the hyperlink of the
error code to view the troubleshooting advice of the error.

If the encountered error code is not included in the document, or if the issue
remains unresolved after following the guide, please record the error code
and contact our customer service or technical support for assistance.

21

<!-- p. 22 -->

HIKMICRO Analyzer Client • Release Notes

3 Optimization and bug fixing

3.1 Optimization

 Optimized the overall visual experience of the client, unified the use of
controls, and improved the visual consistency of pop-ups and controls
 Improved the overlay effects (line style and shadows) in analysis,
exported image.
 Improved the visual consistency of overlays across different export
types
 Improved image quality in exported PDF reports, screenshots and
exported mp4 files.
 The maximum zooming of image during analysis (image, video and
live) is adjusted to 1000%.

 When auto is selected in image Advanced Editing, detailed parameters
are hidden.
 During video and live analysis, if too many chart windows are open,
users are prompted to close some windows to improve client
performance.
 Prompts and error codes display improved in Live analysis.
 Solved the difficulty of inputting palette bar temperatures during live
analysis. Improve the slider operation smoothness.
 Enhanced the animations when switching between client main tabs.
 Optimized internal multi-process handling.

3.2 Bug fixing
 Fixed the issue of palette bar scale number shifting during temperature
switching; removed the upper temperature limit for the palette bar, with
the lower limit now configurable down to -273.15°C.
 Resolved the issue of file copy, cut, and paste failures in local folders.
 Fixed the problem that modified color tags of images during analysis
were not synchronized to the library section.

22

<!-- p. 23 -->

HIKMICRO Analyzer Client • Release Notes

Legal Information

© Hangzhou Microimage Software Co., Ltd. All rights reserved.

About this Manual

The Manual includes instructions for using and managing the Product.
Pictures, charts, images and all other information hereinafter are for
description and explanation only. The information contained in the Manual
is subject to change, without notice, due to firmware updates or other
reasons. Please find the latest version of this Manual at the HIKMICRO
website (www.hikmicrotech.com/).

Please use this Manual with the guidance and assistance of professionals
trained in supporting the Product.

Trademarks

and other HIKMICRO’s trademarks and logos are the properties
of HIKMICRO in various jurisdictions.

Other trademarks and logos mentioned are the properties of their
respective owners.

LEGAL DISCLAIMER

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THIS
MANUAL AND THE PRODUCT DESCRIBED, WITH ITS HARDWARE,
SOFTWARE AND FIRMWARE, ARE PROVIDED “AS IS” AND “WITH ALL
FAULTS AND ERRORS”. HIKMICRO MAKES NO WARRANTIES, EXPRESS OR
IMPLIED, INCLUDING WITHOUT LIMITATION, MERCHANTABILITY,
SATISFACTORY QUALITY, OR FITNESS FOR A PARTICULAR PURPOSE. THE
USE OF THE PRODUCT BY YOU IS AT YOUR OWN RISK. IN NO EVENT WILL
HIKMICRO BE LIABLE TO YOU FOR ANY SPECIAL, CONSEQUENTIAL,
INCIDENTAL, OR INDIRECT DAMAGES, INCLUDING, AMONG OTHERS,
DAMAGES FOR LOSS OF BUSINESS PROFITS, BUSINESS INTERRUPTION,
OR LOSS OF DATA, CORRUPTION OF SYSTEMS, OR LOSS OF
DOCUMENTATION, WHETHER BASED ON BREACH OF CONTRACT, TORT
(INCLUDING NEGLIGENCE), PRODUCT LIABILITY, OR OTHERWISE, IN
CONNECTION WITH THE USE OF THE PRODUCT, EVEN IF HIKMICRO HAS
BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES OR LOSS.

YOU ACKNOWLEDGE THAT THE NATURE OF THE INTERNET PROVIDES
FOR INHERENT SECURITY RISKS, AND HIKMICRO SHALL NOT TAKE ANY
RESPONSIBILITIES FOR ABNORMAL OPERATION, PRIVACY LEAKAGE OR
OTHER DAMAGES RESULTING FROM CYBER-ATTACK, HACKER ATTACK,

23

<!-- p. 24 -->

HIKMICRO Analyzer Client • Release Notes

VIRUS INFECTION, OR OTHER INTERNET SECURITY RISKS; HOWEVER,
HIKMICRO WILL PROVIDE TIMELY TECHNICAL SUPPORT IF REQUIRED.

YOU AGREE TO USE THIS PRODUCT IN COMPLIANCE WITH ALL
APPLICABLE LAWS, AND YOU ARE SOLELY RESPONSIBLE FOR ENSURING
THAT YOUR USE CONFORMS TO THE APPLICABLE LAW. ESPECIALLY, YOU
ARE RESPONSIBLE, FOR USING THIS PRODUCT IN A MANNER THAT DOES
NOT INFRINGE ON THE RIGHTS OF THIRD PARTIES, INCLUDING WITHOUT
LIMITATION, RIGHTS OF PUBLICITY, INTELLECTUAL PROPERTY RIGHTS,
OR DATA PROTECTION AND OTHER PRIVACY RIGHTS. YOU SHALL NOT
USE THIS PRODUCT FOR ANY PROHIBITED END-USES, INCLUDING THE
DEVELOPMENT OR PRODUCTION OF WEAPONS OF MASS DESTRUCTION,
THE DEVELOPMENT OR PRODUCTION OF CHEMICAL OR BIOLOGICAL
WEAPONS, ANY ACTIVITIES IN THE CONTEXT RELATED TO ANY NUCLEAR
EXPLOSIVE OR UNSAFE NUCLEAR FUEL-CYCLE, OR IN SUPPORT OF
HUMAN RIGHTS ABUSES.

IN THE EVENT OF ANY CONFLICTS BETWEEN THIS MANUAL AND THE
APPLICABLE LAW, THE LATTER PREVAILS.

24

<!-- p. 25 -->


