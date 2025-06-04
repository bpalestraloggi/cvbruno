# cvbruno
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Master CV - Bruno Abbatepaulo do Prado</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css" />
  </head>
  <body>
    <nav class="container-fluid">
      <ul>
        <li><strong>Master CV – Bruno Abbatepaulo do Prado</strong></li>
      </ul>
      <ul>
        <li><a href="#sobre">Sobre mim</a></li>
        <li><a href="#projetos">Projetos</a></li>
        <li><a href="#contato" role="button">Contato</a></li>
      </ul>
    </nav>

    <main class="container">
      <div class="grid">
        <section>
          <hgroup>
            <h2>Master CV<br>Bruno Abbatepaulo do Prado</h2>
            <h3>💡 Construindo resultados através de estratégia, vendas e relacionamentos de valor.</h3>
          </hgroup>
          <p>Executivo de Vendas com +12 anos de experiência em contas Enterprise, estruturação de áreas comerciais e liderança de squads de alta performance.</p>
          <figure>
            <img src="https://images.unsplash.com/photo-1603415526960-f7e0328f035d?fit=crop&w=800&q=80" alt="Bruno Abbatepaulo do Prado" />
            <figcaption>Foto ilustrativa - executivo profissional (Unsplash)</figcaption>
          </figure>

          <h3 id="sobre">Sobre mim</h3>
          <p>Sou Bruno Abbatepaulo do Prado. Atuei desde a linha de frente comercial até a construção de estruturas comerciais robustas, sempre guiado por cultura, dados e relacionamento de confiança.</p>

          <h3 id="projetos">Projeto em destaque</h3>
          <p>💬 <strong>Chatbot - Loggi Ajuda</strong><br>
          Assistente virtual treinado para auxiliar em questões de logística. Baseado em IA, criado com foco em atendimento inteligente e rápido.</p>
          <p><a href="https://chatgpt.com/g/g-683f66b668bc8191a65c97fa82fae46e-loggi-ajuda" target="_blank">Acessar Chatbot</a></p>
        </section>
      </div>
    </main>

    <section aria-label="Subscribe example">
      <div class="container">
        <article>
          <hgroup>
            <h2 id="contato">Entre em contato</h2>
            <h3>Fique à vontade para me chamar</h3>
          </hgroup>
          <form class="grid">
            <input type="text" id="firstname" name="firstname" placeholder="Seu nome" aria-label="Seu nome" required />
            <input type="email" id="email" name="email" placeholder="Seu e-mail" aria-label="Seu e-mail" required />
            <button type="submit" onclick="event.preventDefault()">Enviar mensagem</button>
          </form>
        </article>
      </div>
    </section>

    <footer class="container">
      <small><a href="#">LinkedIn</a> • <a href="https://github.com/">GitHub</a></small>
    </footer>
  </body>
</html>