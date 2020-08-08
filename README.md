<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>FARHOD</title>
	<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1">
	<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no"">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
	<!-- Optional theme -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
	<!-- Latest compiled and minified JavaScript -->
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
	<link rel="stylesheet" href="css/bootstrap.css">
<!-- <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous"> -->


	<script src="js/jquery.js"></script>
	<script src="js/bootstrap.js"></script>
	<link rel="stylesheet" href="css/animate.css">
	<link rel="stylesheet" type="text/css" href="css/normalize.css" />
		<link rel="stylesheet" type="text/css" href="fonts/font-awesome-4.3.0/css/font-awesome.min.css" />
		<link rel="stylesheet" type="text/css" href="fonts/vicons/vicons-font.css" />
		<link rel="stylesheet"
          href="https://fonts.googleapis.com/css2?family=Montserrat">
		<link rel="stylesheet" type="text/css" href="css/base.css" />
		<link rel="stylesheet" type="text/css" href="css/pagination.css" />


<style>
	h1{
		margin: 0;
	}
	.box{
		height: 100px;
		width: 10%;
		overflow: hidden;
		border: 1px solid red;
		background: #ff0;
		border-radius: 100%;
	}
	.hid-box{
		top: 100%;
		position: relative;
		transition: all .5s ease-out;
		background: #428bca;
		height: 100%;
	}
	.box:hover > .hid-box{
		top: 0;
	}
/*.container {
    display: grid;
    grid-template-columns: 100px 100px 100px;
    grid-template-rows: 50px 50px;
   
    display: grid;
    grid-template-columns: repeat(3, 100px);
    grid-template-rows: repeat(2, 50px);
    
    display: grid;
    grid-gap: 5px;
    grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
    grid-template-rows: repeat(2, 100px);
}
.container > div > img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.div.int{
	background-color: red;
	width: 100%;
	height: 100%;
	object-fit: cover;
	color: red;
}*/
.navbar{
	background-color: none;
}
.head{
	width: 100%;
	background-color: #333;
	position: relative;
	object-fit: cover;
	/*object-position: left;*/
	height: 45px;
	text-transform: uppercase;
}
.headd{
	width: 100%;
	background-color: #333;
	position: relative;
	object-fit: cover;
	/*object-position: left;*/
	height: 35px;
	text-transform: uppercase;
}
.tel{
	font-size: 13pt;
	/*letter-spacing: -1pt;*/
	font-family: Montserrat;
	color: rgb(237, 237, 237);
	text-align: center;
}
.tel:hover{
	/*text-decoration: none;
	text-underline-position: none;*/
}
.phtel{
	font-size: 24pt;
	color: rgb(63, 212, 199);
	transform: translateY(7px);
}
.phtell{
	font-size: 14pt;
	color: rgb(63, 212, 199);
	transform: translateY(9px);
}
.tel2{
	font-size: 9pt;
	/*letter-spacing: -1pt;*/
	font-family: Montserrat;
	color: rgb(237, 237, 237);
	text-align: center;
	transform: translateY(5.5px);
}
.location{
	font-size: 23pt;
	color: rgb(63, 212, 199);
	transform: translateY(7px);
	transform: translateX(10px;);
}
.locationn{
	font-size: 14pt;
	color: rgb(63, 212, 199);
	transform: translateY(7px);
	transform: translateX(10px;);
}
.location1{
	font-size: 13pt;
	/*letter-spacing: -1pt;*/
	font-family: Montserrat;
	color: rgb(237, 237, 237);
	text-align: center; 
}
.location2{
		font-size: 9pt;
	/*letter-spacing: -1pt;*/
	font-family: Montserrat;
	color: rgb(237, 237, 237);
	text-align: center;
	transform: translateY(5.5px);
}
.colll{
	text-align: right;
	/*padding-right: 50px;*/
	transform: translateY(-25px);
}
.langu{
	color: rgb(237, 237, 237);
	font-family: Montserrat;
	font-size: 13pt;
	border-width: 1px;

}
.lang1{
	color: rgb(63, 212, 199);
	font-size: 17pt;
	letter-spacing: 11pt;
}
.lang1:hover{
	text-decoration: none;
	opacity: 0.6;
	font-weight: bold;
}
.lang{
	color: rgb(237, 237, 237);
	font-size: 12pt;
}
.lang:hover{
	text-decoration: none;
	text-underline-position: none;
}
.colll1{
	text-align: right;
	/*padding-right: 50px;*/
	transform: translateY(-17px);
}
.header{
	width: 100%;
	background-color: none;
}
.tops{
	width: 100%;

}
</style>		
</head>
<body>
		<!-- <div class="container">
  <div><div class="int">ss</div></div>
  <div><div class="int">ss</div></div>
  <div><div class="int">ss</div></div>
  <div><div class="int">ss</div></div>
  <div><div class="int">ss</div></div>
  <div><div class="int">ss</div></div>
		</div> -->
