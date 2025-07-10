# happy-birthday-adu-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Open When Letters 💌</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;700&family=Pacifico&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Quicksand', sans-serif;
      background: linear-gradient(to right, #ffe6f0, #fce8ff);
      color: #333;
      text-align: center;
      padding: 2rem;
    }
    h1 {
      font-family: 'Pacifico', cursive;
      font-size: 2.5rem;
      color: #d16ba5;
      margin-bottom: 0.5rem;
    }
    p.tagline {
      font-size: 1.1rem;
      color: #555;
      margin-bottom: 2rem;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5rem;
      padding: 0 1rem;
    }
    .card {
      background: #fff;
      border-radius: 20px;
      padding: 1.5rem;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s;
      cursor: pointer;
      text-decoration: none;
      color: inherit;
    }
    .card:hover {
      transform: scale(1.03);
    }
    .card span {
      font-size: 2rem;
    }
    .card h3 {
      margin-top: 1rem;
      font-size: 1.2rem;
    }
    footer {
      margin-top: 4rem;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>
<body>
  <h1>For You, Always 💌</h1>
  <p class="tagline">Open a letter whenever you need me most.</p>

  <div class="grid">
    <a href="letters/miss-you.html" class="card">
      <span>💭</span>
      <h3>Open when you miss me</h3>
    </a>
    <a href="letters/sad.html" class="card">
      <span>😔</span>
      <h3>Open when you're sad</h3>
    </a>
    <a href="letters/loved.html" class="card">
      <span>❤️</span>
      <h3>Open when you need love</h3>
    </a>
    <a href="letters/birthday.html" class="card">
      <span>🎂</span>
      <h3>Open on your birthday</h3>
    </a>
    <a href="letters/fight.html" class="card">
      <span>🤍</span>
      <h3>Open after we fight</h3>
    </a>
    <a href="letters/happy.html" class="card">
      <span>🌞</span>
      <h3>Open when you're happy</h3>
    </a>
    <a href="letters/anxious.html" class="card">
      <span>🫶</span>
      <h3>Open when you're anxious</h3>
    </a>
    <a href="letters/lonely.html" class="card">
      <span>🌙</span>
      <h3>Open when you feel lonely</h3>
    </a>
  </div>

  <footer>
    Made with love by Avani 💕
  </footer>
</body>
</html>
