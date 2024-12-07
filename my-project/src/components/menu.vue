<script>
    export default {
        name: "Menu",
        // component logic goes here
        data() {
            return {
                currentSection: "Home",
            };
        },
    };
</script>

<template>
    <div class="h-[7vh] bg-slate-700 z-30">
        <nav class="mx-auto flex justify-between h-[7vh]">
            <div class="inline-flex items-center h-full">
                <img
                    src="https://picsum.photos/100"
                    class="h-full rounded-full"
                />
                <h2 class="hidden md:block">{{ currentSection }}</h2>
            </div>
            <div class="inline">
                <ul class="inline-flex gap-1 items-center h-full text-center">
                    <li class="flex justify-center items-center h-full">
                        <a
                            href="#Home"
                            class="flex items-center p-1 h-2/3 rounded-md border border-black cursor-pointer items-cente h bg-slate-200 hover:bg-stone-500"
                            >Home</a
                        >
                    </li>

                    <li class="flex justify-center items-center h-full">
                        <a
                            href="#AboutMe"
                            class="flex items-center p-1 h-2/3 rounded-md border border-black cursor-pointer items-cente h bg-slate-200 hover:bg-stone-500"
                            >About Me</a
                        >
                    </li>

                    <li class="flex justify-center items-center h-full">
                        <a
                            href="#MyProjects"
                            class="flex items-center p-1 h-2/3 rounded-md border border-black cursor-pointer items-cente h bg-slate-200 hover:bg-stone-500"
                            >My Projects</a
                        >
                    </li>
                    <li class="flex justify-center items-center h-full">
                        <a
                            href="#ContactMe"
                            class="flex items-center p-1 h-2/3 rounded-md border border-black cursor-pointer items-cente h bg-slate-200 hover:bg-stone-500"
                            >Contact Me</a
                        >
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</template>
