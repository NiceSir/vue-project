<template>
  <div id="child">
      {{msgA}}
  </div>
</template>

<script>
export default {
    props: {
        msgA:    
        {
            type: String,
            required: true
         }
    }
};
</script>

<style>
</style>