<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <title>生日快乐</title>
  <style>
    body {
      font-family: sans-serif;
      text-align: center;
      background-color: #fffbf0;
      padding-top: 100px;
    }
    .message {
      font-size: 24px;
      animation: scaleAnimation 1.2s infinite;
    }
    @keyframes scaleAnimation {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
    button {
      margin-top: 30px;
      padding: 10px 20px;
      font-size: 18px;
      border: none;
      background: #ffafcc;
      color: #fff;
      cursor: pointer;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <div class="message">🎂 亲爱的朋友，生日快乐！愿你开心每一天～</div>
  <button onclick="sendWish()">送出祝福</button>
  
  <script>
    function sendWish() {
      alert('你的祝福已送出～');
    }
  </script>
</body>
</html>
