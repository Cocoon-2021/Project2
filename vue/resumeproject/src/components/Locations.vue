<template>
<form>
    <h3>{{titletwo}}</h3>
  <input type="text" placeholder="Network"> <input type='text' placeholder='Username'>
  <br><br>
  <input type='text' placeholder='URL'> 
 </form>
</template>
<!--JS--->

<script>
export default{
    name:'Locations',
    props:{

    titletwo:String
  }
    }
</script>