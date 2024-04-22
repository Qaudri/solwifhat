<template>
  <h1 class="text-6xl xl:text-8xl font-bold bg-clip-text text-transparent"><slot/></h1>
</template>
<style>
h1 {
  background-size: 300% 100%;
  -moz-transition: all .4s ease-in-out;
  -o-transition: all .4s ease-in-out;
  -webkit-transition: all .4s ease-in-out;
  transition: all .4s ease-in-out;
  background-image: linear-gradient(45deg,  #c023d7, #32ecc5, #32ecc5);
  animation: playgradient 3s ease-in-out infinite alternate-reverse;
}

@keyframes playgradient {
  from {
    background-position: left top;
  }

  to {
    background-position: right bottom;
  }
}
</style>
