<script>
export default {
    name : "Home",

}

</script>
<template>
     <div>
        <!-- <img src="../assets/bg.png" class="absolute bg-repeat-y top-0"> -->
    </div>
    <div class="flex flex-col justify-center items-center mt-80 space-y-48">

        <div class="text-center space-y-4" >
            <p class="text-4xl md:text-7xl font-semibold" 
            v-motion
            :initial="{ opacity: 0, y: 100 }"
            :enter="{ opacity: 1, y: 0 }"
            :delay="500">
            Ammar Mohammed</p>
            <p class="text-md md:text-3xl font-light"
            v-motion
            :initial="{ opacity: 0, y: 100 }"
            :enter="{ opacity: 1, y: 0 }"
            :delay="400"
            
            >
                Frontend , Backend , Mobile <span class="text-primary">Developer</span> 
            </p>
        </div>
        
        <div v-motion
            :initial="{ opacity: 0 ,scale:0}"
            :enter="{ opacity: 1, scale:1}"
            :delay="700"

            class="animate-bounce"
            >
           <a href="#expert"> <img src="../assets/Dodils/mouse.png"  class="w-12"></a>
        </div>
        
    </div>
 

</template>
