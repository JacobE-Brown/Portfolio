<script>
    export default {
        name: "Banner",
        // component logic goes here
    };
</script>

<template>
    <div
        class="h-[93vh] w-svw overflow-y-auto mx-auto flex flex-col justify-evenly gap-4 md:gap items-center md:flex-row lg:justify-center lg:gap-40"
    >
        <div
            class="m-3 grid grid-rows-3 max-h-[30vh] md:max-h-[85vh] gap-5 md:h-auto"
        >
            <div
                class="flex justify-start items-center whitespace-nowrap rounded-lg w-fit bg-nomad-300 animate__animated animate__fadeInDown animate__delay-2s"
            >
                <p
                    class="pr-20 pl-20 font-serif text-2xl font-bold text-left text-chicago-950 w-fit"
                >
                    Full-Stack
                </p>
            </div>
            <div
                class="flex justify-start items-center whitespace-nowrap rounded-lg w-fit bg-nomad-500 animate__animated animate__fadeIn animate__delay-1s"
            >
                <h1
                    class="pr-20 pl-20 font-serif text-4xl font-bold text-left text-chicago-950 w-fit"
                >
                    Jacob Brown
                </h1>
            </div>
            <div
                class="flex justify-start items-center whitespace-nowrap rounded-lg w-fit bg-nomad-300 animate__animated animate__fadeInUp animate__delay-2s"
            >
                <h2
                    class="pr-20 pl-20 font-serif text-2xl font-bold text-center text-chicago-950"
                >
                    Web Developer
                </h2>
            </div>
        </div>
        <div class="m-3">
            <img
                class="rounded-full max-h-[45vh] md:max-h-[85vh] animate__fadeIn animate__animated animate__delay-2s"
                src="/public/images/IMG_9288.jpg"
                loading="eager"
                fetchpriority="high"
                decoding="async"
            />
        </div>
    </div>
</template>

<style scoped></style>
