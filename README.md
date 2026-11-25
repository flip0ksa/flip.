
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>FLIP</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;800&display=swap" rel="stylesheet">
<style>
:root{--txt:#eaf0ff;--mute:#9fb0e6;--btn:rgba(255,255,255,.09);--line:rgba(255,255,255,.18);--pri:#e4eaff;--pritxt:#0b1d5a}
body.alt{--txt:#e6ecff;--mute:#8fa3dd;--btn:rgba(255,255,255,.06);--line:rgba(255,255,255,.14);--pri:#2f58d8;--pritxt:#fff}
*{box-sizing:border-box;margin:0}
html,body{height:100%}
body{font-family:Tajawal,system-ui,sans-serif;color:var(--txt);background:#0a1a4f;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:calc(24px + env(safe-area-inset-top,0px)) 20px calc(24px + env(safe-area-inset-bottom,0px));overflow-x:hidden}
.bg{position:fixed;inset:0;z-index:-1;transition:opacity .9s ease}
.a{background:radial-gradient(120% 70% at 50% 0%,#2a4cb8 0%,#14308a 45%,#0a1a4f 100%)}
.b{background:radial-gradient(120% 70% at 50% 0%,#1d3d9c 0%,#0a1b55 40%,#03050e 100%);opacity:0}
body.alt .b{opacity:1}

main{width:100%;max-width:400px;text-align:center}
.stage{perspective:700px;display:inline-block}
#logo{display:block;width:min(70vw,260px);padding:6px;transition:transform .9s cubic-bezier(.45,.05,.2,1);transform-style:preserve-3d;-webkit-tap-highlight-color:transparent;background:none;border:0;cursor:pointer}
#logo svg{width:100%;height:auto;fill:#fff;filter:drop-shadow(0 6px 18px rgba(0,0,0,.35))}
#logo:focus-visible{outline:2px solid var(--txt);outline-radius:8px}
.tag{margin:14px 0 4px;font-size:16px;color:var(--txt)}
.hint{font-size:12px;color:var(--mute);margin-bottom:22px}

.links{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.btn{display:flex;flex-direction:column;justify-content:center;gap:2px;min-height:54px;padding:8px 12px;border-radius:14px;background:var(--btn);border:1px solid var(--line);color:var(--txt);text-decoration:none;transition:background .9s,border-color .9s,color .9s,transform .15s}
.btn:active{transform:scale(.97)}
.btn b{font-size:16px;font-weight:700;direction:ltr}
.btn small{font-size:12px;color:var(--mute);direction:ltr;transition:color .9s}
.btn.pri,.btn.wide{grid-column:1/-1}
.btn.pri{background:var(--pri);color:var(--pritxt);border-color:transparent}
.btn.pri small{color:inherit;opacity:.7}

.wa{position:fixed;left:18px;bottom:calc(18px + env(safe-area-inset-bottom,0px));width:58px;height:58px;border-radius:50%;background:#25a65b;display:grid;place-items:center;box-shadow:0 8px 22px rgba(0,0,0,.4);-webkit-tap-highlight-color:transparent}
.wa svg{width:30px;height:30px;fill:none;stroke:#fff;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round}
@media (prefers-reduced-motion:reduce){*{transition:none!important}}
</style>
</head>
<body>
<div class="bg a"></div><div class="bg b"></div>

<main>
  <div class="stage">
    <button id="logo" aria-label="FLIP">
      <svg viewBox="0 0 300 94" role="img" aria-hidden="true"><path fill-rule="evenodd" d="M198 37 187 29.7 174 35.2 172.7 34 176.7 21 206 5.4ZM88 36.3 25 36.3 21.1 35 27 17.4 93 17.5 93.1 21ZM150 90.4 80.3 90 102 17.5 127.4 18 112.6 71 155 71.7ZM221 90.5 194.5 90 208 43.1 234 42.6 234.9 44 233.3 52 252 52.3 257 51.4 261 48.9 263.6 45 264.1 41 262 37.7 258 36.4 210.6 36 215.3 18 272 17.6 281 19.6 289 24.5 293.2 32 293.8 41 291.4 50 285 59.2 276 65.4 265 69.2 228 70.7ZM189 66.4 164.1 66 170 44.3 185 36.6 195.7 45ZM32 90.1 5.4 90 19.5 43 48 42.6 48 49.1 81.8 50 77.6 65 76 66.6 39.5 67ZM183 90.2 157 90.3 162 72.1 187.9 72Z"/></svg>
    </button>
  </div>
  <p class="tag">كل حسابات Flip في مكان واحد</p>
  <p class="hint">اضغط على الشعار</p>

  <div class="links">
    <a class="btn pri" href="https://salla.sa/flip.ksa" target="_blank" rel="noopener"><b>Store</b><small>تسوق من متجر Flip</small></a>
    <a class="btn" href="https://www.tiktok.com/@flip.brand" target="_blank" rel="noopener"><b>TikTok</b><small>@flip.brand</small></a>
    <a class="btn" href="https://www.instagram.com/flip.brand7" target="_blank" rel="noopener"><b>Instagram</b><small>@flip.brand7</small></a>
    <a class="btn" href="https://snapchat.com/t/INhRgLwq" target="_blank" rel="noopener"><b>Snapchat</b><small>تابعنا</small></a>
    <a class="btn" href="https://x.com/fl1p_ksa" target="_blank" rel="noopener"><b>X</b><small>@fl1p_ksa</small></a>
    <a class="btn wide" href="https://docs.google.com/forms/d/e/1FAIpQLSciTaEtBHD3V6hmghjnbn5rBvhxvZLfB8Pf2uoMthcQeNY1uw/viewform" target="_blank" rel="noopener"><b>Join Us</b><small>انضم إلينا</small></a>
  </div>
</main>

<a class="wa" href="https://wa.me/966530404826" target="_blank" rel="noopener" aria-label="WhatsApp">
  <svg viewBox="0 0 24 24"><path d="M21 11.5a8.4 8.4 0 0 1-12.4 7.4L3 20.5l1.7-5.4A8.4 8.4 0 1 1 21 11.5z"/><path d="M9 8.5c0 3.5 3 6.5 6.5 6.5l1-1.6-2.2-1-1 .9c-.9-.4-1.8-1.3-2.2-2.2l.9-1-1-2.2z"/></svg>
</a>

<script>
let rot=0;
const logo=document.getElementById("logo");
logo.addEventListener("click",()=>{
  rot+=360;
  logo.style.transform="rotateY("+rot+"deg)";
  document.body.classList.toggle("alt");
});
</script>
</body>
</html>
