<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Studio Slix | Crochet Creations</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Comic+Neue:wght@700&display=swap');

    body {
      margin: 0;
      font-family: 'Comic Neue', cursive;
      background: linear-gradient(135deg, #fdfd96, #ffb3ff, #a0e7e5);
      color: #4b0082;
      background-size: 400% 400%;
      animation: gradientShift 15s ease infinite;
    }

    @keyframes gradientShift {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }

    header {
      text-align: center;
      padding: 2rem 1rem;
    }

    h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3rem;
      margin-bottom: 0.3rem;
      text-shadow: 1px 1px #ff69b4;
    }

    p.tagline {
      font-size: 1.2rem;
      font-style: italic;
    }

    .items {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 1rem;
    }

    .item {
      background: rgba(255, 255, 255, 0.7);
      border: 3px dashed #ff69b4;
      border-radius: 15px;
      margin: 1rem;
      padding: 1rem;
      width: 250px;
      text-align: center;
      box-shadow: 3px 3px 10px #ccc;
    }

    .item img {
      max-width: 100%;
      border-radius: 10px;
    }

    .item h2 {
      margin: 0.5rem 0;
      font-size: 1.5rem;
    }

    .item p {
      margin: 0.3rem 0;
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 1.1rem;
      background: #fff0f5;
      border-top: 2px solid #ff69b4;
    }

    a {
      color: #ff1493;
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Studio Slix</h1>
    <p class="tagline">Handmade Y2K Crochet Vibes</p>
  </header>

  <section class="items">
    <div class="item">
      <img src="https://via.placeholder.com/250x250.png?text=Funky+Hat" alt="Crochet Hat">
      <h2>Funky Flare Hat</h2>
      <p>$28</p>
    </div>
    <div class="item">
      <img src="https://via.placeholder.com/250x250.png?text=Granny+Bag" alt="Crochet Bag">
      <h2>Granny Square Bag</h2>
      <p>$35</p>
    </div>
    <div class="item">
      <img src="https://via.placeholder.com/250x250.png?text=Butterfly+Top" alt="Crochet Top">
      <h2>Butterfly Top</h2>
      <p>$42</p>
    </div>
  </section>

  <footer>
    <p>Want to order or collab? Contact me on Instagram: <a href="https://instagram.com/studio.slix" target="_blank">@studio.slix</a></p>
  </footer>
</body>
</html>
