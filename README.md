
<!DOCTYPE html>
<html>
<head>
	<title>Milan Anand Raj</title>
	<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">

<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

<!-- Popper JS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>

<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

<link href='https://fonts.googleapis.com/css?family=Aclonica' rel='stylesheet'>
<script src="https://use.fontawesome.com/0da967aa07.js"></script>
<style type="text/css">
body{
  font-family: Aclonica;
}
	.parallax {
  /* The image used */
  background-image: url("https://amymhaddad.s3.amazonaws.com/morocco-blue.png");
  /* Set a specific height */
  min-height: 710px; 
  min-width: 100%;

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}




.content {
  padding: 100px;
}

.sticky {
  position: fixed;
  top: 0;
  width: 100%;
  background-color:   #B1F085
}

.sticky + .content {
  padding-top: 60px;
}



@media (max-width: 768px) {
    .carousel-inner .carousel-item > div {
        display: none;
    }
    .carousel-inner .carousel-item > div:first-child {
        display: block;
    }
}

.carousel-inner .carousel-item.active,
.carousel-inner .carousel-item-next,
.carousel-inner .carousel-item-prev {
    display: flex;
}

/* display 3 */
@media (min-width: 768px) {
    
    .carousel-inner .carousel-item-right.active,
    .carousel-inner .carousel-item-next {
      transform: translateX(33.333%);
    }
    
    .carousel-inner .carousel-item-left.active, 
    .carousel-inner .carousel-item-prev {
      transform: translateX(-33.333%);
    }
}

.carousel-inner .carousel-item-right,
.carousel-inner .carousel-item-left{ 
  transform: translateX(0);
}


</style>
</head>
<body>

<div class="container-fluid">
  <div class="row"> 


<div class="parallax" style="text-align: center;">
<div><h1>Welcome Amigos</h1></div>
<div id="navbar">
  <div style="text-align: center;padding: 10px; z-index: 1.0"><h3>Vishwajeet Singh's Portfolio</h3></div>
</div>
  <div class="container" style="z-index: -1">
     <div class="row">
        <div class="col-sm-4" style="padding:10px;">
        <img src="fgeek.png" style="height: 45%;" class="img-responsive">
        <div style="padding: 20px;font-weight: bolder;font-size: 25px;">
          -:Coding Profiles:-
          <a href="https://www.hackerrank.com/vsrnitp" style="text-decoration: none;color: teal;">1.Hackerrank</a>
          <a href="https://www.codechef.com/users/vsrnitp" style="text-decoration: none;color: teal;">2.Codechef</a>
        </div>

        </div>
        <div class="col-sm-8" style="padding:30px; color: teal;">
          <h2 style="padding: 10px;text-decoration: underline;">Vishwajeet's Credentials</h2>
          <div style="color: black;font-size: 25px;">
          <p>Designation: - Student</p>
          <p>Studies At: - NIT,Patna</p>
          <p>Pursuing Majors In: - Computer Science</p>
          <p>Skill Stack: - Competetive Programming / Web Dev / ML</p>
          <p>Tech Stack: - C++ / JavaScript / Node.JS / Python / React.JS / MongoDB</p>
         </div>
        </div>
     </div>
  </div>

<div style="text-align: center;"><h2 style="color: teal;text-decoration: underline;">-:Projects:-</h2></div>

<!-- CARD CAROUSAL -->


