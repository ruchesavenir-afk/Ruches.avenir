# Ruches.avenir
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Les Ruches de l'Avenir</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <!-- Logo -->
      <img src="logo.png" alt="Les Ruches de l'Avenir" class="logo">
      <ul>
        <li><a href="index.html">Accueil</a></li>
        <li><a href="miel.html">Miel</a></li>
        <li><a href="elevage.html">Élevage</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <!-- Section Présentation -->
    <section class="presentation">
      <h2>MODIF Présentation</h2>
      <p>Ici vous pouvez modifier le texte de présentation pour parler de vos ruches et de vos valeurs.</p>
    </section>

    <!-- Section Actualités -->
    <section class="actualites">
      <h2>MODIF Actualités</h2>
      <div id="news-container"></div>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Les Ruches de l'Avenir</p>
  </footer>

  <script src="actualites.js"></script>
</body>
</html>
/* Base */
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fffaf0; /* fond doux */
  color: #333;
}

/* Header / Navigation */
header {
  background-color: #f7b731; /* couleur principale logo */
  padding: 10px 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.logo {
  height: 50px;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}

/* Main */
main {
  padding: 20px;
}

.presentation, .actualites {
  margin-bottom: 30px;
}

/* Footer */
footer {
  background-color: #f7b731;
  text-align: center;
  padding: 10px;
}

/* Responsive */
@media (max-width: 600px) {
  nav ul {
    flex-direction: column;
    text-align: center;
  }

  nav ul li {
    margin: 10px 0;
  }
}
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Miel - Les Ruches de l'Avenir</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <img src="logo.png" alt="Les Ruches de l'Avenir" class="logo">
      <ul>
        <li><a href="index.html">Accueil</a></li>
        <li><a href="miel.html">Miel</a></li>
        <li><a href="elevage.html">Élevage</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>MODIF Miel</h2>
    <p>Listez ici vos différents miels, descriptions et caractéristiques.</p>
  </main>

  <footer>
    <p>&copy; 2026 Les Ruches de l'Avenir</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Élevage - Les Ruches de l'Avenir</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <img src="logo.png" alt="Les Ruches de l'Avenir" class="logo">
      <ul>
        <li><a href="index.html">Accueil</a></li>
        <li><a href="miel.html">Miel</a></li>
        <li><a href="elevage.html">Élevage</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>MODIF Élevage</h2>
    <p>Parlez ici de vos techniques d’élevage, des abeilles et de vos colonies.</p>
  </main>

  <footer>
    <p>&copy; 2026 Les Ruches de l'Avenir</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Les Ruches de l'Avenir</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <img src="logo.png" alt="Les Ruches de l'Avenir" class="logo">
      <ul>
        <li><a href="index.html">Accueil</a></li>
        <li><a href="miel.html">Miel</a></li>
        <li><a href="elevage.html">Élevage</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>MODIF Contact</h2>
    <p>Email : <a href="mailto:contact@ruches-avenir.fr">contact@ruches-avenir.fr</a></p>
    <p>Téléphone : 06 12 34 56 78</p>
  </main>

  <footer>
    <p>&copy; 2026 Les Ruches de l'Avenir</p>
  </footer>
</body>
</html>
