<!DOCTYPE html>
<html lang="lt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Mano Svetainė</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Mano Svetainė</a>
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Pagrindinis</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Apie</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Kontaktai</a></li>
        </ul>
      </div>
    </div>
  </nav>

  
  <div class="bg-light text-center text-white" style="background-image: url('https://picsum.photos/seed/beach/1200/400'); background-size: cover; background-position: center;">
    <div class="py-5" style="background-color: rgba(0,0,0,0.4);">
      <h1 class="display-5 fw-bold">Sveiki atvykę į mano svetainę!</h1>
      <p class="lead">Tai yra pavyzdinė svetainė, sukurta naudojant Bootstrap framework'ą</p>
      <a href="#" class="btn btn-primary">Sužinokite daugiau</a>
    </div>
  </div>

 
  <div class="container my-5 text-center">
    <h2>Lorem ipsum</h2>
    <img src="https://picsum.photos/seed/landscape/1000/400" class="img-fluid mt-3" alt="Pagrindinis vaizdas">
  </div>

  
  <div class="container my-5">
    <h2 class="text-center mb-4">Lorem ipsum dolor</h2>
    <div class="row text-center">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="https://picsum.photos/seed/hummingbird/400/250" class="card-img-top" alt="Vaizdas">
          <div class="card-body">
            <h5 class="card-title">Lorem, ipsum dolor.</h5>
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="https://picsum.photos/seed/bird/400/250" class="card-img-top" alt="Vaizdas">
          <div class="card-body">
            <h5 class="card-title">Lorem, ipsum.</h5>
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <a href="#" class="btn btn-secondary">Go somewhere</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="https://picsum.photos/seed/caterpillar/400/250" class="card-img-top" alt="Vaizdas">
          <div class="card-body">
            <h5 class="card-title">Lorem ipsum dolor sit.</h5>
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  
  <div class="container my-5">
    <h2 class="text-center mb-4">DUK</h2>
    <div class="accordion" id="faqAccordion">
      <div class="accordion-item">
        <h2 class="accordion-header" id="headingOne">
          <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident, quia perspiciatis! Explicabo?
          </button>
        </h2>
        <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#faqAccordion">
          <div class="accordion-body">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis, maiores cum!
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header" id="headingTwo">
          <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius veritatis non soluta illum?
          </button>
        </h2>
        <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
          <div class="accordion-body">
            Neque maxime natus accusamus itaque harum voluptatem odio aperiam quibusdam.
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header" id="headingThree">
          <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi?
          </button>
        </h2>
        <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
          <div class="accordion-body">
            veniam ipsam labore eum.
          </div>
        </div>
      </div>
    </div>
  </div>

 
  <footer class="bg-light text-center py-4">
    <p class="mb-0">&copy; 2024 Mano Svetainė</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
