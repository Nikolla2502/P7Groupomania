<template>
    <div>
        <h1>{{ txt }}</h1>
        <connexion></connexion>
    </div>
</template>


<script>
import connexion from './connexion.vue'
export default {
    name: 'Contenu',
    data(){                  //  equivalent à data: function()
        return {
            txt : 'Bienvenue sur votre reseau d\'entreprise'
        }
    },
    components: {
        'connexion': connexion
    }
}

</script>


<style scoped>

</style>