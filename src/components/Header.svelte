<script>
</script>

<header>
  <div class="navbar-clip-left" />
  <div class="navbar-clip-right">
    <a href="index.html"><img src="./../../public/assets/heysiridotcodeslogo.png" class="logo" alt="HeySiri.Codes Logo" /></a>
  </div>
</header>

<style>
  header {
    display: flex;
    top: 0;
  }
  .navbar-clip-left {
    background-color: #1f2133;
    position: absolute;
    z-index: 1;
    width: 100vw;
    height: 90px;
    clip-path: polygon(100% 0%, 100% 80.5%, 0% 100%, 0% 0%);
  }

  .navbar-clip-right {
    background-color: #151622;
    position: initial;
    z-index: 2;
    width: 100vw;
    right: 0;
    height: 110px;
    clip-path: polygon(100% 0%, 100% 80.5%, 0% 13.3%, 0% 0%);
  }

  .logo {
    width: 100px;
    height: auto;
    position: absolute;
    z-index: 3;
    right: 0;
    margin-right: 1rem;
    margin-top: 1.7rem;
  }

  @media screen and (min-width: 1024px) {
    .navbar-clip-left {
      height: 130px;
    }

    .navbar-clip-right {
      height: 150px;
    }

    .logo {
      width: 170px;
      margin-right: 3rem;
      margin-top: 2.5rem;
    }
  }
</style>
