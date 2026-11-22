<style>
  :root {
    --bg: #0d1117;
    --fg: #e6e6e6;
    --muted: #8b949e;
    --accent: #3b82f6;
    --accent2: #10b981;
    --card: #1e2431;
  }
  body {font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; background: var(--bg); color: var(--fg); margin:0; padding:0;}
  .header {position:relative; padding:2rem 1rem; text-align:center;}
  .header h1 {font-size:2.2rem; font-weight:800; letter-spacing:.2em; margin:0.5rem 0;}
  .header .role {font-size:1rem; color:var(--muted); margin-bottom:1rem;}
  .badge {display:inline-block;padding:.2rem .6rem;margin:.2rem;border-radius:9999px;font-size:.7rem;font-weight:600;background:var(--card);color:var(--fg);border:1px solid var(--muted);}
  .section {padding:2rem 1rem; max-width:800px;margin:auto;}
  .section h2 {border-left:4px solid var(--accent);padding-left:.5rem;font-size:1.3rem;margin-bottom:1.5rem;}
  .card {background:var(--card);border:1px solid var(--muted);border-radius:.5rem;padding:1.5rem;margin-bottom:1.5rem;}
  .card h3 {margin:0 0 .5rem 0;font-size:1.1rem;}
  .principle {margin:.5rem 0;padding:.5rem .8rem;background:rgba(59,130,246,0.1);border-radius:.3rem;font-size:.9rem;color:var(--accent);}
  .principle strong {color:var(--fg);}
  .footer {text-align:center;padding:2rem 1rem;color:var(--muted);font-size:.8rem;}
  @keyframes pulse {0%{transform:scale(1);}50%{transform:scale(1.05);}100%{transform:scale(1);}}
  .pulse {animation:pulse 2s infinite;}
</style>

<div class="header">
  <h1>Ayush Kumar</h1>
  <div class="role">Full‑stack engineer · AI‑integrated products · Shipping to production</div>
  <div>
    <a class="badge" href="https://www.linkedin.com/in/ayush-kumar-562666346/">LinkedIn</a>
    <a class="badge" href="mailto:ayushpanther@gmail.com">Email</a>
    <a class="badge" href="https://x.com/AyushkumarXD">X</a>
    <a class="badge" href="https://github.com/99Ayush">GitHub</a>
  </div>
</div>

<div class="section">
  <h2>🎯 What I do</h2>
  <p>I build full‑stack products from empty repository to deployed URL. I’m obsessed with the bits most people skip:</p>
  <ul>
    <li class="principle"><strong>Deterministic over clever</strong> – Salary math is plain JavaScript with a visible formula.</li>
    <li class="principle"><strong>Privacy is an ordering problem</strong> – PII gets redacted before it leaves the machine.</li>
    <li class="principle"><strong>Abstention is an answer</strong> – “I couldn’t find evidence” is a valid verdict.</li>
  </ul>
</div>

