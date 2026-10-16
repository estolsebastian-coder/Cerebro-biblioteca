---
type: libro
title: "Agisoft Metashape User Manual - Professional Edition, Version 1.5"
author: ""
categoria: "Técnicas avanzadas de apoyo al levantamiento. Topografía, fotogrametría y escáner láser (optativa)"
paginas: 130
extraccion: "texto (OCR pendiente)"
fuente: "local:D:/UPV/MCPA/Asignaturas/Técnicas avanzadas de apoyo al levantamiento. Topografía, fotogrametría y escáner láser (optativa)/Bibliografía/manual metashape-pro_1_5_en.pdf"
convertido: 2026-10-16
---

# Agisoft Metashape User Manual - Professional Edition, Version 1.5

> Texto extraído de `Técnicas avanzadas de apoyo al levantamiento. Topografía, fotogrametría y escáner láser (optativa)\Bibliografía\manual metashape-pro_1_5_en.pdf` (130 páginas, texto (OCR pendiente)). El PDF original está en el disco D: (UPV\MCPA\Asignaturas); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Agisoft Metashape User Manual
Professional Edition, Version 1.5

<!-- p. 2 -->

Agisoft Metashape User Manual: Professional Edition, Version 1.5

Publication date 2018
Copyright © 2018 Agisoft LLC

<!-- p. 3 -->

Table of Contents

Overview .......................................................................................................................... v
How it works ............................................................................................................. v
About the manual ....................................................................................................... v
\1. Installation and Activation ................................................................................................ 1
System requirements ................................................................................................... 1
GPU acceleration ........................................................................................................ 1
Installation procedure .................................................................................................. 2
Restrictions of the Demo mode ..................................................................................... 3
Activation procedure ................................................................................................... 3
Floating licenses ......................................................................................................... 5
\2. Capturing scenarios ......................................................................................................... 8
Equipment ................................................................................................................. 8
Camera settings .......................................................................................................... 8
Object/scene requirements ............................................................................................ 8
Image preprocessing ................................................................................................... 8
Capturing scenarios ..................................................................................................... 9
Restrictions .............................................................................................................. 10
Lens calibration ........................................................................................................ 11
\3. General workflow ......................................................................................................... 14
Preferences settings ................................................................................................... 14
Loading photos ......................................................................................................... 15
Aligning photos ........................................................................................................ 19
Building dense point cloud ......................................................................................... 22
Building mesh .......................................................................................................... 23
Building model texture .............................................................................................. 25
Building tiled model .................................................................................................. 28
Building digital elevation model .................................................................................. 30
Building orthomosaic ................................................................................................. 31
Saving intermediate results ......................................................................................... 34
Exporting results ....................................................................................................... 35
\4. Referencing .................................................................................................................. 47
Camera calibration .................................................................................................... 47
Setting coordinate system ........................................................................................... 50
Optimization ............................................................................................................ 58
Working with coded and non-coded targets ................................................................... 61
\5. Measurements ............................................................................................................... 63
Performing measurements on 3D model ........................................................................ 63
Performing measurements on DEM .............................................................................. 64
Vegetation indices calculation ..................................................................................... 66
\6. Editing ........................................................................................................................ 70
Using masks ............................................................................................................ 70
Editing point cloud ................................................................................................... 74
Classifying dense cloud points .................................................................................... 76
Editing model geometry ............................................................................................. 78
Shapes .................................................................................................................... 82
Orthomosaic seamlines editing .................................................................................... 83
\7. Automation .................................................................................................................. 85
Using chunks ........................................................................................................... 85
4D processing .......................................................................................................... 89
Python scripting ........................................................................................................ 91
\8. Distributed processing .................................................................................................... 93

iii

<!-- p. 4 -->

Agisoft Metashape User Manual

Local network processing ........................................................................................... 93
Cloud processing ...................................................................................................... 97
A. Graphical user interface ................................................................................................. 98
Application window .................................................................................................. 98
Menu commands ..................................................................................................... 103
Toolbar buttons ....................................................................................................... 112
Hot keys ................................................................................................................ 115
B. Supported formats ....................................................................................................... 118
Images .................................................................................................................. 118
Camera calibration .................................................................................................. 118
Camera flight log .................................................................................................... 118
GCP locations ........................................................................................................ 119
Interior and exterior camera orientation parameters ........................................................ 119
Tie points .............................................................................................................. 119
Sparse/dense point cloud .......................................................................................... 120
Mesh model ........................................................................................................... 120
Texture .................................................................................................................. 120
Orthomosaic ........................................................................................................... 121
Digital elevation model (DSM/DTM) .......................................................................... 121
Tiled models .......................................................................................................... 121
Shapes and contours ................................................................................................ 122
C. Camera models ........................................................................................................... 123
Frame cameras ........................................................................................................ 123
Fisheye cameras ...................................................................................................... 123
Spherical cameras (equirectangular projection) ............................................................. 124
Spherical cameras (cylindrical projection) .................................................................... 124

iv

<!-- p. 5 -->

Overview

Agisoft Metashape is an advanced image-based 3D modeling solution aimed at creating professional
quality 3D content from still images. Based on the latest multi-view 3D reconstruction technology, it
operates with arbitrary images and is efficient in both controlled and uncontrolled conditions. Photos can
be taken from any position, providing that the object to be reconstructed is visible on at least two photos.
Both image alignment and 3D model reconstruction are fully automated.
How it works

Generally the final goal of photographs processing with Metashape is to build 3D surface, orthomosaic
and DEM. The processing procedure includes four main stages.

\1. The first stage is camera alignment. At this stage Metashape searches for common points on photographs
and matches them, as well as it finds the position of the camera for each picture and refines camera
calibration parameters. As a result a sparse point cloud and a set of camera positions are formed.

The sparse point cloud represents the results of photo alignment and will not be directly used in further
processing (except for the sparse point cloud based reconstruction method, that is not recommended).
However it can be exported for further usage in external programs. For instance, the sparse point cloud
model can be used in a 3D editor as a reference.

On the contrary, the set of camera positions is required for further 3D surface reconstruction by
Metashape.

\2. The next stage is generating dense point cloud, that is built by Metashape based on the estimated camera
positions and pictures themselves. Dense point cloud may be edited and classified prior to export or
proceeding to the next stage.

\3. The third stage is generation of a surface: Mesh and/or DEM. 3D polygonal mesh model represents
the object surface based on the dense or sparse point cloud, this type of surface representation is not
always required, so the user may choose to skip mesh model generation step. Digital Elevation Model
(DEM) can be built in Geografic, Planar or Cylindrical projections according to the user's choice. If
the dense point cloud had been classified on the previous stage - it is possible to use particular point
classes for DEM generation.

\4. After the surface is reconstructed, it can be textured (relevant for mesh model only) or an Orthomosaic
can be generated. Orthomosaic is projected on a surface of user's choice: DEM or Mesh model (if it
had been generated for the project).
About the manual

Basically, the sequence of actions described above covers most of the data processing needs. All these
operations are carried out automatically according to the parameters set by user. Instructions on how to
get through these operations and descriptions of the parameters controlling each step are given in the
corresponding sections of the Chapter 3, General workflow chapter of the manual.

In some cases, however, additional actions may be required to get the desired results. In some capturing
scenarios masking of certain regions of the photos may be required to exclude them from the calculations.
Application of masks in Metashape processing workflow as well as editing options available are described
in Chapter 6, Editing. Camera calibration issues are discussed in Chapter 4, Referencing, that also
describes functionality to optimize camera alignment results and provides guidance on model referencing.

v

<!-- p. 6 -->

Overview

A referenced model, be it a mesh or a DEM serves as a ground for measurements. Area, volume, profile
measurement procedures are tackled in Chapter 5, Measurements, which also includes information on
vegetation indices calculations. While Chapter 7, Automation describes opportunities to save up on manual
intervention to the processing workflow, Local network processing presents guidelines on how to organize
distributed processing of the imagery data on several nodes.

It can take up quite a long time to reconstruct a 3D model. Metashape allows to export obtained results
and save intermediate data in a form of project files at any stage of the process. If you are not familiar with
the concept of projects, its brief description is given at the end of the Chapter 3, General workflow.

In the manual you can also find instructions on the Metashape installation and activation procedures and
basic rules for taking "good" photographs, i.e. pictures that provide most necessary information for 3D
reconstruction. For the information refer to Chapter 1, Installation and Activation and Chapter 2, Capturing
scenarios.

vi

<!-- p. 7 -->

Chapter 1. Installation and Activation
System requirements

Minimal configuration

• Windows XP or later (32 or 64 bit), Mac OS X Mountain Lion or later, Debian/Ubuntu with GLIBC
2.13+ (64 bit)

• Intel Core 2 Duo processor or equivalent

• 4 GB of RAM

Recommended configuration

• Windows 7 SP 1 or later (64 bit), Mac OS X Mountain Lion or later, Debian/Ubuntu with GLIBC 2.13+
(64 bit)

• Intel Core i7 or AMD Ryzen 7 processor

• Discrete NVIDIA or AMD GPU

• 32 GB of RAM

The number of photos that can be processed by Metashape depends on the available RAM and
reconstruction parameters used. Assuming that a single photo resolution is of the order of 10 MPix, 4 GB
RAM is sufficient to make a model based on 30 to 50 photos. 16 GB RAM will allow to process up to
300-400 photographs.
GPU acceleration

Metashape supports accelerated image matching, depth maps reconstruction, depth maps based mesh and
tiled model generation and photoconsistent mesh refinement operation due to the graphics hardware (GPU)
exploiting.

NVidia
GeForce GTX 400 series and later with CUDA support.

ATI
Radeon HD 6000 series and later with OpenCL 1.1 support.

Metashape is likely to be able to utilize processing power of any CUDA enabled device with compute
capability 2.0 and higher or OpenCL 1.1 and higher enabled device with SPIR support for stages specified
above, provided that CUDA/OpenCL drivers for the device are properly installed. However, because of
the large number of various combinations of video chips, driver versions and operating systems, Agisoft
is unable to test and guarantee Metashape's compatibility with every device and on every platform.

The processing performance of the GPU device is mainly related to the number of CUDA cores for
NVIDIA video chips and the number of shader processor units for AMD and Intel video chips. Additionally
depth maps based mesh and tiled model reconstruction as well as photoconsistent mesh refinement
operations would benefit from larger amount of VRAM available.

1

<!-- p. 8 -->

Installation and Activation

The table below lists currently supported devices (on Windows platform only). Agisoft will pay particular
attention to possible problems with Metashape running on these devices.

Table 1.1. Supported Desktop GPUs on Windows platform

NVIDIA AMD
GeForce RTX 2080 Ti Radeon RX Vega 64
Quadro P6000 Radeon RX Vega 56
Tesla V100 Radeon RX 580
Tesla M60 FirePro W9100
Quadro M6000 Radeon R9 390x
GeForce TITAN X Radeon R9 290x
GeForce GTX 1080 Ti Radeon HD 7970
GeForce GTX TITAN X Radeon HD 6970
GeForce GTX 980 Ti Radeon HD 6950
GeForce GTX TITAN Radeon HD 6870
GeForce GTX 780
GeForce GTX 680
GeForce GTX 580
GeForce GTX 570
GeForce GTX 560
GeForce GTX 480

Although Metashape is supposed to be able to utilize other compatible GPU models and being run under
a different operating system, Agisoft does not guarantee that it will work correctly. However, all GPU-
based processing issues should be reported to Agisoft support team for more detailed investigation.
Note

• Use CPU enable flag to allow calculations both on CPU and GPU for GPU-supported tasks.
However if at least one powerful discrete GPU is used it is recommended to disable CPU flag
for stable and rapid processing.

• Using GPU acceleration with mobile or integrated graphics video chips is not recommended
because of the low performance of such GPUs.

• CUDA supported devices on Mac OS X may require to install CUDA drivers from official web-
site first: http://www.nvidia.com/object/mac-driver-archive.html.

Due to lack of CUDA support on certain Mac OS X versions Metashape will automatically switch
to OpenCL implementation for GPU-based processing on NVIDIA graphic devices.
Installation procedure
Installing Metashape on Microsoft Windows

To install Metashape on Microsoft Windows simply run the downloaded msi file and follow the
instructions.

2

<!-- p. 9 -->

Installation and Activation

Installing Metashape on Mac OS X

Open the downloaded dmg image and drag Metashape application bundle to the desired location on your
hard drive. Do not run Metashape directly from the dmg image to avoid issues related to the license
activation.
Installing Metashape on Debian/Ubuntu

Unpack the downloaded archive with a program distribution kit to the desired location on your hard drive.
Start Metashape by running metashape.sh script from the program folder.
Restrictions of the Demo mode

Once Metashape is downloaded and installed on your computer you can run it either in the Demo mode
or in the full function mode. On every start until you enter a serial number it will show a registration
box offering two options: (1) use Metashape in the Demo mode or (2) enter a serial number to confirm
the purchase. The first choice is set by default, so if you are still exploring Metashape click the Continue
button and Metashape will start in the Demo mode.

The employment of Metashape in the Demo mode is not time limited. Several functions, however, are not
available in the Demo mode. These functions are the following:

• saving the project;

• build tiled model;

• build orthomosaic;

• build DEM;

• DEM and orthomosaic related features (such as vegetation index calculation, DEM-based
measurements);

• some Python API commands;

• all export features, including exporting reconstruction results (you can only view a 3D model on the
screen);

• using network and cloud processing features.

To use Metashape in the full function mode you have to purchase it. On purchasing you will get the serial
number to enter into the registration box on starting Metashape. Once the serial number is entered the
registration box will not appear again and you will get full access to all functions of the program.
Activation procedure
Metashape node-locked license activation

The Stand-Alone license for Metashape software is node-locked. Node-locked license files are unique for
each computer, and are tied to the system hardware. If you are to replace major system components or
re-install operational system, you should deactivate the software first and then activate it on the renewed
system.

3

<!-- p. 10 -->

Installation and Activation

Note

• To deactivate the license use Deactivate button in Help Menu -> Activate Product dialog or
argument --deactivate in the command line (terminal) to Metashape executable.

• Uninstalling Metashape software does not deactivate the license automatically. If you have
uninstalled the software before deactivating it, please re-install Metashape and run deactivation
procedure, as described above.

Metashape software requires license key (a digital code) to be activated. First of all, make sure that you
have a valid license key or a trial code at hand. Standard activation procedure, which allows to activate the
product in the means of seconds, requires the machine to be connected to the Internet. If it is your case,
please follow the online activation procedure as described below. In case the system cannot be connected
to the Internet, please opt for the offline activation procedure, which is also described in this section of
the manual.

Online Activation Procedure - To activate Metashape on a machine with Internet
connection

\1. Launch Metashape software, previously installed on your machine, and go to Help menu for Activate
product... command.

\2. In Activation dialog insert license key according to the suggested 5 digit blocks structure. Please
note that license codes never include zero digit - only letter "O".

\3. If the license code has been input correctly, then the OK button will become active. Click on it to
complete the activation procedure. If the button is still grayed out, please make sure that the key you
are using is meant for the product you are trying to activate: a license key for the Standard Edition,
for example, will not activate the Professional Edition.

Offline Activation Procedure - To activate Metashape on a machine with NO
Internet connection

\1. Launch Metashape software, previously installed on your machine, and go to Help menu for Activate
product... command.

\2. In Activation dialog insert license key according to the suggested 5 digit blocks structure. Please
note that license codes never include zero digit - only letter "O". Click OK button.

\3. Click Save Activation Request button. Browse to the destination folder for the activation_request.act
file in the Save as dialog, type in the file name and click Save button.

\4. Send the file saved at previous step to support@agisoft.com. Agisoft support team will process your
activation request and send the special license file to your e-mail with the instructions to complete
the activation process.

If you would like to activate/deactivate Metashape software in headless mode, please see the list of relevant
commands below.

• metashape --activate license_key

• metashape --deactivate

• metashape --activate-offline license_key file_name.act

4

<!-- p. 11 -->

Installation and Activation

• metashape --deactivate-offline file_name.act

Run "metashape --help" to see the complete list of the commands available.
Floating licenses

Metashape software can be used under floating license conditions. A floating license allows to install the
software on an unlimited number of machines, which are connected to a server network. However, at any
one time, Metashape can only run on the maximum number of computers for which licenses have been
purchased. Since Metashape can be installed on more systems than the number of licenses purchased, this
enables the licensee to efficiently share the product across the organization.

A software utility called Floating License Server (FLS) deployed on the server machine issues licenses
to client machines, up to the number of floating licenses purchased. If all floating licenses are in use, no
more computers can run Metashape until a license is returned to the FLS, i.e. until Metashape process is
finished on one of the machines.

Metashape floating licenses are borrowable. A borrowed license can be used on a machine disconnected
from the server network for a certain period (up to 30 days).

Floating license activation procedure is performed on the server machine and includes two steps

• FLS installation and activation

• Floating license activation

Thus, to activate a floating license you will need 3 components:

• FLS archive (to be downloaded from the link provided upon license purchase)

• FLS activation key (to be provided on purchasing a floating license)

• Floating license activation key (to be provided on purchasing a floating license), and the number of
floating licenses associated with the key.
Note

• FLS cannot be installed on a virtual machine.

To activate Floating License Server

\1. Unpack the FLS archive and run FLS utility (rlm/rlm.exe) on the server machine.

\2. Go to http://server_address:5054 to use web-interface of the license management system. Enter
Status section of the left hand side menu. Find "agisoft" line in the ISV Servers table. Click agisoft
button in ACTIVATE column of the table.

\3. Set the following values for the parameters on the Activate/Deactivate Alternate Server Hostid
page. ISV: agisoft, Activation Key: enter FLS activation key. Leave Deactivate? box unchecked.
Click Activate/Deactivate Alternate Server Hostid button.

\4. The FLS is successfully activated now.

\5. To complete the procedure, go to the folder where the FLS utility has been unpacked to and delete
mock license file - agisoft.lic.

5

<!-- p. 12 -->

Installation and Activation

\6. Return to web-interface of the license management system and go to Reread/Restart Servers section
of the left hand side menu. Select "-all-" from the dropdown list of the ISV field. Click REREAD/
RESTART button.

\7. Now the FLS activation procedure is completed.

The next step is activation of the floating license itself.

To activate a floating license

\1. Go to http://server_address:5054 to use web-interface of the license management system. Enter
Activate License section of the left hand side menu. Click BEGIN License Activation button on
License Activation page.

\2. Do not change the suggested value of the ISV activation website parameter. Click Next.

\3. On step 2 of License activation procedure set ISV parameter to "agisoft" value and enter Floating
license activation key into the License activation key textbox. Click Next.

\4. Go to the folder where the FLS utility has been unpacked to, open rlm_agisoft_FLS-activation-key.lic
file. Copy string "license=server-serial-number" from the first line of the file and enter the data into
the License Server or Node-lock hostid: textbox on the 3d step of the License activation procedure.

\5. Indicate the number of floating licenses to be activated in the License count (for floating licenses)
field. The number should not excess the total amount of floating licenses associated with the floating
license activation key. Click Next.

\6. On step 4 indicate the name of the license file to be created. Click Next.

\7. On step 5 check Activation Request Data and if everything is correct, click REQUEST LICENSE
button.

\8. Click (Re)Start License Server. Select "agisoft" from the dropdown list of the ISV field. Click
REREAD/RESTART button.

\9. Floating license activation procedure is completed. You can run Metashape on the client machines
connected to the server.

To run Metashape on a client machine, where the software has been installed, the client machine should
have network connection to the server, where FLS has been deployed. In case the connection is not via
a local network, then a specially prepared *.lic file should be properly placed to the Metashape folder on
the client machine. The data in the file should be the following string: "HOST FLS_address". In case the
server uses a port different from the standard 5053 one, then the string should be: "HOST FLS_address
any the_port_number".

To transfer the Floating License Server

\1. Deactivate FLS in web-interface of the license management system: http://server_address:5054.
Enter Status section of the left hand side menu. Find "agisoft" line in the ISV Servers table. Click
agisoft button in ACTIVATE column of the table. Set the following values for the parameters on
the Activate/Deactivate Alternate Server Hostid page. ISV: agisoft, check Deactivate? box. Click
Activate/Deactivate Alternate Server Hostid button.

\2. Activate FLS on a new server following steps 1-3 from the Floating License Server activation
procedure described above.

6

<!-- p. 13 -->

Installation and Activation

\3. Copy all floating license files (i.e. all *.lic files but for the rlm_agisoft_license server activation
key.lic) from the original server machine to the new server to the folder where floating license server
has been unpacked to.

\4. Modify the server host name in the first line of the copied floating license files to the name of the
new server machine.

\5. Follow steps 5-6 from the Floating License Server activation procedure described above.

There is no need to perform Floating license activation procedure since the floating license is already
activated. Metashape can be run on the client machines connected to the new server.

To borrow a floating license

\1. Connect the machine you would like to borrow the license for to the server machine and make sure
that there is a spare floating license in the server pool.

\2. Run Metashape software on the machine. Go to Help -> Activate Product... menu.

\3. Click Borrow License button in the Metashape Activation dialog. Set the number of days you would
like to borrow the license for and click OK button. The number of days should not exceed 30.

\4. Now the machine can be disconnected from the server network, with Metashape being kept activated
on it.

\5. To return the borrowed license connect the computer to the license server network, start Metashape
and click Return License button in the Help menu -> Activate Product... dialog. Otherwise the license
will be automatically returned to the server pool after the borrowing period is over.

7

<!-- p. 14 -->

Chapter 2. Capturing scenarios

Photographs suitable for 3D model reconstruction in Metashape can be taken by any digital camera (both
metric and non-metric), as long as you follow some specific capturing guidelines. This section explains
general principles of taking and selecting pictures that provide the most appropriate data for 3D model
generation.

IMPORTANT! Make sure you have studied the following rules and read the list of restrictions before you
get out for shooting photographs.
Equipment

• Use a digital camera with reasonably high resolution (5 MPix or more).

• Avoid ultra-wide angle and fisheye lenses. The best choice is 50 mm focal length (35 mm film
equivalent) lenses. It is recommended to use focal length from 20 to 80 mm interval in 35mm equivalent.
If a data set was captured with fisheye lens, appropriate camera sensor type should be selected in
Metashape Camera Calibration dialog prior to processing.

• Fixed lenses are preferred. If zoom lenses are used - focal length should be set either to maximal or to
minimal value during the entire shooting session for more stable results, for intermediate focal lengths
separate camera calibration groups should be used.
Camera settings

• Using RAW data losslessly converted to the TIFF files is preferred, since JPG compression may induce
unwanted noise to the images.

• Take images at maximal possible resolution.

• ISO should be set to the lowest value, otherwise high ISO values will induce additional noise to images.

• Aperture value should be high enough to result in sufficient focal depth: it is important to capture sharp,
not blurred photos.

• Shutter speed should not be too slow, otherwise blur can occur due to slight movements.
Object/scene requirements

• Avoid not textured, shiny, highly reflective or transparent objects.

• If still have to, shoot shiny objects under a cloudy sky.

• Avoid unwanted foregrounds.

• Avoid moving objects within the scene to be reconstructed.

• Avoid absolutely flat objects or scenes.
Image preprocessing

• Metashape operates with the original images. So do not crop or geometrically transform, i.e. resize or
rotate, the images.

8

<!-- p. 15 -->

Capturing scenarios

Capturing scenarios

Generally, spending some time planning your shot session might be very useful.

• Number of photos: more than required is better than not enough.

• Number of "blind-zones" should be minimized since Metashape is able to reconstruct only geometry
visible from at least two cameras.

In case of aerial photography the overlap requirement can be put in the following figures: 60% of side
overlap + 80% of forward overlap.

• Each photo should effectively use the frame size: object of interest should take up the maximum area.
In some cases portrait camera orientation should be used.

• Do not try to place full object in the image frame, if some parts are missing it is not a problem providing
that these parts appear on other images.

• Good lighting is required to achieve better quality of the results, yet blinks should be avoided. It is
recommended to remove sources of light from camera fields of view. Avoid using flash.

• If you are planning to carry out any measurements based on the reconstructed model, do not forget to
locate at least two markers with a known distance between them on the object. Alternatively, you could
place a ruler within the shooting area.

• In case of aerial photography and demand to fulfill georeferencing task, even spread of ground control
points (GCPs) (at least 10 across the area to be reconstructed) is required to achieve results of highest
quality, both in terms of the geometrical precision and georeferencing accuracy. Yet, AgisoftMetashape
is able to complete the reconstruction and georeferencing tasks without GCPs, too.

The following figures represent advice on appropriate capturing scenarios:

Facade (Incorrect) Facade (Correct)

9

<!-- p. 16 -->

Capturing scenarios

Interior (Incorrect) Interior (Correct)

Isolated Object (Incorrect) Isolated Object (Correct)

Restrictions

In some cases it might be very difficult or even impossible to build a correct 3D model from a set of
pictures. A short list of typical reasons for photographs unsuitability is given below.
Modifications of photographs

Metashape can process only unmodified photos as they were taken by a digital photo camera. Processing
the photos which were manually cropped or geometrically warped is likely to fail or to produce highly
inaccurate results. Photometric modifications do not affect reconstruction results.
Lack of EXIF data

Metashape calculates initial values of sensor pixel size and focal length parameters based on the EXIF
data. The better initial approximation of the parameter values is, the more accurate autocalibration of the
camera can be performed. Therefore, reliable EXIF data is important for accurate reconstruction results.
However 3D scene can also be reconstructed in the absence of the EXIF data. In this case Metashape
assumes that focal length in 35 mm equivalent equals to 50 mm and tries to align the photos in accordance
with this assumption. If the correct focal length value differs significantly from 50 mm, the alignment can
give incorrect results or even fail. In such cases it is required to specify initial camera calibration manually.

The details of necessary EXIF tags and instructions for manual setting of the calibration parameters are
given in the Camera calibration section.

10

<!-- p. 17 -->

Capturing scenarios

Lens distortion

The distortion of the lenses used to capture the photos should be well simulated with the camera model
used in the software. Generally, Brown's distortion model implemented in Metashape works well for frame
cameras. However, since fisheye/ ultra-wide angle lenses are poorly simulated by the mentioned distortion
model, it is crucial to choose proper camera type in Camera Calibration dialog prior to processing of such
data - the software will switch to the appropriate distortion model.
Lens calibration

It is possible to use Metashape for automatic lens calibration. Metashape uses LCD screen as a calibration
target (optionally it is possible to use a printed chessboard pattern, providing that it is flat and all its cells are
squares). Lens calibration procedure supports estimation of the full camera calibration matrix, including
non-linear distortion coefficients.
Note

• Lens calibration procedure can usually be skipped in common workflow, as Metashape calculates
the calibration parameters automatically during Align Photos process. However, if the alignment
results are unstable, for example, due to the lack of the tie points between the images, the lens
calibration may be useful.

The following camera calibration parameters can be estimated:

f
Focal length measured in pixels.

cx, cy
Principal point coordinates, i.e. coordinates of lens optical axis interception with sensor plane in pixels.

b1, b2
Affinity and Skew (non-orthogonality) transformation coefficients.

k1, k2, k3, k4
Radial distortion coefficients.

p1, p2, p3, p4
Tangential distortion coefficients.

Before using lens calibration tool a set of photos of calibration pattern should be loaded in Metashape.

To capture photos of the calibration pattern:

\1. Select Show Chessboard... command from the Lens submenu in the Tools menu to display the
calibration pattern.

\2. Use mouse scroll wheel to zoom in/out the calibration pattern. Scale the calibration pattern so that
the number of squares on each side of the screen would exceed 10.

\3. Capture a series of photos of the displayed calibration pattern with your camera from slightly different
angles, according to the guidelines, outlined below. Minimum number of photos for a given focal
length is 3.

\4. If you are calibrating zoom lens, change the focal length of your lens and repeat the previous step
for other focal length settings.

11

<!-- p. 18 -->

Capturing scenarios

\5. Click anywhere on the calibration pattern or press Escape button to return to the program.

\6. Upload the captured photos to the computer.

When capturing photos of the calibration pattern, try to fulfill the following guidelines:

• Make sure that the focal length keeps constant throughout the session (in case of zoom lens).

• Avoid glare on the photos. Move the light sources away if required.

• Preferably, the whole area of the photos should be covered by calibration pattern. Move the camera
closer to the LCD screen if required.

To load photos of the calibration pattern:

\1. Create new chunk using Add Chunk toolbar button on the Workspace pane or selecting Add
Chunk command from the Workspace context menu (available by right-clicking on the root element
on the Workspace pane). See information on using chunks in Using chunks section.

\2. Select Add Photos... command from the Workflow menu.

\3. In the Open dialog box, browse to the folder, containing the photos, and select files to be processed.
Then click Open button.

\4. Loaded photos will appear in the Photos pane.
Note

