<!doctype html>
<html lang="en">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

  <title>The Narrator</title>
</head>

<body>

  <!-- Navigation bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="/The-Narrator/"><b>The Narrator</b></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="/The-Narrator/">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/The-Narrator/about.html">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/The-Narrator/contact.html">Contact Me</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown"
              aria-expanded="false">
              Topics
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Technology</a></li>
              <li><a class="dropdown-item" href="#">Current Affair</a></li>
              <li><a class="dropdown-item" href="#">Self Experiences</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="/The-Narrator/contact.html">Write For Me</a></li>
            </ul>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>

  <!-- carausel -->
  <div id="carouselExampleCaptions" class="carousel slide carousel-fade" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
        aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="carousel1.jpg" width="1400" height="540" class="d-block w-100" alt="Error Loading the Image">
        <div class="carousel-caption d-none d-md-block">
          <h2><b>Welcome to The Narrator</b></h2>
          <h5>The Place Where You Can Update Yourself With Latest Tech & Get Some Unbiased Opinions</h5>
          <button type="button" class="btn btn-primary">Technology</button>
          <button type="button" class="btn btn-danger">World Affairs</button>
          <button type="button" class="btn btn-success">Self Experiences</button>
        </div>
      </div>
      <div class="carousel-item">
        <img src="carosel2.jpg" width="1400" height="540" class="d-block w-100" alt="Error Loading the Image">
        <div class="carousel-caption d-none d-md-block">
          <h2><b>These Blogs Will Give You A New Direction To Your Imagination</b></h2>
          <pre></pre>
          <button type="button" class="btn btn-primary">Technology</button>
          <button type="button" class="btn btn-danger">World Affairs</button>
          <button type="button" class="btn btn-success">Self Experiences</button>
        </div>
      </div>
      <div class="carousel-item">
        <img src="carosel3.jpg" width="1400" height="540" class="d-block w-100" alt="Error Loading the Image">
        <div class="carousel-caption d-none d-md-block">
          <h2><b>One Of The Most Active Blog On The Internet And Various Social Media Platforms</b></h2>
          <button type="button" class="btn btn-primary">Technology</button>
          <button type="button" class="btn btn-danger">World Affairs</button>
          <button type="button" class="btn btn-success">Self Experiences</button>
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

  <!-- 3circles -->

  <div class="container marketing my-5">

    <!-- Three columns of text below the carousel -->
    <div class="row">
      <div class="col-lg-4">
        <img src="circle1.jpg" alt="" class="bd-placeholder-img rounded-circle mx-auto d-block" width="140"
          height="140">
        <h2 class="text-center">Technology</h2>
        <p></p>
        <div class="d-flex justify-content-center">
          <button class="btn btn-primary">View More</button>
        </div>
      </div><!-- /.col-lg-4 -->

      <div class="col-lg-4">
        <img src="circle2.jpg" alt="Error Loading the Image" class="bd-placeholder-img rounded-circle mx-auto d-block" width="140"
          height="140">
        <h2 class="text-center">World Affairs</h2>
        <p>Another exciting bit of representative placeholder content. This time, we've moved on to the second column.
        </p>
        <div class="d-flex justify-content-center">
          <button class="btn btn-danger">View More</button>
        </div>
      </div><!-- /.col-lg-4 -->

      <div class="col-lg-4">
        <img src="circle3.jpg" alt="Error Loading the Image" class="bd-placeholder-img rounded-circle mx-auto d-block" width="140"
          height="140">
        <h2 class="text-center">Experiences</h2>
        <p>Here are my some Experiences which have left a lasting impression on me
          ahahhahahahakjssssssssjjjjjjjjjjjjjjjjjjjjjjjjjjjj.</p>
        <div class="d-flex justify-content-center">
          <button class="btn btn-success">View More</button>
        </div>
      </div><!-- /.col-lg-4 -->
    </div><!-- /.row -->

  </div>


  <!-- wild cards -->
  <hr>
  <div class="container my-4">
    <h2 class="text-center">HAVE A LOOK AT SOME OF OUR MOST VIEWED BLOGS</h2>
  </div>
  <div class="container my-4">
    <div class="row mb-2 my-4">
      <div class="col-md-6">
        <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-primary">Technology</strong>
            <h3 class="mb-0">Latest tech in the market</h3>
            <div class="mb-1 text-muted">Nov 12</div>
            <p class="card-text mb-auto">This is a wider card with supporting text below as a natural lead-in to
              additional content.</p>
            <a href="#" class="stretched-link">Continue reading</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <img class="bd-placeholder-img" src="https://source.unsplash.com/1400x570/?experience,knowledge" width="200"
              height="250" alt="Error Loading the Image">

          </div>
        </div>
      </div>

      <div class="col-md-6">
        <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-primary">Technology</strong>
            <h3 class="mb-0">Latest tech in the market</h3>
            <div class="mb-1 text-muted">Nov 12</div>
            <p class="card-text mb-auto">This is a wider card with supporting text below as a natural lead-in to
              additional content.</p>
            <a href="#" class="stretched-link">Continue reading</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <img class="bd-placeholder-img" src="https://source.unsplash.com/1400x570/?experience,knowledge" width="200"
              height="250" alt="Error Loading the Image">

          </div>
        </div>
      </div>

      <div class="col-md-6">
        <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-primary">Technology</strong>
            <h3 class="mb-0">Latest tech in the market</h3>
            <div class="mb-1 text-muted">Nov 12</div>
            <p class="card-text mb-auto">This is a wider card with supporting text below as a natural lead-in to
              additional content.</p>
            <a href="#" class="stretched-link">Continue reading</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <img class="bd-placeholder-img" src="https://source.unsplash.com/1400x570/?experience,knowledge" width="200"
              height="250" alt="Error Loading the Image">

          </div>
        </div>
      </div>

      <div class="col-md-6">
        <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-primary">Technology</strong>
            <h3 class="mb-0">Latest tech in the market</h3>
            <div class="mb-1 text-muted">Nov 12</div>
            <p class="card-text mb-auto">This is a wider card with supporting text below as a natural lead-in to
              additional content.</p>
            <a href="#" class="stretched-link">Continue reading</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <img class="bd-placeholder-img" src="https://source.unsplash.com/1400x570/?experience,knowledge" width="200"
              height="250" alt="Error Loading the Image">

          </div>
        </div>
      </div>
    </div>
  </div>
  </hr>

  <hr>
</hr>

<footer class="container my-5">
    <p class="float-end"><a href="/The-Narrator/index.html">Back to top</a></p>
    <p>?? 2022???2023 The Narrator, Inc. ?? <a href="#">Privacy</a> ?? <a href="#">Terms</a></p>
  </footer>
  <!-- Dissmissable alert  -->
  <!-- <div class="alert alert-success alert-dismissible fade show"  role="alert" >
    <strong>Welcome Back!</strong> Check out my <a href="#" class="alert-link">Latest Blog</a> Give it a click.
    <span class="badge rounded-pill bg-primary">NEW</span>
    <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
  </div> -->

  <!-- Adding card to show our summary of anything so that it can be clicked Various types of card can be used from documentation  -->
  <!-- <div class="card" style="width: 18rem;">
      <img src="https://source.unsplash.com/400x400/?code" class="card-img-top" alt="...">
      <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
      </div>
  </div> -->

  <!-- Optional JavaScript; choose one of the two! -->

  <!-- Option 1: Bootstrap Bundle with Popper -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
    crossorigin="anonymous"></script>

  <!-- Option 2: Separate Popper and Bootstrap JS -->
  <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
</body>

</html>
