<template>
     <div class="header">
          <Jumbo />
     </div>
</template>

<script>
import Jumbo from './Jumbo'
     export default {
          name: 'Header',
          components: {
               Jumbo
          }
     }
</script>

<style scoped>
.header {
  width: 100%;
  min-height: 680px;
  background-color: rgba(13, 47, 129, 1);
  padding-top: 120px;
}
</style>