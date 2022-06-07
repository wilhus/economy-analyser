<template>
    <div class="relative w-full">
        <header class="d-header">
            <div class="h-full flex items-center mx-auto max-w-7xl px-6">
                <div class="flex items-center flex-1 justify-start">
                    <!-- <p class="font-sant font-light text-white">Economy Analyser</p> -->
                    <img loading="lazy" src="../assets/images/logo.png" alt="A logo" width="256px" />
                </div>
                <nav class="flex items-center justify-center h-full">
                    <div class="relative inline-block text-left cursor-default">
                        <div class="flex items-center w-full mx-2">
                            <span aria-label="Item 1"
                                class="flex font-regular group whitespace-nowrap px-1 py-2 text-white hover:text-indigo-300">
                                Item 1
                            </span>
                            <svg fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                viewBox="0 0 24 24" stroke="currentColor" class="h-4 w-4 text-gray-300">
                                <g transform="rotate(90 12 12)">
                                    <path d="M9 5l7 7-7 7" />
                                </g>
                            </svg>
                        </div>
                    </div>
                    <div class="relative inline-block text-left cursor-default">
                        <div class="flex items-center w-full mx-2">
                            <span aria-label="Item 2"
                                class="flex font-regular group whitespace-nowrap px-1 py-2 text-white hover:text-indigo-300">
                                Item 2
                            </span>
                            <svg fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                viewBox="0 0 24 24" stroke="currentColor" class="h-4 w-4 text-gray-300">
                                <g transform="rotate(90 12 12)">
                                    <path d="M9 5l7 7-7 7" />
                                </g>
                            </svg>
                        </div>
                    </div>
                    <div class="relative inline-block text-left cursor-default">
                        <div class="flex items-center w-full mx-2">
                            <span aria-label="Item 3"
                                class="flex font-regular group whitespace-nowrap px-1 py-2 text-white hover:text-indigo-300">
                                Item 3
                            </span>
                            <svg fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                viewBox="0 0 24 24" stroke="currentColor" class="h-4 w-4 text-gray-300">
                                <g transform="rotate(90 12 12)">
                                    <path d="M9 5l7 7-7 7" />
                                </g>
                            </svg>
                        </div>
                    </div>
                </nav>
                <div class="flex items-center flex-1 justify-end gap-1">
                    <svg class="svg-icon" viewBox="0 0 20 20">
                        <polygon fill="none"
                            points="18.198,7.95 3.168,7.95 3.168,8.634 9.317,9.727 9.317,19.564 12.05,19.564 12.05,9.727 18.198,8.634 ">
                        </polygon>
                        <path fill="none"
                            d="M2.485,10.057v-3.41H2.473l0.012-4.845h1.366c0.378,0,0.683-0.306,0.683-0.683c0-0.378-0.306-0.683-0.683-0.683H1.119c-0.378,0-0.683,0.306-0.683,0.683c0,0.378,0.306,0.683,0.683,0.683h0.683v4.845C1.406,6.788,1.119,7.163,1.119,7.609v2.733c0,0.566,0.459,1.025,1.025,1.025c0.053,0,0.105-0.008,0.157-0.016l-0.499,5.481l5.9,2.733h0.931C8.634,13.266,5.234,10.458,2.485,10.057z">
                        </path>
                        <path fill="none"
                            d="M18.169,6.584c-0.303-3.896-3.202-6.149-7.486-6.149c-4.282,0-7.183,2.252-7.484,6.149H18.169z M15.463,3.187c0.024,0.351-0.103,0.709-0.394,0.977c-0.535,0.495-1.405,0.495-1.94,0c-0.29-0.268-0.418-0.626-0.394-0.977C13.513,3.827,14.683,3.827,15.463,3.187z">
                        </path>
                        <path fill="none"
                            d="M18.887,10.056c-2.749,0.398-6.154,3.206-6.154,9.508h0.933l5.899-2.733L18.887,10.056z">
                        </path>
                    </svg>
                </div>
            </div>
        </header>
        <!-- <div class="fixed bottom-0 right-0 flex flex-col justify-end w-full z-50"></div> -->
        <div class="flex">
            <div class="flex-auto w-full min-w-0 static max-h-full overflow-visible">
                <div class="relative pt-24 pb-32 bg-secondary-darkest">
                    <img class="w-full absolute -bottom-1px left-0 object-fill pointer-events-none z-0" loading="lazy"
                        alt="A chart background" src="../assets/images/bg-2.svg" />
                </div>
            </div>
        </div>
        <footer class="relative z-10 mt-64">
            <div class="text-gray-100 flex gap-2 h-full items-center justify-center">
                <p>Made by wilhus</p>
                <a href="https://github.com/wilhus" rel="noopener nofollow noreferrer" target="_blank"
                    aria-label="Visit my GitHub!" title="Visit my GitHub!" class="block">
                    <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg"
                        class="w-6 h-6 text-gray-400 hover:text-white">
                        <path fill-rule="evenodd" clip-rule="evenodd"
                            d="M7.02751 0.333496C3.34571 0.333496 0.333332 3.40836 0.333332 7.16653C0.333332 10.1845 2.23002 12.7468 4.90769 13.6579C5.2424 13.7149 5.35397 13.4871 5.35397 13.3163C5.35397 13.1454 5.35397 12.7468 5.35397 12.1774C3.51307 12.576 3.12257 11.2664 3.12257 11.2664C2.84365 10.4692 2.39737 10.2414 2.39737 10.2414C1.72795 9.8428 2.39737 9.8428 2.39737 9.8428C3.06679 9.89974 3.4015 10.5261 3.4015 10.5261C4.01513 11.5511 4.96347 11.2664 5.35397 11.0955C5.40975 10.64 5.57711 10.3553 5.80024 10.1845C4.29405 10.0136 2.73208 9.44421 2.73208 6.82488C2.73208 6.08463 3.011 5.45827 3.4015 5.00274C3.4015 4.77497 3.12257 4.09166 3.51307 3.18059C3.51307 3.18059 4.07091 3.00977 5.35397 3.8639C5.91181 3.69307 6.46966 3.63613 7.02751 3.63613C7.58536 3.63613 8.14321 3.69307 8.70105 3.8639C9.98411 2.95283 10.542 3.18059 10.542 3.18059C10.9324 4.14861 10.6535 4.83191 10.5977 5.00274C11.044 5.45827 11.2672 6.08463 11.2672 6.82488C11.2672 9.44421 9.70518 10.0136 8.19899 10.1845C8.42213 10.4122 8.64527 10.8108 8.64527 11.4372C8.64527 12.3482 8.64527 13.0885 8.64527 13.3163C8.64527 13.4871 8.75684 13.7149 9.09155 13.6579C11.7692 12.7468 13.6659 10.1845 13.6659 7.16653C13.7217 3.40836 10.7093 0.333496 7.02751 0.333496Z"
                            fill="currentColor"></path>
                    </svg>
                </a>
            </div>
        </footer>
    </div>
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

.bg-secondary-darkest {
    --tw-bg-opacity: 1;
    background-color: rgba(1, 42, 53, var(--tw-bg-opacity));
}
</style>
<script lang="jsx">
export default {

}
</script>