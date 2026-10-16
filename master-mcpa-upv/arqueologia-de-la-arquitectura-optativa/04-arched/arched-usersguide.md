---
type: libro
title: "ArchEd_UsersGuide"
author: "Barbara Reitgruber"
categoria: "Arqueología de la arquitectura (optativa)"
paginas: 28
extraccion: "texto"
fuente: "local:D:/UPV/MCPA/Asignaturas/Arqueología de la arquitectura (optativa)/04. ArchED/ArchEd_UsersGuide.pdf"
convertido: 2026-10-16
---

# ArchEd_UsersGuide

> Texto extraído de `Arqueología de la arquitectura (optativa)\04. ArchED\ArchEd_UsersGuide.pdf` (28 páginas, texto). El PDF original está en el disco D: (UPV\MCPA\Asignaturas); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

ArchEd
__________________________________________________________________________________________

ArchEd

A program for drawing Harris Matrices

Christoph Hundack
Petra Mutzel
Igor Pouchkarev
Barbara Reitgruber
Barbara Schuhmacher
Stefan Thome

__________________________________________________________________________________________

<!-- p. 2 -->

ArchEd Preface
__________________________________________________________________________________________

Preface:

This program was developed in part during the practical programming course “Automatic
graph drawing“ at the MPII, Saarbrücken, Germany.

This project will be contiune at the technical university of Vienna, Austria.

The authors want to thank I. Herzog and Prof. I. Scollar for their support, and C. Bridger,
A. Fuller (now British Museum), and S. Lütgert for supplying data.
Also we want to thank Prof. Peter Stadler, Prof. Wolfgang Neubauer (both from Vienna
Institute for Archaelogical Science) for their support, and David Bibby for his helpful
suggestions.

__________________________________________________________________________________________
2

<!-- p. 3 -->

ArchEd Contents
__________________________________________________________________________________________

Contents:

Overview......................................................................................................................... 4

The program Window...................................................................................................... 5

Your first Harris matrix with ArchEd............................................................................... 6

User Guide.......................................................................................................................8

A. Opening and saving of documents................................................................. 8

B. Input and Manipulation of Harris matrices...................................................... 11

C. Automatic Redrawing and its options..............................................................16

D. Printing functions and Page setup....................................................................18

E. Import / Export................................................................................................21

F. Other program functions...................................................................................23

G. Help functions..................................................................................................28

__________________________________________________________________________________________
3

<!-- p. 4 -->

ArchEd Overview
__________________________________________________________________________________________

Overview:

In the following parts of this manual we will use some special terms in order to describe how
to use ArchEd. For some users these expressions may not be clear, so we give a short
explanation of them here:

„Clicking“ means „pressing the left mouse button once“. Accordingly „double - clicking“
means „pressing the left mouse button twice (with a very short delay between the two clicks)“
and „Right - clicking“ is the same as „pressing the right mouse button once“.

__________________________________________________________________________________________
4

<!-- p. 5 -->

ArchEd The program window
__________________________________________________________________________________________

The program window:

Starting ArchEd, you see the window below. An empty default document is opened, called
Harris1. In order to work with a Harris-Matrix diagram either you choose to use this
document in case you want to create a new diagram or you open an existing document.

Name of document Menubar
Toolbar

Layout area
Statusbar Scrollbars

__________________________________________________________________________________________
5

<!-- p. 6 -->

ArchEd Your first Harris matrix with
ArchEd
__________________________________________________________________________________________
Creating your first Harris matrix with ArchEd:

In the precedent chapters you have already seen how to install and start ArchEd. Now let’s
see how a Harris matrix can be created. You have already seen the program window before. If
you don’t understand one of the following terms, please have a look at the preceding chapters
to get information about it.

A Harris matrix mainly consists of two elements: The strata and the relations between them.
In ArchEd both of them can be created easily.

In order to create a stratum click at in the Toolbar.

