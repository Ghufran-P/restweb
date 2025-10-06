# Ex.07 Restaurant Website
## Date:06/10/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
in home.html
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="home.css">
    </head>
    <body>
        <div class="homebg"></div>
        <div class="tit"><h1>XIANO SUSHI HOUSE</h1><pre><h1 class="stit">     - A Legacy since 1997</h1></pre></div>
        <nav class="dashboard">
            <ul>
                <li><a href="home.html" style="color: red";>HOME</a></li>
                <li><a href="menu.html" style="color: red";>MENU</a></li>
                <li><a href="admin.html" style="color: red";>ADMIN</a></li>
                <li><a href="contact.html" style="color: red";>CONTACT</a></li>
            </ul>
        </nav>
        <div class="text"><h1>"Authentic Japanese flavors, crafted fresh daily for your delight."</h1></div>
        <div class="home1"></div>
        <footer class="foot">&copy;   Ghufran (25009482)</footer>
    </body>
</html>

in menu.html
<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>
<div class="menubg"></div>
<div class="tit">
    <h1>Our Menu</h1>
    <nav class="dashboard">
      <ul>
                <li><a href="home.html" style="color: black";>HOME</a></li>
                <li><a href="menu.html" style="color: black";>MENU</a></li>
                <li><a href="admin.html" style="color: black";>ADMIN</a></li>
                <li><a href="contact.html" style="color: black";>CONTACT</a></li>
      </ul>
    </nav>
</div>
<div class="sp"><h2>SPECIAL ITEMS</h2></div>
 <div class="product-container">
  	<div class="product-card">
      		<img src="nm1.jpg">
      		<h3>Sukiyaki</h3>
      		<p class="price">¥1200</p>
    	</div>
  	<div class="product-card">
      		<img src="nm2.jpg">
      		<h3>Xiano's Jumbo Pack</h3>
      		<p class="price">¥1000</p>
    	</div>
  	<div class="product-card">
      		<img src="nm3.jpg">
      		<h3>Katsudon</h3>
      		<p class="price">¥1400</p>
    	</div>
  	<div class="product-card">
      		<img src="m4.jpg">
      		<h3>Yakisoba</h3>
      		<p class="price">¥1100</p>
    	</div>
  	<div class="product-card">
      		<img src="m5.jpg">
      		<h3>Onigiri</h3>
      		<p class="price">¥1300</p>
    	</div>
  	<div class="product-card">
      		<img src="nnn1.jpeg">
      		<h3>Xiano's special</h3>
      		<p class="price">¥2200</p>
    	</div>
    <div class="product-card">
      		<img src="nm5.jpg">
      		<h3>Tonkatsu</h3>
      		<p class="price">¥1000</p>
    	</div>
      <div class="product-card">
      		<img src="m8.jpg">
      		<h3>Tempura</h3>
      		<p class="price">¥1700</p>
    	</div>
      <div class="product-card">
      		<img src="m9.jpg">
      		<h3>Okonomiyaki</h3>
      		<p class="price">¥1200</p>
    	</div>
      <div class="product-card">
      		<img src="m10.jpg">
      		<h3>Miso Spigetti</h3>
      		<p class="price">¥1250</p>
    	</div>
      <div class="product-card">
      		<img src="m11.jpg">
      		<h3>Miso Ramen</h3>
      		<p class="price">¥1000</p>
    	</div>
      <div class="product-card">
      		<img src="m12.jpg">
      		<h3>Dorayaki</h3>
      		<p class="price">¥1000</p>
    	</div>
<footer class="foot">&copy;   Ghufran (25009482)</footer>
</body>
</html>

in admin.html
<html>
<head>
    <title>admin</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <div class="title">
        <h1>Administer Team</h1>
        <nav class="dashboard">
      <ul>
                <li><a href="home.html" style="color: black";>HOME</a></li>
                <li><a href="menu.html" style="color: black";>MENU</a></li>
                <li><a href="admin.html" style="color: black";>ADMIN</a></li>
                <li><a href="contact.html" style="color: black";>CONTACT</a></li>
      </ul>
    </nav>
    </div>
    <br>
    <h1 align="center">MEET OUR TEAM</h1>
   <div class="product-container">
  	<div class="product-card">
      		<img src="ceo.jpg">
      		<h3><b>CEO</b></h3>
    	</div>
  	<div class="product-card">
      		<img src="manager.jpg">
      		<h3><B>X-CE0</B></h3>
    	</div>
  	<div class="product-card">
      		<img src="x-ceo.jpeg">
      		<h3><B>MD</B></h3>
    	</div>
        <div class="product-container">
  	<div class="product-card">
      		<img src="salesmanager.jpeg">
      		<h3><B>GENERAL MANAGER</B></h3>
    	</div>
  	<div class="product-card">
      		<img src="MD.jpeg">
      		<h3><B>MANAGER</B></h3>
    	</div>
  	<div class="product-card">
      		<img src="magnus.jpeg">
      		<h3>INVESTOR</h3>
    	</div>
    </div>
