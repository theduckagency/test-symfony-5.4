
# Tâches à réaliser
1. Créez un controller `src\Controller\DefaultController` avec une méthode `hello` dans le fichier
    - route `/hello`
    - accessible uniquement en GET
    - avec comme retour au format JSON `{"hello":"world!"}`
2. Créez une entité Article comprenant les champs suivants :

   |     champ    |   type  | limite | nullable |
   |:------------:|:-------:|:------:|:--------:|
   | title        | varchar | 150    | non      |
   | introduction | varchar | 255    | oui      |
   | content      | text    |        | non      |
4. Créez un controller `src\Controller\ArticleController`
5. Créez la route `/articles/add`
    - créez et affichez un formulaire permettant d'ajouter un article
6. Créez la route `/articles`
    - listez sur cette page les articles en affichant uniquement le titre, avec au bout deux boutons :
        - modification de l'article
        - suppression de l'article
7. Créez la route `/article/update/{id}`
    - créez un formulaire permettant de modifier uniquement l'introduction et le contenu de l'article
8. Créez la route `/article/delete/{id}`
    - cette route devra supprimer l'article
