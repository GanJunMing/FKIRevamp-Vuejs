<template>
  <div class="programme">
    <v-row>
    <v-card color="#8C9EFF"  width="300px" height="650px" grid-list-md>
      <v-container>
        <v-list rounded>
          <v-list-item>
            <v-icon>{{programme}}</v-icon>
            <v-list-item-content>
              <v-list-item-title>--------Undergraduate--------</v-list-item-title>
            </v-list-item-content>
            <v-icon>{{programme}}</v-icon>
          </v-list-item>
          <v-list-item href="#software">
            <v-list-item-content>
              <v-list-item-title>Software Engineering</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item href="#network">
            <v-list-item-content>
              <v-list-item-title>Network Engineering</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item href="#data">
             <v-list-item-content>Data Science</v-list-item-content>
          </v-list-item>
          <v-list-item href="#multimedia">
            <v-list-item-content>Multimedia Technology</v-list-item-content>
          </v-list-item>
          <v-list-item href="#business">
            <v-list-item-content>Business Computing</v-list-item-content>
          </v-list-item>
        </v-list>

        <v-divider></v-divider>

        <v-list rounded>
          <v-list-item>
            <v-icon>{{graduate}}</v-icon>
            <v-list-item-content>
              <v-list-item-title>--------Postgraduate--------</v-list-item-title>
            </v-list-item-content>
            <v-icon>{{graduate}}</v-icon>
          </v-list-item>
          <v-list-item href="#msc">
            <v-list-item-content>
              <v-list-item-title>Master of Science (CS)</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item href="#mscit">
            <v-list-item-content>
              <v-list-item-title>Master of Science (IT)</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item href="#phd">
             <v-list-item-content>Doctor of Philosophy (CS)</v-list-item-content>
          </v-list-item>
          <v-list-item href="#phdit">
            <v-list-item-content>Doctor of Philosophy (IT)</v-list-item-content>
          </v-list-item>
        </v-list>
      </v-container>
    </v-card>

    <v-divider></v-divider>

    <v-card color="#8C9EFF" width="1000px" fluid light>
      <v-container>
        <div class="software">
          <v-img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/master2.jpg')" height="500px">
          </v-img>
          <v-card hover>
            <div class="font-weight-black" style="font-size:30px; text-align:center">Bachelor of Computer Science with Honours in Software Engineering</div>
          </v-card>
          <!-- <v-carousel>
            <v-carousel-item
              v-for="(item,i) in items"
              :key="i"
              :src="item.src"
              reverse-transition="fade-transition"
              transition="fade-transition">
            </v-carousel-item>
          </v-carousel> -->

          <p></p>
          <p class="text-justify">The programme aims to produce graduates with knowledge and skills in computer science and software engineering. 
            Students will be exposed to and trained in the fundamentals of computer systems as well as the advancement of technologies 
            in the field of computer science.</p>
          <p class="text-justify">The courses offered include computer programming, object-oriented programming, software quality and testing, human 
            computer interaction, theory of computation, operating system, artificial intelligence, final year project, to name a few.</p>
          <p class="text-justify">Apart from technical skills, students will be exposed to the soft skills through courses offered. In the final year, 
            students will involve in a computer software development project under the supervision of academic personnel. Their also need 
            to undergo industrial training during their final semester.</p>
          
          <v-container align="center">
            <v-list width="500px" color="indigo lighten-5" dense>
            <v-list-item>
              <v-list-item-content>
                <h3 style="text-align:center">CAREER OPPORTUNITIES</h3>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Software Engineer</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Application Software</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">System Software</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Database Adminstrator</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Computer System Analyst</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Computer Support Specialist</span>
              </v-list-item-content>
            </v-list-item>
          </v-list>
          </v-container>
        </div>

        <v-divider></v-divider>

        <div id="network">
          <v-img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/network.jpg')" height="500px">
          </v-img>
          <v-card hover>
            <div class="font-weight-black" style="font-size:30px; text-align:center">Bachelor of Computer Science with Honours in Network Enginerring</div>
          </v-card>

          <p></p>
          <p class="text-justify">Bachelor of Computer Science  (Network Engineering) with Honours is an undergraduate degree programme offered by 
            Faculty of Computing and Informatics at Kota Kinabalu campus.</p>
          <p class="text-justify">Student will be exposed and trained with the fundamental concepts of computer science and computer network. 
            The offered courses in the programme are in line with the Cisco, IEEE and ACM computing syllabus.</p>
          <p class="text-justify">The courses include computer programming, system analysis and design, database, 
            network fundamentals, routing protocols, parallel and distributed computing, web technology, network security, 
            WAN technology and etc.</p>
          
          <v-container>
            <v-list width="500px" color="indigo lighten-5" dense>
            <v-list-item>
              <v-list-item-content>
                <h3 style="text-align:center">CAREER OPPORTUNITIES</h3>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Network Adminstrator</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Computer Network Architect</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Network Support Engineer</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Telecommunications Specialist</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">System Analyst / Engineer</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Application Developer</span>
              </v-list-item-content>
            </v-list-item>
          </v-list>
          </v-container>
        </div>

        <v-divider></v-divider>

        <div id="data">
          <v-img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/data.jpeg')" height="500px">
          </v-img>
          <v-card hover>
            <div class="font-weight-black" style="font-size:30px; text-align:center">Bachelor of Science with Honours in Data Science</div>
          </v-card>

          <p></p>
          <p class="text-justify">Bachelor of Science (Data Science) with Honours is an undergraduate degree program offered by the 
            Faculty of Computer and Informatics at the Kata Kinabalu campus.</p>
          <p class="text-justify">The purpose of the program is to produce skilled and capable graduates in the field of data science,
             in line with the rapid growth of industries that require the expertise of data scientists. Students will be exposed and trained 
             on the principles of computer science, science and analytics primarily in data mining, visualization techniques, predictive models, 
             and statistics.</p>
          <p class="text-justify">Among the courses offered include computer programming, data science basics, data visualization, 
            data analysis, data mining, analysis and system design for data science, and other programming languages.</p>
          
          <v-container>
            <v-list width="500px" color="indigo lighten-5" dense>
            <v-list-item>
              <v-list-item-content>
                <h3 style="text-align:center">CAREER OPPORTUNITIES</h3>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Data Scientist</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">System Database Development</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Mobile Application Design</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Web Development</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Business Intelligent</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Research-related Career</span>
              </v-list-item-content>
            </v-list-item>
          </v-list>
          </v-container>
        </div>

        <v-divider></v-divider>

        <div id="multimedia">
          <v-img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/multimedia.jpg')" height="500px"></v-img>
          <v-card hover>
            <div class="font-weight-black" style="font-size:30px; text-align:center">Bachelor of Science with Honours in Multimedia Technology</div>
          </v-card>

          <p></p>
          <p class="text-justify">Bachelor of Science (BSc) (Multimedia Technology) with Honours is an undergraduate degree programme offered 
            by Faculty of Computing and Informatics at Labuan International Campus.</p>
          <p class="text-justify">This programme will provide students with skills in the areas of interactive media, 
            graphics arts, audio technology, animation, video and publishing.</p>
          <p class="text-justify">Students will be exposed with the latest and widely utilised multimedia tools as well as programming languages. 
            This will enhance students’ techniques in design and develop multimedia application.</p>
          
          <v-container>
            <v-list width="500px" color="indigo lighten-5" dense>
            <v-list-item>
              <v-list-item-content>
                <h3 style="text-align:center">CAREER OPPORTUNITIES</h3>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Computer Animator</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Video Specialist</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Database Designer</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Web Designer</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Database Designer</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Computer Graphic Designer</span>
              </v-list-item-content>
            </v-list-item>
          </v-list>
          </v-container>
        </div>

        <v-divider></v-divider>

        <div id="business">
          <v-img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/ecommerce.jpg')" height="500px"></v-img>
          <v-card hover>
            <div class="font-weight-black" style="font-size:30px; text-align:center">Bachelor of Information Technology with Honours in Business Computing</div>
          </v-card>

          <p></p>
          <p class="text-justify">Bachelor of Information Technology (BIT) (Business Computing) with Honours  is an
             undergraduate degree programme offered by Faculty of Computing and Informatics at Labuan International Campus.</p>
          <p class="text-justify">Students will be exposed with business computing operation through presentation tier, business tier and database access.</p>
          <p class="text-justify">This degree pogram will emphasises instruction in computer literacy, Business Computing web development, programming and internet marketing. This program follows the currents environment on business computing technologies.</p>
          
          <v-container>
            <v-list width="500px" color="indigo lighten-5" dense>
            <v-list-item>
              <v-list-item-content>
                <h3 style="text-align:center">CAREER OPPORTUNITIES</h3>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Web Designer</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Video Specialist</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Database Designer</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Interface Designer</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Business analyst</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:center">Computer Graphic Designer</span>
              </v-list-item-content>
            </v-list-item>
          </v-list>
          </v-container>
        </div>

        <v-divider></v-divider>
        <div id="msc">
          <v-img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/code.jpg')" height="500px"></v-img>
          <v-card hover>
            <div class="font-weight-black" style="font-size:30px; text-align:center">Master of Science (CS)</div>
          </v-card>

          <p></p>
          <h3 class="text-center">Research Areas for Computer Science</h3>
          <p class="text-justify">Nature-inspired Computational Intelligence, Evolutionary Robotics, Behavior-Based Robotics, 
            Artificial Neural Networks, Evolving Game AI, Multi-Objective Optimization and Metaheuristics, Agent Technology, 
            Semantic Technology, Natural Language Processing, Image Processing, Sentiment Analysis, Augmented Reality, Neuroinformatics</p>
          <v-container>
            <v-list width="950px" color="indigo lighten-5" dense>
            <v-list-item>
              <v-list-item-content>
                <h3 style="text-align:center">Requirement</h3>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Bachelor of Science degree in Computer Science/Information Technology or its equivalent with a minimum CGPA of 2.75; </span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Bachelor of Science degree in Computer Science/Information Technology or its equivalent with a minimum CGPA of 2.50 may be accepted subject to rigorous internal assessment; </span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Bachelor of Science degree in Computer Science/Information Technology or its equivalent with CGPA less than 2.50 may be accepted provided that the applicant has at least five (5) years of direct working experience in the ICT industry</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Bachelor of Science degree or its equivalent in any field other than Computer Science/Information Technology with a minimum CGPA of 3.00 may be accepted provided that the applicant has taken all prerequisite modules in computing;</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">Diploma/STPM or its equivalent provided that the applicant has at least five (5) years of direct working experience in the ICT industry AND passed the APEL T-7 assessment</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">Fulfill other requirements as set by the Senate: Degrees awarded by local/private institutions of higher learning, including those awarded under any collaborative/franchising schemes with local or foreign partners must be accredited by the Malaysian Qualifications Agency (MQA)</span>
              </v-list-item-content>
            </v-list-item>
          </v-list>
          </v-container>
        </div>

        <v-divider></v-divider>

        <div id="mscit">
          <v-img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/master.jpg')" height="500px"></v-img>
          <v-card hover>
            <div class="font-weight-black" style="font-size:30px; text-align:center">Master of Science (IT)</div>
          </v-card>

          <p></p>
          <h3 class="text-center">Research Areas for Computer Science</h3>
          <p class="text-justify">Information Systems, ICT for Development, Knowledge Management, ICT Research Methodology, 
            Enterprise Systems, Action Research, Human Computer Interaction, Web Development Usability, Intelligent Knowledge-based Systems, 
            Information Visualisation, Web Engineering, E-commerce</p>
          <v-container>
            <v-list width="950px" color="indigo lighten-5" dense>
            <v-list-item>
              <v-list-item-content>
                <h3 style="text-align:center">Requirement</h3>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Bachelor of Science degree in Computer Science/Information Technology or its equivalent with a minimum CGPA of 2.75; </span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Bachelor of Science degree in Computer Science/Information Technology or its equivalent with a minimum CGPA of 2.50 may be accepted subject to rigorous internal assessment; </span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Bachelor of Science degree in Computer Science/Information Technology or its equivalent with CGPA less than 2.50 may be accepted provided that the applicant has at least five (5) years of direct working experience in the ICT industry</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Bachelor of Science degree or its equivalent in any field other than Computer Science/Information Technology with a minimum CGPA of 3.00 may be accepted provided that the applicant has taken all prerequisite modules in computing;</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">Diploma/STPM or its equivalent provided that the applicant has at least five (5) years of direct working experience in the ICT industry AND passed the APEL T-7 assessment</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">Fulfill other requirements as set by the Senate: Degrees awarded by local/private institutions of higher learning, including those awarded under any collaborative/franchising schemes with local or foreign partners must be accredited by the Malaysian Qualifications Agency (MQA)</span>
              </v-list-item-content>
            </v-list-item>
          </v-list>
          </v-container>
        </div>

        <v-divider></v-divider>

        <div id="phd">
          <v-img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/phd.png')" height="500px"></v-img>
          <v-card hover>
            <div class="font-weight-black" style="font-size:30px; text-align:center">Doctor of Philosophy (CS)</div>
          </v-card>

          <p></p>
          <h3 class="text-center">Research Areas for Computer Science</h3>
          <p class="text-justify">Nature-inspired Computational Intelligence, Evolutionary Robotics, Behavior-Based Robotics, 
            \Artificial Neural Networks, Evolving Game AI, Multi-Objective Optimization and Metaheuristics, Agent Technology, 
            Semantic Technology, Natural Language Processing, Image Processing, Sentiment Analysis, Augmented Reality, Neuroinformatics</p>
          <v-container>
            <v-list width="950px" color="indigo lighten-5" dense>
            <v-list-item>
              <v-list-item-content>
                <h3 style="text-align:center">Requirement</h3>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Master’s degree in Computer Science/Information Technology or its equivalent from any IPT approved by the Senate</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Master’s degree or its equivalent in any field other than Computer Science/Information Technology may be accepted provided that the applicant has a Bachelor of Science degree in Computer Science/Information Technology and taken all prerequisite modules in computing</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">Candidates who are registered as Master candidates at the Universiti Malaysia Sabah and have obtained approval to upgrade by the Faculty’s Postgraduate Committee and approved by the Senate</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">Fulfill other requirements as set by the Senate: Degrees awarded by local/private institutions of higher learning, including those awarded under any collaborative/franchising schemes with local or foreign partners must be accredited by the Malaysian Qualifications Agency (MQA)</span>
              </v-list-item-content>
            </v-list-item>
          </v-list>
          </v-container>
        </div>

        <v-divider></v-divider>

        <div id="phdit">
          <v-img :src="require('D:/Sem 6/Human Computer Interactive/fkiweb/src/assets/phd2.png')" height="500px"></v-img>
          <v-card hover>
            <div class="font-weight-black" style="font-size:30px; text-align:center">Doctor of Philosophy (IT)</div>
          </v-card>

          <p></p>
          <h3 class="text-center">Research Areas for Computer Science</h3>
          <p class="text-justify">Information Systems, ICT for Development, Knowledge Management, ICT Research Methodology, Enterprise Systems, 
            Action Research, Human Computer Interaction, Web Development Usability, Intelligent Knowledge-based Systems, Information Visualisation, 
            Web Engineering, E-commerce.</p>
          <v-container>
            <v-list width="950px" color="indigo lighten-5" dense>
            <v-list-item>
              <v-list-item-content>
                <h3 style="text-align:center">Requirement</h3>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Master’s degree in Computer Science/Information Technology or its equivalent from any IPT approved by the Senate</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">A Master’s degree or its equivalent in any field other than Computer Science/Information Technology may be accepted provided that the applicant has a Bachelor of Science degree in Computer Science/Information Technology and taken all prerequisite modules in computing</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">Candidates who are registered as Master candidates at the Universiti Malaysia Sabah and have obtained approval to upgrade by the Faculty’s Postgraduate Committee and approved by the Senate</span>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <span style="text-align:justify">Fulfill other requirements as set by the Senate: Degrees awarded by local/private institutions of higher learning, including those awarded under any collaborative/franchising schemes with local or foreign partners must be accredited by the Malaysian Qualifications Agency (MQA)</span>
              </v-list-item-content>
            </v-list-item>
          </v-list>
          </v-container>
        </div>
      </v-container>
    </v-card>
    </v-row>
  </div>
</template>

<script>
import { mdiBookVariantMultiple } from '@mdi/js'
import { mdiSchool } from '@mdi/js'

export default {
    props: {
      source: String,
    },
data: () => ({
  programme: mdiBookVariantMultiple,
  graduate: mdiSchool,
})
}
</script>