<template lang="html">
    <div>
        <h3>admin/organizations</h3>
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
