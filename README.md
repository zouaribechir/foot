<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GOALSPHERE — The World of Football, In One Place</title>
<meta name="description" content="GOALSPHERE is the premium global football platform. Live scores, match analysis, transfer news, tactical intelligence, and editorial coverage of the world's game.">
<meta name="robots" content="index,follow">
<link rel="canonical" href="https://goalsphere.com/">
<meta property="og:type" content="website">
<meta property="og:title" content="GOALSPHERE — The World of Football, In One Place">
<meta property="og:description" content="Premium global football platform: live scores, match analysis, transfers, tactical intelligence.">
<meta property="og:url" content="https://goalsphere.com/">
<meta property="og:site_name" content="GOALSPHERE">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="GOALSPHERE — The World of Football, In One Place">
<meta name="twitter:description" content="Premium global football platform: live scores, match analysis, transfers, tactical intelligence.">
<link href="https://cdn.fontsource.org/css2?family=Inter:wght@300;400;500;600;700;800;900&family=Space+Grotesk:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<script type="application/ld+json">{"@context":"https://schema.org","@type":"Organization","name":"GOALSPHERE","url":"https://goalsphere.com","description":"The World of Football, In One Place."}</script>
<script type="application/ld+json">{"@context":"https://schema.org","@type":"WebSite","name":"GOALSPHERE","url":"https://goalsphere.com","potentialAction":{"@type":"SearchAction","target":"https://goalsphere.com/search?q={search_term_string}","query-input":"required name=search_term_string"}}</script>
<style>
:root{
  --bg:#050507;
  --bg-alt:#0a0a0e;
  --surface:#101014;
  --surface-hover:#15151b;
  --border:#1e1e26;
  --border-light:#2a2a35;
  --text:#f0f0f2;
  --text-sec:#9ca0ab;
  --text-muted:#5c606b;
  --accent:#00ff87;
  --accent-dim:rgba(0,255,135,.1);
  --accent-glow:rgba(0,255,135,.15);
  --red:#ff3b5c;
  --yellow:#ffc107;
  --blue:#3b82f6;
  --radius-sm:6px;
  --radius-md:10px;
  --radius-lg:16px;
  --font-sans:'Inter',system-ui,sans-serif;
  --font-display:'Space Grotesk','Inter',sans-serif;
  --font-mono:'JetBrains Mono',monospace;
  --container:1360px;
  --header-h:64px;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth;-webkit-text-size-adjust:100%}
body{font-family:var(--font-sans);background:var(--bg);color:var(--text);line-height:1.5;-webkit-font-smoothing:antialiased;overflow-x:hidden}
img{max-width:100%;display:block}
a{color:inherit;text-decoration:none}
button{font-family:inherit;cursor:pointer;border:0;background:none;color:inherit}
input{font-family:inherit;color:inherit}
::selection{background:var(--accent);color:#000}
::-webkit-scrollbar{width:8px;height:8px}
::-webkit-scrollbar-track{background:var(--bg)}
::-webkit-scrollbar-thumb{background:var(--border-light);border-radius:10px}

/* Typography */
.display{font-family:var(--font-display);font-weight:700;letter-spacing:-.03em;line-height:.95}
.h1{font-family:var(--font-display);font-weight:700;font-size:clamp(36px,5.5vw,64px);letter-spacing:-.03em;line-height:1}
.h2{font-family:var(--font-display);font-weight:600;font-size:clamp(24px,3vw,34px);letter-spacing:-.02em;line-height:1.1}
.h3{font-family:var(--font-display);font-weight:600;font-size:clamp(18px,2vw,22px);letter-spacing:-.01em;line-height:1.2}
.body-lg{font-size:17px;line-height:1.65;color:var(--text-sec)}
.body{font-size:15px;line-height:1.6;color:var(--text-sec)}
.small{font-size:13px;color:var(--text-muted)}
.meta{font-size:11px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-muted);font-weight:600}
.num{font-family:var(--font-mono);font-weight:600;letter-spacing:-.02em;font-variant-numeric:tabular-nums}

/* Layout */
.container{max-width:var(--container);margin:0 auto;padding:0 28px}
@media(max-width:640px){.container{padding:0 16px}}
.grid{display:grid;gap:20px}
.grid-editorial{display:grid;grid-template-columns:1fr 340px;gap:32px}
@media(max-width:1024px){.grid-editorial{grid-template-columns:1fr}}

/* Buttons */
.btn{display:inline-flex;align-items:center;gap:8px;padding:10px 20px;border-radius:var(--radius-sm);font-size:14px;font-weight:600;transition:all .2s ease;white-space:nowrap}
.btn-primary{background:var(--accent);color:#000}
.btn-primary:hover{background:#00e67a;transform:translateY(-1px);box-shadow:0 8px 24px var(--accent-glow)}
.btn-ghost{background:transparent;border:1px solid var(--border);color:var(--text)}
.btn-ghost:hover{border-color:var(--border-light);background:var(--surface)}
.icon-btn{width:40px;height:40px;border-radius:var(--radius-sm);display:grid;place-items:center;color:var(--text-sec);transition:all .2s ease}
.icon-btn:hover{color:var(--text);background:var(--surface)}

/* Badges */
.badge{display:inline-flex;align-items:center;gap:6px;padding:4px 10px;border-radius:100px;font-size:10px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;background:var(--surface);border:1px solid var(--border);color:var(--text-sec)}
.badge-live{background:rgba(255,59,92,.1);border-color:rgba(255,59,92,.25);color:var(--red)}
.badge-live::before{content:'';width:6px;height:6px;border-radius:50%;background:var(--red);animation:pulse 1.5s infinite}
.badge-accent{background:var(--accent-dim);border-color:rgba(0,255,135,.25);color:var(--accent)}
.badge-yellow{background:rgba(255,193,7,.1);border-color:rgba(255,193,7,.25);color:var(--yellow)}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.3}}

/* Cards */
.card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);overflow:hidden;transition:all .25s ease}
.card-hover:hover{border-color:var(--border-light);transform:translateY(-2px);box-shadow:0 12px 40px rgba(0,0,0,.4)}

/* Section */
.section{padding:64px 0;position:relative}
@media(max-width:768px){.section{padding:40px 0}}
.section-head{display:flex;align-items:flex-end;justify-content:space-between;margin-bottom:28px;gap:16px;flex-wrap:wrap}
.section-title{font-family:var(--font-display);font-weight:600;font-size:clamp(20px,2.5vw,26px);letter-spacing:-.015em}
.section-eyebrow{font-size:11px;letter-spacing:.12em;text-transform:uppercase;color:var(--accent);font-weight:700;margin-bottom:8px;display:flex;align-items:center;gap:10px}
.section-eyebrow::before{content:'';width:24px;height:2px;background:var(--accent)}

/* Header */
.header{position:fixed;top:0;left:0;right:0;z-index:100;height:var(--header-h);transition:all .3s ease;background:transparent}
.header.scrolled{background:rgba(5,5,7,.92);backdrop-filter:blur(20px) saturate(180%);-webkit-backdrop-filter:blur(20px) saturate(180%);border-bottom:1px solid var(--border)}
.header-inner{height:100%;display:flex;align-items:center;justify-content:space-between;gap:24px}
.logo{display:flex;align-items:center;gap:10px;font-family:var(--font-display);font-weight:700;font-size:18px;letter-spacing:-.01em}
.logo-mark{width:30px;height:30px;border-radius:8px;background:linear-gradient(135deg,var(--accent),#00cc6a);display:grid;place-items:center;box-shadow:0 4px 12px var(--accent-glow)}
.logo-mark svg{stroke:#000;stroke-width:2.5}
.nav{display:flex;align-items:center;gap:2px}
.nav a{padding:8px 12px;border-radius:var(--radius-sm);font-size:13px;font-weight:500;color:var(--text-sec);transition:all .2s ease}
.nav a:hover{color:var(--text);background:var(--surface)}
.nav a.active{color:var(--accent)}
.header-actions{display:flex;align-items:center;gap:4px}
.menu-btn{display:none}
@media(max-width:1024px){.nav{display:none}.menu-btn{display:grid}}

/* Mobile Nav */
.mobile-nav{position:fixed;inset:0;z-index:200;background:rgba(5,5,7,.98);backdrop-filter:blur(20px);transform:translateX(100%);transition:transform .35s cubic-bezier(.4,0,.2,1);padding:24px;overflow-y:auto}
.mobile-nav.open{transform:translateX(0)}
.mobile-nav-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:32px}
.mobile-nav-links a{padding:16px 0;font-size:20px;font-weight:500;border-bottom:1px solid var(--border);display:flex;justify-content:space-between;color:var(--text-sec)}
.mobile-nav-links a:hover,.mobile-nav-links a.active{color:var(--accent)}

/* Search Modal */
.search-modal{position:fixed;inset:0;z-index:300;background:rgba(5,5,7,.85);backdrop-filter:blur(20px);display:none;align-items:flex-start;justify-content:center;padding:100px 20px}
.search-modal.open{display:flex}
.search-box{width:100%;max-width:680px;background:var(--surface);border:1px solid var(--border-light);border-radius:var(--radius-lg);overflow:hidden;box-shadow:0 24px 80px rgba(0,0,0,.6)}
.search-input-wrap{display:flex;align-items:center;gap:12px;padding:16px 20px;border-bottom:1px solid var(--border)}
.search-input{flex:1;background:none;border:0;outline:0;font-size:16px;color:var(--text)}
.search-kbd{font-family:var(--font-mono);font-size:11px;padding:3px 6px;background:var(--bg);border:1px solid var(--border);border-radius:4px;color:var(--text-muted)}
.search-results{max-height:500px;overflow-y:auto;padding:8px}
.search-group{padding:8px 12px}
.search-group-title{font-size:11px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-muted);font-weight:700;margin-bottom:8px}
.search-result{display:flex;align-items:center;gap:12px;padding:10px 12px;border-radius:8px;cursor:pointer;transition:background .15s ease}
.search-result:hover{background:var(--surface-hover)}
.crest{width:28px;height:28px;border-radius:6px;background:var(--surface-hover);border:1px solid var(--border);display:grid;place-items:center;font-family:var(--font-display);font-weight:700;font-size:10px;color:var(--text)}

/* Hero */
.hero{position:relative;min-height:720px;padding:calc(var(--header-h) + 40px) 0 60px;overflow:hidden;display:flex;align-items:flex-end}
.hero-bg{position:absolute;inset:0;z-index:0;background:linear-gradient(180deg,#0d0d12 0%,#050507 100%)}
.hero-img{position:absolute;inset:0;z-index:0;background:radial-gradient(ellipse at 70% 40%,rgba(0,255,135,.08),transparent 50%),radial-gradient(ellipse at 20% 80%,rgba(59,130,246,.06),transparent 50%),linear-gradient(135deg,#111118 0%,#08080c 100%)}
.hero-img::after{content:'';position:absolute;inset:0;background-image:linear-gradient(rgba(255,255,255,.02) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.02) 1px,transparent 1px);background-size:80px 80px;mask-image:radial-gradient(ellipse at center,black 20%,transparent 70%)}
.hero-overlay{position:absolute;inset:0;z-index:1;background:linear-gradient(180deg,rgba(5,5,7,.3) 0%,rgba(5,5,7,.6) 50%,rgba(5,5,7,1) 100%)}
.hero-content{position:relative;z-index:2;width:100%}
.hero-grid{display:grid;grid-template-columns:1.2fr 1fr;gap:48px;align-items:end}
@media(max-width:960px){.hero-grid{grid-template-columns:1fr;gap:32px}}
.hero-badge{margin-bottom:20px}
.hero-title{font-family:var(--font-display);font-weight:700;font-size:clamp(42px,6vw,72px);line-height:.95;letter-spacing:-.03em;margin-bottom:24px}
.hero-title .accent{background:linear-gradient(135deg,var(--accent),#7cffb5);-webkit-background-clip:text;background-clip:text;color:transparent}
.hero-summary{font-size:clamp(16px,1.4vw,18px);line-height:1.6;color:var(--text-sec);max-width:600px;margin-bottom:28px}
.hero-meta{display:flex;align-items:center;gap:16px;flex-wrap:wrap;margin-bottom:32px;font-size:13px;color:var(--text-muted)}
.hero-meta .dot{width:3px;height:3px;border-radius:50%;background:var(--text-muted)}
.hero-actions{display:flex;gap:12px;flex-wrap:wrap}
.hero-panel{background:rgba(16,16,20,.85);border:1px solid var(--border);border-radius:var(--radius-lg);padding:24px;backdrop-filter:blur(20px);position:relative;overflow:hidden}
.hero-panel::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,rgba(255,255,255,.08),transparent)}
.hero-panel-label{font-size:10px;letter-spacing:.12em;text-transform:uppercase;color:var(--accent);font-weight:700;margin-bottom:16px;display:flex;align-items:center;gap:8px}
.hero-panel-label::before{content:'';width:6px;height:6px;border-radius:50%;background:var(--accent);box-shadow:0 0 10px var(--accent)}
.hero-score-row{display:grid;grid-template-columns:1fr auto 1fr;gap:16px;align-items:center;margin-bottom:16px}
.hero-score-val{font-family:var(--font-mono);font-size:48px;font-weight:700;letter-spacing:-.03em;line-height:1}
.hero-team-name{font-size:14px;font-weight:600;text-align:center}
.hero-stats{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:16px;padding-top:16px;border-top:1px solid var(--border)}
.hero-stat{text-align:center;padding:8px;background:var(--bg);border-radius:var(--radius-sm)}
.hero-stat-val{font-family:var(--font-mono);font-size:16px;font-weight:700}
.hero-stat-lbl{font-size:9px;color:var(--text-muted);text-transform:uppercase;letter-spacing:.08em;margin-top:2px}

/* Breaking News */
.breaking{background:var(--surface);border-bottom:1px solid var(--border);padding:10px 0;overflow:hidden}
.breaking-inner{display:flex;align-items:center;gap:16px;max-width:var(--container);margin:0 auto;padding:0 28px;font-size:13px}
.breaking-label{background:var(--red);color:#fff;padding:3px 8px;border-radius:4px;font-size:10px;font-weight:800;letter-spacing:.08em;text-transform:uppercase;flex-shrink:0}
.breaking-text{color:var(--text-sec);white-space:nowrap;overflow:hidden;text-overflow:ellipsis}

/* Scores Rail */
.scores-rail{padding:20px 0;border-bottom:1px solid var(--border);background:var(--bg-alt)}
.scores-rail-head{display:flex;align-items:center;justify-content:space-between;margin-bottom:14px;padding:0 28px;max-width:var(--container);margin-left:auto;margin-right:auto}
.scores-rail-title{display:flex;align-items:center;gap:10px;font-size:12px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:var(--text-sec)}
.scores-scroll{display:flex;gap:12px;overflow-x:auto;scroll-behavior:smooth;padding:4px 28px 12px;scrollbar-width:none;cursor:grab}
.scores-scroll::-webkit-scrollbar{display:none}
.score-card{flex:0 0 240px;background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);padding:12px;transition:all .2s ease;position:relative}
.score-card:hover{border-color:var(--border-light);transform:translateY(-2px)}
.score-card.live{border-color:rgba(0,255,135,.2)}
.score-card.live::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,var(--accent),transparent)}
.score-card-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px;font-size:9px;letter-spacing:.08em;text-transform:uppercase;color:var(--text-muted)}
.score-card-teams{display:flex;flex-direction:column;gap:6px}
.score-card-team{display:flex;align-items:center;gap:8px;font-size:13px;font-weight:500}
.score-card-team .crest{width:22px;height:22px;border-radius:5px;font-size:9px}
.score-card-team .score{margin-left:auto;font-family:var(--font-mono);font-weight:700;font-size:14px}
.score-card-foot{margin-top:8px;padding-top:8px;border-top:1px solid var(--border);display:flex;justify-content:space-between;font-size:10px;color:var(--text-muted)}

/* Filters */
.filters{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:24px}
.filter-chip{padding:7px 14px;border-radius:100px;background:var(--surface);border:1px solid var(--border);font-size:12px;font-weight:500;color:var(--text-sec);transition:all .2s ease;cursor:pointer}
.filter-chip:hover{border-color:var(--border-light)}
.filter-chip.active{background:var(--accent-dim);border-color:rgba(0,255,135,.3);color:var(--accent)}

/* News Grid */
.news-grid{display:grid;grid-template-columns:1.3fr 1fr;gap:24px}
@media(max-width:900px){.news-grid{grid-template-columns:1fr}}
.news-featured{position:relative;border-radius:var(--radius-lg);overflow:hidden;background:var(--surface);border:1px solid var(--border);min-height:480px;display:flex;flex-direction:column;justify-content:flex-end;cursor:pointer;transition:all .3s ease}
.news-featured:hover{border-color:var(--border-light)}
.news-featured-bg{position:absolute;inset:0;background:linear-gradient(180deg,transparent 20%,rgba(5,5,7,.5) 60%,rgba(5,5,7,.98) 100%),radial-gradient(ellipse at 70% 30%,rgba(0,255,135,.12),transparent 60%),linear-gradient(135deg,#15151c,#0a0a0e)}
.news-featured-content{position:relative;padding:28px;z-index:1}
.news-featured-title{font-family:var(--font-display);font-weight:700;font-size:clamp(24px,3vw,34px);line-height:1.1;letter-spacing:-.02em;margin-bottom:12px}
.news-featured-summary{color:var(--text-sec);font-size:15px;line-height:1.55;margin-bottom:14px}
.news-list{display:flex;flex-direction:column;gap:12px}
.news-item{display:grid;grid-template-columns:100px 1fr;gap:14px;padding:12px;border-radius:var(--radius-md);background:var(--surface);border:1px solid var(--border);transition:all .2s ease;cursor:pointer}
.news-item:hover{border-color:var(--border-light);background:var(--surface-hover)}
.news-item-img{aspect-ratio:1;border-radius:var(--radius-sm);background:linear-gradient(135deg,var(--surface-hover),var(--bg));position:relative;overflow:hidden}
.news-item-img::after{content:'';position:absolute;inset:0;background:radial-gradient(circle at 30% 30%,rgba(0,255,135,.1),transparent 60%)}
.news-item-body{display:flex;flex-direction:column;justify-content:center;gap:4px}
.news-item-cat{font-size:9px;letter-spacing:.1em;text-transform:uppercase;color:var(--accent);font-weight:700}
.news-item-title{font-family:var(--font-display);font-weight:600;font-size:14px;line-height:1.3;letter-spacing:-.01em}
.news-item-meta{font-size:11px;color:var(--text-muted)}

/* Match Card */
.match-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);padding:16px;transition:all .25s ease;cursor:pointer}
.match-card:hover{border-color:var(--border-light);transform:translateY(-2px);box-shadow:0 8px 30px rgba(0,0,0,.3)}
.match-card-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:12px;font-size:10px;letter-spacing:.08em;text-transform:uppercase;color:var(--text-muted)}
.match-card-teams{display:flex;flex-direction:column;gap:8px}
.match-card-team{display:grid;grid-template-columns:24px 1fr auto;gap:10px;align-items:center;font-size:13px;font-weight:500}
.match-card-team .crest{width:24px;height:24px;border-radius:5px;font-size:9px}
.match-card-team .score{font-family:var(--font-mono);font-weight:700;font-size:15px}
.match-card-foot{margin-top:12px;padding-top:10px;border-top:1px solid var(--border);display:flex;justify-content:space-between;font-size:11px;color:var(--text-muted)}

