<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <script src="https://use.fontawesome.com/d1341f9b7a.js"></script>
    <link rel="stylesheet" href="style.css">
    <title>Personal WebSite</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
  </head>
  <body>

<div class="box">
  <div class="box-img">
  <img src="profile.jpg" alt="">
</div>
  <h1>
John Benedict S. Santos</h1>
<p><strong>
Athlete - Student - Member</strong></p>
<p>
Hello, My name is John Benedict S. Santos. I am 13 years old and I live Santor, Malolos Bulacan. I like to play basketball and ride my bike. I am a member of Group 2 of TEAMTAM, and this is my homepage plus my profile page. Let's get to know more about me! I study in Bulacan Ecumenical School, and my favorite subjects are AP, Computer and TLE. During my free time, I like to watch tikok or play codm.</p>

<div>
 <h2 class="centered">My Javascript Sample!</h2>
  <div class="centered">
    <h3>Hide / Show Box</h3>
    <button class="open-button" id="openButton" onclick="openBox()">Open Box</button>
      <div class="box-popup" id="myBox">
          <h3>I see you made me appear, Yay!</h3>
          <button type="button" class="btn cancel" onclick="closeBox()">Close Box</button>
      </div>
      </div>



<script>
function openBox() {
  document.getElementById("myBox").style.display = "block";
  document.getElementById("openButton").style.display = "none";
}

function closeBox() {
  document.getElementById("myBox").style.display = "none";
  document.getElementById("openButton").style.display = "block";
}
</script>
</body>
</html>


