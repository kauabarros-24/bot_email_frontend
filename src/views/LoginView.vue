<template>
    <v-container>
      <v-form @submit.prevent="login">
        <v-text-field v-model="email" label="Email" required>Ol</v-text-field>
        <v-text-field v-model="password" label="Password" type="password" required></v-text-field>
        <v-btn type="submit">Login</v-btn>
      </v-form>
    </v-container>
  </template>
  
  <script>
  </script>
  