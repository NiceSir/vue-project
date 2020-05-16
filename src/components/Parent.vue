<template>
  <div id="parent">
      <Child :msg-a='msg'/>
  </div>
</template>

<script>
import Child from 'components/Child'
export default {
    data(){
        return{
            msg:'传递'
        }
    },

    components: {
        Child
    }
}
</script>

<style lang="scss" scoped>
$width:300px;
$height:300px;
#parent{
    width:$width;
    height:$height;
}
</style>