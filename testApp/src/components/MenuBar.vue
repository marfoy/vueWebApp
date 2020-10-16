<template>
 <div class="menu_bar">
    <div class="menu" v-show="!showBar">
      <div>
        <button class="menu_bar_open_btn" @click="showBar = !showBar">=</button>
      </div>
    </div>
    <div class="menu" v-show="showBar">
      <div>
        <button class="menu_bar_close_btn" @click="showBar = !showBar">X</button>
      </div>
      <div>
        <div class="menu_section">
          Menu Section A blabalbablbalab
        </div>
        <div class="menu_section">
          Menu Section B
        </div>
        <div class="menu_section">
          Menu Section C balablabablablablablablaajakjkajkajk
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'MenuBar',
  data () {
    return {
      showBar: false
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div.menu_bar {
  position: fixed;
  float: right;
  left: 70%;
  top: 10%;
  width: 30%;
  border-style: solid;
  border-width: 5px;
  border-color: brown;
}

div.menu_section {
  margin:5% auto;
  text-align: right;
}

button.menu_bar_open_btn {
  position: relative;
  bottom: 80%;
  right: 30%;
  width: 10%;
  height: 10%;
  font-size: xx-large;
  background-color: Transparent;
  background-repeat:no-repeat;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
}

button.menu_bar_close_btn {
  position: relative;
  bottom: 80%;
  right: 30%;
  width: 10%;
  height: 10%;
  font-size: xx-large;
  background-color: Transparent;
  background-repeat:no-repeat;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
  border-style: solid;
  border-width: 5px;
  border-color: red;
}

div.menu {
  position: relative;
  top: 10%;
  border-style: solid;
  border-width: 5px;
  border-color: black;
}
</style>
