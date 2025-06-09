<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Discord Badge - Şık Tasarım</title>
  <style>
    body {
      margin: 0;
      background: linear-gradient(135deg, #7289da, #99aab5);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .card {
      background: #2c2f33;
      padding: 20px 30px;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.3);
      transition: transform 0.3s ease;
      cursor: pointer;
      text-align: center;
    }
    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 12px 30px rgba(0,0,0,0.5);
    }
    .card img {
      border-radius: 12px;
      max-width: 300px;
      width: 100%;
      height: auto;
      display: block;
      margin: 0 auto;
    }
    .card p {
      margin-top: 15px;
      color: #fff;
      font-weight: 600;
      letter-spacing: 0.05em;
    }
    a {
      text-decoration: none;
    }
  </style>
</head>
<body>
  <a href="https://discord.com/users/1109048720626024559" target="_blank" rel="noopener noreferrer" class="card">
    <img src="https://lanyard.cnrad.dev/api/1109048720626024559" alt="Discord Presence" />
    <p>Connect with me on Discord</p>
  </a>
</body>
</html>
