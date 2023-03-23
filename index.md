---
layout: homepage
title: Jurongville Secondary School
description: An Isomer site of the Singapore Government
image: /images/JVSS_2020.ico
permalink: /
notification: ""
sections:
  - hero:
      background: /images/Homepage_P1.jpg 
      key_highlights:
        - title: announcements
          description: New Update!
          url: /parents-information/Term-Letters/tl/
  - infopic:
      title: Open House 2022
      description: Click button below for more information!
      button: click here
      url: /our-experience/Open-House-2022/2022/
      image: /images/Banner.jpg
      alt: Image alt text
---
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
