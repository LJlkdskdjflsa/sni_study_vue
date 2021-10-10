<template>
  <nav
    class="navbar is-info"
    role="navigation"
    aria-label="main navigation"
    style="min-height: 5rem;"
  >
    <div class="navbar-brand">
      <a class="navbar-item is-size-4" href="/">Sni Study</a>
    </div>
    <div id="navbar-item" class="navbar-menu">
      <div class="navbar-start">
        <a href="/" class="navbar-item">Home</a>
        <a href="/about" class="navbar-item">About</a>
      </div>
    </div>
    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a href="/sign-up" class="button is-primary">
            <strong>Sign up</strong>
          </a>

          <a class="button is-primary">
            <strong>Login</strong>
          </a>
        </div>
      </div>
    </div>
  </nav>
  <router-view />
  <footer class="footer">
    <p class="has-text-center">Copyright (c) 2021</p>
  </footer>
</template>

<style lang="scss">
@import "../node_modules/bulma";
</style>
