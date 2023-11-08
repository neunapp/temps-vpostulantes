<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">

    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-start">
        <a class="navbar-item">
          Inicio  
        </a>

        <a class="navbar-item">
          Postulantes
        </a>
        <a class="navbar-item">
          Empleados
        </a>
      </div>
    </div>
  </nav>
  <div class="columns is-centered" style="padding: 2em;">
    <router-view/>
  </div>
  
</template>

<style lang="scss">
.app {

}
</style>
