<template>
  <div>
    <navigator/>
    <router-view></router-view>
  </div>
</template>

<script>
import navigator from './components/navigator.vue'

export default {
  name: 'App',
  components: {
    navigator,
  }
}
</script>
