<template>
  <div class="container">
    <div class="header">
      <div class="header-left">
        <h1 class="text-dark">
          探索<span class="border-bottom border-warning border-2">台灣之美</span><br />
          讓我們更親近這片土地
        </h1>
        <p>台灣旅遊景點導覽<span>Taiwan Travel Guide</span></p>
      </div>
    </div>
    <Carousel />
  </div>
</template>

<script>
// @ is an alias to /src
import Carousel from '@/components/Carousel.vue';

export default {
  name: 'Home',
  components: {
    Carousel,
  },
};
</script>

<style lang="scss">
.header-left {
  margin-top: 82px;
  margin-left: 95px;
  h1 {
    line-height: 69.5px;
  }
}
</style>