Now you see that the cursor’s shape has changed. Point this cursor to the position in the
Layout area where you want the new stratum to be placed. Then simply click there and you
will notice that the stratum has been created. You can now go on entering strata (notice that
the cursor hasn’t changed its shape) and should do so two or three times in order to be able to
follow the next steps.

To stop creating strata, click in the Toolbar.

Now the cursor changes back to its standard shape and you are allowed to choose a different
menu or button again.

In the next step we are going to add some relations to our Harris matrix.

To do so click at in the Toolbar.

Now a new window opens:

You see two lists of strata. In the middle of the window you see all types of relations that can
be created. To create a relation between two strata just choose the first respective stratum in
the left list. Then choose the second stratum in the right list and finally the type of relation
you want to create between them. In our example choose „Stratum #1“ in the left list and then
„Stratum #2“ in the right list. Clicking at „is later than“ and then „OK“ creates the relation
„Stratum #1“ is later than (i.e. is above) „Stratum #2“ and closes the window. Choosing
„APPLY“ instead of „OK“ would have created the same relation leaving the „Create relation“
window active waiting for more relations to be created.
If you aren’t satisfied with your Harris matrix you can of course change its look:
__________________________________________________________________________________________
6

<!-- p. 7 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

• To move a stratum click at the stratum you want to move and keep the mouse button
pressed. Then drag the stratum to the desired position and release the mouse button. The
relations of this stratum are dragged to the new position automatically.

Relations can also be moved:
• To move a relation click at the relation you want to move and hold the mouse button
down. Then drag it to the desired position and release the mouse button. Relations that lead
over several levels consist of several segments, one segment for every level they are leading
through. Notice that you cannot move a relation’s segment to a different level.

The strata’s labels can be changed easily: Just double-click at the respective stratum and its
property sheet opens. Double-clicking at the Stratum’s label there allows you to enter a new
label.

Of course that’s not all you can do with ArchEd. If you want to learn more about ArchEd’s
capabilities you should read the next chapters as well. There we will show you how to open
and to save documents, how to import data from other programs and many other things you
can do with ArchEd.

__________________________________________________________________________________________
7

<!-- p. 8 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

User Guide

Generally ArchEd offers two bars to interact with the program.
The program can be completely controlled via the Menubar. For frequently used options there
are buttons in the Toolbar.

The Menubar:

The Menubar consists of five main menus. Each menu opens by clicking it or by pressing
„CTRL” together with the respective underlined letter. For example, pressing „CTRL”
together with „F“ on the keyboard opens the File menu.

The Toolbar:

The Toolbar consists of seventeen buttons, each of them activated by simply clicking it.

A. Opening and saving of documents:

Whether you are opening an existing document or creating a new one, this document always
becomes the „active” document. This means that this document receives all your commands
until you click at another opened document window to set this one to „active” or you open
another document.

As soon as ArchEd has been started, a new empty document is opened, called „Harris1“.
You now have two options: Either create a new Harris Matrix using this new document ( and
give it another name by saving it later) or open a previously saved document.

To open a document click at in the Toolbar or at „OPEN“ in the File-menu.

Both alternatives will result in starting the „OPEN“- window. There you can select the path
and the name of the document you want to open. By default, this window only lists files with
the “_.hm” - extension. Other files are listed by selecting “All Files” instead of the “_.hm” -
extension.
A document is always opened in a separate window.

Selected folder
__________________________________________________________________________________________
8

<!-- p. 9 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

Name of the document you
want to open

In the „OPEN“- window select the folder where the desired document can be found and
double-click at the document you want to open.

In case you need a new empty document to work with, select in the Toolbar
or „NEW“ in the File-menu. The new document is called “Harris_X” by default, “X” being a
number.

When you have finished the work with your document, saving it is as easy as opening a
document. You can click at „CLOSE“ in the File-menu. This closes the „active” document. In
case you did not save this document before, you are prompted as to whether you want to save
it or not.

