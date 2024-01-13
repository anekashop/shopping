---
title: Beranda
layout: default
---
{% includes navigasi.html %}

<div class="container mt-5">
<div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
  {{% includes carousel.html %}}
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</div>
  {% includes kategori-produk.html %}
  {% includes produk-baju.html %}
  {% includes produk-celana.html %}
  {% includes produk-hijab.html %}
  {% includes produk-assesoris.html %}
  {% includes produk-alat-rumah.html %}
  {% includes produk-alat-dapur.html %}
  {% includes produk-alat-wifi.html %}
  {% includes produk-elektronik.html %}
  {% includes footer.html %}