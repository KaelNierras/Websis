<template>
  <div class="register-form">
    <h2>Register</h2>
    <form @submit.prevent="submitForm">
      <div>
        <label for="username">Username</label>
        <input
          type="text"
          v-model="form.username"
          id="username"
          class="p-4"
          required
        />
      </div>
      <div>
        <label for="email">Email</label>
        <input type="email" v-model="form.email" id="email" required />
      </div>
      <div>
        <label for="password">Password</label>
        <input type="password" v-model="form.password" id="password" required />
      </div>
      <button type="submit">Register</button>
    </form>
    <p v-if="message">{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      form: {
        username: "",
        email: "",
        password: "",
      },
      message: "",
    };
  },
  methods: {
    submitForm() {
      if (this.form.username && this.form.email && this.form.password) {
        this.message = "Registration successful!";
      } else {
        this.message = "Please fill in all fields";
      }
    },
  },
};
</script>

<style scoped>
.register-form {
  max-width: 300px;
  margin: auto;
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 8px;
}
.register-form div {
  margin-bottom: 10px;
}
</style>
