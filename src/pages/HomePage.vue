<template>
  <div class="container-fluid">
    <div class="container-fluid" id="rowBg">
      <div class=".container">
        <div class="row pt-5 pb-3">
          <div class="col-12 align-items-center">
            <div class="card mb-3" style="max-width: 45rem;">
              <div class="card-body mx-auto">
                <h4 class="card-title">
                  <b>RELAX & CONNECT WITH YOUR HOLISTIC BEAUTY</b>
                </h4>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-12 text-center">
          <img src="https://images.squarespace-cdn.com/content/v1/600cfbb4f983552f0a570c8e/1614192594660-6Y3OYEUDO0IVYZ0PW52T/ke17ZwdGBToddI8pDm48kC2n6b4B5djcgIa_nCe7vYt7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1UVATma4DTdtI8LeBCGG2CDImoP4hsGpBm45ZXmiL2FcDmVtPpR5HH5ikMffD2gaGnw/IMG_1867.jpg" alt="">
        </div>
      </div>

      <div class="row pt-5">
        <div class="col-12 text-center pt-5 pb-3">
          <h3 class="card p-5" style="max-width: 35rem;">
            <b>YOU’RE IN THE RIGHT PLACE!</b>
          </h3>
        </div>
      </div>

      <div class="row p-5">
        <div class="col-4 text-center">
          <div class="card p-4" style="max-width: 20rem;">
            <h4>NEW TO THE SALON?</h4>
          </div>
          <div class="card p-4" style="max-width: 20rem;">
            <p>Get an idea of what to expect, from booking to the end of your visit.</p>
          </div>
          <button type="button" class="btn btn-dark btn-outline-light">
            New Guest Page
          </button>
        <!-- END OF FIRST AREA -->
        </div>
        <div class="col-4 text-center">
          <h4 class="card p-4" style="max-width: 20rem;">
            EASY SCHEDULING
          </h4>
          <p class="card p-4" style="max-width: 20rem;">
            Request an appointment online, or contact me directly with questions.
          </p>
          <button type="button" class="btn btn-dark btn-outline-light">
            Book Online
          </button>
        <!-- END OF SECOND AREA -->
        </div>
        <div class="col-4 text-center">
          <h4 class="card p-4" style="max-width: 20rem;">
            GET TO KNOW ME!
          </h4>

          <p class="card p-4" style="max-width: 20rem;">
            Connect with my values and passions, I cant wait to hear about yours!
          </p>
          <button type="button" class="btn btn-dark btn-outline-light">
            About
          </button>
        </div>
      </div>
    </div>

    <!-- EMAIL AREA -->
    <div class="container-fluid" id="newBg">
      <div class="row pt-1">
        <div class="col text-center p-5">
          <h3>
            <b>NEVER MISS AN UPDATE.</b>
          </h3>
        </div>
      </div>
      <div class="row p-5">
        <div class="col-12 justify-content-center">
          <form>
            <div class="form-group">
              <label for="exampleInputPassword1">First Name</label>
              <input type="password" class="form-control" id="input2" placeholder="Enter First Name">
            </div>
            <div class="form-group">
              <label for="exampleInputPassword1">Last Name</label>
              <input type="password" class="form-control" id="input2" placeholder="Enter Last Name">
            </div>
            <div class="form-group">
              <label for="exampleInputEmail1">Email address</label>
              <input type="email" class="form-control" id="input1" aria-describedby="emailHelp" placeholder="Enter email">
              <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
            </div>

            <button type="submit" class="btn btn-dark text-light">
              Sign Up
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Arapey&display=swap');
.home{
  text-align: center;
  user-select: none;
  > img{
    height: 200px;
    width: 200px;
  }

}
#rowBg{
  background-image: url("https://png.pngtree.com/thumb_back/fw800/background/20190619/pngtree-herbal-leaf-pattern-seamless-image_130677.jpg");
    color: rgb(219, 219, 219);
font-family: 'Tenor Sans', sans-serif;
}
#newBg{
background-image: url("https://c1.wallpaperflare.com/preview/419/429/240/leaf-plant-eucalyptus-green.jpg");
background-size: cover;
    color: rgb(46, 46, 46);
font-family: 'Tenor Sans', sans-serif;
}
.card{
 background: rgba(46, 46, 46, 0.8);
  border-radius: 10px;
  margin: 0 auto; /* Added */
  float: none; /* Added */
  margin-bottom: 10px; /* Added */
}
.card-body{
  color: white;
}
.container-fluid{
  padding-left: 0rem;
  padding-right: 0rem;
  overflow: hidden;
}
#input1{
  width: 30%;
}
#input2{
  width: 20%;
}
// .wrapper{
// height: 100vh;
// // background-image:url("https://www.alexseal.com/wp-content/gallery/topcoat/swatch_t7153.gif");
// background-size: cover;
// background-position: fixed;
// background-repeat: no-repeat;
// }
// .banner{
// width: 600px;
// height: 350px;
// background: inherit;
// position: absolute;
// overflow: hidden;
// top: 50%;
// left: 50%;
// border-radius: 5px;
// transform: translate(-50%,-50%);
// }
// .banner:before{
//   width: 650px;
//   height: 400px;
//   content: '';
//   position: absolute;
//   top: -25px;
//   left: -25px;
//   bottom: 0;
//   right: 0;
//   background: inherit;
//   box-shadow: inset 0 0 0 500px rgba(255,255,255,0.2);
//   filter: blur(10px);
// }
// .img-text{
// position: absolute;
// top: 50%;
// left: 50%;
// transform: translate(-50%,-50%);
// text-align: center;
// width: 500px;
// }
</style>
