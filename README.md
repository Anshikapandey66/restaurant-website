<!DOCTYPE html>
<html>
<head>
    <title>Foodie Restaurant</title>
    <style>
        body {
            margin: 0;
            font-family: Arial;
        }

        /* Navbar */
        .navbar {
            background: #333;
            padding: 15px;
            text-align: center;
        }
        .navbar a {
            color: white;
            margin: 15px;
            text-decoration: none;
            font-size: 18px;
        }

        /* Hero */
        .hero {
            background: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836') no-repeat center;
            background-size: cover;
            height: 400px;
            color: white;
            text-align: center;
            padding-top: 150px;
        }
        .hero h1 {
            font-size: 40px;
        }
        .btn {
            background: red;
            padding: 10px 20px;
            color: white;
            border: none;
        }

        /* Menu */
        .menu {
            padding: 40px;
            text-align: center;
        }
        .menu-item {
            display: inline-block;
            width: 200px;
            margin: 20px;
        }

        /* Footer */
        .footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>

<body>

<!-- Navbar -->
<div class="navbar">
    <a href="#">Home</a>
    <a href="#">Menu</a>
    <a href="#">Contact</a>
</div>

<!-- Hero Section -->
<div class="hero">
    <h1>Welcome to Foodie</h1>
    <button class="btn">Order Now</button>
</div>

<!-- Menu -->
<div class="menu">
    <h2>Our Menu</h2>

    <div class="menu-item">
        <h3>Pizza</h3>
        <p>₹199</p>
    </div>

    <div class="menu-item">
        <h3>Burger</h3>
        <p>₹99</p>
    </div>

    <div class="menu-item">
        <h3>Pasta</h3>
        <p>₹149</p>
    </div>

</div>

<!-- Footer -->
<div class="footer">
    <p>© 2026 Foodie Restaurant</p>
</div>

</body>
</html># restaurant-website
