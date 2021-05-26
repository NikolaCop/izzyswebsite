<template>
  <div class="newModal container-fluid">
    <div
      class="modal fade"
      id="newModal"
      tabindex="-1"
      role="dialog"
      aria-labelledby="modalTitleId"
      aria-hidden="true"
    >
      <div class="modal-dialog  modal-dialog-centered modal-xl" role="document">
        <div class="modal-content">
          <div class="modal-body">
            <div class="row p-5">
              <div class="col-6 pl-5">
                <h3>HI! I’M SO GLAD YOU’RE HERE.</h3>
                <img src="https://images.squarespace-cdn.com/content/v1/600cfbb4f983552f0a570c8e/1614192594660-6Y3OYEUDO0IVYZ0PW52T/ke17ZwdGBToddI8pDm48kC2n6b4B5djcgIa_nCe7vYt7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1UVATma4DTdtI8LeBCGG2CDImoP4hsGpBm45ZXmiL2FcDmVtPpR5HH5ikMffD2gaGnw/IMG_1867.jpg" class="img-fluid ${3|rounded-top,rounded-right,rounded-bottom,rounded-left,rounded-circle,|}" alt="">
              </div>
              <div class="col-6 pt-3">
                <p>
                  Going to a hairstylist for the first time can be a bit nerve wracking. I want you to know that from the moment you fall on this page, to the moment you leave my chair, you and your hair will be taken care of.

                  I can't wait to meet you! The experience starts when you use the online booking request below. Your appointment request will be received and you will then receive a confirmation within 24 hours to confirm your appointment.

                  Next, you will arrive at the studio, parking with ease in our private lot.  Come inside and take a seat, and I will bring you to my chair! At this time, we will go through about a 15 minute consultation process. We will plan out, not just your first visit, but a long term plan to ensure all your hair goals are met. I will go over all pricing before we begin your services! Please know that I will truly listen and care, I want you to have the most relaxing and restorative experience possible!

                  If you're here for a color, a formula will be custom blended for you and recorded. This gives me a history of what we do together which will create consistent results and seamless transitions for any fun future changes! I have plenty of amenities to help you stay comfy as your color processes.

                  If you are here for a cut, I will create a shape that is perfect for your features, lifestyle and overall hair goals. I will finish with a beautiful style, and share pointers for your own at-home styling.

                  We'll wrap up the visit by sharing my recommendations for at-home care and set you up with your next visit!
                </p>
              </div>
            </div>
            <div class="row pt-3 pr-5 pl-5">
              <i class="fas fa-undo-alt"></i>
              <p class="tinyWords pl-">
                Ok, Take Me Back to the Hompage
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
    background-image: url("https://www.wallpapertip.com/wmimgs/11-112111_wallpaper-grey-blue-gradient-linear-light-blue-gray.jpg");
    background-size: cover;

}

.tinyWords{
  font-size: xx-small;
}
</style>
