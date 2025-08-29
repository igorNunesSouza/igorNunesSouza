@ -1,55 +1,237 @@
<h1 align="left">Hey, I'm Igor Nunes 👋</h1>

---

<h3 align="left">About Me</h3>

<p align="left">
I’m 21 years old and based in Brazil. I am a Full Stack Developer with experience in PHP, jQuery, and MySQL. Currently, I work in technical support, which gives me direct contact with users and production systems, helping me strengthen my problem-solving, communication, and software maintenance skills.
</p>

---

<h3 align="left">📫 Contact Me</h3>

<div align="left">
  <a href="mailto:Igornunes2j@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-Igornunes2j@gmail.com-D14836?style=flat&logo=gmail&logoColor=white" height="25" alt="Gmail"/>
  </a>
</div>

---

<h3 align="left">💻 Programming Languages & Technologies</h3>

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="30" alt="PHP" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-plain-wordmark.svg" height="30" alt="jQuery" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" height="30" alt="JavaScript" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" height="30" alt="MySQL" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-plain.svg" height="30" alt="Bootstrap" />
</div>

---

<h3 align="left">🚀 Projects</h3>

<ul>
  <li>🌐 <a href="https://igornunes.netlify.app/" target="_blank">Igor Nunes Portfolio</a> – My personal portfolio showcasing my projects and skills. <strong>Technologies:</strong> HTML, CSS, JavaScript, PHP.</li>
  <li>☁️ <a href="https://cloudytempo.netlify.app/" target="_blank">CloudyTempo</a> – A weather app displaying current conditions and forecasts. <strong>Technologies:</strong> HTML, CSS, JavaScript, Weather API.</li>
  <li>⏱️ <a href="https://chronopulsetimer.netlify.app/" target="_blank">ChronoPulse Timer</a> – A timer application designed to track activities accurately. <strong>Technologies:</strong> HTML, CSS, JavaScript.</li>
  <li>⛪ <a href="http://igreja.byethost4.com/?i=2" target="_blank">Church Project</a> – A website developed for a church, demonstrating my experience in PHP, Bootstrap, and web development. <strong>Technologies:</strong> PHP, HTML, CSS, Bootstrap.</li>
</ul>

<!-- <h3 align="left">📊 GitHub Contributions</h3>

<p align="center">
  <!-- <img src="image.png" alt="GitHub contributions graph" /> -->
</p> -->



