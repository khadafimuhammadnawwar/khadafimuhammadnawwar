<div align="center">

  <!-- Profile Mascot / Header -->
  <img src="cat.png" width="180" alt="Muhammad Nawwar Khadafi" />

  <h1>Muhammad Nawwar Khadafi</h1>

  <p>
    <b>Informatics Engineering Student & Software Developer</b><br>
  </p>

  <p>
    <a href="https://www.linkedin.com/in/muhammadnawwarkhadafi/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Muhammad_Nawwar_Khadafi-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <img src="https://img.shields.io/badge/Focus-Backend_%26_Data_Pipelines-38BDF8?style=flat-square" alt="Focus" />
    <img src="https://img.shields.io/badge/Status-Open_for_Collaboration-blueviolet?style=flat-square" alt="Status" />
  </p>

</div>

---

### 💻 Developer Console

```bash
╭─ nawwar@pnl-devstation: ~ ────────────────────────────────────────────────────────╮
│                                                                                   │
│  $ whoami --profile                                                               │
│                                                                                   │
│  Name          : Muhammad Nawwar Khadafi                                          │
│  Institution   : Informatics Engineering @ Politeknik Negeri Lhokseumawe (PNL)    │
│  Domain        : Backend Architecture, Automated Data Pipelines & Systems Logic   │
│  Core Tools    : Python 3.12+ • PostgreSQL • C/C++ • Linux • Django               │
│  Methodology   : Test-Driven Development (Pytest) • Strict Financial Checksums    │
│  Status        : Engineering deterministic & scalable automation systems ⚡       │
│                                                                                   │
╰───────────────────────────────────────────────────────────────────────────────────╯
```

---

### ⚡ Active Focus & Engineering Scope

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>🔭 What I'm Building</h4>
      <ul>
        <li><b>High-Precision Data Pipelines:</b> Extracting, transforming, and reconciling government financial audit reports (BPK RI).</li>
        <li><b>Deterministic Validation Gates:</b> Zero-guessing policy with strict balance checksums (Δ ≤ Rp 1.00).</li>
        <li><b>Production Clean Code:</b> Thin controller architecture, decoupled domain services, and robust audit trails.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🛡️ Engineering Principles</h4>
      <ul>
        <li><b>Zero Data-Guessing:</b> Reject arbitrary rounding or speculative values; require hard proof & audit trails.</li>
        <li><b>Test-Driven Rigor:</b> Every pipeline logic change is guarded by comprehensive <code>pytest</code> golden baselines.</li>
        <li><b>Modern Standards:</b> Strict type hints, PEP 621 packaging, and Git Conventional Commits.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠️ Tools & Technologies I Work With

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,django,postgres,redis,docker,nginx,linux,bash,git,github,js,tailwind,htmx,alpinejs,vscode,postman&perline=8" alt="My Skills" />
  </a>
</div>

---

### 🚀 Featured Engineering Case Studies

<table width="100%">
  <tr>
    <td>
      <h3>📊 <a href="https://github.com/khadafimuhammadnawwar/lkpd-aset-tetap">LKPD Fixed Asset Pipeline</a></h3>
      <p>
        An enterprise-grade automation pipeline built to extract, reconcile, and audit 7 fixed-asset accounts from BPK RI official local government financial reports (2018–2023) across 23 regencies and cities in Aceh.
      </p>
      <ul>
        <li><b>Hard Checksum Gate:</b> Enforces zero-tolerance validation (Δ ≤ Rp 1.00) against official balance sheet totals.</li>
        <li><b>Multi-Tier Extraction:</b> Spatial tabular parsing (Tier 1), raw regex extraction (Tier 2), and automated human-in-the-loop review queues.</li>
        <li><b>Immutable Verification:</b> Protected master templates and golden baseline test suite verified with automated <code>pytest</code> suites.</li>
      </ul>
      <pre><code>$ cat pipeline_architecture.txt

┌──────────────────────────┐       ┌───────────────────────────────────────────────┐
│  1. RAW DATA INGESTION   │       │         2. MULTI-TIER EXTRACTION ENGINE       │
│                          │       │                                               │
│  📄 250+ LKPD PDFs       ├──────►│  • Tier 1: Spatial Tabular Parsing (OpenPyXL) │
│  📍 23 Kab/Kota (Aceh)   │       │  • Tier 2: Raw Regex Fallback Engine          │
└──────────────────────────┘       └───────────────────────┬───────────────────────┘
                                                           │
                                                           ▼
