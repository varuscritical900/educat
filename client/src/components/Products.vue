<template>
    <div class="container d-flex flex-column">
    <div>
        <a class="border border-0 mb-2" href="#product">
    <img src="https://firebasestorage.googleapis.com/v0/b/educat-b9f44.appspot.com/o/Eo_circle_green_caret-down.svg.png?alt=media&token=1c4850fe-aeae-492a-9f56-07ae28acd6e6" alt="" class="img-thumbnail rounded-5" style="height: 50px;">
        </a>
</div>

<section id="product" class="mt-2">
    <h6>Our product</h6>
<h1>Learn without Limits</h1>
<div class="container marketing">

<!-- Three columns of text below the carousel -->
<div class="row">
  <div class="col-lg-4">
    <img src="https://firebasestorage.googleapis.com/v0/b/educat-b9f44.appspot.com/o/product1.svg?alt=media&token=e51a62b2-7384-41e9-ae56-486db545471c">
    <h2 class="fw-normal">Educat Library</h2>
    <p>A learning Management System and content library that offers a variety of ways on how to learn through blended learning.</p>
    <p><a class="btn btn-secondary" href="#">View details »</a></p>
  </div><!-- /.col-lg-4 -->
  <div class="col-lg-4">
    <img src="https://firebasestorage.googleapis.com/v0/b/educat-b9f44.appspot.com/o/product2.svg?alt=media&token=a6f96c35-0349-41b5-a727-b95bc0aa95eb">
    <h2 class="fw-normal">Educat Library</h2>
    <p>An online library that contains Digital Module, Worksheets and Assesments aligned with DepEd's K to 12 Curriculum</p>
    <p><a class="btn btn-secondary" href="#">View details »</a></p>
  </div><!-- /.col-lg-4 -->
  <div class="col-lg-4">
    <img src="https://firebasestorage.googleapis.com/v0/b/educat-b9f44.appspot.com/o/product3.svg?alt=media&token=6bf919ed-75d7-4061-a67f-20e3520bad90">
    <h2 class="fw-normal">Educat Rover</h2>
    <p>An offline solution rub by mini-computers that are equipped with wireless local area network for contactless file transfer</p>
    <p><a class="btn btn-secondary" href="#">View details »</a></p>
  </div><!-- /.col-lg-4 -->
</div><!-- /.row -->


</div>
</section>

</div>
</template>

<script setup lang="ts">

</script>

<style scoped>
/* GLOBAL STYLES
-------------------------------------------------- */
/* Padding below the footer and lighter body text */

body {
  padding-top: 3rem;
  padding-bottom: 3rem;
  color: rgb(var(--bs-tertiary-color-rgb));
}


/* CUSTOMIZE THE CAROUSEL
-------------------------------------------------- */

/* Carousel base class */
.carousel {
  margin-bottom: 4rem;
}
/* Since positioning the image, we need to help out the caption */
.carousel-caption {
  bottom: 3rem;
  z-index: 10;
}

/* Declare heights because of positioning of img element */
.carousel-item {
  height: 32rem;
}


/* MARKETING CONTENT
-------------------------------------------------- */

/* Center align the text within the three columns below the carousel */
.marketing .col-lg-4 {
  margin-bottom: 1.5rem;
  text-align: center;
}
/* rtl:begin:ignore */
.marketing .col-lg-4 p {
  margin-right: .75rem;
  margin-left: .75rem;
}
/* rtl:end:ignore */


/* Featurettes
------------------------- */

.featurette-divider {
  margin: 5rem 0; /* Space out the Bootstrap <hr> more */
}

/* Thin out the marketing headings */
/* rtl:begin:remove */
.featurette-heading {
  letter-spacing: -.05rem;
}

/* rtl:end:remove */

/* RESPONSIVE CSS
-------------------------------------------------- */

@media (min-width: 40em) {
  /* Bump up size of carousel content */
  .carousel-caption p {
    margin-bottom: 1.25rem;
    font-size: 1.25rem;
    line-height: 1.4;
  }

  .featurette-heading {
    font-size: 50px;
  }
}

@media (min-width: 62em) {
  .featurette-heading {
    margin-top: 7rem;
  }
}
</style>


