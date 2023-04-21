# Capstone-1-ver-

**BHOE LA DOHH
Established in summer 2021. 
BHOE LA DOHH means, “Let’s go to Tibet” in Tibetan Language. Our T-shirt design’s are illustrated and designed by talented Tibetan artist from New York, Canada and India. Our goal is to promote Tibetan arts and artists.

For every item purchase, we are donating 10% of the sales to Sambhota Sonada Hostel (C.S.T Sonada, Darjeeling). Our donation will help Tibetan students for better education and living facilities.

Bhoe-La-Dohh


## Site images
![homepage img](screenshots/image1.jpg)
![homepage img 2](screenshots/image%202.jpg)
![homepage img3](screenshots/image3.jpg)
![products img](screenshots/image%20r.jpg)
![products img](screenshots/image7.jpg)
![login page](screenshots/image%205.jpg)
![checkout page](screenshots/image8.jpg)


##Interesting piece of html
## navigation bar
<header>
        <nav class="navbar navbar-expand-lg navbar-dark fixed-top bg-dark bg-primary">
            <div class="container">
                <a class="navbar-brand" href="index.html">
                    <img src="images/logo.png" width="30" height="30" class="d-inline-block align-top"
                        alt="BHOE-LA-DOHH Logo">
                    BHOE-LA-DOHH
                </a>

                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse"
                    aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="navbarCollapse">
                    <ul class="nav navbar-nav mr-auto">
                        <li class="nav-item active">
                            <a class="nav-link" aria-current="page" href="index.html">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="products.html">Products</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="login.html">Login | Register</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text" href="checkout.html">Checkout</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text" href="https://www.instagram.com/bhoeladohh/"><img
                                    src="images/insta.png" width="30" height="30"></a>
                        </li>

                    </ul>
                </div>
            </div>
        </nav>
    </header>

##Another piece of code that uses HTML CSS and BOOSTRAP 
## Addding a carousel inside a card.

      <div class="row mt-5">

                <div class="col-lg-3 col-sm-6">

                    <div class="card rounded mb-4 shadow-sm">
                        <div id="welcomeCarousel" class="carousel slide carousel-fade" data-bs-ride="carousel"
                            data-interval="false">
                            <div class="carousel-inner">
                                <div class="carousel-item welcome-carousel-image1 active">
                                    <img class="d-blcok w-100 img-fluid rounded" src="images/potala/image1.jpg"
                                        alt="potala shirt 1">
                                </div>
                                <div class="carousel-item welcome-carousel-image2">
                                    <img class="d-blcok w-100 img-fluid rounded" src="images/potala/image2.jpg"
                                        alt="potala shirt 2">
                                </div>
                                <div class="carousel-item welcome-carousel-image3">
                                    <img class="d-blcok w-100 img-fluid rounded" src="images/potala/image3.jpg"
                                        alt="potala shirt 3">
                                </div>

                            </div>

                        </div>
                        <div class="card-body">
                            <h5 class="card-title">Potala</h5>
                            <p class="card-text">BHOE LA DOHH | Design by Sonam Wangmo</p>
                        </div>
                        <div class="card-footer">
                            <a href="potala.html" class="btn">
                                Buy Now
                            </a>
                        </div>
                    </div>
                </div>