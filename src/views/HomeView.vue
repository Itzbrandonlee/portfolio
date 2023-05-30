<template>
  
  <v-app id="home" :style="{ background: $vuetify.theme.themes.dark.background }">
    <NavBar />
    <v-container fluid>
      <v-row>
        <div id="header">
        <v-col cols="6">
          <h1 class="jobTitle">
            {Full-Stack</h1> <br />
              <h1 class="lineTwo"> Developer}
          </h1>
          <h5 class="top">brandon.zavala</h5>
          <p class="grey--text tagline">
            video games || technology || graphic design || photography
          </p>
        </v-col>
      </div>
        <v-col id="aboutme" cols="12" class="padd">
          <div class="first" id="about">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#F19953" x-large class="ml-3">
                    fa-solid fa-address-card
                  </v-icon>
                  <h3 class="white--text ml-3 mt-4">About Me</h3>
                  <p class="grey--text ml-3 mt-6">
                    Hi! My name is Brandon Zavala, retail management turned software developer. After 15 years in the retail industry I am ready to take the skills I have learned and work with others to create new and amazing things! As an avid problem solver, video game player and graphic arts and photography enthusiast, behind a screen is where I belong. I recently graduted from a software development bootcamp and I have learned amazing skills that have only ignited my passion for the subject. I am always looking for a new opportunity to learn and grow. If you interested in connecting with me, check out my contact information. Id love to connect! 
                  </p>
                  
                </div> 
                <div class="child bgColor2">
                  <v-icon x-large class="ml-3" dark>fa-sharp fa-solid fa-laptop</v-icon>
                  <h3 class="white--text ml-3 mt-4">Skills and Languages</h3>
                  
                    <table class="white--text">
                      <tr>
                        <td>
                          <ul>
                            <li>Java</li>
                            <li>Python</li>
                            <li>Javascript</li>
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>JSON</li>
                          </ul>
                        </td>
                        <td>
                          <ul>
                            <li>Spring Boot</li>
                            <li>React</li>
                            <li>Vue</li>
                            <li>Bootstrap</li>
                            <li>AWS</li>
                            <li>PostgreSql</li> 
                          </ul>
                        </td>
                      </tr>
                    </table>
                  

                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <h1 style="color: #F19953" class="text-darken-4 mt-4 number">15</h1>
                  <h3 class="white--text mt-4">Years Work Experience</h3>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 style="color: #F19953" class="text--darken-4">06</h1>
                        <p class="grey--text">Large Projects</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 style="color: #F19953" class="text--darken-4">800+</h1>
                        <p class="grey--text">Hours Coding Experience</p>
                      </div>
                      
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 style="color: #F19953" class="text--darken-4">04</h1>
                        <p class="grey--text">Certificates of Completion</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 style="color: #F19953" class="text--darken-4">05</h1>
                        <p class="grey--text">Coding Languages</p>
                      </div>
                      
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>

        
        <v-col md="3" offset-md="3" id="titlefeatured">
          <h4 class="white--text">FEATURES PROJECTS</h4>
        </v-col>
        <v-col md="3" class="text-end" id="github">
          <v-btn tile color="#48E5C2" dark href="https://github.com/Itzbrandonlee">View GitHub</v-btn>
        </v-col>
      
        
        <v-col md="3" offset-md="3" id="fitnessimg">
          <v-card class="pa-2 py-12" outlined tile height="20rem" color="#181818">
            <v-img src="./image2.png" contain > </v-img>
          </v-card>
        </v-col>
        
        <v-col md="3" id="fitnessdesc">
          <v-btn color="white" dark text class="ml-n4">
            Fitness Tracking Application
          </v-btn><br />
          <p class="grey--text">
            Full stack web application created on my own using react and a back-end with Java, spring boot and restAPIs. <br/>
              Functions: <br/>
              - Create a profile to track weight loss and gain <br/>
              - Browse workouts from external API using different search criteria<br/>
              - Log workouts <br/>
              - Browse and order workouts to view progress
          </p>
          <v-btn color="#48E5C2" dark text class="ml-n4" href="https://github.com/Itzbrandonlee/FitnessTracking-App">
            know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        
        <v-col md="3" offset-md="3" id="comicdesc">
          <v-btn color="white" dark text class="ml-n4">
            Comic Collection Application

          </v-btn><br />
          <p class="grey--text">
              Full stack web application written in Java with a front end written in Javascript, Vue, HTML and CSS. Used a PostgreSql DB to store users collection information. <br/>
              Functions: <br/>
              
              - Log in / out<br /> 
              - Register New account <br/>
              - Browse comic from external API<br/>
              - Store comics in personal made collections<br/>
              - View user and others collections
            </p>
          <v-btn color="#48E5C2" dark text class="ml-n4" href="https://github.com/Itzbrandonlee/ComicsRUs">
            know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3" id="comicimg">
          <v-card class="pa-2 py-12" outlined tile height="20rem" color="#181818">
            <v-img src="./image.png" contain> </v-img>
          </v-card>
        </v-col>
        
        


        <v-col id="contactme" cols="12" class="padd topInverse">
          <div class="second">
          <div class="secondchild1" id="contact">
                <h1 class="white--text">
                  Reach Out and Say Hello!
                </h1>
                <p class="grey--text">
                  Always looking for new opportunties to connect with my new community. Open to project collaborations, job opportunities, meetups or simply to say "Hello!" Hope to hear from you soon.
                </p>
              <v-col cols="5">
                <v-btn tile color="#F19953" dark class="mt-16" href="mailto:brandon.zavala1990@gmail.com">Contact </v-btn>
            </v-col>
          </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div style="position: absolute; margin-left: auto; margin-right: auto; left: 0; right: 0; text-align: center;">
              <v-btn text @click="scroll('home')">Home</v-btn>
              <v-btn text @click="scroll('projects')">Projects</v-btn>
              <v-btn text @click="scroll('about')">About</v-btn>
              <v-btn text @click="scroll('contact')">Contact</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <FooterBar id="footer" />
  </v-app>
  
