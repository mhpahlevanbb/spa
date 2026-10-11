---
publish: true
created: 2026-10-10T23:41:53.159Z
modified: 2026-10-11T14:39:23.581Z
---

<!DOCTYPE html>

<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>ترانسفورماتور اسپادانا | تعمیر، نگهداری و فروش ترانسفورماتورهای قدرت و توزیع</title>
<meta name="description" content="ترانسفورماتور اسپادانا؛ تخصص، کیفیت و اطمینان در تعمیرات اساسی، سرویس دوره‌ای، فروش و ارزیابی ترانسفورماتورهای قدرت و توزیع بر پایه استانداردهای IEC 60076 و IEEE.">
<meta name="keywords" content="ترانسفورماتور, تعمیر ترانسفورماتور, اورهال ترانسفورماتور, ترانسفورماتور زرهی, DGA, BDV, ترانسفورماتور خشک رزینی, اسپادانا">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
<style>
  :root{
    --navy:#0a2540;
    --navy-2:#123a63;
    --blue:#1b74c4;
    --blue-soft:#e8f1fa;
    --accent:#f5a623;
    --accent-2:#ff8a00;
    --bg:#f6f8fb;
    --card:#ffffff;
    --text:#16232e;
    --muted:#5d7083;
    --border:#e3e9f0;
    --radius:16px;
    --shadow:0 10px 30px rgba(10,37,64,.08);
    --shadow-lg:0 20px 50px rgba(10,37,64,.14);
  }

\*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth;scroll-padding-top:90px}
body{
font-family:'Vazirmatn',system-ui,Tahoma,sans-serif;
background:var(--bg);
color:var(--text);
line-height:1.95;
direction:rtl;
overflow-x:hidden;
}
a{text-decoration:none;color:inherit}
ul{list-style:none}
img{max-width:100%;display:block}
button,input,select,textarea{font-family:inherit}

.container{width:min(1180px,92%);margin-inline:auto}

/\* ============ HEADER ============ \*/
.site-header{
position:sticky;top:0;z-index:200;
background:rgba(255,255,255,.94);
backdrop-filter:blur(14px);
border-bottom:1px solid var(--border);
transition:box-shadow .3s ease;
}
.site-header.scrolled{box-shadow:0 8px 26px rgba(10,37,64,.10)}
.nav{display:flex;align-items:center;justify-content:space-between;gap:20px;height:78px}
.logo{display:flex;align-items:center;gap:12px}
.logo-mark{
width:46px;height:46px;border-radius:13px;flex:0 0 auto;
background:linear-gradient(135deg,var(--navy),var(--blue));
display:grid;place-items:center;color:#fff;
box-shadow:0 8px 18px rgba(27,116,196,.28);
}
.logo-mark svg{width:26px;height:26px}
.logo-text{display:flex;flex-direction:column;line-height:1.35}
.logo-text b{font-size:17px;font-weight:800;color:var(--navy)}
.logo-text small{font-size:11px;color:var(--muted);font-weight:500}

.nav-links{display:flex;align-items:center;gap:4px}
.nav-links a{
padding:9px 14px;border-radius:10px;font-size:14.5px;font-weight:500;
color:#31465c;transition:.22s;white-space:nowrap;
}
.nav-links a:hover{background:var(--blue-soft);color:var(--blue)}

