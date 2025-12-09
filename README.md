<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>GRN Consulting - Home</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Bootstrap -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css">
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js"></script>

  <!-- Custom CSS -->
  <link href="styles.css" rel="stylesheet">
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="index.html">GRN Consulting</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a class="nav-link" href="register.html">Register</a></li>
        <li class="nav-item"><a class="nav-link" href="reports.html">Reports</a></li>
        <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="jumbotron text-center bg-light">
    <h1 class="display-4">Welcome to GRN Consulting</h1>
    <p class="lead">Expert market research in cancer testing, hematology, automation/AI, and point-of-care diagnostics</p>
    <a href="reports.html" class="btn btn-primary btn-lg">Explore Reports</a>
    <a href="contact.html" class="btn btn-outline-secondary btn-lg">Contact Us</a>
    .hero-banner {
  background: url("images/hero-bg.jpg") no-repeat center center/cover;
}
  </div>

  <!-- Services Section -->
  <div class="container my-5">
    <div class="row">
      <div class="col-md-4 text-center">
        <h3>Custom Research</h3>
        <p>Tailored insights to meet your diagnostic testing needs.</p>
      </div>
      <div class="col-md-4 text-center">
        <h3>Ready-Made Reports</h3>
        <p>Access comprehensive reports instantly for faster decision-making.</p>
      </div>
      <div class="col-md-4 text-center">
        <h3>Consulting Expertise</h3>
        <p>Strategic guidance to empower your business growth.</p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="text-center bg-dark text-white p-3">
    <p>&copy; 2025 GRN Consulting | Rockville, MD</p>
  </footer>
</body>
</html>
