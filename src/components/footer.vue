<template>
  <div class="footer-wrapper">
    <div class="footer-block">
      <p class="footer-text">Copyright &copy; 2021 Rishat D. Kagirov.</p>
      <p class="footer-text">Лицензия MIT (<a href="#">просмотр лицензии</a>)</p>
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
