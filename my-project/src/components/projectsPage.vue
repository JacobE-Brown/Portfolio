<script>
    import PageDoubleColumnContainer from "./PageDoubleColumnContainer.vue";
    import ProjectCard from "./projectCard.vue";
    export default {
        name: "projects",
        components: {
            PageDoubleColumnContainer,
            ProjectCard,
        },
    };
</script>
<template>
    <PageDoubleColumnContainer>
        <template #header2>My Projects</template>
        <template #content2>
            <div class="h-full">
                <div class="grid grid-cols-1 gap-5 p-5 h-full lg:grid-cols-2">
                    <!-- Maxwell -->
                    <a href="https://youtu.be/ycHVUvvOwzY?si=Hbt2j8kP9Bc7YYmh" target="_blank">
                        <ProjectCard>
                            <template #projectTitle>
                                Maxwell The CAT!
                            </template>
                            <template #projectImg>
                                <img
                                    src="/public/assets/photos/maxwell-cat-cat.gif"
                                    class="object-cover w-full h-full"
                                />
                            </template>
                            <template #content>
                                <p>Maxwell dance and Maxwell spin all in one</p>
                                <p>
                                    I just like the Maxwell the cat meme for the
                                    song, and the fact it’s a cat spinning
                                    and/or dancing
                                </p>
                            </template>
                        </ProjectCard></a
                    >
                    <a href="#" target="_blank"> <ProjectCard> </ProjectCard></a>
                    <a href="#" target="_blank"> <ProjectCard> </ProjectCard></a>
                    <a href="#" target="_blank"> <ProjectCard> </ProjectCard></a>
                    <a href="#" target="_blank"> <ProjectCard> </ProjectCard></a>
                    <a href="#" target="_blank"> <ProjectCard> </ProjectCard></a>
                    <a href="#" target="_blank"> <ProjectCard> </ProjectCard></a>
                </div>
            </div>
        </template>
    </PageDoubleColumnContainer>
</template>
