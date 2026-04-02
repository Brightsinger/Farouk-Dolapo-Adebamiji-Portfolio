import { useState, useEffect, useRef } from "react";

// ============================================================
// ✏️  EDIT ALL YOUR PORTFOLIO DATA HERE — NO CODE KNOWLEDGE NEEDED
// ============================================================

const SITE_DATA = {
  name: "Farouk Adebamiji",
  title: "Strategic Operations & Content Partner",
  tagline: "I build content engines and automate workflows that scale your voice.",
  subtagline:
    "Deep storytelling meets mid-level n8n & AI automation — I don't just write copy, I build the systems that deliver it consistently, at scale.",
  email: "faroukadebamiji6@gmail.com",
  phone: "+234 701 255 4756",
  location: "Osogbo, Osun State, Nigeria",
  linkedin: "https://linkedin.com/in/faroukadebamiji",
  github: "https://github.com/faroukadebamiji",

  about: {
    headline: "The Rare Crossover Between Craft and Systems Thinking",
    body: `Most content people are great at words. Most automation people are great at workflows. I sit in the rare intersection of both — trained in Mass Communication to understand human behaviour and narrative, then self-taught in n8n, AI tools, and web development to systemise what I create.

My 3+ years working across mental health advocacy, food brands, school media, and NYSC programmes taught me that the best content strategy in the world is useless without the infrastructure to deliver it. So I built that infrastructure myself.

Today, I partner with founders and small teams who are talented but overwhelmed — helping them turn scattered content efforts into coherent, semi-automated operations that run while they sleep.`,
    stats: [
      { value: "3+", label: "Years creating content" },
      { value: "50K+", label: "Cumulative video views" },
      { value: "828+", label: "Organic post views" },
      { value: "40%", label: "Avg. engagement lift" },
    ],
  },

  services: [
    {
      id: "content",
      number: "01",
      title: "Strategic Content Creation",
      description:
        "Brand storytelling, marketing copy, and social media management built around your audience's psychology. Not just words — narratives that convert.",
      details: [
        "Long-form articles & thought leadership",
        "Social media strategy & management",
        "Marketing copywriting & campaigns",
        "Brand voice development",
        "Video scripts & content planning",
      ],
    },
    {
      id: "automation",
      number: "02",
      title: "AI & Workflow Automation",
      description:
        "n8n pipelines, custom LLM integrations, and task automation that eliminate repetitive manual work so you focus on what only you can do.",
      details: [
        "n8n workflow design & deployment",
        "LLM-enhanced content pipelines",
        "Cross-platform data automation",
        "Scheduled publishing systems",
        "AI-assisted research workflows",
      ],
    },
    {
      id: "infrastructure",
      number: "03",
      title: "Digital Infrastructure",
      description:
        "WordPress and basic web development to give your brand a professional digital home. Clean, fast, and built to grow with you.",
      details: [
        "WordPress site development",
        "Landing page build & optimisation",
        "Basic HTML/CSS customisation",
        "Supabase & database setup",
        "Operations documentation (SOPs)",
      ],
    },
  ],

  auditItems: [
    {
      id: 1,
      label: "I spend 1–2 hours daily manually scheduling or posting content.",
      hours: 10,
    },
    {
      id: 2,
      label: "I manually copy-paste lead or client data between platforms.",
      hours: 7,
    },
    {
      id: 3,
      label: "My team has no standardised SOPs or documented workflows.",
      hours: 5,
    },
    {
      id: 4,
      label: "My inbox chaos costs me follow-ups and missed opportunities.",
      hours: 8,
    },
    {
      id: 5,
      label: "I produce content inconsistently because planning takes too long.",
      hours: 6,
    },
    {
      id: 6,
      label: "I have no automated way to repurpose content across platforms.",
      hours: 4,
    },
  ],

  projects: [
    {
      id: 1,
      title: "Luscious Chow — Brand Storytelling Campaign",
      category: "Content",
      categoryColor: "sage",
      problem:
        "A Lagos bread and pastries brand needed marketing copy that connected emotionally with young urban professionals, not just product descriptions.",
      strategy:
        "Used relatable urban pain points (traffic, exhaustion, rushed mornings) as entry points into storytelling narratives. Created the 'Chowppers' community concept to build recurring brand identity.",
      results:
        "828+ organic views and 23+ likes on launch posts. Established a brand voice framework used for subsequent campaigns.",
      tags: ["Copywriting", "Brand Storytelling", "Social Media"],
      metrics: { views: "828+ views", likes: "23+ likes" },
    },
    {
      id: 2,
      title: "St Gregory's College — Media Production System",
      category: "Content",
      categoryColor: "terracotta",
      problem:
        "The school had no consistent visual identity across video content. Events were documented inconsistently with no clear publishing workflow.",
      strategy:
        "Implemented a brand visual identity system for all video content. Created a 48-hour turnaround SOP for event coverage and established a consistent posting cadence.",
      results:
        "12,000+ total views on school social channels. 35% improvement in parent engagement. 100% on-time delivery across 30+ events.",
      tags: ["Video Production", "Brand Identity", "SOPs"],
      metrics: { views: "12K+ views", engagement: "+35% engagement" },
    },
    {
      id: 3,
      title: "Voice Unbound — Thought Leadership Blog",
      category: "Content",
      categoryColor: "sage",
      problem:
        "Building a credible personal brand in Nigerian youth mental health while maintaining consistent content output as a solo creator.",
      strategy:
        "Developed a content calendar anchored in three pillars: mental health, masculinity, and post-graduation realities. Used data-driven topic selection from Instagram analytics.",
      results:
        "200–2,000+ views per post. 15+ published articles. Established as a recognisable voice in mental health for Nigerian youth.",
      tags: ["Thought Leadership", "Content Strategy", "Analytics"],
      metrics: { views: "2K+ per post", articles: "15+ articles" },
    },
    {
      id: 4,
      title: "BTR Media Institute — Vlog Production Pipeline",
      category: "Operations",
      categoryColor: "terracotta",
      problem:
        "A 5-person media team had scheduling conflicts, inconsistent episode quality, and no standardised production workflow causing missed deadlines.",
      strategy:
        "Mapped the entire production pipeline from ideation to publish. Created scheduling templates and resource allocation systems. Built a repeatable research-and-outline scripting framework.",
      results:
        "50,000+ cumulative views. 28% subscriber growth QoQ. 40% reduction in scheduling conflicts. 100% on-time content delivery.",
      tags: ["Pipeline Design", "Script Writing", "Team Coordination"],
      metrics: { views: "50K+ views", growth: "+28% subscribers" },
    },
  ],

  testimonials: [
    {
      quote:
        "Farouk understood our brand voice immediately. The campaign copy felt like it came from inside the brand — not from an outsider.",
      name: "Brand Client",
      role: "Luscious Chow, Lagos",
    },
    {
      quote:
        "His ability to take a brief, build a narrative, and deliver clean video content within 48 hours was invaluable during our busiest terms.",
      name: "School Administration",
      role: "St Gregory's College, Ondo State",
    },
  ],

  navLinks: [
    { label: "About", href: "#about" },
    { label: "Services", href: "#services" },
    { label: "Work", href: "#work" },
    { label: "Audit", href: "#audit" },
  ],
};

