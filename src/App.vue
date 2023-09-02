<template>
  <div id="app">
    <CV/>
  </div>
</template>

<script>
import CV from './components/Resume.vue'

export default {
  name: 'App',
  components: { CV: CV }
}
</script>