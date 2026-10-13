<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Sthira | Discipline, clarity and purpose</title>
<meta name="description" content="Sthira: daily writings, free PDFs and personal guidance on life discipline, mental clarity and purpose.">
<meta property="og:title" content="Sthira">
<meta property="og:description" content="Daily writings, free PDFs and personal guidance on life discipline, mental clarity and purpose.">
<meta property="og:type" content="website">
<meta name="theme-color" content="#f7f6f2">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath d='M19.88 13.39A8 8 0 1 1 18.13 6.86' fill='none' stroke='%233f6a85' stroke-width='2.2' stroke-linecap='round'/%3E%3Ccircle cx='21.8' cy='8.8' r='1.7' fill='%2337766a'/%3E%3C/svg%3E">
<style>
/* ---------- Tokens ---------- */
:root{
  color-scheme:light;
  --bg:#f7f6f2;--alt:#f1efe9;--surface:#fdfcfa;--ink:#17191c;--muted:#5f6368;--line:#e5e2da;
  --a1:#3f6a85;--a2:#37766a;--t1:#3f6a85;--t2:#37766a;--focus:#3f6a85;--danger:#b3412f;
  --glow1:rgba(111,157,181,.20);--glow2:rgba(127,176,162,.17);
  --chip:#ebeeec;--chip-ink:#3a4950;
  --pad:clamp(18px,5vw,40px);
}

/* ---------- Base ---------- */
*,*::before,*::after{box-sizing:border-box}
[hidden]{display:none!important}
html{-webkit-text-size-adjust:100%;scroll-padding-top:76px}
@media (prefers-reduced-motion:no-preference){html{scroll-behavior:smooth}}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;-webkit-font-smoothing:antialiased}
h1,h2,h3,h4,p{margin:0}
h1,h2,h3,h4{font-weight:600;line-height:1.12;letter-spacing:-.025em;text-wrap:balance}
h2{font-size:clamp(1.65rem,4.6vw,2.4rem)}
h3{font-size:1.12rem;letter-spacing:-.01em}
h4{font-size:1.08rem;letter-spacing:-.01em;line-height:1.25}
a{color:inherit}
button{font:inherit;color:inherit}
.muted{color:var(--muted)}
.sm{font-size:.86rem}
.mono{font:12.5px/1.45 ui-monospace,SFMono-Regular,Menlo,Consolas,monospace}
.wrap{width:min(1080px,calc(100% - 2*var(--pad)));margin-inline:auto}
.section{padding-block:clamp(56px,10vw,100px)}
.alt{background:var(--alt);border-block:1px solid var(--line)}
.sec-head{max-width:620px;margin-bottom:clamp(24px,5vw,40px)}
.sec-head p{margin-top:.8rem;color:var(--muted)}
:focus-visible{outline:2px solid var(--focus);outline-offset:3px}
.skip{position:absolute;left:12px;top:-60px;background:var(--surface);padding:.6rem 1rem;border-radius:10px;border:1px solid var(--line);z-index:60}
.skip:focus{top:10px}

