# Farah89-Lab.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Photographer Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Jane Doe Photography</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="gallery.html">Gallery</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>
  
  <!-- Hero Section -->
  <header class="bg-light text-center py-5">
    <div class="container">
      <h1 class="display-4">Capturing Moments, Creating Memories</h1>
      <p class="lead">Welcome to my photography portfolio. Discover my work and let’s create beautiful stories together!</p>
      <a href="gallery.html" class="btn btn-primary btn-lg mt-3">View Gallery</a>
    </div>
  </header>

  <!-- Featured Images -->
  <section class="container my-5">
    <div class="row g-4">
      <div class="col-md-4">
        <img src="images/featured1.jpg" class="img-fluid rounded shadow" alt="Featured 1">
      </div>
      <div class="col-md-4">
        <img src="images/featured2.jpg" class="img-fluid rounded shadow" alt="Featured 2">
      </div>
      <div class="col-md-4">
        <img src="images/featured3.jpg" class="img-fluid rounded shadow" alt="Featured 3">
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    &copy; 2025 Jane Doe Photography. All rights reserved.
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
