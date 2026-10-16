---
type: libro
title: "out"
author: ""
categoria: "Metodologías y técnicas de reconocimiento y evaluación"
paginas: 9
extraccion: "texto"
fuente: "local:D:/UPV/MCPA/Asignaturas/Metodologías y técnicas de reconocimiento y evaluación/MTRE. Ej. 2/Análisis documental de archivo/Material de apoyo/out.pdf"
convertido: 2026-10-16
---

# out

> Texto extraído de `Metodologías y técnicas de reconocimiento y evaluación\MTRE. Ej. 2\Análisis documental de archivo\Material de apoyo\out.pdf` (9 páginas, texto). El PDF original está en el disco D: (UPV\MCPA\Asignaturas); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVI-4/W5-2021
The 6th International Conference on Smart City Applications, 27–29 October 2021, Karabuk University, Virtual Safranbolu, Turkey

COLOURIMETRIC CALIBRATION FOR PHOTOGRAPHY, PHOTOGRAMMETRY, AND
PHOTOMODELLING WITHIN ARCHITECTURAL SURVEY

Laura Carnevali1, Fabio Lanfranchi1, Luca Martelli1, Massimo Martelli2

1Dept. of History, Representation and Restoration of Architecture, “Sapienza” University of Rome, Italy,
laura.carnevali@uniroma1.it, fabio.lanfranchi@uniroma1.it, luca.martelli@uniroma1.it
2Freelance computer programmer, massimo@martel.li

KEY WORDS: Architecture, Colour Imaging, Survey, Colourimetric calibration, Photogrammetry, Photomodelling.

ABSTRACT:

In accordance with the “Declaration of Rome on architectural survey”, we can affirm that recording and interpretation of colour
information in photographic surveying, in photogrammetric surveying and in photomodelling requires careful planning of Colour
Imaging processes. Information acquired by an optical sensor is influenced not just by the actual photographed scene, but also by the
spectral sensitivity of the sensor. We have adopted, from the field of Cultural Heritage, a method of colourimetric calibration for
digital photographs and have proposed some adjustments to finalise this process for the purposes of Architectural Survey. With the
use of a colourimetric target and a non-linear transformation algorithm, our Colour Imaging method statistically reconstructs colours
conventionally unrecordable by a commercial camera. In addition, this method reconstructs colours as if the photographed object
were exposed to a standard illuminant, assessing a colour error parameter value for each photo. By including the colourimetric target
in every shot and by applying the calibration algorithm to all photographs taken, the process correlates all data sets to a single
standard illuminant: regarding photomodelling, this leads to a more uniform and detailed representation of the surfaces of virtual
models. We present two successful examples of application: one focused on a design object with physioplastic decoration and
another regarding a circular fountain in a historic villa.

\1. INTRODUCTION converting the colour space of the photo into the grey scale
(De Luca, 2011, Lowe, 2004).
1.1 General Instructions C. In most cases, photographic and photogrammetric
surveying involves outdoor shooting under uncontrolled
The more imaging (i.e. the processes of capturing, managing conditions, where the features of natural illumination are
and displaying images) acquires relevance within Architectural complex and mutable, not to mention that any material
Survey, the greater the role of colours treated by it in relation to captured in different places and at different times reacts to
knowledge of the investigated construction. Consequently, we light in different ways (Gaiani et al., 2017).
have to take into account three issues:
Issue A had already been addressed in the field of Colour
A. During photographic and photogrammetric surveying, the Imaging applied to Cultural Heritage (Apollonio et al., 2021,
volume of colour data which can be recorded is limited by Melis et al., 2013). However, there is no critical review about
camera spectral sensitivity. The risk of data loss could also implications of these issues within Architectural Survey at the
arise when working on digital photos with inadequately moment: we discuss such outcomes in Section 2. Regarding
calibrated monitors and printers, or with colour spaces too issue B and C, automated pre-processing methods for
small for the needs. For the sake of production, photogrammetry and photomodelling had already been
management and preservation of documentation envisaged proposed: these involve characterisation of an entire
by the “Declaration of Rome on architectural survey”, photographic data set by including a colourimetric target in one
avoiding colour data loss in transitions from a digital or two shoots (Apollonio et al., 2021, Gaiani et al., 2017,
device to another (or from a graphic application to another) Versaci and Cardaci, 2011). In Section 3 we present an
is significant (Cundari, 2013). alternative to such methods, which allows us to evaluate colour
B. Accuracy into recording and interpreting chromatic fidelity in each single photo. In Section 4 we refer three
properties of a work of Architecture not only influences our applications of the proposed method and report their results.
knowledge about the surfaces of that construction: it also Finally, we draw some conclusions in Section 5.
involves the detection of scale-invariant keypoints by
algorithms dedicated to digital photogrammetry and
photomodelling. Therefore, colour rendering influences
individuation of homologous points between one photo and 2. REVIEW OF LITERATURE
another. Scale-Invariant Feature Transform (SIFT), for
example, is an essential algorithm for Structure from 2.1 Colourimetry instruments
Motion (SfM) and indirectly acts as a function of the pixel
colours making up the photograph. This because it is based 2.1.1 Colour Matching Functions (CMF) and Chromaticity
on monochromatic intensities corresponding to these Diagram (CIE 1931): When light radiation is reflected by a
colours. In other words, SIFT relies on values obtained by surface and reaches the visual apparatus, it carries spectral
emission information combined with information about spectral
reflectance of that same surface. The human eye is unable to

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVI-4-W5-2021-151-2021 | © Author(s) 2021. CC BY 4.0 License. 151

