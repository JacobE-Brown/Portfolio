<script setup>
    import CustomBanner from "./components/MainBanner.vue";
    import Menu from "./components/menu.vue";
    import About from "./pages/aboutPage.vue";
    import projectsPage from "./pages/projectsPage.vue";
    import contactPage from "./pages/contactPage.vue";
    import CustomFooter from "./components/footer.vue";
</script>

<template>
    <div class="overflow-y-scroll mx-auto h-screen snap-y snap-mandatory scroll-smooth">
        <header
            id="Home"
            class="h-[93vh] snap-start scroll-m-[7vh]"
        >
            <CustomBanner />
        </header>
        <div class="sticky top-0 no-snap-element">
            <Menu />
        </div>
        <section
            id="AboutMe"
            class="h-[93vh] snap-start scroll-m-[7vh]"
        >
            <About />
        </section>
        <section
            id="MyProjects"
            class="h-[93vh] snap-start scroll-m-[7vh]"
        >
            <projectsPage></projectsPage>
        </section>
        <section
            id="ContactMe"
            class="h-[86vh] snap-start scroll-m-[7vh]"
        >
            <contactPage></contactPage>
        </section>
        <footer>
            <CustomFooter></CustomFooter>
        </footer>
    </div>
</template>

<style scoped></style>
