<script>
export default {
    name: "Menu",
    // component logic goes here
};
</script>

<template>
    <nav class="pure-g h-[7vh] bg-orange-700 sticky top-0">
        <div class="hide-small pure-u-md-1-2 h-full">
            <img
                src="https://picsum.photos/100"
                class="h-full w-auto inline mr-4"
            />
        </div>
        <div class="pure-u-sm-1 pure-u-md-1-2">
            <ul class="inline-flex flex-row-reverse">
                <li>About Me</li>
                <li>Projects</li>
                <li>Contact</li>
            </ul>
        </div>
    </nav>
</template>
