<template>
    <div>
        <appintro></appintro>
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#edf057" fill-opacity="1" d="M0,256L1440,64L1440,0L0,0Z"></path></svg>
        <features id="features"></features>
    </div>
</template>

<script>
    import intro from "./components/intro";
    import screenshot from "./components/screenshot";
    export default {
        name: "apphome",
        components: {
            appintro: intro,
            features: screenshot,
        }
    }
</script>

<style scoped>

</style>