<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Surpreet Kaur — CS & CE @ USC</title>
  <meta name="description" content="Surpreet Kaur — USC CS & CE (AI Apps minor). I build human‑centered systems across AI, edge computing, and fintech." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    :root { color-scheme: dark; }
    html { scroll-behavior: smooth; }
    body { font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans", "Apple Color Emoji", "Segoe UI Emoji"; }
    /* --- Subtle animated background --- */
    .bg-grid {
      position: fixed; inset: 0; z-index: -2;
      background: radial-gradient(1200px 600px at 10% -10%, rgba(126, 34, 206, .25), transparent 60%),
                  radial-gradient(1000px 600px at 100% 0%, rgba(59, 130, 246, .25), transparent 60%),
                  radial-gradient(800px 500px at 50% 100%, rgba(16, 185, 129, .22), transparent 60%),
                  #000; /* base */
    }
    .bg-noise { /* ultra subtle film grain */
      position: fixed; inset: 0; z-index: -1; pointer-events: none; opacity:.09; mix-blend-mode: soft-light;
      background-image: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAgAAAAICAYAAADED76LAAAAHUlEQVQYV2NkYGD4z0AeYBQjAwMDA0MGQ4aRAQAAjE4JfQ1y2fQAAAAASUVORK5CYII=');
      background-size: 8px 8px;
    }
    .glass { background: rgba(255,255,255,0.05); backdrop-filter: blur(12px); border: 1px solid rgba(255,255,255,.08); }
    .tag { border: 1px solid rgba(255,255,255,.1); background: rgba(255,255,255,.03) }
    .hover-raise { transition: transform .25s ease, box-shadow .25s ease; }
    .hover-raise:hover { transform: translateY(-4px); box-shadow: 0 10px 30px rgba(0,0,0,.35), inset 0 0 0 1px rgba(255,255,255,.08); }
    /* buttons */
    .btn { display:inline-flex; align-items:center; gap:.5rem; border-radius:999px; padding:.7rem 1rem; font-weight:600; }
    .btn-primary { background: linear-gradient(135deg,#7c3aed,#2563eb); }
    .btn-outline { border:1px solid rgba(255,255,255,.14); background: rgba(255,255,255,.02); }
    .btn:hover { filter: brightness(1.05); }
    /* section spacing */
    section { padding-top: 5rem; padding-bottom: 5rem; }
  </style>
</head>
<body class="text-zinc-100 bg-black">
  <div class="bg-grid"></div>
  <div class="bg-noise"></div>

  <!-- NAV -->
  <header class="fixed top-0 inset-x-0 z-30">
    <div class="mx-auto max-w-6xl px-4">
      <div class="mt-4 glass rounded-2xl px-4 py-3 flex items-center justify-between">
        <a href="#top" class="font-semibold tracking-tight">Surpreet Kaur</a>
        <nav class="hidden md:flex items-center gap-6 text-sm text-zinc-300">
          <a class="hover:text-white" href="#projects">Projects</a>
          <a class="hover:text-white" href="#skills">Skills</a>
          <a class="hover:text-white" href="#experience">Experience</a>
          <a class="hover:text-white" href="#contact">Contact</a>
        </nav>
        <div class="flex items-center gap-2">
          <a class="btn btn-outline" href="/Surpreet%20Kaur%20%7C%20Resume.pdf" download>Resume</a>
          <a class="btn btn-primary" href="#contact">Say hi</a>
        </div>
      </div>
    </div>
  </header>

  <!-- HERO -->
  <main id="top" class="mx-auto max-w-6xl px-4 pt-28">
    <section class="grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h1 class="text-4xl sm:text-5xl font-extrabold leading-tight">
          CS & CE @ USC · <span class="text-zinc-300 font-semibold">AI Applications Minor</span>
        </h1>
        <p class="mt-5 text-lg text-zinc-300 max-w-xl">
          I build <span class="font-semibold text-white">human‑centered systems</span> at the edge—where AI, distributed systems, and fintech meet. Currently integrating <span class="font-semibold text-white">SAGA ↔ Airflow</span> for edge scheduling, exploring network reconnaissance with ML, and prototyping emotion‑aware interfaces.
        </p>
        <div class="mt-6 flex flex-wrap gap-2">
          <span class="tag px-3 py-1 rounded-full text-sm">Python</span>
          <span class="tag px-3 py-1 rounded-full text-sm">C++</span>
          <span class="tag px-3 py-1 rounded-full text-sm">Edge</span>
          <span class="tag px-3 py-1 rounded-full text-sm">Kubernetes</span>
          <span class="tag px-3 py-1 rounded-full text-sm">Airflow</span>
          <span class="tag px-3 py-1 rounded-full text-sm">PyTorch</span>
          <span class="tag px-3 py-1 rounded-full text-sm">Qiskit</span>
          <span class="tag px-3 py-1 rounded-full text-sm">Fintech</span>
        </div>
        <div class="mt-7 flex items-center gap-3">
          <a class="btn btn-primary" href="#projects">See projects</a>
          <a class="btn btn-outline" href="https://www.linkedin.com/in/surpr33t" target="_blank" rel="noopener" aria-label="LinkedIn">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor" class="opacity-90"><path d="M4.98 3.5C4.98 4.88 3.86 6 2.5 6S0 4.88 0 3.5 1.12 1 2.5 1s2.48 1.12 2.48 2.5zM.5 8h4V24h-4V8zm7 0h3.8v2.2h.1c.5-1 1.8-2.2 3.7-2.2 4 0 4.8 2.6 4.8 6V24h-4v-7c0-1.7 0-3.9-2.4-3.9-2.4 0-2.8 1.8-2.8 3.8V24h-4V8z"/></svg>
            LinkedIn
          </a>
          <a class="btn btn-outline" href="https://github.com/surpr33t" target="_blank" rel="noopener" aria-label="GitHub">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor" class="opacity-90"><path d="M12 .5C5.73.5.98 5.24.98 11.5c0 4.86 3.15 8.98 7.51 10.43.55.1.75-.24.75-.53v-1.9c-3.05.66-3.7-1.47-3.7-1.47-.5-1.27-1.22-1.6-1.22-1.6-.99-.67.07-.66.07-.66 1.1.08 1.68 1.14 1.68 1.14.97 1.67 2.56 1.19 3.18.9.1-.71.38-1.19.69-1.46-2.43-.28-4.99-1.21-4.99-5.4 0-1.19.43-2.16 1.14-2.92-.11-.28-.49-1.4.11-2.92 0 0 .92-.29 3.01 1.12.87-.24 1.8-.35 2.73-.36.93 0 1.86.12 2.73.36 2.09-1.41 3.01-1.12 3.01-1.12.59 1.52.22 2.64.11 2.92.71.76 1.14 1.73 1.14 2.92 0 4.2-2.57 5.12-5.01 5.39.39.34.74 1.01.74 2.04v3.02c0 .29.19.64.76.53 4.35-1.45 7.5-5.56 7.5-10.42C23.02 5.24 18.27.5 12 .5z"/></svg>
            GitHub
          </a>
        </div>
      </div>
      <div class="w-full">
        <div class="glass rounded-3xl p-6 md:p-8 hover-raise">
          <h3 class="text-xl font-semibold mb-3">Quick Snapshot</h3>
          <div class="grid grid-cols-2 gap-3 text-sm text-zinc-300">
            <div class="glass rounded-2xl p-4">
              <div class="text-zinc-400 text-xs">Current</div>
              <div class="font-semibold">CS/CE + AI minor</div>
            </div>
            <div class="glass rounded-2xl p-4">
              <div class="text-zinc-400 text-xs">Focus</div>
              <div class="font-semibold">AI • Edge • Fintech</div>
            </div>
            <div class="glass rounded-2xl p-4">
              <div class="text-zinc-400 text-xs">Seeking</div>
              <div class="font-semibold">Summer 2026 SWE</div>
            </div>
            <div class="glass rounded-2xl p-4">
              <div class="text-zinc-400 text-xs">Location</div>
              <div class="font-semibold">Los Angeles, CA</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- PROJECTS -->
    <section id="projects">
      <div class="flex items-center justify-between mb-6">
        <h2 class="text-2xl font-bold">Selected Projects</h2>
        <a href="https://github.com/surpr33t?tab=repositories" target="_blank" class="text-sm text-zinc-300 hover:text-white">All repos →</a>
      </div>
      <div class="grid md:grid-cols-3 gap-6">
        <a class="glass rounded-3xl p-5 hover-raise block" href="https://github.com/surpr33t/spotify-mood-player" target="_blank">
          <div class="text-sm text-zinc-400">Python • Flask • CV/ML</div>
          <div class="mt-1 font-semibold">Emotion‑Aware Music Player</div>
          <p class="mt-2 text-sm text-zinc-300">Detects user emotion and maps it to Spotify playlists; built with DeepFace and OpenCV.</p>
        </a>
        <a class="glass rounded-3xl p-5 hover-raise block" href="#" target="_blank">
          <div class="text-sm text-zinc-400">C • AVR • Arduino</div>
          <div class="mt-1 font-semibold">Edge Computing Toolkit</div>
          <p class="mt-2 text-sm text-zinc-300">Lightweight pipeline for on‑device sensor processing; designed for low‑latency inference.</p>
        </a>
        <a class="glass rounded-3xl p-5 hover-raise block" href="#" target="_blank">
          <div class="text-sm text-zinc-400">Qiskit • Cirq</div>
          <div class="mt-1 font-semibold">Quantum Algorithms Notes</div>
          <p class="mt-2 text-sm text-zinc-300">Explorations of amplitude amplification and toy circuits; benchmarking intuition‑first.</p>
        </a>
      </div>
    </section>

    <!-- SKILLS (lean) -->
    <section id="skills">
      <h2 class="text-2xl font-bold mb-6">Skills</h2>
      <div class="glass rounded-3xl p-6">
        <div class="flex flex-wrap gap-2 text-sm">
          <span class="tag px-3 py-1 rounded-full">C++</span>
          <span class="tag px-3 py-1 rounded-full">C</span>
          <span class="tag px-3 py-1 rounded-full">Python</span>
          <span class="tag px-3 py-1 rounded-full">Java</span>
          <span class="tag px-3 py-1 rounded-full">SQL</span>
          <span class="tag px-3 py-1 rounded-full">JS/TS</span>
          <span class="tag px-3 py-1 rounded-full">PyTorch</span>
          <span class="tag px-3 py-1 rounded-full">TensorFlow</span>
          <span class="tag px-3 py-1 rounded-full">OpenCV</span>
          <span class="tag px-3 py-1 rounded-full">Flask</span>
          <span class="tag px-3 py-1 rounded-full">Airflow</span>
          <span class="tag px-3 py-1 rounded-full">Kubernetes</span>
          <span class="tag px-3 py-1 rounded-full">Docker</span>
          <span class="tag px-3 py-1 rounded-full">Linux</span>
        </div>
      </div>
    </section>

    <!-- EXPERIENCE (super condensed) -->
    <section id="experience">
      <h2 class="text-2xl font-bold mb-6">Experience</h2>
      <div class="grid gap-4">
        <div class="glass rounded-3xl p-5 hover-raise">
          <div class="flex flex-wrap items-center justify-between gap-2">
            <div class="font-semibold">Autonomous Networks Research Group — Edge Computing Intern</div>
            <div class="text-xs text-zinc-400">May 2025 – Present · Los Angeles</div>
          </div>
          <ul class="list-disc pl-5 mt-2 text-sm text-zinc-300 space-y-1">
            <li>Integrated <b>SAGA</b> with <b>Apache Airflow</b> for DAG‑driven orchestration across edge nodes.</li>
            <li>Deployed automated k8s cluster management on Intel UP7000 edge testbed.</li>
          </ul>
        </div>
        <div class="glass rounded-3xl p-5 hover-raise">
          <div class="flex flex-wrap items-center justify-between gap-2">
            <div class="font-semibold">Network Reconnaissance Lab — Undergraduate Research Assistant</div>
            <div class="text-xs text-zinc-400">Jan 2025 – Present · Los Angeles</div>
          </div>
          <ul class="list-disc pl-5 mt-2 text-sm text-zinc-300 space-y-1">
            <li>ML‑assisted threat detection and vulnerability analysis for complex networks.</li>
          </ul>
        </div>
        <div class="glass rounded-3xl p-5 hover-raise">
          <div class="flex flex-wrap items-center justify-between gap-2">
            <div class="font-semibold">Quantum Programming Seminar — Undergraduate Research Assistant</div>
            <div class="text-xs text-zinc-400">May 2025 – Present · Los Angeles</div>
          </div>
          <ul class="list-disc pl-5 mt-2 text-sm text-zinc-300 space-y-1">
            <li>Designing and simulating algorithms in <b>Qiskit</b> & <b>Cirq</b>; presenting findings weekly.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="pb-24">
      <div class="glass rounded-3xl p-6 md:p-10 text-center hover-raise">
        <h2 class="text-2xl font-bold">Let’s build something useful.</h2>
        <p class="mt-2 text-zinc-300">Open to Summer 2026 SWE internships and collaborations in AI + systems + fintech.</p>
        <div class="mt-5 flex items-center justify-center gap-3">
          <a class="btn btn-primary" href="mailto:surpreet@usc.edu">Email me</a>
          <a class="btn btn-outline" href="https://www.linkedin.com/in/surpr33t" target="_blank">LinkedIn</a>
          <a class="btn btn-outline" href="https://github.com/surpr33t" target="_blank">GitHub</a>
        </div>
      </div>
    </section>
  </main>

  <footer class="pb-10 text-center text-xs text-zinc-500">
    © <span id="y"></span> Surpreet Kaur · Built with Tailwind · Hosted on GitHub Pages
  </footer>

  <script>document.getElementById('y').textContent = new Date().getFullYear()</script>
</body>
</html>