<div class="section">
  <h2>📦 Selected projects</h2>
  <div class="card">
    <h3>Fin‑Buddy</h3>
    <p>Reads offer letters & payslips, extracts numbers, flags risky clauses, compares on <strong>in‑hand pay</strong>.</p>
    <p><strong>Stack:</strong> React · Node · Express · MongoDB · Tesseract OCR</p>
    <p><a href="https://github.com/99Ayush/fin-buddy">GitHub</a> · <a href="https://nivora-pi.vercel.app">Demo</a></p>
  </div>
  <div class="card">
    <h3>Nivora</h3>
    <p>Student housing: verified PG/hostel listings with interactive maps, peer reviews, role‑based auth. I wrote 203 of 207 commits.</p>
    <p><strong>Stack:</strong> React · Express · Firebase · Leaflet · Radix UI</p>
    <p><a href="https://github.com/99Ayush/NIVORA">GitHub</a> · <a href="https://nivora-pi.vercel.app">Demo</a></p>
  </div>
  <div class="card">
    <h3>Verity</h3>
    <p>Evidence‑first fact‑checking: retrieves web sources, returns a verdict with <em>verbatim quoted citations</em>, and abstains deterministically.</p>
    <p><strong>Stack:</strong> React · Express · TypeScript · Gemini · Tavily</p>
    <p><a href="https://github.com/99Ayush/verity">GitHub</a> · <a href="https://verity-nine-lyart.vercel.app">Demo</a></p>
  </div>
  <div class="card">
    <h3>InAmigos ERP</h3>
    <p>NGO operations: volunteer triage, CSR funding pipeline, initiative tracking, full audit trail.</p>
    <p><strong>Stack:</strong> React · Express · Supabase · PostgreSQL</p>
    <p><a href="https://github.com/99Ayush/inamigos-erp">GitHub</a> · <a href="https://in-amigos-foundation-ai-application-ecru.vercel.app">Demo</a></p>
  </div>
  <div class="card">
    <h3>Grand Prix</h3>
    <p>F1 pit‑wall telemetry: calibrated tyre‑compound scoring, aquaplaning risk modelling and pit‑crossover strategy windows.</p>
    <p><strong>Stack:</strong> React · Node · MongoDB · Chart.js</p>
    <p><a href="https://github.com/99Ayush/grandprix">GitHub</a></p>
  </div>
  <div class="card">
    <h3>Banking API Simulator</h3>
    <p>Money movement treated seriously: atomic transfers inside MongoDB transactions, idempotent retries, immutable double‑entry ledger and reconciliation.</p>
    <p><strong>Stack:</strong> Node · Express · MongoDB · Redis · JWT</p>
    <p><a href="https://github.com/99Ayush/banking-app-simulator">GitHub</a></p>
  </div>
  <div class="card">
    <h3>Pokepedia</h3>
    <p>Pokedex in vanilla JavaScript — no framework, no build step, hand‑rolled caching and DOM rendering.</p>
    <p><strong>Stack:</strong> JavaScript · CSS3 · PokeAPI</p>
    <p><a href="https://github.com/99Ayush/pokepedia">GitHub</a> · <a href="https://pokepedia-tan.vercel.app">Demo</a></p>
  </div>
</div>

<div class="section">
  <h2>🛠️ Tech stack</h2>
  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(120px,1fr));gap:.5rem;">
    <span class="badge">JavaScript</span>
    <span class="badge">TypeScript</span>
    <span class="badge">Python</span>
    <span class="badge">C++</span>
    <span class="badge">React</span>
    <span class="badge">Node.js</span>
    <span class="badge">Express</span>
    <span class="badge">Vite</span>
    <span class="badge">Tailwind</span>
    <span class="badge">Chart.js</span>
    <span class="badge">Leaflet</span>
    <span class="badge">MongoDB</span>
    <span class="badge">PostgreSQL</span>
    <span class="badge">Supabase</span>
    <span class="badge">Firebase</span>
    <span class="badge">Gemini</span>
    <span class="badge">Tesseract</span>
  </div>
</div>

<div class="section">
  <h2>📫 Contact</h2>
  <div style="display:flex;justify-content:center;gap:1rem;">
    <a class="badge" href="https://www.linkedin.com/in/ayush-kumar-562666346/">LinkedIn</a>
    <a class="badge" href="mailto:ayushpanther@gmail.com">Email</a>
    <a class="badge" href="https://x.com/AyushkumarXD">X</a>
    <a class="badge" href="https://github.com/99Ayush">GitHub</a>
  </div>
</div>

<div class="footer">
  © 2026 Ayush Kumar · <a href="https://github.com/99Ayush">github.com/99Ayush</a>
</div>

<script>
  // Subtle pulse on accent badges when page is viewed in a browser that supports JS
  document.querySelectorAll('.badge').forEach(b => b.classList.add('pulse'));
</script>