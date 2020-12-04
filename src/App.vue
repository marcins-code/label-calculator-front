<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>

  <ul class="list-inline">
    <li class="list-inline-item">Lorem ipsum</li>
    <li class="list-inline-item">Phasellus iaculis</li>
    <li class="list-inline-item">Nulla volutpat</li>
  </ul>
  <router-view />
  <div class="alert alert-warning alert-dismissible fade show" role="alert">
    <strong>Holy guacamole!</strong> You should check in on some of those fields
    below.
    <button
      type="button"
      class="btn-close"
      data-dismiss="alert"
      aria-label="Close"
    ></button>
  </div>
</template>

<style lang="scss">
@import "./assets/scss/bootstrap/bootstrap.scss";
</style>
