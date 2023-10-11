<template>
    <div>
      <h1>Welcome to My Vue App</h1>
      <p>This is a simple welcome message.</p>
      <router-link to="/accounts">Accounts</router-link>
      <router-link to="/skull">Check out Skull</router-link>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Welcome',
  };
  </script>
  