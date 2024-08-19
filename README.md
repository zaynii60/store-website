# store-website
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <script src="https://kit.fontawesome.com/983e89e942.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css"
        integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <title>Luxe Collection Store - Home</title>
</head>

<body>
    <!-- i am navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Luxe Collection Store</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="http://127.0.0.1:5500/index.html">Home <span
                            class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="http://127.0.0.1:5500/features.html">Sourcing</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                        data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Products
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <a class="dropdown-item" href="https://drive.google.com/drive/folders/1AQjaHbarySlqYD7ketlA0fyhtmHMxaIJ?usp=drive_link/https://drive.google.com/drive/folders/14fp7T-mm3PCi2b_Fcaan-zYAZm0oM01_?usp=drive_link">Bags/Wellets</a>
                        <a class="dropdown-item" href="https://drive.google.com/drive/folders/1tSF6SjoiTePUjqlo1LdcAS1FxYJUbPoX?usp=drive_link">Shouse/Belt</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="https://drive.google.com/drive/folders/1-ykteiuP8VKxTxHks2deo43z7XhasHNv?usp=drive_link">Jewellert/Belt</a>
                        <a class="dropdown-item" href="https://drive.google.com/drive/folders/15KbO29xokYt7YTIZKb0J8iSX0zl_A43y?usp=drive_link">Watch/Glasses</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="https://drive.google.com/drive/folders/1VtTDTnx1nl5pgkz0m5F494gnmsSjXTk2?usp=drive_link">Mobile Covers</a>
                        <a class="dropdown-item" href="https://drive.google.com/drive/folders/1a88_PshA4WfavwLpzh1ug2Acv9REK5VW?usp=drive_link">Winter Stock</a>
                    </div>
                </li>
                <li class="nav-item">
                    <a class="nav-link " href="http://127.0.0.1:5500/contact.html?#">Contact Us</a>
                </li>
            </ul>
            <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-light my-2 my-sm-0" type="submit">Search</button>
            </form>
            <div class="mx-2">
                <button class="btn btn-danger" data-toggle="modal" data-target="#loginModal">Login</button>
                <button class="btn btn-danger" data-toggle="modal" data-target="#signupModal">SignUp</button>
            </div>
        </div>
    </nav>

    <!-- login button navbar  -->
    <!-- Button trigger modal navbar-->

    <!-- Modal navbar-->
    <div class="modal fade" id="loginModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel"
        aria-hidden="true">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="loginModalLabel">Login to Luxe Collection Store</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
                <div class="modal-body">
                    <form>
                        <div class="form-group">
                            <label for="exampleInputEmail1">Email address</label>
                            <input type="email" class="form-control" id="exampleInputEmail1"
                                aria-describedby="emailHelp" placeholder="Enter email">
                            <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone
                                else.</small>
                        </div>
                        <div class="form-group">
                            <label for="exampleInputPassword1">Password</label>
                            <input type="password" class="form-control" id="exampleInputPassword1"
                                placeholder="Password">
                        </div>
                        <div class="form-group form-check">
                            <input type="checkbox" class="form-check-input" id="exampleCheck1">
                            <label class="form-check-label" for="exampleCheck1">Check me out</label>
                        </div>
                        <button type="submit" class="btn btn-primary">Login</button>
                    </form>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                </div>
            </div>
        </div>
    </div>
    <!-- signup  navbar-->
    <!-- Button trigger modal navbar -->

    <!-- Modal navbar-->
    <div class="modal fade" id="signupModal" tabindex="-1" role="dialog" aria-labelledby="signupModalLabel"
        aria-hidden="true">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="signupModalLabel">Get an Luxe Collection Store</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
                <div class="modal-body">
                    <form>
                        <div class="form-group">
                            <label for="exampleInputFullName">Full Name</label>
                            <input type="name" class="form-control" id="exampleInputFullName"
                                aria-describedby="nameHelp" placeholder="Enter name">
                        </div>
                        <div class="form-group">
                            <label for="exampleInputEmail1">Email address</label>
                            <input type="email" class="form-control" id="exampleInputEmail1"
                                aria-describedby="emailHelp" placeholder="Enter email">
                            <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone
                                else.</small>
                        </div>
                        <div class="form-group">
                            <label for="exampleInputPassword1">Password</label>
                            <input type="password" class="form-control" id="exampleInputPassword1"
                                placeholder="Password">
                        </div>
                        <div class="form-group">
                            <label for="cexampleInputPassword1">Confirm Password</label>
                            <input type="password" class="form-control" id="cexampleInputPassword1"
                                placeholder="Password">
                        </div>
                        <button type="submit" class="btn btn-primary">Create an Acount</button>
                    </form>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                </div>
            </div>
        </div>
    </div>
    <!-- navbar complete  -->
    <!-- i am hihi slider  -->
    <!-- i am carousel-slider  -->
    <div id="carouselExampleIndicators" class="carousel slide carousel-fade" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class=" " src="1bgc.png" alt="First slide" width="1520" height="500">
            </div>
            <div class="carousel-item">
                <img class=" " src="sjb.png" alt="Second slide" width="1520" height="500">
            </div>
            <div class="carousel-item">
                <img class=" " src="dress.png" alt="Third slide" width="1520" height="500">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only ">Next</span>
        </a>
    </div>

    <!-- i am 2nd blog -->
    <div class="container my-4">
        <div class="row mb-2">
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-success">PHYSICAL SHOP</strong>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Discover Our Convenient Store Location</a>
                        </h3>
                        <p class="card-text mb-auto">Visit our store to explore our products. Our team is ready to help
                            you find the perfect items.</p>
                        <a href="https://drive.google.com/drive/folders/1n94Bo5-VTBCpqP0fsIcAgPBkDqmPJnUw?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="physicalshop.jpg" alt="" style="width: 340px; height: 236px;">
                </div>
            </div>
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-warning">WAREHOUSE</strong>
                        <h3 class="mb-0">
                            <h3 class="mb-0">
                                <a class="text-dark" href="#">Discover Our Efficient Warehouse Operations</a>
                            </h3>
                            <p class="card-text mb-auto">Our advanced warehouse guarantees secure storage and fast
                                shipping with top-quality systems for reliable delivery.</p>
                            <a href="https://drive.google.com/drive/folders/1-RZONQUIh5wMTrOONU9hW35-Wbu1madx?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="warehouse.jpg" alt="" style="width: 170px; height: 236px;">
                </div>
            </div>
        </div>
    </div>
    <!-- i am blog -->
    <div class="container my-4">
        <div class="row mb-2">
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-primary">BAGS</strong>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Explore Our Exclusive Bag Collection</a>
                        </h3>
                        <p class="card-text mb-auto">Browse our stylish and functional bags. Whether you need a
                            messenger bag, a travel backpack, or a chic tote, we have the perfect option for you.</p>
                        <a href="https://drive.google.com/drive/folders/1AQjaHbarySlqYD7ketlA0fyhtmHMxaIJ?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="bag.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-danger">SHOUSE</strong>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Explore Our Premium Shoe Collection</a>
                        </h3>
                        <p class="card-text mb-auto">Explore our premium shoes for every occasion—sleek dress shoes,
                            comfortable sneakers, and stylish boots. Find your perfect pair and elevate your style.</p>
                        <a href="https://drive.google.com/drive/folders/1tSF6SjoiTePUjqlo1LdcAS1FxYJUbPoX?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="shouseheals.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
        </div>
    </div>

    <!-- i am 2nd blog -->
    <div class="container my-4">
        <div class="row mb-2">
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-success">WALLETS</strong>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Discover Our Premium Wallet Collection</a>
                        </h3>
                        <p class="card-text mb-auto">Explore our imported wallets, from sleek leather designs to
                            practical everyday options. Find the perfect wallet to match your style.</p>
                        <a href="https://drive.google.com/drive/folders/14fp7T-mm3PCi2b_Fcaan-zYAZm0oM01_?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="wellets.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-warning">WATCH</strong>
                        <h3 class="mb-0">
                            <h3 class="mb-0">
                                <a class="text-dark" href="#">Discover Our Premium Watch Collection</a>
                            </h3>
                            <p class="card-text mb-auto">Explore our curated watches, from elegant timepieces to durable
                                everyday options. The perfect watch to match your style and needs.</p>
                            <a href="https://drive.google.com/drive/folders/15KbO29xokYt7YTIZKb0J8iSX0zl_A43y?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="watch.png" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
        </div>
    </div>

    <!-- 3 -->
    <div class="container my-4">
        <div class="row mb-2">
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-primary">BELTS</strong>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Discover Our Premium Belt Collection</a>
                        </h3>
                        <p class="card-text mb-auto">Explore our imported belts, crafted with high-quality materials and
                            stylish designs. Find the perfect accessory, whether you prefer a classic leather belt or a
                            modern look.</p>
                        <a href="https://drive.google.com/drive/folders/1Z1avEqlpcOBEbV0sLg0b-I_Mwrgqz28C?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="belt.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-danger">HATS</strong>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Discover Our Stylish Hat Collection</a>
                        </h3>
                        <p class="card-text mb-auto">Explore our imported hats, with trendy designs and high-quality
                            materials. Find the perfect accessory, whether you prefer a classic cap or a fashionable
                            hat.</p>
                        <a href="https://drive.google.com/drive/folders/1CprQ-RAAYl2xQrJs-LuXozfB8G4_ZJ1L?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="hat.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
        </div>
    </div>
    <!-- i am 2nd blog -->
    <div class="container my-4">
        <div class="row mb-2">
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-success">SHIRT/DRESSES</strong>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Discover Our Premium Apparel Collection</a>
                        </h3>
                        <p class="card-text mb-auto">Explore our imported shirts and dresses, featuring high-quality
                            fabrics and stylish designs. Find the perfect outfit, whether classic or modern.</p>
                        <a href="https://drive.google.com/drive/folders/1tVwb24MaqoqKbwQPgnskd6c8LiS-r2ph?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="shirt.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-warning">WINTER STOCK</strong>
                        <h3 class="mb-0">
                            <h3 class="mb-0">
                                <a class="text-dark" href="#">Discover Our Cozy Winter Collection</a>
                            </h3>
                            <p class="card-text mb-auto">Explore our imported winter stock, featuring warm, high-quality
                                garments designed for style and comfort. Find the perfect pieces to keep you cozy this
                                season.</p>
                            <a href="https://drive.google.com/drive/folders/1a88_PshA4WfavwLpzh1ug2Acv9REK5VW?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="winterstock.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
        </div>
    </div>

    <!-- 4 -->

    <div class="container my-4">
        <div class="row mb-2">
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-primary">JEWELLERY</strong>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Discover Our Elegant Jewelry Collection</a>
                        </h3>
                        <p class="card-text mb-auto">Explore our range of imported jewelry, featuring exquisite designs
                            and high-quality materials. Find the perfect piece to add a touch of elegance to any outfit.
                        </p>
                        <a href="https://drive.google.com/drive/folders/1-ykteiuP8VKxTxHks2deo43z7XhasHNv?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="jewellery.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-danger">GLASSES</strong>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Discover Our Stylish Glasses Collection</a>
                        </h3>
                        <p class="card-text mb-auto">Explore our range of imported glasses, featuring fashionable
                            designs and high-quality lenses. Find the perfect pair to enhance your look and vision.</p>
                        <a href="https://drive.google.com/drive/folders/1SpssHBg3yZH9DzwpMk0ljPAKvT2wdhKx?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="glasses.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
        </div>
    </div>
    <!-- i am 2nd blog -->
    <div class="container my-4">
        <div class="row mb-2">
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-success">MOBILE COVERS</strong>
                        <h3 class="mb-0">
                            <a class="text-dark" href="#">Discover Our Trendy Mobile Covers</a>
                        </h3>
                        <p class="card-text mb-auto">Explore our range of imported mobile covers, designed with both
                            style and protection in mind. Find the perfect cover to keep your phone safe and
                            fashionable.</p>
                        <a href="https://drive.google.com/drive/folders/1VtTDTnx1nl5pgkz0m5F494gnmsSjXTk2?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="mobilecover.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
            <div class="col-md-6">
                <div class="card flex-md-row mb-4 box-shadow h-md-250">
                    <div class="card-body d-flex flex-column align-items-start">
                        <strong class="d-inline-block mb-2 text-warning">CUSTOMER REVIEWS</strong>
                        <h3 class="mb-0">
                            <h3 class="mb-0">
                                <a class="text-dark" href="#">Hear from Our Satisfied Customers</a>
                            </h3>
                            <p class="card-text mb-auto">Read reviews from our happy customers about their experiences
                                with our products and service. Discover why our customers trust us for quality and
                                satisfaction.</p>
                            <a href="https://drive.google.com/drive/folders/1jZgyBoSqb91XOO5TpQ6QxhW8Oqfd0jOQ?usp=drive_link">Google Drive Link...</a>
                    </div>
                    <img class="img-fluid" src="customerreviews.jpg" alt="" style="width: 170px; height: 259px;">
                </div>
            </div>
        </div>
    </div>
    <!-- i am footer  -->
    <!-- Remove the container if you want to extend the Footer to full width. -->
