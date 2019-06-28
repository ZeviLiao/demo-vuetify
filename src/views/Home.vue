<template>
  <div class="home">
    <h1>This is an home page</h1>
    <v-btn class="pink white--text">click me</v-btn>
    <v-btn depressed color="pink">click me</v-btn>
    <v-btn flat color="pink">click me</v-btn>
    <v-btn depressed class="pink white--text">
      <v-icon left>email</v-icon>
      <span>eamil me</span>
    </v-btn>
    <v-btn depressed small class="pink white--text">
      <v-icon left small>email</v-icon>
      <span>eamil me</span>
    </v-btn>
    <v-btn depressed small class="pink white--text">
      <v-icon left small>email</v-icon>
      <span>eamil me</span>
    </v-btn>
    <v-btn fab depressed small dark class="purple">
      <v-icon>favorite</v-icon>
    </v-btn>
  </div>
</template>

<script>
export default {

}
</script>
