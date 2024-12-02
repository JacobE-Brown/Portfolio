<script setup>
import CustomHeader from "./components/header.vue";
import Menu from "./components/menu.vue";
import animatedHeader from "./components/animatedHeaderBackground.vue";
import About from "./components/about.vue";

import Switch from "./components/switch.vue";
</script>

<template>
    <div class="h-screen overflow-y-scroll scroll- snap-y snap-mandatory">
        <CustomHeader class="h-[93vh] snap-start bg-green-200 scroll-m-[7vh]" />
        <div class="no-snap-element sticky top-0">
            <Menu />
        </div>
        <section class="h-[93vh] snap-start bg-green-200 scroll-m-[7vh]">
            <p>Hello World!</p>
        </section>
        <section class="h-[93vh] snap-start bg-green-200 scroll-m-[7vh]">
            <p>Hello World!</p>
        </section>
        <section class="h-[93vh] snap-start bg-green-200 scroll-m-[7vh]">
            <p>Hello World!</p>
        </section>
        <section class="h-[93vh] snap-start bg-green-200 scroll-m-[7vh]">
            <p>Hello World!</p>
        </section>
    </div>
</template>

<style scoped></style>
