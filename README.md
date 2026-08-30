<!DOCTYPE HTML>
<!--
  Massively by HTML5 UP — Emmanuel Adenuga BA Portfolio
  Rebuilt standalone: base Massively theme + original custom CSS,
  since assets/css/main.css and /images/* were not supplied.
-->
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Emmanuel Adenuga | AI Automation Business Analyst</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="description" content="Emmanuel Adenuga – AI Automation Business Analyst with 10+ years experience. n8n, AI Agents, Power BI, SQL, BCS Certified." />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@300;400;600;700;900&family=Roboto+Slab:wght@600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>

    /* ============================================================
       BASE THEME  — recreated in the spirit of Massively by HTML5 UP
       (original assets/css/main.css was not provided)
    ============================================================ */
    :root{
      --navy:#1c2129; --navy-2:#252b35; --accent:#b57000;
      --ink:#1a1a2e; --body:#3d3d3d; --line:#dee2e6;
    }
    *{ box-sizing:border-box; }
    html{ scroll-behavior:smooth; }
    body{
      margin:0; font-family:'Source Sans Pro',-apple-system,Segoe UI,sans-serif;
      color:#3d3d3d; background:#fff; line-height:1.6; -webkit-font-smoothing:antialiased;
    }
    h1,h2,h3{ font-family:'Roboto Slab',serif; color:var(--ink); line-height:1.25; margin:0 0 .6em; }
    a{ color:var(--accent); text-decoration:none; }
    a:hover{ text-decoration:underline; }
    img{ max-width:100%; display:block; }
    ul{ margin:0; padding:0; }

    /* Fade in */
    #wrapper{ opacity:0; animation:fadeIn .6s ease forwards; }
    @keyframes fadeIn{ to{ opacity:1; } }

    /* ── INTRO / HERO ─────────────────────────────────────── */
    #intro{
      min-height:100vh; display:flex; flex-direction:column; align-items:center;
      justify-content:center; text-align:center; padding:6rem 1.5rem 4rem;
      background:
        radial-gradient(circle at 20% 20%, rgba(181,112,0,0.18), transparent 45%),
        radial-gradient(circle at 80% 75%, rgba(181,112,0,0.12), transparent 50%),
        linear-gradient(160deg, var(--navy) 0%, var(--navy-2) 100%);
      color:#fff; position:relative;
    }
    #intro h1{
      color:#fff; font-size:clamp(2.2rem,5vw,3.4rem); font-weight:700;
      letter-spacing:-1px; margin-bottom:0.9rem;
    }
    #intro > p{ color:rgba(255,255,255,0.78); font-size:1.05rem; max-width:520px; margin:0 auto; }
    #intro .actions{ list-style:none; margin-top:2.2rem; }
    #intro .actions a.button{
      display:inline-block; padding:0.85rem 2rem; border-radius:100px;
      background:var(--accent); color:#fff; font-weight:700; font-size:0.85rem;
      letter-spacing:0.04em; text-transform:uppercase; transition:transform .2s ease, box-shadow .2s ease;
      box-shadow:0 8px 24px rgba(181,112,0,0.35);
    }
    #intro .actions a.button:hover{ transform:translateY(-2px); text-decoration:none; }

    /* ── HEADER / NAV ─────────────────────────────────────── */
    header#header{ display:none; } /* logo folded into nav for this single-page build */
    nav#nav{
      position:sticky; top:0; z-index:20; display:flex; align-items:center;
      justify-content:space-between; padding:0.9rem 2rem; background:rgba(28,33,41,0.92);
      backdrop-filter:saturate(180%) blur(10px); border-bottom:1px solid rgba(255,255,255,0.08);
    }
    nav#nav ul{ list-style:none; display:flex; align-items:center; gap:1.4rem; margin:0; }
    nav#nav ul.links a{ color:#fff; font-weight:600; font-size:0.9rem; }
    nav#nav ul.links a:hover{ text-decoration:none; color:var(--accent); }
    nav#nav ul.icons a{
      color:#fff; opacity:0.85; font-size:1.05rem; margin-left:0.9rem;
    }
    nav#nav ul.icons a:hover{ opacity:1; color:var(--accent); }

    /* ── MAIN CONTAINER ───────────────────────────────────── */
    #main{ max-width:1100px; margin:0 auto; padding:3.5rem 1.5rem 1rem; }

    /* Section heading rhythm for skills block already styled below */
    .post.featured, .posts, .ea-about, .ea-skills-wrap{ margin-bottom:3rem; }

    .actions.special{ list-style:none; margin-top:1rem; }
    .actions.special .button{
      display:inline-block; padding:0.65rem 1.5rem; border:1px solid var(--accent);
      color:var(--accent); border-radius:6px; font-weight:600; font-size:0.85rem;
    }
    .actions.special .button:hover{ background:var(--accent); color:#fff; text-decoration:none; }
    .actions.special .button.large{ padding:0.85rem 2rem; font-size:0.9rem; }

    article.post.featured header h2{ font-size:1.6rem; }
    article.post.featured header h2 a{ color:var(--ink); }
    .posts article header h2{ font-size:1.25rem; }
    .posts article header h2 a{ color:var(--ink); }

    /* placeholder art standing in for missing screenshots */
    .shot{
      position:relative; border-radius:8px; overflow:hidden; margin:1rem 0;
      background:linear-gradient(135deg,#eef1f4,#dfe4e9); border:1px solid var(--line);
      display:flex; align-items:center; justify-content:center; text-align:center;
      aspect-ratio:16/9; color:#8a8f96;
    }
    .shot.featured{ aspect-ratio:21/9; background:linear-gradient(135deg,#1c2129,#3a4451); color:#cfd6dd; }
    .shot .shot-label{ padding:1rem; }
    .shot .shot-label i{ font-size:1.8rem; display:block; margin-bottom:0.5rem; opacity:0.7; }
    .shot .shot-label span{ font-size:0.75rem; letter-spacing:0.06em; text-transform:uppercase; font-weight:700; }

    /* ── FOOTER ───────────────────────────────────────────── */
    footer#footer{ background:var(--navy); color:rgba(255,255,255,0.85); padding:3rem 1.5rem 1.5rem; margin-top:3rem; }
    footer#footer .split.contact{
      max-width:1100px; margin:0 auto; display:grid; grid-template-columns:repeat(3,1fr); gap:2rem;
    }
    footer#footer h3{ color:#fff; font-size:1rem; margin-bottom:0.6rem; }
    footer#footer a{ color:rgba(255,255,255,0.8); }
    footer#footer a:hover{ color:var(--accent); }
    footer#footer ul.icons{ list-style:none; display:flex; gap:1rem; }
    footer#footer ul.icons a{ font-size:1.2rem; }
    #copyright{ text-align:center; padding:1.2rem; font-size:0.75rem; color:rgba(255,255,255,0.5); background:var(--navy); }
    #copyright ul{ list-style:none; display:flex; justify-content:center; gap:1rem; }
    @media screen and (max-width:736px){
      footer#footer .split.contact{ grid-template-columns:1fr; text-align:center; }
      footer#footer ul.icons{ justify-content:center; }
    }

    /* ============================================================
       ORIGINAL CUSTOM SECTION STYLES (from the uploaded file, unchanged)
    ============================================================ */
    .ea-badge-row{ display:flex; flex-wrap:wrap; justify-content:center; gap:.45rem; margin:.9rem 0 1.1rem; }
    .ea-badge{ background:rgba(255,255,255,.14); border:1px solid rgba(255,255,255,.32); color:#fff; font-size:.65rem; font-weight:700; letter-spacing:.09em; text-transform:uppercase; padding:.26rem .8rem; border-radius:100px; display:inline-block; }
    .ea-stat-strip{ display:flex; justify-content:center; gap:2rem; margin:1rem 0 1.6rem; flex-wrap:wrap; }
    .ea-stat{ text-align:center; }
    .ea-stat strong{ display:block; font-size:1.9rem; font-weight:800; color:#fff; line-height:1; }
    .ea-stat span{ font-size:.64rem; letter-spacing:.08em; text-transform:uppercase; color:rgba(255,255,255,.7); }

    .ea-avail{ background:#27ae60; color:#fff; font-size:.57rem; font-weight:700; letter-spacing:.06em; text-transform:uppercase; padding:.16rem .5rem; border-radius:100px; margin-left:.4rem; display:inline-block; }

    .ea-eyebrow{ display:block; font-size:.64rem; font-weight:700; letter-spacing:.15em; text-transform:uppercase; color:#b57000; margin-bottom:.4rem; }

    .ea-panel{ background:#f8f9fa; border:1px solid #dee2e6; border-radius:8px; padding:1.8rem 2.2rem; margin-bottom:1.4rem; }
    .ea-panel-accent{ border-left:4px solid #b57000; }

    .ea-about{ margin-bottom:3rem; }
    .ea-bio h3{ font-size:1.15rem; font-weight:700; color:#1a1a2e; margin:0 0 .9rem; padding-bottom:.7rem; border-bottom:1px solid #dee2e6; line-height:1.3; }
    .ea-bio p{ font-size:.9rem; line-height:1.85; color:#3d3d3d; margin:0 0 .8rem; }
    .ea-bio p:last-child{ margin-bottom:0; }
    .ea-bio strong{ color:#1a1a2e; font-weight:700; }
    .ea-bio em{ font-style:normal; color:#b57000; font-weight:600; }

    .ea-ach-grid{ display:grid; grid-template-columns:repeat(2,1fr); gap:.8rem; margin-top:.5rem; }
    .ea-ach-item{ background:#fff; border:1px solid #dee2e6; border-left:3px solid #b57000; border-radius:0 6px 6px 0; padding:.7rem 1rem; display:flex; align-items:flex-start; gap:.6rem; }
    .ea-ach-icon{ font-size:1rem; flex-shrink:0; margin-top:.05rem; }
    .ea-ach-text{ font-size:.79rem; color:#3d3d3d; line-height:1.55; }
    .ea-ach-text strong{ color:#1a1a2e; font-weight:700; }

    .ea-sectors{ background:#f8f9fa; border:1px solid #dee2e6; border-radius:8px; padding:1rem 1.8rem; margin-bottom:1.4rem; display:flex; align-items:center; gap:1rem; flex-wrap:wrap; }
    .ea-sec-label{ font-size:.64rem; font-weight:700; letter-spacing:.11em; text-transform:uppercase; color:#b57000; white-space:nowrap; }
    .ea-sec-tags{ display:flex; flex-wrap:wrap; gap:.38rem; }
    .ea-sec-tag{ font-size:.7rem; font-weight:600; background:#fff; border:1px solid #b57000; color:#6b4400; padding:.2rem .68rem; border-radius:100px; display:inline-block; }

    .ea-comp-wrap{ background:#f8f9fa; border:1px solid #dee2e6; border-radius:8px; padding:1.6rem 2rem; margin-bottom:1.4rem; }
    .ea-comp-heading{ font-size:.7rem; font-weight:700; letter-spacing:.12em; text-transform:uppercase; color:#b57000; margin-bottom:1.1rem; display:block; }
    .ea-comp-grid{ display:grid; grid-template-columns:repeat(3,1fr); gap:.9rem; }
    .ea-comp-card{ background:#fff; border:1px solid #dee2e6; border-top:3px solid #b57000; border-radius:6px; padding:.9rem 1rem; }
    .ea-comp-label{ font-size:.76rem; font-weight:700; color:#1a1a2e; display:block; margin-bottom:.35rem; }
    .ea-comp-desc{ font-size:.74rem; color:#555; line-height:1.55; display:block; }

    .ea-del{ background:#f8f9fa; border-left:4px solid #b57000; border-radius:0 6px 6px 0; padding:1rem 1.2rem; margin:1rem 0; }
    .ea-del-label{ font-size:.6rem; font-weight:700; letter-spacing:.14em; text-transform:uppercase; color:#b57000; display:block; margin-bottom:.75rem; }
    .ea-del ul{ list-style:none; margin:0; padding:0; }
    .ea-del ul li{ font-size:.83rem; line-height:1.6; color:#3d3d3d; padding:.45rem 0 .45rem 1.6rem; position:relative; margin:0; border-bottom:1px solid #e2e6ea; }
    .ea-del ul li:last-child{ border-bottom:none; }
    .ea-del ul li::before{ content:'✓'; color:#b57000; font-weight:700; font-size:.85rem; position:absolute; left:0; top:.48rem; }
    .ea-del ul li strong{ color:#1a1a2e; font-weight:700; display:block; margin-bottom:.15rem; font-size:.84rem; }

    .ea-tools{ display:flex; flex-wrap:wrap; gap:.36rem; margin:.8rem 0 1.2rem; }
    .ea-tb{ font-size:.67rem; font-weight:600; background:#fff; border:1px solid #b57000; color:#6b4400; padding:.2rem .62rem; border-radius:5px; display:inline-block; }

    .ea-skills-wrap{ margin:3rem 0 0; padding:2rem; background:#f8f9fa; border:1px solid #dee2e6; border-top:4px solid #b57000; border-radius:8px; }
    .ea-skills-wrap h2{ color:#1a1a2e; margin-bottom:.3rem; }
    .ea-skills-sub{ font-size:.86rem; color:#666; margin-bottom:1.6rem; display:block; }
    .ea-sk-grid{ display:grid; grid-template-columns:repeat(3,1fr); gap:1.1rem; }
    .ea-sk-card{ background:#fff; border:1px solid #dee2e6; border-top:3px solid #b57000; border-radius:6px; padding:1.2rem; }
    .ea-sk-icon{ font-size:1.4rem; display:block; margin-bottom:.45rem; }
    .ea-sk-title{ font-size:.73rem; font-weight:700; color:#1a1a2e; text-transform:uppercase; letter-spacing:.07em; display:block; margin-bottom:.65rem; padding-bottom:.45rem; border-bottom:1px solid #e9ecef; }
    .ea-sk-list{ list-style:none; margin:0; padding:0; }
    .ea-sk-list li{ font-size:.78rem; color:#444; padding:.2rem 0 .2rem 1rem; position:relative; line-height:1.5; margin:0; }
    .ea-sk-list li::before{ content:''; width:4px; height:4px; background:#b57000; border-radius:50%; position:absolute; left:0; top:.58rem; }

    .ea-disc{ background:#fffbf0; border:1px solid #e8d5a3; border-left:3px solid #b57000; border-radius:0 6px 6px 0; padding:.85rem 1.3rem; }
    .ea-disc p{ font-size:.75rem; color:#6b5c2e; line-height:1.65; margin:0; }
    .ea-disc strong{ color:#4a3d1a; }

    @media screen and (max-width:980px){
      .ea-comp-grid{ grid-template-columns:repeat(2,1fr); }
      .ea-sk-grid{ grid-template-columns:repeat(2,1fr); }
      .ea-ach-grid{ grid-template-columns:1fr; }
    }
    @media screen and (max-width:736px){
      .ea-panel{ padding:1.3rem; }
      .ea-comp-wrap{ padding:1.3rem; }
      .ea-skills-wrap{ padding:1.3rem; }
      nav#nav{ padding:0.8rem 1.2rem; }
    }
    @media screen and (max-width:560px){
      .ea-comp-grid{ grid-template-columns:1fr; }
      .ea-sk-grid{ grid-template-columns:1fr; }
    }

    .posts article > p, article.post.featured > header > p{
      font-size:.875rem; line-height:1.75; color:inherit; margin:0 0 1rem;
    }
    .posts{ display:grid; grid-template-columns:repeat(2,1fr); gap:2.5rem; }
    .posts article{ width:100%; margin:0; }
    @media screen and (max-width:980px){ .posts{ grid-template-columns:1fr; } }
    .ea-span-full{ grid-column:1/-1; max-width:700px; margin:0 auto; }

    </style>
  </head>
  <body class="is-preload">
    <div id="wrapper">

      <!-- ══ NAV ═════════════════════════════════════════════ -->
      <nav id="nav">
        <ul class="links">
          <li><a href="#intro" style="font-family:'Roboto Slab',serif; font-weight:700;">Emmanuel Adenuga</a></li>
          <li><a href="#main">Portfolio</a><span class="ea-avail">Open to Work</span></li>
        </ul>
        <ul class="icons">
          <li><a href="https://www.linkedin.com/in/emmanuel-adenuga/" target="_blank" rel="noopener" title="LinkedIn"><i class="fab fa-linkedin"></i></a></li>
          <li><a href="https://github.com/eoaadenuga" target="_blank" rel="noopener" title="GitHub"><i class="fab fa-github"></i></a></li>
        </ul>
      </nav>

      <!-- ══ INTRO ════════════════════════════════════════════ -->
      <div id="intro">
        <h1>Emmanuel Adenuga</h1>
        <div class="ea-badge-row">
          <span class="ea-badge">AI Automation Business Analyst</span>
          <span class="ea-badge">n8n &amp; AI Agents</span>
          <span class="ea-badge">BCS &amp; Scrum Certified</span>
          <span class="ea-badge">10+ Years Experience</span>
          <span class="ea-badge">Open to Work</span>
        </div>
        <p>Building intelligent systems that streamline business operations — AI workflows, data analysis and digital transformation delivery.</p>
        <div class="ea-stat-strip">
          <div class="ea-stat"><strong>10+</strong><span>Years Experience</span></div>
          <div class="ea-stat"><strong>8</strong><span>Projects</span></div>
          <div class="ea-stat"><strong>14</strong><span>Certifications</span></div>
          <div class="ea-stat"><strong>8</strong><span>Industry Sectors</span></div>
        </div>
        <ul class="actions">
          <li><a href="#main" class="button">View My Work</a></li>
        </ul>
      </div>

      <!-- ══ MAIN ════════════════════════════════════════════ -->
      <div id="main">

        <!-- ABOUT -->
        <div class="ea-about">

          <div class="ea-panel ea-panel-accent ea-bio">
            <span class="ea-eyebrow">About Me</span>
            <h3>AI Automation Business Analyst &amp; Test Professional</h3>
            <p>As a <strong>certified AI Automation Business Analyst and delivery lead with over 10 years of experience</strong>, I develop intelligent systems to streamline business operations. My work involves creating <strong>AI-powered automation workflows with n8n</strong>, designing structured data pipelines and implementing <strong>AI agents for contextual and conversational interactions</strong> — ensuring reliable and consistent outcomes for data-driven decision-making.</p>
            <p>I specialise in bridging business needs and technical solutions across <strong>healthcare, finance, digital platforms and enterprise environments</strong>, with a proven track record of delivering digital transformation initiatives that drive measurable business value, operational efficiency and high-quality software outcomes.</p>
            <p>I hold the <em>BCS Foundation Certificate in Business Analysis</em>, <em>Scrum Fundamentals Certified (SFC)</em>, <em>UiPath Automation BA Diploma</em> and <em>14 industry certifications</em> spanning AI, data science, business analysis and project management.</p>
          </div>

          <div class="ea-panel">
            <span class="ea-eyebrow">Notable Achievements</span>
            <div class="ea-ach-grid">
              <div class="ea-ach-item"><span class="ea-ach-icon">✅</span><span class="ea-ach-text">Reduced device turnaround time for testing by <strong>25%</strong> through lab workflow optimisation at Infosys</span></div>
              <div class="ea-ach-item"><span class="ea-ach-icon">✅</span><span class="ea-ach-text">Increased stakeholder satisfaction by <strong>35%</strong> by capturing 25+ requirements in a structured BRD (Toucan Technology)</span></div>
              <div class="ea-ach-item"><span class="ea-ach-icon">✅</span><span class="ea-ach-text">Accelerated system adoption by <strong>50%</strong> through structured change management and training delivery</span></div>
              <div class="ea-ach-item"><span class="ea-ach-icon">✅</span><span class="ea-ach-text">Achieved <strong>98% UAT acceptance rate</strong> on Digital Rewards Platform deployment (University of East Anglia)</span></div>
              <div class="ea-ach-item"><span class="ea-ach-icon">✅</span><span class="ea-ach-text">Reduced manual workflow effort by <strong>30%</strong> via Power Automate automation (BNPL Platform, Testlio)</span></div>
              <div class="ea-ach-item"><span class="ea-ach-icon">✅</span><span class="ea-ach-text">Enhanced streaming experience for over <strong>750,000 NOW customers</strong> across Europe (Sky)</span></div>
            </div>
          </div>

          <div class="ea-sectors">
            <span class="ea-sec-label">Domain Experience</span>
            <div class="ea-sec-tags">
              <span class="ea-sec-tag">Healthcare Operations</span>
              <span class="ea-sec-tag">Digital &amp; Web Platforms</span>
              <span class="ea-sec-tag">Mobile Application Development</span>
              <span class="ea-sec-tag">E-Commerce &amp; Payment Solutions</span>
              <span class="ea-sec-tag">Streaming &amp; Media Platforms</span>
              <span class="ea-sec-tag">Enterprise Process Improvement</span>
              <span class="ea-sec-tag">Banking &amp; Financial Services</span>
              <span class="ea-sec-tag">AI &amp; Intelligent Systems</span>
            </div>
          </div>

          <div class="ea-comp-wrap">
            <span class="ea-comp-heading">⚡ Core Competencies</span>
            <div class="ea-comp-grid">
              <div class="ea-comp-card"><span class="ea-comp-label">AI Workflow Automation</span><span class="ea-comp-desc">n8n, AI agent design, Bricks AI, Claude AI, Gemini, Copilot, prompt engineering, agentic AI development</span></div>
              <div class="ea-comp-card"><span class="ea-comp-label">Business Analysis</span><span class="ea-comp-desc">Requirements elicitation, BRD/FRD, stakeholder analysis, process design, solution validation, change enablement</span></div>
              <div class="ea-comp-card"><span class="ea-comp-label">Data Analysis</span><span class="ea-comp-desc">Power BI, SQL analytics, KPI definition, customer &amp; sales data analysis, trend identification, insight reporting</span></div>
              <div class="ea-comp-card"><span class="ea-comp-label">Project Implementation</span><span class="ea-comp-desc">End-to-end digital transformation, business case development, change management, risk registers, UAT, go-live support</span></div>
              <div class="ea-comp-card"><span class="ea-comp-label">Process Improvement</span><span class="ea-comp-desc">AS-IS / TO-BE mapping, operational efficiency, workflow automation, bottleneck resolution, root cause analysis</span></div>
              <div class="ea-comp-card"><span class="ea-comp-label">Software &amp; QA Testing</span><span class="ea-comp-desc">Mobile, web &amp; streaming testing, API testing (Postman, Charles Proxy), defect management, test strategy development</span></div>
              <div class="ea-comp-card"><span class="ea-comp-label">Stakeholder Leadership</span><span class="ea-comp-desc">Executive communication, cross-functional alignment, workshop facilitation, user stories, backlog management</span></div>
              <div class="ea-comp-card"><span class="ea-comp-label">Agile &amp; SDLC</span><span class="ea-comp-desc">Agile/Scrum ceremonies, Waterfall lifecycle, Jira, Confluence, Azure DevOps, TestRail, Asana</span></div>
              <div class="ea-comp-card"><span class="ea-comp-label">AI Governance &amp; Compliance</span><span class="ea-comp-desc">AI governance frameworks, GRC, data labelling, responsible AI implementation, compliance reporting</span></div>
            </div>
          </div>

          <div class="ea-disc">
            <p><strong>📁 Portfolio Disclaimer:</strong> The datasets, analyses and reports presented in this portfolio are synthetic and created solely for demonstration purposes. They do not contain real proprietary, confidential or sensitive information from any company, institution or individual. These examples are designed to showcase technical skills in business analysis, AI automation and data analysis while adhering to ethical guidelines and respecting data privacy.</p>
          </div>

        </div>

        <!-- FEATURED PROJECT -->
        <article class="post featured">
          <header class="major">
            <span class="ea-eyebrow">Featured Project — AI &amp; Workflow Automation • n8n • Conversational Analytics</span>
            <h2><a href="https://docs.google.com/presentation/d/1UN1CHdEXf2DG1EN5onqxRAs6l8lSRja_/edit?usp=sharing" target="_blank" rel="noopener">AI-Powered Data Analyst Agent<br />Workflow Automation</a></h2>
            <p>This workflow automates data analysis and reporting through an intelligent AI agent built in n8n. When a user sends a chat message, the system triggers an AI Data Analyst Agent that leverages a large language model, conversational memory, Google Sheets data access and Gmail integration to analyse data, answer questions, generate insights and communicate results automatically.</p>
          </header>
          <a href="https://docs.google.com/presentation/d/1UN1CHdEXf2DG1EN5onqxRAs6l8lSRja_/edit?usp=sharing" class="shot featured" target="_blank" rel="noopener">
            <span class="shot-label"><i class="fa-solid fa-diagram-project"></i><span>AI Workflow Diagram — view case study</span></span>
          </a>
          <div class="ea-del">
            <span class="ea-del-label">4 Key Deliverables</span>
            <ul>
              <li><strong>Conversational Analytics Interface</strong>Built a chat-driven entry point allowing users to ask questions in plain English without requiring SQL or spreadsheet expertise.</li>
              <li><strong>Context-Aware AI Agent</strong>Implemented conversational memory within the n8n workflow, enabling intelligent follow-up discussions and multi-turn analysis sessions.</li>
              <li><strong>Real-Time Data Integration</strong>Connected the agent directly to Google Sheets for live retrieval of current business data without manual export or refresh steps.</li>
              <li><strong>Automated Insight Delivery</strong>Configured Gmail integration so generated insights and reports are delivered automatically to stakeholders without manual intervention.</li>
            </ul>
          </div>
          <div class="ea-tools">
            <span class="ea-tb">n8n</span><span class="ea-tb">AI Agents</span><span class="ea-tb">Google Sheets</span>
            <span class="ea-tb">Gmail Integration</span><span class="ea-tb">Workflow Automation</span><span class="ea-tb">Conversational Analytics</span>
          </div>
          <ul class="actions special">
            <li><a href="https://docs.google.com/presentation/d/1UN1CHdEXf2DG1EN5onqxRAs6l8lSRja_/edit?usp=sharing" class="button large" target="_blank" rel="noopener">View Full Case Study</a></li>
          </ul>
        </article>

        <!-- PROJECT GRID -->
        <section class="posts">

          <article>
            <header>
              <span class="ea-eyebrow">FMCG — Process Improvement • Requirements Analysis</span>
              <h2><a href="https://docs.google.com/presentation/d/1juuA6rW3yZ35jmI7QR97RT-dPHlLO51x/htmlpresent" target="_blank" rel="noopener">Online Canteen Ordering System<br />Unilever PLC</a></h2>
            </header>
            <a href="https://docs.google.com/presentation/d/1juuA6rW3yZ35jmI7QR97RT-dPHlLO51x/htmlpresent" class="shot" target="_blank" rel="noopener"><span class="shot-label"><i class="fa-solid fa-utensils"></i><span>View Case Study</span></span></a>
            <p>Unilever's 1,500-employee UK office was losing an estimated <strong>35 minutes per employee per lunch break</strong> to canteen queues. I conducted a full BA engagement covering business case, stakeholder mapping, functional specifications and a RACI-governed project plan to design a digital ordering solution.</p>
            <div class="ea-del">
              <span class="ea-del-label">4 Key Deliverables</span>
              <ul>
                <li><strong>Business Case with ROI Projection</strong>£200k total investment with cost-benefit analysis across Years 0–6, Year 5 break-even identified and 45% food waste reduction projected as primary non-financial benefit.</li>
                <li><strong>Stakeholder Analysis &amp; RACI Matrix</strong>12-stakeholder engagement register with Power/Interest quadrant mapping, paired with a 9-activity RACI matrix governing all project phases.</li>
                <li><strong>Functional Requirements &amp; Use Case Diagram</strong>Front-end features for Employee and Canteen Staff user groups plus backend requirements: GDPR compliance, RBAC, inventory management and integration APIs.</li>
                <li><strong>Options Analysis &amp; Risk Register</strong>Three-option evaluation (Do Nothing / Expand Canteen / Digital System), digital solution recommended, 9 risks documented with likelihood ratings and mitigations.</li>
              </ul>
            </div>
            <div class="ea-tools">
              <span class="ea-tb">Jira</span><span class="ea-tb">Confluence</span><span class="ea-tb">SWOT Analysis</span>
              <span class="ea-tb">RACI Matrix</span><span class="ea-tb">Use Case Diagrams</span>
              <span class="ea-tb">Business Case</span><span class="ea-tb">Requirements Elicitation</span>
            </div>
            <ul class="actions special"><li><a href="https://docs.google.com/presentation/d/1juuA6rW3yZ35jmI7QR97RT-dPHlLO51x/htmlpresent" class="button" target="_blank" rel="noopener">View Case Study</a></li></ul>
          </article>

          <article>
            <header>
              <span class="ea-eyebrow">Healthcare — Patient Experience • Root Cause Analysis • KPI Reporting</span>
              <h2><a href="https://drive.google.com/file/d/1GaHglbZCQ8CWkybN6NNxP4NVtr9UbKVN/view?usp=drive_link" target="_blank" rel="noopener">Patient Experience Improvement<br />Barnet Hospital</a></h2>
            </header>
            <a href="https://drive.google.com/file/d/1GaHglbZCQ8CWkybN6NNxP4NVtr9UbKVN/view?usp=drive_link" class="shot" target="_blank" rel="noopener"><span class="shot-label"><i class="fa-solid fa-hospital"></i><span>View Case Study</span></span></a>
            <p>Barnet Hospital faced rising patient complaints and operational bottlenecks. I analysed root causes across wait times, resource allocation and communication, producing a structured improvement report with a visual analytics dashboard for NHS Trust leadership.</p>
            <div class="ea-del">
              <span class="ea-del-label">4 Key Deliverables</span>
              <ul>
                <li><strong>Root Cause Analysis Report</strong>Fishbone analysis identifying operational drivers — staffing gaps, inefficient triage, poor discharge planning — behind declining patient satisfaction scores.</li>
                <li><strong>Stakeholder Impact &amp; Communication Plan</strong>Power/interest mapping of clinical staff, ward managers, administration and NHS Trust leadership with a structured engagement strategy.</li>
                <li><strong>Resource Allocation Review &amp; Gap Analysis</strong>Staffing and bed capacity analysis against patient flow demand, identifying peak bottleneck windows and under-resourced departments.</li>
                <li><strong>Performance Dashboard &amp; KPI Framework</strong>Visual dashboard tracking average wait time, complaint resolution rate and patient satisfaction score for ongoing NHS Trust monitoring.</li>
              </ul>
            </div>
            <div class="ea-tools">
              <span class="ea-tb">Root Cause Analysis</span><span class="ea-tb">Stakeholder Mapping</span>
              <span class="ea-tb">Gap Analysis</span><span class="ea-tb">Power BI</span><span class="ea-tb">KPI Framework</span>
            </div>
            <ul class="actions special"><li><a href="https://drive.google.com/file/d/1GaHglbZCQ8CWkybN6NNxP4NVtr9UbKVN/view?usp=drive_link" class="button" target="_blank" rel="noopener">View Case Study</a></li></ul>
          </article>

          <article>
            <header>
              <span class="ea-eyebrow">Aviation — SDLC • Power BI • Customer Analytics</span>
              <h2><a href="https://drive.google.com/file/d/10BTBwSQoEPg2dIpFB_DdvK8jdYBmUISD/view?usp=drive_link" target="_blank" rel="noopener">Customer Satisfaction Analysis<br />British Airways</a></h2>
            </header>
            <a href="https://drive.google.com/file/d/10BTBwSQoEPg2dIpFB_DdvK8jdYBmUISD/view?usp=drive_link" class="shot" target="_blank" rel="noopener"><span class="shot-label"><i class="fa-solid fa-plane"></i><span>View Case Study</span></span></a>
            <p>British Airways sought to boost customer satisfaction and reduce churn. This SDLC-structured engagement used Power BI to transform raw customer review data into strategic intelligence, delivering an interactive dashboard and prioritised service improvement recommendations.</p>
            <div class="ea-del">
              <span class="ea-del-label">4 Key Deliverables</span>
              <ul>
                <li><strong>SDLC-Structured Business Requirements Document</strong>Full BRD covering problem definition, requirements elicitation, system scope, data inputs, sign-off criteria and success metrics.</li>
                <li><strong>Customer Satisfaction Trend Analysis</strong>Multi-dimensional review analysis across in-flight, check-in, baggage and cabin crew touchpoints to surface trends and key satisfaction drivers.</li>
                <li><strong>Interactive Power BI Dashboard</strong>Multi-page report with DAX measures for satisfaction scores by route, passenger class, time period and complaint category with year-on-year drill-through.</li>
                <li><strong>Strategic Recommendations Report</strong>Three prioritised recommendations targeting highest-impact improvement areas with supporting data evidence and expected outcomes.</li>
              </ul>
            </div>
            <div class="ea-tools">
              <span class="ea-tb">Power BI</span><span class="ea-tb">DAX</span><span class="ea-tb">SDLC</span>
              <span class="ea-tb">BRD</span><span class="ea-tb">Customer Analytics</span><span class="ea-tb">Excel</span>
            </div>
            <ul class="actions special"><li><a href="https://drive.google.com/file/d/10BTBwSQoEPg2dIpFB_DdvK8jdYBmUISD/view?usp=drive_link" class="button" target="_blank" rel="noopener">View Case Study</a></li></ul>
          </article>

          <article>
            <header>
              <span class="ea-eyebrow">Retail — Customer Behaviour • Excel • Dashboard</span>
              <h2><a href="https://drive.google.com/file/d/1ahx2_1qc_NMo2cbpSGs7CiSh-OaEsIO8/view?usp=drive_link" target="_blank" rel="noopener">E-Commerce Behaviour Analysis<br />ABC Retail</a></h2>
            </header>
            <a href="https://drive.google.com/file/d/1ahx2_1qc_NMo2cbpSGs7CiSh-OaEsIO8/view?usp=drive_link" class="shot" target="_blank" rel="noopener"><span class="shot-label"><i class="fa-solid fa-cart-shopping"></i><span>View Case Study</span></span></a>
            <p>ABC Retail needed to understand how customers navigated their online store. Using advanced Excel analysis, I uncovered purchasing patterns, revenue leakage and basket abandonment to guide the team's e-commerce strategy.</p>
            <div class="ea-del">
              <span class="ea-del-label">4 Key Deliverables</span>
              <ul>
                <li><strong>Customer Segmentation Analysis</strong>Segmentation by purchase frequency, order value and preference — high-value, at-risk and low-engagement customer groups identified.</li>
                <li><strong>Basket Abandonment &amp; Drop-Off Analysis</strong>Funnel mapping identifying abandonment stages, revenue impact and product categories most associated with drop-off.</li>
                <li><strong>Sales Performance &amp; Revenue Trend Report</strong>Peak revenue windows, underperforming categories and cross-sell opportunities surfaced with ranked optimisation recommendations.</li>
                <li><strong>Interactive Excel Dashboard</strong>Dynamic filter-driven dashboard consolidating sales by category, customer frequency, monthly revenue trends and conversion indicators.</li>
              </ul>
            </div>
            <div class="ea-tools">
              <span class="ea-tb">Microsoft Excel</span><span class="ea-tb">Pivot Tables</span>
              <span class="ea-tb">Customer Segmentation</span><span class="ea-tb">Funnel Analysis</span>
            </div>
            <ul class="actions special"><li><a href="https://drive.google.com/file/d/1ahx2_1qc_NMo2cbpSGs7CiSh-OaEsIO8/view?usp=drive_link" class="button" target="_blank" rel="noopener">View Case Study</a></li></ul>
          </article>

          <article>
            <header>
              <span class="ea-eyebrow">Retail — AI-Assisted Analytics • Multi-Region • Operations</span>
              <h2><a href="https://docs.google.com/presentation/d/17hYFk1qGSngOOcuW-t7YEx2wMuFA_L-k/edit?usp=drive_link" target="_blank" rel="noopener">Sales &amp; Shipping Performance<br />MiniMart</a></h2>
            </header>
            <a href="https://docs.google.com/presentation/d/17hYFk1qGSngOOcuW-t7YEx2wMuFA_L-k/edit?usp=drive_link" class="shot" target="_blank" rel="noopener"><span class="shot-label"><i class="fa-solid fa-truck-fast"></i><span>View Case Study</span></span></a>
            <p>MiniMart, a mid-sized multi-region retailer, faced challenges in sales and shipping. I leveraged Julius AI and NotebookLM to examine datasets, identify operational gaps and deliver a structured improvement roadmap to leadership.</p>
            <div class="ea-del">
              <span class="ea-del-label">4 Key Deliverables</span>
              <ul>
                <li><strong>AI-Assisted Multi-Region Sales Analysis</strong>Julius AI interrogation of regional datasets — performance variances, top product lines, seasonal demand patterns and channel returns identified.</li>
                <li><strong>Shipping &amp; Logistics Bottleneck Report</strong>Dispatch lag, carrier performance issues and regional volume imbalances mapped as root causes of delivery delays and cost overruns.</li>
                <li><strong>Insight Synthesis via NotebookLM</strong>Cross-referencing of sales, logistics and operational context to surface the most actionable business insights from multiple data sources.</li>
                <li><strong>Prioritised Improvement Roadmap</strong>Actions ranked by ease of implementation and projected impact — clear phased plan delivered to leadership for execution.</li>
              </ul>
            </div>
            <div class="ea-tools">
              <span class="ea-tb">Julius AI</span><span class="ea-tb">NotebookLM</span>
              <span class="ea-tb">Multi-Region Analysis</span><span class="ea-tb">Data Storytelling</span>
            </div>
            <ul class="actions special"><li><a href="https://docs.google.com/presentation/d/17hYFk1qGSngOOcuW-t7YEx2wMuFA_L-k/edit?usp=drive_link" class="button" target="_blank" rel="noopener">View Case Study</a></li></ul>
          </article>

          <article>
            <header>
              <span class="ea-eyebrow">Electronics Retail — SQL • Database Design • Inventory Intelligence</span>
              <h2><a href="https://drive.google.com/file/d/1s3ZMPtKP44GCr2IomBSU6I4Tq1okRgHy/view?usp=drive_link" target="_blank" rel="noopener">Sales &amp; Inventory Intelligence<br />Tech Haven Electronics</a></h2>
            </header>
            <a href="https://drive.google.com/file/d/1s3ZMPtKP44GCr2IomBSU6I4Tq1okRgHy/view?usp=drive_link" class="shot" target="_blank" rel="noopener"><span class="shot-label"><i class="fa-solid fa-database"></i><span>View Case Study</span></span></a>
            <p>Tech Haven Electronics needed to unlock the intelligence in their transactional data. I designed a relational database and built structured SQL queries to surface customer purchasing patterns, dormant inventory and product-level revenue performance.</p>
            <div class="ea-del">
              <span class="ea-del-label">4 Key Deliverables</span>
              <ul>
                <li><strong>Relational Database Schema Design</strong>Normalised database storing customer, product, sales and transaction data — a clean, query-ready foundation for all analysis.</li>
                <li><strong>Customer Purchase History Query Set</strong>SQL joins producing complete per-customer sales histories to support VIP identification and personalised marketing.</li>
                <li><strong>Zero-Sales Product Identification Report</strong>Dormant stock prioritised report enabling inventory rationalisation and holding cost reduction.</li>
                <li><strong>Product &amp; Revenue Performance Analysis</strong>Aggregation queries ranking sales volume, total revenue and average selling price by product and category.</li>
              </ul>
            </div>
            <div class="ea-tools">
              <span class="ea-tb">SQL</span><span class="ea-tb">Database Design</span>
              <span class="ea-tb">Relational Modelling</span><span class="ea-tb">Inventory Analysis</span>
            </div>
            <ul class="actions special"><li><a href="https://drive.google.com/file/d/1s3ZMPtKP44GCr2IomBSU6I4Tq1okRgHy/view?usp=drive_link" class="button" target="_blank" rel="noopener">View Case Study</a></li></ul>
          </article>

          <article class="ea-span-full">
            <header>
              <span class="ea-eyebrow">Process Mapping — AS-IS Documentation • Lucidchart • BPMN</span>
              <h2><a href="https://drive.google.com/file/d/19s4frrg5ytryMOLUrKW7JgOo7L-5IQHS/view?usp=sharing" target="_blank" rel="noopener">Travel Expense Reimbursement<br />AS-IS Process Mapping</a></h2>
            </header>
            <a href="https://drive.google.com/file/d/19s4frrg5ytryMOLUrKW7JgOo7L-5IQHS/view?usp=sharing" class="shot" target="_blank" rel="noopener"><span class="shot-label"><i class="fa-solid fa-diagram-project"></i><span>View Case Study</span></span></a>
            <p>This project documented the complete AS-IS workflow for employee travel expense reimbursement using Lucidchart swimlane diagrams — exposing friction in the approval chain and forming the analytical baseline for a TO-BE process redesign.</p>
            <div class="ea-del">
              <span class="ea-del-label">4 Key Deliverables</span>
              <ul>
                <li><strong>AS-IS Swimlane Process Map</strong>Complete Lucidchart diagram across Employee, Line Manager, Finance and Payroll roles with all steps, gateways and data flows in BPMN notation.</li>
                <li><strong>Process Narrative &amp; Step-by-Step Documentation</strong>Trigger event, submission method, approval routing, finance review criteria and payroll processing steps documented for training use.</li>
                <li><strong>Pain Point Register &amp; Friction Analysis</strong>Key AS-IS inefficiencies ranked by business impact: ambiguous approvals, manual submissions, lack of status visibility and inconsistent timescales.</li>
                <li><strong>Baseline &amp; Scope for TO-BE Redesign</strong>In-scope boundaries, exclusions, process owner and specific pain points the TO-BE redesign must address — formalised as the improvement baseline.</li>
              </ul>
            </div>
            <div class="ea-tools">
              <span class="ea-tb">Lucidchart</span><span class="ea-tb">BPMN</span>
              <span class="ea-tb">Swimlane Diagrams</span><span class="ea-tb">AS-IS Analysis</span>
            </div>
            <ul class="actions special"><li><a href="https://drive.google.com/file/d/19s4frrg5ytryMOLUrKW7JgOo7L-5IQHS/view?usp=sharing" class="button" target="_blank" rel="noopener">View Case Study</a></li></ul>
          </article>

        </section>

        <!-- SKILLS -->
        <div class="ea-skills-wrap">
          <span class="ea-eyebrow">Skills &amp; Toolkit</span>
          <h2>What I Bring to the Table</h2>
          <span class="ea-skills-sub">AI automation, structured BA methodology and modern data tools — applied across 10+ years of real-world industry delivery.</span>
          <div class="ea-sk-grid">
            <div class="ea-sk-card"><span class="ea-sk-icon">🤖</span><span class="ea-sk-title">AI &amp; Workflow Automation</span><ul class="ea-sk-list"><li>n8n Workflow Automation</li><li>AI Agent Design &amp; Implementation</li><li>Bricks AI / Claude AI / Gemini</li><li>Prompt Engineering for BA Tasks</li><li>Agentic AI Development</li><li>AI Tool Evaluation &amp; Integration</li></ul></div>
            <div class="ea-sk-card"><span class="ea-sk-icon">🎯</span><span class="ea-sk-title">Business Analysis</span><ul class="ea-sk-list"><li>Requirements Elicitation &amp; BRD/FRD</li><li>Stakeholder Analysis &amp; Management</li><li>User Stories &amp; Acceptance Criteria</li><li>Gap Analysis &amp; SWOT</li><li>RACI Matrix &amp; Business Case Writing</li><li>Solution Validation &amp; Change Enablement</li></ul></div>
            <div class="ea-sk-card"><span class="ea-sk-icon">📊</span><span class="ea-sk-title">Data Analysis</span><ul class="ea-sk-list"><li>Power BI &amp; DAX</li><li>Microsoft Excel (Advanced)</li><li>SQL &amp; Database Design</li><li>KPI Definition &amp; Measurement</li><li>Trend Identification &amp; Forecasting</li><li>Insight-to-Action Reporting</li></ul></div>
            <div class="ea-sk-card"><span class="ea-sk-icon">🚀</span><span class="ea-sk-title">Project Implementation</span><ul class="ea-sk-list"><li>End-to-End Digital Transformation</li><li>Business Case Development</li><li>Change Management &amp; Adoption</li><li>Risk Register &amp; Issue Log</li><li>UAT Planning &amp; Sign-Off</li><li>Go-Live Support &amp; Hypercare</li></ul></div>
            <div class="ea-sk-card"><span class="ea-sk-icon">🔄</span><span class="ea-sk-title">Process Improvement</span><ul class="ea-sk-list"><li>AS-IS / TO-BE Process Mapping</li><li>Swimlane Diagrams (BPMN)</li><li>Lucidchart</li><li>Root Cause Analysis</li><li>Workflow Optimisation</li><li>Bottleneck Identification</li></ul></div>
            <div class="ea-sk-card"><span class="ea-sk-icon">🧪</span><span class="ea-sk-title">Software &amp; QA Testing</span><ul class="ea-sk-list"><li>Functional &amp; Non-Functional Testing</li><li>API Testing — Postman</li><li>Charles Proxy</li><li>Mobile, Web &amp; Streaming Testing</li><li>UAT Coordination &amp; Sign-Off</li><li>Defect Management &amp; Triage</li></ul></div>
            <div class="ea-sk-card"><span class="ea-sk-icon">🛠</span><span class="ea-sk-title">Agile &amp; Collaboration</span><ul class="ea-sk-list"><li>Jira — Backlog &amp; Sprint Management</li><li>Confluence Documentation</li><li>Azure DevOps &amp; TestRail</li><li>Agile / Scrum &amp; Waterfall SDLC</li><li>Asana &amp; Workshop Facilitation</li><li>Cross-Functional Team Alignment</li></ul></div>
            <div class="ea-sk-card"><span class="ea-sk-icon">🏛</span><span class="ea-sk-title">Domain Experience</span><ul class="ea-sk-list"><li>Healthcare &amp; Digital Transformation</li><li>Streaming &amp; Media Platforms</li><li>E-Commerce &amp; Payment Solutions</li><li>Banking &amp; Financial Services</li><li>Enterprise Process Improvement</li><li>Mobile Application Development</li></ul></div>
            <div class="ea-sk-card"><span class="ea-sk-icon">🏆</span><span class="ea-sk-title">Certifications</span><ul class="ea-sk-list"><li>BCS Foundation Cert in Business Analysis</li><li>Scrum Fundamentals Certified (SFC)</li><li>UiPath Automation BA Diploma</li><li>365 Data Science — AI &amp; AI Agents</li><li>IBM &amp; Microsoft BA Fundamentals</li><li>Testlio — Testing AI-Powered Systems</li></ul></div>
          </div>
        </div>

      </div>

      <!-- FOOTER -->
      <footer id="footer">
        <section class="split contact">
          <section class="alt">
            <h3>Location</h3>
            <p>Darlington, UK<br /><em style="font-size:0.8rem;opacity:0.7;">Open to Remote &amp; Hybrid Roles Nationwide</em></p>
          </section>
          <section>
            <h3>Email</h3>
            <p><a href="mailto:eoaadenuga@gmail.com">eoaadenuga@gmail.com</a></p>
          </section>
          <section>
            <h3>Connect</h3>
            <ul class="icons">
              <li><a href="https://www.linkedin.com/in/emmanuel-adenuga/" target="_blank" rel="noopener" title="LinkedIn"><i class="fab fa-linkedin"></i></a></li>
              <li><a href="https://github.com/eoaadenuga/" target="_blank" rel="noopener" title="GitHub"><i class="fab fa-github"></i></a></li>
            </ul>
          </section>
        </section>
      </footer>
      <div id="copyright">
        <ul><li>© 2025 Emmanuel Adenuga</li><li>AI Automation Business Analyst — Darlington, UK</li></ul>
      </div>

    </div>
  </body>
</html>