</template>

<script>
  import NavBar from '../components/NavBar'
  import FooterBar from '../components/FooterBar'
  

  export default {
    name: 'HomeView',

    components: {
      NavBar,
      FooterBar,
      
    },
    methods: {
        scroll(refName) {
            const element = document.getElementById(refName);
            element.scrollIntoView({behavior: "smooth"});
        }
    }
  }
</script>

<style scoped>

#home {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
  gap: 20px;
  grid-template-areas: 
    "header header header header header header"
    ". about about about about about ."
    ". featured . . github ."
    ". fitimg fitimg fitdesc fitdesc ."
    ". comdesc comdesc comimg comimg ."
    ". . contact contact . . "
    "footer footer footer footer footer footer";
}
@media only screen and (max-width: 1024px) {
#home {
  height: 100%;
  width: 100%;
  grid-template-columns: 1fr 1fr;

  grid-template-areas: 
    "header header"
    "about about"
    "featured github "
    "fitimg fitdesc"
    "comdesc comimg"
    "contact contact"
    "footer footer";
}
}

@media only screen and (max-width: 768px){
#home {
  height: 100%;
  width: 100%;
  grid-template-columns: 1fr;
  grid-template-areas: 
    "header"
    "about"
    "featured"
    "github"
    "fitimg"
    "fitdesc"
    "comimg"
    "comdesc"
    "contact"
    "footer";
}
}

#titlefeatured {
  grid-area: featured;
  width: 100vw;
 
  
}

#github {
  grid-area: github;
  width: 100vw;
  
}
#fitnessdesc {
  grid-area: fitdesc;
  width: 100vw;

 
}

#fitnessimg {
  grid-area: fitimg;
  width: 100vw;
  
}

#comicdesc {
  grid-area: comdesc;
  width: 100vw;
  
}
#comicimg {
  grid-area: comimg;
  width: 100vw;
  
}

#header {
  grid-area: header;
  width: 100vw;
  
}

#aboutme {
  grid-area: about;
  width: 100vw;

  
}

#contactme {
  grid-area: contact;
  width: 100vw;
  
}

#footer {
  grid-area: footer;
  width: 100vw;
 
}
.top {
  margin-top: -8rem;
  margin-left: 27rem; 
}

.topInverse {
  margin-top: -16rem;
}

.topTolbar {
  
  text-align: center;
}

.first {
  width: 100%;
  height: 50rem;
  background: linear-gradient(
    to right,
    #111111,
    #111111 50%,
    #181818 50%,
    #181818 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}

.second {
  width: 100%;
  height: 23rem;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
  margin-top: 15rem;
}

.secondchild1 {
  display: inline-block;
  background-color: #181818;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: center;
}


.secondchild1 h1{
  margin-top: -3rem;
  margin-left: 3rem;
  font-size: 3rem;
}

.secondchild1 p {
  width: 50rem;
 margin-left: 5rem; 
 margin-top: 5rem;
}

.secondchild1 a {
  margin-left: 120%;
}


.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
  width: 40%;
  height: 100%;
  
}


.bgColor1 {
  background-color: #1e1e1e
}

.bgColor2 {
  background-color: #F19953;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 15rem;
  
}

.child2 {
  display: inline-block;
  width: 20rem;
  vertical-align: middle;
  
}

.mRight {
  margin-right: 8px;
}

.mButton {
  margin-bottom: 8px;
}

.padd {
  padding: 8px 0px;
}

.col-12.padd {
  padding: 12px 0 !important;
}

.col-12.childcol {
  padding: 0 !important;
}

h1.number {
  font-size: 50px;
  font-weight: bold;
}
h5 {
  color:#48E5C2;
  font-size: 5rem;
}

h1.jobTitle {
  font-size: 5rem;
  white-space: nowrap;
  margin-left: 12rem;
  color: #F19953
}

h1.lineTwo {
  font-size: 20rem;
  color: white;
  white-space: nowrap;
  margin-top: -13rem;
}

p.tagline {
  text-align: right;
  margin-top: -25px;
  font-size: 1rem;
}

li {
  margin-bottom: 5px;
  font-size: 16.5px;
  font-weight:bold;
}

ul {
  margin-right: 25rem;
  overflow-wrap: break-word;
}


</style>
