<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Minha Condessa</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Cinzel&display=swap');
  body {
    margin: 0;
    background: #120202;
    color: #8B0000;
    font-family: 'Cinzel', serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden;
  }
  .container {
    background: linear-gradient(135deg, #1b0000cc, #330000cc);
    border: 2px solid #8B0000;
    padding: 2rem 3rem;
    max-width: 600px;
    border-radius: 15px;
    box-shadow: 0 0 20px #8B0000aa;
    text-align: center;
    opacity: 0;
    animation: fadeIn 6s forwards;
  }
  h1 {
    margin-bottom: 1.2rem;
    font-size: 2.5rem;
    color: #9f1b1b;
    text-shadow: 1px 1px 2px #330000;
  }
  p {
    font-size: 1.2rem;
    line-height: 1.6;
    margin-bottom: 1rem;
  }
  .audio-player {
    margin-top: 1.5rem;
    outline: none;
  }
  @keyframes fadeIn {
    to { opacity: 1; }
  }
  .password-screen {
    background: #120202;
    color: #8B0000;
    font-family: 'Cinzel', serif;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  input[type="password"] {
    font-size: 1.2rem;
    padding: 0.5rem 1rem;
    border: 2px solid #8B0000;
    border-radius: 8px;
    background: #2e0000;
    color: #f9f9f9;
    text-align: center;
    margin-top: 1rem;
    outline: none;
  }
  button {
    margin-top: 1rem;
    background-color: #8B0000;
    border: none;
    padding: 0.5rem 1.2rem;
    font-size: 1.1rem;
    border-radius: 8px;
    color: #f9f9f9;
    cursor: pointer;
    font-family: 'Cinzel', serif;
  }
  button:hover {
    background-color: #b22222;
  }
</style>
</head>
<body>
<div id="passwordScreen" class="password-screen">
  <h2>Insira a senha para acessar</h2>
  <input type="password" id="passwordInput" placeholder="Senha" />
  <button onclick="checkPassword()">Entrar</button>
  <p id="errorMsg" style="color:#b22222; margin-top:10px;"></p>
</div>

<div id="content" class="container" style="display:none;">
  <h1>Minha Condessa</h1>
  <p>Querer te tocar,<br />
  é querer mais que um desejo no ar.<br />
  É querer te amar,<br />
  me render ao seu pescoço,<br />
  querendo mais de seu gosto.</p>
  <p>Sabendo de minhas fraquezas,<br />
  seja a minha única leveza,<br />
  que posso ter a certeza,<br />
  mostrando a verdadeira beleza<br />
  de seus olhos, minha condessa.</p>
  <p>Servindo pela eternidade,<br />
  minha alma jura lealdade.<br />
  Com seu sangue em minha face,<br />
  mordendo cada parte<br />
  de sua alma em meu cálice.</p>

  <audio class="audio-player" controls>
    <source src="https://www.youtube.com/embed/6Bsae5XweAY" type="audio/mpeg" />
    Seu navegador não suporta o elemento de áudio.
  </audio>
</div>

<script>
  const correctPassword = "coelhinha";
  const passwordScreen = document.getElementById("passwordScreen");
  const content = document.getElementById("content");
  const errorMsg = document.getElementById("errorMsg");
  const passwordInput = document.getElementById("passwordInput");

  function checkPassword() {
    if (passwordInput.value.toLowerCase() === correctPassword) {
      passwordScreen.style.display = "none";
      content.style.display = "block";
    } else {
      errorMsg.textContent = "Senha incorreta. Tente novamente.";
      passwordInput.value = "";
    }
  }
</script>
</body>
</html>
