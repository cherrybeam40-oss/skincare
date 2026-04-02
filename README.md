# skincare
A skin care business website template. 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Glow Skincare</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      line-height: 1.6;
      color: #333;
    }

    header {
      height: 100vh;
      background: linear-gradient(to right, #fbc2eb, #a6c1ee);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .btn {
      padding: 12px 30px;
      background: white;
      color: #333;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      font-weight: 500;
      transition: 0.3s;
      text-decoration: none;
    }

    .btn:hover {
      background: #333;
      color: white;
    }

    section {
      padding: 60px 20px;
      text-align: center;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #444;
    }

    p {
      max-width: 600px;
      margin: auto;
      margin-bottom: 30px;
    }

    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .card {
      background: #f9f9f9;
      padding: 20px;
      width: 260px;
      border-radius: 15px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.15);
    }

    .card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 10px;
    }

    .testimonials p {
      font-style: italic;
      margin: 10px 0;
    }

    footer {
      background: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }

    /* Responsive */
    @media(max-width: 768px){
      .services {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>

<body>

  <!-- Hero Section -->
  <header>
    <h1>Glow Skincare</h1>
    <p>Clear skin starts here</p>
    <a href="#contact" class="btn">Book Now</a>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Us</h2>
    <p>Glow Skincare provides effective and affordable skincare products to help you achieve healthy, glowing skin. Your confidence starts with your skin!</p>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <img src="https://source.unsplash.com/260x160/?acne,skincare" alt="Acne Treatment">
        <h3>Acne Treatment</h3>
        <p>Personalized solutions for acne-prone skin.</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/260x160/?beauty,skin" alt="Brightening">
        <h3>Brightening Products</h3>
        <p>Enhance your natural glow with our products.</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/260x160/?consultation,skincare" alt="Consultation">
        <h3>Skincare Consultation</h3>
        <p>Expert advice tailored to your skin type.</p>
      </div>
    </div>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials" class="testimonials">
    <h2>Testimonials</h2>
    <p>"My skin improved in just 2 weeks! Highly recommend Glow Skincare."</p>
    <p>"Affordable, effective, and high-quality products. Love it!"</p>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Phone/WhatsApp: 0712345678 | Location: Nairobi, Kenya</p>
    <a href="https://wa.me/254712345678" class="btn">Message Us</a>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Glow Skincare. All rights reserved.</p>
  </footer>

</body>
</html>
