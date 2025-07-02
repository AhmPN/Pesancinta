
<head>
  <meta charset="UTF-8">
  <title>Pesan Romantis</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom right, #ffb6c1, #ffe4e1);
      font-family: 'Segoe UI', sans-serif;
      color: #8b0000;
      overflow-x: hidden;
    }

    .container {
      text-align: center;
      padding: 50px 20px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
      animation: fadeIn 2s ease-in-out;
    }

    .hearts {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: -1;
    }

    .heart {
      position: absolute;
      width: 30px;
      height: 30px;
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Eo_circle_pink_heart.svg/1024px-Eo_circle_pink_heart.svg.png');
      background-size: cover;
      opacity: 0.7;
      animation: float 10s infinite linear;
    }

    @keyframes float {
      0% {
        transform: translateY(100vh) scale(1);
        opacity: 0;
      }
      50% {
        opacity: 1;
      }
      100% {
        transform: translateY(-100vh) scale(1.5);
        opacity: 0;
      }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    marquee {
      font-size: 1.8em;
      font-weight: bold;
      margin-top: 20px;
      color: #d10056;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>✨ Pesan Karna Kamu Cantik ✨</h1>
    <marquee behavior="scroll" direction="left" scrollamount="9">
      Karna kamu cantik Kan kuberi segalanya apa yang kupunya Dan hatimu baik Sempurnalah duniaku saat kau di sisiku
    </marquee>
  </div>

  <div class="hearts">
    <!-- Banyak hati untuk efek romantis -->
    <div class="heart" style="left:10%; animation-delay: 0s;"></div>
    <div class="heart" style="left:25%; animation-delay: 2s;"></div>
    <div class="heart" style="left:40%; animation-delay: 4s;"></div>
    <div class="heart" style="left:55%; animation-delay: 1s;"></div>
    <div class="heart" style="left:70%; animation-delay: 3s;"></div>
    <div class="heart" style="left:85%; animation-delay: 5s;"></div>
  </div>

</body>
