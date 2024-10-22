<!-- index.html -->
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ACOS CENTRU DE IDEI - Acasă</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="acos-logo.jpg" alt="Logo ACOS" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Acasă</a></li>
                <li><a href="servicii.html">Servicii</a></li>
                <li><a href="portofoliu.html">Portofoliu</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Bun venit la ACOS CENTRU DE IDEI</h1>
        <p>Inspirație și inovație pentru afacerea ta.</p>
        <img src="hero-image.jpg" alt="Imagine inspirativă">
    </section>

    <footer>
        <p>&copy; 2024 ACOS CENTRU DE IDEI. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>

<!-- servicii.html -->
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ACOS CENTRU DE IDEI - Servicii</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="acos-logo.jpg" alt="Logo ACOS" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Acasă</a></li>
                <li><a href="servicii.html">Servicii</a></li>
                <li><a href="portofoliu.html">Portofoliu</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="services">
        <h1>Serviciile Noastre</h1>
        <ul>
            <li>Consultanță creativă și strategii inovatoare</li>
            <li>Dezvoltare de brand și identitate vizuală</li>
            <li>Managementul proiectelor creative</li>
            <li>Organizare evenimente și activități promoționale</li>
        </ul>
        <img src="services-image.jpg" alt="Imagine servicii">
    </section>

    <footer>
        <p>&copy; 2024 ACOS CENTRU DE IDEI. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>

<!-- portofoliu.html -->
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ACOS CENTRU DE IDEI - Portofoliu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="acos-logo.jpg" alt="Logo ACOS" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Acasă</a></li>
                <li><a href="servicii.html">Servicii</a></li>
                <li><a href="portofoliu.html">Portofoliu</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="portfolio">
        <h1>Portofoliu</h1>
        <p>Explorați câteva dintre proiectele noastre de succes:</p>
        <div class="portfolio-gallery">
            <img src="project1.jpg" alt="Proiect 1">
            <img src="project2.jpg" alt="Proiect 2">
            <img src="project3.jpg" alt="Proiect 3">
        </div>
    </section>

    <footer>
        <p>&copy; 2024 ACOS CENTRU DE IDEI. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>

<!-- contact.html -->
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ACOS CENTRU DE IDEI - Contact</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="acos-logo.jpg" alt="Logo ACOS" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Acasă</a></li>
                <li><a href="servicii.html">Servicii</a></li>
                <li><a href="portofoliu.html">Portofoliu</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contactează-ne</h1>
        <form action="#">
            <label for="nume">Nume:</label>
            <input type="text" id="nume" name="nume" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="mesaj">Mesaj:</label>
            <textarea id="mesaj" name="mesaj" rows="4" required></textarea>

            <button type="submit">Trimite</button>
        </form>
        <img src="contact-image.jpg" alt="Imagine contact">
    </section>

    <footer>
        <p>&copy; 2024 ACOS CENTRU DE IDEI. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>

<!-- styles.css -->
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

.logo {
    width: 150px;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.hero, .services, .portfolio, .contact {
    padding: 20px;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
}

.portfolio-gallery img, .services img, .hero img, .contact img {
    max-width: 100%;
    height: auto;
    margin: 20px auto;
    display: block;
}
