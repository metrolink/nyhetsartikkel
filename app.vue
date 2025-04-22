<script lang="ts">
import { Analytics } from '@vercel/analytics/nuxt'
</script>
<template>
  <div class="mainPage">
    <Analytics/>
    <NuxtRouteAnnouncer />
    <AppHeader />
    <NuxtPage/>
    <!-- <NuxtWelcome />-->

  </div>
</template>

<style lang="css">
.mainPage {
    background-color: #A0CFD3;
}
</style>