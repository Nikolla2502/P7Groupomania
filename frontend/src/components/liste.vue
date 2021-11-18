<template>
<ul class="liste">
    <li v-for="(fruit, index) in fruits" v-bind:key="index">{{ fruit }}</li>
</ul>
    
</template>


<script>
export default {
    name: 'Liste',
    data(){
        return {
            fruits: ['Orange', 'Papaye', 'Fraise']
        }
    }
}
</script>


<style scoped>
li {
    list-style: none;
}
</style>