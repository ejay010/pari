<template>
<!-- Footer -->
<footer class="bg-black small text-center text-white-50">
  <div class="container">
    <div class="row d-flex justify-content-center">
      <div class="iCountUp">
        <p>
          <ICountUp :endVal="endVal" :options="options" @ready="onReady"></ICountUp> Visitors
        </p>
      </div>
    </div>
    Copyright &copy; P-ARI Foundation 2019
  </div>
</footer>
</template>

<script>
import ICountUp from 'vue-countup-v2';
export default {
  name: 'footer-counter',
  components: {
    ICountUp
  },
  data() {
    return {
      endVal: 120035,
      options: {
        useEasing: true,
        useGrouping: true,
        separator: ',',
        decimal: '.',
        prefix: '',
        suffix: ''
      }
    }
  },
  methods: {
    onReady: function(instance, CountUp) {
      const that = this;
      instance.update(that.endVal + 100)
    }
  }
}
</script>

<style scoped>
.iCountUp {
  color: white !important;
  font-size: 3em;
  margin: 0;
  color: #4d63bc;
}
</style>
