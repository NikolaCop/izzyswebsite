<template>
  <header>
    <div class="row" id="rowBg">
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
#rowBg{
  background-color: rgb(85, 104, 52);
  color: rgb(219, 219, 219);
}
</style>
