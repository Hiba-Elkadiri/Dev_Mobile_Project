# Dev_Mobile_Project
# Une application de gestion de location de costumes, avec une interface client permettant de consulter les modèles.

Avec notre application de location de costumes, l’utilisateur commence par la page de connexion où il peut entrer son email et son mot de passe pour accéder à son compte, ou se rendre sur la page d’inscription s’il n’a pas encore de compte. 
La page d’inscription permet de créer un profil en saisissant le prénom, le nom, l’email et le mot de passe, avec des validations pour vérifier que l’email est correct et que le mot de passe est suffisamment sécurisé ; les erreurs s’affichent directement sur la page et la redirection vers la connexion ne se fait que lorsque toutes les informations sont correctes.
Une fois connecté, l’utilisateur arrive sur la page d’accueil de notre application, qui affiche son prénom et son nom dynamiquement, ainsi qu’un menu offrant les principales fonctionnalités : 
consulter les catégories de costumes disponibles, voir l’historique de ses locations et se déconnecter via le bouton logout.
La page de location de costumes présente une liste de costumes avec leurs images, noms et prix par jour, ainsi qu’un bouton « Louer » pour réserver un costume. 
L’utilisateur peut filtrer ou rechercher les costumes par catégorie ou par prix.
Toutes les données des costumes sont récupérées depuis la base SQL Server, et le stock se met automatiquement à jour lorsque l’utilisateur loue un costume.