// ============================================================
// DESIGN TOKENS & GLOBAL STYLES
// ============================================================
const STYLES = `
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400;1,600&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;0,9..40,600;1,9..40,300&display=swap');

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg:           #F8F5F0;
    --bg-white:     #FFFFFF;
    --bg-warm:      #F2EDE6;
    --text:         #2A2520;
    --text-2:       #6B6258;
    --text-3:       #9C948D;
    --accent:       #C85A3A;
    --accent-dk:    #A6452B;
    --accent-lt:    #F5E8E4;
    --sage:         #7A9B8E;
    --sage-lt:      #EBF2EF;
    --border:       #E8E3DC;
    --border-dk:    #D4CDC4;
    --font-d:       'Playfair Display', Georgia, serif;
    --font-b:       'DM Sans', system-ui, sans-serif;
    --ease:         cubic-bezier(0.16, 1, 0.3, 1);
    --r:            4px;
  }

  html { scroll-behavior: smooth; font-size: 16px; }

  body {
    font-family: var(--font-b);
    background: var(--bg);
    color: var(--text);
    -webkit-font-smoothing: antialiased;
    overflow-x: hidden;
  }

  ::-webkit-scrollbar { width: 4px; }
  ::-webkit-scrollbar-track { background: var(--bg); }
  ::-webkit-scrollbar-thumb { background: var(--border-dk); border-radius: 2px; }
  ::-webkit-scrollbar-thumb:hover { background: var(--text-3); }

  /* ---- Scroll reveal ---- */
  .rv {
    opacity: 0;
    transform: translateY(24px);
    transition: opacity 0.7s var(--ease), transform 0.7s var(--ease);
  }
  .rv.in { opacity: 1; transform: none; }
  .d1 { transition-delay: 0.08s; }
  .d2 { transition-delay: 0.18s; }
  .d3 { transition-delay: 0.28s; }
  .d4 { transition-delay: 0.38s; }

  /* ---- Keyframes ---- */
  @keyframes fadeUp   { from { opacity:0; transform:translateY(20px); } to { opacity:1; transform:none; } }
  @keyframes fadeIn   { from { opacity:0; } to { opacity:1; } }
  @keyframes pulse    { 0%,100%{opacity:1;} 50%{opacity:.45;} }
  @keyframes slideIn  { from{opacity:0;transform:translateY(12px);} to{opacity:1;transform:none;} }

  /* ---- Nav ---- */
  #pf-nav {
    position: fixed; top:0; left:0; right:0; z-index:200;
    height: 66px;
    display: flex; align-items: center;
    background: rgba(248,245,240,.88);
    backdrop-filter: blur(16px);
    -webkit-backdrop-filter: blur(16px);
    border-bottom: 1px solid transparent;
    transition: border-color .3s, background .3s;
  }
  #pf-nav.s { border-bottom-color: var(--border); background: rgba(248,245,240,.96); }
  .nav-in {
    max-width: 1200px; margin: 0 auto; width: 100%;
    padding: 0 48px;
    display: flex; align-items: center; justify-content: space-between;
  }
  .nav-logo {
    font-family: var(--font-d); font-size: 19px; font-weight: 700;
    color: var(--text); text-decoration: none; letter-spacing: -.4px;
  }
  .nav-logo b { color: var(--accent); }
  .nav-links { display:flex; align-items:center; gap:32px; }
  .nav-links a {
    font-size: 13.5px; font-weight: 500; color: var(--text-2);
    text-decoration: none; letter-spacing:.2px; transition: color .2s;
  }
  .nav-links a:hover { color: var(--text); }
  .nav-cta {
    background: var(--accent) !important; color: white !important;
    padding: 8px 20px; border-radius: var(--r);
    font-size: 13px !important; font-weight: 600 !important;
    transition: background .2s !important;
  }
  .nav-cta:hover { background: var(--accent-dk) !important; }

  /* ---- Common ---- */
  .wrap { max-width: 1200px; margin: 0 auto; }
  .sec { padding: 104px 48px; }
  .sec-tag {
    font-size: 11px; font-weight: 600; letter-spacing: 2px;
    text-transform: uppercase; color: var(--accent);
    display: flex; align-items: center; gap: 10px; margin-bottom: 14px;
  }
  .sec-tag::before { content:''; width:20px; height:1px; background:var(--accent); display:block; }
  .sec-h {
    font-family: var(--font-d);
    font-size: clamp(28px,3.5vw,44px);
    font-weight: 700; line-height: 1.12; letter-spacing: -.8px;
    color: var(--text);
  }
  .sec-h em { font-style: italic; color: var(--accent); }
  .btn-p {
    display: inline-block;
    background: var(--accent); color: white;
    font-family: var(--font-b); font-size: 14px; font-weight: 600;
    padding: 13px 28px; border-radius: var(--r);
    text-decoration: none; letter-spacing: .2px;
    transition: background .25s var(--ease);
  }
  .btn-p:hover { background: var(--accent-dk); }
  .btn-o {
    display: inline-block;
    border: 1.5px solid var(--accent); color: var(--accent);
    font-family: var(--font-b); font-size: 14px; font-weight: 600;
    padding: 13px 28px; border-radius: var(--r);
    text-decoration: none; letter-spacing: .2px;
    transition: background .25s, color .25s;
  }
  .btn-o:hover { background: var(--accent); color: white; }
  .tag {
    font-size: 12px; font-weight: 500;
    padding: 4px 11px; border-radius: 20px;
    background: var(--bg); border: 1px solid var(--border);
    color: var(--text-2);
  }
  .tag-a { background: var(--accent-lt); border-color: rgba(200,90,58,.18); color: var(--accent); }
  .tag-s { background: var(--sage-lt); border-color: rgba(122,155,142,.2); color: var(--sage); }

  /* ---- Hero ---- */
  #hero {
    min-height: 100vh; display:flex; align-items:center;
    padding: 120px 48px 80px; position:relative; overflow:hidden;
  }
  #hero::before {
    content:''; position:absolute; top:-10%; right:-5%;
    width:560px; height:560px; border-radius:50%;
    background: radial-gradient(circle, rgba(200,90,58,.07) 0%, transparent 70%);
    pointer-events:none;
  }
  #hero::after {
    content:''; position:absolute; bottom:0; left:15%;
    width:480px; height:480px; border-radius:50%;
    background: radial-gradient(circle, rgba(122,155,142,.07) 0%, transparent 70%);
    pointer-events:none;
  }
  .hero-grid {
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 72px; align-items: center;
  }
  .hero-eye {
    font-size: 11px; font-weight: 600; letter-spacing: 2px;
    text-transform: uppercase; color: var(--accent);
    display: flex; align-items: center; gap: 10px;
    margin-bottom: 22px;
    animation: fadeIn .7s var(--ease) both;
  }
  .hero-eye::before { content:''; width:24px; height:1px; background:var(--accent); display:block; }
  #hero h1 {
    font-family: var(--font-d);
    font-size: clamp(34px,4.8vw,58px);
    font-weight: 700; line-height: 1.08; letter-spacing: -1.6px;
    margin-bottom: 22px;
    animation: fadeUp .8s .12s var(--ease) both;
  }
  #hero h1 em { font-style:italic; color:var(--accent); }
  .hero-sub {
    font-size: 16.5px; line-height: 1.7; color: var(--text-2);
    max-width: 460px; margin-bottom: 38px; font-weight: 300;
    animation: fadeUp .8s .26s var(--ease) both;
  }
  .hero-btns {
    display:flex; gap:12px; flex-wrap:wrap;
    animation: fadeUp .8s .4s var(--ease) both;
  }
  .hero-r { animation: fadeIn 1s .5s var(--ease) both; }
  .hcard {
    background: var(--bg-white); border: 1px solid var(--border);
    border-radius: 8px; padding: 28px 28px; margin-bottom: 14px;
  }
  .hcard-lbl {
    font-size: 10px; font-weight: 600; letter-spacing: 1.8px;
    text-transform: uppercase; color: var(--text-3); margin-bottom: 14px;
  }
  .stags { display:flex; flex-wrap:wrap; gap:7px; }
  .avail {
    display: inline-flex; align-items: center; gap: 8px;
    font-size: 13px; font-weight: 500;
    color: var(--sage); background: var(--sage-lt);
    border: 1px solid rgba(122,155,142,.25);
    padding: 8px 16px; border-radius: 20px;
    margin-bottom: 16px;
  }
  .dot { width:7px; height:7px; border-radius:50%; background:var(--sage); animation: pulse 2s infinite; }

  /* ---- About ---- */
  #about {
    background: var(--bg-white);
    border-top:1px solid var(--border);
    border-bottom:1px solid var(--border);
  }
  .about-grid { display:grid; grid-template-columns:1fr 1.15fr; gap:72px; align-items:start; }
  .about-body {
    font-size: 15.5px; line-height: 1.78; color: var(--text-2);
    font-weight: 300; white-space:pre-line; margin-top:22px;
  }
  .stats-g {
    display:grid; grid-template-columns:1fr 1fr;
    gap:1px; background:var(--border);
    border:1px solid var(--border); border-radius:8px; overflow:hidden;
    margin-top:36px;
  }
  .stat {
    background: var(--bg-white); padding: 26px 22px;
  }
  .stat-v {
    font-family: var(--font-d); font-size: 38px;
    font-weight: 700; color: var(--accent); line-height:1; margin-bottom:5px;
  }
  .stat-l { font-size: 13px; color: var(--text-3); font-weight:400; line-height:1.4; }
  .pillars { margin-top:36px; }
  .pill-row {
    display:flex; align-items:flex-start; gap:14px;
    padding:18px 0; border-bottom:1px solid var(--border);
  }
  .pill-row:last-child { border-bottom:none; }
  .pill-n { font-family:var(--font-d); font-size:12px; font-weight:700; color:var(--accent); width:22px; flex-shrink:0; padding-top:2px; }
  .pill-t { font-size:14.5px; font-weight:600; color:var(--text); margin-bottom:3px; }
  .pill-d { font-size:13px; color:var(--text-2); line-height:1.55; font-weight:300; }

  /* ---- Services ---- */
  #services { background:var(--bg); }
  .svc-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:20px; margin-top:52px; }
  .svc-card {
    background: var(--bg-white); border:1px solid var(--border); border-radius:8px;
    padding:36px 30px; position:relative; overflow:hidden;
    transition: border-color .3s, box-shadow .3s; cursor:default;
  }
  .svc-card:hover { border-color:var(--accent); box-shadow:0 8px 36px rgba(200,90,58,.07); }
  .svc-bg-num {
    font-family:var(--font-d); font-size:80px; font-weight:700;
    color:var(--border); position:absolute; top:16px; right:20px;
    line-height:1; transition:color .3s; pointer-events:none; user-select:none;
  }
  .svc-card:hover .svc-bg-num { color:rgba(200,90,58,.1); }
  .svc-card h3 {
    font-family:var(--font-d); font-size:21px; font-weight:700;
    color:var(--text); margin-bottom:12px; line-height:1.2; letter-spacing:-.3px;
  }
  .svc-desc { font-size:13.5px; line-height:1.65; color:var(--text-2); font-weight:300; margin-bottom:24px; }
  .svc-list { list-style:none; display:flex; flex-direction:column; gap:8px; }
  .svc-list li {
    font-size:12.5px; color:var(--text-3);
    display:flex; align-items:center; gap:8px;
  }
  .svc-list li::before {
    content:''; width:4px; height:4px; border-radius:50%;
    background:var(--accent); flex-shrink:0;
  }

  /* ---- Audit ---- */
  #audit {
    background:var(--bg-warm);
    border-top:1px solid var(--border); border-bottom:1px solid var(--border);
  }
  .audit-in { max-width:740px; margin:0 auto; }
  .audit-sub {
    font-size: 15px; line-height:1.65; color:var(--text-2); font-weight:300;
    margin-top:16px;
  }
  .audit-list { display:flex; flex-direction:column; gap:9px; margin:36px 0; }
  .ai {
    display:flex; justify-content:space-between; align-items:center;
    padding:16px 20px; background:var(--bg-white);
    border:1.5px solid var(--border); border-radius:6px;
    cursor:pointer; transition:border-color .22s, background .22s, box-shadow .22s;
    user-select:none; gap:16px;
  }
  .ai:hover { border-color:var(--border-dk); }
  .ai.on { border-color:var(--accent); background:var(--accent-lt); box-shadow:0 2px 14px rgba(200,90,58,.1); }
  .ai-txt { font-size:14.5px; font-weight:400; color:var(--text); line-height:1.4; }
  .ai-chk {
    width:22px; height:22px; border-radius:50%;
    border:1.5px solid var(--border-dk);
    display:flex; align-items:center; justify-content:center;
    flex-shrink:0; font-size:11px; color:white;
    transition:background .2s, border-color .2s;
  }
  .ai.on .ai-chk { background:var(--accent); border-color:var(--accent); }
  .audit-res {
    background:var(--text); border-radius:8px; padding:40px 44px;
    text-align:center; animation:slideIn .5s var(--ease) both;
  }
  .ar-lbl {
    font-size:11px; font-weight:600; letter-spacing:1.5px;
    text-transform:uppercase; color:rgba(255,255,255,.4); margin-bottom:10px;
  }
  .ar-hrs {
    font-family:var(--font-d); font-size:80px; font-weight:700;
    color:var(--accent); line-height:1; margin-bottom:6px;
  }
  .ar-sub { font-size:17px; color:rgba(255,255,255,.6); font-weight:300; margin-bottom:32px; }

  /* ---- Projects ---- */
  #work {
    background:var(--bg-white);
    border-top:1px solid var(--border);
  }
  .proj-grid { display:grid; grid-template-columns:1fr 1fr; gap:20px; margin-top:52px; }
  .pcard {
    border:1px solid var(--border); border-radius:8px; overflow:hidden;
    background:var(--bg);
    transition:border-color .3s, box-shadow .3s;
  }
  .pcard:hover { border-color:var(--border-dk); box-shadow:0 8px 28px rgba(42,37,32,.05); }
  .pcard-top { padding:26px 26px 22px; border-bottom:1px solid var(--border); }
  .pcard-meta { display:flex; align-items:center; gap:9px; margin-bottom:14px; flex-wrap:wrap; }
  .cbadge {
    font-size:10px; font-weight:700; letter-spacing:.8px;
    text-transform:uppercase; padding:4px 10px; border-radius:20px;
  }
  .cbadge.terracotta { background:var(--accent-lt); color:var(--accent); }
  .cbadge.sage        { background:var(--sage-lt); color:var(--sage); }
  .mchip {
    font-size:11.5px; font-weight:600; color:var(--text);
    background:var(--bg-white); border:1px solid var(--border);
    padding:3px 9px; border-radius:3px;
  }
  .pcard h3 {
    font-family:var(--font-d); font-size:19px; font-weight:700;
    color:var(--text); line-height:1.22; letter-spacing:-.3px;
  }
  .pcard-body { padding:22px 26px; }
  .psr { margin-bottom:15px; }
  .psr:last-child { margin-bottom:0; }
  .psr-lbl {
    font-size:10px; font-weight:700; letter-spacing:1.5px;
    text-transform:uppercase; color:var(--accent); margin-bottom:4px;
  }
  .psr-txt { font-size:13px; line-height:1.62; color:var(--text-2); font-weight:300; }
  .ptags {
    display:flex; flex-wrap:wrap; gap:6px;
    margin-top:16px; padding-top:16px; border-top:1px solid var(--border);
  }

  /* ---- Testimonials ---- */
  #testi { background:var(--bg); border-top:1px solid var(--border); }
  .tg { display:grid; grid-template-columns:1fr 1fr; gap:20px; margin-top:44px; }
  .tc {
    background:var(--bg-white); border:1px solid var(--border);
    border-radius:8px; padding:34px;
  }
  .tc-q {
    font-family:var(--font-d); font-size:16px; font-style:italic;
    font-weight:400; line-height:1.7; color:var(--text); margin-bottom:22px;
  }
  .tc-a { display:flex; align-items:center; gap:12px; }
  .tc-av {
    width:40px; height:40px; border-radius:50%;
    background:var(--accent-lt); display:flex; align-items:center; justify-content:center;
    font-family:var(--font-d); font-size:16px; font-weight:700; color:var(--accent); flex-shrink:0;
  }
  .tc-name { font-size:14px; font-weight:600; color:var(--text); }
  .tc-role { font-size:12px; color:var(--text-3); margin-top:2px; }

  /* ---- Contact ---- */
  #contact { background:var(--text); }
  #contact .sec-tag { color:var(--accent); }
  #contact .sec-tag::before { background:var(--accent); }
  #contact .sec-h { color:white; }
  .contact-g { display:grid; grid-template-columns:1fr 1fr; gap:72px; margin-top:52px; align-items:start; }
  .contact-desc { font-size:15px; line-height:1.72; color:rgba(255,255,255,.55); font-weight:300; margin-top:18px; }
  .clinks { margin-top:32px; display:flex; flex-direction:column; gap:12px; }
  .clink {
    display:flex; align-items:center; gap:12px;
    color:rgba(255,255,255,.6); font-size:13.5px; font-weight:400;
    text-decoration:none; transition:color .2s;
  }
  .clink:hover { color:white; }
  .clink-i {
    width:34px; height:34px;
    border:1px solid rgba(255,255,255,.12); border-radius:var(--r);
    display:flex; align-items:center; justify-content:center;
    font-size:13px; flex-shrink:0;
    transition:border-color .2s, background .2s;
  }
  .clink:hover .clink-i { border-color:var(--accent); background:rgba(200,90,58,.1); }
  .cform { display:flex; flex-direction:column; gap:14px; }
  .fg { display:flex; flex-direction:column; gap:6px; }
  .fl { font-size:11px; font-weight:500; color:rgba(255,255,255,.4); letter-spacing:.5px; }
  .fi, .fta {
    background:rgba(255,255,255,.06); border:1px solid rgba(255,255,255,.11);
    border-radius:var(--r); padding:12px 15px; color:white;
    font-family:var(--font-b); font-size:14px; font-weight:300;
    outline:none; transition:border-color .2s; resize:none;
  }
  .fi::placeholder,.fta::placeholder { color:rgba(255,255,255,.2); }
  .fi:focus,.fta:focus { border-color:rgba(200,90,58,.5); }
  .fta { min-height:116px; }
  .fsub {
    background:var(--accent); color:white; border:none;
    padding:14px 28px; font-family:var(--font-b); font-size:14px; font-weight:600;
    border-radius:var(--r); cursor:pointer; letter-spacing:.3px;
    align-self:flex-start; transition:background .2s;
  }
  .fsub:hover { background:var(--accent-dk); }
  .fsub:disabled { opacity:.6; cursor:not-allowed; }

  /* ---- Footer ---- */
  #footer {
    background:var(--text);
    border-top:1px solid rgba(255,255,255,.07);
    padding:22px 48px;
  }
  .foot-in {
    max-width:1200px; margin:0 auto;
    display:flex; align-items:center; justify-content:space-between;
  }
  .foot-logo { font-family:var(--font-d); font-size:15px; font-weight:700; color:rgba(255,255,255,.35); }
  .foot-copy { font-size:12px; color:rgba(255,255,255,.2); }
  .foot-links { display:flex; gap:22px; }
  .foot-links a { font-size:12px; color:rgba(255,255,255,.25); text-decoration:none; transition:color .2s; }
  .foot-links a:hover { color:rgba(255,255,255,.65); }

  /* ---- Responsive ---- */
  @media (max-width:960px) {
    .sec { padding:72px 24px; }
    #hero { padding:104px 24px 64px; }
    .hero-grid,.about-grid,.contact-g { grid-template-columns:1fr; gap:40px; }
    .hero-r { display:none; }
    .svc-grid { grid-template-columns:1fr; }
    .proj-grid,.tg { grid-template-columns:1fr; }
    .foot-in { flex-direction:column; gap:10px; text-align:center; }
    #footer { padding:20px 24px; }
    .nav-in { padding:0 24px; }
  }
  @media (max-width:640px) {
    .nav-links { display:none; }
    #hero h1 { font-size:30px; }
    .hero-btns { flex-direction:column; }
    .btn-p,.btn-o { text-align:center; }
    .stats-g { grid-template-columns:1fr 1fr; }
    .ar-hrs { font-size:60px; }
    .audit-res { padding:28px 24px; }
  }
`;

