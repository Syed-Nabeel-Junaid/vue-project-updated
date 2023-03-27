<template>
  <div class="home">
    <h1>loop</h1>
   
   

    <MyUsers />
    <MyProducts />
  </div>
</template>

<script>
import MyUsers from './Users.vue'

import MyProducts from './Products.vue'

export default {
  name: "HomeW",
  components: {
    MyUsers,
    MyProducts,
  },
  props: {
    data: String,
    msg: String,
  },
  methods: {
    hello() {
      this.show = !this.show;
    },
  },
  data() {
    return {
      users: [
        { id: 1, name: "nab", email: "nab@test.com" },
        { id: 2, name: "aab", email: "aab@test.com" },
        { id: 3, name: "bab", email: "bab@test.com" },
        { id: 4, name: "cab", email: "cab@test.com" },
        { id: 5, name: "dab", email: "dab@test.com" },
      ],
    };
  },
};
</script>
<style scoped>
.home {
  background-color: yellowgreen;
  height: 500px;
}
</style>
