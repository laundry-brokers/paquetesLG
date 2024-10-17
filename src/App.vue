<template>
  <div>
      <NavbarComponent />
      <BannerComponent />
      <SectionDarkComponent />
      <SectionRedComponent />
      <PackInicialComponent />
      <PaqueteEmprendeComponent />
      <PaqueteGanaComponent />
      <SectionTextGrayComponent />
      <SectionIconsComponent />
      <SectionBannerLgComponent />
      <SectionRedLogosComponent />
      <WhatsappFloatComponent />
  </div>
</template>

<script>
  import NavbarComponent from './components/navbar/NavbarComponent.vue';
  import BannerComponent from './components/banner/BannerComponent.vue';
  import SectionDarkComponent from './components/SectionDark/SectionDarkComponent.vue';
  import SectionRedComponent from './components/sectionRed/SectionRedComponent.vue';
  import PackInicialComponent from './components/packInicial/PackInicialComponent.vue';
  import PaqueteEmprendeComponent from './components/paqueteEmprende/PaqueteEmprendeComponent.vue';
  import PaqueteGanaComponent from './components/paqueteGana/PaqueteGanaComponent.vue';
  import SectionTextGrayComponent from './components/sectionGray/SectionTextGrayComponent.vue';
  import SectionIconsComponent from './components/sectionIcons/SectionIconsComponent.vue';
  import SectionBannerLgComponent from './components/sectionBannerLg/SectionBannerLgComponent.vue';
  import SectionRedLogosComponent from './components/sectionRedLogos/SectionRedLogosComponent.vue';
  import WhatsappFloatComponent from './components/whatsapp/WhatsappFloatComponent.vue';

  export default {
    name: 'App',
    components: {
      NavbarComponent,
      BannerComponent,
      SectionDarkComponent,
      SectionRedComponent,
      PackInicialComponent,
      PaqueteEmprendeComponent,
      PaqueteGanaComponent,
      SectionTextGrayComponent,
      SectionIconsComponent,
      SectionBannerLgComponent,
      SectionRedLogosComponent,
      WhatsappFloatComponent,
    }
  }
</script>