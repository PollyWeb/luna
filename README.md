<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Luna</title>
		<link rel="stylesheet" href="assets/css/style.css">
		<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css" integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l" crossorigin="anonymous">
	</head>
	<body>
		<header id="zaglavie">
			<div class="container">
				<div class="row">
					<div class="col-md-4">
						<div class="logo">
							<img src="assets/img/logo.png" alt="">							
						</div>
					</div>
					<div class="col-md-8">
						<nav>
							<ul>
								<li><a href="#zaglavie">Home</a>
								</li>
								<li><a href="#about">About us</a>
								</li>
								<li><a href="#service">Services</a>
								</li>
								<li><a href="#contactus">Contact us</a>
								</li>
							</ul>
						</nav>
					</div>
				</div>
				</div>
				<div class="col-md-12">
					<h1 > We make <span>web</span> better.</h1>
				</div>
			</div>
		</header>

		<section class="about">
			<div class="container">
				<div class="row">
					<div class="col-md-5">
						<h2 id="about">About us</h2>
						<hr>
					</div>
	            	<div class="col-md-7">
	            	<p>
	            		Luna is a starting web design agency with an yaun design team that creates innovative, 
	            		effective websites that capture your brand, improve your conversion rates, and maximize your 
	            		revenue to help grow your business and achieve your goals.
	            		
	            	</p>
	            	<p>
	            		In today’s digital world, your website is the first interaction consumers have with your business.
	            		<a href="#contactus">Contact us</a> today to tell us more about your business and start designing your custom website!
	            	</p>

	            	</div>

				</div>
			</div>
		</section>

		<section class="photos">
			<div class="container-fluid">
				<div class="row">
					<div class="col-md-3 pading-0">
						<img src="assets/img/slider1.jpg" alt="laptop">
					</div>
					<div class="col-md-3 pading-0">
						<img src="assets/img/slider2.jpg" alt="laptop">
					</div>
					<div class="col-md-3 pading-0">
						<img src="assets/img/slider3.jpg" alt="laptop">
					</div>
					<div class="col-md-3 pading-0">
						<img src="assets/img/slider4.jpg" alt="laptop">
					</div>
				</div>

			</div>
		</section>

		<section class="services">
			<div class="container">
				<div class="row">
					<div class="col-md-12">
						<h2 id="service">Our services</h2>
						<hr>
					</div>
				</div>
				<div class="row">
					<div class="col-md-4 item">
						<img src="assets/img/service1.jpg" alt="service">
						<h3>Beutiful design</h3>
						<p>
							We create a design that is beautiful, user-friendly and easy to maintain.
						</p>
					</div>
					<div class="col-md-4 item">
						<img src="assets/img/service2.jpg" alt="service">
						<h3>Best development</h3>
						<p>
							We design and build easy-to-use, highly functional and stunning websites.
						</p>
					</div>
					<div class="col-md-4 item">
						<img src="assets/img/service3.jpg" alt="service">
						<h3>Web promote</h3>
						<p>
							Customized web solutions for any type of business optimised for all devices.
						</p>
					</div>
				</div>

			</div>
		</section>
		 <section class="payments">
		 	<div class="container">
		 		<div class="row">
		 			<div class="col-md-6">
		 				<h2><span>Payme</span>
		 				Mobile app</h2>
		 				<p>
		 					Payme is a best & simplest way to create your own mobile payment app and fit in with as much information as you want. Perfect base to build an amazing app with easy navigation and intuitive UX.
		 				</p>
		 				<a href="#">see case study</a>
		 			</div>
		 			<div class="col-md-3">
		 				<img src="assets/img/payments.jpg" alt="payments">
		 			</div>
		 			<div class="col-md-3">
		 				<img src="assets/img/login.jpg" alt="login" class="login">
		 			</div>
				 	</div>
		</section>
		<section class="footer">
				 	<div class="sitemap" ><h3>Site map</h3>
				 		
				 		<div><h4><a href="#zaglavie">Home</a></h4> </div>
                        <div><h4><a href="#about">About us</a></h4></div>
				 		<div><h4><a href="#service">Services</a></h4></div>
				 		<div><h4><a href="#contactus">Contact</a></h4></div>
				 	</div>	
				 	<h3 id="contactus">Contact us</h3>
				 	<div class="forma">

						<form action="action_page.php">
						    <label for="fname">First Name</label>
						    <input type="text" id="fname" name="firstname" placeholder="Your name..">

						    <label for="lname">Last Name</label>
						    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

						    <label for="subject">Subject</label>
						    <textarea id="subject" name="subject" placeholder="Write something.." style="height:50px"></textarea>
						    <input type="submit" value="Submit">

						</form>
					</div>
				 		
		</section>
		<section class="footer2">
		 	<div class="col-md-5">
		 		<span>Cpyright   © 2021,<a href="zaglavie"> Luna</a></span><br>
		 		<span>ПГКМКС - гр.Варна    |    Симеон Раданов, VIII A клас</span>
		 	</div>
		 </section>

	</body>
</html>