<!-- p. 2 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVI-4/W5-2021
The 6th International Conference on Smart City Applications, 27–29 October 2021, Karabuk University, Virtual Safranbolu, Turkey

resolve the spectrum of received radiation with great precision.
It rather performs coarse sampling through the sensitivity of
retinal cones, encoding light radiation into three types of
nervous stimuli. Considering only the visible light spectrum,
cones sensitive to short waves transmit stimuli associated with
blue; cones sensitive to medium waves transmit stimuli for
green; cones sensitive to long waves transmit stimuli for red. In
1931, the Commission Internationale de l’Éclairage (CIE)
ratified three weighting functions, based on the visual apparatus
of a “standard observer”: these are the Colour Matching
Functions (CMF), which can be used to convert the parameters
of a spectral radiation into a set of X, Y, Z values (Figure 1).

Figure 2. Normalised plane xyz in the tristimulus space.

Figure 1. XYZ Colour Matching Functions (CMF) of CIE 1964
standard observer.

X, Y and Z are the tristimulus coordinates of a radiation Figure 3. Comparison between gamuts of several colour spaces
spectrum (within the visible light band). Therefore, in a space of and CIE 1931 Chromaticity Diagram.
coordinates XYZ a radiation spectrum can be represented with a
point Q(X, Y, Z). Vector OQ intersects a plane passing through as the preferred standard illuminant: it has a correlated colour
values (001, 010, 100) on the axes, defining point q with the temperature of 6 504 K and approximately represents the
following normalised coordinates (Figure 2): average daylight at midday from the northern sky, hence the
name (Commission Internationale de l’Éclairage, 1999, Lee,
2005). D65 includes direct solar light and light diffused by a
clear sky, so it is also known as the daylight standard
illuminant. Illuminants have an impact on photographic images
(1) within Architectural Survey. If we want to take a photo of a
construction with colour rendering as close as possible to the
colours found under a given real illuminant (in a certain place,
at a certain time and at a certain orientation), we could calibrate
where x, y, z = chromaticity coordinates our equipment according to on site measurements executed by a
X, Y, Z = CIE XYZ tristimulus values spectrophotometer. However, those measures will only be valid
for a scene that fulfils all the conditions of that specific
By varying the wavelength of a monochromatic source from far situation: the likelihood of being able to reuse them depends on
red to extreme blue, its chromaticity coordinates draw a the accuracy level we require. In some cases, an hour is just
counterclockwise arc inside a triangle with vertices (001, 010, enough for make us need new measurements with the
100). The Chromaticity Diagram, also ratified by CIE in 1931, spectrophotometer: colour information is very difficult to relate
is obtained by connecting the ends of this arc with a segment in between two photos taken one hour apart. If, on the other hand,
plane xy (Melis et al., 2013, Oleari, 2008, Oleari, 2016). The we want to obtain a colour rendering of the construction as if it
area thus circumscribed represents all colours perceptible to the were illuminated in a neutral environment and to have colour
average human eye, while points of maximum saturation are data comparable with information of other photos taken outside
located on the outline (Figure 3). In order to determine the that precise context, we should calibrate our instrumentation
colourimetric coordinates of a measured colour, it is necessary according to a standard illuminant such as D65. This also applies
to combine the spectral reflectance of that measurement, the when comparing colourimetric information from two sequences
CMF of the observer and a reference illuminant (Lindbloom, of photographs depicting the same construction under two
2017). noticeably different lighting conditions (e.g. photos taken at two
significantly distant times in the same day).
2.1.2 Standard illuminants: The specification of colour
measurements requires the specification of the illumination. 2.2 Colour Imaging technologies
Since 1931, CIE has also been ratifying “standard sources” and
“standard illuminants”: the term “illuminant” identifies the 2.2.1 Silicon sensors, sensitivity and demosaicisation: In
specification of a spectral power distribution which may or may silicon sensors, the amount of electrical charge produced per
not be physically realisable. In order to limit the number of photon, i.e. per wave, depends on the wavelength: they are
illuminants used in colourimetry, CIE recommends using D65 typically responsive to wavelengths between a little over 300

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVI-4-W5-2021-151-2021 | © Author(s) 2021. CC BY 4.0 License. 152

