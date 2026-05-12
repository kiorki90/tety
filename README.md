<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Explore Japan</title>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
  }

  /* NAVBAR */
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #111;
    padding: 15px 30px;
  }

  .logo {
    color: white;
    font-size: 22px;
    font-weight: bold;
  }

  .nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
  }

  .nav-links li {
    list-style: none;
  }

  .nav-links a {
    color: white;
    text-decoration: none;
    font-size: 16px;
  }

  .nav-links a:hover {
    color: #ff4d4d;
  }
  .language-switcher select {
    padding: 8px 10px;
    border-radius: 5px;
    border: none;
    background: white;
    color: #111;
    font-size: 14px;
  }

  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border: 0;
  }

  /* HERO */
  .hero {
    background: url('https://images.unsplash.com/photo-1493976040374-85c8e12f0c0e?auto=format&fit=crop&w=1600&q=80') no-repeat center;
    background-size: cover;
    height: 400px;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 20px;
  }

  .hero h1 {
    font-size: 40px;
  }

  .hero p {
    font-size: 18px;
  }

  /* SECTION */
  .section {
    padding: 40px 20px;
    text-align: center;
  }

  .section h2 {
    margin-bottom: 20px;
  }

  /* CARDS */
  .cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }

  .card {
    width: 280px;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    background: white;
  }

  .card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    display: block;
  }

  .card h3 {
    margin: 10px;
  }

  .card p {
    padding: 0 10px 15px;
  }

  /* FOOTER */
  footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
  }
</style>

</head>

<body>
<!-- NAVBAR -->
<nav class="navbar">
  <div class="logo" id="logoText">Explore Japan 🇯🇵</div>
  <ul class="nav-links">
    <li><a href="Untitled-1.html">Attractions</a></li>
    <li><a href="food.html">National food and restaurants</a></li>
    <li><a href="transport.html">Transportation</a></li>
    <li><a href="hotel.html">Hotels/Accommodations </a></li>
    <li><a href="special section.html">Special Section </a></li>
  </ul>
  <div class="language-switcher">
    <label for="languageSelect" class="visually-hidden">Select language</label>
    <select id="languageSelect" aria-label="Choose language">
      <option value="en">English</option>
      <option value="el">Ελληνικά</option>
    </select>
  </div>
</nav>

<!-- HERO -->
<div class="hero">
  <h1 id="heroTitle">Discover Japan</h1>
  <p id="heroText">Culture, Food, and Unforgettable Experiences</p>
</div>

<!-- ATTRACTIONS -->
<section class="section">
  <h2 id="sectionAttractions">🟢 Top Attractions</h2>
  <div class="cards">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=800&q=80" alt="Mount Fuji">
      <h3 id="card1Title">Mount Fuji</h3>
      <p id="card1Text">Japan’s most iconic mountain and a must-see natural landmark.</p>
    </div>

    <div class="card">
      <img src="https://th.bing.com/th/id/OIP.PSm5JTZXlJMTYj3I0mwVWQHaE8?w=210&h=180&c=7&r=0&o=7&pid=1.7&rm=3" alt="Fushimi Inari Shrine">
      <h3 id="card2Title">Fushimi Inari Shrine</h3>
      <p id="card2Text">Famous for its thousands of red torii gates in Kyoto.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1549693578-d683be217e58?auto=format&fit=crop&w=800&q=80" alt="Shibuya Crossing">
      <h3 id="card3Title">Shibuya Crossing</h3>
      <p id="card3Text">The busiest pedestrian crossing in the world.</p>
    </div>

  </div>
</section>

<!-- FOOD -->
<section class="section">
  <h2 id="sectionFood">🍜 Food & Cuisine</h2>
  <div class="cards">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1562158070-57c0dcdde87c?auto=format&fit=crop&w=800&q=80" alt="Sushi">
      <h3 id="card4Title">Sushi</h3>
      <p id="card4Text">Fresh seafood served with rice, loved worldwide.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1604908176997-431c7a64a7c2?auto=format&fit=crop&w=800&q=80" alt="Ramen">
      <h3 id="card5Title">Ramen</h3>
      <p id="card5Text">A comforting noodle soup with rich flavors.</p>
    </div>

  </div>
</section>

<!-- CULTURE -->
<section class="section">
  <h2 id="sectionCulture">🎌 Culture</h2>
  <div class="cards">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1554797589-7241bb691973?auto=format&fit=crop&w=800&q=80" alt="Japanese Festival">
      <h3 id="card6Title">Festivals</h3>
      <p id="card6Text">Experience traditional matsuri full of energy and history.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1518544889283-4f8c3fa4e09c?auto=format&fit=crop&w=800&q=80" alt="Cherry Blossoms">
      <h3 id="card7Title">Cherry Blossoms</h3>
      <p id="card7Text">Enjoy beautiful sakura season in spring.</p>
    </div>

  </div>
</section>

