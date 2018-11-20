<template>
  <div class="home">
    <div class="sidenav">
      <a href="#about" class>about</a>
      <a href="#edu" class>edu</a>
      <a href="#work" class>work</a>
      <a href="#contact" class>contact</a>
    </div>
    <div class="main">
      <section class="section1" id="about">
        <img src="../assets/profile.jpg">
        <p>I am fourth year student who interested in web frontend developer and ui/ux design. I am seeking for an co-operative or internship about 4-6 months periods</p>
      </section>
      <section class="section2" id="edu">
        <p><br><br>King Mongkut's Institute of Technology Ladkrabang (KMITL)<br>
          4th year student, GPA 3.04<br>
          Bachelor of Science, International College,<br>
          Engineering and Technology Management<br><br>

          Poznan University of Economics<br>
          Summer School (one month period, July 2016)<br><br>

          Shigally Hill International Academy, India (2 years)<br><br>

          Sarasas Witead Rangsit School</p>
      </section>
      <section class="section3" id="work">
        <p><br><br>Socket9<br>
          Web frontend developer<br>
          May 2017 - June 2017 (1 month)<br><br>

          Codium<br>
          Web frontend developer and designer<br>
          June 2018 - July 2017 (2 month)<br><br>
          </p>
      </section>
      <section class="section4" id="contact">
        <p><br><br>apichayapg@gmail.com<br>
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
    // margin-left: 0px; /* Same as the width of the sidebar */
    // padding: 0px 10px;
}

</style>