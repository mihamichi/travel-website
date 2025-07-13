<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
</head>
<body>
<header class="d-flex justify-content-between align-items-center px-4">
  <h1>Dream Travel 💗</h1>
  <nav>
    <ul class="navbar-nav flex-row gap-4 mb-0">
      <li><a href="#about">About Me</a></li>
      <li><a href="#destinations">Top 6 Travel Destinations</a></li>
      <li><a href="#facts">Facts & Why I Want to Travel</a></li>
	  <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>
<!-- Yellow top bar -->
<div style="background-color: #ffb703; color: white; padding: 15px 0; text-align: center; font-size: 22px; font-weight: bold;">
  ✈️ Dream Travel Destinations 💗
</div>
<!-- Welcome Message -->
<div id="welcomeMsg" style="text-align:center; font-size: 20px; padding: 20px 0;">
  👋 Welcome to my website!	
<!-- About Me Section -->
<section class="section-box" id="about">
  <h2>About Me 👋</h2>
  <p>Hello! My name is Nafisha Shamiha Islam. I go by Miha as well! I love to travel and explore different cultures, foods, history, and scenery from around the world. Traveling gives me comfort. This website is a small reflection of the places I want to visit someday. I believe travel opens the heart and mind! I'm excited to share my dream destinations with you!</p>
</section>
 <!-- Template Credit -->
  <p style="margin-top: 20px; font-size: 0.9em; color: gray;">
    Template source: 
    <a href="https://themewagon.github.io/iPortfolio/index.html" target="_blank" rel="noopener noreferrer">
      iPortfolio Template by Themewagon
    </a>
  </p>
<!-- Top 6 Destinations Section -->
<section class="section-box" id="destinations">
  <h2>Top 6 Dream Travel Destinations ✈️</h2>
  <div class="destination">
    <h3>1. Istanbul, Turkey 🕌</h3>
    <img src="istanbul1.jpeg" alt="Istanbul view" />
    <img src="istanbul3.jpeg" alt="Istanbul city street" />
    <img src="istanbul5.jpeg" alt="Istanbul cat" />
    <h4 class="highlight-text">
      Rich in culture and history, Istanbul connects Europe and Asia in a magical way.
    </h4>
  </div>
  <div class="destination">
    <h3>2. Paris, France 🗼</h3>
    <img src="paris1.jpeg" alt="Eiffel Tower" />
    <img src="paris5.jpeg" alt="Paris view" />
    <img src="paris2.jpeg" alt="Paris monument" />
    <img src="paris4.jpeg" alt="Paris coffee shop" />
    <h4 class="highlight-text">
      Fall in love with the City of Lights – home to the Eiffel Tower and world-famous art.
    </h4>
  </div>
  <div class="destination">
    <h3>3. Edinburgh, Scotland 🏰</h3>
    <img src="edinburgh1.jpeg" alt="Edinburgh castle" />
    <img src="edinburgh3.jpeg" alt="Edinburgh street" />
    <img src="edinburgh4.jpeg" alt="Edinburgh bookstore" />
    <img src="edinburgh5.jpeg" alt="Edinburgh street" />
    <h4 class="highlight-text">
      Stunning castles, cozy pubs, and beautiful highlands await you in Scotland's capital.
    </h4>
  </div>
  <div class="destination">
    <h3>4. Santorini, Greece 🌊</h3>
    <img src="greece5.jpeg" alt="Greece" />
    <img src="greece2.jpeg" alt="Greece river" />
    <img src="greece3.jpeg" alt="Greece street" />
    <img src="greece4.jpeg" alt="Greece street" />
    <h4 class="highlight-text">
      Famous for its white-washed buildings and unforgettable Aegean sunsets.
    </h4>
  </div>
  <div class="destination">
    <h3>5. Zurich, Switzerland 🏔️</h3>
    <img src="switzerland5.jpeg" alt="Swan" />
    <img src="switzerland3.jpeg" alt="Switzerland" />
    <img src="switzerland2.jpeg" alt="River" />
    <img src="switzerland4.jpeg" alt="Train" />
    <h4 class="highlight-text">
      Enjoy majestic Alps, serene lakes, and some of the best chocolate on Earth.
    </h4>
  </div>
  <div class="destination">
    <h3>6. Vienna, Austria 🎻</h3>
    <img src="vienna5.jpeg" alt="Vienna castle" />
    <img src="vienna2.jpeg" alt="Museum" />
    <img src="vienna3.jpeg" alt="Museum" />
    <img src="vienna1.jpeg" alt="Castle" />
    <h4 class="highlight-text">
      Enjoy coffeehouse culture, home of Mozart, beautiful museums, and operas.
    </h4>
  </div>
</section>
<!-- Facts Section -->
<section class="section-box" id="facts">
  <h2>Facts & Why I Want to Visit These Places 💬</h2>
  <p>Each place holds something special, whether it’s history, beauty, adventure, or peace. I’ve collected some fun facts and my personal reasons for wanting to visit each of these amazing destinations.</p>
  <a href="factsandwhyiwanttotravel.html" class="btn-link" target="_blank" rel="noopener noreferrer">
    📍 Click here to view the facts and reasons
  </a>
</section>
<!-- Interactive Dream Destination Input -->
<div class="text-center my-4">
  <h2>✨ Tell me your dream destination!</h2>
  <button onclick="suggestDestination()">Click Here</button>
  <p id="destinationResponse" style="font-weight: bold; margin-top: 10px;"></p>
</div>
<!-- Contact Section -->
<section class="section-box" id="contact">
  <h2>Contact 📧</h2>
  <p>If you have any questions, suggestions, or just want to say hello, feel free to reach out to me!</p>
  <p>Email: 
    <a href="mailto:s24224019@al.tiu.ac.jp" style="color: #1d3557; font-weight: bold;">
      s24224019@al.tiu.ac.jp
    </a>
  </p>
</section>
<footer>
  <p>Student ID: 24224019 | Name: Nafisha Shamiha Islam</p>
</footer>
<!-- Scroll to top button -->
<div id="scroll-top" title="Scroll to top" onclick="window.scrollTo({top:0, behavior:'smooth'});">
  <i class="bi bi-arrow-up-short"></i>
</div>
<script>
  // Welcome message
  document.getElementById("welcomeMsg").innerText = "👋 Welcome to my website!";
  // User destination prompt
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
    if (window.scrollY > 300) {
      scrollBtn.style.display = 'block';
    } else {
      scrollBtn.style.display = 'none';
    }
  });
</script>
</body>
</html>
