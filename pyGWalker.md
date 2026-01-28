PyGWalker peut simplifier votre flux de travail d'analyse de données et de visualisation de données dans Jupyter Notebook, 
en transformant votre dataframe pandas en une interface utilisateur interactive pour l'exploration visuelle.

PyGWalker (prononcé comme "Pig Walker", juste pour le plaisir) est nommé en tant qu'abréviation de "Python binding of 
Graphic Walker". Il intègre Jupyter Notebook avec Graphic Walker, une alternative open-source à Tableau. 
Cela permet aux data scientists de visualiser / nettoyer / annoter les données avec des opérations simples de glisser-déposer 
et même des requêtes en langage naturel.

# Installer PyGWalker :
    pip = pip install pygwalker runcell
    Conda - forge = conda install -c conda-forge pygwalker OU mamba install -c conda-forge pygwalker

# Utiliser pygwalker dans Jupyter Notebook :

## Démarrage rapide
    Importez pygwalker et pandas dans votre Jupyter Notebook pour commencer.
    ====================
    import pandas as pd
    import pygwalker as pyg

    Vous pouvez utiliser pygwalker sans interrompre votre flux de travail existant. Par exemple, vous pouvez appeler PyGWalker avec le dataframe chargé de cette manière :
    ====================
    df = pd.read_csv('./bike_sharing_dc.csv')
    walker = pyg.walk(df)

C'est tout. Maintenant, vous avez une interface utilisateur interactive pour analyser et visualiser les données avec des opérations simples de glisser-déposer.
