h# Login-box
/*Login page with place to input username and password and also registering to the account*/
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>DanFlex</title>
    <link rel="stylesheet" href="2.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <script src="2.js"></script>
</head>
<body>
 <div class="container">
  <section>
    <div class="rt-container">
      <div class="col-rt">
        <div class="script-content">
          <form class="codehim-form">
            <div class="form-title">
              <div class="user-icon gr gb">
                <i class="fa fa-user"></i> 
              </div>  
              <h2>LOGIN</h2>
            </div>
            <label for="email"><i class="fa fa-envelope"></i> Email:</label>
            <input type="email" id="email" class="cm-input" placeholder="Enter your email Address">
            <label for="pass"><i class="fa fa-lock"></i> Password:</label> <!-- Corrected closing tag -->
            <input id="pass" type="password" class="cm-input" placeholder="Enter your Password">
            <button type="submit" class="btn-login gr gb">Login</button>
          </form> 
        </div>
      </div> 
    </div>
  </section>
</div>
  <div class="cont">
  <section>
    <div class="item">
      <div class="layer">
        <h3>Description</h3>
        <p>
          A good website possesses several key features that contribute to its effectiveness and appeal. Firstly, it should have a user-friendly interface, ensuring easy navigation and intuitive layout, allowing visitors to find information effortlessly. Secondly, it must be responsive, adapting seamlessly to various devices and screen sizes, enhancing accessibility and user experience.
        </p>
        <span><i class="fas fa-lightbulb"></i></span>
      </div>
      <h4>Card One</h4>
    </div>
    <div class="item">
      <div class="layer">
        <h3>Settings</h3>
        <p>
          A good website possesses several key features that contribute to its effectiveness and appeal. Firstly, it should have a user-friendly interface, ensuring easy navigation and intuitive layout, allowing visitors to find information effortlessly. Secondly, it must be responsive, adapting seamlessly to various devices and screen sizes, enhancing accessibility and user experience.
        </p>
        <span><i class="fas fa-cogs"></i></span>
      </div>
      <h4>Card Two</h4>
    </div>
    <div class="item">
      <div class="layer">
        <h3>Data Analysis</h3>
        <p>
          A good website possesses several key features that contribute to its effectiveness and appeal. Firstly, it should have a user-friendly interface, ensuring easy navigation and intuitive layout, allowing visitors to find information effortlessly. Secondly, it must be responsive, adapting seamlessly to various devices and screen sizes, enhancing accessibility and user experience.
        </p>
        <span><i class="fas fa-arrow-up-right"></i></span>
      </div>
      <h4>Card Three</h4>
    </div>
  </section>
</div>
   <div>
  <section>
     <div class="container">
     <button onclick="toggleMenu()">TABS</button>
     <ul id="menu">
        <li><a href="">Home</a></li>
        <li><a href="">About Us</a></li>
        <li><a href="">Our services</a></li>
        <li><a href="">Contact Us</a></li>
     </ul>
     <section>
     <div class="container2">
      <div style="background-image:url('1.jpg');"></div>
      <div style="background-image:url('2.jpg');"></div>
      <div style="background-image:url('3.jpg');"></div>
      <div style="background-image:url('4.jpg');"></div>
      <div style="background-image:url('5.jpg');"></div>
      <div style="background-image:url('6.jpg');"></div>
      <div style="background-image:url('7.jpg');"></div>
  </div>
  </section>
   </div>
     <div class="image3">
        <p class="p1">
          WRITE WEB CONTENTS HERE.
        </p>
     </div>
     <div class="logo">
        <img src="logo1.png" alt="logo1.png" class="logo1">
        <h6 class="logoname">DANFLEX</h6>
        <p class="logodescription">"DANFLEX pioneers in software engineering, crafting innovative solutions for modern challenges. 
        Our vision is to revolutionize technology through relentless innovation and creativity. 
        With a mission to empower businesses through cutting-edge software, we strive to exceed expectations and drive digital transformation.
        Our motto: 'Engineering Tomorrow, Today.' 
        Join us as we shape the future of technology."</p>
     </div>
     <footer class="footer">
        <div class="container3">
           <div class="row">
             <div class="footer-col">
                 <h5>Company</h5>
                 <ul>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Our services</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Affiliate Programs</a></li>
                 </ul>
              </div>
               <div class="footer-col">
                 <h5>Get Help</h5>
                 <ul>
                    <li><a href="#">FAQ</a></li>
                    <li><a href="#">Shipping</a></li>
                    <li><a href="#">Returns</a></li>
                    <li><a href="#">Order Status</a></li>
                    <li><a href="#">Payment Options</a></li>
                 </ul>
              </div>
               <div class="footer-col">
                 <h5>Online shop</h5>
                 <ul>
                    <li><a href="#">Watches</a></li>
                    <li><a href="#">Bags</a></li>
                    <li><a href="#">Men Clothes</a></li>
                    <li><a href="#">Women Clothes</a></li>
                 </ul>
              </div>
               <div class="footer-col">
                 <h5>Follow Us</h5>
                 <div class="social-links">
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-youtube"></i></a>
                 </div>
              </div>
           </div>
           </div>
           </div>
           </div>
           </div>
        </div>
     </footer>
