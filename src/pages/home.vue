<template>
    <div>
        <nav-header/>
        <router-view/>
        <nav-footer/>
    </div>
</template>

<script>
import NavHeader from '../components/NavHeader.vue';
export default {
  components: { NavHeader },
    data() {
        return {

        };
    },
    created() {

    },
    mounted() {

    },
    methods: {

    }
}
</script>

<style scoped lang="less">

</style>
