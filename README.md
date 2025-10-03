# Create-a-simple-Blog-Layout-using-Bootstrap-5.
Use Bootstrap 5CDN to create a blog page with navbar, cards and footer.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Blog</title>
  <!-- Bootstrap 5 CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">My Blog</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" 
              data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" 
              aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Blog Container -->
  <div class="container my-5">
    <div class="row g-4">
      <!-- Card 1 -->
      <div class="col-md-4">
        <div class="card h-100 shadow">
          <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Blog Image">
          <div class="card-body">
            <h5 class="card-title">Blog Post Title</h5>
            <p class="card-text">This is a short description of the blog post. Learn more by clicking below.</p>
            <a href="#" class="btn btn-primary">Read More</a>
          </div>
        </div>
      </div>
      <!-- Card 2 -->
      <div class="col-md-4">
        <div class="card h-100 shadow">
          <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Blog Image">
          <div class="card-body">
            <h5 class="card-title">Another Post</h5>
            <p class="card-text">Quick summary of another blog post goes here.</p>
            <a href="#" class="btn btn-primary">Read More</a>
          </div>
        </div>
      </div>
      <!-- Card 3 -->
      <div class="col-md-4">
        <div class="card h-100 shadow">
          <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Blog Image">
          <div class="card-body">
            <h5 class="card-title">Latest Post</h5>
            <p class="card-text">Stay updated with the latest post from our blog.</p>
            <a href="#" class="btn btn-primary">Read More</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-light text-center py-3">
    <p>© 2025 My Blog | Follow us: 
      <a href="#" class="text-light mx-2"><i class="bi bi-facebook"></i></a>
      <a href="#" class="text-light mx-2"><i class="bi bi-twitter"></i></a>
      <a href="#" class="text-light mx-2"><i class="bi bi-instagram"></i></a>
    </p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <!-- Bootstrap Icons -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css" rel="stylesheet">
</body>
</html>

🔹 Features in This Code:
Navbar with brand & links.

Responsive cards using Bootstrap grid system (row + col-md-4).

Footer with social icons (using Bootstrap Icons).

Utility classes (my-5, shadow, btn-primary, etc.).

Responsive design (works on mobile, tablet, and desktop).