<div class="container text-center my-3">
    <div class="row mx-auto my-auto">
        <div id="recipeCarousel" class="carousel slide w-100" data-ride="carousel">
            <div class="carousel-inner w-100" role="listbox">
                <div class="carousel-item active">
                    <div class="col-md-4">
                        <div class="card card-body" style="height: 100%; background-image: linear-gradient(#2C3E50, #FD746C); color: black;">
                            <h3 style="text-decoration: underline;color: black;"><P>Projetct 1</P></h3>
                            <h5>
                            <p>Name: - BahiKhata</p>
                            <P>Description: - A basic ledger for keeping track of your business.</P>
                            <p>Github Repo: - <a href="https://github.com/vsrnitp/bahiKhata">Github/BahiKhata</a></p>
                            <p>Link to Website: - <a href="https://bahikhata--vishwajeetsingh.repl.co/">BahiKhata</a></p>
                            <p>Used Technology: - Node.JS,MongoDb,EJS</p>
                          </h5>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="col-md-4">
                        <div class="card card-body" style="color: black; height: 100%; background-image: linear-gradient(#e96443, #904e95);">
                             <h3 style="text-decoration: underline;color: black;"><P>Projetct 2</P></h3>
                            <h5>
                            <p>Name: - IEEE NITP Website</p>
                            <P>Description: - Official IEEE Student chapter website of NIT Patna.</P>
                            <p>Github Repo: - <a href="https://github.com/vsrnitp/ieeeSbNITP-Website">Github/IEEE NITP Web</a></p>
                            <p>Link to Website: - <a href="http://ieee.nitp.ac.in/new/index.html">IEEE Nitp</a></p>
                            <p>Used Technology: - HTML,CSS,JS</p>
                          </h5>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="col-md-4">
                        <div class="card card-body" style="height: 100%;background-image: linear-gradient(#2C3E50, #FD746C); color: black;">
                             <h3 style="text-decoration: underline;color: black;"><P>Projetct 3</P></h3>
                            <h5>
                            <p>Name: - Track-Your-Run</p>
                            <P>Description: - A simple running tracker app based on Haversine formula.</P>
                            <p>Github Repo: - <a href="https://github.com/vsrnitp/Track-Your-Run">Github/TrackYourRun</a></p>
                            <p>Used Technology: - React-Native</p>
                          </h5>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="col-md-4">
                        <div class="card card-body" style="height: 100%;background-image: linear-gradient(#e96443, #904e95); color: black;">
                              <h3 style="text-decoration: underline;color: black;"><P>Projetct 4</P></h3>
                            <h5>
                            <p>Name: - Django CRUD app</p>
                            <P>Description: - A basic CRUD application written in Django (Can be tested using Postman).</P>
                            <p>Github Repo: - <a href="https://github.com/vsrnitp/rest_api_in_Django">Github/DjangoRestApi</a></p>
                            <p>Used Technology: - Django,Python</p>
                          </h5>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="col-md-4">
                        <div class="card card-body"  style="height: 100%;background-image: linear-gradient(#2C3E50, #FD746C); color: black;">
                              <h3 style="text-decoration: underline;color: black;"><P>Projetct 5</P></h3>
                            <h5>
                            <p>Name: - GOT Death Predictor</p>
                            <P>Description: - A simple ML model based on linear-regression to predict the death year of Game of Thrones characters.</P>
                            <p>Github Repo: - <a href="https://github.com/vsrnitp/MACHINE-LEARNING-PRACTICE/blob/master/GOT%20DeathPredictor.ipynb">Github/GOTDeathPredictor</a></p>
                            <p>Used Technology: - Python,ML</p>
                          </h5>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="col-md-4">
                        <div class="card card-body"  style="height: 100%;background-image: linear-gradient(#e96443, #904e95); color: black;">
                             <h3 style="text-decoration: underline;color: black;"><P>Projetct 6</P></h3>
                            <h5>
                            <p>Name: - Authentication App</p>
                            <P>Description: - Node.js and moongoose based project for authentication using JSON web Tokens.</P>
                            <p>Github Repo: - <a href="https://github.com/vsrnitp/auth">Github/auth</a></p>
                            <p>Used Technology: - Node.JS,MongoDB,Mongoose</p>
                          </h5>
                        </div>
                    </div>
                </div>
            </div>
            <a class="carousel-control-prev w-auto" href="#recipeCarousel" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon bg-dark border border-dark rounded-circle" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next w-auto" href="#recipeCarousel" role="button" data-slide="next">
                <span class="carousel-control-next-icon bg-dark border border-dark rounded-circle" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </div>
    
</div>


<div> 

<div class="container">
  <div class="row">
      <div class="col-sm-3">
        
      </div>
      <div class="col-sm-6" style="font-weight: bolder;font-size: 25px;padding: 15px;text-decoration: underline;">
        -:Some useful links:-
        <div style="font-size: 55px;">
          <a href="https://github.com/vsrnitp" style="text-decoration: none;color: black;">
          <i class="fa fa-github" aria-hidden="true"></i>
        </a>
        </div>
      </div>
      <div class="col-sm-3">
        
      </div>
  </div>
</div>

</div>


</div>


  </div>
</div>



<script>
window.onscroll = function() {myFunction()};

var navbar = document.getElementById("navbar");
var sticky = navbar.offsetTop;

function myFunction() {
  if (window.pageYOffset >= sticky) {
    navbar.classList.add("sticky")

  } else {
    navbar.classList.remove("sticky");
  }
}




$('#recipeCarousel').carousel({
  interval: 3000
})

$('.carousel .carousel-item').each(function(){
    var minPerSlide = 3;
    var next = $(this).next();
    if (!next.length) {
    next = $(this).siblings(':first');
    }
    next.children(':first-child').clone().appendTo($(this));
    
    for (var i=0;i<minPerSlide;i++) {
        next=next.next();
        if (!next.length) {
          next = $(this).siblings(':first');
        }
        
        next.children(':first-child').clone().appendTo($(this));
      }
});
</script>

</body>
</html>
