<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Landing Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
    }
    header {
      background: #2c3e50;
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 3em;
      margin: 0;
    }
    header p {
      font-size: 1.2em;
      margin-top: 10px;
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
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .section h2 {
      margin-bottom: 20px;
      color: #2c3e50;
    }
    .btn {
      display: inline-block;
      background: #27ae60;
      color: #fff;
      padding: 12px 20px;
      border-radius: 5px;
      text-decoration: none;
      font-size: 16px;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #219150;
    }
    footer {
      background: #2c3e50;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Landing Page</h1>
    <p>Your one-stop solution for awesome products and services</p>
    <a href="#about" class="btn">Learn More</a>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#features">Features</a>
    <a href="#contact">Contact</a>
  </nav>

  <div id="about" class="section">
    <h2>About Us</h2>
    <p>We provide high-quality solutions tailored to your needs. Our mission is to deliver excellence.</p>
  </div>

  <div id="features" class="section">
    <h2>Features</h2>
    <p>✔ Easy to use<br>✔ Responsive design<br>✔ Fast and reliable<br>✔ Customer-focused</p>
    <a href="#contact" class="btn">Get Started</a>
  </div>

  <div id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: info@example.com<br>Phone: +91 98765 43210</p>
  </div>

  <footer>
    <p>&copy; 2025 My Landing Page. All rights reserved.</p>
  </footer>
</body>
</html>
