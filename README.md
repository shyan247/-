# -<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>فروشگاه عطر شیک</title>
  <style>
    body {
      margin: 0;
      font-family: 'Tahoma', sans-serif;
      background-color: #111;
      color: #fff;
    }

    header {
      background-color: #000;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid gold;
    }

    header h1 {
      margin: 0;
      font-size: 2em;
      color: gold;
    }

    nav {
      background-color: #222;
      display: flex;
      justify-content: center;
      padding: 10px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      color: gold;
    }

    .hero {
      background-image: url('https://example.com/perfume-banner.jpg');
      background-size: cover;
      background-position: center;
      height: 350px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .hero h2 {
      background-color: rgba(0, 0, 0, 0.6);
      padding: 20px;
      font-size: 2em;
      color: gold;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 40px 20px;
    }

    .product {
      background-color: #222;
      border: 1px solid gold;
      margin: 10px;
      padding: 20px;
      width: 220px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(255,215,0,0.2);
    }

    .product img {
      width: 100%;
      height: auto;
    }

    .product h3 {
      color: gold;
    }

    .product p {
      color: #ccc;
    }

    .product a button {
      background-color: gold;
      color: black;
      border: none;
      padding: 10px;
      cursor: pointer;
      border-radius: 5px;
    }

    .product a button:hover {
      background-color: #f1c40f;
    }

    footer {
      background-color: #000;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #aaa;
      border-top: 1px solid gold;
    }
  </style>
</head>
<body>

  <header>
    <h1>فروشگاه عطر شیک</h1>
  </header>

  <nav>
    <a href="#">خانه</a>
    <a href="#">محصولات</a>
    <a href="#">درباره ما</a>
    <a href="#">تماس با ما</a>
  </nav>

  <div class="hero">
    <h2>عطرهایی که خاطره می‌سازند</h2>
  </div>

  <section class="products">
    <div class="product">
      <img src="https://example.com/perfume1.jpg" alt="عطر ۱">
      <h3>عطر رز طلایی</h3>
      <p>قیمت: ۵۰۰٬۰۰۰ تومان</p>
      <a href="https://payping.ir/YOURUSERNAME" target="_blank">
        <button>پرداخت آنلاین</button>
      </a>
    </div>
    <div class="product">
      <img src="https://example.com/perfume2.jpg" alt="عطر ۲">
      <h3>عطر شب مشکی</h3>
      <p>قیمت: ۶۲۰٬۰۰۰ تومان</p>
      <a href="https://payping.ir/YOURUSERNAME" target="_blank">
        <button>پرداخت آنلاین</button>
      </a>
    </div>
    <!-- محصولات بیشتر -->
  </section>

  <footer>
    © ۲۰۲۵ فروشگاه عطر شیک | تماس: info@luxperfume.ir
  </footer>

</body>
</html>https://images.unsplash.com/photo-1600180758890-3c5f3f6e6b2b?auto=format&fit=crop&w=500&q=80
