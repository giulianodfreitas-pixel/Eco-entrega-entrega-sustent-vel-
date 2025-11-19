<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Landing Page - MVP</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #4a69bd;
      color: white;
      padding: 40px;
      text-align: center;
    }
    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #4a69bd;
    }
    .cta {
      background: #f1f2f6;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
    }
    form input, form button {
      width: 100%;
      padding: 12px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 16px;
    }
    form button {
      background: #4a69bd;
      color: white;
      cursor: pointer;
      font-weight: bold;
    }
    form button:hover {
      background: #3b55a1;
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>Eco Entrega — Soluções Sustentáveis de Entrega</h1>
    <p>Entregas rápidas, econômicas e sustentáveis para pequenos negócios locais.</p>
  </header>

  <section>
    <h2>O que é a Eco Entrega?</h2>
    <p>A Eco Entrega é uma solução de logística sustentável que conecta pequenos empreendedores a entregadores que utilizam bicicletas, motos elétricas ou rotas otimizadas, reduzindo custos e diminuindo o impacto ambiental.</p>
    <img src="https://via.placeholder.com/800x300?text=Eco+Entrega" alt="Entrega sustentável" style="width:100%; border-radius: 10px; margin-top: 20px;" />

    <h2>Como ajudamos pequenos negócios?</h2>
    <ul>
      <li>Reduzimos custos com entregas por meio de rotas inteligentes e veículos ecológicos.</li>
      <li>Aumentamos a eficiência, garantindo entregas rápidas e rastreáveis.</li>
      <li>Fortalecemos a imagem sustentável da sua marca perante os consumidores.</li>
    </ul>

    <div class="cta">
      <h3>Participe do teste inicial da Eco Entrega!</h3>
      <p>Quer receber nossas condições especiais para parceiros do MVP? Deixe seu contato abaixo:</p>
      <form>
        <input type="text" placeholder="Seu nome" required />
        <input type="email" placeholder="Seu e-mail" required />
        <input type="text" placeholder="Seu WhatsApp" required />
        <button type="submit">Quero participar do MVP</button>
      </form>
    </div>
  </section>

  <footer>
    <p>© 2025 — Eco Entrega | Logística Sustentável</p>
  </footer>
</body>
</html>