/* Featured Match */
.featured-match{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-lg);padding:32px;position:relative;overflow:hidden}
.featured-match::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,rgba(0,255,135,.15),transparent)}
.fm-info{text-align:center;margin-bottom:24px}
.fm-comp{font-size:11px;letter-spacing:.1em;text-transform:uppercase;color:var(--accent);font-weight:700;margin-bottom:6px}
.fm-venue{font-size:12px;color:var(--text-muted)}
.fm-scoreboard{display:grid;grid-template-columns:1fr auto 1fr;gap:24px;align-items:center;text-align:center;margin-bottom:24px}
.fm-crest{width:72px;height:72px;border-radius:14px;font-size:24px;margin:0 auto 10px}
.fm-team-name{font-family:var(--font-display);font-size:18px;font-weight:600}
.fm-score{font-family:var(--font-mono);font-size:64px;font-weight:700;letter-spacing:-.04em;line-height:1}
.fm-score .sep{color:var(--text-muted);margin:0 6px}
.stat-compare{display:flex;flex-direction:column;gap:12px;max-width:500px;margin:0 auto}
.stat-row{display:grid;grid-template-columns:50px 1fr 50px;gap:10px;align-items:center}
.stat-row .val{font-family:var(--font-mono);font-weight:600;font-size:14px}
.stat-row .val.home{text-align:right}
.stat-row .val.away{text-align:left}
.stat-row .label{text-align:center;font-size:11px;color:var(--text-muted);text-transform:uppercase;letter-spacing:.06em}
.stat-bar-wrap{display:flex;gap:3px;height:5px}
.stat-bar{flex:1;background:var(--bg);border-radius:100px;overflow:hidden}
.stat-bar-fill{height:100%;border-radius:100px;transition:width .6s ease}
.stat-bar.home .stat-bar-fill{background:var(--accent);float:right}
.stat-bar.away .stat-bar-fill{background:var(--text-muted)}

/* Transfer Card */
.transfer-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);padding:16px;transition:all .2s ease}
.transfer-card:hover{border-color:var(--border-light);transform:translateY(-2px)}
.tc-head{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:12px}
.tc-player{display:flex;align-items:center;gap:10px}
.tc-avatar{width:40px;height:40px;border-radius:50%;background:var(--surface-hover);border:1px solid var(--border);display:grid;place-items:center;font-family:var(--font-display);font-weight:700;font-size:14px}
.tc-info h4{font-size:14px;font-weight:600;margin-bottom:2px}
.tc-info p{font-size:11px;color:var(--text-muted)}
.tc-clubs{display:flex;align-items:center;gap:8px;margin-top:12px;padding-top:12px;border-top:1px solid var(--border)}
.tc-club{display:flex;align-items:center;gap:6px;font-size:12px;font-weight:500}
.tc-arrow{color:var(--text-muted);flex:1;display:grid;place-items:center}
.tc-fee{margin-top:10px;font-family:var(--font-mono);font-size:16px;font-weight:700;color:var(--accent)}

/* League Card */
.league-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);padding:18px;transition:all .25s ease;cursor:pointer;position:relative;overflow:hidden}
.league-card:hover{border-color:var(--border-light);transform:translateY(-2px)}
.lc-logo{width:52px;height:52px;border-radius:10px;background:var(--surface-hover);border:1px solid var(--border);display:grid;place-items:center;margin-bottom:14px;font-family:var(--font-display);font-weight:700;font-size:16px}
.league-card h3{font-size:16px;font-weight:600;margin-bottom:4px}
.league-card p{font-size:12px;color:var(--text-muted)}
.lc-meta{display:flex;gap:10px;margin-top:10px;font-size:10px;color:var(--text-muted)}

/* Team Card */
.team-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);padding:18px;transition:all .25s ease;cursor:pointer}
.team-card:hover{border-color:var(--border-light);transform:translateY(-2px)}
.tc-head{display:flex;align-items:center;gap:12px;margin-bottom:12px}
.tc-head .crest{width:44px;height:44px;border-radius:8px;font-size:14px}
.team-card h3{font-size:15px;font-weight:600;margin-bottom:2px}
.team-card p{font-size:11px;color:var(--text-muted)}
.form-row{display:flex;gap:3px;margin-top:10px}
.form-dot{width:18px;height:18px;border-radius:3px;display:grid;place-items:center;font-size:9px;font-weight:700;color:#fff}
.form-W{background:#00cc6a}
.form-D{background:#6b7280}
.form-L{background:#ef4444}

/* Player Card */
.player-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);padding:16px;transition:all .25s ease;cursor:pointer;position:relative;overflow:hidden}
.player-card:hover{border-color:var(--border-light);transform:translateY(-2px)}
.pc-photo{aspect-ratio:1;border-radius:var(--radius-sm);margin-bottom:12px;background:linear-gradient(135deg,var(--surface-hover),var(--bg));position:relative;overflow:hidden;display:grid;place-items:center;font-family:var(--font-display);font-weight:700;font-size:40px;color:var(--text-muted)}
.pc-photo::after{content:'';position:absolute;inset:0;background:radial-gradient(circle at 30% 30%,rgba(0,255,135,.08),transparent 60%)}
.player-card h3{font-size:14px;font-weight:600;margin-bottom:2px}
.pc-pos{font-size:10px;color:var(--accent);text-transform:uppercase;letter-spacing:.08em;font-weight:700;margin-bottom:6px}
.pc-club{font-size:11px;color:var(--text-muted)}
.pc-num{position:absolute;top:12px;right:12px;font-family:var(--font-mono);font-size:12px;color:var(--text-muted)}

/* Standings */
.standings{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);overflow:hidden}
.standings table{width:100%;border-collapse:collapse;font-size:13px}
.standings thead{background:var(--surface-hover)}
.standings th{text-align:left;padding:10px 12px;font-size:10px;letter-spacing:.08em;text-transform:uppercase;color:var(--text-muted);font-weight:700;border-bottom:1px solid var(--border)}
.standings th.num{text-align:center}
.standings td{padding:10px 12px;border-bottom:1px solid var(--border)}
.standings td.num{text-align:center;font-family:var(--font-mono);font-weight:600}
.standings tbody tr{transition:background .15s ease}
.standings tbody tr:hover{background:var(--surface-hover)}
.standings tbody tr:last-child td{border-bottom:0}
.standings .team-cell{display:flex;align-items:center;gap:8px;font-weight:500}
.standings .pos{font-family:var(--font-mono);font-weight:700;color:var(--text-sec);width:28px}
.standings .pts{font-family:var(--font-mono);font-weight:700;color:var(--accent)}
.zone-ucl{box-shadow:inset 3px 0 0 var(--accent)}
.zone-uel{box-shadow:inset 3px 0 0 var(--blue)}
.zone-rel{box-shadow:inset 3px 0 0 var(--red)}

/* Pitch */
.pitch{position:relative;aspect-ratio:2/3;max-width:460px;margin:0 auto;background:repeating-linear-gradient(0deg,rgba(0,255,135,.03) 0,rgba(0,255,135,.03) 10%,transparent 10%,transparent 20%),linear-gradient(180deg,#0a2215 0%,#0d2e1d 50%,#0a2215 100%);border-radius:var(--radius-md);border:1px solid rgba(0,255,135,.15);overflow:hidden}
.pitch::before{content:'';position:absolute;inset:0;background:linear-gradient(rgba(255,255,255,.12) 1px,transparent 1px) 0 50%/100% 1px no-repeat,radial-gradient(circle at 50% 50%,transparent 55px,rgba(255,255,255,.12) 55px,rgba(255,255,255,.12) 56px,transparent 56px),linear-gradient(rgba(255,255,255,.12) 1px,transparent 1px) 0 0/100% 1px no-repeat,linear-gradient(rgba(255,255,255,.12) 1px,transparent 1px) 0 100%/100% 1px no-repeat,linear-gradient(rgba(255,255,255,.12) 1px,transparent 1px) 0 0/1px 100% no-repeat,linear-gradient(rgba(255,255,255,.12) 1px,transparent 1px) 100% 0/1px 100% no-repeat}
.pp{position:absolute;transform:translate(-50%,-50%);display:flex;flex-direction:column;align-items:center;gap:3px;z-index:2}
.pp-dot{width:30px;height:30px;border-radius:50%;background:linear-gradient(135deg,var(--accent),#00b85c);display:grid;place-items:center;font-family:var(--font-mono);font-weight:700;font-size:11px;color:#000;box-shadow:0 4px 10px rgba(0,0,0,.4),0 0 0 2px rgba(255,255,255,.08)}
.pp.captain .pp-dot{box-shadow:0 4px 10px rgba(0,0,0,.4),0 0 0 2px var(--accent)}
.pp-name{font-size:9px;font-weight:600;color:#fff;background:rgba(0,0,0,.6);padding:1px 5px;border-radius:3px;white-space:nowrap;backdrop-filter:blur(4px)}

/* Intel */
.intel-card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);padding:20px;position:relative;overflow:hidden}
.intel-card::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,var(--accent),transparent)}
.ic-prompt{display:flex;gap:10px;padding:12px;background:var(--surface-hover);border:1px solid var(--border);border-radius:var(--radius-sm);margin-bottom:14px}
.ic-icon{width:28px;height:28px;border-radius:6px;background:var(--accent-dim);color:var(--accent);display:grid;place-items:center;flex-shrink:0}
.ic-text{font-size:13px;color:var(--text-sec);line-height:1.5}
.ic-response{font-size:13px;color:var(--text-sec);line-height:1.7}
.ic-tag{display:inline-flex;align-items:center;gap:6px;font-size:9px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-muted);margin-top:14px;padding-top:12px;border-top:1px solid var(--border)}

/* Newsletter */
.newsletter{background:linear-gradient(135deg,var(--surface) 0%,var(--surface-hover) 100%);border:1px solid var(--border);border-radius:var(--radius-lg);padding:48px;position:relative;overflow:hidden;text-align:center}
.newsletter::before{content:'';position:absolute;inset:0;background:radial-gradient(circle at 20% 30%,rgba(0,255,135,.08),transparent 50%),radial-gradient(circle at 80% 70%,rgba(59,130,246,.06),transparent 50%)}
.newsletter>*{position:relative;z-index:1}
.newsletter h2{font-family:var(--font-display);font-size:clamp(22px,3vw,30px);font-weight:600;letter-spacing:-.02em;margin-bottom:10px}
.newsletter p{color:var(--text-sec);margin-bottom:20px;max-width:460px;margin-left:auto;margin-right:auto;font-size:15px}
.nl-form{display:flex;gap:8px;max-width:460px;margin:0 auto;flex-wrap:wrap}
.nl-form input{flex:1;min-width:180px;padding:10px 14px;border-radius:var(--radius-sm);background:var(--bg);border:1px solid var(--border);color:var(--text);font-size:14px;outline:none}
.nl-form input:focus{border-color:var(--accent)}

/* Footer */
.footer{background:var(--bg-alt);border-top:1px solid var(--border);padding:64px 0 24px;margin-top:64px}
.footer-grid{display:grid;grid-template-columns:1.4fr repeat(4,1fr);gap:40px;margin-bottom:40px}
@media(max-width:900px){.footer-grid{grid-template-columns:1fr 1fr;gap:28px}}
@media(max-width:500px){.footer-grid{grid-template-columns:1fr}}
.footer-brand p{color:var(--text-muted);font-size:13px;margin:14px 0;max-width:300px;line-height:1.6}
.footer-social{display:flex;gap:6px}
.footer-social a{width:34px;height:34px;border-radius:6px;background:var(--surface);border:1px solid var(--border);display:grid;place-items:center;color:var(--text-sec);transition:all .2s ease}
.footer-social a:hover{color:var(--accent);border-color:var(--accent)}
.footer-col h4{font-size:11px;letter-spacing:.1em;text-transform:uppercase;color:var(--text);font-weight:700;margin-bottom:14px}
.footer-col ul{list-style:none;display:flex;flex-direction:column;gap:8px}
.footer-col a{font-size:13px;color:var(--text-muted);transition:color .15s ease}
.footer-col a:hover{color:var(--accent)}
.footer-bottom{padding-top:24px;border-top:1px solid var(--border);display:flex;justify-content:space-between;align-items:center;font-size:12px;color:var(--text-muted);flex-wrap:wrap;gap:12px}

/* Article */
.article{max-width:740px;margin:0 auto}
.article-head{margin-bottom:36px}
.breadcrumb{display:flex;gap:8px;align-items:center;font-size:12px;color:var(--text-muted);margin-bottom:20px;flex-wrap:wrap}
.breadcrumb a:hover{color:var(--accent)}
.breadcrumb .sep{color:var(--text-muted)}
.article-title{font-family:var(--font-display);font-weight:700;font-size:clamp(30px,5vw,48px);line-height:1.05;letter-spacing:-.025em;margin-bottom:14px}
.article-subtitle{font-size:clamp(16px,1.5vw,19px);color:var(--text-sec);line-height:1.5;margin-bottom:20px}
.article-meta{display:flex;gap:14px;align-items:center;font-size:12px;color:var(--text-muted);flex-wrap:wrap;padding-bottom:20px;border-bottom:1px solid var(--border)}
.article-hero{aspect-ratio:16/9;border-radius:var(--radius-md);background:linear-gradient(135deg,rgba(0,255,135,.08),rgba(59,130,246,.04)),linear-gradient(135deg,var(--surface-hover),var(--bg));margin-bottom:36px;position:relative;overflow:hidden}
.article-hero::after{content:'';position:absolute;inset:0;background:radial-gradient(circle at 70% 30%,rgba(0,255,135,.12),transparent 60%)}
.article-body{font-size:16px;line-height:1.75;color:var(--text-sec)}
.article-body h2{font-family:var(--font-display);font-size:26px;font-weight:600;color:var(--text);margin:36px 0 14px;letter-spacing:-.015em}
.article-body h3{font-family:var(--font-display);font-size:20px;font-weight:600;color:var(--text);margin:28px 0 10px}
.article-body p{margin-bottom:18px}
.article-body blockquote{border-left:3px solid var(--accent);padding:8px 0 8px 22px;margin:24px 0;font-family:var(--font-display);font-size:20px;font-weight:500;color:var(--text);line-height:1.4;font-style:italic}
.article-body ul,.article-body ol{margin:18px 0;padding-left:22px}
.article-body li{margin-bottom:6px}
.article-body strong{color:var(--text);font-weight:600}
.stat-inline{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-sm);padding:18px;margin:22px 0}
.stat-inline h4{font-size:10px;letter-spacing:.1em;text-transform:uppercase;color:var(--accent);margin-bottom:10px;font-weight:700}
.stat-inline .big{font-family:var(--font-mono);font-size:32px;font-weight:700;color:var(--text)}

