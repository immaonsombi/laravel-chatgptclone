<script setup>

</script>
<template >
    <aside class="ml-[-100%] fixed z-10 top-0 pb-3 px-4 w-full flex flex-col justify-between h-screen bo">
        <div>
            <slot name="aside" />

        </div>
    </aside>
    <div class="ml-auto mb-6 lg:w[75%]">

        <div class="pt-6">
            <main>
                <slot />
            </main>
        </div>
    </div>
</template>