/* ---------- Buttons ---------- */
.btn{display:inline-flex;align-items:center;justify-content:center;gap:.5rem;min-height:48px;padding:0 1.4rem;border-radius:999px;border:1px solid transparent;background:linear-gradient(120deg,var(--a1),var(--a2));color:#fff;font-weight:600;text-decoration:none;cursor:pointer;transition:opacity .15s,transform .15s}
.btn:hover{opacity:.92}
.btn:active{transform:scale(.98)}
.btn:disabled{opacity:.6;cursor:default}
.btn-ghost{background:transparent;color:var(--ink);border-color:var(--line)}
.btn-ghost:hover{background:var(--surface);opacity:1}
.btn-sm{min-height:42px;padding:0 1.05rem;font-size:.92rem}
.link{background:none;border:0;padding:0;color:var(--t1);text-decoration:underline;cursor:pointer}
.chip{display:inline-block;align-self:flex-start;font-size:.78rem;font-weight:600;padding:.22rem .65rem;border-radius:999px;background:var(--chip);color:var(--chip-ink)}
.ico::before{content:"";width:16px;height:16px;flex:none;background:currentColor;-webkit-mask:var(--ico) center/contain no-repeat;mask:var(--ico) center/contain no-repeat}
.i-down{--ico:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='black' stroke-width='2.2' stroke-linecap='round' stroke-linejoin='round'%3E%3Cpath d='M12 4v11M7 10.5l5 5 5-5M5 20h14'/%3E%3C/svg%3E")}
.i-chat{--ico:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='black' stroke-width='2.2' stroke-linecap='round' stroke-linejoin='round'%3E%3Cpath d='M21 11.5a8.5 8.5 0 0 1-12.6 7.4L3 20.5l1.6-5.2A8.5 8.5 0 1 1 21 11.5Z'/%3E%3C/svg%3E")}
.i-mark{--ico:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='black' stroke-width='2.2' stroke-linecap='round' stroke-linejoin='round'%3E%3Cpath d='M6 4h12v17l-6-4-6 4z'/%3E%3C/svg%3E")}
.i-file{--ico:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='black' stroke-width='2.2' stroke-linecap='round' stroke-linejoin='round'%3E%3Cpath d='M14 3H7a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V8z'/%3E%3Cpath d='M14 3v5h5'/%3E%3C/svg%3E")}

/* ---------- Header ---------- */
.site-header{position:sticky;top:0;z-index:30;background:var(--bg);border-bottom:1px solid var(--line)}
.bar{display:flex;align-items:center;justify-content:space-between;min-height:62px}
.logo{display:inline-flex;align-items:center;gap:.55rem;text-decoration:none;font-weight:600;font-size:1.12rem;letter-spacing:.01em}
.logo svg{color:var(--t1)}
#nav{display:flex;align-items:center;gap:1.6rem}
#nav a{text-decoration:none;color:var(--muted);font-size:.95rem}
#nav a:hover{color:var(--ink)}
.menu-btn{display:none;width:44px;height:44px;border:1px solid var(--line);border-radius:12px;background:transparent;cursor:pointer;position:relative}
.menu-btn span{position:absolute;left:12px;right:12px;height:2px;border-radius:2px;background:currentColor;transition:transform .2s}
.menu-btn span:first-child{top:16px}.menu-btn span:last-child{top:25px}
.menu-btn[aria-expanded=true] span:first-child{transform:translateY(4.5px) rotate(45deg)}
.menu-btn[aria-expanded=true] span:last-child{transform:translateY(-4.5px) rotate(-45deg)}
@media (max-width:759px){
  .menu-btn{display:block}
  #nav{display:none;position:absolute;left:0;right:0;top:100%;flex-direction:column;align-items:stretch;gap:0;background:var(--bg);border-bottom:1px solid var(--line);padding:6px var(--pad) 18px}
  #nav.open{display:flex}
  #nav a{padding:.85rem 0;border-bottom:1px solid var(--line);font-size:1.02rem}
  #nav .btn{margin-top:14px}
}

/* ---------- Hero ---------- */
.hero{position:relative;overflow:hidden;isolation:isolate;padding:clamp(72px,16vw,160px) 0 clamp(64px,12vw,120px);text-align:center}
.hero::before{content:"";position:absolute;inset:0;z-index:-2;background:radial-gradient(55% 60% at 50% 0%,var(--glow1),transparent 72%),radial-gradient(38% 42% at 88% 38%,var(--glow2),transparent 72%)}
.hero-ring{position:absolute;z-index:-1;left:50%;top:50%;width:min(150vw,820px);transform:translate(-50%,-50%);opacity:.75;pointer-events:none}
.ring-inner{fill:none;stroke:var(--line);stroke-width:.5}
.ring-path{stroke-dasharray:1 1;stroke-dashoffset:0}
.ring-dot{transform-box:fill-box;transform-origin:center}
@media (prefers-reduced-motion:no-preference){
  .ring-path{animation:draw 2.2s cubic-bezier(.3,.6,.2,1) both}
  .ring-dot{animation:pop .7s 1.9s both}
}
@keyframes draw{from{stroke-dashoffset:1}}
@keyframes pop{from{opacity:0;transform:scale(.3)}}
.hero-in{max-width:780px;margin-inline:auto}
.hero h1{font-size:clamp(2.5rem,8.4vw,4.7rem);letter-spacing:-.04em;line-height:1.04}
.lead{margin:1.4rem auto 0;max-width:560px;font-size:clamp(1.02rem,2.6vw,1.2rem);color:var(--muted)}
.cta{display:flex;flex-wrap:wrap;justify-content:center;gap:12px;margin-top:2rem}

/* ---------- Writings ---------- */
.essays{display:grid;gap:12px;max-width:760px}
.essay{border:1px solid var(--line);border-radius:14px;background:var(--surface)}
.essay summary{display:block;list-style:none;cursor:pointer;padding:1.1rem 3.2rem 1.1rem 1.25rem;position:relative}
.essay summary::-webkit-details-marker{display:none}
.essay summary::after{content:"";position:absolute;right:1.35rem;top:1.65rem;width:8px;height:8px;border-right:2px solid var(--muted);border-bottom:2px solid var(--muted);transform:rotate(45deg);transition:transform .2s}
.essay[open] summary::after{transform:translateY(3px) rotate(-135deg)}
.essay h3{margin:.15rem 0 .35rem;font-size:1.28rem}
.essay-meta{font-size:.8rem;color:var(--muted)}
.essay-meta span+span{margin-left:.9rem}
.essay-ex{display:block;color:var(--muted)}
.essay-body{padding:0 1.25rem 1.3rem;max-width:62ch}
.essay-body p+p{margin-top:1rem}
.after{margin-top:1.6rem;color:var(--muted)}
#moreWritings{margin-top:14px}

/* ---------- Library ---------- */
.note{margin-bottom:20px;color:var(--muted);font-size:.95rem;max-width:62ch}
.lib-nav{display:flex;flex-wrap:wrap;gap:8px;margin:0 0 clamp(28px,6vw,44px)}
.lib-nav a{display:inline-flex;align-items:center;gap:.55rem;min-height:42px;padding:0 1rem;border:1px solid var(--line);border-radius:999px;background:var(--surface);text-decoration:none;font-size:.92rem}
.lib-nav a span{color:var(--muted);font-size:.82rem}
.lib-sec+.lib-sec{margin-top:clamp(36px,7vw,60px)}
.sec-title{display:flex;align-items:baseline;flex-wrap:wrap;gap:.3rem .9rem;padding-bottom:.75rem;border-bottom:1px solid var(--line);margin-bottom:.9rem}
.sec-title h3{font-size:1.45rem;letter-spacing:-.02em}
.sec-desc{margin:0 0 1.1rem;color:var(--muted);max-width:60ch}
.grid{display:grid;gap:14px;grid-template-columns:repeat(auto-fill,minmax(min(100%,290px),1fr))}
.lib-card{display:flex;flex-direction:column;gap:.5rem;padding:1.25rem;background:var(--surface);border:1px solid var(--line);border-radius:14px}
.lib-card p{flex:1}
.pdf-name{display:flex;align-items:center;gap:.45rem;font:12.5px/1.35 ui-monospace,SFMono-Regular,Menlo,Consolas,monospace;color:var(--muted);overflow-wrap:anywhere}
.card-actions{display:flex;flex-wrap:wrap;align-items:center;gap:.6rem .9rem;margin-top:.8rem}
.save{display:inline-flex;align-items:center;gap:.4rem;min-height:42px;padding:0 .85rem;border:1px solid var(--line);border-radius:999px;background:transparent;font-size:.9rem;cursor:pointer}
.save[aria-pressed=true]{background:var(--chip);border-color:transparent;color:var(--chip-ink);font-weight:600}
.link-sm{font-size:.9rem;color:var(--muted)}
.empty{padding:1.4rem;border:1px dashed var(--line);border-radius:14px;color:var(--muted)}

/* ---------- Guidance ---------- */
.two{display:grid;gap:36px}
@media (min-width:860px){.two{grid-template-columns:1fr 1.05fr;gap:56px;align-items:start}}
.topics{list-style:none;margin:1.8rem 0 0;padding:0;display:grid;gap:18px}
.topics li{padding-left:1rem;border-left:2px solid var(--t2)}
.topics p{color:var(--muted);margin-top:.2rem}
.fine{margin-top:1.6rem;font-size:.88rem;color:var(--muted)}
.form-card{background:var(--surface);border:1px solid var(--line);border-radius:22px;padding:clamp(1.3rem,4vw,2rem)}
.form-card h3{font-size:1.3rem;margin-bottom:.4rem}
.form-card .lede{color:var(--muted);font-size:.95rem;margin-bottom:1.2rem}
.field{margin-bottom:1rem}
label{display:block;font-size:.88rem;font-weight:600;margin-bottom:.35rem}
input,select,textarea{width:100%;min-height:48px;padding:.7rem .9rem;border:1px solid var(--line);border-radius:12px;background:var(--bg);color:inherit;font:inherit;font-size:16px}
textarea{min-height:120px;resize:vertical}
input:focus,select:focus,textarea:focus{outline:2px solid var(--focus);outline-offset:1px}
.err{min-height:1.25em;margin-top:.3rem;font-size:.85rem;color:var(--danger)}
.check{display:flex;align-items:center;gap:.55rem;font-weight:400;margin:0 0 .6rem}
input[type=checkbox]{width:18px;height:18px;min-height:0;accent-color:var(--a1)}
.wa-num{margin-top:.9rem;text-align:center;font-size:.9rem;color:var(--muted)}

/* ---------- Vault (private, dark) ---------- */
.vault{
  --vi:#e9e7e2;--vm:#a1a6ab;--vs:#171b1e;--vl:#282d32;
  --sage:#22332a;--sage-i:#b9d8c3;--lav:#2b2840;--lav-i:#cfc6f2;--blush:#3b2a27;--blush-i:#f0c8be;
  --vbtn:#a9cdb4;--vbtn-i:#0f1712;--vfocus:#c3b8ee;
  color-scheme:dark;color:var(--vi);
  background:radial-gradient(60% 45% at 50% 0%,rgba(150,130,210,.16),transparent 70%),linear-gradient(180deg,#0e1012,#14171a);
  padding-block:clamp(64px,11vw,112px)
}
.vault :focus-visible{outline-color:var(--vfocus)}
.vault-head{max-width:560px;margin:0 auto;text-align:center}
.vault-head .chip{background:var(--lav);color:var(--lav-i);display:inline-flex;align-items:center;gap:.4rem;margin-bottom:1rem}
.vault-head p{margin-top:.9rem;color:var(--vm)}
.gate{max-width:440px;margin:2rem auto 0;background:var(--vs);border:1px solid var(--vl);border-radius:26px;padding:clamp(1.3rem,4vw,2rem)}
.vault label{color:var(--vi)}
.vault input,.vault textarea{background:transparent;border-color:var(--vl);color:var(--vi)}
.vault input:focus,.vault textarea:focus{outline-color:var(--vfocus)}
.gate input{padding-right:4.6rem}
.pw{position:relative}
.pw button{position:absolute;right:6px;top:6px;height:36px;padding:0 .8rem;border:0;border-radius:9px;background:var(--lav);color:var(--lav-i);font-size:.84rem;font-weight:600;cursor:pointer}
.vbtn{width:100%;margin-top:.4rem;background:var(--vbtn);color:var(--vbtn-i)}
.verr{min-height:1.4em;margin-top:.75rem;font-size:.9rem;color:var(--blush-i);text-align:center}
.verr:not(:empty){background:var(--blush);border-radius:10px;padding:.55rem .8rem}
.shake{animation:shake .35s}
@keyframes shake{25%{transform:translateX(-5px)}75%{transform:translateX(5px)}}
@media (prefers-reduced-motion:reduce){.shake{animation:none}}
.v-bar{display:flex;justify-content:space-between;align-items:center;gap:1rem;margin:2.2rem 0 1rem;flex-wrap:wrap}
.v-bar p{color:var(--vm)}
.vault .btn-ghost{border-color:var(--vl);color:var(--vi)}
.vault .btn-ghost:hover{background:var(--vs)}
.v-list{display:grid;gap:12px;max-width:740px;margin-inline:auto}
.v-item{background:var(--vs);border:1px solid var(--vl);border-radius:20px}
.v-item summary{list-style:none;cursor:pointer;padding:1.1rem 1.3rem;display:flex;flex-wrap:wrap;align-items:center;gap:.4rem .8rem}
.v-item summary::-webkit-details-marker{display:none}
.v-item summary strong{font-size:1.08rem;font-weight:600;flex:1 1 220px}
.v-date{font-size:.82rem;color:var(--vm)}
.v-item .chip{align-self:center}
.k-letter{background:var(--blush);color:var(--blush-i)}
.k-essay{background:var(--lav);color:var(--lav-i)}
.k-writing{background:var(--sage);color:var(--sage-i)}
.v-body{padding:0 1.3rem 1.5rem;max-width:60ch;line-height:1.8}
.v-body p+p{margin-top:1.05rem}
.studio{max-width:740px;margin:2.4rem auto 0;padding:1.4rem;border:1px solid var(--vl);border-radius:22px;background:var(--vs)}
.studio h3{margin-bottom:.5rem}
.studio>p,.studio details p{color:var(--vm);font-size:.92rem;margin-bottom:1rem}
.studio textarea{min-height:240px}
.studio .row{display:flex;flex-wrap:wrap;gap:10px;margin:0 0 1rem}
.studio summary{cursor:pointer;margin-bottom:.8rem;color:var(--vi)}
.studio details{margin-bottom:1rem}
.studio .mono{color:var(--vi)}
.studio .btn:not(.btn-ghost):not(.vbtn){background:var(--vbtn);color:var(--vbtn-i)}

/* ---------- Footer ---------- */
.foot{border-top:1px solid var(--line);padding:2rem 0 calc(2rem + env(safe-area-inset-bottom,0px));color:var(--muted);font-size:.9rem}
.foot .wrap{display:flex;flex-wrap:wrap;gap:.8rem 1.6rem;align-items:center;justify-content:space-between}
.foot nav{display:flex;flex-wrap:wrap;gap:.4rem 1.2rem}
.foot a{text-decoration:none}.foot a:hover{color:var(--ink)}
.admin-toggle{background:none;border:0;padding:.3rem .5rem;font-size:.78rem;color:var(--muted);opacity:.7;cursor:pointer;border-radius:8px}
.admin-toggle:hover{opacity:1}

/* ---------- Dialog, toast ---------- */
dialog{width:min(460px,calc(100% - 24px));max-width:none;max-height:calc(100dvh - 24px);padding:0;border:1px solid var(--line);border-radius:22px;background:var(--surface);color:var(--ink);overflow:auto;overscroll-behavior:contain}
dialog::backdrop{background:rgba(16,18,20,.5)}
.dlg-in{position:relative;padding:1.6rem}
.dlg-in:focus{outline:none}
.dlg-in h2{font-size:1.5rem;padding-right:2rem}
.lede{margin-top:.5rem;color:var(--muted);font-size:.95rem}
.x{position:absolute;top:10px;right:10px;width:40px;height:40px;border:0;border-radius:50%;background:transparent;color:var(--muted);font-size:1.6rem;line-height:1;cursor:pointer}
.x:hover{background:var(--alt)}
.seg{display:flex;gap:4px;padding:4px;border-radius:14px;background:var(--alt);margin:1.1rem 0}
.seg button{flex:1;min-height:40px;border:0;border-radius:10px;background:transparent;color:var(--muted);font-weight:600;font-size:.9rem;cursor:pointer}
.seg button[aria-selected=true]{background:var(--surface);color:var(--ink);box-shadow:0 0 0 1px var(--line)}
.row{display:flex;flex-wrap:wrap;gap:10px;margin-top:1.1rem}
.rowc{border:1px solid var(--line);border-radius:12px;padding:.85rem 1rem;margin-bottom:10px;display:grid;gap:.4rem}
.row-top{display:flex;justify-content:space-between;align-items:center;gap:1rem;flex-wrap:wrap}
.rowc .msg{white-space:pre-wrap;overflow-wrap:anywhere}
.acts{display:flex;gap:.9rem}
.sp-sec{margin-top:1.3rem;padding-top:1.2rem;border-top:1px solid var(--line)}
.sp-sec h3{margin-bottom:.6rem}
#toast{position:fixed;left:50%;bottom:calc(20px + env(safe-area-inset-bottom,0px));transform:translate(-50%,16px);max-width:calc(100% - 32px);padding:.75rem 1.1rem;border-radius:14px;background:var(--ink);color:var(--bg);font-size:.92rem;opacity:0;pointer-events:none;transition:opacity .2s,transform .2s;z-index:80}
#toast.show{opacity:1;transform:translate(-50%,0)}
</style>
</head>
<body>
<a class="skip" href="#main">Skip to content</a>

<header class="site-header">
  <div class="wrap bar">
    <a class="logo" href="#top" aria-label="Sthira, home">
      <svg viewBox="0 0 24 24" width="24" height="24" aria-hidden="true"><path d="M19.88 13.39A8 8 0 1 1 18.13 6.86" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"/><circle cx="21.8" cy="8.8" r="1.7" fill="currentColor"/></svg>
      <span id="logoName">Sthira</span>
    </a>
    <button class="menu-btn" id="menuBtn" type="button" aria-expanded="false" aria-controls="nav" aria-label="Menu"><span></span><span></span></button>
    <nav id="nav" aria-label="Primary">
      <a href="#writings">Writings</a>
      <a href="#library">Library</a>
      <a href="#guidance">Guidance</a>
      <button class="btn btn-ghost btn-sm" id="accountBtn" type="button">Sign In / Account</button>
    </nav>
  </div>
</header>

<main id="main">
  <section class="hero" id="top">
    <svg class="hero-ring" viewBox="0 0 200 200" aria-hidden="true" focusable="false">
      <defs><linearGradient id="rg" x1="0" y1="0" x2="1" y2="1"><stop offset="0" style="stop-color:var(--t1)"/><stop offset="1" style="stop-color:var(--t2)"/></linearGradient></defs>
      <circle class="ring-inner" cx="100" cy="100" r="58"/>
      <path class="ring-path" pathLength="1" d="M178.78 113.89A80 80 0 1 1 161.28 48.58" fill="none" stroke="url(#rg)" stroke-width="1.2" stroke-linecap="round"/>
      <circle class="ring-dot" cx="189.4" cy="70.95" r="3.6" fill="url(#rg)"/>
    </svg>
    <div class="wrap hero-in">
      <h1>Discipline is the quiet road to freedom.</h1>
      <p class="lead">Sthira is a calm space for building a disciplined life, a clear mind and a sense of purpose, through daily writing, free PDFs and personal guidance.</p>
      <div class="cta">
        <a class="btn ico i-chat" data-wa data-text="Hello, I would like personal guidance." href="#guidance">Get personal guidance</a>
        <a class="btn btn-ghost" href="#library">Browse the free PDFs</a>
      </div>
    </div>
  </section>

  <section class="section" id="writings">
    <div class="wrap">
      <div class="sec-head">
        <h2>Writings</h2>
        <p>Short daily notes on living deliberately. Open to everyone, no sign-up.</p>
      </div>
      <div class="essays" id="essays"></div>
      <button class="btn btn-ghost btn-sm" id="moreWritings" type="button" hidden>Show older writings</button>
      <p class="after">Looking for the private letters and long essays? <a 
