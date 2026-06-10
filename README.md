
<style>
.section { margin-bottom: 2rem; }
.section-title { font-size: 13px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.75rem; }
.badge-row { display: flex; flex-wrap: wrap; gap: 8px; }
.badge { font-size: 13px; padding: 4px 12px; border-radius: 20px; font-weight: 500; }
.card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1rem 1.25rem; margin-bottom: 10px; }
.proj-title { font-size: 14px; font-weight: 500; margin: 0 0 4px; }
.proj-desc { font-size: 13px; color: var(--color-text-secondary); margin: 0 0 8px; line-height: 1.5; }
.stat-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; }
.stat-card { background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 0.75rem 1rem; text-align: center; }
.stat-num { font-size: 22px; font-weight: 500; color: var(--color-text-primary); }
.stat-label { font-size: 12px; color: var(--color-text-secondary); margin-top: 2px; }
.copy-btn { font-size: 12px; padding: 6px 14px; border-radius: var(--border-radius-md); background: transparent; border: 0.5px solid var(--color-border-secondary); cursor: pointer; color: var(--color-text-secondary); display: inline-flex; align-items: center; gap: 6px; }
.copy-btn:hover { background: var(--color-background-secondary); }
pre { background: var(--color-background-secondary); border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-tertiary); padding: 1rem; font-size: 12px; font-family: var(--font-mono); overflow-x: auto; white-space: pre-wrap; line-height: 1.7; color: var(--color-text-primary); }
.tabs { display: flex; gap: 8px; margin-bottom: 1.5rem; flex-wrap: wrap; }
.tab { font-size: 13px; padding: 6px 14px; border-radius: 20px; cursor: pointer; border: 0.5px solid var(--color-border-tertiary); background: transparent; color: var(--color-text-secondary); }
.tab.active { background: var(--color-background-secondary); border-color: var(--color-border-primary); color: var(--color-text-primary); font-weight: 500; }
</style>

<h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0);">GitHub profile README preview and copy for Mohamed Elafandy</h2>

<div class="tabs">
  <button class="tab active" onclick="showTab('preview')">Preview</button>
  <button class="tab" onclick="showTab('markdown')">Markdown to copy</button>
</div>

<div id="tab-preview">

<div class="section">
  <p style="font-size:22px;font-weight:500;margin:0 0 4px;">Hi, I'm Mohamed 👋</p>
  <p style="font-size:15px;color:var(--color-text-secondary);margin:0 0 1rem;">Full-Stack Developer · Node.js · NestJS · React · Next.js · PostgreSQL · MongoDB</p>
  <p style="font-size:14px;color:var(--color-text-secondary);line-height:1.7;margin:0;">
    I build secure, scalable backend systems and polished frontend apps. 1+ year of professional experience in multi-tenant SaaS, real-time microservices, and RESTful API design — with a unique dual background in Software Engineering and Accounting & Finance.
  </p>
</div>

<div class="stat-grid section">
  <div class="stat-card"><div class="stat-num">~40%</div><div class="stat-label">API response time reduced</div></div>
  <div class="stat-card"><div class="stat-num">~60%</div><div class="stat-label">DB load reduced</div></div>
  <div class="stat-card"><div class="stat-num">25+</div><div class="stat-label">RESTful endpoints built</div></div>
</div>

<div class="section">
  <div class="section-title">Tech stack</div>
  <div class="badge-row">
    <span class="badge" style="background:#E1F5EE;color:#0F6E56;">Node.js</span>
    <span class="badge" style="background:#E1F5EE;color:#0F6E56;">NestJS</span>
    <span class="badge" style="background:#E6F1FB;color:#185FA5;">React.js</span>
    <span class="badge" style="background:#E6F1FB;color:#185FA5;">Next.js 14</span>
    <span class="badge" style="background:#EEEDFE;color:#534AB7;">TypeScript</span>
    <span class="badge" style="background:#EEEDFE;color:#534AB7;">PostgreSQL</span>
    <span class="badge" style="background:#FAEEDA;color:#854F0B;">MongoDB</span>
    <span class="badge" style="background:#FAEEDA;color:#854F0B;">Redis</span>
    <span class="badge" style="background:#F1EFE8;color:#5F5E5A;">Docker</span>
    <span class="badge" style="background:#F1EFE8;color:#5F5E5A;">JWT / RBAC</span>
    <span class="badge" style="background:#EAF3DE;color:#3B6D11;">Kafka</span>
  </div>
</div>

<div class="section">
  <div class="section-title">Featured projects</div>

  <div class="card">
    <div class="proj-title">🏫 Teacher Platform — Education SaaS</div>
    <div class="proj-desc">Tenant-isolated SaaS with JWT auth, QR-based attendance, RBAC, grade management, and PDF exports. NestJS · PostgreSQL · Next.js 14 · Docker</div>
    <span class="badge" style="background:#EEEDFE;color:#534AB7;font-size:12px;">In progress</span>
  </div>

  <div class="card">
    <div class="proj-title">📡 API Abuse — Real-time traffic monitor</div>
    <div class="proj-desc">Distributed microservices processing high-volume API traffic with Kafka, reducing direct DB load by ~60%. TypeScript · Express · Kafka · Docker</div>
    <a href="#" style="font-size:12px;color:var(--color-text-info);">View on GitHub ↗</a>
  </div>

  <div class="card">
    <div class="proj-title">🐱 Petopia — Cat adoption platform</div>
    <div class="proj-desc">20+ endpoints for full adoption lifecycle with JWT auth and RBAC, reducing unauthorized access by ~80%. Node.js · MongoDB · Cloudinary</div>
    <a href="#" style="font-size:12px;color:var(--color-text-info);">View on GitHub ↗</a>
  </div>
