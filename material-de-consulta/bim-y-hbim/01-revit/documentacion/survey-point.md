---
type: libro
title: "Survey Point"
author: ""
categoria: "BIM Y HBIM"
paginas: 34
extraccion: "texto"
fuente: "local:E:/MATERIAL DE CONSULTA/BIM Y HBIM/01. Revit/DOCUMENTACIÓN/Survey Point.pdf"
convertido: 2026-10-16
---

# Survey Point

> Texto extraído de `BIM Y HBIM\01. Revit\DOCUMENTACIÓN\Survey Point.pdf` (34 páginas, texto). El PDF original está en el disco E: (MATERIAL DE CONSULTA); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

REVIT PURE PRESENTS
PAMPHLETS

ISSUE #14 / FALL 2019
SHARED SITES

revitpure.com
© Copyright 2019 - BIM Pure productions
by: Nicolas Catellier, Architect

<!-- p. 2 -->

PAMPHLETS COLLECTION

REVIT PURE - © Copyright 2019 - BIM Pure productions

<!-- p. 3 -->

PAMPHLETS COLLECTION

REVIT PURE - © Copyright 2019 - BIM Pure productions

<!-- p. 4 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

WHAT IS THIS PAMPHLET ?

Revit Pure Pamphlets are published 4 times a year by email. Each edition
covers a very specific Revit theme. We like to pick themes that are
complex and confusing. Our job is to make these topics simple for you.

WHY SHARED SITES

In Pamphlet #9, we covered the basic notion of Revit’s strange coordinate
system. In this issue, we’ll push further and explore how to properly use the
Shared Site feature. Shared Sites are used in order to have multiple linked
Revit files using the same site coordinates.

Before diving deep into these topics, we’ll go through a small recap of the
major things to know about coordinates.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 4

<!-- p. 5 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

UNDERSTAND THE DIFFERENCE BETWEEN ALL 3
COORDINATE ORIGIN POINTS

There are 3 different origin points in a Revit project: the Project Base
Point, the Survey Point and the secret Internal Origin. The next page
features a short description of each point. To learn more, make sure to
read Pamphlet #9.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 5

<!-- p. 6 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

PROJECT BASE POINT: This point is used almost
exclusively for internal purposes. It is used to place
dimensions relative to the building. It is represented
by a blue circle with a cross in the middle. It can also
be used to set the angle difference between True
North and Project North.

SURVEY POINT: This is used to create a “shared
coordinates” system among multiple linked Revit or
CAD files. That means its location is most useful when
exporting and importing files. It is usually placed relative
to a real-world site element such as the intersection of
2 property lines or a geodetic marker.

INTERNAL ORIGIN: This is the tricky one. This point
is invisible and cannot be moved. Most users don’t
even know it exists. By default, importing or exporting
a CAD or Revit file will be made relative to this super-
secret point, therefore confusing many people.

THE MYSTERIOUS SURVEY POINT

There are multiple ways to use the Survey Point. The way we recommend
is that you always keep it clipped. This way, it will always match the
Shared Site origin of the project. If you move an unclipped Survey Point,
you will probably cause confusion in your project.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 6

<!-- p. 7 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

WHY USE SHARED SITES?

Have a look at the image below. There are 3 different Revit models: two
building models and a site model. Each building has a specific local Project
Base Point and Internal Origin, most likely located at the same location.

The shared site origin position is set in the site model and represented by
the Survey Point. Then, each building model is positioned and the shared
coordinates are acquired from the site model.

Why would you use this Shared Site feature? The next pages will explain
the benefits.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 7

<!-- p. 8 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

BENEFIT #1: Spot coordinates refer to the same point on all
models

In the image below, we use the Spot Coordinate tool, located in the
Annotate tab. It will indicate the X/Y distance from a point to the Shared
Site Origin, which is represented by the Survey Point.

When the Shared Coordinates are spread among all the Revit files, the
spot coordinate tool can be used in any model and still refer to the same
origin point.

Be careful: there can be multiple types of Spot Coordinates. In the type
properties, make sure that the Coordinate Origin is set to Survey Point.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 8

<!-- p. 9 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

BENEFIT #2: Spot elevation refers to the same height on all
models

It is helpful to spot the elevation of a building element in relation to the
site. In the example below, we place the elevation value of the Shared Site
Origin (represented by the Survey Point) at Sea Level = 0. This way, we
can use the Spot Elevation tool to indicate the height of any element in
relation to the sea level. Spread the Shared Coordinates to all Revit files
and you’ll be able to use this feature accurately on any model.

Like with the Spot Coordinates tool, make sure to use Survey Point as the
Elevation Origin in the Spot Elevation type properties.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 9

<!-- p. 10 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

BENEFIT #3: Revit models and other external files can be linked
using “By Shared Coordinates” positioning

You can think of the Shared Coordinate system like a virus that spreads
around. The virus starts from the linked Revit site model. It then spreads
around to the architecture model, to the structure model, to the linked
CAD files, etc. Once the virus is fully spread, you can link any file together
and they will automatically position themselves if you use the Auto - By
Shared Coordinates positioning option.

