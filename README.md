# Brick-log

> Static fake blog, support for jQuery exercise.

* * *

Brick-log is an educational project, which will be used for jQuery courses.

**Note:** the school where the course is given, the HEPL from Liège, Belgium, is a french-speaking school. From this point, the instruction will be in french. Sorry.

* * *

## jQuery

Lancé en 2006 par [John Resig](http://fr.wikipedia.org/wiki/John_Resig), [jQuery](http://jquery.com) s'est très vite imposé comme une révolution dans le monde de javascript.

Simple à prendre en main, flexible et adaptable, jQuery est la boîte à outils du développeur web.

### La librairie jQuery

Pour commencer, nous allons utiliser jQuery seul, sans plugin.

Cet exercice est un peu spécial, puisque nous n'allons pas le faire ensemble : vous allez le faire seul, en utilisant toutes les ressources à votre disposition pour répondre aux demandes de l'énoncé.

Dans ce *repository*, vous avez récupéré un mini-site statique, qui représente un article de blog, et vous allez devoir dynamiser un peu le tout grâce à jQuery.

Je vous ai joins la dernière version de jquery dans le dossier `/js/`.  
Le fichier de travail se nomme `/js/script.js`.

## Note

Cet exercice *doit* tourner sur un serveur local, puisqu'il fait appel à un petit script php.

## Énoncé

Il y a plusieurs choses à faire sur cette page. Les voici : 

1. Il y a certains liens sur la page qui ont un attribut `rel="external"`. Ces liens doivent s'ouvrir dans une nouvelle fenêtre.
    
2. Dans la colonne de droite, il y a 3 vignettes dans une section nommée **Trombinoscope**. Il faudrait n'afficher qu'une seule image, et faire un mini-diaporama pour changer de photo toutes les 5 secondes.

3. Toutes les 5 secondes, vous allez faire un appel `AJAX` vers le service situé à l'adresse `/comments.php`, qui vous fournira un nombre aléatoire de commentaires à ajouter dans la page.

4. Pour chaque commentaire, il y a un petit bouton en forme de croix. Au clic sur ce bouton, le commentaire est remplacé par un avertissement de modération, comme montré dans la page.
