<template>
    <footer>
        <p>{{ footerText }} </p>
    </footer>
</template>



<script>
    export default {
        data() {
            return {
                footerText: 'Copyright 2020'
            }
        }
    }
</script>



<style scoped>
    footer {
        background-color: lightgrey;
        padding: 10px;
        text-align: center;
    }
</style>