To save a document directly click at in the Toolbar or at „SAVE“ in the File-menu.
In case the document you want to save has not been saved before, a window is opened where
you can give a destination path and a name for the file you want to save.
If the document you want to save has been opened before in the current path, it is saved at the
same place under its previous name. For a document that still has its default name, which was
given to it when it was generated, the program asks you to insert the path and name under
which the file will be saved.

If you want to save your document under a different name click at „SAVE AS“ in the File-menu.
A window similar to the one below is opened where you can give a destination path and a
name for the file you want to save.
All the files you save have the extension “_.hm” by default. If desired this can be changed for your
file when you type the name together with the new extension in the “Save As”-window.

__________________________________________________________________________________________
9

<!-- p. 10 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

Current folder

Here you change
the name of your
document

B. Input and Manipulation of Harris Matrices

Entering strata:

The most simple way to add strata is to click at in the Toolbar. You can also select
„STRATUM“ and then „ADD“ in the Layout-menu.

This will change the shape of the cursor to . You can now place a stratum by simply
clicking to the desired position in the layout area.
After you have placed a stratum you will notice that the cursor doesn’t change its shape. This
indicates that you can go on placing strata. In case you want to place some more strata you
don’t need to enter this „strata adding mode“ again as long as you have not left it.

To leave this mode click at in the Toolbar, press the ESC - key on the keyboard or click
at „SELECT“ in the Layout-menu.

New:

If you want to draw a surface you have to click at in the Toolbar, or you can select
“SURFACE” and after that “ADD” in the Layout-menu. Everything you do with a stratum
you can do it with a surface also on the same way.

Selecting a stratum:
A stratum is selected by clicking (not double-clicking!) on it. The stratum will change its
color to indicate this. Selecting a stratum is useful if you want to delete it or you want ot
create a relation with the selected relation as a part of it.

__________________________________________________________________________________________
10

<!-- p. 11 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

Entering relations:

There are two ways to add relations to a Harris Matrix. In the first case you select one of the
two strata that shall take part in this relation. In the second case you directly click at in
the Toolbar or select „RELATION“ and then „ADD“ in the Layout menu.
Note that you cannot select this option until at least two strata exist.
Now a window opens:
On the left side and the right side respectively, there are lists of all existing strata.
If the lists are longer than the space in the window, you can use the scrollbars to find the
desired stratum.

In the middle of the window you can see four types of relations:
− is later than
− is earlier than
− is contemporary with
− is equal with

Generating a relation between two strata is very simple:
In each list you choose the stratum participating in the relation and the type of relation you
want to create between them. In case you selected a stratum before, you can see that this
stratum is already selected in the left list. The relations are created as you read them in the
window :
Let’s say you want to create a relation „Stratum1 is later than Stratum2“. In the left list you
choose the stratum „Stratum1“ and in the right list the stratum „Stratum2“. Now click „is later
than“ in the middle of the window. (If you had chosen „Stratum2“ in the left list and
„Stratum1“ in the right list together with „is later than“, you would have created the relation
„Stratum2 is later than Stratum1“).Now you can choose „OK“ in the lower part of the
window. The window closes and you can see the new relation in the Layout. If you choose
„Apply“ instead of „OK“, the relation is generated and the window remains visible, waiting
for the next relation to be inserted. Clicking the „Cancel“- button will close the window
without generating a new relation.

Lists of strata

Relation types

__________________________________________________________________________________________
11

<!-- p. 12 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

Selecting a relation:

Only „later / earlier“ – relations can be selected. You can do this by clicking at the respective
relation in the Layout area. Selecting a relation is useful if you want to delete this relation.

Deleting a stratum:

In order to delete a stratum click at the respective stratum in the Layout
area. Then press the DEL – key on the keyboard or select „STRATUM“
and then „DELETE“ in the Layout menu.
The stratum and all relations connected to it will be deleted from the Harris Matrix.

Deleting a relation:

The way you delete relations depends upon the kind of relation. Relations of the „later /
earlier“ – type can be selected as mentioned above. Then press the DEL – key on the
keyboard or select „RELATION“ and then „DELETE“ in the Layout menu.
Equal relations are deleted by double-clicking at the respective set of equal strata. A window
similar to the following opens:

