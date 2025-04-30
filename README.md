# home-office
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Informações - Home Office</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .whatsapp-btn-container {
      text-align: center;
    }
    .whatsapp-btn {
      display: inline-block;
      background-color: #25d366;
      color: white;
      padding: 15px 20px;
      border-radius: 10px;
      font-size: 18px;
      margin: 10px;
      text-decoration: none;
    }
    .whatsapp-btn:hover {
      background-color: #128c7e;
    }
  </style>
</head>
<body class="bg-light text-dark">

  <!-- Cabeçalho -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand text-dark" href="#">Home Office</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menuNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="menuNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Início</a></li>
          <li class="nav-item"><a class="nav-link" href="#servicos">Serviços</a></li>
          <li class="nav-item"><a class="nav-link" href="#depoimentos">Depoimentos</a></li>
          <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Conteúdo -->
  <div class="container my-5">
    <div class="bg-white p-4 shadow rounded">
      <h1 class="text-dark">Bem-vindo ao Seu Home Office!</h1>
      <p class="lead">Trabalhar de casa nunca foi tão fácil. Oferecemos soluções completas para profissionais que atuam em home office, proporcionando praticidade, produtividade e conforto no seu dia a dia.</p>

      <!-- Serviços -->
      <h2 id="servicos" class="mt-4">O que oferecemos:</h2>
      <ul class="list-group list-group-flush mb-4">
        <li class="list-group-item">
          <strong>Consultoria de Ambiente de Trabalho:</strong>
          ajudamos você a montar um espaço funcional e ergonômico.
        </li>
        <li class="list-group-item">
          <strong>Suporte Técnico Remoto:</strong>
          suporte para configurações, conexões e segurança digital.
        </li>
        <li class="list-group-item">
          <strong>Ferramentas e Dicas de Produtividade:</strong>
          recomendamos os melhores aplicativos e técnicas para organizar sua rotina e aumentar o foco:
          <ul>
            <li><strong>Trello / Notion:</strong> organização de tarefas e projetos com quadros visuais e listas personalizadas.</li>
            <li><strong>Google Agenda:</strong> agendamento de reuniões, alertas e planejamento diário.</li>
            <li><strong>Técnica Pomodoro:</strong> ciclos de 25 minutos de foco com pausas curtas para manter a produtividade.</li>
            <li><strong>GTD (Getting Things Done):</strong> método que ajuda a organizar e executar tarefas de forma eficaz.</li>
            <li><strong>RescueTime:</strong> monitora seu tempo no computador e mostra onde você pode melhorar seu foco.</li>
          </ul>
        </li>
        <li class="list-group-item">
          <strong>Comunidade Online:</strong>
          participe de grupos e fóruns para trocar experiências.
        </li>
      </ul>

      <!-- Benefícios -->
      <h2>Por que escolher o Home Office?</h2>
      <div class="row row-cols-1 row-cols-sm-2 g-3 mb-4">
        <div class="col"><span class="badge bg-success p-2">Flexibilidade de horários</span></div>
        <div class="col"><span class="badge bg-success p-2">Mais tempo com a família</span></div>
        <div class="col"><span class="badge bg-success p-2">Redução de custos com deslocamento</span></div>
        <div class="col"><span class="badge bg-success p-2">Qualidade de vida e autonomia</span></div>
      </div>

      <!-- Depoimentos -->
      <h2 id="depoimentos" class="mt-5">Depoimentos</h2>
      <div class="row g-4">
        <div class="col-md-6">
          <div class="card shadow-sm">
            <div class="card-body">
              <p>"Com o suporte do Home Office, montei meu escritório em casa e minha produtividade dobrou!"</p>
              <h6 class="text-end text-muted">– Ana Paula, Designer Gráfica</h6>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="card shadow-sm">
            <div class="card-body">
              <p>"A consultoria foi essencial para adaptar meu ambiente de trabalho. Recomendo demais!"</p>
              <h6 class="text-end text-muted">– João Carlos, Consultor de TI</h6>
            </div>
          </div>
        </div>
      </div>

      <!-- Contato -->
      <h2 id="contato" class="mt-5">Entre em Contato</h2>
      <p>Preencha o formulário abaixo para entrar em contato conosco.</p>
      <form>
        <div class="mb-3">
          <label for="nome" class="form-label">Nome</label>
          <input type="text" class="form-control" id="nome" required>
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email" required>
        </div>
        <div class="mb-3">
          <label for="mensagem" class="form-label">Mensagem</label>
          <textarea class="form-control" id="mensagem" rows="4" required></textarea>
        </div>
        <button type="submit" class="btn btn-dark">Enviar</button>
      </form>

      <!-- Mapa -->
      <h3 class="mt-5">Onde Estamos</h3>
      <div class="ratio ratio-16x9 mt-3">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3468.432256241358!2d-47.921779!3d-15.780727!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x935a3847d5b48e33%3A0x1d01b59c7fc0d232!2sAv.%20Pres.%20JK%2C%20Bras%C3%ADlia%20-%20DF!5e0!3m2!1spt-BR!2sbr!4v1615185153684!5m2!1spt-BR!2sbr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
      </div>
    </div>
  </div>

  <!-- Opções de Assistente -->
  <div class="whatsapp-btn-container mb-4">
    <h3>Escolha com qual assistente você quer conversar:</h3>
    <div class="mb-3">
      <a href="https://wa.me/557998878403" class="btn btn-outline-dark" target="_blank" title="Fale com Emilly">
        Fale com Emilly
      </a>
    </div>
    <div class="mb-3">
      <a href="https://wa.me/556293647345" class="btn btn-outline-dark" target="_blank" title="Fale com Juan">
        Fale com Juan
      </a>
    </div>
  </div>

  <!-- Rodapé -->
  <footer class="text-center text-muted py-4">
    &copy; 2025 Seu Home Office. Todos os direitos reservados.
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
