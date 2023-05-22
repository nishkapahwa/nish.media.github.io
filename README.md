<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Housing Company Landing Page</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    /* Custom CSS */
    body {
      background-color: #f8f9fa;
    }

    /* Section 1 - About Us */
    #section1 {
      background-color: #ffffff;
    }

    /* Section 2 - Services */
    #section2 {
      background-color: #f1f3f5;
    }

    /* Section 3 - Featured Properties */
    #section3 {
      background-color: #ffffff;
    }

    /* Section 4 - Testimonials */
    #section4 {
      background-color: #f1f3f5;
    }

    /* Section 5 - Contact Us */
    #section5 {
      background-color: #ffffff;
    }

    /* Section 6 - Get Started */
    #section6 {
      background-color: #f1f3f5;
    }
  </style>
</head>
<body>
  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">Housing Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#section1">About Us</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#section2">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#section3">Featured Properties</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#section4">Testimonials</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#section5">Contact Us</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#section6">Get Started</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Section 1 - About Us -->
  <section id="section1" class="py-5">
    <div class="container">
      <h1>About Us</h1>
      <p>Welcome to our housing company. We specialize in providing high-quality homes for families, couples, and individuals. Our mission is to create spaces that inspire and enhance the lives of our residents.</p>
    </div>
  </section>

  <!-- Section 2 - Services -->
  <section id="section2" class="py-5 bg-light">
    <div class="container">
      <h1>Services</h1>
      <p>We offer a range of services to meet your housing needs:</p>
      <ul>
        <li>Property Sales</li>
        <li>Rentals and Leasing</li>
        <li>Property Management</li>
        <li>Home Improvement and Renovation</li>
      </ul>
    </div>
  </section>

  <!-- Section 3 - Featured Properties -->
  <section id="section3" class="py-5">
    <div class="container">
      <h1>Featured Properties</h1>
      <div class="row">
        <div class="col-md-4">
          <img src="property1.jpg" alt="Property 1" class="img-fluid">
        </div>
        <div class="col-md-4">
          <img src="property2.jpg" alt="Property 2" class="img-fluid">
        </div>
        <div class="col-md-4">
          <img src="property3.jpg" alt="Property 3" class="img-fluid">
        </div>
      </div>
    </div>
  </section>

  <!-- Section 4 - Testimonials -->
  <section id="section4" class="py-5 bg-light">
    <div class="container">
      <h1>Testimonials</h1>
      <div id="testimonialCarousel" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#testimonialCarousel" data-slide-to="0" class="active"></li>
          <li data-target="#testimonialCarousel" data-slide-to="1"></li>
          <li data-target="#testimonialCarousel" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <blockquote class="blockquote">
              <p class="mb-0">"The housing company helped us find our dream home. The process was smooth, and the staff was professional and friendly."</p>
              <footer class="blockquote-footer">John Doe</footer>
            </blockquote>
          </div>
          <div class="carousel-item">
            <blockquote class="blockquote">
              <p class="mb-0">"I highly recommend the housing company for their excellent property management services. They have been responsive and efficient in addressing our needs."</p>
              <footer class="blockquote-footer">Jane Smith</footer>
            </blockquote>
          </div>
          <div class="carousel-item">
            <blockquote class="blockquote">
              <p class="mb-0">"The team at the housing company exceeded our expectations. They truly care about creating a positive living experience for their residents."</p>
              <footer class="blockquote-footer">Mike Johnson</footer>
            </blockquote>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Section 5 - Contact Us -->
  <section id="section5" class="py-5">
    <div class="container">
      <h1>Contact Us</h1>
      <p>For inquiries or to schedule a visit, please reach out to us:</p>
      <ul>
        <li>Email: info@housingcompany.com</li>
        <li>Phone: 123-456-7890</li>
        <li>Address: 123 Main Street, City, Country</li>
      </ul>
    </div>
  </section>

  <!-- Section 6 - Get Started -->
  <section id="section6" class="py-5 bg-light">
    <div class="container">
      <h1>Get Started</h1>
      <p>Ready to find your perfect home? Contact us today or explore our available properties.</p>
      <a href="#section3" class="btn btn-primary">Explore Properties</a>
    </div>
  </section>

  <!-- Bootstrap JS -->
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
