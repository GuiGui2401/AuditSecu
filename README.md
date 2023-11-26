# Analyse de Risque - Projet XYZ

## Description
Ce script Python permet de réaliser une analyse de risque pour le projet XYZ en identifiant les risques, évaluant leur probabilité et leur impact, et planifiant les réponses aux risques.

## Fonctionnalités
- Identification des risques avec description, probabilité et impact.
- Évaluation des risques en calculant un score de risque.
- Planification des réponses aux risques en fonction des scores.
- Génération de rapports au format PDF ou Excel.

## Utilisation
1. Assurez-vous d'avoir Python installé sur votre machine.
2. Installez les dépendances en exécutant `pip install argparse openpyxl fpdf`.
3. Exécutez le script avec la commande suivante :

    ```bash
    python script.py -t [pdf ou excel]
    ```

   Remplacez `[pdf ou excel]` par le type de rapport que vous souhaitez générer.

## Exemple
```bash
python script.py -t pdf
```

## Rapports Générés
- **rapport_analyse_risque.pdf** : Rapport au format PDF contenant les détails de l'analyse de risque.
- **rapport_analyse_risque.xlsx** : Rapport au format Excel avec les informations sur les risques.

## Auteur
GuiGui2401

## Licence
Ce projet est sous licence GNU. Consultez le fichier LICENSE pour plus de détails.