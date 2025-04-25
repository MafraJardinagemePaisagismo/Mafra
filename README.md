<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VerdeVivo - Jardinagem e Paisagismo</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f9f4;
      color: #2e3d2f;
    }
    header {
      background-color: #5b8c5a;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    nav {
      background-color: #4e704e;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    footer {
      background-color: #5b8c5a;
      color: white;
      text-align: center;
      padding: 20px;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    input, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #4e704e;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #3e593e;
    }
  </style>
</head>
<body>

  <header>
    <h1>VerdeVivo</h1>
    <p>Jardinagem & Paisagismo com Amor pela Natureza</p>
  </header>

  <nav>
    <a href="#servicos">Serviços</a>
    <a href="#sobre">Sobre Nós</a>
    <a href="#galeria">Galeria</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="servicos" class="section">
    <h2>Nossos Serviços</h2>
    <div class="services">
      <div>
        <h3>Paisagismo</h3>
        <p>Projetos personalizados para valorizar seu espaço com beleza e funcionalidade.</p>
      </div>
      <div>
        <h3>Jardinagem</h3>
        <p>Manutenção completa do seu jardim: poda, adubação, limpeza e revitalização.</p>
      </div>
      <div>
        <h3>Gramados</h3>
        <p>Instalação e cuidados com gramados naturais e ornamentais.</p>
      </div>
      <div>
        <h3>Irrigação</h3>
        <p>Sistemas de irrigação automatizados para manter tudo sempre verde.</p>
      </div>
    </div>
  </section>

  <section id="sobre" class="section">
    <h2>Sobre Nós</h2>
    <p>Somos apaixonados pela natureza e dedicados a transformar espaços com criatividade, técnica e cuidado. Atendemos residências, empresas e condomínios com excelência e pontualidade.</p>
  </section>

  <section id="galeria" class="section">
    <h2>Galeria de Projetos</h2>
    <p>Em breve, você poderá conferir aqui fotos dos nossos trabalhos realizados!</p>
  </section>

  <section id="contato" class="section">
    <h2>Fale Conosco</h2>
    <form>
      <input type="text" name="nome" placeholder="Seu nome" required>
      <input type="email" name="email" placeholder="Seu email" required>
      <textarea name="mensagem" rows="5" placeholder="Sua mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>
    <p>Ou entre em contato pelas redes sociais:</p>
    <ul>
      <li>WhatsApp: (11) 98765-4321</li>
      <li>Email: contato@verdevivo.com.br</li>
      <li>Instagram: @verdevivo.jardins</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 VerdeVivo - Todos os direitos reservados</p>
  </footer>

</body>
</html>

