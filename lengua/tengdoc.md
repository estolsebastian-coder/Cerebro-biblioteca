---
type: libro
title: "tengdoc"
author: ""
categoria: "Lengua"
paginas: 8
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Libros/pdf´s mezclados/tengdoc.pdf"
convertido: 2026-10-16
---

# tengdoc

> Texto extraído de `pdf´s mezclados/tengdoc.pdf` (8 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Libros); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

T ~gTEX: TEX Spells for Typesetting in Tengwar
User's Manual
Version 1.10

Ivan A Derzhanski

22 September 2000

1 Introduction
This document describes the use of T ~gTEX (tengtex.tex and tengtex.sty)
for the TEX / LATEX / LATEX 2" typesetting of text in the languages of Middleearth in Feanorian tengwar, using my Computer Modern Tengwar family, its
variant Computer Roman Tengwar, the fount teng10 by Julian C Brad eld or
the revised fount tengwar by Michael P Urban (or any combination of these).1
Perhaps it is worth reminding that the name TEX is derived from the
Greek word tekhne `art', which (along with the Latin tex o `weave',
textum `web, fabric, texture', textus `text') goes back to the Proto-
Indo-European root *teks - `create, frame, carve', no doubt from a
Lemberin cognate of the Proto-Eldarin base tek- `write' (The Lost
Road:391), whence also Quenya ° `writes', Sindarin ´¢ `write!'.

The input of T ~gTEX is essentially an asciisation of the R omenorean spelling
adopted by J R R Tolkien and described in Section i of Appendix E to The Lord
of the Rings. (One di erence is that capital letters are used for increasing the
total number of letters available for the input, instead of singling out sentenceinitial words and proper names, a device which is not a regular feature of the
Feanorian script2; another is that no accent marks are used, because of the
limitations of ascii.) Its output strives to follow the orthographic conventions
of the Third Age, discussed in Section ii of the same Appendix and illustrated
Inspiration has been drawn from the package ArabTEX by Klaus Lagally. I give thanks to
Emanuele Vicentini, Gernot Katzer, Dirk Thierbach and Michael Urban for their comments
and cooperation.
1This document uses Computer Modern Tengwar by default. To substitute Computer
Roman Tengwar, J Brad eld's or M Urban's tengwar, uncomment line 18, 19 or 20 of the
source, then recompile it.
2Large ornate initials do occur in some documents, but are used very inconsistently.

1

<!-- p. 2 -->

in the few surviving samples of text in tengwar3; on those occasions on which
the sources disagree, the evidence from the corpus takes precedence over the
description in the Appendix. In its current version T ~gTEX is intended for processing text in Quenya, Sindarin and their close relatives, and it also provides
some support for Westron and the Black Speech, but not for any other languages, although it may work by accident for some post-Third Age Mannish
tongues (such as Irish in Sindarin mode).
T~gTEX is not copyrighted, but its use is protected by an oath, the text
of which (in English and Quenya) is to be found in the le vanda.tex in this
distribution.

