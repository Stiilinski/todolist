<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav class="navbar navbar-expand-lg bg-dark navbar-dark">
        <div class="container">
          <RouterLink class="navbar-brand" to="/">TODOLIST</RouterLink>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <RouterLink class="nav-link" to="/todolist">Dashboard</RouterLink>
              </li>
            </ul>
          </div>
        </div>
      </nav>

    </div>
  </header>

  <RouterView />

</template>
<script>
export default {
  
}
</script>
