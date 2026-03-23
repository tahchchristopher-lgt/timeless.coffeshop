<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Timeless Coffee Shop</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background-color: #f8f5f2;
      color: #3b2f2f;
    }
    header {
      background-color: #00a486;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-family: 'Playfair Display', serif;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      font-size: 1.1em;
      margin-top: 5px;
    }
    .menu {
      max-width: 900px;
      margin: 30px auto;
      padding: 20px;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .menu-section {
      margin-bottom: 30px;
    }
    .menu-section h2 {
      border-bottom: 3px solid #cc5500;
      padding-bottom: 5px;
      font-family: 'Playfair Display', serif;
      color: #5a3e36;
    }
    .item {
      display: flex;
      justify-content: space-between;
      padding: 10px 0;
      border-bottom: 1px dotted #ccc;
    }
    .item:last-child {
      border-bottom: none;
    }
    .item-name {
      font-weight: 600;
    }
    .item-price {
      color: #000000;
      font-weight: 700;
    }
    footer {
      text-align: center;
      padding: 15px;
      background-color: #00a486;
      color: #fff;
      font-size: 0.9em;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Timeless Coffee Shop</h1>
    <p>Take a sip,take a moment</p>
  </header>

  <div class="menu">
    <div class="menu-section">
      <center><h2> Hot drincks</h2></center>
      <div class="item"><span class="item-name">Espresso</span><span class="item-price">0.55$</span></div>
      <div class="item"><span class="item-name">Doppio</span><span class="item-price">1.1$</span></div>
      <div class="item"><span class="item-name">Nescafe</span><span class="item-price">1.1$</span></div>
      <div class="item"><span class="item-name">Cappuccino</span><span class="item-price">1.1$</span></div>
      <div class="item"><span class="item-name">Hot Chocolate</span><span class="item-price">3.88$</span></div>
      <div class="item"><span class="item-name">Tea</span><span class="item-price">0.55$</span></div>
    </div>
    <div class="menu-section">
      <center><h2>Cold drincks</h2></center>
      <div class="item"><span class="item-name">soft drincks</span><span class="item-price">1.1$</span></div>
      <div class="item"><span class="item-name">water</span><span class="item-price">0.55$</span></div>
      <div class="item"><span class="item-name">energy drinck</span><span class="item-price">1.1$</span></div>
      <div class="item"><span class="item-name">ice tea</span><span class="item-price">1.1$</span></div>
      <div class="item"><span class="item-name">beer</span><span class="item-price">1.5$</span></div>
      <div class="item"><span class="item-name">mexican beer</span><span class="item-price">3$</span></div>
      <div class="item"><span class="item-name">juice</span><span class="item-price">0.9$</span></div>
      <div class="item"><span class="item-name">Rim x fruit</span><span class="item-price">1.67$</span></div>
    </div>
    <div class="menu-section">
      <center><h2>fresh juice</h2></center>
      <div class="item"><span class="item-name">orange</span><span class="item-price">1.67$</span></div>
      <div class="item"><span class="item-name">carrot</span><span class="item-price">1.67$</span></div>
      <div class="item"><span class="item-name">lemon</span><span class="item-price">1.67$</span></div>
      <div class="item"><span class="item-name">avocado</span><span class="item-price">$</span></div>
      <div class="item"><span class="item-name">coctail</span><span class="item-price">$</span></div>
    </div>
    <div class="menu-section">
      <center><h2>Kaak</h2></center>
      <div class="item"><span class="item-name">Cheese</span><span class="item-price">2.22$</span></div>
      <div class="item"><span class="item-name">Picon</span><span class="item-price">1.67$</span></div>
      <div class="item"><span class="item-name">Ham and Cheese</span><span class="item-price">2.8$</span></div>
      <div class="item"><span class="item-name">Submarine</span><span class="item-price">4.4$</span></div>
      <div class="item"><span class="item-name">Halloumi Pesto</span><span class="item-price">4.4$</span></div>
      <div class="item"><span class="item-name">Labneh</span><span class="item-price">2.22$</span></div>
      <div class="item"><span class="item-name">Labneh and vegetables</span><span class="item-price">2.8$</span></div>
      <div class="item"><span class="item-name">Chocolate</span><span class="item-price">3.33$</span></div>
      <div class="item"><span class="item-name">Chocoba</span><span class="item-price">3.8$</span></div>
    </div>
     <div class="menu-section">
      <center><h2>Desserts</h2></center>
      <h4><div class="item"><span class="item-name">Cheesecake</span><span class="item-price">5$</span>
      </div>( oreo , lotus , kinder )</h4>
      <div class="item"><span class="item-name">Lazy cake</span><span class="item-price">4$</span></div>
      <div class="item"><span class="item-name">Tiramisu</span><span class="item-price">4$</span></div>
    </div>
   <div class="menu-section">
      <center><h2>shisha</h2></center>
      <div class="item"><span class="item-name">Shisha</span><span class="item-price">3.88$</span></div>
      <div class="item"><span class="item-name">Rass</span><span class="item-price">2.22$</span></div>
      <div class="item"><span class="item-name">Plastic Hose</span><span class="item-price">0.55$</span></div>
    </div>
  <div class="menu-section">
     <center><h2>Add-On</h2></center> 
      <div class="item"><span class="item-name">extra nestle</span><span class="item-price">0.55</span></div>
      <div class="item"><span class="item-name">extra cheese</span><span class="item-price">1.67</span></div>
      <div class="item"><span class="item-name">extra Chocolate</span><span class="item-price">1.1$</span></div>
    </div>
  </div>

  <footer>
    © 2025 Timeless Coffee Shop | Freshly Brewed Happiness Every Day
  </footer>

</body>
</html>
