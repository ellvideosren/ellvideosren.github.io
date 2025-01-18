
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Renat Elizbarian - Showreel</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
      background: black;
      color: white;
      font-family: Arial, sans-serif;
    }

    #container {
      position: relative;
      width: 100vw;
      height: 100vh;
      overflow: hidden;
    }

    video {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: auto;
      height: 100%;
      z-index: 1;
      object-fit: cover;
      object-position: center;
    }

    #name {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 3rem;
      font-weight: bold;
      z-index: 2;
      text-align: center;
      mix-blend-mode: difference; /* Gives a stylish effect against video */
    }
  </style>
</head>
<body>
  <div id="container">
    <!-- Replace 'video.mp4' with the path to your video file -->
    <video autoplay loop muted playsinline>
      <source src="video.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <div id="name">Renat Elizbarian</div>
  </div>
</body>
</html>
