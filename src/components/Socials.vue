<template>
  <div class="max-w-screen-xl mx-auto py-12 px-4 sm:px-6 md:flex md:items-center md:justify-between lg:px-8">
    <div class="flex justify-center md:order-2">
     
          <a
            href="https://twitter.com/pmcp_fyit"
            class="ml-6 text-gray-400 hover:text-gray-500 transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110"
            target="_blank"
            rel="noopener noreferrer"
            title="Twitter"
            name="Twitter"
          >
            <TwitterIcon size="1.5x" />
          </a>
          <a
            href="https://github.com/pmcp"
            class="ml-6 text-gray-400 hover:text-gray-500 transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110"
            target="_blank"
            rel="noopener noreferrer"
            title="Github"
            name="Github"
          >
            <GithubIcon size="1.5x" />
          </a>
    </div>
   
  </div>


</template>

<script>
import { GithubIcon, TwitterIcon } from "vue-feather-icons";
export default {
  components: {
    GithubIcon, TwitterIcon,
  },
}
</script>