<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Igor Nunes — Portfolio README</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ccircle cx='50' cy='50' r='48' fill='%2300D1B2'/%3E%3Ctext x='50' y='58' font-size='52' text-anchor='middle' fill='white' font-family='Verdana'%3EI%3C/text%3E%3C/svg%3E">
  <style>
    :root{
      --bg: #0b0d12;
      --panel: #0f131b;
      --muted: #8b93a7;
      --text: #e7ecf3;
      --brand: #6ee7d2;
      --brand-2: #7aa2ff;
      --card: rgba(255,255,255,.04);
      --stroke: rgba(255,255,255,.08);
      --glow: 0 0 0 1px var(--stroke), 0 8px 30px rgba(0,0,0,.35), 0 12px 60px rgba(68, 115, 255, .12);
      --radius: 16px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
      background:
        radial-gradient(1200px 800px at 10% -10%, rgba(110,231,210,.16), transparent 60%),
        radial-gradient(900px 700px at 110% 10%, rgba(122,162,255,.14), transparent 50%),
        linear-gradient(180deg, #0b0d12 0%, #090b10 100%);
      color:var(--text);
      -webkit-font-smoothing:antialiased; text-rendering: optimizeLegibility;
    }
    a{color:inherit; text-decoration:none}
    .container{max-width: 1000px; margin: 0 auto; padding: 32px 20px 80px}

    /* Header */
    .hero{
      margin-top: 8px;
      padding: 28px;
      border-radius: calc(var(--radius) + 6px);
      background: linear-gradient(180deg, rgba(255,255,255,.06) 0%, rgba(255,255,255,.03) 100%);
      border: 1px solid var(--stroke);
      box-shadow: var(--glow);
      position: relative;
      overflow: hidden;
      isolation: isolate;
    }
    .hero::after{
      content:"";
      position:absolute; inset:-1px;
      background: radial-gradient(500px 80px at 10% 0%, rgba(110,231,210,.25), transparent 60%),
                  radial-gradient(600px 120px at 90% 0%, rgba(122,162,255,.25), transparent 60%);
      pointer-events:none; z-index:-1;
      mask: linear-gradient(180deg, rgba(0,0,0,.7), transparent 60%);
    }
    .title{font-size: clamp(28px, 5vw, 42px); font-weight:800; letter-spacing:.2px; margin:0}
    .subtitle{margin:10px 0 0; font-size: clamp(14px, 2.4vw, 18px); color: var(--muted)}

    .hero-actions{margin-top: 18px; display:flex; gap:12px; flex-wrap: wrap}
    .btn{
      display:inline-flex; align-items:center; gap:10px; padding:12px 16px; border-radius: 999px;
      border:1px solid var(--stroke); background:rgba(255,255,255,.03); font-weight:600; transition:.2s ease;
    }
    .btn:hover{transform: translateY(-1px); background: rgba(255,255,255,.06)}
    .btn-primary{ background: linear-gradient(90deg, var(--brand), var(--brand-2)); color:#0b0d12; border-color: transparent }
    .btn-primary:hover{ filter: saturate(1.05) brightness(1.05) }

    /* Sections */
    .section{margin-top: 32px}
    .section h2{font-size: 20px; letter-spacing:.4px; margin:0 0 14px; color:#eaf1ff}
    .section p{color: var(--muted); line-height:1.65; margin:0}

    /* Tech grid */
    .tech-grid{
      display:grid; grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); gap:12px;
    }
    .chip{
      display:flex; align-items:center; gap:10px; padding:12px 14px; border-radius: var(--radius);
      background: var(--card); border:1px solid var(--stroke);
      transition:.2s ease; backdrop-filter: blur(6px);
    }
    .chip:hover{ transform: translateY(-2px); box-shadow: 0 10px 30px rgba(0,0,0,.25) }
    .chip img{ width:22px; height:22px }
    .chip span{ font-weight:600 }

    /* Projects */
    .projects{ display:grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap:16px }
    .card{
      position:relative; padding:18px; border-radius: var(--radius); background: var(--card);
      border:1px solid var(--stroke); transition:.2s ease; overflow:hidden; backdrop-filter: blur(6px);
    }
    .card:hover{ transform: translateY(-3px); box-shadow: var(--glow) }
    .card h3{ margin:0 0 6px; font-size:18px }
    .card p{ margin:0; color: var(--muted) }
    .card .tags{display:flex; flex-wrap:wrap; gap:8px; margin-top:12px}
    .tag{font-size:12px; padding:6px 10px; border:1px solid var(--stroke); border-radius:999px; background:rgba(255,255,255,.03)}
    .card a{position:absolute; inset:0;}

    /* Footer */
    footer{ margin-top: 28px; color: var(--muted); font-size: 13px; text-align:center }

    /* Badge-like contact */
    .badges{ display:flex; gap:10px; flex-wrap:wrap }

    /* Nice underline link */
    .underlink{ position:relative; font-weight:600 }
    .underlink::after{
      content:""; position:absolute; left:0; right:0; bottom:-2px; height:2px;
      background: linear-gradient(90deg, var(--brand), var(--brand-2)); transform: scaleX(.2); transform-origin:left; transition:.25s ease;
    }
    .underlink:hover::after{ transform: scaleX(1) }

    /* Motion */
    @keyframes floaty{ from{ transform: translateY(0) } 50%{ transform: translateY(-6px) } to{ transform: translateY(0) } }
    .float{ animation: floaty 5s ease-in-out infinite }
  </style>
</head>
<body>
  <div class="container">
    <!-- HERO -->
    <header class="hero">
      <h1 class="title">Hey, I'm Igor Nunes 👋</h1>
      <p class="subtitle">21 anos • Brasil • Desenvolvedor Full Stack (PHP • jQuery • MySQL) • atualmente em Suporte Técnico — foco em <strong>resolução de problemas</strong>, <strong>comunicação</strong> e <strong>manutenção de software</strong>.</p>
      <div class="hero-actions">
        <a class="btn btn-primary" href="mailto:Igornunes2j@gmail.com" aria-label="Enviar email">📫 Fale comigo</a>
        <a class="btn" href="#projects">🚀 Ver projetos</a>
      </div>
    </header>

    <!-- ABOUT -->
    <section class="section" id="about">
      <h2>Sobre mim</h2>
      <p>Sou desenvolvedor focado em <strong>stack web</strong> e tenho experiência prática com <strong>PHP</strong>, <strong>jQuery</strong>, <strong>MySQL</strong> e <strong>Bootstrap</strong>. No dia a dia do suporte técnico, tenho contato direto com usuários e sistemas em produção, o que fortalece minha visão de <em>produto</em> e meu cuidado com <em>qualidade</em>, <em>estabilidade</em> e <em>DX</em> (developer experience).</p>
    </section>

    <!-- CONTACT -->
    <section class="section" id="contact">
      <h2>Contato</h2>
      <div class="badges">
        <a class="btn" href="mailto:Igornunes2j@gmail.com">📧 Igornunes2j@gmail.com</a>
      </div>
    </section>

    <!-- TECH -->
    <section class="section" id="tech">
      <h2>💻 Tecnologias</h2>
      <div class="tech-grid">
        <div class="chip">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP"/>
          <span>PHP</span>
        </div>
        <div class="chip">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-plain-wordmark.svg" alt="jQuery"/>
          <span>jQuery</span>
        </div>
        <div class="chip">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript"/>
          <span>JavaScript</span>
        </div>
        <div class="chip">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" alt="MySQL"/>
          <span>MySQL</span>
        </div>
        <div class="chip">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-plain.svg" alt="Bootstrap"/>
          <span>Bootstrap</span>
        </div>
      </div>
    </section>

    <!-- PROJECTS -->
    <section class="section" id="projects">
      <h2>🚀 Projetos</h2>
      <div class="projects">
        <article class="card float">
          <h3>Portfolio – Igor Nunes</h3>
          <p>Meu portfólio com projetos e habilidades.</p>
          <div class="tags">
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
            <span class="tag">JavaScript</span>
            <span class="tag">PHP</span>
          </div>
          <a href="https://igornunes.netlify.app/" target="_blank" rel="noreferrer" aria-label="Ir para o Portfolio de Igor Nunes"></a>
        </article>

        <article class="card">
          <h3>CloudyTempo</h3>
          <p>App de clima com condições atuais e previsão.</p>
          <div class="tags">
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
            <span class="tag">JavaScript</span>
            <span class="tag">Weather API</span>
          </div>
          <a href="https://cloudytempo.netlify.app/" target="_blank" rel="noreferrer" aria-label="Abrir CloudyTempo"></a>
        </article>

        <article class="card">
          <h3>ChronoPulse Timer</h3>
          <p>Timer para acompanhar atividades com precisão.</p>
          <div class="tags">
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
            <span class="tag">JavaScript</span>
          </div>
          <a href="https://chronopulsetimer.netlify.app/" target="_blank" rel="noreferrer" aria-label="Abrir ChronoPulse Timer"></a>
        </article>

        <article class="card">
          <h3>Church Project</h3>
          <p>Website para igreja, destacando experiência em PHP e Bootstrap.</p>
          <div class="tags">
            <span class="tag">PHP</span>
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
            <span class="tag">Bootstrap</span>
          </div>
          <a href="http://igreja.byethost4.com/?i=2" target="_blank" rel="noreferrer" aria-label="Abrir Church Project"></a>
        </article>
      </div>
      <p style="margin-top:14px; color: var(--muted)">Mais detalhes em <a class="underlink" href="https://igornunes.netlify.app/" target="_blank" rel="noreferrer">igornunes.netlify.app</a></p>
    </section>

    <footer>
      <p>© <span id="year"></span> Igor Nunes — feito com HTML + CSS • tema escuro minimalista</p>
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>