/* Match Center */
.match-header{background:linear-gradient(180deg,var(--surface) 0%,var(--bg) 100%);border-bottom:1px solid var(--border);padding:28px 0}
.mc-scoreboard{display:grid;grid-template-columns:1fr auto 1fr;gap:28px;align-items:center;margin:28px 0;text-align:center}
.mc-crest{width:72px;height:72px;border-radius:14px;font-size:24px;margin:0 auto 10px}
.mc-team{font-family:var(--font-display);font-size:18px;font-weight:600}
.mc-score{font-family:var(--font-mono);font-size:68px;font-weight:700;letter-spacing:-.04em;line-height:1}
.mc-score .sep{color:var(--text-muted);margin:0 6px}
.tabs{display:flex;gap:0;border-bottom:1px solid var(--border);overflow-x:auto;scrollbar-width:none;margin-bottom:28px}
.tabs::-webkit-scrollbar{display:none}
.tab{padding:12px 16px;font-size:13px;font-weight:500;color:var(--text-muted);border-bottom:2px solid transparent;transition:all .2s ease;white-space:nowrap}
.tab:hover{color:var(--text)}
.tab.active{color:var(--accent);border-bottom-color:var(--accent)}

/* Timeline */
.timeline{position:relative;padding:16px 0}
.tl-line{position:absolute;left:50%;top:0;bottom:0;width:1px;background:var(--border);transform:translateX(-50%)}
.tl-event{position:relative;display:grid;grid-template-columns:1fr auto 1fr;gap:16px;padding:10px 0;align-items:center}
.tl-minute{font-family:var(--font-mono);font-weight:700;font-size:13px;color:var(--text-sec)}
.tl-event.home .tl-minute{text-align:right}
.tl-event.away .tl-minute{text-align:left}
.tl-marker{width:32px;height:32px;border-radius:50%;background:var(--surface);border:1px solid var(--border);display:grid;place-items:center;font-size:14px;position:relative;z-index:1}
.tl-event.goal .tl-marker{background:var(--accent-dim);border-color:var(--accent);color:var(--accent)}
.tl-event.yellow .tl-marker{background:rgba(255,193,7,.1);border-color:var(--yellow);color:var(--yellow)}
.tl-event.red .tl-marker{background:rgba(255,59,92,.1);border-color:var(--red);color:var(--red)}

/* Page Header */
.page-header{padding:calc(var(--header-h) + 36px) 0 36px;border-bottom:1px solid var(--border);background:linear-gradient(180deg,var(--surface) 0%,var(--bg) 100%)}
.page-header h1{font-family:var(--font-display);font-size:clamp(30px,4vw,44px);font-weight:700;letter-spacing:-.02em;margin-bottom:6px}
.page-header p{color:var(--text-sec);font-size:15px;max-width:600px}

/* Demo Badge */
.demo-badge{position:fixed;bottom:16px;right:16px;z-index:50;padding:6px 12px;border-radius:100px;background:var(--surface);border:1px solid var(--border);font-size:10px;color:var(--text-muted);letter-spacing:.06em;text-transform:uppercase;backdrop-filter:blur(10px)}

/* Utility */
.divider{height:1px;background:var(--border);margin:40px 0}
.text-accent{color:var(--accent)}
.text-muted{color:var(--text-muted)}
.mt-2{margin-top:16px}.mt-3{margin-top:24px}.mt-4{margin-top:32px}
.mb-2{margin-bottom:16px}.mb-3{margin-bottom:24px}
.flex{display:flex}.items-center{align-items:center}.gap-2{gap:16px}

@media(prefers-reduced-motion:reduce){*,*::before,*::after{animation-duration:.01ms!important;transition-duration:.01ms!important}}
@media(max-width:640px){
  .hero{min-height:auto;padding:calc(var(--header-h) + 24px) 0 24px}
  .hero-stats{grid-template-columns:repeat(3,1fr);gap:4px}
  .mc-scoreboard{gap:12px}
  .mc-crest{width:52px;height:52px;font-size:18px}
  .mc-score{font-size:44px}
  .newsletter{padding:28px 16px}
  .standings table{font-size:11px}
  .standings th,.standings td{padding:8px 4px}
  .hide-mobile{display:none}
  .fm-scoreboard{gap:12px}
  .fm-crest{width:52px;height:52px;font-size:18px}
  .fm-score{font-size:44px}
}
</style>
</head>
<body>

<header class="header" id="header">
  <div class="container header-inner">
    <a href="#/" class="logo" aria-label="GOALSPHERE Home">
      <span class="logo-mark"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><path d="M12 2v20M2 12h20"/></svg></span>
      GOAL<span style="color:var(--accent)">SPHERE</span>
    </a>
    <nav class="nav" aria-label="Main navigation">
      <a href="#/" data-route="/">Home</a>
      <a href="#/live" data-route="/live">Live</a>
      <a href="#/matches" data-route="/matches">Matches</a>
      <a href="#/news" data-route="/news">News</a>
      <a href="#/transfers" data-route="/transfers">Transfers</a>
      <a href="#/leagues" data-route="/leagues">Leagues</a>
      <a href="#/teams" data-route="/teams">Teams</a>
      <a href="#/players" data-route="/players">Players</a>
      <a href="#/standings" data-route="/standings">Standings</a>
      <a href="#/history" data-route="/history">History</a>
      <a href="#/intel" data-route="/intel">Intel</a>
    </nav>
    <div class="header-actions">
      <button class="icon-btn" aria-label="Search" onclick="openSearch()"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg></button>
      <button class="icon-btn" aria-label="Favorites"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"/></svg></button>
      <button class="icon-btn" aria-label="Profile"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M19 21v-2a4 4 0 0 0-4-4H9a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg></button>
      <button class="icon-btn menu-btn" aria-label="Menu" onclick="toggleMobileNav()"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><line x1="4" x2="20" y1="12" y2="12"/><line x1="4" x2="20" y1="6" y2="6"/><line x1="4" x2="20" y1="18" y2="18"/></svg></button>
    </div>
  </div>
</header>

<div class="mobile-nav" id="mobileNav" aria-hidden="true">
  <div class="mobile-nav-head">
    <div class="logo"><span class="logo-mark"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="#000" stroke-width="2.5" stroke-linecap="round"><circle cx="12" cy="12" r="10"/><path d="M12 2v20M2 12h20"/></svg></span>GOAL<span style="color:var(--accent)">SPHERE</span></div>
    <button class="icon-btn" onclick="toggleMobileNav()"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M18 6 6 18"/><path d="m6 6 12 12"/></svg></button>
  </div>
  <nav class="mobile-nav-links">
    <a href="#/" onclick="toggleMobileNav()">Home →</a>
    <a href="#/live" onclick="toggleMobileNav()">Live Scores →</a>
    <a href="#/matches" onclick="toggleMobileNav()">Matches →</a>
    <a href="#/news" onclick="toggleMobileNav()">News →</a>
    <a href="#/transfers" onclick="toggleMobileNav()">Transfers →</a>
    <a href="#/leagues" onclick="toggleMobileNav()">Leagues →</a>
    <a href="#/teams" onclick="toggleMobileNav()">Teams →</a>
    <a href="#/players" onclick="toggleMobileNav()">Players →</a>
    <a href="#/standings" onclick="toggleMobileNav()">Standings →</a>
    <a href="#/history" onclick="toggleMobileNav()">History →</a>
    <a href="#/intel" onclick="toggleMobileNav()">Intel →</a>
  </nav>
</div>

<div class="search-modal" id="searchModal" role="dialog" aria-modal="true">
  <div class="search-box">
    <div class="search-input-wrap">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
      <input class="search-input" id="searchInput" type="text" placeholder="Search teams, players, leagues..." autocomplete="off">
      <span class="search-kbd">ESC</span>
    </div>
    <div class="search-results" id="searchResults"></div>
  </div>
</div>

<main id="main"></main>

<footer class="footer">
  <div class="container">
    <div class="footer-grid">
      <div class="footer-brand">
        <div class="logo"><span class="logo-mark"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="#000" stroke-width="2.5" stroke-linecap="round"><circle cx="12" cy="12" r="10"/><path d="M12 2v20M2 12h20"/></svg></span>GOAL<span style="color:var(--accent)">SPHERE</span></div>
        <p>The World of Football, In One Place. Premium global football coverage, live scores, tactical intelligence, and editorial storytelling.</p>
        <div class="footer-social">
          <a href="#" aria-label="X"><svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg></a>
          <a href="#" aria-label="Instagram"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="2" width="20" height="20" rx="5"/><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"/><line x1="17.5" x2="17.51" y1="6.5" y2="6.5"/></svg></a>
          <a href="#" aria-label="YouTube"><svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"/></svg></a>
        </div>
      </div>
      <div class="footer-col">
        <h4>Football</h4>
        <ul><li><a href="#/matches">Matches</a></li><li><a href="#/live">Live Scores</a></li><li><a href="#/standings">Standings</a></li><li><a href="#/leagues">Leagues</a></li><li><a href="#/teams">Teams</a></li><li><a href="#/players">Players</a></li></ul>
      </div>
      <div class="footer-col">
        <h4>Editorial</h4>
        <ul><li><a href="#/news">Latest News</a></li><li><a href="#/news/breaking">Breaking</a></li><li><a href="#/transfers">Transfers</a></li><li><a href="#/news/tactics">Tactics</a></li><li><a href="#/history">History</a></li><li><a href="#/intel">Intel</a></li></ul>
      </div>
      <div class="footer-col">
        <h4>Company</h4>
        <ul><li><a href="#">About</a></li><li><a href="#">Editorial Policy</a></li><li><a href="#">Contact</a></li><li><a href="#">Privacy</a></li><li><a href="#">Terms</a></li></ul>
      </div>
      <div class="footer-col">
        <h4>Newsletter</h4>
        <p style="font-size:12px;color:var(--text-muted);margin-bottom:10px;line-height:1.5">Daily football intelligence delivered to your inbox.</p>
        <form class="nl-form" onsubmit="event.preventDefault();this.querySelector('input').value='';alert('Subscribed (demo)')">
          <input type="email" placeholder="your@email.com" required>
          <button class="btn btn-primary" type="submit">Subscribe</button>
        </form>
      </div>
    </div>
    <div class="footer-bottom">
      <div>© 2026 GOALSPHERE. All rights reserved. Demonstration data.</div>
      <div>Made for the global football community.</div>
    </div>
  </div>
</footer>

<div class="demo-badge">Demo Data</div>

