# Everestlogic
Welcome to Smart Deals Store – your trusted destination for the best Amazon, Flipkart and Meesho deals.   We help you find trending products, budget gadgets, fashion items, and daily use essentials at the lowest prices.   We are an affiliate website. When you purchase through our links, we may earn a small commission at no extra cost to you.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Everestlogic | Smart Deals Store</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
    }

    header {
      background: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: white;
      border-radius: 10px;
      padding: 15px;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }

    .price {
      color: green;
      font-size: 18px;
    }

    .price del {
      color: gray;
      font-size: 14px;
    }

    button {
      background: #ff5722;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background: #e64a19;
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>

<body>

<header>
  <h1>Everestlogic</h1>
  <p>Smart Deals Store</p>
</header>

<section class="products">

  <div class="card">
    <img src="https://images.unsplash.com/photo-1585386959984-a4155224a1ad">
    <h3>Wireless Headphones</h3>
    <p class="price">₹2,499 <del>₹4,999</del></p>
    <a href="PASTE_AFFILIATE_LINK_HERE" target="_blank">
      <button>Buy Now</button>
    </a>
  </div>

  <div class="card">
    <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30">
    <h3>Smart Watch</h3>
    <p class="price">₹1,999 <del>₹3,999</del></p>
    <a href="PASTE_AFFILIATE_LINK_HERE" target="_blank">
      <button>Buy Now</button>
    </a>
  </div>

  <div class="card">
    <img src="https://images.unsplash.com/photo-1583225214464-9296029427aa">
    <h3>Running Shoes</h3>
    <p class="price">₹1,499 <del>₹2,999</del></p>
    <a href="PASTE_AFFILIATE_LINK_HERE" target="_blank">
      <button>Buy Now</button>
    </a>
  </div>

</section>

<footer>
  <p>Affiliate Disclosure: We may earn commission from qualifying purchases at no extra cost to you.</p>
  <p>© 2026 Everestlogic</p>
</footer>

</body>
</html>
