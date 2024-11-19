<script>
export default {
    name: "Menu",
    // component logic goes here
};
</script>

<template>
    <nav class=" sticky top-0 flex justify-between h-[7vh] bg-slate-700">
        <div class="inline h-full">
            <img src="https://picsum.photos/100" class="h-full rounded-full" />
        </div>
        <div class="inline ">
            <ul class="inline-flex h-full">
                <li
                    class=" flex items-center p-1 cursor-pointer h-full border-black border rounded-md bg-slate-200 hover:bg-stone-500"
                >
                    About Me
                </li>
                <li
                    class=" flex items-center p-1 cursor-pointer border-black border rounded-md bg-slate-200 hover:bg-stone-500"
                >
                    My Projects
                </li>
                <li
                    class=" flex items-center p-1 cursor-pointer border-black border rounded-md bg-slate-200 hover:bg-stone-500"
                >
                    Contact
                </li>
            </ul>
        </div>
    </nav>
</template>
