<template>
  <div class="component">
    <h2>{{ message }}</h2>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        message: 'The key to pursuing excellence is to embrace an organic long term learning process, and not live in a shell of static safe mediocrity. - Josh Waitzkin'
      }
    }
  }
</script>

<style scoped>
  .component {
    background: #e8e8e8;
    min-height: 400px;
  }
</style>