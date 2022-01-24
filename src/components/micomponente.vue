<template>
  <div>
    Titulo: {{titulo}}<br>
    <button v-on:click="count++">
      You clicked me {{ count }} times.
    </button>
  </div>
</template>

<script>
export default {
  name: 'MiComponente',
  props: {
    titulo : String,
    url: String
  },data() {
    return {
      count: 0
    }
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
  color: #ff28ff;
}
</style>
