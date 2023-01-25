<template>
  <div
    id="carouselExampleIndicators"
    class="container carousel slide"
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
        <img
          class="d-block w-300"
          src="https://picsum.photos/1200/301/?auto=yes&bg=666&fg=444&text=Second slide"
          alt="Second slide"
        />
      </div>
      <div class="carousel-item">
        <img
          class="d-block w-300"
          src="https://picsum.photos/1200/302/?auto=yes&bg=555&fg=333&text=Third slide"
          alt="Third slide"
        />
      </div>
    </div>
    <a
      class="carousel-control-prev"
      href="#carouselExampleIndicators"
      role="button"
      data-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a
      class="carousel-control-next"
      href="#carouselExampleIndicators"
      role="button"
      data-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
    <ol class="carousel-indicators">
      <li
        data-target="#carouselExampleIndicators"
        data-slide-to="0"
        class="active"
      ></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>
  </div>
  <div class="container">
    <div class="more-line"></div>
  </div>
</template>
