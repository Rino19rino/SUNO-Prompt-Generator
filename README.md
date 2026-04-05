<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Suno Studio">
<meta name="mobile-web-app-capable" content="yes">
<meta name="theme-color" content="#F8F6F1">
<meta name="description" content="Suno AI Prompt Builder – 500+ Genres (v5.5), 24 Moods, 70+ Instrumente">
<link rel="manifest" href="data:application/json;base64,ewogICJuYW1lIjogIlN1bm8gUHJvbXB0IFN0dWRpbyBQcm8iLAogICJzaG9ydF9uYW1lIjogIlN1bm8gU3R1ZGlvIiwKICAic3RhcnRfdXJsIjogIi4iLAogICJkaXNwbGF5IjogInN0YW5kYWxvbmUiLAogICJiYWNrZ3JvdW5kX2NvbG9yIjogIiMwODA2MEQiLAogICJ0aGVtZV9jb2xvciI6ICIjMDgwNjBEIiwKICAib3JpZW50YXRpb24iOiAicG9ydHJhaXQiLAogICJpY29ucyI6IFt7InNyYyI6ICJkYXRhOmltYWdlL3N2Zyt4bWw7YmFzZTY0LFBITjJaeUI0Yld4dWN6MGlhSFIwY0RvdkwzZDNkeTUzTXk1dmNtY3ZNakF3TUM5emRtY2lJSFpwWlhkQ2IzZzlJakFnTUNBeE9USWdNVGt5SWo0OFpHVm1jejQ4YkdsdVpXRnlSM0poWkdsbGJuUWdhV1E5SW1jaUlIZ3hQU0l5TkNJZ2VURTlJakkwSWlCNE1qMGlNVFk0SWlCNU1qMGlNVFk0SWo0OGMzUnZjQ0J6ZEc5d0xXTnZiRzl5UFNJalJEUTVOVFpCSWk4K1BITjBiM0FnYjJabWMyVjBQU0l4SWlCemRHOXdMV052Ykc5eVBTSWpPRUkyUTBNeElpOCtQQzlzYVc1bFlYSkhjbUZrYVdWdWRENDhMMlJsWm5NK1BHTnBjbU5zWlNCamVEMGlPVFlpSUdONVBTSTVOaUlnY2owaU9EQWlJR1pwYkd3OUluVnliQ2dqWnlraUlHOXdZV05wZEhrOUlqQXVNU0l2UGp4MFpYaDBJSGc5SWprMklpQjVQU0k1TmlJZ1ptOXVkQzFtWVcxcGJIazlJa0Z5YVdGc0lpQm1iMjUwTFhOcGVtVTlJamN3SWlCbWFXeHNQU0lqUlRoQ05EaEJJaUIwWlhoMExXRnVZMmh2Y2owaWJXbGtaR3hsSWlCa2IyMXBibUZ1ZEMxaVlYTmxiR2x1WlQwaVkyVnVkSEpoYkNJK/CfjKc8L3RleHQ+PC9zdmc+IiwgInNpemVzIjogIjE5MngxOTIiLCAidHlwZSI6ICJpbWFnZS9zdmcreG1sIn1dCn0=">
<!-- PWA Icons as inline SVG data URIs -->
<link rel="apple-touch-icon" href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxOTIgMTkyIj48cmVjdCB3aWR0aD0iMTkyIiBoZWlnaHQ9IjE5MiIgcng9IjQwIiBmaWxsPSIjMEYwQzE4Ii8+PHRleHQgeD0iOTYiIHk9IjExNiIgZm9udC1zaXplPSI4MCIgdGV4dC1hbmNob3I9Im1pZGRsZSI+8J+OpzwvdGV4dD48L3N2Zz4=">
<title>Suno Prompt Studio Pro</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Outfit:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
/* ══════════════════════════════════════
   PWA "Midnight Studio" — Mobile-First
   ══════════════════════════════════════ */
:root {
  --bg-deep: #F8F6F1;
  --bg-mid: #EFEBE4;
  --bg-card: rgba(0,0,0,0.025);
  --glass: rgba(0,0,0,0.03);
  --glass-border: rgba(0,0,0,0.08);
  --accent: #C06830;
  --accent-light: #A8522A;
  --accent-glow: rgba(192,104,48,0.2);
  --accent2: #7B5EA7;
  --accent2-glow: rgba(123,94,167,0.15);
  --accent3: #3D8B6E;
  --text: #2A2118;
  --text-dim: rgba(42,33,24,0.65);
  --text-muted: rgba(42,33,24,0.35);
  --chip-bg: rgba(0,0,0,0.03);
  --chip-border: rgba(0,0,0,0.1);
  --chip-active-bg: rgba(192,104,48,0.1);
  --chip-active-border: rgba(192,104,48,0.55);
  --nav-h: 64px;
  --safe-top: env(safe-area-inset-top, 0px);
  --safe-bottom: env(safe-area-inset-bottom, 0px);
  --font-display: 'Cormorant Garamond', Georgia, serif;
  --font-body: 'Outfit', system-ui, sans-serif;
  --font-mono: 'JetBrains Mono', monospace;
  --radius: 14px;
  --radius-sm: 10px;
  --radius-chip: 22px;
}
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;-webkit-font-smoothing:antialiased;-webkit-tap-highlight-color:transparent;overscroll-behavior:none;}
body{font-family:var(--font-body);background:var(--bg-deep);color:var(--text);min-height:100vh;min-height:100dvh;overflow-x:hidden;-webkit-user-select:none;user-select:none;}
input,textarea{-webkit-user-select:text;user-select:text;}