</div>

<div class="section">
  <div class="section-title">Currently learning</div>
  <div class="badge-row">
    <span class="badge" style="background:#FAEEDA;color:#854F0B;">AWS AI/ML (Udacity Scholar)</span>
    <span class="badge" style="background:#FAEEDA;color:#854F0B;">Odoo 19 Development</span>
  </div>
</div>

<div class="section">
  <div class="section-title">Get in touch</div>
  <p style="font-size:14px;color:var(--color-text-secondary);margin:0;">📧 mohamedelafandy593@gmail.com &nbsp;·&nbsp; 📍 Alexandria, Egypt &nbsp;·&nbsp; <a href="https://linkedin.com" style="color:var(--color-text-info);">LinkedIn</a> &nbsp;·&nbsp; <a href="https://github.com" style="color:var(--color-text-info);">GitHub</a></p>
</div>

</div>

<div id="tab-markdown" style="display:none;">
  <p style="font-size:13px;color:var(--color-text-secondary);margin:0 0 0.75rem;">Copy this into your GitHub profile <code>README.md</code> (replace the GitHub/LinkedIn links with yours):</p>
  <button class="copy-btn" onclick="copyMd()"><i class="ti ti-copy" aria-hidden="true"></i> Copy markdown</button>
  <div style="height:10px;"></div>
  <pre id="md-content"></pre>
</div>

<script>
const md = `# Hi, I'm Mohamed Elafandy 👋

**Full-Stack Developer** · Node.js · NestJS · React · Next.js · PostgreSQL · MongoDB

I build secure, scalable backend systems and polished frontend apps — with 1+ year of professional experience in multi-tenant SaaS, real-time microservices, and RESTful API design. Dual background in Software Engineering and Accounting & Finance.

---

## 🚀 Impact highlights

| Metric | Result |
|---|---|
| API response time | ~40% reduction |
| Database load | ~60% reduction |
| RESTful endpoints shipped | 25+ |

---

## 🛠️ Tech stack

**Backend:** Node.js · Express.js · NestJS · REST APIs · Microservices  
**Frontend:** React.js · Next.js 14 · Vite · Tailwind CSS · Framer Motion  
**Databases:** PostgreSQL · TypeORM · MongoDB · Mongoose · Redis  
**Auth & Security:** JWT (Access/Refresh Rotation) · RBAC · HttpOnly Cookies · OTP · bcryptjs  
**DevOps & Tools:** Docker · Git · Jest · Swagger/OpenAPI · Cloudinary  
**Languages:** TypeScript · JavaScript (ES6+) · Python · C  

---

## 📌 Featured projects

### 🏫 Teacher Platform — Education SaaS *(in progress)*
Tenant-isolated SaaS platform with JWT auth, QR-based attendance, RBAC, grade management, and PDF exports.  
\`TypeScript · NestJS · PostgreSQL · TypeORM · Next.js 14 · Docker\`

### 📡 [API Abuse — Real-time traffic monitor](https://github.com/YOUR_USERNAME/api-abuse)
Distributed microservices processing high-volume API traffic with Kafka, reducing direct DB load by ~60%.  
\`TypeScript · Express.js · Kafka · Microservices · Docker\`

### 🐱 [Petopia — Cat adoption platform](https://github.com/YOUR_USERNAME/petopia)
20+ endpoints covering the full adoption lifecycle with JWT, RBAC, and layered security middleware.  
\`Node.js · Express.js · MongoDB · Cloudinary\`

---

## 📚 Currently learning

- AWS AI & ML Scholars Program (Udacity · AWS Certified AI Practitioner path)
- Odoo 19 Development — custom modules, ORM, and core framework

---

## 📫 Get in touch

📧 mohamedelafandy593@gmail.com · 📍 Alexandria, Egypt  
[LinkedIn](https://linkedin.com/in/YOUR_PROFILE) · [GitHub](https://github.com/YOUR_USERNAME)
`;

document.getElementById('md-content').textContent = md;

function showTab(name) {
  document.getElementById('tab-preview').style.display = name === 'preview' ? 'block' : 'none';
  document.getElementById('tab-markdown').style.display = name === 'markdown' ? 'block' : 'none';
  document.querySelectorAll('.tab').forEach(t => t.classList.toggle('active', t.textContent.toLowerCase().includes(name === 'preview' ? 'preview' : 'markdown')));
}

function copyMd() {
  navigator.clipboard.writeText(md).then(() => {
    const btn = document.querySelector('.copy-btn');
    btn.innerHTML = '<i class="ti ti-check" aria-hidden="true"></i> Copied!';
    setTimeout(() => { btn.innerHTML = '<i class="ti ti-copy" aria-hidden="true"></i> Copy markdown'; }, 2000);
  });
}
</script>

 
