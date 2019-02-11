<template>
  <header class="sticky-top">
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark py-lg-4" id="mainNav">
      <div class="container">
        <router-link class="navbar-brand text-uppercase text-expanded font-weight-bold d-lg-none" to="/">
          <img src="@/assets/logo-web.png" alt="Los Postres de Mamá" width="100"/>
        </router-link>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive"
          aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav mx-auto">
            <li class="nav-item px-lg-4">
              <router-link class="nav-link text-uppercase text-expanded" to="/">Inicio</router-link>
            </li>
            <li class="nav-item px-lg-4">
              <router-link class="nav-link text-uppercase text-expanded" to="/about">Sobre nosotros</router-link>
            </li>
            <li class="nav-item px-lg-4">
              <router-link class="nav-link text-uppercase text-expanded" to="/products">Productos</router-link>
            </li>
            <li class="nav-item px-lg-4">
              <router-link class="nav-link text-uppercase text-expanded" to="/contact">Contáctanos</router-link>
            </li>
          </ul>
        </div>

      </div>
    </nav>
  </header>
</template>
