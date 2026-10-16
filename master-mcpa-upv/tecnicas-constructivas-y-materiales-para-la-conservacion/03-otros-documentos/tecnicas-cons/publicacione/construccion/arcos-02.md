---
type: libro
title: "Étude des rapports entre stéréotomie et résistance des voûtes clavées"
author: "Mathias Fantin"
categoria: "Técnicas Constructivas y materiales para la conservación"
paginas: 471
extraccion: "texto"
fuente: "local:D:/UPV/MCPA/Asignaturas/Técnicas Constructivas y materiales para la conservación/03. Otros documentos/Técnicas constructivas/Publicaciones/Construcción/Arcos 02.pdf"
convertido: 2026-10-16
---

# Étude des rapports entre stéréotomie et résistance des voûtes clavées

> Texto extraído de `Técnicas Constructivas y materiales para la conservación\03. Otros documentos\Técnicas constructivas\Publicaciones\Construcción\Arcos 02.pdf` (471 páginas, texto). El PDF original está en el disco D: (UPV\MCPA\Asignaturas); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

Étude des rapports entre stéréotomie et résistance des
voûtes clavées
Mathias Fantin

To cite this version:

Mathias Fantin. Étude des rapports entre stéréotomie et résistance des voûtes clavées. Art et histoire
de l’art. Université Paris-Est, 2017. Français. ￿NNT : 2017PESC1077￿. ￿tel-01834617￿

HAL Id: tel-01834617

https://tel.archives-ouvertes.fr/tel-01834617

Submitted on 10 Jul 2018

HAL is a multi-disciplinary open access L’archive ouverte pluridisciplinaire HAL, est
archive for the deposit and dissemination of sci- destinée au dépôt et à la diffusion de documents
entific research documents, whether they are pub- scientifiques de niveau recherche, publiés ou non,
lished or not. The documents may come from émanant des établissements d’enseignement et de
teaching and research institutions in France or recherche français ou étrangers, des laboratoires
abroad, or from public or private research centers. publics ou privés.

<!-- p. 2 -->

THÈSE

préparée au sein du laboratoire Géométrie Structure Architecture

de l’École nationale supérieure d’architecture Paris-Malaquais

présentée pour l’obtention du diplôme de

DOCTEUR DE L’UNIVERSITÉ PARIS-EST

École doctorale : Ville, Transports et Territoires

Spécialité : Architecture

par

Mathias Fantin

intitulée

Étude des rapports entre stéréotomie et
résistance des voûtes clavées

Soutenue le mercredi 13 décembre 2017 devant le jury composé de :

Alexandre Gady, président du Jury, Université Paris-Sorbonne
Gianmarco De Felice, rapporteur, Università degli Studi Roma Tre
Jean-Claude Morel, rapporteur, Coventry University
Alain Ehrlacher, examinateur, École nationale des ponts et chaussées
Nathalie Domède, examinatrice, INSA Toulouse
Benjamin Mouton, invité, Agence Mouton ACMH
Gilbert Margueritte, invité, Margueritte SAS
Maurizio Brocato, directeur de thèse, ENSA Paris-Malaquais
Thierry Ciblac, professeur co-encadrant, ENSA Paris-Malaquais

<!-- p. 3 -->

Résumé

Cette thèse vise à mieux comprendre l’inﬂuence de la coupe des pierres sur la
résistance des arcs et des voûtes clavés en général, et des couvrements plans en particulier. L’étude historique et typologique des plates-bandes et des voûtes plates, à
travers les exemples construits et les traités d’architecture et de coupe des pierres
du xvie au xviiie siècle, forme le préalable à l’étude mécanique de ces constructions. Les plates-bandes à joints en X, les plates-bandes en fausse-coupe, et les voûtes
plates d’Abeille sont étudiées en détail en raison de leur stéréotomie savante. Les
règles géométriques utilisées pour l’appareillage des plates-bandes, d’une part par les
architectes, et d’autre part par les appareilleurs et tailleurs de pierre, émergent de ce
travail. Une extension de la méthode des réseaux de forces est proposée, pour tenir
compte de l’appareil des voûtes, pour raﬃner les réseaux, et pour intégrer rigoureusement les réseaux à la théorie du calcul à la rupture. Des stratégies de calcul pour
la recherche des chargements extrêmes, dont la détermination fonde la faisabilité de
la technique, sont proposées. Les études mécaniques conduites considèrent les arcs en
plein-cintre et dômes hémisphériques, les plates-bandes et voûtes plates, et les voûtes
hélicoïdales. Elles illustrent la précision de l’estimatif proposée pour le coeﬃcient de
sécurité géométrique, l’inﬂuence de la coupe des pierres pour les couvrements plans,
et les possibilités et limites de l’application de la méthode des réseaux de forces à
l’étude des constructions clavées.

Mots-clés : stéréotomie, coupe des pierres, pierre de taille, appareil, plate-bande,
voûte plate, stabilité, calcul à la rupture

2

<!-- p. 4 -->

Abstract

This work aims at a better understanding of the inﬂuence of stereotomy on the
stability of stone-cut archs and vaults in general, and ﬂat archs and ﬂat vaults in
particular. A study of the history and typology of ﬂat archs and ﬂat vaults, through
the consideration of existing examples and treaties of architecture or stereotomy from
1500 to 1800, is a preambule to the mechanical study of these constructions. Flat archs
with X-joints, ﬂat archs « en fausse-coupe », and Abeille’s ﬂat vaults are studied in
detail because of their speciﬁc stereotomy. Geometric rules used to determine joint
orientation, by architects on the one hand, and by stone masons on the other hand,
emerge from this work. An extension of the force network method is presented, in
order to take into account the vaults’ stonework, to ﬁnd new equilibrium solutions
by reﬁning networks, and to comply rigourously with the theory of yield calculus.
Calculus strategies for the search of limit loads, whose determination is essential for
the technique, are given. Mechanical studies are conducted on cylindrical archs and
hemispherical domes, ﬂat archs and ﬂat vaults, and helicoidal vaults. They show the
precision of the geometric safety factor estimate, the inﬂuence of stone cutting on ﬂat
archs and vaults, and the possibilities and limits of using the force networks method
to study stone-cut vaults.

Keywords : stereotomy, stone cutting, ashlar, stonework, ﬂat arch, ﬂat vault, stability, yield design

3

<!-- p. 5 -->

Remerciements

Je remercie Maurizio Brocato et Thierry Ciblac d’avoir accepté d’encadrer cette
thèse de doctorat et de m’avoir accompagné pendant ces trois années de recherche
sur la coupe des pierres et sur les voûtes.
Je tiens à remercier particulièrement les Compagnons passant du devoir tailleurs
de pierre Luc Tamboréro (Ateliers romeo), Gilbert Margueritte (Margueritte SAS),
et Jérémie Fierens (Ateliers de Saint-Jacques) pour leur aide et leurs conseils sur
la coupe des pierres actuelle et passée des plates-bandes, qui ont été essentiels pour
mon travail de recherche historique sur les règles géométriques de conception des
plates-bandes.
Je voudrais ensuite remercier l’ensemble des historiens de l’art qui m’ont apporté leur expertise pour contextualiser les exemples découverts de plates-bandes en
fausse-coupe, et en tout premier lieu Alexandre Gady (Centre André-Chastel, Université Paris-Sorbonne) et Guillaume Fonkenell (musée national de la Renaissance au
château d’Écouen) pour leur aide précieuse concernant les plates-bandes en faussecoupe de Jacques Lemercier et celles du Louvre. Je remercie également Paolo Cornaglia (Politecnico di Torino), Javier Ibáñez Fernández (Universidad de Zaragoza)
et Arturo Zaragozá Catalán (Universitat de València), Pierre-Louis Laget (Conseil
régional des Hauts-de-France), et Nicolas Reveyron (Université Lumière Lyon 2) pour
leurs remarques éclairées. Un grand merci également à Léonore Losserand (chercheuse
indépendante), Béatrice Viré-Gaillard (ENSA Versailles), Joëlle Barreau (Centre André Chastel) et Yvon Plouzennec (Centre André Chastel) pour leurs conseils et remarques.
Je suis reconnaissant à tous ceux qui m’ont aidé à réunir des informations sur le
phénomène particulier de la fausse-coupe à Chambéry : Humbert de Rivaz (UDAP
Haute-Savoie), Philippe Raﬀaelli (Conservation départementale du patrimoine de la
Savoie), Benoit Chambre (Épure - architecture & patrimoine), François Juttet (Centre
d’interprétation de l’Architecture et du Patrimoine) et Dominique Tritenne (Conservatoire national des pierres et marbres). Je tiens à remercier également Didier Repellin (ACMH) et Thomas Bricheux (Agence Repellin Larpin & Associés) pour leur
aide concernant la coupe des pierres à Lyon, et en particulier pour m’avoir permis
d’observer de près les plates-bandes en fausse-coupe de Souﬄot à l’Hôtel-Dieu de
Lyon.
Un grand merci à Benoît Vérant (ENSA Paris-Malaquais), Vianney Loing
(ENPC), Blerta Lipo (Università Degli Studi Roma Tre) pour leur aide durant et
après les expériences aux Grands Ateliers de l’Isle d’Abeau, et à Marco Czarnecki
(Université Montpellier 2) pour son aide précieuse pour trouver une solution pratique aux problèmes d’optimisation numérique posés par les réseaux de forces.
Je suis également reconnaissant à Jérémy Bleyer (ENPC), Sandrine Conan (Université Lille 3), Antoine Garnier (Atlas roman), Louis Jacquart, Nicolas Lestringuez (ENSA Paris-La-Villette), Anne-Laure Morel (ENSA Paris-Malaquais), Robert March (ENSA Paris-Malaquais), Márton Sarkadi et Nicolas Wasylyszyn (UDAP
de l’Eure).
Enﬁn, merci à Silvia pour sa relecture attentive et sa patience durant ces trois
années de recherche.

4

<!-- p. 6 -->

Liste des symboles

Aﬁn de les distinguer des scalaires, les matrices sont notées par des lettres capitales
en gras, et les vecteurs par des lettres minuscules en gras.

Lettres latines

b : largeur d’une plate-bande (ou 2b dans le cas des plates-bandes à joints en X)

C : matrice de connectivité
CSGj(ζ) = λj(ζ) : le coeﬃcient de sécurité géométrique d’un joint correspondant à
la solution d’équilibre donnée par le vecteur paramètre ζ
CSGJ (ζ) : coeﬃcient de sécurité géométrique de la structure correspondant à la
solution d’équilibre donnée par le vecteur paramètre ζ
CSGJ : coeﬃcient de sécurité géométrique de la structure, correspondant à la plus
grande valeur atteignable avec une solution d’équilibre
CSSj(ζ) : coeﬃcient de sécurité statique d’un joint correspondant à la solution d’équilibre donnée par le vecteur paramètre ζ
CSSJ (ζ) : coeﬃcient de sécurité statique de la structure correspondant à la solution
d’équilibre donnée par le vecteur paramètre ζ
CSSJ : coeﬃcient de sécurité statique de la structure, correspondant à la plus grande
valeur atteignable avec une solution d’équilibre

e : excentricité d’un centre de pression par rapport au centre du joint

f : fonction de coût utilisée pour déterminer un multiplicateur de rupture

F(Q) : coeﬃcient de rupture du mode de chargement Q, également appelé multiplicateur de charge, ou coeﬃcient de sécurité

g : fonction de coût utilisée pour déterminer un multiplicateur de rupture

G : domaine admissible pour les contraintes

H : poussée (réaction horizontale sur un appui)

h : hauteur d’une plate-bande ou d’une voûte plate

K : domaine des chargements potentiellement supportables

K : matrice obtenue par l’écriture de l’équilibre horizontal de chaque nœud d’un
réseau

k : nombre de claveaux d’une plate-bande

l : longueur d’une branche d’un réseau de forces
l∗: force dans la branche d’un réseau de forces
lH : longueur de la projection sur un plan horizontal d’une branche d’un réseau de
forces
Li : portée libre de l’arc ou de la voûte, mesurée à l’intrados
Lm : portée de l’arc ou de la voûte, mesurée à mi-hauteur
M : moment dans le repère global de la plate-bande (contrainte généralisée de la
théorie des poutres)

5

<!-- p. 7 -->

M′ : moment dans le repère local du joint (contrainte généralisée de la théorie des
poutres)

m : moment adimensionné, ou nombre de branches d’un réseau de forces

N : eﬀort normal dans le repère global de la plate-bande (contrainte généralisée de
la théorie des poutres)
N′ : eﬀort normal dans le repère local du joint (contrainte généralisée de la théorie
des poutres)
Nc : eﬀort normal maximal admissible dans le repère global de la plate-band
N′c : eﬀort normal maximal admissible dans le repère local du joint
n : eﬀort normal adimensionné, ou nombre de nœuds d’un réseau de forces
nb : nombre de nœuds d’appuis d’un réseau de forces
ni : nombre de nœuds intérieurs d’un réseau de forces
ndof : degré d’hyperstaticité d’un réseau de forces projeté sur un plan horizontal
r : rayon moyen d’un arc en plein-cintre ou d’un dôme hémisphérique
px, py, pz : composantes du chargement extérieur sur un nœud d’un réseau de forces
Q : vecteur représentant le mode de chargement de la structure

q : densité de force dans une branche d’un réseau de forces
rK : rang de la matrice K
s : force axiale dans une branche d’un réseau de forces

t : épaisseur d’un arc en plein-cintre ou d’un dôme hémisphérique

u : composante selon l’axe x d’une branche d’un réseau de forces
u∗: composante selon l’axe x de la force dans une branche d’un réseau de forces

V : eﬀort tranchant dans le repère global de la plate-bande (contrainte généralisée de
la théorie des poutres)
V ′ : eﬀort tranchant dans le repère local du joint (contrainte généralisée de la théorie
des poutres)

v : eﬀort tranchant adimensionné ou composante selon l’axe y d’une branche d’un
réseau de forces
v∗: composante selon l’axe y de la force dans une branche d’un réseau de forces

W : charge verticale totale s’appliquant à une plate-bande ou une voûte plate
W0 : charge verticale due au poids propre
w : composante selon l’axe z d’une branche d’un réseau de forces
w∗: composante selon l’axe z de la force dans une branche d’un réseau de forces

x : coordonnée cartésienne d’un nœud d’un réseau de forces
xG : coordonnée cartésienne du centre de gravité d’un claveau
y : coordonnée cartésienne d’un nœud d’un réseau de forces
yG : coordonnée cartésienne du centre de gravité d’un claveau
z : coordonnée cartésienne d’un nœud d’un réseau de forces
zG : coordonnée cartésienne du centre de gravité d’un claveau

6

<!-- p. 8 -->

Lettres grecques

λj : coeﬃcient de rupture du joint j, également appelé multiplicateur de charge, ou
coeﬃcient de sécurité

ϕ : angle d’un joint avec la verticale

µ : coeﬃcient de frottement de Coulomb d’un joint, correspondant à un angle de
frottement de tan−1 µ
ρ0 : masse volumique de la pierre
σ : champ de contrainte
σ0 : résistance admissible à la compression d’un joint
ξ : hauteur relative en compression d’un joint

ζ : vecteur des forces horizontales d’un réseau de forces (cas du calcul d’un réseau),
ou vecteur des paramètres de l’équilibre d’un réseau de forces (cas de la recherche des
chargements extrêmes)

Acronymes

GAIA : Grands ateliers de l’Isle d’Abeau

GSA : Laboratoire géométrie, structure, architecture de l’ENSA Paris-Malaquais

ENPC : École nationale des ponts et chaussées

ENSA Paris-Malaquais : École nationale supérieure d’architecture Paris-Malaquais

ENSA Paris-La-Villette : École nationale supérieure d’architecture Paris-La-Villette

ENSA Versailles : École nationale supérieure d’architecture de Versailles

ISMH : Monument inscrit à la liste supplémentaire des Monuments Historiques

MH : Monument classé aux Monuments Historiques

7

<!-- p. 9 -->

Table des matières

Remerciements 3

Liste des symboles 4

Table des matières 8

Introduction 15

Partie I État de l’art 19

1 Équilibre des constructions clavées 20
1.1 Le polygone funiculaire . . . . . . . . . . . . . . . . . . . . . . . . . . . 21
1.2 La ligne de pression . . . . . . . . . . . . . . . . . . . . . . . . . . . . 22
1.3 Comparaison de la ligne de pression et du polygone funiculaire . . . . 23
1.4 Inﬂuence de l’appareil sur la ligne de pression . . . . . . . . . . . . . . 27

2 Stabilité des constructions clavées 28
2.1 Le calcul à la rupture . . . . . . . . . . . . . . . . . . . . . . . . . . . 29
2.1.1 Mécanique des milieux continus tridimensionnels . . . . . . . . 29
2.1.2 Formulation générale . . . . . . . . . . . . . . . . . . . . . . . . 29
2.1.3 Construction de K par l’intérieur . . . . . . . . . . . . . . . . . 31
2.1.4 Approche de K par l’extérieur . . . . . . . . . . . . . . . . . . 32
2.1.5 Coeﬃcient de rupture, multiplicateur de charge, et coeﬃcient
de sécurité . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32
2.1.6 Application aux constructions clavées . . . . . . . . . . . . . . 33
2.1.7 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 34
2.2 Recherche des solutions d’équilibre stables . . . . . . . . . . . . . . . . 34
2.2.1 Méthodes antérieures au calcul à la rupture . . . . . . . . . . . 34
2.2.2 Résolution analytique . . . . . . . . . . . . . . . . . . . . . . . 34
2.2.3 Méthode des équations d’équilibre discrétisées . . . . . . . . . . 35
2.2.4 Méthode de Delbecq . . . . . . . . . . . . . . . . . . . . . . . . 37
2.3 Exemples de structures étudiées . . . . . . . . . . . . . . . . . . . . . . 38

3 Critères de résistance 40
3.1 Critères de résistance des joints . . . . . . . . . . . . . . . . . . . . . . 41

8

<!-- p. 10 -->

Table des matières

3.1.1 Expressions des critères . . . . . . . . . . . . . . . . . . . . . . 41
3.1.2 Construction des coeﬃcients de sécurité . . . . . . . . . . . . . 42
3.2 Résistance ﬁnie des joints à la compression . . . . . . . . . . . . . . . . 43
3.2.1 Coeﬃcient de sécurité statique . . . . . . . . . . . . . . . . . . 43
3.2.2 Cas avec incertitudes sur la géométrie . . . . . . . . . . . . . . 45
3.3 Résistance inﬁnie des joints à la compression . . . . . . . . . . . . . . 46
3.3.1 Coeﬃcient de sécurité statique inopérant . . . . . . . . . . . . 46
3.3.2 Introduction du coeﬃcient de sécurité géométrique . . . . . . . 47
3.4 Résistance interne des pierres . . . . . . . . . . . . . . . . . . . . . . . 49
3.4.1 Cercles de Mohr . . . . . . . . . . . . . . . . . . . . . . . . . . 49
3.4.2 Application au claveau d’une plate-bande . . . . . . . . . . . . 50
3.4.3 Outils graphiques pour déterminer des solutions d’équilibre
stables . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 52

4 Méthode des réseaux de forces 55
4.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 56
4.2 Méthode des densités de forces . . . . . . . . . . . . . . . . . . . . . . 56
4.2.1 Concepts et hypothèses . . . . . . . . . . . . . . . . . . . . . . 56
4.2.2 Connectivité du réseau . . . . . . . . . . . . . . . . . . . . . . . 58
4.2.3 Notations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 58
4.2.4 Mise en équation de l’équilibre . . . . . . . . . . . . . . . . . . 59
4.2.5 Recherche d’une solution admissible . . . . . . . . . . . . . . . 61
4.3 Méthode des réseaux de forces . . . . . . . . . . . . . . . . . . . . . . . 61
4.3.1 Origine de la méthode . . . . . . . . . . . . . . . . . . . . . . . 61
4.3.2 Hypothèses . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 62
4.3.3 Principe de résolution pour les structures existantes . . . . . . 62
4.3.4 Notations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66
4.3.5 Mise en équation de l’équilibre . . . . . . . . . . . . . . . . . . 66
4.3.6 Recherche des solutions d’équilibre admissibles . . . . . . . . . 69

Partie II Plates-bandes et voûtes plates en France 71

5 Stéréotomie et coupe des pierres 72
5.1 Déﬁnitions ; de la pierre au voussoir . . . . . . . . . . . . . . . . . . . 73
5.2 Processus de taille de pierre . . . . . . . . . . . . . . . . . . . . . . . . 76
5.3 Évolution des tracés de coupe des pierres . . . . . . . . . . . . . . . . 77
5.4 Principe de normalité . . . . . . . . . . . . . . . . . . . . . . . . . . . 80

6 Typologie constructive des plates-bandes 85
6.1 Terminologie . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 87
6.1.1 Plates-bandes et linteaux . . . . . . . . . . . . . . . . . . . . . 87
6.1.2 Classiﬁcation des plates-bandes selon les joints . . . . . . . . . 89
6.2 Nombre impair des claveaux . . . . . . . . . . . . . . . . . . . . . . . . 96
6.3 Inclinaison des joints . . . . . . . . . . . . . . . . . . . . . . . . . . . . 98
6.3.1 Principe d’inclinaison . . . . . . . . . . . . . . . . . . . . . . . 98
6.3.2 Rejet des joints verticaux . . . . . . . . . . . . . . . . . . . . . 98

9

<!-- p. 11 -->

Table des matières

6.3.3 Règles géométriques pour déterminer l’inclinaison . . . . . . . . 99
6.3.4 Évolution des règles dans les traités . . . . . . . . . . . . . . . 101
6.3.5 Méthodes de tracés . . . . . . . . . . . . . . . . . . . . . . . . . 110
6.3.6 Architectes et appareilleurs . . . . . . . . . . . . . . . . . . . . 113
6.3.7 Les « portes bombées »et les « croisées bombées » . . . . . . . 115
6.4 Hauteur des claveaux . . . . . . . . . . . . . . . . . . . . . . . . . . . . 116
6.5 Détails constructifs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 121
6.5.1 Crossettes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 121
6.5.2 Balles de plomb, cailloux, goujons et os de bœufs . . . . . . . . 123
6.5.3 La contre-ﬂèche . . . . . . . . . . . . . . . . . . . . . . . . . . . 126
6.5.4 Lit de carrière . . . . . . . . . . . . . . . . . . . . . . . . . . . . 128
6.6 Utilisation du métal dans les plates-bandes . . . . . . . . . . . . . . . 128
6.6.1 Exemples de plates-bandes avec armatures métalliques . . . . . 128
6.6.2 L’armature : linteau ou tirant . . . . . . . . . . . . . . . . . . . 132
6.6.3 Opposition aux armatures . . . . . . . . . . . . . . . . . . . . . 133
6.7 Coupe des pierres et décor . . . . . . . . . . . . . . . . . . . . . . . . . 134
6.7.1 Refends et faux-appareil . . . . . . . . . . . . . . . . . . . . . . 134
6.7.2 Ablaq . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 136
6.7.3 Non-ﬁabilité des dessins et gravures . . . . . . . . . . . . . . . 137

7 Plates-bandes à joints en X 140
7.1 Construction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 141
7.2 Exemples construits au Moyen Âge . . . . . . . . . . . . . . . . . . . . 141
7.3 Références écrites . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 142
7.4 Expériences . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 146
7.4.1 Expériences aux ateliers de l’ENSA Paris-Malaquais . . . . . . 146
7.4.2 Expériences aux Grands ateliers de l’Isle d’Abeau . . . . . . . . 147

8 Plates-bandes en fausse-coupe 151
8.1 La fausse-coupe dans les traités . . . . . . . . . . . . . . . . . . . . . . 152
8.2 Plates-bandes en fausse-coupe potentielles . . . . . . . . . . . . . . . . 154
8.2.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 154
8.2.2 Jacques Lemercier (av. 1586-1654) . . . . . . . . . . . . . . . . 156
8.2.3 Le Louvre . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 158
8.2.4 Le dix-septième siècle . . . . . . . . . . . . . . . . . . . . . . . 159
8.2.5 Refus et renouveau de la fausse-coupe au XVIIIe siècle . . . . . 161
8.2.6 La fausse-coupe à Chambéry . . . . . . . . . . . . . . . . . . . 162
8.3 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 164

9 Plates-bandes de l’Antiquité à la Révolution 168
9.1 Méthode de recherche et objectifs . . . . . . . . . . . . . . . . . . . . . 169
9.2 Antiquité . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 170
9.2.1 Du linteau à la plate-bande dans les entablements . . . . . . . 170
9.2.2 Exemples construits . . . . . . . . . . . . . . . . . . . . . . . . 170
9.3 Moyen Âge . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 176
9.3.1 Portails . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 176
9.3.2 Cheminées . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 177

10

<!-- p. 12 -->

Table des matières

9.3.3 Baies . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 178
9.3.4 Villard de Honnecourt . . . . . . . . . . . . . . . . . . . . . . . 178
9.4 Époque Moderne . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 180
9.4.1 Entablements . . . . . . . . . . . . . . . . . . . . . . . . . . . . 180
9.4.2 Baies . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 180
9.4.3 Escaliers à jour et escaliers suspendus . . . . . . . . . . . . . . 181
9.4.4 Les dessins de Léonard de Vinci . . . . . . . . . . . . . . . . . . 181

10 Voûtes plates 184
10.1 Voûtes plates ou voûtes surbaissées ? . . . . . . . . . . . . . . . . . . . 185
10.2 Voûtes plates dallées . . . . . . . . . . . . . . . . . . . . . . . . . . . . 188
10.3 Voûtes plates clavées . . . . . . . . . . . . . . . . . . . . . . . . . . . . 189
10.3.1 Appareil . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 189
10.3.2 Utilisation du métal . . . . . . . . . . . . . . . . . . . . . . . . 189
10.3.3 Exemples construits . . . . . . . . . . . . . . . . . . . . . . . . 193
10.3.4 Voûtes plates d’Abeille . . . . . . . . . . . . . . . . . . . . . . . 196
10.4 Voûtes très surbaissées . . . . . . . . . . . . . . . . . . . . . . . . . . . 198
10.4.1 Confusion des termes . . . . . . . . . . . . . . . . . . . . . . . . 198
10.4.2 Voûtes surbaissées en pierre de taille . . . . . . . . . . . . . . . 199
10.4.3 Voûtes à la Roussillon, ou voûtes catalanes . . . . . . . . . . . 200

Partie III Réseaux de forces pour les constructions clavées 202

11 Motivation et enjeux 203
11.1 Réseaux de forces et lignes de pression . . . . . . . . . . . . . . . . . . 204
11.1.1 Extension du polygone funiculaire sous forme de réseau . . . . 204
11.1.2 Réseau funiculaire . . . . . . . . . . . . . . . . . . . . . . . . . 205
11.2 Hypothèse de l’intersection des forces . . . . . . . . . . . . . . . . . . . 206
11.2.1 Rappels sur l’équilibre d’un bloc . . . . . . . . . . . . . . . . . 206
11.2.2 L’intersection, condition non nécessaire . . . . . . . . . . . . . 207
11.2.3 Absence de conséquence en 2D . . . . . . . . . . . . . . . . . . 207
11.2.4 Directions ﬁxes des forces projetées sur le plan horizontal . . . 208
11.2.5 Conjugaison des directions du réseau . . . . . . . . . . . . . . . 208
11.3 Verticalité des charges . . . . . . . . . . . . . . . . . . . . . . . . . . . 211
11.4 Besoins d’une extension de la méthode . . . . . . . . . . . . . . . . . . 211
11.4.1 Pour la coupe des pierres . . . . . . . . . . . . . . . . . . . . . 211
11.4.2 Pour le calcul à la rupture . . . . . . . . . . . . . . . . . . . . . 211

12 Extension des réseaux de forces 212
12.1 Extension de la méthode des réseaux de forces . . . . . . . . . . . . . . 213
12.2 Simpliﬁcation de l’appareil et paramétrisation de la géométrie . . . . . 213
12.3 Considération des joints . . . . . . . . . . . . . . . . . . . . . . . . . . 214
12.4 Critères de résistance des joints . . . . . . . . . . . . . . . . . . . . . . 215
12.5 Branches partielles additionnelles . . . . . . . . . . . . . . . . . . . . . 215
12.6 Recherche des chargements extrêmes . . . . . . . . . . . . . . . . . . . 217
12.6.1 Recherche par optimisation sous contraintes . . . . . . . . . . . 217

11

<!-- p. 13 -->

Table des matières

12.6.2 Stratégies de résolution . . . . . . . . . . . . . . . . . . . . . . 218

13 Implémentation numérique 219
13.1 Implémentation de l’extension des réseaux de forces . . . . . . . . . . 220
13.1.1 Visual Basic for Applications et Microsoft Excel . . . . . . . . 220
13.1.2 Équilibre horizontal . . . . . . . . . . . . . . . . . . . . . . . . 220
13.1.3 Équilibre vertical . . . . . . . . . . . . . . . . . . . . . . . . . . 221
13.2 Redéﬁnition des joints . . . . . . . . . . . . . . . . . . . . . . . . . . . 223
13.3 Raﬃnement du réseau et branches partielles . . . . . . . . . . . . . . . 225
13.3.1 Modiﬁcation des équations d’équilibre . . . . . . . . . . . . . . 225
13.3.2 Écriture alternative des équations d’équilibre . . . . . . . . . . 226
13.3.3 Vériﬁcation de l’équilibre a posteriori . . . . . . . . . . . . . . . 226
13.4 Recherche des chargements extrêmes . . . . . . . . . . . . . . . . . . . 227
13.4.1 Optimisation sous contraintes . . . . . . . . . . . . . . . . . . . 227
13.4.2 Polynômes de Lagrange . . . . . . . . . . . . . . . . . . . . . . 227
13.4.3 Multiplicateurs de charges modiﬁés par puissances d’entiers . . 228
13.4.4 Coeﬃcient de sécurité géométrique modiﬁé . . . . . . . . . . . 233
13.4.5 Convexité du domaine des chargements supportables . . . . . . 235
13.4.6 Bilan des stratégies . . . . . . . . . . . . . . . . . . . . . . . . . 236

Partie IV Étude mécanique des constructions clavées 237

14 Étude des arcs et dômes 238
14.1 Épaisseurs minimales . . . . . . . . . . . . . . . . . . . . . . . . . . . . 239
14.1.1 Coeﬃcient de sécurité géométrique . . . . . . . . . . . . . . . . 239
14.1.2 Épaisseur minimale d’un arc plein-cintre . . . . . . . . . . . . . 239
14.1.3 Épaisseur minimale d’un dôme hémisphérique . . . . . . . . . . 241
14.2 Étude des procédés historiques de calcul des voûtes . . . . . . . . . . . 245

15 Étude des plates-bandes 249
15.1 Paramétrisation des plates-bandes . . . . . . . . . . . . . . . . . . . . 250
15.2 Domaines des chargements supportables analytiques . . . . . . . . . . 253
15.2.1 Contexte . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 253
15.2.2 Frontière du critère de résistance en compression . . . . . . . . 253
15.2.3 Frontière du critère de résistance en frottement . . . . . . . . . 256
15.3 Inﬂuence de la coupe des pierres sur la stabilité . . . . . . . . . . . . . 257
15.3.1 Exemples considérés, Prato et GAIA . . . . . . . . . . . . . . . 257
15.3.2 Inﬂuence du nombre de claveaux et de la clé . . . . . . . . . . . 259
15.3.3 Inﬂuence de l’inclinaison des joints . . . . . . . . . . . . . . . . 259
15.3.4 Inﬂuence des joints en X . . . . . . . . . . . . . . . . . . . . . . 261
15.4 Extension des domaines avec les réseaux de forces . . . . . . . . . . . . 263
15.4.1 Principe de construction des domaines avec les réseaux de forces 263
15.4.2 Plates-bandes à joints inclinés . . . . . . . . . . . . . . . . . . . 264
15.4.3 Plates-bandes à joints en X . . . . . . . . . . . . . . . . . . . . 265
15.5 Modèle aux éléments ﬁnis . . . . . . . . . . . . . . . . . . . . . . . . . 270
15.5.1 Contexte . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 270

12

<!-- p. 14 -->

Table des matières

15.5.2 Modèle Cast3M des plates-bandes . . . . . . . . . . . . . . . . 270
15.5.3 Solutions d’équilibre . . . . . . . . . . . . . . . . . . . . . . . . 272

16 Étude des voûtes plates 276
16.1 Description des voûtes étudiées . . . . . . . . . . . . . . . . . . . . . . 277
16.1.1 Étude de trois appareils . . . . . . . . . . . . . . . . . . . . . . 277
16.1.2 Paramétrisation des appareils . . . . . . . . . . . . . . . . . . . 278
16.1.3 Déﬁnition des voûtes étudiées . . . . . . . . . . . . . . . . . . . 279
16.2 Inﬂuence des choix de modélisation . . . . . . . . . . . . . . . . . . . . 280
16.2.1 Application de la méthode des réseaux de forces . . . . . . . . 280
16.2.2 Raﬃnement du réseau . . . . . . . . . . . . . . . . . . . . . . . 281
16.2.3 Interpolation polynomiale des paramètres . . . . . . . . . . . . 283
16.3 Inﬂuence de la coupe des pierres . . . . . . . . . . . . . . . . . . . . . 285
16.3.1 Résultats de la voûte unidirectionnelle . . . . . . . . . . . . . . 285
16.3.2 Résultats de la voûte bidirectionnelle . . . . . . . . . . . . . . . 286
16.3.3 Résultats de la voûte d’Abeille . . . . . . . . . . . . . . . . . . 291
16.3.4 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 294
16.4 Modèle aux éléments ﬁnis . . . . . . . . . . . . . . . . . . . . . . . . . 294

17 Étude des voûtes hélicoïdales 298
17.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 299
17.2 Étude par bandes indépendantes . . . . . . . . . . . . . . . . . . . . . 299
17.3 Étude avec les réseaux de forces . . . . . . . . . . . . . . . . . . . . . . 300
17.3.1 Bande inﬁnitésimale . . . . . . . . . . . . . . . . . . . . . . . . 300
17.3.2 Escalier complet . . . . . . . . . . . . . . . . . . . . . . . . . . 300

Conclusion et perspectives 305

Partie V Annexes 307

A Sources bibliographiques 308
A.1 Citations des traités de l’Époque Moderne . . . . . . . . . . . . . . . . 308
A.2 Citations des traités de l’Époque Contemporaine . . . . . . . . . . . . 321
A.3 Citations des ouvrages récents . . . . . . . . . . . . . . . . . . . . . . . 332
A.4 Discussion des plates-bandes à l’Académie royale d’architecture . . . . 336

B Catalogue 344
B.1 Plates-bandes dans l’Antiquité . . . . . . . . . . . . . . . . . . . . . . 345
B.2 Plates-bandes au Moyen Âge . . . . . . . . . . . . . . . . . . . . . . . 352
B.2.1 Plates-bandes de portail . . . . . . . . . . . . . . . . . . . . . . 352
B.2.2 Plates-bandes de cheminée . . . . . . . . . . . . . . . . . . . . . 359
B.2.3 Plates-bandes de baie . . . . . . . . . . . . . . . . . . . . . . . 365
B.3 Plates-bandes à l’Époque Moderne . . . . . . . . . . . . . . . . . . . . 368
B.3.1 Plates-bandes d’entablement . . . . . . . . . . . . . . . . . . . 368
B.3.2 Plates-bandes d’escalier . . . . . . . . . . . . . . . . . . . . . . 370
B.4 Plates-bandes à joints en X . . . . . . . . . . . . . . . . . . . . . . . . 371

13

<!-- p. 15 -->

Table des matières

B.5 Plates-bandes en fausse-coupe . . . . . . . . . . . . . . . . . . . . . . . 373
B.5.1 Jacques Lemercier . . . . . . . . . . . . . . . . . . . . . . . . . 373
B.5.2 Le Louvre . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 380
B.5.3 Le dix-septième siècle . . . . . . . . . . . . . . . . . . . . . . . 391
B.5.4 Le dix-huitième siècle . . . . . . . . . . . . . . . . . . . . . . . 398
B.5.5 Chambéry . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 406
B.6 Voûtes plates . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 411

C Critère de résistances des joints en X 418

D Instrumentation des plates-bandes à joints en X 422
D.1 Contexte . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 422
D.2 Résultats de mars 2017 (GAIA) . . . . . . . . . . . . . . . . . . . . . . 423
D.3 Résultats de juin 2017 (Troyes) . . . . . . . . . . . . . . . . . . . . . . 424

E Voûtes plates d’Abeille expérimentales 426
E.1 Expériences aux Grands ateliers de l’Isle d’Abeau . . . . . . . . . . . . 426
E.2 Murs préfabriqués du projet Astonyshine . . . . . . . . . . . . . . . . . 427

F Formules des voussoirs 429
F.1 Arc en plein-cintre . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 430
F.2 Dôme hémisphérique . . . . . . . . . . . . . . . . . . . . . . . . . . . . 430
F.3 Dôme elliptique . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 432
F.4 Voûte hélicoïdale . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 433
F.5 Voûte plate . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 433

Table des ﬁgures 436

Index 445

Index des auteurs 449

Bibliographie 453

14

<!-- p. 16 -->

Introduction

L’objectif de cette thèse est de mieux comprendre l’inﬂuence de la coupe des
pierres sur la résistance des arcs et des voûtes clavés en pierre de taille. Elle s’inscrit
dans le cadre de l’étude des techniques constructives antérieures à la Révolution.
Les épures des tailleurs de pierre du xvie au xviiie siècle, telles qu’elles sont
suggérées par les traités de coupe des pierres, sont complexes à appréhender. Elles
débutent cependant par l’application de règles géométriques simples, qui concernent
notamment l’inclinaison à donner aux joints des voussoirs ou claveaux. Ces règles
concernant l’inclinaison des joints constituent le ﬁl conducteur reliant les diﬀérents
arcs et voûtes que nous étudions, du point de vue historique, typologique, puis mécanique.

La partie I présente l’état de l’art de l’étude de la stabilité des constructions
clavées, c’est-à-dire des arcs et des voûtes composés de voussoirs ou claveaux, éléments en pierre de taille taillés et posés pour occuper une place prédéterminée dans
la construction. Les concepts de polygone funiculaire et de ligne de pression sont
d’abord présentés, ainsi que l’inﬂuence de l’appareil, et donc de la coupe des pierres,
sur la ligne de pression. La théorie du calcul à la rupture et son application aux
constructions clavées sont exposées ensuite. Cette théorie permet de déterminer les
chargements potentiellement supportables par un arc ou une voûte. Les domaines
des chargements potentiellement supportables seront exploités ultérieurement pour
comparer la résistance des voûtes. Les diﬀérentes méthodes permettant de produire
les solutions d’équilibre nécessaires à la construction par l’intérieur des domaines
des chargements potentiellement supportables sont évoquées, ainsi que des exemples
de constructions étudiées dans la littérature montrant la diversité des applications
possibles du calcul à la rupture pour la maçonnerie et la pierre de taille.

Pour appliquer la théorie du calcul à la rupture aux constructions clavées, il
convient d’exprimer la résistance des matériaux au niveau des joints. Ce point fait
l’objet d’un chapitre spéciﬁque, en raison de son importance dans le cadre de notre
étude sur la coupe des pierres. Le coeﬃcient de sécurité statique et un estimatif
du coeﬃcient de sécurité géométrique sont déﬁnis. La possible considération de la
résistance interne de la pierre, en construisant des champs de contrainte constant par
morceaux admissible pour chaque claveaux, et en exploitant les propriétés graphiques
des cercles de Mohr, est ensuite présentée.

La méthode des densités de forces et la méthode des réseaux de forces sont ensuite
décrites. Les réseaux de forces étendent sous forme de réseau la notion de polygone
funiculaire, de la même manière que la résille caténaire inversée, notamment utilisée
par Antoni Gaudí, généralise la caténaire inversée. L’intérêt des réseaux de forces

15

<!-- p. 17 -->

Table des matières

pour l’étude des voûtes en maçonnerie a été mis en avant par O’Dwyer (1999) sous le
nom de « force network method », et étendue par Block et Ochsendorf (2007) sous le
nom de « thrust network analysis ». Ces réseaux seront utilisés dans cette thèse pour
générer les solutions d’équilibre des constructions clavées.
La partie II présente les résultats d’une étude historique et typologique des
plates-bandes et des voûtes plates construites en France. Les notions principales de
la stéréotomie et de la taille des pierres sont tout d’abord introduites, ainsi qu’un résumé de l’évolution des traités de coupe des pierres qui décrivent le tracé des épures.
Le principe de normalité, qui indique que les joints des voûtes doivent être perpendiculaires à l’intrados, est ensuite décrit, ainsi que les limites qu’entraîneraient son
application systématique. Cet ensemble constitue le contexte général de la coupe des
pierres des voûtes courbes, qui permet d’apprécier ensuite les spéciﬁcités de la coupe
des pierres des couvrements plans : les plates-bandes et les voûtes plates.
Un essai de typologie constructive des plates-bandes est proposé, en considérant
successivement le nombre de claveaux (généralement impair), la hauteur de la platebande (donnée relativement à sa portée), les détails constructifs (comme l’utilisation
des crossettes, des balles de plomb etc.), et l’utilisation du métal. La relation qu’entretiennent coupe des pierres et décor est examinée à travers des exemples ; l’utilisation
des refends pour souligner l’appareil, ou au contraire simuler un faux-appareil, est
mentionnée ; le caractère non ﬁable des dessins et gravures représentant l’appareil des
plates-bandes est rappelé. Au sein de la typologie proposée, l’inclinaison des joints
des plates-bandes fait l’objet d’une étude approfondie. Le rejet des joints verticaux
pour la construction des plates-bandes conduit à l’utilisation de joints inclinés sur
la verticale. Nous étudions l’évolution des règles géométriques donnant le tracé des
joints inclinés, et les informations que ces règles livrent sur les pratiques respectives
des architectes et des appareilleurs.
Les plates-bandes à joints en X construites au Moyen Âge en Europe, et les platesbandes en fausse-coupe construites à partir du xviie siècle en France, présentent une
coupe des pierres savante, jouant sur l’impression d’instabilité qu’elle procure au
spectateur. Chacune fait l’objet d’un chapitre pour exposer son mode constructif, les
exemples connus, et les informations tirées de la littérature à propos de ces objets.
Les résultats d’expériences sur des plates-bandes à joints en X en bois, puis en pierre,
sont présentés.
Une histoire des plates-bandes est proposée à travers la présentation d’exemples
construits dans l’Antiquité, au Moyen Âge puis à l’Époque Moderne. Pour chaque
époque, les traits principaux des plates-bandes tels qu’ils peuvent être appréciés à
partir des exemples réunis sont exposés.
Enﬁn, les informations réunies sur les voûtes plates en pierre de taille, à ne pas
confondre avec les voûtes surbaissées, font l’objet du dernier chapitre de la partie
historique. Les voûtes plates clavées, et parmi elles les voûtes plates d’Abeille, du
nom de leur inventeur, font l’objet d’un développement particulier.
L’exploitation des informations contenues dans les traités d’architecture et de
coupe des pierres nécessite une part d’interprétation du vocabulaire de leurs auteurs,
qui ne répond pas à une nomenclature bien établie concernant les points de détails
de construction des plates-bandes. À titre d’exemple, le terme « joint à plomb » fait
référence non pas à un joint unique vertical, mais à un joint double formé d’une partie

16

<!-- p. 18 -->

Table des matières

verticale (la fausse-coupe) et d’une partie inclinée. Dans ce contexte, les citations exploitées dans cette étude historique sont reproduites pour permettre la confrontation
des nombreuses sources utilisées. Elles ont été réunies en annexe pour ne pas alourdir
la lecture. Les citations sont numérotées par ordre chronologique de publication. Le
renvoi « cit. 64 » fait référence à la citation numéro 64, les citations étant regroupées
dans l’annexe A.
Le nombre d’exemples de plates-bandes et de voûtes plates réunis pour ces différents chapitres étant important, ils ont été rassemblés en annexe sous forme d’un
catalogue constitué de tableaux illustrés, avec les indications recueillies sur le contexte
de la construction et la datation de chaque plate-bande ou voûte plate référencée.
La partie III présente l’extension de la méthode des réseaux de forces que nous
proposons dans cette thèse. Dans un premier temps, les raisons pour lesquelles une
extension nous a semblé nécessaire sont exposées. Il convient tout d’abord de remarquer que le réseau de forces est l’extension sous forme de réseau du polygone
funiculaire, et non celle de la ligne de pression. De plus, les deux hypothèses fondamentales nécessaires pour appliquer la méthode des réseaux des forces introduisent
des limitations sur les solutions d’équilibre accessibles. Le besoin d’une extension de
la méthode apparaît également pour permettre d’une part l’étude de l’inﬂuence de
l’appareil, et d’autre part l’intégration de la méthode au cadre rigoureux du calcul à
la rupture.
Les principes de l’extension de la méthode des réseaux de forces sont ensuite exposés. Ils consistent en la simpliﬁcation de l’appareil, la considération de la géométrie
des joints, puis celle des critères de résistance exprimés au niveau des joints, qui sont
des points essentiels pour l’intégration de la méthode des réseaux de forces au cadre
du calcul à la rupture. De plus, l’introduction de branches partielles permet de raﬃner
les réseaux et donc les solutions d’équilibre accessibles. Enﬁn, diﬀérentes stratégies
de détermination des chargements extrêmes déﬁnissant les domaines de chargements
potentiellement supportables sont proposées.
L’implémentation de ces diﬀérents points est ensuite détaillée dans un chapitre
spéciﬁque. Les stratégies d’optimisation numérique, qui sont l’enjeu numérique le plus
important pour la recherche des chargements extrêmes et donc pour la faisabilité
pratique de la méthode que nous proposons, sont présentées, ainsi qu’une étude des
vitesses de convergence pour la stratégie la plus eﬃcace (modiﬁcation de la fonction
de coût utilisée pour la recherche des chargements extrêmes).
Enﬁn, la partie IV présente les résultats des études mécaniques que nous avons
menées sur quatre types de structures : les voûtes courbes (arcs et dômes), les platesbandes, les voûtes plates, et les voûtes hélicoïdales.
Le chapitre sur les voûtes courbes présente deux applications de l’extension de la
méthode des réseaux de forces. La première est l’étude des épaisseurs minimales des
arcs en plein-cintre et des dômes hémisphériques, et à travers ces exemples l’étude
de la convergence de l’estimatif du coeﬃcient de sécurité géométrique vers la valeur
du coeﬃcient théorique déﬁni par Heyman (1969). La seconde est l’exploitation des
réseaux de forces pour l’étude des procédés historiques de calcul des voûtes, à travers
les exemples de Rankine et Durand-Claye au xixe siècle.
L’inﬂuence de la coupe des pierres sur la résistance des plates-bandes est étudiée
dans le chapitre suivant. Trois types de plates-bandes sont analysés : les plates-bandes

17

<!-- p. 19 -->

Table des matières

à joints verticaux, les plates-bandes à joints inclinés, et les plates-bandes à joints en X.
Les domaines des chargements potentiellement supportables, qui sont utilisés pour
quantiﬁer la résistance, sont déterminés d’abord par calcul analytique, puis étendus
avec les réseaux de forces. Les réseaux de forces correspondant aux chargements
extrêmes sont comparés aux résultats obtenus avec un modèle aux éléments ﬁnis.

Après les plates-bandes, l’inﬂuence de la coupe des pierres sur la résistance des
voûtes plates est analysée. Trois types de voûte sont analysées : la voûte plate appareillée sur le plan du berceau, la voûte plate appareillée sur le plan de la voûte en
arc-de-cloître, et enﬁn la voûte plate d’Abeille. Les domaines des chargements potentiellement supportables, qui sont utilisés pour quantiﬁer la résistance, sont déterminés
avec les réseaux de forces. Les réseaux de forces correspondant aux chargements extrêmes sont comparés aux résultats obtenus avec un modèle aux éléments ﬁnis.

Enﬁn, le dernier chapitre de l’étude mécanique présente la comparaison des résultats fournis par la méthode des réseaux de forces à ceux d’un modèle analytique des
voûtes hélicoïdales (García Ares, 2007). Cette comparaison vise à illustrer quelques
limites de la méthode des réseaux de forces, comme la conjugaison de la direction
des réseaux, qui limite les solutions d’équilibre qui peuvent être produites avec cette
méthode.

18

<!-- p. 20 -->

Première partie

État de l’art

19

<!-- p. 21 -->

Chapitre 1

Équilibre des constructions
clavées

Résumé : Ce chapitre traite de l’équilibre des constructions clavées en pierre de
taille. Le polygone funiculaire et la ligne de pression sont des formes géométriques
couramment employées pour l’étude en deux dimensions de ces structures. Dans les
cas les plus courants, ces formes sont presque superposées, aussi est-il souvent diﬃcile
de les discerner. Ce chapitre donne la déﬁnition de chacun de ces objets géométriques,
et souligne les confusions existant entre ces termes dans la littérature du xixe siècle.
L’inﬂuence de l’appareil sur la ligne de pression est ensuite évoqué. Les informations
historiques concernant le polygone funiculaire et la ligne de pression de ce chapitre
sont tirées de History of strength of materials de Timoshenko (1953).

Sommaire
1.1 Le polygone funiculaire . . . . . . . . . . . . . . . . . . . . . . . . 21
1.2 La ligne de pression . . . . . . . . . . . . . . . . . . . . . . . . . . 22
1.3 Comparaison de la ligne de pression et du polygone funiculaire . . 23
1.4 Inﬂuence de l’appareil sur la ligne de pression . . . . . . . . . . . 27

20

<!-- p. 22 -->

Chapitre 1. Équilibre des constructions clavées

1.1 Le polygone funiculaire

Pour que trois forces soient en équilibre, en 2D comme en 3D, il faut nécessairement que leurs lignes d’action soient coplanaires et passent par un même point,
ce point pouvant être à l’inﬁni (Culmann, 1880, p. 147). En revanche, pour plus de
trois forces, ces conditions ne sont plus nécessaires : quatre forces peuvent être en
équilibre sans que leurs lignes d’actions soient coplanaires ni passent par un même
point. Nous verrons des exemples de ce type dans le cadre de l’étude des réseaux de
forces (section 11.2 page 206).

L’équilibre d’un claveau faisant partie d’un arc fait intervenir trois forces : le
chargement, et les deux forces s’appliquant sur les joints. À partir de la propriété
précédente, il existe un point d’intersection des forces s’appliquant à chaque claveau.

Déﬁnition 1. Un polygone funiculaire d’un arc clavé est un polygone dont les sommets sont les points d’intersection des lignes d’action des forces en équilibre s’appliquant à chaque claveau.

Si le chargement est formé d’un ensemble de forces coplanaires, comme cela est le
cas généralement pour le chargement gravitaire des arcs, alors le polygone funiculaire
et le polygone des forces sont plans (ﬁg. 1.1 à gauche). Cependant, si les forces ne
sont pas coplanaires, alors le polygone funiculaire et le polygone des forces ne sont
pas plans (ﬁg. 1.1 à droite).

face face
de de
vue vue

dessus dessus
de de
vue vue
polygone polygone
polygone funiculaire des forces polygone funiculaire des forces

Fig 1.1 – Polygones funiculaires et polygones des forces de systèmes composés de
deux forces coplanaires (à g.) ou non coplanaires (à d.), en vue de face et vue
de dessus

Historiquement, La Hire est le premier a avoir utilisé le polygone funiculaire
en 1695 (Timoshenko, 1953, p. 63). Le polygone funiculaire est également utilisé par
Varignon en 1725, par Lamé et Clapeyron en 1823, et par Poncelet en 1840 pour
l’étude des murs de soutènement (1953, p. 84, 89, 194). Il s’agit cependant d’applications pour des cas particuliers, et il faut attendre Culmann (1864) pour la présentation
systématique des méthodes graphiques pour l’analyse des structures (1953, p. 194).

21

<!-- p. 23 -->

Chapitre 1. Équilibre des constructions clavées

Culmann publie Die graphische Statik en 1864 à Zürick. Son ouvrage ne sera
traduit de l’allemand au français qu’en 1880. L’épure de Méry, qui était la méthode
de calcul des arcs en maçonnerie la plus connue en France au xixe siècle, ne fait pas
usage (1) du polygone funiculaire (Méry, 1840).

1.2 La ligne de pression

Un lieu géométrique important pour l’étude de l’équilibre des arcs est pour chaque
joint le point d’application de la résultante des actions de contact. Ce point peut être
également appelé point d’application de la résultante des forces, ou centre de pression.
Les points d’application des résultantes des actions de contact sur les joints
forment la ligne de pression. Dans le cadre de la statique graphique, ces points sont
construits à partir du polygone funiculaire.

Déﬁnition 2. Une ligne de pression d’un arc clavé est la suite des points d’application
des résultantes des actions de contact (ou centres de pression) sur ses joints.

Les centres de pression étant donnés par les intersections des lignes d’action des
résultantes des actions de contact avec les joints, la ligne de pression est donc la
suite des intersections des segments ou des prolongations des segments du polygone
funiculaire avec les joints.
Le concept de ligne de pression est publié pour la première fois par Gerstner
(1831, p. 405) selon Timoshenko (1953, p. 211) et Benvenuto (1991, cit. 134, 135) (2).
Il est ensuite étudié par Moseley (1843a,b), qui est le premier à distinguer la ligne de
pression et le polygone funiculaire, et qui publie en 1843 un article écrit en 1839 sur
la question (Timoshenko, 1953, p. 212). En France, Méry est le premier à employer le
terme de « courbe de(s) pression(s) » en 1840. Selon Dupuit (1870), l’article de 1840
correspond à un travail rédigé en 1827.
Une confusion importante règne parmi les termes utilisés pour désigner le « polygone funiculaire » et la « ligne de pression », en raison des faux-amis (3) en anglais
et en allemand.
Ainsi, dans (Culmann, 1880) qui est la première traduction en français du traité
de statique graphique de Culmann, les noms de « polygone funiculaire » et de « ligne
des pressions » sont appliqués respectivement à un polygone funiculaire en tension,
et à un polygone funiculaire en compression (4). Dans la partie de son ouvrage où
Culmann utilise ces termes, il considère uniquement les relations entre le polygone

(1). L’épure de Méry connaît une évolution tout au long du xixe siècle. Nous faisons référence ici
à l’épure de Méry telle qu’elle fut présentée par son auteur en 1840.
(2). Les citations sont numérotées par ordre chronologique de publication. Le renvoi « cit. 134 » fait
référence à la citation numéro 134, les citations étant regroupées dans l’annexe A.
(3). « Faux-ami : terme d’une langue étrangère qui présente une ressemblance graphique ou phonique avec un terme de la langue maternelle, mais ne possède pas le même sens. » Dictionnaire
Larousse.
(4). Culmann (1880) : « C’est pour ce motif que l’on désigne fréquemment le contour polygonal
formé par les résultantes sous le nom de polygone funiculaire. Dans la théorie des voûtes, où tous les
côtés du polygone sont soumis à des pressions, on l’appelle ligne des pressions. Nous emploierons ces
deux expressions, suivant que la majorité des côtés du polygone sera tendue ou comprimée. »
Culmann (1875) : « Es wird daher häuﬁg dieser Zug der Mittellinien ein Seilpolygon genannt. In der

22

<!-- p. 24 -->

Chapitre 1. Équilibre des constructions clavées

des forces et le polygone funiculaire. Il ne peut donc y avoir confusion de sens avec la
ligne de pression telle que nous l’entendons dans cette thèse, qui nécessite l’existence
d’une famille de joints sur laquelle l’évaluer. Ici, le terme « ligne des pressions » est un
faux-ami, une traduction littérale du terme allemand « Drucklinie », introduisant la
confusion avec les autres acceptions du terme à la même époque. Par ailleurs le terme
« Drucklinie » est également utilisé par Breymann pour traduire le concept de « ligne
de pression ». En eﬀet Breymann intègre une traduction d’une large partie de l’article
de Méry (1840) dans son ouvrage sur la construction en pierre (Breymann, 1849). Le
terme « courbe de pression » de Méry est traduit par Breymann par « Druckcurve ».

En anglais, la « ligne de pression » est traduite par « line of thrust », et le « polygone funiculaire » par « line of pressure », ce qui induit naturellement une confusion
certaine pour les traducteurs.

La comparaison des appellations de plusieurs auteurs est exposée dans la table 1.1.

Déﬁnitions données ici Ligne de pression Polygone funiculaire
Méry (1840) « courbe de(s) pression(s) » ∅– non utilisé
Moseley (1843a) « line of resistance » « line of pressure »
Dupuit (1870) « ligne ou courbe de pression » ∅– non utilisé
Durand-Claye (1880) « courbe de pression » ∅– non utilisé
Culmann (1880) ∅ « polygone funiculaire, ligne
des pressions »
Benvenuto (2006, p. 388) « linea di resistenza » « linea di pressione »
aujourd’hui « ligne de pression » « polygone funiculaire »
aujourd’hui « line of thrust » « funicular polygon »

Table 1.1 – Comparaison des termes désignant la ligne de pression et le polygone
funiculaire

1.3 Comparaison de la ligne de pression et du polygone
funiculaire

La ligne de pression et le polygone funiculaire ont des déﬁnitions distinctes. Cependant, dans le cadre de la statique graphique (5) le second est une étape nécessaire pour
construire les points de la première, et ces deux objets géométriques sont proches :
dans la plupart des cas, les points de la ligne de pression seront localisés sur les
segments du polygone funiculaire.

Cette observation peut être illustrée par plusieurs exemples.
— La ﬁgure 1.2 représente trois cas d’équilibre pour un demi arc en plein-cintre.
Dans la colonne de droite et dans celle du centre sont représentés deux cas
où la ligne de pression et le polygone funiculaire sont proches. En revanche,

Gewölbetheorie, wo alle Seiten des Polygons gepresst sind, heisst es mitunter auch die Drucklinie. Wir
werden beide Ausdrücke gebrauchen, je nachdem die meisten Polygonseiten gespannt oder gepresst
sind. »
(5). Il est à noter cependant qu’avant (Culmann, 1880), première traduction en français de l’ouvrage
de Culmann, la ligne de pression pouvait déjà être dessinée sans recours au polygone funiculaire (p.
ex. Méry, 1840 ; Dupuit, 1870).

23

<!-- p. 25 -->

Chapitre 1. Équilibre des constructions clavées

dans la colonne de gauche est représenté un cas où la ligne de pression et le
polygone funiculaire ne se superposent pas près de la naissance de l’arc.
— Moseley illustre cette diﬀérence en 1843 pour une portion d’arc soumis à la fois
à des forces horizontales et verticales (ﬁg. 1.4, couleurs ajoutées par l’auteur).
— La ﬁgure 1.3 donne l’exemple d’un arc-boutant, où ligne de pression et poly-
gone funiculaire sont presque confondues dans la partie courante de l’arc, et
bien distinctes au niveau de l’élargissement de l’appui de l’arc en pied.
— Dans le cas particulier des joints horizontaux étudié par Dupuit (ﬁg. 1.5
à gauche) sur lequel nous reviendrons ultérieurement, il est intéressant de
noter que le polygone funiculaire se réduit au point m, point d’intersection
commun à l’ensemble des résultantes, alors que la ligne de pression est com-
posée par la suite des points r1, r2, . . . , R. Par ailleurs, le concept de polygone
funiculaire n’est pas utilisé par Dupuit pour tracer ces ﬁgures (6).
La diﬀérence nette qui existe entre la ligne de pression et le polygone funiculaire
sur certains de ces exemples s’explique par l’observation suivante : les centres de pression ne sont pas nécessairement localisés sur le polygone funiculaire. Par déﬁnition,
chaque segment du polygone funiculaire correspond à un joint particulier. L’intersection des lignes prolongeant un segment du polygone funiculaire avec le joint donne le
centre de pression. Le centre de pression peut être placé sur le segment du polygone
des forces, ou bien en dehors de ce segment, sur la ligne qui le prolonge. Par exemple,
sur la ﬁgure de Moseley, le centre de pression e est placé sur la ligne (DE), mais pas
sur le segment [DE] (ﬁg. 1.4).

Un corollaire de cette observation est que le polygone funiculaire peut sortir de
la maçonnerie, alors que tous les centres de pression correspondants sont situés à
l’intérieur de la maçonnerie, ou plus exactement des joints. Cette remarque est essentielle pour trouver des solutions d’équilibre pour les voûtes ayant une stéréotomie
particulière, comme les voûtes d’Abeille et les plates-bandes à joints en X, que nous
étudierons plus en détail ultérieurement (parties 15.3.4 et 16.3.3).

Heyman (2009) a souligné les diﬀérences entre la ligne de pression et le polygone
funiculaire, et les confusions qui pouvaient se produire. Il a également souligné que
ces deux concepts dépendent de la stéréotomie des arcs considérés, ce sur quoi nous
allons revenir dans la section 1.4.

(6). Ce dernier utilise une méthode proche de celle de Méry de 1840, avec la résolution successive
de l’équilibre de l’ensemble des blocs situés au-dessus d’un joint.

24

<!-- p. 26 -->

Chapitre 1. Équilibre des constructions clavées

Cas poussée minimale Cas intermédiaire Cas poussée maximale

Polygone funiculaire Polygone funiculaire Polygone funiculaire

Centres de pression Centres de pression Centres de pression

Superposition Superposition Superposition

Fig 1.2 – Comparaison de la ligne de pression et du polygone funiculaire

25

<!-- p. 27 -->

Chapitre 1. Équilibre des constructions clavées

Fig 1.3 – Comparaison de la ligne de pression (bleu) et du
polygone funiculaire (rouge) sur un exemple d’arc boutant

Fig 1.4 – Ligne de pression en bleu (« line of resistance ») et
polygone funiculaire en rouge (« line of pressure »), d’après Moseley (1843a),
et Heyman (2009)

Fig 1.5 – Inﬂuence du choix des joints sur la ligne de pression d’un piédroit,
d’après Dupuit (1870, Pl. 1)
26

<!-- p. 28 -->

Chapitre 1. Équilibre des constructions clavées

1.4 Inﬂuence de l’appareil sur la ligne de pression

Contrairement au cas du polygone funiculaire qui ne nécessite de connaître que les
points d’application des charges, la détermination de la ligne de pression présuppose
le découpage de la structure à étudier en un certain nombre de blocs, ou de manière
équivalent en 2D le choix d’une famille de joints découpant la structure. Ce choix
constitue l’appareil, parfois également appelé clavage (7), de la structure.

La ligne de pression dépend directement de l’appareil choisi pour l’étude mécanique. Dupuit (8) illustre cette propriété dans le cas d’un piédroit rectangulaire ABCD
soumis uniquement à une force horizontale Q en tête et à son poids propre (Dupuit,
1870 – voir ﬁg. 1.5). Il considère trois familles de joints, qui divisent chacune le piédroit en huit parties égales (de même poids). Le polygone des forces est donc identique
dans les trois cas. Pour une famille de joints horizontaux, la ligne de pression (9) pR
(ﬁgure de gauche) est verticale.

Pour les arcs et voûtes clavées, l’appareil est connu et les blocs de l’étude mécanique doivent correspondre aux blocs réels, les voussoirs ou claveaux. Pour les
structures non clavées, comme les maçonneries en moellons, il est nécessaire de choisir un découpage ﬁctif en blocs pour procéder à l’étude mécanique en utilisant la ligne
des pressions.

Nous reviendrons en détail sur l’inﬂuence de l’appareil, et donc de la coupe des
pierres, sur la résistance des voûtes dans la partie IV consacrée à l’étude mécanique
des constructions clavées.

(7). Sur la déﬁnition et les diﬀérentes acceptions du mot clavage, voir la section 5.1 p. 74.
(8). L’attention apportée par Dupuit à l’inﬂuence des joints sur la forme de la ligne de pression a
été relevée notamment par Huerta Fernández et Aroca Hernández-Ros (1989) et Tarrío (2015).
(9). « Les points r1, r2, . . . , R sont tous situés sur une verticale pR dite ligne de pression. Dans ce
cas particulier, la ligne de pression est droite, mais, dans beaucoup de cas, les points déterminés par
la rencontre de la résultante et de chacun des plans de joint sont en ligne courbe. » Dupuit (1870,
p. 25). La ligne de pression est plus précisément r1R dans le cas présent.

27

<!-- p. 29 -->

Chapitre 2

Stabilité des constructions
clavées

Résumé : Ce chapitre traite de la théorie du calcul à la rupture et de son application
à l’étude de la résistance des constructions clavées. La théorie du calcul à la rupture
sous sa forme générale est d’abord présentée, et les notions de chargement extrême
et de domaine des chargements potentiellement supportables sont introduites. Les
critères de résistances habituellement choisis pour l’application du calcul à la rupture
à la maçonnerie sont ensuite donnés. Il existe diﬀérentes méthodes pour calculer les
solutions d’équilibre qui sont ensuite exploitées dans le cadre du calcul à la rupture.
Ces méthodes sont présentées, ainsi qu’un ensemble de types de constructions en
maçonnerie ou pierre de taille étudiés récemment dans littérature (dômes, escaliers,
roses etc.).

Sommaire
2.1 Le calcul à la rupture . . . . . . . . . . . . . . . . . . . . . . . . . 29
2.1.1 Mécanique des milieux continus tridimensionnels . . . . . 29
2.1.2 Formulation générale . . . . . . . . . . . . . . . . . . . . . 29
2.1.3 Construction de K par l’intérieur . . . . . . . . . . . . . . 31
2.1.4 Approche de K par l’extérieur . . . . . . . . . . . . . . . . 32
2.1.5 Coeﬃcient de rupture, multiplicateur de charge, et coeﬃ-
cient de sécurité . . . . . . . . . . . . . . . . . . . . . . . . 32
2.1.6 Application aux constructions clavées . . . . . . . . . . . . 33
2.1.7 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . 34
2.2 Recherche des solutions d’équilibre stables . . . . . . . . . . . . . 34
2.2.1 Méthodes antérieures au calcul à la rupture . . . . . . . . 34
2.2.2 Résolution analytique . . . . . . . . . . . . . . . . . . . . 34
2.2.3 Méthode des équations d’équilibre discrétisées . . . . . . . 35
2.2.4 Méthode de Delbecq . . . . . . . . . . . . . . . . . . . . . 37
2.3 Exemples de structures étudiées . . . . . . . . . . . . . . . . . . . 38

28

<!-- p. 30 -->

Chapitre 2. Stabilité des constructions clavées

2.1 Le calcul à la rupture

Le calcul à la rupture est un « mode de raisonnement » pour permettre la vériﬁcation du dimensionnement des ouvrages. Selon Salençon (1983, p. 23), « Le calcul
à la rupture est certainement le mode de raisonnement le plus anciennement utilisé
pour tenter d’y apporter une réponse [...]. C’est ce mode de raisonnement que l’on
trouve aussi bien chez Galilée (1638), que chez Coulomb (1773), Culmann (1866), et
qui est à la base de l’épure de Méry (1840), des règles de descentes de charges, etc ; ».
Le calcul à la rupture s’appuie sur la connaissance de trois éléments uniquement :
— la géométrie du système, qui est supposée indéformable ;
— le chargement appliqué au système ;
— la résistance du matériau constitutif.
Il a été appliqué au calcul des structures et à la mécanique des sols.
Nous donnons ici une synthèse de la présentation de Salençon (1983) du calcul
à la rupture. Cette présentation est reprise par diﬀérents auteurs (Oikonomopoulou,
2009 ; Ciblac et Morel, 2014).

2.1.1 Mécanique des milieux continus tridimensionnels

Salençon (1983) présente le calcul à la rupture avec le formalisme des milieux
continus tridimensionnels :
— V est le volume de la structure et S son contour ;
— σ est le tenseur des contraintes de Cauchy ;
— d est le tenseur des vitesses de déformation dérivé de v ;
— −(σ : d) dV est la puissance des eﬀorts intérieurs pour l’élément dV dans le
champ de vitesse v.
Les champs de contrainte statiquement admissibles dans le mode de chargement
étudié sont les champs σ qui satisfont les conditions aux limites sur les contraintes et
les équations d’équilibre pour un état de sollicitation du mode étudié.
Les champs de vitesse cinématiquement admissibles dans le mode de chargement
étudié sont les champs v qui satisfont les conditions aux limites sur les vitesses pour
un état de sollicitation du mode étudié.
Le principe des puissances virtuelles pour l’équilibre statique d’un système s’écrit :

∀σ champ de contrainte statiquement admissible et
∀ˆv champ de vitesse virtuel cinématiquement admissible :
P(i) + P(e) = 0 (2.1)
Z Z
avec P(i) = − [σ(x) : ˆd(x)] dV − [[ˆv(x)]].σ(x).n(x) dΣ (2.2)
V Σ
avec P(e)(Q(σ),ˆv) = Q(σ).˙q(ˆv) (2.3)

2.1.2 Formulation générale

Géométrie, chargement et résistance

Le calcul à la rupture s’applique à des systèmes dont la géométrie, le chargement
et la résistance sont connus. La géométrie de la structure est donnée par son volume

29

<!-- p. 31 -->

Chapitre 2. Stabilité des constructions clavées

V et son contour S. Par hypothèse le mode de chargement dépend linéairement de n
paramètres, et est représenté par le vecteur Q ∈Rn. On désigne par σ(x) le tenseur
des contraintes en un point quelconque de la structure (x ∈V ).
La résistance est donnée sous la forme du domaine admissible pour les contraintes
en chaque point de V . Ce domaine admissible est noté G(x) :

( 1◦ σ(x) /∈G(x) est impossible
(2.4)
2◦ σ(x) ∈G(x) est permis.

Nous faisons les hypothèses suivantes sur le domaine admissible G(x) :

G(x) contient l’état de contrainte nul : σ(x) = 0 ∈G(x) (2.5)

G(x) est convexe (2.6)

Salençon n’utilise que le caractère étoilé de G, notant que la convexité de G est
fréquente mais n’est pas une règle générale.

Notion de stabilité potentielle

Une condition nécessaire de stabilité d’une structure sous un chargement Q est
qu’il existe un champ de contrainte statiquement admissible qui respecte en tout
point le critère de contrainte.

( σ statiquement admissible avec Q
stabilité sous Q ⇒∃σ tel que (2.7)
σ(x) ∈G(x) ∀x ∈V

La condition ci-dessus n’est qu’une condition nécessaire. Elle n’est pas une condition
nécessaire et suﬃsante. On introduit la notion de stabilité potentielle d’une structure
sous un chargement Q par l’équivalence suivante :

( σ statiquement admissible avec Q
stabilité potentielle sous Q ⇔∃σ tel que
σ(x) ∈G(x) ∀x ∈V
(2.8)
Pour illustrer la notion de stabilité potentielle, Salençon utilise dans son cours
un exemple de cadre à six barres. Lorsque la loi de comportement des barres est de
type fragile, des chemins de chargements conduisant à la rupture existent, bien que
les chargements appliqués soient potentiellement supportables.

Chargements potentiellement supportables

Salençon introduit l’ensemble K des chargements potentiellement supportables,
c’est-à-dire des chargements pour lesquels la structure est potentiellement stable. Cet
ensemble est appelé le domaine des chargements potentiellement supportables. Il a les
propriétés suivantes, qui découlent directement des propriétés de G :

K contient le chargement nul : Q = 0 ∈K (2.9)

K est convexe (2.10)

Les chargements appartenant à la frontière de K seront désignés sous le terme de
chargements extrêmes.

30

<!-- p. 32 -->

Chapitre 2. Stabilité des constructions clavées

2.1.3 Construction de K par l’intérieur

La construction de K par l’intérieur exploite la propriété de convexité de K.
Soit Q1 un chargement potentiellement supportable. Soit Qλ = λQ1 un trajet de
charge radial. On recherche le paramètre λ maximal donnant un chargement potentiellement supportable. (ﬁg. 2.1)

Trouver le paramètre maximal qui donne le chargement extrême n’est pas toujours possible en pratique. Cependant tout paramètre λ donnant un chargement potentiellement supportable est une borne inférieure du paramètre maximal recherché.
En conduisant cette recherche pour plusieurs directions de Q, on approche ainsi par
l’intérieur l’ensemble K des chargements potentiellement supportable (ﬁg. 2.2).

Q2

Qλ = λ Q1
Max.
Q1
O
Q1

Fig 2.1 – Construction de K par trajets de charge radiaux, d’après Salençon (1983,
p. 40)

Q2

Qj
Q3

Q1 Q1

Q2

Fig 2.2 – Approximation par l’intérieur de la frontière de K lorsque K est convexe,
d’après Salençon (1983, p. 41)

31

<!-- p. 33 -->

Chapitre 2. Stabilité des constructions clavées

2.1.4 Approche de K par l’extérieur

Approche de K par l’extérieur par les contraintes

L’approche par l’extérieur par les contraintes consiste à chercher des chargements
pour lesquels l’équilibre implique le dépassement de la capacité de résistance du matériau.

Nous n’utiliserons pas cette approche dans cette thèse.

Approche de K par l’extérieur par les vitesses

L’approche de K par l’extérieur par les vitesses est également appelée approche
cinématique par l’extérieur. Elle s’appuie sur le principe des puissances virtuelles, et
introduit la notion de puissance résistante maximale.

Salençon pose les fonctions π suivantes, correspondant à la densité de puissance
résistante maximale :

π(x,ˆd(x)) = sup{σ(x) : ˆd(x) | σ(x) ∈G(x)} (2.11)
π(x,n(x),[[ˆv(x)]]) = sup{[[ˆv(x)]].σ(x).n(x) | σ(x) ∈G(x)} (2.12)

(2.13)

La puissance résistante maximale pour un champ de vitesse virtuel cinématiquement admissible ˆv est :

Z Z
Prm(ˆv) = π(x,ˆd(x)) dV + π(x,n(x),[[ˆv(x)]]) dΣ (2.14)
V Σ

Si il existe un champ de vitesse virtuel ˆv cinématiquement admissible tel que :

Prm(ˆv) \< P(e)(Q,ˆv) = Q.˙q(ˆv) (2.15)

alors Q ne fait pas partie des champs potentiellement supportables.

Le champ de contrainte σ que pris pour calculer la valeur de la fonction π n’est
pas nécessairement un champ statiquement admissible. Il est choisi pour donner la
plus grande valeur possible à la puissance résistante locale.

Dans le cas des arcs clavés, l’approche par l’extérieur consiste à chercher les mécanismes de rupture pour lesquels la puissance résistante maximale des eﬀorts intérieurs
est égale à la puissance du chargement dans le mécanisme considéré.

2.1.5 Coeﬃcient de rupture, multiplicateur de charge, et coeﬃcient
de sécurité

Salençon introduit le coeﬃcient de rupture F(Q) pour un mode de chargement Q
(ﬁg. 2.3). Ce coeﬃcient de rupture est déﬁni tel que QF = F(Q)Q soit un chargement
extrême. Sa déﬁnition est :
F(Q) = max λ (2.16)
λ/λQ∈K

32

<!-- p. 34 -->

Chapitre 2. Stabilité des constructions clavées

Q2
Qλ = λ Q , λ ≥ 0

QF

K
Q
O
Q1

Fig 2.3 – Déﬁnition du coeﬃcient de rupture, d’après Salençon (1983, p. 71)

Nous verrons dans la partie consacrée aux critères de résistance l’application pratique de ce concept de coeﬃcient de rupture.

Le coeﬃcient de rupture est également appelé multiplicateur de charge par Salençon. Il pourrait également être appelé coeﬃcient de sécurité.

2.1.6 Application aux constructions clavées

Le domaine admissible des contraintes G mentionné précédemment est déﬁni par
les critères suivants dans le cas des structures en maçonnerie :

\1. la maçonnerie n’a pas de résistance à la traction ;

\2. la résistance à la compression de la maçonnerie est ﬁnie ;

\3. le critère de résistance au frottement est le critère de frottement sec de Cou-
lomb, la cohésion étant nulle.

L’absence de résistance à la traction implique que la résultante des forces sur un
joint doit se trouver à l’intérieur de l’enveloppe convexe de ce joint.

Une démarche très similaire est adoptée dans le cadre de l’analyse limite, qui étudie les structures composées d’un matériau au comportement élasto-plastique parfait.
Kooharian (1953) propose d’appliquer l’analyse limite à l’étude des arcs clavés en
pierre. Heyman développe cette idée dans un important article pour l’application de
l’analyse limite à la maçonnerie : The Stone Skeleton (Heyman, 1966). Il y propose
trois hypothèses qui ont été très largement reprises depuis pour l’étude des structures
clavées :

\1. la pierre n’a pas de résistance à la traction ;

\2. la résistance à la compression de la pierre est inﬁnie ;

\3. le glissement d’une pierre sur une autre ne peut pas se produire.

Heyman applique les théorèmes de l’analyse limite à l’étude des arcs-boutants et
des voûtes d’ogives (Heyman, 1966), puis aux dômes (1967a) et aux voûtes en éventail (1967b). La synthèse de ses travaux sont publiés dans (Heyman, 1995).

33

<!-- p. 35 -->

Chapitre 2. Stabilité des constructions clavées

2.1.7 Conclusion

Le calcul à la rupture permet de connaître des chargements pour lesquels l’instabilité d’une structure est certaine, dans le cadre des hypothèses de l’étude. Cependant,
pour les chargements potentiellement supportables, la stabilité n’est que potentielle,
et non certaine. Pour obtenir une réponse plus précise, il faut prendre en compte de
nouvelles informations :
— la loi de comportement du matériau constitutif ;
— l’état d’auto-contrainte initial de la structure ;
— l’histoire de chargement de la structure, car la loi de comportement peut en
dépendre ;
— les déformations.

2.2 Recherche des solutions d’équilibre stables

Le calcul à la rupture et l’analyse limite ont été appliqués aux structures en
maçonneries dans la seconde moitié du xxe siècle. Ces théories fournissent un cadre
rigoureux dans lequel de nouvelles méthodes ont pu être formulées.

Les méthodes que nous mentionnons dans la suite ne sont pas des théories indépendantes du calcul à la rupture, mais des moyens de trouver des solutions d’équilibre
qui prennent leur sens grâce à la théorie du calcul à la rupture.

2.2.1 Méthodes antérieures au calcul à la rupture

La plupart des méthodes anciennes de calculs des maçonneries peuvent être réinterprétées dans le cadre de la théorie du calcul à la rupture. L’étude de la poutre
en porte-à-faux par Galilée est peut-être l’exemple le plus ancien et le plus cité (Discours et démonstrations mathématiques concernant deux sciences nouvelles publié en
1638 – ﬁg. 2.4). Cette étude peut être réinterprétée comme une approche statique par
l’extérieur pour déterminer une borne supérieure du chargement extrême d’une telle
poutre selon Salençon. Les travaux de Coulomb sur les murs de soutènement (1773),
la statique graphique mise au point par Culmann (1875), ou encore l’épure de Méry
(1840) permettant de déterminer la ligne de pression d’un arc avant l’avènement de la
statique graphique sont d’autres exemples cités par Salençon de méthodes utilisant le
mode de raisonnement du calcul à la rupture avant que ce dernier soit formellement
établi.

Dans certains cas, les méthodes vues ci-dessous sont simplement l’implémentation
numérique de méthodes plus anciennes.

2.2.2 Résolution analytique

Les solutions d’équilibre nécessaires à l’utilisation du calcul à la rupture peuvent
être obtenues en cherchant les solutions analytiques des équations d’équilibre, en fonction des inconnues hyperstatiques. Une telle résolution n’est possible que pour les géométries les plus simples : piédroits, arcs en plein-cintre, surfaces de révolution etc. Elle
est appliquée par exemple par Heyman (1966) pour étudier les arc-boutants droits,

34

<!-- p. 36 -->

Chapitre 2. Stabilité des constructions clavées

Fig 2.4 – Figure 17 des Discours et démonstrations mathématiques concernant deux
sciences nouvelles de Galilée 1638

par Heyman (1967a) pour étudier les arcs en plein-cintre et les dômes sphériques, et
par Ochsendorf (2002) pour étudier les piédroits et contreforts.

2.2.3 Méthode des équations d’équilibre discrétisées

Nous introduisons la méthode des équations d’équilibre discrétisées par un
exemple. Considérons un arc clavé reposant sur deux appuis. En se donnant la valeur
des trois inconnues hyperstatiques, et en utilisant les équations d’équilibre appliquées
à chaque bloc, les forces intérieures sont déterminées de proche en proche dans l’arc.
Les équations peuvent être écrites sous forme matricielle. La recherche des chargements extrêmes met en jeu ou bien un choix manuel par l’utilisateur des paramètres,
ou en systématisant le processus avec l’optimisation numérique des solutions.

Cette méthode est la plus proche conceptuellement de la statique graphique
du xixe siècle. Si le mode de calcul est numérique et non graphique, les résultats
sont généralement présentés sous leur forme graphique à l’aide de la ligne de pression. Cette approche est utilisée par Smars (2000) et Lau (2006) notamment.

Les opérations nécessaires à l’application de la statique graphique sont des opérations géométriques de base : calculer l’aire d’un polygone, déterminer les intersections
de deux droites, etc. Les logiciels de géométrie dynamique, comme Cabri II Plus (1)
ou Geogebra (2), permettent de mettre en œuvre de façon paramétrique l’ensemble
des tracés pour obtenir une ligne des pressions, puis de rechercher en modiﬁant par
exemple le pôle du polygone des forces une ligne des pressions intérieure à la maçonnerie.

La géométrie dynamique a notamment été utilisée par Ciblac (2008) pour l’enseignement. Certaines méthodes du xixe siècle ont fait l’objet d’implémentation, comme

(1). Logiciel payant, http://www.cabri.com/
(2). Logiciel Open source librement utilisable par des utilisateurs non commerciaux, http://www.
geogebra.org/about

35

<!-- p. 37 -->

Chapitre 2. Stabilité des constructions clavées

celles de Eddy (1877) et Wolfe (1921) par Lau (3) à l’aide du logiciel Cabri Geometry
II (Lau, 2006).
La méthode des équations d’équilibre discrétisées est généralement utilisée pour
les problèmes 2D. En eﬀet dans le cas où la structure à étudier et son chargement
présentent une symétrie par rapport à un plan, il est possible de simpliﬁer l’étude en
se ramenant à l’étude dans le plan, sous l’hypothèse des contraintes planes (cas des
arcs-boutants), ou l’hypothèse des déformations planes (cas des tunnels). Par exemple
la travée d’une église couverte en berceau (ﬁg. 2.5 à gauche) peut être étudiée dans
le plan de symétrie (ﬁg. 2.5 à droite). Dans le cas où la symétrie n’est vraie que
localement, il faut tenir compte des eﬀets de bord. Sur la ﬁgure 2.6 la travée centrale,
en vert, se prête bien à une étude bidimensionnelle, tandis que les travées placées aux
extrémités, en rouge, peuvent être soumises à des eﬀets de bords importants.

Fig 2.5 – Demi-voûte en berceau avec arc-boutant ; vue axonométrique (à g.), et
coupe selon le plan de symétrie (à d.)

Fig 2.6 – Travée présentant une symétrie par rapport à un plan (en vert) ; travée
présentant une symétrie par rapport à un plan seulement localement (en rouge)

Le chargement doit lui aussi être symétrique et ne pas être concentré ponctuellement dans le plan de symétrie. O’Dwyer montre dans le cas d’une voûte en berceau
que l’étude bidimensionnelle dans le cas d’un chargement ponctuel est conservatif : il
est possible de trouver des poussées minimales plus faibles en prenant en compte la
tridimensionnalité du problème (O’Dwyer, 1999).
Une hypothèse simpliﬁcatrice pour tenir compte de la tridimensionnalité du problème d’équilibre tridimensionnel est de le décomposer en une série d’études bidimensionnelles, en découpant la structure par tranches en une série d’arches juxtaposées.

(3). http://web.mit.edu/masonry/wwlau/

36

<!-- p. 38 -->

Chapitre 2. Stabilité des constructions clavées

Cette méthode est mise en avant par Ungewitter et Mohrmann (1901) pour l’étude
des voûtes d’ogives et des dômes. Elle est utilisée par Smars (2000, p. 151) avec l’utilisation d’un logiciel dédié Calipous.
La méthode des réseaux de forces, qui sera présentée en détail dans la prochaine
partie, fait partie des méthodes à équations d’équilibre discrétisées. Précédée par la
méthode des densités de forces (Schek, 1974), la méthode des réseaux de forces a été
développée par O’Dwyer (1999), puis étendue par Block et Ochsendorf sous le nom
de « thrust network analysis » en 2007.

Pour ﬁnir, Tomasoni et D’Ayala ont mis au point une méthode pour les voûtes
en arc-de-cloître en 3D (D’Ayala et Tomasoni, 2008 ; Tomasoni, 2008). Après discrétisation de la voûte en une série de voussoirs, l’équilibre de ces voussoirs est écrite
en fonction de la force dirigée selon les méridiens S, de la force dirigée selon les parallèles H (« hoop forces »), de la force de cisaillement sur les joints des méridiens
Tθx et de la force de cisaillement sur les joints des parallèles Txθ. L’ensemble des
équations d’équilibre des blocs sont exprimées sous la forme d’un système linéaire
d’équations. La maximisation d’une fonction de coût permet de rechercher une solution dont l’ensemble des points d’application des forces sont situés à l’intérieur des
joints.

2.2.4 Méthode de Delbecq

Nous appelons méthode de Delbecq la méthode mise au point par l’ingénieur
du même nom au début des années 1980. Elle a été développée pour fournir un
outil numérique d’évaluation de la capacité portante des ponts en maçonnerie. Elle
explore un ensemble de solutions d’équilibre possibles et choisit la meilleure solution
du point de vue du critère de résistance avec prise en compte de la résistance ﬁnie
de la maçonnerie. Méthode eﬃcace, et qui semble toujours utilisée aujourd’hui par
le Setra (4) avec le logiciel Voûte, elle ne semble cependant pas avoir fait l’objet de
développements ultérieurs.

Delbecq (1983) applique le calcul à la rupture aux ponts en maçonnerie (arches
avec remblai, avec de fortes surcharges d’exploitation). Contrairement à Heyman
(1966), il ne postule pas que la pierre a une résistance à la compression inﬁnie, et
envisage donc la diminution de stabilité due à l’écrasement des voussoirs. Suite à une
étude extensive des formes des lignes de pression des arches avec remblai, Delbecq
produit une méthode qui permet la détermination de l’ensemble des lignes de pression
qui restent comprises à l’intérieur de l’arche, à partir des propriétés des lignes de
pression extrémales. Pour un chargement donné Q, cette méthode donne le coeﬃcient
de rupture F, qui est déﬁni par le chargement minimum Qext = FQ provoquant
l’eﬀondrement. À titre d’exemple, la ﬁgure 2.7 aﬃche en rouge l’ensemble des lignes
de pression intérieures d’un arc simple, trouvées en appliquant la méthode de Delbecq.

(4). Le Setra est le Service d’études sur les transports, les routes et leurs aménagements qui dépend
du ministère de l’Écologie, du Développement durable et de l’Énergie.

37

<!-- p. 39 -->

Chapitre 2. Stabilité des constructions clavées

Fig 2.7 – Ensemble des lignes de pression intérieures d’un arc déterminées avec la
méthode de Delbecq (1983)

2.3 Exemples de structures étudiées

Outre le cas classique des arcs en plein-cintre et des voûtes en berceau, de nombreux types de structures en maçonnerie ont fait l’objet d’une étude ou bien essentiellement graphique (éventuellement informatisée ou sous forme analytique), ou bien
exploitant la théorie du calcul à la rupture, depuis la publication par Heyman du
Stone Skeleton en 1966.

Nous proposons ici une liste non exhaustive d’études concernant des structures
en maçonnerie variées. Les arcs, qui sont présentés par la quasi-intégralité des études
comme exemple introductif, ne sont pas mentionnés ici. Mentionnons cependant la
thèse d’Ochsendorf (2002) qui prend en compte l’eﬀet de la déformation des arcs (par
mécanisme par blocs) sur l’équilibre.

Couvrements de bâtiments — voûtes, ﬂèches

Voûtes en arc de cloître : Tomasoni (2008)

Voûtes d’ogives : Smars (2000), Block et Lachauer (2014a)

Voûtes en éventail : Heyman (1967b), Gil et al. (2010)

Flèches : Heyman (1967b)

Dômes :
— Heyman (1967a) qui calcule leur épaisseur minimale
— Plusieurs étudiants du MIT dans le cadre de mémoire de master ou thèse de
doctorat : Lau (2006), Reese (2008), Zessin (2012). Ces travaux s’intéressent
plus particulièrement aux dômes de Guastavino, selon une technique importée
aux États-Unis depuis l’Espagne à la ﬁn du xixe. Il s’agit de dômes construits
en brique posée à plats, selon une technique similaire à celles des voûtes « à la
Roussillon » que nous détaillerons ultérieurement concernant les voûtes plates.

Élévations de bâtiments — murs, contreforts, tours

Murs : Heyman (1992), Ochsendorf et al. (2004)

Contreforts : Ochsendorf (2002), Ochsendorf et al. (2004)

Tours : Heyman (1992) qui étudie l’eﬀet de leur inclinaison

38

<!-- p. 40 -->

Chapitre 2. Stabilité des constructions clavées

Escaliers

Escaliers à voûte sarrasine : García Ares (2007, 2011), Block (2009), Baratta et Corbi
(2013)

Escaliers suspendus : Como (2013), Marmo et Rosati (2017)

Roses, remplages de baies

Roses : Heyman (2002), Block (2009)

Remplage de baie : Barthel et al. (2003)

Ouvrages d’art — ponts, murs de soutènement

Ponts en maçonnerie : Delbecq (1983)

Murs de soutènement en pierre sèche : Villemus (2004), Colas (2009)

39

<!-- p. 41 -->

Chapitre 3

Critères de résistance

Résumé : Ce chapitre traite de l’utilisation des critères de résistance dans le cadre
du calcul à la rupture. Dans un premier temps, les critères de résistance au niveau
des joints sont considérés. Ces critères permettent de construire les multiplicateurs
de charges, ou coeﬃcients de sécurité, nécessaires à la détermination des domaines
des chargements potentiellement supportables. Plusieurs exemples de critères et coeﬃcients de sécurité associés aux joints sont donnés, lorsque la résistance à la compression des joints est ﬁnie. Le cas particulier du coeﬃcient de sécurité géométrique,
qui ne fait pas partie du cadre rigoureux du calcul à la rupture, est abordé lorsque la
résistance à la compression des joints est considérée inﬁnie. Dans un deuxième temps,
la résistance interne de la pierre est considérée. L’utilisation des propriétés graphiques
des cercles de Mohr pour construire des champs de contrainte constant par morceaux
admissibles vis-à-vis du critère de résistance interne de la pierre sont présentés.

Sommaire
3.1 Critères de résistance des joints . . . . . . . . . . . . . . . . . . . 41
3.1.1 Expressions des critères . . . . . . . . . . . . . . . . . . . 41
3.1.2 Construction des coeﬃcients de sécurité . . . . . . . . . . 42
3.2 Résistance ﬁnie des joints à la compression . . . . . . . . . . . . . 43
3.2.1 Coeﬃcient de sécurité statique . . . . . . . . . . . . . . . 43
3.2.2 Cas avec incertitudes sur la géométrie . . . . . . . . . . . 45
3.3 Résistance inﬁnie des joints à la compression . . . . . . . . . . . . 46
3.3.1 Coeﬃcient de sécurité statique inopérant . . . . . . . . . . 46
3.3.2 Introduction du coeﬃcient de sécurité géométrique . . . . 47
3.4 Résistance interne des pierres . . . . . . . . . . . . . . . . . . . . . 49
3.4.1 Cercles de Mohr . . . . . . . . . . . . . . . . . . . . . . . . 49
3.4.2 Application au claveau d’une plate-bande . . . . . . . . . 50
3.4.3 Outils graphiques pour déterminer des solutions d’équilibre
stables . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 52

40

<!-- p. 42 -->

Chapitre 3. Critères de résistance

3.1 Critères de résistance des joints

3.1.1 Expressions des critères

Nous limitons notre présentation au cas des joints rectangulaires plans. Bien que
ce type de joint soit le plus courant, il existe de nombreux cas de joints polygonaux
(et plans) mais non rectangulaires. Les formules données ci-dessous s’étendent alors
avec les formules habituelles de la résistance des matériaux.

Le cas des joints non plans sort du cadre de notre étude. Par exemple les assises
inférieures et supérieures des voussoirs des dômes hémisphériques sont des surfaces
coniques, et donc correspondent à des joints non plans. Cependant ce type de joint
peut être approximé par un joint plan si les voussoirs sont de taille réduite par rapport
à la taille globale du dôme.
Nous considérons un joint rectangulaire plan, avec b′ son épaisseur et h′ sa hauteur,
et nous nous plaçons dans un repère de coordonnées local x′y′z′ dont l’origine est le
centre du joint, avec l’axe x′ normal au joint, l’axe y′ parallèle au côté b′ et l’axe z
parallèle au côté h′ et orienté vers le bas (ﬁg. 3.1). Nous utiliserons ultérieurement un
autre repère de coordonnées global xyz pour une plate-bande, où l’axe x sera dirigé
selon l’axe de la plate-bande (ﬁg. 3.2).

Fig 3.1 – Axes locaux x′, y′ et z′ Fig 3.2 – Axes globaux x, y et z
d’un joint d’une plate-bande

La contrainte normale σx′x′ et les contraintes tangentielles τx′y′ et τx′z′ sont liées
aux contraintes généralisées (l’eﬀort normal N′, aux eﬀorts tranchants V ′, aux moments de ﬂexion M′ et au moment de torsion T ′) par intégration sur l’ensemble de

41

<!-- p. 43 -->

Chapitre 3. Critères de résistance

la surface du joint S :

h′/2 b′/2 Z Z
N′ = σx′x′ dy′ dz′ (3.1)
−h′/2 −b′/2
h′/2 b′/2
′ Z Z V y = τx′y′ dy′ dz′ (3.2)
−h′/2 −b′/2
h′/2 b′/2
′ Z Z V z = τx′z′ dy′ dz′ (3.3)
−h′/2 −b′/2
h′/2 b′/2 Z Z
M′y = − z′σx′x′ dy′ dz′ (3.4)
−h′/2 −b′/2
h′/2 b′/2 Z Z
M′z = y′σx′x′ dy′ dz′ (3.5)
−h′/2 −b′/2
h′/2 b′/2
′ Z Z T = τx′z′y′ −τx′y′z′ dy′ dz′ (3.6)
−h′/2 −b′/2

Pour simpliﬁer on considère dans la suite que M′y = 0, V y′ = 0 et T ′ = 0, et nous
notons M′ = M′z et V ′ = V z.′ Nous notons N′c = b′h′σc l’eﬀort normal maximal admissible sur un joint, et nous utilisons cette valeur pour créer les valeurs adimensionnées
suivantes :

n′ = N′/N′c (3.7)
2
m′ = M′/N′c (3.8) h′
v′ = V ′/N′c de telle manière que : V ′/N′ = v′/n′ (3.9)

Les critères de résistance sont évalués au niveau des joints entre les blocs, pour les
raisons exposées dans la section précédente. Nous utilisons dans la suite les critères
suivants :

σt ≤σ ≤σc (3.10)
\|τ| ≤µσ (3.11)

Nous considérons dans le cadre de ce travail que la résistance en traction au niveau
du joint est nulle (σt = 0). Le critère de résistance (3.10) devient :

0 ≤σ ≤σc (3.12)

3.1.2 Construction des coeﬃcients de sécurité

Dans le cadre du calcul à la rupture, le critère de résistance choisi pour l’étude
de la stabilité d’une structure est relié à un coeﬃcient de rupture, également appelé
multiplicateur de charge (Salençon, 1983 – voir section 2.1.5 p. 32). Le multiplicateur
de charge est une mesure de la sécurité de la structure vis-à-vis de la charge qui s’y
applique. Il est encore appelé coeﬃcient de sécurité, terme que nous retiendrons pour
la suite de ce document.

42

<!-- p. 44 -->

Chapitre 3. Critères de résistance

Pour les structures en maçonnerie, le critère de résistance est généralement exprimé au niveau du joint. L’hypothèse implicite le justiﬁant est que la résistance de la
pierre est supérieure à celle de l’interface représentée par le joint. Les eﬀorts internes
aux blocs ne sont donc pas pris en compte par les critères de résistance que nous
considérons, bien que cela soit possible dans le cadre du calcul à la rupture.
En pratique, le processus classique suivant, basé sur le travail de Salençon sur
le calcul à la rupture (Salençon, 1983) et son application aux ponts en maçonnerie
par Delbecq (1983), est suivi pour calculer le coeﬃcient de sécurité d’une structure.
Soit Q le chargement, supposé ﬁxé dans la suite. Soit J l’ensemble des joints j de
la structure. Soit ζ le vecteur des paramètres qui déﬁnissent une solution d’équilibre
si la structure est hyperstatique. Le critère considéré ici est un critère local qui doit
être respecté en tout point du joint.
\1. Le critère local est combiné avec une hypothèse sur la répartition des contraintes sur
le joint (contraintes constantes par morceaux, répartition linéaire, etc.), de manière
à donner un coeﬃcient de sécurité local λj(ζ) pour chaque joint j.
\2. L’ensemble des coeﬃcients de sécurité locaux aux joints sont réunis sous la forme
d’un coeﬃcient de sécurité global λJ , dont la valeur est liée à la solution d’équilibre
considérée, c’est-à-dire liée à une valeur du vecteur ζ :

λJ (ζ) = min λj(ζ) (3.13)
j∈J

\3. Le coeﬃcient de sécurité de la structure F pour le chargement considéré Q est
alors déﬁni comme le maximum des coeﬃcients de sécurité globaux pour toutes les
solutions d’équilibre possibles, soit

F(Q) = max λJ (ζ) = max min λj(ζ) (3.14)
ζ ζ j∈J

En résumé, pour tout critère de résistance local formulé pour les joints, un coefﬁcient de sécurité global pour la structure peut être déﬁni.

3.2 Résistance ﬁnie des joints à la compression

3.2.1 Coeﬃcient de sécurité statique

Les critères de résistance (3.12) sur les contraintes normales et ceux (3.11) sur les
contraintes tangentielles au niveau du joint permettent la construction d’un critère
de résistance sur les contraintes généralisées N′, M′ et V ′ s’appliquant sur un joint.
Pour commencer, un champ de contrainte respectant partout le critère de résistance est considéré, et le moment et l’eﬀort normal correspondant sont calculés. Par
simplicité, le champ de contrainte de l’eﬀort normal considéré est constant par morceaux. Il vaut σx′x′ = σc sur un rectangle de largeur b′ et de hauteur ξh′, et est nul
partout ailleurs sur le joint (ﬁg. 3.1).
N′ = ξb′h′σc ⇔ n′ = ξ (3.15)
h′
M′ = N′ (1 −ξ) ⇔ m′ = n′ (1 −ξ) (3.16)
2
V ′ = µξb′h′σc ⇔ v′ = µn′ (3.17)

43

<!-- p. 45 -->

Chapitre 3. Critères de résistance

Ce champ de contrainte est en équilibre avec des contraintes généralisées respectant
les équations suivantes :

h′ N′
M′ = N′ 1 − ⇔ m′ = n′ 1 −n′ en remplaçant ξ (3.18)
2 b′h′σc

Le domaine de résistance étant convexe et comprenant l’état de contrainte nul,
les ensembles d’eﬀorts N′, M′ et V ′ inférieurs à ceux construits ci-dessus sont donc
également statiquement admissibles, ce qui conduit aux critères suivants, et à leurs
équivalents adimensionnés :

N′ M′ ≤h′ N′ 1 − ⇔ m′ ≤n′ 1 −n′ (3.19)
2 b′h′σc
V ′ ≤µN′ ⇔ v′ ≤µn′ (3.20)

La ﬁgure 3.3 représente le domaine de résistance de ce joint.
Ces critères doivent être respectés pour tous les joints. Pour n′, m′ et v′ donnés
et correspondant à un chargement Q posons le facteur multiplicateur λ tel que λn′,
λm′ et λv′ atteignent la frontière d’un des deux critères :

λm′ = λn′ 1 −λn′ (3.21)
λ = 1 −|m′| /n′ (3.22)
n′

Le coeﬃcient de sécurité est alors donné par :
F(Q) = max min 1 −|m′| /n′ (3.23)
joints n′

Cette déﬁnition du critère est exposée puis exploitée par Delbecq (1983) dans le cadre
de sa thèse sur les ponts en maçonnerie. Nous appellerons ce coeﬃcient de sécurité
coeﬃcient de sécurité statique, et le noterons CSS dans la suite. Nous distinguerons :
— CSSj(ζ) le coeﬃcient de sécurité d’un joint correspondant à la solution d’équi-
libre donnée par le vecteur paramètre ζ ;
— CSSJ (ζ) le coeﬃcient de sécurité de la structure correspondant à la solution
d’équilibre donnée par le vecteur paramètre ζ ;
— CSSJ le coeﬃcient de sécurité de la structure, correspondant à la plus grande
valeur atteignable avec une solution d’équilibre.
Ce coeﬃcient de sécurité a les propriétés suivantes :
— si CSSJ > 0, alors pour la solution d’équilibre correspondante, tous les centres
de pression sont localisés à l’intérieur des joints : le coeﬃcient de sécurité
géométrique (que nous déﬁnirons ci-dessous) est supérieur à 1 ;
— si CSSJ = 1, alors pour la solution d’équilibre correspondante, la contrainte
sur le joint atteint en au moins un point la limite de résistance en compres-
sion σ0 ;
— si CSSJ = 2, alors pour la solution d’équilibre correspondante, la contrainte
sur le joint atteint en au moins un point la limite de résistance en compres-
sion σ0/2 ;

44

<!-- p. 46 -->

Chapitre 3. Critères de résistance

— si CSSJ > 1, alors il y a au moins une solution d’équilibre où les contraintes
sur les joints ne sont nulle part supérieures à σ0/CSSJ .
L’inﬂuence de l’hypothèse de la répartition des contraintes sur le domaine de
résistance est étudié pour le cas des joints rectangulaires par Smars (2000, p. 36-51,
87-91).

m′ v′

0,2 0,5 λ(n′,m′) (n′,m′)

(n′,v′) λ(n′,v′)
0 n′ 0 n′
0,2 0,4 0,6 0,8 1 0,2 0,4 0,6 0,8 1

−0,2 −0,5

0.2

0
m

0.5
−0.2
0 0
0.2
0.4
0.6 0.8 v n 1 −0.5

Fig 3.3 – Critères de résistance pour un joint rectangulaire, avec résistance ﬁnie à la
compression

3.2.2 Cas avec incertitudes sur la géométrie

Des incertitudes peuvent régner sur la géométrie : manque d’information sur la
géométrie exacte d’une structure existante, approximations lors de la construction
(même si la géométrie exacte prévue est connue), déformations non prises en compte
par le calcul à la rupture etc.

Il est possible d’introduire un facteur correcteur ε sur la hauteur du joint pour
prendre partiellement en considération cette incertitude. La hauteur du joint considéré dans le calcul devient h′ = εh′. Les critères de résistance vus plus haut deviennent
simplement :

m′ ≤εn′ (3.24)
m′ ≤εn′ 1 −n′/ε (3.25)

45

<!-- p. 47 -->

Chapitre 3. Critères de résistance

La ﬁgure 3.4 indique la modiﬁcation des domaines de résistance dans le cas
où ε = 0,9.

m′
m′ ε = 1.0 ε = 1.0
0,2 ε = 0.9 0,2 ε = 0.9

n′ 0 n′
0,2 0,4 0,6 0,8 1 0,2 0,4 0,6 0,8 1

−0,2 −0,2

Fig 3.4 – Critères de résistance avec et sans incertitudes sur la géométrie

Le coeﬃcient de sécurité est donné par :
F(Q) = max min 1 −|m′| 1 (3.26)
joints εn′ εn′
F(Q) \< CSS(Q) (3.27)

Il n’existe pas de relation de proportionnalité directe entre ce coeﬃcient de sécurité
et celui sans incertitude.

3.3 Résistance inﬁnie des joints à la compression

3.3.1 Coeﬃcient de sécurité statique inopérant

Si la résistance à la compression des joints est négligée, le critère local de résistance
sur les contraintes normales (3.12) devient

0 ≤σ (3.28)

le critère local de résistance sur les contraintes tangentielles (3.11) n’étant pas modiﬁé.

Le critère (3.28) implique les deux conditions équivalentes suivantes sur l’eﬀort
normal N′, le moment M′, et l’excentricité e = M′/N′. En notant h′ la hauteur du
joint et S sa surface :
M′ ≤h′ N′ ⇔ m′ ≤n′ (3.29)
2
\|e| ≤h′ (3.30)
2

Le critère (3.11) implique que :

V ′ ≤µN′ ⇔ v′ ≤µn′ (3.31)

La ﬁgure 3.5 représente le domaine de résistance de ce joint.

Le coeﬃcient de sécurité du calcul à la rupture est inopérant pour ce critère de résistance. En eﬀet, s’il existe un chargement potentiellement supportable Q1, le critère

46

<!-- p. 48 -->

Chapitre 3. Critères de résistance

m′ v′

0,2 0,5

0 n′ 0 n′
0,2 0,4 0,6 0,8 1 0,2 0,4 0,6 0,8 1

−0,2 −0,5

Fig 3.5 – Critères de résistance pour un joint rectangulaire, avec résistance inﬁnie à
la compression

est respecté en tout joint. Les contraintes généralisées λN′ et λM′ respecteront alors
encore le critère pour le chargement λQ1, qui sera donc potentiellement supportable
quelle que soit la valeur de λ > 0.

F(Q1) = ∞ si ∃Q1 potentiellement supportable (3.32)

Ce phénomène apparaît également lorsque la résistance à la compression des
joints σ0 est très grande (mais non inﬁnie) par rapport aux contraintes dans la structure. Le coeﬃcient de sécurité statique ne donne qu’une information binaire sur la
stabilité (stable / non stable). Cette valeur peut d’ailleurs être trompeuse : le coeﬃcient de sécurité statique CSSJ peut être très élevé, et dans le même temps la valeur
du coeﬃcient de sécurité géométrique CSGJ proche de 1.
Pour éviter ce type de problème, Delbecq (1983, p. 162) applique un coeﬃcient de
sécurité réducteur à l’épaisseur de la voûte à prendre en compte pour le calcul. Il justiﬁe l’application de ce coeﬃcient, compris entre 0,9 et 1,0 par la nécessité de prendre en
compte les incertitudes existant sur l’épaisseur réelle des voûtes. Quand le coeﬃcient
de sécurité réducteur de 0,9 est appliqué à l’épaisseur des voûtes, cette précaution
garantie que le coeﬃcient de sécurité géométrique sera au moins de 1/0,9 = 1,11, à
partir du moment où le coeﬃcient de sécurité statique est positif.

3.3.2 Introduction du coeﬃcient de sécurité géométrique

Déﬁnition théorique

Un autre coeﬃcient de sécurité est utilisé dans le cas où la résistance à la traction
est nulle, et la résistance à la compression considérée inﬁnie : le coeﬃcient de sécurité géométrique. Ce coeﬃcient de sécurité tel qu’il est déﬁni par Heyman n’est pas
construit de la même façon que les coeﬃcients de sécurité du calcul à la rupture.

En eﬀet, Heyman déﬁnit le coeﬃcient de sécurité géométrique comme le rapport
entre l’épaisseur de l’arc considéré et l’épaisseur minimale pour laquelle l’arc est
stable (Heyman, 1969 ; 1995, p. 21). La détermination de la valeur de ce coeﬃcient
de sécurité nécessite de déterminer l’épaisseur minimale de la structure pour pouvoir
ensuite la relier à l’épaisseur réelle de la structure (ﬁg. 3.6).

47

<!-- p. 49 -->

Chapitre 3. Critères de résistance

Fig 3.6 – Arc stable (a), et arc d’épaisseur minimale (b), (c), d’après Heyman (1995,
p. 21)

Estimation numérique

Il est possible de calculer une estimation du coeﬃcient de sécurité géométrique
théorique déﬁni par Heyman, en utilisant les mêmes processus calculatoires que ceux
utilisés pour les autres coeﬃcients de sécurité du calcul à la rupture déﬁni précédemment.

Un coeﬃcient de sécurité géométrique local est déﬁni comme le rapport entre la
demi-hauteur du joint h/2, et l’excentricité du centre de pression sur le joint e, soit :

h′ h′
λj = = (3.33)
2e |2M′/N′|

L’estimation du coeﬃcient de sécurité géométrique de la structure est alors déﬁnie
comme le maximum des coeﬃcients de sécurité globaux :

F = max λJ = max min λj (3.34)
ζ ζ j∈J

Nous noterons cette estimation du coeﬃcient de sécurité géométrique CSG dans
la suite. La convergence de cette estimation vers le coeﬃcient de sécurité géométrique
théorique dans le cas des arcs et des dômes (section 14.1 p. 239). Nous notons :
— CSGj(ζ) = λj(ζ) le coeﬃcient de sécurité d’un joint correspondant à la solu-
tion d’équilibre donnée par le vecteur paramètre ζ ;
— CSGJ (ζ) le coeﬃcient de sécurité de la structure correspondant à la solution
d’équilibre donnée par le vecteur paramètre ζ ;
— CSGJ le coeﬃcient de sécurité de la structure, correspondant à la plus grande
valeur atteignable avec une solution d’équilibre.
Si la résistance à la compression des joints σ0 est très grande par rapport aux
contraintes dans la structure, ce coeﬃcient de sécurité a les propriétés suivantes :
— Pour une solution d’équilibre avec un coeﬃcient de sécurité géométrique
CSGJ = 1, le coeﬃcient de sécurité statique CSSJ est nul ;
— Pour une solution d’équilibre avec un coeﬃcient de sécurité géométrique
CSGJ > 1, le coeﬃcient de sécurité statique CSSJ est +∞;
— Pour une solution d’équilibre avec un coeﬃcient de sécurité géométrique
CSGJ \< 1, le coeﬃcient de sécurité statique CSSJ est −∞.
O’Dwyer introduit un coeﬃcient de sécurité géométrique (« geometric factor of
safety »), similaire au coeﬃcient présenté ici, mais qui est exprimé à partir de la
position du polygone funiculaire (ou de façon équivalente du réseau de forces) par
rapport aux limites de la maçonnerie (O’Dwyer, 1999 – ﬁg. 3.7). Cette déﬁnition,

48

<!-- p. 50 -->

Chapitre 3. Critères de résistance

qui ne fait pas intervenir les joints, ne converge pas exactement vers le coeﬃcient de
sécurité géométrique théorique, pour des raisons analogues à celles analysées sur la
diﬀérence entre ligne de pression et polygone funiculaire (voir section 1.3 p. 23).

Fig 3.7 – Coeﬃcient de sécurité géométrique D/d, d’après O’Dwyer (1999)

3.4 Résistance interne des pierres

3.4.1 Cercles de Mohr

Les eﬀorts internes aux pierres ne sont pas pris en considération dans les critères
de résistance présentés jusqu’à présent, puisque ces derniers ne concernent que la
résistance au niveau des joints. Dans cette section, nous considérons au contraire que
la résistance de la pierre elle-même est limitée. La construction des solutions d’équilibre nécessaires pour l’approche par l’intérieur du calcul à la rupture ne peut plus
concerner uniquement les états de contraintes au niveau des joints. Il est nécessaire
de trouver pour chaque claveau un champ de contrainte interne admissible.
Une approche possible est d’exploiter les propriétés graphiques des cercles de
Mohr (1) pour construire de tels champs de contrainte. Ce type de méthode est notamment utilisée dans le cadre de l’étude de la résistance des sols.
Les conventions usuelles des cercles de Mohr utilisent la traction positive. Avec
cette convention, les contraintes sont représentées sur la ﬁgure 3.8. Nous utilisons dans
ce document la convention usuelle pour les maçonneries, avec compression positive,
ce qui nécessite d’adapter la représentation des cercles de Mohr comme indiqué sur
la ﬁgure 3.9, en dirigeant vers le haut l’axe τ.
Nous rappelons les principes de bases pour l’exploitation du cercle de Mohr.
Connaissant les contraintes σ11, σ22 et σ12 = σ21 exprimées dans le repère géométrique y1y2, le cercle de Mohr décrivant l’état de contrainte correspondant est le cercle
de centre C = (σ11+σ22 ; 0) et passant par le point P ∗= (σ11; −σ12). Le point P ∗est 2
appelé pôle du cercle de Mohr.

(1). Les cercles de Mohr sont nommés après Otto Mohr (1835-1918), qui présenta leur utilisation
en 1882 pour la représentation graphique des contraintes. Culmann avait déjà présenté en 1866 dans
son livre sur la statique graphique les cercles de contraintes (« circle of stress »), un cas particulier
des cercles de Mohr, mais qui comprenait déjà les principes de bases que nous utiliserons ici : le pôle
et l’inclinaison de la facette donnant les contraintes sur la facette (Timoshenko, 1953, p. 194-195, 285286).

49

<!-- p. 51 -->

Chapitre 3. Critères de résistance

Soit nv un repère géométrique obtenu par rotation d’un angle α du repère géométrique y1y2. Les composantes des contraintes dans ce repère sont obtenues par
la rotation d’angle 2α et de centre C du point Q0 = (σ11; σ12), donnant ainsi le
point Qα = (σn; σnv) sur la ﬁgure 3.9.
Par ailleurs, les contraintes s’appliquant sur une facette élémentaire sont obtenues
en cherchant l’intersection de la droite parallèle à cette facette passant par le pôle P ∗
d’une part, et le cercle de Mohr d’autre part.

Les contraintes principales de l’état de contrainte sont données par l’intersection
du cercle avec l’axe τ = 0, donc ici les points M = (σ1; 0) et N = (σ2; 0). Les coordonnées du centre C du cercle de Mohr s’expriment également sous la forme (σ1+σ2 ; 0). 2

P ∗= (σ11; −σ12)
• (σ22; σ21) •

y2

σ22
N M σ
• • • σ21
( σ11+σ222 ; 0) = C 2γ σ12 σ11
2α
• Qα = (σn; τnv)

y1
• Q0 = (σ11; σ12)

z2 v y2
σ2 . .
σ22 . .
σ11
. . z1
γ σ1 n . .
y1
τ α

Fig 3.8 – Cercle de Mohr, convention de signe avec traction positive,
d’après Sollazzo et Marzano (1988)

3.4.2 Application au claveau d’une plate-bande

Nous considérons un claveau de plate-bande soumis à un chargement surfacique
vertical uniforme q sur sa face supérieure, et à un chargement (σ, τ) sur la partie
supérieure d’un joint latéral (ﬁg. 3.10).

Nous cherchons un champ de contrainte constant par morceaux qui respecte à la
fois :
— le critère de résistance interne de la pierre ;
— les conditions aux bords données par le chargement.
Le découpage en quatre zones 1, 2, 3 et 4 où les contraintes sont constantes par zone
est donné sur la ﬁgure 3.10. Les données d’entrée du problème sont les valeurs q, σ
et τ. Les inconnues à déterminer sont à la fois la position des frontières délimitant les

50

<!-- p. 52 -->

Chapitre 3. Critères de résistance

τ

• Q0 = (σ11; σ12)
y2

• Qα = (σn; τnv)
2α σ22
( σ11+σ222 ; 0) = C 2γ M σ σ21
• • • σ12
N σ11

y1
• (σ22; σ21) •
P ∗= (σ11; −σ12)
z2 v y2

σ2 . .
σ22 . .
σ11 z1
. . γ
σ1 n
. . y1
α

Fig 3.9 – Cercle de Mohr, convention de signe avec compression positive (utilisée
pour ce document), d’après Sollazzo et Marzano (1988)

Chargement vertical q

2 Chargement
1 (σ, τ)

3

Chargement
(0, 0)
4

Fig 3.10 – Schéma de principe du découpage d’un claveau en champ de contrainte
constant par morceaux

51

<!-- p. 53 -->

Chapitre 3. Critères de résistance

champs de contrainte constants, et la valeur de chacun de ces champs de contrainte
constants.

Nous utilisons un logiciel de géométrie dynamique, GeoGebra, pour résoudre ce
problème. La construction de tels champs nécessite de pouvoir trouver des solutions
aux deux sous-problèmes suivants :
— la détermination d’un cercle de Mohr connaissant deux points de ce cercle et
la direction d’une interface correspondant à un de ces points ;
— la détermination d’un cercle de Mohr à partir de l’équilibre sur une interface
avec un premier cercle de Mohr
Nous présentons ci-dessous deux outils graphiques permettant de trouver les solutions de ces problèmes.

3.4.3 Outils graphiques pour déterminer des solutions d’équilibre
stables

Outil1 : Détermination d’un cercle à partir de deux points et une
direction

Le premier outil permet, connaissant la contrainte sur une interface (1 point A et
une direction dir.A) et la contrainte pour une autre interface (1 point B correspondant
à une interface de direction dir.B non connue), de déterminer le cercle de Mohr et
son pôle P (ﬁg. 3.11).

L’outil 1 fonctionne comme suit. Le point C est l’intersection entre l’axe x et la
médiatrice du segment [AB]. Le cercle de Mohr recherchée est le cercle de centre C
passant par A. Par construction, ce cercle passe également par B. Le pôle P est
obtenu en traçant l’intersection entre le cercle d’une part, et la droite parallèle à la
direction dir.A et passant par A.

τ τ τ B B B
• • •

A A A
• • •
C C
• •
σ σ σ

• P dir.(A) dir.(A) dir.(A)
données connues résolution graphique résultat

Fig 3.11 – Outil 1, détermination d’un cercle de Mohr à partir de deux points et une
direction

Outil2 : Détermination d’un second cercle à partir de l’équilibre sur
une interface

Deux champs de contrainte constants par morceaux sont en équilibre le long d’une
frontière de direction P1P2 inconnue. Les informations connues sont :
— le cercle de Mohr c1 du domaine 1 y compris la position du pôle P1 ;

52

<!-- p. 54 -->

Chapitre 3. Critères de résistance

— un point A du cercle c2 ;
— la direction de l’interface correspondant au point A.
Les informations recherchées sont :
— le cercle de Mohr c2 du domaine 2 et la position de son pôle P2 ;
— la direction de l’interface permettant l’équilibre entre les domaines 1 et 2, et
le point correspondant à cette interface sur les cercles c1 et c2.
L’outil 2 fonctionne comme suit. On se donne un point Da arbitraire sur le
cercle c1. Soit Ea l’intersection de la droite P1Da avec la direction donnée passant
par A. On trace les médiatrices des segments DaA et DaEa, qui s’intersectent en
un point Fa. La même construction est réalisée pour un second point Db arbitraire
sur le cercle c1, conduisant à la détermination d’un point Fb. La droite FaFb coupe
l’axe des abscisses en un point C2 qui est le centre du cercle recherché. Connaissant
le centre C2 et le point A, le cercle c2 est donc connu. Le pôle P2 est l’intersection
avec le cercle de la droite connue passant par A. Les cercles C1C2 et la droite P1P2
s’intersectent en un point unique, qui correspond à la contrainte le long de la frontière
entre 1 et 2, dont la direction est P1P2.

53

<!-- p. 55 -->

Chapitre 3. Critères de résistance

τ données connues

c1

A

C1 σ

P1

τ résolution graphique
Fb Eb

c1 Db

A

Fa

C1 C2 σ
Ea

Da

P1

τ résultat

c2
c1

A

C1 C2 σ

P2

Inter12
P1

Fig 3.12 – Outil 2, détermination d’un second cercle de Mohr à partir de l’équilibre
sur une interface

54

<!-- p. 56 -->

Chapitre 4

Méthode des réseaux de forces

Résumé : Ce chapitre présente successivement la méthode des densités de forces,
puis la méthode des réseaux de forces appliquée aux voûtes en maçonnerie. Ces deux
méthodes expriment l’équilibre d’un système sous la forme d’un réseau, formé de
nœuds où s’appliquent le chargement, et de branches reliant les nœuds et par où
transitent les forces. Les réseaux de forces étendent sous forme de réseau la notion
de polygone funiculaire de la statique graphique. Leur intérêt pour la maçonnerie a
été mis en avant par O’Dwyer (1999) sous le nom de « force network method », et
étendue par Block et Ochsendorf (2007) sous le nom de « thrust network analysis ». Ils
seront utilisés ultérieurement dans cette thèse pour générer les solutions d’équilibre
des constructions clavées étudiées.

Sommaire
4.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 56
4.2 Méthode des densités de forces . . . . . . . . . . . . . . . . . . . . 56
4.2.1 Concepts et hypothèses . . . . . . . . . . . . . . . . . . . . 56
4.2.2 Connectivité du réseau . . . . . . . . . . . . . . . . . . . . 58
4.2.3 Notations . . . . . . . . . . . . . . . . . . . . . . . . . . . 58
4.2.4 Mise en équation de l’équilibre . . . . . . . . . . . . . . . 59
4.2.5 Recherche d’une solution admissible . . . . . . . . . . . . 61
4.3 Méthode des réseaux de forces . . . . . . . . . . . . . . . . . . . . 61
4.3.1 Origine de la méthode . . . . . . . . . . . . . . . . . . . . 61
4.3.2 Hypothèses . . . . . . . . . . . . . . . . . . . . . . . . . . 62
4.3.3 Principe de résolution pour les structures existantes . . . 62
4.3.4 Notations . . . . . . . . . . . . . . . . . . . . . . . . . . . 66
4.3.5 Mise en équation de l’équilibre . . . . . . . . . . . . . . . 66
4.3.6 Recherche des solutions d’équilibre admissibles . . . . . . 69

55

<!-- p. 57 -->

Chapitre 4. Méthode des réseaux de forces

4.1 Introduction

Les réseaux de forces étendent sous forme de réseau la notion de polygone funiculaire de la statique graphique, de la même manière que la résille caténaire inversée,
notamment utilisée par Antoni Gaudí, généralise la caténaire inversée.

Schek (1974) a introduit la méthode des densités de forces, permettant de concevoir des réseaux de forces utilisables dans le cadre de la conception de nouvelles
structures en compression ou en traction.

L’intérêt des réseaux de forces pour l’étude de la stabilité des voûtes en maçonnerie
a été mis en avant par O’Dwyer (1999). Un réseau de forces est une solution d’équilibre
admissible qui peut être utilisée dans le cadre du calcul à la rupture pour l’étude de
la stabilité des voûtes. O’Dwyer a proposé une méthode pour générer les réseaux de
forces adaptés aux voûtes en maçonnerie : la méthode des réseaux de forces (« the
force network method »).

Cette méthode a été étendue par Block et Ochsendorf (2007) sous le nom de
« thrust network analysis », avec l’introduction des ﬁgures réciproques (Maxwell,
1864 ; Culmann, 1864 ; Cremona, 1872). Elle a été utilisée pour mettre au point des
outils d’optimisation de forme (Rippmann, 2016). Plusieurs avancées et extensions
ont été publiées ces dernières années concernant les procédure d’optimisation (Vouga
et al., 2012 ; Block et Lachauer, 2014b) et les formulations variationnelles du problème
mécanique (Fraternali, 2010 ; De Goes et al., 2013). Elle a également fait l’objet d’un
développement par Gil et al. (2010), dans laquelle les branches du réseau de forces
sont remplacées par des barres élastiques, et l’équilibre résolu par une méthode utilisant des éléments ﬁnis.

La méthode des réseaux de forces a été appliquée pour l’étude de constructions
historiques en maçonnerie : voûtes en éventail (Block et Ochsendorf, 2008), voûtes
d’ogives gothiques, les rosaces, escaliers sur voûte sarrasine (Block, 2009 ; Block et
Lachauer, 2014a). Cependant le domaine d’application principal de la méthode est
la conception de structures en compression innovantes. Elle a prouvé être un outil
adéquat pour les processus de recherche de forme (Rippmann et al., 2012). Nous
nous plaçons dans la suite de ce document dans le cadre de la méthode appliquée
à la vériﬁcation des constructions clavées existantes, pour laquelle la géométrie des
claveaux, et donc des joints, est connue.

Nous présentons dans ce chapitre d’abord la méthode des densités de forces, pour
mettre en lumière ensuite les points communs et diﬀérences lors de la présentation
de la méthode des réseaux de forces appliquée aux voûtes en maçonnerie.

4.2 Méthode des densités de forces

4.2.1 Concepts et hypothèses

La méthode des densités de forces est présentée par Schek (1974). Elle permet de
créer des réseaux de forces équilibrés, en tension ou en compression. Les réseaux comportent des nœuds, reliés par des branches. Deux types de nœuds sont considérés, les
nœuds intérieurs (« interior nodes »), dont la position dans l’espace est une inconnue

56

<!-- p. 58 -->

Chapitre 4. Méthode des réseaux de forces

du problème, et les nœuds d’appuis (« boundary nodes » ou « ﬁxed nodes »), dont la
position dans l’espace est ﬁxe.

Les hypothèses fondamentales de la méthode sont les suivantes :
— la ligne d’action de la force entre deux nœuds passe par la branche qui les
relient ;
— les connections entre les branches au niveau des nœuds ne transmettent aucun
moment ;
— les chargements extérieurs s’appliquent uniquement sur les nœuds.
La méthode nécessite de connaître à chaque étape du calcul :
— la position des nœuds d’appuis ;
— le coeﬃcient de proportionnalité entre la force et la longueur de chaque
branche ;
— les charges extérieures s’appliquant sur les nœuds.
Les coeﬃcients de proportionnalités sont appelés densités de forces. La méthode des
densités de forces en tire son nom.

La résolution de l’équilibre permet d’exprimer la position de l’ensemble des nœuds
intérieurs du réseau à travers un système d’équations linéaires dépendant des positions
des nœuds d’appuis, des densités de forces pour toutes les branches, et du chargement
extérieur.

Autrement dit, si le chargement est donné ainsi que les conditions aux limites
(positions des nœuds d’appuis), la forme géométrique du réseau est exprimée en
fonction d’un seul type de paramètre : les densités de forces des branches (ﬁg. 4.1).

Fig 4.1 – Diagramme de la méthode des densités de forces

En faisant varier les valeurs des densités de forces dans les branches, la méthode
permet d’explorer l’ensemble des solutions d’équilibre possibles pour un réseau. Des
conditions complémentaires peuvent être ajoutées pour rechercher des réseaux de
forces possédant des propriétés spéciﬁques :

57

<!-- p. 59 -->

Chapitre 4. Méthode des réseaux de forces

— conditions sur la longueur des branches, soit dans l’état avant chargement
(barre ou câble au repos) ou après chargement (barre ou câble étiré ou com-
primé suivant une loi élastique linéaire) ;
— conditions sur les forces dans les branches ;
— combinaison des deux types de conditions précédentes.
La recherche de réseaux spéciﬁques introduit des équations non linéaires fonctions uniquement des densités de forces dans les nœuds, pour lesquelles Schek (1974)
propose une méthode de résolution itérative.
Par construction, l’équilibre des forces à chaque nœud entraîne l’équilibre des
moments, puisque les branches s’y réunissent en un point.

4.2.2 Connectivité du réseau

Le réseau est considéré sous forme de graphe orienté pour les nécessités d’implémentation numérique du calcul, et la connectivité entre les nœuds et les branches du
réseau peut être transcrite sous forme matricielle avec la matrice de connectivité C
(« branch-node matrix », voir ﬁg. 4.2) :

 1 si le nœud j est le nœud de tête de la branche i
 C(i,j) = −1 si le nœud j est le nœud de queue de la branche i (4.1)
 0 dans les autres cas

En numérotant les nœuds pour avoir en premier les nœuds intérieurs, puis les nœuds
d’appui, cette matrice peut s’écrire sous la forme d’une matrice par blocs avec Ci
et Cb les sous-matrices correspondant respectivement aux nœuds intérieurs et nœuds
d’appuis :
C = Ci ... Cb (4.2)

Ce formalisme est utilisé notamment par Schek (1974) pour la méthode des densités
de forces, et par Block (2009) pour la méthode des réseaux de forces.

4.2.3 Notations

Soit i et b les indices indiquant les quantités correspondant respectivement à un
nœud intérieur ou à un nœud d’appui (« boundary »). Soit n = ni + nb le nombre de
nœuds, et m le nombre de branches du réseau.
Le détail des quantités utilisées pour les calculs et les relations qui les lient sont
les suivantes :
— x, y et z les coordonnées cartésiennes des nœuds ;
— u, v et w les composantes des branches (vecteurs orientés) ; √
— l = u2 + v2 + w2 la longueur des branches ;
— s la force axiale des branches ;
— q = s/l la densité de force dans les branches ;
— px, py et pz les composantes du chargement extérieur.
Aﬁn de les distinguer des scalaires, les matrices sont notées par des lettres capitales
en gras, et les vecteurs par des lettres minuscules en gras. Les vecteurs suivants, déﬁnis
sur la base des quantités précédentes, seront utilisés :

58

<!-- p. 60 -->

Chapitre 4. Méthode des réseaux de forces

Fig 4.2 – Matrice de connectivité (« branch-node matrix »), d’après Schek (1974)

— x, y et z les vecteurs de dimension n obtenus avec les coordonnées x, y et z
de l’ensemble des nœuds ;
— px, py et pz les vecteurs de dimension ni obtenus avec les composantes px, py
et pz du chargement s’appliquant à chaque nœud intérieur ;
— u, v et w les vecteurs de dimension m obtenus avec les composantes u, v et w
de l’ensemble des branches ;
— l, s et q les vecteurs de dimension m obtenus avec les quantités l, s et q de
l’ensemble des branches.
Nous utilisons la notation simpliﬁée suivante pour la correspondance entre un
vecteur et la matrice diagonale qui peut y être associée :

 u1  u1 0 0 0 
u2 0 u2 0 0  
u = ... ↔U = 0 0 ... 0 (4.3)  
0 0 0 un un  

La multiplication d’un vecteur avec une matrice diagonale présente la propriété suivante, qui sera exploitée dans la suite : Uv = V u.

4.2.4 Mise en équation de l’équilibre

En utilisant les propriétés de la matrice de connectivité C, les composantes des
branches orientées s’écrivent simplement en fonction des coordonnées des nœuds :

u = Cx (4.4)

v = Cy (4.5)

w = Cz (4.6)

59

<!-- p. 61 -->

Chapitre 4. Méthode des réseaux de forces

Les forces s dans les branches étant parallèles à ces dernières, leurs composantes
s’écrivent :

UL−1s composantes des forces s suivant l’axe x (4.7)
V L−1s composantes des forces s suivant l’axe y (4.8)
W L−1s composantes des forces s suivant l’axe z (4.9)

Les équations d’équilibre de l’ensemble des nœuds intérieurs s’écrivent :
CtiUL−1s + px = 0 (4.10)
CtiV L−1s + py = 0 (4.11)
CtiW L−1s + pz = 0 (4.12)

Les inconnues dans ces systèmes d’équations sont les coordonnées des nœuds x, y
et z, et donc les quantités U, V , W , L−1 et s qui en dépendent. Ces systèmes
d’équations sont non linéaires car ils font intervenir les termes du type UL−1s. Ils
sont linéarisés en introduisant les densités de forces q qui sont connus à chaque étape
du calcul (nous reviendrons sur le principe du calcul itératif ultérieurement) :

q = L−1s (4.13)

Après injection de cette équation dans les équations d’équilibre, et utilisation des
propriétés du type Uq = Qu, on obtient :
CtiQCx + px = 0 (4.14)
CtiQCy + py = 0 (4.15)
CtiQCz + pz = 0 (4.16)

La matrice D et ses sous-matrices Di et Db sont introduites pour simpliﬁer les
notations :
D = CtiQC (4.17)
Di = CtiQCi (4.18)
Db = CtiQCb (4.19)

Les positions des nœuds intérieurs sont tirées des systèmes d’équations linéaires suivants :

Dixi = −px −Dbxb (4.20)
Diyi = −py −Dbyb (4.21)
Dizi = −pz −Dbzb (4.22)

Ces systèmes montrent que les positions des nœuds intérieurs xi, yi et zi sont données
en fonction des positions des nœuds d’appuis xb, yb et zb, du chargement extérieur
px, py et pz, et des densités de forces q.
Les longueurs des branches, puis les forces dans les branches sont ensuite données
par :

q
L = U tU + V tV + W tW (4.23)

s = Lq (4.24)

60

<!-- p. 62 -->

Chapitre 4. Méthode des réseaux de forces

4.2.5 Recherche d’une solution admissible

Pour trouver une solution admissible, c’est-à-dire ici respectant un ensemble de
conditions formulées sur les longueurs des branches ou les forces dans les branches,
Schek (1974) utilise des méthodes itératives.

Il montre que les conditions sur les longueurs de branches et sur les forces dans
les branches peuvent être exprimées uniquement en fonction des densités de forces q.
L’incrément ∆qj à ajouter à chaque itération j aux densités de forces qj est ensuite
exprimé de façon explicite. Un calcul itératif permet alors de chercher la solution qui
respecte les conditions recherchées (ﬁg. 4.3).

Fig 4.3 – Diagramme de recherche itérative des réseaux de densités de forces

4.3 Méthode des réseaux de forces

4.3.1 Origine de la méthode

La méthode des réseaux de forces permet de produire, comme la méthode des
densités de forces, des réseaux de forces. Cependant, elle utilise une hypothèse complémentaire par rapport à la méthode des densités de forces : la projection des nœuds
sur le plan horizontal est ﬁxée.

L’utilisation de cette hypothèse pour l’étude des structures tendues est antérieure
à l’article de O’Dwyer (1999) (p. ex. Majowiecki, 1994). Cependant, l’intérêt des
réseaux de forces dans le cadre de l’étude des voûtes en maçonnerie est mis en avant
par O’Dwyer (1999), qui expose sa formulation de la méthode sans faire référence à
la méthode des densités de forces.

L’hypothèse complémentaire sur la position des nœuds dans le plan horizontal
induit que les solutions d’équilibre produites par la méthode des réseaux de forces

61

<!-- p. 63 -->

Chapitre 4. Méthode des réseaux de forces

est une sous-classe des solutions d’équilibre produites par la méthode des densités de
forces (1).

Cette hypothèse complémentaire présente deux avantages :
— dans le cadre de l’étude de la stabilité des constructions en maçonnerie, elle
permet de réduire le champ des solutions d’équilibre possibles à celles qui sont
utiles dans ce cadre, c’est-à-dire aux réseaux dont la projection horizontale
coïncide avec celle des centres de gravité des blocs (O’Dwyer, 1999) ;
— de façon générale (étude des constructions existantes ou optimisation de
forme), elle permet d’introduire lors du processus de calcul la dualité entre
le réseau projeté, qui est une forme d’équilibre, et sa forme duale qui est le
diagramme des forces (Block, 2009).
Cette hypothèse modiﬁe également le processus de résolution de l’équilibre :
— les équations d’équilibre dans le plan horizontal ne servent plus à déterminer
la position des nœuds, mais elles introduisent des relations entre les diﬀérentes
densités de forces dans chaque branche, ce qui est la traduction de la limitation
des solutions d’équilibre accessibles, et en même temps permet l’introduction
des ﬁgures réciproques ;
— les distances horizontales entre les nœuds étant ﬁxées, la donnée des densités
de forces devient de fait la donnée des forces horizontales dans les nœuds (2).

4.3.2 Hypothèses

Nous nous plaçons dans le cadre de la vériﬁcation des constructions existantes pour
la présentation de la méthode des réseaux de forces. Les trois hypothèses suivantes
sont requises pour permettre l’utilisation de la méthode :

\1. l’ensemble des droites d’actions des forces s’appliquant sur un bloc s’inter-
sectent en un point ;
\2. l’ensemble des charges extérieures (3) sur le système sont des charges verticales ;

\3. les blocs intérieurs et les blocs d’appuis sont inﬁniment rigides, de façon à ce
que l’équilibre puisse être écrit sur la géométrie initiale du système.

L’hypothèse 2 peut être remplacée par celle d’avoir un ensemble de charges parallèles, ce qui permet ensuite de choisir comme axe vertical du repère un axe parallèle
à ces charges (Block et Lachauer, 2014b).

4.3.3 Principe de résolution pour les structures existantes

Nous présentons le principe de résolution de la méthode des réseaux de forces
appliquée à une construction existante avant de présenter les calculs correspondants.
Nous utilisons dans la suite l’exemple d’un escalier à voûte sarrasine, correspondant à

(1). Réciproquement, si la position des nœuds dans le plan horizontale est modiﬁée à l’aide d’une
procédure itérative, alors la méthode des réseaux de forces permet d’étendre le champ des solutions
d’équilibre à l’ensemble des solutions d’équilibre de la méthode des densités de forces.
(2). Car q = s/L = sH/LH d’après le théorème de Thalès.
(3). Les forces de réactions aux appuis, qui pourraient également être considérées comme un chargement extérieur, ne sont pas soumises à cette hypothèse.

62

<!-- p. 64 -->

Chapitre 4. Méthode des réseaux de forces

une ﬁne voûte hélicoïdale, pour la clarté et lisibilité des ﬁgures décrivant cette structure (ﬁg. 4.4(a)). Le diagramme présentant l’enchaînement des étapes de la méthode
est donné sur la ﬁgure 4.5.

(a) (b) (c)

Fig 4.4 – Escalier hélicoïdal ; blocs (a), nuage de points (b), réseau de masse (c)

Considérons un système de blocs soumis uniquement à son poids propre, chaque
bloc étant un polyèdre (4). Les centres de gravité et les masses forment un nuage de
points pondéré (ﬁg. 4.4(b)). Les points correspondant aux blocs de la structure à étudier sont appelés nœuds intérieurs (« interior nodes » – blocs beiges sur ﬁg. 4.4(a)). Les
points correspondant aux blocs représentant les appuis ou la frontière de la structure
sont appelés nœuds d’appui (« boundary nodes » – blocs rouges sur ﬁg. 4.4(a)).

Pour construire un réseau à partir du nuage de points, une branche est créée pour
chaque joint. Chaque branche connecte les nœuds des blocs adjacents en contact au
joint considéré. La force de contact au niveau du joint a la même direction que celle
de la branche. Cette opération forme un premier réseau, que nous appellerons réseau
de masse (« mass network »). Voir ﬁg. 4.4 (c)

La connectivité du réseau est déduite de la discrétisation de la voûte en un ensemble de blocs. L’inﬂuence de l’appareil sur l’équilibre a été présenté précédemment
sur le cas particulier de la ligne de pression en 2D. Dans le cas d’une voûte en pierre
de taille, la discrétisation correspond à l’appareil (5) de la voûte.

La résolution des équations d’équilibre est réalisée en deux étapes successives.

Premièrement, les équations d’équilibre dans le plan horizontal sont considérées
pour chacun des blocs. La projection du réseau de masse dans un plan horizontal
donne le réseau projeté (« primal grid » ou « form diagram »). Comme le chargement
est un système de forces verticales par hypothèse, la projection du chargement se
réduit à des vecteurs nuls. Le chargement n’intervient pas dans l’équilibre du réseau
projeté.

Nous nous plaçons dans le cas où le réseau projeté est une forme en auto-équilibre
et statiquement indéterminée. L’équilibre du réseau projeté dépend alors uniquement

(4). Un polyèdre est un objet tridimensionnel délimité par des faces planes, chaque face étant un
polygone. Nous verrons dans le cas des plates-bandes à joints en X que les réseaux de forces peuvent
être étendus aux joints non plans au moyen de certaines adaptations qui seront décrites dans la partie
consacrée à l’extension de la méthode des réseaux de forces.
(5). Les questions de vocabulaire concernant la coupe des pierres, l’appareil et la stéréotomie seront
présentés dans la partie consacrée à la coupe des pierres des plates-bandes. Voir section 5.1 p. 73.

63

<!-- p. 65 -->

Chapitre 4. Méthode des réseaux de forces

Fig 4.5 – Diagramme de construction d’un réseau de forces

64

<!-- p. 66 -->

Chapitre 4. Méthode des réseaux de forces

d’un nombre limité de paramètres, indépendants du chargement. Chaque paramètre
correspond à la force horizontale dans une branche.

L’équilibre horizontal peut être exprimé à travers la ﬁgure réciproque du réseau
projeté, appelé le diagramme des forces (« dual grid » ou « force diagram »). Il est
la réunion des polygones des forces exprimant l’équilibre horizontal de chaque nœud
intérieur (ﬁg. 4.6).

Fig 4.6 – Réseau de forces d’un escalier hélicoïdal, projection horizontale du réseau
de forces et ﬁgure réciproque associée en fonction des réactions horizontales
(poussées), d’après Ciblac et Fantin (2016)

Deuxièmement, l’équation d’équilibre vertical est considérée pour chacun des
blocs, de manière à déterminer la position verticale à l’équilibre de chacun des nœuds
intérieurs. En eﬀet, le réseau de masse est une forme équilibrée uniquement pour des
cas particuliers.

À partir du réseau projeté, pour lequel les forces dans chaque branche (horizontale)
est connue, le réseau de forces est donc déduit en appliquant les équations d’équilibre
vertical. Cette étape transforme le réseau projeté, qui est plan, en réseau de forces,
qui est tridimensionnel. Il nécessite l’introduction de nouveaux paramètres, à savoir
la position des nœuds de bords du réseau.

Le réseau de forces obtenu est une forme représentant l’équilibre et dépendant

65

<!-- p. 67 -->

Chapitre 4. Méthode des réseaux de forces

d’un certain nombre de paramètres. Il existe donc une inﬁnité de réseaux de forces
pour une structure de blocs, chaque réseau étant déﬁni par un ensemble de valeurs
aﬀectées aux paramètres. Chaque réseau est en équilibre, mais la forme d’équilibre
représentée n’est pas nécessairement stable. Le jeu de paramètre optimum est déﬁni
comme celui donnant le réseau de forces le plus proche du réseau de masse. Il n’existe
pas nécessairement de réseau de forces superposé au réseau de masse, qui n’est généralement pas un réseau équilibré, sauf dans quelques cas particuliers (optimisation
de forme, solution membranaire).

4.3.4 Notations

Nous reprenons les notations de la méthode des densités de forces (section 4.2.3
ci-dessus), complétées par les notations suivantes.
L’exposant ∗identiﬁe les quantités duales lors du passage du réseau projeté à
sa forme duale, le diagramme des forces. Si u est la coordonnée d’une branche selon
l’axe x dans le réseau projeté, alors u∗est la composante de la force dans cette branche
selon l’axe x dans le diagramme des forces. On note :
— dans le réseau de masse
— xG, yG et zG les coordonnées des nœuds
— dans le réseau projeté
— xG et yG les coordonnées des nœuds
— u et v les composantes des branches (vecteurs orientés) √
— lH = u2 + v2 les longueurs (horizontales) des branches
— dans le diagramme des forces
— u∗et v∗les composantes des branches (vecteurs orientés), qui corres-
pondent aux forces horizontales dans les branches correspondantes du ré-
seau projeté √
— l∗H = u∗2 + v∗2 les longueurs des branches, qui correspondent aux forces
horizontales dans les branches correspondantes du réseau projeté
— dans le réseau de forces
— x = xG, y = yG et z les coordonnées des nœuds
— u, v et w les composantes des branches (vecteurs orientés) √
— l = u2 + v2 + w2 les longueurs des branches
— w∗les forces verticales dans les branches √
— l∗= u∗2 + v∗2 + w∗2 les forces dans les branches
Les notations principales sont rappelées sur la ﬁgure 4.7

4.3.5 Mise en équation de l’équilibre

Équilibre horizontal

Considérons les équations 4.14 et 4.15 de la méthode des densités de forces, qui
expriment l’équilibre selon les axes x et y. La réécriture de ces équations donne :

CtiUq + px = 0 (4.25)
CtiV q + py = 0 (4.26)

66

<!-- p. 68 -->

Chapitre 4. Méthode des réseaux de forces

8
9 10

2
4 5 7 3 1 1 10 3
10 4
5 1 8
3 8
2 9
9 4
2
6 7
1
3 4 2
5 6

7 6

Réseau projeté
Diagramme des forces
x, y coordonnées des nœuds
u, v composantes des branches x∗, y∗coordonnées des nœuds
lH longueurs de branches (distances) u∗, v∗composantes des branches
l∗H longueurs de branches (forces)

Fig 4.7 – Réseau projeté et sa forme duale, le diagramme des forces

Par déﬁnition de la densité de force, on a q = s/l = sH/lH. On pose ζ = sH la
force horizontale dans les branches, et on construit le vecteur correspondant ζ de
dimension m. Ainsi les équations d’équilibre selon les axes x et y sont équivalentes à
l’expression suivante :

" CtiUL−1H # K · ζ = 0 avec K = (4.27)
CtiV L−1H

Contrairement au cas de la méthode des densités de forces, dans la méthode des réseaux de forces les quantités U et V qui désignent les composantes des branches dans
le réseau projeté sont connues. Les coeﬃcients de la matrice K sont donc constants,
et l’équation précédente représente un système d’équations linéaires d’inconnue ζ.
La dimension 2ni × m de la matrice K est la traduction de l’existence de 2ni équations d’équilibre horizontal et de m inconnues. La structure est hyperstatique.
Les valeurs des forces horizontales dans les branches du réseau de forces dépendent de ndof = m −2ni paramètres si la matrice K est de rang maximal, ou
de ndof = m −rK paramètres avec rK le rang de la matrice K dans les autres cas
(Block et Lachauer, 2014b).

Après avoir réordonné le vecteur ζ pour séparer les paramètres choisis des autres
inconnues, ζ est la superposition des vecteurs ζunk et ζdof, et K peut être écrite sous
la forme d’une matrice par blocs avec Kunk et Kdof. La matrice Kunk est alors une

67

<!-- p. 69 -->

Chapitre 4. Méthode des réseaux de forces

matrice carrée inversible.

(ζunk ) K = Kunk ... Kdof et ζ = (4.28)
ζdof

Les équations d’équilibre horizontal sont alors mises sous la forme suivante qui dépend
des ndof paramètres choisis et réunis dans le vecteur ζdof :

Kunk · ζunk = −Kdof · ζdof (4.29)
ζunk = −K−1unk · Kdof · ζdof (4.30)

À la ﬁn de cette étape, l’ensemble des forces horizontales sH = ζ dans les branches
sont connues en fonction du vecteur paramètre ζdof.

Équilibre vertical

Soit lH la longueur d’une branche dans le réseau projeté (c.-à-d. la distance géométrique entre les nœuds correspondant) et l∗H = sH = ζ la longueur d’une branche
dans le diagramme des forces (c.-à-d. la force horizontale dans la branche correspondante du réseau projeté). Chaque force étant parallèle à la branche correspondante,
le thèorème de Thalès donne :

w∗= L−1H L∗Hw = L−1H L∗HCz (4.31)

Considérons l’équation 4.16 de la méthode des densités de forces, qui exprime
l’équilibre vertical (selon l’axe z). La réécriture de cette équation donne successivement :

CtiW q + pz = 0 (4.32)
CtiQw + pz = 0 (4.33)
CtiL−1H ZCz + pz = 0 (4.34)

La matrice D et ses sous-matrices Di et Db sont utilisées pour simpliﬁer les
notations :

D = CtiL−1H ZC (4.35)
Di = CtiL−1H ZCi (4.36)
Db = CtiL−1H ZCb (4.37)

Ces matrices sont identiques à celles de la méthode des densités de forces, elle sont
formulées ici pour faire apparaître la dépendance en Z (matrice diagonale tirée du
vecteur ζ) donnant les forces horizontales dans le réseau.
La position des nœuds d’appuis zb étant connue, ainsi que les forces horizontales ζ
obtenues lors de la résolution de l’équilibre horizontal, l’équation 4.38 ci-dessous peut
être résolue. Elle donne la position verticale de tous les nœuds intérieurs de manière
à respecter l’équilibre vertical :

Dizi = −pz −Dbzb (4.38)

68

<!-- p. 70 -->

Chapitre 4. Méthode des réseaux de forces

Paramètres

Deux types de paramètres ont été introduits lors de la résolution des équations
d’équilibre. Premièrement, les paramètres ζdof (égaux aux forces horizontales) ont été
introduits. Deuxièmement, les paramètres liés à la position verticale des nœuds d’appuis zb ont été introduits. Chaque ensemble de valeurs pour ces jeux de paramètres
donne une solution d’équilibre, qui peut être stable ou non dans le cadre du calcul à
la rupture suivant les critères considérés.

4.3.6 Recherche des solutions d’équilibre admissibles

L’application de la méthode des réseaux de forces produit des réseaux de forces
en équilibre en fonction des paramètres mentionnés précédemment (ﬁg. 4.5).

Le choix des valeurs à prendre pour ces paramètres est guidé par la recherche des
solutions d’équilibre admissibles (stables) parmi l’ensemble des solutions d’équilibre
possibles. Un réseau de forces est jugé admissible si ses nœuds sont situés à l’intérieur
de la maçonnerie (6). En notant zintradosi et zextradosi les altitudes respectives de l’intrados et l’extrados à l’aplomb du nœud i (ﬁg. 3.7 p. 49), cette condition de stabilité
s’écrit :
pour tous les nœuds intérieurs : zintradosi \< zi \< zextradosi (4.39)

Pour rechercher un réseau respectant cette condition, une fonction de coût f à
minimiser est déﬁnie. La fonction f est la somme des distances quadratiques entre
les nœuds du réseau de forces et les nœuds du réseau de masse (Block, 2009 ; Block
et Lachauer, 2014b) :
f = X(z2i −z2G) (4.40)

Pour le réseau de forces minimisant cette fonction, on vériﬁe alors que les nœuds
du réseau sont bien situés à l’intérieur de la maçonnerie. Le diagramme décrivant la
recherche d’un réseau de forces admissible est donné sur la ﬁgure 4.8.

Ce processus d’optimisation ne concerne que les paramètres permettant d’obtenir une solution d’équilibre d’admissible, la géométrie étant une donnée connue du
problème à résoudre (voir paramètres ﬁxes et paramètres variables sur la ﬁgure 4.5).
Dans le cas de la recherche de formes, qui sort du cadre de cette thèse, les poids
et la position des nœuds dans le plan horizontal peuvent également faire partie du
processus d’optimisation pour trouver de nouvelles formes d’équilibre. Ce sujet sort
de notre recherche axée sur les constructions clavées historiques.

(6). Cette propriété utilisé dans la formulation d’origine de la méthode des réseaux de forces
(O’Dwyer, 1999) est une simpliﬁcation par rapport à la condition donnée par l’application rigoureuse du calcul à la rupture. Ce point est étudié en détail dans la partie III consacrée à l’extension
de la méthode des réseaux de forces (section 11.1 p. 204).

69

<!-- p. 71 -->

Chapitre 4. Méthode des réseaux de forces

Fig 4.8 – Diagramme de recherche d’un réseau de forces admissible

70

<!-- p. 72 -->

Deuxième partie

Plates-bandes et voûtes plates
en France

71

<!-- p. 73 -->

Chapitre 5

Stéréotomie et coupe des pierres

Résumé : Ce chapitre traite de la stéréotomie, appelée plus traditionnellement
coupe des pierres. Les déﬁnitions et la terminologie de base relative à la coupe des
pierres sont données. Les processus de taille des pierres et l’évolution historique des
épures exposées dans les traités de coupe des pierres français sont ensuite présentés
pour donner le contexte historique de la coupe des pierres. Enﬁn, le principe de
normalité, qui règle l’orientation à donner aux joints des voûtes, et les limites de son
application sont évoqués.

Sommaire
5.1 Déﬁnitions ; de la pierre au voussoir . . . . . . . . . . . . . . . . . 73
5.2 Processus de taille de pierre . . . . . . . . . . . . . . . . . . . . . 76
5.3 Évolution des tracés de coupe des pierres . . . . . . . . . . . . . . 77
5.4 Principe de normalité . . . . . . . . . . . . . . . . . . . . . . . . . 80

72

<!-- p. 74 -->

Chapitre 5. Stéréotomie et coupe des pierres

5.1 Déﬁnitions ; de la pierre au voussoir

La stéréotomie est la science qui traite de la découpe les solides. Elle s’applique
dans le cadre de la construction à la taille des pierres d’une part, et à la taille du bois
pour les charpentes d’autre part. Le terme stéréotomie apparaît au xviie siècle chez
Curabelle (Pérouse de Montclos, 1982, p. 85, 99). La stéréotomie est plus simplement
appelée coupe des pierres, ou science du trait. Les traités s’intitulent ainsi en majorité
simplement « traité de [la] coupe des pierres » ou font directement référence au terme
« coupe des pierres » (Desargues, De La Hire, De La Rue, Frézier, Simonin, Douliot,
Adhémar, Chaix, Tachon etc.).

La coupe des pierres regroupe l’ensemble des règles de tracé des épures, qui permettent à l’appareilleur de produire les panneaux et gabarits utiles au tailleur de
pierre.

Les voussoirs désignent les pierres de taille qui composent une voûte. Le terme
voussoir désignant une pierre dont l’intrados ou l’extrados est courbe, il ne convient
généralement pas pour les pierres composant une plate-bande dont le soﬃte et l’arasement sont plans. Dans ce cas, le terme claveau s’applique. Ce point est souligné
régulièrement (1) dans les traités et mémoires de l’Époque Moderne.

La clé (ou clef ) désigne le voussoir central lorsqu’un arc est composé d’un nombre
impair de voussoirs ou claveaux. Les voussoirs sur lesquels s’appuie la clé sont appelés
les contre-clés (ou contreclefs). Les pierres situées sur les piédroits et servant d’appui
à l’arc sont les sommiers.
Le voussoir d’un arc possède six faces, ou panneaux (2). Ces derniers sont opposés
deux à deux : deux panneaux de douelle (correspondant à la face inférieure et supérieure du voussoir, et donc à l’intrados et à l’extrados de l’arc), deux panneaux de lits
ou de coupe) (correspondant aux faces en contact avec les voussoirs voisins), et deux
panneaux de tête (D’Aviler, 1691, p. 237-238, cit. 19 (3) – ﬁg. 5.1).

Fig 5.1 – Panneaux de voussoirs, d’après D’Aviler (1691, p. 236)

(1). Derand (1643, p. 2), D’Aviler (1691, p. 237, cit. 18), De La Hire (1712, p. 75, cit. 22), Frézier
(1738, p. 64, cit. 31), Diderot et d’Alembert (1765a, cit. 45).
(2). Le terme panneau désigne également les gabarits utilisés par les tailleurs de pierre pour reporter
les dessins de l’épure sur la pierre à tailler.
(3). Les citations sont numérotées par ordre chronologique de publication. Le renvoi « cit. 19 » fait
référence à la citation numéro 19, les citations étant regroupées dans l’annexe A.

73

<!-- p. 75 -->

Chapitre 5. Stéréotomie et coupe des pierres

De manière générale, le joint désigne l’« espace entre deux éléments, généralement
rempli de mortier, de plâtre ou par des plaques de plomb. Le mot désigne également
la couche de matériau remplissant cet espace. » (Pérouse de Montclos, 2007, p. 58).
Pérouse de Montclos (2007, p. 603) indique que « pour certains auteurs, ce mot [joint]
désigne aussi bien l’intervalle entre deux éléments que la ligne marquant ces intervalles
en parement ». Dans le cas des plates-bandes, il fait la distinction entre le lit en coupe,
qui est le « pan oblique par lequel un claveau s’appuie sur le claveau voisin » et le joint
de lit en coupe qui n’est que la partie visible du joint sur l’intrados (2007, p. 148).

Dans ce document, nous utiliserons le terme de joint pour désigner à la fois les
joints de lit en coupe (segments), et les lits en coupe eux-mêmes (surfaces).

Arcs et voûtes « clavés »

Les termes claver, clavé et clavage ne sont pas déﬁnis dans les traités de coupe des
pierres de l’Époque Moderne, et renvoient à plusieurs concepts suivant leur contexte
d’utilisation.

Aujourd’hui, le dictionnaire Larousse donne trois acceptions pour le verbe claver :

déf. 1. « Construire à claveaux. »

déf. 2. « Mettre en place la clef d’un organe fait de claveaux. »

déf. 3. « Mettre en serrage un soutènement ou un remblai contre le toit. »

Dans le contexte de l’architecture en maçonnerie, et plus particulièrement celui
de l’histoire de l’architecture et de l’histoire de la construction, c’est généralement (4)
la première déﬁnition qui s’applique (déf. 1).

Il convient cependant de préciser le contenu de cette déﬁnition. Dans l’ouvrage
de référence actuel sur le vocabulaire de l’architecture, Pérouse de Montclos (2007)
désigne comme appareil clavé l’appareil composé de claveaux, ces derniers étant un
« élément de l’appareil d’une plate-bande, d’un arc ou d’une voûte, taillé en forme
de coin » (2007, p. 148). Nous reviendrons longuement sur le principe de normalité
qui règle la forme de coin des claveaux à la ﬁn de ce chapitre. Par ailleurs, Pérouse
de Montclos (2007, p. 130) distingue quatre types de voûtes suivant leur matériau
constitutif et la mise en œuvre de ce dernier :
— avec agrégats ou éléments de maçonnerie jetés :
— l’arc ou la voûte en béton ;
— l’arc ou la voûte en blocage, ce dernier étant constitué d’éléments de ma-
çonnerie « de diﬀérentes grosseurs jetés dans un bain de mortier » ;
— avec éléments de maçonnerie ou pierre de taille posés :
— l’arc ou la voûte bloqués au mortier, formés « d’éléments non clavés dont
les joints, remplis de mortier et quelquefois de cailloux, sont ouverts en V
vers l’extrados » (ﬁg. 5.2) ;
— l’arc ou la voûte appareillés, l’appareil étant « une maçonnerie formée d’élé-
ments posés et non jetés : chaque élément est donc taillé pour occuper une
place déterminée ».

74

<!-- p. 76 -->

Chapitre 5. Stéréotomie et coupe des pierres

Fig 5.2 – Voûte bloquée au mortier, surmontée par une maçonnerie de blocage ;
amphithéâtre de Luni, Ligurie (Italie)

Dans le cadre de la déﬁnition des claveaux, Pérouse de Montclos (2007, p. 148)
préconise de « ne pas appeler voussoirs [ou claveaux] les éléments non clavés des
voûtes et des arcs bloqués au mortier ». Enﬁn, il distingue la « voûte assisée clavée »,
formée de voussoirs, de la « voûte [assisée] en tas-de-charge », c’est-à-dire « formée
d’assises horizontales en surplomb l’une sur l’autre » (Pérouse de Montclos, 2007,
p. 130).

En tenant compte de la remarque précédemment faite sur l’emploi respectif du
terme voussoir pour les arcs et les voûtes courbes et claveau pour les plates-bandes
et les voûtes plates, la déﬁnition de Pérouse de Montclos (2007) de l’adjectif clavé
repose sur cinq concepts :

\1. l’adjectif clavé qualiﬁe un arc ou une voûte construite par voussoirs (arcs et
voûtes courbes) ou par claveaux (plates-bandes et voûtes plates) ;

\2. ces voussoirs ou claveaux sont posés ;

\3. ces voussoirs ou claveaux sont taillés pour occuper une place déterminée ;

\4. ces voussoirs ou claveaux sont taillés en forme de coin ;

\5. le mortier n’est pas utilisé pour donner une forme de V aux joints.

Nous retenons cette déﬁnition pour ce document.

Parmi les termes à signiﬁcation proche, notons que la « voûte appareillée » telle
que déﬁnie par Pérouse de Montclos (2007) peut être ou bien clavée, ou bien construite
en encorbellement (5). Le terme « voûte à poussée » est utilisé implicitement pour
désigner les voûtes clavées par Choisy (1899a, p. 31, 162, 246) et Adam (1989, p. 174).

Les termes claver, clavé et clavage sont peu employés avant les années 1870-1880,
ce que traduit leur absence des dictionnaires et lexiques donnés par les traités de

(4). Le terme clavé correspond à la première déﬁnition par exemple chez Choisy (1873), Adam
(1989), Sakarovitch (1998) et Pérouse de Montclos (2007, 1982).
(5). Choisy utilise l’expression « berceau d’appareil » à au moins une occasion pour désigner une
voûte en encorbellement (Choisy, 1899a, p. 30).

75

<!-- p. 77 -->

Chapitre 5. Stéréotomie et coupe des pierres

l’Époque Moderne traitant de la coupe des pierres. En dehors des ouvrages traitant
de l’histoire de l’architecture et de l’histoire de la construction, ils sont à partir de
cette date essentiellement utilisés pour décrire le processus de mise en place de la
clé de voûte (déf. 2), lors de la construction des voûtes ou des tunnels. Aujourd’hui,
le terme clavage désigne dans la pratique courante des ingénieurs en bâtiment la
solidarisation d’un élément porteur et d’un élément porté (déf. 3), et par extension de
deux éléments successifs : poutre en béton précontraint sur murs ou poteaux, dallages,
tabliers des ponts, etc.

Le suﬃxe « -age » désigne dans le cas du dérivé d’un verbe ou bien l’action, ou
bien le résultat de cette action. Dans ce cas, le terme clavage désignerait donc l’action
de mettre en place la clé de voûte (déf. 2), ou l’action de solidariser deux ouvrages
(déf. 3). À ce titre, le dictionnaire Larousse ne donne pas de déﬁnition équivalente à
la déﬁnition 1 vue précédemment pour « claver ». Cependant, le terme clavage peut
également indiquer le résultat de l’action du découpage en claveau. Viollet-le-Duc,
qui n’emploie ce terme que trois fois dans son dictionnaire, et seulement à l’article
sur les roses, semble plutôt utiliser ce terme pour désigner un ensemble de claveaux.

Nous utilisons le terme appareil plutôt que celui de clavage dans ce document.

5.2 Processus de taille de pierre

Le type d’épure est lié au processus de taille de pierre adopté sur le chantier. Les
principaux types de taille de pierre sont les suivants (Sakarovitch, 1998 ; Pérouse de
Montclos, 1982).

La taille par ravalement ne demande pas de tracé préalable. Les pierres sont
placées dans la voûte en construction, puis ravalées, c’est-à-dire retaillées alors qu’elles
occupent déjà leur position ﬁnale dans l’édiﬁce, pour obtenir la surface recherchée.
Ce type de taille comprend notamment la taille à la perche, où une perche sert de
guide pour trouver les parties qui doivent être ravalées. Cette technique de taille est
la plus ancienne.

La taille par équarrissement s’applique à un bloc de pierre préalablement équarri
(parallélépipède rectangle). Le proﬁl du claveau tracé à l’échelle en plan et en élévation
est reporté, soit par panneau (6), soit à la règle et à l’équerre, sur les faces du bloc
équarri, qui est alors de nouveau taillé. Cette taille est également appelée taille par
dérobement.

La taille par panneaux permet un gain de matière par rapport à la taille par
équarrissement. Elle nécessite de dessiner toutes les faces du voussoir (les panneaux).
Le proﬁl de la première face est reporté par panneau et la face est taillée. Les orientations des faces voisines sont reportées avec le biveau ou la sauterelle, qui permettent
de reporter ces orientations à travers l’angle entre les faces. Le panneau de chaque
face à tailler est ensuite reporté.

(6). « Le panneau est le patron en papier, en parchemin, en bois, en métal, d’un des pans du
voussoir à tailler, servant à reporter sur le bloc de pierre le contour donné par l’épure. » (Pérouse de
Montclos, 1982, p. 90)

76

<!-- p. 78 -->

Chapitre 5. Stéréotomie et coupe des pierres

5.3 Évolution des tracés de coupe des pierres

Plus la technique de taille est économe en pierre et précise, plus elle nécessite
des méthodes de tracé perfectionnées. Nous dressons rapidement dans cette section
l’évolution des méthodes de tracés, sans entrer dans le détail de ces dernières, à travers
les traités qui les présentent (ﬁg. 5.3).

La source principale de cette partie est l’ouvrage de Sakarovitch (1998, p. 136-149)
intitulé Épures d’architecture : de la coupe des pierres à la géométrie descriptive xviexixe siècles.

1500 1600 1700 1800

(1567) (1643) (1688) 1739) (1794)
l’Orme Derand LaHire 1738, Monge De De (1737, (1642), Frézier Jousse (1728), (1640), Rue
La
De Desargues

Fig 5.3 – Frise historique des principaux traités français de coupe des pierres

Moyen Âge

L’Album de Villard de Honnecourt comporte des dessins qui illustrent certaines
épures (Lalbat et al., 1987, 1989). Il n’existe cependant pas de traité de coupe des
pierres au Moyen Âge.

La construction des voûtes au Moyen Âge repose sur un nombre limité de méthodes géométriques (Tamboréro et Sakarovitch, 2010). Les statuts des tailleurs de
pierre leur interdisaient au Moyen Âge de partager leur savoir en dehors de la corporation (Sakarovitch, 1992, p. 531, cit. 130 ; Pérouse de Montclos, 1982, p. 85).

Philibert De l’Orme (1514-1570)

Philibert De l’Orme est le premier auteur à avoir publié en France les règles d’un
art dont la transmission était jusqu’alors orale, de maître à apprentis. Architecte,
il consacre les livres III et IV de son traité d’architecture à la coupe des pierres
(De l’Orme, 1567). Son traité s’adresse principalement aux architectes.

De l’Orme présente la coupe des pierres comme le moyen d’aménager et réutiliser les bâtiments existants. Des trompes, tourelles d’angles, et escaliers en vis sont
construites pour desservir les diﬀérents niveaux existants et permettre la régularisation du plan du nouvel édiﬁce construit sur la base d’un édiﬁce antérieur, au plan
irrégulier (De l’Orme, 1567, 86, cit. 6). Selon Sakarovitch (1998, p. 136), « l’archétype

77

<!-- p. 79 -->

Chapitre 5. Stéréotomie et coupe des pierres

de cet[te] usage de la stéréotomie est la trompe du chateau d’Anet, ajoutée sur une
façade déjà construite pour soutenir en porte-à-faux le cabinet du roi Henri II ».
Tamboréro (2013) souligne que le traité de De l’Orme ne se limite pas à diﬀuser
des techniques existantes chez les tailleurs de pierre. De l’Orme propose également de
moderniser les méthodes de tracé. Tamboréro (2013) écrit ainsi : « Ce tracé possède
eﬀectivement une propriété fondamentale en coupe des pierres : il est universel, c’està-dire qu’il peut être appliqué à tous les cas de ﬁgure d’une voûte conique. »
Enﬁn, De l’Orme indique que « les bons maîtres » se servent de la taille par
panneaux, et non de la taille par équarissement (Pérouse de Montclos, 1982, p. 91).
Les méthodes de tracés présentées par De l’Orme sont analysées en détail par Tamboréro (2008).

Girard Desargues (1591-1661)

Girard Desargues est considéré « comme l’une des plus éminentes personnalités
de l’Europe savante du xviie siècle » (Pérouse de Montclos, 1982, p. 98). Il publie
en 1640 un opuscule très court (quatre pages de textes et quatre planches), intitulé
Brouillon projet de coupes des pierres (Desargues, 1640). Tamboréro (2013) explique
que Desargues y expose « une méthode “universelle” qui permet de résoudre la totalité
des problèmes de coupe des pierres, à condition de travailler avec des surfaces planes ».
Desargues s’adresse principalement aux architectes. Il ne donne comme exemple
d’application de sa méthode que les descentes biaises, parce qu’elles regroupent la
plupart des diﬃcultés rencontrées dans la coupe des pierres.
Pérouse de Montclos (1982, p. 88) rapporte la note suivante de François Blondel,
dans sa réédition du traité de Savot en 1685. Les ouvriers « pratiquaient couramment
le ravalement pour corriger leurs défauts de conception », parce qu’ils ne maîtrisaient
pas la seule méthode « infaillible », celle du trait à preuve de Desargues.
Cet opuscule sera durement attaqué par ses contemporains, et notamment Curabelle. Desargues ne publiera plus après, et se consacrera à la construction pour
montrer l’eﬃcacité de sa méthode.
La méthode de Desargues est reprise et présentée par Bosse (1643) dans la Pratique
du trait à preuve.

Curabelle

Curabelle fut d’après Mariette « le meilleur appareilleur de son temps », et en
forte opposition à Desargues qu’il critiqua durement (Sakarovitch, 1998 ; Pérouse de
Montclos, 1982, p. 99). Il est le premier à utiliser le terme stéréotomie, qui était connue
jusqu’alors comme l’art du trait (D’Amato et Fallacara, 2005, p. 52).

Mathurin Jousse (1607-1650)

Mathurin Jousse publie en 1642 Le secret d’architecture découvrant ﬁdèlement les
traits géométriques, couppes et dérobemens nécessaires dans les bastiments. Il s’adresse
aux maçons et tailleurs de pierre. Son texte est court et les ﬁgures dépouillées, destinées à pouvoir être utilisées par les appareilleurs.

78

<!-- p. 80 -->

Chapitre 5. Stéréotomie et coupe des pierres

François Derand (1588-1644)

François Derand publie en 1643 L’architecture des voûtes, ou l’art des traits, et
coupes des voûtes. Plus clair que ses prédécesseurs, il présente l’ensemble des méthodes
qui sont utilisées par les appareilleurs au xviie siècle.

Selon Tamboréro (2013), les textes de Jousse et Derand « rassemblent un bien plus
grand nombre de tracés mais n’apportent pas de réelles nouveautés géométriques »
par rapport à De l’Orme, contrairement à la méthode que propose Desargues, ensuite
reprise par La Hire pour l’enseignement à l’Académie royale d’architecture à partir
de 1688.

Jean-Baptiste de La Rue (1697-1643)

Jean-Baptiste de La Rue publie en 1728 un traité qui est un abrégé de celui de
Derand. Son originalité vient de l’utilisation systématique de la représentation en
axonométrie des claveaux, ce qui facilite la compréhension des épures.

Philippe de La Hire (1640-1718)

Il n’est pas présenté par Sakarovitch, car le cours de La Hire n’est pas publié,
et n’est connu que sous la forme de manuscrits (deux tomes). La Hire est nommé
professeur d’architecture à l’Académie royale d’architecture en 1687, et commence
son cours de coupe des pierres en 1688. Le Traité de la coupe des pierres de Philippe
de La Hire a été analysé et présenté par Tamboréro (2013). Il reprend la méthode de
Desargues, et la présente à l’aide de nombreux exemples.

L’enseignement de Philippe de La Hire aux architectes et ingénieurs du roi vise
à leur fournir une technique de tracé universelle, qui puisse être appliquée à tous les
cas qu’ils pourront rencontrer en pratique, et ainsi aﬀermir le pouvoir des architectes
et ingénieurs sur le chantier, au détriment des corporations (Tamboréro, 2013).

Amédée Frézier (1682-1773)

Amédée Frézier publie un traité monumental en trois tomes (1737; 1738; 1739) :
Théorie et pratique de la coupe des pierres et des bois pour la construction des voûtes
et autres parties des bâtiments civils et militaires. Ce traité comprend des constructions qui n’avaient jusqu’alors pas été présentées dans les traités existants, comme les
retombées de coupole.

Ses observations et préconisations concernant les voûtes plates et les plates-bandes
sont complètes et argumentées, alors que ces objets sont très peu commentés par les
autres auteurs de traités.

« Avec la parution de La théorie et la pratique de la coupe des pierres et des bois...
d’Amédée-François Frézier, le processus d’évolution théorique de la stéréotomie, parti
de la réalité constructive du chantier de la Renaissance, atteignit son apogée. Fondée scientiﬁquement sur les catégories techniques Vitruviennes, la stéréotomie était
organisée dans l’ouvrage de Frézier dans les parties suivantes : tomomorphie, tomographie, stéréographie (ichnographie, orthographie, épipédographie, goniographie) ;

79

<!-- p. 81 -->

Chapitre 5. Stéréotomie et coupe des pierres

et tomotechnique, c’est-à-dire : étude des courbes obtenues comme sections de solides
au moyen des surfaces planes ou courbes ; représentation des courbes sur des surfaces
planes et courbes ; représentation, mesures et développement et, enﬁn, détermination
des sections les plus utiles à la coupe des matériaux de construction. » (D’Amato et
Fallacara, 2005, p. 54).

Gaspard Monge (1746-1818)

Les traités de coupe des pierres que nous avons vus précédemment utilisent les
projections et procédés graphiques de la géométrie descriptive. Cependant ils présentent une suite de cas particuliers, sans regard global sur la théorie employée (Sakarovitch, 1992, p. 532). La géométrie descriptive, mise au point par Gaspard Monge,
est l’aboutissement de la lente évolution des méthodes de tracés (Sakarovitch, 1998,
p. 5).

5.4 Principe de normalité

La perpendicularité des joints avec l’intrados est présentée comme un des principes
fondamentaux de la coupe des pierres dans les traités d’architecture et de coupe
des pierres (ﬁg. 5.4) (Aita, 2003). À défaut d’un terme communément admis pour
désigner ce principe, nous proposons de le nommer « principe de normalité », au sens
mathématique du terme. Dans le cas des arcs de cercles, ou courbes construites sur
la base d’arcs de cercles comme les arcs en anse-de-panier, ce principe est parfois
énoncé sous une autre forme, à savoir que les joints tendent vers le centre des cercles
qui servent au tracé des arcs.

Fig 5.4 – Joints d’un arc formant un angle droit avec l’intrados

Dès l’Antiquité, Vitruve indique que les joints des voussoirs des arcs tendent vers
le centre de l’arc. Son indication ne prend cependant pas la forme d’un principe ; il
indique simplement que les arcs de décharges placés au-dessus des linteaux et les arcs
composant les bâtiments à arcades sont construits ainsi (7).

(7). Traduction du chapitre XI du livre 6 de Vitruve (Rondelet, 1805, p. 11-13) : « Si les fondemens
qu’on élève au-dessus du rez-de-chaussée sont faits comme nous l’avons expliqué dans les livres
précédents en parlant des murs et des théâtres, il n’y a pas de doute que ces édiﬁces se maintiennent
solides jusqu’aux tems les plus reculés. Si l’on fait des constructions souterraines et des voûtes, elles

80

<!-- p. 82 -->

Chapitre 5. Stéréotomie et coupe des pierres

Ce principe est ensuite mentionné dans de nombreux traités français, entre autres
par :
— D’Aviler (1691, p. 237-238, cit. 19) à propos des voussoirs des arcs en plein-
cintre ;
— Tiercelet (1728, p. 61, cit. 25) à propos des arcs segmentaires et plates-bandes
couvrant les fenêtres ;
— Frézier (1737, p. 281-282, cit. 30) ;
— Diderot et d’Alembert (1756, cit. 44), qui indiquent dans l’article concernant
la fausse-coupe que la direction du joint doit être perpendiculaire à l’arc du
cintre pour être « en bonne coupe » (Diderot et d’Alembert, 1756, cit. 44), sans
donner cependant la raison de cette condition ;
— Blondel (1752, p. 156, cit. 56) ;
— Blondel et Patte (1777a, p. 288, cit. 59) ;
— Dhombres (1992, p. 340, cit. 69), (1992, p. 419, cit. 70) ;
— Viollet-Le-Duc (1858, cit. 84), (1859b, cit. 88), (1863, cit. 92) ;
— Bazin (1888, cit. 104, 105) ;
— Chaix (1890, p. 16, cit. 107) ;
— Choisy (1899b, p. 146), qui indique que les arcs brisés romans « ont leurs
lits normaux à l’intrados, ce qui permet de les couper tous sur un modèle
uniforme » ;
— manuscrit (8) ms. 1517 des Ponts et chaussées, non daté, mentionné par Pérouse
de Montclos (1982, p. 88).
Le principe de normalité apparaît implicitement chez Coulomb, Charles Bossut,
Claude Antoine Couplet, Giordano Riccati, Mariano Fontana et Anton Maria Lorgna
(Aita, 2003). Ce sujet a été abordé récemment par Aita (2003) et Rippmann (2016).

Plusieurs justiﬁcations diﬀérentes sont données pour expliquer l’existence de ce

doivent avoir plus d’épaisseur que celles des parties au-dessus. Les murs, les points d’appui et les
colonnes de l’étage supérieur doivent être élevés perpendiculairement au milieu de ceux des parties
inférieures, aﬁn que les parties solides se répondent. Car si la charge des murs et des colonnes était
en porte-à-faux, ils n’auraient ni solidité, ni durée. Indépendamment de cette disposition, il est à
propos de soutenir la trop grande portée des linteaux ou poitrails par des décharges, pour les rendre
plus fermes ; car, lorsque ces linteaux ou poitrails sont trop chargés, ils ﬂéchissent dans le milieu,
et causent des ruptures et des désunions dans les constructions qu’ils soutiennent. Mais au moyen
des décharges angulaires, ﬁg I, planche LXVIII, qu’on peut établir au-dessous, les constructions ne
souﬀrent plus de dommage, et les pièces de bois se trouvent soulagées. On peut aussi les décharger
du poids des murs, en faisant des arcs divisés en voussoirs, dont les joints tendent à un
même centre [cuneorum divisionibus, et ad centrym respondantes earum conclusuræ]. Les premiers
voussoirs de l’arc étant au delà des bouts des linteaux ou des poitrails, se trouveront renfermés dans
le segment de l’arc, et par ce moyen ces pièces de bois étant déchargées du fardeau, ne pourront plus
plier. De plus si dans la suite elles venaient à être détruites par vétusté, elles pourraient être changées
sans avoir besoin d’étayement.
On construit aussi des édiﬁces sur des piliers réunis par des arcades divisées en voussoirs,
dont les joints tendent au centre [divisionibus coagmentis ad centrum respondentibus, fornices
concluduntur] ; alors, il faut que les piliers des extrémités (ﬁg. 2) soient plus larges que les autres, aﬁn
de leur donner la force nécessaire pour résister aux eﬀorts des voussoirs chargés du poids des murs ;
et comme les voussoirs du milieu ne se soutiennent que par leurs joints qui, en tendant au centre,
repoussent les coussinets ou premiers voussoirs. C’est pourquoi si les piliers des angles ont une masse
assez grande, ils contiendront cet eﬀort et procureront à l’ouvrage la stabilité qui lui convient. »
La traduction de Vitruve par Claude Perrault (1673) ne contient pas ces précisions.
(8). « [...] et la géométrie détermine dans tous les cas d’une manière exacte toutes les coupes tendant
au centre des diﬀérents arcs. » Manuscrit ms. 1517 des Ponts et chaussées.

81

<!-- p. 83 -->

Chapitre 5. Stéréotomie et coupe des pierres

principe. La plus commune est que son application permet de donner aux voussoirs
la forme de coins, forme nécessaire à la stabilité (Frézier, 1737, p. 281-282, cit. 30).
La solidité des blocs est également avancée comme explication de la nécessité de ce
principe. Une coupe non normale à la courbe de la voûte produit des angles aigus
jugés néfastes pour la stabilité en raison du risque de rupture de la pierre :
— Frézier (1737, p. 281-282, cit. 30) ;
— Dhombres (1992, p. 340, 419, cit. 69, 70) ;
— Viollet-Le-Duc (1863, cit. 92) ;
— Chaix (1890, p. 16, cit. 107).
Ce principe permet d’obtenir une coupe uniforme pour tous les voussoirs (Choisy,
1899b, p. 146, à propos des arcs brisés romans). Enﬁn, Bazin présente un dernier
argument : selon lui, la coupe normale est la plus « naturelle » parmi les coupes
inclinées, donc parmi celles qui permettent la stabilité (Bazin, 1888, cit. 104, 105).
Le principe de normalité s’applique à l’ensemble des couvrements courbes en pierre
de taille (voûtes en berceau plein-cintre ou surbaissé, voûtes d’arêtes, voûtes en arcde-cloître, coupoles etc.). Il est également mentionné par Viollet-le-Duc dans le cadre
de l’étude de l’appareil des remplages des baies au Moyen Âge (Viollet-Le-Duc, 1863,
cit. 92).
Ce principe n’est cependant pas toujours respecté en pratique. Dans le cas des
remplages, l’analyse que fait Viollet-le-Duc des tracés des remplages souligne la rationalisation que connaissent ces tracés à partir des années 1240. Il souligne que dans le
système abouti, « les joints étaient toujours normaux aux courbes » des voussoirs formant le remplage (Viollet-Le-Duc, 1863, cit. 92). Cependant en négatif apparaissent
tous les remplages antérieurs qui ne respectent pas la condition de normalité.
De même, les méthodes de tracé des épures de coupe des pierres publiées du xvie
au xviiie siècle, qui ont fait l’objet d’une étude comparative par Sakarovitch,
montrent dans le cas des descentes biaises que le principe de normalité n’est pas
toujours respecté (Sakarovitch, 1998, p. 178-179, cit. 129).
Dans le cas des dômes elliptiques étudiés par La Hire (9) le choix du centre de
l’ellipse aurait conduit à des joints qui ne sont pas perpendiculaires à l’intrados,
même si ce choix n’est ﬁnalement pas retenu par La Hire. Frézier souligne également
que le principe de normalité ne peut pas toujours être appliqué, même dans le cas
relativement simple des berceaux (Frézier, 1737, p. 279-281).
En pratique, nous avons également relevé des exemples d’arcs simples ne respectant pas le principe de normalité. C’est ainsi le cas de certains arcs brisés de Toscane
au Moyen Âge, comme cela est particulièrement visible à Prato en raison de l’utilisation de claveaux de couleurs claires et sombres alternées (ﬁg. B.72, voir l’arc du

(9). La question de l’appareillage des dômes elliptiques, soulevée à l’Académie royale d’architecture,
fait l’objet d’interventions répétées de La Hire devant la même Académie (1688 cit. 148, 149, 150, 151,
152 et 153). Ce dernier propose une nouvelle manière de tracer les épures de ces voûtes, probablement
plus compacte que celle habituellement pratiquée (« nouvelle manière de tracer tous les panneaux
sans sortir du champ de l’ouvrage »). De plus, il substitue aux arcs en anse-de-panier, composés
de plusieurs arcs de cercles, de véritables ellipses. Il observe qu’il faudrait utiliser le « centre de
l’ovale [ellipse] » comme point de rayonnement des joints. Comme « cela n’est pas si agréable à la
veue, cependant on est obligé de tomber en ce cas en plusieurs rencontres », c’est-à-dire qu’il faut
utiliser plusieurs centres de rayonnement. Ces centres ne sont pas précisés dans le compte-rendu de
l’Académie, mais on peut supposer qu’ils correspondent, ﬁnalement, aux centres qui auraient été
choisis pour tracer l’arc en anse-de-panier.

82

<!-- p. 84 -->

Chapitre 5. Stéréotomie et coupe des pierres

tympan au-dessus de la plate-bande du portail). L’arc d’une porte de Palmyre (10),
relevé par Durm (1885), montre qu’il existe également des contre-exemples dans l’Antiquité (ﬁg. 5.5).

Fig 5.5 – Arc avec joints non convergents vers le centre de l’arc, porte principale de
« Saülenstrasse » à Palmyre, d’après Durm (1885, ﬁg. 124)

Ainsi, le principe de normalité, bien qu’il puisse être respecté pour les couvrements courbes (11) à toutes les époques, souﬀre de nombreuses exceptions dès que la
géométrie devient complexe, comme dans le cas des remplages et des descentes biaises,
mais aussi pour des géométries simples (berceaux mentionnés par Frézier 1737, arcs
brisés en Toscane). Le principe de normalité sera de plus progressivement remis en
question au xixe siècle pour des raisons statiques, suite aux recherches sur les ponts
biais (Sakarovitch, 1992, p. 539-540, cit. 132 ; Rippmann, 2016).

Le principe de normalité permet néanmoins de souligner la disposition la plus
courante et la plus simple (12) pour le choix de l’inclinaison des joints d’un arc par
rapport à l’intrados, et de remarquer l’impossibilité de son application dans le cas
des plates-bandes (13). Nous reviendrons en détail sur ce point ultérieurement (voir
section 6.3).

Pour terminer sur le principe de normalité, remarquons que Monge produit des
solutions idéalisées, en l’appliquant rigoureusement aux dômes elliptiques, mais dont
la diﬃculté rend la construction laborieuse. Cet exemple est démonstratif de l’impossibilité, du point de vue des nécessités constructives de chantier, d’appliquer le
principe de normalité dans toutes les situations. Ainsi, chez Monge, le principe de
normalité est présent sous une forme plus stricte, énoncée dans les leçons de mathématique de l’École normale de 1794 (publiés par Dhombres, 1992, p. 419, cit. 70).
Les conditions de Monge pour choisir la coupe à donner aux voussoirs sont résumées
par Sakarovitch (1992, p. 536) ainsi :

(10). Cet exemple est relevé par Cejka (1978, 2-17).
(11). Les couvrements courbes ne sont cependant pas les seules structures où cette problématique
du choix de l’orientation des joints se pose. Dans le cas des piédroits, et comme pour les murs,
les assises sont généralement horizontales. Il ne s’agit cependant pas de la seule solution. Dupuit
indique, concernant l’orientation des assises des piles de ponts : « Ce que le constructeur doit plutôt
rechercher, c’est que la direction du joint soit normale à la courbe des pressions, parce qu’alors tout
glissement du massif sur le plan de joint devient impossible. » (Dupuit, 1870, p. 32)
(12). Si les coupes horizontales et verticales sont exclues.
(13). L’impossibilité d’appliquer le principe de normalité aux plates-bandes est mentionné explicitement par Frézier (Frézier, 1737, p. 281-282, cit. 30)

83

<!-- p. 85 -->

Chapitre 5. Stéréotomie et coupe des pierres

Fig 5.6 – Lignes de courbure de l’ellipsoïde, devant correspondre aux joints selon
Monge, d’après Sakarovitch (1992, p. 537)

\1. « L’orthogonalité des joints du voussoir avec la surface de la voûte. Cette
condition s’impose pour des raisons statiques » ;

\2. « L’orthogonalité des joints d’un même voussoir », pour les mêmes raisons
statiques ;

\3. « Les surfaces des joints des voussoirs doivent être développables », pour des
raisons pratiques de taille ;

\4. « Les lignes de division de la surface doivent aussi porter le caractère de la
surface. Cette exigence, purement esthétique, semble s’imposer au géomètre
avec autant de force que les précédentes. »

Monge poursuit : « Pour résoudre les problèmes statique, géométrique, esthétique
et pratique que pose l’appareillage des voûtes, la seule solution consiste à choisir
comme lignes de joint les lignes de courbure de la surface. Les conditions 1 et 3
énoncées ci-dessus suﬃsent d’ailleurs, à elles seules, à imposer de suivre les lignes de
courbure ; [...] ».

Monge remarque que dans le cas simple des surfaces de révolution la pratique des
anciens répondait aux conditions qu’il propose (voussoirs divisés par les méridiens et
les parallèles), avec notamment des lignes de joints horizontales. Cependant dans le
cas d’un ellipsoïde, les conditions de Monge conduisent à un appareil plus complexe
(ﬁg. 5.6) qui ne fut pas employé en pratique (14) (Sakarovitch, 1992, p. 540, cit. 133).

(14). La solution de Monge pour l’appareillage des dômes elliptiques sera cependant mentionnée
régulièrement dans les traités du xixe siècle, comme par exemple à l’article « Appareil » de Pillet
(1888, cit. 106).

84

<!-- p. 86 -->

Chapitre 6

Typologie constructive des
plates-bandes

Résumé : Ce chapitre présente un essai de typologie constructive des plates-bandes.
La terminologie spéciﬁque aux plates-bandes est d’abord introduite, ainsi que l’utilisation du terme plate-bande dans les traités du xiiie au xviie siècle. Les caractéristiques
formant la typologie proposée sont le nombre de claveaux (généralement impair), la
hauteur de la plate-bande (donnée relativement à sa portée), les détails constructifs
(comme l’utilisation des crossettes, des balles de plomb etc.), et l’utilisation du métal
dans les plates-bandes. La relation qu’entretiennent coupe des pierres et décor est
examinée, avec notamment l’utilisation des refends pour souligner l’appareil, ou au
contraire simuler un faux-appareil, et la non ﬁabilité des dessins et gravures pour
représenter l’appareil des plates-bandes. Au sein de la typologie proposée, l’inclinaison des joints des plates-bandes fait l’objet d’une étude approfondie. Le rejet des
joints verticaux pour la construction des plates-bandes est présenté. Ce rejet conduit
à l’utilisation de joints inclinés sur la verticale. Nous étudions l’évolution des règles
géométriques qui permettent le tracé des joints inclinés, et les informations que ces
règles livrent sur les pratiques respectives des architectes et des appareilleurs.

85

<!-- p. 87 -->

Chapitre 6. Typologie constructive des plates-bandes

Sommaire
6.1 Terminologie . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 87
6.1.1 Plates-bandes et linteaux . . . . . . . . . . . . . . . . . . . 87
6.1.2 Classiﬁcation des plates-bandes selon les joints . . . . . . 89
6.2 Nombre impair des claveaux . . . . . . . . . . . . . . . . . . . . . 96
6.3 Inclinaison des joints . . . . . . . . . . . . . . . . . . . . . . . . . 98
6.3.1 Principe d’inclinaison . . . . . . . . . . . . . . . . . . . . . 98
6.3.2 Rejet des joints verticaux . . . . . . . . . . . . . . . . . . 98
6.3.3 Règles géométriques pour déterminer l’inclinaison . . . . . 99
6.3.4 Évolution des règles dans les traités . . . . . . . . . . . . . 101
6.3.5 Méthodes de tracés . . . . . . . . . . . . . . . . . . . . . . 110
6.3.6 Architectes et appareilleurs . . . . . . . . . . . . . . . . . 113
6.3.7 Les « portes bombées »et les « croisées bombées » . . . . . 115
6.4 Hauteur des claveaux . . . . . . . . . . . . . . . . . . . . . . . . . 116
6.5 Détails constructifs . . . . . . . . . . . . . . . . . . . . . . . . . . 121
6.5.1 Crossettes . . . . . . . . . . . . . . . . . . . . . . . . . . . 121
6.5.2 Balles de plomb, cailloux, goujons et os de bœufs . . . . . 123
6.5.3 La contre-ﬂèche . . . . . . . . . . . . . . . . . . . . . . . . 126
6.5.4 Lit de carrière . . . . . . . . . . . . . . . . . . . . . . . . . 128
6.6 Utilisation du métal dans les plates-bandes . . . . . . . . . . . . . 128
6.6.1 Exemples de plates-bandes avec armatures métalliques . . 128
6.6.2 L’armature : linteau ou tirant . . . . . . . . . . . . . . . . 132
6.6.3 Opposition aux armatures . . . . . . . . . . . . . . . . . . 133
6.7 Coupe des pierres et décor . . . . . . . . . . . . . . . . . . . . . . 134
6.7.1 Refends et faux-appareil . . . . . . . . . . . . . . . . . . . 134
6.7.2 Ablaq . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 136
6.7.3 Non-ﬁabilité des dessins et gravures . . . . . . . . . . . . . 137

86

<!-- p. 88 -->

Chapitre 6. Typologie constructive des plates-bandes

6.1 Terminologie

6.1.1 Plates-bandes et linteaux

Le couvrement est un « organe ou ouvrage limitant par le haut un entrecolonnement, une baie, une pièce, un vaisseau, etc. » (Pérouse de Montclos, 2007, p. 125).
Parmi les variétés de couvrement ﬁgurent le linteau et la plate-bande :
— le linteau est un « bloc de pierre, pièce de bois ou de métal couvrant une baie
et présentant un soﬃte » (2007, p. 126) ;
— la plate-bande est un « organe clavé porté par deux points d’appui et présen-
tant un soﬃte » (2007, p. 126).
L’architrave est un « linteau ou Plate-bande portant sur des supports verticaux. L’architrave monolithe est un linteau ; l’architrave clavée, une plate-bande. [...] L’architrave est généralement comprise dans un entablement dont elle constitue la partie
inférieure » (Pérouse de Montclos, 2007, p. 128).

Le soﬃte est la « face inférieure plane et dégagée d’un linteau et d’une platebande » (Pérouse de Montclos, 2007, p. 144). L’arasement est la « face supérieure
horizontale d’un linteau ou d’une plate-bande, exceptionnellement d’un arc ou d’une
voûte » (2007, p. 143). Bien que les termes intrados et extrados soient selon certains
auteurs réservés aux faces inférieures et supérieures curvilignes des arcs et des voûtes
(2007, p. 143-144), nous utilisons ces termes à la place de soﬃte et arasement dans
ce document, comme le fait Frézier (1738, p. 66, cit. 34) (1).
Le terme plate-bande est introduit au xiiie siècle en France (Nollet, 2012, cit. 139).
La seule source écrite du xiiie siècle traitant de la coupe des plates-bandes est le carnet
de Villard de Honnecourt. Ce dernier n’utilise pas le terme plate-bande. Il désigne les
arcs plats sous le terme « pendans rivlés » (« pendans réglés »), et le couvrement plat
d’une baie sous le terme « voussure rivleie » (« voussure réglée ») (Bechmann, 1993).

Dans le Premier tome de l’architecture, De l’Orme utilise le terme de plate-bande
à deux reprises : « platte béde » (1567, 220r) et « plates bandes » (1567, 225v). Il
continue par ailleurs à utiliser d’autres termes, comme « couvertures d’une pièce »
et « [couvertures] de plusieurs pièces ». Léonard et Serlio utilisent pour leur part les
termes d’architraves à plusieurs parties (Nollet, 2012, cit. 140). Les termes « supercilio » et « architrave » utilisés par Serlio (Serlio, 1537, Cit.1 et 2) sont traduits en
français par Coecke en 1542 sous les termes « supercile », « architrabe » et « architrave », et le terme « cunei » (claveaux) par « penantz ».
Tandis que Jousse (2) (1642) puis François Blondel (3) (1675, p. 434) utilisent les
termes « plate bande » ou « platte-bande » pour désigner les architraves clavées,
Félibien ne référence en 1676 dans son dictionnaire que les acceptions relatives à la
décoration pour la « platte-bande », et ne fait donc pas référence aux architraves

(1). Les citations sont numérotées par ordre chronologique de publication. Le renvoi « cit. 34 » fait
référence à la citation numéro 34, les citations étant regroupées dans l’annexe A.
(2). Jousse utilise le terme de « plate bande » pour les trois tracés qu’il propose à ce sujet : « De la
plate Bande droite, ou plat Fond », « De la Plate bande biaize », « Plate bande sous la Tour ronde. »
(Jousse, 1642).
(3). François Blondel consacre une page dans son cours d’architecture à la description des « Plattesbandes que l’on fait servir pour linteaux aux Portes & aux Fenestres, & pour architraves aux Colonnes
isole [...] » (Blondel, 1675, p. 434).

87

<!-- p. 89 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.1 – Plates-bandes droites et bombées, d’après D’Aviler (1691, Pl. 66), détail

clavées (Félibien, 1676, p. 698, cit. 13). En 1691, d’Aviler ajoute dans son dictionnaire
en plus des déﬁnitions liées à la décoration (ﬁg. 6.2) la déﬁnition de la plate-bande
telle que nous l’étudions (4) ici (D’Aviler, 1691, p. 237, cit. 18 – ﬁg. 6.1). Il déﬁnit
la « Platebande de baye », la « Platebande bombée & reglée », et la « Platebande
circulaire ».

Fig 6.2 – Chapiteau et entablement doriques, d’après D’Aviler (1691, Pl. 12),
planche complète et détail

Les auteurs postérieurs à d’Aviler utilisent tous le terme « plate-bande ».

Plates-bandes courbes

Nous appelons plates-bandes courbes les plates-bandes dont la projection sur le
plan horizontal forme une courbe. Ce type de plate-bande se rencontre par exemple

(4). D’Aviler déﬁnit également les « platebandes de compartiment », « platebandes de pavé », « platebandes de parquet » et « platebandes de parterre » qui ne se rapportent pas au concept de platebande que nous étudions ici.

88

<!-- p. 90 -->

Chapitre 6. Typologie constructive des plates-bandes

dans les plates-bandes sous tour ronde dont la coupe des pierres est donnée par Jousse
(1642). Les exemples construits que nous avons relevés sont les suivants :
— « Entre 1654 et 1657, Antoine Le Pautre réalise l’architrave incurvée dans la
cour de l’hôtel de Beauvais à Paris, en utilisant des claveaux de pierre renforcés
de barres métalliques pour porter un important secteur de parois » (Tibières,
2012, voir ﬁg. 6.3) ;
— D’Aviler (1691) mentionne l’« Entablement Ionique de l’église de Saint André
sur le Quirinal à Rome, qui subsiste avec beaucoup de portée par l’artiﬁce de
son apareil » ;
— Quatremère de Quincy (1825) mentionne les « plates-bandes circulaires » des
temples circulaires comme ceux de Vesta et de la Sybille. Cependant ces plates-
bandes sont probablement des architraves monolithes, et non des architraves
clavées ;
— Viollet-Le-Duc (1859a) mentionne la plate-bande de la cheminée du logis des
clergerons, dans la cathédrale du Puy-en-Velay, qui est composée de deux
claveaux soutenus par des consoles (ﬁg. B.48) ;
— Adam (1989, p. 188) mentionne la plate-bande (en brique) d’une fenêtre percée
dans un mur sur plan circulaire, dans la villa des Mystères.

Fig 6.3 – Plate-bande courbe, cour de l’hôtel de Beauvais à Paris,
par Antoine Le Pautre (1654-1657)

Nous proposons également d’intégrer sous ce terme les plates-bandes dont la projection sur le plan horizontal forme une droite brisée. Nous verrons des exemples de
ce type à propos des cheminées construites au xive siècle en France (ﬁgures B.41,
B.42 et B.43).

6.1.2 Classiﬁcation des plates-bandes selon les joints

Nous proposons de classer les plates-bandes suivant la géométrie des joints selon
les catégories suivantes :
— plates-bandes à joints inclinés ;
— plates-bandes à joints inclinés à lits brisés ;
— plates-bandes à joints inclinés à double coupe ;
— plates-bandes à joints verticaux ;
— plates-bandes à joints curvilignes ;
— plates-bandes à joints en X ;

89

<!-- p. 91 -->

Chapitre 6. Typologie constructive des plates-bandes

— plates-bandes en fausse-coupe.
Les sous-catégories suivantes se superposent aux catégories précédentes :
— plates-bandes appareillées à crossettes ;
— plates-bandes à tenons ;
— plates-bandes à clavettes ;
— plates-bandes à balles de plomb.
Il existe également des plates-bandes présentant des joints horizontaux, séparant
deux ou trois rangs de claveaux. Lorsque deux plates-bandes sont superposées, l’ensemble est appelé « plate-bande à deux rangs de claveaux » (Pérouse de Montclos,
2007, p. 126).

Plates-bandes à joints inclinés

Les plates-bandes à joints inclinés sont formées de claveaux dont les joints forment
un angle non nul avec la verticale (ﬁg. 6.4).

La coupe des pierres la plus courante correspond à des joints rayonnant autour
d’un centre placé sur l’axe de symétrie de la plate-bande (ﬁg. 6.5 à d.). Les règles
donnant la position du centre de rayonnement et, à partir de ce dernier, le découpage
en claveaux varient suivant les époques et les professions (architecte, appareilleur).
Nous reviendrons en détail sur cette question ultérieurement (section 6.3).

Fig 6.4 – Plate-bande à joints Fig 6.5 – Plate-bande appareillée à crossettes
inclinés, d’après Diderot et (à g.), et à joints inclinés suivant la règle du
d’Alembert (1756) triangle équilatéral (à d.), d’après Diderot et
d’Alembert (1765a)

Les joints peuvent également présenter une inclinaison constante de part et d’autre
de l’axe central de la plate-bande. Cette méthode simpliﬁe les épures, car tous les
claveaux situés d’un côté de la clé présentent alors la même géométrie, alors que
dans le cas des joints rayonnant chaque claveau présente une géométrie unique. Ce
cas se rencontre moins fréquemment, mais il existe des exemples (ﬁg. 6.6). Le plus
souvent cependant, ce type de dessin correspond à des linteaux enduits avec dessin
d’un faux-appareil de plate-bande (ﬁg. 6.7). L’usage de linteaux enduits pour simuler
une plate-bande est mentionnée par Blondel et Patte (1777a, p. 290, cit. 60).

90

<!-- p. 92 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.6 – Plate-bande à joints inclinés à inclinaison constante, et à lits brisés,
2 rue Métropole, Chambéry

Fig 6.7 – Faux-appareil d’une plate-bande dessinée sur enduit,
13 rue des Beaux-Arts à Paris et 72 rue Saint-Louis-en-L’Ile à Paris

91

<!-- p. 93 -->

Chapitre 6. Typologie constructive des plates-bandes

Plates-bandes à joints inclinés à lits brisés

Selon la terminologie proposée par Pérouse de Montclos (2007), les plates-bandes
à lits brisés sont des plates-bandes à joints inclinés dont la partie inférieure du joint
est verticale, et donc perpendiculaire à l’intrados. Ce système est désigné de multiples
façons dans la littérature :
— Patte (1769, p. 280) les nomme claveaux « taillés à crosettes (5) par le bas » ;
— Rondelet (1804, p. 93) ne nomme pas explicitement ce système, et décrit la
partie inférieure sous le terme « ligne à plomb » ;
— Douliot (1825, p. 81) appelle « facettes d’équerre » les parties verticales de ces
joints ;
— Adhémar (1845, p. 12) ne nomme pas explicitement ce système, et décrit la
partie inférieure sous le terme de « coupe verticale » ;
— Monduit (1889, p. 72) utilise le terme de « crossette verticale ou à plomb ».
Les facettes verticales des lits brisés peuvent être de hauteur égale pour tous les
joints, ou réglés suivant un arc de cercle, comme dans le mémoire de Bullet de 1704
pour l’Académie royale d’architecture (ﬁg. A.4 p. 338), ou chez Rondelet (ﬁg. 6.8).
Adhémar (1845, p. 12) et Chaix (1890, p. 172) présentent les deux systèmes conjointement.

Douliot (1825, p. 79), Chaix (1890, p. 172, cit. 109), et l’Association ouvrière des
Compagnons du devoir (1996, p. 130, cit. 120) préconisent la même hauteur pour les
facettes verticales : 2 pouces ≈5 cm. A contrario, Monduit (1889, p. 72, cit. 95) parle
simplement d’une « hauteur indéterminée » pour les facettes verticales.

Douliot (1825, p. 79) propose une solution avec lits brisés doublement, reprise également par Chaix (1890) (ﬁg. 6.9). Les plates-bandes à lits brisés doublement sont plus
rares que celles à joints brisés (simplement), mais des exemples existent (ﬁg. B.46). Les
plates-bandes peuvent ne présenter des lits brisés qu’au niveau des sommiers, c’est-àdire aux joints qui présentent la plus grande inclinaison sur la verticale, comme par
exemple au 53 rue Saint-Antoine à Paris.
L’utilisation des lits brisés semble assez courante au xviie et xviiie siècle en
France, et nous en verrons de nombreux exemples au chapitre 9 concernant les
exemples construits.

Plates-bandes à joints inclinés à double coupe

Les plates-bandes à joints inclinés à double coupe sont des plates-bandes dont
les joints inclinés présentent deux pentes. Deux centres de rayonnement sont utilisés
pour déﬁnir la coupe (Chaix, 1890, p. 174 ; Association ouvrière des Compagnons du
devoir, 1996, p. 128).

Ce type de plate-bande est utilisé par exemple pour la plate-bande d’un tombeau
dans l’Antiquité (ﬁg. 6.10), et au musée Carnavalet à Paris.

(5). Patte utilise à plusieurs reprises le terme de « crosettes » avec un seul s en 1769 et 1777a, il ne
s’agit donc probablement pas d’une coquille.

92

<!-- p. 94 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.8 – Plates-bandes à lits brisés Fig 6.9 – Plate-bande à lits doublement
suivant un arc de cercle, brisés, d’après Chaix (1890, p. 172)
d’après Rondelet (1828, Pl. XXIX)

Fig 6.10 – Plates-bandes à joints inclinés à double coupe, tombeau de Cecilia
Metella (Via Appia, Italie), d’après Rondelet (1828, Pl. XXIX)

93

<!-- p. 95 -->

Chapitre 6. Typologie constructive des plates-bandes

Plates-bandes à joints verticaux

Les plates-bandes à joints verticaux sont composées de claveaux à panneaux de
tête rectangulaires. Du point de vue géométrique, elles correspondent à des platesbandes à joints inclinés dont le centre de convergence serait placé inﬁniment bas.
Il est parfois diﬃcile de distinguer si les joints sont verticaux ou fortement inclinés
(ﬁg. 6.16).
Nous déﬁnirons ci-dessous également les plates-bandes en fausse-coupe, qui se distinguent des plates-bandes à joints verticaux par l’existence d’un joint incliné masqué.

Plates-bandes à joints curvilignes

Les plates-bandes à joints curvilignes, également appelées « à joints courbes »,
présentent des joints dont le tracé est une surface réglée non plane (ﬁg. B.23). Nous
présenterons quelques rares exemples construits en France au Moyen Âge dans des
portails d’églises. Ce type de plate-bande est généralement associé à l’architecture
islamique (Cejka, 1978 ; Rondelet, 1804, p. 101, cit. 72).

Plates-bandes en fausse-coupe

Selon Pérouse de Montclos (2007, p. 148), « les lits sont dits en fausse-coupe,
lorsque leurs joints ne convergent pas : dans la plate-bande en fausse-coupe les joints
peuvent même être verticaux, seule la queue des claveaux étant taillée en coupe ».
Cela signiﬁe que les joints sont composés de deux plans. Le premier est un plan
vertical, qui forme le joint vertical visible sur le front de la plate-bande. Le second est
un plan incliné sur la verticale, qui forme la seconde partie masquée du joint (ﬁg. 6.11).
Nous reviendrons en détail sur la typologie de la fausse-coupe et son histoire dans le
chapitre 8.

Plates-bandes à joints en X

Les plates-bandes à joints en X sont constituées de claveaux tous identiques,
composés chacun de deux trapèzes (ou triangles) tête-bêche (ﬁg. 6.12). Comme pour
les plates-bandes en fausse-coupe, l’observation du front de l’arc ne révèle que la
moitié des joints qui composent la plate-bande. Nous reviendrons sur la typologie des
plates-bandes à joints en X et leur histoire le chapitre 7.
Il existe peu d’exemples construits de ce type de plate-bande. Nous verrons cinq
exemples potentiels, dont aucun n’est situé en France. En raison de cette rareté, il
n’existe pas de terminologie établie pour désigner les plates-bandes à joints en X. La
similitude conceptuelle entre les plates-bandes en fausse-coupe et les plates-bandes
à joints en X pourrait suggérer de nommer ces dernières plates-bandes en faussecoupe à joints alternés. Cependant en raison du caractère anachronique de cette
description, le terme « fausse-coupe » apparaissant en France deux siècles environ
après la construction des plates-bandes à joints en X, et pour éviter d’utiliser un
qualiﬁcatif (fausse) préjugeant des qualités de l’objet alors que ce type de plate-bande
possède des propriétés mécaniques intéressantes, nous retiendrons dans ce document
le terme neutre de joints en X.

94

<!-- p. 96 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.11 – Plate-bande en fausse-coupe, Fig 6.12 – Plate-bande à joints en X,
d’après Diderot et d’Alembert (1756) d’après Ruskin (1849 ; 1855 pour
ce dessin)

Plates-bandes appareillées à crossettes

Une « plate-bande appareillée à crossettes » est une plate-bande dont les joints
présentent un petit ressaut situé à mi-hauteur du joint environ (ﬁg. 6.5 à gauche).
Cette plate-bande peut être appareillée à simples crossettes (une seule crossette par
joint), ou plus rarement à doubles crossettes (6) (deux crossettes par joint). Une certaine confusion règne concernant le terme crossette, car ce dernier est également
utilisé pour désigner :
— les joints à lits brisés (Patte, 1769, p. 280) ;
— les claveaux en état de charge (Frézier, 1738, p. 66, cit. 35) ;
— les joints à tenons (Chaix, 1890, p. 175).
Dans les plates-bandes à « claveaux en état de charge », selon la terminologie donnée par Douliot (Douliot, 1825, p. 80, cit. 80), un ou plusieurs claveaux font « retour
horizontalement dans une assise des parties au-dessus du couvrement » (7) (ﬁg. 6.13).

Le terme « à crossettes » est parfois remplacé par « à redans » (Gautier, 1717,
p. 17), ou « ressauts » et « redens » (Frézier, 1738, p. 66, cit. 35).

Fig 6.13 – « Plates-bandes à claveaux en état de charge », d’après Douliot (1825,
Pl. 10)

(6). « Le claveau est dit à crossette, à double crossette, lorsque ses lits en coupe présentent un ou
deux petits ressauts, soit pour faire liaison avec le claveau voisin, soit pour faire retour horizontalement dans une assise des parties au-dessus du couvrement » (Pérouse de Montclos, 2007, p. 148).
(7). Cette déﬁnition est de Pérouse de Montclos (2007, p. 148) qui l’applique cependant au terme
« à crossettes ».

95

<!-- p. 97 -->

Chapitre 6. Typologie constructive des plates-bandes

Plates-bandes à tenons

« Le claveau est dit à tenon lorsque l’un des lits présente un tenon qui s’assemble
dans une entaille du claveau voisin. Le tenon interne est un tenon qui n’apparaît pas
en parement. Plate-bande à tenons » (Pérouse de Montclos, 2007, p. 148-149).

Chaix (1890, p. 175) appelle les tenons intérieurs « crossettes intérieures ».

Plates-bandes à clavettes

« Dans l’arc, la plate-bande à clavettes, les claveaux sont assemblés par une clavette, sorte de tenon qui n’est pas solidaire des claveaux mais introduit de force après
la pose dans des entailles entre ces claveaux. » (Pérouse de Montclos, 2007, p. 149).

Les plates-bandes à clavettes ﬁgurent dans Le premier tome de l’architecture de
Philibert De l’Orme (1567) ; voir ﬁgure 6.14. Il en existe de rares exemples, avec des
joints verticaux (voir section 9.4.2)

Fig 6.14 – Plate-bande à clavettes, d’après De l’Orme (1567)

6.2 Nombre impair des claveaux

Dès que cela est précisé dans les traités, le nombre de claveaux composant les
plates-bandes est impair, ce qui induit la présence d’un claveau central appelé clé
(ou clef ). Les auteurs suivants font explicitement référence au nombre impair des
claveaux composant une plate-bande :
— Serlio (1537, 10v, cit. 2) « in numero disparo » ;
— Blondel (1675, p. 434, cit. 11) ;
— Tiercelet (1728, p. 61, cit. 25) ;
— Frézier (1738, p. 65) ;
— Roland Le Virloys (1770a, p. 451) ;
— Blondel et Patte (1777a, p. 288, cit. 59) ;
— Douliot (1825, p. 77, 78) ;
— Adhémar (1845, p. 10) préconise de diviser l’intrados « en un nombre impair
de parties égales » ;
— Chaix (1890, p. 170, 171).
Cette préconisation théorique semble très suivie en pratique. Tous les exemples de
plates-bandes reproduits dans ce document ont un nombre impair de claveaux. Cependant, il existe des plates-bandes avec un nombre important de claveaux (n ≥9),

96

<!-- p. 98 -->

Chapitre 6. Typologie constructive des plates-bandes

chaque claveau ayant une largeur variable, et où la clé n’est pas positionnée exactement au centre de la plate-bande (8).

Il existe néanmoins des plates-bandes avec un nombre pair de claveaux au ProcheOrient, en Sicile et dans les Pouilles (9). Ces plates-bandes appartiennent plutôt à des
constructions modestes, mais nous ne disposons pas de photos pour documenter ces
cas.

Les mêmes observations sont valables pour les arcs courbes (nombre impair de
claveaux de façon presque systématique), à l’exception des arcs brisés où il existe en
général en France un joint vertical à la clé, divisant ainsi l’arc en un nombre pair
de claveaux (Viollet-Le-Duc, 1858, cit. 84 ; Choisy, 1899b, p. 146). A contrario, dans
l’architecture islamique les arcs brisés peuvent présenter un joint vertical à la clé ou
non (Cejka, 1978, 4-39).

Les plates-bandes dans lesquelles les sommiers portent en encorbellement et se
rejoignent au milieu de la portée correspondent d’un point de vue typologique à des
plates-bandes à zéro claveau, et se trouvent donc à la limite de notre déﬁnition de
la plate-bande ; ces structures, qui peuvent théoriquement porter par encorbellement
sans se toucher au centre de la plate-bande, et donc sans générer aucune poussée,
tiennent à la fois de la plate-bande (car il y a un joint), et du linteau (car la portance
de la structure est liée à la résistance interne à la ﬂexion des pierres). Un exemple de
ce type est présent aux fenêtres du château à Coulonges-les-Royaux (Nollet, 2012).
La cheminée du logis des Clergerons au Puy-en-Velay appartient également à ce type
de plate-bande (ﬁg. B.48).

De façon générale, les exemples présentés dans cette thèse comportent en majorité trois, cinq ou sept claveaux, avec quelques exemples avec un nombre supérieur de
claveaux notamment pour les grandes portées (dix-sept claveaux pour le fronton de
l’église Saint-Gervais-Saint-Protais à Paris, ﬁg. B.62). Les exemples de plates-bandes
à un claveau sont plus rares, à l’exception de Lyon, où les plates-bandes des immeubles sont dans leur majorité construites avec un large claveau unique, souvent
à crossettes. Les plates-bandes des édiﬁces monumentaux à Lyon peuvent également
être construites avec un claveau unique (ﬁg. 6.15 et 6.16).

(8). Information transmise oralement par Jérémie Fierens, Ateliers de Saint-Jacques.
(9). Information transmise oralement par Maurizio Brocato.
(10). La chapelle Notre-Dame-de-Pitié de l’Hôtel-Dieu à Lyon est construite par l’architecte
Guillaume Ducellet, qui meurt en 1641 avant la ﬁn des travaux. Les travaux sont poursuivis par
Claude Chana et Simon Le Rupt, maîtres-maçons. L’église est terminée, hors façade, en 1644. La
façade est construite en 1646 sur les plans de Le Muet (Mignot, 1991).
La chapelle Notre-Dame-de-Pitié fait partie de l’Hôtel-Dieu de Lyon, mais ne doit pas être
confondue avec la chapelle des malades de l’Hôtel-Dieu construite par Souﬄot au xviiie siècle, cette
dernière comportant des plates-bandes en fausse-coupe que nous présenterons au chapitre 8.

97

<!-- p. 99 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.15 – Lyon, hôtel de ville Fig 6.16 – Lyon, chapelle
Notre-Dame-de-Pitié (10), façade de 1646
sur des plans de Le Muet

6.3 Inclinaison des joints

6.3.1 Principe d’inclinaison

Le premier texte à aborder directement le problème mécanique posé par la platebande est In mechanica Aristotelis problemata exercitationes, textes rédigés par Baldi
de 1580 à 1615 et publiés à titre posthume (Becchi, 2012). Ce texte souligne que les
plates-bandes composées de claveaux qui n’ont pas la forme de coins, et qui sont donc
à joints verticaux, ne peuvent se soutenir (cit. 7).

Ce principe de non stabilité des plates-bandes à joints verticaux est exprimé explicitement chez les auteurs suivants :
— Baldi (1580-1615, cit. 7) ;
— Frézier (1738, p. 64, cit. 32) ;
— Rondelet (1804, p. 92, cit. 74) ;
— Bazin (1888, p. 40, cit. 105) ;
— Chaix (1890, p. 170, cit. 108).
Plus souvent, les auteurs des traités d’architecture et de coupe des pierres de l’Époque
Moderne préconisent une inclinaison particulière pour les joints, selon des règles que
nous verrons dans la suite, indiquant donc implicitement que les plates-bandes ne
devraient pas être construites à joints verticaux.

Nous appelons donc principe d’inclinaison le principe selon lequel les joints d’une
plate-bande doivent être inclinés, pour donner aux claveaux la forme de coins nécessaire à leur stabilité selon les traités de coupe des pierres.

6.3.2 Rejet des joints verticaux

Il existe donc deux principes antagonistes pour le choix de l’inclinaison des joints
d’une plate-bande :
— le principe de normalité, que nous avons présenté dans le chapitre 5, et qui
est un principe général de la coupe des pierres ;

98

<!-- p. 100 -->

Chapitre 6. Typologie constructive des plates-bandes

— le principe d’inclinaison des joints sur la verticale, qui est un principe spéciﬁque
aux plates-bandes.
Le principe d’inclinaison l’emporte sur le principe de normalité dans le cas des platesbandes (Rondelet, 1804, p. 92, cit. 74 ; Bazin, 1888, p. 40, cit. 105). Les auteurs des
traités prescrivent systématiquement l’usage de joints inclinés. Nous verrons dans la
sous-section suivante quelles règles sont utilisées pour choisir l’inclinaison, et comment
les joints sont ensuite dessinés.

Le non-respect du principe de normalité est cependant problématique, parce que
l’inclinaison des joints engendre des angles aigus (ou aiguïtés), en particulier à proximité des sommiers. Certains auteurs proposent pour cette raison l’utilisation des lits
brisés, qui sont une solution de compromis, où la grande partie du joint est inclinée,
sauf la partie inférieure du joint qui est normale à l’intrados (Chaix, 1890, p. 172,
cit. 109 ; Association ouvrière des Compagnons du devoir, 1996, p. 130, cit. 120 ; Académie royale d’architecture, compte-rendu du 24 février 1710 cit. 162).

L’utilisation des lits brisés est au contraire critiquée par Frézier (1738). Il indique
que cette pratique diminue la hauteur utile de la plate-bande et aﬀaibli donc la platebande (Frézier, 1738, p. 66, cit. 35).

6.3.3 Règles géométriques pour déterminer l’inclinaison

Nécessité et non-unicité de la règle géométrique

Dans les plates-bandes, les joints ne sont pas normaux à l’intrados mais inclinés
sur la verticale, pour les raisons que nous venons de voir. Le principe de normalité
(au sens mathématique du terme) des joints par rapport à l’intrados, qui donne pour
les arcs et voûtes courbes l’inclinaison, n’est donc pas applicable. Dans ce contexte,
il est nécessaire d’avoir une autre règle qui permette de déterminer l’inclinaison des
joints.

Les règles géométriques présentées par les traités reposent pour la plupart sur la
détermination d’un centre vers lequel convergeront les joints, donnant ainsi aux joints
une inclinaison variable avec la verticale, l’inclinaison étant maximale au niveau des
sommiers, et minimale au niveau de la clé. Puisque ce centre n’est pas donné par la
forme de l’intrados, comme cela est généralement le cas pour les intrados courbes,
plusieurs règles géométriques coexistent, basées sur la portée de la plate-bande le plus
souvent.

Frézier (1738, p. 64, cit. 32) souligne qu’il y a dans ces diﬀérentes règles géométriques « plus de disposition de goût que de Géométrie ». En termes contemporains,
il indique donc que ces règles répondent plus à une problématique esthétique qu’à la
résolution d’un problème mécanique.

Trois règles courantes pour les joints rayonnants

Les trois règles les plus courantes dans la littérature pour tracer les joints inclinés
d’une plate-bande sont basées sur le dessin d’un triangle, dont la base correspond à
l’intrados de la plate-bande, et dont le sommet inférieur donne le centre de rayonnement des joints. Ces trois règles sont (ﬁg. 6.17) :

99

<!-- p. 101 -->

Chapitre 6. Typologie constructive des plates-bandes

— la règle du triangle équilatéral, où les longueurs des côtés du triangle corres-
pondent à la portée de la plate-bande ;
— la règle du « 1 pour 2 », où la hauteur du triangle vaut deux fois la demi portée
de la plate-bande ;
— la règle du « 1 pour 3 », où la hauteur du triangle vaut trois fois la demi portée
de la plate-bande.

Fig 6.17 – Trois règles géométriques donnant l’inclinaison des joints d’une
plate-bande

Ces méthodes utilisent la portée, qui est mesurée au niveau de l’intrados. La déﬁnition de la portée ne pose pas de problème dans le cas où les faces inférieures des
claveaux occupent exactement la portée libre couverte par la plate-bande, comme
dans l’exemple dessiné par Jousse (ﬁg. 6.22). Cependant les sommiers qui supportent
la plate-bande peuvent présenter un surplomb ou encorbellement plus ou moins prononcé (ﬁg. 6.21 à gauche et à droite) par rapport au nu du tableau de la baie ou par
rapport au bord du chapiteau, ou au contraire un léger retrait (ﬁg. 6.21 au centre).
Il existe donc plusieurs déﬁnitions possibles pour la portée de la plate-bande, comme
nous en verrons l’illustration en étudiant les gravures de Serlio (1537). Dans le cas
général, il est délicat ne connaissant pas la portée de déterminer quelle règle a été
utilisée par l’appareilleur ou le dessinateur.
L’Association ouvrière des Compagnons du devoir (1996, p. 78) donne les trois
règles indiquées ci-dessus, et ajoute ensuite que l’espacement entre le centre de convergence et l’intrados peut également être réglé sur le nombre (impair) de claveaux.
— pour 5 claveaux, 3/2 de la portée (règle du « 1 pour 3 ») ;
— pour 7 claveaux, 4/3 de la portée (entre la règle du « 1 pour 3 » et celle du
« 1 pour 2 ») ;

100

<!-- p. 102 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.18 – Plates-bandes d’après Serlio (1537, 9v, 10v, 17v)

— pour 9 claveaux, une fois la portée (règle du « 1 pour 2 ») ;
— pour 11 à 13 claveaux, p 2/3 de la portée (proche de la règle du triangle
équilatéral).
Ce dernier procédé réglé sur le nombre de claveaux ne serait pas appliqué en pratique
par les tailleurs de pierre (11).

6.3.4 Évolution des règles dans les traités

Vitruve, De architectura

Au ier siècle avant J.-C., Vitruve donne des indications sur la coupe des pierres
des arcs en général (12), mais il ne donne aucune indication sur la coupe des pierres
des plates-bandes. Dans De architectura, livre VI, au chapitre 11, Vitruve n’évoque
que les systèmes de décharge au-dessus des linteaux.

Claude Perrault (1673, VI-11) illustre sa traduction en français de Vitruve d’un
dessin qui représente une plate-bande (ﬁg. 6.19), et qui ne correspond pas au texte
d’origine qui lui désigne un linteau. Donc ce dessin ne peut pas être pris comme
représentatif de l’inclinaison des joints préconisé par Vitruve. Rondelet remplacera d’ailleurs la plate-bande ajoutée par Perrault par une poutre en bois sur la
planche illustrant les principes constructifs donnés par Vitruve (Rondelet, 1805 –
voir ﬁg. 6.20).

Serlio (1537)

Serlio prescrit pour les plates-bandes de l’ordre toscan l’utilisation de joints rayonnant autour d’un centre unique (Serlio, 1537, 10v, cit. 2). Il ne donne pas d’indication
sur la position à donner à ce centre, mais ses dessins semblent correspondre à la
règle du triangle équilatéral. En eﬀet, considérons les plates-bandes dessinées aux
pages 9v, 10v et 17v (ﬁg. 6.18). Sachant que la hauteur des plates-bandes est le quart
de leur portée (Serlio, 1537, 10v, cit. 2), la portée est tantôt la portée libre de la
baie (ﬁg. 6.21 à gauche), tantôt la portée entre les faces latérales des sommiers de la

(11). Jérémie Fierens, qui a rédigé cette partie de l’encyclopédie des compagnons du devoir, nous a
indiqué que cette méthode proviendrait d’un article de Michal et Lerouge publié dans les Annales
des ponts et chaussées, mais que ce procédé n’est pas passé dans la pratique des tailleurs de pierres.
(12). Concernant la coupe des pierres des arcs en général chez Vitruve, voir la note (7) p. 80.

101

<!-- p. 103 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.19 – Illustration des systèmes de Fig 6.20 – Illustration des systèmes de
décharge de Vitruve, d’après Perrault décharge de Vitruve, d’après Rondelet
(1673, VI-11) (1805, Pl. LXVIII Fig. 1)

plate-bande (ﬁg. 6.21 au centre et à droite). Pour ce choix des portées, la règle du
triangle équilatéral est respectée (13) pour les trois plates-bandes considérées.

Fig 6.21 – Plates-bandes respectant la règle du triangle équilatéral d’après Serlio
(1537, 9v, 10v, 17v) ; voir également ﬁg. 6.18

En dehors du cas de Serlio qui précise la hauteur des plates-bandes en fonction
de la portée, ce qui permet de trouver la portée avant de s’intéresser à la position
du centre, il est diﬃcile de retrouver précisément la règle utilisée à partir des seuls
dessins d’un traité.

Le triangle équilatéral

En 1537, Serlio utilise la règle du triangle équilatéral sans la nommer explicitement dans son texte, comme nous l’avons vu ci-dessus. En 1567, De l’Orme préconise
l’utilisation de joints inclinés, qu’il appelle « commissures de pente » et « joints d’engraissement » (14) (De l’Orme, 1567, 225v, cit. 4). Il utilise à plusieurs reprises dans

(13). Dans le cas de la ﬁgure à droite sur la ﬁgure 6.21, la hauteur des claveaux les plus petits vaut
le quart de la portée.
(14). Le terme « joint d’engraissement » a été relevé par Nollet (2012, p. 280) qui indique qu’ils
signiﬁent joints inclinés.

102

<!-- p. 104 -->

Chapitre 6. Typologie constructive des plates-bandes

son traité la ﬁgure du triangle équilatéral (pour le dessin des fondations, l’emplacement des murailles, etc.), mais il n’en fait pas mention concernant l’inclinaison à
donner aux joints des plates-bandes.

Fig 6.22 – « Plate bande droite, ou plat Fond », d’après Jousse (1642, p. 202)

La première mention explicite de l’utilisation du triangle équilatéral dont nous
avons trouvé la trace dans les traités vient du traité de coupe des pierres de Mathurin Jousse en 1642. À partir de cette date, parmi les diﬀérents auteurs qui utilisent
cette règle explicitement, en nommant le triangle, ou en décrivant sa construction,
on trouve :
— Jousse (1642, p. 203), qui donne uniquement la description de la construction
géométrique, sans évoquer le triangle ou l’intérêt de cette inclinaison ;
— Blondel (1675, p. 434, cit. 11), qui utilise l’expression « triangle équilatéral
renversé » ;
— D’Aviler (1691, p. 122, cit. 17), qui utilise le terme de « triangle équilatéral »
mais uniquement dans le cas particulier de la porte rustique d’ordre toscan ; il
n’aborde pas le sujet de la coupe des pierres lorsqu’il décrit de façon générale
les plates-bandes (D’Aviler, 1691, p. 764, cit. 21) ;
— l’Académie royale d’architecture dans un compte-rendu de 1710 (cit. 162), qui
ajoute qu’en raison du risque de rupture des angles aigus formés par les cla-
veaux, la partie inférieure du joint devait être verticale (plate-bande à lits
brisés) ;
— De La Hire (1712, p. 75), qui utilise le terme de « triangle équilatéral » dans son
mémoire Sur la construction des voûtes dans les édiﬁces présenté à l’Académie
royale des sciences ;
— Gautier (1717, Pl. II Fig. 4), qui utilise l’expression de « triangle équilatéral » ;
— Bélidor (1729, Livre II p. 40, 61, cit. 26), qui utilise l’expression « triangle équi-
latéral » (ﬁg. 6.32) ;
— Frézier (1738, p. 65), qui utilise l’expression « triangle équilatéral », mais re-
commande de positionner le centre du triangle un peu plus bas, comme nous
le verrons ci-dessous ;
— Patte (1769, p. 280), qui indique à propos des claveaux des architraves de
la place Louis XV : « lesquels sont taillés à crosettes par le bas pour ôter
l’aiguité des angles, & leur donner plus de solidité. Ces claveaux par leur coupe

103

<!-- p. 105 -->

Chapitre 6. Typologie constructive des plates-bandes

tendent au sommet d’un triangle équilatéral dont la base est la longueur de
l’architrave » ; il reprend le même terme dans la partie consacrée à la poussée
des plates-bandes en général, dont la base est cette fois-ci « la largeur de
l’entre-colonne » (1769, p. 308), et mentionne le « triangle équilatéral » dans
la description de la voussure du quai Pelletier (1769, p. 216) ;
— Blondel et Patte (1777a, p. 267, 288, cit. 58, 59), qui indiquent que les claveaux
« tendent d’ordinaire au sommet d’un Triangle équilatéral g, dont la base
est la longueur de la Plate-bande ». Il s’agit cette fois-ci des plates-bandes
ordinaires. Le terme de triangle équilatéral est utilisé à plusieurs reprises dans
cet ouvrage ;
— Douliot (1825, p. 77, 81), qui précise que l’utilisation du triangle équilatéral est
la méthode la plus usitée, mais n’explique pas quelles sont les autres règles ;
— Adhémar (1845, p. 10), qui utilise l’expression de « triangle équilatéral » ;
— Monduit (1889, p. 72, cit. 97), qui utilise la méthode mais qui n’utilise pas le
terme « triangle équilatéral » ;
— Chaix (1890, p. 171).
D’autres auteurs utilisent la règle du triangle équilatéral sans la nommer ni décrire
sa construction :
— Serlio (1537, 9v, 10v, 17v), comme nous l’avons vu en détail précédem-
ment (ﬁg. 6.21) ;
— Diderot et d’Alembert (1765a) utilisent la règle du triangle équilatéral, sans la
nommer, sur la ﬁgure 6.5 qui est tirée de la planche liée à l’article concernant
les plates-bandes ;
— Simonin (1792, Pl. XXI – ﬁg. 8.3) utilise la règle du triangle équilatéral unique-
ment pour trouver l’inclinaison des joints des sommiers (les autres inclinaisons
ne donnent pas des joints rayonnants, nous reviendrons sur ce point lors de la
présentation des méthodes des tracés).

Règles du « 1 pour 2 » et « 1 pour 3 »

Les règles du « 1 pour 2 » puis du « 1 pour 3 » apparaissent après les premières
mentions du triangle équilatéral dans les traités. La première source écrite que nous
avons trouvée préconisant de placer le centre de convergence des rayons plus bas
que le sommet du triangle équilatéral se trouve dans le compte-rendu de l’Académie
royale d’architecture de 1698 (cit. 156). Quelques années plus tard, en 1710, la même
Académie préconisera de nouveau l’utilisation du triangle équilatéral (cit. 162).
Frézier (1738) aborde le sujet des plates-bandes en détail. Il n’indique pas par
écrit où il place ce centre – « Je baisse le centre de la coupe un peu plus que le
sommet du triangle équilateral » cit. 33 – mais son dessin (ﬁg. 6.23) correspond à la
règle du « 1 pour 2 », la règle du triangle équilatéral correspondant à une proportion √
de 1 pour 3 ≈1,73.
La règle du triangle équilatéral peut être évoquée (ou dessinée) sans que soient
mentionnées les deux autres règles. A contrario, si les règles du « 1 pour 2 » et du
« 1 pour 3 » sont mentionnées, alors il est systématiquement également fait référence
à la règle du triangle équilatéral.
Parmi les diﬀérents auteurs qui mentionnent implicitement ou explicitement la
règle du « 1 pour 2 » ou « 1 pour 3 » nous avons trouvé :

104

<!-- p. 106 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.23 – Plates-bandes et voûtes plates, d’après Frézier (1738, Pl. 31)

105

<!-- p. 107 -->

Chapitre 6. Typologie constructive des plates-bandes

— De La Hire, Desgodetz et Félibien (cit. 156), qui signent le compte-rendu de
l’Académie royale d’architecture du 20 Janvier 1698 ;
— Frézier (1738, p. 65-66, cit. 33), qui dessine la règle du « 1 pour 2 » pour les
plates-bandes ;
— Frézier (1738, p. 72, cit. 42), qui mentionne celle du « 1 pour 3 » pour les voûtes
plates d’Abeille ;
— Diderot et d’Alembert (1765a, cit. 46), qui utilisent la règle du triangle équila-
téral implicitement. Cependant ils indiquent explicitement qu’éloigner le centre
de convergence des joints de la plate-bande (E sur la ﬁgure) augmente sa pous-
sée, ce qui suggère qu’abaisser ce centre est envisageable (même s’il augmente
la poussée) ;
— Diderot et d’Alembert (1765b, cit. 50), qui utilisent sans la nommer une règle
intermédiaire, correspondant à une proportion de « 1 pour 2,5 » sur une ﬁgure
représentant la coupe des pierres pour une voûte plate (et non une plate-
bande). Voir ﬁg. 32 sur la planche reproduite sur la ﬁgure 10.7 ;
— Monduit (1889, p. 82, cit. 98).

Règle du « 1 pour 1 »

Mentionnons pour terminer la règle du « 1 pour 1 », plus rare, qui revient à dessiner les joints des sommiers à 45◦. Cette règle n’est pas mentionnée par écrit, mais
apparaît implicitement au moins à deux occasions dans des traités. Premièrement,
Simonin utilise sur la planche représentant une « arrière voussure en plate-bande,
ébrasée en quart de cercle », des joints rayonnants dont l’inclinaison au sommier
vaut 45◦(ﬁg. 6.24). Son texte, qui décrit le dessin des panneaux de joints E, F et G,
prend pour base l’élévation A, pour laquelle aucune indication écrite n’est donnée
pour l’inclinaison des joints (Simonin, 1792, p. 30). Deuxièmement, la voûte plate
d’Abeille telle que dessinée sur les planches publiées par Gallon présente des joints
à 45◦avec la verticale. Cependant la description du texte donne une autre inclinaison (Gallon, 1735). Ce point fera l’objet de remarques de la part de Frézier (1738),
comme nous le verrons dans la section consacrée aux voûtes d’Abeille (section 10.3.4).

La règle du « 1 pour 1 » a probablement été utilisée en pratique, mais les exemples
sont rares. Le portail du passage Menestrier à Lyon montre un cas où l’on s’approche
de cette règle (proportion de 1 pour 1,2 environ, voir ﬁg. 6.25).

Cohabitation des règles dans les traités

Les règles du triangle équilatéral, du « 1 pour 2 » et du « 1 pour 3 » cohabitent
dans les traités de coupe des pierres. La synthèse des mentions ou utilisations des
diﬀérentes règles dans les traités est exposée dans la table 6.1.

Deux phénomènes mécaniques opposés expliquent qu’aucune des règles ne se soit
complètement imposée dans les traités par rapport aux autres. En eﬀet, l’inclinaison
des joints joue à la fois sur le risque de rupture des angles aigus des claveaux, et sur
la poussée des plates-bandes (15). Le choix d’une inclinaison est donc nécessairement

(15). Lorsqu’ils abordent la question, les auteurs de l’Époque Moderne indiquent que moins les joints
d’une plate-bande (ou d’un claveau) sont inclinés, plus la poussée de la plate-bande sera importante

106

<!-- p. 108 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.24 – « Arrière voussure en plate-bande, ébrasée en quart de cercle »,
d’après Simonin (1792, Pl. XIII)

107

<!-- p. 109 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.25 – Passage Menestrier, Lyon

Triangle équilatéral « 1 pour 2 » « 1 pour 3 »

Jousse (1642), Acad. Roy. d’Archi. 1698, ≈Frézier (1738),
Blondel (1675), ≈Frézier (1738), ≈Rondelet (1804),
D’Aviler (1691), ≈Diderot et d’Alembert (1765b), Monduit (1889)
Acad. Roy. d’Archi. 1710, ≈Rondelet (1804)
De La Hire (1712),
Gautier (1717),
Bélidor (1729),
Frézier (1738),
Patte (1769),
Blondel et Patte (1777a),
Douliot (1825),
Adhémar (1845),
Monduit (1889),
Chaix (1890)

Table 6.1 – Mention ou utilisation dans les traités des diﬀérentes règles
géométriques pour le choix de l’inclinaison des joints des plates-bandes ; le
symbole ≈indique une utilisation implicite de la règle

108

<!-- p. 110 -->

Chapitre 6. Typologie constructive des plates-bandes

le choix d’un compromis entre ces deux eﬀets, et c’est en substance ce que soulignent
Frézier à propos des plates-bandes puis des voûtes plates d’Abeille (Frézier, 1738,
p. 65-66, 72, cit. 33 et 42), ainsi que l’Association ouvrière des Compagnons du devoir
(1996, p. 78, cit. 119).

Le ﬂou relatif et l’absence d’une solution unique et optimale pour le problème du
choix de l’inclinaison des joints explique que l’Académie royale d’architecture puisse
recommander en 1698 de placer le centre de convergence plus bas qu’un triangle
équilatéral (cit. 156), pour ensuite revenir au triangle équilatéral en 1710 (cit. 162),
mais en préconisant de plus l’utilisation des lits brisés pour éviter la rupture de la
pierre à cause des aiguïtés.

Une autre illustration de ce phénomène se trouve dans la présentation de l’inclinaison des joints par Rondelet (1804). Ce dernier critique d’une part la proportion
de 1 pour 1,5 environ de la ﬁgure 7 de la planche XXVII, soit des angles encore plus
aigus que ceux donnés par la règle du triangle équilatéral, et encourage la proportion
de 1 pour 2,5 des ﬁgures 8 et 9 de cette même planche. Il ne donne pas d’indication
dans son texte sur l’emplacement à donner au centre de convergence des joints. Par
ailleurs, la position de ce centre sera modiﬁée dans les éditions suivantes. Par exemple
sur les planches de Rondelet (1828), pour la ﬁgure 7 (dont la numérotation change)
une proportion de 1,73 est utilisée (soit le triangle équilatéral), et pour la ﬁgure 8
une proportion de 1 pour 2,9. Dans l’édition posthume de 1834, il est simplement indiqué que l’angle entre sommiers peut varier entre 40◦et 60◦(Rondelet, 1834, p. 118,
cit. 78).

Permanence de la règle du triangle équilatéral dans les traités

La synthèse donnée sur la table 6.1 montre la permanence de la règle du triangle
équilatéral dans les traités d’architecture jusqu’à la ﬁn du xixe siècle, alors qu’en
pratique il semble que les tailleurs de pierre utilisent plutôt la règle du « 1 pour 3 »
à partir du début du xviiie siècle. Nous avançons les hypothèses suivantes, qui pourraient expliquer la divergence qui se produit entre la règle prescrite majoritairement
dans les traités et la pratique des tailleurs de pierre :
— les auteurs peuvent, par tradition, reprendre la règle qui ﬁgurait dans les traités
déjà publiés – la règle la plus anciennement transmise par les traités est celle

(p. ex. Diderot et d’Alembert, 1765a, cit. 46, Diderot et d’Alembert, 1765b, cit. 49). Cette propriété
découle probablement (ce n’est pas indiqué dans les textes) de la théorie de La Hire avec voussoirs
à joints glissants, appliquée également par Bélidor (1729, Livre II p. 39-40).
Cette propriété est également transmise oralement par les tailleurs de pierre, présentée cette
fois-ci comme une observation pratique. Lors de la construction des plates-bandes, les tailleurs de
pierre observent que les plates-bandes à joints peu inclinés poussent plus que les autres (serrage des
joints, déformation des appuis, etc.) Cette observation nous a été rapportée par Luc Tamboréro.
Notons que dans le cadre du calcul à la rupture, lorsque la plate-bande présente un fort rapport
portée sur hauteur L/h (la plate-bande a une forme élancée), le critère de résistance en frottement n’intervient pas, comme nous le verrons dans le chapitre 15 consacré à l’étude mécanique des
plates-bandes. Le calcul à la rupture permet d’étudier les chargements extrêmes, et non la situation
d’équilibre réelle se produisant dans la plate-bande. Le calcul à la rupture ne permet donc pas de
donner une réponse à cette question. De plus, les plates-bandes à joints verticaux, qui ne sont pas
admises en pratique pour la construction, présentent des domaines des chargements supportables
similaires à ceux des plates-bandes à joints inclinés. Il y a donc ici une limite à n’étudier la stabilité
des plates-bandes que par le calcul à la rupture.

109

<!-- p. 111 -->

Chapitre 6. Typologie constructive des plates-bandes

du triangle équilatéral ;
— le triangle équilatéral présente un intérêt esthétique et symbolique que n’ont
pas les triangles selon les proportions du « 1 pour 2 » et du « 1 pour 3 » ;
— la règle du triangle équilatéral est plus rapide à dessiner à l’échelle réduite qui
est celle de l’architecte et des auteurs des traités (nous reviendrons dans la
section 6.3.6 sur les diﬀérences pratiques que présentent les trois règles pour
les architectes d’une part, et pour les appareilleurs d’autre part) ;
— les avantages des autres règles (moins de cubage de pierre ; moins de risque de
casse de la pierre lors de la taille, puis lors de la pose) ne sont pas considérés
par les auteurs qui s’adressent plus aux architectes qu’aux tailleurs de pierre.
Il est d’ailleurs surprenant que parmi ces auteurs, Douliot – un tailleur de pierre
de formation – présente la construction de la règle du triangle équilatéral et non celle
de la règle du « 1 pour 3 » dont il avait nécessairement connaissance.

Hypothèses sur l’évolution de l’emploi des règles

Les informations fournies par les traités ne sont pas nécessairement représentatives
des pratiques de chantier, ainsi que l’illustre la permanence de la règle du triangle
équilatéral dans les traités alors que cette dernière n’est plus employée en pratique
au xixe siècle. Nous formulons les hypothèses suivantes sur l’évolution de l’emploi
des règles géométriques sur chantier, basées sur le catalogue d’exemples construits
de plates-bandes réunis dans le cadre de cette thèse. Premièrement, la majorité des
exemples de plates-bandes de l’Antiquité et du Moyen Âge ne correspondent pas à
la règle du triangle équilatéral. La règle du triangle équilatéral semble s’être imposée
en France à partir du xvie ou xviie siècle à la fois sur chantier et dans les traités,
peut-être sous l’inﬂuence des traités italiens (par exemple Serlio). Deuxièmement, la
remise en question de la règle du triangle équilatéral intervient rapidement, dès la
ﬁn du xviie siècle, avec l’utilisation fréquente des lits brisés, puis par l’abaissement
du centre de convergence des joints, dont Frézier se fait l’écho en 1738. Une étude
d’archéologie du bâti, que nous n’avons pas menée, serait nécessaire pour conﬁrmer
et préciser ces hypothèses d’évolution. Il est certain cependant qu’il existe un vrai
décalage concernant les plates-bandes entre le tableau dressé par l’étude des traités
d’architecture et la pratique sur chantier au moins à partir du xviiie siècle.

6.3.5 Méthodes de tracés

Les règles que nous venons de voir permettent de déﬁnir le centre de convergence
des rayons par construction d’un triangle, pointe en bas. L’appareil de la plate-bande
peut être obtenu en divisant l’angle en autant de secteurs angulaires qu’il y a de claveaux. Il existe cependant plusieurs méthodes pour cette dernière étape, dont l’étude
permet de distinguer les avantages et les inconvénients dans la pratique respective
de l’architecte, qui dessine à échelle réduite, et de l’appareilleur, qui dessine en vraie
grandeur.
Nous présentons dans un premier temps les trois techniques décrites dans les
traités, que nous appellerons respectivement, à défaut de terminologie établie les
concernant :
— la méthode du centre de convergence ;

110

<!-- p. 112 -->

Chapitre 6. Typologie constructive des plates-bandes

— la méthode des divisions égales ;
— la méthode de proportion des saillies.

Étapes de la méthode du centre de convergence

Étapes de la méthode des divisions égales

Étapes de la méthode de la proportion des saillies (pour cinq claveaux)

Fig 6.26 – Méthodes de tracé de l’appareil d’une plate-bande à cinq claveaux

Méthode du centre de convergence

La méthode du centre de convergence nécessite, comme son nom l’indique, le centre
de convergence des rayons. Le secteur angulaire, déﬁni par le triangle dont la base
est l’intrados et le sommet le centre de convergence, est divisé en autant de triangles
qu’il y a de claveaux à dessiner (ﬁg. 6.26). Cette division peut être réalisée :
— en divisant l’angle au sommet du triangle en autant d’angles égaux qu’il y a
de claveaux ;
— en divisant l’intrados en autant de segments égaux qu’il y a de claveaux.
L’appareil de la plate-bande est obtenu en prolongeant les droites partant du centre
de convergence jusqu’à l’extrados.

Cette méthode, dans sa version avec division de l’intrados en parties égales, est
présentée par exemple par Douliot (1825, p. 77) et Adhémar (1845, p. 10). Frézier
(1738, p. 65) présente cette méthode dans sa version avec division de l’angle en parties
égales.

Il est à noter que la division égale de l’angle d’une part et la division égale de
l’intrados d’autre part ne donnent pas le même résultat. La division égale de l’intrados
permet d’obtenir des claveaux qui ont tous le même poids W0/k avec W0 le poids
total de la plate-bande et k le nombre des claveaux (car les panneaux de tête ont tous
la même aire). L’appareil parait très régulier à l’œil (ﬁg. 6.27 à droite). A contrario,

111

<!-- p. 113 -->

Chapitre 6. Typologie constructive des plates-bandes

la division égale de l’angle donne des panneaux de tête un peu plus importants à
proximité des sommiers ; la clé parait plus petite que les claveaux près des sommiers
(ﬁg. 6.27 à gauche). Cet eﬀet est discret, mais reste perceptible sans nécessiter de
mesure.

Fig 6.27 – Comparaison des coupes données par la division égales des angles du
triangle, et la division égale de l’intrados

Méthode des divisions égales

La méthode des divisions égales n’utilise pas le centre de convergence des rayons.
Le point de départ de la méthode est donné par les deux joints des sommiers de
la plate-bande (ﬁg. 6.26). Les segments qui relient ces deux joints sont l’intrados et
l’extrados. En divisant ces derniers chacun en autant de parties égales qu’il y a de
claveaux, puis en reliant les points obtenus par des segments, on obtient l’appareil de
la plate-bande.

Le résultat obtenu est le même que celui de la méthode du centre de convergence
dans sa version avec division de l’intrados en parties égales. Cependant, dans cette
seconde méthode à aucun moment le centre de convergence des joints n’est utilisé.

Cette méthode est présentée par Frézier (1738, p. 66, cit. 34) en plus de la méthode
du centre de convergence.

Méthode de proportion des saillies

La méthode de proportion des saillies n’utilise pas le centre de convergence des
rayons. Comme pour la méthode des divisions égales, le point de départ est donné par
les deux joints des sommiers de la plate-bande (ﬁg. 6.26). Les segments qui relient ces
deux joints sont l’intrados et l’extrados. L’intrados est divisé en autant de segments
égaux qu’il y a de claveaux. En revanche, la division de l’extrados suit un système de
proportion des saillies ; nous appelons ici saillie la distance horizontale qui sépare la
partie supérieure d’un joint incliné par rapport à la partie inférieure.

La saillie des joints des sommiers étant connue, elle est divisée en m modules, avec
m le nombre de joints se trouvant de part et d’autres de la clé. Pour une plate-bande
à cinq claveaux, il y a m = 3 joints de part et d’autre de la clé. En partant de la clé,
le premier joint a une saillie de un module, le deuxième de deux modules, et ainsi de
suite jusqu’au joint du sommier qui a une saillie de m modules.

112

<!-- p. 114 -->

Chapitre 6. Typologie constructive des plates-bandes

Comme dans le cas de la méthode des divisions égales, cette méthode ne nécessite
pas de connaître le centre de convergence des rayons correspondant aux joints des
sommiers. Cependant, cette méthode ne présente pas la propriété de donner des joints
convergents en un point unique, comme l’illustre la ﬁgure 6.28 sur deux exemples
(plates-bandes à cinq et sept claveaux).

Fig 6.28 – Non convergence des joints tirés de la méthode de proportion des saillies

Cette méthode est présentée succinctement par Simonin dans le cas particulier
d’une plate-bande en fausse-coupe à cinq claveaux (Simonin, 1792, p. 37, cit. 67 –
ﬁg. 8.3). Simonin utilise par ailleurs également la méthode des divisions égales ou du
centre de convergence dans le cas d’une « arrière voussure en plate-bande, ébrasée en
quart de cercle » (Simonin, 1792, p. 30 – ﬁg. 6.24).

6.3.6 Architectes et appareilleurs

Les méthodes de tracé présentées ci-dessus présentent des avantages et des inconvénients diﬀérents, selon le point de vue adopté : celui de l’architecte, dessinant à
l’échelle réduite, et celui de l’appareilleur, dessinant en vraie grandeur.

Notons pour commencer que les règles servant à déterminer l’inclinaison des joints
(règles du triangle équilatéral, du « 1 pour 2 » et du « 1 pour 3 ») peuvent être facilement adaptées pour obtenir l’inclinaison des joints des sommiers au lieu du centre
de convergence des joints. En traçant au point d’appui un segment avec une pente
de « 1 pour 3 », on obtient le même joint incliné que celui qu’on obtiendrait avec la
règle du « 1 pour 3 » appliquée à la portée de la plate-bande, puis en prolongeant
le trait jusqu’à l’extrados (ﬁg. 6.29). De même, en traçant un segment à 30◦avec la
verticale, on obtient le même joint incliné que celui qu’on obtiendrait avec la règle du
triangle équilatéral. Les règles des traités peuvent donc être appliquées avec les trois
méthodes de tracé présentées sans nécessairement dessiner la position du centre de
convergence des rayons.

Nous comparons ici la méthode des centres de convergence (avec division de l’intrados en parties égales) et la méthode des divisions égales (16). Notons que ces deux

(16). La méthode de proportion des saillies présente les mêmes avantages que celle des divisions
égales dans le cadre de cette comparaison.

113

<!-- p. 115 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.29 – Règle du « 1 pour 3 » dessinée sur la portée (à g.), et sur le joint du
sommier (à d.), donnant un appareil identique

méthodes donnent exactement le même appareil, si les joints des sommiers choisis pour
la méthode des divisions égales convergent au centre de convergence utilisé avec la
méthode des centres de convergence. Notre comparaison concerne donc les méthodes
elles-mêmes, et non les résultats produits par les méthodes (qui sont identiques).
La méthode des divisions égales nécessite une épure occupant un espace beaucoup
plus réduit que celui de la méthode du centre de convergence, surtout si on utilise
la règle du « 1 pour 3 » qui éloigne signiﬁcativement le centre de convergence de
l’intrados de la plate-bande. Elle est donc bien adaptée au chantier, car elle nécessite
peu d’espace au sol pour le tracé. Cette compacité a pour corollaire une plus grande
rapidité d’exécution, les déplacements de l’appareilleur (qui travaille en vraie grandeur
l’échelle du mètre) étant également plus réduits.
Inversement, il sera plus simple et plus rapide pour un dessinateur travaillant à
échelle réduite de travailler avec une règle et un compas en déterminant d’abord le
centre de convergence, puis en tirant des traits depuis ce dernier pour dessiner l’appareil. Le dessin sera généralement trop petit pour permettre de dessiner facilement
la règle du « 1 pour 3 » sur la hauteur du joint du sommier.
Il est possible que cette diﬀérence d’échelle des dessins et des épures sur chantier
soit un facteur explicatif que la règle du triangle équilatéral persiste dans les traités, alors que ces mêmes traités soulignent les problèmes d’aiguïté des joints qu’elle
provoque. En eﬀet, la méthode la plus rapide du point de vue du dessin est celle
du triangle équilatéral, qui ne nécessite que deux coups de compas pour déterminer
le centre de rayonnement des joints. La règle du « 1 pour 3 » nécessite quant à elle
de diviser en deux la portée, pour ensuite la reporter trois fois, ce qui est plus long
et moins commode, surtout lorsque les dessins sont répétitifs. De plus, les avantages
mécaniques de la règle du « 1 pour 3 » n’ont pas nécessairement le même intérêt
pour le dessinateur (qui travaille en atelier) que pour l’appareilleur (qui travaille sur
chantier).
Cette diﬀérence des pratiques ne concerne pas uniquement l’architecte et l’appareilleur. Monduit la souligne également entre l’élève et l’appareilleur (Monduit, 1889,
cit. 99).
Cette diﬀérence des intérêts et des méthodes de tracés respectives de l’architecte
et de l’appareilleur trouve son illustration la plus frappante dans les plates-bandes

114

<!-- p. 116 -->

Chapitre 6. Typologie constructive des plates-bandes

à refends, où l’appareil souligné par les refends ne correspond pas nécessairement à
l’appareil réel. Ainsi, les plates-bandes du 6 rue des Beaux-Arts à Paris (section 6.7.1)
présentent d’une part un faux-appareil à refends à trois claveaux et suivant la règle
du triangle équilatéral, et d’autre part un appareil réel à cinq claveaux et suivant
la règle du « 1 pour 3 ». Le faux-appareil correspond probablement au dessin de la
façade voulu par l’architecte, tandis que l’appareil réel, presque invisible, a probablement été tracé par l’appareilleur indépendamment (ou peut-être sous le contrôle) de
l’architecte.

6.3.7 Les « portes bombées » et les « croisées bombées »

Au xviiie siècle, les trois types de portes ou fenêtres admis dans l’architecture française selon J.-F. Blondel sont les croisées (17) en plein-cintre, les « croisées quarrées »
ou « croisées en plate-bande », et les « croisées bombées » (Blondel, 1752, p. 108, 113,
cit. 52 et 54). Blondel exclut les « croisées surbaissées » (arcs en anse-de-panier) et
les « croisées surmontées » (arcs brisés). D’Aviler (1691) utilise quant à lui le terme
de « plate-bandes bombées » (ﬁg. 6.1).

Fig 6.30 – « Portes quarrées » et « Portes bombées », d’après Blondel (1752, p. 111)

Les portes et croisées bombées correspondent aux portes et fenêtres couvertes d’un
arc segmentaire. La détermination du centre de l’arc, qui détermine sa forme, ou de
façon équivalente sa ﬂèche, répond essentiellement à des préoccupations esthétiques
pour Desgodets et Blondel. Il s’agit de trouver la forme la plus juste du point de vue
du décor architectural, dans un ensemble réglé par le jeu des proportions de la théorie
des ordres.

Bien qu’il n’y soit pas fait référence, nous supposons qu’une fois le centre de
l’arc déterminé pour l’épure de l’arc segmentaire, le même centre est utilisé, par
commodité, comme centre de convergence des joints. Cette solution, la plus simple

(17). Le terme croisée désigne aujourd’hui les fenêtres divisée en croix par un meneau et un croisillon.
Au xviiie siècle, le terme croisée est employé par J.-F. Blondel pour désigner une fenêtre, sans qu’il
soit question de meneau ou de croisillon.

115

<!-- p. 117 -->

Chapitre 6. Typologie constructive des plates-bandes

que l’on puisse imaginer dans cette situation puisqu’elle ne nécessite aucun tracé
complémentaire, donne des joints perpendiculaires à l’intrados, et suit donc le principe
de normalité déﬁni précédemment.
Les règles évoquées dans les traités pour déterminer le centre de l’arc segmentaire
des plates-bandes bombées sont les suivantes.
— D’Aviler (1691, p. 116) donne pour centre le sommet du triangle équilatéral
renversé, dont la base correspond à la largeur de la porte ou de la fenêtre,
alors qu’il ne mentionne pas de règle particulière concernant les plates-bandes
droites (cit. 16).
— Desgodets (1719, p. 98) donne la même règle que d’Aviler, avec le triangle
équilatéral.
— Tiercelet (1728, p. 61) mentionne également le triangle équilatéral (cit. 25).
— Blondel (1752, p. 114) donne deux limites à ne pas dépasser pour les
portes (ﬁg. 6.30). Le centre doit être situé entre le centre donné par la règle du
triangle équilatéral, et le centre qui serait donné par une règle du « 1 pour 4 ».
Ces limites sont données pour des raisons esthétiques et non mécaniques ou
liées à la coupe des pierres (Blondel, 1752, p. 110, cit. 53). La même règle
s’applique aux fenêtres (cit. 55).
Les essais de typologie du portail dans l’architecture privée parisienne, réalisés
par Kamovska-Monnereau concernant le xviie siècle, puis les années 1700-1750, permettent de quantiﬁer pour Paris la fréquence de l’utilisation de ces formes (sans distinguer ici le linteau de la plate-bande, ou l’architrave en pierre de celle en maçonnerie
ou en bois enduit). Ainsi, sur les 300 exemples de portails répertoriés au xviie siècle à
Paris, 89 correspondaient à des « portes à baie rectangulaire » (Kamovska-Monnereau,
2006, p. 42). Entre 1700 et 1750, par contre, les baies rectangulaires sont les moins
représentées du corpus (9 sur 240 – Kamovska-Monnereau, 2004). À cette époque,
les portes bombées (arcs segmentaires) sont beaucoup plus utilisées que les portes
droites.

6.4 Hauteur des claveaux

Les indications sur la hauteur à donner aux plates-bandes sont relativement rares
dans les traités d’architecture de l’Époque Moderne, et plus fréquentes après la Révolution. En eﬀet, à l’Époque Moderne, l’accent est porté par les auteurs des traités plus
sur l’inclinaison des joints, les crossettes, tenons, lits brisés etc., que sur la hauteur
des claveaux. La hauteur joue pourtant un rôle important vis-à-vis de la stabilité des
plates-bandes.
Les traités de la Renaissance se focalisent sur les systèmes de proportions à donner aux ordres, et ce également pour les ornements des fenêtres. À titre d’exemple,
Palladio préconise que l’architrave ait comme hauteur au moins la largeur des jambages de la baie, eux-mêmes devant être compris entre le sixième et le cinquième
de la portée (Palladio, 1570, p. 56). Les dimensions à donner aux frises et corniches
au-dessus de l’architrave sont basées sur le module donné par la division en quatre
de l’architrave.
Nous donnons dans la suite les diﬀérentes méthodes présentées dans des traités
pour trouver la hauteur des plates-bandes. La méthode la plus courante est de prendre

116

<!-- p. 118 -->

Chapitre 6. Typologie constructive des plates-bandes

comme hauteur une fraction de la portée libre de la plate-bande. Dans les autres cas,
nous donnerons également le rapport portée sur hauteur Li/h lorsque ce dernier peut
être déduit de la méthode, pour permettre la comparaison des méthodes entre elles.
La synthèse de ces règles est donnée sur la ﬁgure 6.31, où ont également été reportées
les positions de plates-bandes présentées dans le catalogue en annexe.

h en mètres
2,5 +Baalbek
Serlio 1537
La Hire (hyp. début xviiie s.)
Gautier 1717
Rondelet L/5 à L/4
2 Douliot 1825
Claudel et Laroque 1850

1,5

\+Tombeau Metella

1

Lac d’Albano + + +Split
Temple de Junon + Carceres
de Domitien
0,5

0 Li en mètres
0 0,5 1 1,5 2 2,5 3 3,5 4 4,5 5

Fig 6.31 – Hauteur de la plate-bande suivant diﬀérents auteurs (18)

Serlio (1537)

Serlio (1537, 10v, cit. 2) indique sur l’exemple d’une porte de l’ordre Toscan que la
hauteur à donner à la plate-bande est le quart de la portée. Cette règle, donnée pour
un exemple particulier, s’applique assez bien aux autres exemples de plates-bandes
de l’ordre Toscan de son traité (p. ex. 9v, 10v, 17v – ﬁg. 6.18), à l’exception du dessin
de la page 16v où la plate-bande présente une hauteur supérieure à la moitié de la
portée.

Jousse (1642)

Jousse (1642) donne les méthodes de tracé de l’appareil de trois types de plates-

(18). Les dimensions des exemples de plates-bandes de l’Antiquité représentés par Rondelet sont
indiquées sur cette ﬁgure (Rondelet, 1828, Pl. XXX). Par ailleurs, les droites correspondant aux
règles de Serlio et de Douliot sont légèrement décalées verticalement pour éviter leur superposition
sur le domaine donné par Rondelet, et faciliter la visibilité du graphique.

117

<!-- p. 119 -->

Chapitre 6. Typologie constructive des plates-bandes

bandes : « plate-bande droite », « plate-bande biaise » et « plate-bande sous la tour
ronde ». Il n’indique pas la hauteur à donner aux plates-bandes, et les ratios de
la portée sur la hauteur des plates-bandes dessinées sont variables. Pour le tracé
le plus simple d’une plate-bande droite (ﬁg. 6.22), le rapport portée sur hauteur
vaut Li/h = 2,15.

De La Hire (1712)

Le fascicule de l’encyclopédie des compagnons du devoir concernant les platesbandes a été rédigé par Jérémie Fierens dans le dernier quart du xxe siècle. Il donne
une méthode graphique pour déterminer la hauteur à donner à une plate-bande (Association ouvrière des Compagnons du devoir, 1996, p. 78-79, voir ﬁg. 6.33 à d.). Cette
méthode utilise le triangle équilatéral de sommet F et dont la base correspond à la
portée AB de la plate-bande à l’intrados. Il s’agit du même triangle équilatéral que
celui de la règle géométrique permettant d’obtenir l’inclinaison des joints que nous
avons vu précédemment. Le point E donnant la hauteur de la plate-bande est obtenu
par l’intersection entre la perpendiculaire à AF passant par A et l’axe vertical FD de
la plate-bande. Cette méthode donne un ratio hauteur de plate-bande sur portée de
h/Li = tan(π/6)/2 = 0,289 ou Li/h = 3,46, soit une hauteur comprise entre le tiers
et le quart de la portée.

Cette méthode est équivalente à dessiner l’équilibre limite d’une plate-bande en
utilisant la théorie des claveaux sans frottement de De La Hire (1712), sous réserve
que l’inclinaison des joints de la plate-bande respecte la règle du triangle équilatéral.
Nous n’avons pas trouvé d’indices dans les traités qui permettent de démontrer que
cette méthode pour trouver la hauteur des plates-bandes a bien été proposée par De
La Hire, cependant le lien conceptuel entre cette méthode graphique et la théorie de
De La Hire est évident (19). Nous ferons référence à cette méthode dans la suite en la
qualiﬁant de méthode de De La Hire.

Fig 6.32 – Épaisseur à donner aux piédroits qui soutiennent une plate-bande,
d’après d’après Bélidor (1729, Pl. 6)

(19). La théorie de De La Hire (1712) concernant la stabilité des plates-bandes, ou plus précisément
des piédroits supportant les plates-bandes, est analysée par Becchi (2012).

118

<!-- p. 120 -->

Chapitre 6. Typologie constructive des plates-bandes

Cependant l’appareil pris pour l’exemple de l’encyclopédie est celui donné par
la règle du « 1 pour 3 ». L’exemple de l’encyclopédie des compagnons combine donc
deux règles concernant l’inclinaison des claveaux. La première, celle du « 1 pour 3 »,
est explicite et donne l’inclinaison réelle à donner aux joints des claveaux. La seconde,
celle du triangle équilatéral, est implicite et peut être reliée via la théorie de De La
Hire à l’équilibre de la plate-bande.

Nous faisons l’hypothèse que la règle a initialement été formulée par De La Hire ou
un de ses élèves telle que dessinée sur la ﬁgure 6.33 à gauche, c’est-à-dire en ne faisant
usage que du triangle équilatéral à la fois pour obtenir la hauteur de la plate-bande et
l’inclinaison des joints. La règle donne une hauteur comprise entre le tiers et le quart
de la portée, donc semblable aux exemples construits sans cette règle au xviie siècle.
Lors de l’apparition de la règle du « 1 pour 3 » probablement ﬁn xviie siècle ou
début xviiie siècle, la nouvelle règle appliquée pour l’inclinaison des joints ne pouvait
être appliquée pour la hauteur des plates-bandes, car le ratio qui aurait été obtenu
Li/h = 6 était trop important (la plate-bande trop ﬁne – ﬁg. 6.33 au centre).
Frézier fait explicitement le lien entre le triangle équilatéral et la théorie de De
La Hire, et souligne qu’il faut prendre en considération la modiﬁcation de la position
du centre de convergence dans les calculs et modiﬁer en conséquence le calcul de
l’épaisseur à donner aux piédroits (Frézier, 1738, p. 65-66, cit. 33).

Fig 6.33 – Règle géométrique pour la détermination de la hauteur de la plate-bande ;
ﬁgure de droite d’après Association ouvrière des Compagnons du devoir (1996, p. 78)

Gautier (1717)

Gautier (1717, p. 14) donne une méthode liée à la règle géométrique du triangle
équilatéral, dans laquelle la hauteur des claveaux est donnée par la distance entre un
arc dont le centre est le sommet du triangle équilatéral, et l’intrados (ﬁg. 6.34). Cette
méthode donne un ratio hauteur de plate-bande sur portée de 1 −cos(π/6) = 0,134
que Gautier arrondit comme étant le huitième de la portée h/Li = 0,125.
Cette méthode est en rupture avec les autres méthodes listées ici, car elle produit
des plates-bandes beaucoup plus ﬁnes. L’origine de cette diﬀérence pourrait être liée
au type de constructions considérées, Gautier traitant des ponts, alors que les autres
règles relevées ici sont présentées pour les bâtiments.

119

<!-- p. 121 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.34 – Hauteur et inclinaison des joints à donner à une plate-bande,
d’après Gautier (1717, Pl. II Fig. 4)

Après la Révolution

Rondelet (1804, p. 95, cit. 75) indique que l’épaisseur d’une voûte plate ou d’une
plate-bande devrait être de l’ordre du quart de la portée, et au minimum du cinquième de la portée pour que les systèmes d’armatures en fer puissent en assurer la
stabilité. Nous en déduisons que selon Rondelet pour les plates-bandes sans armatures
métalliques, la hauteur doit également être à minima supérieure à ces proportions.
Douliot (1825, p. 79) indique que pour les petites portées inférieures à 1 m, il faut
donner à la plate-bande au moins le quart de sa largeur. Claudel et Laroque (1850,
p. 242) donnent une expression analytique plus complexe qui se distingue des règles
vues jusqu’à présent car la hauteur n’est plus simplement proportionnelle à la portée.

Dans une voûte appareillée en plate-bande, on a, toutes les dimensions
étant exprimées en mètres,

Li + 5 L2i −h2 ! h = et x = 3 (6.1)
14 2h

Li, moitié de la largeur à recouvrir.
h, hauteur de la plate-bande.
x, distance du point de concours de tous les plans de joints à l’intrados
de la plate-bande
Claudel et Laroque (1850, p. 242)

Ces formules sont reprises par Barré et Barré (1896, p. 652).
Lorsqu’il n’est pas possible de donner à la plate-bande une hauteur suﬃsante,
Douliot (1825, p. 81, cit. 79) présente les crossettes et les tenons intérieurs comme des
solutions « plus ou moins eﬃcaces » pour compenser le manque de hauteur. Chaix
(1890, p. 175, cit. 110) reprend les exemples de Douliot, mais en se montrant nettement
plus réservé quant à leur eﬃcacité.

Exemples construits à faible hauteur

Gautier (1717, p. 15) donne l’exemple d’une plate-bande construite « dans l’Eglise

120

<!-- p. 122 -->

Chapitre 6. Typologie constructive des plates-bandes

des Reverends Peres Jesuites à Nismes, faite sous la conduite de feu le Reverend Pere
Mourgues, & du Dessein de feu Sieur Cubisol, habile architecte ». Cette plate-bande
a quatre toises, deux pieds, six pouces de longueur et un pied d’épaisseur, soit un
rapport portée sur hauteur de Li/h = 26,5/1 = 26,5. Cet exemple est ensuite repris
par d’autres auteurs (Frézier, 1738, p. 67 ; Gauthey, 1843).

Huerta Fernández (2012) cite l’exemple d’une « plate-bande tridimensionnelle »
dans le chœur du monastère El Escorial, présentant un rapport portée sur hauteur
de Li/h = 28.
Ces deux exemples exceptionnels par leur faible hauteur par rapport à leur portée,
bien que mentionnés dans des chapitres traitant des plates-bandes, appartiennent
vraisemblablement plutôt à la catégorie des voûtes plates, soumises aux charges de
circulation de personnes (surcharges d’exploitation) et non au poids de maçonneries,
ce qui rend délicat toute comparaison avec les règles précédemment mentionnées pour
les plates-bandes des bâtiments.

6.5 Détails constructifs

6.5.1 Crossettes

Dimensions et matériau

Les traités apportent les informations suivantes sur la dimension de la saillie des
crossettes, également appelées « repos horizontal » ou « ressaut » :
— ne doit pas être supérieure à 2 ou 3 pouces selon Rondelet (1804, p. 101,
cit. 76) ;
— doit être égale pour toutes les crossettes, et ne doit pas être supérieure au
quart de la demi épaisseur de la plate-bande, soit le huitième de l’épaisseur de
la plate-bande selon Douliot (1825, p. 82) ;
— ne doit pas être supérieure au quart de l’épaisseur du claveau selon Chaix
(1890, p. 174), et selon l’Association ouvrière des Compagnons du devoir (1996,
p. 129).
Rondelet précise par ailleurs que la partie au dessus de la saillie doit être supérieure
à deux fois la saillie (Rondelet, 1804, p. 101, cit. 76).

Douliot (1825), puis Chaix (1890), donnent le moyen de tracer ces crossettes, et
ces deux auteurs les placent alignées sur une droite à mi-hauteur de la plate-bande,
comme le fera plus tard l’Association ouvrière des Compagnons du devoir (1996,
p. 128). D’autres dispositions sont envisageables. Une plate-bande romaine du palais de Dioclétien à Split (Croatie) présente des crossettes alignées sur deux droites
inclinées de part et d’autre de la clé (ﬁg. 6.37). De Vinci a également dessiné des crossettes disposées alternativement sur deux droites horizontales (voir section 9.4.4). Les
joints peuvent également présenter deux crossettes au lieu d’une seule, bien que ces
cas soient beaucoup plus rares. La plate-bande déchargeant le linteau de la porte du
premier étage du mausolée de Théodoric à Ravenne (Italie), construit en 519 (Cejka,
1978, 5-Taf1), présente des doubles crossettes visibles de l’intérieur du bâtiment. Au
Moyen Âge, le chauﬀoir de l’abbaye de Longpont présente une plate-bande à double

121

<!-- p. 123 -->

Chapitre 6. Typologie constructive des plates-bandes

crossettes (ﬁg. B.51). Il existe enﬁn des plates-bandes à double crossettes en Égypte
(ﬁg. 6.35 et 6.36).

Fig 6.35 – Plate-bande à double Fig 6.36 – Plate-bande à double
crossettes, Le Caire (Égypte) – crossettes, Le Caire (Égypte) –
photo : Louis Jacquart, 2016 photo : Louis Jacquart, 2016

Rondelet et Chaix indiquent que les plates-bandes à crossettes peuvent, ou
doivent, être réalisées avec une pierre dure (Rondelet, 1804, p. 101, cit. 76 ; Chaix,
1890, p. 175, cit. 111).

Discussion des crossettes dans les traités

Les crossettes sont employées pour les plates-bandes dès l’Antiquité. Elles ont été
utilisées de façon fréquente au Moyen Âge pour la construction des manteaux des
cheminées.

L’emploi des crossettes ne fait pas l’objet d’un consensus. Certains auteurs
conseillent leur utilisation (Monduit, 1889), ou y voient un moyen de pallier une
hauteur disponible réduite (Douliot, 1825). D’autres auteurs les critiquent (Frézier,
1738 ; Adhémar, 1845). D’autres encore mentionnent avantages et inconvénients supposés sans toutefois apporter d’avis tranché sur la question (Gautier, 1717, cit. 23).

Les traités qui proposent d’employer des crossettes font généralement appel à la
stabilité de la plate-bande pour expliciter leur utilité, mais les arguments sont divers.
Selon Diderot et d’Alembert (1765a), les crossettes permettent de diminuer la poussée de la plate-bande sans devoir recourir à des angles de joints trop importants qui
risqueraient d’entraîner la rupture des arêtes (cit. 47). Tiercelet les conseille, sous le
vocable de « voussoir à crochet », dans le cas où l’on ne dispose pas d’« une bonne
butée » (Tiercelet, 1728, p. 53, cit. 24). Adhémar propose le même argument concernant les voûtes plates, mais son raisonnement s’applique également aux plates-bandes
(Adhémar, 1845, p. 15, cit. 82). Pour ce dernier, il n’y a pour les voûtes plates tout
simplement « pas de poussée » grâce aux crossettes. Monduit indique quant à lui
qu’elles permettent d’éviter l’usage d’« horribles linteaux en fer », et sous-entend que
leur absence ne s’expliquerait que pour des raisons d’économie de taille de pierre et
de temps de pose (Monduit, 1889, p. 72, cit. 96). Enﬁn, Chaix présente les crossettes

122

<!-- p. 124 -->

Chapitre 6. Typologie constructive des plates-bandes

comme une solution lorsque la hauteur disponible pour la plate-bande est insuﬃsante, tout en se montrant réservé sur l’eﬃcacité des diﬀérents systèmes à crossettes,
y compris les plates-bandes à tenons intérieurs qu’il inclut sous cette dénomination
(Chaix, 1890, p. 175, cit. 110).

La critique des crossettes peut être basée sur des arguments esthétiques. Frézier
critique l’utilisation des crossettes (Frézier, 1738, p. 66, cit. 35), et propose de leur substituer un autre système avec des balles de plomb de son invention, que nous verrons
dans la prochaine sous-section. Bien qu’il classe les crossettes parmi les « moyens de
donner de la solidité à ce genre de voûte (20) », son objection est basée sur une appréciation esthétique. Il indique que la « déformité » que représente les crossettes n’est
acceptable que lorsqu’elle peut être cachée par une moulure. Un exemple de platebande de ce type se trouve à la chapelle Saint-Louis de l’hôpital de la Salpêtrière
(ﬁg. 8.7). Couvrant des portes latérales de la chapelle, ces plates-bandes présentent
des joints verticaux, avec une crossette masquée par le sommet du chambranle de
la porte. Tiercelet indique également que les « crochets » des voussoirs pourraient
être masqués comme le sont les joints inclinés par les joints verticaux dans les platesbandes en fausse-coupe (Tiercelet, 1728, p. 53, cit. 24).

Adhémar juge également défavorablement l’aspect des crossettes dans le cas des
plates-bandes (tout en soulignant leur avantage pour les voûtes plates, comme nous
l’avons vu ci-dessus). Il donne le système des tenons intérieurs comme un moyen
d’« éviter l’aspect désagréable produit dans la face apparente du mur par la coupe
brisée [crossette] » (Adhémar, 1845, p. 13).

Douliot indique que même dans le cas des plates-bandes à crossettes, les joints de la
clé doivent être plans et donc dépourvus de crossettes (Douliot, 1825, p. 81, cit. 81). La
justiﬁcation de sa préconisation est liée au processus constructif : la clé étant le dernier
claveau mis en place lors du montage d’une plate-bande, et cette dernière devant servir
à mettre en compression la plate-bande, l’opération serait trop diﬃcile si les joints
en coupe n’étaient pas plans. Chaix, qui s’inspire largement des textes de Douliot
dans son chapitre consacré aux plates-bandes, fait les mêmes remarques à propos
des clés des plates-bandes (Chaix, 1890, p. 175). Cette préconisation est également
reprise par Adhémar (1845, p. 13) et l’Association ouvrière des Compagnons du devoir
(1996, p. 128-129, cit. 121)). Cependant, tous les exemples construits de plates-bandes
à crossettes que nous reproduisons dans ce document présentent des crossettes sur la
clé.

Planat analyse les crossettes à la clé existant sur diverses plates-bandes antiques et
juge ces dernières ineﬃcaces pour des raisons similaires à celles de Douliot, mais cette
fois-ci en cas de mouvements des appuis de la plate-bande (Planat, 1888b, p. 486-487,
cit. 103 – ﬁg. 6.37).

6.5.2 Balles de plomb, cailloux, goujons et os de bœufs

Outre les plates-bandes à tenons et les plates-bandes à clavettes décrites lors de
la déﬁnition des diﬀérents type de plates-bandes, il existe également d’autres artiﬁces
mentionnés dans les traités jouant un rôle similaire aux tenons et clavettes : les « Z »

(20). Les voûtes en question sont les voûtes plates et les plates-bandes.

123

<!-- p. 125 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.37 – Plates-bandes romaines, d’après Planat (1888d, p. 486-487)

124

<!-- p. 126 -->

Chapitre 6. Typologie constructive des plates-bandes

métalliques, les balles de plomb, les cailloux, les goujons en bois ou en métal, et les
os de bœufs.

Balles de plomb et cailloux

Frézier propose un système de son invention pour se substituer au système des
plates-bandes à crossettes dont il critique l’eﬃcacité (Frézier, 1738, p. 66, cit. 35).
Ce système consiste à placer deux balles de plomb de 1 pouce de diamètre (environ
2,7 cm) à chaque joint. Il n’indique pas si les balles de plomb sont coulées en place
dans les « cavités hémisphériques » pratiquées dans le joint, ou si elles sont placées
lors de la pose des claveaux. L’Association ouvrière des Compagnons du devoir (1996,
p. 129) indique que ce procédé constructif n’a cependant pas été observé en pratique.

Rondelet mentionne les balles de plomb, dont il estime la taille à environ « deux
pouces de gros », soit environ 5,4 cm. Il ajoute que des cailloux sont également utilisés,
et que ces derniers sont préférables (Rondelet, 1804, p. 101, cit. 77). L’utilisation des
cailloux nécessite leur scellement, soit au plomb, soit en coulant les joints de la platebande au plâtre (et peut-être avec un coulis de chaux), mais ce détail n’est pas
abordé par Rondelet. L’Association ouvrière des Compagnons du devoir (2001, p. 145)
indique à propos des voussoirs de voûtes (et non spéciﬁquement des plates-bandes),
que l’usage de cailloux n’a été employé que très ponctuellement.

Goujons en bois, pierre, fer ou bronze

Douliot évoque l’utilisation de goujons « de bois durci au feu ou en pierre très
dure », et les crampons en forme de « z », « en fer ou en bronze », scellés au mortier
ou ciment gras. Douliot exclut l’utilisation du plâtre dans le cas des crampons en fer
(Douliot, 1825, p. 83). Il juge « plus simple et plus solide » l’emploi de ces goujons et
crampons, par rapport à l’utilisation des crossettes (Douliot, 1825, p. 82).

Clavettes

Nollet (2012) donne plusieurs exemples de plates-bandes à clavettes à Lyon,
Bourges, et Loches, mais également des précédents italiens entre le xve et xvie siècle.

Os de bœufs

Les suspentes métalliques des plates-bandes armées auraient été remplacées par
des os de bœufs dans l’Ouest de la France. Bienvenu (2013, p. 212-213, cit. 141, 142)
évoque cette pratique de chantier, qui n’apparaît pas dans les traités de construction,
mais qui est présentée au cours d’une expertise sur la construction de la plate-bande
du palier de l’escalier monumental du palais de la Chambre des Comptes à Nantes
au xviiie siècle.

Les autres sources évoquant l’utilisation des os, mais pas spéciﬁquement dans le
cas des plates-bandes, sont les suivantes.

125

<!-- p. 127 -->

Chapitre 6. Typologie constructive des plates-bandes

— L’association ouvrière des Compagnons du devoir évoque au moins une fois
l’utilisation d’os dans la construction en pierre de taille : « À la pose, on y
emboîte une cheville en pierre dure ou en os. Mais aujourd’hui, l’utilisation de
ce procédé ancien est exceptionnelle » (Association ouvrière des Compagnons
du devoir, 1996, p. 129).
— Viollet-le-Duc évoque également l’utilisation des os dans son article concer-
nant les meneaux des remplages de baies : « La barre G traverse la tête de
ces meneaux et maintient les sommiers de la claire-voie au moyen de gou-
jons en os ». Il ajoute en note de bas de page : « À dater du xve siècle, les
constructeurs qui avaient eu l’occasion de constater combien les goujons en
fer, en gonﬂant par suite de l’oxydation, étaient préjudiciables aux travaux
de pierre et les faisaient éclater, remplacèrent ces goujons de métal par des
goujons en os de mouton ou en corne de cerf. Ces derniers ont conservé toute
leur dureté » (Viollet-Le-Duc, 1863).

6.5.3 La contre-ﬂèche

La contre-ﬂèche est nommée au xviiie siècle « bombement » (Bullet, Gautier,
Frézier, Patte), « exhaussement » (Frézier) ou « élévation sous clef » (Simonin).

La contre-ﬂèche est utilisée pour les plates-bandes pour deux raisons, mises en
avant par Bullet dans un mémoire présenté à l’Académie royale d’architecture le
30 juin 1710 (ﬁg. A.6). La première raison est que la plate-bande prend une certaine
ﬂèche après son décintrement, et n’est donc plus parfaitement de niveau. La seconde
raison est due à un eﬀet optique où une droite parait courbe. La seconde raison est
contestée par Frézier qui indique que cet eﬀet d’optique n’est pas sensible sur des
longueurs aussi faibles que celles des plates-bandes (Frézier, 1738, p. 67-68, cit. 38).

Dans le cas spéciﬁque des plates-bandes armées, Patte donne une troisième raison pour donner un léger bombement aux claveaux au centre de la plate-bande. Le
bombement est donné à l’aide de cales de bois lors de la pose des claveaux. Lors du
décintrage, les cales situés sous les trois claveaux centraux sont enlevées en premier,
ce qui induit parfois un léger glissement vers le bas de ces claveaux. Selon Patte
(1769, p. 282, 288), le retrait des cales restantes ne produit plus généralement (« à
l’ordinaire ») de mouvement.

Bullet donne une contre-ﬂèche de 1,5 pouces pour une largeur de 12 pieds (soit
une contre-ﬂèche de 1 pour 100 environ), à adapter suivant la largeur de la porte
couverte par la plate-bande. Patte indique que dans le cas des plates-bandes de la
place Louis XV (actuelle place de la Concorde à Paris), la contre-ﬂèche utilisée était
de 6 lignes, pour une portée de 9 pieds environ (soit une contre-ﬂèche de 1 pour 216
environ) (Patte, 1769, p. 280, 288). Frézier indique qu’on ne peut pas connaître exactement la contre-ﬂèche (« l’exhaussement ») à donner à la plate-bande pour obtenir
après apparition de la ﬂèche une plate-bande parfaitement de niveau, car cette contreﬂèche dépend à la fois de la longueur de la plate-bande, du nombre de claveaux, de la
qualité de la pierre, et de l’adresse des ouvriers lors de la taille puis lors de la pose (Frézier, 1738, p. 67-68, cit. 38). Il reprend l’exemple mentionné par Gautier sur l’église
des Jésuites à Nîmes (voir section 6.4), où une plate-bande de 26 pieds et 6 pouces de
portée a été construite avec une contre-ﬂèche de 6 à 7 pouces (soit une contre-ﬂèche

126

<!-- p. 128 -->

Chapitre 6. Typologie constructive des plates-bandes

de 1 pour 50 environ), et est descendue lors du décintrement de 3 pouces, laissant
ainsi la plate-bande bombée. Patte donne une contre-ﬂèche de 5 ou 6 lignes (environ
un demi pouce) pour les plates-bandes armées de la place Louis XV. L’association
ouvrière des Compagnons du devoir propose une contre-ﬂèche de 3 à 5 pour 1000
dans le cas des voûtes plates de petites dimensions, et de 1 pour 100 pour les voûtes
de grandes dimensions. Pour cela un couchis bombé en plâtre ordinaire est mis en
place sur le platelage du cintre (Association ouvrière des Compagnons du devoir,
2001, p. 147).

Il n’existe donc pas de règle universelle concernant la valeur à donner à la contreﬂèche. Les rapports hauteur sur portée reportés par la littérature sont compris
entre 3 pour 1000 et 1 pour 50. Dans le cas où plusieurs plates-bandes devaient être
construites (cas courant des baies de bâtiment), l’expérience sur la première platebande construite donnait la contre-ﬂèche à utiliser pour les suivantes, la première
pouvant par ailleurs être ravalée si la ﬂèche apparue était trop importante (21).

Bullet propose de tailler les claveaux avec la contre-ﬂèche, qui fait partie de
l’épure. Il est également possible de tailler les claveaux sans contre-ﬂèche, et de les
mettre en place avec contre-ﬂèche sur leur étaiement, ce que semble proposer Frézier sans que cela soit précisé explicitement dans son texte (Frézier, 1738, p. 67-68,
cit. 38). La méthode de l’épure sans contre-ﬂèche, avec contre-ﬂèche intégrée uniquement lors de la mise en œuvre, est celle qui est pratiquée aujourd’hui par les tailleurs
de pierre (22).

Les auteurs qui mentionnent la technique de la contre-ﬂèche sont les suivants :
— Bullet dans son mémoire de 1710, et ﬁgure également sur le dessin de son
mémoire de 1704 (23) ;
— Frézier (1738, p. 67-68) ;
— Patte (1769, p. 282, 288) ;
— Simonin (1792, p. 4, cit. 66) (24) ;
— Association ouvrière des Compagnons du devoir (1996, p. 140, cit. 122 ; 2001,
p. 147) mentionne la contre-ﬂèche, mais uniquement concernant les voûtes
plates.
A contrario, Douliot (1825), qui consacre deux pages à la description de la pose
des plates-bandes, sujet peu abordé par les autres auteurs, n’indique pas l’utilisation
d’une contre-ﬂèche. Il indique simplement que « En posant ces claveaux, on aura
soin de tenir la douëlle bien de niveau, dans le sens de l’épaisseur du mur, et à la
règle, dans celui de la largeur de la porte [...] » (Douliot, 1825, p. 424-425). De même
Monduit (1889) qui consacre six planches à des plates-bandes, et trois planches à des
voûtes plates, et les neuf textes associés à la description des épures, ne mentionne à
aucun moment l’utilisation d’une contre-ﬂèche.

(21). Information transmise oralement par Luc Tamboréro, Ateliers Romeo, Trani (Italie).
(22). Information transmise oralement par Luc Tamboréro, Ateliers Romeo, Trani (Italie).
(23). Nous n’avons pas eu accès au texte complet du mémoire de 1704 de Bullet, et nous n’avons
donc pas d’indications sur d’éventuelles préconisations à ce sujet en 1704.
(24). Simonin après avoir évoqué les ponts fortement surbaissés construit à la ﬁn du xviiie siècle,
comme le pont de Neuilly à Paris, conjecture qu’il sera possible de construire dans le futur des
« arches plates » de très grandes portées (96 pieds de portée, soit environ 30 mètres), en utilisant
une contre-ﬂèche (« une certaine élévation ») comme on le fait déjà pour les plates-bandes (Simonin,
1792, p. 4, cit. 66).

127

<!-- p. 129 -->

Chapitre 6. Typologie constructive des plates-bandes

6.5.4 Lit de carrière

Adhémar précise que les pierres doivent être disposées selon l’orientation de leur
lit de carrière, pour « que les couches dont se compose la pierre soient pressées les
unes contre les autres » (Adhémar, 1845, p. 11).

6.6 Utilisation du métal dans les plates-bandes

Nous décrivons ici l’emploi du métal dans les plates-bandes, en focalisant notre
attention sur la typologie des pièces métalliques, plutôt que sur leur fonction, qui fait
l’objet d’interprétations divergentes. Nous utiliserons dans la suite pour cette raison
le terme d’armature plutôt que ceux de tirant et linteaux, qui font référence à une
fonction structurelle qui oriente la perception des objets.

6.6.1 Exemples de plates-bandes avec armatures métalliques

Choisy mentionne l’utilisation d’« armatures de fer » au temple des Géants d’Agrigente en Sicile (Temple de Zeus Olympien), construit au ve siècle avant J.-C (25).
Choisy reprend l’interprétation de Quatremère de Quincy qui indique que la pierre
tendre de la région ne permettait ni d’obtenir des pierres de dimensions suﬃsante pour
créer les linteaux monolithes de ce temple « dans une dimension double des autres
monumens de cette ville », ni de résistance adaptée pour la même raison, et avait
donc contraint les constructeurs à appuyer l’architrave sur un mur et à créer ainsi
une architrave clavée (Quatremère de Quincy, 1825 ; Choisy, 1899a). Cette architrave
repose en eﬀet partiellement sur le mur entre colonnes du temple (pseudo-périptère –
ﬁg. 6.38). Nous n’avons pas trouvé de détails sur la typologie des armatures.

Fig 6.38 – Plate-bande du temple des Fig 6.39 – Plate-bande armée à Tivoli,
Géants d’Agrigente, d’après Choisy d’après Olivier (1983) reproduisant un
(1899a, p. 302) dessin de Hoﬀmann (1978)

À la villa d’Hadrien à Tivoli, construite au iie siècle ap. J.-C., des sommiers
en pierre de taille particuliers ont été retrouvés en plusieurs endroits (Olivier, 1983 ;

(25). Choisy mentionne le cas particulier de l’entablement du temple de Zeus Olympien à Agrigente
en Sicile à deux reprises (Choisy, 1899a, p. 278-279, 303, cit. 113, 114, voir ﬁg. 6.38).

128

<!-- p. 130 -->

Chapitre 6. Typologie constructive des plates-bandes

Adam, 2012, p. 71). Ces sommiers présentent des entailles qui devaient correspondre à
l’appui d’armatures métalliques. Le reste de la plate-bande était construit en briques,
et une dalle en marbre de forte épaisseur masquait l’ensemble (ﬁg. 6.39). Des traces
de plomb ont été retrouvées dans les rainures. Les cinq travées du portique de la
salle aux piliers doriques et les neuf travées du théâtre maritime ont été remontées en
utilisant ce système, et sont donc des reconstitutions. Olivier suggère que ce système
ait également pu être utilisé à Conimbriga au Portugal.
Tibières (2012) mentionne plusieurs exemples italiens de plates-bandes construites
avec des barres métalliques pour servir à la fois d’« armatures de plates-bandes, en
pierre ou en briques, et comme structures de renfort des architraves en pierre contre
la poussée des voûtes » :
— portique des Conservateurs de Michel-Ange à Rome vers 1537-1558 (Tibières,
2012, cit. 138) ;
— portique des Oﬃces de Giorgio Vasari à Florence, vers 1560-1570 ;
— débat entre 1567 et 1574 sur l’utilisation du fer pour la plate-bande du bap-
tistère de la cathédrale de Milan construit par Pellegrini ;
— description donnée par Scamozzi (1615) des plates-bandes armées, avec ti-
rants inférieurs et supérieurs, ancrés au niveau des colonnes dans des barres
verticales scellées au plomb.
Tibières indique ensuite que cet artiﬁce n’est pas utilisé dans l’architecture française
de la première moitié du xviie siècle.
En France, des barres en fer sont logées dans une réservation taillée dans l’intrados
des plates-bandes. Claudel et Laroque préconisent au xixe siècle que la réservation
soit remplie de « plâtre coloré de la même couleur que la pierre » (Claudel et Laroque,
1850, p. 241-242, cit. 83). Ce remplissage visible sous l’intrados peut trahir la présence
de barres en fer de ce type. Nous avons observé les exemples suivants, sans pouvoir
néanmoins réunir d’informations sur la présence eﬀective de la barre en fer, ni si
cette dernière correspond bien à la construction d’origine et non à une intervention
de restauration :
— fronton de l’église Saint-Gervais-Saint-Protais, construite par Salomon de
Brosse 1616-1621 (ﬁg. B.62) ;
— fronton de l’église du Val-de-Grâce, construite par François Mansart puis Le
Muet 1644-1669 (ﬁg. B.63) ;
— fronton de la chapelle du collège des Quatre-Nations, construite par
Louis Le Vau 1662-1688 (ﬁg. B.64) ;
— porte au rez-de-chaussée de l’avant-corps du château d’Anet, construite par
Philibert De l’Orme après 1547, et remonté au xixe siècle à l’École des Beaux-
Arts à Paris (Pérouse de Montclos, 1995 – ﬁg. 6.40).
Rappelons que De l’Orme critique à plusieurs reprises dans ses traités l’usage du
fer, parce que ce dernier rouille et fait éclater la pierre, et surtout parce que De l’Orme
estime qu’un maître maçon maîtrisant la coupe des pierres peut par ce moyen éviter
d’utiliser le fer (De l’Orme, 1567, 68, cit. 5). Il critique les maçons parisiens qui selon
lui usent des tirants et ancres métalliques liant poutres et murs pour stabiliser ces
derniers et ainsi économiser sur l’épaisseur du mur à construire (De l’Orme, 1561,
5v-6, cit. 3).
Il est ainsi intéressant de noter la présence d’un tirant métallique sous la platebande de l’avant-corps du château d’Anet (ﬁg. 6.40), soit qu’elle corresponde à une

129

<!-- p. 131 -->

Chapitre 6. Typologie constructive des plates-bandes

disposition d’origine voulue par De l’Orme, soit qu’elle ait été ajoutée au xixe siècle
par les maçons et l’architecte qui furent chargés à Paris de son remontage.

Fig 6.40 – Avant-corps du château d’Anet construit par De l’Orme après 1547,
remonté à Paris au xixe s.

La construction de la grande colonnade du Louvre à Paris (1667-1670) par
Claude Perrault, Louis Le Vau et Charles Le Brun provoque un grand débat (26)
sur la coupe des pierres des plates-bandes et l’utilisation du métal pour ces dernières (ﬁg. 6.41). La plate-bande de la grande colonnade utilise plusieurs niveaux
de barres horizontales, ancrées dans l’axe des colonnes à des barres verticales. Des
suspentes métalliques complètent le dispositif. Ces plates-bandes, que nous appellerons plates-bandes armées dans la suite, seront construites ensuite essentiellement
au xviiie siècle :

Fig 6.41 – Grande colonnade du Louvre par Claude Perrault (1667-1670)

— portique du Palais-Royal, construit par Pierre Contant d’Ivry en 1747 ;
— portique de l’église Saint-Sulpice, à Paris, construit par Servandoni entre 1732
et 1749 (Losserand, 2017a) ;

(26). Sur les débats autour de la construction des plates-bandes de la grande colonnade du Louvre,
voir les articles parus dans l’ouvrage collectif L’architrave, le plancher, la plate forme : Nouvelle
histoire de la construction : Petzet (2012) Perrault et l’architrave armée ; Tibières (2012) La coupe
des pierres dans les plates-bandes ; Jeanneret (2012) En quête de vérité : le cas de la plate-bande. Sur
les plates-bandes armées en général, voir Middleton (1987) Des architectes qui imitent les ingénieurs
\- La question des linteaux armés au xviiie siècle.

130

<!-- p. 132 -->

Chapitre 6. Typologie constructive des plates-bandes

— portique de la cathédrale Saint-Pierre de Genève construite par Alﬁeri
entre 1752 et 1756 ;
— portiques de l’hôtel de La Marine et de l’hôtel Crillon sur la place Louis XV
(actuelle place de la Concorde), à Paris, par Ange-Jacques Gabriel en 1758
(ﬁg. 6.42) ;
— portique de l’église Sainte-Geneviève (actuel Panthéon), à Paris, par Jacques-
Germain Souﬄot en 1774 ;
— portique du grand théâtre, à Bordeaux, par Victor Louis entre 1772 et 1780.
Ce portique utilise, outre les armatures, une taille des claveaux des voûtes
plates très spéciﬁque, pour permettre aux claveaux de transmettre la poussée
aux deux extrémités de la colonnade (Carrecabe et Glaud, Le clou de Victor
Louis, Association ouvrière des Compagnons du devoir, 2001).
Jeanneret mentionne également des exemples construit à Arras et SaintPétersbourg (Jeanneret, 2012).

Fig 6.42 – Plates-bandes armées de la place Louis XV (actuelle place de la
Concorde), Paris, d’après Patte (1769)

Le mode de construction des plates-bandes de la grande colonnade du Louvre est
largement décrit par Patte (1769) dans Mémoires sur les objets les plus importans
de l’architecture. Patte décrit également la construction des plates-bandes armées à
Paris de l’église Saint-Sulpice, de l’hôtel de La Marine et de l’hôtel Crillon sur la place
Louis XV (actuelle place de la Concorde), du portail des Théatins, du Palais-Royal,
ainsi que celles de Saint-Pétersbourg. Les dessins de Patte seront repris et complétés
par Rondelet, notamment avec les dessins de l’église Sainte-Geneviève, dans l’Art de
Bâtir publié à partir de 1802.

L’Académie royale d’architecture sera consultée à plusieurs reprises au sujet des

131

<!-- p. 133 -->

Chapitre 6. Typologie constructive des plates-bandes

plates-bandes armées au xviiie siècle. Gabriel y présente son projet lors de la construction des plates-bandes armées place Louis XV en 1762. Souﬄot présente à l’Académie
en 1770 les dessins de la plate-bande construite à la cathédrale Saint-Pierre de Genève
par Alﬁeri entre 1752 et 1756, puis remet à l’Académie en 1780 une maquette de la
plate-bande construite pour l’église Sainte-Geneviève à Paris.

6.6.2 L’armature : linteau ou tirant

Les auteurs des traités d’architecture du xviiie et xixe attribuent à l’armature
en fer engravée dans l’intrados des plates-bandes deux fonctions principales, qui se
reﬂètent dans le vocabulaire employé.

Certains auteurs appellent l’armature un linteau de fer ou plate-bande de fer.
Appuyée sur les sommiers, elle y transfère une partie des charges de la plate-bande
comme le ferait une poutre et il n’est pas fait référence à une fonction de tirant.

D’autres auteurs appellent l’armature un « tirant de fer ». Ancrée dans les sommiers de la plate-bande, elle s’oppose à leur écartement sous la poussée.

Par exemple, Patte utilise les deux signiﬁcations du terme dans des situations
diﬀérentes. Il utilise le terme de « tirans » pour les armatures horizontales des platesbandes armées (Patte, 1769, p. 300), et le terme de « linteau de fer » pour les fers
placés sous les plates-bandes des fenêtres de maison (Blondel et Patte, 1777a, p. 266267, voir ﬁg. 6.43). Dans ce dernier cas, il ne représente pas d’ancrage pour le « linteau
de fer ».

Fig 6.43 – Plates-bandes avec linteau en fer engravé sous l’intrados, d’après Blondel
et Patte (1777a, Pl. LXXIV)

Roland Le Virloys et d’Aviler nomment « plate-bande de fer » l’armature qui
« soulage la portée » de la plate-bande de pierre (D’Aviler, 1691, p. 764, cit. 21 ; Roland
Le Virloys, 1770a, p. 451, cit. 63). Roland Le Virloys utilise le terme « tirant de fer »
pour désigner les armatures retenant la poussée des plates-bandes (Roland Le Virloys,
1770b, p. 37, cit. 64).
Au xviiie siècle, lors de l’expertise sur la construction de la plate-bande du palier
de l’escalier monumental du palais de la Chambre des Comptes à Nantes, deux partis s’opposent sur la faisabilité de la plate-bande imaginée par l’architecte. Le parti
s’opposant à la construction de la plate-bande s’appuiera sur l’argument que l’armature en fer mise en place est insuﬃsante pour porter les claveaux. Le parti adverse

132

<!-- p. 134 -->

Chapitre 6. Typologie constructive des plates-bandes

répliquera en montrant que l’armature est en réalité un tirant, et que cette dernière
n’est pas chargée par les claveaux (Bienvenu, 2013, p. 217, 221).

Les deux fonctionnements vus ci-dessus (ﬂexion ou traction) peuvent se combiner, l’armature étant à la fois linteau et tirant. De plus, l’engagement de l’armature
dans la pierre par frottement peut faire passer des eﬀorts de cisaillement entre les
deux, produisant un troisième comportement similaire à une poutre armée. Le comportement mécanique réel est donc plus complexe que celui simpliﬁé présenté dans
les traités.

Il est impossible de donner des aﬃrmations systématiques sur le fonctionnement
des plates-bandes avec armature encastrée dans l’intrados, car le comportement mécanique dépend de nombreux facteurs (mode d’appui ou d’ancrage des armatures
dans les sommiers, frottement entre le tirant et les claveaux, mode de mise en charge,
nature du mortier, etc.). Dans le cas où l’interaction possible entre la pierre et l’armature est négligée en dehors des appuis, et le bon ancrage de l’armature dans les
appuis postulé, on peut remarquer qu’étant donné la faible rigidité du linteau en fer
formé d’une barre carrée ou légèrement rectangulaire en fer forgé l’armature a dans
ce cas pour la plate-bande plutôt un rôle de tirant que de linteau, en particulier si
la plate-bande présente une portée importante. Par ailleurs malgré sa faible rigidité
en ﬂexion, il est envisageable que le linteau ait un rôle provisoire pour les platesbandes des fenêtres et portes ordinaires, comme le suggère Le Camus de Mézières
(Le Camus de Mézières, 1786, p. 116-117, cit. 65). Enﬁn, il peut agir comme sécurité
en cas de rupture des linteaux en pierre, comme le suggère Savot pour les linteaux
des manteaux de cheminée, qui peuvent se rompre sous l’eﬀet de la chaleur du feu
(Savot, 1624, p. 283-284, cit. 8).

Frézier a peut-être le point de vue le plus nuancé concernant l’usage du fer avec
les plates-bandes. Il remarque que pour une plate-bande bien conçue, c’est-à-dire correctement contrebutée, construite avec une pierre résistante, et située sous un arc de
décharge, les armatures ne sont pas utiles. Il convient néanmoins que les armatures
sont « le grand antidote contre les aﬀaissemens de cette espèce de voute » (Frézier,
1738, p. 67, cit. 36). Cette utilité des armatures pour empêcher un claveau de glisser
est également avancée par Denfer (1891, p. 195, cit. 112). Ce dernier donne également les dimensions usuelles pour les armatures pour les plates-bandes des fenêtres,
information généralement non mentionnée par les autres auteurs.

6.6.3 Opposition aux armatures

La critique de l’usage du métal pour contribuer à la stabilité des maçonnerie date
au moins de De l’Orme (1561, 1567) ; voir section 6.6.1. Dans le cas des armatures
pour les linteaux, deux arguments principaux sont avancés en opposition à l’usage du
métal.

D’une part les armatures, qui ne sont pas visibles, donnent l’impression d’une
construction simple, alors que le procédé constructif des plates-bandes armées est
particulièrement complexe pour assembler l’ensemble des claveaux et des fers. L’usage
des armatures irait donc à l’encontre de la vérité de l’architecture.

D’autre part, la corrosion du métal n’assure pas la pérennité du système. Selon
ses détracteurs, cet argument est renforcé dans le cas des plates-bandes armées par

133

<!-- p. 135 -->

Chapitre 6. Typologie constructive des plates-bandes

le fait que le fer n’est pas dans ce cas un procédé de consolidation, mais un élément
essentiel à la stabilité de l’ensemble.

La synthèse de ces deux arguments est présentée en détail par Reynaud (1867,
p. 529-530, cit. 93).

Si la plupart des auteurs signalent la problématique de la corrosion du fer, certains
d’entre-eux condamnent explicitement l’usage des armatures en fer pour les platesbandes. Parmi eux :
— F. Blondel (1675, p. 434, cit. 12) ;
— Reynaud (1867, p. 529-530, cit. 93) ;
— Viollet-Le-Duc (1864, cit. 86) ;
— Monduit (1889, p. 72, cit. 96), qui rejette l’utilisation de ces « horribles linteaux
en fer que l’on entaille dans le dessous ou l’intrados des arcs et des plates-
bandes ». Cet auteur y voit le signe d’un manque de conﬁance du constructeur
qui n’emploie pas les claveaux à crossettes.
L’Académie royale d’architecture préconise l’utilisation de « tirants en fer » sous
une plate-bande de grande portée à Versailles (compte-rendu de 1672, cit. 143), puis
regrette quelques années plus tard leur usage dans les plates-bandes parce qu’elles en
compromettent la durabilité (compte-rendu de 1683, cit. 146).

Pour ﬁnir, notons que Bélidor se place sur un plan diﬀérent, et indique que la
plate-bande n’est pas adaptée aux fortiﬁcations en raison de sa grande poussée, et
que les barres de fer nécessaires pour contrer cette dernière engendre des « dépenses
considérables », limitant l’application de la technique aux « grands édiﬁces » (Bélidor,
1729, Livre II p. 40, cit. 27).

6.7 Coupe des pierres et décor

6.7.1 Refends et faux-appareil

Les refends sont les canaux creusés dans la pierre qui soulignent les joints et
donc l’appareil d’un parement. Ils peuvent également simuler des joints inexistants
et dessiner ainsi un faux-appareil sur le parement, distinct de l’appareil réel.
Les refends apparaissent à la ﬁn du xviie siècle en France sur les places royales et
certains grands hôtels particuliers. Ils sont utilisés en bandes verticales pour souligner
les angles des bâtiments ou des corps de bâtiments, et des surfaces au rez-de-chaussée
(Mignot, 2004, p. 53). L’utilisation des bossages pour encadrer les baies et souligner
l’appareil des arcs et plates-bandes est antérieur, et procède du même principe.

Les exemples suivants illustrent la diﬀérence entre l’appareil d’une part et le fauxappareil souligné par des refends d’autre part. Le cas du 6 rue des Beaux-Arts à Paris
montre même l’existence de règles diﬀérentes fondant le choix de l’inclinaison des
joints de l’appareil et du faux-appareil.
— Paris, 29 rue de la Ferronnerie, Louis XV (Mignot, 2004, p. 33), voir ﬁg. 6.47.
Plate-bande à refend à sept claveaux, appareil réel à cinq claveaux. Même
centre de convergence des joints dans les deux cas.
— Paris, 6 rue des Beaux-Arts, construit vers 1824, date de percement de la rue
(Hillairet, 1997, voir ﬁg. 6.44). Plate-bande à refends à trois claveaux, appareil

134

<!-- p. 136 -->

Chapitre 6. Typologie constructive des plates-bandes

réel à cinq claveaux. Le centre de convergence de la plate-bande réelle est
nettement plus bas que celui de la plate-bande à refends.
— Paris, 16 rue Tournefort, Ancien couvent des Dames Bénédictines du Saint-
Sacrement (Base Mérimée PA00088409), voussure à refends, où l’appareil réel
est diﬀérent du faux-appareil des refends (ﬁg. 6.45).
Les plates-bandes à bossages visibles à Prato sont particulièrement intéressantes
(ﬁg. 6.46). En eﬀet, ces plates-bandes sont en réalité des linteaux monolithes. Le
faux-appareil dessiné par les bossages représente des joints verticaux, qui ne sont pas
réalisables en pratique. L’inﬂuence de la plate-bande en fausse-coupe de la façade de
la cathédrale de Prato est évidente (ﬁg. 8.8).

Fig 6.44 – Plate-bande à refends, Fig 6.45 – Voussure à refends,
6 rue des Beaux-Arts à Paris 16 rue Tournefort à Paris

Fig 6.46 – Linteau avec faux-appareil en Fig 6.47 – Plate-bande à refends,
bossage, imitant des joints verticaux, sur 29 rue de la Ferronnerie à Paris
la façade d’un palais de Prato

135

<!-- p. 137 -->

Chapitre 6. Typologie constructive des plates-bandes

6.7.2 Ablaq

L’utilisation de pierres de couleurs alternées claires et sombres permet également
de souligner l’appareil (ﬁg. 6.48). Ce procédé, désigné comme « décor ablaq » ou « architecture ablaq » (Cejka, 1978), est courant dans l’architecture islamique, et est
apparu également en Toscane après la première croisade. Il dérive probablement de
l’utilisation combinée de la brique et de la pierre dans l’architecture romaine.

Fig 6.48 – Décor ablaq sur les façades de la cathédrale, du château, et de
l’église San Francesco à Prato

Cet eﬀet décoratif peut s’appliquer aux parements des murs, où les assises claires
et sombres sont alternées formant ainsi des bandes de couleur, ou aux structures
clavées, où les voussoirs sont alors de couleurs alternées. Les plates-bandes à décor
ablaq mentionnées par ailleurs dans cette thèse sont :
— les plates-bandes à double crossettes égyptiennes (ﬁg. 6.35 et 6.36) ;
— la plate-bande en fausse-coupe de la masrada ’Âdiliya à Damas (ﬁg. 8.10) ;
— les plates-bandes de la cathédrale de Prato (ﬁg. 8.8 et B.72) ;
— les plates-bandes des façades du château et de l’église San Francesco à Prato
(ﬁg. 6.48).
Plusieurs autres exemples de plates-bandes à décor ablaq sont mentionnés par Lampariello (2012) en Toscane : église de Santo Stefano al Ponte à Florence, Lucignano
près d’Arezzo.
Cejka (1978) étudie en détail l’architecture ablaq au sein de l’architecture islamique. Il distingue trois modes constructifs pour les arcs à joints courbes. Dans le
premier, le joint courbe fait toute la profondeur de l’arc (ﬁg. 6.49 a). Dans le deuxième,
le joint présente une partie courbe sur l’avant de l’arc, et une partie plane à l’arrière
(ﬁg. 6.49 b). Sur l’exemple donné par Cejka, la partie courbe est de profondeur plus
réduite que la partie plane du joint. Dans le troisième, le joint courbe est créé par
placage (ﬁg. 6.49 c). Cejka ne donne pas d’indication particulière sur les matériaux
et l’assemblage entre la partie structurelle de l’arc et le placage (la partie décorative). Ces observations pour les arcs s’appliquent probablement également pour les
plates-bandes à joints courbes.
Nous n’avons connaissance que d’un seul exemple en France de plate-bande avec
un décor de type ablaq, dont l’eﬀet est beaucoup moins marqué, à Voisinlieu dans

136

<!-- p. 138 -->

Chapitre 6. Typologie constructive des plates-bandes

(a)

(b)

(c)

Fig 6.49 – Modes constructifs des claveaux ablaq dans l’architecture islamique ;
schémas de principe d’après les dessins de Cejka (1978, 5-Abb19a, Abb20)

l’Oise (ﬁg. B.20).

6.7.3 Non-ﬁabilité des dessins et gravures

Les dessins et les gravures des façades ne sont pas des sources ﬁables concernant
l’appareil des plates-bandes. Les raisons de cette non ﬁabilité a déjà été explorée
lors de la considération des pratiques diﬀérentes des architectes et des appareilleurs
(section 6.3.6). Nous donnons ci-dessous deux exemples signiﬁcatifs qui illustrent ce
phénomène.

Palladio et le palazzo Barbarano à Vicence

La façade sur rue du palazzo Barbarano à Vicence possède plusieurs caractéristiques intéressantes regardant la relation entre coupe des pierres et dessin. Comme de
nombreux édiﬁces à Vicence, un faux-appareil en enduit recouvre la maçonnerie en
brique. Le faux-appareil des baies du rez-de-chaussée correspond à une plate-bande à
cinq claveaux, avec une clé un peu plus large que les claveaux voisins. La hauteur de
la plate-bande correspond à une seule assise du faux-appareil. Le dessin du projet (27)
est présenté par Palladio (1570, Livre 2) dans I quattro libri dell’architettura, alors
que le bâtiment est déjà en cours de construction (ﬁg. 6.50). Ce dessin ne correspond
pas à la façade eﬀectivement construite. En eﬀet, Palladio propose sur son dessin
une plate-bande dont la hauteur correspond à deux assises et qui est composée de

(27). Le texte de Palladio est accompagné par deux ﬁgures page 22, qui sont des versions antérieures
du projet, ce que souligne l’auteur. Il indique que les nouveaux dessins n’ont pas pu être intégrés à
temps pour l’impression. Seul le dessin de la page 23, reproduit ici, est présenté comme l’élévation
du projet en cours de réalisation.

137

<!-- p. 139 -->

Chapitre 6. Typologie constructive des plates-bandes

seulement quatre claveaux, et donc sans clé centrale, contrairement à l’usage d’utiliser
un nombre impair de claveaux (voir section 6.2). Notons que toutes les autres platesbandes publiées par Palladio dans I quattro libri dell’architettura sont composées d’un
nombre impair de claveaux (trois ou cinq).

Fig 6.50 – Façade sur rue du Palazzo Barbarano à Vicence, d’après Palladio (1570,
Livre 2 p. 23)

L’originalité de ce dessin est peut-être liée à la liberté laissée par le faux-appareil,
non contraint par les nécessités de la coupe des pierres et de la stabilité des platesbandes. Palladio a pu choisir de représenter un nombre pair de claveaux, sachant que
cette disposition, qui n’est pas admise en pratique pour la construction en pierre de
taille, n’avait aucune importance dans le cas de ce faux-appareil.

Ledoux et l’hôtel d’Uzès à Paris

Le portail de l’hôtel d’Uzès, construit en 1767-1769 par Claude-Nicolas Ledoux (1736-1806) a fait l’objet de nombreuses représentations, en raison notamment de l’organisation d’un concours de perspective de l’Académie d’Architecture en 1784 qui propose le portail de l’hôtel d’Uzès comme sujet
(ﬁg. 39, 40, 41, 55, 62, 66, 67, 70, 80, 81, 109 dans Paze-Mazzi, 2015, p. 55). Elles illustrent la diversité des représentations d’une même plate-bande. Sur les gravures et
dessins présentés ci-dessous, chaque ﬁgure présente une inclinaison diﬀérente (joints
verticaux, inclinés avec inclinaison constante, inclinés rayonnants). Deux dessins représentent sept claveaux, et le troisième neuf claveaux. Le portail a été détruit en 1848,
mais un daguerréotype réalisé probablement peu avant la destruction permet d’observer l’appareil réel de cette plate-bande. Elle était constituée de neuf claveaux inclinés
à lits brisés (Paze-Mazzi, 2015, ﬁg. 109 – Daguerréotype attribué à Victor Chevalier
ou à Claude Félix Niépce de Saint-Victor, collection CCA. PH1984 :0155).

La ﬁgure 6.51, qui représente des joints verticaux, pourrait provenir d’une réédition de L’architecture considérée sous le rapport de l’art, des mœurs et de la législation
publié en 1804 par Ledoux lui-même. La première édition du livre ne fait pas apparaître ce dessin avec plate-bande en fausse-coupe.

138

<!-- p. 140 -->

Chapitre 6. Typologie constructive des plates-bandes

Fig 6.51 – Portail de l’hôtel d’Uzès, construit par Ledoux ; schéma gravé d’après
Ledoux, ne représentant pas l’appareil réel de la plate-bande (Gallet 1980)

Fig 6.52 – Portail de l’hôtel d’Uzès à Fig 6.53 – Portail de l’hôtel d’Uzès à
Paris ; dessin ne représentant pas Paris ; dessin ne représentant pas
l’appareil réel de la plate-bande, l’appareil réel de la plate-bande,
d’après http://www.metmuseum.org/ d’après http://gallica.bnf.fr/ark:
art/collection/search/343839 /12148/btv1b103035743

139

<!-- p. 141 -->

Chapitre 7

Plates-bandes à joints en X

Résumé : Ce chapitre présente les informations réunies sur les plates-bandes à
joints en X, qui sont des plates-bandes à la stéréotomie particulière, et dont tous
les exemples construits connus datent du Moyen Âge. Le principe constructif de ces
plates-bandes est exposé, puis les exemples construits sont répertoriés, et enﬁn les
quelques références écrites mentionnant ces plates-bandes particulières sont présentées.

Sommaire
7.1 Construction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 141
7.2 Exemples construits au Moyen Âge . . . . . . . . . . . . . . . . . 141
7.3 Références écrites . . . . . . . . . . . . . . . . . . . . . . . . . . . 142
7.4 Expériences . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 146
7.4.1 Expériences aux ateliers de l’ENSA Paris-Malaquais . . . 146
7.4.2 Expériences aux Grands ateliers de l’Isle d’Abeau . . . . . 147

140

<!-- p. 142 -->

Chapitre 7. Plates-bandes à joints en X

7.1 Construction

Selon la déﬁnition établie précédemment (section 6.1.2 p. 94), les plates-bandes à
joints en X sont constituées de claveaux tous identiques, composés chacun de deux
trapèzes ou triangles tête-bêche (ﬁg. 6.12 p. 95).

Contrairement aux plates-bandes ordinaires, où la clé est toujours le dernier claveau à être mis en place, dans les plates-bandes à joints en X les claveaux sont
nécessairement mis en place séquentiellement d’un bout à l’autre de la plate-bande,
comme cela est également le cas pour les plates-bandes en fausse-coupe (ﬁg. 7.1).

1 2 3 4
5
6
7

Fig 7.1 – Assemblage séquentiel d’une plate-bande à joints en X

7.2 Exemples construits au Moyen Âge

Les exemples de plates-bandes à joints en X connus à ce jour sont présentés dans
le catalogue en annexe (section B.4). Les informations les concernant sont très lacunaires. Les plates-bandes repérées semblent avoir été construites au xiiie et xive siècle.
Elles ne correspondent pas à une zone géographique bien déﬁnie : les exemples se
trouvent en Italie, Roumanie et Hongrie (ﬁg. 7.3). La mention d’une équipe de maîtres
maçons de Saint-Dié dans les archives de l’exemple roumain de Alba Iulia pourrait
indiquer que des maîtres maçons français aient eu connaissance ou aient participé à
la construction ce type de plate-bande. Néanmoins nous n’avons pas connaissance de
plate-bande de ce type ou s’y assimilant en France au Moyen Âge, la première platebande en fausse-coupe française retrouvée n’étant pas antérieure à 1601 (Montceauxen-Brie).

La typologie des plates-bandes à joints en X est variable. Elles sont construites
avec un nombre impair de claveaux, compris entre 5 et 7 sur les exemples où cette
information est disponible. L’angle ϕ des joints avec la verticale varie de façon importante :
— à Prato, ϕ est compris entre 5 et 7◦environ ;
— à Alba Iulia, les claveaux sont formés de triangles équilatéraux, et ϕ est donc
égal à 30◦;

141

<!-- p. 143 -->

Chapitre 7. Plates-bandes à joints en X

— à Arezzo, nous n’avons pas pu mesurer ϕ, les joints ﬁns correspondant d’ailleurs
peut-être à un faux-appareil ;
— sur le dessin de Léonard de Vinci, les claveaux sont formés de triangles isocèles
(non équilatéraux), et ϕ est égal à 25◦environ.

Fig 7.2 – Plate-bande du portail sud du transept de la cathédrale de Prato,
d’après Raguenet (1915a)

Fig 7.3 – Localisation des cinq exemples de plates-bandes à joints en X connus (fond
de carte : http://www.openstreetmap.org)

7.3 Références écrites

Il existe peu de références écrites à ce type de plate-bande, hormis un dessin de
Léonard de Vinci, et quelques mentions récentes de l’existence de ces plates-bandes
dans des articles.

142

<!-- p. 144 -->

Chapitre 7. Plates-bandes à joints en X

Le Codex Atlanticus est un recueil de dessins et de textes de Léonard de Vinci
qui auraient été composés entre 1478 et 1518. Le feuillet 91 du Codex Atlanticus est
daté vers 1480-1482 (Lampariello, 2012). Il représente de haut en bas des assemblages
de poutres en bois mises bout-à-bout, une poutre armée avec une machine permettant de cintrer la partie inférieure de la poutre avant la mise en place de la partie
supérieure (1), et deux plates-bandes en pierre (ﬁg. 7.4). Les indications manuscrites
suivantes accompagnent les dessins des plates-bandes :

I dua triangoli hanno a essere appiccati insieme e d’un pezzo
D’un pezzo i due triangoli
Questo di sopra e questo di sotto sono modi d’un arco, ovver cardinal
d’uscio, da farlo di pezzi

Les deux premières lignes concernent la plate-bande à joints en X. Elles précisent
que les deux triangles forment un seul et même claveau. Les deux dernières lignes
concernent la plate-bande à crossettes.

Fig 7.4 – Plate-bande dessinée par Léonard de Vinci vers 1480-1482, Codex
Atlanticus f.0091 v

Fleury (2010) fait référence au dessin de Léonard de Vinci parmi ses solutions
de « franchissements plans ». Motro (2009, p. 25) mentionne brièvement la platebande de Alba Iulia comme un exemple peu connu du passage du linteau à la platebande (ﬁg. 7.5). Cependant il n’existe pas à notre connaissance d’étude d’ensemble
concernant le principe des joints en X.

Fig 7.5 – Plate-bande à joints en X d’Alba Iulia (2), d’après Motro (2009)

Pour ﬁnir, notons que le « berceau suspendu » de Simonin présente une légère
similitude avec les plates-bande à joints en X (Simonin, 1792, p. 37-38, cit. 68). Le
« berceau suspendu » est une plate-bande dont les joints en coupe visible sont inversés

(1). Sur le sujet des poutres armées en bois au xve siècle, voir Bouticourt (2008, 2016).
(2). Les proportions du schéma de droite ne correspondent pas à la plate-bande d’Alba Iulia. Ce
schéma indique probablement uniquement l’assemblage séquentiel de ce type de plate-bande.

143

<!-- p. 145 -->

Chapitre 7. Plates-bandes à joints en X

(trapèzes avec grand côté vers le bas), donnant ainsi l’impression de l’instabilité des
claveaux pour l’observateur qui ne voit que le front du berceau (ﬁg. 7.6). Cependant,
dans la solution présentée par Simonin les claveaux sont appuyés sur le mur, et
l’auteur indique que ces derniers doivent avoir suﬃsamment de queue pour que leur
centre de gravité soit à l’aplomb du mur, évitant ainsi leur basculement. La similitude
provient, outre de l’aspect des joints, des pyramides que Simonin ajoute et retranche
aux claveaux E et F pour que les clés et contre-clés puissent être en appui et servir
d’appui aux claveaux voisins (ﬁg. 7.6).

144

<!-- p. 146 -->

Chapitre 7. Plates-bandes à joints en X

Fig 7.6 – « Berceau suspendu », d’après Simonin (1792, Pl. XXII)

145

<!-- p. 147 -->

Chapitre 7. Plates-bandes à joints en X

7.4 Expériences

7.4.1 Expériences aux ateliers de l’ENSA Paris-Malaquais

Aﬁn d’aborder le comportement des plates-bandes à joints en X du point de vue
expérimental, une plate-bande en blocs de bois a été réalisée (3) puis testée en juin
2016 aux ateliers de l’École nationale supérieure d’architecture Paris-Malaquais.

La plate-bande se compose de neuf claveaux identiques, et de deux blocs d’appuis (ﬁg. 7.7). Les deux prismes trapézoïdes composant chaque claveau ont été collés
pour former le claveau ﬁnal. L’angle de frottement du bois étant nettement inférieur
à celui de la pierre, des papiers abrasifs ont été collés sur les faces des blocs pour augmenter le frottement. Les deux blocs d’appuis sont reliés par deux tirants disposés de
part et d’autre de la plate-bande, et centrés en hauteur sur cette dernière.

La géométrie de la plate-bande est déﬁnie par les paramètres suivants (voir paramètrage section 15.1 p. 250) :
— ϕ = 18.4◦(règle du « 1 pour 3 ») ;
— h = 12 cm ;
— 2d = 4 cm ;
— 2a = 2d + 2h tan ϕ = 12 cm ;
— épaisseur demi-claveau : b = 6 cm ;
— Portée libre à l’intrados Li = 68 cm ;
— Portée à mi-hauteur Lm = 72 cm.

Fig 7.7 – Vue 3D éclatée puis assemblée du modèle de la plate-bande à joints en X
en bois

La plate-bande a ensuite été chargée par le biais d’un vérin ﬁxé sur un cadre
métallique. Un essai de ﬂexion trois points (ﬁg. 7.8), et de ﬂexion quatre points ont
été réalisés (ﬁg. 7.9).

En l’absence d’instrumentation, les observations réalisées lors des essais de charge
ont été qualitatives. Dans les deux cas de chargement, une articulation se forme au
niveau de la clé. Les blocs d’appuis étant libres de tourner autour de l’appui conçu
comme un appui rotule, deux autres rotules se forment sous les blocs d’appuis, et non
entre les blocs d’appuis et la plate-bande.

(3). La réalisation de la plate-bande est due à Benoît Vérant, responsable des ateliers de l’ENSA
Paris-Malaquais.

146

<!-- p. 148 -->

Chapitre 7. Plates-bandes à joints en X

Fig 7.8 – Essai en ﬂexion trois points d’une plate-bande à joints en X en bois

Fig 7.9 – Essai en ﬂexion quatre points d’une plate-bande à joints en X en bois

Les plates-bandes à joints en X connues possèdent toutes des blocs d’appuis engagés dans la maçonnerie et chargés par le mur au dessus du niveau de la plate-bande.
Il a donc été choisi, pour l’expérience réalisée l’année suivante en pierre de taille, de
modiﬁer le type les blocs d’appuis et la position du tirant.

7.4.2 Expériences aux Grands ateliers de l’Isle d’Abeau

Description de l’expérience

Une étude expérimentale a été conduite aux Grands ateliers de l’Isle d’Abeau
(GAIA) en mars 2017 sous la direction de Maurizio Brocato et Thierry Ciblac. Deux
plates-bandes en pierre de taille ont été construites : une plate-bande à joint en X
(IA01 – ﬁg. 7.10), et une plate-bande à joints en X réglés (IA02 – ﬁg. 7.11). L’aspect des joints en vue de face est identique pour les deux plates-bandes, et diﬀérent
en vue de dessus et de dessous. Les claveaux ont été taillés et fournis par l’entreprise S.N.B.R. (4) (ﬁg. 7.12).

Chaque plate-bande est composée de sept claveaux, deux sommiers, et un tirant métallique de 24 mm de diamètre ﬁxé aux sommiers. Des plaques en caoutchouc
de 5 mm d’épaisseur sont disposées au niveau des joints, pour rattraper les imprécisions de coupe des pierres et de pose, et permettre la pose à joints secs (sans mortier)
en vue de la réutilisation des claveaux.

La pierre utilisée est un calcaire de Bourgogne (Semond doré) de couleur beige,
de masse volumique théorique 2210 kg/m3, et de résistance moyenne à la compression
égale à 76,6 MPa. Le volume de chaque bloc non percé est 0,3 × 0,2 × 0,3 = 0,018 m3.

(4). S.N.B.R. est une entreprise de restauration de monuments anciens (maçonnerie, pierre de taille
et sculptures), basée à Sainte-Savine (Aube).

147

<!-- p. 149 -->

Chapitre 7. Plates-bandes à joints en X

Fig 7.10 – Vue 3D éclatée puis assemblée, du modèle de la plate-bande à joints
en X (IA01), avec bloc d’appui en rouge, et appui glissant en magenta

Fig 7.11 – Vue 3D éclatée puis assemblée, du modèle de la plate-bande à joints en X
réglés (IA02), avec bloc d’appui en rouge, et appui glissant en magenta

Fig 7.12 – Claveaux – joints en X (IA01 à g.) et joints en X réglés (IA02 à d.)

148

<!-- p. 150 -->

Chapitre 7. Plates-bandes à joints en X

La mesure du poids des blocs donne une masse volumique de 2217 kg/m3 avec un
écart type de 18 kg/m3 (10 blocs pesés).

La géométrie de la plate-bande à joints en X est déﬁnie par les paramètres suivants
(voir paramètrage section 15.1 p. 250) :
— ϕ = 18.4◦(règle du « 1 pour 3 ») ;
— h = 30 cm ;
— 2d = 10 cm ;
— 2a = 2d + 2h tan ϕ = 30 cm ;
— épaisseur demi-claveau : b = 15 cm ;
— Portée libre à l’intrados Li = 1,30 m ;
— Portée à mi-hauteur Lm = 1,40 m.

Fig 7.13 – Plate-bande à joints en X IA01

Fig 7.14 – Plate-bande à joints en X réglés IA02

Montage

Les claveaux ont été percés en leur centre pour faciliter leur manutention
(ﬁg. 7.12). Lors du montage, des barres en acier sont passées à travers les trous,
et des sangles textiles sont utilisées pour permettre le montage progressif de la platebande à l’aide de cales ajustables mobiles (ﬁg. 7.15 à gauche). Le tirant métallique est
le dernier élément mis en place. Il est légèrement mis en tension avant le relâchement
des sangles textiles (ﬁg. 7.15 à droite).

149

<!-- p. 151 -->

Chapitre 7. Plates-bandes à joints en X

Fig 7.15 – Plate-bande IA01 en cours de montage

Chargement

Chaque plate-bande a été chargée par une force verticale appliquée à la clé de la
plate-bande, à l’aide d’un vérin équipé d’une cellule de charge pour mesurer l’eﬀort
appliqué. La charge verticale maximale appliquée lors des expériences à l’Isle d’Abeau
vaut 10 kN environ. Cette charge était volontairement faible pour éviter d’aller jusqu’à
la rupture et pouvoir réutiliser les claveaux. Pour cette charge appliquée progressivement, nous avons observé l’ouverture des joints et une ﬂèche de l’ordre de 4 mm
(ﬁg. 7.16).

Les résultats de l’instrumentation, qui n’ont pas pu être exploités et reliés aux
modèles de calcul, sont présentés en annexe (chapitre D).

Fig 7.16 – Plate-bande IA02 chargée, avec une règle droite posée sur l’extrados pour
visualiser la déformation

150

<!-- p. 152 -->

Chapitre 8

Plates-bandes en fausse-coupe

Résumé : Ce chapitre traite des plates-bandes en fausse-coupe, qui furent
construites à partir du xviie siècle en France. Les informations sur la fausse-coupe
tirées des traités d’architecture sont présentées. Les exemples de plates-bandes en
fausse-coupe proposés dans ce chapitre sont pour la plupart potentiels, car la géométrie exacte de leur coupe est par nature cachée. Ces exemples sont regroupés et
présentés par thèmes, pour essayer de dresser le portrait d’une technique qui eut un
emploi beaucoup plus important que celui suggéré par sa présentation dans les traités
d’architecture et de coupe de pierre.

Sommaire
8.1 La fausse-coupe dans les traités . . . . . . . . . . . . . . . . . . . 152
8.2 Plates-bandes en fausse-coupe potentielles . . . . . . . . . . . . . 154
8.2.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . 154
8.2.2 Jacques Lemercier (av. 1586-1654) . . . . . . . . . . . . . 156
8.2.3 Le Louvre . . . . . . . . . . . . . . . . . . . . . . . . . . . 158
8.2.4 Le dix-septième siècle . . . . . . . . . . . . . . . . . . . . 159
8.2.5 Refus et renouveau de la fausse-coupe au XVIIIe siècle . . 161
8.2.6 La fausse-coupe à Chambéry . . . . . . . . . . . . . . . . 162
8.3 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 164

151

<!-- p. 153 -->

Chapitre 8. Plates-bandes en fausse-coupe

8.1 La fausse-coupe dans les traités

L’inclinaison des joints des arcs et des plates-bandes répond à des règles géométriques. Dans le cas des arcs et voûtes courbes, les joints doivent converger vers le
centre de courbure de l’intrados (principe de normalité, voir section 5.4). Dans le cas
des plates-bandes et voûtes plates, ils doivent être inclinés par rapport à la verticale
(principe d’inclinaison, voir section 6.3).

La fausse-coupe désigne les joints de lits en coupe dont l’inclinaison ne répond
pas à ces règles. Les joints en fausse-coupe des arcs courbes sont donc horizontaux ou
verticaux (ﬁg. 8.1), et ceux des plates-bandes sont verticaux (Diderot et d’Alembert,
1756, cit. 44, voir ﬁg. 8.2).

Fig 8.1 – Joints en fausse-coupe mn d’un Fig 8.2 – Plate-bande en fausse-coupe,
arc, d’après Diderot et d’Alembert d’après Diderot et d’Alembert (1756)
(1756)

Puisque l’inclinaison des joints des plate-bandes en fausse-coupe enfreint les règles
géométriques communément admises, les traités indiquent qu’un artiﬁce est nécessairement présent pour garantir la stabilité de ces plates-bandes. Cet artiﬁce peut être
soit une bonne coupe, c’est-à-dire un joint incliné pour les plates-bandes, qui est masqué à l’arrière du joint vertical, soit l’utilisation de barres de fer. La solution de la
bonne coupe est mentionnée ou représentée par :
— D’Aviler (1691, p. 572, cit. 20) ;
— Tiercelet (1728, p. 53, cit. 24) ;
— Frézier (1738, p. 67, cit. 37) ;
— Diderot et d’Alembert (1756, cit. 44) ;
— Blondel et Patte (1777a, p. 266-267, 288, cit. 58, 59) ;
— (Simonin, 1792, voir ﬁg. 8.3).
La solution avec « barres de fer » est mentionnée par Frézier (cit. 37) et Diderot et
d’Alembert (cit. 44).

Nous retenons dans la suite de ce document le vocabulaire suivant, pour éviter
la confusion entre ces deux systèmes (avec joints inclinés masqués ou avec barres de
fer). Nous appelons plate-bande en fausse-coupe une plate-bande dont les joints sont
composés d’un ou deux plans verticaux et d’un plan incliné (avec ou sans barre de
fer). Nous appelons plate-bande à joints verticaux une plate-bande dont les joints
sont uniquement verticaux (avec ou sans barre de fer).

152

<!-- p. 154 -->

Chapitre 8. Plates-bandes en fausse-coupe

La fausse-coupe peut être simple (si les joints verticaux sont présents seulement
d’un côté) ou double (si les joints verticaux sont présents des deux côtés). La ﬁgure 8.2
représente un cas de simple fausse-coupe, et la ﬁgure 8.3 représente un cas de double
fausse-coupe. Cette distinction n’est pas faite dans le vocabulaire utilisé par les traités.

Fig 8.3 – Plate-bande en fausse-coupe, d’après Simonin (1792, Pl. XXI)

Le terme fausse-coupe existe dans le dictionnaire de Félibien, mais concerne uniquement la charpenterie et la menuiserie (Félibien, 1676). La première occurrence
que nous avons trouvé correspondant aux plates-bandes se trouve chez D’Aviler (1691,
p. 572, cit. 20, voir ﬁg. 6.1). Le terme est ensuite utilisé par Frézier (1738, p. 67, cit. 37),
Diderot et d’Alembert (1756, cit. 44), et Blondel et Patte (1777a, p. 266-267, 288,
cit. 58, 59).
En revanche, d’autres auteurs n’utilisent pas le terme de fausse-coupe pour désigner la technique. L’Académie royale d’architecture qualiﬁe ces joints de « joins à
plomb » (1701 cit. 157) ou de « coupes à plomb » (1710 cit. 162). Tiercelet indique que

153

<!-- p. 155 -->

Chapitre 8. Plates-bandes en fausse-coupe

s’ils ne tendent pas au centre, il faut que les « joints paroissent perpendiculaires » et
accompagne son texte d’un dessin explicite d’un claveau en fausse-coupe (Tiercelet,
1728, p. 61, cit. 25). Simonin appelle ce type de plate-bande « Platte-bande à joints
d’aplomb » (Simonin, 1792, p. 36). Chez ces auteurs (sauf Tiercelet dont le dessin lève
toute ambiguïté), il est implicite qu’une plate-bande à joints verticaux n’est pas réalisable, et donc que les joints verticaux sont doublés de joints inclinés. Le terme « joint
à plomb » est dans ce cas un synonyme de « fausse-coupe », et ne désigne pas les
plates-bandes à joints purement verticaux. Comme vu précédemment, pour éviter les
confusions, nous ferons la distinction entre les plates-bandes à joints verticaux (très
rares), et les plates-bandes en fausse-coupe (composées d’un ou deux plans verticaux
et d’un plan incliné).

Du point de vue géométrique, les descriptions des traités apportent quelques indications sur les proportions des joints en fausse-coupe, souvent contradictoires. D’Aviler indique que la profondeur de la (simple) fausse-coupe est de six pouces [15 cm –
D’Aviler, 1691, p. 572), tandis que Diderot et d’Alembert indiquent seulement trois
à quatre pouces (7,5 cm à 10 cm – Diderot et d’Alembert, 1756, cit. 44). Simonin indique dans le cas d’une double fausse-coupe que l’épaisseur correspondant aux joints
verticaux doit valoir de 40 à 50% de l’épaisseur totale (Simonin, 1792, p. 37). Une
telle disposition est critiquée par l’association ouvrière des Compagnons du devoir qui
indique que « un tel appareil aﬀaiblit considérablement la plate-bande, car la partie clavée ne représente souvent plus que la moitié de sa profondeur » (Association
ouvrière des Compagnons du devoir, 1996, p. 129).

Les exemples de plates-bandes en fausse-coupe connus grâce aux traités d’architectures sont rares, et reviennent toujours aux mêmes bâtiments. Les portes des passages
sous les corps centraux des façades de la cour Carrée du Louvre sont les exemples
le plus souvent cités (1). Sont également cités le portail de l’église Saint-Eustache à
Paris (Quatremère de Quincy, 1825) et plus récemment l’hôtel de Brancas (6 rue de
Tournon à Paris – Tibières, 2012). Il existe en réalité bien d’autres exemples. Nous
présentons dans la section suivante ceux découverts au cours de nos recherches.

8.2 Plates-bandes en fausse-coupe potentielles

8.2.1 Introduction

Nous présentons dans cette section les exemples de fausse-coupe potentielle que
nous avons trouvés au cours de nos recherches. L’adjectif potentiel est ici important.

En eﬀet, les exemples de simple fausse-coupe, où la partie verticale du joint est
visible d’un côté de la plate-bande et la partie inclinée est visible de l’autre côté, sont
rares : les plates-bandes des portes latérales sous oculi de la majorité des avant-corps
du Louvre, de Lemercier à Lefuel, et deux exemples de plates-bandes du xixe siècle
à Chambéry. Dans ces cas la présence de la fausse-coupe est attestée, et la possibilité
qu’il s’agisse uniquement de plates-bandes à joints verticaux ne se pose pas.

(1). Les traités mentionnant ces exemples au Louvre pour illustrer les plates-bandes en fausse-coupe,
en utilisant ou non ce terme, sont les suivants : D’Aviler (1691, p. 572, cit. 20), Tiercelet (1728, p. 53,
cit. 24), Frézier (1738, p. 67, cit. 37), Diderot et d’Alembert (1756, cit. 44), Blondel (1752, p. 156,
cit. 56), Quatremère de Quincy (1825).

154

<!-- p. 156 -->

Chapitre 8. Plates-bandes en fausse-coupe

Dans tous les autres cas, il n’a pas été possible de vériﬁer que les plates-bandes
possédaient des joints inclinés internes, soit parce que des joints verticaux étaient
présents des deux côtés de la plate-bande (double fausse-coupe potentielle, comme
dans le passage du pavillon de l’aile Nord de la cour Carrée du Louvre), soit parce
qu’une seule des deux faces de la plate-bande a pu être vue : si nous n’avons pas eu
accès au bâtiment, ou si l’arrière de la plate-bande était masqué par la retombée du
plafond (cas courant). Dans ces cas, il est possible qu’il n’y ait pas de joints inclinés à
l’intérieur des plates-bandes, et donc que la plate-bande soit une plate-bande à joints
verticaux.

Il existe cependant quelques indices qui permettent de favoriser l’hypothèse de
l’existence d’un joint incliné à l’arrière des fausses coupes présentées, et l’absence de
renforts en métal.

\1. La construction de plates-bandes à joints verticaux n’est pas envisagée comme
possible dans les traités d’architecture (voir section 6.3.1 p. 98). Il faut donc
qu’il existe ou bien une coupe inclinée cachée, ou bien des éléments métalliques,
or la présence de ces derniers semble peu probable (voir points suivants).

\2. L’utilisation des armatures métalliques pour les plates-bandes armées est bien
documentée, par les mêmes auteurs qui font référence à la fausse-coupe. Alors
que dans le cas des plates-bandes armées ces auteurs (Patte, 1769 et Rondelet,
1804 notamment) décrivent les armatures mises en œuvre et les avantages et
inconvénients des diﬀérents systèmes, dans le cas des plates-bandes en fausse-
coupe qui pourraient également comporter des barres de fer aucun dessin de
ce type de système n’est répertorié dans les traités.

\3. En cas de présence de métal à l’intérieur des plates-bandes, leur durabilité
s’amoindrit nettement en raison de la corrosion du métal. Dans le cas du
Louvre, qui présente la plus importante concentration de plates-bandes en
fausse-coupe que nous avons trouvé en France, il n’y a pas eu de restauration
de grande ampleur sur les façades intérieures de la cour Carrée qui auraient
vu le remplacement de plates-bandes potentiellement en fausse coupe suite à
la corrosion des fers (2).

\4. Le type de barres qu’il faudrait mettre en place pour compenser l’utilisation de
joints verticaux n’est jamais précisé dans les traités. Sur les exemples présentés
dans la suite, nous n’avons pas vu de « linteau de fer » engravé sous l’intrados
comme ceux existants pour de nombreuses plates-bandes à joints inclinés (voir
section 6.6 p. 128).

Par ailleurs, la restauration partielle des plates-bandes en fausse-coupe n’est pas
possible sans laisser des traces visibles sur l’appareil, en raison de l’assemblage séquentiel nécessaire pour ces plates-bandes, comme pour les plates-bandes à joints
en X vues précédemment (ﬁg. 7.1). Cela signiﬁe que le procédé traditionnel de remplacement des claveaux (remplacement « en tiroir », c’est-à-dire en retirant le claveau
dans un mouvement horizontal perpendiculaire à la façade) n’est pas possible.

(2). Information transmise oralement par Guillaume Fonkenell, ancien conservateur chargé de l’histoire du Louvre, conservateur chargé de la Sculpture et de l’architecture au musée national de la
Renaissance au château d’Écouen.

155

<!-- p. 157 -->

Chapitre 8. Plates-bandes en fausse-coupe

Nous présenterons les exemples de fausse-coupe potentiels, sans faire référence
dans la suite au caractère potentiel de nos observations pour alléger les descriptions,
en réunissant les exemples par thèmes : Jacques Lemercier, Le Louvre, le dix-septième
siècle, le refus et renouveau de la fausse-coupe au dix-huitième siècle, et enﬁn la
fausse-coupe à Chambéry. Pour faciliter la lecture de cette synthèse, les illustrations
et détails pour chaque exemple sont réunis par thème et présentés dans le catalogue
des plates-bandes en annexe (section B.5).

Nous n’avons pas considéré les baies aveugles parmi les exemples de plates-bandes
en fausse-coupe potentiels, car dans ce cas les claveaux peuvent prendre appui sur le
mur (ﬁg. 8.4 et 8.5).

Fig 8.4 – Paris, fontaine des Fig 8.5 – Paris, Louvre, passage de l’aile
Quatre-Saisons rue de Grenelle, Sud de la cour Carrée
construite par Edmé Bouchardon
(1739-1745)

8.2.2 Jacques Lemercier (av. 1586-1654)

Les informations qui suivent concernant la biographie de Jacques Lemercier sont
tirées de la monographie de Gady (2005) concernant cet architecte.

Jacques Lemercier est issu d’une famille de « maîtres maçons tailleurs de pierre »
de Pontoise. Son grand-père Pierre Lemercier (n.c.-1570), son oncle Pierre II Lemercier (n.c.-1638), son père Nicolas Lemercier (1541-n.c.), son demi-frère Nicolas II Lemercier (1600-ap.1648), son demi-frère Jacques Lemercier (1601-1639), et son beaufrère André Gerbault (n.c.-1641) sont tous maîtres maçons. Bien que Nicolas, le père
de Jacques, est également qualiﬁé de « architecte des Bâtiments de la Reine » pour
ses travaux au château de Montceaux-en-Brie, il agit plutôt en tant que maçon ou
entrepreneur qu’en tant qu’architecte.

Jacques Lemercier apprend probablement le métier de maçon tailleur de pierre
auprès de son père, avant un séjour italien de 1607 à 1611. Si aucune archive ne
permet de conﬁrmer ce point, notons cependant que le jeune Jacques Lemercier a
pu avoir l’occasion d’observer les plates-bandes à joints en X en Toscane (Prato et
Arezzo) pendant sa formation en Italie.

156

<!-- p. 158 -->

Chapitre 8. Plates-bandes en fausse-coupe

De retour en France en 1612, il commence sa carrière par un rôle d’ingénieur
travaillant sur les ponts, pour apporter des solutions techniques sur diﬀérents projets.

Le premier projet de bâtiment important où Jacques Lemercier intervient comme
architecte est la chapelle de l’Oratoire du Louvre à Paris (1622-1625).

Suite à la mort de Salomon de Brosse en 1626, Jacques Lemercier devient l’architecte de la reine Marie de Médicis en 1627, puis du cardinal de Richelieu la même
année. Il devient ultérieurement Premier architecte du roi, et est chargé du doublement de l’aile de Lescot au Louvre (actuelle aile Ouest de la cour Carrée).

Jacques Lemercier est le premier architecte qui utilise régulièrement des platesbandes en fausse-coupe. Les exemples conservés se trouvent à l’église Notre-Dame
de Richelieu, à l’église Saint-Pierre Saint-Paul de Rueil-Malmaison, à la chapelle de
la Sorbonne, au Palais-Royal (ancien palais Cardinal), et enﬁn et surtout au Louvre,
où son exemple sera suivi par ses successeurs jusqu’au xixe siècle inclus.

L’attribution à Jacques Lemercier de la construction de l’église Saint-Josephdes-Carmes est hypothétique aujourd’hui, les archives ne permettant pas d’attribuer la construction à un architecte particulier. Cependant, l’utilisation de la faussecoupe pour le portail pourrait être un indice technique en faveur de l’attribution à
Jacques Lemercier.

Les premiers exemples de plates-bandes fausse-coupe redécouverts en France se
trouvent au château de Montceau-en-Brie (ﬁgures B.76 et B.77). Ils pourraient être
dus à Salomon de Brosse. Mais l’absence de fausse-coupe dans les autres réalisations
de Salomon de Brosse permet de douter de cette hypothèse. Qui alors, de Nicolas
(le père) ou de Jacques (le ﬁls), est à l’origine de ces premiers exemples de platesbandes en fausse-coupe ? Rien ne permet de trancher la question aujourd’hui. Notons
seulement une conjonction de circonstances qui ont pu jouer dans cette apparition.

Premièrement, cette famille de tailleurs de pierre est d’origine picarde. Elle a
donc nécessairement eu connaissance des nombreux exemples de plates-bandes que
l’on trouve dans les églises du Moyen Âge de la région, dont certaines présentent une
stéréotomie particulière (plates-bandes à crossettes, plates-bandes à joints courbes –
voir notre historique des plates-bandes au Moyen Âge). La technique de la platebande fait donc partie d’un patrimoine technique local que ces maîtres tailleurs de
pierre connaissaient nécessairement.

Deuxièmement, le jeune Jacques Lemercier a fait le voyage en Italie. Il aurait pu
voir à cette occasion en Toscane la plate-bande à joints en X du portail Sud et la
plate-bande en fausse-coupe de la façade occidentale de la cathédrale de Prato, et
être intrigué par ces systèmes constructifs, très visibles par leur alternance de pierres
blanches et sombres (décor ablaq).

Notons enﬁn, comme cela est souligné par Gady (2005) dans sa monographie de
l’architecte, que « Le goût de Lemercier pour les jeux de stéréotomie s’exprime enﬁn
par des réalisations que l’on pourrait qualiﬁer de “gratuites”, eu égard à leur position
ou à leur discours ». Gady mentionne un escalier en vis évidé à la Sorbonne, une
arrière voussure de Marseille, etc. Il mentionne également les plates-bandes « formées
de pierres parallèles » au Louvre.

Par ailleurs, nous n’avons pas pu conﬁrmer ou inﬁrmer la présence de platesbandes en fausse-coupe à l’intérieur de la chapelle de l’Oratoire du Louvre, un des

157

<!-- p. 159 -->

Chapitre 8. Plates-bandes en fausse-coupe

premiers grands chantiers parisiens de Lemercier (1622-1625). Lemercier ne conduit
pas le chantier à son terme, les dernières travées de la nef et la façade ne seront
construites qu’au xviiie siècle, ce qui pourrait expliquer l’absence de fausse-coupe
pour cet édiﬁce.
Les exemples relevés de fausse-coupe chez Jacques Lemercier sont présentés dans
le catalogue en annexe (section B.5.1 p. 373).

8.2.3 Le Louvre

Les datations et attributions des constructions et modiﬁcations successives du
Louvre qui seront mentionnées dans cette section sont en grande partie tirées d’un
échange sur site avec Guillaume Fonkenell, ancien conservateur chargé de l’histoire du
Louvre. Les éventuelles erreurs d’attributions et de datations qui se seraient glissées
dans la suite de cette section sont de notre fait.
Les exemples relevés de fausse-coupe au Louvre sont présentés dans le catalogue
en annexe (section B.5.2 p. 380). Pour faciliter la lecture de l’analyse qui va suivre,
les exemples de fausse-coupe situés au rez-de-chaussée de la cour Carrée sont localisés
sur la ﬁgure 8.6.
Si le Louvre n’est pas le premier bâtiment dans lequel la fausse-coupe est utilisée,
elle y est remarquable par son emploi presque systématique pour toutes les portes
et fenêtres couvertes par une plate-bande droite (non cintrée) construites par Lemercier et par les architectes qui lui succèdent pour construire les quatre ailes formant
aujourd’hui la cour Carrée.
Sur les façades intérieures de la cour Carrée, en dehors des parties dues à Pierre
Lescot en 1551-1556 (sud de l’aile occidentale, ouest de l’aile méridionale), il semble
que toutes les plates-bandes des portes du rez-de-chaussée, et toutes celles des fenêtres
du premier étage soient en fausse-coupe. Sur les façades extérieures, l’emploi de la
fausse-coupe est plus limité mais encore présent : sur les trois fenêtres du premier
étage des corps centraux des ailes Nord et Sud dus à Louis Le Vau, sur les autres
fenêtres du premier étage de l’aile Sud, ainsi que les trois portes de la façade orientale
(sous la grande colonnade).
Les plates-bandes en fausse-coupe des portes latérales des avant-corps des ailes
Ouest, Sud et Est côté cour Carrée sont particulièrement signiﬁcatives, parce qu’elles
sont construites à simple coupe, et les joints inclinés sont visibles à l’arrière des
plates-bandes depuis l’intérieur des passages (ﬁgures B.86, B.89 et B.99).
Ces plates-bandes à simple coupe forment un ensemble d’exemples didactiques
d’utilisation de la technique. Ce point est d’autant plus frappant que nous n’avons
trouvé que très peu d’exemples de plates-bandes en fausse-coupe permettant l’observation des joints inclinés qui révèlent le secret de la technique.
La fausse-coupe est employée au Louvre par tous les architectes qui se succéderont
à sa construction après Lemercier : Le Vau, Perrault, Percier et Fontaine, Visconti,
Lefuel. La question de l’utiliser se posa lors des débats précédant la construction de la
grande colonnade en 1669 (Tibières, 2012, p. 369). Elle ne fut ﬁnalement pas utilisée
pour les portiques de la grande colonnade, mais elle est présente sur les trois portes
du corps central (ﬁg. B.101), et aux fenêtres du premier étage (donnant sur la loggia
située sous les portiques – ﬁg. B.102).

158

<!-- p. 160 -->

Chapitre 8. Plates-bandes en fausse-coupe

Sur les façades de la cour Carrée, les joints des plates-bandes des portes secondaires et des fenêtres du premier étage sont particulièrement ﬁns, à tel point qu’il est
diﬃcile parfois de les distinguer depuis le sol. Cette ﬁnesse a été notée par Sauval
au xviie siècle (Sauval, 1724a, p. 32, cit. 15).

La question de l’emploi de la fausse-coupe au palais des Tuileries se pose par la
proximité des deux palais, réunis par la Grande galerie longeant la Seine, et parce
que Louis Le Vau, qui a utilisé de façon intensive la fausse-coupe pour la cour Carrée,
est également intervenu au palais des Tuileries. L’observation des photos prises avant
la destruction du palais n’a cependant pas permis d’établir l’utilisation de la faussecoupe aux Tuileries.

8.2.4 Le dix-septième siècle

Les exemples d’utilisation de la fausse-coupe au xviie siècle que nous avons regroupés sont présentés dans le catalogue en annexe (section B.5.3 p. 391).

En 1738, lorsque Frézier évoque et critique l’utilisation de la fausse-coupe, il
indique que « quelques architectes » en ont fait l’usage, sans en préciser les noms
(Frézier, 1738, p. 67, cit. 37). Ces « quelques architectes » regroupent cependant des
grands noms de l’architecture du xviie siècle : a minima, d’après les exemples que
nous avons retrouvés : Jacques Lemercier (av.1586-1654), Louis Le Vau (1610-1670)
et son collaborateur François d’Orbay (1634-1697), et Pierre Le Muet (1591-1669).
Il faut peut-être ajouter à cette liste Charles Joubert (1640-n.c.), architecte moins
connu, et dont la datation de la plate-bande en fausse-coupe à l’amphithéâtre d’anatomie n’est pas connue avec certitude (ﬁg. B.111). Il existe certainement d’autres noms
à ajouter à cette liste.

Nous n’avons pas trouvé d’exemples de fausse-coupe en consultant les monographies de Salomon de Brosse (~1565-1626), de François Mansart (3) (1598-1666), et de
Jules Hardouin-Mansart (1646-1708), mais il n’est pas exclu que ces derniers aient
utilisé la technique.

Aussi, alors que Pérouse de Montclos (1982, p. 92) remarque l’importance de la
stéréotomie dans l’œuvre de François Mansart, et a contrario le faible usage qu’en
fait Louis Le Vau, la fausse-coupe n’a probablement pas été utilisée par Mansart,
alors qu’elle l’a été à de nombreuses reprises par Le Vau. Notons à cette occasion que
si les plates-bandes en fausse-coupe nécessitent une habileté particulière pour leur
taille et leur mise en œuvre, ce n’est pas le cas pour leur épure, qui est très simple en
comparaison avec les épures des escaliers sur lesquelles Pérouse de Monclos s’appuie
implicitement pour comparer l’usage respectif de la stéréotomie chez Mansart et chez
Le Vau.
La fausse-coupe a donc été utilisée au xviie siècle a minima de 1622 (date de
la ﬁn de la construction de Montceaux-en-Brie) jusqu’en 1692 (date du début de la
construction de la cathédrale de Montauban).

(3). Information apportée par les examinateurs lors de la soutenance : Benjamin Mouton a signalé
la présence d’une plate-bande en fausse-coupe à l’intérieur de l’hôtel de Chimay, dans une partie du
bâtiment construite par François Mansart selon Alexandre Gady. François Mansart a donc également
utilisé la technique de la fausse-coupe.

159

<!-- p. 161 -->

Chapitre 8. Plates-bandes en fausse-coupe

aile Sud (Lescot à l’ouest, Le Vau)

B.94

B.91 B.92 B.89 B.90

aile
Lescot
B.99grande
colonnade B.101 aile
Est pavillon de
B.99 B.86 l’Horloge
(Le (Lemercier)(Perrault,
Le B.100 Vau)
Vau
et B.103
Le
B.99 B.87 aile
LemercierBrun)

B.96 B.95 B.96

B.98

aile Nord (Le Vau)

Fig 8.6 – Localisation des plates-bandes en fausse-coupe au rez-de-chaussée de la
cour Carrée du Louvre ; les numéros renvoient au catalogue en annexe ; fond de plan
d’après Blondel (1756, Pl. 5)

160

<!-- p. 162 -->

Chapitre 8. Plates-bandes en fausse-coupe

Notons pour ﬁnir une variante à la fausse-coupe ; Libéral Bruand (1635-1697)
utilise une plate-bande particulière pour la chapelle Saint-Louis de l’hôpital de la
Salpêtrière (4), à joints verticaux et crossettes. Nous n’avons pas répertorié cet exemple
parmi les exemples de fausse-coupe en raison de la présence des crossettes, qui pourrait
correspondre à un système diﬀérent (sans coupe inclinée masquée ni barres de fer).

Fig 8.7 – Plate-bande à joints verticaux et crossettes, chapelle Saint-Louis de
l’hôpital de la Salpêtrière à Paris, construite par Libéral Bruand (1671-1679)

8.2.5 Refus et renouveau de la fausse-coupe au XVIIIe siècle

Les exemples de fausse-coupe au xviiie siècle relevés sont présentés dans le catalogue en annexe (section B.5.4 p. 398).
Au début du xviiie siècle, deux comptes-rendus de l’Académie royale d’architecture indiquent que le sujet de la fausse-coupe a été abordé, et que cette pratique n’a
pas été « approuvée » (1701 cit. 157), et a même été « blâmée » (1710 cit. 162).

Ces deux avis formulés par l’Académie correspondent au début d’une période
qui s’étend des années 1690 (construction de la cathédrale de Montauban) à 1741
(début de la construction de l’Hôtel-Dieu à Lyon par Souﬄot) où nous n’avons pas
trouvé d’exemples ﬁables de plates-bandes en fausse-coupe. Il est probable qu’il existe
des exemples entre ces deux dates, néanmoins les exemples assez nombreux trouvés
avant 1670 environ, et après 1750 environ, et présentés dans ce document contrastent
avec les quelques exemples dont la datation est incertaine entre ces deux dates (amphithéâtre d’Anatomie et hôtel Brancas à Paris).
La diminution de l’utilisation de la fausse-coupe à la ﬁn du xviie siècle peut être
mise en parallèle avec deux cas particuliers, qui n’ont pas valeur de démonstration
mais illustrent le changement d’esprit vis-à-vis de la technique.

(4). La chapelle Saint-Louis de l’hôpital de la Salpêtrière est construite par Libéral Bruand de 1671
à 1679 sur des plans de Louis Le Vau mort en 1670 avant le début des travaux.
Jacques II Bruand (1663-1752), ﬁls de Jacques I Bruand et neveu de Libéral Bruand (tous
architectes), fut admis à l’Académie royale d’architecture en 1699. Il fait partie des signataires avec
Bullet du compte-rendu de l’Académie royale d’architecture du 22 août 1701 qui désapprouve l’usage
des « joins à plomb », c’est-à-dire de la fausse-coupe.

161

<!-- p. 163 -->

Chapitre 8. Plates-bandes en fausse-coupe

Premièrement, bien que la question de son utilisation se soit posée en 1669 (Tibières, 2012, p. 369), la fausse-coupe n’est pas utilisée pour les portiques de la grande
colonnade du Louvre.

Deuxièmement, un compte-rendu de 1679 indique que les académiciens se sont
penchés sur la question de la coupe à donner aux plates-bandes et aux arcs, et que
l’échange mis au jour des « sentiments diﬀérents » sur lequel le compte-rendu ne
s’étend pas (1679, cit. 145). Il indique seulement à propos de ces avis divergents que
l’Académie « a résolu de s’esclairer au premier jour ». Les comptes-rendus suivants
ne font plus état du sujet.
Souﬄot sera donc parmi les premiers au xviiie siècle, s’il n’est le premier, à
réutiliser les plates-bandes en fausse-coupe, lors de la construction de l’Hôtel-Dieu à
Lyon (à partir de 1741). Son utilisation de la technique est limitée au corps central
de l’aile construite le long du Rhône, correspondant à la chapelle des malades : trois
plates-bandes en façade à l’étage noble côté cour et côté quai (ﬁg. B.115), quatre
plates-bandes d’accès aux salles entourant le vestibule du rez-de-chaussée (ﬁg. B.116),
et enﬁn quatre plates-bandes formant tribunes sur la chapelle des malades (ﬁg. B.118).

Les exemples sont nombreux à partir des années 1750, et se prolongent au delà
de la Révolution, notamment avec Charles Percier (1764-1838) et Pierre Fontaine
(1762-1853), Louis Visconti (1791-1853), et enﬁn Hector-Martin Lefuel (1810-1880)
au Louvre.

Le changement du jugement porté sur les fausses coupes est particulièrement
accusé chez J.-F. Blondel, pour qui ces dernières « n’aﬀoiblissant pas la solidité,
donne à l’édiﬁce une hardiesse apparente qui tient du merveilleux. » (Blondel, 1752,
p. 156, cit. 56).

Certains architectes resteront opposés à l’utilisation de la fausse-coupe. Viel, auteur de De l’impuissance des mathématiques pour assurer la solidité des bâtimens,
et Recherches sur la construction des ponts, s’oppose avec force à l’usage des joints
verticaux (Viel, 1805, p. 35, cit. 71). Viel n’utilise pas le terme de fausse-coupe, mais
cette dernière est visée implicitement dans son texte.

Pour compléter les exemples donnés dans la suite, mentionnons le cas particulier
de l’église Saint-Sulpice à Paris, où les plates-bandes des portiques de la façade sont
à joints verticaux. Il s’agit de plates-bandes avec armatures métalliques, et nous ne
les avons donc pas cataloguées avec les exemples de fausse-coupe que nous supposons
construites probablement sans métal.

8.2.6 La fausse-coupe à Chambéry

Les exemples de fausse-coupe relevés à Chambéry sont présentés dans le catalogue
en annexe (section B.5.5 p. 406).

Chambéry présente un ensemble remarquable de sept bâtiments avec des platesbandes en fausse-coupe construites entre 1767 et la première moitié du xixe siècle.
Cet ensemble est remarquable pour plusieurs raisons.

Premièrement, la ville ne présente pas une tradition particulière de la plate-bande,
en raison du mode de construction des édiﬁces. Dans les édiﬁces du centre ancien
conservés aujourd’hui, les larges baies du rez-de-chaussée consacrées aux boutiques

162

<!-- p. 164 -->

Chapitre 8. Plates-bandes en fausse-coupe

sont couvertes par des arcs en anse-de-panier en calcaire de Lémenc. Dans les étages,
les fenêtres rectangulaires sont couvertes par des linteaux monolithes en molasse.
Lors de la construction (ou reconstruction) des façades sur rue et de l’introduction
des plates-bandes, cette dernière sera réservée au portail d’entrée, les autres baies
de la façade étant couvertes par des arcs en anse-de-panier ou par des arcs segmentaires (hôtel de Chateauneuf, hôtel de Beauregard, hôtel des Marquis de Faverges,
immeubles du 231 et 254 place Saint-Léger, 2 rue Métropole, etc.).

Deuxièmement, le nombre d’exemples conservés (au moins sept bâtiments concernés) est très important au regard de la superﬁcie de la ville ancienne actuelle, cette
dernière ayant été détruite en partie lors de la seconde Guerre Mondiale. À titre
de comparaison, nous avons trouvé un seul exemple de fausse-coupe à Lyon située
à 100 km, en dehors de ceux du très exceptionnel Hôtel-Dieu de Souﬄot. Annecy,
ville située à 50 km et de taille comparable, et possédant la même tradition des boutiques avec arcs en anse-de-panier, n’a pas conservé d’exemples de plates-bandes en
fausse-coupe.

Nous avons exploré deux hypothèses pour essayer d’expliquer l’apparition des
plates-bandes en fausse-coupe à Chambéry.

La première hypothèse était l’inﬂuence turinoise, en raisons des échanges culturels
importants entre les deux villes et parce que l’architecte des deux premiers exemples
connus à Chambéry, Luca Raineri était d’origine turinoise (5). Chambéry fut la capitale du Duché de Savoie jusqu’en 1562, date du transfert de la capitale à Turin.
Cependant, la construction des bâtiments à Turin est principalement en brique, et
les quelques façades en pierre de taille présentent des portails avec arc en plein-cintre
ou linteau monolithe, et donc sans plate-bande (6).

La seconde hypothèse était l’inﬂuence lyonnaise. La construction de l’Hôtel-Dieu
a attiré et mobilisé a Lyon pendant une vingtaine d’années (1741-1763) un nombre
important de tailleurs de pierre, qui ont appris ou observé la technique de la faussecoupe au niveau du corps central de l’aile du quai du Rhône. Il est possible qu’à la ﬁn
de ce chantier, vers 1763, certains tailleurs de pierre qui maîtrisaient la fausse-coupe
soient revenus à Chambéry. Les dates de commencement de la construction de l’hôtel
de Roche (1767) et de l’hôtel Chollet du Bourget (1768) ne sont pas incompatibles
avec cette hypothèse.

Dans ces deux hôtels, les joints verticaux des plates-bandes en fausse-coupe sont
soulignés par des refends, ce qui ne s’observe dans aucun des autres exemples français
de plate-bande en fausse-coupe que nous avons réunis. Le caractère expressif et visible
de l’appareil de ces plates-bandes a pu lancer un mouvement d’émulation entre les
maîtres d’ouvrage et entre les maîtres d’œuvre.

Notons en eﬀet que la technique de la fausse-coupe ne répond à aucun intérêt
structurel ou économique. Elle est plus diﬃcile à réaliser et demande un savoir faire

(5). Luca Raineri est désigné comme « architecte, auteur et directeur de la grotte des Échelles en
Savoie » dans la note bibliographique sur son ﬁls, Francesco Raineri (di Vesme, 1968). Son origine
turinoise est indiquée par Juttet (2005). Nous n’avons pas trouvé d’autres informations sur cet
architecte.
(6). Ces informations sur le mode constructif des façades à Turin nous ont été communiquées par
Paolo Cornaglia, professeur au Politecnico de Turin.

163

<!-- p. 165 -->

Chapitre 8. Plates-bandes en fausse-coupe

particulier, deux raisons qui en augmentent nécessairement le prix pour le maître
d’ouvrage.
Pour ﬁnir, l’utilisation à partir de la ﬁn du xviiie siècle de la plate-bande à Chambéry ne sera plus limitée aux édiﬁces prestigieux. Certaines maisons du Faubourg Maché et du Faubourg de Montmélian sont munies au rez-de-chaussée de plates-bandes
massives à joints inclinés, là où l’utilisation d’un linteau en bois ou d’un arc en ansede-panier se serait peut-être montrée plus économique et mieux adaptée à la faible
importance du bâtiment.

La dynamique qui a conduit à la construction à Chambéry d’un grand nombre
de plates-bandes pour couvrir soit les portails des bâtiments, soit les boutiques en
rez-de-chaussée, certaines à joints en fausse-coupe, d’autres à joints inclinés, reste
donc en grande partie inexpliquée.

8.3 Conclusion

Ce parcours thématique des exemples français de plates-bandes en fausse-coupe,
exemples compris du début du xviie siècle au milieu du xixe siècle, permet de formuler
quelques remarques générales.
Premièrement, l’architecte qui semble lancer la technique en France au xviie siècle
est Jacques Lemercier, qui l’emploiera sur de nombreux chantiers, avant de l’appliquer au Louvre à partir de 1639. Cette technique sera reprise par son successeur
au Louvre, Louis Le Vau, et par tous les architectes qui se succéderont au Louvre
jusqu’au xixe siècle inclus.

Après une période avec peu d’exemples de fausse-coupe, entre les années 1690
et les années 1740 environ, de nombreux exemples ont été repérés à partir des années 1750.

En dehors de l’exemple particulier que forme le Louvre où la plate-bande est utilisée sur des façades entières, l’utilisation de la fausse-coupe est réservée aux parties les
plus importantes des édiﬁces : portails au rez-de-chaussée et fenêtres à l’étage noble
essentiellement. La fausse-coupe n’est pas systématisée à l’ensemble des baies d’un
bâtiment. Par exemple, à l’Hôtel-Dieu de Lyon, Souﬄot les utilise en façade uniquement sur le corps central de l’aile donnant sur le Rhône. Le corps central correspond
par ailleurs à la chapelle des malades, et à l’entrée monumentale du bâtiment.

Claude Mignot émet l’hypothèse qu’une des raisons expliquant l’utilisation de
la fausse-coupe en France est qu’elle permet d’intégrer plus harmonieusement les
lignes dessinées par les joints des plates-bandes aux lignes verticales et horizontales
dessinées par les pierres de taille de la façade (7). En eﬀet, dans le cas des portes et
fenêtres bombées (baies couvertes d’un arc segmentaire), et même dans le cas des
plates-bandes à joints inclinés, les lignes inclinées dessinées par les joints rayonnants
créent une tension avec les lignes horizontales et verticales du bel appareil en pierre de
taille. A contrario, les joints verticaux des plates-bandes en fausse-coupe s’intègrent
parfaitement au dessin de l’appareil du reste de la façade.

(7). Échange oral à l’occasion d’une présentation « Les plates-bandes à l’Époque Moderne », en
avril 2017 au Centre André Chastel, à Paris.

164

<!-- p. 166 -->

Chapitre 8. Plates-bandes en fausse-coupe

Pour soutenir cette hypothèse, notons que dans les débats qui précèdent la
construction de la grande colonnade du Louvre en 1669, il est envisagé de construire
les plates-bandes en fausse-coupe pour des raisons de « beauté » (Tibières, 2012,
p. 369). La remarque toute en emphase de J.-F. Blondel montre que les raisons sont
les mêmes au xviiie : « Pour la propreté de l’appareil dans les platebandes droites
du côté de leur parement, on aﬀecte que les joints soient perpendiculaires, comme
on le remarque au Louvre, ce qui n’aﬀoiblissant pas la solidité, donne à l’édiﬁce une
hardiesse apparente qui tient du merveilleux. » (Blondel, 1752, p. 156, cit. 56).

Les plates-bandes en fausse-coupe présentent une certaine ambivalence du point
de vue visuel. D’une part, ces dernières sont réalisées pour ne pas être vues (8), et pour
s’intégrer à l’appareil du mur : joints verticaux semblables à ceux des autres assises,
joints très ﬁns des exemples du Louvre, uniformité des claveaux, etc. Elles sont de
ce point de vue une réussite, car aujourd’hui le souvenir de ces techniques s’est en
grande partie perdu, et les plates-bandes en fausse-coupe sont désormais anonymes
parmi les autres plates-bandes sur les façades des édiﬁces. D’autre part, c’est parce
que le spectacle visuel qu’elles oﬀrent n’est pas conforme à la vérité de l’architecture
que se développe une rhétorique contre l’utilisation de la fausse-coupe au xviiie siècle,
et qu’on leur attribue ce qualiﬁcatif peu ﬂatteur. Elles sont donc à la fois peu visibles
– c’est leur réussite – et trop visibles – ce qui les condamnera provisoirement au début
du xviiie siècle.

Les plates-bandes à joints en X du Moyen Âge, que nous avons présentées au
chapitre précédent (chapitre 7), oﬀrent des similarités conceptuelles avec les platesbandes en fausse-coupe françaises construites à partir du xviie siècle. Dans les deux
cas, les joints visibles sur le front de la plate-bande ne semblent pas garantir la stabilité
de ces dernières. Les plates-bandes à joints en X ont donc pu avoir une inﬂuence sur
l’apparition de la fausse-coupe française.

Les similitudes et relations entre la France et l’Espagne du point de vue de la stéréotomie sont importantes (Pérouse de Montclos, 1982, p. 200, 212). Il est possible que
la technique de la fausse-coupe provienne d’Espagne. Cependant, le premier exemple
dont il est fait mention dans la littérature daterait de 1642 dans un manuscrit de Joseph Gelabert (Díaz et Mozo, 2012), soit dix à vingt ans après la première utilisation
de la fausse-coupe en France par Lemercier.

Deux autres plates-bandes, dont la similarité avec la coupe des pierres des platesbandes en fausse-coupe françaises est encore plus forte, ont été repérées.

Premièrement, le portail de la façade occidentale de la cathédrale de Prato est
couvert par une plate-bande dont les joints visibles en façade sont des joints verticaux (ﬁg. 8.8). Bien que l’arrière de la plate-bande soit en grande partie masqué par
le plafond du petit vestibule d’entrée, on devine le départ de crossettes. La ﬁgure 8.9
représente une vue hypothétique de la construction de cette plate-bande, en supposant que les joints non visibles au dessus des crossettes à l’arrière de la plate-bande
sont inclinés.

Deuxièmement, le portail de la masrada ’Âdiliya (ou masrada ’al-‘Adiliyya) à
Damas (Syrie) est couvert d’une plate-bande dont les joints visibles en façade sont

(8). Les plates-bandes de l’hôtel de Roche et de l’hôtel Chollet-du-Bourget à Chambéry sont de ce
point de vue de rares contre-exemples, où l’appareil en fausse-coupe est souligné par des refends.

165

<!-- p. 167 -->

Chapitre 8. Plates-bandes en fausse-coupe

des joints verticaux comme à Prato (ﬁg. 8.10). Cette plate-bande est composée de
trois claveaux. Sauvaget (1950) indique la présence de crossettes à l’arrière de cette
plate-bande. Ces deux exemples sont construits avec des claveaux de couleurs alternées claires et foncées, selon la technique du décor ablaq.

Fig 8.8 – Plate-bande à joints en fausse-coupe, portail occidental de la
cathédrale de Prato

166

<!-- p. 168 -->

Chapitre 8. Plates-bandes en fausse-coupe

Fig 8.9 – Composition hypothétique de la plate-bande à joints verticaux de Prato

Fig 8.10 – Plate-bande à joints verticaux de la masrada ’Âdiliya à Damas (Syrie),
avec crossettes masquées à l’arrière – photo : Luc Tamboréro

167

<!-- p. 169 -->

Chapitre 9

Exemples construits de
plates-bandes de l’Antiquité à la
Révolution

Résumé : Ce chapitre propose une succincte histoire des plates-bandes à travers la
présentation d’exemples construits dans l’Antiquité, au Moyen Âge puis à l’Époque
Moderne. Pour chaque époque, les traits principaux des plates-bandes tels qu’ils
peuvent être appréciés à partir des exemples réunis sont exposés. Le catalogue des
exemples utilisés dans ce chapitre est présenté en annexe. Les limites de la méthode
adoptée pour tracer cette histoire sont exposées en introduction.

Sommaire
9.1 Méthode de recherche et objectifs . . . . . . . . . . . . . . . . . . 169
9.2 Antiquité . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 170
9.2.1 Du linteau à la plate-bande dans les entablements . . . . . 170
9.2.2 Exemples construits . . . . . . . . . . . . . . . . . . . . . 170
9.3 Moyen Âge . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 176
9.3.1 Portails . . . . . . . . . . . . . . . . . . . . . . . . . . . . 176
9.3.2 Cheminées . . . . . . . . . . . . . . . . . . . . . . . . . . . 177
9.3.3 Baies . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 178
9.3.4 Villard de Honnecourt . . . . . . . . . . . . . . . . . . . . 178
9.4 Époque Moderne . . . . . . . . . . . . . . . . . . . . . . . . . . . . 180
9.4.1 Entablements . . . . . . . . . . . . . . . . . . . . . . . . . 180
9.4.2 Baies . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 180
9.4.3 Escaliers à jour et escaliers suspendus . . . . . . . . . . . 181
9.4.4 Les dessins de Léonard de Vinci . . . . . . . . . . . . . . . 181

168

<!-- p. 170 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

9.1 Méthode de recherche et objectifs

Nous présentons dans ce chapitre une succincte histoire des plates-bandes
dans l’Antiquité, au Moyen Âge, puis à l’Époque Moderne, à travers l’exploration
d’exemples construits. Du point de vue géographique, nous nous concentrons pour
le Moyen Âge et l’Époque Moderne sur les exemples français. Nous réduisons notre
champ de recherche aux plates-bandes dont l’intrados et l’extrados sont plans et
horizontaux.

L’objectif de ce chapitre est d’observer les grandes lignes de l’évolution typologique
des plates-bandes, qui permettent ensuite de choisir des paramètres judicieux pour la
déﬁnition géométrique de l’appareil des plates-bandes qui feront l’objet d’une étude
mécanique dans la partie IV.

En dehors d’un ouvrage collectif sur l’histoire de la construction des structures horizontales (L’architrave, le plancher, la plate forme : Nouvelle histoire de la construction, 2012), les sources spéciﬁquement dédiées au sujet des plates-bandes sont rares.
Les informations sur les plates-bandes tirées de la littérature doivent donc être prises
avec précaution, car elles ne sont souvent que des bribes données au détour d’un
discours plus général sur l’histoire de l’architecture, l’histoire de l’art, etc.

La majorité des exemples répertoriés pour l’Antiquité sont tirés de L’art de bâtir
de Rondelet (1804). Ceux du Moyen Âge et de l’Époque Moderne sont tirées de
sources variées. Nous avons notamment consulté l’essai de typologie des portails de
l’architecture privée parisienne de Kamovska-Monnereau (2004, 2006).

Nous indiquons les datations connues en indiquant les sources de ces datations.
L’analyse de la cohérence des sources, en particulier celles du xixe siècle, sort du
cadre de notre travail.

Cette méthode d’étude présente comme intérêt principal sa rapidité, puisque cette
recherche historique n’est qu’un prélude à l’étude mécanique des plates-bandes. Elle
présente l’inconvénient de donner une vue biaisée des constructions à travers les représentations qu’en donnent les traités d’architecture. Certains exemples connus font
ainsi l’objet de nombreuses mentions. Tel est le cas des plates-bandes à joints courbes
dans l’Oise mentionnées par Viollet-le-Duc à Beauvais, puis reportées de nouveau par
Enlart, mais qui occultent l’existence d’autres plates-bandes à joints courbes ailleurs
que dans l’Oise, avec par exemple au moins un autre exemple dans les Hautes-Alpes,
et surtout l’existence d’une majorité de plates-bandes au Moyen Âge présentant une
coupe des pierres moins complexe. Nous avons tenté dans quelques cas, comme pour
les escaliers et les cheminées, d’étendre notre champ de vision en consultant des
recueils de relevés, qui ne donnent eux-aussi cependant qu’une vue réduite aux structures les plus exceptionnelles, et ne remplacent donc pas une approche archéologique
plus fouillée, qui sort du cadre de cette thèse et aurait nécessité de réduire le champ
d’étude à la fois temporellement et géographiquement.

169

<!-- p. 171 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

9.2 Antiquité

9.2.1 Du linteau à la plate-bande dans les entablements

Cette partie sur l’histoire des plates-bandes dans l’Antiquité est basée essentiellement sur l’Histoire de l’Architecture de Choisy (1899a) et sur l’article Structures
horizontales dans la Rome antique : du linteau à la plate-bande de Adam (2012).

Les architraves en pierre de l’architecture grecque ne sont pas des plates-bandes
clavées, mais des linteaux monolithes qui portent de colonne à colonne (Adam, 2012 ;
Planat, 1888b, p. 484, cit. 100). Ces linteaux peuvent être seuls, ou composés de pièces
juxtaposées (appelées « architraves à bandes » par Choisy, 1899a, p. 319, 363, 375, voir
ﬁg. 9.2). Ils ne sont cependant pas clavés.

Dans l’architecture grecque le matériau privilégié pour la construction des colonnes et des entablements, dont les linteaux, est le marbre. La qualité de ce matériau
est essentiel au succès de ce système constructif lorsque les portées sont importantes,
cependant les pierres tendres locales sont également utilisées pour des portées plus
réduites, comme à Agrigente.

Ce principe de couvrement monolithe de l’espace entre colonnes est repris pour les
temples romains construits à l’époque républicaine, mais avec l’utilisation d’autres
matériaux (travertin romain, tuf volcanique). L’utilisation du marbre n’apparaîtra
dans l’architecture romaine que dans la seconde moitié du ier siècle av. J.-C. (Adam,
2012, p. 67).

Selon Adam (2012, p. 69), l’utilisation de la plate-bande clavée chez les Romains
est un « artiﬁce technique » pour permettre d’exploiter les matériaux locaux qui ne
possèdent pas la résistance du marbre. Les plates-bandes sont placées au niveau de
la frise, au-dessus d’une architrave monolithe. La plate-bande joue alors un rôle de
décharge de l’architrave. Elle est composée de seulement trois claveaux : deux sommiers et une clé. Le temple Jupiter Stator – actuellement appelé temple des Castors
ou Dioscures – est un exemple représentatif de ce système, relevé par Desgodets
(ﬁg. 9.1), et fréquemment cité (1) (ﬁg. 9.3). Construit pour la première fois vers 499
av. J.-C., il sera reconstruit plusieurs fois, et pour la dernière fois en 6 ap. J.-C. sous
Tibère (2).

En résumé, les plates-bandes clavées ne font pas partie de l’architecture monumentale grecque qui utilise presque exclusivement le linteau monolithe. Les plates-bandes
clavées sont utilisées dans l’architecture monumentale de la Rome Antique, qui reprend ou redécouvre des dispositifs préexistants. Le principe de la plate-bande clavée
existait avant son utilisation chez les Romains, notamment chez les Étrusques à la
prison de Mamertine selon Choisy (« plafond clavé », 1873, p. 125 ; 1899a, p. 247, 514).

9.2.2 Exemples construits

Une grande partie des exemples présentés ci-dessous sont tirés de L’Art de Bâtir de
Rondelet (1804). Alors que la première édition de cet ouvrage contient peu d’exemples
de plates-bandes antiques, en dehors de celle du théâtre de Marcellus, de nouveaux

(1). Par exemple chez Choisy (1899a, p. 515, cit. 115), DeLaine (1990).
(2). Notice p. 382 par Rousteau-Chambon dans le fac-similé de Desgodets (1682).

170

<!-- p. 172 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

Fig 9.1 – « Des Trois Colonnes de Campo Vaccino à Rome », temple de
Jupitor Stator, d’après Desgodets (1682, p. 127)

Fig 9.2 – Entablement dorique avec Fig 9.3 – Temple de Jupiter Stator,
architrave à trois bandes, d’après Choisy d’après Choisy (1899a, p. 515)
(1899a, p. 299)

171

<!-- p. 173 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

exemples sont ajoutés aux éditions suivantes. Ainsi sur la planche XXIX de l’édition de
1828, reproduite à la ﬁgure 9.4, huit ﬁgures sont consacrées à des exemples d’appareil
de plates-bandes antiques. Planat (1888b, p. 486-487, cit. 103) reprend les exemples
et ﬁgures présentés par Rondelet (1834).

Nous n’avons pas mentionné ici le cas des plates-bandes en moellon, en brique, ou
combinant les deux, qui sont également utilisées dans l’architecture civile. Adam en
donne des exemples à Ostie et à Pompéi (Adam, 2012). Ce type de plate-bande sort
du cadre de notre étude des structures en pierre de taille.

À Taposiris Magna, en Égypte, une voûte appareillée à crossette datant d’avant le
milieu du iie siècle av. J.-C. a été découverte récemment (Fournet, 2011). S’il ne s’agit
pas d’une plate-bande, elle établit cependant l’existence du système de la crossette
bien avant le premier exemple que nous avons trouvé pour une plate-bande, au théâtre
d’Orange, à l’époque d’Auguste (ﬁg. B.12).

L’utilisation des plates-bandes est souvent expliquée par l’absence à proximité
du chantier de grandes pierres, ou de pierres de résistance suﬃsantes, pour faire des
linteaux (3). Les arènes de Vérone sont une exception. En eﬀet les portes intérieures
d’accès à l’arène sont construites avec des sommiers monolithes très imposants posés
en encorbellement, et combinés avec un claveau unique de petite dimension (ﬁg. B.11).
Les blocs monolithes qui composent les sommiers auraient pu être utilisés comme des
linteaux. Il existe d’ailleurs dans ces mêmes arènes quelques portes, trop rapprochées
les unes des autres pour permettre la mise en équilibre des sommiers, où l’architrave
est construite avec un linteau et non une plate-bande.

Sur le territoire correspondant actuellement à la France, très peu d’indications
sont disponibles sur la possible utilisation de la plate-bande dans l’Antiquité, en dehors de l’exemple du théâtre d’Orange (ﬁg. B.12). Quicherat (1886, p. 377) mentionne
la présence d’une plate-bande dans le mur d’une poterne des murs gallo-romains de
Sens, qui aurait été détruite vers 1840.

Les exemples relevés sont présentés dans le catalogue en annexe (section B.1
p. 345). Des exemples complémentaires, non mentionnés ici, peuvent être trouvés dans
Cejka (1978, p. 5-6 à 5-19) et DeLaine (1990).

(3). Frézier (1738, p. 69, cit. 41), Viollet-Le-Duc (1859b, cit. 89), DeLaine (1990, p. 413), Adam
(2012, p. 69).

172

<!-- p. 174 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

Fig 9.4 – Plates-bandes antiques, d’après Rondelet (1828, Pl. XXIX)

173

<!-- p. 175 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

Fig 9.5 – Ruines du temple du soleil à Baalbek (iie siècle), d’après Planat (1888c,
p. 422)

174

<!-- p. 176 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

Fig 9.6 – Plates-bandes romaines dessinées par Durm (1885, ﬁg. 116)

175

<!-- p. 177 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

9.3 Moyen Âge

Les exemples relevés de plates-bandes utilisées pour les portails sont présentés
dans le catalogue en annexe (section B.2.1 p. 352).

Contrairement aux plates-bandes de l’Époque Moderne qui ont fait l’objet d’une
littérature abondante, les informations disponibles sur les plates-bandes construites
au Moyen Âge en France sont plus réduites.

Nous n’avons pas trouvé d’information particulières sur les plates-bandes du Haut
Moyen Âge (env. 475-1000) en France. En Orient, les premiers exemples de platebande connus datent de 728-729 en Syrie, à la forteresse de Qasr al-Hair ash-Sharqi
(Speiser et Wimmel, 2012, p. 99). En Italie, une plate-bande à double crossettes décharge le linteau de la porte du premier étage du mausolée de Théodorique à Ravenne
(Italie), construit en 519 (Cejka, 1978, 5-Taf1).

Les plates-bandes sont utilisées au Moyen Âge pour trois « ensembles architectoniques » : le portail, la cheminée, et la baie (Reveyron, 1993). Nous nous intéressons
successivement ci-dessous à ces trois cas.

9.3.1 Portails

Enlart (1927, p. 30, cit. 117) indique que les plates-bandes sont « souvent employé[e]s dans les portails du Moyen Âge ». Ce cas semble si courant pour Enlart,
que ce dernier ne prend pas la peine d’en donner des exemples, alors qu’il recense fréquemment dans son manuel d’archéologie les exemples construits des dispositifs qu’il
présente. Quicherat (1886, p. 448, cit. 94) indique également que les plates-bandes
sont d’un « emploi fréquent pendant le xie et xiie siècle ».

A contrario, selon Viollet-le-Duc (1864, cit. 86) les architectes du Moyen Âge n’utilisent pas la plate-bande sauf « à de très rares exceptions ».

D’autres exemples nous ont été signalés sans que nous puissions les vériﬁer et les
inclure au catalogue.
— Neuvy-en-Champagne, église Saint-Julien (Sarthe) ;
— Dangers, église Saint-Rémy (Eure-et-Loire) ;
— Étouvelle, église Saint-Martin (Aisne) ;
— Baignolet, église Saint-Sébastien (Eure-et-Loir) ;
— Équery, église (Oise) ;
— Saint-Georges-de-Boscherville (Seine-Maritime) ;
— Neauﬂes-Saint-Martin, église (Eure) ;
— Ailly, église (Eure) ;
— La Bonneville-sur-Iton, église abbatiale de la Noé (Eure) ;
— Foix, chapelle de Montgauzy (Ariège), dont la plate-bande pourrait néanmoins
dater de la reconstruction de la chapelle romane au xviie siècle.
Les plates-bandes à joints courbes sont celles pour lesquelles on trouve le plus
d’exemples dans la littérature. Viollet-le-Duc ne dessine pour les plates-bandes de portail qu’un seul exemple, celui de Saint-Étienne à Beauvais à joints courbes (ﬁg. B.23).
Enlart (1927, p. 322-323) ne donne que des exemples de plates-bandes à joints courbes

176

<!-- p. 178 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

pour les plates-bandes de portails. Cela n’indique pas nécessairement que leur diﬀusion est plus importante que celle des plates-bandes à joints plans. Elles sont peut-être
plus visuellement marquantes, et sont mentionnées plus souvent de ce fait.

La situation en Italie est mieux documentée, grâce à l’article de Lampariello (2012)
qui donne de nombreux exemples de plates-bandes utilisées pour des portails d’églises.

9.3.2 Cheminées

Les exemples relevés de plates-bandes utilisées pour les cheminées sont présentés
dans le catalogue en annexe (section B.2.2 p. 359).

Alors que Enlart (1927) mentionne l’emploi fréquent des plates-bandes dans les
portails (voir ci-dessus), Bechmann souligne la rareté des plates-bandes à l’Époque
Gothique, sauf en ce qui concerne les manteaux de cheminée (Bechmann, 1993, p. 200201, cit. 123 et 124). Selon Viollet-le-Duc, les constructeurs au Moyen Âge évitaient
l’utilisation de la plate-bande, mais pouvaient être contraints à l’utiliser pour les manteaux de cheminée en raison de leur grande portée (Viollet-Le-Duc, 1859b, cit. 88, 89 ;
1858, cit. 85).

Les informations sur l’histoire des cheminées sont tirées du recueil de relevés
publiés sous la direction de Diot (2007), sauf indication contraire.

Au Haut Moyen Âge, les cheminées occupent une position centrale dans les pièces.
Ce n’est qu’à partir du xiie siècle que les cheminées sont adossées à un des murs de la
pièce. Le foyer de la cheminée est d’abord de plan circulaire, comme au logis des clergerons au Puy-en-Velay (ﬁg. B.48), avant de devenir de plan rectangulaire. Les formes
qui nous occupent sont le manteau de la cheminée et sa hotte. Le manteau est composé des deux piédroits latéraux, sur lesquels est placée une architrave. L’architrave
porte la hotte, qui se raccorde aux conduits de cheminée, eux-même se raccordant
au niveau de la toiture à la souche de cheminée. Si l’architrave est portée par des
consoles, le manteau est alors appelé faux-manteau.
Par conséquent, à partir du xiie siècle, les manteaux de cheminées nécessitent
une structure horizontale pour former la partie haute du chambranle du manteau
de cheminée, mais également pour porter la hotte. Cette structure sera une pièce
monolithe en pierre (un linteau), ou une pièce monoxyle en bois (4). Des plates-bandes
sont également utilisées.

Les conduits de cheminées, d’abord placés dans l’épaisseur du mur et adossés les
uns aux autres, sont à partir du xviie siècle placés les uns à côté des autres. Cette
évolution technique est accompagnée de la diminution de l’importance du manteau
et de sa hotte, et de son intégration progressive au mur au cours de ce siècle (5).

Les plates-bandes des exemples relevés présentent régulièrement des crossettes,
et ce dès le xiie siècle. Les plates-bandes à crossettes au xiie et xiiie siècle ont fait

(4). Pour l’Époque Moderne, voir les préconisations de Blondel et Patte (1777a, p. 398) concernant
les pièces de charpente qui portent la hotte. Le terme plate-bande ne désigne pas ici une structure
clavée : « Il est d’usage de faire les plate-bandes qui portent la hotte avec des pieces de bois de
charpente recouvertes de plâtre de tous côtés, ce qui ne sauroit avoir d’inconvénient, vu leur élévation
& leur grand éloignement du feu ».
(5). « Vers le milieu du siècle, une réaction classique se produit, la cheminée perd déﬁnitivement
ses dimensions colossales. » (Diot, 2007, p. 234.)

177

<!-- p. 179 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

l’objet d’une étude par Conan (2015).

Un cas de plate-bande à joints courbes daté de 1360 environ a été relevé par
Mesqui à Septmonts (ﬁg. B.49). Il s’agit du seul exemple de plate-bande à joints
courbes que nous connaissons pour les cheminées, ce type de plate-bande étant plus
souvent utilisé pour les portails d’église.

Les plates-bandes des cheminées forment parfois un angle obtus en projection
horizontale (ﬁg. B.43), ce qui nécessite des dispositifs complémentaires pour reprendre
la poussée hors-plan de ces plates-bandes. Ces dispositifs peuvent être des tirants
métalliques masqués à l’intérieur du manteau de cheminée, comme au château de
Vincennes (ﬁg. B.42), ou un étrésillon, comme au palais de justice de Paris (ﬁg. B.41).
Cependant même en l’absence de cet angle obtus, la pente que forme la hotte avec la
verticale peut produire elle aussi une poussée perpendiculaire à la plate-bande, qui
nécessiterait une analyse plus poussée des eﬀets hors plans.

Fig 9.7 – Manteaux de cheminées, d’après Viollet-Le-Duc (1858)

9.3.3 Baies

Nous avons réuni les exemples suivants concernant l’utilisation de la plate-bande
pour les baies au Moyen Âge. Outre ces exemples, Viollet-le-Duc indique l’utilisation
plus fréquente qu’ailleurs des plates-bandes « du côté du Rhin » en raison de la
résistance des grès rouges des Vosges (Viollet-Le-Duc, 1858, cit. 85). Nous n’avons
pas retrouvé d’exemple de ce type.

Les exemples relevés de baies au Moyen Âge sont présentés dans le catalogue en
annexe (section B.2.3 p. 365).

9.3.4 Villard de Honnecourt

Le carnet de Villard de Honnecourt date du xiiie siècle. Sur la planche 40 (folio 20 verso) un petit dessin représente de manière très synthétique la coupe d’une
plate-bande (ﬁg. 9.8). Selon Bechmann, la présence de ce dessin montre la curiosité
de Villard de Honnecourt pour ce procédé rare, plutôt que sa fréquence dans l’architecture gothique (Bechmann, 1993, p. 201, cit. 124).

Le dessin est accompagné d’une courte description comme les autres dessins de
cette même planche : « Par chu tail om pendans rivlés, metes le bas el haut ». Cette
description est traduite ainsi par Bechmann : « ainsi taille-t-on des pendants réglés,
mettez le bas en haut » (1993, p. 202).

178

<!-- p. 180 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

Le dessin représente les trois claveaux centraux d’une plate-bande : une clé et
deux contre-clés, avec la clé superposées aux contre-clés. La clé se trouve à l’envers,
ce qui permet la superposition (ﬁg. 9.9). Il faut retourner la clé pour comprendre le
dessin, ce qu’indique le texte.

La clé n’est pas représentée à l’envers par hasard. La précision de la taille des
joints des plates-bandes est importante. Or cette représentation permet la superposition exacte des joints de la clé avec les joints des contre-clés. De plus cela permet
d’économiser l’espace nécessaire pour le dessin, et donc d’économiser le coût du parchemin qui est une ressource précieuse (Bechmann, 1993).

Fig 9.8 – Dessin d’une clé de plate-bande et des deux contre-clés,
d’après Villard de Honnecourt

Fig 9.9 – Analyse du dessin de Villard de Honnecourt (ﬁg. 9.8), d’après Bechmann
(1993, p. 203)

179

<!-- p. 181 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

9.4 Époque Moderne

Nous avons vu précédemment que les plates-bandes sont utilisées au Moyen Âge
pour trois « ensembles architectoniques » : le portail, la cheminée, et la baie (Reveyron, 1993). À l’Époque Moderne, s’ajoute à ces ensembles les entablements reposant
sur des colonnes (avec fronton ou sans fronton) et les escaliers. Quant aux cheminées,
les plates-bandes sont également utilisées au début de l’Époque Moderne pour les
manteaux de cheminée, mais elles perdent rapidement de leur intérêt d’un point de
vue structurel en raison de l’évolution des formes des manteaux (voir le détail de
cette évolution dans la section consacrée aux cheminées du Moyen Âge).
Nous explorons dans la suite les entablements, les baies, et enﬁn les escaliers.

9.4.1 Entablements

À l’Époque Moderne, la plate-bande apparaît sous une nouvelle forme qui donnera
lieu à de nombreux débats sur sa stabilité : elle forme l’architrave, et parfois la frise
des entablements. Le premier exemple de portique avec fronton en France est celui
du château de Villers-Cotterets, construit vers 1550, et aujourd’hui disparu (Pérouse
de Montclos, 1995, p. 109-110).
Les plates-bandes des frontons sont souvent appareillées avec des joints inclinés
à lits brisés. La largeur des frontons, et par conséquent la portée des plates-bandes,
nécessite parfois l’utilisation du métal. Le cas particulier des plates-bandes armées,
construites en combinant la pierre avec plusieurs éléments en fer forgé (tirants, suspentes, ancres, etc.), a été abordé dans la partie consacrée à l’utilisation du métal dans
les plates-bandes (section 6.6 p. 128). Les grandes portées nécessitent parfois l’utilisation de plates-bandes construites sur plusieurs niveaux, à double ou triple rangs
de claveau. Contrairement à l’Italie, où le système constructif des plates-bandes des
frontons est masqué par un revêtement, en France la coupe des pierres est visible (6).
Quelques exemples de plates-bandes utilisés pour les entablements sont données
en annexe (section B.3.1 p. 368).

9.4.2 Baies

Deux évolutions marquées interviennent au xviie siècle pour les baies. Premièrement, le passage de la croisée à la fenêtre se produit, avec le remplacement au début
du xviie siècle des meneaux et croisillons en pierre par des meneaux et croisillons en
bois, puis leur disparition complète à partir des années 1640 (Pérouse de Montclos,
1995, p. 165-166, cit. 126 et 127 ; Benouville, 1888, cit. 101). Deuxièmement, l’utilisation, l’utilisation du linteau et de la plate-bande à la place des arcs se fait de plus en
plus fréquente de la Renaissance au xviiie siècle. Cette seconde évolution pourrait
avoir été favorisée par l’utilisation des huisseries, mal adaptées aux formes en arc
(Bechmann, 1993, p. 199, cit. 125), ou pourrait être liée à l’importation de formes en
provenance d’Italie (Rivoalen, 1888, cit. 102).
Par ailleurs, du point de vue structurel, la réduction puis la suppression du mur
d’appui des fenêtres, avec la diﬀusion des fenêtres à banquettes, diminue le poids

(6). Diﬀérence notée par Tibières (2012, cit. 137) entre les exemples français et italiens.

180

<!-- p. 182 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

supporté par le couvrement des fenêtres (Blondel et Patte, 1777a, p. 52-53, cit. 57),
et favorise de ce fait l’utilisation des plates-bandes.
Les exemples de plates-bandes pour les baies et portes de l’Époque Moderne sont
extrêmement fréquents, et il ne semble pas utile d’en faire une liste ici comme pour
les périodes précédentes.
Nollet (2012) donne des exemples non datés de plates-bandes très particulières
à Bourges, Loches et Malville : des plates-bandes à joints verticaux et clavettes en
pierre ou en bois. Ces exemples sont similaires au dessin de la plate-bande à clavette
de De l’Orme (1567, voir ﬁg. 6.14), à ceci près que sur le dessin de De l’Orme les
joints sont inclinés.

9.4.3 Escaliers à jour et escaliers suspendus

Les escaliers à jour et les escaliers suspendus peuvent utiliser la plate-bande.
Les escaliers à jour en pierre apparaissent dans le sud de la France dès la première
moitié du xvie siècle (Diot, 2011, p. 31). Ces escaliers sont portés sur quatre supports
verticaux placés dans les angles du périmètre du jour. Ces supports verticaux sont
appelés noyaux. Les volées sont portées par des arcs rampants.
Les escaliers suspendus se diﬀusent à partir de la ﬁn des années 1630. Ces escaliers
sont des escaliers à jour mais sans noyaux (Diot, 2011, p. 32). Des exemples d’escaliers
suspendus antérieurs existent (escalier du palais des rois de Majorque à Perpignan de
1347, escalier du Capitole à Toulouse de 1532 à 1542, escalier en vis des Tuileries de
Philibert De l’Orme – Diot, 2011, p. 32).
Nous laissons de côté les escaliers suspendus sur voûte, pour nous intéresser aux
escaliers où l’appareil du limon permet de distinguer cet appareil facilement du point
de vue structurel de l’appareil de la voûte composant la volée. Ce découpage est
arbitraire, et a pour but de ne pas entrer dans le détail des escaliers sur voûte,
qui nécessiteraient une étude à eux-seuls. Le type d’escalier concerné ici est donc
essentiellement celui des escaliers à jour ou escaliers suspendus, avec marche porteuse
et limon porteur. Ce type d’escalier fait parfois usage de la plate-bande, inclinée pour
le limon, et droite au niveau des paliers. Les exemples relevés sont présentés en annexe
(section B.3.2 p. 370).

9.4.4 Les dessins de Léonard de Vinci

Entre 1479 et 1482, Léonard de Vinci, alors à Florence, dessine plusieurs platesbandes appareillées à crossettes. Ces dessins de plates-bandes sont reproduits sur les
ﬁgures 9.10, 9.11, 9.12 p. 182, et 7.4 p. 143. Les informations sur les dates de réalisation
de ces dessins sont données par di Teodoro (2012).
Le premier dessin (ﬁg. 9.10) représente une plate-bande à joints inclinés avec crossettes, et a été réalisé vers 1479-1480. Les joints inclinés ne sont pas rayonnants, ce
qui se traduit par la largeur plus importante de la clé au niveau de l’extrados par
rapport aux autres claveaux. De Vinci rattrape partiellement cette diﬀérence en donnant une largeur moins importante à la clé au niveau de l’intrados par rapport aux
autres claveaux. Le second dessin (ﬁg. 9.11) est une copie du premier, et n’est pas de
la main de Léonard de Vinci selon di Teodoro (2012).

181

<!-- p. 183 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

Fig 9.10 – Plate-bande dessinée par Léonard de Vinci vers 1479-1480, Codex
Atlanticus f.1074 r

Fig 9.11 – Copie de la plate-bande du feuillet f.1074 r de Léonard de Vinci, Codex
Atlanticus f.0050 r

Fig 9.12 – Plate-bande dessinée par Léonard de Vinci vers 1480-1482, Codex
Atlanticus f.0076 r

182

<!-- p. 184 -->

Chapitre 9. Plates-bandes de l’Antiquité à la Révolution

Le troisième dessin (ﬁg. 9.12) est une invention de Vinci, avec une combinaison
de crossettes dans deux directions.

Le quatrième dessin (ﬁg. 7.4 p. 143) est une plate-bande à joints verticaux et crossettes. Les crossettes ne sont pas alignées sur une droite unique, mais alternées sur
deux droites horizontales, selon un principe dont nous n’avons pas trouvé d’exemples
construits.

183

<!-- p. 185 -->

Chapitre 10

Voûtes plates

Résumé : Ce chapitre traite des voûtes plates. Les principaux termes utilisés pour
décrire et qualiﬁer les voûtes plates sont donnés. La confusion existante entre voûtes
plates et voûtes surbaissées est soulignée. Diﬀérents types de voûtes plates sont ensuite étudiés à travers les informations disponibles dans la littérature : les voûtes
plates dallées, les voûtes plates clavées en général, et les voûtes plates d’Abeille qui
sont un cas particulier de voûte plate clavée. Nous nous intéressons en particulier à
l’appareil de ces diﬀérentes voûtes. Les exemples construits connus répertoriés sont
présentés. Enﬁn, quelques considérations sont données sur les voûtes fortement surbaissées, parfois improprement appelées voûtes plates depuis le xviiie siècle.

Sommaire
10.1 Voûtes plates ou voûtes surbaissées ? . . . . . . . . . . . . . . . . . 185
10.2 Voûtes plates dallées . . . . . . . . . . . . . . . . . . . . . . . . . . 188
10.3 Voûtes plates clavées . . . . . . . . . . . . . . . . . . . . . . . . . 189
10.3.1 Appareil . . . . . . . . . . . . . . . . . . . . . . . . . . . . 189
10.3.2 Utilisation du métal . . . . . . . . . . . . . . . . . . . . . 189
10.3.3 Exemples construits . . . . . . . . . . . . . . . . . . . . . 193
10.3.4 Voûtes plates d’Abeille . . . . . . . . . . . . . . . . . . . . 196
10.4 Voûtes très surbaissées . . . . . . . . . . . . . . . . . . . . . . . . 198
10.4.1 Confusion des termes . . . . . . . . . . . . . . . . . . . . . 198
10.4.2 Voûtes surbaissées en pierre de taille . . . . . . . . . . . . 199
10.4.3 Voûtes à la Roussillon, ou voûtes catalanes . . . . . . . . . 200

184

<!-- p. 186 -->

Chapitre 10. Voûtes plates

10.1 Voûtes plates ou voûtes surbaissées ?

Nous rappelons rapidement quelques points de vocabulaire concernant les proﬁls
des arcs, dont les qualiﬁcatifs sont également utilisés pour décrire les voûtes. Les
arcs surbaissés désignent « tout arc dont la ﬂèche est inférieure à la moitié de la
portée » (Pérouse de Montclos, 2007, p. 131). Ils désignent donc tous les arcs dont
la ﬂèche est moins importante que celle de l’arc en plein-cintre de même portée. Les
arcs surbaissés comprennent en particulier les arcs en anse-de-panier, dont le proﬁl
est proche de celui d’une ellipse, et les arcs segmentaires, qui sont des arcs surbaissés
en arc de cercle. Des proﬁls d’arcs surbaissés sont représentés sur la ﬁgure 10.1.

arc arc arc arc
en anse-de-panier déprimé segmentaire plat

Fig 10.1 – Arcs surbaissés, superposés à un arc en plein-cintre

A contrario, les arcs surhaussés désignent les arcs dont la ﬂèche est supérieure à la
moitié de la portée. Ils désignent donc tous les arcs dont la ﬂèche est plus importante
que celle de l’arc en plein-cintre de même portée. Les arcs surhaussés comprennent
en particulier les arcs brisés (1). Les proﬁls d’arcs surhaussés sont représentés sur la
ﬁgure 10.2.

\+ +
\+ + + + + +
arc brisé arc brisé arc brisé arc surélevé arc surhaussé
équilatère en tiers-point en plein-cintre en anse-de-panier
(a) (b) (c) (d) (e)

Fig 10.2 – Arcs surhaussés, superposés à un arc en plein-cintre

Une voûte plate (2) est une voûte dont l’intrados, appelé dans ce cas particulier
plafond, est horizontal (ﬁg. 10.3). Par ailleurs, une voûte dont seule la partie centrale
est plate est appelée voûte déprimée (3).

Par abus de langage, les voûtes surbaissées et en particulier les voûtes segmentaires
sont fréquemment qualiﬁées de voûtes plates (Pérouse de Montclos, 1982, p. 162).
Ainsi les voûtes surbaissées à arêtes doubles de l’hôtel Franque à Avignon sont réfé-

(1). Parmi les arcs brisés, les arcs brisés en tiers-point peuvent désigner soit les arcs brisés dont les
centres des arcs de cercles sont situés sur les naissances, un triangle équilatéral s’inscrivant alors à
l’intérieur de l’arc brisé (Pérouse de Montclos, 2007, p. 132 – ﬁg. 10.2 a), soit les arcs brisés dont les
centres des arcs de cercles sont obtenus en divisant en trois la corde, segment reliant les naissances
(Diderot et d’Alembert, 1751, cit. 43 – ﬁg. 10.2 c).
(2). Diderot et d’Alembert (1765b, cit. 50) utilisent les termes « voûte plane » et « voûte plate ».
(3). « Une voûte déprimée est formée d’une partie centrale plate et de retombées cintrées » (Pérouse
de Montclos, 1982, p. 162).

185

<!-- p. 187 -->

Chapitre 10. Voûtes plates

rencées sous le vocable « voûte plate » dans la base Mémoire de la Médiathèque de
l’Architecture et du Patrimoine (ﬁg. 10.4).

Fig 10.3 – Appareils des voûtes plates, d’après Rondelet (1804, Pl. XXXI) –
ici Rondelet (1828, Pl. XXX)

Nous essaierons donc de faire dans la suite la distinction entre voûte plate et voûte
très surbaissée. Cependant, il n’existe pas de déﬁnition de limite entre les deux. De
plus, comme pour les plates-bandes, et de façon probablement plus systématique
que pour ces dernières, les voûtes plates sont construites avec une certaine contreﬂèche, nommée au xviiie siècle « bombement », « exhaussement » ou « élévation sous
clef » (section 6.5.3 p. 126). Les voûtes plates sont donc généralement des voûtes très
surbaissées. De même, dans certains exemples, la partie déprimée (c’est-à-dire plate)
de la voûte occupe la presque intégralité de la travée, et nous qualiﬁerons la voûte
dans ce cas de voûte plate (par exemple pour les voûtes du vestibule de l’hôtel de
Saige à Bordeaux).

Parmi les voûtes plates à proprement parler, on distingue les « voûtes plates
dallées » d’une part, et les « voûtes plates clavées » d’autre part, qui sont abordées
successivement dans la suite.

Notons, pour conclure ces déﬁnitions, que les voûtes d’arêtes plates, que l’on oppose aux voûtes d’arêtes bombées, sont des « voûtes d’arêtes dont les quartiers ont
leur ligne de faîte dans le même plan horizontal » (Pérouse de Montclos, 2007, p. 135
– ﬁg. 10.5). Il ne s’agit pas des voûtes plates étudiées dans le cadre de cette thèse.

(4). Source des photos : Médiathèque de l’Architecture et du Patrimoine. Liens consultés : Base
MédiatheK MDP86058061, MDP86058082, MDP86058083, MDP86058084.

186

<!-- p. 188 -->

Chapitre 10. Voûtes plates

Fig 10.4 – Avignon, hôtel Franque (1743-1751), voûtes surbaissées, à arêtes doubles
– photos : Meyer, 1955 (4)

Fig 10.5 – Voûte d’arête plate (à g.) et voûte d’arête bombée (à d.),
d’après Rondelet (1804, Pl. XXXVII) – ici Rondelet (1828, Pl. XXX)

187

<!-- p. 189 -->

Chapitre 10. Voûtes plates

10.2 Voûtes plates dallées

Les voûtes plates dallées sont composées de dalles portées soit directement par
les murs délimitant le couvrement, soit par des arcs secondaires (arcs diaphragmes,
arcs doubleaux) divisant la zone à couvrir. Les exemples, essentiellement construits en
Normandie au xvie siècle, relevés par Pérouse de Montclos (1982) dans L’Architecture
à la française, sont :
— chapelles haute et basse de Gaillon (1504-1510) ;
— ancien évêché de Bayeux (1516) ;
— église Saint-Pierre à Caen (1518-1545) ;
— église du Vieux-Saint-Étienne à Caen (1536-1544) ;
— église Notre-Dame des Marais à La Ferté-Bernard (1536-1544) ;
— église de Tillières-sur-Avre (1543-1546) ;
— église Saint-Jacques de Dieppe (1530-1550) ;
— abbaye de Valmont (1530-1550) ;
— église Saint-Germain d’Argentran (vers 1609) ;
— château d’Azay-le-Rideau ;
— château de la Rochefoucauld ;
— église de Cravant ;
— chapelle de la collégiale de Beaune (1530-1533), où Pérouse de Montclos in-
dique la possible existence d’une structure porteuse au-dessus de la voûte.
Outre ces exemples, nous avons pu observer que la voûte de la chapelle des Évêques
de la cathédrale de Toul appartenait à la catégorie des voûtes plates dallées (ﬁg. 10.6).
Les arcs doubleaux déprimés, à retombées cintrées, et composés de claveaux évidés
sont le support de dalles.

a b a

c a c a c a c

b
c a c

Fig 10.6 – Voûte plate dallée de la chapelle des Évêques de la cathédrale de Toul ;
vue de dessous de la voûte étayée (à g.) et vue de détail de l’extrados (à d.) ;
claveau courant d’un arc doubleau (a), claveau à l’intersection de deux arcs
doubleaux (b), dalle en deux parties (c)

Le système des voûtes plates dallées n’est plus utilisé à partir du début
du xviie siècle (Pérouse de Montclos, 1982, p. 163).

188

<!-- p. 190 -->

Chapitre 10. Voûtes plates

10.3 Voûtes plates clavées

10.3.1 Appareil

Les voûtes plates clavées sont les voûtes qui nous intéresserons dans la suite lors de
l’étude de l’inﬂuence de la coupe des pierres sur la stabilité. Ces voûtes peuvent être
appareillées sur diﬀérents plans (le numéro des ﬁgures données dans la liste ci-dessous
renvoient à la ﬁgure 10.3, tirée de l’Art de Bâtir de Rondelet) :
— voûte appareillée sur le plan de la voûte en berceau, également appelée « voûte
en plate-bande » par l’Association ouvrière des Compagnons du devoir (2001,
p. 148) — ﬁg. 1 et 2 ;
— voûte appareillée sur le plan d’une voûte en arc-de-cloître — ﬁg. 3 et 4 ;
— voûte appareillée sur le plan de la coupole — ﬁg. 5 et 6 ;
— voûte appareillée sur le plan de la voûte d’arêtes — ﬁg. 7 et 8 ;
— voûte d’Abeille, du nom de son inventeur, qui présente un appareil particulier
sur lequel nous reviendrons dans la section 10.3.4.
Les règles utilisées pour le choix de l’inclinaison des joints des voûtes plates étaient
probablement similaires à celles que nous avons vues pour les plates-bandes, mais nous
avons trouvé peu d’informations dans les traités. Le ﬂou des instructions données
par Derand concernant l’appareillage de la partie centrale plate d’une voûte d’arêtes
déprimée est sur ce point révélateur : il conviendra de placer le centre de convergence
« directement au dessous de la clef, & distant d’icelle plus ou moins selon que la force
desdites coupes, eu égard à l’estenduë du plat-fond, l’exigera » (Derand, 1643, p. 382,
cit. 9).

Diderot et d’Alembert (1765b, cit. 50) consacrent une planche aux voûtes
plates (ﬁg. 10.7). Le sujet est traité à l’article « voûte » de leur encyclopédie. Les
appareils décrits dans le texte sont celui de la voûte plate appareillée sur le plan de la
voûte en arc-de-cloître, et celui de la voûte plate appareillée sur le plan de la coupole.
Diderot et d’Alembert (1765b) utilisent une proportion de 1 pour 2,5 sur une ﬁgure
représentant la coupe des pierres pour une voûte plate (Diderot et d’Alembert, 1765b,
cit. 50). Voir ﬁg. 32 sur la planche reproduite p. 190.

Nous avons trouvé une seul référence à une règle géométrique pour trouver le
centre de convergence des rayons utilisés pour l’épure (Blondel, 1752, p. 156, cit. 56).
Blondel donne la règle du triangle équilatéral (voir notre étude de cette règle dans le
chapitre 6 concernant la typologie des plates-bandes).

10.3.2 Utilisation du métal

Derand souligne, à propos des escaliers suspendus sur voûtes en arc de cloître, que
ces derniers « ne se font ordinairement qu’au premier étage où ils se terminent sans
monter plus haut » (Derand, 1643, p. 432, cit. 10). Il ajoute qu’il est de coutume de
poursuivre cet escalier en pierre par un escalier en charpente bois, ou de construire
d’autres escaliers ailleurs dans le bâtiment pour desservir les étages supérieurs. Cette

(5). Cette ﬁgure fait partie la planche II des planches intitulées Architecture, Couppe des pierres de
l’encyclopédie de Diderot et d’Alembert. Nous n’avons pas retrouvé le texte correspondant, hormis
la légende mentionnée ici.

189

<!-- p. 191 -->

Chapitre 10. Voûtes plates

Fig 10.7 – Voûtes plates, d’après Diderot et d’Alembert (1765b)

190

<!-- p. 192 -->

Chapitre 10. Voûtes plates

Fig 10.8 – « Double coupe de la plate-bande A B C D d’un pallier. P, point de
concours des joints mn, mn. R, point de concours des joints no, no. G point de
concours des joints de lit des claveaux du plat-fond », d’après Diderot et
d’Alembert (5)

191

<!-- p. 193 -->

Chapitre 10. Voûtes plates

pratique est justiﬁée par Derand en partie pour des raisons de stabilité, et en partie pour des raisons esthétiques. De plus, même dans le cas où l’escalier ne dessert
qu’un étage, il indique que l’« on a de coustume d’y employer quantité de fer, pour
donner plus de soustenuë & de fermeté aux liaisons des pierres, qui les composent,
& pour mieux lier le tout avec les gros murs, qui les environnent & les supportent ».
Il est néanmoins possible de poursuivre l’escalier en pierre au delà du premier étage,
mais Derand appelle à une certaine prudence dans ce cas, et réitère le conseil d’utiliser « fortes bandes & crampons de fer » (Derand, 1643, p. 432-433, cit. 10 – relevé
par Pérouse de Montclos, 1982).

La recommandation de Derand ne s’applique pas directement aux voûtes plates,
sujet qui n’est abordé que partiellement dans son traité au détour des parties plates
des voûtes déprimées. Cependant cela suggère a fortiori l’usage du métal dans les
escaliers dans lesquels les paliers sont construits comme des voûtes plates (ce qui
n’est pas le cas dans l’épure où Derand fait mention du métal). Dans le cas concret
de l’escalier du château d’Anet, construit de 1680-1712 et dont le palier forme une
voûte plate avec de très courtes retombées cintrées, « toutes les pièces du palier sont
goujonnées » (Pérouse de Montclos, 1982, p. 178).
Ces observations du xviie siècle trouvent une conﬁrmation ultérieure dans le cours
de Blondel et Patte (1777a, p. 290, cit. 61, voir ﬁg. 10.9). Ce cours indique à propos des
escaliers : « Quelquefois on fait leurs grands paliers tout droits par dessous, quoiqu’entiérement bâtis en pierre ; mais alors on ne vient à bout de contenir leurs claveaux ou
voussoirs dans une pareille position, qu’en mettant des T de fer dans leurs joints, &
qu’en multipliant les tirants dans l’épaisseur desdits paliers, de manière à empêcher
tout espéce de poussée, surtout vers le vuide de l’escalier. »

Fig 10.9 – Chaînages métalliques pour les voûtes plates formant palier d’escalier,
d’après Blondel et Patte (1777a, Pl. LXXIX)

De façon similaire, des chaînages métalliques sont utilisés pour les voûtes plates
des portiques, notamment dans celles construites conjointement avec les plates-bandes
armée (Patte, 1769 ﬁg. 10.10). Ils sont visibles sur les photos d’une voûte plate en
cours de déconstruction en 1985 à l’École Militaire à Paris (ﬁg. 10.11). L’Association
ouvrière des Compagnons du devoir (2001, p. 147) indique également que les voûtes
plates clavées étaient cintrées par des chaînages en fer.

192

<!-- p. 194 -->

Chapitre 10. Voûtes plates

10.3.3 Exemples construits

L’invention des voûtes plates clavées daterait de l’invention d’Abeille de 1699 selon
Frézier (Frézier, 1738, p. 69, cit. 40), ou de Jean-Baptiste Franque, né en 1684, selon
Hautecœur. Pérouse de Montclos contredit l’aﬃrmation de Hautecœur, et souligne
qu’il faut nuancer l’aﬃrmation de Frézier : « Dès lors que l’on a su faire des platesbandes, on a pu faire des voûtes plates clavées par juxtaposition de plates-bandes,
mais les plates-bandes n’étant pas solidaires les unes des autres, la voûte ne résistait
pas. » (Pérouse de Montclos, 1982, p. 163). La ﬁn de cette aﬃrmation est probablement trop réductrice, nous reviendrons en détail sur le fonctionnement mécanique
des voûtes plates et l’inﬂuence de leur appareillage dans la partie consacrée à l’étude
mécanique des structures en pierre de taille. Quant à l’existence de voûtes plates antérieures, Pérouse de Montclos (1982) donne trois exemples de voûtes plates clavées
eﬀectivement antérieures à Abeille et Franque : à Écouen (1540-1550 – ﬁg. B.142), à
Anet (1552 – ﬁg. B.141) et à Brissac (1614-1620 – ﬁg. B.143). Il existe également en
Espagne des voûtes clavées en pierre de taille fortement déprimées, presque plates,
dès le début du xvie siècle (Pérouse de Montclos, 1982, p. 208-209). Ajoutons de plus
que des voûtes plates clavées sont connues dans l’Antiquité, à Rome et en Égypte
(voir section 9.2 sur l’histoire des plates-bandes dans l’Antiquité, et ﬁg. B.5 et B.14).

Les exemples relevés de voûtes plates clavées sont présentés dans le catalogue en
annexe (section B.6 p. 411). Sauf mention contraire, la source des datations est la
Base Mémoire de la Médiathèque de l’Architecture et du Patrimoine.
D’autres exemples du xviiie siècles sont probablement répertoriés au sein des
notices rédigées par Pérouse de Montclos sur les voûtes clavées construites en France
entre le milieu du xve siècle et la ﬁn du xviiie siècle (Pérouse de Montclos, 1982,
p. 284-316).

Nous reviendrons en profondeur dans la section suivante sur le cas particulier des
voûtes plates d’Abeille, inventées en 1699 par l’architecte du même nom.

(6). Source des photos : Médiathèque de l’Architecture et du Patrimoine. Liens consultés : Base
MédiatheK MDP86087178, MDP86087367, MDP86087261, MDP86087250.

193

<!-- p. 195 -->

Chapitre 10. Voûtes plates

Fig 10.10 – « Plates-bandes de la Place de Louis XV »
(place de la Concorde à Paris), d’après Patte (1769)

194

<!-- p. 196 -->

Chapitre 10. Voûtes plates

Fig 10.11 – Paris, École Militaire, « Voûte déposée de la travée de l’aile formant le
portique droit » (en h.), « Chaînage longitudinal et transversal repris par ancre au
droit des colonnes » (en b.) – photos : Daniel Bontemps, 1985 (6)

195

<!-- p. 197 -->

Chapitre 10. Voûtes plates

10.3.4 Voûtes plates d’Abeille

Exemples construits

Les voûtes plates d’Abeille sont nommées d’après le nom de leur inventeur,
Joseph Abeille (1673-1752). Peu d’informations sont disponibles à propos de Joseph Abeille. Bauchal (1887, p. 1) mentionne un « architecte et ingénieur » de ce nom
(sans préciser son prénom), actif en 1717 à Montpellier puis à Toulouse, mais il ne
mentionne pas les voûtes plates. Bélidor (1729, Livre II p. 61, cit. 28) fait directement
référence à l’invention de « Mr Abeille Ingenieur du Canal de Picardie », mais sans
donner plus d’informations sur ce dernier. Plus récemment, el Wakil (2009) indique
que Joseph Abeille était ingénieur du roi auprès de Jacques V Gabriel (Premier ingénieur du roi), spécialiste des travaux hydrauliques, et qu’il fut actif à Rennes, en
Bourgogne, à Berne et à Genève.

Les voûtes plates d’Abeille sont constituées de claveaux identiques portant dans
deux directions orthogonales. Les claveaux sont des polyèdres dont les coupes verticales par les plans de symétrie sont des trapèzes isocèles. L’intrados forme un plafond
continu, et l’extrados forme un plancher avec des lacunes pyramidales. Cette disposition peut être inversée pour avoir un intrados décoratif avec les lacunes pyramidales,
et un plancher continu.

Les voûtes d’Abeille auraient été inventées par Joseph Abeille en 1699 à la suite
d’expérimentations réalisées pour les voûtes plates du Louvre, selon de Maillet (2012).
Un dessin amélioré sans les trous pyramidaux à l’extrados est inventé la même année
par Sébastien Truchet. Bélidor mentionne l’invention d’Abeille mais ne décrit pas sa
géométrie (Bélidor, 1729, Livre II p. 61, cit. 28). Les inventions d’Abeille et de Truchet
ne seront publiées qu’en 1735 par Gallon, avec les planches correspondantes (Gallon,
1735).

Selon Díaz et Mozo (2012), aucune voûte d’Abeille n’a été construite en France
jusqu’aux expériences dirigées par Joël Sakarovitch entre 2003 et 2006 aux Grands
ateliers de l’Isle d’Abeau. Ces auteurs ajoutent que deux voûtes d’Abeille ont été
construites en Espagne : à la Cathédrale de Lugo en 1769, et à la Casa de Mina de
Limpia à Ponton de la Oliva en 1853.

Paramétrisation

Nous reprenons ici la paramétrisation des voûtes d’Abeille présentée par Brocato
et Mondardini (2014).
Les claveaux des voûtes d’Abeille sont des polyèdres tous identiques (voir ﬁg 3e
sur ﬁg. 10.12). Les coupes suivant les axes principaux d’un claveau sont des trapèzes
isocèles, déﬁnis par cinq longueurs a, b, c, d et h (ﬁg. 10.13). Ces longueurs sont reliées
par les égalités suivantes :

d = a −h tan ϕ, c = b + h tan ϕ (10.1)

La géométrie d’un claveau est donc complètement déﬁnie par seulement quatre paramètres. Nous prendrons dans la suite les paramètres a, b, h et ϕ. Les paramètres c
et d seront déduits des précédents.

196

<!-- p. 198 -->

Chapitre 10. Voûtes plates

Fig 10.12 – Voûte d’Abeille, d’après Gallon (1735)

La distance entre les centres de gravité de deux claveaux en contact est
p = a + b = c + d dans les deux directions orthogonales principales de la voûte.

z

2b 2a 2b
φ φ φ
2a

h h h
y

2c 2d

2d
x
2c

Fig 10.13 – Paramétrisation de la voûte d’Abeille, d’après Brocato et Mondardini
(2014)

Typologie

La voûte d’Abeille décrite par écrit par Gallon en 1735 correspond au paramétrage
suivant :
3 1
d = c, h = 4c, a −d = 3h (10.2)

197

<!-- p. 199 -->

Chapitre 10. Voûtes plates

Gallon souligne que ces proportions ne sont pas les mêmes que celles des ﬁgures de la
planche qui illustre son texte (7). Les proportions décrites dans le texte correspondent
à un angle ϕ des joints avec la verticale tel que tan ϕ = 1/3 (ϕ ≈18.4◦). Cet angle
est plus faible que celui lié à la règle du triangle équilatéral (ϕ=30◦), lui même plus
faible que l’angle ﬁgurant sur les dessins de Gallon (ϕ=45◦). L’angle prescrit dans le
texte correspond à la règle du « 1 pour 3 » que nous avons présenté dans le chapitre 6
concernant la typologie des plates-bandes.
Les voûtes d’Abeille seront présentées également par Frézier (1738, voir ﬁg. 6.23),
puis dans l’article « voûte » de l’encyclopédie de Diderot et d’Alembert (1765b, cit. 51,
voir ﬁg. 10.7).
À Ponton de la Oliva (Espagne), la voûte construite en 1853 présente des portées
(mesurées à l’intrados) de 3,10 × 3,80 m. L’épaisseur vaut h = 0,21 m, ce qui donne
un rapport portée sur hauteur L/h compris entre 15 et 18 (Díaz et Mozo, 2012).
Trois voûtes plates d’Abeille expérimentales ont été construites et chargées jusqu’à
la rupture en 2006 aux Grands ateliers de l’Isle d’Abeau sous la direction de Joël Sakarovitch. La portée des voûtes valait 2,52 × 2,52 m et 1,26 × 1,26 m. Le rapport L/h
était proche de 14 pour les trois voûtes, et l’angle ϕ des joints valait 30◦ou 45◦. Les
géométries des voûtes expérimentales seront décrites en détail dans l’annexe E.

10.4 Voûtes très surbaissées

10.4.1 Confusion des termes

Le rapport entre la ﬂèche f et la portée Li d’une voûte en berceau est f/Li = 1/2.
Si ce rapport, que nous nommerons simplement ﬂèche dans la suite par simplicité,
est inférieur à 1/2, la voûte est dite surbaissée.
Comme indiqué précédemment lors de la déﬁnition des voûtes plates, les voûtes
surbaissées ne sont pas à proprement parler des voûtes plates. La confusion des termes
existe dans le cours de J.-F. Blondel qui parle ainsi des voûtes surbaissées ou segmentaires en brique : « On les appelle Voûtes plates, parce qu’elles sont surbaissées au
point d’imiter les plafonds, sans exiger néanmoins pour cela des murs plus épais que
de coutume » (Blondel et Patte, 1777b, p. 84). Cette confusion est également présente
dans l’histoire de Paris de Sauval (8) qui désigne les voûtes des arcades de la place
Royale (actuelle place des Vosges) comme une « voûte surbaissée ou plate » (Sauval, 1724b, p. 626, cit. 14). L’observation sur place des voûtes actuelles montre que
les voûtes en brique (ﬁg. 10.14) sont beaucoup moins nombreuses que les voûtes en
plâtre sur ossature bois (9) (ﬁg. 10.15), et que de façon générale les voûtes surbaissées
sont construites sur ossature bois et ne correspondent pas à des voûtes maçonnées.

(7). Cette discordance entre les proportions du texte et des ﬁgures est également relevée par Frézier
(1738, p. 72, cit. 42).
(8). Sauval utilise également le terme de « voûte plate » pour la chapelle de la paroisse de SaintGermain-L’Auxerrois (Sauval, 1724b, p. 303), et pour l’escalier de l’hôtel de Jears (Sauval, 1724a,
p. 204).
(9). Le faux-appareil est soigné, avec pour certaines voûtes en plâtre un trompe l’œil en relief pour
donner l’impression d’une construction en brique. L’observation de la direction des ﬁssures (traversant
ou non les briques et les pierres, suivant ou non l’orientation des joints) permet de faire la distinction
entre les deux types de voûtes.

198

<!-- p. 200 -->

Chapitre 10. Voûtes plates

Fig 10.14 – Place des Vosges, voûtes en Fig 10.15 – Place des Vosges, voûtes en
brique des arcades des pavillons de la plâtre sur ossature bois, à faux appareil ;
Reine (nord de la place) Pavillons à l’ouest de la place

Pour préciser l’ampleur du surbaissement, nous retenons la terminologie de Delbecq (1982, p. 38) qui distingue suivant le rapport σ = f/Li ﬂèche sur portée :
— les voûtes peu surbaissées, où √1 ≤σ ≤1 ; 2 3 2
— les voûtes assez surbaissées, où 1 ≤σ ≤ √1 ≈ 1 ; 7 2 3 3,5
— les voûtes très surbaissées, où σ ≤17.
Delbecq précise que cette classiﬁcation est couramment utilisée pour les ponts.
Gauthey (1843) utilise les expressions « arche en anse-de-panier surbaissée au tiers »
ou « au quart », suivant que le rapport f/Li ﬂèche sur portée vaut respectivement
trois ou quatre environ (10).

Selon Pérouse de Montclos (1982, p. 116), « C’est sans doute au pont de Toulouse (voûté à partir de 1614) que pour la première fois dans l’architecture française
l’anse de panier remplace le plein-cintre traditionnel » . De nombreux traits de voûtes
surbaissées sont déjà donnés par Derand en 1643 : voûte d’arête surbaissée et voûte
en arc-de-cloître surbaissée sur diﬀérents plans (triangle, rectangle, hexagone), voûte
sphérique surbaissée.

Les voûtes peu surbaissées sont innombrables ; les voûtes très surbaissées, c’està-dire dont la ﬂèche est inférieure à 1/7 environ (11) sont plus rares.

10.4.2 Voûtes surbaissées en pierre de taille

La plus connue des voûtes très surbaissées en pierre de taille construite en France
est celle de la voûte de l’hôtel de ville d’Arles en raison de ses dimensions (15 × 15 m),
de sa faible ﬂèche (1/9) et de la science de son tracé. Elle fut construite sur les plans

(10). Nous n’avons pas trouvé la déﬁnition des expressions « arche en anse-de-panier surbaissée au
tiers » ou « au quart » dans l’ouvrage de Gauthey (1843). La confrontation de l’utilisation de ces
expressions avec les dessins des ponts fournis sur les planches de cet ouvrage donne cependant la
correspondance indiquée ici entre le rapport f/Li ﬂèche sur portée et les expressions.
(11). Notons que cette limite a un caractère arbitraire, et que la ﬂèche est rarement indiquée dans les
sources des exemples que nous donnons. Il s’agit donc d’un jugement subjectif de notre part, orienté
par le fait que ces voûtes sont répertoriées comme des « voûtes plates ».

199

<!-- p. 201 -->

Chapitre 10. Voûtes plates

de Jules-Hardouin Mansart, et achevée après le départ de l’architecte, de 1673 à 1675
(Tamboréro, 2010).

De nombreux autres exemples de voûtes très surbaissées et voûtes déprimées
peuvent être trouvés en recherchant « voûte plate » sur la base Mémoire de la Médiathèque d’Architecture et du Patrimoine :
— Villeneuve-lès-Avignon, église collégiale Notre-Dame, attribuée à Jean-
Baptiste Franque et Jean Barriol et construite en 1748 (Viré-Gaillard, 2011) :
voûte à arêtes doubles, à cinq quartiers ;
— Villeneuve-lès-Avignon, chapelle des Pénitents Gris, attribuée à Jean-Baptiste
Franque et construite de 1738 à 1753 (Viré-Gaillard, 2011) : voûtes à arêtes
doubles ;
— Carpentras, Hôtel-Dieu, construit entre 1750 et 1769, d’après le projet de l’ar-
chitecte Antoine d’Alleman, et réalisé sous la direction de Jean-Baptiste Lam-
bertin puis Jean-Pierre Teissier (Losserand, 2017b) : voûte à arêtes doubles
dans le vestibule d’entrée ;
— Avignon, hôtel Franque (ﬁg. 10.4) ;
— Bordeaux, palais Rohan (ancien hôtel de ville), construit de 1771 à 1778 sur les
plans de Joseph Étienne puis Richard-François Bonﬁn : voûte en berceau très
surbaissée et percée de lunettes, située dans la galerie. Le centre de la galerie
est marqué par une voûte de typologie diﬀérente : voûte à arêtes doubles très
surbaissée ;
— Barbentane, château, voûte déprimée dans la salle à manger. Une voûte dé-
primée mais dont la partie centrale occupe presque toute la pièce occupe le
salon. Nous avons classiﬁé cette seconde voûte dans le catalogue des voûtes
plates (voir ﬁg. B.152) ;
— Caen, abbaye aux Hommes, voûte surbaissée dans le vestibule du pavillon
central de l’aile Est. Fait partie d’un ensemble de bâtiments reconstruits à
partir de 1704 ;
— Avignon, Grand Séminaire Saint-Charles, voûte du chœur de la chapelle.
Construit par Jean-Baptiste Franque dans la première moitié du xviiie siècle.
Voir également ﬁg. B.153 ;
— Rodez, cathédrale, tribune du chanoine Philandrier, composée d’une voûte en
berceau segmentaire très surbaissée, avec un décors à entrelacs formant retom-
bée sous l’intrados, construite dans la seconde moitié du xvie siècle (Pérouse
de Montclos, 1982, p. 163, 310) ;
— La Rochelle, Palais de Justice, 1783-1789. Voûtes d’arêtes très surbaissées
(Pérouse de Montclos, 1982, p. 157).

10.4.3 Voûtes à la Roussillon, ou voûtes catalanes

Les voûtes à la Roussillon ont fait l’objet d’études historiques par Bannister
(1968), Pérouse de Montclos (1982, p. 194) et Araguas (1999). Ces voûtes assez surbaissées ou très surbaissées sont construites avec des briques pleines posées à plat ou
sur champ, hourdées au plâtre, en une ou plusieurs couches. La forme en berceau est
traditionnellement employée, mais peut être remplacée par une forme en arc-de-cloître
(voûte « à l’impériale », avec des exemples de ce type construits à Lyon, notamment à

200

<!-- p. 202 -->

Chapitre 10. Voûtes plates

l’Hôtel-Dieu). Aujourd’hui, ces voûtes sont également désignée sous le vocable voûte
catalane, voûte sarrasine et voûte à la Volterra.

Bien qu’il existe des exemples de ce type de voûte dans le Roussillon au Moyen
Âge, et en Catalogne avant le xviiie siècle, cette technique ne se diﬀuse dans le reste
de la France qu’à partir du xviiie siècle (Bannister, 1968). L’Académie royale d’architecture valide en 1755 le principe de ce système constructif « local » (du Roussillon),
mais en recommandant que les briques soient mises en place sur champ, et non à plat.

La typologie des diﬀérents types de voûtes est donnée par Blondel et Patte (1777b,
p. 98-104). Il y mentionne notamment :
— l’utilisation de tirants placés sur l’extrados lorsque la portée des voûtes est
importante ;
— les briques posées à plat en double épaisseur ;
— de petits raidisseurs construits sous forme de murets sur l’extrados dans les
reins de voûte.

Fig 10.16 – Voûte assez surbaissée en Fig 10.17 – Voûte très surbaissée en
brique, extrait de la planche LXXXXV brique, extrait de la planche LXXXXVII
du cours de Blondel et Patte (1777b) du cours de Blondel et Patte (1777b)

Bannister donne de nombreux exemples de voûtes construites ainsi au xviiie siècle,
notamment par Souﬄot et Contant d’Ivry (Bannister, 1968).

201

<!-- p. 203 -->

Troisième partie

Réseaux de forces pour les
constructions clavées

202

<!-- p. 204 -->

Chapitre 11

Motivation et enjeux

Résumé : Ce chapitre présente les raisons pour lesquelles une extension de la méthode des réseaux de forces nous a semblée nécessaire. Dans un premier temps, la similitude conceptuelle entre le réseau de forces et le polygone funiculaire est soulignée.
Les conséquences et limitations introduites par les deux hypothèses fondamentales,
nécessaires pour appliquer la méthode des réseaux des forces, sont ensuite exposées.
Enﬁn, le besoin d’une extension de la méthode est considéré du point de vue de la
coupe des pierres, et du calcul à la rupture.

Sommaire
11.1 Réseaux de forces et lignes de pression . . . . . . . . . . . . . . . 204
11.1.1 Extension du polygone funiculaire sous forme de réseau . 204
11.1.2 Réseau funiculaire . . . . . . . . . . . . . . . . . . . . . . 205
11.2 Hypothèse de l’intersection des forces . . . . . . . . . . . . . . . . 206
11.2.1 Rappels sur l’équilibre d’un bloc . . . . . . . . . . . . . . 206
11.2.2 L’intersection, condition non nécessaire . . . . . . . . . . . 207
11.2.3 Absence de conséquence en 2D . . . . . . . . . . . . . . . 207
11.2.4 Directions ﬁxes des forces projetées sur le plan horizontal 208
11.2.5 Conjugaison des directions du réseau . . . . . . . . . . . . 208
11.3 Verticalité des charges . . . . . . . . . . . . . . . . . . . . . . . . . 211
11.4 Besoins d’une extension de la méthode . . . . . . . . . . . . . . . 211
11.4.1 Pour la coupe des pierres . . . . . . . . . . . . . . . . . . . 211
11.4.2 Pour le calcul à la rupture . . . . . . . . . . . . . . . . . . 211

203

<!-- p. 205 -->

Chapitre 11. Motivation et enjeux

11.1 Réseaux de forces et lignes de pression

La proximité lexicale en anglais entre le réseau de forces (« thrust network ») et
la ligne de pression (« thrust line ») est trompeuse. Le réseau de forces est l’extension
sous forme de réseau du polygone funiculaire, et non celle de la ligne de pression.
Nous présentons dans cette section ces extensions.

11.1.1 Extension du polygone funiculaire sous forme de réseau

Revoyons pour commencer la déﬁnition du polygone funiculaire et celle de la ligne
de pression, qui ont été données dans l’état de l’art pour les constructions clavées.

Déﬁnition 3. Rappel de la déﬁnition vue dans l’état de l’art :
Un polygone funiculaire d’un arc clavé est un polygone dont les sommets sont les
points d’intersection des lignes d’action des forces en équilibre s’appliquant à chaque
claveau.

Déﬁnition 4. Rappel de la déﬁnition vue dans l’état de l’art :
Une ligne de pression d’un arc clavé est la suite des points d’application des résultantes des actions de contact (ou centres de pression) sur ses joints.

Les centres de pression étant donnés par les intersections des joints avec les lignes
d’action des résultantes des actions de contact, la ligne de pression est donc la suite
des intersections des joints avec les segments ou les prolongations des segments du
polygone funiculaire.

Par construction, les lignes d’action des résultantes des actions de contact sur les
joints passent par les branches du réseau de forces. Les nœuds du réseau de forces
sont les points d’intersections des branches, et donc des lignes d’action des forces.
Ainsi, le réseau de forces correspond exactement au concept de polygone funiculaire,
étendu sous forme de réseau.

A contrario, la ligne de pression ne peut pas être étendue en 3D sous la forme
d’un réseau. En eﬀet, en 2D la ligne de pression d’un système de blocs n’est pas
une courbe, mais une suite de points situés sur les plans passant par les joints des
blocs. L’extension de cette suite de points en 3D est un nuage de points, comprenant
l’ensemble des centres de pression (ﬁg. 11.1).

Il est courant en 2D de tracer un segment pour relier les points de la ligne de
pression, de manière à former une courbe. Cependant, en dehors des points d’application des forces sur les joints, les autres points de la courbe ainsi formée n’ont pas
de sens physique. Il n’est d’ailleurs pas possible de transformer le nuage de points
en 3D en un réseau : pour chaque bloc en contact sur quatre faces, il existe quatre
centres de pression, entre lesquels on peut tracer six segments distincts. Il faudrait
donc des hypothèses complémentaires pour déﬁnir un réseau correspondant à la ligne
de pression.

L’extension sous forme de réseau du polygone funiculaire a un caractère pratique,
plus qu’un caractère théorique. En eﬀet, la statique graphique présentée par Culmann
(1864) aborde déjà le cas des forces dans l’espace, et approfondi le cas des « forces
formant une gerbe » (Culmann, 1880), c’est-à-dire des forces qui passent en un même

204

<!-- p. 206 -->

Chapitre 11. Motivation et enjeux

point. Cependant la diﬃculté d’application de la statique graphique en 3D a conduit
les ingénieurs à utiliser cette dernière essentiellement en 2D, c’est-à-dire pour les systèmes de forces coplanaires. La méthode des réseaux de forces permet donc d’obtenir
des résultats déjà théoriquement accessibles grâce à la statique graphique, mais de
manière beaucoup plus commode.

Polygone funiculaire Ligne de pression

2D

⇓ ⇓ ⇓
Réseau de forces Nuage de points, centres de pression

3D

Fig 11.1 – Extensions 2D à 3D du polygone funiculaire et de la ligne de pression

11.1.2 Réseau funiculaire

O’Dwyer et Block utilisent tous les deux directement le réseau de forces pour
déterminer la stabilité des structures qu’ils étudient (O’Dwyer, 1999; Block, 2009).
Ils vériﬁent que le réseau de forces est inclus à l’intérieur de l’enveloppe déﬁnie par
l’intrados et l’extrados de la voûte, et non que les centres de pressions se trouvent à
l’intérieur des joints.

Leur approche est justiﬁée pour deux raisons. Premièrement, cette approche est
conservative. Pour les structures à géométrie régulière, si le réseau de forces est compris à l’intérieur de la maçonnerie, alors les centres de pression seront également à
l’intérieur de la maçonnerie. Une approche conservative, qui produit des structures

205

<!-- p. 207 -->

Chapitre 11. Motivation et enjeux

plus stables que le résultat calculé, ne pose pas de problème pour la création de
nouvelles structures.

Deuxièmement l’utilisation du réseau de forces est bien adaptée pour les processus d’optimisation mathématique qui permettent de trouver des solutions d’équilibre
adaptées. En eﬀet, la résolution numérique des problèmes d’optimisation est la difﬁculté principale pour l’utilisation pratique de la méthode des réseaux de forces.
L’utilisation des centres de pression conduit à des diﬃcultés supplémentaires pour
la résolution numérique. Le gain en précision obtenu en considérant les joints est la
plupart du temps faible par rapport à la complexité plus grande de l’optimisation
que cela entraîne. L’imprécision de l’utilisation des réseaux de forces par rapport à
celles des centres de pression est brièvement envisagée dans la conclusion de la thèse
de Block (2009).

L’utilisation des réseaux de forces sans considération des centres de pression sur
les joints semble s’être imposée pour la recherche de nouvelles formes en compression. Cependant, dans le cadre de l’étude des structures existantes, ou des structures
présentant une stéréotomie particulière, la considération des centres de pression est
essentielle pour obtenir des résultats exploitables dans le cadre du calcul à la rupture.

Dans l’ensemble de ce document, le réseau de forces et les centres de pression
seront toujours dessinés conjointement. La diﬀérence entre les deux sera alors visible
par la distance existante entre les réseaux et les nuages de points. Cette diﬀérence
est conséquente dans certains cas (poussée minimale d’un arc, ﬁg. 1.2 p. 25 ; voûtes
d’Abeille, ﬁg. 16.18 p. 293), et négligeable dans d’autres cas (poussée maximale d’un
arc ﬁg. 1.2 p. 25).

Pour conclure, en anglais le terme « pressure network » ou « force network » semble
plus correct pour désigner le réseau de forces, plutôt que « thrust network ». En
français, le terme réseau funiculaire pourrait être utilisé parallèlement à l’appellation
classique du réseau de forces.

11.2 Hypothèse de l’intersection des forces

11.2.1 Rappels sur l’équilibre d’un bloc

Considérons un polyèdre, en contact sur n faces. Le polyèdre est soumis à n + 1
systèmes de forces : n systèmes de forces s’appliquant sur les joints et le chargement
correspondant à la gravité. Chacun de ces systèmes de forces peut être représenté par
une force unique agissant le long d’une ligne d’action.

Une solution d’équilibre pour ce polyèdre est un ensemble de forces tel que la
somme des forces et des moments appliqués au polyèdre est nulle. Si l’équilibre des
forces est assuré, alors le fait que les lignes d’actions s’intersectent en un point est
une condition suﬃsante pour assurer l’équilibre des moments (1).

Considérons un exemple simple sans faire intervenir les réseaux de forces pour le
moment : un bloc unique soumis à quatre forces sur ses faces latérales, et à son poids
propre. Quatre solutions d’équilibre diﬀérentes sont données sur la ﬁgure 11.2. Seule

(1). Démonstration : le moment de chaque force par rapport à ce point d’intersection est nulle, et
la somme des moments est donc également nulle.

206

<!-- p. 208 -->

Chapitre 11. Motivation et enjeux

la solution (a) sur cette ﬁgure a pour propriété que l’ensemble des lignes d’actions des
forces s’intersectent en un point. Dans les solutions d’équilibre (b) (c) et (d), où les
conditions d’équilibre des forces et des moments sont satisfaites, les lignes d’actions
des forces ne s’intersectent pas en un point.

Cet exemple introductif illustre le fait que l’intersection des forces en un point est
une condition suﬃsante, mais non nécessaire pour assurer l’équilibre des moments.

vues isométrique

vues de face

vues de dessus

a b c d

Fig 11.2 – Cas d’équilibres avec ou sans intersection des forces en un point

11.2.2 L’intersection, condition non nécessaire

La première hypothèse nécessaire à la mise en place de la méthode des réseaux de
forces est celle de l’intersection des lignes d’actions des forces en un point (section 4.3.2
p. 62). Comme nous venons de le voir, cette condition est suﬃsante pour assurer
l’équilibre des moments, mais elle n’est pas nécessaire (au sens mathématique du
terme).

L’hypothèse de l’intersection des forces en un point est donc une hypothèse simpliﬁcatrice qui réduit l’espace des solutions d’équilibre qui peuvent être explorées avec
les réseaux de forces. Cette hypothèse simpliﬁcatrice est néanmoins fondamentale
pour la méthode car elle se trouve à la base de la déﬁnition des réseaux : en l’absence
d’intersection les réseaux de forces ne peuvent être déﬁnis. Elle est importante d’une
part pour la faisabilité de la méthode, et d’autre part pour les limitations qu’elle
implique pour les résultats obtenus.

Les conséquences de l’hypothèse d’intersection des forces varient suivant les systèmes de blocs étudiés, et sont présentées maintenant.

11.2.3 Absence de conséquence en 2D

Pour une structure plane ou étudiée en 2D, le réseau de forces est le polygone
funiculaire de la statique graphique. La condition d’intersection des forces est une

207

<!-- p. 209 -->

Chapitre 11. Motivation et enjeux

condition nécessaire et suﬃsante d’équilibre, car chaque sommet est le point de rencontre de trois forces en équilibre. L’hypothèse d’intersection des forces ne réduit pas
le domaine des solutions d’équilibre qui peuvent être étudiées (ﬁg. 11.4 cas C).

11.2.4 Directions ﬁxes des forces projetées sur le plan horizontal

Les directions des branches projetées sur le plan horizontal sont données par
la projection des centres de gravité des blocs sur le plan horizontal. Comme ces
derniers sont ﬁxes, les directions des branches projetées sur le plan horizontal, et
donc les directions des lignes d’actions des forces projetées sur le plan horizontal,
sont également ﬁxes.

Cela a plusieurs conséquences.

Premièrement, l’angle d’incidence de la composante horizontale des forces sur les
joints est ﬁxe. Le réseau de forces d’une voûte d’Abeille ne peut donc pas faire intervenir d’eﬀorts de cisaillement dans le plan horizontal, car la ligne d’action de la force
est située dans un plan vertical perpendiculaire au joint (2). Brocato et Mondardini
(2014) ont mis en évidence des solutions d’équilibre pour les voûtes d’Abeille à l’aide
de la méthode des éléments ﬁnis (3), en tenant compte du clavage particulier de ces
voûtes plates. Les solutions d’équilibre trouvées mettent en jeu des eﬀorts de cisaillement importants dans le plan horizontal entre les diﬀérents voussoirs, en raison des
conditions d’appuis de la voûte (diﬀérentes de celles qui seront étudiées dans le cadre
de cette thèse). Ces eﬀorts de cisaillement se traduisent par un angle d’incidence
diﬀérent de 90◦, qui ne peut pas être reproduit avec les réseaux de forces.

Deuxièmement, il existe des cas géométriques où la branche passe nécessairement
en dehors du joint, car la projection horizontale du joint n’est pas coupée par la
projection de la branche. Ce cas se produit lorsque le rayon de courbure est faible
par rapport à la taille des blocs, nous donnerons un exemple dans le cas d’un escalier
hélicoïdal formé de blocs allongés (ﬁg. 13.6). Il n’existe alors pas de réseau de forces
représentant une solution d’équilibre dont les centres de pression sont tous situés à
l’intérieur des joints.

11.2.5 Conjugaison des directions du réseau

Le transfert d’une force verticale dans une branche du réseau implique que la force
horizontale dans la branche ne soit pas nulle. L’amplitude de l’eﬀort vertical pour un
eﬀort horizontal constant dépendra de l’altitude des nœuds du réseau. Le transfert
des forces horizontales et des forces verticales n’est donc pas dissocié.

Cela implique une conjugaison des branches du réseau qui transfèrent nécessairement des eﬀorts verticaux dès lors qu’il existe des eﬀorts horizontaux dans les
branches. Des arcs parallèles ne peuvent pas se comporter de façon indépendante les
uns des autres si des branches orthogonales avec des forces horizontales non nulles les
relient.

(2). La ligne d’action est plus exactement perpendiculaire à l’intersection du joint avec le plan
horizontal passant par le centre de pression.
(3). Éléments ﬁnis volumiques pour les blocs avec loi de comportement élastique, et éléments ﬁnis
de type joint dilatant avec un critère de Mohr-Coulomb et écoulement associé entre les blocs.

208

<!-- p. 210 -->

Chapitre 11. Motivation et enjeux

Cette conjugaison des directions du réseau s’illustre sur les exemples suivants.

Plate-bande Considérons une voûte plate sur plan carré, en appui sur ses quatre
côtés, et chargée uniformément. Il est possible de construire une solution d’équilibre
simple, en considérant la voûte plate comme la superposition de deux plates-bandes
perpendiculaires qui portent chacune la moitié du chargement. Cependant, ce cas
d’équilibre impliquant la non unicité de l’intersection des forces s’appliquant à chaque
claveau ne peut pas être reproduit avec un réseau de forces. Nous verrons qu’il faut introduire un raﬃnement du réseau (les branches partielles) pour permettre la création
de réseaux représentant ce cas d’équilibre simple (section 16.3 p. 285).

L’analogie entre la voûte plate et les plates-bandes provient d’une remarque de
Frézier sur les voûtes plates d’Abeille. Cette analogie et ses limites seront étudiées en
détail dans la section 16.3 consacrée à l’étude des voûtes plates et de l’inﬂuence de
leur coupe des pierres.

Voûte hélicoïdale L’étude des voûtes hélicoïdales illustre également la conjugaison
des directions du réseau. Voir section 17.1 p. 299.

Voûte d’Abeille Il existe des polyèdres pour lesquels il n’existe pas de solution
d’équilibre (ﬁg. 11.4 cas B). Par exemple, considérons le cas des voussoirs de la voûte
d’Abeille, avec comme critère de stabilité la compression seule sur les faces, et un critère de glissement (ﬁg. 11.3). Si le voussoir est suﬃsamment long et ses faces latérales
suﬃsamment inclinées, il n’est plus possible d’obtenir d’intersection.

Fig 11.3 – Voussoirs d’une voûte d’Abeille

209

<!-- p. 211 -->

Chapitre 11. Motivation et enjeux

Cas A – Des solutions stables avec intersection des
forces en un point existent

Solutions d’équilibre

Solutions d’équilibre stables

Solutions d’équilibre avec intersection des forces
en un point

Solutions d’équilibre stables avec intersection
des forces en un point

Cas B – Aucune solution stable avec intersection des
forces en un point

exemple : étude réseau de forces (sans raﬃnement ré-
seau) d’une voûte plate d’Abeille avec angle de frotte-
ment limite faible

Cas C – Toute solution stable présente la propriété
d’intersection des forces en un point

exemple : étude 2D d’un arc

Fig 11.4 – Domaines des solutions d’équilibre ; intersections possibles des solutions
d’équilibre stables, avec ou sans la propriété d’intersection des forces en un point

210

<!-- p. 212 -->

Chapitre 11. Motivation et enjeux

11.3 Verticalité des charges

La deuxième hypothèse nécessaire à la mise en place de la méthode des réseaux de
forces est celle de la verticalité des charges s’appliquant sur les nœuds (section 4.3.2
p. 62).

Cette hypothèse n’est pas nécessaire pour la méthode des densités de forces, mais
elle est essentielle pour la méthode des réseaux de forces. Block (2009) indique que des
charges horizontales complémentaires peuvent être ajoutées au système, en ajoutant
des branches complémentaires dans le réseau pour implémenter ces charges horizontales. Cependant, en raison de la première hypothèse d’intersection des forces, cela
induit que la hauteur du point d’application des forces horizontales du chargement
extérieur dépend de la solution d’équilibre en cours de considération. Il s’agit donc de
charges suiveuses. Étant donné que nous considérerons des solutions d’équilibre dans
lesquelles les nœuds ne sont pas compris à l’intérieur de la maçonnerie, l’utilisation
de charges horizontales de ce type est problématique.

Nous n’utilisons pas dans cette thèse de charges horizontales additionnelles pour
cette raison.

11.4 Besoins d’une extension de la méthode

11.4.1 Pour la coupe des pierres

L’histoire des plates-bandes dans l’architecture française que nous avons ébauchée
dans la partie II montre l’attention apportée par les architectes et les tailleurs de
pierre à la question de l’inclinaison à donner aux joints des plates-bandes. L’étude
de l’inﬂuence des diﬀérentes coupes des pierres sur le comportement mécanique des
plates-bandes suppose de pouvoir prendre en considération la géométrie des joints.

Bien que représentant les forces passant à travers les joints, les réseaux de forces
n’intègrent pas l’information de la géométrie des joints. Ce dernier point nécessite
donc une extension de la méthode des réseaux de forces.

De plus, dans le cas de structures clavés particulières, comme par exemple les
voûtes d’Abeille, les réseaux de forces ne peuvent pas fournir de solutions d’équilibre
admissibles du point de vue du critère de Mohr-Coulomb en raison de l’orientation des
joints. Il existe donc un intérêt à pouvoir étendre les solutions d’équilibre accessible.

11.4.2 Pour le calcul à la rupture

Les solutions d’équilibre produites par la méthode des réseaux de forces peuvent
être utilisées pour étudier la stabilité des structures clavées dans le cadre du calcul
à la rupture. L’application rigoureuse des théorèmes du calcul à la rupture nécessite
d’introduire les critères de résistances des joints et les multiplicateurs de rupture
présentés dans la partie I consacrée à l’état de l’art.

Comme dans le cas de l’inﬂuence de la coupe des pierres, l’intégration des réseaux
de forces au cadre du calcul à la rupture nécessite donc l’expression des résultats au
niveau des joints, et par conséquent la considération de la géométrie de ces derniers.

211

<!-- p. 213 -->

Chapitre 12

Extension des réseaux de forces

Résumé : Ce chapitre expose les principes de l’extension de la méthode des réseaux
de forces. Dans un premier temps, la simpliﬁcation de l’appareil pour permettre la
paramétrisation des géométries étudiées est décrite. La considération de la géométrie
des joints, et donc de l’appareil, puis des critères de résistance exprimés au niveau des
joints, points essentiels pour l’intégration de la méthode des réseaux de forces au cadre
du calcul à la rupture sont ensuite exposés. Les branches partielles additionnelles,
qui constituent un raﬃnement du réseau pour permettre l’exploration de nouvelles
solutions d’équilibre sont introduites. Enﬁn, diﬀérentes stratégies de détermination
des chargements extrêmes déﬁnissant les domaines de chargements potentiellement
supportables sont proposées.

Sommaire
12.1 Extension de la méthode des réseaux de forces . . . . . . . . . . . 213
12.2 Simpliﬁcation de l’appareil et paramétrisation de la géométrie . . 213
12.3 Considération des joints . . . . . . . . . . . . . . . . . . . . . . . . 214
12.4 Critères de résistance des joints . . . . . . . . . . . . . . . . . . . 215
12.5 Branches partielles additionnelles . . . . . . . . . . . . . . . . . . 215
12.6 Recherche des chargements extrêmes . . . . . . . . . . . . . . . . . 217
12.6.1 Recherche par optimisation sous contraintes . . . . . . . . 217
12.6.2 Stratégies de résolution . . . . . . . . . . . . . . . . . . . . 218

212

<!-- p. 214 -->

Chapitre 12. Extension des réseaux de forces

12.1 Extension de la méthode des réseaux de forces

L’extension de la méthode des réseaux de forces proposée dans cette thèse permet
d’étudier la stabilité d’une structure clavée à partir de son domaine des chargements
potentiellement supportables, calculé rigoureusement dans le cadre du calcul à la
rupture.
Le diagramme de la méthode étendue est donné sur la ﬁgure 12.1. Les diﬀérents
points nécessaires à l’extension sont exposés successivement dans ce chapitre.

Fig 12.1 – Diagramme de la méthode des réseaux funiculaires

12.2 Simpliﬁcation de l’appareil et paramétrisation de la
géométrie

Les voûtes en pierre de taille ne présentent généralement pas un appareil suﬃsamment régulier pour permettre de décrire de façon paramétrique simple la géométrie
de l’intrados, de l’extrados et des joints.
La simpliﬁcation de l’appareil consiste à insérer des joints ﬁctifs complémentaires
par rapport aux joints existants, et éventuellement à modiﬁer légèrement la position de ces derniers, tout en respectant les principes de coupe des pierres guidant
l’orientation des joints, de manière à pouvoir décrire de manière paramétrique simple
l’ensemble de la géométrie.
Cette procédure est décrite sur le cas particulier des voûtes plates, soit appareillées
sur le plan de la voûte en berceau, soit appareillées sur le plan de la voûte en arc-decloître, dans le chapitre consacré à l’étude mécanique de ces structures (section 16.1,

213

<!-- p. 215 -->

Chapitre 12. Extension des réseaux de forces

ﬁg. 16.4 et ﬁg. 16.5). Par ailleurs, deux cas possibles d’appareils paramétriques sont
donnés sur la ﬁgure 12.2 dans le cas d’un dôme.

Parallèlement, la géométrie curviligne des claveaux est simpliﬁée sous la forme
de polyèdres, c’est-à-dire de solides dont les faces sont des polygones plans. Cette
seconde simpliﬁcation vise à ne traiter que des joints sous la forme de polygone
plans, ou d’assemblages de polygones plans.

Fig 12.2 – Dôme avec oculus – exemples de deux appareils paramétriques

La création des modèles géométriques étudiés dans cette thèse repose sur la possibilité de trouver un paramétrage permettant de décrire la géométrie de la voûte
et de ses joints. Si cela n’est pas possible, il faut alors importer manuellement ou à
l’aide d’un logiciel externe la géométrie (1). Nous n’abordons pas de cas de ce type
dans cette thèse.

12.3 Considération des joints

L’utilisation des critères de résistances sur les joints dans le cadre du calcul à la
rupture nécessite de connaître une expression des eﬀorts s’appliquant sur les joints.
Cette expression peut prendre la forme d’un champ de contrainte, des eﬀorts généralisés, ou encore de la résultante des actions de contact. Nous nous plaçons dans
ce dernier cas ici. La position des résultantes des actions de contact sur les joints
(les centres de pression), et la décomposition des forces résultantes dans les repères
locaux des joints doivent donc être connus.

Un centre de pression peut se trouver en n’importe quel point à l’intérieur du
polygone formant le joint (2). Cependant, l’hypothèse de l’intersection des forces en
un point a pour conséquence de réduire les positions possibles des centres de pression
d’une surface à un segment, ce que nous détaillerons ultérieurement.

Le calcul de la position du centre de pression met en jeu l’intersection d’une droite
(la ligne d’action de la résultante des actions de contact du joint) avec le plan du polygone déﬁnissant le joint. Il est possible de remplacer le polygone du joint (joint 3D)
par d’une part un segment (joint 2D), et d’autre part les caractéristiques géométriques
du polygone (aire, modules statiques, hauteur, largeur). Cette substitution ne modiﬁe
pas les résultats obtenus : centre de pression, et décomposition de cette dernière dans

(1). La géométrie signiﬁe ici seulement la position des centres de gravité des blocs, leur masse et
les joints réduits 2D déﬁnis dans la suite.
(2). Un centre de pression peut également se trouver en dehors de l’intérieur du polygone formant
le joint, s’il se trouve à l’intérieur de son enveloppe convexe. Cette propriété n’est pas exploitée dans
cette thèse.

214

<!-- p. 216 -->

Chapitre 12. Extension des réseaux de forces

le repère local du joint. Elle a deux avantages. Le premier est d’accélérer les calculs en
substituant l’intersection d’une droite avec un plan par l’intersection de deux droites,
et la seconde est de réduire la taille de l’information à stocker concernant chaque
joint.

L’implémentation et la justiﬁcation géométrique de cette démarche sera présentée
en détail dans le chapitre suivant (section 13.2 p. 223).

12.4 Critères de résistance des joints

Une fois la prise en compte des joints réalisées (section précédente), et l’expression
des forces dans le repère local des joints connues, le calcul du multiplicateur de charge
lié au critère de résistance considéré découle directement des expressions rappelées
dans l’état de l’art (section 3.1.1 p. 41).

Les critères de résistances utilisés sont formulés uniquement au niveau des joints,
la résistance interne de la pierre étant donc considérée implicitement inﬁnie. En eﬀet
bien que la résistance du joint (interface mortier-pierre, ou interface pierre-pierre)
fasse intervenir la résistance de la pierre, la résistance de la pierre à l’intérieur des
blocs n’est pas considérée.

Le fait de ne pas considérer la résistance interne des blocs se traduit par une
surestimation de la résistance des blocs notamment lorsque les blocs présentent des
angles aigus (p. ex. inﬂuence de l’inclinaison des joints sur la stabilité des platesbandes, section 15.3.3).

12.5 Branches partielles additionnelles

Le réseau de forces est basé sur l’hypothèse que les lignes d’actions des forces
appliquées à chaque bloc s’intersectent en un point. Ce point est un nœud du réseau
de forces. Cette hypothèse est suﬃsante mais non nécessaire pour assurer l’équilibre
du moment, et diminue l’ensemble des solutions d’équilibre qui peuvent être produites
avec la méthode (voir section 11.2).

L’utilisation de branches partielles additionnelles, qui reposent sur un redécoupage
de chaque bloc en deux sous-blocs, et donc sur un raﬃnage du réseau, permet de
contourner partiellement cette limitation inhérente à la méthode, et ainsi d’avoir
accès à de nouvelles solutions d’équilibre. En eﬀet, la condition d’intersection est
toujours respectée pour chaque nœud, mais comme il y a plus d’un nœud par bloc,
les droites d’actions des forces qui s’appliquent à un bloc ne sont plus nécessairement
concourantes. Ce raﬃnement du réseau permet de considérer des cas d’équilibres
similaires au cas (b) de la ﬁgure 11.2 p. 207, en plus du cas (a) classique. Cependant
les cas (c) et (d) de cette même ﬁgure restent hors de portée de l’extension des réseaux
de forces présentée ici.

Les branches partielles additionnelles peuvent être utilisées seulement pour certaines typologies. Elles peuvent être appliquées aux réseaux de nœuds à quatre
branches, avec les branches perpendiculaires deux à deux en projection sur le plan horizontal. Elles ne peuvent pas être appliquées aux réseaux de nœuds à trois branches

215

<!-- p. 217 -->

Chapitre 12. Extension des réseaux de forces

parce que la résolution de l’équilibre horizontal après le raﬃnement ne serait plus
possible.

Le raﬃnement du réseau suit le principe suivant. Dans la méthode des réseaux
de forces traditionnelle, un seul nœud est créé pour chaque bloc B. Il est localisé
au centre de gravité du bloc dans le réseau de masse. Nous divisons chaque bloc en
deux sous-blocs b1 et b2, correspondant également à deux nouveaux nœuds dans le
réseau de masse, avec leur masse respective. Ces nœuds sont joints par une nouvelle
branche, que nous appelons branche partielle additionnelle. Cette branche correspond
à des forces intérieures au bloc B. Les branches qui reliaient le bloc B à ses blocs
voisins doivent ensuite être raccordées à l’un ou l’autre des nœuds créés pour les
sous-blocs b1 et b2.
Ce processus correspond à un raﬃnement du réseau de forces, qui contient à la ﬁn
du processus plus de nœuds et de branches que le réseau initial, bien que le nombre
de blocs réels et de joints n’ait pas été modiﬁés.

La ﬁgure 12.3 illustre le cas de sous-blocs dont les centres de gravité sont situés
sur une verticale, obtenus par la division d’un bloc par un plan horizontal.

Plan frontal

L.T L.T

Plan horizontal

Fig 12.3 – Nœud à quatre branches avant (à gauche) et après (à droite) le
raﬃnement du réseau

La ﬁgure 12.4 illustre le cas de sous-blocs dont les centres de gravité ne sont pas
situés sur une verticale, obtenu par la division de deux blocs d’un arc par des plans
verticaux par exemple. Ce procédé sera utilisé pour l’étude des plates-bandes à joints
en X.

Plan frontal

L.T L.T

Plan horizontal

Fig 12.4 – Arc avant (à gauche) et après (à droite) le raﬃnement du réseau

Il peut être utile pour des raisons de clarté des ﬁgures de choisir un décalage
vertical arbitraire entre les deux nœuds pour pouvoir les distinguer visuellement. Ce
décalage vertical n’a pas d’eﬀet sur l’équilibre puisque le chargement est vertical.

216

<!-- p. 218 -->

Chapitre 12. Extension des réseaux de forces

12.6 Recherche des chargements extrêmes

12.6.1 Recherche par optimisation sous contraintes

L’état de contrainte réel d’une structure ne peut être déterminé sans introduire des
informations complémentaires (loi de comportement, historique du chargement). Dans
le cadre du calcul à la rupture, la recherche de l’état de contrainte réel est abandonnée
au proﬁt de la recherche des chargements extrêmes constituant la frontière du domaine
des chargements supportables.

La construction par l’intérieur du domaine des chargements potentiellement supportables met en jeu la considération successives de diﬀérents chargements Q, pour
lesquels on cherche le chargement extrême F(Q)Q sur un trajet de chargement radial.
Les deux formulations équivalentes établies dans le cadre général du calcul à la rupture (équation 2.16), puis dans le cas particulier des structures clavées (équation 3.14)
sont rappelées ci-dessous :

F(Q) = max λ (12.1)
λ/λQ∈K

F(Q) = max λJ (ζ) = max min λj(ζ) (12.2)
ζ ζ j∈J

Pour chaque chargement Q considéré, la recherche du chargement extrême F(Q)Q
nécessite de résoudre un problème d’optimisation sous contraintes : la maximisation
d’une fonction de coût f dépendant d’un vecteur de paramètres ζ, tout en respectant
une ou plusieurs contraintes (au sens mathématique du terme) c1, c2 etc.

max f(ζ) (12.3)
ζ,c1>0,c2>0

La fonction f à maximiser ici est :

f(ζ) = min λj(ζ) (12.4)
j∈J

Cette fonction remplace la fonction quadratique faisant intervenir directement la
position de tous les nœuds habituellement utilisée dans le cadre de la méthode des
réseaux de forces (qui est minimisée au lieu d’être maximisée) :

g(ζ) = X(zi(ζ)2 −z2G) (12.5)

La fonction f, bien qu’elle soit classique dans le cadre du calcul à la rupture
appliqué aux structures clavées (p. ex. Delbecq, 1983), n’avait pas été considérée
jusqu’à maintenant dans les implémentations des réseaux de forces (O’Dwyer, 1999 ;
Block, 2009 ; Marmo et Rosati, 2017).

Le problème d’optimisation pour la recherche des chargements extrêmes ne correspond pas à un problème d’optimisation de forme. Dans notre cas, la géométrie du
problème est ﬁxe, et le problème d’optimisation vise à trouver la solution d’équilibre
correspondant à la fonction de coût (le multiplicateur de rupture) le plus élevé. Dans
le cas de l’optimisation de forme, la géométrie de la structure étudiée fait partie des
paramètres du problème d’optimisation.

217

<!-- p. 219 -->

Chapitre 12. Extension des réseaux de forces

12.6.2 Stratégies de résolution

Les algorithmes d’optimisation n’ont pas été étudiés dans le cadre de cette thèse.
Nous avons focalisé notre attention sur la formulation du problème d’optimisation,
pour que ce dernier puisse être rapidement (3) résolu par un algorithme utilisant la
méthode du gradient réduit généralisé (« Generalized Reduced Gradient »).

Pour permettre l’extension de la méthode des réseaux de forces et y intégrer la
considération des joints, nous avons substitué à la fonction (g) présentant un optimum
global, une fonction (f) présentant de multiples optimums locaux. Cela introduit des
diﬃcultés numériques pour obtenir rapidement la solution du problème d’optimisation
permettant de trouver le chargement extrême.

De plus la recherche du domaine des chargements potentiellement stables nécessite
la résolution répétée du problème d’optimisation pour chaque chargement Q pour
construire point par point la frontière du domaine des chargements supportables.

Enﬁn, l’introduction des forces partielles augmente le nombre de paramètres ζ
dont dépend l’équilibre. Le nombre de paramètres supplémentaires est égal au nombre
de nœuds intérieurs, ce qui conduit à la multiplication par 2 ou 3 du nombre de
paramètres dans les cas que nous étudions.

Pour résoudre ces diﬃcultés numériques, nous avons utilisé trois techniques simultanément. Ces techniques consistent :

\1. à diminuer le nombre de paramètres, en postulant que la variation spatiale des
paramètres varie régulièrement et peut être approximée par un polynôme ;

\2. à remplacer la fonction de coût par une nouvelle fonction donnant un résultat
approché mais convergeant plus rapidement vers l’optimum : méthode des
puissances, méthode de l’intervalle ;

\3. à exploiter la propriété de convexité du domaine des chargements potentielle-
ment supportables pour repérer les chargements correspondant à un optimum
local, mais non à l’optimum global, et nécessitant donc des calculs complé-
mentaires.

L’implémentation de ces techniques et la discussion de leurs résultats sont présentées
à partir du chapitre suivant.

(3). « Rapidement » signiﬁe ici de l’ordre de la minute pour les problèmes que nous étudions.

218

<!-- p. 220 -->

Chapitre 13

Implémentation numérique

Résumé : Ce chapitre présente l’implémentation numérique et l’utilisation pratique
de l’extension de la méthode des réseaux de forces proposée. Dans un premier temps,
le logiciel utilisé et le traitement des équations d’équilibre et des nœuds d’appuis est
présenté. Ensuite, la redéﬁnition des joints 3D sous forme de segments 2D, qui permet
la simpliﬁcation des calculs et du stockage des données sans perte de généralité est
exposée. Par ailleurs, le raﬃnement du réseau à l’aide des branches partielles nécessite
une adaptation des équations matricielles, détaillée ici. Enﬁn, les stratégies d’optimisation numérique, qui sont l’enjeu numérique le plus important pour la recherche des
chargements extrêmes et donc pour la faisabilité pratique de la méthode que nous
proposons, sont introduites, ainsi qu’une étude des vitesses de convergence pour la
stratégie la plus eﬃcace (modiﬁcation de la fonction de coût utilisé pour la recherche
des chargements extrêmes).

Sommaire
13.1 Implémentation de l’extension des réseaux de forces . . . . . . . . 220
13.1.1 Visual Basic for Applications et Microsoft Excel . . . . . . 220
13.1.2 Équilibre horizontal . . . . . . . . . . . . . . . . . . . . . . 220
13.1.3 Équilibre vertical . . . . . . . . . . . . . . . . . . . . . . . 221
13.2 Redéﬁnition des joints . . . . . . . . . . . . . . . . . . . . . . . . . 223
13.3 Raﬃnement du réseau et branches partielles . . . . . . . . . . . . 225
13.3.1 Modiﬁcation des équations d’équilibre . . . . . . . . . . . 225
13.3.2 Écriture alternative des équations d’équilibre . . . . . . . 226
13.3.3 Vériﬁcation de l’équilibre a posteriori . . . . . . . . . . . . 226
13.4 Recherche des chargements extrêmes . . . . . . . . . . . . . . . . . 227
13.4.1 Optimisation sous contraintes . . . . . . . . . . . . . . . . 227
13.4.2 Polynômes de Lagrange . . . . . . . . . . . . . . . . . . . 227
13.4.3 Multiplicateurs de charges modiﬁés par puissances d’entiers 228
13.4.4 Coeﬃcient de sécurité géométrique modiﬁé . . . . . . . . . 233
13.4.5 Convexité du domaine des chargements supportables . . . 235
13.4.6 Bilan des stratégies . . . . . . . . . . . . . . . . . . . . . . 236

219

<!-- p. 221 -->

Chapitre 13. Implémentation numérique

13.1 Implémentation de l’extension des réseaux de
forces

13.1.1 Visual Basic for Applications et Microsoft Excel

L’implémentation des réseaux funiculaires a été réalisée en langage objet, avec
VBA (Visual Basic for Applications) et Microsoft Excel. Le logiciel créé a été nommé
Manacoh (Masonry Network Analysis for Construction History). Le choix du langage de programmation pour l’implémentation est antérieur au commencement de
la thèse : la première version du logiciel a été développée dans le cadre d’un travail de recherche sur la stabilité des dômes en maçonnerie (Ciblac et Fantin, 2016).
Un des objectifs de ce travail était de produire un logiciel facile d’accès pour les
étudiants et les ingénieurs, ne nécessitant pas de compétences particulières autres
que celles généralement maîtrisées par les ingénieurs de bureau d’études. La première version du logiciel de 2014 est disponible à l’adresse http://combiencaporte.
blogspot.fr/p/masonry-network-analysis-for.html. La nouvelle version du logiciel développée dans le cadre de cette thèse sera disponible à cette adresse :
http://bestrema.fr/manacoh/.
Les nœuds, les branches, les aires, les paramètres, les polynômes de Lagrange
sont implémentés sous forme objet, à l’aide des classes cNod, cBra, cAre, cDOF,
cDOFPoly etc.
À titre d’exemple, chaque objet de classe cBra (une branche du réseau) fait référence à deux objets de classe cNod (un nœud de tête et un nœud de queue), et à
deux objets de classe cAre (les aires situées à gauche et à droite de la branche dans
le plan horizontal). Réciproquement chaque objet de classe cNod (un nœud) contient
une liste des objets cBra, représentant les branches partant ou aboutissant à ce nœud.
Les feuilles du classeur Microsoft Excel servent à la fois au stockage des données,
à l’écriture des matrices d’équilibre, et à l’inversion de ces dernières. Une des feuilles
du classeur sert d’interface graphique pour les échanges avec l’utilisateur.

Au lancement du programme, les données existantes résultant d’un éventuel calcul précédent sont chargées depuis les feuilles Microsoft Excel dans VBA, les objets
correspondants créés, puis les opérations exécutées depuis VBA.
L’implémentation de la méthode des réseaux de forces classique repose directement sur l’écriture des matrices données dans l’état de l’art présentant la méthode.
Nous présentons dans la suite de cette partie uniquement les points particuliers de
notre implémentation de la méthode.

13.1.2 Équilibre horizontal

Comme nous l’avons vu lors de la présentation de l’application de l’équilibre
horizontal pour la construction des réseaux de forces (p. 67), les valeurs des m forces
horizontales dans les branches du réseau, réunies dans le vecteur ζ de dimension m,
dépendent de ndof paramètres (ndof \< m) réunis dans le vecteur ζdof. La construction
du vecteur ζdof, c’est-à-dire le choix des composantes le formant, et non le choix des
valeurs de ses composantes, peut être guidé par plusieurs stratégies.

220

<!-- p. 222 -->

Chapitre 13. Implémentation numérique

Block (2009) utilise les propriétés des ﬁgures réciproques pour identiﬁer les
ndof paramètres composant le vecteur ζdof. Nous utilisons pour cette thèse deux
approches plus directes, mais n’exploitant pas les propriétés des ﬁgures réciproques.
Dans le cas des géométries paramétriques, les ndof paramètres composant le vecteur ζdof sont choisies parmi les m paramètres composant le vecteur ζ dès la création
de la géométrie, de manière à représenter un ensemble de grandeurs caractéristiques
du système étudié. Par exemple dans le cas des dômes, les forces horizontales des
branches parrallèles aux méridiens seront choisies. Dans le cas des voûtes plates, les
forces horizontales des branches d’appuis seront choisies.
Dans le cas de géométries quelconques où les paramètres ζdof ne sont pas choisis
lors de la création de la géométrie, ou si le nombre de paramètres choisis par l’utilisateur est insuﬃsant, les ndof paramètres ζdof (ou les paramètres manquants) sont
choisis à l’aide d’une procédure itérative qui construit progressivement la matrice K
colonne par colonne tout en vériﬁant que les diﬀérentes colonnes restent indépendantes (à tout instant le rang de la matrice K en cours de construction doit être
égal à son nombre de colonnes). Si l’ajout d’une nouvelle colonne donne un système
dépendant, la force horizontale correspondant à la dernière colonne ajoutée doit être
prise comme paramètre, et la colonne correspondante retirée de la matrice K en cours
de construction.
Par ailleurs, la matrice K−1unkKdof qui relie les paramètres ζdof aux autres forces
horizontales ζunk ne dépend que de la position des nœuds du réseau projeté dans le
plan horizontal et de la connectivité du réseau. Comme ces derniers restent ﬁxes, la
matrice K−1unkKdof peut être calculée lors du premier calcul de l’équilibre horizontal,
et stockée pour être réutilisée pour les autres étapes du calcul. Cette stratégie est
adoptée dans notre implémentation, mais n’est valable que parce que nous ne nous
intéressons pas aux problèmes d’optimisation de formes. Dans ce type d’étude, la
matrice K−1unkKdof change à chaque itération du calcul.

13.1.3 Équilibre vertical

Écriture matricielle

La matrice D−1i relie la position des nœuds d’appuis et le chargement d’une part,
avec la position des nœuds intérieurs d’autre part. Comme la matrice Di dépend des
forces horizontales dans les branches ζ, l’inversion de la matrice Di doit avoir lieu à
chaque étape du calcul.

Position des nœuds d’appuis

Les altitudes des nœuds d’appuis sont données par le vecteur zb de dimension nb.
La construction de la matrice carrée et inversible Di suppose que zb soit connu, et
les altitudes des nœuds d’appuis sont donc une donnée d’entrée de l’équilibre vertical
et non une donnée de sortie.
Cependant, il est possible d’exprimer l’altitude zb d’un nœud d’appui particulier
comme une combinaison linéaire des altitudes des nœuds intérieurs zi, bien que ces
derniers ne soient pas encore connues avant l’application de l’équilibre vertical. Par

221

<!-- p. 223 -->

Chapitre 13. Implémentation numérique

exemple, l’altitude d’un nœud d’appui peut être choisie égale à l’altitude du nœud
intérieur lié au nœud d’appui, pour imposer que la force d’appui correspondante soit
horizontale. Ce type de condition est utile pour modéliser les conditions de symétrie.
Les ﬂèches courbes sur la ﬁgure 13.1 à droite indiquent l’égalité des altitudes des
nœuds d’appuis avec les nœuds intérieurs dans le cas d’une lune d’un dôme hémisphérique.

Fig 13.1 – Lune d’un dôme hémisphérique, réseau de masse, conditions de symétrie
sur les nœuds d’appuis

Dans le cas où l’altitude d’un nœud d’appui est égale à celle du nœud intérieur
correspondant, cette contrainte est implémentée en ajoutant simplement la colonne
de Db correspondant à l’altitude zb en question à la colonne de Di correspondant
à l’altitude zi recherchée. La valeur de zb est (temporairement) prise égale à zéro
pour annuler la contribution de la colonne correspondante dans Db, de telle manière
que l’équation 4.38 puisse être appliquée sans modiﬁcation. Enﬁn, lorsque les résultats sont stockés, la valeur de zb est prise égale à zi. Cette procédure pourrait être
implémentée de façon plus élégante à l’aide de matrices de permutations.

Il est également possible d’utiliser des conditions de symétrie sur les altitudes
des nœuds d’appuis (ﬁg. 13.2 pour le cas d’une voûte plate). Aucune modiﬁcation
particulière des matrices d’équilibre n’est nécessaire dans ce cas.

Fig 13.2 – Voûte plate, réseau de masse, conditions de symétrie sur les nœuds
d’appuis

222

<!-- p. 224 -->

Chapitre 13. Implémentation numérique

13.2 Redéﬁnition des joints

À chaque étape de la recherche d’un réseau de forces correspondant à un chargement extrême, il est nécessaire de recalculer la position du centre de pression de
chaque joint. Ce centre est déﬁni par l’intersection entre une droite (la ligne d’action de la force) et un plan (le plan du joint). Il est possible de réduire ce calcul à
l’intersection entre deux droites.

En eﬀet, d’une part la ligne d’action de la force s’appliquant sur un joint passe
par la branche du réseau correspondant à ce joint. D’autre part la branche du réseau,
quelle que soit sa forme, est contrainte à rester dans le plan vertical Pv passant par
les centres de gravité des deux blocs en contact au joint. Par conséquent l’intersection
entre la ligne d’action et le plan du joint est nécessairement placée sur l’intersection
entre le plan vertical Pv et le plan du joint. L’intersection de ces deux plans est une
droite. Cette droite est représentée par la donnée des deux points extrêmes correspondant aux bords du joints, généralement, mais non nécessairement, un point situé
sur l’extrados, et un point situé sur l’intrados.

Le segment joignant ces deux points représente l’ensemble des positions possibles
pour le centre de pression à l’intérieur du joint, pour les cas d’équilibre générés à
l’aide d’un réseau de forces. Ce segment peut être déterminé lors de la génération
de la géométrie à étudier, et gardé en mémoire pour être utilisé lors de la recherche
des chargements extrêmes. Par construction, l’intersection de la ligne d’action de la
résultante des forces avec le polygone plan du joint ou avec le joint réduit sous forme
de segment est identique.

Considérons un exemple. Un dôme hémisphérique est découpé selon ses parallèles
et méridiens aﬁn de former des voussoirs. Un voussoir aura deux types de joints : les
joints relatifs aux branches des méridiens (« meridian branches »), et les joints relatifs aux branches des parallèles (« parallel branches ») ou branches d’anneau (« hoop
branches »). Les joints des méridiens sont des surfaces coniques qui sont approximées
par leur plan tangent, de manière à être ramenés à l’hypothèse des joints plans polygonaux de notre étude. La génération des segments représentant les joints est donné
sur la ﬁgure 13.4. Le résultat pour l’ensemble des joints est donné sur la ﬁgure 13.5.
Les points déﬁnissant les segments des joints des méridiens (en bleu sur la ﬁgure)
sont tous sur l’intrados ou l’extrados, mais ce n’est pas nécessairement le cas pour les
joints des parallèles (en rouge).

Possible inexistence du joint réduit La génération des joints n’est généralement
pas problématique tant que les dimensions des blocs sont faibles devant les rayons
de courbure locaux de la structure. Il existe cependant des cas où l’intersection entre
le joint et le plan vertical passant par la branche est nulle. Un exemple de ce type
est donné sur une vue de dessus pour une voûte hélicoïdale formé de blocs allongés (ﬁg. 13.6). Nous avons également rencontré cette problématique dans le cas des
voûtes en arc de cloître. Dans ce genre de situation, la considération d’un découpage
plus ﬁn des blocs permet généralement de se replacer dans une situation où le joint
réduit existe.

223

<!-- p. 225 -->

Chapitre 13. Implémentation numérique

a b c

Fig 13.3 – Voussoir d’une lune Fig 13.4 – Réduction des joints à un segment ;
de dôme hémisphérique, après voussoir (a), joint méridien (b), joint parallèle (c)
découpage selon parallèles et
méridiens

Nota : La ﬁgure 13.3 montre un voussoir simpliﬁé, où les joints des méridiens sont des quadrilatères.
La courbe au niveau de l’intrados et l’extrados a complètement disparu. Nous utilisons pour notre
logiciel Manacoh une approximation des joints des méridiens avec des polygones à six côtés, qui
permettent de tenir compte de la courbe. Ceci n’est pas indiqué sur cette ﬁgure pour des raisons de
clarté.

Fig 13.5 – Joints des branches méridiennes (en bleu) et des branches parallèles (en
rouge), pour une lune d’un dôme hémisphérique

224

<!-- p. 226 -->

Chapitre 13. Implémentation numérique

o

\+ +

o o

\+ +
o centre de gravité / nœud

\+ intersection entre la branche o o
et le plan du joint en dehors du
joint réel

\- - - branche

Fig 13.6 – Projection sur le plan horizontal d’une voûte hélicoïdale à cinq claveaux,
où la réduction des joints est vide

13.3 Raﬃnement du réseau et branches partielles

13.3.1 Modiﬁcation des équations d’équilibre

Soit n0 et m0 le nombre de nœuds et de branches avant le raﬃnement du réseau de
masse. Les indices i et b désignent respectivement les nœuds et branches intérieures,
et les nœuds et branches d’appui, comme précédemment. Soit p l’indice pour les
branches partielles, et s l’indice pour les autres branches.
Le nombre total de branches du réseau après raﬃnement est m = ms + mp. Il
se décompose en ms branches normales (ms ≥m0), et mp = n0,i branches partielles
supplémentaires créées pendant le raﬃnement du réseau. Le nombre de nœuds a
doublé : n = 2n0. La matrice de connectivité C contient des lignes correspondant
aux branches partielles additionnelles en plus des lignes habituelles correspondant à
chaque branche (avant raﬃnement). La numérotation des branches et des nœuds peut
être choisie pour que la matrice C de m colonnes et de 2n0 lignes puissent s’écrire
sous forme de matrice par blocs :

" Csi Csb #
C = (13.1)
Cpi Cpb

Par hypothèse, les composantes horizontales de la force dans une branche partielle
additionnelle est nulle, d’où leur nom « partielle » parce que seules des forces verticales
sont transmises par ces branches. Cette hypothèse est arbitraire, et le moyen d’assurer
l’équilibre sera étudié dans la section 13.3.3 ci-dessous.
Suite à cette hypothèse, les branches partielles ne doivent pas être considérées pour
la résolution de l’équilibre dans le plan horizontal. La matrice Csi est ainsi substituée
à la matrice Ci dans les équations (4.25), (4.26) et (4.27) pour assurer l’application
de cette hypothèse. Après résolution de l’équilibre dans le plan horizontal, les forces
horizontales dans les branches non-partielles dépendent de ndof = m −mp −ni paramètres, à condition que la matrice K avant le raﬃnement du réseau était de rang
maximal.
La méthode usuelle des réseaux de forces ne peut pas être utilisée directement
pour l’équilibre vertical, parce qu’elle nécessite que les forces horizontales soient non

225

<!-- p. 227 -->

Chapitre 13. Implémentation numérique

nulles pour son application, ce qui n’est pas le cas dans les branches partielles additionnelles. Nous introduisons donc mp = n0,i nouveaux paramètres w∗p qui sont les
valeurs des forces verticales dans les branches partielles. Ces nouveaux paramètres
forment un troisième type de paramètres pour les réseaux de forces : 1. force horizontale, 2. position verticale d’un nœud d’appui, 3. force verticale dans une branche
partielle.

Les équations exprimant l’équilibre vertical (4.32) (4.36) (4.37) (4.38) deviennent :

Ct0iw∗0 = −pz −Ctpiw∗p (13.2)
D0i = Ct0iL−1H L∗HC0i (13.3)
D0b = Ct0iL−1H L∗HC0b (13.4)
D0izi = −pz −Ctpiw∗p −D0bzb (13.5)

La position des nœuds du réseau zi est donc fonction des charges verticales pz,
des paramètres habituels zb et ζdof, et des nouveaux paramètres w∗p.

13.3.2 Écriture alternative des équations d’équilibre

La modiﬁcation de la résolution de l’équilibre vertical suite au raﬃnement du réseau dans les équations (13.2) à (13.5) est entièrement compris dans le terme −Ctpiw∗p.
Il exprime que la composante verticale de la force dans une branche partielle (la seule
non nulle dans cette branche) agit d’un sous-bloc à l’autre.

Par ailleurs, l’équilibre horizontal est résolu simplement en négligeant les branches
partielles lors de cette étape.

Une écriture alternative des équations d’équilibre peut donc être utilisée. Il s’agit
d’utiliser les matrices habituelles de la méthode des réseaux de forces lors de la résolution de l’équilibre horizontal et de l’équilibre vertical, sans tenir compte des branches
verticales, et d’ajouter à ces équations l’eﬀet des branches verticales. Cet ajout est
réalisé par des charges verticales ﬁctives pz,p = ±w∗p sur chaque nœud intérieur du
réseau. Ces charges sont réunies dans un vecteur pz,p.

13.3.3 Vériﬁcation de l’équilibre a posteriori

Chaque branche partielle applique sur les blocs qu’elle relie deux forces verticales
opposées avec un bras de levier lH, qui correspond à la distance horizontale entre les
nœuds des blocs bi. Ces forces forment un couple si le bras de levier lH n’est pas nul,
et appliquent au bloc B un moment w∗plH, qui correspond à un chargement extérieur
inexistant.

Si les nœuds des branches partielles, c’est-à-dire les nouveaux nœuds créés pour
chaque sous-blocs, sont alignés sur une droite verticale, alors ce chargement extérieur
est nul. En d’autres termes, la force horizontale dans la branche partielle est nulle,
et le fait que les forces des branches partielles aient été négligées pour l’équilibre
horizontal est dans ce cas sans conséquence.

226

<!-- p. 228 -->

Chapitre 13. Implémentation numérique

Si les nœuds des branches partielles ne sont pas alignés sur une verticale, chaque
bloc est soumis à un chargement extérieur inexistant : le moment w∗plH.
Dans le cas où un autre système de forces équilibré, respectant le critère de résistance, et correspondant au chargement extérieur opposé −w∗plH peut être construit,
alors la combinaison de ce système de forces et du réseau de forces donne une solution
d’équilibre, dans laquelle le chargement extérieur inexistant s’annule.

Cependant, il ne peut être garanti que ce second système de forces équilibré puisse
être trouvé pour toute structure. Le champ d’application de cette méthode est donc
limitée à des cas particuliers, comme les voûtes plates d’Abeille où le bras de levier
lH est nul, et les plates-bandes à joints en X où des systèmes de forces équilibrés
complémentaires peuvent être trouvés (Voir section 15.4.3 p. 265).

13.4 Recherche des chargements extrêmes

13.4.1 Optimisation sous contraintes

Nous avons vu dans la section 12.6 p. 217, que la recherche d’un chargement extrême F(Q)Q relatif au chargement Q sur un trajet de chargement radial est réalisée
par résolution d’un problème d’optimisation sous contraintes d’une fonction f dépendant d’un vecteur de paramètres ζ. La fonction f est de la forme :

f(ζ) = min λj(ζ) (13.6)
j∈J

avec λj le multiplicateur de charge local du joint j, et J l’ensemble des joints, tels
que déﬁnis dans la section 3.1.2 p. 42.

Nous présentons dans cette section les moyens mis en œuvre dans le cadre de cette
thèse pour permettre en pratique la recherche de l’optimum global de la fonction f.

13.4.2 Polynômes de Lagrange

Les paramètres contenus dans le vecteur ζ dont dépend une solution d’équilibre
sont de trois types : force horizontale du réseau projeté, altitude d’un nœud d’appui,
force verticale dans une branche partielle.

A l’intérieur de chacun de ces groupes, il est possible de former d’autres sousgroupes : par exemple pour un dôme de distinguer les forces horizontales correspondant aux forces d’anneaux, des forces horizontales correspondant aux forces méridiennes. Les valeurs que prennent les paramètres d’un sous-groupe pour la solution
optimum présentent dans certains cas une certaine régularité. Cette observation peut
être exploitée dans le but de réduire le nombre de paramètres du problème d’optimisation en utilisant les polynômes d’interpolation de Lagrange.
Soit k = k0 + k1 paramètres qui présentent une régularité attendue (ou potentielle). k0 polynômes de Lagrange Lj(X) de degré k0 −1 sont déﬁnis en utilisant les
valeurs ζj des k0 premiers paramètres. Les pôles xj sont les coordonnées tels que
Lj(xj) = 1 et Lj(xi) = 0 si i̸ = j. Ces pôles sont régulièrement espacés dans le réseau de masse de manière à éviter les problèmes de divergence. La variable X est

227

<!-- p. 229 -->

Chapitre 13. Implémentation numérique

une coordonnée cartésienne, cylindrique ou sphérique choisie pour correspondre à la
régularité géométrique de la structure.

(X −xi)
Lj(X) = Y ∀j ∈[1; k0] (13.7)
(xj −xi) i̸=j

Les valeurs ζq des k1 paramètres restants sont alors exprimées en utilisant la
propriété des polynômes de Lagrange :

ζq = X ζjLj(X) ∀q ∈[k0 + 1; k] (13.8)
j∈[1;k0]

L’utilisation de l’interpolation repose sur le postulat de la régularité des valeurs
prises par les paramètres pour la solution optimum. Ce postulat peut se trouver
contredit, comme par exemple dans le cas des forces d’appuis des voûtes plates (section 16.2.3 p. 283). Dans ce cas, le chargement extrême calculé avec interpolation est
nettement inférieur à celui qui aurait été calculé (lorsque cela est possible) sans interpolation. La comparaison des domaines des chargements supportables avec et sans
interpolation a été réalisée sur le cas particulier des voûtes plates (section 16.2.3).

13.4.3 Multiplicateurs de charges modiﬁés par puissances d’entiers

En pratique, même dans le cas d’un faible nombre de paramètres, il est fréquent
que la méthode du gradient réduit généralisé ne permette pas de trouver le maximum
global de la fonction f. Marco Czarnecki (1) nous a suggéré de remplacer la fonction f
de l’équation 13.6 par la fonction approchée gp, utilisant un entier p :

  −1/p
gp(ζ) = X |λj(ζ)|−p  (13.9)
j∈J

Cette fonction présente la propriété suivante :

∀ζ, p→+∞gp(ζ)lim = f(ζ) (13.10)

Nous avons utilisé une version modiﬁée de la fonction gp pour des raisons de calculs numériques. En eﬀet lorsque λj(ζ) est grand pour tous les joints (si la structure
est « très stable »), alors pour p grand P |λj(ζ)|−p est évalué numériquement comme
j∈J
valant zéro, et il n’est alors plus possible de faire le calcul numérique de gp en raison
d’une erreur de division par zéro. La modiﬁcation consiste à normaliser les multiplicateurs de charge locaux avec le multiplicateur de charge global f(ζ) de la solution
d’équilibre en cours de considération. Nous déﬁnissons la nouvelle fonction fp ainsi :

 −p−1/p
λj(ζ)
fp(ζ) = X f(ζ)  × f(ζ) (13.11)
j∈J

(1). Marco Czarnecki, Institut de Mathématiques et Modélisation de Montpellier, UMR 5030
CNRS, Université Montpellier 2.

228

<!-- p. 230 -->

Chapitre 13. Implémentation numérique

La fonction fp présente une propriété équivalente à celle de la fonction gp :

∀ζ, p→+∞fp(ζ)lim = f(ζ) (13.12)

L’existence des propriétés suivantes est conjecturée, mais n’a pas été prouvée du
point de vue théorique :

p→+∞maxlim ζ fp(ζ) = maxζ f(ζ) (13.13)
p = ζ∗ (13.14) p→+∞ζ∗lim

Cette conjecture permet de calculer avec p grand un estimatif du multiplicateur de
charge maxζ f(ζ), en maximisant la fonction fp au lieu de maximiser la fonction
f. L’avantage est que la recherche du maximum de la fonction fp est plus simple
numériquement que la recherche du maximum de la fonction f. La précision de cet
estimatif en fonction p et la notion de simplicité de maximisation sont étudiées sur
des cas particuliers ci-dessous.
La convergence de la suite numérique (max fp)p avec
p ∈{10; 50; 100; 150; 200; 250; 300; 350; 400; 450} est étudiée dans la suite sur
des cas particuliers. Soit n le nombre de paramètres (dimension du vecteur paramètre ζ). Nous notons ci-dessous avec l’exposant ∗la valeur des paramètres qui
permettent d’obtenir le maximum d’une fonction :
— soit ζ∗la valeur du vecteur paramètre ζ tel que f(ζ∗) = max f
— soit ζ∗p la valeur du vecteur paramètre ζ tel que fp(ζ∗p) = max fp
Nous utilisons de plus la notation suivante pour mesurer l’écart entre ζ∗et ζ∗p

∥ζ∗p −ζ∗∥ |ζ∗p,i −ζ∗i | = X (13.15)
∥ζ∗∥ ζ∗i i∈[1,n]

Convergence arc en plein-cintre

Nous considérons le coeﬃcient de sécurité statique (2) d’un arc en plein cintre
chargé uniformément par son poids propre. Les paramètres suivants sont considérés :
— arc composé de 24 claveaux ;
— rayon intrados 8 m, rayon extrados 12 m ;
— masse volumique (3) 1000 kg/m3 ;
— résistance à la compression 10 MPa.
Il est possible d’obtenir une bonne approximation du coeﬃcient de sécurité statique
théorique en raison du faible nombre de paramètres (3, réduits à 2 en utilisant les
conditions de symétrie) : f(ζ∗) = max f = 56,709048 (ﬁg. 13.8).

La ﬁgure 13.9 montre que pour cet exemple, pour p > 50 l’erreur relative sur
l’optimum est inférieure à 0,1% ce qui en pratique est déjà largement suﬃsant vu
les incertitudes usuelles sur la géométrie des arcs et des voûtes. Cette ﬁgure montre

(2). Le coeﬃcient de sécurité statique a été déﬁni dans la section 3.2.1 p. 43.
(3). Le poids des claveaux est obtenu en multipliant leur masse par la gravité prise égale à 10 m.s−2.
Cela revient à utiliser l’approximation usuelle dans le bâtiment « 1 kg = 1 daN ». L’incidence de cette
approximation sur les domaines des chargements potentiellement supportables est abordée p. 252.

229

<!-- p. 231 -->

Chapitre 13. Implémentation numérique

Fig 13.7 – Centres de pression et Fig 13.8 – Coeﬃcient de sécurité
polygone funiculaire statique théorique

également que la suite f(ζ∗p) converge plus rapidement vers max f que la suite
p
fp(ζ∗p) p. Cette remarque est importante, car elle exprime qu’en pratique la maximisation est calculée en utilisant la fonction de coût fp, puisque le résultat ﬁnal à
retenir n’est pas max fp = fp(ζ∗p) mais f(ζ∗p).
Nous donnons également pour l’exemple actuel la vitesse de convergence pour
servir de point de comparaison dans la suite (ﬁg. 13.10). Sur ces ﬁgures, nous notons :
p) −fp−50(ζ∗p−50)| ∆fp(ζ∗p) = 2|fp(ζ∗ (13.16) |fp(ζ∗p) + fp−50(ζ∗p−50)|
p) −f(ζ∗p−50)| ∆f(ζ∗p) = 2|f(ζ∗ (13.17) |f(ζ∗p) + f(ζ∗p−50)|
p −ζ∗p−50| ∆ζp = 2|ζ∗ (13.18) |ζ∗p + ζ∗p−50|

\|fp(ζ∗p) −f(ζ∗)|/|f(ζ∗)| ∆fp(ζ∗p) ∆f(ζ∗p) ∆ζp
100 |f(ζ∗p) −f(ζ∗)|/|f(ζ∗)| 100
∥ζ∗p −ζ∗∥/∥ζ∗∥

10−2 10−2

10−4 10−4

p p
0 100 200 300 400 0 100 200 300 400

Fig 13.9 – Convergence de max fp vers Fig 13.10 – Convergence de
f(ζ∗) = max f, arc en plein-cintre (max fp −max fp−1) vers 0, arc en
plein-cintre

230

<!-- p. 232 -->

Chapitre 13. Implémentation numérique

Convergence dôme elliptique

Nous considérons le coeﬃcient de sécurité statique d’un dôme elliptique chargé
uniformément par son poids propre. Les paramètres suivants sont considérés :
— découpage en 9 × 9 claveaux d’un quart de dôme ;
— rayon moyen rx = rz = 10 m, ry = 2rz = 10 m ;
— épaisseur t = 10rz1 = 1 m ;
— masse volumique (4) 1000 kg/m3 ;
— résistance à la compression 10 MPa.
Le découpage en blocs est représenté sur la ﬁgure 13.11. Les blocs rouges ﬁgurent les
blocs d’appui. Les résultats des joints de tête, qui sont artiﬁciellement réduits à une
surface d’aire nulle en raison de la forme triangulaire des claveaux à la clé, ne seront
pas considérées.
Les forces d’anneau ne sont pas considérées (5). Il y a 9 paramètres pour les forces
horizontales, et 9 paramètres pour les positions des nœuds d’appuis, soit un total
de n = 9 + 9 = 18 paramètres. L’optimum f(ζ∗) ne peut pas être calculé directement et de façon ﬁable avec f en raison du nombre n de paramètres qui est plus
grand que sur l’exemple de l’arc en plein-cintre. Nous considérons donc la vitesse de
convergence (ﬁg. 13.13).
La vitesse de convergence de fp(ζ∗p) est comparable à celle vue précédemment
p
pour l’arc en plein-cintre. En revanche, la vitesse de convergence de f(ζ∗p) et de
p
ζ∗p n’est pas régulière. Une hypothèse pour expliquer ce phénomène est donnée
p
dans l’exemple suivant, concernant la plate-bande.

Convergence plate-bande à joints en X

Nous considérons la plate-bande à joints en X construite aux Grands ateliers de
l’Isle d’Abeau, dont le modèle est présenté dans la section 15.3.1 p. 257. Après application des conditions de symétrie, le système présente un total de n = 8 paramètres, y
compris les branches partielles transmettant des forces verticales entre les demi-blocs.
L’optimum f(ζ∗) ne peut pas être calculé directement et de façon ﬁable avec f
en raison du nombre n de paramètres qui est plus grand que sur l’exemple de l’arc
en plein-cintre. Nous considérons donc la vitesse de convergence (ﬁg. 13.14).
Pour un chargement donné, nous appelons multiplicateur de rupture indéterminé
un multiplicateur de rupture qui peut être trouvé avec plusieurs valeurs des paramètres, et donc plusieurs réseaux de forces diﬀérents.
Ce phénomène pourrait expliquer que les vitesses de convergence de fp(ζ∗p) et
p
f(ζ∗p) soient comparables à celles vues précédemment pour l’arc en plein-cintre, et
p

(4). Le poids des claveaux est obtenu en multipliant leur masse par la gravité prise égale à 10 m.s−2.
Cela revient à utiliser l’approximation usuelle dans le bâtiment « 1 kg = 1 daN ». L’incidence de cette
approximation sur les domaines des chargements potentiellement supportables est abordée p. 252.
(5). Aucune force ne transite par la branche d’anneau représentée en tête du dôme sur les ﬁgures.
Nous utilisons cette branche uniquement pour que l’ensemble des branches soient connectées et
permettent l’exploration des graphes représentatifs des réseaux, et imposons une force nulle dans les
branches d’anneaux.

231

<!-- p. 233 -->

Chapitre 13. Implémentation numérique

Fig 13.11 – Dôme elliptique, avec blocs Fig 13.12 – Réseau de forces
d’appuis en rouge

∆fp(ζ∗p) ∆f(ζ∗p) ∆ζp ∆fp(ζ∗p) ∆f(ζ∗p) ∆ζp

100 100

10−2 10−2

10−4 10−4

p p
0 100 200 300 400 0 100 200 300 400

Fig 13.13 – Convergence de Fig 13.14 – Convergence de
(max fp −max fp−1) vers 0, (max fp −max fp−1) vers 0,
dôme elliptique plate-bande à joints en X

232

<!-- p. 234 -->

Chapitre 13. Implémentation numérique

que pourtant la suite des paramètres optimaux calculés ζ∗p ne converge pas. Cette
p
non-convergence se traduit par des réseaux de forces optimaux calculés visuellement
diﬀérents suivant la valeur de p (ﬁg. 13.15).

Nous avons tenté pour cet exemple de lever l’indétermination du multiplicateur de
rupture en imposant que la somme de la poussée sur les deux faces d’un claveau d’appui vaille 300 daN, ce qui réduit l’espace des paramètres explorés. Même avec cette
condition, utilisée pour créer les ﬁgures mentionnées ci-dessus, il reste une indétermination sur le multiplicateur de rupture, probablement lié aux branches partielles.

p = 100 p = 200

p = 300 p = 400

Fig 13.15 – Réseaux de forces optimaux correspondant aux chargements extrêmes
calculés pour p ∈{100; 200; 300; 400} ; plate-bande à joints en X

Bilan

La reformulation de la fonction à optimiser f avec une fonction fp utilisant des
puissances élevées fonctionne, au sens où la convergence est plus stable : le solveur
intégré de Microsoft Excel ne s’arrête pas sur des maximums locaux, mais semble
bien aller jusqu’au maximum global de la fonction fp. L’ordre de grandeur à prendre
pour p sur la base de ces exemples est de 100 à 200 environ.

Cette modiﬁcation de la fonction de coût est indépendante du type de coeﬃcient
de sécurité considéré. Il s’applique ainsi aussi bien au coeﬃcient de sécurité statique
(considéré dans les exemples ci-dessus) qu’au coeﬃcient de sécurité géométrique.

13.4.4 Coeﬃcient de sécurité géométrique modiﬁé

La modiﬁcation du coeﬃcient de sécurité géométrique présentée ici est spéciﬁque
à ce coeﬃcient, et n’est pas utilisable pour les autres coeﬃcients de sécurité du calcul
à la rupture.
On considère un intervalle [x0; x1] représentant un joint dont le centre est
xm = 12(x0 + x1). Les valeurs prises par le coeﬃcient de sécurité géométrique local
λj = CSGj suivant la position x du centre de pression sur l’intervalle du joint est

233

<!-- p. 235 -->

Chapitre 13. Implémentation numérique

représentée sur la ﬁgure 13.16. Pour éviter la division par zéro en xm, la fonction λj
est remplacée par la fonction quadratique centrée eλj sur cet intervalle, et représentée
sur la ﬁgure 13.17 :

(x −x1)(x −x0) (x −xm)2 + x0x1 −x2m
eλj(x) = = (13.19) (xm −x1)(xm −x0) (xm −x1)(xm −x0)

La fonction x →eλj(x) donnée ci-dessus est normalisée de telle manière à ce que le
maximum, atteint au milieu de l’intervalle xm, vaille eλj(xm) = 1.

y y

λj = CSGj eλj
3 eeλj
1

2
0

1

−1

0 x x
x0 xm x1 x0 xm x1

Fig 13.16 – Coeﬃcient de sécurité local Fig 13.17 – Fonctions polynomiales
sur un joint remplaçant le coeﬃcient de sécurité local

Nous remplaçons la fonction f = min λj pour l’optimisation par la fonction ef =
P eλj, aﬁn de faire disparaître la forte non linéarité liée à la fonction min utilisée par
f. Cette première fonction ne donne pas de résultat satisfaisant, car elle donne une
importance trop grande aux joints dont le coeﬃcient de sécurité local n’est pas proche
du coeﬃcient de sécurité global en cours de calcul.

En eﬀet, la recherche du coeﬃcient de sécurité géométrique d’une structure clavée
revient à la recherche du réseau de forces dont les centres de pression sont globalement les mieux centrés à l’intérieur des joints. Le fait qu’un des centres de pression
soit parfaitement centré sur un joint n’a pas d’intérêt, seule la position du centre de
pression le plus excentré sur son joint compte. Cette observation nous a conduit dans
un second temps à modiﬁer eλj en une autre fonction eeλj.
Pour chercher des solutions où le centre de l’intervalle représentant le joint ait
moins d’importance, on cherche une fonction simple qui ait la même forme globale
que eλj, mais avec un maximum plus plat. Posons la fonction polynomiale de degré 4
eeλj telle que :
eeλ(x) = eλ(x) aeλ(x) + b (13.20)

Les paramètres a et b sont choisis de façon à ce que la fonction ait un fond plat
′
en x = xm (soit eeλ (x) = 0 si et seulement si x = xm) et soit normalisée (eeλ(xm) = 1).

234

<!-- p. 236 -->

Chapitre 13. Implémentation numérique

Ces deux conditions imposent que :

−2a + b = 0 (condition sur eeλ’) (13.21)
−a + b = 1 (condition sur eeλ) (13.22)

Par conséquent la fonction eeλ recherchée, représentée sur la ﬁgure 13.17, a la forme
suivante :
eeλ(x) = eλ(x) eλ(x) + 2 (13.23)

En remplaçant cette fois la fonction f = min λj pour l’optimisation par la fonction
eef = P eeλj, on trouve de meilleures solutions lors de la recherche du coeﬃcient de
sécurité géométrique lorsque le nombre de joints est important. Cette méthode est
cependant moins eﬃcace, et moins générale, que la méthode utilisant les puissances
présentée à la section précédente. Elle n’est donc pas utilisée dans la suite.

13.4.5 Convexité du domaine des chargements supportables

La recherche du chargement extrême F(Q)Q correspondant au chargement Q sur
un trajet de chargement radial repose sur la résolution d’un problème d’optimisation
sous contraintes.

Un des principaux problèmes rencontrés lors de l’optimisation, est qu’il n’est pas
possible de savoir si la solution eF calculée par le problème d’optimisation est égale la
meilleure possible F, ou même si cette dernière est proche de la meilleure possible F.
En eﬀet, l’optimum calculé peut être un optimum local et non un optimum global. Par
ailleurs, lorsque le processus d’optimisation converge lentement et est arrêté avant la
ﬁn du processus, la distance entre la solution obtenuen eF et l’optimum global F n’est
pas connue.

Pour contourner ce problème, il est possible d’exploiter la propriété de convexité
du domaine des chargements potentiellement supportables, pour repérer les solutions eF qui ne peuvent pas être l’optimum global F, et qui doivent être aﬃnées.
Ainsi, sur la ﬁgure 13.18, les chargements considérés Q sont indiqués par les points,
et les plus grands chargements supportables eF(Q)Q obtenus sur un trajet radial sont
indiqués par des ﬂèches. La convexité du domaine des chargements potentiellement
supportables indique que les chargements supportables Fa(Qa)Qaf et Fb(Qb)Qbf sont
situés strictement à l’intérieur du domaine, et qu’ils ne correspondent donc pas à des
chargements extrêmes. A contrario, le chargement Fc(Qc)Qcf est situé sur la frontière
du domaine en cours de calcul. Dans cet exemple, il est certain qu’il est possible de
trouver des chargements supportables plus grands que Fa(Qa)Qaf et Fb(Qb)Qb.f
À partir de ces observations, la stratégie suivante a été adoptée lors des calculs
des domaines des chargements supportables. L’approche par l’intérieur du domaine
sur la base d’un ensemble de chargements (Q1, . . . ,Qn) suit la procédure suivante :
\1. Première étape. Pour tous les chargements Qi, calcul d’un premier estimatif
Fi,1g du multiplicateur de rupture, qui permet d’obtenir un premier domaine
K1 approché par l’intérieur du domaine K des chargements supportables

235

<!-- p. 237 -->

Chapitre 13. Implémentation numérique

Q2

FaQaf

Qa Qb FbQbf Qc
FcQcf

Q1

Fig 13.18 – Exploitation de la propriété de convexité du domaine des chargements
supportables

\2. Deuxième étape.
— Pour tous les chargements Qi tels que Fi,1Qig n’est pas situé sur la fron-
tière du domaine K1, calcul d’un nouvel estimatif Fi,2g du multiplicateur de
rupture.
— Pour les autres chargments Qi on prend Fi,2g = Fi,1g
— On obtient ainsi un nouveau domaine K2 approché du domaine K des
chargements supportables
\3. Étape j. Répéter deuxième étape tant que tous les chargements Fi,jQig ne sont
pas situés sur le domaine approché Kj−1.

13.4.6 Bilan des stratégies

Les techniques présentées ci-dessus permettent de mettre au point des stratégies
appropriées pour les processus d’optimisation.

La stratégie qui nous a paru la plus eﬃcace sur les exemples traités (plates-bandes
à joints en X et voûtes plates) a été de complexiﬁer progressivement les modèles, et
de repartir de solutions intermédiaires.

Ainsi, l’augmentation du degré n des polynômes d’interpolation, et de l’entier p
de la fonction modiﬁée permet de trouver de meilleures solutions (domaine des chargements supportables plus grand), mais augmente les temps de calcul. Nous sommes
donc partis de degré des polynômes faibles (n = 2 ou 3), avec une valeur p = 50,
pour calculer un premier domaine. Dans un second temps, en partant des solutions
déjà calculées, le degré des polynôme est augmenté, ainsi que la valeur de p.

L’arrêt de la recherche de nouvelles solutions a été basé sur la propriété de
convexité du domaine.

236

<!-- p. 238 -->

Quatrième partie

Étude mécanique des
constructions clavées

237

<!-- p. 239 -->

Chapitre 14

Étude des arcs et dômes

Résumé : Ce chapitre présente deux applications de l’extension de la méthode des
réseaux de forces aux arcs et voûtes courbes. La première est l’étude des épaisseurs
minimales des arcs plein-cintre et des dômes hémisphériques, et à travers ces exemples
l’étude de la convergence de l’estimatif du coeﬃcient de sécurité géométrique vers la
valeur du coeﬃcient théorique déﬁni par Heyman (1969). La seconde est l’exploitation
des réseaux de forces pour l’étude des procédés historiques de calcul des voûtes, à
travers les exemples de Rankine et Durand-Claye au xixe siècle.

Sommaire
14.1 Épaisseurs minimales . . . . . . . . . . . . . . . . . . . . . . . . . 239
14.1.1 Coeﬃcient de sécurité géométrique . . . . . . . . . . . . . 239
14.1.2 Épaisseur minimale d’un arc plein-cintre . . . . . . . . . . 239
14.1.3 Épaisseur minimale d’un dôme hémisphérique . . . . . . . 241
14.2 Étude des procédés historiques de calcul des voûtes . . . . . . . . 245

238

<!-- p. 240 -->

Chapitre 14. Étude des arcs et dômes

14.1 Épaisseurs minimales

14.1.1 Coeﬃcient de sécurité géométrique

Nous rappelons ici brièvement les points principaux vus lors de la présentation
du coeﬃcient de sécurité géométrique dans la section 3.3.2 p. 47.

Heyman déﬁnit le coeﬃcient de sécurité géométrique d’un arc comme le rapport
entre l’épaisseur de l’arc considéré et l’épaisseur minimale pour laquelle l’arc est
stable (Heyman, 1969, 1995, p. 21). La détermination de la valeur de ce coeﬃcient
de sécurité nécessite de déterminer l’épaisseur minimale de la structure pour pouvoir
ensuite la relier à l’épaisseur réelle de la structure. Nous notons ce coeﬃcient de
sécurité γH dans la suite.
Nous avons proposé la déﬁnition d’un estimatif du coeﬃcient de sécurité géométrique d’une structure, noté CSGJ , dans la section 3.3.2 p. 47. Cet estimatif est déﬁni
en suivant la même procédure de calcul que celle des multiplicateurs de charge du
calcul à la rupture. Nous noterons ce coeﬃcient de sécurité γ dans cette section, en
remplacement de CSGJ , pour simpliﬁer les notations.
Tandis que γH est obtenu par la division de l’épaisseur réelle d’une structure par
son épaisseur minimale (division de deux nombres), γ est le résultat de l’optimisation
mathématique d’une fonction.

Nous postulons que le coeﬃcient de sécurité géométrique γ a les propriétés suivantes pour un arc d’épaisseur constante t et de rayon moyen r :
— il est une bonne approximation du coeﬃcient de sécurité géométrique γH déﬁni
par Heyman ;
— il donne une bonne estimation de l’épaisseur minimale (t/r)min en prenant
(t/r)/γ ;
— il converge vers 1 quand l’épaisseur t converge vers l’épaisseur minimale tmin ;
— si le coeﬃcient de sécurité géométrique local prend la même valeur sur k joints,
alors ces k joints correspondent aux rotules attendues dans le mécanisme de
ruine attendu pour l’arc d’épaisseur minimale.
Ces propriétés n’ont pas été démontrées. Leur validité est testée dans cette section sur
l’exemple des arcs en plein-cintre et des dômes hémisphériques, chargés uniquement
par leur poids propre.

14.1.2 Épaisseur minimale d’un arc plein-cintre

Le problème de l’épaisseur minimale d’un arc en plein-cintre portant seulement
son poids propre a été posé par Couplet (1730). La première résolution exacte du
problème dans le cas où les joints de l’arc suivent une coupe radiale, a été exposée par
Milankovitch (1) en 1904. Milankovitch étudie l’équilibre de l’arc en résolvant de façon
analytique les équations d’équilibre. Plusieurs auteurs ont cherché ultérieurement à
retrouver cette épaisseur minimale par d’autres méthodes : Heyman (1969, 2009),
Ochsendorf (2002), Oikonomopoulou (2009), Makris et Alexakis (2013).

(1). Nous n’avons pas consulté la thèse de Milankovitch de 1904, mais la synthèse de cette dernière
publiée par Foce en 2007.

239

<!-- p. 241 -->

Chapitre 14. Étude des arcs et dômes

L’épaisseur minimale d’un arc plein-cintre dépend de sa coupe des pierres (Heyman, 2009). Nous nous intéressons ici au cas où les joints suivent une coupe radiale,
suivant le principe de normalité présenté dans notre exposé sur la coupe des pierres
(section 5.4 p. 80). Makris et Alexakis (2013) considèrent également le cas de la coupe
verticale des joints, qui conduit à des résultats diﬀérents.

Nous notons t l’épaisseur d’un arc et r son rayon moyen. L’épaisseur minimale
d’un arc en plein-cintre soumis à son seul poids propre et dont les joints suivent une
coupe radiale vaut (t/r)min = 0,1075 (Milankovitch, 1904) ; Makris et Alexakis (2013)
précisent cette valeur ((t/r)min = 0,10748), et indiquent que les joints critiques (2) sont
déﬁnis par les angles au sommet ϕc = 0◦, 54,484◦et 90◦.
L’épaisseur minimale donnée par les auteurs cités précédemment correspondent à
deux modèles équivalents :
— un arc monolithe constitué d’un matériau inﬁniment résistant à la compression,
et avec une résistance nulle à la traction, où les résultantes des eﬀorts sont
évalués sur des sections radiales ;
— un arc clavé avec des joints rayonnants découpant l’arc en des voussoirs inﬁ-
nitésimaux, c’est-à-dire un arc clavé avec une inﬁnité de joints ; ces joints ont
une résistance inﬁnie à la compression et nulle à la traction.
Nous appellerons « arc inﬁnitésimal » ce type d’arc pour le distinguer des arcs composés d’un nombre ﬁni de voussoirs, qui constituent le cœur de notre étude.

L’étude de l’épaisseur minimale d’un arc composé de 30 voussoirs à l’aide des
réseaux de forces avec considération des joints est donnée sur la ﬁgure 14.1. Cette
ﬁgure illustre deux phénomènes.

Premièrement, pour des arcs à 30 voussoirs, l’estimatif de l’épaisseur minimale
t/r/γ correspond à une erreur relative de moins de 1%, que l’arc considéré soit moitié plus ﬁn ou quatre fois plus épais que l’arc d’épaisseur minimale théorique. L’estimatif de l’épaisseur minimale t/r/γ a donc une bonne précision, relativement aux
incertitudes habituelles existant sur la géométrie réelle des arcs en pierre de taille.

Deuxièmement, l’épaisseur minimale trouvée pour l’arc composé de 30 voussoirs
vaut (t/r)min = 0,10746, à comparer avec l’épaisseur minimale attendue pour un
« arc inﬁnitésimal » dont l’épaisseur minimale vaut (t/r)min = 0,10748. L’écart entre
ces deux valeurs correspondant à des arcs diﬀérents (du point de vue du nombre de
voussoirs) est faible (0,02%).

Pour retrouver l’épaisseur minimale de l’« arc inﬁnitésimal », il faut considérer
ou bien un arc constitué d’un très grand nombre de voussoirs, ou bien un arc où
des joints sont présents à l’emplacement de chaque joint critique attendu : aux naissances (ϕc = 90◦), à la clé (ϕc = 0◦), et sur un joint situé entre les deux précédents à
(ϕc = 54,484◦).
Les arcs semi-circulaires composés de 10, 20, 30, 40 et 60 voussoirs ont tous
comme joint le plus proche du joint critique théorique ϕc = 54,484◦le joint situé
à ϕ = 54◦. Tous ces arcs donnent la même approximation de l’épaisseur minimale,
soit (t/r)min = 0,10746. L’arc semi-circulaire composé de 56 claveaux représente un
découpage plus grossier que l’arc à 60 voussoirs. Cependant le joint le plus proche
du joint critique théorique se trouve à ϕ = 54,643◦au lieu de ϕ = 54◦, et est donc

(2). Nous appelons joints critiques les joints où la ligne de pression touche l’intrados ou l’extrados.

240

<!-- p. 242 -->

Chapitre 14. Étude des arcs et dômes

plus proche de ϕc = 54,484◦. L’épaisseur minimale pour un arc de 56 voussoirs vaut
0,10748, soit exactement l’épaisseur attendue pour un « arc inﬁnitésimal ».

t/r/γ 3.69874
\=

γ
0,1080 2.78244
\=

γ
1.85891
\= 0.930631.00037 γ 0.46546
\==
γγ 0,1075 =γ
(t/r)min = 0.10748 (Milankovitch)

0,1070 t/r
0,00 0,05 0,10 0,15 0,20 0,25 0,30 0,35 0,40

Fig 14.1 – Convergence de l’approximation de l’épaisseur minimale d’un arc de
30 voussoirs vers l’épaisseur minimale théorique

(a) (b)

Fig 14.2 – Lignes de pression d’un arc de 30 voussoirs d’épaisseur minimale
t/r = 0,10746 (a), et d’un arc de 11 voussoirs d’épaisseur minimale t/r = 0,10493 (b)

Pour conclure, notons que l’épaisseur minimale d’un arc en pierre de taille sera
supérieure à celles des modèles à « arc inﬁnitésimal » mentionné ci-dessus pour des
raisons de coupe des pierres : présence d’une clé (nombre impair de voussoirs), et
nombre ﬁni et limité de voussoirs (ﬁg. 14.2).

14.1.3 Épaisseur minimale d’un dôme hémisphérique

Nous notons t l’épaisseur d’un dôme hémisphérique et r son rayon moyen.

L’épaisseur minimale d’un dôme hémisphérique a été étudiée par Heyman (1967a),
Lau (2006), Zessin (2012) et Coccia et al. (2016), avec des méthodes diﬀérentes, et
des résultats proches mais non identiques.

241

<!-- p. 243 -->

Chapitre 14. Étude des arcs et dômes

Heyman considère un dôme avec des forces d’anneaux. Il indique que l’épaisseur
minimale d’un dôme hémisphérique vaut (t/r)min = 0,0420, et que l’épaisseur se réduit progressivement jusqu’à atteindre zéro lorsque l’angle d’ouverture α du dôme
est inférieur à ϕc = 51,8◦. L’évolution de l’épaisseur minimale en fonction de l’angle
d’ouverture α, suivant Heyman (1967a) et Lau (2006) avec des forces d’anneaux, et
suivant Zessin (2012) sans forces d’anneaux est donnée sur la ﬁgure 14.3.

Fig 14.3 – Épaisseur minimale d’un dôme sphérique en fonction de son angle
d’ouverture, d’après Zessin (2012, p. 53)

Pour le cas du dôme hémisphérique complet (α = 90◦), qui sera le seul cas étudié
dans la suite, les épaisseurs minimales valent :
— (t/r)min = 0,0420 (Heyman, 1967a)
— (t/r)min = 0,041 (Lau, 2006)
— (t/r)min = 0,043 (Zessin, 2012)
— (t/r)min = 0,0452 (Coccia et al., 2016)
Coccia et al. (2016) donnent une épaisseur minimale de (t/r)min = 0,0452, qui ne
peut cependant pas être directement comparée aux épaisseurs précédentes. En eﬀet,
ils recherchent l’épaisseur minimale pour pouvoir dessiner la caténaire d’un dôme à
l’intérieur de ce dôme. Cette recherche n’est pas identique à celle de l’épaisseur minimale du dôme stable. En eﬀet dans le premier cas la position des charges appliquées
se trouvent au centre de gravité des voussoirs inﬁnitésimaux, alors que dans le second
cas, la position des charges appliquée se trouvent au niveau de la caténaire. Le résultat proposé par Coccia et al. n’est donc pas une réévaluation du résultat de Heyman,
mais la recherche d’une épaisseur minimale répondant à un problème diﬀérent. La
distinction entre épaisseur minimale pour dessiner la caténaire et l’épaisseur minimale
pour assurer la stabilité d’un arc est soulignée par Makris et Alexakis (2013) dans le
cas de l’arc en plein-cintre. Cette diﬀérence trouve une illustration dans les points de
passage de la ligne de pression trouvée par Heyman, Lau et Zessin, et par la « surface
de pression » (la caténaire d’un dôme) trouvée par Coccia et al. Tandis que les lignes
de pression de Heyman, Lau et Zessin ne touchent pas l’intrados ni l’extrados à la
clé, la « surface de pression » de Coccia et al. touche l’intrados à la clé (comparer
ﬁgures 14.4 et 14.5). Ce résultat ne sera donc pas considéré pour la comparaison dans

242

<!-- p. 244 -->

Chapitre 14. Étude des arcs et dômes

la suite.

Fig 14.4 – Équilibre d’une lune d’un dôme hémisphérique d’épaisseur minimale
(à g.), et mécanisme de ruine correspondant pour le dôme (à d.), d’après Heyman
(1967a)

Fig 14.5 – « surface de pression » (caténaire) touchant le dôme le plus petit la
contenant, d’après Coccia et al. (2016)

Selon un principe présenté par Poleni, et repris par Heyman (1967a), le dôme
étudié est découpé en secteurs angulaires (ﬁg. 14.6 au centre), que nous appellerons
lunes dans la suite. L’étude de la stabilité du dôme est ramenée à celle de ses lunes.

Nous étudions l’épaisseur minimale de deux lunes opposées composées d’un total
de 30 voussoirs (15 voussoirs par lune). L’ouverture angulaire dans le plan horizontal
d’une lune vaut δθ = 1◦(lune d’ouverture angulaire 10 fois plus faible que celles
représentées sur la ﬁgure 14.6). Nous ne considérons pas de forces d’anneaux.

L’étude de l’épaisseur minimale de ces lunes à l’aide des réseaux de forces avec
considération des joints est donnée sur la ﬁgure 14.7. L’estimatif de l’épaisseur minimale trouvée pour ces lunes à 15 voussoirs vaut t/r/γ = 0,0428, et est donc supérieur
à la valeur donnée par Heyman (qui utilise des forces d’anneaux) et inférieur à celle
Zessin (qui n’utilise pas de forces d’anneaux). La considération d’un découpage avec
un plus grand nombre de voussoirs tendra à faire augmenter la valeur t/r/γ = 0,0428,
et donc à s’écarter potentiellement (3) encore un peu plus de la valeur de Heyman de

(3). Pour les tests réalisés avec 30, 31, 33, 35, 45, 46, 47, 59, 60, 61, 70, 79, 92, 93, 105 et 111 voussoirs

243

<!-- p. 245 -->

Chapitre 14. Étude des arcs et dômes

(a) (b) (c)

Fig 14.6 – Découpage d’un dôme hémisphérique en lunes de 10◦d’ouverture (a),
lune isolée (b), et découpage d’une lune en 15 voussoirs (c)

(t/r)min = 0,0420. Le calcul avec les mêmes paramètres géométriques et une ouverture angulaire très faible (δθ = 0,01◦) donne le même résultat t/r/γ = 0,0428.

t/r/γ

0,0450 6.78431
\=

γ
0,0440 4.60677 3.47722 =
γ
\=

γ 0.4674 0.98107 2.3288=
\= = γ
0,0430 γ γ
(t/r)min = 0.043 (Zessin)

0,0420
(t/r)min = 0.0420 (Heyman)

0,0410
(t/r)min = 0.041 (Lau)
t/r
0,00 0,05 0,10 0,15 0,20 0,25 0,30

Fig 14.7 – Convergence de l’approximation de l’épaisseur minimale d’une lune de
15 voussoirs

La recherche des épaisseurs minimales en tenant compte des forces d’anneaux
pose des diﬃcultés pour les processus d’optimisation utilisés pour la recherche du
coeﬃcient de sécurité maximal (non convergence), et nous n’avons pas réussi à trouver
de résultats plus proches de la valeur de Heyman en considérant des forces d’anneaux.

par lune, la valeur t/R/γ est comprise entre 0,04275 et 0,04284. Nota : la variation de t/R/γ n’est
pas une fonction monotone du nombre de voussoirs, puisqu’elle dépend de la proximité des joints les
plus proches des joints critiques.

244

<!-- p. 246 -->

Chapitre 14. Étude des arcs et dômes

Fig 14.8 – Ligne de pression d’une lune d’épaisseur minimale t/r = 0,428

14.2 Étude des procédés historiques de calcul des voûtes

L’extension de la méthode des réseaux de forces permet d’étudier les procédés
historiques de calcul des voûtes. En eﬀet, chaque procédé historique met en jeu d’une
part un ensemble d’hypothèses (considérer une limite de résistance en compression
pour les joints ou non, considérer des joints sans frottement ou non, utiliser la position
exacte ou approchée des centres de gravité etc.) et d’autre part une technique de calcul
pour obtenir les résultats (statique graphique et autres techniques basées sur le dessin,
calculs analytiques, calculs numériques, etc.).

Le développement d’outils numériques qui peuvent reproduire chaque technique de
calcul de chaque procédé historique est possible, mais demande une implémentation
spéciﬁque pour chacun d’entre eux. Ce problème peut être contourné avec l’extension
de la méthode des réseaux de forces proposée dans cette thèse.

En pratique, les hypothèses à la base des procédés historiques (p. ex. joints sans
frottement etc.) sont transformées en une fonction de coût et en des critères mathématiques utilisant des coeﬃcients de sécurité locaux et globaux suivant la même
méthodologie que celle présentée dans le cadre du calcul à la rupture (voir section 3.1.2
p. 42). La solution d’équilibre qui serait donnée par la technique de calcul historique
est calculée sans utiliser cette technique de calcul, mais en calculant la solution correspondant à cette fonction de coût et ces critères mathématiques. Cela est possible
car la plupart des méthodes historiques ont leurs hypothèses formulées au niveau des
joints.

En utilisant ce procédé, nous avons ainsi étudié la méthode de Durand-Claye, qui
combine des aspects analytiques et graphiques, et nous avons reproduit les résultats
de son étude de la stabilité du projet de dôme de Bramante pour la basilique SaintPierre de Rome (Ciblac et Fantin, 2015, ﬁgures 14.9 et 14.10).

Nous avons également étudié le théorème des transformations aﬃne de Rankine
(Ciblac et Fantin, 2016). Rankine a démontré un théorème permettant de produire
de nouvelles solutions d’équilibre pour des structures dissymétriques, à partir de solutions connues pour des cas symétriques (Rankine, 1858 ; Huerta Fernández, 2010). Ce
théorème, appelé par Huerta « Rankine’s theorem of blockwork structures », exploite
la conservation de certaines propriétés géométriques dans les transformations aﬃnes.

245

<!-- p. 247 -->

Chapitre 14. Étude des arcs et dômes

(a) (b) (c)

Fig 14.9 – Projet de dôme pour Saint-Pierre de Rome par Bramante (a), découpage
en blocs pour étude dôme (b), schéma de principe des « aires de stabilité » (c),
d’après Durand-Claye (1880)

(a) (b)

Fig 14.10 – Superposition du polygone funiculaire (a), et des coeﬃcients de sécurité
statiques (b), sur le dessin d’après Durand-Claye (1880)

246

<!-- p. 248 -->

Chapitre 14. Étude des arcs et dômes

Nous considérons une transformation aﬃne de facteur 2 relativement au plan Oyz,
qui transforme un dôme hémisphérique d’épaisseur constante en un dôme elliptique
d’épaisseur variable. L’application du théorème des transformations aﬃne de Rankine
a pour corollaire que le coeﬃcient de sécurité géométrique des deux structures est
identique. En utilisant les propriétés de symétrie, seul un quart du dôme est modélisé.
Le dôme hémisphérique et sa transformation aﬃne sont représentés sur la ﬁgure 14.11.
Sur cette ﬁgure, les blocs beiges représentent le découpage en blocs du quart de dôme,
et les blocs rouges représentent les blocs d’appuis. Les forces d’anneaux ne sont pas
considérées dans la suite. Chaque dôme est divisé en 9 lunes (4) de 10◦d’ouverture
dans le plan horizontal.

Fig 14.11 – Dôme hémisphérique (à g.) et dôme elliptique (à d.)

Nous avons calculé le coeﬃcient de sécurité géométrique avant et après la transformation aﬃne de manière à illustrer le théorème de Rankine, en utilisant la méthode
des réseaux de forces (ﬁg. 14.11). Le coeﬃcient géométrique de sécurité vaut 2,3353
pour toutes les lunes, à la fois pour le dôme hémisphérique, et pour le dôme elliptique
obtenu par transformation aﬃne (ﬁg. 14.12).

Ce résultat est bien celui attendu selon le théorème de Rankine. Cette comparaison permet de valider la qualité du résultat obtenu avec la méthode des réseaux
de forces, en l’appliquant à un cas extrême, ici un dôme elliptique dont le grand axe
est le double du petit axe. Cette étude est purement formelle et ne représente pas le
fonctionnement réel d’un dôme elliptique. En eﬀet, l’appareil utilisé pour les calculs
du dôme elliptique, du fait de la transformation aﬃne, n’est pas adapté à la forme
du dôme.

(4). Le principe du découpage en lunes a été présenté précédemment dans la partie concernant
l’épaisseur minimale des dômes hémisphériques (section 14.1.3 p. 241).

247

<!-- p. 249 -->

Chapitre 14. Étude des arcs et dômes

Fig 14.12 – Dôme elliptique et le réseau de forces correspondant au coeﬃcient de
sécurité géométrique maximum

248

<!-- p. 250 -->

Chapitre 15

Étude des plates-bandes

Résumé : Ce chapitre traite de l’inﬂuence de la coupe des pierres sur la stabilité des
plates-bandes. Trois types de plates-bandes sont analysés : les plates-bandes à joints
verticaux, à joints inclinés, et à joints en X. Les domaines des chargements potentiellement supportables, qui sont utilisés pour quantiﬁer la stabilité, sont déterminés
d’abord par calcul analytique, puis étendus avec les réseaux de forces. L’intégration
des résultats de modèles aux éléments ﬁnis est envisagée.

Sommaire
15.1 Paramétrisation des plates-bandes . . . . . . . . . . . . . . . . . . 250
15.2 Domaines des chargements supportables analytiques . . . . . . . . 253
15.2.1 Contexte . . . . . . . . . . . . . . . . . . . . . . . . . . . . 253
15.2.2 Frontière du critère de résistance en compression . . . . . 253
15.2.3 Frontière du critère de résistance en frottement . . . . . . 256
15.3 Inﬂuence de la coupe des pierres sur la stabilité . . . . . . . . . . 257
15.3.1 Exemples considérés, Prato et GAIA . . . . . . . . . . . . 257
15.3.2 Inﬂuence du nombre de claveaux et de la clé . . . . . . . . 259
15.3.3 Inﬂuence de l’inclinaison des joints . . . . . . . . . . . . . 259
15.3.4 Inﬂuence des joints en X . . . . . . . . . . . . . . . . . . . 261
15.4 Extension des domaines avec les réseaux de forces . . . . . . . . . 263
15.4.1 Principe de construction des domaines avec les réseaux de
forces . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 263
15.4.2 Plates-bandes à joints inclinés . . . . . . . . . . . . . . . . 264
15.4.3 Plates-bandes à joints en X . . . . . . . . . . . . . . . . . 265
15.5 Modèle aux éléments ﬁnis . . . . . . . . . . . . . . . . . . . . . . . 270
15.5.1 Contexte . . . . . . . . . . . . . . . . . . . . . . . . . . . . 270
15.5.2 Modèle Cast3M des plates-bandes . . . . . . . . . . . . . . 270
15.5.3 Solutions d’équilibre . . . . . . . . . . . . . . . . . . . . . 272

249

<!-- p. 251 -->

Chapitre 15. Étude des plates-bandes

15.1 Paramétrisation des plates-bandes

Géométrie des plates-bandes à joints inclinés et verticaux

Nous choisissons les caractéristiques suivantes pour décrire la géométrie des platesbandes qui seront étudiées dans ce chapitre (ﬁg. 15.1) :
— nombre de claveaux k ;
— portée Lm mesurée à mi-hauteur ;
— hauteur h ;
— largeur b ;
— angle ϕ des joints des sommiers avec la verticale.
La coupe des pierres des plates-bandes à joints inclinés est obtenue à partir de
ces paramètres par application de la méthode des divisions égales (voir section 6.3.5
p. 110), décrite notamment par Frézier (1738). Cette méthode a l’avantage, pour
le calcul analytique, de diviser la plate-bande en k claveaux de même masse, dont
l’intersection du joint avec l’axe de la plate-bande (pris à mi-hauteur) est le même
que ceux des plates-bandes à joints verticaux ou joints en X. De plus, lorsque l’angle
ϕ varie :
— la position de l’intersection des joints avec l’axe de la plate-bande est inchan-
gée ;
— la masse de chaque claveau est inchangé ;
— la masse totale de la plate-bande est inchangée.
La portée libre Li de la plate-bande, mesurée à l’intrados, se déduit des paramètres
donnés ci-dessus avec Li = Lm −h/ tan ϕ.

Lm

h

ϕ

b
Li

Fig 15.1 – Paramétrage de la géométrie des plates-bandes à joints inclinés, avec
blocs d’appui en rouge

Géométrie des plates-bandes à joints en X

Dans le cas particulier des plates-bandes à joints en X, nous reprenons la paramétrisation des voûtes plates d’Abeille introduite par Brocato et Mondardini (2014), et
présentée précédemment le chapitre consacré aux voûtes plates (section 10.3.4 p. 196 ;
ﬁg. 10.13). Cette paramétrisation peut être utilisée également pour les plates-bandes
à joints en X.

250

<!-- p. 252 -->

Chapitre 15. Étude des plates-bandes

Un demi-claveau d’une plate-bande à joint en X est paramétré avec les longueurs
a, b, c, d et h, et avec l’angle ϕ des joints avec la verticale (ﬁg. 15.2). Ces paramètres
sont reliés par les égalités suivantes :

d = a −h tan ϕ, b = c (15.1)

Les polyèdres sont donc complètement déﬁnis par 4 paramètres. Nous indiquerons
dans la suite les paramètres a, b, h et ϕ. Les paramètres c et d se déduisent des précédents. Pour respecter les notations de la paramétrisation de proposée par Brocato
et Mondardini (2014), la largeur de la plate-bande est donc notée ici 2b, au lieu de b
habituellement pour le reste de ce document.

La distance entre les centres de gravité de deux blocs en contact est p = a + d.
La portée libre Li entre appuis, déﬁnie sur la ﬁgure 15.2, et la portée mesurée à
mi-hauteur Lm, sont :

Li = (k −1)(d + a) + 2d = 2ka −(k + 1)h tan ϕ (15.2)
Lm = k(d + a) = 2ka −kh tan ϕ (15.3)

Pour juger du risque de glissement des joints, il est utile de considérer l’angle ϕ
des joints avec la verticale et l’angle π/2 −ϕ des joints avec l’horizontale.

a −d
ϕ = tan−1 (15.4)
h

Lm
2d

h

ϕ

2a

2b
Li

Fig 15.2 – Paramétrage de la géométrie des plates-bandes à joints en X, avec
blocs d’appui en rouge

Propriétés mécaniques

Nous choisissons les propriétés mécaniques des pierres et des joints des platesbandes suivantes :
— masse volumique de la pierre ρ0 ;
— résistance admissible des joints à la compression σ0 ;
— coeﬃcient de frottement de Coulomb des joints µ, correspondant à un angle
de frottement de tan−1 µ.

251

<!-- p. 253 -->

Chapitre 15. Étude des plates-bandes

Dans toute la partie des calculs des domaines des chargements potentiellement
supportables, nous faisons l’approximation usuelle dans le milieu du bâtiment qui
consiste à considérer que 1 kg = 1 daN pour simpliﬁer les calculs ; la gravité g est
donc prise égale à 10 ms−2 au lieu de 9.81 ms−2, soit une approximation de moins de
2%. Cette approximation est sans conséquence sur la précision des domaines, puisque
les domaines des chargements supportables peuvent être transformés par homothétie
si la masse volumique ρ0 ou la contrainte admissible σ0 change (section 15.4.1).

Paramètres de chargement

Les paramètres de chargement utilisés pour construire le domaine des chargements
potentiellement supportables K sont :
— la charge verticale totale W, qui est la somme d’une charge verticale unifor-
mément répartie sur la plate-bande ;
— la force horizontale H, ou poussée, appliquée par les appuis sur la plate-bande.
Dans le cas des plates-bandes à joints en X, nous considérerons comme force horizontale H la somme des forces horizontales H1 et H2 sur chacune des faces du joint en X
d’appui. Les paramètres de chargement W et H seront adimensionnalisés en utilisant
le poids propre de la plate-bande W0 = ρ0Lmbh.

Nota sur les arcs de décharges et arrière-linteaux

Un arc de décharge surmonte fréquemment les linteaux et les plates-bandes. Il
peut être constitué d’un arc clavé, ou se former naturellement dans la maçonnerie par
encorbellement (ﬁg. 15.3). La construction d’un arc de décharge au-dessus des linteaux
est recommandée par Vitruve (1) (ﬁg. 6.19 p. 102), puis à la renaissance par Alberti
(1485, Livre III Ch.13) (2). L’usage des arcs de décharge est ensuite recommandé
spéciﬁquement au-dessus des plates-bandes lorsque la largeur de ces dernières est
importante, par exemple pour les portes et les devantures de commerces, par Serlio
(1537, 17v).

Fig 15.3 – Arc de décharge se formant par encorbellement dans la maçonnerie,
d’après Rondelet (1805, Pl. LXIX Fig. 4, p. 309)

(1). Voir citation de Vitruve concernant les arcs de décharges, note (7) p. 80.
(2). Relevé par di Teodoro (2012, p. 192).

252

<!-- p. 254 -->

Chapitre 15. Étude des plates-bandes

Par ailleurs, la plate-bande peut n’occuper qu’une partie de l’épaisseur du mur.
Dans ce cas, un arrière-linteau, composé de une ou plusieurs poutres en bois ou en
métal, est implanté à l’arrière de la plate-bande.

La répartition des charges entre ces diﬀérents éléments, plate-bande, arc de décharge et arrière-linteau est complexe ; nous étudions dans ce chapitre la plate-bande
de façon isolée. Pour les études de cas réels, l’interaction entre la plate-bande et son
environnement devra également être prise en compte.

15.2 Domaines des chargements supportables analy-
tiques

15.2.1 Contexte

Nous étudions dans cette section les domaines des chargements potentiellement
supportables des plates-bandes, par un calcul analytique utilisant la construction par
l’intérieur des domaines du calcul à la rupture (voir section 2.1.3 p. 31).

L’objectif de cette partie est d’obtenir des domaines de référence auxquelles pourront ensuite être comparés les domaines obtenus avec la méthode des réseaux de
forces. Nous n’utilisons donc pas dans un premier temps la méthode des réseaux de
forces.

Le calcul des critères de résistance des joints présenté dans la section 3.1.1 (p. 41)
faisait intervenir le repère local x′y′z′ où l’axe x′ était perpendiculaire au joint (ﬁg. 3.1
p. 41). Nous utilisons dans cette section un repère global xyz, où l’axe x est dirigé
selon l’axe de la plate-bande, où l’axe y est parallèle au côté b, et où l’axe z est
parallèle au côté h et orienté vers le bas (ﬁg. 3.2 p. 41).

Les contraintes généralisées de la théorie des poutres M, N et V sont déﬁnies dans
le repère global xyz, indépendamment du repère local x′y′z′ associé à l’inclinaison
éventuelle de chaque joint.
Nous notons Nc = bhσc l’eﬀort normal maximal admissible sur un joint vertical,
et nous utilisons cette valeur pour créer les valeurs adimensionnées suivantes :

n = N/Nc (15.5)
2
m = hM/Nc (15.6)
v = V/Nc de telle manière que : V/N = v/n (15.7)

15.2.2 Frontière du critère de résistance en compression

Rotules plastiques sur appui et à la clé

On considère un critère de résistance à la compression sous la forme générale :

\|m| ≤f(n,v, tan θ) (15.8)

L’angle θ désigne l’angle du joint considéré avec la verticale, généralement diﬀérent
de l’angle ϕ du joint d’appui. La fonction f peut prendre plusieurs formes, suivant le

253

<!-- p. 255 -->

Chapitre 15. Étude des plates-bandes

type de joint considéré :

f(n) = n(1 −n) (joints verticaux) (15.9)
f(n,v, tan θ) = n + v tan θ −(n + v tan θ)2 cos2 θ (joints inclinés) (15.10)
n
f(n, tan θ) = cos2 θ(1 −n) (joints en X) (15.11)

Les expressions des critères donnés ci-dessus pour les joints verticaux et les joints
inclinés sont obtenus en réécrivant dans le repère global xyz les critères exprimés
avec n′, m′ et v′ dans le repère local x′y′z′ et présentés dans la section 3.1.1 p. 41.
Par ailleurs, l’expression du critère pour les joints en X a été établie par Maurizio
Brocato (communication écrite non publiée – voir en annexe C p. 418).

Ces fonctions sont établies à partir d’hypothèses sur la forme des champs de
contrainte sur les joints. Elles sont donc des approximations par l’intérieur de la
frontière du critère de résistance. Dans les cas des joints en X, une extension de ce
domaine est envisageable en considérant des champs de contrainte plus complexes,
mais ce travail n’a pas été réalisé.

Les expressions analytiques des quantités nécessaires pour les calculs sont données
dans la table 15.1 ci-dessous. La plate-bande considérée comprenant k claveaux, avec
k un nombre impair, l’index i désignant les joints dans cette table varie de 1 à k + 1. Le
choix de placer l’axe x à mi-hauteur de la plate-bande, et le découpage par claveaux
égaux, sont essentiels pour obtenir ces expressions applicables aux trois types de
plates-bandes étudiés.

Var. Val. Val. Val. Description

— appui quelconque clé position du joint considéré

k + 1
i 1 i index du joint considéré
2
i −1 k −1
x 0 Lm Lm position du centre du joint
k 2k
W W W
v (k + 2 −2i) eﬀort tranchant
2Nc 2kNc 2kNc

n n n n eﬀort axial

m −m0 LmhNcW x(Lm −x) −m0 LmhNcW x(Lm −x) −m0 moment (x)

W Lm (i−1)(k−i+1) W Lm k2−1
m −m0 hNc k2 −m0 4hNc k2 −m0 moment (i, k)

i −1 1
tan θ tan ϕ (1 −2 ) tan ϕ tan ϕ inclinaison du joint (sauf si
k k joint X)

Table 15.1 – Expressions analytiques pour le calcul des plate-bandes

Soit ϕ′ = tan−1 1 tan ϕ l’inclinaison des joints de la clé de la plate-bande. Pour k
obtenir une approximation intérieure de la frontière du domaine des chargements
supportables, on écrit que le critère est atteint au joint d’appui et au joint de clé,

254

<!-- p. 256 -->

Chapitre 15. Étude des plates-bandes

soit :

\|m0| = |m(x = 0)| = f(n,v(x = 0), tan ϕ) (15.12)
k −1 k −1
m(x = Lm) = f(n,v(x = Lm), tan ϕ′) (15.13)
2k 2k

La somme de ces deux égalités permet d’éliminer l’inconnue hyperstatique m0 :

WLm k2 −1 W W0 W W0 = f n, , tan ϕ + f n, , tan ϕ′ (15.14)
4hNc k2 W0 2Nc W0 2kNc

Le rapport W peut ensuite être exprimé en fonction de n = H = H W0 aﬁn d’obtenir W0 Nc W0 Nc
l’équation de la frontière du domaine, équation exprimée en fonction des paramètres
de chargement W et H : W0 W0

W 4hNc k2 W W0 W W0 = f n, , tan ϕ + f n, , tan ϕ′ (15.15)
W0 W0Lm k2 −1 W0 2Nc W0 2kNc

Dans le cas des critères de résistance en compression de la plate-bande à joints
verticaux ou joints en X, le critère est de la forme |m| ≤f(n, tan θ) et la dépendance en
W dans le terme de droite de l’équation 15.15 disparait. Il s’en déduit une expressionW0
analytique explicite de W en fonction de H permettant de tracer directement la W0 W0
frontière du domaine de chargements lié au critère en compression :

W 8h H k2
\= 1 −W0 H (joints verticaux) (15.16)
W0 Lm W0 k2 −1 Nc W0
W 1 8h H k2
\= 1 −W0 H (joints en X) (15.17)
W0 cos2 ϕ Lm W0 k2 −1 Nc W0

Cependant dans le cas du critère des joints inclinés, l’équation 15.15 n’est pas linéaire
en W , et la détermination de l’expression analytique de la frontière du domaine de W0
chargement n’est pas triviale. Nous utiliserons pour contourner cette diﬃculté un
calcul en perturbation pour représenter graphiquement la frontière des domaines de
chargements correspondant aux joints inclinés.

Rotules plastiques uniquement à la clé

Pour une hauteur de plate-bande donnée, la résistance à l’eﬀort normal d’un
joint incliné est supérieure à celle d’un joint vertical, parce que l’aire de la surface
du joint incliné est plus grande. De façon analogue, les joints des appuis, qui sont
plus inclinés (tan ϕ) que les joints de la clé ( 1 tan ϕ), peuvent supporter des eﬀorts k
normaux plus importants que ces derniers.

L’équation 15.15 donnée ci-dessus est une condition nécessaire mais non suﬃsante
de respect du critère de résistance à la compression. Dans le cas des joints inclinés,
cette condition peut être respectée sans que la condition ξ ≤1 le soit (pour mémoire,
ξh est la hauteur en compression du joint, voir section 3.2 et ﬁg. 3.1). La relation
entre n, v, ϕ et ξ est donnée pour un joint incliné par :

cos2 ϕ (n + v tan ϕ) = ξ (15.18)

255

<!-- p. 257 -->

Chapitre 15. Étude des plates-bandes

Lorsque ξ = 1, cette équation exprimée au niveau du joint de clé
avec ϕ′ = tan−1 1 tan ϕ devient : k

H W0 W W0 1 + tan ϕ′ = (15.19)
W0 Nc W0 2kNc cos2 ϕ′
W
\= 1 2kNc 1 −H W0 (15.20)
W0 tan ϕ′ W0 cos2 ϕ′ W0 Nc

Cette dernière équation est l’expression du domaine des chargements supportables
vis-à-vis du critère de résistance en compression pour les eﬀorts centrés sur les joints.
Le domaine des chargements pour le critère de résistance en compression est l’intersection des deux domaines calculés ci-dessus.

La seconde frontière du domaine revient à tronquer la pointe formée par les domaines paraboliques (p. ex. ﬁg. 15.5). Cet eﬀet est presque négligeable pour les platesbandes où ϕ = 6◦(voir étude de Prato ci-dessous), mais ne peut pas être négligé pour
les plates-bandes avec des angles ϕ = 18◦et ϕ = 30◦qui sont les cas les plus courants
en pratique (ﬁg. 15.5).

Le gain de résistance qui apparaît pour les joints inclinés par rapport aux joints
verticaux illustre la simpliﬁcation qu’introduit l’hypothèse de négliger l’inﬂuence de
la résistance interne de la pierre, et de considérer la résistance du matériau seulement
au niveau des joints. La considération de la résistance interne de la pierre dans le
cadre du calcul à la rupture est possible, mais nécessite encore des développements
pour être intégrée à la méthode des réseaux de forces (voir chapitre 3.3.2).

15.2.3 Frontière du critère de résistance en frottement

Le critère de résistance en frottement s’exprime dans le repère local du joint x′y′z′
sous la forme :
v′ ≤µn′ (15.21)

Ce critère donne pour les joints verticaux et les joints en X :

\|v| ≤µn joints verticaux ou joints en X (15.22)
\|v| ≤µ + tan ϕ joints inclinés (15.23) 1 −µ tan ϕn

En considérant le joint d’appui, qui est le joint dimensionnant pour le critère de
glissement, l’expression des critères permet d’obtenir le domaine des chargements du
critère sous la forme :

W H
≤2µ joints verticaux ou joints en X (15.24)
W0 W0
W µ + tan ϕ H
≤2 joints inclinés, pour W > 0 (15.25)
W0 1 −µ tan ϕ W0
−W ≤2 µ −tan ϕ H joints inclinés, pour W \< 0 (15.26)
W0 1 + µ tan ϕ W0

256

<!-- p. 258 -->

Chapitre 15. Étude des plates-bandes

Dans le cas des joints verticaux où le repère global et local est identique, (n = n′
et v = v′), cette expression se traduit directement en la limitation de l’angle de la
force de réaction sur le joint d’appui :

W
≤µH (15.27)
2

15.3 Inﬂuence de la coupe des pierres sur la stabilité

15.3.1 Exemples considérés, Prato et GAIA

Nous étudions dans ce chapitre l’inﬂuence de la coupe des pierres sur la stabilité
des plates-bandes. La stabilité est exprimée ici à travers les domaines des chargements potentiellement supportables K, dont les paramètres de chargement sont le
chargement vertical total W et la poussée H (voir section 15.1 pour la déﬁnition des
notations utilisées).

Cette étude prendra pour point de départ deux plates-bandes diﬀérentes.

La première sera la plate-bande à joints en X de la cathédrale de Prato (Toscane,
Italie – voir ﬁgures 7.2 et 6.12 p. 142). Cette plate-bande, construite au Moyen Âge,
présente parmi l’ensemble des exemples répertoriés dans notre chapitre sur les platesbandes une grande hauteur par rapport à sa portée, et des angles de joints avec la
verticale très faibles.

La seconde plate-bande étudiée sera la plate-bande à joints en X construite dans
le cadre d’une étude expérimentale aux Grands Ateliers de l’Isle d’Abeau (GAIA), en
mars 2017 (section 7.4.2 p. 147). La typologie de cette plate-bande a été choisie pour
correspondre aux préconisations des traités d’architecture et de coupe des pierres
du xviiie siècle (3).

La paramétrisation du modèle de plate-bande pour Prato est la suivante :
— géométrie :
— nombre de claveaux k = 5 ; la plate-bande de Prato est composée de
sept claveaux, mais deux claveaux de la plate-bande appuyés sur des cor-
beaux sont considérés comme faisant partie des appuis de la plate-bande ;
— portée (4) Lm = 1,579 m mesurée à mi-hauteur ;
— hauteur h = Li/2 = 0,75 m, ce qui correspond à la proportion observée sur
photo ;
— largeur (5) 2b = h/2 = 0,375 m ;
— base d’un trapèze 2a = 39,4 cm ;

(3). Il n’existe cependant pas de plate-bande de ce type au xviiie siècle en France. Les paramètres
choisis correspondent à ceux des plates-bandes à joints inclinés.
(4). La portée réelle de la plate-bande de Prato n’était pas connue au moment de l’étude. La
valeur donnée ici était hypothétique. La distance entre piédroits vaut 1,5 m environ, et la portée
des cinq claveaux centraux mesuré à mi-hauteur environ 1,1 m. La portée choisie ici pour le calcul,
Lm = 1,579 m mesurée à mi-portée est donc supérieure à la portée réelle. Elle correspond à une portée
Li = 1,500 m mesurée à l’intrados si ϕ = 6◦.
(5). La largeur réelle de la plate-bande de Prato n’est pas connue. La valeur donnée ici est hypothétique.

257

<!-- p. 259 -->

Chapitre 15. Étude des plates-bandes

— angle des joints de ses sommiers avec la verticale ϕ = 6◦; cet angle corres-
pond à une règle de « 1 pour 9 » environ dans le cas des plates-bandes à
joints inclinés.
— propriétés mécaniques :
— masse volumique (6) ρ0 = 2400 kg/m3 ;
— résistance admissible des joints à la compression σ0 = 1,0 MPa ;
— coeﬃcient de frottement de Coulomb des joints µ = 0,7.
Lampariello indique, concernant le système des claveaux bicolores en Toscane, que
les pierres blanches provenaient généralement de Albarese, et les pierres foncées de
Serpentino (7) (Lampariello, 2012, p. 107). Les valeurs des propriétés mécaniques cidessus sont hypothétiques et négligent les possibles diﬀérences entre pierre blanche
et pierre verte.

La paramétrisation du modèle de plate-bande pour la plate-bande construite aux
Grands Ateliers de l’Isle-d’Abeau (GAIA) est la suivante :
— géométrie :
— nombre de claveaux k = 7 ;
— portée (8) Lm = 1,400 m mesurée à mi-hauteur ;
— hauteur h = 0,30 m, ce qui correspond à un rapport Lm/h compris entre 4
et 5 ;
— largeur 2b = h = 0,30 m ;
— angle des joints de ses sommiers avec la verticale ϕ = 18,4◦; cet angle
correspond à une règle de « 1 pour 3 » dans le cas des plates-bandes à
joints inclinés.
— propriétés mécaniques :
— masse volumique ρ0 = 2200 kg/m3 ;
— résistance admissible des joints à la compression σ0 = 1,0 MPa ;
— coeﬃcient de frottement de Coulomb des joints µ = 0,7.
Nous appellerons dans la suite plate-bande de type GAIA les plates-bandes de ce
type.

Chacune de ces deux plates-bandes sera étudiée sous trois formes, présentant
toutes la même portée à mi-hauteur (9) :
— sous sa forme de base, à joints en X ;
— sous la forme d’une plate-bande de mêmes dimensions mais à joints inclinés ;
— sous la forme d’une plate-bande de mêmes dimensions mais à joints verticaux.
Pour chacune de ces plates-bandes, un seul des paramètres décrivant sa typologie,
et donc sa coupe des pierres, sera modiﬁé successivement pour étudier l’eﬀet de ce

(6). Le poids des claveaux est obtenu en multipliant leur masse par la gravité prise égale à 10 m.s−2.
Cela revient à utiliser l’approximation usuelle dans le bâtiment « 1 kg = 1 daN ». L’incidence de cette
approximation sur les domaines des chargements potentiellement supportables est abordée p. 252.
(7). « Bien que les édiﬁces construits en pierres bicolores se soient répandus dans diverses régions de
la côte italienne, où le modèle arabe d’ornement bicolore, nommé ablaq, est plus connu, c’est [ce] n’est
qu’en Toscane que l’on rencontre fréquemment la solution de surmonter les portails d’architraves en
claveaux alternés de pierres claires et de pierres foncées, généralement en pierre blanche (Albarese)
et en marbre vert de Prato (Serpentino), au lieu de blocs monolithes. » (Lampariello, 2012, p. 107)
(8). La portée mesurée à mi-hauteur Lm = 1,400 m correspond à une portée Li = 1,300 m mesurée
à l’intrados si ϕ = 18,4◦.
(9). Pour les raisons vues lors de la présentation du paramétrage des plates-bandes, de manière à
exploiter les avantages de la méthode des divisions égales.

258

<!-- p. 260 -->

Chapitre 15. Étude des plates-bandes

paramètre sur les domaines des chargements supportables, et donc sur la stabilité de
la plate-bande.

Les domaines des chargements supportables présentés dans cette section sont déterminés analytiquement, à l’aide des expressions établies dans la section précédente.

15.3.2 Inﬂuence du nombre de claveaux et de la clé

Nous avons vu dans la partie sur l’histoire des plates-bandes que ces dernières
présentent presque systématiquement un nombre impair de claveaux, et donc une clé
placée au centre de la portée.

L’existence de la clé apporte une résistance complémentaire à la plate-bande par
rapport à une plate-bande équivalence construite avec un nombre pair de claveaux,
quel que soit le type de joint (vertical, incliné, ou en X). Le rapport entre la résistance
d’une plate-bande avec un nombre impair de claveaux k et celle d’une plate-bande
k2
avec un nombre pair de claveaux (quel que soit ce nombre), est donné par k2−1. Ce
rapport vaut 1,123 pour une plate-bande à 3 claveaux, 1,042 pour une plate-bande à
5 claveaux, et 1,020 pour une plate-bande à 7 claveaux. La modiﬁcation du domaine
des chargements potentiellement supportables due à ce paramètre est illustrée sur la
ﬁgure 15.4.

Le nombre de claveaux et la présence d’une clé centrale a donc une inﬂuence non
nulle sur la stabilité, mais qui reste faible. Frézier indique à ce propos, concernant
le choix de la position des joints pour les voûtes en général : « ce n’est pas qu’un
joint sur le milieu d’un ceintre tirât beaucoup de conséquence pour la solidité ; mais
il choqueroit la vuë & la bonne ordonnance. » (Frézier, 1737, p. 280, cit. 29).

15.3.3 Inﬂuence de l’inclinaison des joints

Une plate-bande à joints verticaux a une résistance égale que les chargements verticaux soient orientés vers le haut ou vers le bas (symétrie visible sur la ﬁgure 15.4).
Cette symétrie n’existe pas pour les plates-bandes à joints inclinés (ﬁg. 15.5). L’inclinaison des joints a trois eﬀets :

\1. le critère de résistance au frottement est impacté par l’orientation du joint ;

\2. le critère de résistance en compression est impacté par la variation de l’aire de
la surface des joints (dépendant de l’orientation du joint) ;

\3. la portée eﬀective de la plate-bande, c’est-à-dire la distance horizontale entre
les centres de pression sur les joints d’appuis est impactée par l’orientation du
joint.

Lorsque l’inclinaison des joints augmente, la frontière du domaine des chargements
supportables lié au critère du frottement tourne dans le sens anti-horaire. Par conséquent, pour une faible poussée donnée H, les charges verticales admissibles (positives
ou négatives) se déplacent vers le haut dans le plan (H; W) (ﬁg. 15.5).

Pour les chargements verticaux orientés vers le bas, les eﬀets 2. et 3. mentionnés
ci-dessus s’additionnent et le domaine des chargements supportables grandit lorsque
l’inclinaison des joints augmente (en haut sur la ﬁgure 15.5).

259

<!-- p. 261 -->

Chapitre 15. Étude des plates-bandes

Pour les chargements verticaux orientés vers le haut, les eﬀets 2. et 3. mentionnés
ci-dessus ont des eﬀets contraires, car cette fois-ci la portée eﬀective de la plate-bande
augmente en même temps que l’inclinaison des joints. Sur l’exemple considéré, l’eﬀet
\2. est supérieur à l’eﬀet 3 pour les poussées importantes (ﬁg. 15.5 (b)), et l’eﬀet 2. est
inférieur à l’eﬀet 3 pour les poussées faibles (ﬁg. 15.5 (a)).

Enﬁn, l’augmentation de la résistance aux eﬀorts normaux apportée par l’inclinaison des joints a pour résultat que les deux joints des clés sont moins résistants que les
joints d’appuis. Pour les fortes poussées et faibles chargements verticaux, le critère de
résistance à la compression n’est pas atteint à la fois sur les joints d’appuis et sur les
joints des clés, mais uniquement sur les joints des clés où les joints sont complètement
écrasés (ξ = 1). Cet eﬀet n’est presque pas perceptible lorsque l’inclinaison des joints
d’appuis ϕ vaut 6◦, mais il apparaît nettement pour ϕ = 18◦et ϕ = 30◦(ﬁg. 15.5 (c)).

L’augmentation de la résistance à l’eﬀort normal avec l’augmentation de l’angle
des joints est liée à l’absence de considération de la résistance à l’intérieur des pierres
(voir section 15.2.2 p. 255).

W
W0

20

0

−20

H
W0
0 5 10 15 20 25 30
k = 3 k = 5 k = 7 k = ∞

si µ = 0,7 si µ = ∞

Fig 15.4 – Inﬂuence du nombre de claveaux k sur le domaine des chargements
supportables d’une plate-bande à joints verticaux de type Prato

260

<!-- p. 262 -->

Chapitre 15. Étude des plates-bandes

W
W0

20

(c)

0

−20 (a) (b)

H
W0
0 5 10 15 20 25 30
ϕ = 6◦ ϕ = 18◦ ϕ = 30◦

si µ = 0,7 si µ = ∞

Fig 15.5 – Inﬂuence de l’inclinaison des joints d’appui ϕ sur le domaine des
chargements supportables d’une plate-bande à joints inclinés de type Prato

15.3.4 Inﬂuence des joints en X

Les domaines des chargements supportables d’une plate-bande à joints verticaux,
joints inclinés et joints en X sont superposés sur la ﬁgure 15.6 pour les plates-bandes
de type Prato, et sur la ﬁgure 15.7 pour les plates-bandes de type GAIA.

Les plates-bandes à joints en X procurent une meilleure résistance vis-à-vis des
chargements verticaux inversés (vers le haut) par rapport à la plate-bande à joints
inclinés. Les chargements verticaux inversés pourraient se produire en pratique dans
le cas de séismes.

Dans le cas de la plate-bande à joints en X de Prato, le domaine des chargements
supportables est presque identique à celui de la plate-bande à joints verticaux. Avec
celle de type GAIA cependant, le domaine est plus grand que celui de la platebande à joints verticaux. De plus, contrairement aux joints verticaux dont la stabilité
peut être remise en question par de petits mouvements horizontaux au niveau des
appuis (Smars, 2008), la plate-bande à joints en X est plus sécuritaire vis-à-vis des
déplacements horizontaux des supports.

La forme de la plate-bande de Prato, qui présente un rapport portée sur hauteur Lm/h d’environ 2, explique que le critère de frottement joue un rôle important
sur le comportement mécanique.

A contrario, le critère de frottement n’apparaît presque pas pour les chargements
verticaux dirigés vers le bas de la plate-bande de type GAIA.

261

<!-- p. 263 -->

Chapitre 15. Étude des plates-bandes

W
W0

20

0

−20

H
W0
0 5 10 15 20 25 30

Joints verticaux Joints inclinés Joints en X
µ = 0,7 µ = 0,7 µ = 0,7
µ = ∞ µ = ∞ µ = ∞

Fig 15.6 – Domaines des chargements supportables de plates-bandes de type Prato
à joints verticaux, inclinés, et en X

W
W0

10

0

−10

H
W0
0 5 10 15 20 25 30 35

Joints verticaux Joints inclinés Joints en X
µ = 0,7 µ = 0,7 µ = 0,7
µ = ∞ µ = ∞ µ = ∞

Fig 15.7 – Domaines des chargements supportables de plates-bandes de type GAIA
à joints verticaux, inclinés, et en X

262

<!-- p. 264 -->

Chapitre 15. Étude des plates-bandes

15.4 Extension des domaines avec les réseaux de forces

15.4.1 Principe de construction des domaines avec les réseaux de
forces

Les domaines des chargements supportables présentés ci-dessus et déterminés
à partir d’équations analytiques des frontières seront appelés domaines analytiques
(qu’ils aient été dessinés à partir d’expressions analytiques ou par calcul itératif).
Nous comparons dans cette section ces domaines analytiques avec les domaines
des chargements supportables qui peuvent être construits grâce à l’extension de la
méthode des réseaux de forces. Nous appellerons domaines numériques ces domaines
pour les distinguer des domaines analytiques précédents.
La procédure suivante est appliquée pour construire les domaines numériques K
présentés dans la suite. Pour une poussée horizontale donnée H = ¯H et un chargement
vertical W = ¯W = W0, nous avons calculé le multiplicateur de charge de la platebande F(¯H; ¯W). D’après la déﬁnition de ce multiplicateur, le point F ¯H; FW0 se
trouve à l’intérieur du domaine des chargements potentiellement supportables K. Le
domaine convexe déﬁni par itération en des points successifs est une approximation
par l’intérieur du domaine K (ﬁg. 15.8).

W
W0

(F H,¯ F W¯ )
( H,¯ W¯ )

H
W0

Fig 15.8 – Construction par l’intérieur du domaine des chargements supportables

Le multiplicateur de charge lié au critère en résistance en compression est proportionnel à σ0 (equation 3.23). Par conséquent, le domaine des chargements supportables correspondant à une contrainte admissible σ2 peut être déduit d’un domaine
σ1 simplement en transformant ce dernier domaine par une homothétie de facteur
σ2/σ1.
Par ailleurs, la masse volumique de la pierre n’intervient que via les termes 1/W0
qui servent à rendre adimensionnels les paramètres de chargements, pour la construction des domaines. Les domaines peuvent donc également être transformés par homothétie si la masse volumique change. Par conséquent, la forme des domaines des
chargements supportables produits dans ce document (pour les plates-bandes et les
voûtes plates) sont indépendants des caractéristiques prises pour caractériser la pierre
et les joints (masse volumique et résistance en compression), à l’exception notable du
coeﬃcient de frottement limite µ.

263

<!-- p. 265 -->

Chapitre 15. Étude des plates-bandes

15.4.2 Plates-bandes à joints inclinés

La superposition des domaines analytiques et numériques pour le cas des platesbandes à joints inclinés de type Prato et de type GAIA montre la bonne concordance
des résultats obtenus par calcul analytique et par la méthode des réseaux de forces
(ﬁgures 15.9 et 15.10). Cette bonne correspondance était attendue puisque dans le cas
des joints inclinés, aucune hypothèse simpliﬁcatrice complémentaire n’a été introduite
lors des calculs analytiques des critères, contrairement aux joints en X que nous allons
étudier maintenant.

W
W0

20

0

−20

H
W0
0 5 10 15 20 25 30
Analytique µ = 0,7 Analytique µ = ∞
Numérique µ = 0,7 Numérique µ = ∞

Fig 15.9 – Comparaison des domaines analytiques et numériques d’une plate-bande
à joints inclinés de type Prato

W
W0

10

0

−10

H
W0
0 5 10 15 20 25 30 35
Analytique µ = 0,7 Analytique µ = ∞
Numérique µ = 0,7 Numérique µ = ∞

Fig 15.10 – Comparaison des domaines analytiques et numériques d’une plate-bande
à joints inclinés de type GAIA

264

<!-- p. 266 -->

Chapitre 15. Étude des plates-bandes

15.4.3 Plates-bandes à joints en X

Première approche des domaines de chargement

La superposition des domaines analytiques et numériques pour le cas des platesbandes à joints en X de type Prato et de type GAIA montre que la méthode des réseaux de forces permet de générer des domaines de chargements potentiellement supportables plus grands qu’avec la méthode analytique utilisée ci-dessus (ﬁgures 15.11
et 15.12). Cette observation doit cependant être relativisée, car une partie du domaine
généré avec la méthode des réseaux de forces doit être exclu.

W
W0

(a)

20

0

−20

(a)
H
W0
0 5 10 15 20 25
Analytique µ = 0,7 Analytique µ = ∞
Numérique µ = 0,7 Numérique µ = ∞

Fig 15.11 – Comparaison des domaines analytiques et numériques d’une plate-bande
à joints en X de type Prato

W
W0

(a)

10

0

−10

(a) H
W0
0 5 10 15 20 25 30 35
Analytique µ = 0,7 Analytique µ = ∞
Numérique µ = 0,7 Numérique µ = ∞

Fig 15.12 – Comparaison des domaines analytiques et numériques d’une plate-bande
à joints en X de type GAIA

En eﬀet, si le critère de résistance en frottement est négligé, le domaine
des chargements supportables calculé avec la méthode des réseaux de forces présente
des caractéristiques particulières :

265

<!-- p. 267 -->

Chapitre 15. Étude des plates-bandes

— alors que la charge verticale extrême W maximale ne peut être atteinte que
pour une seule valeur de la poussée pour une plate-bande à joints inclinés
(au sommet de la parabole du domaine), pour les plates-bandes à joints en X
la charge verticale extrême W maximale peut être atteinte sur un intervalle
de valeur de la poussée, qui correspond à la frontière horizontale du domaine
(ﬁg. 15.11 (a) et ﬁg. 15.12 (a)). Par conséquent, plusieurs solutions d’équilibre
distinctes équilibrant le chargement vertical extrême maximal existent. Trois
solutions avec ou sans transmission de forces entre les deux parties composant
les claveaux à joints en X sont donnés sur la ﬁgure 15.13.
— les plates-bandes à joints en X sont stables même pour des poussées inﬁnité-
simales. Ces solutions nécessitent des transmissions d’eﬀorts importants entre
les deux parties composant les claveaux à joints en X (ﬁg. 15.14 à droite).
Nous retrouverons une caractéristique similaire dans le cas des voûtes plates
d’Abeille.
Les solutions correspondant à la frontière horizontale du domaine (ﬁg. 15.11 (a)
et ﬁg. 15.12 (a)) ne respectent pas le critère de résistance en frottement, et sont
susceptible de ne pas respecter deux autres critères qui ne sont pas pris en compte
dans le calcul des domaines eﬀectué ici, et que nous détaillons ci-dessous.

Fig 15.13 – Trois solutions équilibrant le même chargement vertical extrême W si
µ = ∞, avec diﬀérentes forces verticales dans les branches partielles (0 kg, 500 kg et
2000 kg) ; solutions correspondant à la frontière horizontale (a) sur ﬁg. 15.11

Fig 15.14 – Deux solutions équilibrant un chargement extrême si µ = ∞
(H = 1600 kg à g. et H = 50 kg à d.)

Par ailleurs, les solutions d’équilibre données sur les ﬁgures 15.13 et 15.14 sont des
solutions équilibrant un chargement extrême appartenant à la frontière du domaine
des chargements supportables. Ces solutions montrent que le réseau de forces peut
sortir de l’enveloppe intérieure de la maçonnerie, bien que tous les centres de pression
soient localisés sur les joints (voir section 1.3 p. 23).

266

<!-- p. 268 -->

Chapitre 15. Étude des plates-bandes

Limitation des eﬀorts dans les branches partielles

Lorsque la poussée considérée est importante, les solutions équilibrant les chargements extrêmes sont obtenues avec des forces verticales très faibles dans les branches
partielles (ﬁg. 15.14 à gauche). Cependant, lorsque la poussée considérée est faible,
les forces dans les branches partielles sont essentielles pour obtenir les solutions correspondant à la frontière horizontale du domaine (ﬁg. 15.11 (a) et ﬁg. 15.12 (a)). Les
valeurs des forces dans les branches partielles de ces solutions peuvent être importantes, et il convient donc d’en limiter l’amplitude.

La force dans une branche partielle se traduit par deux phénomènes :
— l’application de forces sur les joints triangulaires entre deux claveaux successifs
(A2 sur ﬁg. 15.15), pour équilibrer le moment de torsion que nous détaillons
ci-dessous ; ces forces mettent en jeu la résistance des joints entre claveaux ;
— la transmission d’eﬀorts de cisaillement à travers l’interface entre les deux
demi-claveaux d’un même claveau (A1 sur ﬁg. 15.15) ; cette transmission d’ef-
forts à l’intérieur d’un même claveau met en jeu la résistance interne de la
pierre.
L’utilisation des branches partielles introduit un chargement extérieur non équilibré par le réseau de forces, et pour lequel une solution d’équilibre complémentaire se
superposant au réseau de forces doit être trouvée (section 13.3.3 p. 226). Ce chargement extérieur correspond dans le cas des plates-bandes à joints en X à l’application
d’un moment de torsion à chaque claveau égal à bFv avec b la demi-largeur du claveau
et Fv la force verticale dans la branche partielle du claveau (ﬁg. 15.15 (a)). Les faces
triangulaires formant contact entre les claveaux successifs permettent la reprise de ce
moment de torsion (ﬁg. 15.15 (b)).

b
A2
z

A1

(a) (b) (c)

Fig 15.15 – Moment de torsion et surfaces mises en jeu par les forces verticales dans
les plates-bandes à joints en X

La prise en compte de la limitation des forces verticales qui se développent dans
les branches partielles est délicate, car elle demande de considérer la résistance interne
de la pierre. Pour rester dans le cadre de l’approche par l’intérieur du domaine de
résistance du calcul à la rupture, il faudrait alors construire les champs de contrainte
équilibrés et respectant les critères de résistance à l’intérieur de la pierre, en plus des
champs de contrainte sur les joints déjà utilisés ici. Cela amène également à considérer

267

<!-- p. 269 -->

Chapitre 15. Étude des plates-bandes

les autres phénomènes liés à la résistance interne de la pierre (risque de rupture des
angles aigus des claveaux etc.).

Pour estimer l’eﬀet des limitations sur les forces verticales qui se développent
dans les branches partielles, il est envisageable de choisir une borne pour ces forces
verticales. Notons que cette démarche est seulement qualitative et n’est pas rigoureuse
du point de vue du calcul à la rupture, pour les raisons qui viennent d’être évoquées.

Dans le cas de la plate-bande de type GAIA, un ordre de grandeur de la résistance de l’interface entre les deux demi-claveaux est donné
par Fv,max1 = A1 · 10σ01 = 450 kg, avec A1 l’aire entre deux demi-claveaux égale à
450 cm2 (ﬁg. 15.15 (c)). Par ailleurs, l’équilibre du moment de torsion sur les faces
triangulaires avec le moment de torsion des forces verticales donne une autre limite : bFv,max2 = z · 2A2 · σ0, avec A2 = 75 cm2 la surface d’un triangle, z = 20 cm
le bras de levier entre deux triangles, b = 15 cm la demi-largeur de la plate-bande
(ﬁg. 15.15 (b)). Soit Fv,max2 = 2000 kg. Nous retenons comme limite pour les calculs
suivant Fv,max = min(Fv,max1; Fv,max2) = 450 kg.
Nous déﬁnissons un multiplicateur de rupture lié à ce critère : λ = Fv,max/Fv. La
détermination des nouveaux domaines est réalisée comme pour les autres domaines
présentés jusqu’ici, en ajoutant la considération de ce multiplicateur de rupture aux
autres déjà connus, bien que le multiplicateur de rupture déﬁni ne soit pas rigoureux
dans le cadre du calcul à la rupture.

Seconde approche des domaines de chargement

Les nouveaux domaines numériques avec limitation des eﬀorts dans les branches
partielles sont présentés sur la ﬁgure 15.16 dans le cas de la plate-bande à joints
en X de type GAIA. Ils y sont comparés aux domaines analytiques. La limitation des
branches partielles a pour eﬀet de supprimer du domaine les chargements supportables
à très faible poussée visible sur les précédents domaines numériques (ﬁg. 15.12 (a) cidessus).

Le domaine numérique est plus grand que le domaine analytique pour les poussées
importantes (ﬁg. 15.16 (a)). L’utilisation de champs de contrainte plus détaillés pour
déterminer une approximation intérieure du domaine des chargements pourrait peutêtre permettre d’agrandir le domaine analytique pour les poussées importantes, mais
ce travail n’a pas été réalisé.

Le domaine numérique est plus petit que le domaine analytique pour les faibles
poussées (ﬁg. 15.16 (a)). Cela pourrait être du au fait que les eﬀorts internes à la
pierre ne sont pas pris en considération pour les domaines analytiques, contrairement
aux domaines numériques.

268

<!-- p. 270 -->

Chapitre 15. Étude des plates-bandes

W
W0

10 (b)

(a)
0

−10

H
W0
0 5 10 15 20 25 30 35
Analytique µ = 0,7 Analytique µ = ∞
Numérique µ = 0,7 Numérique µ = ∞

Fig 15.16 – Comparaison des domaines analytiques et numériques d’une plate-bande
à joints en X de type GAIA, avec limitation des eﬀorts dans les branches partielles
pour les domaines numériques

269

<!-- p. 271 -->

Chapitre 15. Étude des plates-bandes

15.5 Modèle aux éléments ﬁnis

15.5.1 Contexte

À chacun des chargements extrêmes présentés jusqu’à présent correspond une solution d’équilibre. Les solutions d’équilibre des chargements extrêmes sont des situations limites, et ne représentent pas nécessairement le comportement réel des platesbandes sous des chargements supportables, inférieurs aux chargements limites.

Le calcul à la rupture n’a pas pour but de produire les solutions d’équilibre réelles
se produisant dans la structure, mais de vériﬁer l’admissibilité des chargements, sans
préjuger de l’état d’équilibre réel de la structure sous ce chargement.

Nous proposons dans cette section de comparer qualitativement les solutions
d’équilibre des chargements extrêmes du calcul à la rupture avec celles qui peuvent
être calculées avec un calcul aux éléments ﬁnis, pour observer si des réseaux avec
double funiculaire dont la projection sur le plan frontal s’entrecroisent, comme ceux
visibles sur la ﬁgure 15.13 au centre, se produisent eﬀectivement dans la structure.

15.5.2 Modèle Cast3M des plates-bandes

La modélisation aux éléments ﬁnis est réalisée grâce au programme Cast3M (10).

Le modèle est composé de deux types d’éléments ﬁnis : les éléments ﬁnis volumiques pour les blocs, et les éléments joints pour représenter l’interface entre les blocs.
Les hypothèses principales du modèle sont :
— les blocs ont un comportement linéaire élastique ;
— les joints ont un comportement élasto-plastique ; il s’agit de joints dilatants
3D avec un critère de Mohr-Coulomb et écoulement associé.
Ce choix est basé sur l’hypothèse implicite que la résistance de la pierre est supérieure à celle de l’interface représentée par le joint (11) ; la rupture des constructions
clavées se produit généralement par l’écrasement et l’ouverture des joints, et non par
la rupture de la pierre. Le cas des plates-bandes à joints en X et les voûtes d’Abeille
forment cependant un cas limite où cette hypothèse peut être prise en défaut.

Les caractéristiques des éléments volumiques de la pierre, et des éléments joints
sont donnés respectivement dans les tables 15.2 et 15.3. La raideur normale et la
raideur de cisaillement est obtenue par les égalités suivantes (Mondardini, 2015) :

Em(1 −νm)
Kn,m = (15.28)
t(1 −νm −2ν2m)
Em
Ks,m = (15.29)
2t(1 + νm)

Nous étudions la plate-bande à joints en X de type GAIA (ﬁg. 15.17), utilisée
précédemment pour l’étude de l’inﬂuence des joints. Sur la ﬁgure 15.17, le modèle

(10). Cast3M est un code de calcul développé par le Centre à l’Énergie Atomique (CEA) pour
l’analyse de structures par la méthode des éléments ﬁnis et la modélisation en mécanique des ﬂuides.
Nous avons utilisé la version 2016 du logiciel.
(11). Point souligné dans le cadre de la déﬁnition des coeﬃcients de sécurité pour le calcul à la
rupture, p. 42.

270

<!-- p. 272 -->

Chapitre 15. Étude des plates-bandes

Notation Valeur Description
ρs 2200 kg/m3 masse volumique
vs 2500 vitesse du son (hypothèse)
νs 0,27 coeﬃcient de poisson (hypothèse)
Ks = ρsv2s 13,75 GPa module d’élasticité isostatique
Es = 3Ks(1 −2νs) 18,98 GPa module d’élasticité

Table 15.2 – Caractéristiques de la pierre

Notation Valeur Description
c 0,0 N/m2 cohésion
ϕ = tan−1 µ 35,0◦ angle de frottement limite
ρm 2200 kg/m3 masse volumique
Em 0,005 GPa module d’élasticité
νm 0,00 coeﬃcient de poisson (hyp.)
t 5,0 mm épaisseur
Kn,m 1000 MN/m3 raideur normale (si ε \< εcn,m)
Ks,m 500 MN/m3 raideur de cisaillement
εcn,m 0,05 seuil de déformation
Ef,m 2Kn,m seconde raideur normale (si ε ≥εcn,m)

Table 15.3 – Caractéristiques des joints

est composé des 7 blocs intérieurs en blanc, et de deux blocs rouges représentant
les appuis. Les blocs d’appui ne font pas partie du modèle, ils servent uniquement à
contrôler les déplacements des nœuds des joints d’appuis du côté des blocs d’appuis.

Fig 15.17 – Blocs composant le modèle Cast3M pour la plate-bande de type GAIA,
avec blocs d’appuis en rouge

Le chargement est composé du poids propre de la pierre et des joints, et du
déplacement horizontal des appuis. Il est appliqué en deux phases.
— application du poids propre (pp) ;
— déplacement imposé horizontal des appuis :
— Cas (ec) : écartement des appuis de 1,0 mm ;
— Cas (ra) : rapprochement des appuis de 10,0 mm.
Pour chaque phase, le calcul est réalisé en plusieurs étapes de manière à suivre l’évolution des résultats au fur et à mesure du chargement.
Les calculs sont réalisés sous l’hypothèse des petits déplacements, de manière à
obtenir des solutions d’équilibre sur la géométrie initiale, comparables aux solutions
d’équilibre utilisées pour le calcul à la rupture, qui sont également décrites sur la
géométrie non déformée.

271

<!-- p. 273 -->

Chapitre 15. Étude des plates-bandes

15.5.3 Solutions d’équilibre

Les solutions d’équilibre Sol1, Sol2 et Sol3 correspondent respectivement à la
solution d’équilibre après écartement des appuis (pp+ec), après application du poids
propre seul (pp), et après rapprochement des appuis (pp+ra). La convention de signe
utilisée avec Cast3M est compression négative.

La ﬁgure 15.18 représente les résultantes des forces sur les joints sous la forme
de segments bleus (joints rectangulaires inclinés), de segments verts (joints triangulaires dans la moitié supérieure de la plate-bande) et de segments rouges (joints
triangulaires dans la moitié inférieure de la plate-bande). L’épaisseur des segments est
proportionnelle à la racine carrée de l’intensité des forces. Les longueurs des segments
sont constantes et ne sont pas liées à l’intensité des forces. Les croix noires localisent
le point d’application des forces sur les joints.

Cette ﬁgure montre que les huit forces qui s’appliquent à bloc ne s’intersectent
pas. Il n’est pas possible de transformer les solutions d’équilibre trouvées avec les
éléments ﬁnis en réseaux de forces, ou en funiculaires. Cependant, la projection des
forces sur le plan frontal (vue de face) montre une similitude avec les réseaux de forces
des chargements extrêmes.

Les forces sur les joints triangulaires assurent la résistance à la torsion des platesbandes. Elles sont visibles sur la ﬁgure 15.18, et ne sont généralement pas perpendiculaires aux joints. Les contraintes sur ces joints triangulaires sont très inférieures
aux contraintes maximales sur les joints rectangulaires (ﬁg. 15.19). Le rapport entre
la contrainte maximale sur les joints rectangulaires et les contraintes maximales sur
les joints triangulaires vaut 5 (ordre de grandeur sur les trois solutions présentées ici).

272

<!-- p. 274 -->

Chapitre 15. Étude des plates-bandes

vue
de
face

vue
de
dessus

Sol1 (poids propre et écartement des appuis)

vue
de
face

vue
de
dessus

Sol2 (poids propre seul)

vue
de
face

vue
de
dessus

Sol3 (poids propre et rapprochement des appuis)

Fig 15.18 – Directions et intensités des résultantes des forces, vue de face et vue de
dessus, pour les solutions d’équilibre générées par Cast3M

273

<!-- p. 275 -->

Chapitre 15. Étude des plates-bandes

Sol1 (poids propre et écartement des appuis)

Sol2 (poids propre seul)

Sol3 (poids propre et rapprochement des appuis)

Fig 15.19 – Contraintes normales sur les joints [ N/m2 ], pour les solutions
d’équilibre générées par Cast3M

274

<!-- p. 276 -->

Chapitre 15. Étude des plates-bandes

Sol1 (poids propre et écartement des appuis)

Sol2 (poids propre seul)

Sol3 (poids propre et rapprochement des appuis)

Fig 15.20 – Déplacements [ m ], pour les solutions d’équilibre générées par Cast3M

275

<!-- p. 277 -->

Chapitre 16

Étude des voûtes plates

Résumé : Ce chapitre traite de l’inﬂuence de la coupe des pierres sur la stabilité
des voûtes plates. Trois types de voûtes sont analysées : les voûtes plates appareillées
sur le plan du berceau, les voûtes plates appareillées sur le plan de la voûte en
arc-de-cloître, et enﬁn la voûte plate d’Abeille. Les domaines des chargements potentiellement supportables, qui sont utilisés pour quantiﬁer la stabilité, sont déterminés
avec les réseaux de forces. L’intégration des résultats de modèles aux éléments ﬁnis
est envisagée.

Sommaire
16.1 Description des voûtes étudiées . . . . . . . . . . . . . . . . . . . . 277
16.1.1 Étude de trois appareils . . . . . . . . . . . . . . . . . . . 277
16.1.2 Paramétrisation des appareils . . . . . . . . . . . . . . . . 278
16.1.3 Déﬁnition des voûtes étudiées . . . . . . . . . . . . . . . . 279
16.2 Inﬂuence des choix de modélisation . . . . . . . . . . . . . . . . . 280
16.2.1 Application de la méthode des réseaux de forces . . . . . . 280
16.2.2 Raﬃnement du réseau . . . . . . . . . . . . . . . . . . . . 281
16.2.3 Interpolation polynomiale des paramètres . . . . . . . . . 283
16.3 Inﬂuence de la coupe des pierres . . . . . . . . . . . . . . . . . . . 285
16.3.1 Résultats de la voûte unidirectionnelle . . . . . . . . . . . 285
16.3.2 Résultats de la voûte bidirectionnelle . . . . . . . . . . . . 286
16.3.3 Résultats de la voûte d’Abeille . . . . . . . . . . . . . . . 291
16.3.4 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . 294
16.4 Modèle aux éléments ﬁnis . . . . . . . . . . . . . . . . . . . . . . . 294

276

<!-- p. 278 -->

Chapitre 16. Étude des voûtes plates

16.1 Description des voûtes étudiées

16.1.1 Étude de trois appareils

Nous étudions dans ce chapitre l’eﬀet de la coupe des pierres sur une voûte plate
construite sur un plan carré. Le paramètre de la coupe des pierres dont nous étudions
l’eﬀet ici est l’appareil global de la voûte. Trois modèles sont étudiés, présentant
successivement un appareil :
— sur le plan de la voûte en berceau (« barrel vault »), appelée voûte unidirec-
tionnelle dans la suite pour simpliﬁer les descriptions (ﬁg. 16.1) ;
— sur le plan de la voûte en arc-de-cloître (« pavillon vault »), appelée voûte
bidirectionnelle dans la suite pour simpliﬁer les descriptions (ﬁg. 16.2) ;
— sur le plan de la voûte d’Abeille, du nom de son inventeur (ﬁg. 16.3).
La voûte unidirectionnelle n’est appuyée que sur deux côtés du carré qu’elle
couvre, alors que la voûte bidirectionnelle et la voûte d’Abeille sont appuyées sur
les quatre côtés du carré. Les appuis sont représentés par des blocs de couleur rouge
sur les ﬁgures 16.1, 16.2 et 16.3.

Fig 16.1 – Voûte plate à joints inclinés appareillée sur le plan du berceau (voûte
plate unidirectionnelle), vue assemblée (à g.) et éclatée (à d.)

Fig 16.2 – Voûte plate à joints inclinés appareillée sur le plan de la voûte en
arc-de-cloître (voûte plate bidirectionnelle), vue assemblée (à g.) et éclatée (à d.)

Par rapport à l’appareil réel d’une voûte plate appareillée sur le plan d’un berceau
(ﬁg. 10.3 sous-ﬁgures 1 et 2) ou appareillée sur le plan de la voûte en arc-de-cloître
(ﬁg. 10.3 sous-ﬁgures 3 et 4), l’appareil des voûtes étudiées est simpliﬁé en divisant
les claveaux et régularisé en ajustant leur taille pour obtenir des blocs dont les faces

277

<!-- p. 279 -->

Chapitre 16. Étude des voûtes plates

Fig 16.3 – Voûte plate d’Abeille, vue assemblée (à g.) et éclatée (à d.)

inférieures (intrados) et supérieures (extrados) sont des carrés (ﬁg. 16.4). La simpliﬁcation introduit des joints ﬁctifs dans la coupe des pierres de la voûte, qui respectent
les règles régissant l’orientation des joints existants dans l’appareil réel (ﬁg. 16.5). La
régularisation aﬀecte légèrement la position des joints réels.

(a) (b)

(a) (b)

Fig 16.4 – Régularisation (a) et simpliﬁcation (b) de la découpe des claveaux

Fig 16.5 – Appareil régularisé des voûtes plates uni- et bidirectionnelles, avant et
après simpliﬁcation par introduction de joints ﬁctifs

16.1.2 Paramétrisation des appareils

Nous choisissons des caractéristiques similaires à celles déjà choisies pour les
plates-bandes pour décrire les appareils des voûtes plates :
— géométrie :
— nombre de claveaux kx et ky selon chaque direction principale ;
— portées Lm,x et Lm,y mesurées à mi-hauteur ;
— hauteur h ;

278

<!-- p. 280 -->

Chapitre 16. Étude des voûtes plates

— angle ϕ des joints des sommiers avec la verticale ;
— propriétés mécaniques :
— masse volumique de la pierre ρ0 ;
— résistance admissible des joints à la compression σ0 ;
— coeﬃcient de frottement de Coulomb des joints µ, correspondant à un angle
de frottement de tan−1 µ.
La coupe des pierres des voûtes plates, autre que les voûtes d’Abeille, est obtenue
à partir de ces paramètres par application de la méthode des divisions égales, décrite
notamment par Frézier (1738) (voir section 6.3.5 p. 110). Cette méthode de coupe a
l’avantage, pour le calcul analytique, de diviser la voûte plate en kxky claveaux de
même poids, dont l’intersection des joints avec le plan horizontal de la voûte plate
(pris à mi-hauteur) est la même quelle que soit l’inclinaison des joints. De plus, lorsque
l’angle ϕ varie :
— la position de l’intersection des joints avec le plan horizontal de la voûte plate
(pris à mi-hauteur) est inchangée ;
— le poids de chaque claveau est inchangé ;
— le poids total de la voûte plate est inchangé.
Les portées libres Li,x et Li,y de la voûte plate, mesurées à l’intrados, se déduisent
des paramètres donnés ci-dessus avec Li = Lm −h/ tan ϕ. Les portées, lorsqu’elles
sont égales dans les deux directions, sont notées simplement Li et Lm.

Paramétrisation des voûtes d’Abeille

Nous reprenons la paramétrisation des voûtes d’Abeille de Brocato et Mondardini
(2014), et présentée dans la partie consacrée aux voûtes plates (section 10.3.4 p. 196).

16.1.3 Déﬁnition des voûtes étudiées

Les caractéristiques suivantes sont communes aux trois voûtes :
— ϕ = 18,4◦correspondant à la règle du « 1 pour 3 » ;
— épaisseur h = 20 cm ;
— ratio Lm/h = 14 ≈Li/h, bien supérieur (voûte plus ﬁne) aux ratios habituels
des plates-bandes de l’ordre de Li/h = 2 à 5. Ce ratio a été retenu pour
permettre la comparaison avec les résultats expérimentaux des Grands ateliers
de l’Isle d’Abeau de 2006. Connaissant la hauteur, la portée mesurée à mi-
hauteur sera Lm = 2,80 m pour ce ratio 14. La portée est mesurée à mi-hauteur
de la plate-bande, de manière à éliminer la variation du poids total de la plate-
bande lors de la variation de l’angle ϕ (même démarche que celle adoptée lors
de l’étude des plates-bandes, même si ici ϕ est constant pour les exemples
étudiés). La portée mesurée à l’intrados vaut Li = 2,73 m ;
— voûte composée de 9 × 9 = 81 claveaux ;
— caractéristiques des matériaux, choisies pour représenter la pierre utilisée lors
des expériences des Grands ateliers de l’Isle d’Abeau en 2006 :
— masse volumique (1) ρ0 = 1658 kg/m3 ;

(1). Le poids des claveaux est obtenu en multipliant leur masse par la gravité prise égale à 10 m.s−2.
Cela revient à utiliser l’approximation usuelle dans le bâtiment « 1 kg = 1 daN ». L’incidence de cette
approximation sur les domaines des chargements potentiellement supportables est abordée p. 252.

279

<!-- p. 281 -->

Chapitre 16. Étude des voûtes plates

— résistance admissible à la compression σ0 = 1,0 MPa ;
— coeﬃcient de frottement : µ = 0,7.
Le poids propre de la voûte unidirectionnelle et de la voûte bidirectionnelle vaut
W0 = 2600 kg, et celui de la voûte plate d’Abeille vaut W0 = 2319 kg. Cette dernière
est légèrement plus légère que les deux précédentes en raison des trous pyramidaux
formant une trame régulière sur l’extrados (ﬁg. 16.3 et ﬁg 2e sur ﬁg. 10.12).

L’inclinaison des joints retenue correspond à la règle du « 1 pour 3 » vue précédemment concernant les plates-bandes, et qui correspond pour mémoire à l’inclinaison
souvent utilisée par les tailleurs de pierre du xviiie siècle. Cette inclinaison correspond
également à la description dans le texte de Gallon de la voûte d’Abeille en 1735.

16.2 Inﬂuence des choix de modélisation

16.2.1 Application de la méthode des réseaux de forces

Procédure de calcul des domaines des chargements supportables

Les paramètres de chargement utilisés pour le calcul des domaines des chargements
potentiellement supportables du calcul à la rupture sont :
— le chargement vertical total W, somme des charges uniformément réparties sur
l’ensemble des claveaux ;
— le chargement horizontal total sur un des côtés du carré P Hx = P Hy, c’est-
à-dire la poussée horizontale totale de la voûte sur un côté.
Pour mémoire, nous notons W0 le poids propre de la voûte. Cette valeur sert à
rendre adimensionnels les paramètres de chargement sur les domaines des chargements supportables, exprimés en fonction de W/W0 et P Hx/W0.
La même procédure que celle utilisée pour les plates-bandes est appliquée pour
les voûtes plates pour construire les domaines numériques des chargements supportables K présentés dans la suite. Pour une poussée horizontale P Hx = ¯H donnée et
un chargement vertical W = ¯W = W0 donné, le multiplicateur de charge de la voûte
plate F(¯H, ¯W) est calculé. D’après la détermination de ce multiplicateur, le point
F ¯H; FW0 se trouve à l’intérieur du domaine des chargements potentiellement supportables K. Le domaine convexe déﬁni par itération en des points successifs est une
estimation par l’intérieur du domaine K (ﬁg. 15.8 p. 263).

Paramètres de l’équilibre

Pour mémoire, la méthode des réseaux de forces, telle qu’elle a été étendue dans
le cadre de cette thèse, exprime l’équilibre des structures clavées sous la forme d’un
réseau de forces paramétré. Les trois types de paramètres sont :
— les forces horizontales dans un sous-ensemble des branches (dont le nombre
est égal au degré d’hyperstaticité du réseau projeté dans le plan horizontal) ;
— les altitudes des nœuds des blocs d’appuis (blocs rouges sur les ﬁgures ci-
dessus) ;
— les forces verticales dans les branches partielles introduites dans notre exten-
sion de la méthode.

280

<!-- p. 282 -->

Chapitre 16. Étude des voûtes plates

Ces paramètres sont réunis sous la forme de vecteurs : ζdof pour les forces horizontales,
zb pour les altitudes des nœuds de bord, et w∗p pour les forces verticales des branches
partielles.

La localisation des paramètres est illustrée sur la ﬁgure 16.6 pour les forces horizontales et les altitudes des nœuds d’appui, et sur la ﬁgure 16.7 pour les forces
verticales dans les branches partielles. Dans le cas présent, le nombre de paramètres
se décompose comme suit :
— pour la voûte bidirectionnelle :
— 18 forces horizontales (5 après symétrie) ;
— 18 positions verticales des nœuds d’appuis (5 après symétrie) ;
— 81 forces verticales dans les branches partielles si considérées (10 après
symétrie (2)) ;
— soit un total de 20 paramètres pour la voûte bi-directionnelle.
— pour la voûte d’Abeille
— 18 forces horizontales (10 après symétrie) ;
— 18 positions verticales des nœuds d’appuis (10 après symétrie) ;
— 81 forces verticales dans les branches partielles si considérées (25 après
symétrie (3)) ;
— soit un total de 45 paramètres pour la voûte d’Abeille.

Paramètres après symétrie Paramètres après symétrie
Paramètres avant symétrie voûte bidir. voûte Abeille

Fig 16.6 – Forces horizontales (en bleu) et altitudes des nœuds d’appui (en rouge),
paramétrant l’équilibre des réseaux de forces

16.2.2 Raﬃnement du réseau

Le réseau de forces de la voûte bidirectionnelle peut être raﬃné en ajoutant des
branches partielles pour chaque claveau, qui ne transmettent que des forces verticales.
Les branches partielles permettent de moduler la transmission des eﬀorts dans les

(2). Les 81 paramètres se réduisent à 15 paramètres en appliquant les conditions de symétrie, puis
à seulement 10 paramètres en faisant l’hypothèse que les branches partielles situées sur la diagonale
y = x ne transmettent pas de forces (sinon une des deux directions sera plus chargée que l’autre, alors
que nous avons fait l’hypothèse que les forces horizontales suivant x et suivant y sont symétriques).
(3). La voûte d’Abeille possède moins de symétrie que la voûte bidirectionnelle, car une voûte
d’Abeille après rotation de 90◦ne peut pas être superposée à la voûte avant rotation, alors qu’une
voûte bidirectionnelle après rotation de 90◦est superposable à la voûte avant rotation.

281

<!-- p. 283 -->

Chapitre 16. Étude des voûtes plates

Paramètres après symétrie Paramètres après symétrie
Paramètres avant symétrie voûte bidir. voûte Abeille

Fig 16.7 – Forces verticales dans les branches partielles, paramétrant l’équilibre des
réseaux de forces

deux directions x et y, en chargeant plus ou moins l’une ou l’autre des directions de
façon indépendante pour chaque bloc.

Pour étudier l’inﬂuence du raﬃnement du réseau sur les résultats, nous comparons
les domaines des chargements supportables correspondant à trois modèles de la voûte
bidirectionnelle (Bi) :
— Modèle Bi-A : réseau de forces sans branches partielles
— Modèle Bi-B : réseau de forces avec branches partielles où la force verticale
est nulle
— Modèle Bi-C : réseau de forces avec branches partielles
Le modèle Bi-C est celui qui permet d’explorer le plus grand domaine de solutions
d’équilibre. Parmi les solutions explorées par le modèle Bi-C se trouvent l’ensemble
des solutions d’équilibre du modèle Bi-A et du modèle Bi-B. En eﬀet, le modèle BiA sans branche partielle est équivalent à un modèle avec branches partielles dans
lesquelles la valeur des forces verticales est choisie pour que les deux nœuds de la
branche partielle soient superposés.
Le domaine des chargements supportables KBi−C calculé englobe les domaines de
chargements supportables KBi−A et KBi−B, comme cela était attendu (ﬁg. 16.8).
Le modèle Bi-B revient à dissocier les branches du réseau parallèles à l’axe x
et celles parallèles à l’axe y. Le modèle est alors composé de 9 plates-bandes indépendantes dirigées selon x et portant la moitié du chargement vertical, et de 9
plates-bandes indépendantes dirigées selon y et portant l’autre moitié du chargement
vertical.
Le domaine des chargements supportables KBi−B du modèle Bi-B englobe des
chargements verticaux extrêmes plus importants que ceux du domaine KBi−A du modèle Bi-A (ﬁg. 16.8 (b)). Inversement, le modèle Bi-A donne des chargements supportables avec des poussées extrêmes plus faibles que celles du modèle Bi-B (ﬁg. 16.8 (a)).

Du point de vue calculatoire, les solutions du modèle B sont paramétrées uniquement par 2 paramètres, alors que celles du modèle Bi-A sont paramétrées par
10 paramètres, nécessitant donc des temps de calcul beaucoup plus important (voir
partie suivante sur le processus de calcul du domaine KBi−A).

282

<!-- p. 284 -->

Chapitre 16. Étude des voûtes plates

W
W0

6 (b)

4

(a)

2

0 W0Hx
0 2 4 6 8 10 12 14 16 18 20 22 24 P

Modèle Bi-A (sans raﬃnement du réseau)
Modèle Bi-B (avec raﬃnement du réseau)
Modèle Bi-C (avec raﬃnement du réseau)

Fig 16.8 – Inﬂuence du raﬃnement du réseau (branches partielles) sur le domaine
des chargements supportables de la voûte bidirectionnelle

16.2.3 Interpolation polynomiale des paramètres

Nous avons vu précédemment que les solutions d’équilibre des réseaux de forces
sont paramétrées par 20 paramètres pour la voûte bi-directionnelle et 45 paramètres
pour la voûte d’Abeille.

Lorsque le nombre de paramètres devient important, il est possible d’interpoler
les valeurs de ces paramètres pour baisser le nombre de paramètres numériques eﬀectivement utilisés pour la recherche des chargements extrêmes (section 13.4.2 p. 227).

La variable des polynômes d’interpolation des forces horizontales et des altitudes des nœuds d’appuis sont x ou y. La variable des polynômes d’interpolation
des branches partielles est r = p x2 + y2. Ce dernier choix a été guidé par l’observation suivante. Dans le cas d’une voûte d’Abeille de 5×5=25 claveaux où l’optimisation
avec 6 + 6 + 6 = 18 paramètres sans interpolation était possible, les forces dans les
branches partielles des solutions d’équilibre représentant les chargements extrêmes
variaient généralement en fonction de leur distance au centre de la voûte.

L’inﬂuence des polynômes de Lagrange sur les résultats est étudiée ici en comparant les modèles suivants :
— pour la voûte bidirectionnelle sans raﬃnement du réseau (modèles Bi-)
— Modèle Bi-II : modèle dans lequel des polynômes de degré 0 sont uti-
lisés pour les vecteurs paramètres ζdof et zb, ce qui conduit à 1 + 1 = 2
paramètres ;
— Modèle Bi-VI : modèle dans lequel des polynômes de degré 2 sont uti-
lisés pour les vecteurs paramètres ζdof et zb, ce qui conduit à 2 + 2 = 3
paramètres (4) ;
— Modèle Bi-X : modèle sans interpolation, avec 10 paramètres.

(4). Un polynôme de degré 2 est déﬁni par 3 coeﬃcients, mais la symétrie donne une condition sur
les pôles du polynôme, et le nombre de coeﬃcients pour chaque polynôme est donc 3-1=2.

283

<!-- p. 285 -->

Chapitre 16. Étude des voûtes plates

— pour la voûte d’Abeille (modèles Ab-)
— Modèle Ab-V : modèle dans lequel des polynômes de degré 0 sont utilisés
pour les vecteurs paramètres ζdof, zb et w∗p ce qui conduit à 2 + 2 + 1 = 5
paramètres ;
— Modèle Ab-XXIII : modèle dans lequel seules les branches partielles w∗p
utilisent des polynômes de degré 2 ce qui conduit à 10 + 10 + 3 = 23 para-
mètres ;

W
W0

6

4

2

0 W0Hx
0 2 4 6 8 10 12 14 16 18 20 22 24 P

Modèle Bi-II (2 param.)
Modèle Bi-VI (6 param.)
Modèle Bi-X (10 param.)

Fig 16.9 – Inﬂuence des polynômes de Lagrange sur le domaine des chargements
supportables de la voûte bidirectionnelle

Les ﬁgures 16.9 et 16.10 montrent que l’utilisation des polynômes de Lagrange
réduit fortement le domaine des chargements supportables.

Dans ces deux cas, au sein de chaque catégorie de paramètres (forces horizontales, altitude des nœuds de bords) pour laquelle un polynôme est utilisé, les valeurs
ne présentent pas suﬃsamment de régularité pour qu’ils puissent être correctement
approximés avec un polynôme de degré 2 ou 3. Ainsi l’interpolation n’est pas utile
pour calculer directement le domaine le plus grand. Elle permet cependant de trouver rapidement un bon point de départ pour la recherche du chargement extrême, qui
constitue un problème d’optimisation sous contraintes. Ainsi, pour obtenir le domaine
des chargements supportables du modèle Bi-X, nous avons préalablement calculé celui du modèle Bi-II, utilisé la solution comme point de départ pour le modèle Bi-VI
et enﬁn utilisé la solution du modèle Bi-VI comme point de départ du modèle Bi-X.
Cette procédure est plus eﬃcace (en terme de temps de calcul), que de calculer directement le domaine du modèle Bi-X à partir d’un point de départ arbitraire. De
la même façon, les solutions trouvées pour le modèle Ab-V ont été utilisées ensuite
comme point de départ pour le modèle Ab-XXIII.

Dans la suite, les résultats seront donnés sans utiliser d’interpolation pour les
paramètres, à l’exception des forces verticales des branches partielles de la voûte
d’Abeille.

Notons ici que si le critère de résistance au frottement n’est pas considéré, la pous-

284

<!-- p. 286 -->

Chapitre 16. Étude des voûtes plates

W
W0

(a)

6

4

2

0 W0Hx
0 2 4 6 8 10 12 14 16 18 20 22 24 P

Modèle Ab-V µ = 0,7
Modèle Ab-V µ = ∞

Modèle Ab-XXIII µ = 0,7
Modèle Ab-XXIII µ = ∞

Fig 16.10 – Inﬂuence des polynômes de Lagrange sur le domaine des chargements
supportables de la voûte d’Abeille

sée minimale pour la voûte d’Abeille est nulle, et il existe un intervalle de valeurs
pour la poussée donnant le même chargement vertical maximum (ﬁg. 16.10 (a)), au
lieu d’avoir une seule poussée possible pour le chargement vertical admissible maximum (p. ex. ﬁg. 16.8 (b)). La forme du domaine des chargements supportables de la
voûte d’Abeille, similaire à celle des plates-bandes à joints en X, illustre l’analogie
mécanique entre ces deux types de structures.

16.3 Inﬂuence de la coupe des pierres

16.3.1 Résultats de la voûte unidirectionnelle

Les résultats de la voûte unidirectionnelle serviront de base de comparaison avec
les autres voûtes étudiées ensuite. Le calcul de cette voûte avec la méthode des réseaux
de forces est équivalent à celui d’une plate-bande, car les forces dans les branches
perpendiculaires au sens de portée sont nécessairement nulles (absence de blocs de
bord), et les branches parallèles au sens de portée sont indépendantes les unes des
autres. Le domaine de résistance Kunidir. est représenté sur la ﬁgure 16.1.
Dans le cas de la voûte unidirectionnelle, le critère de résistance en frottement n’est
pas atteint pour les solutions d’équilibre correspondant aux chargements extrêmes.

Il est possible à partir de ce premier résultat d’estimer le domaine des chargements
supportables de la voûte bidirectionnelle à partir de la remarque suivante. La voûte
bidirectionnelle étant la combinaison de deux voûtes unidirectionnelles, il est possible
de combiner les solutions d’équilibre des chargements extrêmes (¯H; ¯W) sur la frontière
du domaine Kunidir.. Le résultat de cette combinaison est un nouveau chargement

285

<!-- p. 287 -->

Chapitre 16. Étude des voûtes plates

extrême (¯H; 2¯W) pour la voûte bidirectionnelle. La poussée ¯H n’est pas doublée, mais
elle s’applique maintenant sur les quatre bords, au lieu de ne s’appliquer que sur deux
bords. Le domaine des chargements supportables de la voûte bidirectionnelle Kbidir.
est donc a minima la transformation aﬃne de facteur 2 suivant l’axe du paramètre
de chargement W (ﬁg. 16.11).

W
W0

6

4

2

0 W0Hx
0 2 4 6 8 10 12 14 16 18 20 22 24 P

Kunidir. Kbidir. = aﬃnité de facteur 2
suivant W de Kunidir.

Fig 16.11 – Domaine des chargements supportables de la voûte unidirectionnelle et
déduction de celui de la voûte bidirectionnelle

L’utilisation des réseaux de forces, que nous présentons dans la partie suivante,
permet d’obtenir des domaines de chargements pour la voûte bidirectionnelle plus
grands que cette première estimation.

16.3.2 Résultats de la voûte bidirectionnelle

Le modèle Bi-B présenté précédemment lors de l’étude de l’inﬂuence des branches
partielles, où les forces verticales dans les branches partielles sont nulles, donne le
même domaine des chargements supportables que l’estimation du domaine Kbidir.
réalisé par aﬃnité du domaine Kunidir. (les courbes obtenues dans ces deux cas sont
superposées sur la ﬁgure 16.12). Les remarques comparatives entre le modèle Bi-A
et le modèle Bi-B s’appliquent donc de façon identique entre le modèle Bi-A (réseau
de forces sans raﬃnement) et l’estimation du domaine des chargements supportables
par aﬃnité de facteur 2 de la voûte unidirectionnelle : voir p. 282.

Cependant, grâce au raﬃnement du réseau de forces avec les branches partielles
(et forces verticales non nulles), le domaine des chargements supportables de la voûte
bidirectionnelle calculé est plus grand que l’estimation par aﬃnité de facteur 2, principalement pour les chargements horizontaux extrême minimaux (ﬁg. 16.13 (a)) et
maximaux (ﬁg. 16.13 (b)).

286

<!-- p. 288 -->

Chapitre 16. Étude des voûtes plates

Frézier indique que la poussée d’une voûte d’Abeille devrait être la moitié d’une
plate-bande parce qu’elle porte en deux directions au lieu d’une.

Puisque les coupes des claveaux des Voutes plates [d’Abeille] sont tour-
nées de quatre côtez alternativement, il est clair que ces voutes poussent
aussi de quatre côtez, à la diﬀerence des Platebandes, qui ne poussent que
de deux côtez ; d’où il suit qu’elles font la moitié moins d’eﬀort que les
platebandes pour renverser leurs piedroits, & par consequent demandent
moitié moins d’épaisseur de mur, ce qui est un avantage.
Frézier (1738, p. 77)

Ce type de raisonnement s’applique également dans le cas de la voûte bidirectionnelle.

Il est possible d’éclairer cette aﬃrmation de Frézier en utilisant les domaines des
chargements supportables produits ici. Dans le cadre du calcul à la rupture, la poussée minimale désigne, pour un chargement vertical donné, la poussée la plus faible
(en tant que chargement horizontal sur la structure) qui combinée à ce chargement
vertical compose un chargement extrême (et donc potentiellement supportable). En
général, la poussée minimale dépend à la fois du type de chargement vertical (chargement ponctuel, chargement réparti etc.) et de l’intensité de ce chargement vertical.
Cependant, si la résistance à la compression des joints est inﬁnie, ce qui est une hypothèse implicite de Frézier ici, la poussée minimale par unité de chargement vertical
ne dépend pas de l’intensité du chargement vertical, et est donnée par la pente à
l’origine du domaine des chargements supportables.

Dans le cas de l’estimation aﬃne du domaine de chargement de la voûte bidirectionnelle, la pente (et donc la poussée minimale par unité de chargement vertical)
double lors du passage de la voûte unidirectionnelle à la voûte bidirectionnelle (afﬁnité de facteur 2), illustrant donc le raisonnement tenu par Frézier. Cependant la
ﬁgure 16.12 (a) montre qu’il existe des chargements extrêmes où la poussée minimale (par unité de chargement vertical) est encore plus faible que la moitié. Nous en
concluons donc que la poussée (minimale) des voûtes plates est plus de deux fois plus
faible que celle d’une plate-bande ne portant dans une seule direction.

Dans le cas de la voûte bidirectionnelle, le critère de résistance en frottement est
parfois atteint pour les solutions d’équilibre correspondant aux chargements extrêmes
calculés. Cependant pour chaque chargement extrême présentant cette situation, il a
été possible de trouver une nouvelle solution d’équilibre correspondant à un nouveau
chargement extrême au moins égal au précédent et n’atteignant pas le critère de
résistance en frottement.

287

<!-- p. 289 -->

Chapitre 16. Étude des voûtes plates

W
W0

6 (b)

4

(a)

2

0 W0Hx
0 2 4 6 8 10 12 14 16 18 20 22 24 P

Modèle Bi-B (avec raﬀ. et Fv=0)
Kbidir. = aﬃnité de facteur 2 suivant W de Kunidir.
Modèle Bi-A (sans raﬀ.)

Fig 16.12 – Domaine des chargements supportables de la voûte bidirectionnelle

W
W0

6

(a) (b)
4

2

0 W0Hx
0 2 4 6 8 10 12 14 16 18 20 22 24 P

Modèle Bi-C (avec raﬀ.)
Kbidir. = aﬃnité de facteur 2 suivant W de Kunidir.

Fig 16.13 – Domaine des chargements supportables de la voûte bidirectionnelle

288

<!-- p. 290 -->

Chapitre 16. Étude des voûtes plates

W
W0

\+
(b) 6

4

(c) +
2

\+ (a)
0 W0Hx
0 2 4 6 8 10 12 14 16 18 20 22 24 P

(a)

(b)

(c)

Fig 16.14 – Réseaux de forces correspondant à des chargements extrêmes de la
voûte bidirectionnelle, modèle Bi-C (avec raﬃnement)

289

<!-- p. 291 -->

Chapitre 16. Étude des voûtes plates

W
W0

6 +

(c)

\+ (b)
4

2

\+ (a)

0 W0Hx
0 2 4 6 8 10 12 14 16 18 20 22 24 P

(a) (b)

(c)

Fig 16.15 – Réseaux de forces correspondant à des chargements extrêmes de la
voûte bidirectionnelle, modèle Bi-A (sans raﬃnement)

290

<!-- p. 292 -->

Chapitre 16. Étude des voûtes plates

16.3.3 Résultats de la voûte d’Abeille

Le critère de résistance au frottement joue un rôle important pour les basses
poussées (ﬁg. 16.16 (b)), contrairement au cas des voûtes bidirectionnelles où pour
les proportions L/h et l’inclinaison des joints ϕ étudiées le critère de résistance au
frottement n’intervient pas.

Le domaine est nettement plus réduit que celui des voûtes bidirectionnelles dans la
zone des fortes poussées, en raison de la forme trapézoïdale (5) des joints qui engendre
des surfaces de joints plus réduites (ﬁg. 16.16 (a)).

Bien que la voûte d’Abeille ne soit pas rigoureusement symétrique par rapport au
plan horizontal, elle procure une résistance équivalente pour les chargements verticaux
(vers le bas) et pour les chargements verticaux inversés (vers le haut). Le domaine des
chargements supportables attendu est donc presque symétrique (hypothèse retenue à
la ﬁgure 16.17).

W
W0

6

4

(b) (a)

2

0 W0Hx
0 2 4 6 8 10 12 14 16 18 20 22 24 P
Modèle XXIII µ = 0,7
Modèle C (voûte bidir. pour comparaison)

Fig 16.16 – Domaine des chargements supportables de la voûte d’Abeille

(5). Par ailleurs, les calculs des multiplicateurs de rupture sur les surfaces de contact trapézoïdales
(de hauteur h et de surface S) ont été simpliﬁés en utilisant un joint rectangulaire approché de
hauteur égale à h et de largeur b = S/h. L’eﬀet de cette approximation doit cependant être faible
pour l’angle ϕ = 18,4◦considéré pour la voûte de cette étude.

291

<!-- p. 293 -->

Chapitre 16. Étude des voûtes plates

W
W0

5

0

−5

Hx
W0
0 2 4 6 8 10 12 14 16 18 20 22 24 P
Chargements extrêmes positifs
Chargements extrêmes négatifs (estimatif)

Fig 16.17 – Similitude des chargements extrêmes verticaux positifs et négatifs du
domaine des chargements supportables de la voûte d’Abeille

292

<!-- p. 294 -->

Chapitre 16. Étude des voûtes plates

W
W0
(a)
\+
6

\+ (b)
4

2

0 W0Hx
0 2 4 6 8 10 12 14 16 18 20 22 24 P
Modèle XXIII µ = 0,7

(a)

(b)

Fig 16.18 – Réseaux de forces correspondant à des chargements extrêmes de la
voûte d’Abeille, modèle Ab-XXIII

293

<!-- p. 295 -->

Chapitre 16. Étude des voûtes plates

16.3.4 Conclusion

La comparaison des domaines des chargements supportables des voûtes plates
montre que l’appareil joue un rôle important sur la stabilité.

La voûte plate appareillée sur le plan de la voûte en arc-de-cloître présente une
stabilité bien supérieure à celle appareillée sur la voûte en berceau.

Il n’existe pas de changements aussi importants entre la voûte plate appareillée sur
le plan de la voûte en arc-de-cloître et la voûte d’Abeille, les chargements supportables
sont équivalents en ordre de grandeurs. Cependant la voûte d’Abeille permet d’être
utilisée indiﬀéremment dans les deux sens (charges verticales orientées vers le haut
ou vers le bas), ou construite avec les trous pyramidaux en intrados ou en extrados.
Cette propriété n’existe pas pour les autres voûtes plates.

16.4 Modèle aux éléments ﬁnis

Nous proposons dans cette section de comparer qualitativement les solutions
d’équilibre des chargements extrêmes du calcul à la rupture avec celles qui peuvent
être calculées avec un calcul aux éléments ﬁnis, pour observer si des chargements avec
double funiculaire dont la projection sur le plan frontal s’entrecroisent, comme ceux
visibles sur la ﬁgure 16.18 au centre, se produisent eﬀectivement dans la structure.

La discussion de la validité de cette approche, et la description générale de ce type
de modélisation, ont été présentées lors de sa première utilisation pour les platesbandes (section 15.5 p. 270).

Les caractéristiques des éléments volumiques de la pierre, et des éléments joints
sont donnés respectivement dans les tables 16.1 et 16.2.

Notation Valeur Description
ρs 1658 kg/m3 masse volumique
vs 2500 vitesse du son (hypothèse)
νs 0,27 coeﬃcient de poisson (hypothèse)
Ks = ρsv2s 10,36 GPa module d’élasticité isostatique
Es = 3Ks(1 −2νs) 14,30 GPa module d’élasticité

Table 16.1 – Caractéristiques de la pierre

Nous étudions la voûte plate d’Abeille (ﬁg. 16.3), considérée précédemment pour
l’étude de l’inﬂuence des joints. Sur la ﬁgure 16.3 à gauche, le modèle est composé
des 81 blocs intérieurs en beige, et de 36 blocs rouges représentant les appuis. Les
blocs d’appui ne font pas partie du modèle, ils servent uniquement à contrôler les
déplacements des nœuds des joints d’appuis du côté des blocs d’appuis.

Le chargement est composé uniquement du poids propre de la pierre et des joints.
Les calculs sont réalisés sous l’hypothèse des petits déplacements, de manière à obtenir
des solutions d’équilibre sur la géométrie initiale.

La solution d’équilibre obtenue est présentée sur les ﬁgures 16.19, 16.20, 16.21
et 16.22. La convention de signe utilisée avec Cast3M est compression négative.

294

<!-- p. 296 -->

Chapitre 16. Étude des voûtes plates

Notation Valeur Description
c 0,0 N/m2 cohésion
ϕ = tan−1 µ 35,0◦ angle de frottement limite
ρm 2200 kg/m3 masse volumique
Em 0,005 GPa module d’élasticité
νm 0,00 coeﬃcient de poisson (hyp.)
t 5,0 mm épaisseur
Kn,m 1000 MN/m3 raideur normale (si ε \< εcn,m)
Ks,m 500 MN/m3 raideur de cisaillement
εcn,m 0,05 seuil de déformation
Ef,m 2Kn,m seconde raideur normale (si ε ≥εcn,m)

Table 16.2 – Caractéristiques des joints

Les ﬁgures 16.19 et 16.20 représentent les résultantes des forces sur les joints sous
la forme de segments en bleu. L’épaisseur des segments est proportionnelle à la racine
carrée de l’intensité des forces. Les longueurs des segments sont constantes et ne sont
pas liées à l’intensité des forces. Les croix noires localisent le point d’application des
forces sur les joints.

Comme dans le cas des plates-bandes à joints en X étudiées précédemment par
la même méthode, les cinq forces qui s’appliquent à un bloc ne s’intersectent pas. Il
n’est donc pas possible de transformer les solutions d’équilibre trouvées en réseaux
de forces, ou en funiculaires. Cependant, la projection des forces sur le plan frontal
(vue de face et coupes sur ﬁg. 16.20) montre une similitude avec les réseaux de forces
des chargements extrêmes.

295

<!-- p. 297 -->

Chapitre 16. Étude des voûtes plates

Vue isométrique

A A

B B

C C

D D

E E

Vue de dessus

Fig 16.19 – Directions et intensités des résultantes des forces, pour la solution
d’équilibre Sol1 générée par Cast3M (1)

296

<!-- p. 298 -->

Chapitre 16. Étude des voûtes plates

Vue de face

Coupe AA

Coupe BB

Coupe CC

Coupe DD

Coupe EE

Fig 16.20 – Directions et intensités des résultantes des forces, pour la solution
d’équilibre Sol1 générée par Cast3M (2)

Fig 16.21 – Contraintes normales sur les joints [ N/m2 ], pour la solution d’équilibre
Sol1 générée par Cast3M

Fig 16.22 – Déplacements [ m ], pour la solution d’équilibre Sol1 générée par Cast3M

297

<!-- p. 299 -->

Chapitre 17

Étude des voûtes hélicoïdales

Résumé : Ce chapitre présente la comparaison des résultats fournis par la méthode
des réseaux de forces à ceux d’un modèle analytique des voûtes hélicoïdales. Cette
comparaison vise à illustrer la conjugaison de la direction des réseaux, qui limite les
solutions d’équilibre qui peuvent être produits avec la méthode des réseaux de forces.

Sommaire
17.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 299
17.2 Étude par bandes indépendantes . . . . . . . . . . . . . . . . . . . 299
17.3 Étude avec les réseaux de forces . . . . . . . . . . . . . . . . . . . 300
17.3.1 Bande inﬁnitésimale . . . . . . . . . . . . . . . . . . . . . 300
17.3.2 Escalier complet . . . . . . . . . . . . . . . . . . . . . . . 300

298

<!-- p. 300 -->

Chapitre 17. Étude des voûtes hélicoïdales

17.1 Introduction

Nous étudions dans ce chapitre les voûtes hélicoïdales, utilisées pour la construction des escaliers hélicoïdaux avec jour, prenant appui de façon continue sur les murs
de la cage d’escalier. Ce type de voûte a été étudié par García Ares (2007) indépendamment de la méthode des réseaux de forces, en considérant une découpe de
l’escalier par bandes hélicoïdales inﬁnitésimales indépendantes.

La comparaison des solutions qui peuvent être obtenues avec la méthode des
réseaux de forces et celles présentées par García Ares permet d’illustrer la conjugaison
de la direction des réseaux, vue dans la section 11.2.5.

Les escaliers hélicoïdaux font partie des exemples étudiés par Block (2009), puis
par Marmo et Rosati (2017) dans leur article sur leur proposition d’extension de la
méthode.

17.2 Étude par bandes indépendantes

García Ares a proposé une solution d’équilibre pour les escaliers hélicoïdaux en
considérant une découpe de l’escalier par bandes hélicoïdales inﬁnitésimales indépendantes (García Ares, 2007 – ﬁg. 17.1). Chaque bande est dans un premier temps
développée, puis étudiée comme une plate-bande inclinée. García Ares donne la valeur
analytique de la poussée minimale RH de chaque plate-bande, en considérant que la
résistance à la compression des joints est inﬁnie.

1
RH = 8ργ2r2∆r (17.1)

avec r le rayon de la bande hélicoïdale, ∆r son épaisseur, γ son angle en plan, et ρ
sa masse volumique.

Fig 17.1 – Bande inﬁnitésimale d’un escalier hélicoïdal, d’après García Ares (2007)

299

<!-- p. 301 -->

Chapitre 17. Étude des voûtes hélicoïdales

Comme les plates-bandes inclinées sont enroulées autour de l’axe de l’hélicoïde,
des poussées dirigées radialement s’exercent également à travers les bandes adjacentes
jusque dans les murs de la cage d’escalier. La solution d’équilibre exerce en outre des
poussées sur les paliers horizontaux servant d’appui en pied et en tête de l’escalier.
García Ares considère l’application numérique suivante : r0 = 1,5 m, r1 = 2,5 m,
γ = π, ρ = 3333,3 kg/m3, h = 4 m, et une épaisseur verticale de l’escalier de
tz = 0,15 m (ﬁgure 17.1). Pour la bande la plus longue, la poussée est
RH(r = 2,5 m) = 25,7 kg/mm. La poussée totale est :

Z Z r1=2,5 m 1
RH = r0=1,5 m 8ργ2r2 dr = 16792 kg (17.2)

García Ares (2011) propose également une autre solution d’équilibre pour le même
problème dans un article plus récent, qui n’a pas été exploitée ici.

17.3 Étude avec les réseaux de forces

17.3.1 Bande inﬁnitésimale

L’étude d’une bande inﬁnitésimale prise isolément donne le même résultat avec
la méthode des réseaux de forces qu’avec la méthode analytique de García Ares. Cet
exemple a été étudié pour la bande la plus longue (r = 2,5 m, avec une épaisseur
r1 −r0 = 1 mm – voir ﬁgure 17.2).
Le résultat trouvé avec la méthode des réseaux de forces est identique à celle de
García Ares dans ce cas, parce qu’il ne se produit pas la conjugaison des directions
du réseau que nous allons voir dans le cas de l’escalier complet.

17.3.2 Escalier complet

La méthode des réseaux de forces permet de considérer l’ensemble des bandes
et l’interaction de ces diﬀérentes bandes entre-elles. Le modèle considéré est représenté sur la ﬁgure 17.3. Ce modèle inclut les transferts de charges verticales entre
les diﬀérentes bandes. Ces transferts n’existent pas dans la solution analytique de
García Ares.

Essai de reproduction de la solution des bandes inﬁnitésimales En minimisant la fonction f = P Hi on obtient la poussée minimale totale pour le modèle
du réseau de forces (ﬁgures 17.4 et 17.5). Cette poussée minimale est légèrement inférieure à celle donnée avec la solution de García Ares (4% de diﬀérence). Le résultat
ﬁnal obtenu est proche, mais la répartition des poussées est, elle, très diﬀérente. Chez
García Ares la poussée est proportionnelle à r2, et elle est d’autant plus grande que
la bande considérée est proche du mur de la cage d’escalier. Avec le réseau de forces,
la poussée dans les diﬀérentes branches est nulle sauf pour la bande la plus proche de
l’axe de l’escalier. Dans cette solution, les charges au niveau de chaque marche sont
portées sur le principe d’une plate-bande entre le limon de l’escalier et le mur de la
cage d’escalier.

300

<!-- p. 302 -->

Chapitre 17. Étude des voûtes hélicoïdales

Géométrie : Résultats :
voûte hélicoïdale La méthode des réseaux de forces et la solu-
1x17 voussoirs tion de García Ares (2007) donnent la même
épaisseur tz = 0,15 m poussée H = 25,7 kg/mm
r0 = 2,499 m and r1 = 2,500 m
θ ∈[0◦; 180◦]
z ∈[0; 4]m ⇔δz = 4 m
ρ = 3333,3 kg/m3

Recherche solution d’équilibre :
minc>1 f
avec f = H et c = CSGJ

Mass network and joints

Réseau de forces Diagramme des forces horizontales

Fig 17.2 – Poussée minimale d’une bande inﬁnitésimale d’une voûte hélicoïdale,
comparaison entre réseaux de forces et méthode de García Ares (2007)

301

<!-- p. 303 -->

Chapitre 17. Étude des voûtes hélicoïdales

La diﬀérence entre la solution obtenue et la solution théorique agrégeant des
bandes inﬁnitésimales est due à plusieurs causes. Dans la solution basée sur la méthode des réseaux de forces :
— les bandes inﬁnitésimales sont remplacées par des bandes ﬁnies de 25 cm de
large ;
— les reports de charges verticales entre les blocs correspondant à une même
marche ne sont pas négligés.

Fig 17.3 – Voûte hélicoïdale, pour comparaison avec García Ares (2007)

En remplaçant la fonction f = P Hi par la fonction f = P H2i , la solution d’équilibre obtenue est moins éloignée de celle de García Arès. Chaque bande présente une
poussée non nulle (ﬁg. 17.4). Cependant ces poussées sont presque égales (moins de
5% d’écart entre la poussée la plus grande et la poussée la moins grande) et ne sont
pas proportionnelles à r2 comme dans la solution de García Arès.

Cette diﬀérence signiﬁe que le report des charges verticales entre les blocs appartenant à une même marche reste important.

En conclusion à cette comparaison, la conjugaison de la direction des réseaux de
forces a une inﬂuence importante sur les résultats qui sont atteignable en respectant
la condition d’intersection des forces à chaque bloc. Il n’est pas possible de reproduire
avec des réseaux de forces les solutions d’équilibre où les bandes sont indépendantes,
à moins de créer un réseau pour chacune de ces bandes, disjoint des autres réseaux
des autres bandes.

Par ailleurs, les réseaux de forces permettraient également d’étudier des géométries moins régulières que la voûte hélicoïdale, comme par exemples les escaliers à jour
sur plan ellipsoïdal. Ce travail ne poserait pas de diﬃculté théorique particulière, mais
il n’a pas été réalisé.

302

<!-- p. 304 -->

Chapitre 17. Étude des voûtes hélicoïdales

Géométrie : Résultats :
voûte hélicoïdale Soit Hi la poussée de la ième bande. La
4x17 voussoirs bande 1 est la plus proche de l’axe de l’héli-
épaisseur tz = 0,15 m coïde.
θ ∈[0◦; 180◦] Pour f = P Hi : une seule des bandes a une
z ∈[0; 4]m ⇔δz = 4 m poussée non nulle
ρ = 3333,3 kg/m3 P Hi = H1 = 16134 kg
Recherche solution d’équilibre : Pour f = P H2i :
minc>1 f H1 = 4264 kg, H2 = 4216 kg, H3 = 4150 kg,
Deux cas étudiés : H4 = 4074 kg, P Hi = 16705 kg
f = P Hi et c = CSGJ Avec la solution de García Ares (2007) :
f = P H2i et c = CSGJ P Hi = 16792 kg

2986.8 2986.8 2986.8 2986.8 2986.8 2986.8 2986.8
2986.8 2986.8
2986.8 2986.8
2986.8 2986.8
2986.8 2986.8
02238.5 2238.50
16133.8 16133.8

Réseau projeté et forces d’appuis (f = P Hi) Diagramme des forces (f = P Hi)

3092.5 3092.5 3092.5 3092.5 3092.5 3092.5 3092.5
3092.5 3092.5
3092.5 3092.5
3092.5 3092.5
3092.5 3092.5
2317.7 2317.7
4074.2 4149.9 4216.1 4264.3 4264.3 4216.1 4149.9 4074.2

Réseau projeté et forces d’appuis (f = P H2i ) Diagramme des forces (f = P H2i )

Fig 17.4 – Poussées minimales d’une voûte hélicoïdale, pour comparaison avec
García Ares (2007)

303

<!-- p. 305 -->

Chapitre 17. Étude des voûtes hélicoïdales

Réseau de forces pour f = P Hi et CSGJ ≥1 Réseau de forces pour f = P H2i et CSGJ ≥1

Fig 17.5 – Réseaux de forces d’une voûte hélicoïdale

304

<!-- p. 306 -->

Conclusion et perspectives

L’étude historique et typologique des plates-bandes et des voûtes plates a permis
d’ébaucher les grandes lignes de l’évolution de la coupe des pierres de ces structures,
et a guidé le choix des paramètres de l’appareil des constructions clavées étudiées lors
de l’étude de la résistance des voûtes. L’importante utilisation des plates-bandes en
fausse-coupe dans l’architecture française à partir du xviie siècle a été mise en lumière.
Les deux exemples antérieurs, à Prato (Italie) et Damas (Syrie), et l’existence des
plates-bandes à joints en X au Moyen Âge sans exemple équivalent connu en France
laissent supposer qu’il existe un maillon manquant pour expliquer l’apparition de cette
technique en France au xviie siècle. À partir des informations recueillies, nous avons
cependant formulé l’hypothèse que Jacques Lemercier, premier architecte français à
avoir utilisé de façon réccurente la technique, ait pu observer cette technique à Prato
lors de son voyage en Italie, avant de l’appliquer à son retour en France.

Notre étude historique est cependant basée sur un corpus d’exemples en nombre limité. L’étape suivante de cette étude historique serait donc de recentrer les recherches
sur des régions ou périodes plus restreintes, pour préciser les observations et valider
les hypothèses avancées dans cette thèse. À titre d’exemple, l’étude de l’évolution
de l’inclinaison des joints des plates-bandes des châteaux du domaine royal du xve
au xviie siècle permettrait peut-être de démontrer que la règle du triangle équilatéral s’impose à cette époque, et permettrait aussi d’étudier une éventuelle inﬂuence
italienne sur la diﬀusion de cette règle. Autre exemple possible, l’étude de l’évolution
de l’inclinaison des joints des plates-bandes des hôtels particuliers parisiens du xviie
et xviiie permettrait peut-être de démontrer que la règle du « 1 pour 3 » est eﬀectivement utilisée en pratique par les appareilleurs et tailleurs de pierre à cette époque,
bien que la règle du triangle équilatéral soit très majoritairement citée par les traités
de coupe des pierres et d’architecture.

L’extension de la méthode des réseaux de forces permet d’exploiter les solutions
d’équilibre ainsi produites dans le cadre du calcul à la rupture, en prenant en considération la géométrie des joints. Ce point essentiel pour l’application rigoureuse des
théorèmes du calcul à la rupture n’était pas pris en considération dans les formulations antérieures des réseaux de forces (O’Dwyer, 1999 ; Block et Ochsendorf, 2007 ;
Block, 2009 ; Marmo et Rosati, 2017). En outre, il devient alors possible d’exploiter la
méthode pour étudier l’inﬂuence de la coupe des pierres sur la résistance des voûtes
clavées. La comparaison de la résistance des constructions a été basée sur celle des
domaines des chargements potentiellement supportables.

Cependant, l’étude historique des traités montre qu’un des sujets de préoccupation des constructeurs, architectes et tailleurs de pierre, était la rupture des angles

305

<!-- p. 307 -->

Chapitre 17. Étude des voûtes hélicoïdales

aigus des claveaux des plates-bandes. La prise en compte de ces phénomènes nécessite de considérer, outre la résistance au niveau des joints, la résistance interne de la
pierre. Cependant cela nécessite de construire des solutions d’équilibre beaucoup plus
détaillées que celles habituellement utilisées pour le calcul à la rupture des constructions clavées, avec notamment la construction de champs de contrainte intérieurs aux
claveaux. La méthode des réseaux de forces ne semble pas adaptée pour la prise en
considération de la résistance interne des pierres. De plus, il semble diﬃcile d’aller au
delà du raﬃnement proposé pour contourner la condition d’intersection des forces en
un point, qui est une condition fondamentale pour la faisabilité de la méthode des
réseaux de forces, comme pour celle de la méthode des densités de forces. Le raﬃnement que nous proposons consiste d’ailleurs à superposer deux réseaux qui respectent
chacun la condition d’intersection des forces en un point, pour produire un nouveau
réseau qui ne respecte pas cette condition.

Les travaux récents sur l’application du calcul à la rupture combiné avec les solveurs coniques, qui permettent de prendre en compte un nombre très important d’inconnues (Bleyer, 2015), semble être une piste prometteuse pour produire de nouvelles
solutions d’équilibre non explorées avec les réseaux de forces, comme l’équilibre des
claveaux avec des systèmes de forces ne passant pas par un même point. Ces techniques permettraient également de prendre en considération la résistance de la pierre
à l’intérieur des claveaux.

L’implémentation proposée de l’extension de la méthode des réseaux de
forces a été réalisée sur un tableur de calcul, et peut donc être utilisée sur
n’importe quel ordinateur, sans autre licence que les licences habituelles de
bureautique pour Windows (Microsoft Excel). La première version du logiciel de 2014 est disponible à l’adresse http://combiencaporte.blogspot.fr/p/
masonry-network-analysis-for.html. La nouvelle version du logiciel développée
dans le cadre de cette thèse sera disponible à cette adresse : http://bestrema.fr/
manacoh/. Le calcul de structures plus importantes (au delà de 100 à 200 blocs) nécessitera cependant d’implémenter l’extension de la méthode des réseaux de forces
sur un logiciel de calcul numérique.

L’étude mécanique des plates-bandes et des voûtes plates a permis d’étudier l’inﬂuence de la coupe des pierres sur la résistance de ces structures. Les domaines
des chargements potentiellement supportables ont été déterminés par approche par
l’intérieur, et il est donc peut-être possible de trouver des domaines encore plus importants, si la résistance interne des pierres est négligée. Cependant, il faut souligner
pour conclure que les domaines qui prendraient en compte la résistance interne des
pierres doivent être plus petits.

306

<!-- p. 308 -->

Cinquième partie

Annexes

307

<!-- p. 309 -->

Annexe A

Sources bibliographiques

A.1 Citations des traités de l’Époque Moderne

Nous avons ici conservé l’orthographe d’origine des textes sans y apporter de
modiﬁcation.

Sebastiano Serlio (1475-~1554) Ainsi donc, je conseille aux maîtres maçons
ne faire comme aucuns font audit Paris et
Citation 1. Serlio (1537, 9r) lieux voisins, bâtissant de telle sorte que les
[...] la sua altitudine sarà che la fascia che poutres soutiennent les murs. Au contraire de
sostien l’arco, sia il suo supercilio o architrave ce qui doit être, car les murs doivent souche dir lo vogliamo. Et se non si trovera pie- tenir les poutres ou bien les porter. Et sans
tra de un pezzo per tal bisogno, siano fatti li les poutres, souvent lesdits murs tomberaient,
cunei come è dissegnato [...] qui sont retenus par grandes barres de fer,
et grandes clefs qu’ils mettent sur lesdites
La fascia désigne l’assise de pierre qui poutres, à travers des murailles, au droit des
contient l’imposte de l’arc, et qui doit donc chaînes de pierre de taille, aﬁn que les murs
correspondre à l’assise de pierre contenant la ne reculent. En cela il y a un grand abus
plate-bande des portes latérales. Voir ﬁg. 6.18 que les ouvriers font. Car si ont leur avait
à droite. baillé l’œuvre à la charge de n’y mettre du
fer, ils seraient contraints de faire mieux les
Citation 2. Serlio (1537, 10v) murailles et de plus grande grosseur et force
La misura sua sarà, che l’apertura sia di qu’ils ne font. Les ligatures de pierre de taille
quadrato perfetto, il sodo fra l’una & l’al- seraient plus longues, et la maçonnerie de
tra apertura sia la quarta parte menor di moellon mieux maçonnée. Car sous ombre du
quella, il supercilio, detto Architrave sia fer et du plâtre, ils ont espérance que leur oude l’apertura la quarta parte, & sia fatto vrage tiendra trop. J’ai vu advenir un autre
di cunei, che concorrano al centro, in numero grand mal aux bâtiments, pour mettre du fer
disparo [...] dans les maçonneries et avec les pierres de
taille, car le fer s’enrouille, et s’enrouillant,
Voir ﬁg. 6.18 au centre. il s’enﬂe et fait rompre les pierres et murs
qui ne peuvent durer longuement. De ce, nous
\*
prendrons par exemple le lierre duquel les ra-
\* *
cines liées et prises dans les murs, attirent et
rongent la substance du mortier. Et comme
Philibert De l’Orme (~1514-1570) elles deviennent grosses, se font faire place,
reculant les pierres qui n’ont plus de mortier
Citation 3. De l’Orme (1561, 5v-6)

308

<!-- p. 310 -->

Annexe A. Sources bibliographiques

et par ainsi les rendent prêtes de tomber. Quoi Relevé par Sakarovitch (1998, p. 136)
voyant, aucuns en ont fait cette divise : In-
\*
imica amicitia, qui est à dire « ennemie ami-
\* *
tié » ou « ce qui m’aime me ruine » . Ainsi
est-il du fer, lequel les méchantes maçonneries
aiment, de peur qu’elles ne tombent, mais à la Bernardino Baldi (1553-1617)
ﬁn, il les ronge et les ruine. Faisant tout ainsi
Citation 7. Baldi 1580-1615 In mechanicaque ledit lierre, lequel après avoir achevé de
Aristotelis problemata exercitationesruiner la muraille et l’avoir mise par terre,
n’ayant aucune chose pour se soutenir, est Disons tout d’abord que les briques et les
contraint de tomber sur le chemin. Auquel, pierres qui ne sont pas en forme de coins,
après avoir marché dessus, est coupé pour les disposés selon des lignes parallèles, ne se souempêchements qu’il peut faire, et par ainsi il tiennent pas. Nous disons que ceux-ci tombemeurt comme il a fait mourir le mur. ront sitôt démontée l’armature qui les soute-
nait. [...]Citation 4. De l’Orme (1567, 225v)
Mais si ces mêmes claveaux, ou briques,
[A propos de la portée de l’architrave don-
sont disposés en forme de coin de manière
née pour exemple] qui est grande largeur et
qu’ils pointent vers un centre unique, bien que
grande étendue pour les architraves, lesquels
disposés en ligne droite, ils ne tomberont pas,
il ne faut faire ainsi d’une pièce, qui ne vou-
mais ils resteront stables. [...]
drait qu’ils se rompissent ; mais pour les avoir
En vérité, cette structure est faible, et elleforts, il les faut faire de plusieurs pièces, avec
est d’autant plus faible que la largeur de l’es-leurs commissures de pente, ou joints d’en-
pace en dessous est grande et que la hauteurgraissement (ainsi que les appellent les ou-
des coins est élevée. Elle présente le même dé-vriers) au lieu où vous voyez qu’à chacune
faut que les épistyles et que les aérostyles encommissure, au droit de l’architrave, je fais
particulier qui, comme l’écrit Vitruve dans ledes trous carrés, jaçoit qu’ils ressemblent à lo-
livre III, chapitre 2, s’écroulent en raison desanges, ayant les pointes en haut et en bas.
la grandeur des intervalles entre les colonnes.
Citation 5. De l’Orme (1567, 68) Elle a encore un autre inconvénient : les coins
Quand il y a quelque diﬀormité, commu- ainsi disposés poussent de tout leur poids vers
nément les maçons pour n’entendre l’artiﬁce l’extérieur sur les deux plans d’imposte.
desdits traits font les voûtes de brique, ou
Traduction rapportée par Becchi (2012).
moellon, et de pierres menues, plutôt que de
pierre de taille, pour n’avoir l’industrie de *
les y accommoder, et sans y épargner le plus * *
souvent, de grandes barres de fer, pour soutenir leurs maçonneries de peur qu’elles ne
Louis Savot (~1579-1640)
tombent, qui est une très mauvaise coutume
et façon, pour les raisons que nous avons dit Citation 8. Savot (1624, p. 283-284)
ailleurs.
On se sert encore de suspentes et barres
Citation 6. De l’Orme (1567, 86) de fer : les suspentes servent pour tenir le
J’ai montré le moyen de se pouvoir aider faux manteau de la cheminée, et en faut une
des maisons incomodes, vieilles et mal faîtes, ou deux au plus à chaque manteau. Elles se
pour les approprier et accommoder avec les vendent à la livre, et peuvent peser quatrebâtiments neufs et rendre comode, salubre et vingt livres, plus ou moins selon la longueur
habitable, ce qui était incomode, insalubre et qu’elles ont, à raison de la hauteur des étages.
inhabitable ; sans toutefois abatre, ruiner ou Quand les plates-bandes des cheminées
démolir les vieux batiments, comme trop légè- sont de pierre de taille, on met au-dessous,
rement et inconsidérément font faire ceux qui d’autant qu’elles sont sujettes à se fendre
n’entendent l’artiﬁce des traits Géométriques, quelquefois par la trop grande chaleur du feu,
et par leur ignorance ordonnent incontinent une barre de fer qui peut valoir six ou sept
faire tout de neuf. livres plus ou moins.

309

<!-- p. 311 -->

Annexe A. Sources bibliographiques

\* les environnent & les supportent. Ce qui soit
\* * ﬁt, non pour conclure qu’on ne puisse abso-
lument passer ces bornes : mais pour avertir
les ouvriers, que lors qu’ils entreprendront de
François Derand (1588-1644) le faire, il leur faudra employer plus de soin,
tant au choix des materiaux, qu’en la hauCitation 9. Derand (1643, p. 382) teur des coupes des voussoirs, & en l’épais-
[A propos de la voûte d’arêtes sur un quarré, seur des murs, & en la liaison d’iceux avec
ayant un plat-fond quarré au milieu] les voûtes de l’escalier : soit par le moyen de
tant ce quadre [partie déprimée de la voûte] fortes bandes & crampons de fer : soit autreque le surplus [bandeau décoratif] du plat- ment, ainsi qu’ils le jugeront pour le mieux.
fond se fera avec clavaux, desquels les coupes
se prendront sur un point commun, situé di- *
rectement au dessous de la clef, & distant * *
d’icelle plus ou moins selon que la force desdites coupes, eu égard à l’estenduë du plat-
François Blondel (~1618-1686)fond, l’exigera.

Citation 11. Blondel (1675, p. 434)Citation 10. Derand (1643, p. 432-433)
Toute leur force consiste en la couppe de [A propos de l’escalier suspendu, en arc de
leurs claveaux, & de plus souvent on prendcloître, & à repos]
pour centre des lignes de leurs ioints de teste,Il est bon que vous remarquiez icy que ces
le sommet d’un triangle équilatéral renversé,escaliers suspendus, & faits de pierre, ne se
dont la base est la largeur de l’ouverture surfont ordinairement qu’au premier étage où ils
qui la Platte-bande est assise. Le nombre desse terminent sans monter plus haut. Je dis
claveaux qui doit estre impair comme celuyfaits de pierre ; car si on les veut faire monter
des voussoirs des Arcs, aﬁn qu’il y en ait unjusques aux estages plus élevez on les conti-
dans le milieu qui serve de clef.nuë ordinairement de charpente. Mais à mon
aduis le meilleur est de les terminer au pre- Citation 12. Blondel (1675, p. 434)
mier estage, employant le reste de la hauteur
du bastiment à former quelque beau dôme, [A propos des plates-bandes : ] L’on y met
pour les rendre par ce moyen plus nobles & même souvent des barres de fer pour les forspe[a]cieux ; & alors à costé d’iceux on fera tiﬁer, mais cette précaution n’est pas pour les
quelque autre escalier qui servira pour mon- rendre de longue durée, car le fer ronge la
ter aux autres estages. Or la raison pourquoy pierre & la fait rompre avec le temps
on ne fait point passer ces escaliers suspendus faits de massonnerie au delà du premier *
estage, se tire de la disproportion qui arri- * *
veroit pour lors, & qui se trouveroit entre la
charge de leur massonnerie, & la force qu’ils
André Félibien (1619-1695)tirent des coupes de leurs voussoirs, laquelle
estant de soy fort limitée, il est necessaire de Citation 13. Félibien (1676, p. 698)
ne luy donner de faix, sinon autant qu’elle en
Platte-bande qui termine l’architrave depeut porter : or il arriveroit sans doute souvent qu’on luy en donneroit par excez, si on l’ordre Dorique ; c’est la Fasce qui passe imfaisoit servir ces escaliers au delà du premier mediatement sous les Tryglyphes, & qui est à
estage. Et par eﬀet nous voyons que pour af- cet Ordre ce que la Cymaise est aux autres.
fermir ces ouvrages, lors mesme qu’ils sont Les Grecs l’appellent Tænia, Quelques Arterminez à la hauteur du premier estage, on chitectes donnent ce mesme nom à la partie
a de coustume d’y employer quantité de fer, qui est au dessus des tryglyphes & que Vitr.
pour donner plus de soustenuë & de fermeté nomme leur chapiteau.
aux liaisons des pierres, qui les composent, & Platte-bande ou Fasce des champour mieux lier le tout avec les gros murs, qui branles. Vitr. l’appelle Corsa, l. 4. c. 6.

310

<!-- p. 312 -->

Annexe A. Sources bibliographiques

Le mot de Platte-bande se donne aussi Outre les Portes rondes & quarrées, il y en a
à plusieurs autres membre d’Architecture qui d’autres qui approchent de ces ﬁgures, comme
n’ont qu’un largeur sans ornemens ny beau- celle dont le cintre est en anse de panier, &
coup de saillie. V. p.171 176. Pl. XXVIII surbaissé ; & enﬁn d’autres qui sont bombées
ou un peu cintrées dans leur Plattebande, &
\* dont le trait le plus parfait est la portion de
\* * cercle qui se fait sur la Base d’un Triangle
équilatéral, dont le sommet est le centre.

Henri Sauval (1620-1676) Citation 17. D’Aviler (1691, p. 122)

Citation 14. Sauval (1724b, p. 626) [A propos de la porte rustique d’ordre toscan]
Les Claveaux de la platte-bande sont tirez du [A propos de la place Royale, actuelle place
même centre B, qui est le sommet d’un Tri-des Vosges] Les trente-cinq autre Pavillons
angle équilatéral dont la platte-bande fait lasont portés au premier étage sur une longue
longueur de la Baie [...]suite d’arcades larges de huit pieds & demi,
haute de douze ou environ, ornées de pilastres
Citation 18. D’Aviler (1691, p. 237)doriques, sans architrave, frise ni corniche qui
regne à l’entour de la Place, & devant com- Toutes les bayes se ferment ou par cintres,
posent un portique large de deux toises, cou- dont les pierres se nomment voussoirs, ou par
vert d’une voute surbaissée ou plate, presque Platebandes avec des claveaux.
par tout faire de brique & de pierre, en
quelques endroits de plâtre simplement, mais Citation 19. D’Aviler (1691, p. 237-238)
semblables pour la couleur. Chaque voussoir a six faces, deux panneaux
Citation 15. Sauval (1724a, p. 32) de doüelle, dont l’un est intérieur ou d’intra-
dos, & l’autre exterieur, ou d’extrados ; deux
[A propos des façades du Louvre] Chacun ad- panneaux de teste, dont l’un de front fait le
mire la grande dureté & l’éclat de toutes les parement de l’Arc par devant, & l’autre papierres qui ont été employées pour ce superbe roist derriere si la pierre fait parpin, & deux
édiﬁce ; les joints en sont si imperceptibles panneaux de lits qui sont cachés dans le corps
aux yeux des plus clair-voyants, qu’on ne sau- de la Maçonnerie, tous ces panneaux sont oproit se lasser d’admirer la curiosité de l’Ar- posés. Les joints sont ou de lit ou de teste,
chitecte, & la patience des ouvriers ; en eﬀet qu’on nomme aussi joints de coupe, qui sont
toutes sont si bien cimentées qu’il semble que les joints en rayons tirés du centre des arcs
ce grand bâtiment ne soit qu’une seule pierre, de plein cintre. Il y a aussi des joints monsurtout le pavillon du Roi ; qui de plus, pen- tans & des joints de lit ou de niveau dans les
dant près d’un siècle s’est conservé de haut en cours d’assises, & ce dernier joint doit suivre
bas sans fraction, & même paroît encore au- le lit de la carrire, car autrement la pierre sejourd’hui uni, & aussi luisant que s’il étoit de roit mise en delit ; ce qui s’observe aussi aux
marbre ; & s’il en faut croire tous les Maîtres, Arcs & Voûtes où les joints de lit sont ceux
il durera plus que le monde. [...] de la carriere, sans quoi la ruine des voûtes
La même solidité que Mornac admire sur de Plattebandes arrive souvent par cette mal
les murailles de ce pavillon [pavillon du roi façon.
de Lescot], se remarque dans tout le reste du
bâtiment [...] Citation 20. D’Aviler (1691, p. 572)

On dit qu’une PlateBande est en Fausse-
\*
coupe, lorsque les joints de ses claveaux fort
\* *
épais, dont seulement à plomb au parement,
de la profondeur d’environ six pouces [15 cm],
Augustin-Charles d’Aviler (1653- le reste du joint estant incliné selon la Coup.
\1701) Les Platebandes des Portes d’enﬁlade du Bâ-
timent neuf du Louvre devant la Riviere, sont
Citation 16. D’Aviler (1691, p. 116) apareillées de cette maniere. Pl. 66 A p.237

311

<!-- p. 313 -->

Annexe A. Sources bibliographiques

Citation 21. D’Aviler (1691, p. 764) Henri Gautier (1660-1737)

PLATEBANDE. Moulure quarrée plus haute
Citation 23. Gautier (1717)
que saillante, comme sont les faces d’un
Architrave, & la Platebande des Modillons Les Claveaux entre B & C de la Platebande,
d’une Corniche. Pl. 11 p.31 & c. La Plate- Planche 2, Figure 4, sont faits à redans, qu’on
bande est signiﬁée dans Vitruve par ces mots dispose encore d’autre maniere. Il y en a qui
Fascia, Tœnia & Corsa. les estiment mieux ainsi que tout unis, comme
sont ceux qui sont entre B & A autre façon qui
Platebande de baye ; c’est la ferme-
dépend encore du génie de l’Architecte, pour
ture quarrée, qui sert de Linteau, à une Porte
lesquels il y a divers sentimens. Plus il y a de
ou à une Fenestre, & qui est faite d’une piece
façon dans la coupe, disent les uns, plus il y
ou de plusieurs claveaux. Pl. 66 A p.237. &c.
a de la diﬃculté, & par consequent sujets à
Platebande bombée & reglée ; c’est plus de défectuosité. Et plus les choses sont
la fermeture ou Linteau d’une Porte ou d’une simples & unies, & sans composition, plus
Croisée, qui est bombé dans l’embraure ou elles ont de la resistance, & sont taillées plus
dans le tableau, & droit par son proﬁl. ibid. justes, comme sont les Clavaux entre A & B,
Platebande circulaire, celle d’un sans retour.
Temple ou d’un Porche de ﬁgure ronde,
comme la Platebande de l’Entablement Io- Voir ﬁg. 6.34 p. 120
nique de l’Eglise de Saint André sur le Qui- *
rinal à Rome, qui subsiste avec beaucoup de * *
portée par l’artiﬁce de son apareil.
Platebande arasée, celle dont les cla- Augustin-Claude Tiercelet
veaux sont à testes égales en hauteur, & ne
font point de liaison avec les Assises de des- L’architecture moderne est publié de fasus, ibid. çon anonyme par l’éditeur Claude Jombert
[...] à Paris en 1728. Ce traité d’architecture en
deux tomes, fortement inspiré de Manière Platebande de fer. Barre de fer en-
de bastir pour toutes sortes de personnes de
castrée sous les claveaux d’une Platebande de
Le Muet (1623), initialement attribué par erpierre, dont elle soulage la portée. pag. 218.
reur à Charles Étienne Brisieux, est l’œuvre
de Gilles Tiercelet, ou Augustin-Claude Tier-
\* celet (ﬁls du premier). Nous retenons ici l’at-
\* * tribution de Pérouse de Montclos (1982) du
traité à Augustin-Claude Tiercelet.

Les deux évocations des plates-bandes ciPhilippe de La Hire (1640-1718) dessous font référence à une partie ultérieure
du livre concernant la coupe des pierres pour
Citation 22. De La Hire (1712, p. 75)
plus de détails. Cependant ce « petit traité »
Il y a encore une autre espèce de Voûte ou concernant le détail de la coupe des pierres
de fermeture d’un pied-droit à un autre qu’on qui devait faire partie d’un troisième volume
appelle en platte-bande, à cause que le des- n’a ﬁnalement pas été rédigé, ce qu’indique
sous est une superﬁcie plane & non pas courbe la seconde édition de 1764 (p. vi). La citacomme dans les Voûtes ordinaires. Les pierres tion 24 renvoit d’ailleurs à une ﬁgure repréde cette plate-bande qui sont taillées en coupe sentant une plate-bande en fausse-coupe (évoou en coin, & dont les joints tendent ordinai- quée après dans la citation), et non à une
rement en un point comme centre, s’appellent voûte composée de voussoirs à crossettes.
Clavaux & non Voussoirs, comme dans les
Voûtes. Citation 24. Tiercelet (1728, p. 53)
Il seroit à propos de joindre les Voussoirs par
\* crochets aux Voûtes où l’on ne fait pas une
\* * bonne butée (comme le fait voir la Figure 14.)

312

<!-- p. 314 -->

Annexe A. Sources bibliographiques

Ensorte que les crochets ne paroissent pas par rencontrer GI, marquent la ﬁgure & la grandehors, ce qu’on fera mieux connoître dans le deur des clavaux.
petit Traité de la coupe des Pierres qui sera
Voir ﬁg. 6.32 p. 118une partie de ce Livre, en y parlant de la maniere de bander les croisées par joints perpen- Citation 27. Bélidor (1729, Livre II p. 40)
diculaires à l’imitation de celles du Louvre.
La plate-Bande est de toutes les Voûtes celle
qu’il a le plus de poussée, & qui a le moins
de force ; c’est pourquoi elle n’est pas d’usage
pour les Fortiﬁcations, ne s’employant guére
que dans les grands édiﬁces & avec des dé-
penses considerables à cause des barres de
fer dont ont se sert pour soulager les piés-
droits, & pour lier les clavaux ensemble.

Citation 28. Bélidor (1729, Livre II p. 61)

Mr Abeille Ingenieur du Canal de Picardie, a
Plate-bande en fausse-coupe, d’après Tierce- imaginé une construction de plate-Bande fort
let, 1728, p. 50 ingenieuse, la coupe des Clavaux en est sin-
guliere & contribuë beaucoup à diminuer la
Citation 25. Tiercelet (1728, p. 61)
poussée que les piés-droits auroient à soûte-
La largeur des Croisées doit être proportion- nir, j’en aurois volontiers fait la description
née à la grandeur & hauteur des Apparte- si elle étoit venuë à ma connoissance avant
mens, leur forme la plus belle est bombée, que les planches de ce second Livre fussent
dont l’Arc ait pour centre le sommet d’un Tri- gravées.
angle équilatéral, les Cintrées ne conviennent
qu’à des Palais, ou dans le milieu & l’extremi- *
tez d’une grande façade ; pour la solidité, soit * *
qu’elles soient bombées ou en plattes-bandes,
il faut que le nombre des Voussoirs soit im-
Amédée Frézier (1682-1773)pair, & que tous les joints paroissent tendre
au centre, ou que la coupe soit faite de façon Citation 29. Frézier (1737, p. 280)
que les joints paroissent perpendiculaires. On
donnera par la suite la coupe de l’une & de Seconde règle. Diviser le Ceintre Primitif en
l’autre de ces Croisées. autant de parties égales qu’on veut avoir de
rangs de Pierres ou Voussoirs, & régulière-
ment en nombre impair. *
\* * [...]
Nous ajoutons que les divisions doivent
être en nombre impair, aﬁn qu’il ne se trouve
Bernard Forest de Bélidor (1697- point de joint au milieu du ceintre ; mais une
\1761) Pierre également appuyée sur les deux côtez
de la voute qu’elle doit ferme dans l’exécuCitation 26. Bélidor (1729, Livre II p. 39)
tion, on l’appelle pour cette raison la Clef,
La premiere chose dont il faut être pré- nom qui n’est pas aﬀecté à une seule Pierre,
venu, est que pour avoir la cupe des cla- mais au rang de voussoirs qui est le plus
vaux qui doivent composer une plate-Bande, élevé : ce n’est pas qu’un joint sur le milieu
on trace un triangle équilatérale ALF sur la d’un ceintre tirât beaucoup de conséquence
ligne LF qui exprime la largeur de la plate- pour la solidité ; mais il choqueroit la vuë &
bande, ensuite on divise cette largeur en au- la bonne ordonnance.
tant de parties égales, qu’on voit à peu-près
Citation 30. Frézier (1737, p. 281-282)qu’elle doit contenir de claveaux, & du point
A comme centre on tire des lignes qui passent Troisième règle. Diviser les Arcs extepar chaque point de division, lesquelles allant rieur & interieur du Ceintre Primitif, qui

313

<!-- p. 315 -->

Annexe A. Sources bibliographiques

comprennent l’épaisseur de la Voute en Par- ment ; ce que nous ferons remarquer au Livre
ties proportionnelles par des perpendiculaires suivant, en donnant les moyens d’y remédier.
à ces Arcs, aux points de leur Divisions, pour
Citation 31. Frézier (1738, p. 64)régler l’inclinaison des joins de Tête.
Il faut remarquer que les pierres qui com- [...]
posent les voutes de ces trois espèces [plates-
La premiere raison sur laquelle est fon-
bandes, voutes plates, trompes plates] s’apdée cette division proportionelle de l’arc ex-
pellent Claveaux, à la diﬀérence de celles des
terieur & de l’interieur, qui comprennent
voutes concaves, qui s’appellent Voussoirs.
l’épaisseur de la voute, concerne la solidité,
parce que les têtes des voussoirs devienent Citation 32. Frézier (1738, p. 64)
par cette construction, en forme de coin, plus On peut tracer l’épure de cette espèce de voute
large du côté exterieur que de l’interieur, la [Platebande] de plusieurs manieres, qui recirconference de l’un étant plus grande que viennent toutes à la même ﬁn, dans lesquelles
celle de l’autre, les parties aliquotes en sont il y a plus de disposition de goût que de Géoaussi plus grandes ; de sorte que la Pierre ne métrie, & l’on peut dire que la solution de ce
peut passer par l’ouverture inferieure de l’in- Problème est assez arbitraire pour la détermitervale de deux voussoirs, qui est plus etroit à nation de l’inclinaison des joints en lit ; car
la Doele qu’à l’Extrados ; ainsi étant pressée à considerer la construction de la plate-bande
par la pesanteur contre les voussoirs Collate- dans la rigueur Méchanique, pourvû que les
raux, qui se servent mutuellement d’appui les claveaux soient pyramidaux, & bien butez ils
uns aux autres, elle est soutenuë en l’air par doivent se soutenir ; parce que la partie sula résistance des derniers appuis, qui sont les périeure est plus grande que l’ouverture inféPiedroits, lesquels doivent avoir assez de force rieure, entre ls appuis de ces tronçons de pypour contrebalancer l’eﬀort que ces voussoirs ramide renversée.
ou especes de coins font pour les écarter.
Citation 33. Frézier (1738, p. 65-66) Nous avons encore deux autres raisons de
cette construction ; la premiere concerne la Je baisse le centre de la coupe un peu plus
Simetrie, aﬁn de conserver toujours une in- que le sommet du triangle équilateral, auquel
clinaison uniforme des joins de tête sur la les Architectes s’assujettissent ; parce que la
courbe du Ceintre ; car quand même les par- coupe Aa ou Bb du sommier en est un peu
ties de l’arc exterieur & de l’interieur ne se- moins oblique, & celle des claveaux donne des
roient pas proportionelles, la voute n’en sub- parties un peu moins inégales, & des angles
sisteroit pas moins, pourvu que celles de l’in- q & s moins aigus auprès du sommier AL, ou
terieur soient toujours plus petites que celles BN ; en eﬀet les arêtes du joint de lit de ce
de l’exterieur, il n’en résulteroit d’inconvé- premier claveau sont si aiguës ordinairement,
nient que de la diﬀormité, & une inégale im- qu’elles se cassent à la charge pour peu que
pulsion des voussoirs contre les Collateraux. la pierre soit fragile. Les Architectes pour ob-
La seconde raison est pour une plus vier à cet inconvenient ont imaginé de faire
grande solidité, parce que les plans qui passent une portion de joint à plomb comme ir, qui
par les joins de tête, qu’on appelle les lits, fait un coude dans le joint zir, & un pli dans
étant perpendiculaires à la tangente de l’arc le contigu, c’est-à-dire un angle saillant dans
au point de la division, font avec la Doele l’un & rentrant dans l’autre claveau.
de part & d’autre le plus grande angle qu’ils Mais il faut remarquer que ce retour
puissent faire, qui est le Droit, ou inﬁniment d’équerre sur le platfond AB, est autant de
peu diﬀerent du Droit ; car si on le faisoit ob- retranché de la longueur de la coupe inclinée,
tus d’un côté, il rendroit l’autre aigu. qui fait le support des claveaux, & par consé-
Or il importe que les résistance des quent une diminution sur la force de la plaArêtes, c’est-à-dire, des angles des Pierres, tebande, qu’il ne faut plus compter de q en z,
soient égales pour porter également la charge, mais de i en z ; parce que la partie verticale ir
car il est clair que la plus forte feroit casser la est inutile pour l’appui.
plus foible, comme l’expérience le fait voir aux D’où l’on doit conclure, que, lorsque les
platebandes, où l’on est forcé d’en agir autre- butées des piedroits sont bonnes, il convient

314

<!-- p. 316 -->

Annexe A. Sources bibliographiques

de prendre le centre encore plus bas que je deux au moins à chaque lit, ce qui est d’une
ne le propose ; parce que les angles des pre- exécution très facile ; puisqu’il ne s’agit que
miers claveaux en deviendront plus forts, les d’y pratiquer deux cavitez égales & bien égainclinaisons des lits moints diﬀerentes, & les lement placées ; quoique cette invention soit
claveaux plus uniformes à la vue ; puisque nouvelle, il me semble que la raison en assure
leurs extrados augmentent sur l’égalite des di- le succès.
visions de la moitié de l’arc FB dans le rap- D’autres Architectes au lieu de ressaut
port des tangentes. dans le milieu des claveaux en font au des-
[...] sus de l’extrados, qui se surpassent les unes
les autres par des crochets, appelez Crossettes, « Il faut seulement remarquer que Mr de
en s’élevant jusqu’à la clef, comme on voitla Hire, & ceux qui l’ont suivi ont réglé le cal-
en H7x ; cet artiﬁce est plus sur que le pré-cul de la poussée des platebandes sur le sis-
cedent, mais il n’est propre qu’à des portestème de l’inclinaison des lits des sommiers
rustiques, & ne seroit pas bien au dessusau triangle équilatéral, ce qui soit dit en pas-
d’une Architrave.sant, pour y faire attention dans la recherche
de l’épaisseur des piedroits. »
Voir ﬁg. 6.23 p. 105

Voir ﬁg. 6.23 p. 105 Citation 36. Frézier (1738, p. 67)

Citation 34. Frézier (1738, p. 66) Enﬁn les plus timides fortiﬁent les plate-
bandes par des barres de fer dont ils traversent
Quelques Architectes pour plus de simetrie &
les claveaux, ou par dedans ou par derrière,
d’uniformité se contentent de régler l’inclinai-
ou par dessous, ce dernier est le plus désason de la coupe des sommiers à l’angle de
gréable à la vue & le plus mauvais : car le fer
soixante degrez, par le moyen du triangle équi-
n’est pas d’une rigidité inﬂexible, il plie sous
latéral ; après quoi ils ne font plus d’usage du
la charge, comme on le voit en plusieurs encentre S ; mais ils divisent l’intrados AB &
droits ; il faut avouer que le fer est le grand
l’extrados ab en un même nombre de parties
antidote contre les aﬀaissemens de cette eségales, & tirent les joints de tête de l’un à
pèce de voute, cependant lorsque les butées
l’autre par les divisions correspondantes nx,
sont bonnes, & la pierre dont les claveaux sont
oy, qz ; tout cela se peut sans inconvénient.
faits, de bonne consistance, qu’on a soin de
décharger la platebande du fardeau qui est auCitation 35. Frézier (1738, p. 66)
dessus, par une Arcade apparente ou cachée,
Il nous reste à dire quelque chose des moyens on peut s’en épargner la dépense mettant en
de donner de la solidité à ce genre de voute, usage l’expedient que je propose.
où les pierres sont dans une situation plus forcée que dans toute autre. Citation 37. Frézier (1738, p. 67)
Pour cela les Architectes se sont avisez Quelques Architectes au lieu de faire les
de diﬀérens expédiens. Les uns sont des res- joints apparens inclinez, comme ils doivent
sauts ou redens, comme on voit en gm, cf, i2 être, les ont fait à plomb, comme on en voit
au milieu du joint ; mais c’est une diﬀormité au dedans du vieux Louvre, ce que l’on apqui n’est supportable que lorsqu’ils sont cachez pelle en fausse coupe ; mais puisqu’une telle
par quelques moulures, comme lorsque la pla- situation de pierres sans support n’est pas natebande est taillée en Architrave, & que le res- turelle, elle n’est pas belle selon moi ; elle
saut est caché sous la saillie d’une face. Pour ne surprend point le spectateur, & ne fait
moi je préfère à cet artiﬁce l’uniformité des point admirer l’industrie de l’Architecte par
joints unis qui s’aﬀaissent aussi plus égale- les connoisseurs ; on conjecture bien que les
ment à la charge de la platebande. Je voudrois claveaux sont soutenus ou par des barres de
cependant pour empécher les claveaux de cou- fer ou par de bonnes coupes, pratiquées au deler le long de leurs joints en lit y faire de pe- dans des fausses, qui ne sont qu’un trompeuse
tites cavitez hemispériques, propres à y loger apparence, comme on voir à la ﬁg. 34.a
une balle de plomb d’un pouce de diamètre,
moitié dans chaque claveau, & y en mettre Citation 38. Frézier (1738, p. 67-68)

315

<!-- p. 317 -->

Annexe A. Sources bibliographiques

Quoique le détail de la construction ne soit Citation 41. Frézier (1738, p. 69)
pas de notre sujet, je crois devoir avertir Quoique le principal usage des platebandes
que quelque exactitude qu’on apporte à l’appa- soit de suppléer à la grandeur des pierres,
reil & à la pose des plates-bandes, on ne doit qu’il faudroit employer pour faire les fermejamais les faire horizontales sur leur étaye- tures ou Linteaux des portes, & des Archiment, mais un peu bombées ; parce qu’en otant traves d’une seule pièce, com-[ ?] les anciens
leur support elles s’abbaissent toujours un peu le pratiquoient, on emploïe aussi le même
vers le milieu ; on ne peut dire de combien Trait & appareil à faire les voutes plates endoit être cet exhaussement, pour que la charge tieres aux endroits où l’on a pas assez de haumette le platfond de niveau ; cela dépend, 1.◦ teur, pour y en faire de concaves, dont il faude la longueur de la portée, 2.◦du nombre des droit prendre la naissance trop près de terre.
claveaux, 3.◦de la quantité de la pierre, & de [...]
l’adresse des Ouvriers qui la taillent, 4.◦&
enﬁn de l’attention à les poser & ferrer au Citation 42. Frézier (1738, p. 72)
joint.
[A propos de l’inclinaison des joints de la
[...] voûte d’Abeille :] Cette inclinaison devroit
Les Appareilleurs croyent qu’il faut que être réglée à l’angle de 45 degrez, pour que
les platebandes bombent un peu, prévenus la partie horizontale de l’appui fut égale à la
qu’elles paroissent bomber en Contrebas, hauteur de l’épaisseur du claveau ; cependant
quand elles sont exactement de niveau ; c’est à cause que cette inclinaison donne une arête
une erreur que l’optique condamne dans un peu foible, on peut augmenter le nombre
d’aussi petites longueurs que celle qu’on peut des degrez de l’ouverture, mais on augmendonner à leur portée ; car celle dont nous ve- tera aussi la poussée ; parce que la partie honons de parler est peut être la plus grande qui rizontale de la coupe, dans laquelle consiste
ait été exécutée, encore ne peut-elle l’être à tout l’appui, diminuë à l’égard de l’épaisseur.
ce point qu’avec bien des précautions, & une Suivant la règle cette partie n’étant que le
qualité de pierre d’une forte consistance. tiers de l’épaisseur, l’angle aigu sera de 71
degrez 34’ [soit ϕ = π −71 −34/60 = 18,4◦],
Citation 39. Frézier (1738, p. 68) qui a pour tanfente le triple du sinus total, ce
qui donne un angle fort ouvert, & par consé- A propos de pierre forte, je dirai qu’il s’en
quent beaucoup de poussée sans nécessité ; autrouve de telle, qu’on lui fait des tenons &
reste comme les ﬁgures du recueil ne s’ac-des queues d’yronde, comme à la menuiserie ;
cordent pas avec cette partie du discours, ondes témoins occulaires m’ont dit avoir vu en
peut soupçonner qu’il y a quelque erreur dansLanguedoc des platebandes se soutenir avec
l’un ou dans l’autre.très peu de butée, & qu’en ayant approfondi
la construction, ils ont trouvé les claveaux liez
entr’eux par des tenons à queue d’yronde, lo- *
gez dans des mortoises, à peu près comme on * *
en voit assez souvent aux bahus des gardefous
des ponts Fig. 34.e [ﬁg. 6.23 p. 105]
Encyclopédie de Diderot et
Citation 40. Frézier (1738, p. 69) d’Alembert

Ce nom [voute plate] est aussi nouveau que Les textes de l’Encyclopédie ont été pul’invention de ces voutes, qui ne sont pas des bliés de 1751 à 1765 en 17 volumes, et les
platebandes, en ce qu’elles butent de quatre planches de 1762 à 1772 en 11 volumes. L’aucôtez, & que les claveaux sont faits tout diﬀe- teur de l’article sur la fausse-coupe est Louisremment. Jacques Goussier (1722-1799), dont les ar-
L’Epoque de cette invention que nous te- ticles sont signés par la lettre (D). Les auteurs
nons de M. Abeille, fameux Architecte, qui a des articles plate-bande et voûte (comprenant
été dans le Corps des Ingénieurs, est de l’an- la description des voûtes plates) ne sont pas
née 1699, suivant la date de l’approbation de connus avec certitude, mais il pourrait s’agir
l’Académie des Sciences. de Louis-Jacques Goussier qui a écrit sur les

316

<!-- p. 318 -->

Annexe A. Sources bibliographiques

sujets concernant la coupe des pierres, ou J.- claveaux, & non pas voussoirs, comme aux
F. Blondel (1705-1774) qui a écrit sur l’archi- autres voûtes.
tecture (1)
Citation 46. Diderot et d’Alembert (1765a)
Citation 43. Diderot et d’Alembert (1751)
La longueur de la plate-bande entre les piés
Les arcs en tiers & quart-point, comme droits, s’appelle portée ; c’est le genre de voûte
s’expriment quelques ouvriers d’Angleterre, qui a le plus de poussée, c’est-à-dire qui fait
quoique les Italiens les appellent di terzo & le plus d’eﬀort pour renverser les piés droits.
quarto acuto, parce qu’à leur sommet ils font Cet eﬀort est d’autant plus grand que le point
toûjours un angle aigu, sont deux arcs de E ﬁg. 22. où se réunissent les joints de lits, est
cercle qui se rencontrent en formant un angle plus éloigné de la plate-bande AB, & il est en
par le haut, & qui se tirent de la division de même proportion que l’aire du triangle AEB.
la corde en trois ou quatres parties à volonté.
Citation 47. Diderot et d’Alembert (1765a)
Citation 44. Diderot et d’Alembert (1756)
Comme on ne peut faire les angles CCB, que
Fausse-coupe, s. f. (Coupe des pierres.) c’est font les joints avec la plate-bande, aigus que
la direction d’un joint de lit oblique à l’arc jusqu’à un certain point, parce qu’il pourroit
du ceintre, auquel il doit être perpendiculaire s’y faire des balevres, & qu’il est d’ailleurs espour être en bonne coupe. Les joints CD, CD, sentiel de diminuer la poussée autant qu’il est
(ﬁgure 13.) sont en bonne coupe, parce qu’ils possible, on s’est avisé de faire les joints de
sont perpendiculaires à la courbe, & les joints lits des claveaux de deux parties ; comme on
mn, mn, sont en fausse-coupe. voit du côté A de la même ﬁgure, en laissant
Lorsque la voûte est plate comme aux un repos horisontal à chaque claveau pour replates-bandes, ce doit être tout le contraire ; cevoir la saillie de son voisin. Ce qui a assez
la bonne coupe doit être oblique à l’intrados, bien réussi, surtout depuis qu’on a remédié à
comme sont les joints mn, mn, (ﬁg. 14.) au l’inconvénient de ne pas pouvoir facilement ﬁplat-fond AB, pour que les claveaux soient cher les joints, en faisant une grande breche
faits plus larges par le haut que par le bas ; A, au ressaut qui empêchoit l’introduction du
car si les joints sont perpendiculaires à la mortier, ainsi que l’on peut voir à la ﬁg. 2. qui
platebande, les claveaux deviennent d’égale représente un claveau séparé, & un en persépaisseur & sont alors en fausse-coupe, & pective.
ne peuvent se soûtenir que par le moyen des
Citation 48. Diderot et d’Alembert (1765b)
barres de fer qu’on leur donne pour support,
ou par une bonne coupe cachée sous la face On préfere dans bien des cas les voûtes
à quelques pouces d’épaisseur, comme on en plates, parce qu’elles donnent à la piece plus
voit aux portes & aux fenêtres du vieux louvre de hauteur & d’élévation, & que d’ailleurs
à Paris, dont voici la construction. ABCD elles sont plus fermes & plus durables. Voyez
(ﬁg. 15.) représente la face d’une plate-bande ; Platfond, Plancher, &c.
CD est l’intrados ; ABFE est l’extrados en
Citation 49. Diderot et d’Alembert (1765b)
perspective ; mn, mn, est la fausse-coupe apparente ; no, no, est la bonne coupe qui est Mais il arrive toujours que cet eﬀort [sur les
enfoncée dans la plate-bande de la quantité faces latérales du claveau considéré] est d’aumr de trois ou quatre pouces d’épaisseur, & tant plus grand, que les plans inclinés le sont
occupe l’espace rst. La ﬁgure 2. représente la moins ; de sorte que s’ils étoient inﬁniment
clé, & la ﬁgure 3. un des autres voussoirs, où peu inclinés, c’est-à-dire, s’ils étoient perpenl’on voit une partie concave nrst, propre à re- diculaires à l’horison aussi bien que la clé,
cevoir la partie convexe nrotv de la clé, & une elle tendroit à tomber avec tout son poids, &
partie convexe nrotv (ﬁgure 3.) propre à être tomberoit actuellement, à-moins que le morreçue dans la cavité du voussoir prochain. (D) tier ne la retînt.

Citation 45. Diderot et d’Alembert (1765a) Citation 50. Diderot et d’Alembert (1765b)

Les pierres qui en sont les parties, s’appellent Voûte plane. Il y a en général deux manieres

(1). Source : The ARTFL Project, http://encyclopedie.uchicago.edu/, consulté le 25/05/2017.

317

<!-- p. 319 -->

Annexe A. Sources bibliographiques

de les faire : si on avoit des pierres assez qu’elles s’appuient réciproquement le bout de
grandes pour pouvoir couvrit de grands appar- l’une sur le milieu de l’autre, duquel arrangetemens, la voûte plane seroit bientôt faite ; il ment on voit la représentation dans la ﬁg. 33.
n’y auroit qu’à tailler la pierre A en biseau On ne peut douter que les voûtes plates de
ou talud renversé ab sur les bords, ensorte la seconde maniere n’aient été imitées de cette
que la pierre fût une pyramide tronquée & charpente ; car si on considere chaque paralrenversée, ainsi qu’elle est représentée dans lélogramme de l’extrados comme une piece de
la ﬁgure [30] à la lettre A, & le haut des bois, ﬁg. 34. on verra qu’on a suppléé aux enmurs de la chambre en talud BCD pour servir tailles & aux tenons de la ﬁg. 33. par des tade coussinets à la pierre A ; si on l’applique luds sur les côtés, & des coupes en sur-plomb
alors dans l’espece d’entonnoir BCDE, il est sur les bouts ; les uns & les autres conserévident qu’elle ne pourra point tomber en-bas, vant toujours cette sorte d’arrangement, que
à cause que l’ouverture de chambre est plus les architectes appellent à batons rompus.
petite que sa grande base. Mais ce qui rend l’invention de cette voûte
Mais comme on ne trouve pas de pierre plus ingénieuse que celle de la charpente, c’est
assez grande pour faire les planchers d’une que par le moyen de ces sur-plombs & de ces
seule piece, on est obligé de les faire de diﬀé- taluds prolongés, on remplit le vuide (qui reste
rens morceaux, qui réunis font le même eﬀet. entre les poutrelles), dans le parement infé-
Supposons qu’au lieu de grandes pierres, rieur, où l’on forme un plafond continu, tout
on ne trouvât que des anneaux Q R S T, composé de quarrés parfaits arrangés de-suite
ﬁg. 31. no. 2. de diﬀérentes grandeurs, & per- en échiquier, ﬁg. 35. qu’on appelle en archicés à jour en talud mn, & ayant un talud ren- tecture en déliaison, ce qui en rend l’artiﬁce
versé TV, en tout semblable au talud ab de digne d’admiration : il n’en est pas de même
notre grande pierre. Si on en met plusieurs dans la surface supérieure, elle ne peut être
les uns dans les autres, comme la ﬁg. 31. le re- continue, parce que les coupes des taluds resprésente ; leur assemblage formera une voûte tent en partie découvertes, de-sorte qu’il s’y
plate, que l’on pourroit comparer au marc forme des vuides en pyramides quarrées rendont se servent les orfevres. Mais comme on versées a b c d e, ﬁg. 36. qui représente l’exne trouve pas non plus de pierre assez grande trados de cette voûte, dont l’inventeur est M.
pour faire les anneaux d’une seule piece, on Abeille. Ces vuides donnent occasion de faire
les fait de plusieurs parties, qu’il faut obser- un compartiment de pavé agréable & varié,
ver de poser en liaison. Voyez Liaison. parce qu’on peut y mettre des carreaux dif-
férens de celles des premieres pierres.
Tous les joints de cette sorte de voûte,
Cette interruption de continuité a donnétant ceux de lit (qui sont ceux qui séparent
occasion au pere Sebastien & à M. Frezier,les anneaux les uns des autres), que ceux de
de chercher les moyens de remplir les vuidestête, doivent concourir au sommet commun
pyramidaux par des claveaux mixtes. Le pereP des pyramides renversées, dont nous avons
Sebastien en a inventé dont les joints au taludsupposé les tronçons enﬁlés les uns dans les
sont des surfaces gauches, & M. Frezier en aautres.
trouvé de deux sortes, dont voici les exemples.
La ﬁgure L M N O, ﬁg. 32. représente A, ﬁg. 37. no. 2. représente un claveau vu par
l’épure de cette sorte de voûte. Si la chambre la surface inférieure. B, représente le même
étoit ronde, les rangs de claveaux seroient des claveau vu par-dessus, & la ﬁgure 37. l’extratronçons de cône. dos de cette voûte.
L’autre maniere de voûte est représentée,Citation 51. Diderot et d’Alembert (1765b)
ﬁg. 38. l’extrados est tout composé de quarrés,
La seconde maniere de construire les voûtes lesquels sont précisement la moitié de ceux
plates est fondée sur une invention de Serlio, de la doelle. Un des claveaux est représenté
qui a donné une maniere de faire des plan- par-dessus & par-dessous aux ﬁgures a & b,
chers avec des poutrelles trop courtes pour ﬁg. 38. no. 2.
être appuyées sur les murs de part & d’autre :
c’est une certaine disposition qui consiste *
à les faire croiser alternativement, ensorte * *

318

<!-- p. 320 -->

Annexe A. Sources bibliographiques

Jacques-François Blondel (1705- Citation 55. Blondel (1752, p. 114)
\1774) et Pierre Patte (1723-1814) Les croisées à plate-bande & bombées sont
celles dont on fait le plus d’usage ; les quarCitation 52. Blondel (1752, p. 108)
rées s’employent plus ordinairement dans les
Il se fait de trois especes de Portes ; celles ordonnances Toscane & Dorique. [...]
en Plein-ceintre, les Quarrées, & les Bom-
Les croisées bombées peuvent être plus élé-bées. Quelques Architectes modernes en ont
gantes que celles à plate-bande droite, maisintroduit une quatrième espece appelée sur-
il faut sçavoir que jamais, dans quelque or-baissée, ou en anse de panier ; mais le mau-
donnance que ce puissse être, elles ne doiventvais usage que plusieurs d’entre’eux en ont
surpasser en hauteur deux fois & demi leurfait, les a exclu de tout genre de décoration
largeur. On employe les premieres assez indis-régulière, aussi bien que les surmontées que
tinctement à tous les Ordres, à l’exception dules Gothiques avoient introduit dans leurs bâ-
Toscan, faisant attention que l’arc de cercletimens : & si quelque fois l’on fait des Portes
qui termine leur partie supérieure ne soit passurbaissées, ce ne doit être que pour des étages
trop ressenti, ainsi que nous l’avons recom-en soubassement, comme on l’a pratiqué à la
mandé (page 110) en parlant des portes deFontaine de la rue de Grenelle, aﬁn de rendre
cette espèces, Fig VI même Planche.leur hauteur plus en rapport avec leur largeur.

Citation 53. Blondel (1752, p. 110)
Voir ﬁg. 6.30 p. 115
La maniere de tracer les arcs d’une porte
bombée, est de les décrire du sommet d’un tri-
Citation 56. Blondel (1752, p. 156)
angle équilatéral, au moins, comme E (Figure
VI), ou du sommet d’un triangle isoscelle, au Il se fait aussi des voûtes plates qu’on nomme
plus, dont la perpendiculaire soit le double de à platebande, & qui sont d’usage dans les
la base, comme D, même Figure : variation grands édiﬁces où l’on introduit des Périqui doit dépendre de leur ouverture. Mais en styles, tels que celui du Louvre, ou des plagénéral il faut sçavoir que cet arc étant rendu fonds très-méplats, tels que celui du Vestibule
trop sensible, produit à l’oeil un mauvais ef- de l’hôtel de Matignon, à Paris, dont les clafet, parce qu’il ressemble à un plein ceintre veaux doivent êtres décrits du sommet d’un
corrompu, de même qu’en le faisant trop mé- triangle équilatéral, ainsi que ceux des arcs en
plat il ressemble à une plate-bande droite dont plein ceintre & surbaissés qui doivent tendre
l’exécution est viciseuse. aux foyers qui en ont déterminé la cherche.
Pour la propreté de l’appareil dans les plateVoir ﬁg. 6.30 p. 115 bandes droites du côté de leur parement, on
Citation 54. Blondel (1752, p. 113) aﬀecte que les joints soient perpendiculaires,
comme on le remarque au Louvre, ce qui n’af-
Pour nous conformer à l’usage de la déco-
foiblissant pas la solidité, donne à l’édiﬁce une
ration Françoise, qui est l’objet de ce Traité,
hardiesse apparente qui tient du merveilleux.
nous dirons que pour établir aux croisées une
proportion relative au caractere de chaque
Citation 57. Blondel et Patte (1777a, p. 52-édiﬁce, il faut avoir égard à la diversité de
53)leurs formes, lesquelles, ainsi que les portes,
doivent se réduire à trois especes, scavoir Il y a environ 80 ans que les appuis de
celles en plein ceintre, celles à plate-bande, & pierre des croisées embrassoient toute l’épaiscelles qu’on nomme bombées ; devant rejet- seur des murs, ce qui empêchoit de voir comter absolument les surbaissées, qui doivent en- modément dans la rue, & surchargeoit inutilecore moins faire l’objet de la décoration exté- ment les plates-bandes ou linteau des croisées
rieure des croisées que celle des portes, malgré inférieures ; mais maintenant il est d’usage
l’exemple qu’on en voit au nouveau bâtiment de supprimer l’épaisseur de l’embrasement, de
de l’Abbaye de St. Denis, & malgré la licence réduire le mur vers cet endroit à l’épaisseur
dont on use quelquefois de les faire à oreille, seule du tableau & de la feuillure ; ce qui est
ainsi qu’on en remarque dans plusieurs mai- très-bien raisonné pour la construction, & à
sons à Paris. la fois plus commode.

319

<!-- p. 321 -->

Annexe A. Sources bibliographiques

Citation 58. Blondel et Patte (1777a, On laisse souvent les poitrails apparents en
p. 266-267) dehors, en les enduisant d’une couleur de
pierre à l’huile : mais quelquefois on les recule On appelle Plate-bandes, des espèces de
d’un pouce de l’aﬄeurement du mur, pour lesvoûtes qui terminent le haut des bayes, des
latter, & y faire un enduit en plâtre badigeoné,portes, ou des croisées. Les unes sont droites,
où l’on grave des joints qui imitent une plate-ﬁgure VI ; les autres sont bombées, ﬁgure VII :
bande en pierre.leurs Claveaux ou Voussoirs i, tendent d’ordinaire au sommet d’un Triangle équilatéral Citation 61. Blondel et Patte (1777a,
g, dont la base est la longueur de la Plate- p. 290)
bande. On voit cependant dans la moitié de
Quelquefois on fait leurs grands paliers toutla ﬁgure VI, que les Joints h, sont perpen-
droits par dessous, quoiqu’entiérement bâtisdiculaires ; ce qui se pratique quelquefois en
en pierre ; mais alors on ne vient à bout dedevant d’une plate-bande pour le coup-d’œil,
contenir leurs claveaux ou voussoirs dans unemais l’intérieur desdits joints ne laisse pas
pareille position, qu’en mettant des T de ferpour cela de tendre vers le point g, ainsi qu’il
dans leurs joints, & qu’en multipliant les ti-vient d’être dit.
rants dans l’épaisseur desdits paliers, de ma-
nière à empêcher tout espéce de poussée, sur-Déﬁnition complétée p. 288 cit. 59
tout vers le vuide de l’escalier. La ﬁgure VI est
Citation 59. Blondel et Patte (1777a, le Plan du grand Palier d’un escalier à deux
p. 288) rampes ; on y voit la disposition circulaire des
Claveaux N, autour des angles, ainsi que des
On termine les croisées, soit en plein-cintre,
Tirants en croix O, cachés sous le carreau,
soit en anse-de-panier, soit en plate-bande
pour empêcher l’écartement des murs. La ﬁdroite ou bombée : mais quelques ﬁgures
gure VII est le Proﬁl de la Plate-bande P, à
qu’elles ayent, leurs voussoirs doivent tou-
l’arrivée des marches, dont les claveaux sont
jours être en nombre impair, & celui du mi-
soutenus de deux l’un par des T renversés,
lieu forme ce qu’on appelle la clef. Dans les
vissés dans une chaîne de fer quarré desticroisées plein cintre ou anse-de panier, les
née à contenir en même tems les murs oppojoints des voussoirs tendent vers le centre ou
sés. Mais le plus souvent par économie, on se
les centres de ces courbes : & dans les croisées
borne à exécuter les planchers de ces grands
à plate-bande, ils tendent au sommet d’un tri-
paliers en charpente, & alors on prend le parti
angle équilatéral dont la largeur des croisées
d’appuyer les voussures des rampes contre les
détermine le côté. On observe dans le dernier
marches desdits paliers.
cas, c’est-à dire dans l’exécution des croisées
à plate bande, de tailler quelquefois les vous-
Voir ﬁg. 10.9
soirs à crosette par le bas pour éviter l’aiguité
des angles ; & même il y en a qui aﬀectent Citation 62. Patte (1769, p. 300)
de dérober l’obliquité des joints de ces vous-
La façon surtout dont les tirans sont placés
soirs en dehors, en pratiquant sur le devant de
par-dessous l’architrave est remarquable ; &
fausses coupes pour les faire paroître comme
c’est, je crois, de toutes les manières d’ass’ils étoient perpendiculaires, ainsi que nous
surer une plate-bande, la plus solide : les
l’avons expliqué précédemment en décrivant
deux Mansard ne les plaçoient jamais aula ﬁgure VI de la Planche LXX [cit. 58]. En-
trement ; en eﬀet, comme les claveaux d’une
ﬁn on soulage communément le poids & la
plate-bande dirigent toujours leurs eﬀorts en
poussée des plate-bandes droites des portes &
contre-bas, plus on peut saisir le mandrin
des croisées par le moyen d’un linteau de fer,
d’axe de la colonne près du chapiteau, mieux
qu’on encastre de toute son épaisseur par des-
on doit réussir, de toute nécessité, à retenir
sous.
eﬃcacement leur poussée

Voir ﬁg. 6.43 p. 132 Voir ﬁg. B.63

Citation 60. Blondel et Patte (1777a, *
p. 290) * *

320

<!-- p. 322 -->

Annexe A. Sources bibliographiques

Charles François Roland Le Vir- Tirant de fer ; est une barre de fer plat, plus
loys (1716-1772) ou moins longue, ayant à chaque extrémité un
oeil, pour recevoir un ancre : son usage est le
Citation 63. Roland Le Virloys (1770a, même que le précédent [Tirant de bois] : tels
p. 451) sont ceux qui retiennent la poussée des plate-
Plate-bande de fer ; est toute barre placée bandes du péristyle du Louvre.
sous les claveaux d’une plate-bande de pierre,
pour en soulager la portée.

Citation 64. Roland Le Virloys (1770b, *
p. 37) * *

A.2 Citations des traités de l’Époque Contemporaine

Nicolas Le Camus de Mézières Citation 68. Simonin (1792, p. 37-38)
(1721-1789) Toute la diﬃculté consiste à donner de la so-
lidité au claveau ABCD dont la forme, nécesCitation 65. Le Camus de Mézières (1786, saire pour soutenir les autres claveaux, ne pap. 116-117) roît propre qu’à causer sa chute et par consé-
En construisant en moilon, vous vous ser- quent celle du demi-berceau.
virez de linteaux en bois : si c’est en pierre,
vos plate-bandes ou cintres doivent se soute- Voir ﬁg. 7.6 page 145
nir par la coupe. Mettez pour les plates-bandes
\*
un linteau de fer encastré dans la partie de la
\* *
feuillure. Cette précaution cependant n’est nécessaire qu’autant qu’on bâtit rapidement, &
qu’on ne laisse pas au mortier le temps de Gaspard Monge (1746 – 1818)
prendre consistance.
Citation 69. Dhombres (1992, p. 340)

\* Une des conditions auxquelles la position
\* * des joints doit satisfaire, c’est qu’ils soient
perpendiculaires entre eux et que les uns et
les autres rencontrent perpendiculairement la
Simonin surface de la voûte. Si l’on s’écartait sensi-
blement de cette loi, non seulement on blesseCitation 66. Simonin (1792, p. 4) rait les convenances générales, sans lesquelles
rien ne peut avoir de la grâce, mais encore On m’objectera, peut-être, que le poids des
on s’exposerait à rendre la voûte moins so-clefs & contre-clefs, feroit arquer le plafond
lide et moins durable : car si l’un des jointspar en bas ? mais ne donne-t’on pas à l’épure
était oblique à la surface de la voûte, des deuxd’une platte bande, une certaine élévation
voussoirs contigus à ce joint, l’un aurait unsous clef, au dessus des naissances, aﬁn que
angle obtus, l’autre un angle aigu, et dans lapar le tassement, le plafond se trouve de ni-
réaction que les deux voussoirs exercent l’unveau ?
sur l’autre, ces deux angles ne seraient pas caCitation 67. Simonin (1792, p. 37) pables de la même résistance : à cause de la
fragilité des matériaux, l’angle aigu serait ex-
L’inclinaison BG, EI, AK, des claveaux,
posé à éclater, ce qui altérerait la forme de la
doit être aussi proportionnellement partagée ;
voûte et compromettrait la durée de l’édiﬁce.
ainsi, DG, doit être la moitié de FI, & FI, les
deux tiers de HK.
Relevé par Sakarovitch (1992, p. 536)

Voir ﬁg. 8.3 page 153 Citation 70. Dhombres (1992, p. 419)

321

<!-- p. 323 -->

Annexe A. Sources bibliographiques

Une des principales conditions auxquelles la pale, c’est que les lignes de division des vousforme des joints des voussoirs doit satisfaire, soirs, qui, comme nous le venons de le voir,
c’est d’être partout perpendiculaires à la sur- sont de deux espèces et qui doivent se renface de la voûte que ces voussoirs composent : contrer toutes perpendiculairement, doivent
car, si les deux angles qu’un même joint fait aussi porter le caractère de la surface à laavec la surface de la voûte étaient sensible- quelle elles appartiennent. Or, il n’existe
ment inégaux, celui de ces angles qui excé- pas de ligne sur la surface courbe qui
derait l’angle droit serait capable d’une plus puisse remplir en même temps toutes
grande résistance que l’autre ; et dans l’ac- ces conditions, que les deux suites de
tion que deux voussoirs consécutifs exercent lignes de courbure, et elles les remplissent
l’un sur l’autre, l’angle plus petit que l’angle complètement. Ainsi la division d’une voûte
droit serait exposé à éclater, ce qui, au moins, en voussoirs doit donc toujours être faite par
déformerait la voûte et pourrait même al- des lignes de courbure de la surface de la voûte
térer sa solidité et diminuer la durée et les joints doivent être des portions de surde l’édiﬁce. Lors donc que la surface d’un faces développables formées par la suite des
joint doit être courbe, il convient de l’engen- normales à la surface qui, considérées consédrer par une droite qui soit partout perpendi- cutivement, sont deux à deux dans un même
culaire à la surface de la voûte ; et, si l’on veut plan ; en sorte que, pour chaque voussoir, les
de plus que la surface du joint soit dévelop- surfaces des quatre joints et celle de la voûte
pable, il faut que toutes les normales à la sur- soient toutes rectangulaires.
face de la voûte et qui composent, pour ainsi Avant la découverte des considérations
dire, le joint, soient consécutivement deux à géométriques sur lesquelles tout ce que nous
deux dans un même plan. Or, nous venons de venons de dire est fondé, les artistes avaient
voir que cette condition ne peut être remplie, un sentiment confus des lois auxquelles
à moins que toutes les normales ne passent elles conduisent, et, dans tous les cas, ils
par une même ligne de courbure de la surface avaient coutume de s’y conformer. Ainsi, par
de la voûte ; donc, si les surfaces des joints exemple, lorsque la surface de la voûte était de
des voussoirs d’une voûte doivent être déve- révolution, soit qu’elle fût en sphéroïde, soit
loppables, il faut nécessairement que ces sur- qu’elle fût en berceau tournant, ils divisaient
faces rencontrent celle de la voûte dans ses ses voussoirs par des méridiens et par des palignes de courbure. rallèles, c’est-à-dire par les lignes de courbure
D’ailleurs, avec quelque précision que les de la surface de la voûte.
voussoirs d’une voûte soient exécutés, leur di- Les joints qui correspondaient aux mérivision est toujours apparente sur la surface ; diens étaient des plans menés par l’axe de
elle y trace des lignes très sensibles, et ces révolution ; ceux qui correspondaient aux palignes doivent être soumises à des lois gé- rallèles étaient des surfaces coniques de rénérales et satisfaire à des convenances par- volution autour du même axe :, et ces deux
ticulières, selon la nature de la surface de espèces de joints étaient rectangulaires entre
la voûte. Parmi les lois générales, les eux et perpendiculaires à la surface de la
unes sont relatives à la stabilité, les voûte. Mais, lorsque les surfaces des voûtes
autres à la durée de l’édiﬁce ; de ce n’avaient pas une génération aussi simple et
nombre est la règle qui prescrit que les joints quand leurs lignes de courbure ne se préd’un même voussoir soient rectangu- sentaient pas d’une manière aussi marquée,
laires entre eux, par la même raison qu’ils comme dans les voûtes en sphéroïdes allondoivent être eux-mêmes perpendiculaires à la gés et dans un grand nombre d’autres, les arsurface de la voûte. Aussi les lignes de di- tistes ne pouvaient plus satisfaire à toutes les
vision des voussoirs doivent être telles que convenances et ils sacriﬁaient, dans chaque
celles qui divisent la voûte en assises soient cas particulier, celles qui leur présentaient les
toutes perpendiculaires à celles qui divisent diﬃcultés les plus grandes.
une même assise en voussoirs. Quant-aux
Relevé par Sakarovitch (1992, p. 536)convenances particulières, il y en a de plusieurs sortes et notre objet n’est pas ici d’en *
faire l’énumération ; mais il y en a une princi- * *

322

<!-- p. 324 -->

Annexe A. Sources bibliographiques

Charles-François Viel (1745-1819) ont pratiqué quelquefois, dans les joints des
voussoirs et des claveaux, des espèces de
Citation 71. Viel (1805, p. 35) tenons et des entailles. On en trouve un
Une foule d’autres bâtimens de la capi- exemple au théâtre de Marcellus à Rome, dans
tale, quoique composés avec des appareils ré- les joints des plate-bandes qui soutiennent les
guliers, perdent cependant beaucoup de force retombées des voûtes du second rang des pordans la construction des platebandes ; ce sont tiques qui règne autour. [...] On en voit de
les coupes verticales et celles inclinées dans semblables dans les joints des voussoirs de
les claveaux, les uns avec des enclavements plusieurs arcs antiques, et sur-tout dans ceux
intérieurs, les autres avec des redans exté- du Colisée. Au lieu de bossage réservé en
rieurs. Ces deux espèces d’appareils exposent taillant la pierre, ils ont quelquefois incrusté
également à des ruptures dangereuses, comme des cubes de pierre de trois à quatre pouces.
on le verra bientôt. Je traiterai dans la suite
des appareils par évidemens, troisième espèce Voir ﬁg. B.10 page 347
dont le Panthéon-Français est le plus grand
exemple. Citation 74. Rondelet (1804, p. 92)
Je ne dissimulerai point que le péristyle Le principe général de l’art de l’appareil et
du temple de Saint-Sulpice est appareillé dans de la coupe des pierres exige que dans les
ses plates-bandes par des coupes verticales ; murs, comme dans les voûtes, les joints des
c’est le seul reproche que l’on puisse faire dans pierres qui se touchent fassent des angles
l’exécution de cette admirable fabrique. Mais égaux ou des angles droits avec les surfaces
toutes les parties de la construction sont si apparentes qu’elles forment ; et comme dans
abondamment fournies de masses, que la so- les voûtes plates il n’y a que des joints perpenlidité ne peut en être compromise ; la courbe diculaires à leur surface qui puissent former
insensible de deux pouces de ﬂèche qui existe avec elle des angles égaux, il en résulte que
dans l’axe des platebandes de l’ordre dorique, toutes les voûtes plates horizontales devraient
répare la foiblesse des coupes verticales. avoir leurs joints d’à-plomb. Mais cette dispo-
Les deux espèces d’appareils que je pros- sition ne pouvant servir à soutenir des pierres
cris dans les platebandes prennent faveur. Tel qui ne doivent avoir d’autre appui que leurs
monument public qui vient d’être restauré, a joints, on a été obligé de les incliner en les tises claveaux par redans à l’extérieur ; et quoi- rant d’un même point C, aﬁn de donner aux
qu’ils soient en pierre dure, déjà tous les som- pierres la forme de coin pour qu’elles puissent
miers sont rompus. Dans tel autre édiﬁce du se soutenir, ﬁgure 7, planche XXVII. Comme
premier rang, l’on a fait des platebandes avec cet appareil a le désavantage de former des
des coupes verticales et des enclavemens qui angles inégaux avec la surface inférieure, il en
les exposent d’autant plus à des ruptures. résulte que ces pierres, auxquelles on donne le
nom de « claveaux », n’ont pas une résistance
égale ; que leurs eﬀorts ne se correspondent
Jean Rondelet (1743-1829) pas, et quelles poussent toutes à faux les unes
des autres, comme on le voit par les perpenCitation 72. Rondelet (1804, p. 101)
diculaires tirées de l’extrémité des joints 6, 7
On remarque, dans les constructions des et 8 ; de sorte qu’une pareille voûte ne pourArabes, qu’ils aﬀectaient de faire les joints des rait se soutenir, quelque fut l’épaisseur des
voûtes en pierres de taille par ondulation ou pied-droits, si le frottement causé par la rudentelés, ce qui prouve que les constructeurs, desses et l’inégalité des surfaces ne les empêde tous les tems et de tous les pays, ont connu chait d’agir librement, et si le mortier et les
l’avantage d’augmenter, par tous les moyens fers qu’on emploie à leur construction ne les
possibles, l’union des pierres qui ne peuvent entretenaient ensemble avec une force supése soutenir par leurs joints, en les empêchant rieure à ces eﬀorts. On pourra s’assurer de
de glisser. cet eﬀet, comme moi, en faisant faire un mo-
dèle en marbre poli.
Citation 73. Rondelet (1804, p. 100)

Les anciens, pour empêcher les pierres d’agir, Citation 75. Rondelet (1804, p. 95)

323

<!-- p. 325 -->

Annexe A. Sources bibliographiques

Tous ces fers forment une espèce d’arma- sont entaillés et scellés avec soin, ils sont préture qui contient ces plate-bandes de manière férables aux balles de plomb, parce qu’ils ont
à ne pouvoir agir d’aucune façon, à cause plus de fermeté.
du tirant intermédiaire qui empêche la plate-
Citation 78. Rondelet (1834, p. 118)
bande supérieure de s’écarter ; car il faut observer qu’un tirant placé sur l’extrados d’une En général, la mesure de l’angle C, formé au
plate-bande simple, ne suﬃt pas toujours pour milieu, par la rencontre des lignes tirées des
l’empêcher d’agir, comme on le voit par la deux sommiers, peut varier de 60 à 40 degrés
ﬁg. 11, planche XXVII, sur-tout lorsqu’elle a dans la pratique ordinaire.
peu d’épaisseur : en eﬀet, le moindre écrase-
\*ment aux arêtes supérieures de la clef et aux
\* *arêtes inférieures des claveaux qui joignent
les pied-droit, peut occasionner la désunion
et même la chûte de cette espèce de voûte, Jean-Paul Douliot (1788-1834)
sans que les sommiers ou les parties supérieures des pied-droits s’écartent, à cause du Jean-Paul Douliot est un compagnon paspeu de diﬀérence qui se trouve dans les plate- sant tailleur de pierre, devenu professeur d’arbandes qui n’ont pas une grande épaisseur, chitecture à l’École de dessin de Paris (Maentre l’oblique AK et l’horizontale AC. On thonière, 2016).
doit convenir aussi que la moindre exten- Citation 79. Douliot (1825, p. 81)
sion de la chaîne ou tirant, peut favoriser
S’il arrivait que l’on se trouvât dans quelquecet eﬀet, sur-tout lorsqu’elle n’est pas d’une
circonstance où il ne fût pas possible de don-seul pièce ; c’est pourquoi les voûtes plates ne
ner assez de longueur de coupe vers la clef,conviennent pas pour les pièces d’une certaine
on pourrait y suppléer de plusieurs manières,étendue. On ne peut les employer avec succès
plus ou moins eﬃcaces. Je vais en présenterque pour des architraves ou des plate-bandes
deux exemples des plus simples, où il ne seraauxquelles on peut donner une épaisseur égale
employé d’autres secours que ceux que peutau quart, ou au moins au cinquième de leur
donner la forme des claveaux ; ensuite j’ex-portée : elles peuvent encore être employées
pliquerai quelques armatures en fer, que l’onpour former des plafonds de peu d’étendue,
peut employer dans des cas plus diﬃciles.renfermés entre des architraves.
Citation 80. Douliot (1825, p. 80)
Citation 76. Rondelet (1804, p. 101)
Je donne le nom de claveaux en état de
Dans les pays où la pierre a beaucoup de charge, tous ceux qui ont la forme GBCbconsistance, on fait les joints des plate-bandes DEFg [ﬁg. 6.13] ; ce nom me paraît mieux exà crossettes, comme on le voit indiqué dans la primer l’eﬀet qu’ils produisent, que les mots
ﬁgure 8 ; ce moyen, équivalent à une coupe, tas de charge qu’on emploie ordinairement.
a, de plus, l’avantage d’éviter la forme de Comme c’est à la partie horizontale CD que
coin : c’est celui qui convient le mieux pour ces claveaux doivent leur propriété et leur
les voûtes intérieures qui ne peuvent pas avoir nom, nous appelerons état de charge cette
beaucoup d’épaisseur. Il ne faut pas cepen- partie horizontale elle-même.
dant faire les crossettes trop grandes ; il n’est
pas nécessaire de leur donner plus de 2 ou Citation 81. Douliot (1825, p. 81)
3 pouces, et il faut que la partie au-dessous En général, quelle que soit la forme d’apsoit au moins deux fois plus grande que la pareil que l’on adopte pour une plate-bande,
saillie. les coupes de la clef doivent être uniformes.
En eﬀet, dans la pratique, on pose successiCitation 77. Rondelet (1804, p. 101) vement les claveaux à droite et à gauche, sur
Plusieurs constructeurs modernes ont fait les sommiers, de sorte que la clef est toujours
usage de balles de plomb d’environ deux posée la dernière. Or, quelque soin qu’on ait
pouces de gros, pour mettre dans les joints apporté au tracer, à la taille et à la pose des
des plate-bandes. J’ai vu même y employer claveaux, jamais le vide qui reste pour la clef
des cailloux ronds, et je pense que lorsqu’ils n’est parfaitement indiqué par l’épure, ce qui

324

<!-- p. 326 -->

Annexe A. Sources bibliographiques

fait qu’on est obligé d’attendre que tous les *
claveaux de la plate-bande soient posés, pour * *
prendre, sur place, la mesure de la clef ; et
comme il faut nécessairement que cette clef
Eugène Viollet-Le-Duc (1814-entre juste à sa place, non pas tout-à-fait
d’elle même, mais en la forçant avec précau- 1879)
tion, pour qu’elle presse et maintienne solide-
Citation 84. Viollet-Le-Duc (1858)ment les autres claveaux, cette opération serait très diﬃcile, si les coupes n’étaient pas Nous devons ajouter que les coupes des clauniformes. veaux des arcs sont toujours normales à la
courbe. Dans les arcs formés de deux por-
tions de cercle, vulgairement désignés sous le *
nom d’ogives, toutes les coupes des claveaux * *
tendent aux centres de chacun des deux arcs,
de sorte que dans les arcs dits en lancettes les
Joseph Adhémar lits des claveaux présentent des angles très-
peu ouverts avec l’horizon. C’est ce qui fait
Citation 82. Adhémar (1845, p. 15) que ces arcs oﬀrent une si grande résistance
[A propos d’une voûte plate] Cette espèce à la pression et poussent si peu. L’intersection
de voûte n’aura pas de poussée, si l’on fait des deux arcs est toujours divisée par un joint
tout autour de chaque rangée de claveaux une vertical ; il n’y a pas, à proprement parler, de
crossette telle que mnyr ; on pourra, dans clef ; en eﬀet, il ne serait pas logique de place cas, considérer la voûte entière comme cer une clef à l’intersection de deux arcs qui
composée de châssis rectangulaires et concen- viennent buter l’un contre l’autre à leur somtriques s’emboîtant les uns dans les autres, et met, et l’ogive n’est pas autre chose.
portant sur les parties horizontales des cros-
Citation 85. Viollet-Le-Duc (1858)
settes. Cette précaution ne suﬃt pas ; il reste
encore à tailler les claveaux d’une même ran- L’étude de l’appareil des monuments du
gée, de manière qu’ils se soutiennent mutuel- Moyen Âge ne saurait donc être recommanlement. Pour cela on fera sur la tête de chaque dée ; elle est indispensable lorsqu’on veut les
claveau une crossette ab (ﬁg. 30), au moyen restaurer sans compromettre leur solidité, elle
de laquelle il s’appuiera sur le claveau qui pré- est utile toujours, car jamais cette science
cède en partant du claveau d’angle. pratique n’a produit des résultats plus surpre-
nants avec des moyens plus simples, avec une
connaissance plus parfaite des matériaux, de *
leur résistance et de leurs qualités. Dans les * *
édiﬁces du xie au xvie siècle, les linteaux ne
sont généralement employés que pour couvrir
Claudel et Laroque de petites ouvertures, et sont alors d’un seul
morceau. Dans les édiﬁces civils particulièreCitation 83. Claudel et Laroque (1850, ment, où les fenêtres et les portes sont presque
p. 241-242) toujours carrées, les linteaux sont hauts, quel-
Ces linteaux [armatures placés sous la plate- quefois taillés en triangle (19) pour mieux rébande] doivent être peints à l’huile ou gou- sister à la pression, ou soulagés près de leur
dronnés, pour les préserver de l’oxydation, et portée par des consoles tenant aux pieds-droits
on remplit de plâtre coloré de la même cou- (20). Quand ces linteaux doivent avoir une
leur que la pierre (en y mêlant un peu d’ocre grande longueur, comme dans les cheminées
jaune), les entailles faites pour les recevoir, dont les manteaux souvent jusqu’à quatre ou
lesquelles doivent avoir une profondeur suﬃ- cinq mètres de portée, les linteaux sont appasante pour qu’il y ait au moins un centimètre reillés en plates-bandes (21) à joints simples
de plâtre sur le fer ; il est bon que ces linteaux ou à crossettes (22), ou à tenons (23).
portent quelques aspérités faites à chaud au Les constructeurs connaissaient donc
moyen du ciseau pour retenir le plâtre. alors la plate-bande appareillée, et s’ils ne

325

<!-- p. 327 -->

Annexe A. Sources bibliographiques

l’employaient que dans des cas exceptionnels Citation 88. Viollet-Le-Duc (1859b)
et lorsqu’ils ne pouvaient faire autrement, Les constructeurs du moyen âge n’ayant emc’est qu’ils avaient reconnu les inconvénients ployé la plate-bande appareillée qu’exceptionde ce genre d’appareil. D’ailleurs il existe du nellement, nous nous occuperons d’abord des
côté du Rhin, là où les grès rouges des Vosges claveaux d’arcs. En règle générale, la coupe
donnent des matériaux très résistants et te- d’un claveau est toujours normale à la courbe
naces, un grand nombre de plates-bandes ap- de l’arc ; en d’autres termes, la coupe du clapareillées dans des édiﬁces des xiie, xiiie et veau doit être faite suivant la direction du
xive siècles. Dans la portion du château de rayon de l’arc (voy. Construction). Les claCoucy, qui date du XVe siècle, on voit encore veaux, dans l’architecture du moyen âge, étant
d’immenses fenêtres carrées dont les linteaux, toujours intradossés et extradossés, sauf de
qui n’ont pas moins de quatre mètres de por- très-rares exceptions, il en résulte que les clatée, sont appareillés en claveaux, sans aucun veaux d’un même arc sont tous de même
ferrement pour les empêcher de glisser. Mais forme et de même dimension, ainsi que le déce sont là des exceptions ; les portions d’arcs montre la ﬁg. 1. A sont les sommiers, B la clef
de cercle sont toujours préférées par les ap- et C les claveaux.
pareilleurs anciens (24), du moment que les
portées sont trop grandes pour permettre l’em- Citation 89. Viollet-Le-Duc (1859b)
ploi de linteaux d’un seul morceau. Les claveaux de plates-bandes sont rares pen-
dant les périodes romane et gothique ; cepenVoir ﬁg. 9.7 p. 178
dant force fut, dans quelques contrées où la
Citation 86. Viollet-Le-Duc (1864) pierre à bâtir n’était extraite qu’en petites
dimensions, de faire des linteaux de porte Les architectes du Moyen Âge, sauf de très-
composés de claveaux. Dans le Beauvoisis onrares exceptions mentionnées dans l’article
rencontre assez fréquemment des linteaux deConstruction et Fenêtre, ont toujours re-
porte appareillés appartenant au xiie siècle ;poussé le linteau composé de claveaux. S’ils
mais les claveaux de plate-bande ne présententcraignaient une rupture, ils bandaient au-
jamais, à cette époque, des coupes tendantdessus un arc de décharge. Nous sommes
à un centre, comme dans l’architecture ro-moins scrupuleux, et nous posons dans nos
maine ; ils sont maintenus dans leur plan auédiﬁces publics ou privés autant de plates-
moyen de coupes enchevêtrées, qui rendentbandes qu’il y a de baies ou de travées fer-
tout glissement impossible. On voit un de cesmées horizontalement ; seulement nous avons
linteaux de porte le long du ﬂanc nord dele soin de soutenir cet appareil vicieux au
l’église Saint-Étienne de Beauvais (7).moyen de fortes barres de fer.
La diﬃculté résultant de la taille et de
Citation 87. Viollet-Le-Duc (1860b) la pose de plates-bandes ainsi appareillées ﬁt
On voit encore, dans les constructions an- qu’au xiiie siècle, alors que l’on extrayait
ciennes du Palais-de-Justice de Paris, une des carrières des pierres d’un fort volume,
salle voûtée sur un quinconce de colonnes on abandonna ces moyens de construction
(13), avec quatre larges cheminées aux angles. compliqués, à moins d’une nécessité absolue,
Cette salle, qui donne sur le quai du nord, comme, par exemple, pour les manteaux de
à côté de la tour de l’Horloge, est connue cheminée ; et, dans ce cas particulier, les clasous le nom de cuisines de saint Louis. Ce- veaux des manteaux sont appareillés à crospendant cette construction appartient à la ﬁn settes, ou suivant des coupes tendant à un
du xiiie siècle ou au commencement du xive, centre (voy. Appareil, Cheminée).
et est contemporaine des ouvrages élevés sous
Philippe le Bel. Les manteaux des quatre che- Voir ﬁg. B.23 p. 354
minées forment, en projection horizontale, un Citation 90. Viollet-Le-Duc (1860a)
angle obtus, et leur clef est contre-buttée par
une façon d’étrésillon en pierre, ainsi que l’in- La grand’salle du château de Coucy, dite
dique la ﬁg. 14. salle des Preux, était une œuvre parfaite (voy.
Salle) ; nous n’en montrerons ici que cerVoir ﬁg. B.41 p. 361 taines parties tenant plus particulièrement

326

<!-- p. 328 -->

Annexe A. Sources bibliographiques

à l’objet de cet article. [...] Les baies laté- transversales d’un contre-fort à l’autre sont
rales étaient surmontées de lucarnes péné- appareillées en coupes. Si nous faisons une
trant dans le comble. Voici (138) la coupe de section longitudinale sur ce bâtiment, chaque
cette salle prise sur une des fenêtres latérales travée nous donne la ﬁg. 131[Note de pied de
avec la lucarne ouverte au-dessus, et (139) la page : M. Bœswilwald, qui a relevé le château
vue perspective intérieure de cette fenêtre, qui de Hoh-Kœnigsbourg avec le plus grand soin,
n’a pas moins de 4m00 d’ébrasement.La plate- a bien voulu mettre ses dessins à notre dispobande qui la couvre est appareillée de dix cla- sition.].
veaux, posés avec grand soin, lesquels, serrés
Voir ﬁg. B.57 p. 367par les courtines qui ont près de 4m00 d’épaisseur. Citation 92. Viollet-Le-Duc (1863)

On observera encore que, dans cette épure
Voir ﬁg. B.56 p. 366 [remplage de la fenêtre du mur occidental du
transept de la cathédrale d’Amiens], l’appaCitation 91. Viollet-Le-Duc (1860a)
reil est inﬁniment plus simple et rationnel que
Le bâtiment principal du château de Hoh- dans l’épure précédente [remplage des fenêtres
Kœnigsbourg, adossé au rocher (130), ne se hautes de la nef de la cathédrale d’Amiens].
compose que de contre-forts intérieurs avec Les joints tendent sans diﬃcultés aux centres
mur extérieur fort mince du côté des cours. des tiers-points et en même temps aux centres
Il contient quatre étages ; le rez-de-chaussée, des lobes. Ces joints étaient donc toujours
qui servait de cuisines, est voûté en berceau normaux aux courbes, évitaient les aiguïtés et
surbaissé reposant sur des arcs très-plats en par conséquent les causes de brisures.
moellon, bandés d’une pile à l’autre. Le pre- [...]
mier étage est plafonné au moyen de grandes
L’appareil [des remplages de la Sainteplates-bandes appareillées soulagées par de
Chapelle à Paris] est simple, logique, solide,
puissants corbeaux ; entre les plates-bandes,
car toutes les coupes sont normales, comme
les parallélogrammes restant vides sont ban-
l’indique le tracé T.
dés en moellon. Le second étage est couvert par un plancher en bois dont les poutres *
maîtresses portent sur des corbeaux engagés * *
dans les piles. Le troisième étage est voûté en
berceau plein-cintre reposant sur des platesbandes et sur de larges encorbellements dis- Léonce Reynaud (1803-1880)
posés comme ceux du premier. Cette voûte
Citation 93. Reynaud (1867, p. 529-530)supérieure portait une plate-forme ou terrasse couverte en dalles. La coupe perspective Nous n’entrerons pas dans un examen dé-
(ﬁg. 130) donne l’ensemble de cette singulière taillé de ce mode de construction. Ainsi que
construction. Il faut dire que les matériaux nous l’avons dit, en parlant des entablements
du pays (grès rouge) se prêtent à ces har- en pierre, nous ne saurions l’approuver :
diesses ; on ne pourrait, avec nos matériaux d’abord parce qu’il est faux, en ce qu’il tend à
calcaires des bassins de la Seine, de l’Oise faire supposer au spectateur beaucoup de simou de l’Aisne, se permettre l’emploi de lin- plicité de composition où il y a, au contraire,
teaux aussi minces et d’une aussi grande por- une grande complication ; puis, parce qu’il y a
tée [Note de pied de page : Au XVIe siècle, quelque chose de souverainement irrationnel
un accident obligea les propriétaires du châ- à faire reposer entièrement la stabilité d’une
teau de Hoh-Kœnigsbourg à bander des arcs construction sur des barres de fer logées dans
sous le plafond du premier étage.]. Mais dans l’épaisseur des maçonneries, où elles peuvent
l’architecture civile et militaire, plus encore s’oxyder en quelques points, sans qu’on en reque dans l’architecture religieuse, la nature çoive d’autre avis que la chute de l’édiﬁce.
des matériaux eut une inﬂuence très-marquée Il y a lieu de s’étonner qu’un système aussi
dans l’emploi des moyens de construction : cet vicieux ait été aussi fréquemment appliqué,
exemple en est une preuve. Les plates-bandes et qu’aucune catastrophe ne l’ait encore fait
longitudinales entre les contre-forts et celles abandonner ; mais il est hors de doute que les

327

<!-- p. 329 -->

Annexe A. Sources bibliographiques

entablements à l’exécution desquels il a pré- Citation 96. Monduit (1889, p. 72)
sidé n’auront pas une longue durée. Si nous avons conservé la crossette dans nos
Il est assurément très-légitime d’employer épures, et dans les modèles, qui font partie
le fer comme moyen accessoire de consolida- de notre grand ouvrage de stéréotomie, quoition dans les édiﬁces exécutés en pierre ; mais qu’elle ne soit plus en usage à Paris, c’est
il ne l’est pas de faire dépendre de lui seul la parce que nous avons pensé et que nous penstabilité d’une construction qui doit présen- sons encore que la crossette est une bonne
ter, et avoir par elle-même, un caractère mo- chose, qui ne peut qu’ajouter à la solidité des
numental. Dans le premier cas, on obéit à la édiﬁces. – Il n’est pas sans exemple que des
voix de la prudence, on ajoute quelque chose clefs soient descendues, faute de cette crosà une solidité qui, à la rigueur, pourrait pa- sette, qui n’a été supprimée que dans un but
raître suﬃsante, on se prémunit contre des d’économie mal entendue de pierre, de taille,
éventualités dont les conséquences seraient, et de pose.
funestes ; dans le second, on nuit à l’eﬀet de
[...]
l’édiﬁce, si le fer, mis en évidence, prouve que
les supports sont jugés trop faibles pour ré- L’élève ne devra donc pas s’arrêter aux
sister aux actions en vue desquelles ils ont critiques plus ou moins fondées des profesdû être établis, ou la durée de la construction seurs en stéréotomie de la ﬁn de notre siècle,
n’est pas convenablement garantie, si l’on dis- qui, pour la plupart du moins, paraissent ignosimule l’artiﬁce employé. On peut sans doute rer les œuvres si remarquables de nos premiers
concevoir un système d’architecture reposant initiateurs en architecture.
sur l’emploi simultané de matériaux de na- [...]
tures fort diverses ; mais il ne sera satisfai-
S’il partage notre manière de voir, ilsant, que si toutes les parties qui le composent
s’épargnera la tristesse de recourir au moyense rattachent bien les unes aux autres, si le
trop généralement employé, et qui présenterôle de chacune d’elles est nettement marqué,
de si grands inconvénients, c’est-à-dire cessi elles ont toutes leur raison d’être, en un
horribles linteaux en fer que l’on entaillemot, s’il y a harmonie, et vérité dans la com-
dans le dessous ou l’intrados des arcs et desposition.
plates-bandes, et dont l’emploi est la meilleure
preuve que ceux qui s’en servent n’ont euxJules-Étienne Quicherat (1814- même pas grande conﬁance dans la solidité
\1882) des claveaux et voussoirs sans crossettes.

Citation 94. Quicherat (1886, p. 448) Citation 97. Monduit (1889, p. 72)
Les plates-bandes appareillées de claveaux en Il y a plusieurs manières de déterminer ce
guise de linteaux devinrent d’un emploi fré- centre ; mais celle dont nous nous sommes
quent pendant le xie et xiie siècle. C’est dans servis, et que nous conseillons après Rondecelles de la dernière époque que furent mises let, nous semble la meilleure de toutes, tant
à la mode ces coupes compliquées avec des en- qu’elle ne donne pas trop d’inclinaison aux
coches angulaires ou rondes qu’on appelle au- coupes ; nous indiquerons plus loin, un autre
jourd’hui des crossettes. manière de tracer les coupes [voir cit. 98].

\* Citation 98. Monduit (1889, p. 82)
\* *
Pour dresser cette épure, et pour tracer les
pierres, on emploiera les mêmes procédés que
Louis Monduit pour la planche 16. Cependant, nous avons in-
diqué un autre moyen de tracer les coupes en
Citation 95. Monduit (1889, p. 72) élévation, car il arrive quelquefois dans la pra-
Pour éviter les aiguités, qu’il faut surtout re- tique, que le premier procédé [triangle équiladouter dans l’emploi de la pierre, on fera une téral - voir cit. 97] donne trop de coupe ; pour
crossette verticale ou à plomb, dont la hauteur les redresser, au lieu de décrire des arcs de
est indéterminée. cercles avec l’ouverture de la baie pour rayon,

328

<!-- p. 330 -->

Annexe A. Sources bibliographiques

on porte trois fois le rayon sur l’axe, on ob- lui donnait la hauteur de la frise et de l’artient le point 3 que l’on prend pour centre, chitrave, comme on le voit sur la façade du
pour mener toutes les coupes par les points Panthéon de Rome (Fig. 11). Sur les platesde division déterminés comme dans les épures bandes venaient reposer les caissons en maprécédentes. çonnerie, en charpente, en métal parfois.

Citation 101. Benouville (1888)Citation 99. Monduit (1889)
[...] la Renaissance, en disparaissant, em- L’appareilleur, travaillant sur le terrain beau-
porte avec elle les fenêtres à imposte et me-coup plus vaste [que celui de l’élève] et ayant
neaux en pierre, et, à partir de Henri IIIaﬀaire à des masses qu’on ne remue que très
[vers 1574], presque universellement les me-diﬃcilement, ne peut pas toujours employer
nuiseries de fenêtres ne sont plus qu’en boisles mêmes procédés. Si l’épure de petite di-
ou en fer [...]mension, qui est la représentation exacte du
modèle qu’il se propose de couper, suﬃt na- Citation 102. Rivoalen (1888)
turellement à l’élève, il n’en est pas de même Partagés, au commencement du xvie siècle,
pour lui. Il lui faut, non seulement un plan gé- entre le savoir-faire, les formules traditionnéral de la construction qu’il s’agit d’édiﬁer, nelles du Moyen Âge et la nécessité d’adopmais un calepin, une épure grandeur d’exé- tion les modes artistiques importées d’Italie,
cution, enﬁn des panneaux, qui lui servent, les artistes français, espagnols ou allemands
d’une part, à faire sur le chantier le choix s’ingénient à tirer parti d’ordonnances et de
de ses morceaux de pierre, et, de l’autre, au détails décoratifs néo-latins introduits d’Italie
moins le plus souvent, à les tracer. Le pan- en France, en Espagne et dans les Flandres
neau lui permet non seulement de faire vite par l’engouement des princes, des seigneurs
et facilement le choix des morceaux dont il a ou des prélats. [...] En ce qui concerne parbesoin, mais encore de faire souvent des éco- ticulièrement les portes d’édiﬁces privés, par
nomies de pierres ; mérite justement apprécié exemple, l’architecte abandonne l’arc de déchez un appareilleur.précédentes. charge devenu ogival ou l’accolade gothique
pour le linteau droit, quelquefois légèrement
Citation signalée par Robert March.
arrondi près de ses portées [...]
\* Citation 103. Planat (1888b, p. 486-487)
\* *
Les portes de Balbeck nous montrent de ces
linteaux de porte à trois claveaux (1er vol.,
Encyclopédie de la construction pp422). A l’émissaire d’Albano, on trouvera
de Paul Planat la disposition classique des voussoirs de plate-
bandes, mais déjà, au théâtre de Marcellus,
Citation 100. Planat (1888b, p. 484) on remarquera que les Romains s’étaient cru
Pour constituer les plates-bandes qui doivent obligés à l’emploi de crochets ou crossettes,
relier entre elles les colonnes et recevoir les destinés à empêcher le glissement vertical, la
plafonds ou les pièces de toiture, les Grecs descente des voussoirs. Dans une porte du
n’avaient guère fait usage que de pierres mo- tombeau de Cécilia Metella (Fig. 16), comme
nolithes, carrément posées sur leurs supports. dans une autre porte de Dioclétien à Spalatro
La charge était parfois considérable, notam- (Fig. 17), on remarquera également que, sans
ment pour les architraves qui soutiennent les doute dans le même but, les joints sont brisés
frontons ; il allait donc recourir à des pierres au lieu de rester plans ; les voussoirs ont ainsi
de fortes dimensions, tant en longueur qu’en paru mieux accrochés les uns aux autres.
hauteur ; et c’est la possibilité de trouver des La raison en est facile à concevoir : les
échantillons de force et d’homogénéité suf- constructeurs romains savaient parfaitement
ﬁsantes qui a principalement limité la lar- la diﬀérence qui existe entre le travail qui se
geur des entre-colonnements. Les Romains fait à l’intérieur d’une voûte ou celui d’une
ont d’abord suivi le même usage : quelque- plate-bande : dans la voûte, il résulte de la
fois, le linteau en pierre n’a que la hauteur de forme cintrée de l’appareil que les voussoirs
l’architrave ; mais, sous les fortes charges, on dévient de plus en plus de la verticale, ceux

329

<!-- p. 331 -->

Annexe A. Sources bibliographiques

du dessus s’appuient de plus en plus complè- La partie théorique comprend, de plus, [...]
tement sur ceux du dessous, la clef seule est comme notions de l’équilibre, celles qui se
réellement suspendue ; à droite et à gauche, présentent le plus naturellement à l’esprit,
en allant du sommet vers les reins et la nais- comme par exemple, de faire en sorte que les
sance, chaque voussoir est mieux épaulé à joints des blocs ou voussoirs soient normaux
mesure qu’on descend. Dans la plate-bande, aux voûtes.
tous les voussoirs restent suspendus et ne [...]
s’épaulent qu’artiﬁciellement par une coupe
oblique des joints ; ils sont, beaucoup plus que Toutes les autres faces doivent être, en
dans la voûte, exposés à descendre si les joints règle générale, normales à la surface d’intrane sont pas convenablement serrés, ou si les dos.
massifs des extrémités, qui devraient former
culées, sont susceptibles de céder légèrement à Citation 105. Bazin (1888, p. 40)
la poussée, qui est beaucoup plus considérable Quant à l’équilibre de l’appareil, on comprend
que dans la voûte cintrée. immédiatement qu’un voussoir, étant sollicité
Les crossettes, les onglets, les rainures à par son poids, tend a tomber dans l’intérieur
baguettes, etc., et autres combinaisons aux- de la voûte ; les joints ne doivent donc pas
quelles se sont parfois évertués les Romains, être de proﬁl, auquel cas le voussoir tombesemblent, à première vue, propres, en eﬀet, rait sûrement, ni horizontaux, car les mouveà empêcher cette descente des claveaux. Sont- ments ou tassements de la maçonnerie que la
elles véritablement eﬃcaces ? voûte soutient tendraient à repousser le vous-
soir dans le vide de la voûte ; il faut une posi- Les bons constructeurs de la période mo-
tion intermédiaire aux joints ; et, de plus, ilsderne n’hésitent pas à se prononcer pour la
ne doivent pas être parallèles, de façon quenégative. Et en eﬀet de deux choses l’une. Ou
le voussoir vienne coincer entre les joints desbien l’appareil n’est pas suﬃsamment coincé,
deux voussoirs qui l’avoisinent ; la directionle claveau qui a son joint lâche, tend à des-
la plus naturelle est la normale à la courbecendre (Fig. 18) et vient reposer sur la cros-
d’intrados, direction qui a la même déﬁnitionsette ; la plate-bande ne serre plus. Si la cros-
pour tous les appareils. Il suﬃt que le coin-sette résiste, elle s’oppose à l’eﬀet naturel du
cement se produise sur deux faces du vous-décintrement et empêche les claveaux de se
soir ; aussi les coupes ou séparations de ligneserrer et de faire coins ; ces claveaux restent
du même type des voussoirs pourront ne passuspendus à leurs crossettes. — Ou bien, au
être normales à l’intrados, si les joints sontcontraire, le claveau, trop serré, ne descen-
normaux, et inversement ; ou bien ils pour-dant pas à fond (Fig. 19), la crossette ne porte
ront être tous normaux, alors qu’un seul deplus sur les contre-clefs et reçoit alors toute la
ces types produira le coincement. [Bazin dis-charge de la maçonnerie supérieure.
tingue « Les joints sont les surfaces séparant
La véritable solution est d’avoir des joints
des voussoirs de construction diﬀérente, et les
correctement taillés et qui entrent en contact
coupes, les surfaces séparant des voussoirs du
complet sur toute la surface ; de donner
même ordre. »]
une hauteur aux voussoirs bien proportionnée à la charge, et, enﬁn, d’assurer la sta- Dans la voûte en berceau, les joints et les
bilité des massifs qui forment culées, par une coupes sont normaux à l’intrados, mais les
charge suﬃsante. Il faut dire cependant que joints seuls s’opposent au mouvement.
la disposition adoptée au tombeau de Metella Dans l’appareillage des diverses voûtes
(Fig. 16) peut oﬀrir des avantages ; car, ici, sphériques, les joints et les coupes sont norles joints sont seulement coudés, sans cros- maux à l’intrados sphérique ; les coupes, suisettes, et de manière à former un véritable vant des portions de plans méridiens vertiarc de décharge au-dessus de la partie basse caux dont le pôle est le sommet de la voûte ;
qui forme les claveaux de la plate-bande. les joints sont des portions de surface conique
dont le sommet est au centre et la directrice
Voir ﬁg. 6.37 p. 124 et ﬁg. 9.5 p. 174 un des petits cercles continus horizontaux.

Citation 104. Bazin (1888, p. 36) [...]

330

<!-- p. 332 -->

Annexe A. Sources bibliographiques

S’il s’agit de plate-bande, le joint ne peut voûte les coupes n’étaient pas normales à la
être normal ; il faut donc l’incliner. Lorsque surface d’intrados, il en résulterait que cerces joints, normaux ou non, ne sont pas suf- tains voussoirs présenteraient des angles aiﬁsants pour empêcher le glissement du vous- gus qui pourraient se brise après le décintresoir, on emploie un mode d’appareillage par- ment, au moment où les voussoirs se transticulier dit en crossette, qui consiste à donner mettent les pressions provenant de la charge
un redent à la surface du joint du voussoir ; supportée. On devra donc éviter les angles aicet appareillage est surtout employé dans les gus dans toutes les constructions en pierre de
plates-bandes. L’obligation d’avoir des joints taille, autant toutefois que cela sera possible
normaux, n’est donc pas absolue ; et souvent, sans tomber dans d’autres inconvénients plus
quand ces joints sont des surfaces gauches graves.
non développables, d’une taille diﬃcile par
Citation 108. Chaix (1890, p. 170)
conséquent, on les remplacera par des plans
approximativement normaux. Les pierres composant la plate-bande sont
juxtaposées suivant des faces planes qui
Une autre règle, également plutôt de taille
doivent forcément avoir une certain inclinaique de coupe, devra empêcher de donner à la
son sur l’axe vertical pour pouvoir se tenir et
pierre des angles trop aigus, qui la rendraient
porter ce qui est au-dessus
très fragile sur cette arête. Enﬁn, pour la division des coupes, nous donnerons les règles Citation 109. Chaix (1890, p. 172)
suivantes de Rondelet : Pierre tendre, une à
Pour faire disparaître l’aiguïté des claveaux
deux fois la hauteur d’assise ;
du côté de l’intrados, on termine les joints par
Moyenne, une à trois fois ;
des facettes mA, nA, pb (ﬁg. 297) normales
Dures, une à quatre fois ;
à l’intrados et auxquelles on donne une hauTrès dures, une à cinq fois.
teur d’au moins 5 centimètres. [...] Si de plus
on veut faire disparaître l’aiguïté des claveauxCitation 106. Pillet (1888)
du côté de l’extrados, on peut opérer par fa-
Toutes les fois que cela sera compatible avec cettes en retour d’équerre, comme du côté de
la stabilité, on choisira, ainsi que le recom- l’intrados, à partir d’une droite qrs (ﬁg. 298
mande Monge, pour lignes de lit et pour lignes [Fig. 6.9]) placée parallèlement à la ligne CD
de joint, les lignes de courbure de la surface. d’extrados et à 5 ou 6 centimètres de distance.
Dans le cylindre et dans le cône, les lignes On a alors des joints brisés tels que AmqC,
de courbure sont les génératrices et les sec- anre, bpsf... (Il ne faudrait cependant pas trop
tions droites ; dans les surfaces de révolution diminuer la longueur de la partie inclinée des
ce sont les méridiens et les parallèles. joints, car les claveaux n’auraient plus assez
de résistance.) Ces lignes de courbure jouissent de la
propriété d’être orthogonales les unes sur les Citation 110. Chaix (1890, p. 175)
autres, ce qui est la condition indiquée à 2◦, et
Quand la hauteur dont on dispose est faible
de plus les normal[i]es qui leur correspondent
et que, néanmoins, on désire donner de la sosont des surfaces développables (plan, cône,
lidité à l’appareil, on y arrive par les moyens
cylindre...).
suivants, dont nous ne garantissons d’ailleurs
pas l’eﬃcacité.
\* L’un de ces moyens consiste à faire un
\* * appareil à crossettes. [...]

Citation 111. Chaix (1890, p. 175)
J. Chaix
[...] ne faire emploi que de pierre tenace.
Avec des pierres tendres les crossettes seraientCitation 107. Chaix (1890, p. 16)
brisées par l’eﬀet de la pression qui s’exerce-
Au point de vue de la solidité de l’appa- rait sur elles.
reil, il faudra, quant on le pourra, éviter les
angles aigus, et n’avoir, autant que possible *
que des angles droits. Ainsi, si dans une * *

331

<!-- p. 333 -->

Annexe A. Sources bibliographiques

J. Denfer (1839-19 ? ?) retenus par des scellements, et d’un claveau
intermédiaire sans contact avec l’architrave
Citation 112. Denfer (1891, p. 195) (temple dit de Jupiter Stator).
On diminue la poussée, et en même temps on
maintient les voussoirs en cas de léger tasse- Voir ﬁg. 9.3 p. 171
ment, en logeant dans une entaille creusée au
\*fond de la feuillure des voussoirs une barre de
\* *fer carré de 0,05 de côté, qui a comme longueur 0m,40 à 0m,50 en plus de l’ouverture
de la baie. Les deux extrémités pénètrent donc
Camille Enlart (1862-1927)de 0,20 à 0,25 dans les sommiers. Cette barre
forme une sorte de tirant annulant la poussée
Citation 116. Enlart (1927, p. 26)
de la voûte, et présente assez de rigidité à la
ﬂexion pour soutenir un voussoir qui tendrait Les claveaux appareillés en crossettes sont
à glisser, ﬁg. 195. ceux qui s’accrochent les uns aux autres au
moyen d’angles saillants et rentrants ; on en
\* trouve aussi dont les joints décrivent divers
\* * proﬁls sinueux [note de bas de page : Par
exemple, au xiie siècle, au portail de Presle,
près de Laon. Le même artiﬁce a été employé
Auguste Choisy (1841-1909) au xiiie siècle dans des fûts de colonnettes
aux fenêtres du déambulatoire de la cathédraleCitation 113. Choisy (1899a, p. 278-279)
de Bourges.]. Les claveaux rendus ainsi soli-
Comme dernier exemple de consolidation daires ne peuvent glisser l’un sur l’autre et
métallique, nous citerons les armatures de fer l’arc cesse d’être élastique : il se comporte
du linteau de la porte du grand temple d’Agri- comme s’il était d’une pièce.
gente ; la rainure qui les contenait avait 0m16
de large et autant de hauteur ; probablement Citation 117. Enlart (1927, p. 30)
elle était remplie par un paquet de fers plats
Certains linteaux, faute de pierre résistante
posés de champ.
d’une grande dimension, sont appareillés en
Citation 114. Choisy (1899a, p. 303) claveaux, comme des arcs. On les nomme
plates-bandes appareillées ; ce sont de véri- Au temple des Géants d’Agrigente, la faute
tables arcs, mais dont l’intrados et l’extra-s’aggrave encore. L’échelle est si colossale et
dos sont remplacés par des lignes horizon-la pierre si médiocre, qu’on renonce à poser
tales. Très usités par les Romains, ils ontd’une colonne à l’autre une véritable plate-
été souvent employés dans les portails dubande : l’architrave est fractionnée non plus
Moyen Âge, où l’on a fréquemment atténuépar un plan de lit, mais par deux (détail A).
leur manque de solidité par des appareils àNon seulement elle ne porte pas, mais il faut
crossettes plus ou moins compliqués.la porter. De la cette cloison qui l’étaie pour
ainsi dire. Réaliser l’aspect des ordres à l’aide
Citation 118. Enlart (1927, p. 322-323)
de matériaux trop petits pour l’échelle, voilà
l’origine de l’ordonnance à colonnes engagées Les plates-bandes appareillées ne se rend’Agrigente. contrent que dans les linteaux de portails ;
elles y sont fréquentes et souvent, pour plus
Citation 115. Choisy (1899a, p. 515) de solidité, les joints y décrivent un tracé
La ﬁg. 2A montre l’appareil type de la colon- sinueux qui est en même temps un appanade romaine. L’architrave est monolithe, et reil décoratif [note de pied de page : Presles
la frise appareillée en décharge : chaque tra- (Aisne), Villers-Saint-Paul (Oise), Berteauvée de la frise se compose de deux sommiers court (Somme), etc.]

A.3 Citations des ouvrages récents

332

<!-- p. 334 -->

Annexe A. Sources bibliographiques

Association ouvrière des Compa- Mais ces linteaux appareillés, plates-bandes
gnons du devoir ou voûtes plates étaient utilisés exceptionnel-
lement â l’époque gothique, et surtout pour
Citation 119. Association ouvrière des des cheminées. [...] Il existe de nombreux
Compagnons du devoir (1996, p. 78) exemples de cheminées dont le manteau re-
pose sur une plate-bande appareillée et qui Deux paramètres qui s’opposent sont à l’ori-
datent du Moyen Âge.gine d’une divergence d’opinion au sujet de
la meilleure méthode de construction. Si on Citation 124. Bechmann (1993, p. 201)
remonte le point de convergence, les lits sont
plus inclinés et les poussées horizontales exer- Mais dans l’ensemble, la plate-bande appacées par la plate-bande sur les jambages dimi- reillée, la « voûte plate » ou « l’arc plat »
nuent proportionnellement ; mais, en donnant sont des solutions peu fréquentes à l’époque
des angles plus aigus aux claveaux, on accen- gothique ; elles pouvaient donc exciter la cutue leur faiblesse. Dans le cas contraire, les riosité et l’intérêt de Villard.
joints sont moins inclinés, les claveaux sont Citation 125. Bechmann (1993, p. 199)
donc moins fragiles, mais les poussées horizontales augmentent. Or, à l’époque gothique, la plupart des portes
étaient sans huisseries ; elles pivotaient sur
Citation 120. Association ouvrière des des gonds scellés directement dans la maCompagnons du devoir (1996, p. 130) çonnerie et étaient simplement composées de
Ces facettes ont généralement 5 cm de hau- planches assemblées sur des traverses et dans
teur car, si elles doivent être suﬃsamment lesquelles il était facile de pratiquer une déhautes pour remplir leur fonction, il faut éga- coupe arrondie ; les fenêtres étaient encore gélement conserver le maximum de hauteur aux néralement dépourvues de carreaux et simcoupes, puisque ce sont elles qui donnent sa plement fermées par des volets. Mais, peu à
résistance à la plate-bande. peu, on souhaita plus de confort, des ferme-
tures plus étanches et des fenêtres vitrées.
Citation 121. Association ouvrière des
Cela n’était possible qu’avec des huisseries auCompagnons du devoir (1996, p. 128-129)
tour des portes et des bâtis dormants autour
Au cours des siècles, l’emploi de crossettes des croisées, éléments qu’il est bien plus aisé
ou de claveaux en tas-de-charge a été critiqué. de faire rectangulaires que cintrés. C’est une
On leur a notamment reproché de ne pas lais- des raisons pour lesquelles les linteaux apser travailler naturellement la plate-bande. Il pareillés formant des arcs plats devinrent de
est donc préférables, quand cela est possible, plus en plus courants depuis la Renaissance
d’utiliser un arc de décharge. jusqu’au xviiie siècle.
[...]
Toutefois, il ne faut jamais exécuter de Pérouse de Montclos
crossettes sur les joints de la clef : c’est en effet la seule pierre qui peut encore descendre et Citation 126. Pérouse de Montclos (1995,
claver la plate-bande, puisque le reste des cla- p. 165)
veaux forme un bloc ; elle permet donc d’ab- Au début du xviie siècle, le meneau et le
sorber les mouvements éventuels de la maçon- croisillon (ou les croisillons) en pierre, qui
nerie. divisent la croisée (et lui donnent son nom),
Citation 122. Association ouvrière des sont remplacés par des meneaux et croisillons
Compagnons du devoir (1996, p. 140) en bois sur lesquels pivotent des vantaux ap-
pelés guichets (en nombre variable : quatre ou
Souvent, les voûtes plates sont construites
six, ou-deux seulement, suivant que la baie a
avec une légère ﬂèche, qui tend à diminuer
un ou deux croisillons ou n’en a pas). Ces guiou à disparaître lors du décintrement.
chets sont eux-mêmes divisés par un réseau de
plomb portant les vitres.
Bechmann
Citation 127. Pérouse de Montclos (1995,
Citation 123. Bechmann (1993, p. 200) p. 166)

333

<!-- p. 335 -->

Annexe A. Sources bibliographiques

La mutation la plus importante pour le n’enseignera à quiconque n’est pas de notre
confort de la maison est la disparition des métier et n’a jamais fait travail de maçon
parties dormantes, des meneaux et croi- comment tirer l’élévation du plan ».
sillons, c’est-à-dire le passage de la croisée Citation 131. Sakarovitch (1992, p. 537)
à la fenêtre, que l’on peut dater des années
Les voûtes ellipsoïdes, très fréquentes dans1640 : les deux vantaux de la fenêtre garnis
l’architecture baroque et classique (on ende petits bois portant les carreaux, se joignent
trouve à Saint-Pierre de Rome, dans lesau centre.
églises de la Sorbonne, du Val-de-Grâce, des
Citation 128. Pérouse de Montclos (1982, Invalides...) furent traditionnellement appap. 86) reillées, comme les voûtes sphériques ou les
Le succès du traité de Derand, maintes fois ellipsoïde de révolution, avec des rangs d’asréédité, ne doit pas faire illusion. La stéréoto- sise horizontaux.
mie ne s’apprend pas dans les livres. L’eﬀort Citation 132. Sakarovitch (1992, p. 539de clariﬁcation, de généralisation, de vulgari- 540)
sation des mathématiciens, les Desargues, les
Les ponts biais font leur apparition au mo-La Hire, les Frézier, ne modiﬁera pas sensi-
ment de la mise en place des réseaux de che-blement la situation qui prévalait au Moyen
min de fer. Dans l’article qui marque le pointÂge : le trait reste hermétique, il appartient
de départ des études théoriques sur le su-à quelques initiés, et bien des appareilleurs
jet, Lefort cite intégralement le passage dupourraient en remontrer sur ce point aux plus
cours de Monge concernant l’appareillage dessavants architectes.
voûtes pour constater que cette « analyse, si
bien faite, [...] fait presque complètement absSakarovitch traction de l’élément mécanique qui domine la
question. Il est nécessaire, en eﬀet, de diriger
Citation 129. Sakarovitch (1998, p. 178-
les surfaces des joints normalement à la sur179)
face des pressions maxima qui doivent naître
Curieusement les considérations statiques au décintrement. » [Lefort 1839 pp290] Or
sont totalement absentes de tous les textes cette surface, pour une voûte extradossée pade commentaires des épures des descentes rallèlement (c’est-à-dire suivant une surface
biaises. Pourtant si le biais est très pro- de même nature que celle de la douelle) est
noncé, indépendamment de la descente et du la surface normale à la ligne de plus grande
talus, les tracés proposés par les diﬀérents contraction, ligne qui ne se confond pas néauteurs, qui restent géométriquement exacts, cessairement avec la ligne de plus petite courdeviennent inapplicables dans les faits. Cer- bure de la surface. [...] Nous ferons remartains voussoirs comporteraient alors des ai- quer, d’ailleurs, que la condition elle-même
guïtés trop fortes et risqueraient d’éclater sous d’avoir des joints normaux à la voûte est plus
la poussée de la voûte, comme Rondelet en fait géométrique que mécanique, et la véritable déla remarque. ﬁnition de la surface de joint serait celle-ci :
[...] « Cette surface doit être telle que la normale
Pourtant dans l’épure du biais passé évo- en un point donné du joint soit dirigée suiquée au début de ce chapite, Frézier propose vant la résultats des pressions en ce point »
un tracé qui permet précisément de conserver [Graeﬀ, 1867, pp12].
des plans de joint perpendiculaires à la direc- Citation 133. Sakarovitch (1992, p. 540)
tion de la poussée exercée par la voûte tout en
Entre les changements de mode en architec-obtenant une surface d’intrados cylindrique.
ture et les limites intrinsèques de la théorie,
Citation 130. Sakarovitch (1992, p. 531) l’appareillage des voûtes selon les lignes de
Mais, pendant tout le Moyen Âge, le savoir courbure n’a pas eu le succès escompté.
des tailleurs de pierres est gardé secret par la
corporation dont les statuts, publiés à Ratis- Benvenuto
bonne en 1459, précisent encore : « nul ouvrier, nul maître, nul parlier, nul journalier, Citation 134. Benvenuto (2006, p. 388)

334

<!-- p. 336 -->

Annexe A. Sources bibliographiques

Cinque anni dopo appare l’opera di F. J. Dans le pavillon central de l’aile occidenGerstner nella quale questo autore introduce tale du Louvre, édiﬁé entre 1624 et 1642 enper la prima volta due nozioni in seguito lar- viron, Jacques Le Mercier recourt à divers
gamente utilissate dagli studiodsi degli archi : types de plates-bandes (ﬁg. 5). Dans les arla linea di resistenza e la linea di pressione. cades latérales surmontées d’un œil, les claLa prima è il poligono che congiunge i centri veaux sont coupés de manière que dans la fadi pressione su ognuno dei piani dei giunti ; çade la « cour Carrée » les joints semblent
il poligono si muta in linea curva se i giun- verticaux ; par contre, dans l’autre façade, le
ti sono inﬁnitamente numerosi e sottili. La système des claveaux inclinés reste visible.
seconda è l’inviluppo delle rette d’azione delle L’entablement placé sur les colonnes jumeforze reattive tra giunto et giunto. Le due line lées est lui aussi réalisé avec des claveaux à
sono generalmente distinte. joints inclinés. Dans ce demier cas, la fonc-
tion d’arc de décharge échoit à la lunette creu-
sée dans la voûte. Lorsqu’en 1654-1661 enviCitation 135. Benvenuto (1991, p. 432) ron, Louis Le Vau érige l’autre pavillon du
About 1830, two new notions were intro- Louvre, qui se trouve au centre de l’aile sud,
duced to the study of arches : the “line of il reprend le système de Lemercier en ne moresistance” and the “line of pressure”. The diﬁant que la coupe des claveaux dans l’entaﬁrst is a polygon that connects the centres of blement : les joints visibles de la plate-bande
pressure of the planes of the joints. The poly- sont verticaux.
gon changes into a curved line if the voussoirs
are inﬁnitely numerous and thin. The second Citation 137. Tibières (2012)
is the locus of the consecutive intersections of Tandis que les constructeurs français sont
the directions of the resultant pressures upon contraints de se pencher sur le dessin des clathe joints. According to Timoshenko, J.J. veaux parce que la tradition de la « coupe des
Gerstner should be credited with the ﬁrst in- pierres » est fondée sur la visibilité de l’asvestigation of the lines of pressure, while H. semblage des pierres, en Italie, l’usage de la
Moseley examined in greater depth and dis- plate-bande, à l’exception du cas signiﬁcatif
played the diﬀerent properties of the two lines du portique de Michel-Ange avec les pierres
(Figure 12.38). For equilibrium to exist, the apparentes, entraîne souvent le recours à la
line of resistance (a, b, c) must be entirely technique, déjà pratiquée par les anciens Roinside the interior of the arch; if it crosses mains, du revêtement qui masque la présence
the extrados or intrados below a certain an- d’une structure qui pousse.
gle, the arch will break near its point of intersection with the line. If the line of resistance Citation 138. Tibières (2012)
is tangent to one of the edges, the voussoirs C’est justement durant la construction du
may immediately rotate — a state correspond- portique de Michel-Ange, dans la manière de
ing to limit equilibrium, which only inﬁnitely disposer les architraves en une seule pièce (vistrong material could sustain. On the ohter sibles de la place) et en plusieurs parties (sous
hand, the angle ρ with which the line of pres- le portique), et dans le choix d’utiliser des
sure (A, B, C, ...) crosses the joints must barres métalliques le long de l’extrados, que
be connected with the friction of the surfaces se posent les questions de la visibilité ou non
in contact; if f is the coeﬃcient of friction des joints des claveaux et de la position de la
anf ϕ = tan−1 f is the “friction angle” (or, barre métallique.
in Moseley’s words, “the limit angle of resistance”) sliding will or will not occur depending on whether ρ is greater or not greater than Nollet
ϕ.
Citation 139. Nollet (2012)

Le terme plate-bande est originaire de
Tibières France, où il est introduit vers le XIIIe
siècle. Villard de Honnecourt nommait « penCitation 136. Tibières (2012) dans rivlés » (pendants réglés) les claveaux

335

<!-- p. 337 -->

Annexe A. Sources bibliographiques

cunéiformes de cette structure. Au cours Nantes au xviiie siècle. [...] Les comptes endu xvie siècle, le terme « platte bande » est registrent de juin 1765 à février 1768 l’approcouramment utilisé mais désigne une mou- visionnement de six mille cinq cent soixantelure. Dans la traduction française du De re dix-huit de ces os. La maçonnerie du palais
aediﬁcatoria, aux soins de Jean Martin, pu- est donc entièrement truﬀée d’os de pied de
bliée en 1553, il indique un listel. Jean Bul- bœuf systématiquement mis en œuvre.
lant, dans ses écrits, parle de « lisiere ou
bande platte de moulure » et de « platte- Citation 142. Bienvenu (2013, p. 213)
bande », toujours dans le sens décoratif. Dans les rares devis conservés pour la
construction tant publique que privée à
Citation 140. Nollet (2012) Nantes au xviiie siècle, avant cette aﬀaire,
Son [De l’Orme] traité de 1567 contribue les fers sont comptés au poids et il n’est pas
à diﬀuser également la déﬁnition de « plate- non plus fait mention d’emploi d’os dans la
bande » pour indiquer ce que Léonard et Serlio maçonnerie, à une exception près à notre
nommaient les architraves en plusieurs par- connaissance. Le procédé a toutefois été largeties. ment utilisé, aux dires des tailleurs de pierre
et artisans nantais qui en rencontrent fré-
quemment. Ces os sont utilisés pour cramBienvenu ponner à la maçonnerie du mur les pierres de
corniches ou autres éléments en saillie lorsCitation 141. Bienvenu (2013, p. 212) qu’il ne leur est pas donné de queue suﬃsante.
[À propos du Palais de la Chambre des Autre emploi fréquent, ils servent à aﬀermir
Comptes à Nantes] Si l’usage du tirant est le raccord de deux murs perpendiculaires, un
courant et public, l’utilisation d’os de pied mur de face et un mur de refend ou encore
de bœuf appartient à la pratique de chan- un mur de refend et le parpaing d’un escalier.
tier et est absente des traités, savants mais Aucun exemple d’emploi dans une plate-bande
aussi pratiques, qui ne font apparaître que des n’est donné dans l’état actuel de la connaiscrampons de fer. Ceineray fait appel à des sance du bâti nantais du xviiie siècle. Mais,
ouvriers pour l’expliquer lors de l’expertise une plate-bande d’une portée équivalente à
de Crucy. L’emploi de ce matériau organique celle de la Chambre des comptes n’est pas cousemble par ailleurs relativement fréquent à rante dans le bâti public ou privé.

A.4 Discussion des plates-bandes à l’Académie royale
d’architecture

L’Académie royale d’architecture a été établie par Louis XIV sur le conseil de
Colbert en 1671. Toutes les semaines ont lieu d’une part un cours, donné successivement par François Blondel, Philippe de La Hire et Antoine Desgodets (ﬁg. A.2), et
une séance où sont débattus diﬀérents sujets : lecture et analyse des auteurs anciens
(Vitruve, Palladio, Serlio, De l’Orme notamment), avis sur des chantiers en cours, avis
sur des inventions qui leur sont présentées etc. Les procès-verbaux établis à chaque
séance de 1671 à 1793 rendent compte des débats, et ont été publiés de 1911 à 1926
en neuf volumes (Planat (2) 1888a ; Lemonnier, 1915). Institution royale, l’Académie
fut supprimée en 1793, avant d’être rétablie en 1795 puis 1816 au sein de l’Institut
de France, où elle forme aujourd’hui une section de l’Académie des Beaux-Arts.

Les plates-bandes font partie des sujets débattus par l’Académie royale d’architecture, soit du point de vue de la coupe des pierres, soit du point de vue des armatures

(2). L’article de l’encyclopédie est signé par les initiales M.D.S.

336

<!-- p. 338 -->

Annexe A. Sources bibliographiques

de fer des plates-bandes armées. Nous indiquons sur les frises historiques suivantes
le nom des Premiers architectes du roi successifs (ﬁg. A.1), ainsi que ceux des professeurs d’architecture à l’Académie royale d’architecture (ﬁg. A.2), et le sujet des débats
successifs où le sujet des plates-bandes intervient (ﬁg. A.3). Les extraits importants
des procès-verbaux concernant les plates-bandes sont données ci-dessous.

1500 1550 1600 1650 1700 1750 1800
Cerceau Le
de Brosse Lemercier Vaud’Orbay deCotteVGabriel Gabriel du Métezeau Louis François RobertJacques Hardouin-Mansart AndrouetetLouisSalomon Jacques Ange-Jacques II Jules
Jacques

Fig A.1 – Premiers architectes du roi

1500 1600 1700 1800

Blondel La HireDesgodets de
François PhilippeAntoine

Fig A.2 – Professeurs d’architecture à l’Académie royale d’architecture

Citation 143. 31 mars 1672, Vol. 1. les diﬀérentes manières de poser les claveaux
dans les plates bandes et les vousoirs dans les Il est préconisé par l’Académie de mettre en
arcs, sur quoy il y a eu des sentimens diﬀé-place trois tirants en fer sous une plate-bande
rens, sur lesquelz elle a résolu de s’esclairerde grande portée, en cours de construction à
au premier jour.Versailles.
Ont signé : n.c.Ont signé : n.c.
Citation 146. 24 mai 1683, Vol. 2.
Citation 144. 26 juillet 1677, Vol. 1.
La Compagnie n’a rien trouvé à quoy elle
Ce qu’il [De l’Orme] dit des liaisons des peust s’arrester dans la lecture qu’elle a faite
pierres en coupe pour l’architrave est bon, des assemblées tenues cy devant, depuis le 24
quoyqu’à dire le vray, le moins qu’on s’en mai 1677 jusques au 26 juillet de la mesme
puisse servir est le meilleur. année. Elle a seulement fait réﬂexion sur ce
Ont signé : Blondel, Bruand, Gittard, Le qu’elle dit dans la dernière que la pensée de
Paultre, Mansart, Mignard, d’Orbay, Féli- Philbert De l’Orme n’est pas mauvaise de
bien. tailler les architraves par claveaux, en forme
de platte bandes, quoy qu’elle ne voulust pas
Citation 145. 29 mai 1679, Vol. 1. en conseiller l’usage trop fréquent ; elle au-
L’on a continué la lecture de Léon Baptiste roit volontiers souhaitté que l’on peust faire
Albert sur le 9e chapitre du 3e livre. Et, par comme en Italie des architraves de matière à
occasion, la compagnie s’est entretenue sur se porter d’elles mêmes, comme de marbre et

337

<!-- p. 339 -->

Annexe A. Sources bibliographiques

1650 1700 1750 1800

l’Orme armées l’Orme(Souﬄot) De De De plate-bande(Gabriel) plate-bande voûteplate-bandeplate Antoinel’Ormeéquilatéralfausse-coupecrossettes de de plates-bandesdeplates-bandes / Saint et et
fer sous des de trianglerejet dés plates-bandeslinteau dimensions/ plate-bande plate-bande que/ fers et et et plate-bandeclaveaux voussureplate-bandebas coupe fer plate-bandefer de l’Orme, arrièredés plus rappel De plate-bande croisillons, de centrede/
dés
/ plate-bande équilatéral plate-bande et triangle
fer et
brisés
lits

Fig A.3 – Sujets des débats sur les plates-bandes à l’Académie royale d’architecture

« L’on peut pour empescher que les bouts de ces
pierres quarrées ne paroissent à la tête de la plate
bande, laisser quatre a cinq pouces de parament de
pierre â ces claveaux ; l’on pourroit même mettre avec
lien de pierre, des quarrées long de bois si on le juge
à propos, dans la crainte que les quarrées de pierre ne
se cassent, dans l’eﬀort que prendra la platte bande,
alors qu’elle sera decintrée. Outre précaution qu’on
propose de prendre, pour unir et contenir ensemble
tous les claveaux de la plate bande, avec de tenons
et des clefs [ ?] en dets, l’on y peut encore mettre des
tirans et ancres de fer » Transcrit par Guettard (2012)

Fig A.4 – Mémoire de Bullet présenté à Fig A.5 – Mémoire de La Hire présenté à
l’Académie le 14 janvier 1704, reproduit l’Académie le 14 janvier 1704, reproduit
dans Guettard (2012) dans Guettard (2012)

338

<!-- p. 340 -->

Annexe A. Sources bibliographiques

Manière de faire les coupes des plates bandes, pour les claveaux
des portes et croiséess, appliquée à une porte de 12 pieds de large.
Ayant tracé aplomb les piédroits AI BD, et la plate bande de [niveau] AB,
on divisera la largeur de la plate bande AB, en 6 parties égales, on prendra
5 de ces parties, comme de B en O, [dont] on décrira une portion de cercle de B
en O, jusqu’à la ligne du milieu en E, qui sera le centre d’où on décrira la portion
de cercle AGB, qu’on divisera en autant de parties égales, qu’on voudra faire de
claveaux,
et comme il faut que le dessous de la plate bande soit un peu bombée pour les
raisons
qu’on dira cy après, on donnera un pouce et demi pour le bombement, sur la
largeur
de 12 pieds, et plus ou moins en proportion que la plate bande sera plus ou moins
large,
ce [...] faire avec une règle [...] sur le champ, on fera une autre
ligne de 3 pouces au dessus, qui lui sera parallèle, puis du centre F ... les
divisions de ... AGB, on tirera les coupes des claveaux jusqu’à cette seconde
ligne bombée, puis on tirera ces coupes aplomb jusqu’au [...] de la platebande,
bombée, on doit avancer de trois pouces les premières coupes des sommiers A et
B
et diviser l’arc AGB, à commencer de ces premières coupes.
Il y a deux raisons pour lesquelles on doit bomber un peu le [dessous ?] des plates
bandes, dont la premières est que quel que soin qu’on prenne pour la précision
des lits en ... des coupes, quand on a [décintré] la plate bande le poids en fait
toujours baisser un peu le milieu, & l’autre raison est que la plate bande ...
d’une ligne droite, elle paroit toujours plus basse dans le milieu qu’aux extrémités,
mais il faut chercher les raisons de cette [apparence ?].
Lu et présenté à la compagnie le
30e Juin 1710 [...]

Fig A.6 – Mémoire de Bullet présenté à l’Académie le 30 juin 1710, reproduit dans
Guettard (2012)

de travertin, et qu’on ne voulust pas faire de blasmer celuy d’une seule pierre, si ce n’est
si grandes entrecolonnes, aﬃn que les archi- qu’elle n’eust son lit dessus et dessous dont la
traves peussent se soustenir tout d’une pièce, pratique a esté condamnée.
leur faisant seulement des arcs en descharge Ont signé : Bruand, Bullet, d’Orbay, Félibien.
par dessus, comme ont fait les anciens, voyant
avec regret la nécessité où les grandes entre- Citation 148. 8 octobre 1688, Vol. 2.
colonnes nous jettent en France de nous ser- On s’est entretenu sur une question qui a
vir d’architraves taillez à clavaux, qu’on est esté faite à la Compagnie par M. Bullet sur
obligé de tenir bandez ensemble, à force de ti- une voûte de four, dont le plan est en ovale et
rans et d’ancres de fer, dont la rouille, man- le proﬁl aussy en ovale sur sa longueur, mais
geant avec le temps et le fer et la pierre, cause circulaire sur la largeur, ce qu’on appelle en
à la ﬁn la ruine des plus beaux ouvrages. géométrie un demy sphéroïde long, pour sçaOnt signé : Blondel, Gittard, Félibien. voir s’il estoit plus à propos de faire le plan de
chaque assise en ovale semblable au plan toCitation 147. 29 décembre 1687, Vol. 2. tal, ou de le faire à l’ordinaire par des lignes
M. Bullet a commencé à lire à l’Acadé- courbes paralèles entre elles. La Compagnie a
mie un mémoire qu’il a escrit sur le sujet trouvé à propos de s’arrester à la pensée de
des combles, tant de leur origine que de leur M. Bullet, qui est la première des deux dont
forme et de la proportion de leur hauteur, se- nous venons de parler, quoyque tous les plans
lon l’usage et la nécessité des diﬀérens pays. de ses assises soient tout diﬀérents entre eux ;
A cette occasion, il parle du mauvais usage on a l’avantage par cette manière d’avoir la
que l’on fait des lucarnes qu’on met dans les clef semblable au plan, pour y faire de l’ornecombles pour donner du jour aux logemens ment qu’on voudroit qui puisse estre agréable
qu’on y pratique. à la veue.
L’on a proposé si une plattebande d’une Ont signé : De La Hire, Bruand, Bullet, d’Orseule pierre, dont les lits seroient aux deux bay, Félibien
bouts ou délit en joint, seroit aussy solide que
Citation 149. 15 octobre 1688, Vol. 2.si elle estoit faite de plusieurs claveaux, l’on
[a] plus approuvé l’usage des claveaux, sans M. de la Hire a apporté et présenté à la Com-

339

<!-- p. 341 -->

Annexe A. Sources bibliographiques

pagnie une nouvelle manière de tracer tous la ﬁgure qu’on pouroit donner aux rosons dont
les panneaux des voûtes de four, tant surbais- on voudroit orner cette voûte ; la Compagnie
sées que surhaussées, sans sortir du champ a trouvé que cette méthode devoit estre préféde l’ouvrage, et dont il donnera un dessein au rée à toutes les autres.
premier jour. Ont signé : De La Hire, Bruand, Bullet, d’OrOnt signé : De La Hire, Bruand, Bullet, d’Or- bay, Félibien
bay, Félibien
Citation 153. 19 novembre 1688, Vol. 2.
Citation 150. 22 octobre 1688, Vol. 2. M. de la Hire a apporté à la Compagnie une
On s’est encore entretenu sur les voûtes de démonstration dans laquelle il fait voir que,
four qui ont une ellipse pour leur base et une dans les voûtes surbaissées, la clef et les autres
ellipse aussy pour leur proﬁl, et M. de la Hire voussoirs qui en sont proches font plus d’efa promis d’apporter au premier jour la ma- fort pour escarter les premiers voussoirs que
nière de tracer les panneaux, tant de duelle ceux-cy n’ont de force pour y résister, ce qui
que de lit, d’une manière géométrique, les el- se prouve par la propriété du coin, qui est plus
lipses du plan et du proﬁl estant aussy géomé- aigu dans la clef et dans les voussoirs qui lui
triques, à la diﬀérence de celle dont les ou- sont proches que dans les autres. Il y auroit
vriers se servent ordinairement, qui sont for- plus de solidité si tous les joints de lit tenmez par des portions de cercle. doient au centre de l’ovale qui forme le cintre
surbaissé ; mais cela n’est pas si agréable à laOnt signé : De La Hire, Bruand, Bullet, d’Or-
veue, cependant on est obligé de tomber en cebay, Félibien
cas en plusieurs rencontres.
Citation 151. 29 octobre 1688, Vol. 2. Ont signé : De La Hire, Bruand, Bullet, d’Or-
M. Bullet a apporté la manière de tracer les bay, Félibien
panneaux des voûtes de four elliptiques, tant
Citation 154. 14 Aoust 1690, Vol. 2.en leur proﬁl qu’en leur plan, suivant la pratique ordinaire de tracer les ellipses avec des M. de la Hire a apporté à l’assemblée un moportions de cercles, et M. de la Hire a aussy delle de l’arrière voussure qu’on appelle ordiprésenté à l’Académie, suivant ce qu’il avoit nairement de Saint Antoine, où les divisions
promis, la manière de tracer les panneaux de des claveaux de la platte bande sont égales
la mesme voûte par les règles de géométrie, entre elles, de mesme que la teste de la voussans sortir du champ de l’ouvrage, ce qui n’a sure, dont il apportera à sa commodité une
point esté pratiqué jusques à présent. On s’est épure, tant par cette méthode que par celle du
encore entretenu sur la ﬁgure qu’on doit don- père d’Erard, aﬃn de faire voir la diﬀérence
ner aux rosons ou rosasses enfermez dans une de l’une et de l’autre.
ﬁgure quadrilatère, pour garnir toute la voûte Ont signé : De La Hire, Bruand, Bullet, de
dont on a parlé cy dessus. Et l’on a remis à Cotte, Mansart, d’Orbay, Félibien.
s’en entretenir encore la première fois.
Ont signé : De La Hire, Bruand, Bullet, d’Or- Citation 155. 14 décembre 1693, Vol. 2.
bay, Félibien L’on a leu le quinzième chapitre de Philbert
de Lorme. On a approuvé en partie la manière
Citation 152. 12 novembre 1688, Vol. 2. qu’il propose pour aﬀermir la platte bande
M. de la Hire a présenté à la Compagnie l’af- des architraves, en mettant et en entaillant
ﬁche pour les leçons d’architecture de l’année dans les lits de joints des claveaux durs ou
prochaine, où il promet d’expliquer le trait de cailloux longs, pour cramponner les claveaux
la coupe des pierres, suivant la méthode ordi- les uns avec les autres et par ce moyen ne
naire, et d’autres particularitez qu’il donnera faire la platte bande que comme si elle estoit
dans les leçons. d’une seule pièce, et l’on doit observer de ne
mettre ces sortes de crampoms qu’à plus de Il a encore apporté un modelle d’une
six poulces près des parements.voûte de four elliptique en son plan et en son
proﬁl, où l’on voit la forme des douelles de Ont signé : De La Hire, Bruand, Bullet, de
toutes les pierres des assises, ce qui fait voir Cotte, d’Orbay, Félibien.

340

<!-- p. 342 -->

Annexe A. Sources bibliographiques

Citation 156. 20 janvier 1698, Vol. 3. diﬃculté proposée.

A l’égard de ce que M. Blondel dit dans Ont signé : De La Hire, Bruand, Bullet, Desle dernier chapitre du mesme livre touchant godetz, Gobert, Lambert, de Lespine, Mollet,
les plattes bandes, que les joints des claveaux Prévost, Félibien.
doivent tendre au sommet d’un triangle équilatéral renversé, la Compagnie a jugé qu’il Voir ﬁgures A.4 et A.5
faut faire le centre de ces claveaux plus bas,
pour empescher que les joins de ces mesmes Citation 160. 11 février 1704, Vol. 3.
claveaux ne deviennent trop aigus vers le cou-
La Compagnie estant plus nombreuse a de
sinet et ne soient par ce moyen trop faciles à
nouveau examiné la proposition faite par M.
casser.
Lambert au sujet des plattes bandes. L’on a
Ont signé : De La Hire, Desgodetz, Félibien relu les mémoires de M. Bullet et de M. De La
Hire. Et comme ils ont donné matière d’exaCitation 157. 22 Aoust 1701, Vol. 3. miner plus particulièrement les diﬃcultés de
La Compagnie s’est aussi entretenue sur la la question, on a jugé à propos de faire les
pratique qui a quelquesfois esté usitée dans les sommiers plus larges que les tailloirs des chaportes en plattes bandes, à l’égard des clavaux, piteaux, observant de les dégager de la saillie
où l’on a faict tous les joins à plomb. L’on a des tailloirs, en sorte que lesdits sommiers ne
pas approuvé cette pratique et il a esté trouvé portent que sur le nu de la colonne. Il a aussy
plus à propos de faire paroistre les joins tels esté proposé de tailler les pierres des claveaux
qu’ils sont suivant leurs coupes pour satisfaire en crossettes d’environ un pouce et à quatre
les yeux et l’esprit par l’idée de la solidité. pouces près du parement de la teste.
Ont signé : De La Hire, Bruand, Bullet, de Ont signé : De La Hire, Bruand, Bullet, DesCotte, Delisle-Mansart, Desgodetz, Gabriel, godetz, Gobert, Le Maistre, de Lespine, PréGobert, Le Maistre, de Lespine, Félibien. vost, Félibien.

Citation 161. 15 avril 1709, Vol. 3.Citation 158. 7 janvier 1704, Vol. 3.
M. Desgodets a lu un traitté intitulé : Traité La Compagnie, sur ce que M. Lambert a pro-
pour les voûtes portées sur des colonnes ouposé touchant la manière de faire des plastes
pilliers ronds à double arreste en platte bandebandes, a agité plusieurs questions touchant
sur des plans carrés longs et parallélogramesl’usage du fer et la manière de l’employer en
biais, dont les clefs et tous les joints en litde pareils ouvrages où il est diﬃcile de s’en
sont de niveau.passer et où il faut luy conserver toute sa
force. Ce qui a occupé toute la conférance et a Ont signé : De La Hire, Bruand, Bullet, Desparu d’assés grande conséquence pour (estre) godetz, de La Hire ﬁls, de Lespine, Félibien.
examiné encore plus particulièrement dans la
prochaine assemblée avant d’en délibérer. Citation 162. 24 février 1710, Vol. 3.

Ont signé : De La Hire, Bruand, Bullet, Des- On agite une question sur la coupe des pierres
godetz, Gobert, Lambert, de Lespine, Mollet, au sujet de la coupe des clavaux d’une platte
Prévost, Félibien. bande, et l’on a blasmé les coupes qui sont
à plomb dans la teste en face, en ce qu’elles
Citation 159. 14 janvier 1704, Vol. 3. choquent les yeux et qu’elles n’ont aucune
aparence de solidité. Au sujet de la proposition qui a esté faite
dans l’assemblée précédante pour la manière Cependant, comme les clavaux qui sont
de construire solidement des plattes bandes de en coupe ont une incommodité, en ce que
pierres, M. Bullet a donné un mémoire qui a les angles des pierres qui sont proches des
esté lu à la Compagnie et où il y a un des- sommiers sont trop aigus et sont sujets à se
sein. Un autre mémoire concernant la mesme rompre et à s’éclater, c’est pourquoy on fait
proposition, que M. de La Hire a présenté, a les extrémitez de la coupe à plomb jusques à
aussy donné lieu à plusieurs questions qu’on la hauteur de trois pouces ou environ ; et, pour
doit agiter avant que de rien résoudre sur la ce qui est du centre de la coupe des clavaux,

341

<!-- p. 343 -->

Annexe A. Sources bibliographiques

on a jugé qu’il doit estre au sommet du tri- seroient d’un bon usage pour les batimens et
angle équilatéral dont les costez sont égaux à que le sr Chopitel pouvant donner ces espèces
la longueur de la platte bande. de fer à meilleur marché qu’on ne le peut faire
Ont signé : De La Hire, Boﬀrand, Bullet, Des- en les fabriquant à l’estampe, on pourroit en
godetz, de La Hire ﬁls, de Lespine, Félibien. multiplier l’usage.
Ont signé : Aubry, Beausire père, Beausire,
Relevé par Jeanneret (2012). Billaudel, Boﬀrand, Cartaud, Chevotet, De-
luzy, Garnier d’Isle, Godot, Hazon, Lebon,
Citation 163. 16 juin 1710, Vol. 3.
Ledreux, Legrand, de Lespée, Loriot, Tane-
Les anciens architectes françois partageoient vot, Camus.
l’ouverture des fenestres par des croisillons,
qu’ils croyoient nécessaires particulièrement Citation 166. 18 janvier 1762, Vol. 7.
dans les plus grandes ouvertures, pour souste- L’Académie étant assemblée, on a examiné
nir les plattes bandes, et l’on voit encore des le model que M. Gabriel a fait faire de trois
exemples de ces croisillons dans les fenestres moyens diﬀérens dont il se propose d’emles plus anciennes du Louvre. ployer celui qui paroîtra le plus seure à la
L’on a depuis retranché ces croisillons à Compagnie pour la construction des plattes
cause qu’ils ostoient beaucoup de jour. Mais bandes des colonnades de la place de Louis
la Compagnie, en considérant dans le Louvre Quinze et les armatures de fer qui doivent
les fenestres où il y a encore des croisillons, entrer dans laditte construction ; et l’Acadéa trouvé que non seulement ils ostent beau- mie, pour se donner un plus long examen, est
coup de jour, mais encore qu’en arrestant la convenu de ne déterminer son avis que lundi
clef ils sont cause que les claveaux des costez prochain.
descendent plus facilement et endommagent
Ont signé : Gabriel, Aubry, Beausire, Brébion,
les plattes bandes, comme on voit à quelques
Chevotet, Contant, Deluzy, Franque, Hupeau,
fenestres du vieux Louvre.
Lecarpentier, Leroy, de Lespée, Perronet, N.-
On s’est entretenu à cette occasion sur la M. Potain, Rousset, Souﬄot, Tanevot, Cacoupe des claveaux, dont la Compagnie par- mus.
lera plus amplement après y avoir réﬂéchi.
Ont signé : De La Hire, Boﬀrand, Bruand, Citation 167. 25 janvier 1762, Vol. 7.
Bullet, Desgodetz, de La Hire ﬁls, de Lespine, L’Académie étant assamblée, M. Gabriel a
Félibien consulté la Compagnie sur diﬀérens desseins
d’armatures qu’il a présentés pour les platesCitation 164. 30 juin 1710, Vol. 3.
bandes des colonades de la place de Louis
M. Bullet a lu à la Compagnie un mémoire Quinze. Ces desseins et les modèles présentés
intitulé : Manière de faire les coupes des dans la conférence précédente ayant été exaplattes bandes pour les claveaux des portes et minés et la Compagnie ayant considéré que
croisées appliquée à une porte de douze pieds les plates bandes sur la face extérieure n’ont
de largeur. Ensuite M. de La Hire a aussy lu à que 13 pieds, d’un axe de colonne à l’autre,
la Compagnie un escrit intitulé : Règle géné- et sont butez par des pavillons de 11 toises
rale pour la division des voussoirs des grands de face, elle croit que ces plattes bandes pourarcs. Ces deux mémoires ont esté examinez et roient se passer de tirans pour le dessous et de
fort approuvez par la Compagnie. tout autre secours que leur coupe et leur butée.
Ont signé : n.c. Elle approuve cependant que, pour prévenir
tous les accidents qui peuvent être occasionVoir ﬁg. A.6 nez par l’inperfection des matériaux du pays
ou par les défauts de la taille et de la pose et
Citation 165. 22 décembre 1750, Vol. 6. autres accidens diﬃciles à prévoir, de suivre
Les plates bandes proposées par le sr Chopi- le dernier dessein de M. Gabriel, par lequel il
tel, à l’Académie ayant été examinées et les propose un tiran de fer au dessus de l’extrados
commissaires en ayant fait leur rapport, la de l’architrave, accroché des deux bouts dans
Compagnie a été d’avis que ces plates bandes les ancres des colonnes, et deux crampons de

342

<!-- p. 344 -->

Annexe A. Sources bibliographiques

fer placez dans les joints des contre clefs et l’Académie une coupe et une élévation qui déaccrochez au susdit tirant montroient la construction singulière du por-
Elle approuve aussi que l’on employe des tail de Saint Pierre de Genève ; la Compagoujons dans les joints des autres clavaux ; gnie les avoit examinez avec intérest et lui
elle approuve pareillement les tirans de fer avoit demandé de lui procurer de plus grands
d’une seule pièce sous les plattes bandes de éclaircissemens sur la fonction des diﬀérents
traverse de la colonnade, comme il a été pra- tirans de fer servant à maintenir les platte
tiqué à la chapelle de Versailles, estimant que bandes. En conséquence, M. Souﬂot a rapc’est dans le sens seulement de ces plattes porté les éclaircissemens désirez qu’on lui a
bandes que l’on doit craindre la poussée. envoyés de Genève ; ils ont été vus avec plai-
sir, et l’Académie a trouvé très ingénieux tous
Ont signé : Gabriel, Aubry, Beausire, Brébion,
les moyens dont M. le comte Alﬁeri, archiChevotet, Contant, Deluzy, Franque, Hupeau,
tecte de ce monument, a usé pour lui donner
Lecarpentier, Leroy, de Lespée, Perronet, N.-
de la solidité et de la légèreté. M. Souﬂot s’est
M. Potain, Rousset, Souﬄot, Tanevot, Ca-
engagé à en donner une copie à l’Académie.
mus.
Ont signé : Aubry, Brébion, Chalgrin, ChevoCitation 168. 19 juin 1769, Vol. 8. tet, Contant, Coustou, Desmaisons, Franque,
La Compagnie a ensuite entendu la lecture Lecarpentier, Leroy, de Lespée, Moreau, Perde plusieurs extraits du 1er et 2e registre de ronet, Peyre, N.-M. Potain, Régemorte, Rousl’Académie sur ce qui peut constituer le bon set, Souﬄot, de Wailly, J. Sedaine.
goust dans l’architecture et sur la proposi-
Citation 170. 17 janvier 1780, Vol. 9.tion de Philibert de Lorme de tailler les architraves par claveaux en forme de plattes L’Académie étant assemblée, elle a remerbandes. On s’est aussi entretenu des caria- cié M. Souﬄot des modèles en relief dont il a
tides et de l’usage de tailler des testes et fait présent à l’Académie, dont un est le promasques sur les claveaux des arcades. cédé qu’il a employé pour l’exécution des pla-
tebandes du grand portail de l’église de SainteOnt signé : Aubry, Blondel, Boullée, Bré-
Geneviève et l’autre un plafond en comparti-bion, Chevotet, Contant, Deluzy, Desmaisons,
ments et platebandes d’une ancienne exécu-Franque, Lecarpentier, Leroy, de Lespée, Les-
tion, au château de Madrid.trade, Moreau, Perronet, Peyre, N.-M. Potain, Rousset, Souﬄot, Trouard, de Wailly, Ont signé : Gabriel, Bellicard, Brébion, ChalSedaine. grin, Cherpitel, Coustou, Couture, Desmai-
sons, Franque, Gondoin, Hazon, Guillaumot,
Citation 169. 28 mai 1770, Vol. 8. Jardin, Le Roy, de Lespée, Mauduit, Moreau,
L’Académie étant assemblée, M. Souﬂot, à la Perronet, Peyre, Peyre le jeune, N.-M. Potain,
séance du 29e janvier 1770, avoit présenté à Roussel, Souﬄot, M.-J. Sedaine, de Wailly

343

<!-- p. 345 -->

Annexe B

Catalogue des plates-bandes et
voûtes plates

Sommaire
B.1 Plates-bandes dans l’Antiquité . . . . . . . . . . . . . . . . . . . . 345
B.2 Plates-bandes au Moyen Âge . . . . . . . . . . . . . . . . . . . . . 352
B.2.1 Plates-bandes de portail . . . . . . . . . . . . . . . . . . . 352
B.2.2 Plates-bandes de cheminée . . . . . . . . . . . . . . . . . . 359
B.2.3 Plates-bandes de baie . . . . . . . . . . . . . . . . . . . . . 365
B.3 Plates-bandes à l’Époque Moderne . . . . . . . . . . . . . . . . . . 368
B.3.1 Plates-bandes d’entablement . . . . . . . . . . . . . . . . . 368
B.3.2 Plates-bandes d’escalier . . . . . . . . . . . . . . . . . . . 370
B.4 Plates-bandes à joints en X . . . . . . . . . . . . . . . . . . . . . . 371
B.5 Plates-bandes en fausse-coupe . . . . . . . . . . . . . . . . . . . . 373
B.5.1 Jacques Lemercier . . . . . . . . . . . . . . . . . . . . . . 373
B.5.2 Le Louvre . . . . . . . . . . . . . . . . . . . . . . . . . . . 380
B.5.3 Le dix-septième siècle . . . . . . . . . . . . . . . . . . . . 391
B.5.4 Le dix-huitième siècle . . . . . . . . . . . . . . . . . . . . . 398
B.5.5 Chambéry . . . . . . . . . . . . . . . . . . . . . . . . . . . 406
B.6 Voûtes plates . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 411

344

<!-- p. 346 -->

Annexe B. Catalogue

B.1 Plates-bandes dans l’Antiquité

Fig B.1 – Kydna (Turquie)

Vers 250 av. J.-C.

Plate-bande composée de trois claveaux, et sou- —
lageant le linteau monolithe d’une porte, dans la
citadelle de Kydna (Lycie, actuelle Turquie).

Source : Adam (2012, p. 69).

Fig B.2 – Lac d’Albano, Latium (Italie)

Après le ive s. av. J.-C.

Plate-bande composée de sept claveaux, dans
l’émissaire du lac Albano « de la première
époque » (Rondelet, 1834, p. 114). L’émissaire
désigne un déchargeoir, et la plate-bande couvre
donc probablement une porte dans un tun-
nel. Le premier tunnel aurait été construit en
395 av. J.-C., mais cette plate-bande ne corres-
pond pas nécessairement à la date de première
construction.

Source ﬁgure : Rondelet (1804, Pl. XXIX) –
ici Rondelet (1828, Pl. XXX).
Voir également Fig. 2 sur ﬁg. 9.4 page 173.

Fig B.3 – Rome (Italie), Colisée

70-80 ap. J.-C.

Plate-bande composée d’un claveau unique, les
sommiers formant encorbellement, construite
dans le sous-sol du Colisée à Rome.

Sources : Durm (1885); Cejka (1978).

Source ﬁgure : Durm (1885, ﬁg. 116).

Fig B.4 – Pompéi (Italie), forum

Avant 79 ap. J.-C.

Plate-bande composée d’un claveau unique,
construite au forum de Pompéi.

Sources : Durm (1885); Cejka (1978).

Source ﬁgure : Durm (1885, ﬁg. 117).

345

<!-- p. 347 -->

Annexe B. Catalogue

Fig B.5 – Rome (Italie), Tullianum

iie s. av. J.-C.

Selon Choisy, la prison de Mamertine, ou Tullia-
num, aurait été construite par les étrusques, et
présenterait un « plafond clavé » (Choisy, 1873,
p. 125 ; 1899a, p. 247, 514). —
Fournet (2011) date au contraire la construction
du iie siècle av. J.-C., et donne des détails com-
plémentaires sur la construction. La voûte a une
portée de près de 7 m, et est bien contrebutée car
la salle est en grande partie enterrée. Les claveaux
ne présentent pas de crossettes, et sont posés sans
mortier.

Fig B.6 – Rome (Italie), temple
de Junon

Après le iie s. av. J.-C

« Temple de Junon, dans le portique d’Octavie »
à Rome (Rondelet, 1834, p. 115). Le temple est
construit au iie siècle avant J.-C et a fait l’ob-
jet de plusieurs reconstructions, la dernière au
iiie siècle ap. J.-C.

Source ﬁgure : Rondelet (1804, Pl. XXIX) –
ici Rondelet (1828, Pl. XXX).
Voir également Fig. 5 sur ﬁg. 9.4 page 173.

Fig B.7 – Via Appia (Italie)

Seconde moitié du ier s. av. J.-C.

Plate-bande d’une porte du tombeau de Cecilia
Metella, dont « les claveaux sont à double coupe »
(Rondelet, 1834, p. 116). Ce tombeau située le
long de la via Appia, a été construit dans la se-
conde moitié du ier siècle av. J.-C.

Source ﬁgure : Rondelet (1804, Pl. XXIX) –
ici Rondelet (1828, Pl. XXX).
Voir également ﬁg. 6.37 page 124 et Fig. 8 sur
ﬁg. 9.4 page 173.

Fig B.8 – Rome (Italie), Tabularium

76 av. J.-C.

Plusieurs plates-bandes construites en 76
—
av. J.-C. au Tabularium de Rome. La plate-
bande qui couvre la niche Sud-Est a 5,18 m de
portée.

Sources : DeLaine (1990); Acocella (2004).

346

<!-- p. 348 -->

Annexe B. Catalogue

Fig B.9 – Rome (Italie), forum de César

Entre ier s. av. J.-C. et iiie s. ap. J.-C.

Nombreuses plates-bandes composées de sept cla-
veaux, non chargées car situées sous un arc en
— plein cintre sans remplissage entre l’arasement de
la plate-bande et l’intrados de l’arc. Le forum de
César dont la construction débute en 51 av. J.-C.
est plusieurs fois endommagé par des incendies
puis restauré.
Mentionné par Acocella (2004).

Fig B.10 – Rome (Italie),
théâtre de Marcellus

Époque d’Auguste

Plate-bande à tenon du théâtre de Marcellus à
Rome (Rondelet, 1834, p. 115). Les tenons sont
également utilisés pour les voussoirs d’arcs an-
tiques, à Rome. Rondelet (1804, p. 100, cit. 73),
Choisy (1873, p. 127) et Planat (1888d, p. 486).

Source ﬁgure : Rondelet (1804, Pl. XXIX) –
ici Rondelet (1828, Pl. XXX).
Voir également Fig. 7 sur ﬁg. 9.4.

347

<!-- p. 349 -->

Annexe B. Catalogue

Fig B.11 – Vérone (Italie), amphithéâtre

Époque d’Auguste

Plates-bandes de l’amphithéâtre de Vérone,
construites sous le règne d’Auguste. Trois types
de plates-bandes sont présentes à Vérone. Choisy
(1873, p. 133-134) mentionne et reproduit seule-
ment celles correspondant aux portes basses de
l’amphithéâtre, composées de deux très grands
sommiers posés en encorbellement, et d’une pe-
tite clé (photo en haut ci-contre – la photo
est déformée par l’assemblage de plusieurs pho-
tos pour couvrir l’ensemble de la plate-bande).
Choisy souligne que ces plates-bandes pouvaient
être construites sans plate-forme d’appui, et que
les clés étaient mises en place sans être retaillées,
ce qui a conduit à des imprécisions sur leur posi-
tion (voir ﬁgure ci-dessous du même auteur).

Source ﬁgures à g. : Choisy (1873).

Source ﬁgures à d. : Durm (1885, ﬁg. 116 et 188).

348

<!-- p. 350 -->

Annexe B. Catalogue

Fig B.12 – Orange, théâtre

Époque d’Auguste

Plate-bande de 4,86 m de portée du théâtre
d’Orange, construit à l’époque d’Auguste
(Choisy, 1873, p. 135 ; Conti et al., 2012, p. 79).
La plate-bande est constituée de neuf claveaux
à crossettes.

Source ﬁgure en h. : Choisy (1873).

Source ﬁgure en b. : Durm (1885, ﬁg. 118).

Fig B.13 – Carceres de Domitien

Fin du ier s. ap. J.-C.

« Carceres construites du temps de Domitien »,
où l’appareil de la plate-bande est souligné par
l’usage du bossage pour les claveaux (Rondelet,
1834, p. 115). Les carceres désignent les stalles de
départ dans un cirque.

Source ﬁgure : Rondelet (1804, Pl. XXIX) –
ici Rondelet (1828, Pl. XXX).
Voir également Fig. 6 sur ﬁg. 9.4 page 173.

Fig B.14 – Taposiris Magna (Égypte)

Entre ﬁn du iie s. av. J.-C. et ﬁn du ier
s. ap. J.-C.
—
Voûte plate composée de neuf claveaux à cros-
settes, couvrant un espace de 1,80 × 1,50 m et
ayant une épaisseur de 40 cm environ (Fournet,
2011).

349

<!-- p. 351 -->

Annexe B. Catalogue

Fig B.15 – Baalbek (Liban),
temple de Bacchus

iie s. ap. J.-C.

Porte du « temple de Bacchus » à Baalbek appelé
« temple de Jupiter » par Rondelet (1834, p. 114-
\115) et « temple du soleil » par Planat (1888d).
Le temple est construit au iie siècle ap. J.-C. Sa
plate-bande est composée de trois claveaux, et
couvre un espace de 7,50 m de portée, ce qui
constitue un record pour une plate-bande de ce
type (Adam, 2012). Le caractère monumental
de cette plate-bande apparaît clairement sur la
planche XXIX de Rondelet (ﬁg. 9.4), où divers
exemples de plates-bandes antiques sont repré-
sentées à la même échelle, et où la plate-bande
de Baalbek se distingue nettement des autres.

Source ﬁgure : Rondelet (1804, Pl. XXIX) –
ici Rondelet (1828, Pl. XXX).
Voir également ﬁg. 9.5 et Fig. 4 sur ﬁg. 9.4.

Fig B.16 – Split (Croatie),
palais de Dioclétien

Fin du iiie s. ap. J.-C.

Plate-bande à crossettes, ou peut-être à
deux rangs de claveaux, du « palais de Dioclé-
tien à Spalatro » (Split actuellement, Croatie)
(Rondelet, 1834, p. 116).

Source ﬁgure : Rondelet (1804, Pl. XXIX) –
ici Rondelet (1828, Pl. XXX).
Voir également Fig. 9 sur ﬁg. 9.4 page 173.

Fig B.17 – Sbeïtla (Tunisie)

Plate-bande composée de cinq claveaux au péri- —
bole du capitole de Sbeïtla (Tunisie), mentionnée
par Adam (1989, p. 186).

350

<!-- p. 352 -->

Annexe B. Catalogue

Fig B.18 – Palmyre (Syrie)

Tombeau d’Iamblichus à Palmyre, en Syrie (Ron-
delet, 1834, p. 114).

Source ﬁgure : Rondelet (1804, Pl. XXIX) –
ici Rondelet (1828, Pl. XXX).
Voir également Fig. 3 sur ﬁg. 9.4 page 173.

Fig B.19 – Ferenti (Italie), théâtre

Plate-bande du théâtre de Ferenti, à proximité
de Viterbo.

Source ﬁgure : Durm (1885, ﬁg. 116).
Voir également ﬁg. 9.6.

351

<!-- p. 353 -->

Annexe B. Catalogue

B.2 Plates-bandes au Moyen Âge

B.2.1 Plates-bandes de portail

Fig B.20 – Voisinlieu (Oise),
maladerie Saint-Lazare

xiie-xiiie s.

Plate-bande à crossettes du portail sud de
l’église de la maladerie Saint-Lazare à Voisinlieu
dans l’Oise. Cette plate-bande est composée de
cinq claveaux, les deux contre-clés semblant être
dans une pierre diﬀérente des autres claveaux.

Source : Base Mérimée PA00114515, Reveyron
(1993).

Source photos : Lucien Bégule (Base Mé-
moire 51L02355B) et Thierry Prat 1965 (Base
Mémoire MH0269416). Les deux photos n’ont pas
été prises à la même date.

352

<!-- p. 354 -->

Annexe B. Catalogue

Fig B.21 – Bourges (Cher),
porte Saint-Ours

xie-xiie s.

Plate-bande à joints inclinés de la porte Saint-
Ours, provenant de la collégiale Saint-Ursin.
Plate-bande composée de sept claveaux, avec clé
passante (le sommet de la clé dépasse de la ligne
d’arasement de la plate-bande). Les sommiers
sont posés avec un encorbellement marqué.

Source : Base Mérimée PA00096737, Reveyron
(1993).

Source photo : Antoine Garnier, Atlas Roman,
http://atlas-roman.blogspot.fr.

Fig B.22 – Simiane-la-Rotonde (Alpes-
de-Haute-Provence),
château

Plate-bande à joint courbe de la rotonde romane
tardive au château de Simiane (Basses-Alpes).
Une seconde plate-bande plus tardive probable-
ment est visible sur la façade nord au niveau de
l’angle avec escalier.

Source : Base Mérimée PA04000014, Reveyron
(1993).

Source photos : Odile de Pierrefeu 1996 (Base
Mémoire 02040197ZA, 02040239ZA).

353

<!-- p. 355 -->

Annexe B. Catalogue

Fig B.23 – Beauvais (Oise),
église Saint-Étienne

Plate-bande à joints courbes du portail latéral de
l’église Saint-Étienne à Beauvais.

Source : Base Mérimée PA00114508, Sanchini
(2013).

Source ﬁgure : Viollet-Le-Duc (1859b).

Source photo : Alfred-Nicolas Normand (Base
Mémoire NRM00293).

Fig B.24 – Picardie

Plates-bandes à joints courbes de Picardie men-
tionnés par Camille Enlart à propos de l’archi- —
tecture romane : « Presles (Aisne), Villers-Saint-
Paul (Oise), Berteaucourt (Somme), etc. » (En-
lart, 1927, p. 322-323, cit. 118).

Fig B.25 – Boursonne (Oise), église

Plate-bande à joints inclinés, sous le tympan du
portail de l’église de Boursonne, dans l’Oise.

Source : Base Mérimée PA00114544.

Source photo : Antoine Garnier, Atlas Roman,
http://atlas-roman.blogspot.fr.

354

<!-- p. 356 -->

Annexe B. Catalogue

Fig B.26 – Autheuil-en-Valois (Oise),
église

Plate-bande composée de claveaux inégaux
taillés avec crossettes, sous le tympan du por-
tail de l’église de l’ancien prieuré Notre-Dame à
Autheuil-en-Valois, dans l’Oise.

Source photo : Antoine Garnier, Atlas Roman,
http://atlas-roman.blogspot.fr.

Fig B.27 – Rhuis (Oise),
église Saint-Gervais-et-Protais

Plate-bande composée de deux grands sommiers
et d’une petite clé, sous le tympan du portail
de l’église Saint-Gervais-et-Protais à Rhuis, dans
l’Oise.

Source : Base Mérimée PA00114837.

Source photo : Antoine Garnier, Atlas Roman,
http://atlas-roman.blogspot.fr.

Fig B.28 – Presles-et-Thierny (Aisne),
église Saint-Georges-et-Saint-Quirin

Fin xiie s.

Plate-bande à joints courbes de l’église Saint-
Georges-et-Saint-Quirin de Presles-et-Thierny
dans l’Aisne, mentionnée par Enlart (Enlart,
1927, p. 322-323, cit. 118). Église classée MH.

Source : Base Mérimée PA00115878.

Source photo : Aimée Neury 1963 (Base Mé-
moire MH0266840).

355

<!-- p. 357 -->

Annexe B. Catalogue

Fig B.29 – Villers-Saint-Paul (Oise)

Plate-bande à joints courbes de l’église Saint-
Pierre-Saint-Paul de Villers-Saint-Paul dans
l’Oise, mentionnée par Enlart (Enlart, 1927,
p. 322-323, cit. 118). Église classée MH par liste
de 1862.

Source : Base Mérimée PA00114961.

Source photo : Eugène Lefèvre-Pontalis (Base
Mémoire lp007832).

Fig B.30 –
Berteaucourt-les-Dames (Somme), église

Plate-bande à joints courbes de l’église de l’an-
cienne abbaye Sainte-Marie de Berteaucourt-les-
Dames dans la Somme, mentionnée par Enlart
(Enlart, 1927, p. 322-323, cit. 118). L’église a été
classée Monuments Historiques par liste de 1840.
Elle a été endommagée pendant la Première
Guerre mondiale, la plate-bande a peut-être été
détruite.

Nous n’avons pas retrouvé de représentation de
la plate-bande à joint courbe. Il existe un dessin
d’une plate-bande à crossettes correspondant au
portail latéral.

Source : Base Mérimée PA00116098.

Source ﬁgure : Base Mémoire MH0192952.

Fig B.31 – Cerseuil (Aisne), église

Plate-bande prenant toute la hauteur du tympan, —
à l’église de Cerseuil.

Source : Base Mérimée PA00115576.

Fig B.32 – Le Mans (Sarthe), cathédrale

Plate-bande composée de treize claveaux à joints
inclinés au portail de la cathédrale du Mans.

Source photo : Antoine Garnier, Atlas Roman,
http://atlas-roman.blogspot.fr.

356

<!-- p. 358 -->

Annexe B. Catalogue

Fig B.33 – Villeneuve-Renneville-
Chevigny (Marne),
église Saint-Memmie

Deux plates-bandes à joints courbes, une sur le
portail occidental, et une sur le portail latéral de
l’église Saint-Memmie, dans la Marne. Une des
deux plates-bandes est surmontée d’une plate-
bande à joints inclinées.

Source : Base Mérimée PA00078899.

Source photo : Antoine Garnier, Atlas Roman,
http://atlas-roman.blogspot.fr.

Fig B.34 – La Celle (Cher), église

Plate-bande à joints inclinés. Bien que cette
plate-bande appartienne à un édiﬁce du Moyen
Âge, la raideur de la taille de la plate-bande pour-
rait indiquer une reconstruction de cet élément
au xixe siècle.

Source : échange oral avec Nicolas Reveyron.

Source photo : Antoine Garnier, Atlas Roman,
http://atlas-roman.blogspot.fr.

357

<!-- p. 359 -->

Annexe B. Catalogue

Fig B.35 – La Ferté-Milon (Aisne),
église Notre-Dame

Plate-bande à joints inclinés au portail de l’église
Notre-Dame de la Ferté Milon. La niche semble
avoir été creusé après la construction et le cul-
de-lampe ajouté pour porter une statue. La clé,
ou la plate-bande entière, a donc pu être rap-
portée en remplacement d’un linteau monolithe.
La rapport portée sur hauteur L/h est supé-
rieur à 6, c’est-à-dire supérieur aux rapports ha-
bituellement obervés pour les autres exemples du
Moyen Âge, compris entre 2,5 et 4,5 environ. Il
pourrait donc s’agir d’une plate-bande mise en
place pour remplacer un linteau.

Source : Base Mérimée PA00115674, échange oral
avec Nicolas Reveyron.

Source photo : Frank Genestoux (Base Mé-
moire 80L020205).

358

<!-- p. 360 -->

Annexe B. Catalogue

B.2.2 Plates-bandes de cheminée

Fig B.36 – Beaune, hospices civils

1443-1457

Deux plate-bandes à crossettes formant le man-
teaux portant la hotte de la cheminée, dans la
cuisine des hospices civils de Beaune (1443-1457).
Chaque plate-bande est composée de trois cla-
veaux à crossettes. Le manteau de la cheminée
est supporté au centre sur une console (d’où la
présence de deux plates-bandes pour une chemi-
née unique).

Source photo : Félix Martin-Sabon, avant 1920,
(Base Mémoire MH056551).

359

<!-- p. 361 -->

Annexe B. Catalogue

Fig B.37 – Dijon, palais des Ducs

1439-1450

Plates-bandes de la cheminée, dans la cuisine
du palais des Ducs de Bourgogne à Dijon. Les
plates-bandes dessinées par Viollet-le-Duc sont
des plates-bandes composées de trois claveaux,
où la présence ou non de crossette est diﬃcile-
ment visible. La plate-bande photographiée est
une plate-bande composée de cinq claveaux, avec
crossettes.

Source dessins : d’après la coupe de la cuisine du
palais des Ducs de Viollet-Le-Duc (1860b).

Source photo : Hélène Adant 1947 (Base Mé-
moire MH0191921).

Fig B.38 – Dijon, palais des Ducs

1504

Plate-bande de la salle des gardes du palais des
Ducs de Bourgogne à Dijon, construite en 1504
selon la notice de la photo jointe.

Source photo : Hélène Adant 1947 (Base Mé-
moire MH0191927).

360

<!-- p. 362 -->

Annexe B. Catalogue

Fig B.39 – Dijon, palais des Ducs

xve-xvie s. (hyp.)

Plate-bande de la salle Grangier dans la tour
de Bar du palais des Ducs de Bourgogne à Di-
jon. Plate-bande composée de trois claveaux avec
crossettes.

Source photo : Hélène Adant 1947 (Base Mé-
moire MH0191922).

Fig B.40 – Beaune,
hôtel des Ducs de Bourgogne

xve-xvie s. (hyp.)

Bechmann mentionne la longue plate-bande de
4,30 m de portée pour la « Grande cheminée de la —
cuisine des Ducs de Bourgogne à Beaune », pro-
bablement tirée d’un recueil de croquis de Albert
Laprade (Bechmann, 1993, p. 200). Plate-bande
composée de neuf claveaux sur le croquis repro-
duit par Bechmann, avec une clé au centre plus
large que les claveaux courants.

Fig B.41 – Paris, Palais de Justice

Fin xiiie ou début xive s.

Plate-bande à crossette dans les cuisines du pa-
lais de justice de Paris. Quatre cheminées de ce
type existaient dans les cuisines, disposées dans
chaque angle de la pièce. Viollet-le-duc date ces
cheminée de la ﬁn du xiiie siècle ou du début du
xive siècle (Viollet-Le-Duc, 1860b, cit. 87).

Source ﬁgure : Viollet-Le-Duc (1860b).

361

<!-- p. 363 -->

Annexe B. Catalogue

Fig B.42 – Vincennes, château, donjon

xive s.

Plate-bande à crossettes du xive siècle, pour la
cheminée de l’appartement royal au deuxième
étage du donjon du château de Vincennes,
construit dans les années 1360 (Mesqui, 1988,
p. 340). Il existe d’autres plates-bandes du même
type dans ce donjon.

Fig B.43 – Paris, Palais de Justice

xive s.

Plate-bande à crossettes du xive s. pour la Che-
minée du palais de justice de Paris. La projection
dans le plan horizontal de la plate-bande forme
un angle obtus (ﬁgure en bas ci-contre).

Source ﬁgure : Raguenet (1915b).

Fig B.44 – Mortain, abbaye

Plate-bande à crossettes de la cheminée de l’ab-
baye de Mortain, composée uniquement d’une
petite clef et de deux grandes contre-clefs.

Source ﬁgure : Viollet-Le-Duc (1859a).

Fig B.45 – La Rochette-des-Clouseaux

xvie s.

Linteau à crossettes du xvie s.), d’une cheminée
à la Rochette-des-Clouseaux (Vendée).

Source ﬁgure : Raguenet (1915b).

362

<!-- p. 364 -->

Annexe B. Catalogue

Fig B.46 – Cashel (Irlande), château

Plate-bande à lits doublement brisés, d’une che-
minée du château de Cashel (Irlande).
Cette plate-bande pourrait dater du xiiie s. si elle
est contemporaine de la date de construction du
château.

Source ﬁgure : Raguenet (1915b).

Fig B.47 – Bourges, Petit collège

xve s.

Plate-bande à joints verticaux (ou faiblement
inclinés) de la cheminée monumentale du xve,
grande salle du Petit Collège à Bourges.

Source ﬁgure : Raguenet (1915b).

Fig B.48 – Puy-en-Velay, cathédrale

La cheminée du logis des clergerons de la ca-
thédrale du Puy en Velay, comporte une plate-
bande courbe à deux claveaux soutenus par des
consoles.

Source ﬁgure : Viollet-Le-Duc (1859a).

363

<!-- p. 365 -->

Annexe B. Catalogue

Fig B.49 – Septmonts, château

Vers 1360

Plate-bande à joints courbes, de la cheminée si-
tuée au troisième étage du donjon construit dans
les années 1360, à Septmonts (Mesqui, 1988,
p. 302, 307).

Source photo : Mesqui (1988, p. 307).

Fig B.50 – Vez, château

Plate-bande à joints verticaux (ou faiblement in-
clinés) de la cheminée du château de Vez.

Source photo : Mesqui (1988, p. 319).

Fig B.51 – Longpont, abbaye

Plate-bande à doubles crossettes, surmontée d’un
arc de décharge, pour la cheminée de l’abbaye
de Longpont située au centre de la pièce. Le
manteau de la cheminée est composé de quatre
plates-bandes reposant sur quatre colonnes. Ces
colonnes servent également d’appui aux voûtes
d’ogives qui couvrent la pièce. Les plates-bandes
sont beaucoup plus hautes que larges (non visible
sur la photo ci-contre).

Mentionné par Reveyron (1993), Bechmann
(1993) et Conan (2015), et utilisé comme illus-
tration du système des doubles crossettes par Pé-
rouse de Montclos (2007).

Source photo : Frank Genestoux (Base Mé-
moire 80L017306).

Fig B.52 – Mont Saint-Michel,
salle des hôtes

xiie-xiiie s. —

Deux plates-bandes à crossettes pour la cheminée
de la salle des hôtes du Mont-Saint-Michel, datée
du xiie-xiiie siècle selon Reveyron (1993).

364

<!-- p. 366 -->

Annexe B. Catalogue

B.2.3 Plates-bandes de baie

Fig B.53 – Vauclair, abbaye

xiiie s.

Abbaye de Vauclair, fortement endommagée lors
de la guerre de 1914-1918. Plusieurs plates-
bandes couvraient les baies du bâtiment des
convers, également appelé dortoir ou grenier sui-
vant les sources. Plate-bande du bâtiment des
convers mentionnée par Bechmann (1993, p. 200)
et Reveyron (1993).
Classé Monuments Historiques (Base Méri-
mée PA00115546).

Source photos : Eugène Lefèvre-Pontalis (Base
Mémoire LP000978) ; Camille Enlart (Base Mé-
moire MH0028143).

Fig B.54 – Coucy, château,
salle des Preux

Fin xive s.

Plates-bandes de 4 m de portée de la salle des
Preux au château de Coucy. Ces plates-bandes
sont en réalité de véritables voûtes plates, en rai-
son de l’épaisseur de la courtine dans laquelle
sont percées les baies, de 4 m également. La salle
des Preux du château de Coucy, construit par
Enguerrand VII à la ﬁn du xive siècle (travaux
terminées en 1386), est néanmoins un ouvrage
exceptionnel : longue de près de 60 m et large de
15 m (Mesqui, 1988, p. 135, 156).

Ces plates-bandes sont mentionnées et dessi-
nées par Viollet-le-Duc (Viollet-Le-Duc, 1860a,
cit. 90), mentionnées par Reveyron (1993).

Source photos : Mesqui (1988, p. 156-157).
Voir également ﬁg. B.56.

Fig B.55 – Haut-Kœnigsbourg, château

xve s.

Plate-bande supportant le plancher. La plate-
bande est composée d’un seul claveau central,
Voir ﬁgures B.57 à B.61 page 367
appareillé à crossette. Le système a été renforcé
au xvie siècle par la mise en place d’arcs sous
les plates-bandes. Exemple mentionné par Viollet-
Le-Duc (1860a, cit. 91), Reveyron (1993), et Bech-
mann (1993, p. 201).

(1). Sources ﬁgures : https://fr.wikisource.org/wiki/Fichier:Salle.des.Preux.chateau.
Coucy.png et https://fr.wikisource.org/wiki/Fichier:Coupe.Salle.des.Preux.chateau.

365

<!-- p. 367 -->

Annexe B. Catalogue

Fig B.56 – Plate-bande de la salle des Preux au Château de Coucy,
d’après (1) Viollet-Le-Duc (1860a)

Coucy.png

366

<!-- p. 368 -->

Annexe B. Catalogue

Fig B.57 – Château du Fig B.58 – Château du
Haut-Kœnigsbourg, Haut-Kœnigsbourg,
d’après Viollet-Le-Duc (1860a) d’après Viollet-Le-Duc (1860a)

Fig B.59 – Château du Fig B.60 – Château du
Haut-Kœnigsbourg, Haut-Kœnigsbourg,
d’après Viollet-Le-Duc (1860a) d’après Viollet-Le-Duc (1860a)

Fig B.61 – Château du Haut-Kœnigsbourg, d’après Viollet-Le-Duc (1860a)

367

<!-- p. 369 -->

Annexe B. Catalogue

B.3 Plates-bandes à l’Époque Moderne

B.3.1 Plates-bandes d’entablement

Fig B.62 – Paris,
église Saint-Gervais-Saint-Protais

1616-1621

Plate-bande composée de dix-sept claveaux à
joints inclinés et lits brisés, au fronton de
l’église Saint-Gervais-Saint-Protais, par Salomon
de Brosse (1616-1621). Une rainure remplie au
mortier couleur pierre, correspondant probable-
ment à la présence d’un tirant d’intrados, est vi-
sible sur le soﬃte.

Fig B.63 – Paris, église du Val-de-Grâce

1644-1669

Plate-bande composée de onze joints inclinés et
lits brisés. Fronton de l’église du Val-de-Grâce,
construite par François Mansart puis Le Muet
(1644-1669). Une rainure remplie au mortier cou-
leur pierre, correspondant probablement à la pré-
sence d’un tirant d’intrados, est visible sur le sof-
ﬁte.

368

<!-- p. 370 -->

Annexe B. Catalogue

Fig B.64 – Paris,
collège des Quatre-Nations

1662-1688

Plate-bande composée de neuf claveaux à joints
inclinés et lits brisés, au fronton de la chapelle
du collège des Quatre-Nations, par Louis Le Vau
(1662-1688). Une rainure remplie au mortier cou-
leur pierre, correspondant probablement à la pré-
sence d’un tirant d’intrados, est visible sur le sof-
ﬁte.

Fig B.65 – Paris, Louvre

1668-1670

Plates-bandes de la grande colonnade du
Voir ﬁg. 6.41
Louvre, par Claude Perrault, Louis Le Vau et
Charles Le Brun, construite de 1668 à 1670. Ces
plates-bandes sont composées de neuf claveaux à
joints inclinés et lits brisés.

Fig B.66 – Paris, place de la Concorde

1758

Plates-bandes de la place Louis XV (actuellement
place de la Concorde), pour l’hôtel de La Ma- Voir ﬁg. 6.42
rine et l’hôtel Crillon, par Ange-Jacques Gabriel.
Voir Patte (1769, Pl. XIV). Ces plates-bandes sont
composées de onze claveaux à joints inclinés et lits
brisés. Deux rangs de claveaux.

369

<!-- p. 371 -->

Annexe B. Catalogue

B.3.2 Plates-bandes d’escalier

Fig B.67 – Avignon, hôtel Raoulx

1696
—
Escalier à jour de l’hôtel Raoulx 35 rue Bonnete-
rie à Avignon (1696), avec plate-bande à crossette
pour le limon et le palier (Diot, 2011, p. 164).

Fig B.68 – Dijon, abbaye Sainte-Bénigne

1653

Escalier « suspendu sur arc » de l’abbaye Sainte- —
Bénigne 5 rue Docteur-Maret à Dijon (1653), avec
plate-bande à crossette pour le limon. Les cla-
veaux sont si longs que certaines volées sont por-
tées par un seul claveau (Diot, 2011, p. 211).

Fig B.69 – Avignon, hôtel Salvador

1704-1713

Escalier « suspendu sur plate-bande » de l’hô- —
tel de Salvador 19 rue du roi-René à Avignon
(1704-1713) où le claveau de la plate-bande et
la marche sont pris dans une même pierre (Diot,
2011, p. 228).

Fig B.70 – Aubenas,
maison Michel-Veyrenc

Vers 1740
— Escalier « suspendu marche sur marche avec li-
mon porteur », de la maison Michel-Veyrenc
8 rue Jourdan à Aubenas (vers 1740), dont les
plates-bandes sans crossettes ont des joints per-
pendiculaire au limon, (Diot, 2011, p. 238).

370

<!-- p. 372 -->

Annexe B. Catalogue

B.4 Plates-bandes à joints en X

Fig B.71 – Arezzo, Toscane (Italie),
cathédrale San Donato

Après 1277, avant 1337

Le portail latéral, sur la façade sud de la cathé-
drale San Donato de Arezzo, présente une plate-
bande à joints en X. Le portail latéral a été ter-
miné avant 1337, et est nécessairement postérieur
aux travaux de reconstruction de la cathédrale
commencé en 1277.

Source dates : site du diocèse d’Arezzo,
http://www.diocesiarezzo.it/index.php?
option=com_content&view=article&id=256&
Itemid=248, consulté le 25/05/2017.

Source photo : Fabrizio Sciarretta, 2013,
« Arezzo - Duomo - Portale laterale »,
https://www.flickr.com/photos/128952155@
N02/20638434691/

Fig B.72 – Prato, Toscane (Italie),
cathédrale

1317-1368

Le portail de la porte sud du transept de la cathé-
drale de Prato présente une plate-bande à joints
en X. Les claveaux sont alternativement en pierre
blanche de Albarese, et en marbre vert de Prato
(Serpentino), selon un décor ablaq (Lampariello,
2012). La distance entre les piédroits mesure en-
viron 1,5 m.

Le transept aurait été construit par Giovanni Pi-
sano vers 1317-1368. Cette plate-bande est men-
tionnée par Ruskin (1849), et Lampariello (2012).

Source dates : http://www2.po-net.prato.
it/en/artestoria/citta/chiese/duomo/
pagina59.html, consulté le 25/05/2017.

Voir également dessin et gravure de cette plate-
bande : ﬁgures 7.2 et 6.12.

371

<!-- p. 373 -->

Annexe B. Catalogue

Fig B.73 – Alba Iulia (Roumanie),
cathédrale Saint-Michel

Après 1277

La plate-bande du portail de la cathédrale Saint-
Michel à Alba Iulia présente une plate-bande à
joints en X. Les grands fers de renforts ne sont
probablement pas d’origine. Le massif occiden-
tal a été reconstruit après les destructions liées à
des invasions en 1277. Marcu Istrate mentionne
la venue d’une équipe d’artisans de Saint-Dié :
« Johannes de Saint-Dié’s team of craftsmen was
brought in » (Marcu Istrate, 2008), ce qui pour-
rait correspondre à une équipe de maîtres maçons
venus de Saint-Dié dans les Vosges.

La plate-bande de Alba-Iulia en Roumanie est
mentionnée par Marcu Istrate (2008) et Motro
(2009).

Source photo : Márton Sarkadi.

Fig B.74 – Esztergom (Hongrie), château

Une plate-bande du château de Esztergom, située
dans un couloir entre le donjon et la chapelle,
présente des joints en X. La chapelle attenante
serait de la ﬁn du xiie siècle, mais la datation de
la plate-bande n’est pas connue avec exactitude.

L’existance de cette plate-bande et les informa-
tions la concernant nous ont été communiquées
par Márton Sarkadi.

Source photo : Márton Sarkadi.

Fig B.75 – Brateiu (Roumanie), église

Une plate-bande de l’église du village de Brateiu,
à proximité de Sibiu (Roumanie), présenterait des
—
joints en X. Nous n’avons pas pu obtenir de photo
de cette dernière.

Cette plate-bande nous a été signalée par Márton
Sarkadi.

372

<!-- p. 374 -->

Annexe B. Catalogue

B.5 Plates-bandes en fausse-coupe

B.5.1 Jacques Lemercier

Fig B.76 – Montceau-en-Brie, château,
aile Sud

1601-1622

Le château de Montceaux-en-Brie (actuellement
Montceaux-lès-Meaux), a connu trois grandes
phases de construction (Coope, 1959) :
— 1547-1559, pour Catherine de Médicis,
peut-être par De l’Orme ;
— 1597-1599 pour Henri IV et Ga-
brielle d’Estrées, peut-être par
Jacques II du Cerceau ;
— 1601-1622 pour Marie de Médicis, par
Salomon de Brosse.
Nicolas Lemercier, père de Jacques Lemercier,
a pris part à la fois à la deuxième phase de
construction avec Jacques II du Cerceau (1597-
\1599) et à la troisième avec Salomon de Brosse
(1601-1622). Coope (1959) souligne que la pré-
sence prolongée de Nicolas Lemercier sur le chan-
tier de Montceaux-en-Brie indique que son ﬁls
Jacques Lemercier pourrait avoir eu connaissance
du chantier.

Le château fut conﬁsqué en 1793, et était déjà
presque entièrement démoli en 1799. Les vestiges
du château sont classés aux Monuments Histo-
riques (Base Mérimée PA00087113).

Une plate-bande en fausse-coupe est située au
niveau de l’entrée dans l’aile Sud depuis la cour
du château. Cette partie du château daterait de
la troisième phase de construction par Salomon
de Brosse.

Source photos : Coope (1972).

373

<!-- p. 375 -->

Annexe B. Catalogue

Fig B.77 – Montceau-en-Brie, château,
corps de logis

1601-1622

Voir historique du château de Montceaux-en-Brie
(actuellement Montceaux-lès-Meaux) ci-dessus.

Une plate-bande en fausse-coupe est située au ni-
veau du corps de logis principal (ﬁg. B.77). Cette
partie du château daterait de la troisième phase
de construction par Salomon de Brosse.

Source photo : Coope (1972).

Fig B.78 – Paris,
église Saint-Joseph-des-Carmes

1613-1625

Plate-bande en fausse-coupe couvrant la porte
principale de la façade de l’église Saint-Joseph-
des-Carmes (1613-1625).

Le nom de l’architecte de l’église Saint-Joseph-
des-Carmes n’est pas connu avec certitude. Il
pourrait s’agir de Jacques Lemercier mais il
n’existe pas d’archives attestant cette attribu-
tion. La plate-bande semble être en pierre de
Saint-Leu (pierre utilisée à Paris pendant l’An-
cien Régime), et les piédroits en pierre de Chau-
vigny (mêmes carrières que pierre de Saint-Leu,
mais autre banc, qui donne une pierre plus grise,
utilisée au xixe siècle pour les restaurations). La
raideur de la taille des piédroits, diﬀérente de
celle de la plate-bande, est un autre indice en
faveur d’une restauration des piédroits, avec la
conservation en place de la plate-bande d’origine.
La plate-bande pourrait donc être d’origine, au
sein d’une façade restaurée en 1866.

Source : échange oral avec Alexandre Gady.

374

<!-- p. 376 -->

Annexe B. Catalogue

Fig B.79 – Richelieu, église Notre-Dame

1629

Plates-bandes en fausse-coupe couvrant la porte
principale et les deux portes latérales de la façade
de l’église Notre-Dame-de-l’Assomption à Riche-
lieu, qui aurait été édiﬁée par Pierre Lemercier
sur les plans de son frère, Jacques Lemercier, en
\1629.

Source photos : Base Mémoire MH0098112,
MH0335540 et MH0159254

Fig B.80 – Rueil-Malmaison,
église Saint-Pierre Saint-Paul

1632-1635

La façade de l’église Saint-Pierre Saint-Paul de
Rueil-Malmaison est construite de 1632 à 1635
par Jacques Lemercier sur l’ordre du cardinal de
Richelieu. La porte de la façade occidentale est
couverte par une plate-bande en fausse-coupe.
L’arrière de la plate-bande n’est pas visible, car
elle est masquée par le vestibule d’entrée.

« L’église est entièrement reconstruite par l’ar-
chitecte Eugène Lacroix pour Napoléon III qui
en ﬁt faire une restitution ﬁdèle » (Base Méri-
mée IA00064577).

375

<!-- p. 377 -->

Annexe B. Catalogue

Fig B.81 – Paris, chapelle de la Sorbonne

1635-1642

Plates-bandes en fausse-coupe couvrant les
portes principales de la façade sur rue et de la
façade sur cour de la chapelle de la Sorbonne.
La chapelle est construite de 1635 à 1642 par
Jacques Lemercier pour le cardinal de Richelieu.

376

<!-- p. 378 -->

Annexe B. Catalogue

Fig B.82 – Paris, Palais-Royal,
aile de Valois (1)

Années 1630

Le Palais-Royal (ancien palais Cardinal) est le ré-
sultat de constructions successives du xviie siècle
au xixe siècle, suite à des incendies (1763, 1781,
\1871) et agrandissements successifs. L’aile orien-
tale de la seconde cour (aile de Valois, don-
nant sur la cour des colonnes de Buren) a été
construite par Jacques Lemercier pour le cardi-
nal de Richelieu (années 1630), puis la façade
profondément modiﬁée par Pierre Contant d’Ivry
(1752). Ce dernier « a conservé les trophées des
trumeaux [les proues], mais remplacé les baies
cintrées du rez-de-chaussée et les fenêtres d’en-
tresol (sauf une au-dessus du passage ouvert par
ses soins vers la cour des communs [actuelle place
de Valois]) par de grandes fenêtres rectangulaires
Plate-bande de Lemercier (années 1630)
réunissant les deux niveaux ; à l’étage noble, il a
ouvert de nouvelles fenêtres à la place des niches
(d’où le resserrement exceptionnel des baies de
cet étage). Fontaine (1827) a ajouté le portique
dit “galerie des proues” » (Pérouse de Montclos,
1994, p. 382).

Les fenêtres du premier étage sont couvertes
de plates-bandes en fausse-coupe probablement
dues à Jacques Lemercier (années 1630). Ces
plates-bandes sont composées de cinq claveaux,
qui englobent le chambranle et la frise. Elles se
Plate-bande de Contant d’Ivry (1752) distinguent des autres plates-bandes ajoutées en
1752 par Pierre Contant d’Ivry, qui se composent
de seulement deux ou trois claveaux et qui pré-
sentent extérieurement également des joints ver-
ticaux, mais dont les claveaux ne semblent pas se
prolonger systématiquement dans la frise.

L’avant-corps oriental de la façade du corps
de logis sur la seconde cour, construit par
Contant d’Ivry en 1766, ne présente pas de
plates-bandes en fausse-coupe, ce qui semble
conﬁrmer l’hypothèse que les plates-bandes en
fausse-coupe soient dues à Lemercier, et que Plate-bande de Contant d’Ivry (1752)
Contant d’Ivry ait dû imiter le même système,
mais en diminuant le nombre de claveau et peut-
être en armant les plates-bandes, lorsqu’il doubla
le nombre de fenêtres de l’aile de Valois.

Voir également ﬁg. B.132 ci-dessous.

Source historique : Pérouse de Montclos (1994,
p. 380-382).

377

<!-- p. 379 -->

Annexe B. Catalogue

Fig B.83 – Paris, Palais-Royal,
aile de Valois (2)

Années 1630

L’avant-corps oriental de la façade du corps
de logis sur la seconde cour, construit par
Contant d’Ivry en 1766, ne présente pas de
plates-bandes en fausse-coupe. Les trois travées Avant-corps oriental de Contant d’Ivry (1766)
conservées de part et d’autre de cet avant-corps
(entouré en bleu ci-contre) correspondent à des
constructions de Jacques Lemercier, qui pro-
longent les fenêtres du premier étage de l’aile de
Valois. Les plates-bandes de la construction de
Lemercier sont en fausse-coupe.

Source historique : Pérouse de Montclos (1994,
p. 380-382). côté Est

côté Ouest

378

<!-- p. 380 -->

Annexe B. Catalogue

Fig B.84 – Paris, Palais-Royal,
6 rue de Valois

1636

Quatre plates-bandes en fausse-coupe couvrent
les fenêtres du premier étage (au-dessus d’un
entresol). Le 6 rue de Valois appartient aux
constructions de Jacques Lemercier pour le
Palais-Royal. Il ne correspond qu’à une partie
de ces constructions, le reste ayant été détruit
lors du percement de la rue de Valois qui sépara
cet immeuble du reste des bâtiments du Palais-
Royal.

Source : Gady (2005).

Fig B.85 – Louvre, cour Carrée,
pavillon de l’Horloge

1639-1642
—
Les plates-bandes en fausse-coupe du Louvre dues
à Jacques Lemercier (1639-1642) sont présen-
tées conjointement aux autres plates-bandes du
Louvre. Voir les ﬁgures B.86, B.87 et B.88.

379

<!-- p. 381 -->

Annexe B. Catalogue

B.5.2 Le Louvre

Fig B.86 – Louvre, cour Carrée,
pavillon de l’Horloge

1639-1642

Les portes latérales du pavillon de l’Horloge de la
cour Carrée sont couvertes par des plates-bandes
en fausse-coupe surmontées d’un œil de Bœuf.
Ces plates-bandes sont construites par Jacques
Lemercier entre 1639-1642. Jacques Curabelle,
détracteur de Desargues, et qualiﬁé par Sakaro-
vich de « meilleur appareilleur de son temps »,
participe au chantier. La construction avait dé-
buté en 1624-1626 sous la direction de Mété-
zeau, mais le chantier s’était arrêté pour des pro-
blèmes de ﬁnancement, à un niveau situé sous
les plates-bandes en fausse-coupe. Le chantier re-
prend en 1639 sous la direction de Lemercier,
qui est donc l’architecte à l’origine des premières
fausse-coupes connues au Louvre.

Chaque plate-bande comporte onze claveaux. Les
parties vertiales des joints sont visibles du côté
de la cour Carrée, tandis que les parties inclinées
à lits brisés sont visibles du côté du passage.

Source : échange oral avec Guillaume Fonkenell.

380

<!-- p. 382 -->

Annexe B. Catalogue

Fig B.87 – Louvre, cour Carrée,
aile Ouest

1639-1642

La construction du symétrique de l’aile de Les-
cot (1551-1556) par Lemercier a lieu également
entre 1639-1642 après la construction du pavillon
de l’Horloge. Il est diﬃcile de distinguer la co-
pie de l’original (comparaison photos ci-contre).
Cependant, les plates-bandes des trois portes du
rez-de-chaussée sont construites en fausse-coupe.

Les joints en fausse-coupe de ces plates-bandes
sont très ﬁns, contrairement aux joints des plates-
Plate-bande en fausse-coupe de Lemercier bandes des portes latérales du pavillon de l’Hor-
(1639-1642) loge construits peu avant (voir ci-dessus).

Plate-bande à joints inclinés de Lescot
(1551-1556)

Fig B.88 – Louvre, cour Carrée,
aile Ouest

1639-1642

Les plates-bandes des fenêtres du premier étage
de l’aile de Lemercier et du pavillon de l’Horloge
sont également en fausse-coupe.

Joints très ﬁns.

pavillon de l’Horloge

aile Lemercier

381

<!-- p. 383 -->

Annexe B. Catalogue

Fig B.89 – Louvre, cour Carrée, aile Sud

1654-1661

L’aile Sud de la cour Carrée est construite en
1654-1661 par Louis Le Vau, puis le bâtiment
est doublé en profondeur en 1666 du côte de la
Seine, faisant ainsi disparaître la façade de 1654-
1661 côté Seine. Les portes latérales du pavillon
central côté cour Carrée (1654-1661) sont cou-
vertes par des plates-bandes en fausse-coupe sur-
montées d’un œil de Bœuf, similaires à celles du
pavillon de l’Horloge. Elles ne comportent plus
que sept claveaux (au lieu de onze), et l’appareil
de la plate-bande et de l’œil de bœuf sont plus
nettement séparés.

Fig B.90 – Louvre, cour Carrée, aile Sud

1654-1661

Deux plates-bandes parallèles au passage entre
la Seine et la cour Carrée, placées dans l’axe des
trumeaux du corps principal, et portant la voûte
du passage.

Plates-bandes en fausse-coupe composées de
sept claveaux.

Fig B.91 – Louvre, cour Carrée, aile Sud

1654-1661 —

Les portes du rez-de-chaussée et les fenêtres du
premier étage sont en fausse-coupe.

Fig B.92 – Louvre, cour Carrée, aile Sud

1654-1661 ou 1666

Profonde plate-bande dans le passage entre la
Seine et la cour Carrée, à l’aplomb de l’an-
cienne façade intégré au corps du bâtiment lors
du doublement en profondeur de 1666. La plate-
bande est composée de neuf claveaux, avec des
pierres dures en parement et des pierres tendres
au centre.

382

<!-- p. 384 -->

Annexe B. Catalogue

Fig B.93 – Louvre, cour Carrée, aile Sud

1666

Sur la façade côté Seine de l’aile Sud, construite
en 1666 par Le Vau, seules les fenêtres du pre-
mier étage sont à plates-bandes. Les autres baies
sont en plein-cintre ou bombées. L’ensemble des
plates-bandes du premier étage sont construites
avec des plates-bandes en fausse-coupe.

La plate-bande axiale de l’avant-corps possède
neuf claveaux. Les autres fenêtres, moins larges,
possèdent cinq claveaux.

383

<!-- p. 385 -->

Annexe B. Catalogue

Fig B.94 – Louvre, cour Carrée, aile Sud

A l’intérieur du passage entre la Seine et la
cour Carrée, deux portes latérales côté Seine ont
été percées par Percier et Fontaine.

Plates-bandes en fausse-coupe composées de
sept claveaux.

Source : échange oral avec Guillaume Fonkenell.

384

<!-- p. 386 -->

Annexe B. Catalogue

Fig B.95 – Louvre, cour Carrée,
aile Nord

1663-1668

L’aile Nord de la cour Carrée du Louvre est
construite de 1663 à 1668 par Louis Le Vau. Les
portes latérales du pavillon central, côté cour,
sont comme à l’Ouest et au Sud couvertes en
fausse-coupe.

Chaque plate-bande comporte neuf claveaux. La
fausse-coupe est double, puique les parties ver-
ticales des joints sont visibles sur les deux cô-
tés de la plate-bande, la bonne coupe étant mas-
quée à l’intérieur de la plate-bande. Il s’agit du
seul cas de double fausse-coupe que nous avons
trouvé, mais il peut en exister d’autres parmi les
exemples de plates-bandes en fausse-coupe de ce
catalogue. En eﬀet, l’arrière de la plate-bande est
rarement visible.

Fig B.96 – Louvre, cour Carrée,
aile Nord

1663-1668

Système similaire pour la façade sur cour comme
pour aile Ouest et Sud : portes du rez-de-
chaussée et fenêtres du premier étage en fausse-
coupe.

385

<!-- p. 387 -->

Annexe B. Catalogue

Fig B.97 – Louvre, cour Carrée,
aile Nord

1663-1668

Système similaire pour la façade sur rue pour
l’aile Nord comme pour l’aile Sud : plates-
bandes uniquement au premier étage, et toutes
ces plates-bandes sont en fausse-coupe.

Fig B.98 – Louvre, cour Carrée,
aile Nord

1663-1668

A l’intérieur du passage entre la rue de Rivoli et
la cour Carrée, deux portes latérales côté cour
sont couvertes par une plate-bande en fausse-
coupe.

Plates-bandes en fausse-coupe composées de
sept claveaux.

386

<!-- p. 388 -->

Annexe B. Catalogue

Fig B.99 – Louvre, cour Carrée, aile Est

1668

L’aile Est est construite par Louis Le Vau à par-
tir de 1668, à l’exception de la grande colon-
nade qui fera l’objet d’un concours, et qui sera
construite par Claude Perrault, Louis Le Vau et
Charles Le Brun.

Plates-bandes en fausse-coupe comme pour les
autres ailes sur la façade sur cour : portes la-
térales du corps central, trois portes sur chaque
aile, et fenêtres du premier étage.

Fig B.100 – Louvre, cour Carrée, aile Est

1668

Dans le passage sous le pavillon central, les
deux portes latérales sont construites par Le Vau,
mais la décoration au dessus de l’entablement est
incrustée par Percier et Fontaine (date n.c.). La
photo ci-contre en bas montre la diﬃculté pour
restaurer ces plates-bandes, car les claveaux ne
peuvent pas être remplacés « en tiroir ». La res-
tauration ne peut être réalisée sans casser la par-
tie verticale des joints.

387

<!-- p. 389 -->

Annexe B. Catalogue

Fig B.101 – Louvre, cour Carrée, aile Est

1668-1670

Le corps central de la façade à grande colon-
nade du Louvre (aile orientale de la cour Car-
rée) présente cinq plates-bandes en fausse-coupe :
la porte principale, et les deux portes latérales
du rez-de-chaussée, ainsi que les deux fenêtres de
l’étage noble sont couverts en fausse-coupe.

Photo ci-dessous : vue générale du corps central.
Ci-contre de haut en bas : porte principale, porte
latérale, fenêtre de l’étage noble.

.

388

<!-- p. 390 -->

Annexe B. Catalogue

Fig B.102 – Louvre, cour Carrée, aile Est

1668-1670

Les fenêtres du premier étage, ouvrant sur la log-
gia couverte par les portiques de la grande co-
lonnade, sont couvertes par des plates-bandes en
fausse-coupe. Ces fenêtres ont été transformées
en niches peu après la construction de la colon-
nade. Au début du xixe siècle, lors de dépose du
remplissage des niches pour créer de nouveaux
des fenêtres, Pierre Fontaine en charge des tra-
vaux indique dans son journal que les fenêtres
d’origine sont réapparues.

Il est donc probable que les plates-bandes en
fausse-coupe qui couvrent l’ensemble des fenêtres
du premier étage de l’aile Est côté ville corres-
pondent aux plates-bandes d’origine construites
en 1668-1670.

Source : Fontaine (1987), signalé par
Alexandre Gady.

Fig B.103 – Louvre, cour Carrée, aile Est

1668-1670

Les portes latérales du passage de l’aile orientale
entre la ville et la cour Carré sont couvertes par
des plates-bandes en fausse-coupe.

389

<!-- p. 391 -->

Annexe B. Catalogue

Fig B.104 – Louvre,
pavillon de la Bibliothèque

1853-1855

Trois plates-bandes en fausse-coupe couvrant
Édouard Baldus, 1856-57
les fenêtres au premier étage du corps central
de l’aile Rivoli, le pavillon de la Bibliothèque,
construite par Louis Visconti sur ordre de Napo-
léon III.

Source photo noir et blanc : Édouard Bal-
dus, 1856-57, http://www.metmuseum.org/art/
collection/search/267002.

Fig B.105 – Louvre, pavillon Richelieu

1855

Une plate-bande en fausse-coupe est « inversée »
sur la façade du pavillon Richelieu, construit vers
1855 par Hector-Martin Lefuel qui poursuit les
travaux de Visconti après la mort de ce der-
nier. En eﬀet, les parties inclinées des joints sont
visibles du côté de la façade extérieure, et les
parties verticales sont visibles du côté intérieur
du bâtiment. Cette inversion pourrait s’expliquer
par le changement du sens de circulation, la cour
de la pyramide n’étant pas à l’époque le centre
de gravité « touristique » du Louvre qu’elle est
devenue avec les travaux du Grand Louvre. Au
xixe siècle, le visiteur entrait au Louvre depuis la
rue de Rivoli et le pavillon de la Bibliothèque, et
il devait donc d’abord découvrir la partie verti-
cale des joints en fausse-coupe, avant de pouvoir
observer la partie inclinée de l’autre côté de la
plate-bande.

Les portes latérales à l’intérieur du passage entre
la rue de Rivoli et la cour de la pyramide sont
également couvertes par des plates-bandes en
fausse-coupe.

390

<!-- p. 392 -->

Annexe B. Catalogue

B.5.3 Le dix-septième siècle

Fig B.106 – Paris, hôtel Méliand

1635-1644

Le portail de l’hôtel Méliand au 20 rue Poulletier
sur l’île Saint-Louis est couvert par une plate-
bande en fausse-coupe composée de neuf cla-
veaux. La plate-bande a fait l’objet d’une restau-
ration importante, qui pourrait avoir comporté la
mise en place d’un tirant d’intrados. L’hôtel a été
construit pour Jean de La Grange, conseiller du
Roi, par un architecte inconnu.

Il existe une photo de 1900-1901 de Atget du
portail de l’hôtel, mais cette dernière ne per-
met pas de distinguer l’appareil de la plate-
bande et la présence ou l’absence de l’interven-
tion au niveau de l’intrados (http://gallica.
bnf.fr/ark:/12148/btv1b10518073b consulté le
03/10/2017).

Source : Kamovska-Monnereau (2006).

Fig B.107 – Paris,
hôtel de Comans d’Astry

1643

L’hôtel de Comans d’Astry (également appelé
hôtel de Richelieu), au 18 quai de Béthune
à Paris, a été construit en 1643-1652 par
Louis Le Vau. Cet hôtel a autrefois été attribué
par erreur à Le Muet.

La porte d’entrée de la façade sur rue est couverte
par une plate-bande en fausse-coupe, construite
probablement en 1643-1644. Joints en fausse-
coupe très ﬁns qui rappellent la maîtrise de ceux
du Louvre. La porte de la façade sur cour est éga-
lement couverte par une plate-bande en fausse-
coupe, composée de neuf claveaux (ﬁg. 93 de la
thèse de Cojannot, 2011).

Le caractère particulier des plates-bandes
(fausse-coupe) n’est pas relevé par Sauval dans
sa description de l’hôtel (Sauval, 1724c, p. 13).

Source : Cojannot (2011).

391

<!-- p. 393 -->

Annexe B. Catalogue

Fig B.108 – Paris, 6 rue de Bretonvilliers

1642

Le portail de l’hôtel particulier au 6 rue de Bre-
tonvilliers sur l’île Saint-Louis est couvert par
une plate-bande composée de trois claveaux. Les
joints sont diﬃcilement visibles aujourd’hui, et
ont été surlignés sur la photo ci-contre en bas.

Sources : Babelon (1991, p. 283) ; Kamovska-
état 2017
Monnereau (2006).

état 2017, avec surlignement des joints

Fig B.109 – Paris, hôtel de Saint-Aignan

1644-1650

L’hôtel de Saint-Aignan, 71-75 rue du Temple à
Paris, est construit de 1644 à 1650 par Pierre
Le Muet (Ström, 2011, p. 154). Il abrite actuelle-
ment le musée du Judaïsme.

Le portail de la façade sur rue présente une plate-
bande en fausse-coupe à neuf claveaux. La partie
verticale des joints est visible côté rue, et la par-
tie inclinée des joints est visible depuis le passage
cocher. Une réservation importante dans le sof-
ﬁte de la plate-bande semble avoir été créée pour
l’installation des menuiseries en bois de la porte. Portail sur rue, vu de la rue

La porte du corps de logis au fond de la cour
est également couverte avec une plate-bande en
fausse-coupe, composée de cinq claveaux. La
trace d’une réservation correspondant probable-
ment à un tirant est visible sur l’intrados.

Portail sur rue, vu du passage cocher

Porte sur cour

392

<!-- p. 394 -->

Annexe B. Catalogue

Fig B.110 – Paris,
collège des Quatre-Nations

1661-1670

Plate-bande en fausse-coupe composée de
sept claveaux, couvrant la porte de la chapelle
de l’Institut de France (ancien collège des
Quatre-Nations). Le collège des Quatre-Nations
est construit par Louis Le Vau (1661-1670),
qui avait déjà utilisé les plates-bandes en
fausse-coupe pour le Louvre (voir supra) puis
terminé après sa mort par son collaborateur
François d’Orbay.

393

<!-- p. 395 -->

Annexe B. Catalogue

Fig B.111 – Paris, hôtel de la Confrérie
de Saint-Côme et de Saint-Damien

1694-1695 ou 1724-1752

L’hôtel de la Confrérie de Saint-Côme et de
Saint-Damien, au 5 rue de l’École de Méde-
cine à Paris, abrite l’amphithéâtre d’Anatomie,
construit en 1695-1696 par Charles et Louis Jou-
bert. Les plates-bandes en fausse-coupe sont si-
tuées sur les portes latérales de la façade de l’am-
phithéâtre.

Le coût de la construction conduit le maître d’ou-
vrage à de grandes diﬃcultés ﬁnancières, à tel
point qu’à défaut de ﬁnancement les cours ne
pourront se tenir dans l’amphithéâtre les pre-
mières années. Le décor prévu par Joubert pour
la façade avec appareil à refends, n’est pas exé-
cuté. Le décor sculpté rocaille actuel, avec de
grandes tables verticales de chaque côté de la
porte, est probablement réalisé après 1724 et
avant 1752-1756. En eﬀet, 1724 est la date où
les ﬁnances de la confrérie ont pu s’améliorer
grâce à l’édiction des lettres patentes du mois de
septembre 1724, qui établissaient cinq places de
professeurs payés par le roi. D’autre part l’ar-
chitecture françoise de Jacques-François Blondel
qui représente la façade avec son décor actuel est
publié entre 1752 et 1756.

En 1776, seule la table en bas-relief est proba-
blement modiﬁée au-dessus de la plate-bande,
peut-être également avec le ravalement du dé-
cor à gouttes qui encadrait la table existante. La
plate-bande en fausse-coupe daterait donc soit
de 1695, soit de 1724-1756. Nos recherches sem-
blant indiquer l’interruption de l’utilisation de la
fausse-coupe en France pour la première moitié
du xviiie siècle, la date de 1695 nous semble la
plus probable des deux possibles.

Les informations historiques permettant de ca-
drer la date de construction de la plate-bande
nous ont été communiquées par Pierre-Louis
Laget. Sur l’histoire générale de l’amphihéâtre
d’anatomie, voir Laget (1998).

Voir également la planche de Blondel (1754), re-
produite sur la ﬁgure B.114.

394

<!-- p. 396 -->

Annexe B. Catalogue

Fig B.112 – Montauban,
cathédrale Notre-Dame de l’Assomption

1692-1697

Les portes latérales de la façade de la cathé-
drale Notre-Dame de l’Assomption à Montau-
ban sont couvertes par des plates-bandes en
fausse coupe. La façade est construite à par-
tir de 1692 par François d’Orbay qui décède en
\1697. La construction de l’église est poursuivie
par l’agence de Jules-Hardoin Mansart jusqu’en
1708 avant d’être achevée par Robert de Cotte.

Bien que le premier dessin du projet de la fa-
çade reprennent exactement les dispositions de
l’église Notre-Dame de Versailles conçue par
Jules-Hardouin Mansart en 1684 (Julien, 2010),
l’église de Versailles ne présente pas de plates-
bandes en fausse-coupe en façade contrairement
à la cathédrale de Montauban.

Source photo : Base Mémoire MH0013939.

Sources : Julien (2010) ; Base Méri-
mée PA00095799.

395

<!-- p. 397 -->

Annexe B. Catalogue

Fig B.113 – Paris, 6 rue de Tournon

1710-1713

Plates-bandes en fausse-coupe sur les fenêtres
des bâtiments sur rue de l’hôtel de Brancas au
6 rue de Tournon à Paris. L’hôtel de Brancas
est construit par Pierre Bullet en 1710 pour Ter-
rat de Chantosme, chancelier du Régent (Tome
2 procès verbaux de l’Académie royale d’archi-
tecture, p. XXIII). La façade sur rue est classée
aux Monuments Historiques depuis 1970 (Source
base Mérimée PA00088526).

Les plates-bandes en fausse-coupe de cet hôtel
particulier sont mentionnées par Tibières (2012).
Les phases de construction de cet hôtel particu-
lier sont complexes, et il n’est pas certain que
le bâtiment sur rue appartienne aux phases de
constructions dirigées par Pierre Bullet (source :
échange oral avec Alexandre Gady).

Le Bullet signataire de la réunion de l’Acadé-
mie Royale d’Architecture du 22 Août 1701 qui
désapprouve l’usage des « joins à plomb », c’est-
à-dire des joints en fausse-coupe, pourrait être
le ﬁls de Pierre Bullet, Jean-Baptiste Bullet de
Chamblain (1665-1726), également élu à l’Aca-
démie Royale d’Architecture en 1699.

396

<!-- p. 398 -->

Annexe B. Catalogue

Fig B.114 – Façade de l’amphithéâtre d’Anatomie à paris, d’après Blondel (1754)

397

<!-- p. 399 -->

Annexe B. Catalogue

B.5.4 Le dix-huitième siècle

Fig B.115 – Lyon, Hôtel-Dieu,
façade quai du Rhône, corps central

1741-1763

Les travaux d’extension de l’Hôtel-Dieu, avec en
particulier la construction de l’immense aile le
long du quai du Rhône, a lieu de 1741 à 1763.
Jacques-Germain Souﬄot est chargé des travaux,
assisté par l’architecte Toussain Loyer et l’ingé-
nieur Munet. Les travaux seront dirigés par ces
derniers après le départ de Souﬄot pour Paris.

Le corps central de l’aile le long du quai du Rhône
est composé de trois travées. Les trois fenêtres
du premier étage sont couvertes par des plates-
bandes en fausse-coupe, des deux côtés du bâti-
ment (face au quai et face à la cour). Le premier
étage du corps central est occupé par la chapelle
des malades.

La plate-bande centrale est composée de neuf cla-
veaux, et les plates-bandes latérales de sept cla-
veaux.

Photos réalisées avec l’aide de Didier Repellin,
ACMH.

398

<!-- p. 400 -->

Annexe B. Catalogue

Fig B.116 – Lyon, Hôtel-Dieu,
vestibule d’entrée

1741-1763

Les deux portes latérales du vestibule d’entrée,
situé au rez-de-chaussée et donc sous la cha-
pelle des malades, sont couvertes par des plates-
bandes en fausse-coupe à un claveau unique. Les
deux sommiers sont posés en fort encorbellement.

Photos réalisées avec l’aide de Didier Repellin,
ACMH.

Fig B.117 – Lyon, Hôtel-Dieu, galerie

1741-1763

Les deux portes de la galerie côté cour, per-
mettant d’accéder aux pièces situées de part et
d’autre du vestibule d’entrée, sont couvertes par
des plates-bandes en fausse-coupe à un claveau
unique. Les deux sommiers sont posés en fort en-
corbellement. Une des deux pièces correspond à
l’ancien réfectoire du personnel.

Photos réalisées avec l’aide de Didier Repellin,
ACMH.

399

<!-- p. 401 -->

Annexe B. Catalogue

Fig B.118 – Lyon, Hôtel-Dieu,
tribunes de la chapelle des malades

1741-1763

Les quatre tribunes de la chapelle des malades
du corps central sont construites avec des plates-
bandes (ou voûtes plates) en fausse-coupe. Ces
plates-bandes sont composées de quinze cla-
veaux, et sont appuyées sur des sommiers portant
sur des consoles.

Photos réalisées avec l’aide de Didier Repellin,
ACMH.

Fig B.119 – Paris, chapelle de
l’abbaye de Penthemont

1753-1763

La chapelle de l’abbaye de Penthemont (ou Pan-
thémont) a été construite de 1753 à 1763, par
Pierre Contant d’Ivry. La plate-bande couvrant
la porte est une plate-bande à joints inclinés.
Cependant, l’entablement qui surplombe cette
porte semble être construit à l’aide d’une plate-
bande en fausse-coupe, dont les claveaux oc-
cupent la hauteur de l’architrave et d’une partie
de la frise. Cet entablement est placé en avant
du nu du mur. Il est possible également que les
claveaux de la plate-bande fasse queue dans le
corps du mur, et portent simplement en encor-
bellement.

400

<!-- p. 402 -->

Annexe B. Catalogue

Fig B.120 – Paris,
27 rue Saint-André-des-Arts

1754

Immeuble construit par Claude-Louis Daviler
en 1754 (Mignot, 2004, p. 93). L’arcade du porche
qui s’étend sur le rez-de-chaussée et l’entresol,
est divisé en deux par une plate-bande en fausse-
coupe au niveau du plancher de l’entresol.

Fig B.121 – Paris, église Saint-Eustache

Après 1754, avant 1766

Plates-bandes en fausse-coupe couvrant les
portes et fenêtres latérales de la façade occiden-
tale.

Les plates-bandes du premier ordre (photo ci-
contre) appartiennent vraisemblablement à la
première campagne de travaux de 1754-1756, in-
terrompue par la guerre d’Espagne. En 1756 seul
le premier ordre de la façade était terminée. Bien
que le projet de reconstruction de la façade fut
lancé en 1753 sur la base d’une maquette re-
trouvée dans l’église et attribuée à Louis Le Vau
(mais avec réserves selon Descat, 1997), le projet
est modiﬁé par l’architecte de la fabrique, Man-
sart de Jouy (1705-1783), et le chantier relancé
en 1754, sur un plan diﬀérent de la maquette at-
tribuée à Le Vau.

Jean Mansart de Jouy est le petit ﬁls de
Jules Hardouin-Mansart.

Fig B.122 – Lyon, église Saint-Polycarpe

1756

La plate-bande du portail de l’glise Saint-
Polycarpe est en fausse-coupe. Elle se compose
de cinq claveaux, et de deux sommiers posés avec
un encorbellement marqué.

L’église Saint-Polycarpe a été construite par les
oratoriens en 1655. La façade actuelle aurait
été construite par Toussain Loyer en 1756, mais
nous n’avons pas pu conﬁrmer ce point, qui pré-
sente pourtant un intérêt particulier ici puisque
Toussain Loyer a participé à la construction de
l’Hôtel-Dieu de Lyon aux côtés de Souﬄot.

401

<!-- p. 403 -->

Annexe B. Catalogue

Fig B.123 – Paris,
5 rue Geoﬀroy Saint-Hilaire

1760

Pavillon construit en 1760 et dépendant du
marché aux chevaux, au 5 rue Geoﬀroy Saint-
Hilaire à Paris. Les trois plates-bandes du rez-de-
chaussée présentent sont construites en fausse-
coupe.

Fig B.124 – Paris, 1 rue Visconti

Vers 1770

Deux plates-bandes en fausse-coupe donnant sur
la rue de Visconti, pour cet immeuble faisant
l’angle entre la rue de Seine et la rue Visconti,
et construit vers 1770.

Source : échange oral avec Alexandre Gady.

Fig B.125 – Bazeilles,
château de Montvillers

Vers 1770

Le château de Montvilleres à Bazeilles (Ardennes)
a été construit vers 1770 par Claude Jean-
Baptiste Jallier de Savault (1739-1806), élève de
Jacques-Germain Souﬄot. La plate-bande de la
porte principale de la façade antérieure est cou- —
verte par une plate-bande en fausse-coupe com-
posée de cinq claveaux. Le château est classé MH
(Base Mérimée PA00078340).

Source : Yvon Plouzennec (Centre André
Chastel, communication personnelle), Service
Régional de l’Inventaire de Champagne Ar-
denne http://www2.cr-champagne-ardenne.fr/
patrimoineindustriel08/Ill-09_08_02757_
NUCA.html consulté le 06/07/2017.

402

<!-- p. 404 -->

Annexe B. Catalogue

Fig B.126 – Paris, chapelle Saint-Louis

1776

Une plate-bande en fausse-coupe couvre la porte
entre la chapelle et l’aumônerie, dans la chapelle
Saint-Louis de l’hôpital de la Salpêtrière. L’au-
mônerie et la plate-bande de sa porte de com-
munication avec la chapelle pourrait avoir été
construite ou bien en 1776, date indiquée au des-
sus de sa porte, ou bien lors de la construction
de la chapelle par Libéral Bruand en 1671-1679.

Voir également les plates-bandes extérieures à
joints verticaux et crossettes : (ﬁg. 8.7)

Fig B.127 – Paris,
137 rue Vieille du Temple

1777-1778

Immeuble construit en 1777-1778, par Jean-Louis
Blève, dans un « style néoclassique élégant »,
pour Pierre Guérard commissaire des guerres
(Mignot, 2004, p. 100). Les plates-bandes du
deuxième étage (étage noble), troisième étage et
quatrième étage sont en fausse-coupe.

En dehors des plates-bandes du rez-de-chaussée
et du premier étage (ou entresol) qui sont traités
à refends et avec joints inclinés, toutes les plates-
bandes des étages sont construites en fausse-
coupe, ce qui est inhabituel.

403

<!-- p. 405 -->

Annexe B. Catalogue

Fig B.128 – Paris, 19 rue de Beaujolais

1784

Les galeries du Palais-Royal, situées au revers de
la rue de Montpensier, de la rue du Beaujolais
et de la rue de Valois, sont construites par Vic-
tor Louis (1731-1800) en 1784 (Pérouse de Mont-
clos, 1994, p. 380-382).

Le passage au 19 rue de Beaujolais qui permet
l’accès à la galerie depuis la rue, est couvert
par plusieurs plates-bandes en fausse-coupe, qui
pourraient être dues à Victor Louis, également
connu pour une voûte plate à stéréotomie savante
au grand théâtre de Bordeaux (le « clou » de Vic-
tor Louis).

Fig B.129 – Paris,
13 boulevard Beaumarchais

1781

Des plates-bandes en fausse-coupe couvrent les
fenêtres du premier et deuxième étage. Hôtel par-
ticulier construit en 1781 (Gady, 2002).

Fig B.130 – Caen, 41 rue Froide

xviiie s.

Plates-bandes en fausse-coupe sur la façade sur
rue du 41 rue Froide à Caen. La façade sur rue
pourrait dater du xviiie siècle.

L’escalier et les façades sur cour, plus anciennes
et ne présentant pas de plate-bande en fausse-
coupe, sont inscrits aux Monuments Historiques
(Base Mérimée PA00111181).

404

<!-- p. 406 -->

Annexe B. Catalogue

Fig B.131 – Paris, chapelle Expiatoire

1815-1826

La chapelle Expiatoire est construite de 1815
à 1826 par Pierre Fontaine, sans l’aide de Charles
Percier avec lequel il collaborait habituellement.

L’entrée rue Pasquier est couverte par une plate-
bande en fausse-coupe composée de cinq claveaux
(photo ci-contre).

La porte du portail principal de la chapelle serait
également en fausse-coupe, avec des claveaux de
très grand appareil (pas de photo).

Classé aux Monuments Historiques (Base Méri-
mée PA00088809).

Fig B.132 – Paris, Palais-Royal,
aile de Montpensier

1830

L’aile de Montpensier du Palais-Royal a été
construite par Pierre Fontaine en 1830. Elle est
le symétrique de l’aile de Valois construite par
Jacques Lemercier (années 1630) et modiﬁée par
Pierre Contant d’Ivry (1752).

Comme pour l’aile de Valois, les fenêtres de
l’étage noble de l’aile de Montpensier sont cou-
vertes par des plates-bandes en fausse-coupe.
Contrairement à l’aile de Valois, où le double-
ment des fenêtres un siècle après la construc-
tion des premières fausse-coupes montre une dif-
férence sensible de technique, l’ensemble de ces
plates-bandes sont homogènes : plates-bandes
composées de cinq claveaux sur le modèles de
celles de Lemercier.

Voir également ﬁg. B.82 ci-dessus.

Source historique : Pérouse de Montclos (1994,
p. 380-382).

405

<!-- p. 407 -->

Annexe B. Catalogue

B.5.5 Chambéry

Fig B.133 – Chambéry, hôtel de Roche

1767

L’hôtel de Roche, au 153 rue Croix d’Or à Cham-
béry, a été construit en 1767 pour Charles Roche,
avocat au Sénat de Savoie, probablement par
l’architecte turinois Luca Raineri (ou Reynero).
La façade principale, qui donne sur l’étroite
rue Croix d’Or, est composée de trois travées
dans les étages, et de seulement deux travées plus
larges au rez-de-chaussée.

Ces deux travées au rez-de-chaussée sont cou-
vertes par des plates-bandes en fausse-coupe
composées de cinq claveaux. Les parties verti-
cales des joints sont soulignées par les refends
soulignant l’appareil de la façade au rez-de-
chaussée et celui de la chaine d’angle du bâtiment
marquant également l’angle de la rue. A l’étage,
trois balcons sur cul de lampe. Le pied décoratif
d’un cul de lampe retombe sur la plate-bande, et
fait partie de l’un des claveaux.

La similitude de ces plates-bandes avec celles de
l’hôtel Chollet du Bourget sur la place Saint-
Léger est importante (voir exemple suivant).

Source : Juttet (2005, p. 191).

406

<!-- p. 408 -->

Annexe B. Catalogue

Fig B.134 – Chambéry,
hôtel Chollet du Bourget

1768-1773

L’hôtel Chollet du Bourget, a été construit par
l’architecte turinois Luca Raineri (ou Reynero)
en 1768-1773. L’hôtel fait l’angle entre la place
Saint-Léger, et la rue Métropole qui mène à la
cathédrale. Il fut construit à l’emplacement de
plusieurs parcelles, réunies au court des décennies
précédentes par le maître d’ouvrage.

Des modiﬁcations urbaines de la place Saint-
Léger sont à signaler avant la construction de
l’hôtel (démolition de l’église Saint-Léger au
centre de la place en 1760, couvrement progressif
au xviiie du bras de l’Albanne qui séparait aupa-
ravant la place actuelle en deux rues parallèles).

Le « prix-fait » de 1768 qui nous a été com-
muniqué par Benoit Chambre, architecte, est le
contrat de construction passé entre le maître
d’ouvrage (« Gaspard Chollet Baron du Bour-
get ») et l’entrepreneur (« François Joseph De-
neria maître tailleur de pierre »), décrivant les
constructions à réaliser. Le nom « Deneria » cor-
respond peut-être à la famille Denariez, connue
à Chambéry comme tailleurs de pierre sur plu-
sieurs générations, et dont un des descendants
sera entrepreneur lors de la construction de la rue
de Boigne, et un autre sera architecte sur le chan-
tier de l’Hôtel de Ville au milieu du xixe siècle.

Le prix-fait mentionne simplement pour le rez-
de-chaussée « plates-bandes » sans en indiquer le
caractère particulier, et précise que « les pierres
seront des carrières de Lemenc ».

La façade sur la place Saint-Léger se développe
sur sept travées, ce qui marque le caractère par-
ticulier de l’hôtel se détachant nettement du par-
cellaire médiéval du reste de la place Saint-Léger.
Les sept travées du rez-de-chaussée sont cou-
vertes de plates-bandes en fausse-coupe. Elles se
composent de cinq claveaux, dont l’appareil est
souligné par les refends, utilisés comme à l’hô-
tel de Roche pour le rez-de-chaussée et la chaine
verticale à l’angle de la façade.

Sources : Juttet (2005, p. 96, 188) ; informations
orales transmises par Benoit Chambre et Domi-
nique Tritenne.

407

<!-- p. 409 -->

Annexe B. Catalogue

Fig B.135 – Chambéry,
hôtel Chollet du Bourget

1768-1773

Voir historique de l’hôtel Chollet du Bourget ci-
dessus.

La façade de l’hôtel Chollet du Bourget sur la
rue Métropole se développe sur sept travées.
L’ensemble des baies sont couvertes de plates-
bandes en fausse-coupe, dont la mouluration est
diﬀérente de celle de la façade sur la place Saint-
Léger. On note ici l’absence de refends soulignant
les parties verticales des joints, contrairement à
la façade sur la place.

Les plates-bandes sont composées de trois cla-
veaux.

408

<!-- p. 410 -->

Annexe B. Catalogue

Fig B.136 – Chambéry,
hôtel de Bellegarde

1788

La façade de l’hôtel Noyel de Bellegarde
(13 rue Croix d’Or à Chambéry) a été construite
en 1788 par Carlo-Felice Lempo. Les travaux vi-
sèrent à unir derrière une même façade les bâti-
ments existants.

Toutes les baies du rez-de-chaussée sont cintrées
(anse-de-panier ou plein-cintre) à l’exception du
portail qui est couvert par une plate-bande. Cette
plate-bande est construite en fausse-coupe, et
elle est composée de sept claveaux. L’ébrase-
ment droit du soﬃte de la plate-bande donne
l’impression de joints à double coupe, cependant
ces joints s’inscrivent bien dans un plan vertical
(pour leur partie visible). La date de construction
(1788) est gravée sous la clé de la plate-bande.

Sources : Juttet (2005, p. 194) ; Base Méri-
mée PA00118237.

Fig B.137 – Chambéry,
hôtel des Marquis de Faverges

xviiie s. (hyp.)

Plate-bande en fausse-coupe couvrant le portail
d’entrée de la façade de l’hôtel des Marquis de
Faverges, 9 rue Métropole à Chambéry. Toutes
les autres baies de la façade au rez-de-chaussée
sont cintrées.

Il pourrait s’agir de la reconstruction d’une fa-
çade au xviiie siècle.

Source : informations orales transmises par Fran-
çois Juttet.

409

<!-- p. 411 -->

Annexe B. Catalogue

Fig B.138 – Chambéry, 3 rue de Boigne

xixe s. (hyp.)

La rue de Boigne est percée au début du
xixe siècle pour faciliter la traversée de la ville.
La partie centrale de la rue, bordée de portiques,
est construite de 1824 à 1830 par l’architecte
Jacques-Bernard Trivelli, beau-frère du général
de Boigne qui ﬁnance en grande partie les tra-
vaux. Les entrepreneurs sont Dénarié et Dunoyer.
3 rue de Boigne (Façade sur rue)
Le 3 rue de Boigne se trouve au nord de la
partie centrale (à portiques) de la rue, et le
21 rue de Boigne se trouve au sud. Les façades
répondent probablement au cahier des charges
qui devait ﬁxer l’aspect des bâtiments de cette
rue neuve, percée à travers la ville ancienne pour
faciliter la traversée de la ville.

La plate-bande de la porte cochère du
3 rue de Boigne est construite en simple fausse-
3 rue de Boigne, revers de la plate-bande coupe ; les parties verticales des joints sont
visibles côté rue, et les parties inclinées à lits
brisés sont visibles à l’intérieur du passage. Les
autres baies du rez-de-chaussée sont couvertes
de plates-bandes à joints inclinés.

Voir également le 21 rue de Boigne (photo ci-
contre), où la façade est très similaire, mais la
plate-bande n’est pas en fausse-coupe.

A signaler dans le même immeuble
(3 rue de Boigne), un escalier suspendu en
pierre, avec marches monolithes, de grande
21 rue de Boigne
qualité.

Source : Juttet (2005, p. 217-218)

Fig B.139 – Chambéry, 35 place Monge

xixe s. (hyp.)

Plate-bande en simple fausse-coupe couvrant le
portail d’entrée de la façade sur rue. Les parties
verticales des joints sont visibles côté rue, et les
parties inclinées à lits brisés sont visibles côté
passage.

410

<!-- p. 412 -->

Annexe B. Catalogue

Fig B.140 – Chambéry,
14 rue Jean-Pierre Veyrat

xixe s. (hyp.)

Plate-bande en fausse-coupe couvrant le portail
d’entrée de la façade sur rue. La face arrière de
la plate-bande n’est pas visible car masqué par
le plafond du passage cocher.

L’immeuble est construit à l’emplacement des
anciens remparts. Il pourrait dater du xixe siècle.

B.6 Voûtes plates

Sauf mention contraire, la source des datations est la Base Mémoire de la Médiathèque de l’Architecture et du Patrimoine.

Fig B.141 – Anet, château,
bâtiment d’entrée

1552 —

Voûte plate appareillée dans le bâtiment d’entrée.

Source : Pérouse de Montclos (1982, p. 285).

Fig B.142 – Écouen, château

1540-1550

« Escalier de l’aile gauche. Avant-dernière volée —
couverte d’une voûte en berceau très déprimée ,
presque plate, faisant retour sur le repos. ».

Source : Pérouse de Montclos (1982, p. 163, 295).

Fig B.143 – Brissac, château

1614-1620

Voûtes plates appareillées sur le plan d’une voûte
—
en arc de cloître, de 4 × 4 m de portée environ, for-
mant les repos de l’escalier, au château de Brissac.
Elles auraient été construites de 1614 à 1620.

Source : Pérouse de Montclos (1982, p. 163, 292).

Fig B.144 – Anet, château, aile gauche

1680-1712

La volée et les paliers de l’escalier de l’aile gauche
sont construits sur voûte plate, avec des retom-
—
bées cintrées très courtes. Selon les archives,
toutes les pierres du palier auraient été « goujon-
nées ».

Source : Pérouse de Montclos (1982,
p. 74, 178, 285).

411

<!-- p. 413 -->

Annexe B. Catalogue

Fig B.145 – Avignon,
chapelle de l’Oratoire

1731-1749

Quatre voûtes plates des chapelles nord sud est et
ouest entourant la travée du dôme, et une voûte
plate à l’entrée de la chapelle.

Ferdinand Delamonce (1678-1753), Jean-
Ange Brun et Jean-Baptiste II Péru se sont
succédés pour la construction.

Source photos : Henri Lestienne 1954 (Base
MédiatheK MDP86018050, MDP86018051,
MDP86018053, MDP86018053, MDP86018045).

412

<!-- p. 414 -->

Annexe B. Catalogue

Fig B.146 – Paris, église Saint-Sulpice,
porche

Vers 1732-1749

Le plafond du porche se compose de cinq voûtes
plates, dont l’appareil se devine à travers les dé-
cors sculptés de l’intrados, et dont l’appareil est
également visible sur l’extrados. L’extrados des
voussoirs forment l’aire de circulation des pièces
situées au-dessus des tribunes. Ces voûtes plates
sont appareillées sur le plan de la coupole. Il est
possible que les plates-bandes qui encadrent les
voûtes plates sur leur quatre côtés soient armées.
Cependant, le fait qu’aucune armature ne soit vi-
sible sur l’extrados de la voûte (qui est lui visible)
semble indiquer que la voûte elle-même n’est pas
armée. Intrados
Source : Losserand (2017a).

Extrados (photo : Léonore Losserand)

Fig B.147 – Paris, église Saint-Sulpice,
tribune d’orgue

Vers 1740-1750

Le plancher de la tribune se compose de trois
voûtes plates, avec l’appareil formant un dessin
décoratif sur l’intrados. La voûte plate centrale
est une voûte plate appareillée sur le plan d’une
voûte d’arêtes, et les voûtes plates latérales sont
appareillées selon un desssin en spirale, qui se
rapproche des voûtes plates appareillées sur le
plan de la coupole.

Sources : exemple relevé par de Maillet (2012) ;
Losserand (2017a).

413

<!-- p. 415 -->

Annexe B. Catalogue

Fig B.148 – Villeneuve-lès-Avignon,
chapelle des Pénitents Gris

1738-1753

Voûte plate de la sacristie. L’intrados n’est pas
plan, mais néanmoins très surbaissé. D’autres
voûtes surbaissées (moins plates) sont présentes
dans la nef (voûtes à arêtes doubles).

La construction de l’église est attribuée à Jean-
Baptiste Franque, de 1738 à 1753 (Viré-Gaillard,
2011).

Source photos : Henri Lestienne 1954 (Base Mé-
diatheK MDP86084210, MDP86084209).

Fig B.149 – Avignon,
hospices Saint-Louis

1741-1754

Voûte plate appareillée sur le plan d’une voûte
en éventail dans le vestibule.
Voûte plate appareillée partiellement sur le plan
de la coupole, dans la salle du rez-de-chaussée de
l’aile nord.

Bâtiments construits en grande partie par La
Valfenière, puis par Jean Péru au xviie siècle. La
date de construction donnée pour la voûte sur la
Base Mémoire est plus tardive, de 1741 à 1754.

Source photos : Henri Lestienne 1954 (Base Mé-
diatheK MDP86084205, MDP86084218).

414

<!-- p. 416 -->

Annexe B. Catalogue

Fig B.150 – Nantes,
3 place de la petite Hollande

1747-1752

Le palier du premier étage des escaliers de part et
d’autre de la cour sont formés de voûtes plates
appareillées sur le plan du berceau. Ces voûtes
plates sont bordées du côté de la façade par
des plates-bandes dont la hauteur est bien supé-
rieure à celle des voûtes plates ; ces plates-bandes
forment « mur d’allège » sous la fenêtre du pa-
lier également visible sur la photo ci-contre (en
haut).

Le 3 place de la petite Hollande fait partie de
l’ïle Faydeau à Nantes. Cette immeuble a été
construit entre 1747 et 1752 (Bienvenu 2017 Le
travertissement de la règle au xviiie siècle –
l’exemple de l’île Feydeau, communication dans
le cadre du troisième congrès francophone d’his-
toire de la construction).

Fig B.151 – Carpentras, Hôtel-Dieu

1750-1769

Voûte plate de la sacristie de la chapelle. L’Hôtel-
Dieu est construit entre 1750 et 1769, d’après le
projet de l’architecte Antoine d’Alleman, et réa-
lisé sous la direction de Jean-Baptiste Lambertin
puis Jean-Pierre Teissier entre 1750 et 1769.

Source : Losserand (2017b).

Source photo : Base MédiatheK MDP86058037
\1955.

415

<!-- p. 417 -->

Annexe B. Catalogue

Fig B.152 – Barbentane, château

Vers 1770

Voûte déprimée dans le salon des Statues
du château de Barbentane, d’une portée de
6,50 × 8,5 m. Contrairement à la voûte déprimée
de la salle à manger où seule la partie centrale de
la voûte est déprimée, dans le salon la partie ho-
rizontale de la voûte occupe presque l’intégralité
de la pièce.

Jean-Baptiste Franque n’est pas l’architecte de
cette voûte (Pérouse de Montclos, 1982).

Source photo : Base MédiatheK MDP86075662
\1956.

Fig B.153 – Avignon,
Grand séminaire Saint-Charles

1721-1723 ou 1753

Voûte plate du vestibule d’entrée, appareillée sur
le plan d’une voûte en éventail, construite sur
les plans de Jean-Baptiste Franque en 1721-1723
ou sur les plans de Jean-Baptiste et François II
Franque en 1753 (Viré-Gaillard, 2011). Les re-
tombées de la voûte sont cintrées.

Source photo : Henri Lestienne 1954 (Base Mé-
diatheK MDP86018030).

416

<!-- p. 418 -->

Annexe B. Catalogue

Fig B.154 – Paris, École Militaire

Vers 1770

Voûtes plates des portiques de l’Ecole Militaire
à Paris, construites vers 1770. La photo ci-contre
représente la voûte en cours de déconstruction.

Source photo : Daniel Bontemps 1985 (Base Mé-
diatheK MDP86087365).
Voir également ﬁg. 10.11.

Fig B.155 – Vaison-la-Romaine, église,
tribune

xviiie s. (hyp.)

La tribune de l’église est supportée par —
trois voûtes plates. Deux voûtes plates latérales
appareillées sur le plan d’une plate-bande, et une
voûte plate centrale appareillée sur le plan d’une
voûte en arc de cloître. Ces voûtes plates sup-
portent directement les tomettes du revêtement
de sol de la tribune.

417

<!-- p. 419 -->

Annexe C

Critère de résistances des joints
en X

Nous reproduisons ici un extrait d’un article en cours de rédaction de Maurizio
Brocato, qui décrit le calcul d’une estimation par l’intérieur du critère de résistance
d’un joint en X. Le résultat de cette démonstration est exploitée pour le calcul des
critères des joints des plates-bandes (section 15.2.2 p. 253).

In the case of a X-joint, when deﬁning the internal actions, we need to take into
account the contact stresses on two rectangular inclined ﬂat surfaces, containing the
y-axis, and on two triangular vertical ﬂat surfaces, orthogonal to y.
Each of the rectangular inclined face of the X can be seen as a ﬂat joint, of
width b/2, either inclined of ϕ or of −ϕ. Let us denote with a prime all entities
relative to the ϕ inclined half of the X, with a double prime those of the other half
(h′′ = h′ = h/ cos ϕ) and with a triple prime those on the two triangular faces. The
resultant forces and moment on each part of the joint are (see ﬁg. C.1)

h′/2 0 h′′/2 b/2 Z Z Z Z
N′ = σ′x′x′ dy dz′ ; N′′ = σ′′x′′x′′ dy dz′′ ;
−h′/2 −b/2 −h′′/2 0

Z h/2 Z z tan ϕ/2
N′′′ = − τxy dx dz ;
−h/2 −z tan ϕ/2

h′/2 0 h′′/2 b/2
′ Z Z ′ ′′ Z Z ′′ V y = τ x′y dx′ dy ; V y = τ x′′y dx′′ dy ;
−h′/2 −b/2 −h′′/2 0
′′′ Z 0 Z z tan ϕ/2 Z h/2 Z z tan ϕ/2
V y = − σyy dx dz + σyy dx dz ;
−h/2 −z tan ϕ/2 0 −z tan ϕ/2

h′/2 0 h′′/2 b/2
′ Z Z ′ ′′ Z Z ′′ V z′ = τ x′z′ dy dz′ ; V z′′ = τ x′′z′′ dy dz′′ ;
−h′/2 −b/2 −h′′/2 0
′′′ Z 0 Z z tan ϕ/2 Z h/2 Z z tan ϕ/2
V z = τyz dx dz − τyz dx dz ;
−h/2 −z tan ϕ/2 0 −z tan ϕ/2

h′/2 0 h′′/2 b/2 Z Z Z Z
M′y = − σ′x′x′z′ dy dz′ ; M′′y = − σ′′x′′x′′z′′ dy dz′′ ;
−h′/2 −b/2 −h′′/2 0

418

<!-- p. 420 -->

Annexe C. Critère de résistances des joints en X

Z 0 Z z tan ϕ/2 Z h/2 Z z tan ϕ/2
M′′′y = (τxyz −τyzx) dx dz − (τxyz −τyzx) dx dz ;
−h/2 −z tan ϕ/2 0 −z tan ϕ/2

h′/2 0 h′′/2 b/2 Z Z Z Z
M′z′ = σ′x′x′y dy dz′ ; M′′z′′ = σ′′x′′x′′y dy dz′′ ;
−h′/2 −b/2 −h′′/2 0

Z 0 Z z tan ϕ/2 Z h/2 Z z tan ϕ/2
M′′′z = − σyyx dx dz + σyyx dx dz ;
−h/2 −z tan ϕ/2 0 −z tan ϕ/2

h′/2 0
′ Z Z ′ ′ T = (τ x′z′y −τ x′yz′) dy dz′ ;
−h′/2 −b/2

h′′/2 b/2
′′ Z Z ′′ ′′ T = (τ x′′z′′y −τ x′′yz′′) dy dz′′ ;
−h′′/2 0

′′′ Z 0 Z z tan ϕ/2 Z h/2 Z z tan ϕ/2
T = σyyz dx dz − σyyz dx dz .
−h/2 −z tan ϕ/2 0 −z tan ϕ/2

b
2

⌧yz
σyy
σx00x00 σx0x0
⌧x00y ⌧xy
h ⌧x00z00 ⌧x0z0 ⌧x0y
x00

'

y
σyy ⌧xy
' x
⌧yz
z0
x0 b
z z00
2

Fig C.1 – Axes adopted in the description of contact stresses and actions for
X-joints.

The equilibrium conditions among these internal actions and those deﬁned in the
initial reference system (which are the internal actions of the ﬂat arch at the centre
of the X-joint) are :

N = (N′ + N′′) cos ϕ + (V z′′ −V z′′)′′ sin ϕ + N′′′ ;

Vz = −(N′ −N′′) sin ϕ + (V z′′ + V z′′)′′ cos ϕ + V z′′′ ;
Vy = V y′ + V y′′ + V y′′′ ;
My = M′y + M′′y + M′′′y ;
Mz = (M′z′ + M′′z′′) cos ϕ + (T ′ −T ′′) sin ϕ + M′′′z ;
T = −(M′z′ −M′′z′′) sin ϕ + (T ′ + T ′′) cos ϕ + T ′′′ .

419

<!-- p. 421 -->

Annexe C. Critère de résistances des joints en X

A ﬁrst result can be obtained taking, on the rectangular surfaces, stress ﬁelds
similar to the previous case, with the plastic neutral axis cutting the two rectangular surfaces at the same distance from the extrados, and taking, on the triangular
surfaces, the σyy ﬁeld be non null and symmetric with respect to the yz-plane. We
assume this ﬁeld be piecewise constant, with an area of maximum compression between the extrados and a segment parallel to it at a distance h(1 −ξ)/2, a similar
area between the intrados and a segment parallel to it at the same distance, and a
complementary area of null stress (see ﬁg. C.2).

h(1 −⇠)/2
h⇣
h⇣ 2 cos '
2 cos '

y

h(1 −⇠)/2 x

z

Fig C.2 – First assumption on the contact stress ﬁeld for X-joints : grey surfaces
carry the limit compressive stress.

The local contact actions are then :

bhσc N′ = N′′ = 2 cos ϕζ ; N′′′ = 0 ;

V y′ = V y′′ = V y′′′ = 0 ;

′ ′′ bhσc ′′′
V z′ = V z′′ = αµ z = 0 ; 2 cos ϕζ ; V
bh2σc
M′y = M′′y = y = 0 ; 4 cos2 ϕζ(1 −ζ) ; M′′′
b2hσc
−M′z′ = M′′z′′ = z = 0 ; 8 cos ϕζ ; M′′′
T ′ = T ′′ = 0 ; T ′′′ = −h3σc tan ϕ (1 −ξ3) ;
6
hence
N = 2N′ cos ϕ = bhσcζ ; Vy = 0 ; Vz = 2V z′′ cos ϕ = αµbhσcζ ;
bh2σc
My = 2M′y = 2 cos2 ϕζ(1 −ζ) ; Mz = 0 ;
b2hσc tan ϕ
T = ζ −h3σc tan ϕ (1 −ξ3) .
4 6

420

<!-- p. 422 -->

Annexe C. Critère de résistances des joints en X

The torsional equilibrium condition of the X section implies :

T = 0 ⇒ξ3 = 1 −3b2 ζ
2h2

which, in turn, implies an additional limitation for ζ, when h/b \< p3/2 :

( 2h2 )
0 ≤ξ ≤1 ⇒ζ ≤¯ζ = min ,1 .
3b2

We thus get the domain included in the surface whose edges are the parametric
curves :
 n = ζ
 vz = ζαµ ζ ∈[0,¯ζ] ; α ∈{−1,1} .
 |my| = ζ(1 −ζ)/ cos2 ϕ

Eliminating the parameter ζ we have the conditions :

n
\|my| ≤ (1 −n) ; |vz| ≤µn ; n ≤¯ζ . (C.1)
cos2 ϕ

showing that the X conﬁguration produces larger resisting moments per given axial
force than standard (when h/b ≥ p3/2), at least as far as the resistance of stone
does not enter into play.

The thus modeled X-joint ﬂat arch can be actually seen as a standard one, with
a ﬁctitious height, hX, larger than the nominal one :

hX = h/ cos2 ϕ .

421

<!-- p. 423 -->

Annexe D

Instrumentation des
plates-bandes à joints en X

D.1 Contexte

Les plates-bandes construites aux Grands ateliers de l’Isle d’Abeau (GAIA) en
2017 ont été décrites dans la section 7.3. Nous présentons dans cette annexe les
résultats de l’instrumentation, qui n’ont pas pu être exploités et reliés aux modèles de
calcul. Deux campagnes de mesures ont été conduites sur les mêmes plates-bandes.
La première a été réalisée en mars 2017 aux Grands ateliers de l’Isle d’Abeau. La
seconde a été réalisée dans les locaux de l’entreprise S.N.B.R. près de Troyes en juin
\2017.

Chaque plate-bande a été chargée par une force verticale appliquée à la clé de la
plate-bande, à l’aide d’un vérin équipé d’une cellule de charge pour mesurer l’eﬀort
appliqué. Le tirant était équipé d’une cellule de charge pour mesurer son eﬀort, et
donc la poussée de la plate-bande, un des sommiers étant placé sur un appui glissant.
Les déplacements verticaux de la clé (δ1, δ2 et δ3), et le déplacement horizontal d’une
contre-clé (δ4), ont également été mesurés (ﬁg. D.1).
Nous avons cherché à établir les relations expérimentales existant entre la charge
verticale centrée Q d’une part, et d’autre part la tension F dans le tirant et le déplacement vertical de la clé δm.

1
δm = 4(δ1 + δ2 + 2δ3) (D.1)

422

<!-- p. 424 -->

Annexe D. Instrumentation des plates-bandes à joints en X

Fig D.1 – Instrumentation de la plate-bande à joints en X IA01

D.2 Résultats de mars 2017 (GAIA)

Lors des expériences de mars 2017 (GAIA), les valeurs de la tension F dans le
tirant se sont avérées erronées en raison d’un problème technique sur le capteur de
mesure du tirant. Seules les valeurs du chargement Q et des déplacements ont été
obtenues.

La ﬁgure D.2 montre le déplacement vertical de la clé (compté positivement vers le
bas) en fonction de la charge verticale centrée Q . Les mesures des déplacements sont
prises égales à zéro au début de chaque cycle de chargement. Il existe une corrélation
linéaire entre le déplacement vertical de la clé et la charge centrée Q, lors de la charge.
Le rapport entre l’incrément de déplacement (en mm) et l’incrément de charge (en kN)
vaut 0,41 mm/kN environ.

423

<!-- p. 425 -->

Annexe D. Instrumentation des plates-bandes à joints en X

δm [mm] δm [mm] δm [mm]
Essai 1 du 22/03/17 Essai 2 du 22/03/17 Essai 3 du 22/03/17
4 GAIA 4 GAIA 4 GAIA
IA01 IA01 IA01

2 2 2

Q [kN] Q [kN] Q [kN]
0 0 0
0 5 10 0 5 10 0 5 10

δm (charge) δm (charge) δm (charge)
δm (d´echarge) δm (d´echarge) δm (d´echarge)
0,44 · Q −0,60 0,40 · Q −0,05 0,38 · Q + 0,10

Fig D.2 – Évolution des déplacements verticaux δm en fonction de la charge verticale
centrée Q, pour la plate-bande IA01 lors des expériences de mars 2017 (GAIA)

D.3 Résultats de juin 2017 (Troyes)

Lors des expériences de juin 2017 à Troyes, les déplacements mesurés se sont avérés inexploitables, la ﬁxation des capteurs de déplacement n’étant pas suﬃsamment
rigide. Seules les valeurs du chargement Q et de la tension dans le tirant F ont pu
être exploitées.

Les ﬁgures D.3 et D.4 montrent les mesures de la force F dans le tirant (convention
traction positive) en fonction de la charge verticale centrée Q, pour chaque platebande. Il existe une corrélation linéaire entre ces deux grandeurs. Cette ﬁgure montre
que la tension dans le tirant sous l’eﬀet du poids propre et de la mise en tension du
tirant, avant l’application de la charge verticale centrée, vaut 6,4 kN pour la platebande IA01, et 6 kN pour la plate-bande IA02. Le rapport entre l’augmentation de la
tension dans le tirant et la charge verticale centrée vaut ensuite 1,45 environ pour la
plate-bande IA01, et 1,4 pour la plate-bande IA02.

424

<!-- p. 426 -->

Annexe D. Instrumentation des plates-bandes à joints en X

F [kN] F [kN] F [kN]
20 20 20 Essai 1 du 15/06/17 Essai 2 du 15/06/17 Essai 3 du 15/06/17
Troyes Troyes Troyes
IA01 IA01 IA01
15 15 15

10 10 10

Q [kN] Q [kN] Q [kN]
5 5 5
0 5 10 15 0 5 10 15 0 5 10 15

cycle 1 cycle 2 cycle 3
1,47 · Q + 6,45 1,44 · Q + 6,44 1,42 · Q + 6,34

Fig D.3 – Évolution de la tension F dans le tirant en fonction de la charge verticale
centrée Q, pour la plate-bande à joints en X (IA01) lors des expériences
de juin 2017 (Troyes)

F [kN] F [kN]
20 20 Essai 1 du 15/06/17 Essai 2 du 15/06/17
Troyes Troyes
IA02 IA02
15 15

10 10

Q [kN] Q [kN]
5 5
0 5 10 15 0 5 10 15

cycle 1 cycle 2
1,39 · Q + 6,21 1,42 · Q + 5,76

Fig D.4 – Évolution de la tension F dans le tirant en fonction de la charge verticale
centrée Q, pour la plate-bande à joints en X réglés (IA02) lors des expériences
de juin 2017 (Troyes)

425

<!-- p. 427 -->

Annexe E

Voûtes plates d’Abeille
expérimentales

Les voûtes expérimentales présentées ici correspondent à des travaux de recherche
sur le système des voûtes plates d’Abeille, dirigés par Joël Sakarovitch puis Maurizio
Brocato au sein du laboratoire Géométrie, Structure, Architecture (GSA) de l’École
nationale supérieure d’architecture Paris-Malaquais (ENSA Paris-Malaquais). Ces
expériences, réalisées entre 2003 et 2012, sont les seuls exemples de voûtes d’Abeille
construites en France, l’invention d’Abeille n’ayant probablement pas été appliquée
en pratique au xviiie siècle (Díaz et Mozo, 2012, p. 294). Dans cette thèse, le choix
du rapport L/h entre portée et hauteur pris pour les études mécaniques est tiré des
expériences de Sakarovitch.

E.1 Expériences aux Grands ateliers de l’Isle d’Abeau

Plusieurs études expérimentales sur les voûtes plates d’Abeille ont été conduites
aux Grands ateliers de l’Isle d’Abeau entre 2003 et 2006 sous la direction de Joël Sakarovitch (2006). Les informations présentées ici concernent l’une de ces études expérimentales, et sont rapportées par Fleury (2009).

Lors de cette étude expérimentale, trois voûtes ont été construites. Chaque voûte
était composée de 25 claveaux courants, 20 claveaux de rive et 4 claveaux d’angles. La
pierre utilisée était une pierre de Saint-Leu ou pierre de Saint-Maximin roche ﬁne, de
masse volumique de la pierre 1658 kg/m3, et de résistance moyenne à la compression
comprise entre 8 et 15 MPa. Dans les trois cas, le ratio L/h est environ 14.

GAIA Cas A

— Portée hors-tout 2,52 m
— 2c = 2d = 35.7 cm
— h = 18 cm
— ϕ = 30◦
— 2a = 2d + 2h tan ϕ ≈56.5 cm
— 2b = 2c −2h tan ϕ ≈14.9 cm

426

<!-- p. 428 -->

Annexe E. Voûtes plates d’Abeille expérimentales

GAIA Cas B

— Portée hors-tout 1,26 m
— 2c = 2d = 17.7 cm
— h = 9 cm
— ϕ = tan−1( 4)1 ≈14,04◦
— 2a = 2d + 2h tan ϕ ≈22.2 cm
— 2b = 2c −2h tan ϕ ≈13.2 cm

GAIA Cas C

— Portée hors-tout 1,26 m
— 2c = 2d = 17,7 cm
— h = 8,85 cm
— ϕ = 45◦
— 2a = 2d + 2h tan ϕ ≈35.4 cm
— 2b = 2c −2h tan ϕ = 0 cm
Fleury indique que l’orientation des joints des voûtes nommées ici A, B et C sont
respectivement 60◦, 75◦et 45◦, soit ϕA = 90−60 = 30◦, ϕB = 90−75 = 15◦et ϕC =
90−45 = 45◦. Il semble qu’il y ait une erreur de transcription pour l’angle de la voûte
B, car la valeur ϕB = 15◦ne permet pas de trouver ensuite des valeurs compatibles
pour a, b, c et d. Nous proposons ci-dessus la correction ϕB = tan−1(14) ≈14.04◦qui
permet de retrouver les autres valeurs numériques données par Fleury pour a, b, c
et d. Les angles choisis pour les voûtes A, B et C correspondent alors à la règle du
triangle équilatéral, la règle du « 1 pour 4 », et la règle du « 1 pour 1 », que nous
avons évoquées dans la partie consacrée à l’histoire des plates-bandes.

E.2 Murs préfabriqués du projet Astonyshine

Le principe des voûtes d’Abeille a été utilisé par le projet Astonyshine dans le
cadre du Solar Décathlon Europe, une compétition universitaire internationale de
recherche et d’innovation sur la construction et l’énergie solaire (Brocato et al., 2014).
Des murs préfabriqués en pierre de taille ont été utilisés pour ce projet. Ils ont été
construits à Sainte-Savine dans les locaux de l’entreprise SNBR, puis assemblés et
présentés à Madrid en septembre 2012 (ﬁg. E.1).

Ces murs préfabriqués sont décrits par Brocato et al. (2014). Les murs sont constitués de 47 claveaux en pierre de taille, assemblés à l’intérieur d’un cadre en bois. Les
paramètres décrivant la géométrie des claveaux sont :
— 2b = 12 cm
— 2a = 60 cm
— h = 10 cm
— ϕ = 15◦
La pierre utilisée était une pierre de Noyant, de masse volumique de la pierre
2000 kg/m3. Le bois était un bois lamellé-collé de classe de résistance GL24h.

427

<!-- p. 429 -->

Annexe E. Voûtes plates d’Abeille expérimentales

Fig E.1 – Mur horizontal construit suivant le principe des voûtes d’Abeille,
d’après Brocato et al. (2014)

428

<!-- p. 430 -->

Annexe F

Formules des centres de gravités
et volumes des voussoirs

Les faces des voussoirs sont approximés par des polygones plans lors de la création
de la géométrie des voûtes avant l’application de la méthode des réseaux de forces
présentée dans cette thèse. L’information concernant la géométrie des voussoirs sont
réduits à des polyèdres après la génération de la géométrie. Il est possible de calculer
le volume et la position du centre de gravité des polyèdres à partir de formules
génériques. Ces quantités, exactes pour les polyèdres, sont des approximations des
quantités relatives aux voussoirs courbes.

Nous évitons cette approximation en aﬀectant à chaque polyèdre le centre de
gravité et la masse du voussoir à faces courbes correspondant avant simpliﬁcation
de ses surfaces courbes en polygones plans. Cette démarche nécessite de disposer des
formules analytiques des masses et des positions des centres de gravité des voussoirs
paramétrés. Ces formules sont données dans la suite. Les systèmes de coordonnées
utilisés pour décrire les voûtes et les voussoirs sont données sur la ﬁgure F.1.

z z z

r φ φ r
y y y
θ r θ
x x x

Coordonnées cylindriques d’axe y Coordonnées cylindriques d’axe z Coordonnées sphériques
pour arc plein-cintre pour voûte hélicoïdale pour dômes

Fig F.1 – Systèmes de coordonnées utilisés pour la description des voussoirs

429

<!-- p. 431 -->

Annexe F. Formules des voussoirs

F.1 Arc en plein-cintre

Nous considérons un arc en plein-cintre déﬁni en coordonnées cylindriques ﬁg. F.1
par :

— le rayon de l’intrados ri et le rayon de l’extrados re ;
— les plans verticaux y = y0 et y = y1.

Nous considérons ensuite un voussoir de cet arc, dont les joints sont donnés par
l’intersection des plans ϕ = ϕ0 et ϕ = ϕ1 avec l’arc.

Soit V le volume du voussoir, xG, yG, zG les coordonnées cartésiennes et rG, ϕG,
yG les coordonnées cylindriques de son centre de gravité. Ces quantités sont déﬁnies
par les formules suivantes.

Z re Z ϕ1 Z y1
V = r dr dϕ dy (F.1)
ri ϕ0 y0
Z re Z ϕ1 Z y1
V · xG = (r sin ϕ)(r dr dϕ dy) (F.2)
ri ϕ0 y0
Z re Z ϕ1 Z y1
V · zG = (r cos ϕ)(r dr dϕ dy) (F.3)
ri ϕ0 y0

Après intégration et factorisation, on obtient :

1
e −r2i ) · (ϕ1 −ϕ0) · (y1 −y0) (F.4) V = 2(r2
2 r3e −r3i −cos ϕ1 + cos ϕ0
xG = · · (F.5)
3 r2e −r2i ϕ1 −ϕ0
1
yG = 2(y0 + y1) (F.6)
2 r3e −r3i sin ϕ1 −sin ϕ0
zG = · · (F.7)
3 r2e −r2i ϕ1 −ϕ0

F.2 Dôme hémisphérique

Nous considérons un dôme hémisphérique déﬁni en coordonnées sphériques ﬁg. F.1
par le rayon de l’intrados ri et le rayon de l’extrados re. Nous considérons ensuite
un voussoir de ce dôme, dont les joints des méridiens sont donnés par l’intersection
des plans θ = θ0 et θ = θ1 avec le dôme, et les joints des parallèles sont donnés par
l’intersection des surfaces coniques ϕ = ϕ0 et ϕ = ϕ1 avec le dôme.

Soit V le volume de ce voussoir, xG, yG, zG les coordonnées cartésiennes et rG, ϕG,
θG les coordonnées sphériques de son centre de gravité. Ces quantités sont déﬁnies

430

<!-- p. 432 -->

Annexe F. Formules des voussoirs

par les formules suivantes.

Z re Z ϕ1 Z θ1
V = r2 sin ϕ dr dϕ dθ (F.8)
ri ϕ0 θ0
Z re Z ϕ1 Z θ1
V · xG = (r sin ϕ cos θ) · r2 sin ϕ dr dϕ dθ (F.9)
ri ϕ0 θ0
Z re Z ϕ1 Z θ1
V · yG = (r sin ϕ sin θ) · r2 sin ϕ dr dϕ dθ (F.10)
ri ϕ0 θ0
Z re Z ϕ1 Z θ1
V · zG = (r cos ϕ) · r2 sin ϕ dr dϕ dθ (F.11)
ri ϕ0 θ0

Après intégration et factorisation, on obtient :

1
e −r3i ) · (θ1 −θ0) · (−cos ϕ1 + cos ϕ0) (F.12) V = 3(r3
3 r4e −r4i sin θ1 −sin θ0 2(ϕ1 −ϕ0) −sin 2ϕ1 + sin 2ϕ0
xG = · · · (F.13)
16 r3e −r3i θ1 −θ0 −cos ϕ1 + cos ϕ0
3 r4e −r4i −cos θ1 + cos θ0 2(ϕ1 −ϕ0) −sin 2ϕ1 + sin 2ϕ0
yG = · · · (F.14)
16 r3e −r3i θ1 −θ0 −cos ϕ1 + cos ϕ0
3 r4e −r4i −cos 2ϕ1 + cos 2ϕ0
zG = · · (F.15)
16 r3e −r3i −cos ϕ1 + cos ϕ0

Les limites de ces quantités lorsque ϕ1 →ϕ0 sont :

3 r4e −r4i sin θ1 −sin θ0
lim xG = · · · 4 sin ϕ0 (F.16)
ϕ1→ϕ0 16 r3e −r3i θ1 −θ0
3 r4e −r4i −cos θ1 + cos θ0
lim yG = · · · 4 sin ϕ0 (F.17)
ϕ1→ϕ0 16 r3e −r3i θ1 −θ0
3 r4e −r4i
lim zG = · · 4 cos ϕ0 (F.18)
ϕ1→ϕ0 16 r3e −r3i

Les expressions précédentes donnent la position exacte du centre de gravité. Cependant pour comparer les résultats donnés par la méthode des réseaux de forces
avec d’autres méthodes de calculs, il est parfois nécessaire d’utiliser une position approchée. Par exemple, dans le cadre de la théorie membranaire, la surface considérée
pour l’écriture des équations d’équilibre est la surface moyenne. Or les centres de
gravité des voussoirs des réseaux de forces ne sont pas placés sur la surface moyenne.
Dans ce cas particulier, nous utilisons les formules approchées suivantes :
rG ≈1 + re) (F.19) 2(ri
ϕG ≈1 + ϕ1) (F.20) 2(ϕ0
1
θG = 2(θ0 + θ1) (F.21)

Voir également la thèse de Lau (2006, p. 36) pour les formules de V et xG dans le
cas des dômes dont la coupe est un arc brisé.

431

<!-- p. 433 -->

Annexe F. Formules des voussoirs

F.3 Dôme elliptique

Nous considérons un dôme elliptique d’épaisseur constante t déﬁni par les paramètres suivants :
— les rayons de l’intrados rix, riy et riz ;
— les rayons de l’extrados rex, rey et rez.
Les rayons sont reliés par les égalités rex −rix = t, rey −riy = t et rez −riz = t. Les
surfaces de l’intrados et de l’extrados sont engendrées par les surfaces paramétrées
suivantes, avec ϕ∗∈[0; π/2] et θ∗∈[0; 2π] :

x = rixcosθ∗sinϕ∗ x = rexcosθ∗sinϕ∗ (F.22)
y = riysinθ∗sinϕ∗ y = reysinθ∗sinϕ∗ (F.23)
z = rizcosϕ∗ z = rezcosϕ∗ (F.24)

Nous considérons ensuite un voussoir de ce dôme elliptique, dont les joints des
méridiens sont donnés par l’intersection des plans θ∗= θ0 et θ∗= θ1 avec le dôme, et
les joints des parallèles sont donnés par l’intersection des surfaces gauches ϕ∗= ϕ0
et ϕ∗= ϕ1 avec le dôme. Les paramètres θ∗et ϕ∗ne correspondent pas à aux coordonnées sphériques ϕ θ (ﬁg. F.1).

Contrairement aux autres types de voussoirs donnés dans cette annexe, nous avons
utilisé une approximation pour le calcul des volumes et centres de gravité des voussoirs
des dômes elliptiques d’épaisseur constante. En eﬀet, les expressions exactes de ces
quantités font intervenir des intégrales elliptiques dont la résolution sort du cadre de
notre étude.

Les approximations du volume V et de la position du centre de gravité d’un
voussoir sont obtenues en assimilant le voussoir étudié, avec un voussoir d’un dôme
elliptique d’épaisseur variable coïncidant localement avec le voussoir étudié. Le dôme
elliptique d’épaisseur variable est obtenu par transformation aﬃne d’un voussoir d’un
dôme hémisphérique d’épaisseur constante. Dans ce procédé, l’épaisseur du dôme hémisphérique et la transformation aﬃne doivent être ajustées pour chacun des voussoirs.

Le processus de calcul est le suivant. Nous considérons six objets géométriques :
— E0m, un ellipsoïde déﬁni par (rx = rxm ; ry = rym ; rz = rzm) ;
— R0m, une sphère déﬁnie par (r = rzm) ;
— E1m, un ellipsoïde déﬁni par (rx = αxrzm ; ry = αyrzm et rz = αzrzm), trans-
formation aﬃne de la sphère R0m (r = rzm) ;
— E0, un dôme elliptique d’épaisseur constante, correspondant au dôme étudié
(rx = rxm ; ry = rym ; rz = rzm)
— R0, un dôme sphérique d’épaisseur constante, dont les caractéristiques peuvent
être facilement calculées (r = rzm)
— E1, un dôme elliptique d’épaisseur variable dans l’espace, obtenu par transfor-
mation aﬃne du dôme sphérique R0
La transformation aﬃne recherchée est décrite par trois facteurs αx, αy et αz.
L’épaisseur du dôme R0 et les trois facteurs αx, αy et αz sont choisis de telle manière
que :
— les ellipsoïdes E0m and E1m sont identiques (cela donne αx, αy et αz) ;

432

<!-- p. 434 -->

Annexe F. Formules des voussoirs

— les dômes elliptiques E0 and E1 coïncident localement au niveau du voussoir
étudié (cela donne l’épaisseur du dôme R0).

Les caractéristiques du voussoir du dôme elliptique d’épaisseur variable E1 sont
déduites par transformation aﬃne des caractéristiques du dôme sphérique R0.

Cette technique ne donne qu’une approximation du volume et de la position des
centres de gravité. Sur l’exemple d’un quart de dôme, composé de 10 × 15 voussoirs, nous obtenons une erreur relative de 0,02% avec le volume total du quart
de dôme, qui peut être calculé analytiquement (contrairement aux volumes individudels des voussoirs qui le composent). Le poids total du quart de dôme vaut
4/3 π(rxeryerze −rxiryirzi).

F.4 Voûte hélicoïdale

Nous considérons une voûte hélicoïdale d’épaisseur verticale tz, et d’axe
z. Nous considérons ensuite un voussoir dont le volume intérieur est
déﬁni en coordonnées cylindriques (ﬁg. F.1) par r ∈[r0; r1], θ ∈[θ0; θ1] et
h θ−θ0 θ−θ0 i
z ∈ z0 + (z1 −z0) θ1−θ0 −tz/2; z0 + (z1 −z0) θ1−θ0 + tz/2 . Le voussoir considéré a
des joints verticaux. L’épaisseur verticale tz est plus grande que l’épaisseur du bloc (1).

Soit V le volume, et rG, θG, zG les coordonnées cylindriques du centre de gravité.
Ces quantités sont déﬁnies par les formules suivantes.

1
V = · r21 −r20 · (θ1 −θ0) · tz (F.25) 2
2 r31 −r30
rG = · (F.26)
3 r21 −r20
1
θG = · (θ0 + θ1) (F.27)
2
1
zG = · (z0 + z1) (F.28)
2

F.5 Voûte plate

Nous considérons une voûte plate d’épaisseur verticale h = z1 −z0, correspondant
à une voûte plate appareillée sur le plan du berceau ou d’une voûte en arc-de-cloître,
ou à une voûte plate d’Abeille. Nous considérons ensuite un claveau, dont la face
inférieure est donnée par les intervalles [xi0; xi1] × [yi0; yi1], et dont la face supérieure
est donnée par les intervalles [xe0; xe1] × [ye0; ye1].

Soit V le volume de ce claveau, et xG, yG, zG les coordonnées cartésiennes de son

(1). L’épaisseur verticale tz est notée g dans l’article de García Ares (2007).

433

<!-- p. 435 -->

Annexe F. Formules des voussoirs

centre de gravité. Ces quantités sont déﬁnies par les formules suivantes.

Z z1 Z x1(z) Z y1(z)
V = dx dy dz (F.29)
z0 x0(z) y0(z)
Z z1 Z x1(z) Z y1(z)
V · xG = x dx dy dz (F.30)
z0 x0(z) y0(z)
Z z1 Z x1(z) Z y1(z)
V · yG = y dx dy dz (F.31)
z0 x0(z) y0(z)
Z z1 Z x1(z) Z y1(z)
V · zG = z dx dy dz (F.32)
z0 x0(z) y0(z)

Nous utilisons les notations suivantes pour simpliﬁer les expressions :

∆xi = xi1 −xi0 (F.33)
∆xe = xe1 −xe0 (F.34)
1
xim = 2(xi0 + xi1) (F.35)
1
xem = 2(xe0 + xe1) (F.36)
∆yi = yi1 −yi0 (F.37)
∆ye = ye1 −ye0 (F.38)
1
yim = 2(yi0 + yi1) (F.39)
1
yem = 2(ye0 + ye1) (F.40)

434

<!-- p. 436 -->

Annexe F. Formules des voussoirs

Après intégration et factorisation, on obtient :

V = h∆xi∆yi
h
\+ (∆xi(∆ye −∆yi) + ∆yi(∆xe −∆xi))
2
h
\+ ((∆xe −∆xi)(∆ye −∆yi)) (F.41)
3
V xG = h∆xi∆yixim
h
\+ (∆xi(∆ye −∆yi)xim + ∆yi(∆xe −∆xi)xim + ∆xi∆yi(xem −xim))
2
h
\+ (∆xi(∆ye −∆yi)(xem −xim) + ∆yi(∆xe −∆xi)(xem −xim) + (∆xe −∆xi)(∆ye −∆yi)xim)
3
h
\+ (∆xe −∆xi)(∆ye −∆yi)(xem −xim) (F.42)
4
V yG = h∆xi∆yiyim
h
\+ (∆xi(∆ye −∆yi)yim + ∆yi(∆xe −∆xi)yim + ∆xi∆yi(yem −yim))
2
h
\+ (∆xi(∆ye −∆yi)(yem −yim) + ∆yi(∆xe −∆xi)(yem −yim) + (∆xe −∆xi)(∆ye −∆yi)yim)
3
h
\+ (∆xe −∆xi)(∆ye −∆yi)(yem −yim) (F.43)
4
h2
V zG −z0 = ∆xi∆yi
2
h2
\+ (∆xi(∆ye −∆yi) + ∆yi(∆xe −∆xi))
3
h2
\+ (∆xe −∆xi)(∆ye −∆yi) (F.44)
4

435

<!-- p. 437 -->

Table des ﬁgures

1.1 Polygones funiculaires et polygones des forces de systèmes composés
de deux forces coplanaires (à g.) ou non coplanaires (à d.), en vue
de face et vue de dessus . . . . . . . . . . . . . . . . . . . . . . . . . . 21
1.2 Comparaison de la ligne de pression et du polygone funiculaire . . . 25
1.3 Comparaison de la ligne de pression (bleu) et du polygone funicu-
laire (rouge) sur un exemple d’arc boutant . . . . . . . . . . . . . . . 26
1.4 Ligne de pression en bleu (« line of resistance ») et polygone funicu-
laire en rouge (« line of pressure »), d’après Moseley (1843a), et Hey-
man (2009) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 26
1.5 Inﬂuence du choix des joints sur la ligne de pression d’un piédroit,
d’après Dupuit (1870, Pl. 1) . . . . . . . . . . . . . . . . . . . . . . . . 26

2.1 Construction de K par trajets de charge radiaux, d’après Salençon
(1983, p. 40) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 31
2.2 Approximation par l’intérieur de la frontière de K lorsque K est
convexe, d’après Salençon (1983, p. 41) . . . . . . . . . . . . . . . . . 31
2.3 Déﬁnition du coeﬃcient de rupture, d’après Salençon (1983, p. 71) . . 33
2.4 Figure 17 des Discours et démonstrations mathématiques concernant
deux sciences nouvelles de Galilée 1638 . . . . . . . . . . . . . . . . . 35
2.5 Demi-voûte en berceau avec arc-boutant ; vue axonométrique (à g.),
et coupe selon le plan de symétrie (à d.) . . . . . . . . . . . . . . . . . 36
2.6 Travée présentant une symétrie par rapport à un plan (en vert) ; travée
présentant une symétrie par rapport à un plan seulement localement
(en rouge) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 36
2.7 Ensemble des lignes de pression intérieures d’un arc déterminées avec
la méthode de Delbecq (1983) . . . . . . . . . . . . . . . . . . . . . . 38

3.1 Axes locaux x′, y′ et z′ d’un joint . . . . . . . . . . . . . . . . . . . . 41
3.2 Axes globaux x, y et z d’une plate-bande . . . . . . . . . . . . . . . . 41
3.3 Critères de résistance pour un joint rectangulaire, avec résistance ﬁnie
à la compression . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 45
3.4 Critères de résistance avec et sans incertitudes sur la géométrie . . . . 46
3.5 Critères de résistance pour un joint rectangulaire, avec résistance in-
ﬁnie à la compression . . . . . . . . . . . . . . . . . . . . . . . . . . . 47
3.6 Arc stable (a), et arc d’épaisseur minimale (b), (c), d’après Heyman
(1995, p. 21) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 48
3.7 Coeﬃcient de sécurité géométrique D/d, d’après O’Dwyer (1999) . . . 49

436

<!-- p. 438 -->

Table des ﬁgures

3.8 Cercle de Mohr, convention de signe avec traction positive,
d’après Sollazzo et Marzano (1988) . . . . . . . . . . . . . . . . . . . 50
3.9 Cercle de Mohr, convention de signe avec compression positive (utili-
sée pour ce document), d’après Sollazzo et Marzano (1988) . . . . . . 51
3.10 Schéma de principe du découpage d’un claveau en champ de contrainte
constant par morceaux . . . . . . . . . . . . . . . . . . . . . . . . . . 51
3.11 Outil 1, détermination d’un cercle de Mohr à partir de deux points et
une direction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 52
3.12 Outil 2, détermination d’un second cercle de Mohr à partir de l’équi-
libre sur une interface . . . . . . . . . . . . . . . . . . . . . . . . . . . 54

4.1 Diagramme de la méthode des densités de forces . . . . . . . . . . . . 57
4.2 Matrice de connectivité (« branch-node matrix »), d’après Schek (1974) 59
4.3 Diagramme de recherche itérative des réseaux de densités de forces . . 61
4.4 Escalier hélicoïdal ; blocs (a), nuage de points (b), réseau de masse (c) 63
4.5 Diagramme de construction d’un réseau de forces . . . . . . . . . . . 64
4.6 Réseau de forces d’un escalier hélicoïdal, projection horizontale du
réseau de forces et ﬁgure réciproque associée en fonction des réactions
horizontales (poussées), d’après Ciblac et Fantin (2016) . . . . . . . . 65
4.7 Réseau projeté et sa forme duale, le diagramme des forces . . . . . . . 67
4.8 Diagramme de recherche d’un réseau de forces admissible . . . . . . . 70

5.1 Panneaux de voussoirs, d’après D’Aviler (1691, p. 236) . . . . . . . . . 73
5.2 Voûte bloquée au mortier, surmontée par une maçonnerie de blocage ;
amphithéâtre de Luni, Ligurie (Italie) . . . . . . . . . . . . . . . . . . 75
5.3 Frise historique des principaux traités français de coupe des pierres . 77
5.4 Joints d’un arc formant un angle droit avec l’intrados . . . . . . . . . 80
5.5 Arc avec joints non convergents vers le centre de l’arc, porte principale
de « Saülenstrasse »à Palmyre, d’après Durm (1885, ﬁg. 124) . . . . . 83
5.6 Lignes de courbure de l’ellipsoïde, devant correspondre aux joints selon
Monge, d’après Sakarovitch (1992, p. 537) . . . . . . . . . . . . . . . . 84

6.1 Plates-bandes droites et bombées, d’après D’Aviler (1691, Pl. 66), détail 88
6.2 Chapiteau et entablement doriques, d’après D’Aviler (1691, Pl. 12),
planche complète et détail . . . . . . . . . . . . . . . . . . . . . . . . 88
6.3 Plate-bande courbe, cour de l’hôtel de Beauvais à Paris, par An-
toine Le Pautre (1654-1657) . . . . . . . . . . . . . . . . . . . . . . . 89
6.4 Plate-bande à joints inclinés, d’après Diderot et d’Alembert (1756) . . 90
6.5 Plate-bande appareillée à crossettes (à g.), et à joints inclinés suivant
la règle du triangle équilatéral (à d.), d’après Diderot et d’Alembert
(1765a) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 90
6.6 Plate-bande à joints inclinés à inclinaison constante, et à lits brisés,
2 rue Métropole, Chambéry . . . . . . . . . . . . . . . . . . . . . . . . 91
6.7 Faux-appareil d’une plate-bande dessinée sur enduit,
13 rue des Beaux-Arts à Paris et 72 rue Saint-Louis-en-L’Ile à Paris . 91
6.8 Plates-bandes à lits brisés suivant un arc de cercle, d’après Rondelet
(1828, Pl. XXIX) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 93

437

<!-- p. 439 -->

Table des ﬁgures

6.9 Plate-bande à lits doublement brisés, d’après Chaix (1890, p. 172) . . 93
6.10 Plates-bandes à joints inclinés à double coupe, tombeau de Cecilia
Metella (Via Appia, Italie), d’après Rondelet (1828, Pl. XXIX) . . . . 93
6.11 Plate-bande en fausse-coupe, d’après Diderot et d’Alembert (1756) . . 95
6.12 Plate-bande à joints en X, d’après Ruskin (1849 ; 1855 pour ce dessin) 95
6.13 « Plates-bandes à claveaux en état de charge », d’après Douliot (1825,
Pl. 10) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 95
6.14 Plate-bande à clavettes, d’après De l’Orme (1567) . . . . . . . . . . . 96
6.15 Lyon, hôtel de ville . . . . . . . . . . . . . . . . . . . . . . . . . . . . 98
6.16 Lyon, chapelle Notre-Dame-de-Pitié, façade de 1646 sur des plans de
Le Muet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 98
6.17 Trois règles géométriques donnant l’inclinaison des joints d’une plate-
bande . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 100
6.18 Plates-bandes d’après Serlio (1537, 9v, 10v, 17v) . . . . . . . . . . . . 101
6.19 Illustration des systèmes de décharge de Vitruve, d’après Perrault
(1673, VI-11) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 102
6.20 Illustration des systèmes de décharge de Vitruve, d’après Rondelet
(1805, Pl. LXVIII Fig. 1) . . . . . . . . . . . . . . . . . . . . . . . . . 102
6.21 Plates-bandes respectant la règle du triangle équilatéral d’après Serlio
(1537, 9v, 10v, 17v) ; voir également ﬁg. 6.18 . . . . . . . . . . . . . . . 102
6.22 « Plate bande droite, ou plat Fond », d’après Jousse (1642, p. 202) . . 103
6.23 Plates-bandes et voûtes plates, d’après Frézier (1738, Pl. 31) . . . . . 105
6.24 « Arrière voussure en plate-bande, ébrasée en quart de cercle »,
d’après Simonin (1792, Pl. XIII) . . . . . . . . . . . . . . . . . . . . . 107
6.25 Passage Menestrier, Lyon . . . . . . . . . . . . . . . . . . . . . . . . . 108
6.26 Méthodes de tracé de l’appareil d’une plate-bande à cinq claveaux . . 111
6.27 Comparaison des coupes données par la division égales des angles du
triangle, et la division égale de l’intrados . . . . . . . . . . . . . . . . 112
6.28 Non convergence des joints tirés de la méthode de proportion des saillies113
6.29 Règle du « 1 pour 3 »dessinée sur la portée (à g.), et sur le joint du
sommier (à d.), donnant un appareil identique . . . . . . . . . . . . . 114
6.30 « Portes quarrées »et « Portes bombées », d’après Blondel (1752, p. 111)115
6.31 Hauteur de la plate-bande suivant diﬀérents auteurs . . . . . . . . . . 117
6.32 Épaisseur à donner aux piédroits qui soutiennent une plate-bande,
d’après d’après Bélidor (1729, Pl. 6) . . . . . . . . . . . . . . . . . . . 118
6.33 Règle géométrique pour la détermination de la hauteur de la plate-
bande ; ﬁgure de droite d’après Association ouvrière des Compagnons
du devoir (1996, p. 78) . . . . . . . . . . . . . . . . . . . . . . . . . . 119
6.34 Hauteur et inclinaison des joints à donner à une plate-bande,
d’après Gautier (1717, Pl. II Fig. 4) . . . . . . . . . . . . . . . . . . . 120
6.35 Plate-bande à double crossettes, Le Caire (Égypte) –
photo : Louis Jacquart, 2016 . . . . . . . . . . . . . . . . . . . . . . . 122
6.36 Plate-bande à double crossettes, Le Caire (Égypte) –
photo : Louis Jacquart, 2016 . . . . . . . . . . . . . . . . . . . . . . . 122
6.37 Plates-bandes romaines, d’après Planat (1888d, p. 486-487) . . . . . . 124
6.38 Plate-bande du temple des Géants d’Agrigente, d’après Choisy (1899a,
p. 302) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 128

438

<!-- p. 440 -->

Table des ﬁgures

6.39 Plate-bande armée à Tivoli, d’après Olivier (1983) reproduisant un
dessin de Hoﬀmann (1978) . . . . . . . . . . . . . . . . . . . . . . . . 128
6.40 Avant-corps du château d’Anet construit par De l’Orme après 1547,
remonté à Paris au xixe s. . . . . . . . . . . . . . . . . . . . . . . . . 130
6.41 Grande colonnade du Louvre par Claude Perrault (1667-1670) . . . . 130
6.42 Plates-bandes armées de la place Louis XV (actuelle place de la
Concorde), Paris, d’après Patte (1769) . . . . . . . . . . . . . . . . . 131
6.43 Plates-bandes avec linteau en fer engravé sous l’intrados, d’après Blon-
del et Patte (1777a, Pl. LXXIV) . . . . . . . . . . . . . . . . . . . . . 132
6.44 Plate-bande à refends, 6 rue des Beaux-Arts à Paris . . . . . . . . . . 135
6.45 Voussure à refends, 16 rue Tournefort à Paris . . . . . . . . . . . . . . 135
6.46 Linteau avec faux-appareil en bossage, imitant des joints verticaux,
sur la façade d’un palais de Prato . . . . . . . . . . . . . . . . . . . . 135
6.47 Plate-bande à refends, 29 rue de la Ferronnerie à Paris . . . . . . . . 135
6.48 Décor ablaq sur les façades de la cathédrale, du château, et de
l’église San Francesco à Prato . . . . . . . . . . . . . . . . . . . . . . 136
6.49 Modes constructifs des claveaux ablaq dans l’architecture islamique ;
schémas de principe d’après les dessins de Cejka (1978, 5-Abb19a,
Abb20) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 137
6.50 Façade sur rue du Palazzo Barbarano à Vicence, d’après Palladio
(1570, Livre 2 p. 23) . . . . . . . . . . . . . . . . . . . . . . . . . . . . 138
6.51 Portail de l’hôtel d’Uzès, construit par Ledoux ; schéma gravé d’après
Ledoux, ne représentant pas l’appareil réel de la plate-bande (Gallet
\1980) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 139
6.52 Portail de l’hôtel d’Uzès à Paris ; dessin ne représentant pas l’appareil
réel de la plate-bande . . . . . . . . . . . . . . . . . . . . . . . . . . . 139
6.53 Portail de l’hôtel d’Uzès à Paris ; dessin ne représentant pas l’appareil
réel de la plate-bande . . . . . . . . . . . . . . . . . . . . . . . . . . . 139

7.1 Assemblage séquentiel d’une plate-bande à joints en X . . . . . . . . . 141
7.2 Plate-bande du portail sud du transept de la cathédrale de Prato,
d’après Raguenet (1915a) . . . . . . . . . . . . . . . . . . . . . . . . . 142
7.3 Localisation des cinq exemples de plates-bandes à joints en X connus 142
7.4 Plate-bande dessinée par Léonard de Vinci vers 1480-1482, Codex
Atlanticus f.0091 v . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 143
7.5 Plate-bande à joints en X d’Alba Iulia, d’après Motro (2009) . . . . . 143
7.6 « Berceau suspendu », d’après Simonin (1792, Pl. XXII) . . . . . . . . 145
7.7 Vue 3D éclatée puis assemblée du modèle de la plate-bande à joints
en X en bois . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 146
7.8 Essai en ﬂexion trois points d’une plate-bande à joints en X en bois . 147
7.9 Essai en ﬂexion quatre points d’une plate-bande à joints en X en bois 147
7.10 Vue 3D éclatée puis assemblée, du modèle de la plate-bande à joints
en X (IA01), avec bloc d’appui en rouge, et appui glissant en magenta 148
7.11 Vue 3D éclatée puis assemblée, du modèle de la plate-bande à joints
en X réglés (IA02), avec bloc d’appui en rouge, et appui glissant en
magenta . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 148
7.12 Claveaux – joints en X (IA01 à g.) et joints en X réglés (IA02 à d.) . 148

439

<!-- p. 441 -->

Table des ﬁgures

7.13 Plate-bande à joints en X IA01 . . . . . . . . . . . . . . . . . . . . . . 149
7.14 Plate-bande à joints en X réglés IA02 . . . . . . . . . . . . . . . . . . 149
7.15 Plate-bande IA01 en cours de montage . . . . . . . . . . . . . . . . . 150
7.16 Plate-bande IA02 chargée, avec une règle droite posée sur l’extrados
pour visualiser la déformation . . . . . . . . . . . . . . . . . . . . . . 150

8.1 Joints en fausse-coupe mn d’un arc, d’après Diderot et d’Alembert
(1756) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 152
8.2 Plate-bande en fausse-coupe, d’après Diderot et d’Alembert (1756) . . 152
8.3 Plate-bande en fausse-coupe, d’après Simonin (1792, Pl. XXI) . . . . . 153
8.4 Paris, fontaine des Quatre-Saisons rue de Grenelle, construite par
Edmé Bouchardon (1739-1745) . . . . . . . . . . . . . . . . . . . . . . 156
8.5 Paris, Louvre, passage de l’aile Sud de la cour Carrée . . . . . . . . . 156
8.6 Localisation des plates-bandes en fausse-coupe au rez-de-chaussée de
la cour Carrée du Louvre ; les numéros renvoient au catalogue en an-
nexe ; fond de plan d’après Blondel (1756, Pl. 5) . . . . . . . . . . . . 160
8.7 Plate-bande à joints verticaux et crossettes, chapelle Saint-Louis
de l’hôpital de la Salpêtrière à Paris, construite par Libé-
ral Bruand (1671-1679) . . . . . . . . . . . . . . . . . . . . . . . . . . 161
8.8 Plate-bande à joints en fausse-coupe, portail occidental de la cathé-
drale de Prato . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 166
8.9 Composition hypothétique de la plate-bande à joints verticaux de Prato167
8.10 Plate-bande à joints verticaux de la masrada ’Âdiliya à Damas (Syrie),
avec crossettes masquées à l’arrière – photo : Luc Tamboréro . . . . . 167

9.1 « Des Trois Colonnes de Campo Vaccino à Rome », temple de Jupi-
tor Stator, d’après Desgodets (1682, p. 127) . . . . . . . . . . . . . . . 171
9.2 Entablement dorique avec architrave à trois bandes, d’après Choisy
(1899a, p. 299) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 171
9.3 Temple de Jupiter Stator, d’après Choisy (1899a, p. 515) . . . . . . . 171
9.4 Plates-bandes antiques, d’après Rondelet (1828, Pl. XXIX) . . . . . . 173
9.5 Ruines du temple du soleil à Baalbek (iie siècle), d’après Planat
(1888c, p. 422) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 174
9.6 Plates-bandes romaines dessinées par Durm (1885, ﬁg. 116) . . . . . . 175
9.7 Manteaux de cheminées, d’après Viollet-Le-Duc (1858) . . . . . . . . 178
9.8 Dessin d’une clé de plate-bande et des deux contre-clés, d’après Vil-
lard de Honnecourt . . . . . . . . . . . . . . . . . . . . . . . . . . . . 179
9.9 Analyse du dessin de Villard de Honnecourt (ﬁg. 9.8), d’après Bech-
mann (1993, p. 203) . . . . . . . . . . . . . . . . . . . . . . . . . . . . 179
9.10 Plate-bande dessinée par Léonard de Vinci vers 1479-1480, Codex
Atlanticus f.1074 r . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 182
9.11 Copie de la plate-bande du feuillet f.1074 r de Léonard de Vinci, Codex
Atlanticus f.0050 r . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 182
9.12 Plate-bande dessinée par Léonard de Vinci vers 1480-1482, Codex
Atlanticus f.0076 r . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 182

10.1 Arcs surbaissés, superposés à un arc en plein-cintre . . . . . . . . . . 185

440

<!-- p. 442 -->

Table des ﬁgures

10.2 Arcs surhaussés, superposés à un arc en plein-cintre . . . . . . . . . . 185
10.3 Appareils des voûtes plates, d’après Rondelet (1804, Pl. XXXI) –
ici Rondelet (1828, Pl. XXX) . . . . . . . . . . . . . . . . . . . . . . . 186
10.4 Avignon, hôtel Franque (1743-1751), voûtes surbaissées, à arêtes
doubles – photos : Meyer, 1955 . . . . . . . . . . . . . . . . . . . . . . 187
10.5 Voûte d’arête plate (à g.) et voûte d’arête bombée (à d.), d’après Ron-
delet (1804, Pl. XXXVII) – ici Rondelet (1828, Pl. XXX) . . . . . . . 187
10.6 Voûte plate dallée de la chapelle des Évêques de la cathédrale de Toul ;
vue de dessous de la voûte étayée (à g.) et vue de détail de l’extrados
(à d.) ; claveau courant d’un arc doubleau (a), claveau à l’intersection
de deux arcs doubleaux (b), dalle en deux parties (c) . . . . . . . . . 188
10.7 Voûtes plates, d’après Diderot et d’Alembert (1765b) . . . . . . . . . 190
10.8 « Double coupe de la plate-bande A B C D d’un pallier. P, point de
concours des joints mn, mn. R, point de concours des joints no, no.
G point de concours des joints de lit des claveaux du plat-fond »,
d’après Diderot et d’Alembert . . . . . . . . . . . . . . . . . . . . . . 191
10.9 Chaînages métalliques pour les voûtes plates formant palier d’escalier,
d’après Blondel et Patte (1777a, Pl. LXXIX) . . . . . . . . . . . . . . 192
10.10 « Plates-bandes de la Place de Louis XV »(place de la Concorde à Pa-
ris), d’après Patte (1769) . . . . . . . . . . . . . . . . . . . . . . . . . 194
10.11 Paris, École Militaire, « Voûte déposée de la travée de l’aile formant le
portique droit »(en h.), « Chaînage longitudinal et transversal repris
par ancre au droit des colonnes »(en b.)– photos : Daniel Bontemps,
1985 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 195
10.12 Voûte d’Abeille, d’après Gallon (1735) . . . . . . . . . . . . . . . . . . 197
10.13 Paramétrisation de la voûte d’Abeille, d’après Brocato et Mondardini
(2014) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 197
10.14 Place des Vosges, voûtes en brique des arcades des pavillons de la
Reine (nord de la place) . . . . . . . . . . . . . . . . . . . . . . . . . . 199
10.15 Place des Vosges, voûtes en plâtre sur ossature bois, à faux appareil ;
Pavillons à l’ouest de la place . . . . . . . . . . . . . . . . . . . . . . . 199
10.16 Voûte assez surbaissée en brique, extrait de la planche LXXXXV du
cours de Blondel et Patte (1777b) . . . . . . . . . . . . . . . . . . . . 201
10.17 Voûte très surbaissée en brique, extrait de la planche LXXXXVII du
cours de Blondel et Patte (1777b) . . . . . . . . . . . . . . . . . . . . 201

11.1 Extensions 2D à 3D du polygone funiculaire et de la ligne de pression 205
11.2 Cas d’équilibres avec ou sans intersection des forces en un point . . . 207
11.3 Voussoirs d’une voûte d’Abeille . . . . . . . . . . . . . . . . . . . . . . 209
11.4 Domaines des solutions d’équilibre ; intersections possibles des solu-
tions d’équilibre stables, avec ou sans la propriété d’intersection des
forces en un point . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 210

12.1 Diagramme de la méthode des réseaux funiculaires . . . . . . . . . . . 213
12.2 Dôme avec oculus – exemples de deux appareils paramétriques . . . . 214
12.3 Nœud à quatre branches avant (à gauche) et après (à droite) le raﬃ-
nement du réseau . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 216

441

<!-- p. 443 -->

Table des ﬁgures

12.4 Arc avant (à gauche) et après (à droite) le raﬃnement du réseau . . . 216

13.1 Lune d’un dôme hémisphérique, réseau de masse, conditions de symé-
trie sur les nœuds d’appuis . . . . . . . . . . . . . . . . . . . . . . . . 222
13.2 Voûte plate, réseau de masse, conditions de symétrie sur les nœuds
d’appuis . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 222
13.3 Voussoir d’une lune de dôme hémisphérique, après découpage selon
parallèles et méridiens . . . . . . . . . . . . . . . . . . . . . . . . . . . 224
13.4 Réduction des joints à un segment ; voussoir (a), joint méridien (b),
joint parallèle (c) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 224
13.5 Joints des branches méridiennes (en bleu) et des branches parallèles
(en rouge), pour une lune d’un dôme hémisphérique . . . . . . . . . . 224
13.6 Projection sur le plan horizontal d’une voûte hélicoïdale à cinq cla-
veaux, où la réduction des joints est vide . . . . . . . . . . . . . . . . 225
13.7 Centres de pression et polygone funiculaire . . . . . . . . . . . . . . . 230
13.8 Coeﬃcient de sécurité statique théorique . . . . . . . . . . . . . . . . 230
13.9 Convergence de max fp vers f(ζ∗) = max f, arc en plein-cintre . . . . 230
13.10 Convergence de (max fp −max fp−1) vers 0, arc en plein-cintre . . . . 230
13.11 Dôme elliptique, avec blocs d’appuis en rouge . . . . . . . . . . . . . . 232
13.12 Réseau de forces . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 232
13.13 Convergence de (max fp −max fp−1) vers 0, dôme elliptique . . . . . 232
13.14 Convergence de (max fp −max fp−1) vers 0, plate-bande à joints en X 232
13.15 Réseaux de forces optimaux correspondant aux chargements extrêmes
calculés pour p ∈{100; 200; 300; 400} ; plate-bande à joints en X . . . 233
13.16 Coeﬃcient de sécurité local sur un joint . . . . . . . . . . . . . . . . . 234
13.17 Fonctions polynomiales remplaçant le coeﬃcient de sécurité local . . . 234
13.18 Exploitation de la propriété de convexité du domaine des chargements
supportables . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 236

14.1 Convergence de l’approximation de l’épaisseur minimale d’un arc de
30 voussoirs vers l’épaisseur minimale théorique . . . . . . . . . . . . 241
14.2 Lignes de pression d’un arc de 30 voussoirs d’épaisseur minimale
t/r = 0,10746 (a), et d’un arc de 11 voussoirs d’épaisseur minimale
t/r = 0,10493 (b) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 241
14.3 Épaisseur minimale d’un dôme sphérique en fonction de son angle
d’ouverture, d’après Zessin (2012, p. 53) . . . . . . . . . . . . . . . . . 242
14.4 Équilibre d’une lune d’un dôme hémisphérique d’épaisseur minimale
(à g.), et mécanisme de ruine correspondant pour le dôme (à d.),
d’après Heyman (1967a) . . . . . . . . . . . . . . . . . . . . . . . . . 243
14.5 « surface de pression »(caténaire) touchant le dôme le plus petit la
contenant, d’après Coccia et al. (2016) . . . . . . . . . . . . . . . . . 243
14.6 Découpage d’un dôme hémisphérique en lunes de 10◦d’ouverture (a),
lune isolée (b), et découpage d’une lune en 15 voussoirs (c) . . . . . . 244
14.7 Convergence de l’approximation de l’épaisseur minimale d’une lune
de 15 voussoirs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 244
14.8 Ligne de pression d’une lune d’épaisseur minimale t/r = 0,428 . . . . 245

442

<!-- p. 444 -->

Table des ﬁgures

14.9 Projet de dôme pour Saint-Pierre de Rome par Bramante (a), décou-
page en blocs pour étude dôme (b), schéma de principe des « aires de
stabilité »(c), d’après Durand-Claye (1880) . . . . . . . . . . . . . . . 246
14.10 Superposition du polygone funiculaire (a), et des coeﬃcients de sécu-
rité statiques (b), sur le dessin d’après Durand-Claye (1880) . . . . . 246
14.11 Dôme hémisphérique (à g.) et dôme elliptique (à d.) . . . . . . . . . . 247
14.12 Dôme elliptique et le réseau de forces correspondant au coeﬃcient de
sécurité géométrique maximum . . . . . . . . . . . . . . . . . . . . . . 248

15.1 Paramétrage de la géométrie des plates-bandes à joints inclinés, avec
blocs d’appui en rouge . . . . . . . . . . . . . . . . . . . . . . . . . . . 250
15.2 Paramétrage de la géométrie des plates-bandes à joints en X, avec
blocs d’appui en rouge . . . . . . . . . . . . . . . . . . . . . . . . . . . 251
15.3 Arc de décharge se formant par encorbellement dans la maçonnerie,
d’après Rondelet (1805, Pl. LXIX Fig. 4, p. 309) . . . . . . . . . . . . 252
15.4 Inﬂuence du nombre de claveaux k sur le domaine des chargements
supportables d’une plate-bande à joints verticaux de type Prato . . . 260
15.5 Inﬂuence de l’inclinaison des joints d’appui ϕ sur le domaine des char-
gements supportables d’une plate-bande à joints inclinés de type Prato261
15.6 Domaines des chargements supportables de plates-bandes de type
Prato à joints verticaux, inclinés, et en X . . . . . . . . . . . . . . . . 262
15.7 Domaines des chargements supportables de plates-bandes de type
GAIA à joints verticaux, inclinés, et en X . . . . . . . . . . . . . . . . 262
15.8 Construction par l’intérieur du domaine des chargements supportables 263
15.9 Comparaison des domaines analytiques et numériques d’une plate-
bande à joints inclinés de type Prato . . . . . . . . . . . . . . . . . . 264
15.10 Comparaison des domaines analytiques et numériques d’une plate-
bande à joints inclinés de type GAIA . . . . . . . . . . . . . . . . . . 264
15.11 Comparaison des domaines analytiques et numériques d’une plate-
bande à joints en X de type Prato . . . . . . . . . . . . . . . . . . . . 265
15.12 Comparaison des domaines analytiques et numériques d’une plate-
bande à joints en X de type GAIA . . . . . . . . . . . . . . . . . . . . 265
15.13 Trois solutions équilibrant le même chargement vertical extrême W
si µ = ∞, avec diﬀérentes forces verticales dans les branches par-
tielles (0 kg, 500 kg et 2000 kg) ; solutions correspondant à la frontière
horizontale (a) sur ﬁg. 15.11 . . . . . . . . . . . . . . . . . . . . . . . . 266
15.14 Deux solutions équilibrant un chargement extrême si µ = ∞(H =
1600 kg à g. et H = 50 kg à d.) . . . . . . . . . . . . . . . . . . . . . . 266
15.15 Moment de torsion et surfaces mises en jeu par les forces verticales
dans les plates-bandes à joints en X . . . . . . . . . . . . . . . . . . . 267
15.16 Comparaison des domaines analytiques et numériques d’une plate-
bande à joints en X de type GAIA, avec limitation des eﬀorts dans
les branches partielles pour les domaines numériques . . . . . . . . . . 269
15.17 Blocs composant le modèle Cast3M pour la plate-bande de type
GAIA, avec blocs d’appuis en rouge . . . . . . . . . . . . . . . . . . . 271
15.18 Directions et intensités des résultantes des forces, vue de face et vue
de dessus, pour les solutions d’équilibre générées par Cast3M . . . . . 273

443

<!-- p. 445 -->

Table des ﬁgures

15.19 Contraintes normales sur les joints [ N/m2 ], pour les solutions d’équi-
libre générées par Cast3M . . . . . . . . . . . . . . . . . . . . . . . . 274
15.20 Déplacements [ m ], pour les solutions d’équilibre générées par Cast3M 275

16.1 Voûte plate à joints inclinés appareillée sur le plan du berceau (voûte
plate unidirectionnelle), vue assemblée (à g.) et éclatée (à d.) . . . . . 277
16.2 Voûte plate à joints inclinés appareillée sur le plan de la voûte en
arc-de-cloître (voûte plate bidirectionnelle), vue assemblée (à g.) et
éclatée (à d.) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 277
16.3 Voûte plate d’Abeille, vue assemblée (à g.) et éclatée (à d.) . . . . . . 278
16.4 Régularisation (a) et simpliﬁcation (b) de la découpe des claveaux . . 278
16.5 Appareil régularisé des voûtes plates uni- et bidirectionnelles, avant
et après simpliﬁcation par introduction de joints ﬁctifs . . . . . . . . 278
16.6 Forces horizontales (en bleu) et altitudes des nœuds d’appui (en
rouge), paramétrant l’équilibre des réseaux de forces . . . . . . . . . . 281
16.7 Forces verticales dans les branches partielles, paramétrant l’équilibre
des réseaux de forces . . . . . . . . . . . . . . . . . . . . . . . . . . . 282
16.8 Inﬂuence du raﬃnement du réseau (branches partielles) sur le domaine
des chargements supportables de la voûte bidirectionnelle . . . . . . . 283
16.9 Inﬂuence des polynômes de Lagrange sur le domaine des chargements
supportables de la voûte bidirectionnelle . . . . . . . . . . . . . . . . 284
16.10 Inﬂuence des polynômes de Lagrange sur le domaine des chargements
supportables de la voûte d’Abeille . . . . . . . . . . . . . . . . . . . . 285
16.11 Domaine des chargements supportables de la voûte unidirectionnelle
et déduction de celui de la voûte bidirectionnelle . . . . . . . . . . . . 286
16.12 Domaine des chargements supportables de la voûte bidirectionnelle . 288
16.13 Domaine des chargements supportables de la voûte bidirectionnelle . 288
16.14 Réseaux de forces correspondant à des chargements extrêmes de la
voûte bidirectionnelle, modèle Bi-C (avec raﬃnement) . . . . . . . . 289
16.15 Réseaux de forces correspondant à des chargements extrêmes de la
voûte bidirectionnelle, modèle Bi-A (sans raﬃnement) . . . . . . . . 290
16.16 Domaine des chargements supportables de la voûte d’Abeille . . . . . 291
16.17 Similitude des chargements extrêmes verticaux positifs et négatifs du
domaine des chargements supportables de la voûte d’Abeille . . . . . 292
16.18 Réseaux de forces correspondant à des chargements extrêmes de la
voûte d’Abeille, modèle Ab-XXIII . . . . . . . . . . . . . . . . . . . . 293
16.19 Directions et intensités des résultantes des forces, pour la solution
d’équilibre Sol1 générée par Cast3M (1) . . . . . . . . . . . . . . . . . 296
16.20 Directions et intensités des résultantes des forces, pour la solution
d’équilibre Sol1 générée par Cast3M (2) . . . . . . . . . . . . . . . . . 297
16.21 Contraintes normales sur les joints [ N/m2 ], pour la solution d’équi-
libre Sol1 générée par Cast3M . . . . . . . . . . . . . . . . . . . . . . 297
16.22 Déplacements [ m ], pour la solution d’équilibre Sol1 générée par Cast3M297

17.1 Bande inﬁnitésimale d’un escalier hélicoïdal, d’après García Ares (2007)299
17.2 Poussée minimale d’une bande inﬁnitésimale d’une voûte hélicoïdale,
comparaison entre réseaux de forces et méthode de García Ares (2007) 301

444

<!-- p. 446 -->

Table des ﬁgures

17.3 Voûte hélicoïdale, pour comparaison avec García Ares (2007) . . . . . 302
17.4 Poussées minimales d’une voûte hélicoïdale, pour comparaison avec
García Ares (2007) . . . . . . . . . . . . . . . . . . . . . . . . . . . . 303
17.5 Réseaux de forces d’une voûte hélicoïdale . . . . . . . . . . . . . . . . 304

A.1 Premiers architectes du roi . . . . . . . . . . . . . . . . . . . . . . . . 337
A.2 Professeurs d’architecture à l’Académie royale d’architecture . . . . . 337
A.3 Sujets des débats sur les plates-bandes à l’Académie royale d’architecture338
A.4 Mémoire de Bullet présenté à l’Académie le 14 janvier 1704, reproduit
dans Guettard (2012) . . . . . . . . . . . . . . . . . . . . . . . . . . . 338
A.5 Mémoire de La Hire présenté à l’Académie le 14 janvier 1704, repro-
duit dans Guettard (2012) . . . . . . . . . . . . . . . . . . . . . . . . 338
A.6 Mémoire de Bullet présenté à l’Académie le 30 juin 1710, reproduit
dans Guettard (2012) . . . . . . . . . . . . . . . . . . . . . . . . . . . 339

C.1 Axes adopted in the description of contact stresses and actions for
X-joints. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 419
C.2 First assumption on the contact stress ﬁeld for X-joints : grey surfaces
carry the limit compressive stress. . . . . . . . . . . . . . . . . . . . . 420

D.1 Instrumentation de la plate-bande à joints en X IA01 . . . . . . . . . 423
D.2 Évolution des déplacements verticaux δm en fonction de la charge
verticale centrée Q, pour la plate-bande IA01 lors des expériences
de mars 2017 (GAIA) . . . . . . . . . . . . . . . . . . . . . . . . . . . 424
D.3 Évolution de la tension F dans le tirant en fonction de la charge
verticale centrée Q, pour la plate-bande à joints en X (IA01) lors
des expériences de juin 2017 (Troyes) . . . . . . . . . . . . . . . . . . 425
D.4 Évolution de la tension F dans le tirant en fonction de la charge
verticale centrée Q, pour la plate-bande à joints en X réglés (IA02)
lors des expériences de juin 2017 (Troyes) . . . . . . . . . . . . . . . . 425

E.1 Mur horizontal construit suivant le principe des voûtes d’Abeille,
d’après Brocato et al. (2014) . . . . . . . . . . . . . . . . . . . . . . . 428

F.1 Systèmes de coordonnées utilisés pour la description des voussoirs . . 429

Les ﬁgures du catalogue des plates-bandes et des voûtes plates ne sont pas intégrées à cette table des ﬁgures.

Les photographies des plates-bandes et voûtes plates sont de l’auteur, sauf mention
contraire.

Les images (photographies, gravures etc.) tirées des bases de données en ligne de
la Médiathèque de l’architecture et du patrimoine (base Mémoire, base Mérimée et
base MédiatheK) sont référencées avec le nom de la base de donnée et le numéro de
cliché correspondant (p. ex. Base Mémoire 51L02355B). Ces images appartiennent
au Ministère de la Culture (France), Médiathèque de l’architecture et du patrimoine
(Centre de recherche des monuments historiques - CRMH).

445

<!-- p. 447 -->

Index

ablaq, 136, 157, 166, 371 coeﬃcient de sécurité, 33, 42
appareil, 27, 76, 134 géométrique, 47, 233
clavé, 74 statique, 44, 229
arasement, 87 contre-clé, 73
arc contre-ﬂèche, 126, 186
brisé, 81, 82, 97, 115, 185 contreclef, voir contre-clé
en anse-de-panier, 115, 185 contrefort, 38
en plein-cintre, 229, 239, 430 coupe des pierres, 73
segmentaire, 115, 185 couvrement, 87
surbaissé, 185 croisée, voir fenêtre
surhaussé, 185 crossette, 95, 120, 121
architrave, 87
arrière-linteau, 253 densité de force, 57
diagramme des forces, 65
biveau, 76 domaine des chargements potentiellebombement, voir contre-ﬂèche ment supportables, 30, 235
bossage, 134 douelle, voir panneau
dôme
centre de gravité, 429 elliptique, 83, 231, 247, 432
centre de pression, 22, 214 hémisphérique, 222, 223, 241, 247,
cercle de Mohr, 49 430
champ de contrainte statiquement ad-
missible, 29 encorbellement, 75
champ de vitesse cinématiquement ad- entablement, 180
missible, 29 équilatéral, 99, 102, 116, 118, 119, 427
chargement escalier
extrême, 30, 227 hélicoïdal, voir voûte hélicoïdale
potentiellement supportable, 30 suspendu, 39, 181
cheminée, 177 à jour, 181
clavage, 27, 74–76 état de charge, 95
claveau, 27, 73–75, 429 exhaussement, voir contre-ﬂèche
hauteur, 116 extrados, 87
nombre, 96
claver, 74, 75 fausse-coupe, 94, 152
clavettes, 96 double, 153, 385
clavé, 74, 75 simple, 153, 410
clef, voir clé faux-appareil, 134, 137
clé, 73, 96, 123 faux-manteau, 177
coeﬃcient de rupture, 32, 42 fenêtre, 115

446

<!-- p. 448 -->

Index

ﬁgure réciproque, 56, 65 droite, 118
ﬂèche (couvrement), 38 en fausse-coupe, voir fausse-coupe
fronton, 180 sous la tour ronde, 118
à claveaux en état de charge, 95
hotte, 177 à clavettes, voir clavettes
à deux rangs de claveaux, 90
intrados, 87
à joints courbes, 94, 136
à joints curvilignes, 94, 136joint, 74, 223
à joints en X, 94, 231 appareillé à crossette, voir cros-
à joints inclinés, 90 sette
à joints verticaux, 94, 98 de lit en coupe, 74
à double coupe, 92 à tenons, voir tenon
à lit brisé, 92 poids, 429
point d’application de la résultante des
Lagrange, voir polynôme actions de contact, voir centre
ligne de pression, 22, 49, 204 de pression
linteau, 87 point d’application de la résultante des
de fer, 132 forces, voir centre de pression
lit de carrière, 128 polygone
lit en coupe, voir joint des forces, 21
lune, 222, 224, 243 polygone funiculaire, 21, 48, 49, 204
polynôme, Lagrange, 227
manteau, 177 polyèdre, 63
mode de chargement, 30 pont, 39
multiplicateur de charge, 33, 42 portail, 176
méthode porte, 115
de De La Hire, 118 poussée
de proportion des saillies, 112 minimale, 285, 287, 299
des densités de forces, 56 principe
des divisions égales, 112, 250, 279 d’inclinaison, 98, 152
des réseaux de forces, 61 de normalité, 74, 80, 98, 116, 152,
du centre de convergence, 111 240
pôle du cercle de Mohr, 49
nœud d’appui, 221

refend, 114, 134optimisation, 227
remplage, 39
panneau, 73, 76 rose, 39
de coupe, 73 règle
de douelle, 73 du « 1 pour 1 », 106, 427
de lit, 73 du « 1 pour 2 », 99, 104
de tête, 73 du « 1 pour 3 », 99, 104, 118
pierre sèche, 39 du « 1 pour 4 », 116, 427
plafond, 185 du triangle équilatéral, voir équiplate-bande, 87 latéral
biaise, 118 réseau
courbe, 88 de forces, 206
de fer, 132 de masse, 63

447

<!-- p. 449 -->

Index

funiculaire, 206 à la Roussillon, 200
projeté, 63 à la Volterra, 201

sauterelle, 76
soﬃte, 87
sommier, 73
stéréotomie, 24, 73

taille
par dérobement, 76
par panneaux, 76, 78
par ravalement, 76
par équarissement, 78
par équarrissement, 76
à la perche, 76
tenon, 96, 120
tour, 38
trait, 73
à preuve, 78
triangle équilatéral, voir équilatéral

volume, 429
voussoir, 27, 73, 75, 429
voûte
appareillée, 74
bloquée au mortier, 74
catalane, 201
clavée, 74
d’Abeille, 196, 433
d’arêtes bombée, 186
d’arêtes plate, 186
déprimée, 185, 186, 189
elliptique, voir dôme
en arc de cloître, 38
en berceau plein-cintre, 430
en blocage, 74
en encorbellement, 75
en éventail, 38
hélicoïdale, 299, 433
plate, 185, 433
plate clavée, 189
plate dallée, 188
sarrasine, 39, 62, 201
segmentaire, 185
sphérique, voir dôme
surbaissée, 185, 198
à arêtes doubles, 185
à l’impériale, 200

448

<!-- p. 450 -->

Index des auteurs

Acocella (2004), 346, 347, 453 Block (2009), 39, 56, 58, 62, 69, 205,
Adam (1989), 75, 89, 350, 453 206, 211, 217, 220, 299, 305,
Adam (2012), 129, 170, 172, 345, 350, 454
453 Blondel et Patte (1777a), 81, 90, 92, 96,
Adhémar (1845), 92, 96, 104, 108, 111, 104, 108, 132, 152, 153, 177,
122, 123, 128, 325, 453 181, 192, 319, 320, 455
Aita (2003), 80, 81, 453 Blondel et Patte (1777b), 198, 201, 455
Alberti (1485), 252, 453 Blondel (1675), 87, 96, 103, 108, 134,
Araguas (1999), 200, 453 310, 455
Association ouvrière des Compagnons Blondel (1752), 81, 115, 116, 154, 162,
du devoir (1996), 92, 99, 100, 165, 189, 319, 455
109, 118, 119, 121, 123, 125– Blondel (1754), 394, 397, 455
127, 154, 333, 453 Blondel (1756), 160, 455
Association ouvrière des Compagnons Bosse (1643), 78, 455
du devoir (2001), 125, 127, Bouticourt (2008), 143, 455
131, 189, 192, 453 Bouticourt (2016), 143, 455
Bélidor (1729), 103, 108, 109, 118, 134, Breymann (1849), 23, 455
196, 313, 454 Brocato et Mondardini (2014), 196,
Bannister (1968), 200, 201, 453 197, 208, 250, 251, 279, 456
Baratta et Corbi (2013), 39, 453 Brocato et al. (2014), 427, 428, 455
Barré et Barré (1896), 120, 453 Cejka (1978), 83, 94, 97, 121, 136, 137,
Barthel et al. (2003), 39, 453 172, 176, 345, 456
Bauchal (1887), 196, 454 Chaix (1890), 81, 82, 92, 93, 95, 96, 98,
Bazin (1888), 81, 82, 98, 99, 330, 454 99, 104, 108, 120–123, 331, 456
Becchi (2012), 98, 118, 309, 454 Choisy (1873), 75, 170, 346–349, 456
Bechmann (1993), 87, 177–180, 333, Choisy (1899a), 75, 128, 170, 171, 332,
361, 364, 365, 454 346, 456
Benouville (1888), 180, 329, 454 Choisy (1899b), 81, 82, 97, 456
Benvenuto (1991), 22, 335, 454 Ciblac et Fantin (2015), 245, 456
Benvenuto (2006), 23, 334, 454 Ciblac et Fantin (2016), 65, 220, 245,
Bienvenu (2013), 125, 133, 336, 454 456
Bleyer (2015), 306, 454 Ciblac et Morel (2014), 29, 456
Block et Lachauer (2014a), 38, 56, 454 Ciblac (2008), 35, 456
Block et Lachauer (2014b), 56, 62, 67, Claudel et Laroque (1850), 120, 129,
69, 454 325, 456
Block et Ochsendorf (2007), 16, 37, 55, Coccia et al. (2016), 241–243, 456
56, 305, 455 Cojannot (2011), 391, 456
Block et Ochsendorf (2008), 56, 455 Colas (2009), 39, 456

449

<!-- p. 451 -->

Index des auteurs

Como (2013), 39, 456 Diot (2011), 181, 370, 459
Conan (2015), 178, 364, 457 Douliot (1825), 92, 95, 96, 104, 108,
Conti et al. (2012), 349, 457 111, 120–123, 125, 127, 324,
Coope (1959), 373, 457 459
Coope (1972), 373, 374, 457 Dupuit (1870), 22, 23, 26, 27, 83, 459
Cremona (1872), 56, 457 Durand-Claye (1880), 23, 246, 459
Culmann (1864), 21, 22, 56, 204, 457 Durm (1885), 83, 175, 345, 348, 349,
Culmann (1875), 22, 34, 457 351, 459
Culmann (1880), 21–23, 204, 457 Eddy (1877), 36, 459
D’Amato et Fallacara (2005), 78, 80, Enlart (1927), 176, 177, 332, 354–356,
457 459
D’Aviler (1691), 73, 81, 88, 89, 103, Félibien (1676), 88, 153, 310, 459
108, 115, 116, 132, 152–154, Fleury (2009), 426, 459
311, 312, 457 Fleury (2010), 143, 459
D’Ayala et Tomasoni (2008), 37, 457 Foce (2007), 239, 459
Díaz et Mozo (2012), 165, 196, 198, Fontaine (1987), 389, 460
426, 457 Fournet (2011), 172, 346, 349, 460
DeLaine (1990), 170, 172, 346, 458 Frézier (1737), 77, 79, 81–83, 259, 313,
Delbecq (1982), 199, 458 460
Delbecq (1983), 37–39, 43, 44, 47, 217, Frézier (1738), 73, 77, 79, 87, 95, 96,
458 98, 99, 103–106, 108, 109, 111,
Denfer (1891), 133, 332, 458 112, 119, 121–123, 125–127,
Derand (1643), 73, 77, 79, 189, 192, 133, 152–154, 159, 172, 193,
199, 310, 458 198, 250, 279, 287, 314–316,
Desargues (1640), 77, 78, 458 460
Descat (1997), 401, 458 Frézier (1739), 77, 79, 460
Desgodets (1682), 170, 171, 458 Fraternali (2010), 56, 460
Desgodets (1719), 116, 458 Gady (2002), 404, 460
De Goes et al. (2013), 56, 457 Gady (2005), 156, 157, 379, 460
De La Hire (1688), 77, 79, 457 Gallon (1735), 106, 196, 197, 280, 460
De La Hire (1712), 73, 103, 108, 118, García Ares (2007), 18, 39, 299, 301–
312, 457 303, 433, 460
De La Rue (1728), 77, 79, 458 García Ares (2011), 39, 300, 460
De l’Orme (1561), 129, 133, 308, 458 Gauthey (1843), 121, 199, 460
De l’Orme (1567), 77, 87, 96, 102, 129, Gautier (1717), 95, 103, 108, 119, 120,
133, 181, 309, 458 122, 312, 460
Dhombres (1992), 81–83, 321, 458 Gerstner (1831), 22, 460
Diderot et d’Alembert (1751), 185, 317, Gil et al. (2010), 38, 56, 461
458 Guettard (2012), 338, 339, 461
Diderot et d’Alembert (1756), 81, 90, Heyman (1966), 33, 34, 37, 38, 461
95, 152–154, 317, 459 Heyman (1967a), 33, 35, 38, 241–243,
Diderot et d’Alembert (1765a), 73, 90, 461
104, 106, 109, 122, 317, 459 Heyman (1967b), 33, 38, 461
Diderot et d’Alembert (1765b), 106, Heyman (1969), 17, 47, 238, 239, 461
108, 109, 185, 189, 190, 198, Heyman (1992), 38, 461
317, 318, 459 Heyman (1995), 33, 47, 48, 239, 461
Diot (2007), 177, 459 Heyman (2002), 39, 461

450

<!-- p. 452 -->

Index des auteurs

Heyman (2009), 24, 26, 239, 240, 461 Moseley (1843a), 22, 23, 26, 464
Hillairet (1997), 134, 461 Moseley (1843b), 22, 464
Huerta Fernández et Aroca Hernández- Motro (2009), 143, 372, 464
Ros (1989), 27, 461 Nollet (2012), 87, 97, 102, 125, 181,
Huerta Fernández (2010), 245, 461 335, 336, 464
Huerta Fernández (2012), 121, 461 O’Dwyer (1999), 16, 36, 37, 48, 49, 55,
Jeanneret (2012), 130, 131, 342, 461 56, 61, 62, 69, 205, 217, 305,
Jousse (1642), 77, 78, 87, 89, 103, 108, 464
117, 462 Ochsendorf et al. (2004), 38, 464
Julien (2010), 395, 462 Ochsendorf (2002), 35, 38, 239, 464
Juttet (2005), 163, 406, 407, 409, 410, Oikonomopoulou (2009), 29, 239, 464
462 Olivier (1983), 128, 464
Kamovska-Monnereau (2004), 116, Pérouse de Montclos (1982), 73, 75–
169, 462 78, 81, 159, 165, 185, 188, 192,
Kamovska-Monnereau (2006), 116, 193, 199, 200, 312, 334, 411,
169, 391, 392, 462 416, 465
Kooharian (1953), 33, 462 Pérouse de Montclos (1994), 377, 378,
Laget (1998), 394, 462 404, 405, 465
Lalbat et al. (1987), 77, 462 Pérouse de Montclos (1995), 129, 180,
Lalbat et al. (1989), 77, 462 333, 465
Lampariello (2012), 136, 143, 177, 258, Pérouse de Montclos (2007), 74, 75, 87,
371, 462 90, 92, 94–96, 185, 186, 364,
Lau (2006), 35, 36, 38, 241, 242, 431, 465
462 Palladio (1570), 116, 137, 138, 464
Lemonnier (1915), 336, 462 Patte (1769), 92, 95, 103, 104, 108, 126,
Le Camus de Mézières (1786), 133, 321, 127, 131, 132, 155, 192, 194,
464 320, 369, 464
Le Muet (1623), 312, 462 Paze-Mazzi (2015), 138, 464
Losserand (2017a), 130, 413, 463 Perrault (1673), 81, 101, 102, 464
Losserand (2017b), 200, 415, 463 Petzet (2012), 130, 465
Méry (1840), 22, 23, 29, 34, 464 Pillet (1888), 84, 331, 465
Majowiecki (1994), 61, 463 Planat (1888a), 336, 465
Makris et Alexakis (2013), 239, 240, Planat (1888b), 123, 170, 172, 329, 465
242, 463 Planat (1888c), 174, 465
Marcu Istrate (2008), 372, 463 Planat (1888d), 124, 347, 350, 465
Marmo et Rosati (2017), 39, 217, 299, Quatremère de Quincy (1825), 89, 128,
305, 463 154, 465
Mathonière (2016), 324, 463 Quicherat (1886), 172, 176, 328, 465
Maxwell (1864), 56, 463 Raguenet (1915a), 142, 465
Mesqui (1988), 362, 364, 365, 463 Raguenet (1915b), 362, 363, 466
Middleton (1987), 130, 463 Rankine (1858), 245, 466
Mignot (1991), 97, 463 Reese (2008), 38, 466
Mignot (2004), 134, 401, 403, 463 Reveyron (1993), 176, 180, 352, 353,
Milankovitch (1904), 239, 240, 463 364, 365, 466
Mondardini (2015), 270, 463 Reynaud (1867), 134, 327, 466
Monduit (1889), 92, 104, 106, 108, 114, Rippmann et al. (2012), 56, 466
122, 127, 134, 328, 329, 464 Rippmann (2016), 56, 81, 83, 466

451

<!-- p. 453 -->

Index des auteurs

Rivoalen (1888), 180, 329, 466 Tibières (2012), 89, 129, 130, 154, 158,
Roland Le Virloys (1770a), 96, 132, 162, 165, 180, 335, 396, 468
321, 466 Tiercelet (1728), 81, 96, 116, 122, 123,
Roland Le Virloys (1770b), 132, 321, 152, 154, 312, 313, 468
466 Timoshenko (1953), 20–22, 49, 468
Rondelet (1802), 131, 466 Tomasoni (2008), 37, 38, 469
Rondelet (1804), 92, 94, 98, 99, 108, Ungewitter et Mohrmann (1901), 37,
109, 120–122, 125, 155, 169, 469
170, 186, 187, 323, 324, 345– Viel (1805), 162, 323, 469
347, 349–351, 466 Villemus (2004), 39, 469
Rondelet (1805), 80, 101, 102, 252, 466 Viollet-Le-Duc (1858), 81, 97, 177, 178,
Rondelet (1828), 93, 109, 117, 172, 325, 469
173, 186, 187, 345–347, 349– Viollet-Le-Duc (1859a), 89, 362, 363,
351, 466 469
Rondelet (1834), 109, 172, 324, 345– Viollet-Le-Duc (1859b), 81, 172, 177,
347, 349–351, 467 326, 354, 469
Ruskin (1849), 95, 371, 467 Viollet-Le-Duc (1860a), 326, 327, 365–
Sakarovitch (1992), 77, 80, 83, 84, 321, 367, 469
322, 334, 467 Viollet-Le-Duc (1860b), 326, 360, 361,
Sakarovitch (1998), 75–78, 80, 82, 309, 469
334, 467 Viollet-Le-Duc (1863), 81, 82, 126, 327,
Sakarovitch (2006), 426, 467 469
Salençon (1983), 29, 31, 33, 42, 43, 467 Viollet-Le-Duc (1864), 134, 176, 326,
Sanchini (2013), 354, 467 469
Sauvaget (1950), 166, 467 Viré-Gaillard (2011), 200, 414, 416, 469
Sauval (1724a), 159, 198, 311, 467 Vouga et al. (2012), 56, 470
Sauval (1724b), 198, 311, 467 Wolfe (1921), 36, 470
Sauval (1724c), 391, 467 Zessin (2012), 38, 241, 242, 470
Savot (1624), 133, 309, 467 de Maillet (2012), 196, 413, 463
Scamozzi (1615), 129, 467 di Teodoro (2012), 181, 252, 468
Schek (1974), 37, 56, 58, 59, 61, 467 di Vesme (1968), 163, 469
Serlio (1537), 87, 96, 100–102, 104, 117, el Wakil (2009), 196, 470
252, 308, 467
Simonin (1792), 104, 106, 107, 113,
127, 143, 145, 152–154, 321,
468
Smars (2000), 35, 37, 38, 45, 468
Smars (2008), 261, 468
Sollazzo et Marzano (1988), 50, 51, 468
Speiser et Wimmel (2012), 176, 468
Ström (2011), 392, 468
Tamboréro et Sakarovitch (2010), 77,
468
Tamboréro (2008), 78, 468
Tamboréro (2010), 200, 468
Tamboréro (2013), 78, 79, 468
Tarrío (2015), 27, 468

452

<!-- p. 454 -->

Bibliographie

Acocella, A. 2004, L’architettura di pietra : antichi e nuovi magisteri costruttivi,
Alinea Editrice.

Adam, J.-P. 1989, La construction romaine : matériaux et techniques, Picard, Paris.

Adam, J.-P. 2012, «Structures horizontales dans la Rome antique : du linteau à la
plate-bande», dans L’architrave, le plancher, la plate forme : Nouvelle histoire de
la construction, PPUR, p. 67–76.

Adhémar, J. 1845, Traité de la coupe des pierres, Carilian - Goewry et V. Dalmont,
Paris. URL https//catalog.hathitrust.org/Record/011613083.

Aita, D. 2003, «Between geometry and mechanics : A re-exarnination of the prin-
ciples of stereotomy frorn a statical point of view», dans Proceedings of the ﬁrst
international congress on construction history, Madrid, p. 161–170.

Alberti, L. B. 1485, De re aediﬁcatoria, N. di Lorenzo, Florence. URL http://
architectura.cesr.univ-tours.fr/Traite/Notice/ENSBA_20A4.asp?param=.

Araguas, P. 1999, «Voûte à la Roussillon», Butlletí de la Reial Acadèmia Catalana
de Belles Arts de Sant Jordi, vol. 13, p. 173–185. URL http://www.raco.cat/
index.php/ButlletiRACBASJ/article/download/219285/329803.

Association ouvrière des Compagnons du devoir. 1996, La maçonnerie et la
pierre de taille, Encyclopédie des métiers, vol. 3, Librairie du Compagnonnage,
Paris.

Association ouvrière des Compagnons du devoir. 2001, La maçonnerie et la
pierre de taille, Encyclopédie des métiers, vol. 7, Librairie du Compagnonnage,
Paris.

Bannister, T. C. 1968, «The Roussillon Vault : The Apotheosis of a "Folk"
Construction», Journal of the Society of Architectural Historians, vol. 27, no 3,
p. 163–175.

Baratta, A. et I. Corbi. 2013, «Equilibrium models for helicoidal laterally sup-
ported staircases», Computers & Structures.

Barré, P. et L. Barré. 1896, Memento de l’architecte et de l’entrepreneur. Théorie
pratique et législation du bâtiment, E. Bernard, Paris. URL http://gallica.bnf.
fr/ark:/12148/bpt6k58247805.

453

<!-- p. 455 -->

Bibliographie

Barthel, R., L. Schiemann et M. Jagfeld. 2003, «Static analysis and evaluation
of the construction system of a gothic "choir-window" consisting of a ﬁligree tracery
and slender stone rips», dans Proceedings of the ﬁrst international congress on
construction history, Madrid, p. 333–340.

Bauchal, C. 1887, Nouveau dictionnaire biographique et critique des architectes
français, Paris, André, Daly ﬁls et cie. URL http://archive.org/details/
nouveaudictionna00baucuoft.

Bazin, C. 1888, «Coupe des pierres», dans Encyclopédie de l’architecture et de la
construction - Volume IV, partie 1 : CO - ES, édité par P. Planat, Librairie de
la construction moderne, Paris, p. 36–41. URL http://www.purl.org/yoolib/
inha/8431.

Becchi, A. 2012, «Ut unum sint : poutres, arcs, plates-bandes», dans L’architrave, le
plancher, la plate forme : Nouvelle histoire de la construction, PPUR, p. 329–340.

Bechmann, R. 1993, Villard de Honnecourt - La pensée technique au XIIIe siècle et
sa communication, Picard, Paris.

Benouville, L. 1888, «Fenêtre», dans Encyclopédie de l’architecture et de la
construction - Volume IV, partie 2 : ES - GO, édité par P. Planat, Librairie de
la construction moderne, p. 473–488. URL http://www.purl.org/yoolib/inha/
\8432.

Benvenuto, E. 1991, An introduction to the history of structural mechanics - Part
II : Vaulted structures and elastic systems, vol. 2, Springer-Verlag, New York.

Benvenuto, E. 2006, La scienza delle costruzioni e il suo sviluppo storico, 2e éd.,
Edizioni di storia e letteratura, Roma.

Bienvenu, G. 2013, De l’architecte voyer à l’ingénieur en chef des services tech-
niques : les services d’architecture et d’urbanisme de la ville de Nantes du XVIIIe
siècle au XXe siècle, Paris 1. URL http://www.theses.fr/2013PA010607.

Bleyer, J. 2015, Méthodes numériques pour le calcul à la rupture des struc-
tures de génie civil, thèse de doctorat, Université Paris-Est. URL https://tel.
archives-ouvertes.fr/tel-01259958/document.

Bélidor, B. F. d. 1729, La Science des ingénieurs dans la conduite des travaux
de fortiﬁcation et d’architecture civile - Livres I à III, C. Jombert, Paris. URL
http://gallica.bnf.fr/ark:/12148/bpt6k6566066p.

Block, P. 2009, Thrust Network Analysis : exploring three-dimensional equilibrium,
thèse de doctorat, Massachusetts Institute of Technology, Dept. of Architecture.
URL http://dspace.mit.edu/handle/1721.1/49539.

Block, P. et L. Lachauer. 2014a, «Three-Dimensional (3d) Equilibrium Analysis
of Gothic Masonry Vaults», International Journal of Architectural Heritage, vol. 8,
no 3, p. 312–335.

454

<!-- p. 456 -->

Bibliographie

Block, P. et L. Lachauer. 2014b, «Three-dimensional funicular analysis of ma-
sonry vaults», Mechanics Research Communications, vol. 56, p. 53–60.

Block, P. et J. Ochsendorf. 2007, «Thrust network analysis : a new methodology
for three-dimensional equilibrium», Journal of the International Association for
Shell and Spatial Structures, vol. 48, no 3, p. 167–173.

Block, P. et J. Ochsendorf. 2008, «Lower-bound analysis of masonry vaults»,
dans Proceedings of the 6th International Conference on Structural Analysis of
Historical Construction. Bath, UK. URL http://block.arch.ethz.ch/sites/
research_group/files/pdf/publications/block_ochs_SAHC_2008.pdf.

Blondel, F. 1675, Cours d’architecture enseigné dans l’Académie royale d’archi-
tecture, P. Auboin et F. Clouzier, Paris. URL http://gallica.bnf.fr/ark:
/12148/bpt6k85661p.

Blondel, J.-F. 1752, Architecture françoise, ou Recueil des plans, élévations, coupes
et proﬁls des églises, maisons royales, palais, hôtels & édiﬁces les plus considérables
de Paris, vol. 1, Charles-Antoine Jombert, Paris. URL http://gallica.bnf.fr/
ark:/12148/bpt6k108033j.

Blondel, J.-F. 1754, Architecture françoise, ou Recueil des plans, élévations, coupes
et proﬁls des églises, maisons royales, palais, hôtels & édiﬁces les plus considérables
de Paris, vol. 3, Charles-Antoine Jombert, A Paris. URL http://gallica.bnf.
fr/ark:/12148/bpt6k1080325.

Blondel, J.-F. 1756, Architecture françoise, ou Recueil des plans, élévations, coupes
et proﬁls des églises, maisons royales, palais, hôtels & édiﬁces les plus considérables
de Paris, vol. 4, Charles-Antoine Jombert, A Paris. URL http://gallica.bnf.
fr/ark:/12148/bpt6k1080359.

Blondel, J.-F. et P. Patte. 1777a, Cours d’architecture, ou Traité de la décoration,
distribution & construction des bâtiments, vol. 5, Veuve Desaint, Paris. URL http:
//books.google.fr/books?id=weFIAQAAIAAJ.

Blondel, J.-F. et P. Patte. 1777b, Cours d’architecture, ou Traité de la décoration,
distribution & construction des bâtiments, vol. 6, Desaint, Paris. URL http://
gallica.bnf.fr/ark:/12148/bpt6k85705g.

Bosse, A. 1643, La pratique du trait a preuves, de Mr Desargues Lyonnois, Pierre
Des Hayes, Paris. URL http://architectura.cesr.univ-tours.fr/Traite/
Notice/MBAT1950-7-1.asp.

Bouticourt, E. 2008, «Les origines médiévales d’une technique de charpente : la
poutre armée», Archéologie du midi médiéval, , no 26, p. 145–165.

Bouticourt, E. 2016, Charpentes méridionales : Construire autrement, Editions
Honoré Clair, Arles.

Breymann, G. A. 1849, Bauconstructionslehre Vol 1 Constructionen in Stein, Hoﬀ-
mann’sche Verlags-Buchhandlung, Stuttgart. URL http://www.e-rara.ch/zut/
content/titleinfo/8642550.

455

<!-- p. 457 -->

Bibliographie

Brocato, M., W. Deleporte, L. Mondardini et J.-E. Tanguy. 2014, «A pro-
posal for a new type of prefabricated stone wall», International Journal of Space
Structures, vol. 29, no 2, p. 97–112.

Brocato, M. et L. Mondardini. 2014, «Parametric analysis of structures from ﬂat
vaults to reciprocal grids», International Journal of Solids and Structures.

Cejka, J. 1978, Tonnegewölbe und Bögen islamischer Architektur - Wölbungstechnik
und Form, thèse de doctorat, Technische Universität München, Munich.

Chaix, J. 1890, Traité de coupe des pierres, H. Chairgrasse ﬁls, Paris. URL http:
//gallica.bnf.fr/ark:/12148/bpt6k872986p.

Choisy, A. 1873, L’art de bâtir chez les Romains, Ducher et Cie, Paris. URL http:
//www.augustechoisy2009.net/pdfs/Choisy_1883_TEXTE.pdf.

Choisy, A. 1899a, Histoire de l’architecture, vol. 1, Gauthier-Villars, Paris. URL
http://www.augustechoisy2009.net/.

Choisy, A. 1899b, Histoire de l’architecture, vol. 2, Gauthier-Villars, Paris. URL
http://www.augustechoisy2009.net/.

Ciblac, T. 2008, «Structure computation tools in architectural design. Teaching
experimentations», dans Actes de la conference eCAADe 2008, p. 275–281.

Ciblac, T. et M. Fantin. 2015, «Rediscovering Durand-Claye’s method using force
network method implemented for construction history», dans Proceedings of the
ﬁfth international congress on construction history, Chicago.

Ciblac, T. et M. Fantin. 2016, «Analyse de la stabilité des dômes maçonnés à l’aide
de la méthode des réseaux de forces», dans Les temps de la construction. Processus,
acteurs, matériaux., édité par F. Fleury, L. Baridon, A. Mastrorilli, R. Mouterde
et N. Reveyron, A. et J. Picard, Vaulx-en-Velin, p. 1167–1178.

Ciblac, T. et J.-C. Morel. 2014, Maçonneries durables - comportement mécanique
et modélisation des structures, Lavoisier : Hermès science publications, Paris.

Claudel, J. et L. Laroque. 1850, Pratique de l’art de construire - Maçonnerie,
Carilian-Goeury et V. Dalmont, Paris. URL http://www.google.fr/books?id=
zygOb89Ro1MC.

Coccia, S., M. Como et F. Di Carlo. 2016, «Minimum thrust and minimum
thickness of hemispherical masonry domes», Acta Mechanica, vol. 227, no 9, p.
2415–2425.

Cojannot, A. 2011, Louis Le Vau et les nouvelles ambitions de l’architecture fran-
çaise (1634-1654), Thèse de doctorat, Université Paris-Sorbonne, Paris.

Colas, A.-S. 2009, Mécanique des murs de soutènement en pierre sèche : modé-
lisation par le calcul à la rupture et expérimentation échelle 1, thèse de docto-
rat, Ecole Nationale des Travaux Publics de l’Etat, Vaulx-en-Velin. URL http:
//bibli.ec-lyon.fr/exl-doc/acolas.pdf.

456

<!-- p. 458 -->

Bibliographie

Como, M. 2013, Statics of historic masonry constructions, Springer, Berlin ; New
York.

Conan, S. 2015, «Flat arches with joggle joints», dans Proceedings of the ﬁfth inter-
national congress on construction history, Chicago.

Conti, C., G. Martines et A. Sinopoli. 2012, «L’arc droit dans les bâtiments
de la Rome antique, de Sylla à Hadrien», dans L’architrave, le plancher, la plate
forme : Nouvelle histoire de la construction, PPUR, p. 77–85.

Coope, R. 1959, «The Chateau of Montceaux-en-Brie», Journal of the Warburg and
Courtauld Institutes, vol. 22, no 1/2, p. 71.

Coope, R. 1972, Salomon de Brosse and the development of the classical style in
French architecture from 1565 to 1630, Pennsylvania State University.

Cremona, L. 1872, Le ﬁgure reciproche nella statica graﬁca, G. Bernardoni, Milan.

Culmann, K. 1864, Die graphische Statik, Meyer & Zeller, Zürick.

Culmann, K. 1875, Die graphische Statik, 2e éd., Meyer & Zeller (A . Reimann),
Zürick. URL http://archive.org/details/diegraphischest01culmgoog.

Culmann, K. 1880, Traité de statique graphique, Dunod, Paris. URL http://
archive.org/details/traitedestatiqu00culmgoog.

D’Amato, C. et G. Fallacara. 2005, «Tradition et innovation dans le pro-
jet/construction d’architecture : rôle des ‘modèles’ et actualité de la stéréotomie»,
dans L’arte della stereotomia. I Compagnons du Devoir e le meraviglie della cos-
truzione in pietra, Verona, p. 52–89.

D’Aviler, A.-C. 1691, Cours d’architecture qui comprend les ordres de Vignole, Ni-
colas Langlois, Paris. URL http://architectura.cesr.univ-tours.fr/Traite/
Notice/ENSBA_LES223.asp?param=.

D’Ayala, D. F. et E. Tomasoni. 2008, «The structural behaviour of masonry
vaults : Limit state analysis with ﬁnite friction», dans Proceedings of the 6th In-
ternational Conference Structural Analysis of Historical Construction (SAHC),
p. 3–19. URL http://iscarsah.icomos.org/content/articles_by_members/
DAyala_SAHC_2008.pdf.

Díaz, E. R. et A. L. Mozo. 2012, «Les joints occultes sur plates-bandes et voûtes
plates en Espagne», dans L’architrave, le plancher, la plate forme : Nouvelle histoire
de la construction, PPUR, p. 288–295.

De Goes, F., P. Alliez, H. Owhadi et M. Desbrun. 2013, «On the equilibrium
of simplicial masonry structures», ACM Transactions on Graphics, vol. 32, no 4.
URL http://hal.inria.fr/hal-00826280/.

De La Hire, P. 1688, Traité de la coupe des pierres, non publié, Paris.

457

<!-- p. 459 -->

Bibliographie

De La Hire, P. 1712, «Sur la construction des voûtes dans les édiﬁces», Mémoires
de mathématique et de physique de l’Académie royale des sciences. URL https:
//hal.archives-ouvertes.fr/ads-00121784/document.

De La Rue, J. B. 1728, Traité de la coupe des pierres, où par une méthode facile &
abrégée : l’on peut aisément se perfectionner en cette science, Imprimerie royale.

De l’Orme, P. 1561, Nouvelles inventions pour bâtir à petits frais, F. Morel, Paris.
URL http://architectura.cesr.univ-tours.fr/Traite/Textes/Masson643.
pdf.

De l’Orme, P. 1567, Le premier tome de l’architecture, F. Morel, Paris. URL http:
//architectura.cesr.univ-tours.fr/Traite/Notice/ENSBA_Les1653.asp.

DeLaine, J. 1990, «Structural experimentation : The lintel arch, corbel and tie in
western Roman architecture», World Archaeology, vol. 21, no 3, p. 407–424.

Delbecq, J.-M. 1982, «Les ponts en maçonnerie - Constitution et stabilité», cahier
de recherche, Ministère des transports - SETRA, Paris. URL http://catalogue.
setra.fr/document.xsp?id=Dtrf-0000487&qid=sdx_q0&n=5&q=.

Delbecq, J.-M. 1983, Analyse de la stabilité des ponts en maçonnerie par la théorie
du calcul à la rupture, thèse de doctorat, Ecole nationale des ponts et chaussées,
Paris.

Denfer, J. 1891, Architecture et constructions civiles. Maçonnerie, vol. 1, Gauthier-
Villars (Paris). URL http://gallica.bnf.fr/ark:/12148/bpt6k910571.

Derand, F. 1643, L’architecture des voûtes, ou l’art des traits, et coupes des
voûtes, Sebastien Cramoisy, Paris. URL http://memoirevive.besancon.fr/ark:
/48565/a011290090127uw1226.

Desargues, G. 1640, Brouillon project d’exemple d’une maniere universelle... tou-
chant la practique du trait a preuves pour la coupe des pierres en l’architecture...,
n.c., Paris.

Descat, S. 1997, «Les travaux de Pierre-Louis Moreau pour la fabrique Saint-
Eustache dans la seconde moitié du XVIIIe siècle», Bulletin Monumental, vol. 155,
no 3, p. 207–230. URL http://www.persee.fr/doc/bulmo_0007-473x_1997_
num_155_3_914000.

Desgodets, A. 1682, Les édiﬁces antiques de Rome dessinés et mesurés très exac-
tement, J.-B. Coignard, Paris. URL http://bibliotheque-numerique.inha.fr/
collection/4696-les-edifices-antiques-de-rome-dessines/?lang=fr.

Desgodets, A. 1719, Traité des ordres d’architecture. URL http://architectura.
cesr.univ-tours.fr/Traite/Notice/Desgodets1719.asp.

Dhombres, J. 1992, L’École normale de l’an III : leçons de mathématiques, Dunod,
Paris. URL http://books.openedition.org/editionsulm/442.

458

<!-- p. 460 -->

Bibliographie

Diderot, D. et J. d’Alembert. 1751, «Arc», URL https://fr.wikisource.org/
wiki/L%E2%80%99Encyclop%C3%A9die/1re_%C3%A9dition/ARC.

Diderot, D. et J. d’Alembert. 1756, «Fausse coupe», URL https:
//fr.wikisource.org/wiki/L%E2%80%99Encyclop%C3%A9die/1re_%C3%
A9dition/FAUSSE-COUPE.

Diderot, D. et J. d’Alembert. 1765a, «Plate-bande», URL https:
//fr.wikisource.org/wiki/L%E2%80%99Encyclop%C3%A9die/1re_%C3%
A9dition/PLATE-BANDE.

Diderot, D. et J. d’Alembert. 1765b, «Voûte», URL http://fr.wikisource.
org/wiki/L%E2%80%99Encyclop%C3%A9die/1re_%C3%A9dition/VO%C3%9BTE.

Diot, M. 2007, Cheminées : Étude de structures du Moyen Âge au XVIIIe siècle,
Centre des monuments nationaux.

Diot, M. 2011, Escaliers, Étude de structure : Du XIIe au XVIIIe siècle, Editions
du Patrimoine – Centre des monuments nationaux.

Douliot, J. P. 1825, Traité spécial de coupe des pierres, Carilian-Goeury, Paris.
URL http://books.google.fr/books?id=BqUJAAAAIAAJ.

Dupuit, J. 1870, Traité de l’équilibre des voutes et de la construction des ponts en
maçonnerie, Dunod, Paris. URL http://gilbert.aq.upm.es/.

Durand-Claye, A. 1880, «Vériﬁcation de la stabilité des voûtes et des arcs -
application aux voûtes sphériques», Annales des ponts et chaussées. URL http:
//gallica.bnf.fr/ark:/12148/cb34348188q/date.

Durm, J. 1885, Handbuch der Architektur - Die Baukunst der Etrusker, die Baukunst
der Römer, Diehl, Darmstadt.

Eddy, H. T. 1877, New constructions in graphical statics, D. Van Nostrand, New
York. URL http://archive.org/details/newconstruction00eddygoog.

Enlart, C. 1927, Manuel d’archéologie française depuis les temps mérovingiens jus-
qu’à la Renaissance - I. Architecture religieuse Tome 1, 3e éd., Auguste Picard,
Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k364918.

Fleury, F. 2009, Réﬂexions épistémologiques, historiques et pédagogiques sur l’usage
des modèles de mécanique des structures dans le champ de l’architecture, Mémoire
hdr, Université Paris-Est Marne-la-Vallée.

Fleury, F. 2010, «Les idées sous-jacentes à la conception de la voûte plate perpen-
diculaire», dans Ediﬁces & artiﬁces, Picard, Paris, p. 283–291.

Félibien, A. 1676, Des Principes de l’architecture, de la sculpture, de la peinture
et des autres arts qui en dépendent, avec un dictionnaire des termes propres à
chacun de ces arts, J.-B. Coignard, Paris. URL http://gallica.bnf.fr/ark:
/12148/btv1b86268296.

459

<!-- p. 461 -->

Bibliographie

Foce, F. 2007, «Milankovitch’s Theorie der Druckkurven : Good mechanics for ma-
sonry architecture», Nexus Network Journal, vol. 9, no 2, p. 185–210.

Fontaine, P. 1987, Journal (1799-1853), École nationale supérieure des beaux-arts,
Institut français d’architecture, Société de l’histoire de l’art français, Paris.

Fournet, T. 2011, «Trois curiosités architecturales des bains de Taposiris Ma-
gna (Égypte) : voûte à crossettes, radiateur et dalle clavée», Revue archéologique,
p. 323–347. URL http://www.cairn.info/resume.php?ID_ARTICLE=ARCH_112_
\0323.

Fraternali, F. 2010, «A thrust network approach to the equilibrium problem of
unreinforced masonry vaults via polyhedral stress functions», Mechanics Research
Communications, vol. 37, no 2, p. 198–204.

Frézier, A. 1737, Théorie et pratique de la coupe des pierres et des bois pour la
construction des voûtes et autres parties des bâtiments civils et militaires - Tome 1,
vol. 1, Guerin, Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k856861.

Frézier, A. 1738, Théorie et pratique de la coupe des pierres et des bois pour la
construction des voûtes et autres parties des bâtiments civils et militaires - Tome 2,
vol. 2, Jombert, Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k85687c.

Frézier, A. 1739, Théorie et pratique de la coupe des pierres et des bois pour la
construction des voûtes et autres parties des bâtiments civils et militaires - Tome 3,
vol. 3, Jombert, Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k85688q.

Gady, A. 2002, Le Marais : guide historique et architectural, Le Passage, Paris.

Gady, A. 2005, Jacques Lemercier : Architecte et ingénieur du Roi, Maison des
Sciences de l’Homme, Paris.

Gallon. 1735, Machines et inventions approuvées par l’Académie royale des sciences
depuis son établissement avec leur description - Tome 1 (1666-1701), Martin, Coi-
gnard, Guerin, Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k3471s.

García Ares, J. A. 2007, «Un enfoque para el análisis límite de las escaleras de
fábrica helicoidales», dans Actas del quinto congreso nacional de historia de la
construcción, Burgos, p. 335–343. URL http://oa.upm.es/3958/.

García Ares, J. A. 2011, «Una nueva solución de equilibrio para el análisis límite
de helicoides de fábrica con óculo central como los construidos por guastavino»,
dans VII Congreso Nacional de Historia de la Construcción, p. 469–477. URL
http://oa.upm.es/9812/.

Gauthey, E. 1843, Traité de la construction des ponts, vol. 1, 3e éd., Leduc, Liège.
URL http://gilbert.aq.upm.es/.

Gautier, H. 1717, Dissertation sur l’epaisseur des culées des ponts, sur la largeur
des piles, sur la portée des voussoirs, sur l’eﬀort et la pesanteur des arches à dif-
ferens surbaissemens..., André Cailleau, Paris. URL http://cnum.cnam.fr/CGI/
redire.cgi?8RESLE18.2.

460

<!-- p. 462 -->

Bibliographie

Gerstner, F. 1831, Hanbuch der Mechanik, Johann Spurny, Prague. URL http:
//dx.doi.org/10.3931/e-rara-20206.

Gil, L., P. Roca et A. Andreu. 2010, «Analysis of masonry structures by funicular
networks», Proceedings of the ICE - Engineering and Computational Mechanics,
vol. 163, no 3, p. 147–154.

Guettard, A. 2012, «Variantes de la plate-bande de De l’Orme», dans L’architrave,
le plancher, la plate forme : Nouvelle histoire de la construction, PPUR, p. 392–397.

Heyman, J. 1966, «The stone skeleton», International Journal of Solids and Struc-
tures, vol. 2, no 2, p. 249–256.

Heyman, J. 1967a, «On shell solutions for masonry domes», International Journal
of Solids and Structures, vol. 3, no 2, p. 227–241.

Heyman, J. 1967b, «Spires and fan vaults», International Journal of Solids and
Structures, vol. 3, no 2, p. 243–257.

Heyman, J. 1969, «The safety of masonry arches», International Journal of Mecha-
nical Sciences, vol. 11, no 4, p. 363–385.

Heyman, J. 1992, «Leaning towers», Meccanica, vol. 27, no 3, p. 153–159.

Heyman, J. 1995, The Stone Skeleton : Structural Engineering of Masonry Archi-
tecture, Cambridge University Press.

Heyman, J. 2002, «Rose Windows», dans New Approaches to structural mechanics,
shells and biological structures, Kluwer Academic Publishers, Dordrecht, p. 165–
\177.

Heyman, J. 2009, «La coupe des pierres», dans Proceedings of the Third International
Congress on Construction History, Cottbus, p. 807–812. URL http://www.bma.
arch.unige.it/ENGL/engl_proceedings_construction_history.html.html.

Hillairet, J. 1997, Dictionnaire historique des rues de Paris, Les éditions de Minuit,
Paris.

Huerta Fernández, S. 2010, «Designing by geometry. rankine’s theorems of trans-
formation of structures.», dans Geometría y proporción en las estructuras. En-
sayos en honor de Ricardo Aroca, Lampreave, p. 263–285. URL http://oa.upm.
es/4368/.

Huerta Fernández, S. 2012, «Wedges and plate-bandes : mechanical theories after
De la Hire», dans L’architrave, le plancher, la plate forme : Nouvelle histoire de la
construction, PPUR, p. 405–435.

Huerta Fernández, S. et R. Aroca Hernández-Ros. 1989, «Masonry Domes :
A study on proportion and similarity», dans Proceedings of IASS 30th anniversary
world congress, vol. 1, Madrid. URL http://oa.upm.es/1278/.

461

<!-- p. 463 -->

Bibliographie

Jeanneret, L. 2012, «En quête de vérité : le cas de la plate-bande», dans L’archi-
trave, le plancher, la plate forme : Nouvelle histoire de la construction, PPUR, p.
465–479.

Jousse, M. 1642, Le secret d’architecture découvrant ﬁdèlement les traits géo-
métriques, couppes et dérobemens nécessaires dans les bastiments, G. Griveau,
La Flèche. URL http://architectura.cesr.univ-tours.fr/Traite/Notice/
ENSBA_LES1251.asp.

Julien, P. 2010, «Façade de la cathédrale Notre-Dame de l’Assomption», dans
Jules Hardouin-Mansart : 1646-1708, édité par A. Gady, Maison des Sciences de
l’Homme, Paris, p. 466–467.

Juttet, F. 2005, Chambéry : Lecture d’une ville. Patrimoine, architecture, urba-
nisme, Comp’act Editions, Chambéry.

Kamovska-Monnereau, M. 2004, Le portail dans l’architecture privée parisienne
entre 1700 et 1750, Mémoire de Master 1, Université Paris-Sorbonne, Paris.

Kamovska-Monnereau, M. 2006, Le portail dans l’architecture privée parisienne
au XVIIe siècle, Mémoire de Master 2, Université Paris-Sorbonne, Paris.

Kooharian, A. 1953, «Limit analysis of voussoir (segmental) and concrete arches»,
dans Proceedings - American Concrete Institute, vol. 49, Detroit, Michigan, p. 317–
\328.

Laget, P.-L. 1998, «L’amphithéâtre d’anatomie de la communauté des chirur-
giens de Paris sis rue des Cordeliers», Bulletin Monumental, vol. 156, no 4, p.
369–384. URL http://www.persee.fr/web/revues/home/prescript/article/
bulmo_0007-473x_1998_num_156_4_1836000.

Lalbat, C., G. Margueritte et J. Martin. 1987, «De la stéréotomie médiévale :
la coupe des pierres chez Villard de Honnecourt (I)», Bulletin Monumental, vol.
145, no 4, p. 387–406.

Lalbat, C., G. Margueritte et J. Martin. 1989, «De la stéréotomie médiévale :
la coupe des pierres chez Villard de Honnecourt (II)», Bulletin Monumental, vol.
147, no 1, p. 11–34. URL http://www.persee.fr/web/revues/home/prescript/
article/bulmo_0007-473x_1989_num_147_1_4678.

Lampariello, B. 2012, «Le système de la plate-bande en Italie», dans L’architrave,
le plancher, la plate forme : Nouvelle histoire de la construction, PPUR, p. 101–109.

Lau, W. W. 2006, Equilibrium analysis of masonry domes, Master thesis, Massa-
chusetts Institute of Technology. URL http://dspace.mit.edu/handle/1721.1/
\34984.

Le Muet, P. 1623, Manière de bastir pour toutes sortes de personnes, Melchior
Tauernier. URL http://books.google.fr/books?id=kP5PAAAAcAAJ.

462

<!-- p. 464 -->

Bibliographie

Lemonnier, H. 1915, «Cinquante années de l’Académie Royale d’Architecture (1671-
1726)», Journal des savants, vol. 13, no 10, p. 445–460. URL http://www.persee.
fr/doc/jds_0021-8103_1915_num_13_10_4453.

Losserand, L. 2017a, Les chantiers d’églises paroissiales à Paris au XVIIe et XVIIIe
siècle, Thèse de doctorat, Université Paris-Sorbonne, Paris.

Losserand, L. 2017b, «L’hôtel-Dieu de Carpentras à travers ses archives (1750-
1769)», In Situ. Revue des patrimoines, , no 31. URL http://insitu.revues.
org/13941.

de Maillet, A. 2012, «Le succès des planchers de Serlio, Wallis et Abeille», dans
L’architrave, le plancher, la plate forme : Nouvelle histoire de la construction,
PPUR, p. 350–362.

Majowiecki, M. 1994, Tensostrutture - progetto e veriﬁca, Edizioni CREA.

Makris, N. et H. Alexakis. 2013, «The eﬀect of stereotomy on the shape of the
thrust-line and the minimum thickness of semicircular masonry arches», Archive of
Applied Mechanics, vol. 83, no 10, p. 1511–1533.

Marcu Istrate, D. 2008, «The Roman Catholic Cathedral and the Bishop’s Palace
of Alba Iulia - the 2000-2002 Archaeological Research», cahier de recherche.

Marmo, F. et L. Rosati. 2017, «Reformulation and extension of the thrust network
analysis», Computers & Structures, vol. 182, p. 104–118.

Mathonière, J.-M. 2016, «Jean-Paul Douliot (1788-1834), compagnon passant
tailleur de pierre, professeur d’architecture et auteur du Cours élémentaire, pra-
tique et théorique de construction», dans Les temps de la construction. Processus,
acteurs, matériaux., édité par F. Fleury, L. Baridon, A. Mastrorilli, R. Mouterde
et N. Reveyron, A. et J. Picard, Vaulx-en-Velin, p. 163–173.

Maxwell, J. C. 1864, «On reciprocal ﬁgures and diagrams of forces», Philosophical
Magazine, vol. 27, no 182, p. 250–261.

Mesqui, J. 1988, Ile-de-France gothique 2. L’architecture seigneuriale., Picard, Paris.

Middleton, R. 1987, «Des architectes qui imitent les ingénieurs - La question des
linteaux armés au XVIIIème siècle», dans L’idée constructive en architecture - Actes
du colloque de 1984 à Grenoble, Picard, Paris, p. 119–135.

Mignot, C. 1991, Le Muet : architecte (1591-1669), Thèse de doctorat, Université
Paris 4.

Mignot, C. 2004, Grammaire des immeubles parisiens : Six siècles de façades du
Moyen Âge à nos jours, Parigramme.

Milankovitch, M. 1904, Beitrag zur Theorie der Druckkurven, thèse de doctorat,
K.K. technische Hochschule, Vienne.

463

<!-- p. 465 -->

Bibliographie

Mondardini, L. 2015, Contribution au développement des structures en pierre de
taille : modélisation, optimisation et outils de conception, thèse de doctorat, Uni-
versité Paris-Est. URL http://www.theses.fr/2015PESC1084.

Monduit, L. 1889, Traité théorique et pratique de la stéréotomie au point de vue de
la coupe des pierres, Juliot.

Moseley, H. 1843a, The mechanical principles of engineering and architecture,
Longman, Brown, Green and Longmans, London.

Moseley, H. 1843b, «On the Theory of the Arch», On the Theory, Practice, and
Architecture of Bridges, vol. 1.

Motro, R. 2009, «An approach to structural morphology», dans An anthology of
structural morphology, World Scientiﬁc Publishing, Singapore, p. 15–32.

Méry, E. 1840, «Equilibre des voûtes en berceau», Annales des ponts et chaussées,
p. 51–70. URL http://gallica.bnf.fr/ark:/12148/cb34348188q/date.

Le Camus de Mézières, N. 1786, Le guide de ceux qui veulent bâtir, vol. 1, Morin,
Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k6557721j.

Nollet, M. 2012, «Plates-bandes françaises et inventions de De l’Orme», dans L’ar-
chitrave, le plancher, la plate forme : Nouvelle histoire de la construction, PPUR,
p. 280–287.

Ochsendorf, J., J. I. Hernando et S. Huerta. 2004, «Collapse of masonry but-
tresses», Journal of architectural engineering, p. 88–97.

Ochsendorf, J. A. 2002, Collapse of Masonry Structures, thèse de doctorat, King’s
College, Cambridge.

O’Dwyer, D. 1999, «Funicular analysis of masonry vaults», Computers & structures,
vol. 73, no 1-5, p. 187–197.

Oikonomopoulou, A. 2009, Approches numériques pour l’étude du comportement
des structures maçonnées anciennes : un outil basé sur le calcul à la rupture et
la visualisation graphique, thèse de doctorat, Université Paris-Est ENSA Paris La
Villette, Paris. URL http://tel.archives-ouvertes.fr/tel-00493588/fr/.

Olivier, A. 1983, «Sommiers de plates-bandes appareillées et armées à Conimbriga
et à la Villa d’Hadrien à Tivoli», Mélanges de l’Ecole française de Rome. Anti-
quité, vol. 95, no 2, p. 937–959. URL http://www.persee.fr/web/revues/home/
prescript/article/mefr_0223-5102_1983_num_95_2_1396.

Palladio, A. 1570, I quattro libri dell’architettura, Domenico De Franceschi, Venise.

Patte, P. 1769, Mémoires sur les objets les plus importans de l’architecture, Rozet,
Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k5701519t.

Paze-Mazzi, O. 2015, L’Hôtel d’Uzès – XVIIIe XIXe siècle, Mémoire de Master 2,
Université Paris-Sorbonne, Paris.

464

<!-- p. 466 -->

Bibliographie

Perrault, C. 1673, Les dix livres d’architecture de Vitruve, corrigez et traduits
nouvellement en françois avec des notes et des ﬁgures, J.-B. Coignard, Paris. URL
http://gallica.bnf.fr/ark:/12148/bpt6k85660b.

Petzet, M. 2012, «Perrault et l’architrave armée», dans L’architrave, le plancher,
la plate forme : Nouvelle histoire de la construction, PPUR, p. 376–384.

Pillet, J. 1888, «Appareil», dans Encyclopédie de l’architecture et de la construc-
tion - Volume I, partie 1 : AB - AR, édité par P. Planat, Librairie de la construc-
tion moderne, Paris, p. 195–198. URL http://bibliotheque-numerique.inha.
fr/collection/8425-encyclopedie-de-l-architecture-et-de-la/?n=1.

Planat, P. 1888a, «Académie royale d’architecture», dans Encyclopédie de l’archi-
tecture et de la construction - Volume I, partie 1 : AB - AR, Librairie de la construc-
tion moderne, Paris, p. 34–37. URL http://bibliotheque-numerique.inha.fr/
collection/8425-encyclopedie-de-l-architecture-et-de-la/?n=1.

Planat, P. 1888b, «Construction», dans Encyclopédie de l’architecture et de la
construction - Volume III, partie 2 : CI - CO, Librairie de la construction
moderne, Paris, p. 447–588. URL http://bibliotheque-numerique.inha.fr/
collection/8430-encyclopedie-de-l-architecture-et-de-la/?n=6.

Planat, P. 1888c, Encyclopédie de l’architecture et de la construc-
tion - Volume I, partie 2 : AR, Librairie de la construction moderne,
Paris. URL http://bibliotheque-numerique.inha.fr/collection/
8426-encyclopedie-de-l-architecture-et-de-la/?n=2.

Planat, P. 1888d, Encyclopédie de l’architecture et de la construction -
Volume III, partie 2 : CI - CO, Librairie de la construction mo-
derne, Paris. URL http://bibliotheque-numerique.inha.fr/collection/
8430-encyclopedie-de-l-architecture-et-de-la/?n=6.

Pérouse de Montclos, J.-M. 1982, L’architecture à la française : du milieu du
XVe à la ﬁn du XVIIIe siècle, Picard, Paris.

Pérouse de Montclos, J.-M. 1994, Le guide du Patrimoine : Paris, Direction du
Patrimoine C.N.M.H.S.

Pérouse de Montclos, J.-M. 1995, Histoire de l’architecture : de la Renaissance
à la Révolution, vol. 2, Mengès, Paris.

Pérouse de Montclos, J.-M. 2007, Architecture : méthode et vocabulaire, 6e éd.,
Impr. nationale : Ed. du patrimoine, Paris.

Quicherat, J.-É. 1886, Mélanges d’archéologie et d’histoire, Alphonse Picard, Paris.
URL http://gallica.bnf.fr/ark:/12148/bpt6k36495n.

Quatremère de Quincy, A. 1825, «Plate-bande», URL http://gallica.bnf.fr/
ark:/12148/bpt6k85720c.

465

<!-- p. 467 -->

Bibliographie

Raguenet, A. 1915a, Matériaux et documents d’architecture et de sculpture, classés
par ordre alphabétique, vol. 6, G. Broes Van Dort Co., Chicago. URL http://
archive.org/details/materialsdocumen06unse.

Raguenet, A. 1915b, Matériaux et documents d’architecture et de sculpture, classés
par ordre alphabétique, vol. 5, G. Broes Van Dort Co., Chicago. URL http://
archive.org/details/materialsdocumen05unse.

Rankine, W. J. M. 1858, A manual of applied mechanics, Griﬃn, London.

Reese, M. L. 2008, Structural analysis and assessment of Guastavino vaulting,
Master thesis, Massachusetts Institute of Technology, Dept. of Architecture. URL
http://dspace.mit.edu/handle/1721.1/44748.

Reveyron, N. 1993, «Les structures clavées non-extradossées dans l’architecture
romane et gothique (XIIe-XIIIe siècles)», Bulletin Monumental, vol. 151, no 4, p.
553–589. URL http://www.persee.fr/web/revues/home/prescript/article/
bulmo_0007-473x_1993_num_151_4_3408.

Reynaud, L. 1867, Traité d’architecture - Première Partie - Art de Batir, vol. 1,
3e éd., Dalmont et Dunod, Paris. URL http://gallica.bnf.fr/ark:/12148/
bpt6k5741692d.

Rippmann, M. 2016, Funicular Shell Design : Geometric Approaches to Form Fin-
ding and Fabrication of Discrete Funicular Structures, thèse de doctorat, ETH
Zurich, Department of Architecture, Zurich.

Rippmann, M., L. Lachauer et P. Block. 2012, «Interactive vault design», In-
ternational Journal of Space Structures, vol. 27, no 4, p. 219–230. URL http:
//block.arch.ethz.ch/brg/publications/260.

Rivoalen, E. 1888, «Porte», dans Encyclopédie de l’architecture et de la construc-
tion - Volume VI, partie 1 : NA-RE, édité par P. Planat, Librairie de la construc-
tion moderne, Paris, p. 255–267. URL http://bibliotheque-numerique.inha.
fr/collection/8435-encyclopedie-de-l-architecture-et-de-la/?n=11.

Roland Le Virloys, C. F. 1770a, Dictionnaire d’architecture, civile, militaire et
navale - Tome second, vol. 2, Libraires Associés, Paris. URL http://www.purl.
org/yoolib/inha/11749.

Roland Le Virloys, C. F. 1770b, Dictionnaire d’architecture, civile, militaire et
navale - Tome troisième, vol. 3, Libraires Associés, Paris. URL http://www.purl.
org/yoolib/inha/11750.

Rondelet, J. 1802, Traité théorique et pratique de l’art de bâtir - Tome 1 Livre 1,
chez l’auteur, Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k86635c.

Rondelet, J. 1804, Traité théorique et pratique de l’art de bâtir - Tome 2 Livres 3 et
4, chez l’auteur, Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k86636q.

Rondelet, J. 1805, Traité théorique et pratique de l’art de bâtir - Tome 3 Livre 5,
chez l’auteur, Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k866372.

466

<!-- p. 468 -->

Bibliographie

Rondelet, J. 1828, Art de bâtir - Planches, chez l’auteur, Paris. URL http://digi.
ub.uni-heidelberg.de/diglit/rondelet1828planches.

Rondelet, J. 1834, Traité théorique et pratique de l’art de bâtir - Tome 2 Livres 3
et 4, 7e éd., Firmin Didot frères, Paris.

Ruskin, J. 1849, The seven lamps of architecture, 1re éd., Smith, Elder, & Co.,
London.

Sakarovitch, J. 1992, «La coupe des pierres et la géométrie descriptive», dans
L’École normale de l’an III : leçons de mathématiques, édité par J. Dhombres,
Dunod, Paris, p. 530–540. URL http://books.openedition.org/editionsulm/
\442.

Sakarovitch, J. 1998, Epures d’architecture : de la coupe des pierres à la géométrie
descriptive XVIe-XIXe siècles, Birkhäuser, Basel ; Boston.

Sakarovitch, J. 2006, «Construction History and Experimentation», dans Procee-
dings of the second international congress on construction history, Cambridge, p.
2777–2791.

Salençon, J. 1983, Calcul à la rupture et analyse limite, Presses de l’École Nationale
des Ponts et Chaussées, Paris.

Sanchini, V. 2013, Progetto e costruzione di piattabande in pietra da taglio. I casi di
Saint-Etienne a Beauvais e Saint-Pierre-Saint-Paul a Villers-Saint-Paul., Mémoire
de Master, Università di Bologna.

Sauvaget, J. 1950, «La madrasa ’Âdiliya», dans Les monuments Ayyoubides de
Damas, Études arabes, médiévales et modernes, Presses de l’Ifpo, Beyrouth, p.
77–92. URL http://books.openedition.org/ifpo/3804.

Sauval, H. 1724a, Histoire et recherches des antiquités de la ville de Paris, vol. 2,
Charles Moette & Jacques Chardon, Paris. URL http://archive.org/details/
histoireetrecher02sauv.

Sauval, H. 1724b, Histoire et recherches des antiquités de la ville de Paris, vol. 1,
Charles Moette & Jacques Chardon, Paris. URL http://archive.org/details/
histoireetrecher01sauv.

Sauval, H. 1724c, Histoire et recherches des antiquités de la ville de Paris, vol. 3,
Charles Moette & Jacques Chardon, Paris. URL http://archive.org/details/
histoireetrecher03sauv.

Savot, L. 1624, L’architecture françoise des bastimens particuliers, Sesbastien Cra-
moisy, Paris. URL http://gallica.bnf.fr/ark:/12148/bpt6k85642d.

Scamozzi, V. 1615, L’idea della architettura universale, Venise. URL architectura.
cesr.univ-tours.fr/Traite/Notice/Scamozzi1615.asp.

Schek, H.-J. 1974, «The force density method for form ﬁnding and computation
of general networks», Computer Methods in Applied Mechanics and Engineering,
vol. 3, no 1, p. 115–134.

467

<!-- p. 469 -->

Bibliographie

Serlio, S. 1537, Regole generali di architetura, F. Marcolini, Venise. URL http:
//architectura.cesr.univ-tours.fr/Traite/Notice/B272296201_A101.asp.

Simonin. 1792, Traité élémentaire de la coupe des pierres ou Art du trait, Basset,
Paris. URL http://books.google.com.br/books?id=tDMVAAAAQAAJ.

Smars, P. 2000, Études sur la stabilité des arcs et voûtes - confrontation des méthodes
de l’analyse limite aux voûtes gothiques en Brabant, thèse de doctorat, Université
Catholique de Louvain, Leuven. URL http://smars.yuntech.edu.tw/phd/phd_
f.html.

Smars, P. 2008, «Notes on the inﬂuence of friction and tensile resistance on the
stability of masonry arches», dans Proceedings of the 6th International Conference
Structural Analysis of Historical Construction, p. 1–8.

Sollazzo, A. et S. Marzano. 1988, Elementi di meccanica dei continui e resistenza
dei materiali, no 2 dans Scienza delle costruzioni, Utet, Torino.

Speiser, P. et R. Wimmel. 2012, «Éléments horizontaux dans l’architecture des
pays islamiques», dans L’architrave, le plancher, la plate forme : Nouvelle histoire
de la construction, PPUR, p. 92–100.

Ström, M. 2011, Paris en détails : Le Marais, Le Studiolo, Michel de Maule.

Tamboréro, L. 2008, De Delorme à de La Hire, la recherche d’une méthode univer-
selle dans les traités de stéréotomie. Opérations géométriques et emprunts., thèse
de doctorat, EHESS, Paris. URL http://www.researchgate.net/profile/Luc_
Tamborero/.

Tamboréro, L. 2010, «La voûte de l’hôtel de ville d’Arles. Approche historique et
technique du chantier (1673-1677)», dans Ediﬁces & artiﬁces, Picard, Paris.

Tamboréro, L. 2013, «Le traité de la coupe des pierres», dans Philippe de la Hire
1640-1718 Entre architecture et sciences, Picard, Paris, p. 191–202.

Tamboréro, L. et J. Sakarovitch. 2010, «La voûte de l’hôtel de ville d’Arles», .

Tarrío, I. 2015, «The Buttressing System in Pol Abraham’s Criticism of Viollet-Le-
Duc’s Theories», dans Proceedings of the ﬁfth international congress on construc-
tion history, Chicago.

di Teodoro, F. P. 2012, «Plates-bandes, planchers en poteries et poutres composées
de Léonard», dans L’architrave, le plancher, la plate forme : Nouvelle histoire de
la construction, PPUR, p. 188–193.

Tibières, C. 2012, «La coupe des pierres dans les plates-bandes», dans L’architrave,
le plancher, la plate forme : Nouvelle histoire de la construction, PPUR, p. 363–375.

Tiercelet, A.-C. 1728, Architecture moderne ou L’art de bien bâtir pour
toutes sortes de personnes : tant pour les maisons des particuliers que pour
les palais, vol. 1, C. Jombert, Paris. URL https://archive.org/details/
architecturemode01jomb.

468

<!-- p. 470 -->

Bibliographie

Timoshenko, S. 1953, History of strength of materials, McGraw-Hill, New York.

Tomasoni, E. 2008, Le volte in muratura negli ediﬁci storici : tecniche cos-
truttive e comportamento strutturale, PhD thesis, Università degli Studi di
Trento. URL http://www.unitn.it/files/download/9646/phd_thesis_elide_
tomasoni_-_ciclo_xx.pdf.

Ungewitter, G. G. et K. Mohrmann. 1901, Lehrbuch der gotischen Konstruktio-
nen, vol. 1, 4e éd., Tauchnitz, Leipzig. URL http://books.google.fr/books?id=
SksAAAAAYAAJ.

di Vesme, A. B. 1968, Schede Vesme - L’arte in Piemonte dal XVI al XVIII secolo
\- N-Z, vol. 3, Società Piemontese di archeologia e belle arti.

Viel, C.-F. 1805, De l’impuissance des mathématiques pour assurer la solidité des
bâtimens , et Recherches sur la construction des ponts, Tilliard et ﬁls, Paris. URL
http://gallica.bnf.fr/ark:/12148/bpt6k6529022b.

Villemus, B. 2004, Étude des murs de soutènement en maçonnerie de pierres sèches,
thèse de doctorat, Institut National des Sciences Appliquées de Lyon. URL http:
//theses.insa-lyon.fr/publication/2004ISAL0015/these.pdf.

Viollet-Le-Duc, E. 1858, «Appareil», URL https://fr.wikisource.org/wiki/
Dictionnaire_raisonn%C3%A9_de_l%E2%80%99architecture_fran%C3%A7aise_
du_XIe_au_XVIe_si%C3%A8cle/Appareil.

Viollet-Le-Duc, E. 1859a, «Cheminée», URL https://fr.wikisource.org/
wiki/Dictionnaire_raisonn%C3%A9_de_l%E2%80%99architecture_fran%C3%
A7aise_du_XIe_au_XVIe_si%C3%A8cle/Chemin%C3%A9e.

Viollet-Le-Duc, E. 1859b, «Claveau», URL https://fr.wikisource.org/wiki/
Dictionnaire_raisonn%C3%A9_de_l%E2%80%99architecture_fran%C3%A7aise_
du_XIe_au_XVIe_si%C3%A8cle/Claveau.

Viollet-Le-Duc, E. 1860a, «Construction – Civiles», URL https:
//fr.wikisource.org/wiki/Dictionnaire_raisonn%C3%A9_de_l%E2%
80%99architecture_fran%C3%A7aise_du_XIe_au_XVIe_si%C3%A8cle/
Construction_--_Civiles.

Viollet-Le-Duc, E. 1860b, «Cuisine», URL http://fr.wikisource.org/wiki/
Dictionnaire_raisonn%C3%A9_de_l%E2%80%99architecture_fran%C3%A7aise_
du_XIe_au_XVIe_si%C3%A8cle/Corniche.

Viollet-Le-Duc, E. 1863, «Meneau», URL https://fr.wikisource.org/wiki/
Dictionnaire_raisonn%C3%A9_de_l%E2%80%99architecture_fran%C3%A7aise_
du_XIe_au_XVIe_si%C3%A8cle/Meneau.

Viollet-Le-Duc, E. 1864, «Plate-bande», URL https://fr.wikisource.org/
wiki/Dictionnaire_raisonn%C3%A9_de_l%E2%80%99architecture_fran%C3%
A7aise_du_XIe_au_XVIe_si%C3%A8cle/Plate-bande.

469

<!-- p. 471 -->

Bibliographie

Viré-Gaillard, B. 2011, Les Franque : une dynastie d’architectes avignonnais au
XVIIIe siècle, Thèse de doctorat, Université Paris-Sorbonne, Paris.

Vouga, E., M. Höbinger, J. Wallner et H. Pottmann. 2012, «Design of self-
supporting surfaces», ACM Transactions on Graphics (TOG), vol. 31, no 4, p. 87.

el Wakil, L. 2009, «"Cet homme nous fut envoyé par le ciel pour rénover l’archi-
tecture égarée depuis des siècles" Relecture de quelques cas genevois», Études de
lettres, , no 1, p. 35–56. URL http://edl.revues.org/523.

Wolfe, W. S. 1921, Graphical analysis - a text book on graphic statics, 1re éd.,
McGraw-Hill book company, New York. URL http://archive.org/details/
graphicalanalysi00wolfrich.

Zessin, J. F. 2012, Collapse analysis of unreinforced masonry domes and curving
walls, thèse de doctorat, Massachusetts Institute of Technology, Dept. of Architec-
ture. URL http://dspace.mit.edu/handle/1721.1/70879.

470
