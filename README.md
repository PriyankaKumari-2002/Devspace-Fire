# Devspace-Fire
A one-stop shop platform to help women all across the globe to connect with other women to build and flourish business and start-ups.
The project is a website where women entrepreneurs can connect with employees and vice-versa ,calculate EMI for the loans which they plan to take.
WORK Completed till now
HTML PART:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Our Vision"</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>
<div class="container">
    <div class="aim">
        <hl><span>Our Aim</span></hl>
        <p>Our vision-Your success</p>
    </div>
    <div>
        <div class="row">
            <div class="col-md-4">
                <div class="minimise_gap">
                    <i class="fa fa-handshake-o" aria-hidden="true"></i>
                    <h3><span>Bridge The Gap</span></h3>
                    <p>To bridge the gap between female entrepreneurs and employees.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="minimise_gap">
                    <i class="fa fa-users" aria-hidden="true"></i>
                    <h3><span>One platform-Many services</span></h3>
                    <p>To provide a platform to women to calculate the EMI of loans and  contacts to propel their businesses to great heights.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="minimise_gap">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <h3><span>Tales of Motivation</span></h3>
                    <p>Motivational stories to guide and encourage you to push your boundaries and test your limits.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="minimise_gap">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <h3><span>Amazing Articles</span></h3>
                    <p>To help you understand teh basics of bank and business.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="minimise_gap">
                    <i class="fa fa-trophy" aria-hidden="true"></i>
                    <h3><span>Success</span></h3>
                    <p>All in all, we want all the sisters to brainstorm,start and lead businesses and work towards the goal of collective success. </p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="minimise_gap">
                    <i class="fa fa-briefcase" aria-hidden="true"></i>
                    <h3><span>So,what are you waiting for?</span></h3>
                    <p>Click on the link below to flourish your business and be at the pinnacle of success.</p>
                    <a href="#"><i class="fa fa-arrow-circle-right" aria-hidden="true"></i></a>
                </div>
            </div>
        </div>
    </div>
</div>
<div class="contact-form">
    <div class="first-container">
     <div class="info-container">
       <div> 
         <h3>Address</h3>
         <p>VELLORE INSTITUTE OF TECHNOLOGY</p>
       </div>
       <div> 
         <h3>Lets Talk</h3>
         <p>3565869709</p>
       </div>
       <div> 
         <h3>General Support</h3>
         <p>contact@example.com</p>
       </div>
     </div>
    </div>
    <div class="second-container">
      <h2><b> CONTACT US </b></h2>
      <form>
        <div class="form-group">
          <label for="name-input"><b>  TELL US YOUR NAME*  </b></label>
          <input id="name-input" type="text" placeholder="First name" required="">
          <input type="text" placeholder="Last name" required="">
        </div>
        <div class="form-group">
          <label for="email-input"><b>   ENTER YOUR EMAIL  </b></label>
          <input id="email-input" type="text" placeholder="Eg. example@gmail.com" required="">
        </div>
        <div class="form-group">
          <label for="phone-input"><b>  ENTER YOUR PHONE NUMBER  </b></label>
          <input id="phone-input" type="text" placeholder="Eg. _1800 000000" required="">
        </div>
        <div class="form-group">
          <label for="message-textarea"><b>  MESSAGE  </b></label>
          <input class="textarea" id="message-textarea" placeholder="Write us a message"></input>
        </div>
        <a class="btn">Send message</button>
      </form>
    </div>
</body>
</html>

CSS PART:
@import url()
*
{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  outline: none;
  font-family: "Poppins", sans-serif;
}

body {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  background: #2F4F4F;
}
.contact-form{
  width:80vw;
  display:flex;
  justify-content:space-between;
  background:#fff;
  margin:30px 0;
}
.contact-form > * {
  width:50%;
}
.contact-form .first-container{
  background:linear-gradient(45deg, rgba(0,0,0,0.8), rgba(0,0,0,0.8)), url(https://wallpaperaccess.com/full/722327.jpg) center center/cover no-repeat;
  display:flex;
  justify-content:center;
  align-items:center;
}
.contact-form .first-container .info-container div{
  margin:24px 0;
}
.contact-form .first-container .info-container div h3{
  color:#fff;
  font-size:18px;
  font-weight: 400;
  line-height: 1.2;
  padding-bottom: 10px;
}
.contact-form .first-container .info-container div p{
  font-size: 16px;
  line-height: 1.6;
  color:#DCDCDC;
}
.contact-form .first-container .info-container div:first-of-type p{
  max-width:260px;
  color:#DCDCDC;
}
.contact-form .second-container{
  padding:30px;
}
.contact-form .second-container form{
  display:flex;
  flex-direction: column;
}
.contact-form .second-container h2{
  font-size:30px;
  font-weight:400;
  color:#333;
  line-height: 1.2;
  text-align: center;
  margin-bottom:20px;
} 
.contact-form .second-container form .form-group{
  margin-bottom:10px;
}
.contact-form .second-container form .form-group *{
   min-height: 55px;
   border:1px solid #e6e6e6;
   padding:0 20px;
}
.contact-form .second-container form .form-group label{
  display:flex;
  align-items:center;
  width:100%;
  border:1px solid #e6e6e6;
  font-size:16px;
  color:#333;
  text-transform: uppercase;
  margin-top:-1px;
}
.contact-form .second-container form .form-group:first-of-type input{
  width:50.1%;
  margin-right:-5px;
}
.contact-form .second-container form .form-group input{
  width:100%;
  font-size:15px;
  margin-top:-2px;
}
.contact-form .second-container form .form-group input::placeholder,
.contact-form .second-container form .form-group .textarea::placeholder{
  color:#999;
}
.contact-form .second-container form .form-group .textarea{
  width:100%;
  min-height: 80px;
  resize:none;
  padding:10px 20px;
  margin-top:-1px;
}
.contact-form .second-container form .btn{
  width:200px;
  height:50px;
  background:#2E2E2E;
  color:#fff;
  font-size:17px;
  font-weight: 600;
  text-transform: uppercase;
  border:0;
  position:relative;
  left:calc(50% - 100px);
  cursor:pointer;
}
.contact-form .second-container form .btn:hover{
  background:#333;
}
@media screen and (max-width:800px){
  .contact-form{
    width:90vw;
  }
}
@media screen and (max-width:700px){
  .contact-form{
    flex-direction: column-reverse;
  }
  .contact-form > *{
    width:100%;
  }
  .contact-form .first-container{
    padding:40px 0;
  }
}
*
{
    margin: 0;
    padding: 0;
}
body
{
    background: rgb(155, 55, 117) !important;
    color: #fff !important;
}
.aim
{
    font-size: 38px !important;
    margin-top: 50px;
    margin-bottom: 30px;
}
.minimise_gap
{
    box-shadow: 0 0 8px 0 #ffb109;
    padding: 20px;
    position: relative;
}
.fa
{
    font-size: 40px !important;
    margin-bottom: 20px;
    background: linear-gradient(to right, #ff105f,#ffad06);
    -webkit-background-clip: text;
    color: transparent;
}
p
{
    text-align: justify;
}
span
{
    background: linear-gradient(to right, #ff105f,#ffad06);
    -webkit-background-clip: text;
    color: transparent;
}