<script>
const MOCK_TEAMS=[
{id:'t1',name:'Manchester City',shortName:'MCI',country:'England',leagueId:'l1',stadium:'Etihad Stadium',coach:'Pep Guardiola',form:['W','W','D','W','W']},
{id:'t2',name:'Arsenal',shortName:'ARS',country:'England',leagueId:'l1',stadium:'Emirates Stadium',coach:'Mikel Arteta',form:['W','W','W','D','W']},
{id:'t3',name:'Liverpool',shortName:'LIV',country:'England',leagueId:'l1',stadium:'Anfield',coach:'Arne Slot',form:['W','D','W','W','L']},
{id:'t4',name:'Chelsea',shortName:'CHE',country:'England',leagueId:'l1',stadium:'Stamford Bridge',coach:'Enzo Maresca',form:['D','W','L','W','D']},
{id:'t5',name:'Manchester United',shortName:'MUN',country:'England',leagueId:'l1',stadium:'Old Trafford',coach:'Ruben Amorim',form:['L','D','W','L','W']},
{id:'t6',name:'Tottenham Hotspur',shortName:'TOT',country:'England',leagueId:'l1',stadium:'Tottenham Hotspur Stadium',coach:'Ange Postecoglou',form:['W','L','D','W','L']},
{id:'t7',name:'Newcastle United',shortName:'NEW',country:'England',leagueId:'l1',stadium:"St James' Park",coach:'Eddie Howe',form:['W','W','D','L','W']},
{id:'t8',name:'Aston Villa',shortName:'AVL',country:'England',leagueId:'l1',stadium:'Villa Park',coach:'Unai Emery',form:['D','W','W','L','W']},
{id:'t9',name:'Real Madrid',shortName:'RMA',country:'Spain',leagueId:'l2',stadium:'Santiago Bernabéu',coach:'Carlo Ancelotti',form:['W','W','W','D','W']},
{id:'t10',name:'Barcelona',shortName:'BAR',country:'Spain',leagueId:'l2',stadium:'Spotify Camp Nou',coach:'Hansi Flick',form:['W','W','W','W','D']},
{id:'t11',name:'Atlético Madrid',shortName:'ATM',country:'Spain',leagueId:'l2',stadium:'Cívitas Metropolitano',coach:'Diego Simeone',form:['W','D','W','W','L']},
{id:'t12',name:'Bayern Munich',shortName:'BAY',country:'Germany',leagueId:'l3',stadium:'Allianz Arena',coach:'Vincent Kompany',form:['W','W','D','W','W']},
{id:'t13',name:'Borussia Dortmund',shortName:'BVB',country:'Germany',leagueId:'l3',stadium:'Signal Iduna Park',coach:'Nuri Şahin',form:['W','L','W','D','W']},
{id:'t14',name:'Paris Saint-Germain',shortName:'PSG',country:'France',leagueId:'l4',stadium:'Parc des Princes',coach:'Luis Enrique',form:['W','W','W','D','W']},
{id:'t15',name:'Inter Milan',shortName:'INT',country:'Italy',leagueId:'l5',stadium:'San Siro',coach:'Simone Inzaghi',form:['W','W','D','W','W']},
{id:'t16',name:'AC Milan',shortName:'ACM',country:'Italy',leagueId:'l5',stadium:'San Siro',coach:'Paulo Fonseca',form:['D','W','L','W','D']},
{id:'t17',name:'Juventus',shortName:'JUV',country:'Italy',leagueId:'l5',stadium:'Allianz Stadium',coach:'Thiago Motta',form:['W','D','W','W','D']},
{id:'t18',name:'LAFC',shortName:'LAF',country:'USA',leagueId:'l6',stadium:'BMO Stadium',coach:'Steve Cherundolo',form:['W','W','D','W','L']}
];
const MOCK_PLAYERS=[
{id:'p1',name:'Erling Haaland',position:'Forward',teamId:'t1',nationality:'Norway',age:25,number:9,stats:{goals:28,assists:6,apps:32}},
{id:'p2',name:'Kylian Mbappé',position:'Forward',teamId:'t9',nationality:'France',age:26,number:9,stats:{goals:32,assists:9,apps:34}},
{id:'p3',name:'Jude Bellingham',position:'Midfielder',teamId:'t9',nationality:'England',age:21,number:5,stats:{goals:14,assists:11,apps:30}},
{id:'p4',name:'Bukayo Saka',position:'Forward',teamId:'t2',nationality:'England',age:23,number:7,stats:{goals:16,assists:13,apps:33}},
{id:'p5',name:'Vinícius Júnior',position:'Forward',teamId:'t9',nationality:'Brazil',age:24,number:7,stats:{goals:21,assists:10,apps:31}},
{id:'p6',name:'Mohamed Salah',position:'Forward',teamId:'t3',nationality:'Egypt',age:32,number:11,stats:{goals:23,assists:12,apps:34}},
{id:'p7',name:'Kevin De Bruyne',position:'Midfielder',teamId:'t1',nationality:'Belgium',age:33,number:17,stats:{goals:7,assists:15,apps:26}},
{id:'p8',name:'Lamine Yamal',position:'Forward',teamId:'t10',nationality:'Spain',age:17,number:19,stats:{goals:12,assists:14,apps:32}},
{id:'p9',name:'Phil Foden',position:'Midfielder',teamId:'t1',nationality:'England',age:24,number:47,stats:{goals:15,assists:9,apps:30}},
{id:'p10',name:'Lautaro Martínez',position:'Forward',teamId:'t15',nationality:'Argentina',age:27,number:10,stats:{goals:25,assists:7,apps:33}},
{id:'p11',name:'Harry Kane',position:'Forward',teamId:'t12',nationality:'England',age:31,number:9,stats:{goals:30,assists:9,apps:32}},
{id:'p12',name:'Rodri',position:'Midfielder',teamId:'t1',nationality:'Spain',age:27,number:16,stats:{goals:8,assists:10,apps:28}},
{id:'p13',name:'Florian Wirtz',position:'Midfielder',teamId:'t13',nationality:'Germany',age:21,number:10,stats:{goals:13,assists:14,apps:29}},
{id:'p14',name:'Cole Palmer',position:'Midfielder',teamId:'t4',nationality:'England',age:22,number:20,stats:{goals:18,assists:11,apps:31}},
{id:'p15',name:'Ousmane Dembélé',position:'Forward',teamId:'t14',nationality:'France',age:27,number:10,stats:{goals:17,assists:12,apps:30}}
];
const MOCK_LEAGUES=[
{id:'l1',name:'Premier League',country:'England',season:'2025/26',teams:20},
{id:'l2',name:'La Liga',country:'Spain',season:'2025/26',teams:20},
{id:'l3',name:'Bundesliga',country:'Germany',season:'2025/26',teams:18},
{id:'l4',name:'Ligue 1',country:'France',season:'2025/26',teams:18},
{id:'l5',name:'Serie A',country:'Italy',season:'2025/26',teams:20},
{id:'l6',name:'MLS',country:'USA',season:'2026',teams:29},
{id:'l7',name:'UEFA Champions League',country:'Europe',season:'2025/26',teams:36},
{id:'l8',name:'UEFA Europa League',country:'Europe',season:'2025/26',teams:48}
];
const MOCK_FIXTURES=[
{id:'f1',leagueId:'l1',homeTeamId:'t1',awayTeamId:'t2',homeScore:2,awayScore:1,status:'FT',minute:'90',date:'2026-09-14',venue:'Etihad Stadium',round:'Matchweek 5'},
{id:'f2',leagueId:'l1',homeTeamId:'t3',awayTeamId:'t5',homeScore:3,awayScore:0,status:'LIVE',minute:'67',date:'2026-09-16',venue:'Anfield',round:'Matchweek 5'},
{id:'f3',leagueId:'l2',homeTeamId:'t9',awayTeamId:'t10',homeScore:1,awayScore:1,status:'HT',minute:'HT',date:'2026-09-16',venue:'Santiago Bernabéu',round:'Jornada 6'},
{id:'f4',leagueId:'l3',homeTeamId:'t12',awayTeamId:'t13',homeScore:null,awayScore:null,status:'UPCOMING',minute:'',date:'2026-09-17',venue:'Allianz Arena',round:'Matchday 4'},
{id:'f5',leagueId:'l5',homeTeamId:'t15',awayTeamId:'t16',homeScore:2,awayScore:2,status:'FT',minute:'90',date:'2026-09-15',venue:'San Siro',round:'Matchday 5'},
{id:'f6',leagueId:'l4',homeTeamId:'t14',awayTeamId:'t9',homeScore:null,awayScore:null,status:'UPCOMING',minute:'',date:'2026-09-18',venue:'Parc des Princes',round:'Matchday 6'},
{id:'f7',leagueId:'l1',homeTeamId:'t6',awayTeamId:'t4',homeScore:1,awayScore:2,status:'FT',minute:'90',date:'2026-09-14',venue:'Tottenham Hotspur Stadium',round:'Matchweek 5'},
{id:'f8',leagueId:'l1',homeTeamId:'t7',awayTeamId:'t8',homeScore:null,awayScore:null,status:'UPCOMING',minute:'',date:'2026-09-17',venue:"St James' Park",round:'Matchweek 5'},
{id:'f9',leagueId:'l7',homeTeamId:'t1',awayTeamId:'t15',homeScore:null,awayScore:null,status:'UPCOMING',minute:'',date:'2026-09-19',venue:'Etihad Stadium',round:'League Phase'},
{id:'f10',leagueId:'l2',homeTeamId:'t11',awayTeamId:'t9',homeScore:0,awayScore:2,status:'FT',minute:'90',date:'2026-09-13',venue:'Cívitas Metropolitano',round:'Jornada 6'}
];
const MOCK_ARTICLES=[
{id:'a1',slug:'man-city-arsenal-tactical-masterclass',title:"Guardiola's Gambit: How Manchester City Dismantled Arsenal's Low Block",subtitle:'A tactical breakdown of the Etihad showdown that reshaped the Premier League title race.',category:'Tactics',author:'Marcus Reid',publishedAt:'2026-09-15T19:30:00Z',readTime:'8 min read',summary:"An in-depth analysis of the tactical decisions that defined Manchester City's 2-1 victory over Arsenal at the Etihad.",body:'<h2>The Setup</h2><p>When the teamsheets landed at 14:00 GMT, one thing was immediately clear: Pep Guardiola had prepared something specific for this Arsenal side. The traditional 4-3-3 was gone, replaced by an asymmetrical 3-2-4-1 that asked questions Mikel Arteta\'s structure wasn\'t ready to answer.</p><blockquote>"We studied their build-up for three weeks. Every pattern, every trigger. Tonight was about execution."</blockquote><h2>First Half: Control Through Chaos</h2><p>City\'s opening twenty-five minutes were a masterclass in controlled possession. Rodri dropped between the center-backs, inviting Arsenal\'s press, before releasing Phil Foden into the half-spaces.</p><h3>The Opening Goal</h3><p>The breakthrough came on 28 minutes. Bernardo Silva\'s dummy sent two Arsenal players the wrong way, and Foden found himself in yards of space. His cutback to Haaland was clinically finished.</p><div class="stat-inline"><h4>Key Stat</h4><div class="big">87%</div><p>City\'s pass completion in the final third during the first half — the highest recorded at the Etihad this season.</p></div><h2>Second Half: The Response</h2><p>Arteta\'s halftime adjustments were immediate. Martin Ødegaard pushed higher, and Bukayo Saka was instructed to isolate City\'s left-back. The equalizer came on 58 minutes.</p><p>But City had a second gear. On 74 minutes, a De Bruyne free-kick found Haaland at the back post. The Norwegian didn\'t even have to jump.</p>'},
{id:'a2',slug:'mbappe-real-madrid-season-analysis',title:'Mbappé at Real Madrid: The Evolution of a Galáctico',subtitle:'How the French superstar has adapted to life in white — and why his numbers tell only half the story.',category:'Players',author:'Sofia Martín',publishedAt:'2026-09-14T11:00:00Z',readTime:'6 min read',summary:'Kylian Mbappé\'s second season at Real Madrid has revealed a more complete footballer.',body:'<h2>Beyond the Goals</h2><p>Kylian Mbappé has scored 32 goals across all competitions this season. The numbers are spectacular, but they only scratch the surface of what has become one of the most fascinating tactical evolutions in modern football.</p><p>Under Carlo Ancelotti, the French forward has been asked to do things he rarely did at Paris Saint-Germain: press from the front, track back on transitions, and occupy spaces that serve the team rather than his own highlight reel.</p><h2>The Partnership with Bellingham</h2><p>The Mbappé-Bellingham axis has become the most potent attacking duo in European football. Their understanding is telepathic.</p><blockquote>"Playing with Kylian is like having a cheat code. You know the ball will find you in the right space." — Jude Bellingham</blockquote>'},
{id:'a3',slug:'champions-league-preview-2026',title:'Champions League 2025/26: The Teams Poised to Go Deep',subtitle:'From Manchester City\'s experience to Barcelona\'s youth revolution — our preview of the competition\'s main protagonists.',category:'Leagues',author:'James O\'Connor',publishedAt:'2026-09-13T08:00:00Z',readTime:'12 min read',summary:'The new-look Champions League league phase is underway. Here are the teams most likely to lift the trophy in Munich.',body:'<h2>The Favorites</h2><p>Manchester City enter as the bookmakers\' favorites, and for good reason. Pep Guardiola\'s side has the depth, the experience, and — crucially — a fully fit squad for the first time in three seasons.</p><p>Real Madrid sit alongside them. The addition of Mbappé has given Carlo Ancelotti\'s side an extra dimension.</p><h2>The Dark Horses</h2><p>Barcelona, under Hansi Flick, have become something of a revelation. Lamine Yamal at 17 is playing with the composure of a veteran.</p>'},
{id:'a4',slug:'yamal-barcelona-breakout',title:'Lamine Yamal at 17: Football\'s New Prodigy Is Already Here',subtitle:'The Barcelona teenager is redefining what\'s possible at his age — and he\'s only getting started.',category:'Players',author:'Carlos Vega',publishedAt:'2026-09-12T15:00:00Z',readTime:'5 min read',summary:'Lamine Yamal has become the most exciting teenager in world football.',body:'<h2>A Generation Ahead</h2><p>At 17 years and 62 days, Lamine Yamal has already achieved more than most players manage in a full career. A European Championship winner with Spain, a La Liga title, and now the undisputed star of Hansi Flick\'s Barcelona.</p>'},
{id:'a5',slug:'transfer-window-recap',title:'Summer 2026 Transfer Window: The Deals That Defined the Market',subtitle:'Record-breaking fees, surprise moves, and the tactical implications of football\'s biggest summer.',category:'Transfers',author:'Emma Thompson',publishedAt:'2026-09-10T09:00:00Z',readTime:'10 min read',summary:'A comprehensive review of the summer transfer window that reshaped European football.',body:'<h2>Record Spending</h2><p>The summer 2026 transfer window saw a record £7.2 billion spent across Europe\'s top five leagues. Premier League clubs accounted for nearly half of that total.</p><h3>The Biggest Moves</h3><ul><li><strong>Florian Wirtz to Manchester City</strong> — £115m (rumoured)</li><li><strong>Alexander Isak to Liverpool</strong> — £95m</li><li><strong>João Neves to PSG</strong> — £85m</li></ul>'},
{id:'a6',slug:'premier-league-title-race',title:'Premier League Title Race: Why 2025/26 Could Be the Tightest Yet',subtitle:'Five teams within four points. The data suggests this could go down to the final day.',category:'Leagues',author:'Marcus Reid',publishedAt:'2026-09-11T14:00:00Z',readTime:'7 min read',summary:'The Premier League title race is wide open — and the data suggests it could go to the final weekend.',body:'<h2>The Contenders</h2><p>After five matchweeks, the top five are separated by just four points. Manchester City lead, but Arsenal, Liverpool, Chelsea, and Newcastle are all within touching distance.</p>'},
{id:'a7',slug:'tactical-trend-high-press',title:'The Death of the High Press? Why Possession Is Making a Comeback',subtitle:'After years of gegenpressing dominance, the tactical pendulum is swinging back.',category:'Tactics',author:'Dr. Elena Rossi',publishedAt:'2026-09-09T10:00:00Z',readTime:'9 min read',summary:'The tactical trends shaping the 2025/26 season.',body:'<h2>A Shift in Philosophy</h2><p>For the better part of a decade, the high press was the dominant tactical philosophy in elite European football. But something interesting is happening in 2025/26.</p>'},
{id:'a8',slug:'mls-expansion-story',title:'MLS in 2026: The League That\'s Finally Coming of Age',subtitle:'With the World Cup on home soil and Messi still drawing crowds, American soccer has reached an inflection point.',category:'Leagues',author:'David Chen',publishedAt:'2026-09-08T12:00:00Z',readTime:'6 min read',summary:'Major League Soccer is entering a new era.',body:'<h2>The Messi Effect, Two Years On</h2><p>When Lionel Messi arrived at Inter Miami in 2023, skeptics questioned whether his presence would transform MLS or simply provide a temporary boost. Two years later, the answer is clear: both.</p>'}
];
const MOCK_TRANSFERS=[
{id:'tr1',playerId:'p13',playerName:'Florian Wirtz',fromTeamId:'t13',toTeamId:'t1',fee:'£115m',date:'2026-08-28',status:'RUMOUR'},
{id:'tr2',playerName:'Alexander Isak',fromTeamId:'t7',toTeamId:'t3',fee:'£95m',date:'2026-08-25',status:'CONFIRMED'},
{id:'tr3',playerName:'João Neves',fromTeamId:'t14',toTeamId:'t14',fee:'£85m',date:'2026-08-22',status:'CONFIRMED'},
{id:'tr4',playerName:'Viktor Gyökeres',fromTeamId:'t17',toTeamId:'t2',fee:'£65m',date:'2026-08-20',status:'CONFIRMED'},
{id:'tr5',playerName:'Niclas Füllkrug',fromTeamId:'t12',toTeamId:'t16',fee:'£45m',date:'2026-08-18',status:'CONFIRMED'},
{id:'tr6',playerName:'Joshua Kimmich',fromTeamId:'t12',toTeamId:'t9',fee:'£60m',date:'2026-08-15',status:'RUMOUR'},
{id:'tr7',playerName:'Benjamin Šeško',fromTeamId:'t13',toTeamId:'t4',fee:'£70m',date:'2026-08-12',status:'CONFIRMED'},
{id:'tr8',playerName:'Xavi Simons',fromTeamId:'t13',toTeamId:'t10',fee:'£80m',date:'2026-08-10',status:'RUMOUR'}
];
const MOCK_STANDINGS=[
{pos:1,teamId:'t1',mp:5,w:4,d:1,l:0,gf:14,ga:4,gd:10,pts:13,form:['W','W','D','W','W'],zone:'ucl'},
{pos:2,teamId:'t2',mp:5,w:4,d:0,l:1,gf:12,ga:5,gd:7,pts:12,form:['W','W','W','D','W'],zone:'ucl'},
{pos:3,teamId:'t3',mp:5,w:3,d:2,l:0,gf:11,ga:4,gd:7,pts:11,form:['W','D','W','W','L'],zone:'ucl'},
{pos:4,teamId:'t7',mp:5,w:3,d:1,l:1,gf:9,ga:5,gd:4,pts:10,form:['W','W','D','L','W'],zone:'ucl'},
{pos:5,teamId:'t8',mp:5,w:3,d:1,l:1,gf:8,ga:6,gd:2,pts:10,form:['D','W','W','L','W'],zone:'uel'},
{pos:6,teamId:'t4',mp:5,w:2,d:2,l:1,gf:7,ga:6,gd:1,pts:8,form:['D','W','L','W','D'],zone:'uel'},
{pos:7,teamId:'t6',mp:5,w:2,d:1,l:2,gf:8,ga:8,gd:0,pts:7,form:['W','L','D','W','L']},
{pos:8,teamId:'t5',mp:5,w:2,d:1,l:2,gf:6,ga:7,gd:-1,pts:7,form:['L','D','W','L','W']},
{pos:9,teamId:'t17',mp:5,w:1,d:3,l:1,gf:5,ga:5,gd:0,pts:6,form:['W','D','W','W','D']},
{pos:10,teamId:'t16',mp:5,w:1,d:2,l:2,gf:4,ga:6,gd:-2,pts:5,form:['D','W','L','W','D']}
];
const MOCK_MATCH_EVENTS=[
{minute:12,type:'goal',teamId:'t1',player:'Erling Haaland',assist:'Kevin De Bruyne',scoreAfter:'1-0'},
{minute:28,type:'yellow',teamId:'t2',player:'Declan Rice',scoreAfter:'1-0'},
{minute:41,type:'goal',teamId:'t1',player:'Phil Foden',assist:'Erling Haaland',scoreAfter:'2-0'},
{minute:58,type:'goal',teamId:'t2',player:'Bukayo Saka',assist:'Martin Ødegaard',scoreAfter:'2-1'},
{minute:67,type:'yellow',teamId:'t1',player:'Rodri',scoreAfter:'2-1'},
{minute:74,type:'substitution',teamId:'t2',playerIn:'Leandro Trossard',playerOut:'Gabriel Jesus',scoreAfter:'2-1'},
{minute:82,type:'substitution',teamId:'t1',playerIn:'Mateo Kovačić',playerOut:'Kevin De Bruyne',scoreAfter:'2-1'},
{minute:88,type:'yellow',teamId:'t2',player:'William Saliba',scoreAfter:'2-1'}
];

class MockFootballRepository{
  getTeams(){return Promise.resolve(MOCK_TEAMS)}
  getTeam(id){return Promise.resolve(MOCK_TEAMS.find(t=>t.id===id))}
  getPlayers(){return Promise.resolve(MOCK_PLAYERS)}
  getPlayer(id){return Promise.resolve(MOCK_PLAYERS.find(p=>p.id===id))}
  getLeagues(){return Promise.resolve(MOCK_LEAGUES)}
  getLeague(id){return Promise.resolve(MOCK_LEAGUES.find(l=>l.id===id))}
  getFixtures(){return Promise.resolve(MOCK_FIXTURES)}
  getFixture(id){return Promise.resolve(MOCK_FIXTURES.find(f=>f.id===id))}
  getLiveFixtures(){return Promise.resolve(MOCK_FIXTURES.filter(f=>['LIVE','HT'].includes(f.status)))}
  getArticles(){return Promise.resolve(MOCK_ARTICLES)}
  getArticle(slug){return Promise.resolve(MOCK_ARTICLES.find(a=>a.slug===slug))}
  getTransfers(){return Promise.resolve(MOCK_TRANSFERS)}
  getStandings(leagueId='l1'){return Promise.resolve(MOCK_STANDINGS)}
  getMatchEvents(fixtureId){return Promise.resolve(MOCK_MATCH_EVENTS)}
  getPlayersByTeam(teamId){return Promise.resolve(MOCK_PLAYERS.filter(p=>p.teamId===teamId))}
  getFixturesByTeam(teamId){return Promise.resolve(MOCK_FIXTURES.filter(f=>f.homeTeamId===teamId||f.awayTeamId===teamId))}
  getFixturesByLeague(leagueId){return Promise.resolve(MOCK_FIXTURES.filter(f=>f.leagueId===leagueId))}
  search(query){
    const q=query.toLowerCase();
    return Promise.resolve({
      teams:MOCK_TEAMS.filter(t=>t.name.toLowerCase().includes(q)),
      players:MOCK_PLAYERS.filter(p=>p.name.toLowerCase().includes(q)),
      leagues:MOCK_LEAGUES.filter(l=>l.name.toLowerCase().includes(q)),
      articles:MOCK_ARTICLES.filter(a=>a.title.toLowerCase().includes(q))
    });
  }
}
const repo=new MockFootballRepository();

const $=(sel,el=document)=>el.querySelector(sel);
const $$=(sel,el=document)=>Array.from(el.querySelectorAll(sel));
const teamById=id=>MOCK_TEAMS.find(t=>t.id===id);
const leagueById=id=>MOCK_LEAGUES.find(l=>l.id===id);
const playerById=id=>MOCK_PLAYERS.find(p=>p.id===id);

