# Local commit

**Etape 1**

     git init

Edit file...

**Etape 2**

     git add *

**Etape 3**

    git commit -m "My comment"

**Etape 4**

    git push origin master

> Si vous souhaitez push une branch (exemple feature)

    git branch feature
    git checkout feature
 
> Combinaison des deux :

    git checkout -b feature

> Création et push de la branch sur le ripo github

    git push origin feature

# Pull request

**Etape 1**

Cliquez sur le bouton **Fork**

**Etape 2**

Clonez le projet

    git clone https://github.com/ThomasMouchelet/tutogithub.git

Ajouter le remote upstream en cas de modification sur le ripo master

    git remote add upstream https://github.com/elodidu33/test.git

    git fetch upstream

    git pull

Editez le fichier

**Etape 3**

Il est préférable de créer une nouvelle branch

    git checkout -b feature
    git add *
    git commit -m "My comment"
    git push origin feature

**Etape 4**

Cliquez sur le bouton **Create pull request** dans votre compte github.