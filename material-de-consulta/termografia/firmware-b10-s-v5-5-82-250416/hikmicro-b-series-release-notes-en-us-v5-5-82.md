---
type: libro
title: "HIKMICRO B Series_Release Notes_en-US_V5.5.82"
author: "高晓萌"
categoria: "TERMOGRAFÍA"
paginas: 11
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/TERMOGRAFÍA/Firmware_B10(S)_V5.5.82_250416/HIKMICRO B Series_Release Notes_en-US_V5.5.82.pdf"
convertido: 2026-10-16
---

# HIKMICRO B Series_Release Notes_en-US_V5.5.82

> Texto extraído de `TERMOGRAFÍA\Firmware_B10(S)_V5.5.82_250416\HIKMICRO B Series_Release Notes_en-US_V5.5.82.pdf` (11 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

HIKMICRO B Series
Handheld Thermal Camera (V5.5.82)
Release Notes

<!-- p. 2 -->

HIKMICRO B Series• Release Notes

Legal Information
© Hangzhou Microimage Software Co., Ltd. ON BREACH OF CONTRACT, TORT
All rights reserved. (INCLUDING NEGLIGENCE), PRODUCT
About this Manual LIABILITY, OR OTHERWISE, IN CONNECTION
The Manual includes instructions for using WITH THE USE OF THE PRODUCT, EVEN IF
and managing the Product. Pictures, charts, HIKMICRO HAS BEEN ADVISED OF THE
images and all other information hereinafter POSSIBILITY OF SUCH DAMAGES OR LOSS.
are for description and explanation only. The YOU ACKNOWLEDGE THAT THE NATURE
information contained in the Manual is OF THE INTERNET PROVIDES FOR
subject to change, without notice, due to INHERENT SECURITY RISKS, AND
firmware updates or other reasons. Please HIKMICRO SHALL NOT TAKE ANY
find the latest version of this Manual at the RESPONSIBILITIES FOR ABNORMAL
HIKMICRO website OPERATION, PRIVACY LEAKAGE OR OTHER
(www.hikmicrotech.com/). DAMAGES RESULTING FROM CYBERPlease use this Manual with the guidance ATTACK, HACKER ATTACK, VIRUS
and assistance of professionals trained in INFECTION, OR OTHER INTERNET
supporting the Product. SECURITY RISKS; HOWEVER, HIKMICRO
Trademarks WILL PROVIDE TIMELY TECHNICAL
SUPPORT IF REQUIRED. and other HIKMICRO’s
YOU AGREE TO USE THIS PRODUCT INtrademarks and logos are the properties of
COMPLIANCE WITH ALL APPLICABLEHIKMICRO in various jurisdictions.
LAWS, AND YOU ARE SOLELY RESPONSIBLEOther trademarks and logos mentioned are
FOR ENSURING THAT YOUR USEthe properties of their respective owners.
CONFORMS TO THE APPLICABLE LAW.LEGAL DISCLAIMER
ESPECIALLY, YOU ARE RESPONSIBLE, FORTO THE MAXIMUM EXTENT PERMITTED BY
USING THIS PRODUCT IN A MANNER THATAPPLICABLE LAW, THIS MANUAL AND THE
DOES NOT INFRINGE ON THE RIGHTS OFPRODUCT DESCRIBED, WITH ITS
THIRD PARTIES, INCLUDING WITHOUTHARDWARE, SOFTWARE AND FIRMWARE,
LIMITATION, RIGHTS OF PUBLICITY,ARE PROVIDED “AS IS” AND “WITH ALL
INTELLECTUAL PROPERTY RIGHTS, ORFAULTS AND ERRORS”. HIKMICRO MAKES
DATA PROTECTION AND OTHER PRIVACYNO WARRANTIES, EXPRESS OR IMPLIED,
RIGHTS. YOU SHALL NOT USE THISINCLUDING WITHOUT LIMITATION,
PRODUCT FOR ANY PROHIBITED END-USES,MERCHANTABILITY, SATISFACTORY
INCLUDING THE DEVELOPMENT ORQUALITY, OR FITNESS FOR A PARTICULAR
PRODUCTION OF WEAPONS OF MASSPURPOSE. THE USE OF THE PRODUCT BY
DESTRUCTION, THE DEVELOPMENT ORYOU IS AT YOUR OWN RISK. IN NO EVENT
PRODUCTION OF CHEMICAL ORWILL HIKMICRO BE LIABLE TO YOU FOR
BIOLOGICAL WEAPONS, ANY ACTIVITIES INANY SPECIAL, CONSEQUENTIAL,
THE CONTEXT RELATED TO ANY NUCLEARINCIDENTAL, OR INDIRECT DAMAGES,
EXPLOSIVE OR UNSAFE NUCLEAR FUEL-INCLUDING, AMONG OTHERS, DAMAGES
CYCLE, OR IN SUPPORT OF HUMAN RIGHTSFOR LOSS OF BUSINESS PROFITS,
ABUSES.BUSINESS INTERRUPTION, OR LOSS OF
IN THE EVENT OF ANY CONFLICTSDATA, CORRUPTION OF SYSTEMS, OR LOSS
BETWEEN THIS MANUAL AND THEOF DOCUMENTATION, WHETHER BASED
APPLICABLE LAW, THE LATTER PREVAILS.

i

<!-- p. 3 -->

HIKMICRO B Series• Release Notes

TABLE OF CONTENTS
1 Introduction ................................................................................................................... 1
1.1 Version Information ................................................................................................................................. 1
1.2 More Information...................................................................................................................................... 1
1.3 Upgrade Device......................................................................................................................................... 2
1.3.1 Upgrade Device with USB .................................................................................................................... 2
1.3.2 Upgrade Device via HIKMICRO Viewer ............................................................................................... 2
2 New Features ................................................................................................................ 3
2.1 Scene Mode for Fast Anomaly Detection (B20s, B10S, B11S, B01S and B21LS) ................................ 3
2.2 Record Video is Available ........................................................................................................................ 4
2.3 A New Palette is Available: Blue Yellow .................................................................................................. 4
2.4 Status Prompts are Supported During Power On ................................................................................... 4
2.5 Alarm Mode Palettes is Available in Alarm Function ............................................................................. 4
2.6 Casting Screen via HIKMICRO Analyzer is Supported ........................................................................... 5
2.7 Others ........................................................................................................................................................ 5
3 Optimizations ................................................................................................................ 5
3.1 Distance and Parallax Correction are Merged ........................................................................................ 5
3.2 Others ........................................................................................................................................................ 5
4 FAQ on Upgrade ............................................................................................................. 6
4.1 Why my PC failed to detect the camera as a USB drive? ....................................................................... 6
4.2 What should I do when my PC notifies power surge on the USB port? ................................................. 6
4.3 What should I do when my PC notifies USB device not recognized? .................................................... 6
4.4 What should I do if my PC notifies the USB drive has a problem to be fixed? ..................................... 7

ii

<!-- p. 4 -->

HIKMICRO B Series• Release Notes

1 Introduction

The handheld thermal camera is an ideal solution which provides accurate
touch-free temperature measurement and heat distribution image display
for electrical predictive maintenance, building inspection, HVAC inspection,
manufacturing monitor, etc. HIKMICRO’s handheld thermal cameras have
been used widely in detecting temperature anomalies before detecting
radiator efficiency for HVAC inspection, searching for heat loss in buildings,
finding hot spots and invisible defects on mechanical or electrical systems
that could indicate a potential problem. They are also used for surveying
areas that are hard to reach with conventional measurement tools.

This document introduces optimizations in V5.5.82 of B Series.

1.1 Version Information

Item Description
Firmware Version V5.5.82 build 250416
B21L, B01S, B21LS, B01, B11, B20S, B10S, B20,
Models
B10

1.2 More Information
 Mobile Client: HIKMICRO Viewer (only for the camera models with Wi-Fi
and Hotspot)
https://www.hikmicrotech.com/en/industrial-products/hikmicro-viewer-
software/
 PC Client for analysis and report: HIKMICRO Analyzer
https://www.hikmicrotech.com/en/industrial-products/hikmicro-
analyzer-software/or contact technical support for help.
 Welcome to visit our website and see more Compatibility Lists.
https://www.hikmicrotech.com/en/support/download-
center/compatibility/

1

<!-- p. 5 -->

HIKMICRO B Series• Release Notes

1.3 Upgrade Device

1.3.1 Upgrade Device with USB

Before upgrading your camera, make sure:

 Fully charge your camera.
 Auto Power-off function is turned-off to avoid accidental suspension
during upgrading.
\1. Download new firmware from our website
(https://www.hikmicrotech.com/en/industrial-products/b20s-handheld-
thermal-imager/), and save it to your PC.
\2. Use supplied USB cable (USB-C to USB-A) to connect the device to PC.
\3. Open the detected disk on your PC.
\4. Unzip the firmware, and copy and paste the .dav file to the root directory
of the disk.
\5. Disconnect the device from PC and reboot the device to start upgrading
automatically. The upgrading lasts several minutes, please wait for the
process to complete.
1.3.2 Upgrade Device via HIKMICRO Viewer

BeforeYouStart
Scan the QR code below to download and install HIKMICRO Viewer on your
phone.

Android iOS

\1. Launch HIKMICRO Viewer on your phone.
\2. Upgrade the device. You can choose one of the following paths:
 In the home screen, tap Device Upgrade > Check for Updates.
 In the home screen, tap Device Info > Device Upgrade > Check for
Updates.

2

<!-- p. 6 -->

HIKMICRO B Series• Release Notes

2 New Features

2.1 Scene Mode for Fast Anomaly Detection (B20S,
B10S, B01S and B21LS)
To conduct fast anomaly detection, several preset modes are included in
Scene mode for various detection scenarios. Users can choose or
customize a scene based on targets.

Scene Mode Description
Inspect the water leak of building ceilings, walls and
Water Leak
floors indoors.
Detect indoor insulation deficiency of building walls,
Insulation
ceilings, common users can apply this scene.
Floor Heating Detect and observe the faults of floor heating system.
Electrical Detect and observe the faults of wires, circuits,
Faults electrical components, terminators, etc
Solar Panel Detect and observe the faults of solar panels
Insulation Pro Detect indoor insulation anomalies of building walls and
ceilings, professional users can apply this scene. Extra
parameters Indoor Temp., Outdoor Temp. and
Insulation Level are required.
Condensation Inspect potential moisture problems indoors. It is a
prerequisite to set Relative Humidity, Ambient Temp.,
and RH Threshold(%).
Users can customize a mode to save desired
Custom
temperature measurement parameters for future use.

SuperScene technology can assist in fast recognition for anomalies during
water leak and insulation detection. When SuperScene is enabled and water
leak/insulation anomalies are detected, Suspectwill be displayed on top of
live view.

Please refer to the user manual of B Series to access more detailed
information.

3

<!-- p. 7 -->

HIKMICRO B Series• Release Notes

2.2 Record Video is Available
\1. Hold the trigger in live view. When the recording icon and time display in
the interface, recording begins, and you can release the trigger.
\2. Press the trigger completes the recording. The device will display a pop-
up notification saying "Recording Succeeded”. The recording video will
be saved.

2.3 A New Palette is Available: Blue Yellow
A new palette Blue Yellow is available in this version.

2.4 Status Prompts are Supported During Power On
When the device is powered on, there appears “~” before a temperature
value, it means that your device is not well prepared for accurate
temperature measurement.

When the device is powered on and conducting image calibration, the
prompt “image calibrating…” is displayed on the top of live image.

2.5 Alarm Mode Palettes is Available in Alarm
Function
Alarm Mode Palettes is one of the alarm linkage. When the target’s
temperature is higher than the set value, the target will become red; when
the target’s temperature is lower than the set value, the target will become
blue.

4

<!-- p. 8 -->

HIKMICRO B Series• Release Notes

2.6 Casting Screen via HIKMICRO Analyzer is
Supported
In this version, the device supports casting screen to PC by HIKMICRO
Analyzer, a UVC protocol-based client software.

Please visit our website www.hikmicrotech.comor contact our technical
supports or customer service teams for installation packages, and
download and install HIKMICRO Analyzer.

2.7 Others
 UVC protocol - based video streaming with third-party software like
Xcapture is supported by macOS.
 Estonian is available in this version. Go to Settings > More Settings >
Language.

3 Optimizations

3.1 Distance and Parallax Correction are Merged
In this version, when you adjust the value of distance, it works for both
Distance in temperature measurement parameters and Parallax Correction
in Fusion image mode.

In live view, go to Settings > Distance, to adjust the distance.

3.2 Others
 Image calibration, display settings and the algorithm of Fusion mode
were optimized.
 The minimum difference value between the maximum temperature and
the minimum temperature of the temperature scale is 1 Celsius degree.

5

<!-- p. 9 -->

HIKMICRO B Series• Release Notes

4 FAQ on Upgrade

4.1 Why my PC failed to detect the camera as a USB
drive?
Check the following items:

 Use a good quality USB-C to USB-A cable to connect your PC to your
camera. The supplied cable is recommended. Normally, a cable should
be able to charge a camera and transfer data.
 Select USB Drive as the USB mode.
 Keep the camera powered on.

4.2 What should I do when my PC notifies power
surge on the USB port?

Check the following items:
 When you are looking for an adapter of USB-C to USB-A, please choose
an unpowered hub. A powered hub such as Surface Dock Station is not
compatible.
 If you are using a built-in USB PowerShare port in your PC, please try
another port.

4.3 What should I do when my PC notifies USB device
not recognized?

In most cases, it does not affect use. You can just ignore the prompt and
find the detected USB drive in This PC.

6

<!-- p. 10 -->

HIKMICRO B Series• Release Notes

4.4 What should I do if my PC notifies the USB drive
has a problem to be fixed?

Some Windows computers will scan a USB drive when it is connected, and
show the error. Click scan and fix, Windows will confirm the drive is fine and
connect to it. You can also skip scanning and find the detected USB drive in
This PC, which does not affect use in most cases.

7

<!-- p. 11 -->


