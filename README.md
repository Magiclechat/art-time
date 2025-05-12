
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ART Time – Montres d'Exception</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Playfair Display', serif;
      background: linear-gradient(to right, #f0f0f0, #d9d9d9);
      color: #333;
    }
    header {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 2em 1em;
    }
    header h1 {
      margin: 0;
      font-size: 3em;
    }
    header p {
      margin-top: 0.5em;
      font-size: 1.5em;
      font-style: italic;
    }
    nav {
      background-color: #333;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: white;
      padding: 1em;
      text-decoration: none;
      transition: background 0.3s;
    }
    nav a:hover {
      background-color: #555;
    }
    section {
      padding: 2em 1em;
      max-width: 1200px;
      margin: auto;
    }
    .montres {
      display: flex;
      flex-wrap: wrap;
      gap: 2em;
      justify-content: center;
    }
    .montre {
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      max-width: 300px;
      text-align: center;
      transition: transform 0.3s;
    }
    .montre:hover {
      transform: scale(1.05);
    }
    .montre img {
      width: 100%;
      height: auto;
      display: block;
    }
    .montre h3 {
      margin: 0.5em 0;
    }
    footer {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 1em;
    }
  </style>
</head>
<body>

  <header>
    <h1>ART Time</h1>
    <p>Le temps sublimé par l'art et l'innovation</p>
  </header>

  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#montres">Nos Montres</a>
    <a href="#apropos">À propos</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="accueil">
    <h2>Bienvenue chez ART Time</h2>
    <p>Découvrez notre collection exclusive de montres alliant tradition, modernité et art horloger.</p>
  </section>

  <section id="montres">
    <h2>Nos Montres</h2>
    <div class="montres">
      <div class="montre">
        <img src="https://conteenium.fr/wp-content/uploads/2022/07/RA-AC0M04Y-768x512.jpg.webp" alt="Montre Vintage" />
        <h3>Montre Vintage</h3>
        <p>Un design classique qui traverse le temps.</p>
      </div>
      <div class="montre">
        <img src="https://www.luxebytrendy.com/wp-content/uploads/2012/07/Urwerk-UR-110-RG.jpeg.jpeg" alt="Montre Futuriste" />
        <h3>Montre Futuriste</h3>
        <p>Innovation et technologie de pointe.</p>
      </div>
      <div class="montre">
        <img src="https://www.louispion.fr/media/catalog/product/4/9/4942715022273_1_685f.png" alt="Montre Moderne" />
        <h3>Montre Moderne</h3>
        <p>Élégance et simplicité contemporaine.</p>
      </div>
      <div class="montre">
        <img src="https://lduchen.com/upload/iblock/c10/D_161_1_Galaxy.png" alt="Montre d'Art" />
        <h3>Collection d'Art</h3>
        <p>Des pièces uniques inspirées par l'art.</p>
      </div>
    </div>
  </section>

  <section id="apropos">
    <h2>À propos</h2>
    <p>ART Time est une maison horlogère dédiée à la création de montres d'exception, fusionnant l'art, l'innovation et le savoir-faire traditionnel.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Pour toute demande ou information, veuillez nous contacter à l'adresse suivante : contact@arttime.fr</p>
  </section>

  <footer>
    <p>&copy; 2025 ART Time. Tous droits réservés.</p>
  </footer>

</body>
</html>
