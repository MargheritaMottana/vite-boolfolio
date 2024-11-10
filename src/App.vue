<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default{
  data(){

  },

  components:{
    AppHeader,
    AppMain,
    AppFooter,
  },

  methods:{

  },
}

</script>

<template>

  <div class="container py-5">
    
    <AppHeader />

    <AppMain />

    <AppFooter />

  </div>

</template>

<style scoped>
</style>
