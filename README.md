<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Purgux</title>
  <style>
    /* Reset and basic styling */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      height: 100vh;
      background-color: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Segoe UI', sans-serif;
      color: #fff;
    }

    .container {
      text-align: center;
      animation: fadeIn 1.2s ease-in-out;
    }

    .title {
      font-size: 64px;
      background: linear-gradient(to right, #00ffff, #ff00ff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-shadow: 0 0 20px rgba(0, 255, 255, 0.3);
      margin-bottom: 10px;
    }

    .description {
      font-size: 20px;
      color: #ccc;
      text-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(10px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="title">PURGUX</h1>
    <p class="description">Genesis Coupe 3.8 · 2016</p>
  </div>
</body>
</html>
