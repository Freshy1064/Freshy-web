<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>One Piece Reanimated</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Trebuchet MS', sans-serif;
      background: linear-gradient(#000000cc, #000000cc),
                  url('https://wallpapercave.com/wp/wp10661849.jpg') no-repeat center center fixed;
      background-size: cover;
      color: white;
      overflow-x: hidden;
    }

    header {
      padding: 30px 20px;
      text-align: center;
      background: rgba(0, 0, 0, 0.6);
      animation: fadeIn 2s ease-out;
    }

    header h1 {
      font-size: 3rem;
      color: #ffcc00;
      text-shadow: 2px 2px 6px #000;
      animation: slideInDown 1.5s ease-out;
    }

    .content {
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
      background: rgba(255, 255, 255, 0.9);
      color: #222;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.2);
      animation: fadeInUp 2s ease-out;
    }

    .content img {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 0 10px #000;
      margin-bottom: 20px;
      animation: zoomIn 1.5s ease-out;
    }

    .content h2 {
      color: #d84315;
      font-size: 2rem;
      margin-bottom: 10px;
    }

    .content p {
      font-size: 1.1rem;
      margin-bottom: 15px;
      text-align: justify;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: rgba(0, 0, 0, 0.6);
      color: #ffcc00;
      font-size: 0.9rem;
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; }
      to   { opacity: 1; }
    }

    @keyframes slideInDown {
      from { transform: translateY(-100px); opacity: 0; }
      to   { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeInUp {
      from { transform: translateY(40px); opacity: 0; }
      to   { transform: translateY(0); opacity: 1; }
    }

    @keyframes zoomIn {
      from { transform: scale(0.9); opacity: 0; }
      to   { transform: scale(1); opacity: 1; }
    }
  </style>
</head>
<body>
  <header>
    <h1>ONE PIECE: REANIMATED</h1>
  </header>

  <div class="content">
    <img src="https://i.pinimg.com/originals/88/b4/35/88b4352c4e46fc8a40d6f4ff887c11f4.jpg" alt="Straw Hat Crew" />
    <h2>What is One Piece?</h2>
    <p>
      One Piece is an epic anime and manga series created by Eiichiro Oda. It tells the story of Monkey D. Luffy and his crew as they sail the seas to find the legendary treasure known as the "One Piece" and fulfill Luffy’s dream of becoming the Pirate King.
    </p>
    <p>
      The Reanimated version of One Piece brings together fan artists and animators to recreate iconic episodes, scenes, and intros with new styles, tributes, and love for the series. This is a tribute site to that movement!
    </p>
    <p>
      Explore the Grand Line, meet the Straw Hats, and discover what makes this series legendary. Join the crew as we sail through a reimagined adventure.
    </p>
  </div>

  <footer>
    © 2025 One Piece Reanimated Fan Project. All rights belong to their original creators.
  </footer>
</body>
</html>
