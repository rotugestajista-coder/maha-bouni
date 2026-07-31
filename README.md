# maha-bouni
 the one and only bouni 4feet girl MAHA
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Maha</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#ffd6e7;
    color:#5c0031;
}

header{
    background:#ff4f9a;
    color:white;
    text-align:center;
    padding:25px;
    font-size:36px;
    font-weight:bold;
    box-shadow:0 4px 10px rgba(0,0,0,.15);
}

.container{
    display:flex;
    gap:30px;
    max-width:1200px;
    margin:auto;
    padding:40px;
}

.content{
    flex:3;
}

.content h2{
    margin-bottom:20px;
    color:#b0005a;
}

.content p{
    background:white;
    padding:25px;
    border-radius:15px;
    line-height:1.8;
    font-size:18px;
    box-shadow:0 5px 15px rgba(0,0,0,.15);
}

.sidebar{
    flex:1;
    background:#fff0f7;
    border-radius:15px;
    padding:20px;
    text-align:center;
    box-shadow:0 5px 15px rgba(0,0,0,.15);
}

.sidebar h3{
    color:#b0005a;
    margin-bottom:20px;
}

.profile-pic{
    width:180px;
    height:180px;
    border-radius:50%;
    object-fit:cover;
    border:5px solid #ff4f9a;
    box-shadow:0 0 20px hotpink;
    transition:.3s;
}

.profile-pic:hover{
    transform:scale(1.08);
    box-shadow:0 0 30px deeppink;
}

.sidebar p{
    margin-top:15px;
    font-weight:bold;
}

footer{
    background:#ff4f9a;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:40px;
}

/* Mobile Responsive */

@media(max-width:768px){

header{
    font-size:28px;
}

.container{
    flex-direction:column;
    padding:20px;
}

.content p{
    font-size:17px;
}

.sidebar{
    width:100%;
}

.profile-pic{
    width:220px;
    height:220px;
}

}
</style>

</head>

<body>

<header>
    Welcome to Maha's Page 💖
</header>

<div class="container">

<div class="content">

<h2>About</h2>

<p>
<p>
Being short comes with its own set of funny moments! 😂 Sometimes the top shelf looks like it's in another country, and asking someone to grab something becomes a daily superpower. Group photos almost always mean a guaranteed front-row VIP spot. Hoodies feel extra cozy because they're basically mini blankets, and finding legroom is never a problem. Friends might joke about height, but being short also means being quick, confident, and standing out in your own way. In the end, personality is always much bigger than height, and a good sense of humor is something everyone can appreciate. 😄
</p>
</p>

</div>

<div class="sidebar">

<h3>Instagram 💖</h3>

<a href="https://www.instagram.com/_j_i_n_n_i/?utm_source=ig_web_button_share_sheet" target="_blank">

<img src="6dea7653-fac8-4bd8-8db6-0923d7ce8531.png"
class="profile-pic"
alt="Profile Picture">

</a>

<p>Tap the picture to visit the profile 📸</p>

</div>

</div>

<footer>
Made with ❤️ using HTML & CSS
</footer>

</body>
</html>
