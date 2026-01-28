<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Gargi ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Great+Vibes&display=swap" rel="stylesheet">

<style>
* { margin: 0; padding: 0; box-sizing: border-box; }

body {
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #ff9a9e, #fad0c4);
  color: white;
  text-align: center;
  overflow-x: hidden;
}

.hidden { display: none; }

/* HERO */
.hero {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 20px;
}

.hero h1 {
  font-family: 'Great Vibes', cursive;
  font-size: 3.5rem;
}

.btn {
  margin-top: 25px;
  padding: 12px 30px;
  background: white;
  color: #ff5f8f;
  border-radius: 30px;
  border: none;
  font-size: 1rem;
  cursor: pointer;
}

/* COUNTDOWN */
#countdown {
  font-size: 1.1rem;
  margin-top: 15px;
  opacity: 0.9;
}

/* SECTION */
.section {
  padding: 50px 20px;
}

.card {
  background: rgba(255,255,255,0.15);
  backdrop-filter: blur(10px);
  border-radius: 20px;
  padding: 22px;
  margin: 25px auto;
  max-width: 520px;
}

/* IMAGE FRAME */
.frame {
  border-radius: 18px;
  overflow: hidden;
  margin-bottom: 10px;
}

.frame img {
  width: 100%;
  display: block;
}

/* TEXT */
.note {
  font-size: 0.95rem;
  opacity: 0.95;
}

.poem {
  font-size: 1rem;
  line-height: 1.8;
}

/* FINAL LOVE */
.final-love {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.final-love h1 {
  font-family: 'Great Vibes', cursive;
  font-size: 4rem;
}

.final-love p {
  margin-top: 10px;
  font-size: 1.1rem;
  opacity: 0.95;
}

/* HEART FLOAT */
.heart {
  position: fixed;
  bottom: -20px;
  font-size: 18px;
  animation: float 6s linear infinite;
}

@keyframes float {
  from { transform: translateY(0); opacity: 1; }
  to { transform: translateY(-110vh); opacity: 0; }
}

/* HEART BURST */
.burst {
  position: fixed;
  font-size: 20px;
  animation: burst 1.5s ease-out forwards;
}

@keyframes burst {
  from { transform: scale(0); opacity: 1; }
  to { transform: translateY(-150px) scale(1.5); opacity: 0; }
}
</style>
</head>

<body>

<!-- MUSIC -->
<audio id="music" loop>
  <source src="c:\Users\intel\Downloads\HELLO! London View Violin BGM Music  sad and happy Versions.mp3" type="audio/mpeg">
</audio>

<!-- LOCK SCREEN -->
<div class="hero" id="lockScreen">
  <h1>For Gargi ❤️</h1>
  <p>This little world opens at midnight</p>
  <div id="countdown"></div>
</div>

<!-- CONTENT -->
<div id="content" class="hidden">

  <div class="hero">
    <h1>Happy 21st Birthday, Gargi ❤️</h1>
    <p>Made with love, only for you</p>
    <button class="btn" onclick="startLove()">Tap to Feel the Love 💕</button>
  </div>

  <div class="section" id="notes">

    <!-- 21 NOTES -->
    <!-- Duplicate and change image/text -->
    <div class="card"><div class="frame"><img src="https://i.imgur.com/aQ8bPT6.jpeg"></div><div class="note">1."The way you feel deeply, even when you don’t show it."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/nMxEikj.jpeg "></div><div class="note">2."Your strength in public and softness in private."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/Jy57JwQ.jpeg "></div><div class="note">3."How your presence itself feels comforting."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/bh0BBrj.jpeg"></div><div class="note">4."Your honesty, even when it’s hard."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/rMt0UlX.jpeg"></div><div class="note">5."The calm you bring without trying."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/V3fu0NT.jpeg"></div><div class="note">6."The way you stay true to yourself."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/EGu3vJa.jpeg"></div><div class="note">7."Your smile — it stays with me."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/yJj33Tx.jpeg"></div><div class="note">8."How you care more than you admit."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/BpfqVTm.jpeg"></div><div class="note">9."Your silence that still speaks."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/Uu7qfSG.jpeg"></div><div class="note">10."The trust we’re slowly building."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/w60VJza.jpeg"></div><div class="note">11."Your resilience on tough days."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/Xn7rLZu.jpeg"></div><div class="note">12."The way you make moments feel real."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/r8ftwHq.jpeg"></div><div class="note">13."Your laughter when you’re truly happy."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/TWazxKX.jpeg "></div><div class="note">14."Your ability to stand strong."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/WRuMvBD.jpeg"></div><div class="note">15."The comfort of being myself with you."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/C13FYCK.jpeg"></div><div class="note">16."How you matter more than you know."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/OoE9EWS.jpeg"></div><div class="note">17."Your heart, even when guarded."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/p7Wal1E.jpeg"></div><div class="note">18."The warmth you bring into my life."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/ahFTLhY.jpeg"></div><div class="note">19."The patience we’re learning together."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/5PO6yKT.jpeg"></div><div class="note">20."The way you slowly became home."</div></div>
    <div class="card"><div class="frame"><img src="https://i.imgur.com/7F8uCiF.jpeg"></div><div class="note">21."Simply because you are you, Gargi."</div></div>

    <!-- POEM -->
    <div class="card">
      <h2>Another Truth</h2>
      <div class="poem">
        "I didn’t fall in love all at once,<br>
        It happened quietly,<br>
        In comfort, in patience,<br>
        In the way you stayed.<br><br>
        Loving you feels natural,<br>
        Like something my heart always knew."
      </div>
    </div>

    <!-- PROMISE -->
    <div class="card">
      <h2>My Promise</h2>
      <p>
        "I don’t promise perfection,<br>
        but I promise effort, respect, patience,<br>
        and love that grows - not fades."
      </p>
    </div>

  </div>

  <!-- FINAL -->
  <div class="final-love" id="finalLove">
    <h1>"I love you, Gargi ❤️"</h1>
    <p>"Today, Tomorrow, Always"</p>
   
  </div>

</div>

<script>
/* COUNTDOWN */
const targetDate = new Date("January 01, 2026 00:00:00").getTime();
setInterval(() => {
  const now = new Date().getTime();
  const diff = targetDate - now;
  if (diff <= 0) {
    lockScreen.style.display = "none";
    content.classList.remove("hidden");
  } else {
    countdown.innerHTML =
      Math.floor(diff / (1000*60*60*24)) + " days " +
      Math.floor((diff / (1000*60*60)) % 24) + " hrs " +
      Math.floor((diff / (1000*60)) % 60) + " min " +
      Math.floor((diff / 1000) % 60) + " sec";
  }
}, 1000);

/* START */
function startLove() {
  music.play();
  notes.scrollIntoView({ behavior: "smooth" });
}

/* FLOAT HEARTS */
setInterval(() => {
  const h = document.createElement("div");
  h.className = "heart";
  h.innerHTML = "❤️";
  h.style.left = Math.random() * 100 + "vw";
  document.body.appendChild(h);
  setTimeout(() => h.remove(), 6000);
}, 600);


observer.observe(document.getElementById("finalLove"));
</script>

</body>
</html>
