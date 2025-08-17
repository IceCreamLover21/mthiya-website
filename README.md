<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mthiya Tradings and Projects</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
    }
    header {
      background-color: #2A316F; /* main blue from your logo */
      padding: 20px;
      text-align: center;
      color: white;
    }
    header img {
      max-width: 200px;
      height: auto;
      margin-bottom: 10px;
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
    section {
      padding: 40px;
      text-align: center;
    }
    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    .contact {
      background: #ecf0f1;
      padding: 40px;
    }
    form {
      max-width: 500px;
      margin: 0 auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    form label {
      display: block;
      margin: 10px 0 5px;
      text-align: left;
    }
    form input {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      background: #2c3e50;
      color: #fff;
      padding: 12px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
    }
    form button:hover {
      background: #1a252f;
    }
    footer {
      background: #2c3e50;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
    @media (max-width: 600px) {
      header img {
        max-width: 150px;
      }
      section {
        padding: 20px;
      }
      form {
        width: 90%;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="IMG-20250816-WA0000.jpg" alt="Mthiya Tradings and Projects Logo">
    <p>📞 <a href="tel:+27712345678" style="color:white; text-decoration:none;">+27 720 448 395</a> | 
       ✉️ <a href="mailto:info@mthiyatradingsandprojects.co.za" style="color:white; text-decoration:none;">Mthiyatrading241@gmail.com</a></p>
      <a> 
          
      </a><p>Office:<a/></p>
       <p>822 milton crescent Grobler Park, Roodepoort  Soith Africa</p>
</header>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="services">
    <h2>Our Services</h2>
    <p>We specialize in building renovations, home improvements, office remodeling, and construction management.</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form id="contactForm">
      <label for="name">First Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="surname">Surname:</label>
      <input type="text" id="surname" name="surname" required>

      <label for="Tell">Tell Number:</label>
      <input type="tel" id="Tell" name="Tell" required>
      
      <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

      <label for="company">Company Name:</label>
      <input type="text" id="company" name="company">

      <button type="submit">Send Request</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Mthiya Tradings and Projects. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById('contactForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Thank you! Your contact request has been sent.');
      this.reset();
    });
  </script>

</body>
</html>
