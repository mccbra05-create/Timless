# Timless
A streetwear brand
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Timeless.7</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #e6e6e6;
      color: #111;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      background: #e6e6e6;
    }

    .brand {
      font-size: 28px;
      font-weight: bold;
      letter-spacing: 2px;
    }

    .menu-btn {
      font-size: 28px;
      cursor: pointer;
    }

    .menu {
      position: fixed;
      top: 0;
      right: -100%;
      width: 70%;
      height: 100%;
      background: #111;
      color: white;
      padding: 40px;
      transition: 0.3s;
    }

    .menu a {
      display: block;
      color: white;
      text-decoration: none;
      font-size: 22px;
      margin-bottom: 20px;
    }

    .menu.active {
      right: 0;
    }

    .hero {
      padding: 60px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 16px;
      letter-spacing: 1px;
    }

    .section {
      padding: 40px 20px;
    }

    .product {
      background: #f2f2f2;
      padding: 20px;
      max-width: 400px;
      margin: auto;
    }

    .product h2 {
      margin: 10px 0;
    }

    .price {
      font-size: 22px;
      font-weight: bold;
    }

    .details {
      font-size: 14px;
      line-height: 1.6;
      color: #333;
    }

    button {
      margin-top: 20px;
      padding: 12px;
      width: 100%;
      background: #111;
      color: white;
      border: none;
      font-size: 16px;
      cursor: pointer;
    }
  </style>
</head>
<body>

<header>
  <div class="brand">TIMELESS.7</div>
  <div class="menu-btn" onclick="toggleMenu()">☰</div>
</header>

<div class="menu" id="menu">
  <a href="#">Home</a>
  <a href="#">Search</a>
  <a href="#">Clothes</a>
  <a href="#">Outerwear</a>
  <a href="#">Shirts</a>
  <a href="#">Bottoms</a>
  <a href="#">Long Sleeves</a>
  <a href="#"><strong>New Releases</strong></a>
</div>

<section class="hero">
  <h1>Timeless.</h1>
  <p>450 GSM • 100% Cotton • Built to Last</p>
</section>

<section class="section">
  <div class="product">
    <h2>Timeless.7 Tracksuit</h2>
    <p class="price">$90</p>
    <p class="details">
      • 450 GSM heavyweight cotton fleece<br>
      • 100% Cotton<br>
      • Distressed waistband & cuffs<br>
      • Faded graffiti-style logos<br>
      • Wide leg opening (13.5”)<br>
      • New Release
    </p>
    <button>Add to Cart</button>
  </div>
</section>

<script>
  function toggleMenu() {
    document.getElementById("menu").classList.toggle("active");
  }
</script>

</body>
</html>
