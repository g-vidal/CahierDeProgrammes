# CahierISNEtICN

Utilisation de Jupyter / Jupyterhub pour enseigner l'algorithmique et le codage sans avoir recours à une interface météo. 

## ISN ICN et "//Météo climat Tremplin pour l'enseignement des sciences//"

Le dispositif "meteo et climat : tremplin pour l'enseignement des sciences" s'appuie sur l'utilisation de nano-ordinateurs, d'objets connectés et de capteurs météorologiques pour enseigner le codage. Au cours des travaux il est apparu que les enseignants de mathématiques ne souhaitaient pas utiliser la météo comme support d'apprentissage mais étaient intéressés par l'adoption des outils logiciels d'apprentissage Jupyter et Jupyterhub. De même l'exploitation d'une RaspberryPi ou d'un edison comme système d'intermédiation n'a pas été adopté par tous ce qui a conduit à proposer cet ensemble de cahiers jupyter ne faisant pas appel à des capteurs météo et étant indépendants d'une installation sur RaspberryPi ou Edison si l'usager le souhaite; ils restent bien sûr compatibles avec l'utilisation d'une RaspBerryPi ou d'un Edison comme serveur mobile de classe ou objet connecté..

Les cahiers de ce dossier ont pour objectif d'assurer une formation pour des enseignants de mathématiques 

## Contenu des cahiers 

 * Un cahier qui exploite le module Geopy : Objectif, générer une table ou un fichier qui permette quand on travaille avec des établissments de créer la ressource pour faire un shapefile dans QGIS.
Deux fichiers sont liés à ce cahier : lieux.csv et lieux.db
 * Un cahier qui présente la syntaxe markdown : le markdown est un langage non balisé qui permet une lecture directe aisée en texte seul et produit un formattage de type HTML quand il est interprété. Ce cahier évite le passage par la page  ["anti-sèche" de github](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), le va et vient entre "ressource en ligne" et "cahier" ne semblant pas aller de soi pour certains des usagers testeurs.
 * Un cahier exemple Latex. Un des avantages de jupyter et jupyterhub est d'embarquer un interpréteur laTeX qui permet d'insérer dans les blocs de texte du laTeX qui fournit des formules en mode vectoriel (et ps des images)
 * Un Cahier lié au projet de l'académie d'Amiens : PythonEdu. Pour montrer l'intérêt de Jupyterhub le Chapitre 1 de PythonEdu a été reproduit,le fichier lycee.py est un module qui contient les fonctions utilisées par PythonEdu.
