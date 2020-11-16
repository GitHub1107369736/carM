<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
  </div>
</template>

<script>
    export default {
        props: {

        },
        data() {
            return {

            };
        },
        methods: {

        },
        components: {

        },
        mounted(){
          // this.$router.push('/');
        }
    };
</script>

<style lang="less">
#app {
    height: 100%;
    
}


</style>
