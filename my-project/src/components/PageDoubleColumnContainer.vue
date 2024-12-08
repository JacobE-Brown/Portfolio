<script>
    import ContentBlock from "./contentBlock.vue";

    export default {
        name: "container",
        components: {
            ContentBlock,
        },
    };
</script>

<template>
    <div
        class="h-[93vh] w-full overflow-y-auto mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-5 p-1 md:p-6 lg:p-8">
        <ContentBlock class="order-2 md:order-3">
            <template #contentHeader>
                <slot name="header1">Content Header</slot>
            </template>
            <template #content>
                <slot name="content1"></slot>
            </template>
        </ContentBlock>

        <ContentBlock class="order-4 lg:col-span-2">
            <template #contentHeader>
                <slot name="header2">Content Header</slot>
            </template>
            <template #content>
                <slot name="content2"
                    ><p>
                        Sed autem repellendus libero. In sit ab dicta
                        exercitationem voluptates. Placeat sed quisquam sapiente
                        non sed consequuntur.
                    </p>
                    <p>
                        Consequatur odit reiciendis architecto. Fuga et mollitia
                        est aut hic praesentium vel facere deserunt. Hic et aut
                        consequuntur maiores omnis. Repudiandae aut quidem rerum
                        quibusdam neque. Asperiores autem commodi modi optio.
                        Velit voluptates veniam est quia.
                    </p></slot
                >
            </template>
        </ContentBlock>
    </div>
</template>
