<template>
  <div class="about">
      <Header/>
      <div class="container flex">
          <Menu/>
          <MessageBox/>
      </div>
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Menu from '@/components/Menu.vue'
import MessageBox from '@/components/MessageBox.vue'

export default {
    name: 'MessageViews',
    components: {
        Header,
        Menu,
        MessageBox,
    },
}
</script>