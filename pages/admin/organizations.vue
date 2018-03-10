<template lang="html">
    <div>
        <h1>admin/organizations</h1>
        <ul>
            <li v-for="org in 10">
                <nuxt-link
                    :to="{
                        name: 'org-id',
                        params: {id: org }
                        }">
                    Organization {{ org }}
                </nuxt-link>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
}
</script>

<style lang="css">
</style>
