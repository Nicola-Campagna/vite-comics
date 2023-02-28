
<script>

export default {

}

</script>

<template>
  <header>
    <div class="nav-head-container container">
      <img src="../assets/img/dc-logo.png" alt="logo">
      <ul>
        <li>
          <a href="#">CHARACTERS</a>
        </li>
        <li>
          <a href="#">COMICS</a>
        </li>
        <li>
          <a href="#">MOVIES</a>
        </li>
        <li>
          <a href="#">TV</a>
        </li>
        <li>
          <a href="#">GAMES</a>
        </li>
        <li>
          <a href="#">COLLECTIBLES</a>
        </li>
        <li>
          <a href="#">VIDEOS</a>
        </li>
        <li>
          <a href="#">FANS</a>
        </li>
        <li>
          <a href="#">NEWS</a>
        </li>
        <li>
          <a href="#">SHOP</a>
        </li>
      </ul>

    </div>

  </header>
</template>

<style lang="scss" scoped>
// @use "../scss/mixin.scss" as *;

header .nav-head-container {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

header ul li {
  display: inline-block;
  padding: 0 10px;

  a {
    font-size: 12px;
    text-decoration: none;
    color: #000;

    &:hover {
      color: blue;
    }
  }

}
</style>
