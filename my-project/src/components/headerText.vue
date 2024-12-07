<script>
export default {
    name: "HeaderText",
};
</script>

<template>
    <div
        class="flex justify-center items-center w-full rounded-lg border-4 bg-nomad-600 border-Ebony-900"
    >
        <h3 class="flex items-center font-serif text-2xl font-bold min-h-12">
            <slot>Placeholder Heading</slot>
        </h3>
    </div>
</template>
