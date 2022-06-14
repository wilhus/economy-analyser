<template>
    <header class="d-header">
        <div class="h-full flex items-center mx-auto max-w-7xl px-6">
            <div class="flex items-center flex-1 justify-start">
                <img loading="lazy pointer-events-none cursor-pointer" src="../assets/images/logo.png" alt="A logo"
                    width="256px" />
            </div>
            <nav class="flex items-center justify-center h-full">
                <div class="relative inline-block text-left cursor-default">
                    <div class="flex items-center w-full mx-2">
                        <span aria-label="Item 1"
                            class="flex font-regular group whitespace-nowrap px-1 py-2 text-white hover:text-indigo-300">
                            Item 1
                        </span>
                        <b-icon icon="chevron-down" class="text-white" />
                    </div>
                </div>
                <div class="relative inline-block text-left cursor-default">
                    <div class="flex items-center w-full mx-2">
                        <span aria-label="Item 2"
                            class="flex font-regular group whitespace-nowrap px-1 py-2 text-white hover:text-indigo-300">
                            Item 2
                        </span>
                        <b-icon icon="chevron-down" class="text-white" />
                    </div>
                </div>
                <div class="relative inline-block text-left cursor-default">
                    <div class="flex items-center w-full mx-2">
                        <span aria-label="Item 3"
                            class="flex font-regular group whitespace-nowrap px-1 py-2 text-white hover:text-indigo-300">
                            Item 3
                        </span>
                        <b-icon icon="chevron-down" class="text-white" />
                    </div>
                </div>
            </nav>
            <div class="flex items-center flex-1 justify-end gap-1 h-full">
                <v-btn icon>
                    <b-icon icon="gear-fill" class="text-gray-200 w-5 h-5 hover:text-indigo-300" />
                </v-btn>
                <v-btn icon>
                    <b-icon icon="person-circle" class="text-gray-200 w-5 h-5 hover:text-indigo-300" />
                </v-btn>
            </div>
        </div>
    </header>
</template>
<style>
.d-header {
    border-style: none;
    background-color: rgba(0, 30, 38, var(--tw-bg-opacity));
    height: var(--header-height);
    position: sticky;
    backdrop-filter: blur(12px);
    top: 0;
    width: 100%;
    z-index: 50;
    --tw-bg-opacity: 0.8;
    --header-height: 4.5rem;
}
</style>
<script lang="jsx">
export default {
}
</script>