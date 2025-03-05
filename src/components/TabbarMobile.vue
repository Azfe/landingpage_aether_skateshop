<template>
    <nav class="w-full h-16 bg-white fixed left-0 top-0 shadow-md flex space-x-8 items-center px-20 z-50 justify-between lg:hidden" id="tabbar">
        <!-- Logotipo -->
        <div v-show="showLogo" class="flex flex-grow flex-row flex-nowrap items-center animate-fade-slide">
            <img src="../assets/images/logo/logo_aether_skateshop.svg" alt="logo aether skateshop" class="logo w-10 h-10 mr-4">        
            <div class="flex flex-col">
                    <h1 class="logotext text-2xl font-bold text-tertiary">Aether Skateshop</h1>
                    <!--<p class="text-md text-gray-75 md:hidden">Feel the infinite</p>-->
            </div>
        </div>

        <!-- Botón del menú hamburguesa -->
        <div class="relative ml-auto">     
            <button @click="toggleMenu" class="text-gray-75 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                </svg>
            </button>         

            <!-- Menú desplegable -->
            <transition name="fade">
                <div v-if="isOpen" class="absolute top-10 right-0 w-48 p-2 bg-white border border-gray-200 rounded-md shadow-lg">
                    <a href="#home" class="block px-4 py-2 text-gray-700 hover:bg-primary active:text-secondary" @click="toggleMenu">Inicio</a>            
                    <hr class="border-t-1 border-gray-37 w-4/5 mx-auto rounded-full">
                    <a href="#products" class="block px-4 py-2 text-gray-700 hover:bg-primary active:text-secondary" @click="toggleMenu">Productos</a>
                    <hr class="border-t-1 border-gray-37 w-4/5 mx-auto rounded-full">
                    <a href="#videos" class="block px-4 py-2 text-gray-700 hover:bg-gray-100 active:text-secondary" @click="toggleMenu">Videos</a>
                    <hr class="border-t-1 border-gray-37 w-4/5 mx-auto rounded-full">
                    <a href="#footer"class="block px-4 py-2 text-gray-700 hover:bg-gray-100 active:text-secondary" @click="toggleMenu">Sobre nosotros</a>
                    <hr class="border-t-1 border-gray-37 w-4/5 mx-auto rounded-full">
                    <a href="#login"class="block px-4 py-2 text-gray-700 hover:bg-gray-100 active:text-secondary" @click="toggleMenu">Iniciar sesión</a>
                </div>
            </transition> 
        </div> 
        <!--
        <transition name="fade">
            <div v-if="isOpen" class="absolute top-16 right-4 bg-white shadow-lg rounded-lg w-48 p-4 flex flex-col space-y-3 lg:hidden">
                <a href="#home" class="text-primary hover:text-tertiary" @click="toggleMenu">Inicio</a>
                <a href="#our_recomendations" class="text-primary hover:text-tertiary" @click="toggleMenu">Recomendados</a>
                <a href="#products" class="text-primary hover:text-tertiary" @click="toggleMenu">Productos</a>
                <a href="#faqs" class="text-primary hover:text-tertiary" @click="toggleMenu">FAQS</a>
                <a href="#footer" class="text-primary hover:text-tertiary" @click="toggleMenu">Sobre nosotros</a>
            </div>
        </transition>
        -->
        
        <!-- 
        <a href="#home" class="text-gray-75 hover:text-tertiary cursor-pointer">
            <svg width="32" height="31" viewBox="0 0 32 31" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                <path class="fill-current" d="M17.0159 3.03837C16.7669 2.75451 16.4034 2.58866 16.0189 2.58338C15.6344 2.57811 15.2662 2.73393 15.009 3.01084L3.00896 15.9275C2.65672 16.3067 2.5678 16.8511 2.78202 17.3171C2.99624 17.7831 3.47347 18.0833 4.00002 18.0833H6.66669V25.8333C6.66669 26.5466 7.26364 27.1249 8.00002 27.1249H13.3334V20.6666H18.6667V27.1249H24C24.7364 27.1249 25.3334 26.5466 25.3334 25.8333V18.0833H27.3334C27.8531 18.0833 28.3254 17.7907 28.5436 17.3337C28.7617 16.8768 28.6859 16.3387 28.3493 15.955L17.0159 3.03837Z"/>
            </svg>                
        </a>
        <a href="#faqs" class="text-gray-75 hover:text-tertiary cursor-pointer">
            <svg width="31" height="31" viewBox="0 0 31 31" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                <path class="fill-current" fill-rule="evenodd" clip-rule="evenodd" d="M5.78225 19.6464C7.4799 17.2799 10.4865 15.4999 15.4999 15.4999C20.5132 15.4999 23.5199 17.2799 25.2175 19.6464C26.8582 21.9336 27.1196 24.5552 27.1248 26.0058C27.13 27.4645 25.9071 28.4166 24.6533 28.4166H6.34642C5.09262 28.4166 3.86971 27.4645 3.87496 26.0058C3.88017 24.5552 4.1415 21.9336 5.78225 19.6464Z"/>
                <path class="fill-current" fill-rule="evenodd" clip-rule="evenodd" d="M15.5 12.9166C18.3535 12.9166 20.6667 10.6034 20.6667 7.74992C20.6667 4.89645 18.3535 2.58325 15.5 2.58325C12.6465 2.58325 10.3333 4.89645 10.3333 7.74992C10.3333 10.6034 12.6465 12.9166 15.5 12.9166Z"/>
            </svg>
        </a>
        -->
    </nav>    
</template>

<script setup>
    import { ref, onMounted } from 'vue';

    // Estado para mostrar u ocultar el menú
    const isOpen = ref(false); 

    const toggleMenu = () => {
        isOpen.value = !isOpen.value;
    };

    // Show logo
    const showLogo = ref(false);

    onMounted(() => {
        setTimeout(() => {
            showLogo.value = true;
        }, 300); // Retraso para ver la animación
    });
</script>

<style>
    /* Animación del menú */
    .fade-enter-active, .fade-leave-active {
        transition: opacity 0.3s ease-in-out;
    }
    .fade-enter-from, .fade-leave-to {
        opacity: 0;
    }

    /* Animación personalizada con Tailwind */
    @keyframes fade-slide {
        0% {
            transform: translateX(-50px);
            opacity: 0;
        }
        100% {
            transform: translateX(0);
            opacity: 1;
        }
    }

    .animate-fade-slide {
        animation: fade-slide 0.8s ease-out forwards;
    }
</style>