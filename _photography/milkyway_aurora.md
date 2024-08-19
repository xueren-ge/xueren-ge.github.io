---
title: "Milkyway Collections"
layout: single-portfolio
collection: photography
order_number: 10
---

<link href="https://cdn.jsdelivr.net/npm/lightbox2@2.11.3/dist/css/lightbox.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/lightbox2@2.11.3/dist/js/lightbox.min.js"></script>

<script>
  document.addEventListener('contextmenu', function(e) {
    if (e.target.tagName === 'IMG') {
      e.preventDefault();
    }
  });
</script>

<style>
  .image-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    justify-content: center;
    grid-auto-rows: 1fr;
  }
  .image-grid figure {
    margin: 0;
  }
  .image-grid img {
    width: 180px;
    height: 250px;
    padding: 5px;
    border: 1px solid #ddd;
    margin: auto;
    -webkit-user-drag: none;
    user-drag: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    pointer-events: none;
  }
  .image-grid figcaption {
    text-align: center;
    font-size: 12px;
    color: #666;
    margin-top: 5px;
  }
  .copyright {
    text-align: center;
    font-size: 12px;
    color: #666;
    margin-top: 20px;
  }
  .overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: transparent;
  }
</style>

<div class="image-grid">
  <figure>
    <a href="/images/photography/milkyway/m0.jpg" data-lightbox="milkyway"><img src="/images/photography/milkyway/m0.jpg" alt="Image 1"></a>
  </figure>
  <figure>
    <a href="/images/photography/milkyway/m1.jpg" data-lightbox="milkyway"><img src="/images/photography/milkyway/m1.jpg" alt="Image 2"></a>
  </figure>
  <figure>
    <a href="/images/photography/milkyway/m2.jpg" data-lightbox="milkyway"><img src="/images/photography/milkyway/m2.jpg" alt="Image 3"></a>
  </figure>
  <figure>
    <a href="/images/photography/milkyway/m3.jpg" data-lightbox="milkyway"><img src="/images/photography/milkyway/m3.jpg" alt="Image 4"></a>
  </figure>
  <figure>
    <a href="/images/photography/milkyway/m4.jpg" data-lightbox="milkyway"><img src="/images/photography/milkyway/m4.jpg" alt="Image 5"></a>
  </figure>
  <figure>
    <a href="/images/photography/milkyway/m5.jpg" data-lightbox="milkyway"><img src="/images/photography/milkyway/m5.jpg" alt="Image 6"></a>
  </figure>
</div>



<style>
  .panorama-grid {
    margin-top: 40px; /* Add a margin of 40px to create space */
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* Create 2 columns */
    justify-content: center;
    gap: 20px;
  }
  .panorama {
    width: 400px; /* Adjust the width to fit your panorama images */
    height: 230px; /* Adjust the height to fit your panorama images */
  }
  .panorama img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    padding: 5px;
    border: 1px solid #ddd;
  }
  .copyright {
    text-align: center;
    font-size: 12px;
    color: #666;
    margin-top: 20px;
  }
</style>

<div class="panorama-grid">
  <div class="panorama">
    <a href="/images/photography/milkyway/p1.jpg" data-lightbox="milkyway"><img src="/images/photography/milkyway/p1.jpg" alt="Panorama 1"></a>
  </div>
  <div class="panorama">
    <a href="/images/photography/milkyway/p2.jpg" data-lightbox="milkyway"><img src="/images/photography/milkyway/p2.jpg" alt="Panorama 2"></a>
  </div>
</div>

