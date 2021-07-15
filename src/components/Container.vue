<template>
<div class="container">
<div class="block">
<div>
<div>Small</div>
<div>Medium</div>
<div>Large</div>
</div>
</div>
<hr/>
<div class="block">
<div>Adults</div>
</div>
<hr/>
<div class="block">
<div>Children</div>
</div>
</div>
</template>
<script>
export default {
  name : "Container",
  data(){
    return{
small:0,
medium:0,
large:0,
adults:0,
children:0
    }
  }
}
</script>

<style>
.container{
  border : 1px solid blue;
  border-radius:2px;
  display:flex;
  flex-direction:column;
}
hr{
  width:90%
}
.block{
  display:flex;
}
</style>