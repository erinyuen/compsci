
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Home</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="layout.css">
    
  </head>
  <body>
    <div class="topnav">
    <a href="index.html">HOME</a>
    <a href="portfolio.html">PORTFOLIO</a>
     <a href="aboutme.html">ABOUT ME</a>
     </div>
     <div class="header">
    <h1><center>HOME</center></h1>
    </div>
    <div class="row">
      <div class="column">
        <div class="card">
        <h2>WELCOME<br /><br /></h2>
        <p3><center>welcome to my website for ap comp sci principles, enjoy!!!<br /><br /><br />༼ ºل͟º ༼ ºل͟º ༼ ºل͟º ༽ ºل͟º ༽ ºل͟º ༽</center></p3>
      </div>
      </div>
      <div class="column">
        <div class="card">
        <h2>this is me:</h2>
        <center>
          <img class="mySlides" src="images/pictureme.jpg" height="300">
          <img class="mySlides" src="images/tdf.jpg" height="300">
          <img class="mySlides" src="images/eliza_dani.jpg" height="300">
          </center>
          <script>
            var slideIndex = 0;
carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    for (i = 0; i < x.length; i++) {
      x[i].style.display = "none"; 
    }
    slideIndex++;
    if (slideIndex > x.length) {slideIndex = 1}
    x[slideIndex-1].style.display = "block"; 
    setTimeout(carousel, 2500);
}
        </script>
        </div>
        </div>
    </div>
  </body>
</html>
