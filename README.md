# tp_git
## Partie 0 : Configuration de Git et du Gitlab de ViaRézo

Avant de pouvoir utiliser Git, il y a quelques configuration à faire.

### Ajout d'un nom et email dans Git

Pour que les modifications que tu feras sur le repository soient identifiables, il faut fournir un nom et une adresse email. Pour faire cette configuration, ouvre GitBash (ou un terminal pour Mac/Linux) et entre les commandes suivantes en remplaçant nom et adresse email :

`git config --global user.name "<votre nom>"`

`git config --global user.email "<votre adresse email>"`

Git sait maintenant qui tu es et le nom choisi sera associé aux modifications que tu feras.

### Clone du repo

* Sur la page d'accueil de ton projet, clique sur le bouton ***clone*** et copie le lien pour cloner avec `SSH` (cf. l'étape du dessus s'il existe des problèmes de permissions).
* Ouvre un GitBash (Windows) ou un terminal (Mac et Linux) à l'endroit où tu veux enregistrer les fichiers du repo git.
* Entre la commande `git clone <lien copié>`. Git va alors créer un dossier et téléchargement le contenu du projet sur le serveur. Tu as maintenant une copie locale du code !

## Partie 1 : Versionnage et Premiers commits

Maintenant que tu as une copie locale des fichiers, tu peux commencer à les éditer localement (avant d'envoyer tes modifications sur le serveur). Pour cela, ouvre VSCode et fait ***File > Open Folder***. Sélectionne le dossier `formation_git` fraichement créé. Tu auras alors accès dans VScode à tous les fichiers du repo.

### Mission 1 : Modifier un fichier

Dans un repo git, l'édition des fichiers se fait comme dans un dossier classique. Mais cette modification en local doit ensuite être synchronisée avec le serveur.

Voici-ci dessous une ligne moche et inutile. Sauras-tu la supprimer ? (Le bilan des actions comme décrit sur le diapo te sera utile si tu bloques)

**Cette ligne est moche est inutile, supprime là !**

Il existe aussi un module git intégré à VSCode, je t'encourage à essayer de l'utiliser pour supprimer la deuxième ligne moche et inutile ci-dessous.

**Cette ligne est aussi moche et inutile, supprime là !**

Tu peux vérifier que les lignes du fichier ont bien disparu du repo distant via l'interface web de Gitlab sur ta copie personnelle.

### Mission 2 : Ajouter un fichier

Ta deuxième mission est de créer un fichier `solutions.md` à la racine du repo (à coté du `README.md`) et d'y ajouter la démarche que tu as suivie pour réussir la mission précédente.