Select the stratum you wish to delete here

__________________________________________________________________________________________
12

<!-- p. 13 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

Select the label of the stratum you want to delete in the list and click at the „REMOVE
FROM EQUAL SET“ button.
Now another small window opens. There you can decide which relation (from the original set
of relations of this set of equal strata) shall belong to the stratum you are going to remove
now.

Name of the stratum you are
going to remove

Lists of strata

The splitted stratum will receive all those relations listed in this window. In case there are
relations listed you do not want for the splitted stratum just click at the respective relation and
press „DEL“ on the keyboard. The relation will be deleted from the list.

Strata belonging to contemporary relations are assigned with a small number at the right of
their label. To delete a stratum from a contemporary relation double-click at the right part of
the respective stratum. A window similar to the following opens:

List of strata
belonging to this
contemporary
relation

__________________________________________________________________________________________
13

<!-- p. 14 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

Now select the stratum you wish to delete from the list by clicking at it and then clicking at
„DELETE STRATUM“. You can also delete the contemporary relations for all strata listed
by clicking at „DELETE ALL STRATA“. Finally click at „OK“ for your changes to take
effect.

Moving a stratum:

To move a stratum around in the Layout area click on it and keep the mouse button pressed.
Then drag the stratum to the desired position and release the mouse button. Note that all
relations belonging to this stratum are also moved. If you try to position a stratum in a place
that is already occupied, the program will try move the other objets out of the way.

Moving a relation:

Moving a relation works in a similar way to the moving of strata: Click at the desired relation
and hold the mouse button pressed until you release it at the desired position. Note that only
relations of the „later / earlier“-type can be moved.

Showing the properties of a stratum:

Double-clicking on a stratum or selecting a stratum followed by clicking at „STRATUM“ and
then „PROPERTIES“ in the Layout menu will open the stratum’s property sheet:

The label (=name) of this
stratum Enter any comments
about this stratum here

Adjust the
stratum’s
shape by
dragging
these scroll-
buttons

These lists contain all
__________________________________________________________________________________________strata related directly
to this stratum14

<!-- p. 15 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

In this window you can change the label as well as any comments about the respective
stratum by simply double-clicking at the respective area and then entering the new text. The
three lists in the middle of the window only serve information purposes: You cannot change
the relations shown there by clicking there. This window also allows to change the shape of
the respective stratum. To do so, click at on of the two small scrollbuttons in the upper right
corner, keep the mouse button pressed, move the scrollbutton to the desired position and
release the mouse button.You can also change the stratum’s shape by dragging the small blue
point. Moving this blue point combines the moves of both scrollbuttons and thus simplifies
the changing of the stratum’s shape.
All changes in this window must be confirmed by finally clicking at „OK“ . Clicking at
„Cancel“ closes the window discarding any edits.

Undo / Redo of actions:

While you are working with a Harris Matrix you don’t need to be worried about making
mistakes. ArchEd provides an undo / redo function that allows you to reinstall the original
state of your drawing easily in case you made a mistake. These undo / redo functions of the
program work like the usual undo / redo functions:

Each time you click at the program goes one step back in the list of committed
operations.

Each time you click at the program goes one step forward in the list of committed
operations.

(Notice that „Undo” of a „Generate Drawing”- operation is impossible.)

Instead of using the Toolbar buttons mentioned above, you can also select „UNDO“ or
„REDO“ in the layout menu.

__________________________________________________________________________________________
15

<!-- p. 16 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

C. Automatic Redrawing and its options

In course of the creation of a Harris Matrix you will probably notice that, as your drawing
grows larger, it becomes more and more difficult to keep the drawing easily readable. Of
course you could move objects around manually, but especially for large Harris Matrices this
is getting diffcult. For this case ArchEd provides a function, called „Automatic Redrawing“
which can be executed how often you want at any stage of your work.

To start an automatic redrawing click at in the Toolbar or select “GENERATE” in the
Layout menu.

