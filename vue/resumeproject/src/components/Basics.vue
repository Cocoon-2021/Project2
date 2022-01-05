<template>
<form>
  <h3>{{title}}</h3>
  <input type="text" placeholder="Address"> <input type='text' placeholder='Postal Code'>
  <br><br>
  <input type='text' placeholder='Image URL'> <input type='email' placeholder='Email'>
  <br><br>
  <input type='text' placeholder='Label'> <input type='text' placeholder='URL'>
  <br><br>
  <input type='text' placeholder='Summary' maxlength='25'>
 
</form>
</template>

<!--JS--->
<script>
export default{
  name:'Basics',
  props:{
    title:String
  }
}
</script>  
