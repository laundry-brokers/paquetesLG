<template>
  <div class="background-gray">
    <div class="container">
        <div class="row">
            <div class="col-md-6 col-sm-12 col-lg-6 col-xl-6 col-xxl-6 mt-4">
                <div class="d-flex justify-content-center">
                    <img src="/public/img/LG_Land_Promo_4toTrim_Img_Oferta.png"  width="250" alt="" class="img-fluid">
                </div>
                <div>
                    <img src="/public/img/LG_Land_Promo_4toTrim_Empre_equipos.png" alt="" class="img-fluid">
                </div>
            </div>

            <div class="col-md-6 col-sm-12 col-lg-6 col-xl-6 col-xxl-6 mt-4">
                <div style="margin-left: 50px;">
                    <img src="/public/img/LG_Land_Promo_4toTrim_Tex_Emprend.png" width="200" alt="" class="img-fluid">
                </div>
                <div class="d-flex justify-content-center">
                    <img src="/public/img/LG_Land_Promo_4toTrim_Tex_Empre_descrip.png" alt="" class="img-fluid">
                </div>
            </div>
        </div>
    </div>
    <br><br>
  </div>
</template>

<script>
export default {
    name: 'PaqueteEmprendeComponent'
}
</script>

<style scoped>
    .background-gray {
        background-image: url('/public/img/LG_Land_Promo_4toTrim_Back_Gris.png');
        background-position: center, center;
        background-repeat: no-repeat;
        background-size: cover;
        width: 100%;
        height: auto;
    }
</style>