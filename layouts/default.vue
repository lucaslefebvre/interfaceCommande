<template>
  <div>
    <nav class="navbar navbar-dark bg-dark">
      <ul class="nav">
        <li class="nav-item active">
          <nuxt-link class="nav-link" to="/">Accueil</nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link class="nav-link" to="/commandes">Commandes</nuxt-link>
        </li>
      </ul>
    </nav>
    <div class="container mt-3 pt-3">
      <Nuxt />
    </div>
  </div>
</template>

<style>
</style>
