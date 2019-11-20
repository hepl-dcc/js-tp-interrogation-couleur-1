# Colorie la page
> JS test given at HEPL

* * *

**js-tp-interrogation-couleur-1** is an educational project, which will be used for `JS` courses.

**Note:** the school where the course is given, the [HEPL](http://www.provincedeliege.be/hauteecole) from Liège, Belgium, is a french-speaking school. From this point, the instruction will be in french. Sorry.

* * *

> Lors de vos cours de *web*, vous allez découvrir le langage *JavaScript* et le mettre en pratique pour apprendre à rendre vos pages web interactives.  

* * *

## Énoncé

Ta mission est : au clic sur un des boutons, colorie la page dans la couleur choisie par l'utilisateur.
Cachier des charges :
* tu vas appliquer le style avec CSS, JavaScript va se contenter d'ajouter au clic, une classe sur le body qui indiquera à CSS dans quelle couleur il doit être stylé ;
* comme nom de classe, tu peux utiliser la valeur de l'attribut `data-color` du bouton concerné ;
* tu vas le faire en n'utilisant qu'une seule fonction (colorie) : cette fonction doit donc récupérer l'attribut `data-color` du bouton auquel elle est associée
* BONUS : au lieu de faire quatre appels de fonction différés (un pour chauqe bouton), parcours la liste des boutons avec une boucle (utilise ici la boucle for… of) et affecte-leur l'écouteur d'événement dans la boucle.

![readme](./readme.gif)
