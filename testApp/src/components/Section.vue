<template>
<div>
    <div class="menu_section" @click="scrollMeTo('anchorA')">
        Menu Section A blabalbablbalabobo
    </div>
    <div class="menu_section" @click="scrollMeTo('anchorB')">
        Menu Section B
    </div>
    <div class="menu_section" @click="scrollMeTo('anchorC')">
        Menu Section C balablabablablablablablaajakjkajkajk
    </div>
</div>
</template>
<script>
export default {
  name: 'Section',
  methods: {
    scrollMeTo (refName) {
      this.$emit('scroll', refName)
    }
  }
}
</script>
<style scoped>

div.menu_section {
  margin:5% auto;
  text-align: right;
  color:white;
  font-size: 4vw;
}

</style>
