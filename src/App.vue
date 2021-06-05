<template>
  <v-app>
    <v-navigation-drawer floating
      temporary
      class="mx-auto overflow-hidden"
      color="indigo lighten-1"
      v-model="drawer"
      width="256"
      app
      light
    >

    <v-img>
      <img src="../src/assets/fki.png" width="256px" alt="Logo">
    </v-img>

      <v-list rounded>
        <v-list-item router-link to="/">
          <v-list-item-action>
            <v-icon >mdi-home</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title >Home</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item router-link to="/programmes">
          <v-list-item-action>
            <v-icon>{{svgPath1}}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title>Programmes</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item router-link to="/event">
          <v-list-item-action>
            <v-icon>{{svgPath2}}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title>Event</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item router-link to="/news"> 
          <v-list-item-action>
            <v-icon>{{svgPath3}}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title>News</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        
        <v-list-item router-link to="/contact">
          <v-list-item-action>
            <v-icon>mdi-email</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title>Contact Us</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

      </v-list>
    </v-navigation-drawer>

    <v-app-bar
      app
      color="indigo lighten-1"
      flat
      light
      hide-on-scroll
    >
      <v-app-bar-nav-icon @click.stop="drawer = !drawer" bottom></v-app-bar-nav-icon>
      <img src="../src/assets/ums.png" height="55px">
      <v-toolbar-title>
        <h2 class="font-weight-light">Faculty Computer and Informatics</h2>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn icon>
        <v-icon color="#9FA8DA">{{ login }}</v-icon>
      </v-btn>
      <v-btn 
        elevation 
        color="indigo lighten-3" 
        rounded
        router-link to="/Login"
        >
        <span class="font-weight-light">Login / Register</span>
      </v-btn>
    </v-app-bar>

    <v-content>
      <v-container class="fill-height" fluid>
        <!-- <v-img>
          <img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/code.jpg')">
        </v-img> -->
        <v-row align="center" justify="center">
          <router-view></router-view>
        </v-row>
      </v-container>
    </v-content>
    
  </v-app>
</template>

<script>
  import {mdiAccount} from '@mdi/js'
  import { mdiCalendarClock } from '@mdi/js'
  import { mdiNewspaper } from '@mdi/js'
  import { mdiBookVariantMultiple } from '@mdi/js'

  export default {
    props: {
      source: String,
    },
    data: () => ({
      drawer: null,
      login: mdiAccount,
      svgPath1: mdiBookVariantMultiple,
      svgPath2: mdiCalendarClock,
      svgPath3: mdiNewspaper
    }),
  }
</script>