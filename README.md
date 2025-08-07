
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Mercearia Belém</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
    }

    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #34495e;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .produtos {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .produto {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 15px;
      width: 200px;
      text-align: center;
    }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Mercearia Belém</h1>
    <p>Produtos frescos e de qualidade para sua casa</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#produtos">Produtos</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="sobre">
    <h2>Sobre Nós</h2>
    <p>Somos uma mercearia tradicional localizada no coração de Belém. Trabalhamos com produtos frescos, locais e com atendimento de qualidade. Nossa missão é levar o melhor para sua mesa todos os dias.</p>
  </section>

  <section id="produtos">
    <h2>Nossos Produtos</h2>
    <div class="produtos">
      <div class="produto">
        <h3>Arroz Tipo 1</h3>
        <p>5kg - R$ 25,00</p>
      </div>
      <div class="produto">
        <h3>Feijão Carioca</h3>
        <p>1kg - R$ 8,90</p>
      </div>
      <div class="produto">
        <h3>Leite Integral</h3>
        <p>1L - R$ 4,50</p>
      </div>
      <!-- Adicione mais produtos aqui -->
    </div>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>📍 Rua da Mercearia, 123 - Belém, PA</p>
    <p>📞 (91) 99999-9999</p>
    <p>📧 contato@merceariabelem.com.br</p>
  </section>

  <footer>
    <p>&copy; 2025 Mercearia Belém - Todos os direitos reservados</p>
  </footer>

</body>
</html>
