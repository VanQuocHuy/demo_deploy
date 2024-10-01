<template>
  <div class="sticky-top">
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
       <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img src="/images/logo_banner.png" class="logo-img" alt=""> 
      </a>
  
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-4 mb-lg-2">
        <li class="nav-item">
          <NuxtLink to="/" class="nav-link">Trang chủ</NuxtLink>
        </li> 
        <li class="nav-item">
          <NuxtLink to="/about" class="nav-link">Giới thiệu</NuxtLink>
        </li>

        <li class="nav-item"> 
          <NuxtLink to="/services" class="nav-link">Dịch Vụ </NuxtLink>
        </li> 

        <li class="nav-item">
          <NuxtLink to="/contact" class="nav-link">Liên Hệ</NuxtLink>
        </li>
         
      </ul>
      
    </div>
  </div>
</nav>
  </div>
</template>

<script>
export default {
   name: 'AppHeader'
}
</script>

<style> 
  .logo-img{
    width: 100px;
    height: 40px;
    margin-left: 200px;
  }

</style>