• You can open any photo by double clicking on its thumbnail in the Photos pane. To obtain good
calibration, the photos should be reasonably sharp, with crisp boundaries between cells.

• If you have loaded some unwanted photos, you can easily remove them at any time.

• Before calibrating fisheye lens you need to set the corresponding Camera Type in the Camera
Calibration... dialog available from the Tools menu. See information on other camera calibration
settings in Camera calibration section.

To calibrate camera lens

\1. Select Calibrate Lens... command from the Lens submenu in the Tools menu.

\2. In the Calibrate Lens dialog box, select the desired calibration parameters. Click OK button when
done.

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click the Cancel button.

\4. The calibration results will appear on the Adjusted tab of the Camera Calibration... dialog available
from the Tools menu. The adjusted values can be saved to file by using Save button on the Adjusted
tab. The saved lens calibration data can later be used in another chunk or project, providing that the
same camera and lens is used.
Note

• After you have saved the calibration parameters for the lens, you may proceed with the workflow
steps in a separate chunk for the actual image set captured by the same camera and lens. To

12

<!-- p. 19 -->

Capturing scenarios

protect the calibration data from being refined during Align Photos process one should check Fix
calibration box on the Initial tab for the chunk with the data to be processed. In this case initial
calibration values will not be changed during Align Photos process.

After calibration is finished, you will be presented with the following information:

Detected chessboard corners are displayed on each photo (the photo can be opened by double clicking on
its name in the Photos pane). It is preferable when the majority of the corners were detected correctly. For
each detected corner the reprojection error between the detected corner position and estimated position
according to the calculated calibration is also displayed. The errors are scaled x20 times for display.

13

<!-- p. 20 -->

Chapter 3. General workflow

Processing of images with Metashape includes the following main steps:

• loading photos into Metashape;

• inspecting loaded images, removing unnecessary images;

• aligning photos;

• building dense point cloud;

• building mesh (3D polygonal model);

• generating texture;

• building tiled model;

• building digital elevation model;

• building orthomosaic;

• exporting results.

If you are using Metashape in the full function (not the Demo) mode, intermediate results of the image
processing can be saved at any stage in the form of project files and can be used later. The concept of
projects and project files is briefly explained in the Saving intermediate results section.

The list above represents all the necessary steps involved in the construction of a textured 3D model ,
DEM and orthomosaic from your photos. Some additional tools, which you may find to be useful, are
described in the successive chapters.
Preferences settings

Before starting a project with Metashape it is recommended to adjust the program settings for your needs.
In Preferences dialog (General Tab) available through the Tools menu you can indicate the path to the
Metashape log file to be shared with the Agisoft support team in case you face any problem during the
processing. Here you can also change GUI language to the one that is most convenient for you. The options
are: English, Chinese, French, German, Italian, Japanese, Korean, Portuguese, Russian, Spanish.

Switch Theme in case you have preferences between Dark or Light program GUI or leave it as Classic for
the simplest view. Shortcuts can be adjusted for your convenience on the General tab as well.

On the GPU Tab you need to make sure that all discrete GPU devices detected by the program are checked.
Metashape exploits GPU processing power that speeds up the process significantly. However, Agisoft
does not recommend to use integrated graphic card adapters due to their possible unstable work under
heavy load. If you have decided to switch on GPUs to boost the data processing with Metashape, it is
recommended to uncheck "Use CPU when performing GPU accelerated processing" option, providing that
at least one discrete GPU is utilized for processing.

Advanced tab allows you to switch on such advanced features like rich Python console, for example.
Furthermore, you can enable loading of extra camera data from XMP (camera calibration, camera
orientation angles, camera location accuracy, GPS/INS offset).

Keep depth maps option can be beneficial in terms of saving up the processing time, in case there might
be a need to rebuild dense point cloud, once generated, for a smaller part of the scene, or if both mesh and
dense cloud are based on the same quality depth maps.

14

<!-- p. 21 -->

General workflow

Fine-level task subdivision option is useful in cases when large datasets are to be processed. Enabled option
provides internal splitting of some tasks to the sub-jobs, thus allowing to reduce the memory consumption
during the processing. The tasks that are supported for fine-level distribution are the following: Match
Photos, Align Cameras, Build Depth Maps, Build Dense Cloud, Build Tiled Model, Build DEM, Build
Orthomosaic and Classify Points.

Metashape allows for incremental image alignment, which may be useful in case of some data missing in
the initially aligned project. If this may be the case, you should switch on the Keep key points option on
the Advanced tab of the Preferences dialog before you start the processing of the data.
Loading photos

Before starting any operation it is necessary to point out what photos will be used as a source for 3D
reconstruction. In fact, photographs themselves are not loaded into Metashape until they are needed. So,
when you "load photos" you only indicate photographs that will be used for further processing.

To load a set of photos

\1. Select Add Photos... command from the Workflow menu or click Add Photos toolbar button on
the Workspace pane.

\2. In the Add Photos dialog box browse to the folder containing the images and select files to be
processed. Then click Open button.

\3. Selected photos will appear on the Workspace pane.
Note

• Metashape accepts the following image formats: JPEG, TIFF, DNG, PNG, OpenEXR, BMP,
TARGA, PPM, PGM, SEQ, ARA (thermal images) and JPEG Multi-Picture Format (MPO).
Photos in any other format will not be shown in the Add Photos dialog box. To work with such
photos you will need to convert them in one of the supported formats.

If you have loaded some unwanted photos, you can easily remove them at any moment.

To remove unwanted photos

\1. On the Workspace pane select the photos to be removed.

\2. Right-click on the selected photos and choose Remove Items command from the opened context
menu, or click Remove Items toolbar button on the Workspace pane. The selected photos will
be removed from the working set.
Camera groups

If all the photos or a subset of photos were captured from one camera position - camera station, for
Metashape to process them correctly it is obligatory to move those photos to a camera group and mark
the group as Camera Station. It is important that for all the photos in a Camera Station group distances
between camera centers were negligibly small compared to the camera-object minimal distance. 3D model
reconstruction will require at least two camera stations with overlapping photos to be present in a chunk.
However, it is possible to export panoramic picture for the data captured from only one camera station.
Refer to Exporting results section for guidance on panorama export.

15

<!-- p. 22 -->

General workflow

Alternatively, camera group structure can be used to manipulate the image data in a chunk easily, e.g. to
apply Disable/Enable functions to all the cameras in a group at once.

To move photos to a camera group

\1. On the Workspace pane (or Photos pane) select the photos to be moved.

\2. Right-click on the selected photos and choose Move Cameras - New Camera Group command from
the opened context menu.

\3. A new group will be added to the active chunk structure and selected photos will be moved to that
group.

\4. Alternatively selected photos can be moved to a camera group created earlier using Move Cameras
\- Camera Group - Group_name command from the context menu.

To mark group as camera station, right click on the camera group name and select Set Group Type
command from the context menu.
Inspecting loaded photos

Loaded photos are displayed on the Workspace pane along with flags reflecting their status.

The following flags can appear next to the photo name:

NC (Not calibrated)
Notifies that the EXIF data available is not sufficient to estimate the camera focal length. In this case
Metashape assumes that the corresponding photo was taken using 50mm lens (35mm film equivalent).
If the actual focal length differs significantly from this value, manual calibration may be required.
More details on manual camera calibration can be found in the Camera calibration section.

NA (Not aligned)
Notifies that external camera orientation parameters have not been estimated for the current photo yet.

Images loaded to Metashape will not be aligned until you perform the next step - photos alignment.

Notifies that Camera Station type was assigned to the group.
Multispectral imagery

Metashape supports processing of multispectral images saved as multichannel (single page) TIFF files.
The main processing stages for multispectral images are performed based on the primary channel, which
can be selected by the user. During orthomosaic export, all spectral bands are processed together to form
a multispectral orthomosaic with the same bands as in source images.

The overall procedure for multispectral imagery processing does not differ from the usual procedure for
normal photos, except the additional primary channel selection step performed after adding images to the
project. For the best results it is recommended to select the spectral band which is sharp and as much
detailed as possible.

To select primary channel

\1. Add multispectral images to the project using Add Photos... command from the Workflow menu or
Add Photos toolbar button.

16

<!-- p. 23 -->

General workflow

\2. Select Set Primary Channel... command from the chunk context menu in the Workspace pane.

\3. In the Set Primary Channel dialog select the channel to be used as primary and click OK button.
Display of images in Metashape window will be updated according to the primary channel selection.
Note

• Set Primary Channel... command is available for RGB images as well. You can either indicate
only one channel to be used as the basis for photogrammetric processing or leave the parameter
value as Default for all three channels to be used in processing.

Multispectral orthomosaic export is supported in GeoTIFF format only. When exporting in other formats,
only primary channel will be saved.
Rigid camera rigs

Metashape supports processing of multispectral datasets captured with multiple synchronized cameras
operating in different spectral ranges. In this case multiple images (planes) are available for each position
and Metashape will estimate separate calibration for each plane as well as their relative orientation within
camera rig.

The default assumption is that synchronized cameras have the same position in space. In case distance
between the cameras cannot be neglected, it is possible for Metashape to calculate relative camera offset.

To calculate relative camera offset for synchronized cameras

\1. Select Camera Calibration command from the Tools menu.

\2. Switch to Slave offset tab.

\3. Check Fit location option.

\4. The distance for the active camera will be calculated in relevance to master camera - the camera
whose images were loaded to the project first of all.

To change master camera, you can use the corresponding command from the context menu of the camera
group displayed in the lefthand part of the Camera Calibration dialog.

Multiplane layout is formed at the moment of adding photos to the chunk. It will reflect the data layout
used to store image files. Therefore it is necessary to organize files on the disk appropriately in advance.
The following data layouts can be used with Metashape:

a. All image planes from each position are contained in a separate multilayer image. The number of
multilayer images is equal to the number of camera positions.

b. Corresponding planes from all camera positions are contained in a separate subfolder. The number of
subfolders is equal to the number of planes.

c. For a special case of MicaSense cameras (MicaSense RedEdge, Parrot Sequoia), no special layout
is required. In this case the arrangement of images into cameras and planes will be performed
automatically based on available meta data.

Once the data is properly organized, it can be loaded into Metashape to form multiplane cameras. The
exact procedure will depend on whether the multilayer layout (variant a ), multifolder layout (variant b )
or if MicaSense data is used.

17

<!-- p. 24 -->

General workflow

To create a chunk from multilayer images

\1. Select Add Photos... command from the Workflow menu or click Add Photos toolbar button.

\2. In the Add Photos dialog box browse to the folder containing multilayer images and select files to
be processed. Then click Open button.

\3. In the Add Photos dialog select the data layout "Create multispectral cameras from files as cameras".

\4. Created chunk with multispectral cameras will appear on the Workspace pane.

To create a chunk from multifolder layout

\1. Select Add Folder... command from the Workflow menu.

\2. In the Add Folder dialog box browse to the parent folder containing subfolders with images. Then
click Select Folder button.

\3. In the Add Photos dialog select the data layout "Create multispectral cameras from folders as bands"

\4. Created chunk with multispectral cameras will appear on the Workspace pane. The labels of the
multispectral cameras would be taken from the image filenames of the first image folder used.

To create a chunk from MicaSense data

\1. Select Add Photos... command from the Workflow menu or click Add Photos toolbar button.

\2. In the Add Photos dialog box browse to the folder containing MicaSense images and select files to
be processed. Then click Open button.

\3. In the Add Photos dialog select "Create multispectral cameras from files as bands".

\4. Created chunk with multispectral cameras will appear on the Workspace pane. The labels of the
multispectral cameras would be taken from the first band image filenames.

After chunk with multispectral cameras is created, it can be processed in the same way as normal chunks.
For these chunks additional parameters allowing to manipulate the data properly will be provided where
appropriate.
Video Data

Metashape allows for video data processing as well, which can be beneficial for quick inspection scenarios,
for example. The video is to be divided into frames which will be further used as source images for 3D
reconstruction.

To import a video file

\1. Select Import video command from the File menu.

\2. In the Import video dialog you can inspect the video and set the output folder for the frames.

\3. Set the filename pattern for the frames and indicate the frame extraction rate.

\4. Click OK button for the frames to be automatically extracted and saved to the designated folder. The
images extracted from the video will be automatically added to the active chunk.

18

<!-- p. 25 -->

General workflow

After the frames have been extracted you can follow standard processing workflow for the images.
Aligning photos

Once photos are loaded into Metashape, they need to be aligned. At this stage Metashape finds the camera
position and orientation for each photo and builds a sparse point cloud model.

To align a set of photos

\1. Select Align Photos... command from the Workflow menu.

\2. In the Align Photos dialog box select the desired alignment options. Click OK button when done.

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.

Alignment having been completed, computed camera positions and a sparse point cloud will be displayed.
You can inspect alignment results and remove incorrectly positioned photos, if any. To see the matches
between any two photos use View Matches... command from a photo context menu in the Photos pane.

Incorrectly positioned photos can be realigned.

To realign a subset of photos

\1. Reset alignment for incorrectly positioned cameras using Reset Camera Alignment command from
the photo context menu.

\2. Set markers (at least 4 per photo) on these photos and indicate their projections on at least two
photos from the already aligned subset. Metashape will consider these points to be true matches. (For
information on markers placement refer to the Setting coordinate system section).

\3. Select photos to be realigned and use Align Selected Cameras command from the photo context menu.

\4. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.

When the alignment step is completed, the point cloud and estimated camera positions can be exported
for processing with another software if needed.
Image quality

Poor input, e. g. vague photos, can influence alignment results badly. To help you to exclude poorly
focused images from processing Metashape suggests automatic image quality estimation feature. Images
with quality value of less than 0.5 units are recommended to be disabled and thus excluded from
photogrammetric processing, providing that the rest of the photos cover the whole scene to be
reconstructed. To disable a photo use Disable button from the Photos pane toolbar.

Metashape estimates image quality for each input image. The value of the parameter is calculated based
on the sharpness level of the most focused part of the picture.

To estimate image quality

\1. Switch to the detailed view in the Photos pane using Details command from the Change menu
on the Photos pane toolbar.

19

<!-- p. 26 -->

General workflow

\2. Select all photos to be analyzed on the Photos pane.

\3. Right button click on the selected photo(s) and choose Estimate Image Quality command from the
context menu.

\4. Once the analysis procedure is over, a figure indicating estimated image quality value will be
displayed in the Quality column on the Photos pane.
Alignment parameters

The following parameters control the photo alignment procedure and can be modified in the Align Photos
dialog box:

Accuracy
Higher accuracy settings help to obtain more accurate camera position estimates. Lower accuracy
settings can be used to get the rough camera positions in a shorter period of time.

While at High accuracy setting the software works with the photos of the original size, Medium setting
causes image downscaling by factor of 4 (2 times by each side), at Low accuracy source files are
downscaled by factor of 16, and Lowest value means further downscaling by 4 times more. Highest
accuracy setting upscales the image by factor of 4. Since tie point positions are estimated on the
basis of feature spots found on the source images, it may be meaningful to upscale a source photo
to accurately localize a tie point. However, Highest accuracy setting is recommended only for very
sharp image data and mostly for research purposes due to the corresponding processing being quite
time consuming.

Pair preselection
The alignment process of large photo sets can take a long time. A significant portion of this time period
is spent on matching of detected features across the photos. Image pair preselection option may speed
up this process due to selection of a subset of image pairs to be matched. In the Generic preselection
mode the overlapping pairs of photos are selected by matching photos using lower accuracy setting
first.

In the Reference preselection mode the overlapping pairs of photos are selected based on the
measured camera locations (if present). For oblique imagery it is necessary to set Ground altitude
value (average ground height in the same coordinate system which is set for camera coordinates data)
in the Settings dialog of the Reference pane to make the preselection procedure work efficiently.
Ground altitude information must be accompanied with yaw, pitch, roll data for cameras. Yaw, pitch,
roll data should be input in the Reference pane.

You can switch on both options to speed up the processing even more.

Reset current alignment
If this option is checked, all the tie, and key, and matching points will be discarded and the alignment
procedure will be started from the very beginning.

Additionally the following advanced parameters can be adjusted.

Key point limit
The number indicates upper limit of feature points on every image to be taken into account during
current processing stage. Using zero value allows Metashape to find as many key points as possible,
but it may result in a big number of less reliable points.

Tie point limit
The number indicates upper limit of matching points for every image. Using zero value doesn't apply
any tie point filtering.

20

<!-- p. 27 -->

General workflow

Apply mask to
If apply mask to key points option is selected, areas previously masked on the photos are excluded
from feature detection procedure. Apply mask to tie points option means that certain tie points are
excluded from alignment procedure. Effectively this implies that if some area is masked at least on a
single photo, relevant key points on the rest of the photos picturing the same area will be also ignored
during alignment procedure (a tie point is a set of key points which have been matched as projections
of the same 3D point on different images). This can be useful to be able to suppress background in
turntable shooting scenario with only one mask. For additional information on the usage of masks
please refer to the Using masks section.

Adaptive camera model fitting
This option enables automatic selection of camera parameters to be included into adjustment based on
their reliability estimates. For data sets with strong camera geometry, like images of a building taken
from all the sides around, including different levels, it helps to adjust more parameters during initial
camera alignment. For data sets with weak camera geometry , like a typical aerial data set, it helps
to prevent divergence of some parameters. For example, estimation of radial distortion parameters
for data sets with only small central parts covered by the object is very unreliable. When the option
is unchecked, Metashape will refine only the fixed set of parameters: focal length, principal point
position, three radial distortion coefficients (K1, K2, K3) and two tangential distortion coefficients
(P1, P2).
Note

• Tie point limit parameter allows to optimize performance for the task and does not generally
effect the quality of the further model. Recommended value is 4000. Too high or too low tie point
limit value may cause some parts of the dense point cloud model to be missed. The reason is that
Metashape generates depth maps only for pairs of photos for which number of matching points is
above certain limit. This limit equals to 100 matching points, unless moved up by the figure "10%
of the maximum number of matching points between the photo in question and other photos,
only matching points corresponding to the area within the bounding box being considered."

• The number of tie points can be reduced after the alignment process with Tie Points - Thin Point
Cloud command available from Tools menu. As a results sparse point cloud will be thinned, yet
the alignment will be kept unchanged.
Incremental image alignment

In case some extra images should be subaligned to the set of already aligned images, you can benefit
from incremental image alignment option. To make it possible, two rules must be followed: 1) the scene
environment should not have changed significantly (lighting conditions, etc); 2) do not forget to switch on
Keep key points option in the Preferences dialog, Advanced tab BEFORE the whole processing is started.

To subalign some extra images added to the chunk with already aligned set of
images

\1. Add extra photos to the active chunk using Add photos command from the Workflow menu.

\2. Open Align photos dialog from the Workflow menu.

\3. Set alignment parameters for the newly added photos. IMPORTANT! Uncheck Reset alignment
option.

\4. Click OK. Metashape will consider existing key points and try to match them with key points detected
on the newly added images.

21

<!-- p. 28 -->

General workflow

Point cloud generation based on imported camera data

Metashape supports import of external and internal camera orientation parameters. Thus, if precise camera
data is available for the project, it is possible to load them into Metashape along with the photos, to be
used as initial information for 3D reconstruction job.

To import external and internal camera parameters
\1. Select Import Cameras command from the File menu.

\2. Select the format of the file to be imported.

\3. Browse to the file and click Open button.

\4. The data will be loaded into the software. Camera calibration data can be inspected in the Camera
Calibration dialog, Adjusted tab, available from Tools menu. If the input file contains some reference
data (camera position data in some coordinate system), the data will be shown on the Reference pane,
View Estimated tab.

Camera data can be loaded in one of the following formats: Metashape *.xml, BINGO *.dat, Bundler *.out,
Autodesk FBX (*.fbx), VisionMap Detailed Report *.txt, Realviz RZML *.rzml.

Once the data is loaded, Metashape will offer to build point cloud. This step involves feature points
detection and matching procedures. As a result, a sparse point cloud - 3D representation of the tie-points
data, will be generated. Build Point Cloud command is available from Tools - Tie Points menu. Parameters
controlling Build Point Cloud procedure are the same as the ones used at Align Photos step (see above).
Building dense point cloud

Metashape allows to generate and visualize a dense point cloud model. Based on the estimated camera
positions the program calculates depth information for each camera to be combined into a single dense
point cloud. Metashape tends to produce extra dense point clouds, which are of almost the same density,
if not denser, as LIDAR point clouds. A dense point cloud can be edited and classified within Metashape
environment and used as a basis for such processing stages as Build Mesh, Build DEM, Build Tiled Model.
Alternatively, the point cloud can be exported to an external tool for further analysis.

To build a dense point cloud
\1. Check the reconstruction volume bounding box. To adjust the bounding box use the Resize
Region, Move Region and Rotate Region toolbar buttons. To resize the bounding box, drag
corners of the box to the desired positions; to move- hotd the box with the left mouse button.

\2. Select the Build Dense Cloud... command from the Workflow menu.

\3. In the Build Dense Cloud dialog box select the desired reconstruction parameters. Click OK button
when done.

\4. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
Reconstruction parameters
Quality
Specifies the desired reconstruction quality. Higher quality settings can be used to obtain more detailed
and accurate geometry, but they require longer time for processing. Interpretation of the quality

22

<!-- p. 29 -->

General workflow

parameters here is similar to that of accuracy settings given in Photo Alignment section. The only
difference is that in this case Ultra High quality setting means processing of original photos, while
each following step implies preliminary image size downscaling by factor of 4 (2 times by each side).

Additionally the following advanced parameters can be adjusted.

Depth filtering modes
At the stage of dense point cloud generation reconstruction Metashape calculates depth maps for every
image. Due to some factors, like noisy or badly focused images, there can be some outliers among
the points. To sort out the outliers Metashape has several built-in filtering algorithms that answer the
challenges of different projects.

If there are important small details which are spatially distinguished in the scene to be
reconstructed, then it is recommended to set Mild depth filtering mode, for important features
not to be sorted out as outliers. This value of the parameter may also be useful for aerial projects
in case the area contains poorly textured roofs, for example. Mild depth filtering mode is also
required for the depth maps based mesh reconstruction.

If the area to be reconstructed does not contain meaningful small details, then it is reasonable
to choose Aggressive depth filtering mode to sort out most of the outliers. This value of
the parameter normally recommended for aerial data processing, however, mild filtering may be
useful in some projects as well (see poorly textured roofs comment in the mild parameter value
description above).

Moderate depth filtering mode brings results that are in between the Mild and Aggressive
approaches. You can experiment with the setting in case you have doubts which mode to choose.

Additionally depth filtering can be Disabled. But this option is not recommended as the resulting
dense cloud could be extremely noisy.

Calculate point colors
This option can be unchecked in case the points color is not of interest. This will allow to save up
processing time.

Reuse depth maps
If you would like to reuse depth maps available in the chunk, select respective Quality and Depth
filtering parameters values (see info next to Depth maps label on the Workspace pane) and then check
Reuse depth maps option.
Point cloud import

Metashape allows to import a point cloud to be interpreted at further processing stages as a dense
point cloud. If you want to upload a dense point cloud got from some external source (photogrammetry
technology, laser scanning, etc), you can use Import points command from the File menu. In the Import
points dialog browse to a file in one of the supported formats and click Open button.

Dense point cloud can be imported in one of the following formats: Wavefront OBJ, Stanford PLY, ASPRS
LAS, LAZ, ASTM E57, ASCII PTS.
Building mesh
Mesh based on point cloud data

Based on the point cloud information (Dense Cloud, Sparse Cloud, Point Cloud uploaded from external
source) Metashape can reconstruct polygonal model - mesh.

23

<!-- p. 30 -->

General workflow

To build a mesh

\1. Check the reconstruction volume bounding box. If the model has already been referenced, the
bounding box will be properly positioned automatically. Otherwise, it is important to control its
position manually.

To adjust the bounding box manually, use the Resize Region, Move Region and Rotate
Region toolbar buttons. Rotate the bounding box and then drag corners of the box to the desired
positions - only part of the scene inside the bounding box will be reconstructed. If the Height
field reconstruction method is to be applied, it is important to control the position of the red side
of the bounding box: it defines reconstruction plane. In this case make sure that the bounding box
is correctly oriented.

\2. Select the Build Mesh... command from the Workflow menu.

\3. In the Build Mesh dialog box select the desired reconstruction parameters. Click OK button when
done.

\4. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
Reconstruction parameters

Metashape supports several reconstruction methods and settings, which help to produce optimal
reconstructions for a given data set.

Surface type

Arbitrary surface type can be used for modeling of any kind of object. It should be selected
for closed objects, such as statues, buildings, etc. It doesn't make any assumptions on the type of
the object being modeled, which comes at a cost of higher memory consumption.

Height field surface type is optimized for modeling of planar surfaces, such as terrains or
basereliefs. It should be selected for aerial photography processing as it requires lower amount
of memory and allows for larger data sets processing.

Source data
Specifies the source for the mesh generation procedure. Sparse cloud can be used for fast 3D
model generation based solely on the sparse point cloud. Dense cloud setting will result in longer
processing time but will generate high quality output based on the previously reconstructed dense
point cloud.Depth maps setting allows to use all the information from the input images more
effectively and is less resource demanding compared to the dense cloud based reconstruction. The
option is recommended to be used for Arbitrary surface type reconstruction, unless the workflow used
assumes dense cloud editing prior to the mesh reconstruction.

Quality
Specifies the desired reconstruction quality of the depth maps, providing that they are selected as a
source option. Higher quality settings can be used to obtain more detailed and accurate geometry, but
they require longer time for the processing. Interpretation of the quality parameters here is similar to
that of accuracy settings given in Photo Alignment section. The only difference is that in this case
Ultra High quality setting means processing of original photos, while each following step implies
preliminary image size downscaling by factor of 4 (2 times by each side).

Face count
Specifies the maximum number of polygons in the final mesh. Suggested values (High, Medium, Low)
present optimal number of polygons for a mesh of a corresponding level of detail. For the dense cloud

24

<!-- p. 31 -->

General workflow

based reconstruction they are calculated based on the number of points in the source dense point cloud:
the ratio is 1/5, 1/15, and 1/45 respectively. It is still possible for a user to indicate the target number
of polygons in the final mesh through the Custom value of the Face count parameter. Please note that
while too small number of polygons is likely to result in too rough mesh, too huge custom number
(over 10 million polygons) is likely to cause model visualization problems in external software.

Additionally the following advanced parameters can be adjusted.

Interpolation (for point cloud source options only)

If interpolation mode is Disabled it leads to accurate reconstruction results since only areas
corresponding to dense point cloud points are reconstructed. Manual hole filling is usually
required at the post processing step.

With Enabled (default) interpolation mode Metashape will interpolate some surface areas
within a circle of a certain radius around every dense cloud point. As a result some holes can be
automatically covered. Yet some holes can still be present on the model and are to be filled at
the post processing step.

In Extrapolated mode the program generates holeless model with extrapolated geometry.
Large areas of extra geometry might be generated with this method, but they could be easily
removed later using selection and cropping tools.

Point classes
Specifies the classes of the dense point cloud to be used for mesh generation. For example, select
only "Ground Points" to produce a DTM as opposed to a DSM. Preliminary Classifying dense cloud
points procedure should be performed for this option of mesh generation to be active. Option is not
applicable to depth maps and sparse cloud based reconstruction.

Calculate vertex colors
If source data have color information for the points, you can optionally calculate vertex colors.

Reuse depth maps
If you would like to reuse depth maps available in the chunk, select respective Quality (see info next
to Depth maps label on the Workspace pane) and then check Reuse depth maps option. The option
is applicable to the depth maps based reconstruction method only and requires Mild filtering option
applied to the depth maps.
Note

• Metashape tends to produce 3D models with excessive geometry resolution, so it may be
reasonable to perform mesh decimation after geometry computation. More information on mesh
decimation and other 3D model geometry editing tools is given in the Editing model geometry
section.
Building model texture
Color calibration

If the lighting conditions have been changing significantly during capturing scenario, it is recommended
to use 'Calibrate colors' option from the Tools menu before Build texture procedure. The option can help
to even brightness and white balance of the images over the data set. Please note that for large data sets
Calibrate colors procedure can turn out to be quite time consuming.

25

<!-- p. 32 -->

General workflow

To calibrate colors

\1. Select Calibrate colors... command from the Tools menu.

\2. Select the desired colors calibration parameters in the Calibrate colors dialog box. Click OK button
when done.

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
Color calibration parameters

Source data
Defines what data should be taken as the basis for overlapping areas estimation.
Sparse cloud - the quickest yet the roughest estimation available.

Model - gives more precise results, but only on condition that the surface is detailed enough. This
parameter value is the recommended one if the aim is to calibrate colors to improve the quality of
the model texture.

