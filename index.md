<!Doctype html>
<html lang="en">
<head>
<link rel="shortcut icon" href="/G:/coding/wensite/favicon.ico" type="image/x-icon" />
<meta charset="utf-8"/>
<title> I_See_St4irs</title>
<meta name="Viewpoint" content="Width=device-width,initial-scale=1.0">
<link rel="stylsheet" href="blueberry.css"/>
<style type="text/css">
* {
margin: 0;
border: 0;
padding: 0;
}
body{
background: #f0f0f0;
font: 14px/20px Arial, San-Serif;
color: #555;
margin: 0;
}
h1 {
text-align: center;
font size: 180%;
line-height: 120%;
padding: 5% 0;
}
h2 {
text-decoration: underline;
line-height: 280%;
padding-left: 2%:
}
h3 {
line-height: 110%;
padding: 5% 0;
}
p{
padding: 1%;
}
img {
text-align: center;
max-width: 100%;
height: auto;
width: auto;
}
a {
color: #fff;
text-decoration: none;
font-weight: bold;
}
a:hover {
color: #fff;
text-decoration: underline;
}
header {
background: #405580;
width: 100%;
height: 86px;
position: fixed;
top: 0;
left: 0;
z-index: 100;
opacity: 0.90;
}
#logo {
  display: inline-block;
  margin: 15px; 
  float: left;
  height: 60px;
  width: auto; 
  border-radius: 50%; 
}
nav { 
float: right;
padding: 35px 20px 20px 0;
}
#menu-icon {
display: hidden;
width: 40px;
height: 40px;
background:#ccc url(http://i65.tinypic.com/xgfvc4.jpg ) center;
}
a:hover#menu-icon {
border-radius: 4px 4px 0 0;
}
ul {
list-style: none;
}
nav ul li {
display: inline-block;
float: left;
padding: 10px;
}
.current {
color: #fff;
text-decoration: underline;
}
#doc {
margin: 40px 0;
}
#content {
margin; 0 auto;
max-width: 1140px;
margin-top: 110px;
}
.blueberry {
max-width; 960px;
margin-top; 110px;
}
section {
width: 29%;
float: left;
margin: 2% 2%;
text-align: center;
}
.clear {
clear: both;
}
article {
float: left;
margin: 0 auto;
width: 50%;
height: auto;
padding: 4%;
}
aside {
float: right;
margin: 0 auto;
width: 35%;
height: auto;
padding: 3%;
}
ul.camaro li {
padding-left: 3%;
}
footer {
background: #333333;
width: 100%;
overflow: hidden;
opacity: 0.90;
}
footer p, footer h3 {
color: #fff;
}
footer p a {
color: #fff;
text-decoration: none;
}
ul.social li {
display: inline;
}
ul.social li img {
height: 50px;
}
footer.second {
border-top: 1px solid #4D4E50;
background-color: #333333;
max-height: 50px;
text-align: center;
opacity: 0.95;
}






/*-------------------------MEDIA!!!-------------------------*/
@media screen and (max-width: 478px) {
body {
position: absolute;
}
}
@media screen and (max-width: 740px) {
header {
psotion: absolute;
}
#menu-icon {
display: inline-block;
}
nav ul, nav:active ul {
display: none;
position: absolute;
padding: 20px;
background: #405580;
border: 1px solid #fff;
right: 20px;
top: 60px;
width: 50%;
border-radius: 2px 0 2px 2px;
}
nav li {
text-align: center;
width: 100%;
padding: 10px 0;
margin: 0;
}
nav:hover ul {
display: block;
}
section {
float: left;
width: 100%;
margin: 0;
padding: 0;
}
}
</style>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.1/jquery.min.js"></script>
<script src="jquery.blueberry.js"></script>
<script>
$(window).load(function() {
$('.blueberry').blueberry();
});
</script>
</head>
<body>
<header>
<a href="#"><img id="logo" src="http://i67.tinypic.com/2v9dm5h.jpg"></a>
<nav>
<a href="#" id="menu-icon"></a>
<ul>
<li><a href="index.html" class="current">Home</a></li>
<li><a href="accounts.html">Accounts</a></li>
<li><a href="contact me.html">Contact Me.</a></li>
<li><a href="pictures.html">Pictures</a></li>
<li><a href="about me.html">About Me</a></li>
<li><a href="other people.html">Other People</a></li>
</ul>