function crest(team,size=28){
  if(!team)return`<div class="crest" style="width:${size}px;height:${size}px">?</div>`;
  const i=team.shortName||team.name.substring(0,3).toUpperCase();
  return`<div class="crest" style="width:${size}px;height:${size}px;font-size:${Math.max(8,size/3)}px" aria-label="${team.name}">${i}</div>`;
}
function formatDate(d){return new Date(d).toLocaleDateString('en-GB',{day:'numeric',month:'short',year:'numeric'})}
function formatTime(d){return new Date(d).toLocaleTimeString('en-GB',{hour:'2-digit',minute:'2-digit'})}
function relativeTime(d){
  const diff=Date.now()-new Date(d).getTime(),mins=Math.floor(diff/60000);
  if(mins<60)return`${mins}m ago`;const hrs=Math.floor(mins/60);
  if(hrs<24)return`${hrs}h ago`;return`${Math.floor(hrs/24)}d ago`;
}
function statusBadge(status,minute=''){
  if(status==='LIVE')return`<span class="badge badge-live">LIVE ${minute}'</span>`;
  if(status==='HT')return`<span class="badge badge-live">HT</span>`;
  if(status==='FT')return`<span class="badge">FT</span>`;
  return`<span class="badge badge-accent">UPCOMING</span>`;
}
function formDots(form){return form.map(f=>`<span class="form-dot form-${f}">${f}</span>`).join('')}

const routes={};
function route(path,handler){routes[path]=handler}
function navigate(path){window.location.hash=path}
function getRoute(){return window.location.hash.replace('#','')||'/'}

async function renderRoute(){
  const path=getRoute(),main=$('#main');
  main.style.opacity='0';await new Promise(r=>setTimeout(r,100));
  $$('.nav a').forEach(a=>{const r=a.dataset.route;if(path===r||(r!=='/'&&path.startsWith(r)))a.classList.add('active');else a.classList.remove('active')});
  let handler=routes[path];
  if(!handler){for(const pattern in routes){if(pattern.includes(':')){const regex=new RegExp('^'+pattern.replace(/:[^/]+/g,'([^/]+)')+'$');const match=path.match(regex);if(match){handler=routes[pattern];window.__routeParams=match.slice(1);break}}}}
  if(handler){window.scrollTo(0,0);await handler(main)}
  else{main.innerHTML=`<div class="page-header"><div class="container"><h1>Page Not Found</h1><p>The page you're looking for doesn't exist.</p><a href="#/" class="btn btn-primary mt-3">Go Home</a></div></div>`}
  main.style.opacity='1';main.style.transition='opacity .15s ease';updateSEO(path);
}
window.addEventListener('hashchange',renderRoute);
window.addEventListener('load',renderRoute);

function updateSEO(path){
  const titles={'/':'GOALSPHERE — The World of Football, In One Place','/live':'Live Football Scores | GOALSPHERE','/matches':'Football Fixtures & Results | GOALSPHERE','/news':'Football News | GOALSPHERE','/transfers':'Football Transfer News | GOALSPHERE','/leagues':'Football Leagues & Competitions | GOALSPHERE','/teams':'Football Teams Directory | GOALSPHERE','/players':'Football Players Directory | GOALSPHERE','/standings':'Football Standings & Tables | GOALSPHERE','/history':'Football History | GOALSPHERE','/intel':'AI Football Intelligence | GOALSPHERE'};
  const descs={'/':'Premium global football platform. Live scores, match analysis, transfer news, tactical intelligence.','/live':'Follow live football scores from the Premier League, La Liga, Champions League, and more.','/matches':'Football fixtures, results, and match previews from leagues around the world.','/news':'Latest football news, tactical analysis, and editorial coverage.','/transfers':'Confirmed transfers, rumours, and market analysis.','/leagues':'Premier League, La Liga, Bundesliga, Serie A, Ligue 1, Champions League.','/teams':'Football teams directory with squads, stats, and fixtures.','/players':'Football players directory with profiles, statistics, and career data.','/standings':'Live league standings and tables from around the world.','/history':'Historical football data, records, and legendary matches.','/intel':'AI-powered football analysis, tactical breakdowns, and predictions.'};
  document.title=titles[path]||'GOALSPHERE';
  let metaDesc=document.querySelector('meta[name="description"]');if(metaDesc)metaDesc.setAttribute('content',descs[path]||'Premium global football platform.');
  let canonical=document.querySelector('link[rel="canonical"]');if(canonical)canonical.setAttribute('href','https://goalsphere.com'+(path==='/'?'':path));
}

function sectionHeader(eyebrow,title,action=''){return`<div class="section-head"><div><div class="section-eyebrow">${eyebrow}</div><h2 class="section-title">${title}</h2></div>${action}</div>`}

function scoreCard(fixture){
  const home=teamById(fixture.homeTeamId),away=teamById(fixture.awayTeamId),league=leagueById(fixture.leagueId);
  const hw=fixture.homeScore>fixture.awayScore,aw=fixture.awayScore>fixture.homeScore;
  return`<div class="score-card ${fixture.status==='LIVE'?'live':''}" onclick="location.hash='/matches/${fixture.id}'">
    <div class="score-card-head"><span>${league?.name||'Competition'}</span>${statusBadge(fixture.status,fixture.minute)}</div>
    <div class="score-card-teams">
      <div class="score-card-team ${hw?'winner':aw?'loser':''}">${crest(home,22)}<span>${home?.shortName||'Home'}</span><span class="score">${fixture.homeScore??'-'}</span></div>
      <div class="score-card-team ${aw?'winner':hw?'loser':''}">${crest(away,22)}<span>${away?.shortName||'Away'}</span><span class="score">${fixture.awayScore??'-'}</span></div>
    </div>
    <div class="score-card-foot"><span>${fixture.status==='UPCOMING'?formatTime(fixture.date):fixture.minute?fixture.minute+"'":''}</span><span>${fixture.venue?.split(' ')[0]||''}</span></div>
  </div>`;
}

function matchCard(fixture){
  const home=teamById(fixture.homeTeamId),away=teamById(fixture.awayTeamId),league=leagueById(fixture.leagueId);
  const hw=fixture.homeScore>fixture.awayScore,aw=fixture.awayScore>fixture.homeScore;
  return`<article class="match-card" onclick="location.hash='/matches/${fixture.id}'">
    <div class="match-card-head"><span>${league?.name||''}</span>${statusBadge(fixture.status,fixture.minute)}</div>
    <div class="match-card-teams">
      <div class="match-card-team ${hw?'winner':aw?'loser':''}">${crest(home,24)}<span>${home?.name||'Home'}</span><span class="score">${fixture.homeScore??'-'}</span></div>
      <div class="match-card-team ${aw?'winner':hw?'loser':''}">${crest(away,24)}<span>${away?.name||'Away'}</span><span class="score">${fixture.awayScore??'-'}</span></div>
    </div>
    <div class="match-card-foot"><span>${formatDate(fixture.date)}</span><span>${fixture.venue||''}</span></div>
  </article>`;
}

function newsItem(article){
  return`<article class="news-item" onclick="location.hash='/news/${article.slug}'">
    <div class="news-item-img"></div>
    <div class="news-item-body">
      <span class="news-item-cat">${article.category}</span>
      <h3 class="news-item-title">${article.title}</h3>
      <div class="news-item-meta">${relativeTime(article.publishedAt)} · ${article.readTime}</div>
    </div>
  </article>`;
}

function teamCard(team){
  return`<article class="team-card" onclick="location.hash='/teams/${team.id}'">
    <div class="tc-head">${crest(team,44)}<div><h3>${team.name}</h3><p>${team.country} · ${leagueById(team.leagueId)?.name||''}</p></div></div>
    <div class="small mb-2">${team.stadium}</div>
    <div class="form-row">${formDots(team.form)}</div>
  </article>`;
}

function playerCard(player){
  const team=teamById(player.teamId);
  return`<article class="player-card" onclick="location.hash='/players/${player.id}'">
    <span class="pc-num">#${player.number}</span>
    <div class="pc-photo">${player.name.charAt(0)}</div>
    <h3>${player.name}</h3>
    <div class="pc-pos">${player.position}</div>
    <div class="pc-club">${team?.name||''} · ${player.nationality}</div>
  </article>`;
}

function leagueCard(league){
  const short=league.name.split(' ').map(w=>w[0]).join('').substring(0,3).toUpperCase();
  return`<article class="league-card" onclick="location.hash='/leagues/${league.id}'">
    <div class="lc-logo">${short}</div>
    <h3>${league.name}</h3>
    <p>${league.country}</p>
    <div class="lc-meta"><span>${league.season}</span><span>·</span><span>${league.teams} teams</span></div>
  </article>`;
}

function transferCard(t){
  const from=teamById(t.fromTeamId),to=teamById(t.toTeamId);
  const initials=t.playerName.split(' ').map(n=>n[0]).join('').substring(0,2);
  return`<article class="transfer-card">
    <div class="tc-head">
      <div class="tc-player">
        <div class="tc-avatar">${initials}</div>
        <div class="tc-info"><h4>${t.playerName}</h4><p>${playerById(t.playerId)?.position||'Player'} · ${playerById(t.playerId)?.age||''} ${playerById(t.playerId)?.nationality?'· '+playerById(t.playerId).nationality:''}</p></div>
      </div>
      <span class="badge ${t.status==='CONFIRMED'?'badge-accent':'badge-yellow'}">${t.status}</span>
    </div>
    <div class="tc-clubs">
      ${from?`<div class="tc-club">${crest(from,24)}<span>${from.shortName}</span></div>`:''}
      <div class="tc-arrow"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg></div>
      ${to?`<div class="tc-club">${crest(to,24)}<span>${to.shortName}</span></div>`:''}
    </div>
    <div class="tc-fee">${t.fee}</div>
  </article>`;
}

// === PAGES ===