// ============================================================
// Intersection observer hook
// ============================================================
function useReveal() {
  const ref = useRef(null);
  useEffect(() => {
    const el = ref.current;
    if (!el) return;
    const ob = new IntersectionObserver(
      ([e]) => {
        if (e.isIntersecting) {
          el.querySelectorAll(".rv").forEach((n) => n.classList.add("in"));
          ob.unobserve(el);
        }
      },
      { threshold: 0.1 }
    );
    ob.observe(el);
    return () => ob.disconnect();
  }, []);
  return ref;
}

// ============================================================
// NAV
// ============================================================
function Nav() {
  const [sc, setSc] = useState(false);
  useEffect(() => {
    const h = () => setSc(window.scrollY > 20);
    window.addEventListener("scroll", h, { passive: true });
    return () => window.removeEventListener("scroll", h);
  }, []);
  const { name, navLinks, email } = SITE_DATA;
  const ini = name.split(" ").map((w) => w[0]).join("");
  return (
    <nav id="pf-nav" className={sc ? "s" : ""}>
      <div className="nav-in">
        <a href="#hero" className="nav-logo">
          {ini}<b>.</b>
        </a>
        <div className="nav-links">
          {navLinks.map((l) => <a key={l.label} href={l.href}>{l.label}</a>)}
          <a href={`mailto:${email}`} className="nav-cta">Hire Me</a>
        </div>
      </div>
    </nav>
  );
}

