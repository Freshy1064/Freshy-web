<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>One Piece | Home</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
                  url('https://wallpapercave.com/wp/wp10661849.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
      overflow-x: hidden;
    }

    header {
      padding: 40px 20px;
      text-align: center;
      background-color: rgba(0, 0, 0, 0.6);
      animation: fadeIn 1.5s ease-out;
    }

    header h1 {
      font-size: 3rem;
      color: #ffe600;
      text-shadow: 2px 2px 8px #000;
      animation: slideDown 1.2s ease-out;
    }

    main {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: rgba(255, 255, 255, 0.95);
      color: #222;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.1);
      animation: fadeInUp 2s ease-out;
    }

    main img {
      width: 100%;
      max-width: 700px;
      margin-bottom: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.5);
      animation: zoomIn 1s ease-out;
    }

    h2 {
      color: #c62828;
      margin-bottom: 10px;
      font-size: 2rem;
      border-bottom: 3px solid #c62828;
      display: inline-block;
    }

    p {
      font-size: 1.1rem;
      line-height: 1.8;
      margin: 15px 0;
      text-align: justify;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: rgba(0, 0, 0, 0.6);
      color: #ffc107;
      font-size: 0.9rem;
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; } to { opacity: 1; }
    }

    @keyframes slideDown {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeInUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes zoomIn {
      from { transform: scale(0.9); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to the World of One Piece</h1>
  </header>

  <main>
    <img src="https://i.pinimg.com/originals/88/b4/35/88b4352c4e46fc8a40d6f4ff887c11f4.jpg" alt="Straw Hat Pirates">
    <h2>About One Piece</h2>
    <p>
      One Piece is a legendary anime and manga series created by Eiichiro Oda. It follows Monkey D. Luffy, a rubber-bodied boy with a big dream—to become the Pirate King by finding the greatest treasure, the "One Piece."
    </p>
    <p>
      As he sails across the Grand Line, Luffy builds a crew of diverse and powerful allies: the Straw Hat Pirates. Together, they fight the World Government, challenge rival pirates, and uncover the deep secrets of the sea.
    </p>
    <p>
      With unmatched world-building, emotional storytelling, and unforgettable characters, One Piece is one of the most beloved anime journeys of all time.
    </p>
  </main>

  <footer>
    © 2025 One Piece Fan Site. Built by Fans, For Fans.
  </footer>

</body>
</html>
