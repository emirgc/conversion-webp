# Script de conversion d'images vers WebP

Ce script est destiné à convertir tous les fichiers image (jpeg, jpg, png) dans un répertoire donné en fichiers WebP, pour une utilisation plus efficace sur le Web. Le script met également à jour tous les fichiers HTML et Markdown dans tous les répertoires pour remplacer les liens des images converties en format WebP. Les fichiers d'origine seront supprimés après la conversion afin de gagner de l'espace. 

## Utilisation

1. Assurez-vous d'avoir installé les dépendances nécessaires, notamment le programme cwebp pour la conversion WebP et markdown pour python. 

2. Placez les fichiers image que vous souhaitez convertir dans un sous-répertoire du répertoire racine spécifié dans le script. Dans cet exemple, le chemin des images est /docs/assets/images.

3. Exécutez le script en tapant `python webp.py` dans le terminal.

4. Les fichiers d'origine seront supprimés après la conversion. Les fichiers HTML et Markdown seront également mis à jour pour remplacer les liens des images converties en format WebP.

Le repo inclut des fichiers exemples.
## Contributions

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir un issue ou à proposer un pull request si vous souhaitez apporter des améliorations ou corriger des bogues.

## Licence

Ce projet est sous licence MIT.
