<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>4Deals - Dein Online-Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav {
            text-align: center;
            padding: 15px;
            background-color: #555;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .hero {
            text-align: center;
            padding: 50px;
            background: url('https://source.unsplash.com/1600x600/?shopping') no-repeat center center/cover;
            color: white;
        }
        .container {
            max-width: 1100px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            background: white;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 30%;
        }
        .product img {
            width: 100%;
            border-radius: 10px;
        }
        .buy-button {
            display: inline-block;
            padding: 10px 15px;
            margin-top: 10px;
            background-color: #28a745;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Willkommen bei 4Deals - Dein Online-Shop</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#produkte">Produkte</a>
        <a href="#kontakt">Kontakt</a>
    </nav>
    <section class="hero">
        <h2>Beste Produkte – Direkt zu dir!</h2>
        <p>Finde die besten Angebote in unserem exklusiven Online-Shop.</p>
    </section>
    <div class="container">
        <h2>Über 4Deals</h2>
        <p>Wir bieten hochwertige Produkte direkt von den besten Lieferanten. Kein Zwischenhändler – nur die besten Preise für dich!</p>
    </div>
    <div class="container" id="produkte">
        <h2>Unsere Bestseller</h2>
        <div class="products">
            <div class="product">
                <img src="https://example.com/smartwatch.jpg" alt="Smartwatch">
                <h3>Smartwatch</h3>
                <p>Stylische und funktionale Smartwatch für den Alltag.</p>
                <p><strong>49,99€</strong></p>
                <a href="https://example.com/smartwatch" class="buy-button">Jetzt kaufen</a>
            </div>
            <div class="product">
                <img src="https://example.com/fitness-tracker.jpg" alt="Fitness-Tracker">
                <h3>Fitness-Tracker</h3>
                <p>Überwache deine Aktivitäten mit unserem Fitness-Tracker.</p>
                <p><strong>39,99€</strong></p>
                <a href="https://example.com/fitness-tracker" class="buy-button">Jetzt kaufen</a>
            </div>
            <div class="product">
                <img src="https://example.com/headphones.jpg" alt="Kabellose Kopfhörer">
                <h3>Kabellose Kopfhörer</h3>
                <p>Hochwertiger Sound, komplett kabellos.</p>
                <p><strong>59,99€</strong></p>
                <a href="https://example.com/headphones" class="buy-button">Jetzt kaufen</a>
            </div>
        </div>
    </div>
    <div class="container" id="kontakt">
        <h2>Kontakt</h2>
        <p>Hast du Fragen? Kontaktiere uns per E-Mail: <strong>support@4deals.de</strong></p>
    </div>
    <footer>
        &copy; 2025 4Deals | Alle Rechte vorbehalten
    </footer>
</body>
</html>
