<template>
    <header class="global-header">
        <div class="header-wrap">
            <router-link to="/">
                <h1>Header</h1>
            </router-link>
            <GlobalNav />
        </div>
    </header>
</template>

<script>
import GlobalNav from '@/components/Nav/GlobalNav.vue'

export default {
    components: { GlobalNav }
}
</script>

<style lang="scss" scoped>
.global-header {
    width: 100%;
    border-bottom: 1px solid #eee;
    .header-wrap {
        display: flex;
        align-items: center;
        justify-content: space-between;
        width: 100%;
        height: 100px;
        padding: 0 15px;
        margin: 0 auto;
    }
}
</style>