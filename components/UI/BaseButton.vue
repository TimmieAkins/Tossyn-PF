<template>
    <button>
        <slot>

        </slot>
    </button>
</template>

<style scoped>
button {
    width: 100%;
    height: 50px;
    margin: 10px 0;
    /* padding: 12px 0; */
    background-color: skyblue;
    color: black;
    border: none;
    border-radius: 10px;
    cursor: pointer;
}
</style>