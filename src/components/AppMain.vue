<script>

// importato axios per chiamata api
import axios from 'axios';

export default{
  data(){
    return{

    };
  },

  components:{

  },

  // per far partire la chiamata la devo richiamare
  mounted(){
    this.getProjects();
  },

  methods:{

    // chiamata api
    getProjects(){
      axios
        .get('http://127.0.0.1:8000/api/projects')
        .then((res)=>{
          console.log(res.data);
        });
    }
    
  },
}

</script>

<template>
  <main>
    Main
  </main>
</template>

<style scoped>
</style>
