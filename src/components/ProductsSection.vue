<script setup>
</script>

<template>
    <!-- Main Product -->
    <section id="products" class="w-full h-full bg-white">
        <div class="flex flex-col py-20 mx-30">
            <h2 class="text-5xl text-primary text-center font-bold">Skateboards</h2>
            <hr class="border-t-6 border-secondary w-65 mx-auto my-7 rounded-full">            
            <p class="text-center text-tertiary text-base mt-6">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec dictum tempus nibh, ultricies sodales magna dictum in. Ut porttitor eros in purus tincidunt auctor. Aliquam semper dolor at erat scelerisque pretium. Fusce lorem tortor, rhoncus quis enim faucibus, facilisis pellentesque metus. Donec a consequat orci, ut facilisis tellus. Mauris non tortor tellus. Donec urna quam, placerat vel quam sit amet, malesuada aliquam lacus.
            </p>            
            <div class="flex lg:w-1/2 pt-10 items-center justify-center mx-auto">
                <img src="../assets/images/products/01_tarot_moon.jpg" alt="Tarot Moon">
            </div> 
            <div class="flex flex-col space-y-2 py-6 mx-auto items-center">
                <h6 class="text-gray-75">Skate completo</h6>
                <h4 class="text-primary">Tarot Moon Complete</h4>
                <small class="text-gray-75">7.75" - 8.25"</small>                           
            </div>
            <button class="
                h-9 bg-primary text-white border border-transparent rounded-xl px-20 py-1 mx-auto
                hover:bg-white hover:text-primary hover:border-primary active:border-secondary active:text-secondary 
                transition duration-300 cursor-pointer"
            >
                Comprar
            </button>  
        </div>
    </section>
    <!-- New Products -->
    <section class="w-full h-full bg-gray-75">
        <h2 class="text-5xl text-secondary font-bold pt-20 px-30">Novedades</h2>
        <div class="w-auto items-center mt-6 overflow-x-auto overscroll-x-contain flex space-x-4 lg:space-x-6 overflow-y-hidden">
            <!-- Cards -->
            <div class="Card">
                <div class="w-full border border-secondary bg-transparent p-4 rounded-4xl max-w-sm mx-auto">
                    <img src="../assets/images/products/02_day_legs.jpg" alt="Day legs" class="w-80 rounded-4xl mb-4 mx-auto cursor-pointer">
                    <div class="flex justify-between items-center mb-2">
                        <h2 class="text-xl font-bold text-secondary">8" Day Legs Complete</h2>
                        <button class="w-20 border border-secondary bg-transparent text-secondary px-2 py-1 rounded-full mr-5 cursor-pointer">110€</button>
                    </div>
                    <p class="text-secondary">Skate completo</p>
                    <p class="text-secondary">Composición</p>
                    <p class="text-secondary">[Tejido principal] 75% Madera de arce, 15% Acero, 8% Uretano, 2% Lija</p>
                </div>                
            </div>
            <div class="Card">
                <div class="w-full border border-secondary bg-transparent p-4 rounded-4xl max-w-sm mx-auto">
                    <img src="../assets/images/products/02_day_legs.jpg" alt="Day legs" class="w-80 rounded-4xl mb-4 mx-auto cursor-pointer">
                    <div class="flex justify-between items-center mb-2">
                        <h2 class="text-xl font-bold text-secondary">8" Day Legs Complete</h2>
                        <button class="w-20 border border-secondary bg-transparent text-secondary px-2 py-1 rounded-full mr-5 cursor-pointer">110€</button>
                    </div>
                    <p class="text-secondary">Skate completo</p>
                    <p class="text-secondary">Composición</p>
                    <p class="text-secondary">[Tejido principal] 75% Madera de arce, 15% Acero, 8% Uretano, 2% Lija</p>
                </div>                
            </div>
            <div class="Card">
                <div class="w-full border border-secondary bg-transparent p-4 rounded-4xl max-w-sm mx-auto">
                    <img src="../assets/images/products/02_day_legs.jpg" alt="Day legs" class="w-80 rounded-4xl mb-4 mx-auto">
                    <div class="flex justify-between items-center mb-2">
                        <h2 class="text-xl font-bold text-secondary">8" Day Legs Complete</h2>
                        <button class="w-20 border border-secondary bg-transparent text-secondary px-2 py-1 rounded-full mr-5">110€</button>
                    </div>
                    <p class="text-secondary">Skate completo</p>
                    <p class="text-secondary">Composición</p>
                    <p class="text-secondary">[Tejido principal] 75% Madera de arce, 15% Acero, 8% Uretano, 2% Lija</p>
                </div>                
            </div>
            <div class="Card">
                <div class="w-full border border-secondary bg-transparent p-4 rounded-4xl max-w-sm mx-auto">
                    <img src="../assets/images/products/02_day_legs.jpg" alt="Day legs" class="w-80 rounded-4xl mb-4 mx-auto">
                    <div class="flex justify-between items-center mb-2">
                        <h2 class="text-xl font-bold text-secondary">8" Day Legs Complete</h2>
                        <button class="w-20 border border-secondary bg-transparent text-secondary px-2 py-1 rounded-full mr-5">110€</button>
                    </div>
                    <p class="text-secondary">Skate completo</p>
                    <p class="text-secondary">Composición</p>
                    <p class="text-secondary">[Tejido principal] 75% Madera de arce, 15% Acero, 8% Uretano, 2% Lija</p>
                </div>                
            </div>

        </div>
    </section>
    
</template>