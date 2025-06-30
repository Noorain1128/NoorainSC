<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Noorain Skincare & Cosmetics</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom, #fff6f7, #ffe6eb);
      overflow-x: hidden;
      color: #4b2c2c;
    }
    header {
      background: #f9e6e8;
      text-align: center;
      padding: 1rem;
    }
    header img {
      max-width: 160px;
    }
    nav {
      background: #ffe3e3;
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      padding: 1rem;
      font-weight: bold;
    }
    nav a {
      text-decoration: none;
      color: #a33658;
    }
    .carousel {
      display: flex;
      overflow: hidden;
      width: 100%;
      max-height: 350px;
      margin: 0 auto;
      position: relative;
    }
    .carousel img {
      width: 100%;
      height: auto;
      object-fit: cover;
      flex-shrink: 0;
      animation: slide 12s infinite;
    }
    @keyframes slide {
      0% { transform: translateX(0%); }
      33% { transform: translateX(-100%); }
      66% { transform: translateX(-200%); }
      100% { transform: translateX(0%); }
    }
    .hero {
      text-align: center;
      padding: 3rem 1rem;
    }
    .section-title {
      text-align: center;
      font-size: 2rem;
      color: #c83b6f;
      margin-top: 2rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }
    .product {
      background: white;
      padding: 1rem;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product button {
      margin: 0.5rem;
      padding: 0.5rem 1rem;
      border: none;
      border-radius: 6px;
      background: #f49ab0;
      color: white;
      cursor: pointer;
    }
    .testimonial-section {
      display: flex;
      gap: 1.5rem;
      overflow-x: auto;
      padding: 2rem;
      scroll-snap-type: x mandatory;
    }
    .testimonial-card {
      min-width: 250px;
      flex: 0 0 auto;
      background: white;
      border-radius: 12px;
      padding: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      scroll-snap-align: start;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.8rem;
      margin: 0.5rem 0;
      border-radius: 8px;
      border: 1px solid #ccc;
    }
    form button {
      background: #c83b6f;
      color: white;
      padding: 0.8rem 2rem;
      border: none;
      border-radius: 6px;
    }
    .whatsapp-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 0.75rem 1rem;
      border-radius: 50%;
      text-decoration: none;
      font-size: 24px;
      z-index: 999;
    }
  </style>
</head>
<body>
<header>
  <img src="https://i.postimg.cc/KYBZbktv/Noorain-Logo-Rosegold.png" alt="Noorain Logo"/>
</header>

<div class="carousel">
  <img src="https://i.postimg.cc/3RFLXjQK/model1.jpg" alt="Model 1">
  <img src="https://i.postimg.cc/nLZynsn6/model2.jpg" alt="Model 2">
  <img src="https://i.postimg.cc/VLf3kQFH/model3.jpg" alt="Model 3">
</div>

<nav>
  <a href="#home">Home</a>
  <a href="#shop">Shop</a>
  <a href="#about">About</a>
  <a href="#checkout">Checkout</a>
</nav>

<section class="hero" id="home">
  <h1>Skincare Crafted For Confidence for Men and Women</h1>
  <p>Handcrafted skincare powered by nature, designed for confidence and love.</p>
</section>

<h2 class="section-title" id="about">Founder Story & Vision</h2>
<section style="padding: 2rem; max-width: 800px; margin: auto;">
  <p>I created Noorain Skincare & Cosmetics to offer safe, effective, natural skincare that promotes confidence, peace, and self-love. Handcrafted in small batches, our products serve both men and women with love and care.</p>
</section>

<h2 class="section-title" id="shop">Shop All Products</h2>
<section class="products">
  <div class="product"><img src="https://i.postimg.cc/43ZKvvFq/night-cream.jpg" alt=""><h3>Brightening Night Cream</h3><p>₹750</p><button>Add to Cart</button></div>
  <div class="product"><img src="https://i.postimg.cc/MpZfVw6x/ricecream-facewash.jpg" alt=""><h3>Ricecream with Rose</h3><p>₹199</p><button>Add to Cart</button></div>
  <div class="product"><img src="https://i.postimg.cc/1zt4K3rG/ginseng-facewash.jpg" alt=""><h3>Ginseng Face Wash</h3><p>₹199</p><button>Add to Cart</button></div>
  <div class="product"><img src="https://i.postimg.cc/FRdjcRfw/irish-soap.jpg" alt=""><h3>Irish Illumination Soap</h3><p>₹129</p><button>Add to Cart</button></div>
  <div class="product"><img src="https://i.postimg.cc/kXcRnTXK/beetroot-lip.jpg" alt=""><h3>Beetroot-Rose Lip Butter</h3><p>₹149</p><button>Add to Cart</button></div>
</section>
