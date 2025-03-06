<script setup>
</script>

<template>
    <section id="videos" class="w-full h-full bg-white">
        <div class="w-full h-1 bg-white"></div>
        <hr class="border-t-3 border-secondary w-4/5 mx-auto my-17 rounded-full">
        <div class="flex flex-col lg:flex-row mx-30 gap-12">
            <h3 class="text-4xl font-bold text-tertiary text-nowrap">Ver videos</h3>
            <p class="text-lg text-tertiary">
                Fusce risus lorem, ultrices non posuere eget, malesuada ac odio. Nunc  sem ipsum, hendrerit a ante nec, lobortis placerat elit. Nullam  malesuada venenatis orci ut rutrum. Quisque non nisi non elit auctor  rhoncus non sed metus. Donec eu fermentum velit. Sed elementum efficitur  risus eu pulvinar.
            </p>
        </div>
        <!-- Videos -->        
        <div class="flex flex-col lg:flex-row mx-30 py-20 gap-12">
            <div class="flex flex-col lg:flex-row gap-8">
                <!-- Video 1 -->                
                <a href="#" class="relative">
                    <img src="../assets/images/videos_section/video_1.jpg" alt="Video 1" class="w-full h-auto rounded-lg">
                    <div class="absolute inset-0 flex items-end justify-end p-4">
                        <!-- Botón de Play -->
                    <button class="
                        button-play absolute inset-0 m-auto flex items-center justify-center w-1/4 h-1/4 max-w-full max-h-full 
                        bg-opacity-50 rounded-full transition-colors duration-300 cursor-pointer"
                    >
                        <svg 
                            viewBox="0 0 22 27" fill="currentColor" xmlns="http://www.w3.org/2000/svg" 
                            class="w-2/3 h-2/3 ml-1"
                        >
                            <path d="M21.05 11.4291L3.04 0.411562C2.73636 0.225628 2.38858 0.124123 2.0326 0.11753C1.67661 0.110938 1.32532 0.199497 1.015 0.374061C0.707637 0.545914 0.451595 0.796535 0.273205 1.10015C0.0948143 1.40377 0.000513572 1.74942 0 2.10156V24.1341C0.00231596 24.6623 0.214292 25.168 0.58933 25.54C0.964367 25.912 1.47177 26.1198 2 26.1178C2.36869 26.1177 2.73023 26.016 3.045 25.8241L21.05 14.8066C21.3394 14.6302 21.5786 14.3823 21.7446 14.0868C21.9105 13.7912 21.9977 13.458 21.9977 13.1191C21.9977 12.7801 21.9105 12.4469 21.7446 12.1514C21.5786 11.8558 21.3394 11.608 21.05 11.4316V11.4291ZM2 24.1103V2.11781L19.9788 13.1178L2 24.1103Z"/>
                        </svg>
                    </button>
                    </div>
                </a>                            
                <!-- Video 2 -->
                <a href="#" class="relative">
                    <!-- Imagen -->
                    <img src="../assets/images/videos_section/video_2.jpg" alt="Video 2" class="w-full h-auto rounded-lg">

                    <!-- Botón de Play -->
                    <button class="
                        button-play absolute inset-0 m-auto flex items-center justify-center w-1/4 h-1/4 max-w-full max-h-full 
                        bg-opacity-50 rounded-full transition-colors duration-300 cursor-pointer"
                    >
                        <svg 
                            viewBox="0 0 22 27" fill="currentColor" xmlns="http://www.w3.org/2000/svg" 
                            class="w-2/3 h-2/3 ml-1"
                        >
                            <path d="M21.05 11.4291L3.04 0.411562C2.73636 0.225628 2.38858 0.124123 2.0326 0.11753C1.67661 0.110938 1.32532 0.199497 1.015 0.374061C0.707637 0.545914 0.451595 0.796535 0.273205 1.10015C0.0948143 1.40377 0.000513572 1.74942 0 2.10156V24.1341C0.00231596 24.6623 0.214292 25.168 0.58933 25.54C0.964367 25.912 1.47177 26.1198 2 26.1178C2.36869 26.1177 2.73023 26.016 3.045 25.8241L21.05 14.8066C21.3394 14.6302 21.5786 14.3823 21.7446 14.0868C21.9105 13.7912 21.9977 13.458 21.9977 13.1191C21.9977 12.7801 21.9105 12.4469 21.7446 12.1514C21.5786 11.8558 21.3394 11.608 21.05 11.4316V11.4291ZM2 24.1103V2.11781L19.9788 13.1178L2 24.1103Z"/>
                        </svg>
                    </button>
                </a>
                <!-- Video 3 -->                
                <a href="#" class="relative">
                    <img src="../assets/images/videos_section/video_3.jpg" alt="Video 3" class="w-full h-auto rounded-lg">                    
                    <!-- Botón de Play -->
                    <button class="
                        button-play absolute inset-0 m-auto flex items-center justify-center w-1/4 h-1/4 max-w-full max-h-full 
                        bg-opacity-50 rounded-full transition-colors duration-300 cursor-pointer"
                    >
                        <svg 
                            viewBox="0 0 22 27" fill="currentColor" xmlns="http://www.w3.org/2000/svg"
                            class="w-2/3 h-2/3 ml-1"
                        >
                            <path d="M21.05 11.4291L3.04 0.411562C2.73636 0.225628 2.38858 0.124123 2.0326 0.11753C1.67661 0.110938 1.32532 0.199497 1.015 0.374061C0.707637 0.545914 0.451595 0.796535 0.273205 1.10015C0.0948143 1.40377 0.000513572 1.74942 0 2.10156V24.1341C0.00231596 24.6623 0.214292 25.168 0.58933 25.54C0.964367 25.912 1.47177 26.1198 2 26.1178C2.36869 26.1177 2.73023 26.016 3.045 25.8241L21.05 14.8066C21.3394 14.6302 21.5786 14.3823 21.7446 14.0868C21.9105 13.7912 21.9977 13.458 21.9977 13.1191C21.9977 12.7801 21.9105 12.4469 21.7446 12.1514C21.5786 11.8558 21.3394 11.608 21.05 11.4316V11.4291ZM2 24.1103V2.11781L19.9788 13.1178L2 24.1103Z"/>
                        </svg>
                    </button>                  
                </a>     
                               
            </div>                
        </div>
    </section>
</template>

<style scoped>
    .button-play{
        background-color: rgba(215, 6, 48, 0.801);
        /*transition: color 0.3s; */       
    }
    .button-play:hover{
        background-color: rgba(166, 237, 142, 0.85);
    }
</style>