.btn{
display:inline-flex;align-items:center;justify-content:center;gap:8px;
padding:12px 24px;border-radius:12px;font-size:14.5px;font-weight:600;
border:none;cursor:pointer;transition:.25s;white-space:nowrap;
}
.btn-accent{
background:linear-gradient(135deg,var(--accent),var(--accent-2));
color:#20160a;box-shadow:0 10px 22px rgba(245,166,35,.32);
}
.btn-accent:hover{transform:translateY(-2px);box-shadow:0 14px 28px rgba(245,166,35,.42)}
.btn-ghost{background:transparent;color:#fff;border:1.5px solid rgba(255,255,255,.45)}
.btn-ghost:hover{background:rgba(255,255,255,.12);border-color:#fff}
.btn-navy{background:var(--navy);color:#fff}
.btn-navy:hover{background:var(--navy-2);transform:translateY(-2px)}
.btn-outline{background:#fff;color:var(--navy);border:1.5px solid var(--border)}
.btn-outline:hover{border-color:var(--blue);color:var(--blue)}

.burger{
display:none;width:46px;height:46px;border-radius:12px;border:1px solid var(--border);
background:#fff;cursor:pointer;place-items:center;
}
.burger span{display:block;width:20px;height:2px;background:var(--navy);border-radius:2px;position:relative;transition:.25s}
.burger span::before,.burger span::after{
content:"";position:absolute;right:0;width:20px;height:2px;background:var(--navy);border-radius:2px;transition:.25s;
}
.burger span::before{top:-6px}
.burger span::after{top:6px}
.burger.open span{background:transparent}
.burger.open span::before{top:0;transform:rotate(45deg)}
.burger.open span::after{top:0;transform:rotate(-45deg)}

/\* ============ HERO ============ \*/
.hero{
position:relative;overflow:hidden;color:#fff;
padding:92px 0 104px;
background:
radial-gradient(circle at 88% 12%, rgba(245,166,35,.20), transparent 42%),
radial-gradient(circle at 8% 88%, rgba(27,116,196,.30), transparent 45%),
linear-gradient(135deg,#081d33 0%,#0a2540 40%,#123a63 100%);
}
.hero::after{
content:"";position:absolute;inset:0;opacity:.35;pointer-events:none;
background-image:linear-gradient(rgba(255,255,255,.05) 1px,transparent 1px),
linear-gradient(90deg,rgba(255,255,255,.05) 1px,transparent 1px);
background-size:64px 64px;
mask-image:radial-gradient(circle at 50% 40%,#000,transparent 78%);
}
.hero .container{position:relative;z-index:2}
.hero-grid{display:grid;grid-template-columns:1.15fr .85fr;gap:56px;align-items:center}

.badge{
display:inline-flex;align-items:center;gap:9px;
background:rgba(255,255,255,.10);border:1px solid rgba(255,255,255,.22);
padding:8px 16px;border-radius:100px;font-size:13px;font-weight:500;
color:#dbe9f7;margin-bottom:22px;
}
.badge i{width:8px;height:8px;border-radius:50%;background:var(--accent);box-shadow:0 0 0 4px rgba(245,166,35,.22);display:block}

.hero h1{
font-size:clamp(28px,4vw,46px);font-weight:800;line-height:1.55;
letter-spacing:-.4px;margin-bottom:20px;
}
.hero h1 em{
font-style:normal;
background:linear-gradient(135deg,var(--accent),#ffd479);
-webkit-background-clip:text;background-clip:text;color:transparent;
}
.hero p.lead{font-size:16.5px;color:#c3d6e8;max-width:640px;font-weight:300;margin-bottom:32px}
.hero-actions{display:flex;gap:14px;flex-wrap:wrap;margin-bottom:46px}

.hero-stats{
display:grid;grid-template-columns:repeat(4,1fr);gap:1px;
background:rgba(255,255,255,.14);border:1px solid rgba(255,255,255,.14);
border-radius:14px;overflow:hidden;
}
.hero-stats div{background:rgba(9,29,50,.55);padding:18px 12px;text-align:center}
.hero-stats b{display:block;font-size:15px;font-weight:700;color:#fff}
.hero-stats span{font-size:12px;color:#9db6cd}

/\* Hero side card \*/
.hero-card{
background:rgba(255,255,255,.07);
border:1px solid rgba(255,255,255,.18);
border-radius:22px;padding:30px 26px;
backdrop-filter:blur(10px);
box-shadow:var(--shadow-lg);
}
.hero-card h3{font-size:17px;font-weight:700;margin-bottom:18px;display:flex;align-items:center;gap:10px}
.hero-card h3 svg{width:20px;height:20px;color:var(--accent)}
.hero-card ul li{
display:flex;gap:11px;align-items:flex-start;
font-size:14px;color:#c8dbeb;padding:9px 0;font-weight:300;
border-bottom:1px dashed rgba(255,255,255,.10);
}
.hero-card ul li:last-child{border-bottom:none}
.hero-card ul li svg{width:17px;height:17px;flex:0 0 auto;margin-top:7px;color:#5fd08a}

/\* ============ SECTIONS ============ \*/
section{padding:84px 0}
.section-head{text-align:center;max-width:740px;margin:0 auto 52px}
.eyebrow{
display:inline-block;font-size:13px;font-weight:600;color:var(--blue);
background:var(--blue-soft);padding:6px 16px;border-radius:100px;margin-bottom:16px;
}
.section-head h2{font-size:clamp(23px,3vw,33px);font-weight:800;color:var(--navy);line-height:1.6;margin-bottom:14px}
.section-head p{color:var(--muted);font-size:15.5px}

.alt-bg{background:#fff;border-block:1px solid var(--border)}

/\* Cards \*/
.grid{display:grid;gap:22px}
.grid-4{grid-template-columns:repeat(auto-fit,minmax(248px,1fr))}
.grid-3{grid-template-columns:repeat(auto-fit,minmax(290px,1fr))}
.grid-2{grid-template-columns:repeat(auto-fit,minmax(340px,1fr))}

.card{
background:var(--card);border:1px solid var(--border);border-radius:var(--radius);
padding:28px 24px;transition:.3s;position:relative;overflow:hidden;
}
.card::before{
content:"";position:absolute;inset-inline:0;top:0;height:3px;
background:linear-gradient(90deg,var(--blue),var(--accent));
transform:scaleX(0);transform-origin:right;transition:transform .35s ease;
}
.card:hover{transform:translateY(-6px);box-shadow:var(--shadow-lg);border-color:#d3e0ee}
.card:hover::before{transform:scaleX(1)}

.card-icon{
width:52px;height:52px;border-radius:14px;display:grid;place-items:center;
background:var(--blue-soft);color:var(--blue);margin-bottom:18px;
}
.card-icon svg{width:26px;height:26px}
.card h3{font-size:17px;font-weight:700;color:var(--navy);margin-bottom:10px}
.card p{font-size:14.5px;color:var(--muted);font-weight:300}

/\* About \*/
.about-grid{display:grid;grid-template-columns:1fr 1fr;gap:44px;align-items:start}
.about-text p{color:var(--muted);font-size:15.5px;font-weight:300;margin-bottom:16px}
.mini-panels{display:grid;gap:18px;margin-top:26px}
.mini{
background:#fff;border:1px solid var(--border);border-radius:14px;padding:22px 22px;
border-inline-start:4px solid var(--blue);
}
.mini h4{font-size:15.5px;font-weight:700;color:var(--navy);margin-bottom:8px;display:flex;align-items:center;gap:9px}
.mini h4 svg{width:18px;height:18px;color:var(--blue)}
.mini p{font-size:14px;color:var(--muted);font-weight:300;margin:0}

.feature-list{display:grid;gap:14px}
.feature{
display:flex;gap:14px;align-items:flex-start;background:#fff;
border:1px solid var(--border);border-radius:14px;padding:18px 20px;transition:.25s;
}
.feature:hover{border-color:#cfe0f0;box-shadow:var(--shadow);transform:translateX(-4px)}
.feature .tick{
width:30px;height:30px;border-radius:9px;background:#e9f8ef;color:#1f9d55;
display:grid;place-items:center;flex:0 0 auto;margin-top:4px;
}
.feature .tick svg{width:16px;height:16px}
.feature b{display:block;font-size:15px;color:var(--navy);font-weight:700;margin-bottom:3px}
.feature span{font-size:13.5px;color:var(--muted);font-weight:300}

/\* Steps \*/
.steps{counter-reset:step;display:grid;gap:16px}
.step{
counter-increment:step;position:relative;
background:#fff;border:1px solid var(--border);border-radius:14px;
padding:20px 76px 20px 22px;transition:.25s;
}
.step::before{
content:counter(step);
position:absolute;right:20px;top:50%;transform:translateY(-50%);
width:40px;height:40px;border-radius:12px;
background:linear-gradient(135deg,var(--navy),var(--blue));color:#fff;
display:grid;place-items:center;font-weight:700;font-size:16px;
box-shadow:0 6px 14px rgba(27,116,196,.28);
}
.step b{display:block;font-size:15px;color:var(--navy);font-weight:700;margin-bottom:4px}
.step span{font-size:14px;color:var(--muted);font-weight:300}
.step:hover{box-shadow:var(--shadow);border-color:#d3e0ee}

/\* Tables \*/
.table-wrap{
background:#fff;border:1px solid var(--border);border-radius:var(--radius);
overflow:hidden;box-shadow:var(--shadow);
}
.table-scroll{overflow-x:auto}
table{width:100%;border-collapse:collapse;min-width:520px}
thead th{
background:linear-gradient(135deg,var(--navy),var(--navy-2));
color:#fff;font-size:14px;font-weight:600;padding:15px 18px;text-align:right;white-space:nowrap;
}
tbody td{
padding:14px 18px;font-size:14px;color:#3a4d60;border-bottom:1px solid #eef2f7;
}
tbody tr:last-child td{border-bottom:none}
tbody tr:nth-child(even){background:#fafcfe}
tbody tr:hover{background:var(--blue-soft)}
tbody td:first-child{font-weight:600;color:var(--navy)}
.price{font-weight:700;color:var(--blue);white-space:nowrap;direction:ltr;text-align:left}

.note{
display:flex;gap:12px;align-items:flex-start;
background:#fff8ea;border:1px solid #ffe3b0;border-inline-start:4px solid var(--accent);
border-radius:12px;padding:16px 18px;margin-top:18px;
font-size:13.5px;color:#7a5a1c;
}
.note svg{width:19px;height:19px;flex:0 0 auto;margin-top:5px;color:var(--accent-2)}

/\* Maintenance layout \*/
.split{display:grid;grid-template-columns:1fr 1fr;gap:44px;align-items:start}
.sub-title{
font-size:18px;font-weight:700;color:var(--navy);margin-bottom:20px;
display:flex;align-items:center;gap:10px;
}
.sub-title::before{content:"";width:5px;height:22px;border-radius:3px;background:linear-gradient(var(--blue),var(--accent))}

/\* Form \*/
.form-card{
background:#fff;border:1px solid var(--border);border-radius:20px;
padding:34px 30px;box-shadow:var(--shadow);
}
.form-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.field{display:flex;flex-direction:column;gap:8px}
.field.full{grid-column:1/-1}
.field label{font-size:13.5px;font-weight:600;color:#31465c}
.field input,.field select,.field textarea{
width:100%;padding:12px 15px;border:1.5px solid var(--border);border-radius:11px;
font-size:14px;background:#fbfdff;color:var(--text);transition:.2s;outline:none;
}
.field input:focus,.field select:focus,.field textarea:focus{
border-color:var(--blue);background:#fff;box-shadow:0 0 0 4px rgba(27,116,196,.10);
}
.field textarea{resize:vertical;min-height:110px}
.form-foot{margin-top:24px;display:flex;align-items:center;gap:16px;flex-wrap:wrap}
.form-msg{
display:none;background:#e9f8ef;border:1px solid #b8e6c9;color:#1f7a45;
padding:12px 18px;border-radius:11px;font-size:14px;margin-top:16px;
}
.form-msg.show{display:block}

/\* Blog \*/
.post{
background:#fff;border:1px solid var(--border);border-radius:var(--radius);
padding:24px 22px;display:flex;gap:16px;align-items:flex-start;transition:.28s;
}
.post:hover{transform:translateY(-5px);box-shadow:var(--shadow-lg);border-color:#d3e0ee}
.post .num{
width:42px;height:42px;flex:0 0 auto;border-radius:12px;
background:var(--blue-soft);color:var(--blue);display:grid;place-items:center;
font-weight:700;font-size:15px;
}
.post h4{font-size:15px;font-weight:600;color:var(--navy);line-height:1.75}
.post:hover h4{color:var(--blue)}

/\* Contact \*/
.contact-grid{display:grid;grid-template-columns:.9fr 1.1fr;gap:40px;align-items:start}
.info-card{
background:linear-gradient(160deg,var(--navy),var(--navy-2));
color:#fff;border-radius:20px;padding:34px 30px;box-shadow:var(--shadow-lg);
}
.info-card h3{font-size:19px;font-weight:700;margin-bottom:22px}
.info-item{display:flex;gap:14px;align-items:flex-start;padding:14px 0;border-bottom:1px solid rgba(255,255,255,.12)}
.info-item:last-child{border-bottom:none}
.info-item .ic{
width:40px;height:40px;border-radius:11px;flex:0 0 auto;
background:rgba(255,255,255,.10);display:grid;place-items:center;color:var(--accent);
}
.info-item .ic svg{width:19px;height:19px}
.info-item b{display:block;font-size:13px;color:#9db6cd;font-weight:500;margin-bottom:2px}
.info-item span{font-size:15px;font-weight:500}

/\* Footer \*/
footer{background:#081d33;color:#9db6cd;padding:56px 0 26px;font-size:14px}
.footer-grid{display:grid;grid-template-columns:1.4fr 1fr 1fr;gap:38px;padding-bottom:34px;border-bottom:1px solid rgba(255,255,255,.10)}
.footer-grid h4{color:#fff;font-size:16px;font-weight:700;margin-bottom:16px}
.footer-grid ul li{padding:7px 0;transition:.2s;font-weight:300}
.footer-grid ul li:hover{color:var(--accent)}
.footer-about p{font-weight:300;line-height:2;color:#8ba4bc}
.footer-bottom{padding-top:22px;text-align:center;font-size:13px;color:#6c86a1}

/\* Reveal animation \*/
.reveal{opacity:0;transform:translateY(22px);transition:opacity .65s ease,transform .65s ease}
.reveal.in{opacity:1;transform:none}

/\* Scroll to top \*/
.to-top{
position:fixed;inset-inline-start:22px;bottom:22px;width:46px;height:46px;border-radius:13px;
background:var(--navy);color:#fff;border:none;cursor:pointer;display:grid;place-items:center;
box-shadow:var(--shadow-lg);opacity:0;visibility:hidden;transition:.3s;z-index:150;
}
.to-top.show{opacity:1;visibility:visible}
.to-top:hover{background:var(--blue)}

/\* ============ RESPONSIVE ============ \*/
@media (max-width:1024px){
.hero-grid{grid-template-columns:1fr;gap:44px}
.about-grid,.split,.contact-grid{grid-template-columns:1fr;gap:34px}
.footer-grid{grid-template-columns:1fr 1fr}
}
@media (max-width:900px){
.burger{display:grid}
.nav-links{
position:absolute;top:78px;inset-inline:0;
background:#fff;border-bottom:1px solid var(--border);
flex-direction:column;align-items:stretch;gap:2px;
padding:14px 6%;box-shadow:0 18px 34px rgba(10,37,64,.12);
display:none;
}
.nav-links.open{display:flex}
.nav-links a{padding:13px 14px;border-radius:10px;font-size:15px}
.header-cta{display:none}
}
@media (max-width:640px){
section{padding:62px 0}
.hero{padding:64px 0 74px}
.hero-stats{grid-template-columns:1fr 1fr}
.form-grid{grid-template-columns:1fr}
.form-card{padding:26px 20px}
.step{padding:18px 68px 18px 18px}
.footer-grid{grid-template-columns:1fr;gap:28px}
.logo-text small{display:none}
} </style>

</head>
<body>

<!-- ==================== HEADER ==================== -->

<header class="site-header" id="header">
  <div class="container">
    <nav class="nav">
      <a href="#hero" class="logo">
        <span class="logo-mark">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
            <rect x="4" y="3" width="16" height="18" rx="2"/>
            <path d="M8 7h8M8 11h8M8 15h4"/>
            <path d="M12 3v18"/>
          </svg>
        </span>
        <span class="logo-text">
          <b>ترانسفورماتور اسپادانا</b>
          <small>تعمیر، نگهداری و تأمین ترانسفورماتور</small>
        </span>
      </a>

```
  <ul class="nav-links" id="navLinks">
    <li><a href="#services">خدمات</a></li>
    <li><a href="#about">درباره ما</a></li>
    <li><a href="#maintenance">تعمیر و نگهداری</a></li>
    <li><a href="#sales">فروش ترانسفورماتور</a></li>
    <li><a href="#evaluation">ارزیابی و قیمت‌گذاری</a></li>
    <li><a href="#lab">آزمایشگاه</a></li>
    <li><a href="#blog">وبلاگ</a></li>
    <li><a href="#contact">تماس</a></li>
  </ul>

  <a href="#contact" class="btn btn-accent header-cta">درخواست مشاوره</a>

  <button class="burger" id="burger" aria-label="منو">
    <span></span>
  </button>
</nav>
```

  </div>
</header>

<!-- ==================== HERO ==================== -->

<section class="hero" id="hero">
  <div class="container">
    <div class="hero-grid">
      <div class="hero-copy">
        <span class="badge"><i></i> تخصص، کیفیت و اطمینان در تعمیر و نگهداری ترانسفورماتور</span>
        <h1>پایداری شبکه برق‌رسانی خود را با <em>ترانسفورماتور اسپادانا</em> تضمین کنید</h1>
        <p class="lead">
          با بهره‌گیری از دانش فنی متخصصان مجرب و تجهیزات پیشرفته، خدمات جامع تعمیر، نگهداری، بازسازی
          و تأمین ترانسفورماتورهای قدرت و توزیع را بر پایه استانداردهای IEC 60076 و IEEE ارائه می‌دهیم.
        </p>
        <div class="hero-actions">
          <a href="#contact" class="btn btn-accent">
            درخواست ارزیابی فنی
            <svg width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 12H5M12 19l-7-7 7-7"/></svg>
          </a>
          <a href="#services" class="btn btn-ghost">مشاهده خدمات</a>
        </div>

```
    <div class="hero-stats">
      <div><b>IEC 60076</b><span>استاندارد اجرایی</span></div>
      <div><b>۲۴/۷</b><span>پشتیبانی اضطراری</span></div>
      <div><b>DGA / BDV</b><span>آزمون‌های تشخیصی</span></div>
      <div><b>گارانتی</b><span>تضمین کیفیت خدمات</span></div>
    </div>
  </div>

  <aside class="hero-card">
    <h3>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg>
      چرا ترانسفورماتور اسپادانا؟
    </h3>
    <ul>
      <li>
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg>
        تیم مهندسان برق قدرت با تجربه در تعمیرات اساسی ترانسفورماتورهای زرهی
      </li>
      <li>
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg>
        آزمایشگاه مجهز به دستگاه‌های آزمون DGA، BDV، مقاومت عایقی و نسبت تبدیل
      </li>
      <li>
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg>
        آمادگی اعزام تیم سیار تعمیراتی در شرایط اضطراری
      </li>
      <li>
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg>
        افزایش عمر مفید تجهیزات و کاهش هزینه‌های خرابی‌های غیرمنتظره
      </li>
    </ul>
  </aside>
</div>
```

  </div>
</section>

<!-- ==================== SERVICES ==================== -->

<section id="services">
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">خدمات کلیدی</span>
      <h2>خدمات جامع تعمیر و نگهداری ترانسفورماتور</h2>
      <p>مأموریت ما افزایش عمر مفید تجهیزات شما و کاهش هزینه‌های ناشی از خرابی‌های غیرمنتظره است.</p>
    </div>

```
<div class="grid grid-4">
  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round">
        <path d="M14.7 6.3a1 1 0 000 1.4l1.6 1.6a1 1 0 001.4 0l3.77-3.77a6 6 0 01-7.94 7.94l-6.91 6.91a2.12 2.12 0 01-3-3l6.91-6.91a6 6 0 017.94-7.94l-3.76 3.76z"/>
      </svg>
    </div>
    <h3>تعمیرات اساسی</h3>
    <p>دمونتاژ کامل، بازسازی سیستم عایقی، تعویض سیم‌پیچی و مونتاژ مجدد اکتیو پارت.</p>
  </article>

  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round">
        <circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 2"/>
      </svg>
    </div>
    <h3>سرویس دوره‌ای</h3>
    <p>بازرسی‌های روزانه، هفتگی، ماهانه و سالانه بر پایه استانداردهای بین‌المللی.</p>
  </article>

  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round">
        <path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/><path d="M3 6h18M16 10a4 4 0 01-8 0"/>
      </svg>
    </div>
    <h3>فروش ترانسفورماتور</h3>
    <p>تأمین انواع ترانسفورماتورهای قدرت، توزیع، خشک رزینی و ویژه با گارانتی معتبر.</p>
  </article>

  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round">
        <path d="M9 11l3 3L22 4"/><path d="M21 12v7a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h11"/>
      </svg>
    </div>
    <h3>ارزیابی و قیمت‌گذاری</h3>
    <p>کارشناسی فنی ترانسفورماتورهای مستعمل و بازسازی‌شده با آزمون‌های تشخیصی استاندارد.</p>
  </article>
</div>
```

  </div>
</section>

<!-- ==================== ABOUT ==================== -->

<section id="about" class="alt-bg">
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">درباره ما</span>
      <h2>مرجع تخصصی تعمیر و نگهداری ترانسفورماتور</h2>
      <p>دانش بومی، استانداردهای جهانی و تجربه عملی در پروژه‌های نیروگاهی، پالایشگاهی و صنعتی.</p>
    </div>

```
<div class="about-grid">
  <div class="about-text reveal">
    <div class="sub-title">معرفی شرکت</div>
    <p>
      شرکت ترانسفورماتور اسپادانا با هدف ارائه خدمات تخصصی در حوزه تعمیر، نگهداری، بازسازی و تأمین
      ترانسفورماتورهای قدرت و توزیع تأسیس شده است. تیم فنی ما متشکل از مهندسان برق قدرت و تکنسین‌های
      مجرب است که سال‌ها تجربه عملی در پروژه‌های نیروگاهی، پالایشگاهی و صنعتی را در کارنامه خود دارند.
    </p>
    <p>
      ما با تکیه بر دانش فنی متخصصان مجرب و بهره‌گیری از تجهیزات پیشرفته، در کنار شما هستیم تا
      پایداری شبکه برق‌رسانی خود را تضمین کنید.
    </p>

    <div class="mini-panels">
      <div class="mini">
        <h4>
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><circle cx="12" cy="12" r="6"/><circle cx="12" cy="12" r="2"/></svg>
          مأموریت
        </h4>
        <p>توانمندسازی صنایع و شرکت‌های توزیع نیرو برای بهینه‌سازی عملکرد ترانسفورماتورهای خود از طریق خدمات فنی دقیق، سریع و مقرون‌به‌صرفه.</p>
      </div>
      <div class="mini">
        <h4>
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/><circle cx="12" cy="12" r="3"/></svg>
          چشم‌انداز
        </h4>
        <p>تبدیل شدن به مرجع تخصصی تعمیر و نگهداری ترانسفورماتور در ایران و منطقه، با تکیه بر دانش بومی و استانداردهای جهانی.</p>
      </div>
    </div>
  </div>

  <div class="reveal">
    <div class="sub-title">مزیت‌های رقابتی</div>
    <div class="feature-list">
      <div class="feature">
        <span class="tick"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg></span>
        <div><b>تیم متخصص</b><span>مهندسان برق قدرت با تجربه در تعمیرات اساسی ترانسفورماتورهای زرهی (Shell Type).</span></div>
      </div>
      <div class="feature">
        <span class="tick"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg></span>
        <div><b>تجهیزات پیشرفته</b><span>آزمایشگاه مجهز به دستگاه‌های آزمون DGA، BDV، مقاومت عایقی و نسبت تبدیل.</span></div>
      </div>
      <div class="feature">
        <span class="tick"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg></span>
        <div><b>استانداردهای بین‌المللی</b><span>تمام خدمات بر پایه استانداردهای IEC 60076 و IEEE انجام می‌شود.</span></div>
      </div>
      <div class="feature">
        <span class="tick"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg></span>
        <div><b>پشتیبانی ۲۴/۷</b><span>آمادگی برای اعزام تیم تعمیراتی در شرایط اضطراری.</span></div>
      </div>
      <div class="feature">
        <span class="tick"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg></span>
        <div><b>گارانتی خدمات</b><span>تضمین کیفیت تمام تعمیرات و قطعات تعویض‌شده.</span></div>
      </div>
    </div>
  </div>
</div>
```

  </div>
</section>

<!-- ==================== MAINTENANCE ==================== -->

<section id="maintenance">
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">خدمات تعمیر و نگهداری</span>
      <h2>نگهداری صحیح، عمر مفید بیشتر، خسارت کمتر</h2>
      <p>
        ترانسفورماتورها گران‌بهاترین و حیاتی‌ترین تجهیزات شبکه‌های انتقال و توزیع برق شناخته می‌شوند.
        نگهداری صحیح و به‌موقع آن‌ها نه‌تنها عمر مفید تجهیزات را افزایش می‌دهد، بلکه از بروز خسارات
        جبران‌ناپذیر ناشی از قطع برق جلوگیری می‌کند.
      </p>
    </div>

```
<div class="split" style="margin-bottom:52px">
  <div class="reveal">
    <div class="sub-title">تعمیرات اساسی (اورهال)</div>
    <div class="steps">
      <div class="step"><b>دمونتاژ کامل</b><span>باز کردن تانک، بوشینگ‌ها، رادیاتورها و اتصالات.</span></div>
      <div class="step"><b>بازرسی اکتیو پارت</b><span>بررسی هسته، سیم‌پیچی‌ها و سیستم عایقی.</span></div>
      <div class="step"><b>مهندسی معکوس و بازسازی سیستم عایقی</b><span>بازسازی عایق‌های فرسوده مطابق مشخصات اصلی.</span></div>
      <div class="step"><b>تعویض سیم‌پیچی</b><span>در صورت نیاز، بازسازی کامل سیم‌پیچی‌های آسیب‌دیده.</span></div>
      <div class="step"><b>خشک‌کردن و مونتاژ</b><span>خشک‌کردن اکتیو پارت و مونتاژ مجدد.</span></div>
      <div class="step"><b>آزمون‌های نهایی</b><span>انجام آزمون‌های بی‌باری، اتصال کوتاه، مقاومت عایقی و نسبت تبدیل.</span></div>
    </div>
  </div>

  <div class="reveal">
    <div class="sub-title">تعمیر در محل و تخصص ویژه</div>
    <div class="card" style="margin-bottom:18px">
      <h3>تعمیر در محل (تیم سیار)</h3>
      <p>
        تیم سیار ترانسفورماتور اسپادانا با تجهیزات قابل حمل، قادر به انجام تعمیرات جزئی و نیمه‌اساسی
        در محل نصب ترانسفورماتور است. این خدمات شامل رفع نشتی روغن، تعویض گسکت، تعویض بوشینگ،
        تصفیه روغن و تنظیم تپ‌چنجر تحت بار است. خدمات پس از فروش ایران ترانسفو نیز شامل تصفیه و
        سیرکولاسیون روغن در سایت، خشک‌سازی اکتیو پارت و انجام آزمون‌های الکتریکی و روغن بر روی
        ترانسفورماتور است.
      </p>
    </div>
    <div class="card">
      <h3>تخصص ویژه: تعمیر ترانسفورماتورهای زرهی</h3>
      <p>
        ترانسفورماتورهای زرهی به دلیل ساختار خاص و پیچیدگی فنی، نیازمند تخصص ویژه برای تعمیرات اساسی
        هستند. تیم ترانسفورماتور اسپادانا با تسلط بر این نوع ترانسفورماتورها، آماده ارائه خدمات
        تعمیرات اساسی با بالاترین کیفیت است.
      </p>
    </div>
  </div>
</div>

<div class="reveal">
  <div class="sub-title">نگهداری پیشگیرانه — برنامه نگهداری دوره‌ای</div>
  <div class="table-wrap">
    <div class="table-scroll">
      <table>
        <thead>
          <tr>
            <th style="width:140px">دوره</th>
            <th>فعالیت‌ها</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>روزانه</td>
            <td>بررسی دمای روغن، سطح روغن، فشار گاز، وضعیت بوشینگ‌ها</td>
          </tr>
          <tr>
            <td>هفتگی</td>
            <td>بازرسی نشتی، عملکرد سیستم خنک‌کاری، وضعیت رطوبت‌گیر</td>
          </tr>
          <tr>
            <td>ماهانه</td>
            <td>آزمون روغن (BDV، اسیدیته)، بررسی عملکرد رله‌های حفاظتی</td>
          </tr>
          <tr>
            <td>سالانه</td>
            <td>تحلیل گاز محلول (DGA)، آزمون مقاومت عایقی، آزمون نسبت تبدیل، بازرسی کامل تانک و اتصالات</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
```

  </div>
</section>

<!-- ==================== SALES ==================== -->

<section id="sales" class="alt-bg">
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">فروش ترانسفورماتور</span>
      <h2>تأمین انواع ترانسفورماتور قدرت و توزیع</h2>
      <p>
        تمام محصولات ما مطابق استانداردهای IEC 60076 تأمین و با گارانتی معتبر ارائه می‌شوند.
      </p>
    </div>

```
<div class="grid grid-3" style="margin-bottom:52px">
  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg>
    </div>
    <h3>ترانسفورماتورهای قدرت (Power Transformers)</h3>
    <p>مناسب برای نیروگاه‌ها، پست‌های فوق‌توزیع و صنایع سنگین. ظرفیت از ۲۰ MVA تا بیش از ۵۰۰ MVA.</p>
  </article>

  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"><path d="M3 21h18M5 21V7l7-4 7 4v14"/><path d="M9 21v-6h6v6"/></svg>
    </div>
    <h3>ترانسفورماتورهای توزیع (Distribution)</h3>
    <p>مناسب برای شبکه‌های توزیع شهری و روستایی. ظرفیت از ۲۵ kVA تا ۱۰ MVA.</p>
  </article>

  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/><path d="M9 12l2 2 4-4"/></svg>
    </div>
    <h3>ترانسفورماتورهای خشک رزینی (Dry-Type)</h3>
    <p>
      مناسب برای محیط‌های حساس مانند بیمارستان‌ها، ساختمان‌های بلندمرتبه و صنایع غذایی. بدون روغن و
      ایمنی بالا در برابر آتش. تقاضا برای ترانسفورماتورهای خشک در ایران به دلیل نیاز به راهکارهای
      انرژی‌کارآمد در حال افزایش است.
    </p>
  </article>

  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 00.33 1.82l.06.06a2 2 0 11-2.83 2.83l-.06-.06a1.65 1.65 0 00-1.82-.33 1.65 1.65 0 00-1 1.51V21a2 2 0 11-4 0v-.09A1.65 1.65 0 008 19.4a1.65 1.65 0 00-1.82.33l-.06.06a2 2 0 11-2.83-2.83l.06-.06a1.65 1.65 0 00.33-1.82 1.65 1.65 0 00-1.51-1H2a2 2 0 110-4h.09A1.65 1.65 0 003.6 8a1.65 1.65 0 00-.33-1.82l-.06-.06a2 2 0 112.83-2.83l.06.06A1.65 1.65 0 008 3.6 1.65 1.65 0 009 2.09V2a2 2 0 114 0v.09a1.65 1.65 0 001 1.51 1.65 1.65 0 001.82-.33l.06-.06a2 2 0 112.83 2.83l-.06.06A1.65 1.65 0 0019.4 8v0a1.65 1.65 0 001.51 1H21a2 2 0 110 4h-.09a1.65 1.65 0 00-1.51 1z"/></svg>
    </div>
    <h3>ترانسفورماتورهای ویژه</h3>
    <p>شامل ترانسفورماتورهای کوره قوس الکتریکی (EAF)، ترانسفورماتورهای یکسوساز و ترانسفورماتورهای نیروگاه‌های تجدیدپذیر.</p>
  </article>

  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"><path d="M21 12a9 9 0 11-9-9"/><path d="M21 3v6h-6"/></svg>
    </div>
    <h3>ترانسفورماتورهای دست دوم بازسازی‌شده</h3>
    <p>ترانسفورماتورهای کارشناسی‌شده با گارانتی، گزینه‌ای اقتصادی برای پروژه‌های با بودجه محدود.</p>
  </article>

  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2l3 7h7l-5.5 4.5L18.5 21 12 16.5 5.5 21l2-7.5L2 9h7z"/></svg>
    </div>
    <h3>خدمات پس از فروش</h3>
    <p>نصب و راه‌اندازی توسط تیم فنی مجرب، آموزش بهره‌برداران، پشتیبانی فنی تلفنی و آنلاین و تأمین قطعات یدکی اصلی.</p>
  </article>
</div>

<div class="reveal">
  <div class="sub-title">نمونه قیمت‌های بازار (شهریور ۱۴۰۵)</div>
  <p style="color:var(--muted);font-size:14.5px;margin-bottom:18px;font-weight:300">
    برای مرجع مشتریان، نمونه قیمت‌های ترانسفورماتور توزیع ایران ترانسفو به شرح زیر است:
  </p>

  <div class="table-wrap">
    <div class="table-scroll">
      <table>
        <thead>
          <tr>
            <th>توان</th>
            <th>نوع</th>
            <th>قیمت (ریال)</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>۲۵ kVA</td><td>تک‌فاز ۲۰ کیلوولت</td><td class="price">۲,۳۴۸,۱۸۱,۰۰۰</td></tr>
          <tr><td>۵۰ kVA</td><td>کم‌تلفات ۲۰ کیلوولت</td><td class="price">۴,۸۰۲,۳۸۰,۰۰۰</td></tr>
          <tr><td>۱۰۰ kVA</td><td>کم‌تلفات ۲۰ کیلوولت</td><td class="price">۷,۳۰۱,۰۰۸,۰۰۰</td></tr>
          <tr><td>۱۶۰ kVA</td><td>کم‌تلفات (روغنی)</td><td class="price">۸۹۰,۶۹۹,۰۰۰</td></tr>
          <tr><td>۶۳۰ kVA</td><td>کم‌تلفات (روغنی)</td><td class="price">۲,۳۳۲,۸۸۳,۰۰۰</td></tr>
          <tr><td>۱۰۰۰ kVA</td><td>کم‌تلفات (روغنی)</td><td class="price">۳,۰۷۶,۳۹۰,۰۰۰</td></tr>
        </tbody>
      </table>
    </div>
  </div>

  <div class="note">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><path d="M12 16v-4M12 8h.01"/></svg>
    <span>توجه: قیمت‌ها بر اساس لیست رسمی شهریور ۱۴۰۵ و با احتساب ارزش افزوده اعلام شده‌اند. هزینه حمل به‌صورت جداگانه محاسبه می‌شود.</span>
  </div>
</div>
```

  </div>
</section>

<!-- ==================== EVALUATION ==================== -->

<section id="evaluation">
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">ارزیابی و قیمت‌گذاری</span>
      <h2>تصمیم درست، پیش‌نیاز آن ارزیابی فنی دقیق است</h2>
      <p>
        ارزیابی فنی دقیق ترانسفورماتور، پیش‌نیاز تصمیم‌گیری صحیح برای تعمیر، بازسازی یا جایگزینی آن است.
        ترانسفورماتور اسپادانا با بهره‌گیری از آزمون‌های تشخیصی استاندارد، وضعیت واقعی تجهیزات شما را
        مشخص می‌کند.
      </p>
    </div>

```
<div class="reveal" style="margin-bottom:52px">
  <div class="sub-title">آزمون‌های تشخیصی</div>
  <div class="table-wrap">
    <div class="table-scroll">
      <table>
        <thead>
          <tr>
            <th>آزمون</th>
            <th>هدف</th>
            <th>استاندارد</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>تحلیل گاز محلول (DGA)</td><td>تشخیص زودهنگام خطاهای داخلی</td><td>IEC 60567</td></tr>
          <tr><td>ولتاژ شکست روغن (BDV)</td><td>ارزیابی کیفیت عایقی روغن</td><td>IEC 60156</td></tr>
          <tr><td>اسیدیته روغن</td><td>سنجش میزان تخریب روغن</td><td>IEC 62021</td></tr>
          <tr><td>کشش سطحی</td><td>بررسی وضعیت مولکول‌های روغن</td><td>ASTM D971</td></tr>
          <tr><td>مقاومت عایقی</td><td>ارزیابی عایق‌بندی سیم‌پیچی</td><td>IEC 60076-1</td></tr>
          <tr><td>نسبت تبدیل</td><td>بررسی سلامت سیم‌پیچی‌ها</td><td>IEC 60076-1</td></tr>
          <tr><td>تانژانت دلتا (Tan δ)</td><td>سنجش تلفات عایقی</td><td>IEC 60076-1</td></tr>
          <tr><td>مقاومت سیم‌پیچی</td><td>تشخیص اتصال کوتاه حلقه‌ای</td><td>IEC 60076-1</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>

<div class="split" style="margin-bottom:52px">
  <div class="reveal">
    <div class="sub-title">فرآیند ارزیابی ترانسفورماتور دست دوم</div>
    <div class="steps">
      <div class="step"><b>بازرسی ظاهری</b><span>بررسی پلاک مشخصات، بدنه، بوشینگ‌ها و نشتی‌ها.</span></div>
      <div class="step"><b>نمونه‌برداری روغن</b><span>انجام آزمون‌های DGA، BDV و اسیدیته.</span></div>
      <div class="step"><b>آزمون‌های الکتریکی</b><span>مقاومت عایقی، نسبت تبدیل، مقاومت سیم‌پیچی.</span></div>
      <div class="step"><b>تحلیل نتایج</b><span>مقایسه با مقادیر مرجع و تعیین وضعیت کلی ترانسفورماتور.</span></div>
      <div class="step"><b>صدور گزارش ارزیابی</b><span>ارائه گزارش کامل همراه با توصیه‌های فنی.</span></div>
    </div>
  </div>

  <div class="reveal">
    <div class="sub-title">عوامل مؤثر بر قیمت</div>
    <div class="card">
      <ul style="display:grid;gap:10px">
        <li style="display:flex;gap:10px;align-items:flex-start;font-size:14.5px;color:var(--muted)">
          <span style="color:var(--blue);font-weight:700">•</span> ظرفیت نامی (kVA یا MVA)
        </li>
        <li style="display:flex;gap:10px;align-items:flex-start;font-size:14.5px;color:var(--muted)">
          <span style="color:var(--blue);font-weight:700">•</span> سطح ولتاژ (kV)
        </li>
        <li style="display:flex;gap:10px;align-items:flex-start;font-size:14.5px;color:var(--muted)">
          <span style="color:var(--blue);font-weight:700">•</span> نوع ترانسفورماتور (روغنی، خشک، هرمتیک)
        </li>
        <li style="display:flex;gap:10px;align-items:flex-start;font-size:14.5px;color:var(--muted)">
          <span style="color:var(--blue);font-weight:700">•</span> کلاس حرارتی و سطح تلفات
        </li>
        <li style="display:flex;gap:10px;align-items:flex-start;font-size:14.5px;color:var(--muted)">
          <span style="color:var(--blue);font-weight:700">•</span> استانداردهای ساخت (IEC، IEEE)
        </li>
        <li style="display:flex;gap:10px;align-items:flex-start;font-size:14.5px;color:var(--muted)">
          <span style="color:var(--blue);font-weight:700">•</span> برند و کشور سازنده
        </li>
        <li style="display:flex;gap:10px;align-items:flex-start;font-size:14.5px;color:var(--muted)">
          <span style="color:var(--blue);font-weight:700">•</span> وضعیت (نو، دست دوم، بازسازی‌شده)
        </li>
      </ul>
    </div>

    <div class="note" style="margin-top:18px">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M10.29 3.86L1.82 18a2 2 0 001.71 3h16.94a2 2 0 001.71-3L13.71 3.86a2 2 0 00-3.42 0z"/><path d="M12 9v4M12 17h.01"/></svg>
      <span><b>نکته مهم:</b> توان یکسان به معنی مشخصات فنی و کاربرد یکسان نیست. قیمت ترانسفورماتور به سطح ولتاژ، نوع عایق، مقدار تلفات، جنس سیم‌پیچ، تجهیزات جانبی و شرایط پروژه بستگی دارد.</span>
    </div>
  </div>
</div>

<div class="reveal">
  <div class="sub-title">فرم درخواست ارزیابی</div>
  <p style="color:var(--muted);font-size:14.5px;margin-bottom:20px;font-weight:300">
    برای دریافت پیش‌فاکتور و ارزیابی فنی، لطفاً فرم زیر را تکمیل کنید:
  </p>

  <form class="form-card" id="evalForm" novalidate>
    <div class="form-grid">
      <div class="field">
        <label for="e-name">نام و نام خانوادگی</label>
        <input type="text" id="e-name" name="name" placeholder="مثال: علی محمدی" required>
      </div>
      <div class="field">
        <label for="e-company">نام شرکت</label>
        <input type="text" id="e-company" name="company" placeholder="نام شرکت / سازمان">
      </div>
      <div class="field">
        <label for="e-phone">شماره تماس</label>
        <input type="tel" id="e-phone" name="phone" placeholder="۰۹۱۲۳۴۵۶۷۸۹" required>
      </div>
      <div class="field">
        <label for="e-capacity">ظرفیت ترانسفورماتور (kVA)</label>
        <input type="text" id="e-capacity" name="capacity" placeholder="مثال: ۱۰۰۰">
      </div>
      <div class="field">
        <label for="e-voltage">سطح ولتاژ (kV)</label>
        <input type="text" id="e-voltage" name="voltage" placeholder="مثال: ۲۰">
      </div>
      <div class="field">
        <label for="e-type">نوع ترانسفورماتور</label>
        <select id="e-type" name="type">
          <option value="">انتخاب کنید…</option>
          <option>روغنی</option>
          <option>خشک</option>
          <option>هرمتیک</option>
          <option>ویژه</option>
        </select>
      </div>
      <div class="field">
        <label for="e-status">وضعیت</label>
        <select id="e-status" name="status">
          <option value="">انتخاب کنید…</option>
          <option>نو</option>
          <option>دست دوم</option>
          <option>نیازمند تعمیر</option>
        </select>
      </div>
      <div class="field full">
        <label for="e-desc">توضیحات</label>
        <textarea id="e-desc" name="desc" placeholder="توضیحات تکمیلی درباره تجهیز، علائم خرابی یا نیاز پروژه…"></textarea>
      </div>
    </div>

    <div class="form-foot">
      <button type="submit" class="btn btn-navy">ارسال درخواست ارزیابی</button>
      <span style="font-size:13px;color:var(--muted)">پاسخ‌گویی در اولین فرصت کاری</span>
    </div>
    <div class="form-msg" id="evalMsg">درخواست شما ثبت شد. کارشناسان ما به‌زودی با شما تماس می‌گیرند.</div>
  </form>
</div>
```

  </div>
</section>

<!-- ==================== LAB ==================== -->

<section id="lab" class="alt-bg">
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">آزمایشگاه و تست</span>
      <h2>آزمایشگاه تخصصی ترانسفورماتور</h2>
      <p>
        آزمایشگاه تخصصی ترانسفورماتور اسپادانا با تجهیزات پیشرفته، آماده ارائه خدمات آزمون و تحلیل روغن
        ترانسفورماتور و آزمون‌های الکتریکی است.
      </p>
    </div>

```
<div class="grid grid-2">
  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round">
        <path d="M9 3h6v5l4 9a2 2 0 01-1.8 3H6.8A2 2 0 015 17l4-9V3z"/><path d="M6.5 14h11"/>
      </svg>
    </div>
    <h3>تحلیل روغن ترانسفورماتور</h3>
    <ul style="display:grid;gap:11px;margin-top:6px">
      <li style="font-size:14.5px;color:var(--muted)">— <b style="color:var(--navy);font-weight:600">تحلیل گاز محلول (DGA):</b> شناسایی خطاهای حرارتی و الکتریکی</li>
      <li style="font-size:14.5px;color:var(--muted)">— <b style="color:var(--navy);font-weight:600">ولتاژ شکست (BDV):</b> ارزیابی کیفیت عایقی</li>
      <li style="font-size:14.5px;color:var(--muted)">— <b style="color:var(--navy);font-weight:600">اسیدیته (Neutralization Number):</b> سنجش تخریب روغن</li>
      <li style="font-size:14.5px;color:var(--muted)">— <b style="color:var(--navy);font-weight:600">کشش سطحی (Interfacial Tension):</b> بررسی وضعیت مولکولی</li>
      <li style="font-size:14.5px;color:var(--muted)">— <b style="color:var(--navy);font-weight:600">محتوای رطوبت:</b> اندازه‌گیری آب موجود در روغن</li>
    </ul>
  </article>

  <article class="card reveal">
    <div class="card-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round">
        <path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/>
      </svg>
    </div>
    <h3>آزمون‌های الکتریکی</h3>
    <ul style="display:grid;gap:11px;margin-top:6px">
      <li style="font-size:14.5px;color:var(--muted)">— مقاومت عایقی و شاخص پلاریزاسیون</li>
      <li style="font-size:14.5px;color:var(--muted)">— مقاومت سیم‌پیچی</li>
      <li style="font-size:14.5px;color:var(--muted)">— نسبت تبدیل</li>
      <li style="font-size:14.5px;color:var(--muted)">— تانژانت دلتا (Tan δ)</li>
      <li style="font-size:14.5px;color:var(--muted)">— آزمون ولتاژ اعمالی و القایی</li>
    </ul>
  </article>
</div>
```

  </div>
</section>

<!-- ==================== BLOG ==================== -->

<section id="blog">
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">وبلاگ فنی</span>
      <h2>مقالات پیشنهادی</h2>
      <p>مطالب آموزشی و فنی درباره نگهداری، عیب‌یابی و انتخاب ترانسفورماتور.</p>
    </div>

```
<div class="grid grid-3">
  <a href="#blog" class="post reveal">
    <span class="num">۱</span>
    <h4>راهنمای گام‌به‌گام نگهداری دوره‌ای ترانسفورماتورهای قدرت</h4>
  </a>
  <a href="#blog" class="post reveal">
    <span class="num">۲</span>
    <h4>DGA چیست و چگونه از خرابی ترانسفورماتور جلوگیری می‌کند؟</h4>
  </a>
  <a href="#blog" class="post reveal">
    <span class="num">۳</span>
    <h4>علائم هشداردهنده خرابی ترانسفورماتور که نباید نادیده بگیرید</h4>
  </a>
  <a href="#blog" class="post reveal">
    <span class="num">۴</span>
    <h4>تفاوت ترانسفورماتور روغنی و خشک رزینی: کدام یک برای پروژه شما مناسب است؟</h4>
  </a>
  <a href="#blog" class="post reveal">
    <span class="num">۵</span>
    <h4>هزینه‌های پنهان خرابی ترانسفورماتور: چرا نگهداری پیشگیرانه مقرون‌به‌صرفه است؟</h4>
  </a>
  <a href="#blog" class="post reveal">
    <span class="num">۶</span>
    <h4>روش‌های تشخیص ترانسفورماتورهای تقلبی و دست دوم معیوب</h4>
  </a>
</div>
```

  </div>
</section>

<!-- ==================== CONTACT ==================== -->

<section id="contact" class="alt-bg">
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">تماس با ما</span>
      <h2>آماده پاسخ‌گویی به شما هستیم</h2>
      <p>برای مشاوره فنی، استعلام قیمت یا درخواست اعزام تیم تعمیراتی با ما در تماس باشید.</p>
    </div>

```
<div class="contact-grid">
  <aside class="info-card reveal">
    <h3>اطلاعات تماس</h3>
    <div class="info-item">
      <span class="ic">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>
      </span>
      <div><b>آدرس</b><span>...</span></div>
    </div>
    <div class="info-item">
      <span class="ic">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07 19.5 19.5 0 01-6-6A19.79 19.79 0 012.12 4.18 2 2 0 014.11 2h3a2 2 0 012 1.72c.13.96.36 1.9.7 2.81a2 2 0 01-.45 2.11L8.09 9.91a16 16 0 006 6l1.27-1.27a2 2 0 012.11-.45c.9.34 1.85.57 2.81.7A2 2 0 0122 16.92z"/></svg>
      </span>
      <div><b>تلفن</b><span>...</span></div>
    </div>
    <div class="info-item">
      <span class="ic">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><path d="M22 6l-10 7L2 6"/></svg>
      </span>
      <div><b>ایمیل</b><span>...</span></div>
    </div>
    <div class="info-item">
      <span class="ic">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
      </span>
      <div><b>ساعات کاری</b><span>شنبه تا چهارشنبه، ۸ تا ۱۷</span></div>
    </div>
  </aside>

  <form class="form-card reveal" id="contactForm" novalidate>
    <div class="sub-title" style="margin-bottom:22px">فرم استعلام سریع</div>
    <div class="form-grid">
      <div class="field">
        <label for="c-name">نام</label>
        <input type="text" id="c-name" name="name" placeholder="نام و نام خانوادگی" required>
      </div>
      <div class="field">
        <label for="c-company">شرکت</label>
        <input type="text" id="c-company" name="company" placeholder="نام شرکت">
      </div>
      <div class="field">
        <label for="c-phone">تلفن</label>
        <input type="tel" id="c-phone" name="phone" placeholder="۰۹۱۲۳۴۵۶۷۸۹" required>
      </div>
      <div class="field">
        <label for="c-type">نوع درخواست</label>
        <select id="c-type" name="type">
          <option value="">انتخاب کنید…</option>
          <option>تعمیر</option>
          <option>فروش</option>
          <option>ارزیابی</option>
          <option>مشاوره</option>
        </select>
      </div>
      <div class="field full">
        <label for="c-desc">توضیحات</label>
        <textarea id="c-desc" name="desc" placeholder="شرح درخواست خود را وارد کنید…"></textarea>
      </div>
    </div>
    <div class="form-foot">
      <button type="submit" class="btn btn-accent">ارسال درخواست</button>
      <span style="font-size:13px;color:var(--muted)">یا با شماره تماس درج‌شده تماس بگیرید</span>
    </div>
    <div class="form-msg" id="contactMsg">پیام شما با موفقیت ارسال شد. به‌زودی با شما تماس می‌گیریم.</div>
  </form>
</div>
```

  </div>
</section>

<!-- ==================== FOOTER ==================== -->

<footer>
  <div class="container">
    <div class="footer-grid">
      <div class="footer-about">
        <h4>ترانسفورماتور اسپادانا</h4>
        <p>
          ارائه‌دهنده خدمات جامع تعمیرات اساسی، نگهداری پیشگیرانه، بازسازی، فروش و ارزیابی ترانسفورماتورهای
          قدرت و توزیع، بر پایه استانداردهای IEC 60076 و IEEE.
        </p>
      </div>

```
  <div>
    <h4>دسترسی سریع</h4>
    <ul>
      <li><a href="#services">خدمات کلیدی</a></li>
      <li><a href="#about">درباره ما</a></li>
      <li><a href="#maintenance">تعمیر و نگهداری</a></li>
      <li><a href="#sales">فروش ترانسفورماتور</a></li>
    </ul>
  </div>

  <div>
    <h4>خدمات تخصصی</h4>
    <ul>
      <li><a href="#evaluation">ارزیابی و قیمت‌گذاری</a></li>
      <li><a href="#lab">آزمایشگاه و تست</a></li>
      <li><a href="#maintenance">تعمیر ترانسفورماتور زرهی</a></li>
      <li><a href="#contact">پشتیبانی ۲۴/۷</a></li>
    </ul>
  </div>
</div>

<div class="footer-bottom">
  © تمامی حقوق برای شرکت ترانسفورماتور اسپادانا محفوظ است.
</div>
```

  </div>
</footer>

<button class="to-top" id="toTop" aria-label="بازگشت به بالا">
  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 19V5M5 12l7-7 7 7"/></svg>
</button>

<script>
  /* ---------- Mobile menu ---------- */
  const burger = document.getElementById('burger');
  const navLinks = document.getElementById('navLinks');

  burger.addEventListener('click', () => {
    burger.classList.toggle('open');
    navLinks.classList.toggle('open');
  });

  navLinks.querySelectorAll('a').forEach(link => {
    link.addEventListener('click', () => {
      burger.classList.remove('open');
      navLinks.classList.remove('open');
    });
  });

  /* ---------- Header shadow + scroll-to-top ---------- */
  const header = document.getElementById('header');
  const toTop = document.getElementById('toTop');

  window.addEventListener('scroll', () => {
    const y = window.scrollY;
    header.classList.toggle('scrolled', y > 12);
    toTop.classList.toggle('show', y > 600);
  });

  toTop.addEventListener('click', () => {
    window.scrollTo({ top: 0, behavior: 'smooth' });
  });

  /* ---------- Reveal on scroll ---------- */
  const revealEls = document.querySelectorAll('.reveal');
  if ('IntersectionObserver' in window) {
    const io = new IntersectionObserver((entries) => {
      entries.forEach((entry, i) => {
        if (entry.isIntersecting) {
          setTimeout(() => entry.target.classList.add('in'), i * 70);
          io.unobserve(entry.target);
        }
      });
    }, { threshold: 0.12, rootMargin: '0px 0px -40px 0px' });

    revealEls.forEach(el => io.observe(el));
  } else {
    revealEls.forEach(el => el.classList.add('in'));
  }

  /* ---------- Forms (demo submit) ---------- */
  function handleForm(formId, msgId) {
    const form = document.getElementById(formId);
    const msg = document.getElementById(msgId);
    if (!form) return;

    form.addEventListener('submit', (e) => {
      e.preventDefault();

      const required = form.querySelectorAll('[required]');
      let valid = true;
      required.forEach(input => {
        if (!input.value.trim()) {
          valid = false;
          input.style.borderColor = '#e05252';
          input.addEventListener('input', () => { input.style.borderColor = ''; }, { once: true });
        }
      });

      if (!valid) return;

      msg.classList.add('show');
      form.reset();
      setTimeout(() => msg.classList.remove('show'), 6000);
    });
  }

  handleForm('evalForm', 'evalMsg');
  handleForm('contactForm', 'contactMsg');
</script>

</body>
</html>