┌──────────────────────────┐       ┌───────────────────────────────────────────────┐
│   4. QA & VERIFICATION   │       │         3. DETERMINISTIC VALIDATION GATE      │
│                          │ PASS  │                                               │
│  ✅ Golden Baseline DB   │◄──────┤  ⚖️ Hard Checksum Gate (Δ ≤ Rp 1.00)          │
│  🧪 Pytest Suite Guarded │       │     Against Official Balance Sheet Totals     │
└──────────────────────────┘       └───────────────────────┬───────────────────────┘
                                                           │ FAIL (Δ > Rp 1.00)
                                                           ▼
                                   ┌───────────────────────────────────────────────┐
                                   │         ⚠️ HUMAN-IN-THE-LOOP QUEUE            │
                                   │         Flagged for Manual Audit Review       │
                                   └───────────────────────────────────────────────┘</code></pre>
      <p>
        <b>Tech Stack:</b> <code>Python 3.12+</code> • <code>Pytest</code> • <code>Pandas</code> • <code>OpenPyXL</code> • <code>PEP 621 CLI</code>
      </p>
    </td>
  </tr>
</table>

<br/>

<table width="100%">
  <tr>
    <td>
      <h3>🎓 <a href="https://github.com/khadafimuhammadnawwar/sim-magang-tik-pnl">SIM Magang JTIK PNL (Academic Internship Management System)</a></h3>
      <p>
        An enterprise academic workflow and digital document review platform engineered for the Department of Information and Computer Technology (JTIK), Politeknik Negeri Lhokseumawe.
      </p>
      <ul>
        <li><b>Interactive PDF Review Studio:</b> Zero-lag in-browser document review featuring custom touch/pointer drawing canvas overlay powered by local Mozilla PDF.js v3.11.174 without external CDNs.</li>
        <li><b>Sequential Approval State Machine:</b> Strict 4-step sequential approval chain (Koordinator Magang &rarr; Kaprodi &rarr; Sekjur &rarr; Kajur) enforced via <code>django-fsm-2</code> model guards and service layer orchestration.</li>
        <li><b>Concurrency & Atomicity Safety:</b> ACID atomic operations with PostgreSQL row-level locks (<code>select_for_update</code>) to prevent double-approval race conditions, auto SHA-256 document checksums, and append-only audit trails.</li>
        <li><b>Modern Server-Rendered Architecture:</b> Reactive hypermedia-driven UI combining Django 6 server templates with Tailwind CSS, Alpine.js, and granular HTMX partial exchanges.</li>
      </ul>
      <p>
        <b>Tech Stack:</b> <code>Python 3.12+</code> • <code>Django 6.x</code> • <code>PostgreSQL</code> • <code>HTMX</code> • <code>Alpine.js</code> • <code>Tailwind CSS</code> • <code>Mozilla PDF.js</code>
      </p>
    </td>
  </tr>
</table>

<br/>

<table width="100%">
  <tr>
    <td>
      <h3>⚡ <a href="https://github.com/khadafimuhammadnawwar/ProyekElearning">Hybrid E-Learning Platform (Dual-Currency & Community Engine)</a></h3>
      <p>
        A production-grade online learning platform featuring dual payment gateway integration, automated Discord community role synchronization, and asynchronous video streaming infrastructure.
      </p>
      <ul>
        <li><b>Hybrid Dual-Currency Gateway:</b> Unified webhook architecture routing local IDR payments via Midtrans Snap (QRIS, e-Wallets, Virtual Accounts) and global USD checkouts via Lemon Squeezy (PayPal, Apple Pay) with automated HMAC signature verification.</li>
        <li><b>Automated Discord Community Integration:</b> Real-time membership tier synchronization with Discord REST API v10 to instantly provision premium student roles upon successful checkout.</li>
        <li><b>Asynchronous Video & Document Delivery:</b> Background video upload pipeline utilizing Cloudinary with adaptive HLS (HTTP Live Streaming <code>.m3u8</code>) transcoding and secure CloudPDF modular curriculum paywalls.</li>
        <li><b>Clean Service Layer Architecture:</b> Decoupled transaction, subscription, and enrollment domain services isolated in <code>core/services.py</code> with comprehensive webhook replay protection.</li>
      </ul>
      <p>
        <b>Tech Stack:</b> <code>Python 3.12+</code> • <code>Django 5.x</code> • <code>PostgreSQL / MySQL</code> • <code>Midtrans Snap API</code> • <code>Lemon Squeezy API</code> • <code>Discord API v10</code> • <code>Tailwind CSS</code> • <code>Cloudinary</code>
      </p>
    </td>
  </tr>
</table>

---

<div align="center">
  <sub>Engineered with precision & modern architectural standards • <b>Muhammad Nawwar Khadafi</b></sub>
</div>
