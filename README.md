# Rostoimpera
Seo mana

<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <title>My ENS Landing</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;600;800&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: radial-gradient(circle at top, #1b1f3b, #0b0f19);
      color: #eaeaea;
      text-align: center;
    }

    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 40px;
    }

    h1 {
      font-size: 3rem;
      font-weight: 800;
      background: linear-gradient(90deg, #7c7cff, #00ffd5);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    p {
      font-size: 1.2rem;
      opacity: 0.85;
      max-width: 600px;
      margin: 20px auto;
    }

    .btn {
      margin-top: 30px;
      padding: 15px 30px;
      background: linear-gradient(90deg, #7c7cff, #00ffd5);
      color: #000;
      text-decoration: none;
      border-radius: 30px;
      font-weight: 600;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 30px rgba(0,255,213,0.3);
    }

    footer {
      opacity: 0.5;
      font-size: 0.9rem;
      padding: 20px;
    }
  </style>
</head>
<body>

  <div class="hero">
    <h1>Ciao, sono [TUO NOME]</h1>
    <p>
      Costruisco esperienze Web3.
      ENS • IPFS • Decentralizzazione
    </p>
    <a href="mailto:tuamail@email.com" class="btn">Contattami</a>
  </div>

  <footer>
    © 2026 — Powered by ENS + IPFS
  </footer>

</body>
</html>
