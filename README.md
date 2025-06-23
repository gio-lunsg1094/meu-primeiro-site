# meu-primeiro-site
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Meu Primeiro Site</title>
  <link rel="stylesheet" href="estilo.css"> <!-- futuramente para estilizar -->
</head>
<body>

  <!-- Cabeçalho com menu de navegação -->
  <header>
    <h1>Mundo dos Nerds de Musicais</h1>
    <nav>
      <ul>
        <li><a href="#">Início</a></li>
        <li><a href="#">Sobre nós</a></li>
        <li><a href="#">Serviços</a></li>
        <li><a href="#">Contato</a></li>
        <li><a href="#" class="botao-destaque">Matricule-se já!</a></li>
      </ul>
    </nav>
  </header>

  <!-- Conteúdo principal da página -->
  <main>
    <h2>Bem-vindo ao nosso site!</h2>
    <p>Seja bem vindo! Este é um site para se sentir em casa e se divertir com tudo que vc queira saber sobre o universo dos musicais.</p>
    <img src="<img src="imagem wicked Brasil.jpg" alt="imagem do musical de Wicked">
" alt="Imagem principal do site" width="500">
  </main>

/* ---------- Estilo geral da página ---------- */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: #f4f8fc; /* Cor de fundo clara e agradável */
  font-family: 'Arial', sans-serif;
  color: #333;
  line-height: 1.6;
  padding: 20px;
}

/* ---------- Títulos ---------- */
h1, h2 {
  color: #222;
  margin-bottom: 20px;
}

h1 {
  text-align: center;
}

/* ---------- Parágrafos ---------- */
p {
  font-size: 16px;
  margin-bottom: 15px;
}

/* ---------- Menu de navegação ---------- */
nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
  justify-content: flex-end;
  align-items: center;
  background-color: #ffffff;
  padding: 15px 30px;
  border-bottom: 2px solid #ddd;
}

nav a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}

/* ---------- Botão de destaque ---------- */
.botao-destaque {
  background-color: #007BFF;
  color: white;
  padding: 8px 16px;
  border-radius: 5px;
}

.botao-destaque:hover {
  background-color: #0056b3;
}

  <!-- Rodapé com informações finais -->
  <footer>
    <p>© 2025 - Meu Site. Todos os direitos reservados.</p>
    <p>Redes sociais: Facebook | Instagram | WhatsApp</p>
  </footer>
