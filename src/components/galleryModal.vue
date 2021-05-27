<template>
  <div class="galleryModal container-fluid">
    <div
      class="modal fade"
      id="galleryModal"
      tabindex="-1"
      role="dialog"
      aria-labelledby="modalTitleId"
      aria-hidden="true"
    >
      <div class="modal-dialog  modal-dialog-centered modal-lg" role="document">
        <div class="modal-content">
          <div class="modal-body">
            <div class="row">
              <div class="col-12 text-dark">
                <p>
                  See more @hairartistizzy on Instagram!
                </p>
              </div>
            </div>
            <div class="container">
              <figure>
                <img src="data:image/jpeg;base64,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" alt="A windmill" />
                <figcaption><a href="#">1</a></figcaption>
              </figure>
              <figure>
                <img src="https://scontent.fymy1-2.fna.fbcdn.net/v/t1.6435-9/p720x720/168682950_1821201738036757_8673173439214760545_n.jpg?_nc_cat=103&ccb=1-3&_nc_sid=2d5d41&_nc_ohc=J8JTmzkBSr8AX-zX7V1&_nc_ht=scontent.fymy1-2.fna&tp=6&oh=e633b414902c1e3d5006655d744f71ee&oe=60B1610B" alt="The Clifton Suspension Bridge" />
                <figcaption><a href="#">2</a></figcaption>
              </figure>
              <figure>
                <img src="https://scontent.fymy1-2.fna.fbcdn.net/v/t1.6435-9/s720x720/166221688_1816506601839604_4306298866138574057_n.jpg?_nc_cat=106&ccb=1-3&_nc_sid=2d5d41&_nc_ohc=kTIoSlqC6L4AX8Ugwuz&_nc_ht=scontent.fymy1-2.fna&tp=7&oh=3f5eb7fd73cb004d55a2c525a12a45fd&oe=60B12D08" alt="Sunset and boats" />
                <figcaption><a href="#">3</a></figcaption>
              </figure>
              <figure>
                <img src="https://assets.codepen.io/12005/snowy.jpg" alt="a river in the snow" />
                <figcaption><a href="#">4</a></figcaption>
              </figure>
              <figure>
                <img src="https://assets.codepen.io/12005/bristol-balloons1.jpg" alt="a single checked balloon" />
                <figcaption><a href="#">5</a></figcaption>
              </figure>
              <figure>
                <img src="https://assets.codepen.io/12005/dog-balloon.jpg" alt="a hot air balloon shaped like a dog" />
                <figcaption><a href="#">6</a></figcaption>
              </figure>
              <figure>
                <img src="https://assets.codepen.io/12005/abq-balloons.jpg" alt="View from a hot air balloon of other balloons" />
                <figcaption><a href="#">7</a></figcaption>
              </figure>
              <figure>
                <img src="https://assets.codepen.io/12005/disney-balloon.jpg" alt="a balloon fairground ride" />
                <figcaption><a href="#">8</a></figcaption>
              </figure>
              <figure>
                <img src="https://assets.codepen.io/12005/bristol-harbor.jpg" alt="sunrise over a harbor" />
                <figcaption><a href="#">9</a></figcaption>
              </figure>
              <figure>
                <img src="https://assets.codepen.io/12005/bristol-balloons2.jpg" alt="three hot air balloons in a blue sky" />
                <figcaption><a href="#">10</a></figcaption>
              </figure>
              <figure>
                <img src="https://assets.codepen.io/12005/toronto.jpg" alt="the Toronto light up sign at night" />
                <figcaption><a href="#">11</a></figcaption>
              </figure>
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
body {
  background-color: #000;
  font: 1.1em Arial, Helvetica, sans-serif;
}

img {
  max-width: 100%;
  display: block;
}

figure {
  margin: 0;
  display: grid;
  grid-template-rows: 1fr auto;
  background-color: white;
}

figure > img {
  grid-row: 1 / -1;
  grid-column: 1;
}

figure a {
  color: black;
  text-decoration: none;
}

figcaption {
  grid-row: 2;
  grid-column: 1;
  background-color: rgba(255,255,255,.5);
  padding: .2em .5em;
  justify-self: start;
}

.container {
  display: grid;
  gap: 10px;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: masonry;
  height: 200vh;
  align-tracks: stretch ;
}

.tinyWords{
  font-size: xx-small;
}
</style>
