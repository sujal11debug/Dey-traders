# Dey-traders
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dey Traders</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
    }

    header {
      background: #2b7a0b;
      color: white;
      padding: 1rem 2rem;
      text-align: center;
    }

    nav {
      background: #226600;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      padding: 1rem;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      background: #1a5205;
    }

    .section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5rem;
    }

    .product-card {
      background: white;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    footer {
      background: #2b7a0b;
      color: white;
      text-align: center;
      padding: 1rem;
    }

    h2 {
      color: #226600;
    }
  </style>
</head>
<body>

  <header>
    <h1>Dey Traders</h1>
    <p>High-Quality Seeds, Fertilizers & Crop Protection – Locally Delivered</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div id="home" class="section">
    <h2>Welcome to Dey Traders</h2>
    <p>Your trusted local supplier of maize and paddy seeds, fertilizers, pesticides, and weedicides. Serving local farmers with the best agricultural inputs at affordable prices.</p>
  </div>

  <div id="products" class="section">
    <h2>Our Products</h2>
    <div class="products-grid">
      <div class="product-card">
        <h3>Maize Seeds</h3>
        <p>High-yield hybrid and local maize seeds suitable for your farm's soil and climate.</p>
      </div>
      <div class="product-card">
        <h3>Paddy Seeds</h3>
        <p>Certified paddy seeds for better germination, yield, and disease resistance.</p>
      </div>
      <div class="product-card">
        <h3>Fertilizers</h3>
        <p>Urea, DAP, Potash and other essential fertilizers to boost crop growth.</p>
      </div>
      <div class="product-card">
        <h3>Pesticides</h3>
        <p>Effective solutions to protect your crops from harmful pests and insects.</p>
      </div>
      <div class="product-card">
        <h3>Weedicides</h3>
        <p>Top-performing weed control products for cleaner, healthier fields.</p>
      </div>
    </div>
  </div>

  <div id="about" class="section">
    <h2>About Us</h2>
    <p>Dey Traders has been serving the local farming community with reliable agricultural supplies. We believe in honest pricing, expert advice, and building long-term relationships with our customers. Come visit us for personal service and quality you can count on.</p>
  </div>

  <div id="contact" class="section">
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> [Your Shop Address Here]</p>
    <p><strong>Phone:</strong> +91-XXXXXXXXXX</p>
    <p><strong>WhatsApp:</strong> [WhatsApp Link]</p>
    <p><strong>Business Hours:</strong> Mon–Sat, 9am–6pm</p>
  </div>

  <footer>
    <p>&copy; 2025 Dey Traders. All rights reserved.</p>
  </footer>

</body>
</html>