</nav>
</header>
<div id="doc">
<div id="content">
<div class="blueberry">
<ul class="slides">
<li><img src="staring.jpg"/></li>
<li><img src="burnout.jpg"/></li>
<li><img src="ablade.jpg"/></li>
<li><img src="aston.jpg"/></li>
<li><img src="jag.jpg"/></li>
<li><img src="post1.jpg"/></li>
<li><img src="post2.jpg"/></li>
<li><img src="post4.jpg"/></li>
<li><img src="post5.jpg"/></li>
<li><img src="post8.jpg"/></li>
<li><img src="post9.jpg"/></li>
<li><img src="post10.jpg"/></li>
<li><img src="post11.jpg"/></li>

</ul>
</div>
</div>
</div>
<section>
<img src="instagram_logo_small.png"/>
<h1>My Instagram!</h1>
<p> This is my instagram account my name on instagram is I_see_st4irs i post mainly car pictures</p>
</section>
<section>
<img src="twitter.png"/>
<h1>My Twitter!</h1>
<p> This is my Twitter account my name on Twitter is I_see_st4irs i post a little bit of everything i have a secondary twitter by the name of Lenny_bruh_rekt</p>
</section>
<section>
<img src="pinterest.png"/>
<h1>My Pinterest!</h1>
<p> This is my Pinterest account my name on Pinterest is I_see_st4irs i post anything i like on my boards.</p>
</section>
<div class="clear"></div>
<article>
<img src="2ss.jpg"/>
</article>
<aside>
<h2> My Favorite Car:</h2>
<ul class="Camaro">
<li><h3>My favorite car is the Chevrolet Camaro, especially the 6th gen Camaro which is the latest Camaro.</h3></li>
<li><h3>455 horsepower</h3></li>
<li><h3>455 foot pounds of torque</h3></li>
<li><h3>0-60 mph in 3.9 seconds</h3></li>
<li><h3>Runs the quarter mile in 12.2 seconds</h3></li>
<li><h3>Weighs 3,685 pounds</h3></li>
<li><h3>So the 2016 Camaro SS is a great muscle car</h3></li>
</ul>
</aside>
<div class="clear"></div>
<section>
<h1>The 2016 Camaro SS</h1>
<img src="ss.jpg"/>
<p> This is My favorite muscle car.</p>
</section>
<section>
<h1>The 2015 Koenigsegg one:1</h1>
<img src="koenigsegg.jpg"/>
<p> This is my favorite Megacar.</p>
</section>
<section>
<h1>The 2016 Dodge Charger Hellcat</h1>
<img src="hellcat.jpg"/>
<p> This is My favorite sports sedan.</p>
</section>
<footer>
<section>
<h3><b> Me</b></h3>
<p><b>@iamwilsparks@gmail.com</b><br><br>
contact me if you want to send me pictures to post on my Instagram or Twitter.</p>
</section>
<section>
<h3>Follow me!</h3>
<ul class="social">
<li><a href="www.online-instagram.com/user/i_see_st4irs/246253528"><img src="instagram_logo_small.png"></a></li>
<li><a href="https://twitter.com/i_see_st4irs"><img src="twitter.png"></a></li>
<li><a href="https://twitter.com/i_see_st4irs"><img src="tumblr.png"></a></li>
<li><a href="https://plus.google.com/wm/quevuelvamatt/.../collections"><img src="googleplus.png"></a></li>
<li><a href="https://www.youtube.com/channel/UCOaUXzGUZ2_1EB_-QI15WoA"><img src="youtube.png"></a></li>
</ul>
</section>
<section>
<img src="logo.jpg">
</section>
</footer>
<footer class="second">
<p>©copyright - I_See_St4irs, 2016.</p>
</footer>





</body>
</html>
