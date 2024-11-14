<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            background-image: url('sitefond.png');
            background-size: cover; /* Pour que l'image couvre tout l'arrière-plan */
            background-position: center; /* Pour centrer l'image */
            background-repeat: no-repeat; /* Pour éviter que l'image se répète */
            font-family: Arial, sans-serif; /* Choix de la police d'écriture */
            color: #fff; /* Couleur du texte */
            margin: 0; /* Pour enlever les marges par défaut */
            padding: 20px; /* Pour ajouter un peu d'espace interne */
            text-align: center; /* Centrer le texte */
        }

        h2 {
            margin: 20px 0; /* Ajouter de l'espace entre les titres */
            font-size: 2em; /* Taille des titres */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6); /* Ombre pour le texte */
        }

        ul {
            list-style-type: none; /* Suppression des puces */
            padding: 0; /* Suppression de l'espace interne */
        }

        li {
            margin: 10px 0; /* Ajouter de l'espace entre les éléments de la liste */
        }

        a {
            text-decoration: none; /* Enlever le soulignement */
            color: #fff; /* Couleur des liens */
            font-size: 1.5em; /* Taille des liens */
            transition: color 0.3s; /* Transition pour le changement de couleur */
        }

        a:hover {
            color: #FFA500; /* Changement de couleur au survol */
        }

        img {
            max-width: 100%; /* Rendre l'image responsive */
            height: auto; /* Garder le rapport d'aspect */
        }
    </style>
</head>
<body>
    <h2><img src="USClogo.png" alt="Logo USC"></h2>
    <h2>Menu</h2>
    <ul>
        <li><a href="actualité.html">Actualité</a></li>
        <li><a href="statistique.html">Statistiques</a></li>
        <li><a href="classement.html">Classement</a></li>
        <li><a href="S2425.html">Calendrier/Résultats</a></li>
        <li><a href="photo.html">Photo</a></li>
    </ul>
</body>
</html>
