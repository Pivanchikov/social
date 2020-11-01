<template>
  <div class="Registration__page">
     <Header/>
      <div class="container flex">
        <Info/>
        <div class="aside">
          <Sign/>
          <StartRegistr/>
        </div>
      </div>
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Info from '@/components/RegistrationInfo.vue'
import Sign from '@/components/SignIn.vue'
import StartRegistr from '@/components/StartRegistr.vue'


export default {
  name: 'Registration',
  components: {
    Header,
    Info,
    Sign,
    StartRegistr,
  },
  data() {
    return {
      registration: true,
    }
  }
}


</script>


<style lang="scss">
@import "@/assets/style/registration.scss"
</style>