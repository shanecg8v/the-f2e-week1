<template>
  <div id="carousel" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button
        type="button"
        data-bs-target="#carousel"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#carousel"
        data-bs-slide-to="1"
        aria-label="Slide 2"
      ></button>
      <button
        type="button"
        data-bs-target="#carousel"
        data-bs-slide-to="2"
        aria-label="Slide 3"
      ></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          src="https://source.unsplash.com/user/erondu/1600x900"
          class="carousel-img w-100"
          alt="..."
        />
        <div class="carousel-caption d-none d-md-block">
          <h5>First | qwe</h5>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="https://source.unsplash.com/collection/190727/1600x900"
          class="carousel-img w-100"
          alt="..."
        />
      </div>
      <div class="carousel-item">
        <img
          src="https://source.unsplash.com/collection/190727/1600x900"
          class="carousel-img w-100"
          alt="..."
        />
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carousel"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carousel"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>

<script>
export default {
  name: 'Carousel',
  data() {
    return {};
  },
};
</script>

<style lang="scss">
.carousel-img {
  height: 400px;
  border-radius: 1.5rem;
}
.carousel-caption {
  bottom: 41%;
}
</style>
