<template lang="html">
    <div>
        <h1>This is the Admin page</h1>
        <nuxt-link to="/admin/new">Add a new Organization</nuxt-link>
        <nuxt-link to="/admin/organizations">All Organizations</nuxt-link>
        <nuxt-link to="/admin/users">All Users</nuxt-link>
        <nuxt-child />
    </div>
</template>

<script>
export default {
}
</script>

<style lang="css">
</style>