The program uses several algorithms to place the strata on the appropriate levels, minimize
the crossings of the relations, eliminate redundant relations, and draw the Harris Matrix
nicely.
Depending on your computer, the computation of larger Harris-Matrices (more than ~1000
strata) may take some time.

The redrawing process can be influenced by clicking at „SETTINGS“ in the Layout menu.
A window opens where you can select from three options:

„Later / Earlier Relations“:

ArchEd uses heuristics to calculate the strata’s positions in a way that reduces the crossings
between the relations. By moving the small button in the upper left part of this window to the
left or right you can decrease or increase the number of executions of these heuristics when
doing an automatic redraw. Generally more executions show a better result (i.e. less
crossings) but take a longer time to compute. By clicking at „SETTINGS“ you can tell
ArchEd which heuristic shall be used in which „run“. Additionally you can decide to reduce

__________________________________________________________________________________________
16

<!-- p. 17 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

excess relations or to merge relations by checking the appropriate boxes. Reducing execess
relations means that some relations that are already implicitly given by existing relations are
deleted from the drawing. Activating this option may strongly increase the drawing’s
readabilty. Merging edges means that the way the relations are drawn is changed: ArchEd
tries to use as many common lines for the relations as possible, whereas normally each
relation consists of lines „of its own“.
Clicking at „SET DEFAULTS“ resets all settings in this window to its standard values.
As you change the settings you will notice that an preview drawing in the right part of the
window shows how your changes will affect the looking of your drawing.

After clicking at the „Strata Placement“ tab the following window will open:

By selecting either „down“ or „down-top“ you can decide in which direction the redrawing
algorithm goes through the drawing. „Down“ starts at the top of the drawing and runs to its
bottom whereas „down-top“ starts in the same way but aditionally runs back to the top of the
drawing. The small preview-window will show an example how these changes may influence
your drawing.

In the section „Vertical placement of strata“ you can decide how many empty intermediate
levels shall be inserted between every level. Additonally you can adjust the height of the
levels with respect to the strata height and the minimum and maximum numbers of strata in
each level.
Again, all these options will be used for the next redrawing only if you leave this window by
clicking at „OK“. Clicking at „CANCEL“ will close this window and discard any edits.

The „Numbering of Strata“ window will be explained in part F. of this manual, since this
window doesn’t belong to the „automatic redrawing“ topic.

__________________________________________________________________________________________
17

<!-- p. 18 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

D. Printing functions and Page Setup:

Print Setup:

ArchEd provides several functions that help you to print your drawings. First of all, you can
set up your printer in a Windows-standard manner, depending on the connected printer(s). To
do this click at „PRINT SETUP..“ in the File menu. A window will open where you can
change the printer options.

Print Preview:

Before printing, you can get an impression of the printout’s looking by clicking
or by selecting „PRINT PREVIEW“ in the File menu:
The pages of your document are shown in the same way as they will be printed.
You can change between the different pages of your printing, zoom in or zoom out to inspect
the printings and print them on paper by clicking on the respective buttons.

Header

Footer

__________________________________________________________________________________________
18

<!-- p. 19 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

Printing:

To print a document just click at in the Toolbar or click at „PRINT“ in the File menu.

Page Setup:

By clicking at „PAGE SETUP“ in the File menu, a window is opened where you can choose
between two tabs. The first tab „Margins“ allows you to set the margins and the indents for
printing your document. In the center of the window a preview sheet shows the effects of your
changes. Additonally you can select whether you want to center the drawings horizontally /
vertically by checking the appropriate boxes.

__________________________________________________________________________________________
19

<!-- p. 20 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

By selecting the tab “Header / Footer” you open a window where you can add some
information to your printing ( in a row at the top or the bottom of the page, called “header” or
“footer” ). By clicking on the button to the right of the text line, you can add additional
information ( the current date and time, the page number, the total number of pages or the
name of the diagram) to the respective part of the sheet. By selecting „#A“ you can change
the font and font size for the respective part. The three buttons to the right of „#A“ let you
select where to align the text of the header or footer respectively. (Align left, Center or Align
right)
A sample at the top and the bottom of the window will show the effects of your changes.

