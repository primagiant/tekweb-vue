<template>
    <nav class="h-24 bg-indigo-50 flex justify-between items-center shadow-lg px-12">
        <div class="flex justify-center items-center">
            <h1 class="text- sm:text-xl md:text-2xl font-pacifico">My Apps</h1>
            <router-link class="font-quicksand text-sm ml-4 p-2 md:ml-8 md:p-4 hover:bg-white" to="/">Home</router-link>
            <router-link class="font-quicksand text-sm ml-2 p-2 md:ml-4 md:p-4 hover:bg-white" to="/kasir">Kasir</router-link>
            <router-link class="font-quicksand text-sm ml-2 p-2 md:ml-4 md:p-4 hover:bg-white" to="/about">About</router-link>
        </div>
        <div class="h-10 w-10 rounded-full bg-white flex justify-center items-center">
            <img class="h-6" src="../assets/logo.png" alt="image not found" />
        </div>
    </nav>
</template>

<script>
export default {
    name: "Navbar",
};
</script>
