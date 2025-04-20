<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fairy Deluxe</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #f0f8ff;
      color: #333;
    }
    header {
      background-color: #b3e0ff;
      text-align: center;
      padding: 50px 20px;
    }
    .logo {
      width: 80px;
      height: 80px;
      background-color: white;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0 auto 20px;
      font-size: 2em;
      font-weight: bold;
      color: #2a90d9;
      box-shadow: 0 0 8px rgba(0, 0, 0, 0.1);
    }
    header h1 {
      margin: 0;
      font-size: 3em;
    }
    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .product {
      background-color: white;
      border-radius: 10px;
      padding: 20px;
      flex: 1 1 calc(33% - 40px);
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .product h3 {
      margin-top: 0;
    }
    .features ul {
      list-style-type: square;
      padding-left: 20px;
    }
    footer {
      background-color: #e6f7ff;
      text-align: center;
      padding: 30px 20px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">FD</div>
    <h1>Fairy Deluxe</h1>
    <p>Bringing Sparkle & Shine to Every Surface</p>
  </header>

  <section>
    <h2>About Us</h2>
    <p>Fairy Deluxe is a trusted manufacturer of premium cleaning chemicals and soaps. We focus on high-quality, eco-friendly solutions for homes, businesses, and industries alike.</p>
  </section>

  <section>
    <h2>Our Products</h2>
    <div class="products">
      <div class="product">
        <h3>Multi-Surface Cleaner</h3>
        <p>Perfect for kitchens, bathrooms, and countertops. Tough on grime, gentle on surfaces.</p>
      </div>
      <div class="product">
        <h3>Liquid Hand Soap</h3>
        <p>Moisturizing and antibacterial. Leaves hands soft and clean with every wash.</p>
      </div>
      <div class="product">
        <h3>Glass & Mirror Spray</h3>
        <p>Streak-free shine for all glass surfaces. Fast-drying and crystal clear results.</p>
      </div>
    </div>
  </section>

  <section class="features">
    <h2>Why Choose Fairy Deluxe?</h2>
    <ul>
      <li>Eco-friendly ingredients</li>
      <li>Safe for your family and pets</li>
      <li>Powerful cleaning with a gentle touch</li>
      <li>Trusted by professionals and households</li>
    </ul>
  </section>

  <footer>
    <h2>Contact Us</h2>
    <p>Email: contact@fairydeluxe.com</p>
    <p>&copy; 2025 Fairy Deluxe. All rights reserved.</p>
  </footer>
</body>
</html>
