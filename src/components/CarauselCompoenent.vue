<template>
  <div id="carousel">
    <div
      class="container carousel slide"
      id="carouselExampleIndicators"
      data-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            class="d-block w-300"
            src="https://picsum.photos/1200/300/?auto=yes&bg=777&fg=555&text=First slide"
            alt="First slide"
          />
        </div>
        <div class="carousel-item">
          <h1>Slide Two</h1>
        </div>
        <div class="carousel-item">
          <h1>Slide There</h1>
        </div>
      </div>
      <a
        href="#carouselExampleIndicators"
        class="carousel-control-prev"
        role="button"
        data-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      </a>
      <a
        href="#carouselExampleIndicators"
        class="carousel-control-next"
        role="button"
        data-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
      </a>

      <ol class="carousel-indicators">
        <li
          class="active"
          data-target="#carouselExampleIndicators"
          data-slide-to="0"
        ></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
      </ol>
    </div>
  </div>
</template>

<style>
#carousel {
  background: #000;
  color: yellowgreen;
}
</style>
