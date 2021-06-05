<template>
  <div class="home" app>
    <p class="font-weight-light" style="text-align:center; font-size:30px">Welcome to Faculty Computer and Informatics</p>
    <v-carousel>
      <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
        reverse-transition="fade-transition"
        transition="fade-transition">
      </v-carousel-item>
    </v-carousel>
    <p></p>

    <h1 style="text-align:center">ABOUT US</h1>
    <p class="font-italic" style="text-align:center">FACULTY COMPUTER AND INFORMATICS</p>
    
    <v-container>
      <p class="text-justify">Faculty of Computing and Informatics (FCI) formerly known as Labuan School of Informatics Science (LSIS) was established in May 1999, 
        offering programmes in the field of computing and information technology. In October 2003 Universiti Malaysia Sabah was recognised by 
        Multimedia Development Corporation (MDeC) for ICT- facilitated business that develop or use multimedia technologies to produce and enhance 
        their products and services (quality graduates).</p>
      <v-row>
        <v-img style="text-align:center">
          <img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/25.png')" height="230px" alt="logo">
        </v-img>
        <v-list>
          <v-list-item>
            <v-row style="text-align:center">
              <v-icon>{{course}}</v-icon>
              <p>--------------------------The program offered under FCI---------------------------</p>
              <v-icon>{{course}}</v-icon>
            </v-row>
          </v-list-item>
          <v-list-item-title>Bachelor of Computer Science (Software Engineering) With Honour</v-list-item-title>
          <v-list-item-title>Bachelor of Computer Science (Network Engineering) With Honour</v-list-item-title>
          <v-list-item-title>Bachelor of Computer Science(Data Science) With Honour</v-list-item-title>
          <v-list-item-title>Bachelor of Science (Multimedia Technology) With Honour</v-list-item-title>
          <v-list-item-title>Bachelor of Information Technology (Business Computing) With Honour</v-list-item-title>
        </v-list>
      </v-row>
      <p class="text-justify">The growth in information technology amd computing has been regards as a pivotal element within the everyday activities. Therefore it is 
        imperative for such knowledge to be masters in the dissemination of information, thus realising the merged role of information and communication 
        technology towards a borderless world.</p>
    </v-container>
  </div>
</template>

<script>
import { mdiSchool } from '@mdi/js'
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  // name: 'Home',
  // components: {
    
  // },
  props: {
        source: String,
  },
  data:() =>({
    course: mdiSchool,
    items: [
      {
        src: require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/umskk.jpg'),
      },
      {
        src: require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/fki1.jpg'),
      },
      {
        src: require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/fkil.jpg'),
      },
      {
        src: require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/umskk2.jpg'),
      },
    ]
  })
}
</script>