<!-- p. 3 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVI-4/W5-2021
The 6th International Conference on Smart City Applications, 27–29 October 2021, Karabuk University, Virtual Safranbolu, Turkey

nm and a little over 1 100 nm. So, in order to be used in digital assigning each device (camera, scanner, screen, printer, etc.) a
cameras, silicon sensors must be shielded by selective filters. colour profile, based on the characteristics of the machine itself.
Similarly to the cones of human retina, each silicon sensor Colour profiles follow regulations and standards promoted by
model has its own specific sensitivity, which may differ from the International Colour Consortium (ICC): therefore, they are
ones of other models. When we take a photo, the silicon sensor also known as ICC profiles. Device manufacturers and users can
ponders the spectrum of emerging radiation according to its generate ICC profiles using specific instruments for
own sensitivity functions, then it saves all recorded data in a colourimetric calibration (tristimulus colourimeters and
RAW file on a memory. What is contained in a RAW file is not spectrophotometers). An ICC profile contains conversion rules
a proper image, but the totality of all information that the between the colour space values described in the profile and
camera recorded following settings we chose. Through a another standard colour space, called Profile Connection Space
process of interpolation called demosaicisation, several raster (PCS). According to ICC regulations, a PCS must be based on
files in different formats (JPG, BMP, TIFF, etc.) can be L*a*b system or CIE XYZ system (with standard illuminant
extracted from a single RAW file. For each sensor pixel, the D50). We can express these transformations using a
other values of the two unrecorded primary colours can be correspondence table (interpolating whenever needed),
interpolated from values of adjacent pixels: in this way, the mathematical formulas, or a combination of the two
three RGB channels are compiled and a complete matrix of aforementioned methods. In the light of the above, it is clear
colour data is assembled (Oleari, 2016). that unplanned colour management and unreasonable
application of ICC profiles can undermine photographic
2.2.2 Colour spaces and gamuts: From the point of view of material destined to the operational archives of a survey.
Information Theory, synthesising a continuous spectrum with Therefore, we believe it is very useful to include planning of
just three values means losing much of the original data: there colour management and of ICC profiles into the contract
can be no biunivocal relationship between a spectrum and specifications envisaged by the “Declaration of Rome on
colourimetric coordinates. While a spectrum corresponds to a architectural survey” (Cundari, 2013).
specific set of colourimetric values, a set of colourimetric values
can simultaneously relate to a large number of diverse spectra. 2.3 Colour Imaging workflows for Architectural and
This phenomenon, known as metamerism, physiologically Cultural Heritage
involves the human eye. As a matter of fact, all manmade
imaging relies on metamerism, which is the simulation of Processes for colourimetric calibration of digital still cameras
almost all colours by mixing few resources with fixed radiation and images derived therefrom are codified in ISO 17321:
spectra, or pigments with fixed spectral reflectances. Current among the approaches described therein, one of the most widely
CMF do not minimise metamerism and fail to appropriately used in Architectural and Cultural Heritage makes use of a
represent a source at maximum saturation (monochrome), colourimetric target (ISO/TC 42 Photography, 2012). With this
except for some portions of plane xy. The ideal CMF graphs technique, spectral values of the target under on site
would be linear and subtend triangular areas: such functions illuminantcan be related to spectral values of the same target
would correspond to a hypothetical Chromaticity Diagram under an illuminant obtained in laboratory, under controlled
shaped like an equilateral triangle (Melis et al., 2013). In spite conditions: it allows colourimetric reconstruction of photo data
of its imperfections, CIE 1931 (two-dimensionally represented as if the scene depicted had been subjected to such a controlled
by the Chromaticity Diagram in Figure 3) is the most common illuminant. During demosaicisation of each photograph, the
example of a colour space covering all colours perceivable by a colourimetric characterisation algorithm evaluates deviation
standard observer. More generally, a colour space is the between spectral data of the target in the photo and spectral data
combination of a colour model and an appropriate mapping of the target under the controlled illuminant, expressing a value
function for that model. Many colour spaces can be considered of colour error parameter ∆E: the lower the ∆E value, the closer
as subsets of CIE 1931, which is unused in practical colour rendering will be to the sample (Oleari, 2016). As far as
applications because of its complexities. The domains or, in instrumental surveying is concerned, most methods proposed in
jargon, “gamuts” of the various colour spaces introduced over literature follow the practice of calibrating acquisition devices
the years can be represented as triangles fully or partially just once at the beginning of survey operations. In case of
contained by the Chromaticity Diagram in plane xy. survey with a terrestrial laser scanner equipped with a camera,
Technological advances have enabled codification of ever-wider the target is placed on a spot of the site: only part of the scan
colour spaces: for example, Wide Gamut RGB colour space is captures the colourimetric target (Versaci and Cardaci, 2011). In
more extensive than Adobe RGB 1998, which in turn is larger case of photogrammetric surveying, the target is included once
than sRGB (Figure 3). Similarly to what has been said about or twice maximum per acquired photo sequence (Apollonio et
silicon sensor inputs, metamerism and various fabrication issues al., 2021, Gaiani et al., 2017). In these applications, the trend is
prevent development of colour spaces and graphic to make colourimetric characterisation of images as automated
representation devices having the theoretical triangular as possible, using commercial targets and modifying or
Chromaticity Diagram as their gamut. Technological progress in supplementing the accompanying preset software.
Colour Imaging has, however, led to the introduction of graphic Colourimetric calibration is thus encapsulated in an automatic
output devices (screens, printers, etc.) with increasingly phase of image pre-processing and compilation of the observed
extensive gamuts: the correct use of this instrumentation, ∆E values. Within Colour Imaging dedicated to Cultural
however, requires appropriate colourimetric calibrations and the Heritage, however, the most precise methods involve design and
deployment of colour management processes. manufacture of custom-made colourimetric targets, as well as
laboratory sampling of the spectral values of these targets under
2.2.3 Colour management and International Colour several standard illuminants (Melis et al., 2013). Although a
Consortium (ICC) profiles: If two colour spaces to be process involving reduced use of colourimetric targets and the
connected have different extensions, colourimetric data may be most possible automation offers indisputable advantages in
altered during transition from the source colour space to the terms of image processing, we thought appropriate to propose
destination colour space. Colour Management Systems (CMS) an alternative method, derived from the aforementioned
allow non-destructive adaptation of colourimetric data by advanced Cultural Heritage techniques and finalised at

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVI-4-W5-2021-151-2021 | © Author(s) 2021. CC BY 4.0 License. 153

