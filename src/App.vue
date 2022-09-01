<template>
  <div class="holder">
    <div class="handler">
      <div id="div">
        <h1>Disshort</h1>
      </div>
      <Button />
    </div>
    <div class="getInformation">
      <h1>When<br>The Shorter,</h1>
      <SearchBoxVue />
      <h1>the better</h1>
      <button id="conter">Get started</button>
    </div>
  </div>
</template>

<script>
import Button from './components/Button.vue';
import SearchBoxVue from './components/SearchBox.vue';

export default {
  name: "TheRoot",
  components: {
    Button,
    SearchBoxVue
  }
}
</script>

<style>
#conter {
  border: 3px solid rgb(70, 163, 238);
  background-color: rgb(70, 163, 238);
  border-radius: 16px;
  padding: 9px;
  height: 50px;
  color: white;
  width: 200px;
  text-align: center;
  margin-bottom: 100px;
}

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

.getInformation {
  font-size: 40px;
  text-align: left;
  margin-left: 50px;
}

#div {
  display: flex;
}

#div h1 {
  color: rgb(245, 86, 86);
}

#img {
  margin-left: 6px;
}
</style>
