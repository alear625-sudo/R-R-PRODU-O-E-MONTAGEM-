<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>R & R — Móveis Planejados</title>
  <style>
    :root{--accent:#8b5e3c;--muted:#666;--bg:#f7f5f2;--card:#fff}
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; margin:0;background:var(--bg);color:#222}
    .container{max-width:1000px;margin:28px auto;padding:20px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{font-weight:700;font-size:22px;color:var(--accent)}
    .subtitle{font-size:14px;color:var(--muted)}
    .hero{background:linear-gradient(180deg,rgba(139,94,60,0.06),transparent);padding:18px;border-radius:12px;margin-top:14px}
    .cta{display:inline-block;background:var(--accent);color:#fff;padding:10px 14px;border-radius:8px;text-decoration:none;font-weight:600}
    section{margin-top:22px}
    h2{margin:6px 0 12px 0}
    .services{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
    .card{background:var(--card);padding:14px;border-radius:10px;box-shadow:0 6px 18px rgba(30,30,30,0.06)}
    .service-title{font-weight:700;margin-bottom:8px}
    .gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:10px}
    .gallery img{width:100%;height:120px;object-fit:cover;border-radius:8px;display:block}
    .contact{display:flex;flex-wrap:wrap;gap:10px;align-items:center}
    .whatsapp{display:inline-flex;align-items:center;gap:8px;padding:10px 12px;border-radius:8px;background:#25D366;color:#fff;text-decoration:none;font-weight:700}
    .meta{color:var(--muted);font-size:14px}
    .testimonials{display:flex;flex-direction:column;gap:8px}
    .testimonial{background:#fff;padding:12px;border-radius:8px;border-left:4px solid var(--accent)}
    footer{margin-top:28px;text-align:center;color:var(--muted);font-size:13px}
    @media (max-width:420px){.brand{font-size:18px}.hero{padding:12px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div>
        <div class="brand">R &amp; R Marcenaria</div>
        <div class="subtitle">Fabricação e Montagem de móveis planejados</div>
      </div>
      <div>
        <a class="cta" href="#contato">Chamar no WhatsApp</a>
      </div>
    </header>

    <div class="hero">
      <h1>Qualidade, acabamento e móveis sob medida</h1>
      <p class="meta">Atendemos em São Paulo com projetos personalizados e montagem profissional.</p>
    </div>

    <section id="servicos">
      <h2>🧱 Nossos Serviços</h2>
      <div class="services">
        <div class="card">
          <div class="service-title">Móveis planejados sob medida</div>
          <div class="meta">Projetados especialmente para o seu espaço, com acabamento profissional e materiais de qualidade.</div>
        </div>

        <div class="card">
          <div class="service-title">Montagem com uma equipe especializada</div>
          <div class="meta">Equipe treinada e com cuidado no transporte, montagem e acabamento final.</div>
        </div>

        <div class="card">
          <div class="service-title">Atendimento em domicílio</div>
          <div class="meta">Medições, orçamento e apresentação de propostas no local — tudo para sua comodidade.</div>
        </div>
      </div>
    </section>

    <section id="galeria">
      <h2>🖼️ Galeria</h2>
      <p class="meta">Substitua as imagens abaixo pelas fotos dos seus trabalhos.</p>
      <div class="gallery">
        <img src="" alt="Cozinha planejada">
        <img src="images/guarda-roupa.jpg" alt="Guarda-roupa planejado">
        <img src="images/painel-tv.jpg" alt="Painel de TV">
        <img src="images/escritorio.jpg" alt="Escritório planejado">
        <img src="images/lavanderia.jpg" alt="Área de serviço">
        <img src="images/outro.jpg" alt="Outro móvel">
      </div>
    </section>

    <section id="contato">
      <h2>📞 Contato</h2>
      <div class="card contact">
        <div>
          <div class="meta">Telefone / WhatsApp</div>
          <div style="font-weight:700;margin-top:6px">(11) 99160-2544</div>
        </div>

        <div>
          <div class="meta">Instagram</div>
          <div style="font-weight:700;margin-top:6px">R&amp;R</div>
        </div>

        <div>
          <div class="meta">Cidade</div>
          <div style="font-weight:700;margin-top:6px">São Paulo</div>
        </div>

        <div style="margin-left:auto">
          <!-- Link para abrir conversa no WhatsApp. Substitua o número se precisar -->
          <a class="whatsapp" href="https://wa.me/5511991602544?text=Ol%C3%A1%20R%20%26%20R%20Marcenaria%2C%20gostaria%20de%20um%20or%C3%A7amento" target="_blank" rel="noopener">Chamar no WhatsApp</a>
        </div>
      </div>
    </section>

    <section id="depoimentos">
      <h2>⭐ Depoimentos</h2>
      <div class="testimonials">
        <div class="testimonial">"Excelente trabalho!"</div>
        <div class="testimonial">"Acabamento impecável."</div>
        <div class="testimonial">"Ótimo atendimento e entrega no prazo!"</div>
      </div>
    </section>

    <footer>
      © <span id="year"></span> R &amp; R Marcenaria — Todos os direitos reservados.
    </footer>
  </div>

  <script>
    // atualiza o ano no rodapé
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
