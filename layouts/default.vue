<template lang="html">
    <div class="container mx-auto app">
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
.app {
    display: grid;
    grid-gap: 10px;
    grid-template-columns: 2fr 7fr 3fr;
}

.navigation {
    align-content: start;
}

.training-module {
    grid-column: 2;
    /* display: grid;
    grid-gap: 20px;
    grid-template-columns: 100px auto 100px; */
}
</style>
