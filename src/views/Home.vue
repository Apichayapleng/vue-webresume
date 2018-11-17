<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <mainPage msg="Welcome to Your Vue.js + TypeScript App"/> -->
    <!-- <mainPage/> -->
    
    <div class="sidenav">
      <a href="#">about</a>
      <a href="#">edu</a>
      <a href="#">work</a>
      <a href="#">contact</a>
    </div>
    <div class="main">
      <div class="about">
        <p>I am fourth year student who interested in web frontend developer and ui/ux design. I am seeking for an co-operative or internship about 4-6 months periods</p>
      </div>
      <div class="edu">
        <p><br><br>King Mongkut's Institute of Technology Ladkrabang (KMITL)<br>
          4th year student, GPA 3.04<br>
          Bachelor of Science, International College,<br>
          Engineering and Technology Management<br><br>

          Poznan University of Economics<br>
          Summer School (one month period, July 2016)<br><br>

          Shigally Hill International Academy, India (2 years)<br><br>

          Sarasas Witead Rangsit School</p>
      </div>
      <div class="work">
        <p><br><br>Socket9<br>
          Web frontend developer<br>
          May 2017 - June 2017 (1 month)<br><br>

          Codium<br>
          Web frontend developer and designer<br>
          June 2018 - July 2017 (2 month)<br><br>
          </p>
      </div>
      <div class="contact">
        <p><br><br>apichayapg@gmail.com<br>
          098-4649892 <br><br> </p>
      </div>
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
    z-index: 1; /* Stay on top */
    top: 0; /* Stay at the top */
    right: 0;
    overflow-x: hidden; /* Disable horizontal scroll */
    // padding-top: 20px;
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