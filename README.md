<!DOCTYPE html>
<html>
<head>
<title>Online Shopping Site for Fashion, Electronics, Home &amp; More | Meesho</title>
<link rel="icon" href="C:\Users\kaviy\OneDrive\kavi/meesho logo.png">
<link rel="stylesheet" href="style2.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer"/>
	<style>
		*{
	box-sizing: border-box;
}
:root{
	--hoverTextColor:rgb(204,19,127);
	--TextColor:rgb(87,85,85);
}
body{
	margin:0;
	padding:0;
	width:100%;
	font-family:'Roboto',Sans-serif;
	color:var(--TextColor);
}
.header
{   
    top:0px;
	height:75px;
	outline:1px solid blue;
	display:flex;
	padding-right:85px;
	 padding-left:10.5px;
	align-items:center;
    position:fixed;
	background:white;
}
.table{
	position:relative;
	align-items:center;
     position:fixed;
	 top:76px;
	 background:white;
	 outline:1px solid blue;
	 padding-right:85px;
	 padding-left:3.6px;
}
.table .appcontainer{
	position:absolute;
	top:0px;
}
.searchborder{
	margin-left:40px;
	height:45px;
	max-width:400px;
    outline:1px solid rgb(126,126,126);
    display:flex;
	align-items:center;
	border-radius:3px;
	padding:10px
}
.input{
	width:100%;
	border:none;
	outline:none;
}
.meesho
{ 	
 margin-left:85px;	
}
.search{
	margin:6px;
}
.mobile{
	margin-left:50px;
}
.App{
	position:fixed;
	align-items:center;
	display:flex;
	padding-right:20px;
	position:relative;
	color:var(--TextColor);
}
.App:hover{
		border-bottom:3px solid var(--hoverTextColor);
		border-bottom-width:4px;
	    color:var(--hoverTextColor);
}
.mobile:hover{
		
	color:var(--hoverTextColor);
}
.down{ 
 width:200px;
display:block;
}

.appcontainer{
	position:fixed;
	position:absolute;
	position:0;
	top:100px;
	box-shadox:0px 0px 5px rgba(0,0,0,0.3);
    display:none; 
	color:var(--TextColor);
	border:1.5px;
	background-color:white;
	margin-left:50px;
	
	border-bottom:1px solid transparent;
}
.App:hover .appcontainer,
.App:focus .appcontainer{
	display:block;
}
.boxpro{
	height:50px;
	width:200px;
	background-color:purple;
}
.profile:hover{
    border-bottom:2px solid var(--hoverTextColor);
	border-bottom-width:4px;
	color:var(--hoverTextColor);
	visibility:visible;
}
.profilecontainer{
	height:300px;
	width:250px;
	padding-left:20px;
	padding-right:20px;
	background-color:yellow;
	position:absolute;
	position:0;
	display:none;
	/*visibility:hidden;*/
	top:61px;
	box-shadox:0px 0px 5px rgba(0,0,0,0.3);
	color:var(--TextColor);
	border:1px;
	margin-left:50px;
	border-bottom:2px solid transparent;
}
.hand1{
		position:relative;
}

.profileborder{
    align-items:center;
	display:flex;
	padding-right:20px;
	position:relative;
	color:var(--TextColor);

}
.profileborder:hover{
	 border-bottom:3px solid var(--hoverTextColor);
     border-bottom-width:4px;	 
	color:var(--hoverTextColor);
	position:relative;
	visibility:visible;
}
.hand1{
	visibility:visible;
}	
.pro1{
	width:200px;
    display:block;
}
.profileborder:hover .profliecontainer,
.proflieborder:focus .profliecontainer{
	display:block;
}
.navpart 
{
display:flex;
	
}

.secondpart
{
	margin-right:0px;
	margin-left:0px;
transform:translate(-23px);
outline:1px solid blue;
top:76px;
display:flex;
font-size:16.5px;
position:absolute;
position:fixed;
background-color:white;
}
.navigation
{
display:flex;	
list-style-type:none;
margin:10px;
}
.a1:hover
{
color:purple;
border-bottom:3px solid red;
border-bottom-width:4px;
}
.a1
{
text-decoration:none;
color:black;
padding-left:26.5px;
padding-right:26.1px;
align-items:center;	
border-bottom:transparent;
}
#womenethnic 
{
	top:128px;
list-style-type:none;
visibility:hidden;
background-color:#eef0ed;
}
.navigation li:hover ul#womenethnic
{
	
visibility:visible;	
}
#womenwestern 
{
	margin-right:100px;
list-style-type:none;
visibility:hidden;
background-color:#eef0ed;
}
li:hover ul#womenwestern
{
visibility:visible;	
}
#men
{
list-style-type:none;
visibility:hidden;
background-color:white;
}
li:hover ul#men
{
visibility:visible;	
}
#kids
{
list-style-type:none;
visibility:hidden;
background-color:white;
}
li:hover ul#kids
{
visibility:visible;	
}
#home
{
list-style-type:none;
visibility:hidden;
background-color:white;
}
li:hover ul#home
{
visibility:visible;	
}
#beauty
{
list-style-type:none;
visibility:hidden;
background-color:white;
}
li:hover ul#beauty
{
visibility:visible;	
}
#jewels
{
list-style-type:none;
visibility:hidden;
background-color:white;
}
li:hover ul#jewels
{
visibility:visible;	
}
#bags
{
list-style-type:none;
visibility:hidden;
background-color:white;
}
li:hover ul#bags
{
visibility:visible;	
}#electronics
{
list-style-type:none;
visibility:hidden;
background-color:white;

}
li:hover ul#electronics
{
visibility:visible;	
}
.thirdpart
{
display:flex;
padding-top:50px;	
}
.supply{
	padding:0px 35px;
    border-left:2px solid #ccc;
	border-right:2px solid #ccc;
	height:40px;
	font-size:17px;
}
.news
{
    border-right:2px solid #ccc;
	padding:0px 35px;
	height:40px;
	font-size:17px;
}
.profileandcart{
	display:flex;
	align-items:center;
	position:relative;
}
.profileandcart p{
	margin:0px;
	padding:0px;
	position:relative;
	}
