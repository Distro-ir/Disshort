<template>
  <div class="handler">
    <div id="div">
      <h1>Disshort</h1>
    </div>
    <Button />
  </div>
</template>

<script>
import Button from './components/Button.vue';

export default {
  name: "TheRoot",
  components: {
    Button
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.handler {
  display: flex;
  justify-content: space-between;
  padding-left: 50px;
  padding-right: 50px;
  margin: 40px;
}

#div {
  display: flex;
}

#div h1 {
  color: #2c3e50;
}

#img {
  margin-left: 6px;
}
</style>
