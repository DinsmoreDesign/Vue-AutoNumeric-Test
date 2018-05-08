<template>

  <div id="app">
    
    <vue-autonumeric
      id="inputToEmpty"
      options="euro"
      v-model="emptyValue"
      placeholder="Enter your value here"
    />

  </div>

</template>




<script>

  import VueAutonumeric from 'vue-autonumeric';

  export default {

    name: 'app',
    components: {
			VueAutonumeric
		},
    data () {
      return {
        emptyValue: ''
      }
    }

  }

</script>




<style lang="scss">



</style>
