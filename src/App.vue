<template>
  <header>
    <div class="row">
      <div class="col-12 text-center">
        <h1>
          IZZY, HAIR ARTIST
        </h1>
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

</style>
