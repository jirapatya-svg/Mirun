<!DOCTYPE html>  
<html lang="th">  
<head>  
<meta charset="utf-8" />  
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1" />  
<title>สำหรับ mirun 💖</title>  
<meta name="theme-color" content="#ff6b9e">  
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@300;400;600;800&display=swap" rel="stylesheet">  
<style>  
  :root{  
    --bg:#fff7fb; --card:#ffffff; --ink:#2b2b2b;  
    --pink:#ff6b9e; --pink2:#ff9dc0; --vio:#7b5cff;  
    --shadow:0 10px 30px rgba(0,0,0,.08); --radius:18px;  
  }  
  *{box-sizing:border-box}  
  html,body{margin:0;background:var(--bg);color:var(--ink);font-family:"Noto Sans Thai",system-ui,sans-serif}  
  .wrap{max-width:880px;margin:0 auto;padding:22px 16px 120px}  
  header{position:sticky;top:0;z-index:9;backdrop-filter:saturate(1.2) blur(8px);  
    background:linear-gradient(180deg,rgba(255,247,251,.85),rgba(255,247,251,.65));border-bottom:1px solid #ffe3f0}  
  .bar{display:flex;align-items:center;gap:12px;padding:10px 14px}  
  .logo{width:38px;height:38px;border-radius:12px;background:conic-gradient(from 210deg,var(--pink),var(--vio),var(--pink2));  
    box-shadow:var(--shadow);display:grid;place-items:center;color:white;font-weight:800}  
  h1{font-size:20px;margin:0}  
  .card{background:var(--card);border-radius:var(--radius);box-shadow:var(--shadow);padding:18px;margin:16px 0}  
  .cta{display:flex;flex-wrap:wrap;gap:12px}  
  button,.btn{appearance:none;border:none;cursor:pointer;background:linear-gradient(135deg,var(--pink),var(--vio));  
    color:white;border-radius:14px;padding:14px 16px;font-weight:700;box-shadow:0 8px 20px rgba(255,107,158,.35);transition:.2s transform,.2s filter}  
  button:active{transform:translateY(1px);filter:brightness(.95)}  
  .ghost{background:#fff;color:var(--pink);border:2px solid #ffd2e6;box-shadow:none}  
  .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:12px}  
  .tile{background:var(--card);border-radius:16px;padding:16px;border:1px solid #ffe3f0;display:flex;flex-direction:column;gap:10px;min-height:140px}  
  .tile h3{margin:0;font-size:18px}  
  .muted{opacity:.75}  
  .kiss{font-size:28px}  
  .center{text-align:center}  
  .tiny{font-size:12px;opacity:.7}  
  .pill{display:inline-block;background:#fff0f6;border:1px solid #ffd2e6;color:#cc3c7b;border-radius:999px;padding:6px 10px;font-weight:700}  
  /* Scratch card */  
  #scratch{touch-action:none;border-radius:12px;border:1px solid #ffe3f0;display:block;width:100%}  
  /* Timeline */  
  .timeline{position:relative;padding-left:12px}  
  .timeline::before{content:"";position:absolute;left:7px;top:0;bottom:0;width:2px;background:#ffd2e6}  
  .tl{position:relative;margin-left:14px;margin-bottom:14px;background:#fff;border:1px solid #ffe3f0;border-radius:12px;padding:12px}  
  .tl::before{content:"";position:absolute;left:-16px;top:12px;width:10px;height:10px;border-radius:50%;background:var(--pink)}  
  /* Gallery */  
  .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:6px}  
  .gallery img{width:100%;height:110px;object-fit:cover;border-radius:10px;border:1px solid #ffe3f0}  
  /* Hearts */  
  .heart{position:fixed;pointer-events:none;left:50%;font-size:22px;animation:float 3s ease-out forwards}  
  @keyframes float{0%{transform:translate(-50%,0) scale(1);opacity:1}100%{transform:translate(-50%,-160px) scale(1.8);opacity:0}}  
</style>  
</head>  
<body>  
<header>  
  <div class="bar">  
    <div class="logo">❤</div>  
    <div>  
      <h1>สำหรับ mirun 💕</h1>  
      <div class="tiny">เว็บเล็กๆ ที่ทำไว้ให้เธอคนเดียว</div>  
    </div>  
  </div>  
</header>  
  
<div class="wrap">  
  <!-- Hero -->  
  <section class="card center">  
    <div class="pill">เซอร์ไพรส์พิเศษ ✨</div>  
    <h2 class="kiss">สวัสดีที่รัก mirun 💘</h2>  
    <p class="type" id="type">วันนี้ 25 พฤษภาคม 2025 คือวันแรกของเรา 💞</p>  
    <div class="cta" style="justify-content:center;margin-top:10px">  
      <button onclick="burstHearts()">ปล่อยหัวใจ</button>  
      <button class="ghost" onclick="scrollToEl('#menu')">เริ่มกันเลย</button>  
    </div>  
  </section>  
  
  <!-- Quick menu -->  
  <section id="menu" class="grid">  
    <div class="tile">  
      <h3>ขูดการ์ดลับ 💌</h3>  
      <p class="muted">ขูดให้หมด เดี๋ยวรู้ว่ามีอะไรอยู่ข้างใต้</p>  
      <button onclick="openCard('scratchCard')">ไปขูดกัน</button>  
    </div>  
    <div class="tile">  
      <h3>ไทม์ไลน์ความรัก ⏳</h3>  
      <p class="muted">เก็บโมเมนต์สำคัญของเราไว้ตรงนี้</p>  
      <button onclick="openCard('timeline')">ดูไทม์ไลน์</button>  
    </div>  
    <div class="tile">  
      <h3>จดหมายล็อก 🔐</h3>  
      <p class="muted">ใส่รหัสวันที่พิเศษเพื่อเปิดอ่าน</p>  
      <button onclick="openCard('lockedLetter')">เปิดจดหมาย</button>  
    </div>  
    <div class="tile">  
      <h3>คูปองความรัก 🎟️</h3>  
      <p class="muted">สุ่มคูปองน่ารักๆ ให้ mirun</p>  
      <button onclick="openCard('coupons')">รับคูปอง</button>  
    </div>  
    <div class="tile">  
      <h3>แกลเลอรี 💞</h3>  
      <p class="muted">รวมรูปของเรา</p>  
      <button onclick="openCard('gallery')">เปิดดูรูป</button>  
    </div>  
  </section>  
  
  <!-- Scratch Card -->  
  <section id="scratchCard" class="card hidden">  
    <h3>ขูดการ์ดลับ 💌</h3>  
    <canvas id="scratch" width="800" height="320"></canvas>  
    <div class="center muted tiny">ขูด ~60% แล้วข้อความจะเผยทั้งหมด</div>  
    <div class="cta" style="justify-content:center;margin-top:10px">  
      <button onclick="resetScratch()" class="ghost">เริ่มใหม่</button>  
      <button onclick="back()">เสร็จละ</button>  
    </div>  
  </section>  
  
  <!-- Timeline -->  
  <section id="timeline" class="card hidden">  
    <h3>ไทม์ไลน์ความรัก ⏳</h3>  
    <div class="timeline" id="tl"></div>  
    <div class="cta" style="margin-top:10px">  
      <button class="ghost" onclick="back()">ย้อนกลับ</button>  
    </div>  
  </section>  
  
  <!-- Locked Letter -->  
  <section id="lockedLetter" class="card hidden">  
    <h3>จดหมายล็อก 🔐</h3>  
    <p class="muted">กรอกรหัสวันที่พิเศษของเราในรูปแบบ <b>DDMM</b></p>  
    <input id="pin" class="input" placeholder="ใส่รหัส 4 ตัว" maxlength="4" inputmode="numeric">  
    <div class="cta" style="margin-top:10px">  
      <button onclick="openLetter()">เปิดอ่าน</button>  
      <button class="ghost" onclick="back()">ย้อนกลับ</button>  
    </div>  
    <div id="letter" class="card hidden" style="background:#fff0f6;border:1px solid #ffd2e6">  
      <h3>ถึง mirun ของเค้า 💖</h3>  
      <p id="letterBody">  
        mirun, 25 พฤษภาคม 2025 คือวันแรกที่เราเริ่มคบกัน 💕    
        ขอบคุณที่เข้ามาเป็นความสุขในชีวิต เค้าจะดูแลเธอให้ดีที่สุด    
        ขอให้มีแต่วันที่ดีร่วมกันไปนานๆ รักเธอที่สุดเลย ❤  
      </p>  
    </div>  
  </section>  
  
  <!-- Love Coupons -->  
  <section id="coupons" class="card hidden">  
    <h3>คูปองความรัก 🎟️</h3>  
    <p class="muted">กดสุ่มคูปองให้ mirun ใช้ได้ 1 ครั้ง/ใบ</p>  
    <div id="couponBox" class="card" style="background:#fff0f6;border:1px dashed #ffb8d4;text-align:center;font-weight:800">  
      กดปุ่มด้านล่างเพื่อสุ่มคูปอง  
    </div>  
    <div class="cta" style="justify-content:center;margin-top:10px">  
      <button onclick="drawCoupon()">สุ่มคูปอง</button>  
      <button class="ghost" onclick="back()">ย้อนกลับ</button>  
    </div>  
  </section>  
  
  <!-- Gallery -->  
  <section id="gallery" class="card hidden">  
    <h3>แกลเลอรีของเรา 💞</h3>  
    <div class="gallery" id="gal"></div>  
    <div class="tiny muted" style="margin-top:8px">กดค้างที่รูปเพื่อบันทึก (บนมือถือ)</div>  
    <div class="cta" style="margin-top:10px">  
      <button class="ghost" onclick="back()">ย้อนกลับ</button>  
    </div>  
  </section>  
</div>  
  
<script>  
/* ===== Config ===== */  
const partnerName = "mirun";   
const secretPIN   = "2505";    
const revealText  = `mirun, 25 พฤษภาคม 2025 คือวันแรกที่เราเริ่มคบกัน 💕   
ขอบคุณที่เข้ามาเป็นความสุขในชีวิตเค้า   
จากนี้ไปเราจะมีแต่วันที่ดีด้วยกันนะ รักเธอที่สุดเลย ❤`;  
  
const timelineData = [  
  { date: "25 พ.ค. 2025", text: "วันที่เราเริ่มคบกัน 💘" },  
  { date: "25 มิ.ย. 2025", text: "ครบ 1 เดือนแรกของเรา" },  
  { date: "25 พ.ย. 2025", text: "ครบรอบครึ่งปี" },  
  { date: "25 พ.ค. 2026", text: "ครบรอบ 1 ปีเต็ม 🎉" }  
];  
  
const galleryImages = [  
  "D27936FA-7495-4D73-A445-D87020618C28.jpeg", // รูปคู่ที่คุณส่งมา  
  makePlaceholder("2"),  
  makePlaceholder("3")  
];  
  
const coupons = [  
  "กอดฟรีไม่จำกัดครั้ง 💞",  
  "mirun เลือกเมนู เราเลี้ยง 🍽️",  
  "นวดไหล่+หัว 20 นาที",  
  "ไปดูหนังที่ mirun เลือก ไม่เถียง",  
  "พาไปกินของอร่อยที่ mirun อยากกิน",  
  "ถ่ายรูปคู่เพิ่มอีกเยอะๆ วันนี้เลย 📸"  
];  
/* ===== Functions ===== */  
// Hearts  
function burstHearts(){  
  const emojis = ["💗","💖","💘","💝","💞","💕"];  
  for(let i=0;i<18;i++){  
    const h = document.createElement('div');  
    h.className='heart'; h.style.left = (15+Math.random()*70)+'%';  
    h.style.top = (60+Math.random()*10)+'%'; h.textContent = emojis[Math.floor(Math.random()*emojis.length)];  
    h.style.animationDuration = (2.2+Math.random()*1.2)+'s';  
    document.body.appendChild(h); setTimeout(()=>h.remove(), 3200);  
  }  
}  
// Router  
function openCard(id){  
  document.querySelectorAll('.wrap > section.card').forEach(s => {  
    if(s.id && s.id !== 'menu') s.classList.add('hidden');  
  });  
  document.getElementById(id).classList.remove('hidden');  
  scrollToEl('#'+id);  
}  
function back(){  
  document.querySelectorAll('.wrap > section.card').forEach(s => {  
    if(s.id && s.id !== 'menu' && s.id !== 'scratchCard') s.classList.add('hidden');  
  });  
  scrollToEl('#menu');  
}  
function scrollToEl(sel){ document.querySelector(sel).scrollIntoView({behavior:'smooth',block:'start'}); }  
// Timeline  
function buildTimeline(){  
  const tl = document.getElementById('tl'); tl.innerHTML="";  
  timelineData.forEach(i=>{  
    const n = document.createElement('div'); n.className='tl';  
    n.innerHTML = `<div class="tiny" style="margin-bottom:4px">${i.date}</div>${i.text}`;  
    tl.appendChild(n);  
  });  
}  
// Locked letter  
function openLetter(){  
  const pin = (document.getElementById('pin').value||'').trim();  
  if(pin === secretPIN){  
    document.getElementById('letter').classList.remove('hidden'); burstHearts();  
  }else{  
    alert('รหัสไม่ถูกน้าา ลองใหม่อีกที');  
  }  
}  
// Coupons  
function drawCoupon(){  
  const box = document.getElementById('couponBox');  
  const pick = coupons[Math.floor(Math.random()*coupons.length)];  
  box.textContent = pick + ' — สำหรับ ' + partnerName;  
}  
// Gallery  
function buildGallery(){  
  const g = document.getElementById('gal'); g.innerHTML="";  
  galleryImages.forEach(src=>{  
    const img = document.createElement('img'); img.src = src; img.alt='our-photo';  
    g.appendChild(img);  
  });  
}  
function makePlaceholder(id){  
  const svg = encodeURIComponent(`<svg xmlns='http://www.w3.org/2000/svg' width='400' height='300'>  
  <defs><linearGradient id='g' x1='0' x2='1' y1='0' y2='1'><stop offset='0' stop-color='#ffe3f0'/><stop offset='1' stop-color='#e8e3ff'/></linearGradient></defs>  
  <rect width='100%' height='100%' fill='url(#g)'/>  
  <text x='50%' y='50%' dominant-baseline='middle' text-anchor='middle' font-family='Noto Sans Thai' font-size='28' fill='#cc3c7b'>รูปที่ ${id}</text>  
  </svg>`);  
  return `data:image/svg+xml;charset=utf-8,${svg}`;  
}  
// Scratch card setup  
let scratch, sctx, coverImg, revealed=false;  
window.onload=()=>{buildTimeline();buildGallery();setupScratch();}  
function setupScratch(){  
  scratch = document.getElementById('scratch'); sctx = scratch.getContext('2d');  
  const bg = sctx.createLinearGradient(0,0,800,0); bg.addColorStop(0,'#fff0f6'); bg.addColorStop(1,'#f0e9ff');  
  sctx.fillStyle = bg; sctx.fillRect(0,0,scratch.width,scratch.height);  
  sctx.fillStyle = '#cc3c7b'; sctx.font = 'bold 30px "Noto Sans Thai", sans-serif';  
  wrapText(sctx, revealText, 32, 80, 740, 42);  
  coverImg = document.createElement('canvas'); coverImg.width=800; coverImg.height=320;  
  const cctx = coverImg.getContext('2d');  
  cctx.fillStyle = '#ffd2e6'; cctx.fillRect(0,0,800,320);  
  cctx.fillStyle = '#cc3c7b'; cctx.font = 'bold 26px "Noto Sans Thai", sans-serif';  
  cctx.fillText('ขูดตรงนี้สิ 💝', 300, 165);  
  sctx.globalCompositeOperation='destination-over'; sctx.drawImage(coverImg,0,0);  
  sctx.globalCompositeOperation='destination-out';  
  bindScratch();  
}  
function bindScratch(){  
  const pos = e => {  
    const r = scratch.getBoundingClientRect();  
    const x = (e.touches?e.t  
