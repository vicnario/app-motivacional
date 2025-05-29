<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Frases Motivadoras - AURA</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 40px;
      background: #f0f8ff;
    }
    h1 {
      color: #333;
      margin-bottom: 20px;
    }
    .frase {
      font-size: 1.5em;
      margin: 30px 0;
      color: #007acc;
      min-height: 60px;
    }
    button {
      padding: 10px 20px;
      font-size: 1em;
      border: none;
      background-color: #28a745;
      color: white;
      cursor: pointer;
      border-radius: 10px;
    }
    button:hover {
      background-color: #218838;
    }
    .footer {
      margin-top: 40px;
      font-size: 1em;
      color: #555;
    }
  </style>
</head>
<body>

  <h1>Motívate tú solo…</h1>

  <div class="frase" id="frase">Haz clic para recibir tu frase motivadora</div>

  <button onclick="mostrarFrase()">Mostrar frase</button>

  <div class="footer">
    Siempre disponibles para ti en <strong>AURA</strong><br>
    56257998817 – agenda tu cita
  </div>

  <script>
    const frases = [
      "Cree en ti y todo será posible.",
      "Cada día es una nueva oportunidad para brillar.",
      "No te rindas, lo mejor está por venir.",
      "El éxito es la suma de pequeños esfuerzos repetidos cada día.",
      "Tú puedes con todo.",
      "Los límites solo existen en tu mente.",
      "Transforma tus debilidades en fortalezas.",
      "Actitud es todo.",
      "El momento perfecto es ahora.",
      "Todo lo que necesitas está dentro de ti.",
      // Agrega aquí hasta 100 frases motivadoras...
    ];

    function mostrarFrase() {
      const indice = Math.floor(Math.random() * frases.length);
      document.getElementById("frase").textContent = frases[indice];
    }
  </script>

</body>
</html>
