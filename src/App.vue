<template>
  <header>
    <div class="row p-4" id="rowBg">
      <div class="col-12 text-center">
        <h3>
          IZZY, HAIR ARTIST
        </h3>
      </div>
    </div>

    <Navbar />
  </header>
  <main>
    <router-view />
  </main>
</template>

<script>
import { computed } from 'vue'
import { AppState } from './AppState'
export default {
  name: 'App',
  setup() {
    return {
      appState: computed(() => AppState)
    }
  }
}
</script>
<style lang="scss">
@import "./assets/scss/main.scss";
@import url('https://fonts.googleapis.com/css2?family=Arapey&display=swap');

#rowBg{
  background-color: rgb(65, 75, 48);
  color: rgb(219, 219, 219);
font-family: 'Tenor Sans', sans-serif;
}
</style>
