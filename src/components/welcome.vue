<template>
  <div class="centered-content">
    <h1>Welcome to IE Bank</h1>
    <p>Feel free to check out this.</p>
    <router-link to="/accounts">Accounts</router-link>
    <br>
    <router-link to="/skull">Check out Skull</router-link>
  </div>
</template>

<style scoped>
.centered-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh; /* This makes the content take the full viewport height. */
  text-align: center;
}

.centered-content h1 {
  font-size: 36px;
  color: #333;
}

.centered-content p {
  font-size: 18px;
  color: #555;
  margin-top: 20px;
}
</style>
