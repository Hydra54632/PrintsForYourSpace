<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>Meine erste Webseite</title>
</head>
<body>
<h1>Hallo Welt!</h1>
<p>Das ist meine erste Webseite.</p>
</body>
</html><!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Meine Webseite</title>
<link rel="stylesheet" href="style.css" />
</head>
<body>
 
    <header>
<h1>Willkommen auf meiner Webseite</h1>
<nav>
<a href="#about">Über mich</a>
<a href="#projects">Projekte</a>
<a href="#contact">Kontakt</a>
</nav>
</header>
 
    <section id="about">
<h2>Über mich</h2>
<p>Hier kannst du etwas über dich reinschreiben.</p>
</section>
 
    <section id="projects">
<h2>Meine Projekte</h2>
<div class="card">
<h3>Projekt 1</h3>
<p>Kleine Beschreibung deines Projekts.</p>
</div>
<div class="card">
<h3>Projekt 2</h3>
<p>Noch eine Beschreibung …</p>
</div>
</section>
 
    <section id="contact">
<h2>Kontakt</h2>
<button onclick="zeigeKontakt()">Kontakt anzeigen</button>
<p id="kontaktInfo" class="hidden">Email: beispiel@mail.de</p>
</section>
 
    <footer>
<p>© 2025 Deine Webseite</p>
</footer>
 
    <script src="script.js"></script>
</body>
</html>

 
body {

    margin: 0;

    font-family: Arial, sans-serif;

    background: #f7f7f7;

}
 
header {

    background: #3366cc;

    color: white;

    padding: 20px;

    text-align: center;

}
 
nav a {

    color: white;

    margin: 0 15px;

    text-decoration: none;

    font-weight: bold;

}
 
section {

    padding: 40px;

    text-align: center;

}
 
.card {

    background: white;

    padding: 20px;

    margin: 20px auto;

    max-width: 400px;

    border-radius: 10px;

    box-shadow: 0 0 10px rgba(0,0,0,0.1);

}
 
footer {

    background: #222;

    color: white;

    padding: 10px;

    text-align: center;

}
 
.hidden {

    display: none;

}
 
vbody {

    margin: 0;

    font-family: Arial, sans-serif;

    background: #f7f7f7;

}
 
header {

    background: #3366cc;

    color: white;

    padding: 20px;

    text-align: center;

}
 
nav a {

    color: white;

    margin: 0 15px;

    text-decoration: none;

    font-weight: bold;

}
 
section {

    padding: 40px;

    text-align: center;

}
 
.card {

    background: white;

    padding: 20px;

    margin: 20px auto;

    max-width: 400px;

    border-radius: 10px;

    box-shadow: 0 0 10px rgba(0,0,0,0.1);

}
 
footer {

    background: #222;

    color: white;

    padding: 10px;

    text-align: center;

}
 
.hidden {

    display: none;

}
 
