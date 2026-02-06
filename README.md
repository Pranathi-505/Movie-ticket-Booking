# Movie-ticket-Booking
# HOME PAGE
<!DOCTYPE html>  
<html lang="en">  
<head>  
  <title>Bootstrap Case</title>  
  <meta charset="utf-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1">  
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">  
  <link rel="stylesheet" href="style.css">
</head>  
<body>  
  
<div class="container">  
  <h1 style="text-align: center;">Movie ticket Booking</h1>  
  
  <ul class="nav nav-tabs">  
    <li class="active"><a href="ho">Home</a></li>  
    <li><a href="Movies.html">Movies</a></li>  
    <li><a href="about.html">About us</a></li>  
    <li><a href="Login.html">Login</a></li>  
  </ul> 
  
  <br>
 
  <div class="row" style="text-align: center;">
    <div class="column">
      <img src="images/2.jpg" alt="Snow" style="width:100%">
      <h2>RRR</h2>
    </div>

    <div class="column">
      <img src="images/8.jpg" alt="Forest" style="width:100%">
      <h2>Avatar</h2>
    </div>

    <div class="column">
      <img src="images/4.jpg" alt="Mountains" style="width:100%">
      <h2>99</h2>
    </div>

   # MOVIES PAGE


<!DOCTYPE html>  
<html lang="en">  
   
    <style>
          * {
    box-sizing: border-box;
}

body {
    background-image: linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.8)),url("https://static.chaos.com/images/assets/000/013/861/full_width_original/PSX_20211022_164829.jpg?1634917737");
    background-position: center;
    background-size: cover;
    margin-bottom: 500px;
}
  h1 {
    color: white;
  }
  p {
    color: red;
  }
  ul{
    font-size: 20px;
  }
  .column {
    float: left;
    width: 30%;
    padding: 20px;
    border-color: aqua;
    border-bottom: 50px;
  }
  
  .row::after {
    content: "";
    clear: both;
    display: table;
   
  }
  img {
    border-radius: 20%;
    height: 500px;
    border: 6px solid #d31d1d;
  }
  h3{
    background-color: aliceblue;
    
  }
  button {
    background-color: #15bbe4;
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
    border-radius: 12px;
}

    </style>

<head>  
  <title>Bootstrap Case</title>  
  <meta charset="utf-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1">  
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">  
 
</head>   
<body>  
    <div class="container">  
        <h1 style="text-align: center; color: aqua;">Movies</h1>  
        
        <ul class="nav nav-tabs" style="background-color: white">  
          <li ><a href="Home.html">Home</a></li>  
          <li><a href="Movies.html">Movies</a></li>  
          <li><a href="about.html">About us</a></li>  
          <li><a href="Login.html">Login</a></li>  
        </ul> 
        
        <br>
        <div class="row" style="text-align: center; ">
        <div class="column">
          <img src="images/2.jpg" alt="Snow" style="width:100%">
          <h3>RRR</h3>
          <button id="mybutton">Book Now</button>
        </div>
        <script type="text/javascript">
            document.getElementById("mybutton").onclick = function () {
                location.href = "http://127.0.0.1:5500/confo.html";
            };
        </script>
        <div class="column">
          <img src="images/8.jpg" alt="Forest" style="width:100%">
          <h3>Avatar</h3>
          <button id="mybutton1">Book Now</button>
        </div>
        <script type="text/javascript">
            document.getElementById("mybutton1").onclick = function () {
                location.href = "http://127.0.0.1:5500/confo.html";
            };
        </script>
    
        <div class="column">
          <img src="images/4.jpg" alt="Mountains" style="width:100%">
          <h3>99</h3>
          <button id="mybutton2">Book Now</button>
        </div>
        <script type="text/javascript">
            document.getElementById("mybutton2").onclick = function () {
                location.href = "http://127.0.0.1:5500/confo.html";
            };
        </script>
      </div>
    
    </div>  
   
    </body>  
    </html>


    
  </div>

</div>  
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script> 

# LOGIN PAGE

