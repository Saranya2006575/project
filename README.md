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
project home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home -THE BRIDAL LOOM </title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">THE BRIDAL LOOM</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle n
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="home.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to THE BRIDAL LOOM</h1>
        <p>"Step into a world of elegance and tradition at *[Shop Name]*, your ultimate destination for exquisite lehengas!
             From timeless classics to contemporary designs, our collection is handcrafted to make every occasion unforgettable.
             Whether you're a bride-to-be or attending a festive celebration, we bring you the finest fabrics, intricate embroidery, 
             and vibrant colors to suit your style.</p>
         <P>  Let us help you twirl in confidence and grace—because every woman deserves to feel like royalty.
             With expert craftsmanship, exclusive customizations, and unmatched quality, we ensure your look is as unique as your story.
             Visit us today and transform your dreams into reality at "THE BRIDAL LOOM!"</p>
        <p>Thank you for choosing THE BRIDAL LOOM for your better looks . We look forward to serving you and helping you live a gorgeous.</p>
      </div>
      <div class="col-md-4">
       
      </div>
    </div>
  </div>
  <body background="bgimgdress.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <style>
    body {
      margin: 0;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      color:aliceblue;
      
    }
    footer {
      margin-top: auto;
      background-color: #343a40; /* Matches Bootstrap's bg-dark */
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body background="BG.png" style="background-repeat: no-repeat; background-size: cover;">

  <!-- Other Content -->
  <div class="content">
    <!-- Add your page content here -->
  </div>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 THE BRIDAL LOOM. All rights reserved. BY J SARANYA</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

about
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>abou THE BRIDAL LOOM</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">THE BRIDAL LOOM</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>ABOUT THE BRIDAL LOOM</h1>
        <div id="vision">
          <h2>Vision</h2>
          <p>To expand our global presence, bringing our unique brand of luxury and craftsmanship to discerning customers around the world.
        </p>
        </div>
        <div id="mission">
          <h2>Mission</h2>
          <p>To create high-quality, timeless lehangas that transcends trends and becomes cherished heirlooms.
            To deliver exceptional service that exceeds expectations, making every interaction with the brand a memorable and delightful experience.
            To uphold the traditions of fine dress making, passing on the skills and knowledge of master artisans to future generations.
        </p>
        </div>
        <div id="values">
          <h2>Values</h2>
          <ul>
            <li>Craftsmanship Excellence – We take pride in delivering lehengas that showcase impeccable quality and intricate artistry. Each piece is meticulously handcrafted to perfection, ensuring that every thread and detail reflects timeless elegance.</li>
                <li>Cultural Heritage – Our designs celebrate the rich traditions of Indian ethnic wear, blending age-old craftsmanship with a modern touch. By embracing cultural roots, we create lehengas that are not just garments but a tribute to history and tradition.</li>
                    <li>Innovation & Creativity – We believe in constantly evolving, bringing fresh designs that fuse contemporary styles with classic elements. Our innovative approach ensures each lehenga is unique, stylish, and ahead of the trends.</li>
                        <li> Customer-Centric Approach – At the heart of our business is our commitment to our customers. We prioritize their needs, preferences, and satisfaction by offering personalized designs, perfect fits, and exceptional service.</li>
                            <li>Sustainability – We are dedicated to using eco-friendly materials and adopting ethical production practices to create lehengas that are as gentle on the planet as they are beautiful to wear.</li>
                                <li>Empowering Artisans – Our work is a celebration of skilled craftsmanship. We support talented artisans by providing fair wages, fostering their creativity, and showcasing their incredible artistry to the world..</li>
                                    <li>These values guide our journey in creating lehengas that not only look stunning but also resonate with purpose and meaning.</li>
            
          </ul>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>
  <body background="bgimg2.jpg" style="background-repeat: no-repeat; background-size: cover;"></body>
  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-3">
    <p>&copy; 2024 THE BRIDAL LOOM. All rights reserved.  BY J.SARANYA</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

product
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products - THE BRIDAL LOOM</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">THE BRIDAL LOOM</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Products
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Over-the-counter (OTC) THE BRIDAL BLOOM</a>
            <a class="dropdown-item" href="#">no</a>
            <a class="dropdown-item" href="#">no</a>
            <a class="dropdown-item" href="#">Supplements</a>
          </div>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-3">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Product categories</h1>
        <div class="card-deck">
          <div class="card">
            <img src="Screenshot 2024-12-22 192631.png" class="card-img-top" alt="Product 1" width="200" height="300">
            <div class="card-body">
              <h5 class="card-title"> Colourful lehanga</h5>
              <p class="card-text">Alright, gorgeous bride-to-be, let’s dive deep into the world of modern bridal . Its not just about wearing a piece of lehanga; its about making a statement, telling your unique story
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="Screenshot 2024-12-22 192546.png" class="card-img-top" alt="Product 2" width="200" height="300">
            <div class="card-body">
              <h5 class="card-title">purple lehanga</h5>
              <p class="card-text">
              <p>Drape yourself in regal elegance with our stunning purple lehenga, a perfect blend of sophistication and charm. Adorned with intricate embroidery and shimmering accents, 
                it’s designed to make you feel like royalty at every celebration.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="Screenshot 2024-12-22 192607.png" class="card-img-top" alt="Product 3" width="200" height="300">
            <div class="card-body">
              <h5 class="card-title">bride lehanga</h5>
              <p class="card-text">A bridal lehenga that embodies grace, tradition, and timeless beauty, crafted to make your special day truly unforgettable.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 THE BRIDAL LOOM. All rights reserved. By J.SARANYA</p>
  </footer>
  <body background="bgimg3.webp" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

final

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - THE BRIDAL LOOM</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">THE BRIDAL LOOM</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows=3" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>THE BRIDAL LOOM</h2>
        <address>
          <strong>Address:</strong><br>
          18, puliyar kovil street, thambaram,chennai<br>
          India, 510501<br><br>
          <strong>Email:</strong><br>
          abcthebridalloom@gmail.com<br><br>
          <strong>Phone:</strong><br>
          9943301901
        </address>
      </div>
    </div>
  </div>
  <body background="bgimg4.jpg" style="background-repeat: no-repeat; background-size: cover;">


    <style>
        body {
          margin: 0;
          display: flex;
          flex-direction: column;
          min-height: 100vh;
          color:black;
          
        }
        footer {
          margin-top: auto;
          background-color: #343a40; /* Matches Bootstrap's bg-dark */
          color:black;
          text-align: center;
          padding: 1rem;
        }
      </style>
    </head>
    <body background="BG.png" style="background-repeat: no-repeat; background-size: cover;">
    
      <!-- Other Content -->
      <div class="content">
        <!-- Add your page content here -->
      </div>
    
      <!-- Footer -->
      <footer>
        <p>&copy; 2024 THE BRIDAL LOOM. All rights reserved. BY J SARANYA</p>
      </footer>
    
      <!-- Bootstrap JS -->
      <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
      <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
      <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    </body>
    </html>


```
# OUTPUT:

![Screenshot 2024-12-22 232122](https://github.com/user-attachments/assets/a83a91c0-3793-48d0-87a3-6cc5c36695f9)

![Screenshot 2024-12-22 232143](https://github.com/user-attachments/assets/6e38e91e-cdf6-4b5f-8af0-9cd75ec16bb2)

![Screenshot 2024-12-22 232210](https://github.com/user-attachments/assets/c3e16566-bbc6-4540-92ef-5ce7d88d760c)


![Screenshot 2024-12-22 232230](https://github.com/user-attachments/assets/f9b250cc-fb5f-420e-8ce0-154d170689c4)




# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
