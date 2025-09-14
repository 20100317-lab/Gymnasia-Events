<!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Gymnasia Events — ბავშვთა დღეები & კორპორატიული ღონისძიებები</title>
  <meta name="description" content="Gymnasia Events • ბავშვთა დაუვიწყარი დღესასწაულები, მასტერკლასები, შოუები, დეკორაციები და სპეციალური პაკეტები. Book now!" />
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" rel="stylesheet" />
  <style>
    :root{--brand:#6C5CE7;--accent:#00D1B2;--ink:#111827}
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:Inter,system-ui,Segoe UI,Roboto,Helvetica,Arial,sans-serif;background:linear-gradient(135deg,#667eea 0%,#764ba2 100%);color:#111827;overflow-x:hidden}
    a{color:inherit;text-decoration:none}
    /* Header */
    .header{position:sticky;top:0;z-index:50;background:rgba(255,255,255,.9);backdrop-filter:blur(10px);border-bottom:1px solid rgba(0,0,0,.06)}
    .nav{max-width:1200px;margin:0 auto;display:flex;align-items:center;justify-content:space-between;padding:12px 20px}
    .logo{font-weight:800;font-size:20px;letter-spacing:.2px}
    .logo span{background:linear-gradient(45deg,#ff6b6b,#4ecdc4);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent}
    .nav-links{display:flex;gap:20px}
    .nav-links a{font-weight:600;opacity:.85}
    .lang{display:flex;gap:8px}
    .btn{padding:8px 14px;border-radius:999px;border:1px solid rgba(0,0,0,.1);background:#fff;font-weight:700;cursor:pointer}
    .btn.primary{background:var(--brand);color:#fff;border-color:transparent}
    /* Sections */
    .section{padding:80px 20px}
    .container{max-width:1200px;margin:0 auto}
    .title{font-size:40px;line-height:1.1;margin-bottom:28px;background:linear-gradient(45deg,#fff,#e6e6ff);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent;text-align:center}
    /* Hero */
    .hero{min-height:88vh;display:grid;place-items:center;position:relative}
    .hero-card{background:rgba(255,255,255,.12);backdrop-filter:blur(10px);border:1px solid rgba(255,255,255,.3);border-radius:22px;padding:36px;text-align:center;color:#fff;max-width:900px}
    .hero h1{font-size:56px;line-height:1.05;margin-bottom:10px}
    .hero p{font-size:18px;opacity:.92;margin-bottom:22px}
    .cta{display:flex;gap:12px;justify-content:center;flex-wrap:wrap}
    .chip{display:inline-flex;align-items:center;gap:8px;border-radius:999px;background:rgba(255,255,255,.15);border:1px solid rgba(255,255,255,.25);padding:8px 12px;color:#fff;margin-top:10px}
    /* Cards Grid */
    .grid{display:grid;gap:20px}
    .grid.cols-3{grid-template-columns:repeat(auto-fit,minmax(280px,1fr))}
    .card{background:#fff;border-radius:18px;border:1px solid rgba(0,0,0,.06);box-shadow:0 10px 30px rgba(0,0,0,.08);padding:18px}
    .card h3{font-size:18px;margin-bottom:8px}
    .item{display:flex;align-items:center;justify-content:space-between;padding:10px 0;border-bottom:1px dashed #eef}
    .item:last-child{border-bottom:none}
    .price{font-weight:800;background:linear-gradient(45deg,#ff6b6b,#4ecdc4);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent}
    .price.free{background:linear-gradient(45deg,#22c55e,#16a34a);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent}
    /* Packages */
    .packages{background:linear-gradient(135deg,#667eea 0%,#764ba2 100%)}
    .pkg{background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.3);backdrop-filter:blur(8px);border-radius:18px;padding:22px;color:#fff;transition:.2s transform}
    .pkg:hover{transform:translateY(-6px)}
    .pkg h3{font-size:20px;margin-bottom:6px}
    .pkg .now{font-size:34px;font-weight:900;color:#4ecdc4}
    .pkg .was{opacity:.65;text-decoration:line-through}
    .pkg ul{margin-top:10px;list-style:none;display:grid;gap:8px}
    .pkg li{display:flex;gap:10px;align-items:center}
    /* Contact */
    .contact{background:linear-gradient(135deg,#f093fb 0%,#f5576c 100%);color:#fff;text-align:center}
    .contact-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px;margin-top:20px}
    .contact-card{background:rgba(255,255,255,.15);border:1px solid rgba(255,255,255,.3);border-radius:14px;padding:16px}
    /* Footer */
    footer{background:#0f172a;color:#cbd5e1;padding:18px;text-align:center}
    /* Responsive */
    @media (max-width:720px){.hero h1{font-size:36px}.title{font-size:32px}}
  </style>
</head>
<body>
  <!-- Header -->
  <header class="header" aria-label="Main Navigation">
    <div class="nav">
      <div class="logo"><span>Gymnasia</span> Events · <small>Level Up, Growing Up</small></div>
      <nav class="nav-links" aria-label="Sections">
        <a href="#services" data-i18n="nav_services">სერვისები</a>
        <a href="#packages" data-i18n="nav_packages">პაკეტები</a>
        <a href="#contact" data-i18n="nav_contact">კონტაქტი</a>
      </nav>
      <div class="lang">
        <button class="btn" id="btn-ka">KA</button>
        <button class="btn" id="btn-en">EN</button>
        <a href="#contact" class="btn primary" data-i18n="nav_cta">დაჯავშნა</a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section class="section hero" id="home">
    <div class="hero-card" role="banner">
      <h1 data-i18n="hero_title">ბავშვთა დაუვიწყარი დღესასწაულები, ვაუ-ეფექტით</h1>
      <p data-i18n="hero_sub">მასტერკლასები, შოუები, დეკორაციები და სპეციალური პაკეტები — ერთ სივრცეში.</p>
      <div class="cta">
        <a class="btn primary" href="#packages" data-i18n="hero_cta1">ნახე პაკეტები</a>
        <a class="btn" href="https://wa.me/995598901990" target="_blank" rel="noopener" data-i18n="hero_cta2"><i class="fa-brands fa-whatsapp"></i> დაწერე WhatsApp-ზე</a>
      </div>
      <div class="chip"><i class="fa-solid fa-location-dot"></i> Tbilisi, Georgia</div>
    </div>
  </section>

  <!-- Services -->
  <section class="section" id="services">
    <div class="container">
      <h2 class="title" data-i18n="srv_title">სერვისები</h2>
      <div class="grid cols-3">
        <!-- Workshops -->
        <div class="card">
          <h3 data-i18n="srv_workshops">მასტერკლასები / Workshops</h3>
          <div class="item"><span>ორცხობილების მოხატვა / Cookie Decorating</span><span class="price free">0 ₾</span></div>
          <div class="item"><span>ბუშტების მასტერკლასი / Balloon Workshop</span><span class="price">200–350 ₾</span></div>
          <div class="item"><span>კოკტეილების მასტერკლასი / Cocktail Workshop</span><span class="price free">0 ₾</span></div>
          <div class="item"><span>ხელოვნების მასტერკლასი / Art Workshop</span><span class="price">400 ₾</span></div>
          <div class="item"><span>კულინარიული / Cooking Workshop</span><span class="price free">0 ₾</span></div>
          <div class="item"><span>სლაიმის ვორქშოფი / Slime Party</span><span class="price">500 ₾</span></div>
        </div>
        <!-- Shows -->
        <div class="card">
          <h3 data-i18n="srv_shows">შოუები / Shows</h3>
          <div class="item"><span>მშრალი ყინულის შოუ / Dry Ice Show</span><span class="price">500 ₾</span></div>
          <div class="item"><span>აზოტის შოუ / Nitrogen Show</span><span class="price">600 ₾</span></div>
          <div class="item"><span>ტესლას შოუ / Tesla Show</span><span class="price">800 ₾</span></div>
          <div class="item"><span>ცეცხლის შოუ / Fire Show</span><span class="price">500 ₾</span></div>
          <div class="item"><span>ლაზერ შოუ / Laser Show</span><span class="price">900 ₾</span></div>
          <div class="item"><span>LED შოუ / LED Show</span><span class="price">800 ₾</span></div>
        </div>
        <!-- Tech & Decor -->
        <div class="card">
          <h3 data-i18n="srv_tech">ტექნიკა & დეკორი / Tech & Decor</h3>
          <div class="item"><span>DJ</span><span class="price">500–800 ₾</span></div>
          <div class="item"><span>ფოტო / ვიდეო / Photography or Videography</span><span class="price">500 ₾ / 400 ₾</span></div>
          <div class="item"><span>თოვლის მანქანა / Snow Machine</span><span class="price">600 ₾</span></div>
          <div class="item"><span>კარაოკე სცენა / Karaoke Stage (35min)</span><span class="price">600 ₾</span></div>
          <div class="item"><span>360° ფოტოგადაღება / 360° Booth</span><span class="price free">0 ₾</span></div>
          <div class="item"><span>ბუშტების რკალი / Balloon Arch</span><span class="price">300 ₾</span></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Packages -->
  <section class="section packages" id="packages">
    <div class="container">
      <h2 class="title" style="-webkit-text-fill-color:initial;color:#fff" data-i18n="pkg_title">სპეციალური პაკეტები / Special Packages</h2>
      <div class="grid cols-3">
        <div class="pkg" aria-label="Package 1">
          <h3>🎁 <span data-i18n="p1">პაკეტი 1 / Package 1</span></h3>
          <div class="now">500 ₾</div>
          <div class="was">1000 ₾</div>
          <ul>
            <li>✨ <span data-i18n="p1_i1">კონფეტის წვიმა / Confetti Rain</span></li>
            <li>📸 <span data-i18n="p1_i2">ფოტოზონა / Photo Zone</span></li>
            <li>🏆 <span data-i18n="p1_i3">დაჯილდოება თასით/ვარსკვლავით / Award with Trophy/Star</span></li>
            <li>🎈 <span data-i18n="p1_i4">ჰელიუმის ბუშტები – 10 / 10 Helium Balloons</span></li>
          </ul>
        </div>
        <div class="pkg" aria-label="Package 2">
          <h3>🎊 <span data-i18n="p2">პაკეტი 2 / Package 2</span></h3>
          <div class="now">900 ₾</div>
          <div class="was">1800 ₾</div>
          <ul>
            <li>📸 <span data-i18n="p2_i1">ფოტო ან ვიდეო / Photo or Video</span></li>
            <li>⭐ <span data-i18n="p2_i2">ვარსკვლავის გახსნა ან თასით დაჯილდოება / Star Opening or Trophy Award</span></li>
            <li>✨ <span data-i18n="p2_i3">კონფეტის წვიმა / Confetti Rain</span></li>
            <li>🎞️ <span data-i18n="p2_i4">ფოტოზონა / Photo Zone</span></li>
            <li>🎈 <span data-i18n="p2_i5">ჰელიუმის ბუშტები – 20 / 20 Helium Balloons</span></li>
            <li>🎓 <span data-i18n="p2_i6">სასურველი მასტერკლასი / Preferred Workshop</span></li>
          </ul>
        </div>
        <div class="pkg" aria-label="Package 3">
          <h3>🎈 <span data-i18n="p3">პაკეტი 3 / Package 3</span></h3>
          <div class="now">1200 ₾</div>
          <div class="was">2400 ₾</div>
          <ul>
            <li>📸 <span data-i18n="p3_i1">ფოტო ან ვიდეო / Photo or Video</span></li>
            <li>⭐ <span data-i18n="p3_i2">ვარსკვლავი ან თასი / Star or Trophy Award</span></li>
            <li>✨ <span data-i18n="p3_i3">კონფეტის წვიმა / Confetti Rain</span></li>
            <li>🎞️ <span data-i18n="p3_i4">ფოტოზონა / Photo Zone</span></li>
            <li>🎈 <span data-i18n="p3_i5">ჰელიუმის ბუშტები – 30 / 30 Helium Balloons</span></li>
            <li>🎉 <span data-i18n="p3_i6">პინიატა / Piñata</span></li>
            <li>🍿 <span data-i18n="p3_i7">პოპკორნი ან ბამბის ნაყინი / Popcorn or Cotton Candy</span></li>
          </ul>
        </div>
        <div class="pkg" aria-label="Package 4">
          <h3>🎪 <span data-i18n="p4">პაკეტი 4 / Package 4 (VIP)</span></h3>
          <div class="now">1500 ₾</div>
          <div class="was">3000 ₾</div>
          <ul>
            <li>📸 <span data-i18n="p4_i1">ფოტო ან ვიდეო / Photo or Video</span></li>
            <li>🏅 <span data-i18n="p4_i2">ვარსკვლავი, თასი ან მედალი / Star, Trophy or Medal</span></li>
            <li>✨ <span data-i18n="p4_i3">კონფეტის წვიმა / Confetti Rain</span></li>
            <li>🎞️ <span data-i18n="p4_i4">ფოტოზონა / Photo Zone</span></li>
            <li>🎈 <span data-i18n="p4_i5">ჰელიუმის ბუშტები – 30 / 30 Helium Balloons</span></li>
            <li>🎉 <span data-i18n="p4_i6">პინიატა / Piñata</span></li>
            <li>🎧 <span data-i18n="p4_i7">დამატებითი სერვისი (სახის მოხატვა, DJ) / Extra Service (Face Painting, DJ)</span></li>
            <li>🧪 <span data-i18n="p4_i8">ან შოუ: მშრალი ყინული, აზოტი, ტესლა / Or Show: Dry Ice, Nitrogen, Tesla</span></li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section class="section contact" id="contact">
    <div class="container">
      <h2 class="title" style="-webkit-text-fill-color:initial;color:#fff" data-i18n="contact_title">დაგვიკავშირდით / Contact Us</h2>
      <p data-i18n="contact_sub">მოგწერეთ WhatsApp-ზე ან დაგვირეკეთ — ადგილები სწრაფად ივსება.</p>
      <div class="contact-grid">
        <div class="contact-card"><i class="fa-solid fa-phone"></i><div>+995 598 90 19 90</div></div>
        <div class="contact-card"><i class="fa-solid fa-envelope"></i><div>info@gymnasia.com</div></div>
        <a class="contact-card" href="https://wa.me/995598901990" target="_blank" rel="noopener"><i class="fa-brands fa-whatsapp"></i><div>WhatsApp</div></a>
        <div class="contact-card"><i class="fa-brands fa-instagram"></i><div>@gymnasia_events</div></div>
      </div>
    </div>
  </section>

  <footer>© <span id="y"></span> Gymnasia Events. All rights reserved.</footer>

  <script>
    // Simple KA/EN i18n map
    const dict = {
      en: {
        nav_services: 'Services', nav_packages: 'Packages', nav_contact: 'Contact', nav_cta:'Book Now',
        hero_title: 'Unforgettable Kids’ Parties with WOW Effect',
        hero_sub: 'Workshops, shows, decorations and special packages — all in one place.',
        hero_cta1: 'See Packages', hero_cta2:'Message on WhatsApp',
        srv_title:'Services', srv_workshops:'Workshops', srv_shows:'Shows', srv_tech:'Tech & Decor',
        pkg_title:'Special Packages',
        p1:'Package 1', p2:'Package 2', p3:'Package 3', p4:'Package 4 (VIP)',
        p1_i1:'Confetti Rain', p1_i2:'Photo Zone', p1_i3:'Award with Trophy/Star', p1_i4:'10 Helium Balloons',
        p2_i1:'Photo or Video', p2_i2:'Star Opening or Trophy Award', p2_i3:'Confetti Rain', p2_i4:'Photo Zone', p2_i5:'20 Helium Balloons', p2_i6:'Preferred Workshop',
        p3_i1:'Photo or Video', p3_i2:'Star or Trophy Award', p3_i3:'Confetti Rain', p3_i4:'Photo Zone', p3_i5:'30 Helium Balloons', p3_i6:'Piñata', p3_i7:'Popcorn or Cotton Candy',
        p4_i1:'Photo or Video', p4_i2:'Star, Trophy or Medal', p4_i3:'Confetti Rain', p4_i4:'Photo Zone', p4_i5:'30 Helium Balloons', p4_i6:'Piñata', p4_i7:'Extra Service (Face Painting, DJ)', p4_i8:'Or Show: Dry Ice, Nitrogen, Tesla',
        contact_title:'Contact Us', contact_sub:'Write on WhatsApp or call us — slots fill fast.'
      }
    };
    const $ = (q)=>document.querySelectorAll('[data-i18n="'+q+'"]');
    const setLang=(lng)=>{
      Object.keys(dict.en).forEach(k=>{
        const nodes=document.querySelectorAll('[data-i18n="'+k+'"]');
        nodes.forEach(n=> n.textContent = (lng==='en'? dict.en[k] : n.getAttribute('data-i18n-ka')||n.textContent));
      });
      document.documentElement.lang = (lng==='en'?'en':'ka');
    };
    // Store KA text into data attributes once, to allow toggling back from EN
    document.querySelectorAll('[data-i18n]').forEach(n=>{n.setAttribute('data-i18n-ka', n.textContent)});
    document.getElementById('btn-en').addEventListener('click',()=>setLang('en'));
    document.getElementById('btn-ka').addEventListener('click',()=>setLang('ka'));
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
