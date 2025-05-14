<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Villa Papel</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="header">
    <div class="container">
      <h1>Villa Papel</h1>
      <nav>
        <a href="index.html">Início</a>
        <a href="produtos.html">Produtos</a>
        <a href="carrinho.html">Carrinho</a>
        <a href="https://wa.me/5562991000090" target="_blank">Contato</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h2>"Tudo o que é feito com alma permanece no coração de quem recebe."</h2>
      <a href="produtos.html" class="btn">Explorar a loja</a>
    </div>
  </section>

  <section class="destaques">
    <div class="container">
      <h3>Destaques</h3>
      <div class="produtos">
        <div class="produto">
          <img src="img/diario-vida.jpg" alt="Diário de Vida" />
          <h4>Diário de Vida</h4>
          <p>R$ 89,90</p>
          <a href="produto.html" class="btn">Ver mais</a>
        </div>
        <div class="produto">
          <img src="img/caneca-mae.jpg" alt="Caneca Dia das Mães" />
          <h4>Caneca "Te Amo Mamãe"</h4>
          <p>R$ 39,90</p>
          <a href="produto.html" class="btn">Ver mais</a>
        </div>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="container">
      <p>Villa Papel © 2015 - Criado por Sandrinha Fleury</p>
      <p><a href="https://wa.me/5562991000090">Fale conosco no WhatsApp</a></p>
    </div>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Villa Papel - Produtos</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <div class="logo">Villa Papel</div>
      <ul>
        <li><a href="index.html">Início</a></li>
        <li><a href="produtos.html">Produtos</a></li>
        <li><a href="carrinho.html">Carrinho</a></li>
      </ul>
    </nav>
  </header>

  <main class="produtos-container">
    <h1>Nossos Produtos</h1>
    <div class="produtos-grid">
      <div class="produto">
        <img src="produto1.jpg" alt="Caneca Personalizada">
        <h2>Caneca Amor de Mãe</h2>
        <p>Caneca com frase personalizada para presentear com carinho.</p>
        <span class="preco">R$ 39,90</span>
        <a href="produto.html">Ver mais</a>
      </div>

      <div class="produto">
        <img src="produto2.jpg" alt="Diário de Vida">
        <h2>Diário de Vida</h2>
        <p>Livro artesanal para registrar memórias inesquecíveis.</p>
        <span class="preco">R$ 69,90</span>
        <a href="produto.html">Ver mais</a>
      </div>

      <!-- Adicione mais produtos conforme necessário -->
    </div>
  </main>

  <footer>
    <p>Villa Papel © 2025 · Criado por Sandrinha Fleury</p>
  </footer>
<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Carrinho - Villa Papel</title>
  <link rel="stylesheet" href="estilo.css">
</head>

<body>
  <header>
    <h1>Villa Papel</h1>
    <nav>
      <ul>
        <li><a href="index.html">Início</a></li>
        <li><a href="produtos.html">Produtos</a></li>
        <li><a href="carrinho.html">Carrinho</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <main class="carrinho">
    <h2>Seu Carrinho</h2>
    <table>
      <thead>
        <tr>
          <th>Produto</th>
          <th>Quantidade</th>
          <th>Preço</th>
          <th>Total</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Exemplo de Produto</td>
          <td>1</td>
          <td>R$ 59,90</td>
          <td>R$ 59,90</td>
        </tr>
      </tbody>
    </table>
    <div class="resumo-carrinho">
      <p>Total: <strong>R$ 59,90</strong></p>
      <a href="#" class="btn">Finalizar Compra</a>
    </div>
  </main>

  <footer id="contato">
    <p>Entre em contato: <a href="https://wa.me/5562991000090" target="_blank">WhatsApp (62) 99100-0090</a></p>
    <p>&copy; 2025 Villa Papel - Todos os direitos reservados.</p>
  </footer>
</body>

</html>
