<template>
    <span>
        <home-hero></home-hero>
        <home-details></home-details>
        <home-plans></home-plans>
    </span>
</template>

<script>
    import HomeHero from "../components/HomeHero";
    import HomeDetails from "../components/HomeDetails";
    import HomePlans from "../components/HomePlans";
    export default {
        name: "Home",
        components: {HomePlans, HomeDetails, HomeHero}
    }
</script>

<style scoped>

</style>