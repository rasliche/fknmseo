<template lang="html">
    <div>
        <h1>This is the Admin page</h1>
        <nuxt-link
            class="bg-grey-light rounded mx-4 px-2"
            active-class="bg-blue"
            to="/admin/new-org">
            Add a new Organization
        </nuxt-link>
        <nuxt-link
            class="bg-grey-light rounded mx-4 px-2"
            active-class="bg-blue"
            to="/admin/organizations">
            All Organizations
        </nuxt-link>
        <nuxt-link
            class="bg-grey-light rounded mx-4 px-2"
            active-class="bg-blue"
            to="/admin/users">
            All Users
        </nuxt-link>

        <nuxt-child />
    </div>
</template>

<script>
export default {
}
</script>

<style lang="css">
</style>
