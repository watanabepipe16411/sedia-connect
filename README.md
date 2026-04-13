<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>セディアコネクト</title>

<style>
body{
margin:0;
font-family: "Helvetica Neue", Arial, sans-serif;
color:#333;
}

.hero{
background:linear-gradient(135deg,#000,#555);
color:#fff;
padding:100px 20px 140px;
text-align:center;
position:relative;
overflow:hidden;
}

.hero:after{
content:"";
position:absolute;
bottom:-1px;
left:0;
width:100%;
height:80px;
background:#fff;
clip-path:polygon(0 0,100% 100%,0 100%);
}

.hero h1{
font-size:42px;
margin-bottom:15px;
}

.hero p{
font-size:18px;
opacity:.9;
}

.cta{
margin-top:30px;
}

.cta a{
background:#ffcc00;
color:#000;
padding:16px 40px;
border-radius:6px;
font-weight:bold;
text-decoration:none;
}

.section{
padding:80px 20px;
max-width:1100px;
margin:auto;
}

.section-gray{
background:#f7f7f7;
}

.section-dark{
background:#000;
color:#fff;
text-align:center;
}

.title{
text-align:center;
font-size:28px;
margin-bottom:50px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:#fff;
padding:30px;
border-radius:12px;
box-shadow:0 8px 20px rgba(0,0,0,.08);
text-align:center;
}

.section-gray .card{
background:#fff;
}

.step{
display:flex;
justify-content:space-between;
flex-wrap:wrap;
gap:20px;
}

.step-box{
flex:1;
min-width:250px;
background:#fff;
padding:30px;
border-radius:12px;
box-shadow:0 8px 20px rgba(0,0,0,.08);
text-align:center;
position:relative;
}

.step-number{
font-size:40px;
font-weight:bold;
color:#ffcc00;
margin-bottom:10px;
}

.big-cta{
background:#ffcc00;
color:#000;
padding:20px 60px;
font-size:20px;
font-weight:bold;
border-radius:8px;
display:inline-block;
text-decoration:none;
margin-top:20px;
}

footer{
background:#111;
color:#aaa;
text-align:center;
padding:20px;
}
</style>
</head>

<body>

<section class="hero">
<h1>セディアコネクト</h1>
<p>施工店ネットワークで仕事の機会を創出</p>

<div class="cta">
<a href="https://example.com/contact">無料で問い合わせ</a>
</div>
</section>

<section class="section">
<h2 class="title">こんなお悩みありませんか？</h2>

<div class="grid">
<div class="card">施工店が見つからない</div>
<div class="card">案件が回らない</div>
<div class="card">新規取引先を増やしたい</div>
<div class="card">遠方現場に対応したい</div>
</div>
</section>

<section class="section section-gray">
<h2 class="title">セディアコネクトの特長</h2>

<div class="grid">
<div class="card">全国施工店ネットワーク</div>
<div class="card">元請案件紹介</div>
<div class="card">安心補償付き</div>
<div class="card">入会金・年会費無料</div>
</div>
</section>

<section class="section">
<h2 class="title">ご利用の流れ</h2>

<div class="step">
<div class="step-box">
<div class="step-number">01</div>
お問い合わせ
</div>

<div class="step-box">
<div class="step-number">02</div>
サービス説明
</div>

<div class="step-box">
<div class="step-number">03</div>
マッチング開始
</div>
</div>

</section>

<section class="section-dark section">
<h2>まずはお気軽にお問い合わせください</h2>
<p>無料でご案内いたします</p>

<a href="https://example.com/contact" class="big-cta">
今すぐ問い合わせる
</a>

</section>

<footer>
© SEDIA CONNECT
</footer>

</body>
</html>
