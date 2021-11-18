<template>
   <h1>Hello {{ user }} from the hello component</h1>
</template>
<script>
   export default {
      name: 'hello',
      data() {
         return {
            user: 'Sean'
         }
      }

   }
</script>