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
Ajouter un lien vers le dépôt distant
git remote add nom_distant git@github.com:utilisateur/depot_utilisateur.git
Ajouter un lien vers le dépôt distant (ssh)
git push –u origin main
Upload les maj vers le dépôt distant depuis le dépôt local
git clone lien-github.com
download le dépôt distant vers un dépôt local