/* ── Animated BG ── */
.bg-canvas{position:fixed;inset:0;z-index:0;pointer-events:none;overflow:hidden;}
.bg-orb{position:absolute;border-radius:50%;filter:blur(80px);opacity:0.2;will-change:transform;animation:orbDrift 20s ease-in-out infinite alternate;}
.bg-orb:nth-child(1){width:400px;height:400px;background:radial-gradient(circle,rgba(192,104,48,0.2),transparent 70%);top:-8%;left:-8%;animation-duration:18s;}
.bg-orb:nth-child(2){width:320px;height:320px;background:radial-gradient(circle,rgba(123,94,167,0.15),transparent 70%);top:35%;right:-10%;animation-duration:24s;animation-delay:-6s;}
.bg-orb:nth-child(3){width:280px;height:280px;background:radial-gradient(circle,rgba(61,139,110,0.12),transparent 70%);bottom:10%;left:15%;animation-duration:22s;animation-delay:-12s;}
.bg-noise{position:fixed;inset:0;z-index:1;pointer-events:none;opacity:0.015;background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");background-size:180px;}
@keyframes orbDrift{0%{transform:translate(0,0)scale(1)}33%{transform:translate(30px,-25px)scale(1.08)}66%{transform:translate(-15px,18px)scale(.95)}100%{transform:translate(22px,-8px)scale(1.04)}}

/* ── Install Banner ── */
.install-banner{position:fixed;top:0;left:0;right:0;z-index:100;padding:calc(var(--safe-top) + 8px) 16px 10px;background:linear-gradient(135deg,rgba(192,104,48,0.1),rgba(123,94,167,0.06));backdrop-filter:blur(20px);border-bottom:1px solid rgba(192,104,48,0.15);display:none;align-items:center;gap:12px;animation:slideDown .4s ease-out;}
.install-banner.show{display:flex;}
.install-banner-text{flex:1;font-size:13px;color:var(--text);line-height:1.4;}
.install-banner-text small{display:block;font-size:11px;color:var(--text-dim);margin-top:2px;}
.install-btn{padding:8px 18px;border-radius:20px;border:none;background:var(--accent);color:var(--bg-deep);font-weight:700;font-size:12px;font-family:var(--font-body);cursor:pointer;}
.install-close{background:none;border:none;color:var(--text-muted);font-size:18px;cursor:pointer;padding:4px;}
@keyframes slideDown{from{transform:translateY(-100%);opacity:0}to{transform:translateY(0);opacity:1}}

/* ── App Shell ── */
.app-shell{position:relative;z-index:2;padding-top:var(--safe-top);padding-bottom:calc(var(--nav-h) + var(--safe-bottom) + 16px);}
.page{max-width:680px;margin:0 auto;padding:0 14px;}
.page-content{animation:fadeUp .35s ease-out;}

/* ── Bottom Nav ── */
.bottom-nav{position:fixed;bottom:0;left:0;right:0;z-index:50;background:rgba(248,246,241,0.94);backdrop-filter:blur(24px)saturate(180%);border-top:1px solid rgba(0,0,0,0.08);padding:6px 0 calc(var(--safe-bottom) + 4px);display:flex;justify-content:space-around;}
.nav-item{display:flex;flex-direction:column;align-items:center;gap:2px;padding:6px 12px;border-radius:12px;background:none;border:none;cursor:pointer;color:var(--text-muted);transition:all .25s;-webkit-tap-highlight-color:transparent;min-width:64px;}
.nav-item.active{color:var(--accent-light);}
.nav-item.active .nav-icon{transform:scale(1.15);}
.nav-icon{font-size:22px;transition:transform .25s;}
.nav-label{font-size:10px;font-family:var(--font-body);font-weight:500;letter-spacing:.3px;}
.nav-indicator{position:absolute;top:0;height:2px;background:var(--accent);border-radius:0 0 2px 2px;transition:all .35s cubic-bezier(.4,0,.2,1);width:48px;}

/* ── Header ── */
.header{text-align:center;padding:20px 0 16px;animation:fadeUp .6s ease-out;}
.header-icon{font-size:38px;margin-bottom:2px;animation:floatIcon 4s ease-in-out infinite;}
.header h1{font-family:var(--font-display);font-size:32px;font-weight:700;background:linear-gradient(135deg,var(--accent),var(--accent2),var(--accent3));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;letter-spacing:-.3px;}
.header-sub{font-size:11px;color:var(--text-muted);margin-top:2px;letter-spacing:1.5px;text-transform:uppercase;font-weight:300;}
.header-stats{display:flex;justify-content:center;gap:8px;margin-top:12px;flex-wrap:wrap;}
.header-stat{padding:5px 12px;border-radius:18px;background:var(--glass);border:1px solid var(--glass-border);font-size:10px;color:var(--text-dim);font-weight:500;backdrop-filter:blur(10px);}
.header-stat strong{color:var(--accent-light);font-weight:700;}
@keyframes floatIcon{0%,100%{transform:translateY(0)}50%{transform:translateY(-5px)}}
@keyframes fadeUp{from{opacity:0;transform:translateY(16px)}to{opacity:1;transform:translateY(0)}}

/* ── Section ── */
.section{margin-bottom:8px;border-radius:var(--radius);background:var(--bg-card);border:1px solid var(--glass-border);overflow:hidden;transition:border-color .25s;}
.section:active{border-color:rgba(255,255,255,0.12);}
.section-header{display:flex;align-items:center;gap:10px;padding:14px 16px;cursor:pointer;-webkit-tap-highlight-color:transparent;transition:background .15s;}
.section-header:active{background:rgba(255,255,255,0.02);}
.section-icon{font-size:17px;flex-shrink:0;}
.section-title{flex:1;font-family:var(--font-display);font-size:18px;font-weight:600;color:var(--accent-light);letter-spacing:.2px;}
.section-count{font-family:var(--font-body);font-size:10px;font-weight:700;color:var(--bg-deep);background:var(--accent);padding:2px 7px;border-radius:9px;margin-left:4px;display:inline-block;vertical-align:middle;}
.section-arrow{font-size:10px;color:var(--text-muted);transition:transform .3s cubic-bezier(.4,0,.2,1);}
.section.collapsed .section-arrow{transform:rotate(-90deg);}
.section-body{padding:4px 16px 16px;max-height:2000px;transition:max-height .4s ease,opacity .3s;opacity:1;overflow:hidden;}
.section.collapsed .section-body{max-height:0;opacity:0;padding-top:0;padding-bottom:0;}
.section-subtitle{font-size:12px;color:var(--text-muted);margin-bottom:8px;font-weight:300;}

/* ── Chips ── */
.chip-group{display:flex;flex-wrap:wrap;gap:7px;}
.chip-group-label{width:100%;font-size:11px;font-weight:700;color:var(--text-muted);text-transform:uppercase;letter-spacing:1.5px;margin:10px 0 4px;padding-left:2px;}
.chip-group-label:first-child{margin-top:0;}
.chip{padding:8px 16px;border-radius:var(--radius-chip);border:1px solid var(--chip-border);background:var(--chip-bg);color:var(--text-dim);cursor:pointer;font-family:var(--font-body);font-size:14px;font-weight:400;transition:all .2s;white-space:nowrap;-webkit-tap-highlight-color:transparent;position:relative;overflow:hidden;touch-action:manipulation;}
.chip:active{transform:scale(.96);}
.chip.active{border-color:var(--chip-active-border);background:var(--chip-active-bg);color:var(--accent-light);font-weight:600;box-shadow:0 0 14px rgba(212,149,106,0.08);}
.chip-sm{padding:7px 13px;font-size:13px;}
.mood-dot{display:inline-block;width:8px;height:8px;border-radius:50%;margin-right:6px;vertical-align:middle;}

/* ── Inputs ── */
.input-text,.input-area{width:100%;padding:11px 14px;border-radius:var(--radius-sm);border:1px solid var(--glass-border);background:rgba(255,255,255,0.7);color:var(--text);font-family:var(--font-body);font-size:15px;transition:all .25s;-webkit-appearance:none;appearance:none;}
.input-text:focus,.input-area:focus{border-color:var(--accent);outline:none;box-shadow:0 0 20px rgba(212,149,106,0.08);}
.input-text::placeholder,.input-area::placeholder{color:var(--text-muted);}
.input-area{resize:vertical;line-height:1.7;font-family:var(--font-mono);font-size:14px;}
.input-search{width:100%;padding:9px 12px 9px 34px;border-radius:8px;border:1px solid var(--glass-border);background:rgba(255,255,255,0.6);color:var(--text);font-family:var(--font-body);font-size:14px;margin-bottom:10px;-webkit-appearance:none;}
.input-search:focus{border-color:var(--accent);outline:none;}
.search-wrap{position:relative;}
.search-ico{position:absolute;left:10px;top:50%;transform:translateY(-50%);font-size:14px;color:var(--text-muted);pointer-events:none;}

/* ── Structure Cards ── */
.struct-card{padding:10px 14px;border-radius:var(--radius-sm);margin-bottom:6px;border:1px solid var(--glass-border);background:var(--chip-bg);cursor:pointer;transition:all .2s;-webkit-tap-highlight-color:transparent;touch-action:manipulation;}
.struct-card:active{transform:scale(.98);}
.struct-card.active{border-color:var(--accent);background:var(--chip-active-bg);box-shadow:0 0 16px rgba(212,149,106,0.06);}
.struct-label{font-weight:600;font-size:13px;color:var(--accent-light);}
.struct-card:not(.active) .struct-label{color:var(--text-dim);}
.struct-desc{font-size:10px;color:var(--text-muted);margin-top:2px;line-height:1.4;}

/* ── Presets ── */
.preset-card{display:block;width:100%;padding:16px;margin-bottom:10px;border-radius:var(--radius);border:1px solid var(--glass-border);background:var(--bg-card);cursor:pointer;text-align:left;transition:all .25s;-webkit-tap-highlight-color:transparent;touch-action:manipulation;}
.preset-card:active{transform:scale(.98);background:rgba(255,255,255,0.04);}
.preset-name{font-family:var(--font-display);font-size:18px;font-weight:600;color:var(--accent-light);margin-bottom:4px;}
.preset-desc{font-size:11px;color:var(--text-muted);line-height:1.5;}

/* ── Output ── */
.output-panel{margin-top:12px;padding:20px 16px;border-radius:18px;background:linear-gradient(145deg,rgba(192,104,48,0.04),rgba(123,94,167,0.03),rgba(61,139,110,0.02));border:1px solid rgba(192,104,48,0.15);position:relative;overflow:hidden;animation:pulseGlow 4s ease-in-out infinite;}
.output-panel::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,var(--accent),var(--accent2),transparent);opacity:.3;}
@keyframes pulseGlow{0%,100%{box-shadow:0 0 20px rgba(192,104,48,0.03)}50%{box-shadow:0 0 35px rgba(192,104,48,0.08)}}
.output-title{font-family:var(--font-display);font-size:22px;font-weight:700;color:var(--accent);margin-bottom:2px;}
.output-hint{font-size:12px;color:var(--text-muted);margin-bottom:14px;letter-spacing:.2px;}
.output-label{font-size:11px;font-weight:700;color:var(--text-muted);letter-spacing:2px;text-transform:uppercase;margin-bottom:5px;}
.output-box{padding:11px 13px;border-radius:var(--radius-sm);background:rgba(255,255,255,0.6);font-size:14px;line-height:1.7;color:var(--text-dim);min-height:36px;word-break:break-word;border:1px solid rgba(0,0,0,0.06);-webkit-user-select:text;user-select:text;}
.output-box-mono{font-family:var(--font-mono);font-size:13px;white-space:pre-wrap;max-height:240px;overflow-y:auto;}
.output-box .ph{color:var(--text-muted);font-style:italic;}
.charcount{text-align:right;margin-top:3px;font-size:9.5px;color:var(--text-muted);}

