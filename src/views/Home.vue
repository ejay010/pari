<template>
<span>
  <headerview></headerview>
  <about></about>
  <projects></projects>
  <signup></signup>
  <contact></contact>
  <stepview></stepview>
  <moresteps></moresteps>
  <footerview></footerview>
</span>
</template>

<script>
// @ is an alias to /src
import headerview from "@/components/Header.vue";
import about from "@/components/About.vue";
import projects from "@/components/Projects.vue";
import signup from "@/components/Signup.vue";
import contact from "@/components/contact.vue";
import footerview from "@/components/footer.vue";
import stepview from "@/components/steps.vue";
import moresteps from "@/components/moresteps.vue";

export default {
  name: "home",
  components: {
    moresteps,
    headerview,
    about,
    projects,
    signup,
    contact,
    stepview,
    footerview
  }
};
</script>
