<template>
  <div class="slide-show">
    <carousel
      :per-page="1"
      :mouse-drag="false"
      :autoplay="true"
      :loop="true"
      :speed="2000"
      :autoplayTimeout="6000"
      :navigate-to="someLocalProperty"
    >
      <slide>
        <img src="../assets/office1.jpg" alt="" />
      </slide>
      <slide>
        <img src="../assets/office2.jpg" alt="" />
      </slide>
      <slide>
        <img src="../assets/office3.jpg" alt="" />
      </slide>
    </carousel>
  </div>
</template>

<script>
export default {
  name: "SlideShow",
  components: {},
};
</script>

<style lang="scss">
.slide-show {
  margin-top: 10px;
  img {
    max-width: 1100px;
  }
}
</style>
