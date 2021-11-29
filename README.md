## Installation de l'environnement virtuel

Créer l'environnement à partir du fichier yaml
```bash
conda env create -f environment.yml
```

Activer l'environnement
```bash
conda activate projet_3
```

Quitter l'environnement
```bash
conda deactivate projet_3
```

Supprimer l'environnement
```bash
conda env remove --name projet_3
```

## Téléchargement du jeu de données

Récupérer le jeu de données <a href = https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-scientist/P2/fr.openfoodfacts.org.products.csv.zip>à cette adresse</a>

Dézipper et placer le fichier nommé "fr.openfoodfacts.org.products.csv" dans le dossier "data/"

## Démarrer le serveur Voila

(Ne pas oublier de d'abord installer l'environnement)

Lancer la commande suivante :

```bash
voila P3_01_notebook.ipynb
```