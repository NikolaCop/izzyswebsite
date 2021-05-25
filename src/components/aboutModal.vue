<template>
  <div class="aboutModal container-fluid">
    <div
      class="modal fade"
      id="aboutModal"
      tabindex="-1"
      role="dialog"
      aria-labelledby="modalTitleId"
      aria-hidden="true"
    >
      <div class="modal-dialog  modal-dialog-centered modal-xl" role="document">
        <div class="modal-content">
          <div class="modal-body">
            <div class="row p-5">
              <div class="col-12 text-center">
                <h3>
                  <i> HI, I’M IZZY! </i>
                </h3>
              </div>
            </div>
            <div class="row">
              <div class="col-6 pb-5">
                <img src="https://images.squarespace-cdn.com/content/v1/600cfbb4f983552f0a570c8e/1614191074272-LV3RWHM0QP57D11QXLZT/ke17ZwdGBToddI8pDm48kH_jyMKD5dc4sWtT72s84KZ7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1URjVRoTo_44URq6EKQD5UVYVCPirsFZhcxCauxpQwDPfxdLwnFHSFwykx4_DJJxhXw/IMG_1865.jpg?format=1500w" class="img-fluid ${3|rounded-top,rounded-right,rounded-bottom,rounded-left,rounded-circle,|}" alt="">
              </div>
              <div class="col-6 pr-5 pl-5">
                <p>
                  As a hair artist, I believe that guests are looking for more than just  hair color! They are looking for a place they can feel comfortable and welcomed by someone who will understand their needs. My ultimate goal is for you to leave my chair feeling more connected to your inner beauty and totally at home in your hair.
                </p>
                <br>
                <p>
                  My passions are keeping your hair healthy and finding styles that suit your lifestyle & maintenance needs. I am so blessed to start my most recent adventure, this February 2021, renting my own chair and running this sweet little business myself!
                </p>
                <br>
                <p>
                  I thrive on creating relationships with my guests and educating you about your hair.  I am committed to using products and practices that are better for the environment, our community and you!
                </p>
                <br>
                <p>
                  For my color and products  I have chosen to work with Aveda, a Vegan and cruelty free line! Using only certified organic ingredients, no synthetic aromas, and ethical ingredient sourcing, these are non negotiable for myself and my guests!
                </p>
                <br>
              </div>
            </div>
            <div class="row pt-3 pr-5 pl-5">
              <i class="fas fa-undo-alt"></i>
              <p class="tinyWords pl-2">
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
#aboutModal{
  color: rgb(46, 46, 46);
}
.modal-body{
    background-image: url("https://www.teahub.io/photos/full/261-2617153_wallpaper-linear-brown-yellow-gradient-sandy-brown-light.jpg");
    background-size: cover;

}

.tinyWords{
  font-size: xx-small;
}
</style>