.profileborder,
.cartborder{
	padding:0px 20px;
	display:flex;
	align-items:center;
	justify-content:center;
	flex-direction:column;
	position:relative;
}
.c{
	display:flex;
	top:250;
}
.price{
	border:1px;
	width:550px;
	height:350px;
	margin-left:220px;
	margin-top:50px;
	background-color:#eef0ed;
}
.table1{
	margin-top:120px;
}
.box{
	display:flex;
	border:1px;
	margin-left:40px;
	margin-top:70px;
	width:350px;
	height:50px;
	background-color:white;
}
.link{
	border:1px;
	margin-left:40px;
	margin-top:40px;
	width:300px;
	height:50px;
	background-color:purple;
}
.cat
{
	margin-top:50px;
	margin-left:50px;
   width:250px;
   height:1px;
   background-color:purple;
}
.text2{   
    padding-left:50px;
	font-size:40px;
	margin-top:50px;
}
.D{
	font-size:25px;
	border:1px;
	width:1100px;
	height:550px;
	background-color:purple;
}
.d1
 {
	 align-content:center;
	 border:1px;
	width:350px;
	height:400px;
	background-color:white;
}
.d2
{ 
    border-radius:15px;
    align-content:center;
	border:1px;
	width:325px;
	height:300px;
	background-color:white;
}
.d3
{  
    border-radius:15px;
    align-content:center;
    border:1px;
	width:325px;
	height:300px;
	background-color:white;
}
.wo1{
	display:flex;
}
.wo2{
	display:flex;
}
.me1{
	display:flex;
}
.me2{
	display:flex;
}
.ki1{
	display:flex;
}
.ki2{
	display:flex;
}
.flex{
	display:flex;
}
.box9{
	display:flex;
	border:1px;
	width:1100px;
	height:550px;
	background-color:purple;
}
.ho1{
	margin-top:80px;
	border-radius:15px;
	margin-left:85px;
	border:1px;
	width:200px;
	height:200px;
	background-color:white;
}
.ho2{
	margin-top:80px;
	border-radius:15px;
	margin-left:15px;
	border:1px;
	width:200px;
	height:200px;
	background-color:white;
}
.ho3{
	margin-top:80px;
	border-radius:15px;
	margin-left:15px;
	border:1px;
	width:200px;
	height:200px;
	background-color:white;
}
.border{
	align-items:center;
	text-align:center;
	border-radius:20px;
	border:1px;
	width:170px;
	height:70px;
	background-color:yellow;
	color:white;
	font-size:33px;
}
.doll{
	border-radius:15px;
	border:1px;
	width:150px;
	height:30px;
	background-color:white;
}
.doll1{
	border-radius:15px;
	border:1px;
	width:150px;
	height:30px;
	background-color:white;
}
.doll2{
	border-radius:15px;
	border:1px;
	width:150px;
	height:30px;
	background-color:white;
}
.border .fo{
	align-items:center;
	margin-top:18px;
	margin-left:25px;
	text-align:center;
}
.size{
	margin-top:120px;
	margin-left:60px;
}
.box10{
	display:flex;
	border:1px;
	width:1100px;
	height:550px;
	background-color:purple;
}
.h4{
	margin-top:80px;
	border-radius:15px;
	margin-left:85px;
	border:1px;
	width:200px;
	height:200px;
	background-color:white;
}
.h5{
	margin-top:80px;
	border-radius:15px;
	margin-left:15px;
	border:1px;
	width:200px;
	height:200px;
	background-color:white;
}
.h6{
	margin-top:80px;
	border-radius:15px;
	margin-left:15px;
	border:1px;
	width:200px;
	height:200px;
	background-color:white;
}
.border1{
	text-align:center;
	border-radius:20px;
	border:1px;
	width:170px;
	height:70px;
	background-color:yellow;
	color:white;
	font-size:33px;
}
.doll3{
	border-radius:15px;
	border:1px;
	width:150px;
	height:30px;
	background-color:white;
}
.doll4{
	border-radius:15px;
	border:1px;
	width:150px;
	height:30px;
	background-color:white;
}
.doll5{
	border-radius:15px;
	border:1px;
	width:150px;
	height:30px;
	background-color:white;
}
.border .fo1{
	align-items:center;
	margin-top:30px;
	margin-left:25px;
	text-align:center;
}
.size1{
	margin-top:120px;
	margin-left:50px;
}
.place{
	display:flex;
}
.image{
position:relative;
}
.image .font1{
	position:absolute;
	color:blue;
    font-size:30px;
	top:10px;
	left:925px;
}
.image .font2{
	position:absolute;
	color:purple;
    font-size:24px;
	top:80px;
	left:650px;
}
.image .font3{
	position:absolute;
	color:purple;
    font-size:24px;
	top:130px;
	left:780px;
}
.image .place{
	position:absolute;
	top:260px;
	left:881px;
}
.last{
	position:relative;
}

