<template>
  <div class="child">
    <h1>users</h1>
    
    <!-- <h1>{{data}}</h1>
    <h1>{{msg}}</h1> -->
  </div>
</template>
<script>
export default {
  name: "MyUsers",
  props: {
    data: String,
    msg: String,
  },
};
</script>
<style scoped>
.child {
  background-color: rgb(50, 184, 205);
  height: 150px;
  width: 200px;
}
</style>
