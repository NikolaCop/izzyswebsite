<template>
  <div class="contactModal container-fluid">
    <div
      class="modal fade"
      id="contactModal"
      tabindex="-1"
      role="dialog"
      aria-labelledby="modalTitleId"
      aria-hidden="true"
    >
      <div class="modal-dialog  modal-dialog-centered modal-lg" role="document">
        <div class="modal-content">
          <div class="modal-body">
            <div class="row pl-5 pb-3 pt-3">
              <h2>CONTACT ME</h2>
            </div>
            <div class="row">
              <div class="col-6 pl-5">
                <p>For appointment inquires and other questions please feel free to reach out in any of these places. If you know what services you’d like to receive, or would like to come in for a complimentary consultation , you can go ahead and request your appointment now.</p>
              </div>
              <div class="col-6 pt-3">
                <h5>
                  <i class="fab fa-instagram"></i> HAIRARTISTIZZY
                </h5>
                <br>
                <h5>
                  <i class="fas fa-envelope-open-text"></i> HAIRARTISTIZZY@GMAIL.COM
                </h5>
                <br>
                <h5>
                  <i class="fas fa-phone-alt"></i> 208 391 7534
                </h5>
              </div>
            </div>
            <div class="row pt-3 pr-5 pl-5">
              <i class="fas fa-undo-alt"></i>
              <p class="tinyWords pl-">
                Ok, Take Me Back
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: '',
  props: [],
  setup() {
    return {}
  },
  components: {}
}
</script>
<style scoped>
#contactModal{
  color: rgb(46, 46, 46);
}
.modal-body{
    background-image: url("https://images.unsplash.com/photo-1610653216265-74079d187414?ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8YmVpZ2V8ZW58MHx8MHx8&ixlib=rb-1.2.1&w=1000&q=80");
    background-size: cover;

}

.tinyWords{
  font-size: xx-small;
}
</style>
