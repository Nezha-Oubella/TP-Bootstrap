# TP-Bootstrap
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <title>Tp Bootstrap</title>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark  fixed-top bg-dark">
        <div class="container-fluid p-2">
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0 ms-3">
            <li class="nav-item px-3">
                <a class="nav-link" href="#">Logo</a>
            </li>
              <li class="nav-item px-3">
                <a class="nav-link active" aria-current="page" href="#">Aceuil</a>
              </li>
              <li class="nav-item px-3">
                <a class="nav-link" href="#">Services</a>
              </li>
              <li class="nav-item px-3">
                <a class="nav-link" href="#">Contact</a>
              </li>
             
            </ul>
            <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-light" type="submit">Go</button>
              </form>
          </div>
        </div>
      </nav>
      <br><br><br>
      <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner ">
          <div class="carousel-item active">
            <img src="https://picsum.photos/1000/400?12" class="d-block w-100" alt="slid1 mp-12">
          </div>
          <div class="carousel-item">
            <img src="https://picsum.photos/1000/400?34" class="d-block w-100" alt="slid2 mp-12">
          </div>
          <div class="carousel-item">
            <img src="https://picsum.photos/1000/400?56" class="d-block w-100" alt="slid3 mp-12">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <br>
      <div class="container">
        <div class="row">
            <div class="card col-lg mt-5" >
              <div class="row">
                <div class="col-md-6 col-lg-12">
                <img src="https://picsum.photos/1500/480" class="card-img-top" alt="...">
                </div>
                <div class="col-md-6 col-lg-12">
                <div class="card-body">

                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
                </div>
                </div>
              </div>

              <div class="card col-lg mt-5" >
                <div class="row">
                  <div class="col-md-6 col-lg-12">
                  <img src="https://picsum.photos/1500/603" class="card-img-top" alt="...">
                  </div>
                  <div class="col-md-6 col-lg-12">
                  <div class="card-body">
  
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  </div>
                  </div>
                  </div>
              </div>
              <div class="card col-lg mt-5" >
                <div class="row">
                  <div class="col-md-6 col-lg-12">
                  <img src="https://picsum.photos/1500/505" class="card-img-top" alt="...">
                  </div>
                  <div class="col-md-6 col-lg-12">
                  <div class="card-body">
  
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  </div>
                  </div>
                  </div>
              </div>
        </div>
    </div>
</br>
      <div class="m-10 container d-none d-lg-block">
          <h2>Notre équipe</h2>
          <div class="container-fluid mt-5" style="text-align: center;">
              <div class="row ">
              <div class="  col rounded-circle W-80">
                  <img src="https://picsum.photos/250/250?1" alt="" class="rounded-circle w-10 z-depth-2"></br>
                  <h3 >Nezha OUBELLA</h3>

              </div>
              <div class=" col rounded-circle w-80">
                <img src="https://picsum.photos/250/250?2" alt="" class="rounded-circle w-10 z-depth-2"></br>
                <h3>Fatima AFA</h3>

            </div>
            <div  class="  col rounded-circle w-80 ">
                <img src="https://picsum.photos/250/250?3" alt="" class="rounded-circle w-10 z-depth-2"></br>
                <h3>Laila AKHMARI</h3>

            </div>
          </div>
      </div>
      </div>
    </br>

    <div class="card mb-3" >
      <div class="row g-0 flex-row-reverse">
        <div class="col-md-8">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3319.1649224451016!2d-7.362641985454823!3d33.70468114341428!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xda7b6d0db170185%3A0x79759da1a916fc50!2sENSET%20Mohammedia!5e0!3m2!1sfr!2sma!4v1647549106865!5m2!1sfr!2sma" width="100%" height="350" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
        <div class="col-md-4">
          <div style="padding: 12% 10%;">
            <h5 class="card-title"><i class="bi bi-telephone"></i> (212) 5 10 36 48 00 / (212) 5 10 36 48 55
            </h5>
            <h5 class="card-title"><i class="bi bi-envelope"></i> n.oubella@etu.enset-media.ac.ma</h5>
            <h5 class="card-title"><i class="bi bi-geo-alt"></i>Mohammedia</h5>
        </div>
        </div>
      </div>
    </div>

      </body>
    <footer>

    </footer>
    
      
</body>
</html>
