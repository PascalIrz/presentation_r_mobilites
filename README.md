# Bonnes pratiques de développement : retour d'expérience
----------------

# Organisation

## Arborescence
- sous-répertires avec des noms explicites
- "projet" R => chemins en relatif (en particulier si utilisation d'une forge)

## Ecriture
- Standardiser le style de code
- Règles de nommage
- pas de scripts trop longs => 99_make.R
- parcimonie : pas de recalculs
- optimisation : oui mais pas trop. vectorisation / boucles
- 
## Programmation fonctionnelle
- écrire des fonctions
- packager
- soumettre

## Disjoindre le fond et la forme

si applis, structure modulaire la plus dépouillée possible (externaliser tout le code qui peut l'être)

# Documentation
Essentiel en particulier pour un projet tel que celui sur les mobilités car nbses personnes contribuent au développement (environ 10 déjà).

## Commentaires
En mettre partout. Explicite à l'échelle de la ligne ou du bloc de code.

## Métadonnées des fonctions
Obligatoire. Explique à quoi sert une fonction et comment l'utiliser. 

## Tutos / vignettes
Démonstration de chaines de traitement (suite de fonctions mobilisées) avec toute la place nécessaire.

# Versionnage

