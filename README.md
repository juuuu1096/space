<!DOCTYPE html>
<html>
  <head>
    <title>Space Travel</title>
    <meta charset="utf-8" />
    <meta name="viewpoint" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="/Project1/web1.css" />
    <style>
      body {
  background-color: rgba(0,0,0);
  overflow-y: hidden;
  height: 100vh;
}
#section1 {
  position: relative;
  width: 100vw;
  height: 100vh;
}
#section2 {
  position: relative;
  width: 100vw;
  height: 100vh;
}
/*-------------------------------------------------------------*/

.img1 {
  position: absolute;
  width: 25vh;
  height: auto;
  opacity: 0.3;
  top: 28vh;
  left: 43vw;
  -moz-animation: r1 4s infinite ease-in-out;
  -webkit-animation: r1 4s infinite linear;
}

@-moz-keyframes r1 {
  0% {
    opacity: 1;
    width: 40vh;
    height: auto;
  }
  50% {
    opacity: 1;
    width: 0vh;
    height: auto;
  }
  100% {
    opacity: 1;
  }
}

/*-------------------------------------------------------------*/
#circle {
  position: absolute;
  background-color: transparent;
  top: 32vh;
  left: 45vw;
}
.outerCircle {
  position: absolute;
  background-color: transparent;

  border: 8px solid aliceblue;
  opacity: 0.9;

  border-right: 5px solid transparent;
  border-left: 5px solid transparent;
  border-radius: 100px;

  width: 15vh;
  height: 15vh;

  -moz-animation: spinPulse 3s infinite ease-in-out;
  -webkit-animation: spinPulse 3s infinite ease-in-out;
}

.innerCircle {
  position: relative;
  background-color: transparent;

  border: 5px solid pink;
  opacity: 0.9;

  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-radius: 100px;
  top: 1vh;
  left: 1vh;
  width: 13vh;
  height: 13vh;

  -moz-animation: spinoffPulse 1s infinite linear;
  -webkit-animation: spinoffPulse 1s infinite linear;
}

@-moz-keyframes spinPulse {
  0% {
    -moz-transform: rotate(160deg);
    opacity: 0;
    box-shadow: 0 0 1px #bdd73c;
  }
  50% {
    -moz-transform: rotate(145deg);
    opacity: 1;
  }
  100% {
    -moz-transform: rotate(-320deg);
    opacity: 0;
  }
}
@-moz-keyframes spinoffPulse {
  0% {
    -moz-transform: rotate(0deg);
  }
  100% {
    -moz-transform: rotate(360deg);
  }
}
@-webkit-keyframes spinPulse {
  0% {
    -webkit-transform: rotate(160deg);
    opacity: 0;
    box-shadow: 0 0 1px #bdd73c;
  }
  50% {
    -webkit-transform: rotate(145deg);
    opacity: 1;
  }
  100% {
    -webkit-transform: rotate(-320deg);
    opacity: 0;
  }
}
@-webkit-keyframes spinoffPulse {
  0% {
    -webkit-transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(360deg);
  }
}
@-moz-keyframes rotatecircle {
  0% {
    -moz-transform: rotate(0deg);
  }
  100% {
    -moz-transform: rotate(-360deg);
  }
}

@-webkit-keyframes rotatecircle {
  0% {
    -webkit-transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(-360deg);
  }
}

/*-------------------------------------------------------------*/

/* DEMO-SPECIFIC STYLES */
.typewriter h1 {
  position: relative;
  top: 28vh;
  left: 50vh;
  color: white;
  font-family: monospace;
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: 0.15em solid orange; /* The typwriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: 0.15em;
  animation: typing 6.5s steps(20, end), blink-caret 0.5s step-end infinite;
}

/* The typing effect */
@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from,
  to {
    border-color: transparent;
  }
  50% {
    border-color: orange;
  }
}

/*-------------------------------------------------------------*/
#instagram {
  position: absolute;
  background-color: transparent;
  color: hotpink;
  text-decoration: none;
  font-family: monospace;
  width: 11vw;
  height: 3vh;
  top: 60vh;
  left: 45vw;
  text-align:center;
  border-radius: 5px;
  border-style: ridge;
  border-color: white;
}

.insta{
  text-align:center;
  background-color: transparent;
  color: hotpink;
  text-decoration: none;
  font-family: monospace;
  font-size:1.5em;
}


#DC {
  position: absolute;
  background-color: transparent;
  color: hotpink;
  text-decoration: none;
  font-family: monospace;
  width: 11vw;
  height: 3vh;
  top: 65vh;
  left: 45vw;
  text-align:center;
  border-radius: 5px;
  border-style: ridge;
  border-color: white;
}

.dc1{
  text-align:center;
  background-color: transparent;
  color: hotpink;
  text-decoration: none;
  font-family: monospace;
  font-size:1.5em;
}
    </style>
  </head>

  <body>
    <div id="section1">
      <div id="imgcontainer">
        <img
          src="https://cdn.glitch.global/53d79856-1b9d-4ae0-b0df-00c8ec2d6daf/Space-Hole-PNG-Image.png?v=1643940169697"
          class="img1"
        />
      </div>
      <a href="#section2"
        ><div id="circle">
          <div class="outerCircle"></div>
          <div class="innerCircle"></div>
        </div>
      </a>
    </div>

    <div id="section2">
      <div class="typewriter">
        <h1>Oops.</h1><br>
        <h1>Something just went wrong.</h1><br>
          <h1>I don't know what's happening.</h1>
          <h1>Have I just been sucked into a space hole?</h1>
        <br>
        <br>
          <h1>Wait. </h1>
          <h1>I have to put this on my instagram!</h1>
       
      </div>
      <div id="instagram">
        <a href="https://www.instagram.com/juliaaaa1096/" class="insta">Go to My Insta</a>
      </div>
      <div id="DC">
        <a href="https://www.bilibili.com/video/BV1Dx411B72c?from=search&seid=11399444919261781069&spm_id_from=333.337.0.0" class="dc1">Or maybe...</a>
      </div>
    </div>
  </body>
</html>
