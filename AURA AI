<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>AURA AI — Energy Intelligence</title>
<meta name="description" content="AURA AI — Enerjinin nereye gittiğini yapay zekâ söyler.">

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap');

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Inter,Arial,sans-serif;
    background:#050706;
    color:#f5f7f6;
    overflow-x:hidden;
}

:root{
    --green:#9cff38;
    --green2:#55d66b;
    --dark:#050706;
    --card:#0b100d;
    --border:rgba(156,255,56,.14);
    --muted:#89938d;
}

a{
    color:inherit;
    text-decoration:none;
}

button{
    font-family:inherit;
}

.container{
    width:min(1180px,92%);
    margin:auto;
}

/* BACKGROUND */

.bg{
    position:fixed;
    inset:0;
    pointer-events:none;
    z-index:-2;
    background:
    radial-gradient(circle at 15% 10%,rgba(156,255,56,.12),transparent 28%),
    radial-gradient(circle at 85% 30%,rgba(43,255,140,.07),transparent 25%),
    radial-gradient(circle at 50% 100%,rgba(156,255,56,.06),transparent 30%),
    #050706;
}

.grid{
    position:fixed;
    inset:0;
    z-index:-1;
    pointer-events:none;
    opacity:.18;
    background-image:
    linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),
    linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);
    background-size:55px 55px;
    mask-image:linear-gradient(to bottom,black,transparent 85%);
}

/* NAVBAR */

nav{
    position:fixed;
    top:0;
    width:100%;
    z-index:100;
    backdrop-filter:blur(20px);
    background:rgba(5,7,6,.68);
    border-bottom:1px solid rgba(255,255,255,.06);
}

