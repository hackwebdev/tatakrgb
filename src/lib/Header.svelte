<script>
  let active = false;
</script>

<header>
  <a href="/" class="logo"><i class="fas fa-utensils" />TatakRGB</a>

  <nav class="navbar">
    <a class="active" href="#home">home</a>
    <a href="#products">Products</a>
    <a href="#about">about</a>
    <a href="#stocks">stocks</a>
    <a href="#review">review</a>
    <a href="#order">order</a>
  </nav>

  <div class="icons">
    <i class="fas fa-bars" id="menu-bars" />
    <i
      on:click={() => (active = true)}
      class="fas fa-search"
      id="search-icon"
    />
    <a href="/" class="fas fa-heart"><span /></a>
    <a href="/" class="fas fa-shopping-cart"><span /></a>
  </div>
</header>

<form class:active action="" id="search-form">
  <input type="search" placeholder="search here..." name="" id="search-box" />
  <label for="search-box" class="fas fa-search" />
  <i on:click={() => (active = false)} class="fas fa-times" id="close" />
</form>
