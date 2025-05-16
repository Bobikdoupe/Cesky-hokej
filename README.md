# Cesky-hokej
<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Český hokej</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      color: #111;
    }
    header {
      background-color: #d00000;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #0033a0;
      color: white;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 20px;
      max-width: 1000px;
      margin: auto;
      background-color: white;
      margin-top: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #d00000;
    }
    footer {
      background-color: #0033a0;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
    iframe {
      width: 100%;
      height: 600px;
      border: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Český hokej</h1>
    <p>Novinky, statistiky a zápasy českého hokeje</p>
  </header>

  <nav>
    <a href="#zive">Zápasy live</a>
    <a href="#statistiky">Statistiky</a>
    <a href="#novinky">Novinky</a>
    <a href="#odkazy">Odkazy</a>
  </nav>

  <section id="zive">
    <h2>🎯 Zápasy live</h2>
    <p>Zde můžeš sledovat živé výsledky:</p>
    <!-- Ukázka vložení live skóre z externí služby -->
    <iframe src="https://www.livesport.cz/zapas/"></iframe>
    <p><em>*Zde můžeš vložit iframe s konkrétním zápasem nebo widget od Livesportu.</em></p>
  </section>

  <section id="statistiky">
    <h2>📊 Statistiky</h2>
    <ul>
      <li>Nejlepší střelci Extraligy</li>
      <li>Nejproduktivnější hráči</li>
      <li>Statistiky týmů</li>
    </ul>
    <p><em>*Lze propojit přes veřejné API např. od hokej.cz nebo aktualizovat ručně.</em></p>
  </section>

  <section id="novinky">
    <h2>📰 Novinky</h2>
    <p>Poslední zprávy z českého hokeje:</p>
    <ul>
      <li>🏒 Nový trenér národního týmu byl oznámen</li>
      <li>🇨🇿 Češi porazili Švédy v přátelském utkání 3:2</li>
      <li>🧊 Sezona Extraligy startuje 15. září</li>
    </ul>
    <p><em>*Můžeš napojit RSS feed např. z hokej.cz nebo sport.cz.</em></p>
  </section>

  <section id="odkazy">
    <h2>🔗 Užitečné odkazy</h2>
    <ul>
      <li><a href="https://www.hokej.cz" target="_blank">Hokej.cz</a></li>
      <li><a href="https://www.livesport.cz/hokej/" target="_blank">Livesport - Hokej</a></li>
      <li><a href="https://www.ceskyhokej.cz" target="_blank">Český svaz ledního hokeje</a></li>
    </ul>
  </section>

  <footer>
    &copy; 2025 Český hokej – Neoficiální informační web
  </footer>
</body>
</html>
