<template>
  <div class="home" id="home">
    <b-container fluid>
      <b-row>
        <b-col>
          Home Page
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<style lang="scss">
@import "../assets/main.scss";
@import "../assets/variables.scss";

</style>

<script lang="ts">
import Vue from 'vue'
import HelloWorld from '@/components/HelloWorld.vue'

export default Vue.extend({
  name: 'home',
  components: {
    HelloWorld
  },
  data () {
  },
  methods: {
  }
})
</script>
