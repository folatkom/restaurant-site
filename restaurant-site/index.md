<!doctype html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Industrial Pub</title>
	<link rel="stylesheet" href="css/bootstrap.min.css">
	<link rel="stylesheet" href="css/styles.css">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Xanh+Mono&display=swap" rel="stylesheet" type="text/css">
	
    

</head>
<body>
	<header>
		<nav id="header-nav" class="navbar navbar-default">
			<div class="container">
				<div class="navbar-header">
					<a href="index.html" class="pull-left visible-sm visible-md visible-lg">
						<div id="logo-img"></div>
					</a>
					<div class="navbar-brand">
						<a href="index.html"><h1>Industrial Pub</h1></a>
						<p>food & drink</p>
					</div>
					<!--button for small devices only-->
					<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#collapsable-nav" aria-expanded="false">
       					<span class="sr-only">Toggle navigation</span>
        				<span class="icon-bar"></span>
        				<span class="icon-bar"></span>
        				<span class="icon-bar"></span>
      				</button>
				</div>
				<div id="collapsable-nav" class="collapse navbar-collapse">
					<ul id="nav-list" class="nav navbar-nav navbar-right">
						<li>
							<a href="menu.html">
								<span class="glyphicon glyphicon-cutlery" aria-hidden="true"></span><br class="hidden-xs">Menu</a>
						</li>
						<li>
							<a href="drinks.html">
								<span class="glyphicon glyphicon-glass" aria-hidden="true"></span><br class="hidden-xs">Drinks</a>
						</li>
						<li>
							<a href="info.html">
								<span class="glyphicon glyphicon-info-sign" aria-hidden="true"></span><br class="hidden-xs">Info</a>
						</li>
						<li id="phone" class="hidden-xs pull-right">
							<a href="tel:500-400-300">
								<span class="glyphicon glyphicon-earphone"></span><span class="text-center"> 500-400-300</span></a>
						</li>
					</ul>
				</div>
			</div>
		</nav><hr>
	</header>

	<div id="call-btn" class="visible-xs">
		<a class="btn" href="tel:500-400-300">
			<span class="glyphicon glyphicon-earphone"></span> 500-400-300</a>
	</div>
	
	<div id="main-content" class="container">
		<div class="jumbotron">
			<img src="pics/marco-chilese-Gprl8lDVR9c-unsplash-1920px.jpg" alt="Picture of the restaurant" class="img-responsive visible-xs">
		</div>
		<div class="row">
			<div class="col-md-4 col-sm-6 col-xs-12">
				<a href="offers.html"><div id="specials-tile" class="row-element"><span>special offers</span></div></a>
			</div>
			<div class="col-md-4 col-sm-6 col-xs-12">
				<a href="cocktails.html"><div id="drinks-tile" class="row-element"><span>cocktails</span></div></a>
			</div>
			<div class="col-md-4 col-sm-12 col-xs-12">
				<a href="https://goo.gl/maps/esEFAN3M8DCdvZmZ9" target="_blank">
					<div id="map-tile" class="row-element">
					<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6650.23929364031!2d19.941065814260856!3d50.0110233707956!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x361056e30c510504!2sBonarka%20City%20Center!5e0!3m2!1spl!2spl!4v1612038436707!5m2!1spl!2spl" width="100%" height="250" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe><span>map</span></div></a>
			</div>
		</div>
	</div>

	<footer class="panel-footer">
		<div class="container">
			<div class="row">
				<section id="address" class="col-sm-4">
					<span>Address</span><br>
						Kamienskiego 11<br>
						30-644 Cracow
						<hr class="visible-xs">
				</section>
				<section id="hours" class="col-sm-4">
					<span>Opening hours</span><br>
						Sun-Thurs: 12pm-11pm<br>
						Fri-Sat: 12pm-1am
						<hr class="visible-xs">
				</section>
				<section id="delivery" class="col-sm-4">
					<span>Delivery</span><br>
					Free delivery in Cracow on orders over 20&euro;
				</section>
			</div>
			<div class="text-center">&copy; Copyright Monika Folatko 2021</div>
		</div>
	</footer>



	<script src="js/jquery-2.1.4.min.js"></script>
	<script src="js/bootstrap.min.js"></script>
	<script src="js/script.js"></script>
</body>
</html>