</body>
</html>
//css code 
body {
   background-image: url('11.jpg');
   background-repeat: no-repeat;
   background-size: cover; /* Ensure the background image covers the entire viewport */
   width: 100%;
   height: 100%;
   line-height: 1.5;
   font-family: 'Poppins', sans-serif;
}
*{
   margin: 0;
   padding: 0;
}
section{
   display: flex;
   width: 100%;
   height: 100vh;
   justify-content: left;
   align-items: left;
   flex-flow: column;
}
button{
   background: linear-gradient(
    90deg,
    rgba(255, 215, 0, 1) 0%,
    rgba(252, 196, 0, 1) 55%,
    rgba(255, 215, 0, 1) 100%
);
   color: black;
   transition: box-shadow 0.3s ease;
   box-shadow: 0 0 5px gold, 0 0 25px gold;
   font-size: 18px;
   padding: 5px 20px;
   border-radius: 10px;
   border: none;
   cursor: pointer;
   margin-top: 40px;
   left: 1cm;
   width: 100px;
}
.button:hover{
    box-shadow: 0 0 10px gold, 0 0 50px gold, 0 0 100px gold;
}
ul#menu{
   list-style: none;
   width: 200px;
   margin-top: 20px;
}
ul#menu li{
   margin: 5px 0;
   opacity: 0;
   transition: 0.5s all cubic-bezier(0.31,-0.105,0.43,1.4);
}
ul#menu li:nth-child(even){
   transform: translateX(50px);
}
ul#menu li:nth-child(odd){
   transform: translateX(-50px);
}
ul#menu li:nth-child(1){
   transition-delay: 0.1s;
}
ul#menu li:nth-child(2){
   transition-delay: 0.2s;
}
ul#menu li:nth-child(3){
   transition-delay: 0.3s;
}
ul#menu li:nth-child(4){
   transition-delay: 0.4s;
}
ul#menu.active li{
   opacity: 1;
   transform: translateX(0px);
}
ul#menu li a{
   background-color: #2d2f3b;
   display: block;
   padding: 20px 20px;
   font-weight: 500;
   color: white;
   text-decoration: none;
   border-radius: 7px;
   align-content: center;
}
.container {
  width: 100%;
  margin-top: -5px;
  margin-left: 0.2cm;
  margin-right: 0.2cm;
  left: 0;
  position: absolute;
  align-self: right;
  top: 0;
}
.codehim-form {
  max-width: 400px;
  min-height: 400px;
  box-sizing: border-box;
  background: rgba(255, 255, 255, 0.6);
  box-shadow: 4px 2px 16px rgba(0, 0, 0, 0.4);
  border-radius: 8px;
  margin: 150px auto 0 auto;
  padding: 25px;
  color: #414141;
  margin-top: 45px;
}
.cm-input {
  display: block;
  box-sizing: border-box;
  padding: 10px;
  width: 100%;
  margin: 14px auto;
  border-radius: 20px;
  border: 1px solid #ccc;
}

.cm-input:focus {
  outline: 0;
  border-color: #f9cb81;
}

.cm-input:invalid {
  border-color: #e41b17;
}
.gr.gb {
  background: rgba(255, 215, 0, 1);
  background: linear-gradient(
    90deg,
    rgba(255, 215, 0, 1) 0%,
    rgba(252, 196, 0, 1) 55%,
    rgba(255, 215, 0, 1) 100%);
}
.btn-login {
  display: block;
  width: 100%;
  padding: 10px;
  border: 0;
  color: black;
  border-radius: 20px;
  cursor: pointer;
}

.btn-login:focus {
  outline: 0;
}

.btn-login:hover {
  opacity: 0.8;
  transition: 0.3s;
}

.form-title {
  padding: 12px;
  text-align: center;
  position: relative;
}

.form-title h2 {
  color: rgba(255, 215, 0, 1);
}

