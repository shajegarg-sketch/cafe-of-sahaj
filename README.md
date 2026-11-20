<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Kulhad Corner Café</title>
<meta name="description" content="Chai in clay cups, cold coffee, wood-fired pizza and fresh bakes. Open daily, 8 am to 11 pm.">
<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>☕</text></svg>">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=Karla:wght@400;500;700&display=swap" rel="stylesheet">
<style>
:root{--teal:#0F3D3A;--teal2:#16524E;--gold:#F4B63A;--chalk:#F2F6F3;--ink:#17231F;--coral:#E4694F;--muted:#5A6B66;--line:#D3DDD8}
@media (prefers-color-scheme:dark){:root{--chalk:#0C1F1D;--ink:#EAF1ED;--muted:#9DB0AA;--line:#27413D}}
*{box-sizing:border-box;margin:0}
html{scroll-behavior:smooth}
body{font-family:Karla,system-ui,sans-serif;background:var(--chalk);color:var(--ink);line-height:1.65;font-size:17px}
h1,h2,h3{font-family:'Bricolage Grotesque',Georgia,serif;line-height:1.05;letter-spacing:-.02em}
a{color:inherit}
:focus-visible{outline:3px solid var(--gold);outline-offset:3px}
.wrap{max-width:1040px;margin:0 auto;padding:0 22px}
nav{display:flex;justify-content:space-between;align-items:center;padding:18px 0}
nav b{font-family:'Bricolage Grotesque',serif;font-size:1.25rem}
nav div a{margin-left:20px;text-decoration:none;font-weight:500}
nav div a:hover{text-decoration:underline}
.hero{background:var(--teal);color:#F2F6F3;overflow:hidden}
.hero .wrap{padding-bottom:84px}
.hero nav b{color:var(--gold)}
.hero h1{font-size:clamp(3.2rem,11vw,8rem);font-weight:800;margin:56px 0 22px;max-width:9em}
.hero h1 span{color:var(--gold)}
.hero p{max-width:34em;font-size:1.15rem;opacity:.9}
.btns{margin-top:30px;display:flex;gap:14px;flex-wrap:wrap}
.btn{display:inline-block;padding:13px 24px;border-radius:999px;font-weight:700;text-decoration:none;background:var(--gold);color:#1B1B10}
.btn.alt{background:transparent;color:#F2F6F3;border:2px solid #F2F6F3}
.btn:hover{transform:translateY(-2px)}
section{padding:76px 0}
h2{font-size:clamp(2rem,5vw,3.2rem);margin-bottom:12px}
.lead{color:var(--muted);max-width:34em;margin-bottom:34px}
.tabs{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:26px}
.tabs button{font:inherit;font-weight:700;padding:9px 20px;border-radius:999px;border:2px solid var(--teal2);background:transparent;color:var(--ink);cursor:pointer}
.tabs button[aria-selected=true]{background:var(--teal2);color:#fff}
.menu{list-style:none;padding:0;display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:4px 48px}
.menu li{display:flex;justify-content:space-between;gap:16px;padding:16px 0;border-bottom:1px dashed var(--line)}
.menu strong{display:block;font-size:1.08rem}
.menu small{color:var(--muted);font-size:.93rem}
.menu .p{font-family:'Bricolage Grotesque',serif;font-weight:700;font-size:1.15rem;white-space:nowrap}
.story{background:var(--gold);color:#1B1B10}
.story p{max-width:36em;font-size:1.2rem}
.story h2{max-width:11em}
.info{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:36px}
.info h3{font-size:1.4rem;margin-bottom:8px}
.info td{padding:2px 22px 2px 0}
footer{background:var(--teal);color:#F2F6F3;padding:34px 0;font-size:.95rem}
footer .wrap{display:flex;justify-content:space-between;flex-wrap:wrap;gap:10px}
@media (prefers-reduced-motion:reduce){*{transition:none!important;scroll-behavior:auto!important}}
@media (prefers-reduced-motion:no-preference){.btn{transition:transform .15s}}
</style>
</head>
<body>
<header class="hero">
  <div class="wrap">
    <nav><b>Kulhad Corner</b><div><a href="#menu">Menu</a><a href="#story">Our story</a><a href="#visit">Visit</a></div></nav>
    <h1>Chai, served <span>in clay.</span></h1>
    <p>A neighbourhood café for slow mornings, loud evenings and everything in between. Kulhad chai, cold coffee, wood-fired pizza and bakes from our own oven.</p>
    <div class="btns"><a class="btn" href="#menu">See the menu</a><a class="btn alt" href="#visit">Find us</a></div>
  </div>
</header>

<main>
<section id="menu"><div class="wrap">
  <h2>What we're pouring and baking</h2>
  <p class="lead">Everything is made fresh each day. Ask us about today's special.</p>
  <div class="tabs" role="tablist" aria-label="Menu categories"></div>
  <ul class="menu" id="items"></ul>
</div></section>

<section id="story" class="story"><div class="wrap">
  <h2>Started with one stove and a lot of tea.</h2>
  <p>Kulhad Corner began as a tea stall idea between friends. Today it's a small café where students study, families celebrate birthdays and regulars keep their own corner table. We still boil the chai the slow way, with fresh ginger and cardamom, and pour it into a kulhad that you can take home.</p>
</div></section>

<section id="visit"><div class="wrap">
  <h2>Come say hello</h2>
  <p class="lead">Walk in, or message us to book a table for your group.</p>
  <div class="info">
    <div><h3>Hours</h3><table><tr><td>Mon to Fri</td><td>8 am to 11 pm</td></tr><tr><td>Sat and Sun</td><td>8 am to midnight</td></tr></table></div>
    <div><h3>Address</h3><p>12, Main Market Road<br>Your City, Punjab</p></div>
    <div><h3>Book or order</h3><p><a href="https://wa.me/910000000000" rel="noopener">Message us on WhatsApp</a><br><a href="tel:+910000000000">+91 00000 00000</a></p></div>
  </div>
</div></section>
</main>

<footer><div class="wrap"><span>© <span id="yr">2026</span> Kulhad Corner Café</span><span>Made fresh, every day.</span></div></footer>

<script>
const MENU={
 "Chai & Coffee":[["Kulhad Masala Chai","Ginger, cardamom, slow boiled",40],["Cold Coffee","Thick, with a scoop of ice cream",120],["Hazelnut Latte","Hot or iced",150],["Filter Coffee","South Indian style",70]],
 "Bites":[["Paneer Tikka Sandwich","Grilled, with mint chutney",130],["Veg Cheese Maggi","The late-night classic",90],["Peri Peri Fries","Crisp, with house dip",110],["Bun Maska","Soft bun, white butter",60]],
 "Pizza & Pasta":[["Margherita Pizza","Wood-fired, fresh basil",220],["Farmhouse Pizza","Capsicum, onion, olives, corn",280],["White Sauce Pasta","Creamy, with garlic bread",200],["Red Sauce Pasta","Tangy and herby",190]],
 "Desserts":[["Brownie with Ice Cream","Warm, with chocolate sauce",150],["Chocolate Cake Slice","Baked in-house",110],["Kulhad Kulfi","Malai, pistachio",80]]
};
const tabs=document.querySelector('.tabs'),list=document.getElementById('items');
function show(cat){
  tabs.querySelectorAll('button').forEach(b=>b.setAttribute('aria-selected',b.textContent===cat));
  list.innerHTML='';
  MENU[cat].forEach(([n,d,p])=>{
    const li=document.createElement('li');
    li.innerHTML='<div><strong></strong><small></small></div><span class="p">₹'+p+'</span>';
    li.querySelector('strong').textContent=n;li.querySelector('small').textContent=d;
    list.appendChild(li);
  });
}
Object.keys(MENU).forEach(c=>{
  const b=document.createElement('button');b.textContent=c;b.setAttribute('role','tab');
  b.onclick=()=>show(c);tabs.appendChild(b);
});
show(Object.keys(MENU)[0]);
document.getElementById('yr').textContent=new Date().getFullYear();
</script>
</body>
</html>
