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
<head>
<style>
div.Title {
    background-color: teal;
    color: white;
    margin: 20px 0 20px 0;
    padding: 20px;
}
</style>
</head>

<body>

<div class="Title">
<h2 img align="middle"><font size="18">College Knowledge</font>
</div> 
<div style="background-color:#a8dadc;
<div class="logo" img align="middle">
</div>
<div>
<div style="background-color:#a8dadc;
<div class="logo" img align="middle">
<img src="http://image.ibb.co/nc92Uv/Final_Final_Logo.jpg" alt="Final_Final_Logo" border="0"></a><br /><a target='_blank' href='http://imgbb.com/'></a><br />
</div>
</body>
<body>


<div class="tab">
  <button class="tablinks" onclick="openDetail(event, 'College Hacks')" id="defaultOpen">College Hacks</button>
  <button class="tablinks" onclick="openDetail(event, 'Study Tips')">Study Tips</button>
  <button class="tablinks" onclick="openDetail(event, 'Scholarships')">Scholarships</button>
   <button class="tablinks" onclick="openDetail(event, 'Studying Abroad')" id="defaultOpen">Studying Abroad</button>
   <button class="tablinks" onclick="openDetail(event, 'Student Discounts')" id="defaultOpen">Student Discounts</button>
   <button class="tablinks" onclick="openDetail(event, 'Road to Success')" id="defaultOpen">Road to Success</button>
   <button class="tablinks" onclick="openDetail(event, 'The Creators')" id="defaultOpen">The Creators</button>
   <button class="tablinks" onclick="openDetail(event, 'References')" id="defaultOpen">References</button>
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
    <h4> Never Buy a Textbook Again!</h4>
    <p> Here are 10 websites where you can get them for free </p>
  <ul>
  <li style="font-family:graduate;">TextBookNova.com</li>
  <li style="font-family:graduate;">eBookee.org</li>
  <li style="font-family:graduate;">ManyBooks.net</li>
  <li style="font-family:graduate;">FeedUrBrain.com</li>
  <li style="font-family:graduate;">AllenG.ru</li>
  <li style="font-family:graduate;">2020Ok.com</li>
  <li style="font-family:graduate;">FreeTextBooks.com</li>
  <li style="font-family:graduate;">Gutenberg.org</li>
  <li style="font-family:graduate;">Eknigu.com</li>
  <li style="font-family:graduate;">En.Bookfi.org</li>
  </ul>
    <h4> Top 6 Editing Tools for College Students</h4>
  <ul>
  <li style="font-family:graduate;"> Grammarly </li>
  <p style="font-family:graduate;"> Grammarly can spot your usual spelling errors, as well as identify grammar, stylistic, and contextual spelling errors with a detailed explanation to explain your mistake.</p>
  <li style="font-family:graduate;"> ProWritingAid</li>
  <p style="font-family:graduate;"> ProWritingAid will help you improve your writing chops when it comes to clarity, sentence length, phrasing, style, and repetition.
  <li style="font-family:graduate;"> Help.PragTracker </li>
  <p style="font-family:graduate;"> You can have your paper edited by a professional to make sure your paper is 100% plagiarism-free, as well as contact their helpfull staff through their live chat app.</p>
  <li style="font-family:graduate;"> The Hemingway Editor </li>
  <p style="font-family:graduate;"> The Hemingway Editor will help you achieve clarity in your writing by clearing cliches, redundant structures, phrases, adverbs, and more. </p>
  <li style="font-family:graduate;"> Wordcounter </li>
  <p style="font-family:graduate;"> Wordcounter keeps track of how many times you have used every word, and ranks them according to frequency of use so that you don't rely too much on some words. </p>
  <li style="font-family:graduate;"> After the Deadline </li>
  <p style="font-family:graduate;"> After the Deadline is a Grammarly alternative that will also explain why a word is wrong, and provide an appropriate replacement in about 90% of cases </li>
</div>

