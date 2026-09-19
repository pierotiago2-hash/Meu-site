# Meu-site
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Meu Site</title>
</head>
<body>
  <h1>Olá! Bem-vindo A aula de tecnologia</h1>
  

  <button onclick="alert('Obrigado por visitar!')">
    Clique aqui
  </button>
</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Naruto 👍</title>

  <style>
    body {
      margin: 0;
      background: #111;
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    h1 {
      margin-top: 30px;
      color: orange;
    }

    img {
      width: 300px;
      max-width: 90%;
      border-radius: 15px;
      margin-top: 20px;
    }

    p {
      font-size: 20px;
    }
  </style>
</head>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

 

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0b1020;
      color: white;
      text-align: center;
    }

    h1 {
      color: #00aaff;
      margin-top: 30px;
    }

    .curso {
      margin: 30px auto;
      width: 90%;
      max-width: 500px;
    }

    .curso img {
      width: 100%;
      border-radius: 15px;
    }

    p {
      font-size: 20px;
    }

    button {
      background: #00aaff;
      color: white;
      border: none;
      padding: 15px 25px;
      border-radius: 10px;
      font-size: 18px;
    }
  </style>
</head>

<body>


 

    <p>Aprenda tecnologia, programação e criação de sites!</p>

  

</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Curso de Tecnologia</title>

  <style>
    body {
      font-family: Arial;
      background: #0b1020;
      color: white;
      text-align: center;
      padding: 30px;
    }

    button {
      background: #00aaff;
      color: white;
      border: none;
      padding: 15px 25px;
      border-radius: 10px;
      font-size: 18px;
      cursor: pointer;
    }

    .aulas {
      display: none;
      margin-top: 30px;
    }

    .aula {
      background: #18213a;
      padding: 20px;
      margin: 15px auto;
      border-radius: 10px;
      max-width: 500px;
    }
  </style>
</head>

<body>

  
  <div class="aulas" id="aulas">

    
  </div>

  <script>
    function começarCurso() {
      document.getElementById("aulas").style.display = "block";
    }
  </script>

</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Curso de Tecnologia</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0b1020;
      color: white;
    }

    header {
      text-align: center;
      padding: 30px;
      background: #111a33;
    }

    header h1 {
      color: #00aaff;
    }

    .curso {
      max-width: 700px;
      margin: 30px auto;
      padding: 15px;
    }

    .aula {
      background: #18213a;
      margin-bottom: 15px;
      padding: 20px;
      border-radius: 12px;
    }

    .aula h2 {
      color: #00aaff;
    }

    .aula p {
      color: #ddd;
      font-size: 17px;
    }

    button {
      background: #00aaff;
      color: white;
      border: none;
      padding: 12px 20px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
    }

    button:hover {
      background: #0088cc;
    }

    .conteudo {
      display: none;
      margin-top: 20px;
      padding: 20px;
      background: #0f172a;
      border-radius: 10px;
      line-height: 1.6;
    }
  </style>
</head>

<body>

<header>
  <h1>💻 Curso de Tecnologia</h1>
  <p>Aprenda tecnologia do zero!</p>
</header>

<div class="curso">

  <!-- AULA 1 -->
  <div class="aula">
    <h2>📚 Aula 1 — Introdução à Tecnologia</h2>
    <p>Conheça os principais conceitos de tecnologia.</p>

    <button onclick="mostrar('aula1')">
      Começar Aula 1
    </button>

    <div id="aula1" class="conteudo">
      <h3>O que é tecnologia?</h3>

      <p>
        Tecnologia é o conjunto de conhecimentos, ferramentas e técnicas
        usados para resolver problemas e facilitar tarefas.
      </p>

      <h3>📱 Exemplos de tecnologia</h3>

      <p>
        Celulares, computadores, videogames, internet, inteligência
        artificial, aplicativos e muitos outros dispositivos e sistemas.
      </p>

      <h3>🎯 Objetivo da aula</h3>

      <p>
        Entender como a tecnologia está presente no nosso dia a dia
        e conhecer alguns dos principais conceitos da área.
      </p>
    </div>
  </div>


  <!-- AULA 2 -->
  <div class="aula">
    <h2>🌐 Aula 2 — HTML</h2>
    <p>Aprenda a criar sua primeira página de internet.</p>

    <button onclick="mostrar('aula2')">
      Começar Aula 2
    </button>

    <div id="aula2" class="conteudo">
      <h3>O que é HTML?</h3>

      <p>
        HTML é uma linguagem usada para estruturar páginas da internet.
      </p>

      <h3>📝 Exemplo</h3>

      <pre>
&lt;h1&gt;Meu primeiro site&lt;/h1&gt;

&lt;p&gt;Olá, mundo!&lt;/p&gt;
      </pre>

      <p>
        Com HTML você pode criar títulos, textos, imagens, links,
        botões e outras partes de uma página.
      </p>
    </div>
  </div>


  <!-- AULA 3 -->
  <div class="aula">
    <h2>🎨 Aula 3 — CSS</h2>
    <p>Aprenda a deixar seu site bonito.</p>

    <button onclick="mostrar('aula3')">
      Começar Aula 3
    </button>

    <div id="aula3" class="conteudo">
      <h3>O que é CSS?</h3>

      <p>
        CSS é usado para estilizar páginas HTML.
        Com ele podemos mudar cores, tamanhos, fontes,
        espaçamentos e muito mais.
      </p>

      <h3>🎨 Exemplo</h3>

      <pre>
body {
  background: black;
  color: white;
}

h1 {
  color: blue;
}
      </pre>
    </div>
  </div>


  <!-- AULA 4 -->
  <div class="aula">
    <h2>⚡ Aula 4 — JavaScript</h2>
    <p>Aprenda a colocar funções e interatividade no site.</p>

    <button onclick="mostrar('aula4')">
      Começar Aula 4
    </button>

    <div id="aula4" class="conteudo">
      <h3>O que é JavaScript?</h3>

      <p>
        JavaScript permite adicionar comportamentos e interatividade
        às páginas da internet.
      </p>

      <h3>⚡ Exemplo</h3>

      <pre>
function mensagem() {
  alert("Olá! Bem-vindo ao curso!");
}
      </pre>

      <button onclick="alert('Olá! Você está aprendendo JavaScript! 🚀')">
        Testar JavaScript
      </button>
    </div>
  </div>

</div>


<script>
  function mostrar(id) {
    const conteudo = document.getElementById(id);

    if (conteudo.style.display === "block") {
      conteudo.style.display = "none";
    } else {
      conteudo.style.display = "block";
    }
  }
</script>

</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Opinião Sobre Tecnologia</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f1f5f9;
      text-align: center;
      padding: 30px;
    }

    .caixa {
      max-width: 500px;
      margin: auto;
      background: white;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.15);
    }

    h1 {
      color: #2563eb;
    }

    textarea {
      width: 100%;
      height: 150px;
      padding: 12px;
      box-sizing: border-box;
      border: 2px solid #ddd;
      border-radius: 10px;
      resize: none;
      font-size: 16px;
    }

    button {
      margin-top: 15px;
      padding: 12px 25px;
      background: #2563eb;
      color: white;
      border: none;
      border-radius: 10px;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background: #1d4ed8;
    }

    #resposta {
      margin-top: 20px;
      font-weight: bold;
    }
  </style>
</head>

<body>

  
