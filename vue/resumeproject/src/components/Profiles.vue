<template>
<form>
    <h3>{{titleone}}</h3>
  <input type="text" placeholder="Address"> <input type='text' placeholder='Postal Code'>
  <br><br>
  <input type='text' placeholder='City'> <input type='text' placeholder='Country code'>

  <br><br>
  <input type='text' placeholder='Label'> <input type='text' placeholder='URL'>
  <br><br>
  <input type='text' placeholder='Region' maxlength='25'>
 </form>
</template>
<!--JS--->
<script>
export default {
    name:'Profiles',
    props:{
    titleone:String
  }

}
</script>
