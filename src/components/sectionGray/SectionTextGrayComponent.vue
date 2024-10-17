<template>
    <div class="section-gray">
      <div>
        <p class="text-gray text-center">
            En LG, nos enorgullece ser la marca número uno en lavadoras de carga frontal en más de 30 países, incluyendo Estados Unidos, Australia y Corea del Sur. Nuestro compromiso es <br>
            ofrecerte no solo equipos de alta calidad, sino también soluciones innovadoras que cuidan de tu bolsillo y del medio ambiente. Gracias a nuestra tecnología avanzada y eficiencia <br>
            energética mejorada, nuestras soluciones de lavandería profesional no solo brindan un rendimiento de limpieza superior, sino que también ayudan a reducir el consumo de agua y <br>

            energía. Con LG, puedes disfrutar de resultados impecables mientras mantienes tus facturas más bajas y contribuyes a un planeta más verde.
        </p>
      </div>
    </div>
</template>
  
<script>
    export default {
        name: 'SectionTextGrayComponent'
    }
</script>
  
<style scoped>
    .section-gray {
        background-color: #EEEEEE;
        width: 100%;
        padding: 20px;
        height: auto;
    }
    
    .text-gray {
        color: #202020;
        font-weight: 500;
    }
    
    @media (max-width: 768px) {
        .text-gray {
            font-size: 14px;
        }
    }
    
    @media (min-width: 768px) {
        .text-gray {
            font-size: 16px;
        }
    }
</style>
  