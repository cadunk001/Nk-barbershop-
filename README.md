# Nk-barbershop-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NK Barbershop - Serviços</title>
  <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@700&family=Raleway&display=swap" rel="stylesheet">
  <style>
    body {
      background: #1E2526;
      color: #2A9D8F;
      font-family: 'Raleway', sans-serif;
      margin: 0;
      padding: 0;
    }
    .services-section {
      padding: 50px;
      text-align: center;
    }
    .services-section h1 {
      font-family: 'Oswald', sans-serif;
      font-size: 3em;
      color: #E76F51;
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .service-card {
      background: #2D3436;
      border-radius: 10px;
      padding: 20px;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .service-card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 10px #E76F51;
    }
    .service-card h3 {
      font-family: 'Oswald', sans-serif;
      font-size: 1.8em;
      color: #F4A261;
      margin: 10px 0;
    }
    .service-card p {
      font-size: 1em;
      color: #A3BFFA;
    }
    .service-card .price {
      color: #E76F51;
      font-weight: bold;
      font-size: 1.2em;
    }
    .service-card a {
      display: inline-block;
      background: #E76F51;
      color: #FFFFFF;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      margin-top: 10px;
      transition: background 0.3s;
    }
    .service-card a:hover {
      background: #D65A3D;
    }
  </style>
</head>
<body>
  <section class="services-section">
    <h1>NK Barbershop</h1>
    <p>Escolha seu corte, agende pelo WhatsApp e saia com estilo!</p>
    <div class="services-grid">
      <div class="service-card">
        <h3>Degradê Navalhado</h3>
        <p class="price">R$ 30,00</p>
        <p>Precisão na navalha, estilo no visual.</p>
        <a href="https://wa.me/5562993571882?text=Oi,%20quero%20agendar%20um%20Degradê%20Navalhado">Agendar Agora</a>
      </div>
      <div class="service-card">
        <h3>Corte Social</h3>
        <p class="price">R$ 25,00</p>
        <p>Clássico, limpo e pronto pra qualquer ocasião.</p>
        <a href="https://wa.me/5562993571882?text=Oi,%20quero%20agendar%20um%20Corte%20Social">Agendar Agora</a>
      </div>
      <div class="service-card">
        <h3>Sobrancelha</h3>
        <p class="price">R$ 10,00</p>
        <p>Acabamento perfeito pro seu olhar.</p>
        <a href="https://wa.me/5562993571882?text=Oi,%20quero%20agendar%20uma%20Sobrancelha">Agendar Agora</a>
      </div>
      <div class="service-card">
        <h3>Pezinho</h3>
        <p class="price">R$ 10,00</p>
        <p>Detalhe que faz toda a diferença.</p>
        <a href="https://wa.me/5562993571882?text=Oi,%20quero%20agendar%20um%20Pezinho">Agendar Agora</a>
      </div>
      <div class="service-card">
        <h3>Corte Tesoura</h3>
        <p class="price">R$ 35,00</p>
        <p>Elegância e técnica em cada tesourada.</p>
        <a href="https://wa.me/5562993571882?text=Oi,%20quero%20agendar%20um%20Corte%20Tesoura">Agendar Agora</a>
      </div>
      <div class="service-card">
        <h3>Limpeza de Pele</h3>
        <p class="price">R$ 25,00</p>
        <p>Rosto renovado, vibe impecável.</p>
        <a href="https://wa.me/5562993571882?text=Oi,%20quero%20agendar%20uma%20Limpeza%20de%20Pele">Agendar Agora</a>
      </div>
    </div>
  </section>
</body>
</html>
