<template>
    <div>
        <ul>
            <li v-for="(flower, index) in Flowers" :key="index" @click="Flowers.show =!Flowers.show">
            <p>{{ flower.name }}</p>
            <p> v-show="Flowers.show"{{ Flowers.color}}</p>

            </li>
        </ul>
    </div>
</template>


<script>
    export default {
        data() {
            return {
                Flowers: [
                    { name: 'Roses', color: 'red', show: false},
                    { name: 'Violets', color: 'blue', show: false},
                    ]
            }
        }
    }
</script>


<style scoped>
ul {
    display: flex;
    max-width: 1000px;
    margin: 20px;
    padding: 10px;
    box-sizing: border-box;
}
li {
    list-style: none;
    padding: 20px;
    margin: 10px;
    text-align: center;
    border: 2px purple;
    flex-flow: 1;
}
</style>
