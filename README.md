<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>General Auto Works | Car Repair & Service</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0b0b0b;
      color: white;
      line-height: 1.6;
    }

    header {
      background: #111;
      padding: 18px 20px;
      text-align: center;
      border-bottom: 2px solid #e63946;
    }

    header h1 {
      font-size: 28px;
      color: #fff;
    }

    header p {
      color: #bbb;
      margin-top: 5px;
    }

    .hero {
      min-height: 430px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 40px 20px;
      background:
        linear-gradient(rgba(0,0,0,.72), rgba(0,0,0,.85)),
        #222;
    }

    .hero h2 {
      font-size: 38px;
      margin-bottom: 15px;
    }

    .hero h2 span {
      color: #e63946;
    }

    .hero p {
      color: #ddd;
      font-size: 17px;
      max-width: 600px;
      margin: auto;
    }

    .buttons {
      margin-top: 25px;
    }

    .btn {
      display: inline-block;
      padding: 13px 22px;
      margin: 6px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    .call {
      background: #e63946;
      color: white;
    }

    .whatsapp {
      background: #25D366;
      color: white;
    }

    section {
      padding: 45px 20px;
      max-width: 1000px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      font-size: 30px;
      margin-bottom: 30px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
      gap: 18px;
    }

    .card {
      background: #151515;
      padding: 25px 18px;
      border-radius: 12px;
      text-align: center;
      border: 1px solid #292929;
    }

    .card h3 {
      color: #e63946;
      margin-bottom: 10px;
    }

    .card p {
      color: #bbb;
    }

    .about {
      background: #111;
      max-width: none;
      text-align: center;
    }

    .about-content {
      max-width: 800px;
      margin: auto;
    }

    .contact {
      text-align: center;
    }

    .contact-box {
      background: #151515;
      padding: 25px;
      border-radius: 12px;
      max-width: 600px;
      margin: auto;
    }

    .contact-box p {
      margin: 12px 0;
      color: #ddd;
    }

    footer {
      background: #080808;
      text-align: center;
      padding: 22px;
      color: #888;
      border-top: 1px solid #222;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 30px;
      }

      header h1 {
        font-size: 23px;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>GENERAL AUTO WORKS</h1>
  <p>Car Repair • Service • Diagnostics</p>
</header>

<div class="hero">
  <div>
    <h2>Your Car, <span>Our Care</span></h2>
    <p>
      Professional car repair and maintenance services.
      Quality work for all major car brands.
    </p>

    <div class="buttons">
      <a class="btn call" href="tel:YOUR_PHONE">📞 Call Now</a>
      <a class="btn whatsapp" href="https://wa.me/YOUR_PHONE">💬 WhatsApp</a>
    </div>
  </div>
</div>

<section>
  <h2>Our Services</h2>

  <div class="services">

    <div class="card">
      <h3>🔧 Car Repair</h3>
      <p>Complete mechanical repair and maintenance.</p>
    </div>

    <div class="card">
      <h3>💻 Computer Diagnostics</h3>
      <p>OBD scanning and vehicle fault diagnosis.</p>
    </div>

    <div class="card">
      <h3>❄️ AC Service</h3>
      <p>Car AC checking, gas charging and repair.</p>
    </div>

    <div class="card">
      <h3>⚙️ Engine Work</h3>
      <p>Engine inspection, repair and maintenance.</p>
    </div>

    <div class="card">
      <h3>🚗 Brake Service</h3>
      <p>Brake inspection, repair and replacement.</p>
    </div>

    <div class="card">
      <h3>✨ Car Polish</h3>
      <p>Professional car cleaning and polishing.</p>
    </div>

  </div>
</section>

<section class="about">
  <div class="about-content">
    <h2>About General Auto Works</h2>

    <p>
      General Auto Works provides reliable automobile repair,
      servicing and diagnostic solutions. Our focus is on
      quality workmanship and proper vehicle diagnosis.
    </p>
  </div>
</section>

<section class="contact">
  <h2>Contact Us</h2>

  <div class="contact-box">
    <p>📍 <strong>General Auto Works</strong></p>

    <p>
      📞 <a href="tel:YOUR_PHONE" style="color:#e63946;">
        YOUR PHONE NUMBER
      </a>
    </p>

    <p>
      💬 <a href="https://wa.me/YOUR_PHONE"
      style="color:#25D366;">
        Chat on WhatsApp
      </a>
    </p>

    <p>🕒 Open for Car Service & Repair</p>
  </div>
</section>

<footer>
  © 2026 General Auto Works. All Rights Reserved.
</footer>

</body>
</html>
