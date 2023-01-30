<template>
    <div class="nav">
        <router-link class="link" to="/home">Home</router-link>
        <router-link class="link" to="/page1">Page1</router-link>
        <router-link class="link" to="/page2">Page2</router-link>
        <router-link class="link" to="/page3">Page3</router-link>
    </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.nav {
    .link {
        & ~ .link {
            margin-left: 10px;
        }
    }
}
</style>