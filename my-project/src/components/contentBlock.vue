<script>
    import HeaderText from "./headerText.vue";

    export default {
        name: "ContentBlock",
        components: {
            HeaderText,
        },
    };
</script>

<template>
    <article class="flex overflow-y-auto flex-col gap-2 h-full md:gap-5">
        <HeaderText>
            <slot name="contentHeader">Header Text</slot>
        </HeaderText>
        <div
            class="flex overflow-hidden flex-col items-center w-full h-full rounded-xl bg-sandstone-200">
            <div class="flex overflow-y-auto flex-col gap-5 w-full h-full">
                <slot name="content"
                    >Nostrum odio et repudiandae error accusamus unde est.
                    Recusandae quibusdam voluptas possimus ad ab. Quam maiores
                    ducimus voluptates.</slot
                >
            </div>
        </div>
    </article>
</template>
