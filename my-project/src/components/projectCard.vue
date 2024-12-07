<script>
    export default {
        name: "projectCard",
    };
</script>

<template>
    <div
        class="w-full transition duration-300 ease-in-out cursor-pointer hover:scale-105"
    >
        <div
            class="overflow-hidden rounded-3xl border-4 bg-Ebony-700 border-slate-500"
        >
            <div
                class="col-span-1 h-auto border-b-4 border-slate-500 lg:col-span-3"
            >
                <div class="object-cover w-full h-full">
                    <slot name="projectImg">
                        <img src="https://picsum.photos/500/300" class="object-cover w-full h-full" loading="lazy" />
                    </slot>
                </div>
            </div>
            <div
                class="flex object-cover flex-col col-span-2 gap-2 p-3 lg:col-span-3"
            >
                <h4
                    class="text-lg font-bold text-center rounded-md border-4 border-roman-coffee-500 bg-slate-700"
                >
                    <slot name="projectTitle">Tasty Fresh Mouse</slot>
                </h4>

                <slot name="content">
                    <p>
                        Et minima ipsa voluptatem esse vero beatae. Cupiditate
                        itaque earum dolores et. Voluptatem porro iusto
                        reprehenderit odio enim mollitia. Iure dolores ea.
                        Deserunt sit exercitationem ipsum rerum. Repellat
                        adipisci ullam mollitia sit velit laboriosam occaecati
                        ut.
                    </p>
                </slot>
            </div>
        </div>
    </div>
</template>
