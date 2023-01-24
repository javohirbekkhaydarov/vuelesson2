<script>
import Button from "./Button.vue";
export default {
  name: "HomePage",

  components: {
    Button,
  },
};
</script>

<template>
  <section class="section-component">
    <div class="container">
      <div class="row">
        <div class="col-6">
          <div class="title">
            <p class="home-title-underline">
              Подробнее
              <span class="underline"></span>
            </p>
            <p class="home-title">Azur Life</p>
            <p class="home-title-bottom">
              Это забота о Вас и Вашей недвижимости
            </p>
          </div>

          <div class="col-info">
            <p class="col-info-text">
              Мы готовы Вас приятно удивить особым подходом и, конечно,
              трепетным отношением к каждому клиенту. Мы говорим на Вашем языке,
              так что вы можете лешко и просто оформить сделку дистанционно или
              посетить наш офис. Расскажите нам о своих предпочтениях и мы
              подберем стоящий вариант в самом сердце Французской Ривьеры без
              посредников.
            </p>
          </div>

          <div class="col-numbers">
            <div class="col-number">
              <p class="col-number-title">7</p>
              <p class="col-number-title-info">лет на рынке</p>
            </div>
            <div class="col-number">
              <p class="col-number-title">240</p>
              <p class="col-number-title-info">лет на рынке</p>
            </div>
            <div class="col-number">
              <p class="col-number-title">27</p>
              <p class="col-number-title-info">лет на рынке</p>
            </div>
          </div>
          <div class="col-contact-btn">
            <Button name="Оставить заявку" />
          </div>
        </div>
        <div class="col-6">
          <svg class="home-svg" width="855" height="1013" viewBox="0 0 855 1013" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M469.596 0L816.812 893.656C831.042 929.649 847.169 953.802 865.194 966.115C883.219 977.481 899.821 983.638 915 984.585V1013C896.026 1011.11 872.784 1010.16 845.272 1010.16C817.76 1009.21 790.249 1008.74 762.737 1008.74C725.739 1008.74 691.112 1009.21 658.857 1010.16C626.602 1010.16 600.513 1011.11 580.591 1013V984.585C628.974 982.69 659.806 974.64 673.087 960.432C686.369 945.277 683.523 913.547 664.549 865.241L399.868 159.125L422.636 140.655L175.031 782.837C159.852 820.724 150.84 852.928 147.994 879.449C145.148 905.022 147.519 925.387 155.109 940.541C163.647 955.696 177.403 966.589 196.376 973.219C216.299 979.849 240.964 983.638 270.373 984.585V1013C243.81 1011.11 215.824 1010.16 186.415 1010.16C157.955 1009.21 131.392 1008.74 106.726 1008.74C83.0093 1008.74 62.6127 1009.21 45.5365 1010.16C29.409 1010.16 14.2302 1011.11 0 1013V984.585C18.9736 979.849 38.4215 968.957 58.3437 951.907C78.2659 933.911 96.2908 903.602 112.418 860.979L446.827 0C450.622 0 454.417 0 458.212 0C462.006 0 465.801 0 469.596 0ZM643.204 603.822V632.237H219.145L233.375 603.822H643.204Z" fill="white" fill-opacity="0.02"/>
</svg>

          <img src="../assets/home.png" alt="" />
        </div>
      </div>
    </div>
  </section>
</template>
