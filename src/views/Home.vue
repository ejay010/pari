<template>
<span>
  <headerview></headerview>
  <about></about>
  <projects></projects>
  <signup></signup>
  <contact></contact>
  <stepview></stepview>
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

export default {
  name: "home",
  components: {
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
