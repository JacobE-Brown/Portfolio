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
                    class="h-full rounded-full" />
                <h2 class="hidden md:block">{{ currentSection }}</h2>
            </div>
            <div class="inline">
                <ul class="inline-flex gap-1 items-center h-full text-center">
                    <li
                        class="flex items-center p-1 h-2/3 rounded-md border border-black cursor-pointer bg-slate-200 hover:bg-stone-500">
                        About Me
                    </li>
                    <li
                        class="flex items-center p-1 h-2/3 rounded-md border border-black cursor-pointer bg-slate-200 hover:bg-stone-500">
                        My Projects
                    </li>
                    <li
                        class="flex items-center p-1 h-2/3 rounded-md border border-black cursor-pointer bg-slate-200 hover:bg-stone-500">
                        Contact
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</template>
