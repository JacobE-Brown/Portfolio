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
                    <a
                        href="https://jacobe-brown.github.io/SWDV%20102/SWDV%20140/Final%20Project/Index.html"
                        target="_blank"
                    >
                        <ProjectCard>
                            <template #projectTitle>
                                FizzCraft Website Project
                            </template>
                            <template #projectImg>
                                <img
                                    src="/public/images/FizzCraft.png"
                                    class="object-cover w-full h-full"
                                    loading="lazy"
                                />
                            </template>
                            <template #content>
                                <p>Final Project of SWDV 140</p>
                                <p>
                                    This Website is made with plain css (Sass),
                                    HTML, and Javascript.
                                </p>
                                <p>
                                    I am particularly proud of the SVG animation
                                    I was able to accomplish by exporting it from
                                    inkscape and animating the peices with css.
                                </p>
                            </template>
                        </ProjectCard></a
                    >
                    <a
                        href="https://jacobe-brown.github.io/SWDV%20102/SWDV%20143/Project%201%20--%20Paralax/index.html"
                        target="_blank"
                    >
                        <ProjectCard
                            ><template #projectTitle>
                                Parallax Website Made with Bootstrap 5
                            </template>
                            <template #projectImg>
                                <img
                                    src="/public/images/BootStrap.png"
                                    class="object-cover w-full h-full"
                                    loading="lazy"
                                />
                            </template>
                            <template #content>
                                <p>
                                    This simple website walks through a
                                    simplified history of the concept of
                                    Parallax.
                                </p>
                                <p>
                                    Mostly though it was to practice making
                                    websites with BootStrap 5.
                                </p>
                                <p>
                                    I am happy with the result, as simple as it
                                    may be.
                                </p>
                            </template>
                        </ProjectCard></a
                    >
                    <a
                        href="http://reacttube.s3-website-us-east-1.amazonaws.com/"
                        target="_blank"
                    >
                        <ProjectCard
                            ><template #projectTitle>
                                Simple React Social Media Card
                            </template>
                            <template #projectImg>
                                <img
                                    src="/public/images/ReactJSApp.png"
                                    class="object-cover w-full h-full"
                                    loading="lazy"
                                />
                            </template>
                            <template #content>
                                <p>
                                    This Project I focused on making a small,
                                    detailed, responsive social media card in
                                    Reac.JS
                                </p>
                                <p>
                                    It includes the social media card itself,
                                    and two other pages that are linked to in
                                    the React-Router.
                                </p>
                                <p>
                                    The Like and Dislike buttons are reactive
                                    and follow reasonable logic for allowing
                                    only one like or one dislike.
                                </p>
                            </template>
                        </ProjectCard></a
                    >
                    <a
                        href="#"
                        target="_blank"
                    >
                        <ProjectCard>
                            <template #projectTitle>
                                AWS Static Website Hosting
                            </template>
                            <template #projectImg>
                                <img
                                    src="/public/images/AWS.jpg"
                                    class="object-cover w-full h-full"
                                    loading="lazy"
                                />
                            </template>
                            <template #content>
                                <p>
                                    I understand the basics of AWS and how to
                                    host a static website and how to use Route
                                    53 to point a domain name to an S3 bucket.
                                </p>
                                <p>
                                    Most of my Framework websites are Hosted on
                                    my AWS account. Those website were developed
                                    on a live server with Vite and then exported
                                    with <code> npm run build </code> then
                                    submited to AWS.
                                </p>
                            </template></ProjectCard
                        ></a
                    >
                    <a
                        href="#"
                        target="_blank"
                    >
                        <ProjectCard>
                            <template #projectTitle>
                                Vite Web Development Environment.
                            </template>
                            <template #projectImg>
                                <img
                                    src="/public/images/Vite.jpg"
                                    class="object-cover w-full h-full"
                                    loading="lazy"
                                />
                            </template>
                            <template #content>
                                <p>My preferred bundler is Vite.</p>
                                <p>
                                    I appreciate its simplicity, speed, and
                                    minification. All of which have greatly
                                    aided in my website development.
                                </p>
                            </template>
                        </ProjectCard></a
                    >
                </div>
            </div>
        </template>
    </PageDoubleColumnContainer>
</template>
