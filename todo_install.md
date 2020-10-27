# Installation d'un nouveau système

Notes d'installation d'un nouveau système GNU/Linux.
Pour convertir ces notes en PDF :

pandoc -s todo_install.md todo_install.pdf 



## Actions à réaliser en root
### Installation de packages additionnels

pacman -Syu

pacman -S git firefox vim pandoc gnupg sudo

pacman -S python-numpy python-scipy python-pandas R texlive

### Création de l'utilisateur
#### Commande de création

useradd renaud

#### Groupes complémentaires

usermod -aG wheel renaud

#### Configuration de sudo

visudo

## Actions à réaliser en tant que user

### Configuration de git


### Récupération des fichiers de configuration git

mkdir ~/git

cd git

git clone https://github.com/StochasticSocks/config-files.git

### Configuration de GPG

### Utilisation des clés stockées dans la smartcard

### Import des fichiers de configuration

