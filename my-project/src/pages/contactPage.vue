<script>
    import ContentBlock from "../components/contentBlock.vue";
    import CustomFooter from "../components/footer.vue";

    export default {
        name: "projects",
        components: {
            CustomFooter,
            ContentBlock,
        },
    };
</script>
<template>
    <ContentBlock class="p-8">
        <template
            #contentHeader
            class="mt-0"
        >
            Contact Me
        </template>
        <template #content>
            <div class="flex justify-center items-center w-full h-full">
                <div class="w-3/5 h-auto transition duration-500 ease-in-out bg-sandstone-300">
                    <form
                        name="Contact Me Form"
                        action="mailto:---?subject=Personal%20Portfolio%20Mail"
                        enctype="text/plain"
                        method="POST"
                        class="p-6 w-full rounded-lg border-2 border-roman-coffee-800"
                    >
                        <fieldset class="p-0">
                            <div>
                                <label
                                    for="SubmitName"
                                    class="block text-lg font-semibold text-gray-700"
                                    >Full Name:</label
                                >
                                <input
                                    type="text"
                                    name="SubmitName"
                                    id="SubmitName"
                                    class="p-2 mt-1 w-full rounded-md border border-gray-300 transition duration-300 ease-in-out focus:ring-blue-400 focus:scale-105"
                                    pattern="[a-zA-Z][a-zA-Z0-9-_]{4,24}"
                                    required
                                />
                            </div>

                            <div>
                                <label
                                    for="Email"
                                    class="block text-lg font-semibold text-gray-700"
                                    >Email:</label
                                >
                                <input
                                    type="email"
                                    name="Email"
                                    id="Email"
                                    pattern="(\w\.?)+@[\w\.-]+\.\w{2,}}"
                                    class="p-2 mt-1 w-full rounded-md border border-gray-300 transition duration-300 ease-in-out focus:ring-blue-400 focus:scale-105"
                                    required
                                />
                            </div>
                        </fieldset>

                        <div>
                            <label
                                for="Message"
                                class="block text-lg font-semibold text-gray-700"
                                >Please write your message:</label
                            >
                            <textarea
                                id="Message"
                                name="message"
                                class="w-full rounded-md border transition duration-300 ease-in-out focus:ring-blue-400 focus:scale-105"
                                rows="4"
                                placeholder="Please type your message here"
                                required
                            ></textarea>
                        </div>

                        <div class="flex justify-end mt-4">
                            <input
                                type="submit"
                                name="submit"
                                value="Submit"
                                class="px-6 py-2 pt-2 font-semibold text-white rounded-md transition ease-in-out cursor-pointer bg-Ebony-600 hover:bg-Ebony-700 focus:scale-105 hover:scale-105"
                            />
                        </div>
                    </form>
                </div>
            </div>
        </template>
    </ContentBlock>
</template>
