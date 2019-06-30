<template>
  <v-app>
    <v-toolbar color="primary" fixed dark>
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-toolbar-title>vue</v-toolbar-title>
    </v-toolbar>
    <main>
      <v-container class="mt-4">
        <router-view></router-view>
      </v-container>
    </main>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      sidenav: false
    }
  }
}
</script>
