<template lang="html">
    <div class="navigation">
        <nuxt-link
            class="text-center bg-grey-lighter rounded hover:bg-grey-light"
            to="/">
            Home
        </nuxt-link>
        <nuxt-link
            class="text-center bg-grey-lighter rounded hover:bg-grey-light"
            to="/training/about-blue-star">
            About Blue Star
        </nuxt-link>
        <nuxt-link
            class="text-center bg-grey-lighter rounded hover:bg-grey-light"
            to="/training/about-the-sanctuary">
            About The Sanctuary
        </nuxt-link>
        <nuxt-link
            class="text-center bg-grey-lighter rounded hover:bg-grey-light"
            to="/admin">
            Admin
        </nuxt-link>
    </div>
</template>

<script>
export default {
}
</script>

<style lang="css">
.navigation {
    display: grid;
    grid-gap: 20px;
}
</style>
