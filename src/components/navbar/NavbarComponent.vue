<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-body-tertiary border-body border-bottom shadow-lg p-4">
        <div class="container">
            <a href="/" class="navbar-brand">
                <img src="/public/img/LogoGrisSitio.png" alt="Logo" class="img-fluid">
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a href="https://lglaundry.mx/" class="nav-link active">Inicio</a>
                    </li>   
                </ul>
            </div>
        </div>
    </nav>
  </div> 
</template>

<script>
export default {
    name: 'NavbarComponent'
}
</script>

<style scoped>
    .nav-link {
        color: #EA1E63 !important;
        font-size: 20px !important;
        font-weight: 400;
    }

    .bg-body-tertiary {
        background-color: #FFFFFF !important;
    }
</style>