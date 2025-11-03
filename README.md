<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GreenSprout - Gardening Startup</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #f5f9f6;
      color: #2e2e2e;
    }

    header {
      background-color: #3b7a57;
      color: white;
      text-align: center;
      padding: 1.5rem 0;
      font-size: 1.8rem;
      letter-spacing: 1px;
    }

    nav {
      background-color: #2e6045;
      display: flex;
      justify-content: center;
      padding: 0.7rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: 500;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #a8e6cf;
    }

    .hero {
      background-image: url('https://images.unsplash.com/photo-1524594227085-4e82ab9b9c39?auto=format&fit=crop&w=1600&q=80');
      background-size: cover;
      background-position: center;
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
      text-align: center;
    }

    .hero h1 {
      font-size: 3rem;
    }

    .hero p {
      font-size: 1.2rem;
      margin-top: 1rem;
      max-width: 600px;
    }

    .btn {
      margin-top: 1.5rem;
      padding: 0.8rem 1.8rem;
      background-color: #3b7a57;
      border: none;
      border-radius: 25px;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .btn:hover {
      background-color: #2e6045;
    }

    section {
      padding: 3rem 1.5rem;
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }

    h2 {
      color: #3b7a57;
      margin-bottom: 1rem;
    }

    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      margin-top: 2rem;
    }

    .service {
      background: white;
      padding: 1.5rem;
      width: 280px;
      margin: 1rem;
      border-radius: 15px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .service h3 {
      color: #3b7a57;
      margin-bottom: 0.5rem;
    }

    footer {
      background-color: #2e6045;
      color: white;
      text-align: center;
      padding: 1rem 0;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>🌿 GreenSprout - Gardening Startup</header>
  
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero" id="home">
    <h1>Grow Green, Live Clean</h1>
    <p>We bring nature closer to you — indoor plants, vertical gardens, and eco-friendly landscaping.</p>
    <button class="btn">Explore Our Services</button>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>
      GreenSprout is a modern gardening startup dedicated to transforming urban spaces into green, thriving environments.
      We offer personalized gardening solutions for homes, schools, and offices — combining sustainability with style.
    </p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service">
        <h3>Indoor Plants</h3>
        <p>Beautify your home with air-purifying and low-maintenance plants.</p>
      </div>
      <div class="service">
        <h3>Landscape Design</h3>
        <p>Custom garden layouts for homes, offices, and public spaces.</p>
      </div>
      <div class="service">
        <h3>Maintenance</h3>
        <p>Regular plant care, pruning, and seasonal planting support.</p>
      </div>
      <div class="service">
        <h3>Eco Workshops</h3>
        <p>Learn about composting, sustainability, and urban gardening (coming soon!).</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@greensprout.com</p>
    <p>Address: GreenSprout Gardens, Pune, India</p>
  </section>

  <footer>
    &copy; 2025 GreenSprout | Designed with 🌱 Love for Nature
  </footer>
</body>
</html>