DEM - is a reasonable alternative to 'Model' value for large data sets when it is not feasible to reconstruct
solid polygonal model (mesh).

Calibrate white balance
Additional option to be switched on if white balance should be evened as well.

To generate 3D model texture

\1. Select Build Texture... command from the Workflow menu.

\2. Select the desired texture generation parameters in the Build Texture dialog box. Click OK button
when done.

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
Texture mapping modes

The texture mapping mode determines how the object texture will be packed in the texture atlas. Proper
texture mapping mode selection helps to obtain optimal texture packing and, consequently, better visual
quality of the final model.

Generic
The default mode is the Generic mapping mode; it allows to parametrize texture atlas for arbitrary
geometry. No assumptions regarding the type of the scene to be processed are made; program tries
to create as uniform texture as possible.

Adaptive orthophoto
In the Adaptive orthophoto mapping mode the object surface is split into the flat part and
vertical regions. The flat part of the surface is textured using the orthographic projection, while vertical
regions are textured separately to maintain accurate texture representation in such regions. When in
the Adaptive orthophoto mapping mode, program tends to produce more compact texture
representation for nearly planar scenes, while maintaining good texture quality for vertical surfaces,
such as walls of the buildings.

26

<!-- p. 33 -->

General workflow

Orthophoto
In the Orthophoto mapping mode the whole object surface is textured in the orthographic
projection. The Orthophoto mapping mode produces even more compact texture representation
than the Adaptive orthophoto mode at the expense of texture quality in vertical regions.

Spherical
Spherical mapping mode is appropriate only to a certain class of objects that have a ball-like form.
It allows for continuous texture atlas being exported for this type of objects, so that it is much easier
to edit it later. When generating texture in Spherical mapping mode it is crucial to set the Bounding
box properly. The whole model should be within the Bounding box. The red side of the Bounding
box should be under the model; it defines the axis of the spherical projection. The marks on the front
side determine the 0 meridian.

Single photo
The Single photo mapping mode allows to generate texture from a single photo. The photo to be
used for texturing can be selected from 'Texture from' list.

Keep uv
The Keep uv mapping mode generates texture atlas using current texture parametrization. It can
be used to rebuild texture atlas using different resolution or to generate the atlas for the model
parametrized in the external software.
Texture generation parameters

The following parameters control various aspects of texture atlas generation:

Texture from (Single photo mapping mode only)
Specifies the photo to be used for texturing. Available only in the Single photo mapping mode.

Blending mode (not used in Single photo mode)
Selects the way how pixel values from different photos will be combined in the final texture.

Mosaic - implies two-step approach: it does blending of low frequency component for overlapping
images to avoid seamline problem (weighted average, weight being dependent on a number of
parameters including proximity of the pixel in question to the center of the image), while high
frequency component, that is in charge of picture details, is taken from a single image - the one that
presents good resolution for the area of interest while the camera view is almost along the normal to
the reconstructed surface in that point.

Average - uses the weighted average value of all pixels from individual photos, the weight being
dependent on the same parameters that are considered for high frequency component in mosaic mode.

Max Intensity - the photo which has maximum intensity of the corresponding pixel is selected.

Min Intensity - the photo which has minimum intensity of the corresponding pixel is selected.

Disabled - the photo to take the color value for the pixel from is chosen like the one for the high
frequency component in mosaic mode.

Texture size / count
Specifies the size (width & height) of the texture atlas in pixels and determines the number of files
for texture to be exported to. Exporting texture to several files allows to archive greater resolution of
the final model texture, while export of high resolution texture to a single file can fail due to RAM
limitations.

Multi-page texture atlas generation is supported for Generic mapping mode only and Keep UV option,
if the imported model contains proper texture layout.

27

<!-- p. 34 -->

General workflow

Additionally the following advanced parameters can be adjusted.

Enable ghosting filter
In case the scene includes some thin structures or moving objects which failed to be reconstructed
as part of polygonal model, it can be useful to switch on this option to avoid ghosting effect on the
resulting texture.

Enable hole filling
This option is enabled on default since it helps to avoid salt-and-pepper effect in case of complicated
surface with numerous tiny parts shading other parts of the model. Only in case of very specific tasks
might it be recommended to switch the function off.
Note

• HDR texture generation requires HDR photos on input.
Improving texture quality

To improve resulting texture quality it may be reasonable to exclude poorly focused images from
processing at this step. Metashape suggests automatic image quality estimation feature. Images with quality
value of less than 0.5 units are recommended to be disabled and thus excluded from texture generation
procedure. To disable a photo use Disable button from the Photos pane toolbar.

Metashape estimates image quality as a relative sharpness of the photo with respect to other images in
the data set. The value of the parameter is calculated based on the sharpness level of the most focused
part of the picture.

To estimate image quality

\1. Switch to the detailed view in the Photos pane using Details command from the Change menu
on the Photos pane toolbar.

\2. Select all photos to be analyzed on the Photos pane.

\3. Right button click on the selected photo(s) and choose Estimate Image Quality command from the
context menu.

\4. Once the analysis procedure is over, a figure indicating estimated image quality value will be
displayed in the Quality column on the Photos pane.
Building tiled model

Hierarchical tiles format is a good solution for city scale modeling. It allows for responsive visualization
of large area 3D models in high resolution. The tiled model can be either opened in Metashape itself or
with Agisoft Viewer - a complementary tool included in Metashape installer package, or with some other
external application which supports a hierarchical tiles format.

Tiled model is build based on dense point cloud, or mesh, or depth maps data. Hierarchical tiles are textured
from the source imagery.
Note

• Build Tiled Model procedure can be performed only for projects saved in .PSX format.

28

<!-- p. 35 -->

General workflow

To build a tiled model

\1. Check the reconstruction volume bounding box - tiled model will be generated for the area within
bounding box only. To adjust the bounding box use the Move Region, Resize Region and
Rotate Region toolbar buttons. Rotate the bounding box and then drag corners of the box to the
desired positions.

\2. Select the Build Tiled Model... command from the Workflow menu.

\3. In the Build Tiled model dialog box select the desired reconstruction parameters. Click OK button
when done.

\4. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
Reconstruction parameters

Source data
Depth maps. Recommended for large projects when Build Mesh procedure is not feasible due to
processing time and result management issues.

Dense cloud. Can be used as an alternative to the depth maps based option in case the dense
cloud has been already generated for any other purposes, whereas the depth maps are not stored in the
project or have been generated with the filtering option different from Mild.

Mesh. Allows to keep all the details in the tiled model if a very detailed mesh has been generated
previously.

Pixel size (m)
Suggested value shows automatically estimated pixel size due to input imagery effective resolution.
It can be set by the user in meters.

Tile size
Tile size can be set in pixels. For smaller tiles faster visualization should be expected.

Face count
Suggested values (High, Medium, Low) present optimal number of polygons for a tiled model block
of a corresponding level of detail. It is still possible for a user to indicate the target number of polygons
in the final mesh through the Custom value of the Face count parameter.

Quality
Specifies the desired reconstruction quality of the depth maps, providing that they are selected as a
source option. Higher quality settings can be used to obtain more detailed and accurate geometry, but
they require longer time for the processing. Interpretation of the quality parameters here is similar to
that of accuracy settings given in Photo Alignment section. The only difference is that in this case
Ultra High quality setting means processing of original photos, while each following step implies
preliminary image size downscaling by factor of 4 (2 times by each side).

Additionally the following advanced parameters can be adjusted.

Enable ghosting filter
In case the scene includes some thin structures or moving objects which fails to be reconstructed as
part of polygonal model, it can be useful to enable this option to avoid ghosting effect on the resulting
texture.

29

<!-- p. 36 -->

General workflow

Reuse depth maps
If you would like to reuse depth maps available in the chunk, select respective Quality (see info next
to Depth maps label on the Workspace pane) and then check Reuse depth maps option. The option
is applicable to the depth maps based reconstruction method only and requires Mild filtering option
applied to the depth maps.
Building digital elevation model

Metashape allows to generate and visualize a digital elevation model (DEM). A DEM represents a surface
model as a regular grid of height values. DEM can be rasterized from a dense point cloud, a sparse point
cloud or a mesh. Most accurate results are calculated based on dense point cloud data. Metashape enables
to perform DEM-based point, distance, area, volume measurements as well as generate cross-sections for
a part of the scene selected by the user. Additionally, contour lines can be calculated for the model and
depicted either over DEM or Orthomosaic in Ortho view within Metashape environment. More information
on measurement functionality can be found in Performing measurements on DEM section.
Note

• Build DEM procedure can be performed only for projects saved in .PSX format.

• DEM can be calculated for referenced or scaled projects only. So make sure that you have set
a coordinate system for your model or specified at least one reference distance before going to
build DEM operation. For guidance on Setting coordinate system please go to Setting coordinate
system

DEM is calculated for the part of the model within the bounding box. To adjust the bounding box use the
Resize Region and Rotate Region toolbar buttons. Rotate the bounding box and then drag corners
of the box to the desired positions.

To build DEM

\1. Select the Build DEM... command from the Workflow menu.

\2. In the Build DEM dialog box set Coordinate system for the DEM or choose the projection type.

\3. Select source data for DEM rasterization.

\4. Click OK button when done.

\5. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
Parameters

Projection type
Geographic - allows to choose a geographic coordinate system from the dropdown list or upload
parameters of a customized geographical coordinate system. The coordinate system set by default
is the coordinate system previously selected for the model itself. You can switch to a different one,
providing that corresponding datum transformation parameters are available.
Planar. Metashape allows to project DEM onto a plane set by the user. You can select projection
plane and orientation of the resulting DEM. The plane can be determined by a set of markers (if there
are no 3 markers in a desired projection plane it can be specified with 2 vectors, i. e. 4 markers). Planar
projection type may be useful for DEM generation in projects concerning facades, for example.

30

<!-- p. 37 -->

General workflow

Cylindrical - allows to project DEM on a cylindrical surface. In this case height value is
calculated as the distance from the model surface to the cylindric surface. Refer to Building
orthomosaic section to see the options.

Source data
It is recommended to calculate DEM based on Dense Cloud data. Preliminary elevation data results
can be generated from a Sparse Cloud, avoiding Build Dense Cloud step for time limitation
reasons. Mesh and Tiled Model options can be used, if DEM should follow the polygonal model
precisely or dense cloud has not been reconstructed.

Interpolation
If interpolation mode is Disabled it leads to accurate reconstruction results since only areas
corresponding to point cloud or polygonal points are reconstructed. Usually this method is
recommended for Mesh and Tiled Model data source.

With Enabled (default) interpolation mode Metashape will calculate DEM for all areas of the
scene that are visible on at least one image. Enabled (default) setting is recommended for
DEM generation.

In Extrapolated mode the program generates holeless model with some elevation data being
extrapolated up to the bounding box extents.

Point classes
The parameter allows to select a point class (classes) that will be used for DEM calculation.

To generate digital terrain model (DTM), it is necessary to classify dense cloud points first in order to
divide them in at least two classes: ground points and the rest. Please refer to Classifying dense cloud
points section to read about dense point cloud classification options. Select Ground value for Point class
parameter in Build DEM dialog to generate DTM.

Metashape generates DEM only for the area inside the bounding box. To calculate DEM for a particular
rectangular part of the project, use Region section of the Build DEM dialog. Indicate coordinates of the
bottom left and top right corners of the region you would like to build the DEM for. Suggested values
indicate coordinates of the bottom left and top right corners of the whole area to be rasterized, the area
being defined with the bounding box.

Resolution value shows effective ground resolution for the DEM estimated for the source data. Size of the
resulting DEM, calculated with respect to the ground resolution, is presented in Total size section fields.
Building orthomosaic

Orthomosaic export is normally used for generation of high resolution imagery based on the source photos
and reconstructed model. The most common application is aerial photographic survey data processing,
but it may be also useful when a detailed view of the object is required. Metashape enables to perform
orthomosaic seamline editing for better visual results (see Orthomosaic seamlines editing section of the
manual).

For multispectral imagery processing workflow Ortho view tab presents Raster Calculator tool for NDVI
and other vegetation indices calculation to analyze crop problems and generate prescriptions for variable
rate farming equipment. More information on NDVI calculation functionality can be found in Performing
measurements on 3D model section.
Note

• Build Orthomosaic procedure can be performed only for projects saved in .PSX format for chunks
with the existing mesh or DEM.

31

<!-- p. 38 -->

General workflow

Color calibration

If the lighting conditions have been changing significantly during capturing scenario, it is recommended
to use 'Calibrate colors' option from the Tools menu before Build orthomosaic procedure. The option can
help to even brightness and white balance of the images over the data set. Please note that for large data
sets Calibrate colors procedure can turn out to be quite time consuming.

To calibrate colors

\1. Select Calibrate colors... command from the Tools menu.

\2. Select the desired colors calibration parameters in the Calibrate colors dialog box. Click OK button
when done.

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
Color calibration parameters

Source data
Defines what data should be taken as the basis for overlapping areas estimation. It is preferable to
select the source data type according to teh surface which you plan to project the orthomosaic on.
Sparse cloud - the quickest yet the roughest estimation available.

Model - gives more precise results, but only on condition that the surface is detailed enough.

DEM - is a reasonable alternative to 'Model' value for large data sets when it is not feasible to reconstruct
solid polygonal model (mesh).

Calibrate white balance
Additional option to be switched on if white balance should be evened as well.

To build Orthomosaic

\1. Select the Build Orthomosaic... command from the Workflow menu.

\2. In the Build Orthomosaic dialog box set Coordinate system for the Orthomosaic referencing or select
projection type.

\3. Select type of surface data for orthorectified imagery to be projected onto.

\4. Click OK button when done.

\5. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
Build orthomosaic parameters

Projection type
Geographic - allows to choose a geographic coordinate system from the dropdown list or upload
parameters of a customized geographical coordinate system. The coordinate system set by default
is the coordinate system previously selected for the model itself. You can switch to a different one,
providing that corresponding datum transformation parameters are available.

Planar. Metashape allows to project the orthomosaic onto a plane set by the user, providing
that mesh is selected as the surface type. You can select projection plane and orientation of the

32

<!-- p. 39 -->

General workflow

orthomosaic. The plane can be determined by a set of markers (if there are no 3 markers in a desired
projection plane it can be specified with 2 vectors, i. e. 4 markers). Planar projection type may be
useful for orthomosaic generation in projects concerning facades or other vertical surfaces.

Cylindrical - allows to project orthomosaic on a cylindrical surface. It helps to avoid severe
distortions while projecting cylindrical objects, like tubes, round towers, tunnels, etc.

To project 3D points on a cylindrical surface one needs to: 1) define the cylinder, i.e. define its axis and
its radius; 2) drop a perpendicular from the 3D point to the axis of the cylinder - the point of intersection
of the perpendicular and the cylindrical surface is the projection of the 3D point in question; 3) agree
on how to define x and y coordinates of a point on the cylinder. For the purpose of orthomosaic and
DEM generation in cylindrical projection Metashape defines x and y coordinates of a point on the
cylinder in the following way: x - along the curve in the zero-plane, y - along the zero-element of the
cylindric surface (zero-line), where zero-plane and zero-line are to be defined.

Metashape offers four methods to perform projecting on cylindrical surface. They differ in how the
four core elements - cylinder axis and radius, zero-plane and zero-line - are defined.

Current Region. The cylinder is inscribed in the Bounding box: the axis goes through the cross
sign on the bottom side of the Bounding box perpendicular to the bottom plane; the radius is defined
as one half of the shorter side of the rectangle in the bottom of the Bounding box. Zero-plane goes
through the center of the Bounding box perpendicular to the axis; zero-line belongs to the Bounding
box side which is opposite to the side with the vertical marks.

Current View. The axis is set as the line from the viewpoint to the center of rotation for the
model. Radius is defined as one half of the shortest of all the edges of the Bounding box. Zero-plane
goes through the center of rotation for the model perpendicular to the axis; zero-line goes through the
highest point (in monitor-related coordinate system) of the curve in the zero-plane.

Markers. At least three marker are required. The first pair sets the axis. The third marker defines
zero-point, i.e. defines zero-plane and zero-line, on condition that radius is the distance from the third
marker to the axis.

X/Y/Z. The axis is the line parallel to the corresponding Cartesian axis - X/Y/Z, going through the
center of the Bounding box. Radius (r) is defined as one half of the shortest edge of the Bounding box.
Zero-plane goes through the center of the Bounding box perpendicular to the axis; zero-line is the
line opposite to the cut line. The cut line definition for each of the three possible options is illustrated
on the Figure below.

Interior projection option allows to switch to projecting on the inner surface of the cylinder.

Surface
Orthomosaic creation based on DEM data is especially efficient for aerial survey data processing
scenarios allowing for time saving on mesh generation step. Alternatively, mesh surface type allows

33

<!-- p. 40 -->

General workflow

to create orthomosaic for less common, yet quite demanded applications, like orthomosaic generation
for facades of the buildings or other models that might be not referenced at all.

Blending mode
Mosaic (default) - implements approach with data division into several frequency domains
which are blended independently. The highest frequency component is blended along the seamline
only, each further step away from the seamline resulting in a less number of domains being subject
to blending.
Average - uses the weighted average value of all pixels from individual photos.
Disabled - the color value for the pixel is taken from the photo with the camera view being almost
along the normal to the reconstructed surface in that point.

Pixel size
Default value for pixel size in Export Orthomosaic dialog refers to ground sampling resolution, thus,
it is useless to set a smaller value: the number of pixels would increase, but the effective resolution
would not. However, if it is meaningful for the purpose, pixel size value can be changed by the user
in coordinate system units or in meters.

Max. dimension (pix)
The parameter allows to set maximal dimension for the resulting raster data.

Back face culling
The option allows to neglect on projecting parts of the surface where normals are counter directed to
the targeted projection plane.

Enable hole filling
This option is enabled on default since it helps to avoid salt-and-pepper effect in case of complicated
surface with numerous tiny parts shading other parts of the source surface model. Only in case of very
specific tasks might it be recommended to switch the function off.

Refine seamlines
The option is recommended to be used for DTM-based orthomosaics in order to make automatically
created seamlines to bypass buildings and other complex objects in order to avoid visual artifacts on
the final image and time consuming manual orthomosaic patching.

Metashape generates orthomosaic only for the area inside the bounding box. However, if the orthomosaic
should be generated for a particular (rectangular) part of the project, Region section of the Build
Orthomosaic dialog should be used for indication of the coordinates of the bottom left and top right corners
of the region to be applied in the left and right columns of the textboxes respectively. Estimate button
allows you to see the coordinates of the bottom left and top right corners of the whole area.

Estimate button also enables to control total size of the resulting orthomosaic data according to the currently
selected reconstruction area and resolution (Pixel size or Max. dimension parameters). The information is
shown in the Total size (pix) section fields.
Saving intermediate results

Certain stages of 3D model reconstruction can take a long time. The full chain of operations could
eventually last for 4-6 hours when building a model from hundreds of photos. It is not always possible to
complete all the operations in one run. Metashape allows to save intermediate results in a project file.
Metashape project archive (.PSZ)

Metashape Archive files (*.psz) may contain the following information:

34

<!-- p. 41 -->

General workflow

• List of loaded photographs with reference paths to the image files.

• Photo alignment data such as information on camera positions, sparse point cloud model and set of
refined camera calibration parameters for each calibration group.

• Masks applied to the photos in project.

• Depth maps for cameras.

• Dense point cloud model with information on points classification.

• Reconstructed 3D polygonal model with any changes made by user. This includes mesh and texture
if it was built.

• List of added markers as well as of scale-bars and information on their positions.

• Structure of the project, i.e. number of chunks in the project and their content.

Note that since Metashape tends to generate extra dense point clouds and highly detailed polygonal models,
project saving procedure can take up quite a long time.
Metashape project file (.PSX)

The software also allows to save Metashape Project file (*.psx) which stores the links to the processing
results in *.psx file and the data itself in *.files structured archive. This format enables responsive loading
of large data (dense point clouds, meshes, etc.), thus avoiding delays on reopening a thousands-of-photos
project. DEM, orthomosaic and tiled model generation options are available only for projects saved in
PSX format.

You can save the project at the end of any processing stage and return to it later. To restart work simply
load the corresponding file into Metashape. Project files can also serve as backup files or be used to save
different versions of the same model.

Project files use relative paths to reference original photos. Thus, when moving or copying the project file
to another location do not forget to move or copy photographs with all the folder structure involved as
well. Otherwise, Metashape will fail to run any operation requiring source images, although the project
file including the reconstructed model will be loaded up correctly. Alternatively, you can enable Store
absolute image paths option on the Advanced tab of the Preferences dialog available from Tools menu.
Exporting results

Metashape supports export of processing results in various representations: sparse and dense point clouds,
camera calibration and camera orientation data, mesh, etc. Orthomosaics and digital elevation models
(both DSM and DTM), as well as tiled models can be generated according to the user requirements.

Point cloud and camera calibration data can be exported right after photo alignment is completed. All other
export options are available after the corresponding processing step.

If you are going to export the results (point cloud / mesh / tiled model ) for the chunk that is not referenced,
please note that the resulting file will be oriented according to a default coordinate system (see axes in
the bottom right corner of the Model view), i. e. the model can be shown differently from what you see
in Metashape window. To align the model orientation with the default coordinate system use Rotate
object button from the Toolbar. Move object and Scale object instruments can be used to adjust
the size and location of the unreferenced model.

35

<!-- p. 42 -->

General workflow

In some cases editing model geometry in the external software may be required. Metashape supports model
export for editing in external software and then allows to import it back as it is described in the Editing
model geometry section of the manual.

Main export commands are available from the File menu.
Point cloud export

To export sparse or dense point cloud

\1. Select Export Points... command from the File menu.

\2. Browse the destination folder, choose the file type, and print in the file name. Click Save button.

\3. In the Export Points dialog box select desired Type of point cloud - Sparse or Dense.

\4. Specify the coordinate system and indicate export parameters applicable to the selected file type,
including the dense cloud classes to be saved.

\5. Click OK button to start export.

\6. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.

Split in blocks option in the Export Points dialog can be useful for exporting large projects. It is available
for referenced models only. You can indicate the size of the section in xy plane (in meters) for the point
cloud to be divided into respective rectangular blocks. The total volume of the 3D scene is limited with
the Bounding Box. The whole volume will be split in equal blocks starting from the point with minimum
x and y values. Note that empty blocks will not be saved.

In some cases it may be reasonable to edit point cloud before exporting it. To read about point cloud editing
refer to the Editing point cloud section of the manual.

Metashape supports point cloud export in the following formats:

• Wavefront OBJ

• Stanford PLY

• XYZ text file format

• ASPRS LAS

• LAZ

• ASTM E57

• ASCII PTS

• Autodesk DXF

• U3D

• potree

• Cesium 3D Tiles

36

<!-- p. 43 -->

General workflow

• Agisoft OC3

• Topcon CL3

• PDF
Note

• Saving color information of the point cloud is not supported by the OBJ and DXF formats.

• Saving point normals information is not supported by the LAS, LAZ, PTS, CL3 and DXF
formats.

Metashape supports direct uploading of the point clouds to the following resources: 4DMapper, PointBox,
PointScene and Sketchfab. To publish your point cloud online use Upload Model... command from the
File menu.
Tie points and camera calibration, orientation data
export

To export camera calibration and camera orientation data select Export Cameras... command from the File
menu.

Metashape supports camera data export in the following formats:

• Agisoft XML structure

• Bundler OUT file format

• CHAN file format

• Boujou TXT file format

• Omega Phi Kappa text file format

• Realviz RZML format

• PATB Exterior orientation

• BINGO project file

• ORIMA file

• AeroSys Exterior orientation

• Inpho project file

• Summit Evolution project

• Blocks exchange
Note

• Camera data export in Bundler and Boujou file formats will save sparse point cloud data in the
same file.

37

<!-- p. 44 -->

General workflow

• Camera data export in Bundler file format would not save distortion coefficients k3, k4.

To export tie points data one should choose one of the following exchange formats in the Export Cameras
dialog: BINGO, ORIMA, PATB, Summit Evolution or Blocks. Tie points can be exported only along with
camera calibration and orientation data.

To export / import only camera calibration data select Camera Calibration... command from the Tools
menu. Using / buttons it is possible to load / save camera calibration data in the following formats:

• Agisoft Camera Calibration (*.xml)

• Australis Camera Parameters (*.txt)

• PhotoModeler Camera Calibration (*.ini)

• 3DM CalibCam Camera Parameters (*.txt)

• CalCam Camera Calibration (*.cal)

• Inpho Camera Calibration (*.txt)

• USGS Camera Calibration (*.txt)

• Z/I Distortion Grid (*.dat)
Panorama export

Metashape is capable of panorama stitching for images taken from the same camera position - camera
station. To indicate for the software that loaded images have been taken from one camera station, one
should move those photos to a camera group and assign Camera Station type to it. For information on
camera groups refer to Loading photos section.

To export panorama

\1. Select Export Panorama... command from the File menu.

\2. Select camera group which panorama should be previewed for.

\3. Choose panorama orientation in the file with the help of navigation buttons to the right of the preview
window in the Export Panorama dialog.

\4. Set exporting parameters: select camera groups which panorama should be exported for and indicate
export file name mask.

\5. Click OK button

\6. Browse the destination folder and click Save button.

Additionally, you can set boundaries for the region of panorama to be exported using Setup boundaries
section of the Export Panorama dialog. Text boxes in the first line (X) allow to indicate the angle in the
horizontal plane and the second line (Y) serves for angle in the vertical plane limits. Image size (pix) option
enables to control the dimensions of the exported image file.

Metashape supports panorama export in the following formats:

38

<!-- p. 45 -->

General workflow

• JPEG

• TIFF

• PNG

• BMP

• OpenEXR

• TARGA
3D model export

To export 3D model

\1. Select Export Model... command from the File menu.

\2. Browse the destination folder, choose the file type, and print in the file name. Click Save button.

\3. In the Export Model dialog specify the coordinate system and indicate export parameters applicable
to the selected file type.

\4. Click OK button to start export.

\5. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.

If a model generated with Metashape is to be imported in a 3D editor program for inspection or further
editing, it might be helpful to use Shift function while exporting the model. It allows to set the value to
be subtracted from the respective coordinate value for every vertex in the mesh. Essentially, this means
translation of the model coordinate system origin, which may be useful since some 3D editors, for example,
truncate the coordinates values up to 8 or so digits, while in some projects they are decimals that make
sense with respect to model positioning task. So it can be recommended to subtract a value equal to the
whole part of a certain coordinate value (see Reference pane, Camera coordinates values) before exporting
the model, thus providing for a reasonable scale for the model to be processed in a 3D editor program.

Metashape supports model export in the following formats:

• Wavefront OBJ

• 3DS file format

• VRML

• COLLADA

• Alembic

• Stanford PLY

• STL

• Autodesk FBX

• Autodesk DXF (in Polyline or 3DFace representation)

39

<!-- p. 46 -->

General workflow

• U3D

• Google Earth KMZ

• Adobe PDF

Some file formats (OBJ, 3DS, VRML, COLLADA, PLY, FBX) save texture image in a separate file. The
texture file should be kept in the same directory as the main file describing the geometry. If the texture
atlas was not built only the model geometry is exported.

Metashape supports direct uploading of the models to Sketchfab resource. To publish your model online
use Upload Model... command from the File menu.
Tiled model export

To export tiled model

\1. Select Export Tiled Model... command from the File menu.

\2. Browse the destination folder, choose the file type, and print in the file name. Click Save button.

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.

Metashape supports tiled model export in the following formats:

• Cesium 3D Tiles (*.zip)

• Scene Layer Package (*.slpk)

• PhotoMesh Layer (*.zip)

• Agisoft Tiled Model (*.tls)

• Agisoft Tile Archive (*.zip)

Agisoft Tiled Model can be visualiszd in Agisoft Viewer application, which is included in Agisoft
Metashape Professional installation file. Thanks to hierarchical tiles format, it allows to responsively
visualize large models.

Metashape supports direct uploading of the tiled models to the following resources: 4DMapper, Melown
Cloud, Sputnik. To publish your tiled model online use Upload Model... command from the File menu.
Orthomosaic export

To export Orthomosaic

\1. Select Export Orthomosaic... command from the File menu.

\2. In the Export Orthomosaic dialog box specify coordinate system for the Orthomosaic to be saved in.

\3. Check Write KML file and / or Write World file options to create files needed to georeference the
orthomosaic in the Google Earth and / or a GIS .

\4. Click Export... button to start export.

40

<!-- p. 47 -->

General workflow

\5. Browse the destination folder, choose the file type, and print in the file name. Click Save button.

\6. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
Note

• Write KML file option is available only if the selected export coordinate system is WGS84 due
to the fact that Google Earth supports only this coordinate system.

