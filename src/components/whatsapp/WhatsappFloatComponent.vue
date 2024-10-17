<template>
    <div>
      <a href="https://api.whatsapp.com/send?phone=5213319712408&text=Hola,%20Necesito%20m%C3%A1s%20informaci%C3%B3n." class="float shadow-lg" target="_blank">
          <i class="fab fa-whatsapp my-float shadow-lg"></i>
        </a>
    </div>
  </template>
  
  <script>
  export default {
      name: 'WhatsappFloatComponent'
  }
  </script>
  
  <style scoped>
       .float{
          position:fixed;
          width:60px;
          height:60px;
          bottom:40px;
          right:40px;
          background-color:#25d366;
          color:#FFF;
          border-radius:50px;
          text-align:center;
          font-size:30px;
          box-shadow: 2px 2px 3px #999;
          z-index:100;
      }
  
      .my-float{
          margin-top:16px;
      }
  </style>