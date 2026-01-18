
<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GRAND ASIA</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
<style>
body{font-family:'Poppins',sans-serif;margin:0;padding:0;background:#0a1f33;color:#fff;}
header{background:#102b46;text-align:center;padding:20px;color:#e3b17d;font-size:28px;font-weight:bold;}
nav{display:flex;justify-content:center;gap:15px;padding:10px;background:#081522;}
nav button{background:none;border:none;color:#e3b17d;font-weight:bold;font-size:14px;cursor:pointer;}
nav button:hover{color:#f0c08d;}
section{padding:40px 10px;text-align:center;}
h2{color:#e3b17d;margin-bottom:15px;}
p{max-width:600px;margin:auto;line-height:1.6;}
button.action{background:#e3b17d;border:none;color:#0a1f33;padding:10px 20px;border-radius:8px;font-weight:bold;margin-top:15px;}
button.action:hover{background:#f0c08d;}
.gallery{display:flex;flex-wrap:wrap;justify-content:center;margin-top:20px;}
.gallery img{width:90%;max-width:300px;border-radius:10px;margin:10px;transition:transform 0.3s;}
.gallery img:hover{transform:scale(1.05);}
footer{background:#081522;padding:15px;color:#ccc;text-align:center;font-size:14px;margin-top:30px;}
</style>
</head>
<body>

<header>GRAND ASIA</header>

<nav>
<button onclick="changeLang('uz')">UZ</button>
<button onclick="changeLang('en')">EN</button>
<button onclick="changeLang('ru')">RU</button>
<button onclick="changeLang('ko')">KO</button>
</nav>

<section id="hero">
<h2 data-uz="Osiyoni kashf eting!" data-en="Discover Asia!" data-ru="Откройте Азию!" data-ko="아시아를 발견하세요!">Osiyoni kashf eting!</h2>
<p data-uz="Biz sizning sayohatingizni unutilmas qilamiz 🌏 O‘zbekiston, Qozog‘iston va Tojikiston bo‘ylab tur paketlar."
   data-en="We make your trip unforgettable 🌏 Travel packages across Uzbekistan, Kazakhstan, and Tajikistan."
   data-ru="Мы сделаем ваше путешествие незабываемым 🌏 Турпакеты по Узбекистану, Казахстану и Таджикистану."
   data-ko="우리는 여행을 잊지 못하게 만들어드립니다 🌏 우즈베키스탄, 카자흐스탄, 타지키스탄 여행 패키지.">Biz sizning sayohatingizni unutilmas qilamiz 🌏 O‘zbekiston, Qozog‘iston va Tojikiston bo‘ylab tur paketlar.</p>
<button class="action" data-uz="Biz bilan bog‘lanish" data-en="Contact Us" data-ru="Свяжитесь с нами" data-ko="문의하기">Biz bilan bog‘lanish</button>
<p style="margin-top:15px;">📞 +998 90 008 94 09</p>
</section>

<section class="gallery">
<h2 data-uz="Galereya" data-en="Gallery" data-ru="Галерея" data-ko="갤러리">Galereya</h2>
<img src="https://images.unsplash.com/photo-1549887533-8e80bb76a929" alt="">
<img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" alt="">
<img src="https://images.unsplash.com/photo-1526779259212-2d1f3c49789b" alt="">
<img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b" alt="">
</section>

<footer>© 2026 GRAND ASIA. Barcha huquqlar himoyalangan.</footer>

<script>
function changeLang(lang){
    document.querySelectorAll('[data-uz]').forEach(el=>{
        el.innerText = el.getAttribute('data-'+lang);
    });
}
</script>

</body>
</html>