• World file specifies coordinates of the four corner vertices of the exporting orthomosaic. This
information is already included in GeoTIFF file, however, you could duplicate it for some reason.
If you need to export orthomosaic in JPEG, PNG or BMP file formats and would like to have
georeferencing data this informations could be useful.

If the export file of a fixed size is needed, it is possible to set the length of the longer side of the export
file in Max. dimension (pix) parameter. The length should be indicated in pixels.

Split in blocks option in the Export Orthomosaic dialog can be useful for exporting large projects. You
can indicate the size of the blocks (in pix) for the orthomosaic to be divided into. The whole area will be
split in equal blocks starting from the point with minimum x and y values. Note that empty blocks will
not be saved.

To export a particular part of the project use Region section of the Export Orthomosaic dialog. Indicate
coordinates of the bottom left and top right corners of the region to be exported in the left and right columns
of the textboxes respectively. Estimate button allows you to see the coordinates of the bottom left and top
right corners of the whole area.

Alternatively, you can indicate the region to be exported using polygon drawing option in the Ortho view
tab of the program window. (For instructions on polygon drawing refer to Shapes section of the manual.)
Once the polygon is drawn, right-click on the polygon and set it as a boundary of the region to be exported
using Set Boundary Type option from the context menu.

Default value for pixel size in Export Orthomosaic dialog refers to ground sampling resolution, thus, it
is useless to set a smaller value: the number of pixels would increase, but the effective resolution would
not. If you have chosen to export orthomosaic with a certain pixel size (not using Max. dimension (pix)
option), it is recommended to check estimated Total size (pix) of the resulting file to be sure that it is not
too large to be correctly saved to the targeted file format.

For (Geo)TIFF export compression type may be set by the user. The following options are available:
LZW, JPEG, Packbits, Deflate. Additionally, the file may be saved without compression (None value
of the compression type parameter). Write BigTIFF file option allows to save files bigger than standard
TIFF limit of 4Gb. Total size textbox in the Export Orthomosaic dialog helps to estimate the size of the
resulting file. However, it is recommended to make sure that the application you are planning to open the
orthomosaic with supports BigTIFF format. Alternatively, you can split a large orthomosaic in blocks,
with each block fitting the limits of a standard TIFF file.

While exporting orthomosaic in JPEG format, JPEG quality parameter controls balance between
compression level (i.e. quality of the result) and export file size: the higher the value of the parameter (%)
the more emphasis is on the quality at the expense of a larger resulting file.

The following formats are supported for orthomosaic export:

• GeoTIFF

• JPEG

41

<!-- p. 48 -->

General workflow

• PNG

• BMP

• Multiresolution Google Earth KML mosaic

• Google Map Tiles

• MBTiles

• World Wind Tiles

Metashape supports direct uploading of the orthomosaics to the following resources: 4DMapper, MapBox,
Melown Cloud, Sputnik. To publish your point cloud online use Upload Model... command from the File
menu.

Multispectral orthomosaic export is supported in GeoTIFF format only. When exporting in other formats,
only primary channel will be saved. Multispectral orthomosaic has all channels of the original imagery.
Optionally the alpha channel may be included that defines transparency being used for no-data areas of
the orthomosaic.

To export Multispectral orthomosaic

\1. Select Export Orthomosaic... command from the File menu.

\2. Follow steps 2-3 from Orthomosaic export procedure above.

\3. Select None value for Raster transform parameter.

\4. Click Export button to start export.

\5. Browse the destination folder, choose GeoTIFF type, and print in the file name. Click Save button.

\6. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
NDVI data export

Vegetation index data export is available with the Export Orthomosaic... command from the File menu.
Vegetation index data can be saved as two types of data: as a grid of floating point index values calculated
per pixel of orthomosaic (multichannel orthomosaic if several vegetation indices have been calculated for
the project) or as an orthomosaic in pseudocolors according to a pallet set by user (exports only data for the
first vegetation index or combined data for selected 3 vegetation indices, providing that False Color value
is set for the color palette parameter). The format is controlled with Raster transform option in Export
Orthomosaic / Export Google KMZ / Export Google Map Tiles / Export MBTiles / Export World Wind
Tiles dialogs. None value allows to export orthomosaic generated for the data before any index calculation
procedure was performed.
Digital Elevation Model (DSM/DTM) export

Metashape allows to calculate and then export both a digital surface model (DSM) and a digital terrain
model (DTM) (see Building digital elevation model section).

To export Digital Elevation Model

\1. Select Export DEM... command from the File menu.

42

<!-- p. 49 -->

General workflow

\2. In the Export DEM dialog specify coordinate system to georeference the DEM.

\3. Check Write KML file and/or Write World file options to create files needed to georeference the
DEM in the Google Earth and/or a GIS.

\4. Click Export button to start export.

\5. Browse the destination folder, choose the file type, and print in the file name. Click Save button.

\6. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.
Note

• Write KML file option is available only if the model is georeferenced in WGS84 coordinate
system due to the fact that Google Earth supports only this coordinate system.

• World file specifies coordinates of the four corner vertices of the exporting DEM. This
information is already included in GeoTIFF elevation data as well as in other supported file
formats for DEM export, however, you could duplicate it for some reason.

If export file of a fixed size is needed, it is possible to to set the length of the longer side of the export file
in Max. dimension (pix) parameter. The length should be indicated in pixels.

Unlike orthomosaic export, it is sensible to set smaller pixel size compared to the default value in DEM
export dialog; the effective resolution will increase. If you have chosen to export DEM with a certain pixel
size (not using Max. dimension (pix) option), it is recommended to check estimated Total size (pix) of the
resulting file to be sure that it is not too large to be correctly saved to the targeted file format.

No-data value is used for the points of the grid, where elevation value could not be calculated based on
the source data. Default value is suggested according to the industry standard, however it can be changed
by user.

Split in blocks option in the Export DEM dialog can be useful for exporting large projects or meeting
special DEM requirements. (See Orthomosaic export section for details.)

To export a particular part of the project use Region section of the Export DEM dialog. (See Orthomosaic
export section for details.) Similarly to orthomosaic export, polygons drawn over the DEM on the Ortho
tab of the program window can be set as boundaries for DEM export. (For instructions on polygon drawing
refer to Shapes section of the manual.)

The following formats are supported for DEM export:

• GeoTIFF elevation data

• Arc/Info ASCII Grid (ASC)

• Band interleaved file format (BIL)

• XYZ file format

• Sputnik KMZ

Metashape supports direct uploading of the elevation models to the following resources: 4DMapper,
MapBox, Melown Cloud, Sputnik. To publish your elevation model online use Upload Model... command
from the File menu.

43

<!-- p. 50 -->

General workflow

Extra products to export

In addition to main targeted products Metashape allows to export several other processing results, like

• Undistort photos, i. e. photos free of lens distortions (Undistort Photos... command available from Export
submenu of the File menu). Undistorted photos may be exported with the applied color correction, if
corresponding option is selected in the Undistort Photos dialog.

• Depth map for any image (Export Depth... command available from photo context menu).

• Individually orthorectified images (Export Orthophotos... command available from Export submenu of
the File menu).

• High resolution image of the model as it is shown in the Model view or in Ortho view mode. Capture
View command available from the context menu shown on right button click in the Model or Ortho view.
Processing report generation

Metashape supports automatic processing report generation in PDF format, which contains the basic
parameters of the project, processing results and accuracy evaluations.

To generate processing report

\1. Select Generate Report... command from the File menu.

\2. Browse the destination folder, choose the file type, and print in the file name. Click Save button.

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.

Metashape processing report presents the following data:

• Orthomosaic sketch.

• Survey data including coverage area, flying altitude, GSD, general camera(s) info, as well as overlap
statistics.

• Camera calibration results: figures and an illustration for every sensor involved in the project.

• Camera positioning and orientation error estimates.

• Ground control and check points error estimates.

• Scale bars estimated distances and measurement errors.

• Digital elevation model sketch with resolution and point density info.

• Processing parameters used at every stage of the project.
Note

• Processing report can be exported after alignment step. Processing report export option is
available for georeferenced projects only.
Survey Data

Number of images - total number of images uploaded into the project.

44

<!-- p. 51 -->

General workflow

Camera stations - number of aligned images.

Flying altitude - average height above ground level.

Tie points - total number of valid tie points (equals to the number of points in the sparse cloud).

Ground resolution - effective ground resolution averaged over all aligned images.

Projections - total number of projections of valid tie points.

Coverage area - size of the area that has been surveyed.

Reprojection error - root mean square reprojection error averaged over all tie points on all images.

Reprojection error is the distance between the point on the image where a reconstructed 3D point can be
projected and the original projection of that 3D point detected on the photo and used as a basis for the
3D point reconstruction procedure.
Camera Calibration

For precalibrated cameras internal parameters input by the user are shown on the report page. If a camera
was not precalibrated, internal camera parameters estimated by Metashape are presented.
Camera Locations

X error (m) - root mean square error for X coordinate for all the cameras.

Y error (m) - root mean square error for Y coordinate for all the cameras.

XY error (m) - root mean square error for X and Y coordinates for all the cameras.

Z error (m) - root mean square error for Z coordinate for all the cameras.

Total error (m) - root mean square error for X, Y, Z coordinates for all the cameras.
Total error = sqrt(Sumi=1n [(Xi, est - Xi, in)2 + (Yi, est - Yi, in)2 + (Zi, est - Zi, in)2] / n)

Xi, in - input value for X coordinate for i camera position,

Xi, est - estimated value for X coordinate for i camera position,

Yi, in - input value for Y coordinate for i camera position,

Yi, est - estimated value for Y coordinate for i camera position,

Zi, in - input value for Z coordinate for i camera position,

Zi, est - estimated value for Z coordinate for i camera position,
Ground Control and Check Points

XY error (m) - root mean square error for X and Y coordinates for a GCP location / check point.

Z error (m) - error for Z coordinate for a GCP location / check point.

Error (m) - root mean square error for X, Y, Z coordinates for a GCP location / check point.

Projections - number of projections for a GCP location / check point over all the images.

45

<!-- p. 52 -->

General workflow

Error (pix) - root mean square error for X, Y coordinates on an image for a GCP location / check
point averaged over all the images.

Total - implies averaging over all the GCP locations / check points.
Scale Bars

Distance (m) - scale bar length estimated by Metashape.

Error (m) - difference between input and estimated values for scale bar length.

Total - implies averaging over all the scale bars in Control/Check section.
Digital Elevation Model

Resolution - effective resolution of the exported DEM. The value depends on the Quality parameter
value used at Build point cloud step, providing that DEM has been generated from dense point cloud.

Point Density - average number of dense cloud points per square meter.
Processing Parameters

Processing report contains processing parameters information, which is also available form Chunk context
menu. Along with the values of the parameters used at various processing stages, this page of the report
presents information on processing time.

For projects calculated over network processing time will be displayed as a sum of the time spent for
processing by each node.

Metashape matches images on different scales to improve robustness with blurred or difficult to match
images. The accuracy of tie point projections depends on the scale at which they were located. Metashape
uses information about scale to weight tie point reprojection errors. In the Reference pane settings dialog
tie point accuracy parameter now corresponds to normalized accuracy - i.e. accuracy of tie point detected
at the scale equal to 1. Tie points detected on other scales will have accuracy proportional to their scales.
This helps to obtain more accurate bundle adjustment results. On the processing parameters page of the
report (as well as in chunk information dialog) two reprojection errors are provided: the reprojection error
in the units of tie point scale (this is the quantity that is minimized during bundle adjustment), and the
reprojection error in pixels (for convenience). The mean key point size value is a mean tie point scale
averaged across all projections.

46

<!-- p. 53 -->

Chapter 4. Referencing
Camera calibration
Calibration groups

While carrying out photo alignment Metashape estimates both internal and external camera orientation
parameters, including nonlinear radial distortions. For the estimation to be successful it is crucial to apply
the estimation procedure separately to photos taken with different cameras. Once photos have been loaded
in the program, Metashape automatically divides them into calibration groups according to the image
resolution and/or EXIF meta data like camera type and focal length. All the actions described below could
and should be applied (or not applied) to each calibration group individually.

Calibration groups can be rearranged manually.

To create a new calibration group

\1. Select Camera Calibration... command from the Tools menu.

\2. In the Camera Calibration dialog box, select photos to be arranged in a new group.

\3. In the right-click context menu choose Create Group command.

\4. A new group will be created and depicted on the left-hand part of the Camera Calibration dialog box.

To move photos from one group to another

\1. Select Camera Calibration... command from the Tools menu.

\2. In the Camera Calibration dialog box choose the source group on the left-hand part of the dialog.

\3. Select photos to be moved and drag them to the target group on the left-hand part of the Camera
Calibration dialog box.

To place each photo into a separate group you can use Split Groups command available at the right button
click on a calibration group name in the left-hand part of the Camera Calibration dialog
Camera types

Metashape supports four major types of camera: frame camera, fisheye camera, spherical camera and
cylindrical camera. Camera type can be set in Camera Calibration dialog box available from Tools menu.

Frame camera. If the source data within a calibration group was shot with a frame camera, for successful
estimation of camera orientation parameters the information on approximate focal length (pix) is required.
Obviously, to calculate focal length value in pixel it is enough to know focal length in mm along with the
sensor pixel size in mm. Normally this data is extracted automatically from the EXIF meta data.

Frame camera with Fisheye lens. If extra wide lenses were used to get the source data, standard
Metashape camera model will not allow to estimate camera parameters successfully. Fisheye camera type
setting will initialize implementation of a different camera model to fit ultra-wide lens distortions.

Spherical camera (equirectangular projection). In case the source data within a calibration group
was shot with a spherical camera, camera type setting will be enough for the program to calculate

47

<!-- p. 54 -->

Referencing

camera orientation parameters. No additional information is required except the image in equirectangular
representation.

Spherical camera Cylindrical projection. In case the source data within a calibration group is a set
of panoramic images stitched according to cylindrical model, camera type setting will be enough for the
program to calculate camera orientation parameters. No additional information is required.

In case source images lack EXIF data or the EXIF data is insufficient to calculate focal length in pixels,
Metashape will assume that focal length equals to 50 mm (35 mm film equivalent). However, if the initial
guess values differ significantly from the actual focal length, it is likely to lead to failure of the alignment
process. So, if photos do not contain EXIF meta data, it is preferable to specify focal length (mm) and
sensor pixel size (mm) manually. It can be done in Camera Calibration dialog box available from Tools
menu. Generally, this data is indicated in camera specification or can be received from some online source.
To indicate to the program that camera orientation parameters should be estimated based on the focal
length and pixel size information, it is necessary to set the Type parameter on the Initial tab to Auto value.
Scanned Photos

Metashape supports processing of analog aerial images scanned to digital files. On uploading, all the
scanned photos from the same analog camera should be placed in a designated calibration group.
Metashape will automatically put the photos in the same calibration group, providing that they have been
scanned to the images of the same resolution. In case scanned analog photos from different cameras have
been uploaded to the same chunk, you should manually divide them into different calibration groups. It
could be done in Camera Calibration dialog available from Tools menu.

Camera calibration in case of scanned images is performed based on the fiducial marks information. That is
why camera calibration starts with fiducial marks detection in this workflow. Metashape enables automatic
detection of most of the fiducial mark types. See Figure below.

To calibrate scanned images with automatically detectable fiducial marks

\1. Select Camera Calibration... command from the Tools menu.

\2. In the Camera Calibration dialog box check Film camera with fiducial marks option.

\3. Close Camera Calibration dialog with OK button.

\4. Run Detect Fiducials... command from the Tools -> Markers menu.

\5. In the Camera Calibration dialog box print in coordinates of the automatically detected fiducial marks
on the image according to the analog camera certificate. They should be measured in coordinate
system associated with the sensor: origin - in the center of the sensor; axes X - to the right, axes Y
\- downwards; in millimeters (mm).

\6. Close Camera Calibration dialog with OK button and proceed to general Metashape processing
workflow starting from Align Photos... step. The software will automatically scale and orientate all
the photos according to the fiducial marks information.

In case your fiducial marks type is not among those supported for automatic detection (see Figure above),
please place a feature request with Agisoft support team: support@agisoft.com. The current version of
the software allows to perform calibration of the scanned images based on such fiducial marks manually
following the procedure outlined below.

To calibrate scanned images with non-standard fiducial marks manually

\1. Select Camera Calibration... command from the Tools menu.

48

<!-- p. 55 -->

Referencing

\2. In the Camera Calibration dialog box check Film camera with fiducial marks option.

\3. On the Fiducials tab add fiducial mark instances, te number should be equal to the amount of fiducial
marks used on the original photos.

\4. Print in coordinates of the fiducial marks on the image according to the analog camera certificate.
They should be measured in coordinate system associated with the sensor: origin - in the center of
the sensor; axes X - to the right, axes Y - downwards; in millimeters (mm).

\5. Close Camera Calibration dialog with OK button.

\6. Then it is necessary to place all the fiducials on each photo from the calibration group.

\7. Open the photo in Photo View.

\8. Zoom in to a fiducial mark center.

\9. Right button click on the targeted fiducial mark and use Place Fiducial command from the context
menu. You will need to chose a corresponding fiducial mark instance from the dropdown list.

\10. After placing all the fiducial mark instances, you can proceed to general Metashape processing
workflow. The software will automatically scale and orientate all the photos according to the fiducial
marks information.
Note

• If there is no camera certificate with fiducial marks coordinates information for the data set in
question, then it will be necessary to additionally run Calibrate Fiducials... command from the
context menu of the selected images in the Camera Calibration dialog box. All the images from
the respective calibration group should be selected for the purpose.

• It is recommended to mask out all the margins with auxiliary information on scanned photos to
avoid negative effect on the stability of the further processing.
Camera calibration parameters

Once you have tried to run the estimation procedure and got poor results, you can improve them thanks
to the additional data on calibration parameters.

To specify camera calibration parameters

\1. Select Camera Calibration... command from the Tools menu.

\2. Select calibration group, which needs reestimation of camera orientation parameters on the left side
of the Camera Calibration dialog box.

\3. In the Camera Calibration dialog box, select Initial tab.

\4. Modify the calibration parameters displayed in the corresponding edit boxes.

\5. Set the Type to the Precalibrated value.

\6. Repeat to every calibration group where applicable.

\7. Click OK button to set the calibration.

49

<!-- p. 56 -->

Referencing

Note

• Alternatively, initial calibration data can be imported from file using Load button on the Initial tab
of the Camera Calibration dialog box. In addition to Agisoft calibration file format it is possible
to import data from Australis, PhotoModeler, 3DM CalibCam, CalCam.

Initial calibration data will be adjusted during the Align Photos processing step. Once Align Photos
processing step is finished adjusted calibration data will be displayed on the Adjusted tab of the Camera
Calibration dialog box.

If very precise calibration data is available, to protect it from recalculation one should check Fix calibration
box. In this case initial calibration data will not be changed during Align Photos process.

Adjusted camera calibration data can be saved to file using Save button on the Adjusted tab of the Camera
Calibration dialog box.

Estimated camera distortions can be seen on the distortion plot available from context menu of a camera
group in the Camera Calibration dialog. In addition, residuals graph (the second tab of the same Distortion
Plot dialog) allows to evaluate how adequately the camera is described with the applied mathematical
model. Note that residuals are averaged per cell of an image and then across all the images in a camera
group. Scale reference under the plot indicates the scale of the distortions/residuals.
Calibration parameters list

f
Focal length measured in pixels.

cx, cy
Principal point coordinates, i.e. coordinates of lens optical axis interception with sensor plane in pixels.

b1, b2
Affinity and Skew (non-orthogonality) transformation coefficients.

k1, k2, k3, k4
Radial distortion coefficients.

p1, p2, p3, p4
Tangential distortion coefficients.
Setting coordinate system

Many applications require data with a defined coordinate system. Setting the coordinate system also
provides a correct scaling of the model allowing for surface area and volume measurements and makes
model loading in geoviewers and geoinformation software much easier. Some Metashape functionality
like digital elevation model export is available only after the coordinate system is defined.

Metashape supports setting a coordinate system based on either ground control point (marker) coordinates
or camera coordinates. In both cases the coordinates are specified in the Reference pane and can be either
loaded from the external file or typed in manually.

Setting coordinate system based on recorded camera positions is often used in aerial photography
processing. However, it may be also useful for processing close-range data sets collected with GPS enabled
cameras. Placing markers is not required if recorded camera coordinates are used to initialize the coordinate
system.

50

<!-- p. 57 -->

Referencing

In case ground control points are used to set up the coordinate system, markers should be placed in the
corresponding locations of the scene.

Using camera data for georeferencing is faster since manual marker placement is not required. On the
other hand, ground control point coordinates are usually more accurate than telemetry data, allowing for
more precise georeferencing.
Placing markers

Metashape uses markers to specify locations within the scene. Markers are used for setting up a coordinate
system, photo alignment optimization, measuring distances and volumes within the scene as well as for
marker based chunk alignment. Marker positions are defined by their projections on the source photos.
The more photos are used to specify marker position the higher is the accuracy of marker placement. To
define marker location within a scene, it should be placed on at least 2 photos.
Note

• Marker placement is not required for setting the coordinate system based on recorded camera
coordinates. This section can be safely skipped if the coordinate system is to be defined based
on recorded camera locations.

Metashape supports two approaches to marker placement: manual marker placement and guided marker
placement. Manual approach implies that the marker projections should be indicated manually on each
photo where the marker is visible. Manual marker placement does not require 3D model and can be
performed even before photo alignment.

In the guided approach marker projection is specified for a single photo only. Metashape automatically
projects the corresponding ray onto the model surface and calculates marker projections on the rest of
the photos where marker is visible. Marker projections defined automatically on individual photos can be
further refined manually. Reconstructed 3D model surface is required for the guided approach.

Guided marker placement usually speeds up the procedure of marker placement significantly and also
reduces the chance of incorrect marker placement. It is recommended in most cases unless there are any
specific reasons preventing this operation.

To place a marker using guided approach

\1. Open a photo where the marker is visible by double clicking on its name.

\2. Switch to the marker editing mode using Edit Markers toolbar button.

\3. Right click on the photo at the point corresponding to the marker location.

\4. Select Create Marker command from the context menu. New marker will be created and its projections
on the other photos will be automatically defined.
Note

• If the 3D model is not available or the ray at the selected point does not intersect with the model
surface, the marker projection will be defined on the current photo only.

• Guided marker placement can be performed in the same way from the 3D view by right clicking
on the corresponding point on the model surface and using Create Marker command from the
context menu. While the accuracy of marker placement in the 3D view is usually much lower, it

51

<!-- p. 58 -->

Referencing

may be still useful for quickly locating the photos observing the specified location on the model.
To view the corresponding photos use Filter by Markers command again from the 3D view
context menu. If the command is inactive, please make sure that the marker in question is selected
on the Reference pane.

To place a marker using manual approach

\1. Create marker instance using Add marker button on the Workspace pane or by Add Marker
command from the Chunk context menu (available by right clicking on the chunk title on the
Workspace pane).

\2. Open the photo where the marker projection needs to be added by double clicking on the photos name.

\3. Switch to the marker editing mode using Edit Markers toolbar button.

\4. Right click at the point on the photo where the marker projection needs to be placed. From the context
menu open Place Marker submenu and select the marker instance previously created. The marker
projection will be added to the current photo.

\5. Repeat the previous step to place marker projections on other photos if needed.

To save up time on manual marker placement procedure Metashape offers guiding lines feature. When a
marker is placed on an aligned photo, Metashape highlights lines, which the marker is expected to lie on,
on the rest of the aligned photos.
Note

• If a marker has been placed on at least two aligned images Metashape will find the marker
projections on the rest of the photos. The calculated marker positions will be indicated with
icon on the corresponding aligned photos in Photo View mode.

Automatically defined marker locations can be later refined manually by dragging their projections on the
corresponding photos.

To refine marker location

\1. Open the photo where the marker is visible by double clicking on the photo's name. Automatically
placed marker will be indicated with icon.

\2. Switch to the marker editing mode using Edit Markers toolbar button.

\3. Move the marker projection to the desired location by dragging it using left mouse button. Once the
marker location is refined by user, the marker icon will change to
Note

• To list photos where the marker locations are defined, select the corresponding marker on the
Workspace pane. The photos where the marker is placed will be marked with a icon on the
Photos pane. To filter photos by marker use Filter by Markers command from the 3D view
context menu.

52

<!-- p. 59 -->

Referencing

In those cases when there are hesitations about the features depicted on the photo, comparative inspection
of two photos can prove to be useful. To open two photos in Metashape window simultaneously Move to
Other Tab Group command is available from photo tab header context menu.

To open two photos simultaneously

\1. In the Photos pane double click on one photo to be opened. The photo will be opened in a new tab
of the main program window.

\2. Right click on the tab header and choose Move to Other Tab Group command from the context menu.
The main program window will be divided into two parts and the photo will be moved to the second
part.

\3. The next photo you will choose to be opened with a double click will be visualized in the active tab
group.

Metashape automatically assigns default labels for each newly created marker. These labels can be changed
using the Rename... command from the marker context menu in the Workspace / Reference pane.
Assigning reference coordinates

To reference the model, real world coordinates of at least 3 points of the scene should be specified.
Depending on the requirements, the model can be referenced using marker coordinates, camera
coordinates, or both. Real world coordinates used for referencing the model along with the type of
coordinate system used are specified using the Reference pane.

The model can be located in either local Euclidean coordinates or in georeferenced coordinates. Metashape
supports a wide range of various geographic and projected coordinate systems, including widely used
WGS84 coordinate system. Besides, almost all coordinate systems from the EPSG registry are supported
as well.

Reference coordinates can be specified in one of the following ways:

• Loaded from a separate text file (using character separated values format).

• Entered manually in the Reference pane.

• Loaded from GPS EXIF tags (if present).

To load reference coordinates from a text file

\1. Click Import toolbar button on the Reference pane. (To open Reference pane use Reference
command from the View menu.) Browse to the file containing recorded reference coordinates and
click Open button.

\2. In the Import CSV dialog set the coordinate system if the data presents geographical coordinates.

\3. Select the delimiter and indicate the number of the data column for each coordinate.

\4. Indicate columns for the orientation data if present. Make sure that the proper angle triple (according
to the source data) is set: [yaw,pitch,roll] or [omega, phi, kappa].

\5. Click OK button. The reference coordinates data will be loaded onto the Reference pane.
Note

• In the data file columns and rows are numbered starting from 0.

53

<!-- p. 60 -->

Referencing

• If reference coordinates of a marker / camera position for a photo are not specified in the loading
file the current value will be kept for them.

• An example of a coordinates data file in the CSV format is given in the next section.

Information on the accuracy of the source coordinates (x, y, z) as well as of the source orientation angles
can be loaded with a CSV file as well. Check Load Accuracy option and indicate the number of the column
where the accuracy for the data should be read from. It is possible to indicate the same accuracy column
for all three coordinates/angles.

To assign reference coordinates manually

\1. Switch to the View Source mode using View Source button from the Reference pane toolbar. (To
open Reference pane use Reference command from the View menu.)

\2. On the Reference pane select x/y/z or angle data cells and press F2 button on the keyboard to assign
values to corresponding coordinates/angles.

\3. Repeat for every marker/camera position (orientation angle) needed to be specified.

\4. To remove unnecessary reference coordinates select corresponding items from the list and press Del
key.

\5. Click Update toolbar button to apply changes and set coordinates.

The format of the orientation data ([yaw,pitch,roll] or [omega, phi, kappa]) can be switched in the
Reference Settings dialog. Do not forget to click OK button in the Reference Settings dialog to apply the
changes.

Additionally, it is possible to indicate accuracy data for the coordinates / orientation angles. Select Set
Accuracy... command from the context menu of an image on the Reference pane and input accuracy data
both for position (i.e. x,y,z coordinates) and orientation (i.e. [yaw,pitch,roll] or [omega, phi, kappa] angles)
data. It is possible to select several cameras and apply Set Accuracy... command simultaneously to all of
them. Alternatively, you can select Accuracy (m) or Accuracy (deg) text box for a certain camera on the
Reference pane and press F2 button on the keyboard to type the text data directly onto the Reference pane.
Note that "/" delimiter allows to enter different accuracy data for x, y, z or yaw, pitch, roll (omega, phi,
kappa) data respectively.

To load reference coordinates from GPS EXIF tags

• Click Import EXIF button on the Reference pane. (To open Reference pane use Reference
command from the View menu.) The reference coordinates data will be loaded into the Reference
pane.

If the corresponding options on the Advanced tab of Preferences window are checked on, it is also possible
to load camera orientation angles and location/rotation accuracy parameters from XMP extension of the
image header. The data will be loaded on clicking Import EXIF button.

After reference coordinates have been assigned Metashape automatically estimates coordinates in a local
Euclidean system and calculates the referencing errors. To see the results switch to the View Estimated or
View Errors modes respectively using View Estimated and View Errors toolbar buttons.