.image .table{
	position:absolute;
}
		</style>
</head>
<body>
<meta name="viewpoint" content="width-device-width, intitial-scale=1.0">
<header class="header">
<div class="meesho"><a href="file:///C:/Users/kaviy/OneDrive/kavi/meeshoweb.html"><img src="meshotext.jpg" width="155px"></a>
</div>
<div class="searchborder">
<div class="search">
<img src="search1.png" width="25px">
</div>
<input style="font-size:15px;width:500px;height:50px" type="text" placeholder="Try Saree,Kurti or Search by Product Code" class="input">
</div>
<div class="hand">
<div class="App">
<div class="mobile">
<img src="phone.png" width="45px">
</div>
<p style="font-size:15px" >Download App</p>
<div class="appcontainer">
<center>
<h3>Download Form</h3>
</center>
<a href="https://play.google.com/store/apps/details?id=com.meesho.supply&pid=pow_website&c=pow"><img src="https://images.meesho.com/images/pow/playstore-icon-big.png" class="down"></a>

<br><a href="https://apps.apple.com/us/app/meesho-online-shopping/id1457958492"><img src="https://images.meesho.com/images/pow/appstore-icon-big.png" class="down"></a>
<br>
</div>
</div>
</div>
<div class="supply">
<a href="https://supplier.meesho.com/?utm_source=meesho&utm_medium=website&utm_campaign=header" style="text-decoration:none" ><p style="margin-top:12px;color:black">Become a Supplier</p></a>
</div>
<div class="news">
<a href="https://www.meesho.io/news" style="text-decoration:none" ><p style="margin-top:12px;color:black">Newsroom</p></a>
</div>
<div class="profileandcart">
<div class="hand1">
<div class="profileborder">
<div class="profile">
<img src="pro.png" width="20px" height="20px">
</div>
<p style="font-size:17px" width="20px">Profile</p>
<div class="profilecontainer">
<h3>Hello User</h3>
<h6>To access Your Meesho Account</h6>
<div class="boxpro">
<br>
<a style="text-decoration:none;font-size:20px;margin-left:65px" href="https://www.meesho.com/auth?redirect=https%3A%2F%2Fwww.meesho.com%2F&source=profile&entry=header&screen=HP" class="pro1">Sign Up</a>
</div>
<br>
<hr>
<br>
<a style="text-decoration:none" href="https://www.meesho.com/auth?redirect=https://www.meesho.com/orders"><i class="fa-solid fa-bag-shopping" class="pro1"></i>My Orders</a>
<br>
<hr>
<br>
<a style="text-decoration:none" href="https://www.meesho.com/account/delete" class="pro1">Delete Account</a>
<br>
</div>
</div>
</div>
<div class="cartborder">
<div class="cart"><a style="text-decoration:none" href="https://www.meesho.com/auth?redirect=https%3A%2F%2Fwww.meesho.com%2Fmcheckout%2Fcart&source=cart-icon&screen=HP">
<img src="trolly.png" width="25px">
</div>
<p style="font-size:18px;color:black" width="20px">Cart</p></a>
</div>
</div>
</div>
</div>
</header>
<ul><div class="secondpart">
<ul class="navigation">
<li><a class="a1" href="#" >Women Ethnic</a>
<ul id="womenethnic">
<div style="border:1px solid #eef0ed;display:flex;position:absolute;background-color:#eef0ed;margin-top:3.5px;transform:translate(-50px)">
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:350px;"><li><a class="a1"  style="color:purple">All Women Ethnic</a></li><br>
	<br>
<li><a class="a1" href="https://www.meesho.com/ethnicwear-women/pl/3tq">View All</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:230px;
	height:300px" ><li><a class="a1" style="color:rgb(136,2,80)">Sarees</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/sarees/pl/3iy">All Sarees</a></li><br>
