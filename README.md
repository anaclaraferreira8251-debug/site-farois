<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Auto Parts Full — Loja de Faróis</title>

  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f3f3f3; color: #333; }
    header { background: #1a73e8; color: white; padding: 20px; text-align: center; font-size: 26px; font-weight: bold; }

    nav { background: #0f5bd0; padding: 10px; text-align: center; }
    nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }

    .container { max-width: 1000px; margin: 30px auto; background: white; padding: 20px;
      border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }

    h2 { color: #1a73e8; margin-top: 20px; }

    .produtos { display: grid; grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); gap: 20px; }

    .card-produto {
      background: #fafafa; padding: 15px; border-radius: 10px; border: 1px solid #ddd;
      text-align: center;
    }

    .card-produto img { max-width: 100%; height: 150px; object-fit: contain; }
    .card-produto h3 { margin: 10px 0; font-size: 18px; }

    .preco { color: #0a7a27; font-weight: bold; margin-bottom: 10px; }

    .btn {
      padding: 10px 15px; background: #1a73e8; color: white; border: none; border-radius: 5px;
      cursor: pointer; transition: 0.2s;
    }
    .btn:hover { background: #0f5bd0; }

    footer { text-align: center; margin-top: 40px; padding: 15px; background: #e8e8e8; font-size: 14px; }
  </style>
</head>

<body>

<header>Auto Parts Full — Faróis Automotivos</header>

<nav>
  <a href="index.html">Home</a>
  <a href="contato.html">Contato</a>
</nav>

<div class="container">

  <h2>🔥 Produtos em Destaque</h2>

  <div class="produtos">
    
    <div class="card-produto">
      <img src="https://http2.mlstatic.com/D_NQ_NP_2X_828263-MLB45268994175_032021-F.webp" alt="Farol Corolla 2018">
      <h3>Farol Corolla 2018</h3>
      <p class="preco">R$ 850,00</p>
      <button class="btn">Comprar</button>
    </div>

    <div class="card-produto">
      <img src="https://acdn.mitiendanube.com/stores/001/287/383/products/733661-mla31076827032_062019-o1-92c99f2fb82842f66d16482350f43147-640-0.webp" alt="Farol Onix 2020">
      <h3>Farol Traseiro Onix 2020</h3>
      <p class="preco">R$ 420,00</p>
      <button class="btn">Comprar</button>
    </div>

    <div class="card-produto">
      <img src="https://cdn.awsli.com.br/2500x2500/1000/1000579/produto/66556641/8be3fbfd70.jpg" alt="Farol HB20 2019">
      <h3>Farol HB20 2019</h3>
      <p class="preco">R$ 680,00</p>
      <button class="btn">Comprar</button>
    </div>

    <div class="card-produto">
      <img src="https://cdn.dooca.store/1186/products/farol-de-neblina-honda-civic-2017-2018-le-esquerdo-tyc_640x640+fill_ffffff.jpg?v=1678800460&webp=0" alt="Farol Civic 2017">
      <h3>Farol de Neblina Civic 2017</h3>
      <p class="preco">R$ 350,00</p>
      <button class="btn">Comprar</button>
    </div>

  </div>

  <h2>Sobre a Auto Parts Full</h2>
  <p>
    A Auto Parts Full é especializada em faróis automotivos para diversos modelos.
    Trabalhamos com peças originais e de ótima qualidade.
  </p>

</div>

<footer>Auto Parts Full © 2025 — Faróis Automotivos</footer>

</body>
</html>
