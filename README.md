# petals-and-echoes

This is a personal project. It contains a curated playlist of 19 songs and a gallery of selected flowers.  

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Petals & Echoes</title>
  <style>
    body {
      font-family: 'Times New Roman', serif;
      background-image: url('background.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: #333;
      max-width: 900px;
      margin: auto;
      padding: 20px;
      backdrop-filter: brightness(0.9);
    }

    h1, h2 {
      text-align: center;
      color: #222;
    }

    .playlist {
      margin: 20px 0;
      padding-left: 20px;
      background-color: rgba(255, 255, 255, 0.8);
      border-radius: 10px;
      padding: 15px 20px;
    }

    .playlist li {
      margin: 8px 0;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
      margin-top: 30px;
      background-color: rgba(255, 255, 255, 0.8);
      padding: 20px;
      border-radius: 10px;
    }

    .gallery img {
      width: 150px;
      border-radius: 8px;
      object-fit: cover;
      transition: transform 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    .note {
      text-align: left;
      font-style: italic;
      color: #222;
      margin-top: 30px;
      line-height: 1.5;
      background-color: rgba(255, 255, 255, 0.8);
      padding: 20px;
      border-radius: 10px;
      white-space: pre-line;
    }
  </style>
</head>
<body>
  <h1>Petals & Echoes</h1>

  <h2>Playlist</h2>
  <ol class="playlist">
    <li>Lihim – Oranges &amp; Lemons</li>
    <li>Cinnamon Girl – Lana del Ray</li>
    <li>Sino – Unique Salonga</li>
    <li>4th of July – Sufjan Stevens</li>
    <li>Please, Please, Please Let Me Get What I Want – The Smiths</li>
    <li>Cry – Cigarettes After Sex</li>
    <li>Tumalon – Solace Out The Door</li>
    <li>Demonyo (redefined) - juan karlos</li>
    <li>Spoilarium – Eraserheads</li>
    <li>Jules – Unique Salonga</li>
    <li>Midnight Sky – Unique Salonga</li>
    <li>Promise Me – Laufey</li>
    <li>Akap – Imago</li>
    <li>Balisong (Transformed)</li>
    <li>Sparks – Coldplay</li>
    <li>She's Always a Woman – Billy Joel</li>
    <li>Iris – Goo Goo Dolls</li>
    <li>Lover, You Should've Come Over – Jeff Buckley</li>
    <li>Huwag Na Huwag Mong Sasabihin – Kitchie Nadal</li>
  </ol>

  <div class="gallery">
    <img src="arabian-jasmine.jpg" alt="Arabian Jasmine">
    <img src="peregrina.jpg" alt="Peregrina">
    <img src="plumbago.jpg" alt="Plumbago">
  </div>

  <p class="note">
Did you know that 19 is a happy number? No? Here's why:

19 = 1² + 9² = 82
82 = 8² + 2² = 68
68 = 6² + 8² = 100
100 = 1² + 0² + 0² = 1

It always circles back to 1. I hope this will make you a happy one.

Every song, every flower tells a journey. Our moments in bloom, curated in 19 songs.

Much love,
Yours truly
  </p>
</body>
</html>
