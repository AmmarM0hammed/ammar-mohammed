<script>
import ExpertiseCard from "../components/ExpertiseCard.vue";

export default {
    name:"Expertise",
    components:{
        ExpertiseCard,
    }
}
</script>
<template >

     <div class="bg relative">
            <img src="../assets/BG/Group 4.svg" class="w-[40.42px] left-[511px] top-[106px]">
            <img src="../assets/BG/Group 5.svg" class="w-[91.23px] left-[500px] top-[601px]">
            <img src="../assets/BG/Group 11.svg" class="w-[40px] left-[774px] top-[185px]">
            <img src="../assets/BG/Group 10.png" class="w-[52.5px] left-[563px] top-[190px]">
            <img src="../assets/BG/Group 12.svg" class="w-[70px] left-[1091px] top-[200px]">
     </div>
    <div id="expert" class="flex flex-col justify-center items-center my-52 align-top h-full ">
        <div class="text-center space-y-40" >
            <p class="sm:text-6xl text-4xl md:text-7xl font-semibold line" 
            v-motion
            :initial="{ opacity: 0, y: 100 }"
            :visibleOnce="{ opacity: 1, y: 0 }"
            :delay="500"
           >
            My Expertise</p>
           

            <div class="flex mt-96 space-y-2 flex-wrap justify-center">

               <ExpertiseCard 
               title="Frontend"
               imageName="vue.png" 
               disc=" UI/UX. Over 4 years of development experience in HTML, CSS, JS   frameworks. VUE , TAILWINDCSS" 
               :delay="600"
               />
                <div 
                class="divider divider-horizontal before:bg-white after:bg-white"
                v-motion
                :initial="{ opacity: 0, x: -100 }"
                :visibleOnce="{ opacity: 1, x: 0 }"
                :delay="600"
                ></div>
                
               <ExpertiseCard 
               title="Backend" 
               imageName="laravel.png" 
               disc=" Experience in Laravel and php Over 5 Years of Development"
               :delay="700"
                />
                <div 
                class="divider divider-horizontal before:bg-white after:bg-white"
                v-motion
                :initial="{ opacity: 0, x: -100 }"
                :visibleOnce="{ opacity: 1, x: 0 }"
                :delay="800"
                ></div>
                
               <ExpertiseCard
                title="Flutter"
                imageName="flutter.png"
                disc=" Skilled in developing hybrid mobile apps and cross-platform solutions using the Flutter framework."
                :delay="900"
                  />
                
                  <div 
                class="divider divider-horizontal lg:hidden  before:bg-white after:bg-white"
                v-motion
                :initial="{ opacity: 0, x: -100 }"
                :visibleOnce="{ opacity: 1, x: 0 }"
                :delay="900"
                ></div>
            </div>

           
        </div>
    </div>
</template>

<style scoped>

</style>