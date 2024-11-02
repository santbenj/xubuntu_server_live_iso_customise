> [!WARNING]
Je recommande vivement d'utiliser ces scripts sur une machine virtuelle de 30 Go au moins, les scripts désactiveront les mots de passe de l'utilisateur et ne créera pas d'ISO juste la configuration nécessaire et des outils utilitaires pour le réaliser. Ces script ne fonctionneront que sur Ubuntu-server, peut-être Xubuntu si vous voulez-essayer.

Vous pouvez modifier et ajouter d'autre programmes aux besoins et après avoir modifier votre système, il suffira de lancer cette commande:

sudo eggs produce --clone

Ces scripts sont un point de départ pour creer un système "boite à outils" qui peut être en tant que ISO, l'objectif principal de ces scripts est de creer un système liveUSB pour réparer, sauvegarder et modifier votre ordinateur si vous en avez le besoin. 

# Installation 

Lancez la commande dans le terminal:
```
./Install
```
Puis après le redémarrage, lancer la deuxième encore dans le terminal:

```
./After_show
```
Le script Install va installer des outils utilitaires au système, l'environnment xubuntu-core, configurer le bureau et supprimer snap et l'installation de snap, il va ussi configurer le système pour fonctionner sans mots de passe et quand le script seras finis, il redémarrera le système. 

Le script After_show va installer [penguins-eggs](https://penguins-eggs.net/) et supprimer le dossier des scripts.

Penguin-eggs est un outil console permettant de redistribuer le système et de le distribuer en tant qu'image iso, il y a beaucoup d'option avec cet outil mais pour le système live, on se contentera d'utiliser :

```
sudo eggs produce --clone
```
> [!TIP]
Vous pouvez aussi ajouter l'option `--max`pour une compression maximale quand vous avez finis de modifier et de tester le système. 

L'image ISO sera localisé dans `/home/eggs/.mnt/`

Voci une liste des thèmes installées :

Curseur = oreo_spark_lime_cursors venant de (https://github.com/milkmadedev/oreo-cursors-compiled) 

Thème d'icone = Tela-red venant de (https://github.com/vinceliuice/Tela-icon-theme.git)

thème GTK= Qogir-Dark venant de (https://github.com/vinceliuice/Vimix-gtk-themes.git)
