<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gratis knippen bij Ynss the Barber</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f0f0f0;
    }
    header {
      background-color: #222;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #444;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }
    .hero {
      background-image: url('https://source.unsplash.com/featured/?barber');
      background-size: cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2.5em;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
    }
    .content {
      padding: 20px;
      background: white;
      margin: 20px 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 10px;
    }
    .btn {
      background-color: #f1c40f;
      color: white;
      padding: 10px 20px;
      border: none;
      text-decoration: none;
      border-radius: 5px;
    }
    .form-container {
      background: #f9f9f9;
      padding: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .calendar {
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }
    .calendar iframe {
      border: none;
      width: 100%;
      max-width: 600px;
      height: 400px;
    }
  </style>
</head>
<body>

<header>
  <h1>Gratis knippen bij Ynss the Barber</h1>
  <p>Maak je klaar voor de beste kapsels in de stad, nu tijdelijk gratis!</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#overons">Over ons</a>
  <a href="#diensten">Diensten</a>
  <a href="#afspraak">Afspraak maken</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero">
  Welkom bij Ynss the Barber!
</div>

<div class="content" id="home">
  <h2>Welkom bij Ynss the Barber!</h2>
  <p>We zijn een barbershop die zich richt op kwaliteit, stijl en persoonlijke service. Bij ons krijg je niet alleen een geweldig kapsel, maar een ervaring die je nooit zult vergeten. En nu, voor een beperkte tijd, bieden we **gratis knippen** aan voor alle nieuwe klanten! Kom langs en laat je verwennen door Ynss, de beste barber in de stad.</p>
  <a href="#afspraak" class="btn">Maak direct een afspraak</a>
</div>

<div class="content" id="overons">
  <h2>Over ons</h2>
  <p>Ynss the Barber is opgericht door Ynss, een ervaren en gepassioneerde kapper met meer dan 10 jaar ervaring in de industrie. Ynss heeft gewerkt met de beste barbers uit de wereld en brengt die expertise naar zijn eigen shop. Of je nu een trendy kapsel wilt of gewoon een frisse snit, Ynss zorgt ervoor dat jij de look krijgt die bij je past!</p>
</div>

<div class="content" id="diensten">
  <h2>Onze Diensten</h2>
  <ul>
    <li>Heren knippen</li>
    <li>Baard trimmen</li>
    <li>Styling advies</li>
    <li>Speciale knipbeurten voor kinderen</li>
  </ul>
  <p>En veel meer! Kom langs en ontdek de complete service bij Ynss the Barber.</p>
</div>

<div class="content" id="afspraak">
  <h2>Maak een afspraak</h2>
  <p>Wil je gebruik maken van onze gratis knipactie? Vul hieronder je gegevens in om een afspraak te maken! Gebruik de kalender om een datum en tijd te kiezen.</p>
  
  <!-- Google Calendar Embed (hier kan je je echte agenda toevoegen) -->
  <div class="calendar">
    <iframe src="https://calendar.google.com/calendar/embed?src=YOUR_CALENDAR_ID&ctz=Europe%2FAmsterdam" 
      frameborder="0" scrolling="no"></iframe>
  </div>
  
  <div class="form-container">
    <form>
      <label for="naam">Naam:</label>
      <input type="text" id="naam" name="naam" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="datum">Gewenste datum:</label>
      <input type="date" id="datum" name="datum" required>

      <label for="bericht">Bericht (optioneel):</label>
      <textarea id="bericht" name="bericht"></textarea>

      <button type="submit" class="btn">Verstuur afspraak</button>
    </form>
  </div>
</div>

<div class="content" id="contact">
  <h2>Contact</h2>
  <p>Heb je vragen of wil je meer weten? Neem dan contact met ons op:</p>
  <p><strong>Adres:</strong> Stratenmakerstraat 12, 1234 AB, Amsterdam</p>
  <p><strong>Telefoon:</strong> 06-12345678</p>
  <p><strong>Email:</strong> info@ynssthebarber.nl</p>
</div>

<footer>
  &copy; 2025 Ynss the Barber - Alle rechten voorbehouden
</footer>

</body>
</html>
