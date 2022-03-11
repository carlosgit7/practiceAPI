<script setup>
  import Nav from "./components/Nav.vue"
</script>

<template>
<div class="min-h-screen bg-slate-400 bg-cover bg-center" style="background-image: url('./public/elements.jpg')">
    <Nav />
    <div class="container mx-auto grid justify-items-center">
     <router-view />
    </div>
</div>
</template>

