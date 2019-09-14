<template>
    <v-container fluid>
    <v-layout>
        <div>
            <home-plans></home-plans>
            <meal-recipes></meal-recipes>
        </div>
    </v-layout>
    </v-container>
</template>

<script>
    import HomePlans from '@/components/HomePlans';
    import MealRecipes from '@/components/MealRecipes';
    export default {
        name: "Menu",
        components: {
            HomePlans,
            MealRecipes
        }
    }
</script>

<style scoped>

</style>