route('/',async(main)=>{
  const[fixtures,articles,teams,players,leagues,transfers,standings]=await Promise.all([repo.getFixtures(),repo.getArticles(),repo.getTeams(),repo.getPlayers(),repo.getLeagues(),repo.getTransfers(),repo.getStandings()]);
  const live=fixtures.filter(f=>['LIVE','HT'].includes(f.status));
  const finished=fixtures.filter(f=>f.status==='FT');
  const upcoming=fixtures.filter(f=>f.status==='UPCOMING');
  const featuredMatch=fixtures.find(f=>f.id==='f1');
  const featuredArticle=articles[0];
  const latestArticles=articles.slice(1,5);
  const fh=teamById(featuredMatch.homeTeamId),fa=teamById(featuredMatch.awayTeamId);
  
  main.innerHTML=`
  <section class="hero" aria-label="Featured story">
    <div class="hero-bg"></div>
    <div class="hero-img"></div>
    <div class="hero-overlay"></div>
    <div class="container hero-content">
      <div class="hero-grid">
        <div>
          <div class="hero-badge"><span class="badge badge-accent">⚡ Featured Analysis</span></div>
          <h1 class="hero-title">The tactical <span class="accent">revolution</span> reshaping Europe's elite.</h1>
          <p class="hero-summary">From Manchester City's asymmetrical build-up to Barcelona's teenage phenoms — the 2025/26 season is redefining what's possible on the pitch. Deep tactical analysis, live intelligence, and editorial storytelling from the world of football.</p>
          <div class="hero-meta">
            <span>By Marcus Reid</span><span class="dot"></span><span>15 min read</span><span class="dot"></span><span>Updated 2 hours ago</span>
          </div>
          <div class="hero-actions">
            <a href="#/news/${featuredArticle.slug}" class="btn btn-primary">Read Analysis <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg></a>
            <a href="#/live" class="btn btn-ghost"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><circle cx="12" cy="12" r="10"/><polygon points="10 8 16 12 10 16 10 8"/></svg> Live Scores</a>
          </div>
        </div>
        <div class="hero-panel">
          <div class="hero-panel-label">Featured Match · Premier League</div>
          <div class="hero-score-row">
            <div>${crest(fh,56)}<div class="hero-team-name">${fh.name}</div></div>
            <div class="hero-score-val">${featuredMatch.homeScore}<span style="color:var(--text-muted);margin:0 4px">:</span>${featuredMatch.awayScore}</div>
            <div>${crest(fa,56)}<div class="hero-team-name">${fa.name}</div></div>
          </div>
          <div class="hero-stats">
            <div class="hero-stat"><div class="hero-stat-val">62%</div><div class="hero-stat-lbl">Possession</div></div>
            <div class="hero-stat"><div class="hero-stat-val">2.4</div><div class="hero-stat-lbl">xG</div></div>
            <div class="hero-stat"><div class="hero-stat-val">14</div><div class="hero-stat-lbl">Shots</div></div>
          </div>
          <div style="display:flex;justify-content:space-between;margin-top:12px;font-size:11px;color:var(--text-muted)">
            <span>Etihad Stadium</span><span>${formatDate(featuredMatch.date)}</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <div class="breaking">
    <div class="breaking-inner">
      <span class="breaking-label">Breaking</span>
      <span class="breaking-text">Haaland scores brace as Manchester City defeat Arsenal 2-1 in Premier League title clash · El Clásico ends 1-1 at the Bernabéu</span>
    </div>
  </div>

  <section class="scores-rail" aria-label="Live scores">
    <div class="scores-rail-head">
      <div class="scores-rail-title"><span style="width:6px;height:6px;border-radius:50%;background:var(--accent);animation:pulse 1.5s infinite"></span> Live & Recent</div>
      <a href="#/live" class="small" style="color:var(--accent)">View all →</a>
    </div>
    <div class="scores-scroll" id="scoresScroll">${[...live,...finished,...upcoming].map(f=>scoreCard(f)).join('')}</div>
  </section>

  <section class="section">
    <div class="container">
      <div class="grid-editorial">
        <div>
          ${sectionHeader("Latest Football News","Editorial",`<a href="#/news" class="small" style="color:var(--accent)">All news →</a>`)}
          <div class="news-grid mb-4">
            <article class="news-featured" onclick="location.hash='/news/${featuredArticle.slug}'">
              <div class="news-featured-bg"></div>
              <div class="news-featured-content">
                <span class="badge badge-accent">${featuredArticle.category}</span>
                <h2 class="news-featured-title">${featuredArticle.title}</h2>
                <p class="news-featured-summary">${featuredArticle.summary}</p>
                <div class="news-item-meta">By ${featuredArticle.author} · ${relativeTime(featuredArticle.publishedAt)}</div>
              </div>
            </article>
            <div class="news-list">${latestArticles.map(newsItem).join('')}</div>
          </div>
          
          ${sectionHeader("Today's Matches","Fixtures",`<a href="#/matches" class="small" style="color:var(--accent)">All matches →</a>`)}
          <div class="filters">
            <button class="filter-chip active">All</button>
            <button class="filter-chip">Premier League</button>
            <button class="filter-chip">La Liga</button>
            <button class="filter-chip">Champions League</button>
          </div>
          <div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:14px">
            ${fixtures.slice(0,6).map(matchCard).join('')}
          </div>
        </div>
        
        <div>
          <div class="card" style="padding:20px;margin-bottom:20px">
            <div class="section-eyebrow" style="margin-bottom:14px">Most Read</div>
            <div style="display:flex;flex-direction:column;gap:12px">
              ${articles.slice(0,5).map((a,i)=>`
                <a href="#/news/${a.slug}" style="display:flex;gap:10px;align-items:flex-start">
                  <span style="font-family:var(--font-mono);font-size:18px;font-weight:700;color:var(--text-muted);width:24px;text-align:right">${i+1}</span>
                  <div>
                    <div style="font-size:13px;font-weight:500;line-height:1.3;margin-bottom:2px">${a.title}</div>
                    <div class="small">${a.category} · ${relativeTime(a.publishedAt)}</div>
                  </div>
                </a>
              `).join('')}
            </div>
          </div>
          
          <div class="card" style="padding:20px;margin-bottom:20px">
            <div class="section-eyebrow" style="margin-bottom:14px">Trending</div>
            <div style="display:flex;flex-direction:column;gap:10px">
              ${['Premier League','Champions League','Erling Haaland','Transfer News','Live Scores'].map(s=>`
                <a href="#" style="font-size:13px;color:var(--text-sec);padding:6px 0;border-bottom:1px solid var(--border)" onclick="event.preventDefault()">${s}</a>
              `).join('')}
            </div>
          </div>
          
          <div class="card" style="padding:20px">
            <div class="section-eyebrow" style="margin-bottom:14px">Quick Facts</div>
            <div style="display:flex;flex-direction:column;gap:10px;font-size:13px">
              <div style="display:flex;justify-content:space-between;padding:6px 0;border-bottom:1px solid var(--border)"><span class="text-muted">Top Scorer</span><span>Haaland (28)</span></div>
              <div style="display:flex;justify-content:space-between;padding:6px 0;border-bottom:1px solid var(--border)"><span class="text-muted">Most Assists</span><span>De Bruyne (15)</span></div>
              <div style="display:flex;justify-content:space-between;padding:6px 0;border-bottom:1px solid var(--border)"><span class="text-muted">Clean Sheets</span><span>Alisson (12)</span></div>
              <div style="display:flex;justify-content:space-between;padding:6px 0"><span class="text-muted">Avg Goals/Game</span><span>2.84</span></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section" style="padding-top:0">
    <div class="container">
      ${sectionHeader("Featured Match","Match of the Round")}
      <div class="featured-match">
        <div class="fm-info">
          <div class="fm-comp">Premier League · Matchweek 5</div>
          <div class="fm-venue">Etihad Stadium · Manchester · ${formatDate(featuredMatch.date)}</div>
        </div>
        <div class="fm-scoreboard">
          <div>${crest(fh,72)}<div class="fm-team-name">${fh.name}</div></div>
          <div class="fm-score">${featuredMatch.homeScore}<span class="sep">:</span>${featuredMatch.awayScore}</div>
          <div>${crest(fa,72)}<div class="fm-team-name">${fa.name}</div></div>
        </div>
        <div class="stat-compare">
          ${[{l:'Possession',h:62,a:38},{l:'Shots',h:14,a:7},{l:'xG',h:2.4,a:0.9},{l:'Corners',h:8,a:3}].map(s=>`
            <div class="stat-row">
              <div class="val home">${s.h}</div>
              <div style="display:flex;flex-direction:column;gap:4px;flex:1">
                <div class="label">${s.l}</div>
                <div class="stat-bar-wrap">
                  <div class="stat-bar home"><div class="stat-bar-fill" style="width:${s.h/(s.h+s.a)*100}%"></div></div>
                  <div class="stat-bar away"><div class="stat-bar-fill" style="width:${s.a/(s.h+s.a)*100}%"></div></div>
                </div>
              </div>
              <div class="val away">${s.a}</div>
            </div>
          `).join('')}
        </div>
        <div style="text-align:center;margin-top:20px"><a href="#/matches/${featuredMatch.id}" class="btn btn-primary">Enter Match Center →</a></div>
      </div>
    </div>
  </section>

  <section class="section" style="padding-top:0">
    <div class="container">
      ${sectionHeader("Transfer Center","Market Intelligence",`<a href="#/transfers" class="small" style="color:var(--accent)">All transfers →</a>`)}
      <div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:14px">
        ${transfers.slice(0,4).map(transferCard).join('')}
      </div>
    </div>
  </section>

  <section class="section" style="padding-top:0">
    <div class="container">
      ${sectionHeader("Popular Leagues","Competitions",`<a href="#/leagues" class="small" style="color:var(--accent)">All leagues →</a>`)}
      <div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:14px">
        ${leagues.map(leagueCard).join('')}
      </div>
    </div>
  </section>

  <section class="section" style="padding-top:0">
    <div class="container">
      <div class="grid" style="grid-template-columns:1fr 1fr;gap:40px">
        <div>
          ${sectionHeader("Trending Teams","Clubs",`<a href="#/teams" class="small" style="color:var(--accent)">All teams →</a>`)}
          <div style="display:flex;flex-direction:column;gap:10px">
            ${teams.slice(0,5).map(t=>`
              <a href="#/teams/${t.id}" style="display:flex;align-items:center;gap:12px;padding:12px;background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);transition:all .2s" onmouseover="this.style.borderColor='var(--border-light)'" onmouseout="this.style.borderColor='var(--border)'">
                ${crest(t,36)}
                <div style="flex:1;min-width:0"><div style="font-weight:600;font-size:14px">${t.name}</div><div class="small">${t.country} · ${leagueById(t.leagueId)?.name||''}</div></div>
                <div class="form-row" style="margin:0">${formDots(t.form.slice(-3))}</div>
              </a>
            `).join('')}
          </div>
        </div>
        <div>
          ${sectionHeader("Trending Players","Stars",`<a href="#/players" class="small" style="color:var(--accent)">All players →</a>`)}
          <div style="display:flex;flex-direction:column;gap:10px">
            ${players.slice(0,5).map(p=>{const team=teamById(p.teamId);return`
              <a href="#/players/${p.id}" style="display:flex;align-items:center;gap:12px;padding:12px;background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-md);transition:all .2s" onmouseover="this.style.borderColor='var(--border-light)'" onmouseout="this.style.borderColor='var(--border)'">
                <div style="width:36px;height:36px;border-radius:50%;background:var(--surface-hover);border:1px solid var(--border);display:grid;place-items:center;font-family:var(--font-display);font-weight:700;font-size:14px;color:var(--text-muted)">${p.name.charAt(0)}</div>
                <div style="flex:1;min-width:0"><div style="font-weight:600;font-size:14px">${p.name}</div><div class="small">${p.position} · ${team?.name||''}</div></div>
                <div style="text-align:right"><div style="font-family:var(--font-mono);font-weight:700;font-size:16px;color:var(--accent)">${p.stats.goals}</div><div class="small">goals</div></div>
              </a>
            `}).join('')}
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section" style="padding-top:0">
    <div class="container">
      ${sectionHeader("Premier League Standings","Table",`<a href="#/standings" class="small" style="color:var(--accent)">Full table →</a>`)}
      <div class="standings">
        <table>
          <thead><tr><th style="width:36px">#</th><th>Team</th><th class="num">MP</th><th class="num hide-mobile">W</th><th class="num hide-mobile">D</th><th class="num hide-mobile">L</th><th class="num hide-mobile">GD</th><th class="num">PTS</th><th class="num hide-mobile">Form</th></tr></thead>
          <tbody>
            ${standings.slice(0,8).map(s=>{const t=teamById(s.teamId);return`<tr class="zone-${s.zone||''}">
              <td class="pos">${s.pos}</td>
              <td><div class="team-cell">${crest(t,22)}<span>${t.name}</span></div></td>
              <td class="num">${s.mp}</td>
              <td class="num hide-mobile">${s.w}</td>
              <td class="num hide-mobile">${s.d}</td>
              <td class="num hide-mobile">${s.l}</td>
              <td class="num hide-mobile">${s.gd>0?'+':''}${s.gd}</td>
              <td class="pts">${s.pts}</td>
              <td class="hide-mobile"><div class="form-row">${formDots(s.form)}</div></td>
            </tr>`}).join('')}
          </tbody>
        </table>
      </div>
    </div>
  </section>

  <section class="section" style="padding-top:0">
    <div class="container">
      ${sectionHeader("Tactical Analysis","Pitch View")}
      <div class="grid" style="grid-template-columns:1fr 1fr;gap:24px">
        <div class="card" style="padding:24px">
          <h3 class="h3 mb-3">Manchester City · 4-3-3</h3>
          <div class="pitch">
            ${[{x:50,y:90,n:'Ederson',num:31},{x:15,y:70,n:'Gvardiol',num:24},{x:38,y:75,n:'Stones',num:5},{x:62,y:75,n:'Dias',num:3},{x:85,y:70,n:'Walker',num:2},{x:30,y:45,n:'Bernardo',num:20},{x:50,y:50,n:'Rodri',num:16,c:true},{x:70,y:45,n:'De Bruyne',num:17},{x:20,y:20,n:'Grealish',num:10},{x:50,y:15,n:'Haaland',num:9},{x:80,y:20,n:'Foden',num:47}].map(p=>`
              <div class="pp ${p.c?'captain':''}" style="left:${p.x}%;top:${p.y}%"><div class="pp-dot">${p.num}</div><div class="pp-name">${p.n}</div></div>
            `).join('')}
          </div>
          <div class="small mt-2" style="text-align:center">Demonstration Data</div>
        </div>
        <div class="card" style="padding:24px">
          <h3 class="h3 mb-3">Tactical Breakdown</h3>
          ${[{l:'Formation',v:'4-3-3 (asymmetric)'},{l:'Shape in possession',v:'3-2-4-1'},{l:'Pressing intensity',v:'Medium-high'},{l:'Build-up style',v:'Play from the back'},{l:'Primary zones',v:'Right half-space, central'},{l:'Key player',v:'Kevin De Bruyne'},{l:'Strengths',v:'Possession control'},{l:'Vulnerabilities',v:'Transitions'}].map(i=>`
            <div style="padding:10px 0;border-bottom:1px solid var(--border)"><div class="meta mb-1">${i.l}</div><div style="font-size:14px;font-weight:500">${i.v}</div></div>
          `).join('')}
        </div>
      </div>
    </div>
  </section>

  <section class="section" style="padding-top:0">
    <div class="container">
      ${sectionHeader("Football Intelligence","AI Analysis",`<a href="#/intel" class="small" style="color:var(--accent)">Explore Intel →</a>`)}
      <div class="grid" style="grid-template-columns:repeat(auto-fit,minmax(320px,1fr));gap:14px">
        ${[{q:"Analyze Man City's approach against low-block defenses.",a:'City average 68% possession vs low-block opponents, with increased switches of play (4.2/game). Rodri creates a 3-2 build-up base...'},
           {q:"Compare Haaland's xG conversion to top strikers.",a:'Haaland leads with 0.87 xG conversion (28 goals from 32.2 xG). Salah second at 0.79, Isak 0.74. Elite inside-box efficiency (0.92)...'}
        ].map(i=>`
          <div class="intel-card">
            <div class="ic-prompt"><div class="ic-icon"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2z"/><path d="M12 6v6l4 2"/></svg></div><div class="ic-text">${i.q}</div></div>
            <div class="ic-response"><p>${i.a}</p></div>
            <div class="ic-tag">⚡ AI-generated example</div>
          </div>
        `).join('')}
      </div>
    </div>
  </section>

  <section class="section" style="padding-top:0">
    <div class="container">
      <div class="newsletter">
        <div class="section-eyebrow" style="justify-content:center">Newsletter</div>
        <h2>The daily football briefing.</h2>
        <p>Get the most important football stories, tactical analysis, and transfer intelligence delivered to your inbox every morning.</p>
        <form class="nl-form" onsubmit="event.preventDefault();this.querySelector('input').value='';this.querySelector('button').textContent='Subscribed ✓'">
          <input type="email" placeholder="Enter your email" required>
          <button class="btn btn-primary" type="submit">Subscribe</button>
        </form>
      </div>
    </div>
  </section>
  `;
  setupDragScroll($('#scoresScroll'));
  $$('.filter-chip').forEach(chip=>{chip.addEventListener('click',()=>{chip.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));chip.classList.add('active')})});
});

