<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>My Travel Dream Website</title>

  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">

  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f9f9;
      color: #333;
      scroll-behavior: smooth;
    }
    header {
      background-color: #1d3557;
      color: white;
      padding: 20px 0;
    }
    .navbar-nav a {
      color: white !important;
      font-weight: 600;
      cursor: pointer;
      margin-right: 15px;
    }
    .section-box {
      background-color: white;
      padding: 25px;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      margin: 40px auto;
      max-width: 900px;
    }
    h1, h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    h1 {
      color: white;
    }
    h2 {
      color: #1d3557;
    }
    .destination {
      text-align: center;
      margin-bottom: 40px;
    }
    .destination img {
      width: 200px;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      margin: 5px;
    }
    .highlight-text {
      border: 2px solid orange;
      padding: 10px;
      border-radius: 8px;
      text-align: center;
      max-width: 700px;
      margin: 15px auto 0 auto;
    }
    a.btn-link {
      background-color: #ffb703;
      color: white;
      padding: 12px 20px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      display: inline-block;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      margin-top: 20px;
    }
    footer {
      text-align: center;
      margin-top: 50px;
      padding: 20px;
      background-color: #e0e0e0;
      font-size: 14px;
    }
    #scroll-top {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background: #ff9f1c;
      color: white;
      border-radius: 50%;
      width: 40px;
      height: 40px;
      text-align: center;
      line-height: 40px;
      font-size: 24px;
      cursor: pointer;
      display: none;
      z-index: 9999;
    }
    #scroll-top:hover {
      background: #fb8500;
    }
  </style>
</head>
<body>

<header class="d-flex justify-content-between align-items-center px-4">
  <h1>Dream Travel 💗</h1>
  <nav>
    <ul class="navbar-nav flex-row mb-0">
      <li class="nav-item"><a class="nav-link" href="#about">About Me</a></li>
      <li class="nav-item"><a class="nav-link" href="#destinations">Top 6 Travel Destinations</a></li>
      <li class="nav-item"><a class="nav-link" href="#facts">Facts & Why I Want to Travel</a></li>
      <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<!-- Top Bar -->
<div style="background-color: #ffb703; color: white; padding: 15px 0; text-align: center; font-size: 22px; font-weight: bold;">
  ✈️ Dream Travel Destinations 💗
</div>

<!-- Welcome -->
<div id="welcomeMsg" style="text-align:center; font-size: 20px; padding: 20px 0;">
  👋 Welcome to my website!
</div>

<!-- About -->
<section class="section-box" id="about">
  <h2>About Me 👋</h2>
  <p>Hello! My name is Nafisha Shamiha Islam. I go by Miha as well! I love to travel and explore different cultures, foods, history, and scenery from around the world. Traveling gives me comfort. This website is a small reflection of the places I want to visit someday. I believe travel opens the heart and mind! I'm excited to share my dream destinations with you!</p>
</section>
<p style="text-align: center; font-size: 0.9em; color: gray;">
  Template source: <a href="https://themewagon.github.io/iPortfolio/index.html" target="_blank">iPortfolio Template by Themewagon</a>
</p>

<!-- Destinations -->
<section class="section-box" id="destinations">
  <h2>Top 6 Dream Travel Destinations ✈️</h2>
  <!-- repeat .destination blocks here like you already had -->
</section>

<!-- Facts -->
<section class="section-box" id="facts">
  <h2>Facts & Why I Want to Visit These Places 💬</h2>
  <p>Each place holds something special... collected some fun facts and personal reasons for visiting each of these destinations.</p>
  <a href="factsandwhyiwanttotravel.html" class="btn-link" target="_blank">📍 Click here to view the facts and reasons</a>
</section>

<!-- Suggestion Prompt -->
<div class="text-center my-4">
  <h2>✨ Tell me your dream destination!</h2>
  <button onclick="suggestDestination()">Click Here</button>
  <p id="destinationResponse" style="font-weight: bold; margin-top: 10px;"></p>
</div>

<!-- Contact -->
<section class="section-box" id="contact">
  <h2>Contact 📧</h2>
  <p>If you have any questions, suggestions, or just want to say hello, feel free to reach out to me!</p>
  <p>Email: <a href="mailto:s24224019@al.tiu.ac.jp">s24224019@al.tiu.ac.jp</a></p>
</section>

<!-- Footer -->
<footer>
  <p>Student ID: 24224019 | Name: Nafisha Shamiha Islam</p>
</footer>

<!-- Scroll Top -->
<div id="scroll-top" onclick="window.scrollTo({top:0, behavior:'smooth'});">
  <i class="bi bi-arrow-up-short"></i>
</div>

<!-- JavaScript -->
<script>
  document.getElementById("welcomeMsg").innerText = "👋 Welcome to my website!";

  function suggestDestination() {
    const place = prompt("Where would you love to go?");
    if (place) {
      document.getElementById("destinationResponse").innerText = "That sounds amazing! " + place + " is definitely worth visiting!";
    }
  }

  window.addEventListener('scroll', () => {
    const scrollBtn = document.getElementById('scroll-top');
    scrollBtn.style.display = window.scrollY > 300 ? 'block' : 'none';
  });
</script>

</body>
</html>

