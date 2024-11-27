
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Site Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0078d7;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #00509e;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .services {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .service {
            border: 1px solid #ccc;
            padding: 15px;
            width: 30%;
            box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
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
        @media (max-width: 768px) {
            .services {
                flex-direction: column;
                align-items: center;
            }
            .service {
                width: 80%;
                margin-bottom: 20px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenue sur Mon Site Web</h1>
    <p>Découvrez nos services et contactez-nous pour plus d'informations</p>
</header>

<nav>
    <a href="#accueil">Accueil</a>
    <a href="#services">Services</a>
    <a href="#apropos">À propos</a>
    <a href="#contact">Contact</a>
</nav>

<section id="accueil">
    <h2>Accueil</h2>
    <p>Bienvenue sur notre site web. Nous sommes heureux de vous accueillir et de vous proposer nos services.</p>
</section>

<section id="services">
    <h2>Nos Services</h2>
    <div class="services">
        <div class="service">
            <h3>Service 1</h3>
            <p>Description du service 1.</p>
        </div>
        <div class="service">
            <h3>Service 2</h3>
            <p>Description du service 2.</p>
        </div>
        <div class="service">
            <h3>Service 3</h3>
            <p>Description du service 3.</p>
        </div>
    </div>
</section>

<section id="apropos">
    <h2>À propos de nous</h2>
    <p>Nous sommes une entreprise dédiée à offrir des services de qualité et à répondre aux besoins de nos clients.</p>
</section>

<section id="contact">
    <h2>Contactez-nous</h2>
    <p>Email : contact@monsite.com</p>
    <p>Téléphone : +33 6 12 34 56 78</p>
</section>

<footer>
    <p>&copy; 2024 Mon Site Web. Tous droits réservés.</p>
</footer>

</body>
</html>
