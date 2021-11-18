

<template>
  <div>
    <h1>App Shell</h1>
    <hello></hello>
   </div>
</template>
<script>
    import Hello from './components/HelloComponent.vue'
    export default {
      name: 'app',
      components: {
        Hello
      },
      data() {
        return {
          user: 'Tracy'
        }
      }
    }
</script>