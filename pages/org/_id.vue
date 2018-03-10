<template lang="html">
    <div>
        <h1>Organization Page</h1>
        <p>Organization ID: {{ orgId }}</p>
    </div>
</template>

<script>
export default {
    asyncData({ params }) {
        return {
            orgId: params.id
        }
    }
}
</script>

<style lang="css">
</style>
