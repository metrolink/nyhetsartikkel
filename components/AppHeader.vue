<script lang="ts">
</script>

<template>
    <div class="tabs">
        <NuxtLink to="/" class="routerLink">Hjem</NuxtLink>
        <NuxtLink to="https://karriere.adressa.no/stillinger/" class="routerLink">Karriere</NuxtLink>
        <NuxtLink to="https://t-rosag.no/" class="routerLink">Prosjekter</NuxtLink>
        <NuxtLink to="/ideas" class="routerLink">Ideer</NuxtLink>
    </div>

</template>

<style>
.tabs {
    top:0;
    height: 60px;
    position:sticky;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    background-color: #B4EDD2;
    z-index: 5;
}

.routerLink:hover {
    background-color: #8D94BA;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.routerLink {
    width: 20%;
    margin: 40px;
    text-align: center;
}
</style>