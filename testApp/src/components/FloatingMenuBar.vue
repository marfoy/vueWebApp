<template>
 <div class="menu_bar">
    <div class="home_btn" @click="scrollMeTo('Home')"></div>
    <div class="menu" v-show="!showBar">
      <div>
        <button class="menu_bar_open_btn" @click="showBar = !showBar">=</button>
      </div>
    </div>
    <div class="menu" v-show="showBar">
      <div>
        <button class="menu_bar_close_btn" @click="showBar = !showBar">X</button>
      </div>
      <transition name="slide" appear>
        <app-section @scroll="scrollMeTo(...arguments)" v-show="showBar"></app-section>
      </transition>
    </div>

  </div>
</template>

<script>
import Section from './Section.vue'
export default {
  name: 'FloatingMenuBar',
  components: {
    'app-section': Section
  },
  data () {
    return {
      showBar: false
    }
  },
  methods: {
    scrollMeTo (refName) {
      this.$emit('scroll', refName)

      // Close the floating bar after section selection if scroll not tigger by the home btn
      if (refName !== 'Home') {
        this.showBar = !this.showBar
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

div.home_btn {
  position : relative;
  border-style: solid;
  border-width: 2vw;
  border-color:red;
  background-color: chartreuse;
  width: 6vw;
  height: 6vw;
}
div.menu {
  position: relative;
  top: 100%;
  border-style: solid;
  border-width: 5px;
  border-color: black;

}
div.menu {
  position: relative;
  top: 100%;
  border-style: solid;
  border-width: 5px;
  border-color: black;
}
div.menu_bar {
  position: fixed;
  float: right;
  width: 100%;
  border-style: solid;
  border-width: 5px;
  border-color: brown;
}

div.menu_section {
  margin:5% auto;
  text-align: right;
  font-size: 4vw;
  color: white;
}

button.menu_bar_open_btn {
  position: relative;
  bottom: 80%;
  left: 80%;
  width: 4vw;
  height: 10%;
  font-size: 4vw;
  background-color: Transparent;
  background-repeat:no-repeat;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
  color: white;
}

button.menu_bar_close_btn {
  position: relative;
  bottom: 80%;
  left: 80%;
  width: 4vw;
  height: 10%;
  font-size: 4vw;
  background-color: Transparent;
  background-repeat:no-repeat;
  border: none;
  cursor:pointer;
  overflow: hidden;
  outline:none;
  border-style: solid;
  border-width: 5px;
  border-color: red;
  color:white;
}

/* Animations */

.slide-enter-active {
  animation: slide-in 1s ease-out forwards
}
.slide-leave-active {
  animation: slide-out 1s ease-out forwards
}

@keyframes slide-in {
 from {
   transform: translateX(-4vw)
 }
 to {
   transform: translateX(0)
 }
}

@keyframes slide-out {
 from {
   transform: translateX(0)
 }
 to {
   transform: translateX(-4vw)
 }
}
</style>
