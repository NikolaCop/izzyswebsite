<template>
  <div class="container-fluid" id="rowBg">
    <div class="row pt-5 pb-3">
      <div class="col-12 text-center">
        <h5>RELAX & CONNECT WITH YOUR HOLISTIC BEAUTY</h5>
      </div>
    </div>

    <div class="row">
      <div class="col-12 text-center">
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALEAAAEcCAMAAAC/AqVzAAAANlBMVEXMzMzPz8+RkZHLy8u4uLiUlJS1tbXDw8Ojo6O6urrHx8fAwMCPj4+ZmZmpqam8vLyfn5+vr6+0FCexAAADI0lEQVR4nO3d2XLbOBCFYTT2RSSA93/ZaXCZUuy4khvTM1X/50Shya7oAARbvKKMAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAID/HxG5N/6+5OvabyNyxah7jmtD0p77b3OsI/PY0Npy1Lac28OZ28ta+5piatAN/dektcP/LsY6YsdVYtfw+trozybuYc85eyO7bWa31cjYqhnBfS7VI8lM60VGSCZriWzDuW17dJIljnNVuKDz60KUavV813vijjD3Wl3TKtuuJX6VeGmvJvqSHk287+cyTut9JWcpVqdXtnmk7NvKtsUz8goqY5eup+KIHsM6EOKTkyx5zjzdWpEr6Nz0jzmjH8fHpoO6l8g29FLTiY5rh+xZ9rWo1xieTDzWBRecRLveXCdtHimOLGZdmLHaew5b2HIYx7hWyXaOS/Kzie2o4u11glfuc97mlVjylre7OG06unwnnv8mzo9eeu04wcF8Mcer6d3dy4WRXNEO+DHxo3N8NoP+cl+sY128oV5b/VVljU7HZc5B/cQ6rkdn0rjJ3r0ivPUKHUMIV3jxLzlfz14xfqZX6LwdF9HRivXNpzbbvpptOY87O6N+tLzVznC3bH+24vRqDwbWRNlpC9amvIcq92ee5Kuh6R6nTe2cQ13HVVrQ2rtEgn7mjfDsMp7a2+zmjkss2LUi29pzneikdxy6Ds4Jl/jSI2tZp1Wy1k2xIdyn47HIMY95TGjKIx57Wh73jVCP61D0V23PY69XyXmf1/MX93nfGfntnvfjxn1f8V78aeOBjAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/Ld8fjpvdSb9UvBLyYfn/T7Pzfj+m/6V4uR6ZLJp0vps06W4HrnuYpQeW2lm/mBk10qJzZfafKyzxVjj7iTGUpwOZe9TvEQfi1+PLde5jeJLLI8+rfxj4j1551vcze6rl92n4jWxi7KeR61p9cf3VtY3NPRaJZpYkvd//o+/L3EV551LzdSiy1dfmsZJpcrxbSPnj0jSdZFM6VKjS0Ye/b6Lv9Xrn2vw3f4BfUgXGiU+0vsAAAAASUVORK5CYII=" alt="">
      </div>
    </div>

    <div class="row pt-5">
      <div class="col-12 text-center pt-5 pb-3">
        <h5>
          YOU’RE IN THE RIGHT PLACE!
        </h5>
      </div>
    </div>

    <div class="row" id="newBg">
      <div class="col-12 text-center p-5">
        <h3>
          NEVER MISS AN UPDATE.
        </h3>
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
          <div class="form-check">
            <input type="checkbox" class="form-check-input" id="exampleCheck1">
            <label class="form-check-label" for="exampleCheck1">Check me out</label>
          </div>
          <button type="submit" class="btn btn-primary">
            Submit
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
  background-color: rgb(65, 75, 48);
    color: rgb(219, 219, 219);
font-family: 'Tenor Sans', sans-serif;
}
#newBg{
background-image: url("https://i.pinimg.com/originals/78/9d/10/789d108ae0ba9a93266170031c109189.jpg");
background-size: cover;
    color: rgb(46, 46, 46);
font-family: 'Tenor Sans', sans-serif;
}
</style>
