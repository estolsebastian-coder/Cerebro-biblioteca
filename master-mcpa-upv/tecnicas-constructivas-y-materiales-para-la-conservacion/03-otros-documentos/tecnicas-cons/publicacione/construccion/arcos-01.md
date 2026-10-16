---
type: libro
title: "APPROCHES NUMERIQUES POUR L'ETUDE DU COMPORTEMENT DES STRUCTURES MAÇONNEES ANCIENNES: Un outil basé sur le Calcul à la Rupture et la visualisation graphique"
author: "Apostolia Oikonomopoulou"
categoria: "Técnicas Constructivas y materiales para la conservación"
paginas: 238
extraccion: "texto"
fuente: "local:D:/UPV/MCPA/Asignaturas/Técnicas Constructivas y materiales para la conservación/03. Otros documentos/Técnicas constructivas/Publicaciones/Construcción/Arcos 01.pdf"
convertido: 2026-10-16
---

# APPROCHES NUMERIQUES POUR L'ETUDE DU COMPORTEMENT DES STRUCTURES MAÇONNEES ANCIENNES: Un outil basé sur le Calcul à la Rupture et la visualisation graphique

> Texto extraído de `Técnicas Constructivas y materiales para la conservación\03. Otros documentos\Técnicas constructivas\Publicaciones\Construcción\Arcos 01.pdf` (238 páginas, texto). El PDF original está en el disco D: (UPV\MCPA\Asignaturas); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

APPROCHES NUMERIQUES POUR L’ETUDE DU
COMPORTEMENT DES STRUCTURES
MAÇONNEES ANCIENNES : Un outil basé sur le
Calcul à la Rupture et la visualisation graphique
Apostolia Oikonomopoulou

To cite this version:

Apostolia Oikonomopoulou. APPROCHES NUMERIQUES POUR L’ETUDE DU COMPORTE-
MENT DES STRUCTURES MAÇONNEES ANCIENNES : Un outil basé sur le Calcul à la Rupture et
la visualisation graphique. Matériaux. Université Paris-Est; ENSA Paris La Villette, 2009. Français.
￿tel-00493588￿

HAL Id: tel-00493588

https://tel.archives-ouvertes.fr/tel-00493588

Submitted on 20 Jun 2010

HAL is a multi-disciplinary open access L’archive ouverte pluridisciplinaire HAL, est
archive for the deposit and dissemination of sci- destinée au dépôt et à la diffusion de documents
entific research documents, whether they are pub- scientifiques de niveau recherche, publiés ou non,
lished or not. The documents may come from émanant des établissements d’enseignement et de
teaching and research institutions in France or recherche français ou étrangers, des laboratoires
abroad, or from public or private research centers. publics ou privés.

<!-- p. 2 -->

ECOLE NATIONALE SUPERIEURE D’ARCHITECTURE DE PARIS LA VILLETTE
ECOLE DOCTORALE «VILLE, TRANSPORTS ET TERRITOIRE», UNIVERSITE PARIS-EST

Thèse préparée au sein de :
Atelier de Recherche en Informatique, Architecture et Modélisation-

Laboratoire d'Architecturologie et de Recherches Epistémologiques

pour obtenir

LE GRADE DE DOCTEUR

en discipline :
architecture

par
Apostolia Th. OIKONOMOPOULOU

Titre de la thèse :
APPROCHES NUMERIQUES POUR L’ETUDE DU COMPORTEMENT

DES STRUCTURES MAÇONNEES ANCIENNES :

Un outil basé sur le Calcul à la Rupture et la visualisation graphique

soutenue le 16 Décembre 2009 devant le jury composé de :

Monsieur Joël SAKAROVITCH Président du jury

Monsieur Santiago HUERTA Rapporteur

Monsieur Jean Claude MOREL Rapporteur

Monsieur François FLEURY Examinateur

Monsieur François GUENA Directeur de thèse

Monsieur Thierry CIBLAC Tuteur

<!-- p. 3 -->



<!-- p. 4 -->

Avant propos

Cette thèse a été réalisée au laboratoire ARIAM-LAREA de l’Ecole Nationale Supérieure
d’Architecture de Paris la Villette pendant les trois ans entre décembre 2006 et décembre 2009.
Elle a été financée partiellement par une bourse issue de la direction de l’Architecture et du
Patrimoine du ministère de la Culture et de la Communication. Je resterai toujours
reconnaissante pour ce soutien.

Je tiens à remercier profondément le Professeur François Guéna, directeur de cette thèse, pour
avoir encadré et guidé mes travaux de recherche pendant ces trois ans. Egalement, je remercie les
Maîtres Assistants des Ecoles d'Architecture, M. Thierry Ciblac et M. Louis-Paul Untersteller,
ainsi que tous les membres d’ARIAM-LAREA qui m’ont accueilli chaleureusement au laboratoire
dès le début, quand je suis arrivée comme une comète, même sans parler la langue française. Le
présent travail a été structuré et réalisé en collaboration avec M. Ciblac, tuteur de cette thèse,
dont les conseils m’ont toujours été précieux et continueront à l’être.

Je remercie le Professeur Joël Sakarovitch pour avoir accepté de présider au jury de cette thèse.

Le Professeur Santiago Huerta pour ses commentaires et pour l’inspiration qui m’a donné avec
ses travaux de recherche.

Le Chercheur Jean Claude Morel pour le temps qui a dédié pour étudier si profondément ce
mémoire et pour avoir ouvert un champ de développement important.

Le Professeur François Fleury pour ses remarques et ses suggestions.

Un grand merci à Mme Nazila Hanachi-Belkadi qui, même si elle provient d’un domaine
scientifique différent, est entrée à la problématique du sujet de cette thèse afin de contribuer à son
amélioration.

Enfin je souhaite transmettre toute mon affection et mes remerciements à M. Charisis
Chatzigogos pour son soutien, tant scientifique que personnelle, sans lequel je n’aurais jamais
achevé ce travail.

Cette thèse est dédiée à ma mère Eleni Kechagia Oikonomopoulou pour le support qu’elle m’a
accordé pendant toute ma vie.

Αυτό το διδακτορικό είναι αφιερωμένο στην μητέρα μου Ελένη Κεχαγιά Οικονομοπούλου για την
συμπαράσταση της σε όλη την ζωή μου.

I

<!-- p. 5 -->

II

<!-- p. 6 -->

Sommaire

L’ingénieur et l’architecte, confrontés à la large demande pour la préservation des structures
historiques et monumentales, ont besoin d’une approche transdisciplinaire et efficace pour le traitement de
ces systèmes complexes. Les travaux de recherche proposés dans cette thèse s’inscrivent particulièrement
à un effort de développement d’un outil informatique servant à une évaluation préliminaire de la stabilité des
structures maçonnées anciennes. Etant donné que le comportement statique global de ce type de structures
pose plutôt un problème d’équilibre, le théorème statique du Calcul à Rupture est utilisé afin de vérifier la
stabilité d’une structure maçonnée sous chargements statiques ou quasi-statiques. La méthode proposée
correspond aux systèmes structuraux bidimensionnels ou pseudo-tridimensionnels (symétries axiales) qui
comportent les éléments typiques de l’architecture médiévale combinés de façons variables (arc - arcboutant – pilier). L’évaluation du comportement des éléments constitutifs dans la stabilité de la structure
globale ainsi qu’une approximation des régions d’endommagement sont mis en œuvre. Trois applications de
l’outil aux systèmes structuraux inspirés d’édifices médiévaux sont présentées.

Mots-clés : maçonnerie, architecture médiévale, matériau sans traction, théorème statique, Calcul à
Rupture, évaluation préliminaire de stabilité, modélisation-restitution architecturale.

III

<!-- p. 7 -->

Abstract

The engineer and the architect, confronted to the ubiquitous demand for the preservation of historic
and monumental buildings, need an interdisciplinary and effective method for the treatment of these
complexes systems. The research study proposed in this thesis concerns the development of a tool serving
for a first-level evaluation of the stability of ancient masonry structures. As the global static behaviour of this
type of structures is mostly an equilibrium problem, the static theorem of the Yield Design Theory is used in
order to verify the stability of a masonry structure under static or pseudo-static loadings. The proposed
method corresponds to two-dimensional or pseudo three-dimensional structural systems (axial symmetries)
that comprise the typical elements of the medieval architecture (arch – flying-buttress – pillar) combined in
various ways. The evaluation of the behaviour of the constitutive elements in relation to the stability of the
global system as well as an approximation of the damaged areas are implemented. Three applications of the
tool on structural systems inspired from medieval buildings are presented.

Key words: masonry, medieval architecture, no tension material, static theorem, Yield Design Theory,
first-level evaluation of stability, architectural modelling-restitution.

IV

<!-- p. 8 -->

Table des notations principales

Lettres latines

Paragraphe
Notation Signification
d’apparition

Ε module d’élasticité 1.2.1

Q facteurs de chargement 1.3

K domaine des Q potentiellement supportables 1.3.1

Q vecteur de charment 1.3.1.2

3 xG vecteur position d’un point dans R 1.3.1.2

R n ensemble des nombre réels n 1.3.1.2

n nombre des paramètres de chargement 1.3.2.1
G( xG ) domaine des σ( xG ) admissibles 1.3.1.2
Q× vecteur de chargements extrêmes 1.3.2.1

ux, uy uz composantes du champ de vitesse 1.3.2.4
G
T vecteur d’effort sur une surface 1.4.1
nG vecteur unitaire normale 1.4.1

s coordonnée de courbe directrice 1.4.2

q coordonnée orthogonale à s 1.4.2

h(s) épaisseur d’une structure curviligne plane 1.4.2

N(s) effort normal au point s 1.4.2

V

<!-- p. 9 -->

Paragraphe
Notation Signification
d’apparition

M(s) moment fléchissant au point s 1.4.2
nG (s) vecteur unitaire tangent sur la courbe directrice 1.4.2

e(s) excentricité par rapport à la courbe directrice 1.4.2

N΄ (s) effort normal pour équilibrer le couple N(s), M(s) 1.4.2
G
R force de réaction 1.4.3.1a
G
Rx, Rz composantes horizontale et verticale de la force de réaction R 1.4.3.1a
G
V poids propre 1.4.3.1a

Gx abscisse du centre de gravité d’une portion circulaire 1.4.3.1a

Rint, Rext rayons intérieur et extérieur d’une portion circulaire 1.4.3.1a
G
iF force de réaction développée au joint i d’un bloc-voussoir 1.4.3.1b
G
Wi chargement vertical du nœud i dans un réseau de forces 1.4.3.1c

H poussée, composante horizontale de la réaction d’un élément 1.4.3.1c

t épaisseur d’un élément 1.4.4

r rayon moyen d’un arc 1.4.4
G
U champ de vitesse virtuel 1.4.5

d tenseur de taux de déformations virtuel 1.4.5

m masse 1.4.5

z vecteur des ordonnées d’un réseau des forces 2.1

z1 , z 2 ,... nz ordonnées d’un réseau des forces 2.1

K matrice d’équilibre 2.1

W vecteur des chargements verticaux 2.1

ordonnées des contours extérieur et intérieur du nœud i d’un z ext ,i , z int, i 2.1 réseau des forces

VI

<!-- p. 10 -->

Paragraphe
Notation Signification
d’apparition

Hint, Hext hauteurs intérieure et extérieure d’un arc (ou flèche) 2.2.1

RO rapport ogival d’un arc 2.2.1

S aire d’une surface 2.2.1

Ks coefficient sismique 2.2.1.2

g accélération de la gravité 2.2.1.2

système des coordonnées cartésiennes pour la simulation du
(x΄,z΄) 2.2.1.2
chargement sismique de manière quasi-statique

h hauteur d’un élément vertical 2.3

Fs coefficient relatif à la traction 2.5.1

Ft coefficient de frottement 2.5.2

Hr,i forces horizontales aux appuis d’une coupole 4.2

Hcir,i forces circonférentielles d’une coupole 4.2

Lettres Grecques

Paragraphe
Notation Signification d’apparition

σ1, σ2, σ3 contraintes principales 1.2.3
σ( xG ) tenseur de contraintes 1.3.2.1

θ1, θ2 angles entre l’axe horizontal et les joints d’une portion circulaire 1.4.3.1a
G G
ρ1, ρ2 rayons de l’application des R1 , R2 1.4.3.1a

β angle entre la rotule d’un arc et l’axe vertical 1.4.4
G
U π ( ) densité de puissance résistante maximale 1.4.5
facteur modifiant le chargement vertical proportionnellement du
λ 2.2 poids propre

VII

<!-- p. 11 -->

Paragraphe
Notation Signification
d’apparition

γ poids volumique 2.2.1.1

Angle de rotation de structure pour la simulation du chargement
φ 2.2.1.2
sismique de manière quais-statique

a pente du côté rectiligne d’un arc-boutant 2.3

δ angle entre la normale à un joint et la ligne de pression 2.5.2

θ angle entre un joint et l’axe horizontal 2.5.2

ψ angle entre la ligne de pression et l’axe horizontal 2.5.2

Symboles

Paragraphe
Notation Signification d’apparition

a quantité virtuelle a 1.4.5
[[a ]] discontinuité d’une quantité a 1.4.5

αarc paramètre caractérisant un arc (central) 2.2.1

paramètre utilisé pour la simulation des forces d’inertie d’un
αs 2.2.1.2 chargement sismique imposé de manière quasi-statique

α΄ paramètre a appartenant à un système des coordonnes (x΄,z΄) 2.2.1.2

αab paramètre caractérisant un arc-boutant 2.2.2

αp paramètre caractérisant un pilier 2.2.2

αcu paramètre caractérisant une culée 2.3

α* paramètre appartenant à une géométrie symétrique 2.3.2

VIII

<!-- p. 12 -->

Table des matières

1 Contexte du travail…………………………………………………..………………………………………3

1.1 Introduction………………………………………………..……………………………………………………3

1.1.1 Motivations……………………………………………………………………………………………3

1.1.2 Les structures concernées et leurs détériorations………………………………………………..6

1.1.3 Le matériau……………………………………………………………………………………………9

1.1.4 Le problème de la stabilité de structures maçonnées…………………………………………..14

1.1.5 Organisation de la thèse – Objectifs………………………………………………………………15

1.2 Aperçu des modélisations des structures maçonnées……………………………………………………17

1.2.1 Modélisations des structures maçonnées à l’échelle macroscopique………………………...17

1.2.2 Modélisations des structures maçonnées à l’échelle microscopique………………………….23

1.2.3 Approches multi-échelles – homogénéisation…………………………………………………...24

1.2.4 Conclusion sur les méthodes de modélisation des structures maçonnées…………………..27

1.3 Présentation générale du Calcul à la Rupture……………………………………………………………..28

1.3.1 La notion de la « stabilité potentielle » du Calcul à la Rupture……...…………………………29

1.3.2 La mise en œuvre du Calcul à la Rupture ………………………………………………………..33

1.3.2.1 Le domaine K…………………………………………………………………..………….33

1.3.2.2 L’approche statique par l’intérieur……………………………………………………….34

1.3.2.3 L’approche statique par l’extérieur………………………………………………………35

1.3.2.4 L’approche cinématique par l’extérieur…………………………………………………36

1.4 Application du Calcul à la Rupture aux structures maçonnées………………………………………….38

1.4.1 Critère de résistance………………………………………………………………………………..38

IX

<!-- p. 13 -->

1.4.2 Critère de résistance - Structures curvilignes planes……………………………………….…..40

1.4.3 Mise en œuvre de l’approche statique par l’intérieur pour les structures maçonnées
curvilignes - La notion de « la ligne de pression » ………………………………………………………..42

1.4.3.1 Les méthodes de construction de la ligne de pression……………………………….46

1.4.4 Mise en œuvre de l’approche statique par l’extérieur pour les structures maçonnées
curvilignes - la notion de «l’équilibre limite» ………………………………………………………………54

1.4.5 Mise en œuvre de la méthode cinématique par l’extérieur pour les structures maçonnées
curvilignes……………………………………………………………………………………………………..56

1.4.6 Les précautions de l’adoption du critère de résistance du matériau sans traction…………..61

1.4.7 Autres outils du Calcul à la Rupture………………………………………………………………62

1.5 Modélisation géométrique de l’édifice en vue d’une simulation de son comportement structurel
………………………………………………………………………………………………………………….62

1.5.1 La modélisation volumique et surfacique à partir de document……………………………….63

1.5.2 La modélisation à partir de nuages de points acquis par laser………………………………..65

1.5.3 La modélisation à partir de photos………………………………………………………………..68

1.5.4 La modélisation paramétrique…………………………………………………………………….71

1.5.5 Assistance à la modélisation et à la construction d’un maillage………………………………74

1.5.6 Exigences de discrétisation du modèle en vue de réalisation des calculs mécaniques
…………………………………………………………………………………………………………………79

1.6 Conclusion du Chapitre 1……………………………………………………………………………………81

2 Développement d’un outil de simulation du comportement des structures
maçonnées………..…..……………………………..……………..……………………………..……………...84

2.1 La méthode d’O’Dwyer………………..……………………………..……………………………..………..86

2.2 Etude de la stabilité des éléments structuraux………………..……………………………..……………89

2.2.1 Arc…………..…..…………..…………..……………………………..…………………………….…92

X

<!-- p. 14 -->

2.2.1.1 Chargement sous poids propre………………..…………………..……………………94

2.2.1.2 Chargement sismique: approche quasi-statique………………..……………………96

2.2.2 Arc-boutant………………..……………………………..……………………………..…………101

2.2.2.1 Chargement vertical………………..……………………………..……………………..101

2.2.2.2 Chargement sismique: approche quasi-statique………………..……………………103

2.2.3 Pilier….…..……………………………..……………………………..……………………………105

2.2.4 Jonction de plusieurs éléments………………..……………………………..………………….107

2.3 Système structural………………..……………………………..……………………………..……………111

2.3.1 Chargement sous poids propre………………..……………………………..………………….113

2.3.1.1 Procédure et calculs………………..……………………………..…………………….113

2.3.1.2 Effets stabilisants du système………………..…………….……..……………………118

2.3.1.3 L’effet du comportement de bloc de la jonction de plusieurs éléments……………120

2.3.2 Chargement sismique: approche quasi-statique………………..……………………………..122

2.3.3 Remarques………………..……………………………..……………………………..………….128

2.4 Comparaison avec des résultats obtenus par des analyses du système aux éléments finis et aux
éléments discrets.…..……………………………..……………………………..……………………………..132

2.4.1 Comparaison avec des résultats obtenus par des analyses du système aux éléments
finis…….…………………………..……………………………..……………………………..……………132

2.4.2 Ligne de pression d’un système structural et traitement aux éléments discrets……………137

2.5 Coefficients de sécurité………………..……………………………..……………………………..……...138

2.5.1 Coefficient relatif à traction dans la structure………………..……………………………..….138

2.5.2 Coefficient relatif au glissement dans la structure………………..……………………………141

2.6 Considérations sur l’épaisseur minimale, les rotules et les poussées extrêmes d’un arc en plein
cintre………………..……………………………..……………………………..……………………………..…147

2.6.1 Considérations sur la détermination de l’épaisseur minimale d’un arc………………..…….147

XI

<!-- p. 15 -->

2.6.2 Etudes paramétriques d’un arc en plein cintre : position de rotules et poussées extrêmes en
fonction du rapport t/r ……..………………..……………………………..………………………………151

2.6.2.1 Position de rotules d’un arc un plein cintre par rapport au rapport t/r….…………151

2.6.2.2 Poussées extrêmes d’un arc en plein cintre en fonction du rapport t/r
………………………………………………………………………………………………………152

2.6.3 Remarques…………………………………………………………………………………………152

2.7 Conclusion du Chapitre 2…………………………………………………………………………………..154

3 Applications de l’outil………………………………………………………..……………………………159

3.1 Etude de la stabilité d’une coupe inspirée par la géométrie de l’église Santa Maria del
Borgo………………………………………………………………………………………………………………161

3.2 Etude de la stabilité d’une coupe inspirée par la géométrie de la nef de la cathédrale
d’Amiens……………………………………………………………………………………………..……………169

3.2.1 Etudes paramétriques de la stabilité d’une coupe inspirée par la géométrie de la nef de la
cathédral d’Amiens………………………………………………………………………………….………173

3.3 Etude de la stabilité d’une coupe inspirée par le chevet de la basilique de Saint-Quentin………….177

3.3.1 Stabilité du système et effet de l’adjonction de l’arc-boutant intermédiaire…………………181

3.3.2 Stabilité du système pour une géométrie déformée…………………………………………...186

3.4 Conclusion du Chapitre 3…………………………………………………………………………………..190

4 Conclusion générale et Perspectives…………………………..………………………………………193

4.1 Conclusion.....................................................................................................................................193

4.2 Perspectives..................................................................................................................................197

Références Bibliographiques……………………………………………………..………………………………203

Annexes………………………...……………………………………………………..………………………………213

XII

<!-- p. 16 -->

Liste de Figures

Chapitre 1

Figure 1.1 – Le modèle volumique de l’église de Montreuil (Guéna, 2005) ………………………………..……5

Figure 1.2 – Arcs en succession pour la construction de l’aqueduc (Ségovie, Espagne) ……………..…..……6

Figure 1.3 – Altérations de la maçonnerie (Anjar, Liban) …………………………………………….………..……7

Figure 1.4 – (a) Fortification médiévale dans un milieu urbain contemporain et (b) interventions récentes à
l’église de Santa Maria del Borgo (Rhodes, Grèce) …………………..………………..………………….…..……8

Figure 1.5 – Evolution des états d’équilibre pour la maçonnerie (Anjar, Liban) …………..………………..…….9

Figure 1.6 – Les deux familles de maçonneries : le blocage et l’appareil…………..………………..…………..10

Figure 1.7 – Hétérogénéité de la maçonnerie carolingienne…………..………………..………………..……….12

Figure 1.8 – Anisotropie des éléments et des joints d’une maçonnerie appareillée…………..………………..13

Figure 1.9 – Les trois échelles de la maçonnerie…………..………………..………………..………………..…..14

Figure 1.10 – Isovaleurs des déplacements verticaux pour chargement sous poids propre
(extrait de Godart et al.1996) …………..………………..………………..………………..………………..……….19

Figure 1.11 - Lois de comportement élastique non-linéaire appropriée pour la maçonnerie…………..………20

Figure 1.12 - Essai cyclique d’un mur de maçonnerie sous force latérale dans le plan, tiré de Tomazevic
(1999) …………..………………..………………..………………..………………..………………..………………..22

Figure 1.13 - Model aux éléments discrets de la structure colonne-architrave du Parthénon d’Athènes.
Déformations permanentes après une analyse sismique, extrait de Psycharis et al. (2003) …………..……..24

Figure 1.14 - Définition du volume représentatif…………..………………..………………..………………..……25

Figure 1.15 – Domaine de résistance de la maçonnerie, extrait de De Buhan et al. (1997) …………..……...26

Figure 1.16 – Cadre à dix barres…………..………………..………………..………………..………………..……29

Figure 1.17 – Chargements « potentiellement supportables » pour la structure de la Figure 1.16…………...31

Figure 1.18 - Approximation par l’intérieur de la frontière du domaine …………………………………....……35

Figure 1.19 - Approximation de la frontière du domaine par l’approche statique par l’extérieur……………..36

Figure 1.20 - Interface arbitraire dans une structure constituée de matériau sans traction….…………..……39

XIII

<!-- p. 17 -->

Figure 1.21 - Représentation du critère de résistance du matériau sans traction dans l’espace des
contraintes principales…………..………………..………………..………………..………………..……………….40

Figure 1.22 – Structure curviligne bidimensionnelle…………..………………..………………..…………………41

Figure 1.23 – « Lignes de pression » en maçonnerie dans deux arcs-boutants (ancienne et nouvelle
construction) de l’église St Jacques-du-Haut-Pas, Paris…………..………………..………………..……………44

Figure 1.24 – Les notions de la « ligne de résistance » et de la « ligne de pression » en 1830 (extrait de
Moseley) …………..………………..………………..………………..………………..………………..…………….45

Figure 1.25 – Equilibre de la portion d’un arc en plein cintre utilisé pour la construction de la ligne de
pression (première méthode) …………..………………..………………..………………..………………..………48

Figure 1.26 – Equilibre d’un bloc–voussoir d’un arc en plein cintre utilisée pour la construction de la ligne de
pression (deuxième méthode) …………..………………..………………..………………..………………..……..49

Figure 1.27 – Ligne de pression d’un arc construite par le calcul des résultantes compressives aux
joints…………..………………..………………..………………..………………..………………..………………….49

Figure 1.28 – Statique graphique et géométrie dynamique (Ciblac et al. 2008) …………..………………..….50

Figure 1.29 – La méthode du réseau de forces proposée par O’Dwyer (1999) …………..………………..…..51

Figure 1.30 - Comparaison des méthodes de construction de la ligne de pression : méthode du réseau de
forces (ligne en pointillé) et méthode de Moseley (ligne continue) …………..………………..…………………52

Figure 1.31 – Equilibre d’un arc aux limites pour l’évaluation de la poussée minimale (Heyman, 1969, 2009)
…………..………………..………………..………………..………………..………………..………………..……….55

Figure 1.32 – Equilibre d’un contrefort fissuré (extrait d’Ochsendorf et al. 2004) …………….…………..…….56

Figure 1.33 – Champs de vitesses qui conduisent à une puissance résistante maximale nulle : (a) pour les
points de vitesse continue les valeurs propres du tenseur d doivent être négatives et (b) pour les surfaces de
discontinuité de vitesse, la vitesse doit être normale sur la surface …………..………………..………………..58

Figure 1.34 – (a) Mécanisme de rupture pour un arc et (b) champs des vitesses aux points
d’ouverture…………..………………..………………..………………..………………..………………..…………...59

Figure 1.35 – Accélération maximale utilisée pour une simulation quasi-statique…………..………………….60

Figure 1.36 – Modélisation volumique : (a) Arc : révolution du profil autour d’un axe semi-circulaire………64

Figure 1.37 – Illustration schématique des deux principes de fonctionnement des dispositifs de balayage
laser, extrait de Marbs (2001). A gauche le principe du temps de vol, à droite celui de la
triangulation…..…………..…………..…………..…………..…………..…………..…………..…………..………..66

Figure 1.38 – Photogrammétrie et modélisation 3D..…… ……..……..…………..…………..…………..………68

Figure 1.39 – Schéma représentant les trois techniques de restitution photogrammétrique (extrait de De
Luca, 2006). De gauche à droite : la restitution à partir d’une seule image, d’un couple d’images et d’un bloc
multi-image…..…………..…………..…………..…………..…………..…………..…………..…………..…………69

Figure 1.40 – Représentation schématique du principe des règles 3X3 considérant les prises de vue autour
d’un bâtiment afin de réaliser une restitution multi-image complète (extrait de Grussenmeyer, 2003) …..….70

Figure 1.41 – Modélisation paramétrique d’un arc (plein cintre-ogival) avec le logiciel COBALT…..…………72

XIV

<!-- p. 18 -->

Figure 1.42 - Le modèle tridimensionnel d’une église méso-byzantine, résultat de modélisation paramétrique
et de CSG, extrait de Potamianos et al. (1995) …..…………..…………..…………..…………..…………..……73

Figure 1.43 – Le modèle paramétrique de l’église St Julien, Couleuvre, France (extrait du web site de
l’Université de Columbia) …..…………..…………..…………..…………..…………..…………..…………..……74

Figure 1.44 – Architecture logicielle du système, extrait de Chassagnoux et al. (2000) …..…………..……..76

Figure 1.45 – Interprétation du graphe topologique, extrait de Chassagnoux et al. (2000) …..…………..…..77

Figure 1.46 – Visualisation du maillage d’une voûte sélectionnée, extrait de Chassagnoux et al. (2000)
…..…………..…………..…………..…………..…………..…………..…………..…………..…………..…………..77

Figure 1.47 – Les niveaux logiques du logiciel OGIVES (extrait de Chassagnoux et al. 2000) ..…………….78

Chapitre 2

Figure 2.1 - L’architecture logicielle de l’outil..…………. ..…………. ..….………. ..…………. ..…………. ..…86

Figure 2.2 - L’équilibre d’un assemblage de blocs..…………. ..…………. ..…………. ..…………. ..………….87

Figure 2.3 - Equilibre aux 3 nœuds du réseau..…………. ..…………. ………….……...…………. ..………….88

Figure 2.4 - Critère de résistance pour le matériau sans traction..…………. ..…………...…………. ..………91

Figure 2.5 - Les caractéristiques de la géométrie d’un arc en plein cintre..…………. ..…………. ..………….94

Figure 2.6 - Discrétisation de l’arc en plein cintre..…………. ..…………. ..…………. ..…………. ..………… 94

Figure 2.7 - Chargement vertical de l’arc..…………. ..…………. ..…………. ..…………. ..…………. ..………95

Figure 2.8 - Etat passif (minHarc) et état actif (maxHarc) de l’arc..…………. ..…………. ..…………. ..……...97

Figure 2.9 - Chargement sismique de manière quasi-statique d’un arc......................................................... 98

Figure 2.10 - Changement du système des coordonnées pour simulation du chargement sismique............. 99

Figure 2.11 - Ligne de pression de l’arc (chargement sous poids propre et sismique, Ks=0.37).................. 101

Figure 2.12 - La géométrie de l’arc-boutant étudié ..................................................................................... 102

Figure 2.13 - Discrétisation et chargement vertical de l’arc-boutant............................................................. 103

Figure 2.14 - Ligne de pression pour les poussées extrêmes d’un arc-boutant (chargement vertical)........ 104

Figure 2.15 - Chargement de l’arc-boutant sous poids propre et simulation du chargement sismique de la
manière quasi-statique................................................................................................................................. 105

Figure 2.16 - Ligne de pression de l’arc-boutant (chargement sismique, Ks=0.37)..................................... 105

Figure 2.17 - Maillage du pilier, chargement sous poids propre et chargement sismique de la manière quasistatique ........................................................................................................................................................ 106

Figure 2.18 - Le bloc de jonction de trois éléments structuraux différents .................................................. 108

Figure 2.19 - Equilibre des triangles ABI1 et BCI1......................................................................................... 110

Figure 2.20 - Deuxième estimation du point d’intersection I......................................................................... 111

XV

<!-- p. 19 -->

Figure 2.21 - Géométrie du système examiné : arc - arc-boutant - pilier .................................................... 113

Figure 2.22 - Procédure itérative pour la définition des combinaisons possibles d’équilibre pour minHarc.. 115

Figure 2.23 - Lignes de pression du système ............................................................................................. 116

Figure 2.24 - Domaine d’équilibre du système............................................................................................. 118

Figure 2.25 - Géométrie du système examiné : arc - arc-boutant - pilier de hauteur augmentée................ 119

Figure 2.26 - Domaines d’équilibre du système pour différentes valeurs de hpp ......................................... 120

Figure 2.27 - La poussée de l’arc aux appuis horizontaux et de l’arc contre buté....................................... 121

Figure 2.28 - Domaines d’équilibre du système en considérant le bloc de la jonction a) comme corps rigide
et b) comme matériau sans traction............................................................................................................. 122

Figure 2.29 - L’équilibre du système pour un bloc de jonction considéré comme un corps rigide.............. 123

Figure 2.30 - Chargement horizontal de l’arc et des arcs-boutants............................................................. 124

Figure 2.31 - Changement du système des coordonnées de l’arc et des arcs-boutants............................. 125

Figure 2.32 - Chargement sismique des piliers et des culées..................................................................... 125

Figure 2.33 - Ligne de pression du système pour un chargement horizontal 0.3g...................................... 126

Figure 2.34 - Ligne de pression du système pour un chargement sismique Ks=0.075............................... 128

Figure 2.35 - Domaines d’équilibre de la structure étudiée pour trois valeurs différentes de l’accélération
sismique....................................................................................................................................................... 128

Figure 2.36 - Le système examiné par Smars (2000) et son domaine d’équilibre....................................... 130

Figure 2.37 - Formation de mécanisme de rupture en fonction de la valeur d’accélération et de la durée du
phénomène sismique (Ochsendorf, 2002) ................................................................................................... 131

Figure 2.38 - Contraintes principales σ11 du système (chargement sous poids propre) - structure déformée
..................................................................................................................................................................... 134

Figure 2.39 -.Contraintes principales σ22 du système (chargement sous poids propre) - structure déformée
..................................................................................................................................................................... 134

Figure 2.40 - Comparaison des résultats pour chargement sous poids propre avec une analyse aux éléments
finis .............................................................................................................................................................. 135

Figure 2.41 - Lignes de pression du système pour chargement sous poids propre (tarc/rarc = 0.12)......... 136

Figure 2.42 - Contraintes principales σ11 du système (tarc/rarc = 0.12, chargement sous poids propre) –
structure déformée....................................................................................................................................... 136

Figure 2.43 - Comparaison des résultats de l’analyse aux éléments finis et de l’outil pour le système
(chargement sous poids propre et sismique de Ks = 0.05).......................................................................... 137

Figure 2.44 - Le système examiné par Acary (2001) ................................................................................... 138

Figure 2.45 - Paramètres de définition du coefficient relatif à la traction..................................................... 139

Figure 2.46 - Réduction du domaine d’équilibre pour chargement sous poids propre en appliquant la loi du
tiers central .................................................................................................................................................. 141

XVI

<!-- p. 20 -->

Figure 2.47 - Paramètres de définition du coefficient relatif au glissement .................................................. 143

Figure 2.48 - Variation de l’angle δ de l’arc et de l’arc-boutant pour minHarc, minHab \< Hab \< maxHab... 144

Figure 2.49 - Variation de l’angle δ de l’arc et de l’arc-boutant pour maxHarc, minHab \< Hab \< maxHab... 145

Figure 2.50 - Variation de l’angle δ de l’arc et des arcs-boutants pour chargement sous poids propre et
sismique Ks = 0.075..................................................................................................................................... 145

Figure 2.51 - Variation de l’angle δ pour minHab est a) considéré d’un système structural et b) examiné seul
..................................................................................................................................................................... 146

Figure 2.52 - Variation de l’angle δ pour un arc en plein cintre des joints verticaux et des joints horizontaux
..................................................................................................................................................................... 147

Figure 2.53 - Diagramme de l’angle β et du ratio t/r pour minHarc et pour maxHarc................................... 151

Figure 2.54 - Diagramme du rapport t/r d’un arc en plein cintre en fonction des minHarc et maxHarc ...... 152

Chapitre 3

Figure 3.1 - L’église de Santa Maria del Borgo, Rhodes, Grèce................................................................. 161

Figure 3.2 - Le système examiné (église Santa Maria del Borgo)............................................................... 162

Figure 3.3 - Considération de la stabilité de la jonction entre l’arc central et l’arc latéral droit ..................... 164

Figure 3.4 - Lignes de pression du système pour : minHarc, minHc \< Hc \< maxHc .................................... 164

Figure 3.5 - Lignes de pression du système pour : maxHarc, minHc \< Hc \< maxHc ................................... 165

Figure 3.6 - Lignes de pression du système pour : minHarc, minHc \< Hc \< maxHc. Chargement sismique
Ks=0.1.......................................................................................................................................................... 166

Figure 3.7 - Lignes de pression du système pour : maxHarc, minHc \< Hc \< maxHc. Chargement sismique
Ks=0.1.......................................................................................................................................................... 166

Figure 3.8 - Domaine d’équilibre du système pour chargement sous poids propre et pour des chargements
sismiques d’intensité variable ...................................................................................................................... 167

Figure 3.9 - A gauche : coupe de la nef de la cathédrale d’Amiens. A droite : le système étudié................ 169

Figure 3.10 - Linges de pression du système pour : (a) minHarc, maxHc, minHab \< Hab \< maxHab ........ 171

Figure 3.11 - Domaine d’équilibre du système pour hp - hc et hp (considération de minHc et maxHc) ..... 172

Figure 3.12 - Domaine d’équilibre du système............................................................................................ 172

Figure 3.13 - Lignes de pression du système pour RO = 100% et RO = 156% ........................................... 173

Figure 3.14 - Domaines d’équilibre du système pour RO = 100%, RO = 125%, RO = 156%, RO = 173%. 174

Figure 3.15 - Rapport entre la solution obtenue pour la considération de l’arc (RO = 173%)dans le système
structural et des solutions obtenues pour un arc examiné seul de l’étude paramétrique de Ciblac (2008).. 175

Figure 3.16 - A gauche, plan de la basilique de Saint-Quentin et à droite, vue extérieure de la partie du
chevet étudiée.............................................................................................................................................. 177

XVII

<!-- p. 21 -->

Figure 3.17 - A gauche: coupe typique du chevet. A droite : vue entre deux coupes typiques du chevet.... 178

Figure 3.18 - Les tirants en bois du déambulatoire...................................................................................... 178

Figure 3.19 - Le système étudié................................................................................................................... 179

Figure 3.20 - Lignes de pression................................................................................................................. 182

Figure 3.21 - Domaines d’équilibre du système d’origine et du système après l’adjonction de l’arc-boutant
intermédiaire (considération minHab,2) ....................................................................................................... 183

Figure 3.22 - Domaines d’équilibre du système après l’adjonction de l’arc-boutant intermédiaire............... 184

Figure 3.23 - Lignes de pression.................................................................................................................. 185

Figure 3.24 - Déversement du pilier et augmentation correspondante de l’écartement d’arc du déambulatoire
..................................................................................................................................................................... 186

Figure 3.25 - Domaine d’équilibre du système d’origine (dx = 0 et dx = 0.1tp) ............................................ 187

Figure 3.26 - Domaines d’équilibre du système après l’adjonction de l’arc-boutant intermédiaire (dx = 0 et dx
\= 0.1tp)......................................................................................................................................................... 188

Chapitre 4

Figure 4.1 - A gauche : Statique graphique appliquée à l’étude de stabilité des systèmes structuraux
(Chapelle du Saint-Paul à l’université de Columbia, extrait par Goodyear, 1906)........................................ 194

Figure 4.2 - Explorations de nouvelles formes en équilibre.......................................................................... 199

Figure 4.3 - Explorations de nouvelles formes en équilibre : Replacement du pilier droit par un pilier
symétrique et un élément supplémentaire ................................................................................................... 200

Figure 4.4 - Surface de pression d’une coupole en fonction des forces de réaction Hr,i et
des forces circonférentielles Hcir,i ............................................................................................................... 201

Annexes

Figure A.1 – Déplacement et rotation de la partie droite de l’arc du déambulatoire..................................... 213

XVIII

<!-- p. 22 -->

Liste de Tableaux

Chapitre 1

Tableau 1.1 - Propriétés mécaniques des éléments (extrait d’Acary, 2001) .................................................. 11

Tableau 1.2 - Quantités à définir dans chaque point d’une structure............................................................ 37

Chapitre 2

Tableau 2.1 - Poussées extrêmes de l’arc en plein cintre de t/r = 0.25 pour densités variables de
discrétisation.................................................................................................................................................. 97

Tableau 2.2 - Définition du rapport mint/r selon différentes approches...................................................... 150

Chapitre 3

Tableau 3.1 - Paramètres de l’arc du déambulatoire et vérification de la stabilité du système pour différentes
valeurs du défaut d’aplomb du pilier ............................................................................................................ 188

XIX

<!-- p. 23 -->

Publications réalisées à partir de la

thèse

\1. Ciblac, T., Oikonomopoulou, A., Guéna, F. (2008) - Approches numériques pour l'étude du

comportement des structures maçonnées anciennes. Proc. Congrès d'histoire de la construction,

Paris. (Parties rédigées par Oikonomopoulou : paragraphes 2 et 4)

\2. Oikonomopoulou, A., Ciblac, T., Guéna, F. (2009a) - Modeling Tools for the Mechanical

Behavior of Historic Masonry Structures. Proc. of Third International Congress on History

Construction, Cottbus, Germany.

\3. Oikonomopoulou, A., Ciblac, T., Guéna, F. (2009b) - Parametric studies using tools for the

analysis of the stability of masonry structures. Proc. PROHITECH2009 International Conference

in Protection of Historical Buildings, Rome.

\4. Oikonomopoulou, A., Untersteller, L.-P., Ciblac, T., Guéna, F. (2009) - Structures maçonnées

anciennes : diagnostiquer les situations de stabilité. Proc. Colloque International, la ville et les

risques urbains, Constantine, Algérie.

XX

<!-- p. 24 -->

Chapitre 1

Contexte du travail

Résumé du Chapitre 1

Ce premier chapitre constitue une introduction à la problématique de la thèse et décrit le
cadre général dans lequel ce travail est situé. Le chapitre vise à fournir à la fois un exposé de la
motivation qui a conduit à la réalisation de cette étude, une présentation des éléments théoriques
de base concernant le comportement mécanique des structures maçonnées, ainsi qu’un aperçu
des travaux de recherche récents, relatifs au sujet abordé.
Le chapitre est divisé en cinq parties. La première partie n’est dédiée qu’à la présentation
de la motivation de cette étude. La valeur inestimable des monuments historiques (dont le
matériau de construction est dans la grande majorité la maçonnerie) d’une part et le caractère
tout à fait singulier de la maçonnerie d’autre part, créent le besoin d’outils simplifiés aux
communautés d’ingénieurs-architectes et d’archéologues, permettant une évaluation efficace
d’aspects tels que la stabilité des structures maçonnées, l’identification des zones susceptibles à
l’endommagement, l’estimation du risque sismique etc. Ces besoins sont à l’origine de cette
étude et offrent la motivation pour la définition de ses objectifs.
La deuxième partie est consacrée à la présentation des différentes méthodes de
modélisation mécanique des structures maçonnées. Une première classification des méthodes de
modélisation est effectuée sur la base de l’échelle de référence pour le modèle mécanique
introduit. Ainsi, on a la classe de modélisations macroscopiques, qui font introduire un modèle
mécanique pour le matériau « maçonnerie » à l’échelle de la structure globale. Dans les
modélisations microscopiques, la connaissance de la géométrie des joints de la maçonnerie
permet d’introduire des modèles pour les phases de la maçonnerie vue comme un matériau
hétérogène : modèle pour les blocs de pierres ou les briques et surtout modèle pour les joints de
la maçonnerie qui sont les zones de localisation des déformations irréversibles, de dissipation
d’énergie etc. Une deuxième classification des méthodes de modélisation est effectuée par
rapport aux ingrédients nécessaires pour leur mise en œuvre. Ainsi, on a la classe des approches
du Calcul à la Rupture qui permettent de vérifier la stabilité potentielle d’un système mécanique
de géométrie et de résistance données sous un procédure de chargement prédéfinie et les
approches du suivi du trajet de chargement de la structure qui font introduire en plus la loi de
comportement du matériau constitutif de la structure. En visant à la plus grande généralité de
l’outil développé on se place dans le contexte des modélisations macroscopiques avec les
approches du Calcul à la Rupture, ce qui permet de s’affranchir des incertitudes liées à la
géométrie exacte des joints d’une structure maçonnée et à la loi de comportement pertinent.

1

<!-- p. 25 -->

Dans cet esprit, la troisième partie porte sur une brève présentation de la théorie du
Calcul à la Rupture. Les lignes principales de la théorie sont décrites ainsi que sa mise en œuvre
sous forme de trois méthodes différentes : méthode statique par l’intérieur, méthode statique par
l’extérieur et méthode cinématique par l’extérieur. Les caractéristiques des trois méthodes sont
discutés ainsi que les traits qualitatifs des leurs résultats dans la pratique de l’ingénierie.
La quatrième partie présente l’application du Calcul à la Rupture aux structures
maçonnées. La mise en ouvre des trois approches de cette méthode est faite pour les structures
élancées en présentant brièvement les travaux existants pertinents. Les notions de « la ligne de
pression » et de « l’équilibre limite » sont explorées.
Le premier chapitre s’achève avec une présentation des méthodes de modélisation d’une
structure visant à sa simulation mécanique. On présente les exigences d’une telle modélisation
ainsi que les développements réalisés dans le domaine de l’informatique pour l’ingénieurarchitecte et l’archéologue afin d’avoir des outils qui permettent un traitement holistique de la
réhabilitation et de la protection des monuments historiques. Les contributions de cette thèse
doivent être considérées sans oublier qu’elles s’inscrivent dans ce contexte général.

2

<!-- p. 26 -->

1 Contexte du travail

1.1 Introduction

1.1.1 Motivations

La conservation du patrimoine architectural ancien est incontestablement un enjeu important pour les
communautés des ingénieurs et des architectes dans les sociétés modernes et à plusieurs titres. Il s’agit d’un
enjeu culturel en premier lieu, puisque les structures qui ont survécu jusqu’à nos jours sont les témoins
incontournables du passé historique et d’un enjeu urbanistique, puisque les monuments anciens se trouvent
très souvent dans des milieux urbains plus récents. Enfin, il s’agit d’un enjeu social et économique, car
plusieurs structures anciennes sont encore en usage et constituent un capital précieux pour le développement
d’aspects tels que le tourisme, la recherche et l’identité culturelle.

L’ingénieur et l’architecte, confrontés à la large demande pour la préservation des structures
historiques et monumentales, ont besoin d’une approche transdisciplinaire et efficace pour le traitement de
ces systèmes complexes. Cette approche doit s’étendre sur le spectre entier des questions soulevées dans
un projet de préservation, en commençant par l’acquisition des données géométriques et la restitution
architecturale et aboutissant à la mise en œuvre de simulations et de calculs permettant de vérifier la sûreté
et la fonctionnalité de ces structures. Les travaux de recherche proposés dans cette thèse s’inscrivent
particulièrement dans un effort de développement d’un outil simplifié pour l’analyse du comportement
mécanique des structures maçonnées anciennes.

La procédure de développement de l’outil, abordée dans cette thèse, a été articulée suivant les points
suivants :

a. Premièrement, l’outil doit fournir un cadre pertinent pour la description des structures du point de vue
géométrique, mais aussi mécanique, en gardant la plus grande généralité possible. En d’autres termes, il doit
ne conserver que les informations nécessaires pour une simulation mécanique à partir du grand volume

3

<!-- p. 27 -->

4 1 Introduction

d’informations issues de restitutions architecturales détaillées. Du point de vue mécanique, il doit être adapté
à la spécificité du comportement mécanique du matériau constitutif des structures anciennes. Ce dernier point
se révèle d’une importance centrale à cause de la nature extrêmement compliquée du matériau de
construction « maçonnerie 1», qui rend son traitement par l’ingénieur susceptible d’incertitudes variées. Il n’est
peut-être pas exagéré de remarquer que le matériau « maçonnerie » rassemble dans ses caractéristiques
mécaniques tous les éléments « indésirables » pour la modélisation : hétérogénéité, anisotropie,
endommagement fragile, plasticité non-associée, comportement unilatéral, difficulté de distinguer des
échelles caractéristiques, difficulté de préciser les propriétés mécaniques des matériaux constitutifs (pierres –
briques – mortier), diverses détériorations au cours du temps etc. Ajoutons que le terme « maçonnerie » est
de contexte très général : il comporte de nombreuses techniques et dispositions constructives, rencontrées à
des époques et des régions différentes et présentant des caractéristiques mécaniques variables. Cette
constatation limite considérablement l’applicabilité de modèles sophistiqués pour le matériau « maçonnerie »
et privilégie les approches simplifiées. Le comportement mécanique compliqué de la maçonnerie crée le
besoin de méthodes générales et simples qui fournissent une première évaluation de la tenue mécanique de
la structure globale et guident la sélection du modèle mécanique avancé qui est le plus approprié dans
chaque cas.

b. L’outil envisagé doit pouvoir servir de moyen d’investigation pour le chercheur de la technologie et de
l’histoire de la construction. A partir d’analyses de configurations simples, l’outil peut permettre la mise en
œuvre d’études paramétriques et l’explication de la pathologie (ruptures, fissures, déformations etc.) qui sont
survenues à un moment donné. Il peut aider à la localisation de zones susceptibles d’endommagement dans
une structure réelle et à une quantification des dommages possibles.

c. L’outil de calcul de stabilité envisagé doit compléter les sorties des autres outils qui interviennent
dans les phases d’un projet de préservation de monuments. Parmi ceux-ci, les plus importants sont les outils
de reconstitution géométrique de la structure. Ce point fait appel à des travaux de recherche déjà effectués au
sein de l’Atelier de Recherche en Informatique Architecture et Modélisation (ARIAM). Ces travaux ont porté
sur la conception et la mise en œuvre d’un outil de simulation du comportement des voûtes d’ogives
gothiques à destination des architectes en chef des monuments historiques (Chassagnoux et al. 1998). Il

1 Le terme est utilisé pour désigner le matériau (homogénéisé ou pas) qui est introduit dans la modélisation mécanique de la

structure maçonnée et qui permet de reproduire à partir de sa loi de comportement tous les effets qui caractérisent la réponse de la

structure réelle.

<!-- p. 28 -->

1.1 Motivations et objectifs 5

s’agissait d’un projet de recherche, financé par la sous direction des monuments historiques du Ministère de
la Culture, qui a abouti au développement d’un premier prototype permettant d’assister l’architecte à produire
un maillage de la structure en vue d’un calcul aux éléments finis (Chassagnoux et al. 2000). Dans le même
esprit, les travaux présentés dans cette thèse concernent le développement d’un outil qui permet l’évaluation
de la stabilité de la structure au moyen des méthodes du Calcul à la Rupture en se basant sur des systèmes
structuraux produits par les logiciels de restitution des modèles volumiques d’édifices originalement destinés à
des calculs aux éléments finis. Comme exemple typique, on présente sur la Figure 1.1 le modèle volumique
reconstitué pour l’église de Montreuil. La mise au point d’outils utilisant la théorie du Calcul à la Rupture pour
des calculs de la stabilité des structures maçonnées fut aussi l’objectif d’un programme d'échange entre
l’ARIAM et le département d'architecture de l’Institut de Technologie de Massachusetts (MIT). Le projet a eu
lieu en 2004 et a abouti à une méthodologie d'utilisation de principes de la statique graphique et de la
géométrie dynamique pour étudier le comportement des structures (Block et al. 2006).

Figure 1.1 – Le modèle volumique de l’église de Montreuil (Guéna, 2005)

<!-- p. 29 -->

6 1 Contexte du travail

1.1.2 Les structures concernées et leurs détériorations

Les structures maçonnées constituent la grande majorité du patrimoine architectural historique
mondial. Selon le type de structure, les anciens bâtisseurs et maçons utilisaient la maçonnerie pour atteindre
des buts différents. Dans le cas des églises et des cathédrales, le but était la couverture d’un grand espace.
Avec l’avancement des techniques de construction et des connaissances mécaniques, l’espace couvert
devient de plus en plus large par le déploiement des formes complexes, constituées d’éléments, dont les
dômes, les arcs, les arcs-boutants, les voûtes, les piliers. Le lancement d’un pont par dessus une rivière était
une opération délicate, qu’il s’agisse de la franchir d’une seule portée ou grâce à une ou plusieurs piles
intermédiaires capables de résister à l’action de l’eau et à la force du courant. La construction des
fortifications et des aqueducs demandait un matériau lourd et volumineux dont les constituants pouvaient
facilement être trouvés et préparés sur le site.

Figure 1.2 – Arcs en succession pour la construction de l’aqueduc (Ségovie, Espagne)

Les structures maçonnées, souvent exposées aux conditions environnementales agressives et
rapidement changeantes dans le temps, demandaient un matériau de grande durabilité. Etant données ces
conditions, le matériau d’une structure maçonnée subit fréquemment des altérations variées dépendantes de
ses caractéristiques physiques (porosité, durabilité, conductivité thermique, etc.). A titre d’exemple, la
présence de sels (sulfuriques, nitriques, carboniques, chloriques, etc.) dans les matériaux constitutifs de la
maçonnerie (pierre, brique, mortier), soit par constitution, soit par une infiltration générée par l’humidité à
partir d’autres sources (par le sol, par exemple), peut créer des altérations de leur texture. En parties hautes
de murs, on rencontre souvent un type de dégât, identifié facilement par la formation sur la surface des

<!-- p. 30 -->

1.1 Motivations et objectifs 7

matériaux de cellules et de cavités de dimensions variées (altération alvéolaire). La cause de ce type
d’altération et généralement l’exposition de la structure à la pluie et au vent.

Des traces de fissuration et de ramollissement peuvent être observées dans les parties de la
maçonnerie exposées à des cycles de gel et de dégel et là où peuvent se développer des racines de plantes.
Par ailleurs, l’altération biologique peut aussi avoir un caractère chimique à cause de bactéries et de
microorganismes développés sur les éléments structuraux humides et insuffisamment ensoleillés. Ce type de
dégât se reconnaît par l’altération de la couleur et de la texture de la surface. Les points de contact entre la
maçonnerie et les éléments métalliques rouillés sont à l’origine de dégâts qui peuvent se propager dans des
parties saines de la maçonnerie. Il s’agit d’un point qui s’avère très important pour la restauration des édifices
maçonnés : la sélection d’un matériau de renforcement tel que l’acier peut être dommageable pour la
structure maçonnée à long terme, même s’il augmente ses capacités de résistance, à cause d’une
détérioration de type chimique - physique.

Figure 1.3 – Altérations de la maçonnerie (Anjar, Liban)

Pour les structures maçonnées dans les milieux urbains, la pollution atmosphérique constitue un
agent supplémentaire de détérioration des matériaux des façades extérieures. Ajoutons les aménagements
urbains, les perturbations du sous-sol voisin (construction d’ouvrages souterrains) et l’abaissement de la
nappe phréatique, qui peuvent générer des déplacements et des inclinaisons au niveau de la fondation des
structures ainsi que de la fissuration à la superstructure. Des dégâts peuvent encore être provoqués à cause

<!-- p. 31 -->

8 1 Contexte du travail

de vibrations dues à la circulation de véhicules lourds. Un séisme peut provoquer la perte de stabilité d’une
partie ou de l’ensemble des structures maçonnées. Les changements dans le système structural initial,
provenant d’agrandissements et d’interventions récents, peuvent entraîner de nouveaux états de stabilité ou
même des ruptures à une structure maçonnée. Le retrait du mortier, surtout de celui utilisé dans le
remplissage entre les deux parements d’un mur, conduit à la diminution des sections initiales des éléments
structuraux et peut entraîner lui aussi des états d’instabilité (Papagianni et al. 2006).

(a) (b)

Figure 1.4 – (a) Fortification médiévale dans un milieu urbain contemporain et (b) interventions récentes à l’église de

Santa Maria del Borgo (Rhodes, Grèce)

Cette liste indicative de dégâts et de détériorations potentiels d’une structure maçonnée souligne
d’une part, la vulnérabilité de ces structures et révèle, d’autre part, une évolution dans le temps ainsi que
l’existence de mécanismes de défense contre tous ces agents agressifs. Comme le note Heyman (1995),
malgré toutes ces altérations possibles, les structures maçonnées ont une capacité à réagir et à trouver des
états d’équilibre nouveaux pour accommoder les effets des alternations possibles, qui peuvent y survenir
pendant leur longue vie. Cette capacité de résistance découle de la nature de ces structures, qui peuvent être
vues comme des ensembles de blocs posés les uns contre les autres de manière à ce que l’ensemble se
trouve dans un état stable. La structure à l’échelle globale peut s’accommoder des altérations qui se
produisent à l’échelle des blocs par le changement de sa géométrie au moyen de la fissuration. La stabilité
des structures maçonnées s’avère une question de géométrie plutôt qu’une question de résistance de
matériau (Heyman, 1995).

<!-- p. 32 -->

1.1 Motivations et objectifs 9

Figure 1.5 – Evolution des états d’équilibre pour la maçonnerie (Anjar, Liban)

Cette remarque fondamentale d’Heyman se trouve à la base des travaux de recherche abordés dans
cette thèse. On s’intéresse aux ruptures des structures maçonnées liées à une instabilité qui est entraînée par
une incompatibilité entre le chargement imposé à la structure et la géométrie de la structure. Cette question
de compatibilité chargement/géométrie est traitée en imposant la condition très générale d’impossibilité de
transférer des forces de traction aux blocs de la maçonnerie. De ce point de vue, on s’intéressera à des
structures qui assurent leur stabilité au moyen de leur forme géométrique en combinant plusieurs éléments
structuraux (arcs, arcs-boutants, etc.), telles que par exemple les églises médiévales.

En dehors du manque de résistance en traction, on ne précisera pas davantage la loi de
comportement du matériau « maçonnerie », qui toutefois peut s’avérer extrêmement compliquée. Ainsi on ne
pourra pas traiter avec les méthodes développées des ruptures à l’échelle globale, liées à une perte ou à une
insuffisance de résistance au niveau de blocs de la maçonnerie.

1.1.3 Le matériau

Le matériau de construction « maçonnerie » est probablement un des tous premiers matériaux de

construction dans l’histoire de l’humanité. Il reste cependant bien moins connu que les autres matériaux de

l’architecture contemporaine : l’acier et le béton.

Le terme « maçonnerie » recouvre tout ouvrage construit de pierres, de briques, d’agglomérés ou tout

autre élément servant à la construction. Les éléments constitutifs de la maçonnerie sont compactés entre eux

par la gravité. Du point de vue mécanique, cela correspond bien évidemment à des comportements et des

réponses variés. Dans ce paragraphe on essaie d’introduire les termes les plus importants du vocabulaire des

<!-- p. 33 -->

10 1 Contexte du travail

maçonneries. Les ouvrages de référence des Viollet-le-Duc (1856), Pérouse de Montclos (1988) et Laurent

(2007) sont des guides complets en ce qui concerne les techniques de construction de la maçonnerie et la

terminologie des dispositions constructives.

Très généralement, deux familles de maçonneries peuvent être différenciées par leur construction : le

blocage et l’appareil. Le blocage est une maçonnerie d’éléments de différentes tailles, jetés pêle-mêle dans

un bain de mortier. Le blocage peut être utilisé de plusieurs manières : seul, pour constituer des éléments

structuraux ou en fourrure pour remplir l’intermédiaire entre deux appareils constituant les parements.

L’appareil est une maçonnerie d’éléments posés et non jetés : chaque élément est adapté,

éventuellement équarri ou taillé, pour occuper une place déterminée. Plusieurs types d’appareils sont

couramment rencontrés. L’appareil irrégulier est le moins ordonné au niveau de ces éléments. L’appareil

assisé présente une régularité plus importante. Une assise est un rang d’éléments de même hauteur posés

de niveau ou rampant. L’appareil à assises régulières est un appareil assisé constitué d’éléments de

longueurs variables mais de même hauteur. Dans la Figure 1.6, on présente sur les vestiges du monastère

médiéval de Zarakas (Péloponnèse, Grèce) les deux types de maçonnerie susmentionnés.

Figure 1.6 – Les deux familles de maçonneries : le blocage et l’appareil

Les deux éléments de base de la maçonnerie sont les éléments et les joints.

Les éléments sont constitués des morceaux du matériau de construction de la maçonnerie qui sont

posés (appareil) ou jetés (blocage) de manière à former le corps de la maçonnerie. Les matériaux utilisés

pour les éléments sont la pierre, la brique, les agglomérés, la terre crue et la tuile (entière ou concassée). Les

<!-- p. 34 -->

1.1 Motivations et objectifs 11

éléments sont le plus souvent décrits par les fabricants par leurs caractéristiques d’élasticité linéaire et leur

résistance en traction et en compression. Le comportement mécanique des éléments est de type fragile ou

quasi-fragile supposant en première approche une rupture brutale du matériau. Le Tableau 1.2, tiré d’Acary

(2001), fournit quelques valeurs caractéristiques pour les propriétés mécaniques des éléments de la

maçonnerie. La remarque que l’on retiendra est que la résistance en compression des éléments est

considérablement plus importante que la résistance en traction, celle-ci restant en général limitée à des

valeurs faibles.

Masse Module Résistance Résistance Coefficient
volumique d’Young traction compression de Poisson
(Kg/m3) (GPa) (MPa) (MPa)
Grès des Vosges a 2000 30 0.3 - 150
Granit b 2600 40 - 70 0.2 - 0.3 - 70 - 280
Calcaire b 2000 - 2600 20 - 70 0.2 - 0.3 25 – 30 20 - 200
Marbre b 2600 -2900 50 - 100 0.2 - 0.3 10 - 20 50 - 180
Beton c 2300 30 0.2 3 30
Agglomérés d 2000 - - 5 15
Brique creuse e 3000 5 0.3 8 20
Brique pleine f ancienne 3000 8.7 0.16 3.45 40
Brique pleine f moderne 3000 14.7 0.22 3.14 64
a Keryvin V. (1999),
b Gere J.M. et al (1990)
c Lemaitre J. et al. (1988)
d Société Bouyer – Leroux, masse volumique du matériau
f Atkinson et al. (1989)

Tableau 1.1 – Propriétés mécaniques des éléments (extrait d’Acary, 2001)

Les joints sont définis comme l’espace entre deux éléments. Le terme « joint » se réfère aussi

implicitement à la couche de matériau qui remplit cet espace, c’est-à-dire au mortier. Dans le cas où le

matériau est absent, on parle de joint vif. Les mortiers anciens et traditionnels sont à base de chaux. La

chaux grasse, obtenue par extinction de la chaux vive en la laissant vieillir, est la base du mortier traditionnel

rencontré dans les édifices anciens. Les propriétés mécaniques des mortiers dépendent d’un grand nombre

de paramètres dont le dosage des différents éléments constitutifs, la mise en œuvre etc. En règle générale,

les mortiers à base de chaux possèdent une plasticité très bonne mais leur résistance mécanique est faible et

leur cure lente. Les travaux de Moropoulou et al. (1997, 2000a, 2000b) fournissent une description détaillée

de la caractérisation mécanique des mortiers anciens en vue de leur aspect physico-chimique. On note

<!-- p. 35 -->

12 1 Contexte du travail

finalement que la caractérisation mécanique des joints-vifs se réduit à la description du frottement entre deux

éléments. Plusieurs résultats expérimentaux (par exemple, Armand et al. 1997) suggèrent que le frottement

des joints vifs est suffisamment décrit par la loi de frottement de Coulomb ; des coefficients de frottement

typiques sont à l’ordre de 0.90 pour une vitesse de glissement faible (coefficient de frottement statique) et

0.60 pour une vitesse de glissement élevée (coefficient de frottement dynamique).

Ce bref exposé de caractéristiques principales du matériau « maçonnerie » nous permet de retenir

les points importants suivants :

a. L’hétérogénéité de la maçonnerie. La maçonnerie est un matériau fortement hétérogène en vue des

comportements mécaniques très différents entre les éléments et les joints. Les éléments sont généralement

constitués de matériaux de forte résistance alors que les joints présentent des résistances faibles, surtout en

traction. Le cas des joints vifs constitue un cas extrême : le joint est réduit à une interface de résistance à la

traction nulle. La Figure 1.7, extrait de Viollet-le-Duc (1856), décrit le parement appareillé et le remplissage en

blocage d’une maçonnerie carolingienne. On peut distinguer trois éléments de résistance différente qui

rendent le matériau de la maçonnerie très hétérogène : les briques qui appartiennent à l’assise A et ont une
résistance σA, les pierres qui appartiennent à l’assise B et ont une résistance σB, et les joints remplis du
mortier de résistance σM.

Figure 1.7 – Hétérogénéité de la maçonnerie carolingienne

b. L’anisotropie de la maçonnerie. La maçonnerie est également un matériau anisotrope. Son

anisotropie augmente dans le cas de construction en appareil puisque le positionnement régulier de joints

dans des directions spécifiques, combiné avec le contraste des propriétés mécaniques entre les éléments et

les joints, crée des directions de chargement qui privilégient la rupture dans les joints, c’est-à-dire dans les

<!-- p. 36 -->

1.1 Motivations et objectifs 13

régions faibles de la maçonnerie (Figure 1.8). Dans le cas de construction en blocage, l’effet de l’anisotropie

diminue en vue du placement arbitraire des joints dans le corps de la maçonnerie.

Figure 1.8 – Anisotropie des éléments et des joints d’une maçonnerie appareillée

c. Les échelles de la maçonnerie. On note finalement qu’il est possible de distinguer dans la

maçonnerie trois échelles différentes : a) l’échelle au niveau des éléments et des joints ou échelle

microscopique, b) l’échelle de l’appareillage de la maçonnerie ou échelle mésoscopique et c) l’échelle de

la structure maçonnée elle-même ou échelle macroscopique. On notera que l’échelle microscopique met en

évidence l’hétérogénéité de la maçonnerie alors que l’échelle mésoscopique est plus liée à l’anisotropie de la

maçonnerie. On notera aussi que ces deux phénomènes sont généralement atténués en passant à l’échelle

macroscopique. On notera finalement que la distinction entre les trois échelles mentionnées n’est pas toujours

possible pour toutes les structures. Dans ces cas, il est possible de distinguer seulement deux ou même une

seule échelle caractéristique pour la structure entière. Dans la Figure 1.9 on présente schématiquement ces

trois échelles de la maçonnerie. Les dessins sont extraits de Viollet-le-Duc (1856).

<!-- p. 37 -->

14 1 Contexte du travail

Figure 1.9 – Les trois échelles de la maçonnerie

1.1.4 Le problème de la stabilité de structures maçonnées

Les paragraphes précédents ont souligné les points suivants par rapport au comportement
mécanique du matériau maçonnerie :

a. La formulation d’une loi de comportement générale pour le matériau « maçonnerie » présente des
difficultés importantes à l’égard des propriétés de la maçonnerie (hétérogénéité, anisotropie, échelles
caractéristiques, variabilité des matériaux constitutifs et des techniques de construction).

b. A l’échelle macroscopique, la maçonnerie présente une résistance à la traction très limitée à cause
de la présence de joints. Pratiquement, cette résistance peut être considérée nulle.

c. La résistance en compression et en cisaillement de la maçonnerie sont régies par le comportement
des éléments et des interfaces éléments/joints. En général, ces résistances suffisent largement pour la reprise
de contraintes de compression et de cisaillement développées dans une structure maçonnée.

d. Le seul critère à satisfaire en première approximation pour la stabilité de la maçonnerie est donc
qu’elle soit partout en compression. Il s’agit d’un critère de résistance très simple mais très efficace pour la
description du matériau « maçonnerie ».

<!-- p. 38 -->

1.1 Motivations et objectifs 15

La stabilité d’une structure sous un chargement donné est contrôlée par deux facteurs : sa géométrie
et ses capacités de résistance. La grande simplicité du critère de résistance de la maçonnerie implique que
l’on peut s’affranchir du facteur résistance et formuler le problème de stabilité comme un problème
géométrique plutôt qu’un problème de résistance du matériau constitutif (Heyman, 1995). Par exemple, si la
structure est composée de plusieurs blocs qui se trouvent en compression et si la résistance à la compression
est considérée infinie, la seule condition à satisfaire est l’équilibre de chaque bloc comme corps rigide, ce qui
constitue un problème de nature purement géométrique. Une preuve de cette remarque est fournie par les
règles traditionnelles des anciens bâtisseurs pour la conception des voûtes et des arcs-boutants en
maçonnerie qui sont géométriques, c’est-à-dire qu’elles définissent les proportions entre les éléments
structuraux d’un ensemble. Jusqu’ au 18ème siècle, les bâtisseurs ne disposaient pas de science de la
construction véritablement scientifique, fondée sur la résistance des matériaux et la mécanique, ils ont
cependant construit les chefs d’œuvres de l’architecture gothique (Huerta, 2001).

Aujourd’hui, le problème de stabilité des structures maçonnées peut être formulé dans le cadre de la
théorie du Calcul à la Rupture (Salençon, 2002), théorie qui permet de préciser si une structure peut
supporter une combinaison donnée de charges extérieures. Trois éléments sont nécessaires pour mettre en
œuvre une des approches du calcul à la rupture : a) la géométrie de la structure, b) les processus de
chargement et c) les critères de résistance des matériaux et des interfaces constitutifs de la structure. Il est
essentiel de noter que, dans le Calcul à la Rupture, il n’est pas nécessaire de préciser la loi de comportement
du matériau constitutif de la structure, qui est difficile à déterminer pour les structures maçonnées.

Dans la suite nous proposons une méthode d’analyse qui se base sur cette propriété des structures
maçonnées.

1.1.5 Organisation de la thèse – Objectifs…

Ayant expliqué les motivations et le contexte de notre travail, on procède dans la deuxième partie du
premier chapitre à un bref exposé des méthodes disponibles pour l’étude du comportement mécanique du
matériau « maçonnerie » en se basant sur les échelles de ce matériau. La troisième partie porte sur une
brève présentation de la théorie du Calcul à la Rupture utilisée pour notre approche et la quatrième partie sur
l’application de cette théorie aux structures maçonnées curvilignes planes. La cinquième partie vise à une
présentation des méthodes de restitution tridimensionnelle pertinentes pour la réalisation des simulations
mécaniques et relatives à la problématique exposée pour le développent d’un outil d’analyse de la stabilité
des structures maçonnées utilisable dans le domaine de réhabilitation des structures historiques.

<!-- p. 39 -->

16 1 Contexte du travail

Le deuxième chapitre présente les étapes du développement de l’outil proposé pour le calcul des
structures maçonnées utilisant l’approche statique du Calcul à la Rupture. Un système structural simple est
introduit afin de présenter le développement de la méthodologie adoptée. On compare les résultats de cette
simulation avec d’autres méthodes et on procède à l’adoption des coefficients de sécurité appropriés pour les
structures maçonnées. Aussi, on présente quelques considérations sur l’épaisseur minimale, les rotules et les
poussées extrêmes d’un arc en plein cintre.

Le troisième chapitre procède à l’exploration du comportement de systèmes plus exigeants en
étudiant des systèmes inspirés des édifices médiévaux réels. Des géométries différentes sont utilisées afin de
présenter la nature des résultats obtenus.

Le quatrième chapitre porte sur les conclusions et les objectifs du développement de l’outil pour les
calculs d’évaluation des structures maçonnées. Les obstacles et les inconvénients par rapport à la nature des
résultats obtenus et à l’intégration de l’outil de calcul aux systèmes de restitution tridimensionnelle existants
sont estimés. Les applications et les améliorations envisageables dans la lignée de ce qui a été développé
sont discutées.

<!-- p. 40 -->

1.2 Modélisations des structures maçonnées 17

1.2 Aperçu des modélisations des structures
maçonnées

On présentera dans ce paragraphe un aperçu des différentes méthodes de modélisation des
structures maçonnées. Notre exposé sera divisé en trois parties : a) modélisations à l’échelle macroscopique,
b) modélisations à l’échelle microscopique et c) approches multi-échelles et homogénéisation.

1.2.1 Modélisations des structures maçonnées à l’échelle
macroscopique

On commence tout d’abord par une considération de la structure maçonnée à son échelle globale :
échelle macroscopique dans le sens du paragraphe 1.1.3. Ceci implique alors la définition du matériau
constitutif « maçonnerie » qui est considéré continu et homogène dans la structure entière ou au moins dans
un ensemble de sous-structures qui restent à la même échelle que la structure globale. Bien évidemment, ce
matériau constitutif est défini de manière à ce qu’il reflète les propriétés de la maçonnerie à l’échelle
inférieure, c’est-à-dire à l’échelle des blocs de pierre, des briques, des joints etc.

La procédure de la modélisation commence par la définition de la géométrie de la structure. Comme,
il s’agit d’un sujet très riche, on décalera la discussion jusqu’au paragraphe 1.5, qui porte sur les méthodes de
restitution géométrique des structures maçonnées. La procédure est poursuivie par la définition du
chargement qui est appliqué sur la structure.

On s’intéresse alors à la troisième pièce d’information nécessaire pour achever la procédure de la
modélisation, qui n’est autre que la définition des caractéristiques mécaniques des matériaux constitutifs de la
structure. On peut noter que la caractérisation mécanique très générale d’un matériau en vu de son utilisation
dans une analyse mécanique exige la connaissance de deux éléments :

a) Les capacités de résistance du matériau. On considère une particule élémentaire du
matériau ainsi que les paramètres de forces élémentaires qui y sont appliqués (par exemple, tenseur
de contraintes pour une modélisation comme milieu continu, ou efforts de poutres pour une
modélisation en éléments de poutre etc.). Les capacités de résistance du matériau sont définies
comme la totalité des combinaisons possibles des paramètres de forces élémentaires qui peuvent
être supportées par la particule. On verra des exemples de cette notion aux paragraphes suivants.

b) La loi de comportement du matériau. Il s’agit de la relation qui relie les paramètres de forces
élémentaires avec les paramètres cinématiques correspondants. C’est effectivement cet élément qui

<!-- p. 41 -->

18 1 Contexte du travail

fournit une diversité énorme aux modélisations des structures maçonnées : la loi de comportement
peut être très différente selon le type de structure concerné, le niveau de sophistication désiré et le
type de résultat recherché.

En vue de ces éléments d’information, on peut donner une classification des méthodes d’analyse des
structures maçonnées dans deux grandes catégories :

a) Calcul à la Rupture. La première grande catégorie est celle des méthodes du Calcul à la
Rupture : pour la mise en œuvre du Calcul à la Rupture, on utilise comme éléments d’information la
géométrie, la procédure de chargement et les capacités de résistance du matériau constitutif
« maçonnerie » uniquement, sans définition de la loi de comportement de la maçonnerie. Le grand
avantage du Calcul à la Rupture est qu’il nous permet de nous affranchir du problème de la définition
rigoureuse de la loi de comportement du matériau maçonnerie. Ainsi les analyses préservent une
généralité importante. Les résultats des analyses permettent de dire si un chargement extérieur est
un chargement qui n’est pas supportable ou un chargement qui est potentiellement supportable par la
structure. Le terme « potentiellement supportable » (c’est-à-dire on ne connaît pas définitivement s’il
est supportable ou pas) exprime le prix à payer pour le manque d’une définition rigoureuse de la loi
de comportement. Ce point sera développé plus amplement au paragraphe 1.3.1. Un point
inconvénient du Calcul à la Rupture est qu’il ne fournit aucun élément sur la cinématique
(déformations) de la structure sous un chargement externe : c’est une autre conséquence du manque
de connaissance de la loi de comportement. Les résultats portent donc sur la stabilité de la structure
uniquement et on ne peut aucunement connaître la géométrie déformée de la structure. En vue des
incertitudes liées à la définition de la loi de comportement de la maçonnerie, on notera qu’une
analyse par les méthodes du Calcul à la Rupture doit toujours précédée une analyse plus
sophistiquée puisque les résultats du Calcul à la Rupture sont indépendants de la loi de
comportement et permettent donc d’encadrer les résultats obtenus par les méthodes d’analyse.

b) Suivi du trajet de chargement de la structure. Les méthodes qui introduisent une loi de
comportement de la maçonnerie, celle-ci étant d’emblée non-linéaire, peuvent être qualifiées en tant
que méthodes de suivi du trajet de chargement de la structure. L’analyse commence par un état
équilibré de la structure (par exemple, par un état entièrement déchargé ou par un état
d’autocontrainte stable) et impose un historique de chargement prédéfini de manière incrémentale :
dans chaque incrément de chargement, on calcule les forces internes dans la structure ainsi que la
cinématique (déformations / déplacements) qui leur est associée au moyen de la loi de
comportement. On peut ainsi avoir une connaissance complète de l’état de la structure à chaque
instant de son histoire de chargement. La rupture dans les méthodes de ce type s’obtient lorsqu’un

<!-- p. 42 -->

1.2 Modélisations des structures maçonnées 19

déplacement excessif est produit dans une partie de la structure impliquant que celle-ci ne peut plus
supporter d’incréments de chargement.

A partir de ce point, les méthodes de suivi du trajet de chargement sont distinguées selon la loi de
comportement qu’elles utilisent. Mentionnons quelques grandes familles de lois de comportement utilisées
pour la modélisation de la maçonnerie :

\1. Lois de comportement élastiques (linéaire ou non-linéaire). La loi de comportement élastique
linéaire est la loi de comportement la plus simple, puisqu’elle définit une relation linéaire entre les paramètres
de force et les paramètres cinématiques correspondants sans prise en compte des capacités de résistance de
la structure. Alors, il est possible de résoudre le problème d’équilibre de la structure en un seul pas de calcul.
Bien évidemment, ce type de modèle ne permet pas de retrouver les caractéristiques de la maçonnerie
(fissuration, glissement, déplacements irréversibles etc.) et pose le problème de sélection des bonnes
caractéristiques élastiques de la maçonnerie. Cependant, ce type de calcul permet de comprendre avec
précision les effets géométriques et structurels sur la tenue de la structure. Citons les travaux de Godart et al.
(1996) sur la Cathédrale de Strasbourg : la maçonnerie est modélisée comme matériau élastique linéaire
isotrope ; des résultats représentatifs de ce type d’analyse sont présentés sur la Figure 1.10.

Figure 1.10 – Isovaleurs des déplacements verticaux pour chargement sous poids propre

(extrait de Godart et al.1996)

<!-- p. 43 -->

20 1 Contexte du travail

Il est possible d’améliorer cette loi de comportement, en restant en régime linéaire, par la prise en
compte d’effets d’anisotropie : les caractéristiques élastiques prennent des valeurs différentes selon la
direction de chargement.

Il est également possible de formuler une loi de comportement élastique non-linéaire, en supposant
par exemple que la rigidité de la structure est différente si l’on impose dans la même direction un chargement
en compression ou en traction : par exemple, la caractéristique d’une résistance en traction nulle, peut être
obtenue en considérant une rigidité en traction nulle comme il représenté sur la Figure 1.11 (les contraintes
sont positives en compression). Des formulations de ce genre sont développées dans Lucchesi et al. (2008).
La caractéristique de ce type de formulations est la réversibilité parfaite du comportement du système : dans
un essai cyclique, on reste toujours dans la même courbe force-déplacement bilinéaire. Ce type de loi de
comportement suffit pour la description du comportement idéalisé sans traction : néanmoins, il ne peut pas
reproduire le phénomène de dissipation d’énergie qui peut avoir lieu dans le système.

Figure 1.11 - Lois de comportement élastique non-linéaire appropriée pour la maçonnerie

\2. Lois de comportement élastoplastiques. La description des processus de dissipation
d’énergie dans la structure (pour les chargements quasi-statiques) est effectuée au moyen des lois de
comportement élastoplastiques. Pour ce qui est des structures maçonnées, on notera qu’il y a plusieurs
mécanismes irréversibles dans la structure qui sont sources de dissipation d’énergie : le glissement possible
entre deux blocs de maçonnerie ou le long d’un joint, l’écrasement d’une partie de maçonnerie si elle est
soumise à des contraintes de compression élevées, la rupture fragile d’un bloc de pierre en traction ou en
flexion etc.

<!-- p. 44 -->

1.2 Modélisations des structures maçonnées 21

Les ingrédients nécessaires pour la formulation d’une loi élastoplastique sont grosso modo (en
dehors des caractéristiques élastiques) les suivants. a) La surface de charge, qui est définie dans l’espace de
paramètres de force et limite le domaine dans lequel le comportement du système reste élastique. La surface
de charge représente le seuil d’enclenchement de procédures de dissipation d’énergie dans le système. b)
Une loi dite d’écrouissage, qui définit comment la surface de charge évolue en fonction du chargement et c)
une loi dite d’écoulement, qui définit comment les déformations plastiques sont obtenues si l’on affranchit le
seuil de comportement plastique.

Il peut y avoir plusieurs variations sur la définition des trois ingrédients du comportement
élastoplastique, ce qui crée une variété très riche de formulations possibles. Une description des plus
importants modèles développés dans le contexte des structures maçonnées est donnée dans Acary (2001).

\3. Le phénomène d’endommagement. Une troisième famille de lois de comportement est
obtenue en introduisant dans la modélisation, le phénomène de dégradation de propriétés élastiques au fur et
à mesure que les déformations plastiques dans la structure s’accumulent. Ce phénomène, connu sous le nom
d’endommagement, est mis en évidence sur la Figure 1.12, qui représente les résultats obtenus à partir d’un
essai typique en chargement cyclique dans le plan d’un mur de maçonnerie (Tomazevic, 1999). La figure
présente clairement la dégradation de la rigidité apparente du système (pentes rouges) avec les cycles de
chargement. On notera également, un autre phénomène caractéristique du comportement des structures
maçonnées : celui de l’adoucissement : il s’agit d’une dégradation de la résistance de la structure avec
l’accumulation d’énergie dissipée et des déplacements irréversibles. Le phénomène de l’adoucissement est
représenté sur la Figure 1.12 par la courbe enveloppe bleu en pointillé d’allure décroissant.

Lemaitre et al. (2005) présentent les bases théoriques et un nombre abondant d’applications
concernant la prise en compte des phénomènes tels que l’endommagement, l’adoucissement ou la rupture
fragile dans la mécanique des structures. Pour des modèles développés dans le contexte des structures
maçonnées, on renvoie le lecteur aux travaux de Lofti et al. (1991) et de Papa et al. (1997).

<!-- p. 45 -->

22 1 Contexte du travail

Figure 1.12 - Essai cyclique d’un mur de maçonnerie sous force latérale dans le plan, tiré de Tomazevic (1999)

Achevons ce bref aperçu des modélisations macroscopiques des structures maçonnées avec un
commentaire sur l’analyse limite. Il s’agit en fait, d’un type de calcul identique à celui du Calcul à la Rupture :
on cherche les charges ultimes supportées par la structure sans examiner le trajet suivi par la structure pour
arriver à l’état de ruine. Comme on l’a vu, dans le Calcul à la Rupture, en vue d’un manque de connaissance
de la loi de comportement du matériau constitutif de la structure, on ne peut avoir que les chargements
potentiellement supportables par la structure. Dans l’analyse limite, on tente de remédier cette partialité de
connaissance sur la tenue de la structure, on introduisant les éléments qui permettront de savoir avec
certitude si un chargement et supportable par la structure ou pas. Ces éléments sont justement une loi de
comportement plastique qui doit satisfaire une condition en mécanique, connue sous le terme « règle de
normalité ». Pour plus de détails, on renvoie le lecteur aux travaux de Halphen et Nguyen (1975). Le
problème qui se pose pour les structures maçonnées est que, a priori, le matériau constitutif « maçonnerie »
ne respecte pas cette condition mécanique. Alors, la connaissance partielle sur la stabilité de la structure n’est
pas seulement une dérive du Calcul à la Rupture mais c’est plutôt une caractéristique intrinsèque du matériau
maçonnerie. Pour les matériaux qui ne respectent pas la règle de normalité, les charges supportables par la
structure dépendent également de l’histoire de chargement et l’adoption d’une méthode de type « suivi du
trajet de chargement » est indispensable afin de vérifier la tenue de la structure. Un exemple de ce
phénomène est en fait fourni par les résultats de la Figure 1.12. Si l’on reste à un nombre limité de cycles de
chargement on voit bien que le chargement ultime prend des valeurs de l’ordre de 40kN. Par contre, si le
phénomène d’adoucissement est activé, la résistance baisse à 15kN. Alors, la charge de 40kN est
potentiellement supportable, à condition que l’on reste à un nombre limité de cycles de chargement.

<!-- p. 46 -->

1.2 Modélisations des structures maçonnées 23

1.2.2 Modélisations des structures maçonnées à l’échelle

microscopique

Suite à la considération de la maçonnerie en tant que matériau homogène vu à l’échelle de la
structure, on examine brièvement dans ce paragraphe les méthodes principales pour la modélisation de la
maçonnerie à l’échelle de ses éléments constitutifs. Le matériau est désormais considéré comme un milieu
hétérogène et chaque phase (blocs de pierre, briques, mortier, joints) est modélisée explicitement du point de
vue mécanique. Comme remarque Acary (2001), les modélisations micromécaniques se distinguent dans
deux grandes classes qui consistent à considérer le matériau soit comme un milieu continu soit comme un
milieu discret. Un point commun dans les deux classes de modélisations est bien évidemment l’exigence
d’une description très fine de la géométrie de la structure, et en particulier des joints séparant les blocs de
pierre ou les briques de la maçonnerie. Cette tâche est facilitée par la mise en œuvre de méthodes
photogrammétriques (cf. paragraphe 1.5.3).

Concernant les méthodes du type « milieu continu », on notera qu’elles se basent sur une définition
d’un modèle mécanique pour les blocs et les joints de la maçonnerie séparément sans toutefois lever
l’hypothèse de la continuité de la maçonnerie. Les modèles adoptés appartiennent en général aux familles
mentionnées dans le paragraphe précédent : modèles élastiques, élastoplastiques, élastoplastiques avec
adoucissement etc. Le point délicat dans ce type de modélisation est le modèle à adopter pour les joints de la
maçonnerie. Les joints sont les zones les plus faibles de la structure et donc les lieux de développement de
fissures, de déformations irréversibles et de dissipation d’énergie dans la structure. On trouve dans la
littérature, des modèles sophistiqués pour les joints de la maçonnerie comme celui proposé par Lourenço et
al. (1997) ou celui de Giambanco et al. (1997), qui va jusqu’à la prise en compte de notions de tribologie pour
caractériser le comportement mécanique des joints.

Les méthodes de type « milieu discret » se réfèrent à l’application de la méthode aux éléments
distincts (ou discrets) (Discrete Element Method) dans la modélisation des maçonneries. Pour une revue
détaillée de la méthode le lecteur peut se référer aux travaux de Lemos (2007). La méthode consiste à
considérer la maçonnerie comme un ensemble de corps (souvent considérés parfaitement rigides) reliés les
uns aux autres par des lois d’interaction qui concrétisent le comportement des joints. La géométrie des joints
est réduite aux interfaces entre les blocs alors que les lois d’interaction garantissent surtout la noninterpénétration des blocs. Le grand avantage de cette méthode est qu’elle est très efficaces du point de vue
numérique et qu’elle est facilement implémentée à des problèmes dynamiques. Elle est bien adaptée pour les
maçonneries à joints vifs et elle permet de suivre l’évolution de la structure maçonnée jusqu’à la ruine et la
séparation du corps de la maçonnerie en blocs disjoints. La méthode a été utilisée avec succès dans la

<!-- p. 47 -->

24 1 Contexte du travail

modélisation des structures monumentales grecques anciennes sous sollicitations dynamiques. A titre,
d’exemple, citons les travaux récents de Papantonopoulos et al. (2002) et de Psycharis et al. (2003, Figure
1.13).

Figure 1.13 - Model aux éléments discrets de la structure colonne-architrave du Parthénon d’Athènes.

Déformations permanentes après une analyse sismique, extrait de Psycharis et al. (2003)

Une variante avancée de la méthode aux éléments discrets a été développée dans la thèse d’Acary
(2001). Cette variante utilise la théorie de la dynamique non régulière du contact (Non Smooth Contact
Dynamics : NSCD) pour la modélisation des structures maçonnées. Cette méthode est formulée dans le
contexte mathématique de la Mécanique non régulière (Non-Smooth Mechanics) (cf. Moreau et
Panagiotopoulos, 1988), théorie très technique qui sort des objectifs de cette thèse.

1.2.3 Approches multi-échelles – homogénéisation

On achève ce court aperçu des méthodes de modélisation des structures maçonnées avec un
commentaire sur les approches multi-échelles et leur théorie de base, qui est la théorie mécanique de
l’homogénéisation.

Les approches multi-échelles tentent à offrir un compromis entre les modélisations macroscopiques
et microscopiques. Elles peuvent s’appliquer lorsque l’on possède une connaissance suffisante de la
microstructure de la maçonnerie au lieu d’une analyse à l’échelle microscopique qui peut s’avérer très

<!-- p. 48 -->

1.2 Modélisations des structures maçonnées 25

coûteuse. La modélisation est effectuée en deux étapes : en premier, la structure est traitée à son échelle
microscopique où l’on essaie de reconnaître un volume représentatif, générateur de la structure globale. La
définition du volume représentatif peut être immédiate dans le cas d’une structure périodique (par exemple,
appareil régulier, Figure 1.14). Le volume représentatif comporte les phases hétérogènes de la structure, à
savoir les joints et les blocs de pierres ou les briques et est traité de manière à en tirer les propriétés
mécaniques d’un matériau homogène équivalent. Dans la deuxième étape de la modélisation, le matériau
homogène équivalent, défini en conformité avec la microstructure de la maçonnerie, est utilisée dans une
analyse de la structure à l’échelle macroscopique.

Figure 1.14 - Définition du volume représentatif

Le point délicat des approches multi-échelles est bien évidemment la définition du matériau
homogène équivalent à partir des propriétés mécaniques des phases hétérogènes dans le volume
représentatif générateur. Ce problème est traité au moyen de la théorie mécanique de l’homogénéisation,
sujet très riche qui sort du contexte de cette thèse. Le lecteur intéressé peut se référer aux ouvrages de base
de Zaoui (2000) ou de Torquato (2001).

On notera que la procédure de l’homogénéisation peut concerner la définition des caractéristiques de
déformabilité équivalentes (telles que les modules d’élasticité) ou bien des caractéristiques de résistance.
Anthoine (1995) fournit un exemple d’utilisation de la théorie d’homogénéisation pour la détermination des
propriétés élastiques équivalentes de murs de maçonnerie qui sont sollicités dans le plan.

Pour une application de la théorie d’homogénéisation dans le contexte du Calcul à la Rupture des
structures maçonnées, on peut citer les travaux de De Buhan et al. (1997). Leur approche consiste à résoudre

<!-- p. 49 -->

26 1 Contexte du travail

un problème de Calcul à la Rupture dans le volume représentatif, celui-ci vu comme une structure soumise à
des forces extérieures et possédant des caractéristiques de résistance connues. Les forces extérieures sont
identifiées avec les éléments du tenseur de contraintes (développés dans le volume du matériau
homogénéisé). Les critères de résistance adoptés sont une loi de frottement avec cohésion de type MohrCoulomb pour les joints et une résistance infinie pour les blocs de pierre. Le résultat de ce premier calcul est
de préciser le domaine de résistance du volume représentatif. Ce domaine est tracé dans l’espace des
éléments du tenseur de contraintes et définit toutes les combinaisons de contraintes admissibles dans le
volume représentatif (Figure 1.15, les contraintes principales sont notées avec Σ). Dans la deuxième étape de
la procédure, le domaine de résistance du volume représentatif est utilisé en tant que critère de résistance du
matériau homogène équivalent afin d’effectuer un Calcul à la Rupture à l’échelle macroscopique de la
structure.

Figure 1.15 – Domaine de résistance de la maçonnerie, extrait de De Buhan et al. (1997)

<!-- p. 50 -->

1.2 Modélisations des structures maçonnées 27

1.2.4 Conclusion sur les méthodes de modélisation des structures

maçonnées

Le bref aperçu des méthodes de modélisation des structures maçonnées présenté a révélé d’une part
la grande diversité des méthodes disponibles et d’autre part les exigences qui sont requises afin de mettre en
œuvre ces méthodes. En particulier, on a vu que les méthodes du Calcul à la Rupture permettent
d’investiguer la stabilité des structures maçonnées en n’utilisant que les caractéristiques de résistance de la
maçonnerie. Les méthodes qui font introduire une loi de comportement pour le matériau maçonnerie
deviennent très vite assez fastidieuses vu que la maçonnerie met en évidence un comportement non-linéaire
à partir de premiers incréments de chargement.

Visant à la plus grande généralité possible et au développement d’un outil à l’usage de spécialistes
de différents domaines intervenant au traitement des structures maçonnées, on adopte dans la suite les
approches du Calcul à la Rupture (permettant de s’affranchir de la connaissance de la loi de comportement et
de paramètres de déformabilité de la maçonnerie) ainsi que le critère général de résistance proposé par
Heyman (1995).

Les paragraphes suivants, 1.3 et 1.4, présentent successivement un exposé de la théorie du Calcul à
la Rupture et son application dans le contexte des structures maçonnées.

<!-- p. 51 -->

28 1 Contexte du travail

1.3 Présentation générale du Calcul à la Rupture

Le traitement du problème de la stabilité des structures maçonnées présenté ici s’effectue dans le
cadre de la théorie du Calcul à la Rupture. Une présentation exhaustive de la théorie du Calcul à la Rupture
se place hors des objectifs de cette thèse et le lecteur intéressé peut se référer aux travaux de Salençon
(Salençon 1983, 1990, 2002), qui fournissent la formulation mathématique stricte de la méthode ainsi qu’un
nombre abondant d’applications. On en donne ici une brève description.

La théorie du Calcul à la Rupture se construit en s’appuyant sur trois éléments de données et seulement sur
eux. Ces données sont :

\1. La connaissance de la géométrie de la structure examinée.

\2. La connaissance du chargement qui lui est appliqué.

\3. La connaissance des capacités de résistance de ses matériaux constitutifs.

On peut faire le commentaire suivant :

\- En ce qui concerne la géométrie de la structure examinée, on considère qu’elle est donnée une fois
pour toutes. La théorie du Calcul à la Rupture ne prend pas en compte les changements de la géométrie
d’une structure lors de son chargement à partir d’un état initial donné. En revanche, elle peut être appliquée
sur une géométrie déformée, pourvu que celle-ci soit donnée. Cette remarque est importante parce qu’elle
permet d’étendre les méthodes développées à des configurations de structures existantes qui mettent en
évidence des déformations non négligeables, des fissurations etc. Ceci dit, on insiste sur le fait que la
géométrie de la structure examinée, déformée et/ou fissurée ou pas, est donnée une fois pour toutes dès le
début.

\- La connaissance des capacités de résistance des matériaux constitutifs de la structure introduit une
condition nécessaire pour la stabilité de la structure. La stabilité de la structure est exprimée
mathématiquement par la compatibilité entre l’équilibre dans la structure et les conditions imposées par les
capacités de résistance de ses matériaux constitutifs. Ceci signifie que si la structure est stable sous un
chargement Q donné, il y a compatibilité entre l’équilibre quasi-statique sous ce chargement et les capacités
de résistance de la structure, mais que la réciproque n’est pas assurée. C’est-à-dire que les données
d’entrée pour la mise en œuvre du Calcul à la Rupture (éléments 1 à 3 mentionnés plus haut) ne suffisent pas
pour assurer définitivement qu’une structure est stable sous un chargement donné même si l’on peut montrer
que la compatibilité équilibre – résistance peut être possible.

\- On peut exprimer cette condition nécessaire de stabilité sous la forme :

<!-- p. 52 -->

1.3 Calcul à la Rupture 29

(1.1) Stabilité sous Q ⇒ Compatibilité équilibre – résistance

On observe qu’à elle seule la compatibilité entre l’équilibre quasi-statique sous un chargement Q et
les conditions imposées par les capacités de résistance de la structure, ne peut pas assurer que la structure
soit stable sous Q . C’est ainsi que l’on introduit la notion de la « stabilité potentielle » qui nous permettra
d’inverser la condition exprimée par (1.1):

(1.2) Stabilité « potentielle » sous Q ⇔ Compatibilité équilibre – résistance

1.3.1 La notion de la « stabilité potentielle » du Calcul à la Rupture

Afin d’éclaircir les notions mentionnées, nous présentons l’exemple qui suit en suivant l’exposé de
Salençon (1983) : nous examinons la structure réticulée représentée sur la Figure 1.16 : il s’agit d’un cadre
carré ABCD avec deux diagonales, articulé aux quatre sommets. Cette structure est soumise au mode de
chargement dépendant du paramètre Q , défini par deux forces égales et opposées appliquées en A et C.

Figure 1.16 – Cadre à dix barres

Les capacités de résistance, identiques pour chacune des barres constituant ce système sont
définies comme suit : les efforts N i dans chacune des barres doivent rester compris entre les valeurs + L
(traction) et − L (compression) :

(1.3) N i ≤ L, i = 1, 2 ,..., 6 ,

<!-- p. 53 -->

30 1 Contexte du travail

La question posée est alors de savoir, pour une valeur donnée du paramètre Q , si la structure sera
stable sous chargement compte tenu de la condition (1.3). Pour qu’il en soit ainsi, il est clair qu’il faut que le
système formé par les équations d’équilibre quasi-statique de la structure et les conditions (1.3) soit possible,
c’est-à-dire ait au moins une solution.

Les équations d’équilibre quasi-statique s’obtiennent en écrivant l’équilibre des nœuds A, B, C, D. Il
vient sans difficultés :

(1.4) N 1 = N 2 = N 3 = N 4

Pour simplifier on peut poser :

(1.5) N 1 = T , N 5 = U , N 6 = V

et il reste encore à écrire deux équations d’équilibre :

(1.6) U + T 2 = Q ,

(1.7) V +T 2 = 0 .

Il s’ensuit, à partir de (1.2), que la structure examinée est potentiellement stable si et seulement si le
système formé par les expressions (1.3), (1.6) et (1.7) a au moins une solution.

Les équations (1.6) et (1.7) permettent d’exprimer U et V en fonction du paramètre de chargement Q
alors que le paramètre T est choisi comme inconnue hyperstatique. Il s’agit donc d’un système avec trois
inconnues (U ,V ,T ), composé de deux équations ((1.6) et (1.7)) et des inégalités (1.3). Ce système peut
avoir une infinité de solutions, une unique solution ou aucune solution selon les valeurs des paramètres Q et
L . On voit que les éléments fournis pour la structure dans le contexte du Calcul à la Rupture, ne suffisent
pas pour une détermination explicite des efforts dans les barres sous le chargement imposé. Pour procéder,
on peut considérer les paramètres Q et T comme variables libres et déterminer à partir de (1.6) et (1.7) les
valeurs des paramètres U et V . Avec cette démarche on peut évaluer les valeurs de Q et T pour
lesquelles les conditions (1.3) sont satisfaites. Les résultats sont présentés sur la Figure 1.17 : dans le plan
(T, Q) on représente le domaine H . Ce domaine définit les combinaisons des paramètres Q et T pour
lesquelles le système des expressions (1.3), (1.6) et (1.7) a au moins une solution. Ce domaine est délimité
par les parties AB, BC, CD, DA. Lorsque Q et T sont sur ces parties droites, les conditions
correspondantes, présentées sur la Figure 1.17 , sont satisfaites. Au delà du domaine H , les conditions (1.3)
sont violées et la structure est instable.

La Figure 1.17 révèle que les chargements Q qui sont « potentiellement supportables » pour la
structure sont situés sur le segment K qui est la projection du domaine H sur l’axe Q :

<!-- p. 54 -->

1.3 Calcul à la Rupture 31

(1.8) K = [ − 2 L, + 2 L ] .

La structure est « potentiellement stable » si Q ∈ K . On peut distinguer les cas suivants :

\- L’« instabilité » de la structure est certaine pour tout chargement supérieur à 2L (ou inférieur à
− 2L ), c’est-à-dire qu’il n’est pas possible alors d’assurer l’équilibre quasi-statique du système en respectant
les conditions de résistance.

\- La stabilité est possible mais pas certaine si K ∈−[ 2 L, 2 L ] . En fait, elle dépend de la valeur du
paramètre hyperstatique T , comme il est montré sur la Figure 1.17.

On remarquera que, même si le domaine ( − L, + L ) représente le domaine de résistance de
l’élément, ce qui signifie que tout effort N tel que − L ≤ N ≤ + L sera supporté sans dommage par les
barres, il n’est pas possible d’affirmer que tout chargement Q tel que − 2 L ≤ Q ≤ +2 L , sera lui-même
supporté sans dommage par la structure. Pour donner une réponse définitive sur la stabilité de la structure
sous un Q donné, il faut être capable de préciser la valeur du paramètre hyperstatique T , ce qui ne peut pas
être fait sur la base de trois éléments d’information (géométrie, chargement, capacité) disponibles pour la
structure.

Figure 1.17 – Chargements « potentiellement supportables » pour la structure de la Figure 1.16

L’exemple présenté montre que, même si l’expression (1.2) fournit une réponse partielle, cette
réponse représente l’information maximale accessible au niveau de la structure à partir des données

<!-- p. 55 -->

32 1 Contexte du travail

disponibles. Le Calcul à la Rupture fournit alors les chargements potentiellement supportables pour une
structure en se basant exclusivement sur la connaissance de sa géométrie, sa procédure de chargement et
sa résistance, et cette partialité de la réponse constitue quand même la meilleure exploitation de ces trois
données. L’exemple présenté montre que la source de cette partialité de réponse sur la stabilité de la
structure a pour origine le fait que l’on ne peut pas déterminer les paramètres hyperstatiques de la structure et
que le domaine de la stabilité de la structure est fonction de ces paramètres inconnus.

Pour établir une réponse définitive sur la stabilité de la structure, la connaissance d’autres aspects de son
comportement est exigée, et plus précisément (Salençon, 1983) la connaissance de:

• La loi de comportement des matériaux constitutifs de la structure à l’intérieur du domaine de
résistance et lorsque les limites de résistances sont atteintes. Par exemple, dans le cas du carré
articulé présenté, et si l’on suppose que les barres obéissent à une loi de comportement élastique
parfaitement plastique associée, on peut déterminer uniquement le paramètre hyperstatique T et
ainsi avoir une réponse définitive sur la stabilité de la structure sous Q .

• L’état d’autocontrainte initial de la structure. Cet élément d’information est nécessaire pour prendre en
compte dans l’évaluation de la stabilité des effets tels que la précontrainte des éléments d’une
structure ou l’effet des déplacements induits aux supports de la structure.

• L’histoire du chargement de la structure, c’est-à-dire le trajet et l’horaire de parcours de son
chargement. Cet élément est nécessaire car la plupart des lois de comportement, tels que la loi
élastique-parfaitement plastique associée, sont dépendants de l’histoire du chargement

L’exemple de structure simplifiée présentée permet de souligner les aspects qualitatifs du traitement
d’un problème de stabilité de maçonnerie par la théorie du Calcul à la Rupture : en particulier, il n’est pas
nécessaire pour la mise en œuvre de la méthode de définir la loi de comportement de la maçonnerie ; ceci est
incontestablement un très grand avantage, sachant que le matériau « maçonnerie » (sous ses différentes
formes) peut présenter des comportements très variés. Il n’est également pas nécessaire de définir le trajet
de chargement, généralement inconnu, qui a été ou sera imposé dans une structure. Ce manque de données
a pour conséquence induite la définition d’une stabilité « potentielle » (au lieu de la certitude) qui toutefois
constitue une réponse suffisante au niveau pratique.

Pour ce qui est de la description du chargement du système, il suffit d’exprimer la procédure du
chargement dans la structure à partir d’un nombre fini de paramètres de chargement (paramètres
hyperstatiques) au moyen desquels, il sera possible d’exprimer complètement l’état de forces (ou de
contraintes) dans la structure.

<!-- p. 56 -->

1.3 Calcul à la Rupture 33

Finalement, le critère de résistance du matériau, dernière pièce d’information pour la mise en œuvre
de la méthode, devient pour la maçonnerie le critère de matériau sans traction de Heyman. Ce critère,
quoique approximatif est très satisfaisant pour la description de la grande majorité des structures maçonnées.

1.3.2 La mise en œuvre du Calcul à la Rupture

L’exemple présenté au paragraphe précédent nous permet de définir et de discuter les notions
principales du Calcul à la Rupture et les méthodes de sa mise en œuvre.

1.3.2.1 Le domaine K

La première notion introduite dans le Calcul à la Rupture est celle du domaine K de la structure
examinée. Le domaine K , comme dans l’exemple présenté, désigne l’ensemble de tous les chargements
« potentiellement supportables » par la structure. Dans le cas général d’une structure tridimensionnelle, Il
résulte de (1.2) qu’un chargement Q appartient à K si et seulement s’il existe un champ de contraintes
σ( xG ) dans la structure qui satisfait l’équilibre vis-à-vis de Q et ne viole pas les conditions imposées par les
capacités de résistance des matériaux constitutifs de la structure. Ces dernières sont exprimées dans le cas
général par un domaine G( xG ) fonction de la position xG dans la structure. Le domaine G( xG ) délimite les
valeurs admissibles pour les contraintes σ( xG ) dans le sens que σ( xG ) doit appartenir à G( xG ) pour que la
structure soit stable. Vu que le tenseur des contraintes σ( xG ) est composé de six éléments distincts, le
6 .domaine G( xG ) est un sous ensemble de l’espace de dimensions 6, R

Concernant le domaine K on peut faire les remarques suivantes :

a. Dans la pratique du Calcul à la Rupture, le chargement d’une structure dépend d’un nombre fini de
paramètres n (Salençon et al. 1981). Par exemple, dans le cas du carré articulé examiné (cf. paragraphe
1.3.1), n = 1 , puisque le chargement de la structure est entièrement défini par la connaissance de la valeur
de la force Q . Ainsi, dans le cas général, chaque chargement examiné peut s’écrire comme une combinaison
linéaire de n paramètres de chargement distincts. On peut toutefois noter que si le mode de chargement
d’une structure dépend de n paramètres, chaque chargement possible peut être exprimé sous forme d’un
vecteur Q ∈ R n , où n est le nombre de paramètres de chargement. Il s’ensuit que K est un sous-ensemble
de l’espace R n : K ⊂R n . Par exemple, si n = 1 , K est un segment de la ligne des nombres réels (comme
sur la Figure 1.17); si n = 2 , K est une partie du plan R 2 etc.

<!-- p. 57 -->

34 1 Contexte du travail

b. Par définition, le domaine K est directement issu du domaine de résistance du matériau constitutif
de la structure. Pour les applications à la mécanique de la maçonnerie, le critère de résistance le plus
commun est le critère du matériau sans traction. Ce critère définit un domaine, dans l’espace des
contraintes R 6 , qui est convexe (cf. paragraphe 1.4.1). Étant donné que le domaine G( xG ) des contraintes
admissibles est convexe, il n’est pas difficile de démontrer que K est convexe aussi dans R n (Salençon,
1983).

c. Comme K contient tous les chargements « potentiellement supportables », il s’ensuit que tout
chargement extérieur à K entraînera, à coup sûr, l’instabilité. D’un point de vue pratique, il peut être très utile
de connaître les chargements qui se trouvent sur la frontière du domaine K : ces modes s’appellent
chargements extrêmes du système et sont notés par Q× . La frontière du domaine K s’appelle aussi
surface ultime.

Le Calcul à la Rupture se met en œuvre par trois approches différentes, qui sont présentés dans les
paragraphes suivants.

1.3.2.2 L’approche statique par l’intérieur

Dans l’approche statique par l’intérieur du Calcul à la Rupture, on essaie de construire une
approximation « par défaut » de la frontière du domaine K . L’approche se fonde sur la convexité du domaine
K , et sur le fait que si l’on peut construire un champ de contrainte σ( xG ) qui ne viole pas les conditions
imposées par la résistance du matériau constitutif en aucun point de la structure et s’équilibre avec un
chargement Q , alors Q appartient à K . Supposons que l’on ait ainsi mis en évidence p chargements
Q1 , Q 2 , … , Q p dans K . La convexité de K permet d’affirmer que l’enveloppe convexe de ces chargements
constitue une borne inférieure de la frontière de K . On illustre cette idée sur la Figure 1.18.

Or, on peut formuler cette procédure d’approximation « par défaut » de la frontière du domaine K
par un principe variationnel correspondant. Ceci signifie pratiquement que l’on remplace le problème initial
par un problème d’optimisation. Une méthode pour procéder est de définir, pour un chargement Q * ∈ K , le
mode de chargement radial comme l’ensemble λQ * avec λ un nombre réel, et d’effectuer, pour le champ
de contrainte λσ*( xG ) qui lui correspond, la majoration suivante :
(1.9) trouver la plus grande valeur λs de λ, tel que le champ λσ*( xG ) est statiquement admissible

Cette procédure d’approximation du domaine K est représentée sur la Figure 1.18.

<!-- p. 58 -->

1.3 Calcul à la Rupture 35

Figure 1.18 - Approximation par l’intérieur de la frontière du domaine K

Notons que l’exemple du carré articulé, présenté dans le paragraphe 1.3.1, a été traité avec
l’approche statique par l’intérieur.

1.3.2.3 L’approche statique par l’extérieur

En inversant la logique de l’approche statique par l’intérieur, on peut pratiquement obtenir une
approximation « par excès » de la surface ultime en montrant que l’équilibre global (l’équilibre au sens de la
mécanique des solides indéformables) d’un sous-système de la structure est impossible à assurer sous un
chargement donné compte tenu des conditions imposées par les capacités de résistance de la structure. On
appelle cette méthode, approche statique par l’extérieur. Avec cette approche on construit des points à
l’extérieur de la frontière du domaine K (par exemple, Q1 , Q 2 , … , Q p ) comme présenté sur la Figure 1.19.
L’approximation de K uniquement par l’approche statique par l’extérieur n’est pas très commode (sauf pour
le cas unidimensionnel), puisque la convexité par rapport aux points obtenus n’est pas valable. L’application
de l’approche statique par l’extérieur dans l’exemple du carré articulé (cf. paragraphe 1.3.1) peut se faire en
considérant les efforts dans les barres de la structure qui correspondraient à un état de ruine de la structure et
en écrivant les conditions d’équilibre avec le chargement imposé. Si l’on considère par exemple le cas de
ruine où les deux barres diagonales sont endommagées, il s’ensuit que :

(1.10) T = 0.707 L,U = L,V = − L

et la force de chargement qui correspond à cette configuration d’efforts dans les barres vaut :

(1.11) Q = 2 L

<!-- p. 59 -->

36 1 Contexte du travail

Selon la théorie du Calcul à la Rupture, la valeur du paramètre de chargement Q dans l’expression
(1.11) constitue une approximation par excès du chargement ultime de la structure. Or, on a déjà montré par
l’approche statique par l’intérieur que la même valeur constitue une approximation par défaut. On a donc
prouvé en combinant les deux méthodes (par l’intérieur et par l’extérieur) que la valeur Q = 2 L est un
chargement extrême pour la structure dans le sens du paragraphe 1.3.2.1. Cet exemple a montré d’une part
une application de l’approche statique par l’extérieur du Calcul à la Rupture et d’autre part, comment on peut
combiner deux méthodes du Calcul à la Rupture afin d’obtenir une très bonne approximation (voire une
estimation exacte) de la frontière du domaine K des chargements potentiellement supportables.

Figure 1.19 - Approximation de la frontière du domaine K par l’approche statique par l’extérieur

1.3.2.4 L’approche cinématique par l’extérieur

L’approche cinématique par l’extérieur est la troisième et dernière méthode de la mise en œuvre du
Calcul à la Rupture. La méthode fournit, comme au cas précédent, une approximation « par excès » de la
frontière du domaine K , qui peut s’obtenir (Salençon, 1983, 2002) à partir de la dualisation mathématique de
la condition de compatibilité équilibre – résistance.

L’obtention d’un principe dual dans ce contexte s’appuie sur le principe des puissances virtuelles.
La méthode se concrétise par la combinaison du principe des puissances virtuelles avec la connaissance du
domaine de résistance du matériau constitutif de la structure ; la combinaison de ces données conduit à
l’évaluation de la « puissance résistante maximale » de la structure vis-à-vis d’un champ de vitesses virtuel

<!-- p. 60 -->

1.3 Calcul à la Rupture 37

donné. Si la puissance d’un chargement Q , dans un champ de vitesse virtuel est supérieure à la puissance
résistante maximale, il en résulte que ce chargement ne peut pas être supporté par la structure. L’étude de
plusieurs champs de vitesses virtuels et la mise en évidence de chargements non supportables par la
structure fournissent une approximation « par excès » des chargements extrêmes.

Dans une logique similaire à celle de l’approximation « par défaut », on peut établir le principe
variationnel qui dérive de l’approche cinématique par l’extérieur. Dans ce cas, on cherche à minimiser une
certaine fonction objectif qui respecte les conditions imposées par la résistance et obéit au principe des
puissances virtuelles.

En pratique, la méthode se déroule comme suit : a. on définit la géométrie, la résistance et le
chargement de la structure, b. on introduit un grand nombre de mécanismes potentiels de rupture (souvent
ces mécanismes sont paramétrés à un nombre fini de paramètres géométriques), c. pour chaque mécanisme
on évalue la puissance des efforts extérieurs et la puissance des efforts intérieurs (ayant un effet stabilisant),
d. en écrivant l’égalité entre la puissance de efforts extérieurs et la puissance des efforts intérieurs pour
chaque mécanisme de rupture, on obtient une approximation par excès des charges extrêmes de la structure
et e. parmi les mécanismes de rupture considérés, on retient celui qui fournit les valeurs minimales des
charges extrêmes. On note que l’approche cinématique par l’extérieur fournit des bornes supérieures pour les
charges extrêmes de la structure. Par conséquent, ses résultats ne vont pas dans le sens de la sécurité.

L’approche cinématique par l’extérieur, en dépit du fait qu’elle fournit des résultats qui ne sont pas
conservatifs est néanmoins utilisée largement dans la pratique. Son grand avantage par rapport à l’approche
statique par l’intérieur est qu’elle exige la définition d’un mécanisme de rupture optimal dans la structure,
c’est-à-dire, d’un champ de vitesses. La définition d’un champ de vitesses, étant un champ vectoriel, est en
général plus facile que la définition d’un champ de contraintes (champ tensoriel) qui peut s’avérer très difficile
à établir, surtout pour les problèmes de stabilité tridimensionnels (Tableau 1.2).

Problème Approche statique Approche cinématique
2d σxx, σyy, σxy ux, uy
σxx, σyy, σzz, 3d ux, uy uz σyy, σxz, σyz,

Tableau 1.2 - Quantités à définir dans chaque point d’une structure

<!-- p. 61 -->

38 1 Contexte du travail

1.4 Application du Calcul à la Rupture aux structures
maçonnées

Ayant fourni une description générale de la théorie du Calcul à la Rupture dans les paragraphes
précédents, on précise ici les éléments nécessaires pour l’application de la théorie dans le cas des structures
maçonnées.

1.4.1 Critère de résistance

On commence notre exposé avec le critère de résistance adopté dans cette thèse pour les structures
maçonnées. Ce critère a été utilisé dans la totalité des analyses présentées ici.

On définit tout d’abord la convention des signes pour les contraintes en compression et en traction :
on considère que les contraintes sont positives en compression. Ceci est en fait l’inverse de la règle
habituellement adoptée dans la mécanique du milieu continu. Cette convention est cependant plus commode
dans le contexte des structures maçonnées, puisqu’on ne permettra que des contraintes en compression
dans ces structures.

Le critère de résistance adopté ici n’est autre que le critère de matériau sans traction d’Heyman
(1995). Le matériau constitutif de la maçonnerie a une résistance infinie en compression et en cisaillement (le
glissement n’est permis en aucune interface) et une résistance nulle à la traction.

Dans la suite on considère une structure générique tridimensionnelle homogène qui est constituée du
matériau obéissant au critère décrit. Notons que la structure étant homogène, seule l’orientation du
découpage de la maçonnerie en blocs et joints est utilisée. Le critère de matériau sans traction comporte
implicitement la « microstructure » de la maçonnerie. C’est un critère qui se réfère à l’échelle macroscopique
de la maçonnerie (niveau structure).

Le manque de résistance à la traction implique que, sur une interface arbitraire dans la structure, le
Gvecteur-contrainte T et le vecteur unitaire normale nG (pris positif exerçant une compression sur l’interface)
doivent satisfaire l’expression suivante :
G G(1.12) n ⋅ T ≥ 0 , pour chaque direction nG

Ceci est représenté dans la Figure 1.20.

<!-- p. 62 -->

1.4 Calcul à la Rupture et structures maçonnées 39

Figure 1.20 - Interface arbitraire dans une structure constituée de matériau sans traction

En introduisant le tenseur de contraintes σ au moyen de la règle de tétraèdre de Cauchy, on a
G G
T = σ ⋅ n , d’où on obtient :

G G (1.13) n ⋅ ( σ ⋅ n ) ≥ 0 , pour chaque direction nG

L’expression (1.13) fournit la condition nécessaire et suffisante que le tenseur de contraintes doit
satisfaire afin qu’il soit compatible avec le critère de résistance d’Heyman. En fait, l’expression (1.13) n’est
autre que la définition des matrices semi-définies positives. Il s’ensuit que dans les structures constituées du
matériau sans traction, le tenseur des contraintes doit être représenté, en tous les points de la structure, par
une matrice semi-définie positive.

Pour le tenseur de contraintes général σ une représentation graphique de la condition obtenue n’est
pas commode, puisqu’elle exige la définition des six composantes du tenseur des contraintes. Or, on peut
définir pour chaque tenseur de contraintes, le tenseur associé des contraintes principales. Ce tenseur est
représenté par une matrice diagonale dont les composantes sont les valeurs propres ( σi avec i = 1,2,3 ) du
tenseur de contraintes initial.

Un théorème connu de l’algèbre linéaire affirme que les valeurs propres d’une matrice semi-définie
positive symétrique doivent être non-négatives :

(1.14) σi ≥ 0, i = 1,2,3

L’expression (1.14) permet une représentation graphique du critère du matériau sans traction dans
l’espace des contraintes principales. Chaque point de cet espace correspond à un triplé (σ1 ,σ2 ,σ3 ) .

<!-- p. 63 -->

40 1 Contexte du travail

L’ensemble des triplés admissibles pour le critère du matériau sans traction peut être identifié avec le premier
octant (octant positif) de l’espace des contraintes principales, comme il est présenté dans la Figure 1.21.

Figure 1.21 - Représentation du critère de résistance du matériau sans traction dans l’espace des contraintes

principales

1.4.2 Critère de résistance - Structures curvilignes planes

Il est intéressant d’examiner les implications de l’adoption du critère de résistance sans traction dans
le cas d’une structure curviligne plane. On utilise le terme «plane» pour désigner une structure qui s’étend
dans deux dimensions de l’espace et le terme « curviligne » pour désigner une structure plane mettant en
évidence une forme élancée et suggérant une modélisation unidimensionnelle, définie par une courbe
directrice : les arcs, les arcs-boutants, les piliers de maçonnerie et tout système constitué de ces éléments
(par exemple, systèmes obtenus par des sections d’une structure réelle tridimensionnelle) appartiennent à
cette catégorie de structures.

Une structure de ce type est représentée dans la Figure 1.22. La courbe directrice de cette structure
est paramétrée par la coordonnée s (abscisse curviligne). On définit aussi la coordonnée q , orthogonale à
s . Dans chaque position de la courbe directrice on définit l’épaisseur de la structure h ( s ) .

On peut supposer sans perte de généralité que la courbe directrice est identifiée avec la fibre
moyenne de la structure, c’est-à-dire les points le long de l’intrados ont la coordonnée q = − h / 2 et le long
de l’extrados q = + h / 2 , où h est fonction de s .

<!-- p. 64 -->

1.4 Calcul à la Rupture et structures maçonnées 41

Figure 1.22 – Structure curviligne bidimensionnelle

On suppose que la structure est constituée d’un matériau obéissant au critère de résistance de
Heyman. Si la structure est soumise à un chargement externe, les contraintes développées dans son volume
satisfont les expressions (1.13) et (1.14).

Dans chaque position de la courbe directrice on peut définir les quantités suivantes :

h / 2 G G
(1.15) N ( s ) = ∫− h /2 n ( s ) ⋅ ( σ ⋅ n ( s ) ) d q
h /2 G G
(1.16) M ( s ) = ∫− h / 2 n ( s ) ⋅ ( σ ⋅ n ( s ) ) q d q
Dans les expressions précédentes, nG (s ) représente le vecteur unitaire tangent à la courbe directrice.
L’intégration du tenseur de contraintes est effectuée sur une section perpendiculaire à la courbe directrice.

La quantité N ( s ) dans (1.15) représente l’effort normal (dans le sens de la mécanique de poutres)
exercé au point s sur la courbe directrice. Similairement la quantité M ( s ) dans (1.16) n’est autre que le
moment fléchissant au point s .

Définissons également l’excentricité e par l’expression :

M ( s )
(1.17) e ( s ) =
N ( s )

L’excentricité e ( s ) représente la distance à partir de la courbe directrice où l’on doit appliquer une
force N ′( s ) (de module et de direction identiques à N ( s ) ) afin d’équilibrer l’ensemble N ( s ) , M ( s ) qui est
exercé sur la courbe directrice.

L’adoption du critère de résistance conduit à une condition pour l’excentricité e ( s ) . Ecrivons la
valeur absolue du moment fléchissant :

h / 2 G G
(1.18) M ( s ) = ∫− h / 2 n ( s ) ⋅ ( σ ⋅ n ( s ) ) q dq

<!-- p. 65 -->

42 1 Contexte du travail

G G G Le fait que n ⋅ ( σ ⋅ n ) ≥ 0 , pour chaque direction n (cf. équation (1.13)) combiné avec le fait que q
prend des valeurs positives et négatives, implique la majoration suivante :

h / 2 G G
(1.19) M ( s ) = ∫− h /2 n ( s ) ⋅ ( σ ⋅ n ( s ) ) q dq

h /2 G G
≤ ∫− h / 2 n ( s ) ⋅ ( σ ⋅ n ( s ) ) q dq
h h /2 G G
≤ ∫− h /2 n ( s ) ⋅ ( σ ⋅ n ( s ) ) d q 2
(1.13)
h h / 2 G G
\= ∫− h /2 n ( s ) ⋅ ( σ ⋅ n ( s ) ) d q 2
h
\= N ( s )
2
Il s’ensuit que l’excentricité e ( s ) doit satisfaire :

M ( s ) h
(1.20) e ( s ) = ≤
N ( s ) 2

La signification de (1.20) est la suivante : le point d’application de l’effort normal résultant N ′( s ) ne
peut pas être à l’extérieur du contour de la structure. Il s’agit d’une condition très utile du point de vue pratique
puisqu’elle traduit les critères (1.13) et (1.14) dans un critère géométrique particulièrement simple. Ce résultat
est amplement utilisé dans les analyses de cette thèse qui se basent sur l’application de l’approche statique
par l’intérieur aux structures maçonnées en construisant la ligne de pression (cf. paragraphe 1.4.3).

Notons que le développement présenté pour les structures curvilignes planes peut être généralisé
aux structures curvilignes tridimensionnelles (voir par exemple, Lucchesi et al. 2008).

On notera également que dans le développement présenté on n’a guère fait appel à l’effort tranchant
développé sur une section de notre structure. L’hypothèse d’une résistance en cisaillement supposée toujours
suffisante permet en fait de s’affranchir de l’évaluation de l’effort tranchant.

1.4.3 Mise en œuvre de l’approche statique par l’intérieur pour les

structures maçonnées curvilignes - La notion de « la ligne de
pression »

L’approche statique par l’intérieur pour une structure maçonnée curviligne plane se base sur la
considération de la structure en équilibre, l’application des équations d’équilibre et la construction de la ligne

<!-- p. 66 -->

1.4 Calcul à la Rupture et structures maçonnées 43

de pression. Appliquée à des structures constituées du matériau sans traction, elle fournit la base cohérente,
du point de vue mécanique, pour la formulation des notions des minima et des maxima (initialement
introduites par Coulomb, 1773) de grandeurs physiques caractérisant la stabilité d’une structure (notions telles
que la poussée, la butée etc.).

Il semble que Hooke (1675) ait eu l’intuition de la ligne de pression lorsqu’il a décrit l’analogie entre le
comportement d’un arc en maçonnerie et d’une chaîne suspendue. L’équilibre de la chaîne est atteint à cause
de la capacité de son matériau à résister à la traction développée par son poids propre. De la même manière,
l’arc maçonné est en équilibre, mais travaille en compression. Dans son expérience pour étudier la stabilité de
la coupole de St Pierre à Rome, Poleni (1748) a divisé la section verticale de la coupole en plusieurs tranches
et, ensuite, il a simulé leur comportent sous poids propre en utilisant le modèle d’une chaîne suspendue
mettant en évidence la même répartition des masses. Si la courbe inversée formée par la chaîne est
contenue dans les contours de l’arc, la stabilité de l’arc est assurée. L’idée de la chaîne suspendue a inspiré
une représentation des états de contraintes dans une structure maçonnée curviligne connue aujourd’hui sous
le terme « ligne de pression ».

On peut trouver des exemples d’application de la ligne de pression dans la conception des structures
maçonnées1. Dans la Figure 1.23 on présente deux arcs-boutants (à gauche et à droite : ancienne et nouvelle
construction respectivement) de l’église de Saint Jacques-du-Haut-Pas à Paris (17ème siècle). La position des
blocs de pierre montre l’existence, dans l’épaisseur de chaque arc-boutant, d’éléments dont la forme
correspond à une ligne de pression (anticipant un état passif pour l’arc-boutant, cf. paragraphe 2.2.1.1). Ces
éléments sont utilisés, probablement, afin de renforcer la maçonnerie et contribuer à une meilleure répartition
de charges (comportement similaire à celui d’un arc de décharge). Une autre explication de la création d’une
telle forme se base sur le fait que les arcs-boutants sont construits en plusieurs phases.

1 La première utilisation de l’idée d’équivalence entre l’arc maçonné et la chaîne suspendue pour la conception d’une

structure réelle, est dans la construction du Pont Sainta Trinita à Florence (16ème siècle). Celle-ci peut alors être

considérée comme la première application dans la conception de « la ligne de pression » (Benvenuto 1991, p.328).

<!-- p. 67 -->

44 1 Contexte du travail

Figure 1.23 – « Lignes de pression » en maçonnerie dans deux arcs-boutants (ancienne et nouvelle construction)

de l’église St Jacques-du-Haut-Pas, Paris

D’après Timoshenko (1953) la première définition de ce que l’on appelle aujourd’hui la ligne de
pression a été donnée par Gerstner (1831) qui a utilisé le terme « ligne de résistance » (en anglais : line of
resistance). La ligne de résistance de Gerstner correspond au polygone qui est formé par les centres de
pression sur chacun des plans des joints1. La ligne de résistance de Gerstner est devenue dans les
travaux du 20ème siècle (par exemple, dans les travaux de Heyman) « the line of thrust » dont la traduction
courante en français est « ligne de pression ».

Cette ligne ne doit pas être confondue avec une deuxième ligne, connue dans la littérature du 19ème
siècle sous le même nom : « ligne de pression » (en anglais : line of pressure). La définition de cette
deuxième ligne est le lieu géométrique de l’intersection consécutive des directions des pressions
résultantes sur les joints2. Après l’interprétation des méthodes empiriques et graphiques anciennes dans le
contexte de la théorie du Calcul à la Rupture avec les travaux d’Heyman, seule la notion de « line of thrust ==
ligne de pression » est retenue dans la littérature alors que l’utilisation de la deuxième ligne (line of pressure)
n’est plus utilisée.

1 “The line of resistance is a polygon that connects the centres of pressure of the planes of the joints” (Benvenuto,

1991).

2 “The line of pressure is the locus of the consecutive intersections of the directions of the resultant pressures upon the

joints” (Benvenuto, 1991).

<!-- p. 68 -->

1.4 Calcul à la Rupture et structures maçonnées 45

Moseley (1833) a étudié et distingué les propriétés différentes de ces deux lignes alors
que Milankovitch (1907) en a donné un traitement mathématique complet. Les deux lignes coïncident quand
l’intersection de deux résultantes développées sur les joints d’un voussoir forme un angle obtus (Kurrer,
2008). Heyman (2009) note que la chaîne suspendue avec un poids spécifique peut représenter en même
temps la ligne de résistance de Gestner et la ligne de pression (contexte du 19ème siècle) d’un arc
monolithique si elle est parfaitement flexible, c’est-à-dire si l’on considère un nombre infini de joints.

Cependant, la notion contemporaine de la ligne de pression correspond au lieu géométrique des
points d’application des forces résultantes des contraintes développées à chaque joint. Ochsendorf
(2002) donne la définition : lieu géométrique des points de pression1. Dans le schéma de Moseley (Figure
1.24), on aperçoit, donc, que la notion contemporaine de la ligne de pression peut être attribuée plutôt à la
ligne de résistance, définie, qu’à sa ligne synonymique (une ambigüité qui n’existe pas en anglais où le nom
line of thrust est couramment utilisé).

Figure 1.24 – Les notions de la « ligne de résistance » et de la « ligne de pression » en 1830 (extrait de Moseley)

Il est intéressant de noter que la ligne de résistance de Gerstner/Moseley a été appelée par Méry
(1840) « courbe des pressions ». Viollet-le-Duc (1856) dans la catégorie « construction-voûte » de son
dictionnaire utilise le même terme. Victor Fournié (1864) l’utilise aussi dans sa traduction du traité de Schefler

1 “Locus of pressure points” (Ochsendorf, 2002).

<!-- p. 69 -->

46 1 Contexte du travail

(1858) sur la stabilité des constructions. Le terme « pressions » est utilisé pour désigner les forces
compressives résultantes sur chaque joint. Parmi les auteurs français on trouve le terme « ligne de centres de
pression » (Delbecq, 1982), ainsi que le terme « ligne des poussées » (Coste, 1997) qui est plus proche du
terme anglais line of thrust.

On notera, aussi, que la définition contemporaine de la ligne de pression due à Ochsendorf (2002) ne
peut être utile au niveau pratique que pour des structures dont les positions des joints sont précisément
connues. Dans le cas d’une structure monolithique ou d’une structure dans laquelle la position exacte des
joints n’est pas connue, ou finalement si l’on veut avoir une définition de la ligne de pression indépendante de
la connaissance de la position des joints, on fera appel à la méthode développée au paragraphe 1.4.2. On y a
montré que le critère de résistance du matériau sans traction peut être transformé dans un critère
géométrique se référant à la grandeur « excentricité », dont une définition mathématique stricte a été donnée
dans le même paragraphe pour les structures maçonnées curvilignes planes. On définit alors la « ligne de
pression » comme le lieu géométrique des points sur chaque section transversale (section
perpendiculaire à la courbe directrice de la structure) dont la distance depuis la courbe directrice
correspond à l’excentricité de la force normale résultante qui passe dans cette section.

Avec cette définition de « la ligne de pression » on peut utiliser directement le critère de résistance
géométrique établi dans le paragraphe 1.4.2 : la ligne de pression doit être contenue dans les contours
géométriques de la structure pour en assurer la stabilité. On voit également que s’il y a des sections
transversales de la structure, perpendiculaires sur la courbe directrice de la structure et qui coïncident avec
les joints de la structure, la définition proposée est équivalente à la définition d΄Ochsendorf (2002).

1.4.3.1 Les méthodes de construction de la ligne de pression

Les paragraphes 1.4.2 et 1.4.3 suggèrent que la construction de la ligne de pression dans une
structure maçonnée et curviligne plane peut servir comme moyen de mise en œuvre de l’approche statique
par l’intérieur du Calcul à la Rupture pour des structures dont le matériau constitutif obéit au critère de
résistance du matériau sans traction de Heyman.

On dirait que c’est effectivement en ce point, la grande efficacité et le succès de ce critère de
résistance : d’une part il retient les caractéristiques essentielles du comportement mécanique de la
maçonnerie et d’autre part, son adoption pour une structure curviligne plane, où l’on peut représenter les états
de contrainte (cf. Tableau 1.2) dans toute section transversale au moyen de la construction de la ligne de
pression, conduit à une transformation du critère de résistance en un critère géométrique particulièrement

<!-- p. 70 -->

1.4 Calcul à la Rupture et structures maçonnées 47

simple. La simplicité frappante de ce critère géométrique permet à la fois une vérification immédiate de la
stabilité si l’on a construit la ligne de pression et aussi la détection des zones susceptibles
d’endommagement, si le critère géométrique n’est pas satisfait.

En utilisant comme structure de référence un arc en plein cintre, on présentera trois méthodes de
construction de la ligne de pression. Dans ces méthodes l’arc est considéré comme un assemblage des
blocs-voussoirs et la position de ces joints est précisément connue. L’idée de base des trois méthodes est de
considérer que les voussoirs se comportent comme des corps rigides et d’écrire les équations d’équilibre de
forces et de moments pour chaque bloc-voussoir. La ligne de pression ainsi obtenue exprime alors l’équilibre
de chaque voussoir et fait que les trois méthodes sont équivalentes. La différence entre les trois méthodes
consiste à écrire les équations d’équilibre pour des différents types des voussoirs (première méthode : taille
variable d’un voussoir et deuxième - troisième méthode : arc discrétisé à un nombre fixe des voussoirs). La
ligne est définie aux joints par les deux premières méthodes et relativement à la ligne d’action du poids propre
des blocs par la troisième.

a) La méthode d’une portion circulaire de dimensions variables

La première méthode se concrétise avec l’équation proposée par Moseley (1833) permettant de
tracer la ligne de pression pour l’arc en plein cintre décrit dans un système des coordonnées polaires (θ, ρ).
L’équation considère l’équilibre d’une portion circulaire ABCD de l’arc en plein cintre, disons un voussoir de
dimensions variantes (Figure 1.25). Cette portion est définie par deux joints radiaux (ils peuvent être réels ou
fictifs) faisant les angles θ1 et θ2 avec l’axe Ox comme il est présenté sur la Figure 1.25. On considère
G
l’équilibre de la portion sous l’effet de son poids propre et soit la réaction R1 appliquée au point M1 (ρ1, θ1) le
long du côté AB. En écrivant l’équilibre des forces dans les directions horizontale et verticale, on détermine la
G G
réaction R2 appliquée le long du côté CD. Le point d’application M2 (ρ2, θ2) de la réaction R2 est déterminé
en prenant l’équilibre des moments autour du point M2 :
VG x − R1 x ρ1 sin θ1 − R1 z ρ1 cosθ1(1.21) ρ2 =
(V − R1 z )cosθ2 − R1 x sin θ2
G
où R1x et R1z sont respectivement les composantes horizontale et verticale de la réaction R1 . Le
G
poids propre V de la portion et l’abscisse du centre de gravité Gx de la portion sont fonctions des rayons
intérieur Rint et extérieur Rext de la portion ainsi que des angles θ1 et θ2.

<!-- p. 71 -->

48 1 Contexte du travail

Figure 1.25 – Equilibre de la portion d’un arc en plein cintre utilisé pour la construction de la ligne de pression

(première méthode)

b) La méthode d’un nombre fixe des voussoirs

Dans le cas où l’arc est constitué d’un nombre fixe des voussoirs de dimensions connues, la méthode
de Moseley permettant de tracer la ligne de pression consiste à écrire les équations d’équilibre à chaque
voussoir-bloc. Dans ce cas, les équations d’équilibre des forces et des moments combinées avec la
connaissance précise des formes des voussoirs et des positions des joints, permettent de préciser les points
d’application des forces résultantes qui se développent sur chaque joint. La procédure est illustrée sur la
Figure 1.26, qui représente un bloc arbitraire de l’arc. Notons que dans ce cas les blocs-voussoirs peuvent
avoir n’importe quelle forme et les joints ne doivent pas forcément être perpendiculaires à la courbe directrice
de l’arc.
G
En supposant que la force 1F est exercée au point C1 sur la paroi A1B1 du bloc, on détermine la
G
force de réaction F2 avec son point d’application C2, qui doit être appliquée sur la paroi A2B2 pour que le
bloc soit en équilibre. Ceci étant, on peut commencer par un des deux supports de l’arc (où l’on introduit une
G
réaction Rarc , d et son point d’application) et on peut procéder bloc par bloc jusqu’au deuxième support en
déterminant la force qui s’exerce sur chaque joint. En reliant les points d’application des réactions sur les
joints, on obtient une représentation équivalente de la ligne de pression (Figure 1.27). On note que dans cette
considération équivalente de l’équilibre, les conditions imposées par le critère de résistance du matériau se
traduisent par le fait que le point d’application de la force sur chaque joint (direction de joint) se trouve sur
l’intervalle défini par l’épaisseur de l’arc.

<!-- p. 72 -->

1.4 Calcul à la Rupture et structures maçonnées 49

Figure 1.26 – Equilibre d’un bloc–voussoir d’un arc en plein cintre utilisée pour la construction de la ligne de

pression (deuxième méthode)

Figure 1.27 – Ligne de pression d’un arc construite par le calcul des résultantes compressives aux joints

C’est effectivement cette procédure de construction de la ligne de pression qui est utilisée dans les
méthodes de la statique graphique (Culmann 1866, Pirard 1967). Notons que la statique graphique était la
méthode la plus efficace pour la considération de l’équilibre des structures au 19ème et pendant la première
moitié du 20ème siècle. Elle devient généralement fastidieuse pour des cas de structures complexes ou pour la
réalisation d’études paramétriques de typologie architecturale. Aujourd’hui certains logiciels informatiques,
tels que les logiciels de géométrie dynamique, peuvent servir à surmonter les obstacles rencontrés dans
l’application de la statique graphique à l’étude de stabilité des structures. La construction de la ligne de
pression d’une structure peut donc être réalisée très facilement à l’aide d’outils informatiques très simples

<!-- p. 73 -->

50 1 Contexte du travail

d’utilisation (par exemple, logiciel CABRI) en paramétrant la géométrie et le chargement d’une structure sur la
base d’un nombre réduit de paramètres géométriques et de chargement. A titre d’exemple, on présente dans
la Figure 1.28 l’outil d’évaluation de la stabilité d’un arc créé par Ciblac (2006). Cet exemple illustre la
recherche de la poussée maximale (A) et de la poussée minimale (B) d’un arc ogival en tiers-point sur une
même figure dynamique de polygones funiculaires. Dans chaque cas l’outil produit le polygone de forces et
permet de visualiser la magnitude des forces internes, s’exerçant entre les blocs, qui résultent si l’on applique
une poussée donnée aux extrémités de l’arc. Une deuxième application de la mise en œuvre des principes de
la statique graphique à l’aide de la géométrie dynamique peut être trouvée dans les travaux de Block et al.
(2006a, 2006b). Ce travail concerne des systèmes structuraux combinant des arcs, des piliers et des
contreforts.

Figure 1.28 – Statique graphique et géométrie dynamique (Ciblac et al. 2008)

c) La méthode du réseau de forces

La troisième et dernière méthode que l’on présente ici pour la construction de la ligne de pression a
été proposée par O’Dwyer (1999). L’idée de base de cette méthode est de représenter la ligne de pression
comme un réseau de forces obtenu en discrétisant la structure en un nombre fini de nœuds. La masse du
système et son chargement sont concentrés en ce nombre réduit de nœuds. La méthode du réseau de forces
d’ O’Dwyer est celle qui est utilisée dans cette thèse (cf. Chapitre 2) pour la réalisation des calculs de stabilité
des structures maçonnées. Il est intéressant de noter que la méthode du réseau de forces proposée par
O’Dwyer constitue la version numérique des modèles funiculaires de Gaudi (Huerta, 2006, 2008).

<!-- p. 74 -->

1.4 Calcul à la Rupture et structures maçonnées 51

On donne dans la suite une brève description de la méthode. L’application de cette méthode
nécessite que la structure soit discrétisée en plusieurs blocs qui sont réduits à un ensemble de nœuds
formant un réseau. Les centres de gravité de chaque bloc fixent l’abscisse de chaque nœud. Les contraintes
imposées par l’équilibre statique de chaque nœud (direction horizontale et verticale et moments) sont
formulées à l’égard des hauteurs inconnues des nœuds du réseau. Les nœuds sont déplacés verticalement
pour assurer l’équilibre avec le chargement extérieur qui peut comporter le poids propre de la structure
(calculé par sa géométrie), des poussées exercées aux appuis (forces horizontales) ainsi qu’un chargement
extérieur éventuellement appliqué aux centres de gravité des blocs de la structure (Figure 1.29). Ayant
déterminé les abscisses et les ordonnées pour chaque nœud, on peut construire la ligne de pression en
traçant la ligne qui passe par les positions modifiées des nœuds. Dans la Figure 1.29 on représente avec de
petites étoiles vertes les positions initiales des nœuds (identifiées avec les centres de gravité de chaque bloc)
et avec des bulles noires les positions modifiées des nœuds qui assurent l’équilibre de chaque bloc.

Figure 1.29 – La méthode du réseau de forces proposée par O’Dwyer (1999)

On note que dans cette considération de l’équilibre, les conditions imposées par le critère de
résistance du matériau se traduisent par la condition que chaque nœud du réseau de forces se trouve sur
l’intervalle défini par l’épaisseur de l’arc (les abscisses des nœuds se trouvent sur les axes verticaux qui
passent par les centres de gravité des blocs). En considérant que les points susceptibles de la formation de

<!-- p. 75 -->

52 1 Contexte du travail

rotules se trouvent sur les joints et non à l’intérieur des blocs, la méthode proposée par O’Dwyer présente
l’inconvénient qu’elle ne fait pas la vérification du critère de résistance du matériau sur les joints alors que la
méthode précédente donne directement cette possibilité.

Les diagrammes de la Figure 1.30 soulignent d’une part, le fait que les deux méthodes comparées
sont parfaitement équivalentes puisque les deux n’expriment que l’équilibre de chaque voussoir et d’autre
part, le fait que la méthode du réseau de forces fournit la position de la ligne de pression (en pointillé) à
l’intérieur des blocs (centres de gravités) alors que la méthode de Moseley (ligne de pression continue) la
place sur les joints.

(a)

(b)

Figure 1.30 - Comparaison des méthodes de construction de la ligne de pression : méthode du réseau de forces (ligne
en pointillé) et méthode de Moseley (ligne continue).

(a) poussée minimale minHarc de l’arc, (b) et poussée maximale maxHarc de l’arc

<!-- p. 76 -->

1.4 Calcul à la Rupture et structures maçonnées 53

On adoptera dans la suite du travail la méthode du réseau de forces : il s’agit d’une méthode qui est
plus facilement programmable informatiquement et elle plus adaptable à des géométries compliquées et à
des systèmes de plusieurs éléments structuraux.

Etant donné que le sujet de cette thèse consiste à étudier la stabilité des systèmes structuraux avec
plusieurs éléments, il est intéressant de mentionner les travaux de Huerta et al. (1997) et Block et al. (2006a)
dans ce domaine. Huerta et al. ont étudié la stabilité de la section transversale de l’église de Guimarei qui
correspond à un système structural d’un arc supporté sur deux piliers et deux contreforts. En se basant sur
l’approche statique par défaut, ils ont procédé à une exploration des causes de la fissuration et de grandes
déformations observées, ainsi qu’à une proposition des mesures de consolidation. Des considérations sur les
coefficients de sécurité appliqués aux structures maçonnées ont été présentées. Block et al. (2006a) ont
appliqué l’approche statique par l’intérieur en utilisant la statique graphique et la géométrie dynamique pour
étudier la stabilité des coupes transversales typiques de l’architecture romane. Dans notre approche, on
essayera de systématiser la mise en ouvre de l’approche statique par l’intérieur en se basant sur la méthode
du réseau de forces afin d’étudier les systèmes structuraux complexes tels que rencontrés dans l’architecture
gothique.

Terminons cette section avec un petit récapitulatif. On a présenté la notion de ligne de pression d’une
structure maçonnée élancée et on a montré son utilité pour la mise en œuvre de l’approche statique par
l’intérieur du Calcul à la Rupture. La ligne de pression fournit la représentation réduite des états de contraintes
dans la structure qui est suffisante pour vérifier le critère de résistance du matériau sans traction. Notons que
la notion de la ligne de pression a été abordée historiquement avant le développement de la théorie de
l’élasticité. Cette théorie permet de déterminer explicitement l’état de contraintes dans une structure qui met
en évidence une loi de comportement élastique. Pour le matériau « maçonnerie » une telle loi n’est
néanmoins pas pertinente et ne peut être appliquée que pour des chargements très faibles qui toutefois ne
présentent pas d’intérêt pratique.

Dans cette thèse, la stabilité des structures maçonnées sera évaluée par la théorie du Calcul à la
Rupture et, en particulier, par l’approche statique par l’intérieur : dans cette approche on ne cherche pas à
préciser le véritable état de contraintes dans la maçonnerie mais juste à vérifier si la structure maçonnée est
stable sous un chargement donné. Pour les structures curvilignes, l’approche se concrétise avec la
construction de la ligne de pression. On a donné alors trois méthodes équivalentes pour construire la ligne de
pression : chaque méthode exprime l’équilibre des forces et des moments dans la structure.

<!-- p. 77 -->

54 1 Contexte du travail

Dans les paragraphes suivants on donnera un bref exposé des travaux sur la stabilité des structures
maçonnées avec les deux autres approches du Calcul à la Rupture, à savoir l’approche statique par
l’extérieur et l’approche cinématique par l’extérieur.

1.4.4 Mise en œuvre de l’approche statique par l’extérieur pour les

structures maçonnées curvilignes - la notion de «l’équilibre
limite»

La mise en œuvre de l’approche statique par l’extérieur pour les structures maçonnées curvilignes se
concrétise par l’introduction d’un mécanisme virtuel de rupture selon lequel, la structure est amenée vers la
ruine en se décomposant en un nombre fini de blocs rigides. La méthode est initiée en anticipant la géométrie
de ces blocs et ensuite en écrivant les conditions d’équilibre que chaque bloc doit satisfaire juste avant la
ruine. Ce type d’analyse est connu sous le nom d’équilibre limite et constitue une approche statique par
l’extérieur. Le point délicat de la méthode est de reconnaître les forces intérieures qui sont exercées sur les
blocs à l’instant de la ruine. Pour faire cela on doit introduire une condition supplémentaire par rapport aux
conditions d’équilibre puisque les amplitudes des forces externes sont aussi inconnues (c’est en fait, ce que
l’on cherche). Pour les forces intérieures on reconnaîtra qu’il s’agit de forces de compression entre deux blocs
différents qui peuvent prendre des valeurs aussi grandes que nous souhaitons. La condition supplémentaire
ne peut donc pas provenir de l’amplitude de ces forces et en général on introduit une hypothèse sur la
direction de ces forces. Ajoutons que dans l’approche statique par l’extérieur on n’examine que l’équilibre de
chaque bloc rigide sans nécessairement examiner la stabilité interne (présence de régions en traction) de
chaque bloc. Comme déjà expliqué, l’approche statique par l’extérieur conduit à des bornes supérieures pour
les charges extrêmes d’une structure, elle est donc non conservative.

A titre d’exemple, mentionnons deux cas représentatifs d’utilisation de l’approche statique par
l’extérieur dans le contexte de la mécanique des structures maçonnées : il s’agit de la solution de Heyman
(1969, 2009) au fameux problème de Couplet (trouver l’épaisseur minimale d’un arc en plein cintre) et de la
solution d’Ochsendorf et al. (2004) au problème de renversement des contreforts maçonnés.

Pour proposer une solution au problème de Couplet, Heyman a considéré le mécanisme de rupture
présenté dans la Figure 1.31. L’arc est divisé en quatre blocs rigides par trois rotules qui le transforment en
une structure isostatique. Heyman écrit les équations d’équilibre pour les parties ABMM΄ et M΄MCD de
l’arc en introduisant les poussées qui sont exercées au niveau de rotules. Les équations d’équilibre
aboutissent à deux équations à deux inconnus : le rapport t/r, où t l’épaisseur de l’arc et r son rayon moyen

<!-- p. 78 -->

1.4 Calcul à la Rupture et structures maçonnées 55

ainsi que l’angle β du segment OM par rapport à l’axe Oz. Il s’agit en effet d’une approche statique par
l’extérieur puisque l’équilibre est écrit pour les blocs de l’arc en tant que corps rigides sans examiner la
stabilité « interne » de ces blocs.

Figure 1.31 – Equilibre d’un arc aux limites pour l’évaluation de la poussée minimale (Heyman, 1969, 2009)

Ochsendorf et al. (2004) ont appliqué les équations d’équilibre pour étudier le problème de
renversement des contreforts non monolithiques maçonnés. Dans la Figure 1.32, extrait d’Ochsendorf et al.
2004, sur un contrefort gothique typique de poids propre Vb, les forces verticale Fz,b et horizontale Hb
extérieures sont appliquées (cas (a)). Le mécanisme de rupture considéré implique une répartition linéaire
des contraintes compressives dans la maçonnerie. Ainsi, le contrefort est considéré présenter une fissure
diagonale de hauteur eb. La région inférieure à la fissure, de poids propre Vc, reste inactif (cas (b)) et son
poids propre est égal à celui de la région supérieure à la fissure définie par eb (cas (c)). La connaissance de la
répartition des contraintes compressives permet de vérifier la forme du mécanisme de rupture adopté. La
méthode de résolution suggère, alors, une procédure itérative où une succession d’approches statiques par
l’extérieur est effectuée. Cette succession converge vers un état de contraintes qui satisfait l’équilibre et le
critère de résistance partout dans la structure et qui donc exprime une solution statique par l’intérieur. La
méthode fournit, alors, la charge ultime exacte (potentiellement supportable) du contrefort.

<!-- p. 79 -->

56 1 Contexte du travail

Figure 1.32 – Equilibre d’un contrefort fissuré (extrait d’Ochsendorf et al.2004)

1.4.5 Mise en œuvre de la méthode cinématique par l’extérieur

pour les structures maçonnées curvilignes

On termine la section sur la théorie du Calcul à la Rupture avec quelques commentaires concernant
l’application de l’approche cinématique par l’extérieur aux structures constituées d’un matériau sans traction.
Comme on l’a évoqué plus haut, l’approche cinématique se base sur l’introduction d’un champ de vitesse
décrivant un mécanisme potentiel de rupture dans la structure, entraîné par le chargement qui est appliqué
sur la structure et dont on cherche les valeurs extrêmes.

Afin de mettre en œuvre l’approche cinématique et étant donné un champ de vitesses, on doit évaluer
deux quantités : d’une part la puissance des efforts extérieurs, qui dépend exclusivement du chargement
extérieur sans aucune influence du critère de résistance du matériau constitutif de la structure et d’autre part,
on doit évaluer la quantité dite « puissance résistante maximale » de la structure pour le champ de vitesses
considéré. Cette quantité traduit le potentiel de la structure à résister au chargement imposé et dépend
uniquement du critère de résistance de la structure.

Sans entrer dans les détails mathématiques, on notera que la puissance de résistante maximale pour
G
un champ de vitesse donné U (les quantités soulignées montrent qu’il s’agit de quantités virtuelles
correspondant à un mécanisme potentiel de rupture) s’obtient par intégration dans le volume de la structure
de la densité de puissance résistante maximale ; Cette quantité est en effet définie directement par le critère

<!-- p. 80 -->

1.4 Calcul à la Rupture et structures maçonnées 57

de résistance de la structure et constitue une deuxième caractérisation de la résistance de la structure
parfaitement équivalente à celle du critère de résistance dans les expressions (1.13) et (1.14).
G
On utilise le symbole π U pour désigner la densité de puissance résistante maximale en un point ( )
xG de la structure pour un champ de vitesses virtuel UG .

On se contentera à donner l’expression de la densité de puissance résistante maximale pour le
matériau sans traction. Pour ce faire on introduit le tenseur de taux de déformations virtuel qui s’obtient à
partir du champ de vitesses virtuel Uˆ par la relation :
1 G T G(1.22) d = gradU + gradU ( ) 2

On donne une expression séparée pour les points dans le volume où le champ de vitesses est
continu et pour les points où il y a discontinuité de vitesse. Pour les premiers on a :

⎧⎪ 0 si id ≤ 0(1.23) π( d ) = ⎨+∞⎪⎩ dans le cas contraire

Pour les points de discontinuité de vitesse le long d’une surface S on a :
JG JG G ⎧ 0 si ⎡ ⎡U ⎤ ⎤ ⋅ n = − ⎡ ⎡U ⎤ ⎤ JG ⎣ ⎣ ⎦ ⎦ ⎣ ⎣ ⎦ ⎦ G ⎪⎪(1.24) π ⎡ ⎡U ⎤ ⎤ ,n = ⎨ ( ⎣ ⎣ ⎦ ⎦ )
⎪+∞ dans le cas contraire
⎪⎩
JG G
où ⎡ ⎡U ⎤ ⎤ représente le vecteur de discontinuité de vitesses et n est le vecteur unitaire normal sur la ⎣ ⎣ ⎦ ⎦
surface S.

La signification de (1.23) et (1.24) est que la densité de la puissance résistante maximale est nulle à
condition que l’on trouve des champs de vitesses qui respectent les conditions dans (1.23) et (1.24). Ces
champs sont présentés sur la Figure 1.33.

Dans ce cas, l’intégration d’une quantité nulle est évidemment nulle et il s’ensuit que la puissance
résistante maximale dans le système est nulle : il suffit donc de calculer la puissance des efforts extérieurs
pour le champ de vitesses retenu (respectant les conditions dans (1.23) et (1.24), et de la poser égale à zéro
pour en tirer les valeurs des charges extrêmes de la structure.

Notons que les champs de vitesses qui conduisent à une puissance résistante maximale infinie ne
sont pas intéressants du point de vue pratique puisque dans ce cas, les bornes supérieures obtenues pour les
charges extrêmes sont infinies. Les champs de vitesses qui conduisent à des bornes supérieures finies sont
appelés pertinents.

<!-- p. 81 -->

58 1 Contexte du travail

(a). (b)

Figure 1.33 – Champs de vitesses qui conduisent à une puissance résistante maximale nulle : (a) pour les points

de vitesse continue les valeurs propres du tenseur d doivent être négatives et (b) pour les surfaces de

discontinuité de vitesse, la vitesse doit être normale sur la surface

Examinons la pertinence du champ de vitesse classique d’un arc en plein cintre où un mécanisme de
rupture est formé par la création de cinq rotules comme présenté sur la Figure 1.34. Le champ de vitesse
comporte quatre blocs qui subissent un mouvement de corps rigide et cinq discontinuités de vitesses le long
des sections où on a la formation des rotules. Les zones où le champ de vitesse est continu, c’est-à-dire dans
les blocs rigides, satisfont l’équation (1.23) puisqu’il s’agit d’un mouvement rigidifiant. De même, le long des
surfaces de discontinuité de vitesse, l’équation (1.25) est également satisfaite puisque la vitesse est normale
sur la surface de discontinuité (Figure 1.34b). Par conséquent, le champ de vitesse considéré est pertinent
pour le critère de résistance du matériau sans traction, conduit à une puissance résistante maximale nulle et
permet d’obtenir une borne supérieure finie pour la stabilité de l’arc.

<!-- p. 82 -->

1.4 Calcul à la Rupture et structures maçonnées 59

(a) (b)

Figure 1.34 – (a) Mécanisme de rupture pour un arc et (b) champs des vitesses aux points d’ouverture

Smars (2000) et Ochsendorf (2002) ont utilisé l’approche cinématique par l’extérieur dans le contexte
de la stabilité des structures maçonnées.

Ochsendorf (2002) a étudié la stabilité d’un arc sur des appuis qui peuvent subir un glissement en
considérant le mécanisme de rupture présenté sur la Figure 1.34a pour un chargement sous poids propre. En
appliquant l’approche cinématique par l’extérieur, il a estimé l’épaisseur minimale des arcs circulaires d’angle
interne1 variable. Avec la même approche, il a aussi examiné la stabilité sismique des arcs en introduisant un
chargement uniforme horizontal simulant l’accélération sismique. Notons que ce type d’analyse sismique est
couramment utilisé dans le génie parasismique et sera utilisé dans les chapitres suivants.

Ce type d’analyse sismique peut être qualifié comme analyse quasi-statique. En commençant par
l’équation d’équilibre dynamique,

(1.26) mu (t ) + ku (t ) = p (t )

on dissocie l’accélération du déplacement correspondant et on ne retient que la valeur maximale de
l’accélération u max .

Alors, on peut écrire :

(1.27) ku = p − mu max

1 Il s’agit de l’angle défini entre les appuis d’un arc et l’axe vertical.

<!-- p. 83 -->

60 1 Contexte du travail

Ceci revient à l’équation de l’équilibre statique où les forces d’inertie − mu max sont exprimées en tant
que forces extérieures. Dans le cadre du Calcul à la Rupture, ce type de raisonnement nous permet de
considérer les forces d’inertie comme paramètre de chargement extérieur et chercher la valeur maximale
u max qui est supportable par la structure.

Le diagramme d’accélération présenté dans la Figure 1.35 constitue un exemple typique
d’accélération sismique développée dans une structure. Il est manifeste que le signe de l’accélération
sismique change plusieurs fois au cours de la sollicitation. Par conséquent, pour les analyses du Calcul à la
Rupture, on retiendra la valeur u max , qui est la valeur maximale absolue pour la composante du séisme sans
d’avantage définir une direction de sollicitation spécifique. Des diagrammes similaires sont également obtenus
pour la composante sismique verticale. Notons que l’accélération verticale maximale est, en général, plus
faible que la composante horizontale. Dans la pratique du génie parasismique les deux composantes sont
prise en compte simultanément et la composante verticale est prise égale à deux tiers de la composante
horizontale. Dans les analyses des chapitres suivants et pour des raisons de simplicité on ne considère que la
composante horizontale de l’accélération sismique.

Figure 1.35 – Accélération maximale utilisée pour une simulation quasi-statique

Ochsendorf (2002) a finalement procédé à l’étude de la rupture d’un système comportant un arc qui
est supporté en deux contreforts pour un chargement sous poids propre et pour un chargement sismique
appliqué de manière quasi-statique. Il a, également, proposé des coefficients de sécurité pour un tel système.
Dans ces calculs l’arc est traité avec l’approche cinématique du Calcul à la Rupture et les contreforts avec

<!-- p. 84 -->

1.4 Calcul à la Rupture et structures maçonnées 61

l’équilibre limite (cf. paragraphe 1.4.4). On peut noter que l’approche cinématique nécessitant l’adoption d’un
mécanisme de rupture devient fastidieuse pour des systèmes structuraux plus complexes.

1.4.6 Les précautions de l’adoption du critère de résistance du
matériau sans traction

La phénoménologie du comportement mécanique des structures maçonnées à l’échelle globale
(c’est-à-dire, sans prise en compte des caractéristiques de la microstructure de la maçonnerie) révèle que les
caractéristiques principales de la résistance d’une maçonnerie sont les suivantes : il s’agit d’un matériau
résistant en compression et dont la rupture est observée surtout à cause de rotations entre les voussoirs. Ces
aspects sont décrits par le critère de résistance du matériau sans traction, critère de résistance adopté pour la
mise en œuvre de la méthode du Calcul à la Rupture dans cette thèse. Il s’agit bien sûr d’un critère simplifié
qui implique que la maçonnerie n’a pas de résistance en traction, que la résistance en compression est infinie
et que le phénomène de glissement ne peut apparaître nulle part dans la structure. Par rapport à ses trois
hypothèses simplificatrices on note les points suivants.

\1. La maçonnerie n’a pas de résistance en traction. Cette hypothèse conservative, alignée globalement
avec le comportement des structures maçonnées, peut parfois fausser son véritable comportement. Smars
(2000) a étudié la stabilité des arcs dont les joints ont une faible résistance à la traction et il a redéfini les
poussées extrêmes pour la stabilité d’un arc. Sa remarque essentielle est que la prise en compte d’une
résistance à la traction ainsi que l’augmentation (ou réduction) conséquente des poussées maximales
(respectivement minimales) peut changer le mode de rupture de la structure. Par exemple, lorsque la poussée
maximale d’un élément est augmentée, il est nécessaire que les éléments de contrebutement puissent
supporter cette augmentation.

\2. La résistance en compression est infinie. Cette considération concerne plutôt les contraintes
moyennes développées dans la maçonnerie. Cependant, la concentration des contraintes peut augmenter et
des écrasements et des fracturations peuvent apparaître. Delbecq (1982) et Smars (2000) ont proposé des
solutions de la stabilité d’un arc pour une résistance en compression finie.

\3. Le glissement ne se produit nulle part dans la maçonnerie. Même si la rupture est plutôt une question
d’ouverture de fissures à cause de rotations, on doit considérer le cas où le frottement n’est pas assez
important. En pratique, le glissement peut apparaître dans la maçonnerie mais il ne conduit pas à la ruine. On
cite les travaux de Delbecq (1982) et Boothby (1994) qui ont essayé d’incorporer la dissipation de l’énergie à

<!-- p. 85 -->

62 1 Contexte du travail

cause du frottement pour étudier la stabilité des arcs. Smars (2000) dans son approche statique propose un
contrôle de l’effort tranchant en adoptant un critère de frottement de type Coulomb.

On peut noter que l’adoption du critère de résistance du matériau sans traction, étant très général,
nous permettra de s’affranchir de la discussion des propriétés de la microstructure, des dispositifs de
construction ainsi que des critères de résistance indépendants de la pierre et du mortier. Heyman (1995) a
noté que les simplifications mentionnées peuvent avoir des effets mais en général ils restent du côté de la
sécurité.

1.4.7 Autres outils du Calcul à la Rupture

On peut trouver des outils numériques divers de la mise en œuvre du Calcul à la Rupture dans la
littérature qui feront l’objet de ce paragraphe sans avoir l’intention d’être exhaustif. Ces outils concernent
surtout le domaine des structures géotechniques. Il s’agit d’outils qui permettent d’évaluer la capacité portante
des fondations superficielles ou les poussées et les butées des murs de soutènement ou finalement de
vérifier la stabilité des talus. A titre d’exemple, citons le logiciel OXLIM, logiciel dédié aux calculs des
structures dont le matériau obéit au critère de résistance de Mohr-Coulomb.

Dans le domaine des structures maçonnées, on mentionnera deux programmes effectuant une
analyse de la stabilité des voûtes. Le programme CALIPOUS (Smars, 2000) permet de calculer la ligne de
pression d’un arc tridimensionnel en faisant varier la forme de l’intrados, l’épaisseur, la profondeur (hors-plan)
et les charges appliquées. Dans ce programme, une résistance faible en traction et une résistance finie en
compression sont considérées.

Le programme VOUTE (Delbecq, 1982) est destiné spécifiquement au calcul de stabilité des sections
verticales de ponts en maçonnerie. Ce programme permet de calculer pour une géométrie et un chargement
donné : a) le coefficient de rupture, b) les poussées extrêmes, c) les lignes de pressions correspondantes et
d) les réactions. Le programme n’effectue pas la vérification du risque de glissement entre les blocs de la
maçonnerie aux appuis. Dans les calculs effectués par ce logiciel, la résistance en compression est finie car
dans ce type de structures maçonnées les contraintes développées sont de même ordre de grandeur que la
résistance en compression du matériau.

Les logiciels destinés aux voûtes maçonnées sont difficiles à utiliser pour des structures comprenant
d’autres éléments.

<!-- p. 86 -->

1.5 Model d’une structure en vue d’une simulation mécanique 63

1.5 Modélisation géométrique de l’édifice en vue
d’une simulation de son comportement structurel

Les simulations numériques sont utilisées dans de nombreux domaines scientifiques afin de
remplacer partiellement ou totalement les approches expérimentales. Plusieurs étapes peuvent être
distinguées pendant la simulation du comportement d’une structure. En premier lieu, le modèle
tridimensionnel de la structure est construit et, ensuite, dans ce modèle, les données nécessaires pour
effectuer la simulation sont introduites. L’outil de calcul de la stabilité des structures maçonnées développé
dans cette thèse requiert un modèle architectural de la structure qui décrit précisément des surfaces qui
correspondent aux contours de la structure. Cette description des contours de la structure est utilisée dans
deux stades du calcul : au premier stade pour estimer son volume et son poids propre ainsi qu’au stade de
l’évaluation de la stabilité de la structure en maçonnerie pour conditionner les contraintes d’équilibre (cf.
paragraphe 1.4.2). En ce qui concerne le maillage du modèle, on doit avoir la possibilité de définir le volume
de chaque élément ainsi que la stéréotomie des voussoirs de la maçonnerie.

La modélisation tridimensionnelle de l’édifice peut s’effectuer selon différentes techniques qui
disposent chacune d’avantages et d’inconvénient. Le choix d’une technique peut être fait selon la disponibilité
et la qualité des informations qui décrivent la structure, la situation de l’édifice, le coût de la mise en œuvre
etc. Dans la suite, on présentera les principes de la modélisation géométrique, volumique et surfacique, ainsi
que le concept de la modélisation paramétrique. On présentera, parallèlement, le principe de la restitution
basée sur la mesure à distance de l’existant. Il s’agit de la restitution à partir d’un nuage de points ou à partir
des techniques utilisant des photos. En outre, on présentera des outils de restitution d’édifices qui réalisent un
modèle 3D au moyen d’une base de connaissances architecturales relatives à la conception de la structure à
modéliser. Finalement, on définira les exigences et les caractéristiques du maillage nécessaire à la simulation
mécanique.

1.5.1 La modélisation volumique et surfacique à partir de

document

Si l’on dispose tous les documents précis à l’échelle décrivant l’édifice (plans, coupes, façades), on
peut créer le modèle géométrique tridimensionnel au moyen d’un modeleur 3D. La plupart des éléments de la
structure d’un édifice médiéval peuvent être modélisés par des opérations de révolution d’un profil autour d’un
axe ou par balayage d’un profil le long d’une courbe. Par exemple, il s’agit du cas d’un pilier ou d’un arc
(Figure 1.36a). Il est, aussi, possible d’utiliser des primitives géométriques (par exemple, cylindre, sphère,

<!-- p. 87 -->

64 1 Contexte du travail

cône, tore, etc.) et de les combiner grâce à des opérations booléennes (par exemple, union, intersection,
soustraction) pour produire l’objet à modéliser. Dans la Figure 1.36b on pressente la modélisation
tridimensionnelle d’une voûte romane par l’union de deux demi-cylindres.

(a) (b)

Figure 1.36 – Modélisation volumique : (a) Arc : révolution du profil autour d’un axe semi-circulaire,

(b) Voûte romane : union de deux demi-cylindres

Pour certains éléments composés de surfaces gauches comme, par exemple, les voûtains d’une
voûte gothique, la modélisation surfacique est nécessaire. Il s’agit de produire les courbes qui définissent le
contour de l’intrados et de l’extrados des voûtains, d’ajouter éventuellement des lignes transversales
épousant la courbure des voûtains puis de faire passer une surface passant par l’ensemble de ces courbes.

Le travail nécessaire pour la modélisation d’une structure à partir de documents peut être long mais
n’est pas d’une très grande difficulté ou d’un coût important. En plus, aujourd’hui le recours à des spécialistes
pour une telle modélisation n’est plus nécessaire. En ce qui concerne les simulations mécaniques aux
éléments finis, les outils de calculs acceptent en entrée des modèles tridimensionnelles volumiques ou/et
surfaciques et un maillage tétraédrique de l’ensemble du modèle tridimensionnel peut être effectué
automatiquement préalablement au calcul. Cependant, il est souvent nécessaire de procéder à des maillages
différents selon la nature des éléments de la structure et l’expertise d’un ingénieur analyste est souvent
requise pour opérer ces différents maillages. Dans ce cas, le coût de l’opération peut être sensiblement
augmenté.

Dans tous les cas de modélisation mentionnés, la précision de la description géométrique de la
structure à reconstituer dépend de la qualité des documents disponibles. Souvent pour des édifices

<!-- p. 88 -->

1.5 Model d’une structure en vue d’une simulation mécanique 65

historiques en maçonnerie, la fiabilité de ces documents n’est pas très importante. Les grandes dimensions et
le caractère fragile du matériau « maçonnerie » rendent ces structures susceptibles d’avoir subi des
altérations pendant leur vie (cf. paragraphe 1.1.2). De ce fait, l’unique moyen est d’effectuer le relevé actuel
de la surface des objets à restituer. Etant donné que pour le relevé des édifices complexes, tels que les
cathédrales gothiques, les méthodes classiques de mesure (mètre ruban, niveau, etc.) sont exclues, les
méthodes d’acquisition des données à distance doivent être utilisées. Il s’agit des méthodes de la
lassergrammétrie (où le relevé est un nuage de points) et de la photogrammétrie (où le relevé est reconstitué
à partir de photographies) qui seront présentées dans les deux paragraphes suivants.

1.5.2 La modélisation à partir de nuages de points acquis par laser

Si l’on ne dispose pas de documents suffisamment précis et fiables, le modèle tridimensionnel d’une
structure réelle peut être acquis par la méthode de la lasergrammétrie. Des balayages de la structure sont
réalisés au moyen de dispositifs appelés « capteurs laser » dont le fonctionnement s’appuie sur le principe
des rayons «LASER». Il s’agit de l’«amplification de la lumière par émission stimulée de rayonnement» (en
anglais : Light Amplification by Stimulated Emission of Radiation). Il y a deux catégories principales de
modules de balayage laser tridimensionnel applicables au relevé d’édifices : les capteurs à temps de vol et les
capteurs à triangulation. Les premiers, appelés aussi scanners longue portée, déduisent la distance
parcourue à partir de la mesure du temps de retour d’un faisceau lumineux de nature connue, projeté sur un
objet ou bien en comparant le changement de phase de l’onde transmise et reçue d’un angle modulé. Le
principe de fonctionnement des capteurs à triangulation repose sur l’observation d’un point émis par une
diode laser à l’aide d’un système optique décalé de l’émetteur. Marbs et al. (2001) et Fuchs (2006) fournissent
une description détaillée des principes de fonctionnent appartenant aux deux catégories. La Figure 1.37, tirée
de Marbs (2001), représente schématiquement les principes de fonctionnement des deux types de scanners.

<!-- p. 89 -->

66 1 Contexte du travail

Figure 1.37 – Illustration schématique des deux principes de fonctionnement des dispositifs de balayage laser,

extrait de Marbs (2001). A gauche le principe du temps de vol, à droite celui de la triangulation

La précision et le niveau de détail acquis par les scanners tridimensionnels disponibles sur le marché
sont présentés dans une analyse comparative dans Bohler et al. (2003). Dans le cas du modèle 3D d’un
édifice de patrimoine, destiné à des simulations mécaniques, la distance d’acquisition est, en général, grande
et les scanners à temps de vol sont les plus adaptés.

L’acquisition par les scanners laser tridimensionnel est directe puisque les points acquis sont
restitués en temps réel sous forme de coordonnées, c’est-à-dire les données d’un scanner laser sont déjà des
points orientés dans l’espace. Cependant, la connaissance de la position des points par elle-même ne suffit
pas pour la reconstitution des éléments différents de l’édifice puisque l’on ne connaît pas à quel élément
appartient chaque point. De plus, un seul balayage n’est jamais suffisant pour la restitution entière d’un édifice
du patrimoine. Par conséquent, un prétraitement est nécessaire pour exporter les données vers un modeleur
CAO1. Ce prétraitement est divisé en trois étapes : la consolidation, la segmentation, le maillage. La
consolidation porte sur l’insertion des nuages de points de plusieurs points de vue dans un système de
coordonnées unique. Trois stratégies sont possibles (Boehler et al. 2002) :

• La collecte des données peut être accompagnée par une saisie de points d’appui au moyen d’un
autre système de relevé (par exemple une station totale avec des coordonnées et une orientation
connues).

1 Conception Assistée par Ordinateur

<!-- p. 90 -->

1.5 Model d’une structure en vue d’une simulation mécanique 67

• Des cibles (naturelles ou artificielles) peuvent être utilisées pour transformer les données acquises
localement en fonction d’un système de coordonnées commun.

• Des procédures automatiques de superposition de surfaces obtenues par maillage automatique
(uniquement pour les objets de petite taille comme les sculptures ou des décors) peuvent être
utilisées.

Pour les objets à l’échelle architecturale, la technique la plus courante est celle qui utilise des cibles. Pendant
la segmentation, les sous-ensembles logiques dans le nuage des points sont constitués en isolant les
ensembles de points qui correspondent à des parties différentes de l’objet ou de l’environnement. Le maillage
est généré par polygonisation régulière (triangulaire) du nuage des points qui est transformé dans un
ensemble de mailles surfaciques. La phase suivante est réalisée à l’aide d’un logiciel CAO/DAO1 ou un
modeleur tridimensionnel et aboutit à la modélisation géométrique et la représentation numérique
tridimensionnelle de la structure.

Par rapport au niveau du détail de la représentation de la structure en vue des simulations
mécaniques, certains auteurs discutent le rapport de la précision du modèle comme fonction de l’ampleur des
altérations (déformations, fissurations, etc.) qui forment la pathologie du bâtiment. Heyman (1995) remarque
que le tassement différentiel de 100mm d’un haut pilier d’une cathédrale et sa fissuration correspondante de
la superstructure ne sont pas dangereux puisque le même tassement tracé dans une échelle réduite de
1 :100 est pratiquement inaperçu. Il relie alors le niveau de détail nécessaire dans un modèle à la possibilité
de distinguer le même détail dans un modèle réduit en présentant l’argument que si le détail reste inaperçu
dans le modèle réduit, il n’y a pas de vrai changement aux équations d’équilibre (qui sont bien sûr déduites de
la géométrie de la structure). En revanche, dans les travaux de Huerta et al. (1997), concernant la
restauration de l’église de Guimarei où une grande inclinaison des faces des murs de l’église (d’un angle
entre 1.45o à 2.12o) a été mise en évidence, la prise en compte de la géométrie déformée de la structure a
guidé essentiellement la nature des résultats obtenus. En général, le modèle acquis par le scanner laser est
très précis mais la même précision n’est pas forcement nécessaire pour effectuer des
simulations mécaniques.

La modélisation à partir de nuages de points acquis par laser est une campagne coûteuse et un
travail délicat. Des spécialistes sont indispensables afin de repérer dans le nuage de points les éléments de la

1 DAO: Dessin Assisté par Ordinateur

<!-- p. 91 -->

68 1 Contexte du travail

structure, les modéliser et produire le maillage en vue des simulations mécaniques. En plus, des obstacles
posées parfois par des structures voisines rendent impossible le balayage de l’édifice entier. Il s’agit d’une
méthode plutôt réservé à des édifices prestigieux. Dans ce qui suit, on présentera une autre méthode
d’acquisition des données pour la restitution tridimensionnelle du patrimoine qui est moins exhaustive, mais
plus ergonomique et, donc, très diffusée dans la pratique.

1.5.3 La modélisation à partir de photos

La photogrammétrie architecturale est une autre méthode d’acquisition de données visant à la
modélisation tridimensionnelle d’une structure réelle pour laquelle les documents existants ne sont pas bien
construits ou détaillés. Le mot photogrammétrie indique un sort de mesure (-mmétrie, du grec μετρώ =
mesurer) basée sur la photographie (photogra-), c’est-à-dire de l’écriture de la lumière (photo-, du grec φως =
lumière et –graphie, du grec γράφω = écrire). Parmi le grand nombre des logiciels commerciaux de
modélisation tridimensionnelle à partir de photos, on présente dans la Figure 1.38, à titre d’exemple, la
restitution d’une cave avec le logiciel CANOMA.

Figure 1.38 – Photogrammétrie et modélisation 3D.

A gauche : image de source. A droite modèle 3D (extrait du web-site CANOMA)

Le principe fondamental de la photogrammétrie se base sur la déduction des paramètres d’orientation
externes et internes de l’appareil photo (Kraus et al. 1997). L’orientation interne consiste à fixer la position du
centre de projection par rapport au support de l’image et à chiffrer la distorsion, ce qui correspond au

<!-- p. 92 -->

1.5 Model d’une structure en vue d’une simulation mécanique 69

calibrage de l’appareil photo. L’orientation externe détermine la position et l’orientation de l’appareil photo
dans l’espace-objet. La restitution photogrammétrique permet alors d’extraire des images d’un ensemble de
coordonnées exprimées dans l’espace-objet. Les méthodes de restitution utilisées dans la photogrammétrie
diffèrent en fonction de la configuration de l’acquisition: mono-, stéréo- ou multi-images (Figure 1.39, De Luca,
2006).

Figure 1.39 – Schéma représentant les trois techniques de restitution photogrammétrique (extrait de De Luca, 2006).

De gauche à droite : la restitution à partir d’une seule image, d’un couple d’images et d’un bloc multi-image

Restitution à partir d’une seule image. La restitution à partir d’images isolées peut être réalisée si l’on dispose
d’informations supplémentaires sur l’objet ou on connaît sa géométrie. Pour que l'image soit une copie exacte
de l'objet, elle doit être redressée ou rectifiée, c’est-à-dire il faut contraindre un certain nombre de points dans
l'image en définissant leurs positions relatives.

Restitution à partir d’un couple d’images - Stéréophotogrammétrie. Au lieu de déterminer des points utilisant
les principes de la perspective (ce qui consiste une procédure longue et difficile), la stéréophotogrammétrie
utilise la stéréoscopie pour la saisie directe de points sur deux clichés différents. Afin d’avoir deux cliches
exploitables, les prises de vue doivent respecter un nombre de conditions (Alby, 2006). La stéréoscopie est
un mécanisme d’observation tridimensionnelle des solides (stéréo-, du grec στερεός = solide et –scopie, du
grec σκοπεύω = observer). Ce mécanisme consiste à déplacer en translation le deuxième cliché en fonction
de la position observée sur le premier de façon à ce que les deux points observés soient toujours
homologues. Les développements récents dans la stéréophotogrammétrie portent sur la
stéréophotogrammétrie numérique qui, à partir des images numériques ou numérisées, permet d’acquérir des
fichiers numériques exploitables sans l’intermédiaire du traitement tel que le développement de la prise de
vue numérique.

<!-- p. 93 -->

70 1 Contexte du travail

Restitution à partir d’un couple d’images - Photogrammétrie multi-image. La photogrammétrie multi-image
monoscopique se base sur le traitement logiciel semi-automatisé de clichés pris dans des conditions quasialéatoires (Fuchs, 2006). Il s’agit d’une méthode de restitution très flexible puisqu’elle permet de traiter
rapidement des photographies issues de matériel grand public. Le traitement logiciel semi-automatisé
développe un bloc d’images, où la position de chaque image est déterminée par la voisine grâce à
l’ajustement des faisceaux perspectifs de chaque prise de vue. Les distorsions provenant d’appareils de prise
de vue sont corrigées afin d’obtenir des résultats métriques. Une fois le modelé tridimensionnel obtenu, le
logiciel de photogrammétrie permet de projeter les fichiers raster pour en constituer la surface
(Grussenmeyer, 2003). Les prises de vue doivent respecter un certain nombre de règles. Dans le cas de la
photogrammétrie architecturale, Waldhaeusl et al. (1994) ont proposé les règles 3X3 pour la réalisation de
prise de vues dans des conditions optimales en vue d’un traitement photogrammétrique ultérieur. Ces règles
ont été présentées schématiquement (Figure 1.40) par Grussenmeyer (2003).

Figure 1.40 – Représentation schématique du principe des règles 3X3 considérant les prises de vue autour d’un

bâtiment afin de réaliser une restitution multi-image complète (extrait de Grussenmeyer, 2003)

La photogrammétrie est une méthode d’acquisition moins coûteuse que la lasergrammétrie qui donne
une précision réduite parce qu’elle est restreinte par le pointage manuel des points homologues. Les limites
de chaque objet peuvent être définies précisément mais la description, par exemple, des éléments
cylindriques reste difficile. L’intégration des systèmes CAO à la photogrammétrie a beaucoup augmenté
l’efficacité de la modélisation photogrammétrique (Van De Heuvel, 2000). Les travaux de Maher et al. (2002)
sur la Sagrada Familia constituent un exemple représentatif de la flexibilité acquise dans la modélisation
grâce à la combinaison des outils CAO et de la photogrammétrie. Par ailleurs, la restitution visant à une

<!-- p. 94 -->

1.5 Model d’une structure en vue d’une simulation mécanique 71

représentation complète de la structure demande l’association des deux méthodes d’acquisition de données.
La lassergrammétrie peut donner une haute précision au modèle et la photogrammétrie peut contribuer au
niveau de documentation de la pathologie. La photogrammétrie est, aussi, la méthode pertinente pour
l’acquisition de données considérant les détails constructifs d’une structure (par exemple, pour une structure
maçonnée : la taille des éléments, l’orientation des joints, etc.). On peut citer dans ce contexte les travaux de
Baletti et al. (2004) qui proposent une modélisation hybride et sont adaptés à la représentation architecturale.
On note, finalement, que la production du maillage à partir du modèle tridimensionnel construit soit avec la
lassergrammétrie, soit avec la photogrammétrie, en vue des simulations mécaniques reste une procédure qui
nécessite un traitement spécialisé et ne peut pas être produit automatiquement.

1.5.4 La modélisation paramétrique

Lorsqu’il s’agit de construire le modèle d’une structure à partir de documents (cf. paragraphe 1.5.1)
ou en utilisant les méthodes de mesure à distance de l’existant (modèle à partir de nuages de points ou de
photos, cf. paragraphes 1.5.2 et 0), il est préférable de s’orienter vers une modélisation paramétrique. Dans
ce genre de modélisation les éléments de la structure et les relations qu’ils entretiennent sont paramétrés et,
par conséquence, la flexibilité du modèle augmente considérablement. Le modèle paramétré permet de
produire plusieurs variantes et d’ajuster la restitution pour étudier plusieurs aspects de la structure
(géométries déformées, variantes typologiques, etc.). A titre d’exemple, dans la Figure 1.41, on présente la
modélisation paramétrique d’un arc passant de la géométrie plein-cintre à celle d’un arc ogival en utilisant le
logiciel COBALT. Pour plus de détail sur la méthode on renvoie le lecteur aux travaux de Burry et al. (1997).
Dans la suite, on présentera quelques exemples afin de démontrer l’utilité de la modélisation paramétrique.

<!-- p. 95 -->

72 1 Contexte du travail

Figure 1.41 – Modélisation paramétrique d’un arc (plein cintre-ogival) avec le logiciel COBALT

La modélisation paramétrique peut être très utile pour les travaux de restitution des structures très
complexes. Un exemple parlant est l’architecture de Gaudi. Pour la construction de la partie incomplète de la
Sagrada Familia, des modèles paramétriques ont été développés à l’objectif d’offrir de la flexibilité par rapport
aux exigences créées pendant les travaux (Burry et al. 2001, 2006). La construction de la fenêtre de la
Passion Façade est un projet où la construction de la partie inférieure se passait au même temps que la
modélisation de la partie supérieure. Comme l’échafaudage se levait, le modèle devait être adapté en tenant
en compte les nouvelles mesures des parties voisines déjà construites. De plus, la comparaison avec un
modèle réduit en plâtre a révélé le besoin de plusieurs ajustements au modèle initial. Ainsi, la mise en œuvre
d’un modèle flexible aux changements, tel que le modèle paramétrique, a été indispensable afin d’éviter des
suppressions et des reconstructions successives du modèle initial. La modélisation paramétrique a beaucoup
servi aussi dans la phase de définition du taillage des blocs en pierre en considérant les exigences de la
géométrie de chaque bloc pour sa mise en place par le derrick.

La modélisation volumique a une flexibilité restreinte à cause de possibilités limitées de créer le
volume désiré par un ensemble d'opérations. Cependant, l’intégration du contrôle paramétrique de relations
dimensionnelles aux modeleurs peut beaucoup contribuer à dépasser cette difficulté. Dans l’esprit de la
modélisation paramétrique et volumique des solides (basée sur les principes de la Géométrie Constructive
des Solides), les travaux de Potamianos et al. (1995) proposent un langage procédural pour la génération de
modèles de restitution 3D des églises méso-byzantines (Figure 1.42). Le modèle est défini à partir de

<!-- p. 96 -->

1.5 Model d’une structure en vue d’une simulation mécanique 73

formules algébriques déduites des théories de construction des églises de ce style. Même si les modèles
développés ne sont pas exhaustifs, vu que leur but primaire reste éducatif pour la réalisation d’études
paramétriques de typologie, ils peuvent bien servir pour la réalisation des simulations mécaniques.

Figure 1.42 - Le modèle tridimensionnel d’une église méso-byzantine, résultat de modélisation paramétrique et de

CSG, extrait de Potamianos et al. (1995)

Un exemple qui combine la lassergrammétrie et le paramétrage du modèle acquis se trouve dans les
travaux de recherche effectués à l’Université de Columbia pour l’église de Saint Julien de Couleuvre en
France (Boothby et al. 2007b). Il s’agit d’un balayage de plus de six millions de points d’une grande précision.
Ce balayage a servi pour la réalisation des modèles utilisés aux simulations mécaniques tant
tridimensionnelles (simulations éléments finis) que bidimensionnelles (simulations en utilisant la statique
graphique). En plus, ce modèle, considéré comme typique de l’architecture romane bourbonnaise, à été
paramétré afin d’être utilisé pour des simulations mécaniques interactives bidimensionnelles (statique
graphique) d’une centaine d’églises romanes (Block et al. 2006a). La Figure 1.43 représente l’outil interactif
de restitution tridimensionnelle et le modèle paramétrique de l’église de Saint Julien (extrait du web-site de
l’Université de Columbia).

<!-- p. 97 -->

74 1 Contexte du travail

Figure 1.43 – Le modèle paramétrique de l’église St Julien, Couleuvre, France (extrait du web site de l’Université de

Columbia)

Dans tous les cas, produire une modélisation paramétrique peut être d’une grande utilité surtout
quand il s’agit d’un modèle en vue des simulations mécaniques. On observera au troisième chapitre qu’un
modèle paramétrique peut assister à une meilleure compréhension d’un phénomène lié à une déformation et
prévoir des remèdes, en donnant la possibilité d’étudier le comportement de la structure avant la déformation
ou de chercher la déformation ultime avant la rupture (cf. paragraphe 3.3.2). Aussi, au même chapitre on
peut observer l’utilité du modèle paramétrique pour l’étude de l’effet de la typologie d’un élément dans la
stabilité d’un ensemble structural (cf. paragraphe 3.2.1). Cependant, on doit noter que la constitution d’un
modèle paramétrique tridimensionnelle requiert une plus grande expertise que pour une modélisation
volumique et surfacique « classique ».

1.5.5 Assistance à la modélisation et à la construction
d’un maillage

Les paragraphes précédents ont révélé que la restitution d’un édifice maçonné est un travail lent et
délicat. Parfois, l’utilisation d’une méthode d’acquisition des données visant à la restitution tridimensionnelle

<!-- p. 98 -->

1.5 Model d’une structure en vue d’une simulation mécanique 75

de la totalité d’une structure, telle que le balayage laser ou la prise des photographies, est empêchée à cause
de difficultés techniques, comme par exemple celles occasionnées par le voisinage avec d’autres bâtiments,
ou à cause du coût important de leur mise en œuvre. Par conséquent, la restitution tridimensionnelle basée
sur ces techniques d’acquisition de données n’est pas pertinente pour les nombreux cas d’édifices qui, bien
que moins prestigieux, nécessitent une approche efficace, pas exhaustive, ni coûteuse.

Les difficultés liées à l’utilisation de ces techniques de modélisation ont conduit certaine équipes de
recherche, comme l’ARIAM par exemple, à développer des outils de modélisation appropriés. Pour la plupart
des édifices, il existe des documents le décrivant, tels que des dessins, des photos et généralement au moins
un plan. Cette considération a orienté des travaux de recherche vers une approche de restitution
tridimensionnelle qui utiliserait les documents disponibles et quelques mesures prises sur site.

Le logiciel OGIVES développé à l’ARIAM (Chassagnoux et al. 1998) vise à la modélisation
tridimensionnelle des édifices gothiques et à la constitution d’un maillage en vue des simulations mécaniques.
Il est basé sur le fait que l’on peut produire un model à partir des informations déduites par le plan de l’édifice
et de quelques mesures prises sur le site. Il est fondé, aussi, sur la possibilité de fabriquer automatiquement
un maillage spécifique adapté à la nature des éléments de la structure et destiné aux calculs avec la méthode
des éléments finis. Il s’agit d’un outil d’évaluation de la stabilité des structures gothiques ayant comme objectif
la compréhension de l’édifice et l’explication de désordres constatés. Une analogie peut être faite avec le
« stéthoscope » du médecin.

Le logiciel est constitué de trois modules (Figure 1.44). Le premier est destiné à assister l’architecte à
produire un modèle paramétrique de l’édifice gothique à étudier à partir des documents le décrivant (plans,
coupes etc.). Le modèle résultant est composé des différents éléments structurels qui composent l’édifice
(pile, arc, voûtains etc.) ainsi que des relations qu’ils entretiennent pour constituer la structure. A partir de ce
modèle paramétrique l’utilisateur peut produire différentes restitutions de l’édifice en ajustant la valeur des
paramètres de manière à s’approcher au mieux de l’édifice existant. Le second module a pour objet de
produire automatiquement un maillage du modèle tridimensionnel en tenant compte des caractéristiques des
éléments constituant la structure. A la différence des maillages tétraédriques automatiques, proposés par la
plupart des outils d’analyse aux éléments finis, il s’agit d’adapter le maillage aux caractéristiques constructives
des éléments de la structure. Autrement dit, la manière de constituer les mailles d’une pile, d’un arc ou d’un
voûtain sera différente. Le principe est de différencier le maillage selon la nature des appareillages de la
maçonnerie dans l’objectif d’obtenir une simulation plus fiable. Le troisième module correspond au logiciel de
calcul proprement dit. L’objet de ce dernier module est de produire les résultats de la simulation du
comportement de la structure à partir du maillage.

<!-- p. 99 -->

76 1 Contexte du travail

Utilisateur

Module Module Module
d’aide à la de maillage de calculs
description de de l’édifice par
l’édifice éléments finis

Figure 1.44 – Architecture logicielle du système, extrait de Chassagnoux et al. (2000)

Du point de vue de la modélisation la particularité du système est qu’il utilise une base de
connaissances capable d’interpréter des indications fournies par l’utilisateur sur le document décrivant
l’édifice (le plan). L’utilisateur trace approximativement l’axe des arcs (formeret, doubleau, arc ogivaux etc.)
sur le plan. A partir de ces indications et d’un système à base de connaissances fondé sur le raisonnement
par classification (Guéna, 2005) le système identifie les éléments qui constituent la structure et effectue une
estimation de leur position dans l’espace. La base de connaissance décrit dans une hiérarchie de classes les
propriétés permettant d’identifier les différents éléments de l’architecture gothique à partir des indications de
l’utilisateur. Le système de classification cherche à apparier les intersections des traces représentant l’axe
des arcs, à la classe des piles ou à celle des clés de voûtes de l’édifice. Il identifie les arcs correspondant aux
formerets, aux doubleaux ou aux arcs ogivaux. Enfin, il repère les éléments du document qui constitue les
voûtes et peut les qualifier (quadripartie, sexpartite etc., Figure 1.45). Une fois les éléments constituant la
structure identifiés, le module produit un modèle paramétrique de la structure. Les informations non
mesurables sur le plan (par exemple, la hauteur des clés de voûtes) sont estimées à partir de connaissances
sur l’architecture gothique (par exemple, arcs en tiers-points). Le système peut ainsi produire un modèle
paramétrique canonique que l’utilisateur peut ajuster ensuite en faisant varier la valeur des paramètres des
éléments dans le but de s’ajuster au mieux à la forme de l’édifice existant (hauteurs réelles des clés de voûtes
et du tas de charge qu’il est possible de mesurer sur le site, inclinaison des piles etc.).

<!-- p. 100 -->

1.5 Model d’une structure en vue d’une simulation mécanique 77

élément gothique

arc voutain voute pile clé

doubleau formeret ogive Voute Voute
quadripartite sexpartite

Figure 1.45 – Interprétation du graphe topologique, extrait de Chassagnoux et al. (2000)

A partir de ce modèle paramétrique le module de maillage effectue pour chacun des éléments un
maillage spécifique dépendant de son type. Dans la Figure 1.46 on présente le maillage produit en vue des
calculs aux éléments finis pour une voûte de l’église de Montreuil (extrait de Chassagnoux et al. 2000).

Figure 1.46 – Visualisation du maillage d’une voûte sélectionnée (extrait de Chassagnoux et al. 2000)

<!-- p. 101 -->

78 1 Contexte du travail

Un autre exemple de cette approche de modélisation tridimensionnelle des structures se trouve dans
les travaux de Dosch et al. (2000), qui proposent la restitution des édifices à partir d’un système d’analyse des
documents architecturaux. En passant d’une reconnaissance graphique du plan de chaque niveau à un
modèle bidimensionnel qui transforme le document en une description en termes d’entités architecturales
basiques, une modélisation tridimensionnelle est proposée associant les niveaux reconstruits. Ce système a
été appliqué aux édifices canoniques dont les plans de différent niveaux sont précisément déterminés.
Cependant, la complexité du système structural des cathédrales gothiques rend plus difficile leur restitution
tridimensionnelle à partir d’un plan. Dans le plan d’une cathédrale gothique, les objets superposés dans
l’espace sont souvent représentés avec le même trait (par exemple, un formeret au niveau de la voûte du
collatéral et un autre formeret au niveau de la nef centrale). Pour surpasser cette ambiguïté du plan, la notion
des niveaux logiques a été introduite au « stéthoscope » (Figure 1.47).

Figure 1.47 – Les niveaux logiques du logiciel OGIVES (extrait de Chassagnoux et al. 2000)

Ces approches de restitution d’édifices évitent les procédures d’acquisition de données exploitant en
mieux les documents existants. En se basant sur une structuration hiérarchisée des objets-éléments
paramétrés, ces techniques peuvent décrire finement la géométrie de chaque élément. Cette propriété de
discrétisation de la structure en ses éléments constitutifs est indispensable pour la réalisation des calculs
mécaniques proposés dans cette thèse.

<!-- p. 102 -->

1.5 Model d’une structure en vue d’une simulation mécanique 79

1.5.6 Exigences de discrétisation du modèle en vue de réalisation

des calculs mécaniques

A partir donc du modèle tridimensionnel, le volume doit être discrétisé afin de servir aux simulations
mécaniques envisagées. Les caractéristiques nécessaires pour un maillage destiné à des calculs aux
éléments finis sont selon Laug (2006) :

• comporter un nombre raisonnable d’éléments,

• être suffisamment fin pour que la solution soit calculée avec une précision satisfaisante et pour que la
géométrie soit convenablement respectée,

• contenir des éléments suffisamment réguliers.

Pour chaque cas, les caractéristiques préalables du maillage sont imposées par l’échelle considérée
pour la simulation mécanique de la structure (cf. paragraphes 1.1.3 et 1.2) et par les propriétés du matériau
constitutif (dans cette thèse on ne considère que de la maçonnerie qui suit les propriétés du matériau sans
traction, cf. paragraphe 1.4.1). Dans les caractéristiques mentionnées du maillage pertinentes pour une
approche aux éléments finis il n’y a pas de distinction entre les éléments constitutifs de la structure et du
matériau. Par contre, en ce qui concerne l’outil de calcul développé dans cette thèse, une interprétation des
caractéristiques géométriques des éléments autonomes de la structure est nécessaire. Un premier maillage
nécessaire considère la description de la géométrie des frontières du volume de chaque élément par rapport
à ses voisins. Le maillage polygonal plus dense de chaque élément constitue l’étape suivante. Pendant la
création des polyèdres du maillage, l’orientation du clavage réel des éléments constitutifs de la maçonnerie
(des pierres monolithes) doit être respectée, une condition imposée par l’hypothèse d’Heyman interdisant le
glissement entre deux éléments. On envisage, donc, un maillage où l’orientation des blocs-mailles est telle
que les joints rencontrent la courbe directrice (cf. paragraphe 1.4.2) de chaque élément le plus verticalement
que possible (par exemple, le maillage radial d’un arc pour la discrétisation du modèle). En parallèle, on doit
considérer un nombre raisonnable de polyèdres et respecter les conditions de régularité de leur forme. Il est
souhaitable de retenir des mailles qui approchent les dimensions réelles des éléments de la maçonnerie.
Cependant, si l’on manque d’informations sur ces dimensions, il est souhaitable de pouvoir effectuer un
maillage très dense pour l’affranchir de la taille des voussoirs (cf. paragraphe 2.2.1.1). Pour récapituler, les
caractéristiques nécessaires du maillage destiné à l’approche présentée dans le cadre de cette étude sont les
suivants. Le maillage doit :

• décrire des éléments autonomes et le voisinage avec d’autres éléments,

<!-- p. 103 -->

80 1 Contexte du travail

• respecter l’orientation du clavage principale de chaque élément,

• être suffisamment dense pour décrire le volume des éléments constitutifs de la maçonnerie ou
s’affranchir de la taille de ces éléments.

La séparation des éléments autonomes est bien incorporée dans le logiciel OGIVES de l’ARIAM
puisqu’il s’agit de la procédure qui permet la réalisation des modèles tridimensionnels. La coupe de la Figure
1.47 nous permet d’apercevoir la distinction entre les différents éléments qui constituent l’ensemble de la
structure (on distingue la géométrie des arcs, des arcs-boutants, des piliers et des jonctions entre eux
formées par les tas de charge).

Dans cette thèse des simulations mécaniques bidimensionnelles sont proposées. Il y a deux options
pour l’acquisition du modèle du système structural, c’est-à-dire de la géométrie et du maillage. La première
est que la géométrie du système provient d’un modèle tridimensionnel en réalisant des coupes verticales.
Dans le cas du modèle tridimensionnel produit avec le logiciel OGIVES, l’interface avec l’outil de calcul
s’effectuerait après le maillage (par conséquent, le maillage polyédrique du modèle est transformé à un
maillage polygonal). La deuxième option, réalisée pour les applications présentées aux chapitres suivants, est
que la géométrie du modèle et sa discrétisation sont générées dans l’outil de calcul.

<!-- p. 104 -->

1.6 Conclusion du Chapitre 1 81

1.6 Conclusion du Chapitre 1

Le sujet de cette thèse concerne le développement d’un outil pour une évaluation préliminaire de la
stabilité des structures maçonnées anciennes, utilisable dans le domaine de la réhabilitation de monuments
historiques. Dans ce chapitre introductif les particularités principales qui sont rencontrées pendant le
traitement de la stabilité de ces structures ont été présentées.

Le terme « maçonnerie » recouvre un grand nombre de configurations constructives. La complexité
de ce matériau rend délicate l’analyse de la stabilité d’une structure maçonnée. Hétérogène et anisotrope, la
«maçonnerie » peut être analysée suivant trois approches: les méthodes qui considèrent la structure à son
échelle globale, celles qui se basent sur l’échelle des éléments constitutifs de la maçonnerie (pierres et joints)
et les méthodes combinant les deux échelles. Un des objectifs principaux de l’outil proposé dans cette thèse
est d’être applicable à un grand nombre de structures sans préciser le type de maçonnerie utilisée. Ainsi,
avons-nous choisi l’utilisation d’une méthode qui se base sur l’échelle de la structure globale et dans laquelle
le matériau est traité comme homogène et continu. Plus précisément, on a travaillé avec le théorème statique
du Calcul à la Rupture.

La théorie du Calcul à la Rupture présente le cadre scientifique pour une formulation du problème
compte tenu des informations que l’on dispose : la géométrie bidimensionnelle de structure et le critère de
résistance du matériau. Elle apporte la meilleure réponse possible qui se concrétise avec la définition d’une
stabilité potentielle de la structure. Cette réponse partielle sur la stabilité de la structure est le prix à payer
pour le manque d’informations considérant la loi de comportement du matériau. Le critère de résistance
adopté est celui du matériau sans traction suivant lequel la maçonnerie n’a aucune résistance à la traction, sa
résistance en compression est infinie et le phénomène de glissement n’apparaît pas. Il s’agit d’un critère très
général qui peut correspondre à un grand nombre de structures car il met en évidence le type de rupture
habituellement rencontré aux structures maçonnées à cause de rotations entre les voussoirs.

L’approche statique du Calcul à la Rupture a été considérée la plus pertinente pour la formulation du
problème étant donné que l’on vise à étudier des systèmes structuraux complexes décrivant de typologies
architecturales variées. Dans le cas des systèmes structuraux complexes, l’approche cinématique, exigeant la
définition de mécanismes de rupture potentiels, deviendra fastidieuse. De plus, suivant l’approche statique par
l’intérieur la vérification de stabilité est réalisée au moyen de la ligne de pression qui est une notion
compréhensible par divers disciplines qui peuvent intervenir dans le domaine de réhabilitation des structures
maçonnées anciennes. On se base sur la méthode du réseau de forces proposée par O’Dwyer (1999) pour
construire la ligne de pression car cette méthode donne une grande flexibilité à la formulation numérique du
problème.

<!-- p. 105 -->

82 1 Contexte du travail

La modélisation géométrique de la structure constitue la phase initiale pour une simulation mécanique
d’une structure et le type du modèle géométrique choisi joue un rôle important sur les résultats de l’analyse.
Pour l’outil de calcul de stabilité proposé dans cette thèse il est indispensable d’avoir un modèle où la
géométrie et les frontières de chaque élément constitutif de la structure (arc, arc-boutant, pilier etc.) sont
décrites. En ce qui concerne les objectifs du calcul envisagé pour cet outil, un modèle paramétrique est le
plus approprié car il donne la possibilité d’étudier plusieurs aspects d’une structure (géométries déformées,
typologies architecturales différentes etc.).

Le développement de l’outil et trois applications aux systèmes structuraux inspirés des édifices
médiévaux sont présentés dans les deux chapitres suivants.

<!-- p. 106 -->

Chapitre 2

Développement d’un outil de

simulation du comportement des

structures maçonnées

Résumé du Chapitre 2

Le deuxième chapitre est consacré à l’exposé des principes sur lesquels est basé l’outil
de calcul de stabilité des structures maçonnées développé. Les édifices médiévaux constituent le
cas d’étude traité. La présentation de l’outil est effectuée à travers de l’analyse d’un système
structural simple. Sur un tel système, on réalise les applications initiales de la méthodologie
adoptée pour l’évaluation de la stabilité des structures maçonnées. On procède à l’exploration
du comportement de systèmes plus exigeants dans le chapitre suivant.
Le chapitre s’ouvre avec une présentation de la méthode de réseau de forces sur laquelle
on s’appuie pour étudier les éléments structuraux principaux de l’architecture médiévale.
Avant de traiter un système structural complet, on examine séparément les éléments
structuraux principaux. Tout d’abord, la stabilité de l’arc est étudiée sous chargement vertical
ainsi que sous chargement horizontal (chargement sismique imposé de la manière quasistatique). Les états limites de l’arc sont exprimés au moyen de la ligne de pression qui est tracée
en fonction de la réaction horizontale aux supports de l’arc. La prescription de l’équilibre
statique dans chaque point du réseau de forces, implique que la méthode équivaut à la
considération de l’équilibre statique de corps rigide de chaque voussoir de l’arc.
La même démarche est suivie pour l’étude de la stabilité des arcs-boutants. La stabilité
des éléments verticaux, tels que les piliers, les culées et les contreforts soumis à des chargements
verticaux ou horizontaux, est étudiée en considérant l’équilibre des forces et des moments
exercés sur des coupes horizontales dans ces éléments. Finalement, pour le traitement des
jonctions qui relient les éléments structuraux de l’architecture médiévale, une procédure
itérative est proposée pour la localisation du point de croisement des lignes de pression de
différents éléments. En particulier, on examine différentes possibilités pour le comportement de
la jonction : jonction se comportant comme corps rigide, jonction obéissant au modèle de
matériau sans traction.

83

<!-- p. 107 -->

Les analyses des éléments structuraux distincts permettent de mettre en œuvre une
méthode d’analyse d’un système structural simplifié. Il s’agit d’un système symétrique se
composant d’un arc et de deux arcs-boutants, supportés par quatre éléments verticaux. Ce
système simplifié permet d’explorer et de comprendre le couplage entre les éléments différents
dans une structure réelle. Le système s’avère être un outil pratique pour la compréhension
d’aspects tels que l’influence de la hauteur d’un pinacle sur la stabilité du système, l’effet du
comportement de la jonction (jonction rigide ou jonction sans traction), les différences obtenues
selon l’hypothèse adoptée pour les supports de l’arc (appuis verticaux ou contreventements
horizontaux) etc. La théorie du Calcul à la Rupture permet d’exprimer les états admissibles du
système au moyen d’un domaine dans l’espace des poussées admissibles pour l’arc et l’arc
boutant, qui varie selon le niveau des chargements imposés sur la structure (chargements
verticaux ou horizontaux). On montre que les poussées admissibles de l’arc et de l’arc-boutant
dans le système couplé sont différentes de celles obtenues si ces éléments sont étudiés
séparément.
Ensuite, on présente les conclusions obtenues par la comparaison du système étudié
avec des résultats obtenus par des analyses du système aux éléments finis et aux éléments
discrets. La nécessité de l’adoption des coefficients relatifs à la traction et au glissement est
discutée pour les calculs de la stabilité du système effectués. On présente, aussi, quelques
considérations autour de l’épaisseur minimale d’un arc en plein cintre, calculées avec des
méthodes du Calcul à la Rupture présentées au chapitre précédent. Le deuxième chapitre
s’achève avec des études paramétriques sur les régions susceptibles pour la formation des
rotules et sur les poussées extrêmes possiblement développées dans un arc en plein cintre sous
chargements verticaux et horizontaux en fonction de son épaisseur.

84

<!-- p. 108 -->

2 Développement d’un outil de
simulation du comportement des
structures maçonnées

L’objectif de l’outil de calcul proposé dans cette thèse est de réaliser une évaluation rapide et
facilement abordable par l’utilisateur de la stabilité d’une structure de géométrie donnée. La stabilité des
systèmes structuraux bidimensionnels, décrivant des coupes d’édifices médiévaux, a été étudiée avec une
méthode basée sur l’approche statique du Calcul à la Rupture. La géométrie et le maillage de ces systèmes
bidimensionnels correspondent à ceux du logiciel OGIVES de l’ARIAM en réalisant des coupes verticales au
modèle tridimensionnel. Cependant, il faut noter que l’objectif de cette thèse est de développer un outil de
calcul de stabilité autonome, ainsi la géométrie et le maillage des systèmes bidimensionnels sont générés
automatiquement par une procédure intégrée dans l’outil.

Des simulations mécaniques peuvent être réalisées sur des coupes qui comportent les éléments
typiques de l’architecture médiévale combinés de façons variables. Ces éléments sont l’arc et l’arc-boutant,
ainsi que les éléments verticaux tels que les piliers, les culées et les contreforts. Une fois la géométrie et le
maillage du système définis, la deuxième étape consiste à appliquer le chargement au système structural.
L’outil donne la possibilité pour la simulation de trois cas de chargement : chargement sous poids propre,
chargement extérieur vertical et chargement sismique. Le chargement sismique est imposé sur le système
de la manière quasi-statique. Pendant la troisième étape, la vérification de la stabilité de la structure est
effectuée au moyen de l’approche statique du Calcul à la Rupture. A la dernière étape de la procédure, les
résultats sont représentés au moyen de lignes de pression qui sont tracées pour la structure entière. La ligne
de pression donne une représentation des conditions d’équilibre en compression pour un chargement donné.
Les résultats sont également exprimés sous forme de diagramme du domaine d’équilibre. L’utilisateur peut
faire entrer les caractéristiques de la géométrie, la densité du maillage et le type du chargement au moyen
d’un fichier MsEXCEL. La programmation des algorithmes des calculs pour l’évaluation de la stabilité ont été
réalisées avec le logiciel Scilab (INRIA, ENPC) qui fournit aussi les résultats sous forme graphique
représentant la structure entière avec sa ligne de pression. Les diagrammes du domaine d’équilibre de la

85

<!-- p. 109 -->

86 2 Développement de l’outil

structure sont générés automatiquement dans un fichier MsEXCEL. La Figure 2.1 représente
schématiquement l’architecture logicielle de l’outil.

Figure 2.1 - L’architecture logicielle de l’outil

En premier lieu, nous présenterons la méthode d’évaluation de la stabilité qui est adopté pour le
développement de l’outil et qui constitue une concrétisation de l’approche statique du Calcul à la Rupture. Il
s’agit d’une méthode proposée par O’Dwyer (1999) pour un arc soumis à la gravité. Ensuite, nous
présenteront les étapes de développement de l’outil. La mise en œuvre de ces étapes concernent
essentiellement la considération de l’équilibre des éléments structuraux séparément, ce qui permettra de
procéder à la simulation d’un système structural simple (que l’on appellera académique).

.

<!-- p. 110 -->

2.1 La méthode d’O’Dwyer 87

2.1 La méthode d’O’Dwyer

L’évaluation de la stabilité des systèmes examinés est basée sur la méthode du réseau de forces
proposée par O’Dwyer (1999). L’idée principale de la méthode est de représenter l’état de contraintes dans
la structure comme un réseau de forces équivalent et d’optimiser sa forme.

Sur la Figure 2.2, on présente l’équilibre global d’un assemblage de n blocs. On introduit la
convention suivante par rapport aux réactions qui s’exercent entre les blocs. La force F i est la réaction du
bloc i-1 vers le bloc i (i=1,2,…n). Alors, sur un bloc i, s’exercent les réactions F i et - F i +1 des blocs
G
voisins i-1 et i+1 respectivement et on impose un chargement W i dans la direction verticale. On peut ainsi
examiner l’équilibre pour chaque bloc i.

Figure 2.2 - L’équilibre d’un assemblage de blocs

G G
D’après le théorème d’équilibre de trois forces les lignes d’action des forces iF et - iF +1 doivent être
G
concourantes sur la ligne d’action du chargement Wi , ce qui signifie que la somme des moments est nulle :
G G
(2.1) M i = 0 ∑

Pour satisfaire l’équilibre au nœud i, il faut que la somme vectorielle des forces appliquées soit nulle :
G G
F = 0 ⇒ ∑(2.2) G G G G
Fi − Fi +1 + Wi = 0

Si l’on prend l’équilibre dans la direction horizontale :

<!-- p. 111 -->

88 2 Développement de l’outil

Fx = 0 ⇒ ∑
(2.3) Fx , i − Fx , i +1 = 0 ⇒
Fx , i = Fx , i +1 = H

Il est clair que la force horizontale H est constante partout dans le système dans le cas d’un
chargement qui n’est appliqué que dans la direction verticale. On appellera cette force « poussée » H.

Dans la suite, on étudiera, à titre d’exemple, l’équilibre d’un assemblage de trois blocs. Ce système
est transformé en un système de trois nœuds dont les abscisses sont identifiées aux abscisses des centres
de gravité de chaque bloc et dont les ordonnées restent à être déterminées. Le système initial est alors
transformé en un système de trois forces en chaque nœud (Figure 2.3). Les forces qui se rencontrent en
chaque nœud doivent être en équilibre. Les contraintes imposées par l’équilibre statique de chaque nœud
peuvent être formulées à l’égard des hauteurs inconnues des trois nœuds ( z i −1 , z i , z i +1 ). Les nœuds seront
déplacés verticalement pour assurer l’équilibre des forces. Pour que le nœud i soit en équilibre, les
G G
composantes verticales des forces iF et - iF +1 qui se rencontrent au nœud i, plus le chargement appliqué
au nœud i, doivent donner une force résultante nulle.

Figure 2.3 - Equilibre aux 3 nœuds du réseau

<!-- p. 112 -->

2.1 La méthode d’O’Dwyer 89

G
On désignera par Wi le chargement vertical à chaque nœud i. Ce chargement peut inclure le poids
K
propre du bloc iV ainsi qu’un chargement vertical extérieur exprimé au moyen d’un facteur multiplicateur λ.
Le chargement vertical total de chaque bloc sera :
G K
(2.4) Wi = (1 + λ) Vi

Alors l’équilibre dans la direction verticale au nœud i donne :

Σ Fz = 0 ⇒
(2.5)
Fz , i − Fz , i +1 − W i = 0

En introduisant la force horizontale H l’équilibre est reformulé ci-dessous :

zi − zi −1 Fz,i = H
xi − xi −1
− zi zi +1 Fz,i +1 = H
xi +1 − xi
(2.6)
− z i zi − zi −1 zi +1 H − H = W i
xi − xi −1 xi +1 − xi
⎛ H H ⎞ ⎛ H ⎞ ⎛ H ⎞
⎜ + ⎟ zi − ⎜ ⎟ zi −1 − ⎜ ⎟ zi +1 = Wi
⎝ xi − xi −1 xi +1 − xi ⎠ ⎝ xi − xi −1 ⎠ ⎝ xi +1 − xi ⎠

En écrivant cette équation pour tous les nœuds, on forme le système linéaire :

(2.7) K z = W

où z T = ( z1 , z 2 ,... nz ) est le vecteur des ordonnées des nœuds du réseau de forces, W T = (W1 , W2 ,...Wn )
est le vecteur qui comporte les chargements verticaux appliqués à chaque nœud et K une matrice (n, n) où
n représente le nombre des nœuds dans le système. Cette matrice regroupe les coefficients à appliquer aux
quantités zi pour satisfaire l’équation d’équilibre à chaque nœud. Cette matrice sera appelée matrice
d’équilibre. C’est une matrice tri-diagonale symétrique :

⎡ • • 0 0 0 ⎤
⎢ ⎥ • • • 0 0 ⎢ ⎥
K= ⎢ 0 • • • 0 ⎥
⎢ ⎥ 0 0 • • • ⎢ ⎥
⎢ ⎣ 0 0 0 • • ⎥⎦

<!-- p. 113 -->

90 2 Développement de l’outil

Les éléments de cette matrice ont la forme suivante :

⎛ H H ⎞
K i,i = ⎜ + ⎟ pour i = 1, 2 ,.......n
⎝ xi − xi −1 xi +1 − xi ⎠
H ⎫
(2.8) K i,i −1 = − ⎪ xi − xi −1 ⎪
⎬ pour i = 2 ,.......n − 1
H ⎪ K i,i +1 = −
xi +1 − xi ⎪⎭
Le vecteur z peut être déterminé en calculant l’inverse de la matrice K :

(2.9) z = K −1 W

À partir des coordonnées cartésiennes (xi, zi) de chaque nœud, on peut construire la ligne de
pression qui correspond au chargement appliqué. .

Pour vérifier si la ligne se trouve dans le contour de la structure on examine l’ordonnée zi de la ligne
de pression de chaque nœud i à l’égard des ordonnées zint,i et zext,i du contour intérieur (intrados) et
extérieur (extrados) de la structure pour la même abscisse du nœud :

(2.10) z int,i \< z i \< z ext,i

Cette méthode est appliquée aux deux éléments structuraux typiques de l’architecture médiévale :
l’arc et l’arc-boutant.

<!-- p. 114 -->

2.2 Stabilité des éléments structuraux 91

2.2 Etude de la stabilité des éléments structuraux

Dans ce paragraphe on présentera le traitement de la stabilité des éléments structuraux en
considérant qu’ils sont des structures élémentaires. Les cas étudiés sont l’arc, l’arc-boutant, le pilier et le
bloc qui forme la jonction entre trois éléments différents. En ce qui concerne le critère de résistance du
matériau, on introduit la même hypothèse pour tous les cas examinés. On considère que le matériau
constitutif des structures étudiées est un matériau sans résistance à la traction et avec une résistance à la
compression infinie. Si l’on représente les états de contraintes du matériau dans un plan par le cercle de
Mohr associé, on doit avoir :

(2.11) σ2 \< σ1 \< 0

On note que les contraintes sont positives en compression (Figure 2.4).

Figure 2.4 - Critère de résistance pour le matériau sans traction

En ce qui concerne le critère de résistance des interfaces d’appuis de la structure, on suppose que
la résistance tant en effort normal qu’en effort de cisaillement est infinie. Cette hypothèse permet de
s’affranchir de problèmes tels que le glissement ou le décollement le long des appuis de la structure et de ne
se concentrer que sur la stabilité du matériau dans la structure elle-même.

La procédure d’évaluation de la stabilité de chaque élément est divisée en quatre étapes.

a. Tout d’abord, on précise pour chaque structure les caractéristiques qui définissent sa géométrie
ainsi que son maillage.

<!-- p. 115 -->

92 2 Développement de l’outil

b. Ensuite, on applique trois types de chargement : chargement sous poids propre, chargement
vertical extérieur et chargement sismique (de manière quasi-statique). Le poids propre est défini par
le poids volumique γ de la maçonnerie. Afin de simplifier le traitement du problème on considère un
poids propre unitaire. Comme chargement extérieur, afin de ne pas alourdir l’exposé, on peut
considérer un chargement uniforme dans la direction verticale, défini par le facteur λ sur le poids
volumique (ce qui correspond à une structure de poids propre 1 + λ). Bien évidement, l’uniformité du
chargement extérieur n’est pas restrictive et on peut considérer n’importe quelle répartition de forces
verticales extérieures sur les nœuds du réseau. L’application du chargement sismique sera
développée au paragraphe 2.2.1.2

c. Les résultats graphiques de l’équilibre (exprimés au moyen de la ligne de pression) permettent de
vérifier la stabilité de la structure pour le chargement donné.

d. Ces résultats graphiques ainsi que les résultats numériques (exprimés en pourcentage du poids
propre de la structure) sont présentés en rapport avec les poussées admissibles pour chaque
structure élémentaire.

En effet, si l’on ne connaît pas la loi de comportement du matériau constitutif de la structure, il n’est
guère possible de déterminer la position « réelle » de la ligne de pression, bien qu’une inspection de la
structure puisse révéler des fissures et donc permettre la localisation des régions de transfert des forces
dans la structure. Pour déterminer la position de la ligne de pression, il faut introduire au moins la valeur de
la force horizontale H qui s’exerce aux extrémités de chaque structure. Or, dans la formulation du problème
nous n’avons pas introduit les caractéristiques de rigidité de la structure qui permettraient le calcul explicite
des réactions aux appuis de la structure et, par conséquent, la détermination de cette force horizontale.
Alors, on considère arbitrairement une valeur pour la force horizontale H et à partir de cette valeur on trace
la ligne de pression qui lui est associée à travers les conditions d’équilibre. Pour chaque valeur de H, on
peut donc obtenir les cas suivants :

• La ligne de pression franchit quelque part le contour géométrique de la structure : il s’agit d’un
état instable.

• b. La ligne de pression se trouve partout à l’intérieur du contour géométrique de la structure : la
structure est stable sous la combinaison de forces considérée (cf. paragraphe 1.4.2).

Il s’en suit que la stabilité de chaque structure est assurée si la ligne de pression se trouve à l’intérieur du
contour géométrique de la structure : la valeur de poussée H qui lui correspond est acceptable pour la
stabilité de la structure.

<!-- p. 116 -->

2.2 Stabilité des éléments structuraux 93

Pour chaque structure examinée, il est donc possible avec cette méthodologie de déterminer la
valeur minimale minH et maximale maxH de la force horizontale (état passif et état actif de la structure
respectivement, selon Heyman, 1995) qui correspondent à un état stable pour la structure. Il est clair que la
détermination des ces deux valeurs caractéristiques conduit à un problème d’optimisation sous contraintes.
On cherche à maximiser ou minimiser la valeur de la poussée H en respectant les conditions d’équilibre
dans le système (contraintes en forme d’égalités) et les conditions géométriques pour les ordonnées des
nœuds, qui doivent se trouver dans le contour de la structure (contraintes en forme d’inégalités).

On note finalement que les deux valeurs minH et maxH forment l’intervalle des valeurs admissibles
qui peut être identifié en tant que domaine de résistance de la structure dans le sens de la théorie du Calcul
à la Rupture.

2.2.1 Arc

Dans ce paragraphe on présentera l’étude de stabilité d’un arc suivant la méthode du réseau de
forces. On considère un arc en plein cintre ABB΄A΄. Sa géométrie est définie par (Figure 2.5) :

a) le rayon intérieur Rintarc qui est égal à la demi-largeur intérieure.

b) le rayon extérieur Rextarc qui est égal à la demi largeur extérieure.

c) la hauteur intérieure (ou flèche) Hintarc de l’arc.

On introduit aussi le rapport ogival RO qui caractérise la forme de l’arc:

H int
(2.12) RO =
Rint

On remarque que pour un arc en plein cintre, ROarc = 100% (Hintarc = Rintarc) et pour un arc en tiers-point
(sommets d’un triangle équilatéral), ROarc = 173% (Hintarc = 3 Rintarc). La demi largeur moyenne et
l’épaisseur de l’arc sont égales à :

Rint + Re xt
(2.13) r =
2
(2.14) t = Re xt − Rint

Les deux rapports caractéristiques définissant la géométrie de l’arc sont les paramètres adimensionnels
ROarc et tarc/rarc. Alors pour l’arc étudié : ROarc = 1 et tarc/rarc = 0.25.

<!-- p. 117 -->

94 2 Développement de l’outil

Figure 2.5 - Les caractéristiques de la géométrie d’un arc en plein cintre

La mise en œuvre de la méthode d’O’Dwyer exige un découpage de la géométrie de l’arc en un
certain nombre de blocs : chaque bloc est représenté par un nœud et on construit le réseau de forces qui
passent par ces nœuds. Dans le cas d’un arc réel avec géométrie connue, les blocs de découpage de l’arc
peuvent être identifiés aux voussoirs de l’arc. Dans l’exemple étudié, on considérera un découpage radial en
n blocs identiques (O’Dwyer a proposé un découpage vertical, cf. Figure 1.29 du paragraphe 1.4.1.3). Pour
chaque bloc on définit la position du centre de gravité Gi et l’aire Si (Figure 2.6).

Figure 2.6 - Discrétisation de l’arc en plein cintre.

<!-- p. 118 -->

2.2 Stabilité des éléments structuraux 95

Le centre de gravité Gi de chaque bloc fixe l’abscisse du nœud correspondant dans le réseau de
forces. Les ordonnées des nœuds du réseau ne sont pas connues a priori et elles sont déterminées par
l’équilibre des forces qui s’exercent sur les nœuds.

2.2.1.1 Chargement sous poids propre

Afin de simplifier le traitement du problème on considérera que l’arc est soumis uniquement à son
G
poids propre pris égal à l’unité ( γ = 1 , λ = 0). Alors, le chargement vertical Wi de chaque nœud est égal au
K
poids propre iV de chaque bloc :
G G
Wi = Vi = γGS i ⇒(2.15)
Wi = S i

Les expressions (2.15) permettent de construire le vecteur de chargement W qui apparaît dans
l’équation (2.7). La matrice d’équilibre K (n, n) pour notre système peut être déterminée par les équations
(2.8) en considérant une valeur arbitraire pour la poussée de l’arc Harc. En inversant cette matrice, on
détermine à partir de l’équation (2.9), les ordonnées iz de chaque nœud et donc ses coordonnées
cartésiennes (xi, zi). Le dernier élément à préciser afin de construire la ligne de pression, sont les positions
où la poussée est exercée sur les supports de l’arc. On désigne par Mg et Md les points où les réactions
aux supports sont appliquées (Figure 2.7). Ces deux points sont contenus dans les intervalles définis par
l’épaisseur de l’arc (leur position en verticale est fixée : z g = z d = 0 ).

Figure 2.7 - Chargement vertical de l’arc

<!-- p. 119 -->

96 2 Développement de l’outil

La construction de la ligne de pression permet de vérifier si le système se trouve dans un état stable
ou pas pour la poussée et le point d’application considérés. En faisant varier les valeurs de la poussée et
son point d’application aux appuis, il est possible de déterminer les valeurs extrêmes de la poussée de
l’arc, minHarc (état passif) et maxHarc (état actif). On trouve que l’état passif de l’arc correspond à une
poussée minHarc = 14% de son poids propre et l’état actif à une poussée maxHarc = 27% de son poids
propre. Les lignes de pression qui correspondent à ces deux valeurs caractéristiques de la poussée, sont
représentées sur la Figure 2.8. Pour la représentation des lignes de pression, on introduit la convention
suivante : les lignes pointillées et continues correspondent respectivement à la valeur minimale et maximale
de la poussée appliquée aux extrémités de l’élément.

Les valeurs des poussées calculées respectent la condition que la ligne de pression ne franchit
nulle part les contours de la structure. Par conséquent ces valeurs de poussée définissent les états
potentiellement stables de la structure. Les lignes de pression qui correspondent aux valeurs extrêmes de la
poussée permettent d’envisager le mécanisme de rupture qui tend à se produire en surpassant ces valeurs.
Dans le cas de l’arc en plein cintre avec t/r = 0.25 on distingue les deux cas suivants : a. l’état passif de
l’arc, qui correspond à une augmentation de l’écartement1 de l’arc avec la création de trois rotules ; une
rotule à l’extrados de la clé de l’arc et deux rotules symétriques au point X1 à l’intrados à un angle β = 64.14o
de l’axe Oz et b. l’état actif de l’arc lors duquel les appuis de l’arc s’approchent1 avec la formation des trois
rotules ; deux rotules symétriques à l’extrados aux points d’appui et une rotule à l’intrados à la position de la
clé. Les positions des rotules ainsi déterminées sont approximatives puisque le calcul ne prend pas en
compte le découpage réel de la structure en voussoirs : à une structure réelle les rotules seront formées aux
joints proches des positions déterminées avec la procédure présentée.

1 L’application du théorème statique du Calcul à la Rupture présuppose que la géométrie de la structure est faiblement
affectée par les déformations de façon que les équations d’équilibre ne sont affectées non plus.

<!-- p. 120 -->

2.2 Stabilité des éléments structuraux 97

Figure 2.8 - Etat passif (minHarc) et état actif (maxHarc) de l’arc

Dans la Figure 2.8 la ligne de pression a été construite pour une discrétisation de l’arc beaucoup
plus dense que celle qui apparaît dans la Figure 2.6. L’influence du découpage sur les valeurs extrêmes de
la poussée de l’arc en plein cintre de t/r = 0.25 est présentée dans le Tableau 2.1. Le tableau présente les
poussées minHarc et maxHarc en pourcentages du poids propre de l’arc pour des densités variables de
discrétisation. On note que les valeurs des poussées extrêmes de l’arc sont stables à partir d’une
discrétisation de 22 blocs-voussoirs. C’est le nombre minimal de blocs qui sera utilisé dans nos calculs pour
s’affranchir de l’effet de la taille des blocs sur les valeurs extrêmes des Harc obtenues.

Nombre de 3 4 8 12 18 22 26 30
voussoirs

non minHarc/Varc_circ 17.24% 14.59% 14.33% 14.19% 14.12% 14.12% 14.12% stable

non
maxHarc/Varc_circ 26.57% 27.45% 27.59% 27.63% 27.68% 27.72% 27.72% stable

Tableau 2.1 - Poussées extrêmes de l’arc en plein cintre de t/r = 0.25 pour densités variables de discrétisation

2.2.1.2 Chargement sismique: approche quasi-statique

Dans le présent paragraphe on traite le problème de la stabilité de l’arc qui est soumis à son poids
propre et à une sollicitation sismique imposée de manière quasi-statique. Lors de l’excitation du
système, des forces d’inertie se développent dans le volume de l’arc dues à sa vibration sismique. Le

<!-- p. 121 -->

98 2 Développement de l’outil

problème est simplifié en considérant que les forces d’inertie se développent dans la direction horizontale
uniquement et qu’elles sont uniformes dans le volume de l’arc. On note que l’accélération sismique verticale
peut être introduite directement en modifiant le poids propre de la structure (paramètre λ cf. paragraphe 2.2).
La prise en compte du chargement sismique peut être effectuée dans la méthodologie présentée en ajoutant
la force d’inertie horizontale qui se produit à chaque bloc sur le nœud correspondant (Figure 2.9).

Figure 2.9 - Chargement sismique de manière quasi-statique d’un arc

La force d’inertie horizontale de chaque nœud i est donnée par l’expression suivante :

(2.16) H s,i = mi K s g

où K s g représente l’accélération horizontale développée dans la structure lors du séisme et mi la masse de
chaque bloc.

Ce problème peut être ramené à une configuration identique à celle traitée dans le paragraphe
précédent (chargement sous poids propre) en introduisant un nouveau système des coordonnées Ox΄z΄
(Figure 2.10) qui est incliné par rapport au système initial Oxz à un angle φ, donné par l’expression
suivante :

−1 H s −1 K s mg −1(2.17) ϕ= tan = tan = tan K s
V mg

<!-- p. 122 -->

2.2 Stabilité des éléments structuraux 99

Figure 2.10 - Changement du système des coordonnées pour simulation du chargement sismique

Il s’ensuit que la force résultante W′i sur chaque nœud i est donnée par l’expression:
G G G
(2.18) Wi ′= Vi + H s , i pour i = 1...n

Cette force suit le nouvel axe vertical Οz΄, ce qui permet d’utiliser la méthodologie du paragraphe
précèdent pour le calcul de la ligne de pression. On écrit la poussée de l’arc H′arc , alignée sur le nouvel axe
horizontal Ox΄, en fonction de la réaction Rd à l’extrémité droite de l’arc :
(2.19) H arc′ = Rd cos(δ− ϕ)

où δ est l’angle entre la direction de la force Rd et l’axe horizontal Οx. Les équations (2.6) exprimant
l’équilibre dans la direction verticale se transforment pour i=1,2,….n:

z' i − z' i −1 z' i +1 − z' i Η arc′ − Η arc′ = Wi ′ ⇒
x' i − x' i −1 x' i +1 − x' i
(2.20)
⎛ Η arc′ Η arc′ ⎞ ⎛ Η arc′ ⎞ ⎛ Η arc′ ⎞ ⎜ + ⎟ z' i − ⎜ ⎟ z' i −1 − ⎜ ⎟ z' i +1 = Wi ′
⎝ x' i − x' i −1 x' i +1 − x' i ⎠ ⎝ x' i − x' i −1 ⎠ ⎝ x' i +1 − x'i ⎠

En écrivant cette équation pour tous les nœuds en forme matricielle on obtient :

<!-- p. 123 -->

100 2 Développement de l’outil

(2.21) K z ′ = W ′

où z 'T = ( z '1 , z ' 2 ,... z ' n ) est le vecteur des ordonnées des nœuds du réseau de forces dans le nouveau
système de coordonnées Ox΄z΄. Le vecteur W ′ T = (W1′, W2′,...Wn′) comporte, pour i = 2,…..n-1, les
résultantes des forces (poids propre + force d’inertie horizontale) appliquées sur les nœuds.
G G G G
(2.22) Wi ′ = Wi ′ = Vi + H s , i pour i = 2...n − 1

Pour le calcul des éléments W′1 et W′n on raisonne comme suit :

Les coordonnées des points d’application des réactions Mg et Md, ont été modifiés dans le nouveau
système de coordonnées Ox΄z΄, suivant les expressions :

x ' g = x g cos(ϕ)
(2.23)
z ' g = x ' g sin(ϕ)

x 'd = xd cos(ϕ)
z 'd = xd sin(ϕ)

Alors les ordonnées de ces points ne sont plus nulles ( z g ≠ ,0 z d ≠ 0 ) : les W′1 et W′n sont donc
donnés selon les équations (2.6) par les expressions :

⎛ H arc′ ⎞ W1′ = W1′ + ⎜ ⎟ z' g ⎜
⎝ x'1 − x' g ⎟⎠(2.24)
⎛ H arc′ ⎞ Wn′ = Wn′ + ⎜ ⎟ z' d
⎝ x' d − x' n ⎠

Les éléments de K s’écrivent :
H arc′ H arc′ K i,i = + pour i = 1, 2 ,.....n
x' i − x' i −1 x' i +1 − x' i
H arc′ ⎫
(2.25) K i,i −1 = − ⎪ x' i − x' i −1 ⎪
⎬ pour i = 2 ,.....n − 1
H arc′ ⎪ K i,i +1 = −
x' i +1 − x' i ⎪⎭

et les ordonnées des nœuds dans le nouveau système de coordonnées sont déterminées par la résolution
du système linéaire :

(2.26) z ′ = K −1 W ′

<!-- p. 124 -->

2.2 Stabilité des éléments structuraux 101

Une fois les ordonnées des nœuds déterminées, on peut tracer la ligne de pression en reliant les
positions obtenues des nœuds du réseau de forces. Il est évident que la ligne de pression se réfère à la
géométrie de l’arc décrite dans le système de coordonnées original.

On note ici que les poussées sur les deux supports de l’arc ne sont plus égales. Leur somme
algébrique est égale à la force sismique totale exercée au système. On appellera « poussée » de l’arc Harc
la force qui suit la direction du séisme (c'est-à-dire la composante horizontale de la réaction sur l’appui qui
est dans le même sens de l’accélération sismique et présente le module le plus faible entre les deux
réactions, Figure 2.11).

La Figure 2.11 présente la ligne de pression pour l’arc en plein cintre avec t/r = 0.25 au système de
coordonnées initial, pour un chargement sous poids propre et sous un chargement sismique de Ks = 0.37 : il
s’agit de la valeur maximale de l’accélération horizontale sismique supportée pour qu’il y ait au moins une
ligne de pression contenue dans l’aire de l’arc. On peut noter quatre points susceptibles à la formation de
rotules, ce qui constitue un cas instable. Dans une structure réelle, les imperfections de la géométrie
auraient comme effet de ne pas permettre la formation de ces quatre rotules simultanément. On constate
que la ligne de pression s’incline graduellement vers la direction opposée à la direction du séisme. Cette
inclinaison est d’autant plus importante que les forces d’inertie dues au séisme augmentent. Pour Ks = 0.37
la rotule à la clé est formée à φ = atan(0.37) = 20.3o. On note que l’on peut avoir la même forme de la ligne
de pression dans le cas d’un arc soumis à son poids propre et avec un tassement de l’appui droit (Heurta,
2005).

Figure 2.11 - Ligne de pression de l’arc (chargement sous poids propre et sismique, Ks=0.37)

<!-- p. 125 -->

102 2 Développement de l’outil

La valeur d’accélération Ks = 0.37 ne constitue qu’une borne inférieure de l’accélération nécessaire
pour la création du mécanisme de rupture et peut servir comme une première estimation de la stabilité des
structures existantes. Il faut noter que cette valeur est en général très conservative afin de juger la stabilité
de la structure sous séisme qui est un phénomène qui se produit dans une certaine durée. Cependant, on
peut constater que la stabilité du système est assurée pour n’importe quelle durée si l’accélération est
inférieure à la valeur seuil Ks = 0.37 (cf. paragraphe 2.3.3).

2.2.2 Arc-boutant

On examinera dans ce paragraphe la stabilité du deuxième élément caractéristique de l’architecture
médiévale : l’arc-boutant. On considère l’arc-boutant BCJG (Figure 2.12), dont l’intrados est formé d’un
quart de cercle de rayon Rintab (rapport ogival ROab = 100%) et dont l’extrados est formé d’une ligne droite
décrite par l’équation : z = − x + R ' .

Figure 2.12 - La géométrie de l’arc-boutant étudié

2.2.2.1 Chargement vertical

Pour chargement sous poids propre, le traitement de l’arc-boutant par la méthode de réseau de
forces, suit les mêmes lignes que celui de la stabilité de l’arc. Le découpage radial et le chargement
correspondant sont présentés sur la Figure 2.13.

<!-- p. 126 -->

2.2 Stabilité des éléments structuraux 103

Figure 2.13 – Discrétisation et chargement vertical de l’arc-boutant

Dans ce cas, la poussée Hab est appliquée au bloc extrême supérieur de l’arc-boutant (bloc 1 sur la
Figure 2.13) en point N g dont les coordonnées sont :
(2.27) ( x N , z N ) = (0, z g )

L’équation (2.7) est transformée :

(2.28) Kz = W

où le vecteur W T = (W1 , W2 ,...Wn ) comporte, pour i = 2,…..n, le poids propre de chaque bloc comme dans
l’arc (equation (2.15)). Selon les équations (2.6), il s’ensuit que l’élément W1 de ce vecteur devient :
⎛ H ab ⎞(2.29) W1 = V1 + ⎜ ⎟ z g ⎜
⎝ x1 − x g ⎟⎠

En dehors de cette différence, on procède de la même manière que pour l’arc : on détermine les
coordonnées cartésiennes (xi, zi) de chaque nœud du réseau de forces et on trace la ligne de pression de
l’arc-boutant.

<!-- p. 127 -->

104 2 Développement de l’outil

Figure 2.14 - Ligne de pression pour les poussées extrêmes d’un arc-boutant (chargement vertical)

La Figure 2.14 présente les lignes de pression ainsi obtenues pour les deux valeurs extrêmes de la
poussée Hab. La valeur minimale de la poussée de l’arc-boutant vaut minHab = 12% de son poids propre.
Par ailleurs, la valeur maximale de la poussée maxHab est limitée par la résistance en compression de la
section minimale (Heyman, 1995) puisqu’il y a une ligne droite qui peut passer d’un côté à l’autre de la
géométrie de l’arc-boutant2.

2.2.2.2 Chargement sismique: approche quasi-statique

Une méthode similaire au traitement de l’arc est suivie pour l’analyse de l’arc-boutant sous
chargement sismique: des forces d’inertie horizontales sont introduites à chaque nœud (Figure 2.15)
représentant le chargement sismique imposé de manière quasi-statique.

2En considérant que la résistance en compression d’un arc-boutant (ou d’une ogive d’une voûte) est cent fois plus
importante que les contraintes développées (Heyman, 1995), on ne prendra pas en compte cette limitation.

<!-- p. 128 -->

2.2 Stabilité des éléments structuraux 105

Figure 2.15 - Chargement de l’arc-boutant sous poids propre et simulation du chargement sismique de la manière
quasi-statique

Dans la Figure 2.16 on représente les lignes de pression pour les poussées minimale (en pointillé) et
maximale (continue) de l’arc-boutant pour chargement sous poids propre combiné avec un chargement
sismique de Ks = 0.37.

Figure 2.16 - Ligne de pression de l’arc-boutant (chargement sismique, Ks=0.37)

<!-- p. 129 -->

106 2 Développement de l’outil

La poussée minimale appliquée à l’élément est égale à minHab = 0.1% de son poids propre et la
poussée maximale peut être considérée infinie. La poussée minimale peut contrebuter la poussée de l’arc
pour le même chargement horizontal présentée dans la Figure 2.11. Si l’arc est soumis à un chargement
horizontal appliqué dans la direction inverse de celle marquée dans la Figure 2.11, une poussée beaucoup
plus importante (telle que la poussée maximale présentée dans la Figure 2.16) doit se développer à l’arcboutant pour contrebuter la poussée à l’appui droit de l’arc. (La comparaison des états d’équilibre de ces
éléments est utile pour le développement d’un système structural qui les intègre, cf. paragraphe 2.3).

2.2.3 Pilier

Ensuite, on présentera l’étude de stabilité des piliers et, en général, des éléments verticaux (culées,
contreforts). Premièrement, on procède à un découpage horizontal inspiré par les assises des éléments
verticaux de la maçonnerie. On effectue des calculs d’équilibre de forces et de moments pour chaque maillebloc. Le découpage horizontal est défini par des segments UiFi où i=1,2…..n (Figure 2.17).

Figure 2.17 - Maillage du pilier, chargement sous poids propre et chargement sismique de manière quasi-statique

<!-- p. 130 -->

2.2 Stabilité des éléments structuraux 107

On calcule le centre de gravité Gi de chaque bloc i du pilier et on applique au système un
chargement vertical ne comportant verticalement que le poids propre de chaque bloc (λ = 0) ainsi qu’un
chargement sismique horizontal imposé de manière quasi-statique. Alors, les forces suivantes sont
G
appliquées à la partie du pilier définie par sa tête DC et le joint UiFi : a) la force R p qui correspond à la
G
réaction de l’élément qui est joint au côté DC, appliquée au point L, b) le poids propre iV , appliqué au
centre de gravité Gi de cette partie et c) la force d’inertie Hs,i. Les deux dernières forces sont
proportionnelles à l’aire de la partie DCFiUi (équations (2.15), (2.16)).

L’équilibre des moments et des forces de la partie DCFiUi permet de définir le point d’application Li
G
de la force Fb ,i nécessaire pour sa stabilité. En rejoignant les points Li, on construit la ligne de pression du
pilier. Les états potentiellement stables sont définis si la ligne est contenue dans l’aire définie par le contour
droit CF et gauche DU du pilier. La vérification de la stabilité, alors, a la forme suivante:

(2.30) x g , i \< x L ,i \< x d,i

Dans les calculs effectués dans cette thèse, tous les éléments verticaux seront découpés
horizontalement sur toute leur section. Généralement, on peut distinguer trois catégories de construction des
piliers (Cassinello, 2008) : les piliers monolithiques, les piliers constitués de plusieurs blocs de pierres et
ceux constituent d’un parement extérieur (en maçonnerie assisée) et d’un remplissage intérieur de mortier et
de pierres (en blocage). Principalement, dans la dernière catégorie, le séchage du mortier de remplissage
est possible et produit une réduction de la section effective pour la distribution des contraintes et des forces.
Cependant, dans notre calcul on considérera que la section effective est la section totale du pilier. Le cas de
la réduction de la section effective peut être intégré aux calculs avec l’application d’un coefficient
géométrique de sécurité (cf. paragraphe 2.5.1).

Comme on l’a déjà mentionné, les contraintes de compression développées dans les éléments
maçonnés d’une structure gothique représentent un faible pourcentage de la résistance en compression du
matériau (pour les piliers: 10% de leur résistance en compression selon Heyman, 2008). De ce fait, on ne
procède pas aux calculs des contraintes de compression sur un pilier même si il s’agit de l’élément le plus
sollicité comme il reçoit les charges de tous les éléments supérieurs. De même, on n’étudie pas le problème
du flambage des piliers car il s’agit d’un phénomène qui n’apparaît pas pour un pilier gothique à cause de sa
raideur. En effet, Heyman (2008) a calculé que pour un pilier maçonné articulé à sa tête, avec un rapport
longueur sur diamètre t/l = 10 et un module de Young E = 20 KN/mm2, la contrainte nécessaire pour avoir
du flambage est quatre fois plus grande que la contrainte nécessaire pour l’effondrement par rupture en
compression simple (et encore plus élevé pour un pilier encastré à sa tête).

<!-- p. 131 -->

108 2 Développement de l’outil

2.2.4 Jonction de plusieurs éléments

Dans ce paragraphe on discutera les méthodes pour étudier la stabilité du bloc de jonction, c’est-àdire du bloc où sont joints plusieurs éléments structuraux. Ce bloc constitue une zone importante de la
maçonnerie puisqu’il garantit que les charges sont transférées en sécurité (par exemple, de la nef à la partie
basse d’une structure). Dans les structures réelles, cette jonction est habituellement formée par le tas de
charge, c’est-à-dire les « assises de pierres à lits horizontaux que l'on place sur un point d'appui, sur une pile
ou un angle de mur entre des arcs, pour recevoir des constructions supérieures» (Viollet-le-Duc, 1856).

Une première approche peut consister à considérer la zone de la jonction comme bloc monolithique,
même s’il s’agit d’une hypothèse non valide, car on ne la rencontre pas dans les structures réelles. Afin de
prendre en compte un comportement non monolithique et chercher l’extension des lignes de pression de
chaque élément dans le bloc de la jonction, on propose la méthode présentée dans ce paragraphe. Dans
notre approche, on considère que ce bloc se comporte comme un matériau sans traction sans toutefois
prendre en compte le vrai découpage en pierres d’assises horizontales.

A titre d’exemple, on considère un bloc ABCD où sont joints trois éléments, un arc, un arc-boutant
et un pilier, aux côtés AB, BC et DC respectivement (Figure 2.18).

Figure 2.18 - Le bloc de jonction de trois éléments structuraux différents

<!-- p. 132 -->

2.2 Stabilité des éléments structuraux 109

On considère l’équilibre du bloc de la jonction ABCD où sont imposées les réactions de ces trois
G G G
éléments : de l’arc Rarc (appliquée au point M) ; de l’arc-boutant Rab (appliquée au point N) et du pilier R p
G
(appliquée au point L). On considère aussi le poids propre V ABCD du bloc. Si l’on prolonge la ligne d’action
de chaque réaction dans le bloc ABCD de manière rectiligne, on suppose que les trois lignes se
rencontrent au point I1.

Les segments AI1, BI1 et CI1 permettent la définition de la région d’influence de chaque élément,
c'est-à-dire la région de la jonction qui participe à la formation de la ligne de pression correspondante. Ainsi,
pour la ligne d’action de la réaction de l’arc étendue dans la jonction, la région d’influence dans la jonction
est le triangle ABI1. Similairement, pour la ligne d’action de la réaction de l’arc-boutant, la région d’influence
est le triangle BCI1 et finalement pour la ligne d’action de la réaction du pilier, la région d’influence est le
polygone AI1CD. On note que l’extension des lignes d’action des réactions dans la jonction a été faite sans
prendre en compte le poids propre de chaque région d’influence. Par conséquent, elle n’est pas exacte.

Afin de déterminer l’extension exacte des lignes de pression de chaque élément dans le bloc de la
jonction ABCD, il faut prendre en compte la réaction de chaque élément et le poids propre de chaque
région d’influence. Le problème alors concerne la détermination du point d’intersection I des trois droites
prolongeant les lignes d’action de réactions pour lequel l’équilibre est satisfait entre les réactions des
G G G G G G
éléments du système ( Rarc , Rab , R p ) et les poids propres des régions d’influence ( V1arc , V1ab , V1 p , Figure
2.19). On note que les poids propres des régions d’influence sont fonctions de la position du point I dont la
détermination dépend à son tour des valeurs de ces poids propres. On est ainsi amené à une procédure
itérative pour la détermination du point I : une estimation pour la position du point I est introduite, l’équilibre
est testé et s’il n’est pas satisfait, une correction de la position du point I est faite. La procédure est
poursuivie jusqu’à l’atteinte d’un critère de convergence qui garantit l’équilibre.

Dans la suite, on détaille la procédure itérative suivie pour la détermination du point I.

Procédure de définition du point I

a) On trouve le point d’intersection I1 des lignes d’action des réactions de l’arc et de l’arcboutant. Il s’agit de la première estimation pour la position du point I. A partir de ce point on définit les
régions d’influence correspondantes (triangle ABI1 pour l’arc et BCI1 pour l’arc-boutant).

b) Pour les régions d’influence ABI1 et BCI1, on détermine le module, la direction et le point
d’application de la force qui est nécessaire pour assurer l’équilibre des moments et des forces de chaque
région d’influence en tenant compte son poids propre ainsi que de la réaction provenant de l’élément
correspondant.

<!-- p. 133 -->

110 2 Développement de l’outil

Figure 2.19 - Equilibre des triangles ABI1 et BCI1

Pour la détermination du point d’application de la force nécessaire pour assurer l’équilibre pour

chaque région d’influence, on note les cas suivants :

G
• Triangle ABI1. Les forces exercées sur le triangle ABI1 sont la réaction de l’arc Rarc et son
G
poids propre V1arc . Soit I1arc le point d’application de la force qui équilibre ces deux forces. On distingue
deux cas séparés pour la position du point I1arc selon la position du point d’application M de la réaction
G
de l’arc Rarc et le centre de gravité du triangle.
G
a. Si le point d’application M de la réaction Rarc est à droite de la ligne d’action du poids propre
G
V1arc du triangle ABI1, la force qui équilibre les deux forces se développe au côté BI1 du triangle.
G
b. Si le point d’application M de la réaction Rarc est à gauche de la ligne d’action du poids propre
G
V1arc du triangle ABI1, la force qui équilibre les deux forces se développe au côté AI1 du triangle.
Ce cas est représenté sur la Figure 2.19.

• Triangle BCI1. Les forces exercées sur le triangle BCI1 sont la réaction de l’arc-boutant
G G
Rab et son poids propre V1ab . L’équilibre est assuré au point I1ab qui se trouve au côté CI1 du triangle
(Figure 2.19).

Si les points I1arc et I1ab sont les mêmes que I1 la procédure est terminée. Si non, on doit corriger la
position du point I.

<!-- p. 134 -->

2.2 Stabilité des éléments structuraux 111

c) On trace les droites définies par les points M - I1arc et N – I1ab. On trouve le point
d’intersection I2 de ces lignes : ceci constitue la nouvelle estimation pour la position du point I.

Figure 2.20 - Deuxième estimation du point d’intersection I

La procédure est répétée jusqu’au moment où les points définis par l’équilibre des régions
d’influence de l’arc et de l’arc-boutant coïncident. Le critère de convergence adopté porte sur la distance de
deux points d’intersection consécutifs Ii et Ii+1.

d) Ayant déterminé la position du point I avec une précision satisfaisante on introduit les
conditions imposées par l’équilibre du polygone AICD afin de construire la ligne de pression du pilier.

Il faut noter que la méthode proposée dans ce paragraphe est équivalente au cas où l’on examine
l’équilibre du bloc ABCD comme corps rigide. Cependant, la méthode proposée permet le tracé des lignes
de pression à l’intérieur du bloc de jonction et de vérifier donc les hypothèses du matériau sans traction. Les
conséquences sur la stabilité d’un système structural apportées par de différentes considérations du
comportement mécanique du bloc de la jonction seront développées dans le paragraphe 2.3.1.3.

<!-- p. 135 -->

112 2 Développement de l’outil

2.3 Système structural

Ce paragraphe est dédié à l’étude d’un système structural bidimensionnel qui permet d’explorer le
couplage des éléments présentés aux paragraphes précédents et surtout le phénomène de l’arc-boutement,
clef de la tenue mécanique de nombreux systèmes structuraux. L’étude de ce phénomène sera faite sur un
système pas réel, que l’on l’appellera académique et qui servira en tant qu’étape intermédiaire pour l’étude
du comportement de structures réelles présentée au chapitre suivant.

Ce système académique est symétrique par rapport à l’axe vertical Oz (Figure 2.21). Il comporte un
arc en plein cintre ABB΄C΄, supporté sur deux piliers symétriques ABFU. L’arc est retenu par deux arcsboutants symétriques BCJG, supportés sur deux culées symétriques JGQT. Tout le système est soumis à
son poids propre. On supposera que la résistance théorique sur les interfaces TQ, UF et leurs symétriques
tant en effort normal qu’en effort de cisaillement est infinie. La géométrie du système est définie par les
éléments suivants :

a) le rayon intérieur Rintarc de l’arc ABB΄C΄,

b) son épaisseur tarc,

c) la hauteur hp des deux piliers ADFU,

d) le rayon intérieur Rintab des arcs-boutants DGIJ,

e) l’épaisseur tcu des culées JGQT des arcs-boutants,

f) la pente a du côté BG des arcs-boutants DGIJ.

Pour le système examiné on supposera les proportions suivantes :

t arc t arc Rint ab t cuRO = 1, = 0.25, = 0.15, = 0 . 76, = 1 . 83
rarc h p Rint arc t arc

<!-- p. 136 -->

2.3 Stabilité d’un système structural 113

Figure 2.21 - Géométrie du système examiné : arc – arc-boutant – pilier

Il s’agit d’un système qui permet de comprendre le rôle couplé des deux éléments typiques de
l’architecture gothique : l’arc et l’arc-boutant dans l’ensemble de la structure. De tels systèmes ont été
examinés entre autres par Breymann (1849). La méthode présentée ici permet de surmonter l’ambiguïté par
rapport au traitement de la jonction des trois éléments (arc, l’arc-boutant et pilier) (Heyman, 1966,
concernant le traitement Breymann). Dans l’analyse qui suit, on considérera le bloc ABCD (jonction des
trois éléments ABPR, DGJG et CDUF) comme un élément séparé et on lui appliquera la procédure
présentée au paragraphe 2.2.4.

L’objectif de notre analyse est de construire une solution statique pour la stabilité de ce système,
exprimée au moyen de la ligne de pression que l’on doit tracer pour tous ses éléments structuraux. Pour le
faire, on introduit les deux forces horizontales Harc et Hab qui s’exercent aux extrémités de l’arc (PR et AB)
et de l’arc-boutant (BC et JG) respectivement. On déterminera les combinaisons des valeurs extrêmes des
forces Harc et Hab pour lesquelles le système est stable, c’est-à-dire, pour lesquelles la ligne de pression se
trouve partout à l’intérieur de la structure.

<!-- p. 137 -->

114 2 Développement de l’outil

2.3.1 Chargement sous poids propre

On examinera dans ce paragraphe le comportement du système uniquement sous poids propre.

2.3.1.1 Procédure et calculs

On a montré dans les paragraphes 2.2.1 et 2.2.2, considérant l’étude de stabilité de l’arc et de l’arcboutant examinés seuls, que la géométrie de chaque élément défini les poussées extrêmes admissibles pour
la détermination des états potentiellement stables de chaque élément. Afin d’étudier le comportement de ces
éléments dans un système structural, on vise à déterminer quelles combinaisons des poussées Harc et Hab
définissent les états potentiellement stables du système entier. Dans notre approche, la poussée de l’arc
sera le paramètre prédominant dans notre analyse (on commencera en prédisant toujours une valeur
d’Harc). Il s’agit d’une interprétation du fait que les éléments inférieurs servent essentiellement à supporter
l’arc central.

a. Procédure

Pour construire la ligne de pression du système entier, on suit les étapes suivantes :

\1. On examine l’arc seul et on détermine la valeur minimale minHarc et maximale maxHarc de la force
horizontale pour que l’arc soit stable.

\2. On considère que la valeur minHarc est la poussée effective de l’arc et on calcule la force horizontale
minimale minHab et maximale maxHab de l’arc-boutant pour que le système entier soit stable. Pour le faire,
on effectue une procédure itérative en changeant la force horizontale Hab de l’arc boutant et l’on examine à
la fois l’équilibre de la culée JGQT de l’arc-boutant (2a), du bloc de la jonction ABCD (2b) et du pilier
CDUF (2c).

\3. La procédure est terminée lorsque les valeurs extrêmes de Hab qui satisfont l’équilibre de tous les
éléments sont déterminées.

\4. Si l’équilibre n’est jamais satisfait on répète la procédure avec une valeur plus élevée pour la poussée
effective de l’arc.

\5. On répète la même procédure pour la valeur maxHarc et pour un spectre des valeurs de Harc entre
minHarc et maxHarc.

<!-- p. 138 -->

2.3 Stabilité d’un système structural 115

Dans la Figure 2.22 on présente schématiquement la procédure utilisée pour calculer toutes les
combinaisons possibles d’équilibre en considérant la poussée minimale minHarc de l’arc. Les étapes de 1 à
4 y sont marquées.

Figure 2.22 - Procédure itérative pour la définition des combinaisons possibles d’équilibre pour minHarc

Avec cette procédure on détermine toutes les poussées de l’arc et de l’arc-boutant admissibles pour
la stabilité du système. Il faut noter que même si le problème de la stabilité du système est réduit à la
définition des valeurs extrêmes des poussées Harc et Hab, la procédure de leur définition demande la
détermination du point d’application de chaque poussée aux extrémités de l’élément correspondant. Comme
le cas du système académique étudié ici est un cas de géométrie et de chargement symétrique par rapport
à l’axe Oz, les points d’application de la poussée de l’arc et de l’arc-boutant sont symétriques par rapport au
même axe.

Le contrôle de l’admissibilité des poussées considérées pour la stabilité du système est réalisé par
l’équation (2.10) pour l’arc et l’arc-boutant (cf. paragraphe 2.1) et de l’équation (2.30) pour les éléments
verticaux (cf. paragraphe 2.2.3). L’atteinte d’un état de stabilité est toujours signalée, ce qui permet à
l’utilisateur d’arrêter la procédure itérative.

<!-- p. 139 -->

116 2 Développement de l’outil

b. Construction de lignes de pression

Dans la suite, on présente les résultats graphiques pour les deux valeurs extrêmes de la force Harc
(Figure 2.23a pour minHarc et Figure 2.23b pour maxHarc). Pour chaque valeur extrême de Harc, on
présente les lignes de pression du système entier pour les deux poussées extrêmes admissibles de l’arcboutant. Pour la représentation des lignes de pression, on garde la convention utilisée dans le cas des
éléments étudiés seuls : les lignes pointillées et continues correspondent respectivement à la valeur
minimale et maximale de la poussée appliquée aux extrémités de chaque élément. Le calcul est fait avec
une discrétisation des éléments plus dense que celle qui apparaît sur la Figure 2.21(a) (sauf au bloc de la
jonction) pour s’affranchir de l’effet de la taille des blocs sur les valeurs extrêmes des poussées obtenues.
On note une brisure de la ligne de pression dans le cas de maxHarc et maxHab au niveau bas du bloc de la
jonction (Figure 2.23b, lignes continues). Dans ce cas le point d’intersection I des lignes de pression dans le
bloc de la jonction ABCD coïncide presque avec l’extrémité B du même bloc. La brisure vient du fait que le
bloc AICD n’est pas discrétisé.

Figure 2.23 - Lignes de pression du système pour : (a) minHarc, minHab \< Hab \< maxHab

(b) maxHarc, minHab \<Hab \< maxHab

<!-- p. 140 -->

2.3 Stabilité d’un système structural 117

c. Détermination des poussées extrêmes

• Premier cas : on calcule la poussée minimale de l’arc minHarc = 14% de son poids propre et
l’on détermine les valeurs minimale et maximale de la poussée de l’arc-boutant : minHab =
18% et maxHab = 73% de son poids propre (cas présenté dans la Figure 2.23a).

• Deuxième cas : on calcule la poussée maximale de l’arc maxHarc = 27% de son poids
propre. Pour cette valeur les valeurs minimale et maximale de la poussée de l’arc-
boutant sont minHab= 63% et maxHab = 91% de son poids propre (cas présenté dans la
Figure 2.23b)

Il faut noter que les valeurs extrêmes minHab et maxHab calculées avec la procédure présentée ne
sont pas les mêmes que celles obtenues par la considération de l’arc-boutant seul (où la poussée minimale
de l’arc-boutant est minHab=12% de son poids propre et la poussée maximale maxHab est limitée par la
résistance en compression de la section minimale, paragraphe 2.2.2.1). L’équilibre du système entier impose
des conditions supplémentaires sur la stabilité de l’arc-boutant. Les valeurs extrêmes de la poussée de l’arc
sont égales à celles calculées pour la considération de l’arc seul.

d. Détermination des rotules

Les points susceptibles de formation de rotules pour l’arc et l’arc-boutant sont décrits par les points i
où les différences z ext,i − z i et zi − zint, i sont minimisées ( iz sont les ordonnées de la ligne de pression,
z ext,i , z int,i les ordonnées du contour intérieur et extérieur respectivement, cf. équation (2.10)). Pour les
éléments verticaux, ces points sont décrits par les points i de minimisation des termes x ext,i − xi et xi − xint,i
( ix sont les abscisses de la ligne de pression, xd,i , x g,i les abscisses du contour droit est gauche
respectivement, cf. équation (2.30)).

On peut noter les points suivants par rapport à la fissuration du système:

• Si Harc = minHarc, minHab \< Hab \< maxHab (Figure 2.23(a)), on a le développement de
rotules sur la paroi extérieure en clé de l’arc (point P) et sur la paroi intérieure au point X1 (à
64.14o de l’axe Oz). En ce qui concerne l’arc-boutant, pour la valeur minHab, on a le
développement de rotules sur la paroi extérieure au point X2 (à 18o de l’axe Oz) et sur la
paroi intérieure au point X3 (à 55.8o de l’axe Oz). Similairement pour la valeur maxHab on a
le développement de rotules au point X4 (à 35.1o de l’axe Oz) sur la paroi intérieure de l’arc-
boutant. Finalement, dans le pilier CDUF, les points extrêmes U et F de la base sont

susceptibles à la formation de rotules.

<!-- p. 141 -->

118 2 Développement de l’outil

• Si Harc = maxHarc, minHab \< Hab \< maxHab (Figure 2.23(b)), on obtient des rotules sur la
paroi intérieure en clé de l’arc (point R) et au point extérieur B de la naissance de l’arc.
Dans l’arc-boutant, pour la valeur minHab on obtient des rotules au point X5 (à 5.4o de l’axe
Oz) et sur la paroi intérieure au point X6 (à 50.4o de l’axe Oz). Pour la valeur maxHab on a
la formation de rotules au point extrême B et sur la paroi intérieure au point X7 (à 48.6o de
l’axe Oz). Dans le pilier CDUF, les points extrêmes U et F de la base sont susceptibles à

la formation de rotules.

e. Domaine d’équilibre

Les calculs présentés permettent de définir le domaine de toutes les combinaisons admissibles des
poussées Harc et Hab pour le système. Le domaine d’équilibre du système est défini comme l’enveloppe
convexe des combinaisons des Harc et Hab qui définissent la stabilité potentielle de tous les éléments du
système (Figure 2.24); il s’agit d’une conséquence directe du théorème statique du Calcul à la Rupture (cf.
paragraphe 1.3.1.2). Dans notre représentation, on présente les poussées extrêmes de l’arc (en abscisse) et
de l’arc-boutant (en ordonnée) en pourcentage du poids propre de chaque élément ayant déjà considéré la
capacité des autres éléments d’assurer l’équilibre.

Figure 2.24 - Domaine d’équilibre du système

<!-- p. 142 -->

2.3 Stabilité d’un système structural 119

2.3.1.2 Effets stabilisants du système

Le système académique présenté dans la Figure 2.21 constitue le cas le plus simple pour étudier
l’interaction du comportement de l’arc et de l’arc-boutant. Dans ce paragraphe on présentera quelques
considérations sur les éléments rencontrés dans l’architecture gothique qui peuvent avoir un effet stabilisant
pour la structure.

Premièrement, on explorera le comportement du même système mais avec une augmentation hpp
de la hauteur des piliers au dessus du niveau de la naissance de l’arc (Figure 2.25).

Figure 2.25 - Géométrie du système examiné : arc – arc-boutant – pilier de hauteur augmentée

Dans la Figure 2.26, on présente trois cas différents du domaine d’équilibre. La ligne en pointillé
correspond au domaine d’équilibre du système sans augmentation de la hauteur des piliers (hpp = 0, Figure
2.21) et les lignes continues correspondent aux domaines d’équilibre du même système avec augmentation
de la hauteur des piliers (hpp = 0.50hp et hpp = 0.75hp, Figure 2.25).

<!-- p. 143 -->

120 2 Développement de l’outil

Figure 2.26 - Domaines d’équilibre du système pour différentes valeurs de hpp

Le domaine d’équilibre du système est élargi avec l’augmentation de la hauteur des piliers. Cet effet
positif stabilisant est dû à l’augmentation de la charge verticale au dessus du niveau de l’application de la
force oblique de réaction de l’arc. Dans le premier cas (hpp = 0), l’arc est supporté sur les deux piliers et les
appuis de l’arc sont considérés dans la direction horizontale (segment AB). Dans le deuxième cas, l’arc est
contre buté et ses appuis sont considérés dans la direction verticale (segment AX). Dans la Figure 2.27 on
présente, à titre d’exemple, le cas de la poussée maximale d’un arc en plein cintre. Les lignes continue et en
pointillé correspondent respectivement à la ligne de pression de l’arc contrebuté et de l’arc aux appuis
horizontaux. Pour chaque cas, on a appliqué une force horizontale de 32% du poids propre de l’arc en plein
cintre : pour cette valeur l’équilibre est possible seulement pour l’arc contre buté. On remarque que des
poussées plus élevées peuvent être appliquées sur l’appui vertical de l’arc (pour que la ligne approche
l’extrémité de l’appui horizontal B de l’arc) à cause de l’action du poids propre de la partie du pilier d’hauteur
hpp. Pour cela, le cas le plus courant est celui d’un arc contre buté. Les résultats de la Figure 2.26 sont
conformes à l’observation d’Heyman (1995), à savoir qu’il y a toujours un effet stabilisant des éléments, tels
que les pinacles, sur la culée d’un arc-boutant même si cet effet est relativement faible. De plus, ces
éléments servent toujours d’agent de précontrainte sur la zone potentiellement instable en tête du pilier ou
de la culée.

<!-- p. 144 -->

2.3 Stabilité d’un système structural 121

Figure 2.27 - La poussée de l’arc aux appuis horizontaux et de l’arc contre buté

Un effet stabilisant peut être acquis grâce au lestage3 ou aux charges supportées par les arcs
comme les charges d’une voûte ou des écoinçons4. Le lestage peut apporter un effet stabilisant car il
augmente l’aire entre les contours et laisse, ainsi, plus de possibilité de passage pour les lignes de pression.
Les écoinçons peuvent avoir une hauteur importante et augmentent considérablement les charges verticales
aux arcs aux piliers diminuant l’action de la poussée.

2.3.1.3 L’effet du comportement de bloc de la jonction de plusieurs éléments

L’équilibre du bloc de la jonction ABCD du système est calculé avec la procédure présentée dans

le paragraphe 2.2.4 où ce bloc est considéré comme matériau sans traction. Dans ce cas on cherche

l’équilibre pour que les lignes de pression restent dans les contours du bloc et le bloc travaille seulement en

compression. Si l’on traite le bloc de la jonction comme corps rigide, on doit considérer l’équilibre des forces
et des moments du bloc ABCD, en prenant compte le poids propre du bloc ABCD et des forces de

réaction de l‘arc et de l’arc-boutant, et on détermine la réaction du bloc vers le pilier (Figure 2.18, Figure

2.21). Les calculs permettent de définir le domaine de toutes les combinaisons admissibles des poussées
Harc et Hab pour les états de stabilité potentielle du système. Dans le diagramme suivant (Figure 2.28) il

3 Le lestage est constitué des matériaux posés entre la partie qui contrebute l’arc et l’arc.
4 Les écoinçons sont les parties qui remplissent les espaces au-dessus et entre les arcs (Paulin, 2009).

<!-- p. 145 -->

122 2 Développement de l’outil

s’agit du domaine d’équilibre en ligne continue. En ligne pointillée représente le domaine d’équilibre pour le

traitement du bloc de la jonction comme matériau sans traction.

Figure 2.28 - Domaines d’équilibre du système en considérant le bloc de la jonction a) comme corps rigide et
b) comme matériau sans traction

En comparant l’équilibre pour les poussées maximales de l’arc et à l’arc-boutant, on note que, quand

le bloc de la jonction est considéré comme matériau sans traction, la poussée maximale admissible de l’arc-

boutant est moindre que celle obtenue pour le cas du bloc de jonction considéré comme corps rigide. Au
premier cas l’équilibre pour des poussées maximales est assurée pour de maxHarc = 27% et maxHab = 91%
et au deuxième cas pour maxHarc = 27% et maxHab = 105% du poids propre de chaque élément. Dans le
cas d’un bloc de jonction considéré comme corps rigide, on examine l’équilibre sans préciser le point

d’intersection des quatre forces appliquées à ce bloc. Dans la Figure 2.29, où la stabilité du système est
présentée pour la deuxième combinaison des poussées maxHarc et maxHab et une considération du bloc
ABCD comme corps rigide, on voit que l’intersection de ces poussées se passe hors du bloc. On note que

la considération du bloc de jonction comme matériau sans traction donne un domaine d’équilibre allant vers

le sens de la sécurité, car on élimine la possibilité d’avoir des lignes de pression qui sortent de ce bloc. Ceci

est fait en considérant comme zones effectives des côtés du bloc de la jonction, pour l’application des

<!-- p. 146 -->

2.3 Stabilité d’un système structural 123

poussées, seulement, celles qui conduisent à un point d’intersection des lignes de pression dans le bloc de

la jonction.

Figure 2.29 - L’équilibre du système pour un bloc de jonction considéré comme un corps rigide

2.3.2 Chargement sismique: approche quasi-statique

La procédure présentée au paragraphe 2.2.1.2 peut être utilisée aussi pour un chargement
horizontal. Dans ce paragraphe, on procédera à une simulation des accélérations sismiques horizontales
avec les forces d’inertie appliquées à la structure de manière quasi-statique. On note que la composante
verticale des accélérations sismiques peut être simulée de manière quasi-statique avec la procédure
présentée au paragraphe précédent en modifiant le poids propre de la structure au moyen du facteur
multiplicateur du chargement vertical λ (équation (2.4)).

Pour examiner le comportement du système de la Figure 2.21 sous un chargement horizontal,
premièrement, on applique le chargement à l’arc et aux arcs-boutants et, deuxièmement, aux éléments
verticaux. Comme il s’agit d’un cas de chargement non symétrique, on présentera les calculs pour la
structure entière. Les forces d’inertie seront considérées uniformément réparties dans la structure,
proportionnellement aux poids propre de chaque voussoir et appliquées au centre de gravité des voussoirs.

<!-- p. 147 -->

124 2 Développement de l’outil

Calcul de stabilité de l’arc et des arcs-boutants

Tout d’abord, les forces d’inertie sont appliquées à l’arc et aux arcs-boutants. En se référant à la
Figure 2.30 et en écrivant l’équilibre pour l’arc et les deux arcs-boutants, on obtient :

H s , arc : La résultante au côté B΄A΄ de l’arc,(2.31) H arc ,t = H arc + ∑

H s , ab : La résultante au côté BC de l’arc-boutant droit,(2.32) H ab , t = H ab + ∑

H s*, ab : La résultante au côté I΄J΄ de l’arc-boutant gauche.(2.33) H ab* , t = H ab* + ∑

Figure 2.30 - Chargement horizontal de l’arc et des arcs-boutants

On introduit un changement du système de coordonnées (Figure 2.31) pour notre structure. Le
nouveau système de coordonnées est obtenu par la rotation du système de coordonnées initial à un angle
ϕ (équation (2.17)):

<!-- p. 148 -->

2.3 Stabilité d’un système structural 125

Figure 2.31 - Changement du système des coordonnées de l’arc et des arcs-boutants.

Calcul de stabilité des piliers et des culées

Après avoir calculé les lignes de pression pour l’arc et les arcs-boutants, on retourne au système de
coordonnées initial Oxz et on étudie la stabilité des piliers et des culées. Pour le faire, on prend l’équilibre
des blocs en considérant des coupes parallèles horizontales (Figure 2.32) et on applique la méthode du
paragraphe 2.2.3.

Figure 2.32 - Chargement sismique des piliers et des culées

<!-- p. 149 -->

126 2 Développement de l’outil

Dans la suite, on examinera l’équilibre du système pour deux manières d’application du chargement
horizontal : a. chargement horizontal appliqué dans une seule direction et b. chargement horizontal en tenant
compte de deux sens d’application. Les valeurs de poussées que l’on précisera dans ce qui suit sont
considérées de suivre la direction du chargement horizontal.

a. Equilibre du système pour une seule direction de l’application du

chargement horizontal

Comme on est dans un cas de chargement non-symétrique, le nombre des poussées à déterminer
est trois : Harc, Hab, H ab* les poussées considérées comme inconnues suivent la direction du chargement
horizontal). Premièrement, on examine l’équilibre du système en considérant la direction du chargement
notée dans la Figure 2.30 et la Figure 2.32 et on détermine des valeurs extrêmes pour les trois poussées.

Figure 2.33 - Ligne de pression du système pour un chargement horizontal 0.3g

La Figure 2.33 présente l’équilibre du système pour un chargement horizontal de 0.3g qui constitue
le chargement maximal supportable par le système. La stabilité potentielle du système est définie pour la
combinaison de poussées suivante : Harc = 6%, Hab ≈ 0, H ab* = 112%. On voit que, pour la valeur du
chargement d’accélération et le sens d’application considéré, la poussée de l’arc-boutant gauche nécessaire
pour stabiliser le système est très élevée par rapport à la poussée de l’arc-boutant droit. Ainsi, l’arc-boutant
gauche est sollicité de manière active alors que l’arc-boutant droit est sollicité de manière passive (ce qui est

<!-- p. 150 -->

2.3 Stabilité d’un système structural 127

aussi évident par la forme de la ligne de pression aux arcs-boutants, cf. Figure 2.16). La dissymétrie du
chargement implique une dissymétrie du comportement des éléments malgré la symétrie de la géométrie.

b. Equilibre du système pour les deux directions possibles de l’application

du chargement horizontal

Lors d’un séisme, les directions de sollicitation sont altérnées avec une certaine fréquence et la
structure peut être, donc, soumise à deux orientations opposées de l’accélération. En supposant qu’après
chaque sollicitation, évaluée de manière quasi-statique, le système est à nouveau sollicité dans l’autre sens,
on peut chercher à solliciter la structure d’une manière plus « homogène » et éviter de passer d’un état
passif à un état actif. Dans ce cas, les paramètres à déterminer se réduisent à deux : la poussée Harc de
l’arc et la poussée Hab de l’arc-boutant.

Dans la Figure 2.34, on présente la ligne de pression du système soumis à un chargement sismique
de Ks = 0.075 et ayant adopté l’hypothèse Hab = H ab* . Les poussées appliquées au système sont : Harc =
10% et Hab = 34%. Par la forme des lignes de pression des arcs-boutants on peut noter que la structure a un
comportement « homogène ». Pour considérer un tel comportement, la valeur Ks = 0.075 constitue la plus
grande accélération sismique imposée de manière quasi-statique supportée par le système. Pour cette
accélération il n’y a qu’une combinaison des poussées de l’arc et de l’arc-boutant pour lesquelles la ligne de
pression reste dans les contours de la structure. On voit que même si l’arc et l’arc-boutant (Figure 2.11 et
Figure 2.16) peuvent supporter une accélération de Ks = 0.37 quand ils sont examinés séparément, la
stabilité du système entier impose une limitation considérable au chargement sismique potentiellement
supportable. Pour cela, la valeur de l’accélération de Ks = 0.075 est peut-être très conservative mais, vue
qu’elle résulte d’une simulation du séisme de manière quasi-statique, elle indique que la structure est stable
pour toutes accélérations inférieures, indépendamment de la durée du phénomène sismique. Par
conséquent, elle peut servir comme un premier diagnostic de la nécessité d’analyses temporelles (cf.
paragraphe 2.3.3).

<!-- p. 151 -->

128 2 Développement de l’outil

Figure 2.34 - Ligne de pression du système pour un chargement sismique Ks=0.075

Dans la Figure 2.35, le cas pour Ks = 0.075 est représenté dans le diagramme du domaine
d’équilibre comme un seul point. On présente aussi les domaines de stabilité de la structure pour Ks = 0 et
Ks=0.05 qui mettent en évidence la réduction des combinaisons admissibles des poussées de l’arc et de
l’arc-boutant avec l’augmentation du coefficient sismique.

Figure 2.35 - Domaines d’équilibre de la structure étudiée pour trois valeurs différentes de l’accélération
sismique (Hab = H ab* )

<!-- p. 152 -->

2.3 Stabilité d’un système structural 129

2.3.3 Remarques

\1. Chargement extérieur et définition du domaine K

L’approche statique du Calcul à la Rupture permet de dire si un chargement extérieur est
potentiellement supportable par la structure. Dans le paragraphe 2.3.1, le système structural est examiné
seulement sous poids propre, sans chargement extérieur. Dans ce cas, on a considéré que le chargement
extérieur est le poids propre de la structure, qui est constant et connu, et on a choisi de déterminer le
domaine K (cf. paragraphe 1.3.2.1) à partir des valeurs des forces horizontales Harc et Hab appliquées aux
extrémités de l’arc et de l’arc-boutant respectivement (données en pourcentage du poids propre de l’élément
correspondant). Etant donné que, habituellement, le domaine K représente les valeurs supportables du
chargement, on appelle le domaine défini par Harc et Hab domaine d’équilibre5. Les poussées Harc et Hab
sont considérées comme variables libres (comme le paramètre T de l’exemple du paragraphe 1.3.1). Pour
des valeurs introduites des Harc et Hab on obtient un système structural isostatique. A partir du système
isostatique, on essaie de déterminer les combinaisons de ces forces qui conduisent aux états potentiels
d’équilibre et respectent le critère de résistance du matériau. Dans le paragraphe 2.3.2, la résultante du
poids propre et du chargement horizontal constitue le chargement extérieur. Même si le chargement
horizontal potentiellement supportable par le système est inconnu, on présente les résultats avec le domaine
d’équilibre (à partir des valeurs des forces horizontales Harc et Hab) pour de différentes valeurs du coefficient
sismique Ks (Figure 2.35).

\2. Différentes définitions du domaine d’équilibre

Le domaine d’équilibre d’une structure maçonnée a été initialement introduit par Smars (2000) pour
une géométrie légèrement différente (Figure 2.36). Dans ce cas, le domaine d’équilibre est défini par les
poussées des arcs ainsi que par la poussée des piliers (la même conception du domaine est utilisée par
Block et al. 2006a). La méthode proposée dans cette thèse pour la considération de la stabilité du bloc de
jonction a permis de réduire les forces inconnues définissant le domaine d’équilibre seulement aux éléments
structuraux qui entraînent une force de poussée (arc et arc-boutant) en prenant en compte simultanément
des poussées admissibles dans tous les éléments verticaux.

5 Delbecq (1982) a défini le domaine de stabilité potentielle d’un arc à partir de l’effort normal N, l’effort tranchant Q et
la cote z du point de passage de la ligne de pression à la clef.

<!-- p. 153 -->

130 2 Développement de l’outil

Figure 2.36 - Le système examiné par Smars (2000) et son domaine d’équilibre

\3. Chargement sismique imposé de manière quasi-statique et Théorème
statique du Calcul à la Rupture

L’estimation de la valeur minimale d’accélération pour la création d’un mécanisme de rupture
obtenue en utilisant l’approche statique du Calcul à la Rupture est généralement très conservative. Une
autre estimation peut être obtenue en utilisant l’approche cinématique du Calcul à la Rupture (simulation du
séisme de manière quasi-statique). Cette approche pourrait servir pour une comparaison de la valeur
d’accélération obtenue avec l’approche statique mais, généralement, elle n’est applicable qu’aux systèmes
structuraux simples (comme un arc supporté sur deux piliers, Ochsendorf 2002, De Luca et al. 2009,
Brandonisio et al. 2009). Les mécanismes de rupture potentiels se multiplient avec la complexité du système
structural. Dans ce sens, les positions des rotules obtenues avec l’approche statique peuvent servir à la
détermination des mécanismes étudiés avec l’approche cinématique.

Le séisme étant un phénomène dynamique, il peut produire des contraintes locales importantes qui
peuvent entraîner une rupture par écrasement de la maçonnerie. Il entraîne, aussi, des vibrations qui
augmentent la possibilité de glissement entre les blocs. Cependant, l’analyse des effets du séisme de
manière quasi-statique nous permet d’appliquer les hypothèses d’Heyman pour le matériau sans traction afin
de déterminer l’accélération constante minimale nécessaire pour la création d’un mécanisme de rupture. Il
faut noter que cette analyse statique équivalente n’est basée que sur la géométrie de la structure. Elle est
indépendante de l’échelle considérée pour la structure, qui est un effet important pour le comportement

<!-- p. 154 -->

2.3 Stabilité d’un système structural 131

dynamique et pour la résistance d’une structure maçonnée. Par exemple, un arc plus grand est plus résistant
pour une sollicitation dynamique qu’un plus petit de mêmes proportions géométriques, comme il l’est
expliqué par les modèles analytiques de De Lorenzis et al. (2007). Néanmoins, une simulation sismique au
premier ordre tel que la simulation de manière quasi-statique est bien appropriée pour l’étude des systèmes
structuraux complexes. Des simulations numériques basées sur la méthode des éléments discrets ou des
simulations analytiques peuvent difficilement être appliquées sur ce type de systèmes6.

La Figure 2.37 (Ochsendorf, 2002) met en évidence l’effet de la variable du temps par rapport à la
stabilité sismique d’une structure. Ce diagramme fournit la valeur de l’accélération maximale admissible pour
la stabilité globale de la structure en fonction de la durée du phénomène sismique en supposant que cette
accélération est constante lors du séisme.

Figure 2.37 - Formation de mécanisme de rupture en fonction de la valeur d’accélération et de la durée du
phénomène sismique (Ochsendorf, 2002)

6 A notre connaissance, les seules applications de ces méthodes concernent des éléments ou des systèmes simples.

<!-- p. 155 -->

132 2 Développement de l’outil

On peut constater qu’un état potentiellement stable du système est défini pour toute durée de
séisme si l’accélération est inférieure à la valeur seuil Ksmin. C’est exactement la valeur que l’on calcule avec
la méthode présentée (Ks = 0.075 dans le cas du système structural). Au dessous de cette valeur la
structure reste stable car il n’y a pas de mécanisme de rupture activé dans la structure. On remarque,
encore, que le système peut supporter des accélérations plus élevées que Ksmin si elles sont appliquées
pour des périodes courtes. Ceci signifie que l’on permet au mécanisme de rupture de se développer dans la
structure à condition que les déplacements permanents induits par ce mécanisme restent inferieurs à une
valeur seuil qui entrainerait la ruine de la structure. Pour mettre ce phénomène en évidence, on doit avoir
recours à des analyses temporelles non-linéaires permettant d’évaluer les déplacements irréversibles au fur
et à mesure qu’un mécanisme de rupture se développe dans la structure lors de la sollicitation. L’utilité de la
valeur seuil Ksmin pour une structure réelle est qu’elle permet de s’affranchir de tout besoin d’analyses
temporelles si elle est supérieure au risque sismique dans la région où se situe la structure examinée.

<!-- p. 156 -->

2.4 Comparaison des résultats 133

2.4 Comparaison avec des résultats obtenus par des
analyses du système aux éléments finis et aux
éléments discrets

Dans ce paragraphe on présentera une validation des résultats obtenus pour le système
académique défini au paragraphe 2.3 (Figure 2.21) en les comparant avec des résultats issus de l’analyse
d’un système similaire, traité avec la méthode des éléments finis. Ensuite, on présentera les résultats de
l’analyse d’un système similaire traité avec la méthode des éléments discrets et l’on cherchera la corrélation
avec la méthode issue du matériau sans traction.

2.4.1 Comparaison avec des résultats obtenus par des analyses du

système aux éléments finis

Afin de réaliser une comparaison avec la méthode des éléments finis, la géométrie présentée à la
Figure 2.21 a été introduite dans le logiciel SAP2008. Pour la modélisation du système on a utilisé des
éléments finis plans de type éléments coque avec une épaisseur unitaire et une loi de comportement pour le
matériau « maçonnerie » linéaire élastique isotrope. On adopte les paramètres suivants : module d’élasticité
égal à 2.0GPa, coefficient de Poison 0.2, poids volumique 20KN/m3. Les déplacements verticaux horizontaux
sont bloqués pour les nœuds des appuis. Dans la Figure 2.38 et la Figure 2.39 les diagrammes des
contraintes principales σ11 et σ22, sont présentés respectivement sur la géométrie déformée du système pour
un chargement sous poids propre de la structure. Les régions où la structure se trouve en traction sont
représentées en couleur blanche. Ces régions représentent les positions possibles de formation de fissures.
Si l’on fait une comparaison avec les régions susceptibles d’endommagement calculées par l’outil, on peut
remarquer une relation avec les résultats obtenus pour le cas de la poussée minimale dans l’arc (Figure
2.23a). Cette relation est expliquée aussi par l’augmentation de l’écartement de l’arc acquise par la méthode
des éléments finis qui correspond à l’état passif de l’arc.

<!-- p. 157 -->

134 2 Développement de l’outil

Figure 2.38 - Contraintes principales σ11 du système (chargement sous poids propre) - structure déformée

Figure 2.39 -.Contraintes principales σ22 du système (chargement sous poids propre) - structure déformée

Les poussées de l’arc et de d’arc-boutant acquises par l’analyse aux éléments finis correspondent à
17% du poids propre de l’arc et à 49% du poids propre de l’arc-boutant respectivement. Ces résultats sont
représentés dans la Figure 2.40.

<!-- p. 158 -->

2.4 Comparaison des résultats 135

Figure 2.40 - Comparaison des résultats pour chargement sous poids propre avec une analyse aux éléments finis

Dans un deuxième temps, on applique les deux méthodes de calcul à un système de la même
géométrie mais pour un arc et des piliers d’une épaisseur réduite de moitié pour un chargement sous poids
propre (tarc/rarc = 0.12). Pour cette géométrie, la poussée unique supportable par l’arc est Harc = 19% de son
poids propre et même si l’on applique la poussée minimale de l’arc-boutant minHab = 41% on voit que la
ligne de pression croise le contour gauche du pilier et la stabilité du système n’est pas assurée (Figure 2.41).
Les poussées calculées par les calculs aux éléments finis sont égales à 18% pour l’arc et 29% pour l’arcboutant (Figure 2.42). La méthode des éléments finis donne des poussées compatibles avec un
comportement élastique et permet de définir des zones potentielles de fissures mais elle ne renseigne pas
sur la stabilité de la structure.

<!-- p. 159 -->

136 2 Développement de l’outil

Figure 2.41 - Lignes de pression du système pour chargement sous poids propre (tarc/rarc = 0.12)

Figure 2.42 - Contraintes principales σ11 du système (tarc/rarc = 0.12, chargement sous poids propre) -
structure déformée

Nous avons, aussi, procédé à une simulation du chargement sismique (de manière quasi-statique)
avec la méthode des éléments finis. Le chargement a été appliqué dans la direction horizontale aux
éléments coques proportionnellement à leur poids propre. Le diagramme de la Figure 2.43 représente le
domaine d’équilibre du système sous poids propre et avec un chargement sismique Ks = 0.05. L’approche
fournit une poussée de l’arc Harc = 14%, une poussée de l’arc-boutant droit Hab = 35% et une poussée de
l’arc-boutant gauche H ab* = 53% du poids propre de chaque élément. Cette combinaison de poussées ne
constitue qu’un cas stable pour le système pour une seule orientation des forces d’inertie du séisme.
Cependant, afin de prévoir un comportement « homogène » du système sous un chargement horizontal,
indépendamment de l’orientation de son application, on doit appliquer la même poussée aux deux arcs-

<!-- p. 160 -->

2.4 Comparaison des résultats 137

boutants (cf. paragraphe 2.3.2), ce qui ne peut pas être facilement reproduit avec un calcul aux éléments
finis.

Figure 2.43 - Comparaison des résultats de l’analyse aux éléments finis et de l’outil pour le système (chargement
sous poids propre et sismique de Ks = 0.05)

On note que la méthode de la ligne de pression a été mise en œuvre sans l’introduction d’une
hypothèse concernant la loi de comportement (contraintes-déformations) de la maçonnerie. Le seul élément
nécessaire pour cette méthode est le critère de résistance de la maçonnerie et des interfaces entre la
structure et ses supports. Par contre, la mise en œuvre de la méthode des éléments finis exige l’introduction
d’une loi de comportement pour la maçonnerie et ici on a adopté une loi élastique. Une loi plus avancée est
apparemment plus pertinente mais elle augmenterait considérablement la complexité du problème (Boothby
et al. 2007a). On note, finalement, que dans la méthode des éléments finis, la sélection de type des appuis
se fait en imposant une condition sur les déplacements de ceux-ci et non en imposant une condition sur les
efforts supportables le long des appuis, comme c’était le cas pour la méthode de la ligne de pression.

<!-- p. 161 -->

138 2 Développement de l’outil

2.4.2 Ligne de pression d’un système structural et traitement aux

éléments discrets

Dans les travaux de recherche présentés par Acary (2001), le matériau maçonnerie est traité en
introduisant les hypothèses appropriées le long des interfaces réelles des différents blocs de la maçonnerie.
Il y a en particulier dans ces travaux le traitement d’un système qui peut servir à la validation des résultats
fournis par l’outil développé qui, nous le rappelons, est fondé sur les hypothèses sur le comportement de la
maçonnerie introduites par Heyman (1995).

Figure 2.44 - Le système examiné par Acary (2001)

On peut noter que la rotule obtenue à la clef dans notre analyse du système (Figure 2.23a), obtenue
pour la poussée minimale de l’arc, est associée à un mécanisme tendant à écarter les appuis de l’arc.
L’étude d’Acary du portique de la Figure 2.44, soumis à la gravité, résulte aussi en une augmentation de
l’écartement de l’arc. Les régions en gris foncé du modèle d’Acary représentent les régions les plus
sollicitées en compression et correspondent à la forme de la ligne de pression obtenue pour la poussée
minimale de l’arc de notre analyse. Pour la réalisation de calculs avec la méthode d’Acary, les points de
contact entre les éléments constitutifs de la maçonnerie doivent être prévus. Les cas possibles d’équilibre de
la structure obtenus par notre outil peuvent indiquer les points candidats de contact.

<!-- p. 162 -->

2.5 Coefficients de sécurité 139

2.5 Coefficients de sécurité

La tenue d’une structure dans le temps est le meilleur témoin pour la vérification de sa stabilité.
Cependant, pour prévoir de possibles perturbations de cette stabilité ou pour proposer des remèdes pour
des dégâts existants, il est envisageable d’introduire des coefficients de sécurité de la stabilité des
structures. Dans notre considération, le coefficient de sécurité pour la maçonnerie est une règle géométrique
par opposition au coefficient de résistance appliqué habituellement aux structures. Nous allons introduire
deux coefficients de sécurité géométriques : le coefficient relatif à traction et le coefficient relatif au
glissement.

2.5.1 Coefficient relatif à traction dans la structure

Dans ce paragraphe on présentera des considérations sur l’adoption d’un coefficient géométrique
relatif à la traction afin de réduire le risque de fissuration d’un système structural réalisé en matériau sans
traction.

Ce coefficient relatif à la traction est défini par le rapport de l’épaisseur de la structure divisé par
l’épaisseur réduite (Heyman, 1966).

t
(2.34) Fs =
d

Figure 2.45 - Paramètres de définition du coefficient relatif à la traction

<!-- p. 163 -->

140 2 Développement de l’outil

Dans notre approche, l’introduction de ce coefficient géométrique est transformée en une réduction
du domaine d’équilibre de la structure. Dans ce cas, les poussées extrêmes, qui sont admissibles pour la
stabilité de la structure, doivent être calculées en prenant en compte le poids propre de la section entière de
chaque bloc pour créer la ligne de pression mais elles doivent produire une ligne contenue à une géométrie
réduite. En d’autres termes, les contraintes d’équilibre restent les mêmes mais les contraintes des
ordonnées admissibles zi sont modifiées. O’Dywer (1997) a introduit dans l’équation (2.10) la notion d’un
paramètre β, équivalent au coefficient de sécurité.

(2.35) z int,i + ( z ext,i − z int,i )β\< z i \< z ext,i − ( z ext,i − z int,i )β

Dans ce cas le coefficient de sécurité est:

1
(2.36) Fs =
1 − 2β
Si l’on adopte le coefficient de sécurité relatif à traction égal à deux pour un arc, proposé par
Heyman, la nouvelle géométrie suit le même axe central avec la structure entière mais elle n’a que la moitié
de l’épaisseur. La loi du tiers central (Méry, 1840), qui a été originalement un concept élastique pour éviter la
traction dans une section, constitue un coefficient pratique. Elle propose que la ligne de pression doive rester
dans la section définie par la distance d’un tiers de chaque contour. Huerta et al. (1997) ont essayé de fixer
la valeur du coefficient de sécurité en considérant les déformations des appuis (murs et contreforts) qui ont
soutenu la voûte en berceau de l’église de Guimarei. Il s’agit d’un cas où la géométrie initiale des appuis a
conduit à une augmentation de l’écartement de la voûte, à sa fissuration et aux déformations des murs. Dans
une intervention plus récente, l’épaisseur des contreforts a été augmentée et les déformations ont été
arrêtées. Il a été rendu clair que la section des appuis initiaux (épaisseur de la section du contrefort initial et
du mur) correspond à un coefficient de sécurité de Fs = 1.2 qui n’était pas suffisant pour garantir la stabilité
du système structural. La géométrie actuelle des appuis (épaisseur de la section du contrefort et du mur
augmentée), qui garantit la stabilité du système, révèle un coefficient de sécurité de Fs = 1.58. Cependant,
autres auteurs proposent des coefficients de sécurité beaucoup plus importants. On a déjà vu que Mery,
ainsi que Rankine (1858), ont proposé un coefficient de sécurité Fs = 3. La valeur Fs = 1.5 est acceptable
selon Rankine seulement pour des murs de soutènement sans structures en surface.

<!-- p. 164 -->

2.5 Coefficients de sécurité 141

Etant donné que l’on ne peut pas savoir exactement la distribution des contraintes sur une section
dans la maçonnerie, on adoptera une distribution linéaire des contraintes7 et la loi du tiers central. En
essayant d’appliquer le coefficient de sécurité dans la structure présentée sur la Figure 2.21, la question de
l’élément d’application se soulève. Comme les arcs et les arcs-boutants sont des éléments minces, la
considération du rapport de sécurité à leur section sera trop restrictive. On l’appliquera, donc, aux sections
des appuis (comme effectué dans les travaux de Heurta et al. 1997 et Block et al. 2006a). Dans la Figure
2.46 on présente en ligne continue le domaine d’équilibre du système structural en appliquant la loi du tiers
central.

Figure 2.46 - Réduction du domaine d’équilibre pour chargement sous poids propre en appliquant la loi du tiers
central

7 Plusieurs auteurs ont adopté la distribution linéaire des contraintes dans la maçonnerie (Dupuit, 1870,

Castigliano, 1879, Heyman, 1992, La Mendola et al. 1993, Ochsendorf et al. 2004).

<!-- p. 165 -->

142 2 Développement de l’outil

En redéfinissant de cette manière les états potentiels d’équilibre, on évite le cas de présence de
fissuration au pied des éléments d’appui et le control relatif au renversement n’est pas nécessaire
(Ochsendorf et al. 2004, cf. paragraphe 1.4.4).

2.5.2 Coefficient relatif au glissement dans la structure

Il faut bien noter que, en plus du coefficient géométrique relatif à la traction, on doit aussi adopter un
coefficient de sécurité relatif au glissement entre les blocs de la maçonnerie. Les bâtisseurs anciens ont
prévu des mesures contre le glissement. La construction radiale des pierres aux arcs et aux arcs-boutants, le
renforcement de la tête des arcs-boutants avec une colonne extérieure formant aussi un passage et la
formation du croisement des arcs en tas de charge constituent des exemples des mesures prises pour éviter
le cas du glissement entre les voussoirs. Pour les calculs de stabilité potentielle présentés, l’interdiction de
glissement entre les blocs de la maçonnerie doit être satisfaite en cohérence avec la considération du
matériau sans traction. Suivant la troisième hypothèse adoptée pour ce matériau le cas du glissement entre
les blocs n’est pas possible grâce au développement suffisant du frottement. Ainsi, on adopte le critère de
frottement de Coulomb et l’interdiction de glissement entre les blocs peut être définie en calculant l’angle δ
entre la ligne de pression (ligne verte) et la normale au joint AiBi entre le bloc i et le bloc i+1, pour
i=1,2,…n (Figure 2.47). La ligne de pression calculée avec la méthode du réseau de forces est pertinente
pour décrire la direction de la force de réaction qui s’exerce au joint entre deux blocs. Dans la Figure 2.3, on
peut remarquer que les points définissant cette ligne sont les points d’intersection des lignes d’action des
forces de réaction développées aux côtés de chaque bloc (et du poids propre). Le segment qui relie deux
points définit donc la direction de la force de réaction au joint entre deux blocs.

<!-- p. 166 -->

2.5 Coefficients de sécurité 143

Figure 2.47 – Paramètres de définition du coefficient relatif au glissement

Il s’agit là de garantir que l’angle δ soit inférieur à la valeur correspondant au coefficient de
frottement statique entre les joints. On adoptera la valeur du coefficient de frottement pour la maçonnerie en
mortier proposée par Coulomb (1773) égale à 0.758 :

T
(2.37) Ft = tan δ = ≤ 0.75
N
où T est la force de frottement et N la force verticale appliquée sur le joint.

Ce coefficient correspond à un angle δ = 36.87o. Si l’on appelle θ la pente du joint et ψ l’angle entre la
direction de ligne de pression à Ci et de l’axe Ox :

δ+ θ+ψ = 90ο ⎫ ο(2.38) ⎪⇒⎬ θ+ψ ≥ 53.13 ο
δ ≤ 36.87 ⎪⎭

Dans le cas d’un arc ou d’un arc-boutant, où le maillage de n blocs est radial, les angles θ et ψ sont donnés
par les expressions suivantes, pour chaque joint AiBi:

180
(2.39) θ = 180 − i
n
zi +1 − zi −1(2.40) ψ = a tan
xi +1 − xi −1

8 On adopte la valeur conservative 0,75 proposée par Coulomb (1773) pour généraliser le problème aussi que pour
avoir la flexibilité de comparer nos résultats avec des autres auteurs.

<!-- p. 167 -->

144 2 Développement de l’outil

où zi, xi sont les coordonnées de la ligne de pression pour chaque bloc i.

Le coefficient géométrique relatif au glissement proposé dans cette thèse est une considération
équivalente à la prise en compte d’une résistance maximale des joints sans cohésion à l’effort tranchant
proposée par Smars (2000). Dans notre approche, les propriétés de la ligne de pression acquise avec la
méthode du réseau de forces permettent une vérification géométrique du critère de frottement de Coulomb
sans passer par une estimation des efforts N et T développés aux joints de la structure.

Etude des cas

Dans les deux figures suivantes, on présente la variation de l’angle δ pour les combinaisons
admissibles des poussées Harc et Hab pour chargement sous poids propre. La Figure 2.48 présente le cas
pour minHarc et minHab \< Hab \< maxHab (présenté sur Figure 2.23(a)). On note que les angles les plus
grands sont obtenus pour l’arc central aux régions des appuis (δ =17.65o), pour minHab aux régions de
l’appui entre l’arc-boutant et le pilier (δ =38.24o) et pour maxHab à l’appui contre la culée (δ =31.51o).

Figure 2.48 - Variation de l’angle δ de l’arc et de l’arc-boutant pour minHarc, minHab \< Hab \< maxHab

Dans la Figure 2.49 on présente la variation de l’angle δ pour maxHarc, minHab \< Hab \< maxHab
(présenté sur la Figure 2.23(b)). Les angles les plus grands sont aperçus pour l’arc aux appuis (δ =26.57o),
pour l’arc-boutant à l’appui contre la culée pour (δ =minHab, 36.84o et δ =maxHab, 43.02o).

<!-- p. 168 -->

2.5 Coefficients de sécurité 145

Figure 2.49 - Variation de l’angle δ de l’arc et de l’arc-boutant pour maxHarc, minHab \< Hab \< maxHab

Dans la Figure 2.50, on présente la variation de l’angle δ pour les combinaisons des poussées Harc
et Hab dans le cas du chargement sous poids propre et du chargement sismique de Ks = 0.075 (Figure
2.34). Les appuis de l’arc et l’appui de l’arc-boutant gauche contre la culée présentent les angles les plus
grands (δ =23.21o et δ =23.51o, respectivement).

Figure 2.50 - Variation de l’angle δ de l’arc et des arcs-boutants pour chargement sous poids propre et sismique
Ks = 0.075

On note que le dépassement de l’angle limite relatif au glissement (maxδ = 36.87o) est faible pour
les poussées considérées et on ne procédera pas á une redéfinition des poussées admissibles. Comme on a

<!-- p. 169 -->

146 2 Développement de l’outil

noté dans le paragraphe 2.3.1.1c, quand l’arc-boutant est considéré dans un système structural, la valeur
minimale de sa poussée admissible pour la stabilité du système entier est plus importante que celle obtenue
par une considération de l’arc-boutant seul. Cette augmentation de la valeur minimale de la poussée de l’arcboutant a un effet positif par rapport au risque de glissement (en considérant un maillage radial). La Figure
2.51 présente la variation de l’angle δ pour l’arc-boutant dans le cas où il est considéré dans le système
structural (δab,1 - ligne en pointillé) et dans le cas où il est examiné seul (δab,2 - ligne continue) pour la
poussée minimale minHab obtenue à chaque considération. La ligne de pression obtenue pour la poussée
minimale quand l’arc-boutant est considéré seul constitue un cas susceptible de provoquer le glissement
entre les voussoirs prés de la tète du pilier (maxδab,2 = 66.35o = 1.8maxδ). La considération du
comportement de l’arc-boutant dans un système structural réduit ce risque (maxδab,1 = 38.24o = 1.04maxδ).
Nikolinakou et al. (2005, 2006) ont étudié le risque du glissement entre voussoirs des arcs-boutants adoptés
dans l’architecture gothique primitive. En effet, les auteurs ont suggéré qu’il serait plus pertinent de
considérer l’équilibre des systèmes structuraux complets afin d’étudier le rapport entre la poussée minimale
et la géométrie des arcs-boutants adoptée. Nous avons montré la pertinence de cette suggestion dans le
diagramme de la Figure 2.51.

Figure 2.51 - Variation de l’angle δ pour minHab pour les cas où l’arc-boutant est

a) considéré d’un système structural et b) examiné seul

<!-- p. 170 -->

2.5 Coefficients de sécurité 147

L’application du coefficient relatif au glissement nous permet de discuter l’influence du découpage
sur la stabilité d’un arc un plein cintre. Sur la Figure 2.52, on présente en ligne en pointillé et continue la
variation de l’angle δ pour un arc des joints radiaux et des joints verticaux respectivement. On a appliqué à
l’arc (tarc/rarc = 0.25) la poussée minimale minHarc = 14.12%. On note l’augmentation du risque de
glissement entre les blocs dans le cas où l’arc se compose des joints verticaux (maxδvertical = 70.01o,
maxδradial = 17.65o).

Figure 2.52 - Variation de l’angle δ d’un arc en plein cintre des joints verticaux et des joints horizontaux

<!-- p. 171 -->

148 2 Développement de l’outil

2.6 Considérations sur l’épaisseur minimale, les
rotules et les poussées extrêmes d’un arc en plein
cintre

2.6.1 Considérations sur la détermination de l’épaisseur minimale

d’un arc

Un problème fondamental de la mécanique de l’arc en maçonnerie concerne la détermination de
l’épaisseur minimale nécessaire pour assurer sa stabilité lorsqu’il est soumis à son poids propre : il s’agit du
fameux problème de Couplet (1729, 1730). Dans la suite, on considérera des arcs en plein cintre pour
effectuer la comparaison avec différentes approches.

Un élément essentiel pour la compréhension du problème porte sur le rôle du découpage de l’arc
par rapport à sa résistance globale et à son épaisseur minimale. Comme il a été noté par Heyman (2009), un
arc monolithique possède une résistance plus élevée (ou au moins égale mais jamais inférieure) qu’un arc
découpé en voussoirs. En plus, pour l’arc découpé en voussoirs, la résistance est dépendante de la direction
des joints, c’est-a-dire de la stéréotomie des voussoirs. En effet, si l’on considère un arc monolithique, il est
certain que l’introduction d’un découpage en voussoirs ne peut pas à coup sûr augmenter la résistance de la
structure. Par conséquent, on peut considérer que l’épaisseur minimale (ou épaisseur critique) de l’arc
dépendra du découpage de l’arc et que parmi les arcs découpés et non découpés, l’arc monolithique mettra
en évidence l’épaisseur critique minimale.

La théorie du Calcul à la Rupture (avec ses trois approches différentes) peut être utilisée afin de
fournir une estimation par excès ou par défaut de la valeur de l’épaisseur critique d’un arc. Plusieurs
solutions sont disponibles en utilisant les trois approches possibles du Calcul à la Rupture. On rappelle que
la valeur exacte de l’épaisseur critique est déterminée si et seulement si une solution statique (approche
statique par l’intérieur) et une solution cinématique (approche cinématique par l’extérieur) sont construites et
conduisent au même résultat. L’approche statique par l’intérieur, du fait qu’elle est une approche
conservative, fournira des approximations par excès, c’est-à-dire des épaisseurs supérieures ou égales à
l’épaisseur critique exacte. Les deux autres approches (statique par l’extérieur et cinématique par l’extérieur)
fourniront des épaisseurs inférieures ou égales à l’épaisseur critique exacte. On présente dans la suite
diverses solutions du problème et on les compare avec la solution obtenue avec l’outil de calcul développé.

<!-- p. 172 -->

2.6 Epaisseur minimale, rotules et poussées extrêmes d’un arc en plein cintre 149

Ochsendorf (2002) en utilisant l’approche cinématique du Calcul à la Rupture a estimé l’épaisseur
minimale d’un arc en plein cintre soumis à son poids propre égale à mint/r = 0.1075. Pour cela, il a
considéré un mécanisme de rupture d’un arc divisé en quatre parties qui sont définies par des joints radiaux
(paragraphe 1.4.5). Il a considéré l’égalité de la puissance des efforts intérieurs (qui sont nuls pour le
matériau sans traction) avec la puissance des efforts extérieurs (qui se constituent du poids propre de l’arc).
Comme le mécanisme de rupture considéré constitue l’unique mécanisme de rupture, la valeur du rapport t/r
est une solution exacte (Heyman, 2009).

La même valeur du rapport minimale mint/r est obtenue en utilisant la méthode de Moseley
(paragraphe 1.4.3.1) qui se base sur l’application des équations d’équilibre sur des joints radiaux d’un arc
non fissuré. On peut conclure que, comme la solution de l’approche statique par l’intérieur (Moseley) et de
l’approche cinématique (Ochsendorf) donnent le même résultat, la valeur exacte de l’épaisseur critique pour
un arc de découpage radial est égale a mint/r = 0.1075.

En utilisant la méthode d’O’Dwyer la valeur mint/r = 0.109 est obtenue. Il est intéressant de noter
que les lignes de pressions résultantes de la méthode d’O’Dwyer et de Moseley, pour l’application de la
même poussée aux extrémités de l’arc, ne sont pas identiques même si elles s’appuient sur l’approche
statique du Calcul à la Rupture (paragraphe 1.4.3.1). L’utilisation du réseau de forces proposée par O’Dwyer
résulte à la création d’une ligne de pression définie aux abscisses sur la ligne d’action des poids de blocs et
pas aux points appartenant aux joints. En prenant aussi en compte le fait que, dans la méthode d’O’Dwyer,
le contrôle de l’admissibilité de la ligne par rapport aux contours est réalisé aux nœuds du réseau et pas aux
joints, on peut expliquer cette différence sur l’épaisseur critique minimale d’un arc en plein cintre.

Dans les travaux sur l’épaisseur minimale d’un arc en plein cintre, Heyman (1969, 2009) a considéré
l’équilibre limite d’un arc fissuré qui se compose de quatre blocs monolithiques et il a proposé la solution
mint/r = 0.106. L’approche d’Heyman suit l’approche statique par l’extérieur, car elle se base sur l’application
des équations d’équilibre à une structure en état de ruine (paragraphe 1.4.4). Elle conduit, donc, à une
épaisseur plus fine que celle donnée par l’approche statique par l’intérieur car elle vise à estimer l’épaisseur
minimale par défaut. Cette solution correspond à un arc monolithique qui, logiquement, puisse être stable
pour une moindre épaisseur à cause de sa meilleure résistance (Heyman, 2009).

On récapitule dans le Tableau 2.2 les valeurs de l’épaisseur minimale d’un arc en plein cintre
calculées avec les approches précédentes. Les valeurs de mint/r selon les méthodes d’O’Dwyer et de
Moseley ont été calculées dans cette thèse. On note que, initialement, O’Dwyer a utilisé un découpage
vertical mais les calculs présentés ici ont été réalisés avec un découpage radial de l’arc.

<!-- p. 173 -->

150 2 Développement de l’outil

Méthode année mint/r découpage approche

Couplet radial (β = statique par
1729 0.101
45ο) l’extérieur

Moseley statique par
1830 0.1075 radial
l’intérieur

statique par
Heyman 1969 0.106 vertical l’extérieur

radial
statique par
O’Dwyer 1999 0.109 (dans cette l’intérieur
thèse)

Ochsendorf 2002 0.1075 radial cinématique

Tableau 2.2 - Définition du rapport mint/r selon différentes approches

<!-- p. 174 -->

2.6 Epaisseur minimale, rotules et poussées extrêmes d’un arc en plein cintre 151

2.6.2 Etudes paramétriques d’un arc en plein cintre : position des

rotules et poussées extrêmes en fonction du rapport t/r

2.6.2.1 Position des rotules d’un arc un plein cintre en fonction du rapport t/r

Dans la suite, on procèdera à quelques considérations sur les positions des rotules d’un arc en plein
cintre étudié avec la méthode du réseau de forces. Dans la Figure 2.53, les résultats de la position β des
rotules par rapport à l’axe Oz sont présentés pour des valeurs du rapport t/r qui varient de 0.109 à 0.30. Les
lignes en pointillé et continue correspondent aux positions des rotules formées à l’état passif (minHarc) et à
l’état actif (maxHarc) de l’arc respectivement.

Figure 2.53 - Diagramme de l’angle β et du ratio t/r pour minHarc et pour maxHarc

On note que, dans l’état passif, l’augmentation du rapport t/r correspond à une augmentation de
l’angle β ; les rotules se situent plus près des supports de l’arc. Dans le cas actif, on note, que pour des
rapports t/r inférieures à 0.25, on a la formation de quatre rotules (deux rotules aux appuis à l’extrados et
deux rotules à l’intrados symétriques par rapport à l’axe Oz faisant un angle β). Pour des valeurs du rapport
t/r supérieures à 0.25, on a la formation des rotules aux appuis et d’une seule rotule à l’intrados à la clé.

<!-- p. 175 -->

152 2 Développement de l’outil

La ligne en pointillé, correspondant à l’état passif d’un arc en plein cintre, a été calculée aussi par
Ochsendorf (2002) en utilisant l’approche cinématique du Calcul à la Rupture. Les lignes de deux approches
ont la même forme.

2.6.2.2 Poussées extrêmes d’un arc en plein cintre en fonction du rapport t/r

On présente ici des études paramétriques du rapport t/r d’un arc en plein cintre en fonction de ses
poussées extrêmes pour différentes valeurs du coefficient sismique (approche quasi-statique). La Figure
2.54 présente les études paramétriques pour des cas suivants du chargement : chargement sous poids
propre avec un chargement sismique d’accélération Ks = 0, 0.1, 0.2 et 0.3. Ce diagramme prolonge, au cas
d’un chargement sismique imposé de manière quasi-statique, les études paramétriques effectuées par
Ciblac et al. (2008) pour un chargement sous poids propre d’un arc en plein cintre en utilisant la statique
graphique (cf. Figure 3.15, Chapitre 3).

Figure 2.54 - Diagramme du rapport t/r d’un arc en plein cintre en fonction des minHarc et maxHarc

2.6.3 Remarques

\1. Epaisseur minimale d’un arc et Calcul à la Rupture

La détermination de l’épaisseur minimale d’un arc est un problème complexe. Les trois approches
du Calcul à la Rupture (Tableau 2.2) conduisent à des solutions différentes selon le type d’approche et selon
le maillage considéré pour un arc en plein cintre (qui est indicatif de la stéréotomie des voussoirs). On doit

<!-- p. 176 -->

2.6 Epaisseur minimale, rotules et poussées extrêmes d’un arc en plein cintre 153

aussi prendre en compte que l’épaisseur minimale d’un arc dépend de son angle interne, défini entre l’axe
vertical et les appuis, comme évoqué par Oshcendorf (2002). Le rapport ogival est aussi un paramètre
essentiel pour la définition de l’épaisseur minimale comme montré par Ciblac (2008). Finalement, on
montrera au Chapitre 3 que la considération de l’équilibre d’un système structural complet apporte des
différences sur la détermination de l’épaisseur minimale d’un arc (cf. paragraphe 3.2.1).

\2. Calcul à la Rupture et détermination des régions susceptibles
d’endommagement

L’adoption des hypothèses du matériau sans traction et son application aux calculs à l’échelle
macroscopique d’une structure provient du comportement de la structure à son échelle microscopique du
matériau. Acary (2001) a défini la « maçonnerie » comme un composite des matériaux quasi-fragiles (échelle
microscopique). Heyman (1995) a évoqué que, à cause du caractère fragile du matériau, la structure
maçonnée peut s’accommoder de différentes altérations au niveau de ses voussoirs et qu’elle dispose d’un
comportement ductile dans son ensemble (échelle macroscopique).

De l’autre côté, la détermination des phénomènes d’endommagement, tels que le glissement et la
formation des rotules, avec le Calcul à la Rupture, ainsi qu’avec toutes les méthodes qui traitent la structure
à l’échelle macroscopique, a, a priori, un caractère approximatif. Comme on a traité le problème à l’échelle
définie par la structure, où la « maçonnerie » est considérée homogène et continue, on n’a pas utilisé
d’informations concernant la position des joints. Ainsi, on peut partialement répondre à une question qui
concerne la disposition des joints et des éléments dans la microstructure.

Par ailleurs, la détermination des régions susceptibles de formation des rotules avec la méthode
proposée pour des systèmes structuraux complexes (cf. paragraphe 2.3.1.1d) peut servir à la définition des
mécanismes de rupture étudiés suivant l’approche cinématique du Calcul à la Rupture.

<!-- p. 177 -->

154 2 Développement de l’outil

2.7 Conclusion du Chapitre 2

Dans les paragraphes précédents, le développement d’un outil d’évaluation de la stabilité des
structures maçonnées a été présenté. L’idée de base est de représenter les contraintes de la structure
comme un réseau de forces qui s’approche de la ligne de pression de la structure pour un chargement
donné. Le critère de stabilité exige que la ligne de pression demeure dans l’aire définie par la géométrie de
la structure. Nous insistons sur les conclusions suivantes :

• Il s’agit d’une méthode particulièrement simple d’utilisation permettant de prendre en compte les
caractéristiques mécaniques simples, mais pertinentes, de la maçonnerie (résistance infinie à la
compression et pratiquement nulle en traction). L’absence de fissuration dans la structure peut être
garantie par l’adoption d’un coefficient de sécurité géométrique relatif à la traction imposant que la
ligne de pression se trouve à l’intérieur d’une zone réduite.

• La troisième hypothèse du critère de résistance du matériau, suivant laquelle le cas du glissement
entre les blocs constitutifs de la maçonnerie n’est pas possible, est fondée sur la supposition que le
frottement entre les blocs soit suffisamment élevé. Dans notre approche, une vérification
géométrique de cette hypothèse est proposée correspondant à l’adoption du critère de frottement de
Coulomb pour un nombre fixe des joints de chaque élément du système structural. Cette vérification
se base sur la définition de deux angles relativement à l’axe horizontal du système: l’angle de la
surface des joints et l’angle de la ligne de pression à chaque joint.

• Même si les éléments structuraux peuvent être étudiés séparément, le traitement de la structure
entière permet d’examiner comment la présence d’un élément structural influence le comportement
de l’ensemble. Nous avons montré que les valeurs extrêmes de la poussée Harc d’un arc et de la
poussée Hab d’un arc-boutant sont différentes si ces éléments structuraux sont considérés
séparément ou dans l’ensemble d’un système structural. Cette limitation des poussées admissibles
joue un rôle important pour l’étude de la géométrie des éléments d’un système structural, car elle
conduit pour certains éléments à la réduction du risque de glissement entre leurs joints. Ainsi, des
géométries, qui sont propices au glissement étant examinées seules, peuvent être adoptées quand
elles font partie des systèmes structuraux comprenant plusieurs éléments (par exemples,

<!-- p. 178 -->

2.7 Conclusion du Chapitre 2 155

géométries des arcs-boutants adoptées dans l’architecture gothique primitive (Nikolinakou et al.
2005, 2006).

• La méthode permet l’estimation des régions susceptibles de formation de rotules d’un système
structural : il s’agit des points d’intersection entre la ligne de pression et le contour de la géométrie
de la structure. Les régions de fissuration de la structure dûes à la présence de traction se
développent alors dans la même section mais sur la paroi opposée. Les limitations aux poussées
admissibles suivant la considération de la stabilité d’un système structural apportent des différences
aux régions susceptibles de formation de rotules relativement aux régions correspondant à une
considération de la stabilité des éléments séparément du système. Cependant, il s’agit de
l’application d’un chargement horizontal qui apporte des différences essentielles par rapport aux
régions susceptibles de formation de rotules.

• La méthode proposée pour l’étude de la stabilité des systèmes structuraux peut être adoptée pour la
simulation des chargements statiques ou quasi-statiques sismiques. Dans ce chapitre, on a examiné
la stabilité d’un système soumis à son poids propre et à un chargement correspondant à une
accélération horizontale constante. Ce dernier chargement peut simuler les forces d’inertie produites
dans la structure avec l’application de l’accélération maximale d’un phénomène dynamique, tel que
le séisme. Ainsi, on a traité le chargement sismique imposé de manière quasi-statique en adoptant
l’hypothèse que l’accélération est uniforme dans la structure entière. Deux valeurs seuils
d’accélération horizontale constante potentiellement supportables par un système symétrique par
rapport à l’axe vertical ont été évaluées : a) une valeur d’accélération correspondant à l’équilibre
ultime du système où chaque élément se trouve à un état différent (passif ou actif) et b) une valeur
d’accélération correspondant à l’équilibre ultime où le système dispose d’un
comportement « homogène » (les éléments symétriques se trouvent au même état). Cette dernière
hypothèse, bien qu’elle conduis à une valeur d’accélération plus conservative, est considérée la plus
commode afin de simuler un phénomène sismique pendant lequel les directions de sollicitation sont
alternées. En définissant cette valeur seuil d’accélération, on peut considérer que la structure reste
stable indépendamment de la durée du phénomène sismique. La simulation du vent peut constituer
un autre cas de chargement dans la direction horizontale.

• La comparaison des résultats de la méthode proposée avec les résultats d’une simulation aux
éléments finis (simulation élastique linéaire et isotrope) a montrée la comptabilité de la solution

<!-- p. 179 -->

156 2 Développement de l’outil

unique fournie par les éléments finis avec le domaine d’équilibre du système défini par la méthode
proposée au cas où l’équilibre du système est possible. La même remarque peut être faite pour les
régions susceptibles d’endommagement. Cependant, la méthode des éléments finis ne renseigne
pas sur le cas où l’équilibre n’est pas possible. En parallèle, elle ne permet pas d’introduire un
comportement « homogène » de la structure sous un chargement horizontal pour la détermination
de la deuxième valeur seuil de l’accélération mentionnée précédemment.

Il est aussi intéressant de noter que, contrairement à la méthode des éléments finis, avec l’utilisation
du Calcul à la Rupture, aucune supposition n’est faite pour la loi de comportement de la maçonnerie,
qui est en général, une caractéristique mécanique difficile à déterminer pour ce matériau. De plus,
l’utilisation du théorème statique du Calcul à la Rupture nous permet d’éviter l’adoption des
hypothèses sur les liaisons des appuis qui sont aussi difficiles à déterminer. Plusieurs états
d’équilibre sont considérés admissibles vis-à-vis du critère de résistance du matériau et on considère
comme inconnus les conditions aux appuis (Heyman, 1998). Cependant, la méthode des éléments
finis exige la définition des conditions aux appuis, ce qui influence beaucoup les résultats. Comme
Heyman (1999) a souligné, le groupe des équations d’équilibre, du matériau et de la compatibilité est
énormément sensible même à une très petite variation des conditions aux appuis.

Le Calcul à la Rupture ne donne aucune information sur les déformations résultant du chargement
de la structure, contrairement à la méthode aux éléments finis. Cependant, dans cette dernière
approche les résultats sont entachés d’une grande incertitude. Il est toutefois possible avec la
méthode du Calcul à la Rupture d’évaluer l’influence de déformations de la structure supposées ou
observées in situ (cf. paragraphe 3.3.2).

• La construction de la ligne de pression avec la méthode du réseau de forces permet de définir les
régions susceptibles des rotules et les poussées extrêmes d’un arc en plein cintre en fonction du
rapport t/r et d’un chargement horizontal. La définition de l’épaisseur minimale d’un arc en plein
cintre avec cette méthode constitue une approximation par défaut (mint/r = 0.109). Cette
approximation est encore plus conservative que celles acquises avec les autres approches
par l’intérieur du Calcul à la Rupture à cause de la définition de la ligne de pression aux abscisses
sur la ligne d’action du poids propre des blocs-voussoirs et pas sur leurs joints.

• La méthode de calcul proposée amène à une évaluation préliminaire de la stabilité des systèmes
maçonnées qui peut être facilement appliquée à des structures réelles comme on le verra dans le

<!-- p. 180 -->

2.7 Conclusion du Chapitre 2 157

chapitre suivant. Il s’agit d’une procédure de calcul qui ne vise pas à remplacer les analyses
mécaniques sophistiquées mais plutôt à préciser les aspects du comportement mécanique des
structures maçonnées que ces analyses doivent mettre en évidence. Les résultats sont exprimés
sous forme de la ligne de pression que l’on trace pour le système entier ainsi que sous forme du
domaine d’équilibre, donné dans l’espace des paramètres hyperstatiques de la structure. Des
dimensions réduites de ce domaine combinées avec un coefficient de sécurité en traction faible,
mesuré dans les sections susceptibles d’endommagement, peut révéler le besoin d’une analyse
mécanique plus sophistiquée. De l’autre côté, si ce domaine se révèle être de dimensions
importantes il s’ensuit que la géométrie de la structure n’est pas un facteur critique pour sa stabilité ;
les études peuvent donc être orientées vers d’autres aspects qui pourraient influencer la stabilité de
la structure. Le tracé de la ligne de pression peut aussi conduire à l’amélioration des résultats
obtenus par des analyses plus sophistiquées (par exemple, pour l’estimation des points candidats
de contact dans le cas d’analyses aux éléments discrets) ou servir en tant qu’analyses préliminaires
nécessaires.

<!-- p. 181 -->

158

<!-- p. 182 -->

Chapitre 3

Applications de l’outil

Résumé du Chapitre 3

Le troisième chapitre élargit les principes d’analyse de stabilité appliqués au système
structural académique présenté au chapitre précédent et poursuite l’étude des systèmes inspirés
d’édifices médiévaux. On traitera trois cas afin d’illustrer le domaine d’application de l’outil
par rapport aux géométries utilisées et à la nature des résultats obtenus. Les coupes
bidimensionnelles des édifices constituent les cas d’étude traités. Les systèmes structuraux
traités portent sur : une coupe inspirée de la géométrie de l’église Santa Maria del Borgo et une
coupe inspirée de la géométrie de la cathédrale d’Amiens et une coupe inspirée de la géométrie
de la basilique de Saint-Quentin.
La première application traite une coupe de l’église Santa Maria del Borgo à Rhodes
(Grèce) au point d’intersection du chœur avec la nef qui est un des vestiges de l’édifice entier.
Notre étude vise à évaluer la stabilité de cette coupe soumise à la gravité ainsi qu’à une
première évaluation de la charge ultime sismique imposée de manière quasi-statique dans son
plan.
La deuxième application se réfère au système de la cathédrale d’Amiens en vue d’une
étude paramétrique menée à l’aide de l’outil. La stabilité de ce système structural est évaluée
pour un chargement sous poids propre. Les arcs ogivaux sont graduellement transformés en
arcs plein cintre. Le changement des états de stabilité de la structure est évalué au moyen des
domaines d’équilibre. En plus, on procède à une comparaison avec d’autres études
paramétriques concernant le changement de la géométrie des arcs.
La troisième application porte sur l’étude d’une coupe de la basilique de Saint-Quentin.
Il s’agit d’un cas où de grandes déformations ont été observées et où des éléments structuraux
ont été rajoutés. Le rôle de ces éléments est évalué par rapport à la stabilité du système sans et
avec déformations.
Finalement les inconvénients de ces approches sont discutés. Le cas sismique par
approche quasi-statique, il faut bien le noter, ne constitue qu’une première approche simplifiée
du chargement sismique. Les systèmes structuraux de la cathédrale d’Amiens et de la basilique

159

<!-- p. 183 -->

de Saint-Quentin constituent des cas complexes et leur étude nécessite la détermination de
plusieurs paramètres afin de construire leur domaine d’équilibre. On met en évidence au
travers ces exemples, premièrement, l’importance des calculs et, deuxièmement, les indications
trouvées dans la structure qui peuvent réduire les difficultés de la visualisation du domaine
d’équilibre (qui dépasse les trois dimensions).

160

<!-- p. 184 -->

3 Applications de l’outil

3.1 Etude de la stabilité d’une coupe inspirée par la
géométrie de l’église Santa Maria del Borgo

La première application de l’outil concerne l’église médiévale de Notre Dame de Borgo à Rhodes,
Grèce (Santa Maria del Borgo, Figure 3.1). Il s’agit d’un exemple typique de l’architecture des Chevaliers
influencé par la riche tradition byzantine locale. C’est une basilique qui s’est composée d’une nef à trois
vaisseaux et de deux arcades de quatre piles. La nef, qui a été couverte probablement de voûtes gothiques,
à été détruite pendant le siège de 1522 des Turcs (Zerlantis et al. 1996, Dellas, 1993). Le chœur tripartite
reste encore aujourd’hui. (Des informations supplémentaires sur ce monument peuvent être trouvées dans le
catalogue de l’exposition Architecture gothique méditerranéenne, édité par le Ministère de la Culture de
Grèce, 2007). La coupe transversale qui connectait le chœur avec la nef est examinée dans ce qui suit.

Figure 3.1 - L’église de Santa Maria del Borgo, Rhodes, Grèce

161

<!-- p. 185 -->

162 3 Applications de l’outil

Le système comporte trois arcs ogivaux et il est symétrique par rapport à l’axe vertical Oz (Figure
3.2). Des systèmes similaires, composés de trois arcs, ont été examinés par Block et al. (2006a) et par
Smars (2000) pour un chargement sous poids propre. Les arcs étudiés de l’église de Santa Maria del Borgo
présentent la particularité géométrique suivante. Le centre Oext du contour extérieur de chaque arc se
trouve au dessus du centre Oint du contour intérieur de sorte que l’épaisseur de chaque arc varie de la
naissance à la clé (Figure 3.2).

Figure 3.2 - Le système examiné (église Santa Maria del Borgo)

La géométrie du système est définie par les paramètres suivants:

a) le rayon Rintarc du contour intérieur de l’arc central,

b) la hauteur Hintarc du contour intérieur de l’arc central,

c) le rayon Rextarc du contour extérieur de l’arc central,

d) la hauteur Hextarc du contour extérieur de l’arc central,

e) le rayon Rintc du contour intérieur de l’arc latéral,

f) la hauteur Hintc du contour intérieur de l’arc latéral,

<!-- p. 186 -->

3.1 Stabilité d’une coupe de l’église de Santa Maria del Borgo 163

g) le rayon Rextc du contour extérieur de l’arc latéral,

h) la hauteur Hextc du contour extérieur de l’arc latéral,

i) la hauteur hp des piliers,

j) la hauteur hcu des contreforts,

k) l’épaisseur tp des piliers,

l) l’épaisseur tcu des contreforts et

m) la distance entre les centres Oext et Oint de chaque arc.

La géométrie du système est décrite par les proportions suivantes :

Rext arcROint arc = 2 .16 , ROext arc = 1 .76 , = .123 ,
Rint arc

Rext c t p h cuROint c = 1.41 , ROext c = 1.67 , = .110 , = .075 , = 1.53
Rint c t cu h p

OOint arc OOint arc O c Oint c = 1.00 , = .074 , = .076
h p OOext arc O c Oext c

Premièrement, la structure est soumise à son poids propre. La solution statique pour la structure est
construite en supposant une valeur pour les trois poussées inconnues H arc , H c et H c* qui sont appliquées
aux extrémités de l’arc central, de l’arc latéral droit et de l’arc latéral gauche respectivement. Pour ce cas de
changement et de géométrie symétriques on considère : H c = H c* . L’étude de la stabilité des blocs de la
jonction de ce système est fondée sur les mêmes hypothèses présentées dans le paragraphe 2.2.4, mais
comme les éléments se joignent aux côtés gauche, droit et inférieur du bloc (au lieu des côtés supérieur,
droit et inférieur du bloc), la prise en compte des régions d’influence des éléments est différente.

Considération de la stabilité des jonctions de deux arcs

La stabilité de la jonction entre l’arc central et les arcs latéraux (la Figure 3.3 présente la jonction
entre l’arc central et l’arc latéral droit) est examinée en considérant le bloc ABF1D1 où les lignes d’action
G G
des réactions Rarc de l’arc central et Rc de l’arc latéral se coupent au point I1. On divise ce bloc en deux
blocs AC1I1D1 et C1BF1 I1, qui sont considérés comme régions d’influence de l’arc central et de l’arc latéral
respectivement et on effectue la procédure itérative présentée dans le paragraphe 2.2.4 pour préciser le
point I d’intersection des lignes de pression des deux arcs et du poids propre du bloc de la jonction.

<!-- p. 187 -->

164 3 Applications de l’outil

Figure 3.3 - Considération de la stabilité de la jonction entre l’arc central et l’arc latéral droit

Dans la Figure 3.4 et la Figure 3.5, on présente les lignes de pression du système pour les valeurs
minimale et maximale de la poussée de l’arc central respectivement (chargement sous poids propre). Pour
chaque cas, les lignes de pression du système pour les deux valeurs extrêmes de la poussée des arcs
latéraux sont données.

Figure 3.4 - Lignes de pression du système pour : minHarc, minHc \< Hc \< maxHc

<!-- p. 188 -->

3.1 Stabilité d’une coupe de l’église de Santa Maria del Borgo 165

Figure 3.5 - Lignes de pression du système pour : maxHarc, minHc \< Hc \< maxHc

Ensuite, le système est soumis à un chargement sismique dans le plan imposé de manière quasistatique. On adopte l’hypothèse conservative que les poussées développées aux arcs latéraux sont égales
afin de prévoir un comportement « homogène » de la structure (cf. paragraphe 2.3.2b). Sur les figures
suivantes, on présente les lignes de pression du système en considérant le chargement sous poids propre et
un chargement sismique de Ks=0.1. De la même manière que précédemment, la Figure 3.6 et la Figure 3.7
représentent l’équilibre du système pour les valeurs minimale et maximale de la poussée de l’arc central
respectivement. Pour chaque cas, les lignes de pression du système pour les deux valeurs extrêmes de la
poussée des arcs latéraux sont données.

<!-- p. 189 -->

166 3 Applications de l’outil

Figure 3.6 - Lignes de pression du système pour : minHarc, minHc \< Hc \< maxHc. Chargement sismique Ks=0.1

Figure 3.7 - Lignes de pression du système pour : maxHarc, minHc \< Hc \< maxHc. Chargement sismique Ks=0.1

<!-- p. 190 -->

3.1 Stabilité d’une coupe de l’église de Santa Maria del Borgo 167

Les domaines d’équilibre du système sont présentés dans la Figure 3.8 pour cinq cas de
chargement. La ligne en pointillé correspond au domaine d’équilibre du système pour un chargement sous
poids propre uniquement (Ks = 0) et les lignes continues aux domaines d’équilibre pour un chargement sous
poids propre et un chargement sismique d’accélération croissante de Ks=0.05, Ks=0.1, Ks=0.15 à Ks=0.17.
La figure montre la réduction du domaine d’équilibre des toutes des combinaisons admissibles de poussées
avec l’augmentation de l’accélération sismique. Pour le dernier cas (Ks=0.17), le domaine d’équilibre est
réduit aux dimensions d’un point ; il s’agit de l’état ultime du système ; le système est stable pour une seule
combinaison de poussées des arcs.

Figure 3.8 - Domaine d’équilibre du système pour chargement sous poids propre et pour des chargements

sismiques d’intensité variable

On peut faire les remarques suivantes au regard des résultats précédents. Quand on applique le
chargement sismique sur la structure (Figure 3.6, Figure 3.7), il y a un changement aux points susceptibles
de formation des rotules aux contours intérieurs et extérieurs des arcs par rapport aux points susceptibles
dans le cas du chargement sous poids propre uniquement (Figure 3.4, Figure 3.5). De plus, l’écart des
poussées admissibles aux arcs latéraux est beaucoup plus faible en considérant la poussée maximale
appliquée à l’arc central qu’en considérant la poussée minimale. Quand l’accélération sismique augmente ce
phénomène devient plus intense (Figure 3.8) jusqu’au point où les deux valeurs extrêmes des poussées
pour les arcs latéraux coïncident pour Ks approximativement supérieur à 0.15. En d’autres termes, le
domaine d’équilibre devient triangulaire avant de se minimiser à un point.

<!-- p. 191 -->

168 3 Applications de l’outil

L’évaluation de la valeur minimale d’accélération pour la création d’un mécanisme de rupture
obtenue en utilisant l’approche statique du Calcul à la Rupture est généralement très conservative1. Une
autre estimation peut être obtenue en utilisant l’approche cinématique du Calcul à la Rupture (simulation du
séisme de manière quasi-statique). Cette approche pourrait servir comme une comparaison de la valeur
d’accélération obtenue avec l’approche statique mais, généralement, elle n’est applicable qu’aux systèmes
structuraux simples (comme un arc supporté sur deux piliers, Ochsendorf 2002, De Luca et al. 2009,
Brandonisio et al. 2009). Les mécanismes de rupture possibles se multiplient avec la complexité du système
structural. Dans ce sens, les rotules obtenues avec l’approche statique peuvent servir pour la formation des
mécanismes étudiés avec l’approche cinématique.

1 On note que l’accélération réglementaire à Rhodes est égale à Ks=0.24.

<!-- p. 192 -->

3.2 Stabilité d’une coupe de la cathédrale d’Amiens 169

3.2 Etude de la stabilité d’une coupe inspirée par la
géométrie de la nef de la cathédrale d’Amiens

L’outil de calcul est appliqué dans ce paragraphe à un système structural, relatif à des structures
gothiques, qui est inspirée par la nef de la cathédrale d’Amiens (Figure 3.9). Le système est symétrique par
rapport à l’axe vertical Oz. Il comporte un arc ogival central supporté sur deux piliers et par deux arcsboutants. Il y a encore deux arcs ogivaux latéraux. Le système n’est soumis qu’à son poids propre. On note
que l'on n’a pas intégré dans ce modèle l’arc-boutant supérieur. Cet arc-boutant est considéré supporter les
charges du vent et du toit et par conséquent, il ne sera pas inclus dans le modèle proposé. On note, aussi,
que le point de jonction de l’arc-boutant inférieur avec l’arc central est différent. Bien que différent du
système d’Amiens, le système étudié ici illustre l’étude d’un cas plus complexe qui servira à la réalisation des
études paramétriques de géométrie.

Figure 3.9 - A gauche : coupe de la nef de la cathédrale d’Amiens. A droite : le système étudié

La géométrie du système est définie par les éléments suivants :

a) le rayon intérieur Rintarc de l’arc central,

b) la hauteur intérieure Hintarc de l’arc central,

<!-- p. 193 -->

170 3 Applications de l’outil

c) l’épaisseur tarc de l’arc central,

d) la hauteur hp du centre de l’arc central,

e) le rayon intérieur Rintab de l’arc-boutant,

f) l’épaisseur tcu des culées de l’arc-boutant,

g) le rayon intérieur Rintc de l’arc latéral,

h) la hauteur intérieure Rintc de l’arc latéral,

i) l’épaisseur tc de l’arc latéral,

j) la hauteur hc du centre de l’arc latéral.

Pour le système examiné on supposera les proportions suivantes :

t arc t cROarc = 1.56, = 0. 08, ROc = 1.42, = 0. 17,
rarc rc
Rint ab Rint ab t cu t p = 1.24, = 2, = 7.71, = 0.39,
Rint arc Rint c t arc t cu
h p h p = 2.93, = 1.74
hc hab

La solution statique pour ce système structural soumis à son poids propre est construite en
supposant une valeur pour les poussées inconnues Harc, Hc et Hab qui sont appliquées aux extrémités des
arcs central et latéral et de l’arc-boutant respectivement. On note que, par rapport au système académique
étudié au paragraphe 2.3, un troisième paramètre inconnu est introduit, la poussée Hc aux extrémités de
l’arc latéral, ce qui apporte les changements suivants par rapport à la procédure présentée dans le
paragraphe 2.3.1.1a. La stabilité du système est examinée en introduisant les valeurs des trois poussées :
Harc, Hab et Hc. La vérification de la stabilité du système est faite en examinant la stabilité à la fois des
parties de la culée (2a) et du pilier (2c) définies entre l’arc-boutant et l’arc latéral, ainsi que la stabilité des
trois blocs de jonction (2b).

Les résultats pour les valeurs minimale et maximale de la poussée de l’arc central sont présentés
sur la Figure 3.10a et la Figure 3.10b, respectivement. Pour chaque cas, on présente les poussées extrêmes
admissibles de l’arc-boutant. Les résultats sont donnés pour la poussée maximale de l’arc latéral qui
correspond à la poussée la moins favorable pour la stabilité du système.

<!-- p. 194 -->

3.2 Stabilité d’une coupe de la cathédrale d’Amiens 171

Figure 3.10 - Linges de pression du système pour : (a) minHarc, maxHc, minHab \< Hab \< maxHab

(b) maxHarc, maxHc, minHab \< Hab \< maxHab

On note que, dans le cas de la poussée minimale dans l’arc central, il n’y a qu’une poussée de l’arcboutant qui peut assurer l’équilibre du système qui est égale à la valeur minimale (dans la Figure 3.10a il n’y
qu’une ligne dans l’arc-boutant qui est en pointillé). La même remarque peut être faite sur le domaine
d’équilibre du système donné dans l’espace des Harc et Hab où le domaine est triangulaire (Figure 3.11, ligne
en pointillé). Le domaine triangulaire en ligne en pointillé est construit en considérant la poussée maximale
de l’arc latéral. Dans la même figure on présente aussi en pointillé le domaine d’équilibre du système en
appliquant la poussée minimale de l’arc latéral et en ligne continue le domaine d’équilibre d’une structure
similaire sans les arcs latéraux et avec une hauteur des piliers diminuée hp - hc (un système structural
correspondant à celui présenté dans le paragraphe 2.3.1.1).

<!-- p. 195 -->

172 3 Applications de l’outil

Figure 3.11 - Domaine d’équilibre du système pour hp - hc et hp (considération de minHc et maxHc)

Les résultats montrent que le domaine d’équilibre des poussées de l’arc central et de l’arc-boutant
est d’autant plus faible que la hauteur de la structure augmente, ce qui est attendu. On doit noter que la
réduction des poussées admissibles développées à ces éléments est contrebalancée par le développement
des poussées de l’arc latéral. Le domaine d’équilibre de la coupe inspirée par la cathédrale d’Amiens
correspond à un hexaèdre dans l’espace tridimensionnel (Harc, Hab, Hc) comme présenté dans la Figure
3.12.

Figure 3.12 - Domaine d’équilibre du système

<!-- p. 196 -->

3.2 Stabilité d’une coupe de la cathédrale d’Amiens 173

3.2.1 Etudes paramétriques de la stabilité d’une coupe inspirée par

la géométrie de la nef de la cathédral d’Amiens

Dans le présent paragraphe on procède à une paramétrisation de la coupe inspirée par la géométrie
de la nef de la cathédrale d’Amiens au regard du rapport ogival de l’arc central en passant progressivement
d’un arc ogival de RO = 173% à un arc en plein cintre de RO = 100% (tous les autres paramètres restent
constants). Dans la Figure 3.13a et la Figure 3.13b, on présente les poussées minimales et maximales de
l’arc central et de l’arc-boutant respectivement, en considérant la poussée maximale de l’arc latéral. Dans
chaque figure les résultats sont présentés pour deux géométries de l’arc central: RO = 100% et RO = 156%
(rapport ogival de l’arc central de la cathédrale d’Amiens). La convention suivante est introduite par rapport
aux lignes : la ligne continue et en pointillé correspondent aux lignes de pression du système avec un arc
central ogival (RO = 156%) et avec un arc central en plein cintre (RO = 100%) respectivement. On note que
la poussée minimale de l’arc-boutant est égale à 14% de son poids propre pour RO = 100% ainsi que pour
RO=156% de l’arc central. A cause de cet effet, il y a seulement une ligne de pression dans l’arc-boutant de
la Figure 3.13a.

Figure 3.13 - Lignes de pression du système pour RO = 100% et RO = 156%: (a) minHarc, minHab, maxHc,

(b) maxHarc, maxHab, maxHc

<!-- p. 197 -->

174 3 Applications de l’outil

Le domaine d’équilibre du système est présenté sur la Figure 3.14 où quatre configurations
géométriques de l’arc central sont examinées : RO = 156% (géométrie initiale), RO = 100% (géométrie d’un
arc en plein cintre), RO = 125%, RO = 173% (géométrie d’un arc en tiers point).

Figure 3.14 - Domaines d’équilibre du système pour RO = 100%, RO = 125%, RO = 156%, RO = 173%

Le diagramme du domaine d’équilibre du système mène aux remarques suivantes :

• La poussée minimale de l’arc-boutant est indépendante du changement de rapport RO de l’arc
central et de l’application de la poussée minimale ou maximale à l’arc central. La valeur de la
poussée de l’arc-boutant à la base de chaque domaine est constante et égale à minHab = 14%.
(La même remarque a été aussi notée sur les résultats des lignes de pression dans la Figure
3.13a où il n’y qu’une ligne dans l’arc-boutant pour RO = 100% et pour RO = 156%).

• L’augmentation de rapport RO de l’arc central est liée à la réduction de la taille du domaine
d’équilibre du système ce qui signifie la réduction du nombre des combinaisons admissibles des
poussées des arcs et de l’arc-boutant. Pour RO = 173%, le domaine d’équilibre est réduit à un
triangle ; la stabilité du système est assurée en considérant la poussée unique de l’arc central
(Harc = 14%) et les combinaisons admissibles des poussées de l’arc-boutant et de l’arc latéral.
(La poussée de l’arc-boutant peut varier entre 15% et 17% et la poussée de l’arc latéral entre

<!-- p. 198 -->

3.2 Stabilité d’une coupe de la cathédrale d’Amiens 175

16% et 24% du poids propre de chaque élément. Pour les autres valeurs de rapport RO la
poussée de l’arc latéral peut varier entre 16% et 31% de son poids propre).

• La valeur de la poussée minimale de l’arc central diminue avec l’augmentation du rapport RO,
comme on peut aussi noter sur l’étude paramétrique réalisée par Ciblac (2008, Figure 3.15) où
l’arc est examiné seul (l’étude fournit des courbes limites de la poussée minimale et maximale,
rapportées au poids total de l’arc et données en fonction de t/r pour des valeurs de RO
variables). Ce qui ne fait que confirmer la remarque que les arcs les plus élancés sont ceux qui
nécessitent le moins de contrebutement par les supports.

Figure 3.15 - Rapport entre la solution obtenue pour la considération de l’arc (RO = 173%) dans le système structural

et des solutions obtenues pour un arc examiné seul de l’étude paramétrique de Ciblac (2008)

• L’écart des valeurs des poussées admissibles pour l’arc central diminue avec l’augmentation du
rapport RO suivant l’étude paramétrique de la coupe inspirée par la cathédrale d’Amiens (t/r =
8.1%). En regardant aussi l’étude de Ciblac, on peut noter que pour une valeur constante du
rapport t/r, la même remarque peut être faite. Cela signifie que l’amplitude et les bornes des
poussées admissibles pour la stabilité sont moindres pour des rapports RO plus grands pour un
arc considéré seul tant que dans un système structural.

<!-- p. 199 -->

176 3 Applications de l’outil

• Les résultats fournis par l’étude paramétrique de la coupe d’Amiens montrent que la stabilité du
système est possible pour t/r = 8.1% de l’arc central et tous rapports RO entre 173% et 100%.
Cependant, on peut noter que ces résultats divergent sensiblement avec les résultats donnés
par l’étude paramétrique d’un arc seul de Ciblac. Par exemple, la stabilité d’un arc de t/r = 8.1%
et RO = 100%, RO = 125% n’est pas possible quand l’arc est examiné seul (l’étude
paramétrique de Ciblac donne mint/r = 11% pour RO = 100% et mint/r = 8.33% pour RO =
125%). Il est intéressant de noter les causes de la différence du comportement de cet arc dans
le cas où il est examiné comme un élément structural du système et dans le cas où il est
examiné seul. Dans le premier cas, l’arc est retenu par les arcs-boutants et ses poussées sont
réduites par le poids propre des éléments supérieurs (paragraphe 3.1.5.b), effets qui constituent
un cas stable une telle géométrie d’arc.

• L’étude paramétrique du système pour un rapport RO = 173% indique une différence sur
l’épaisseur minimale et sur les poussées admissibles de l’arc central par rapport aux mêmes
valeurs d’un arc de la même géométrie examiné seul (Figure 3.15). La combinaison des valeurs
RO = 173% et t/r = 8.1% est très proche de la valeur minimale du rapport t/r de l’arc considéré
dans le système structural (poussée unique Harc = 14%). Cependant, pour un arc de RO =
173% examiné seul, la valeur correspondante est égale à mint/r = 7.9% selon l’étude
paramétrique de Ciblac (poussée unique Harc = 11.5%). On peut conclure que, comme on est
dans le cas d’une géométrie correspondant à l’équilibre limite, des petites variations ont des
conséquences considérables sur la stabilité.

<!-- p. 200 -->

3.4 Conclusion du Chapitre 3 177

3.3 Etude de la stabilité d’une coupe inspirée par le
chevet de la basilique de Saint-Quentin

Dans ce paragraphe on étudiera la stabilité d’un système structural inspiré de la basilique de SaintQuentin de l’Aisne (Figure 3.16). Pendant la longue durée de construction (du 12ème au 15ème siècle) de ce
monument historique et lors des multiples efforts de restauration et de consolidation, des parties et des
éléments structuraux ont été reconstruits ou rajoutés. Aujourd’hui, le monument subit des altérations
diverses.

Figure 3.16 - A gauche : plan de la basilique de Saint-Quentin. A droite: vue extérieure de la partie du chevet étudiée

Parmi ces altérations, les déversements des piliers absidiaux paraissent très importants. Les plus
grands défauts d’aplomb sont remarqués aux niveaux de naissance des arcs de l’abside et des arcs du
déambulatoire. Dans ce qui suit, on se concentrera sur l’étude de stabilité d’une coupe inspirée par la coupe
du chevet de cette église, cerclée sur la Figure 3.16. Le même système structural est répété quatre fois entre
les chapelles absidiales (Figure 3.17).

<!-- p. 201 -->

178 3 Applications de l’outil

Figure 3.17 - A gauche: coupe typique du chevet. A droite : vue entre deux coupes typiques du chevet

En ce qui concerne l’historique de la construction et de la mise en place des éléments du chevet, on
note que les arcs-boutants supérieur et inférieur ont été réalisés dans la première phase de la construction
(vers 1250). L’arc-boutant intermédiaire a été rajouté au 14ème siècle. Le défaut d’aplomb important au
niveau des arcs du déambulatoire a nécessité la mise en place successive des tirants depuis 1475 (les deux
interventions sont marquées sur la coupe typique de la Figure 3.17). La forme actuelle des tirants en bois est
moderne (Figure 3.18).

Figure 3.18 - Les tirants en bois du déambulatoire

<!-- p. 202 -->

3.4 Conclusion du Chapitre 3 179

Le système structural étudié se compose de la moitié d’un arc ogival appartenant à l’abside qui est
contrebuté par trois arcs-boutants. Il y a encore un deuxième arc ogival appartenant au déambulatoire
(Figure 3.19). On note que, dans ce système, on n’a pas pris en compte la partie rectiligne de l’arc-boutant
supérieur. Car, le comportement de ce type d’arc-boutant peut être considéré équivalent à celui de deux
organes de contrebutement différents (Heyman, 1995). La partie rectiligne sert pour la reprise des charges
de la toiture et la partie circulaire sert pour le contrebutement de l’arc central (la fissuration de chaque partie
est transférée à l’autre à travers des colonnettes qui les relient, Figure 3.17).

Figure 3.19 - Le système étudié

La géométrie du système est définie par les éléments suivants :

a) le rayon intérieur Rintarc de l’arc de l’abside,

b) la hauteur intérieure Hintarc de l’arc de l’abside,

c) l’épaisseur tarc de l’arc de l’abside

d) la hauteur hp du centre de l’arc de l’abside,

e) le rayon intérieur Rintab des arcs-boutants,

<!-- p. 203 -->

180 3 Applications de l’outil

f) les épaisseurs successives tcu,1, tcu,2, et tcu,3 de la culée des arcs-boutants,

g) les hauteurs hab,1, hab,2, et hab,3 des centres des arcs-boutants supérieur, intermédiaire, inférieur,

h) le rayon intérieur Rintc de l’arc du déambulatoire,

i) la hauteur intérieure Hintc de l’arc du déambulatoire,

j) l’épaisseur tc de l’arc du déambulatoire,

k) la hauteur hc du centre de l’arc du déambulatoire.

Pour le système examiné on supposera les proportions suivantes :

t arc t c t arcROarc = 1.25, = 0 .06, ROc = 1.51, = 0.13, = 5.13,
rarc rc t c
Rint ab Rint ab t cu ,1 t cu ,1 t cu ,1 = 0.83, = 2, = 1.18, = 0.77, = 0.55,
Rint arc Rint c t p t cu ,2 t cu ,3
h p h p hab , 1 hab , 1 = 2.71, = 1.23, = 1.12, = 1.64
hc hab , 1 hab , 2 hab ,3

Dans le cas de la coupe de Saint-Quentin, on a un nombre important de paramètres inconnus : les
poussées H arc et H c de l’arc central et de l’arc du déambulatoire et les poussées H ab 1, , H ab , 2 , et H ab 3,
des arcs-boutants supérieur, intermédiaire et inférieur, respectivement. Les défauts de l’aplomb du pilier aux
niveaux de naissance de l’arc de l’abside et de l’arc du déambulatoire résultent pour chaque arc d’une
augmentation de son écartement et permettent de supposer que ces éléments se trouvent à l’état passif. Les
étapes de la procédure présentée dans le paragraphe 2.3.1.1a sont modifiées par rapport aux points
suivants:

1 et 5. On précise les valeurs minimales des poussées H arc et H c séparément du système pour chaque
arc et on les considère comme poussées effectives uniques, car les arcs sont supposés être dans l’état
passif. (L’étude de la stabilité du système pour l’application de la poussée maximale de chaque arc est
exclue).

\2. La stabilité du système est examinée en considérant les combinaisons possibles pour les valeurs
extrêmes de trois poussées : H ab 1, , H ab , 2 , et H ab 3, . La vérification est faite en examinant la stabilité à la
fois des parties de la culée (2a) et du pilier (2c) définies entre les trois arcs-boutants et de l’arc du
déambulatoire, ainsi que la stabilité des cinq blocs de jonction (2b).

En raison du manque des mesures précises de la géométrie actuelle du bâtiment, on procédera à une
estimation qualitative des poussées exercées aux éléments du chevet afin d’investiguer la fonction de

<!-- p. 204 -->

3.4 Conclusion du Chapitre 3 181

chaque élément et de déterminer la poussée supplémentaire maximale exercée au niveau de la naissance
de l’arc de l’abside par les éléments supérieurs de l’abside (voûte, toiture, etc.). Finalement, on réévaluera la
stabilité du système pour une géométrie déformée en ce qui concerne l’arc du déambulatoire.

3.3.1 Stabilité du système et effet de l’adjonction de l’arc-boutant

intermédiaire

La solution statique pour ce système structural soumis à son poids propre est construite en
supposant une valeur pour les poussées inconnues H ab 1, , H ab , 2 , et H ab 3, des arcs-boutants supérieur,
intermédiaire et inférieur respectivement, étant donné que l’on n’applique que la poussée minimale des arcs
de l’abside et du déambulatoire. Dans la Figure 3.20a et la Figure 3.20b on présente les lignes de pression
du système d’origine et du système après l’adjonction de l’arc-boutant intermédiaire, respectivement. Pour
chaque géométrie, on présente la stabilité du système pour la poussée minimale (en ligne en pointillé) et
maximale (en ligne continue) de l’arc-boutant inférieur en considérant la poussée maximale de l’arc-boutant
supérieur. Pour la géométrie après l’adjonction de l’arc-boutant intermédiaire on considère le développement
de la poussée minimale de cet élément.

<!-- p. 205 -->

182 3 Applications de l’outil

Figure 3.20 - Lignes de pression pour:

(a) le système d’origine et minHarc, minHc, maxHab,1, minHab,3 \< Hab,3 \< maxHab,3

(b) le système des 3 arcs-boutants et minHarc, minHc, maxHab,1, minHab,2, minHab,3 \< Hab,3 \< maxHab,3

On note que la poussée admissible pour la stabilité du système développée à l’arc-boutant inférieur
au système d’origine varie entre 25% et 51% de son poids propre ayant considéré la poussée maximale de
l’arc-boutant supérieur. Cependant, après l’adjonction de l’arc-boutant intermédiaire, cette poussée est
unique est égale à sa valeur minimale (il n’y a qu’une seule ligne qui est en pointillé dans l’arc-boutant
inférieur de la Figure 3.20b). La limitation des poussées admissibles de l’arc-boutant inférieur est
contrebalancée par l’action de l’arc-boutant intermédiaire comme on notera, aussi, dans les domaines de
l’équilibre du système présentés dans la Figure 3.21.

Les domaines d’équilibre du système sont présentés dans la Figure 3.21 en fonction des poussées
H ab 1, , H ab 3, des arcs-boutants supérieur et inférieur comme pourcentage du poids propre de chaque
élément pour deux géométries : domaine de la géométrie d’origine avec deux arcs-boutants en ligne
continue et domaine de la géométrie après l’adjonction de l’arc-boutant intermédiaire en ligne en pointillé. Le
domaine d’équilibre de la géométrie avec trois arcs-boutants est présenté pour l’application de la poussée
minimale à l’arc-boutant intermédiaire (minHab,2 = 26% de son poids propre). La poussée minimale des arcs

<!-- p. 206 -->

3.4 Conclusion du Chapitre 3 183

de l’abside et du déambulatoire sont égales à minHarc = 19% et minHc = 15% du poids propre de chaque
élément, respectivement.

Figure 3.21 - Domaines d’équilibre du système d’origine et du système après l’adjonction de l’arc-boutant

intermédiaire (considération minHab,2)

On voit qu’il y a une réduction des combinaisons des poussées admissibles des arcs-boutants
supérieur et inférieur après l’adjonction de l’arc-boutant intermédiaire. Cette réduction est contrebalancée par
les combinaisons des poussées admissibles aux trois arcs-boutants qui correspondent à un domaine
d’équilibre développé dans l’espace tridimensionnel (Figure 3.22). Si l’on examine les arcs-boutants
intermédiaire et inférieur séparément du système, on peut considérer que leur poussée maximale est infinie
à cause de leur géométrie. Pour cela, la détermination du cas de stabilité avec développement des poussées
maximales simultanément à ces arcs-boutants (soit pour la poussée maximale ou minimale de l’arc-boutant
circulaire) ne peut pas être défini. Ainsi, dans l’espace tridimensionnel, le domaine est un tétraèdre. On note
que la poussée maximale possiblement développée à l’arc-boutant intermédiaire est égale à maxHab,2 =
64% de son poids propre, ayant considéré comme poussées effectives des arcs-boutants supérieur et
inférieur les valeurs minimales minHab,1 = 35% et minHab,3 = 25% du poids propre de chaque élément,
respectivement.

<!-- p. 207 -->

184 3 Applications de l’outil

Figure 3.22 - Domaines d’équilibre du système après l’adjonction de l’arc-boutant intermédiaire

L’effet de l’arc-boutant intermédiaire n’apparaît pas nécessaire pour la stabilité du système pour un
chargement seulement sous poids propre. Dans le calcul des domaines d’équilibre précédents, on suppose
que l’arc de l’abside n’exerce au système que son poids propre et sa poussée minimale définie par sa
géométrie. Cependant, cet élément est chargé à porter et à transférer les charges qui proviennent de la
partie supérieure du chevet (toiture, voûte, etc.). Les charges de cette partie apportent de grandes
différences à la stabilité du système en comparaison avec la considération de la stabilité présentée dans la
Figure 3.21. D’une part, les charges verticales constituent des effets stabilisants et d’autre part, le cas
d’instabilité peut être atteint quand les charges horizontales dépassent une certaine limite. En essayant de
préciser cette limite on a intégré au calcul de la stabilité du système une force horizontale qu’elle s’exerce au
même point que la poussée minimale de l’arc de l’abside. Afin de simplifier les calculs, l’effet des charges
verticales ne sont pas pris en compte. La valeur de la poussée supplémentaire maximale supportée par le
système est égale à Hvo = 40% pour la géométrie d’origine et égale à Hvt = 69% pour la géométrie après
l’adjonction de l’arc-boutant intermédiaire. Dans la Figure 3.23a et la Figure 3.23b on présente les lignes de
pression du système pour les géométries mentionnées respectivement.

<!-- p. 208 -->

3.4 Conclusion du Chapitre 3 185

Figure 3.23 - Lignes de pression pour:

(a) le système d’origine et maxHvo, minHarc, minHc, maxHab,1, minHab,3

(b) le système des 3 arcs-boutants et maxHvt, minHarc, minHc, maxHab,1, minHab,2, minHab,3

Les poussées appliquées aux arcs-boutants sont les minimales pour stabiliser le système à
l’exception de la poussée de l’arc-boutant supérieur où l’on considère la poussée maximale (76% de son
poids propre). Pour les deux géométries, la poussée minimale de l’arc-boutant inférieur est égale à 50% de
son poids propre et pour la géométrie des trois arcs-boutants la poussée minimale de l’arc-boutant
intermédiaire est égale à 114% de son poids propre.

L’augmentation de la force supplémentaire maximale avec l’adjonction de l’arc-boutant intermédiaire
montre que cet élément sert considérablement à la stabilité du système global. La connaissance exacte des
forces appliquées à la région de la naissance de l’arc de l’abside et la comparaison avec la valeur maximale
calculée auparavant peuvent expliquer si le déversement du pilier à cette hauteur est dû au fait du
dépassement des poussées supportables par le système.

<!-- p. 209 -->

186 3 Applications de l’outil

3.3.2 Stabilité du système pour une géométrie déformée

Dans ce paragraphe, on étudiera la stabilité du système en prenant en compte le changement de la
géométrie provoqué par le plus grand déversement du pilier qui est marqué au niveau de la naissance de
l’arc du déambulatoire (qui a nécessité la mise en place des tirants). Ce défaut d’aplomb, qui n’est observé
qu’au pilier (on manque d’informations sur l’éventuel déversement de la culée), se passe à la direction
inverse du défaut d’aplomb du pilier au niveau de l’arc de l’abside. En l’absence de vraies mesures
concernant les déversements du pilier, on procédera aux calculs de stabilité de la partie inférieure de l’arc du
G G
déambulatoire en supposant que la partie supérieure reste intacte. Alors, les forces R p et Rcu exercées à
une section verticale du pilier et de la culée, respectivement, au niveau de naissance de l’arc du
déambulatoire seront calculées comme au paragraphe précédent. La structure est désormais considérée à
son état déformé. Le déversement du pilier provoque une augmentation dx de l’écartement de l’arc du
déambulatoire et un tassement dz de la clé (Figure 3.24).

Figure 3.24 - Déversement du pilier et augmentation correspondante de l’écartement d’arc du déambulatoire

N’ayant pas d‘indications de fissuration (Figure 3.18), on supposera que le matériau est consolidé et
on procédera aux calculs de stabilité pour une maçonnerie continue mais déformée. Le changement de la
géométrie de l’arc à cause de l’augmentation de l’écartement est présenté dans l’Annexe 1.

<!-- p. 210 -->

3.4 Conclusion du Chapitre 3 187

Les domaines d’équilibre pour le système d’origine sont présentés dans la Figure 3.25 sans
déformation (ligne continue) et avec l’augmentation hypothétique de l’écartement de l’arc du déambulatoire
de dx = 0.1tp (ligne en pointillé) dans l’espace des H ab 1, , H ab 3, .

Figure 3.25 - Domaine d’équilibre du système d’origine (dx = 0 et dx = 0.1tp)

Respectivement, dans la Figure 3.26 on présente le domaine d’équilibre pour la géométrie du
système après l’adjonction de l’arc-boutant intermédiaire sans déformation (domaine extérieur) et avec une
augmentation hypothétique de l’écartement de l’arc du déambulatoire de 0.1tp (domaine intérieur). Dans les
deux diagrammes, les réductions du domaine d’équilibre reflète le fait évident que le système est moins
stable pour la déformation considérée. On peut attribuer ce résultat à une capacité réduite du pilier à recevoir
les poussées à cause du déplacement de son centre de gravité.

<!-- p. 211 -->

188 3 Applications de l’outil

Figure 3.26 - Domaines d’équilibre du système après l’adjonction de l’arc-boutant intermédiaire (dx = 0 et dx = 0.1tp)

On notera également que la géométrie déformée de l’arc du déambulatoire (de rapport ogival réduit)
entraînera une poussée minimale plus importante, comme présenté dans le Tableau 3.1. Dans ce tableau,
on présente le tassement de la clé, le rapport ogival et la poussée minimale de l’arc du déambulatoire ainsi
que la vérification de la stabilité du système pour un défaut d’aplomb du pilier de: 0, 0.1tp, 0.3tp et 0.45tp.

minHc Stabilité Stabilité dx dz
ROc (%) (% du poids propre géométrie avec géométrie avec
(% de tp) (% de Hintc) de l’arc) 2 arcs-boutants 3 arcs-boutants
0 0 1.51 15 oui oui
10 2 1.42 17 oui oui
30 8 1.25 19 oui oui
45 12 1.14 21 oui non

Tableau 3.1 - Paramètres de l’arc du déambulatoire et vérification de la stabilité du système pour différentes

valeurs du défaut d’aplomb du pilier

<!-- p. 212 -->

3.4 Conclusion du Chapitre 3 189

On voit que la stabilité du système est assurée pour chargement sous poids propre ainsi que pour la
déformation de 0.1tp. Les déformations de 0.45tp et de 0.3tp sont les cas ultimes de stabilité du système
d’origine et du système des trois arcs-boutants, respectivement. L’arc-boutant intermédiaire apporte un effet
stabilisant pour l’arc de l’abside, comme présenté dans le paragraphe précédent, mais diminue la résistance
globale du système quand l’arc du déambulatoire est déformé.

Les tirants nécessaires peuvent être dimensionnés en sachant le défaut d’aplomb précis à la
naissance de l’arc du déambulatoire et l’existence des poussées supplémentaires provenant des autres
facteurs hors du poids propre de cet arc.

<!-- p. 213 -->

190 3 Applications de l’outil

3.4 Conclusion du Chapitre 3

Dans ce chapitre, on a essayé de montrer l’applicabilité de l’outil dans trois cas d’études réalistes.
Des conclusions suivantes peuvent être tirées de l’étude de stabilité de ces trois systèmes structuraux.

• L’utilité de la méthode porte sur le fait qu’elle peut être facilement appliquée à un grand nombre de
structures permettant d’obtenir une estimation préliminaire de la stabilité. Des géométries différentes
de celles rencontrées habituellement (comme les arcs de la coupe de l’église de Santa Maria del
Borgo) ainsi que des systèmes très complexes (géométrie de la basilique de Saint-Quentin) peuvent
être simulés facilement.

• L’estimation d’une accélération sismique maximale simulée de manière quasi-statique est faisable
pour une structure réelle. Pour la coupe de l’église Santa Maria del Borgo une valeur seuil
d’accélération sismique est évaluée, bien que conservative. L’utilité de simulation des phénomènes
dynamiques de manière quasi-statique avec la méthode proposée pour les structures réelles est que
l’on peut s’affranchir de tout besoin d’analyses temporelles si cette valeur seuil d’accélération est
supérieure au risque sismique dans la région où se situe la structure examinée.

• Grâce au contrôle paramétrique du modèle géométrique et à la logique de base de la réalisation de
calculs, la mise en œuvre d’études paramétriques de typologie architecturale sont possibles. Ces
études peuvent servir à une description du comportement d’un élément d’un système structural par
rapport aux changements de la géométrie des autres éléments. L’évolution des états d’équilibre d’un
système structural en fonction du changement de la géométrie de ses éléments constitutifs peut être
exprimée au moyen du domaine d’équilibre. Aussi, les études paramétriques fournis par l’outil
peuvent aboutir à une définition de l’épaisseur minimale d’un arc en fonction de son rapport ogival
pour une considération de l’arc dans un système structural donné. Ainsi, l’outil de calcul de stabilité
de structures maçonnées proposé dans cette thèse peut constituer un outil performant aux mains
des historiens de la construction.

• Le Calcul à la Rupture ne peut pas renseigner sur les déformations de la structure car on n’introduit
pas de loi de comportement pour le matériau. Cependant, dans ce chapitre on a montré la possibilité

<!-- p. 214 -->

3.4 Conclusion du Chapitre 3 191

d’utiliser comme donnée d’entrée une géométrie déformée afin d’estimer avec une procédure
itérative la déformation ultime avant la rupture de la structure. Cette possibilité est très utile pour une
analyse qui vise à la réhabilitation des maçonneries. Les structures maçonnées, disposant d’un
comportement ductile à l’échelle globale, présentent souvent des déformations importantes et une
analyse de la stabilité du nouvel état d’équilibre est nécessaire. On note que l’estimation de la
déformation ultime du système a été faite sans considérer les fissures mais en considérant le
matériau consolidé et continu. Cependant, l’utilisation de l’approche statique par l’intérieur conduit à
une estimation conservative des déformations ultimes. Une comparaison avec les résultats de
l’approche cinématique du Calcul à la Rupture est envisagée dans les perspectives de cette thèse
(la comparaison peut être réalisée avec les résultats fournis par Ochsendorf (2002) pour un système
structural d’un arc en plein cintre supporté par deux contreforts).

• Les analyses effectuées montrent que le nombre de paramètres nécessaires pour la définition du
domaine de stabilité augmente avec la complexité du système. Par exemple, dans le cas d’analyse
de la coupe de la cathédrale d’Amiens et de la basilique de Saint-Quentin, on devrait définir le
domaine de stabilité dans l‘espace tridimensionnel. Afin de déterminer les combinaisons des
poussées des éléments qui correspondent à un état stable du système, la première prédiction de
poussée introduite dans les calculs concerne l’arc central de chaque système structural. On adopte
cet ordre en supposant qu’il y a un rôle prédominant de la poussée de l’arc central et que le rôle des
autres éléments est de contrebuter cette poussée afin d’atteindre la hauteur et l’écartement définis
par la géométrie de l’arc central. Finalement, les déformations potentielles de la structure peuvent
donner des indications sur l’état (passif ou actif) d’un élément, et diminuer les paramètres à préciser,
comme dans le cas des déformations des arcs de la basilique de Saint-Quentin.

<!-- p. 215 -->

192

<!-- p. 216 -->

Chapitre 4

Conclusion générale et Perspectives

4.1 Conclusion

L’objectif de cette thèse a été de contribuer à l’étude de la stabilité des structures maçonnées
anciennes au moyen d’une mise en œuvre numérique de l’approche statique par l’intérieur du Calcul à la
Rupture. Plus précisément, nous avons développé un outil d’évaluation de la stabilité des systèmes
structuraux maçonnés à travers les notions de ligne de pression et de domaine d’équilibre d’une structure.
Un des nos objectifs majeurs était de préserver la généralité et la simplicité maximale possible afin que la
méthodologie et les résultats produits par cet outil soient compréhensibles par des utilisateurs travaillant dans
diverses disciplines. Les systèmes structuraux, que l’outil permet de traiter, combinent plusieurs éléments
(arcs, arcs-boutants, éléments verticaux) de façons variables et ils peuvent être soumis à des chargements
statiques ou quasi-statiques sismiques.

Les recherches scientifiques contemporaines concernent principalement l’étude d’éléments
structuraux examinés seuls. En revanche, notre but a été de travailler sur les systèmes structuraux complexes
en maçonnerie, d’évaluer leur stabilité ainsi que de mettre en évidence l’effet de chaque élément sur la
stabilité globale de ces systèmes. En utilisant le théorème statique du Calcul à la Rupture, la stabilité de
chaque élément du système structural peut être évaluée indépendamment de la structure et deux états
extrêmes d’équilibre (passif-actif) peuvent être définis en rapport avec la poussée exercée aux extrémités de
l’élément. Suivant une procédure itérative, nous avons redéfini ces états extrêmes des éléments du système
afin que la stabilité du système entier soit possible. Autrement dit, on a cherché à définir les combinaisons des
poussées admissibles des éléments de manière à obtenir un domaine des poussées admissibles pour la
stabilité du système entier, appelé domaine d’équilibre du système. La vérification de la stabilité est faite en
traçant la ligne de pression du système entier qui doit rester dans les contours définis pas la géométrie de la
structure. L’adoption des coefficients relatifs à la traction et au glissement est proposée. Il s’agit des

193

<!-- p. 217 -->

194 4 Conclusion générale et perspectives

coefficients géométriques qui se basent sur l’emplacement de la ligne de pression relativement à la géométrie
du système structural et la stéréotomie des voussoirs de la maçonnerie. Pour le calcul de la ligne de pression,
on a utilisé la méthode du réseau de forces proposée par O’Dwyer (1999). En parallèle, on a développé une
méthode pour étudier la stabilité du bloc de la jonction de différents éléments structuraux en le traitant comme
matériau sans traction. Le tracé de la ligne de pression du système entier pour les poussées extrêmes des
éléments constitutifs de la structure permet la détermination du domaine d’équilibre du système et met en
évidence les cas de stabilité potentielle d’une structure maçonnée.

L’approche adoptée se rapproche de la statique graphique notamment quand elle est combinée à la
géométrie dynamique (par exemple, Block et al. 2006a). Les deux méthodes présentent l’avantage de
représenter graphiquement les résultats de l’analyse sous forme de lignes de pression ce qui permet un usage
adapté à des utilisateurs non-spécialistes. La statique graphique préserve une interprétation vectoriellegraphique des forces au moyen du polygone de forces. De ce fait, elle peut être considérée plus naturelle et
intuitive par un ensemble d’utilisateurs varié.

Figure 4.1 – A gauche : Statique graphique appliquée à l’étude de stabilité des systèmes structuraux (Chapelle du
Saint-Paul à l’université de Columbia, extrait par Goodyear, 1906)

– A droite : Résultats graphiques de l’approche numérique proposée pour l’étude de stabilité des systèmes
structuraux (Basilique de Saint-Quentin, cf. paragraphe 3.3)

<!-- p. 218 -->

4 Conclusion générale et Perspectives 195

Cependant, les constructions graphiques deviennent très compliquées et difficiles à réaliser dans le
cas des systèmes structuraux complexes (Figure 4.1 gauche). Le risque de manquer de précision est
important et une automatisation des tracés devient nécessaire pour l’étude de typologies complexes. Notre
approche numérique, qui se base sur l’étude de l’équilibre des forces des systèmes structuraux au moyen
d’un réseau de forces, présente le double avantage d’une représentation graphique des résultats et d’une
mise en ouvre des calculs de manière automatisée (Figure 4.1 droite).

La procédure développée dans cette thèse pour l’étude de la stabilité des systèmes maçonnés est
systématisée sous la forme d’un outil qui peut servir pour l’étude des systèmes de diverses typologies
comprenant les éléments typiques de l’architecture médiévale combinés de façon variable. En adoptant un
critère de résistance général pour le matériau, le champ d’application de l’outil s’étend à un grand nombre de
structures. Ainsi, l’outil développé dans cette thèse se caractérise par une grande flexibilité d’application et
offre une première évaluation de la stabilité de la structure qui peut guider ou compléter des analyses
mécaniques plus avancées. L’outil a servi à développer les points suivants.

• Nous avons montré que le couplage du logiciel OGIVES de restitution architecturale de l’ARIAM avec
un outil de calcul de stabilité est réalisable. L’outil présenté dans cette thèse permet de compléter les
sorties du logiciel de restitution avec une évaluation de la stabilité de la structure, effectuée aux
sections verticales du modèle tridimensionnel.

• De plus, l’outil développé grâce à sa simplicité et sa généralité permet la mise en œuvre d’études
paramétriques, qui sont difficilement envisageables avec des méthodes d’analyse mécanique plus
sophistiquées. Les études paramétriques effectuées dans cette thèse ont considéré : a. le
chargement, b. la typologie architecturale et c. les déformations des systèmes structuraux.

a. Un chargement horizontal d’intensité variable a été appliqué aux systèmes structuraux afin
d’évaluer de manière quasi-statique l’accélération horizontale maximale sismique. Cette valeur
d’accélération est indicative sur la nécessité ou non de la mise en œuvre d’une analyse temporelle.

b. L’effet de la typologie architecturale des éléments d’un système structural a été étudié. L’évolution
des états d’équilibre d’un système structural a été définie en fonction du changement de la géométrie
de ses éléments constitutifs. En plus, les géométries limites des éléments constitutifs sont définies en
tenant en compte de l’équilibre du système structural global.

c. La stabilité d’un système structural a été évaluée pour des géométries déformées par incrément
afin de déterminer une estimation par défaut de la déformation ultime avant la rupture, sans
considérer les fissures mais en considérant le matériau consolidé et continu.

<!-- p. 219 -->

196 4 Conclusion générale et perspectives

Par ailleurs, on peut envisager des applications de l’outil proposé aux domaines suivants.

• Dans le domaine de l’histoire de la construction, l’outil proposé pourrait servir à une simulation des
phases potentiellement suivies pendant la construction d’une structure maçonnée. Dans l’outil
l’adjonction et la suppression des éléments structuraux sont facilement réalisées, ce qui rend possible
l’identification des états successifs d’équilibre pendant la durée de la construction. Par exemple, une
application de l’outil peut être envisagée vis-à-vis des travaux de Huerta et al. (2006) considérant le
processus de construction de la cathédrale de Ségovie.

• Dans le domaine de l’enseignement, le comportement mécanique d’une structure, réalisée avec un
matériau sans traction, peut être illustré au moyen de la ligne de pression. Le phénomène de
contrebutement des éléments ainsi que l’influence de l’application des charges autres que le poids
propre peuvent être explorés.

Cependant, il est inévitable que la grande généralité d’application, soit accompagnée de certaines
limitations d’utilisation ou d’interprétation des résultats fournis par l’outil. L’outil de calcul proposé fournit une
évaluation préliminaire de la stabilité des systèmes maçonnées qui peut être facilement réalisée pour des
structures réelles. Cependant, les résultats acquis n’ont pas de sens définitif pour la stabilité de la structure
(compte tenu du manque de définition des lois de comportement du matériau et des caractéristiques des
dispositions constructives) mais servent plutôt pour une compréhension du comportement mécanique de la
structure à son échelle globale. Les résultats fournis par cette approche peuvent indiquer les points importants
du comportement mécanique des structures maçonnées ainsi que la nécessité d’une étude plus sophistiquée.

<!-- p. 220 -->

4 Conclusion générale et Perspectives 197

4.2 Perspectives

a. Comparaison des résultats avec l’approche cinématique du Calcul à la

Rupture

L’approche statique du Calcul à la Rupture est considérée plus pertinente pour l’étude des systèmes
structuraux complexes étant donné que l’approche cinématique, nécessitant la définition des mécanismes de
rupture, devient difficile à mettre en œuvre pour l’étude des cas complexes. On peut toutefois envisager de
coupler les deux approches du Calcul à la Rupture dans l’étude des deux cas suivants.

Premièrement, on envisage la mise en œuvre de l’approche cinématique pour le système structural
constitué par un arc et deux arcs-boutants. Une comparaison des résultats de l’approche statique du Calcul à
la Rupture pour ce système a été réalisée avec la méthode aux éléments finis (cf. paragraphe 2.4.1) mais la
comparaison avec l’approche cinématique du Calcul à la Rupture sera plus pertinente et donnera une
estimation par excès du domaine d’équilibre du système. Les régions susceptibles de formation de rotules
calculées par l’outil peuvent définir les mécanismes de rupture pour la mise en œuvre de l’approche
cinématique. Ainsi, quatre mécanismes de rupture peuvent être étudiés suivant les quatre combinaisons des
poussées extrêmes de l’arc et de l’arc boutant (cf. paragraphe 2.3.1.1d).

Deuxièmement, une mise en œuvre de l’approche cinématique du Calcul à la Rupture est envisagée
pour comparer les déformations du système structural d’un arc ogival supporté par deux contreforts qui sont
estimées avec l’outil proposé (basilique de Saint-Quentin, cf. paragraphe 3.3.2).

b. Intégration de l’outil aux logiciels de restitution architecturale

Le développement de l’outil proposé dans cette thèse a été basé sur une décomposition du système
structural en plusieurs éléments autonomes avant d’étudier la stabilité de l’ensemble. Parmi les différents
logiciels de modélisation architecturale, certains effectuent cette décomposition en formes plus élémentaires
et proposent une classification des différentes typologies structurales. Suivant cet esprit, dans le logiciel de
restitution de l’ARIAM, l’édifice est restitué à partir des éléments structuraux autonomes (piles, voûtains,
formerets, doubleaux, arcs ogivaux etc.) qui constituent les « classes » dans le contexte de type de
programmation orientée objet (le logiciel utilise le langage C++). Les calculs de stabilité effectués dans cette
thèse sont réalisés au moyen d’un logiciel de programmation mathématique (logiciel SCILAB). Une
transcription des algorithmes de l’outil de calcul de stabilité peut être envisagée dans le langage C++ ce qui
permettra de coupler l’outil développé avec le logiciel de restitution de l’ARIAM. Un autre objectif est de créer
une interface entre les deux logiciels avec l’intermédiaire d’une feuille de calcul (par exemple, MsEXCEL) qui

<!-- p. 221 -->

198 4 Conclusion générale et perspectives

fournira les données du chargement extérieur et la géométrie des éléments du système. La même perspective
peut être envisagée pour le couplage de l’outil de calcul avec d’autres logiciels de modélisation géométrique
pourvu qu’ils fournissent une définition de la géométrie de chaque élément.

c. Evolution de l’outil vers un guide technique de restauration

La restauration d’une structure historique apparaît clairement comme un domaine de travail complexe

mettant en jeux de nombreuses disciplines : l’Architecture, la Mécanique, mais aussi les sciences de

l’Archéologie du bâti et l’Histoire de la Construction. Une autre perspective de cet outil peut être envisagée

vers le développement d’un guide pour les techniques de restauration. Dans ce cas, les méthodes

habituellement adoptées pour le renforcement des structures maçonnées peuvent être incorporées dans la

modélisation. Par exemple, la simulation de la mise en place des tirants métalliques nécessitera l’ajout de

deux paramètres supplémentaires : la valeur de la poussée exercée par le tirant ainsi que son point

d’application. De plus, l’adoption d’un critère de résistance plus détaillé pour la maçonnerie peut être

nécessaire. Par exemple, pour la simulation de la mise en place des armatures métalliques on doit considérer

une capacité du matériau de résister à la traction (dans ce cas la ligne de pression pourrait sortir du contour

de la structure). Finalement, on peut envisager la prise en compte d’une résistance en compression affaiblie

(et par conséquence non infinie) pour les régions endommagées.

d. Extension de l’outil à l’exploration des nouvelles formes en équilibre avec

des matériaux sans traction

Dans cette thèse, l’outil de calcul de stabilité des structures maçonnées a été utilisé pour la simulation
des systèmes structuraux correspondant à l’architecture médiévale. Les capacités de modélisation
géométrique concernent des éléments qui entraînent une force de poussée et correspondent aux éléments
plutôt de l’architecture gothique tels que les arcs et les arcs-boutants. En remarquant que la méthode du
réseau de forces correspond aux expériences des funiculaires de Gaudi (Huerta, 2006), on peut aussi
envisager l’application de l’outil à l’exploration de nouvelles formes en équilibre. Ces formes peuvent être
réalisées dans un matériau sans traction (par exemple en maçonnerie ou en bêton non-armé).

A titre d’exemple, dans la Figure 4.2 et la Figure 4.3, on présente la logique de base pour la déduction
d’une forme à partir de la stabilité d’une autre. Pour l’arc A1D1D2A2 on définira deux systèmes structuraux
potentiellement stables (pour tous les calculs l’arc sera considéré à son état passif, H1 = minHarc). Le
système structural de départ est constitué de l’arc A1D1D2A2 supporté par deux contreforts E1A1K1M1 et
E2A2K2M2 (Figure 4.2a). Pour la déduction du deuxième système structural (Figure 4.2b) on pose la

<!-- p. 222 -->

4 Conclusion générale et Perspectives 199

contrainte de garder la même abscisse de la ligne de pression au niveau des appuis de la structure (points M1
et M2). Avec une procédure itérative, on déduit une forme inclinée et plus fine, correspondant aux piliers
A1B1M1N1 et A2B2M2N2 qui supportent l’arc horizontalement aux extrémités gauche A1B1 et droite B2A2.

Figure 4.2 – Explorations de nouvelles formes en équilibre : a. Arc supporté par deux contreforts

b. Arc supporté sur deux piliers inclinés

Deuxièmement, on vise à remplacer le pilier droit A2B2M2N2 en imposant la contrainte d’avoir un
élément avec la même inclinaison et la même épaisseur avec le pilier gauche A1B1M1N1 (Figure 4.3). On
produit la forme du pilier A2B2ST et afin de stabiliser le système on ajoute un élément supplémentaire
A2PFI, qui entraîne une poussée H2 (l’élément se trouve à un équilibre limite et stable uniquement sous la
poussée H2).

<!-- p. 223 -->

200 4 Conclusion générale et perspectives

Figure 4.3 – Explorations de nouvelles formes en équilibre : Replacement du pilier droit par un pilier symétrique et un

élément supplémentaire

On voit qu’en changeant les contraintes de base de la déduction des formes, on pourrait explorer un
grand nombre de nouveaux systèmes structuraux en équilibre. Il est intéressant de noter que les formes
architecturales produites par un outil de calcul de stabilité présente l’avantage qu’elles seront renseignées du
point de vue structural, étant stables sous condition qu’elles soient réalisées avec un matériau sans traction.

e. Extension de l’outil aux structures tridimensionnelles

Les structures maçonnées correspondants à l’architecture gothique constituent le cas le plus pertinent

pour les calculs effectués avec l’outil proposé dans cette thèse. Le cas des structures longitudinales est aussi

pertinent (par exemple, systèmes avec voûtes en berceau). La typologie des structures byzantines, par

exemple, constitue un cas où les études tridimensionnelles deviennent plus pertinentes puisque ces structures

mettent en évidence des phénomènes hors plan plus significatifs que dans les cas traités ici. Par rapport aux

problèmes tridimensionnels, l’approche statique du Calcul à la Rupture se concrétise au moyen d’une surface

de pression définissant un domaine des contraintes compressives dans la structure. Dans un effort de créer

cette surface pour une coupole (Figure 4.4) avec la méthode proposée par O’Dwyer (1999), on a noté une

augmentation très importante des paramètres à déterminer. Dans le cas de l’arc, un seul paramètre de

chargement est suffisant pour une représentation de son état des forces : la force horizontale aux appuis.
Dans le cas de la coupole, au contraire, on doit déterminer les forces horizontales aux appuis Hr,i ainsi que les
forces circonférentielles Hcir,i dont le nombre est défini par le maillage considéré.

<!-- p. 224 -->

4 Conclusion générale et Perspectives 201

Figure 4.4 – Surface de pression d’une coupole en fonction des forces de réaction Hr,i et

des forces circonférentielles Hcir,i

Block et al. (2007) ont procédé à une limitation de ces paramètres pour le cas d’une voûte en utilisant
les propriétés de la théorie de dualité. Le développement d’une méthode de calcul de stabilité des systèmes
structuraux comprenant plusieurs éléments tridimensionnels est un problème très complexe surtout au niveau
d’interaction entre éléments différents. Les conclusions tirées par le problème bidimensionnel dans cette thèse
peuvent constituer la base des développements du problème tridimensionnel ce qui ouvre un champ de
développement important.

<!-- p. 225 -->

202

<!-- p. 226 -->

Références bibliographiques

ACARY, V. (2001) - Contribution à la modélisation mécanique et numérique des édifices
maçonnés. Thèse de doctorat, Ecole supérieure de mécanique de Marseille.

ALBY, E. (2006) - Elaboration d’une méthodologie de relevé d’objets architecturaux :
contribution basée sur la combinaison de techniques d’acquisition. Thèse de doctoral, Université
Henri Poincaré, Nancy-1.

ANTOINE, E. (1995) – Derivation of in-plane elastic characteristics of masonry through
homogenisation theory. International Journal of Solids and Structures, vol. 32, no 2, pp. 137-163.

ARMAND, G., BOULON, M., JAY, J.C., PAPADOPOULOS, C., PICAUD, C., REVEILLET,
M., REY, B., VERDUS, J. F. (1997) - Monuments under seismic action. Task 3 – Interface
Properties EV5V-CT93-0300, Laboratoire Sols Solides Structures HMG INPG CNRS, Grenoble,
France.

ATKINSON, R. H., AMADEI B.P., SAEB, S., STURE, S. (1989) - Response of masonry bed
joints in direct shear. Journal of Structural Engineering, A.S.C.E., vol. 115, no 9, pp. 2276-2296.

BALLETTI, C., GUERRA, F., VERNIER, P., STUDNICKA, N., RIEGL, J., ORLANDINI, S.
(2004) - Practical comparative of an integrated hybrid sensor based on photogrammetry and laser
scanning for architectural representation. Proceedings XXth congress of the International Society
of Photogrammetry and Remote Sensing, Constantinople, Turkey.

BENVENUTO, E. (1991) - An introduction to the History of Structural Mechanics, V.2. Vaulted
structures and elastic systems. Springer – Verlag, New York.

BLOCK, P., OCHSENDORF, J. (2007) - Thrust network analysis: A new methodology for three
dimensional equilibrium. Journal of International Association for Shell and Spatial Structures,
vol. 48, no 3, p.167-173.

BLOCK, P., CIBLAC, T., OCHSENDORF, J. A. (2006a) - Real-time limit analysis of vaulted
masonry buildings. Computers and Structures, vol. 84, pp.1841-1852.

BLOCK, P., DEJONG, M., OCHSENDORF, J. (2006b) - As Hangs the Flexible Line:
Equilibrium of Masonry Arches. The Nexus Network Journal, vol. 8, no 2, pp 13-24.

203

<!-- p. 227 -->

204 Références bibliographiques

BOEHLER, W., BORDAS, V., MARBS, A. (2003) - Investigating Laser Scanner Accuracy,
Proceedings of the International Archives of Photogrammetry, Remote Sensing and Spatial
Information Sciences, vol. XXXIV, Part 5/C15, pp. 696-701, Antalya, Turkey.

BOEHLER, W., HEINZ, G., MARBS, A., SIEBOLD, M. (2002) - 3D Scanning Software : an
introduction. Proceedings of the CIPA WG 6 International Workshop on Scanning for Cultural
Heritage Recording, Corfu, Greece.

BOOTHBY, T. (1994) – Stability of masonry piers and arches including sliding. Journal of
Engineering Mechanics, vol. 120, no 2.

BOOTHBY, T., ATAMTURKTUR, S. (2007a) – A guide for the finite element analysis of
historic load bearing masonry structures. Proceedings of 10th North American Masonry
Conference, St. Louis, Missouri, USA.

BOOTHBY, T., ATAMTURKTUR, S., OCHSENDORF, J., TALLON, A., MURRAY, S. (2007b)
\- Structural Modeling of the Vaults of St. Julien in Couleuvre, France. Proceedings of 10th North
American Masonry Conference, St. Louis, Missouri, USA.

BRANDONISIO, G., DE LUCA, A. , MELE, E. (2009) - Horizontal capacity of masonry portal
frames. Proceedings of the International Conference on Protection of historical Building,
PROHITECH 09, Federico Mazzolani, vol. 2, pp. 1121-1126.

BREYMANN, G.-A. (1849) - Bau-Constructions-Lehre. vol. 1: Constructionen in Stein, Stuttgart.

BURRY, J. R., BURRY, M. C. (2006) - Gaudi and CAD. ITcon, Special Issue The Effects of CAD
on Building Form and Design Quality, vol. 11, pp. 437-446.
disponible sur: http://www.itcon.org/2006/32

BURRY, M., BURRY, J., FAULÍ, J. (2001) - Sagrada Família Rosassa: Global Computeraided
Dialogue between Designer and Craftsperson (Overcoming Differences in Age, Time and
Distance). Proceedings of the Twenty First Annual Conference of the Association for ComputerAided Design in Architecture, pp. 076-086, Buffalo, New York.

BURRY, M. C., MURRAY, Z. (1997) – Computer aided architectural design using parametric
variation and associative geometry. Proceedings of the 15th eCAADe conference, Vienne.

CASSINELLO, P. (2008) - Mechanics and construction of medieval columns. System against
earthquakes of Spanish gothic cathedrals. La colonne. Nouvelle histoire de la construction, Presse
polytechniques et universitaires romandes, pp. 61-71.

CASTIGLIANO, A. (1879) - Théorie de l’équilibre des systèmes élastiques et ses applications.
Turin.

CHASSAGNOUX, A., GUÉNA, F., MAILLE, M., UNTERSTELLER, L.-P. (1998) -
Modelisation and calculation of gothic or ogive vaults. Proceedings of the First european
congress on restoration of gothic cathedrals, Europa Congress Hall, Vitoria - Gasteiz.

<!-- p. 228 -->

Références bibliographiques 205

CHASSAGNOUX, A., GUENA, F., UNTERSTELLER L.-P., (2000) - Simulation du
comportement des voûtes d’ogives gothiques, Rapport final de recherche, Contrat n°97 5620 017,
Ministère de la culture, direction du patrimoine.

CIBLAC, T., GUENA, F., UNTERSTELLER, L.-P. (2005) - De l’esquisse d’architecture à main
levée au modèle numérique. Actes SCAN’05 (Séminaire de conception architecturale numérique),
Paris.

CIBLAC, T., OIKONOMOPOULOU, A., GUENA, F. (2008) - Approches numériques pour
l'étude du comportement des structures maçonnées anciennes, Congrès d'histoire de la
construction, Paris.

COSTE, A. (1997) - L’architecture gothique. Lectures et interprétations d’un modèle. Centre
d’études Foréziennes, Publication de l’université de Saint-Etienne.

COULOMB, C. A. (1773) - Essai sur une application des règles de maximis et minimis a quelques
problèmes de statique, relatifs à l’architecture. Mémoires de Mathématique et de Physique
présentés à l’Académie Royale des Science par Divers Savans et lus dans ses Assemblées, vol. 7,
pp. 343-382, Paris.

COUPLET, P. (1729, 1730) - De la poussée des voûtes. Histoire de l’Académie Royale des
Sciences, Paris (1731, 1732).

CULMANN, K. (1866) - Die graphische Statik. Meyer und Zeller, Zürich.

DE BUHAN, P., DE FELICE, G. (1997) – A homogenisation approach to ultimate strength of
brick masonry. Journal of Mechanics and Physics of Solids, vol. 45, no 7, pp. 1085-1104.

DE LUCA, A. , SANTANIELLO, R., GIORDANO, A., MELE, E. (2009) - Non linear FEM and
limit analysis of masonry structures in religious heritage constructions. Proceedings of the
International Conference on the Protection of historical Building, PROHITECH 09, Federico
Mazzolani, vol. 1, pp.15-24.

DE LUCA, L. (2006) - Relevé et multi-représentations du patrimoine architectural – Définition
d’une approche hybride de reconstruction 3D d’édifices. Thèse de doctorat, Ecole Nationale
Supérieure des Arts et Métiers, Aix-en–Provence.

DE LORENZIS, L., DEJONG, M., OCHSENDORF J., (2007) - Failure of masonry arches under
impulse base motion. Earthquake engineering and structural dynamics, vol. 36, pp. 2219-2136.

DELBECQ (1982) – Les ponts en maçonnerie. Evaluation de la stabilité. Ministère des
Transports, Direction des routes, SETRA.

DELLAS, G. (1993) - Les églises en voûtes ogivaux de la ville médiévale à Rhodes. Proceedings
of the International Congres : Rhodes 2400 ans. La ville de Rhodes à partir de sa fondation
jusqu’à l’occupation de Turcs (1523), Athènes.
(en grec : Ντέλλας, Γ (1993) - Οι Σταυροθολιακές εκκλησίες της μεσαιωνικής πόλης της Ρόδου.
Πρακτικα Διεθνούς Επιστημονικού Συνεδρίου: Ρόδος 2400 χρόνια, Η πόλη της Ρόδου από την
ίδρυση της μέχρι την κατάληψη από τους Τούρκους (1523), Αθήνα.)

<!-- p. 229 -->

206 Références bibliographiques

DOSCH, Ph., TOMBRE, K., AH-SOON, C., MASINI, G. (2000) - A complete system for the
analysis of architectural drawings. International Journal on Documents Analysis and Recognition,
vol. 3, no 2, pp.102-116.

DUPUIT, J. (1870) - Traité de l’équilibre des voûtes et de la construction des ponts en
maçonnerie. Dunod, Paris.

FOURNIE, V., (1864) - Traité de la stabilité des constructions. Première partie : théorie des
voûtes et des murs de soutènement. Dunod, Paris.

FUCHS, A. (2006) - Outils numériques pour le relevé architectural et la restitution
archéologique. Thèse de doctorat, Université Henri Poincaré, Nancy-1.

GERE, J.M., TIMOSHENKO, S.P. (1990) - Mechanics of materials. PWS-KENT Publishing
Company, 3rd edition, Boston, Massachusetts.

GERSTNER, F. J. (1831) - Handbuch der Mechanik. vol. 1, p. 405, Prague.

GIAMBANCO, G., DI GATI, L. - (1997) A cohesive interface model for the structural mechanics
of block masonry. Mechanics Research Communications, vol. 24, no 5, pp. 503-512.

GODART, B., TIVERON, M., DUVAL, D. (1996) - Modélisation de la cathédrale de Strasbourg
à l'aide du code de calcul aux éléments finis CESAR-LCPC - Etude de l'influence de mouvements
d'appuis sur le comportement d'une partie de l'édifice. Bulletin de liaison des LPC, no 206, pp. 4162.

GOODYEAR, W.H. (1906) – The Columbia University Chapel. Brickbuilder, vol. 15.

GRUSSENMEYER, P. (2003) - Photogrammétrie architecturale et modélisation 3D du
patrimoine. Revue de l’Association Française de Topographie XYZ , no 95, pp. 30-36.

GUÉNA, F. (2005) - Assisting 3D Modeling from Documents. Proceedings of the 23rd
Conference on Education in Computer Aided Architectural Design in Europe, Lisbon.

HALPHEN, B., NGUYEN, Q., S. (1975) – Sur les matériaux standards généralisés. Journal de
Mécanique, vol. 14, no 1, pp. 39 – 63.

HEYMAN, J. (1966) - The stone skeleton. International Journal of Solids and Structures, vol. 2,
pp. 249-279.

HEYMAN, J. (1969) - The safety of masonry arches. Int. J. Mech. Sci., 11.

HEYMAN, J., (1992) - Leaning towers. Meccanica, vol. 27, pp. 153-159.

HEYMAN, J. (1995) - The stone skeleton: Structural engineering of masonry architecture.
Cambridge University Press.

HEYMAN, J. (1998) – Structural analysis: a historical approach. Cambridge University Press.

<!-- p. 230 -->

Références bibliographiques 207

HEYMAN, J. (1999) – The science of structural engineering. Imperial College Press, London.

HEYMAN, J. (2008) - Gothic piers and columns. La colonne. Nouvelle histoire de la construction,
Presse polytechniques et universitaires romandes, pp. 55-59.

HEYMAN, J. (2009) - La coupe des pierres. Proceedings of International Congress on
Construction History, vol. 2, pp. 807-812.

HUERTA, S. (2001) - Mechanics of masonry vaults: The equilibrium approach. Proceedings of
Historical Constructions, Lourenco, Roca, Guimarães.

HUERTA, S. (2005) – The use of simple models in the teaching of the essentials of masonry arch
behaviour. Theory and Practice of constructions: knowledge, means, models, Ravenna, pp.747761.
disponible sur: http://www.ad.upm.es

HUERTA, S. (2006) – The Structural Design in the Work of Gaudi. Architectural Science Review,
vol. 49, no 4, pp. 324-339.

HUERTA, S., Ruiz, A. (2006) – Some notes on gothic building processes: the expertises of
Segovia Cathedral. Proceedings of the Second International Congress on History Construction,
London.

HUERTA, S. (2008) – The Analysis of Masonry Architecture: A Historical Approach.
Architectural Science Review, vol. 51, no 4, pp. 297-328.

HUERTA, S. (2009) - The debate about the structural behaviour of gothic vaults. Proceedings of
the International Congress on Construction History, vol. 2, pp. 800-806.

HUERTA, S., LÓPEZ, M. (1997) - Stability and consolidation of an ashlar barrel vault with great
deformations: the church of Guimarei. Structural studies, repairs and maintenance of historical
buildings, Computational Mechanics Publications, pp. 587-596, Southampton, Reino Unido.

HOOKE, R. (1675) – A description of helioscopes, and some other instruments. London.

KERYVIN, V. (1999) - Contribution à la modélisation de l’endommagement localisé. Thèse de
doctorat, Université de Poitiers.

KRAUS, K., WALDHAUL, P. (1997) - Manuel de photogrammétrie : principes et procédés
fondamentaux. Hermes.

KURRER, K.-E. (2008) - The history of the theory of structures, From arch analysis to
computational mechanics. Ernst & Sohn Verlag Architektur und technische, Berlin.

LA MENDOLA, L., PAPIA, M., (1993) - Stability of masonry piers under their own weight and
eccentric load. Journal of Structural Engineering, vol. 119, no 6, pp. 1678-1693.

<!-- p. 231 -->

208 Références bibliographiques

LAUG, P. (2006) - Contribution à la génération automatique de maillages de qualité pour la
simulation numérique. Mémoire pour habilitation à diriger des recherches, Université Pierre et
Marie Curie, Paris VI.

LAURENT, J.- M. (2007) - Construction et restauration des bâtiments en pierre. Histoire,
technique, pratique, Editions Vial.

LEMAITRE, J., CHABOCHE, J. L. (1988) - Mécanique des matériaux solides. Dunod, 2éme
édition, Paris.

LEMAITRE, J., DESMORAT, R. (2005) - Engineering damage mechanics: Ductile, Creep,
Fatigue and Brittle Failures. Spinger Verlag, pp.395.

LEMOS, J. V. (2007) - Discrete element modelling of masonry structures. International Journal
of Architectural Heritage, vol. 1, pp. 190-213.

LUCCHESI, M., PADOVANI C., PASQUINELLI, G., ZANI, N. (2008) - Masonry
Constructions: Mechanical Models and Numerical Applications. Springer Verlag, Berlin
Heidelberg.

LOFTI, H.R., SHING, P.B. (1991) - An appraisal of smeaked crack models for masonry shear
wall analysis. Computers and Structures, vol. 41, no 3, pp.413-425.

LOURENÇO, P.-B., ROTS, J. G. (1997) – Multisurface interface model for analysis of masonry
structures. Journal of engineering mechanics, vol. 123, no 7, pp. 660-668.

MAHER, A. M., M. BURRY, M. (2002) - Hybridized Measurement: Interpreting historical
Images of Sagrada Familia Church in Barcelona using CAD-based digital photogrammetry.
ECAADE 20, Warsaw.

MAKRODIMOPOULOS, A., MARTIN, C.M. (2006) - Lower bound limit analysis of cohesivefrictional materials using second-order cone programming. International Journal for Numerical
Methods in Engineering, vol. 66, no. 4, pp. 604-634.

MARBS, A., HEINZ, G., BOEHLER, W. (2001) - The potential of non-contact close range laser
scanners for cultural heritage recording. Proceedings of the CIPA International Symposium,
Potsdam, Germany.

MERY, E. (1840) - Sur l’équilibre des voûtes en berceau. Annales des Ponts et Chaussées.

MILANKOVITCH, M. (1907) - Theorie der Druckkurven. Zeitscrift fur Mathematik und Physik,
vol. 55, pp. 1-27.

Ministère de la Culture de Grèce, Département des monuments byzantins et post-byzantins (2007)
\- Catalogue of the exhibition Mediterranean Gothic Architecture. Athènes.

MOREAU, J. J., PANAGIOTOPOULOS, P. D. (1998) – Nonsmooth mechanics and applications.
CISM, Courses and lectures, vol. 302, Springer Verlag.

<!-- p. 232 -->

Références bibliographiques 209

MOROPOULOU, A., BAKOLAS, A, BISBIKOU, K. (2000a) - Investigation of the technology of
historic mortar. Journal of Cultural Heritage, vol. 1, pp. 45-58.

MOROPOULOU, A., BAKOLAS, A., BISBIKOU, K. (2000b) - Physicochemical adhesion and
cohesion bonds in joint mortars imparting durability to historic structures. Construction and
building materials, vol. 14, no 1, pp. 35-46.

MOROPOULOU, A., BISCONTIN, G., BAKOLAS, A., BISBIKOU, K. (1997) - Technology and
behaviour of rubble masonry mortars. Construction and building materials, vol. 10, no 2, pp. 119129.

MOSELEY, H. (1833) - On a new principle in statics, called the principle of least pressure.
Philosophical Magazine, vol. 3, pp. 285-288.

NIKOLINAKOU, K.A., TALLON, A. (2006) - New research in Early Gothic Flying Buttresses.
Proceedings of the Second International Congress in Construction History, vol. 3, pp. 2347-2361,
Cambridge.

NIKOLINAKOU, K.A., TALLON, A., OCSHENDORF, J.-A. (2005) - Structure and form of
early gothic flying buttresses. Revue européenne de génie civil, vol. 9, no 9, pp. 1191-1217.

OCHSENDORF, J. A. (2002) - Collapse of masonry structures. Thèse doctorat, University of
Cambridge.

OCHSENDORF, J. A., HERNANDO, J.-I., HEURTA, S. (2004) - Collapse of masonry buttresses.
Journal of Architectural Engineering, American Society of Civil Engineers, vol. 10, no. 3, pp. 8897.

O’DWYER, D. (1999) - Funicular analysis of masonry vaults. Computers and Structures, vol. 73,
pp. 187-197.

PAPA, E., NAPPI, A. (1997) - Numerical modeling of masonry: A material model accounting for
damage effects and plastic strains. Applied Mathematical Modelling, vol. 21, pp. 319-335.

PAPAGIANNI, I., OIKONOMOPOULOU, A. (2006) - The pathology of the structures of stone
lighthouses. Proceedings of the XIII International TICCIH Congress, Terni, Italy.

PAPANTONOPOULOS, C., PSYCHARIS, I. N., PAPASTAMATIOU, D. Y., LEMOS, J.V.,
MOUZAKIS, H. (2002) - Numerical Prediction of the Earthquake Response of Classical Columns
Using the Distinct Element Method. Earthquake Engineering and Structural Dynamics, vol. 31,
pp. 1699-1717.

PAULIN, M. (2009) – Vocabulaire illustré de la construction. Guide technique. Le Moniteur,
Paris.

PEROUSE DE MONTCLOS, J.-M. (1988) - Architecture vocabulaire – Principes d’analyse
scientifique. Imprimerie Nationale.

PIRARD, A. (1967) - La Graphique Statique. Editions Dunod, Paris.

<!-- p. 233 -->

210 Références bibliographiques

POLENI, G. (1748) - Memorie istoriche della Gran Cupola del Tempio Vaticano. Nella Stamperia
des Seminario, Padua.

PONCELET, J. V. (1852) - Examen critique et historique des principales théories ou solutions
concernant l’équilibre des voûtes. Comptes-rendus de l’Académie des Sciences, vol. 35, no 15, pp.
494-502, no 16, pp. 531-540, no 17, pp. 577-587.

POTAMIANOS, I., TURNER, J., JABI, W. (1995) - Exploring the Proportions of MiddleByzantine Churches: A Parametric Approach. Proceedings of the Sixth International Conference
on Computer-Aided Architectural Design Futures, pp. 483-493, Singapore.

PSYCHARIS, I.N., LEMOS, J.V., PAPASTAMATIOU, D.Y., ZAMBAS, C.,
PAPANTONOPOULOS C. (2003) - Numerical Study of the Seismic Behaviour of a Part of the
Parthenon Pronaos. Earthquake Engineering and Structural Dynamics, vol. 32, pp. 2063-2084.

RANKINE, W. J. M. (1858) - A manual of applied mechanics. London.

SALENÇON, J. (1983) - Calcul à la rupture et analyse limite. Presses de l’ENPC, Paris.

SALENÇON, J. (1990) - An introduction to the Yield Design Theory and its applications in Soil
Mechanics. Eur. J. Mech. A/Solids, vol. 9, no 5, pp. 477 – 500.

SALENÇON, J. (2002) - De l’élastoplasticité au calcul à la rupture. Presses de l’Ecole
Polytechnique, Palaiseau.

SALENÇON, J., HALPHEN, B. (1981) - Cours de calcul des structures anélastiques. Élastoplasticité. Presses ENPC, Paris.

SCHEFFLER, H. (1858) - Theorie der Festigkeit gegen das Zerknicken. Brunswick.

SMARS, P. (2000) - Etudes sur la stabilité des arcs et voûtes. Thèse Doctorat, Centre Raymond
Lemaire pour la Conservation, Leuven.

TIMOSHENKO, S. P. (1953) – History of the strength of materials. Mc Graw-Hill Book
Company, New York.

TOMAZEVIC, M., (1999) - Earthquake-resistant design of masonry buildings. Imperial College
Press.

TORQUATO, S., (2001) - Random Heterogeneous Materials: Microstructure and Macroscopic
Properties. Springer Verlag, New York.

VAN DE HEUVEL, F.A. (2002) – Trends in CAD-based photogrammetric measurement.
International archives of Photogrammety and Remote Sensing, vol. 33, Part 5/2, pp.852-863.

<!-- p. 234 -->

Références bibliographiques 211

VIOLLET-LE-DUC, E. (1856) - Dictionnaire raisonné de l’architecture française du XIe au XVIe
siècle. Paris.
disponible sur :
http://fr.wikisource.org/wiki/Dictionnaire_raisonn%C3%A9_de_l%27architecture_fran%C3%A7a
ise_du_XIe_au_XVIe_si%C3%A8cle

WALDHAEUSL, P., OGLEBY, C. (1994) - 3x3-Rules for simples photogrammetric
documentation of architecture. International Archives of Photogrammetry and Remote Sensing,
Volume XXX, Part B5, pp. 426-429, Melbourne.

ZAOUI, A. (2000) - Matériaux hétérogènes et composites. Cours à l'École Polytechnique,
Presses de l’Ecole polytechnique.

ZERLANTIS, M., PSAROLOGAKI, M. (1996) - Enterrements et structures d’enterrement à
l’église de Notre Dame de Bourgos de la ville médiévale de Rhodes. Proceedings of the 16eme
symposium de l’archéologie et de l’art byzantin et post-byzantin, Athènes.
(en grec : ΖΕΡΛΑΝΤΗΣ, Μ., ΨΑΡΟΛΟΓΑΚΗ, Μ. (1996) - Ταφές και ταφικές κατασκευές της
Παναγίας του Μπούργκου στην Μεσαιωνική Πόλη της Ρόδου. 16ο Συμπόσιο Βυζαντινής και
Μεταβυζαντινής Αρχαιολογίας και Τέχνης, Πρόγραμμα και Περιλήψεις Εισηγήσεων και
Ανακοινώσεων, Αθήνα.)

Sites web

• Ciblac, T., 2006:

http://www.paris-lavillette.archi.fr/simulations-evaluations/ogive.html

• CANOMA:

http://www.canoma.com/

• CABRI:

http://www.cabri.com/

• COBALT:

http://www.mediaworks.fr/?p=produit&produit_id=186

• Columbia University, Romanesque Architecture of the Bourbonnais:

http://www.mcah.columbia.edu/bourbonnais/

• http://web.mit.edu/masonry/index.html

<!-- p. 235 -->

212 Références bibliographiques

• http://www.paris-lavillette.archi.fr/uel6tr0708

• http://www.paris-lavillette.archi.fr/simulations-evaluations

• SAP2000 :

http://csiberkeley.com/products_SAP.html

<!-- p. 236 -->

Annexes

\1. Annexe au paragraphe 3.2.2

Définition de la nouvelle géométrie de l’arc du déambulatoire à cause du

déversement du pilier

Soit AB et AB΄ les parties gauches intérieures de l’arc du déambulatoire avant et après le
déversement du pilier respectivement. Il s’agit des arcs des centres O et O΄, respectivement (Figure A.1).
Etant donné que le segment AB est déplacé de dx, l’axe de symétrie de l’arc du déambulatoire (qui passe
du segment BC) est déplacé de dx/2 (parce que le point de l’extrémité de la partie droite de l’arc ne se
déplace pas, il appartient à la culée).

Figure A.1 – Déplacement et rotation de la partie droite de l’arc du déambulatoire

213

<!-- p. 237 -->

Les coordonnées du point Α΄ sont connues, D’abord, on cherche à calculer le déplacement vertical
dz du point B. Les segments AB et A΄B΄ sont égaux, alors on peut écrire :

AB = A ′B′

AC 2 + CB 2 = A ′C′ 2 + C′B′ 2
(Rint c ) 2 + (Hint c ) 2 = (dx + Rint c ) 2 + (Hint c − dz ) 2
dz 2 − 2 Hint c dz + dx 2 + 2 dxRint c = 0

On prend la plus petite racine :

dz = 2 Hint c − Hint c 2 + ( dx 2 + 2 dxRint c )

Maintenant, en connaissant les coordonnées du point B΄, on peut préciser l’inclinaison θ du
segment A΄Β΄ par rapport à l’axe Ox.

Ensuite, on calcule les coordonnées du centre O΄ de l’arc après déplacement. L’angle φ΄ est égal à
l’angle φ connu de l’arc initial.

Hint ca tan ϕ=
Rint c

Alors la hauteur Ο΄Μ΄ du triangle A΄O΄B΄ est égal à:

A ′B′
O′M ′ = sin ϕ
2

Soit (xM΄, zM΄) les coordonnées du point M΄. Les coordonnées du point O΄ (xO΄, zO΄) sont données
par les expressions suivantes :

x o′ = x M ′ + O ′M ′ sinθ
z o′ = z M ′ − O ′M ′ cosθ

On introduit une transformation des coordonnées de la partie gauche de l’arc du déambulatoire en
rapport avec le déplacement et la rotation du point O΄. La même procédure est suivie pour étudier le
changement de géométrie de la partie droite de cet arc avec la différence que son extrémité droite reste
intacte.

214

<!-- p. 238 -->


