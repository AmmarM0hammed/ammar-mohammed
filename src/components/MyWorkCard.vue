<script>
export default {
    name:"CardMyWork",
    props:{
        image:String,
        title:String,
        disc:String,
        path:String,
    }
}
</script>
<template >
    <div 
    class=" card card-compact mx-5 md:mx-0 md:w-80 bg-base-200 shadow-xl"
    v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"
           
            :delay="600"
    >
        <figure><img :src="'src/assets/MyWork/'+image" alt="Work" class="rounded-3xl  transition-all hover:brightness-75"/></figure>
        <div class="card-body">
            <h2 class="card-title">{{title}}</h2>
            <p>{{ disc }}</p>
            <div class="card-actions justify-end my-2">
                <!-- <a :href="path" class="btn btn-primary">Details</a> -->
            </div>
        </div>
    </div>
</template>