<!-- TRANSPORT -->
<section class="section">
  <h2 id="sectionTransport">🚄 Transportation</h2>
  <p id="transportText">The Shinkansen (bullet train) connects major cities quickly and efficiently.</p>
</section>

<!-- FOOTER -->
<footer>
  <p id="footerText">© 2026 Explore Japan | School Project by Γιώργος και Μηχάλης</p>
</footer>

<script>
  const translations = {
    en: {
      htmlLang: 'en',
      logoText: 'Explore Japan 🇯🇵',
      navAttractions: 'Attractions',
      navFood: 'National food and restaurants',
      navCulture: 'Cultur and tips for tourists',
      navTransport: 'Transportation',
      navHotels: 'Hotels/Accommodations',
      navSpecial: 'Special Section',
      heroTitle: 'Discover Japan',
      heroText: 'Culture, Food, and Unforgettable Experiences',
      sectionAttractions: '🟢 Top Attractions',
      card1Title: 'Mount Fuji',
      card1Text: 'Japan’s most iconic mountain and a must-see natural landmark.',
      card2Title: 'Fushimi Inari Shrine',
      card2Text: 'Famous for its thousands of red torii gates in Kyoto.',
      card3Title: 'Shibuya Crossing',
      card3Text: 'The busiest pedestrian crossing in the world.',
      sectionFood: '🍜 Food & Cuisine',
      card4Title: 'Sushi',
      card4Text: 'Fresh seafood served with rice, loved worldwide.',
      card5Title: 'Ramen',
      card5Text: 'A comforting noodle soup with rich flavors.',
      sectionCulture: '🎌 Culture',
      card6Title: 'Festivals',
      card6Text: 'Experience traditional matsuri full of energy and history.',
      card7Title: 'Cherry Blossoms',
      card7Text: 'Enjoy beautiful sakura season in spring.',
      sectionTransport: '🚄 Transportation',
      transportText: 'The Shinkansen (bullet train) connects major cities quickly and efficiently.',
      footerText: '© 2026 Explore Japan | School Project by Γιώργος and Μηχάλης'
    },
    el: {
      htmlLang: 'el',
      logoText: 'Εξερευνήστε την Ιαπωνία 🇯🇵',
      navAttractions: 'Αξιοθέατα',
      navFood: 'Παραδοσιακή κουζίνα και εστιατόρια',
      navCulture: 'Πολιτισμός και συμβουλές για τουρίστες',
      navTransport: 'Μεταφορές',
      navHotels: 'Ξενοδοχεία/Διαμονή',
      navSpecial: 'Ειδικό Τμήμα',
      heroTitle: 'Ανακαλύψτε την Ιαπωνία',
      heroText: 'Πολιτισμός, φαγητό και αξέχαστες εμπειρίες',
      sectionAttractions: '🟢 Κορυφαία Αξιοθέατα',
      card1Title: 'Όρος Φούτζι',
      card1Text: 'Το πιο εμβληματικό βουνό της Ιαπωνίας και ένα αξιοθέατο που πρέπει να δείτε.',
      card2Title: 'Ναός Φουσιμί Ιναρί',
      card2Text: 'Γνωστό για τις χιλιάδες κόκκινες πύλες τορίι στο Κιότο.',
      card3Title: 'Σταυροδρόμι Σιμπούγια',
      card3Text: 'Ο πιο πολυσύχναστος διάβαση πεζών στον κόσμο.',
      sectionFood: '🍜 Φαγητό & Κουζίνα',
      card4Title: 'Σούσι',
      card4Text: 'Φρέσκα θαλασσινά με ρύζι, αγαπητά παγκοσμίως.',
      card5Title: 'Ράμεν',
      card5Text: 'Μία ζεστή σούπα με noodles και πλούσια γεύση.',
      sectionCulture: '🎌 Πολιτισμός',
      card6Title: 'Φεστιβάλ',
      card6Text: 'Ζήστε παραδοσιακά μασούρι γεμάτα ενέργεια και ιστορία.',
      card7Title: 'Λουλούδια κερασιάς',
      card7Text: 'Απολαύστε την όμορφη εποχή των σάκουρα την άνοιξη.',
      sectionTransport: '🚄 Μεταφορές',
      transportText: 'Το σινκανσέν (βομβητής τρένο) συνδέει μεγάλες πόλεις γρήγορα και αποδοτικά.',
      footerText: '© 2026 Εξερευνήστε την Ιαπωνία | Σχολικό έργο από Γιώργο και Μιχάλη'
    }
  };

  function setLanguage(lang) {
    const data = translations[lang] || translations.en;
    document.documentElement.lang = data.htmlLang;
    Object.keys(data).forEach((key) => {
      if (key === 'htmlLang') return;
      const element = document.getElementById(key);
      if (element) {
        element.textContent = data[key];
      }
    });
  }

  const languageSelect = document.getElementById('languageSelect');
  languageSelect.addEventListener('change', () => setLanguage(languageSelect.value));
  setLanguage('en');
</script>
</body>
</html>
