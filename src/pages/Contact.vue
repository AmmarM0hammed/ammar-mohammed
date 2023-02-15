<script>
export default {
    name:"Contact"
}
</script>
<template>
    <div class="relative bg">
    <img src="../assets/BG/Ellipse9.svg" class="w-[233px] left-[1400px] top-[108px]">
    <img src="../assets/BG/Ellipse7.svg" class="w-[90px] left-[189px] top-[600px]">
    <img src="../assets/BG/Polygon3.svg" class="w-[176px] left-[1110px] top-[500px]">
    <img src="../assets/BG/Rectangle16.svg" class="w-[40px] left-[360px] top-[200px]">
    <img src="../assets/BG/Rectangle17.svg" class="w-[40px] left-[800px] top-[280px]">
    <img src="../assets/BG/Group4.svg" class="w-[40.42px] left-[511px] top-[106px]">
    <img src="../assets/BG/Group5.svg" class="w-[91.23px] left-[500px] top-[601px]">
    <img src="../assets/BG/Group11.svg" class="w-[40px] left-[774px] top-[185px]">
   <img src="../assets/BG/Group10.png" class="w-[52.5px] left-[563px] top-[190px]">
    </div>
    <div class="flex flex-col justify-start min-h-screen px-5 md:mx-32">
        <div class="sm:text-5xl text-4xl md:text-6xl font-semibold"
            v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"
            :delay="500"
        >
           Available for 
          <p>Design or developed</p>
        </div>

        <div class="sm:text-3xl text-2xl md:text-4xl font-light mt-10 space-y-3"
        v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"
            :delay="700"
        >
           <p> Have an <span class="text-primary">project</span> you need help with ?</p>
           <p>Send me an email or contact me via </p>
            <p> instant message !</p>
        </div>

        <div class="mt-16 space-y-10"
        v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"
            :delay="900"
        >
            <p class="sm:text-4xl text-3xl md:text-5xl font-semibold"><span class="text-primary">+964</span>7729830123</p>

            <p class="sm:text-4xl text-3xl md:text-5xl font-semibold">amar661232<span class="text-primary">@gmail.com</span></p>

            <p class=" hover:text-primary w-fit transition-all">
                 <a href="https://github.com/AmmarM0hammed" target="_blank" class=" sm:text-4xl text-3xl md:text-5xl font-semibold"><span class="text-primary">git</span>hub</a>
            </p>
            <p class="sm:text-4xl text-3xl md:text-5xl font-semibold"><span class="text-primary">@</span>_jk_4</p>

           
        </div>
    </div>
</template>
