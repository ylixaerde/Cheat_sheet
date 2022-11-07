# Cheat sheet - Git/GitHub

## Git

### Dépot local

git init

>Initialiser le dossier pour qu’il se transforme en dépot

git add .

>Ajouter à l’index les éléments du dossier courant

git commit –m « explication »

>Créer une nouvelle version des fichiers ajouter à l’index
>Explication – exemple : « update 1 cheat sheet python et github complétées »

### Dépot distant

git remote add origin lien-github.com

>Ajouter un lien vers le dépôt distant

git remote add nom_distant git@github.com:utilisateur/depot_utilisateur.git

>Ajouter un lien vers le dépôt distant (ssh)

git push –u origin main

>Upload les maj vers le dépôt distant depuis le dépôt local

git clone lien-github.com

>Download le dépôt distant vers un dépôt local

##GitHub

gh auth

>lance le script d'authentification Git vers GitHub

gh repo create --source=. --public --push

>Créer un dépot distant sur GitHub en mode public et uploader la dernière version du dépot local dessus.

git push

>Envoyer les modifications vers le dépot distant