Again, this positioning option only becomes available when the files have
been synced using Share or Publish Coordinates. That’s what you will learn
in the coming pages.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 10

<!-- p. 11 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

BENEFIT #4: The “True North” of a building can be adjusted in
the site model by using the rotation tool

All Revit projects contain two norths: first, the Project North, which is
used to orient view in a convenient way in relation to the sheets. The True
North represents the real north in relation to the site.

The most common way to set the True North value is to manually set a
rotation angle value between the True North and Project North. However,
there is a simpler way to do this: you can link your architecture project on
the Revit site model, rotate it and publish the coordinates.

When coordinates are shared, you can go back to the Architecture model
and adjust the Orientation parameter in the instance properties of a plan
view. Pick between Project North and True North.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 11

<!-- p. 12 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

THE DIFFERENCE BETWEEN SHARED COORDINATES
AND SHARED SITES

Shared Coordinates and Shared Sites are not the same thing. In the image
below, there is a site model and 2 instances of a building model. Each of
these files is using the same Shared Coordinate System. However, each
instance of the Revit building model has its own Shared Site. Basically, all
files have a common Survey Point but they also have their own personal
Project Base Point and Internal Origin.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 12

<!-- p. 13 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

12 STEPS TO CREATE SHARED SITES IN REVIT

REVIT PURE - © Copyright 2019 - BIM Pure Productions 13

<!-- p. 14 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

1- CREATE ARCHITECTURE MODEL, LOCATE INTERNAL
ORIGIN

The first step is to create the main architecture model. Orient the views
for convenience and ignore the True North for the moment.

Make sure to place the building in relation to the internal origin. Usually,
that means at the corner of your building, where two major grids might
intersect. Don’t mess up this step. You cannot relocate the internal origin
of the project.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 14

<!-- p. 15 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

2- LINK REVIT MODELS FROM ALL DISCIPLINES USING
“ORIGIN TO ORIGIN”

If you have MEP and Structure models ready, you can link all the Revit
files together. Use the Auto – Origin to Origin option. Always use this
option and you will never have positioning problems when linking multiple
disciplines. Don’t worry about shared coordinates for now.

3- CREATE SITE MODEL AND LINK CAD SURVEY DATA

Once you have the Survey Data from your civil engineer or surveyor in
hand, create a new Revit site model. Make sure the origin in the CAD file
containing the survey data is where it needs to be. In this example, we will
use a 2D CAD topo file, although sometimes you might receive 3D files.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 15

<!-- p. 16 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

In this surveyor DWG file, the origin (0,0) is located at the corner of the
property lines. This is the agreed location of the shared site origin. The
default Revit origins are all at the same spot. Then, use the Link CAD tool
and use Manual - Center positioning option. Click to place the DWG file.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 16

<!-- p. 17 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

Now, go to the manage tab, click on the Coordinates icon and select the
Acquire Coordinates tool.

Then, click on the CAD link. As you can see, the Survey Point of the Revit
site model is automatically moved to match the CAD file origin.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 17

<!-- p. 18 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

4- MODEL TOPOSURFACE USING CAD FILE

Now, let’s model the topography of the site using the Toposurface tool,
located in the Massing & Site tab. Click on the Create from Import tool
and select the CAD file. Select the correct CAD layer. In this case we
know it is layer TOPO.

Thousands of points will be automatically created. In this case, this is a 2D
CAD file, which means you still have to manually set the height of all the
points. Use the sea level information to set the proper height to the points
on each curved line.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 18

<!-- p. 19 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

5- SET SURVEY POINT TO ELEVATION = 0

In most cases, you want the Survey Point height to be set to level 0. This
way, you can use it to indicate the Sea Level elevation of any point. In
your Revit site model, go to any elevation and uncrop the view. Activate
the Survey Point visibility in the Visibility Graphics menu, under the Site
subcategory. Select the Survey Point and make sure it is clipped. Move it
to Level 0. Make sure you don’t modify the X/Y coordinates of the point.

Depending on how your Revit template is set up, the Survey Point might
already be set to Level 0. It should match the Internal Origin elevation.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 19

<!-- p. 20 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

6- LINK AND POSITION THE ARCHITECTURE MODEL

Use the Link Revit tool in the Insert tab. Select your architecture model
and use the Manual - Center positioning option.

Now, manually position the building on the site model.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 20

<!-- p. 21 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

7- ROTATE THE ARCHITECTURE MODEL IF NECESSARY

In page 11, we’ve talked about how you can set the True North of a project
using the rotation tool inside the site model. It is now time to rotate your
model if necessary.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 21

<!-- p. 22 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

8- ADJUST THE BUILDING VERTICAL POSITION

Go to an elevation view. Figure out what Sea Level elevation will match
the Level 1 of the architecture model. Create a new level in the site model
and call it “Building A.” In the example below, we know Level 1 = Sea Level
7600mm. Align and lock the architecture model Level 1 to this new level.
With this technique, adjusting the building height in relation to the site
becomes pretty easy.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 22

