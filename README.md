<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Curso de Gerência de Configuração de Software</title>
  <style>
    :root {
      --primary: #1e3a8a;   /* azul marinho */
      --secondary: #3b82f6; /* azul claro */
      --gray: #6b7280;
      --bg: #f9fafb;
      --max-width: 960px;
      font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    }
    *{margin:0;padding:0;box-sizing:border-box;}
    body {
      background: var(--bg);
      color: #111827;
      line-height: 1.6;
      display: flex;
      justify-content: center;
    }
    .container {
      width: 100%;
      max-width: var(--max-width);
      padding: 16px;
    }
    header {
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      color: white;
      text-align: center;
      padding: 50px 20px;
      border-radius: 12px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.15);
    }
    header h1 {
      font-size: 2.2rem;
      margin-bottom: 8px;
    }
    header p {
      font-size: 1.1rem;
      opacity: 0.9;
    }
    section {
      margin: 40px 0;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.06);
    }
    h2 {
      color: var(--primary);
      margin-bottom: 12px;
      font-size: 1.6rem;
    }
    ul {
      list-style: disc;
      margin-left: 20px;
      color: var(--gray);
    }
    .cta {
      text-align: center;
      margin-top: 20px;
    }
    .btn {
      display: inline-block;
      padding: 12px 24px;
      border-radius: 8px;
      background: var(--secondary);
      color: white;
      font-weight: bold;
      text-decoration: none;
      transition: 0.3s;
    }
    .btn:hover {
      background: var(--primary);
    }
    footer {
      text-align: center;
      margin-top: 40px;
      padding: 16px;
      font-size: 0.9rem;
      color: var(--gray);
    }
    @media (max-width: 600px) {
      header h1 {font-size: 1.8rem;}
      section {padding: 16px;}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Curso de Gerência de Configuração de Software</h1>
      <p>Aprenda as práticas essenciais para garantir qualidade, rastreabilidade e eficiência em projetos de software.</p>
    </header>

    <section>
      <h2>Sobre o Curso</h2>
      <p>Este curso apresenta os conceitos, ferramentas e práticas da <strong>Gerência de Configuração de Software</strong>, ajudando você a dominar técnicas de controle de versões, integração contínua e automação de processos.</p>
    </section>

    <section>
      <h2>Módulos do Curso</h2>
      <ul>
        <li>Introdução à Gerência de Configuração</li>
        <li>Controle de Versões (Git e GitHub)</li>
        <li>Integração e Entrega Contínua</li>
        <li>Automação de Builds e Testes</li>
        <li>Ferramentas e Boas Práticas</li>
      </ul>
    </section>

    <section>
      <h2>Inscreva-se</h2>
      <p>Garanta já sua vaga e avance na sua carreira de desenvolvimento de software.</p>
      <div class="cta">
        <a href="#" class="btn">Quero me inscrever</a>
      </div>
    </section>

    <footer>
      © 2025 Curso de Gerência de Configuração de Software · Todos os direitos reservados
    </footer>
  </div>
</body>
</html>
