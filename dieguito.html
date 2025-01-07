<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Texto con corazones y video de fondo</title>
  <script src="https://code.createjs.com/1.0.0/easeljs.min.js"></script>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      background: black;
    }
    video {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }
    canvas {
      display: block;
    }
  </style>
</head>
<body>
  <video autoplay loop muted>
    <source src="https://static.videezy.com/system/resources/previews/000/051/777/original/VZ-HD-CG0010.mp4" type="video/mp4">
  </video>

  <canvas id="canvas"></canvas>

  <script>
    var canvas = document.getElementById("canvas");
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
    var stage = new createjs.Stage(canvas);

    var text = new createjs.Text(
      "Cuanto más tiempo estoy contigo\nmás te amo, mi amor:3",
      "bold 24px Arial",
      "#ffffff"
    );
    text.textAlign = "center";
    text.textBaseline = "middle";
    text.x = canvas.width / 2;
    text.y = canvas.height / 2;
    stage.addChild(text);

    function createHeart() {
      var heart = new createjs.Shape();
      var color = createjs.Graphics.getHSL(Math.random() * 360, 100, 70);
      heart.graphics
        .beginFill(color)
        .moveTo(0, -10)
        .bezierCurveTo(-10, -20, -20, -10, 0, 10)
        .bezierCurveTo(20, -10, 10, -20, 0, -10)
        .endFill();

      heart.x = Math.random() * canvas.width;
      heart.y = canvas.height + 20;
      heart.scaleX = heart.scaleY = Math.random() * 0.5 + 0.5;
      heart.alpha = Math.random() * 0.5 + 0.5;

      stage.addChild(heart);

      createjs.Tween.get(heart)
        .to({ y: -20, alpha: 0 }, 5000 + Math.random() * 3000)
        .call(() => stage.removeChild(heart));
    }

    createjs.Ticker.framerate = 60;
    createjs.Ticker.addEventListener("tick", () => {
      if (Math.random() < 0.1) createHeart();
      stage.update();
    });

    window.addEventListener("resize", function () {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
      text.x = canvas.width / 2;
      text.y = canvas.height / 2;
      stage.update();
    });
  </script>
</body>
</html>
