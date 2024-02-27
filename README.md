<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clothing Fashion - Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Clothing Fashion</h1>
      <nav>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="about.html">About Us</a></li>
          <li><a href="contact.html">Contact Us</a></li>
        </ul>
      </nav>
    </div>
    <div class="buy-now">
      <a href="#" class="btn">Buy Now</a>
    </div>
  </header>
 <section class="main-content">
    <div class="container">
      <h2>Welcome to Clothing Fashion</h2>
    </div>
    <p>With our unique clothing line, experience elegance redefined. Every dress, from traditional forms to modern styles, is handcrafted with care to highlight your distinct sense of fashion and individuality. Invest in high-quality materials, expert tailoring, and figure-flattering shapes to boost your personal style and project confidence and modification at every turn.</p>
    </div>
      <div class="image-container">
        <div class="image-item">
          <img src="dress 1.jpg" alt="Image 1"style="width:250px; height:300px">
          <p>$500</p>
        </div>
        <div class="image-item">
          <img src="dress 2.jpg" alt="Image 2"style="width:250px; height:300px">
          <p>$300</p>
        </div>
        <div class="image-item">
          <img src="dress 3.jpg" alt="Image 3"style="width:250px; height:300px">
          <p>$700</p>
        </div>
     
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2024 Clothing Fashion. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clothing Fashion - About Us</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Clothing Fashion</h1>
      <nav>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="about.html">About Us</a></li>
          <li><a href="contact.html">Contact Us</a></li>
        </ul>
      </nav>
    </div>
  </header>
  
  <section class="main-content">
    <div class="container">
      <h2>About Us</h2>
      <img src="store.jpg" alt="About Us Image"style="width:700px; height:450px">
      <p>"Clothing Fashion is dedicated to bringing you the latest trends in apparel and accessories. Our team of fashion experts meticulously curates collections to inspire your personal style. With a focus on quality and affordability, we strive to make fashion accessible to everyone. Explore our diverse range of clothing options, from casual wear to formal attire, and discover pieces that speak to your individuality. Join us on a journey of self-expression through fashion with Clothing Fashion."</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>2024 Clothing Fashion. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clothing Fashion - Contact Us</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Clothing Fashion</h1>
      <nav>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="about.html">About Us</a></li>
          <li><a href="contact.html">Contact Us</a></li>
        </ul>
      </nav>
    </div>
  </header>
  
  <section class="main-content">
    <div class="container">
      <h2>Contact Us</h2>
        <p>Get in touch with Clothing Fashion for inquiries and support.</p>
        <p>Email: clothingfashion@gmail.com</p>
        <p>Phone: +1234567890</p>
        <p>Address: 20 Fashion Street, Etobicoke</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>2024 Clothing Fashion. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  /* Basic Styling */
  body {
    font-family: Georgia, 'Times New Roman', Times, serif;
    background-color: #f4f4f4;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }
  
  header {
    background-color: #767ed5;
    color: #fff;
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  header h1 {
    font-size: 24px;
  }
  
  nav ul {
    list-style: none;
  }
  
  nav ul li {
    display: inline;
    margin-right: 20px;
  }
  
  nav ul li a {
    color: #fff;
    text-decoration: none;
  }
  
  .buy-now {
    margin-right: 20px;
  }
  
  .btn {
    background-color: #5b1da2;
    color: #fff;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
  }
  
  .btn:hover {
    background-color: #d32f2f;
  }
  
  .main-content {
    text-align: center;
    margin-top: 50px;
  }
  
  .main-content h2 {
    font-size: 36px;
    margin-bottom: 20px;
  }
  
  .image-container {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
  }
  
  .image-container img {
    width: 30%;
  }
  
  .main-content p {
    font-size: 18px;
    margin-bottom: 20px;
  }
  
  footer {
    background-color: #767ed5;
    color: #fff;
    text-align: center;
    padding: 20px 0;
  }
