<template>
  <div>
    <form @submit.prevent="login">
      <input v-model="email" type="email" placeholder="Email" />
      <input v-model="password" type="password" placeholder="Password" />
      <button type="submit">Login</button>
    </form>
  </div>
</template>

<script lang="ts" setup>
const email = ref("email@email.text");
const password = ref("*******");
</script>
<style></style>
