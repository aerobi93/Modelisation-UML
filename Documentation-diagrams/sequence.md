# <center> sequence </center>

## Pourquoi ce diagramme

Nous avons décider d'utiliser ce diagramme car il permet de décrire **COMMENT** les éléments du système interargissent entre eux et avec les acteurs :
- Les objets au coeur d'un système interargissent en s'échangeant des messages.
- Les acteurs interargissent avec le sustème au moyen d'IHM (Interface Homme-Machine).

## Explication du diagramme

Nous avons l'utilisateurs, on a le site cuistonaute, le modérateur

Connexion :
- si bon, OK.
- si error, life line end.
retour redirection page accueil avec navbar connecter

Changer le nombre de résultat par page 

Rechercher/Trier (avec enregistrement compte possible des paramètres de tri) une recette :
- si bon, afficher recettes trier.
- si error, afficher toutes recettes avec message error.


Clique sur la carte de recette : 
- si bon, affiche recette détailler.
- si error, redirige page 404.

Adapter la composition en fonction du nombre de personnes

Ajouter la recette en favori
- si bon, recette est enregistrer en favori.
- si error, error message.

Noter la recette :
- si bon.
- si error, error message.

Voir tous les commentaires :
- si bon, affiche tous les commentaires.
- si error, error message.

Cliquer sur un commentaire/avatar :
- si bon, redirige vers la page de l'utilisateur.
- si error, error message.

Commenter la recette :
- si bon, enregistre le commentaire.
- si error, error message.



## Image du diagramme