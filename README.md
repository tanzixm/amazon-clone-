# amazon-clone-
just using basic html and css easy and simple 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amazon Clone</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
</head>
<body>
  <!-- Navbar -->
  <header>
    <div class="navbar">
      <div class="nav-logo border">
        <div class="logo"></div>
      </div>
      <div class="nav-address border">
        <p class="add-first">Deliver to</p>
        <div class="add-icon">
          <i class="fa-solid fa-location-dot"></i>
          <p class="add-second">India</p>
        </div>
      </div>
      <div class="nav-search">
        <select class="search-select">
          <option>All</option>
        </select>
        <input placeholder="Search Amazon" class="search-input">
        <div class="search-icon">
          <i class="fa-solid fa-magnifying-glass"></i>
        </div>
      </div>
      <div class="nav-signin border">
        <p><span>Hello, sign in</span></p>
        <p class="nav-second">Account & Lists</p>
      </div>
      <div class="nav-return border">
        <p><span>Returns</span></p>
        <p class="nav-second">& Orders</p>
      </div>
      <div class="nav-cart border">
        <i class="fa-solid fa-cart-shopping"></i>
        Cart
      </div>
    </div>

    <div class="panel">
      <div class="panel-all">
        <i class="fa-solid fa-bars"></i>
        All
      </div>
      <div class="panel-ops">
        <p>Today's Deals</p>
        <p>Customer Service</p>
        <p>Registry</p>
        <p>Gift Cards</p>
        <p>Sell</p>
      </div>
    </div>
  </header>

  <!-- Hero Section -->
  <div class="hero-section">
    <div class="hero-msg">
      <p>You are on amazon.com. You can also shop on Amazon India for millions of products with fast local delivery. 
        <a href="#">Click here to go to amazon.in</a>
      </p>
    </div>
  </div>

  <!-- Shop Section -->
  <div class="shop-section">
    <div class="box">
      <div class="box-content">
        <h2>Clothes</h2>
        <div class="box-img" style="background-image:url('box1_image.jpg');"></div>
        <p>See more</p>
      </div>
    </div>
    <div class="box">
      <div class="box-content">
        <h2>Health & Personal Care</h2>
        <div class="box-img" style="background-image:url('box2_image.jpg');"></div>
        <p>See more</p>
      </div>
    </div>
    <div class="box">
      <div class="box-content">
        <h2>Furniture</h2>
        <div class="box-img" style="background-image:url('box3_image.jpg');"></div>
        <p>See more</p>
      </div>
    </div>
    <div class="box">
      <div class="box-content">
        <h2>Electronics</h2>
        <div class="box-img" style="background-image:url('box4_image.jpg');"></div>
        <p>See more</p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <div class="foot-panel1">Back to Top</div>
    <div class="foot-panel2">
      <ul>
        <p>Get to Know Us</p>
        <a>Careers</a>
        <a>Blog</a>
        <a>About Amazon</a>
      </ul>
      <ul>
        <p>Connect with Us</p>
        <a>Facebook</a>
        <a>Twitter</a>
        <a>Instagram</a>
      </ul>
      <ul>
        <p>Make Money with Us</p>
        <a>Sell on Amazon</a>
        <a>Affiliate Marketing</a>
      </ul>
    </div>
    <div class="foot-panel3">
      <div class="logo"></div>
    </div>
    <div class="foot-panel4">
      <p>© 2025 Amazon Clone. Created for practice.</p>
    </div>
  </footer>
</body>
</html>





* {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  box-sizing: border-box;
}

/* Navbar */
.navbar {
  display: flex;
  align-items: center;
  background-color: #131921;
  color: white;
  padding: 10px;
  justify-content: space-between;
}

.nav-logo .logo {
  background-image: url("amazon_logo.png");
  background-size: cover;
  width: 100px;
  height: 40px;
}

.border {
  padding: 5px;
  cursor: pointer;
}
.border:hover {
  border: 1px solid white;
}

/* Address */
.nav-address {
  padding: 5px;
}
.add-first {
  font-size: 12px;
  color: #ccc;
}
.add-second {
  font-size: 14px;
  font-weight: bold;
}

/* Search */
.nav-search {
  display: flex;
  flex: 1;
  margin: 0 10px;
}
.search-select {
  padding: 5px;
  background: #f3f3f3;
  border: none;
}
.search-input {
  flex: 1;
  padding: 8px;
  border: none;
}
.search-icon {
  background: #febd69;
  padding: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
}

/* Sign in and cart */
.nav-signin span, .nav-return span {
  font-size: 12px;
}
.nav-second {
  font-size: 14px;
  font-weight: bold;
}
.nav-cart {
  display: flex;
  align-items: center;
  font-weight: bold;
}
.nav-cart i {
  margin-right: 5px;
}

/* Panel */
.panel {
  display: flex;
  align-items: center;
  background: #232f3e;
  color: white;
  padding: 10px;
}
.panel-all {
  margin-right: 15px;
}
.panel-ops p {
  display: inline;
  margin: 0 10px;
  cursor: pointer;
}

/* Hero Section */
.hero-section {
  background-image: url("hero_image.jpg");
  background-size: cover;
  height: 400px;
  display: flex;
  align-items: flex-end;
  justify-content: center;
}
.hero-msg {
  background: white;
  padding: 10px;
  margin-bottom: 30px;
}
.hero-msg a {
  color: #007185;
  text-decoration: none;
}

/* Shop Section */
.shop-section {
  display: flex;
  justify-content: space-evenly;
  background: #e2e7e6;
  flex-wrap: wrap;
  padding: 20px 0;
}
.box {
  width: 22%;
  background: white;
  margin: 10px;
  padding: 20px;
}
.box-img {
  height: 250px;
  margin: 10px 0;
  background-size: cover;
}

/* Footer */
.foot-panel1 {
  background: #37475a;
  color: white;
  text-align: center;
  padding: 15px;
  cursor: pointer;
}
.foot-panel2 {
  display: flex;
  justify-content: space-evenly;
  background: #232f3e;
  color: white;
  padding: 20px 0;
}
.foot-panel2 ul {
  list-style: none;
}
.foot-panel2 a {
  display: block;
  margin: 5px 0;
  font-size: 14px;
}
.foot-panel3 {
  background: #131921;
  padding: 20px;
  display: flex;
  justify-content: center;
}
.foot-panel3 .logo {
  background-image: url("amazon_logo.png");
  background-size: cover;
  width: 100px;
  height: 40px;
}
.foot-panel4 {
  background: #131921;
  color: #ccc;
  text-align: center;
  padding: 10px;
  font-size: 12px;
}
