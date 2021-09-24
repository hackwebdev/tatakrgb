<script>
  let active = false;
  let menu = false;
</script>

<header>
  <div id="logo">
    <img src="/logo.svg" alt="" /><a href="/" class="logo">Tatak RGB</a>
  </div>

  <nav class={menu ? "navbar active" : "navbar"}>
    <a on:click={() => (menu = false)} class="active" href="#home">home</a>
    <a on:click={() => (menu = false)} href="#products">Products</a>
    <a on:click={() => (menu = false)} href="#about">about</a>
    <a on:click={() => (menu = false)} href="#stocks">stocks</a>
    <a on:click={() => (menu = false)} href="#review">review</a>
    <!-- <a href="#order">order</a> -->
  </nav>

  <div class="icons">
    <i class="fas fa-bars" id="menu-bars" on:click={() => (menu = !menu)} />
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

<style>
  #logo {
    display: flex;
    height: 40px;
    align-items: center;
  }
  #logo img {
    height: 60px;
  }
</style>