<!-- p. 4 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVI-4/W5-2021
The 6th International Conference on Smart City Applications, 27–29 October 2021, Karabuk University, Virtual Safranbolu, Turkey

photomodelling: it features greater accuracy and takes into RGB colour space and spectral reflectance values sampled in
account on site illuminant variations between individual laboratory under illuminant D65, Visipick© performed non-linear
photographic shots. colourimetric transformations based on CIE 64 CMF (Oleari,
2016): the algorithm statistically reconstructed all those colours
present in Wide Gamut RGB colour space but excluded from
\3. METHODOLOGY Adobe RGB colour space. As stated in literature, non-linear
colour characterisation processes require RGB values to be
3.1 Assembly of a custom-made colourimetric target and scaled when there is a change in exposure, but this may result in
sampling of its spectral reflection values angular shifts in XYZ vectors, leading to visible colour shifts
(Gaiani et al., 2017). However, in the advanced techniques for
We assembled two colourimetric targets of different Cultural Heritage to which we referred, non-linear
generations, according to the most advanced methods of Colour transformations are preferred as they allow corrections
Imaging for Cultural Heritage: we equipped them with fiducial introducible by the chosen illuminant, the camera sensitivity or
markers, useful for optional automatic detection during photo a combination of these two. In addition, the issue of angular
characterisation (Figure 4). We then subjected the target tiles to shifts in XYZ vectors had been effectively contained by
various standard illuminants in laboratory, including D65, and equipping our colourimetric targets with tiles specifically
sampled their spectral reflectance values using a chosen to form certain colour scales, unlike those in the
spectrophotometer. Thereafter, we entered these values into majority of commercially available kits, which averagely
Visipick© software for colourimetric calibration, created by include fewer shades. Referencing to spectral reflectance values
ProfilocoloreSrl. under D65, Visipick© expressed a ∆E00 value for the colour
rendering of each demosaicised photo: ∆E00 is expressed
according to CIE 2000 Formula, which could not be transcribed
here but is in public domain (Lindbloom, 2017, Oleari, 2016).

3.4 Photomodelling with Structure from Motion technique