<div style="background-color:teal;color:white;padding:20px:"id="Study Tips" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3> Study Tips</h3>
  <p style="font-family:graduate;">One key to success in college is intertwined with your studying habits, since your grade primarily comes from the assessments you take in class. It is important you find the studying method which is best for you.</p> 
  <h4> Studying for an exam? </h4>
    <p style="font-family:graduate;"> Google "site:edu [subject] exam". You'll get a bunch of college exams from the same course. A great way to quiz yourself before your actual exam.</p>
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
  <h4> 14 Restaurants That Do Student Discounts </h4>
  <ul>
  <li style="font-family:graduate;"> Subway - 10% off </li>
  <li style="font-family:graduate;"> Chipotle - Free Drink </li>
  <li style="font-family:graduate;"> Qdoba - Free Drink </li>
  <li style="font-family:graduate;"> Burger King - 10% off </li>
  <li style="font-family:graduate;"> Waffle House - 10% off </li>
  <li style="font-family:graduate;"> Chick-Fil-A - Free Drink </li>
  <li style="font-family:graduate;"> Arby's - 10% off </li>
  <li style="font-family:graduate;"> McDonalds - 10% off </li>
  <li style="font-family:graduate;"> Buffalo Wild Wing - 10% off </li> 
  <li style="font-family:graduate;"> Dairy Queen - 10% off </li>
  <li style="font-family:graduate;"> Domino's - 10% off </li>
  <li style="font-family:graduate;"> Pizza Hut - 10-20% off </li>
  <li style="font-family:graduate;"> Papa John's - 10-20% off </li>
  <li style="font-family:graduate;"> IHOP - 10% off </li>
  </ul>
  <h4>  Supplies Stores That Do Student Discounts</h4>
  <ul>
  <li style="font-family:graduate;"> FedEx Office - 30% off documents - 20% off with their shipping services </li>
  <li style="font-family:graduate;"> Amazon - free two-day shipping for 6 months </li>
  <li style="font-family:graduate;"> Ben Franklin Crafts - Tuesdays, take 10% off </li>
  <li style="font-family:graduate;"> Jo-Ann Fabric Store - 10% off </li>
  <li style="font-family:graduate;"> Hancock Fabrics - 10% off </li>
  <li style="font-family:graduate;"> Discount Dance Supply - 10% off </li>
  </ul>
  <h4> Bookstores That Do Student Discounts</h4>
  <ul>
  <li style="font-family:graduate;"> Guilford Press - 40% off and free shipping </li>
  <li style="font-family:graduate;"> The Economist - up to 69% with International Student ID Card </li>
  <li style="font-family:graduate;"> The New York Times - 99 cents first 4 weeks - 50% off afterwards </li>
  <li style="font-family:graduate;"> The Wall Street Journal - 75% off regular rates delivery </li>
  </ul>
  <h4> Clothing and General Merchandise</h4>
  <ul>
  <li style="font-family:graduate;"> Eddie Bauer - depends on location </li>
  <li style="font-family:graduate;"> Necessary Clothing - 20% off online purchases of $100 </li>
  <li style="font-family:graduate;"> Sam's Club - discount on membership - savings on college essentials </li>
  <li style="font-family:graduate;"> J.Crew - 15% off </li>
  <li style="font-family:graduate;"> Oasis - 20% off </li>
  <li style="font-family:graduate;"> Toms - free shipping - donates pair to child in need for every pair bought </li>
  <li style="font-family:graduate;"> Banana Republic - %15 off </li>
  <li style="font-family:graduate;"> Asos - free shipping </li>
  <li style="font-family:graduate;"> Eastern Mountain Sports - up to 20% off </li>
  <li style="font-family:graduate;"> Ralph Lauren Rugby - 15% off </li>
  <li style="font-family:graduate;"> CollegeBudget - major discounts on clothing, electronics, paintballing </li>
  <li style="font-family:graduate;"> Charlotte Russe - 10% off </li>
  <li style="font-family:graduate;"> Sally Beauty Supply - monthly specials and email offers </li>
  <li style="font-family:graduate;">
</div>

<div style="background-color:teal;color:white;padding:20px:"id="References" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3> References</h3>
  <ul> 
  <li style="font-family:graduate;"> studyreadwrite.com </li>
  <li style="font-family:graduate;"> tun.com </li>
  <li style="font-family:graduate;"> 1000lifehacks.com </li>
  </ul>
</div>

<div style="background-color:teal;color:white;padding:20px:"id="The Creators" class="tabcontent">
   <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
   <h3> The Creators</h3>
   <p style="font-family:graduate;"> 
   
<body>

<br>

<div class="row">
  <div class="column" <div style="background-color: #FFFFOO; style="width:100%">
    <div class="card">
      <img src= alt="Vanesa" style="width:100%">
      <div class="container">
        <h2>Vanesa Marar</h2>
        <p class="title">Co-Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>  
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column" <div style="background-color: #B9D9BD; style="width:100%">
    <div class="card" >
	   <img src= alt="Jacqueline" style="width:100%">
      <div class="container">
        <h2>Jacqueline Marchan</h2>
        <p class="title">Co-Founder</p>
        <p>I am 16 and I like creating websites!</p>
        <p>marchjac000@auburnsd.org</p>  
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src= alt="Julia" style="width:100%">
      <div class="container">
        <h2>Julia Devine</h2>
        <p class="title">Co-Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p> 
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>

</body>
</div>

<div style="background-color:teal;color:white;padding:20px:"id="Road to Success" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3> Road to Success</h3>
   <p style="font-family:graduate;">To pursue a life of success and prosperity relies heavily on choices that you make as a student. Getting your habits and motivations in check are prime factors in planning out your future and acquiring it later on.</p>
</div>
<div style="background-color:#82B2B1;color:white;padding:20px;">
  <h2 align="middle">About Us</h2>
  <p style="font-family:graduate;">Hello! We are 3 young girls from a program named Girls Who Code! Here in GWC we learn the basics of JavaScript, C++, HTML, Python, etc. During our final 2 weeks we come together and start brainstorming ideas for our final project. We got placed in groups depending on what we wanted from the options available. Finally we were put into groups and started to work on our final projects. Which has brought us to the creation of this website! While planning what we were going to do for our website we all emphasized the desire to help high school students or anyone interested towards attending college. </p> 
  <p style="font-family:graduate;">Creators: Jacqueline Marchan, Julia Devine, Vanesa Marar</p>
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

