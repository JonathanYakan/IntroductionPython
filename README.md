# Introduction au language Python

## Pré-requis

Avant d'en apprendre un peu plus sur le language Python nous allons commencer par l'installer si ce n'est pas déjà fait.

### Installer Python3:

- sur Fedora: `sudo dnf install python3`
- sur Ubuntu: `sudo apt-get install python3`
- sur ArchLinux: `sudo pacman -S python`

Vous pouvez verifiez votre installation en executant la commande suivante: `python3 --version`

## Pour commencer

_En savoir un peu plus sur lui_

Python est un langage de programmation interprété, orienté objet et à typage dynamique écrit en language C. Voici une description rapide des principales caractéristiques de Python que vous pouvez inclure dans votre README pour un workshop d'apprentissage de Python :

- Simplicité d'utilisation et lisibilité
- Large bibliothèque standard
- Un language multiparadigme
- Large communauté et écosystème
- Utilisation polyvalente (web, analyse de données, automatisation, ...)

### Exercice 1: _Le traditionnel Hello World !_

#### nom du fichier: ex1.py

Le but de cet exercice est d'afficher dans le terminal le text suivant: `Hello world !`

pour lancer votre programme vous pouvez faire `python3 ex1.py`

### Exercice 2:

#### nom du fichier: ex2.py

Le but de cet exercice est de crée une fonction qui affiche les chiffres de 9 à 0 (l'odre est important) en utilisant une boucle.
(il y a plusieurs manière de faire, libre à vous de choisir comment)

### Exercice 3:

#### nom du fichier ex3.py

Le but de cet exercice est de crée une fonction qui prend en paramètre un nombre et qui renvoi un True ou False si le nombre est pair ou impair.

### Exercice 4:

#### nom du fichier ex4.py

Le but de cet exercice est de convertir une température en degrés Celsius en Fahrenheit. Mais il faut que la température soit récupérée via l'entrée utiliteur (input).

### Exercice 5:

#### le nom du fichier ex5.py

Dans cet exercice vous devez crée une fonction qui renvoi True si le mot donné en paramètre est un palindrome sinon False.

#

Bon nous allons commencer à utiliser quelques librairies

#

### Exercice 6:

#### le nom du fichier ex6.py

Le but de cet exercice est d'ajouter dans un tableau 10 nombres genérés aléatoirement entre 1 et 100.
Ensuite il faudra trié cette liste.
Enfin affiché chaque élement de la liste mais aussi la liste elle meme.

https://docs.python.org/3/library/random.html  
https://docs.python.org/3/library/array.html  
(On peu appliqué plusieurs méthodes sur les array :))

### Exercice 7:

#### le nom du fichier ex7.py

Le but de cet exercice est de découvrir comment envoyer des requêtes à des API mais aussi de traiter l'information.

Vous devez envoyer une requête GET à l'URL suivante : `https://catfact.ninja/fact`

Cette API va vous envoyer une reponse json, vous devez parser le json reçu pour pouvoir afficher au format suivant les informations reçues :  
`La taille du msg reçu est X, et voici le message : "Un message sur les chats"`

### Exercice 8:

#### le nom du fichier ex8.py

` python3 -m pip install coverage`

Partie 1:

Dans cet exercice, vous allez devoir crée une class `Calcul` dans le fichier ex8. Cette class prend en paramètre un nombre "a" à la création de l'object et stock ce nombre.

Vous allez implémenter une méthode is_prime_number() qui renvoi renvoi un booleen pour savoir si la valeur d'entrée est un nombre premier ou non.

Partie 2:

Vous allez faire des tests unitaires en python en utilisant le module unittest
https://coverage.readthedocs.io/en/7.2.7/

Vous devez avoir 100% de coverage sur le fichier ex8.
