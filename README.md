# The-Moment
Travel snippets

<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>我的旅行日誌</title>
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
        記錄走過的城市、遇見的人，<br>
        還有那些值得收藏的旅行時光。
      </p>
    </section>

    <section class="trips" id="trips">
      <h2>我的旅行故事</h2>
      <div class="trip-card">
        <h3>我的第一趟旅程</h3>
        <p>📍 在這裡寫下你去過的城市</p>
        <p>每一趟旅行，都是生活送給自己的禮物。</p>
      </div>
    </section>
  </main>

  <footer>Made with love & memories ♡</footer>
</body>
</html>
