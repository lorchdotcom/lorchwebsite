<template>
  <v-navigation-drawer app>
    <v-list>
      <v-list-item to="/">Home</v-list-item>
      <v-list-item to="/about">About</v-list-item>
      <v-list-item to="/dashboard">Dashboard</v-list-item>
    </v-list>
  </v-navigation-drawer>
</template>

<script>
export default {
  name: 'Sidebar',
};
</script>
