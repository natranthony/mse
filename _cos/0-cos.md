---
title: MSE Committee of Supply 2021
permalink: /cos2021
---

<style>

/* Fouridine's colours
blue #04B1DC
brown #F4F0E5
light blue #E9F4F4
neon green #9DFF94
red #E44325
*/


/* html {
  font-size: 18px;
  line-height: 1.5;
  font-weight: 300;
  color: #333;
  font-family: "Nunito Sans", sans-serif;
} */

body {
  background-color: #F4F0E5;
}

*, *:before, *:after {
  box-sizing: border-box;
}

#main-content > section:nth-child(3) > div > div > div.col.is-1.has-float-btns.is-position-relative.is-hidden-touch {
      visibility: hidden;
}


.card-content {
  display: flex;
  margin: 0 auto;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  max-width: 1000px;
}


.card-content a:hover, .card-content a:active {
  color: #000;
}

.heading {
  width: 100%;
  margin-left: 1rem;
  font-weight: 900;
  font-size: 1.618rem;
  text-transform: uppercase;
  letter-spacing: 0.1ch;
  line-height: 1;
  padding-bottom: 0.5em;
  margin-bottom: 1rem;
  position: relative;
}


.description {
  width: 100%;
  margin-top: 0;
  margin-left: 1rem;
  margin-bottom: 3rem;
  text-align: center;
  font-style: italic;
  font-family: "Roboto Condensed", "Lato", sans-serif;
}

.card {
  color: #000;
  cursor: pointer;
  width: calc(33% - 2rem);
  min-width: calc(33% - 2rem);
  height: 400px;
  min-height: 400px;
  perspective: 1000px;
  margin: 1rem;
  position: relative;
}

@media screen and (max-width: 800px) {
  .card {
    width: calc(50% - 2rem);
  }
}
@media screen and (max-width: 500px) {
  .card {
    width: 100%;
  }
}

.front,
.back {
  display: flex;
  border-radius: 12px;
  background-position: center;
  background-size: cover;
  text-align: left;
  justify-content: center;
  align-items: center;
  position: absolute;
  height: 100%;
  width: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  transform-style: preserve-3d;
  transition: ease-in-out 600ms;
}

.front h2, 
.front h4 {
  background-size: cover;
  padding: 1.4rem;
  font-size: 2.2rem;
  font-weight: 600;
  color: #fff;
  overflow: hidden;
  font-family: "Roboto Condensed", "Lato", sans-serif;
  font-style: italic;
}

.front h4 img {
  width: 80%;
  float: left;
  padding-top: 1rem;
}

