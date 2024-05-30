# Bonnes pratiques de développement : retour d'expérience autour de l'appli mov'around
----------------

# Contexte / enjeux

Point de départ : l'appli mov'around, v0 (~2500L de code, essentiellement du commentaire ligne à ligne).

Enjeux de maintenance et de performance / utilisateur. 
  
# Principes

- Organiser le projet.
- Coder proprement.
- Sortir de l'appli tout ce qui peut l'être.
- Structurer l'appli en modules.
- Disjoindre le fond et la forme.
- Packager (programmation fonctionnelle, tests, soumission).
- Optimiser la réactivité (mise à jour auto des données => parcimonie du téléchargement).
- Documenter.

# Organiser le projet

- Arborescences standards.
- Nommage des sous-répertoires, des fichiers, des fonctions, des arguments de fonctions.
- "projet" R => chemins en relatif (en particulier si utilisation d'une forge).
- pas de scripts trop longs => 99_make.R

# Architecture générale

Objectif général : simplifier la maintenance (tests, débuggage, montée de versions).

Bénéfice secondaire : plusieurs productions qui chacunes peuvent rentrer dans une dynamique de partage / amélioration. 

## Sortir de l'appli tout ce qui peut l'être


## Structurer l'appli en modules


## Le fond et la forme


## Programmation fonctionnelle

- écrire des fonctions
- packager (yc tests unitaires)
- soumettre


  
- parcimonie : pas de recalculs
- optimisation : oui mais pas trop. vectorisation / boucles
  


# La forme du code

- Standardiser le style de code (e.g. tidyverse)
- Indentation (cf. fonction d'aide "Reformat code" de RStudio)

# Documentation
Essentiel en particulier pour un projet tel que celui sur les mobilités car nbses personnes contribuent au développement (environ 10 déjà).
Packagedown.

## Commentaires
En mettre partout. Explicite à l'échelle de la ligne ou du bloc de code.

## Métadonnées des fonctions
Obligatoire. Explique à quoi sert une fonction et comment l'utiliser. 

## Tutos / vignettes
Démonstration de chaines de traitement (suite de fonctions mobilisées) avec toute la place nécessaire.

# Versionnage

Cf. présentation de Tim.
