<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Surpreet Kaur</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0a0b0f; --card:#11131a; --muted:#a7b0be; --text:#e7eaf0; --border:#1b1f2a;
      --accent:#6ee7f9; --accent2:#a78bfa;
    }
    *{box-sizing:border-box}
    html,body{margin:0;background:var(--bg);color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif}
    a{color:inherit;text-decoration:none}
    .wrap{max-width:980px;margin:0 auto;padding:28px}
    .hero{padding:40px 0;border-bottom:1px solid var(--border);
      background:
        radial-gradient(900px 300px at 10% -10%, rgba(108,99,255,.18) 0%, transparent 60%),
        radial-gradient(900px 300px at 100% 0%, rgba(0,255,255,.12) 0%, transparent 60%);
    }
    .row{display:grid;grid-template-columns:140px 1fr;gap:22px;align-items:center}
    @media(max-width:700px){.row{grid-template-columns:1fr;text-align:center}}
    .pfp{width:140px;height:140px;border-radius:50%;border:1px solid var(--border);object-fit:cover;box-shadow:0 10px 30px rgba(0,0,0,.45)}
    h1{font-size:34px;letter-spacing:.3px;margin:0 0 6px;font-weight:800}
    .tag{color:var(--muted);margin:0 0 18px}
    .icons{display:flex;gap:10px;flex-wrap:wrap}
    .btn{display:inline-flex;align-items:center;gap:10px;padding:10px 14px;border-radius:12px;border:1px solid var(--border);background:var(--card)}
    .btn.primary{background:linear-gradient(135deg,var(--accent),var(--accent2));color:#0a0b0f;border:none;font-weight:700}
    .spacer{height:8px}
    section{padding:34px 0;border-bottom:1px solid var(--border)}
    h2{margin:0 0 12px;font-size:20px}
    p{margin:0 0 12px}
    .list{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
    @media(max-width:850px){.list{grid-template-columns:repeat(2,1fr)}}
    @media(max-width:560px){.list{grid-template-columns:1fr}}
    .pill{background:var(--card);border:1px solid var(--border);border-radius:999px;padding:9px 12px;color:#d5d9e3}
    footer{padding:26px 0;color:var(--muted);text-align:center}
    .muted{color:var(--muted)}
    /* inline icons */
    .icon{width:18px;height:18px;display:inline-block;vertical-align:-3px;opacity:.95}
  </style>
</head>
<body>
  <header class="hero">
    <div class="wrap">
      <div class="row">
        <img class="pfp" src="headshot.jpg" alt="Surpreet Kaur headshot" />
        <div>
          <h1>Surpreet Kaur</h1>
          <p class="tag">CS & CE @ USC • AI Applications Minor — building human-centered systems across AI, edge, and fintech.</p>
          <div class="icons">
            <a class="btn" href="mailto:surpreet.kaur.pro@gmail.com" aria-label="Email">
              <svg class="icon" viewBox="0 0 24 24" fill="currentColor"><path d="M2 6a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6zm2 .4V18h16V6.4l-8 5.2-8-5.2zm8 3.2L20 6H4l8 3.6z"/></svg>
              Email
            </a>
            <a class="btn" href="https://www.linkedin.com/in/surpr33t" target="_blank" rel="noopener" aria-label="LinkedIn">
              <svg class="icon" viewBox="0 0 24 24" fill="currentColor"><path d="M4.98 3.5C4.98 4.88 3.86 6 2.5 6S0 4.88 0 3.5 1.12 1 2.5 1s2.48 1.12 2.48 2.5zM.5 8.5h4V23h-4V8.5zM8.5 8.5h3.8v2h.05c.53-1 1.82-2.05 3.75-2.05 4.01 0 4.75 2.64 4.75 6.08V23h-4v-6.5c0-1.55-.03-3.55-2.17-3.55-2.17 0-2.5 1.7-2.5 3.44V23h-3.8V8.5z"/></svg>
              LinkedIn
            </a>
            <a class="btn" href="https://github.com/surpr33t" target="_blank" rel="noopener" aria-label="GitHub">
              <svg class="icon" viewBox="0 0 24 24" fill="currentColor"><path d="M12 .5a12 12 0 0 0-3.79 23.4c.6.11.82-.26.82-.58v-2.24c-3.34.73-4.04-1.61-4.04-1.61-.55-1.4-1.34-1.77-1.34-1.77-1.09-.75.08-.74.08-.74 1.2.08 1.84 1.22 1.84 1.22 1.07 1.84 2.8 1.31 3.48 1 .11-.78.42-1.31.76-1.61-2.67-.3-5.48-1.34-5.48-5.95 0-1.31.47-2.38 1.24-3.22-.12-.3-.54-1.52.12-3.17 0 0 1.01-.32 3.3 1.23a11.5 11.5 0 0 1 6 0c2.28-1.55 3.29-1.23 3.29-1.23.66 1.65.24 2.87.12 3.17.77.84 1.23 1.91 1.23 3.22 0 4.62-2.81 5.64-5.49 5.94.43.37.81 1.1.81 2.22v3.29c0 .32.21.7.82.58A12 12 0 0 0 12 .5z"/></svg>
              GitHub
            </a>
            <a class="btn primary" href="resume.pdf" target="_blank" rel="noopener">Download Resume</a>
          </div>
        </div>
      </div>
    </div>
  </header>

  <main class="wrap">
    <section aria-labelledby="bio">
      <h2 id="bio">About</h2>
      <p>
        I didn’t wait to grow up—life handed me responsibility early. I started school at two weeks old and learned to adapt,
        observe, and figure things out fast. That mindset is why I study Computer Engineering and Computer Science with a minor in AI at USC.
      </p>
      <p>
        I’m into building systems that make sense of complexity—whether that’s edge computing, quantum algorithms,
        or AI tools that respond to real human needs. I’ve worked across labs, startups, and public institutions with the same approach:
        solve the problem, keep it real, make it meaningful.
      </p>
    </section>

    <section aria-labelledby="skills">
      <h2 id="skills">Skills</h2>
      <div class="list">
        <div class="pill">Python</div>
        <div class="pill">C++ / C</div>
        <div class="pill">JavaScript / TypeScript</div>
        <div class="pill">React</div>
        <div class="pill">TensorFlow / PyTorch</div>
        <div class="pill">OpenCV / DeepFace</div>
        <div class="pill">Flask</div>
        <div class="pill">SQL</div>
        <div class="pill">Linux / Git</div>
        <div class="pill">Docker</div>
        <div class="pill">Kubernetes</div>
        <div class="pill">Apache Airflow</div>
        <div class="pill">Edge / SAGA</div>
        <div class="pill">RPi / Arduino</div>
        <div class="pill">GCP (basics)</div>
      </div>
      <p class="muted">Coursework: SWE, AI/ML, Embedded & Digital Systems, Probability/Statistics, Algorithms, Computer Architecture.</p>
    </section>

    <section aria-labelledby="projects">
      <h2 id="projects">Projects</h2>
      <p class="muted">I keep everything on GitHub. Browse them all here:</p>
      <div class="spacer"></div>
      <a class="btn" href="https://github.com/surpr33t?tab=repositories" target="_blank" rel="noopener">
        Browse all projects on GitHub →
      </a>
    </section>

    <section id="contact" aria-labelledby="contact-title">
      <h2 id="contact-title">Contact</h2>
      <p>Email: <a href="mailto:surpreet.kaur.pro@gmail.com">surpreet.kaur.pro@gmail.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/surpr33t" target="_blank" rel="noopener">linkedin.com/in/surpr33t</a></p>
      <p>GitHub: <a href="https://github.com/surpr33t" target="_blank" rel="noopener">github.com/surpr33t</a></p>
    </section>
  </main>

  <footer>© 2025 Surpreet Kaur</footer>
</body>
</html>

