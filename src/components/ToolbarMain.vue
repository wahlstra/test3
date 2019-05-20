<template>
  <div class= "toolbarMain">

      <v-toolbar app class="grey lighten-4">
        <v-toolbar-side-icon @click="drawer=!drawer">
        </v-toolbar-side-icon>

        <v-toolbar-items >
          <v-img :src="require('../assets/vom_logo_2a.png')" max-width="70" width="50" contain></v-img>
        </v-toolbar-items>
        <v-toolbar-title left class="text-uppercase grey--text">
          <span class="font-weight-light">Voice of The </span>
          <span>Machine </span>
        </v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn flat>
          <router-link to="/">Log out</router-link>
        </v-btn>
      </v-toolbar>
      <v-navigation-drawer v-model="drawer" app class="grey lighten-4">
        test
      </v-navigation-drawer>

  </div>

</template>

<script>
  export default{
    name: "toolbarMain",
    components: {


    },
    data() {
      return{
        drawer:false
      }
    }
  }


</script>
