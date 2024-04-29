<template>
  <div class="container-fluid home-slider">
    <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
        <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="https://sun9-9.userapi.com/impf/c636830/v636830865/1628b/CJ8lLF0JzwA.jpg?size=1280x494&quality=96&sign=db14d114bd740e94de6e7d5e2129909c&c_uniq_tag=_3unik3OvSZ567PdtWZkfRIJ8Qir5LTNKYm2M4scuDg&type=album" class="d-block w-100" alt="Первая картинка">
          <div class="carousel-caption d-none d-md-block">
            <h5>Посмотрите на новую колекцию часов</h5>
            <p>Все эти новинки есть уже в каталоге</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="https://sun9-26.userapi.com/impf/c3FiMOUgB1cTIcOakVBh_HTEw6_mZwv_D2v-RQ/AwzvWTLQPeU.jpg?size=1920x768&quality=95&crop=138,0,1515,605&sign=f3a4a049f386b4cc2e4c8a5e5416ce1f&type=cover_group" class="d-block w-100" alt="Вторая картинка">
          <div class="carousel-caption d-none d-md-block">
            <h5>СКОРО В ПРОДАЖЕ</h5>
            <p>Эксключивные модели</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="https://i.pinimg.com/originals/4f/50/5b/4f505b476fefd6697d1e90da2313f941.jpg" class="d-block w-100" alt="Третья картинка">
          <div class="carousel-caption d-none d-md-block">
            <h5>СКОРО В ПРОДАЖЕ</h5>
            <p>Новейшие модели от из известных брендов</p>
          </div>
        </div>
      </div>
      <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Slider"
}
</script>

<style scoped>

</style>
