<script>
export default {
    name: "Navbar",
   
}

</script>
<template>
    <nav>
        <div class="navbar absolute top-0  h-24 lg:px-44 z-50  ">
            <div class="navbar-start">
                <a class=" h-fit w-28">
                    <img src="../assets/logo.png" class="w-20">
                </a>
            </div>
            <div class="navbar-center hidden md:flex space-x-10 md:space-x-20">
                <!-- <a href="" class="btn-nav active">Home</a>
                <a class="btn-nav ">Expertise</a>
                <a class="btn-nav ">Work</a>
                <a class="btn-nav ">Experience</a>
                <a class="btn-nav ">Contact</a> -->
            </div>
            <!-- <div class="navbar-end md:hidden">
                <button class="btn btn-square btn-ghost">
                    <box-icon name='menu-alt-right' color="white" size="md"></box-icon>
                </button>
            </div> -->
        </div>
    </nav>
</template>

