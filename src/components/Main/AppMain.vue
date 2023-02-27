<script>
import FirstTry from './FirstTry.vue'
import SecondTry from './SecondTry.vue'
import ThirdTry from './ThirdTry.vue'
import FourthTry from './FourthTry.vue'
export default {
  name: 'AppMain',
  components:{
    FirstTry,
    SecondTry,
    ThirdTry,
    FourthTry,
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
    <ThirdTry />
    <FourthTry />
  </div>
</template>

<style lang="scss" scoped>
</style>
