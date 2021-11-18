<template>
    <div>
        <h1>{{ txt }}</h1>
        <liste></liste>
    </div>
</template>


<script>
import Liste from './liste.vue'
export default {
    name: 'Contenu',
    data(){                  //  equivalent à data: function()
        return {
            txt : 'Bienvenue sur votre reseau d\'entreprise'
        }
    },
    components: {
        'liste': Liste
    }
}

</script>


<style scoped>

</style>