<template>
  <div class="hero-lg">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-4 col-sm-12 col-12 mt-4">
          <div class="card energy-star-card shadow-sm p-3 mb-4 bg-white rounded d-flex align-items-center flex-row">
            <img src="/public/img/LG_Land_Promo_4toTrim_Logo_Energystar.png" class="energy-star-logo img-fluid" alt="Energy Star Logo">
            <div class="energy-star-text ms-3">
              <h6 class="fw-bold mb-1">Las lavadoras comerciales LG</h6>
              <p class="mb-0">Cuentan con certificado ENERGY STAR, el cumplimiento de los estándares del sector de la eficiencia energética.</p>
            </div>
          </div>
        </div>

        <div class="col-md-4 col-sm-12 col-12 mt-4">
          <div class="card energy-star-card shadow-sm p-3 mb-4 bg-white rounded d-flex align-items-center flex-row">
            <div class="energy-star-text ms-3">
              <p class="mb-0">Los clientes prefieren la gran capacidad de las lavadoras
                  comerciales LG porque pueden terminar su ropa en una sola
                  carga, una mayor capacidad significa más rotaciones de
                  clientes para su negocio.</p>
            </div>
          </div>
        </div>

        <div class="col-md-4 col-sm-12 col-12 mt-4">
          <div class="card energy-star-card shadow-sm p-3 mb-4 bg-white rounded d-flex align-items-center flex-row">
            <div class="energy-star-text ms-3">
              <p class="mb-0">Duración estimada de 10 a 15 años en el negocio de
                  lavanderías profesionales, cuentan con el sistema LG Inverter
                  Direct DriveTM, por lo que ofrece un funcionamiento silencioso
                  y de baja vibración, lo que ayuda a generar menos desgaste
                  en los equipos.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'SectionBannerLGComponent'
  }
</script>

<style scoped>
.hero-lg {
  background-image: url('/public/img/LG_Land_Promo_4toTrim_Back_Black.png');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}

.energy-star-card {
  width: 100%;
  min-height: 180px;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  padding: 15px;
  flex-direction: row;
}


.energy-star-logo {
  width: 70px;
}

.energy-star-text {
  color: #333;
  text-align: left;
  margin-left: 10px;
  flex-grow: 1;
}

@media (max-width: 992px) { 
  .energy-star-card {
    max-width: 100%;
    flex-direction: column;
    text-align: center;
    align-items: center;
  }
  
  .energy-star-logo {
    width: 60px;
  }

  .energy-star-text {
    margin-left: 0;
    margin-top: 10px;
  }
}

@media (max-width: 768px) {
  .energy-star-logo {
    width: 50px;
  }

  .energy-star-card {
    flex-direction: column;
    text-align: center;
    align-items: center;
  }

  .energy-star-text {
    margin-left: 0;
    margin-top: 10px;
  }
}

@media (max-width: 576px) {
  .energy-star-logo {
    width: 45px;
  }

  .energy-star-card {
    padding: 10px;
    max-width: 100%;
  }

  .energy-star-text {
    margin-left: 0;
    margin-top: 5px;
  }
}
</style>


  