<template>
    <div class="relative w-full">
        <NavBar />
        <!-- <div class="fixed bottom-0 right-0 flex flex-col justify-end w-full z-50"></div> -->
        <div class="flex">
            <div class="flex-auto w-full min-w-0 static max-h-full overflow-visible">
                <div class="flex justify-center relative pt-8 pb-4 bg-secondary-darkest">
                    <!-- <section class="flex flex-col justify-start w-full px-4 pt-36 pb-56 text-center z-20">
                        <h1 class="font-normal font-serif text-display-4 mb-6 text-white">
                            Analyse your private <br>Economy
                        </h1>
                    </section>
                    <img class="w-full absolute bottom-0 left-0 object-fill pointer-events-none z-0" loading="lazy"
                        alt="A chart background" src="../assets/images/bg-2.svg" /> -->
                    <img class="opacity-30 absolute top-20 object-fill pointer-events-none z-0"
                        loading="lazy" alt="A chart background" src="../assets/images/bg-polygon.svg" />
                    <div class="overflow-hidden relative text-white mt-4 pt-18">
                        <div class="flex flex-wrap justify-center py-0 section">

                            <section class="flex flex-col justify-center w-full px-4 pt-36 pb-56 text-center z-20">
                                <p class="font-normal font-serif text-6xl mb-6">
                                    Let's Analyse Your <br>
                                    <strong class="text-indigo-300">
                                        Economy
                                    </strong>
                                </p>
                                <p class="font-normal text-xl mb-8 px-8 text-gray-200">
                                    Learn more about your income and expenditure. <br> 
                                    Set goals and follow your progress!
                                </p>
                               
                                    <v-btn depressed large >Get Started</v-btn>
                                
                                
                            </section>
                            
                        </div>
                    </div>
                     <img class="absolute bottom-0 left-0 w-full mb-0 object-fill pointer-events-none z-0" loading="lazy"
                                alt="A chart background" src="../assets/images/bg-2.svg" />

                </div>
               
            </div>
        </div>
        <footer class="relative z-10 mt-32" >
            <div class="text-gray-100 flex gap-2 h-full items-center justify-center mb-8">
                <p>Website created by wilhus</p>
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