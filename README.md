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
      background-color: #000;
      color: #f5f5f5;
      line-height: 1.8;
    }

    header {
      text-align: center;
      padding: 40px 20px;
      background: #111;
      border-bottom: 2px solid #e0a800;
    }

    header h1 {
      font-size: 3rem;
      color: #ffce00;
      text-shadow: 2px 2px 8px #000;
      letter-spacing: 2px;
    }

    main {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: #1a1a1a;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(255, 206, 0, 0.2);
    }

    .main-image {
      width: 100%;
      max-width: 700px;
      display: block;
      margin: 0 auto 30px;
      border-radius: 10px;
      border: 2px solid #ffce00;
      box-shadow: 0 0 10px #ffce00;
    }

    h2 {
      font-size: 2rem;
      color: #ffce00;
      border-bottom: 2px solid #ffce00;
      padding-bottom: 5px;
      margin-bottom: 20px;
      text-align: center;
    }

    p {
      font-size: 1.1rem;
      color: #ddd;
      text-align: justify;
      margin-bottom: 20px;
    }

    footer {
      text-align: center;
      background: #111;
      padding: 20px;
      color: #aaa;
      font-size: 0.9rem;
      border-top: 2px solid #e0a800;
      margin-top: 40px;
    }

    /* Scroll animation */
    @keyframes fadeInUp {
      from {
        transform: translateY(40px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }

    main, header {
      animation: fadeInUp 1.2s ease-out;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to One Piece World</h1>
  </header>

  <main>
    <img
      class="main-image"
      src="https://i.pinimg.com/originals/88/b4/35/88b4352c4e46fc8a40d6f4ff887c11f4.jpg"
      alt="Straw Hat Pirates"
    />

    <h2>About One Piece</h2>
    <p>
      One Piece is a legendary manga and anime series created by Eiichiro Oda. It follows the thrilling journey of Monkey D. Luffy, a boy who gains the power of rubber after eating a Devil Fruit, and dreams of becoming the Pirate King.
    </p>
    <p>
      Luffy assembles a unique crew known as the Straw Hat Pirates. Together, they sail across dangerous seas, explore mysterious islands, battle powerful enemies, and uncover the secrets of the world in search of the ultimate treasure—the One Piece.
    </p>
    <p>
      With a perfect mix of action, emotion, comedy, and world-building, One Piece has become one of the most beloved and longest-running anime series ever made. Welcome to a world of adventure!
    </p>
  </main>

  <footer>
    © 2025 One Piece Fan Page | Made with ❤️ by a Straw Hat
  </footer>

</body>
</html>
