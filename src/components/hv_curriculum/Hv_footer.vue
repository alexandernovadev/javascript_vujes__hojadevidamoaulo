<template>
  <footer :class="`w3-container w3-${color} w3-center `">
  <p>Find me on social media.{{color}} </p>
  <i class="fa fa-facebook-official w3-hover-opacity"></i>
  <i class="fa fa-instagram w3-hover-opacity"></i>
  <i class="fa fa-snapchat w3-hover-opacity"></i>
  <i class="fa fa-pinterest-p w3-hover-opacity"></i>
  <i class="fa fa-twitter w3-hover-opacity"></i>
  <i class="fa fa-linkedin w3-hover-opacity"></i>
  <p>Hecha con VueJS / W3CSS</p>
</footer>
</template>

<script>
export default {
    name:'hvfooter',
    props: ['color'],
}
</script>

<style>

</style>