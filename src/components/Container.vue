<template>
<div class="container">
<div class="sub-container">
<div class="block">
<div><i class="fas fa-pizza-slice"></i></div>
<div>Small</div>
<div>-</div>
<div>{{adults}}</div>
<div>+</div>
</div>
<div class="block">
<div><i class="fas fa-pizza-slice"></i></div>
<div>Medium</div>
<div>-</div>
<div>{{adults}}</div>
<div>+</div></div>
<div class="block">
<div><i class="fas fa-pizza-slice"></i></div>
<div>Large</div>
<div>-</div>
<div>{{adults}}</div>
<div>+</div></div>
</div>
<hr/>
<div class="block">
<div>Icon</div>
<div>Adults</div>
<div>-</div>
<div>{{adults}}</div>
<div>+</div>
</div>
<hr/>
<div class="block">
<div>Icon</div>
<div>Children</div>
<div>-</div>
<div>{{adults}}</div>
<div>+</div>
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
.block div{
  width:20%;
}
</style>