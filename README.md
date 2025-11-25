<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>Flickxzi Header</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      background: transparent;
      font-family: sans-serif;
    }

    .header {
      width: 100%;
      height: 70px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0 20px;
      box-sizing: border-box;
      background: rgba(0, 0, 0, 0.6);
    }

    .logo img {
      width: 100px;
      height: auto;
      transform: scale(1.4);
      transform-origin: left center;
    }

    .buttons {
      display: flex;
      gap: 10px;
    }

    .btn {
      padding: 8px 16px;
      border-radius: 6px;
      font-size: 14px;
      font-weight: bold;
      text-decoration: none;
      color: #fff;
      display: flex;
      align-items: center;
      gap: 6px;
    }

    .btn img {
      width: 18px;
      height: 18px;
    }

    .btn.green {
      background-color: #00c300;
    }

    .btn.orange {
      background-color: #f5511e;
    }
  </style>
</head>
<body>
  <div class="header">
    <div class="logo">
      <!-- โลโก้ของคุณ -->
      <img src="https://i.postimg.cc/2SSHL0Px/Untitled-design.png" alt="Flickxzi Logo">
    </div>

    <div class="buttons">
      <!-- ลิงก์ไลน์ของคุณ (สมัคร + เข้าสู่ระบบ) -->
      <a href="https://line.me/R/ti/p/~@313wsohw?utm_medium=social&utm_source=heylink.me"
         class="btn green" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111728.png" alt="LINE">
        สมัครสมาชิก
      </a>

      <a href="https://line.me/R/ti/p/~@313wsohw?utm_medium=social&utm_source=heylink.me"
         class="btn orange" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/1828/1828490.png" alt="Login">
        เข้าสู่ระบบ
      </a>
    </div>
  </div>
</body>
</html>
