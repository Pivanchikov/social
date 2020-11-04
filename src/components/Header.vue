<template>
  <div class="hello">
      <div class="about ">
        <div class="container flex">
            <div class="about__item flex">
                <a href="/">
                    <h1>DEEONE</h1>
                </a>
                <form action="">
                    <input type="search">
                    <input type="button" value="Найти">
                </form>
            </div>

            <div class="switch" v-if='!title'>
                <a href="#"> Друзья </a>|
                <a href="#"> Музыка </a>|
                <a href="#"> Видео </a>|
                <a href="#"> Выход </a>
            </div>
        </div>
  </div>

  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
      title: String,
  },
}
</script>


<style scoped lang="scss">
@import '~@/assets/style/components/header.scss';
</style>
