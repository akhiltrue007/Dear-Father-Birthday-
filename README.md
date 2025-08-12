<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Papa 🎉</title>
<style>
    body {
        margin: 0;
        padding: 0;
        font-family: 'Segoe UI', sans-serif;
        background: linear-gradient(135deg, #ff9a9e, #fad0c4);
        overflow: hidden;
        text-align: center;
        color: white;
    }
    h1 {
        font-size: 2.5em;
        margin-top: 80px;
        animation: glow 2s infinite alternate;
    }
    p {
        font-size: 1.2em;
        max-width: 90%;
        margin: auto;
    }
    @keyframes glow {
        0% { text-shadow: 0 0 10px yellow, 0 0 20px orange; }
        100% { text-shadow: 0 0 20px red, 0 0 40px gold; }
    }
    .balloon {
        position: absolute;
        bottom: -100px;
        font-size: 40px;
        animation: floatUp 8s infinite ease-in;
    }
    @keyframes floatUp {
        0% { transform: translateY(0); opacity: 1; }
        100% { transform: translateY(-110vh); opacity: 0; }
    }
    footer {
        position: fixed;
        bottom: 20px;
        width: 100%;
        font-size: 1.2em;
    }
</style>
</head>
<body>

<h1>🎉 Happy Birthday, Papa 🎂</h1>
<p>Dear Papa,<br>  
You are my hero, my guide, and my best friend.  
May your special day be filled with love, laughter, and joy. ❤️</p>

<footer>With love,<br><b>Akhil</b></footer>

<!-- Balloons -->
<div class="balloon" style="left: 10%;">🎈</div>
<div class="balloon" style="left: 30%;">🎈</div>
<div class="balloon" style="left: 50%;">🎈</div>
<div class="balloon" style="left: 70%;">🎈</div>
<div class="balloon" style="left: 90%;">🎈</div>

<!-- Background music -->
<audio autoplay loop>
  <source src="https://www.bensound.com/bensound-music/bensound-sunny.mp3" type="audio/mpeg">
</audio>

<script>
    // Random balloon animation delay
    document.querySelectorAll('.balloon').forEach(balloon => {
        balloon.style.animationDelay = Math.random() * 5 + "s";
    });
</script>

</body>
</html>
