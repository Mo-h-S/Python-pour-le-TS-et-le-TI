
# Python pour le TS et le TI

## Qu'est-ce que Python ?

Python est un langage de programmation polyvalent, créé par Guido van Rossum. Il est connu pour sa syntaxe claire et sa facilité d'utilisation, ce qui en fait un choix populaire pour les débutants et les professionnels.

## Utilisateurs de Python

Python est utilisé dans divers domaines, notamment :
* Développement logiciel
* Science des données
* Administration système
* Développement web
* Recherche académique

Des entreprises comme Netflix, Spotify et NASA utilisent Python pour diverses applications.

* Avantages de Python
* Facile à apprendre
* Bibliothèques étendues
* Multiplateforme
* Fort soutien communautaire

## Versions de Python
Python possède deux versions principales que vous pouvez rencontrer lors de l’installation du langage :

- Python 2.x
Il s'agit de l'ancienne version de Python, dont la dernière version est Python 2.7.18. Bien que Python 2.x soit encore utilisé dans certaines applications anciennes, il est important de noter qu'il a atteint sa fin de vie en janvier 2020. Cela signifie qu'aucune mise à jour ou correction de bogue ne sera plus fournie. Par conséquent, il est fortement recommandé d’utiliser Python 3.x pour les nouveaux projets.

- Python 3.x
C’est la version actuelle et activement maintenue de Python, avec des mises à jour et des améliorations continues. Python 3.x a apporté de nombreuses améliorations et modifications au langage, le rendant plus efficace et plus puissant. C’est la version recommandée pour tous les nouveaux projets et installations.

Comment installer Python
Nous allons maintenant vous guider dans le processus d’installation de la dernière version de Python sur le système d’exploitation de votre choix.

## Prérequis pour l'installation
- Connaissances informatiques de base Familiarité avec la ligne de commande  
- Ordinateur avec connexion Internet
- Système d'exploitation compatible (Windows 7+, macOS 10.9+, ou Linux)
- Au moins 4 Go de RAM et 5 Go d'espace disque1

## Deux choix pour installer Python sur votre système.

#### Installation de Python sur différents systèmes et un IDLE
Télécharger le programme d'installation depuis le site officiel de Python 
| Système   | Lien      | 
| :-------  | :-------  | 
| Windows  | https://www.python.org/downloads/windows/  |
| Ubuntu | https://www.python.org/downloads/source/  | 
| MacOS | https://www.python.org/downloads/macos/  | 


Exécuter le programme d'installation
Personnaliser l'installation (facultatif)
Lancer l'installation
Vérifier l'installation via la commande python --version
Une alternative est d'installer Python via le Microsoft Store

### IDLE : Environnement de Développement Intégré
IDLE (Integrated Development and Learning Environment) est l'environnement de développement intégré pour Python, conçu pour faciliter l'apprentissage et le développement. Il est entièrement écrit en Python et fonctionne sur plusieurs plateformes, y compris Windows, Unix et macOS.
#### Fonctionnalités Principales
- Console Interactive : Permet d'exécuter du code Python ligne par ligne avec coloration syntaxique pour une meilleure lisibilité.
- Éditeur de Texte : Offre des fonctionnalités avancées comme l'auto-complétion, l'indentation automatique et la gestion des erreurs.
- Outils de Débogage : Inclut des options pour définir des points d'arrêt et inspecter les variables.
- Gestion des Fichiers : Facilite la création, l'ouverture et la sauvegarde de scripts Python.
- Documentation Intégrée : Accès direct à la documentation Python pour aider les utilisateurs à comprendre les fonctionnalités.
IDLE est particulièrement adapté aux débutants en raison de son interface intuitive, mais il peut être limité pour des projets plus complexes, où d'autres IDE comme VSCode ou PyCharm pourraient être plus appropriés.


## Facilite la vie en installant Anaconda pour avoir tous les packages

#### Installation python avec Anaconda

Anaconda est une distribution logicielle gratuite et facile à installer pour Python et R, qui comprend une vaste collection de plus de 7 500 packages open source (incluant R)14. Lors de l'installation d'Anaconda, plus de 250 packages sont automatiquement installés en même temps que Python.

## Installation d'anaconda sur différents systèmes
Télécharger le programme d'installation depuis le site officiel d'anaconda

| Système   | Lien      | 
| :-------  | :-------  | 
| Windows  | https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Windows-x86_64.exe  |
| Ubuntu | https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Linux-x86_64.sh  | 
| MacOS | https://repo.anaconda.com/archive/Anaconda3-2024.10-1-MacOSX-arm64.pkg  | 

Ouvrir Anaconda Navigator : Lancez Anaconda Navigator depuis le menu de votre système d'exploitation ou en utilisant le terminal avec la commande anaconda-navigator.

- Lancer Spyder : Dans Anaconda Navigator, cliquez sur l'icône de Spyder pour l'ouvrir / Vous pouvez également lancer Spyder directement depuis le terminal(anaconda prompt) en tapant spyder.

  Et voila !!!!!

Pour verifier la version de python tapez dans le terminal:

