<template>
  <div class="GalleryPage">
    <div class="row">
      <div class="col-12 p-5">
        View more on Instagram!
      </div>
    </div>
    <div class="row">
      <div class="masonry">
        <div class="item">
          <img src="https://cdn.shopify.com/s/files/1/0533/2089/files/placeholder-images-image_large.png?format=webp&v=1530129081" alt="">
        </div>
        <div class="item">
          <img src="https://www.rev6sports.com/wp-content/uploads/2015/04/placeholder-200x200.png" alt="">
        </div>
        <div class="item">
          <img src="data:image/png;base64,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" alt="">
        </div>
        <div class="item">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        </div>
        <div class="item">
          <img src="data:image/png;base64,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" alt="">
        </div>
        <div class="item">
          <img src="https://cdn.shopify.com/s/files/1/0533/2089/files/placeholder-images-image_large.png?format=webp&v=1530129081" alt="">
        </div>
        <div class="item">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        </div>
        <div class="item">
          <img src="data:image/png;base64,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" alt="">
        </div>
        <div class="item">
          <img src="https://www.rev6sports.com/wp-content/uploads/2015/04/placeholder-200x200.png" alt="">
        </div>
        <div class="item">
          <img src="https://cdn.shopify.com/s/files/1/0533/2089/files/placeholder-images-image_large.png?format=webp&v=1530129081" alt="">
        </div>
        <div class="item">
          <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAPFBMVEXi4uKenp7h4eHl5eWbm5uysrK4uLje3t7Hx8fS0tLb29ulpaWZmZnOzs67u7uurq7CwsLW1taoqKjr6+smf25RAAAGbklEQVR4nO2ah5bkKAxFDQIHnF3//68rCYxDuXpmQzez57w7Z7oLHIpngQLuqgIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADADVsRyc8Mpe7UIKL7JW8d+QC9n02Jz1d9O2vXdU1udULYW/bajML1AmurGxTayddTG84iuzPN/ZKfgebBDeM+qMY454Yt2ZCmQZrjachscuOGYabqJrHxcimfbeqQz6feHQzdt4t5hLwxbszjNIJLmpr+3Ernj467XLjdpeudSTiTL6DeHLiiCg8bKtFEtLi7Qjbhpn3TdVl1Rk5VU/Gv9qLwz7DhTaE+blsZc1fIqzDZ6ryoKOh58xhCVxtX0z6DRaGb2sTN7j/Fs8L5xdZq3btCqlNne+6cxHKLuBiidT7Ei8Jhze60DI8KeVjc6B9sGGQ6zty7ne4hV7HlKnVQbMDshNSG3d0p/TBvCqONPFWje7ehLE23iUweeF5t43CdtvYyS3cblhL6YEOZcyaoS/HzzdPIkNsXLzY3H6tNZM9HiKhO0eLkS9tC0/RBYVD/0MnaWq8K49JsaNVj2Yb8SJzfBXftmH1KVPiwcn+SB4VWokS/icOhs0J2PtKcXvSaXVp4eouoMDU2jgu7mKQwBos/SGGz+xs3vq42VNv5aZpm+ZBvIZbtd1HzyVy6DuV8pi4UDh8VqvcXf0lXG8q5Muk0rkt4SFfFSZvud1eYo8VPqjrzqDAlb91VYRXiotrzsz7fZOOuLa7Ddxt22igXMZ4UxhDOJqwuCmNvz/9M9JE5nZVp6mY1VsNqn21YyoqPCivrYj5+naUaKhrF1jFCRA9KfhDTzlOt8/jqaWafKORqnhVK3bTRVWF0KDGwU8xP1xQirJ1dWqH66x4tYkI+UYmpaonHNpyrJ6c2tMuyqkI5mvTL/Euj5B8xYOSoX+/L0zmf05tr9VRGIQ+t7/vDhtyIZuJlI0mm73uT3Pxq+Niarxvl1GM3gNZJ5fR1dyw4mvsTS6GFaIVTqzk9aCtHm9Oh04lVUzWnJNvyEwlrCPbiUOyJpmwC/sDzgOyn5h83fgD+79jT7/sCe98q/Zs3LUDe4L513FvZddrj04drLldcvHUBqEoO3h4Ree+Ju/L5NNmDoUvcPrJNys/p7eKSlYVEbt3ok/GFNveO6SOFpZ60mG90Q5CL4E7SAxo1DeAwXy8x6rcpF1jltFj+h3QJl/25rwCctXBSbFqyNA55+Zm4qU2r8UttZPBhkAyaFdazZnNS4XOmWi9eD1PKWKgdvJ9jgtbxR19r6itfMRVTOL2IRlZEndsVcoIWbcRCKGoKQ9D9MpoOhQ0/GD68SXdWaPh26yBFYWesTk/ycpduWD8O4jux8vXsCuRdQ1ZI7ex1wI2Rzc7ORYXqOE4K4yNhOdVFYTps+bAkfFYVSu1VrHqSAkG//lBYT4uX/c2gexOriAtOXyldFLZ9VBiOWVqNqpDNzgq1Sjm+olTmrQ+4OSmUty/t2FdZYbPYOEvtg0JbXRQmG+rE7tIucbRhY8YiCnWWUpSSFTZmDepqokINlLoOVaHnhfabCmOhEddha0q9IfU+rN3mq6xQ6vfGalUYXPYOwW39rJ7GzYz5tUJeh9vm1dPo5k7B3UQpTuXjbkMeOU/Uheyh0FIYxk7GyLN0Xdew5XX4lcKx00ji/Rr6pUyFv0cLnX+7p6Hak/y/ztLD07x+bx3SeR3Ssj1//7cTo0WlPi/bcPZdV/fVrjDUTYoWldrw9zyNrc6+NJ5VhBgP9aMo1H+9n+racA6wR4vGqqepvo4Wepfx2YZVVfDd0/6GhUcUlarbbORNN0d8sYWTBPUh4o8qgSM+3W2YEoJTxI/utaxCnlWxLhhVad/uWdskU+4xa3PjkbVJAsdhPmVt4y1r47ve/36jhELJlH2jQxYHqGao21rfPHzIvKfW6581UC8J/EKaeftb5p0eR6msbdzjFMVqp4k9WiXJLuiX1VNX+0nXpxZhS3eqnuxRPY0y16ktFBDt8WD1r89OTat9e+n/oQI+3uanuvmpAq7s5Yt+mNuOhT12KNLv80bF2y7G9dq3W142m//1UP8h9vMHffRvA3sctH3u/qoLAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADAf8Bfebk7pKqxKa8AAAAASUVORK5CYII=" alt="">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'GalleryPage',
  props: [],
  setup() {
    return {}
  },
  components: {}
}
</script>
<style scoped>
.masonry { /* Masonry container */
  column-count: 4;
  column-gap: 1em;
}

.item { /* Masonry bricks or child elements */
  background-color: #eee;
  display: inline-block;
  margin: 0 0 1em;
  width: 100%;
}
</style>
