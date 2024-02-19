# tp_git
## Partie 0 : Configuration de Git

Avant de pouvoir utiliser Git, il y a quelques configuration à faire.

### Ajout d'un nom et email dans Git

Pour que les modifications que tu feras sur le repository soient identifiables, il faut fournir un nom et une adresse email. Pour faire cette configuration, ouvre GitBash (ou un terminal pour Mac/Linux) et entre les commandes suivantes en remplaçant nom et adresse email :

`git config --global user.name "<votre nom>"`

`git config --global user.email "<votre adresse email>"`

Git sait maintenant qui tu es et le nom choisi sera associé aux modifications que tu feras.

### Clone du repo

* Sur la page d'accueil de ton projet, clique sur le bouton ***clone*** et copie le lien pour cloner.
* Ouvre un GitBash (Windows) ou un terminal (Mac et Linux) à l'endroit où tu veux enregistrer les fichiers du repo git.
* Entre la commande `git clone <lien copié>`. Git va alors créer un dossier et téléchargement le contenu du projet sur le serveur. Tu as maintenant une copie locale du code !

## Partie 1 : Versionnage et Premiers commits

Maintenant que tu as une copie locale des fichiers, tu peux commencer à les éditer localement (avant d'envoyer tes modifications sur le serveur). Pour cela, ouvre VSCode et fait ***File > Open Folder***. Sélectionne le dossier `formation_git` fraichement créé. Tu auras alors accès dans VScode à tous les fichiers du repo.

### Mission 1 : Modifier un fichier

essayer de modifier un fichier dans ce projet et aprés valider le (commit) par execution des commandes de git (git status ,git add , git commit)

### Mission 2 : Ajouter un fichier

Ta deuxième mission est de créer un fichier `solutions.md` à la racine du repo (à coté du `README.md`).

### Mission 3 : Supprimer un fichier (facultatif)

Dernière mission pour la route, il y a dans le repo un fichier nommé `fichier_inutile`. Sauras-tu le supprimer du repo Github ?

Tu peux vérifier que le fichier a bien disparu du repo distant via l'interface web de Github.

Les quelques commandes que tu viens d'utiliser (`git status`, `git add`, `git commit`, `git pull`, `git push`) sont les commandes que tu utiliseras 95% du temps.

## Partie 2 : Collaboration, branches et merge requests

Pour pouvoir travailler séparément sur des features différentes on utilise des branches, cette fonctionnalité est particulièrement pratique pour faire avancer en même temps plusieurs versions du même code qui implémentent des fonctionnalités différentes.

### Mission 1 : Créer une branche

* Créer une branche et place toi sur cette nouvelle branche
* Vérifie que cette branche est bien sélectionnée
* Effectuer des modifications sur la nouvelle branche
* Validation des changements
* Retour à la branche principale 
* Fusion des branches / Résolution des conflits (si nécessaire) 
* Vérification de la fusion
* Nettoyage
