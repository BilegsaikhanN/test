<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="http://www.w3schools.com/lib/w3.css">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<link href="https://fonts.googleapis.com/css?family=Slabo+27px" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="shortcut icon" href="my ico.ico" type="ico" />

<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: 100% 100%;
}
* {
  box-sizing: border-box;
}
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  position: relative;
  overflow: hidden;
  background-color: none;
}

.topnav a {
  float: left;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 8px;
}

.topnav a:hover {
  background-color: red;
  color: black;
}

.topnav a.active {
  background-color: none;
  color: grey;
}

.topnav input[type=text] {
  float: right;
  padding: 6px;
  margin-top: 8px;
  margin-right: 16px;
  border: none;
  font-size: 10px;
}

.topnav-centered a {
  float: none;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.topnav-right {
  float: right;
}

/* Responsive navigation menu (for mobile devices) */
@media screen and (max-width: 600px) {
  .topnav a, .topnav-right {
    float: none;
    display: block;
  }

  .topnav-centered a {
    position: relative;
    top: 0;
    left: 0;
    transform: none;
  }
}

/* CSS for main element */
    .intro {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: left;
      width: 100%;
      height: 520px;
      background: linear-gradient(to bottom, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.5) 100%), url("R.jfif");
      background-size: 50%;
      background-position: right;
      background-repeat: no-repeat;
    }

    .intro h1 {
      font-family: sans-serif;
      font-size: 40px;
      color: black;
      font-weight: bold;
      text-transform: uppercase;
      margin: 0;
    }

    .intro p {
      font-size: 10px;
      color: black;
      text-transform: uppercase;
      margin: 20px 0;
    }

    .intro button {
      background-color: black;
      color: white;
      padding: 10px 25px;
      border: none;
      border-radius: 5px;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0px 0px 20px rgba(255, 255, 255, 0.4)
    }

    .achievements {
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 40px 80px;
    }

    .achievements .work {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 0 40px;
    }

    .achievements .work i {
      width: fit-content;
      font-size: 50px;
      color: #333333;
      border-radius: 50%;
      border: 2px solid #333333;
      padding: 12px;
    }

    .achievements .work .work-heading {
      font-size: 20px;
      color: #333333;
      text-transform: uppercase;
      margin: 10px 0;
    }

    .achievements .work .work-text {
      font-size: 15px;
      color: #585858;
      margin: 10px 0;
    }

    .WOMEN {
      display: flex;
      justify-content: center;
      align-items: left;
      padding: 40px 80px;
      border-top: 2px solid #eeeeee;
    }

     .WOMEN-text h2 {
      float: center;
	  align-items: center;
      font-size: 30px;
      color: #333333;
      text-transform: uppercase;
      margin: 0;
    }
    .WOMEN-text p {
       float: left;
      align-items: left;
      font-size: 15px;
      color: #585858;
      margin: 10px 0;
   }


/* CSS for footer */
    .footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: none;
      padding: 40px 80px;
    }

    .footer .copy {
      color: black;
    }

    .bottom-links {
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 40px 0;
    }

    .bottom-links .links {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 0 40px;
    }

    .bottom-links .links span {
      font-size: 20px;
      color: #fff;
      text-transform: uppercase;
      margin: 10px 0;
    }

    .bottom-links .links a {
      text-decoration: none;
      color: #a1a1a1;
      padding: 10px 20px;
    }

</style>
</head>
<body>


<!-- Top navigation -->
<div class="topnav">

  <!-- Centered link -->
  <div class="topnav-centered">
    <a href="#home" class="active">GOBI</a>
  </div>

  <!-- Left-aligned links (default) -->
  <a href="home.html"> HOME</a>
  <a href="men.html"> MEN</a>
  <a href="Women.html"> WOMEN</a>
  <a href="accessories.html"> ACCESSORIES</a>
  <a href="organic.html"> ORGANIC</a>
  <input type="text" placeholder="Search..">
  </div>

 <main>
    <div class="intro">
      <h1>WINTER SPICE 2020</h1>
      <p>Infusion of summer pieces and cashmere silk blends.</p>
      <button>SHOP NOW</button>
    </div>

	<div class="WOMEN">
      <div class="WOMEN-text">
        <h2>WOMEN</h2>

       <p><img src="women1.jfif" alt="cardigans" title="CARDIGANS" style="float:left;width:300px;height:300px;"></p>
	   <p><img src="poncho.jfif" alt="poncho" title="PONCHOS" style="float:center;width:300px;height:300px;"></p>
	   <p><img src="sweater.jfif" alt="sweater" title="SWEATERS" style="float:right;width:300px;height:300px;"></p>
	  </div>
    </div>
  </main>

<footer class="footer">
    <div class="copy">&copy; Copyright @ Gobi Cashmere</div>
    <div class="bottom-links">
      <div class="links">
        <span>More Info</span>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
      </div>
      <div class="links">
        <span>Social Links</span>
        <a href="#"><i class="fab fa-facebook"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
  </footer>

</body>
</html>
