<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Noorain Skincare & Cosmetics</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: linear-gradient(to bottom, #fff6f7, #ffe6eb);
      background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="200" height="200"><text y="100" x="100" font-size="24" text-anchor="middle" fill="%23ff8cb7">🌸</text></svg>');
      background-repeat: repeat;
      color: #4b2c2c;
    }
    header {
      background-color: #f9e6e8;
      padding: 1.5rem;
      text-align: center;
    }
    .logo {
      max-width: 160px;
    }
    nav {
      background: #ffe3e3;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem 0;
      font-weight: bold;
    }
    .hero {
      background: #fff0f3;
      text-align: center;
      padding: 3rem 1rem;
    }
    .hero h1 {
      font-size: 2.5rem;
      color: #a33658;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }
    .product {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
      padding: 1rem;
    }
    .product img {
      width: 100%;
      max-height: 250px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product h3 {
      color: #aa3c51;
      margin-top: 1rem;
    }
    .product button {
      margin: 0.5rem;
      padding: 0.5rem 1rem;
      border: none;
      background-color: #f49ab0;
      color: white;
      border-radius: 8px;
      cursor: pointer;
    }
    .product button:hover {
      background-color: #d86c8c;
    }
    .section-title {
      text-align: center;
      margin-top: 3rem;
      font-size: 2rem;
      color: #c83b6f;
    }
    .social-icons a {
      margin: 0 10px;
      color: #a33658;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      background: #fce4ec;
      text-align: center;
      padding: 2rem 1rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="YOUR_LOGO_URL_HERE" alt="Noorain Logo" class="logo" />
  </header>
  <nav>
    <a href="#shop">Shop</a>
    <a href="#about">About</a>
    <a href="#blog">Blog</a>
    <a href="#checkout">Checkout</a>
    <a href="#policy">Shipping & Returns</a>
  </nav>
  <section class="hero">
    <h1>Glow Naturally with Noorain 🌸</h1>
    <p>Handcrafted skincare powered by nature, designed for confidence and love.</p>
  </section>  <h2 class="section-title" id="shop">Shop All Products</h2>
  <section class="products" id="products"></section>  <h2 class="section-title" id="about">Founder Story & Vision</h2>
  <section style="padding: 2rem; max-width: 800px; margin: auto;">
    <p>I created Noorain Skincare & Cosmetics to offer safe, effective, natural skincare that promotes confidence, peace, and self-love. Handcrafted in small batches, our products serve both men and women with love and care.</p>
  </section>  <h2 class="section-title" id="blog">Skincare Blog</h2>
  <section style="padding: 2rem; max-width: 800px; margin: auto;">
    <p>Learn how to build the perfect skincare routine using our brightening night cream, gentle ricecream facewash, and SPF 50 sunscreen. Stay tuned for tips, tricks, and glowing skin secrets!</p>
  </section>  <h2 class="section-title" id="checkout">Checkout</h2>
  <section style="padding: 2rem; max-width: 600px; margin: auto;">
    <form>
      <input type="text" placeholder="Full Name" required><br><br>
      <input type="text" placeholder="Shipping Address" required><br><br>
      <input type="text" placeholder="Phone Number" required><br><br>
      <p>Pay via UPI: <strong>7972530698@okbizaxis</strong></p>
      <button type="submit">Confirm Order</button>
    </form>
  </section>  <h2 class="section-title" id="policy">Shipping & Return Policy</h2>
  <section style="padding: 2rem; max-width: 800px; margin: auto;">
    <p>We ship across India within 3-5 business days. Due to the nature of skincare products, we do not accept returns unless an item is damaged or incorrect. For assistance, contact us at nooraincosmetics@gmail.com.</p>
  </section>  <footer>
    <p>📞 WhatsApp: <a href="https://wa.me/message/FCDYEGMJYSJ6O1">7972530698</a> | 📧 Email: <a href="mailto:nooraincosmetics@gmail.com">nooraincosmetics@gmail.com</a></p>
    <div class="social-icons">
      <a href="https://www.instagram.com/noorain_skincare_cosmetics?igsh=eTljMjkwd3ZwY3h3" target="_blank">Instagram</a>
      <a href="https://wa.me/message/FCDYEGMJYSJ6O1" target="_blank">WhatsApp</a>
      <a href="https://www.facebook.com/share/1586dWhFzkk/" target="_blank">Facebook</a>
    </div>
    <p>&copy; 2025 Noorain Skincare & Cosmetics. All rights reserved.</p>
  </footer>  <script>
    const products = [
      { name: "Brightening Night Cream", price: "₹750", img: "IMAGE_URL_1" },
      { name: "Ricecream with Rose", price: "₹199", img: "IMAGE_URL_2" },
      { name: "Ginseng Energize Face Wash", price: "₹199", img: "IMAGE_URL_3" },
      { name: "Irish Illumination Soap", price: "₹129", img: "IMAGE_URL_4" },
      { name: "Beetroot-Rose Lip Lightening Butter", price: "₹149", img: "IMAGE_URL_5" },
      { name: "Strawberry Lip Lightening Butter", price: "₹149", img: "IMAGE_URL_6" },
      { name: "Chocolate Lip Lightening Butter", price: "₹149", img: "IMAGE_URL_7" },
      { name: "Mini Tinted Lip Balm", price: "₹60", img: "IMAGE_URL_8" },
      { name: "LumiGlow SPF 50 Sunscreen", price: "₹399", img: "IMAGE_URL_9" },
      { name: "Hydra-Rose Mist", price: "₹149", img: "IMAGE_URL_10" },
    ];

    const container = document.getElementById("products");
    products.forEach((item) => {
      const div = document.createElement("div");
      div.className = "product";
      div.innerHTML = `
        <img src="${item.img}" alt="${item.name}">
        <h3>${item.name}</h3>
        <p>${item.price}</p>
        <button onclick="alert('Added to cart')">Add to Cart</button>
        <button onclick="alert('Added to wishlist')">Wishlist</button>
      `;
      container.appendChild(div);
    });
  </script></body>
</html>
