<template lang="html">
    <div class="container mx-auto">
        <app-header></app-header>
        <nuxt />
    </div>
</template>

<script type="text/javascript">
import Header from '@/components/Header'

export default {
    components: {
        AppHeader: Header
    }
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