In each of the first two case studies, a calibrated data set and an
uncalibrated data set have been introduced into Agisoft
Metashape© software, resulting in two separate virtual models.
To prevent the presence of colourimetric targets and their
supports from interfering with photo processing, we excluded
them by applying a mask on each photograph. As stated in its
User Manual, Agisoft Metashape© does not alter colour data of Figure 4. Colourimetric targets by Profilocolore Srl: left,
photos during processing (Agisoft LCC, 2021): therefore, we Mark.06; right, Mark.07.
deduced that colourimetric characteristics of photos calibrated
by Visipick© had been preserved in the textures of related3.2 On site shooting with colourimetric target
virtual models. For the first two case studies, in addition to a
In order to apply a SfM photomodelling process, we need to direct comparison between the three-dimensional model from
survey the object by taking reference measurements, by the calibrated data set and the one derived from the uncalibrated
carefully planning Ground Sampling Distance (GSD) and data set, we also performed a reliability comparison between the
coverages between photos, by materialising characteristic points two associated dense point clouds.
and, finally, by taking different shots of the object surface. For
each case study we just used one colourimetric target model,
which we included in every single shot. Colourimetric 4. EXPERIMENTS AND RESULTS
calibration processes require the target illumination conditions
4.1 Study Case No. 1: a decorated vaseto be as close as possible to those of the photographed subject.
Ideally, the target should be oriented perpendicular to the
To easily ascertain the possibilities of the method described in
optical axis, but it can be captured at moderately different Section 3, we conducted an initial test at the scale of design
positions as long as each of its tiles imprints at least a 10 px × objects. We chose a subject that would immediately test the
10 px square on the photo: this rule also applies in relation to process effectiveness: a vase with a painted silicone
camera-to-target distance. To take full advantage of the camera physioplastic decoration (Figure 5). We conducted the whole
sensitivity (an Olympus EM-10©), we set its RAW file saving experiment on a roof terrace on an afternoon with uniformly
options to Adobe RGB colour space. cloudy skies: this situation was certainly advantageous for a
photographic survey under semi-controlled conditions and
3.3 Statistical recreation of colours through aimed at photomodelling. In order to materialise scalar
characterisation during demosaicisation reference points, we preferred to use a grid of paper fiducial
markers on the tabletop rather than highlight characteristicTo demonstrate the impact of colourimetric calibration and ICC
points with pigments or pins, as these would inevitably coverprofile choice on operational archives for photomodelling, we
part of the vessel surface, making it impossible to capture. Weperformed two parallel and independent demosaicisation
took a total of 78 photos in 5 circular paths at various heightsprocesses on the RAW file data sets of each case study: one
and orientations around the object, including Mark.06 targetwith RawTherapee software, producing rasters with TIFF
(Figure 4) in each shot. In addition to obvious differences informat, 16-bit gamma integer precision, and destination ICC
colour rendering, all photos calibrated by Visipick© have lessprofile RTv4_sRGB (derived from sRGB colour space); the
noise and more sharpness, while the reliability of the associatedother with Visipick©, generating rasters with TIFF format, 16-
dense point cloud is slightly better in some parts (Figure 6).bit gamma integer precision, but destination ICC profile Wide
Gamut RGB. Stemming from RAW files expressed in Adobe

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVI-4-W5-2021-151-2021 | © Author(s) 2021. CC BY 4.0 License. 154

<!-- p. 5 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVI-4/W5-2021
The 6th International Conference on Smart City Applications, 27–29 October 2021, Karabuk University, Virtual Safranbolu, Turkey

Every ∆E00 value obtained during the characterisation of each reference, we carried out a direct mensuration of the metal fence
frame is shown in Table 1. around the fountain. We took a total of 113 photos in 4 circular
paths at various heights and locations around the object,
including Mark.07 target in each shot (Figure 4). Considering
that the photographic campaign was carried out under
unfavourable and uncontrolled circumstances, as well as under
two different lighting conditions, we can safely deem the results
shown in Table 2 as satisfactory. Colourimetric calibration by
Visipick© led to reconstruction of a more uniform illumination
over the entire surface of the virtual model (Figure 10).

Figure 5. Left, the surveyed vessel; right, orientation of capture
sequences.

Figure 8. Left, the surveyed fountain in Villa Alberoni-
Paganini; right, orientation of capture sequences.

Figure 6. Reliability comparison between the dense point
clouds of the vase. Improved parts are circled in black.

Figure 9. Reliability comparison between the dense point
clouds of the fountain. Improved parts are circled in black.

Figure 7. Comparison between the textured three-dimensional
models of the vase.

4.2 Study Case No. 2: a circular fountain Figure 10. Comparison between the textured three-dimensional
models of the fountain.
To easily ascertain the possibilities of the method described in
Section 3, we conducted an initial test at the scale of design
4.3 Study Case No. 3: a historic aedicule
objects. We chose a subject that would immediately test the
process effectiveness: a vase with a painted silicone In order to assess reproducibility of the method on even larger
physioplastic decoration (Figure 5). We conducted the whole scale, we have attempted a photographic campaign of the
experiment on a roof terrace on an afternoon with uniformly Celebratory Aedicule of Villa Torlonia, also in Rome (Figure
cloudy skies: this situation was certainly advantageous for a 11). Although the results shown in Table 3 have not proven
photographic survey under semi-controlled conditions and overly problematic, we found that the chiaroscuro effects of
aimed at photomodelling. In order to materialise scalar such a complex architecture present difficulties: the presence of
reference points, we preferred to use a grid of paper fiducial heavily shaded areas causes the colourimetric characterisation
markers on the tabletop rather than highlight characteristic algorithm to overexpose surfaces which are already adequately
points with pigments or pins, as these would inevitably cover lit, burning out some details. After a direct inspection of
part of the vessel surface, making it impossible to capture. The calibrated photos, we have nevertheless observed excellent
purpose of the second test was to verify reproducibility of the sharpness in the previously shadowed parts, such that we can
method at architectural scale. We chose as our subject a clearly distinguish brick joints (Figure 12).
nineteenth-century circular fountain located in the park of Villa
Alberoni-Paganini in Rome (Figure 8). In order to have a scalar

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVI-4-W5-2021-151-2021 | © Author(s) 2021. CC BY 4.0 License. 155