<li><a class="a1" href="https://www.meesho.com/silk-sarees/pl/3j4">Silk Sarees</a></li><br>
<li><a class="a1" href="https://www.meesho.com/cotton-silk-sarees/pl/3jt">Cotton Silk Sarees</a></li><br>
<li><a class="a1"  href="https://www.meesho.com/cotton-sarees/pl/3jh">Cotton Sarees</a></li><br>
<li><a class="a1" href="https://www.meesho.com/georgette-sarees/pl/3m1">Georgette Sarees</a></li><br>
<li><a class="a1" href="https://www.meesho.com/chiffon-sarees/pl/3m0">Chiffon Sarees</a></li><br>
<li><a class="a1" href="https://www.meesho.com/satin-sarees/pl/3k5">Satin Sarees</a></li><br>
<li><a class="a1" href="https://www.meesho.com/embroidered-sarees/pl/3ju">Embroidered Sarees</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:350px"><li><a class="a1" style="color:rgb(136,2,80);">Krutis</a></li><br>
<br>
<li><a class="a1" href="https://www.meesho.com/women-kurtis/pl/3j0">All krutis</a></li><br>
<li><a class="a1" href="https://www.meesho.com/anarkali-women-kurtis/pl/3jc">Anarkali kurtis</a></li><br>
<li><a class="a1" href="https://www.meesho.com/rayon-women-kurtis/pl/3jz">Rayon Kurtis</a></li><br>
<li><a class="a1" href="https://www.meesho.com/cotton-women-kurtis/pl/3jj">Cotton Kurtis</a></li><br>
<li><a class="a1" href="https://www.meesho.com/embroidered-women-kurtis/pl/3k0">Embroidered Kurtis</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:350px"><li><a class="a1" style="color:rgb(136,2,80)"> Kurta sets</a></li>
	<br><br>
<li><a class="a1" href="https://www.meesho.com/kurta-sets-women/pl/3k9">All Kurta Sets</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:280px;
	height:350px"><li><a class="a1" style="color:rgb(136,2,80)">Suits<code><b> & </b></code>Dress Material</a></li><br>
	<br>
<li><a class="a1" href="https://www.meesho.com/women-suits-dress-materials/pl/3iz">All Suits<code><b> & </b></code>Dress Material</a></li><br>
<li><a class="a1" href="https://www.meesho.com/cotton-women-suits-dress-materials/pl/3jk">Cotton Suits</a></li><br>
<li><a class="a1" href="https://www.meesho.com/embroidered-women-suits-dress-materials/pl/3k1">Embroidered Suits</a></li><br>
<li><a class="a1" href="https://www.meesho.com/chanderi-suits-dress-materials/pl/3jv">Chanderi Suits</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:230px;
	height:300px"><li><a class="a1" style="color:purple">Other Ethnic</a></li><br>
	<br>
<li><a class="a1" href="https://www.meesho.com/blouses/pl/3l5">Blouses</a></li><br>
<li><a class="a1" href="https://www.meesho.com/dupattas/pl/3lz">Dupattas</a></li><br>
<li><a class="a1" href="https://www.meesho.com/lehengas/pl/3l6">Lehanga</a></li><br>
<li><a class="a1" href="https://www.meesho.com/gowns-women/pl/3l9">Gown</a></li><br>
<li><a class="a1" href="https://www.meesho.com/ethnic-bottomwear-women/pl/3ta">Ethnic Bottomwear</a></li></div><br>
</div>
</ul>
</li>
<li><a class="a1" href="#" >Women Western</a>
<ul id="womenwestern" >
<div style="border:1px solid #eef0ed;display:flex;position:absolute;background-color:#eef0ed;margin-top:3.5px;transform:translate(-158px)">
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Top Wear</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/tops-ladies/pl/3ja">Tops</a></li><br>
<li><a class="a1" href="https://www.meesho.com/dresses-women/pl/3j3">Dresses</a></li><br>
<li><a class="a1" href="https://www.meesho.com/sweaters-women/pl/3l2">Sweters</a></li><br>
<li><a class="a1" href="https://www.meesho.com/jumpsuits-women/pl/3kq">Jumpsuits</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Bottomwears</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/jeans-women/pl/3kc">Jeans</a></li><br>
<li><a class="a1" href="https://www.meesho.com/jeggings/pl/3kk">Jeggings</a></li><br>
<li><a class="a1" href="https://www.meesho.com/palazzo-pants/pl/3jb">Palazzos</a></li><br>
<li><a class="a1" href="https://www.meesho.com/shorts-women/pl/3kp">Shorts</a></li><br>
<li><a class="a1" href="https://www.meesho.com/skirts-ladies/pl/3jf">Skirts</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Inner Wear</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/ladies-bra/pl/3ji">Bra</a></li><br>
<li><a class="a1" href="https://www.meesho.com/briefs-women/pl/3kl">Breifs</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Sleepwear</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/nightdresses-women/pl/3nm">Nightsuits</a></li><br>
<li><a class="a1" href="https://www.meesho.com/babydoll-dress/pl/3kv">Babydolls</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:400px;
	height:300px" ><li></div>
</div>
</ul>
</li>
<li><a class="a1" href="#">Men</a>
<ul id="men">
<div style="border:1px solid #eef0ed;display:flex;position:absolute;background-color:#eef0ed;margin-top:3.5px;transform:translate(-329px);">
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:370px;"><li><a class="a1" style="color:rgb(136,2,80)">Top Wear</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/topwear-men/pl/3tc">All Top Wear</a></li><br>
<li><a class="a1" href="https://www.meesho.com/tshirts-men/pl/3k8">Tshirts</a></li><br>
<li><a class="a1" href="https://www.meesho.com/shirts-men/pl/3jq">Shirts</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:370px"><li><a class="a1" style="color:rgb(136,2,80)">Bottom Wear</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/track-pants-men/pl/3kw">Track Pants</a></li><br>
<li><a class="a1" href="https://www.meesho.com/jeans-men/pl/3nw">Jeans</a></li><br>
<li><a class="a1" href="https://www.meesho.com/trousers-men/pl/3lw">Trousers</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:370px;"><li><a class="a1" style="color:rgb(136,2,80)">Men Accessories</a></li><br><br>
	<li><a class="a1" href="https://www.meesho.com/accessories-men/pl/3tp">All Men Accessories</a></li><br>
