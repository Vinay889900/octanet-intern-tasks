<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vegetable Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #343a40;
            text-align: center;
        }

        header {
            background-color: #28a745;
            color: #fff;
            padding: 20px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }

        section {
            padding: 50px;
        }

        h1, h2 {
            margin-bottom: 20px;
        }

        .product {
            margin-bottom: 30px;
        }

        .product img {
            width: 80%;
            border-radius: 10px;
        }

        footer {
            background-color: #28a745;
            color: #fff;
            padding: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Vegetable Shop</h1>
        <nav>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Vegetable 1">
            <h3>Tomatoes</h3>
            <p>Fresh and juicy tomatoes for your salads and recipes.</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Vegetable 2">
            <h3>Carrots</h3>
            <p>Crunchy carrots packed with vitamins and minerals.</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Vegetable 3">
            <h3>Spinach</h3>
            <p>Nutritious spinach leaves perfect for salads and smoothies.</p>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We are dedicated to providing fresh and high-quality vegetables to our customers. Our produce comes directly from local farmers, ensuring the best quality and supporting the community.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@vegetableshop.com</p>
        <p>Phone: 123-456-7890</p>
    </section>

    <footer>
        <p>&copy; 2024 Vegetable Shop. All rights reserved.</p>
    </footer>
</body>
</html>