.nav{
    height:76px;
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.logo{
    display:flex;
    align-items:center;
    gap:11px;
    font-size:20px;
    font-weight:900;
    letter-spacing:-1px;
}

.logo-mark{
    width:34px;
    height:34px;
    border-radius:11px;
    background:var(--green);
    color:#071006;
    display:grid;
    place-items:center;
    font-size:17px;
    box-shadow:0 0 30px rgba(156,255,56,.25);
}

.links{
    display:flex;
    gap:32px;
    color:#aab2ad;
    font-size:13px;
}

.links a{
    transition:.25s;
}

.links a:hover{
    color:white;
}

.nav-btn{
    padding:11px 17px;
    border-radius:12px;
    border:1px solid var(--border);
    background:rgba(156,255,56,.08);
    color:var(--green);
    font-size:13px;
    font-weight:700;
}

/* HERO */

.hero{
    min-height:100vh;
    padding-top:150px;
    display:flex;
    align-items:center;
}

.hero-grid{
    display:grid;
    grid-template-columns:1.05fr .95fr;
    gap:70px;
    align-items:center;
}

.badge{
    display:inline-flex;
    align-items:center;
    gap:9px;
    padding:8px 13px;
    border:1px solid var(--border);
    background:rgba(156,255,56,.06);
    border-radius:100px;
    color:#c8d3cc;
    font-size:11px;
    font-weight:700;
    margin-bottom:25px;
}

.dot{
    width:7px;
    height:7px;
    background:var(--green);
    border-radius:50%;
    box-shadow:0 0 15px var(--green);
}

h1{
    font-size:clamp(48px,7vw,86px);
    line-height:.96;
    letter-spacing:-5px;
    max-width:760px;
}

.gradient{
    color:var(--green);
}

.hero p{
    margin-top:27px;
    color:#98a29c;
    max-width:590px;
    line-height:1.8;
    font-size:16px;
}

.buttons{
    display:flex;
    gap:13px;
    margin-top:34px;
    flex-wrap:wrap;
}

.primary{
    border:0;
    background:var(--green);
    color:#061006;
    padding:15px 22px;
    border-radius:13px;
    font-weight:800;
    cursor:pointer;
    transition:.25s;
}

.primary:hover{
    transform:translateY(-2px);
    box-shadow:0 12px 40px rgba(156,255,56,.18);
}

.secondary{
    border:1px solid rgba(255,255,255,.1);
    background:rgba(255,255,255,.035);
    color:white;
    padding:15px 22px;
    border-radius:13px;
    font-weight:700;
    cursor:pointer;
}

/* HERO VISUAL */

.hero-panel{
    position:relative;
    border:1px solid var(--border);
    background:
    linear-gradient(145deg,rgba(156,255,56,.07),rgba(255,255,255,.015)),
    rgba(9,13,11,.85);
    border-radius:28px;
    padding:22px;
    box-shadow:0 30px 100px rgba(0,0,0,.4);
    animation:float 5s ease-in-out infinite;
}

@keyframes float{
    0%,100%{transform:translateY(0)}
    50%{transform:translateY(-9px)}
}

.panel-top{
    display:flex;
    justify-content:space-between;
    align-items:center;
    margin-bottom:25px;
}

.panel-title{
    font-size:12px;
    color:#aab3ad;
}

.live{
    color:var(--green);
    font-size:10px;
    font-weight:800;
    display:flex;
    align-items:center;
    gap:6px;
}

.live span{
    width:6px;
    height:6px;
    background:var(--green);
    border-radius:50%;
    box-shadow:0 0 10px var(--green);
}

.big-number{
    font-size:49px;
    font-weight:800;
    letter-spacing:-3px;
}

.unit{
    font-size:15px;
    color:#829087;
}

.chart{
    height:150px;
    margin-top:20px;
    display:flex;
    align-items:end;
    gap:5px;
}

.bar{
    flex:1;
    border-radius:6px 6px 2px 2px;
    background:linear-gradient(to top,var(--green),rgba(156,255,56,.12));
    opacity:.8;
    animation:bars 2s ease-in-out infinite alternate;
}

@keyframes bars{
    from{opacity:.55}
    to{opacity:1}
}

.panel-bottom{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:10px;
    margin-top:18px;
}

.mini{
    padding:13px;
    border:1px solid rgba(255,255,255,.06);
    background:rgba(255,255,255,.025);
    border-radius:13px;
}

.mini small{
    display:block;
    color:#718078;
    font-size:9px;
    margin-bottom:6px;
}

.mini strong{
    font-size:15px;
}

/* SECTION */

section{
    padding:115px 0;
}

.section-head{
    max-width:700px;
    margin-bottom:50px;
}

.eyebrow{
    color:var(--green);
    font-size:11px;
    font-weight:800;
    letter-spacing:2px;
    text-transform:uppercase;
    margin-bottom:14px;
}

h2{
    font-size:clamp(34px,5vw,56px);
    letter-spacing:-3px;
    line-height:1.05;
}

.section-head p{
    margin-top:17px;
    color:#849088;
    line-height:1.7;
}

/* FEATURES */

.features{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:15px;
}

.card{
    padding:28px;
    border:1px solid rgba(255,255,255,.07);
    background:rgba(255,255,255,.025);
    border-radius:22px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-6px);
    border-color:var(--border);
    background:rgba(156,255,56,.035);
}

.icon{
    width:43px;
    height:43px;
    border-radius:13px;
    display:grid;
    place-items:center;
    background:rgba(156,255,56,.08);
    color:var(--green);
    font-size:20px;
    margin-bottom:23px;
}

.card h3{
    font-size:18px;
    margin-bottom:10px;
}

.card p{
    color:#7f8b84;
    line-height:1.7;
    font-size:13px;
}

/* DASHBOARD */

.dashboard-wrap{
    border:1px solid rgba(255,255,255,.08);
    border-radius:27px;
    overflow:hidden;
    background:#080c0a;
    box-shadow:0 40px 120px rgba(0,0,0,.35);
}

