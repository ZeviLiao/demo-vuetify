<template>
  <div class="about">
    <h1 class="subheading grey--text">Team</h1>
    <v-container fluid class="my-5">
      <v-layout row wrap>
        <v-flex xs12 sm6 md4 lg3 v-for="person in team" :key="person.name">
          <v-card flat class="text-xs-center ma-3">
            <v-responsive class="pt-4">image goes here</v-responsive>
            <v-card-text>
              <div class="subheading">{{person.name}}</div>
              <div class="grey--text">{{person.name}}</div>
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>
  </div>
</template>

<script>
  export default {
      data(){
        return {
          team:[
            {name:'a', role:'aa'},
            {name:'a', role:'aa'},
            {name:'a', role:'aa'},
            {name:'a', role:'aa'},
            {name:'a', role:'aa'},
          ]
        }
      }
  }
</script>

<style lang="scss" scoped>

</style>
