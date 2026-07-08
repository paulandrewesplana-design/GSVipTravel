[index.html](https://github.com/user-attachments/files/29818934/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GS VIP Travel — Casino VIP Experiences & Luxury Cruises | Gene Stark</title>
<meta name="description" content="Gene Stark, Independent Casino Representative for Caesars Entertainment and luxury cruise lines. Exclusive Casino VIP player experiences on land and at sea. Call 949-293-1661.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,500;0,600;0,700;1,500&family=Source+Sans+3:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{
  --ivory:#FBFAF7;
  --white:#FFFFFF;
  --ink:#1C2430;
  --slate:#4A5568;
  --navy:#12233A;
  --gold:#A8862D;
  --gold-light:#C9A94E;
  --gold-wash:#F6F1E4;
  --line:#E7E2D6;
  --radius:18px;
  --shadow:0 6px 24px rgba(18,35,58,.08);
  --shadow-lift:0 14px 40px rgba(18,35,58,.14);
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  font-family:'Source Sans 3',-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;
  font-size:19px;line-height:1.65;color:var(--ink);background:var(--ivory);
  -webkit-font-smoothing:antialiased;
}
h1,h2,h3{font-family:'Playfair Display',Georgia,serif;line-height:1.18;color:var(--ink)}
img{max-width:100%;display:block}
a{color:var(--gold);text-decoration:none}
.wrap{max-width:1120px;margin:0 auto;padding:0 24px}

/* ---------- reveal motion ---------- */
.reveal{opacity:0;transform:translateY(26px);transition:opacity .8s ease,transform .8s ease}
.reveal.in{opacity:1;transform:none}
.reveal.d1{transition-delay:.12s}.reveal.d2{transition-delay:.24s}.reveal.d3{transition-delay:.36s}
@media (prefers-reduced-motion:reduce){
  html{scroll-behavior:auto}
  .reveal{opacity:1;transform:none;transition:none}
  *{animation:none!important;transition:none!important}
}

/* ---------- nav ---------- */
nav{
  position:sticky;top:0;z-index:50;
  background:rgba(251,250,247,.88);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);
  border-bottom:1px solid var(--line);
}
.nav-inner{display:flex;align-items:center;justify-content:space-between;height:72px}
.brand{display:flex;align-items:baseline;gap:10px;font-family:'Playfair Display',serif;font-size:22px;font-weight:700;color:var(--ink)}
.brand .gs{color:var(--gold)}
.nav-links{display:flex;gap:32px;align-items:center}
.nav-links a{color:var(--slate);font-weight:600;font-size:16px;transition:color .25s}
.nav-links a:hover{color:var(--gold)}
.nav-call{
  background:var(--navy);color:#fff!important;padding:11px 22px;border-radius:999px;
  font-weight:700;transition:background .25s,transform .25s;white-space:nowrap;
}
.nav-call:hover{background:var(--gold);transform:translateY(-1px)}
.menu-btn{display:none;background:none;border:none;cursor:pointer;padding:8px}
.menu-btn span{display:block;width:26px;height:3px;background:var(--ink);margin:5px 0;border-radius:2px;transition:.3s}
.mobile-menu{display:none;flex-direction:column;padding:12px 24px 24px;border-top:1px solid var(--line);background:var(--ivory)}
.mobile-menu a{padding:14px 4px;font-size:19px;font-weight:600;color:var(--ink);border-bottom:1px solid var(--line)}
.mobile-menu a:last-child{border-bottom:none}
@media(max-width:880px){
  .nav-links{display:none}
  .menu-btn{display:block}
  .mobile-menu.open{display:flex}
}

