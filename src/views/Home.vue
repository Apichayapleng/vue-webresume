<template>
  <div class="home">
    <div class="sidenav">
      <a href="#about" class>About</a>
      <a href="#edu" class>Education</a>
      <a href="#work" class>Experience</a>
      <a href="#contact" class>Contact</a>
    </div>
    <div class="main">
      <section class="section1" id="about">

      <div class="row">
        <!-- <b-row> -->
          <div class="col-6"><img src="../assets/profile.jpg" width="400px"></div>
          <div class="col-4">
            <h1>APICHAYA HUANGRAK</h1>
            
            <p>I am fourth year student who interested in web frontend developer and ui/ux design. I am seeking for an co-operative or internship about 4-6 months periods</p>
          </div>
        <!-- </b-row> -->
      </div>

        <!-- <img src="../assets/profile.jpg" width="300px">
        <p>I am fourth year student who interested in web frontend developer and ui/ux design. I am seeking for an co-operative or internship about 4-6 months periods</p> -->
      </section>
      <section class="section2" id="edu">
        <h2>EDUCATION</h2>
        <p><b>King Mongkut's Institute of Technology Ladkrabang (KMITL)</b><br>
          4th year student, GPA 3.04<br>
          Bachelor of Science, International College,<br>
          Engineering and Technology Management<br><br>

          <b>Poznan University of Economics</b><br>
          Summer School (one month period, July 2016)<br><br>

          <b>Shigally Hill International Academy, India (2 years)</b><br><br>

          <b>Sarasas Witead Rangsit School</b></p>
      </section>
      <section class="section3" id="work">
        <h2><br><br>WORK EXPERIENCE</h2>
        <p><b>Socket9</b><br>
          Web frontend developer<br>
          May 2017 - June 2017 (1 month)<br><br>

          Codium<br>
          Web frontend developer and designer<br>
          June 2018 - July 2017 (2 month)<br><br>
          </p>
      </section>
      <section class="section4" id="contact">
        <h2>CONTACT</h2>
        <p>apichayapg@gmail.com<br>
          098-4649892 <br><br> </p>
      </section>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import mainPage from '@/components/mainPage.vue' // @ is an alias to /src

@Component({
  components: {
  mainPage,
  },
  })
export default class Home extends Vue {}
</script>

<style scoped lang="scss">

.sidenav {
    height: 100%; /* Full-height: remove this if you want "auto" height */
    width: 160px; /* Set the width of the sidebar */
    position: fixed; /* Fixed Sidebar (stay in place on scroll) */
    // z-index: 0; /* Stay on top */
    // top: 0; /* Stay at the top */
    right: 0;
    overflow-x: hidden; /* Disable horizontal scroll */
    // padding-top: 20px;
    text-align: center;

}

/* The navigation menu links */
.sidenav a {
    padding: 6px 6px 6px 6px;
    text-decoration: none;
    font-size: 25px;
    color: #818181;
    display: block;
}

/* When you mouse over the navigation links, change their color */
.sidenav a:hover {
    color: black;
}

/* Style page content */
.main {
  padding-top: 20px;
    // margin-left: 0px; /* Same as the width of the sidebar */
    // padding: 0px 10px;
}

.home {
  background-color: #495E84;
  color: #F9E7D4;
}
</style>