<!-- p. 6 -->

COMPARISON BETWEEN COLOURIMETRICALLY COLOR ERROR PARAMETER (∆E00) VALUESOBTAINED DURING The UNCALIBRATED AND CALIBRATED PHOTOGRAPHS CHARACTERIZATION, PROVIDED BY VISIPICK© SOFTWARE The
6th
Uncalibrated photos within Calibrated photos within PATH A PATH B PATH C PATH D PATH E
RTv4_sRGB colour space Wide Gamut RGB color space
27 Mar 2021 27 Mar 2021 27 Mar 2021 27 Mar 2021 27 Mar 2021 14:30 – 16:30 14:30 – 16:30 14:30 – 16:30 14:30 – 16:30 14:30 – 16:30 International International Table Cloudy sky Cloudy sky Cloudy sky Cloudy sky Cloudy sky
\1. Path A Photo ID ∆E00 Photo ID ∆E00 Photo ID ∆E00 Photo ID ∆E00 Photo ID ∆E00 Archives
of Dataset VasoA01 1.876 VasoB01 1.927 VasoC01 1.845 VasoD01 1.851 VasoE01 1.784 Conferencethe
of Photo ID: VasoA07 Photo ID: VasoA07 on
Study VasoA02 1.875 VasoB02 1.829 VasoC02 1.752 VasoD02 1.755 VasoE02 1.662 VasoA03 1.880 VasoB03 1.830 VasoC03 1.896 VasoD03 1.878 VasoE03 1.785 Smart
City This Case Path VasoA04 1.872 VasoB04 1.878 VasoC04 1.935 VasoD04 2.229 VasoE04 1.987 No. B Photogrammetry,
1: VasoA05 2.129 VasoB05 2.047 VasoC05 2.278 VasoD05 2.223 VasoE05 1.992
the Photo ID: VasoB08 Photo ID: VasoB08 VasoA06 2.307 VasoB06 2.192 VasoC06 2.950 VasoD06 2.658 VasoE06 1.842 contribution Applications,Remote
vase VasoA07 2.550 VasoB07 2.000 VasoC07 2.087 VasoD07 2.706 VasoE07 2.110 has
27–29Sensing with VasoA08 2.086 VasoB08 2.111 VasoC08 2.228 VasoD08 2.438 VasoE08 2.051 been
Path and
C VasoA09 1.963 VasoB09 2.026 VasoC09 2.090 VasoD09 2.342 VasoE09 2.062 Octoberhttps://doi.org/10.5194/isprs-archives-XLVI-4-W5-2021-151-2021

\| VasoA10 2.151 VasoB10 2.173 VasoC10 1.942 VasoD10 2.093 VasoE10 2.179© Spatial physioplastic Photo ID: VasoC07 Photo ID: VasoC07 2021,
VasoA11 1.853 VasoB11 2.099 VasoC11 2.044 VasoD11 2.202 VasoE11 2.035 peer-reviewed.
Author(s) VasoA12 1.763 VasoB12 2.191 VasoC12 1.972 VasoD12 2.059 VasoE12 1.972 Karabuk Information decoration
Path VasoA13 1.799 VasoB13 1.963 VasoC13 1.925 VasoD13 1.973 VasoE13 1.7132021. in
D
CC VasoA14 1.870 VasoB14 2.057 VasoC14 2.129 VasoD14 1.779 VasoE14 1.838 University,Sciences,BY painted VasoA15 1.940 VasoB15 1.978 VasoC15 1.967 VasoD15 1.902 Photo ID: VasoD07 Photo ID: VasoD07
4.0 VasoA16 1.808 VasoB16 1.878 VasoD16 1.951 VirtualVolume silicone.
VasoB17 1.897License.
Path
Path A Path B Path C Path D Path E E 1.983 2.004 2.069 2.127 1.929 Safranbolu,
average average average average average XLVI-4/W5-2021 SURVEY AVERAGE 2.025 Turkey Photo ID: VasoE07 Photo ID: VasoE07
156

<!-- p. 7 -->

