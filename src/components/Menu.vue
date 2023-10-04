<script>
export default {

    name: 'Menu',
    props: {
        esSection: String,
        esUrlLink: String,
    },
    data() {
        return {

        }
    },
    components: {

    }

}
</script>

<template>
    <a id="menu" :href="esUrlLink">
        {{ esSection }}
    </a>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/Menu.scss' as *;
</style>
