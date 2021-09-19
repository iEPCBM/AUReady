<template>
  <div class="footer-wrapper">
    <div class="footer-block">
      <p class="footer-text">Copyright &copy; 2021 PrintDocCloud team</p>
      <p class="footer-text">Изображение музея: https://kazan.vperemen.com/, CC BY-SA 4.0 https://creativecommons.org/licenses/by-sa/4.0, via Wikimedia Commons</p>
      <p class="footer-text">Страница является демонстративной. Информация на данной странице может не совпадать с действительностью.</p>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
.footer-wrapper {
  display: flex;
  padding: 2em 5em;
  color: var(--m-color-bg);
  background-color: var(--m-color-dark-gray);
}
.footer-text {
  margin: 0;
  padding: 0.25em 3em;
}
.footer-text a {
  color: var(--m-color-green);
}
.footer-block {
  padding: 2em 3em;
}
</style>
