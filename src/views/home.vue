<template>
    <div class="home">
        <cube></cube>
    </div>
</template>
<script>
import cube from '@/components/cube/index'
export default {
    components: {
        cube
    },
    data: function () {
        return {
            msg: 'home'
        }
    }
}
</script>
<style lang="stylus" scoped></style>