.front:before {
  position: absolute;
  display: block;
  border-radius: 12px;
  content: "";
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: linear-gradient(135deg, #000, #000);
  opacity: 0.4;
  z-index: -1;
}
.card:hover .front {
  transform: rotateY(180deg);
}
.card:nth-child(even):hover .front {
  transform: rotateY(-180deg);
}

.back {
  background: #F4F0E5;
  transform: rotateY(-180deg);
  padding: 0 1em;
}
/* .back .button {
  background: linear-gradient(135deg, #1a9be6, #1a57e6);
}
.back .button:before {
  box-shadow: 0 0 10px 10px rgba(26, 87, 230, 0.25);
  background-color: rgba(26, 87, 230, 0.25);
} */
.card:hover .back {
  transform: rotateY(0deg);
}
.card:nth-child(even) .back {
  transform: rotateY(180deg);
}
/* .card:nth-child(even) .back .button {
  background: linear-gradient(135deg, #e61a80, #e61a3c);
}
.card:nth-child(even) .back .button:before {
  box-shadow: 0 0 10px 10px rgba(230, 26, 60, 0.25);
  background-color: rgba(230, 26, 60, 0.25);
} */
.card:nth-child(even):hover .back {
  transform: rotateY(0deg);
}


.button {
  cursor: pointer;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  font: inherit;
  border: none;
  position: relative;
  transition: 300ms ease;
  color: #484848 !important;
  text-transform: uppercase;
  text-decoration: none;
  background: #ffffff;
  padding: 15px 20px;
  border: 2px solid #484848;
  display: inline-block;
  transition: all 0.4s ease 0s;
  border-radius: 15px;
  font-weight: bold;
  text-decoration: none !important;
}
.button:before {
  transition: 300ms ease;
  position: absolute;
  display: block;
  content: "";
  transform: translateZ(-40px);
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  height: calc(100% - 20px);
  width: calc(100% - 20px);
  border-radius: 100px;
  left: 10px;
  top: 16px;
}
.button:hover {
  transform: translateZ(55px);
  color: #ffffff !important;
  background: #4a96b0;
  border-color: #4a96b0 !important;
  transition: all 0.4s ease 0s;
  text-decoration: none;
}
.button:hover:before {
  transform: translateZ(-45px);
}
.button:active {
  transform: translateZ(20px);
}
.button:active:before {
  transform: translateZ(-20px);
  top: 10px;
}



</style>


<link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital@1&display=swap" rel="stylesheet">
<div class="container">
<div class="card-content">
<h2 class="description" style="color:#4a96b0; font-weight:bold; font-family:'Roboto Condensed'">RALLYING COLLECTIVE ACTION <br> FOR A CLEANER AND GREENER FUTURE</h2>
  <!-- <p class="description"> Everyone has a part to play in keeping our public spaces clean, and in saving resources as a way of life in Singapore</p> -->
        
  <div class="card">
    <div class="front" style="background-image: url(/images/cosclean.jpg);">
      <h4>Cleaner Public Spaces</h4>      
    </div>
    <div class="back">
      <div>
        <p>Our collective efforts to shore up our public health defences will guard us against future threats. </p>
        <a href="/cos2021/cleaner-public-spaces"><button class="button">Learn More</button></a>
      </div>
    </div>
  </div>
    
  <div class="card"> 
    <div class="front" style="background-image: url(/images/cosgreengov.jpg)">
      <h4>GreenGov.SG
      <img src="/images/sgplogowhite.png" alt=""></h4>
    </div>
    <div class="back">
        <div>
          <p>New and ambitious targets will be set for the public sector as we place sustainability at the core of everything we do.</p>
          <a href="/cos2021/greengov"><button class="button">Learn More</button></a>
        </div>
      </div>
  </div>

  <div class="card">
    <div class="front" style="background-image: url(/images/coswaste.jpg)">
      <h4>Towards Zero Waste
      <img src="/images/sgplogowhite.png" alt=""></h4>
    </div>
    <div class="back">
      <div>
        <p>New schemes and frameworks will be put in place to encourage recycling and reduce food waste and e-waste.</p>
        <a href="/cos2021/sustainable-living"><button class="button">Learn More</button></a>
      </div>
    </div>
  </div>
    
  <div class="card">
    <div class="front" style="background-image: url(/images/coswater.jpg)">
      <h4>Improving Water Efficiency
      <img src="/images/sgplogowhite.png" alt=""></h4>
    </div>
    <div class="back">
      <div>
        <p>Every drop is precious. We will manage water demand by encouraging the switch to more water-efficient products.</p>
        <a href="/cos2021/water"><button class="button">Learn More</button></a>
      </div>
    </div>
  </div>

  <div class="card">
    <div class="front" style="background-image: url(/images/cosclimate.jpg)">
      <h4>Climate Resilience & Food Security
      <img src="/images/sgplogowhite.png" alt=""></h4>
    </div>
    <div class="back">
      <div>
        <p>Mitigating and adapting to climate change will help ensure our resilient future.</p>
        <a href="/cos2021/resilient-future"><button class="button">Learn More</button></a>
      </div>
    </div>
  </div>

  <div class="card">
    <div class="front" style="background-image: url(/images/coshawker.jpg)">
      <h4>Our Hawker Culture</h4>
    </div>
    <div class="back">
      <div>
        <p>We are safeguarding our hawker culture and transforming the industry through new programmes and schemes.</p>
        <a href="/cos2021/hawker"><button class="button">Learn More</button></a>
      </div>
    </div>
  </div>
  
  <div class="card" style="width: calc(100% - 2rem);
  min-width: calc(100% - 2rem); height: 120px; min-height: 120px;">
    <div class="front" style="background-image: url(/cos/resources/cos-thumbnail-icons.jpeg);">
      <h4>Speeches & Infographics</h4>      
    </div>
    <div class="back">
      <div>
        <a href="/cos2021/speeches-and-infographics"><button class="button">Speeches & Infographics</button></a>
      </div>
    </div>
  </div>

</div>
</div>





