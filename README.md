<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL"
    crossorigin="anonymous"></script>
  <link rel="stylesheet" href="./style.css">
</head>

<body>
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Carousel</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll"
        aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarScroll">
        <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" aria-disabled="true">Disabled</a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
  <div id="carouselExampleCaptions" class="carousel slide">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
        aria-label="Slide 3"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3"
        aria-label="Slide 4"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="./erik-mclean-CKJYAcSc3WE-unsplash.jpg" height="450" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>First slide label</h5>
          <p>Some representative placeholder content for the first slide.</p>
          <button type="button" class="btn btn-primary btn-lg">Sign up Today</button>
        </div>
      </div>
      <div class="carousel-item">
        <img src="./erik-mclean-CKJYAcSc3WE-unsplash.jpg" height="450" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
        </div>
      </div>
      <div class="carousel-item">
        <img src="./erik-mclean-CKJYAcSc3WE-unsplash.jpg" height="450" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
        </div>
      </div>
      <div class="carousel-item">
        <img src="./erik-mclean-CKJYAcSc3WE-unsplash.jpg" height="450" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  <div class="container-md">
    <div class="d-flex flex-row gap-5 justify-content-sm-center pt-5 text-center">
      <div class="card align-items-center   border-0" style="width: 18rem;">
        <img src="./wallpaperbetter (1).jpg" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h4 class="card-title">Heading</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
            content.</p>
          <a href="#" class="btn btn-primary">Views details>></a>
        </div>
      </div>
      <div class="card align-items-center  border-0" style="width: 18rem;">
        <img src="./wallpaperbetter (1).jpg" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h4 class="card-title">Heading</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
            content.</p>
          <a href="#" class="btn btn-primary">Views details>></a>
        </div>
      </div>
      <div class="card  align-items-center  border-0" style="width: 18rem;">
        <img src="./wallpaperbetter (1).jpg" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h4 class="card-title">Heading</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
            content.</p>
          <a href="#" class="btn btn-primary">Views details>></a>
        </div>
      </div>
    </div>
    <div>
      <hr class="pt-3">
    </div>
    <div class="d-flex flex-row justify-content-between pt-5">
      <div class="d-flex flex-column justify-content-center"><strong>Lorem ipsum dolor sit amet, consectetur adipisicing
          elit. </strong> <br> Voluptates deleniti perferendis saepe corporis, <br>
        minus aspeate cum. Praesentium soluta nemo dignissimos deleniti totam!</div>
      <div>
        <img src="./wallpaperbetter (2).jpg" width="600" height="500" alt="">
      </div>
    </div>
    <div>
      <hr class="pb-3">
    </div>
    <div class="d-flex flex-row justify-content-between px-4"> <div>
        <img src="./wallpaperbetter (2).jpg" width="600" height="500" alt="">
      </div>
      <div class="d-flex flex-column justify-content-center px-4"><strong>Lorem ipsum dolor sit amet, consectetur adipisicing
          elit. </strong> <br> Voluptates deleniti perferendis saepe corporis, <br>
        minus aspeate cum. Praesentium soluta nemo dignissimos deleniti totam!</div>
     
    </div>
    <div>
      <hr class="pb-3">
    </div>
    <div class="d-flex flex-row justify-content-between pt-5">
      <div class="d-flex flex-column justify-content-center"><strong>Lorem ipsum dolor sit amet, consectetur adipisicing
          elit. </strong> <br> Voluptates deleniti perferendis saepe corporis, <br>
        minus aspeate cum. Praesentium soluta nemo dignissimos deleniti totam!</div>
      <div>
        <img src="./wallpaperbetter (2).jpg" width="600" height="500" alt="">
      </div>
    </div>
</body>

</html>
