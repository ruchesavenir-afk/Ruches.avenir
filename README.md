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