.dashboard-head{
    padding:19px 22px;
    border-bottom:1px solid rgba(255,255,255,.06);
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.dash-logo{
    font-weight:800;
    font-size:14px;
}

.status{
    font-size:10px;
    color:var(--green);
    padding:7px 10px;
    border-radius:20px;
    background:rgba(156,255,56,.07);
}

.dashboard{
    display:grid;
    grid-template-columns:190px 1fr;
    min-height:480px;
}

.sidebar{
    border-right:1px solid rgba(255,255,255,.06);
    padding:20px 12px;
}

.side-item{
    padding:12px;
    color:#69756e;
    border-radius:9px;
    font-size:11px;
    margin-bottom:4px;
}

.side-item.active{
    background:rgba(156,255,56,.08);
    color:var(--green);
}

.dash-content{
    padding:23px;
}

.kpis{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:11px;
}

.kpi{
    padding:17px;
    border:1px solid rgba(255,255,255,.06);
    background:#0c110e;
    border-radius:15px;
}

.kpi label{
    color:#66736b;
    font-size:9px;
}

.kpi strong{
    display:block;
    margin-top:8px;
    font-size:20px;
}

.up{
    color:var(--green);
    font-size:9px;
}

.dashboard-main{
    display:grid;
    grid-template-columns:1.4fr .8fr;
    gap:13px;
    margin-top:13px;
}

.chart-box,
.ai-box{
    border:1px solid rgba(255,255,255,.06);
    background:#0c110e;
    border-radius:16px;
    padding:18px;
}

.box-title{
    font-size:11px;
    font-weight:700;
    margin-bottom:15px;
}

.line-chart{
    height:190px;
    position:relative;
    overflow:hidden;
}

svg{
    width:100%;
    height:100%;
}

.ai-box{
    background:
    radial-gradient(circle at 90% 10%,rgba(156,255,56,.1),transparent 35%),
    #0c110e;
}

.ai-badge{
    display:inline-block;
    padding:6px 9px;
    background:rgba(156,255,56,.1);
    color:var(--green);
    border-radius:8px;
    font-size:9px;
    font-weight:800;
    margin-bottom:15px;
}

.ai-box h3{
    font-size:17px;
    line-height:1.35;
}

.ai-box p{
    color:#76827b;
    font-size:11px;
    line-height:1.6;
    margin-top:11px;
}

.saving{
    margin-top:20px;
    padding-top:15px;
    border-top:1px solid rgba(255,255,255,.06);
}

.saving strong{
    font-size:25px;
    color:var(--green);
}

.saving small{
    display:block;
    color:#68746d;
    font-size:9px;
}

/* AI */

.ai-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:18px;
}

.ai-card{
    border:1px solid rgba(156,255,56,.12);
    background:
    linear-gradient(140deg,rgba(156,255,56,.06),transparent 55%),
    rgba(255,255,255,.025);
    padding:30px;
    border-radius:23px;
}

.ai-card .number{
    font-size:48px;
    color:var(--green);
    font-weight:900;
    letter-spacing:-3px;
}

.ai-card h3{
    margin-top:14px;
    font-size:20px;
}

.ai-card p{
    margin-top:10px;
    color:#7d8982;
    line-height:1.7;
    font-size:13px;
}

.insights{
    display:flex;
    flex-direction:column;
    gap:10px;
}

.insight{
    padding:17px;
    border:1px solid rgba(255,255,255,.07);
    border-radius:14px;
    background:rgba(255,255,255,.025);
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:20px;
}

.insight strong{
    font-size:12px;
}

.insight span{
    color:var(--green);
    font-size:10px;
    white-space:nowrap;
}

/* SECTORS */

.sectors{
    display:grid;
    grid-template-columns:repeat(6,1fr);
    gap:10px;
}

.sector{
    text-align:center;
    padding:25px 10px;
    border:1px solid rgba(255,255,255,.06);
    border-radius:17px;
    background:rgba(255,255,255,.02);
    transition:.25s;
}

.sector:hover{
    border-color:var(--border);
    transform:translateY(-4px);
}

