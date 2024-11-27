
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Troc</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #4caf50;
            color: white;
            text-align: center;
            padding: 20px 10px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1em;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #4caf50;
        }
        section {
            padding: 40px 20px;
            text-align: center;
        }
        .offers {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .offer {
            background: white;
            margin: 15px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            width: 30%;
            box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
        }
        .offer h3 {
            color: #4caf50;
        }
        .cta {
            background-color: #4caf50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
            text-decoration: none;
        }
        .cta:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenue sur Troc&Co</h1>
    <p>Échangez des biens et services en toute simplicité !</p>
</header>

<nav>
    <a href="#offers">Offres</a>
    <a href="#add-offer">Ajouter une annonce</a>
    <a href="#contact">Contact</a>
</nav>

<section id="offers">
    <h2>Dernières Offres</h2>
    <div class="offers">
        <div class="offer">
            <h3>Chaise en bois</h3>
            <p>Échange contre un petit meuble.</p>
            <a href="#contact" class="cta">Échanger</a>
        </div>
        <div class="offer">
            <h3>Vélo adulte</h3>
            <p>Recherche outils de bricolage.</p>
            <a href="#contact" class="cta">Échanger</a>
        </div>
        <div class="offer">
            <h3>Services de jardinage</h3>
            <p>Disponible contre des cours de cuisine.</p>
            <a href="#contact" class="cta">Échanger</a>
        </div>
    </div>
</section>

<section id="add-offer">
    <h2>Ajouter une annonce</h2>
    <p>Remplissez le formulaire ci-dessous pour proposer un bien ou un service à échanger.</p>
    <form action="#" method="post" style="max-width: 500px; margin: auto;">
        <label for="title">Titre de l'offre :</label><br>
        <input type="text" id="title" name="title" required style="width: 100%; padding: 8px; margin: 10px 0;"><br>
        <label for="description">Description :</label><br>
        <textarea id="description" name="description" rows="4" required style="width: 100%; padding: 8px; margin: 10px 0;"></textarea><br>
        <label for="exchange">Ce que vous recherchez :</label><br>
        <input type="text" id="exchange" name="exchange" required style="width: 100%; padding: 8px; margin: 10px 0;"><br>
        <button type="submit" class="cta">Soumettre</button>
    </form>
</section>

<section id="contact">
    <h2>Contactez-nous</h2>
    <p>Email : contact@trocandco.com</p>
    <p>Téléphone : +33 6 12 34 56 78</p>
</section>

<footer>
    <p>&copy; 2024 Troc&Co. Tous droits réservés.</p>
</footer>

</body>
</html>
