<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Skyvien Store</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f0f8ff;
      color: #333;
    }
    header {
      background: #0047ab;
      color: white;
      padding: 15px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    nav ul {
      list-style: none;
      padding: 0;
      margin: 10px 0;
      display: flex;
      justify-content: center;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 50px 20px;
      background: linear-gradient(to right, #0047ab, #0e6eb8);
      color: white;
    }
    .btn {
      background: white;
      color: #0047ab;
      padding: 10px 20px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #0047ab;
      color: white;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Skyvien Store</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <h2>Welcome to Skyvien Store</h2>
    <p>Your favorite place for quality products!</p>
    <a href="#products" class="btn">Shop Now</a>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Skyvien Store. All rights reserved.</p>
  </footer>
</body>
</html>
