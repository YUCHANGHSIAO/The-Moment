# The-Moment 

<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>還沒想到</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f8f5ef;
      color: #343b32;
    }

    header {
      padding: 24px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #fffdf8;
    }

    nav a {
      margin-left: 16px;
      color: #343b32;
      text-decoration: none;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
      background: #e6e9df;
    }

    .hero h1 {
      font-size: clamp(36px, 6vw, 64px);
      margin-bottom: 16px;
    }

    .hero p {
      font-size: 18px;
      line-height: 1.8;
    }

    .trips {
      padding: 48px 8%;
    }

    .trip-card {
      background: white;
      padding: 24px;
      border-radius: 16px;
      max-width: 500px;
      line-height: 1.8;
    }

    footer {
      text-align: center;
      padding: 30px;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <strong>MY TRAVEL JOURNAL</strong>
    <nav>
      <a href="#home">首頁</a>
      <a href="#trips">我的旅程</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <p>✈ A LITTLE JOURNAL OF MY LIFE</p>
      <h1>世界很大，慢慢去看。</h1>
      <p>
        記錄所走過的城市，<br>
        還有那些值得收藏的旅行片段。
      </p>
    </section>

    <section class="trips" id="trips">
      <h2>旅行</h2>
      <div class="trip-card">
        <h3>所有的起點</h3>
        <p>📍 香港,澳門,日本,柬埔寨,加拿大,美國,德國,奧地利,法國,韓國,波蘭,匈牙利,瑞典,比利時,英國,挪威,西班牙,克羅埃西亞,丹麥,希臘,卡達,義大利,芬蘭,愛沙尼亞,拉脱維亞,立陶宛,荷蘭,瑞士,梵蒂岡,阿爾巴尼亞,斯洛伐克,捷克,斯洛維尼亞,埃及,蒙特內哥羅,葡萄牙,保加利亞,羅馬尼亞,土耳其</p>
        <p>每一趟旅行，都是生活送給自己的禮物。</p>
      </div>
    </section>
  </main>

  <footer>Made with love & memories ♡</footer>
</body>
</html>
