<template>
        <div class="glide tokenomics">
        <div class="flex items-center justify-between">
          <div>
            <UiTypographyH2>Tokenomics</UiTypographyH2>
          </div>
          <div class="glide__arrows flex gap-2" data-glide-el="controls">
            <button class="glide__arrow glide__arrow--left" data-glide-dir="<">
              <div class="bg-secondary aspect-square rounded-full p-1.5 hover:bg-primary duration-300 bg-opacity-75">
                <IconsAccordion class="w-7 h-7 -rotate-90 text-white" />
              </div>
            </button>
            <button class="glide__arrow glide__arrow--right" data-glide-dir=">">
              <div class="bg-secondary aspect-square rounded-full p-1.5 hover:bg-primary duration-300 bg-opacity-75">
                <IconsAccordion class="w-7 h-7 rotate-90 text-white" />
              </div>
            </button>
          </div>
        </div>

        <div class="glide__track mt-5" data-glide-el="track">
          <ul class="glide__slides items-center">
            <li class="rounded-full bg-gradient-to-tr from-secondary via-primary to-primary p-0.5 glide__slide">
              <div class="flex rounded-full bg-tertiary py-3 px-5 justify-center">
                Name: SolWifHat
              </div>
            </li>
            <li class="rounded-full bg-gradient-to-tr from-secondary via-primary to-primary p-0.5 glide__slide">
              <div class="flex rounded-full bg-tertiary py-3 px-5 justify-center">
                Symbol: SolWif
              </div>
            </li>
            <li class="rounded-full bg-gradient-to-tr from-secondary via-primary to-primary p-0.5 glide__slide">
              <div class="flex rounded-full bg-tertiary py-3 px-5 justify-center text-center">
                Total Supply: {{supply.toLocaleString()}}
              </div>
            </li>
            <li class="rounded-full bg-gradient-to-tr from-secondary via-primary to-primary p-0.5 glide__slide">
              <div class="flex rounded-full bg-tertiary py-3 px-5 justify-center">
                LP Locked 🔐
              </div>
            </li>
            <li class="rounded-full bg-gradient-to-tr from-secondary via-primary to-primary p-0.5 glide__slide">
              <div class="flex rounded-full bg-tertiary py-3 px-5 justify-center">
                Tax 0/0
              </div>
            </li>
          </ul>
        </div>
      </div>
</template>
<script setup>
import Glide from '@glidejs/glide';
import '@glidejs/glide/dist/css/glide.core.min.css';
const supply = 50000000;
onMounted(() =>{
  new Glide('.glide', {
    type: 'carousel',
    focusAt: 'center',
    autoplay: 2000,
    gap: 20,
    peek: 30,
    perView: 1,
    animationDuration: 1000,
    breakpoints: {
      600: {
        perView: 1
      },
      1024: {
        perView: 3
      },
      1440: {
        perView: 4
      },
      12000: {
        perView: 5
      }
    }
  }).mount()
})
</script>