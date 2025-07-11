<!DOCTYPE html><html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Guadagna Robux gratis guardando video pubblicitari. Ogni visualizzazione aiuta a finanziare premi veri!">
  <title>Guadagna Robux Guardando Video</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f0f0f0; }
    header { background: #1f2937; color: white; padding: 1em; text-align: center; }
    main { padding: 2em; max-width: 600px; margin: auto; background: white; margin-top: 2em; border-radius: 10px; }
    button { background: #10b981; color: white; padding: 1em 2em; border: none; border-radius: 8px; cursor: pointer; font-size: 1em; }
    button:hover { background: #059669; }
    .points { font-size: 2em; color: #111827; margin-top: 1em; }
    footer { text-align: center; font-size: 0.9em; margin-top: 3em; color: #6b7280; }
    nav { margin-bottom: 1.5em; text-align: center; }
    nav a { margin: 0 1em; color: #4b5563; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
  </style>
</head>
<body>
  <header>
    <h1>Guadagna Robux Guardando Video</h1>
  </header>
  <main>
    <nav>
      <a href="#home">Home</a>
      <a href="#come-funziona">Come Funziona</a>
      <a href="#privacy">Privacy</a>
    </nav>
    <section id="home">
      <p>Guarda video pubblicitari, guadagna punti e trasformali in Robux. È gratis, veloce e legale!</p>
      <button onclick="watchAd()">Guarda un Video</button>
      <div class="points">Punti: <span id="points">0</span></div>
    </section><section id="come-funziona">
  <h2>Come Funziona</h2>
  <p>Ogni video pubblicitario che guardi ci fa guadagnare una piccola somma. Noi usiamo questi guadagni per premiarti con Robux veri. Ogni video visto = 1 punto. Quando raggiungi abbastanza punti, riceverai i tuoi Robux.</p>
</section>

<section id="privacy">
  <h2>Privacy</h2>
  <p>Non raccogliamo dati personali sensibili. I punti sono salvati solo localmente sul tuo dispositivo. Le pubblicità sono gestite da piattaforme esterne come Google AdSense.</p>
</section>

  </main>  <footer>
    <p>&copy; 2025 Robux Rewards - Tutti i diritti riservati</p>
  </footer>  <script>
    let points = localStorage.getItem("robuxPoints") || 0;
    document.getElementById("points").innerText = points;

    function watchAd() {
      // Simula la visione di un video premiato
      alert("Simulazione: hai guardato un video pubblicitario!");
      points++;
      localStorage.setItem("robuxPoints", points);
      document.getElementById("points").innerText = points;
    }
  </script></body>
</html>