</body>
</html>

in contact.html
<html>
<head>
    <tilte></tilte>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <div class="bg"></div>
    <div class="rect">
        <h1><b>Contact Us</b></h1>
        <br>
        <h2>Visit us at : 175 , BB Xiano Road, Tokyo, japan</h2>
        <br>
        <h2>xiano7124@gmail.com</h2>
        <br>
        <br>
        <h3> + 81 0315 64 1576</h3>
    </div>
</body>
<footer class="foot">&copy;   Ghufran (25009482)</footer>
</html>

in home.css
*{
   padding: 0%;
   margin: 0%;
}
.homebg{
    background-image: url("homebg.jpg");
    background-size: cover;
    position: relative;
    width: 100%;
    height: 100%;
}
.tit{
    font-size: larger;
    color: orangered;
    top: 2%; 
    left: 3%;
    position: absolute;
    display: inline-block;
}
.stit{
    color: silver;
    display: inline-block;
}
.dashboard{
    display: flex;
    position: absolute;
    top: 2%;
    right: 20%;
}
.dashboard ul{
    display: flex;
    position: absolute;
    list-style: none;
    gap: 20px;
}
.dashboard li{
    color: bisque;
    cursor: pointer;
}
.text{
    top: 22%;
    left: 17%;
    position: absolute;
    color: cornsilk;
}
.home1{
    background-image: url("inhome.jpeg");
    background-size: cover;
    background-position: center;
    position: absolute;
    width: 900px;
    height: 400px;
    top: 37%;
    left: 20%;
}
.foot{
    position: absolute;
    background-color: black;
    color: azure;
    width: 100%;
    height: 25px;
    bottom: 1px;
    text-align: center;
}
in menu.css

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: sans-serif;
  background-color: #f8f8f8;
}

.menubg {
  background-image: url("menubg.jpg");
  background-size: cover;
  width: 100%;
  height: 100vh;
  position: fixed;
  z-index: -1;
}

.tit {
  background-color: cadetblue;
  width: 100%;
  height: 75px;
  text-align: center;
  position: sticky;
  top: 0;
  z-index: 1;
}

.dashboard {
  display: flex;
  justify-content: center;
}

.dashboard ul {
  display: flex;
  list-style: none;
  gap: 20px;
  margin-top: 10px;
}

.dashboard li {
  color: bisque;
}

.sp {
  text-align: center;
  margin: 100px 0 20px;
  color: gainsboro;
}

.product-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding-bottom: 50px;
}

.product-card {
  width: 220px;
  background-color: darkgray;
  border: 1px solid black;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  text-align: center;
  transition: transform 0.2s;
}

.product-card:hover {
  transform: scale(1.05);
}

.product-card img {
  width: 100%;
  height: auto;
  border-radius: 5px;
  margin-bottom: 10px;
}

.product-card .price {
  color: purple;
  font-weight: bold;
}

.foot {
  background-color: black;
  color: azure;
  text-align: center;
  padding: 10px;
}

in admin.css
*{
    padding: 0%;
    margin: 0%;
}
.title{
   background-color: cadetblue;
    width: 100%;
    height: 75px;
    position: relative;
    top: 0%;
    text-align: center;
}
.dashboard{
    display: flex;
    position: absolute;
    top: 45px;
    left: 40%;
}
.dashboard ul{
    display: flex;
    position: absolute;
    list-style: none;
    gap: 20px;
}
.dashboard li{
    color: bisque;
    cursor: pointer;
}
.product-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding-bottom: 100px;
}

.product-card {
  width: 220px;
  background-color: black;
  border: 1px solid black;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  text-align: center;
  color: azure;
}
.product-card img {
  width: 100%;
  height: auto;
  border-radius: 5px;
}

in contact.html
*{
    padding: 0%;
    margin: 0%;
}
.bg{
    background-image: url("contact.jpg");
    position: relative;
    width: 100%;
    height: 100%;
    background-size: cover;
}
.rect{
    border: solid orangered 2px;
    width: 30%;
    height: 30%;
    background-color: orangered;
    top: 35%;
    left: 35%;
    position:absolute;
    text-align: center;
}
.foot{
    position: absolute;
    background-color: black;
    color: azure;
    width: 100%;
    height: 25px;
    bottom: 1px;
    text-align: center;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-10-06 125522.png>)
![alt text](<Screenshot 2025-10-06 125542.png>)
![alt text](<Screenshot 2025-10-06 125605.png>)
![alt text](<Screenshot 2025-10-06 125616.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