The „Header / Footer“ tab as well as the „Margins“ tab contain a „PRINT“ button and a
„PRINT PREVIEW“ button which have the same effect as the respective buttons mentioned
above.
Again, clicking at „OK“ will make the program to accept your changes whereas clicking at
„Cancel“ will close the window and discard any changes.

__________________________________________________________________________________________
20

<!-- p. 21 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

E. Import / Export:

IMPORT:

This feature allows you to open documents which have been created by other programs.
File formats of the following programs are supported:

• The Bonn Harris Matrix program, which is part of the WinBasp package ( extension:
“_.lst” or “_.LST”). This format saves the drawing in ASCII format, so changes can be
made via a text editor.

The Import window works similiarly to the Open window mentioned above. By selecting the
file extension, you decide which kind of document you want to import. The window shows
you all documents in the present folder with the selected extension. You open the desired
document by double-clicking it.

Current folder

Name of the document you
Select the file extensions have selected
here

__________________________________________________________________________________________
21

<!-- p. 22 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

EXPORT:

Opposite to the Import function, this function allows you to save your documents in one of
the following formats:

• The List format of the Bonn Harris Matrix program, which is part of the WinBasp
package
( extension: „_.lst” )
• The Windows metafile format and the Enhanced metafile format (extensions: „_.wmf“ or
„_.emf“). These formats can be used to export Harris Matrices to MSWord for example.
• The Bitmap format (in this case a 24-bit Bitmap format) (extension „_.bmp“). Use this
format to export HarrisMatrices to graphic editors as MSPaint or CorelDraw for example.

Again you select the desired format by choosing the respective extension. Apart from this, the
Export window works in the same way as the Save window mentioned above.

__________________________________________________________________________________________
22

<!-- p. 23 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

F. Other program functions:

Changing Colors:

By clicking at „SET COLORS“ in the View menu the following window opens:

Categories of elements Items in the present category

Here you can see a
preview of your changes

Click here to reset all
colours to their
default values

Select the color for the
selected item here

Preview window

You can change the colors of all elements of a Harris-Matrix here. Just select the category and
the item you want to change. Then you select a new color for this item by simply clicking the
desired color. A preview window shows the effects of your changes.

__________________________________________________________________________________________
23

<!-- p. 24 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

Numbering of strata:

This window allows you to specify the way strata are labeled by the program. In order to open
it, select „SETTINGS“ in the View menu and then click at the „Numbering of strata“- tab. Of
course you can change the label of every stratum by double-clicking it. But any new stratum
will have the label specified here at the time it is created. You can also insert a default
comment for your strata. On the right you can see two selection buttons. These buttons let you
choose the kind of label / comment that is inserted (date and / or time for example). If you
choose to number the strata, you can give a start value as well as a step value which indicates
the difference between the numbers of two consecutive strata. The SET DEFAULTS button
sets all options back to their default values, which means that strata are labelled by numbers
and there are no default comments. You can insert static text as label / comment by simply
clicking the respective area and typing the desired text there.

Enter label / comment here Selection buttons

Enter the start value for
Enter the size of the steps your numbering here
between the numbers here

Setting the fonts used in the drawing:

__________________________________________________________________________________________
24

<!-- p. 25 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

To set the font and the font style used for the labels, comments, etc. of the drawing, click at
„SET FONT“ in the View menu. The options in this window are self-explanatory. A small
sample will show the effects of your changes. If you are satisfied with the settings, click at
„OK“ to leave this window. Clicking at „Cancel“ will leave the window and discard any
changes.

Zooming functions:

Especially for large Harris matrices it might be useful to see larger parts of the matrix or even
the whole drawing at one glance. Arched provides functions for both cases:

You can zoom in or zoom out your drawing by clicking or .

(Alternatively you can click at „ZOOM IN“ / „ZOOM OUT“ in the View menu.)

