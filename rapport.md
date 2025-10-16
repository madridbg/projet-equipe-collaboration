# Rapport de laboratoire Git - Équipe cool

## 1. Membres de l'équipe
- Membre 1 : Madrid Boutin-Guénette - Chef de l'équipe
- Membre 2 : Jacob Somphanthabansouk  - Développeur
- Membre 3 : Emerick Lanthier - Testeur

## 2. Résumé des parties complétées

### Partie 1 : Configuration initiale
Création du dépôt local. Création github pour créer un nouveau repository en public. Ensuite nous avons relié le dépôt local
avec le repository github

### Partie 2 : Ajout des collaborateurs
Dans la section collaborators, j'ai invité les membres de mon équipe. Ils ont tous accepté l'invitation. À partir du repository, ils ont créé un dépôt local avec git clone.

### Partie 3 : Première collaboration
Nous avons créé nos fichiers sur VSCode à partir de la fonctionnalité New File. Pour que chaque personnes voit les changements, nous avons add, commit et push pour qu'ensuite les membres puissent pull.

### Partie 4 : Résolution de conflits
Ajout dans le fichier readme un texte. Ensuite, le membre 2 a modifié le meme endroit sans pull. Au moment qu'il a push, un conflit a surgit. Pour résoudre le tout, nous avons fait git pull et nous avons combiner les deux versions.

### Partie 5 : Collaboration HTML
Création du fichier HTML, ajout du contenu pour ensuite envoyer les modifications. Récupérer les modifications pour les deux autre. Modification du titre, le push (Par le membre 1). Ensuite, le membre 2 modifie le même titre sans faire de récupération auparavant. Cela entraîne un conflit, qui est résolu après qu'un pull soit effectué.

### Partie 6 : Utilisation des branches
Le membre 1 crée une branche ajout-style avec un fichier css présent. Le fichier css est ensuite modifié avant d'être commité et pushé. Retour sur la branche main pour ensuite merger la branche ajout-style.

### Partie 7 : Situations réalistes
1- Cas de modification simultanée
Les membres 1 et 2 modifient leurs fichiers membre.txt respectifs. En tentant de faire un push en même temps, seul un des deux réussi à le faire, car le deuxième nécessite un pull avant que son push ne fonctionne. 

2- Oubli de faire un pull
Le membre 1 modifie le readme.md et le push. En parallèle, le membre 2 modifie le readme.md, mais n'effectue pas de pull après le push du membre 1. Ceci résulte en une erreur qui devra être résolue de façon manuelle lorsque le pull est appelé. Le membre 2 effectue ensuite un push et les changements se suivent selon la résolution choisie.

3- Annulation d'un commit
Création d'un fichier erreur.txt, qui sera ajouté et commité. Ensuite, à l'aide d'un git reset --SOFT, le commit dernier est annulé, toutefois, le fichier reste en zone de préparation, prête à être commitée à nouveau. Après, on fait un git reset --HARD qui supprime définitivement les modifications et notre fichier erreur.txt disparaît.

4- Visualisation de l'historique
Test des différentes commandes git log, soit
git log, qui affiche les informations complètes des logs.
git log --oneline, qui affiche une version compacte des informations et qui aide mieux à la visualisation.
git log --oneline --graph --all, qui démontre une visualisation colorée et organisée des logs, où l'on peut y voir des chemins vers les branches créées.
q
## 4. Difficultés rencontrées

### Difficulté 1
- **Problème** : MEMBRE 1 -Mettre mon projet local dans le repository. Je n'arrivais pas à lier les deux, et ça me demandait mon authentification et quand je rentrais mon mot de passe, cela ne fonctionnait pas.  J'ai changé le mot de passe et même à cela, je ne pouvais pas lier les deux 

- **Solution** : J'ai re créer un dépôt local complet pour repartir de zéro. Avec mon nouveau mot de passe et nouveau dépôt local, la liaison des deux a fonctionnée.

### Difficulté 2
- **Problème** : MEMBRE 1 - Problème de push, cela n'apparaissait pas dans le github pour tout le monde. Les modifications du membre 1 ne s'affichaient pas.
- **Solution** : Nous svaons réalisé que nous avions pas sauvegardé le fichier avant d'envoyer les modifications

## 5. Apprentissages

### Ce que nous avons appris sur Git
-Apprentissage 1 : L’importance de faire git pull régulièrement pour éviter les conflits et garder le projet à jour.

-Apprentissage 2 : Comment résoudre un conflit de fusion en comparant les versions de code et en choisissant les bonnes lignes à conserver.

-Apprentissage 3 : L’utilité des branches pour travailler sur de nouvelles fonctionnalités sans affecter la version principale du projet.

### Ce que nous avons appris sur le travail d'équipe
- Apprentissage 1 : L’importance de bien communiquer entre les membres pour éviter de travailler sur les mêmes fichiers en même temps.

- Apprentissage 2 : Comment se coordonner en planifiant les tâches de chacun et en utilisant des messages clairs dans les commits et sur GitHub.

## 6. Conclusion
[Rédigez une courte conclusion (5-10 lignes) sur votre expérience globale du laboratoire]
En conclusion, ce laboratoire nous a permis de nous familiariser avec les concepts de base de Git, ainsi que les manipulations et le partage de fichiers via GitHub. Pour préciser, nous avions déjà tenté d'utiliser GitHub pour des projets antérieurs, avec beaucoup de difficulté. Ce laboratoire, avec ses directives détaillées, a rendu la compréhension des conventions et du fonctionnement global de GitHub beaucoup plus aisée. Selon nous, ce travail était très nécessaire, car c'était l'expérience la plus proche d'une situation réelle de travail en milieu d'entreprise, où le travail d'équipe est indispensable.