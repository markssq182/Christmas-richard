<!DOCTYPE html>
<html>
<head>
  <title>Christmas with Richard</title>
</head>
<body>
  <h1>Merry Christmas 🎄</h1>
  <p>This story is for Richard ❤️</p>
</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Christmas with Richard</title>

  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom, #0b3d2e, #145a32);
      font-family: "Georgia", serif;
      color: white;
      text-align: center;
      overflow-x: hidden;
    }

    h1 {
      margin-top: 40px;
      font-size: 40px;
      color: #ffeb3b;
      text-shadow: 2px 2px 8px black;
    }

    .card {
      background: rgba(255,255,255,0.12);
      margin: 40px auto;
      padding: 30px;
      border-radius: 25px;
      max-width: 750px;
      box-shadow: 0 0 25px rgba(0,0,0,0.5);
    }

    p {
      font-size: 18px;
      line-height: 1.9;
    }

    .footer {
      margin-bottom: 50px;
      font-style: italic;
      color: #ffd1dc;
    }

    /* Snow */
    .snow {
      position: fixed;
      top: -10px;
      color: white;
      animation: fall linear infinite;
      user-select: none;
      z-index: 9999;
    }

    @keyframes fall {
      to {
        transform: translateY(110vh);
      }
    }
  </style>
</head>

<body>

<h1>🎄 Merry Christmas, Richard ❤️</h1>

<div class="card">
  <p>
    On a quiet Christmas night, when the lights shine softly
    and the world feels warmer than usual,
    there is one name that my heart whispers again and again —
    <b>Richard</b>.
  </p>

  <p>
Christmas isn't just about a beautiful tree or neatly wrapped gifts.
Christmas is about someone who makes your heart feel like home. 
    And for me, that person is you.
  </p>

  <p>
    Richard, being with you feels like peace.
    Your presence calms my heart,
    your smile feels like a gentle miracle,
    and your care is the most beautiful gift I never knew I needed.
  </p>

  <p>
    If I could make one wish this Christmas,
    it would be to keep walking beside you,
    sharing laughter, quiet moments,
    and stories that only we understand.
  </p>

  <p>
    May this Christmas bring warmth to your heart,
hope in every step you take,
and love that always reminds you
that you matter. 
  </p>

  <p>
    <b>Merry Christmas, Richard.</b><br>
    Thank you for being the most beautiful part of my story. ❤️
  </p>
</div>

<div class="footer">
  With all my love, this Christmas 🎄✨
</div>

<!-- Music -->
<audio autoplay loop>
  <source src="https://cdn.pixabay.com/audio/2022/10/25/audio_eb8b2d0c57.mp3" type="audio/mpeg">
</audio>

<!-- Snow Script -->
<script>
  function createSnow() {
    const snow = document.createElement("div");
    snow.className = "snow";
    snow.innerHTML = "❄";
    snow.style.left = Math.random() * window.innerWidth + "px";
    snow.style.fontSize = Math.random() * 10 + 10 + "px";
    snow.style.animationDuration = Math.random() * 5 + 5 + "s";
    document.body.appendChild(snow);

    setTimeout(() => {
      snow.remove();
    }, 10000);
  }

  setInterval(createSnow, 200);
</script>

</body><!-- QR CODE CHRISTMAS -->
<div style="margin:50px auto; text-align:center;">
  <h2 style="color:#ffeb3b;">🎁 Scan This Christmas Surprise 🎄</h2>
  <p style="font-size:18px;">Untuk Richard ❤️</p>

  <img
    src="https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=https://markssq182.github.io/Christmas-richard/"
    alt="QR Christmas Richard"
    style="
      background:white;
      padding:15px;
      border-radius:25px;
      box-shadow:0 0 20px rgba(0,0,0,0.5);
    "
  >

  <p style="margin-top:15px; font-style:italic;">
    Scan me and read our Christmas story ✨
  </p>
</div>

</html>