/* ── Buttons ── */
.btn{padding:13px 20px;border-radius:var(--radius-sm);border:none;cursor:pointer;font-family:var(--font-body);font-size:15px;font-weight:600;transition:all .2s;-webkit-tap-highlight-color:transparent;touch-action:manipulation;}
.btn:active{transform:scale(.97);}
.btn-copy{padding:7px 15px;border-radius:8px;font-size:12px;font-weight:600;border:1px solid rgba(192,104,48,0.3);background:transparent;color:var(--accent);cursor:pointer;font-family:var(--font-body);transition:all .2s;-webkit-tap-highlight-color:transparent;}
.btn-copy:active{transform:scale(.95);}
.btn-copy.copied{background:rgba(192,104,48,0.08);}
.btn-primary{background:linear-gradient(135deg,var(--accent),var(--accent2));color:#fff;font-weight:700;box-shadow:0 4px 20px rgba(192,104,48,0.15);}
.btn-primary:active{box-shadow:0 2px 10px rgba(212,149,106,0.1);}
.btn-ghost{background:transparent;border:1px solid var(--glass-border);color:var(--text-muted);}
.btn-row{display:flex;gap:8px;margin-top:14px;flex-wrap:wrap;}
.btn-row .btn-primary{flex:1;min-width:100px;}

/* ── Counter ── */
.counter-bar{display:flex;justify-content:space-between;align-items:center;padding:10px 14px;border-radius:var(--radius-sm);background:rgba(212,149,106,0.04);border:1px solid rgba(212,149,106,0.1);margin-bottom:14px;font-size:12px;}
.counter-bar span{color:var(--text-dim);}
.counter-bar button{background:none;border:none;color:var(--accent);cursor:pointer;font-family:var(--font-body);font-size:12px;font-weight:600;}

/* ── Saved ── */
.saved-card{padding:14px;margin-bottom:10px;border-radius:var(--radius);border:1px solid var(--glass-border);background:var(--bg-card);}
.saved-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:5px;}
.saved-name{font-family:var(--font-display);font-size:16px;font-weight:600;color:var(--accent-light);}
.saved-date{font-size:10px;color:var(--text-muted);}
.saved-style{font-size:11px;color:var(--text-muted);line-height:1.5;margin-bottom:8px;}
.saved-actions{display:flex;gap:6px;flex-wrap:wrap;}

/* ── Empty ── */
.empty-state{text-align:center;padding:48px 20px;}
.empty-icon{font-size:40px;margin-bottom:8px;opacity:.35;}
.empty-text{font-size:14px;color:var(--text-muted);}
.empty-hint{font-size:11px;color:var(--text-muted);margin-top:4px;opacity:.5;}

