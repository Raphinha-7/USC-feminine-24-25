<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="USClogo.png" alt="logousc">
        <h1>Titre du site</h1>
    </header>

    <nav>
        <ul>
            <li><a href="actualité.html">Actualité</a></li>
            <li><a href="statistique.html">Statistiques</a></li>
            <li><a href="classement.html">Classement</a></li>
            <li><a href="S2425.html">Calendrier/Résultats</a></li>
            <li><a href="photo.html">Photo</a></li>
        </ul>
    </nav>

    <main>
        <section>
            <h2>Bienvenue sur notre site</h2>
            <p>Contenu de la page.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Votre Nom</p>
    </footer>
</body>
</html>
body {
    background-image: url('sitefond.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    font-family: 'Arial', sans-serif;
    color: #333; /* Choisissez votre couleur */
    margin: 0; /* Supprime les marges par défaut */
    padding: 0;
}

header {
    background-color: #f0f0f0; /* Choisissez votre couleur */
    padding: 20px;
    text-align: center;
}

nav {
    background-color: #eee; /* Choisissez votre couleur */
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

nav li {
    display: inline-block;
    margin: 0 10px;
}

nav a {
    text-decoration: none;
    color: #333; /* Choisissez votre couleur */
}

main {
    padding: 20px;
}

footer {
    background-color: #333; /* Choisissez votre couleur */
    color: #fff;
    padding: 10px;
    text-align: center;
    position: fixed; /* Positionnez le footer en bas */
    bottom: 0;
    width: 100%;
}
