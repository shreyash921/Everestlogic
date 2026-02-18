<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Everestlogic | Smart Deals Store</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin:0;
      font-family: Arial, sans-serif;
      background:#f4f4f4;
    }
    header {
      background:#111;
      color:white;
      text-align:center;
      padding:20px;
    }
    .products {
      display:grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap:20px;
      padding:20px;
    }
    .product-card {
      background:white;
      border-radius:10px;
      padding:15px;
      text-align:center;
      box-shadow:0 4px 8px rgba(0,0,0,0.1);
    }
    .product-card img {
      width:100%;
      height:200px;
      object-fit:cover;
      border-radius:10px;
    }
    button {
      background:#ff5722;
      color:white;
      border:none;
      padding:10px 15px;
      border-radius:5px;
      cursor:pointer;
    }
    button:hover { background:#e64a19; }
    footer {
      text-align:center;
      padding:15px;
      background:#111;
      color:white;
    }
  </style>
</head>
<body>

<header>
  <h1>Everestlogic</h1>
  <p>Smart Deals Store</p>
</header>

<section class="products">

  <!-- PRODUCT 1 -->
  <div class="product-card">
    <img src="https://images.meesho.com/images/products/xxxxxx.jpg" alt="New Bandages First Aid">
    <h3>New Bandages First Aid</h3>
    <p>Net Quantity: 1</p>
    <p>Dispatch: 2 Days</p>
    <a href="https://link.meesho.co/anmsan6phw" target="_blank">
      <button>Buy on Meesho</button>
    </a>
  </div>

  <!-- PRODUCT 2 (Optional) -->
  <div class="product-card">
    <img src="https://images.meesho.com/images/products/yyyyyy.jpg" alt="Product 2">
    <h3>Example Product 2</h3>
    <p>Details here</p>
    <p>Dispatch: 3 Days</p>
    <a href="https://link.meesho.co/example" target="_blank">
      <button>Buy on Meesho</button>
    </a>
  </div>

</section>

<footer>
  <p>This page contains affiliate links. We may earn commission at no extra cost to you.</p>
  <p>© 2026 Everestlogic</p>
</footer>

</body>
</html>
