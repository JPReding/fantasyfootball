---
layout: post
author: Jonathan
description: Looking good on paper
title: Draft Results
---
The draft was a blast and the 12 team dynamic proved interesting and challenging. I uploaded our results to a popular fantasy site and here is the way it graded the current strength of our teams. 

As we all know, however, things change drastically upon the first regular season snap, the injuries, and the waiver wire pickups start rolling. 

It's anybody's championship to take, but please, oh please can we stop Jeremy for once?

### Draft Rankings

<img class="center" src="/assets/draft/draftpower.png" alt="Draft Power Rankings">
### Playoff Projections

<img class="center" src="/assets/draft/playoffprojections.png" alt="Draft Playoff Projections">

<!-- HTML -->
### Round by Round
<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <img src="/assets/draft/r1.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r2.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r3.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r4.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r5.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r6.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r7.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r8.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r9.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r10.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r11.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r12.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r13.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r14.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r15.png" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/draft/r16.png" style="width:100%">
  </div>

<!-- Next and previous buttons -->
  <a class="imageprev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="imagenext" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span> 
  <span class="dot" onclick="currentSlide(6)"></span> 
  <span class="dot" onclick="currentSlide(7)"></span> 
  <span class="dot" onclick="currentSlide(8)"></span>
  <span class="dot" onclick="currentSlide(9)"></span>
  <span class="dot" onclick="currentSlide(10)"></span> 
  <span class="dot" onclick="currentSlide(11)"></span> 
  <span class="dot" onclick="currentSlide(12)"></span> 
  <span class="dot" onclick="currentSlide(13)"></span> 
  <span class="dot" onclick="currentSlide(14)"></span> 
  <span class="dot" onclick="currentSlide(15)"></span> 
  <span class="dot" onclick="currentSlide(16)"></span> 
</div>

<!-- CSS -->
<style>
* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.imageprev, .imagenext {
  cursor: pointer;
  position: absolute;
  top: 40%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  background-color: #145998;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
  opacity: 0.2;
}

/* Position the "next button" to the right */
.imagenext {
  right: 0;
  background-color: #145998;
  color: white;
}

/* On hover, add a black background color with a little bit see-through */
.imageprev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
  opacity: 0.7;
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
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.round {
  border-radius: 50%;
}

.active, .dot:hover {
  background-color: #145998;
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

</style>

<script>
var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1} 
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none"; 
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block"; 
  dots[slideIndex-1].className += " active";
}
</script>