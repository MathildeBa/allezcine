<template>
    <button> {{ text }} </button>
</template>

<script>
export default {
    name:'Btn',
    props: ['text'],  
}
</script>

<style>
button {
    background-color: red;
    border: 1px hidden red;
    border-radius: 5px;;
    color: white;
    padding: 0px 55px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
</style>

