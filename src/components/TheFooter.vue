<template>
    <footer class="global-footer">
        <div class="footer-wrap">
            <h1>Footer</h1>
        </div>
    </footer>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.global-footer {
    width: 100%;
    border-top: 1px solid #eee;
    .footer-wrap {
        display: flex;
        align-items: center;
        justify-content: space-between;
        width: 1200px;
        height: 100px;
        padding: 0 15px;
        margin: 0 auto;
    }
}
</style>