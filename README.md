<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>فروشگاه الکترونیکی پناه</title>
  <style>
    body {
      font-family: 'Vazir', sans-serif;
      direction: rtl;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #1e90ff;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .hero {
      padding: 40px 20px;
      text-align: center;
      background-color: #e0f0ff;
    }
    .hero h1 {
      margin-bottom: 10px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background-color: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #1e90ff;
      color: white;
      border-radius: 5px;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 15px;
      background-color: #333;
      color: white;
    }
  </style>
</head>
<body>

  <header>
    <h1>فروشگاه پناه</h1>
    <p>مرجع تخصصی خرید لوازم الکترونیکی با بهترین قیمت</p>
  </header>

  <div class="hero">
    <h1>به فروشگاه پناه خوش آمدید</h1>
    <p>انواع بردهای آردوینو، ماژول‌ها، سنسورها و تجهیزات الکترونیکی با کیفیت بالا و قیمت مناسب</p>
    <a href="#products" class="btn">مشاهده محصولات</a>
  </div>

  <div class="products" id="products">
    <div class="product">
      <img src="https://example.com/arduino.jpg" alt="برد آردوینو">
      <h3>برد آردوینو UNO R3</h3>
      <p>قیمت: ۳۲۰,۰۰۰ تومان</p>
      <a href="#" class="btn">خرید</a>
    </div>
    <div class="product">
      <img src="https://example.com/sensor.jpg" alt="ماژول سنسور">
      <h3>ماژول سنسور دما DHT11</h3>
      <p>قیمت: ۵۵,۰۰۰ تومان</p>
      <a href="#" class="btn">خرید</a>
    </div>
    <div class="product">
      <img src="https://example.com/power.jpg" alt="ماژول تغذیه">
      <h3>ماژول تغذیه MB102</h3>
      <p>قیمت: ۷۰,۰۰۰ تومان</p>
      <a href="#" class="btn">خرید</a>
    </div>
  </div>

  <footer>
    <p>تمامی حقوق محفوظ است - فروشگاه پناه © 2025</p>
  </footer>

</body>
</html>
