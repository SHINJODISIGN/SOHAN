# SOHAN
-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Black & White Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff;
      color: #000;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 20px;
      background-color: #000;
      color: #fff;
    }
    .logo {
      font-size: 24px;
      font-weight: bold;
    }
    nav {
      display: flex;
      gap: 20px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-size: 16px;
      padding: 5px 10px;
      transition: background-color 0.3s ease;
    }
    nav a:hover {
      background-color: #fff;
      color: #000;
      border-radius: 5px;
    }
    .cart {
      font-size: 16px;
      cursor: pointer;
    }
    .cart:hover {
      color: #999;
    }
    main {
      padding: 20px;
      text-align: center;
    }
    .button {
      background-color: #000;
      color: #fff;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .button:hover {
      background-color: #fff;
      color: #000;
      border: 1px solid #000;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">My Brand</div>
    <nav>
      <a href="#home">หน้าแรก</a>
      <a href="#products">สินค้า</a>
      <a href="#about">เกี่ยวกับเรา</a>
      <a href="#contact">ติดต่อเรา</a>
    </nav>
    <div class="cart">🛒 ตะกร้าสินค้า</div>
  </header>
  <main>
    <h1>ยินดีต้อนรับสู่เว็บไซต์ของเรา</h1>
    <p>เลือกชมสินค้าของเราได้ที่เมนูด้านบน</p>
    <button class="button">ดูสินค้า</button>
  </main>
</body>
</html>
