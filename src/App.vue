 <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Alkatra&display=swap" rel="stylesheet">
 
 
 <template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
<!--   <Counter :start="101" /> -->
<Indecision />
 </template>

<script>

import Indecision from './components/Indecision.vue'




export default {
  name: 'App',
  components:{
    Indecision,
    
  }
}
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  
  
}

</style>
