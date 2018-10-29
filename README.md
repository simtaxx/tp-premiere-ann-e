* Helene Mry
* Sarah Gungor
* wilem djennane
* haris sci
* younes Elhamdani
* ness ness
* maeva benzina
* baptiste painot-lapeyre
* carlo Berni
* doriane farau
* amelie hl
* Nastasia dotlic
* rayan adamczak
* arthur barré
* xavier mvdz
* Julian Romana
* ines dlmx
* amanda tan
* feriel maddi
* anouk pakeeree
* adrien lecoq
* Julien Lefort
* Louise Formery
* Ck Cheik
* Jacky Shao
* Justine Taisant
* Jason M Gauvin
* Cloé Coupris

# Les conditions

*cf conditions.html*

## Exercice 1 
*5min puis correction*

#### Définir une variable age égale à 18

#### Ecrire une condition : si age est plus grand que 18, écrire dans la console "tu peux entrer" sinon "c'est interdit pour toi"

*pour écrire dans la console utiliser console.log("texte")*

*pour voir la console quand vous ouvrez la page html sur votre navigateur, clic droit -> inspecter -> onglet console, le message devrait s'afficher*

#### Si l'age est compris entre 18 et 50, écrire dans la console "tu peux entrer", si l'age est plus grand que 50, écrire dans la console "t'es ieuv", si l'age est plus petit que 18, écrire dans la console "mdr"

#### Changer la valeur de age pour pouvoir afficher les 3 messages possibles

## Exercice 2
*10min on vous aide si besoin puis correction rapide*

#### Définir une variable big à true

#### Si big est vrai, alors écrire dans la console "bouge de la", sinon écrire dans la console "bienvenue mon ami"

# Les boucles
*cf boucles.html*

## Exercice 1

*vous le faîtes*

#### Déclarer une variable birthyear égale à l'année de votre naissance ainsi qu'une variable actualYear égale à l'année actuelle (2018 de rien)

#### Utilisez une boucle while pour afficher dans la console chaque année passée depuis votre naissance (ex : 2000, 2001, 2002, ... , 2018)

## Exercice 2
*5min puis correction*

#### Déclarer une variable counter égale à 0, comme son nom l'indique, elle va nous servir de compteur

#### Déclarer un tableau students avec 10 noms d'élèves

#### Faire une boucle while en utilisant counter pour afficher les noms de chaque élève du tableau

## Exercice 3

*démerdez-vous*

#### Faire la même chose que l'exercice 2 en utilisant une boucle for

# Le DOM
*cf dom.html*

*Le DOM (DocumentObjetcModel) définit la structure d'une page et le moyen d'interagir avec elle*

## Exercice 1

#### Créer une variable list qui va contenir le premier ul du code html

*indice : utilisez querySelector*

#### Mettre à cette variable list un bg rose, une fontSize de 32px et une fontFamily de type horrible (Comic sans ms)

#### Remplacer le contenu du premier ul par un li
*utiliser innerHTML*

#### Rajouter un texte dans ce li (par exemple "haut oui")
*utiliser textContent*

## Exercice 2

#### De la meme manière que dans l'exercice 1 récupérer la div class yoyo, changer son bg, rajouter un texte et mettre ce texte en couleur
*/!\ attention ici on récupère la class pas l'élément*

#### Récupérer le bouton id execellent dans la variable que vous appelerez btn

#### Rajouter un écouteur d'évènement sur le bouton pour qu'en cliquant dessus vous rajoutiez/enleviez à la div yoyo la class big (définie dans le css au dessus)
*utiliser la méthode addEventListener()*

# Le DOM (suite)
*cf dom2.html*

## Exercice 1

#### Récupérer tous les p dans un tableau paragraphe

#### Afficher dans chaque p un text, changer la couleur de ce texte en rouge et aussi sa fontSize à 20px
*/!\ c'est un tableau de plusieurs éléments, il faut bien itérer sur chaque élément du tableau, et qui dit itération, dit ...*

## Exercice 2 

#### Récupérer la div à la classe square dans une variable appelée box

#### Changer la hauteur et la largeur de box à 300px, lui mettre un bg jaune et un texte quelconque. Enfin mettre ce texte en rose (#design)

#### Récupérer le premier bouton et lui ajouter un écouteur d'évènement pour ajouter/enlever la classe close (définie dans le css) à box

#### Faire la meme chose avec le bouton class dropTheMike et ajouter/enlever la classe mike (définie dans le css) à box
