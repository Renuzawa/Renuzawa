<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Cuizon, Blire Justine D.</title>
  <style>
    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
    }
    body {
      min-height: 100vh;
      background: #fff;
      color: #222;
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      position: relative;
    }
    .name {
      width: 100%;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      font-size: 3rem;
      font-weight: bold;
      letter-spacing: 2px;
      margin-top: 3in;
      text-align: center;
      text-shadow: none;
    }
    .socials {
      display: flex;
      gap: 2rem;
      margin-top: 1in;
      margin-bottom: 3vh;
      justify-content: center;
      width: 100%;
    }
    .social-link {
      display: flex;
      align-items: center;
      text-decoration: none;
      color: #222;
      font-size: 1.1rem;
      font-weight: 500;
      transition: color 0.2s;
    }
    .social-link:hover {
      color: #1db954;
    }
    .logo {
      width: 32px;
      height: 32px;
      margin-right: 0.5rem;
      transition: transform 0.4s cubic-bezier(0.68, -0.55, 0.27, 1.55), filter 0.2s;
      filter: none;
    }
    .social-link:hover .logo {
      transform: rotate(-10deg) scale(1.2) translateY(-5px);
      filter: drop-shadow(0 2px 6px #1db954);
    }
    @media (max-width: 500px) {
      .name { font-size: 1.5rem; margin-top: 2vh; }
      .socials { margin-top: 2vh; }
      .logo { width: 24px; height: 24px; }
    }
  </style>
</head>
<body>
  <div class="name">Cuizon, Blire Justine D.</div>
  <div class="socials">
    <a class="social-link" href="https://www.facebook.com/urfutureprogrammerRenu/about" target="_blank">
      <img class="logo" src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/facebook.svg" alt="Facebook Logo">
      Facebook
    </a>
    <a class="social-link" href="https://www.instagram.com/its.r3nu" target="_blank">
      <img class="logo" src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/instagram.svg" alt="Instagram Logo">
      Instagram
    </a>
    <a class="social-link" href="https://discord.com/users/1038981829488807996" target="_blank">
      <img class="logo" src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/discord.svg" alt="Discord Logo">
      Discord
    </a>
  </div>
</body>
</html>
