<html lang="en">
<head>
 <title>Dream Travel</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top py-3">
  <div class="container">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
      data-bs-target="#navbarContent" aria-controls="navbarContent" aria-expanded="false"
      aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarContent">
      <ul class="navbar-nav ms-auto align-items-center">
        <li class="nav-item px-3">
          <a class="nav-link" href="#about">About Me</a>
        </li>
        <li class="nav-item px-3">
          <a class="nav-link" href="#destinations">Destinations</a>
        </li>
        <li class="nav-item px-3">
          <a class="nav-link" href="#facts">Why I Want to Travel</a>
        </li>
        <li class="nav-item px-3">
          <a class="nav-link" href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</body>
<!-- Add this to make the navbar not overlap your content -->
<div style="height: 80px;"></div>
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
</head>
<body>
<div class="top-bar">
  ✈️ Dream Travel Destinations 💗
</div>
<div id="welcomeMsg">👋 Welcome to my website!</div>
<section id="about">
  <h2>About Me 👋</h2>
  <p>Hello! My name is Nafisha Shamiha Islam. I go by Miha as well! I love to travel and explore different cultures, foods, history, and scenery from around the world. Traveling gives me comfort. This website is a small reflection of the places I want to visit someday. I believe travel opens the heart and mind! I'm excited to share my dream destinations with you!</p>
</section>

<div class="text-center">
  <h2>✨ Tell me your dream destination!</h2>
  <button onclick="suggestDestination()" class="btn-warning">Click Here</button>
  <p id="destinationResponse" style="font-weight: bold; margin-top: 10px;"></p>
</div>

<section style="text-align:center; font-size: 0.9em; color: gray; margin: 30px auto;">
  Template source: 
  <a href="https://themewagon.github.io/jadoo/v1.0.0/" target="_blank" rel="noopener noreferrer" style="color: #1d3557;">
    Jadoo Template by Themewagon
  </a>
</section>

<section id="destinations">
  <h2>Top 6 Dream Travel Destinations ✈️</h2>

  <div class="destination">
    <h3>1. Istanbul, Turkey 🕌</h3>
    <img src="istanbul1.jpeg" style="width: 200px; height: 150px;" alt="Istanbul view" />
    <img src="istanbul3.jpeg" style="width: 200px; height: 150px;" alt="Istanbul city street" />
    <img src="istanbul5.jpeg" style="width: 200px; height: 150px;" alt="Istanbul cat" />
    <img src="istanbul4.jpeg" style="width: 200px; height: 150px;" alt="Istanbul cat" />
    <h4 class="highlight-text">Rich in culture and history, Istanbul connects Europe and Asia in a magical way.</h4>
  </div>

  <div class="destination">
    <h3>2. Paris, France 🗼</h3>
    <img src="paris1.jpeg" style="width: 200px; height: 150px;" alt="Eiffel Tower" />
    <img src="paris5.jpeg" style="width: 200px; height: 150px;" alt="Paris view" />
    <img src="paris2.jpeg" style="width: 200px; height: 150px;" alt="Paris monument" />
    <img src="paris4.jpeg" style="width: 200px; height: 150px;" alt="Paris coffee shop" />
    <h4 class="highlight-text">Fall in love with the City of Lights – home to the Eiffel Tower and world-famous art.</h4>
  </div>

  <div class="destination">
    <h3>3. Edinburgh, Scotland 🏰</h3>
    <img src="edinburgh1.jpeg" style="width: 200px; height: 150px;" alt="Edinburgh castle" />
    <img src="edinburgh3.jpeg" style="width: 200px; height: 150px;" alt="Edinburgh street" />
    <img src="edinburgh4.jpeg" style="width: 200px; height: 150px;" alt="Edinburgh bookstore" />
    <img src="edinburgh5.jpeg" style="width: 200px; height: 150px;" alt="Edinburgh street" />
    <h4 class="highlight-text">Stunning castles, cozy pubs, and beautiful highlands await you in Scotland's capital.</h4>
  </div>

  <div class="destination">
    <h3>4. Santorini, Greece 🌊</h3>
    <img src="greece5.jpeg" style="width: 200px; height: 150px;" alt="Greece" />
    <img src="greece2.jpeg" style="width: 200px; height: 150px;" alt="Greece river" />
    <img src="greece3.jpeg" style="width: 200px; height: 150px;" alt="Greece street" />
    <img src="greece4.jpeg" style="width: 200px; height: 150px;" alt="Greece street" />
    <h4 class="highlight-text">Famous for its white-washed buildings and unforgettable Aegean sunsets.</h4>
  </div>

  <div class="destination">
    <h3>5. Zurich, Switzerland 🏔️</h3>
    <img src="switzerland5.jpeg" style="width: 200px; height: 150px;" alt="Swan" />
    <img src="switzerland3.jpeg" style="width: 200px; height: 150px;" alt="Switzerland" />
    <img src="switzerland2.jpeg" style="width: 200px; height: 150px;" alt="River" />
    <img src="switzerland4.jpeg" style="width: 200px; height: 150px;" alt="Train" />
    <h4 class="highlight-text">Enjoy majestic Alps, serene lakes, and some of the best chocolate on Earth.</h4>
  </div>

  <div class="destination">
    <h3>6. Vienna, Austria 🎻</h3>
    <img src="vienna5.jpeg" style="width: 200px; height: 150px;" alt="Vienna castle" />
    <img src="vienna2.jpeg" style="width: 200px; height: 150px;" alt="Museum" />
    <img src="vienna3.jpeg" style="width: 200px; height: 150px;" alt="Museum" />
    <img src="vienna1.jpeg" style="width: 200px; height: 150px;" alt="Castle" />
    <h4 class="highlight-text">Enjoy coffeehouse culture, home of Mozart, beautiful museums, and operas.</h4>
  </div>
</section>

<section id="facts">
  <h2>Facts & Why I Want to Visit These Places 💬</h2>
  <p>Each place holds something special, whether it’s history, beauty, adventure, or peace. I’ve collected some fun facts and my personal reasons for wanting to visit each of these amazing destinations.</p>
  <p class="text-center"><a href="factsandwhyiwanttotravel.html" class="btn-link" target="_blank" rel="noopener noreferrer">📍 Click here to view the facts and reasons</a></p>
</section>

<section id="contact">
  <h2>Contact 📧</h2>
  <p>If you have any questions, suggestions, or just want to say hello, feel free to reach out to me!</p>
  <p>Email: <a href="mailto:s24224019@al.tiu.ac.jp" style="color: #1d3557; font-weight: bold;">s24224019@al.tiu.ac.jp</a></p>
</section>

<footer>
  <p>Student ID: 24224019 | Name: Nafisha Shamiha Islam</p>
</footer>

<div id="scroll-top" title="Scroll to top" onclick="window.scrollTo({top:0, behavior:'smooth'});">&#8679;</div>

<script>
  // Welcome message
  document.getElementById("welcomeMsg").innerText = "👋 Welcome to my website!";

  // Interactive prompt
  function suggestDestination() {
    const place = prompt("Where would you love to go?");
    if (place) {
      document.getElementById("destinationResponse").innerText =
        "That sounds amazing! " + place + " is definitely worth visiting!";
    }
  }

  // Show/hide scroll to top button
  window.addEventListener('scroll', () => {
    const scrollBtn = document.getElementById('scroll-top');
    scrollBtn.style.display = window.scrollY > 300 ? 'block' : 'none';
  });
</script>
</body>
</html>
