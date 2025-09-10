
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Tu Nombre — Mycology</title>
  <meta name="description" content="Página personal estilo mycobradshaw.com — biografía, proyectos y publicaciones.">
  <style>
    :root{--bg:#0f1720;--card:#0b1220;--muted:#9aa4b2;--accent:#66d9ef;--maxw:900px}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Arial;background:linear-gradient(180deg,#071021 0%,var(--bg) 100%);color:#e6eef6;line-height:1.5}
    .wrap{max-width:var(--maxw);margin:36px auto;padding:28px}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:140px;height:140px;border-radius:8px;border:2px solid rgba(255,255,255,0.06);background:#08131b;display:flex;align-items:center;justify-content:center;overflow:hidden}
    .avatar img{width:100%;height:100%;object-fit:cover}
    h1{margin:0;font-size:28px}
    h2{margin:6px 0 14px;color:var(--muted);font-weight:600}
    nav{margin-top:8px}
    nav a{color:var(--muted);text-decoration:none;margin-right:14px;font-size:14px}
    .grid{display:grid;grid-template-columns:1fr;gap:22px;margin-top:22px}
    .card{background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .muted{color:var(--muted)}
    .skills{display:flex;gap:8px;flex-wrap:wrap}
    .pill{background:rgba(255,255,255,0.03);padding:8px 10px;border-radius:999px;font-size:13px}
    .projects li{margin-bottom:10px}
    footer{margin-top:26px;color:var(--muted);font-size:13px}
    @media(min-width:900px){.grid{grid-template-columns:2fr 1fr}}
    .links a{display:inline-block;margin-right:10px;text-decoration:none;color:var(--accent)}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar">
        <!-- Sustituye por tu foto: /assets/avatar.jpg -->
        <img src="assets/avatar.jpg" alt="Tu foto">
      </div>
      <div>
        <h1>Tu Nombre <span class="muted">— Mycólogo</span></h1>
        <h2>Postdoctoral Researcher / Taxonomía y Genómica</h2>
        <nav>
          <a href="#about">About</a>
          <a href="#projects">Proyectos</a>
          <a href="#publications">Publicaciones</a>
          <a href="#contact">Contacto</a>
        </nav>
      </div>
    </header>

    <main class="grid">
      <section id="about" class="card">
        <h3>Sobre mí</h3>
        <p class="muted">Breve introducción. Ej: Soy micólogo dedicado a la taxonomía y sistemática del género <em>Psilocybe</em>. Trabajo con colecciones, secuencias ITS y claves morfológicas.</p>
        <p>Redacta aquí 4–6 líneas con tu trayectoria, intereses y centro de trabajo. Añade enlaces a CV o Google Scholar si los tienes.</p>

        <h4>Habilidades clave</h4>
        <div class="skills">
          <span class="pill">Taxonomía</span>
          <span class="pill">Genómica</span>
          <span class="pill">Bioinformática</span>
          <span class="pill">Herbario</span>
        </div>
      </section>

      <aside class="card">
        <h4>Contacto</h4>
        <p class="muted">Correo:</p>
        <p><a class="links" href="mailto:tu@email.com">tu@email.com</a></p>
        <p class="muted">Ubicación:</p>
        <p>Medellín, Colombia</p>
        <p class="muted">CV:</p>
        <p><a class="links" href="#">Descargar CV (PDF)</a></p>
      </aside>

      <section id="projects" class="card">
        <h3>Proyectos destacados</h3>
        <ul class="projects">
          <li><strong>Revisión taxonómica de <em>Psilocybe</em></strong> — Resumen corto y link a la página del proyecto o repo.</li>
          <li><strong>Herbario digital</strong> — Indexación y digitalización de tipos.</li>
          <li><strong>Claves interactivas</strong> — Herramienta para identificación morfológica.</li>
        </ul>
      </section>

      <section id="publications" class="card">
        <h3>Publicaciones seleccionadas</h3>
        <ol>
          <li>Apellido et al. (2024). Título. <em>Journal</em>. <a class="links" href="#">DOI</a></li>
          <li>Apellido et al. (2023). Título. <em>Journal</em>. <a class="links" href="#">PDF</a></li>
        </ol>
      </section>

      <section id="contact" class="card">
        <h3>Contacto y redes</h3>
        <p class="muted">Enlaces:</p>
        <p class="links"><a href="#">GitHub</a> · <a href="#">Google Scholar</a> · <a href="#">LinkedIn</a></p>
      </section>

    </main>

    <footer>
      <p>&copy; <!-- Año actual se puede actualizar --> 2025 — Tu Nombre. Diseño inspirado en sitios académicos de micología.</p>
    </footer>
  </div>
</body>
</html>
