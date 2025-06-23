# Projeto-de-P-rtifolio-Alura

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Portfólio da Ana Giullia</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #fff0f6, #ffe6f0);
      color: #3d3d3d;
    }
    header {
      background-color: #d63384;
      color: white;
      text-align: center;
      padding: 40px 20px;
      position: relative;
    }
    header::before {
      content: "💇‍♀️✂️💄";
      position: absolute;
      top: 10px;
      left: 15px;
      font-size: 20px;
    }
    header::after {
      content: "💅🎀💆‍♀️";
      position: absolute;
      top: 160px;
      right: 15px;
      font-size: 20px;
    }
    .container {
      max-width: 900px;
      margin: 30px auto;
      background-color: #fff;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
    h2 {
      color: #b03060;
    }
    h1{
        color :rgb(104, 17, 78)
    }
    section {
      margin-bottom: 30px;
    }
    .highlight {
      background-color: #ffe0eb;
      padding: 15px;
      border-left: 6px solid #d63384;
      border-radius: 8px;
    }
    .decor {
      text-align: center;
      font-size: 30px;
      margin-top: 25px;
      opacity: 0.8;
    }
    .decor span {
      margin: 0 10px;
      transition: transform 0.3s ease;
      cursor: default;
    }
    .decor span:hover {
      transform: scale(1.2) rotate(-5deg);
      opacity: 1;
    }
    footer {
      background-color: #a61e4d;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      margin-top: 40px;
    }
    .espelho {
      background-color: #fce4ec;
      padding: 20px;
      border: 2px dashed #d63384;
      border-radius: 12px;
      font-family: 'Courier New', monospace;
      margin-top: 15px;
    }
    ul {
      padding-left: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Ana Giullia</h1>
    <p>Apaixonada por transformar autoestima com beleza e carinho</p>
  </header>

  <div class="container">
    <section>
      <h2>Sobre Mim</h2>
      <p>Meu nome é Ana Giullia e sou aspirante a cabeleireira.Busco trabalhar com o corte de cabelo feminino, escova e hidratação, estou sempre atualizando meu conhecimento com as últimas tendências da beleza e busco aprender cada vez mais.</p>
    </section>
    <section>
      <h2>Formação Acadêmica</h2>
      <ul>
        <li> Fadlo haidar, Ensino medio- Cursando </li>
      </ul>
    </section>
    <section class="highlight">
      <h2>Habilidades</h2>
      <ul>
        <li>Cortes femininos modernos e clássicos</li>
        <li>Escova lisa e modelada</li>
        <li>Aplicação de hidratação, nutrição e reconstrução capilar</li>
        <li>Atendimento simpático e personalizado</li>
      </ul>
    </section>
    <section class="espelho">
      <h2>Contato</h2>
      <p>Email: 00001116672200sp@al.educacao.sp.gov.br</p>
      <p>Telefone:+55 11 99280-1778</p>
      <p>Localização: São Paulo - SP</p>
    </section>
    <div class="decor">
      <span>✂️</span>
      <span>💇‍♀️</span>
      <span>🎀</span>
      <span>💄</span>
      <span>💅</span>
      <span>🪞</span>
      <span>🧴</span>
      <span>🧖‍♀️</span>
    </div>
  </div>
  <footer>
    <p> Ana Giullia - Portfólio de 
    Cabeleireira</p>
    <div style="text-align: center;">
  <p>São Paulo-2025</p>
</div>

  </footer>

</body>
</html>
