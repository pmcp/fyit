<template>
  
  <div class="max-w-screen-xl ">
    <!-- <p class="text-center text-base leading-6 font-semibold uppercase text-gray-600 tracking-wider">
      
    </p> -->
    <div class="mt-6 grid grid-cols-2 gap-0.5 md:grid-cols-3 lg:mt-8">
      <div class="col-span-1 flex justify-center py-8 px-8 bg-gray-50">
        <img class="h-12 max-h-12 ml-companies" src="@/assets/companies/sporza.png" alt="VRT NWS">
      </div>
      <div class="col-span-1 flex justify-center py-8 px-8 bg-gray-50">
        <img class="h-12 max-h-12 ml-companies" src="@/assets/companies/vrtnws.png" alt="Sporza">
      </div>
      <div class="col-span-1 flex justify-center py-8 px-8 bg-gray-50">
        <img class="h-12 max-h-12" src="https://tailwindui.com/img/logos/tuple-logo.svg" alt="Tuple">
      </div>
      <div class="col-span-1 flex justify-center py-8 px-8 bg-gray-50">
        <img class="h-12 max-h-12" src="https://tailwindui.com/img/logos/laravel-logo.svg" alt="Laravel">
      </div>
      <div class="col-span-1 flex justify-center py-8 px-8 bg-gray-50">
        <img class="h-12 max-h-12" src="https://tailwindui.com/img/logos/statickit-logo.svg" alt="StaticKit">
      </div>
      <div class="col-span-1 flex justify-center py-8 px-8 bg-gray-50">
        <img class="h-12 max-h-12" src="https://tailwindui.com/img/logos/statamic-logo.svg" alt="Statamic">
      </div>
    </div>
  </div>

</template>

<script>
export default {

}
</script>

<style>
    .ml-companies {
    filter: invert(100%);
  }

  html[lights-out] .ml-companies {
    -webkit-filter: invert(0%);
    filter: invert( 0%); 
  }
   
</style>