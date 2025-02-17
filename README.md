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
            background-color: #ff9800;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }
        nav {
            text-align: center;
            padding: 15px;
            background-color: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
            font-weight: bold;
        }
        .hero {
            text-align: center;
            padding: 50px;
            background: url('https://source.unsplash.com/1600x600/?shopping,ecommerce') no-repeat center center/cover;
            color: black;
            font-size: 24px;
            font-weight: bold;
            text-shadow: none;
        }
        .hero p {
            color: black;
        }
        .container {
            max-width: 1100px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            text-align: center;
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
            font-weight: bold;
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
        Willkommen bei 4Deals - Die besten Angebote online!
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#produkte">Produkte</a>
        <a href="#kontakt">Kontakt</a>
    </nav>
    <section class="hero">
        <h2>Jetzt Top-Produkte zum besten Preis sichern!</h2>
        <p>Finde die besten Angebote in unserem exklusiven Online-Shop.</p>
    </section>
    <div class="container" id="produkte">
        <h2>Unsere Bestseller</h2>
        <div class="products">
            <div class="product">
                <img src="https://m.media-amazon.com/images/I/71RargTF1hL._AC_SL1500_.jpg" alt="Smartwatch">
                <h3>Smartwatch mit integrierten Kopfhörern</h3>
                <p>2-in-1 Bluetooth Smartwatch mit Fitness-Tracker und kabellosen Ohrhörern.</p>
                <p><strong>99,00€</strong></p>
                <a href="https://www.amazon.de/dp/B0CL3XMK1F" class="buy-button">Jetzt kaufen</a>
            </div>
            <div class="product">
                <img src="https://m.media-amazon.com/images/I/61YXNim+iQL._AC_SL1500_.jpg" alt="Fitness-Tracker">
                <h3>Fitness-Tracker</h3>
                <p>Überwache deine Aktivitäten mit unserem fortschrittlichen Fitness-Tracker.</p>
                <p><strong>105,00 €</strong></p>
                <a href="https://www.amazon.de/dp/B0CHN3W617" class="buy-button">Jetzt kaufen</a>
            </div>
            <div class="product">
                <img src="https://m.media-amazon.com/images/I/71rNAXcPZ2L._AC_SL1500_.jpg" alt="Kabellose Kopfhörer">
                <h3>LETSACTIV Funkkopfhörer</h3>
                <p>Kabellose TV-Kopfhörer mit Sender-Ladestation, ideal für Senioren.</p>
                <p><strong>89,99 €</strong></p>
                <a href="https://www.amazon.de/dp/B0CTMJLR6Q" class="buy-button">Jetzt kaufen</a>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 4Deals | Alle Rechte vorbehalten</p>
        <p><a href="#agb">AGB</a> | <a href="#datenschutz">Datenschutz</a> | <a href="#impressum">Impressum</a></p>
    </footer>
</body>
</html>
