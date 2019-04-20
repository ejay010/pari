<template>
<div id="app">
  <navigation></navigation>

  <headerview></headerview>
  <about></about>
  <projects></projects>
  <signup></signup>
  <stepview></stepview>
  <moresteps></moresteps>
  <contact></contact>
  <footerview></footerview>
</div>
</template>

<style lang="scss">
@import '@/assets/scss/grayscale.scss';
@import url('https://fonts.googleapis.com/css?family=Montserrat:700|Playfair+Display+SC:900|Roboto:900');
#app {
    font-family: "Montserrat", Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    // text-align: center;
    color: #2c3e50;
    min-width: 100%;
}
#nav {
    padding: 30px;
    a {
        font-weight: bold;
        color: #2c3e50;
        &.router-link-exact-active {
            color: #42b983;
        }
    }
}
.color1 {
    color: #F3F700 !important; //yellow
}
.color2 {
    color: #F29202;
}
.color3 {
    color: #32F202;
}
</style>

<script>
import navigation from "@/components/Navigation.vue"
import headerview from "@/components/Header.vue";
import about from "@/components/About.vue";
import projects from "@/components/Projects.vue";
import signup from "@/components/Signup.vue";
import contact from "@/components/contact.vue";
import footerview from "@/components/footer.vue";
import stepview from "@/components/steps.vue";
import moresteps from "@/components/moresteps.vue";

export default {
  name: "app",
  components: {
    moresteps,
    navigation,
    headerview,
    about,
    projects,
    signup,
    stepview,
    contact,
    footerview
  }
}
</script>
