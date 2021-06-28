<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta charset="utf-8">
  <title>SimpleTrail - שביל ישראל</title>
  <link rel="icon" href="int.ico ">

  <!-- css -->
  <link rel="stylesheet" href="css/simplrtrailstyle.css">

  <!-- bootstrap -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>

<!-- fontawesome -->
  <script src="https://use.fontawesome.com/3a277a95fa.js"></script>


</head>

<style>
  body {
  margin: 0 0 0 0;
  text-align: center;
}

/********navbar*********/
.navbar {
  font-size: 1.15rem;
  font-family: Helvetica, Sans-Serif;
  height: 60px;
  background-color: #C68B59;
}




.explain-nav{
  font-size: 1.2rem;
}

b{
  color: #E8F0F2;
  font-size: 0.9rem;
}




/*******title*****/
.title {
  padding-top: 10%;
  font-size: 7rem;
  font-style: italic;
  font-family: Helvetica, Sans-Serif;
  color: #D7B19D;
}

.title-container {
  padding: 7% 5%;
  background-color: #865439;
  text-align: center;
}

.animation {
  animation-iteration-count: infinite;
  animation-name: logo;
  animation-duration: 4s;
}

.circul-title {
  border-radius: 100%;
  width: 70%;
  height: 100%;
}

@keyframes logo {
  0% {
    left: -2%;
  }

  50% {
    left: 6%;
  }

  100% {
    left: -2%;
  }
}

/* main-container */
.container {
  text-align: center;
}

.main {
  text-align: right;
}

.carousel {
  padding: 8% 5%;
}

img {
  width: 800px;
  height: 600px;

}



.explain {
  line-height: 1.8;
  padding-right: 3%;
  padding-top: 8%;
  text-align: right;
  font-size: 1.7rem;
  font-family: Helvetica, Sans-Serif;
  color: #402218;
}


 .hr {
  border-style: none;
  border-top-style: dotted;
  border-width: 1rem;
  width: 10%;
  color: #D7B19D;
  margin-bottom: 7%
}



/* information */

.devide{
  padding: 1% 0 7%;
}


.container-info{

  text-align: right;
  padding:2% 20% 10%;
  font-size: 1.6rem;
  font-family: Helvetica, Sans-Serif;
}


.list{
  display: inline;
  color: #C68B59;
  text-decoration: none;
}
.list:hover{
  text-decoration: none;
  color:gold;
}

.info_col  {
  padding: 5%;
}


.b{
  font-weight: bold;
  color: #402218;

}



/* footer */

.icon{
  height: 2rem;
  width: 2.2rem;
}


.pad{
  padding: 1% 0.7%;
}



.footer {
  text-align: center;
  margin-bottom: 0;
  padding-top: 1%;
  height: 3.5rem;
  background-color: #C68B59;
}

.contact {
  padding: 0 2%;
  color: #fff;
  font-size: 1rem;
}

.fff{
  color:#fff;

}

.fff:hover{
  color: #FFEAC9;
  text-decoration: none;
}

strong{
  color: #402218;
}
  </style>


<!-- nav-bar -->


<nav class="navbar navbar-expand-md navbar-dark fixed-top ">
<ul class="navbar-nav">
  <li class="nav-item active">
  <a class="navbar-brand" href="simpletrail1.html">SimpleTrail-שביל ישראל</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#information"><strong>כל המידע</strong></a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="sirtonim.html">סרטוני שביל</a>
  </li>
  <li class="nav-item">
    <a class="nav-link disabled" href="#about">על האתר</a>
  </li>
</ul>
</nav>



<body>






<!-- title -->

<div class="title-container">
  <div class="row">
     <div class="animation  col-6"><img class="circul-title" src=" imag/step.jpeg" alt=""> </div>
     <div class="col-6"><p class="title">SimpleTrail  שביל ישראל</p> </div>
   </div>
</div>







<!-- main-web -->

<div class="carousel  row">
    <div class="col-lg-6"><div id="myCarousel" class="carousel slide" data-ride="carousel" data-interval="2000">

  <!-- Indicators -->
  <ul class="carousel-indicators">
    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
    <li data-target="#myCarousel" data-slide-to="1"></li>
    <li data-target="#myCarousel" data-slide-to="2"></li>
  </ul>

  <!-- The slideshow -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="pic/6.jpg" alt="Los Angeles" >
    </div>
    <div class="carousel-item">
      <img src="pic/2.jpg" alt="Chicago" >
    </div>
    <div class="carousel-item">
      <img src="pic/3.jpg" alt="New York" >
    </div>
    <div class="carousel-item">
      <img src="pic/4.jpg" alt="New York" >
    </div>
    <div class="carousel-item">
      <img src="pic/5.jpg" alt="New York" >
    </div>
    <div class="carousel-item">
      <img src="pic/1.jpg" alt="New York"  >
    </div>
    <div class="carousel-item">
      <img src="pic/7.jpg" alt="New York"  >
    </div>
    <div class="carousel-item">
      <img src="pic/8.jpg" alt="New York"  >
    </div>
    <div class="carousel-item">
      <img src="pic/9.jpg" alt="New York"  >
    </div>
    <div class="carousel-item">
      <img src="pic/10.jpg" alt="New York"  >
    </div>
    <div class="carousel-item">
      <img src="pic/11.jpg" alt="New York"  >
    </div>
    <div class="carousel-item">
      <img src="pic/12.jpg" alt="New York"  >
    </div>
  </div>

  <!-- Left and right controls -->
  <a class="carousel-control-prev" href="#myCarousel" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </a>
  <a class="carousel-control-next" href="#myCarousel" data-slide="next">
    <span class="carousel-control-next-icon"></span>
  </a>
