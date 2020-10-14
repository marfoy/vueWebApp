<template>
 <div class="menu_bar">
    <div v-show="defaultMenu">
      <div>
        <button class="menu_bar_open_btn" @click="defaultMenu = !defaultMenu">=</button>
      </div>
    </div>
    <div v-show="!defaultMenu">
      <div>
        <button class="menu_bar_close_btn" @click="defaultMenu = !defaultMenu">X</button>
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
      defaultMenu: true,
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div.menu_bar {
  position: fixed;
  left: 80%;
  top: 10%;
  width: 30%;
}

div.menu_section {
  margin:5% auto;
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
}
</style>
