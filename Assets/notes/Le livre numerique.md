# Le livre numérique, et si c'était du web ?

* Ne pas s'avancer sur l'historique si je ne le maitrise pas
* NCX : en cours de déprécation, ne pas hésiter à l'"oublier"
* Walrus Kadath

## Introduction

## Le livre numérique

(Montrer une liseuse)
Expliquer que le livre numérique est une version électronique du livre papier
Différents devices

Il existe plusieurs formats, mais les 2 principaux sont ePub et PDF.

* Mobi, Azw, Lrf, Lit, doc, txt et les autres
	* MobiPocket/AZW : format Kindle
	* LRF : Sony eReader

Actuellement, l'ePub est le format le plus utilisé, et c'est donc sur ce dernier que nous allons nous concentrer.

## La base	

* EPub
	* Généralités
		* electronic publication
		* Géré par IDPF (International Digital Publishing Forum)
		* Crée en 2006
		* Basé sur les normes W3C
	* Format
		* ePub est une archive Zip dont l'extension est .epub
		* l'archive contient un site web (arborescence de fichiers HTML, CSS, et images)
		* Plusieurs métadonnées
			* Fichier OPF
			* Fichier MIMETYPE
			* Dossier META-INF

* => Donner un exemple d'ePub décompressé
	* Décompresser livre pour voir le contenu
	* Expliquer l'équivalent index.html => fichier OPF 
* // avec le .jar

## Les convergences

* L'ePub utilise les technologies web standard : HTML / CSS / Javascript
* Liens dans le texte (aide, carte, navigation)
* Dans la version actuelle, la v2, l'ePub est surtout prévu pour du contenu textuel
	* Adaptable sur tout support
	* Permet une personnalisation, bien que limitée

## Les perspectives

* Le format ePub3 apporte toute la modernité de HTML5/CSS3 au livre numérique (SVG, Javascript, MathML)
* Sortir de l'équivalent numérique du format papier, mais sortir de réelles créations
	* Intégrer des animations
	* Intégrer des vidéos/sons
	* Ajouter des animations pour raconter le texte  (http://www.ebouquin.fr/2010/09/13/moving-tales-le-livre-anime-prend-son-envol/)
	* Focus sur l'accessibilité
		* Plus de possibilité de description de contenu, moins de contenus non accessible
		* Possibilité de synchroniser le son avec la lecture (braille)
	
## Les raisons d'avoir un format propre

* Il existe 2 grands moteurs de rendus pour l'ePub : ARM (Adobe Reader Mobile) et WebKit
* Ils ont été construits spécifiquement pour le rendu d'eBook, donc avec quelques intégrations propres
	* Métadonnées du livre
	* Navigation propre

## Les "avertissements"

* Ne pas refaire l'erreur de la "multi-standardisation" (penser à utiliser http://xkcd.com/927/)
	* Exemple de Kindles avec le AZW 
	
