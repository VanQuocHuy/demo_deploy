<template>
  <div>
      <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="/images/meo8.jpg" class="d-lock w-100" alt="logo1">
      </div>
      <div class="carousel-item">
        <img src="/images/meo3.jpg" class="d-lock w-100" alt="logo2">
      </div>
      <div class="carousel-item">
        <img src="/images/meo9.jpg" class="d-lock w-100" alt="logo3 ">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  </div>
</template>

<script>
export default {
    name: 'slider'

}
</script>
