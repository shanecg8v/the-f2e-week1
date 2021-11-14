<template>
  <nav class="navbar navbar-expand-lg navbar-light border-bottom">
    <div class="container">
      <router-link class="navbar-brand" active-class="active" to="/">
        <img src="../assets/img/Logo-desktop.png" alt="" />
      </router-link>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" to="/">探索景點</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" to="/qwe">節慶活動</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" to="/ee">品嚐美食</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
