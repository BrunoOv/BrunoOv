# Hola, soy Bruno 🦊

<svg width="200" height="100" xmlns="http://www.w3.org/2000/svg">
  <style>
    @keyframes blink {
      0%, 100% { fill: #FFA500; } /* Naranja claro */
      50% { fill: #FF4500; } /* Naranja oscuro */
    }
      @keyframes move-randomly {
      0% { cx: 10; cy: 10; }
      20% { cx: 150; cy: 80; }
      40% { cx: 50; cy: 50; }
      60% { cx: 180; cy: 20; }
      80% { cx: 100; cy: 70; }
      100% { cx: 10; cy: 10; }
    }
    .fox {
      animation: blink 1s infinite,appear-disappear 2s infinite, move-randomly 6s infinite;;
    }
  </style>
  <circle cx="50" cy="10" r="10" class="fox" />
</svg>


---