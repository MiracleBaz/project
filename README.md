# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sports Shop</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">ONE|ALL SPORTS</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link active" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="shop.html">Shop</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<div class="container-fluid bg-primary text-white text-center py-5">
  <h1>Welcome to ONE|ALL SPORTS</h1>
  <p>Your one-stop shop for all sports gear!</p>
  <a href="#" class="btn btn-light btn-lg">Shop Now</a>
</div>

<!-- Product Showcase Section -->
<div class="container py-5">
  <h2 class="text-center mb-4">Featured Products</h2>
  <div class="row">
    <div class="col-md-4 mb-4">
      <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTy0NG_MI7UzH17qowf7mVtslPa1eX967OQSw&s" class="card-img-top" alt="Football">
        <div class="card-body">
          <h5 class="card-title">Football</h5>
          <p class="card-text">$25.00</p>
          <a href="#" class="btn btn-primary">Add to Cart</a>
        </div>
      </div>
    </div>
    <div class="col-md-4 mb-4">
      <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQhTP3mYI-7GgjP-omjnEC7_4Jv8juE3EaA5A&s" class="card-img-top" alt="Basketball">
        <div class="card-body">
          <h5 class="card-title">Basketball</h5>
          <p class="card-text">$30.00</p>
          <a href="#" class="btn btn-primary">Add to Cart</a>
        </div>
      </div>
    </div>
    <div class="col-md-4 mb-4">
      <div class="card">
        <img src="https://img.freepik.com/premium-photo/tennis-racket-with-tennis-ball-lying-top-it-ready-game-detailed-closeup-tennis-racquet-neon-yellow-ball-ai-generated_538213-41165.jpg?w=360" class="card-img-top" alt="Tennis Racket">
        <div class="card-body">
          <h5 class="card-title">Tennis Racket</h5>
          <p class="card-text">$40.00</p>
          <a href="#" class="btn btn-primary">Add to Cart</a>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Customer Testimonials Section -->
<div class="container py-5">
  <h2 class="text-center mb-4">What Our Customers Say</h2>
  <div class="row">
    <div class="col-md-4 mb-4">
      <div class="card">
        <div class="card-body">
          <p class="card-text">"Amazing products! The quality is top-notch, and my order arrived quickly!"</p>
          <h5 class="card-title">John Doe</h5>
        </div>
      </div>
    </div>
    <div class="col-md-4 mb-4">
      <div class="card">
        <div class="card-body">
          <p class="card-text">"The best sports shop I've ever visited. Great prices and fast delivery!"</p>
          <h5 class="card-title">Jane Smith</h5>
        </div>
      </div>
    </div>
    <div class="col-md-4 mb-4">
      <div class="card">
        <div class="card-body">
          <p class="card-text">"Excellent customer service and a wide range of sports gear. Highly recommend!"</p>
          <h5 class="card-title">Michael Johnson</h5>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="bg-dark text-white text-center py-4">
  <p>&copy; 2024 ONE|ALL Inc. | <a href="#" class="text-white">Privacy Policy</a> | <a href="#" class="text-white">Terms of Service</a></p>
  <p>
    <a href="#" class="text-white mx-2">Facebook</a>
    <a href="#" class="text-white mx-2">Twitter</a>
    <a href="#" class="text-white mx-2">Instagram</a>
  </p>
