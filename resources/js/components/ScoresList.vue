<template>
    <div>
        <p class="text-xl text-center mb-2">League Name:</p>
        <Score></Score>
    </div>
</template>

<script>
    import Score from "./Score.vue";

    export default {
        components: {Score},
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
