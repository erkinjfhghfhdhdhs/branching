<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>15amlaiy mashfdfk</title>
</head>
<body>
<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>1-IYUN | Bolalar Bayrami</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:#07111f;
    color:white;
    overflow-x:hidden;
}

/* ================= HEADER ================= */

header{
    width:100%;
    height:100vh;
    position:relative;
    background:
    linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.6)),
    url('https://images.unsplash.com/photo-1516627145497-ae6968895b74?q=80&w=2070&auto=format&fit=crop')
    center/cover no-repeat;

    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
}

.overlay{
    position:absolute;
    width:100%;
    height:100%;
    background:linear-gradient(to top,#07111f 5%,transparent);
}

.hero{
    position:relative;
    z-index:5;
    max-width:1000px;
}

.hero h1{
    font-size:90px;
    font-weight:800;
    line-height:1.1;
    margin-bottom:25px;
    text-shadow:0 0 30px rgba(255,255,255,.4);
    animation:fadeDown 1.5s ease;
}

.hero span{
    color:#ffd43b;
}

.hero p{
    font-size:22px;
    line-height:1.8;
    margin-bottom:35px;
    color:#ddd;
    animation:fadeUp 2s ease;
}

.hero-btn{
    display:inline-block;
    padding:18px 45px;
    background:#ffd43b;
    color:#111;
    border-radius:60px;
    font-size:20px;
    font-weight:700;
    text-decoration:none;
    transition:.4s;
    box-shadow:0 10px 40px rgba(255,212,59,.4);
}

.hero-btn:hover{
    transform:translateY(-8px) scale(1.05);
    background:white;
}

/* ================= FLOATING BALLS ================= */

.ball{
    position:absolute;
    border-radius:50%;
    opacity:.4;
    animation:float 8s infinite linear;
}

.ball1{
    width:120px;
    height:120px;
    background:#ff4d6d;
    top:10%;
    left:5%;
}

.ball2{
    width:80px;
    height:80px;
    background:#38bdf8;
    top:70%;
    left:10%;
}

.ball3{
    width:100px;
    height:100px;
    background:#ffd43b;
    right:10%;
    top:15%;
}

.ball4{
    width:70px;
    height:70px;
    background:#7c3aed;
    right:15%;
    bottom:15%;
}

@keyframes float{
    0%{transform:translateY(0px);}
    50%{transform:translateY(-25px);}
    100%{transform:translateY(0px);}
}

/* ================= ABOUT ================= */

.about{
    padding:120px 10%;
    display:flex;
    align-items:center;
    gap:80px;
    flex-wrap:wrap;
}

.about-image{
    flex:1;
}

.about-image img{
    width:100%;
    border-radius:30px;
    box-shadow:0 20px 60px rgba(0,0,0,.5);
}

.about-text{
    flex:1;
}

.about-text h2{
    font-size:55px;
    margin-bottom:25px;
}

.about-text p{
    font-size:20px;
    line-height:2;
    color:#ccc;
}

/* ================= CARDS ================= */

.cards{
    padding:100px 10%;
    background:#0b1727;
}

.section-title{
    text-align:center;
    margin-bottom:70px;
}

.section-title h2{
    font-size:60px;
}

.card-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:30px;
}

.card{
    background:#111d30;
    border-radius:25px;
    padding:40px 30px;
    transition:.5s;
    position:relative;
    overflow:hidden;
}

.card:hover{
    transform:translateY(-15px);
    box-shadow:0 20px 50px rgba(0,0,0,.5);
}

.card::before{
    content:'';
    position:absolute;
    width:100%;
    height:5px;
    left:0;
    top:0;
    background:linear-gradient(to right,#ffd43b,#ff4d6d);
}

.card h3{
    font-size:28px;
    margin-bottom:20px;
}

.card p{
    color:#ccc;
    line-height:1.9;
}

/* ================= GALLERY ================= */

.gallery{
    padding:120px 10%;
}

.gallery-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}

.gallery-grid img{
    width:100%;
    height:320px;
    object-fit:cover;
    border-radius:25px;
    transition:.5s;
}

.gallery-grid img:hover{
    transform:scale(1.05);
}

/* ================= TIMER ================= */

