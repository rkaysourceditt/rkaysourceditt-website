# rkaysourceditt-website
RKAYSOURCEDITT™ - Streetwear, Sneakers &amp; Luxury E-commerce Website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RKAYSOURCEDITT™</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#000;
color:#fff;
}

header{
background:#0a0a0a;
padding:15px 5%;
display:flex;
justify-content:space-between;
align-items:center;
border-bottom:1px solid #222;
position:sticky;
top:0;
z-index:1000;
}

.logo{
font-size:32px;
font-weight:bold;
color:#ff0000;
}

.search{
width:40%;
padding:12px;
background:#111;
border:1px solid #333;
color:white;
border-radius:30px;
}

.icons{
display:flex;
gap:20px;
}

.hero{
height:80vh;
background:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7));
display:flex;
align-items:center;
padding:5%;
}

.hero-content h1{
font-size:70px;
color:#ff0000;
}

.hero-content p{
margin:20px 0;
font-size:20px;
}

.btn{
background:#ff0000;
padding:15px 35px;
display:inline-block;
color:white;
text-decoration:none;
font-weight:bold;
}

.section{
padding:60px 5%;
}

.section h2{
text-align:center;
margin-bottom:40px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.card{
background:#111;
border:1px solid #222;
padding:20px;
text-align:center;
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.price{
color:#ff0000;
font-size:22px;
margin:10px 0;
}

.add-cart{
background:#ff0000;
border:none;
padding:12px;
width:100%;
color:white;
cursor:pointer;
}

.reviews{
background:#080808;
padding:60px 5%;
}

.review{
background:#111;
padding:20px;
border:1px solid #222;
}

footer{
background:#050505;
padding:40px 5%;
border-top:1px solid #222;
}
</style>
</head>

<body>

<header>
<div class="logo">RKAYSOURCEDITT™</div>

<input class="search" placeholder="Search products...">

<div class="icons">
<span>Account</span>
<span>Wishlist</span>
<span>Basket (0)</span>
</div>
</header>

<section class="hero">
<div class="hero-content">
<h1>RKAYSOURCEDITT™</h1>
<p>Streetwear • Sneakers • Luxury</p>
<a href="#" class="btn">SHOP NOW</a>
</div>
</section>

<section class="section">
<h2>Shop By Category</h2>

<div class="grid">

<div class="card">Tracksuits</div>
<div class="card">Sneakers</div>
<div class="card">Jackets</div>
<div class="card">Bags</div>
<div class="card">Hats</div>
<div class="card">Electronics</div>
<div class="card">Jewellery</div>

</div>
</section>

<section class="section">
<h2>Featured Products</h2>

<div class="grid">

<div class="card">
<h3>Nike Tech Tracksuit</h3>
<p class="price">£120</p>
<button class="add-cart">ADD TO CART</button>
</div>

<div class="card">
<h3>Jordan 4 Retro</h3>
<p class="price">£160</p>
<button class="add-cart">ADD TO CART</button>
</div>

<div class="card">
<h3>Moncler Jacket</h3>
<p class="price">£320</p>
<button class="add-cart">ADD TO CART</button>
</div>

<div class="card">
<h3>LV Backpack</h3>
<p class="price">£280</p>
<button class="add-cart">ADD TO CART</button>
</div>

</div>
</section>

<section class="reviews">
<h2>Customer Reviews</h2>

<div class="grid">

<div class="review">
★★★★★
<p>Great communication and fast delivery.</p>
</div>

<div class="review">
★★★★★
<p>Item arrived exactly as described.</p>
</div>

<div class="review">
★★★★★
<p>Highly recommended seller.</p>
</div>

</div>
</section>

<footer>
<h3>RKAYSOURCEDITT™</h3>
<p>Streetwear • Sneakers • Luxury</p>
<p>Instagram: @rkaysourceditt</p>
<p>Snapchat: @rkaysourceditt</p>
<p>TikTok: @rkaysourceditt</p>
</footer>

</body>
</html>