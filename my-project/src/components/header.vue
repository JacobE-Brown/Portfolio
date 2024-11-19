<script>
export default {
    name: "Header",
    // component logic goes here
};
</script>

<template>
    <div class="p-6 bg-blue-200 h-[93vh]">
        <!-- Flex container that will stack on small screens and switch to side-by-side on medium screens -->
        <div class="flex flex-col md:flex-row">
            <!-- Text Block: On small screens, takes full width, on md takes 1/3 of the space -->
            <div class="w-full md:w-1/3 p-4">
                <h1 class="text-3xl">My name is Jacob Brown</h1>
                <p class="text-lg">And I am a full stack Web Developer</p>
            </div>

            <!-- Image Block: On small screens, takes full width, on md takes 2/3 of the space -->
            <div class="w-full md:w-2/3 p-4">
                <img
                    src="https://picsum.photos/500"
                    alt="Image"
                    class="w-full h-auto object-cover rounded-lg"
                />
            </div>
        </div>
    </div>
</template>

<style scoped>
/* Media Queries for Small Screens */
@media (max-width: 600px) {
}
</style>
