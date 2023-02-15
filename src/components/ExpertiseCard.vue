<script>
export default {
    name:"ExpertiseCard",
    props:{
        title:String,
        imageName:String,
        disc:String,
        delay:0,
    }
}
</script>
<template >
        <div 
        class="flex flex-col justify-start space-y-5"
        v-motion
            :initial="{ opacity: 0, x: -100 }"
            :visibleOnce="{ opacity: 1, x: 0 }"
            :delay="delay"
        >
                    <div class="flex flex-row items-center">
                        <img :src="'src/assets/lang/' +imageName" class="w-20">
                        <div class="flex flex-col justify-start text-left space-y-0">
                            <p class="font-semibold text-2xl ">{{title}}</p>
                             <p class="font-semibold text-2xl relative -top-2">Development</p>
                        </div>
                    </div>
                    <div class="flex flex-row justify-start ml-6 items-center" >
                        <img src="../assets/lang/H4.png" alt="">
                        <p class="font-light text-lg text-gray-300  w-72 text-left leading-8">
                            {{ disc }}
                        </p>
                    </div>
                </div>
</template>

