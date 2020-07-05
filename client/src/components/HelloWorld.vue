<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      more to come...stay tuned
    </p>    
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://www.meinspielplan.de/plan/KbGjP1#" target="_blank" rel="noopener">Palinka--League</a></li>
      <li><a href="https://meet.palinka-darts.de" target="_blank" rel="noopener">Jitsi-Room</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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
