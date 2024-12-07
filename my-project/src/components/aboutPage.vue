<script>
    import doubleContainer from "./PageDoubleColumnContainer.vue";
    export default {
        name: "about",
        components: {
            doubleContainer,
        },
    };
</script>

<template>
    <doubleContainer>
        <template #header1>About Me</template>
        <template #content1>
            <div
                class="flex flex-col gap-5 p-5 w-full h-full font-serif font-medium md:text-2xl">
                <p>
                    I first graduated from <i>Magdalen College</i> in May of
                    2023 with a degree in the
                    <em>Liberal Arts majoring in History</em>. From my Alma
                    Mater I learned how to read and write well while also
                    immersing myself in the classics.
                </p>
                <p>
                    I must also say of myself that after graduation I got
                    married to Brianna Brown in May of 2023. As
                    <cite>Jane Austen</cite> once said:
                </p>
                <blockquote>
                    “It is a truth universally acknowledged, that a single man
                    in possession of a good fortune, must be in want of a wife.”
                    (Austen, <i>Pride and Prejudice</i>,
                    <cite>Canturbery classics</cite>, 1)
                </blockquote>
                <p>
                    Well, I must acknowledge that it is a universal truth that a
                    married man in possesion of a good wife, must be in need of
                    a good fortune. Now I am taking the
                    <strong>Software Development course (SWDV)</strong> from the
                    <i>College of Western Idaho</i> (CWI) in order to earn that
                    fortune.
                </p>
            </div>
        </template>
        <template #header2>MY GLORIOUS THESIS!!!!!</template>
        <template #content2>
            <!-- <div class="w-full h-full nt:hidden md:block">

                <object
                    data="/public/documents/BrownJacobThesis.pdf#zoom=75"
                    type="application/pdf"
                    class="w-full h-full"></object>
            </div>

            <div class="md:hidden">
                <p class="p-5">
                    This is the thesis I wrote for the completion of my
                    batchulars degree at Magdalen College.
                </p>
                <a href="/public/documents/BrownJacobThesis.pdf"
                    ><img
                        src="../assets/CoverPage_page-0001.jpg"
                        alt="Jacob Brown Thesis On The Nature of History"
                /></a>
            </div> -->
        </template>
    </doubleContainer>
</template>
