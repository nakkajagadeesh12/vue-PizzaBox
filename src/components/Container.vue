<template>
<div class="container">
<div>
Block 1
</div>
<hr/>
<div>
Block 2
</div>
<hr/>
<div>
Block 3
</div>
</div>
</template>
<script>
export default {
  name : "Container",
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
</style>