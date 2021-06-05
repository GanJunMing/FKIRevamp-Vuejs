<template>
<div>
    <v-row>
    <v-card color="#8C9EFF"  width="300px" flat>
      <v-container>
        <v-list rounded>
          <v-list-item>
            <v-icon>{{programme}}</v-icon>
            <v-list-item-content>
              <v-list-item-title>--------Undergraduate--------</v-list-item-title>
            </v-list-item-content>
            <v-icon>{{programme}}</v-icon>
          </v-list-item>
          <v-list-item href="#/software">
            <v-list-item-content>
              <v-list-item-title>Software Engineering</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item href="#/network">
            <v-list-item-content>
              <v-list-item-title>Network Engineering</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item router-link to="/software">
             <v-list-item-content>Data Science</v-list-item-content>
          </v-list-item>
          <v-list-item link>
            <v-list-item-content>Multimedia</v-list-item-content>
          </v-list-item>
          <v-list-item link>
            <v-list-item-content>Business Computing</v-list-item-content>
          </v-list-item>
        </v-list>

        <v-list rounded>
          <v-list-item>
            <v-icon>{{graduate}}</v-icon>
            <v-list-item-content>
              <v-list-item-title>--------Postgraduate--------</v-list-item-title>
            </v-list-item-content>
            <v-icon>{{graduate}}</v-icon>
          </v-list-item>
          <v-list-item link>
            <v-list-item-content>
              <v-list-item-title>Master of Science (IT)</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item link>
            <v-list-item-content>
              <v-list-item-title>Master of Science (CS)</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item link>
             <v-list-item-content>Doctor of Philosophy (IT)</v-list-item-content>
          </v-list-item>
          <v-list-item link>
            <v-list-item-content>Doctor of Philosophy (CS)</v-list-item-content>
          </v-list-item>
        </v-list>
      </v-container>
    </v-card>
    <v-card color="#8C9EFF" width="1000px" fluid light>
      <v-container>

        <div class="software">
          <h2 style="text-align:center">Bachelor Of Computer Science with Honours in Software Engineering</h2>
          <v-img>
            <img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/code.jpg')" width="990px" height="300px">
          </v-img>
          <p class="text-justify">The programme aims to produce graduates with knowledge and skills in computer science and software engineering. 
            Students will be exposed to and trained in the fundamentals of computer systems as well as the advancement of technologies 
            in the field of computer science.</p>
          <p class="text-justify">The courses offered include computer programming, object-oriented programming, software quality and testing, human 
            computer interaction, theory of computation, operating system, artificial intelligence, final year project, to name a few.</p>
          <p class="text-justify">Apart from technical skills, students will be exposed to the soft skills through courses offered. In the final year, 
            students will involve in a computer software development project under the supervision of academic personnel. Their also need 
            to undergo industrial training during their final semester.</p>
          
        </div>
        <v-divider></v-divider>
        <div class="network">
          <p>Network Engineering</p>
        </div>
        </v-container>
    </v-card>
    </v-row>
</div>
</template>