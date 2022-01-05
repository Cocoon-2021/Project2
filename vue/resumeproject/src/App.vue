<template>
<div>
<Basics title="Basics"/>
<Profiles titleone="Profiles"/>
<Locations titletwo="Locations"/>
<Button/>
</div>
</template>
<script>
import Basics from './components/Basics.vue'
import Profiles from './components/Profiles.vue'
import Locations from './components/Locations.vue'
import Button from'./components/Button.vue'
export default{
  name:'App',
  components:{
    Basics,
    Profiles,
    Locations,
    Button,  
  },
}

</script>
<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}

</style>