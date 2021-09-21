<script>
  import AboutUs from "$lib/AboutUs.svelte";
  import DishesCart from "$lib/DishesCart.svelte";
  import Menu from "$lib/Menu.svelte";
  import Pagination from "$lib/Pagination.svelte";
  import SearchFormNav from "$lib/SearchFormNav.svelte";
</script>

<!-- search form  -->
<SearchFormNav />

<!-- home section starts  -->
<Pagination />

<!-- dishes section starts  -->

<section class="dishes" id="dishes">
  <h3 class="sub-heading">our dishes</h3>
  <h1 class="heading">popular dishes</h1>

  <div class="box-container">
    <DishesCart />
  </div>
</section>

<!-- about section starts  -->
<AboutUs />

<!-- menu section starts  -->
<Menu />

<!-- review section starts  -->

<section class="review" id="review">
  <h3 class="sub-heading">customer's review</h3>
  <h1 class="heading">what they say</h1>

  <div class="swiper-container review-slider">
    <div class="swiper-wrapper">
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
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit fugiat
          consequuntur repellendus aperiam deserunt nihil, corporis fugit
          voluptatibus voluptate totam neque illo placeat eius quis laborum
          aspernatur quibusdam. Ipsum, magni.
        </p>
      </div>

      <div class="swiper-slide slide">
        <i class="fas fa-quote-right" />
        <div class="user">
          <img src="images/pic-2.png" alt="" />
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
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit fugiat
          consequuntur repellendus aperiam deserunt nihil, corporis fugit
          voluptatibus voluptate totam neque illo placeat eius quis laborum
          aspernatur quibusdam. Ipsum, magni.
        </p>
      </div>

      <div class="swiper-slide slide">
        <i class="fas fa-quote-right" />
        <div class="user">
          <img src="images/pic-3.png" alt="" />
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
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit fugiat
          consequuntur repellendus aperiam deserunt nihil, corporis fugit
          voluptatibus voluptate totam neque illo placeat eius quis laborum
          aspernatur quibusdam. Ipsum, magni.
        </p>
      </div>

      <div class="swiper-slide slide">
        <i class="fas fa-quote-right" />
        <div class="user">
          <img src="images/pic-4.png" alt="" />
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
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit fugiat
          consequuntur repellendus aperiam deserunt nihil, corporis fugit
          voluptatibus voluptate totam neque illo placeat eius quis laborum
          aspernatur quibusdam. Ipsum, magni.
        </p>
      </div>
    </div>
  </div>
</section>

<!-- review section ends -->

<!-- order section starts  -->

<section class="order" id="order">
  <h3 class="sub-heading">order now</h3>
  <h1 class="heading">free and fast</h1>

  <form action="">
    <div class="inputBox">
      <div class="input">
        <span>your name</span>
        <input type="text" placeholder="enter your name" />
      </div>
      <div class="input">
        <span>your number</span>
        <input type="number" placeholder="enter your number" />
      </div>
    </div>
    <div class="inputBox">
      <div class="input">
        <span>your order</span>
        <input type="text" placeholder="enter food name" />
      </div>
      <div class="input">
        <span>additional food</span>
        <input type="test" placeholder="extra with food" />
      </div>
    </div>
    <div class="inputBox">
      <div class="input">
        <span>how musch</span>
        <input type="number" placeholder="how many orders" />
      </div>
      <div class="input">
        <span>date and time</span>
        <input type="datetime-local" />
      </div>
    </div>
    <div class="inputBox">
      <div class="input">
        <span>your address</span>
        <textarea
          name=""
          placeholder="enter your address"
          id=""
          cols="30"
          rows="10"
        />
      </div>
      <div class="input">
        <span>your message</span>
        <textarea
          name=""
          placeholder="enter your message"
          id=""
          cols="30"
          rows="10"
        />
      </div>
    </div>

    <input type="submit" value="order now" class="btn" />
  </form>
</section>

<!-- order section ends -->

<!-- footer section starts  -->

<section class="footer">
  <div class="box-container">
    <div class="box">
      <h3>locations</h3>
      <a href="#">india</a>
      <a href="#">japan</a>
      <a href="#">russia</a>
      <a href="#">USA</a>
      <a href="#">france</a>
    </div>

    <div class="box">
      <h3>quick links</h3>
      <a href="#">home</a>
      <a href="#">dishes</a>
      <a href="#">about</a>
      <a href="#">menu</a>
      <a href="#">reivew</a>
      <a href="#">order</a>
    </div>

    <div class="box">
      <h3>contact info</h3>
      <a href="#">+123-456-7890</a>
      <a href="#">+111-222-3333</a>
      <a href="#">shaikhanas@gmail.com</a>
      <a href="#">anasbhai@gmail.com</a>
      <a href="#">mumbai, india - 400104</a>
    </div>

    <div class="box">
      <h3>follow us</h3>
      <a href="#">facebook</a>
      <a href="#">twitter</a>
      <a href="#">instagram</a>
      <a href="#">linkedin</a>
    </div>
  </div>

  <div class="credit">copyright @ 2021 by <span>mr. web designer</span></div>
</section>

<!-- footer section ends -->

<!-- loader part 
<div class="loader-container">
  <img src="images/loader.gif" alt="" />
</div>
-->
