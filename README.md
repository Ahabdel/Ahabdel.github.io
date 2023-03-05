![logo](https://user-images.githubusercontent.com/64559175/222990903-b2af0ac7-58e2-4e6c-bea2-d7834af3a14d.png)
![cart](https://user-images.githubusercontent.com/64559175/222990927-b0879a59-ffba-4109-a169-01d3c0e824da.png)
![DentalBanner](Dentalbanner.png)
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="with=deivce-width, initial-
    scale=1.0">
     <title>Dental Course Website</title>
     <link rel="stylesheet" href="style.css">
     <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">
</head>
<body>
  <section class="header">
    <nav>
      <div class="logo">
        <img src="images/logo.png" >
      </div>
      <div class="nav-links" id="navLinks">
        <i class="fa-sharp fa-solid fa-xmark" onclick="hideMenu()"></i>
        <ul> 
          <li><a href="Home.html">HOME</a></li>
          <li><a href="Courses.html">COURSES</a></li>
          <li><a href="MyAccount.html">MY ACCOUNT</a></li>
          <li><a href="ContactUs.html">CONTACT US</a></li>
          <li><a href="Cart.html"><img src="images/cart.png" width="30px" height="30px" ></a></li>
        </ul>
      </div>
      <i class="fa-solid fa-bars" onclick="showMenu()"></i>
    </nav>
<div class="text-box">
  <h1>Learn The Latest Techniques In Dental Care</h1>
  <p>Our courses provide in-depth training on the newest and most effective dental procedures, so you can provide the best care to your patients.</p>
  <a href=""class="hero-btn">See Courses</a>
  <br>
  <br>
  <br>
  <video width="35%" controls>
    <source src="video.mp4" type="video/mp4" >
  </video>
</div>
   </section>

<!-------- Course --------->

<section class="course">
  <h1>Courses We Offer</h1>
  <p></p>

  <div class="row">
    <div class="course-col">
      <h3>Intermediate</h3>
      <p>Snjdn djndjndj djndsjndj dndsjnd</p>
      <br>
      <a href="Courses.html" class="course1-btn">More Info</a>
    </div>  
    <div class="course-col">
      <h3>Degree</h3>
      <p>Snjdn djndjndj djndsjndj dndsjnd</p>
      <br>
      <a href="Courses.html" class="course2-btn">More Info</a>
    </div>
    <div class="course-col">
      <h3>Post Graduation</h3>
      <p>Snjdn djndjndj djndsjndj dndsjnd</p>
      <br>
      <a href="Courses.html" class="course3-btn">More Info</a>
    </div>
  </div>
</section>

<!---------- Footer ---------->
<section class="footer">
  <a href="AboutUs.html" class="aboutus-btn">About Us</a>

</section>


<!---------JavaScript for Toggle Menu-------->

<script>
      var navLinks = document.getElementById("navLinks");
      
      function showMenu(){
        navLinks.style.right = "0";
      }
      function hideMenu(){
        navLinks.style.right = "-200px";
      }
   </script>
   
  </body>
</html>
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="with=deivce-width, initial-
    scale=1.0">
     <title>Dental Course Website</title>
     <link rel="stylesheet" href="style.css">
     <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">
</head>
<body>
  <section class="header">
    <nav>
      <a href="Home.html"><img src="images/logo.png"></a>
      <div class="nav-links" id="navLinks">
        <i class="fa-sharp fa-solid fa-xmark" onclick="hideMenu()"></i>
        <ul> 
          <li><a href="Home.html">HOME</a></li>
          <li><a href="Courses.html">COURSES</a></li>
          <li><a href="MyAccount.html">MY ACCOUNT</a></li>
          <li><a href="ContactUs.html">CONTACT US</a></li>
          <li><a href="Cart.html"><img src="images/cart.png" width="30px" height="30px" ></a></li>
        </ul>
      </div>
      <i class="fa-solid fa-bars" onclick="showMenu()"></i>
    </nav>

<!----------  Cart Item Details ----------->
<div class="small-container cart-page">

<div class="Product-section">
  <table>
    <tr>
        <th>Product</th>
        <th>Quantity</th>
        <th>Subtotal</th>
    </tr>

    
    <tr>
        <td>
          <div class="cart-info">
            <img src="images/Course1.jpg" >
            <div>
                <p>Dental Course 1</p>
                <small> Price: $120.00</small>
                <br>
                <a href="">Remove</a>
            </div>
          </div>
        </td>
        <td><input type="number" value="1"></td>
        <td>$50.00</td>
    </tr>


    <tr>
      <td>
        <div class="cart-info">
          <img src="images/Course1.jpg" >
          <div>
              <p>Dental Course 1</p>
              <small> Price: $120.00</small>
              <br>
              <a href="">Remove</a>
          </div>
        </div>
      </td>
      <td><input type="number" value="1"></td>
      <td>$50.00</td>
  </tr>


  <tr>
    <td>
      <div class="cart-info">
        <img src="images/Course1.jpg" >
        <div>
            <p>Dental Course 1</p>
            <small> Price: $120.00</small>
            <br>
            <a href="">Remove</a>
        </div>
      </div>
    </td>
    <td><input type="number" value="1"></td>
    <td>$50.00</td>
  </tr>

  </table>
</div>

  <div class="total-price">

            <table>
                  <tr>
                    <td>Subtotal</td>
                    <td>$200.00</td>
                  </tr>
                  <tr>
                    <td>Tax</td>
                    <td>$100.00</td>
                  </tr>
                  <tr>
                    <td>Total</td>
                    <td>$300.00</td>
                  </tr>
            </table>


  </div>



</div>


   </section>
<!---------- Footer ---------->
<section class="footer">
  <a href="AboutUs.html" class="aboutus-btn">About Us</a>

</section>


<!---------JavaScript for Toggle Menu-------->

<script>
      var navLinks = document.getElementById("navLinks");
      
      function showMenu(){
        navLinks.style.right = "0";
      }
      function hideMenu(){
        navLinks.style.right = "-200px";
      }
   </script>
   
  </body>
</html>
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="with=deivce-width, initial-
    scale=1.0">
     <title>Dental Course Website</title>
     <link rel="stylesheet" href="style.css">
     <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">
</head>
<body>
  <section class="header">
    <nav>
      <a href="Home.html"><img src="images/logo.png"></a>
      <div class="nav-links" id="navLinks">
        <i class="fa-sharp fa-solid fa-xmark" onclick="hideMenu()"></i>
        <ul> 
          <li><a href="Home.html">HOME</a></li>
          <li><a href="Courses.html">COURSES</a></li>
          <li><a href="MyAccount.html">MY ACCOUNT</a></li>
          <li><a href="ContactUs.html">CONTACT US</a></li>
          <li><a href="Cart.html"><img src="images/cart.png" width="30px" height="30px" ></a></li>
        </ul>
      </div>
      <i class="fa-solid fa-bars" onclick="showMenu()"></i>
    </nav>
   </section>

<!---------- Footer ---------->
<section class="footer">
  <a href="" class="aboutus-btn">About Us</a>

</section>


<!---------JavaScript for Toggle Menu-------->

<script>
      var navLinks = document.getElementById("navLinks");
      
      function showMenu(){
        navLinks.style.right = "0";
      }
      function hideMenu(){
        navLinks.style.right = "-200px";
      }
   </script>
   
  </body>
</html>
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="with=deivce-width, initial-
    scale=1.0">
     <title>Dental Course Website</title>
     <link rel="stylesheet" href="style.css">
     <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">
</head>
<body>
  <section class="header">
    <nav>
      <div class="logo">
        <img src="images/logo.png" >
      </div>
      <div class="nav-links" id="navLinks">
        <i class="fa-sharp fa-solid fa-xmark" onclick="hideMenu()"></i>
        <ul> 
          <li><a href="Home.html">HOME</a></li>
          <li><a href="Courses.html">COURSES</a></li>
          <li><a href="MyAccount.html">MY ACCOUNT</a></li>
          <li><a href="ContactUs.html">CONTACT US</a></li>
          <li><a href="Cart.html"><img src="images/cart.png" width="30px" height="30px" ></a></li>
        </ul>
      </div>
      <i class="fa-solid fa-bars" onclick="showMenu()"></i>
    </nav>
                                                                      <div class="container">
      <h2>Our Courses</h2>
      <div class="price-row">
        <div class="price-col">
          <p>8 Hour Infection Control Training</p>
          <h4>$299.99</h4>
          <ul>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
          </ul>
          <button>Add To Cart</button>
        </div>
        <div class="price-col">
          <p>4 Hour Infection Control Training</p>
          <h4>$59.99</h4>
          <ul>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
          </ul>
          <button>Add To Cart</button>
        </div>
        <div class="price-col">
          <p>2 Hour Infection Control Training</p>
          <h4>$29.99</h4>
          <ul>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
          </ul>
          <button>Add To Cart</button>
        </div>
      </div>
      
                                                        <div class="container2">
              <div class="price-row">
        <div class="price-col">
          <p>Sexual Harrasment Course</p>
          <h4>$14.99</h4>
          <ul>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
          </ul>
          <button>Add To Cart</button>
        </div>
        <div class="price-col">
          <p>Responsibilites and Requirements of Prescribing Schedule II Opioids</p>
          <h4>$14.99</h4>
          <ul>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
          </ul>
          <button>Add To Cart</button>
        </div>
        <div class="price-col">
          <p>Dental Practice Act</p>
          <h4>$14.99</h4>
          <ul>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
            <li>1 Website</li>
          </ul>
          <button>Add To Cart</button>
        </div>
      </div>
      <div class="price-col">
        <p>Sexual Harrasment Course</p>
        <h4>$14.99</h4>
        <ul>
          <li>1 Website</li>
          <li>1 Website</li>
          <li>1 Website</li>
          <li>1 Website</li>
          <li>1 Website</li>
        </ul>
        <button>Add To Cart</button>
      </div>
      <div class="price-col">
        <p>Responsibilites and Requirements of Prescribing Schedule II Opioids</p>
        <h4>$14.99</h4>
        <ul>
          <li>1 Website</li>
          <li>1 Website</li>
          <li>1 Website</li>
          <li>1 Website</li>
          <li>1 Website</li>
        </ul>
        <button>Add To Cart</button>
      </div>
      <div class="price-col">
        <p>Dental Practice Act</p>
        <h4>$14.99</h4>
        <ul>
          <li>1 Website</li>
          <li>1 Website</li>
          <li>1 Website</li>
          <li>1 Website</li>
          <li>1 Website</li>
        </ul>
        <button>Add To Cart</button>
      </div>
    </div>
   </section>

<!---------- Footer ---------->
<section class="footer">
  <a href="AboutUs.html" class="aboutus-btn">About Us</a>

</section>


<!---------JavaScript for Toggle Menu-------->

<script>
      var navLinks = document.getElementById("navLinks");
      
      function showMenu(){
        navLinks.style.right = "0";
      }
      function hideMenu(){
        navLinks.style.right = "-200px";
      }
   </script>
   
  </body>
</html>
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="with=deivce-width, initial-
    scale=1.0">
     <title>Dental Course Website</title>
     <link rel="stylesheet" href="style.css">
     <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">
</head>
<body>
  <section class="header">
    <nav>
      <div class="logo">
        <img src="images/logo.png" >
      </div>
      <div class="nav-links" id="navLinks">
        <i class="fa-sharp fa-solid fa-xmark" onclick="hideMenu()"></i>
        <ul> 
          <li><a href="Home.html">HOME</a></li>
          <li><a href="Courses.html">COURSES</a></li>
          <li><a href="MyAccount.html">MY ACCOUNT</a></li>
          <li><a href="ContactUs.html">CONTACT US</a></li>
          <li><a href="Cart.html"><img src="images/cart.png" width="30px" height="30px" ></a></li>
        </ul>
      </div>
      <i class="fa-solid fa-bars" onclick="showMenu()"></i>
    </nav>
<!---------- Sign Up / Sign In Form Box ---------->
    <div class="form-box">
      <h1 id="title">Register</h1>
      <form>
        <div class="input-group">

          <div class="input-field" id="nameField">
            <i class="fa-solid fa-user"></i>
            <input type="text" placeholder="Full Name" id="contact -name" onkeyup="validatename()">
            <span id="name-error"></span>
          </div>

          <div class="input-field" id="phoneField">
            <i class="fa-solid fa-lock"></i>
            <input type="tel" placeholder="Phone No.">
            <span id="phone-error"></span>
          </div>
    
          <div class="input-field">
            <i class="fa-solid fa-envelope"></i>
            <input type="email" placeholder="Email">
            <span id="email-error"></span>
          </div>
    
          <div class="input-field">
            <i class="fa-solid fa-lock"></i>
            <input type="password" placeholder="Password">
            <span id="password-error"></span>
          </div>
          <p><a href="#">Forgot password?</a></p>
        </div>
        <div class="btn-field">
          <button type="button" id="signupBtn">Register</button>
          <span id="Register-error"></span>
          <button type="button" id="signinBtn"class="disable">Log in</button>
          <span id="Login-error"></span>
        </div>
      </form>
    
    </div>
<script>

let signupBtn = document.getElementById("signupBtn");
let signinBtn = document.getElementById("signinBtn");
let nameField = document.getElementById("nameField");
let phoneField = document.getElementById("phoneField")
let title = document.getElementById("title");


signinBtn.onclick = function(){
    nameField.style.maxHeight = "0";
    phoneField.style.maxHeight ="0";
    title.innerHTML = "Log In";
    signupBtn.classList.add("disable");
    signinBtn.classList.remove("disable");

}

signupBtn.onclick = function(){
    nameField.style.maxHeight = "60px";
    phoneField.style.maxHeight = "60px"
    title.innerHTML = "Register";
    signupBtn.classList.remove("disable");
    signinBtn.classList.add("disable");

}
</script>
</section>



<!---------JavaScript for Toggle Menu-------->

<script>
      var navLinks = document.getElementById("navLinks");
      
      function showMenu(){
        navLinks.style.right = "0";
      }
      function hideMenu(){
        navLinks.style.right = "-200px";
      }
   </script>
<script src="script.js">
validatename.call


</script>
  </body>
</html>    
    
    














*{
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
}
/*------- Home --------*/
.header{
  min-height: 100vh;
  width: 100%;
  background-image: linear-gradient(rgba(4,9,30,0.7),rgba(4, 9, 30, 0.7)), url(Images/Dentalbanner.png);
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
  background: #46aece;
  display: block;
  margin: auto;
  transition: 0.5s;
}
.nav-links ul li:hover::after{
  width: 100%;
}
.text-box{
  width: 90%;
  color: #8eb7ec;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
  text-align: center;
}
.text-box h1{
    font-size: 62px;
}
.text-box p{
  margin: 10px 0 40px;
  font-size: 16px;
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
}
.hero-btn:hover {
  border: 1px solid #46aece;
  background: #46aece;
  transition: 1s;
}
.course1-btn{
  display: inline-block;
  text-decoration: none;
  color: #000000;
  border: 1px solid #000000;
  padding: 12px 34px;
  font-size: 13px;
  background: transparent;
  position: relative;
  cursor: pointer;
}
.course1-btn:hover {
  border: 1px solid #46aece;
  background: #46aece;
  transition: 1s;
}
.course2-btn{
  display: inline-block;
  text-decoration: none;
  color: #000000;
  border: 1px solid #000000;
  padding: 12px 34px;
  font-size: 13px;
  background: transparent;
  position: relative;
  cursor: pointer;
}
.course2-btn:hover {
  border: 1px solid #46aece;
  background: #46aece;
  transition: 1s;
}
.course3-btn{
  display: inline-block;
  text-decoration: none;
  color: #000000;
  border: 1px solid #000000;
  padding: 12px 34px;
  font-size: 13px;
  background: transparent;
  position: relative;
  cursor: pointer;
}
.course3-btn:hover {
  border: 1px solid #46aece;
  background: #46aece;
  transition: 1s;
}
.aboutus-btn{
  display: inline-block;
  text-decoration: none;
  color: #000000;
  padding: 12px 34px;
  font-size: 13px;
  position: relative;
  cursor: pointer;
}

.footer{
  width: 100%;
  text-align: center;
}


nav .fa-solid{
  display: none;

}
@media(max-width: 700px) {
  .text-box h1{
    font-size: 20px;
  }
  .nav-links ul li{
    display: block;
  }
  .nav-links{
    position: absolute;
    background: #46aece;
    height: 100vh;
    width: 200px;
    top: 0;
    right: -200px;
    text-align: left;
    z-index: 2;
  }
  nav .fa-solid{
    display: block;
    color: #fff;
    margin: 10px;
    font-size: 22px;
    cursor: pointer;
  }
  .nav-links ul{
      padding: 30px;
  }
}

/*------ Course -------*/

.course{ 
  width: 80%;
  margin: auto;
  text-align: center;
  padding-top: 100px;
}
.text-box h1{
  font-size: 36px;
  font-weight: 600;
}
.course col p{
  color: #777;;
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
.course-col{
  flex-basis: 31%;
  background: #c9d9ee;
  border-radius: 10px;
  margin-bottom: 5%;
  padding: 20px 12px;
  box-sizing: border-box;
  transition: 0.5s;
}
.course-col h3{
  text-align: center;
  font-weight: 600;
  margin: 10px 0;
}
.course-col:hover{
  box-shadow: 0 0 20px 0px rgba(0,0,0,0.2);
}
@media(max-width: 700px){
  .row{
    flex-direction: column;
  }
}

/*----------- My Account Page ------------*/
.sub-header{
  min-height: 100vh;
  width: 100%;
  background-image: linear-gradient(rgba(4,9,30,0.7),rgba(4,9,30,0.7)), url(images/MyAccount.jpg);
  background-position: center;
  background-size: cover;
  position: relative;
  color: #000000;
}
.form-box{
  width: 90%;
  max-width: 450px;
  position: absolute;
  top: 5%;
  left: 50%;
  transform: translate(-50%,50%);
  background: #fff;
  padding: 50px 60px 70px;
  text-align: center;
}
.form-box h1{
  font-size: 30px;
  margin-bottom: 60px;
  color: #8eb7ec;
  position: relative;
}
.form-box h1::after{
  content: '';
  width: 30px;
  height: 4px;
  border-radius: 3px;
  background: #8eb7ec;
  position: absolute;
  bottom: -12px;
  left: 50%;
  transform: translateX(-50%);
}



.input-field{
  background:#eaeaea;
  margin: 15px 0;
  border-radius: 3px;
  display: flex;
  align-items: center;
  max-height: 65px;
  transition: max-height 0.5s;
  overflow: hidden;
}
input{
  width: 100%;
  background: transparent;
  border: 0;
  outline: 0;
  padding: 18px 15px;
}
.input-field i{
  margin-left: 15px;
  color: #999;
}
form p{
  text-align: left;
  font-size: 13px;

}
form p a{
  text-decoration: none;
  color: #8eb7ec;
}
.btn-field{
  width: 100%;
  display: flex;
  justify-content: space-between;
}
.btn-field button{
  flex-basis: 48%;
  background: #8eb7ec;
  color: #fff;
  height: 40px;
  border-radius: 20px;
  border: 0;
  outline: 0;
  cursor: pointer;
  transition: background 1s;
}

.btn-field button.disable{
  background: #eaeaea;
  color: #555;
}


/*----- Validation Form For My Account Page------*/

.input-group span{
  font-size: 14px;
  color: red;

}

.btn-field span{
  font-size: 14px;
  color: red;
}


/*------- Courses Page -------*/
.container h2{
  color: #fff;
  font-size: 32px;
  padding: 50px 0;
  text-align: center;
}
.price-row{
  width: 90%;
  max-width: 1100px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  grid-gap: 25px;
}
.price-col{
  background: #1f283b;
  padding: 10% 15%;
  border-radius: 10px;
  color: #fff;
  text-align: center;
}


.price-col p{
  font-size: 22px;
}

.price-col h4{
  font-size: 44px;
  margin: 20px 0 40px;
  font-weight: 500;
}

.price-col h4 span{
  font-size: 16px;
}

.price-col ul{
  text-align: left;
  margin: 20px 0;
  color: #ddd;
  list-style: none;
}
.price-col ul li{
  margin: 15px 0;
}
.price-col ul li::before{
  content: '\2022';
  color: #46aece;
  font-weight: bold;
  margin-right: 8px;
}
.price-col button{
  width: 100%;
  padding: 14px 0;
  background: transparent;
  color: #fff;
  font-size: 15px;
  border: 1px solid #46aece;
  border-radius: 6px;
  margin-top: 30px;
  cursor: pointer;
  transition: background 0.5s;
}

.price-col button:hover{
  background: #46aece;
}



/*----- Cart Items --------*/



.cart-page{
  margin: 80px auto;

}
.Product-section table{
  width: 80%;
  border-collapse: collapse;
  margin: 0 auto;
  background-color: #8eb7ec;
} 
.cart-info{
  display: flex;
  flex-wrap: wrap;
  
}
th{
  text-align: left;
  padding: 5px;
  color: #fff;
  background: #46aece;
  font-weight: normal;
}
td{
  padding: 10px 5px;
}
td input{
  width: 40px;
  height: 30px;
  padding: 5px;
}
td a{
  color: #46aece;
  font-size: 12px;
}

td img{
  width: 80px;
  height: 80px;
  margin-right: 10px;
}
.total-price{
  display: flex;
  justify-content: flex-end;
}

.total-price table{
  margin: 0 auto;
  margin-left: 68.5%;
  border-collapse: collapse;
  background-color: #8eb7ec;
  border-top: 3px solid #46aece;
  width: 100%;
  max-width: 400px;
}

td:last-child{
  text-align: right;
}
th:last-child{
  text-align: right;
}
