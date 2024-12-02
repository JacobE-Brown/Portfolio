<script>
export default {
    name: "Header",
    // component logic goes here
};
</script>

<template>
    <header>
        <div class="bg-blue-200 h-[93vh] w-svw overflow-y-auto">
            <div
                class="  h-full flex flex-col items-center justify-evenly md:flex-row"
            >
                <div class="lg:flex-auto">
                    <img
                        src="https://picsum.photos/500"
                        alt="Jacob Brown"
                        class="w-full max-w-xs h-auto m-auto object-cover rounded-full"
                    />
                </div>

                <!-- Name Tag and button-->
                <div
                    class="flex flex-row items-center justify-evenly w-full md:flex-col md:w-auto md:h-2/3 lg:flex-auto"
                >
                    <div
                        class="flex-shrink w-fit bg-white rounded-md overflow-hidden"
                    >
                        <h2 class="bg-red-700 text-center p-3">
                            Hello! <br />
                            My name is
                        </h2>
                        <h1 class="text-center">Jacob Brown</h1>
                        <p class="bg-red-700 text-center p-2">
                            and I am a full stack web developer.
                        </p>
                    </div>
                    <div class="hover:hidden md:block">
                        <a
                            class="text-center bg-red-700 border border-black rounded-md p-4 hover:bg-red-400 transition-colors"
                        >
                            About Me
                        </a>
                    </div>
                </div>

                <!-- Button -->
            </div>
        </div>
    </header>
</template>

<style scoped></style>
