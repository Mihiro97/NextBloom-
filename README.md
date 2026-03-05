# NextBloom-
uploading an existing file
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NextBloom</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;600&display=swap" rel="stylesheet">
<style>
body {
    margin: 0;
    font-family: 'Noto Sans JP', sans-serif;
    background: #0f0f14;
    color: #ffffff;
    line-height: 1.8;
}

section {
    padding: 80px 20px;
    max-width: 900px;
    margin: auto;
}

h1, h2 {
    font-weight: 600;
    letter-spacing: 1px;
}

.hero {
    height: 100vh;
    background: url('hero.jpg') center/cover no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    position: relative;
}

.hero::after {
    content: "";
    position: absolute;
    inset: 0;
    background: rgba(0,0,0,0.5);
}

.hero-content {
    position: relative;
    z-index: 2;
}

.hero h1 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero p {
    font-size: 18px;
    opacity: 0.9;
}

.small {
    font-size: 14px;
    opacity: 0.7;
}

.gallery img {
    width: 100%;
    margin-bottom: 30px;
    border-radius: 4px;
}

.voice {
    background: #151520;
    padding: 60px 20px;
}

.voice p {
    margin-bottom: 20px;
    opacity: 0.9;
}

.footer {
    text-align: center;
    padding: 60px 20px;
    font-size: 14px;
    opacity: 0.6;
}

a {
    color: #ffffff;
    text-decoration: none;
    border-bottom: 1px solid rgba(255,255,255,0.3);
}

a:hover {
    opacity: 0.7;
}
</style>
</head>

<body>

<!-- HERO -->
<div class="hero">
  <div class="hero-content">
    <h1>NextBloom</h1>
    <p>ここは、みんなでつくる。</p>
    <p>はじめてでも、大丈夫。<br>気づいたら、行きたくなる一日。</p>
    <p class="small">2026.11.15<br>at CASINO★DRIVE（旭川）</p>
  </div>
</div>

<!-- CONCEPT -->
<section>
  <h2>CONCEPT</h2>
  <p>
    ライブハウスに行く文化を、高校生の間に。<br>
    音楽やお笑いを、もっと身近に。
  </p>
  <p>高校生一部無料。</p>
</section>

<!-- ABOUT -->
<section>
  <h2>この場所について。</h2>
  <p>
    NextBloomは、旭川市の高校生がつくるイベントです。<br><br>
    ステージに立つ人。<br>
    フロアで音を浴びる人。<br>
    その日、その空間にいる全員で、はじめてNextBloomになる。<br><br>
    ライブハウスが初めてでもいい。<br>
    ひとりで来てもいい。<br><br>
    誰かの人生が、ほんの少し動き出す。<br>
    そんな一日になれたら嬉しい。
  </p>
</section>

<!-- STORY -->
<section>
  <h2>はじめての話</h2>
  <p>
    暗くて、音が大きくて、最初はちょっとびっくりした。<br>
    でもその瞬間から、わくわくが止まらなかった。<br><br>
    照明も、最初の一音も、全部覚えている。<br>
    あの日から、ライブが大好きになった。<br><br>
    だから今度は、誰かにとっての“はじめて”をつくりたい。
  </p>
</section>

<!-- GALLERY -->
<section class="gallery">
  <h2>GALLERY</h2>
  <img src="photo1.jpg" alt="会場の様子">
  <img src="photo2.jpg" alt="ライブ風景">
  <img src="photo3.jpg" alt="観客の様子">
</section>

<!-- VOICE -->
<section class="voice">
  <h2>VOICE</h2>
  <p>「思ってたより、ずっと楽しかった。」</p>
  <p>「音が鳴った瞬間、鳥肌が立った。」</p>
  <p>「また来たいって、自然に思えた。」</p>
</section>

<!-- SPONSOR -->
<section>
  <h2>SPONSOR</h2>
  <p>
    NextBloomは高校生主体で運営しています。<br>
    この挑戦を未来へ続けるため、共に支えてくださる企業様を募集しています。
  </p>
  <p>前回協賛：株式会社セコマ 様</p>
</section>

<!-- CONTACT -->
<section>
  <h2>CONTACT</h2>
  <p>お問い合わせ：<br>
  <a href="mailto:nextbloom1115@gmail.com">nextbloom1115@gmail.com</a></p>
  <p>Instagram：<br>
  <a href="https://www.instagram.com/next_bloom1214" target="_blank">@next_bloom1214</a></p>
</section>

<div class="footer">
  NextBloom © 2026<br>
  旭川市高校生企画・運営
</div>

</body>
</html>
