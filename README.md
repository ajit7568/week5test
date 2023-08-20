# week5test
hosted link https://ajit7568.github.io/week5test/
html code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Geekster Project</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200">
  
  </head>
  <body oncontextmenu="return false;">
    <header>
      <nav class="navbar">
        <div class="nav-logo">
          <a href="#"><img src="images/amazon_logo.png" alt="logo"></a>
        </div>
        <div class="address">
          <a href="#" class="deliver">Deliver</a>
          <div class="map-icon">
            <span class="material-symbols-outlined">location_on</span>
            <a href="#" class="location">India</a>
          </div>
        </div>

 <div class="nav-search">
          <select class="select-search">
            <option>All</option>
            <option>All Categories</option>
            <option>Amazon Devices</option>
          </select>
          <input type="text" placeholder="Search Amazon" class="search-input">
          <div class="search-icon">
            <span class="material-symbols-outlined">search</span>
          </div>
        </div>

   <div class="sign-in">
         <a href="#"> <p>Hello, sign in</p>
          <span>Account &amp; Lists</span></a>
        </div>

  <div class="returns">
          <a href="#"><p>Returns</p>
            <span>&amp; Orders</span></a>
        </div>

   <div class="cart">
          <a href="#">
            <span class="material-symbols-outlined cart-icon">shopping_cart</span>
            </a>
            <p>Cart</p>
        </div>
      </nav>
      
  <div class="banner">
        <div class="banner-content">
          <div class="panel">
            <span class="material-symbols-outlined">menu</span>
            <a href="#">All</a>
          </div>
  
  <ul class="links">
            <li><a href="#">Today's Deals</a></li>
            <li><a href="#">Customer Service</a></li>
            <li><a href="#">Registry</a></li>
            <li><a href="#">Gift Cards</a></li>
            <li><a href="#">Sell</a></li>
          </ul>
          <div class="deals">
            <a href="#">Shop deals in Electronics</a>
          </div>
        </div>
      </div>
    </header>

   <section class="hero-section"></section>

  <div class="shop-images">
        <div class="shop-link" data-aos="flip-left" data-aos-duration='900'>
          <h3>Shop Laptops &amp; Tables</h3>
          <img src="images/img-1.png" alt="card">
          <a href="#">Shop now</a>
        </div>
        <div class="shop-link" data-aos="flip-left" data-aos-duration='1000' >
          <h3>Shop Smartwatches</h3>
          <img src="images/img-2.png" alt="card">
          <a href="#">Shop now</a>
        </div>
        <div class="shop-link" data-aos="flip-left" data-aos-duration='1100'>
          <h3>Create with Strip Lights</h3>
          <img src="images/img-3.png" alt="card">
          <a href="#">Shop now</a>
        </div>
        <div class="shop-link" data-aos="flip-left" data-aos-duration='1200'>
          <h3>Home Refresh Ideas</h3>
          <img src="images/img-4.png" alt="card">
          <a href="#">Shop now</a>
        </div>
      </div>
    </section>

 <footer>
      <a href="#" class="footer-title">
        Back to top
      </a>
      <div class="footer-items">
        <ul>
          <h3>Get to Know Us</h3>
          <li><a href="#">About us</a></li>
          <li><a href="#">Careers</a></li>
          <li><a href="#">Press Release</a></li>
          <li><a href="#">Amazon Science</a></li>
        </ul>
        <ul>
          <h3>Connect with Us</h3>
          <li><a href="#">Facebook</a></li>
          <li><a href="#">Twitter</a></li>
          <li><a href="#">Instagram</a></li>
        </ul>
        <ul>
          <h3>Make Money with Us</h3>
          <li><a href="#">Sell on Amazon</a></li>
          <li><a href="#">Sell under Amazon Accelerator</a></li>
          <li><a href="#">Protect and Build Your Brand</a></li>
          <li><a href="#">Amazon Global Selling</a></li>
          <li><a href="#">Become an Affiliate</a></li>
          <li><a href="#">Fulfillment by Amazon</a></li>
          <li><a href="#">Advertise Your Products</a></li>
          <li><a href="#">Amazon Pay on Merchants</a></li>
        </ul>
        <ul>
          <h3>Let Us Help You</h3>
          <li><a href="#">COVID-19 and Amazon</a></li>
          <li><a href="#">Your Account</a></li>
          <li><a href="#">Return Centre</a></li>
          <li><a href="#">100% Purchase Protection</a></li>
          <li><a href="#">Amazon App Download</a></li>
          <li><a href="#">Help</a></li>
        </ul>
      </div>
    </footer>
    <!-- <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
      AOS.init({offset: 300,});
      </script> -->
  </body>
</body>
</html>
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@200;300;400;500;600;700&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Open Sans", sans-serif;
}

html {
  scroll-behavior: smooth;
}

a {
  text-decoration: none;
  color: #fff;
}

a:hover {
  color: #ddd;
}

/* Header or Navbar */
header {
  width: 100%;
  background-color: #0f1111;
}

.navbar {
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  cursor: pointer;
  color: #fff;
  max-width: 1280px;
  margin: 0 auto;
}

.nav-logo img {
  margin-top: 10px;
  width: 128px;
}

.address .deliver {
  margin-left: 20px;
  font-size: 0.75rem;
  color: #ccc;
}

.address .map-icon {
  display: flex;
  align-items: center;
}