<li><a class="a1" href="https://www.meesho.com/men-watches/pl/3k7">Watches</a></li><br>
<li><a class="a1" href="https://www.meesho.com/belts-men/pl/3nn">Belts</a></li><br>
<li><a class="a1" href="https://www.meesho.com/wallets-men/pl/3o5">Wallets</a></li><br>
<li><a class="a1" href="https://www.meesho.com/jewellery-men/pl/3tb">Jewellery</a></li><br>
<li><a class="a1" href="https://www.meesho.com/sunglasses-men/pl/3jr">Sunglasses</a></li><br>
<li><a class="a1" href="https://www.meesho.com/bags-backpacks-men/pl/3kr">Bags</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:370px"><li><a class="a1" style="color:rgb(136,2,80)">Men Footwear</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/casual-shoes-men/pl/3m2">Casual Shoes</a></li><br>
<li><a class="a1" href="https://www.meesho.com/sports-shoes-men/pl/3kj">Sports Shoes</a></li><br>
<li><a class="a1" href="https://www.meesho.com/sandals-men/pl/3js">Sandals</a></li><br>
<li><a class="a1" href="https://www.meesho.com/formal-shoes-for-men/pl/3o6">Formal Shoes</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:370px"><li><a class="a1" style="color:rgb(136,2,80)">Ethnic Wear</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/men-kurtas/pl/3j2">Men Kurtas</a></li><br>
<li><a class="a1" href="https://www.meesho.com/ethnic-jackets-men/pl/3j6">Ethnic Jackets</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:370px"><li><a class="a1" style="color:rgb(136,2,80)">Inner<code><b> & </b></code>Sleep Wear</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/inner-sleepwear-men/pl/3te">All Inner<code><b> & </b></code>Sleep Wear</a></li><br>
<li><a class="a1" href="https://www.meesho.com/vests-men/pl/3l0">Wests</a></li></div><br>
</div>
</ul>
</li>
<li><a class="a1" href="#" >Kids</a>
<ul id="kids">
<div style="border:1px solid #eef0ed;display:flex;position:absolute;background-color:#eef0ed;margin-top:3.5px;transform:translate(-416px)">
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Boys<code>&</code>Girls 2+ Years</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/dresses-kids/pl/3jg">Dresses</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:300px"><li><a a class="a1" style="color:rgb(136,2,80)">Infant 0-2 Years</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/rompers/pl/3l4">Rompers</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:300px"><li><a a class="a1" style="color:rgb(136,2,80)">Toys<code><b> & </b></code>Accessories</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/soft-toys-kids/pl/3l1">Soft Toys</a></li><br>
<li><a class="a1" href="https://www.meesho.com/footwear-kids/pl/3ti">Footwear</a></li><br>
<li><a class="a1" href="https://www.meesho.com/stationery-items/pl/3kz">Stationery</a></li><br>
<li><a class="a1" href="https://www.meesho.com/watches-kids/pl/3ko">Watches</a></li><br>
<li><a class="a1" href="https://www.meesho.com/bags-kids/pl/3kx">Bags<code>&</code>Backpacks</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:300px"><li><a a class="a1" style="color:rgb(136,2,80)">Baby Care</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/baby-care/pl/3tj">All Baby Care</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:470px;
	height:300px" ><li></div>
</div>
</ul>
</li>
<li><a class="a1" href="#" >Home<code><b> & </b></code>Kitchen</a>
<ul id="home">
<div style="border:1px solid #eef0ed;display:flex;position:absolute;background-color:#eef0ed;margin-top:3.5px;transform:translate(-500px)">
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:300px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Home Furnishing</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/bedsheets/pl/3jm">Bedsheets</a></li><br>
<li><a class="a1" href="https://www.meesho.com/door-bath-mats/pl/3kf">Doormates</a></li><br>
<li><a class="a1" href="https://www.meesho.com/curtains-sheers/pl/3jn">Curtains<code><b> & </b></code>Sheers</a></li><br>
<li><a class="a1" href="https://www.meesho.com/cushion-covers/pl/3k3">Cushions<code><b> & </b></code>Cushion Covers</a></li><br>
<li><a class="a1" href="https://www.meesho.com/mattress-protectors/pl/3l3">Mattress Protectors</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Home Decor</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/home-decor/pl/3tl">All Home Decor</a></li><br>
<li><a class="a1" href="https://www.meesho.com/decorative-stickers/pl/3ka">Stickers</a></li><br>
<li><a class="a1" href="https://www.meesho.com/clocks/pl/3kh">Clocks</a></li><br>
<li><a class="a1" href="https://www.meesho.com/show-pieces-home/pl/3ku">Showpieces</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Kitchen<code><b> & </b></code>Dining</a></li><br>
<li><a class="a1" href="https://www.meesho.com/kitchen-storage/pl/3tn">Kitchen Storage</a></li><br>
<li><a class="a1" href="https://www.meesho.com/cookware-bakeware/pl/3tm">Cookware<code> <b>&</b> </code>Backware</a></li></div><br>
<div style="background-color:#eef0ed;padding-top:25px;padding-left:20px;border:1px;width:600px;
	height:300px" ></div></div>
