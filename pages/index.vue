<template> <!--Can only contain one template block at a time for vue-loader-->
<div id="app">
  <TestMessage />
</div>
</template>

<script>
import TestMessage from '@/components/test-message'

export default {
  name: 'Index',
  components: { TestMessage }
};
</script>

<style lang ="scss" scoped>
/* write Sass here eventually*/
/*Scoped attribute means CSS will apply to elements of the current component ONLY*/
</style>