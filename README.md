
# Création de routes utilisateur
💪 Challenge


Ton défi consiste à :

    Créer une route GET /api/users, cette route doit renvoyer un statut 200 et une liste d'utilisateurs de la base de données au format json
    Créez une route GET /api/users/:id qui renverra uniquement l'utilisateur de la base de données correspondant à l'identifiant défini dans l'url
        S'il y a un utilisateur qui correspond aux paramètres, renvoie une réponse avec un statut 200 et l'utilisateur correspondant en tant qu'objet json
        Sinon, retourne un statut 404 avec un message "Not Found"

Publie une URL d'un dépôt GitHub avec ton application complète comme solution.

🧐 Critères de validation

Le serveur fonctionne
* L'url /api/users affiche la liste des utilisateurs au format json
* L'url /api/users/2 affiche un utilisateur au format json
* L'url /api/users/0 affiche "Not found"
* Crée une route POST pour /api/users qui insérera un nouvel utilisateur dans la base de données
* Crée une route DELETE pour le chemin /api/users/:id qui va supprimer un utilisateur dans la base de données
* Créez une route PUT pour le chemin /api/users/:id : ta route modifiera un utilisateur dans la base de données
* Ajoute deux filtres pour la route GET /api/users existant :

    si un paramètre language est fourni dans l'URL (?language=English), ne renvoie que les locuteurs de cette langue.
    si un paramètre city est fourni dans l'URL (?city=Paris), ne renvoie que les utilisateurs dont la ville correspond au paramètre.

Publie ton application améliorée sur GitHub et partage l'URL ici.

