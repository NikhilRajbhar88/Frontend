<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>SIWS College (Autonomous)</title>
 <style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f9f9f9;
 }
  header {
    background: white;
    display: flex;
    align-items: center;
    padding: 10px 20px;
    border-bottom: 1px solid #ccc;
    flex-wrap: wrap;
 }
  header img {
    height: 80px;
    margin-right: 20px;
 }
  .college-details {
    flex: 1;
 }
  .college-details h1 {
    margin: 0;
    color: indigo;
    font-size: 24px;
 }
  .college-details h3 {
    margin: 0;
    color: indigo;
    font-size: 20px;
    }
  .college-details p {
    margin: 5px 0 0 0;
    font-size: 14px;
    line-height: 1.4;
    color: #333;
  }
  .college-details a {
    color: blue;
    text-decoration: none;
 }
  .college-details a:hover {
    text-decoration: underline;
 }
nav {
  display: flex;
  gap: 20px;
  justify-content: center;
  background: white;
  border-bottom: 1px solid #ccc;
  flex-wrap: wrap;
}
nav a {
  text-decoration: none;
  color: black;
  font-weight: bold;
  padding: 10px;
}
nav a:hover {
  background: #f0f0f0;
  border-radius: 5px;
}
.notification-bar {
   background: orange;
   color: black;
   font-weight: bold;
   overflow: hidden;
   white-space: nowrap;
   height: 30px;
   display: flex;
   align-items: center;
   border-bottom: 1px solid #ccc;
}
.notification-bar span {
  isplay: inline-block;
  padding-left: 100%;
  animation: moveText 10s linear infinite;
}
@keyframes moveText {
   0% {
        transform: translateX(0%);
      }
  100% {
        transform: translateX(-100%);
      }
  }
   
.hero {
  position: relative;
  overflow: hidden;
}
.hero img {
  width: 100%;
  display: block;
  border-radius: 10px;
}
.hero-text {
  position: absolute;
  top: 30%;
  left: 10%;
  color: white;
}
.hero-text p {
  margin: 0;
  font-size: 18px;
}
.hero-text h1 {
  font-size: 36px;
  font-weight: bold;
  margin: 5px 0;
}
.hero-text button {
   margin-top: 10px;
   padding: 10px 20px;
   background: orange;
   border: none;
   color: white;
   font-weight: bold;
   cursor: pointer;
   border-radius: 5px;
}
.programs {
  background: #e7f0fb;
  text-align: center;
  padding: 40px 20px;
}
.programs h2 {
  color: #1a237e;
  margin-bottom: 10px;
}
.programs p {
  color: #333;
  max-width: 600px;
  margin: auto;
  line-height: 1.5;
}
</style>
</head>
<body>

<header>
<img src="logo.png" alt="SIWS College Logo">
 <div class="college-details">
   <h1>SIWS</h1>
    <p>
     <h3> N.R. Swamy College of Commerce & Economics and <br>
      Smt. Thirumalai College of Science (Autonomous) </h3><br>
       NAAC Re-Accredited A Grade with 3.15 CGPA <br>
      College Code 311 | AISHE CODE.C-34030 | Wadala, Mumbai 400031 <br>
      <a href="https://www.siwscollege.edu.in" target="_blank">www.siwscollege.edu.in</a>
    </p>
  </div>
<nav>
  <a href="#">About Us</a>
  <a href="#">Academics</a>
  <a href="#">Admissions</a>
  <a href="#">Amenities</a>
  <a href="#">Student Corner</a>
  <a href="#">Contact Us</a>
  <a href="#">Quicklinks</a>
  </nav>
</header>

<div class="notification-bar">
<span>Admissions Open Now</span>
</div>

<div class="hero">
<img src="college_building.jpg" alt="SIWS College">
<div class="hero-text">
 <p>Empowering Your Future At</p>
   <h1>SIWS College <span style="font-size:16px;">(Autonomous)</span></h1>
    <button>Learn more</button>
   </div>
</div>

<div class="programs">
 <h2>Our Programs, your Future</h2>
  <p>Choose from specialized courses designed to set the foundation for a successful career.</p>
  </div>

</body>
</html>
