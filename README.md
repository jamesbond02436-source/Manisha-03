<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Happy Birthday Manisha 💖</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background: radial-gradient(circle at top, #ffdde1, #ee9ca7, #270b36);
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      padding: 10px;
    }

    .card {
      background: rgba(0, 0, 0, 0.35);
      padding: 30px 25px;
      border-radius: 20px;
      max-width: 430px;
      text-align: center;
      box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
      position: relative;
      overflow: hidden;
      animation: fadeIn 2s ease;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #ffd3f0;
      margin-bottom: 18px;
      box-shadow: 0 0 15px rgba(255, 235, 244, 0.5);
      animation: pulse 3s infinite ease-in-out;
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.05); }
    }

    h1 {
      font-size: 2rem;
      margin-bottom: 10px;
    }

    h2 {
      font-size: 1.25rem;
      color: #ffd3f0;
      margin-bottom: 18px;
    }

    p {
      margin-bottom: 18px;
      font-size: 1rem;
      line-height: 1.6;
    }

    .name {
      font-weight: 600;
      color: #ffe082;
    }

    .from {
      margin-top: 10px;
      opacity: 0.9;
    }

    .btn {
      background: linear-gradient(135deg, #ff9a9e, #fecfef);
      color: #521b41;
      padding: 10px 22px;
      border: none;
      border-radius: 999px;
      font-weight: 600;
      cursor: pointer;
      margin-top: 5px;
      font-size: 0.95rem;
    }

    /* floating hearts */
    .hearts {
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      pointer-events: none;
      overflow: hidden;
      z-index: -1;
    }
    .heart {
      position: absolute;
      color: rgba(255,255,255,0.4);
      font-size: 22px;
      animation: floatUp 6s linear infinite;
    }
    @keyframes floatUp {
      0% { transform: translateY(100vh) translateX(0); }
      100% { transform: translateY(-10vh) translateX(20px); }
    }
  </style>
</head>
<body>

  <!-- Background Music (Bollywood Instrumental) -->
  <audio autoplay loop>
    <source src="https://files.catbox.moe/2jg2no.mp3" type="audio/mp3">
  </audio>

  <div class="hearts">
    <!-- random floating hearts -->
    <div class="heart" style="left:10%; animation-delay:0s;">❤</div>
    <div class="heart" style="left:30%; animation-delay:2s;">❤</div>
    <div class="heart" style="left:50%; animation-delay:4s;">❤</div>
    <div class="heart" style="left:70%; animation-delay:1s;">❤</div>
    <div class="heart" style="left:90%; animation-delay:3s;">❤</div>
  </div>

  <div class="card">

    <!-- Replace with real photo URL -->
    <img src="manisha-photo.jpg" alt="Manisha Photo">

    <h1>Happy Birthday, <span class="name">Manisha 🎉</span></h1>
    <h2>You deserve all the love and happiness 💗</h2>

    <p>
      Manisha, every day you add a little more beauty to the world just by being in it.
      Your smile has a magic that can soften the hardest moments, and your laughter
      feels like a song I never want to stop hearing. On your birthday, I want you to know
      that you are appreciated, admired, and cared for more than words can say.
    </p>

    <p>
      I hope life brings you everything your heart quietly dreams of — gentle mornings,
      warm memories, and a love that feels like home. You deserve all the happiness in
      the universe. Thank you for being someone my heart notices every single time.
    </p>

    <p class="from">
      With all my love,<br>
      <span class="name">[Your Name]</span>
    </p>

    <button class="btn">Make a Birthday Wish ✨</button>

  </div>

</body>
</html>