2 Generalia
To activate T ~gTEX, load it by \input tengtex into a TEX source le, include
the option tengtex into the document header of a LATEX document or instruct
LATEX 2" to \usepackage{tengtex}.
The fount used is selected by one of the spells \cmteng (Computer Modern Tengwar, the default option), \crteng (Computer Roman Tengwar), \jcb
(J Brad eld's teng10) and \mpu (M Urban's tengwar). Tengwar can be magni-
ed by the spell \tengwarmag (with one argument; the default is 0). The chosen
magni cation is activated when you next select a fount.
Three major modes are available: Quenya, Classical Sindarin and Beleriandic Sindarin. The appropriate mode is selected by the spells \quenya, \sindarin
and \beleriand (there is no default mode). There are also certain options
within each of the modes, described in the dedicated sections.
The typesetting of text in tengwar, particularly of longer passages, is done by
the environment elvish. For the inclusion of short quotations in tengwar into
text written in other scripts the macro \quetta is also available.4 An Elvish environment, but not an Elvish quotation, may consist of two or more paragraphs
separated by blank lines.
In an Elvish environment or quotation continuous strings of letters (in the
TEX sense) are recognised as words and written in tengwar in the output, following the orthographic conventions of the mode (and ignoring letters to which
a value is not assigned); continuous strings of decimal digits are recognised as
numbers, and are inverted in the output.5 Numbers may form part of words.
Sauron ataltane 3019sse. ¢ïà¥; â; ¥ 9103 ë.
[Quenya] `Sauron fell in 3019.'
3One of these sources, Aragorn's letter to Master Samwise, is in fact an early Fourth
Age document, but it can be taken as representative of Third Age Sindarin writing, since
it was during the Third Age that the author received his Elvish education.|Some archaic
(pre-Third Age) conventions, in particular regarding Quenya, are also supported.
4All the macro does is send its parameter to the environment for processing; it thus uses
more of TEX's memory, but it is shorter to type.
5Numbers are not explicitly marked as such with a dot or line above them, since the
numerals in the founts are already su ciently distinct from tengwar, in any case more so than
a dot would be from an overdot tehta.

2

<!-- p. 3 -->

Any other characters (such as punctuation marks), blank space and TEX, LATEX
or T ~gTEX parameterless commands are let through unchanged, and it is the
user's responsibility to ensure that their visible e ect, if any, makes sense in
the chosen fount (for example, because of the way the character code tables are
organised, a hyphen yields a tengwa number 11 in J Brad eld's fount and a
wavy dash in M Urban's and in Computer Modern Tengwar). Empty pairs of
curly brackets can be used to break ligatures, as they make T ~gTEX think that
the word ends there and a new one begins.

3 Computer Modern Tengwar

The Computer Modern Tengwar family (included in this distribution) is to
Computer Modern Roman as the tengwar themselves are to the medi val AngloSaxon and Celtic calligraphic Roman hands that were their Primary World
prototype. Just as Computer Modern Roman is TEX's default fount family, the
Computer Modern Tengwar are now T ~gTEX's native accent.
I made this family with several purposes. First, I expect it to help us see
the tengwar with the eyes of a European of old (such as Ottor W fre the
mariner, named Eriol in Tol Eressea), to whom they would not have appeared
archaic, only di erent in the use, but not the style, of eminently familiar graphic
elements.
Second, chances are that those who wish to use the tengwar for large-scale
writing will need a wider variety of sizes and styles. Within this family counterparts of all Computer Modern and Concrete Roman typefaces can be generated
and used. (Support for their selection has not been included in the package at
this stage, but it can be added easily enough if the idea proves popular. In the
meantime users are encouraged to experiment.)
Third, it blends better with surrounding text in Roman (so well, in fact,
that I have found it necessary to underline all inclusions in tengwar in this
document), which may be an advantage in some situations.
And fourth, there now is a fount that I can make T ~gTEX's default, without
having to give priority to either J Brad eld's or M Urban's.

4 Computer Roman Tengwar

The Computer Roman Tengwar family endeavours an even more radical move in
the same direction as Computer Modern Tengwar: on top of the modernisation
of the entire character set it performs a further degree of romanisation of the
primary tengwar (the secondary ones are not altered). Needless to say, it blends
even better with Roman text.
Although it claims to be a separate family, in reality it uses the same
typefaces as Computer Modern Tengwar, only di erent parts of them.

3

<!-- p. 4 -->

5 Quenya
5.1 Vowels
In Quenya mode you have the option of choosing between heavy (default)
and light vocalisation, using the words \heavyvocalise and \lightvocalise
for switching back and forth.
Short vowels are written as tehtar over the preceding consonant or (when
syllable-initial) over a short carrier. When light vocalisation (a glimpse of which
is to be seen in J R R Tolkien, Life and Legend (Catalogue of the Bodleian
Library Exhibition, Oxford, 1992), Plate 218) is selected, the tehta for a is
not written, but all tengwar standing for syllable- nal consonants receive a
subscript dot tehta (falmar `waves', for example, is set as ªâ;¤; if vocalised
lightly and ^ªâ^¤ if vocalised heavily).
Long vowels can be either doubled in the input, and then the tehta is also
doubled (yeen }´¥ `year', mool "â `slave, thrall', uur $¤ ` re'; note that this
only works with e, o and u), or capitalised, and then the single tehta is written
over a long carrier (yAr ´^¤ `blood').
Diphthongs with i as second element are written as yanta bearing the tehta
for the rst element (oire îà `everlasting age'). Diphthongs with u as second
element are written as ure bearing the tehta for the rst element (leuke â ï °
\`snake').

5.2 Consonants
The following consonants and consonant clusters are available:
c, k ° f ª G ´ h ì hl â
hr ¤ ht ² hw º H ² l â
lb â© ld ã m mb © mp «
n ¥ nc, nk ³ nd ¡ ng ± ngw ¹
nq, nqu » nt £ N µ Nw ½
p ¨ q, qu ¸ r ¤ rd á
s è ss ê S ¢ t
v ¬ w ¼ x ° y ´ z ê
Double consonants are written with an underbar tehta (quetta ¸ 6 `word',
tyelle â `grade'). The only exception is ss, which is written as esse (Gassa
´ê `hole, opening, mouth').
G, H, S,
N, Nw yield tengwar which had lost their original phonetic values by the Third
Age. They are meant for writers concerned with etymology (Galda ´ã
\`tree', HOn ² ¥; `heart', Noola "µâ `wise, learned', Sinde _¢¡ `grey').7
6The examples in this section are vocalised lightly.
7The rst notation is suggested by the fact that Proto-Eldarin g, preserved in Sindarin,
became zero in Quenya, presumably going through a stage where it was an approximant, such

4

<!-- p. 5 -->

q may be used without the following u, so both quetta and qetta yield ¸ .
r is written as r omen when followed by a vowel or by y (rOmen à ¥; `east',
hrIve à_ ¬ `winter', kirya _°à `ship') and as ore elsewhere (kirkar _°¤; °¤;
\`sickles').

R is always written as ore (ORe ¤ `heart, inner mind').

s is written as an underhook tehta when following another consonant (otso
\`seven', aksa ° `ravine', norsa ¥¤ `giant').

y is written as an under-di resis tehta when following another consonant
(Nwalya ½â `torment').

When silme and esse bear a tehta for a following vowel, their nuquerna shapes
are automatically substituted (silme _éâ; `starlight', esse ë `name').

5.3 An illustration
Galadriel's lament in L orien
(From The Road Goes Ever On.)
^î! â^ï_à ^â ^£¤ ^â_ë è' _à¥¥, }´_¥ ' ¥ _ ¬ à^^¤ ^^ãà¥!. ´ _¥ ¬ _â£ '´^ã¤ ^¬^_¥ ¤ _
à^_á _â ë,_'à¬ à^¬,^¡' ¥ ¨^â , ^¬ á 'â ^¤ '¥ â'î_¥ ^´ë¥ _ _£^â¤ _ â_¥ ^ à ^îà ^_à,â_ _à¥¥.
è_ ^¥ _ '´â ^ _¥¥ ^»'£^¬?.
^¥ è_ _ ^£â ^¬^á î âë ¬ ^ª^¥¤ ^^à â£^_à ¤^ ¥, ^¤ _â _ ¤ ''¡â^¬ 'â'©â; ^¤
_é^¡¥ _à â °^î^ ¤_¥ _ ^ªâ^_â^¥¤ _© , ^¤ ì_ _é ' £' ^¨ ^°^â_°à _ _à î^â. è_ ^¬¥^¼ ¥^,
à â ^¬¥^¼, ^¬_â^¤!.
^¥^_à ! ¥^î _ì'à^¬â ^¬_â^¤. ¥^î â _ì'à^¬. ^¥^_à !.

6 Sindarin
6.1 Vowels
Short vowels are written as tehtar over the following consonant or (when none
follows) over a short carrier. By default o is written as a curl open to the right
and u as a curl open to the left, but their r^oles can be swapped by specifying \oleft (Black Speech uruk à¸ `great soldier-orc, Uruk-hai') and restored
by specifying \oright.
Long vowels can be either doubled in the input, and then the tehta is also
doubled (eel }â `star', too " `thither', uur $¤ ` re'; note that this only works
with e, o and u), or capitalised, and then the single tehta is written over a long
carrier (Ar ^¤ `king, chieftain', gwI \¹_ `net, web', rhYn á¥ `hound of chase',
Black Speech shaRkU ²^¤¸' `old man'). No distinction is made between long and
overlong vowels.
as might have been denoted by anna. The remaining four tengwar are pronounced as the ones
input by the corresponding lowercase Roman letters.

5

<!-- p. 6 -->

Diphthongs with e as second element are written as yanta bearing the te-
hta for the rst element (oer î¤ `sea'). Diphthongs with i as second element
are written as anna bearing the tehta for the rst element (uir '´¤ `eternity').
Diphthongs with u as second element are written as ure bearing the tehta for
the rst element (naug ¥^ï¹ `dwarf').

6.2 Consonants
In either of the two Sindarin modes you have the option of choosing whether
the calmat ema or the quesset ema is to be used for velar consonants (and,
in the latter case, whether the calmat ema is to be used for palatal conson-
ants) and whether the oretyelle or the n umetyelle is to be used for single
nasal consonants. The selection of the Classical Sindarin mode automatic-
ally allocates the velars in the quesset ema, though \vaswestron makes c avail-
able for calma (English cek ° ¸ `cheque') and \vincalma transfers the rest of
the velars into the calmat ema. (The shortcut \blackspeech is equivalent to
\sindarin \oleft \vaswestron.) Also, the the nasal consonants are allocated
in the n umetyelle, though this setting can be altered by specifying \ninOre, and
restored by \ninnUmen. The following consonants and consonant clusters are
available in the default setting:
b © bh « B ¯ c, k ¸ ch, kh º
d ¡ dh £ D § f « g ¹ gh »
h ì hw í j ³ l â lh ã
m mh mm | n ¥ nn ¥| N ½
p ¨ ph ª r ¤ rh á
s è ss ê sh ² t th ¢
v « w ¼ z ê zh ³
Double consonants are written with an underbar tehta (tellen â ¥ `footprint').
The only exceptions are ss, which is written as esse, and mm and nn, which are
written as malta and n umen with or without an overbar or overtilde tehta.
bh is provided for the sake of completeness, as an alternative to v.
f is written as formen in initial and medial position (farn ª^à¥ `enough',
tofn ª¥ `deep') and as ampa in nal position (tif _« ` ute').
gh, j,
sh, z, zh are provided in order to make possible the typesetting of text in Westron
(zIr ê_ ¤ `wise') or the Black Speech (ghAsh »^² ` re').
H is always written as hyarmen, without forming a digraph with a preceding
consonant letter.
i is written as yanta when it appears as a glide in initial position (iAr î^¤
\`blood', iolf î â« `brand', iuith î'´¢ `use', iUl î' â or iuul î$â `embers').
m is written as an overbar or overtilde tehta when preceding a labial conson-
ant (hamp ì^~¨ `garment', ammarth ^à¢^| `doom, fate').

6

<!-- p. 7 -->

n is written as an overbar or overtilde tehta when preceding a dental or velar
consonant (rhink á _~¸ `sudden move', lhann ã ¥^| `wide').
ph is written as formen in initial and nal position (alph ^âª `swan') and as
formen with an underbar tehta in medial position (ephel ª â `outer fence').
r is written as ore when it occurs word- nally (bar ©^¤ `home') and as r omen
elsewhere (rAd à^¡ `path, track', arth ^à¢ `region, realm'). It is, however,
always written as r omen if n is ore.
R is written as ore if n is n umen, and as r omen otherwise.
w is written as a squiggle tehta when following another consonant other
than h (gwelw \¹\â `air'). A tengwa can bear no more than one conson-
ant superscript tehta, however, so w following a consonant preceded by a
homorganic nasal is written separately as a wilya (angwedh ¹¼^| £ `chain',
glentweth ¹â ~ ¼¢ `thinness'), unless the etymology suggests a di erent
spelling (as in the case of thurin{}gwethil ¢'à_¥\¹ ¢_â `secret shadow wo-
man').
When silme and esse bear a tehta for a preceding vowel (which is, in fact, always
the case with esse), their nuquerna shapes are automatically substituted (kost
¸ é `quarrel', bess © ë `woman').

6.3 Illustrations
6.3.1 The King's letter to Samwise Gamgee
(From Sauron Defeated.)
âë^¤ â¸ ~ ^¤; ^à^¹à¥ ^à^¢à¥_¥ £âì^à¥, ^à^¥ ¹ ¡| ¤ ^¤ ì_ ¤ _ ©^´¤| ¥^| '´, ¹â^| ¥^¢^| _
«^à¡^| '´¥_ ^~ à_¥ ¡ â¢¥ ¢'´â, ¹¤ © ¥ ¹ ¥¡_^¡ ¡à ¥^´â^| à_¥ \¹_à_¢ \¡¥. ^¤ ^¥_ à^
¥^é| è'´â ¥^| ^¡ â ¥ _ ¥ ª^´¥; ¡à¹â ^¥_ à^ _ à^¡ _ º ¤¡_¤ ¨ ¤ì^îâ (_ è ¥| '´ ¨^~ ì^îâ
é ^¢^¤ ^î¥) ¸ ¡| _¤ _ ¡à ¥,^| ^¤ à_â © ë ¡_ ¥, ^¤ â^¥¤, à_â, ¹â àª ¥__| â, ^¤ ´à_¥ è â ^¢
¡_ ¥; ^¤ î àì^îâ, ¹ â_¤, ¸ à¡«, ^¤ ©^à^«à¥ î ¥^¢| ¡_ ¥.
^ ª àì^îâ ^¤ ^ à_â è '´â^¡ '´¥ ^à^¥ _¥^é _à_¢ ¥ âº^î¥¥ '´¥ º'´¤.

6.3.2 The Ring inscription
(From The Lord of the Rings.)
^² ¥^ë¹ ¡ ¤©^ â"¸, ^² ¥^ë¹ ¹ ©^_| â,
^² ¥^ë¹ ¢à^¸^ â"¸, ^» © ¤ê_²_ ¸à _~¨^ â

7 Beleriandic
7.1 Vowels
Short vowels are written as tengwar. Long vowels, written double (if they could
be doubled in the Classical Sindarin mode) or represented as capitals in the

7

<!-- p. 8 -->

input, are written as the corresponding tengwar with an andaith (eel îâ `star',
too ´ `thither', uur ïà ` re'; Ar à `king, chieftain', gwI \± `net, web', rhYn
áé¤ `hound of chase').
Diphthongs with e as second element are written in full (oer ´îà `sea').
Diphthongs with i as second element are written as the tengwa for the rst
element bearing a di resis tehta (uir ïà `eternity'). Diphthongs with u as
second element are written as the tengwa for the rst element bearing a squiggle
tehta (naug ¤\± `dwarf').

7.2 Consonants
The selection of the Beleriandic mode automatically allocates the velars in the
calmatema and the single nasal consonants in the oretyelle, though this setting
can be altered by specifying \vinquesse or \vincalma for the former and/or
\ninnUmen or \ninnOre for the latter. The following consonants and consonant
clusters are available in the default setting:
b © bh « B ¯ c, k ° ch, kh ²
d ¡ dh £ D § f « g ± gh ³
h ì hw í j ³ l â lh ã
m ¬ mh mm n ¤ nn ¥ N µ
p ¨ ph ª r à rh á
s è ss ê sh ² t th ¢
v « w ¼ z ê zh ³
The glide i in initial position is written as a long carrier (iAr à `blood'). The
remaining input conventions are the same as in the Classical Sindarin mode.8
Since there are no vowel tehtar in this mode, silme and esse always appear
in their upright (not nuquerna) shapes.

7.3 Illustrations
7.3.1 The hymn of the Rivendell elves
(From The Road Goes Ever On.)
îâ©îàî¢! ± â¢´¤ îâ! è â «àî¤ ¨î¥ ¬ à îâ, ´ ¬î¤îâ ±â à îâî¤ ¢!
¤ ,² îàî¡ ¨ â ¤,¡ à îâ ´ ± â £àî ¤ î¥´à ¢; ª ¤ïâ´è, âî â ¥ ¢´¤,
¤î« î à, è ¤î« î à´¤!

7.3.2 The inscription on the Moria Gate
(From The Lord of the Rings. Observe the spelling mel{}lon ¬îââ´¤ instead
of mellon ¬îâ ´¤.)
î¥é¤ ¡ïà ¤ à ¤ ¬´à ; ¨î¡´ ¬îââ´¤ ¬ ¥´.
¬ ¤ à« ì¤ î² ~ ; °îâî©à ©´à| ´ îàî± ´¤ î¢ ~ ¢ ¼ ì ¤.
8An error in the de nition of the Beleriandic mode used to interfere with the proper
interpretation of word-internal ph. In Version 1.10 this has been corrected.

8
