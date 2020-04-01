<!DOCTYPE html>
<html lang="en">
<title>Home</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
    body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif}
    .w3-bar,h1,button {font-family: "Montserrat", sans-serif}
</style>
<body>

<!-- Navbar -->
<div class="w3-top">
    <div class="w3-bar w3-purple w3-card w3-left-align w3-large">
        <a class="w3-bar-item w3-button w3-hide-medium w3-hide-large w3-right w3-padding-large w3-hover-white w3-large w3-red" href="javascript:void(0);" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
        <a href="index.html" class="w3-bar-item w3-button w3-padding-large w3-white">Home</a>
        <a href="play.html" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">Play</a>
        <a href="design.html" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">Design</a>
        <a href="team.html" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">The Team</a>
    </div>
</div>

<!-- Header -->
<header class="w3-container w3-black w3-center" style="padding:128px 16px; background-image: url('images/Web_Game_Logo.png'); background-repeat: no-repeat; background-size: 1100px 600px; background-position: center">
    <h1 class="w3-margin w3-jumbo"></h1>
    <p class="w3-xlarge" style="padding-top: 512px">A game by Leon, Kenneth and Kirstin</p>
    <button class="w3-button w3-indigo w3-padding-large w3-large w3-margin-top" onclick="window.location='play.html'">Play</button>
</header>

<!-- Video Demo -->
<div class="w3-row-padding w3-light-grey w3-padding-64 w3-container">
    <div class="w3-content">
        <iframe width="896" height="504" src="https://www.youtube.com/embed/NUWSGjkbUfY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>

        </iframe>
    </div>
    </div>
</div>

<!-- Overview -->
<div class="w3-row-padding w3-padding-64 w3-container w3-indigo">
    <div class="w3-content">
        <div class="w3-twothird w3-text-white">

            <h1>Fight back the monsters!</h1>

            <h5 class="w3-padding-32">
                Sleepless Nights is a local 2D co-op top-down survival shooter which involve a group with 3
                young children whom must team up to defeat the monsters lurking within the darkness of their imagination.
                The game is inspired by similar style games such as dungeon crawlers and other survival based shooter games.
            </h5>

            <p class="w3-text-white"></p>
        </div>

        <div class="w3-third w3-center">
            <img src="images/Girl2.png" height="300" width="200">
        </div>
    </div>
</div>

<!-- Description -->
<div class="w3-row-padding w3-light-grey w3-padding-64 w3-container">
    <div class="w3-content">
        <div class="w3-third w3-center">
            <img src="images/Boy2.png" height="300" width="200">
        </div>

        <div class="w3-twothird">

            <h1>Team up with friends!</h1>

            <h5 class="w3-padding-32">Featuring up to 2 player local co-op, you won't have to fight the monsters alone! Each player can chose their own character with unique abilities and weapons.</h5>

            <p class="w3-text-grey"></p>
        </div>
    </div>
</div>

<div class="w3-container w3-black w3-center w3-opacity w3-padding-64">
    <h1 class="w3-margin w3-xlarge"></h1>
</div>

</body>
</html>