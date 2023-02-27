<script>
import FirstTry from './FirstTry.vue'
import SecondTry from './SecondTry.vue'
import ThirdTry from './ThirdTry.vue'
import FourthTry from './FourthTry.vue'
import FifthTry from './FifthTry.vue'
import SixthTry from './SixthTry.vue'
import SeventhTry from './SeventhTry.vue'
export default {
  name: 'AppMain',
  components:{
    FirstTry,
    SecondTry,
    ThirdTry,
    FourthTry,
    FifthTry,
    SixthTry,
    SeventhTry,
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
    <SeventhTry />
  </div>
</template>

<style lang="scss" scoped>
</style>