.nav-search {
  display: flex;
  justify-content: space-evenly;
  max-width: 620px;
  width: 100%;
  height: 40px;
  border-radius: 4px;
}

.select-search {
  background: #f3f3f3;
  width: 50px;
  text-align: center;
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px;
  border: none;
}

.search-input {
  max-width: 600px;
  width: 100%;
  font-size: 1rem;
  border: none;
  outline: none;
  padding-left: 10px;
}

.search-icon {
  max-width: 45px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 1.2rem;
  background: #febd68;
  color: #000;
  cursor: pointer;
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px;
}

.sign-in p,
.returns p {
  font-size: 0.75rem;
}

.sign-in,
.returns span {
  font-size: 0.875rem;
  font-weight: 600;
}

.cart {
  display: flex;
}

.cart .cart-icon {
  font-size: 2.5rem
}

.cart p {
  margin-top: 20px;
  font-weight: 500;
}

.banner {
  padding: 10px 20px;
  background: #222f3d;
  color: #fff;
  font-size: 0.875rem;
}

.banner-content {
  margin: 0 auto;
  max-width: 1280px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.panel {
  max-width: 1280px;
  display: flex;
  align-items: center;
  gap: 5px;
  cursor: pointer;
}

.panel span {
  margin-right: 7px;
}

.links {
  display: flex;
  align-items: center;
  list-style: none;
  gap: 15px;
  flex-grow: 1;
  margin-left: 15px;
}

.links a {
  padding: 10px 0;
}

.deals a {
  font-size: 0.9rem;
  font-weight: 500;
  white-space: nowrap;
}

/* Hero Section */
.hero-section {
  height: 400px;
  background-image: url("images/hero-img.jpg");
  background-position: center;
  background-size: cover;
}

/* Shop Section */
.shop-section {
  display: flex;
  align-items: center;
  flex-direction: column;
  background-color: #f3f3f3;
  padding: 50px 0;
}

.shop-images {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 40px;
  max-width: 1280px;
  width: 100%;
  overflow: hidden;
}

.shop-link {
  background-color: #fff;
  padding: 30px;
  display: flex;
  cursor: pointer;
  flex-direction: column;
  white-space: nowrap;
  transform: scale(1);
  transition: transform 0.7s ease-in-out;
}

.shop-link:hover{
  transform: scale(1.1);
}


.shop-link img {
  width: 100%;
  height: 280px;
  object-fit: cover;
  margin-bottom: 10px;
}

.shop-link h3 {
  margin-bottom: 10px;
}

.shop-link a {
  display: inline-block;
  margin-top: 10px;
  font-size: 0.9rem;
  color: blue;
  font-weight: 500;
  transition: color 0.3s ease;
}

.shop-link:hover a {
  color: #c7511f;
  text-decoration: underline;
}

/* Footer */
.footer-title {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #37475a;
  color: #fff;
  font-size: 0.875rem;
  font-weight: 600;
  height: 60px;
}

.footer-items {
  display: flex;
  justify-content: space-evenly;
  width: 100%;
  margin: 0 auto;
  background: #232f3e;
}

.footer-items h3 {
  font-size: 1rem;
  font-weight: 500;
  color: #fff;
  margin: 20px 0 10px 0;
}

.footer-items ul {
  list-style: none;
  margin-bottom: 20px;
}

.footer-items li a {
  color: #ddd;
  font-size: 0.875rem;
}

.footer-items li a:hover {
  text-decoration: underline;
}
break down the main components and features of this website:

Head Section:

The head section contains meta information about the webpage, such as character encoding, viewport settings for responsiveness, and the title of the webpage.
It includes links to external resources: a custom CSS file ("style.css") for styling and a Google Fonts stylesheet for using a specific font.
Body Section:

The body of the webpage contains the main content that is visible to users.
Header Section:

The header section is the top part of the webpage, containing the navigation bar and other header elements.
The navigation bar consists of various links and icons:
The website logo.
Delivery-related information with a location icon and country link.
A search bar with a dropdown for selecting search categories.
"Hello, sign in" link for user account information.
"Returns & Orders" link.
A shopping cart icon for the user's cart.
Banner Section:

The banner section is right below the header and contains navigation links and promotional content.
It includes a "menu" icon and links to various sections such as "Today's Deals," "Customer Service," "Registry," "Gift Cards," and "Sell."
A link to shop deals in the "Electronics" category is also provided.
Hero Section:

The hero section is currently empty in the provided code. It's a common area to display featured content or images.
Shop Section:

This section displays multiple "shop links" for various product categories.
Each "shop link" includes a title, an image representing the category, and a "Shop now" link.
Footer Section:

The footer section appears at the bottom of the webpage and contains various links and information.
It's divided into different sections, each with a heading and a list of related links:
"Get to Know Us" with links about the company and its activities.
"Connect with Us" with social media links.
"Make Money with Us" with links for selling on Amazon and related programs.
"Let Us Help You" with links for customer support and assistance.
A link titled "Back to top" provides quick navigation to the top of the page.
Commented Script Section:

There's a commented-out script tag that references the AOS (Animate On Scroll) library. AOS is used for adding animations to elements as they scroll into view.
Overall, the provided HTML code creates a basic structure for an online shopping website with a header, navigation, promotional content, product sections, and a footer with various links for different purposes. 
