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
            <img src="../assets/BG/Group 4.svg" class="w-[40.42px] left-[511px] top-[106px]">
            <img src="../assets/BG/Group 5.svg" class="w-[91.23px] left-[500px] top-[601px]">
            <img src="../assets/BG/Group 11.svg" class="w-[40px] left-[774px] top-[185px]">
            <img src="../assets/BG/Group 10.png" class="w-[52.5px] left-[563px] top-[190px]">
            <img src="../assets/BG/Group 12.svg" class="w-[70px] left-[1091px] top-[200px]">
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
            <MyWorkCard 
            title="Coffie App"
            image="coffee.png"
            disc="UI Coffee app store"
            path="#"
            />
            <MyWorkCard 
            title="Doctor App Reservation"
            image="doctor.png"
            disc="UI Doctor App Reservation"
            path="#"
            />
            <MyWorkCard 
            title="Doctor Website  Reservation"
            image="doctorweb.png"
            disc="UI & Frontend & backend Doctor Website Reservation"
            path="#"
            />
            <MyWorkCard 
            title="Menu Restaurant App"
            image="food.png"
            disc="Flutter App Menu Restaurant"
            path="#"
            />
            <MyWorkCard 
            title="Netflex Clone App"
            image="movies.png"
            disc="Flutter App Movies"
            path="#"
            />
            <MyWorkCard 
            title="Photo App "
            image="photo.png"
            disc="Flutter App Photo Frontend & Backend"
            path="#"
            />
            <MyWorkCard 
            title="Frontend Vue Music App"
            image="song.png"
            disc="Vue Music App"
            path="#"
            />
            <MyWorkCard 
            title="Flutter Store App"
            image="store.png"
            disc="Flutter Store App"
            path="#"
            />
            
            
      </div>

</div>


</template>
