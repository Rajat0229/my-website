<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MapleOne Movers</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #ffffff;
      color: #333;
    }
    header {
      background-color: #d32f2f;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background-color: #b71c1c;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: 600;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background-image: url('https://images.unsplash.com/photo-1581091215367-2d587ef2c2df');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 6rem 2rem;
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto;
    }
    .btn {
      display: inline-block;
      margin-top: 2rem;
      padding: 0.8rem 2rem;
      background-color: white;
      color: #b71c1c;
      font-weight: bold;
      border-radius: 8px;
      text-decoration: none;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    footer {
      background-color: #212121;
      color: white;
      text-align: center;
      padding: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>MapleOne Movers</h1>
    <p>Moving Canada with Care</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero" id="home">
    <h1>Your Trusted Moving Partner</h1>
    <p>Whether it's local or long distance, residential or commercial—MapleOne Movers makes moving smooth and stress-free.</p>
    <a class="btn" href="#contact">Get a Free Quote</a>
  </div>

  <section id="about">
    <h2>About Us</h2>
    <p>With over 5 years of experience, MapleOne Movers is proud to be one of Canada's most reliable moving companies. We’re fully licensed, insured, and committed to providing top-quality service every step of the way.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Residential Moving</li>
      <li>Commercial & Office Moves</li>
      <li>Long Distance Relocations</li>
      <li>Packing & Unpacking</li>
      <li>Storage Solutions</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@mapleonemovers.ca</p>
    <p>Phone: +1 (123) 456-7890</p>
    <p>Location: Based in Calgary, AB – Serving across Canada</p>
  </section>

  <footer>
    <p>&copy; 2025 MapleOne Movers. All rights reserved.</p>
  </footer>
</body>
</html>
