<template>
  <div id="app">
      <app-header></app-header>
      <router-view></router-view>
  </div>
</template>

<script>

import header from './components/Header.vue';

export default {
    name: 'App',
    components:{
        'app-header': header,
    },
}
</script>