<!DOCTYPE html>
<html>
<head>
 <meta name="viewport" content="width=device-width, initialscale=1.0">
 <title>HASAX Headwear</title>
 <link rel="stylesheet" href="style.css">
 <link rel="preconnect" href="https://fonts.googleapis.com">
 <link rel="preconnect" href="https://fonts.gstatic.com"
crossorigin>
 <link href="https://fonts.googleapis.com/css2?
family=Bebas+Neue&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,6
00;0,700;1,200&display=swap" rel="stylesheet">

</head>
<body>
 <section class="header">
 <nav>
 <a href="index.html"><img src="images/logo.png"></a>
 <div class="nav-links">
 <ul>
 <li><a href="">HOME</a></li>
 <li><a href="">SHOP</a></li>
 <li><a href="">ABOUT</a></li>
 <li><a href="">CONTACT</a></li>
 </ul>
 </div>
 </nav>

<div class="text-box">
 <h1>World's Finest Headwear Brand</h1>
 <p>Want the best possible headwear you will ever experience? It's
a reality with Hasax Headwear! <br> Check out our webstore, select a
product, and between 2-5 days the package will be delivered at your
front door!</p>
 <a href="" class="hero-btn">Go to shop</a>
</div>
</section>
<!--- services --->
<section class="services">
 <h1>Services We Offer.</h1>
 <small>Take a look at the several unique and high-quality services
we offer!</small>

 <div class="row">
 <div class="service-col">
 <h3>Hat Steaming</h3>
 <p>Visit one of our stores for custom hat steaming. Our
employees would be more than happy to help with any problems you've
been dealing with.</p>
 </div>

 <div class="service-col">
 <h3>Hat Steaming</h3>
 <p>Visit one of our stores for custom hat steaming. Our
employees would be more than happy to help with any problems you've
been dealing with.</p>
 </div>

 <div class="service-col">
 <h3>Hat Steaming</h3>
 <p>Visit one of our stores for custom hat steaming. Our
employees would be more than happy to help with any problems you've
been dealing with.</p>
 </div>
 </div>
</section>

<!--- types of hats --->
<section class="types-hats">
 <h1>The Different Types of Hats We Sell.</h1>
 <small>Check out our subcategories for the different types of hats
we sell!</small>

<div class="row">
 <div class="hats-col">
 <img src="images/fpic1.jpg">
 <div class="layer">
 <h3>CAPS</h3>
 </div>
 </div>

 <div class="hats-col">
 <img src="images/fpic2.jpg">
 <div class="layer">
 <h3>BEANIES</h3>
 </div>
 </div>

 <div class="hats-col">
 <img src="images/fpic3.jpg">
 <div class="layer">
 <h3>BUCKET HATS</h3>
 </div>
 </div>
</div>


</section>

<!--- footer --->

<footer class="footer">
 <div class="container">
 <div class="row">
 <div class="footer-col">
 <h4>Company</h4>
 <ul>
 <li><a href="">About us.</a></li>
 <li><a href="">Our Services.</a></li>
 <li><a href="">Privacy Policy.</a></li>
 </ul>
 </div>
 </div>

 <div class="footer-col">
 <h4>Support</h4>
 <ul>
 <li><a href="">FAQ.</a></li>
 <li><a href="">Shipping.</a></li>
 <li><a href="">Returning Products.</a></li>
 </ul>
 </div>

 <div class="footer-col">
 <h4>Webstore</h4>
 <ul>
 <li><a href="">Caps.</a></li>
 <li><a href="">Beanies.</a></li>
 <li><a href="">Bucket Hats.</a></li>
 </ul>
 </div>

 <div class="footer-col">
 <h4>Follow us</h4>
 <ul>
 <li><a href="">Instagram.</a></li>
 <li><a href="">Facebook.</a></li>
 <li><a href="">Twitter.</a></li>
 </ul>

 </div>


 </div>
</footer>


</body>
</html>