.sector-icon{
    font-size:27px;
    margin-bottom:12px;
}

.sector span{
    color:#929d96;
    font-size:10px;
    font-weight:700;
}

/* HOW */

.steps{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:12px;
}

.step{
    position:relative;
    padding:27px;
    border-top:1px solid rgba(156,255,56,.2);
}

.step-num{
    color:var(--green);
    font-size:11px;
    font-weight:900;
}

.step h3{
    margin-top:22px;
    font-size:18px;
}

.step p{
    color:#77827c;
    font-size:12px;
    line-height:1.7;
    margin-top:9px;
}

/* CTA */

.cta{
    text-align:center;
    padding:100px 20px;
    border:1px solid var(--border);
    border-radius:30px;
    background:
    radial-gradient(circle at 50% 0%,rgba(156,255,56,.12),transparent 40%),
    rgba(255,255,255,.02);
}

.cta h2{
    max-width:760px;
    margin:auto;
}

.cta p{
    max-width:570px;
    margin:18px auto 30px;
    color:#7e8983;
    line-height:1.7;
}

/* FOOTER */

footer{
    border-top:1px solid rgba(255,255,255,.06);
    padding:35px 0;
    color:#66716b;
    font-size:11px;
}

.footer{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.footer-links{
    display:flex;
    gap:20px;
}

/* MOBILE */

@media(max-width:900px){

    .links{
        display:none;
    }

    .hero{
        padding-top:120px;
    }

    .hero-grid,
    .ai-grid,
    .dashboard-main{
        grid-template-columns:1fr;
    }

    .features{
        grid-template-columns:1fr 1fr;
    }

    .sectors{
        grid-template-columns:repeat(3,1fr);
    }

    .steps{
        grid-template-columns:1fr 1fr;
    }

    .dashboard{
        grid-template-columns:1fr;
    }

    .sidebar{
        display:none;
    }

    .kpis{
        grid-template-columns:1fr 1fr;
    }
}

@media(max-width:600px){

    h1{
        letter-spacing:-3px;
    }

    section{
        padding:80px 0;
    }

    .features{
        grid-template-columns:1fr;
    }

    .sectors{
        grid-template-columns:repeat(2,1fr);
    }

    .steps{
        grid-template-columns:1fr;
    }

    .panel-bottom{
        grid-template-columns:1fr;
    }

    .footer{
        flex-direction:column;
        gap:18px;
    }

    .dashboard{
        min-height:400px;
    }

    .dash-content{
        padding:12px;
    }
}
</style>
</head>

<body>

<div class="bg"></div>
<div class="grid"></div>

<!-- NAVBAR -->

<nav>
<div class="container nav">

<a href="#" class="logo">
<div class="logo-mark">A</div>
AURA AI
</a>

<div class="links">
<a href="#platform">Platform</a>
<a href="#dashboard">Dashboard</a>
<a href="#ai">AURA Intelligence</a>
<a href="#sectors">Sektörler</a>
</div>

<a href="#contact" class="nav-btn">AURA'yı Keşfet →</a>

</div>
</nav>


<!-- HERO -->

<header class="hero">
<div class="container hero-grid">

<div>

<div class="badge">
<span class="dot"></span>
ENERGY INTELLIGENCE PLATFORM
</div>

<h1>
Enerjinin nereye gittiğini
<span class="gradient">AURA AI</span> söyler.
</h1>

<p>
AURA AI; enerji tüketimini izler, verileri analiz eder,
anormal tüketimleri algılar ve daha verimli kullanım için
akıllı öneriler üretir.
</p>

<div class="buttons">
<a class="primary" href="#dashboard">
Dashboard'u Keşfet →
</a>

<a class="secondary" href="#platform">
Nasıl Çalışıyor?
</a>
</div>

</div>


<div class="hero-panel">

<div class="panel-top">
<div class="panel-title">AURA LIVE / ENERGY CORE</div>

<div class="live">
<span></span>
LIVE MONITORING
</div>
</div>

<div class="big-number">
4.82 <span class="unit">kW</span>
</div>

<div class="chart">

<div class="bar" style="height:35%"></div>
<div class="bar" style="height:50%"></div>
<div class="bar" style="height:42%"></div>
<div class="bar" style="height:70%"></div>
<div class="bar" style="height:55%"></div>
<div class="bar" style="height:83%"></div>
<div class="bar" style="height:62%"></div>
<div class="bar" style="height:91%"></div>
<div class="bar" style="height:70%"></div>
<div class="bar" style="height:48%"></div>
<div class="bar" style="height:63%"></div>
<div class="bar" style="height:75%"></div>

</div>

<div class="panel-bottom">

<div class="mini">
<small>BUGÜN</small>
<strong>38.7 kWh</strong>
</div>

<div class="mini">
<small>TAHMİN</small>
<strong>₺214</strong>
</div>

<div class="mini">
<small>VERİMLİLİK</small>
<strong style="color:#9cff38">87%</strong>
</div>

</div>

</div>

</div>
</header>


<!-- PLATFORM -->

<section id="platform">

<div class="container">

<div class="section-head">

<div class="eyebrow">AURA PLATFORM</div>

<h2>
Sadece veriyi göstermez.
<strong>Veriyi anlamlandırır.</strong>
</h2>

<p>
Binlerce ölçümü anlaşılabilir bilgiler haline getirerek
enerji yönetimini daha kolay ve daha akıllı hale getirir.
</p>

</div>


<div class="features">

<div class="card">
<div class="icon">⚡</div>
<h3>Gerçek Zamanlı İzleme</h3>
<p>
Enerji kullanımını anlık olarak takip edin.
Tüketimdeki değişimleri tek ekranda görün.
</p>
</div>

<div class="card">
<div class="icon">◈</div>
<h3>AI Anomali Algılama</h3>
<p>
AURA AI alışılmış tüketim davranışlarını öğrenir
ve sıra dışı durumları belirler.
</p>
</div>

<div class="card">
<div class="icon">↗</div>
<h3>Tasarruf Önerileri</h3>
<p>
Tüketim verilerinden hareketle hangi alanlarda
verimlilik fırsatı olduğunu gösterir.
</p>
</div>

<div class="card">
<div class="icon">◉</div>
<h3>Enerji Skoru</h3>
<p>
Sistemin genel verimliliğini anlaşılır bir skor
üzerinden takip edin.
</p>
</div>

<div class="card">
<div class="icon">⌁</div>
<h3>Tahminleme</h3>
<p>
Geçmiş tüketim eğilimlerinden gelecekteki
kullanım için tahminler oluşturun.
</p>
</div>

<div class="card">
<div class="icon">▣</div>
<h3>Tek Merkez</h3>
<p>
Farklı alanlardan gelen enerji verilerini tek
bir merkezi panelde birleştirin.
</p>
</div>

</div>

</div>
</section>


<!-- DASHBOARD -->

<section id="dashboard">

<div class="container">

<div class="section-head">

<div class="eyebrow">AURA COMMAND CENTER</div>

<h2>
Enerji sisteminizin
<strong>kontrol merkezi.</strong>
</h2>

<p>
Karmaşık enerji verilerini sade, hızlı ve anlaşılır
bir arayüzde görüntüleyin.
</p>

</div>


<div class="dashboard-wrap">

<div class="dashboard-head">

<div class="dash-logo">
AURA AI / COMMAND CENTER
</div>

<div class="status">
● SYSTEM ONLINE
</div>

</div>


<div class="dashboard">

<aside class="sidebar">

<div class="side-item active">Overview</div>
<div class="side-item">Energy Flow</div>
<div class="side-item">Analytics</div>
<div class="side-item">AI Insights</div>
<div class="side-item">Devices</div>
<div class="side-item">Reports</div>
<div class="side-item">Settings</div>

</aside>


<main class="dash-content">

<div class="kpis">

<div class="kpi">
<label>ANLIK TÜKETİM</label>
<strong>4.82 kW</strong>
<span class="up">↓ %8.4</span>
</div>

<div class="kpi">
<label>BUGÜN</label>
<strong>38.7 kWh</strong>
<span class="up">↓ %12.1</span>
</div>

<div class="kpi">
<label>TAHMİNİ MALİYET</label>
<strong>₺214</strong>
<span class="up">+₺18</span>
</div>

<div class="kpi">
<label>AURA SCORE</label>
<strong>87/100</strong>
<span class="up">Excellent</span>
</div>

</div>


<div class="dashboard-main">

<div class="chart-box">

<div class="box-title">
Enerji Tüketimi / Son 24 Saat
</div>

<div class="line-chart">

<svg viewBox="0 0 600 190" preserveAspectRatio="none">

<defs>

<linearGradient id="area" x1="0" y1="0" x2="0" y2="1">

<stop offset="0%" stop-color="#9cff38" stop-opacity=".25"/>
<stop offset="100%" stop-color="#9cff38" stop-opacity="0"/>

</linearGradient>

</defs>

<path
d="M0,145
C35,135 45,110 80,125
C115,140 125,85 160,105
C195,125 215,80 245,95
C280,110 300,55 335,80
C365,105 390,90 420,65
C450,40 470,95 500,72
C530,50 550,75 600,35
L600,190 L0,190 Z"
fill="url(#area)"
/>

<path
d="M0,145
C35,135 45,110 80,125
C115,140 125,85 160,105
C195,125 215,80 245,95
C280,110 300,55 335,80
C365,105 390,90 420,65
C450,40 470,95 500,72
C530,50 550,75 600,35"
fill="none"
stroke="#9cff38"
stroke-width="3"
/>

</svg>

</div>

</div>


<div class="ai-box">

<div class="ai-badge">AURA INTELLIGENCE</div>

<h3>
3 tasarruf fırsatı tespit edildi.
</h3>

<p>
AURA, mevcut tüketim davranışlarını
analiz ederek optimizasyon fırsatlarını
önceliklendiriyor.
</p>

<div class="saving">

<strong>₺428</strong>

<small>
Tahmini aylık tasarruf potansiyeli
</small>

</div>

</div>

</div>

</main>

</div>

</div>

</div>
</section>


<!-- AI -->

<section id="ai">

<div class="container">

<div class="section-head">

<div class="eyebrow">AURA INTELLIGENCE</div>

<h2>
Enerji verisinden
<strong>karar desteğine.</strong>
</h2>

<p>
AURA AI yalnızca “ne oldu?” sorusunu değil,
“neden oldu?” ve “ne yapılabilir?” sorularını da hedefler.
</p>

</div>


<div class="ai-grid">

<div class="ai-card">

<div class="number">03</div>

<h3>
Bugün tespit edilen fırsatlar
</h3>

<p>
AURA'nın analiz motoru, tüketim profilindeki
değişimleri inceleyerek dikkat edilmesi gereken
noktaları öne çıkarır.
</p>

</div>


<div class="insights">

<div class="insight">
<strong>Gece tüketimi normalin üzerinde</strong>
<span>İNCELE →</span>
</div>

<div class="insight">
<strong>HVAC tüketiminde artış algılandı</strong>
<span>ÖNCELİKLİ</span>
</div>

<div class="insight">
<strong>Bekleme tüketimi optimize edilebilir</strong>
<span>FIRSAT</span>
</div>

<div class="insight">
<strong>Bu haftanın verimliliği yükseldi</strong>
<span>+8.2%</span>
</div>

</div>

</div>

</div>
</section>


<!-- SECTORS -->

<section id="sectors">

<div class="container">

<div class="section-head">

<div class="eyebrow">WHERE AURA WORKS</div>

<h2>
Her binanın
<strong>enerji hikâyesi farklıdır.</strong>
</h2>

</div>


<div class="sectors">

<div class="sector">
<div class="sector-icon">🏠</div>
<span>KONUT</span>
</div>

<div class="sector">
<div class="sector-icon">🏫</div>
<span>OKUL</span>
</div>

<div class="sector">
<div class="sector-icon">🏭</div>
<span>FABRİKA</span>
</div>

<div class="sector">
<div class="sector-icon">🏨</div>
<span>OTEL</span>
</div>

<div class="sector">
<div class="sector-icon">🍽️</div>
<span>RESTORAN</span>
</div>

<div class="sector">
<div class="sector-icon">🏢</div>
<span>OFİS</span>
</div>

</div>

</div>
</section>


<!-- HOW -->

<section>

<div class="container">

<div class="section-head">

<div class="eyebrow">HOW AURA WORKS</div>

<h2>
Dört adım.
<strong>Daha akıllı enerji.</strong>
</h2>

</div>


<div class="steps">

<div class="step">
<div class="step-num">01 / MEASURE</div>
<h3>Ölç</h3>
<p>
Enerji sisteminden veriler toplanır.
</p>
</div>

<div class="step">
<div class="step-num">02 / ANALYZE</div>
<h3>Analiz Et</h3>
<p>
AURA verileri işler ve tüketim davranışlarını inceler.
</p>
</div>

<div class="step">
<div class="step-num">03 / DETECT</div>
<h3>Tespit Et</h3>
<p>
Anormal tüketimler ve verimlilik fırsatları belirlenir.
</p>
</div>

<div class="step">
<div class="step-num">04 / OPTIMIZE</div>
<h3>Optimize Et</h3>
<p>
Kullanıcıya anlaşılır aksiyon önerileri sunulur.
</p>
</div>

</div>

</div>
</section>


<!-- CTA -->

<section id="contact">

<div class="container">

<div class="cta">

<div class="eyebrow">THE FUTURE OF ENERGY</div>

<h2>
Enerjiyi sadece tüketme.
<strong>Onu anla.</strong>
</h2>

<p>
AURA AI ile enerji verilerini daha anlaşılır,
daha ölçülebilir ve daha akıllı bir sisteme dönüştür.
</p>

<a href="#dashboard" class="primary">
AURA AI'yi Keşfet →
</a>

</div>

</div>
</section>


<!-- FOOTER -->

<footer>

<div class="container footer">

<div>
© 2026 AURA AI — Energy Intelligence
</div>

<div class="footer-links">
<a href="#platform">Platform</a>
<a href="#dashboard">Dashboard</a>
<a href="#ai">AI</a>
<a href="#contact">İletişim</a>
</div>

</div>

</footer>


<script>

/* LIVE ENERGY NUMBER */

const number = document.querySelector(".big-number");

setInterval(() => {

    const value = (4.5 + Math.random() * .7).toFixed(2);

    number.innerHTML =
    value + ' <span class="unit">kW</span>';

},2500);


/* SCROLL REVEAL */

const cards = document.querySelectorAll(
    ".card,.ai-card,.sector,.step,.dashboard-wrap"
);

const observer = new IntersectionObserver(
(entries)=>{
    entries.forEach(entry=>{
        if(entry.isIntersecting){
            entry.target.style.opacity="1";
            entry.target.style.transform="translateY(0)";
        }
    });
},
{threshold:.12}
);

cards.forEach(card=>{
    card.style.opacity="0";
    card.style.transform="translateY(25px)";
    card.style.transition="opacity .7s ease, transform .7s ease";
    observer.observe(card);
});


/* SMOOTH BUTTON FEEDBACK */

document.querySelectorAll(".primary").forEach(btn=>{

    btn.addEventListener("click",()=>{
        btn.style.transform="scale(.97)";

        setTimeout(()=>{
            btn.style.transform="";
        },120);

    });

});

</script>

</body>
</html>
