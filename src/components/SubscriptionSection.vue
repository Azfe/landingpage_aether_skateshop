<script setup>
</script>

<template>
    <section class="w-full h-full bg-secondary">
        <div class="w-full h-1 bg-secondary"></div>
        <hr class="border-t-3 border-tertiary w-4/5 mx-auto my-17 rounded-full">
        <div class="flex flex-col lg:flex-row mx-30 gap-12">
            <h3 class="text-4xl font-bold text-white text-nowrap">Suscríbete</h3>
            <p class="text-lg text-white">
                Fusce risus lorem, ultrices non posuere eget, malesuada ac odio. Nunc  sem ipsum, hendrerit a ante nec, lobortis placerat elit. Nullam  malesuada venenatis orci ut rutrum. Quisque non nisi non elit auctor  rhoncus non sed metus. Donec eu fermentum velit. Sed elementum efficitur  risus eu pulvinar.
            </p>
        </div>
        <!-- Subscription -->        
        <div class="flex flex-col lg:flex-row mx-30 py-20 gap-12">
            <div class="flex flex-col lg:flex-row gap-8">
                <div class="flex flex-col gap-4">
                    <input type="email" placeholder="Correo electrónico" class="w-378 h-14 px-4 text-black border border-tertiary rounded-4xl">
                </div>
                <div class="flex flex-col gap-4">
                    <button class="w-378 h-14 bg-tertiary text-white border border-transparent rounded-4xl hover:bg-white hover:text-tertiary hover:border-tertiary transition duration-300 cursor-pointer">
                        Suscribirme
                    </button>
                </div>
            </div>                
        </div>

    </section>
</template>