.form-title .user-icon {
  position: absolute;
  font-size: 42px;
  color: #fff;
  width: 90px;
  height: 90px;
  line-height: 90px;
  text-align: center;
  border-radius: 50px;
  top: -60px;
  left: -45px;
}
.rt-container {
  position: absolute;
  top: 30px;
  align-self: center;
}
@import url("https://fonts.googleapis.com/css?family=Varela+Round");
@import url("https://use.fontawesome.com/releases/v6.5.1/css/all.css");
p {
  font-size: 9px;
}
h3, h4 {
  margin: 0;
}
.cont {
  display: flex;
  gap: 50px;
  align-items: center;
  justify-content: center;
  font-family: "Varela Round", sans-serif;
  line-height: 1.5em;
  position: absolute;
  top: 10cm;
  left: 3cm;
  transform: translateX(-50%);
}
.item {
  display: flex; 
  flex-direction: column; 
  align-items: center;
  color: #ffd700;
  width: 185px;
  background-color: var(--color);
  box-shadow: rgba(0, 0, 0, 0.12) 0px 1px 2px, rgba(0, 0, 0, 0.12) 0px 2px 4px, rgba(0, 0, 0, 0.12) 0px 4px 8px, rgba(0, 0, 0, 0.12) 0px 8px 16px, rgba(0, 0, 0, 0.12) 0px 16px 32px, rgba(0, 0, 0, 0.12) 0px 32px 64px;
  border-radius: 20px;
  padding: 10px 5px;
  cursor: pointer;
  position: relative;
  transition: all 0.8s cubic-bezier(.25,.4,.45,1.4); 
}
.item:hover {
  flex: 5;
}
.item:nth-child(2) {
  color: grey;
}
.item:nth-child(3) {
  color: #119630;
}
.container2{
  justify-items: center;
  margin-top: 3cm;
  display: flex;
  margin-left: 6cm;
  height: 20rem;
  gap: 1rem;
  position: relative;
  background-position: center;
}
.container2 >div{
  flex:1;
  border-radius: 5rem;
  background-position: center;
  background-repeat: no-repeat;
  background-size: auto 100%;
  transition: all 0.8s cubic-bezier(.25,.4,.45,1.4);
}
.container2 >div:hover {
  flex:3;
  border-radius: 3rem;
}
.p1{
   font-size: 20px;
   color: #ffd700;
   margin:10px 20px;
   position: absolute;
  top: 23cm;
  left: 60%;
  transform: translateX(-50%);
  align-content: right;
}
@import url('https://fonts.googleapis.com/2.css?Family=Poppins:wgnt@300;400;500;600;700&display=swap');
.container3{
    max-width: 1170px;
    margin: auto;
    position: absolute;
    left: 0;
    padding: 35px;
    width: 100%;
    top: 52cm;
}
.row{
   display: flex;
   flex-wrap: wrap;
}
ul{
   list-style: none;
}
.footer{
   padding: 70px 0;
   background-color: black;
}
.footer-col{
   width: 25%;
   padding: 0 15px;
}
.footer-col h5{
   font-size: 18px;
   color: #ff6200;
   text-transform: capitalize;
   margin-bottom: 35px;
   font-weight: 500;
   position: relative;
}
.footer-col h5::before{
   content: "";
   position: absolute;
   left: 5%;
   bottom: 10px;
   background-color: #ffd700;
   height: 2px;
   box-sizing: border-box;
   width: 50px;
   top: 30px;
   padding: 5px;
   border-radius: 2rem;
   background-position: center;
}
.footer-col ul li:not(:last-child){
   margin-bottom: 10px;
}
.footer-col ul li a{
   font-size:16px;
   text-transform: capitalize;
   color: #ffd700;
   text-decoration: none;
   font-weight: 300;
   display: block;
   transition: all 0.3s ease;
}
.footer-col ul li a:hover{
   color: red;
   padding-left: 8px;
}
.footer-col .social-links{
   padding: 0;
   margin: 0;
}
.footer-col .social-links a{
   font-size: 20px;
   background-color: #ff523b;
   text-align: center;
   line-height: 40px;
   width: 40px;
   height: 40px;
   margin: 0 5px;
   color: #fff;
   border-radius: 50%;
   display: inline-block;
   transition: all 0.5s ease;
}
.footer-col .social-links a:hover{
   background-color: #ffd700;
   color: #111;
}
@keyframes animate{
   0%{
       opacity: 0;
       transform: translateY(50px);
   }
   100%{
       opacity: 1;
       transform: translateY(0);
   }
}
/*responsive*/
@media(max-width: 767px){
   .footer-col{
       width: 50%;
       margin-bottom: 30px;
   }
}
@media(max-width: 574px){
   .footer-col{
       width: 100%;
   }
}
.logo{
   background-color: transparent;
   margin-left: 95%;
   top: 0.5cm;
   box-sizing: border-box;
   position: fixed;
   padding: -30px 0px -10px 0px;
   background-color: rgba(255, 255, 255, 0.3);
    border-radius: 30%;
    width: 100px;
    height: 90px;
    position: relative;
    margin-top: -15px;
   
}
.logo1{
   width: 100%;
}
.logoname{
   color: #ffd700;
   font-size: 15px;
   letter-spacing: -1px;
   text-align: center;
}
.logodescription{
   top: 4cm;
   color: #ffd700;
}
//js code
function toggleMenu() {
    var menu = document.getElementById("menu");
    menu.classList.toggle("active");
}
