<script setup>
</script>

<template>
    <section class="w-full h-full bg-secondary">  
        <div class="flex flex-col lg:flex-row mx-30 py-10 lg:gap-12">
            <div class="flex flex-col lg:w-2/4 py-10 gap-12">
                <h3 class="text-4xl font-bold text-tertiary">15% DE DESCUENTO EN TU PRIMERA COMPRA ONLINE*</h3>
                <p class="text-base text-gray-75">
                    Suscríbete ahora para recibir las ultimas informaciones y ofertas exclusivas.                
                </p>
            </div>
            <!-- Subscription -->        
            <div class="flex flex-col lg:flex-row lg:w-2/4 lg:py-20 gap-12">
                <div class="flex flex-col gap-4 items-end">
                    <div class="flex flex-col gap-4">
                        <input 
                            type="email" 
                            placeholder="Correo electrónico" 
                            class="w-100 h-9 px-4 text-gray-75 border border-gray-75 rounded-xl"
                        >
                    </div>
                    <div class="flex flex-col gap-4">
                        <button class="h-9 bg-primary text-white border border-transparent rounded-xl w-67 
                            hover:bg-transparent hover:text-primary hover:border-primary transition duration-300 cursor-pointer"                         
                        >
                            Suscribirme
                        </button>
                        <!-- 
                            "h-9 bg-primary text-white border border-transparent rounded-md px-20 py-1 mx-auto
                            hover:bg-white hover:text-primary hover:border-primary transition duration-300 cursor-pointer"
                        -->
                    </div>
                </div>
            </div>

        </div>              
        
        <div class="pb-10">
            <p class="text-gray-75 text-center">*Oferta válida para nuevos suscriptores</p>
        </div>
    </section>
</template>