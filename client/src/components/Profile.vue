<template>
    <div class="main__info flex">
               <img src="../assets/cat.jpg" alt="photo" 
               width="250px" height="200px">
               <div class="main__about">
                   <div class="name"><strong>Павел Иванчиков</strong></div>
                   <hr>
                   <div class="age"><span>Дата рождения: </span>19.12.1995</div>
                   <div class="town"><span>Город: </span>Гомель</div>
                   <div class="sp"><span>Семейное положение: </span>Не женат</div>
                    <div class="wall">
                       <Wall/>
                    </div>
               </div>
           </div>
</template>

<script>
import Wall from '@/components/wall.vue'
export default {
    name: 'profile',
    components: {
        Wall,
        }
}
</script>

<style scoped lang="scss">
@import '~@/assets/style/components/profile.scss';
@import '@/assets/style/components/wall.scss';
</style>