<script>
export default {
    name: "Header",
    // component logic goes here
};
</script>

<template>
    <div class="bg-blue-200 h-[93vh] overflow-y-auto">
        <div
            class="flex flex-col md:flex-row md:justify-center items-center h-auto md:h-full mt-5 md:mt-0 md:p-4 container mx-auto"
        >
            <!-- Name Tag -->
            <div
                id="Name-Tag"
                class="flex-1 md:w-1/3 justify-center flex md:justify-end"
            >
                <div
                    class="bg-white rounded-md overflow-hidden w-full md:max-w-80 h-fit md:max-w-"
                >
                    <h2 class="bg-red-700 w-full text-center p-3">
                        Hello! <br />
                        My name is
                    </h2>
                    <h1 class="text-center">Jacob Brown</h1>
                    <p class="bg-red-700 text-center p-2">
                        and I am a full stack web developer.
                    </p>
                </div>
            </div>
            <!-- Picture and Button -->
            <div
                id="Picture-Button"
                class="flex-1 md:w-2/3 p-4 md:h-full flex justify-center items-center flex-col md:items-start"
            >
                <!-- Picture -->
                <div class="mb-3 rounded-full">
                    <img
                        src="https://picsum.photos/500"
                        class="w-full max-w-72 md:w-full h-auto rounded-full object-cover mb-7"
                    />
                    <!-- Button -->
                    <div class="flex justify-center">
                        <button
                            class="text-center bg-red-700 border border-black rounded-md p-4 px-7 hover:bg-red-400"
                        >
                            About Me
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
/* Media Queries for Small Screens */
@media (max-width: 600px) {
}
</style>
