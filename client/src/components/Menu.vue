<template>
           <div class="main__navigation">
               <div class="main__navigation-list">
                   <ul>
                       <li><a href="/">Моя страница</a></li>
                       <li><a href="#">Мои друзья</a></li>
                       <li><a href="/message">Мои сообщения</a></li>
                       <li><a href="#">Мои группы</a></li>
                       <li><a href="#">Закладки</a></li>
                       <li><a href="/registration">Регистрация</a></li>
                   </ul>
               </div>
           </div>
</template>

<script>
export default {
    name: 'Menu',
}
</script>

<style scoped lang='scss'>
@import '~@/assets/style/components/menu.scss';
</style>