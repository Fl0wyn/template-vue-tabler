<template>
  <header class="navbar navbar-expand-md navbar-light d-print-none">
    <div class="container-xl">
      <!-- Logo -->
      <h1
        class="
          navbar-brand navbar-brand-autodark
          d-none-navbar-horizontal
          pe-0 pe-md-3
        "
      >
        <a href=".">
          <img
            src="/logo.svg"
            alt="Tabler"
            class="navbar-brand-image"
            width="110"
            height="32"
          />
        </a>
      </h1>
      <!-- Button -->
      <div class="navbar-nav flex-row order-md-last">
        <div class="nav-item d-none d-md-flex me-3">
          <div class="btn-list">
            <a
              href="https://github.com/fl0wyn/template-vue-tabler"
              class="btn"
              target="_blank"
              rel="noreferrer"
            >
              Source code
            </a>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>
