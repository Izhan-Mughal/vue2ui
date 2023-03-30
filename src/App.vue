<template>
  <div id="app">

    <router-view/>
  </div>
</template>

<script>

export default {
  name: 'App',
  methods: {
  getFoo() {
    $( "div.foo" ).html();
  }
}
}

</script>

<style>
@import 'bootstrap/dist/css/bootstrap.css';

</style>