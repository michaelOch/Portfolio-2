<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iReynolds</title>
    <!-- Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <!-- Bootstrap -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <!-- Animate CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.0.0/animate.min.css">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <!-- Custom Styles -->
    <link rel="stylesheet" href="./css/index.css" >
</head>
<body>
    <header class="header-section">
        <!-- Navbar -->
        <nav class="navbar fixed-top navbar-expand-lg navbar-light">
            <div class="container">
                <a class="navbar-brand navbar-brand_custom" href="#">iReynolds</a>
                <button class="navbar-toggler collapsed border-0" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                    <i class="fa fa-reorder text-blue"></i>
                    <i class="fa fa-close text-blue"></i>
                </button>
                <div class="collapse navbar-collapse" id="navbarNavDropdown">
                    <ul class="navbar-nav navbar-nav_custom ml-auto">
                        <li class="nav-item mx-auto px-2 nav-link_disappear active-item" style="width: max-content;">
                            <a class="nav-link active-link" href="">Home</a>
                        </li>
                        <li class="nav-item mx-3">
                            <a class="nav-link" href="#about">About</a>
                        </li>
                        <li class="nav-item mx-3">
                            <a class="nav-link" href="#education">Education/Work</a>
                        </li>
                        <li class="nav-item mx-3">
                            <a class="nav-link" href="#portfolio">Portfolio</a>
                        </li>
                        <li class="nav-item mx-3 nav-link_disappear">
                            <a class="nav-link" href="#what">What I Do</a>
                        </li>
                        <li class="nav-item mx-3">
                            <a class="nav-link" href="#contact">Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <div class="container header-section_content">
            <div class="d-flex align-items-center position-relative header-section_content-wrapper">
                <div class="mr-2 avatar-wrapper">
                    <img class="d-block" src="./img/profile-avatar.png" alt="profile avatar" >
                </div>
                <div class="">
                    <h1 class="wow animate__animated animate__bounceInDown">
                        Hi, <br>
                        I'm <br>
                        <span class="text-blue">Reynolds</span> <br>
                        A UI/UX <br>
                        DESIGNER
                    </h1>
                </div>
            </div>
        </div>
        <div id="about"></div>
    </header>
    <!-- About Section -->
    <section class="about-section">
        <div class="container text-center">
            <div class="row">
                <div class="col-md-5 mt-2">
                    <span class="pb-2 caption mb-3 mx-auto mobile-show" style="width: max-content;">ABOUT ME</span>
                    <img class="d-block w-100 h-100" src="./img/about-image.png" alt="" >
                </div>
                <div class="col-md-1 mt-2"></div>
                <div class="col-md-6 mt-2 text-left">
                    <span class="pb-2 caption mobile-hide" id="about">ABOUT ME</span>
                    <h3 class="text-blue mt-4 text-left">
                        Designer at day, <br>
                        Adult at night</h3>
                    <p class="text-left">
                        I ahave a couple of years experience in the areas of science and technology, ny foundation before moving on to UI design, to see my qualifications, get my resume.
                    </p>
                    <div class="d-flex justify-content-start">
                        <button type="submit" class="btn btn-blue mr-2 mt-2">Download Resume</button>
                        <button type="submit" class="btn btn-black mt-2">Hire Me</button>
                    </div>
                </div>
            </div>
        </div>
        <div id="education"></div>
    </section>
    <!-- Education Section -->
    <section class="education-section">
        <div class="container text-center">
            <span class="pb-2 caption">EDUCATION/WORK</span>
            <div class="row mobile-hide">
                <div class="col-md-4 mt-5">
                    <h3 class="">2011</h3>
                </div>
                <div class="col-md-4 mt-5">
                    <h3 class="">2014</h3>
                </div>
                <div class="col-md-4 mt-5">
                    <h3 class="">2018</h3>
                </div>
            </div>
            <div class="position-relative horizontal-line mt-3 mobile-hide">
                <img class="ellipse1" src="./img/ellipse.png" alt="ellipse" >
                <img class="ellipse2" src="./img/ellipse.png" alt="ellipse" >
                <img class="ellipse3" src="./img/ellipse.png" alt="ellipse" >
            </div>
            <div class="row">
                <div class="col-md-4 mt-5 wow animate__animated animate__zoomIn">
                    <h4 class="mobile-show">2011</h4>
                    <div class="position-relative horizontal-line w-75 mx-auto my-3 mobile-show">
                        <img class="ellipse-custom" src="./img/ellipse12.png" alt="ellipse" >
                    </div>
                    <i class="fa fa-graduation-cap text-blue" aria-hidden="true"></i>
                    <p class="text-center mb-1">Junior</p>
                    <p class="text-center">All Saints School</p>
                </div>
                <div class="col-md-4 mt-5 wow animate__animated animate__zoomIn">
                    <h4 class="mobile-show">2014</h4>
                    <div class="position-relative horizontal-line w-75 mx-auto my-3 mobile-show">
                        <img class="ellipse-custom" src="./img/ellipse12.png" alt="ellipse" >
                    </div>
                    <i class="fa fa-graduation-cap text-blue" aria-hidden="true"></i>
                    <p class="text-center mb-1">Science (WEAC)</p>
                    <p class="text-center">Federal Science and Technical College</p>
                </div>
                <div class="col-md-4 mt-5 wow animate__animated animate__zoomIn">
                    <h4 class="mobile-show">2018</h4>
                    <div class="position-relative horizontal-line w-75 mx-auto my-3 mobile-show">
                        <img class="ellipse-custom" src="./img/ellipse12.png" alt="ellipse" >
                    </div>
                    <i class="fa fa-graduation-cap text-blue" aria-hidden="true"></i>
                    <p class="text-center mb-1">Computer Science (Bsc)</p>
                    <p class="text-center">Covenant University</p>
                </div>
            </div>
        </div>
        <div id="portfolio"></div>
    </section>
    <!-- Portfolio Section -->
    <section class="portfolio-section">
        <div class="container text-center">
            <span class="pb-2 caption">PORTFOLIO</span>
            <div class="portfolio-wrapper mt-5">
                <div class="wow animate__animated animate__bounceInUp portfolio-1">
                    <img class="" src="./img/portfolio-1.png" alt="" >
                </div>
                <div class="wow animate__animated animate__bounceInUp portfolio-2">
                    <img class="" src="./img/portfolio-2.png" alt="" >
                </div>
                <div class="wow animate__animated animate__bounceInUp portfolio-3">
                    <img class="" src="./img/portfolio-3.jpg" alt="" >
                </div>
                <div class="wow animate__animated animate__bounceInUp portfolio-4">
                    <img class="" src="./img/portfolio-4.png" alt="" >
                </div>
                <div class="wow animate__animated animate__bounceInUp portfolio-5">
                    <img class="" src="./img/portfolio-5.png" alt="" >
                </div>
                <div class="wow animate__animated animate__bounceInUp portfolio-6">
                    <img class="" src="./img/portfolio-6.png" alt="" >
                </div>
            </div>
            <button type="button" class="btn btn-blue">Load More</button>
        </div>
        <div id="what"></div>
    </section>
    <!-- What I Do Section -->
    <section class="what-section">
        <div class="container text-center">
            <span class="pb-2 caption">WHAT I DO</span>
            <div class="row mt-5">
                <div class="col-md-3 mt-2 wow animate__animated animate__zoomIn">
                    <div class="card card-body box-wrapper h-100 h-100">
                        <div class="position-relative mt-5 mb-3">
                            <img class="d-block mx-auto" src="./img/what1_1.png" alt="" >
                            <div class="image-overlay_1-1">
                                <img class="" src="./img/what1_2.png" alt="" >
                                <img class="" src="./img/what1_3.png" alt="" >
                                <img class="" src="./img/what1_4.png" alt="" >
                            </div>
                        </div>
                        <h6 class="text-center mb-5">Web Development</h6>
                    </div>
                </div>
                <div class="col-md-3 mt-2 wow animate__animated animate__zoomIn">
                    <div class="card card-body box-wrapper h-100">
                        <div class="position-relative mt-5 mb-3">
                            <img class="d-block mb-3 mx-auto" src="./img/what2_1.png" alt="" >
                        </div>
                        <h6 class="text-center mb-5">Web/App Design</h6>
                    </div>
                </div>
                <div class="col-md-3 mt-2 wow animate__animated animate__zoomIn">
                    <div class="card card-body box-wrapper h-100">
                        <div class="position-relative mt-5 mb-3">
                            <img class="d-block mb-3 mx-auto" src="./img/what3_1.png" alt="" >
                            <img class="image-overlay_3-1" src="./img/what3_2.png" alt="" >
                            <img class="image-overlay_3-2" src="./img/what3_3.png" alt="" >
                        </div>
                        <h6 class="text-center mb-5">Graphic Design</h6>
                    </div>
                </div>
                <div class="col-md-3 mt-2 wow animate__animated animate__zoomIn">
                    <div class="card card-body box-wrapper h-100">
                        <div class="position-relative mt-5 mb-3">
                            <img class="d-block mb-3 mx-auto" src="./img/what4_1.png" alt="" >
                            <img class="image-overlay_4-1" src="./img/what4_2.png" alt="" >
                            <img class="image-overlay_4-2" src="./img/what4_3.png" alt="" >
                        </div>
                        <h6 class="text-center mb-5">Logo Making</h6>
                    </div>
                </div>
            </div>
        </div>
        <div id="contact"></div>
    </section>
    <!-- Contact Section -->
    <section class="contact-section">
        <div class="container text-center">
            <span class="pb-2 caption">GET IN TOUCH</span>
            <div class="row mt-5 text-left">
                <div class="col-md-6 mt-2 card card-body d-flex flex-column justify-content-center contact-section_left">
                    <h5 class="text-blue">
                        I will not want you <br> 
                        to remain a stranger.
                    </h5>
                    <h6>Get in touch with me, I will reply promptly</h6>
                    <p>Let us create magic together.</p>
                    <div class="d-flex">
                        <div class="d-flex justify-content-center align-items-center mx-4">
                            <a href=""><i class="fa fa-facebook text-white" aria-hidden="true"></i></a>
                        </div>
                        <div class="d-flex justify-content-center align-items-center mx-4">
                            <a href=""><i class="fa fa-twitter text-white" aria-hidden="true"></i></a>
                        </div>
                        <div class="d-flex justify-content-center align-items-center mx-4">
                            <a href=""><i class="fa fa-linkedin text-white" aria-hidden="true"></i></a>
                        </div>
                        <div class="d-flex justify-content-center align-items-center mx-4">
                            <a href=""><i class="fa fa-envelope text-white" aria-hidden="true"></i></a>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 mt-2">
                    <form>
                        <div class="form-group mb-5">
                            <label for="name">Name</label>
                            <input type="text" class="form-control">
                        </div>
                        <div class="form-group mb-5">
                            <label for="email">Email</label>
                            <input type="email" class="form-control">
                        </div>
                        <div class="form-group mb-5">
                            <label for="message">Message</label>
                            <textarea class="form-control" rows="6"></textarea>
                        </div>
                        <div class="d-flex justify-content-center">
                            <button type="submit" class="btn btn-blue">Submit</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer Section -->
    <footer class="footer-section">
        <div class="container">
            <div class="d-flex justify-content-between align-items-center">
                <div class="">&copy; <span class="text-blue">iReynolds</span></div>
                <div class="d-flex align-items-center">
                    <ul class="mb-0">
                        <li class="mx-2">FACEBOOK</li>
                        <li class="mx-2">INSTAGRAM</li>
                        <li class="mx-2">TWITTER</li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
    
    <!-- Scripts -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    <!-- WOW JS -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/wow/1.1.2/wow.min.js" integrity="sha256-z6FznuNG1jo9PP3/jBjL6P3tvLMtSwiVAowZPOgo56U=" crossorigin="anonymous"></script>
    <script>
        new WOW().init();
    </script>
    <script>
        $('.navbar-collapse a').click(function(){
            $(".navbar-collapse").collapse('hide');
        });
    </script>
</body>
</html>