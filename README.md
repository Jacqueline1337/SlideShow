<!DOCTYPE html>
<html>
<head>
<style>
body {font-family: "Lato", graduate;}


/* Style the tab */
div.tab {
    overflow: hidden;
    border: 1px solid #ccc;
    background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
div.tab button {
    background-color: #f1faee;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 14px 16px;
    transition: 0.3s;
    font-size: 17px;
}


/* Change background color of buttons on hover */
div.tab button:hover {
    background-color: #a8dadc;
   
}

/* Create an active/current tablink class */
div.tab button.active {
    background-color: #83BAB0;
}

/* Style the tab content */
.tabcontent {
    display: none;
    padding: 6px 12px;
    border: 1px solid #ccc;
    border-top: none;
}

/* Style the close button */
.topright {
    float: right;
    cursor: pointer;
    font-size: 20px;
}

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing:border-box}
body {font-family: Verdana,sans-serif;}
.mySlides {display:none}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
  background-color: #BF8B85;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 13px;
  width: 13px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}


/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 13px;
  width: 13px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>
</head>


</style>
</head>
<body>


<div class="tab">
  <button class="tablinks" onclick="openDetail(event, 'College Hacks')" id="defaultOpen">College Hacks</button>
  <button class="tablinks" onclick="openDetail(event, 'Study Tips')">Study Tips</button>
  <button class="tablinks" onclick="openDetail(event, 'Scholarships')">Scholarships</button>
   <button class="tablinks" onclick="openDetail(event, 'Studying Abroad')" id="defaultOpen">Studying Abroad</button>
   <button class="tablinks" onclick="openDetail(event, 'Student Discounts')" id="defaultOpen">Student Discounts</button>
   <button class="tablinks" onclick="openDetail(event, 'Road to Success')" id="defaultOpen">Road to Success</button>
</div>

<div class="slideshow-container" img align="middle">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="http://i67.tinypic.com/w6uwhx.jpg" border="0" alt="Image and video hosting by TinyPic"></a>
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="http://preview.ibb.co/b33PPv/IMG_2901.jpg" alt="IMG_2901" border="0"></a><br /><a target='_blank' href='http://imgbb.com/'></a><br />
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="http://preview.ibb.co/caocBa/1728697_Anthony_D_Williams_Quote_Knowledge_comes_from_learning_Wisdom.jpg" alt="1728697_Anthony_D_Williams_Quote_Knowledge_comes_from_learning_Wisdom" border="0"></a><br /><a target='_blank' href='http://imgbb.com/'></a><br />
  <div class="text"></div>
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    for (i = 0; i < slides.length; i++) {
       slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex> slides.length) {slideIndex = 1}    
    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active";
    setTimeout(showSlides, 5000); 
}
</script>

<div style="background-color:teal;color:white;padding:20px:"id="College Hacks" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3> College Hacks</h3>
  <p style="font-family:graduate;">Shortcuts are everywhere to simplify the difficulty of tasks, which is greatly needed for a college student in an environment where everything appears to be intricate.</p>
</div>

<div style="background-color:teal;color:white;padding:20px:"id="Study Tips" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3> Study Tips</h3>
  <p style="font-family:graduate;">One key to success in college is intertwined with your studying habits, since your grade primarily comes from the assessments you take in class. It is important you find the studying method which is best for you.</p> 
</div>

<div style="background-color:teal;color:white;padding:20px:"id="Scholarships" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3> Scholarships</h3>
  <p style="font-family:graduate;">Who doesn't want a free education? Scholarships are a great way to obtain financial assistance for tuition and supplies.</p>
</div>

<div style="background-color:teal;color:white;padding:20px:"id="Studying Abroad" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3> Studying Abroad</h3>
  <p style="font-family:graduate;">Culture comes into play when studying outside the borders, which enables a lot 
  of opportunities for a college student, not only fulfilling their education, but their interests and hobbies as well.</p>
</div>

<div style="background-color:teal;color:white;padding:20px:"id="Student Discounts" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3> Student Discounts</h3>
  <p style="font-family:graduate;">As you may know, college is the time when lack of money becomes quite persistent, so saving up becomes quite 
  essential. Fortunately, there are places such as stores and cafes which provide students with discounts.</p>
</div>

<div style="background-color:teal;color:white;padding:20px:"id="Road to Success" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3> Road to Success</h3>
   <p style="font-family:graduate;">To pursue a life of success and prosperity relies heavily on choices that you make as a student. Getting your habits and motivations in check are prime factors in planning out your future and acquiring it later on.</p>
</div>
<div style="background-color:#82B2B1;color:white;padding:20px;">
  <h2>About Us</h2>
  <p style="font-family:graduate;">Hello! We are 3 young girls from a program named Girls Who Code! Here in GWC we learn the basics of JavaScript, C++, HTML, Python, etc. During our final 2 weeks we come together and start brainstorming ideas for our final project. We got placed in groups depending on what we wanted from the options available. Finally we were put into groups and started to work on our final projects. Which has brought us to the creation of this website! While planning what we were going to do for our website we all emphasized the desire to help high school students or anyone interested towards attending college. </p> <p>Creators: Jacqueline Marchan, Julia Devine, Vanesa Marar</p>
</div> 

<script>
function openDetail(evt, detailName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(detailName).style.display = "block";
    evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
<div id="google_translate_element"></div>

<script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({pageLanguage: 'en'}, 'google_translate_element');
}
</script>

<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
</body>
</html> 

