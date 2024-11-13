<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>U.S. Colomiers Féminine 24/25</title>
    <style>
        body {
            background-image: url('sitefond.png');
            background-repeat: no-repeat; /* Empêche la répétition de l'image */
            background-size: cover; /* L'image couvre toute l'écran */
            margin: 0; /* Supprime les marges par défaut */
            font-family: Arial, sans-serif; /* Police générique */
        }
        /* Style du menu */
        .menu {
            background-color: rgba(51, 51, 51, 0.8); /* Couleur de fond avec opacité */
            overflow: hidden;
            padding: 10px 0; /* Espacement vertical */
        }
        /* Liens du menu */
        .menu a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        /* Change la couleur lorsque l'on survole */
        .menu a:hover {
            background-color: rgba(17, 17, 17, 0.8);
        }
        /* Conteneur pour le sous-menu */
        .dropdown {
            float: left;
            overflow: hidden;
        }
        /* Bouton du sous-menu */
        .dropdown .dropbtn {
            background-color: inherit; /* Utilise la couleur de fond du parent */
            border: none;
            cursor: pointer;
            padding: 14px 16px;
            color: white;
            font-size: 16px;
        }
        /* Style du sous-menu (caché par défaut) */
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9; /* Couleur de fond du sous-menu */
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
        }
        /* Liens du sous-menu */
        .dropdown-content a {
            float: none;
            color: black;
            text-decoration: none;
            text-align: left;
            padding: 12px 16px;
        }
        /* Changer la couleur lorsqu'on survole un lien du sous-menu */
        .dropdown-content a:hover {
            background-color: #ddd;
        }
        /* Afficher le sous-menu lorsque le bouton est survolé */
        .dropdown:hover .dropdown-content {
            display: block;
        }
    </style>
</head>
<body>
    <div class="menu">
        <a href="#accueil">Accueil</a>
        <div class="dropdown">
            <button class="dropbtn">Services</button>
            <div class="dropdown-content">
                <a href="#service1">Service 1</a>
                <a href="#service2">Service 2</a>
                <a href="#service3">Service 3</a>
            </div>
        </div>
        <a href="#about">À propos</a>
        <a href="#contact">Contact</a>
    </div>

</body>
</html>
