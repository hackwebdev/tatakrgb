<script>
  import { Swiper, SwiperSlide } from "swiper/svelte";

  // Import Swiper styles
  import "swiper/css";

  import "swiper/css/pagination";

  // import Swiper core and required modules
  import SwiperCore, { Pagination } from "swiper";

  // install Swiper modules
  SwiperCore.use([Pagination]);
</script>

<section class="review" id="review">
  <h3 class="sub-heading">customer's review</h3>
  <h1 class="heading">what they say</h1>

  <div class="swiper-container review-slider">
    <div class="swiper-wrapper">
      <Swiper
        slidesPerView={1}
        spaceBetween={20}
        centeredSlides={true}
        pagination={{
          clickable: true,
        }}
        loop={true}
        breakpoints={{
          "640": {
            slidesPerView: 1,
            spaceBetween: 20,
          },
          "768": {
            slidesPerView: 2,
            spaceBetween: 40,
          },
          "1024": {
            slidesPerView: 2,
            spaceBetween: 50,
          },
        }}
        class="mySwiper"
        ><div class="swiper-slide slide">
          <SwiperSlide>
            <i class="fas fa-quote-right" />
            <div class="user">
              <img src="images/pic-1.png" alt="" />
              <div class="user-info">
                <h3>john deo</h3>
                <div class="stars">
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star-half-alt" />
                </div>
              </div>
            </div>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
              fugiat consequuntur repellendus aperiam deserunt nihil, corporis
              fugit voluptatibus voluptate totam neque illo placeat eius quis
              laborum aspernatur quibusdam. Ipsum, magni.
            </p>
          </SwiperSlide>
        </div>
        <div class="swiper-slide slide">
          <SwiperSlide>
            <i class="fas fa-quote-right" />
            <div class="user">
              <img src="images/pic-1.png" alt="" />
              <div class="user-info">
                <h3>john deo</h3>
                <div class="stars">
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star-half-alt" />
                </div>
              </div>
            </div>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
              fugiat consequuntur repellendus aperiam deserunt nihil, corporis
              fugit voluptatibus voluptate totam neque illo placeat eius quis
              laborum aspernatur quibusdam. Ipsum, magni.
            </p>
          </SwiperSlide>
        </div>
        <div class="swiper-slide slide">
          <SwiperSlide>
            <i class="fas fa-quote-right" />
            <div class="user">
              <img src="images/pic-1.png" alt="" />
              <div class="user-info">
                <h3>john deo</h3>
                <div class="stars">
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star-half-alt" />
                </div>
              </div>
            </div>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
              fugiat consequuntur repellendus aperiam deserunt nihil, corporis
              fugit voluptatibus voluptate totam neque illo placeat eius quis
              laborum aspernatur quibusdam. Ipsum, magni.
            </p>
          </SwiperSlide>
        </div>
        <SwiperSlide>
          <div class="swiper-slide slide">
            <i class="fas fa-quote-right" />
            <div class="user">
              <img src="images/pic-1.png" alt="" />
              <div class="user-info">
                <h3>john deo</h3>
                <div class="stars">
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star" />
                  <i class="fas fa-star-half-alt" />
                </div>
              </div>
            </div>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit
              fugiat consequuntur repellendus aperiam deserunt nihil, corporis
              fugit voluptatibus voluptate totam neque illo placeat eius quis
              laborum aspernatur quibusdam. Ipsum, magni.
            </p>
          </div>
        </SwiperSlide>
      </Swiper>
    </div>
  </div>
</section>

<style>
  .swiper-wrapper {
    overflow: visible;
  }
</style>
