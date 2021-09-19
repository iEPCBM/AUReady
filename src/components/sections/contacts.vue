<template>
  <div class="section sec-contacts">
    <h2 class="sec-title">Контакты</h2>
    <div class="sec-c-content">
      <div class="c-section">
        <ul class="addr-sec">
          <li>Адрес: г. Челябинск, Комсомольский проспект, д. 83</li>
          <li>Время работы: ежедневно с 9:00 до 19:00</li>
          <li>Телефон: 8(800)555-35-35</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
.c-section {

}
.addr-sec {
  list-style: none;
  margin: 0;
  padding: 0 1em;
}
.addr-sec li {
  padding: 0.25em 0;
}
.sec-contacts {
  background-color: var(--m-color-green);
  color: var(--m-color-dark-gray);
}
.sec-c-content {
  display: flex;
  padding: 0em 10em;
}
</style>
