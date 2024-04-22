<template>
  <div @click="revealMenuEvent">
    <div class="w-8">
      <div :class="(mobile_nav ? 'transition transform rotate-45 my-0 w-8 bg-primary' : 'transition my-1.5 w-8 bg-white')" class="block cursor-pointer" style="height: 3px;"></div>
      <div :class="(mobile_nav ? 'transition transform -rotate-45 my-0 w-8 -mt-0.5 bg-primary' : 'transition my-1.5 w-8 bg-white')"  class="block cursor-pointer" style="height: 3px;"></div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    rotateMenu: Boolean
  },

  data(){
    return{
      mobile_nav: false,
    }
  },
  methods: {
    revealMenuEvent(){
      this.mobile_nav = !this.mobile_nav
      this.$emit("revealMenu")
    }
  }
}
</script>