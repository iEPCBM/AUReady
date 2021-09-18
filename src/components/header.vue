<template>
  <div class="header-wrapper">
    <h2 class="title">{{m_title}}</h2>
    <ul>
      <li>Купить билет</li>
      <li>О музее</li>
      <li>Онлайн-тур</li>
      <li>Контакты</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'header',
  props: {
    m_title: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
  float: right;
}
li {
  display: inline;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.title {

}
</style>
