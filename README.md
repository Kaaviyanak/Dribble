# Project Responsive Web Design using Bootstrap
## Date:19.11.25
## NAME:KAAVIYAN.K
## REG NO:212224240066

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sample Bootstrap Webpage</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">MySite</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="py-5 bg-light text-center">
    <div class="container">
      <h1 class="display-5 fw-bold">Welcome to My Website</h1>
      <p class="lead">A simple responsive webpage built using Bootstrap.</p>
      <a href="#services" class="btn btn-primary btn-lg">Learn More</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-5">
    <div class="container">
      <h2 class="mb-4">About Us</h2>
      <div class="row">
        <div class="col-md-6">
          <p>We are dedicated to providing quality content and responsive web design using modern frameworks like Bootstrap.</p>
        </div>
        <div class="col-md-6">
          <p>Our team focuses on simplicity, usability, and clean interface layouts to enhance the user experience.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="py-5 bg-light">
    <div class="container">
      <h2 class="mb-4 text-center">Our Services</h2>

      <div class="row g-4">
        <div class="col-md-4">
          <div class="card h-100 shadow-sm">
            <div class="card-body text-center">
              <h5 class="card-title">Web Design</h5>
              <p class="card-text">Responsive and modern website layouts using Bootstrap.</p>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card h-100 shadow-sm">
            <div class="card-body text-center">
              <h5 class="card-title">Development</h5>
              <p class="card-text">Clean and structured code to bring your website to life.</p>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card h-100 shadow-sm">
            <div class="card-body text-center">
              <h5 class="card-title">Support</h5>
              <p class="card-text">Ongoing support and updates for your web projects.</p>
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-5">
    <div class="container">
      <h2 class="mb-4">Contact Us</h2>
      <form>
        <div class="row g-3">
          <div class="col-md-6">
            <input type="text" class="form-control" placeholder="Your Name" required>
          </div>
          <div class="col-md-6">
            <input type="email" class="form-control" placeholder="Your Email" required>
          </div>
          <div class="col-12">
            <textarea class="form-control" rows="4" placeholder="Your Message" required></textarea>
          </div>
          <div class="col-12 text-center">
            <button type="submit" class="btn btn-primary">Send Message</button>
          </div>
        </div>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p class="mb-0">&copy; 2025 MySite. All Rights Reserved.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:
<img width="1920" height="1200" alt="Screenshot 2025-11-19 103833" src="https://github.com/user-attachments/assets/27fa4010-cfd2-463b-bb56-2f2c536a581e" />


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
