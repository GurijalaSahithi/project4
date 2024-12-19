<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tiffin Service</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }

        nav a:hover {
            background-color: #ddd;
            color: black;
        }

        .container {
            padding: 20px;
        }

        .menu-item {
            border: 1px solid #ddd;
            margin: 10px;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Tiffin Service</h1>
</header>

<nav>
    <a href="#menu">Menu</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-item">
            <h3>Dish Name 1</h3>
            <p>Description of Dish 1</p>
            <button>Order Now</button>
        </div>
        <div class="menu-item">
            <h3>Dish Name 2</h3>
            <p>Description of Dish 2</p>
            <button>Order Now</button>
        </div>
        <div class="menu-item">
            <h3>Dish Name 3</h3>
            <p>Description of Dish 3</p>
            <button>Order Now</button>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We connect you with local tiffin service providers, delivering delicious home-cooked meals straight to your doorstep.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@tiffinservice.com</p>
        <p>Phone: +123-456-7890</p>
    </section>
</div>

<footer>
    <p>&copy; 2024 Tiffin Service. All rights reserved.</p>
</footer>

</body>
</html>