</ul>
</li>
<li><a class="a1" href="#" >Beauty<code> <b>&</b> </code>Health</a>
<ul id="beauty">
<div style=" border:1px solid #eef0ed;display:flex;position:absolute;background-color:#eef0ed;margin-top:3.5px;transform:translate(-690px)">
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Make up</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/face-makeup/pl/3j7">Face</a></li><br>
<li><a class="a1" href="https://www.meesho.com/eye-makeup/pl/3j1">Eyes</a></li><br>
<li><a class="a1" href="https://www.meesho.com/lips-makeup/pl/3jd">Lips</a></li><br>
<li><a class="a1" href="https://www.meesho.com/nails-makeup/pl/3j9">Nails</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:230px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Wellness</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/sanitizers/pl/3kg">Sanitizes</a></li><br>
<li><a class="a1" href="https://www.meesho.com/oral-care/pl/3tf">Oral Care</a></li><br>
<li><a class="a1" href="https://www.meesho.com/feminine-hygiene/pl/3tg">Feminine Hygiene</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Skincare</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/deodrants/pl/3kt">Deodorants</a></li></div><br>
<div style="background-color:#eef0ed;padding-top:25px;padding-left:20px;border:1px;width:700px;
	height:300px" ></div>
</div>
</ul>
</li>
<li><a class="a1" href="#" >Jewellery<code> <b>&</b> </code> Accessories</a>
<ul id="jewels">
<div style=" border:1px solid #eef0ed;display:flex;position:absolute;background-color:#eef0ed;margin-top:3.5px;transform:translate(-850px)">
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:390px"><li><a class="a1" style="color:rgb(136,2,80)">Jewellery</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/jewellery-sets-women/pl/3jy">Jewellery Set</a></li><br>
<li><a class="a1" href="https://www.meesho.com/earrings-women/pl/3lc">Earrings</a></li><br>
<li><a class="a1" href="https://www.meesho.com/mangalsutras/pl/3j5">Mangalsutras</a></li><br>
<li><a class="a1" href="https://www.meesho.com/stud-earrings-women/pl/3n9">Studs</a></li><br>
<li><a class="a1" href="https://www.meesho.com/bangles-women/pl/3lv">Bangles</a></li><br>
<li><a class="a1" href="https://www.meesho.com/necklaces/pl/3lh">Necklaces</a></li><br>
<li><a class="a1" href="https://www.meesho.com/rings-women/pl/3j8">Rings</a></li><br>
<li><a class="a1" href="https://www.meesho.com/anklets-payal/pl/3je">Anklets</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:250px;
	height:390px"><li><a class="a1" style="color:rgb(136,2,80)">Women Accessory</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/bags-ladies/pl/3jo">Bags</a></li><br>
<li><a class="a1" href="https://www.meesho.com/women-watches/pl/3jx">Watches</a></li><br>
<li><a class="a1" href="https://www.meesho.com/hair-accessories-women/pl/3jl">Hair Accessories</a></li><br>
<li><a class="a1" href="https://www.meesho.com/sunglasses-women/pl/3kd">Sunglasses</a></li><br>
<li><a class="a1" href="https://www.meesho.com/socks-women/pl/3km">Socks</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:850px;
	height:390px" ></div>
</div>
</ul>
</li>
<li><a class="a1" href="#" >Bags<code><b> & </b></code> Footwear</a>
<ul id="bags">
<div style=" border:1px solid #eef0ed;display:flex;position:absolute;background-color:#eef0ed;margin-top:3.5px;transform:translate(-1100px)">
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Women Bags</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/bags-ladies/pl/3jo">All Women Bags</a></li><br>
<li><a class="a1" href="https://www.meesho.com/handbags-women/pl/3k2">Handbags</a></li><br>
<li><a class="a1" href="https://www.meesho.com/clutches-bags-women/pl/3nd">Clutches</a></li><br>
<li><a class="a1" href="https://www.meesho.com/slingbags-women/pl/3k4">Slingbags</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Men Bags</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/bags-backpacks-men/pl/3kr">All Men Bags</a></li><br>
<li><a class="a1" class="a1" href="https://www.meesho.com/wallets-men/pl/3o5">Men Wallets</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:200px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Men Footwear</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/sports-shoes-men/pl/3kj">Sports Shoes</a></li><br>
<li><a class="a1" href="https://www.meesho.com/casual-shoes-men/pl/3m2">Casual Shoes</a></li><br>
<li><a class="a1" href="https://www.meesho.com/formal-shoes-for-men/pl/3o6">Formal Shoes</a></li><br>
<li><a class="a1" href="https://www.meesho.com/sandals-men/pl/3js">Sandals</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:230px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Women Footwear</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/flats-women/pl/3o1">Flats</a></li><br>
<li><a class="a1" href="https://www.meesho.com/bellies/pl/3n8">Bellies</a></li><br>
<li><a class="a1" href="https://www.meesho.com/jutti/pl/3lx">Juttis</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:500px;
	height:300px" ></div>
