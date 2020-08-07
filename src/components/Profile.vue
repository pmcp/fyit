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
      <Companies></Companies>
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