<template>
    <div class="flex border-solid border-2 justify-evenly py-1">
        <div id="team-one" class="self-center">
            <span>Team One</span>
        </div>
        <div id="status" class="flex flex-col w-1/3">
            <div id="time" class="mx-auto">
                <span>HT</span>
            </div>
            <div id="scores" class="mx-auto">
                <span class="border-solid border-2 mr-1">0</span>
                <span class="border-solid border-2">0</span>
            </div>
        </div>
        <div id="team-two" class="self-center">
            <span>Team Two</span>
        </div>
    </div>
</template>

<script>
export default {
    name: "Score"
}
</script>

<style scoped>

</style>
