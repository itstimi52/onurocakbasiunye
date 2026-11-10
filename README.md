<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Onur Ocakbaşı | Ünye</title>
<meta name="description" content="Ünye'nin ocakbaşı lezzet durağı. Adana, Urfa, Çöp Şiş ve daha fazlası. Telefonla sipariş: 324 7070">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;800&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --night:#0c0a09;
  --coal:#1a1715;
  --ash:#26211e;
  --gold:#d4a62a;
  --gold-soft:#f0cf74;
  --ember:#c0281c;
  --white:#fbf7f0;
  --muted:#b8ada0;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:'Poppins',system-ui,sans-serif;background:var(--night);color:var(--white);line-height:1.7;-webkit-font-smoothing:antialiased}
a{color:inherit;text-decoration:none}
img{display:block;max-width:100%}
:focus-visible{outline:2px solid var(--gold);outline-offset:3px}

/* HERO */
.hero{
  position:relative;min-height:100svh;display:flex;align-items:center;justify-content:center;text-align:center;padding:2rem 1.25rem;
  background:
    linear-gradient(180deg,rgba(12,10,9,.72) 0%,rgba(12,10,9,.55) 45%,rgba(12,10,9,.95) 100%),
    url('https://images.unsplash.com/photo-1555939594-58d7cb561ad1?auto=format&fit=crop&w=1800&q=80') center/cover no-repeat,
    radial-gradient(circle at 50% 40%,#5a1a10 0%,var(--night) 70%);
  background-color:var(--night);
}
.hero::after{content:"";position:absolute;left:0;right:0;bottom:0;height:3px;background:linear-gradient(90deg,transparent,var(--ember),var(--gold),var(--ember),transparent)}
.hero-inner{max-width:860px;animation:rise 1.1s ease both}
@keyframes rise{from{opacity:0;transform:translateY(26px)}to{opacity:1;transform:none}}
.hero h1{
  font-family:'Playfair Display',serif;font-weight:800;text-transform:uppercase;
  font-size:clamp(2.6rem,9vw,6.2rem);line-height:1.05;letter-spacing:.06em;
  color:var(--gold-soft);text-shadow:0 4px 30px rgba(0,0,0,.6);
}
.hero .rule{width:90px;height:2px;background:var(--ember);margin:1.4rem auto}
.hero p.slogan{font-size:clamp(1.05rem,3.4vw,1.6rem);font-weight:300;letter-spacing:.08em;color:var(--white)}
.hero .town{margin-top:.6rem;font-size:.9rem;color:var(--muted);letter-spacing:.2em}
.btn-row{display:flex;gap:1rem;justify-content:center;flex-wrap:wrap;margin-top:2.4rem}
.btn{
  display:inline-flex;align-items:center;justify-content:center;gap:.6rem;
  padding:1rem 2rem;border-radius:999px;font-weight:600;font-size:1rem;
  min-width:250px;transition:transform .25s,box-shadow .25s,background .25s;
}
.btn-primary{background:linear-gradient(135deg,var(--ember),#8f1a12);color:#fff;box-shadow:0 8px 28px rgba(192,40,28,.4)}
.btn-primary:hover{transform:translateY(-3px);box-shadow:0 12px 36px rgba(192,40,28,.6)}
.btn-ghost{border:1.5px solid var(--gold);color:var(--gold-soft);background:rgba(12,10,9,.4);backdrop-filter:blur(6px)}
.btn-ghost:hover{background:var(--gold);color:var(--night);transform:translateY(-3px)}

/* SECTIONS */
section{padding:5.5rem 1.25rem}
.wrap{max-width:1120px;margin:0 auto}
.title{text-align:center;margin-bottom:3.2rem}
.title h2{font-family:'Playfair Display',serif;font-size:clamp(1.9rem,5vw,3rem);color:var(--gold-soft);font-weight:600}
.title p{color:var(--muted);margin-top:.6rem;max-width:520px;margin-inline:auto}

/* MENU */
.menu{background:var(--coal)}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:1.6rem}
.card{background:var(--ash);border:1px solid rgba(212,166,42,.18);border-radius:18px;overflow:hidden;display:flex;flex-direction:column;transition:transform .3s,border-color .3s}
.card:hover{transform:translateY(-6px);border-color:var(--gold)}
.card .pic{margin:10px 10px 0;height:200px;border-radius:10px;background:linear-gradient(135deg,#4a1710,#1a1715);overflow:hidden}
.card .body{padding:1.4rem 1.4rem 1.6rem;display:flex;flex-direction:column;flex:1}
.card h3{font-family:'Playfair Display',serif;font-size:1.4rem;font-weight:600}
.card p{color:var(--muted);font-size:.92rem;margin:.5rem 0 1.1rem;flex:1}
.price{color:var(--gold-soft);font-weight:600;font-size:1.3rem;border-top:1px dashed rgba(212,166,42,.35);padding-top:.8rem}
.note{text-align:center;color:var(--muted);font-size:.85rem;margin-top:2rem}

/* ORDER */
.order-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:1.2rem;max-width:980px;margin:0 auto}
.brand{
  display:flex;align-items:center;gap:1rem;padding:1.15rem 1.5rem;border-radius:20px;color:#fff;font-weight:600;
  transition:transform .3s,box-shadow .3s;
}
.brand small{display:block;font-weight:400;font-size:.78rem;opacity:.9}
.brand .logo{width:46px;height:46px;border-radius:50%;background:rgba(255,255,255,.95);display:grid;place-items:center;flex-shrink:0}
.brand .logo svg{width:26px;height:26px}
.brand:hover{transform:translateY(-4px)}
.ys{background:#fa0050}.ys:hover{box-shadow:0 0 34px rgba(250,0,80,.65)}
.tg{background:#f27a1a}.tg:hover{box-shadow:0 0 34px rgba(242,122,26,.65)}
.mg{background:#ff6d00;background:linear-gradient(135deg,#ff7a00,#e85d00)}.mg:hover{box-shadow:0 0 34px rgba(255,122,0,.65)}
.gg{background:#fff;color:#202124}.gg:hover{box-shadow:0 0 34px rgba(255,255,255,.5)}

/* FOOTER */
footer{background:#080605;border-top:1px solid rgba(212,166,42,.25);padding:4rem 1.25rem 2rem}
.f-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:2.2rem;max-width:1120px;margin:0 auto}
footer h4{font-family:'Playfair Display',serif;color:var(--gold-soft);font-size:1.25rem;margin-bottom:.7rem;font-weight:600}
footer p,footer li{color:var(--muted);font-size:.95rem;list-style:none}
footer a:hover{color:var(--gold-soft)}
.copy{text-align:center;margin-top:3rem;padding-top:1.5rem;border-top:1px solid rgba(255,255,255,.07);color:#7d746a;font-size:.8rem}

@media (max-width:560px){.btn{width:100%;min-width:0}section{padding:4rem 1.1rem}}
@media (prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}html{scroll-behavior:auto}}
</style>
</head>
<body>

<header class="hero">
  <div class="hero-inner">
    <h1>Onur Ocakbaşı</h1>
    <div class="rule"></div>
    <p class="slogan">Damakta Yağ Değil, Lezzet Bırakır</p>
    <p class="town">ÜNYE / ORDU</p>
    <div class="btn-row">
      <a class="btn btn-primary" href="tel:+904523247070">&#9742; Telefonla Sipariş (324 7070)</a>
      <a class="btn btn-ghost" href="https://www.google.com/maps/search/?api=1&query=Onur+Ocakba%C5%9F%C4%B1+%C3%9Cnye" target="_blank" rel="noopener">&#128205; Yol Tarifi Al</a>
    </div>
  </div>
</header>

<section class="menu" id="menu">
  <div class="wrap">
    <div class="title">
      <h2>Popüler Lezzetlerimiz</h2>
      <p>Közde, sipariş üzerine pişen ocakbaşı klasiklerimiz.</p>
    </div>
    <div class="grid">
      <article class="card">
        <div class="pic"><img src="https://upload.wikimedia.org/wikipedia/commons/8/8c/Turkish_koftes.jpg" alt="Izgara Köfte" loading="lazy" referrerpolicy="no-referrer" onerror="this.style.display='none'" style="width:100%; height:200px; object-fit:cover; border-radius:10px;"></div>
        <div class="body"><h3>Izgara Köfte</h3><p>Özel baharatlar ve hakiki dana etiyle harmanlanmış, içi sulu mangal köftesi.</p><div class="price">350 ₺</div></div>
      </article>
      <article class="card">
        <div class="pic"><img src="https://cdn.pixabay.com/photo/2022/08/31/12/39/steak-7423232_1280.jpg" alt="Dana Antrikot" loading="lazy" referrerpolicy="no-referrer" onerror="this.style.display='none'" style="width:100%; height:200px; object-fit:cover; border-radius:10px;"></div>
        <div class="body"><h3>Mermer dokulu yumuşacık dana etinin ocakbaşı ateşinde lokum kıvamında pişmiş hali.</p><div class="price">350 ₺</div></div>
      </article>
      <article class="card">
        <div class="pic"><img src="https://images.pexels.com/photos/8051852/pexels-photo-8051852.jpeg" alt="Tavuk Prizola" loading="lazy" referrerpolicy="no-referrer" onerror="this.style.display='none'" style="width:100%; height:200px; object-fit:cover; border-radius:10px;"></div>
        <div class="body"><h3>Tavuk Prizola</h3><p>Özel marinasyonla dinlendirilmiş, dışı çıtır içi yumuşacık tavuk pirzola.</p><div class="price">290 ₺</div></div>
      </article>
      <article class="card">
        <div class="pic"><img src="https://images.pexels.com/photos/17205227/pexels-photo-17205227.jpeg" alt="Izgara Dana Lokum" loading="lazy" referrerpolicy="no-referrer" onerror="this.style.display='none'" style="width:100%; height:200px; object-fit:cover; border-radius:10px;"></div>
        <div class="body"><h3>Izgara Dana Lokum</h3><p>Sıfır yağ, sıfır sinir; ocakbaşının en elit ve en yumuşak spesiyal eti.</p><div class="price">350 ₺</div></div>
      </article>
    </div>
    <p class="note">Fiyatlar örnek olup güncel menü için bizi arayabilirsiniz.</p>
  </div>
</section>

<section id="siparis">
  <div class="wrap">
    <div class="title">
      <h2>Online Sipariş ve Yorumlar</h2>
      <p>Sevdiğiniz uygulamadan sipariş verin, deneyiminizi bizimle paylaşın.</p>
    </div>
    <div class="order-grid">
      <a class="brand ys" href="https://www.yemeksepeti.com" target="_blank" rel="noopener">
        <span class="logo"><svg viewBox="0 0 24 24"><path fill="#fa0050" d="M7 2v8a3 3 0 0 0 2 2.8V22h2V12.8A3 3 0 0 0 13 10V2h-1.5v6h-1V2h-1.5v6h-1V2H7zm9 0c-1.7 1.2-3 3.7-3 6.5 0 2 1 3.3 2 3.8V22h2V2z"/></svg></span>
        <span>Yemeksepeti<small>Sipariş ver</small></span>
      </a>
      <a class="brand tg" href="https://www.trendyol.com/go" target="_blank" rel="noopener">
        <span class="logo"><svg viewBox="0 0 24 24"><path fill="#f27a1a" d="M13 2 4 14h6l-1 8 9-12h-6z"/></svg></span>
        <span>Trendyol Go<small>Sipariş ver</small></span>
      </a>
      <a class="brand mg" href="https://www.migros.com.tr/yemek" target="_blank" rel="noopener">
        <span class="logo"><svg viewBox="0 0 24 24"><path fill="#ff7a00" d="M3 4h2.5l.6 3H21l-2 8H8L5.6 6H3zM9 18a1.6 1.6 0 1 0 0 3.2A1.6 1.6 0 0 0 9 18zm8 0a1.6 1.6 0 1 0 0 3.2 1.6 1.6 0 0 0 0-3.2z"/></svg></span>
        <span>Migros Yemek<small>Sipariş ver</small></span>
      </a>
      <a class="brand gg" href="https://www.google.com/maps/search/?api=1&query=Onur+Ocakba%C5%9F%C4%B1+%C3%9Cnye" target="_blank" rel="noopener">
        <span class="logo" style="box-shadow:inset 0 0 0 1.5px #e3e3e3"><svg viewBox="0 0 24 24"><path fill="#4285F4" d="M22 12.2c0-.7-.1-1.3-.2-1.9H12v3.6h5.6a4.8 4.8 0 0 1-2.1 3.1v2.6h3.4c2-1.8 3.1-4.5 3.1-7.4z"/><path fill="#34A853" d="M12 22.5c2.8 0 5.2-.9 6.9-2.5l-3.4-2.6c-.9.6-2.1 1-3.5 1-2.7 0-5-1.8-5.800-4.300H2.700v2.700A10.500 10.500 0 0 0 12 22.500z"/><path fill="#FBBC05" d="M6.200 14.100a6.300 6.300 0 0 1 0-4.200V7.200H2.700a10.500 10.500 0 0 0 0 9.600z"/><path fill="#EA4335" d="M12 5.800c1.500 0 2.900.5 4 1.600l3-3A10.500 10.500 0 0 0 2.700 7.200l3.500 2.700C7 7.500 9.300 5.800 12 5.800z"/></svg></span>
        <span>Google Yorumlar<small>Yorum yap, puan ver</small></span>
      </a>
    </div>
  </div>
</section>

<footer>
  <div class="f-grid">
    <div>
      <h4>Onur Ocakbaşı</h4>
      <p>Damakta Yağ Değil, Lezzet Bırakır.</p>
    </div>
    <div>
      <h4>Adres</h4>
      <p>Ünye / Ordu<br><a href="https://www.google.com/maps/search/?api=1&query=Onur+Ocakba%C5%9F%C4%B1+%C3%9Cnye" target="_blank" rel="noopener">Haritada göster</a></p>
    </div>
    <div>
      <h4>Telefon</h4>
      <p><a href="tel:+904523247070">(0452) 324 70 70</a></p>
    </div>
    <div>
      <h4>Çalışma Saatleri</h4>
      <ul><li>Pazartesi - Pazar</li><li>10:00 - 20:30</li></ul>
    </div>
  </div>
  <p class="copy">&copy; 2026 Onur Ocakbaşı. Tüm hakları saklıdır.</p>
</footer>

</body>
</html>
