
<template>
<div class="card shadow-2xl h-[130px] w-[130px] md:h-[160px] md:w-[160px] lg:h-[160px] lg:w-[160px] hover:-translate-y-4 duration-500 hover:bg-zinc-200">
    <slot></slot>
</div>







</template>
<style scoped lang="scss">
     .card {
     
        border-radius: .6rem;
        display: flex;
        justify-content:center;
        align-items: center;
     } 




</style>