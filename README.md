# WebProject
# Authors: Albert Linares, Abdoulaye Traore, Adem Kakhadze

# Code Progress
-------------------------------------------------------------------------------------------------------------------------------------
# Albert Linares:
<!DOCTYPE html>
<html>
<head>
	<title>Business Publications</title>
	<link rel="stylesheet" href="style.css">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
	<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
</head>
<body>
	<!--Navigational Bar-->
	<section id="nBar">
		<nav class="navbar navbar-expand-lg navbar-light">
  			<a class="navbar-brand" href="#"><img src="imgs/logo.png"></a>
  			<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    			<span class="navbar-toggler-icon"></span>
  			</button>
 			<div class="collapse navbar-collapse" id="navbarNav">
    			<ul class="navbar-nav ml-auto">
      				<li class="nav-item">
        				<a class="nav-link" href="#">Home</a>
      				</li>
      				<li class="nav-item">
        				<a class="nav-link" href="#">About Us</a>
      				</li>
      				<li class="nav-item">
        				<a class="nav-link" href="#">Publish</a>
      				</li>
      				<li class="nav-item">
        				<a class="nav-link" href="#">Contact Us</a>
      				</li>
    			</ul>
  			</div>
		</nav>
	</section>
------------------------------------------------------------------------------------------------------------------------------------- 
# Abdoulaye Traore:
<!--Image Slider-->
	<div id="slider">
		<div class="slides">
  			<div id="hSlider" class="carousel slide" data-ride="carousel">
    			<ol class="carousel-indicators">
      				<li data-target="#hSlider" data-slide-to="0" class="active"></li>
      				<li data-target="#hSlider" data-slide-to="1"></li>
      				<li data-target="#hSlider" data-slide-to="2"></li>
    			</ol>
    			<div class="carousel-inner">
      				<div class="carousel-item active">
        				<img src="imgs/1.jpg" class="d-block img-fluid">
        				<div class="carousel-caption d-none d-md-block">
          					<h5>Business Publications</h5>
          					<p>Your Central Hub for Publications.</p>
        				</div>
      				</div>
      				<div class="carousel-item">
        				<img src="imgs/2.jpg" class="d-block img-fluid">
        				<div class="carousel-caption d-none d-md-block">
          					<h5>Tell Them About You </h5>
          					<p>Give your company a voice, tell the world who you are and what you're looking for!</p>
        				</div>
      				</div>
      				<div class="carousel-item">
        				<img src="imgs/3.jpg" class="d-block img-fluid">
        				<div class="carousel-caption d-none d-md-block">
          					<h5>Expand</h5>
          					<p>Take your company to new heights and leave your mark on the world.</p>
        				</div>
      				</div>
    			</div>
    			<a class="carousel-control-prev" href="#hSlider" role="button" data-slide="prev">
      				<span class="carousel-control-prev-icon" aria-hidden="true"></span>
      				<span class="sr-only">Previous</span>
    			</a>
    			<a class="carousel-control-next" href="#hSlider" role="button" data-slide="next">
      				<span class="carousel-control-next-icon" aria-hidden="true"></span>
      				<span class="sr-only">Next</span>
    			</a>
  			</div>
		</div>
	</div>
  
  <!--About Us-->
	<section id="aboutUs">
		<div class="container">
			<div class="row">
				<div class="col-md-6">
					<h2>About Us</h2>
					<div class="about-content">
						<p>This website is more about giving back. We know how hard it is to get exposure for a Business/Company that is still growing. Here at Business Publications we've designed this website with one intention, and that is to help your Businesses expand.</p>
            <p>We have decided to become a central hub in which businesses or companies may publish information about what they do and what they are looking for in a customer, or if they are in need of workers, in a employee.</p>
					</div>
					<button type="button" class="btn btn-primary">Read more...
				</div>
				<div class="col-md-6 skills-bar">
					<p>skill one</p>
					<div class="progress">
						<div class="progress-bar" style="width: 80%;">80%
						</div>
					</div>
					<p>skill two</p>
					<div class="progress">
						<div class="progress-bar" style="width: 80%;">80%
						</div>
					</div>
					<p>skill three</p>
					<div class="progress">
						<div class="progress-bar" style="width: 80%;">80%
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
</body>
</html>
-------------------------------------------------------------------------------------------------------------------------------------
# Adem Kakhadze:
*
{
	margin: 0;
	padding: 0;
}

/*___Navagational Bar___*/
#nBar
{
	position: sticky;
	top: 0;
	z-index: 10;
}

.navbar-brand img
{
	/*Logo customizations*/
	height: 70px;
	padding-left: 30px;
}

.navbar-nav li
{
	padding: 0 10px;
}

.navbar-nav li a
{
	float: right;
	text-align: left;
}

#nBar ul li a:hover
{
	/*The Color for the tabs (while hovering)*/
	color: #FF0000!important;
}

.navbar
{
	background-color: #fff;
}

.navbar-toggler
{
	border: none!important;
}

.nav-link
{
	color: #555!important;
	font-weight: 600;
	font-size: 16px;
}

/*___Page Slider___*/
#slider
{
	width: 100%;
}

/*___About Us___*/
#aboutUs
{
	padding-top: 50px;
	padding-bottom: 50px;
	color: #555;
}

#aboutUs .btn
{
	margin-top: 20px;
	margin-bottom: 30px;
}

.about-content
{
	padding-top: 20px;
}

.skills-bars
{
	margin-bottom: 6px;
	font-weight: 600;
}

.progress-bar
{
	border-radius: 20px;
}

.progress
{
	border-radius: 16px;
	margin-bottom: 20px;
}
	