<!-- p. 23 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

9- PUBLISH COORDINATES TO ARCHITECTURE MODEL

You have linked an architecture model, properly positioned it on the site
and adjusted the rotation value. Now, it is time to Publish the coordinates
from the site model to the architecture model. Select the linked
architecture file. In the instance properties, you will find the Shared Site
parameter. Click on it.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 23

<!-- p. 24 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

When clicking Shared Site, here are all the options available to you:

In this case, you should pick the first option: you want to publish the
coordinates from the Site model to the Architecture model. Basically, this
will move the survey point in the house model to be in the same position as
the site model. The operation will only be complete once you close the site
model: you will be asked what to do with the linked house model position.
Select the first option.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 24

<!-- p. 25 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

It’s a good idea to verify if the publish coordinates tool worked as intended.
Open the architecture Revit model. Normally, the Survey Point has been
moved to reflect the position in the site model.

Try to set the view orientation to True North. It should match the north
you’ve set with the rotation tool in the site model.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 25

<!-- p. 26 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

10- OPTIONAL: CREATE MULTIPLE INSTANCES OF THE
SAME ARCHITECTURE MODEL

You can have multiple instances of the building on the same site. In the
Revit site model, copy and paste the building instance. Adjust the position,
both in plan view and in elevation.

Now, you have to create a new Shared Site. Click on the Shared Site
button in the instance properties of the linked model.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 26

<!-- p. 27 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

Use the Record current position... option and click on Change...

You now have access to the Site menu of the linked architecture model.
Click on Duplicate.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 27

<!-- p. 28 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

Enter a name for the new Shared Site. Click on OK.

To verify everything is correct, open the architecture file. Select the
Survey Point and click on the blue text Survey Point - Internal. There will
be a list of multiple sites. Select “Site 2” and click on Make Current. The
position of the Survey Point and the True North angle will be updated to
reflect the position you have set in the Site Model.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 28

<!-- p. 29 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

11- STRUCTURE AND MEP MODELS ACQUIRE
COORDINATES FROM ARCHITECTURE

Now, let’s acquire the coordinates from the Architecture model to the
Structure and MEP models.

In the example below, you are inside the structural model. The
Architecture model is already linked inside (using Origin to Origin
positioning option). Select the Architecture model and click on the
Shared Site parameter in the instance properties. This time, you have to
use the Acquire option instead of Publish. You want to acquire the shared
coordinates system of the Building-A architecture file.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 29

<!-- p. 30 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

12-LINK SITE MODEL INTO STRUCTURE AND MEP
MODELS USING “BY SHARED COORDINATES” OPTION

Congratulations, all the Revit models are now using the same Shared
Coordinate system! That means you can link any of these files together
using the Auto - By Shared Coordinates positioning option. In the image
below, you can see our Structural model with the linked site model.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 30

<!-- p. 31 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

SITES WITH MULTIPLE BUILDINGS

Sometimes, you might have a site that contains multiple buildings. The
workflow remains similar:

1- Create the architecture project.
2- Create a site model, set shared site origin and model toposurface.
3- Link the architecture model inside the site model.
4- Manually position the building inside the site.
5- Publish the coordinates from the site to the architecture model.
6- Spread the coordinates from the architecture file to the other
disciplines. Link all files together using Auto - By Shared Coordinates.

Repeat these steps for all buildings. Each building has a unique shared site.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 31

<!-- p. 32 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

BIM EXECUTION PLAN

When writing a BIM execution plan, you should list all the important
coordinate points and include a screen shot. Make sure to list the internal
origin, the project base point and the survey point of the linked site model
(if applicable). Make sure to also indicate the elevation values. It should
look like this:

PROJECT BASE POINT:
The project base point of the architecture model is located at the intersection
of grids A and 1.

INTERNAL ORIGIN:
The internal origin is also located at the intersection of grids A and 1,
intersecting in height with level 1.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 32

<!-- p. 33 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

SURVEY POINT:
The survey point of the linked Revit site model is located at the south-west
property line intersection. The elevation at height 0 refers to the sea level.

After setting up these coordinate points, they should be pinned and never
moved again.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 33

<!-- p. 34 -->

PAMPHLETS
ISSUE #14 / FALL 2019 / SHARED SITES

THANKS FOR READING!

As always, send your thoughts at nick@revitpure.com. I read and answer
all emails. Let me know if you loved or hated this pamphlet.

REVIT PURE PACKAGES

Did you like the simple, efficient style of this pamphlet? That means you
will love our learning packages! BASICS will help you learn all the essential
tools of Revit. Check it out at: revitpure.com/basics. DESIGN will teach
you how to create beautiful presentation documents using Revit. Check it
out at revitpure.com/design.

Both packages contain an eBook and video tutorials, but also bonus
content such as templates and Revit families. Use code learn to get 15%
off on any package.

REVIT PURE - © Copyright 2019 - BIM Pure Productions 34
