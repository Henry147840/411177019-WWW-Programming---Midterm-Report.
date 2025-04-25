<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>廖詠兪 | 個人履歷網站</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Noto Sans TC', sans-serif;
      background-color: #f4f6f9;
      color: #333;
    }
    .navbar {
      padding: 1rem 0;
    }
    .navbar-brand {
      font-weight: bold;
      font-size: 1.25rem;
    }
    .hero {
      padding: 100px 0 60px;
      background-color: #fff;
      text-align: center;
    }
    .hero img {
      width: 160px;
      height: 160px;
      object-fit: cover;
      border-radius: 50%;
      margin-bottom: 20px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .hero h1 {
      font-weight: 700;
      font-size: 3rem;
    }
    .hero p {
      font-size: 1.2rem;
      color: #555;
    }
    section {
      padding: 60px 0;
    }
    .section-title {
      font-weight: 700;
      margin-bottom: 30px;
    }
    .skills span {
      display: inline-block;
      background: #dee2e6;
      padding: 8px 15px;
      margin: 6px;
      border-radius: 20px;
      font-size: 0.95rem;
    }
    .contact-form input, .contact-form textarea {
      margin-bottom: 15px;
    }
    footer {
      background: #fff;
      border-top: 1px solid #ddd;
      padding: 20px 0;
      color: #777;
    }
  </style>
</head>
<body>

<!-- 導覽列 -->
<nav class="navbar navbar-light bg-white shadow-sm fixed-top">
  <div class="container">
    <a class="navbar-brand" href="#">廖詠兪</a>
  </div>
</nav>

<!-- Hero 區塊 -->
<section class="hero">
  <div class="container">
    <img src="C:\Users\henry\Pictures\Saved Pictures\ajaxImageReader.jpg" alt="廖詠兪">
    <h1>你好，我是廖詠兪</h1>
    <p>一名前端開發學習者，致力於設計簡約、直覺且具有美感的網站介面。</p>
  </div>
</section>

<!-- 關於我 -->
<section class="bg-white">
  <div class="container">
    <h2 class="section-title">關於我</h2>
    <p>目前就讀於高雄師範大學軟體工程與管理學系，熱衷於前端技術與使用者體驗設計。專注於撰寫語意清晰的程式碼，並不斷學習新技術提升網站效能與美感。</p>
  </div>
</section>

<!-- 技能 -->
<section>
  <div class="container">
    <h2 class="section-title">技能</h2>
    <div class="skills">
      <span>HTML5</span>
      <span>CSS3</span>
      <span>JavaScript</span>
      <span>Bootstrap</span>
      <span>Git</span>
      <span>GitHub</span>
      <span>響應式設計</span>
    </div>
  </div>
</section>

<!-- 小功能展示區 (JavaScript) -->
<section class="bg-white">
  <div class="container text-center">
    <h2 class="section-title">互動小功能</h2>
    <p>點擊按鈕顯示問候語：</p>
    <button onclick="sayHello()" class="btn btn-success">Say Hello</button>
    <p id="greetText" class="mt-3 fw-bold"></p>
  </div>
</section>

<!-- 聯絡我 -->
<section>
  <div class="container">
    <h2 class="section-title">聯絡我</h2>
    <form class="contact-form">
      <div class="row">
        <div class="col-md-6">
          <input type="text" class="form-control" placeholder="姓名" required>
        </div>
        <div class="col-md-6">
          <input type="email" class="form-control" placeholder="電子信箱" required>
        </div>
      </div>
      <textarea class="form-control" rows="4" placeholder="留言內容" required></textarea>
      <button type="submit" class="btn btn-primary mt-3">送出</button>
    </form>
  </div>
</section>

<!-- Footer -->
<footer class="text-center">
  <div class="container">
    <p class="mb-0">© 2025 廖詠兪 | 所有權利保留</p>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
<script>
  function sayHello() {
    const message = "哈囉，歡迎來到我的網站！";
    document.getElementById('greetText').textContent = message;
  }
</script>
</body>
</html>