*{
 margin: 0;
 padding: 0;
 font-family: 'Bebas Neue', cursive;
 font-family: 'Poppins', sans-serif;
 box-sizing: border-box;
}
.header{
 min-height: 100vh;
 width: 100%;
 background-image: lineargradient(rgba(4,9,30,0.7),rgba(4,9,30,0.7)),url(images/header.jpg);
 background-position: center;
 background-size: cover;
 position: relative;
}
nav{
 display: flex;
 padding: 2% 6%;
 justify-content: space-between;
 align-items: center;
}
nav img{
 width: 150px;
}
.nav-links{
 flex: 1;
 text-align: right;
}
.nav-links ul li{
 list-style: none;
 display: inline-block;
 padding: 8px 12px;
 position: relative;
}
.nav-links ul li a{
 color: #fff;
 text-decoration: none;
 font-size: 13px;
}
.nav-links ul li::after{
 content: '';
 width: 0%;
 height: 2px;
 background: #55ACEE;
 display: block;
 margin: auto;
 transition: 0.5s;
}
.nav-links ul li:hover::after{
 width: 100%;
}
.text-box{
 width: 90%;
 color: #fff;
 position: absolute;
 top: 50%;
 left: 50%;
 transform: translate(-50%,-50%);
 text-align: center;
}
.text-box h1{
 font-size: 62px;
}
text-box p{
 margin: 10px 0 40px;
 font-size: 14px;
 color: #fff;
}
.hero-btn{
 display: inline-block;
 text-decoration: none;
 color: #fff;
 border: 1px solid #fff;
 padding: 12px 34px;
 font-size: 13px;
 background: transparent;
 position: relative;
 cursor: pointer;
 margin-top: 20px;
}
.hero-btn:hover{
 border: 1px solid #55ACEE;
 background: #55ACEE;
 transition: 1s;
}
/*---- services -----*/
.services{
 width: 80%;
 margin: auto;
 text-align: center;
 padding-top: 100px;
}
h1{
 font-size: 36px;
 font-weight: 600;
}
p{
 color: #fff;
 font-size: 14px;
 font-weight: 300;
 line-height: 22px;
 padding: 10px;
}
.row{
 margin-top: 5%;
 display: flex;
 justify-content: space-between;
}
.service-col{
 color: #fff;
 flex-basis: 31%;
 background: rgba(4,9,30,0.7);
 border-radius: 10px;
 margin-bottom: 5%;
 padding: 20px 12px;
 box-sizing: border-box;
}
/*---- types of hats -----*/
.types-hats{
 width: 80%;
 margin: auto;
 text-align: center;
 padding-top: 50px;
}
.hats-col{
 color: #777;
 flex-basis: 32%;
 border-radius: 10px;
 margin-bottom: 60px;
 position: relative;
 overflow: hidden;
}
hats-col img{
 width: 100%;
}
.layer{
 background: transparent;
 height: 100%;
 width: 100%;
 position: absolute;
 top: 0;
 left: 0;
}
.layer:hover{
 background: rgba(4,9,30,0.7);
 transition: 1s;
}
/*---- footer -----*/
.container{
 max-width: 1170px;
 background-color: #24262b;
 margin: auto;
}
.row{
 display: flex;
 flex-wrap: wrap;
}
ul{
 list-style: none;
}
.footer{
 background-color: #24262b;
 padding: 70px 0;
}
.footer-col{
 width: 25%;
 padding: 0 15px;
}
.footer-col h4{
 font-size: 18px;
 color: #ffffff;
 text-transform: capitalize;
 margin-bottom: 30px;
 font-weight: 500;
 position: relative;
}
.footer-col h4::before{
 content: '';
 position: absolute;
 left: 0;
 bottom: -10px;
 background-color: #55ACEE;
 height: 2px;
 box-sizing: border-box;
 width: 50px;
}
.footer-col ul li:not(:last-child){
 margin-bottom: 10px;
}
.footer-col ul li a{
 font-size: 16px;
 text-transform: capitalize;
 color: #ffffff;
 text-decoration: none;
 font-weight: 300;
 color: #bbbbbb;
 display: block;
 transition: all 0.5s ease;
}
.footer-col ul li a:hover{
 color: #ffffff;
 padding-left: 8px;
}
