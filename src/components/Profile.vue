<template>
  <div class="pt-8 md:pt-16 min-h-screen">
    <div class="flex flex-col items-center">
      <div class="flex flex-col items-center mb-2 text-ui-primary">
        <Logo :width="160" />
        <h1 class="text-4xl text-center lg:text-5xl">
          Maarten Lauwaert
        </h1>
      </div>
      <p class="text-xl font-medium text-center">
        Brussels based UX Researcher & Prototyping Expert
      </p>
      <Socials></Socials>
      <section class=" py-12 px-4 sm:px-6 lg:py-16 lg:px-8 ml-animation">
        <div class="flex flex-col items-center mb-2 text-ui-primary">      
          <h2 class="text-center text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl sm:leading-10 ml-animation__underline">
            Clients
          </h2>
        </div>
      <Companies></Companies>
      </section>
    </div>

  </div>
</template>

<script>
import Socials from '@/components/Socials';
import Companies from '@/components/Companies';
import Logo from '@/components/Logo';

import { ArrowRightCircleIcon, ZapIcon, CodeIcon, MoonIcon, SearchIcon } from 'vue-feather-icons';

export default {
  components: {
    Logo,
    Socials,
    Companies,
    ArrowRightCircleIcon,
    ZapIcon,
    CodeIcon,
    MoonIcon,
    SearchIcon
  },
}
</script>

<style>
</style>