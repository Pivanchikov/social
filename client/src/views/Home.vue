<template>
  <div class="home">
    <Header/>
    <div class="container flex">
      <Menu/>
      <Profile/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Menu from '@/components/Menu.vue'
import Profile from '@/components/Profile.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Menu,
    Profile,
  }
}
</script>
