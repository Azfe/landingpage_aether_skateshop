<script setup>
</script>

<template>
    <!-- Hero -->
    <div class="w-full h-150 bg-hero bg-cover bg-center">
        <div class="flex items-center justify-center h-full text-white pr-80 pt-25">
            <img src="../assets/images/logo/logo_aether_skateshop.svg" alt="logo_aether_skateshop" class="logo w-20 h-20 mr-4">
            <div>
                <h1 class="logotext text-4xl font-bold">Aether Skateshop</h1>
                <p class="text-lg">Feel the infinite</p>
            </div>
        </div>
    </div>
    <!-- CTA Hero -->
    <div class="w-full bg-tertiary bg-cover bg-center">
        <div class="flex items-center space-x-20 text-white py-20">
            <div class="space-y-8">
                <h2 class="text-5xl">Vive el skate cada día</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec dictum  tempus nibh, ultricies sodales magna dictum in. Ut porttitor eros in  purus tincidunt auctor. Aliquam semper dolor at erat scelerisque  pretium. Fusce lorem tortor, rhoncus quis enim faucibus, facilisis  pellentesque metus.
                </p>
                <button class=" outline-1 outline-offset-4 outline-solid rounded-md px-8">Empezar a rodar</button>
            </div>
            <div class="w-3/4">
                <img src="../assets/images/vive_el_skate.jpg" alt="Vive el skate" class="rounded-4xl">
            </div>            
        </div>              
    </div>
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