<!DOCTYPE html>  
<html lang="en">  
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"></script>
<style>body{margin: 0;padding: 0;background: url(https://i.ibb.co/VQmtgjh/6845078.png) no-repeat;height: 100vh;font-family: sans-serif;background-size: cover;background-repeat: no-repeat;background-position: center;overflow: hidden}@media screen and (max-width: 600px){body{background-size: cover; }}#particles-js{height: 100%}.loginBox{position: absolute;top: 50%;left: 50%;transform: translate(-50%,-50%);width: 350px;min-height: 200px;background: #000000;border-radius: 10px;padding: 40px;box-sizing: border-box}.user{margin: 0 auto;display: block;margin-bottom: 20px}h3{margin: 0;padding: 0 0 20px;color: #59238F;text-align: center}.loginBox input{width: 100%;margin-bottom: 20px}.loginBox input[type="text"], .loginBox input[type="password"]{border: none;border-bottom: 2px solid #262626;outline: none;height: 40px;color: #fff;background: transparent;font-size: 16px;padding-left: 20px;box-sizing: border-box}.loginBox input[type="text"]:hover, .loginBox input[type="password"]:hover{color: #42F3FA;border: 1px solid #42F3FA;box-shadow: 0 0 5px rgba(0,255,0,.3), 0 0 10px rgba(0,255,0,.2), 0 0 15px rgba(0,255,0,.1), 0 2px 0 black}.loginBox input[type="text"]:focus, .loginBox input[type="password"]:focus{border-bottom: 2px solid #42F3FA}.inputBox{position: relative}.inputBox span{position: absolute;top: 10px;color: #262626}.loginBox input[type="submit"]{border: none;outline: none;height: 40px;font-size: 16px;background: #59238F;color: #fff;border-radius: 20px;cursor: pointer}.loginBox a{color: #262626;font-size: 14px;font-weight: bold;text-decoration: none;text-align: center;display: block}a:hover{color: #00ffff}p{color: #0000ff}</style>
<div class="loginBox"> <img class="user" src="https://i.ibb.co/yVGxFPR/2.png" height="100px" width="100px">
    <h3>Sign in here</h3>
    <form action="http://127.0.0.1:5500/sumathi/loginconf.html" method="post">
        <div class="inputBox"> <input id="uname" type="text" name="Username" placeholder="Username"> <input id="pass" type="password" name="Password" placeholder="Password"> </div>
        <div class="text-center">
        <button style="text-align: center;" type="button" id="mybutton2" class="btn btn-success">Sign in</button>
    </div>
        <script type="text/javascript">
            document.getElementById("mybutton2").onclick = function () {
                location.href = "http://127.0.0.1:5500/loginconf.html";
            };
        </script>
    </form> 
    
    
</div>

# LOGIN CONFORM PAGE

<style>
    *{
  box-sizing:border-box;
 /* outline:1px solid ;*/
}
body{
background: #ffffff;
background: linear-gradient(to bottom, #ffffff 0%,#e1e8ed 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ffffff', endColorstr='#e1e8ed',GradientType=0 );
    height: 100%;
        margin: 0;
        background-repeat: no-repeat;
        background-attachment: fixed;
  
}

.wrapper-1{
  width:100%;
  height:100vh;
  display: flex;
flex-direction: column;
}
.wrapper-2{
  padding :30px;
  text-align:center;
}
h1{
    font-family: 'Kaushan Script', cursive;
  font-size:4em;
  letter-spacing:3px;
  color:#5892FF ;
  margin:0;
  margin-bottom:20px;
}
.wrapper-2 p{
  margin:0;
  font-size:1.3em;
  color:#aaa;
  font-family: 'Source Sans Pro', sans-serif;
  letter-spacing:1px;
}
.go-home{
  color:#fff;
  background:#5892FF;
  border:none;
  padding:10px 50px;
  margin:30px 0;
  border-radius:30px;
  text-transform:capitalize;
  box-shadow: 0 10px 16px 1px rgba(174, 199, 251, 1);
}
.footer-like{
  margin-top: auto; 
  background:#D7E6FE;
  padding:6px;
  text-align:center;
}
.footer-like p{
  margin:0;
  padding:4px;
  color:#5892FF;
  font-family: 'Source Sans Pro', sans-serif;
  letter-spacing:1px;
}
.footer-like p a{
  text-decoration:none;
  color:#5892FF;
  font-weight:600;
}

@media (min-width:360px){
  h1{
    font-size:4.5em;
  }
  .go-home{
    margin-bottom:20px;
  }
}

@media (min-width:600px){
  .content{
  max-width:1000px;
  margin:0 auto;
}
  .wrapper-1{
  height: initial;
  max-width:620px;
  margin:0 auto;
  margin-top:50px;
  box-shadow: 4px 8px 40px 8px rgba(88, 146, 255, 0.2);
}
  
}
</style>

<div class=content>
    <div class="wrapper-1">
      <div class="wrapper-2">
        <h1>Thank you !</h1>
        <p>Thanks for Sign in  </p>
        <p>Please book your movie</p>
        <button class="go-home" id="mybutton3">
         back to booking
        </button>
        <script type="text/javascript">
            document.getElementById("mybutton3").onclick = function () {
                location.href = "http://127.0.0.1:5500/Movies.html";
            };
        </script>
      </div>
    
  </div>
  </div>
  
  
  
  <link href="https://fonts.googleapis.com/css?family=Kaushan+Script|Source+Sans+Pro" rel="stylesheet">
<script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>  
</body>  
</html>

# BOOKING  PAGE
<!DOCTYPE html>  
<html lang="en">  
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"></script>
<style>body{margin: 0;padding: 0;background: url(https://i.ibb.co/VQmtgjh/6845078.png) no-repeat;height: 100vh;font-family: sans-serif;background-size: cover;background-repeat: no-repeat;background-position: center;overflow: hidden}@media screen and (max-width: 600px){body{background-size: cover; }}#particles-js{height: 100%;}.loginBox{position: absolute;top: 50%;left: 50%;transform: translate(-50%,-50%);width: 350px;min-height: 200px;background: #000000;border-radius: 10px;padding: 40px;box-sizing: border-box}.user{margin: 0 auto;display: block;margin-bottom: 20px}h3{margin: 0;padding: 0 0 20px;color: #59238F;text-align: center}.loginBox input{width: 100%;margin-bottom: 20px}.loginBox input[type="text"], .loginBox input[type="password"]{border: none;border-bottom: 2px solid #262626;outline: none;height: 40px;color: #fff;background: transparent;font-size: 16px;padding-left: 20px;box-sizing: border-box}.loginBox input[type="text"]:hover, .loginBox input[type="password"]:hover{color: #42F3FA;border: 1px solid #42F3FA;box-shadow: 0 0 5px rgba(0,255,0,.3), 0 0 10px rgba(0,255,0,.2), 0 0 15px rgba(0,255,0,.1), 0 2px 0 black}.loginBox input[type="text"]:focus, .loginBox input[type="password"]:focus{border-bottom: 2px solid #42F3FA}.inputBox{position: relative}.inputBox span{position: absolute;top: 10px;color: #262626}.loginBox input[type="submit"]{border: none;outline: none;height: 40px;font-size: 16px;background: #59238F;color: #fff;border-radius: 20px;cursor: pointer}.loginBox a{color: #262626;font-size: 14px;font-weight: bold;text-decoration: none;text-align: center;display: block}a:hover{color: #00ffff}p{color: #0000ff}</style>
<body>
  <div class="loginBox"> <img class="user" src="https://i.ibb.co/yVGxFPR/2.png" height="100px" width="100px">
  <h3>Conformation!</h3>
  <form action="bookcofo.html" method="post">
      <div class="inputBox"> <input id="uname" type="text" name="Username" placeholder="Username"> <input id="pass" type="number" name="password" placeholder="number of seats">
        <input id="pass" type="text" name="password" placeholder="email Id">
        <div class="text-center">
        <button style="text-align: center;" type="button" id="mybutton2" class="btn btn-success">submit</button>
      </div>
        <script type="text/javascript">
            document.getElementById("mybutton2").onclick = function () {
                location.href = "http://127.0.0.1:5500/bookcofo.html";
            };
        </script>
  </form> 

  
</div>
</body>

# BOOKING CONFORM PAGE

<style>
    @import url('https://fonts.googleapis.com/css?family=Raleway:100,200,300,400,500,600,700,800,900&display=swap');
html,body {
    font-family: 'Raleway', sans-serif;  
}
.thankyou-page ._header {
    background: #fee028;
    padding: 100px 30px;
    text-align: center;
    background: #15cade url(https://codexcourier.com/images/main_page.jpg) center/cover no-repeat;
}
.thankyou-page ._header .logo {
    max-width: 200px;
    margin: 0 auto 50px;
}
.thankyou-page ._header .logo img {
    width: 100%;
}
.thankyou-page ._header h1 {
    font-size: 65px;
    font-weight: 800;
    color: white;
    margin: 0;
}
.thankyou-page ._body {
    margin: -70px 0 30px;
}
.thankyou-page ._body ._box {
    margin: auto;
    max-width: 80%;
    padding: 50px;
    background: white;
    border-radius: 3px;
    box-shadow: 0 0 35px rgba(10, 10, 10,0.12);
    -moz-box-shadow: 0 0 35px rgba(10, 10, 10,0.12);
    -webkit-box-shadow: 0 0 35px rgba(10, 10, 10,0.12);
}
.thankyou-page ._body ._box h2 {
    font-size: 32px;
    font-weight: 600;
    color: #4ab74a;
}
.thankyou-page ._footer {
    text-align: center;
    padding: 50px 30px;
}

.thankyou-page ._footer .btn {
    background: #4ab74a;
    color: white;
    border: 0;
    font-size: 14px;
    font-weight: 600;
    border-radius: 0;
    letter-spacing: 0.8px;
    padding: 20px 33px;
    text-transform: uppercase;
}
</style>
<div class="thankyou-page">
    <div class="_header">
        
        <h1>Thank You!</h1>
    </div>
    <div class="_body">
        <div class="_box">
            <h2>
                <strong>Thank you for Booking,</strong> Please book more movies and enjoy your day with us.
            </h2>
           
        </div>
    </div>
    <div class="_footer">
        
        <a class="btn" href="Home.html">Back to homepage</a>
    </div>
</div

  # ABOUT US PAGE

<style>
    body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 20%;
  margin-bottom: 16px;
  padding: 0 8px;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  margin: 8px;
}

.about-section {
  padding: 50px;
  text-align: center;
  background-color: #474e5d;
  color: white;
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}
</style>
<div class="about-section">
    <h1>About Us Page</h1>

  </div>
  
  <h2 style="text-align:center">Our Team</h2>
  <div class="row">
    <div class="column">
      <div class="card">
        <img src="images/p.jpg" alt="Jane" style="width:50%">
        <div class="container">
          <h2>Pranathi M S</h2>
          <p class="title">USN : 1EW22EE021</p>

         
        </div>
      </div>
    </div>
   </div>
