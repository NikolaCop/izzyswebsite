<template>
  <div class="CreateKeepModal container-fluid">
    <div
      class="modal fade"
      id="bookOnline"
      tabindex="-1"
      role="dialog"
      aria-labelledby="modalTitleId"
      aria-hidden="true"
    >
      <div class="modal-dialog  modal-dialog-centered modal-lg" role="document">
        <div class="modal-content">
          <div class="modal-header">
            <h3 class="modal-title">
              CANCELLATION ETIQUETTE
            </h3>
            <button
              type="button"
              class="close"
              data-dismiss="modal"
              aria-label="Close"
            >
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            <h5>Please reschedule or cancel at least 24 hours before your appointment begins to avoid any late cancellation fee. If less than 24 hours notice is given you may be charged 50% of the total value of the appointment you have missed. Thank you!</h5>
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
