# CheckList
All the checklist for all to do. Just copy/paste checklist in the WordPress plugin [Task Manager](https://fr.wordpress.org/plugins/task-manager/)

Toutes les checklists pour tout faire, il suffit juste de copier/coller les listes dans l'extension de WordPress : [Task Manager](https://fr.wordpress.org/plugins/task-manager/)


##  Charte de nommage et organisation des fichiers
### Noms des dossiers
Les noms ci-dessous sont des dossiers chaque dossier est relatif d'une catégories, secteur d'activité, famille. C'est un regroupement de dossiers ou directement des checklist en rapport avec sont nom.
* Personnel
* Web
* SEO
* Audit
* Industrie
* QHSE

### Nom des fichiers sources des checklist

les fichiers sont au format .txt. Le nommage des sources doit respecter la charte de nommage suivante :
* Les caractères autorisés sont [a-z],[1-9]
* nomdossierparent_nomdossierparent_description_formX.txt

Exemple à suivre, dans le dossier Cuisine/pate_crepe
* cuisine_pate_crepe_listing_ingredients.txt
* cuisine_pate_crepe_recette.txt
* cuisine_pate_crepe_listing_controle.txt

## Organisation du versionning du contenu des fichiers
Le systeme de version est basé sur semversion, il doit être indiqué dans la premiere ligne du fichier de la facon suivante :
%task%Sujet du formulaire - X.Y.Z-AAAAMMJJ
Exemple :
%task%Vérification de la conformité RGPD - 1.1.0-20180523
