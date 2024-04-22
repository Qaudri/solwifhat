<template>
  <div>
    <button @click="emitclicked()" class="gradient py-2 px-5 text-white font-medium text-base 2xl:text-lg justify-center rounded-lg outline-none" :class="flexdisplay ? 'flex w-full gap-4 items-center' : 'block w-fit'">
      <slot />
    </button>
  </div>
</template>

<script>
export default {
  props: {
    flexdisplay: Boolean
  },
  methods: {
    emitclicked(){
      this.$emit("clicked")
    }
  }
}
</script>

<style>
.gradient {
  background-size: 300% 100%;
  -moz-transition: all .4s ease-in-out;
  -o-transition: all .4s ease-in-out;
  -webkit-transition: all .4s ease-in-out;
  transition: all .4s ease-in-out;
  background-image: linear-gradient(45deg,  #c023d7, #32ecc5, #32ecc5, #32ecc5);
}

.gradient:hover {
  background-position: 100% 0;
  -moz-transition: all .4s ease-in-out;
  -o-transition: all .4s ease-in-out;
  -webkit-transition: all .4s ease-in-out;
  transition: all .4s ease-in-out;
}
</style>