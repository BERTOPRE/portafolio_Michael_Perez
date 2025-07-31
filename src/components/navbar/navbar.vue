<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <!-- <a class="navbar-brand" href="/">MPDev</a> -->
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/" class="nav-link">Inicio</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/sobre-nosotros" class="nav-link">Mis tecnologías</router-link>
          </li>
          <li class="nav-item">
            <router-link to="#" class="nav-link">Portafolio</router-link>
          </li>
        </ul>
        <button type="button" class="btn btn-primary" id="btn-contact">Contáctame</button>
      </div>
    </div>
  </nav>
</template>
