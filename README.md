Vous trouverez dans ce github le projet de Deep Learning de 3 élèves de l'EISTI.

Les objectifs de ce projet sont les suivants:
- Construire un modèle qui à partir d'un texte en entrée va détecter son niveau de toxicité (plusieurs types
sont possibles dans un texte). Le modèle doit être capable de détecter différents types de toxicité comme
les menaces, l'obscénité, les insultes, etc. Le modèle doit prédire une probabilité pour chaque classe (type
de toxicité). 
- Proposer une application/démonstrateur.

Vous trouverez dans le fichier NLP_PROJET.ipynb :
- l'import et chargement des données
- Préparation des données
- Création des modèles 

Il est possible de réutiliser les modeles deja entrainés dans le fichier models/

Le fichier embeddings/ est vide pour ne pas surcharger ce github, a telecharger sur https://nlp.stanford.edu/projects/glove/ et unzip "glove.6B.100d.txt" dans le fichier embeddings qui est a creer si non existantt

Si vous voulez réentrainer les modeles il faut changer le variable CHARGEMENT_SAUVEGARDE à False

En bas du notebook est présent une interface graphique très simpliste permettant de marquer une phrase et de constater sa toxicité à travers les différents modèles

contact: arthur.aries@outlook.com antimiluc@eisti.eu lequerethi@eisti.eu