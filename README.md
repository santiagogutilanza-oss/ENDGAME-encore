<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Endgame Encore | Santa María CENAFI</title>
<style>
:root{
  --red:#e21d2f; --gold:#f5c451; --dark:#07080d; --card:#11131c;
  --muted:#b9bcc8; --white:#fff;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
  font-family:Arial,Helvetica,sans-serif;background:var(--dark);color:var(--white);
  line-height:1.5;overflow-x:hidden;
}
body:before{
  content:"";position:fixed;inset:0;z-index:-2;
  background:
    radial-gradient(circle at 20% 20%,rgba(226,29,47,.20),transparent 30%),
    radial-gradient(circle at 80% 70%,rgba(245,196,81,.10),transparent 28%),
    linear-gradient(135deg,#05060a,#10121b 50%,#07080d);
}
nav{
  position:fixed;top:0;width:100%;z-index:20;padding:16px 7%;
  display:flex;justify-content:space-between;align-items:center;
  background:rgba(5,6,10,.82);backdrop-filter:blur(12px);border-bottom:1px solid #ffffff18;
}
.logo{font-weight:900;letter-spacing:2px;color:var(--gold)}
nav a{color:#fff;text-decoration:none;margin-left:22px;font-size:14px;font-weight:bold}
nav a:hover{color:var(--gold)}
.hero{
  min-height:100vh;display:flex;align-items:center;justify-content:center;text-align:center;
  padding:110px 7% 70px;position:relative;
}
.hero:after{
  content:"";position:absolute;width:520px;height:520px;border-radius:50%;
  border:1px solid #ffffff12;box-shadow:0 0 80px #e21d2f18;z-index:-1;
}
.kicker{color:var(--gold);font-weight:800;letter-spacing:4px;font-size:13px;text-transform:uppercase}
h1{
  font-size:clamp(55px,10vw,115px);line-height:.88;margin:20px 0;
  letter-spacing:-5px;text-shadow:0 8px 35px #000;
}
h1 span{display:block;color:var(--red)}
.subtitle{max-width:700px;margin:auto;color:#d7d8df;font-size:19px}
.cta{
  display:inline-block;margin-top:30px;padding:15px 28px;border-radius:8px;
  background:var(--red);color:white;text-decoration:none;font-weight:900;
  box-shadow:0 10px 30px #e21d2f44;transition:.2s;
}
.cta:hover{transform:translateY(-3px);background:#f0293b}
section{padding:85px 7%;max-width:1150px;margin:auto}
.section-title{text-align:center;margin-bottom:45px}
.section-title small{color:var(--gold);font-weight:800;letter-spacing:3px}
.section-title h2{font-size:38px;margin-top:8px}
.info-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:15px}
.card{
  background:linear-gradient(145deg,#151721,#0d0e15);border:1px solid #ffffff12;
  border-radius:16px;padding:24px;min-height:145px;box-shadow:0 15px 40px #0004;
}
.card .icon{font-size:28px;margin-bottom:12px}.card h3{font-size:15px;color:#aaaebb}.card p{font-size:21px;font-weight:800;margin-top:5px}
.highlight{
  background:linear-gradient(100deg,#6e0c18,#210b10);border:1px solid #ff465933;
  border-radius:20px;padding:40px;display:grid;grid-template-columns:1fr auto;align-items:center;gap:25px;
}
.highlight h2{font-size:32px}.highlight p{color:#d7d7dd;margin-top:8px}.price{font-size:48px;font-weight:900;color:var(--gold)}
.timeline{display:grid;gap:14px;max-width:760px;margin:auto}
.step{display:flex;gap:18px;align-items:flex-start;background:#10121a;padding:20px;border-radius:13px;border-left:4px solid var(--red)}
.step strong{color:var(--gold);min-width:90px}
.faq{display:grid;gap:10px;max-width:800px;margin:auto}
details{background:#10121a;border:1px solid #ffffff10;border-radius:12px;padding:18px 20px}
summary{cursor:pointer;font-weight:800}
details p{color:var(--muted);margin-top:10px}
footer{text-align:center;padding:45px 20px;color:#858895;border-top:1px solid #ffffff0d}
#countdown{font-size:clamp(30px,6vw,58px);font-weight:900;color:var(--gold);margin-top:12px}
@media(max-width:800px){
  nav{padding:14px 5%}nav a{display:none}.info-grid{grid-template-columns:1fr 1fr}
  .highlight{grid-template-columns:1fr}.hero{min-height:90vh}h1{letter-spacing:-3px}
}
@media(max-width:500px){.info-grid{grid-template-columns:1fr}.card{min-height:auto}section{padding:65px 5%}}
</style>
</head>
<body>
<nav>
  <div class="logo">CENAFI • CINE</div>
  <div>
    <a href="#info">INFO</a>
    <a href="#organizacion">ORGANIZACIÓN</a>
    <a href="#faq">FAQ</a>
  </div>
</nav>

<header class="hero">
  <div>
    <div class="kicker">Salida cinematográfica • Colegio Santa María CENAFI</div>
    <h1>ENDGAME <span>ENCORE</span></h1>
    <p class="subtitle">Una salida especial para disfrutar la película junto a todo el colegio.</p>
    <div id="countdown">Calculando...</div>
    <p style="color:#8f929d;margin-top:4px">para la función</p>
    <a class="cta" href="#info">VER INFORMACIÓN ↓</a>
  </div>
</header>

<section id="info">
  <div class="section-title">
    <small>TODO EN UN SOLO LUGAR</small>
    <h2>Información de la salida</h2>
  </div>
  <div class="info-grid">
    <div class="card"><div class="icon">📅</div><h3>FECHA</h3><p>3 de octubre</p></div>
    <div class="card"><div class="icon">🕚</div><h3>HORA</h3><p>11:00 AM</p></div>
    <div class="card"><div class="icon">🎬</div><h3>CINE</h3><p>Monje Campero</p></div>
    <div class="card"><div class="icon">🏫</div><h3>COLEGIO</h3><p>Santa María CENAFI</p></div>
  </div>
</section>

<section>
  <div class="highlight">
    <div>
      <h2>🎟️ Entrada</h2>
      <p>El precio indicado para participar en la salida cinematográfica es:</p>
    </div>
    <div class="price">25 Bs.</div>
  </div>
</section>

<section id="organizacion">
  <div class="section-title">
    <small>ANTES Y DURANTE LA SALIDA</small>
    <h2>Organización</h2>
  </div>
  <div class="timeline">
    <div class="step"><strong>ANTES</strong><div>Confirma tu participación y ten preparada tu entrada.</div></div>
    <div class="step"><strong>11:00</strong><div>Hora indicada para la función en el cine Monje Campero.</div></div>
    <div class="step"><strong>DURANTE</strong><div>Respeta las indicaciones de profesores y del personal del cine.</div></div>
    <div class="step"><strong>IMPORTANTE</strong><div>Si el colegio comunica cambios de horario, punto de encuentro o transporte, sigue siempre el aviso oficial.</div></div>
  </div>
</section>

<section id="faq">
  <div class="section-title">
    <small>PREGUNTAS FRECUENTES</small>
    <h2>¿Tienes dudas?</h2>
  </div>
  <div class="faq">
    <details><summary>¿Cuánto cuesta la entrada?</summary><p>La entrada tiene un costo de 25 Bs.</p></details>
    <details><summary>¿Dónde es la función?</summary><p>La función será en el cine Monje Campero.</p></details>
    <details><summary>¿Cuándo es?</summary><p>El 3 de octubre, a las 11:00 AM.</p></details>
    <details><summary>¿Qué pasa si hay cambios?</summary><p>Revisa los comunicados oficiales del colegio para cualquier modificación.</p></details>
  </div>
</section>

<footer>
  <strong>Santa María CENAFI</strong><br>
  Salida cinematográfica • Endgame Encore<br><br>
  <small>Esta página es informativa y no reemplaza los comunicados oficiales del colegio.</small>
</footer>

<script>
function updateCountdown(){
  const target = new Date("2026-10-03T11:00:00-04:00").getTime();
  const now = Date.now();
  let diff = target-now;
  const el=document.getElementById("countdown");
  if(diff<=0){el.textContent="¡LA FUNCIÓN ES HOY!";return;}
  const d=Math.floor(diff/86400000); diff%=86400000;
  const h=Math.floor(diff/3600000); diff%=3600000;
  const m=Math.floor(diff/60000); const s=Math.floor((diff%60000)/1000);
  el.textContent=`${d}d ${String(h).padStart(2,"0")}h ${String(m).padStart(2,"0")}m ${String(s).padStart(2,"0")}s`;
}
updateCountdown(); setInterval(updateCountdown,1000);
</script>
</body>
</html>
