<template>
  <div id="app">
    <m-head></m-head>
    <router-view/>
  </div>
</template>

<script>
import mHead from '@/components/m-head/m-head'
export default {
  name: 'App',
  components : {
    mHead
  }
}
</script>

<style>
#app {

}
</style>