COMPARISON BETWEEN COLOURIMETRICALLY COLOR ERROR PARAMETER (∆E00) VALUES OBTAINED DURING The UNCALIBRATED AND CALIBRATED PHOTOGRAPHS CHARACTERIZATION, PROVIDED BY VISIPICK© SOFTWARE The
PATH A PATH B PATH C PATH D 6th Uncalibrated photos within Calibrated photos within
29 Jul 2021 29 Jul 2021 29 Jul 2021 28 Jul 2021 RTv4_sRGB colour space Wide Gamut RGB colour space
18:45 – 20:15 18:45 – 20:15 18:45 – 20:15 7:40 – 8:40 Clear sky Clear sky Clear sky Clear sky International Table Photo ID ∆E00 Photo ID ∆E00 Photo ID ∆E00 Photo ID ∆E00 International
\2. FonCirA01 1.840 FonCirB01 1.697 FonCirC01 1.912 FonCirD01 1.543 FonCirA02 1.665 FonCirB02 2.026 FonCirC02 1.982 FonCirD02 1.586 Archives Path Dataset A FonCirA03 1.767 FonCirB03 1.886 FonCirC03 1.960 FonCirD03 1.544 of of FonCirA04 1.626 FonCirB04 1.817 FonCirC04 1.761 FonCirD04 1.596 Conferencethe
FonCirA05 1.860 FonCirB05 1.919 FonCirC05 1.913 FonCirD05 1.593 on
FonCirA06 1.755 FonCirB06 1.737 FonCirC06 2.709 FonCirD06 1.656 Study
Photo ID: FonCirA15 Photo ID: FonCirA15 FonCirA07 1.728 FonCirB07 1.780 FonCirC07 1.993 FonCirD07 1.653 Smart Case FonCirA08 1.665 FonCirB08 1.749 FonCirC08 2.559 FonCirD08 1.631
This FonCirA09 1.874 FonCirB09 1.713 FonCirC09 2.016 FonCirD09 1.582 City No. FonCirA10 1.731 FonCirB10 1.840 FonCirC10 2.300 FonCirD10 1.556 Photogrammetry, 2:
FonCirA11 1.710 FonCirB11 1.849 FonCirC11 1.739 FonCirD11 1.594
the Path FonCirA12 1.907 FonCirB12 1.760 FonCirC12 1.948 FonCirD12 1.678
B FonCirA13 1.963 FonCirB13 1.679 FonCirC13 1.824 FonCirD13 1.652 contribution Applications,Remote
FonCirA14 1.752 FonCirB14 1.846 FonCirC14 1.728 FonCirD14 1.540 has circular FonCirA15 1.792 FonCirB15 1.642 FonCirC15 1.887 FonCirD15 1.571 27–29 FonCirA16 1.980 FonCirB16 1.851 FonCirC16 2.239 FonCirD16 1.676 Sensing
FonCirA17 1.877 FonCirB17 1.770 FonCirC17 2.068 FonCirD17 1.627 and been fountain Photo ID: FonCirB07 Photo ID: FonCirB07 FonCirA18 2.021 FonCirB18 1.800 FonCirC18 1.769 FonCirD18 1.635 in Octoberhttps://doi.org/10.5194/isprs-archives-XLVI-4-W5-2021-151-2021 FonCirA19 1.929 FonCirB19 2.113 FonCirC19 2.103 FonCirD19 1.779
\| the© FonCirA20 1.836 FonCirB20 2.052 FonCirC20 1.915 Average 1.615 Spatial 2021, 2.019 FonCirB21 1.806 FonCirC21 2.261 park Path FonCirA21 peer-reviewed. FonCirA22 1.927 FonCirB22 1.827 FonCirC22 2.099
of C
FonCirA23 1.971 FonCirB23 1.861 FonCirC23 2.263Author(s) Karabuk Villa FonCirA24 2.185 FonCirB24 1.622 FonCirC24 2.347 Information
FonCirA25 1.874 FonCirB25 1.697 FonCirC25 2.2682021.
Photo ID: FonCirC07 Photo ID: FonCirC07 FonCirA26 2.042 FonCirB26 1.640 FonCirC26 2.311
CC FonCirA27 1.927 Average 1.807 FonCirC27 1.914 University,Sciences,BY FonCirA28 2.178 Average 2.066
4.0 PATH A VirtualVolume Photo ID ∆E00 Photo ID ∆E00 Photo ID ∆E00 Photo ID ∆E00 Alberoni-Paganini. Path FonCirA29 2.205 FonCirA33 1.891 FonCirA37 1.808 FonCirA41 2.010License. D FonCirA30 1.848 FonCirA34 1.835 FonCirA38 1.904 Average 1.912
FonCirA31 2.210 FonCirA35 2.164 FonCirA39 2.097 Safranbolu,
FonCirA32 2.168 FonCirA36 1.878 FonCirA40 1.970
Photo ID: FonCirD06 Photo ID: FonCirD06 SURVEY AVERAGE 1.875 XLVI-4/W5-2021 Turkey
157

<!-- p. 8 -->

The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLVI-4/W5-2021
The 6th International Conference on Smart City Applications, 27–29 October 2021, Karabuk University, Virtual Safranbolu, Turkey

REFERENCES

Agisoft LCC, 2021. Metashape Professional Edition© Software.
Version 1.7.