/* ── Toast ── */
.toast{position:fixed;bottom:calc(var(--nav-h) + var(--safe-bottom) + 16px);left:50%;transform:translateX(-50%)translateY(80px);z-index:90;padding:10px 22px;border-radius:24px;background:rgba(192,104,48,0.92);color:#fff;font-size:14px;font-weight:700;font-family:var(--font-body);pointer-events:none;opacity:0;transition:all .4s cubic-bezier(.4,0,.2,1);}
.toast.show{transform:translateX(-50%)translateY(0);opacity:1;}

/* ── Scrollbar ── */
::-webkit-scrollbar{width:4px;}
::-webkit-scrollbar-track{background:transparent;}
::-webkit-scrollbar-thumb{background:rgba(192,104,48,0.2);border-radius:2px;}

/* ── iOS fixes ── */
@supports(-webkit-touch-callout:none){
  body{min-height:-webkit-fill-available;}
}
</style>
</head>
<body>

<div class="bg-canvas"><div class="bg-orb"></div><div class="bg-orb"></div><div class="bg-orb"></div></div>
<div class="bg-noise"></div>

<!-- Install Banner -->
<div class="install-banner" id="installBanner">
  <div class="install-banner-text">
    <strong>📲 Als App installieren</strong>
    <small>Zum Homescreen hinzufügen für den vollen App-Modus</small>
  </div>
  <button class="install-btn" id="installBtn">Installieren</button>
  <button class="install-close" id="installClose">✕</button>
</div>

<!-- App Shell -->
<div class="app-shell">
  <div class="page" id="app"></div>
</div>

<!-- Bottom Nav -->
<nav class="bottom-nav" id="bottomNav">
  <div class="nav-indicator" id="navIndicator"></div>
  <button class="nav-item active" data-tab="builder" onclick="switchTab('builder',this)">
    <span class="nav-icon">🎛️</span><span class="nav-label">Builder</span>
  </button>
  <button class="nav-item" data-tab="presets" onclick="switchTab('presets',this)">
    <span class="nav-icon">✨</span><span class="nav-label">Presets</span>
  </button>
  <button class="nav-item" data-tab="saved" onclick="switchTab('saved',this)">
    <span class="nav-icon">💾</span><span class="nav-label">Gespeichert</span>
  </button>
  <button class="nav-item" data-tab="settings" onclick="switchTab('settings',this)">
    <span class="nav-icon">⚙️</span><span class="nav-label">Info</span>
  </button>
</nav>

<!-- Toast -->
<div class="toast" id="toast"></div>

<script>
// ═══════════════════════════════════════
//  DATA
// ═══════════════════════════════════════
const GENRES={"Pop":["Pop","Synth Pop","Electro Pop","Indie Pop","Dream Pop","Art Pop","Chamber Pop","Power Pop","Bubblegum Pop","Dance Pop","Teen Pop","Baroque Pop","Europop","K-Pop","J-Pop","C-Pop","City-Pop","Afropop","Latin Pop","Bedroom Pop","Hyperpop","Neon Pop","Noise Pop","Thai Pop","Adult Contemporary","Urban Contemporary","Glitch Pop"],"Rock":["Rock","Classic Rock","Alternative Rock","Indie Rock","Punk Rock","Post-Punk","Grunge","Shoegaze","Progressive Rock","Psychedelic Rock","Hard Rock","Soft Rock","Garage Rock","Surf Rock","Blues Rock","Southern Rock","Stoner Rock","Noise Rock","Math Rock","Post-Rock","Emo","Pop Rock","Britpop","Krautrock","Space Rock","Glam Rock","Acid Rock","Art Rock","Desert Rock","Electronic Rock","Experimental Rock","Folk Rock","Funk Rock","Gothic Rock","Industrial Rock","Instrumental Rock","Piano Rock","Rap Rock","Rock and Roll","Rock Opera","Rockabilly","Skate Rock","Stadium Rock","Symphonic Rock","Afro-Blues-Rock","Country Rock"],"Metal":["Heavy Metal","Thrash Metal","Death Metal","Melodic Death Metal","Black Metal","Atmospheric Black Metal","Symphonic Black Metal","Doom Metal","Power Metal","Symphonic Metal","Folk Metal","Gothic Metal","Nu Metal","Metalcore","Melodic Metalcore","Deathcore","Djent","Progressive Metal","Sludge Metal","Industrial Metal","Speed Metal","Glam Metal","Viking Metal","Pagan Metal","War Metal","Groove Metal","Post-Metal","Avant-garde Metal","Funk Metal","Heavy Metal Trap","Kawaii Metal","Oriental Metal","Rap Metal","Scandinavian Metal"],"Electronic & Dance":["Electronic","EDM","House","Deep House","Tech House","Progressive House","Tropical House","Acid House","Future House","Afro House","Latin House","French House","Bass House","Vocal House","Techno","Minimal Techno","Detroit Techno","Deep Techno","Dub Techno","Trance","Psytrance","Goa Trance","Vocal Trance","Ambient Trance","Drum and Bass","Liquid Drum and Bass","Neurofunk","Jungle","Dubstep","Brostep","Post-Dubstep","Future Bass","Future Garage","Garage","UK Garage","UK Funky","Breakbeat","IDM","Hardstyle","Happy Hardcore","Gabber","Synthwave","Retrowave","Vaporwave","Chillwave","Chillsynth","Downtempo","Trip Hop","Glitch","Glitch Hop","Electronica","Eurodance","Italo Disco","Nu Disco","Post-Disco","Space Disco","Disco","Electro","Electro Swing","Future Funk","Phonk","Hyperpop","Electroclash","Electropop","Breakcore","Acid Breaks","Nightcore","Moombahton","Rave","Witch House","Cyberpunk","Dark Electro","Club","Dance"],"Hip-Hop & Rap":["Hip-Hop","Trap","Boom Bap","Lo-Fi Hip-Hop","Cloud Rap","Drill","UK Drill","Mumble Rap","Conscious Hip-Hop","Gangsta Rap","Old School Hip-Hop","Jazz Rap","Abstract Hip-Hop","Horrorcore","Chopped & Screwed","Crunk","Grime","G-Funk","Emo Rap","Phonk Rap","Dirty South","Hyphy","Pop Rap","Rap","West Coast Rap","Afro-Trap"],"R&B & Soul":["R&B","Contemporary R&B","Neo Soul","Classic Soul","Motown","Funk","P-Funk","Disco Funk","Alternative R&B","Quiet Storm","New Jack Swing","Disco","Boogie","Gospel","Southern Soul","Soul","Afroswing","Doo Wop"],"Jazz & Blues":["Jazz","Bebop","Cool Jazz","Free Jazz","Jazz Fusion","Smooth Jazz","Latin Jazz","Swing","Big Band","Bossa Nova","Acid Jazz","Nu Jazz","Gypsy Jazz","Modal Jazz","Hard Bop","Post-Bop","Jazz Funk","Ethio-Jazz","Dark Jazz","New Orleans Jazz","Soul Jazz","Vocal Jazz","Avant-garde Jazz","Barbershop","Blues","Delta Blues","Chicago Blues","Electric Blues","Piano Blues","Piedmont Blues","Punk Blues","Country Blues","Slide Guitar Blues","Texas Blues"],"Klassik & Soundtrack":["Klassik","Barock","Romantik","Impressionismus","Minimalism","Neo-Klassik","Contemporary Classical","Modern Classical","Orchestral","Filmmusik","Cinematic","Trailer Music","Opera","Operatic Pop","Choral","Kammermusik","Symphonic","Symphony","Sonata","Requiem","Rhapsody","String Quartet","Classical Crossover","Score","Movie Soundtrack","Video Game Music","TV Themes","Spaghetti Western","Villain Theme"],"Country & Folk":["Country","Country Rock","Alt-Country","Outlaw Country","Honky Tonk","Truck Driving Country","Folk","Indie Folk","Folk Rock","Folk Punk","Freak Folk","Psychedelic Folk","Americana","Bluegrass","Acoustic","Singer-Songwriter","Celtic","Irish Folk","Nordic Folk","Balkan Folk","Klezmer","Medieval","Neofolk","Traditional Folk","Urban Folk","Sea Shanties","Spanish Folk"],"Reggae & Caribbean":["Reggae","Roots Reggae","Dub","Dancehall","Ska","Rocksteady","Lovers Rock","Soca","Calypso","Reggaeton","Dembow","Caribbean"],"Latin & Brasilianisch":["Latin","Salsa","Bachata","Merengue","Cumbia","Tango","Flamenco","Bossa Nova","MPB","Samba","Forró","Fado","Bolero","Cha-Cha","Mambo","Guajira","Rumba","Mariachi","Norteño","Ranchera","Sertanejo","Tropicalia","Latin House","Latin Dance Pop","Latin Jazz","Latin Pop"],"Afrikanisch":["Afrobeats","Afrobeat","Amapiano","Afro House","Afro-Funk","Afro-Cuban","Afropop","Afroswing","Highlife","Soukous","Afro-Blues-Rock","Afro-Trap","Taarab","Tribal","World Beat","World Fusion","World"],"Asiatisch & Indisch":["Bollywood","Bhangra","Carnatic","Hindustani","Indian Classical","Qawwali","Sufi Music","J-Pop","K-Pop","C-Pop","Kawaii","Anime","Raga","Sitar","Tabla","Arabic Pop","Turkish Pop","Tuareg","Raï","Chaabi","Gnawa","Sephardic"],"Ambient & Experimental":["Ambient","Dark Ambient","Drone","New Age","Meditation","Space Music","Field Recordings","Noise","Harsh Noise","Experimental","Avant-Garde","Musique Concrète","Sound Collage","Sound Art","Tape Music","Binaural","432 Hz","Solfeggio","Sound Bath","ASMR Music","Psyambient","Dungeon Synth","No Wave","Power Electronics","Electroacoustic"],"Punk & Hardcore":["Punk","Hardcore Punk","Post-Hardcore","Pop Punk","Ska Punk","Folk Punk","Crust Punk","Anarcho-Punk","Screamo","Mathcore","Powerviolence","Straight Edge","New York Hardcore"],"Vocal & Chor":["Acapella","Barbershop","Beatboxing","Choir","Christmas Carol","Doo Wop","Gregorian Chant","Throat Singing","Vocal","Vocaloid"],"Lounge & Easy":["Lounge","Dark Cabaret","Broadway","Chanson","Polka","Zydeco","Cajun","Hawaiian","Quebecois Traditional","Russian Folk","Martial Industrial"]};
const MOODS=[{id:"euphoric",label:"Euphorisch",color:"#FFD700"},{id:"melancholic",label:"Melancholisch",color:"#6B7FD7"},{id:"energetic",label:"Energetisch",color:"#FF4444"},{id:"calm",label:"Ruhig",color:"#7ECEC1"},{id:"dark",label:"Dunkel",color:"#4A3660"},{id:"romantic",label:"Romantisch",color:"#E88BAA"},{id:"mystical",label:"Mystisch",color:"#9B6DFF"},{id:"empowering",label:"Kraftvoll",color:"#FF8C00"},{id:"dreamy",label:"Verträumt",color:"#B8A9E8"},{id:"rebellious",label:"Rebellisch",color:"#DC143C"},{id:"nostalgic",label:"Nostalgisch",color:"#D4A574"},{id:"healing",label:"Heilend",color:"#5DB075"},{id:"aggressive",label:"Aggressiv",color:"#8B0000"},{id:"playful",label:"Verspielt",color:"#FF69B4"},{id:"anxious",label:"Beklemmend",color:"#555577"},{id:"triumphant",label:"Triumphierend",color:"#FFB347"},{id:"spiritual",label:"Spirituell",color:"#C4A7E7"},{id:"sensual",label:"Sinnlich",color:"#C41E3A"},{id:"hopeful",label:"Hoffnungsvoll",color:"#87CEEB"},{id:"bittersweet",label:"Bittersüß",color:"#C19A6B"},{id:"eerie",label:"Unheimlich",color:"#2F4F4F"},{id:"joyful",label:"Fröhlich",color:"#FFA500"},{id:"contemplative",label:"Nachdenklich",color:"#708090"},{id:"cinematic",label:"Cinematic",color:"#8B7355"}];
const VOCALS={"Stimme":["Weiblich","Männlich","Androgyn","Kind","Chor","Duett","Trio","A Cappella"],"Gesangsstil":["Clean Vocals","Raspy / Heiser","Breathy / Hauchig","Belting","Falsetto","Vibrato","Whisper / Flüstern","Spoken Word","Rap","Fast Rap","Melodic Rap","Sing-Rap","Screaming","Growling","Opera","Yodeling","Scat","Beatbox","Autotune","Vocoder","Layered Harmonies","Ad-libs","Call & Response"],"Kein Gesang":["Instrumental","Vocalless","Humming Only","Ooh & Aah Only"]};
const INSTRUMENTS={"Tasten":["Klavier","E-Piano","Rhodes","Wurlitzer","Orgel","Hammond Orgel","Synthesizer","Analog Synth","Modular Synth","Moog","Cembalo","Akkordeon","Melodica"],"Gitarren & Saiten":["Akustikgitarre","E-Gitarre","Nylon-Gitarre","12-String","Slide Guitar","Pedal Steel","Bass","Slap Bass","Fretless Bass","Upright Bass","Sitar","Oud","Banjo","Mandoline","Ukulele","Charango","Bouzouki"],"Streicher":["Violine","Viola","Cello","Kontrabass","String Ensemble","Erhu","Koto","Dulcimer","Zither","Harfe"],"Bläser":["Trompete","Posaune","Saxophon","Klarinette","Flöte","Querflöte","Oboe","Fagott","Tuba","Mundharmonika","Pan Flöte","Dudelsack","Didgeridoo","Shakuhachi"],"Drums & Percussion":["Akustik Drums","Electronic Drums","808 Drums","Drum Machine","Percussion","Congas","Bongos","Djembe","Tabla","Cajon","Handpan","Hang Drum","Marimba","Xylophon","Vibraphon","Glockenspiel","Steel Drums","Timpani","Taiko","Frame Drum","Shaker","Tamburin"],"Elektronisch":["Synthesizer Pad","Lead Synth","Arpeggiator","Vocoder","Sampler","Turntables","Theremin","Laser Harp","Keytar"]};
const PRODUCTION=["Lo-Fi","Hi-Fi","Raw / Roh","Polished / Poliert","Vintage","Modern","Analog","Digital","Overproduced","Stripped Down","Wall of Sound","Minimalistisch","Maximalistisch","Bedroom Pop","Stadium Sound","Intimate","Atmospheric","Glitchy","Clean","Dirty / Gritty","Warm","Cold / Kalt","Saturated","Compressed","Dynamic","Spacious","Tight","Loose / Organisch","Live Sound","Studio Sound"];
const ERAS=["1950er","1960er","1970er","1980er","1990er","2000er","2010er","2020er","Retro-Futuristic","Timeless","Medieval","Renaissance","Victorian","Roaring 20s"];
const EFFECTS=["Reverb","Delay","Echo","Chorus","Phaser","Flanger","Distortion","Overdrive","Fuzz","Wah-Wah","Tremolo","Vibrato","Compression","Sidechain","Vinyl Crackle","Tape Hiss","Bitcrusher","Pitch Shift","Time Stretch","Reverse","Stutter","Glitch","Auto-Pan","Ring Modulation","Stereo Widening","Lo-Pass Filter","Hi-Pass Filter","Noise Gate"];
const TEMPOS=[{id:"very-slow",label:"Sehr Langsam",bpm:"40–60 BPM",icon:"🕊️"},{id:"slow",label:"Langsam",bpm:"60–80 BPM",icon:"🐌"},{id:"moderate",label:"Moderat",bpm:"80–110 BPM",icon:"🚶"},{id:"upbeat",label:"Beschwingt",bpm:"110–130 BPM",icon:"🏃"},{id:"fast",label:"Schnell",bpm:"130–160 BPM",icon:"⚡"},{id:"very-fast",label:"Sehr Schnell",bpm:"160–200+ BPM",icon:"🔥"}];
const STRUCTURES=[{id:"standard",label:"Standard",desc:"Intro → Verse → Chorus → Verse → Chorus → Bridge → Chorus → Outro"},{id:"simple",label:"Einfach",desc:"Intro → Verse → Chorus → Verse → Chorus → Outro"},{id:"epic",label:"Episch",desc:"Intro → Build → Verse → Pre-Chorus → Chorus → Verse → Chorus → Bridge → Final Chorus → Outro"},{id:"minimal",label:"Minimal",desc:"Intro → Loop → Variation → Loop → Fade"},{id:"progressive",label:"Progressiv",desc:"Part A → Part B → Part C → Part D (keine Wiederholungen)"},{id:"aaba",label:"AABA",desc:"Verse → Verse → Bridge → Verse (Jazz/Classic)"},{id:"freeform",label:"Frei",desc:"Keine feste Struktur"},{id:"ambient-flow",label:"Flow",desc:"Continuous evolution, keine Sektionen"}];
const LANGUAGES=["Deutsch","Englisch","Spanisch","Französisch","Italienisch","Portugiesisch","Japanisch","Koreanisch","Arabisch","Hindi","Türkisch","Russisch","Schwedisch","Gemischt (DE/EN)","Phantasiesprache"];
const PRESETS=[{name:"Heilungsreise",genre:["Ambient"],mood:["healing"],tempo:"slow",vocals:["Weiblich","Breathy / Hauchig"],instruments:["Klavier","Flöte","Harfe","Handpan"],production:["Atmospheric","Warm"],extras:"432 Hz, Naturklänge, meditativer Gesang, sanfte Wellen"},{name:"Empowerment Anthem",genre:["Dance Pop"],mood:["empowering"],tempo:"upbeat",vocals:["Weiblich","Belting","Layered Harmonies"],instruments:["Synthesizer","Drums","Bass","Klavier"],production:["Polished / Poliert","Stadium Sound"],extras:"Anthemic chorus, claps, powerful build-up"},{name:"Mystische Nacht",genre:["Downtempo"],mood:["mystical"],tempo:"moderate",vocals:["Androgyn","Whisper / Flüstern"],instruments:["Synthesizer Pad","Percussion","Cello","Theremin"],production:["Atmospheric","Dirty / Gritty"],extras:"Ethereal pads, tribal drums, reverb-heavy"},{name:"Midnight Lofi",genre:["Lo-Fi Hip-Hop"],mood:["nostalgic"],tempo:"slow",vocals:["Instrumental"],instruments:["Rhodes","Akustikgitarre","Akustik Drums"],production:["Lo-Fi","Vintage","Warm"],extras:"Vinyl crackle, jazz chords, rain ambience, tape hiss"},{name:"Neon City",genre:["Synthwave"],mood:["cinematic"],tempo:"upbeat",vocals:["Männlich","Vocoder"],instruments:["Analog Synth","Drum Machine","Lead Synth","Bass"],production:["Modern","Hi-Fi"],extras:"80s nostalgia, neon glow, driving arpeggios, gated reverb"},{name:"Soul Kitchen",genre:["Neo Soul"],mood:["sensual"],tempo:"moderate",vocals:["Weiblich","Raspy / Heiser"],instruments:["Rhodes","Upright Bass","Saxophon","Akustik Drums"],production:["Warm","Analog","Intimate"],extras:"Smooth grooves, vintage warmth, live feel"}];

// ═══════════════════════════════════════
//  STATE
// ═══════════════════════════════════════
const S={tab:'builder',genre:[],customGenre:'',moods:[],tempo:'moderate',customBpm:'',vocals:[],instruments:[],production:[],era:'',effects:[],structure:'standard',language:'Deutsch',extras:'',lyrics:'',songTitle:'',saved:JSON.parse(localStorage.getItem('suno_saved')||'[]'),collapsed:{},copied:null};

function persistSaved(){try{localStorage.setItem('suno_saved',JSON.stringify(S.saved))}catch(e){}}
function tog(a,v){const i=a.indexOf(v);i>=0?a.splice(i,1):a.push(v);return a}
function toast(msg){const t=document.getElementById('toast');t.textContent=msg;t.classList.add('show');setTimeout(()=>t.classList.remove('show'),1800);}
function vibrate(){try{navigator.vibrate&&navigator.vibrate(8)}catch(e){}}

function buildStyle(){
  const p=[];
  if(S.genre.length)p.push(S.genre.join(', ')+(S.customGenre?' / '+S.customGenre:''));
  const ml=S.moods.map(id=>MOODS.find(m=>m.id===id)?.label).filter(Boolean);
  if(ml.length)p.push(ml.join(', '));
  const t=TEMPOS.find(x=>x.id===S.tempo);
  if(t)p.push(S.customBpm?S.customBpm+' BPM':t.bpm);
  if(S.vocals.length)p.push(S.vocals.join(', '));
  if(S.instruments.length)p.push(S.instruments.join(', '));
  if(S.production.length)p.push(S.production.join(', '));
  if(S.era)p.push(S.era);
  if(S.effects.length)p.push(S.effects.join(', '));
  const s=STRUCTURES.find(x=>x.id===S.structure);
  if(s&&S.structure!=='standard')p.push(s.label+' Struktur');
  if(S.language!=='Deutsch')p.push('Sprache: '+S.language);
  if(S.extras.trim())p.push(S.extras.trim());
  return p.join(', ');
}
function buildFull(){let p='';if(S.songTitle)p+='Titel: '+S.songTitle+'\n\n';p+='Style: '+buildStyle()+'\n';if(S.lyrics.trim())p+='\nLyrics:\n'+S.lyrics.trim()+'\n';return p;}
function resetAll(){S.genre=[];S.customGenre='';S.moods=[];S.tempo='moderate';S.customBpm='';S.vocals=[];S.instruments=[];S.production=[];S.era='';S.effects=[];S.structure='standard';S.language='Deutsch';S.extras='';S.lyrics='';S.songTitle='';render();}
function copyText(t,id){navigator.clipboard.writeText(t).then(()=>{vibrate();toast('✓ In Zwischenablage kopiert!');S.copied=id;render();setTimeout(()=>{S.copied=null;render()},2000)});}
function savePrompt(){S.saved.unshift({id:Date.now(),name:S.songTitle||'Unbenannt',style:buildStyle(),full:buildFull(),date:new Date().toLocaleDateString('de-DE')});persistSaved();vibrate();toast('💾 Prompt gespeichert!');render();updateSavedBadge();}
function activeCount(){return S.genre.length+S.moods.length+S.vocals.length+S.instruments.length+S.production.length+S.effects.length+(S.era?1:0);}

function switchTab(tab,btn){
  S.tab=tab;vibrate();
  document.querySelectorAll('.nav-item').forEach(n=>n.classList.remove('active'));
  if(btn)btn.classList.add('active');
  else document.querySelector(`[data-tab="${tab}"]`)?.classList.add('active');
  updateIndicator();render();
}
function updateIndicator(){
  const active=document.querySelector('.nav-item.active');
  const ind=document.getElementById('navIndicator');
  if(active&&ind){ind.style.left=active.offsetLeft+(active.offsetWidth/2-24)+'px';}
}
function updateSavedBadge(){
  const btn=document.querySelector('[data-tab="saved"] .nav-label');
  if(btn)btn.textContent=S.saved.length?`Gespeichert (${S.saved.length})`:'Gespeichert';
}

// ═══════════════════════════════════════
//  DOM Helpers
// ═══════════════════════════════════════
function h(t,a,...c){const e=document.createElement(t);if(a)Object.entries(a).forEach(([k,v])=>{if(k==='className')e.className=v;else if(k==='innerHTML')e.innerHTML=v;else if(k.startsWith('on'))e.addEventListener(k.slice(2).toLowerCase(),v);else e.setAttribute(k,v)});c.flat(9).forEach(ch=>{if(ch!=null)e.appendChild(typeof ch==='string'?document.createTextNode(ch):ch)});return e}

function mkChipGroup(groups,sel,key){
  const f=document.createDocumentFragment();
  Object.entries(groups).forEach(([g,items])=>{
    f.appendChild(h('div',{className:'chip-group-label'},g));
    const cg=h('div',{className:'chip-group'});
    items.forEach(item=>{
      cg.appendChild(h('button',{className:'chip chip-sm'+(sel.includes(item)?' active':''),onClick:()=>{vibrate();tog(S[key],item);render()}},item));
    });
    f.appendChild(cg);
  });return f;
}
function mkSearchChips(items,sel,key,ph){
  const w=h('div');
  const sw=h('div',{className:'search-wrap'});
  sw.appendChild(h('span',{className:'search-ico'},'🔍'));
  const inp=h('input',{className:'input-search',placeholder:ph,type:'text'});
  sw.appendChild(inp);w.appendChild(sw);
  const cg=h('div',{className:'chip-group',style:'max-height:160px;overflow-y:auto'});
  function fill(f){cg.innerHTML='';(f?items.filter(i=>i.toLowerCase().includes(f.toLowerCase())):items).forEach(item=>{cg.appendChild(h('button',{className:'chip chip-sm'+(sel.includes(item)?' active':''),onClick:()=>{vibrate();tog(S[key],item);render()}},item))})}
  fill('');inp.addEventListener('input',e=>fill(e.target.value));
  w.appendChild(cg);return w;
}
function mkSection(key,icon,title,sub,fn){
  const cl=S.collapsed[key];
  const s=h('div',{className:'section'+(cl?' collapsed':'')});
  const hd=h('div',{className:'section-header',onClick:()=>{vibrate();S.collapsed[key]=!S.collapsed[key];render()}});
  hd.appendChild(h('span',{className:'section-icon'},icon));
  const tt=h('span',{className:'section-title'});tt.innerHTML=title;hd.appendChild(tt);
  hd.appendChild(h('span',{className:'section-arrow'},'▼'));
  s.appendChild(hd);
  if(!cl){const bd=h('div',{className:'section-body'});if(sub)bd.appendChild(h('div',{className:'section-subtitle'},sub));bd.appendChild(fn());s.appendChild(bd);}
  return s;
}

// ═══════════════════════════════════════
//  RENDER
// ═══════════════════════════════════════
function render(){
  const app=document.getElementById('app');app.innerHTML='';
  const pg=h('div',{className:'page-content'});

  // Header (only on builder)
  if(S.tab==='builder'){
    const hdr=h('div',{className:'header'});
    hdr.appendChild(h('div',{className:'header-icon'},'🎧'));
    hdr.appendChild(h('h1',null,'Suno Prompt Studio'));
    hdr.appendChild(h('div',{className:'header-sub'},'Dein Song · Dein Stil · Dein Prompt'));
    const stats=h('div',{className:'header-stats'});
    [['500+','Genres'],['24','Moods'],['70+','Instrumente'],['23','Vocals']].forEach(([n,l])=>{const s=h('span',{className:'header-stat'});s.innerHTML='<strong>'+n+'</strong> '+l;stats.appendChild(s)});
    hdr.appendChild(stats);pg.appendChild(hdr);
  }

  // ── PRESETS ──
  if(S.tab==='presets'){
    pg.appendChild(h('div',{style:'padding:20px 0 8px;text-align:center'},h('div',{style:'font-size:32px;margin-bottom:4px'},'✨'),h('div',{className:'header',innerHTML:'<h1 style="font-size:22px">Presets</h1><div class="header-sub" style="margin-top:2px">Schnellstart — tippe und passe im Builder an</div>'})));
    PRESETS.forEach(p=>{
      const c=h('button',{className:'preset-card',onClick:()=>{vibrate();S.genre=[...p.genre];S.moods=[...p.mood];S.tempo=p.tempo;S.vocals=[...p.vocals];S.instruments=[...p.instruments];S.production=[...p.production];S.extras=p.extras;switchTab('builder');toast('✨ Preset geladen!')}});
      c.appendChild(h('div',{className:'preset-name'},p.name));
      const ml=p.mood.map(id=>MOODS.find(m=>m.id===id)?.label).filter(Boolean).join(', ');
      c.appendChild(h('div',{className:'preset-desc'},p.genre.join(', ')+' · '+ml+' · '+p.extras));
      pg.appendChild(c);
    });
  }

  // ── SAVED ──
  if(S.tab==='saved'){
    pg.appendChild(h('div',{style:'padding:20px 0 8px;text-align:center'},h('div',{style:'font-size:32px;margin-bottom:4px'},'💾'),h('div',{className:'header',innerHTML:'<h1 style="font-size:22px">Gespeicherte Prompts</h1><div class="header-sub" style="margin-top:2px">'+S.saved.length+' Prompt'+(S.saved.length!==1?'s':'')+'</div>'})));
    if(!S.saved.length){
      const em=h('div',{className:'empty-state'});em.appendChild(h('div',{className:'empty-icon'},'📝'));em.appendChild(h('div',{className:'empty-text'},'Noch keine Prompts gespeichert.'));em.appendChild(h('div',{className:'empty-hint'},'Erstelle einen im Builder und speichere ihn.'));pg.appendChild(em);
    }else{
      S.saved.forEach(sp=>{
        const c=h('div',{className:'saved-card'});
        const hdr=h('div',{className:'saved-header'});hdr.appendChild(h('span',{className:'saved-name'},sp.name));hdr.appendChild(h('span',{className:'saved-date'},sp.date));c.appendChild(hdr);
        c.appendChild(h('div',{className:'saved-style'},sp.style.length>200?sp.style.slice(0,200)+'…':sp.style));
        const acts=h('div',{className:'saved-actions'});
        acts.appendChild(h('button',{className:'btn-copy'+(S.copied==='s'+sp.id?' copied':''),onClick:()=>copyText(sp.style,'s'+sp.id)},S.copied==='s'+sp.id?'✓':'📋 Style'));
        acts.appendChild(h('button',{className:'btn-copy'+(S.copied==='f'+sp.id?' copied':''),onClick:()=>copyText(sp.full,'f'+sp.id)},S.copied==='f'+sp.id?'✓':'📋 Voll'));
        acts.appendChild(h('button',{className:'btn-copy',onClick:()=>{vibrate();S.saved=S.saved.filter(x=>x.id!==sp.id);persistSaved();updateSavedBadge();toast('Prompt gelöscht');render()}},'✕'));
        c.appendChild(acts);pg.appendChild(c);
      });
    }
  }

  // ── SETTINGS / INFO ──
  if(S.tab==='settings'){
    pg.appendChild(h('div',{style:'padding:20px 0 8px;text-align:center'},h('div',{style:'font-size:32px;margin-bottom:4px'},'⚙️'),h('div',{className:'header',innerHTML:'<h1 style="font-size:22px">Info & Anleitung</h1>'})));
    const info=[
      ['📲','<strong>Als App installieren</strong><br>Tippe auf "Teilen" → "Zum Home-Bildschirm" (iOS) oder auf das Install-Banner (Android).'],
      ['🎛️','<strong>Builder</strong><br>Wähle Genre, Stimmung, Vocals, Instrumente und mehr. Der Prompt wird live generiert.'],
      ['📋','<strong>Kopieren</strong><br>Tippe "Kopieren" beim Style-Prompt und füge ihn in Sunos "Style of Music"-Feld ein. Lyrics separat.'],
      ['✨','<strong>Presets</strong><br>Schnellstart-Vorlagen. Tippe drauf und passe im Builder an.'],
      ['💾','<strong>Speichern</strong><br>Deine Prompts werden lokal auf dem Gerät gespeichert.'],
      ['🎵','<strong>Suno Tags</strong><br>Nutze in den Lyrics: [Verse], [Chorus], [Bridge], [Intro], [Outro], [Break], [Drop], [Hook], [Instrumental], [Fade Out]'],
      ['🔊','<strong>Tipp</strong><br>Halte den Style-Prompt unter 200 Zeichen für beste Ergebnisse bei Suno.'],
    ];
    info.forEach(([icon,text])=>{
      const card=h('div',{className:'saved-card',style:'margin-bottom:8px'});
      card.innerHTML='<div style="display:flex;gap:12px;align-items:flex-start"><span style="font-size:20px;flex-shrink:0">'+icon+'</span><div style="font-size:12.5px;color:var(--text-dim);line-height:1.6">'+text+'</div></div>';
      pg.appendChild(card);
    });
    // Version
    pg.appendChild(h('div',{style:'text-align:center;padding:20px 0;font-size:10px;color:var(--text-muted)'},'Suno Prompt Studio Pro v2.0 · Made with ♥'));
  }

  // ── BUILDER ──
  if(S.tab==='builder'){
    const ac=activeCount();
    if(ac>0){const bar=h('div',{className:'counter-bar'});bar.appendChild(h('span',null,'✦ '+ac+' ausgewählt'));bar.appendChild(h('button',{onClick:()=>{vibrate();resetAll()}},'↺ Reset'));pg.appendChild(bar);}

    pg.appendChild(mkSection('title','🏷️','Songtitel','Optional',()=>{const inp=h('input',{className:'input-text',type:'text',placeholder:'z.B. Sternenstaub',value:S.songTitle});inp.addEventListener('input',e=>{S.songTitle=e.target.value});return inp}));

    pg.appendChild(mkSection('genre','🎵','Genre'+(S.genre.length?' <span class="section-count">'+S.genre.length+'</span>':''),'Mehrfachauswahl · 500+ Genres · Suno v5.5 kompatibel',()=>{const w=h('div');w.appendChild(mkChipGroup(GENRES,S.genre,'genre'));const inp=h('input',{className:'input-text',type:'text',placeholder:'Custom Genre z.B. "Trap Soul meets Bossa Nova"',value:S.customGenre,style:'margin-top:12px'});inp.addEventListener('input',e=>{S.customGenre=e.target.value});w.appendChild(inp);return w}));

    pg.appendChild(mkSection('mood','🎭','Stimmung'+(S.moods.length?' <span class="section-count">'+S.moods.length+'</span>':''),'Welches Gefühl?',()=>{const cg=h('div',{className:'chip-group'});MOODS.forEach(m=>{const a=S.moods.includes(m.id);const c=h('button',{className:'chip'+(a?' active':''),style:a?'border-color:'+m.color+'60;background:'+m.color+'15;color:'+m.color:'',onClick:()=>{vibrate();tog(S.moods,m.id);render()}});c.innerHTML='<span class="mood-dot" style="background:'+m.color+';box-shadow:0 0 6px '+m.color+'80"></span>'+m.label;cg.appendChild(c)});return cg}));

    pg.appendChild(mkSection('tempo','⏱️','Tempo',null,()=>{const w=h('div');const cg=h('div',{className:'chip-group',style:'margin-bottom:10px'});TEMPOS.forEach(t=>{const c=h('button',{className:'chip'+(S.tempo===t.id?' active':''),onClick:()=>{vibrate();S.tempo=t.id;render()}});c.innerHTML=t.icon+' '+t.label+' <span style="opacity:.4;font-size:10px;margin-left:3px">'+t.bpm+'</span>';cg.appendChild(c)});w.appendChild(cg);const inp=h('input',{className:'input-text',type:'text',placeholder:'Exaktes BPM z.B. 128',value:S.customBpm,style:'width:160px'});inp.addEventListener('input',e=>{S.customBpm=e.target.value});w.appendChild(inp);return w}));

    pg.appendChild(mkSection('vocals','🎙️','Vocals'+(S.vocals.length?' <span class="section-count">'+S.vocals.length+'</span>':''),'Stimme + Stil',()=>{const w=h('div');w.appendChild(mkChipGroup(VOCALS,S.vocals,'vocals'));return w}));

    pg.appendChild(mkSection('instruments','🎹','Instrumente'+(S.instruments.length?' <span class="section-count">'+S.instruments.length+'</span>':''),'70+ in 6 Kategorien',()=>{const w=h('div');w.appendChild(mkChipGroup(INSTRUMENTS,S.instruments,'instruments'));return w}));

    pg.appendChild(mkSection('production','🎚️','Produktion'+(S.production.length?' <span class="section-count">'+S.production.length+'</span>':''),'Sound-Ästhetik',()=>mkSearchChips(PRODUCTION,S.production,'production','Produktionsstil suchen...')));

    pg.appendChild(mkSection('era','📅','Ära / Epoche',null,()=>{const cg=h('div',{className:'chip-group'});ERAS.forEach(e=>{cg.appendChild(h('button',{className:'chip chip-sm'+(S.era===e?' active':''),onClick:()=>{vibrate();S.era=S.era===e?'':e;render()}},e))});return cg}));

    pg.appendChild(mkSection('effects','🌀','Effekte'+(S.effects.length?' <span class="section-count">'+S.effects.length+'</span>':''),null,()=>mkSearchChips(EFFECTS,S.effects,'effects','Effekte suchen...')));

    pg.appendChild(mkSection('structure','📐','Songstruktur',null,()=>{const w=h('div');STRUCTURES.forEach(s=>{const a=S.structure===s.id;const c=h('div',{className:'struct-card'+(a?' active':''),onClick:()=>{vibrate();S.structure=s.id;render()}});c.appendChild(h('span',{className:'struct-label'},s.label));c.appendChild(h('div',{className:'struct-desc'},s.desc));w.appendChild(c)});return w}));

    pg.appendChild(mkSection('language','🌍','Sprache',null,()=>{const cg=h('div',{className:'chip-group'});LANGUAGES.forEach(l=>{cg.appendChild(h('button',{className:'chip chip-sm'+(S.language===l?' active':''),onClick:()=>{vibrate();S.language=l;render()}},l))});return cg}));

    pg.appendChild(mkSection('extras','✨','Extras & Vibes','Referenz-Künstler, Sounds...',()=>{const ta=h('textarea',{className:'input-area',rows:'3',placeholder:'"Enya meets Massive Attack, Naturklänge, 432 Hz, Tribal..."'});ta.value=S.extras;ta.addEventListener('input',e=>{S.extras=e.target.value});return ta}));

    pg.appendChild(mkSection('lyrics','📝','Lyrics','Optional · [Verse] [Chorus] [Bridge] Tags',()=>{const ta=h('textarea',{className:'input-area',rows:'8',placeholder:'[Intro]\n(Sanftes Klavier)\n\n[Verse 1]\nDie Sterne flüstern leise...\n\n[Chorus]\nWir tanzen durch die Nacht...'});ta.value=S.lyrics;ta.addEventListener('input',e=>{S.lyrics=e.target.value});return ta}));

    // ═══ OUTPUT ═══
    const sp=buildStyle(),fp=buildFull();
    const out=h('div',{className:'output-panel'});
    out.appendChild(h('div',{className:'output-title'},'🚀 Dein Suno Prompt'));
    out.appendChild(h('div',{className:'output-hint'},'Style → "Style of Music" · Lyrics → "Lyrics" Feld'));

    const sBlk=h('div',{style:'margin-bottom:14px'});
    const sHd=h('div',{style:'display:flex;justify-content:space-between;align-items:center;margin-bottom:5px'});
    sHd.appendChild(h('span',{className:'output-label'},'STYLE PROMPT'));
    sHd.appendChild(h('button',{className:'btn-copy'+(S.copied==='style'?' copied':''),onClick:()=>copyText(sp,'style')},S.copied==='style'?'✓ Kopiert!':'📋 Kopieren'));
    sBlk.appendChild(sHd);
    const sBox=h('div',{className:'output-box'});
    if(sp)sBox.textContent=sp;else sBox.innerHTML='<span class="ph">Wähle oben deine Optionen...</span>';
    sBlk.appendChild(sBox);
    if(sp){const warn=sp.length>200;sBlk.appendChild(h('div',{className:'charcount',style:warn?'color:#FF8C00':''},sp.length+' Zeichen'+(warn?' ⚠️ Suno empfiehlt <200':'')));}
    out.appendChild(sBlk);

    const fBlk=h('div');
    const fHd=h('div',{style:'display:flex;justify-content:space-between;align-items:center;margin-bottom:5px'});
    fHd.appendChild(h('span',{className:'output-label'},'VOLLSTÄNDIGER PROMPT'));
    fHd.appendChild(h('button',{className:'btn-copy'+(S.copied==='full'?' copied':''),onClick:()=>copyText(fp,'full')},S.copied==='full'?'✓ Kopiert!':'📋 Kopieren'));
    fBlk.appendChild(fHd);
    const fBox=h('div',{className:'output-box output-box-mono'});fBox.textContent=fp||'Wähle oben deine Optionen...';
    fBlk.appendChild(fBox);out.appendChild(fBlk);

    const br=h('div',{className:'btn-row'});
    br.appendChild(h('button',{className:'btn btn-primary',onClick:savePrompt},'💾 Speichern'));
    br.appendChild(h('button',{className:'btn btn-ghost',onClick:()=>{vibrate();resetAll()}},'↺ Reset'));
    out.appendChild(br);pg.appendChild(out);
  }

  app.appendChild(pg);
  updateSavedBadge();
  setTimeout(updateIndicator,50);
}

// ═══════════════════════════════════════
//  PWA Install
// ═══════════════════════════════════════
let deferredPrompt;
window.addEventListener('beforeinstallprompt',e=>{e.preventDefault();deferredPrompt=e;document.getElementById('installBanner').classList.add('show')});
document.getElementById('installBtn').addEventListener('click',()=>{if(deferredPrompt){deferredPrompt.prompt();deferredPrompt.userChoice.then(()=>{deferredPrompt=null;document.getElementById('installBanner').classList.remove('show')})}});
document.getElementById('installClose').addEventListener('click',()=>{document.getElementById('installBanner').classList.remove('show')});

// Show iOS install hint
if(/iPad|iPhone|iPod/.test(navigator.userAgent)&&!window.navigator.standalone){
  const b=document.getElementById('installBanner');
  b.querySelector('.install-banner-text').innerHTML='<strong>📲 Als App installieren</strong><small>Tippe auf <strong>Teilen ⬆</strong> → <strong>"Zum Home-Bildschirm"</strong></small>';
  b.querySelector('.install-btn').style.display='none';
  setTimeout(()=>b.classList.add('show'),2000);
}

// Register simple SW for offline caching
if('serviceWorker' in navigator){
  const swCode=`self.addEventListener('install',e=>{self.skipWaiting()});self.addEventListener('activate',e=>{e.waitUntil(clients.claim())});self.addEventListener('fetch',e=>{e.respondWith(caches.match(e.request).then(r=>r||fetch(e.request).then(res=>{if(res.ok){const c=res.clone();caches.open('suno-v2').then(cache=>cache.put(e.request,c))}return res}).catch(()=>caches.match(e.request)))})`;
  const blob=new Blob([swCode],{type:'application/javascript'});
  navigator.serviceWorker.register(URL.createObjectURL(blob)).catch(()=>{});
}

// Init
render();
window.addEventListener('resize',updateIndicator);
</script>
</body>
</html>