54

<!-- p. 61 -->

Referencing

Setting georeferenced coordinate system

To set a georeferenced coordinate system

\1. Assign reference coordinates using one of the options described above.

\2. Click Settings button on the Reference pane toolbar.

\3. In the Reference Settings dialog box select the Coordinate System used to compile reference
coordinates data if it has not been set at the previous step.

\4. Specify the assumed measurement accuracy on the left-hand side part of the dialog.

\5. If the information about GPS system shift with respect to the camera itself is available, it worth
inputting it on GPS/INS Offset tab of Camera Calibration dialog available from tools menu. See
Figure below.

\6. Click OK button to initialize the coordinate system and estimate geographic coordinates.

GPS offset.

Rotation angles for the camera coordinates in Metashape are defined around the following axes: yaw axis
runs from top to bottom, pitch axis runs from left to right wing of the drone, roll axis runs from tail to nose
of the drone. Zero values of the rotation angle triple define the following camera position aboard: camera
looks down to the ground, frames are taken in landscape orientation, and horizontal axis of the frame is
perpendicular to the central (tail-nose) axis of the drone. If the camera is fixed in a different position,
respective yaw, pitch, roll values should be input on GPS/INS Offset tab of Camera Calibration dialog.
The signs of the angles are defined according to the right-hand rule. See Figure below.

55

<!-- p. 62 -->

Referencing

INS offset.
Note

• Step 5 can be safely skipped if you are using standard GPS system (not that of superhigh
precision).

In Select Coordinate System dialog it is possible to ease searching for the required georeferencing system
using Filter option. Enter respective EPSG code (e.g. EPSG::4302) to filter the systems.
Using different vertical datums

On default Metashape requires all the source altitude values for both cameras and markers to be input as
values mesuared above the ellipsoid. However, Metashape allows for the different geoid models utilization
as well. Metashape installation package includes only EGM96 geoid model, but additional geoid models
can be downloaded from Agisoft's website if they are required by the coordinate system selected in the
Reference pane settings dialog. Downloaded geoid model from the supported list should be copied to
\geoids\ folder in Metashape installation directory before using the corresponding coordinate system
from GUI.

Please refer to the following web-page to review the list of supported geoid models: http://
www.agisoft.com/downloads/geoids/.
Reference pane: some features more

To view the estimated geographic coordinates and reference errors switch between the View Estimated
and View Errors modes respectively using View Estimated and View Errors toolbar buttons. A
click on the column name on the Reference pane sorts the markers and cameras by the data in the column.

56

<!-- p. 63 -->

Referencing

At this point you can review the errors and decide whether additional refinement of marker locations is
required (in case of marker based referencing), or if certain reference points should be excluded.

To save the errors and/or estimated coordinates use Export toolbar button on the Reference pane.

To reset a chunk georeferencing, use Reset Transform command from the chunk context menu on the
Workspace pane. [R] indicator of a chunk being georeferenced will be removed from the chunk name.

Note

• Unchecked reference points on the Reference pane are not used for georeferencing and
optimization. Use context menu to check/uncheck selected items.

• After adjusting marker locations on the photos, the coordinate system will not be updated
automatically. It should be updated manually using Update toolbar button on the Reference
pane.

• Metashape allows to convert the estimated geographic coordinates into a different coordinate
system. To calculate the coordinates of the camera positions and/or markers in a different
coordinate system use Convert toolbar button on the Reference pane.
Example of a reference coordinates file in CSV format
(*.txt)

The reference coordinates can be loaded onto the Reference pane using character separated text file format.
Each reference point is specified in this file on a separate line. Sample reference coordinates file is provided
below:

\# \<label> \<longitude> \<latitude> \<altitude>
IMG_0159.JPG 40.165011 48.103654 433.549477
IMG_0160.JPG 40.165551 48.103654 434.724281
IMG_0161.JPG 40.166096 48.103640 435.630558

Individual entries on each line should be separated with a tab (space, semicolon, comma, etc)
character. All lines starting with # character are treated as comments.

Records from the coordinate file are matched to the corresponding cameras or markers basing on the
label field. Camera coordinates labels should match the file name of the corresponding photo including
extension. Marker coordinates labels should match the labels of the corresponding markers in the project
file. All labels are case insensitive.

Note

• Character separated reference coordinates format does not include specification of the type of
coordinate system used. The kind of coordinate system used should be selected separately in the
Reference Settings dialog.

• Metashape requires z value to indicate height above the ellipsoid.

57

<!-- p. 64 -->

Referencing

Optimization
Optimization of camera alignment

Metashape estimates internal and external camera orientation parameters during photo alignment. This
estimation is performed using image data alone, and there may be some errors in the final estimates. The
accuracy of the final estimates depends on many factors, like overlap between the neighboring photos, as
well as on the shape of the object surface. These errors can lead to non-linear deformations of the final
model.

During georeferencing the model is linearly transformed using 7 parameter similarity transformation (3
parameters for translation, 3 for rotation and 1 for scaling). Such transformation can compensate only a
linear model misalignment. The non-linear component can not be removed with this approach. This is
usually the main reason for georeferencing errors.

Possible non-linear deformations of the model can be removed by optimizing the estimated point cloud
and camera parameters based on the known reference coordinates. During this optimization Metashape
adjusts estimated point coordinates and camera parameters minimizing the sum of reprojection error and
reference coordinate misalignment error.

To achieve greater optimizing results it may be useful to edit sparse point cloud deleting obviously
mislocated points beforehand. To read about point cloud editing refer to the Editing point cloud section
of the manual.

Georeferencing accuracy can be improved significantly after optimization. It is recommended to perform
optimization if the final model is to be used for any kind of measurements.

To optimize camera alignment
\1. Set the marker and/or camera coordinates to be used for optimization (if not done yet).

\2. Click Settings toolbar button on the Reference pane and set the coordinate system (if not done yet).

\3. In the Reference pane Settings dialog box specify the assumed accuracy of measured values as well
as the assumed accuracy of marker projections on the source photos.

\4. Click OK button.

\5. Indicate relative GPS device and/or INS to camera coordinates (if info is available) on GPS/INS tab
of Camera Calibration dialog available from Tools menu.

\6. Check Fix GPS/INS offset box.

\7. Click OK button.

\8. Click Optimize toolbar button. In Optimize Camera Alignment dialog box check additional
camera parameters to be optimized if needed. Click OK button to start optimization.

\9. After the optimization is complete, the georeferencing errors will be updated.
Note
• Step 5 can be safely skipped if you are using standard GPS (not that of extremely high precision).

• Tangential distortion parameters p3, p4, are available for optimization only if p1, p2 values are
not equal to zero after alignment step.

58

<!-- p. 65 -->

Referencing

• The model data (if any) is cleared by the optimization procedure. You will have to rebuild the
model geometry after optimization.

Image coordinates accuracy for markers indicates how precisely the markers were placed by the user or
adjusted by the user after being automatically placed by the program.

Ground altitude parameter is used to make reference preselection mode of alignment procedure work
effectively for oblique imagery. See Aligning photos for details.

Camera, marker and scale bar accuracy can be set per item (i.d. per camera/marker/scale bar) using
Accuracy column on the Reference pane. Accuracy values can be typed in on the pane per item or for a
group of selected items. Alternatively accuracy values can be uploaded along with camera/marker data
as a text file (see Assigning reference coordinates subsection of Setting coordinate system). Additionally,
different accuracies per coordinate can be indicated using "/" as a separator between values in the Accuracy
column.

GPS/INS offset values input by the user can also be adjusted by Metashape with respect to measurement
accuracy that may be indicated on the GPS/INS tab of Camera Calibration dialog. Uncheck Fix GPS/INS
offset box to allow for adjustment procedure.

Generally it is reasonable to run optimization procedure based on markers data only. It is due to the fact that
GCPs coordinates are measured with significantly higher accuracy compared to GPS data that indicates
camera positions. Thus, markers data are sure to give more precise optimization results. Moreover, quite
often GCP and camera coordinates are measured in different coordinate systems, that also prevents from
using both cameras and markers data in optimization simultaneously.

The results of the optimization procedure can be evaluated with the help of error information on the
Reference pane. In addition, distortion plot can be inspected along with mean residuals visualized per
calibration group. This data is available from Camera Calibration dialog (Tools menu), from context menu
of a camera group - Distortion Plot... command. Note that residuals are averaged per cell of an image
and then across all the images in a camera group. Scale reference under the plot indicates the scale of the
distortions/residuals.

In case optimization results does not seem to be satisfactory, you can try recalculating with lower values
of accuracy parameters, i.e. assuming ground control measurements to be more accurate.
Scale bar based optimization

Scale bar is program representation of any known distance within the scene. It can be a standard ruler or
a specially prepared bar of a known length. Scale bar is a handy tool to add supportive reference data to
your project. They can prove to be useful when there is no way to locate ground control points all over
the scene. Scale bars allow to save field work time, since it is significantly easier to place several scale
bars with precisely known length, than to measure coordinates of a few markers using special equipment.
In addition, Metashape allows to place scale bar instances between cameras, thus making it possible to
avoid not only marker but ruler placement within the scene as well. Surely, scale bar based information
will not be enough to set a coordinate system, however, the information can be successfully used while
optimizing the results of photo alignment. It will also be enough to perform measurements in Metashape
software. See Performing measurements on 3D model.

To add a scale bar between markers

\1. Place markers at the start and end points of the bar. For information on marker placement please refer
to the Setting coordinate system section of the manual.

\2. Select both markers on the Reference pane using Ctrl button.

59

<!-- p. 66 -->

Referencing

\3. Select Create Scale Bar command form the Model view context menu. The scale bar will be
created and an instant added to the Scale Bar list on the Reference pane.

\4. Switch to the View Source mode using the Reference pane toolbar button.

\5. Double click on the Distance (m) box next to the newly created scale bar name and enter the known
length of the bar in meters.

To add a scale bar between cameras

\1. Select the two cameras on the Workspace or Reference pane using Ctrl button. Alternatively, the
cameras can be selected in the Model view window using selecting tools from the Toolbar.

\2. Select Create Scale Bar command form the context menu. The scale bar will be created and an
instant added to the Scale Bar list on the Reference pane.

\3. Switch to the View Source mode using the Reference pane toolbar button.

\4. Double click on the Distance (m) box next to the newly created scale bar name and enter the known
length of the bar in meters.

To run scale bar based optimization

\1. On the Reference pane check all scale bars to be used in optimization procedure.

\2. Click Settings toolbar button on the Reference pane. In the Reference pane Settings dialog box
specify the assumed accuracy of scale bars measurements.

\3. Click OK button.

\4. Click Optimize toolbar button. In Optimize Camera Alignment dialog box check additional
camera parameters to be optimized if needed. Click OK button to start optimization.

After the optimization is complete, cameras and markers estimated coordinates will be updated as well as
all the georeferencing errors. To analyze optimization results switch to the View Estimated mode using
the Reference pane toolbar button. In scale bar section of the Reference pane estimated scale bar distance
will be displayed.

To delete a scale bar

\1. Select the scale bar to be deleted on the Reference pane.

\2. Right-click on it and chose Remove Scale Bars command from the context menu.

\3. Click OK for the selected scale bar to be deleted.
What do the errors in the Reference pane mean?

Cameras section

\1. Error (m) - distance between the input (source) and estimated positions of the camera.

\2. Error (deg) - root mean square error calculated over all three orientation angles.

60

<!-- p. 67 -->

Referencing

\3. Error (pix) - root mean square reprojection error calculated over all feature points detected on the
photo.

Reprojection error is the distance between the point on the image where a reconstructed 3D point can be
projected and the original projection of that 3D point detected on the photo and used as a basis for the
3D point reconstruction procedure.

Markers section

\1. Error (m) - distance between the input (source) and estimated positions of the marker.

\2. Error (pix) - root mean square reprojection error for the marker calculated over all photos where
marker is visible.

Scale Bars section

• Error (m) - difference between the input (source) scale bar length and the measured distance between
two cameras or markers representing start and end points of the scale bar.

If the total reprojection error for some marker seems to be too large, it is recommended to inspect
reprojection errors for the marker on individual photos. The information is available with Show Info
command from the marker context menu on the Reference pane.
Working with coded and non-coded targets
Overview

Coded and non-coded targets are specially prepared, yet quite simple, real world markers that can add up
to successful 3D model reconstruction of a scene. The difference between coded and non-coded targets
is that while a non-coded target looks like an ordinary full circle or a figure (circle / rectangular) with 4
segments, the coded target has a ring parted in black and white segments around the central full circle.
Coded targets advantages and limitations

Coded targets (CTs) can be used as markers to define local coordinate system and scale of the model or as
true matches to improve photo alignment procedure. Metashape functionality includes automatic detection
and matching of CTs on source photos, which allows to benefit from marker implementation in the project
while saving time on manual marker placement. Moreover, automatic CTs detection and marker placement
is more precise then manual marker placement.

Metashape supports four types of circle CTs: 12 bit, 14 bit, 16 bit and 20 bit. While 12 bit pattern is
considered to be decoded more precisely, whereas 14 bit, 16 bit and 20 bit patterns allow for a greater
number of CTs to be used within the same project.

To be detected successfully CTs must take up a significant number of pixels on the original photos. This
leads to a natural limitation of CTs implementation: while they generally prove to be useful in close-range
imagery projects, aerial photography projects will demand too huge CTs to be placed on the ground, for
the CTs to be detected correctly.
Coded targets in workflow

Sets of all patterns of CTs supported by Metashape can be generated by the program itself.

61

<!-- p. 68 -->

Referencing

To create a printable PDF with coded targets

\1. Select Print Markers... command from the Tools menu.

\2. Specify the CTs type and desired print parameters in Print Markers dialog.

\3. Click OK.

Once generated, the pattern set can be printed and the CTs can be placed over the scene to be shot and
reconstructed.

When the images with CTs seen on them are uploaded to the program, Metashape can detect and match
the CTs automatically.

To detect coded targets on source images

\1. Select Detect Markers... command from the Tools menu.

\2. Specify parameters of detector in Detect Markers dialog according to the CTs type.

\3. Click OK.

Metashape will detect and match CTs and add corresponding markers to the Reference pane.

CTs generated with Metashape software contain even number of sectors. However, previous versions of
Metashape software had no restriction of the kind. Thus, if the project to be processed contains CTs from
previous versions of Metashape software, it is required to disable parity check in order to make the detector
work.
Non-coded targets implementation

Non-coded targets can also be automatically detected by Metashape (see Detect Markers dialog) .
However, for non-coded targets to be matched automatically, it is necessary to run align photos procedure
first.

Non-coded targets are more appropriate for aerial surveying projects due to the simplicity of the pattern
to be printed on a large scale. But, looking alike, they does not allow for automatic identification, so
manual assignment of an identifier is required if some referencing coordinates are to be imported from
a file correctly.

62

<!-- p. 69 -->

Chapter 5. Measurements
Performing measurements on 3D model

Metashape supports measuring of distances on the model, as well as of surface area and volume of the
reconstructed 3D model. All the instructions of this section are applicable for working in the Model view
of the program window, both for analysis of Dense Point Cloud or of Mesh data. When working in the
model view, all measurements are performed in 3D space, unlike measurements in Ortho view, which are
planar ones.
Distance measurement

Metashape enables measurements of distances between the points of the reconstructed 3D scene.
Obviously, model coordinate system must be initialized before the distance measurements can be
performed. Alternatively, the model can be scaled based on known distance (scale bar) information to
become suitable for measurements. For instructions on setting coordinate system please refer to the Setting
coordinate system section of the manual. Scale bar concept is described in the Optimization section.

To measure distance
\1. Select Ruler instrument from the Toolbar of the Model view.

\2. Click on the point of the model where the measurement should be started from.

\3. Upon the second click on the model the distance between the indicated points will be shown right
in the Model view.

\4. The distance can be measured along the polyline drawn with the Ruler.

\5. To complete the measurement and to proceed to a new one, please press Escape button on the
keyboard. The result of the measurement will be shown on the Console pane

Shape drawing is enabled in Model view as well. See Shapes section of the manual for information on
shape drawing. Measure command available from the context menu of a selected shape allows to learn the
coordinates of the vertices as well as the perimeter of the shape.

To measure several distances between pairs of points and automatically keep the resulting data, markers
can be used.

To measure distance between two markers
\1. Place the markers in the scene at the targeted locations. For information on marker placement please
refer to the Setting coordinate system section of the manual.

\2. Select both markers to be used for distance measurements on the Reference pane using Ctrl button.
\3. Select Create Scale Bar command form the 3D view context menu. The scale bar will be created
and an instant added to the Scale Bar list on the Reference pane.

\4. Switch to the estimated values mode using View Estimated button from the Reference pane
toolbar.

\5. The estimated distance for the newly created scale bar equals to the distance that should have been
measured.

63

<!-- p. 70 -->

Measurements

To measure distance between cameras

\1. Select the two cameras on the Workspace or Reference pane using Ctrl button. Alternatively, the
cameras can be selected in the Model view window using selecting tools from the Toolbar.

\2. Select Create Scale Bar command form the context menu. The scale bar will be created and an
instant added to the Scale Bar list on the Reference pane.

\3. Switch to the estimated values mode using View Estimated button from the Reference pane
toolbar.

\4. The estimated distance for the newly created scale bar equals to the distance that should have been
measured.
Note

• Please note that the scale bar used for distance measurements must be unchecked on the
Reference pane.
Note

• The distance values measured by Metashape are displayed in meters.
Surface area and volume measurement

Surface area or volume measurements of the reconstructed 3D model can be performed only after the scale
or coordinate system of the scene is defined. For instructions on setting coordinate system please refer to
the Setting coordinate system section of the manual.

To measure surface area and volume

\1. Select Measure Area and Volume... command from the Tools menu.

\2. The whole model surface area and volume will be displayed in the Measure Area and Volume dialog
box. Surface area is measured in square meters, while mesh volume is measured in cubic meters.

Volume measurement can be performed only for the models with closed geometry. If there are any holes
in the model surface Metashape will report zero volume. Existing holes in the mesh surface can be filled
in before performing volume measurements using Close Holes... command from the Tools menu.
Performing measurements on DEM

Metashape is capable of DEM-based point, distance, area, and volume measurements as well as of
generating cross-sections for a part of the scene selected by the user. Additionally, contour lines can be
calculated for the model and depicted either over DEM or Orthomosaic in Ortho view within Metashape
environment. Measurements on the DEM are controlled with shapes: points, polylines and polygons. For
information about how to create and work with shapes please refer to Shapes section of the manual.
Point measurement

Ortho view allows to measure coordinates of any point on the reconstructed model. X and Y coordinates
of the point indicated with the cursor as well as height of the point above the vertical datum selected by
the user are shown in the bottom right corner of the Ortho view.

64

<!-- p. 71 -->

Measurements

Distance measurement

To measure distance with a Ruler

\1. Select Ruler instrument from the Toolbar of the Ortho view.

\2. Click on the point of the DEM where the measurement should be started from.

\3. Upon the second click on the DEM the distance between the indicated points will be shown right
in the Ortho view.

\4. The distance can be measured along the polyline drawn with the Ruler.

\5. To complete the measurement and to proceed to a new one, please press Escape button on the
keyboard. The result of the measurement will be shown on the Console pane

To measure distance with shapes

\1. Connect the points of interest with a polyline using Draw Polyline tool from the Ortho view
toolbar.

\2. Double click on the last point to indicate the end of a polyline.

\3. Right button click on the polyline and select Measure... command from the context menu.

\4. In the Measure Shape dialog inspect the results. Perimeter value equals to the distance that should
have been measured.

In addition to polyline length value (see perimeter value in the Measure Shape), coordinates of the vertices
of the polyline are shown on the Planar tab of the Measure Shape dialog.
Note

• Measure option is available from the context menu of a selected polyline. To select a polyline,
double-click on it. A selected polyline is colored in red.
Area and volume measurement

To measure area and volume

\1. Draw a polygon on the DEM using Draw Polygon instrument to indicate the area to be measured.

\2. Right button click on the polygon and select Measure... command from the context menu.

\3. In the Measure Shape dialog inspect the results: see area value on the Planar tab and volume values
on the Volume tab.

Metashape allows to measure volume above best fit / mean level / custom level planes. Best fit and mean
level planes are calculated based on the drawn polygon vertices. Volume measured against custom level
plane allows to trace volume changes for the same area in the course of time.
Note

• Measure option is available from the context menu of a selected polygon. To select a polygon,
double-click on it. A selected polygon is colored in red.

65

<!-- p. 72 -->

Measurements

Cross sections and contour lines

Metashape enables to calculate cross sections, using shapes to indicate the plane(s) for a cut(s), the cut
being made with a plane parallel to Z axis. For a polyline/polygon the program will calculate profiles along
all the edges starting from the first drawn side.

To calculate cross section

\1. Indicate a line to make a cut of the model using Draw Polyline / Draw Polygon tool from the
Ortho view toolbar.

\2. Double click on the last point to indicate the end of a polyline.

\3. Right button click on the polyline/polygon and select Measure... command from the context menu.

\4. In the Measure Shape dialog inspect the results on the Profile tab of the dialog.

Generate Contours... command is available either from DEM label context menu on the Workspace pane
or from the Tools menu.

To generate contours

\1. Select Generate Contours... command from Tools menu.

\2. In the Generate Contours dialog select DEM as the source data for calculation.

\3. Set values for Minimal altitude, Maximal altitude parameters as well as the Interval for the contours.
All the values should be indicated in meters.

\4. Click OK button once done.

\5. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.

\6. When the procedure is finished, a shape layer with "contours" label will be added to the project file
structure shown on the Workspace pane.

Contour lines can be exported using Export Contours command from the contour lines label context menu
on the Workspace pane. Alternatively the command is available from the File menu. In the Export Contour
Lines dialog it is necessary to select the type of the contour lines to be exported. A .SHP file can store the
lines of the same type only: either polygons or polylines.
Vegetation indices calculation
Multispectral cameras

Metashape enables to calculate NDVI and other vegetation indices based on the multispectral imagery
input. Vegetation index formula can be set by the user, thus allowing for great flexibility in data analysis.
Calculated data can be exported as a grid of floating point index values calculated per pixel of orthomosaic
or as an orthomosaic in pseudocolors according to a palette set by the user. In case several indices
are calculated for the same orthomosaic, the results can be exported as a multichannel orthomosaic,
one channel per index. Furthermore, values of 3 different vegetation indices can be mixed to represent
combined results as a false color "RGB" image.

66

<!-- p. 73 -->

Measurements

To calculate a vegetation index

\1. Open orthomosaic in the Ortho tab double-clicking on the orthomosaic label on the Workspace pane.

\2. Open Raster Calculator tool using Raster Calculator button from the Ortho view toolbar.

\3. On the left-hand side of the Transform tab of the Raster Calculator dialog all the bands of the input
images are listed. Set a vegetation index expression on the Output Bands side of the tab using keyboard
input and operator buttons of the raster calculator if necessary. If the expression is valid, the line will
be marked with sign.

\4. You can set several vegetation index expressions to be calculated. Use , buttons to add/delete
lines in the list of output bands.

\5. Click OK button to have the index(ces) calculated. The result - orthomosaic with vegetation
index(ces) information, each index being stored in a separate channel, can be exported with Export
orthomosaic command from the File menu. For guidance on the export procedure, please refer to
NDVI data export section of the manual.

\6. Alternatively to Step 5, if you would like to have the index visualized in Ortho view of Metashape
window for inspection, follow Steps 6-12. Check Enable transform box and switch to the Palette tab
of the Raster Calculator dialog.

\7. Select output band in 'Use band' field on the Palette tab.

\8. Click Update button to have the histogram of the index values shown on the left-hand side of the
Palette tab.

\9. Select the range of meaningful index values either manually on the histogram or apply automatically
calculated range with the Auto button at the bottom of the tab.

\10. Select palette preset from the drop-down list on the right-hand side of the Palette tab.

\11. Click Apply button. Once the operation is completed - all the vegetation indices are calculated, the
index values stored in the selected output band (indices calculated according to the selected output
band expression set on the Transform tab of the Raster Calculator) will be shown in the Ortho view,
index values being visualized with pseudocolors according to the palette set in the Raster Calculator
dialog.

\12. You can either continue your work in Raster Calculator or click OK button to close the dialog.

Palette defines the color for each index value to be shown with. Metashape offers several standard palette
presets on the Palette tab of the Raster Calculator dialog. A preset (Heat, NDVI, Gray scale) can be chosen
from the drop-down list on the Palette tab of the Raster Calculator dialog. Alternatively, the user can
upload the palette from a Surfer Color Spectrum (*.clr) file ( Import Palette), preliminary prepared in
an external tool.

The palette can also be edited within Metashape environment using Add Color and Remove Color
buttons on the Palette tab of the Raster Calculator dialog. For each new line added to the palette a certain
index value should be typed in. Double click on the newly added line to type the value in. A customized
palette can be saved for future projects using Export Palette button on the Palette tab of the Raster
Calculator dialog.

67

<!-- p. 74 -->

Measurements

The range of meaningful index values can be manually adjusted on the left-hand side of the Palette tab or
set automatically with the Auto button at the bottom of the tab. Interpolate colors option can be checked
to introduce intermediate colors to the output image.

False color value on the drop-down list of the palette presets allows to visualize combined results of
particular 3 vegetation indices tackled as false RGB colors.
Note

• If you change the index expression for selected output band on the Transform tab, do not forget
to adjust Palette settings for visualization purposes: click Update button on the Palette tab to
have the histogram of the index values updated, set the range of the meaningful values, chose
the proper color palette.

• If you would like to inspect values of a different vegetation index, not the one already shown,
you need to set the corresponding formula in the selected band of the Output Band list on the
Transform tab of the Raster Calculator dialog.

• If you would like to see original multispectral orthomosaic, with no index calculation applied,
uncheck Enable transform option on the Transform tab of the Raster Calculator dialog and
click Apply/OK button. If the input images have three channels marked as R, G, B, then the
orthomosaic will be visualized as an RGB image (or false RGB). Otherwise, the spectral data
from the first channel will be visualized in gray scale.
Modified visible range cameras

Modified visible range cameras provide data in the form of three channel imagery, but those channels
do not contain standard R, G, B spectrum range information due to some physical manipulation done on
the sensor. For example, a Colored Infrared (CIR) camera by MAVinci records Red+NIR data in the first
channel, Green+NIR data in the second channel, and NIR data in the third one.

Modified visible range cameras are used for vegetation monitoring along with multispectral cameras. To
calculate vegetation indices with Metashape the data captured with a modified camera should be calibrated
first. This means we need to get pure R, G, NIR values to apply vegetation index formula. To perform
the calibration, one needs calibration matrix data. In this context, a calibration matrix is a matrix of linear
transformation of source light intensity values in each channel into absolute values of intensity.

In case of CIR camera by MAVinci, calibration matrix can be calculated based on the histograms for the
following relations: NIR/R, NIR/G. Calibration matrix spectrum values will be equal to the values of the
cut offs (kR, kG) of the corresponding histograms: C = {(kR, 0, -1), (0, kG, -1), (0, 0, 1)}. Then the vector of
the absolute intensity values for R, G, NIR spectrum bands, scaled according to NIR intensity value, can
be calculated as X1=C*X0, where C [3x3]- CIR calibration matrix, X0 [3x1]- vector of the source values
of the intensity for each band.

Metashape offers dialog to manually input values of the calibration matrix - see Color Matrix section of
the CIR Calibration tab in the Raster Calculator dialog. (The tab is available for 3 bands imagery only. If
the project deals with multispectral imagery, there is no need to calibrate the data.) One can either print in
the values, or select the values with sliders on the histograms. For a CIR camera by MAVinci, calibration
matrix values can be set automatically with the Auto button.

Once the calibration matrix values are set, click Apply button for Metashape to perform the calibration.
After that you can proceed to Transform and Palette tabs of the Raster Calculator to calculate vegetation
indices as described in the section above. Metashape will use calibrated values as Input Bands on the
Transform tab.

68

<!-- p. 75 -->

Measurements

Index based contour lines

Metashape enables to calculate contour lines based on the calculated index values.

To calculate contour lines based on vegetation index data

\1. Select Generate Contours... command from the orthomosaic icon context menu on the Workspace
pane, while index data is shown in the Ortho view.

\2. Select Orthomosaic as the source for the contours calculation.

\3. Adjust the min/max value and the interval parameters for the task.

\4. Press OK button to calculate index values.

\5. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.

\6. When the procedure is finished, a shape layer with "contours" label will be added to the project file
structure shown on the Workspace pane. The contour lines will be shown over the index data on the
Ortho tab.

69

<!-- p. 76 -->

Chapter 6. Editing
Using masks
Overview

