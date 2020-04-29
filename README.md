<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
	<title>Lemonade|Some Good News — Issue 01</title>
	<meta name="viewport" content="width=device-width">
	<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
	<link rel="icon" href="" type="image/x-icon">
	<!-- meyer-reset is a special css library that overrides all the ugle default css styles that come with html5 -->
	<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,500&display=swap" rel="stylesheet">

	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css">
  <script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
  <script src="//cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.7/ScrollMagic.min.js"></script>
  <script src="//cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.7/plugins/debug.addIndicators.min.js"></script>

	<link rel="stylesheet" href="css/style.css">
</head>

<body>

<div class="marqueeDiv">
  <marquee width="50%" direction="left" scrollamount="5" scrolldelay="60" onmouseover="this.stop();" onmouseout="this.start();">
    <ul class="ticker-left">
        <li id="marquee">
          Look for the helpers. You will always find people who are helping. Darkness cannot drive out darkness; only light can do that. Hate cannot drive out hate; only love can do that. Look for the helpers. You will always find people who are helping. Darkness cannot drive out darkness; only light can do that. Hate cannot drive out hate; only love can do that. Look for the helpers. You will always find people who are helping. Darkness cannot drive out darkness; only light can do that. Hate cannot drive out hate; only love can do that. Look for the helpers. You will always find people who are helping. Darkness cannot drive out darkness; only light can do that. Hate cannot drive out hate; only love can do that.Look for the helpers. You will always find people who are helping. Darkness cannot drive out darkness; only light can do that. Hate cannot drive out hate; only love can do that.
        </li>
    </ul>
  </marquee>
</div>

<div class="nav">
  <a class="navStyle" href="page1.html#">[EV]</a>
  <a class="navStyle" href="page1.html#">[SJ]</a>
  <a class="navStyle" href="page1.html#">[AC]</a>
</div>

<section class="intro">

  <video autoplay muted loop id="introVideo">
    <source src="images/1_1.mp4" type="video/mp4">
  </video>

  <div class="introTitle">
    <a id="introAT" href="index.html">ALONE TOGETHER</a>
    <h1 id="introIntro">Introduction</h1>
  </div>

  <div class="introPages">
    <div class="introPg1">
      <h1 id="introPg1">"That's one of the things that connect us as neighbors — in our own way, each one of us is a giver and a receiver.”</h1>
      <h1 id="introPg1Fred">Fred Rogers</h1><br><br>
      <h1 id="introPg1">|<br>|<br>|<br>|</h1>
    </div>

    <div class="introPg2">
      <h1 id="introPg1">In this Issue, Lemonade presents 3 inspiring stories from the Pandemic that give hope to the future of social justice, the environment, science, and the arts.</h1><br><br><br><br>
      <h1 id="introPg1">|<br>|<br>|<br>|</h1>
    </div>

</section>

<section class="one">

  <div id="oneTitle">
    <h1 id="oneSubStyle">THE ENVIRONMENT</h1>
    <h1 id="oneTitleStyle">The Coronavirus Offers a Radical New Vision for India’s Cities</h1>
  </div>

  <div id="oneTitleImages">
    <img class="oneMainImage"src="images/india.jpg" alt="">

  </div>

</section>

<script
  	src="https://code.jquery.com/jquery-3.4.1.min.js"
  	integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="
  	crossorigin="anonymous"></script>

  	<!-- link for your script file -->
    <script src="//cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.7/ScrollMagic.min.js"></script>
    <script src="//cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.7/plugins/debug.addIndicators.min.js"></script>
  <script src="script.js"></script>
  </body>
</html>



css

.intro {
  height:200vh;
  display: flex;
}


.introTitle {
  width: 50vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  position:sticky;
  position: -webkit-sticky;
  top:0;
}

.introPages {
  width: 50vw;
}

.introPages div{
  height:100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#marquee {
  text-transform: uppercase;
  font-family: 'Helvetica Neue LT Std 55 Roman';
  font-size: 18px;
  padding-top: 24px;
  -webkit-text-fill-color: white;
}

.marqueeDiv {
  position:sticky;
  position: -webkit-sticky;
  top:0;
}

#introAT {
  text-decoration: none;
  font-family: 'Playfair Display', serif;
  font-size: 24px;
  text-align: center;
  -webkit-text-fill-color: white;

}

#introIntro {
  font-family: 'Helvetica Neue LT Std 53 Extended';
  font-size: 48px;
  text-align: center;
  -webkit-text-fill-color: white;
  line-height: 60px;
}

#introVideo {
   position: fixed;
   top: px;
   right: 0;
   bottom: 0;
   left: 0;
   overflow: hidden;
   z-index: -100;
   width: 50vw;
}

#introPg1 {
  font-family: 'Helvetica Neue LT Std 55 Roman';
  font-size: 24px;
  text-align: center;
  width: 70%;
}

#introPg1Fred {
  font-family: 'Playfair Display', serif;
  font-size: 24px;
  text-align: center;
  line-height: 36px;
}

#scrollText {
  font-family: 'Helvetica Neue LT Std 53 Extended';
  font-size: 24px;
  text-align: center;
  width: 30%;
}

.nav{
  position: fixed;
  padding: 0px;
  margin-left:820px;
  margin-top: -24px;
}

.navStyle {
  font-family: 'Helvetica Neue LT Std 53 Extended';
  font-size: 24px;
  text-decoration: none;
  -webkit-text-fill-color: white;
  padding: 5px;
}


.one {
  height:200vh;
  display: flex;
}

#oneTitle {
  width: 50vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  position:sticky;
  position: -webkit-sticky;
  top:0;
}

.oneMainImage{
  height: 100vh;
  display: flex;
}
