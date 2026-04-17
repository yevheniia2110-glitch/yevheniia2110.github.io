<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>Zitate</title>

  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: antiquewhite;
      color: midnightblue;
      font-family: 'Playfair Display', serif;
      text-align: center;
      padding: 20px;
    }

    #quote {
      font-size: 4rem;
      max-width: 800px;
      line-height: 2;
    }
  </style>
</head>

<body>

  <div id="quote">Lädt...</div>

  <script>
    document.addEventListener("DOMContentLoaded", function() {
      const quotes = [
        "Die Frau hat die Aufgabe, Kinder zu gebären und damit das Volk zu erhalten",
        "Jede Mutter ist die Schöpferin der Zukunft unseres Volkes",
        "Die Frau gehört in die Kinder, Küche und Kirche",
        "Die wichtigste Aufgabe der deutschen Frau ist die Erhaltung und Vermehrung des nordischen Blutes",
        "Die deutsche Mutter trägt das heiligste Gut des Volkes in sich: seine Zukunft"
      ];

      const randomIndex = Math.floor(Math.random() * quotes.length);
      document.getElementById("quote").textContent = quotes[randomIndex];
    });
  </script>

</body>
</html>
