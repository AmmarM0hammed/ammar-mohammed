<script>
import ExpertiseCard from "../components/ExpertiseCard.vue";

export default {
    name: "Expertise",
    components: {
        ExpertiseCard,
    }
}
</script>
<template >

    <div class="bg relative">
        <img src="../assets/BG/Group4.svg" class="w-[40.42px] left-[511px] top-[106px]">
        <img src="../assets/BG/Group5.svg" class="w-[91.23px] left-[500px] top-[601px]">
        <img src="../assets/BG/Group11.svg" class="w-[40px] left-[774px] top-[185px]">
        <img src="../assets/BG/Group10.png" class="w-[52.5px] left-[563px] top-[190px]">
        <img src="../assets/BG/Group12.svg" class="w-[70px] left-[1091px] top-[200px]">
    </div>
    <div id="expert" class="flex flex-col justify-center items-center my-52 align-top h-full ">
        <div class="text-center space-y-40">
            <p class="sm:text-6xl text-4xl md:text-7xl font-semibold line" v-motion :initial="{ opacity: 0, y: 100 }"
                :visibleOnce="{ opacity: 1, y: 0 }" :delay="500">
                My Expertise</p>


            <div class="flex mt-96 space-y-2 flex-wrap justify-center">

                <div class="flex flex-col justify-start space-y-5" v-motion :initial="{ opacity: 0, x: -100 }"
                    :visibleOnce="{ opacity: 1, x: 0 }" :delay="600">
                    <div class="flex flex-row items-center">
                        <img src="@/assets/lang/vue.png" class="w-20">
                        <div class="flex flex-col justify-start text-left space-y-0">
                            <p class="font-semibold text-2xl ">Forntend</p>
                            <p class="font-semibold text-2xl relative -top-2">Development</p>
                        </div>
                    </div>
                    <div class="flex flex-row justify-start ml-6 items-center">
                        <img src="@/assets/lang/H4.png" alt="">
                        <p class="font-light text-lg text-gray-300  w-72 text-left leading-8">
                            UI/UX. Over 4 years of development experience in HTML, CSS, JS   frameworks. VUE , TAILWINDCSS
                        </p>
                    </div>
                </div>
                <div class="divider divider-horizontal before:bg-white after:bg-white" v-motion
                    :initial="{ opacity: 0, x: -100 }" :visibleOnce="{ opacity: 1, x: 0 }" :delay="600"></div>
                    <div class="flex flex-col justify-start space-y-5" v-motion :initial="{ opacity: 0, x: -100 }"
                    :visibleOnce="{ opacity: 1, x: 0 }" :delay="700">
                    
                    <div class="flex flex-row items-center">
                        <img src="@/assets/lang/laravel.png" class="w-20">
                        <div class="flex flex-col justify-start text-left space-y-0">
                            <p class="font-semibold text-2xl ">Backend</p>
                            <p class="font-semibold text-2xl relative -top-2">Development</p>
                        </div>
                    </div>
                    <div class="flex flex-row justify-start ml-6 items-center">
                        <img src="@/assets/lang/H4.png" alt="">
                        <p class="font-light text-lg text-gray-300  w-72 text-left leading-8">
                            Experience in Laravel and php Over 5 Years of Development
                        </p>
                    </div>
                </div>

               
                <div class="divider divider-horizontal before:bg-white after:bg-white" v-motion
                    :initial="{ opacity: 0, x: -100 }" :visibleOnce="{ opacity: 1, x: 0 }" :delay="800"></div>

                    
                    <div class="flex flex-col justify-start space-y-5" v-motion :initial="{ opacity: 0, x: -100 }"
                    :visibleOnce="{ opacity: 1, x: 0 }" :delay="900">
                    
                    <div class="flex flex-row items-center">
                        <img src="@/assets/lang/flutter.png" class="w-20">
                        <div class="flex flex-col justify-start text-left space-y-0">
                            <p class="font-semibold text-2xl ">Flutter</p>
                            <p class="font-semibold text-2xl relative -top-2">Development</p>
                        </div>
                    </div>
                    <div class="flex flex-row justify-start ml-6 items-center">
                        <img src="@/assets/lang/H4.png" alt="">
                        <p class="font-light text-lg text-gray-300  w-72 text-left leading-8">
                            Skilled in developing hybrid mobile apps and cross-platform solutions using the Flutter framework.
                        </p>
                    </div>
                </div>

                    
               

                <div class="divider divider-horizontal lg:hidden  before:bg-white after:bg-white" v-motion
                    :initial="{ opacity: 0, x: -100 }" :visibleOnce="{ opacity: 1, x: 0 }" :delay="900"></div>
            </div>


        </div>
    </div>
</template>

<style scoped>

</style>