Apollonio, F. I., Fantini, F., Garagnani, S., Gaiani, M., 2021. A
Photogrammetry-Based Workflow for the Accurate 3D
Construction and Visualization of Museums Assets. Remote
Sensing, 13(3), 486. doi.org/10.3390/rs13030486.
Figure 11. Left, the Celebratory Aedicule of Villa Torlonia;
right, orientation of the capture sequences. Commission Internationale de l’Éclairage, 1999. CIE Standard
Illuminants for Colorimetry (ISO 10526:1999/CIE S005/E-
1998).
ID A01 A02 A03 A04 A05 A06 A07 A08 A09 A10
Cundari, C., 2013. Il rilievo architettonico. Ragioni.
∆E00 3.24 2.72 2.80 2.69 2.37 2.84 2.64 2.76 2.94 2.45 Fondamenti. Applicazioni. Edizioni Kappa - Aracne Editrice
ID A11 A12 A13 A14 A15 A16 A17 A18 A19 A20 S.r.l., Rome, Italy.
∆E00 2.55 2.49 2.62 3.41 2.68 2.46 2.78 2.36 2.34 2.47
De Luca, L., 2011. La fotomodellazione architettonica. Rilievo,
ID A21 avg. modellazione, rappresentazione di edifici a partire da
∆E00 2.43 2.67 fotografie. Dario Flaccovio Editore, Palermo, Italy.

Table 3. Colour error parameter (∆E00) values for the Gaiani, M., Apollonio, F. I., Ballabeni, A., Remondino, F., 2017.
Celebratory Aedicule in Study Case No. 3. Securing Color Fidelity in 3D Architectural Heritage Scenarios.
Sensors, 17(11), 2437. doi.org/10.3390/s17112437.

ISO/TC 42 Photography, 2012. Graphic technology and
photography — Colour characterisation of digital still cameras
(DSCs) — Part 1: Stimuli, metrology and test procedures (ISO
17321-1:2012).

Lee, H., 2005. Introduction to Color Imaging Science.
Cambridge University Press, Cambridge, UK.

Lindbloom, B., 2017. Computing xyz from spectral data
Figure 12. Two raster images from photo “A10”: left, (reflective and transmissive cases).
uncalibrated TIFF file; right, calibrated TIFF file. http://www.brucelindbloom.com (30 July 2021).

Lowe, D. G., 2004. Distinctive Image Features from Scale
\5. CONCLUSION Invariant Keypoints. Int. J. Comput. Vis., 60(2), 91-110.
https://doi.org/10.1023/B:VISI.0000029664.99615.94.In this work we have highlighted the importance of colour
spaces and colour management in photographic and
Melis, M., Miccoli, M., Quarta, D., 2013. Multispectralphotogrammetric surveying, in photomodelling and, more
Hypercolorimetry and automatic guided pigment identification:generally, in Architectural Survey. We have illustrated a method
some masterpieces case studies. SPIE Proceedings Volumefor reconstructing, by colourimetric calibration, colour
8790,Optics for Arts, Architecture, and Archaeology IV,information unattainable from a conventionally used
87900W. doi.org/10.1117/12.2020643.commercial camera, assessing the error of this statistical
reconstruction in each photo. Finally, we have reported on our
Oleari, C., 2008. Misurare il colore. Hoepli, Milan, Italy.first applications of the proposed method in SfM
photomodelling and have achieved more uniform illumination
Oleari, C., 2016. Standard colorimetry. Definitions, Algorithmsand more accurate reproduction of surfaces in the virtual
and Software. John Wiley and Sons Ltd, Chichester, UK.models. Possible continuations of this research could concern
greater interaction between colour management and digital
Profilocolore Srl, 2021. Visipick © Software, Version 1.3.three-dimensional models obtained by photomodelling, as well
as resolution of some issues through the study of even more
RawTherapee Development Team, 2020. RawTherapeesuitable colourimetric targets for Architectural Survey.
Software, Version 5.8. rawtherapee.com (04 February 2020).

Versaci, A., Cardaci, A., 2011. Il rilievo “automatico” del CONFLICTS OF INTEREST
colore: nuove tecnologie a supporto della lettura cromatica per
The authors declare that they have no conflict of interest. il restauro dell’edilizia storica. Il colore nel costruito storico.
innovazione, sperimentazione, applicazione, 13-15 October
ACKNOWLEDGEMENTS 2011, Lerici, Italy.
https://openarchive.icomos.org/id/eprint/1203 (30 July 2021).
The authors would like to thank Profilocolore Srl for making
their colourimetric targets and Visipick© software available for
the development of this paper.

This contribution has been peer-reviewed.
https://doi.org/10.5194/isprs-archives-XLVI-4-W5-2021-151-2021 | © Author(s) 2021. CC BY 4.0 License. 158

<!-- p. 9 -->

© 2021. This work is published under
https://creativecommons.org/licenses/by/4.0/(the “License”). Notwithstanding
the ProQuest Terms and Conditions, you may use this content in accordance
with the terms of the License.
