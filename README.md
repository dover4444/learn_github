<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>home</title>
  <!-- link css-->
  <link rel="stylesheet" href="/css/bootstrap.min.css">
  <link rel="stylesheet" href="style.css">

  <!-- end link css -->

  <!-- link js -->
  <script src="/js/bootstrap.min.js"></script>

  <!-- end link js -->

</head>

<body>
  <!-- NAVBAR -->

  <header class="py-3 mb-4 border-bottom">
    <div class="container d-flex flex-wrap justify-content-center">
      <a href="/" class="d-flex align-items-center mb-3 mb-lg-0 me-lg-auto text-dark text-decoration-none">
        <svg class="bi me-2" width="40" height="32">
          <use xlink:href="#bootstrap"></use>
        </svg>
        <span class="fs-4">Dove SHOp</span>
      </a>
      <div>
        <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
          <li><a href="#" class="nav-link px-2 link-secondary">หน้าแรก</a></li>
          <li><a href="#" class="nav-link px-2 link-dark">สินค้าทั้งหมด</a></li>
          <li><a href="#" class="nav-link px-2 link-dark">Pricing</a></li>
          <li><a href="#" class="nav-link px-2 link-dark">สอบถาม</a></li>
          <li><a href="#" class="nav-link px-2 link-dark">About</a></li>
        </ul>
      </div>
      <div></div>

      <form class="col-12 col-lg-auto mb-3 mb-lg-0" role="search">
        <input type="search" class="form-control" placeholder="Search..." aria-label="Search">
      </form>
    </div>
  </header>
  <!-- END -->



  <!-- slide -->
  <div class="container">
  <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="10000">
      <img src="image/images.jpg" class="d-block w-100" alt="..." height="400px">
    </div>
    <div class="carousel-item" data-bs-interval="2000">
      <img src="image/imagesh.jpg" class="d-block w-100" alt="..."height="400px">
    </div>
    <div class="carousel-item">
      <img src="image/index.jpg" class="d-block w-100" alt="..."height="400px">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</div>
  <!-- end -->

  <!-- content -->


  <!-- end -->

</body>

</html>
