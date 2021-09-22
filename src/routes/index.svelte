<script>
  import AboutUs from "$lib/AboutUs.svelte";
  import Products from "$lib/Products.svelte";
  import Footer from "$lib/Footer.svelte";
  /* import Loader from "$lib/Loader.svelte"; */
  import Order from "$lib/Order.svelte";
  import Pagination from "$lib/Pagination.svelte";
  import Review from "$lib/Review.svelte";
  import Stocks from "$lib/Stocks.svelte";
  /* import SearchFormNav from "$lib/SearchFormNav.svelte"; */
</script>

<!-- search form  -->
<!-- <SearchFormNav /> -->

<!-- home section starts  -->
<Pagination />

<!-- dishes section starts  -->
<Products />

<!-- about section starts  -->
<AboutUs />

<!-- menu section starts  -->
<Stocks />

<!-- review section starts  -->
<Review />

<!-- order section starts  -->
<!-- <Order /> -->

<!-- footer section starts  -->
<Footer />

<!-- loader part 
<Loader />
-->