<div class="container-fluid p-0">

    <footer class="text-white text-lg-start bg-dark">
        <!-- Grid container -->
        <div class="container p-4">
            <!--Grid row-->
            <div class="row mt-4">
                <!--Grid column-->
                <div class="col-lg-4 col-md-12 mb-4 mb-md-0 text-start">
                    <h5 class="text-uppercase mb-4">About company</h5>

                    <p>
                        At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium
                        voluptatum deleniti atque corrupti.
                    </p>

                    <p>
                        Blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias.
                    </p>

                    <div class="mt-4">
                        <!-- Facebook -->
                        <a type="button" class="btn btn-floating btn-light btn-lg" style="background-color: #343a40;"><i class="fab fa-facebook-f"></i></a>
                        <!-- Dribbble -->
                        <a type="button" class="btn btn-floating btn-light btn-lg" style="background-color: #343a40;"><i class="fab fa-dribbble"></i></a>
                        <!-- Twitter -->
                        <a type="button" class="btn btn-floating btn-light btn-lg" style="background-color: #343a40;"><i class="fab fa-twitter"></i></a>
                        <!-- Google + -->
                        <a type="button" class="btn btn-floating btn-light btn-lg" style="background-color: #343a40;"><i class="fab fa-google-plus-g"></i></a>
                        <!-- Linkedin -->
                    </div>
                </div>
                <!--Grid column-->

                <!--Grid column-->
                <div class="col-lg-4 col-md-6 mb-4 mb-md-0">
                    <h5 class="text-uppercase mb-4 pb-1">Search something</h5>
          
                    <div class="form-outline form-white mb-4">
                      <input type="text" id="formControlLg" class="form-control form-control-lg" />
                      <label class="form-label" for="formControlLg">Search</label>
                    </div>
          
                    <ul class="fa-ul" style="margin-left: 1.65em;">
                      <li class="mb-3">
                        <span class="fa-li"><i class="fas fa-home"></i></span><span class="ms-2">UAE, 000-999, Dubai</span>
                      </li>
                      <li class="mb-3">
                        <span class="fa-li"><i class="fas fa-envelope"></i></span><span class="ms-2">storeluxecollection0@gmail.com</span>
                      </li>
                      <li class="mb-3">
                        <span class="fa-li"><i class="fas fa-phone"></i></span><span class="ms-2">+ 92 346 990 834</span>
                      </li>
                    </ul>
                  </div>
                <!--Grid column-->

                <!--Grid column-->
                <div class="col-lg-4 col-md-6 mb-4 mb-md-0 text-start">
                    <h5 class="text-uppercase mb-4">Opening hours</h5>

                    <table class="table text-white">
                        <tbody class="fw-normal">
                            <tr>
                                <td>Mon - Thu:</td>
                                <td>8am - 8pm</td>
                            </tr>
                            <tr>
                                <td>Fri - Sat:</td>
                                <td>9am - 10pm</td>
                            </tr>
                            <tr>
                                <td>Sunday:</td>
                                <td>12pm - 10pm</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <!--Grid column-->
            </div>
            <!--Grid row-->
        </div>
        <!-- Grid container -->

        <!-- Copyright -->
        <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
            © 2020 Copyright:
            <a class="text-white" href="https://drive.google.com/drive/folders/1pGaBJUEqlwNO48e1og0Ld7kBOUe7sYuN">LuxeCollectionStore.com</a>
        </div>
        <!-- Copyright -->
    </footer>

</div>
<!-- End of .container -->

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
        integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
        integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/js/bootstrap.min.js"
        integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6"
        crossorigin="anonymous"></script>
</body>

</html>