</div></div>
  <div class="col-lg-6 " id="about"><p class="explain">אנשים יקרים, לפני לא הרבה זמן החלטתי תוך פרק זמן מועט שאני עושה את שביל ישראל, זה היה בהחלטה של רגע וישר חיפשתי את כל המידע הנגיש האפשרי שאני צריך כדי פשוט לצאת. זה היה מסע מאוד מסורבל והתפוצצתי ביותר מדי מידע, לא היה מקור מידע פשוט וקצר שיאפשר לי לצאת בנינוחות ובלי דאגות. היום שאני כבר אחרי המסע, הבנתי שהרבה אנשים לא יוצאים לשביל בגלל עודף המידע והרושם המוטעה שנוצר שזה מסע מפרך ומסובך. המטרה שלי היא לפשט לכם הכל עד כמה שניתן , כיוון שזו חוויה כל כך נגישה ופשוטה שמאחדת אותנו ומחברת אותנו לארץ פיזית ונפשית כאחד. כל מטרתי כאן היא להקל עליכם לקבל את ההחלטה שתעשו את השביל , כיוון שברגע שהחלטתם, עשיתם/ן כבר את רוב הדרך</p><p class="explain"> בנוסף, אתם שולטים באתר הזה. כל הצעה לייעול או להוספת פרטים תתקבל בברכה , אז שלחו לנו ב-אינסטגרם או ב-מייל שבקישורים למטה</p></div>


</div>



<!-- information -->


<hr class="hr">


<section id="information">

<div class="container-info">
  <div class="row">
    <div class="info_col col-9"><p>במילה אחת - מינימליזם, תצמצמו כמה שניתן, כיוון שתרגישו כל גרם, מצד שני לא להתפשר על דברים קריטיים או שעושים לכם טוב בלב . אז כאן תוכלו להוריד את הרשימה המפורטת ולתאם אותה לנוחיותכם .<a class="list" href="imag/list.docx">  להורדה </a></p>
    </div>
    <div class="b  info_col  col-3">ציוד </div>
    <div class="info_col  col-9">  , לכשירות הפיזית יש קשר ישיר לציוד שתלכו איתו, תשקיעו בתיק ונעליים שלא יפצעו אתכם. מבחינת כושר לפני היציאה לשביל תלכו עם כל הציוד המלא שתלכו איתו בשביל + 3 ק"ג, הטיול המכין מחויב במינימום להיות 30 ק"מ בתוואי בינוני ואותם תפרסו למשך כיומיים הליכה</div>
    <div class="b  info_col  col-3">הכנה פיזית</div>
    <div class="info_col  col-9">הדלק שלכם, תהיו חכמים, מצד אחד חשבו את המשקל שלא תסחבו יתר על המידה, ומצד שני זהו הדבר הראשון שלא מתפשרים עליו. למתחילים מהצפון הרבה יותר קל להתגמש ולדעת מה כמות הצריכה השבועית שלכם. <a class="list" href="imag/food.docx">להורדה</a></div>
    <div class="b  info_col  col-3">אוכל</div>
    <div class="info_col  col-9">אחד הדברים שהייתי מאוד מוטרד מהם לפני היציאה, באמת שאין שום סיבה לכך פשוט תתקשרו למטמינים, דרכם גם תוכלו לדעת באילו מקומות נחוץ הטמנות וכמה מים תצטרכו. יניר -0542461066</div>
    <div class="b  info_col  col-3">הטמנות</div>
    <div class="info_col  col-9">רוב המטיילים בשביל מנווטים עם עמוד ענן, כאן יש לכם מפות לפי מקטעים במידה ותרצו להדפיס. <a class="list" href="imag/israeltrailmaps.zip">  להורדה </a></div>
    <div class="b  info_col  col-3">מפות וניווט</div>
    <div class="info_col  col-9">כבדו כל מקום שתגיעו אליו, השתדלו להיות ספונטניים במידה ולא מצאתם מישהו ליום מסוים, תמיד איכשהו מסתדרים. <a class="list" href="https://shvil.fandom.com/wiki/%D7%9E%D7%9C%D7%90%D7%9B%D7%99_%D7%A9%D7%91%D7%99%D7%9C_%D7%99%D7%A9%D7%A8%D7%90%D7%9C" target="_blank"> למעבר לאתר </a> </div>
    <div class="b  info_col  col-3">מלאכי שביל</div>
    <div class="info_col  col-9">בדקו כל שבוע עומסי חום ושיטפונות , מיותר להדגיש את זה כי זה די מובן מאליו, בנוסף במידה ואתם קצת לא מרגישים טוב בתחילת יום אז אל תצאו אליו, תנוחו ותמלאו מצברים. <a class="list" href="https://ims.gov.il/he" target="_blank">  לאתר השרות המטאורולוגי </a></div>
    <div class="b  info_col  col-3">בטיחות</div>
  </div>
</div>
</section>



 <!-- footer -->

 <div class="footer">
   <a class="pad"  href="mailto:simpletrailisr@gmail.com?subject=feedback" target="_blank">
     <img class="icon" src="pic/email.png" >
   </a>
 <a class="pad"  href="https://www.instagram.com/simple.trail_shvilisrael/" target="_blank">
    <img class="icon" src="pic/ins.png" >
 </a>
 <a class="pad"  href="https://www.facebook.com/" target="_blank">
   <img class="icon" src="pic/face.png" >
 </a>
 </div>

</body>




</html>
