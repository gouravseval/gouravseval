
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  .wrap { padding: 2rem 1rem; max-width: 680px; font-family: var(--font-sans); }
  .hero { text-align: center; padding-bottom: 1.5rem; border-bottom: 0.5px solid var(--color-border-tertiary); margin-bottom: 1.5rem; }
  .avatar { width: 80px; height: 80px; border-radius: 50%; background: #EEEDFE; display: flex; align-items: center; justify-content: center; font-size: 26px; font-weight: 500; color: #534AB7; margin: 0 auto 1rem; border: 0.5px solid #CECBF6; }
  .name { font-size: 22px; font-weight: 500; color: var(--color-text-primary); margin-bottom: 4px; }
  .tagline { font-size: 14px; color: var(--color-text-secondary); margin-bottom: 1rem; }
  .links { display: flex; gap: 8px; justify-content: center; flex-wrap: wrap; }
  .link-btn { display: inline-flex; align-items: center; gap: 6px; padding: 5px 12px; border-radius: 20px; font-size: 12px; font-weight: 500; text-decoration: none; border: 0.5px solid var(--color-border-secondary); color: var(--color-text-secondary); background: var(--color-background-secondary); cursor: pointer; }
  .link-btn i { font-size: 14px; }
  .link-btn:hover { background: var(--color-background-tertiary); }

  .section { margin-bottom: 1.5rem; }
  .section-title { font-size: 13px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 10px; display: flex; align-items: center; gap: 6px; }
  .section-title i { font-size: 15px; }

  .about-grid { display: grid; gap: 6px; }
  .about-row { display: flex; align-items: flex-start; gap: 8px; font-size: 14px; color: var(--color-text-primary); line-height: 1.5; }
  .about-row i { font-size: 15px; color: var(--color-text-secondary); margin-top: 2px; flex-shrink: 0; }

  .stats { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; }
  .stat { background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 12px; text-align: center; }
  .stat-num { font-size: 22px; font-weight: 500; color: var(--color-text-primary); }
  .stat-label { font-size: 12px; color: var(--color-text-secondary); margin-top: 2px; }

  .badges { display: flex; flex-wrap: wrap; gap: 6px; }
  .badge { display: inline-flex; align-items: center; gap: 5px; padding: 4px 10px; border-radius: var(--border-radius-md); font-size: 12px; font-weight: 500; border: 0.5px solid; }
  .badge.blue { background: #E6F1FB; border-color: #B5D4F4; color: #185FA5; }
  .badge.teal { background: #E1F5EE; border-color: #9FE1CB; color: #0F6E56; }
  .badge.coral { background: #FAECE7; border-color: #F5C4B3; color: #993C1D; }
  .badge.purple { background: #EEEDFE; border-color: #CECBF6; color: #534AB7; }
  .badge.gray { background: #F1EFE8; border-color: #D3D1C7; color: #5F5E5A; }
  .badge.amber { background: #FAEEDA; border-color: #FAC775; color: #854F0B; }
  .badge.green { background: #EAF3DE; border-color: #C0DD97; color: #3B6D11; }

  .projects { display: grid; gap: 10px; }
  .project-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 12px 14px; }
  .project-card:hover { border-color: var(--color-border-secondary); }
  .proj-name { font-size: 14px; font-weight: 500; color: #534AB7; display: flex; align-items: center; gap: 5px; margin-bottom: 5px; }
  .proj-desc { font-size: 13px; color: var(--color-text-secondary); line-height: 1.5; margin-bottom: 8px; }
  .proj-stack { display: flex; flex-wrap: wrap; gap: 4px; }
  .stack-tag { font-size: 11px; padding: 2px 7px; border-radius: 10px; background: #F1EFE8; color: #5F5E5A; border: 0.5px solid #D3D1C7; }
  .proj-highlight { font-size: 12px; color: #0F6E56; background: #E1F5EE; border: 0.5px solid #9FE1CB; border-radius: 10px; padding: 2px 8px; display: inline-block; margin-bottom: 6px; }

  .contact-bar { background: var(--color-background-secondary); border-radius: var(--border-radius-lg); padding: 12px 16px; display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 8px; }
  .contact-item { display: flex; align-items: center; gap: 6px; font-size: 13px; color: var(--color-text-secondary); }
  .open-badge { background: #EAF3DE; border: 0.5px solid #C0DD97; color: #3B6D11; font-size: 11px; font-weight: 500; padding: 3px 10px; border-radius: 12px; }
</style>

<div class="wrap">
  <h2 class="sr-only">Gourav Jangra — GitHub Profile</h2>

  <div class="hero">
    <div class="avatar">GJ</div>
    <div class="name">Gourav Jangra</div>
    <div class="tagline">Full Stack AI Developer · React · Next.js · Angular · Node.js · Python</div>
    <div class="links">
      <a class="link-btn" href="https://linkedin.com/in/gouravjangra"><i class="ti ti-brand-linkedin" aria-hidden="true"></i>LinkedIn</a>
      <a class="link-btn" href="https://github.com/gouravjangra"><i class="ti ti-brand-github" aria-hidden="true"></i>GitHub</a>
      <a class="link-btn" href="mailto:gouravjangra033@gmail.com"><i class="ti ti-mail" aria-hidden="true"></i>Email</a>
    </div>
  </div>

  <div class="section">
    <div class="section-title"><i class="ti ti-user-circle" aria-hidden="true"></i>About me</div>
    <div class="about-grid">
      <div class="about-row"><i class="ti ti-building" aria-hidden="true"></i><span>Software Engineer (Frontend) at <strong>Antino Labs</strong>, Gurgaon</span></div>
      <div class="about-row"><i class="ti ti-stack-2" aria-hidden="true"></i><span>Full stack dev — React, Next.js, Angular on frontend; Django, FastAPI, Node.js on backend</span></div>
      <div class="about-row"><i class="ti ti-users" aria-hidden="true"></i><span>Delivered production apps serving <strong>50,000+ monthly active users</strong></span></div>
      <div class="about-row"><i class="ti ti-robot" aria-hidden="true"></i><span>AI-assisted development with Claude, Cursor AI, GitHub Copilot, and OpenAI Codex</span></div>
      <div class="about-row"><i class="ti ti-chart-line" aria-hidden="true"></i><span>Focused on Core Web Vitals, SSR/SSG, and performance optimization</span></div>
      <div class="about-row"><i class="ti ti-world" aria-hidden="true"></i><span>Based in Haryana, India · Open to relocation</span></div>
    </div>
  </div>

  <div class="section">
    <div class="section-title"><i class="ti ti-chart-bar" aria-hidden="true"></i>At a glance</div>
    <div class="stats">
      <div class="stat"><div class="stat-num">1.10</div><div class="stat-label">Years experience</div></div>
      <div class="stat"><div class="stat-num">4+</div><div class="stat-label">Live products</div></div>
      <div class="stat"><div class="stat-num">50K+</div><div class="stat-label">Monthly users</div></div>
    </div>
  </div>

  <div class="section">
    <div class="section-title"><i class="ti ti-code" aria-hidden="true"></i>Tech stack</div>
    <div style="margin-bottom: 8px; font-size: 12px; color: var(--color-text-secondary); font-weight: 500;">Frontend</div>
    <div class="badges" style="margin-bottom: 12px;">
      <span class="badge blue">React.js</span>
      <span class="badge blue">Next.js</span>
      <span class="badge coral">Angular</span>
      <span class="badge blue">TypeScript</span>
      <span class="badge blue">JavaScript ES6+</span>
      <span class="badge teal">Tailwind CSS</span>
      <span class="badge gray">HTML5 / CSS3</span>
    </div>
    <div style="margin-bottom: 8px; font-size: 12px; color: var(--color-text-secondary); font-weight: 500;">Backend & Database</div>
    <div class="badges" style="margin-bottom: 12px;">
      <span class="badge green">Node.js</span>
      <span class="badge green">Python</span>
      <span class="badge green">Django</span>
      <span class="badge green">FastAPI</span>
      <span class="badge gray">Express.js</span>
      <span class="badge gray">NestJS</span>
      <span class="badge gray">Flask</span>
    </div>
    <div style="margin-bottom: 8px; font-size: 12px; color: var(--color-text-secondary); font-weight: 500;">State & Architecture</div>
    <div class="badges" style="margin-bottom: 12px;">
      <span class="badge purple">Redux Toolkit</span>
      <span class="badge purple">RBAC</span>
      <span class="badge purple">REST APIs</span>
      <span class="badge purple">JWT / OAuth 2.0</span>
      <span class="badge purple">SSR / SSG</span>
    </div>
    <div style="margin-bottom: 8px; font-size: 12px; color: var(--color-text-secondary); font-weight: 500;">AI Tools</div>
    <div class="badges" style="margin-bottom: 12px;">
      <span class="badge coral">Claude</span>
      <span class="badge coral">Cursor AI</span>
      <span class="badge coral">GitHub Copilot</span>
      <span class="badge coral">OpenAI Codex</span>
    </div>
    <div style="margin-bottom: 8px; font-size: 12px; color: var(--color-text-secondary); font-weight: 500;">Tools & UI</div>
    <div class="badges">
      <span class="badge amber">Git / GitHub</span>
      <span class="badge gray">Postman</span>
      <span class="badge gray">Vite / Webpack</span>
      <span class="badge gray">Ant Design</span>
      <span class="badge gray">Material UI</span>
      <span class="badge gray">shadcn/ui</span>
      <span class="badge gray">Figma</span>
    </div>
  </div>

  <div class="section">
    <div class="section-title"><i class="ti ti-rocket" aria-hidden="true"></i>Projects</div>
    <div class="projects">
      <div class="project-card">
        <div class="proj-name">Guarented — Furniture & Appliance Rental</div>
        <div class="proj-highlight">40% faster page load</div>
        <div class="proj-desc">Built responsive rental and admin workflows with Angular. Integrated Python backend APIs, implemented RBAC, and improved Lighthouse scores and SEO visibility.</div>
        <div class="proj-stack">
          <span class="stack-tag">Angular</span><span class="stack-tag">JavaScript</span><span class="stack-tag">Tailwind CSS</span><span class="stack-tag">Python</span><span class="stack-tag">RBAC</span>
        </div>
      </div>
      <div class="project-card">
        <div class="proj-name">RxMen — Healthcare Technology Platform</div>
        <div class="proj-highlight">Improved Core Web Vitals</div>
        <div class="proj-desc">Developed Next.js frontend for healthcare booking, checkout, and subscriptions. Integrated Razorpay and Stripe, applied SSR and code splitting for performance.</div>
        <div class="proj-stack">
          <span class="stack-tag">Next.js</span><span class="stack-tag">SSR</span><span class="stack-tag">Razorpay</span><span class="stack-tag">Stripe</span><span class="stack-tag">TypeScript</span>
        </div>
      </div>
      <div class="project-card">
        <div class="proj-name">Spare Space — Workspace Rental</div>
        <div class="proj-highlight">Real-time map discovery</div>
        <div class="proj-desc">SSR-enabled workspace discovery and booking with Leaflet.js map integration. Built role-based admin panel for listing and booking management.</div>
        <div class="proj-stack">
          <span class="stack-tag">Next.js</span><span class="stack-tag">React.js</span><span class="stack-tag">Redux Toolkit</span><span class="stack-tag">Leaflet.js</span><span class="stack-tag">Node.js</span>
        </div>
      </div>
      <div class="project-card">
        <div class="proj-name">GMR EV — Airport EV Charging Management</div>
        <div class="proj-highlight">Real-time charging ops</div>
        <div class="proj-desc">Developed EV charging station booking and management dashboards. Integrated REST APIs for real-time session and availability data at airport locations.</div>
        <div class="proj-stack">
          <span class="stack-tag">React.js</span><span class="stack-tag">JavaScript</span><span class="stack-tag">Tailwind CSS</span><span class="stack-tag">REST APIs</span>
        </div>
      </div>
    </div>
  </div>

  <div class="contact-bar">
    <div style="display:flex; align-items:center; gap:8px;">
      <span class="open-badge">Open to work</span>
      <span style="font-size:13px; color:var(--color-text-secondary);">Frontend · Full Stack · Open to relocation</span>
    </div>
    <div style="display:flex; gap:12px; flex-wrap:wrap;">
      <div class="contact-item"><i class="ti ti-mail" aria-hidden="true"></i>gouravjangra033@gmail.com</div>
      <div class="contact-item"><i class="ti ti-phone" aria-hidden="true"></i>+91 98027 76676</div>
    </div>
  </div>
</div>
