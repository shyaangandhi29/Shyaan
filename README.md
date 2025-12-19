<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shyaan Clothing</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Shyaan Clothing</h1>
        <nav>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
            <div id="cart">Cart: <span id="cart-count">0</span> items</div>
        </nav>
    </header>
    
    <section id="hero">
        <h2>Welcome to Shyaan Clothing</h2>
        <p>Discover stylish, affordable clothes for every occasion.</p>
    </section>
    
    <section id="products">
        <h2>Our Products</h2>
        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="T-Shirt">
                <h3>Cotton T-Shirt</h3>
                <p>$20</p>
                <button onclick="addToCart('Cotton T-Shirt', 20)">Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Jeans">
                <h3>Denim Jeans</h3>
                <p>$50</p>
                <button onclick="addToCart('Denim Jeans', 50)">Add to Cart</button>
            </div>
            <!-- Add more products as needed -->
        </div>
    </section>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Shyaan Clothing offers high-quality, trendy apparel made with sustainable materials.</p>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: info@shyaanclothing.com | Phone: (123) 456-7890</p>
    </section>
    
    <footer>
        <p>&copy; 2023 Shyaan Clothing. All rights reserved.</p>
    </footer>
    
    <script src="script.js"></script>
</body>
</html>