This way you can either inspect some details of the drawing or get an overview of large parts
of the diagram.
If you want to see more of your drawing at one glance, click at „NAVIGATE“ in the View
menu.

__________________________________________________________________________________________
25

<!-- p. 26 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

This opens a small window that shows the whole drawing together with a red frame that
indicates the part of the diagram displayed on the layout area. This frame can be moved over
the drawing in order to display other parts of the diagram on the layout area.

Frame

Finding objects:

Another small but helpful function that may increase the readabilty of your drawing is the
grid shown in the Layout area. You can toggle it on / off by clicking at „GRID“ in the View
menu.

In case you need to find a special stratum or relation in your diagram, click at „FIND“ in the
Layout menu. A window is opened where you select the stratum or the relation respectively.
After clicking at “Find Next” the layout area is scrolled to the position of the desired object
and the object is highlighted in a different color.

Select here from which
and to which stratum the
relation, you are looking
for, is leading.

Select here whether you want to
find a stratum or a relation

__________________________________________________________________________________________
26

<!-- p. 27 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

Toolbar / Statusbar:

By default the Toolbar and the Statusbar are shown on the screen. In case you want to enlarge
the space for your drawing on the screen you can toggle both bars on / off by clicking at
„TOOLBAR“ / „STATUSBAR“ in the View menu.
Marking the direction of later / earlier relations:

Usually, two strata that are related to each other with a later / earlier relation are connected by
a simple line in the drawing. The later stratum is drawn on a higher level than the earlier one.
This assignment to the correct levels is done by an automatic redraw. However while creating
a Harris matrix manually such a correct level assignment is not necessarily given which
means that it is not always clear in which direction each later / earlier relation goes. To avoid
such possible errors click at „RELATION DIRECTION“ in the View menu. If this option is
switched on a small black rectangle will be drawn at the one end of each later / earlier relation
that touches the earlier stratum.

Switching between orthogonal and direct line drawing mode:

Many users of ArchEd find it more convenient to draw the relation lines in a manner that only
rectngular bends are allowed. To toggle between this mode and the default direct line drawing
mode, click at „ORTHOGONAL“ in the View menu.

Arranging the document windows:

As it is usual for many windows programs, the document windows can be arranged in
different ways.
By clicking at „NEW WINDOW“ in the Window menu a new window for the “active”
document is opened. All changes made in one of the windows of a document are executed as
well in all other windows of this document to keep consistency.
Clicking at „CASCADE“ in the Window menu arranges all document windows such that they
overlap whereas selecting „TILE“ arranges all document windows as non-overlapping tiles.
Finally, clicking at „ARRANGE ICONS“results in arranging all minimized windows in a row
at the bottom of the program window.

__________________________________________________________________________________________
27

<!-- p. 28 -->

ArchEd Your first Harris Matrix with ArchEd
__________________________________________________________________________________________

G. Help functions:

In the case any questons arise while using ArchEd, the program contains several help
functions. In order to read more about this, click at „USING HELP“ in the Help menu. An
introduction of ArchEd’s Help system will be shown.

The easiest way to get help is often to click at the screen element you want to know more
about and then to press F1 on the keyboard. For those screen elements that cannot be selected
by clicking at them, you should try to right-click at them. Then a small window named
„What’s this“ will open und you should select it by clicking it. In both cases, ArchEd will
open a help file related to the momentariliy used function. But as this way of getting help is in
some cases not sufficient, there are some more possibilites for getting help:

In case you need help about a special topic you have two options to get more information:

Click at „INDEX“ in the Help menu and a window opens where you enter topics for which
you need help. The program then shows keywords related to the desired topic and you can
select from the alternatives shown.

Another possibilty is to click at or at „HELP TOPICS“ in the Help menu which opens the
complete list of help keywords from which you can select the needed topic.

If you click at and then select an element of the program window, you will get more
information about the selected element.

Clicking at or at „ABOUT“ in the Help menu will show some information on the program
eg, the version number.

__________________________________________________________________________________________
28
