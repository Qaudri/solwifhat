<template>
  <footer class="">
    <div class="max-w-7xl mx-auto px-6 py-8 grid place-items-center">
      <div class="flex gap-5">
        <NuxtLink to="https://t.me/Solanawifhat" class="h-12 w-12 gradient font-medium text-base 2xl:text-lg justify-center duration-500 ease-in-out rounded-full outline-none focus:outline-none flex items-center gap-4">
          <IconsTelegram class="w-7 h-7" />
        </NuxtLink>
        <NuxtLink to="https://twitter.com/SolWifHat1" class="h-12 w-12 gradient font-medium text-base 2xl:text-lg justify-center duration-500 ease-in-out rounded-full outline-none focus:outline-none flex items-center gap-4">
          <IconsTwitter class="w-7 h-7" />
        </NuxtLink>
      </div>
      <UiTypographyP class="mt-2">&copy;  {{new Date().getFullYear()}} Solwifhat - All rights reserved.</UiTypographyP>
    </div>
  </footer>
</template>