</div>
</ul>
</li>
<li><a class="a1" href="#" style="padding-left:13px;padding-right:40px" >Electronics</a>
<ul id="electronics">
<div style=" border:1px solid #eef0ed;display:flex;position:absolute;background-color:#eef0ed;margin-top:3.5px;transform:translate(-1280px)">
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:280px;
	height:300px""><li><a class="a1" style="color:rgb(136,2,80)">Mobile<code><b> & </b></code>Accessories</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/mobiles-and-accessories/pl/3tk">All Mobile<code><b> & </b></code>Accessories</a></li><br>
<li><a class="a1" href="https://www.meesho.com/smart-watches/pl/3ks">Smartwatches</a></li><br>
<li><a class="a1" href="https://www.meesho.com/mobile-holders/pl/3ky">Mobile Holders</a></li><br>
<li><a class="a1" href="https://www.meesho.com/mobile-cases-covers/pl/3q3">Mobile cases and covers</a></li></div><br>
<div style="padding-top:25px;padding-left:20px;border:1px;width:230px;
	height:300px"><li><a class="a1" style="color:rgb(136,2,80)">Appliances</a></li><br><br>
<li><a class="a1" href="https://www.meesho.com/appliances/pl/3to">All Appliances</a></li><br>
<li><a class="a1" href="https://www.meesho.com/grooming-kits-men/pl/3kn">Grooming</a></li><br>
<li><a class="a1" href="https://www.meesho.com/home-appliances/pl/3th">Home Appliances</a></li></div><br>
<div style="background-color:white;padding-top:25px;padding-left:20px;border:1px;width:870px;
	height:300px" ></div><br>
</div>
</li>

</ul>

</ul>

</div></ul>
</div>
<table class="table1">
<tr><th><div class="C">
<div class="price">
<h2 style="font-size:45px;margin-left:40px;margin-top:30px">Lowest Prices<br>Best Quality Shopping</h2>
<div class="box">
<div style="margin-top:10px">
<i class="fa-solid fa-truck">Free<br>Delivery</i>
</div>
<hr>
<div style="margin-top:10px">
<i class="fa-solid fa-wallet">Cash on<br>Delivery</i>
</div>
<hr>
<div style="margin-top:10px">
<i class="fa-solid fa-bag-shopping">Easy<br>Returns</i>
</div>
</div>

<div class="link">
<a href="https://play.google.com/store/apps/details?id=com.meesho.supply&pid=pow_website&c=pow&pow_click_page_type=HP&pow_distinct_id=19029ddd928495-068807a6c9f2fb-26001c51-144000-19029ddd929106e&pli=1" style="text-decoration:none;color:white;margin-right:20px"><img src="what.jpeg" width="30px" height="30px"  class="play" style="margin-top:10px">Download the Meesho App</a>
</div>
</th>
</div>
<th>
<div class="pic">
<img src="what1.jpeg" style="margin-top:53px" width="500px" height="350px">
</div>
</tr></th>
</div>
</table>
<div style="display:flex;align-items:center;margin-left:130px">
<div class="cat" style="margin-left:30px">
</div>
<div class="text2">
<b>Top Catagories to choose from</b>
</div>
<div class="cat">
</div>
</div>
<center>
<div class="pair">
<div class="D">
<h1 style="color:white;margin-left:250px">Be fashion forward</h1>
<div class="flex">
<div style="margin-top:10px;margin-left:30px" class="d1">
<div>
<a style="text-decoration:none" href="https://www.meesho.com/women-store/pl/3g5o"><b>Women's Store</b></a>
</div>
<div class="wo1">
<a style="text-decoration:none" href="https://www.meesho.com/women-store/pl/3g5o"><img src="mes1.jpg" width="150px" height="150px" style="margin-left:16px"><br>Clothing </a>

<a style="text-decoration:none" href="https://www.meesho.com/women-store/pl/3g5o"><img src="mes2.jpg" width="150px" height="150px" style="margin-left:16px"><br>Handbag</a>
</div>
<div class="wo2">
<a  style="text-decoration:none" href="https://www.meesho.com/women-store/pl/3g5o"><img src="mes3.jpg" width="150px" height="150px" style="margin-left:16px"><br>Jewellery</a>

<a style="text-decoration:none" href="https://www.meesho.com/women-store/pl/3g5o"><img src="mes4.jpg" width="150px" height="150px" style="margin-left:16px"><br>Beauty</a>
</div>
</div>
<div style="margin-left:15px;margin-top:110px" class="d2">
<a style="text-decoration:none" href="https://www.meesho.com/men-store/pl/3g5p"><b>men's Store</b></a>
<div style="margin-left:30px" class="me1">
<a style="text-decoration:none" href="https://www.meesho.com/men-store/pl/3g5p"><img src="mes5.jpg" width="120px" height="90px"><br>Clothing</a>

<a style="text-decoration:none" href="https://www.meesho.com/men-store/pl/3g5p"><img src="mes6.jpg" width="120px" height="90px" style="margin-left:30px"><br>Grooming</a>
</div>
<div class="me2">
<a style="text-decoration:none" href="https://www.meesho.com/men-store/pl/3g5p"><img src="mes7.jpg" width="120px" height="90px" style="margin-left:30px"><br>Belt</a>

