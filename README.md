# 2020 2021 Hydrodynamique souterraine
# Notebooks compléments de cours
## ENSEGID - ENS2
### Enseignants: F. Larroque, A. Dupuy, G. Cohen, O. Atteia

Ces notebooks constituent un complément au cours d'hydrodynamique souterraine ENS2. Ils viennent en renfort des exercices de TD abordés lors des séances en présentiel et proposent un approfondissement quant à leur résolution en intégrant l'outil de programmation Python.

Ces supports sont basés sur l'outil Jupyter Notebook qui a été développé pour représenter et partager les données scientifiques, en intégrant notamment des outils de programmation éditables. Un notebook intègre du texte, des figures, des formules, éventuellement du code informatique (Python, R, Julia, ...) et les sorties associées. L'avantage est de pouvoir être mis à disposition et édité de manière totalement transparente.

Les outils permettant de créer et d'utiliser des Notebooks sont gratuits, et le Projet Jupyter, utilisé ici est open-source. Il est possible d'installer le logiciel sur sa propre machine pour pouvoir utiliser les notebooks sans être connecté au réseau, ou au contraire utiliser une machine virtuelle en ligne, afin d'exploiter les notebooks sans nécessiter d'installation du logiciel.
Une bonne introduction globale aux notebooks est disponible à l’adresse suivante :
-	https://blog.quantinsti.com/jupyter-notebook-tutorial-installation-components-magic-commands/

Accès aux ressources du module Hydrodynamique souterraine :
Les notebooks et données nécessaires sont stockées sur le site d’échange libre GitHub, sur l’espace de stockage dédié. Tous les fichiers sont téléchargeables.
- https://github.com/larroque852/20202021_ENS2_HYDRODYN

Utilisation du Notebook sur poste « déconnecté » :
La méthode la plus simple est d’installer la suite Anaconda qui intègre l’éditeur Jupyter Notebook. Cette suite intègre également une distribution Python. De nombreux sites détaillent la procédure et les sites pour installer ces logiciels.
-	https://openclassrooms.com/fr/courses/4452741-decouvrez-les-librairies-python-pour-la-data-science/5559646-installez-jupyter-sur-votre-propre-ordinateur
-	https://realpython.com/jupyter-notebook-introduction/
-	https://github.com/molmod/Tutorial

***Utilisation du Notebook en ligne :***
Les Notebooks sont également exploitables en ligne, en utilisant une machine virtuelle hébergée par un site web. Les fonctionnalités sont identiques mais la génération de la machine virtuelle peut prendre un peu de temps au lancement. L’utilisation nécessite évidemment une connexion internet active tout le temps de l’exploitation.
Plusieurs sites permettent de créer des machines virtuelles. La solution retenue est basée sur le site Binder :
- https://mybinder.org/

il suffit ensuite de préciser le site GitHub contenant les dépôts des fichiers Notebooks (https://github.com/larroque852/20202021_ENS2_HYDRODYN) puis lancer la création dela machine virtuelle (cela peut prendre un peu de temps). On a alors accès à une interface identique à celle du logiciel Jupyter Notebook/
On peut également accéder à une version pré-compilée de la machine virtuelle via l’adresse suivante (cela peut mettre un peu de temps à se lancer... c'est normal!) :
- https://mybinder.org/v2/gh/larroque852/20202021_ENS2_HYDRODYN/345633fdb1eede75f02428b5462ef5a5d9728c7a

## Notebooks disponibles
-	ENS2_diff.ipynb : utilisation de l’équation de diffusivité. Applications en nappe captive et nappe libre
-	ENS2_Puits.ipynb : essai de puits - théorie et application
-	ENS2_Theis1.ipynb : solution à l’équation de diffusivité en régime transitoire – solution de Theis, analyse et exploitation
-	ENS2_Nappe_Theis.ipynb : essais de nappe - méthode de Theis
-	ENS2_Nappe_Jacob.ipynb : essais de nappe – méthode de Cooper Jacob
- ENS2_Superposition : principe de superposition, analyse effets de limite et remontée
