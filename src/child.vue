<template>
  <div>
    <h1>Hello!! I am the child....</h1>
    <h2>my name is {{childname}} i am {{age}} years old. i live in {{country}}.</h2>
  </div>
</template>

<script>
export default {
  props :{
      childname : String,       //having single type
      age : [String,Number],    //having multiple types
      country :{
        type : String,
        required : true,
        default : "India"
      }
  }
}
</script>

<style scoped>
    h1{
        color: blue;
    }
    div{
        background-color: burlywood;
    }
</style>>

