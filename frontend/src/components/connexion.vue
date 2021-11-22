<template>
<ul class="connexion">
    <li >{{ name }}</li>
    <li >{{ password }}</li>
</ul>
    
</template>


<script>
export default {
    name: 'connexion',
    data(){
        return {
            name : "name",
            password: "Password"
        }
    }
}
</script>


<style scoped>
li {
    list-style: none;
}
</style>