python --version

Si tout est en ordre, vous n'avez plus besoin de faire quoi que ce soit. Cependant, si vous souhaitez séparer vos projets et travailler avec des environnements distincts, tout en installant uniquement les librairies nécessaires pour chaque projet, il est essentiel de configurer un environnement virtuel (Voir la section Configuration d'un Environnement Virtuel).

Maintenant que tout est en place, il ne reste plus qu'une dernière étape.

### Configuration de spyder 

#### Configuration de la sortie graphique
Ouvrez Spyder.
- Allez dans le menu Outils.
- Sélectionnez Préférences.
- Dans la fenêtre des préférences, allez dans IPython console > Graphiques (Choisissez graphique) et vous pouvez configurer la sortie graphique selon vos besoins (par exemple, choisir entre une sortie inline ou une nouvelle fenêtre).

##### Effacer les variables avant l'exécution
- Allez dans Console d'IPython > Exécution.
- Cochez l'option Effacer toutes les variables avant de démarrer une exécution.

##### Configuration de l'aide dans les préférences
- Allez dans Aide. 
- Ici, vous pouvez configurer comment vous souhaitez que l'aide s'affiche (par exemple, en ligne, dans une fenêtre séparée, etc.).
- Cochez toutes les cases.

#### Indentation automatique
Allez dans Préférences.
- Sous Editeur > Indentation, vous pouvez configurer l'indentation automatique. Vous pouvez choisir entre des tabulations ou des espaces et définir le nombre d'espaces par indentation.
- Pour respecter la PEP8
- Sélectionnez Utiliser des espaces au lieu des tabulations, car PEP8 recommande d'utiliser 4 espaces pour chaque niveau d'indentation.
- Définissez le nombre d'espaces par indentation à 4.


Si vous êtes arrivé jusqu'ici, félicitations ! Votre environnement de travaill est maintenant configuré.

## Pour commencer

- Configurer votre projet : Une fois Spyder ouvert, allez dans le menu "Projets" et créez un nouveau projet
- Donnez un nom à votre projet et choisissez un répertoire pour le stocker
- Écrire et exécuter du code : Utilisez l'éditeur de texte de Spyder pour écrire votre code Python
- Par exemple, vous pouvez écrire un simple script comme print("Hello, World!")
- Pour exécuter le script, cliquez sur le bouton "Exécuter" dans la barre d'outils ou utilisez le raccourci clavier Ctrl + Entrée
- Explorer les variables : Utilisez l'Explorateur de Variables pour voir les valeurs de vos variables pendant l'exécution de votre programme
- Vous pouvez trouver cet outil dans l'onglet "Variables" à droite de l'interface
- Accéder à la documentation : Pour obtenir la documentation d'une fonction ou d'un module, placez simplement le curseur sur le nom de la fonction ou du module et appuyez sur la touche F11


### Configuration d'un Environnement Virtuel
Les environnements virtuels sont un outil précieux qui permet de gérer plusieurs installations Python distinctes. C'est particulièrement utile lorsque vous travaillez sur plusieurs projets Python simultanément. Plutôt que de maintenir une installation unique et encombrée avec tous les packages imaginables, les environnements virtuels assurent que chaque projet a son propre espace propre avec seulement les outils nécessaires.

- Pour configurer votre premier environnement virtuel, ouvrez le Terminal sur macOS ou l'Anaconda Prompt sur Windows. Ensuite, créez un nouvel environnement virtuel avec la commande suivante :
```bash
conda create --name Lab1 python=3.4
```
Ici, le paramètre --name spécifie le nom de l'environnement virtuel, dans ce cas, "Lab1". Le paramètre python=3.4 est facultatif mais indique que cet environnement virtuel doit utiliser la version 3.4.x de Python, assurant que tout le monde utilise la même version de Python.

Conda peut installer quelques packages, en vous demandant confirmation avant de continuer. Une fois l'installation terminée, activez l'environnement conda que vous venez de créer en tapant conda activate Lab1 sur macOS ou activate Lab1 sur Windows. Votre invite de commande devrait maintenant afficher le nom de l'environnement entre crochets avant la ligne de commande, comme ceci :
```bash
(Lab1) ➜  ~
```
Cela confirme que vous êtes maintenant dans l'environnement que vous venez de créer et que tous les packages Python que vous installerez resteront dans ce sandbox. Ensuite, installons quelques outils de base :

conda install numpy jupyter pip matplotlib

Vous pouvez lister autant de noms de packages que nécessaire après le mot-clé install, et conda les installera tous en une fois. Encore une fois, il peut vous demander confirmation avant d'installer des packages que vous n'avez pas déjà.

Pour accéder à cet environnement, tapez:
```bash
conda activate ./envs
```
Vous pouvez désactiver votre environnement à tout moment en utilisant la commande conda deactivate sur macOS, ou simplement deactivate sur Windows.
```bash
conda deactivate ./envs
```
for more information check this link : https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

## Feedback

If you have any feedback, please reach out to us.

## Sources 

https://www.anaconda.com/download/success

https://www.python.org/downloads/
