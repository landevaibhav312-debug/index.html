<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shopping Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
    }
    header {
      background: #2c3e50;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #34495e;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .product {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 5px;
      margin: 15px;
      padding: 15px;
      width: 250px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      max-width: 100%;
      height: auto;
    }
    .product h3 {
      margin: 10px 0;
    }
    .product p {
      color: #555;
      font-size: 16px;
    }
    .product button {
      background: #27ae60;
      color: #fff;
      border: none;
      padding: 10px 15px;
      cursor: pointer;
      border-radius: 3px;
      font-size: 14px;
    }
    .product button:hover {
      background: #219150;
    }
    footer {
      background: #2c3e50;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>🛒 My Shopping Page</h1>
    <p>Find the best deals here!</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Cart</a>
    <a href="#">Contact</a>
  </nav>

  <div class="container">
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Product 1">
      <h3>Product 1</h3>
      <p>$19.99</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Product 2">
      <h3>Product 2</h3>
      <p>$29.99</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Product 3">
      <h3>Product 3</h3>
      <p>$39.99</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Product 4">
      <h3>Product 4</h3>
      <p>$49.99</p>
      <button>Add to Cart</button>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 My Shopping Page. All rights reserved.</p>
  </footer>
</body>
</html>
