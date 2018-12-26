<template>
  <div class="container is-fluid">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item is-uppercase has-text-link has-text-weight-bold" href="/">My Portfolio Site</a>
        <button class="button navbar-burger">
          <span></span>
          <span></span>
          <span></span>
        </button>
      </div>
      <div class="navbar-menu">
        <div class="navbar-end has-text-weight-semibold">
          <nuxt-link class="navbar-item has-text-info" to="/">Home</nuxt-link>
          <nuxt-link class="navbar-item" to="/about">About</nuxt-link>
          <nuxt-link class="navbar-item" to="/projects">Projects</nuxt-link>
          <nuxt-link class="navbar-item" to="/contact">Contact</nuxt-link>
        </div>
      </div>
    </nav>
  </div>
</template>