<script setup>
</script>

<template>
    <!-- Hero -->
    <section class="w-full h-150 bg-hero bg-cover bg-center">
        <div class="flex items-center h-full text-white pt-25 mx-20">
            <img src="../assets/images/logo/logo_aether_skateshop.svg" alt="logo_aether_skateshop" class="logo w-20 h-20 mr-4">
            <div>
                <h1 class="logotext text-4xl font-bold">Aether Skateshop</h1>
                <p class="text-lg">Feel the infinite</p>
            </div>
        </div>
    </section>
    <!-- CTA Hero -->
    <section class="w-full bg-tertiary">
        <div class="flex flex-col lg:flex-row lg:space-x-20 py-10 text-white mx-30">
            <div class="flex flex-col lg:w-1/2 lg:order-1 lg:pl-8 space-y-8 py-10 md:items-center">
                <h2 class="text-5xl">Vive el skate cada día</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec dictum  tempus nibh, ultricies sodales magna dictum in. Ut porttitor eros in  purus tincidunt auctor. Aliquam semper dolor at erat scelerisque  pretium. Fusce lorem tortor, rhoncus quis enim faucibus, facilisis  pellentesque metus.
                </p>
                <button class=" outline-1 outline-offset-4 outline-solid rounded-md px-25 mt-2 hover:outline-primary hover:text-primary transition duration-300">
                    Empezar a rodar
                </button>
            </div>
            <div class="flex lg:order-2 lg:w-1/2 py-10 items-center">
                <img src="../assets/images/vive_el_skate.jpg" alt="Vive el skate" class="rounded-4xl">
            </div>            
        </div>              
    </section>
</template>

<style>
.logo {
    
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em var(--color-primary));
  }
  .logotext:hover {
    filter: drop-shadow(0 0 2em var(--color-white));
  }
</style>