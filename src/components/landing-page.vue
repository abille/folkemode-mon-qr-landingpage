<template>
  <div class="hello">
    <h1>Folkemøde Møn</h1>
    <div>
      <a href="https://apps.apple.com/dk/app/folkem%C3%B8de-m%C3%B8n/id1634585997">
        <img src="../assets/app-store.png" alt="app store">
      </a>
      <a href="https://play.google.com/store/apps/details?id=dk.folkemodemon">
        <img src="../assets/google-play.png" alt="app store">
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LandingPage',
  props: {
    msg: String
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
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
