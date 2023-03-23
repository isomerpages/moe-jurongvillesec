---
layout: homepage
title: Jurongville Secondary School
description: An Isomer site of the Singapore Government
image: /images/JVSS_2020.ico
permalink: /
notification: ""

---

<body>
<div class="slideshow-container">

<div class="mySlides fade">
  <img src="/images/Homepage_P1.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <img src="/images/Homepage_P2.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <img src="/images/Homepage_P3.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <img src="/images/Homepage_P4.jpg" style="width:100%">
</div>  
  
</div>
<br>

<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  slides[slideIndex-1].style.display = "block";  
  setTimeout(showSlides, 5000); // Change image every 2 seconds
}
</script>
