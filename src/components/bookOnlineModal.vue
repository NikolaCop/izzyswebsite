<template>
  <div class="bookOnlineModal container-fluid">
    <div
      class="modal fade"
      id="bookOnlineModal"
      tabindex="-1"
      role="dialog"
      aria-labelledby="modalTitleId"
      aria-hidden="true"
    >
      <div class="modal-dialog  modal-dialog-centered modal-lg" role="document">
        <div class="modal-content">
          <div class="modal-body">
            <div class="row">
              <h3 class=" pl-3">
                <i> CANCELLATION ETIQUETTE </i>
              </h3>
            </div>
            <div class="row">
              <div class="col-8 pr-5">
                <h5 class="pl-1">
                  Please reschedule or cancel at least 24 hours before your appointment begins to avoid any late cancellation fees. If less than 24 hours notice is given you may be charged 50% of the total value of the appointment you have missed. Thank you!
                </h5>
              </div>
            </div>
            <div class="row p-5">
              <div class="col-12 pt-3 pb-2">
                <button type="button" class="bookOnline btn btn-dark btn-outline-light" onclick="location.href='https://square.site/book/LQQMA9RZJC609/izzy-hair-artist-boise-id';">
                  BOOK ONLINE!
                </button>
              </div>
            </div>
            <div class="row pt-3 pr-5 pl-5">
              <i class="fas fa-undo-alt"></i>
              <p class="tinyWords pl-2">
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
#bookOnlineModal{
  color: rgb(46, 46, 46);
}
.modal-body{
    background-image: url("https://img.rawpixel.com/s3fs-private/rawpixel_images/website_content/pdflowerset17-tang-01a_1.jpg?w=800&dpr=1&fit=default&crop=default&q=65&vib=3&con=3&usm=15&bg=F4F4F3&ixlib=js-2.2.1&s=41ed6d28fced529a495837a378f8cf9b");
    background-size: cover;
}
.bookOnline{
  height: 75px;
  width: 175px;
  border-radius: 5px;
}
.tinyWords{
  font-size: xx-small;
}
</style>
