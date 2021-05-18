<template>
  <div class="container-fluid" id="rowBg">
    <div class="row pt-5 pb-3">
      <div class="col-12 text-center">
        <h5>RELAX & CONNECT WITH YOUR HOLISTIC BEAUTY</h5>
      </div>
    </div>

    <div class="row">
      <div class="col-12 text-center">
        <img src="https://images.squarespace-cdn.com/content/v1/600cfbb4f983552f0a570c8e/1614192594660-6Y3OYEUDO0IVYZ0PW52T/ke17ZwdGBToddI8pDm48kC2n6b4B5djcgIa_nCe7vYt7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1UVATma4DTdtI8LeBCGG2CDImoP4hsGpBm45ZXmiL2FcDmVtPpR5HH5ikMffD2gaGnw/IMG_1867.jpg" alt="">
      </div>
    </div>

    <div class="row pt-5">
      <div class="col-12 text-center pt-5 pb-3">
        <h5>
          YOU’RE IN THE RIGHT PLACE!
        </h5>
      </div>
    </div>

    <div class="row">
      <div class="col-4">
        <h6>NEW TO THE SALON?</h6>
      </div>
      <div class="col-4">
        <h6>EASY SCHEDULING</h6>
      </div>
      <div class="col-4">
        <h6>GET TO KNOW ME!</h6>
      </div>
    </div>

    <div class="row p-5" id="newBg">
      <div class="col-12 text-center p-5">
        <h4>
          NEVER MISS AN UPDATE.
        </h4>
      </div>
      <div class="col-4">
        <form>
          <div class="form-group">
            <label for="exampleInputEmail1">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
            <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
          </div>
          <div class="form-group">
            <label for="exampleInputPassword1">First Name</label>
            <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
          </div>
          <div class="form-group">
            <label for="exampleInputPassword1">Last Name</label>
            <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
          </div>
          <button type="submit" class="btn btn-dark text-light">
            Sign Up
          </button>
        </form>
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
</style>