.timer{
    padding:120px 10%;
    text-align:center;
    background:linear-gradient(to right,#111827,#0f172a);
}

.timer h2{
    font-size:60px;
    margin-bottom:40px;
}

.countdown{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:30px;
}

.time-box{
    width:180px;
    padding:40px 20px;
    border-radius:25px;
    background:#172437;
    box-shadow:0 10px 40px rgba(0,0,0,.4);
}

.time-box h3{
    font-size:55px;
    color:#ffd43b;
}

.time-box span{
    color:#bbb;
    font-size:18px;
}

/* ================= FOOTER ================= */

footer{
    padding:40px;
    text-align:center;
    background:#08101d;
    color:#aaa;
}

/* ================= ANIMATIONS ================= */

@keyframes fadeDown{
    from{
        opacity:0;
        transform:translateY(-60px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

@keyframes fadeUp{
    from{
        opacity:0;
        transform:translateY(60px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

/* ================= RESPONSIVE ================= */

@media(max-width:900px){

    .hero h1{
        font-size:55px;
    }

    .hero p{
        font-size:18px;
    }

    .about{
        flex-direction:column;
    }

    .section-title h2,
    .timer h2,
    .about-text h2{
        font-size:40px;
    }

}

</style>
</head>

<body>

<!-- ================= HERO ================= -->

<header>

<div class="overlay"></div>

<div class="ball ball1"></div>
<div class="ball ball2"></div>
<div class="ball ball3"></div>
<div class="ball ball4"></div>

<div class="hero">
    <h1>1-IYUN <br><span>BOLALAR BAYRAMI</span></h1>

    <p>
        Har bir bolaning kulgusi — dunyoning eng go‘zal ovozi.
        1-IYUN — mehr, quvonch va baxt ulashadigan kun.
    </p>

    <a href="#about" class="hero-btn">Boshlash</a>
</div>

</header>

<!-- ================= ABOUT ================= -->

<section class="about" id="about">

<div class="about-image">
<img src="https://images.unsplash.com/photo-1503454537195-1dcabb73ffb9?q=80&w=1200&auto=format&fit=crop">
</div>

<div class="about-text">
<h2>Bolalar — Bizning Kelajagimiz</h2>

<p>
Bolalar qalbi beg‘ubor va toza bo‘ladi.
Shuning uchun ham 1-IYUN butun dunyoda eng quvonchli bayramlardan biri hisoblanadi.
Bu kun bolalarga mehr, sovg‘a va tabassum ulashiladi.
</p>

</div>

</section>

<!-- ================= CARDS ================= -->

<section class="cards">

<div class="section-title">
<h2>Bayramning Go‘zalligi</h2>
</div>

<div class="card-grid">

<div class="card">
<h3>🎉 Quvonch</h3>
<p>
Bolalar kulgisi har qanday joyni yorqin va chiroyli qiladi.
</p>
</div>

<div class="card">
<h3>🎁 Sovg‘alar</h3>
<p>
1-IYUN kuni bolalar uchun turli tadbirlar va sovg‘alar tashkil qilinadi.
</p>
</div>

<div class="card">
<h3>❤️ Mehr</h3>
<p>
Bu kun bolalarga mehr va e’tibor ko‘rsatish kuni hisoblanadi.
</p>
</div>

</div>

</section>

<!-- ================= GALLERY ================= -->

<section class="gallery">

<div class="section-title">
<h2>Bayram Galereyasi</h2>
</div>

<div class="gallery-grid">

<img src="https://images.unsplash.com/photo-1516627145497-6c2d52f4c7a5?q=80&w=1200&auto=format&fit=crop">

<img src="https://images.unsplash.com/photo-1509099836639-18ba1795216d?q=80&w=1200&auto=format&fit=crop">

<img src="https://images.unsplash.com/photo-1516627145497-ae6968895b74?q=80&w=1200&auto=format&fit=crop">

</div>

</section>

<!-- ================= TIMER ================= -->

<section class="timer">

<h2>1-IYUNGA QOLGAN VAQT</h2>

<div class="countdown">

<div class="time-box">
<h3 id="days">00</h3>
<span>KUN</span>
</div>

<div class="time-box">
<h3 id="hours">00</h3>
<span>SOAT</span>
</div>

<div class="time-box">
<h3 id="minutes">00</h3>
<span>MINUT</span>
</div>

<div class="time-box">
<h3 id="seconds">00</h3>
<span>SEKUND</span>
</div>

</div>

</section>

<!-- ================= FOOTER ================= -->

<footer>
<h3>© 2026 | 1-IYUN BAYRAM WEBSITE</h3>
</footer>

<script>

const target = new Date("June 1, 2026 00:00:00").getTime();

setInterval(() => {

const now = new Date().getTime();

const distance = target - now;

const days = Math.floor(distance / (1000 * 60 * 60 * 24));
const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
const seconds = Math.floor((distance % (1000 * 60)) / 1000);

document.getElementById("days").innerHTML = days;
document.getElementById("hours").innerHTML = hours;
document.getElementById("minutes").innerHTML = minutes;
document.getElementById("seconds").innerHTML = seconds;

},1000);

</script>

</body>
</html>
</body>
</html>
