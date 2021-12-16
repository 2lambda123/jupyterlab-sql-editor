# jupyterlab-sql-editor

A JupyterLab extension providing:

- SQL formatter
- Automatic extraction of database schemas
- Auto-completion triggered by `tab` or `dot`
    - table names
    - table alias
    - table joins
    - nested column names
    - functions
- Syntax highlight
    - line magic
    - cell magic
    - python strings

IPython magic for:
- Spark SQL
- Trino

Une extension a JupyterLab qui contribue:

- Formattage de SQL
- Extraction automatique du schéma de base de données
- Complétion automatique suivant un `tab` ou `dot` des
    - nom de tables
    - des alias de tables
    - des jointure de tables
    - des noms de colones imbriquées
    - des fonctions
-  Surbrillance de la syntaxe
    - ligne magic
    - cellule magic
    - python strings

IPython magic pour:
- Spark SQL
- Trino

Many thanks to the contributors of these projects / Merci à tous les contributeurs des projets suivants:

- [krassowski/jupyterlab-lsp](https://github.com/jupyter-lsp/jupyterlab-lsp)
- [joe-re/sql-language-server](https://github.com/joe-re/sql-language-server)
- [zeroturnaround/sql-formatter](https://github.com/zeroturnaround/sql-formatter)
- [cryeo/sparksql-magic](https://github.com/cryeo/sparksql-magic)
- [trino-python-client](https://github.com/trinodb/trino-python-client)
- [bloomberg/ipydatagrid](https://github.com/bloomberg/ipydatagrid)


## Execute and output your query results into an interactive data grid / Execution et affichage des résultats dans une grilles interactive
![display](images/ipydatagrid.gif)

## Output as JSON / Résultats en JSON
![display](images/json-output.gif)

## Auto suggest column names and sub-fields / Suggestion automatique des noms de colones et sous champs
![display](images/sparksql-nested-columns.gif)

## Auto suggest JOINs on matching column names / Suggestion automatiques de jointures sur nom de colones
![display](images/trino-inner-join.gif)

## Format and syntax highlight Notebook code cells / Formattage et surbrillance de la syntaxe des cellules
![display](images/format-cell.gif)

## Format and syntax highlight SQL within python strings / Formattage et surbrillance de la syntaxe dans un string python
![display](images/format-string.gif)


## Capture your Spark query as a Dataframe or a temporary view / Capture de la requete dans un Dataframe ou vue temporaire
![display](images/args.png)



## Installation

Following the installation instructions in [CONTRIBUTING](./CONTRIBUTING.md)

Suivre les instructions d'installation dans [CONTRIBUTING](./CONTRIBUTING.md)

## Security Vulnerability Reporting

If you believe you have identified a security vulnerability in this project, please send email to the project
team at contact@cyber.gc.ca, detailing the suspected issue and any methods you've found to reproduce it.

Please do NOT open an issue in the GitHub repository, as we'd prefer to keep vulnerability reports private until
we've had an opportunity to review and address them.

## Rapports sur les vulnérabilités de sécurité

Si vous pensez avoir identifié une faille de sécurité dans ce projet, veuillez envoyer un courriel à l'équipe du projet à contact@cyber.gc.ca, en détaillant le problème soupçonné et les méthodes que vous avez trouvées pour le reproduire.

Veuillez NE PAS ouvrir un problème dans le GitHub repo, car nous préférerions garder les rapports de vulnérabilité privés jusqu'à ce que nous ayons eu l'occasion de les examiner et de les résoudre.

