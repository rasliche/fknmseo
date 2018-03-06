<template lang="html">
    <div class="container mx-auto">
        <nuxt />
    </div>
</template>

<script>
export default {
}
</script>

<style lang="css">
.training-module {
    display: grid;
    grid-gap: 20px;
    grid-template-columns: 100px auto 100px;
}

.training-module>* {
    grid-column: 2 / span 1;
}
</style>