Masks are used in Metashape to specify the areas on the photos which can otherwise be confusing to
the program or lead to incorrect reconstruction results. Masks can be applied at the following stages of
processing:

• Matching of the images

• Building depth maps

• Building 3D model texture

• Building Tiled Model

• Building Orthomosaic

Alignment of the photos
Masked areas can be excluded during feature point detection. Thus, the objects on the masked parts
of the photos are not taken into account while estimating camera positions. This is important in the
setups, where the object of interest is not static with respect to the scene, like when using a turn table
to capture the photos.

Masking may be also useful when the object of interest occupies only a small part of the photo. In
this case a small number of useful matches can be filtered out mistakenly as a noise among a much
greater number of matches between background objects.

Building dense point cloud
While building dense point cloud, masked areas are not used in the depth maps computation process.
Masking can be used to reduce the resulting dense cloud complexity, by eliminating the areas on the
photos that are not of interest.

Masked areas are always excluded from processing during dense point cloud and texture generation
stages, including Tiled Model generation process.

Let's take for instance a set of photos of some object. Along with an object itself on each photo some
background areas are present. These areas may be useful for more precise camera positioning, so it
is better to use them while aligning the photos. However, impact of these areas at the building dense
point cloud is exactly opposite: the resulting model will contain object of interest and its background.

70

<!-- p. 77 -->

Editing

Background geometry will "consume" some part of mesh polygons that could be otherwise used for
modeling the main object.

Setting the masks for such background areas allows to avoid this problem and increases the precision
and quality of geometry reconstruction.

Building texture atlas
During texture atlas generation (for single mesh model and tiled model), masked areas on the photos
are not used for texturing. Masking areas on the photos that are occluded by outliers or obstacles helps
to prevent the "ghosting" effect on the resulting texture atlas.
Loading masks

Masks can be loaded from external sources, as well as generated automatically from background images
if such data is available. Metashape supports loading masks from the following sources:

• From alpha channel of the source photos.

• From separate images.

• Generated from background photos based on background differencing technique.

• Based on reconstructed 3D model.

To import masks

\1. Select Import Masks... command from the File menu.

\2. In the Import Mask dialog select suitable parameters. Click OK button when done.

\3. When generating masks from separate or background images, the folder selection dialog will appear.
Browse to the folder containing corresponding images and select it.

\4. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.

The following parameters can be specified during mask import:

Method
Specifies the source of the mask data.

From Alpha - load masks from alpha channel of the source photos.

From File - load masks from separate images.

From Background - generate masks from background photos.

From Model - generate masks based on reconstructed model.

Operation
Specifies the action to be done in case a second mask is imported for the photo.

Replacement - new mask will be loaded and stored instead of the original one.

Union - two masks will be united and stored.

Intersection - the intersection of the two masks will be stored as a new mask for the photo.

71

<!-- p. 78 -->

Editing

Difference - only the difference between two masks will be stored as a new mask for the photo.

Filename template (not used in From alpha mode)
Specifies the file name template used to generate mask file names. This template can contain special
tokens, that will be substituted by corresponding data for each photo being processed. The following
tokens are supported:

{filename} - file name of the source photo without extension.

{fileext} - extension of the source photo.

{camera} - camera label.

{frame} - frame number.

{filenum} - sequential number of the mask being imported.

For example, {filename}_mask.png template can be used if masks are available in PNG format and
have a _mask suffix.

Tolerance (From Background method only)
Specifies the tolerance threshold used for background differencing. Tolerance value should be set
according to the color separation between foreground and background pixels. For larger separation
higher tolerance values can be used.

Apply to
Specifies whether masks should be imported for the currently opened photo, active chunk or entire
Workspace.

All cameras - load masks for active chunk.

Entire workspace - load masks for all chunks in the project.

Selected cameras - load mask for the currently checked cameras (if any).

Current photo - load mask for the currently opened photo (if any).
Editing masks

Modification of the current mask is performed by adding or subtracting selections. A selection is created
with one of the supported selection tools and is not incorporated in the current mask until it is merged with
a mask using Add Selection or Subtract Selection operations.

To edit the mask

\1. Open the photo to be masked by double clicking on its name on the Workspace / Photo pane. The
photo will be opened in the main window. The existing mask will be displayed as a shaded region
on the photo.

\2. Select the desired selection tool and generate a selection.

\3. Click on Add Selection toolbar button to add current selection to the mask, or Subtract
Selection to subtract the selection from the mask. Invert Selection button allows to invert current
selection prior to adding or subtracting it from the mask.

72

<!-- p. 79 -->

Editing

The following tools can be used for creating selections:

Rectangle selection tool
Rectangle selection tool is used to select large areas or to clean up the mask after other selection tools
were applied.

Intelligent scissors tool
Intelligent scissors is used to generate a selection by specifying its boundary. The boundary is formed
by selecting a sequence of vertices with a mouse, which are automatically connected with segments.
The segments can be formed either by straight lines, or by curved contours snapped to the object
boundaries. To enable snapping, hold Ctrl key while selecting the next vertex. To complete the
selection, the boundary should be closed by clicking on the first boundary vertex.

Intelligent paint tool
Intelligent paint tool is used to "paint" a selection by the mouse, continuously adding small image
regions, bounded by object boundaries.

Magic wand tool
Magic Wand tool is used to select uniform areas of the image. To make a selection with a Magic
Wand tool, click inside the region to be selected.

The range of pixel colors selected by Magic Wand is controlled by the tolerance value. At lower
tolerance values the tool selects fewer colors similar to the pixel you click with the Magic Wand tool.
Higher value broadens the range of colors selected.
Note

• To add new area to the current selection hold the Ctrl key during selection of additional area.

• To reset mask selection on the current photo press Esc key.

A mask can be inverted using Invert Mask command from the Edit menu. The command is active in Photo
View only. Alternatively, you can invert masks either for selected cameras or for all cameras in a chunk
using Invert Masks... command from a photo context menu on the Photos pane.

The masks are generated individually for each image. If some object should be masked out, it should be
masked out on all photos, where that object appears.
Saving masks

Created masks can be also saved for external editing or storage.

To export masks

\1. Select Export Masks... command from the File menu.

\2. In the Export Mask dialog select suitable parameters. Click OK button when done.

\3. Browse to the folder where the masks should be saved and select it.

\4. The progress dialog box will appear displaying the current processing status. To cancel processing
click Cancel button.

The following parameters can be specified during mask export:

73

<!-- p. 80 -->

Editing

Export masks for
Specifies whether masks should be exported for the currently opened photo, active chunk or entire
Workspace.

Current photo - save mask for the currently opened photo (if any).
Active chunk - save masks for active chunk.
Entire workspace - save masks for all chunks in the project.
File type
Specifies the type of generated files.

Single channel mask image - generates single channel black and white mask images.
Image with alpha channel - generates color images from source photos combined with mask
data in alpha channel.

Mask file names
Specifies the file name template used to generate mask file names. This template can contain special
tokens, that will be substituted by corresponding data for each photo being processed. The following
tokens are supported:

{filename} - file name of the source photo without extension.
{fileext} - extension of the source photo.
{camera} - camera label.
{frame} - frame number.
{filenum} - sequential number of the mask being exported.
For example, {filename}_mask.png template can be used to export masks in PNG format with _mask
suffix.
Note
• When importing/exporting mask for the current photo only, Metashape will prompt for the actual
image instead of image folder. Mask file names parameter will not be used in this case.
Editing point cloud

The following point cloud editing tools are available in Metashape:

• Automatic filtering based on specified criterion (sparse cloud only)

• Automatic filtering based on applied masks (dense cloud only)

• Automatic filtering based on points colors (dense cloud only)

• Reducing number of points in cloud by setting tie point per photo limit (sparse cloud only)

• Manual points removal
Note
• Point cloud editing operation can be undone/redone using Undo/Redo command from the Edit
menu.

74

<!-- p. 81 -->

Editing

Filtering points based on specified criterion

In some cases it may be useful to find out where the points with high reprojection error are located within
the sparse cloud, or remove points representing high amount of noise. Point cloud filtering helps to select
such points, which usually are supposed to be removed.

Metashape supports the following criteria for point cloud filtering:

Reprojection error
High reprojection error usually indicates poor localization accuracy of the corresponding point
projections at the point matching step. It is also typical for false matches. Removing such points can
improve accuracy of the subsequent optimization step.

Reconstruction uncertainty
High reconstruction uncertainty is typical for points, reconstructed from nearby photos with small
baseline. Such points can noticeably deviate from the object surface, introducing noise in the point
cloud. While removal of such points should not affect the accuracy of optimization, it may be useful
to remove them before building geometry in Point Cloud mode or for better visual appearance of the
point cloud.

Image count
Metashape reconstruct all the points that are visible at least on two photos. However, points that are
visible only on two photos are likely to be located with poor accuracy. Image count filtering enables
to remove such unreliable points from the cloud.

Projection Accuracy
This criterion allows to filter out points which projections were relatively poorer localized due to their
bigger size.

To remove points based on specified criterion

\1. Switch to Point Cloud view mode using Point Cloud toolbar button.

\2. Select Gradual Selection... command from the Model menu.

\3. In the Gradual Selection dialog box specify the criterion to be used for filtering. Adjust the threshold
level using the slider. You can observe how the selection changes while dragging the slider. Click
OK button to finalize the selection.

\4. To remove selected points use Delete Selection command from the Edit menu or click Delete
Selection toolbar button (or simply press Del button on the keyboard).
Filtering points based on applied masks

To remove points based on applied masks

\1. Switch to Dense Cloud view mode using Dense Cloud toolbar button.

\2. Choose Select Masked Points... command from the Dense Cloud submenu of the Tools menu.

\3. In the Select Masked Points dialog box indicate the photos whose masks to be taken into account.
Adjust the edge softness level using the slider. Click OK button to run the selection procedure.

75

<!-- p. 82 -->

Editing

\4. To remove selected points use Delete Selection command from the Edit menu or click Delete
Selection toolbar button (or simply press Del button on the keyboard).
Filtering points based on points colors

To remove points based on points colors

\1. Switch to Dense Cloud view mode using Dense Cloud toolbar button.

\2. Choose Select Points by Color... command from the Dense Cloud submenu of the Tools menu.

\3. In the Select Points by Color dialog box the color to be used as the criterion. Adjust the tolerance
level using the slider. Click OK button to run the selection procedure.

\4. To remove selected points use Delete Selection command from the Edit menu or click Delete
Selection toolbar button (or simply press Del button on the keyboard).
Tie point per photo limit

Tie point limit parameter could be adjusted before Align photos procedure. The number indicates the upper
limit for matching points for every image. Using zero value doesn't apply any tie-point filtering.

The number of tie points can also be reduced after the alignment process with Tie Points - Thin Point Cloud
command available from Tools menu. As a results sparse point cloud will be thinned, yet the alignment
will be kept unchanged.
Manual points removal

Incorrect points can be also removed manually.

To remove points from a point cloud manually

\1. Switch to Sparse Cloud view mode using Point Cloud toolbar button or to Dense Cloud view
mode using Dense Cloud toolbar button.

\2. Select points to be removed using Rectangle Selection, Circle Selection or Free-Form
Selection tools. To add new points to the current selection hold the Ctrl key during selection of
additional points. To remove some points from the current selection hold the Shift key during
selection of points to be removed.

\3. To delete selected points click the Delete Selection toolbar button or select Delete Selection
command from the Edit menu. To crop selection to the selected points click the Crop Selection
toolbar button or select Crop Selection command from the Edit menu.
Classifying dense cloud points

Metashape allows not only to generate and visualize dense point cloud but also to classify the points within
it. There are two options: automatic division of all the points into two classes - ground points and the rest,
and manual selection of a group of points to be placed in a certain class from the standard list known for
LIDAR data. Dense cloud points classification opens way to customize Build Mesh step: you can choose

76

<!-- p. 83 -->

Editing

what type of objects within the scene you would like to be reconstructed and indicate the corresponding
point class as a source data for mesh generation. For example, if you build mesh or DEM based on ground
points only, it will be possible to export DTM (as opposed to DSM) at the next step.
Automatic classification of ground points

For the user to avoid extra manual work Metashape offers feature for automatic detection of ground points.

To classify ground points automatically

\1. Select Classify Ground Points... command from the Dense Cloud submenu of the Tools menu.

\2. In the Classify Ground Points dialog box select the source point class for the classification procedure.

\3. Click OK button to run the classification procedure.

Automatic classification procedure consists of two steps. At the first step the dense cloud is divided into
cells of a certain size. In each cell the lowest point is detected. Triangulation of these points gives the first
approximation of the terrain model.

Additionally, at this step Metashape filters out some noise points to be handled as Low Points class.

At the second step new point is added to the ground class, providing that it satisfies two conditions: it lies
within a certain distance from the terrain model and that the angle between terrain model and the line to
connect this new point with a point from a ground class is less than a certain angle. The second step is
repeated while there still are points to be checked.

The following parameters control automatic ground points classification procedure

Max angle (deg)
Determines one of the conditions to be checked while testing a point as a ground one, i.e. sets limitation
for an angle between terrain model and the line to connect the point in question with a point from a
ground class. For nearly flat terrain it is recommended to use default value of 15 deg for the parameter.
It is reasonable to set a higher value, if the terrain contains steep slopes.

Max distance (m)
Determines one of the conditions to be checked while testing a point as a ground one, i.e. sets limitation
for a distance between the point in question and terrain model. In fact, this parameter determines the
assumption for the maximum variation of the ground elevation at a time.

Cell size (m)
Determines the size of the cells for point cloud to be divided into as a preparatory step in ground
points classification procedure. Cell size should be indicated with respect to the size of the largest
area within the scene that does not contain any ground points, e. g. building or close forest.
Automatic dense cloud multi-class classification

Metashape allows for semantic classification of dense point clouds to solve the task of higher-level
interpretation of the reconstructed data. Using the machine learning techniques Metashape enables
automatic dense cloud classification to any combination of the following classes: Ground, High
Vegetation, Building, Road, Car and Man-made.

To start the automatic multi-class classification

\1. Select Classify Points... command from the Dense Cloud submenu of the Tools menu.

77

<!-- p. 84 -->

Editing

\2. In the Classify Points dialog box select the source point class for the classification procedure in the
"From" field.

\3. Select the target classes from the list in "To" field.

\4. Define Confidence parameter in 0 - 1 range. Higher value of the parameter means that the point
which class cannot be reliably assigned, will remain unclassified.

\5. Click OK button to run the classification procedure.
Note

• If you are not satisfied with the automatic multi-class classification results or would like
to contribute and improve the classificator, please send the manually labeled point clouds
according to the guidelines published on the following page to support@agisoft.com: http://
www.agisoft.com/support/tips-tricks/
Manual classification of dense cloud points

Metashape allows to associate all the points within the dense cloud with a certain standard class (see
LIDAR data classification). This provides possibility to diversify export of the processing results with
respect to different types of objects within the scene, e. g. DTM for ground, mesh for buildings and point
cloud for vegetation.

To assign a class to a group of points

\1. Switch to Dense Cloud view mode using using Dense Cloud toolbar button.

\2. Select points to be placed to a certain class using Rectangle Selection, Circle Selection or
Free-Form Selection tools. To add new points to the current selection hold the Ctrl key during
selection of additional points. To remove some points from the current selection hold the Shift key
during selection of points to be removed.

\3. Select Assign Class... command from the Dense Cloud submenu of the Tools menu.

\4. In the Assign Class dialog box select the source point data for the classification procedure and the
targeted class to be assigned to the selected points. Click OK button to run classification procedure.

Dense point cloud classification can be reset with Reset Classification command from Tools - Dense Cloud
menu.
Editing model geometry

The following mesh editing tools are available in Metashape:

• Decimation tool

• Close Holes tool

• Smooth tool

• Automatic filtering based on specified criterion

78

<!-- p. 85 -->

Editing

• Manual polygon removal

• Fixing mesh topology

• Refinement tool

More complex editing can be done in the external 3D editing tools. Metashape allows to export mesh and
then import it back for this purpose.
Note

• For polygon removal operations such as manual removal and connected component filtering it
is possible to undo the last mesh editing operation. There are Undo/Redo commands in the Edit
menu.

• Please note that undo/redo commands are not supported for mesh decimation and this operation
cannot be undone.
Decimation tool

Decimation is a tool used to decrease the geometric resolution of the model by replacing high resolution
mesh with a lower resolution one, which is still capable of representing the object geometry with high
accuracy. Metashape tends to produce 3D models with excessive geometry resolution, so mesh decimation
is usually a desirable step after geometry computation.

Highly detailed models may contain hundreds of thousands polygons. While it is acceptable to work with
such a complex models in 3D editor tools, in most conventional tools like Adobe Reader or Google Earth
high complexity of 3D models may noticeably decrease application performance. High complexity also
results in longer time required to build texture and to export model in pdf file format.

In some cases it is desirable to keep as much geometry details as possible like it is needed for scientific and
archive purposes. However, if there are no special requirements it is recommended to decimate the model
down to 100 000 - 200 000 polygons for exporting in PDF, and to 100 000 or even less for displaying in
Google Earth and alike tools.

To decimate 3D model

\1. Select Decimate Mesh... command from the Tools menu.

\2. In the Decimate Mesh dialog box specify the target number of polygons, which should remain in the
final model. Click on the OK button to start decimation.

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click on the Cancel button.
Note

• Texture atlas is discarded during decimation process. You will have to rebuild texture atlas after
decimation is complete.
Close Holes tool

Close Holes tool provides possibility to repair your model if the reconstruction procedure resulted in a
mesh with several holes, due to insufficient image overlap for example.

79

<!-- p. 86 -->

Editing

Some tasks require a continuous surface disregarding the fact of information shortage. It is necessary to
generate a close model, for instance, to fulfill volume measurement task with Metashape.

Close holes tool enables to close void areas on the model substituting photogrammetric reconstruction
with extrapolation data. It is possible to control an acceptable level of accuracy indicating the maximum
size of a hole to be covered with extrapolated data.

To close holes in a 3D model

\1. Select Close Holes... command from the Tools menu.

\2. In the Close Holes dialog box indicate the maximum size of a hole to be covered with the slider. Click
on the OK button to start the procedure.

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click on the Cancel button.
Note

• The slider allows to set the size of a hole in relation to the size of the whole model surface.
Polygon filtering on specified criterion

In some cases reconstructed geometry may contain the cloud of small isolated mesh fragments surrounding
the "main" model or big unwanted polygons. Mesh filtering based on different criteria helps to select
polygons, which usually are supposed to be removed.

Metashape supports the following criteria for face filtering:

Connected component size
This filtering criteria allows to select isolated fragments with a certain number of polygons. The
number of polygons in all isolated components to be selected is set with a slider and is indicated in
relation to the number of polygons in the whole model. The components are ranged in size, so that
the selection proceeds from the smallest component to the largest one.

Polygon size
This filtering criteria allows to select polygons up to a certain size. The size of the polygons to be
selected is set with a slider and is indicated in relation to the size of the whole model. This function
can be useful, for example, in case the geometry was reconstructed in Smooth type and there is a need
to remove extra polygons automatically added by Metashape to fill the gaps; these polygons are often
of a larger size that the rest.

To remove small isolated mesh fragments

\1. Select Gradual Selection... command from the Edit menu.

\2. In the Gradual Selection dialog box select Connected component size criterion.

\3. Select the size of isolated components to be removed using the slider. Size of the largest component
is taken for 100%. You can observe how the selection changes while dragging the slider. Click OK
button to finalize the selection.

\4. To remove the selected components use Delete Selection command from the Edit menu or click
Delete Selection toolbar button (or simply press Del button on the keyboard).

80

<!-- p. 87 -->

Editing

To remove large polygons

\1. Select Gradual Selection... command from the Edit menu.

\2. In the Gradual Selection dialog box select Polygon size criterion.

\3. Select the size of polygons to be removed using the slider. Size of the largest polygon is taken for
100%. You can observe how the selection changes while dragging the slider. Click OK button to
finalize the selection.

\4. To remove the selected components use Delete Selection command from the Edit menu or click
Delete Selection toolbar button (or simply press Del button on the keyboard).

Note that Metashape always selects the fragments starting from the smallest ones. If the model contains
only one component the selection will be empty.
Manual face removal

Unnecessary and excessive sections of model geometry can be also removed manually.

To remove part of the mesh polygons manually

\1. Select rectangle, circle or free-form selection tool using Rectangle Selection, Circle Selection
or Free-Form Selection toolbar buttons.

\2. Make the selection using the mouse. To add new polygons to the current selection hold the Ctrl key
during selection of additional polygons. To remove some polygons from the current selection hold
the Shift key during selection of polygons to be excluded.

\3. To delete selected polygons click the Delete Selection toolbar button or use Delete Selection
command from the Edit menu. To crop selection to the selected polygons click the Crop Selection
toolbar button or use Crop Selection command from the Edit menu.

To grow or shrink current selection

\1. To grow current selection press PageUp key in the selection mode. To grow selection by even a larger
amount, press PageUp while holding Shift key pressed.

\2. To shrink current selection press PageDown key in the selection mode. To shrink selection by even
a larger amount, press PageDown while holding Shift key pressed.
Fixing mesh topology

Metashape is capable of basic mesh topology fixing.

To fix mesh topology

\1. Select View Mesh Statistics... command from the Tools menu.

\2. In the Mesh Statistics dialog box you can inspect mesh parameters. If there are any topological
problems, Fix Topology button will be active and can be clicked to solve the problems.

81

<!-- p. 88 -->

Editing

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click on the Cancel button.
Editing mesh in the external program

To export mesh for editing in the external program

\1. Select Export Model... command from the File menu.

\2. In the Save As dialog box, specify the desired mesh format in the Save as type combo box. Select the
file name to be used for the model and click Save button.

\3. In the opened dialog box specify additional parameters specific to the selected file format. Click OK
button when done.

To import edited mesh

\1. Select Import Mesh... command from the File menu.

\2. In the Open dialog box, browse to the file with the edited model and click Open.
Note

• Metashape supports loading models in Wavefront OBJ, 3DS, STL, COLLADA, Stanford PLY,
Autodesk FBX, Autodesk DXF, OpenCTM and U3D file formats only. Please make sure to select
one of these file formats when exporting model from the external 3D editor.

• Please be aware that it is important to keep reference information for the model if any.
Shapes

Shapes are used to indicate boundaries either for DEM/Orthomosaic export or for measurement
procedures. Shapes can be drawn over DEM or Orthomosaic as well as over model using buttons from the
Ortho/Model view toolbar. Alternatively, shapes can be loaded from a .SHP/.DXF/.KML files using Import
Shapes... subcommand of Import... command available from the File menu. Shapes created in Metashape
can be exported using Export Shapes... subcommand of Export... command available from the File menu.

To draw a shape on DEM/Orthomosaic/Model

\1. Open DEM/orthomosaic in Ortho view double clicking on DEM/orthomosaic label in the Workspace
pane. Alternatively, model in Model view.

\2. Select Draw Point / Draw Polyline / Draw Polygon instrument from the toolbar.

\3. Draw a point/polyline/polygon on the DEM/orthomosaic/model with a cursor.

\4. Double click on the last point to indicate the end of a polyline. To complete a polygon, place the end
point over the starting one.

\5. Once the shape is drawn, a shape label will be added to the chunk data structure on the Workspace
pane. All shapes drawn on the same model (and on the corresponding DEM and orthomosaic) will
be shown under the same label on the Workspace pane.

\6. The program will switch to a navigation mode once a shape is completed.

82

<!-- p. 89 -->

Editing

Drawing shapes in 3D (on the model) solves issues with building basements and other features which are
not visible on the orthomosaic. However, drawing on a model might not be accurate enough. For this case
Metashape offers possibility to draw a shape on source photos and automatically reconstruct it in 3D.

To automatically reconstruct a shape in 3D

\1. Go to Preferences dialog available from Tools menu and enable "Attach markers to vertices on
photos" option on Advanced tab.

\2. Open a photo in Photo view double clicking on the photo thumbnail in the Photo pane.

\3. Select Draw Point / Draw Polyline / Draw Polygon instrument from the toolbar.

\4. Draw a point/polyline/polygon on the photo with a cursor.

\5. Double click on the last point to indicate the end of a polyline. To complete a polygon, place the end
point over the starting one. All the vertices will be indicated with markers.

\6. Switch to Model view to see that the shape has been reconstructed in 3D automatically.

\7. To refine the position of the shape, filter photos by shape using the corresponding command from the
shape context menu. The shape must be selected - to select a shape double click on it.

\8. Inspect all the relevant photos to refine markers-vertices positions where necessary. The position of
the shape in 3D will automatically be refined.

After a shape has been drawn, it can be edited using Insert Vertex / Delete Vertex commands from the
context menu. Delete Vertex command is active only for a vertex context menu. To get access to the vertex
context menu, select the shape with a double click first, and then select the vertex with a double click on
it. To change position of a vertex, drag and drop it to a selected position with the cursor. Positions of the
markers-vertices cannot be changed in the model view.

Shapes allow to measure distances both on DEM and 3D model and to measure coordinates, surface
areas and volumes on 3D model. Please refer to Performing measurements on 3D model, Performing
measurements on DEM sections of the Manual for details.

Shapes added to the particular chunk of the project can be organized into layers. The first layer is generated
automatically on creation of the first shape and is placed into the Shapes folder on the project tree. This
layer is meant to serve as a background thus named No Layer. It is originally set as default one to store
all the shapes.

To create a new layer use Create Shape Layer command from the context menu of the Shape folder on
the Workspace pane. A layer can be set as default one using Set as default command from the context
menu of the layer name on the Workspace pane. A newly created layer can be renamed with a relevant
command from the context menu.

Export Layers... command from the context menu of a layer allows to save shapes from the layer in one
of the supported export formats available: shp, dxf, kml.

A shape can be labeled and saved to a certain layer using Properties... command from the context menu
of the shape in the Model/Ortho view.
Orthomosaic seamlines editing

Metashape software offers various blending options at orthomosaic generation step for the user to adjust
processing to their data and task. However, in some projects moving objects can cause artifacts which

83

<!-- p. 90 -->

Editing

interfere with visual quality of the orthomosaic. The same problem may result from oblique aerial imagery
processing if the area of interest contains high buildings or if the user has captured facade from too oblique
positions. To eliminate mentioned artifacts Metashape offers seamline editing tool. The functionality
allows to choose manually the image or images to texture the indicated part of the orthomosaic from. Thus,
the final orthomosaic can be improved visually according to the user's expectations.

Automatic seamlines can be turned on for inspection in the Ortho view with pressing the Show
Seamlines button from the Ortho view toolbar.

To edit orthomosaic seamlines

\1. Draw a polygon on the orthomosaic using Draw Polygon instrument to indicate the area to be
retextured.

\2. Select Assign Images... command from the context menu of the selected polygon.

\3. In the Assign Images dialog box select the image to texture the area inside the polygon from.
Orthomosaic preview on the Ortho tab allows to evaluate the results of the selection. Click OK button
to finalise the image selection process.

\4. Click Update Orthomosaic button from the Ortho view toolbar to apply the changes.

Assign Images dialog allows to activate multiple selection option. If the Allow multiple selection option
is checked, it is possible to assign several images to texture the area inside the polygon from. However, in
this case there is no possibility to preview the resulting orthomosaic. It is necessary to Click Update
Orthomosaic button from the Ortho view toolbar to apply the changes and see the results. Until the changes
are applied, the area of interest will be marked with a net of blue color to indicate that some edits are waiting
for enforcement. Blending method selected at build orthomosaic step will be implemented at orthomosaic
editing step.

Assign Images dialog, alternatively, allows to exclude selected images from texturing the area of interest.
Check Exclude selected images option to follow this way. Please note that in this case preview illustrates
the image to be excluded, i.d. the results one should expect after applying the changes are not shown. Click
Update Orthomosaic button from the Ortho view toolbar to apply the changes

84

<!-- p. 91 -->

Chapter 7. Automation
Using chunks

When working with typical data sets, automation of general processing workflow allows to perform routine
operations efficiently. Metashape allows to assign several processing steps to be run one by one without
user intervention thanks to Batch Processing feature. Manual user intervention can be minimized even
further due to 'multiple chunk project' concept, each chunk to include one typical data set. For a project with
several chunks of the same nature, common operations available in Batch Processing dialog are applied to
each selected chunk individually, thus allowing to set several data sets for automatic processing following
predefined workflow pattern.

In addition, multiple chunk project could be useful when it turns out to be hard or even impossible to
generate a 3D model of the whole scene in one go. This could happen, for instance, if the total amount
of photographs is too large to be processed at a time. To overcome this difficulty Metashape offers a
possibility to split the set of photos into several separate chunks within the same project. Alignment of
photos, building dense point cloud, building mesh, and forming texture atlas operations can be performed
for each chunk separately and then resulting 3D models can be combined together.

