<template>
    <header>
        <h3> {{ title }} </h3>
    </header>
</template>


<script>
    export default {
        data () {
            return {
                title: 'All about Flowers!'
            }
        }
    }
</script>


<style scoped>
    header {
        background-color: pink;
        padding: 10px;
        height: 50px;
        text-align: center;
    }
</style>