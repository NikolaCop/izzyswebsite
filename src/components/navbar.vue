<template>
  <div class="container-fluid" id="rowBg">
    <nav class="navbar navbar-expand-lg navbar-light ">
      <!-- <a class="navbar-brand" href="#">IZZY, HAIR ARTIST</a>  //NOTE MAKE THIS APPEAR ON MOBILE. -->
      <button class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#navbarNavAltMarkup"
              aria-controls="navbarNavAltMarkup"
              aria-expanded="false"
              aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-item nav-link active text-white" href="#">Home <span class="sr-only">(current)</span></a>
          <a class="nav-item nav-link text-white" href="#">About</a>
          <a class="nav-item nav-link text-white" href="#">Services</a>
          <a class="nav-item nav-link text-white" href="#">Gallery</a>
          <a class="nav-item nav-link text-white" href="#">Book Online</a>
          <a class="nav-item nav-link text-white" href="#">New Guest</a>
          <a class="nav-item nav-link text-white" href="#">Contact</a>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
import { AuthService } from '../services/AuthService'
import { AppState } from '../AppState'
import { computed, reactive } from 'vue'
export default {
  name: 'Navbar',
  setup() {
    const state = reactive({
      dropOpen: false
    })
    return {
      state,
      user: computed(() => AppState.user),
      async login() {
        AuthService.loginWithPopup()
      },
      async logout() {
        await AuthService.logout({ returnTo: window.location.origin })
      }
    }
  }
}
</script>

<style scoped>
.dropdown-menu {
  user-select: none;
  display: block;
  transform: scale(0);
  transition: all 0.15s linear;
}
.dropdown-menu.show {
  transform: scale(1);
}
.hoverable {
  cursor: pointer;
}
a:hover {
  text-decoration: none;
}
.nav-link{
  text-transform: uppercase;
}
.nav-item .nav-link.router-link-exact-active{
  color: var(--primary);
}
@import url('https://fonts.googleapis.com/css2?family=Arapey&display=swap');
#rowBg{
  background-color: rgb(38, 39, 35);
  color: rgb(219, 219, 219);
font-family: 'Tenor Sans', sans-serif;
}
</style>