route('/live',async(main)=>{
  const fixtures=await repo.getFixtures();
  const live=fixtures.filter(f=>['LIVE','HT'].includes(f.status));
  const recent=fixtures.filter(f=>f.status==='FT');
  const upcoming=fixtures.filter(f=>f.status==='UPCOMING');
  main.innerHTML=`
    <div class="page-header"><div class="container"><div class="section-eyebrow">Live</div><h1>Live Football Scores</h1><p>Real-time scores, match events, and statistics from competitions around the world.</p></div></div>
    <section class="section"><div class="container">
      ${live.length?`<h2 class="h3 mb-3">Live Now</h2><div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:14px;margin-bottom:32px">${live.map(matchCard).join('')}</div>`:''}
      ${recent.length?`<h2 class="h3 mb-3">Finished Today</h2><div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:14px;margin-bottom:32px">${recent.map(matchCard).join('')}</div>`:''}
      ${upcoming.length?`<h2 class="h3 mb-3">Upcoming</h2><div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:14px">${upcoming.map(matchCard).join('')}</div>`:''}
    </div></section>`;
});

route('/matches',async(main)=>{
  const fixtures=await repo.getFixtures();
  main.innerHTML=`
    <div class="page-header"><div class="container"><div class="section-eyebrow">Fixtures</div><h1>Football Matches</h1><p>Fixtures, results, and match previews from leagues around the world.</p></div></div>
    <section class="section"><div class="container">
      <div class="filters"><button class="filter-chip active">All</button><button class="filter-chip">Today</button><button class="filter-chip">This Week</button><button class="filter-chip">Premier League</button><button class="filter-chip">La Liga</button></div>
      <div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:14px">${fixtures.map(matchCard).join('')}</div>
    </div></section>`;
  $$('.filter-chip').forEach(chip=>{chip.addEventListener('click',()=>{chip.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));chip.classList.add('active')})});
});

route('/matches/:id',async(main)=>{
  const id=window.__routeParams[0];
  const fixture=await repo.getFixture(id);
  if(!fixture){main.innerHTML='<div class="page-header"><div class="container"><h1>Match not found</h1></div></div>';return}
  const home=teamById(fixture.homeTeamId),away=teamById(fixture.awayTeamId),league=leagueById(fixture.leagueId);
  const events=await repo.getMatchEvents(id);
  main.innerHTML=`
    <div class="match-header"><div class="container">
      <div style="text-align:center;margin-bottom:20px">
        <div class="fm-comp">${league?.name||'Competition'} · ${fixture.round||''}</div>
        <div class="fm-venue">${fixture.venue} · ${formatDate(fixture.date)}</div>
        <div class="mt-2">${statusBadge(fixture.status,fixture.minute)}</div>
      </div>
      <div class="mc-scoreboard">
        <div>${crest(home,72)}<div class="mc-team">${home.name}</div></div>
        <div class="mc-score">${fixture.homeScore??'-'}<span class="sep">:</span>${fixture.awayScore??'-'}</div>
        <div>${crest(away,72)}<div class="mc-team">${away.name}</div></div>
      </div>
      <div class="tabs" role="tablist">
        <button class="tab active" data-tab="overview">Overview</button>
        <button class="tab" data-tab="timeline">Timeline</button>
        <button class="tab" data-tab="lineups">Lineups</button>
        <button class="tab" data-tab="statistics">Statistics</button>
        <button class="tab" data-tab="tactics">Tactics</button>
        <button class="tab" data-tab="h2h">Head-to-Head</button>
      </div>
    </div></div>
    <section class="section" style="padding-top:28px"><div class="container"><div id="tabContent"></div></div></section>`;
  
  const tabs={
    overview:`<div class="grid" style="grid-template-columns:1fr 1fr;gap:20px">
      <div class="card" style="padding:20px">
        <h3 class="h3 mb-3">Match Summary</h3>
        <p class="body-lg">A compelling encounter that saw ${home.name} edge past ${away.name} in a tactical battle. The home side's control of possession ultimately proved decisive.</p>
        <div class="divider"></div>
        <div class="meta mb-2" style="color:var(--text)">Key Facts</div>
        <ul style="list-style:none;display:flex;flex-direction:column;gap:8px;font-size:13px">
          <li style="display:flex;justify-content:space-between;padding:6px 0;border-bottom:1px solid var(--border)"><span class="text-muted">Referee</span><span>Michael Oliver</span></li>
          <li style="display:flex;justify-content:space-between;padding:6px 0;border-bottom:1px solid var(--border)"><span class="text-muted">Attendance</span><span>53,400</span></li>
          <li style="display:flex;justify-content:space-between;padding:6px 0"><span class="text-muted">Match rating</span><span style="color:var(--accent);font-weight:600">8.4 / 10</span></li>
        </ul>
      </div>
      <div class="card" style="padding:20px">
        <h3 class="h3 mb-3">Key Statistics</h3>
        <div class="stat-compare">
          ${[{l:'Possession',h:62,a:38},{l:'Shots',h:14,a:7},{l:'Shots on Target',h:6,a:2},{l:'Corners',h:8,a:3},{l:'Fouls',h:9,a:12},{l:'xG',h:2.4,a:0.9}].map(s=>`
            <div class="stat-row"><div class="val home">${s.h}</div><div style="display:flex;flex-direction:column;gap:4px;flex:1"><div class="label">${s.l}</div><div class="stat-bar-wrap"><div class="stat-bar home"><div class="stat-bar-fill" style="width:${s.h/(s.h+s.a)*100}%"></div></div><div class="stat-bar away"><div class="stat-bar-fill" style="width:${s.a/(s.h+s.a)*100}%"></div></div></div></div><div class="val away">${s.a}</div></div>
          `).join('')}
        </div>
      </div>
    </div>`,
    timeline:`<div class="card" style="padding:20px">
      <h3 class="h3 mb-3">Match Timeline</h3>
      <div class="timeline"><div class="tl-line"></div>
        ${events.map(e=>{const icon={goal:'⚽',yellow:'🟨',red:'🟥',substitution:'↔',var:'📺'}[e.type]||'•';
          const desc=e.type==='goal'?`<strong>${e.player}</strong>${e.assist?` (${e.assist})`:''}`:e.type==='substitution'?`${e.playerIn} ↔ ${e.playerOut}`:`<strong>${e.player}</strong>`;
          return`<div class="tl-event ${e.type}"><div class="tl-content home">${e.teamId===fixture.homeTeamId?desc:''}</div><div class="tl-marker">${icon}</div><div class="tl-content away">${e.teamId===fixture.awayTeamId?desc:''}</div></div><div style="text-align:center;font-family:var(--font-mono);font-size:11px;color:var(--text-muted);margin:-6px 0 6px">${e.minute}' · ${e.scoreAfter||''}</div>`}).join('')}
      </div>
    </div>`,
    lineups:`<div class="grid" style="grid-template-columns:1fr 1fr;gap:20px">
      ${[home,away].map(team=>`<div class="card" style="padding:20px">
        <div style="display:flex;align-items:center;gap:10px;margin-bottom:16px">${crest(team,36)}<div><h3 style="font-size:15px;font-weight:600">${team.name}</h3><div class="small">4-3-3 Formation</div></div></div>
        <div style="display:flex;flex-direction:column;gap:6px">
          ${['GK: Ederson','DF: Walker, Dias, Stones, Gvardiol','MF: Rodri, De Bruyne, Bernardo','FW: Foden, Haaland, Grealish'].map(line=>{const[pos,players]=line.split(': ');return`<div style="padding:8px 10px;background:var(--surface-hover);border-radius:var(--radius-sm);font-size:12px"><span style="color:var(--accent);font-weight:700;margin-right:6px">${pos}</span>${players}</div>`}).join('')}
        </div>
        <div class="small mt-2">Coach: ${team.coach}</div>
      </div>`).join('')}
    </div>`,
    statistics:`<div class="card" style="padding:20px">
      <h3 class="h3 mb-3">Match Statistics</h3>
      <div class="stat-compare">
        ${[{l:'Possession',h:62,a:38},{l:'Shots',h:14,a:7},{l:'Shots on Target',h:6,a:2},{l:'Corners',h:8,a:3},{l:'Fouls',h:9,a:12},{l:'Passes',h:612,a:348},{l:'Pass Accuracy',h:91,a:82},{l:'xG',h:2.4,a:0.9}].map(s=>`
          <div class="stat-row"><div class="val home">${s.h}</div><div style="display:flex;flex-direction:column;gap:4px;flex:1"><div class="label">${s.l}</div><div class="stat-bar-wrap"><div class="stat-bar home"><div class="stat-bar-fill" style="width:${s.h/(s.h+s.a)*100}%"></div></div><div class="stat-bar away"><div class="stat-bar-fill" style="width:${s.a/(s.h+s.a)*100}%"></div></div></div></div><div class="val away">${s.a}</div></div>
        `).join('')}
      </div>
    </div>`,
    tactics:`<div class="grid" style="grid-template-columns:1fr 1fr;gap:20px">
      <div class="card" style="padding:20px">
        <h3 class="h3 mb-3">${home.name} · Tactical Setup</h3>
        <div class="pitch">
          ${[{x:50,y:90,n:'Ederson',num:31},{x:15,y:70,n:'Gvardiol',num:24},{x:38,y:75,n:'Stones',num:5},{x:62,y:75,n:'Dias',num:3},{x:85,y:70,n:'Walker',num:2},{x:30,y:45,n:'Bernardo',num:20},{x:50,y:50,n:'Rodri',num:16,c:true},{x:70,y:45,n:'De Bruyne',num:17},{x:20,y:20,n:'Grealish',num:10},{x:50,y:15,n:'Haaland',num:9},{x:80,y:20,n:'Foden',num:47}].map(p=>`<div class="pp ${p.c?'captain':''}" style="left:${p.x}%;top:${p.y}%"><div class="pp-dot">${p.num}</div><div class="pp-name">${p.n}</div></div>`).join('')}
        </div>
        <div class="small mt-2" style="text-align:center">Demonstration Data</div>
      </div>
      <div class="card" style="padding:20px">
        <h3 class="h3 mb-3">Tactical Analysis</h3>
        ${[{l:'Formation',v:'4-3-3 (asymmetric)'},{l:'Shape in possession',v:'3-2-4-1'},{l:'Pressing',v:'Medium-high'},{l:'Build-up',v:'Play from back'},{l:'Key zones',v:'Right half-space'},{l:'Strengths',v:'Possession control'},{l:'Weaknesses',v:'Transitions'}].map(i=>`<div style="padding:8px 0;border-bottom:1px solid var(--border)"><div class="meta mb-1">${i.l}</div><div style="font-size:13px;font-weight:500">${i.v}</div></div>`).join('')}
      </div>
    </div>`,
    h2h:`<div class="card" style="padding:20px">
      <h3 class="h3 mb-3">Head-to-Head</h3>
      <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-bottom:20px;text-align:center">
        <div style="padding:16px;background:var(--surface-hover);border-radius:var(--radius-sm)"><div style="font-family:var(--font-mono);font-size:28px;font-weight:700;color:var(--accent)">12</div><div class="small mt-1">${home.shortName} Wins</div></div>
        <div style="padding:16px;background:var(--surface-hover);border-radius:var(--radius-sm)"><div style="font-family:var(--font-mono);font-size:28px;font-weight:700">6</div><div class="small mt-1">Draws</div></div>
        <div style="padding:16px;background:var(--surface-hover);border-radius:var(--radius-sm)"><div style="font-family:var(--font-mono);font-size:28px;font-weight:700">8</div><div class="small mt-1">${away.shortName} Wins</div></div>
      </div>
      <div class="meta mb-2" style="color:var(--text)">Recent Meetings</div>
      <div style="display:flex;flex-direction:column;gap:6px">
        ${[{d:'2026-04-12',hs:2,as:1},{d:'2025-11-25',hs:1,as:1},{d:'2025-03-08',hs:3,as:0}].map(m=>`
          <div style="display:grid;grid-template-columns:70px 1fr auto 1fr 50px;gap:8px;align-items:center;padding:8px;background:var(--surface-hover);border-radius:var(--radius-sm);font-size:12px">
            <span class="small">${formatDate(m.d)}</span><span style="text-align:right">${home.shortName}</span><span style="font-family:var(--font-mono);font-weight:700;text-align:center">${m.hs} - ${m.as}</span><span>${away.shortName}</span><span class="badge" style="font-size:8px;padding:2px 5px">${m.hs>m.as?home.shortName:m.hs<m.as?away.shortName:'DRAW'}</span>
          </div>
        `).join('')}
      </div>
    </div>`
  };
  const tabContent=$('#tabContent');
  tabContent.innerHTML=tabs.overview;
  $$('.tab').forEach(t=>{t.addEventListener('click',()=>{$$('.tab').forEach(x=>x.classList.remove('active'));t.classList.add('active');tabContent.innerHTML=tabs[t.dataset.tab]})});
});

route('/news',async(main)=>{
  const articles=await repo.getArticles();
  const featured=articles[0],rest=articles.slice(1);
  main.innerHTML=`
    <div class="page-header"><div class="container"><div class="section-eyebrow">Editorial</div><h1>Football News</h1><p>Latest news, tactical analysis, and editorial coverage from the world of football.</p></div></div>
    <section class="section"><div class="container">
      <div class="filters"><button class="filter-chip active">All</button><button class="filter-chip">Breaking</button><button class="filter-chip">Transfers</button><button class="filter-chip">Tactics</button><button class="filter-chip">Players</button></div>
      <div class="news-grid mb-4">
        <article class="news-featured" onclick="location.hash='/news/${featured.slug}'">
          <div class="news-featured-bg"></div>
          <div class="news-featured-content">
            <span class="badge badge-accent">${featured.category}</span>
            <h2 class="news-featured-title">${featured.title}</h2>
            <p class="news-featured-summary">${featured.summary}</p>
            <div class="news-item-meta">By ${featured.author} · ${relativeTime(featured.publishedAt)}</div>
          </div>
        </article>
        <div class="news-list">${rest.slice(0,5).map(newsItem).join('')}</div>
      </div>
      <h2 class="h3 mb-3">More Stories</h2>
      <div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:14px">
        ${rest.slice(5).map(a=>`<article class="card card-hover" style="padding:18px;cursor:pointer" onclick="location.hash='/news/${a.slug}'">
          <div style="aspect-ratio:16/9;border-radius:var(--radius-sm);background:linear-gradient(135deg,var(--surface-hover),var(--bg));margin-bottom:12px;position:relative;overflow:hidden"><div style="position:absolute;inset:0;background:radial-gradient(circle at 30% 30%,rgba(0,255,135,.08),transparent 60%)"></div></div>
          <span class="news-item-cat">${a.category}</span>
          <h3 style="font-family:var(--font-display);font-weight:600;font-size:16px;line-height:1.3;margin:6px 0">${a.title}</h3>
          <p class="small">${a.summary.substring(0,90)}...</p>
          <div class="small mt-2">${relativeTime(a.publishedAt)} · ${a.readTime}</div>
        </article>`).join('')}
      </div>
    </div></section>`;
  $$('.filter-chip').forEach(chip=>{chip.addEventListener('click',()=>{chip.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));chip.classList.add('active')})});
});

route('/news/:slug',async(main)=>{
  const slug=window.__routeParams[0];
  const article=await repo.getArticle(slug);
  if(!article){main.innerHTML='<div class="page-header"><div class="container"><h1>Article not found</h1></div></div>';return}
  const related=(await repo.getArticles()).filter(a=>a.slug!==slug).slice(0,3);
  main.innerHTML=`
    <div style="padding-top:calc(var(--header-h) + 36px)"></div>
    <section class="section" style="padding-top:0"><div class="container">
      <div class="grid-editorial">
        <article class="article">
          <div class="article-head">
            <nav class="breadcrumb" aria-label="Breadcrumb"><a href="#/">Home</a><span class="sep">/</span><a href="#/news">News</a><span class="sep">/</span><a href="#/news">${article.category}</a></nav>
            <span class="badge badge-accent mb-2">${article.category}</span>
            <h1 class="article-title">${article.title}</h1>
            <p class="article-subtitle">${article.subtitle}</p>
            <div class="article-meta">
              <span>By <strong style="color:var(--text)">${article.author}</strong></span><span class="dot" style="width:3px;height:3px;border-radius:50%;background:var(--text-muted)"></span>
              <span>${formatDate(article.publishedAt)}</span><span class="dot" style="width:3px;height:3px;border-radius:50%;background:var(--text-muted)"></span><span>${article.readTime}</span>
            </div>
          </div>
          <div class="article-hero"></div>
          <div class="article-body">${article.body}</div>
          <div class="divider"></div>
          <div style="display:flex;gap:8px;flex-wrap:wrap"><button class="btn btn-ghost">Share</button><button class="btn btn-ghost">Save</button></div>
        </article>
        <div>
          <div class="card" style="padding:20px;margin-bottom:20px">
            <div class="section-eyebrow" style="margin-bottom:14px">Related Stories</div>
            <div style="display:flex;flex-direction:column;gap:12px">
              ${related.map(a=>`<a href="#/news/${a.slug}" style="display:flex;gap:10px;align-items:flex-start">
                <div style="width:60px;height:60px;border-radius:var(--radius-sm);background:linear-gradient(135deg,var(--surface-hover),var(--bg));flex-shrink:0;position:relative;overflow:hidden"><div style="position:absolute;inset:0;background:radial-gradient(circle at 30% 30%,rgba(0,255,135,.08),transparent 60%)"></div></div>
                <div><div style="font-size:13px;font-weight:500;line-height:1.3;margin-bottom:2px">${a.title}</div><div class="small">${a.category} · ${relativeTime(a.publishedAt)}</div></div>
              </a>`).join('')}
            </div>
          </div>
          <div class="card" style="padding:20px">
            <div class="section-eyebrow" style="margin-bottom:14px">Most Read</div>
            <div style="display:flex;flex-direction:column;gap:10px">
              ${(await repo.getArticles()).slice(0,4).map((a,i)=>`<a href="#/news/${a.slug}" style="display:flex;gap:8px;align-items:flex-start">
                <span style="font-family:var(--font-mono);font-size:16px;font-weight:700;color:var(--text-muted);width:20px;text-align:right">${i+1}</span>
                <div style="font-size:13px;font-weight:500;line-height:1.3">${a.title}</div>
              </a>`).join('')}
            </div>
          </div>
        </div>
      </div>
    </div></section>`;
});

route('/transfers',async(main)=>{
  const transfers=await repo.getTransfers();
  main.innerHTML=`
    <div class="page-header"><div class="container"><div class="section-eyebrow">Market</div><h1>Transfer Center</h1><p>Confirmed deals, rumours, and market intelligence from football's transfer market.</p></div></div>
    <section class="section"><div class="container">
      <div class="filters"><button class="filter-chip active">Latest</button><button class="filter-chip">Confirmed</button><button class="filter-chip">Rumours</button><button class="filter-chip">Big Deals</button></div>
      <div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:14px">${transfers.map(transferCard).join('')}</div>
    </div></section>`;
  $$('.filter-chip').forEach(chip=>{chip.addEventListener('click',()=>{chip.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));chip.classList.add('active')})});
});

route('/leagues',async(main)=>{
  const leagues=await repo.getLeagues();
  main.innerHTML=`
    <div class="page-header"><div class="container"><div class="section-eyebrow">Competitions</div><h1>Football Leagues</h1><p>Explore leagues and competitions from around the world.</p></div></div>
    <section class="section"><div class="container">
      <div class="filters"><button class="filter-chip active">All</button><button class="filter-chip">Europe</button><button class="filter-chip">Domestic</button></div>
      <div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:14px">${leagues.map(leagueCard).join('')}</div>
    </div></section>`;
  $$('.filter-chip').forEach(chip=>{chip.addEventListener('click',()=>{chip.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));chip.classList.add('active')})});
});

route('/leagues/:id',async(main)=>{
  const id=window.__routeParams[0];
  const league=await repo.getLeague(id);
  if(!league){main.innerHTML='<div class="page-header"><div class="container"><h1>League not found</h1></div></div>';return}
  const fixtures=await repo.getFixturesByLeague(id);
  const standings=await repo.getStandings(id);
  main.innerHTML=`
    <div class="page-header"><div class="container">
      <nav class="breadcrumb" aria-label="Breadcrumb"><a href="#/">Home</a><span class="sep">/</span><a href="#/leagues">Leagues</a></nav>
      <div class="flex items-center gap-2 mb-2">
        <div class="lc-logo" style="width:56px;height:56px;font-size:18px">${league.name.split(' ').map(w=>w[0]).join('').substring(0,3)}</div>
        <div><div class="section-eyebrow">${league.country}</div><h1>${league.name}</h1></div>
      </div>
      <p>${league.season} · ${league.teams} teams</p>
    </div></div>
    <section class="section"><div class="container">
      <div class="tabs"><button class="tab active">Overview</button><button class="tab">Standings</button><button class="tab">Fixtures</button><button class="tab">Top Scorers</button></div>
      ${standings.length?`<div class="standings"><table>
        <thead><tr><th>#</th><th>Team</th><th class="num">MP</th><th class="num hide-mobile">W</th><th class="num hide-mobile">D</th><th class="num hide-mobile">L</th><th class="num hide-mobile">GD</th><th class="num">PTS</th></tr></thead>
        <tbody>${standings.slice(0,10).map(s=>{const t=teamById(s.teamId);return`<tr><td class="pos">${s.pos}</td><td><div class="team-cell">${crest(t,22)}<span>${t.name}</span></div></td><td class="num">${s.mp}</td><td class="num hide-mobile">${s.w}</td><td class="num hide-mobile">${s.d}</td><td class="num hide-mobile">${s.l}</td><td class="num hide-mobile">${s.gd>0?'+':''}${s.gd}</td><td class="pts">${s.pts}</td></tr>`}).join('')}</tbody>
      </table></div>`:'<p class="body-lg">No data available.</p>'}
      ${fixtures.length?`<h2 class="h3 mt-4 mb-3">Fixtures</h2><div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:14px">${fixtures.map(matchCard).join('')}</div>`:''}
    </div></section>`;
});

route('/teams',async(main)=>{
  const teams=await repo.getTeams();
  main.innerHTML=`
    <div class="page-header"><div class="container"><div class="section-eyebrow">Directory</div><h1>Football Teams</h1><p>Explore clubs from leagues around the world.</p></div></div>
    <section class="section"><div class="container">
      <div class="search-field mb-3" style="max-width:380px;display:flex;align-items:center;gap:8px;padding:8px 12px;border-radius:var(--radius-sm);background:var(--surface);border:1px solid var(--border)">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
        <input type="text" placeholder="Search teams..." id="teamSearch" style="flex:1;background:none;border:0;outline:0;font-size:13px;color:var(--text)">
      </div>
      <div class="filters"><button class="filter-chip active">All</button><button class="filter-chip">England</button><button class="filter-chip">Spain</button><button class="filter-chip">Germany</button><button class="filter-chip">Italy</button></div>
      <div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:14px" id="teamsGrid">${teams.map(teamCard).join('')}</div>
    </div></section>`;
  $('#teamSearch').addEventListener('input',e=>{const q=e.target.value.toLowerCase();$('#teamsGrid').innerHTML=teams.filter(t=>t.name.toLowerCase().includes(q)).map(teamCard).join('')});
  $$('.filter-chip').forEach(chip=>{chip.addEventListener('click',()=>{chip.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));chip.classList.add('active')})});
});

route('/teams/:id',async(main)=>{
  const id=window.__routeParams[0];
  const team=await repo.getTeam(id);
  if(!team){main.innerHTML='<div class="page-header"><div class="container"><h1>Team not found</h1></div></div>';return}
  const players=await repo.getPlayersByTeam(id);
  const fixtures=await repo.getFixturesByTeam(id);
  const league=leagueById(team.leagueId);
  main.innerHTML=`
    <div class="page-header"><div class="container">
      <nav class="breadcrumb" aria-label="Breadcrumb"><a href="#/">Home</a><span class="sep">/</span><a href="#/teams">Teams</a></nav>
      <div class="flex items-center gap-3 mb-3">${crest(team,72)}<div><div class="section-eyebrow">${team.country}</div><h1>${team.name}</h1><p>${league?.name||''} · ${team.stadium}</p></div></div>
      <div class="flex gap-2 mt-2" style="flex-wrap:wrap"><div class="badge">Coach: ${team.coach}</div><div class="badge">Season 2025/26</div><div class="badge">Form: ${team.form.join(' ')}</div></div>
    </div></div>
    <section class="section"><div class="container">
      <div class="tabs"><button class="tab active">Overview</button><button class="tab">Squad</button><button class="tab">Fixtures</button><button class="tab">Statistics</button></div>
      <div class="grid" style="grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:14px;margin-bottom:28px">
        <div class="card" style="padding:18px;text-align:center"><div style="font-family:var(--font-mono);font-size:32px;font-weight:700;color:var(--accent)">28</div><div class="small mt-1">Matches Played</div></div>
        <div class="card" style="padding:18px;text-align:center"><div style="font-family:var(--font-mono);font-size:32px;font-weight:700">52</div><div class="small mt-1">Goals Scored</div></div>
        <div class="card" style="padding:18px;text-align:center"><div style="font-family:var(--font-mono);font-size:32px;font-weight:700">24</div><div class="small mt-1">Goals Conceded</div></div>
        <div class="card" style="padding:18px;text-align:center"><div style="font-family:var(--font-mono);font-size:32px;font-weight:700">+28</div><div class="small mt-1">Goal Difference</div></div>
      </div>
      ${players.length?`<h2 class="h3 mb-3">Squad</h2><div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:14px">${players.map(playerCard).join('')}</div>`:'<p class="body-lg">Squad data coming soon.</p>'}
      ${fixtures.length?`<h2 class="h3 mt-4 mb-3">Fixtures</h2><div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:14px">${fixtures.map(matchCard).join('')}</div>`:''}
    </div></section>`;
});

route('/players',async(main)=>{
  const players=await repo.getPlayers();
  main.innerHTML=`
    <div class="page-header"><div class="container"><div class="section-eyebrow">Directory</div><h1>Football Players</h1><p>Explore player profiles, statistics, and career data.</p></div></div>
    <section class="section"><div class="container">
      <div class="search-field mb-3" style="max-width:380px;display:flex;align-items:center;gap:8px;padding:8px 12px;border-radius:var(--radius-sm);background:var(--surface);border:1px solid var(--border)">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
        <input type="text" placeholder="Search players..." id="playerSearch" style="flex:1;background:none;border:0;outline:0;font-size:13px;color:var(--text)">
      </div>
      <div class="filters"><button class="filter-chip active">All</button><button class="filter-chip">Forwards</button><button class="filter-chip">Midfielders</button><button class="filter-chip">Defenders</button></div>
      <div class="grid" style="grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:14px" id="playersGrid">${players.map(playerCard).join('')}</div>
    </div></section>`;
  $('#playerSearch').addEventListener('input',e=>{const q=e.target.value.toLowerCase();$('#playersGrid').innerHTML=players.filter(p=>p.name.toLowerCase().includes(q)).map(playerCard).join('')});
  $$('.filter-chip').forEach(chip=>{chip.addEventListener('click',()=>{chip.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));chip.classList.add('active')})});
});

route('/players/:id',async(main)=>{
  const id=window.__routeParams[0];
  const player=await repo.getPlayer(id);
  if(!player){main.innerHTML='<div class="page-header"><div class="container"><h1>Player not found</h1></div></div>';return}
  const team=teamById(player.teamId);
  main.innerHTML=`
    <div class="page-header"><div class="container">
      <nav class="breadcrumb" aria-label="Breadcrumb"><a href="#/">Home</a><span class="sep">/</span><a href="#/players">Players</a></nav>
      <div style="display:grid;grid-template-columns:auto 1fr;gap:20px;align-items:center">
        <div class="pc-photo" style="width:100px;height:100px;font-size:40px;border-radius:var(--radius-md)">${player.name.charAt(0)}</div>
        <div>
          <div class="section-eyebrow">${player.nationality} · #${player.number}</div>
          <h1>${player.name}</h1>
          <p>${player.position} · <a href="#/teams/${team?.id}" style="color:var(--accent)">${team?.name||''}</a></p>
          <div class="flex gap-2 mt-2" style="flex-wrap:wrap"><div class="badge">Age: ${player.age}</div><div class="badge">Position: ${player.position}</div></div>
        </div>
      </div>
    </div></div>
    <section class="section"><div class="container">
      <div class="tabs"><button class="tab active">Overview</button><button class="tab">Statistics</button><button class="tab">Career</button><button class="tab">Matches</button></div>
      <div class="grid" style="grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:14px;margin-bottom:28px">
        <div class="card" style="padding:20px;text-align:center"><div style="font-family:var(--font-mono);font-size:36px;font-weight:700;color:var(--accent)">${player.stats.goals}</div><div class="small mt-1">Goals</div></div>
        <div class="card" style="padding:20px;text-align:center"><div style="font-family:var(--font-mono);font-size:36px;font-weight:700">${player.stats.assists}</div><div class="small mt-1">Assists</div></div>
        <div class="card" style="padding:20px;text-align:center"><div style="font-family:var(--font-mono);font-size:36px;font-weight:700">${player.stats.apps}</div><div class="small mt-1">Appearances</div></div>
        <div class="card" style="padding:20px;text-align:center"><div style="font-family:var(--font-mono);font-size:36px;font-weight:700">${(player.stats.goals/player.stats.apps).toFixed(2)}</div><div class="small mt-1">Goals/App</div></div>
      </div>
      <div class="card" style="padding:20px">
        <h3 class="h3 mb-3">Performance Snapshot</h3>
        <p class="body-lg mb-3">${player.name} has contributed ${player.stats.goals} goals and ${player.stats.assists} assists in ${player.stats.apps} appearances for ${team?.name||'his club'}.</p>
        <div class="stat-compare">
          ${[{l:'Minutes played',v:player.stats.apps*82,m:player.stats.apps*90},{l:'Shot accuracy',v:58,m:100},{l:'Pass accuracy',v:84,m:100},{l:'Dribble success',v:62,m:100}].map(s=>`
            <div class="stat-row"><div class="val home" style="color:var(--accent)">${s.v}</div><div style="display:flex;flex-direction:column;gap:4px;flex:1"><div class="label">${s.l}</div><div class="stat-bar home" style="flex:1"><div class="stat-bar-fill" style="width:${s.v/s.m*100}%"></div></div></div><div></div></div>
          `).join('')}
        </div>
      </div>
    </div></section>`;
});

route('/standings',async(main)=>{
  const standings=await repo.getStandings();
  main.innerHTML=`
    <div class="page-header"><div class="container"><div class="section-eyebrow">Tables</div><h1>Football Standings</h1><p>Live league tables from competitions around the world.</p></div></div>
    <section class="section"><div class="container">
      <div class="filters"><button class="filter-chip active">Premier League</button><button class="filter-chip">La Liga</button><button class="filter-chip">Bundesliga</button><button class="filter-chip">Serie A</button></div>
      <div class="standings"><table>
        <thead><tr><th style="width:36px">#</th><th>Team</th><th class="num">MP</th><th class="num hide-mobile">W</th><th class="num hide-mobile">D</th><th class="num hide-mobile">L</th><th class="num hide-mobile">GF</th><th class="num hide-mobile">GA</th><th class="num hide-mobile">GD</th><th class="num">PTS</th><th class="num hide-mobile">Form</th></tr></thead>
        <tbody>${standings.map(s=>{const t=teamById(s.teamId);return`<tr class="zone-${s.zone||''}"><td class="pos">${s.pos}</td><td><div class="team-cell">${crest(t,22)}<span>${t.name}</span></div></td><td class="num">${s.mp}</td><td class="num hide-mobile">${s.w}</td><td class="num hide-mobile">${s.d}</td><td class="num hide-mobile">${s.l}</td><td class="num hide-mobile">${s.gf}</td><td class="num hide-mobile">${s.ga}</td><td class="num hide-mobile">${s.gd>0?'+':''}${s.gd}</td><td class="pts">${s.pts}</td><td class="hide-mobile"><div class="form-row">${formDots(s.form)}</div></td></tr>`}).join('')}</tbody>
      </table></div>
      <div class="mt-3 small" style="display:flex;gap:14px;flex-wrap:wrap">
        <span><span style="display:inline-block;width:10px;height:10px;background:var(--accent);border-radius:2px;vertical-align:middle;margin-right:4px"></span>Champions League</span>
        <span><span style="display:inline-block;width:10px;height:10px;background:var(--blue);border-radius:2px;vertical-align:middle;margin-right:4px"></span>Europa League</span>
        <span><span style="display:inline-block;width:10px;height:10px;background:var(--red);border-radius:2px;vertical-align:middle;margin-right:4px"></span>Relegation</span>
      </div>
    </div></section>`;
  $$('.filter-chip').forEach(chip=>{chip.addEventListener('click',()=>{chip.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));chip.classList.add('active')})});
});

route('/history',async(main)=>{
  main.innerHTML=`
    <div class="page-header"><div class="container"><div class="section-eyebrow">Archive</div><h1>Football History</h1><p>Legendary matches, iconic players, and the moments that shaped the beautiful game.</p></div></div>
    <section class="section"><div class="container">
      <div class="filters"><button class="filter-chip active">All</button><button class="filter-chip">Players</button><button class="filter-chip">Clubs</button><button class="filter-chip">Matches</button><button class="filter-chip">Records</button></div>
      <div class="grid" style="grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:14px">
        ${[{y:'1958',t:'The Munich Air Disaster',d:'The tragic event that forever changed Manchester United and world football.'},{y:'1970',t:"Brazil's Perfect World Cup",d:'The greatest team ever assembled — Pelé, Jairzinho, Gérson, Tostão, Rivelino.'},{y:'1986',t:"Maradona's Hand of God",d:'The most controversial moment in World Cup history.'},{y:'1999',t:"Manchester United's Treble",d:'The greatest season in English club football.'},{y:'2005',t:'The Miracle of Istanbul',d:"Liverpool's incredible Champions League final comeback against AC Milan."},{y:'2009',t:"Barcelona's Sextuple",d:"Pep Guardiola's side completes an unprecedented six-trophy calendar year."},{y:'2014',t:'Germany 7-1 Brazil',d:'The semi-final that shocked the world in Belo Horizonte.'},{y:'2022',t:'Messi Finally Lifts the World Cup',d:"Argentina's emotional victory in Qatar completes football's greatest story."}].map(e=>`
          <article class="card card-hover" style="padding:20px">
            <div style="font-family:var(--font-mono);font-size:12px;color:var(--accent);letter-spacing:.08em;margin-bottom:6px">${e.y}</div>
            <h3 style="font-family:var(--font-display);font-size:18px;font-weight:600;margin-bottom:6px;letter-spacing:-.01em">${e.t}</h3>
            <p class="body">${e.d}</p>
          </article>
        `).join('')}
      </div>
    </div></section>`;
  $$('.filter-chip').forEach(chip=>{chip.addEventListener('click',()=>{chip.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));chip.classList.add('active')})});
});

route('/intel',async(main)=>{
  main.innerHTML=`
    <div class="page-header"><div class="container"><div class="section-eyebrow">AI Intelligence</div><h1>Football Intelligence</h1><p>AI-powered analysis, tactical breakdowns, and football Q&A. Demonstration responses only.</p></div></div>
    <section class="section"><div class="container">
      <div class="filters"><button class="filter-chip active">All</button><button class="filter-chip">Match Analysis</button><button class="filter-chip">Tactical</button><button class="filter-chip">Player</button><button class="filter-chip">Q&A</button></div>
      <div class="grid" style="grid-template-columns:repeat(auto-fit,minmax(320px,1fr));gap:14px">
        ${[{q:"Analyze Man City's tactical approach against low-block defenses.",a:'City average 68% possession against low-block opponents, with increased switches of play (4.2/game). Rodri creates a 3-2 build-up base...'},
           {q:"Compare Haaland's xG conversion rate to top strikers.",a:'Haaland leads with 0.87 xG conversion (28 goals from 32.2 xG). Salah second at 0.79, Isak 0.74. Elite inside-box efficiency...'},
           {q:"What tactical changes has Arsenal made under Arteta?",a:'Arsenal shifted to a fluid 4-3-3 with inverted full-backs. Rice operates as single pivot in build-up, allowing Ødegaard to roam...'},
           {q:"Predict Real Madrid vs Barcelona based on current form.",a:'Barcelona hold slight edge (58% win probability). Defensive solidity under Flick (0.7 xGA/game) gives advantage...'},
           {q:"Who are the most underrated players in Europe?",a:'Several players performing at elite levels: Éderson (Atalanta), Xavi Simons creative output, Florian Wirtz progressive carries...'},
           {q:"Analyze the evolution of the 3-4-3 formation.",a:'The 3-4-3 evolved from defensive system to attacking weapon. Key developments: ball-playing CBs, wing-backs as wingers...'}
        ].map(i=>`
          <div class="intel-card">
            <div class="ic-prompt"><div class="ic-icon"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2z"/><path d="M12 6v6l4 2"/></svg></div><div class="ic-text">${i.q}</div></div>
            <div class="ic-response"><p>${i.a}</p></div>
            <div class="ic-tag">⚡ AI-generated example</div>
          </div>
        `).join('')}
      </div>
    </div></section>`;
  $$('.filter-chip').forEach(chip=>{chip.addEventListener('click',()=>{chip.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));chip.classList.add('active')})});
});

// Header scroll
const header=$('#header');
window.addEventListener('scroll',()=>{if(window.scrollY>40)header.classList.add('scrolled');else header.classList.remove('scrolled')},{passive:true});

// Mobile nav
function toggleMobileNav(){const nav=$('#mobileNav');nav.classList.toggle('open');nav.setAttribute('aria-hidden',!nav.classList.contains('open'));document.body.style.overflow=nav.classList.contains('open')?'hidden':''}

// Search
function openSearch(){$('#searchModal').classList.add('open');setTimeout(()=>$('#searchInput').focus(),100);renderSearchResults('')}
function closeSearch(){$('#searchModal').classList.remove('open');$('#searchInput').value=''}
$('#searchModal').addEventListener('click',e=>{if(e.target.id==='searchModal')closeSearch()});
document.addEventListener('keydown',e=>{if((e.ctrlKey||e.metaKey)&&e.key==='k'){e.preventDefault();openSearch()}if(e.key==='Escape')closeSearch()});
$('#searchInput').addEventListener('input',async e=>{renderSearchResults(e.target.value)});
async function renderSearchResults(q){
  const results=$('#searchResults');
  if(!q){results.innerHTML=`<div class="search-group"><div class="search-group-title">Trending Searches</div>${['Premier League','Champions League','Erling Haaland','Transfer News','Live Scores'].map(s=>`<div class="search-result" onclick="document.getElementById('searchInput').value='${s}';renderSearchResults('${s}')"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" style="color:var(--text-muted)"><polyline points="22 7 13.5 15.5 8.5 10.5 2 17"/><polyline points="16 7 22 7 22 13"/></svg><div class="search-result-info"><h4>${s}</h4></div></div>`).join('')}</div>`;return}
  const data=await repo.search(q);
  results.innerHTML=`
    ${data.teams.length?`<div class="search-group"><div class="search-group-title">Teams</div>${data.teams.slice(0,4).map(t=>`<div class="search-result" onclick="closeSearch();location.hash='/teams/${t.id}'">${crest(t,26)}<div class="search-result-info"><h4>${t.name}</h4><p>${t.country} · ${leagueById(t.leagueId)?.name||''}</p></div></div>`).join('')}</div>`:''}
    ${data.players.length?`<div class="search-group"><div class="search-group-title">Players</div>${data.players.slice(0,4).map(p=>`<div class="search-result" onclick="closeSearch();location.hash='/players/${p.id}'"><div class="crest" style="width:26px;height:26px;border-radius:50%;font-size:10px">${p.name.charAt(0)}</div><div class="search-result-info"><h4>${p.name}</h4><p>${p.position} · ${teamById(p.teamId)?.name||''}</p></div></div>`).join('')}</div>`:''}
    ${data.leagues.length?`<div class="search-group"><div class="search-group-title">Leagues</div>${data.leagues.slice(0,3).map(l=>`<div class="search-result" onclick="closeSearch();location.hash='/leagues/${l.id}'"><div class="crest" style="width:26px;height:26px;border-radius:5px;font-size:9px">${l.name.split(' ').map(w=>w[0]).join('').substring(0,3)}</div><div class="search-result-info"><h4>${l.name}</h4><p>${l.country} · ${l.season}</p></div></div>`).join('')}</div>`:''}
    ${data.articles.length?`<div class="search-group"><div class="search-group-title">Articles</div>${data.articles.slice(0,3).map(a=>`<div class="search-result" onclick="closeSearch();location.hash='/news/${a.slug}'"><div class="crest" style="width:26px;height:26px;border-radius:5px;font-size:11px;background:var(--accent-dim);color:var(--accent);border-color:rgba(0,255,135,.3)">⚡</div><div class="search-result-info"><h4>${a.title}</h4><p>${a.category} · ${relativeTime(a.publishedAt)}</p></div></div>`).join('')}</div>`:''}
    ${!data.teams.length&&!data.players.length&&!data.leagues.length&&!data.articles.length?`<div class="search-group" style="text-align:center;padding:32px 20px"><p class="text-muted">No results for "${q}"</p></div>`:''}
  `;
}

// Drag scroll
function setupDragScroll(el){
  if(!el)return;let isDown=false,startX,scrollLeft;
  el.addEventListener('mousedown',e=>{isDown=true;el.style.cursor='grabbing';startX=e.pageX-el.offsetLeft;scrollLeft=el.scrollLeft});
  el.addEventListener('mouseleave',()=>{isDown=false;el.style.cursor='grab'});
  el.addEventListener('mouseup',()=>{isDown=false;el.style.cursor='grab'});
  el.addEventListener('mousemove',e=>{if(!isDown)return;e.preventDefault();const x=e.pageX-el.offsetLeft;el.scrollLeft=scrollLeft-(x-startX)*1.5});
}
</script>
</body>
</html>
