<!-- global-bottom.vue -->
<template>
    <img src="/images/bar-01.png" class="absolute top-0 left-0" />
    <img src="/images/logo.png" class="io-logo absolute top-5 left-5 w-15" v-bind:data-index="$slidev.nav.currentPage" />
    <div class="absolute bottom-2 left-10 ">
        <SlideCurrentNo class="text-xs" />
        <span class="text-xs pl-10">Optimizing useEffect for Performance?</span>
    </div>
</template>