<a style="text-decoration:none" href="https://www.meesho.com/men-store/pl/3g5p"><img src="mes8.jpg" width="120px" height="90px" style="margin-left:30px"><br>Watches</a>
</div>
</div>
<div style="margin-left:15px;margin-top:110px" class="d3">
<a style="text-decoration:none" href="https://www.meesho.com/kids-store/pl/3g5q"><b>kid's Store</b></a>
<div style="margin-left:30px" class="ki1">
<a style="text-decoration:none" href="https://www.meesho.com/kids-store/pl/3g5q"><img src="mes9.jpg" width="120px" height="90px"><br>Clothing</a>

<a style="text-decoration:none" href="https://www.meesho.com/kids-store/pl/3g5q"><img src="mes10.jpg" width="120px" height="90px" style="margin-left:30px"><br>Accessories</a>
</div>
<div style="margin-left:30px" class="ki2">
<a style="text-decoration:none" href="https://www.meesho.com/kids-store/pl/3g5q"><img src="mes11.jpg" width="120px" height="90px"><br>Toys</a>

<a style="text-decoration:none" href="https://www.meesho.com/kids-store/pl/3g5q"><img src="mes12.jpg" width="120px" height="90px" style="margin-left:30px"><br>Healthcare</a>
</div>
</div>
</div>
</div>
</div>
<center>
<div style="margin-top:60px" class="box9">
<div class="size"><h1 style="color:white;font-size:50px">Essentials</h1>
<a style="text-decoration:none" href="https://www.meesho.com/essentials/pl/9ol"><div class="border"><div class="fo">View All</div></div></a>
</div>
<div class="ho1">
<div>
<a style="text-decoration:none" href="https://www.meesho.com/home-decor/pl/3tl"><img src="https://images.meesho.com/images/marketing/1690978007288_200.webp" height="350px" width="200px"><div class="doll">Home Decoder</div></a>
</div>
</div>
<div class="ho2">
<div>
<a style="text-decoration:none" href="https://www.meesho.com/kitchen-accessories/pl/1i3z"><img src="https://images.meesho.com/images/marketing/1690978024110_200.webp" height="350px" width="200px"><div class="doll1">Kitchen Applications</div></a>
</div>
</div>
<div class="ho3">
<div>
<a style="text-decoration:none" href="https://www.meesho.com/skincare/pl/5kw"><img src="https://images.meesho.com/images/marketing/1690977994925_200.webp" height="350px" width="200px"><div class="doll2">Health Care</div></a>
</div>
</div>
</div>
</center>
<center>
<div style="margin-top:60px" class="box10">
<div class="size"><h1 style="color:white;font-size:50px">New Styles</h1>
<a style="text-decoration:none" href="https://www.meesho.com/essentials/pl/9ol"><div class="border1"><div class="fo1">View All</div></div></a>
</div>
<div class="h4">
<div>
<a style="text-decoration:none" href="https://www.meesho.com/accessories/pl/1k5q"><img src="https://images.meesho.com/images/marketing/1690977773436_200.webp" height="350px" width="200px"><div class="doll3">Accessories</div></a>
</div>
</div>
<div class="h5">
<div>
<a style="text-decoration:none" href="https://www.meesho.com/footwear/pl/3yb"><img src="https://images.meesho.com/images/marketing/1690977909442_200.webp" height="350px" width="200px"><div class="doll4">Footwears</div></a>
</div>
</div>
<div class="h6">
<div>
<a style="text-decoration:none" href="https://www.meesho.com/electronics/pl/45g"><img src="https://images.meesho.com/images/marketing/1690977645848_200.webp" height="350px" width="200px"><div class="doll5">Electronics</div></a>
</div>
</div>
</div>
<div class="last">
<div style="margin-top:60px" class="image"><img src="https://images.meesho.com/images/pow/downloadBannerDesktop_1050.webp" width="1100px" height="550px"><div class="font1"><p>Become a Reseller and</p></div><div class="font2"><h1> Start your Online Business</h1></div><div class="font3"><h1>with Zero Investment</h1></div><div class="place"><div><a href="https://play.google.com/store/apps/details?id=com.meesho.supply&pid=pow_website&c=pow&pow_click_page_type=HP&pow_distinct_id=19029ddd928495-068807a6c9f2fb-26001c51-144000-19029ddd929106e"><img src="https://images.meesho.com/images/pow/playstoreIcon_500.webp" height="50px" width="180px"></div></a><a href="https://apps.apple.com/us/app/meesho-online-shopping/id1457958492"><div style="margin-left:15px"><image src="https://images.meesho.com/images/pow/appstoreIcon_500.webp" height="50px" width="180px"> </div></a></div>
</div>
</div>
<div class="last1">
<a href="https://supplier.meesho.com/?utm_source=meesho&utm_medium=website&utm_campaign=banner"><div style="margin-top:60px;margin-Bottom:60px"><img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*fx7ElXTQ-QZh79fs-rVX2Q.png" width="1100px" height="300px">
</a></div>
</div>
</center>
</body>
</html>