// ============================================================
// HERO
// ============================================================
function Hero() {
  const { tagline, subtagline, email } = SITE_DATA;

  // Italicise key action words
  const italics = new Set(["content", "engines", "automate", "workflows", "scale", "voice"]);
  const words = tagline.split(" ");

  return (
    <section id="hero">
      <div className="wrap hero-grid">
        {/* Left */}
        <div>
          <div className="hero-eye">Strategic Operations & Content Partner</div>
          <h1>
            {words.map((w, i) => {
              const clean = w.toLowerCase().replace(/[^a-z]/g, "");
              return italics.has(clean)
                ? <em key={i}>{w}{i < words.length - 1 ? " " : ""}</em>
                : <span key={i}>{w}{i < words.length - 1 ? " " : ""}</span>;
            })}
          </h1>
          <p className="hero-sub">{subtagline}</p>
          <div className="hero-btns">
            <a href="#audit" className="btn-p">Audit My Operations</a>
            <a href="#work" className="btn-o">View Documented Work</a>
          </div>
        </div>

        {/* Right — desktop only */}
        <div className="hero-r">
          <div className="avail"><span className="dot" />Open to new partnerships</div>

          <div className="hcard">
            <div className="hcard-lbl">Core Stack</div>
            <div className="stags">
              {[
                ["Content Strategy","a"],["n8n Automation","a"],["AI Workflows","a"],
                ["WordPress","s"],["Web Dev","s"],["Copywriting",""],
                ["Video Editing",""],["Social Media",""],["Canva / CapCut",""],
                ["Supabase",""],["Graphic Design",""],
              ].map(([t, c]) => (
                <span key={t} className={`tag${c === "a" ? " tag-a" : c === "s" ? " tag-s" : ""}`}>{t}</span>
              ))}
            </div>
          </div>

          <div className="hcard" style={{ display:"flex", justifyContent:"space-between", alignItems:"center" }}>
            <div>
              <div style={{ fontFamily:"var(--font-d)", fontSize:22, fontWeight:700 }}>Farouk Adebamiji</div>
              <div style={{ fontSize:12.5, color:"var(--text-3)", marginTop:4 }}>Osogbo, Nigeria · BSc Mass Communication</div>
            </div>
            <a href={`mailto:${email}`} style={{ fontSize:12, color:"var(--accent)", textDecoration:"none", fontWeight:500 }}>{email}</a>
          </div>
        </div>
      </div>
    </section>
  );
}

