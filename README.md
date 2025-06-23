# Whiskers-to-Keepsakes
When my beloved cat, Whiskers, lost a tooth, I wanted to keep a part of her with me forever. This small tooth, once a part of her playful purrs and gentle nuzzles, became a cherished keepsake. Inspired by this bond, I began creating unique jewelry pieces from pet teeth, turning memories into tangible treasures. Each piece is craft with your pet  
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Whiskers to Keepsakes - Unique Cat Tooth Jewelry</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background: #f6f6f6;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: #fff;
      padding: 30px 0;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #7c3aed;
    }
    header p {
      font-size: 1.2em;
      color: #555;
      margin-top: 10px;
    }
    nav {
      background: #7c3aed;
      padding: 10px 0;
      text-align: center;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 20px;
      font-size: 1.1em;
      transition: text-decoration 0.2s;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .container {
      max-width: 900px;
      margin: 40px auto;
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.07);
    }
    .story {
      margin-bottom: 40px;
    }
    .story h2 {
      color: #7c3aed;
      margin-bottom: 10px;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-bottom: 40px;
      justify-content: center;
    }
    .gallery img {
      width: 220px;
      height: 220px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
      background: #eee;
    }
    .products {
      margin-bottom: 40px;
    }
    .products h2 {
      color: #7c3aed;
      margin-bottom: 10px;
    }
    .product-list {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      justify-content: center;
    }
    .product {
      background: #f6f6f6;
      border-radius: 10px;
      padding: 18px;
      width: 250px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 140px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 12px;
      background: #ddd;
    }
    .product h3 {
      margin: 0 0 8px 0;
      color: #333;
    }
    .product p {
      margin: 0 0 12px 0;
      color: #555;
      font-size: 0.98em;
    }
    .product .price {
      color: #7c3aed;
      font-weight: bold;
      font-size: 1.2em;
      margin-bottom: 10px;
      display: block;
    }
    .product button {
      background: #7c3aed;
      color: #fff;
      border: none;
      padding: 10px 22px;
      border-radius: 6px;
      font-size: 1em;
      cursor: pointer;
      transition: background 0.2s;
    }
    .product button:hover {
      background: #5b21b6;
    }
    .custom-order {
      background: #f3e8ff;
      padding: 24px;
      border-radius: 10px;
      margin-bottom: 40px;
      text-align: center;
    }
    .custom-order h2 {
      color: #7c3aed;
      margin-bottom: 8px;
    }
    .custom-order p {
      color: #555;
      margin-bottom: 14px;
    }
    .custom-order a {
      color: #fff;
      background: #7c3aed;
      padding: 10px 20px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.2s;
    }
    .custom-order a:hover {
      background: #5b21b6;
    }
    .testimonials {
      margin-bottom: 40px;
    }
    .testimonials h2 {
      color: #7c3aed;
      margin-bottom: 10px;
    }
    .testimonial {
      background: #f6f6f6;
      border-radius: 8px;
      padding: 16px;
      margin-bottom: 12px;
      font-style: italic;
      color: #444;
      box-shadow: 0 1px 4px rgba(0,0,0,0.04);
    }
    .testimonial span {
      display: block;
      margin-top: 8px;
      font-style: normal;
      color: #7c3aed;
      font-weight: bold;
    }
    .ethics {
      background: #e0e7ff;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 40px;
    }
    .ethics h2 {
      color: #7c3aed;
      margin-bottom: 8px;
    }
    .ethics p {
      color: #444;
    }
    footer {
      background: #7c3aed;
      color: #fff;
      text-align: center;
      padding: 22px 0;
      border-radius: 0 0 12px 12px;
      margin-top: 40px;
    }
    @media (max-width: 700px) {
      .container {
        padding: 12px;
      }
      .gallery, .product-list {
        flex-direction: column;
        align-items: center;
      }
      .product {
        width: 95%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Whiskers to Keepsakes</h1>
    <p>Unique Cat Tooth Jewelry – Cherish Your Feline Forever</p>
  </header>
  <nav>
    <a href="#story">Our Story</a>
    <a href="#gallery">Gallery</a>
    <a href="#products">Shop</a>
    <a href="#custom">Custom Orders</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#ethics">Ethics</a>
    <a href="#contact">Contact</a>
  </nav>
  <div class="container">
    <section class="story" id="story">
      <h2>Our Story</h2>
      <p>
        When my beloved cat, Whiskers, lost a tooth, I wanted to keep a part of her with me forever. This small tooth, once a part of her playful purrs and gentle nuzzles, became a cherished keepsake. Inspired by this bond, I began creating unique jewelry pieces from pet teeth, turning memories into tangible treasures. Each piece is crafted with love and care, honoring the special connection between pets and their humans.
      </p>
    </section>
    <section class="gallery" id="gallery">
      <img src="https://images.unsplash.com/photo-1518717758536-85ae29035b6d?auto=format&fit=crop&w=400&q=80" alt="Cat tooth necklace example">
      <img src="https://images.unsplash.com/photo-1518715308788-3005759c41e4?auto=format&fit=crop&w=400&q=80" alt="Cat jewelry example">
      <img src="https://images.unsplash.com/photo-1518715308788-3005759c41e4?auto=format&fit=crop&w=400&q=80" alt="Cat tooth jewelry display">
    </section>
    <section class="products" id="products">
      <h2>Shop Our Collection</h2>
      <div class="product-list">
        <div class="product">
          <img src="https://images.unsplash.com/photo-1518717758536-85ae29035b6d?auto=format&fit=crop&w=400&q=80" alt="Cat Tooth Pendant">
          <h3>Cat Tooth Pendant</h3>
          <span class="price">$49.00</span>
          <p>Handcrafted pendant featuring a real cat tooth, set in sterling silver. Each piece is unique!</p>
          <button>Buy Now</button>
        </div>
        <div class="product">
          <img src="https://images.unsplash.com/photo-1518715308788-3005759c41e4?auto=format&fit=crop&w=400&q=80" alt="Cat Tooth Charm Bracelet">
          <h3>Cat Tooth Charm Bracelet</h3>
          <span class="price">$59.00</span>
          <p>Delicate bracelet with a cat tooth charm, perfect for everyday wear and remembrance.</p>
          <button>Buy Now</button>
        </div>
        <div class="product">
          <img src="https://images.unsplash.com/photo-1518715308788-3005759c41e4?auto=format&fit=crop&w=400&q=80" alt="Custom Cat Tooth Ring">
          <h3>Custom Cat Tooth Ring</h3>
          <span class="price">$69.00</span>
          <p>Send us your cat's tooth and we’ll craft a custom ring just for you. A true keepsake.</p>
          <button>Buy Now</button>
        </div>
      </div>
    </section>
    <section class="custom-order" id="custom">
      <h2>Custom Orders</h2>
      <p>Want a piece made from your own cat's tooth? We offer fully personalized jewelry. Click below to get started!</p>
      <a href="mailto:youremail@example.com?subject=Custom Cat Tooth Jewelry Order">Start Your Custom Order</a>
    </section>
    <section class="testimonials" id="testimonials">
      <h2>What Our Customers Say</h2>
      <div class="testimonial">
        "I never thought I could keep a part of my cat with me forever. The pendant is beautiful and means so much to me." 
        <span>- Sarah P.</span>
      </div>
      <div class="testimonial">
        "The custom ring was the perfect way to remember my best friend. Thank you for your care and amazing work!" 
        <span>- Mike R.</span>
      </div>
    </section>
    <section class="ethics" id="ethics">
      <h2>Ethical & Sustainable</h2>
      <p>
        All jewelry is crafted with the utmost respect for your pet and the environment. We only use naturally shed or extracted teeth, never harming any animal. Our materials are ethically sourced and our process is eco-friendly.
      </p>
    </section>
    <section class="contact" id="contact">
      <h2>Contact Us</h2>
      <p>Questions? Collaborations? Email us at <a href="mailto:youremail@example.com">youremail@example.com</a> or DM us on Instagram <a href="https://instagram.com/yourhandle" target="_blank">@yourhandle</a>.</p>
    </section>
  </div>
  <footer>
    &copy; 2024 Whiskers to Keepsakes. All rights reserved.
  </footer>
</body>
</html>
![IMG_1511](https://github.com/user-attachments/assets/9f484d03-cf7d-4979-9d8a-6bf5e16fa3d5)
