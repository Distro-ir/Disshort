<template>
  <div class="searchBox">
    <div class="window">
      <div class="red"></div>
      <div class="yellow"></div>
      <div class="green"></div>
    </div>
    <div class="window">
      <img id="left" src="../assets/chevron-left.svg" alt="left" width="20">
      <img src="../assets/chevron-right.svg" alt="right" width="20">
    </div>
    <img src="../assets/layout.svg" alt="layout" width="20">
    <div class="search-container">
      <div class="search-begin">
        <div class="blue">
        </div>
      </div>
      <input type="text" name="searchbox" id="searchbox">
    </div>
  </div>
</template>

<script>
export default {
  name: 'SearchBox'
}
</script>

<style scoped>
.searchBox {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  border-radius: 18px;
  background-color: rgb(240, 229, 229);
  margin: 100px;
  margin-left: 10px;
  padding: 15px;
}

.searchBox img {
  padding: 10px;
  border-radius: 17px;
  background-color: rgb(221, 220, 220);
}

.window {
  display: flex;
  justify-content: space-between;
}

.window img {
  padding: 10px;
  border-radius: 17px;
  background-color: rgb(221, 220, 220);
}

#left {
  margin-right: 6px;
}

.red {
  width: 20px;
  height: 20px;
  border-radius: 50%;
  margin-right: 6px;
  background-color: red;
  margin-top: 10px;
}

.blue {
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background-color: rgb(106, 97, 236);
}

.yellow {
  width: 20px;
  height: 20px;
  border-radius: 50%;
  margin-right: 6px;
  background-color: rgb(235, 235, 31);
  margin-top: 10px;

}

.green {
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background-color: green;
  margin-top: 10px;

}

.search-container {
  background-color: white;
  border-radius: 40px;
  display: flex;
  justify-content: center;
  width: 600px;
}

.search-begin {
  background-color: white;
  border-radius: 40px;
  border: 0 white;
  width: fit-content;
  padding: 10px;
}

.search-container input {
  text-indent: 1.2em;
  flex: 1;
  border: none;
  background-color: rgba(0, 0, 0, 0);
  outline: none;
  padding: 0;
  color: var(--bg-color) !important;
  font-size: 14px;
  font-family: DevelopixIranYekanNormal;
}
</style>
