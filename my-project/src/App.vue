<script setup>
    import CustomBanner from "./components/banner.vue";
    import Menu from "./components/menu.vue";
    import About from "./components/aboutPage.vue";
    import projectsPage from "./components/projectsPage.vue";
    import contactPage from "./components/contactPage.vue";
</script>

<template>
    <div class="overflow-y-scroll mx-auto h-screen snap-y snap-mandatory">
        <header class="h-[93vh] snap-start scroll-m-[7vh]">
            <CustomBanner />
        </header>
        <div class="sticky top-0 no-snap-element">
            <Menu />
        </div>
        <section class="h-[93vh] snap-start scroll-m-[7vh]">
            <About />
        </section>
        <section class="h-[93vh] snap-start scroll-m-[7vh]">
            <projectsPage></projectsPage>
        </section>
        <section class="h-[93vh] snap-start scroll-m-[7vh]">
            <contactPage></contactPage>
        </section>
    </div>
</template>

<style scoped></style>
