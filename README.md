# Ruches.avenir
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apiculture Antoine</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <h1>Apiculture Antoine</h1>
      <ul>
        <li><a href="index.html">Accueil</a></li>
        <li class="dropdown">
          Produits
          <ul class="dropdown-menu">
            <li><a href="miel.html">Miel</a></li>
            <li><a href="elevage.html">Élevage</a></li>
          </ul>
        </li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="presentation">
      <h2>Bienvenue chez Apiculture Antoine</h2>
      <p>Nous élevons nos abeilles avec soin et proposons des produits naturels de qualité.</p>
    </section>

    <section class="actualites">
      <h2>Actualités</h2>
      <div id="news-container"></div>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Apiculture Antoine</p>
  </footer>

  <script src="actualites.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fff8f0;
  color: #333;
}

header {
  background-color: #f1c40f;
  padding: 10px 20px;
}

header h1 {
  display: inline-block;
  margin: 0;
  font-size: 24px;
}

nav ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: inline-block;
  float: right;
}

nav ul li {
  display: inline-block;
  position: relative;
  margin-left: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}

nav ul li:hover .dropdown-menu {
  display: block;
}

.dropdown-menu {
  display: none;
  position: absolute;
  background-color: #f1c40f;
  min-width: 120px;
  top: 25px;
}

.dropdown-menu li {
  display: block;
  margin: 0;
}

.dropdown-menu li a {
  display: block;
  padding: 5px 10px;
}

main {
  padding: 20px;
}

.presentation, .actualites {
  margin-bottom: 30px;
}

footer {
  background-color: #f1c40f;
  padding: 10px;
  text-align: center;
}

@media (max-width: 600px) {
  nav ul {
    float: none;
    display: block;
    text-align: center;
  }

  nav ul li {
    display: block;
    margin: 10px 0;
  }
}
fetch('actualites.json')
  .then(response => response.json())
  .then(data => {
    const container = document.getElementById('news-container');
    data.forEach(item => {
      const article = document.createElement('div');
      article.className = 'news-item';
      article.innerHTML = `<h3>${item.titre}</h3><p>${item.date}</p><p>${item.texte}</p>`;
      container.appendChild(article);
    });
  });
  [
  {
    "titre": "Nouvelle récolte de miel 2026 !",
    "date": "18 janvier 2026",
    "texte": "Notre première récolte de l'année est disponible, 100% naturel et local."
  },
  {
    "titre": "Ouverture de l'élevage des reines",
    "date": "15 janvier 2026",
    "texte": "Nous avons commencé un nouvel élevage de reines sélectionnées pour leur robustesse."
  }
]
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Miel - Apiculture Antoine</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <h1>Apiculture Antoine</h1>
      <ul>
        <li><a href="index.html">Accueil</a></li>
        <li class="dropdown">
          Produits
          <ul class="dropdown-menu">
            <li><a href="miel.html">Miel</a></li>
            <li><a href="elevage.html">Élevage</a></li>
          </ul>
        </li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>Nos Miels</h2>
    <p>Découvrez nos différents miels naturels, récoltés avec soin.</p>
    <ul>
      <li>Miel de fleurs sauvages</li>
      <li>Miel d’acacia</li>
      <li>Miel de châtaignier</li>
    </ul>
  </main>

  <footer>
    <p>&copy; 2026 Apiculture Antoine</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Élevage - Apiculture Antoine</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <h1>Apiculture Antoine</h1>
      <ul>
        <li><a href="index.html">Accueil</a></li>
        <li class="dropdown">
          Produits
          <ul class="dropdown-menu">
            <li><a href="miel.html">Miel</a></li>
            <li><a href="elevage.html">Élevage</a></li>
          </ul>
        </li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>Notre Élevage</h2>
    <p>Nous élevons des reines et des colonies saines pour assurer une production durable et de qualité.</p>
  </main>

  <footer>
    <p>&copy; 2026 Apiculture Antoine</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Apiculture Antoine</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <h1>Apiculture Antoine</h1>
      <ul>
        <li><a href="index.html">Accueil</a></li>
        <li class="dropdown">
          Produits
          <ul class="dropdown-menu">
            <li><a href="miel.html">Miel</a></li>
            <li><a href="elevage.html">Élevage</a></li>
          </ul>
        </li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>Contactez-nous</h2>
    <p>Email : <a href="mailto:contact@apicultureantoine.fr">contact@apicultureantoine.fr</a></p>
    <p>Téléphone : 06 12 34 56 78</p>
  </main>

  <footer>
    <p>&copy; 2026 Apiculture Antoine</p>
  </footer>
</body>
</html>
