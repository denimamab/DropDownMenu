# DropDownMenu
DropDownMenu is a responsive multi levels menu using jQuery & LESS. [Demo](https://denimamab.github.io/DropDownMenu/)


#Gestion des Menus selon la largeur du support

##Partie CSS

Dans la partie CSS je gère les menus, et **autant** de niveaux de sous menus possibles. 

##Partie HTML

Pour ajouter un autre niveau il suffit de rajouter une liste après la balise **a** qui se trouve à l'intérieur **li**. 
**L'ordre est très important** sinon le script JS sera mal interprété.

###Architecture : 
* **ul** premier niveau
  * **li**
    * **a** lien non terminal
    * **ul** deuxième niveau
      * **li**
        * **a** lien terminal

De la même façon on construit le troisième niveau etc.

##Partie JavaScript

Gère tout les menus et les sous menus qui existent.
