
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Investidor Fundamentalista</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css"/>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0c0f1f;
      color: #ffffff;
      background-image: url("Logo%20(8).png");
      background-repeat: no-repeat;
      background-size: cover;
      background-position: center;
    }
    header {
      text-align: center;
      padding: 60px 20px 40px;
    }
    header img {
      max-width: 180px;
      height: auto;
      display: block;
      margin: 0 auto 20px;
    }
    h1 {
      font-size: 36px;
      color: #ffffff;
    }
    p.highlight {
      font-size: 18px;
      margin: 20px 0 40px;
      max-width: 700px;
      margin-left: auto;
      margin-right: auto;
    }
    .cta-buttons {
      display: flex;
      flex-direction: column;
      gap: 20px;
      align-items: center;
      justify-content: center;
      margin-bottom: 40px;
    }
    .cta-buttons a {
      padding: 16px 32px;
      text-decoration: none;
      color: #fff;
      background-color: #1eb980;
      border-radius: 8px;
      font-size: 16px;
      font-weight: bold;
      transition: background-color 0.3s;
    }
    .cta-buttons a.secondary {
      background-color: #444;
    }
    .cta-buttons a:hover {
      background-color: #17a36e;
    }
    .form-section {
      max-width: 600px;
      margin: auto;
      background-color: #1c1f2e;
      padding: 40px;
      border-radius: 12px;
      text-align: center;
    }
    .form-section input[type="email"] {
      width: 100%;
      padding: 14px;
      margin-bottom: 20px;
      border: none;
      border-radius: 8px;
      font-size: 16px;
    }
    .form-section button {
      width: 100%;
      padding: 14px;
      font-size: 16px;
      font-weight: bold;
      background-color: #1eb980;
      border: none;
      color: #fff;
      border-radius: 8px;
      cursor: pointer;
    }
    .form-section button:hover {
      background-color: #17a36e;
    }
    .download-counter {
      font-size: 18px;
      color: #1eb980;
      text-align: center;
      margin-top: 20px;
    }
    #testimonials {
      padding: 60px 20px;
      text-align: center;
    }
    #testimonials_header h1,
    #testimonials_header h2,
    #testimonials_header p {
      margin-bottom: 10px;
    }
    .testimonial-rate i {
      color: #f5b301;
    }
    .testimonial-quote {
      font-style: italic;
      margin: 20px 0;
    }
    .testimonial-author {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 15px;
    }
    .testimonial-author img {
      width: 50px;
      height: 50px;
      border-radius: 50%;
    }
    .swiper-button-prev,
    .swiper-button-next {
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <img src="Logo%20(8).png" alt="Investidor Inteligente logo">
    <h1>Investidor Fundamentalista</h1>
    <p class="highlight">Faça parte dos brasileiros que prosperam em meio à adversidade por meio do mercado de ações.</p>
  </header>

  <div class="cta-buttons">
    <a href="#form">Garantir minha vaga</a>
    <a class="secondary" href="https://wa.me/5585974017237" target="_blank">Falar com consultor</a>
  </div>

  <div class="form-section" id="form">
    <h2>📘 Baixe o eBook + Planilha</h2>
    <p>Receba agora gratuitamente o guia "Comece a Investir com Inteligência" e uma planilha prática para organizar sua vida financeira.</p>
    <form action="https://seu-serviço-de-email.com/subscribe" method="POST">
      <input type="email" name="email" placeholder="Digite seu melhor e-mail" required>
      <button type="submit">Quero Receber Agora</button>
    </form>
    <div class="download-counter">
      📥 Mais de <span id="downloadCount">12.482</span> pessoas já baixaram!
    </div>
  </div>

  <main id="testimonials">
    <div id="testimonials_header">
      <h1>Avaliações</h1>
      <h2>O que os clientes dizem</h2>
      <p>Quer saber o que torna a nossa marca tão especial? Confira o que nossos clientes têm a dizer!</p>
    </div>

    <div class="swiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
          <div class="testimonial-rate">
            <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
          </div>
          <blockquote class="testimonial-quote">"Experiência incrível! Desde o primeiro contato, fui muito bem atendido e recebi todas as informações de forma clara. Recomendo para todos!"</blockquote>
          <div class="testimonial-author">
            <img src="src/images/avatar1.jpg" alt="Imagem de uma pessoa">
            <div class="author-info">
              <h3>Fulano de Tal</h3>
              <p>Cliente desde 2020</p>
            </div>
          </div>
        </div>
        <div class="swiper-slide">
          <div class="testimonial-rate">
            <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
          </div>
          <blockquote class="testimonial-quote">"Experiência incrível! Desde o primeiro contato, fui muito bem atendido e recebi todas as informações de forma clara. Recomendo para todos!"</blockquote>
          <div class="testimonial-author">
            <img src="src/images/avatar2.jpg" alt="Imagem de uma pessoa">
            <div class="author-info">
              <h3>Fulano de Tal</h3>
              <p>Cliente desde 2020</p>
            </div>
          </div>
        </div>
        <div class="swiper-slide">
          <div class="testimonial-rate">
            <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
          </div>
          <blockquote class="testimonial-quote">"Experiência incrível! Desde o primeiro contato, fui muito bem atendido e recebi todas as informações de forma clara. Recomendo para todos!"</blockquote>
          <div class="testimonial-author">
            <img src="src/images/avatar3.jpg" alt="Imagem de uma pessoa">
            <div class="author-info">
              <h3>Fulano de Tal</h3>
              <p>Cliente desde 2020</p>
            </div>
          </div>
        </div>
      </div>
      <div class="swiper-pagination"></div>
      <div class="swiper-button-prev"></div>
      <div class="swiper-button-next"></div>
    </div>
  </main>

  <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
  <script>
    let count = 12482;
    setInterval(() => {
      count += Math.floor(Math.random() * 3);
      document.getElementById("downloadCount").textContent = count.toLocaleString("pt-BR");
    }, 4000);

    const swiper = new Swiper('.swiper', {
      loop: true,
      pagination: {
        el: '.swiper-pagination',
        clickable: true,
      },
      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
      },
      autoplay: {
        delay: 5000,
        disableOnInteraction: false,
      },
      slidesPerView: 1,
      spaceBetween: 30,
      breakpoints: {
        768: {
          slidesPerView: 2
        },
        1024: {
          slidesPerView: 3
        }
      }
    });
  </script>
</body>
</html>
