<template>
  <div>
    <div class="hero-image img-fluid"></div>

    <div class="hero-image-mobile">
      <img src="/public/img/LG_Land_Promo_4toTrim_Banner_Mobil.png" alt="" class="img-fluid">
    </div>
  </div>
</template>

<script>
export default {
    name: 'BannerComponent'
}
</script>

<style scoped>
  .hero-image {
    background-image: url('/public/img/LG_Land_Promo_4toTrim_Banner_web.png');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: 85vh;
    display: block;
  }

  .hero-image-mobile {
    display: none; 
  }

  @media (max-width: 768px) {
    .hero-image {
      display: none;
    }

    .hero-image-mobile {
      display: block;
      height: auto;
    }
  }
</style>
