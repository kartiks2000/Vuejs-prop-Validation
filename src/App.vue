<template>
  <div class="kk">
    <h1>Hello!! I am the parent....</h1>
    <Child childname="kartik" age="19" country="USA"></Child>
  </div>
</template>

<script>
import child from './child';
export default {
  components:{
    Child : child
  },
}
</script>

<style scoped>
  h1{
    color: red;
  }
  div{
    margin: 3rem;
  }
  .kk{
    background-color: cornsilk;
    padding: 3rem;
  }
</style>>

</style>
