<template>
    <div>
        <TheHeader />
        <main>
            <div>
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

</style>