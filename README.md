# self_o
おりがめ、じこしょうかいします！
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>🌸 わたしの紅茶ページ 🌸</title>
  <style>
    body {
      font-family: 'Hiragino Kaku Gothic ProN', sans-serif;
      background: linear-gradient(to bottom, #fffaf5, #ffeedd);
      color: #4b2e2e;
      text-align: center;
      padding: 50px;
      overflow: hidden;
    }
    h1 {
      font-size: 3em;
      color: #c46210;
      text-shadow: 1px 1px 2px #ffc0cb;
    }
    p, .tea {
      font-size: 1.3em;
      margin-top: 20px;
      line-height: 1.8;
    }
    .tea {
      color: #865b42;
    }
    img {
      margin-top: 30px;
      width: 250px;
      border-radius: 15px;
      box-shadow: 0 0 10px rgba(255, 192, 203, 0.6);
    }
    footer {
      margin-top: 40px;
      font-size: 1em;
      color: #a67c52;
    }

    /* アニメーションスタイル */
    .floating-tea {
      font-size: 2.5em;
      position: absolute;
      animation: float 5s ease-in-out infinite;
    }
    .tea1 { top: 10%; left: 10%; animation-delay: 0s; }
    .tea2 { top: 40%; left: 80%; animation-delay: 1s; }
    .tea3 { top: 70%; left: 20%; animation-delay: 2s; }
    .tea4 { top: 20%; left: 60%; animation-delay: 3s; }
    .tea5 { top: 60%; left: 40%; animation-delay: 4s; }

    @keyframes float {
      0%   { transform: translateY(0px) rotate(0deg); opacity: 1; }
      50%  { transform: translateY(-20px) rotate(10deg); opacity: 0.8; }
      100% { transform: translateY(0px) rotate(0deg); opacity: 1; }
    }
  </style>
</head>
<body>
  <h1>✨🍰 Welcome to my Tea World! ☕✨</h1>

  <p>こんにちは〜！origa-meです🌸🌈<br>  
  このページを見つけてくれてありがとう〜💖</p>

  <div class="tea">
    ☕🌿 わたしは <strong>紅茶だいすき人間</strong> です！！ 🌿☕<br>
    💫 ホットティーも アイスティーも大歓迎！<br>
    💕 ダージリン、アールグレイ、アッサム…どれも好き〜！<br>
    🫖 お気に入りのカップでのんびりする時間が宝物です✨<br>
    🍓 お茶菓子といっしょに楽しむのも最高〜〜！🍪💞
  </div>

  <img src="https://upload.wikimedia.org/wikipedia/commons/5/52/Tea_in_Porcelain_Cup.jpg" alt="紅茶カップの写真">

  <footer>
    🌟 紅茶とともに、今日もすてきな1日を〜 🌟<br>
    💌 また遊びにきてね♪
  </footer>

  <!-- ☕️アイコンがふわふわ〜 -->
  <div class="floating-tea tea1">🫖</div>
  <div class="floating-tea tea2">🍵</div>
  <div class="floating-tea tea3">☕</div>
  <div class="floating-tea tea4">🫖</div>
  <div class="floating-tea tea5">🍵</div>
</body>
</html>
