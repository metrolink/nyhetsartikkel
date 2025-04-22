<template>
    <div class="tabs">
        <div>Hjem</div>
        <div>Karriere</div>
        <div>Prosjekter</div>
        <div>Ideer</div>
    </div>

</template>

<style>
.tabs {
    top:0;
    height: 600;
    position:sticky;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    background-color: lightskyblue;
}

.tabs > div:hover {
    background-color: lightcoral;
}

.tabs > div {
    width: 20%;
    height: 40;
    margin: 40;
    text-align: center;
}
</style>