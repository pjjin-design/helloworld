<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      SWEN90013_YL
    </p>
    <h3>Front_End_Team</h3>
    <h3>Back_End_Team</h3>
    <h3>Dev_Ops_Team</h3>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
</style>
