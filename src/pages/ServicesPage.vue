<template>
  <div class="container-fluid">
    <div class="ServicesPage">
      <div class="row pt-5 pl-5">
        <div class="col-4">
          <button type="button" class="btn btn-dark btn-outline-light" id="bookOnlineBTN" data-toggle="modal" data-target="#bookOnlineModal">
            Book Online!
          </button>
        </div>
        <div class="col-6">
          <h5>
            ALL COLOR PRICES ARE STARTING PRICES AND MAY INCREASE IF YOU HAVE PARTICULARLY LONG OR THICK HAIR.
          </h5>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ServicesPage',
  props: [],
  setup() {
    return {}
  },
  components: {}
}
</script>
<style scoped>
.container-fluid{
  background-image: url("https://st4.depositphotos.com/5837058/24054/v/600/depositphotos_240548206-stock-illustration-cream-gradient-background-decor.jpg");
  background-size: cover;
     font-family: 'Tenor Sans', sans-serif;
}
#bookOnlineBTN{
  width: 150px;
  height: 85px;
}
</style>
