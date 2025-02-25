<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <title>生日快乐🎂</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #ffeef5;
      padding-top: 80px;
    }
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    .message {
      font-size: 2em;
      color: #ff69b4;
      margin-bottom: 30px;
      animation: bounce 1.5s infinite;
    }
    button {
      padding: 12px 25px;
      font-size: 1.1em;
      border: none;
      border-radius: 10px;
      background-color: #ff69b4;
      color: #fff;
      cursor: pointer;
      transition: transform 0.2s;
    }
    button:hover {
      transform: scale(1.1);
    }
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="message">🎉亲爱的朋友，生日快乐🎂！</div>
    <button onclick="sendWish()">点我送祝福</button>
  </div>

  <script>
    function sendWish() {
      alert('🎈你的生日祝福已经送出啦！');
    }
  </script>
</body>
</html>
