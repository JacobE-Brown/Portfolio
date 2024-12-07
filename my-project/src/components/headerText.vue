<script>
export default {
    name: "HeaderText",
};
</script>

<template>
    <div
        class="flex justify-center items-center w-full rounded-lg bg-nomad-600"
    >
        <h3 class="flex items-center font-serif text-2xl font-bold min-h-12">
            <slot>Placeholder Heading</slot>
        </h3>
    </div>
</template>
