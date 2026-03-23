<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Selene</title>

<!-- Ícones -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #0a0a0a;
  color: #eee;
}

/* HERO */
.hero {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: radial-gradient(circle, #111, #000);
  text-align: center;
}

.hero h1 {
  font-size: 4em;
  letter-spacing: 5px;
}

.hero p {
  opacity: 0.6;
  margin: 10px 0 30px;
}

/* BOTÃO PRINCIPAL */
.cta-main {
  background: #ff003c;
  padding: 20px 40px;
  font-size: 1.3em;
  border-radius: 50px;
  text-decoration: none;
  color: white;
  font-weight: bold;
  box-shadow: 0 0 20px #ff003c;
  animation: pulse 1.5s infinite;
  transition: 0.3s;
}

.cta-main:hover {
  transform: scale(1.1);
}

/* ANIMAÇÃO */
@keyframes pulse {
  0% { box-shadow: 0 0 10px #ff003c; }
  50% { box-shadow: 0 0 25px #ff003c; }
  100% { box-shadow: 0 0 10px #ff003c; }
}

/* BOTÕES FLUTUANTES */
.float-buttons {
  position: fixed;
  bottom: 20px;
  right: 20px;
  display: flex;
  flex-direction: column;
  gap: 10px;
  z-index: 999;
}

.float-buttons a {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 12px 18px;
  border-radius: 50px;
  color: white;
  text-decoration: none;
  font-weight: bold;
  box-shadow: 0 0 15px rgba(0,0,0,0.5);
  transition: 0.3s;
}

.float-buttons a:hover {
  transform: scale(1.1);
}

.whatsapp {
  background: #25D366;
}

.gmail {
  background: #D44638;
}

/* SEÇÕES */
.section {
  padding: 80px 20px;
  max-width: 900px;
  margin: auto;
}

/* MANIFESTO */
.manifesto {
  font-size: 1.2em;
  line-height: 1.6;
  border-left: 3px solid #ff003c;
  padding-left: 20px;
}

/* CONTATO */
.contact-box {
  text-align: center;
  background: #111;
  padding: 50px 20px;
  border-radius: 15px;
}

.contact-buttons a {
  display: inline-block;
  margin: 15px;
  padding: 15px 25px;
  border-radius: 10px;
  text-decoration: none;
  color: white;
  font-weight: bold;
  transition: 0.3s;
}

.whats {
  background: #25D366;
}

.insta {
  background: #E1306C;
}

.gmail-btn {
  background: #D44638;
}

.contact-buttons a:hover {
  transform: scale(1.1);
}

/* GALERIA */
.gallery img {
  width: 100%;
  margin-top: 15px;
  border-radius: 10px;
  filter: grayscale(100%);
  transition: 0.3s;
}

.gallery img:hover {
  filter: grayscale(0%);
}

footer {
  text-align: center;
  padding: 30px;
  opacity: 0.5;
}
</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
  <h1>SELENE</h1>
  <p>rock autoral • intensidade • presença</p>

  <a href="https://contate.me/5535999710526" class="cta-main">
    CONTATE AGORA
  </a>
</section>

<!-- SOBRE -->
<section class="section">
  <h2>Sobre</h2>
  <p class="manifesto">
    Selene não é apenas um som.
    Somos o que esse mundo necessita.  
    Somos a lua.
  </p>
</section>

<!-- GALERIA -->
<section class="section gallery">
  <h2>Visual</h2>
  <img src="https://i.ibb.co/ycZzpLzk/1000084294-removebg-preview.png">
</section>

<!-- CONTATO -->
<section class="section">
  <div class="contact-box">
    <h2>Leve a Selene para seu palco</h2>
    <p>Clique abaixo e fale direto com a banda</p>

    <div class="contact-buttons">
      <a href="https://contate.me/5535999710526" class="whats">
        <i class="fab fa-whatsapp"></i> WhatsApp
      </a>

      <a href="https://www.instagram.com/seleneband_/" class="insta">
        <i class="fab fa-instagram"></i> Instagram
      </a>

      <a href="mailto:bandselene@gmail.com?subject=Contato%20com%20a%20banda%20Selene&body=Olá,%20quero%20contratar%20a%20banda%20Selene!" class="gmail-btn">
        <i class="fas fa-envelope"></i> Gmail
      </a>
    </div>
  </div>
</section>

<!-- BOTÕES FLUTUANTES -->
<div class="float-buttons">
  <a href="https://contate.me/5535999710526" class="whatsapp">
    <i class="fab fa-whatsapp"></i>
  </a>

  <a href="mailto:bandselene@gmail.com?subject=Contato%20com%20a%20banda%20Selene" class="gmail">
    <i class="fas fa-envelope"></i>
  </a>
</div>

<footer>
  Selene © 2026
</footer>

</body>
</html>
