<script>
  import { Swiper, SwiperSlide } from "swiper/svelte";
  // Import Swiper styles
  import "swiper/css";
  import "swiper/css/pagination";
  // import Swiper core and required modules
  import SwiperCore, { Pagination, Autoplay } from "swiper";
  // install Swiper modules
  SwiperCore.use([Pagination, Autoplay]);
</script>

<section class="home" id="home">
  <div class="swiper-container home-slider">
    <div class="swiper-wrapper wrapper">
      <Swiper
        autoplay={(false, { delay: 10000 })}
        spaceBetween={50}
        slidesPerView={1}
        pagination={true}
        class="mySwiper"
      >
        <SwiperSlide
          ><div class="swiper-slide slide">
            <div class="content">
              <span>our special dish</span>
              <h3>spicy noodles</h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
                natus dolor cumque?
              </p>
              <a href="/" class="btn">order now</a>
            </div>
            <div class="image">
              <img src="images/home-img-1.png" alt="" />
            </div>
          </div>
        </SwiperSlide>
      </Swiper>

      <div class="swiper-pagination" />
    </div>
  </div>
</section>

<style>
  .swiper-slide {
    text-align: center;
    font-size: 18px;
    background: #fff;

    /* Center slide text vertically */
    display: -webkit-box;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    -webkit-justify-content: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    -webkit-align-items: center;
    align-items: center;
  }

  .swiper-slide img {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
</style>
