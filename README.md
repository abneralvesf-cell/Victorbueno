<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Mídia Kit — Victor Bueno</title>
  <link rel="icon" href="data:;base64,iVBORw0KGgo=">
  <!-- Font Awesome para ícones -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --bg:#0f172a; 
      --card:#1e293b; 
      --accent:#ff6b6b; 
      --accent2:#ffbb33; 
      --muted:#94a3b8;
      --maxw:1100px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    body { 
      margin:0; 
      background:linear-gradient(180deg,#0f172a,#1e293b); 
      color:#f8fafc; 
    }
    .wrap { max-width:var(--maxw); margin:28px auto; padding:20px; }
    .card { 
      background:var(--card); 
      border-radius:16px; 
      box-shadow:0 6px 28px rgba(0,0,0,0.4); 
      padding:24px; 
    }
    header { display:flex; gap:20px; align-items:center; flex-wrap:wrap; }
    .avatar { width:140px; height:140px; border-radius:20px; overflow:hidden; border:4px solid var(--accent); box-shadow:0 6px 20px rgba(0,0,0,0.6); }
    .avatar img { width:100%; height:100%; object-fit:cover; display:block; }
    .hero-info h1 { 
      margin:0; 
      font-size:40px; 
      font-weight:900; 
      background:linear-gradient(90deg,var(--accent),var(--accent2)); 
      -webkit-background-clip:text; 
      color:transparent; 
    }
    .hero-info p { margin:8px 0; color:var(--muted); font-size:16px; }
    .social-links { margin-top:12px; display:flex; gap:14px; flex-wrap:wrap; }
    .social-links a { 
      font-size:20px; 
      color:white; 
      background:var(--accent); 
      width:42px; height:42px; 
      display:flex; 
      align-items:center; 
      justify-content:center; 
      border-radius:50%; 
      box-shadow:0 4px 10px rgba(0,0,0,0.4); 
      transition:0.2s; 
    }
    .social-links a:hover { transform:scale(1.1); background:var(--accent2); }
    .grid { display:grid; grid-template-columns:1fr 340px; gap:20px; margin-top:20px; }
    .section { background:transparent; padding:16px; border-left:4px solid var(--accent); border-radius:10px; margin-bottom:16px; }
    .section h2 { margin-top:0; font-size:20px; color:var(--accent2); }
    .stats { display:flex; gap:12px; flex-wrap:wrap; margin-top:10px; }
    .stat { 
      background:linear-gradient(180deg,#1e293b,#334155); 
      padding:16px; 
      border-radius:12px; 
      flex:1; 
      min-width:140px; 
      text-align:center; 
    }
    .stat h3 { margin:0; font-size:20px; color:var(--accent); }
    .stat p { margin:6px 0 0; color:var(--muted); font-size:14px; }
    .contact { display:flex; flex-direction:column; gap:8px; font-size:15px; }
    .partners { display:grid; grid-template-columns:repeat(auto-fit,minmax(140px,1fr)); gap:20px; margin-top:12px; }
    .partner { 
      background:#334155; 
      border:2px solid var(--accent); 
      border-radius:12px; 
      padding:18px; 
      display:flex; 
      align-items:center; 
      justify-content:center; 
      box-shadow:0 4px 10px rgba(0,0,0,0.4); 
      transition: transform 0.2s ease; 
    }
    .partner:hover { transform:scale(1.05); border-color:var(--accent2); }
    .partner img { max-height:50px; max-width:120px; object-fit:contain; }
    footer { margin-top:20px; color:var(--muted); font-size:13px; text-align:center; }
    button { padding:10px 14px; border-radius:10px; border:0; background:var(--accent); color:white; cursor:pointer; font-weight:600; }
    button.secondary { background:#475569; }
    @media (max-width:920px) { .grid { grid-template-columns:1fr } }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card" id="midiakit">
      <header>
        <div class="avatar">
          <img src="img/perfil.jpg.jpeg" alt="Victor Bueno">
        </div>
        <div class="hero-info">
          <h1>Victor Bueno</h1>
          <p>Criador de conteúdo digital — Lifestyle / Humor</p>
          <div class="social-links">
            <a href="https://www.instagram.com/vixtrbueno/" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="https://www.tiktok.com/@victrbueno" target="_blank"><i class="fab fa-tiktok"></i></a>
            <a href="https://www.facebook.com/victrbuenoo" target="_blank"><i class="fab fa-facebook-f"></i></a>
            <a href="https://www.youtube.com/@VictorBuenovlog" target="_blank"><i class="fab fa-youtube"></i></a>
            <a href="https://wa.me/5511967031938" target="_blank"><i class="fab fa-whatsapp"></i></a>
          </div>
        </div>
      </header>

      <div class="grid">
        <main>
          <section class="section card">
            <h2>Sobre</h2>
            <p>
Victor Bueno, 25 anos, de São Paulo, é um criador de conteúdo autêntico e divertido, reconhecido por compartilhar seu dia a dia com humor, leveza e carisma. Seu objetivo é criar conexões genuínas com o público, transformando situações cotidianas em momentos de entretenimento e inspiração.

<br>Apaixonado pelo universo digital, Victor está sempre explorando formas criativas de engajar e entreter pessoas que valorizam conteúdo espontâneo, real e cheio de personalidade.
            </p>
          </section>

          <section class="section card">
            <h2>Estatísticas</h2>
            <div class="stats">
              <div class="stat"><h3>77,5k</h3><p>Seguidores Instagram</p></div>
              <div class="stat"><h3>162,8k</h3><p>Interações mensais</p></div>
              <div class="stat"><h3>+10k</h3><p>Views em Stories</p></div>
              <div class="stat"><h3>267,8k</h3><p>Seguidores TikTok</p></div>
              <div class="stat"><h3>+9,9M</h3><p>Curtidas no TikTok</p></div>
            </div>
          </section>

          <section class="section card">
            <h2>Estilo & Tipo de Conteúdo</h2>
            <ul>
              <li><strong>Carrosséis & Reels:</strong> humor cotidiano e reflexões espontâneas.</li>
              <li><strong>Autenticidade:</strong> situações reais transformadas em entretenimento leve.</li>
              <li><strong>Lifestyle:</strong> rotina, viagens, bem-estar e humor.</li>
            </ul>
          </section>

          <section class="section card">
            <h2>Público-Alvo</h2>
            <p>Jovens adultos (18–35 anos), interessados em tendências, estilo de vida, humor e entretenimento saudável.</p>
          </section>

          <section class="section card">
            <h2>Matérias</h2>
            <ul>
              <li><a href="https://www.bnews.com.br/amp/noticias/bnews-pet/influencer-volta-julgar-tutores-de-caes-pela-raca-dos-pets-mulher-que-tem-pit-bull-e-piriguete-assista.html" target="_blank">BNews - Julgando tutores pela raça dos pets</a></li>
              <li><a href="https://www.amomeupet.org/noticias/9010/tiktoker-e-39julgae-39-tutores-com-base-na-raca-do-cachorro-que-possuem-videos.amp" target="_blank">Amo Meu Pet - Julgando tutores</a></li>
            </ul>
          </section>

          <section class="section card">
            <h2>Marcas Parceiras</h2>
            <p style="color:var(--muted); margin-bottom:12px">
              Algumas empresas e marcas que já colaboraram com Victor Bueno:
            </p>
            <div class="partners">
              <div class="partner"><img src="logos/playarte.svg" alt="PlayArte Pictures"></div>
              <div class="partner"><img src="logos/magalu.svg" alt="Magalu"></div>
              <div class="partner"><img src="logos/proa.svg" alt="Proa"></div>
              <div class="partner"><img src="logos/snickers.svg" alt="Snickers"></div>
              <div class="partner"><img src="logos/kopenhagen.svg" alt="Kopenhagen"></div>
              <div class="partner"><img src="logos/torra.svg" alt="Torra"></div>
              <div class="partner"><img src="logos/hospital-hari.svg" alt="Hospital Hari"></div>
              <div class="partner"><img src="logos/nitro-circus.svg" alt="Nitro Circus"></div>
            </div>
          </section>
        </main>

        <aside>
          <div class="card">
            <h3>Contato comercial</h3>
            <div class="contact">
              <div><strong>Email:</strong> <a href="mailto:victorbuenocontato@gmail.com">victorbuenocontato@gmail.com</a></div>
              <div><strong>Telefone:</strong> <a href="tel:+5511967031938">(11) 96703-1938</a></div>
              <div><strong>Local:</strong> São Paulo, Brasil</div>
            </div>
            <div style="margin-top:12px">
              <button onclick="window.print()">Baixar / Imprimir</button>
              <a href="https://wa.me/5511967031938" target="_blank" style="text-decoration:none; margin-left:8px">
                <button class="secondary">WhatsApp</button>
              </a>
            </div>
          </div>
        </aside>
      </div>

      <footer>
        <small>Mídia Kit 2025 — Victor Bueno. Atualizado a partir de informações oficiais.</small>
      </footer>
    </div>
  </div>
</body>
</html>
