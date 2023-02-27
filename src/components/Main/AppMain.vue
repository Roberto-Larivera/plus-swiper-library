<script>
import FirstTry from './FirstTry.vue'
import SecondTry from './SecondTry.vue'
export default {
  name: 'AppMain',
  components:{
    FirstTry,
    SecondTry,
  },
  data(){
    return{

    }
  }
  
}
</script>

<template>
  <div>
    <FirstTry />
    <SecondTry />
  </div>
</template>

<style lang="scss" scoped>
</style>