</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.min.js"></script>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .product-card {
            border: 1px solid #ddd;
            border-radius: 10px;
            margin: 15px 0;
            overflow: hidden;
        }
        .product-card img {
            width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
        }
        .product-info {
            padding: 15px;
            text-align: center;
        }
        .product-name {
            font-size: 1.2rem;
            font-weight: bold;
            margin: 10px 0;
        }
        .product-price {
            font-size: 1rem;
            color: #007bff;
            font-weight: bold;
        }
        .product-description {
            font-size: 0.9rem;
            color: #555;
            margin-bottom: 10px;
        }
        .btn-buy {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        .btn-buy:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">ONE|ALL SPORTS</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="home.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="shop.html">Shop</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  
  <!-- Hero Section -->
  <div class="container-fluid bg-primary text-white text-center py-5">
    <h1>Sports Accessories</h1>
    <p>Your one-stop shop for all sports gear!</p>
    <a href="#" class="btn btn-light btn-lg">Shop Now</a>
  </div>
  
    <!-- Product Section -->
    <div class="container mt-5">
        <div class="row">
            <!-- Product 1 -->
            <div class="col-md-4">
                <div class="product-card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLHE0yWwnQRlY8EeksEPbkEOBCvOfXYL8stg&s" alt="Product 1">
                    <div class="product-info">
                        <div class="product-name">Running Shoes</div>
                        <div class="product-price">$59.99</div>
                        <div class="product-description">Comfortable running shoes for all levels of runners.</div>
                        <button class="btn-buy">Buy Now</button>
                    </div>
                </div>
            </div>

            <!-- Product 2 -->
            <div class="col-md-4">
                <div class="product-card">
                    <img src="data:image/jpeg;base64,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" alt="Product 2">
                    <div class="product-info">
                        <div class="product-name">Basketball</div>
                        <div class="product-price">$29.99</div>
                        <div class="product-description">Durable basketball for both indoor and outdoor play.</div>
                        <button class="btn-buy">Buy Now</button>
                    </div>
                </div>
            </div>

            <!-- Product 3 -->
            <div class="col-md-4">
                <div class="product-card">
                    <img src="https://img.freepik.com/premium-photo/tennis-racket-with-tennis-ball-lying-top-it-ready-game-detailed-closeup-tennis-racquet-neon-yellow-ball-ai-generated_538213-41165.jpg?w=360" alt="Product 3">
                    <div class="product-info">
                        <div class="product-name">Tennis Racket</div>
                        <div class="product-price">$89.99</div>
                        <div class="product-description">High-quality racket for professional tennis players.</div>
                        <button class="btn-buy">Buy Now</button>
                    </div>
                </div>
            </div>

            <!-- Product 4 -->
            <div class="col-md-4">
                <div class="product-card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwlH3BrGhdPrswPLOUH74eem0g0FqMkvqy8g&s" alt="Product 4">
                    <div class="product-info">
                        <div class="product-name">Yoga Mat</div>
                        <div class="product-price">$19.99</div>
                        <div class="product-description">Non-slip yoga mat for your workout sessions.</div>
                        <button class="btn-buy">Buy Now</button>
                    </div>
                </div>
            </div>

            <!-- Product 5 -->
            <div class="col-md-4">
                <div class="product-card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTy0NG_MI7UzH17qowf7mVtslPa1eX967OQSw&s" alt="Product 5">
                    <div class="product-info">
                        <div class="product-name">Football</div>
                        <div class="product-price">$34.99</div>
                        <div class="product-description">Premium football for professional matches.</div>
                        <button class="btn-buy">Buy Now</button>
                    </div>
                </div>
            </div>

            <!-- Product 6 -->
            <div class="col-md-4">
                <div class="product-card">
                    <img src="https://swingloosegolf.com/wp-content/uploads/Golf-Clubs-on-Grass.webp" alt="Product 6">
                    <div class="product-info">
                        <div class="product-name">Golf Clubs</div>
                        <div class="product-price">$199.99</div>
                        <div class="product-description">Complete set of golf clubs for every skill level.</div>
                        <button class="btn-buy">Buy Now</button>
                    </div>
                </div>
            </div>

            <!-- Product 7 -->
            <div class="col-md-4">
                <div class="product-card">
                    <img src="https://hitafterhitonline.com/cdn/shop/files/cq5dam.web.1200.1200_15_c1282a91-5b98-43b8-a1c1-8fa09b23a273_1024x.jpg?v=1710334130" alt="Product 7">
                    <div class="product-info">
                        <div class="product-name">Baseball Glove</div>
                        <div class="product-price">$49.99</div>
                        <div class="product-description">Durable leather glove for baseball players.</div>
                        <button class="btn-buy">Buy Now</button>
                    </div>
                </div>
            </div>

            <!-- Product 8 -->
            <div class="col-md-4">
                <div class="product-card">
                    <img src="https://cdn11.bigcommerce.com/s-6ravsmq/images/stencil/1280x960/uploaded_images/are-swimming-goggles-bad-for-your-eyes.jpg?t=1643043345" alt="Product 8">
                    <div class="product-info">
                        <div class="product-name">Swimming Goggles</div>
                        <div class="product-price">$15.99</div>
                        <div class="product-description">Anti-fog swimming goggles for optimal performance.</div>
                        <button class="btn-buy">Buy Now</button>
                    </div>
                </div>
            </div>

            <!-- Product 9 -->
            <div class="col-md-4">
                <div class="product-card">
                    <img src="https://soccermastermind.com/wp-content/uploads/2024/01/drasensoccercleatsRealfashionshowmodern16khdhighdefin3ddf587c-ddee-4d3d-9657-a5b219f0da06.png" alt="Product 9">
                    <div class="product-info">
                        <div class="product-name">Soccer Cleats</div>
                        <div class="product-price">$79.99</div>
                        <div class="product-description">Professional quality cleats for soccer players.</div>
                        <button class="btn-buy">Buy Now</button>
                    </div>
                </div>
            </div>

            <!-- Product 10 -->
            <div class="col-md-4">
                <div class="product-card">
                    <img src="https://nwscdn.com/media/catalog/product/cache/h700xw700/b/o/boxing-gloves-black_1.jpg" alt="Product 10">
                    <div class="product-info">
                        <div class="product-name">Boxing Gloves</div>
                        <div class="product-price">$59.99</div>
                        <div class="product-description">High-quality boxing gloves for training and competition.</div>
                        <button class="btn-buy">Buy Now</button>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-light text-center py-3 mt-5">
        <p>&copy; 2024 ONE|ALL SPORTS All Rights Reserved</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us - ONE|ALL SPORTS</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      padding-top: 50px;
    }
    .team-member img {
      border-radius: 50%;
      width: 150px;
      height: 150px;
      object-fit: cover;
    }
    .team-member h5 {
      margin-top: 20px;
    }
    .team-member p {
      font-style: italic;
    }
    .store-img {
      width: 100%;
      height: auto;
    }
    .footer {
      background-color: #343a40;
      color: white;
      padding: 20px 0;
    }
    .footer a {
      color: white;
    }
    .footer a:hover {
      color: #007bff;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">ONE|ALL SPORTS</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="home.html">Home</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="about.html">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="shop.html">Shop</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- About Section -->
  <section id="about" class="container mt-5">
    <div class="row text-center">
      <div class="col-12">
        <h2 class="display-4">About Us</h2>
        <p class="lead">Your one-stop shop for all your sports equipment and apparel needs!</p>
      </div>
    </div>

    <!-- Mission and Vision -->
    <div class="row mt-4">
      <div class="col-md-6">
        <h3>Our Mission</h3>
        <p>At Sports Shop, our mission is to provide athletes and sports enthusiasts with the best quality equipment and apparel to help them perform at their best. Whether you're a professional or a weekend warrior, we have everything you need to take your game to the next level.</p>
      </div>
      <div class="col-md-6">
        <h3>Our Vision</h3>
        <p>We aim to be the leading sports retailer, offering a wide variety of high-quality products that cater to athletes of all skill levels. Our goal is to create an inclusive sports community by making sports accessible to everyone.</p>
      </div>
    </div>

    <!-- Store Image Section -->
    <div class="row mt-5">
      <div class="col-12">
        <h3 class="text-center">Our Store</h3>
        <img src="https://images.jdmagicbox.com/v2/comp/chennai/p7/044pxx44.xx44.191030135003.h3p7/catalogue/the-sports-story-poonamallee-chennai-sports-goods-dealers-8qqp9z68ri.jpg" alt="Sports Shop" class="store-img">
      </div>
    </div>

    <!-- Meet the Team -->
    <div class="row mt-5 text-center">
      <div class="col-md-4 team-member">
        <img src="https://images.squarespace-cdn.com/content/v1/569591ff0ab3771dba3f1ec6/1650383193773-4E38HIVJMG16Q5MHD80A/JD+Solo+by+Todd+V+Wolfson.jpg?format=2500w" alt="Team Member">
        <h5>John Doe</h5>
        <p>Founder & CEO</p>
      </div>
      <div class="col-md-4 team-member">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSoAqP1vvJ0juBvSZAMGWhF-tPYuukzTr1qww&s" alt="Team Member">
        <h5>Jane Smith</h5>
        <p>Store Manager</p>
      </div>
      <div class="col-md-4 team-member">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQHlZNiai5_JMwHIWFWx1eJVW4mjehdH8zECg&s" alt="Team Member">
        <h5>Michael Johnson</h5>
        <p>Head of Sales</p>
      </div>
    </div>
  </section>

  <!-- Footer Section -->
  <footer class="footer text-center">
    <div class="container">
      <p>&copy; 2024 ONE|ALL SPORTS. All Rights Reserved.</p>
      <p>
        <a href="#">Facebook</a> | 
        <a href="#">Instagram</a> | 
        <a href="#">Twitter</a>
      </p>
    </div>
  </footer>

  <!-- Bootstrap JS and Dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - ONE|ALL SPORTS</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      padding-top: 70px;
    }

    .footer {
      background-color: #343a40;
      color: white;
      padding: 20px 0;
    }

    .footer a {
      color: white;
    }

    .footer a:hover {
      color: #007bff;
    }

    .contact-form .form-group input,
    .contact-form .form-group textarea {
      border-radius: 0.5rem;
    }
  </style>
