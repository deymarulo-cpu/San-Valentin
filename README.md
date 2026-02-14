<!DOCTYPE html>
<html>
<head>
<title>¿Quieres ser mi San Valentín?</title>

<style>
body {
  margin: 0;
  height: 100vh;
  background: url('https://upload.wikimedia.org/wikipedia/commons/5/57/M31bobo.jpg') no-repeat center center fixed;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: 'Comic Sans MS', cursive;
  text-align: center;
  color: white;
}

.container {
  background: rgba(0,0,0,0.6);
  padding: 40px;
  border-radius: 20px;
}

button {
  padding: 15px 30px;
  margin: 10px;
  border: none;
  border-radius: 30px;
  font-size: 18px;
  cursor: pointer;
}

.yes {
  background-color: pink;
}

.no {
  background-color: lightblue;
}

iframe.spotify-embed {
  border-radius: 12px;
  margin-top: 15px;
}
</style>

</head>
<body>

<div class="container">
  <h1>¿Leyley quieres ser mi San Valentin atrasado? 💖</h1>

  <!-- Reproductor Spotify -->
  <iframe class="spotify-embed"
    src="https://open.spotify.com/embed/track/3EK4tGkSiO5xvvB5sM4tln"
    width="300" height="80"
    frameborder="0"
    allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture">
  </iframe>

  <button class="yes" onclick="aceptar()">Sí 💕</button>
  <button class="no" onmouseover="mover()">No 😢</button>
</div>

<script>
function aceptar() {
  alert("❤️ En este día tan especial, aunque la distancia nos separe, quiero recordarte que todos los días a tu lado son extraordinarios mi linda Leyley💖. Una fecha en el calendario me es indiferente cuando tengo la fortuna de compartir mi vida contigo 💕 porque lo que hace especial a este dia no es la fecha sino nosotros.No importa que hoy no estemos juntos 💌; lo verdaderamente especial son nuestros encuentros, los momentos que compartimos, porque somos nosotros quienes damos magia a cada día 💞.");
  // Aquí podrías agregar más acciones si quieres
}

function mover() {
  const btn = document.querySelector('.no');
  btn.style.position = 'absolute';
  btn.style.top = Math.random() * window.innerHeight + 'px';
  btn.style.left = Math.random() * window.innerWidth + 'px';
}
</script>

</body>
</html>
