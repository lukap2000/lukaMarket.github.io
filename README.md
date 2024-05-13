<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shoes Trading Marketplace</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 20px;
        }
        h2 {
            color: #333;
        }
        .listing {
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 20px;
            overflow: hidden;
        }
        .listing img {
            max-width: 200px;
            max-height: 200px;
            margin-right: 20px;
            float: left;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Shoes Trading Marketplace</h1>
</header>

<nav>
    <a href="#listings">View Listings</a>
    <a href="#sell">Sell Your Shoes</a>
    <a href="#top-sellers">Top Seller Shoes</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">

    <section id="listings">
        <h2>Current Listings</h2>
        <div class="listing">
            <img src="https://via.placeholder.com/200" alt="Nike Air Max">
            <div>
                <h3>Nike Air Max</h3>
                <p>Price: $50</p>
                <p>Size: 10</p>
                <p>Condition: Like New</p>
                <p>Contact Seller: seller@example.com</p>
                <p>The Nike Air Max is a classic sneaker known for its comfortable cushioning and stylish design. Perfect for casual wear or running.</p>
            </div>
        </div>
        <div class="listing">
            <img src="https://via.placeholder.com/200" alt="Adidas Superstar">
            <div>
                <h3>Adidas Superstar</h3>
                <p>Price: $30</p>
                <p>Size: 9</p>
                <p>Condition: Used</p>
                <p>Contact Seller: seller2@example.com</p>
                <p>The Adidas Superstar is an iconic sneaker with a timeless design. Featuring a rubber shell toe and signature 3-stripes, it's a must-have for any sneaker collection.</p>
            </div>
        </div>
        <!-- Add more listings here -->
        <div class="listing">
            <img src="https://via.placeholder.com/200" alt="Jordan Retro">
            <div>
                <h3>Jordan Retro</h3>
                <p>Price: $120</p>
                <p>Size: 11</p>
                <p>Condition: New</p>
                <p>Contact Seller: seller3@example.com</p>
                <p>The Jordan Retro is a classic basketball shoe known for its high-top style and iconic Jumpman logo. It's a favorite among sneaker enthusiasts and basketball players alike.</p>
            </div>
        </div>
        <div class="listing">
            <img src="https://via.placeholder.com/200" alt="New Balance 990">
            <div>
                <h3>New Balance 990</h3>
                <p>Price: $150</p>
                <p>Size: 8</p>
                <p>Condition: Like New</p>
                <p>Contact Seller: seller4@example.com</p>
                <p>The New Balance 990 is a premium quality running shoe known for its exceptional comfort and stability. It's perfect for long-distance running or everyday wear.</p>
            </div>
        </div>
    </section>

    <section id="sell">
        <h2>Sell Your Shoes</h2>
        <p>To sell your shoes, please provide details about your shoes, including brand, size, condition, and price, along with your contact information.</p>
        <!-- Add a form for sellers to submit their listings -->
        <form action="#">
            <label for="brand">Brand:</label><br>
            <input type="text" id="brand" name="brand"><br>
            <label for="size">Size:</label><br>
            <input type="text" id="size" name="size"><br>
            <label for="condition">Condition:</label><br>
            <input type="text" id="condition" name="condition"><br>
            <label for="price">Price:</label><br>
            <input type="text" id="price" name="price"><br>
            <label for="contact">Contact Email:</label><br>
            <input type="email" id="contact" name="contact"><br><br>
            <input type="submit" value="Submit">
        </form>
    </section>

    <section id="top-sellers">
        <h2>Top Seller Shoes of the Month</h2>
        <ol>
            <li>Nike Air Max - Comfortable cushioning and stylish design</li>
            <li>Adidas Superstar - Iconic design with rubber shell toe</li>
            <li>Jordan Retro - Classic basketball shoe with high-top style</li>
            <li>New Balance 990 - Premium quality and exceptional comfort</li>
            <li>Vans Old Skool - Timeless skate shoe with iconic side stripe</

