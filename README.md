<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Letreiro - Alison Moreira</title>
  <style>
    body {
      background-color: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .neon-text {
      font-family: 'Arial', sans-serif;
      font-size: 60px;
      color: #fff;
      text-shadow:
        0 0 5px #1db954,
        0 0 10px #1db954,
        0 0 20px #1db954,
        0 0 40px #1db954;
      animation: blink 2s infinite alternate;
    }

    @keyframes blink {
      0% {
        text-shadow:
          0 0 5px #1db954,
          0 0 10px #1db954,
          0 0 20px #1db954,
          0 0 40px #1db954;
      }
      100% {
        text-shadow:
          0 0 2px #0f3,
          0 0 4px #0f3,
          0 0 8px #0f3,
          0 0 16px #0f3;
      }
    }
  </style>
</head>
<body>
  <div class="neon-text">Alison Moreira</div>
</body>
</html>
