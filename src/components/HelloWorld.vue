<template>
  <div class="container">
    <h1>{{ msg }}</h1>
    <div class="row">
      <div class="cell">
        <img class="logo" src="static/images/django_logo.png">
      </div>
      <div class="cell">
        <img class="logo" src="static/images/vue_logo.png">
      </div>
      <div class="cell">
        <img class="logo" src="static/images/webpack_logo.png">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Django + Vue + Webpack Template'
    }
  }
}
</script>

<style scoped>
.container {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1 {
  font-weight: normal;
}

.row {
  display: flex;
  flex-direction: row;
  align-items: center;
}

.cell {
  flex: 1;
  padding: 20px;
}

.logo {
  max-width: 100%;
}
</style>