</head>

<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">ONE|ALL SPORTS</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="home.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="shop.html">Shop</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">About</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Contact Section -->
  <section class="container my-5">
    <h2 class="text-center mb-4">Contact Us</h2>

    <div class="row">
      <!-- Contact Form -->
      <div class="col-md-6 contact-form">
        <h4>Send Us a Message</h4>
        <form>
          <div class="form-group">
            <label for="name">Full Name</label>
            <input type="text" class="form-control" id="name" placeholder="Your Name">
          </div>
          <div class="form-group">
            <label for="email">Email address</label>
            <input type="email" class="form-control" id="email" placeholder="Your Email">
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>

      <!-- Store Location and Contact Info -->
      <div class="col-md-6">
        <h4>Our Location</h4>
        <p>We are located at:</p>
        <p>NO 17 Sports Street, Sydney, Australia</p>
        <p><strong>Email:</strong> info@sportsshop.com</p>
        <p><strong>Phone:</strong> +1 (800) 123-4567</p>
        <p><strong>Business Hours:</strong></p>
        <ul>
          <li>Monday - Friday: 9:00 AM - 6:00 PM</li>
          <li>Saturday: 10:00 AM - 4:00 PM</li>
          <li>Sunday: Closed</li>
        </ul>

       

  <!-- Bootstrap JS and Dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>
```


# OUTPUT:

![alt text](<Screenshot 2024-12-26 130655.png>)
![alt text](<Screenshot 2024-12-26 130717.png>)
![alt text](<Screenshot 2024-12-26 134611.png>)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
