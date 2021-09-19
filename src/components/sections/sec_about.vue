<template>
  <div class="sec-about-wrapper">
    <h2 class="sec-title">О музее</h2>
    <div class="about-content">
      <img class="img-museum" src="../../assets/museum1.jpg" alt="">
      <div class="desc-wrapper">
        <p class="desc-content">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
.sec-about-wrapper {
  background-color: var(--m-color-gray);
  margin: auto;
}
.img-museum {
  width: 33%;
  min-width: 480px;
  margin: 0em 5em;
}
.about-content {
  display: flex;
  padding: 1em 10em;
}
.pic-wrapper {
  display: inline-block;
}
.desc-wrapper {
  align-self: flex-start;
}
.desc-content {
  margin: 2em 1.5em;
  padding: 0;
}
</style>