/* ---------- hero ---------- */
.hero{
  background:linear-gradient(180deg,var(--navy) 0%,#1B3352 100%);
  color:#fff;text-align:center;position:relative;overflow:hidden;
}
.hero::after{
  content:"";position:absolute;inset:auto 0 -1px 0;height:120px;
  background:linear-gradient(180deg,transparent,rgba(0,0,0,.18));pointer-events:none;
}
.hero .wrap{padding:96px 24px 110px;position:relative;z-index:1}
.hero .eyebrow{
  display:inline-block;letter-spacing:.22em;text-transform:uppercase;font-size:14px;font-weight:700;
  color:var(--gold-light);margin-bottom:22px;
}
.hero h1{color:#fff;font-size:clamp(38px,5.4vw,64px);font-weight:600;max-width:850px;margin:0 auto 24px}
.hero h1 em{font-style:italic;color:var(--gold-light)}
.hero p{font-size:clamp(19px,2.2vw,23px);color:#D7DEE8;max-width:720px;margin:0 auto 42px}
.hero-ctas{display:flex;gap:16px;justify-content:center;flex-wrap:wrap}
.btn{
  display:inline-flex;align-items:center;gap:10px;justify-content:center;
  padding:17px 34px;border-radius:999px;font-size:19px;font-weight:700;
  transition:transform .25s,box-shadow .25s,background .25s;cursor:pointer;border:none;
}
.btn-gold{background:var(--gold);color:#fff}
.btn-gold:hover{background:var(--gold-light);transform:translateY(-2px);box-shadow:0 10px 26px rgba(0,0,0,.25)}
.btn-ghost{background:rgba(255,255,255,.1);color:#fff;border:1.5px solid rgba(255,255,255,.45)}
.btn-ghost:hover{background:rgba(255,255,255,.2);transform:translateY(-2px)}
.hero-badges{display:flex;gap:14px 36px;justify-content:center;flex-wrap:wrap;margin-top:56px;color:#B9C5D4;font-size:16px;font-weight:600}
.hero-badges span{display:flex;align-items:center;gap:9px}
.hero-badges svg{flex:none}

/* ---------- gold divider signature ---------- */
.divider{display:flex;align-items:center;gap:16px;justify-content:center;margin:0 auto 18px;max-width:340px}
.divider::before,.divider::after{content:"";flex:1;height:1px;background:var(--gold);opacity:.5}
.divider .dot{width:7px;height:7px;background:var(--gold);border-radius:50%}

/* ---------- sections ---------- */
section{padding:96px 0}
.section-head{text-align:center;max-width:760px;margin:0 auto 60px}
.section-head .kicker{letter-spacing:.2em;text-transform:uppercase;font-size:14px;font-weight:700;color:var(--gold);display:block;margin-bottom:14px}
.section-head h2{font-size:clamp(30px,4vw,44px);font-weight:600;margin-bottom:18px}
.section-head p{color:var(--slate);font-size:20px}

/* two pillars */
.pillars{display:grid;grid-template-columns:1fr 1fr;gap:28px}
.pillar{
  background:var(--white);border:1px solid var(--line);border-radius:var(--radius);
  padding:48px 42px;box-shadow:var(--shadow);transition:transform .35s ease,box-shadow .35s ease;
  display:flex;flex-direction:column;
}
.pillar:hover{transform:translateY(-6px);box-shadow:var(--shadow-lift)}
.pillar .icon{
  width:64px;height:64px;border-radius:16px;background:var(--gold-wash);
  display:flex;align-items:center;justify-content:center;margin-bottom:26px;
}
.pillar h3{font-size:28px;margin-bottom:14px}
.pillar p{color:var(--slate);margin-bottom:26px;flex:1}
.pillar .tags{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:30px}
.tag{background:var(--gold-wash);color:var(--gold);border:1px solid #E9DFC2;padding:6px 14px;border-radius:999px;font-size:15px;font-weight:700}
.link-arrow{font-weight:700;font-size:18px;color:var(--gold);display:inline-flex;align-items:center;gap:8px;transition:gap .25s}
.link-arrow:hover{gap:13px}
@media(max-width:820px){.pillars{grid-template-columns:1fr}}

/* destinations */
.dest-section{background:var(--white);border-top:1px solid var(--line);border-bottom:1px solid var(--line)}
.dest-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.dest{
  background:var(--ivory);border:1px solid var(--line);border-radius:var(--radius);padding:32px 30px;
  transition:transform .3s,box-shadow .3s,border-color .3s;
}
.dest:hover{transform:translateY(-4px);box-shadow:var(--shadow);border-color:#DCCFA6}
.dest .city{font-size:14px;letter-spacing:.16em;text-transform:uppercase;font-weight:700;color:var(--gold);margin-bottom:8px}
.dest h3{font-size:23px;margin-bottom:10px}
.dest p{color:var(--slate);font-size:17px}
@media(max-width:900px){.dest-grid{grid-template-columns:repeat(2,1fr)}}
@media(max-width:600px){.dest-grid{grid-template-columns:1fr}}

.perks{display:flex;gap:22px;justify-content:center;flex-wrap:wrap;margin-top:52px}
.perk{
  display:flex;align-items:center;gap:12px;background:var(--gold-wash);border:1px solid #E9DFC2;
  border-radius:999px;padding:13px 26px;font-weight:700;color:var(--ink);font-size:17px;
}

/* cruises */
.cruise-section{background:linear-gradient(180deg,var(--ivory),#F3F0E7)}
.cruise-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:22px;margin-bottom:56px}
.cruise{
  background:var(--white);border:1px solid var(--line);border-radius:var(--radius);
  padding:36px 28px;text-align:center;transition:transform .3s,box-shadow .3s;
}
.cruise:hover{transform:translateY(-5px);box-shadow:var(--shadow-lift)}
.cruise .mono{
  font-family:'Playfair Display',serif;font-size:30px;font-weight:700;color:var(--gold);
  width:70px;height:70px;border-radius:50%;background:var(--gold-wash);border:1px solid #E9DFC2;
  display:flex;align-items:center;justify-content:center;margin:0 auto 20px;
}
.cruise h3{font-size:21px;margin-bottom:8px}
.cruise p{color:var(--slate);font-size:16px}
@media(max-width:960px){.cruise-grid{grid-template-columns:repeat(2,1fr)}}
@media(max-width:540px){.cruise-grid{grid-template-columns:1fr}}

.la-banner{
  background:var(--navy);color:#fff;border-radius:var(--radius);padding:46px 48px;
  display:flex;align-items:center;justify-content:space-between;gap:32px;flex-wrap:wrap;
  box-shadow:var(--shadow-lift);
}
.la-banner h3{color:#fff;font-size:27px;margin-bottom:10px}
.la-banner p{color:#C9D3DF;max-width:600px;font-size:18px}
.la-banner .btn{flex:none}

/* about */
.about-grid{display:grid;grid-template-columns:1.05fr .95fr;gap:70px;align-items:center}
.about-grid h2{font-size:clamp(30px,3.6vw,42px);font-weight:600;margin-bottom:24px}
.about-grid .lead{font-size:21px;color:var(--ink);margin-bottom:18px}
.about-grid p{color:var(--slate);margin-bottom:18px}
.sig{font-family:'Playfair Display',serif;font-style:italic;font-size:26px;color:var(--gold);margin-top:8px}
.cred-card{
  background:var(--white);border:1px solid var(--line);border-radius:var(--radius);
  padding:44px 40px;box-shadow:var(--shadow);
}
.cred{display:flex;gap:18px;padding:20px 0;border-bottom:1px solid var(--line);align-items:flex-start}
.cred:last-child{border-bottom:none}
.cred .num{font-family:'Playfair Display',serif;font-size:34px;font-weight:700;color:var(--gold);line-height:1;min-width:86px}
.cred .lbl{font-weight:700;font-size:18px;margin-bottom:3px}
.cred .sub{color:var(--slate);font-size:16px}
@media(max-width:880px){.about-grid{grid-template-columns:1fr;gap:44px}}

/* quote */
.quote{background:var(--navy);text-align:center;padding:88px 0}
.quote blockquote{
  font-family:'Playfair Display',serif;font-style:italic;font-size:clamp(24px,3.4vw,36px);
  color:#fff;max-width:820px;margin:0 auto 22px;line-height:1.4;
}
.quote cite{color:var(--gold-light);font-style:normal;font-weight:700;letter-spacing:.14em;text-transform:uppercase;font-size:15px}

/* travel notes */
.notes{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.note{background:var(--white);border:1px solid var(--line);border-radius:var(--radius);padding:34px 30px;box-shadow:var(--shadow)}
.note h3{font-size:20px;margin-bottom:10px;display:flex;align-items:center;gap:10px}
.note p{color:var(--slate);font-size:17px}
@media(max-width:880px){.notes{grid-template-columns:1fr}}

/* contact */
.contact{background:var(--white);border-top:1px solid var(--line)}
.contact-card{
  max-width:820px;margin:0 auto;text-align:center;background:var(--ivory);
  border:1px solid var(--line);border-radius:24px;padding:64px 48px;box-shadow:var(--shadow);
}
.contact-card h2{font-size:clamp(30px,4vw,42px);margin-bottom:14px}
.contact-card>p{color:var(--slate);font-size:20px;margin-bottom:40px}
.contact-btns{display:flex;gap:16px;justify-content:center;flex-wrap:wrap;margin-bottom:40px}
.btn-navy{background:var(--navy);color:#fff}
.btn-navy:hover{background:#1B3352;transform:translateY(-2px);box-shadow:var(--shadow-lift)}
.btn-outline{background:transparent;color:var(--navy);border:2px solid var(--navy)}
.btn-outline:hover{background:var(--navy);color:#fff;transform:translateY(-2px)}
.contact-lines{color:var(--slate);font-size:18px;line-height:2}
.contact-lines strong{color:var(--ink)}
@media(max-width:560px){.contact-card{padding:44px 24px}.btn{width:100%}}

/* footer */
footer{background:var(--navy);color:#9FAEC0;padding:56px 0 40px;font-size:16px}
.foot-top{display:flex;justify-content:space-between;gap:32px;flex-wrap:wrap;padding-bottom:32px;border-bottom:1px solid rgba(255,255,255,.12);margin-bottom:28px}
.foot-brand{font-family:'Playfair Display',serif;font-size:24px;font-weight:700;color:#fff;margin-bottom:10px}
.foot-brand .gs{color:var(--gold-light)}
footer a{color:#C9D3DF}
footer a:hover{color:var(--gold-light)}
.foot-links{display:flex;flex-direction:column;gap:10px}
.foot-bottom{display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap;font-size:15px}
</style>
</head>
<body>

<nav>
  <div class="wrap nav-inner">
    <a href="#top" class="brand"><span class="gs">GS</span> VIP Travel</a>
    <div class="nav-links">
      <a href="#caesars">Caesars Resorts</a>
      <a href="#cruises">Luxury Cruises</a>
      <a href="#about">About Gene</a>
      <a href="#notes">Travel Notes</a>
      <a href="tel:9492931661" class="nav-call">Call Gene · 949-293-1661</a>
    </div>
    <button class="menu-btn" aria-label="Open menu" onclick="document.getElementById('mm').classList.toggle('open')">
      <span></span><span></span><span></span>
    </button>
  </div>
  <div class="mobile-menu" id="mm">
    <a href="#caesars">Caesars Resorts</a>
    <a href="#cruises">Luxury Cruises</a>
    <a href="#about">About Gene</a>
    <a href="#notes">Travel Notes</a>
    <a href="tel:9492931661"><strong>Call Gene · 949-293-1661</strong></a>
  </div>
</nav>

<header class="hero" id="top">
  <div class="wrap">
    <span class="eyebrow reveal">Independent Casino Representative · Est. Relationships Since 1989</span>
    <h1 class="reveal d1">Casino VIP experiences,<br><em>on land and at sea.</em></h1>
    <p class="reveal d2">Gene Stark personally arranges exclusive Caesars Entertainment resort stays and luxury casino cruises for VIP players — every reservation handled for you, start to finish.</p>
    <div class="hero-ctas reveal d3">
      <a class="btn btn-gold" href="tel:9492931661">📞&nbsp; Call Gene Directly</a>
      <a class="btn btn-ghost" href="#caesars">Explore Destinations</a>
    </div>
    <div class="hero-badges reveal d3">
      <span>✦&nbsp; 35+ Years of VIP Service</span>
      <span>✦&nbsp; Caesars Entertainment Representative</span>
      <span>✦&nbsp; CLIA Member</span>
    </div>
  </div>
</header>

<section id="pillars">
  <div class="wrap">
    <div class="section-head reveal">
      <span class="kicker">Two Ways to Play</span>
      <div class="divider"><span class="dot"></span></div>
      <h2>Your premier connection for VIP travel</h2>
      <p>Whether you're seeking a Casino Resort retreat or an adventure at sea, GS VIP Travel makes every arrangement so your trip is fun, exciting, and completely stress-free.</p>
    </div>
    <div class="pillars">
      <div class="pillar reveal">
        <div class="icon"><svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#A8862D" stroke-width="1.8"><path d="M3 21h18M4 21V8l8-5 8 5v13M9 21v-6h6v6M9 11h.01M15 11h.01"/></svg></div>
        <h3>Caesars Entertainment Resorts</h3>
        <p>Exclusive VIP reservations at Caesars destinations across Nevada, California, and New Orleans — including special events, show tickets, tier credit multipliers, and Seven Stars benefits.</p>
        <div class="tags">
          <span class="tag">Las Vegas</span><span class="tag">Lake Tahoe</span><span class="tag">Reno</span>
          <span class="tag">San Diego</span><span class="tag">New Orleans</span><span class="tag">Laughlin</span>
        </div>
        <a class="link-arrow" href="#caesars">See Caesars destinations →</a>
      </div>
      <div class="pillar reveal d1">
        <div class="icon"><svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#A8862D" stroke-width="1.8"><path d="M2 20c1.5 1 3 1 4.5 0s3-1 4.5 0 3 1 4.5 0 3-1 4.5 0M4 17l-1-5 9-3 9 3-1 5M12 9V4M8 6h8"/></svg></div>
        <h3>Luxury Casino Cruises</h3>
        <p>Full-service "Casino Resorts at Sea" — world-class ships with luxury accommodations, fabulous restaurants and shows, and exciting Vegas-style gaming. Wake up to new scenery every day.</p>
        <div class="tags">
          <span class="tag">MSC Cruises</span><span class="tag">Norwegian</span>
          <span class="tag">Royal Caribbean</span><span class="tag">Celebrity</span>
        </div>
        <a class="link-arrow" href="#cruises">See cruise lines →</a>
      </div>
    </div>
  </div>
</section>

<section id="caesars" class="dest-section">
  <div class="wrap">
    <div class="section-head reveal">
      <span class="kicker">Caesars Entertainment</span>
      <div class="divider"><span class="dot"></span></div>
      <h2>Nevada, California &amp; New Orleans</h2>
      <p>Gene arranges VIP stays, special events, and show reservations at these Caesars destinations. Call to find the property and promotion that suits you best.</p>
    </div>
    <div class="dest-grid">
      <div class="dest reveal"><div class="city">Nevada</div><h3>Las Vegas</h3><p>Special events for VIP guests, headline shows, and the full Las Vegas Strip experience.</p></div>
      <div class="dest reveal d1"><div class="city">Nevada</div><h3>Lake Tahoe</h3><p>Harrah's and Caesars Republic — lakeside gaming with alpine scenery year-round.</p></div>
      <div class="dest reveal d2"><div class="city">Nevada</div><h3>Reno: The Row</h3><p>Downtown Reno's premier connected resort experience for VIP players.</p></div>
      <div class="dest reveal"><div class="city">California</div><h3>San Diego: Harrah's SoCal</h3><p>Resort getaway just outside San Diego — a Southern California favorite.</p></div>
      <div class="dest reveal d1"><div class="city">Louisiana</div><h3>New Orleans</h3><p>Caesars New Orleans — world-class gaming in the heart of the French Quarter's doorstep.</p></div>
      <div class="dest reveal d2"><div class="city">Nevada</div><h3>Laughlin</h3><p>Harrah's and Tropicana on the Colorado River — a relaxed riverside gaming escape.</p></div>
    </div>
    <div class="perks reveal">
      <span class="perk">⭐&nbsp; Seven Stars Benefits</span>
      <span class="perk">🎟️&nbsp; Las Vegas Shows &amp; Events</span>
      <span class="perk">✨&nbsp; Tier Credit Multipliers &amp; Special Promotions</span>
    </div>
  </div>
</section>

<section id="cruises" class="cruise-section">
  <div class="wrap">
    <div class="section-head reveal">
      <span class="kicker">Casino VIP Cruising</span>
      <div class="divider"><span class="dot"></span></div>
      <h2>World-class cruise lines we represent</h2>
      <p>Your gaming action qualifies you for casino perks like comps and discounts at sea. Gene will match you with the casino cruise promotion that best suits your play.</p>
    </div>
    <div class="cruise-grid">
      <div class="cruise reveal"><div class="mono">M</div><h3>MSC Cruises</h3><p>European luxury with the exclusive Yacht Club — a "ship within a ship." Sailings from the US and Europe.</p></div>
      <div class="cruise reveal d1"><div class="mono">N</div><h3>Norwegian</h3><p>Freestyle cruising with worldwide itineraries — including departures from Los Angeles.</p></div>
      <div class="cruise reveal d2"><div class="mono">R</div><h3>Royal Caribbean</h3><p>The world's most innovative ships, with convenient sailings from Los Angeles.</p></div>
      <div class="cruise reveal d3"><div class="mono">C</div><h3>Celebrity</h3><p>Modern luxury at sea with refined dining, service, and elegant casino floors.</p></div>
    </div>
    <div class="la-banner reveal">
      <div>
        <h3>Departing from Los Angeles?</h3>
        <p>Enjoy a fun 3+ night cruise from LA to Mexico round-trip aboard newer world-class ships — luxury accommodations, fabulous restaurants and shows, and exciting Vegas-style gaming.</p>
      </div>
      <a class="btn btn-gold" href="tel:9492931661">Ask Gene About LA Sailings</a>
    </div>
  </div>
</section>

<section id="about">
  <div class="wrap about-grid">
    <div class="reveal">
      <span class="kicker" style="letter-spacing:.2em;text-transform:uppercase;font-size:14px;font-weight:700;color:var(--gold);display:block;margin-bottom:14px">About Gene Stark</span>
      <h2>Casino VIPs benefit by booking through us</h2>
      <p class="lead">Gene Stark has spent more than 35 years providing superior service to Casino VIPs — first at Caesars Entertainment, and now as an Independent Gaming Representative.</p>
      <p>GS VIP Travel specializes in assisting Casino VIPs with reservations and arrangements for fun trips on land and at sea. We're exclusive representatives for Caesars Entertainment and several upscale luxury cruise lines — with more to come.</p>
      <p>We're always delighted to help you book new and exciting destinations where luxury, comfort, and adventure await. Please let us know anytime we can be of assistance.</p>
      <p class="sig">Cheers to fun travel, — Gene</p>
    </div>
    <div class="cred-card reveal d1">
      <div class="cred"><div class="num">35+</div><div><div class="lbl">Years of VIP Service</div><div class="sub">At Caesars Entertainment and as an Independent Representative</div></div></div>
      <div class="cred"><div class="num">NVGB</div><div><div class="lbl">Independent Gaming Representative</div><div class="sub">Registered — Nevada Gaming Board</div></div></div>
      <div class="cred"><div class="num">CLIA</div><div><div class="lbl">Cruise Lines International Association</div><div class="sub">Member in good standing</div></div></div>
      <div class="cred"><div class="num">5</div><div><div class="lbl">Brands Represented</div><div class="sub">Caesars, MSC, Norwegian, Royal Caribbean, Celebrity</div></div></div>
    </div>
  </div>
</section>

<section class="quote">
  <div class="wrap reveal">
    <blockquote>"Guests who take the time to plan the details of their casino vacation are usually the happiest guests."</blockquote>
    <cite>— Gene Stark</cite>
  </div>
</section>

<section id="notes">
  <div class="wrap">
    <div class="section-head reveal">
      <span class="kicker">Travel Notes</span>
      <div class="divider"><span class="dot"></span></div>
      <h2>A few tips before you book</h2>
    </div>
    <div class="notes">
      <div class="note reveal"><h3>🛡️ Protect your trip</h3><p>We recommend purchasing travel insurance to help reimburse you for unforeseen cancellation, medical, or other expenses.</p></div>
      <div class="note reveal d1"><h3>📅 Book ahead</h3><p>To keep the casino comfortable, most cruise lines limit the number of Casino Cruise Offers allowed per sailing — reserve early.</p></div>
      <div class="note reveal d2"><h3>🎰 Play qualifies you</h3><p>Your gaming action earns casino perks like comps and discounts. Call Gene to find the player promotion that best fits your play.</p></div>
    </div>
  </div>
</section>

<section class="contact" id="contact">
  <div class="wrap">
    <div class="contact-card reveal">
      <span class="kicker" style="letter-spacing:.2em;text-transform:uppercase;font-size:14px;font-weight:700;color:var(--gold);display:block;margin-bottom:14px">Ready When You Are</span>
      <h2>Let's plan your next getaway</h2>
      <p>Contact Gene for assistance with all of your Casino VIP reservation requests — land or sea. All cruises subject to availability.</p>
      <div class="contact-btns">
        <a class="btn btn-navy" href="tel:9492931661">📞&nbsp; Gene's Cell · 949-293-1661</a>
        <a class="btn btn-outline" href="mailto:genestark@outlook.com">✉️&nbsp; Email Gene</a>
      </div>
      <div class="contact-lines">
        <strong>GS VIP Travel</strong> · Office 949-800-7067<br>
        genestark@outlook.com · www.gsviptravel.com<br>
        7131 Yorktown Ave #1002, Huntington Beach, CA 92648
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">
    <div class="foot-top">
      <div>
        <div class="foot-brand"><span class="gs">GS</span> VIP Travel</div>
        <p style="max-width:380px">Exclusive Casino VIP Player Experiences and Luxury Cruises.<br>Gene Stark — Independent Gaming Representative (NVGB).</p>
      </div>
      <div class="foot-links">
        <a href="#caesars">Caesars Resorts</a>
        <a href="#cruises">Luxury Cruises</a>
        <a href="#about">About Gene</a>
        <a href="#contact">Contact</a>
      </div>
      <div class="foot-links">
        <a href="tel:9492931661">Cell: 949-293-1661</a>
        <a href="tel:9498007067">Office: 949-800-7067</a>
        <a href="mailto:genestark@outlook.com">genestark@outlook.com</a>
      </div>
    </div>
    <div class="foot-bottom">
      <span>© 2026 GS VIP Travel Specialists — All Rights Reserved.</span>
      <span>Caesars Entertainment · MSC Cruises · Norwegian · Royal Caribbean · Celebrity</span>
    </div>
  </div>
</footer>

<script>
// gentle scroll-reveal
const io = new IntersectionObserver((entries)=>{
  entries.forEach(e=>{ if(e.isIntersecting){ e.target.classList.add('in'); io.unobserve(e.target);} });
},{threshold:0.12});
document.querySelectorAll('.reveal').forEach(el=>io.observe(el));

// close mobile menu on link tap
document.querySelectorAll('#mm a').forEach(a=>a.addEventListener('click',()=>document.getElementById('mm').classList.remove('open')));
</script>
</body>
</html>
