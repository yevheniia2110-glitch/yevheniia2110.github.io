<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>Zitaten</title>

  <link href="https://fonts.google.com/specimen/Engagement" rel="stylesheet">

  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #D5B893;
      color: #25344F;
      font-family: 'Engagment' !important;
      text-align: center;
      padding: 20px;
    }

    #quote {
      font-size: 7rem;
      max-width: 900px;
      line-height: 1;
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
