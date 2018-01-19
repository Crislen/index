<!DOCTYPE html>
<html>

<head>
	<title></title>

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href="cssfile.css" rel="stylesheet" style="text/css">
 <script src="https://code.jquery.com/jquery-3.1.1.js"></script>
<script src="Login.js" style="text/javascript"></script>
<script src="jQuery v1.11.js" style="text/javascript"></script>

</head>


<body>


<!------------------------------- Nav bar for desktop------------------------------------->

	
<div>
	<nav id="nav">
		<ul class="navbtn">
			<li><a href="index.html">Home</a></li>
			<li><a href="Gallery.html">Gallery</a></li>	
			<li><a href="Lyrics.html">Lyrics</a>
			<li><a href="Games/Games.html">Games</li></a></li>
			<li><a href="Tutorial/Tutorial.html">Tutorials</a></li>
			<li><a href="AboutUs.html">About Us</a></li>	
		</ul>
		
	<nav>
</div>	
	
	


<!--========== LOG IN FORM  ==========================-->
<div>
	<button class="Login"> Log in </button>
</div>

<div class="boxing">
	<form>
		<label for="email">Email</label><br/>
			<input type="email" required placeholder="example@gmail.com"><br/></br>
					
		      <label for="email">Password</label><br/>
			      <input type="password" required placeholder="password">	<br/></br>
					
	      	<input type="checkbox" checked="checked"> Remember me
			        <br/>
			    <button class="loginbtn" type="submit">Log in</button>
				      <br/><br/>
		      <button type="button" 
			      class="cancelbtn"> Cancel</button>
				      <br/><br/>
		      <span class="psw"> Forgot <a href="#"> password? </a><span>
			      <br/>
	</form>
			<br/><br/>
		<div class="hide">Hide me</div>
		
</div>

	<!-- ================================================ Responsive nav bar ====================================-->
	
<div class="dropdown">

	<button class="dropbtn">Menu</button>
		<div class="dropdown-content">

			<a  href="index.html">Home</a>
			<a 	href="Gallery.html">Gallery</a>
			<a  href="Lyrics.html">Lyrics
			<a  href="Games/Games.html">Games</li></a>
			<a  href="Tutorial/Tutorial.html">Tutorials</a>
			<a  href="AboutUs.html">About Us</a>
			<a  href="AboutUs.html">Log in / Sign up</a>
		
	 </div>
</div>	




<!--==================================== HOME Section =========================================================-->

<div id="homepage">
	<img  src="pics/home-pic.jpg" style="width:100%">
	
</div>

<!--============================================== Body Link Section ==========================================-->

<div id="photos">
	<a href="Gallery.html">
	<img src="pics/photography.jpg" style="width:100%">
		
</div>
	
	
<div id="food">
	<a href="Lyrics.html">
	<img src="pics/foods.jpg" style="width:100%">	
</div>


<div id="game">
	<a href="Games/Games.html">
	<img src="pics/games.jpg" style="width:100%">		
</div>


<div id="tutorial">
	<a href="Tutorial/Tutorial.html">
	<img src="pics/tutorial.jpg" style="width:100%">			
</div>

</body>

<!-- ============================================FOOTER Section ===========================-->
<div id="footer">
	<a href="#">Help</a>
	<a href="#">Contact us</a>
	<a href="#">Suggestions</a>
	
</div>


</body>
</html>