// ============================================================
// ABOUT
// ============================================================
function About() {
  const ref = useReveal();
  const { about, services } = SITE_DATA;
  return (
    <section id="about" className="sec">
      <div className="wrap" ref={ref}>
        <div className="about-grid">
          <div>
            <div className="sec-tag rv">About</div>
            <h2 className="sec-h rv d1">{about.headline}</h2>
            <p className="about-body rv d2">{about.body}</p>
          </div>
          <div>
            <div className="stats-g rv d1">
              {about.stats.map((s, i) => (
                <div className="stat" key={i}>
                  <div className="stat-v">{s.value}</div>
                  <div className="stat-l">{s.label}</div>
                </div>
              ))}
            </div>
            <div className="pillars rv d2">
              {services.map((s) => (
                <div className="pill-row" key={s.id}>
                  <div className="pill-n">{s.number}</div>
                  <div>
                    <div className="pill-t">{s.title}</div>
                    <div className="pill-d">{s.description.split(".")[0]}.</div>
                  </div>
                </div>
              ))}
            </div>
          </div>
        </div>
      </div>
    </section>
  );
}

// ============================================================
// SERVICES
// ============================================================
function Services() {
  const ref = useReveal();
  return (
    <section id="services" className="sec">
      <div className="wrap" ref={ref}>
        <div className="sec-tag rv">What I Do</div>
        <h2 className="sec-h rv d1">Three pillars. One <em>coherent system.</em></h2>
        <div className="svc-grid">
          {SITE_DATA.services.map((s, i) => (
            <div className={`svc-card rv d${i + 1}`} key={s.id}>
              <div className="svc-bg-num">{s.number}</div>
              <h3>{s.title}</h3>
              <p className="svc-desc">{s.description}</p>
              <ul className="svc-list">
                {s.details.map((d) => <li key={d}>{d}</li>)}
              </ul>
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}

// ============================================================
// AUDIT TOOL
// ============================================================
function Audit() {
  const ref = useReveal();
  const [sel, setSel] = useState([]);
  const { auditItems, email } = SITE_DATA;

  const toggle = (id) =>
    setSel((p) => p.includes(id) ? p.filter((x) => x !== id) : [...p, id]);

  const hrs = sel.reduce((s, id) => {
    const it = auditItems.find((a) => a.id === id);
    return s + (it?.hours || 0);
  }, 0);

  const monthCost = Math.round(hrs * 4.3 * 15);

  return (
    <section id="audit" className="sec">
      <div className="wrap" ref={ref}>
        <div className="audit-in">
          <div className="sec-tag rv">Operations Audit</div>
          <h2 className="sec-h rv d1">
            Your manual work is costing you <em>more than you think.</em>
          </h2>
          <p className="audit-sub rv d2">
            Tick every bottleneck that applies to your week. We'll calculate how many hours you're losing — and what it's worth to reclaim them.
          </p>

          <div className="audit-list">
            {auditItems.map((item, i) => {
              const on = sel.includes(item.id);
              return (
                <div
                  key={item.id}
                  className={`ai rv d${Math.min(i + 1, 4)}${on ? " on" : ""}`}
                  onClick={() => toggle(item.id)}
                  role="checkbox"
                  aria-checked={on}
                  tabIndex={0}
                  onKeyDown={(e) => (e.key === "Enter" || e.key === " ") && toggle(item.id)}
                >
                  <span className="ai-txt">{item.label}</span>
                  <div className="ai-chk">{on ? "✓" : ""}</div>
                </div>
              );
            })}
          </div>

          {hrs > 0 && (
            <div className="audit-res">
              <div className="ar-lbl">Hours lost per week</div>
              <div className="ar-hrs">{hrs}</div>
              <div className="ar-sub">
                ~{hrs * 4} hrs/month · Est. ${monthCost.toLocaleString()} in lost productivity
              </div>
              <a
                className="btn-p"
                href={`mailto:${email}?subject=Operations Audit — losing ${hrs} hrs/week&body=Hi Farouk,%0A%0AI just completed your operations audit and found I'm losing ${hrs} hours per week.%0A%0AI'd love to discuss how you could help fix that.`}
              >
                Reclaim Your Time — Book a 15-Min Call
              </a>
            </div>
          )}
        </div>
      </div>
    </section>
  );
}

// ============================================================
// PROJECTS
// ============================================================
function Projects() {
  const ref = useReveal();
  return (
    <section id="work" className="sec">
      <div className="wrap" ref={ref}>
        <div className="sec-tag rv">Documented Work</div>
        <h2 className="sec-h rv d1">Problem. Strategy. <em>Results.</em></h2>
        <div className="proj-grid">
          {SITE_DATA.projects.map((p, i) => (
            <div className={`pcard rv d${(i % 2) + 1}`} key={p.id}>
              <div className="pcard-top">
                <div className="pcard-meta">
                  <span className={`cbadge ${p.categoryColor}`}>{p.category}</span>
                  {Object.entries(p.metrics).map(([k, v]) => (
                    <span className="mchip" key={k}>{v}</span>
                  ))}
                </div>
                <h3>{p.title}</h3>
              </div>
              <div className="pcard-body">
                {[
                  { l: "Problem",  t: p.problem },
                  { l: "Strategy", t: p.strategy },
                  { l: "Results",  t: p.results },
                ].map(({ l, t }) => (
                  <div className="psr" key={l}>
                    <div className="psr-lbl">{l}</div>
                    <p className="psr-txt">{t}</p>
                  </div>
                ))}
                <div className="ptags">
                  {p.tags.map((t) => <span className="tag" key={t}>{t}</span>)}
                </div>
              </div>
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}

// ============================================================
// TESTIMONIALS
// ============================================================
function Testimonials() {
  const ref = useReveal();
  return (
    <section id="testi" className="sec">
      <div className="wrap" ref={ref}>
        <div className="sec-tag rv">Social Proof</div>
        <h2 className="sec-h rv d1">Words from those I've worked with</h2>
        <div className="tg">
          {SITE_DATA.testimonials.map((t, i) => (
            <div className={`tc rv d${i + 1}`} key={i}>
              <p className="tc-q">"{t.quote}"</p>
              <div className="tc-a">
                <div className="tc-av">{t.name[0]}</div>
                <div>
                  <div className="tc-name">{t.name}</div>
                  <div className="tc-role">{t.role}</div>
                </div>
              </div>
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}

// ============================================================
// CONTACT
// ============================================================
function Contact() {
  const ref = useReveal();
  const { email, phone, location, linkedin, github } = SITE_DATA;
  const [f, setF] = useState({ name: "", email: "", message: "" });
  const [sent, setSent] = useState(false);

  const send = () => {
    if (!f.name || !f.email || !f.message) return;
    window.location.href = `mailto:${email}?subject=Portfolio Enquiry from ${encodeURIComponent(f.name)}&body=${encodeURIComponent(f.message + "\n\nFrom: " + f.name + "\nReply to: " + f.email)}`;
    setSent(true);
    setTimeout(() => setSent(false), 3000);
  };

  const links = [
    { icon: "✉", label: email, href: `mailto:${email}` },
    { icon: "☏", label: phone, href: `tel:${phone}` },
    { icon: "in", label: "LinkedIn Profile", href: linkedin },
    { icon: "<>", label: "GitHub", href: github },
    { icon: "⌖", label: location, href: null },
  ];

  return (
    <section id="contact" className="sec">
      <div className="wrap" ref={ref}>
        <div className="sec-tag rv">Let's Work Together</div>
        <h2 className="sec-h rv d1">
          Ready to build something that <em>actually works?</em>
        </h2>
        <div className="contact-g">
          <div className="rv d2">
            <p className="contact-desc">
              Whether you need a content system, an automation pipeline, or someone who can do both — let's talk. I typically respond within 24 hours.
            </p>
            <div className="clinks">
              {links.map((l) =>
                l.href ? (
                  <a key={l.label} href={l.href} className="clink" target={l.href.startsWith("http") ? "_blank" : undefined} rel="noopener noreferrer">
                    <div className="clink-i">{l.icon}</div>
                    {l.label}
                  </a>
                ) : (
                  <div key={l.label} className="clink" style={{ cursor: "default" }}>
                    <div className="clink-i">{l.icon}</div>
                    {l.label}
                  </div>
                )
              )}
            </div>
          </div>

          <div className="cform rv d3">
            <div className="fg">
              <label className="fl">Your Name</label>
              <input className="fi" placeholder="e.g. Amina Okafor" value={f.name} onChange={(e) => setF({ ...f, name: e.target.value })} />
            </div>
            <div className="fg">
              <label className="fl">Email Address</label>
              <input className="fi" type="email" placeholder="you@company.com" value={f.email} onChange={(e) => setF({ ...f, email: e.target.value })} />
            </div>
            <div className="fg">
              <label className="fl">What do you need?</label>
              <textarea className="fta" placeholder="I need help with content strategy and automating my publishing workflow..." value={f.message} onChange={(e) => setF({ ...f, message: e.target.value })} />
            </div>
            <button className="fsub" onClick={send} disabled={sent}>
              {sent ? "Opening email client…" : "Send Message →"}
            </button>
          </div>
        </div>
      </div>
    </section>
  );
}

// ============================================================
// FOOTER
// ============================================================
function Footer() {
  const { name, linkedin, github, email } = SITE_DATA;
  return (
    <footer id="footer">
      <div className="foot-in">
        <div className="foot-logo">{name}</div>
        <div className="foot-copy">© {new Date().getFullYear()} · All rights reserved</div>
        <div className="foot-links">
          <a href={linkedin} target="_blank" rel="noopener noreferrer">LinkedIn</a>
          <a href={github} target="_blank" rel="noopener noreferrer">GitHub</a>
          <a href={`mailto:${email}`}>Email</a>
        </div>
      </div>
    </footer>
  );
}

// ============================================================
// ROOT
// ============================================================
export default function Portfolio() {
  return (
    <>
      <style>{STYLES}</style>
      <Nav />
      <main>
        <Hero />
        <About />
        <Services />
        <Audit />
        <Projects />
        <Testimonials />
        <Contact />
      </main>
      <Footer />
    </>
  );
}
