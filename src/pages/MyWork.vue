<script>
import MyWorkCard from '../components/MyWorkCard.vue';

export default {
    name:"MyWork",
    components:{
      MyWorkCard,
    }
}
</script>
<template>

<div class="bg relative">
            <img src="@/assets/BG/Group4.svg" class="w-[40.42px] left-[511px] top-[106px]">
            <img src="@/assets/BG/Group5.svg" class="w-[91.23px] left-[500px] top-[601px]">
            <img src="@/assets/BG/Group11.svg" class="w-[40px] left-[774px] top-[185px]">
            <img src="@/assets/BG/Group10.png" class="w-[52.5px] left-[563px] top-[190px]">
            <img src="@/assets/BG/Group12.svg" class="w-[70px] left-[1091px] top-[200px]">
</div>
  <div class=" flex-col justify-center align-middle min-h-screen  items-center overflow-hidden">

        <p class="sm:text-6xl text-4xl md:text-7xl font-semibold text-center " 
            v-motion
            :initial="{ opacity: 0, y: 100 }"
            :visibleOnce="{ opacity: 1, y: 0 }"
            :delay="400">
            My Work</p>
      <p class="py-5 text-md md:text-2xl font-medium text-center  break-all whitespace-pre-line my-3 "
            v-motion
            :initial="{ opacity: 0, y: -100 }"
            :visibleOnce="{ opacity: 1, y: 0 }"
            :delay="600"
            >
            These are some of the projects I've worked on in the past
       </p>
 
   
      <div class="flex flex-row flex-wrap gap-6 md:mx-24 justify-center my-20 ">
            <div 
            class=" card card-compact mx-5 md:mx-0 md:w-80 bg-base-200 shadow-xl"
            v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"   
            :delay="600"
            >
                  <figure><img src="@/assets/MyWork/coffee.png" alt="Work" class="rounded-3xl  transition-all hover:brightness-75"/></figure>
                  <div class="card-body">
                        <h2 class="card-title">Coffie App</h2>
                        <p>UI Coffee app store</p>
                        <div class="card-actions justify-end my-2">
                        </div>
                  </div>
            </div>
            
            <div 
            class=" card card-compact mx-5 md:mx-0 md:w-80 bg-base-200 shadow-xl"
            v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"   
            :delay="600"
            >
                  <figure><img src="@/assets/MyWork/doctor.png" alt="Work" class="rounded-3xl  transition-all hover:brightness-75"/></figure>
                  <div class="card-body">
                        <h2 class="card-title">Doctor App Reservation</h2>
                        <p>UI Doctor App Reservation</p>
                        <div class="card-actions justify-end my-2">
                        </div>
                  </div>
            </div>

            <div 
            class=" card card-compact mx-5 md:mx-0 md:w-80 bg-base-200 shadow-xl"
            v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"   
            :delay="600"
            >
                  <figure><img src="@/assets/MyWork/doctorweb.png" alt="Work" class="rounded-3xl  transition-all hover:brightness-75"/></figure>
                  <div class="card-body">
                        <h2 class="card-title">Doctor Website  Reservation</h2>
                        <p>UI & Frontend & backend Doctor Website Reservation</p>
                        <div class="card-actions justify-end my-2">
                        </div>
                  </div>
            </div>

            <div 
            class=" card card-compact mx-5 md:mx-0 md:w-80 bg-base-200 shadow-xl"
            v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"   
            :delay="600"
            >
                  <figure><img src="@/assets/MyWork/food.png" alt="Work" class="rounded-3xl  transition-all hover:brightness-75"/></figure>
                  <div class="card-body">
                        <h2 class="card-title">Menu Restaurant App</h2>
                        <p>Flutter App Menu Restaurant</p>
                        <div class="card-actions justify-end my-2">
                        </div>
                  </div>
            </div>
           
            <div 
            class=" card card-compact mx-5 md:mx-0 md:w-80 bg-base-200 shadow-xl"
            v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"   
            :delay="600"
            >
                  <figure><img src="@/assets/MyWork/movies.png" alt="Work" class="rounded-3xl  transition-all hover:brightness-75"/></figure>
                  <div class="card-body">
                        <h2 class="card-title">Netflex Clone App</h2>
                        <p>Flutter App Movies</p>
                        <div class="card-actions justify-end my-2">
                        </div>
                  </div>
            </div>
           
           
            <div 
            class=" card card-compact mx-5 md:mx-0 md:w-80 bg-base-200 shadow-xl"
            v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"   
            :delay="600"
            >
                  <figure><img src="@/assets/MyWork/photo.png" alt="Work" class="rounded-3xl  transition-all hover:brightness-75"/></figure>
                  <div class="card-body">
                        <h2 class="card-title">Photo App</h2>
                        <p>Flutter App Photo Frontend & Backend</p>
                        <div class="card-actions justify-end my-2">
                        </div>
                  </div>
            </div>
           
            <div 
            class=" card card-compact mx-5 md:mx-0 md:w-80 bg-base-200 shadow-xl"
            v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"   
            :delay="600"
            >
                  <figure><img src="@/assets/MyWork/song.png" alt="Work" class="rounded-3xl  transition-all hover:brightness-75"/></figure>
                  <div class="card-body">
                        <h2 class="card-title">Frontend Vue Music App</h2>
                        <p>Vue Music App</p>
                        <div class="card-actions justify-end my-2">
                        </div>
                  </div>
            </div>
           
            <div 
            class=" card card-compact mx-5 md:mx-0 md:w-80 bg-base-200 shadow-xl"
            v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"   
            :delay="600"
            >
                  <figure><img src="@/assets/MyWork/store.png" alt="Work" class="rounded-3xl  transition-all hover:brightness-75"/></figure>
                  <div class="card-body">
                        <h2 class="card-title">Flutter Store App</h2>
                        <p>Flutter Store App</p>
                        <div class="card-actions justify-end my-2">
                        </div>
                  </div>
            </div>
           
           
            <div 
            class=" card card-compact mx-5 md:mx-0 md:w-80 bg-base-200 shadow-xl"
            v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"   
            :delay="600"
            >
                  <figure><img src="@/assets/MyWork/1.png" alt="Work" class="rounded-3xl  transition-all hover:brightness-75"/></figure>
                  <div class="card-body">
                        <h2 class="card-title">Flutter Todolist App</h2>
                        <p>Flutter Todolist App</p>
                        <div class="card-actions justify-end my-2">
                        </div>
                  </div>
            </div>
           
           
      
            
      </div>

</div>


</template>
