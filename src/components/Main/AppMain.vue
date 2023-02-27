<script>
import FirstTry from './FirstTry.vue'
import SecondTry from './SecondTry.vue'
import ThirdTry from './ThirdTry.vue'
import FourthTry from './FourthTry.vue'
import FifthTry from './FifthTry.vue'
import SixthTry from './SixthTry.vue'
export default {
  name: 'AppMain',
  components:{
    FirstTry,
    SecondTry,
    ThirdTry,
    FourthTry,
    FifthTry,
    SixthTry,
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
    <FifthTry />
    <SixthTry />
  </div>
</template>

<style lang="scss" scoped>
</style>
