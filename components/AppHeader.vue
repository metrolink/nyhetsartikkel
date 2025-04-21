<template>
    <div class="tabs">
        <div>Main page</div>
        <div>Off page</div>
        <div>Header</div>
        <div>yes</div>
    </div>

</template>

<style>
.tabs {
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