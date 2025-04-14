# index.html 
Code 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Breaking the False Matrix – The War Beyond Time</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=UnifrakturCook:wght@700&display=swap');

    body {
      margin: 0;
      padding: 0;
      font-family: 'UnifrakturCook', cursive;
      color: #00ffcc;
      background-color: black;
      overflow-x: hidden;
    }

    .matrix {
      position: fixed;
      top: 0;
      left: 0;
      z-index: -1;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle, #003300 0%, #000000 80%);
      animation: pulse 3s infinite ease-in-out;
    }

    @keyframes pulse {
      0% { opacity: 0.9; }
      50% { opacity: 0.6; }
      100% { opacity: 0.9; }
    }

    header {
      text-align: center;
      padding: 4vh 2vw;
      border-bottom: 1px solid #00ffcc88;
    }

    header h1 {
      font-size: 7vw;
      color: #00ffcc;
      margin: 0;
    }

    header h2 {
      font-size: 4vw;
      color: #ffffffbb;
      margin-top: 5px;
    }

    .intro {
      text-align: center;
      margin: 6vh 5vw;
      font-size: 4vw;
      line-height: 1.6;
    }

    .books {
      display: grid;
      grid-template-columns: 1fr;
      gap: 4vh;
      padding: 5vw;
    }

    .book {
      background: rgba(0, 20, 0, 0.8);
      border: 1px solid #00ffcc55;
      padding: 4vh 4vw;
      border-radius: 12px;
      box-shadow: 0 0 18px #00ffcc88;
      transition: transform 0.3s;
    }

    .book:hover {
      transform: scale(1.03);
    }

    .book h3 {
      color: #ff4444;
      font-size: 5vw;
      margin-bottom: 2vh;
    }

    .book p {
      font-size: 3.5vw;
      color: #ffffffcc;
    }

    .book a {
      display: inline-block;
      margin-top: 2vh;
      font-size: 3.5vw;
      color: gold;
      text-decoration: underline;
    }

    .book.inactive {
      opacity: 0.3;
      pointer-events: none;
    }

    .activation {
      text-align: center;
      margin: 6vh 0;
    }

    .activation a {
      font-size: 5vw;
      padding: 1.5vh 4vw;
      background: #00ffcc;
      color: black;
      text-decoration: none;
      border-radius: 12px;
      box-shadow: 0 0 14px #00ffcc;
      animation: flicker 2s infinite;
    }

    @keyframes flicker {
      0% { opacity: 1; }
      50% { opacity: 0.6; }
      100% { opacity: 1; }
    }

    footer {
      font-size: 2.7vw;
      padding: 4vh 5vw;
      color: #777;
      text-align: center;
    }

    .legal {
      font-size: 2vw;
      opacity: 0.5;
      margin-top: 3vh;
    }
  </style>
</head>
<body>
  <div class="matrix"></div>

  <header>
    <h1>Breaking the False Matrix</h1>
    <h2>The War Beyond Time</h2>
  </header>

  <div class="intro">
    You were never meant to be a slave. These books are the weapons of awakening.
    Step through the gate and remember who you are.
  </div>

  <div class="activation">
    <a href="#books">ENTER THE GATE</a>
  </div>

  <section id="books" class="books">
    <div class="book">
      <h3>Book 1: Origins – The Root of the True Universe</h3>
      <p>The first code. The first flame. The story before time. The root of the real cosmos, before it was hijacked by false light.</p>
      <a href="#">Read More – 22 USD</a>
    </div>

    <div class="book inactive">
      <h3>Book 2: The Fire in the Sacral</h3>
      <p>Coming soon...</p>
    </div>

    <div class="book inactive">
      <h3>Book 3: Solar Code of Will</h3>
      <p>Coming soon...</p>
    </div>

    <div class="book inactive">
      <h3>Book 4: Heart of the Source Flame</h3>
      <p>Coming soon...</p>
    </div>

    <div class="book inactive">
      <h3>Book 5: Voice of the Akashic</h3>
      <p>Coming soon...</p>
    </div>

    <div class="book inactive">
      <h3>Book 6: Eye of the True Light</h3>
      <p>Coming soon...</p>
    </div>

    <div class="book inactive">
      <h3>Book 7: Crown of the Original Flame</h3>
      <p>Coming soon...</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Order of the Code Breakers. All rights reserved.
    <div class="legal">
      Digital product only. No refunds after download. For educational and transformational purposes only. Buyer takes full responsibility. All rights reserved under international law.
    </div>
  </footer>
</body>
</html>
