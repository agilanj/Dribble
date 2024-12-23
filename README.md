# Project Responsive Web Design using Bootstrap
## Date: 23-12-2024

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
.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Simplified Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Explore</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Blog</a></li>
          <li class="nav-item"><a class="nav-link text-primary" href="#">Sign Up</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Log In</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="hero-section text-center text-white d-flex align-items-center justify-content-center">
    <div class="container">
      <h1 class="display-4 fw-bold">LUXURIOUS, CREATIVE AND COMFORTABLE INTERIORS</h1>
      <p class="lead">Explore work from the most talented and accomplished designers ready to take on your next project</p>
    <form class="d-flex justify-content-center mt-3">
        <input type="text" class="form-control w-50" placeholder="Search" />
      </form>
    </div>
  </header>

  <!-- Trending Searches Section -->
  <section class="py-5 text-center">
    <div class="container">
      <h2>Trending Searches</h2>
      <div class="d-flex flex-wrap justify-content-center mt-3">
        <a href="#" class="btn btn-primary m-1">Makeup</a>
        <a href="#" class="btn btn-outline-primary m-1">Skincare</a>
        <a href="#" class="btn btn-outline-primary m-1">Glam</a>
        <a href="#" class="btn btn-outline-primary m-1">Selfcare</a>
        <a href="#" class="btn btn-outline-primary m-1">dashboard</a>
        <a href="#" class="btn btn-outline-primary m-1">icons</a>
      </div>
    </div>
  </section>

  <!-- Featured Designs Section -->
  <section class="py-5 bg-light">
    <div class="container">
      <div class="row g-4">
        <!-- Example Card -->
        <div class="col-md-4">
            <div class="card shadow-sm">
              <img src="cos.png" class="card-img-top" alt="Foundation">
              <div class="card-body">
                <h5 class="card-title">Foundation</h5>
                <p class="card-text text-muted">7.2k Views</p>
              </div>
            </div>
          </div>
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="cos1.png" class="card-img-top" alt="Brush">
            <div class="card-body">
              <h5 class="card-title">Brush</h5>
              <p class="card-text text-muted">8.2k Views</p>
            </div>
          </div>
        </div>
        <!-- Repeat for other cards -->
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="cos2.png" class="card-img-top" alt="Lip Stick">
            <div class="card-body">
              <h5 class="card-title">Lip Stick</h5>
              <p class="card-text text-muted">9.2k Views</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="cos3.png" class="card-img-top" alt="Organizer">
            <div class="card-body">
              <h5 class="card-title">Organizer</h5>
              <p class="card-text text-muted">5.2k Views</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
            <div class="card shadow-sm">
              <img src="cos4.png" class="card-img-top" alt="LipGloss Container">
              <div class="card-body">
                <h5 class="card-title">LipGloss Container</h5>
                <p class="card-text text-muted">100k Views</p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card shadow-sm">
              <img src="cos5.png" class="card-img-top" alt="Spray Bottle">
              <div class="card-body">
                <h5 class="card-title">Spray Bottle</h5>
                <p class="card-text text-muted">105k Views</p>
              </div>
            </div>
          </div>
        <!-- Add more cards -->
      </div>
    </div>
  </section>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## OUTPUT:
![Screenshot (77)](https://github.com/user-attachments/assets/a6f897d6-a618-4422-aa0a-1bb325bba37e)
![Screenshot (78)](https://github.com/user-attachments/assets/24046db2-b50d-41c8-babc-27b22b641999)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
