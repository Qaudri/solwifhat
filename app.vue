<template>
  <header class="px-6 max-w-6xl py-8 mx-auto">
    <nav class="w-full border border-primary rounded-full flex items-center justify-between">
      <NuxtLink to="/" class="cursor-pointer bg-primary px-5 rounded-full py-3 duration-300 ease-in-out hover:bg-secondary">Solfwifhat</NuxtLink>
      <UiButtonsMenu class="w-8 mr-5" />
    </nav>
  
    <main class="py-8 flex flex-col lg:flex-row items-center gap-8 lg:gap-24">
      <img src="/logo.png" alt="Solwifhat logo">
      <div>
        <UiTypographyH1>Welcome to Solwifhat</UiTypographyH1>
        <div class="flex gap-5 items-center mt-5">
          <img src="/Ethereum.png" class="h-16" alt="Ethereum logo">
          <img src="/sol_logo.png" class="h-16" alt="Solana logo">
          <img src="/DollarCoin.png" class="h-16" alt="Dollar logo">
          <img src="/logo.png" class="h-16" alt="Solwifhat logo">
        </div>
        <div class="flex gap-5 mt-5">
          <UiButtonsPrimary :flexdisplay="true">
            <IconsTelegram class="w-6" />
            Join Telgram
          </UiButtonsPrimary>
          <UiButtonsPrimary :flexdisplay="true">
            <IconsTwitter class="w-6" />
            Follow on X
          </UiButtonsPrimary>
        </div>
      </div>

    </main>
  </header>

  <section class="px-6 max-w-6xl py-8 mx-auto">
    <UiTypographyH2 data-aos="fade-right" data-aos-duration="1500">About SolWifhat</UiTypographyH2>
    <UiTypographyP data-aos="fade-right" data-aos-duration="1500" data-aos-delay="500" class="mt-5">
      Solwifhat memes are indeed a creative and entertaining way to engage with the Solana community and showcase the unique aspects of the blockchain ecosystem. By using Solwifhat to depict different elements of Solana, these memes can help foster a sense of community, spark conversations, and provide a lighthearted perspective on the technology and projects within the Solana network. Whether highlighting the latest developments, poking fun at industry trends, or simply sharing a laugh, Solwifhat memes can be a fun and engaging way to connect with others in the Solana community through Solwifhat NFTs, artificial intelligence (AI), and gaming.
      <br><br>
      As for Solwifhat being the next 1000x on the Solana ecosystem, it's exciting to see such enthusiasm and optimism! Solwifhat's potential for growth and success within the Solana ecosystem is certainly something to keep an eye on. With its innovative approach and potential for significant impact, Solwifhat could very well be a key player in the future of Solana. It's always great to see new projects and initiatives that have the potential to make a big impact in the blockchain space, and Solwifhat seems to be one of those projects worth watching closely.
    </UiTypographyP>
  </section>
  <section class="px-6 max-w-6xl py-8 mx-auto">
    <CarouselTokenomics />
  </section>
  <section class="px-6 max-w-6xl py-8 mx-auto">
    <UiTypographyH2>Utilities</UiTypographyH2>
    <ul class="grid lg:grid-cols-2 mt-5 gap-8">
      <li data-aos="zoom-in-up" data-aos-duration="1500" class="rounded-xl bg-gradient-to-tr from-secondary via-primary to-primary p-0.5">
        <div class="bg-gradient-to-tr from-tertiary to-gray-700 p-5 rounded-xl bg-opacity-50 backdrop-blur">
          <span class="font-bold text-xl">Play and Earn SolWifHat Game</span>
          <dd class="mt-2">Immerse yourself in a thrilling world of gaming with our project, where you can play captivating games and earn SolWifHat rewards. <br>
            Our games are meticulously crafted to deliver an immersive and enjoyable experience. Engage in action-packed battles, solve perplexing puzzles, or embark on captivating quests.
          </dd>
        </div>
      </li>

      <li data-aos="zoom-in-up" data-aos-delay="500" data-aos-duration="1500" class="rounded-xl bg-gradient-to-tr from-secondary via-primary to-primary p-0.5">
        <div class="bg-gradient-to-tr from-tertiary to-gray-700 p-5 rounded-xl bg-opacity-50 backdrop-blur h-full">
          <span class="font-bold text-xl">Earn Rewards and Prizes</span>
          <dd class="mt-2">As you progress through the games, you will be rewarded with SolWifHat tokens and in-game items. These rewards can be utilized to unlock new levels, upgrade your characters, or exchange for valuable prizes.
          </dd>
        </div>
      </li>

      <li data-aos="zoom-in-up" data-aos-duration="1500" data-aos-delay="500" class="rounded-xl bg-gradient-to-tr from-secondary via-primary to-primary p-0.5">
        <div class="bg-gradient-to-tr from-tertiary to-gray-700 p-5 rounded-xl bg-opacity-50 backdrop-blur h-full">
          <span class="font-bold text-xl">SolWifHat NFTs: Utility and Rewards</span>
          <dd class="mt-2">Our SolWifHat NFTs are not just digital collectibles; they are keys to a world of exclusive benefits and rewards. <br>
            SolWifHat Token Rewards:
            <dt class="ml-5">
              * Hold a SolWifHat NFT to receive regular distributions of SolWifHat tokens.
            </dt>
            <dt class="ml-5">
              * The rarity and tier of your NFT determine the amount of tokens you earn.
            </dt>
          </dd>
        </div>
      </li>

      <li data-aos="zoom-in-up" data-aos-duration="1500" data-aos-delay="500" class="rounded-xl bg-gradient-to-tr from-secondary via-primary to-primary p-0.5">
        <div class="bg-gradient-to-tr from-tertiary to-gray-700 p-5 rounded-xl bg-opacity-50 backdrop-blur h-full">
          <span class="font-bold text-xl">Staking DApp:</span>
          <dd class="mt-2">
            <dt class="ml-5">
              * Stake your SolWifHat NFTs in our dedicated staking DApp.
            </dt>
            <dt class="ml-5">
              * Earn additional SolWifHat tokens as rewards for staking your NFTs.
            </dt>
            <dt>
              * The longer you stake, the greater your rewards.
            </dt>
          </dd>
        </div>
      </li>

      <li data-aos="zoom-in-up" data-aos-duration="1500" data-aos-delay="500" class="rounded-xl bg-gradient-to-tr from-secondary via-primary to-primary p-0.5">
        <div class="bg-gradient-to-tr from-tertiary to-gray-700 p-5 rounded-xl bg-opacity-50 backdrop-blur h-full">
          <span class="font-bold text-xl">Join the SolWifHat NFT Revolution:</span>
          <dd class="mt-2">
            Acquire a SolWifHat NFT today and unlock a wealth of rewards and exclusive benefits. Become part of our growing community and experience the power of NFTs in the SolWifHat ecosystem.
          </dd>
        </div>
      </li>

      <li data-aos="zoom-in-up" data-aos-duration="1500" data-aos-delay="500" class="rounded-xl bg-gradient-to-tr from-secondary via-primary to-primary p-0.5">
        <div class="bg-gradient-to-tr from-tertiary to-gray-700 p-5 rounded-xl bg-opacity-50 backdrop-blur h-full">
          <span class="font-bold text-xl">SolWifHat Artificial Intelligence (AI)</span>
          <dd class="mt-2">
            SolWifHat leverages the power of artificial intelligence (AI) to enhance your experience and provide innovative features. <br>SolWifHat Chatbot:
            <dt class="ml-5">*Interact with our AI-powered chatbot, SWIFI, for instant support and information.</dt>
            <dt class="ml-5">*Ask questions about the project, game mechanics, NFT utilities, and more.</dt>
            <br>Image Generation: <br>
            <dt class="ml-5">*Utilize our AI-driven image generator to create unique and captivating images.</dt>

          </dd>
        </div>
      </li>
    </ul>
  </section>
  <NavigationFooter />
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');
body {
  background-color: #151515;
  color: white;
}
* {
  font-family: "Montserrat", sans-serif;
  font-optical-sizing: auto;
  font-style: normal;
}
</style>
<script>
import AOS from 'aos';
import 'aos/dist/aos.css';
export default {
  mounted(){
    AOS.init();
  }
}
</script>