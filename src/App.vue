<template>
  <div id="app">
    <div class="content">
      <nav class="navbar navbar-dark bg-first navbar-expand-lg mb-5">
        <a class="navbar-brand">Sebastian Smoliński</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item">
              <router-link class="nav-link" to="/home" active-class="active">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/contact" active-class="active">Kontakt</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/projects" active-class="active">Projekty</router-link>
            </li>
          </ul>
        </div>
      </nav>

      <div class="container">
        <router-view></router-view>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
.navbar-brand {
  font-size: 1.75rem;
}

.nav-link {
  font-size: 1.25rem;
}

.bg-first {
  background-color: #29b6f6;
}
</style>
