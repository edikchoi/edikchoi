<template>
    <div>
        <TheHeader />
        <main class="main">
            <div class="main-wrap">
                <router-view />
            </div>
            <TheFooter />
        </main>
    </div>
</template>

<script>
import TheFooter from "@/components/TheFooter.vue"
import TheHeader from "@/components/TheHeader.vue"

export default {
    name: 'BaseLayout',
    components: { TheHeader, TheFooter }
}
</script>

<style lang="scss" scoped>
.main {
    width: 100%;
    .main-wrap {
        margin: 60px auto;
        width: 1200px;
        padding: 0 15px;
    }
}
</style>