Working with chunks is not more difficult than using Metashape following the general workflow. In fact,
in Metashape always exists at least one active chunk and all the 3D model processing workflow operations
are applied to this chunk.

To work with several chunks you need to know how to create chunks and how to combine resulting 3D
models from separate chunks into one model.
Creating a chunk

To create new chunk click on the Add Chunk toolbar button on the Workspace pane or select Add
Chunk command from the Workspace context menu (available by right-clicking on the root element on
the Workspace pane).

After the chunk is created you may load photos in it, align them, generate dense point cloud, generate mesh
surface model, build texture atlas, export the models at any stage and so on. The models in the chunks
are not linked with each other.

The list of all the chunks created in the current project is displayed in the Workspace pane along with
flags reflecting their status.

The following flags can appear next to the chunk name:

R (Referenced)
Indicates that 3D model in the chunk was referenced. Also will appear when two or more chunks are
aligned with each other. See information on how to reference the model in Setting coordinate system.

S (Scaled)
Indicates that 3D model in the chunk was scaled based on scale bars information only, with no
reference coordinates data being present. See information on scale bar placement in Optimization
section.

T (Transformed)
Indicates that 3D model has been modified manually with at least one of the following instruments:
Rotate object, Move object or Scale object.

85

<!-- p. 92 -->

Automation

To move photos from one chunk to another simply select them in the list of photos on the Workspace pane,
and then drag and drop to the target chunk.
Working with chunks

All operations within the chunk are carried out following the common workflow: loading photographs,
aligning them, generating dense point cloud, building mesh, building texture atlas, exporting 3D model
and so on.

Note that all these operations are applied to the active chunk. When a new chunk is created it is activated
automatically. Save project operation saves the content of all chunks. To save selected chunks as a separate
project use Save Chunks command from the chunk context menu.

To set another chunk as active
\1. Right-click on the chunk title on the Workspace pane.

\2. Select Set Active command from the context menu.

To remove chunk
\1. Right-click on the chunk title on the Workspace pane.

\2. Select Remove Chunks command from the context menu.

To rearrange the order of chunks in the Workspace pane simply drag and drop the chunks in the pane.
Aligning chunks

After the "partial" 3D models are built in several chunks they can be merged together. Before merging
chunks they need to be aligned.

To align separate chunks
\1. Select Align Chunks command from the Workflow menu.

\2. In the Align Chunks dialog box select chunks to be aligned, indicate reference chunk with a double-
click. Set desired alignment options. Click OK button when done.

\3. The progress dialog box will appear displaying the current processing status. To cancel processing
click the Cancel button.
Aligning chunks parameters

The following parameters control the chunks alignment procedure and can be modified in the Align Chunks
dialog box:

Method
Defines the chunks alignment method. Point based method aligns chunks by matching photos
across all the chunks. Marker based method uses markers as common points for different chunks.
The details on using markers are available in the Setting coordinate system section. Camera based
method is used to align chunks based on estimated camera locations. Corresponding cameras should
have the same label.

Accuracy (Point based alignment only)
Higher accuracy setting helps to obtain more accurate chunk alignment results. Lower accuracy setting
can be used to get the rough chunk alignment in the shorter time.

86

<!-- p. 93 -->

Automation

Point limit (Point based alignment only)
The number indicates upper limit of feature points on every image to be taken into account during
Point based chunks alignment.

Fix scale
Option is to be enabled in case the scales of the models in different chunks were set precisely and
should be left unchanged during chunks alignment process.

Preselect image pairs (Point based alignment only)
The alignment process of many chunks may take a long time. A significant portion of this time is
spent for matching of detected features across the photos. Image pair preselection option can speed
up this process by selection of a subset of image pairs to be matched.

Constrain features by mask (Point based alignment only)
When this option is enabled, features detected in the masked image regions are discarded. For
additional information on the usage of masks refer to the Using masks section.
Note

• Chunk alignment can be performed only for chunks containing aligned photos.

• There is no need to perform chunk alignment for georeferenced chunks, as they are already in
the same coordinate frame.
Merging chunks

After alignment is complete the separate chunks can be merged into a single chunk.

To merge chunks

\1. Select Merge Chunks command from the Workflow menu.

\2. In the Merge Chunks dialog box select chunks to be merged and the desired merging options. Click
OK button when done.

\3. Metashape will merge the separate chunks into one. The merged chunk will be displayed in the project
content list on Workspace pane.

The following parameters control the chunks merging procedure and can be modified in the Merge Chunks
dialog box:

Merge tie points
Defines if the projections of the tie points for corresponding features should be merged. Since tie
points merging operation assumes re-matching of the features from different chunks, the operation
may be time consuming. Thus it is recommended to disable tie points merging, unless it is required
by the task specifics.

Merge dense clouds
Defines if dense clouds from the selected chunks are combined.

Merge models
Defines if models from the selected chunks are combined.

Merge markers
Defines if markers from the selected chunks are merged (only markers with the same labels would
be merged).

87

<!-- p. 94 -->

Automation

Chunks merging result (i.e. photos, point clouds and geometry) will be stored in the new chunk and it may
be treated as an ordinary chunk (e.g. the model can be textured and/or exported).
Note

• Dense cloud and model merging operations will be applied only to the active items. Disabled
(inactive) items will not be transfered to the merged chunk.
Batch processing

Metashape allows to perform general workflow operations with multiple chunks automatically. It is useful
when dealing with a large number of chunks to be processed.

Batch processing can be applied to all chunks in the Workspace, to unprocessed chunks only, or to the
chunks selected by the user. Each operation chosen in the Batch processing dialog will be applied to every
selected chunk before processing will move on to the next step.

Align Photos Align/Merge Chunks Save/Load Project
Optimize Alignment Decimate Mesh Export/Import Cameras
Build Dense Cloud Smooth Model Export Points
Build Mesh Close Holes Export Model
Build Texture Calibrate Colors Export Texture
Build Tiled Model Remove Lighting Export Tiled Model
Build DEM Classify Points / Ground Points Export DEM
Build Orthomosaic Import Shapes Export Orthomosaic
Refine Mesh Import Masks Reset Region
Detect Markers Detect Fiducials Run Script
Generate Report Undistort Photos

To start batch processing

\1. Select Batch Process... command from the Workflow menu.

\2. Click Add to add the desired processing stages.

\3. In the Add Job dialog select the kind of operation to be performed, the list of chunks it should be
applied to, and desired processing parameters. Click OK button when done.

\4. Repeat the previous steps to add other processing steps as required.

\5. Arrange jobs by clicking Up and Down arrows at the right of the Batch Process... dialog box.

\6. Click OK button to start processing.

\7. The progress dialog box will appear displaying the list and status of batch jobs and current operation
progress. To cancel processing click the Cancel button.

When the batch process includes import/export features that are applied to multiple chunks it is reasonable
to use the following templates in the Path field of the import/export jobs:

• {filename} - filename (without extension),

88

<!-- p. 95 -->

Automation

• {fileext} - file extension,

• {camera} - camera label,

• {frame} - frame index,

• {chunklabel} - chunk label,

• {imagefolder} - folder containing images of an active chunk,

• {projectfolder} - path to the folder containing current project,

• {projectname} - current project filename,

• {projectpath} - absolute path to the current project.

The list of tasks for batch processing can be exported to XML structured file using Save button in the
Batch processing dialog and imported in a different project using Open button.
4D processing
Overview

Metashape supports reconstruction of dynamic scenes captured by a set of statically mounted synchronized
cameras. For this purpose multiple image frames captured at different time moments can be loaded for
each camera location, forming a multiframe chunk. In fact normal chunks capturing a static scene are
multiframe chunks with only a single frame loaded. Navigation through the frame sequence is performed
using Timeline pane.

Although a separate static chunk can be used to process photos for each time moment, aggregate multiframe
chunks implementation has several advantages:

• Coordinate systems for individual frames are guaranteed to match. There is no need to align chunks to
each other after processing.

• Each processing step can be applied to the entire sequence, with a user selectable frame range. There is
no need to use batch processing, which simplifies the workflow.

• Accuracy of photo alignment is better due to the joint processing of photos from the entire sequence.

• Markers can be tracked automatically through the sequence.

• Intuitive interface makes navigation through the sequence pretty simple and fast.

Multiframe chunks can be also efficient (with some limitations) for processing of disordered photo sets of
the same object or even different objects, provided that cameras remain static throughout the sequence.
Managing multiframe chunks

Multiframe layout is formed at the moment of adding photos to the chunk. It will reflect the data layout
used to store image files. Therefore it is necessary to organize files on the disk appropriately in advance.
The following data layouts can be used with Metashape:

a. All frames from corresponding camera are contained in a separate subfolder. The number of subfolders
is equal to the number of cameras.

89

<!-- p. 96 -->

Automation

b. Corresponding frames from all cameras are contained in a separate subfolder. The number of subfolders
is equal to the number of frames.

c. All frames from corresponding camera are contained in a separate multilayer image. The number of
multilayer images is equal to the number of cameras.

d. Corresponding frames from all cameras are contained in a separate multilayer image. The number of
multilayer images is equal to the number of frames.

Once the data is properly organized, it can be loaded into Metashape to form a multiframe chunk. The
exact procedure will depend on whether the multifolder layout (variants a and b) or multilayer (variants
c and d) layout is used.

To create a chunk from multifolder layout

\1. Select Add Folder... command from the Workflow menu.

\2. In the Add Folder dialog box browse to the parent folder containing subfolders with images. Then
click Select Folder button.

\3. In the Add Photos dialog select the suitable data layout. For layout a) above select "Create multiframe
cameras from folders as cameras". For layout b) select "Create multiframe cameras from folders as
frames".

\4. Created multiframe chunk will appear on the Workspace pane.

To create a chunk from multilayer images

\1. Select Add Photos... command from the Workflow menu or click Add Photos toolbar button.

\2. In the Add Photos dialog box browse to the folder containing multilayer images and select files to
be processed. Then click Open button.

\3. In the Add Photos dialog select the suitable data layout. For layout c) above select "Create multiframe
cameras from files as cameras". For layout d) select "Create multiframe cameras from files as frames".

\4. Created multiframe chunk will appear on the Workspace pane.

It is recommended to inspect the loaded frame sequence for errors. This can be done by scrolling the frame
selector in the Timeline pane and inspecting thumbnails in the Photos pane during scrolling.

After multiframe chunk is created, it can be processed in the same way as normal chunks. For multiframe
chunks additional processing parameters allowing to select the range of frames to be processed will be
provided where appropriate.
Tracking markers

Metashape allows to automatically track marker projections through the frames sequence, provided that
object position doesn't change significantly between frames. This greatly simplifies the task of labeling of
a moving point if the number of frames is large.

To track markers through the frame sequence

\1. Scroll frame selector in the Timeline pane to the 1st frame. Add markers for the 1st frame as described
in the Setting coordinate system section.

90

<!-- p. 97 -->

Automation

\2. Select Track Markers... command from the Tools menu.

\3. Adjust the starting and ending frame indices if necessary. Default values correspond to tracking from
the current frame to the end of sequence. Click OK button to start tracking.

\4. Check tracked marker locations. Automatically tracked markers will be indicated with icons. In
case of a placement error at some frame, adjust the wrong marker location within the frame where
the failure occurred. Once the marker location is refined by user, the marker icon will change to

\5. Restart tracking from that frame using Track Markers... command again.
Note

• If the ending frame index is smaller than the starting index, tracking will be performed in the
backwards direction.

• Automatic marker tracking is likely to fail in case when structured light is used to add texture
details to the object surface, as the light pattern will not be static with respect to the moving
object surface.
Python scripting

Metashape supports Python API, using Python 3.5 as a scripting engine.

Python commands and scripts can be executed in Metashape through one of the following options:

• Metashape Console pane can serve as Python rich console;

• Click Run Script button on Console pane toolbar or use Run Script... command from the Tools
menu to run a Python script.

• From command-line using -r argument.

On Windows:
metashape.exe -r \<scriptname.py>

On Linux:
./metashape.sh -r \<scriptname.py>

On Mac OS X:
./MetashapePro.app/Contents/MacOS/MetashapePro -r \<scriptname.py>

• From autorun folder.
for Windows: C:/Users/\<user>/AppData/Local/Agisoft/Metashape Pro/scripts/

for Linux: /home/\<user>/.local/share/Agisoft/Metashape Pro/scripts/

for Mac OS X: /Users/\<user>/Library/Application Support/Agisoft/Metashape Pro/scripts/

on any OS (for all users): \<installation folder>/scripts/

For details on Metashape functionality accessible through Python scripts please refer to Python API
Reference document available on Agisoft official website (http://www.agisoft.com/downloads/user-
manuals/).

91

<!-- p. 98 -->

Automation

The collection of the sample Python scripts is available on Agisoft GitHub repository: https://github.com/
agisoft-llc/photoscan-scripts.

92

<!-- p. 99 -->

Chapter 8. Distributed processing
Local network processing
Overview

Agisoft Metashape can be configured to run on a computer cluster where processing is distributed on
several computer nodes connected to a local network. In such configuration multiple Metashape instances
running on different processing nodes can work on the same task in parallel, effectively reducing the total
processing time needed.

By default processing is divided between the nodes on a chunk by chunk, frame by frame basis (with the
exception of camera alignment and optimization, where each chunk is processed as a whole on a single
node). In addition a more fine grained distribution can be enabled for image matching and alignment, as
well as generation of dense clouds, tiled models, DEMs and orthomosaics, in which case processing of
individual chunks/frames is further subdivided between several processing nodes.

Communication between processing nodes, server and clients is performed using TCP connections. In
addition, shared network storage accessible for all processing nodes and clients is used for storing the
source data and intermediate processing results.
Cluster components

Server

The server node coordinates operation of all processing nodes, maintaining a task queue for all projects
scheduled for processing. A separate interface is provided for clients, which can connect to the server to
start new processing tasks or monitor progress of existing ones.

The server itself doesn't perform any processing and can easily run on slow hardware. The server
component is critical for operation of the cluster, and is not fault tolerant. Measures should be taken to
ensure continuous operation of the server node.

93

<!-- p. 100 -->

Distributed processing

The server node accepts TCP connections from processing nodes and clients on 2 separate interfaces,
which can be attached to different physical network interfaces if necessary. The server node doesn't initiate
any TCP connections itself.
Processing nodes

Processing nodes perform actual calculations, and thus need to be run on fast hardware. Each processing
node connects to the server on startup and waits for a task to be assigned. Once the task is available, the
node starts processing, informing the server about the progress. When processing is finished, the results
are stored on shared network storage, and the server is informed about completion. Then a node switches
to the next task when it becomes available.

Processing nodes can be added or removed from the cluster as needed. Abnormal shutdown of processing
node doesn't cause cluster failure in most cases. Nevertheless, it is highly recommended to stop particular
nodes using Agisoft Network Monitor before disconnecting them from the cluster.
Clients

Clients can connect to the server node to control cluster operation or to monitor its status. New tasks can be
submitted for processing using Agisoft Metashape software configured as a network client, while cluster
monitoring is performed using Agisoft Network Monitor. Multiple clients can be connected to the server
node simultaneously.
Cluster setup

Before proceeding to the following steps please make sure that shared network storage is accessible from
all processing and client nodes using the same absolute path. It should be either mounted to the same folder
on all nodes (Linux), or should have the same UNC network path (Windows). In case such configuration
is not possible (for example in mixed Windows/Linux cluster), a path prefix can be specified on each node
to compensate for the differences.
Starting server

It is recommended to configure server with a static IP address, not dynamically assigned one. This IP
address will be needed for each processing node and client.

The server process can be started by executing Metashape with the following command line arguments:
metashape --server --control \<ip>[:port] --dispatch \<ip>[:port]
\--server parameter specifies that Metashape should be started in a server mode.
\--control parameter specifies the network interface to be used for communication with clients. In case port
value is omitted, the default port 5840 is used.

\--dispatch parameter specifies the network interface to be used for communication with processing nodes.
In case port value is omitted, the default port 5841 is used.

Example:
metashape --server --control 10.0.1.1 --dispatch 10.0.1.1

In this case Metashape will use the same interface for both clients and processing nodes with default port
values.
Starting network nodes

The processing node can be started by executing Metashape with the following command line arguments:

94

<!-- p. 101 -->

Distributed processing

metashape --node --dispatch \<ip>[:port] [--root prefix]
\--node parameter specifies that Metashape should be started as a processing node.
\--dispatch parameter specifies IP of the server to connect. In case port value is omitted, the default port
5841 is used.

\--root parameter can be used to specify network storage mount point or prefix path in case it is not the
same across network.

\--priority \<priority> parameter can be used to specify the priority of the node. Higher number means
higher priority.

\--capability {cpu, gpu, any} parameter can be used to specify whether the node should work on CPU-
only tasks, GPU-supported tasks only or will receive any tasks.

\--gpu_mask \<mask> parameter set GPU device mask for GPU-supported tasks.
\--cpu_enable {0,1} parameter can be used to enable or disable CPU during the GPU-supported tasks.
\--absolute_paths {0,1} parameter can be used to set the absolute paths option.
\--timestamp parameter can be used to append timestamps to the output messages.
\--auto-submit parameter can be used to enable automatic crash report submission.
\--email \<address> parameter specifies email address to be included in the crash reports.
\--comment \<text> parameter specifies optional comment to be included in the crash reports.
\--service {install,remove,start,stop} parameter can be used to configure Windows service.
\--service-name \<name> optional parameter for Windows service name.

Example:
metashape --node --dispatch 10.0.1.1 --root /processing

This command will start processing node using 10.0.1.1 as a server IP with default port 5841.
Checking cluster status

Start Agisoft Network Monitor application. In the host name field enter server IP used for client
connections (10.0.1.1 in our example). Modify port values in case non-default port was specified. Click
Connect button when done.

A list of available network nodes currently connected to the server will be displayed in the bottom part of
the window. Please make sure that all started processing nodes are listed. Agisoft Network Monitor for
each node allows to modify the node priority, capability, CPU enable flag, GPU mask and to pause/resume
the node. The priority for the tasks can be also altered and tasks themselves can be paused, resumed and
aborted via Agisoft Network Monitor.

The top part lists tasks currently being processed (finished tasks are removed from the list as soon as they
are completed). The task list will be empty if no processing was started yet.
Starting network processing

\1. Configure Agisoft Metashape for network processing.

Start Agisoft Metashape on any computer connected to the cluster network.

95

<!-- p. 102 -->

Distributed processing

Open Preferences dialog using Preferences... command from the Tools menu. On the Network tab
make sure Enable network processing option is turned on, and specify the server IP used for client
connection in the Host name field. In case non-default port was configured on a server, modify the
port value accordingly.

In case you are going to process a few single-frame chunks with large number of photos, we
recommend to enable fine-level task subdivision in the Advanced tab of Preferences dialog. The
subdivision will be automatically applied when possible to all the supported operations (Match
Photos, Align Cameras, Build Depth Maps, Build Dense Cloud, Build Tiled Model, Build DEM,
Build Orthomosaic, Classify Points). In case you are going to process a large number of small chunks,
or chunks with large number of frames, fine-level task subdivision can be left in disabled state,
therefore each chunk or frame will be processed on the single chunk only without any further internal
distribution applied.

Press OK button when done.

\2. Prepare project for network processing.

Open the project file to be processed. Make sure that the project is saved in Metashape Project (*.psx)
format. Processing of projects in Metashape Archive (*.psz) format is not supported in network mode.

Important! Please make sure that source images are located on shared network storage and not on a
local hard drive. Otherwise processing nodes will be unable to load them.

\3. Start processing.

Start processing using corresponding command from the Workflow menu, or using Batch Process
command to execute a command sequence. A network progress dialog should appear displaying
current progress.

\4. Wait for processing to complete.

You can disconnect from the server at any time using Disconnect button in the Network Progress
dialog in case you need to work on other projects. Processing will continue in the background.

To see processing status after you have disconnected from the server simply open corresponding .psx
project on the network storage. Alternatively you can use Agisoft Network Monitor to see processing
status for all projects being processed.

\5. Inspect processing results.

After processing is finished, click Close button to close Network Progress dialog. The project with
processing results will be displayed in Metashape window.
Cluster administration
Adding processing nodes

New processing nodes can be added by starting Agisoft Metashape on additional computers in the network
node mode, as outlined in the Starting network nodes section above.
Removing processing nodes

Aborting or disconnecting processing node during cluster operation is not absolutely safe, and can lead to
project corruption if performed during final project update at the end of processing. Although the chances

96

<!-- p. 103 -->

Distributed processing

of this situation are relatively low, we strongly recommend against such approach. To safely disconnect
processing node from the cluster you need to stop processing on this node using Agisoft Network Monitor
first.

\1. Start Agisoft Network Monitor. Make sure the server IP is properly configured in the host name field
and click Connect button.

\2. In the bottom list of network nodes identify the node to be removed. From the node menu select
Pause command to stop the node after it finishes current job, or Stop command to abort processing
immediately.

\3. Wait until the Batch # and Progress items for a selected node become empty. This indicates that the
node has finished processing. The status of the node should be Paused.

\4. Now you can safely disconnect the node by aborting Metashape process.
Cloud processing
Overview

Agisoft Metashape presents cloud processing option integrated in the application user interface for those
who do not want to invest in the hardware infrastructure, but are interested in the high quality outputs of
considerably big datasets.
Starting cloud processing

Cloud processing option is only accessible for those Metashape license owners who have registered on
Agisoft Cloud page: https://account.agisoft.com/

After completing the registration and choosing the appropriate payment plan the account information
should be input to the Network tab in Preferences dialog. The checkbox for "Enable cloud processing"
option should be turned on, while "Enable network processing" option should be turned off.

When the cloud processing is enabled and the selected plan allows to process the new projects, each
time the processing operation is run the confirmation dialog will appear, asking if the operation should
be executed locally or in the cloud. If the cloud processing option is selected, the project data and
related source imagery will be uploaded/synchronized with the data in your personal account. Do not
disable Internet connection or shut down the computer when the uploading process is in progress, you
can disconnect, however, once the processing has been started according to the indication in the program
interface and in the web-interface of your personal account.

Next time you open the local project after the processing operation in the cloud is finished the updated
project files will be downloaded from the cloud and synchronized with your local copy.
Note

• Cloud processing is supported only for projects saved in Metashape Project (*.psx) format.

• All the files related to the certain project can be removed to free the available disk space from
your personal account in Agisoft Cloud web-interface.

• Some operations do not support processing in the cloud (for example, any export operations). If
the Batch Process task sent to the cloud include such operations, the warning message will be
displayed and the batch processing task list can be adjusted before sending it to the cloud.

97

<!-- p. 104 -->

Appendix A. Graphical user interface
Application window
General view

General view of application window.
Model view

Model view tab is used for displaying 3D data as well as for mesh and point cloud editing. The view of
the model depends on the current processing stage and is also controlled by mode selection buttons on
the Metashape toolbar.

98

<!-- p. 105 -->

Graphical user interface

Model can be shown as a dense cloud, with class indication or without, or as a mesh in shaded, solid,
wireframe or textured mode. Along with the model the results of photo alignment can be displayed. These
include sparse point cloud and camera positions visualized data. Additionally tiled textured model can be
displayed and navigated in the model view.

Metashape supports the following tools for navigation in the 3D view:

Tool Keyboard modifier
Rotation Tool Default
Pan Tool Ctrl key pressed
Zooming Tool Shift key pressed

All navigation tools are accessible in the navigation mode only. To enter the navigation mode click the

Navigation toolbar button.

Metashape offers two different navigation modes: Object navigation and Terrain navigation. Switching
between the navigation modes can be performed from the Navigation Mode submenu of the View menu.
Object navigation mode allows for 3-axis rotation control, while Terrain navigation mode restricts control
to 2-axis rotation only, z-axis being kept vertical all the time.

In Object navigation mode the rotation with mouse can be performed while left mouse button is pressed,
whereas holding right mouse button allows for model tilt. In Terrain navigation mode mouse buttons
functionality is inverted and left button is responsible for tilt, whereas right button for rotation.
Note

• Zooming into the model can be also controlled by the mouse wheel.
Ortho view

Ortho view is used for the display of 2D processing results data: digital elevation model, full resolution
orthomosaic, NDVI color-coded values, as well as shapes and contour lines data. Switching between DEM
and orthomosaic can be performed using the corresponding button on the toolbar or by double-clicking on
the respective icon on the Workspace pane, providing that both products have been generated.

Orthomosaic can be displayed in the original colors or in colors according to the palette set for vegetation
index values visualization.

Additional instruments allow to draw points, polylines and polygons on the orthomosaic and/or digital
elevation model to perform point, linear, profile and volume measurements. Also polygonal shapes are
allowed to be set up as inner or outer boundaries, that will be used for the definition of the area to be
exported. Using polygonal shapes allows to create custom seamlines on the orthomosaic, which can be
useful for some projects enabling to eliminate blending artefacts.

Switching to Ortho view mode changes the contents of the Toolbar, presenting related instruments and
hiding irrelevant buttons.
Photo view

Photo view tab is used for displaying individual photos as well as semi-transparent depth maps, markers,
shapes and masks on them.

99

<!-- p. 106 -->

Graphical user interface

In the Photo view tab it is allowed to create markers, refine their projections, draw shapes and adjust
positions of shape vertices and to draw masks on the photos. Additionally in Photo view tab it is possible
to display the residuals for the tie points and markers providing that the corresponding camera is aligned

Photo view is visible only if any photo is opened. To open a photo double-click on the label of the
corresponding camera on the Workspace, Reference or Photos pane.

For multicamera systems which have several sensors assigned to the same layer Photo view tab will be
vertically split into corresponding number of sub-frames.

Switching to Photo view mode changes the contents of the Toolbar, presenting related instruments and
hiding irrelevant buttons.
Workspace pane

On the Workspace pane all elements comprising the current project are displayed. These elements can
include:

• List of chunks in the project

• List of cameras and camera groups in each chunk

• List of markers and marker groups in each chunk

• List of scale bars and scale bar groups in each chunk

• List of shape layers in each chunk

• Tie points in each chunk

• Depth maps in each chunk

• Dense point clouds in each chunk

• 3D models in each chunk

• Tiled models in each chunk

• Digital elevation models in each chunk

• Orthomosaics in each chunk

Buttons located on the Workspace pane toolbar allow to:

• Add chunk

• Add photos

• Add marker

• Create scale bar

• Enable or disable certain cameras or chunks for processing at further stages.

• Remove items

100

<!-- p. 107 -->

Graphical user interface

Each element in the list is linked with the context menu providing quick access to some common
operations.
Photos pane

Photos pane displays the list of photos / masks / depth maps in the active chunk in the form of thumbnails.

Buttons located on the Photos pane toolbar allow to:

• Enable / disable certain cameras

• Remove cameras

• Rotate selected photos clockwise / counterclockwise (for display purposes only)

• Reset current photo filtering option

• Switch between images / masks / depth maps thumbnails

• Increase / decrease icons' size or display detailed information on photos including EXIF data
Console pane

Console pane is used for:

• Displaying auxiliary information

• Displaying error messages

• Python commands input

Buttons located on the pane toolbar allow:

• Save log (in HTML, XHTML or Plain Text format)

• Clear log

• Execute Python script
Reference pane

Reference pane is designed for:

• Displaying and editing camera and / or marker coordinates

• Displaying and editing scale bars lengths

• Displaying and editing camera orientation angles

• Displaying estimation errors

• Displaying and editing accuracy parameters for camera/marker coordinates, camera angles and scale
bar lengths

101

<!-- p. 108 -->

Graphical user interface

Buttons located on the pane toolbar allow:

• Import / export reference coordinates

• Convert reference coordinates from one system to the other

• Optimize camera alignment and update data

• Switch between source coordinates, estimated coordinates and errors views

• Specify the coordinate system and measurement accuracy to be assumed through Settings dialog
Jobs pane

Jobs pane is designed for:

• Monitoring the processing status for active and background projects

• Organizing the background processing queue

• Switching between the projects

Buttons located on the pane toolbar allow:

• Start / pause / cancel the selected tasks

• Change the order of the tasks in the processing queue

• Clear the processing tasks history
Timeline pane

Timeline pane is designed for:

• Working with multi-frame chunks

Buttons located on the pane toolbar allow:

• Add / remove frames from chunk

• Play / stop frame sequence

• Adjust frame rate through Settings dialog
Animation pane

Animation pane is designed for:

• Loading the camera track

• Start / stop the camera movement according to the track

• Render the frame sequence to the form of the video file

102

<!-- p. 109 -->

Graphical user interface

Buttons located on the pane toolbar allow:

• Start / stop the animation according to the camera track

• Render the animation and save to the external video file

• Create track, load track and adjust track properties through Settings dialog
Note

• To open any pane select a corresponding command from the View menu.
Menu commands

