<template>
  <div class="header-wrapper">
    <h2 class="title">Музей {{m_title}}</h2>
    <div class="nav-wrapper">
      <ul>
        <li><a href="#" class="aws-txt">Купить билет</a></li>
        <li><a href="#">О музее</a></li>
        <li><a href="#">Онлайн-тур</a></li>
        <li><a href="#">Контакты</a></li>
        <li><a>RU</a></li>
        <li><a>TT</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'mheader',
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
.nav-wrapper {
  float: right;
  display: inline-block;
  align-self: center;
  margin-left: auto;
}
ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
li {
  display: inline;
  margin: 0 10px;
}
a {
  color: var(--m-color-dark-gray);
}
.title {
  display: inline;
}
.header-wrapper {
  position: sticky;
  top: 0;
  padding: 1.5em 8em;
  background-color: var(--m-color-gray);
  color: var(--m-color-dark-gray);
  text-transform: uppercase;
  display: flex;
  align-items: center;
  z-index: 10;
  opacity: 0.98;
}
.aws-txt {
  background-color: var(--m-color-red);
  color: #fefefe;
  padding: 5px 1em;
  border-radius: 15px;
  text-decoration: none;
  font-weight: 300;
  transition: .25s;
}
.aws-txt:hover {
  background-color: var(--m-color-red-light);
}
</style>
