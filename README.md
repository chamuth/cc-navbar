# cc-navbar
cc-navbar is a Navigation Bar bootstrapping option for modern websites. By following these simple steps you can manage cc-navbar to create a great-looking navigation bar for your website.

#INSTALLATION
1. Download and paste 'cc-navbar.css' into a folder inside your web project known as css/
2. Add this code to your head tag in your html file / files.
```html
<link rel="stylesheet" href="css/cc-navbar.css"/>
<meta charset="utf-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width, initial-scale=0.7, maximum-scale=1.0, user-scalable=no" />
```
3. Add this code to the top of your body tag (where a nav should be)
```html
<nav class="nav">
	<div class="container">
		<div class="nav-content">
			<a href="http://www.google.com">Ninponix</a>
			
			<div class="nav-links">
				<!--here add the links, they must be <a> tags-->
				<a href="#">Home</a>
				<a href="#">Downloads</a>
				<a href="#">About Us</a>
				<a href="#">Contact Us</a>
			</div>
		</div>
	</div>
</nav>
```
4. Add all of your content inside a div with the class of container-body (refer to the example.html)
```html
<div class="container-body">
</div>
```

#MODIFICATIONS FOR YOUR PROJECT

* Change the padding in .container class, and .container-body class in the css to fit your html content.
* Change the media querie's max-width property to fit your project mobile max-width size.
* Change the default color scheme (0,150,255 and 0,120,225) to your project's color schemes.