<div class="hidden-xs">
<div class=" head">

	<div class="container-fluid">
		<div class="row">
			<div class="col-md-12">
				<a href="tel:+998712471630" class="fa fa-phone phtel hidden-xs"> </a>

				<!-- <a href="tel:+998712471630"><span class="fa fa-phone phtell visible-xs-inline-block"> </span> </a> -->

				<span style="color: #333; font-size: 2pt;">A</span>
				<a href="tel:+998712471630" class="hidden-xs tel">+998 71 247 16 30</a>
				<a href="#" class="visible-xs-inline-block tel2">Call now</a>
				
				<span style="color: #333; font-size: 10pt">lorem</span>

				<a href="#" class="fa fa-map-marker location hidden-xs"> </a>
				<a href="#" class="fa fa-map-marker locationn visible-xs-inline-block"> </a>
				<span style="color: #333; font-size: 2pt;">A</span>
				<a href="#" class="hidden-xs location1">DIRECTION</a>
				<a href="#" class="visible-xs-inline-block location2">DIRECTION</a>
				
			</div>
		</div>
	
				<div class="container-fluid-right">
					<div class="colll ">
						<span class="langu hidden-xs"> FOLLOW US </span>
						<span style="color: #333; font-size: 5pt;">lorem</span>
						<a href="#" class="fa fa-instagram lang1"></a>
						<a href="#" class="fa fa-telegram lang1"></a>
						<a href="#" class="fa fa-facebook lang1"></a>
						<span style="color: #333; font-size: 8pt;">lorem</span>
						<a href="#" class="lang">UZ  </a>
						<span class="lang"> | </span>
						<span class="lang" style="color: darkgray;"> RU</span>
					</div>
				</div>
				</div>
</div>
</div>
<div class="headd visible-xs-inline-block"> 
	<div class="container-fluid">
		<div class="row">
			<div class="col-md-12">
				
				<a href="tel:+998712471630" class="fa fa-phone phtell visible-xs-inline-block"> </a>
				<span style="color: #333; font-size: 2pt;">A</span>
				
				<a href="tel:+998712471630" class="visible-xs-inline-block tel2">Call now</a>
			
				<span style="color: #333; font-size: 5pt">lorem</span>

				
				<a href="#" class="fa fa-map-marker locationn visible-xs-inline-block"> </a>
				<span style="color: #333; font-size: 2pt;">A</span>
				
				<a href="#" class="visible-xs-inline-block location2">DIRECTION</a>
				

				<div class="container-fluid-right">
					<div class="colll1 ">
						<a href="#" class="lang">UZ  </a>
						<span class="lang"> | </span>
						<!-- <a href="index.html" class="lang" style="color: darkgray">  RU</a> -->
						<span class="lang" style="color: darkgray;"> RU</span>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
<div class="container-fluid tops">
	<div id="#top">
		<div class="header">
			<nav class="navbar bavbar-inverse navbar">
	<div class="container-fluid">
		<div class="navbar-header">
			<button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
				<span class="icon-bar fa fa-bars"></span>
				<span class="icon-bar"></span>
				<span class="icon-bar"></span>
			</button>
			<!-- <a href="tel:+998977777777" class="t2"><i class="fa fa-phone"></i></a> -->
			<a href="index.html" class="navbar-brand"><span style="font-family: Brush Script Std; text-align: center;">FARHOD</span></a>
		</div>
		<div class="collapse navbar-collapse navbar-right" id="myNavbar">
			<ul class="nav navbar-nav">
				<li><a href="#top" class="t2">ГЛАВНАЯ</a></li>
				<li><a href="#content1" class="t2">О НАС</a></li>
				<li><a href="#footer" class="t2">КОНТАКТЫ</a></li>
				
			</ul>
		</div>
	</div>
			</nav>
		</div>
	</div>
</div>



<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</body>
</html>
