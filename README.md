Portfolio
=========
```html
<!DOCTYPE html>
<html>
	<!-- HEAD -->
	<head>
		<link rel="stylesheet" href="css/core.css">
		<link rel="stylesheet" href="css/index.css">
		<script src="js/jquery-1.11.0.min.js"></script>
		<script type="text/javascript">
		$(document).ready(function() {
			var state = true;

			$("#button-for-menu").click(function () {
				
			   	if (state) {
			        $('.button-menu').css('right', '0px');
			        state = false;
			    }
			    else {
			          $('.button-menu').css('right', '-250px');
			          state = true;
			    }
			});
		});
			
		</script>
	</head>
	<!-- /HEAD -->

	<!-- BODY -->
	<body>
		<header>
			<div class="div-100" id="top-menu">
				<div class="logo">
					<img src="images/logo.png">
				</div>
				<div class="static-menu bg-green on-mouse">
					<p class="bold color-white" style="font-family: Roboto-700;">Stat Menu</p>
				</div>

				<ul id="menu-inline">
				    <li><a href="#">Home</a></li>
				    <li><a href="#">About</a></li>
				    <li><a href="#"><i class="dropdown-icon"></i>Products</a>
				        <ul>
				            <li><a href="#">Widgets</a></li>
				            <li><a href="#">Thingamabobs</a></li>
				            <li><a href="#">Doohickies</a></li>
				        </ul>
				    </li>
				    <li><a href="#">Contact</a></li>
				    <li><a href="#"><i class="dropdown-icon"></i>Menu1</a>
				    	<ul>
				            <li><a href="#">Widgets</a></li>
				            <li><a href="#">Thingamabobs</a></li>
				            <li><a href="#">Doohickies</a></li>
				        </ul>
				    </li>
				    <li><a href="#">Menu2</a></li>
				    <li><a href="#">Menu3</a></li>
				    <li><a href="#">Menu4</a></li>
				</ul>

				<ul id="menu-inline-small">
				    <li><a href="#">Home</a></li>
				    <li><a href="#">About</a></li>
				    <li><a href="#">Contact</a></li>
				</ul>

				

				<div id="" class="button-menu">
					<div id="button-for-menu" class="button-for-menu on-mouse">
				
					</div>

					<div id="" class="menu">

					</div>
				</div>
				

			</div>
		</header>

		<div class="div-100" id="page">
<!--
			<div class="div-100" id="slider">
				<ul>
					<li><img src="images/slider1.png"></li>
					<li><img src="images/slider2.png"></li>
					<li><img src="images/slider3.png"></li>
					<li><img src="images/slider4.png"></li>
				</ul>
			</div>
-->
			<div class="div-resize" id="d1">
				<div class="image-resize-bg">
					<img width="459" height="330" src="images/web-1.png" class="image-resize">
				</div>
				<ul class="image-action">
					<li><a href="#"></a>M</li>
					<li><a href="#"></a>M</li>
					<li><a href="#"></a>M</li>
				</ul>
			</div>
			<div class="div-resize" id="d2">
				<div class="image-resize-bg">
					<img width="459" height="330" src="images/web-1.png" class="image-resize">
				</div>
				<ul class="image-action">
					<li><a href="#"></a><img src="icons/fb.png" class="image-40x40 grayscale"></li>
					<li><a href="#"></a><img src="icons/tw.png" class="image-40x40 grayscale"></li>
					<li><a href="#"></a><img src="icons/yt.png" class="image-40x40 grayscale"></li>
					<li><a href="#"></a><img src="icons/rss.png" class="image-40x40 grayscale"></li>
				</ul>
			</div>
			<div class="div-resize" id="d3">
				<div class="image-resize-bg">
					<img width="459" height="330" src="images/web-1.png" class="image-resize">
					</div>
				<ul class="image-action">
					<li><a href="#"></a><img src="icons/fb.png" class="action-image image-40x40 grayscale"></li>
					<li><a href="#"></a><img src="icons/yt.png" class="action-image image-40x40 grayscale"></li>
				</ul>
			</div>
			<div class="div-resize" id="d1">
				<div class="image-resize-bg">
					<img width="459" height="330" src="images/web-1.png" class="image-resize">
					</div>
				<ul class="image-action">
					<li><a href="#"></a><img src="icons/yt.png" class="action-image image-40x40 grayscale"></li>

				</ul>
			</div>
			<div class="div-resize" id="d2">

			</div>
			<div class="div-resize" id="d3">

			</div>
		</div>

		<footer>

		</footer>
	</body>
	<!-- /BODY -->
</html>
