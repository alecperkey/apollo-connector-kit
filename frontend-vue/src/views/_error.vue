<template>
  <div>
    <h1>We got an {{ status }} error code</h1>
    <p>Please, try again later</p>
    <a href="/">Home</a>
  </div>
</template>

<script>
// import { mapState, mapActions, mapMutations } from 'vuex';

export default {
  name: "Forbidden",
  props: {
    status: {
      type: String || Number,
      default: ""
    }
  }
};
</script>

<style scoped>
</style>
