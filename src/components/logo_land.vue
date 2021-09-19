<template>
  <div class="part-wrapper">
    <img class="logo" src="../assets/m_statue_c.png" alt="">
    <div class="desc-wrapper">
      <h2 class="title">Музей <span class="title-sel">{{title}}</span></h2>
      <p class="sub-title">приглашает Вас на виртуальную выставку</p>
      <p class="t-btn-wrapper"><a class="btn" href="#s-tour">Посетить</a></p>
    </div>
  </div>
</template>

<script>
export default {
  props: ["title"]
}
</script>
<style lang="css" scoped>
.part-wrapper {
  display: flex;
  position: relative;
  margin: 0 0 0;
}
.desc-wrapper {
  align-self: center;
}
.logo {
  min-width: 360px;
  width: 33%;
  margin: 5em -13em 0 20vw;
  /* z-index: 11; */
}
.title {
  font-weight: bold;
  font-size: 2em;
  margin: 0 0 0.3em 0
}
.title-sel {
  color: #FFF;
  background-color: var(--m-color-dark-gray);
  padding: 0.05em 0.2em;
  border-radius: 0.25em;
}
.sub-title {
  margin: 0;
  font-size: 1.5em;
}
.btn {
  padding: 1.5em 1em;
  text-transform: uppercase;
  padding: 0.75em 1em;
  border-width: 3px;
  border-color: var(--m-color-dark-gray);
  border-style: solid;
  font-weight: 500;
  transition: .25s;
  text-decoration: none;
  color: var(--m-color-dark-gray)
}
.btn:hover {
  background-color: var(--m-color-dark-gray);
  color: #FFF;
}
.t-btn-wrapper {
  margin: 2em 0.1em;
  padding: 0;
}
</style>