File Menu
Creates an empty Metashape project. New
Opens Metashape project file. Open...
Appends existing Metashape project file to the Append... current one.
Saves Metashape project file. Save
Saves Metashape project file with a new name. Save As...
Saves sparse / dense point cloud. Export Points...
Saves 3D model. Export Model...
Saves a tiled model as hierarchical tiles. Export Tiled Model...
Exports generated orthomosaic. Export Orthomosaic...
Exports generated digital elevation model. Export DEM...
Generates Agisoft Metashape processing report in Generate Report... PDF format.
Exports camera positions, orientation data and tie Export Cameras... points measurements.
Exports marker projections / estimated marker Export Markers... locations.
Exports masks. Export Masks...
Exports shapes from the selected layers. Export Shapes...
Exports model texture. Export Texture...
Exports spherical panorama for camera stations. Export Panorama...
Exports separate orthorectified images. Export Orthophotos...
Removes nonlinear distortions by warping source Undistort Photos... photos and saving the result as files.

103

<!-- p. 110 -->

Graphical user interface

File Menu
Lenticular images generation Render Photos...
Imports camera positions and orientation data. Import Cameras...
Imports marker projections. Import Markers...
Imports masks or creates mask from model or Import Masks... background.
Imports shapes to be used for editing or Import Shapes... measurements.
Imports points in a form of the dense point cloud. Import Points...
Imports polygonal mesh model. Import Model...
Imports texture and applies it to the current model. Import Texture...
Imports digital elevation model. Import DEM...
Imports video in a form of frame sequence and Import Video... saves the extracted frames as images.
Uploads generated products (points, textured mesh Upload Data... models , tiled models, orthomosaics or digital
elevation models) to one of the supported web-
sites.
Closes the application window. Exit

Edit Menu
Undo the last editing operation. Undo
Redo the previously undone editing operation. Redo
Adds current selection to the mask. Add selection
Subtracts current selection from the mask. Subtract selection
Inverts current selection for the photo. Invert Selection
Inverts current selection of faces / points / cameras. Invert Selection
Grows current selection of mesh faces. Grow Selection
Shrinks current selection of mesh faces. Shrink Selection
Removes selected faces from the mesh or selected Delete Selection points from the point cloud.
Crops selected faces / points. Crop Selection
Inverts mask for the current photo. Invert Mask
Resets mask for the current photo. Reset mask
Rotates the photo clockwise. Rotate right

104

<!-- p. 111 -->

Graphical user interface

Edit Menu
Rotates the photo counterclockwise. Rotate left

View Menu
Increases magnification in the active view mode. Zoom In
Decreases magnification in the active view mode. Zoom Out
Resets the viewport to display the complete model Reset View or photo.
Saves screenshot of current view of the project Capture view (Model/Ortho/Photo)
Shows or hides Workspace pane. Workspace
Shows or hides Timeline pane. Timeline
Shows or hides Animation pane. Animation
Shows or hides Reference pane. Reference
Shows or hides Photos pane. Photos
Shows or hides Console pane. Console
Shows or hides Jobs pane. Jobs
Shows or hides Toolbar. Toolbar
Switches to / from Full Screen mode. Full Screen

Workflow Menu
Loads additional photos to be processed by Add Photos... Metashape.
Loads additional photos from folders to be Add Folder... processed by Metashape.
Estimates camera positions and sparse point cloud. Align Photos...
Generates dense point cloud. Build Dense Cloud...
Generates polygonal mesh model. Build Mesh...
Generates texture for the mesh model. Build Texture...
Generates tiled textured model. Build Tiled Model...
Generates digital elevation model. Build DEM...
Generates orthomosaic. Build Orthomosaic...
Aligns multiple chunks. Align Chunks...
Merges multiple chunks into the single chunk. Merge Chunks...

105

<!-- p. 112 -->

Graphical user interface

Workflow Menu
Opens Batch Process dialog box. Batch Process...

Model Menu
Switches to navigation mode. Navigation
Rectangle selection tool for the elements of the Rectangle Selection Model view.
Circle selection tool for the elements of the Model Circle Selection view.
Free-form selection tool for the elements of the Free-form Selection Model view.
Selects faces / points based on the specified Gradual selection... criterion.
Switches to the 3D point drawing tool. Draw Point
Switches to the 3D polyline drawing tool. Draw Polyline
Switches to the 3D polygon drawing tool. Draw Polygon
Switches to 3D coordinate and linear distance Ruler measurement tool.
Switches to object movement tool. Move Object
Switches to object rotation tool. Rotate Object
Switches to object scaling tool. Scale Object
Resets the transformations applied to the object. Reset Transform
Switches to volume movement tool. Move region
Switches to volume rotation tool. Rotate Region
Switches to volume resize tool. Resize region
Resets the transformations applied to the volume to Reset Region default.
Displays or hides camera positions estimated Show Cameras during image alignment.
Displays or hides image thumbnails in the camera Show Thumbnails placeholders.
Displays or hides shapes. Show Shapes
Displays or hides marker positions. Show Markers
Displays or hides item labels. Show Labels
Switches stereographic image overlay mode on/ Show Images off.

106

<!-- p. 113 -->

Graphical user interface

Model Menu
Locks current image in stereographic image Lock Image overlay mode.
Displays or hides region selector. Show Region
Displays or hides the trackball. Show Trackball
Displays or hides the auxiliary on-screen Show Info information.
Displays or hides the grid. Show Grid
Displays all elements at the same time. Show All
Hides all elements. Hide All
Displays sparse point cloud reconstructed during Point Cloud photo alignment.
Displays sparse point cloud colored by variance. Point Cloud Variance
Displays dense point cloud. Dense Cloud
Displays dense point cloud colored by point Dense Cloud Classes classes.
Displays 3D model in the shaded mode. Shaded
Displays 3D model in the solid mode. Solid
Displays 3D model in the wireframe mode. Wireframe
Displays 3D model in the textured mode. Textured
Displays tiled model with applied texture. Tiled Model Textured
Displays tiled model without texture in the solid Tiled Model Solid model.
Displays tiled model in the wireframe mode. Tiled Model Wireframe
Switches visualization view between Perspective Perspective/Orthographic and Orthographic.
Enable/disable stereo view mode according to the Stereo Mode parameters specified in Preferences dialog.
Switches viewport to one of the predefined views. Predefined views
Switches between Object / Terrain navigation Navigation Mode modes for the Model view window. Object
navigation mode allows for 3-axis rotation control,
while Terrain navigation mode restricts control to
2-axis rotation only, z-axis being kept vertical all
the time.

Photo Menu
Switches to navigation mode. Navigation

107

<!-- p. 114 -->

Graphical user interface

Photo Menu
Rectangle selection tool. Rectangle Selection
Intelligent Scissors selection tool. Intelligent Scissors
Intelligent Paint selection tool. Intelligent Paint
Magic Wand selection tool. Magic Wand
Switches to the 3D point drawing tool. Draw Point
Switches to the 3D polyline drawing tool. Draw Polyline
Switches to the 3D polygon drawing tool. Draw Polygon
Switches to 3D coordinate and linear distance Ruler measurement tool.
Opens next photo from the list in the Photos pane. Open Next Photo
Opens previous photo from the list in the Photos Open Previous Photo pane.
Zooms to the next marker projection on the opened Go To Next Marker photo.
Zooms to the previous marker projection on the Go To Previous Marker opened photo.
Turns mask shading on or off. Show Masks
Turns depth maps overlay on or off. Show Depth Maps
Displays or hides shapes. Show Shapes
Displays or hides markers. Show Markers
Displays or hides item labels. Show Labels
Displays or hides tie point projections used for the Show Points camera alignment.
Displays all elements at the same time. Show All
Hides all elements. Hide All

Ortho Menu
Switches to navigation mode. Navigation
Rectangle selection tool for the elements of the Rectangle Selection Ortho view.
Circle selection tool for the elements of the Ortho Circle Selection view.
Free-form selection tool for the elements of the Free-form Selection Ortho view.
Switches to the 2D point drawing tool. Draw Point

108

<!-- p. 115 -->

Graphical user interface

Ortho Menu
Switches to the 2D polyline drawing tool. Draw Polyline
Switches to the 2D polygon drawing tool. Draw Polygon
Switches to the patch drawing tool. Draw Patch
Switches to coordinate and linear distance Ruler measurement tool.
Displays or hides orthomosaic seamlines. Show Seamlines
Displays or hides shapes. Show Shapes
Displays or hides markers. Show Markers
Displays or hides item labels. Show Labels
Displays all elements at the same time. Show All
Hides all elements. Hide All
Switches to the digital elevation model display DEM mode.
Switches to the orthomosaic display mode. Orthomosaic
Enables or disables hillshading mode of digital Hillshading elevation mode visualization.

Tools Menu
Creates markers from coded targets on photos. Detect Markers...
Detects fiducial marks on the images. Detect Fiducials...
Tracks marker locations across the frame Track Markers... sequence.
Generates printable PDF file with coded targets. Print Markers...
Enables or disables the mode where every newly Attach Markers drawn shape has markers attached to its vertices.
Enables or disables automatic marker projection Refine Markers refinement based on the image content.
Builds sparse point cloud based on the estimated Build Point Cloud... camera parameters available.
Thins sparse point cloud by reducing the number Thin Point Cloud... of projections on the individual photos to the given
limit.
Displays View Matches dialog for visual View Matches... representation of the common tie points between
the image pairs.
Applies colors to the dense cloud points basing on Colorize Dense Cloud... source images or orthomosaic.

109

<!-- p. 116 -->

Graphical user interface

Tools Menu
Inverts normals for the selected points of the dense Invert Point Normals... cloud.
Classifies dense point cloud based on the user Classify Ground Points... defined settings.
Automatically classifies dense point cloud to the Classify Points... supported classes.
Assigns class to the selected points. Assign Class...
Resets assigned classes for the selected point Reset Classification... classes.
Selects dense cloud points according to the masks Select Points by Masks... of the selected images.
Selects dense cloud points according to the color Select Points by Color... and tolerance.
Selects dense cloud points according to the Select Points by Shapes... selected shapes.
Filters the points in the dense cloud according to Filter By Class the selected classes.
Filters the points in the dense cloud according to Filter By Selection the selected points.
Resets all applied dense cloud filters. Reset Filter
Permanently removes all deleted points from the Compact Dense Cloud... dense cloud.
Restores all deleted points of the dense cloud that Restore Dense Cloud... were once marked as removed.
Updates statistics of the dense cloud, including Update Dense Cloud... point numbers and assigned classes.
Starts photoconsistent mesh refinement operation. Refine Mesh...
Decimates mesh to the target face count. Decimate Mesh...
Smoothes mesh. Smooth Mesh...
Closes holes on the model surface. Close Holes...
Starts the delighting operation for mesh texture. Remove Lighting...
Collects and displays mesh statistics. View Mesh Statistics...
Displays mesh UV mapping. View Mesh UVs...
Displays surface area and volume of the polygonal Measure Area and Volume... model.
Filters the faces of the polygonal model according Filter By Selection to the selected points.
Resets all applied mesh filters. Reset Filter

110

<!-- p. 117 -->

Graphical user interface

Tools Menu
Displays digital elevation model transformation Transform DEM... dialog.
Applies all the manual edits to the orthomosaic. Update Orthomosaic
Resets all applied edits to default orthomosaic Reset Orthomosaic stitching.
Removes individually orthorectified images from Remove Orthophotos the project contents.
Creates the shape layer with the polygonal shapes Generate Seamlines as copies of the orthmosaic patches.
Displays lens calibration dialog. Calibrate Lens...
Displays the calibration board on screen. Show Chessboard...
Displays camera calibration dialog box. Camera Calibration...
Starts the optimization of exterior and interior Optimize Cameras... parameters of the aligned cameras.
Displays reflectance calibration dialog for precise Calibrate Reflectance... radiometric calibration of multispectral data based
on reflectance panel and sun sensor data.
Displays the color correction dialog for the Calibrate Colors... brightness and white balance compensation of the
images.
Displays the primary channel selection dialog. Set Primary Channel...
Adjusts image brightness and contrast for more Set Brightness... convenient display.
Displays Raster Calculator dialog for NDVI and Set Raster Transform... other vegetation indices calculation.
Generates contours based on DEM according Generate Contours... to the elevation levels or based on Orthomosaic
according to the vegetation index values.
Reduces the number of enabled cameras in the Optimize Coverage... active project to optimize the coverage in case of
excessive overlap.
Displays the survey statistics dialog in a form of Survey Statistics... interactive report.
Displays Run Script dialog box for Python script Run Script... execution.
Displays preferences dialog box. Preferences...

Help Menu
Displays help contents. Contents
Checks if Metashape update is available for Check for Updates... download.

111

<!-- p. 118 -->

Graphical user interface

Help Menu
Displays the activation dialog for activation / Activate Product... deactivation of the product using the activation key
or borrowing / returning borrowed floating license
to the license server .
Displays program information, version number and About Metashape... copyright.
Toolbar buttons

General commands
Creates a new Metashape project file. New
Opens a Metashape project file. Open
Saves a Metashape project file. Save

3D view commands
Undo the last editing operation. Undo
Redo the previously undone editing operation. Redo
Navigation tool. Navigation
Rectangle selection tool. Rectangle Selection
Circle selection tool. Circle Selection
Free-form selection tool. Free-Form Selection
Resets current selection. Reset Selection
Volume translation tool. Move region
Volume resize tool. Resize region
Volume rotation tool. Rotate Region
Resets region according to the actual point cloud. Reset Region
Model translation tool. Move Object
Model rotation tool. Rotate Object
Model resize tool. Scale Object
Resets all transformations applied to the model. Reset Transform
Switches to the 3D point drawing tool. Draw Point
Switches to the 3D polyline drawing tool. Draw Polyline

112

<!-- p. 119 -->

Graphical user interface

3D view commands
Switches to the 3D polygon drawing tool. Draw Polygon
3D coordinate and linear distance measurement Ruler tool.
Removes selected faces / points. Delete Selection
Crops selected faces / points. Crop Selection

3D view settings
Increases magnification. Zoom In
Decreases magnification. Zoom Out
Resets model view. Reset View
Displays sparse point cloud reconstructed during Point Cloud image alignment.
Displays sparse point cloud colored by variance. Point Cloud Variance
Displays dense point cloud model. Dense Cloud
Displays dense point cloud colored by point Dense Cloud Classes classes.
Displays 3D model in the shaded mode. Shaded
Displays 3D model in the solid mode. Solid
Displays 3D model in the wireframe mode. Wireframe
Displays 3D model in the textured mode. Textured
Displays tiled model with the applied texture. Tiled Model Textured
Displays tiled model in the solid mode. Tiled Model Solid
Displays tiled model in the wireframe mode. Tiled Model Wireframe
Displays or hides camera positions, reconstructed Show Cameras during image alignment.
Displays or hides image thumbnails in the camera Show Thumbnails placeholders.
Displays or hides 3D shapes. Show Shapes
Displays or hides positions of markers placed on Show Markers the model.
Displays or hides stereographic image overlay. Show Images
Locks current image in stereographic image Lock Images overlay mode.
Displays or hides enabled aligned chunks. Show Aligned Chunks

113

<!-- p. 120 -->

Graphical user interface

Photo view commands
Undo the last mask editing operation. Undo
Redo the previously undone mask editing Redo operation.
Switches to the navigation mode. Navigation
Rectangle selection tool. Rectangle Selection
Intelligent scissors tool. Intelligent Scissors
Intelligent paint tool. Intelligent Paint
Magic wand tool. Magic Wand
Resets current selection. Reset Selection
Switches to the 3D point drawing tool. Draw Point
Switches to the 3D polyline drawing tool. Draw Polyline
Switches to the 3D polygon drawing tool. Draw Polygon
3D coordinate and linear distance measurement Ruler tool.
Adds current selection to the mask. Add Selection
Subtracts current selection from the mask. Subtract Selection
Inverts current selection. Invert Selection
Adjusts image brightness and contrast for more Set Brightness convenient display.
Rotates the image clockwise. Rotate Right
Rotates the image counterclockwise. Rotate Left
Increases magnification. Zoom In
Decreases magnification. Zoom Out
Resets the viewport to display the whole image. Reset View
Enables or disables the mask shading overlay. Show Masks
Enables or disables the depth map overlay. Show Depth Maps
Displays or hides shapes on the current image. Show Shapes
Displays or hides marker projections. Show Markers
Displays or hides residuals related to marker Show Marker Residuals projections.
Displays or hides tie point projections. Show Points

114

<!-- p. 121 -->

Graphical user interface

Photo view commands
Displays or hides residuals related to tie point Show Point Residuals projections.

Ortho view commands
Switches to the navigation mode. Navigation
Rectangle selection tool. Rectangle Selection
Circle selection tool. Circle Selection
Free-form selection tool. Free-Form Selection
Resets current selection. Reset Selection
Switches to the point drawing tool. Draw Point
Switches to the polyline drawing tool. Draw Polyline
Switches to the polygon drawing tool. Draw Polygon
Switches to the patch drawing tool. Draw Patch
2D linear distance measurement tool. Ruler
Switches to the digital elevation model display DEM mode.
Switches to the orthomosaic display mode. Orthomosaic
Displays Raster Calculator dialog for NDVI and Set Raster Transform other vegetation indices calculation.
Adjusts image brightness and contrast for more Set Brightness convenient display.
Applies all the manual edits to the orthomosaic. Update Orthomosaic
Increases the magnification of the image in the Zoom In Ortho view.
Decreases the magnification of the image in the Zoom Out Ortho view.
Resets the viewport to display the complete Reset View orthomosaic or DEM.
Enables or disables hillshading mode of digital Hillshading mode elevation mode visualization.
Displays or hides orthomosaic seamlines. Show Seamlines
Displays or hides shapes. Show Shapes
Displays or hides marker positions. Show Markers
Hot keys

Below is a list of default hot keys that can be customized in the Preferences dialog.

115

<!-- p. 122 -->

Graphical user interface

General

Create new project Ctrl + N
Save project Ctrl + S
Load project Ctrl + O
Run Script Ctrl + R
Full Screen F11
Model View

Undo (only for Delete, Assign Class / Classify Ctrl + Z
Ground Points,Masking and Close Holes
operations)
Redo (only for Delete, Assign Class / Classify Ctrl + Y
Ground Points,Masking and Close Holes
operations)
Switch between navigation and any other Space
previously selected mode
Reset view 0
Switch to stereoview mode 9
Switch between orthographic and perspective view 5
modes
Change the angle for perspective view Ctrl + mouse wheel
Assign dense cloud class (only if some points are Ctrl + Shift + C
selected)
Predefined Views
Top 7
Bottom Ctrl + 7
Right 3
Left Ctrl + 3
Front 1
Back Ctrl + 1
Rotate View
Rotate Up 8
Rotate Down 2
Rotate Left 4
Rotate Right 6
Photo View

Next photo (according to Photos pane order) Page Up
Previous photo (according to Photos pane order) Page Down
Go to the next marker on the same photo Tab

116

<!-- p. 123 -->

Graphical user interface

Go to the previous marker on the same photo Shift + Tab
Navigation mode V
Selection Tools
Rectangle selection M
Intelligent scissors L
Intelligent paint P
Magic wand W
Add selection Ctrl + Shift + A
Subtract selection Ctrl + Shift + S
Invert selection Ctrl + Shift + I

117

<!-- p. 124 -->

Appendix B. Supported formats
Images

Input formats Undistort formats
JPG JPG
TIFF TIFF
PNG PNG
BMP BMP
OpenEXR OpenEXR
JPEG 2000 JPEG 2000
TARGA
Digital Negative (DNG)
Portable Bit Map (PGM, PPM)
Multi-Picture Object (MPO)
Norpix Sequence (SEQ)
AscTec Thermal Images (ARA)
Camera calibration

Import formats Export formats
Agisoft Camera Calibration (*.xml) Agisoft Camera Calibration (*.xml)
Australis Camera Parameters (*.txt) Australis Camera Parameters (*.txt)
Australis v.7 Camera Parameters (*.txt) Australis v.7 Camera Parameters (*.txt)
PhotoModeler Camera Calibration (*.ini) PhotoModeler Camera Calibration (*.ini)
3DM CalibCam Camera Parameters (*.txt) 3DM CalibCam Camera Parameters (*.txt)
CalCam Camera Calibration (*.cal) CalCam Camera Calibration (*.cal)
Inpho Camera Calibration (*.txt) Inpho Camera Calibration (*.txt)
USGS Camera Calibration (*.txt) USGS Camera Calibration (*.txt)
OpenCV Camera Calibration (*.xml) OpenCV Camera Calibration (*.xml)
Z/I Distortion Grid (*.dat) Z/I Distortion Grid (*.dat)
Camera flight log

Input format Estimated positions
Agisoft XML (*xml) Agisoft XML (*xml)
Character-separated values (*.txt, *.csv) Character-separated values (*.txt)
EXIF meta data
MAVinci CSV (*.csv)

118

<!-- p. 125 -->

Supported formats

Input format Estimated positions
APM/PixHawk Log (*.log)
C-Astral Bramor log (*.log)
TopoAxis telemetry (*.tel)
GCP locations

Input format Estimated positions
Character-separated values (*.txt, *.csv) Character-separated values (*.txt)
Agisoft XML (*.xml) Agisoft XML (*.xml)
Interior and exterior camera orientation
parameters

Import camera positions Export camera positions
Agisoft XML (*.xml) Agisoft XML (*.xml)
Autodesk FBX (*.fbx) Autodesk FBX (*.fbx)
Alembic (*.abc) Alembic (*.abc)
Realviz RZML (*.rzml) Realviz RZML (*.rzml)
Bundler (*.out) Bundler (*.out)
Inpho Project File (*.prj) Inpho Project File (*.prj)
BINGO (*.dat) BINGO Exterior Orientation (*.dat)
VisionMap Detailed Report (*.txt) Boujou (*.txt)
Omega Phi Kappa (*.txt)
PATB Exterior Orientation (*.ptb)
CHAN files (*.chan)
ORIMA (*.txt)
AeroSys Exterior Orientation (*.orn)
Summit Evolution Project (*.smtxml)
Blocks Exchange (*.xml)
Tie points

Export matches
BINGO (*.dat)
ORIMA (*.txt)
Import not available PATB (*.ptb)
Summit Evolution Project (*.smtxml)
Blocks Exchange (*.xml)

119

<!-- p. 126 -->

Supported formats

Sparse/dense point cloud

Import formats Export formats
Wavefront OBJ (*.obj) Wavefront OBJ (*.obj)
Stanford PLY (*.ply) Stanford PLY (*.ply)
ASCII PTS (*.pts) ASCII PTS (*.pts)
ASPRS LAS (*.las) ASPRS LAS (*.las)
LAZ (*.laz) LAZ (*.laz)
ASTM E57 (*.e57) ASTM E57 (*.e57)
XYZ Point Cloud (*.txt)
Cesium 3D Tiles (*.zip)
Universal 3D (*.u3d)
Autodesk DXF (*.dxf)
potree (*.zip)
Agisoft OC3 (*.oc3)
Topcon CL3 (*.cl3)
Adobe 3D PDF (*.pdf)
Mesh model

Import mesh Export mesh
Wavefront OBJ (*.obj) Wavefront OBJ (*.obj)
3DS models (*.3ds) 3DS models (*.3ds)
COLLADA (*.dae) COLLADA (*.dae)
Stanford PLY (*.ply) Stanford PLY (*.ply)
Alembic (*.abc) Alembic (*.abc)
STL models (*.stl) STL models (*.stl)
Autodesk DXF (*.dxf) Autodesk DXF (*.dxf)
Autodesk FBX (*.fbx) Autodesk FBX (*.fbx)
Universal 3D models (*.u3d) Universal 3D models (*.u3d)
OpenCTM models (*.ctm) VRML models (*.wrl)
Binary glTF (*.glb)
X3D models (*.x3d)
OpenSceneGraph (*.osgb)
Google Earth KMZ (*.kmz)
Adobe 3D PDF (*.pdf)
Texture

Import texture Export texture
JPG JPG

120

<!-- p. 127 -->

Supported formats

Import texture Export texture
TIFF TIFF
PNG PNG
BMP BMP
TARGA TARGA
JPEG 2000 JPEG 2000
OpenEXR OpenEXR
Orthomosaic

Export orthomosaic
GeoTIFF
JPG
JPEG 2000
PNG
BMP
Import not available Google Earth KML/KMZ
Google Map Tiles
MBTiles
World Wind Tiles
Tiled Map Service Tiles
Digital elevation model (DSM/DTM)

Import DEM Export DEM
GeoTIFF elevation (*.tif) GeoTIFF elevation (*.tif)
Arc/Info ASCII Grid (*.asc)
Band interleaved file format (*.bil)
XYZ (*.xyz)
Sputnik KMZ (*.kmz)
Tiled models

Export tiles
Cesium 3D Tiles (*.zip)
Scene Layer Package (*.slpk)
Import not available PhotoMesh Layer (*.zip)
OpenSceneGraph (*.osgb)
Agisoft Tiled Model (*.tls)
Agisoft Tile Archive (*.zip)

121

<!-- p. 128 -->

Supported formats

Shapes and contours

Import shapes Export shapes/contours
Shape Files (*.shp) Shape Files (*.shp)
DXF Files (*.dxf) DXF Files (*.dxf)
KML files (*.kml) KML Files (*.kml)
KMZ files (*.kmz) KMZ Files (*.kmz)

122

<!-- p. 129 -->

Appendix C. Camera models

Agisoft Metashape supports several parametric lens distortion models. Specific model which approximates
best a real distortion field must be selected before processing. All models assume a central projection
camera. Non-linear distortions are modeled using Brown's distortion model.

A camera model specifies the transformation from point coordinates in the local camera coordinate system
to the pixel coordinates in the image frame.

The local camera coordinate system has origin at the camera projection center. The Z axis points towards
the viewing direction, X axis points to the right, Y axis points down.

The image coordinate system has origin at the top left image pixel, with the center of the top left pixel
having coordinates (0.5, 0.5). The X axis in the image coordinate system points to the right, Y axis points
down. Image coordinates are measured in pixels.

Equations used to project a points in the local camera coordinate system to the image plane are provided
below for each supported camera model.

The following definitions are used in the equations:

(X, Y, Z) - point coordinates in the local camera coordinate system,

(u, v) - projected point coordinates in the image coordinate system (in pixels),

f - focal length,

cx, cy - principal point offset,
K1, K2, K3, K4 - radial distortion coefficients,
P1, P2, P3, P4 - tangential distortion coefficients,
B1, B2 - affinity and non-orthogonality (skew) coefficients,

w, h - image width and height in pixels.
Frame cameras

x = X / Z

y = Y / Z
r = sqrt(x2 + y2)
x' = x(1 + K1r2 + K2r4 + K3r6 + K4r8) + (P1(r2+2x2) + 2P2xy)(1 + P3r2 + P4r4)
y' = y(1 + K1r2 + K2r4 + K3r6 + K4r8) + (P2(r2+2y2) + 2P1xy)(1 + P3r2 + P4r4)
u = w * 0.5 + cx + x'f + x'B1 + y'B2
v = h * 0.5 + cy + y'f
Fisheye cameras

x0 = X / Z

123

<!-- p. 130 -->

Camera models

y0 = Y / Z
r0 = sqrt(x02 + y02)
x = x0 * tan-1r0 / r0
y = y0 * tan-1r0 / r0
r = sqrt(x2 + y2)
x' = x(1 + K1r2 + K2r4 + K3r6 + K4r8) + (P1(r2+2x2) + 2P2xy)(1 + P3r2 + P4r4)
y' = y(1 + K1r2 + K2r4 + K3r6 + K4r8) + (P2(r2+2y2) + 2P1xy)(1 + P3r2 + P4r4)

u = w * 0.5 + cx + x'f + x'B1 + y'B2

v = h * 0.5 + cy + y'f
Spherical cameras (equirectangular projection)
u = w * 0.5 + f * tan-1(X / Z)
v = h * 0.5 + f * tan-1(Y / sqrt(X2 + Z2))

where:

f = w / (2 * pi)
Note

• Spherical (equirectangular) camera model doesn't support distortions. All distortions should be
corrected before loading images in Metashape.

• In case you are capturing panoramas with a rotated frame/fisheye camera, we recommend to
process original images in Metashape using camera station function instead of stitching them in
external software.
Spherical cameras (cylindrical projection)
u = w * 0.5 + f * tan-1(X / Z)
v = h * 0.5 + f * Y / sqrt(X2 + Z2)

where:

f = w / (2 * pi)
Note

• Spherical (cylindrical) camera model doesn't support distortions. All distortions should be
corrected before loading images in Metashape.

• In case you are capturing panoramas with a rotated frame/fisheye camera, we recommend to
process original images in Metashape using camera station function instead of stitching them in
external software.

124
