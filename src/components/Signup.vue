<!-- eslint-disable vue/multi-word-component-names -->
<!-- src/components/Signup.vue -->
<template>
  <div>
    <h2>Signup</h2>
    <form @submit.prevent="signup">
      <label>Email:</label>
      <input v-model="email" type="email" required />
      <label>Password:</label>
      <input v-model="password" type="password" required />
      <button type="submit">Signup</button>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      email: '',
      password: '',
    };
  },
  methods: {
    signup() {
      // Implement Firebase signup logic here
    },
  },
};
</script>

<style scoped>
/* Add your component styles here */
</style>
