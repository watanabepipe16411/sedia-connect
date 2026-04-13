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

/* 番号付き特徴 */
.feature{
display:flex;
gap:20px;
margin-bottom:30px;
align-items:flex-start;
}

.feature-number{
background:#ffcc00;
color:#000;
font-weight:bold;
font-size:24px;
width:60px;
height:60px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
flex-shrink:0;
}

.feature-text h3{
margin:0 0 10px;
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
<h2 class="title">セディアコネクトの特徴</h2>

<div class="feature">
<div class="feature-number">01</div>
<div class="feature-text">
<h3>施工店マッチング</h3>
セディアグループのネットワークから最適な施工店をご紹介します。
</div>
</div>

<div class="feature">
<div class="feature-number">02</div>
<div class="feature-text">
<h3>元請案件のご紹介</h3>
新しい元請会社との取引機会を創出します。
</div>
</div>

<div class="feature">
<div class="feature-number">03</div>
<div class="feature-text">
<h3>安心の補償制度</h3>
セディア・コネクト内でマッチングした工事に限り、対物事故1000万円まで補償れさます。<br>
  ※補償には事前の申請が必要となります。
</div>
</div>

<div class="feature">
<div class="feature-number">04</div>
<div class="feature-text">
<h3>入会金・年会費無料</h3>
費用負担なく導入可能です。
</div>
</div>

</section>

<section class="section-dark section">
<h2>まずはお気軽にお問い合わせください</h2>
<p>サービス詳細をご案内いたします</p>

<a href="https://example.com/contact" class="big-cta">
今すぐ問い合わせる
</a>

</section>

<footer>
© SEDIA CONNECT
</footer>

</body>
</html>
